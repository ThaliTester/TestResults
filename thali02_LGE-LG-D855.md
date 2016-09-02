#### Test 83268893e6b65d6_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
09-02 15:26:29.184  2132  2132 I CloudHub: [CLIENT][CloudHubClientFactory$1|onFinish] Time is up to exit
09-02 15:26:29.191  2132  2132 I CloudHub: [CLIENT][CloudHubClientFactory$1|onFinish] Scheduler destroyed
,09-02 15:26:52.563  6863  6863 D AndroidRuntime: 
09-02 15:26:52.563  6863  6863 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
09-02 15:26:52.570  6863  6863 D AndroidRuntime: CheckJNI is OFF
09-02 15:26:52.772  6863  6863 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-02 15:26:52.783  1043  1060 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-02 15:26:52.799  1928  2902 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
09-02 15:26:52.805  1043  1060 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
09-02 15:26:52.807  1043  1060 D ActivityManager: setTaskToReturnTo : TaskRecord{944a54a #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
09-02 15:26:52.807  1043  1060 D ActivityManager: setTaskToReturnTo : TaskRecord{944a54a #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
09-02 15:26:52.809  1043  1060 D WindowStateEx: AppWindowTokenEx init.. 
09-02 15:26:52.810   337   344 E GBMv2   : DFP En is all cleared set to be enabled
09-02 15:26:52.837  1043  1060 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6878 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
09-02 15:26:52.839  6863  6863 D AndroidRuntime: Shutting down VM
09-02 15:26:52.903  1928  1944 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
09-02 15:26:52.903  1928  1944 D SplitWindowPolicy: topRunningActivity=ActivityInfo{8729990 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
09-02 15:26:52.904  1928  1943 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
09-02 15:26:52.904  1928  1943 D SplitWindowPolicy: topRunningActivity=ActivityInfo{18f57289 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
09-02 15:26:52.960  6878  6878 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
09-02 15:26:53.032  6878  6878 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,09-02 15:26:53.041  6878  6878 I LibraryLoader: Loading: webviewchromium
09-02 15:26:53.051  6878  6878 I LibraryLoader: Time to load native libraries: 11 ms (timestamps 6313-6324)
09-02 15:26:53.052  6878  6878 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-02 15:26:53.085  6878  6878 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2f87e5be}
,09-02 15:26:53.087  6878  6878 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-02 15:26:53.087  6878  6878 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
09-02 15:26:53.100  6878  6878 I BrowserStartupController: Initializing chromium process, renderers=0
,09-02 15:26:53.101  6878  6878 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-02 15:26:53.117  6878  6878 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,09-02 15:26:53.118  6878  6878 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
09-02 15:26:53.119  6878  6878 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
09-02 15:26:53.128   308   308 V AudioPolicyService: registerClient() client 0xb558a720, uid 10118
09-02 15:26:53.137  1043  1119 D BluetoothManagerService: Message: 20
09-02 15:26:53.137  1043  1119 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@23a80784:true
,09-02 15:26:53.138  6878  6878 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-02 15:26:53.138  6878  6878 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-02 15:26:53.138  6878  6878 I Adreno-EGL: Build Date: 12/12/14 금
09-02 15:26:53.138  6878  6878 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-02 15:26:53.138  6878  6878 I Adreno-EGL: Remote Branch: 
09-02 15:26:53.138  6878  6878 I Adreno-EGL: Local Patches: 
09-02 15:26:53.138  6878  6878 I Adreno-EGL: Reconstruct Branch: 
09-02 15:26:53.231  6878  6917 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,09-02 15:26:53.240  6878  6878 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
09-02 15:26:53.257  6878  6878 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-02 15:26:53.267  6878  6878 W AwContents: onDetachedFromWindow called when already detached. Ignoring
09-02 15:26:53.271  6878  6878 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
,09-02 15:26:53.275  6878  6878 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
09-02 15:26:53.275  6878  6878 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
09-02 15:26:53.292  6878  6878 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,09-02 15:26:53.300  6878  6878 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-02 15:26:53.300  6878  6878 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-02 15:26:53.337  6878  6933 D OpenGLRenderer: Render dirty regions requested: true
09-02 15:26:53.337  6878  6933 I OpenGLRenderer: Initialized EGL, version 1.4
,09-02 15:26:53.345  6878  6933 D OpenGLRenderer: Enabling debug mode 0
09-02 15:26:53.355  6878  6878 D Atlas   : Validating map...
,09-02 15:26:53.359  1043  1979 D SplitWindow: check instance of lgWin Window{3b10889e u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-02 15:26:53.419  6878  6931 D LgDataFeature: LgDataFeature() Constructor: none
09-02 15:26:53.420  6878  6931 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-02 15:26:53.435  6878  6878 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@144f3fa5 time:166708
,09-02 15:26:53.460  1043  1120 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +557ms (total +648ms)
09-02 15:26:53.461  1043  1120 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3dd31cbb u0 com.test.thalitest/.MainActivity t6} time:166734
09-02 15:26:53.587  6878  6878 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-02 15:26:53.676  6878  6931 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
09-02 15:26:53.676  6878  6931 I chromium: 
,09-02 15:26:53.818  6878  6945 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435060736
,09-02 15:26:53.834  6878  6945 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-02 15:26:53.834  6878  6945 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-02 15:26:53.834  6878  6945 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-02 15:26:53.834  6878  6945 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-02 15:26:53.834  6878  6945 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-02 15:26:53.834  6878  6945 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ea5e359 added. We now have 1 listener(s),
,09-02 15:26:53.837  6878  6878 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
09-02 15:26:53.837  6878  6878 I chromium: 
09-02 15:26:53.840  1043  1562 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 15:26:53.843  6878  6945 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
09-02 15:26:53.844  6878  6945 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-02 15:26:53.846  6878  6945 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 15:26:53.846  6878  6945 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-02 15:26:53.855  6878  6945 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-02 15:26:53.855  6878  6945 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-02 15:26:53.855  6878  6945 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-02 15:26:53.855  6878  6945 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
09-02 15:26:53.855  6878  6945 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-02 15:26:53.855  6878  6945 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-02 15:26:53.855  6878  6945 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-02 15:26:53.855  6878  6945 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-02 15:26:53.855  6878  6945 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-02 15:26:53.855  6878  6945 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-02 15:26:53.855  6878  6945 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-02 15:26:53.855  6878  6945 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-02 15:26:53.855  6878  6945 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-02 15:26:53.855  6878  6945 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-02 15:26:53.855  6878  6945 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7b841cc added. We now have 1 listener(s)
09-02 15:26:53.856  6878  6945 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 15:26:53.861  1043  1429 D WifiService: New client listening to asynchronous messages
,09-02 15:26:53.865  6878  6945 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-02 15:26:53.865  6878  6945 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-02 15:26:53.866  6878  6945 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-02 15:26:53.866  6878  6945 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-02 15:26:53.866  6878  6945 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
09-02 15:26:53.870  6878  6945 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 15:26:53.870  1043  1962 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 15:26:53.872  6878  6945 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
,09-02 15:26:53.884  6878  6945 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
09-02 15:26:53.884  6878  6945 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 15:26:53.884  6878  6945 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 15:26:53.884  6878  6945 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 15:26:53.884  6878  6945 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 15:26:53.884  6878  6945 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 15:26:53.884  6878  6945 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 15:26:53.884  6878  6945 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 15:26:53.884  6878  6945 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-02 15:26:53.885  6878  6945 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-02 15:26:53.885  6878  6945 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-02 15:26:53.889  6878  6878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 15:26:53.891  6878  6878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 15:26:53.892  6878  6945 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-02 15:26:53.929  6878  6878 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-02 15:26:54.596   337   346 E GBMv2   : DFP En is all cleared set to be enabled
09-02 15:26:54.597   337   346 E GBMv2   : Set value is all cleared set the max
,09-02 15:26:54.597   337   346 I GBMv2   : DFP Enabled. Ignore VFP set
,09-02 15:26:55.056  6878  6948 W jxcore-log: Initializing JXcore engine
09-02 15:26:55.057  6878  6948 W jxcore-log: JXcore engine is ready
,09-02 15:26:55.125  6948  6948 W Thread-807: type=1400 audit(0.0:162): avc: denied { ioctl } for path="socket:[8341]" dev="sockfs" ino=8341 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,09-02 15:26:55.125  6948  6948 W Thread-807: type=1400 audit(0.0:163): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
09-02 15:26:55.125  6948  6948 W Thread-807: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[8490]" dev="sockfs" ino=8490 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
09-02 15:26:55.125  6948  6948 W Thread-807: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
09-02 15:26:55.125  6948  6948 W Thread-807: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[32163]" dev="sockfs" ino=32163 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
09-02 15:26:55.157  6878  6948 W jxcore-log: Starting JXcore engine
,09-02 15:26:55.265  6878  6948 W jxcore-log: Platform android
09-02 15:26:55.265  6878  6948 W jxcore-log: 
09-02 15:26:55.265  6878  6948 W jxcore-log: Process ARCH arm
09-02 15:26:55.265  6878  6948 W jxcore-log: 
,09-02 15:26:55.675  6878  6948 I jxcore-log: JXcore Cordova bridge is ready!
09-02 15:26:55.675  6878  6948 I jxcore-log: 
09-02 15:26:55.676  6878  6948 W jxcore-log: JXcore engine is started
,09-02 15:26:55.689  6878  6945 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-02 15:26:55.696  6878  6878 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
09-02 15:27:00.046  1589  1589 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-02 15:27:00.046  1589  1589 I KeyguardUpdateMonitor: called onTimeUpdated()
09-02 15:27:00.047  1589  1589 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
09-02 15:27:00.047  1589  1589 I [SystemUI]Clock: called onTimeUpdated()
,09-02 15:27:00.052  1589  1589 I LgeClockWidgetControlView: called onTimeUpdated()
09-02 15:27:00.052  1589  1589 I [SystemUI]DateView: called onTimeUpdated()
09-02 15:27:00.054  1589  1589 I [SystemUI]DateView: called onTimeUpdated()
09-02 15:27:00.054  1589  1589 D KeyguardUpdateMonitor: handleTimeUpdate
,09-02 15:27:08.572  6878  6948 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-02 15:27:08.572  6878  6948 I jxcore-log: 
09-02 15:27:08.574  6878  6948 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-02 15:27:08.574  6878  6948 I jxcore-log: 
,09-02 15:27:08.577  6878  6948 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 15:27:08.577  6878  6948 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 15:27:08.577  6878  6948 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 15:27:08.577  6878  6948 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 15:27:08.577  6878  6948 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 15:27:08.577  6878  6948 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 15:27:08.577  6878  6948 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 15:27:08.577  6878  6948 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-02 15:27:08.579  6878  6948 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-02 15:27:08.581  6878  6948 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-02 15:27:08.581  6878  6948 I jxcore-log: 
09-02 15:27:08.583  6878  6948 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-02 15:27:08.583  6878  6948 I jxcore-log: 
09-02 15:27:09.082  6878  6948 D executeNativeTests: Running unit tests
,09-02 15:27:09.163  6878  6948 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-02 15:27:09.163  6878  6948 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a0bb1e9 added. We now have 2 listener(s)
09-02 15:27:09.163  1043  2014 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-02 15:27:09.165  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-02 15:27:09.165  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 15:27:09.165  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-02 15:27:09.165  6878  6948 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 15:27:09.165  6878  6948 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a65ee6e added. We now have 2 listener(s)
09-02 15:27:09.165  6878  6948 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 15:27:09.165  6878  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-02 15:27:09.168  6878  6948 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 15:27:09.172  6878  6948 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 15:27:09.172  6878  6948 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 15:27:09.172  6878  6948 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 15:27:09.172  6878  6948 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 15:27:09.172  6878  6948 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 15:27:09.172  6878  6948 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 15:27:09.172  6878  6948 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 15:27:09.172  6878  6948 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-02 15:27:09.173  6878  6948 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-02 15:27:09.173  6878  6948 D io.jxcore.node.ConnectivityMonitor: start: OK
09-02 15:27:09.175  6878  6878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 15:27:09.176  6878  6878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 15:27:09.182  6878  6948 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-02 15:27:09.184  6878  6948 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-02 15:27:09.184  6878  6948 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-02 15:27:09.188  6878  6948 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-02 15:27:09.189  6878  6948 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-02 15:27:09.189  6878  6948 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-02 15:27:09.189  6878  6948 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-02 15:27:09.189  6878  6948 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-02 15:27:09.190  6878  6948 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 15:27:09.192  6878  6948 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 15:27:09.192  6878  6948 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 15:27:09.192  6878  6948 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 15:27:09.193  6878  6948 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:27:09.193  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-02 15:27:09.193  6878  6948 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-02 15:27:09.193  6878  6948 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a0bb1e9 removed from the list
09-02 15:27:09.193  6878  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:27:09.193  6878  6948 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a65ee6e removed from the list
09-02 15:27:09.193  6878  6948 D io.jxcore.node.ConnectivityMonitor: stop
09-02 15:27:09.193  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 15:27:09.196  6878  6948 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:27:09.196  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:27:09.197  6878  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 15:27:09.197  6878  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 15:27:09.197  6878  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:27:09.197  6878  6948 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a65ee6e not in the list
09-02 15:27:09.199  6878  6948 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-02 15:27:09.199  6878  6948 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 15:27:09.199  6878  6948 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 15:27:09.199  6878  6948 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 15:27:09.200  6878  6948 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 15:27:09.200  6878  6948 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:27:09.200  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:27:09.200  6878  6948 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a0bb1e9 not in the list
09-02 15:27:09.200  6878  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:27:09.200  6878  6948 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a65ee6e not in the list
09-02 15:27:09.200  6878  6948 D io.jxcore.node.ConnectivityMonitor: stop
09-02 15:27:09.200  6878  6948 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:27:09.200  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:27:09.200  6878  6948 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:27:09.200  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:27:09.201  6878  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 15:27:09.201  6878  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 15:27:09.201  6878  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:27:09.201  6878  6948 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a65ee6e not in the list
09-02 15:27:09.207  6878  6948 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-02 15:27:09.207  6878  6948 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,09-02 15:27:09.207  6878  6948 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-02 15:27:09.207  6878  6948 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-02 15:27:09.207  6878  6948 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-02 15:27:09.207  6878  6948 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-02 15:27:09.207  6878  6948 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-02 15:27:09.207  6878  6948 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-02 15:27:09.207  6878  6948 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-02 15:27:09.207  6878  6948 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-02 15:27:09.207  6878  6948 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-02 15:27:09.208  6878  6948 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-02 15:27:09.208  6878  6948 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-02 15:27:09.208  6878  6948 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-02 15:27:09.208  6878  6948 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-02 15:27:09.208  6878  6948 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-02 15:27:09.208  6878  6948 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-02 15:27:09.208  6878  6948 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-02 15:27:09.208  6878  6948 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-02 15:27:09.208  6878  6948 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-02 15:27:09.208  6878  6948 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-02 15:27:09.208  6878  6948 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-02 15:27:09.208  6878  6948 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-02 15:27:09.208  6878  6948 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-02 15:27:09.208  6878  6948 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-02 15:27:09.208  6878  6948 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-02 15:27:09.208  6878  6948 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-02 15:27:09.208  6878  6948 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-02 15:27:09.208  6878  6948 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<,no peer name> 37:2710:2710:2710:2710:2710]
09-02 15:27:09.208  6878  6948 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-02 15:27:09.208  6878  6948 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-02 15:27:09.208  6878  6948 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 15:27:09.208  6878  6948 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 15:27:09.208  6878  6948 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 15:27:09.210  6878  6948 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 15:27:09.210  6878  6948 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:27:09.210  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:27:09.210  6878  6948 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a0bb1e9 not in the list
09-02 15:27:09.210  6878  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:27:09.210  6878  6948 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a65ee6e not in the list
09-02 15:27:09.210  6878  6948 D io.jxcore.node.ConnectivityMonitor: stop
09-02 15:27:09.210  6878  6948 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:27:09.210  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:27:09.210  6878  6948 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:27:09.210  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:27:09.211  6878  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 15:27:09.211  6878  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 15:27:09.211  6878  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:27:09.211  6878  6948 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a65ee6e not in the list
09-02 15:27:09.212  6878  6948 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-02 15:27:09.213  6878  6948 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 15:27:09.215  6878  6948 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 15:27:09.215  6878  6948 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 15:27:09.215  6878  6948 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 15:27:09.215  6878  6948 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 15:27:09.215  6878  6948 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 15:27:09.215  6878  6948 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 15:27:09.215  6878  6948 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 15:27:09.2,15  6878  6948 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-02 15:27:09.216  6878  6948 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-02 15:27:09.216  6878  6948 D io.jxcore.node.ConnectivityMonitor: start: OK
09-02 15:27:09.217  6878  6948 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-02 15:27:09.217  6878  6948 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-02 15:27:09.217  6878  6878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 15:27:09.217  6878  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-02 15:27:09.217  6878  6948 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 15:27:09.217  6878  6948 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-02 15:27:09.218  6878  6878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 15:27:09.222  6878  6948 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-02 15:27:09.223  1043  1059 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 15:27:09.226  6878  6948 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-02 15:27:09.230  6878  6948 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-02 15:27:09.232  6878  6948 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
,09-02 15:27:09.233  6878  6948 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-02 15:27:09.233  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 15:27:09.234  6878  6948 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-02 15:27:09.234  6878  6948 I io.jxcore.node.ConnectionHelper: start: OK
09-02 15:27:09.237  6878  6948 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 15:27:09.237  6878  6948 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 15:27:09.237  6878  6948 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 15:27:09.237  6878  6948 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 15:27:09.237  6878  6948 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:27:09.237  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 15:27:09.237  6878  6948 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a0bb1e9 not in the list
09-02 15:27:09.237  6878  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:27:09.237  6878  6948 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a65ee6e not in the list
09-02 15:27:09.237  6878  6948 D io.jxcore.node.ConnectivityMonitor: stop
09-02 15:27:09.237  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:27:09.237  6878  6948 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-02 15:27:09.238  6878  6948 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 15:27:09.240  6878  6948 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 15:27:09.240  6878  6948 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 15:27:09.240  6878  6948 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 15:27:09.240  6878  6948 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 15:27:09.240  6878  6948 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 15:27:09.240  6878  6948 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 15:27:09.240  6878  6948 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 15:27:09.240  6878  6948 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-02 15:27:09.241  6878  6948 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-02 15:27:09.241  6878  6948 D io.jxcore.node.ConnectivityMonitor: start: OK
09-02 15:27:09.242  6878  6948 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-02 15:27:09.242  6878  6948 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-02 15:27:09.242  6878  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: s,tart: Discovery mode: BLE, start discovery: true, start advertiser: false
09-02 15:27:09.242  6878  6948 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 15:27:09.242  6878  6948 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-02 15:27:09.242  6878  6878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 15:27:09.244  6878  6878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 15:27:09.247  6878  6948 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-02 15:27:09.247  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 15:27:09.248  6878  6948 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-02 15:27:09.249  6878  6948 I io.jxcore.node.ConnectionHelper: start: OK
09-02 15:27:09.250  6878  6948 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 15:27:09.250  6878  6948 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 15:27:09.250  6878  6948 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 15:27:09.250  6878  6948 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 15:27:09.250  6878  6948 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:27:09.250  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 15:27:09.250  6878  6948 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a0bb1e9 not in the list
09-02 15:27:09.250  6878  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:27:09.250  6878  6948 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a65ee6e not in the list
09-02 15:27:09.250  6878  6948 D io.jxcore.node.ConnectivityMonitor: stop
09-02 15:27:09.250  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:27:09.250  6878  6948 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:27:09.250  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:27:09.251  6878  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 15:27:09.251  6878  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 15:27:09.252  6878  6948 D BluetoothLeScanner: could not find callback wrapper
09-02 15:27:09.252  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-02 15:27:09.252  6878  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:27:09.252  6878  6948 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a65ee6e not in the list
09-02 15:27:09.253  6878  6948 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-02 15:27:09.254  6878  6948 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 15:27:09.256  6878  6948 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 15:27:09.256  6878  6948 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 15:27:09.256  6878  6948 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 15:27:09.256  6878  6948 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 15:27:09.256  6878  6948 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 15:27:09.256  6878  6948 V io.jxcore.node.ConnectivityMonitor:     - BSSID nam,e: f4:f2:6d:22:99:3e
09-02 15:27:09.256  6878  6948 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 15:27:09.256  6878  6948 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-02 15:27:09.257  6878  6948 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-02 15:27:09.257  6878  6948 D io.jxcore.node.ConnectivityMonitor: start: OK
09-02 15:27:09.258  6878  6878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 15:27:09.259  6878  6878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 15:27:09.259  6878  6948 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-02 15:27:09.259  6878  6948 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-02 15:27:09.259  6878  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-02 15:27:09.259  6878  6948 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 15:27:09.259  6878  6948 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-02 15:27:09.262  6878  6948 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-02 15:27:09.262  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 15:27:09.263  6878  6948 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-02 15:27:09.263  6878  6948 I io.jxcore.node.ConnectionHelper: start: OK
09-02 15:27:09.263  6878  6948 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 15:27:09.263  6878  6948 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 15:27:09.263  6878  6948 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 15:27:09.264  6878  6948 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 15:27:09.264  6878  6948 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 15:27:09.264  6878  6948 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 15:27:09.264  6878  6948 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 15:27:09.264  6878  6948 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:27:09.264  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 15:27:09.264  6878  6948 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a0bb1e9 not in the list
09-02 15:27:09.264  6878  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:27:09.264  6878  6948 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a65ee6e not in the list
09-02 15:27:09.264  6878  6948 D io.jxcore.node.ConnectivityMonitor: stop
09-02 15:27:09.264  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:27:09.265  6878  6948 W org.thaliproj,ect.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:27:09.265  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:27:09.265  6878  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 15:27:09.265  6878  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 15:27:09.265  6878  6948 D BluetoothLeScanner: could not find callback wrapper
09-02 15:27:09.265  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-02 15:27:09.265  6878  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:27:09.265  6878  6948 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a65ee6e not in the list
09-02 15:27:09.266  6878  6948 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-02 15:27:09.266  6878  6948 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 15:27:09.266  6878  6948 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 15:27:09.266  6878  6948 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 15:27:09.266  6878  6948 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 15:27:09.266  6878  6948 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:27:09.266  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:27:09.266  6878  6948 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a0bb1e9 not in the list
09-02 15:27:09.266  6878  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
09-02 15:27:09.266  6878  6948 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a65ee6e not in the list
09-02 15:27:09.266  6878  6948 D io.jxcore.node.ConnectivityMonitor: stop
09-02 15:27:09.266  6878  6948 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-02 15:27:09.266  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:27:09.267  6878  6948 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:27:09.267  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:27:09.267  6878  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
,09-02 15:27:09.267  6878  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 15:27:09.268  6878  6948 D BluetoothLeScanner: could not find callback wrapper
09-02 15:27:09.268  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-02 15:27:09.268  6878  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:27:09.268  6878  6948 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a65ee6e not in the list
09-02 15:27:09.268  6878  6948 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-02 15:27:09.268  6878  6948 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 15:27:09.268  6878  6948 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 15:27:09.269  6878  6948 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 15:27:09.269  6878  6948 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 15:27:09.269  6878  6948 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:27:09.269  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:27:09.269  6878  6948 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a0bb1e9 not in the list
09-02 15:27:09.269  6878  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:27:09.269  6878  6948 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a65ee6e not in the list
09-02 15:27:09.269  6878  6948 D io.jxcore.node.ConnectivityMonitor: stop
09-02 15:27:09.269  6878  6948 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:27:09.269  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:27:09.269  6878  6948 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:27:09.269  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:27:09.270  6878  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 15:27:09.270  6878  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 15:27:09.270  6878  6948 D BluetoothLeScanner: could not find callback wrapper
09-02 15:27:09.270  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-02 15:27:09.270  6878  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:27:09.270  6878  6948 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a65ee6e not in the list
09-02 15:27:09.270  6878  6948 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-02 15:27:09.271  6878  6948 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 15:27:09.271  6878  6948 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 15:27:09.271  6878  69,48 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 15:27:09.271  6878  6948 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 15:27:09.271  6878  6948 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:27:09.271  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:27:09.271  6878  6948 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a0bb1e9 not in the list
09-02 15:27:09.271  6878  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:27:09.271  6878  6948 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a65ee6e not in the list
09-02 15:27:09.271  6878  6948 D io.jxcore.node.ConnectivityMonitor: stop
09-02 15:27:09.271  6878  6948 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:27:09.271  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:27:09.271  6878  6948 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:27:09.271  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:27:09.272  6878  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 15:27:09.272  6878  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 15:27:09.272  6878  6948 D BluetoothLeScanner: could not find callback wrapper
09-02 15:27:09.272  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-02 15:27:09.272  6878  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:27:09.272  6878  6948 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a65ee6e not in the list
09-02 15:27:09.273  6878  6948 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-02 15:27:09.273  6878  6948 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 15:27:09.273  6878  6948 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 15:27:09.273  6878  6948 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 15:27:09.273  6878  6948 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 15:27:09.273  6878  6948 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:27:09.273  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:27:09.273  6878  6948 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a0bb1e9 not in the list
09-02 15:27:09.273  6878  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:27:09.273  6878  6948 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a65ee6e not in the list
09-02 15:27:09.273  6878  6948 D io.jxcore.node.ConnectivityMonitor: stop
09-02 15:27:09.273  6878  6948 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:27:09.273  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:27:09.273  6878  6948 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:27:09.273  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:27:09.274  6878  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 15:27:09.274  6878  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 15:27:09.274  6878  6948 D BluetoothLeScanner: could not find callback wrapper
09-02 15:27:09.274  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-02 15:27:09.274  6878  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:27:09.274  6878  6948 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a65ee6e not in the list
09-02 15:27:09.275  6878  6948 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-02 15:27:09.276  6878  6948 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-02 15:27:09.276  6878  6948 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-02 15:27:09.276  6878  6948 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-02 15:27:09.276  6878  6948 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-02 15:27:09.276  6878  6948 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-02 15:27:09.276  6878  6948 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 15:27:09.276  6878  6948 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 15:27:09.276  6878  6948 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 15:27:09.276  6878  6948 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 15:27:09.276  6878  6948 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:27:09.276  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:27:09.276  6878  6948 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a0bb1e9 not in the list
09-02 15:27:09.276  6878  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:27:09.276  6878  6948 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a65ee6e not in the list
09-02 15:27:09.276  6878  6948 D io.jxcore.node.ConnectivityMonitor: stop
09-02 15:27:09.276  6878  6948 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:27:09.276  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:27:09.276  6878  6948 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:27:09.276  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:27:09.277  6878  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 15:27:09.277  6878  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 15:27:09.278  6878  6948 D BluetoothLeScanner: could not find callback wrapper
09-02 15:27:09.278  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-02 15:27:09.278  6878  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:27:09.278  6878  6948 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a65ee6e not in the list
09-02 15:27:09.278  6878  6948 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-02 15:27:09.278  6878  6948 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-02 15:27:09.278  6878  6948 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-02 15:27:09.280  6878  6948 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-02 15:27:09.280  6878  6948 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-02 15:27:09.280  6878  6948 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-02 15:27:09.280  6878  6948 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-02 15:27:09.280  6878  6948 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-02 15:27:09.280  6878  6948 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-02 15:27:09.280  6878  6948 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-02 15:27:09.280  6878  6948 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-02 15:27:09.280  6878  6948 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-02 15:27:09.280  6878  6948 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-02 15:27:09.280  6878  6948 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-02 15:27:09.280  6878  6948 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-02 15:27:09.280  6878  6948 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-02 15:27:09.280  6878  6948 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-02 15:27:09.280  6878  6948 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-02 15:27:09.280  6878  6948 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-02 15:27:09.280  6878  6948 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-02 15:27:09.280  6878  6948 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-02 15:27:09.280  6878  6948 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-02 15:27:09.280  6878  6948 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-02 15:27:09.280  6878  6948 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-02 15:27:09.280  6878  6948 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-02 15:27:09.281  6878  6948 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-02 15:27:09.281  6878  6948 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-02 15:27:09.281  6878  6948 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-02 15:27:09.281  6878  6948 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-02 15:27:09.281  6878  6948 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-02 15:27:09.281  6878  6948 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-02 15:27:09.281  6878  6948 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-02 15:27:09.281  6878  6948 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-02 15:27:09.281  6878  6948 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-02 15:27:09.281  6878  6948 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-02 15:27:09.281  6878  6948 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-02 15:27:09.281  6878  6948 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-02 15:27:09.281  6878  6948 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-02 15:27:09.281  6878  6948 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-02 15:27:09.281  6878  6948 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-02 15:27:09.281  6878  6948 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-02 15:27:09.281  6878  6948 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-02 15:27:09.281  6878  6948 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-02 15:27:09.281  6878  6948 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-02 15:27:09.283  6878  6948 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-02 15:27:09.283  6878  6948 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-02 15:27:09.283  6878  6948 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-02 15:27:09.284  6878  6948 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-02 15:27:09.284  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-02 15:27:09.284  6878  6948 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-02 15:27:09.284  6878  6948 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-02 15:27:09.284  6878  6948 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-02 15:27:09.284  6878  6948 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 15:27:09.284  6878  6948 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 15:27:09.284  6878  6948 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 15:27:09.285  6878  6948 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 15:27:09.285  6878  6948 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:27:09.285  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:27:09.286  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-02 15:27:09.286  6878  6948 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a0bb1e9 not in the list
09-02 15:27:09.286  6878  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:27:09.286  6878  6948 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a65ee6e not in the list
09-02 15:27:09.286  6878  6948 D io.jxcore.node.ConnectivityMonitor: stop
09-02 15:27:09.286  6878  6948 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:27:09.286  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:27:09.286  6878  6948 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:27:09.286  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:27:09.287  6878  6975 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 871)
09-02 15:27:09.288  6878  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 15:27:09.288  6878  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 15:27:09.288  6878  6948 D BluetoothLeScanner: could not find callback wrapper
09-02 15:27:09.288  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-02 15:27:09.288  6878  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:27:09.288  6878  6948 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a65ee6e not in the list
09-02 15:27:09.290  6878  6948 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-02 15:27:09.291  6878  6976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 871
09-02 15:27:09.292  6878  6948 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 15:27:09.292  6878  6948 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 15:27:09.292  6878  6948 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 15:27:09.293  6878  6948 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 15:27:09.293  6878  6948 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:27:09.293  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:27:09.293  6878  6948 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a0bb1e9 not in the list
09-02 15:27:09.293  6878  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:27:09.293  6878  6948 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a65ee6e not in the list
09-02 15:27:09.293  6878  6948 D io.jxcore.node.ConnectivityMonitor: stop
09-02 15:27:09.293  6878  6948 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:27:09.293  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:27:09.293  6878  6948 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:27:09.293  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:27:09.294  6878  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 15:27:09.294  6878  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 15:27:09.295  6878  6948 D BluetoothLeScanner: could not find callback wrapper
09-02 15:27:09.295  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-02 15:27:09.295  6878  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:27:09.295  6878  6948 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a65ee6e not in the list
09-02 15:27:09.297  6878  6948 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-02 15:27:09.298  6878  6948 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 15:27:09.298  6878  6948 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 15:27:09.298  6878  6948 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 15:27:09.299  6878  6948 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 15:27:09.299  6878  6948 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:27:09.299  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:27:09.299  6878  6948 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a0bb1e9 not in the list
09-02 15:27:09.299  6878  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:27:09.299  6878  6948 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a65ee6e not in the list
09-02 15:27:09.299  6878  6948 D io.jxcore.node.ConnectivityMonitor: stop
09-02 15:27:09.300  6878  6948 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:27:09.300  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:27:09.300  6878  6948 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:27:09.300  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:27:09.301  6878  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 15:27:09.301  6878  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 15:27:09.302  6878  6948 D BluetoothLeScanner: could not find callback wrapper
09-02 15:27:09.302  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-02 15:27:09.302  6878  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:27:09.302  6878  6948 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a65ee6e not in the list
09-02 15:27:09.303  6878  6948 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-02 15:27:09.303  6878  6948 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-02 15:27:09.303  6878  6948 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-02 15:27:09.303  6878  6948 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-02 15:27:09.303  6878  6948 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-02 15:27:09.304  6878  6948 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-02 15:27:09.304  6878  6948 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-02 15:27:09.304  6878  6948 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-02 15:27:09.304  6878  6948 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-02 15:27:09.304  6878  6948 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-02 15:27:09.304  6878  6948 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-02 15:27:09.304  6878  6948 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-02 15:27:09.304  6878  6948 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 15:27:09.304  6878  6948 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 15:27:09.304  6878  6948 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 15:27:09.306  6878  6948 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 15:27:09.306  6878  6948 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:27:09.306  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:27:09.306  6878  6948 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a0bb1e9 not in the list
09-02 15:27:09.306  6878  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:27:09.306  6878  6948 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a65ee6e not in the list
09-02 15:27:09.306  6878  6948 D io.jxcore.node.ConnectivityMonitor: stop
09-02 15:27:09.306  6878  6948 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-02 15:27:09.306  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:27:09.306  6878  6948 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:27:09.306  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:27:09.307  6878  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 15:27:09.307  6878  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 15:27:09.308  6878  6948 D BluetoothLeScanner: could not find callback wrapper
09-02 15:27:09.308  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-02 15:27:09.308  6878  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:27:09.308  6878  6948 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a65ee6e not in the list
09-02 15:27:09.308  6878  6948 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 15:27:09.308  6878  6948 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:27:09.308  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:27:09.308  6878  6948 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a0bb1e9 not in the list
09-02 15:27:09.308  6878  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:27:09.308  6878  6948 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a65ee6e not in the list
09-02 15:27:09.308  6878  6948 D io.jxcore.node.ConnectivityMonitor: stop
09-02 15:27:09.308  6878  6948 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:27:09.308  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:27:09.308  6878  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:27:09.310  6878  6948 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a65ee6e not in the list
09-02 15:27:09.310  6878  6948 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 15:27:09.310  6878  6948 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:27:09.310  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:27:09.310  6878  6948 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a0bb1e9 not in the list
09-02 15:27:09.310  6878  6948 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 15:27:09.310  6878  6948 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 15:27:09.310  6878  6948 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 15:27:09.311  6878  6948 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 15:27:09.311  6878  6948 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:27:09.311  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:27:09.311  6878  6948 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a0bb1e9 not in the list
09-02 15:27:09.311  6878  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:27:09.311  6878  6948 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a65ee6e not in the list
09-02 15:27:09.311  6878  6948 D io.jxcore.node.ConnectivityMonitor: stop
09-02 15:27:09.311  6878  6948 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:27:09.311  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:27:09.311  6878  6948 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:27:09.311  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:27:09.312  6878  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 15:27:09.312  6878  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 15:27:09.313  6878  6948 D BluetoothLeScanner: could not find callback wrapper
09-02 15:27:09.313  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-02 15:27:09.313  6878  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:27:09.313  6878  6948 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a65ee6e not in the list
09-02 15:27:09.315  6878  6948 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-02 15:27:09.315  6878  6948 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 15:27:09.319  6878  6948 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-02 15:27:09.320  6878  6948 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-02 15:27:09.320  6878  6948 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-02 15:27:09.321  6878  6878 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-02 15:27:09.322  6878  6948 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-02 15:27:09.322  6878  6948 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-02 15:27:09.325  1043  1891 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 15:27:09.325  6878  6948 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 15:27:09.325  6878  6948 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-02 15:27:09.325  6878  6948 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-02 15:27:09.325  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-02 15:27:09.325  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:27:09.325  6878  6948 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-02 15:27:09.326  6878  6878 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-02 15:27:09.326  6878  6948 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a0bb1e9 not in the list
09-02 15:27:09.326  6878  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:27:09.326  6878  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-02 15:27:09.326  6878  6948 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-02 15:27:09.326  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-02 15:27:09.326  6878  6977 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-02 15:27:09.327  4250  4627 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=84 mFd=82
09-02 15:27:09.328  6878  6977 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-02 15:27:09.328  6878  6977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-02 15:27:09.328  6878  6977 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-02 15:27:09.329  6878  6948 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-02 15:27:09.330  6878  6948 D BluetoothLeScanner: could not find callback wrapper
09-02 15:27:09.330  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-02 15:27:09.330  6878  6948 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-02 15:27:09.331  6878  6948 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:27:09.331  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:27:09.331  6878  6948 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-02 15:27:09.332  6878  6878 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-02 15:27:09.332  6878  6878 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-02 15:27:09.332  6878  6878 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-02 15:27:09.332  6878  6878 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-02 15:27:09.333  6878  6948 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a65ee6e not in the list
09-02 15:27:09.333  6878  6948 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 15:27:09.333  6878  6948 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 15:27:09.333  6878  6948 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 15:27:09.334  6878  6948 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 15:27:09.334  6878  6948 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:27:09.334  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:27:09.334  6878  6948 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a0bb1e9 not in the list
09-02 15:27:09.334  6878  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:27:09.334  6878  6948 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a65ee6e not in the list
09-02 15:27:09.334  6878  6948 D io.jxcore.node.ConnectivityMonitor: stop
09-02 15:27:09.334  6878  6948 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:27:09.334  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:27:09.335  6878  6948 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:27:09.335  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:27:09.335  6878  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 15:27:09.335  6878  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 15:27:09.335  6878  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:27:09.336  6878  6948 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a65ee6e not in the list
09-02 15:27:09.337  6878  6948 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-02 15:27:09.337  6878  6948 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-02 15:27:09.337  6878  6948 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-02 15:27:09.337  6878  6948 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-02 15:27:09.337  6878  6948 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 15:27:09.337  6878  6948 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 15:27:09.337  6878  6948 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 15:27:09.338  6878  6948 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 15:27:09.338  6878  6948 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:27:09.338  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:27:09.338  6878  6948 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a0bb1e9 not in the list
09-02 15:27:09.338  6878  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:27:09.338  6878  6948 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a65ee6e not in the list
09-02 15:27:09.338  6878  6948 D io.jxcore.node.ConnectivityMonitor: stop
09-02 15:27:09.338  6878  6948 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:27:09.338  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:27:09.338  6878  6948 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:27:09.338  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:27:09.339  6878  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 15:27:09.339  6878  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 15:27:09.339  6878  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:27:09.339  6878  6948 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a65ee6e not in the list
09-02 15:27:09.341  1043  1998 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 15:27:09.341  1043  2018 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 15:27:09.342  1043  1562 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 15:27:09.342  6878  6948 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 15:27:09.342  6878  6948 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 15:27:09.342  6878  6948 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 15:27:09.343  6878  6948 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 15:27:09.343  6878  6948 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:27:09.343  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:27:09.343  6878  6948 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a0bb1e9 not in the list
09-02 15:27:09.343  6878  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:27:09.343  6878  6948 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a65ee6e not in the list
09-02 15:27:09.343  6878  6948 D io.jxcore.node.ConnectivityMonitor: stop
09-02 15:27:09.343  6878  6948 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:27:09.343  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:27:09.343  6878  6948 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:27:09.343  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:27:09.346  6878  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 15:27:09.347  6878  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 15:27:09.347  6878  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:27:09.347  6878  6948 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a65ee6e not in the list
09-02 15:27:09.348  6878  6948 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 15:27:09.348  6878  6948 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 15:27:09.348  6878  6948 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-02 15:27:09.350  6878  6948 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 15:27:09.350  6878  6948 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:27:09.350  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:27:09.350  6878  6948 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a0bb1e9 not in the list
09-02 15:27:09.350  6878  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:27:09.350  6878  6948 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a65ee6e not in the list
09-02 15:27:09.350  6878  6948 D io.jxcore.node.ConnectivityMonitor: stop
09-02 15:27:09.350  6878  6948 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:27:09.350  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:27:09.350  6878  6948 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:27:09.351  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:27:09.352  6878  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 15:27:09.352  6878  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 15:27:09.352  6878  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:27:09.352  6878  6948 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a65ee6e not in the list
09-02 15:27:09.356  6878  6948 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-02 15:27:09.356  6878  6948 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-02 15:27:09.357  6878  6948 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-02 15:27:09.357  6878  6948 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-02 15:27:09.357  6878  6948 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-02 15:27:09.357  6878  6948 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-02 15:27:09.358  6878  6948 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-02 15:27:09.358  6878  6948 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-02 15:27:09.359  6878  6948 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-02 15:27:09.359  6878  6948 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-02 15:27:09.359  6878  6948 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-02 15:27:09.359  6878  6948 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-02 15:27:09.359  6878  6948 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-02 15:27:09.359  6878  6948 D io.jxcore.node.Connectio,nModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-02 15:27:09.359  6878  6948 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-02 15:27:09.359  6878  6948 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-02 15:27:09.360  6878  6948 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-02 15:27:09.360  6878  6948 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-02 15:27:09.360  6878  6948 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-02 15:27:09.360  6878  6948 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-02 15:27:09.361  6878  6948 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 15:27:09.361  6878  6948 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8ec3b07 added. We now have 2 listener(s)
09-02 15:27:09.361  6878  6948 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 15:27:09.367  6878  6948 D BluetoothAdapter: enable(): BT is already enabled..!
09-02 15:27:09.369  1043  1873 D WifiServiceImplEx: setWifiEnabled: true pid=6878, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-02 15:27:09.369  1043  1873 D WifiService: setWifiEnabled: true pid=6878, uid=10118
09-02 15:27:09.369  1043  1873 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-02 15:27:09.370  6878  6948 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 15:27:09.370  6878  6948 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@34fb7434 added. We now have 3 listener(s)
09-02 15:27:09.370  6878  6948 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 15:27:09.371  6878  6975 W LGMDMUISystemServiceAdapter: checkBluetoothPairing btPolicy: false
09-02 15:27:09.371  6878  6975 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-02 15:27:09.372  4250  4270 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-02 15:27:09.373  4250  4488 W bt-l2cap: L2CA_ErtmConnectReq()  PSM: 0x0001  BDA: 001122334455  p_ertm_info: 0x00000000 allowed:0x0 preferred:0
09-02 15:27:09.374  6878  6948 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 15:27:09.374  6878  6948 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b0825d added. We now have 4 listener(s)
09-02 15:27:09.374  6878  6948 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 15:27:09.376  6878  6948 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 15:27:09.376  6878  6948 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3ce07d2 added. We now have 5 listener(s)
09-02 15:27:09.376  6878  6948 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 15:27:09.377  1043  1927 D WifiServiceImplEx: setWifiEnabled: false pid=6878, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-02 15:27:09.378  1043  1927 D WifiService: setWifiEnabled: false pid=6878, uid=10118
09-02 15:27:09.378  1043  1927 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-02 15:27:09.387  1043  1043 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-02 15:27:09.388  1043  1043 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-02 15:27:09.388  1043  1043 D Ulp_jni : JNI:system_update. Event-4
09-02 15:27:09.388  1043  1377 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
09-02 15:27:09.389  1043  1377 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
09-02 15:27:09.389  1043  1377 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
09-02 15:27:09.389  1043  1377 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
09-02 15:27:09.389  1043  1377 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
09-02 15:27:09.389  1043  1377 E WifiStateMachine: WifiStateMachine: Leaving Connected state
09-02 15:27:09.389  1043  1377 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-02 15:27:09.389  1043  1377 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-02 15:27:09.390  1043  1059 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 15:27:09.390  1043  1059 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@dd275b9 mBinding = false
09-02 15:27:09.390  1043  1377 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-02 15:27:09.390  1043  1377 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-02 15:27:09.399  1043  1377 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-02 15:27:09.399  1043  1377 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-02 15:27:09.399  2696  2696 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-02 15:27:09.399  1043  1374 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-02 15:27:09.399  1043  1374 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-02 15:27:09.399  1043  1377 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-02 15:27:09.399  1043  1377 D WifiNative-wlan0: doBoolean: SET ps 1
,09-02 15:27:09.400  1043  1377 D WifiNative-wlan0: SET ps 1: returned true
09-02 15:27:09.400   304   880 D CommandListener: Clearing all IP addresses on wlan0
09-02 15:27:09.400  1043  2828 D DhcpStateMachine: RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-02 15:27:09.407  1043  1119 D BluetoothManagerService: Message: 2
09-02 15:27:09.407  1043  1043 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-02 15:27:09.407  1043  1043 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-02 15:27:09.407  1043  1043 D Ulp_jni : JNI:system_update. Event-4
09-02 15:27:09.407  1043  1119 D BluetoothManagerService: Sending off request.
09-02 15:27:09.408  4250  4287 D LGBluetoothServiceAdapter: [BTUI] Precleanup
09-02 15:27:09.408  4250  4333 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
09-02 15:27:09.408  4250  4333 D BluetoothAdapterProperties: Setting state to 13
09-02 15:27:09.409  4250  4333 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-02 15:27:09.409  4250  4333 D BluetoothAdapterProperties: onBluetoothDisable()
09-02 15:27:09.409  4250  4333 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
09-02 15:27:09.410  4250  4337 D BluetoothAdapterProperties: Scan Mode:20
09-02 15:27:09.410  4250  4333 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
09-02 15:27:09.410  4250  4333 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-02 15:27:09.411  4250  4632 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,09-02 15:27:09.412  4250  4631 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
09-02 15:27:09.412  4250  4631 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-02 15:27:09.412  4250  4631 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
09-02 15:27:09.412  4250  4631 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
09-02 15:27:09.412  4250  4631 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
09-02 15:27:09.412  4250  4631 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
09-02 15:27:09.412  4250  4631 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
09-02 15:27:09.412  4250  4631 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
09-02 15:27:09.412  4250  4686 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-02 15:27:09.412  4250  4687 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-02 15:27:09.413  4250  4690 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-02 15:27:09.413  4250  4488 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
09-02 15:27:09.413  4250  4488 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
09-02 15:27:09.414  4250  4488 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-02 15:27:09.414  4250  4488 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-02 15:27:09.414  4250  4488 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-02 15:27:09.414  4250  4488 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-02 15:27:09.414  4250  4488 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-02 15:27:09.414  4250  4488 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-02 15:27:09.414  4250  4488 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-02 15:27:09.414  4250  4488 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-02 15:27:09.414  4250  4488 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-02 15:27:09.414  4250  4488 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
09-02 15:27:09.414  4250  4488 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
09-02 15:27:09.414  4250  4488 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-02 15:27:09.415  1043  1119 D BluetoothManagerService: Message: 60
09-02 15:27:09.415  1043  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
09-02 15:27:09.415  1043  1119 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
09-02 15:27:09.417  6878  6975 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 871)
09-02 15:27:09.419  6878  6878 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 15:27:09.419  6878  6878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 15:27:09.419  6878  6878 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 15:27:09.419  6878  6878 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 15:27:09.419  6878  6878 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 15:27:09.419  6878  6878 V io.jxcore.node.ConnectivityMonitor:     - is B,luetooth enabled: false
09-02 15:27:09.419  6878  6878 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 15:27:09.419  6878  6878 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 15:27:09.419  6878  6878 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-02 15:27:09.419  6878  6878 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 15:27:09.419  6878  6878 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-02 15:27:09.425  1043  1431 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-02 15:27:09.425  1043  1431 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,09-02 15:27:09.433  1043  1998 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
09-02 15:27:09.433  1043  2827 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
09-02 15:27:09.433  1043  2827 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
09-02 15:27:09.433  1043  2827 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
09-02 15:27:09.433  1043  2827 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-1ms what=532486 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
09-02 15:27:09.433  1043  2827 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on <unknown ssid>
,09-02 15:27:09.452  1043  1115 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6995 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,09-02 15:27:09.454  6878  6948 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 15:27:09.456  6878  6948 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 15:27:09.456  6878  6948 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 15:27:09.456  6878  6948 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 15:27:09.456  6878  6948 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 15:27:09.456  6878  6948 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 15:27:09.456  6878  6948 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 15:27:09.456  6878  6948 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 15:27:09.456  6878  6948 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 15:27:09.456  6878  6948 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-02 15:27:09.457  6878  6948 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 15:27:09.457  6878  6948 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-02 15:27:09.457  6878  6948 D io.jxcore.node.ConnectivityMonitor: start: OK
09-02 15:27:09.457  1043  1043 D WifiHS20: hidePasspointNotification off =false
09-02 15:27:09.458  1043  1043 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 15:27:09.458  1043  1043 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 15:27:09.458  1043  1043 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-02 15:27:09.459  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 15:27:09.459  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-02 15:27:09.460  1928  1928 V WfdStateTracker: handleWifiStateChangedEvent: 0
09-02 15:27:09.462  6878  6878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 15:27:09.462  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 15:27:09.463  6878  6878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 15:27:09.465  1043  1377 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 15:27:09.466  1043  1377 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,09-02 15:27:09.466  1043  1374 D LGWifiP2pService: InactiveState{ when=-2ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
,09-02 15:27:09.466  1043  1374 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-02 15:27:09.466  1043  1374 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@3ad5a88c
09-02 15:27:09.467  1043  1374 D LGWifiP2pService: P2pDisablingState
09-02 15:27:09.467  1043  1374 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
09-02 15:27:09.467  1043  1374 D LGWifiP2pService: p2p socket connection lost
09-02 15:27:09.467  1043  1374 D LGWifiP2pService: P2pDisabledState
09-02 15:27:09.469  1928  1928 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-02 15:27:09.469  1043  1377 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 15:27:09.470  1043  1377 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 15:27:09.470  1043  1377 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 15:27:09.470  1043  1377 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 15:27:09.470  1043  1377 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-02 15:27:09.470  1043  1377 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 15:27:09.471  1043  1377 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 15:27:09.471  1043  1377 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 15:27:09.471  1043  1377 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
09-02 15:27:09.471  1043  1377 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-02 15:27:09.471  4250  4250 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-02 15:27:09.471  1043  1374 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-02 15:27:09.471  1043  1374 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-02 15:27:09.471  4250  4250 D BluetoothMapService: STATE_TURNING_OFF
09-02 15:27:09.471  2696  2696 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-02 15:27:09.471  4250  4250 V BluetoothMapService: Handler(): got msg=4
09-02 15:27:09.472  4250  4250 D BluetoothMapService: MAP Service closeService in
09-02 15:27:09.472  4250  4250 D BluetoothMapMasInstance: MAP Service shutdown
09-02 15:27:09.472  4250  4250 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-02 15:27:09.472  4250  4250 V BluetoothMapService: MAP Service closeService out
09-02 15:27:09.472  4250  4250 V BtOppService: Receiver DISABLED_ACTION 
09-02 15:27:09.472  4250  4250 I BtOppRfcommListener: stopping Accept Thread
09-02 15:27:09.472  4250  4250 V BtOppRfcommListener: close mBtServerSocket
09-02 15:27:09.473  4250  4250 V BtOppRfcommListener: waiting for thread to terminate
09-02 15:27:09.473  4250  4686 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-02 15:27:09.474  4250  4250 V BtOppRfcommListener: done waiting for thread to terminate
09-02 15:27:09.477  1043  1377 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-02 15:27:09.477  1043  1377 D WifiNative-wlan0: doBoolean: SET ps 1
09-02 15:27:09.477  1043  1377 D WifiNative-wlan0: SET ps 1: returned true
09-02 15:27:09.478  6878  6878 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 15:27:09.478  6878  6878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 15:27:09.478  6878  6878 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 15:27:09.478  6878  6878 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTE,D
09-02 15:27:09.478  6878  6878 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 15:27:09.478  6878  6878 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 15:27:09.478  6878  6878 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 15:27:09.478  6878  6878 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 15:27:09.478  6878  6878 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-02 15:27:09.479  6878  6878 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 15:27:09.479  6878  6878 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-02 15:27:09.480  6878  6878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 15:27:09.483  1589  1589 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-02 15:27:09.487   304   880 D CommandListener: Clearing all IP addresses on wlan0
09-02 15:27:09.487   304  7014 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
09-02 15:27:09.488  1043  1431 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
09-02 15:27:09.488  1043  1431 D DSQN    : disableDataServiceNotify
09-02 15:27:09.488  1043  1431 D DSQN    : stop dsqn bin
09-02 15:27:09.488  1043  2827 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
09-02 15:27:09.488  1043  1117 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
09-02 15:27:09.501  1043  1431 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-02 15:27:09.501  1043  1431 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 15:27:09.501  1043  1431 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-02 15:27:09.502  1043  1431 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
09-02 15:27:09.502  1043  1431 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
09-02 15:27:09.502  1043  2827 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-02 15:27:09.502  1043  2827 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-02 15:27:09.502  1043  2827 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
09-02 15:27:09.502  1043  1431 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
09-02 15:27:09.502  1589  2084 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
09-02 15:27:09.502  1043  1431 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-02 15:27:09.502  1043  1431 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,09-02 15:27:09.517  1043  1115 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=7015 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
09-02 15:27:09.518  4250  4250 V BtOppService: onDestroy
,09-02 15:27:09.519  1043  1043 D WifiHS20: hidePasspointNotification off =false
09-02 15:27:09.521  1043  1043 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 15:27:09.521  1043  1043 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 15:27:09.521  1043  1043 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-02 15:27:09.521  1043  1043 D WifiScanningService: SCAN_AVAILABLE : 1
09-02 15:27:09.521  1043  1043 D RttService: SCAN_AVAILABLE : 1
09-02 15:27:09.522  1043  1544 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-02 15:27:09.522  1043  1542 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
09-02 15:27:09.522  1928  1928 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-02 15:27:09.522  1928  1928 D WfdsService: WifiP2pState is changed : false
09-02 15:27:09.522  1928  2260 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
09-02 15:27:09.522  1928  2260 D WfdsService: Set the WFDS Monitor: false
09-02 15:27:09.522  1043  1377 D WifiNative-p2p0: doBoolean: TERMINATE
09-02 15:27:09.523  1043  1377 D WifiNative-p2p0: TERMINATE: returned true
09-02 15:27:09.523  1043  1043 D WifiHS20: hidePasspointNotification off =false
09-02 15:27:09.523  1043  1377 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-02 15:27:09.523  1043  1377 E WifiStateMachine: useWiFiOffloading() : false
09-02 15:27:09.523  1043  1377 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-02 15:27:09.523  1928  2260 D WfdsMonitor: WFDS Monitor is stopped
09-02 15:27:09.523  1928  2260 D WfdsService: STATE : WfdsDisabledState - enter
09-02 15:27:09.523  1928  2761 D CtrlSupplicant: Received on exit socket, terminate
09-02 15:27:09.523  1928  2761 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
09-02 15:27:09.523  1928  2761 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
09-02 15:27:09.523  1928  2761 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
09-02 15:27:09.523  1928  2264 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
09-02 15:27:09.524  1043  1043 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 15:27:09.524  1043  1043 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 15:27:09.524  1043  1043 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-02 15:27:09.526  1928  2260 W WfdsService: DefaultState - msg [9445378] is not handled
09-02 15:27:09.527  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 15:27:09.527  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-02 15:27:09.528  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 15:27:09.528  4250  4250 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
09-02 15:27:09.529  1043  1431 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-02 15:27:09.529  1043  1431 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-02 15:27:09.531  1043  1431 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-02 15:27:09.531  1043  1431 D ConnectivityServic,e: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 15:27:09.531  1043  1431 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 15:27:09.532  1043  1431 D NetworkManagementService: Removing idletimer
09-02 15:27:09.532  1043  1431 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 15:27:09.533  1043  1373 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-02 15:27:09.534  1928  1928 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
,09-02 15:27:09.534  1043  1373 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-02 15:27:09.534  1043  1431 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
09-02 15:27:09.534  1043  1043 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-02 15:27:09.536  1836  1836 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 15:27:09.536  1836  1836 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-02 15:27:09.537  1043  1377 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 15:27:09.537  1043  1377 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-02 15:27:09.538  1043  1043 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
09-02 15:27:09.538  1043  1043 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-02 15:27:09.539  6878  6878 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 15:27:09.539  6878  6878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 15:27:09.539  6878  6878 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 15:27:09.539  6878  6878 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 15:27:09.539  6878  6878 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 15:27:09.539  6878  6878 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 15:27:09.539  6878  6878 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 15:27:09.539  6878  6878 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 15:27:09.539  6878  6878 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-02 15:27:09.539  1043  1043 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-02 15:27:09.539  6878  6878 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 15:27:09.539  1043  1043 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-02 15:27:09.539  6878  6878 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-02 15:27:09.539  1043  1043 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-02 15:27:09.539  1043  1043 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-02 15:27:09.539  1043  1043 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
09-02 15:27:09.539  1043  1043 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-02 15:27:09.539  1043  1043 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-02 15:27:09.539  1043  1043 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-02 15:27:09.540  6878  6878 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the, Bluetooth is disabled - will return stored value
09-02 15:27:09.540  6878  6878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 15:27:09.540  6878  6878 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 15:27:09.540  6878  6878 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 15:27:09.540  6878  6878 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 15:27:09.540  6878  6878 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 15:27:09.540  6878  6878 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 15:27:09.540  6878  6878 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 15:27:09.540  6878  6878 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-02 15:27:09.541  6878  6878 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 15:27:09.541  6878  6878 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-02 15:27:09.556  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-02 15:27:09.556  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-02 15:27:09.556  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 15:27:09.570  7015  7015 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-02 15:27:09.571  7015  7015 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
09-02 15:27:09.571  7015  7015 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-02 15:27:09.571  7015  7015 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
09-02 15:27:09.572  7015  7015 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-02 15:27:09.572  7015  7015 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-02 15:27:09.589  1589  1589 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-02 15:27:09.590  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 15:27:09.590  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-02 15:27:09.591  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 15:27:09.605  1043  2828 D DhcpStateMachine: StoppedState
09-02 15:27:09.605  1043  2828 D DhcpStateMachine: StoppedState{ when=-127ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-02 15:27:09.606  1043  1377 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
09-02 15:27:09.606  1043  1377 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
,09-02 15:27:09.607  1589  1589 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,09-02 15:27:09.608  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 15:27:09.608  6995  6995 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
09-02 15:27:09.608  6995  6995 W LG Account v2.2: No ProfileInfo entries
09-02 15:27:09.608  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 15:27:09.608  6995  6995 I LG Account v2.2: isEnabled: false
09-02 15:27:09.608  6995  6995 I Feature : [Lifetracker]ver: 4.21.112(40211120)
09-02 15:27:09.608  6995  6995 I Feature : [Lifetracker]Country: EU
09-02 15:27:09.608  6995  6995 I Feature : [Lifetracker]Operator: OPEN
09-02 15:27:09.608  6995  6995 I Feature : [Lifetracker]Ranking support: false
09-02 15:27:09.608  6995  6995 I Feature : [Lifetracker]Comfort support: false
09-02 15:27:09.608  6995  6995 I Feature : [Lifetracker]Accessory: true
09-02 15:27:09.608  6995  6995 I Feature : [Lifetracker]Health device: true
09-02 15:27:09.608  6995  6995 I Feature : [Lifetracker]Extra Pedometer: false
09-02 15:27:09.609  6995  6995 I Feature : [Lifetracker]Blood glucose device: false
09-02 15:27:09.609  6995  6995 I Feature : [Lifetracker]Device Number: 3
09-02 15:27:09.615  6433  6433 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-02 15:27:09.627  2696  2696 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
09-02 15:27:09.627  2696  2696 I wpa_supplicant: monitor socket send errors count : 1
09-02 15:27:09.627  2696  2696 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1928-2\x00 that cannot receive messages
,09-02 15:27:09.629  1043  2759 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
09-02 15:27:09.629  1043  2759 D WifiMonitor: Dropping event because (p2p0) is stopped
09-02 15:27:09.658  1043  2018 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7035 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
09-02 15:27:09.659  1043  2018 I ActivityManager: Killing 6200:com.android.providers.calendar/u0a14 (adj 15): empty #17
,09-02 15:27:09.719  1043  1059 W libprocessgroup: failed to open /acct/uid_10014/pid_6200/cgroup.procs: No such file or directory
,09-02 15:27:09.735  2696  2696 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-02 15:27:09.735  1043  2759 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
09-02 15:27:09.736  1043  2759 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-02 15:27:09.736  1043  2759 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-02 15:27:09.736  1043  2759 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
,09-02 15:27:09.738  1043  1377 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=183000
09-02 15:27:09.738  2696  2696 W wpa_supplicant: USIM:  scard_deinit function
09-02 15:27:09.739  1043  2759 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-02 15:27:09.739  1043  2759 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-02 15:27:09.741  1043  1377 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=183003
09-02 15:27:09.741  1043  1119 D Tethering: InitialState.processMessage what=4
09-02 15:27:09.742  1043  1377 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=183004  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-02 15:27:09.744  1043  1119 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-02 15:27:09.745  1043  1377 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=183006  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-02 15:27:09.747  1043  1377 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
09-02 15:27:09.747  1043  1377 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,09-02 15:27:09.796  7035  7035 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,09-02 15:27:09.801  7035  7035 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-02 15:27:09.802  7035  7035 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-02 15:27:09.805  1043  1059 I ActivityManager: Killing 6318:com.android.defcontainer/u0a4 (adj 15): empty #17
09-02 15:27:09.824  7015  7015 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,09-02 15:27:09.834  6878  6878 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
09-02 15:27:09.836  1043  1865 W libprocessgroup: failed to open /acct/uid_10004/pid_6318/cgroup.procs: No such file or directory
,09-02 15:27:09.838  2696  2696 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
09-02 15:27:09.838  1043  2759 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
09-02 15:27:09.838  1043  2759 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
09-02 15:27:09.839  1043  2759 D WifiMonitor: Disconnecting from the supplicant, no more events
09-02 15:27:09.840  1043  1377 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
09-02 15:27:09.851  4250  4250 V BluetoothPbapReceiver: PbapReceiver onReceive 
,09-02 15:27:09.851  4250  4250 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-02 15:27:09.851  4250  4250 V BluetoothPbapReceiver: ***********state = 13
09-02 15:27:09.853  4250  4250 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
09-02 15:27:09.854  4250  4250 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-02 15:27:09.854  4250  4250 V BluetoothPbapService: state: 13
09-02 15:27:09.854  4250  4250 V BluetoothPbapService: Pbap Service closeService in
09-02 15:27:09.856  2160  2160 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-02 15:27:09.857  4250  4250 V BluetoothPbapService: successfully stopped pbap service
09-02 15:27:09.857  4250  4250 V BluetoothPbapService: Pbap Service closeService out
09-02 15:27:09.857  4250  4250 V BluetoothPbapService: Pbap Service onDestroy
09-02 15:27:09.857  4250  4250 V BluetoothPbapService: Pbap Service closeService in
09-02 15:27:09.857  4250  4250 V BluetoothPbapService: Pbap Service closeService out
09-02 15:27:09.857  4250  4250 D LGBluetoothPbapAdapter: [BTUI] cleanup
09-02 15:27:09.873  7015  7015 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-02 15:27:09.911  7015  7015 D LgDataFeature: LgDataFeature() Constructor: none
09-02 15:27:09.911  7015  7015 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-02 15:27:09.922  7015  7015 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-02 15:27:09.931  1043  1119 D BluetoothManagerService: Message: 20
09-02 15:27:09.932  1043  1119 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2241aa98:true
,09-02 15:27:09.942  1043  1377 D WifiOffDelayIfNotUsed: stopMonitoring
09-02 15:27:09.942  1043  1377 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-02 15:27:09.942  1043  1377 E WifiStateMachine: useWiFiOffloading() : false
09-02 15:27:09.942  1043  1377 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,09-02 15:27:09.946  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 15:27:09.947  1043  1043 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
09-02 15:27:09.947  1928  1928 D WfdsService: Supplicant Connection state is changed : false
09-02 15:27:09.948  1928  2260 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
09-02 15:27:09.948  1928  2260 D WfdsService: Set the WFDS Monitor: false
09-02 15:27:09.948  1928  2260 D WfdsMonitor: WFDS Monitor is stopped
09-02 15:27:09.948  1043  1395 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
09-02 15:27:09.949  1928  1928 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-02 15:27:09.949  1043  1395 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
09-02 15:27:09.951  1043  1119 D BluetoothManagerService: Message: 30
09-02 15:27:09.953  2469  2469 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 15:27:09.955  6878  6878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 15:27:09.960  6878  6878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 15:27:09.966  1043  1119 D BluetoothManagerService: Message: 30
09-02 15:27:09.970  7015  7015 D LocalBluetoothProfileManager: Adding local MAP profile
,09-02 15:27:09.972  7015  7015 D BluetoothMap: Create BluetoothMap proxy object
09-02 15:27:09.973  1043  1119 D BluetoothManagerService: Message: 30
09-02 15:27:09.978  1043  1119 D BluetoothManagerService: Message: 30
09-02 15:27:09.980  7015  7015 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
09-02 15:27:09.981  7015  7015 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
09-02 15:27:09.997  7015  7015 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
,09-02 15:27:10.002  7015  7015 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
09-02 15:27:10.020  7015  7015 D DockEventReceiver: finishStartingService: stopping service
,09-02 15:27:10.044  7015  7015 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,09-02 15:27:10.054  7015  7015 D BluetoothInputDevice: Proxy object connected
09-02 15:27:10.057  7015  7015 D HidProfile: Bluetooth service connected
,09-02 15:27:10.059  7015  7015 D BluetoothPan: BluetoothPAN Proxy object connected
09-02 15:27:10.061  7015  7015 D PanProfile: Bluetooth service connected
09-02 15:27:10.063  7015  7015 D BluetoothMap: Proxy object connected
09-02 15:27:10.064  7015  7015 D MapProfile: Bluetooth service connected
09-02 15:27:10.065  7015  7015 D BluetoothMap: getConnectedDevices()
09-02 15:27:10.066  7015  7015 D BluetoothMap: Bluetooth is Not enabled
09-02 15:27:10.067  7015  7015 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
09-02 15:27:10.072  7015  7015 D BluetoothPermissionRequest: onReceive
,09-02 15:27:10.077  7015  7015 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,09-02 15:27:10.094  1043  2014 I ActivityManager: Killing 6499:com.google.android.partnersetup/u0a8 (adj 15): empty #17
09-02 15:27:10.096  7015  7015 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,09-02 15:27:10.128  1043  1771 W libprocessgroup: failed to open /acct/uid_10008/pid_6499/cgroup.procs: No such file or directory
,09-02 15:27:10.130  4250  4250 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
09-02 15:27:10.130  4250  4250 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
09-02 15:27:10.131  4250  4250 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
09-02 15:27:10.142  4250  4250 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-02 15:27:10.143  4250  4250 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
,09-02 15:27:10.146  4250  4250 V BluetoothFtpService: Ftp Service onStartCommand
09-02 15:27:10.146  4250  4250 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-02 15:27:10.147  4250  4250 V BluetoothFtpService: Ftp Service closeService
09-02 15:27:10.147  4250  4250 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
09-02 15:27:10.223  1043  1060 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=7063 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,09-02 15:27:10.230  4250  4250 V BluetoothFtpService: successfully stopped ftp service
09-02 15:27:10.231  4250  4250 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-02 15:27:10.231  4250  4250 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-02 15:27:10.232  4250  4250 V BluetoothSapReceiver: SapReceiver onReceive 
09-02 15:27:10.232  4250  4250 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-02 15:27:10.232  4250  4250 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
09-02 15:27:10.232  4250  4250 V BluetoothSapReceiver: Calling SAP service start service with action = null
09-02 15:27:10.234  4250  4250 V BluetoothFtpService: Ftp Service onDestroy
09-02 15:27:10.234  4250  4250 V BluetoothFtpService: Ftp Service closeService
09-02 15:27:10.236  4250  4250 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-02 15:27:10.237  4250  4250 V BluetoothSapService: state: 13
09-02 15:27:10.237  4250  4250 V BluetoothSapService: Stopping SAP server process
09-02 15:27:10.240  4250  4250 V BluetoothSapService: Sap Service closeSapService in
09-02 15:27:10.240  4250  4250 V BluetoothSapService: Close listen Socket : 
09-02 15:27:10.240  4250  4250 V BluetoothSapService: Close rfcomm Socket : 
09-02 15:27:10.240  4250  4250 V BluetoothSapService: Close sapd  Socket : 
,09-02 15:27:10.299  1043  1873 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=7080 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-02 15:27:10.300  4250  4250 V BluetoothSapService: Sap Service closeSapService out
,09-02 15:27:10.300  4250  4250 V BluetoothSapService: Sap Service onDestroy
09-02 15:27:10.300  4250  4250 V BluetoothSapService: Sap Service closeSapService in
09-02 15:27:10.300  4250  4250 V BluetoothSapService: Close listen Socket : 
09-02 15:27:10.300  4250  4250 V BluetoothSapService: Close rfcomm Socket : 
09-02 15:27:10.300  4250  4250 V BluetoothSapService: Close sapd  Socket : 
09-02 15:27:10.306  4250  4250 V BluetoothSapService: Sap Service closeSapService out
09-02 15:27:10.326  7063  7063 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-02 15:27:10.354  7063  7063 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,09-02 15:27:10.367  7080  7080 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-02 15:27:10.382  1043  2018 I ActivityManager: Killing 6537:com.lge.appbox.client/u0a11 (adj 15): empty #17
,09-02 15:27:10.392  7063  7063 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,09-02 15:27:10.392  7063  7063 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
09-02 15:27:10.393  7063  7063 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
09-02 15:27:10.393  7063  7063 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
,09-02 15:27:10.394  7063  7063 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
,09-02 15:27:10.396  7063  7063 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
09-02 15:27:10.402  7063  7063 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
09-02 15:27:10.418  4250  4488 W bt-btif : ag scb idx 1 not allocated
09-02 15:27:10.418  4250  4488 E bt-btif : BTA AG is already disabled, ignoring ...
09-02 15:27:10.418  4250  4488 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
,09-02 15:27:10.418  4250  4488 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-02 15:27:10.418  4250  4337 D bt_hci_bdroid: cleanup
09-02 15:27:10.418  4250  4488 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-02 15:27:10.418  4250  4488 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-02 15:27:10.418  4250  4488 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-02 15:27:10.418  4250  4488 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-02 15:27:10.418  4250  4488 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-02 15:27:10.418  4250  4488 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-02 15:27:10.418  4250  4488 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-02 15:27:10.418  4250  4488 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-02 15:27:10.418  4250  4488 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-02 15:27:10.418  4250  4488 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-02 15:27:10.418  4250  4488 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-02 15:27:10.418  4250  4488 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-02 15:27:10.418  4250  4488 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-02 15:27:10.418  4250  4488 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-02 15:27:10.418  4250  4488 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-02 15:27:10.418  4250  4488 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-02 15:27:10.418  4250  4488 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-02 15:27:10.418  4250  4611 I bt_userial_mct: exiting userial_read_thread
09-02 15:27:10.418  4250  4491 I bt_lpm  : LPM is already off!!!
09-02 15:27:10.418  4250  4611 D bt_userial_mct: Leaving userial_evt_read_thread()
09-02 15:27:10.419  4250  4337 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
09-02 15:27:10.420  4250  4491 I bt_vendor: hw_epilog_process
09-02 15:27:10.421  4250  4337 D bt_hci_bdroid: cleanup Finalizing cleanup
09-02 15:27:10.421  4250  4337 D bt_userial_mct: userial_close
09-02 15:27:10.421  4250  4337 E bt_userial_mct: pthread_join() FAILED result:3
09-02 15:27:10.421  4250  4337 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
09-02 15:27:10.428  1043  1926 W libprocessgroup: failed to open /acct/uid_10011/pid_6537/cgroup.procs: No such file or directory
09-02 15:27:10.440  7063  7063 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-02 15:27:10.445  7063  7063 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-02 15:27:10.477  7063  7063 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-02 15:27:10.482  7063  7063 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
09-02 15:27:10.485  6433  6433 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-02 15:27:10.486  7063  7063 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
09-02 15:27:10.489  7035  7035 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-02 15:27:10.489  7035  7035 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-02 15:27:10.489  7035  7035 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-02 15:27:10.497  7015  7015 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-02 15:27:10.500  4250  4337 D bt_hci_bdroid: set_power 0
09-02 15:27:10.500  4250  4337 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
09-02 15:27:10.500  4250  4337 I bt_vendor: bluetooth satus is on
09-02 15:27:10.500  4250  4337 I bt_vendor: bt-vendor : resetting BT status
09-02 15:27:10.500  4250  4337 I bt_vendor: Starting hciattach daemon
09-02 15:27:10.500  4250  4337 I bt_vendor: try to set false
,09-02 15:27:10.503  7015  7015 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 15:27:10.503  4250  4337 I bt_vendor: Starting hciattach daemon
09-02 15:27:10.503  4250  4337 I bt_vendor: try to set false
09-02 15:27:10.505  4250  4337 I bt_vendor: cleanup
09-02 15:27:10.506  4250  4488 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
09-02 15:27:10.507  4250  4337 I GKI_LINUX: GKI_exit_task 0 done
09-02 15:27:10.507  4250  4337 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
09-02 15:27:10.508  4250  4333 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
09-02 15:27:10.517  4250  4250 D HeadsetService: Received stop request...Stopping profile...
,09-02 15:27:10.518  4250  4250 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-02 15:27:10.518  4250  4250 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-02 15:27:10.519  4250  4250 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13d0e61f
09-02 15:27:10.519  4250  4443 D HeadsetStateMachine: Exit Disconnected: -1
09-02 15:27:10.521  1836  1836 D BluetoothHeadset: Proxy object disconnected
09-02 15:27:10.521  1836  1836 D BluetoothHeadset: Proxy object disconnected
09-02 15:27:10.521  1836  1836 D BluetoothHeadset: Proxy object disconnected
09-02 15:27:10.521  7063  7063 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-02 15:27:10.522  7063  7063 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-02 15:27:10.524  1043  1043 D BluetoothHeadset: Proxy object disconnected
09-02 15:27:10.524  1043  1043 D AudioService: onServiceDisconnected: Bluetooth profile: 1
09-02 15:27:10.526  4250  4250 D A2dpService: Received stop request...Stopping profile...
09-02 15:27:10.527  4250  4461 D A2dpStateMachine: Exit Disconnected: -1
09-02 15:27:10.528  4250  4250 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
09-02 15:27:10.528  7063  7063 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-02 15:27:10.528  4250  4333 D BluetoothAdapterState: Stopping profile services that were post enabled
09-02 15:27:10.535  6433  6433 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-02 15:27:10.537  4250  4250 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
09-02 15:27:10.537  4250  4250 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
09-02 15:27:10.537  4250  4250 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13d0e61f
09-02 15:27:10.538  1043  1043 D BluetoothA2dp: Proxy object disconnected
09-02 15:27:10.538  1043  1043 D AudioService: onServiceDisconnected: Bluetooth profile: 2
09-02 15:27:10.540  4250  4250 D HidService: Received stop request...Stopping profile...
09-02 15:27:10.540  4250  4250 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13d0e61f
09-02 15:27:10.543  7035  7035 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-02 15:27:10.543  7035  7035 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-02 15:27:10.543  7035  7035 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-02 15:27:10.544  7015  7015 D BluetoothInputDevice: Proxy object disconnected
09-02 15:27:10.544  4250  4250 D HeadsetStateMachine: Unbinding service...
09-02 15:27:10.544  7015  7015 D HidProfile: Bluetooth service disconnected
09-02 15:27:10.546  4250  4250 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-02 15:27:10.546  4250  4250 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-02 15:27:10.546  4250  4250 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-02 15:27:10.546  4250  4250 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-02 15:27:10.546  4250  4250 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-02 15:27:10.546  4250  4250 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-02 15:27:10.546  4250  4250 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-02 15:27:10.548  4250  4250 D HealthService: Received stop request...Stopping profile...
09-02 15:27:10.548  4250  4250 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13d0e61f
,09-02 15:27:10.551  7015  7015 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-02 15:27:10.554  4250  4250 D PanService: Received stop request...Stopping profile...
09-02 15:27:10.555  4250  4250 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13d0e61f
09-02 15:27:10.556  4250  4250 D BtGatt.DebugUtils: handleDebugAction() action=null
09-02 15:27:10.557  4250  4250 D BtGatt.GattService: Received stop request...Stopping profile...
09-02 15:27:10.557  4250  4250 D BtGatt.GattService: stop()
09-02 15:27:10.557  4250  4250 D BtGatt.AdvertiseManager: advertise clients cleared
09-02 15:27:10.558  4250  4250 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13d0e61f
09-02 15:27:10.560  4250  4250 D BluetoothMapService: Received stop request...Stopping profile...
09-02 15:27:10.560  4250  4250 D BluetoothMapService: stop()
09-02 15:27:10.561  4250  4250 D BluetoothMapEmailAppObserver: deinitObservers()
09-02 15:27:10.562  4250  4250 D BluetoothMapEmailAppObserver: removeReceiver()
,09-02 15:27:10.562  4250  4250 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13d0e61f
,09-02 15:27:10.563  4250  4250 I BluetoothA2dpServiceJni: cleanupNative
09-02 15:27:10.563  4250  4462 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
09-02 15:27:10.563  4250  4250 I GKI_LINUX: GKI_exit_task 2 done
09-02 15:27:10.563  4250  4250 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
09-02 15:27:10.564  4250  4250 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-02 15:27:10.564  4250  4250 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-02 15:27:10.564  4250  4250 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-02 15:27:10.565  4250  4250 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-02 15:27:10.565  4250  4250 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-02 15:27:10.565  4250  4250 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-02 15:27:10.565  4250  4250 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-02 15:27:10.566  7015  7015 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 15:27:10.567  4250  4250 V BluetoothMapService: Handler(): got msg=4
09-02 15:27:10.567  4250  4250 D BluetoothMapService: MAP Service closeService in
09-02 15:27:10.567  4250  4250 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-02 15:27:10.567  4250  4250 V BluetoothMapService: MAP Service closeService out
09-02 15:27:10.567  4250  4250 D BluetoothMapService: cleanup()
09-02 15:27:10.567  4250  4250 D BluetoothMapService: MAP Service closeService in
09-02 15:27:10.567  4250  4250 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-02 15:27:10.567  4250  4250 V BluetoothMapService: MAP Service closeService out
09-02 15:27:10.567  4250  4333 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
09-02 15:27:10.567  4250  4333 D BluetoothAdapterProperties: Setting state to 10
09-02 15:27:10.567  4250  4333 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
09-02 15:27:10.568  1043  1119 D BluetoothManagerService: Message: 60
09-02 15:27:10.568  1043  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
09-02 15:27:10.568  1043  1119 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
09-02 15:27:10.568  1043  1119 D BluetoothA2dp: onBluetoothStateChange: up=false
09-02 15:27:10.568  4250  4333 I BluetoothAdapterState: Entering OffState
09-02 15:27:10.570  7015  7030 D BluetoothPan: onBluetoothStateChange on: false
09-02 15:27:10.572  1043  1119 D BluetoothHeadset: onBluetoothStateChange: up=false
09-02 15:27:10.572  7015  7015 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-02 15:27:10.572  7015  7015 D PanProfile: Bluetooth service disconnected
09-02 15:27:10.572  7015  7015 D BluetoothMap: Proxy object disconnected
09-02 15:27:10.572  7015  7015 D MapProfile: Bluetooth service disconnected
09-02 15:27:10.572  1836  3496 D BluetoothHeadset: onBluetoothStateChange: up=false
09-02 15:27:10.573  7015  7030 D BluetoothPbap: onBluetoothStateChange: up=false
09-02 15:27:10.573  1836  2685 D BluetoothHeadset: onBluetoothStateChange: up=false
09-02 15:27:10.574  7015  7031 D BluetoothMap: onBluetoothStateChange: up=false
,09-02 15:27:10.580  7063  7063 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-02 15:27:10.580  1836  1852 D BluetoothHeadset: onBluetoothStateChange: up=false
09-02 15:27:10.580  7063  7063 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-02 15:27:10.581  7015  7030 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-02 15:27:10.583  1043  1119 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
09-02 15:27:10.583  7063  7063 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-02 15:27:10.583  1043  1119 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
09-02 15:27:10.586  1043  1119 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
09-02 15:27:10.586  1043  1119 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
09-02 15:27:10.587  1043  1119 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@dd275b9 mBinding = false
09-02 15:27:10.588  1043  1119 D BluetoothManagerService: Sending unbind request.
,09-02 15:27:10.645  1043  1927 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7105 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,09-02 15:27:10.657  1043  1119 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
09-02 15:27:10.659  1928  1928 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-02 15:27:10.659  1928  2066 D LGBluetoothAPIService: Message: 2
09-02 15:27:10.660  1928  2066 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@85db28e mBinding = false
09-02 15:27:10.660  1928  2066 D LGBluetoothAPIService: Sending unbind request.
09-02 15:27:10.662  4250  4337 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,09-02 15:27:10.662  4250  4250 I GKI_LINUX: GKI_exit_task 1 done
09-02 15:27:10.662  4250  4250 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
09-02 15:27:10.663  4250  4250 I BluetoothServiceJni: cleanupNative: return from cleanup
09-02 15:27:10.663  4250  4250 I art     : --- WEIRD: removing null entry 246
09-02 15:27:10.663  4250  4250 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
09-02 15:27:10.664  4250  4250 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
09-02 15:27:10.664  1589  1589 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-02 15:27:10.669  6878  6878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 15:27:10.669  4250  4250 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
09-02 15:27:10.670  6878  6878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 15:27:10.671  7015  7015 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
09-02 15:27:10.672  7015  7015 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
09-02 15:27:10.672  7015  7015 D LGBluetoothEventManager: [BTUI] clear device connection state
09-02 15:27:10.673  1589  1589 D BluetoothAdapter: 644570902: getState() :  mService = null. Returning STATE_OFF
09-02 15:27:10.673  1589  1589 D BluetoothAdapter: 644570902: getState() :  mService = null. Returning STATE_OFF
09-02 15:27:10.675  7015  7015 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,09-02 15:27:10.680  4250  4250 I art     : System.exit called, status: 0
09-02 15:27:10.680  4250  4250 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
09-02 15:27:10.694  7015  7015 D DockEventReceiver: finishStartingService: stopping service
,09-02 15:27:10.704   308   308 V AudioFlinger: 4250 died, releasing its sessions
09-02 15:27:10.704   308   308 V AudioFlinger:  pid 1836 @ 0
09-02 15:27:10.704   308   308 V AudioFlinger:  pid 3395 @ 1
09-02 15:27:10.704   308   308 V AudioFlinger:  pid 3395 @ 2
09-02 15:27:10.704  7015  7015 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
09-02 15:27:10.747  1043  1927 I ActivityManager: Process com.android.bluetooth (pid 4250) has died
09-02 15:27:10.747  1043  1927 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
,09-02 15:27:10.758  2160  2160 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-02 15:27:10.772  7015  7015 D BluetoothPermissionRequest: onReceive
09-02 15:27:10.775  7015  7015 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
,09-02 15:27:10.775  7015  7015 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
09-02 15:27:10.780  7015  7015 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-02 15:27:10.836  1043  1059 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7129 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,09-02 15:27:10.848  7035  7035 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-02 15:27:10.850  7015  7015 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-02 15:27:10.860  7015  7015 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-02 15:27:10.881  7015  7015 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
,09-02 15:27:10.881  7015  7015 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-02 15:27:10.882  7015  7015 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-02 15:27:10.882  7015  7015 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-02 15:27:10.883  7015  7015 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-02 15:27:10.891  7105  7149 W FormManager: Network not available. Please check & try again.
,09-02 15:27:10.903  7015  7015 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-02 15:27:10.903  7015  7015 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-02 15:27:10.903  7015  7015 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-02 15:27:10.903  7015  7015 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-02 15:27:10.903  7015  7015 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-02 15:27:10.904  7015  7015 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-02 15:27:10.909  4743  4743 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-02 15:27:10.910  4743  4743 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-02 15:27:10.911  7105  7150 V FormManager: Network unavailable.
09-02 15:27:10.912  4743  4743 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-02 15:27:10.916  4743  4743 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-02 15:27:10.916  7105  7150 V FormManager: Network unavailable.
09-02 15:27:10.923  7035  7035 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
09-02 15:27:10.923  7035  7035 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-02 15:27:10.923  7035  7035 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-02 15:27:10.925  7129  7129 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
09-02 15:27:10.925  7129  7129 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-02 15:27:10.926  7129  7129 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
09-02 15:27:10.926  7129  7129 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-02 15:27:10.927  7015  7015 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-02 15:27:10.935  4743  7153 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,09-02 15:27:10.938  7015  7015 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 15:27:10.945  4743  7155 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-02 15:27:10.945  4743  7155 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-02 15:27:10.946  7105  7156 W FormManager: Network not available. Please check & try again.
09-02 15:27:10.950  7129  7129 D BluetoothAdapterApp: Loading JNI Library
09-02 15:27:10.956  7105  7157 V FormManager: Network unavailable.
,09-02 15:27:10.960  7063  7063 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,09-02 15:27:10.961  7105  7157 V FormManager: Network unavailable.
09-02 15:27:10.961  7063  7063 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
09-02 15:27:10.962  7063  7063 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
09-02 15:27:10.966  1043  2037 I ActivityManager: Killing 5989:com.android.contacts/u0a19 (adj 15): empty #17
09-02 15:27:10.989  7129  7129 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@221127d4 Instance Count = 1
,09-02 15:27:11.006  7063  7063 D LgDataFeature: LgDataFeature() Constructor: none
,09-02 15:27:11.006  7063  7063 D LgDataFeature: LgDataFeature() Constructor Done, null
09-02 15:27:11.015  7063  7063 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
09-02 15:27:11.017  7063  7063 V SoundPool: load: fd=31, offset=10857164, length=17813, priority=1
09-02 15:27:11.017  7063  7063 V SoundPool: create sampleID=1, fd=30, offset=17813 length=10857164
09-02 15:27:11.017  7063  7063 V SoundPool: doLoad: loading sample sampleID=1
09-02 15:27:11.017  7063  7160 V SoundPool: Start decode
09-02 15:27:11.017  7063  7160 V MediaPlayer[Native]: decode(30, 10857164, 17813)
09-02 15:27:11.018  7063  7063 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
09-02 15:27:11.018   308  1383 V MediaPlayerService: decode(23, 10857164, 17813)
09-02 15:27:11.018   308  1383 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
09-02 15:27:11.018   308  1383 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
09-02 15:27:11.018   308  1383 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
09-02 15:27:11.018   308  1383 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
,09-02 15:27:11.018   308  1383 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
09-02 15:27:11.018   308  1383 V MediaPlayerService: player type = 3
09-02 15:27:11.018   308  1383 V AwesomePlayer: AwesomePlayer create()
09-02 15:27:11.019   308  1383 V AwesomePlayer: reset_l() 
09-02 15:27:11.019   308  1383 V AwesomePlayer: cancelPlayerEvents
09-02 15:27:11.019   308  1383 V AwesomePlayer: setAudioSink() 
09-02 15:27:11.019   308  1383 V AwesomePlayer: reset_l() 
09-02 15:27:11.019   308  1383 V AudioCache: notify(0xb5474800, 8, 0, 0)
09-02 15:27:11.019   308  1383 V AudioCache: ignored
09-02 15:27:11.019   308  1383 V AwesomePlayer: cancelPlayerEvents
,09-02 15:27:11.020   308  1383 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
09-02 15:27:11.020   308  1383 V AwesomePlayer: setDataSource_l dataSource
09-02 15:27:11.020   308  1383 V LGParserOSAL: SniffLGParser start
09-02 15:27:11.020   308  1383 V LGParserOSAL: MainType:5, SubType=0
09-02 15:27:11.020   308  1383 V LGParserOSAL: #### check Mime : application/ogg
09-02 15:27:11.020   308  1383 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
09-02 15:27:11.020   308  1383 E MediaExtractor: Use LGExtractor :application/ogg 
09-02 15:27:11.028  1043  1873 W libprocessgroup: failed to open /acct/uid_10019/pid_5989/cgroup.procs: No such file or directory
09-02 15:27:11.034  7129  7129 D BluetoothAdapterApp: onCreate
,09-02 15:27:11.038  6777  6777 D UEI.SmartControl: QS Service created
09-02 15:27:11.038  7063  7063 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
09-02 15:27:11.047  7063  7063 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-02 15:27:11.048  7063  7063 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
09-02 15:27:11.058  7129  7129 D ProfileConfigQcom: [BTUI] HeadsetService is supported
09-02 15:27:11.058  7129  7129 D ProfileConfigQcom: Adding HeadsetService
09-02 15:27:11.058  7129  7129 D ProfileConfigQcom: [BTUI] A2dpService is supported
09-02 15:27:11.058  7129  7129 D ProfileConfigQcom: Adding A2dpService
09-02 15:27:11.058  7129  7129 D ProfileConfigQcom: [BTUI] HidService is supported
09-02 15:27:11.059  7129  7129 D ProfileConfigQcom: Adding HidService
09-02 15:27:11.059  7129  7129 D ProfileConfigQcom: [BTUI] HealthService is supported
09-02 15:27:11.059  7129  7129 D ProfileConfigQcom: Adding HealthService
09-02 15:27:11.059  7129  7129 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
,09-02 15:27:11.061  7129  7129 D ProfileConfigQcom: [BTUI] PanService is supported
09-02 15:27:11.061  7129  7129 D ProfileConfigQcom: Adding PanService
09-02 15:27:11.061  7129  7129 D ProfileConfigQcom: [BTUI] GattService is supported
09-02 15:27:11.061  7129  7129 D ProfileConfigQcom: Adding GattService
09-02 15:27:11.062  7129  7129 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
09-02 15:27:11.062  7129  7129 D ProfileConfigQcom: Adding BluetoothMapService
09-02 15:27:11.062  7063  7063 V LGMDMManager: Create singleton instance
09-02 15:27:11.062  7129  7129 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
09-02 15:27:11.064  7129  7129 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
09-02 15:27:11.068  7015  7015 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
09-02 15:27:11.071  6777  6777 I UEI.SmartControl: Service initServices...
09-02 15:27:11.071  7129  7129 V LGMDMManagerInternal: Create singleton instance
09-02 15:27:11.071  6777  6777 D UEI.SmartControl: QS start get config
09-02 15:27:11.075   308  1383 V LGParserOSAL: supported mime: application/ogg
09-02 15:27:11.075   308  1383 V AwesomePlayer: setDataSource_l() extractor countTracks=1
09-02 15:27:11.075   308  1383 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
09-02 15:27:11.075   308  1383 V AwesomePlayer: mBitrate = -1 bits/sec
09-02 15:27:11.075   308  1383 V AwesomePlayer: AudioTrack Setting
09-02 15:27:11.075   308  1383 V AwesomePlayer: AudioTrack Setting channelCount = 2
09-02 15:27:11.075   308  1383 V AwesomePlayer: setAudioSource() 
09-02 15:27:11.075   308  1383 V MediaPlayerService: prepare
09-02 15:27:11.075   308  1383 V AwesomePlayer: prepareAsync_l() 
09-02 15:27:11.075   308  1383 V MediaPlayerService: wait for prepare
09-02 15:27:11.076   308  7162 V AwesomePlayer: onPrepareAsyncEvent() 
09-02 15:27:11.076   308  7162 V AwesomePlayer: initAudioDecoder() 
09-02 15:27:11.076   308  7162 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
09-02 15:27:11.076   308  7162 V AudioSystem: isOffloadSupported()
09-02 15:27:11.076   308  7162 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
09-02 15:27:11.076   308  7162 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
09-02 15:27:11.076   308  7162 I AudioFlinger: isAudioPlaybackHookOn() false
09-02 15:27:11.076   308  7162 V AwesomePlayer: getUseOffload() = 0 
09-02 15:27:11.076   308  7162 V OMXCodec: OMXCodec::Create
09-02 15:27:11.076   308  7162 V OMXCodec: findMatchingCodecs()
09-02 15:27:11.076   308  7162 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
,09-02 15:27:11.076   308  7162 V OMXCodec: matchingCodecs.size()=1
09-02 15:27:11.076   308  7162 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
09-02 15:27:11.078   308  7162 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
09-02 15:27:11.078   308  7162 V LGCodecAdapter: LG Codec Adapter start
09-02 15:27:11.078   308  7162 V OMXCodec: OMXCodec Createtor
09-02 15:27:11.078   308  7162 V OMXCodec: setComponentRole
09-02 15:27:11.078   308  7162 V OMXCodec: configureCodec protected=0
09-02 15:27:11.078   308  7162 V LGCodecAdapter: called getLGCodecSpecificData
09-02 15:27:11.078   308  7162 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
09-02 15:27:11.078   308  7162 V LGCodecOSAL: Called LGconfigureCodecMETA
09-02 15:27:11.078   308  7162 V LGCodecOSAL: Called LGconfigureCodecMSG
09-02 15:27:11.078   308  7162 V LGCodecOSAL: Not support LGCodec
09-02 15:27:11.078   308  7162 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
09-02 15:27:11.079   308  7162 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
09-02 15:27:11.079   308  7162 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
09-02 15:27:11.079   308  7162 I AwesomePlayer: Could not offload audio decode, try pcm offload
09-02 15:27:11.079   308  7162 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
09-02 15:27:11.079   308  7162 V AudioSystem: isOffloadSupported()
09-02 15:27:11.079   308  7162 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
09-02 15:27:11.079   308  7162 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
09-02 15:27:11.079   308  7162 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
09-02 15:27:11.079   308  7162 V OMXCodec: init()
09-02 15:27:11.079   308  7162 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
09-02 15:27:11.079   308  7162 V OMXCodec: allocateBuffers
09-02 15:27:11.079   308  7162 V OMXCodec: allocateBuffersOnPort portIndex=0
09-02 15:27:11.079   308  7162 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
09-02 15:27:11.080   308  7162 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7740 on input port
09-02 15:27:11.080   308  7162 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f79c0 on input port
09-02 15:27:11.080   308  7162 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a10 on input port
09-02 15:27:11.081   308  7162 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a60 on input port
09-02 15:27:11.081   308  7162 V OMXCodec: allocateBuffersOnPort portIndex=1
09-02 15:27:11.081   308  7162 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
09-02 15:27:11.081   308  7162 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on output port
09-02 15:27:11.081   308  7162 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on output port
09-02 15:27:11.081   308  7162 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57bb150 on output port
09-02 15:27:11.081   308  7162 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57bb290 on output port
09-02 15:27:11.081   308  7162 V OMXCodec: init() mAsyncCompletion wait!!! 
09-02 15:27:11.086   308  7164 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
09-02 15:27:11.086   308  7164 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
09-02 15:27:11.087   308  7164 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
09-02 15:27:11.087   308  7162 V OMXCodec: init() mAsyncCompletion wait!!! 
09-02 15:27:11.087   308  ,7164 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
09-02 15:27:11.087   308  7164 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
09-02 15:27:11.087   308  7164 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
09-02 15:27:11.087   308  7162 V OMXCodec: init() mAsyncCompletion wait free! 
09-02 15:27:11.087   308  7162 V AwesomePlayer: finishAsyncPrepare_l() 
09-02 15:27:11.087   308  7162 V AudioCache: notify(0xb5474800, 5, 0, 0)
09-02 15:27:11.087   308  7162 V AudioCache: ignored
09-02 15:27:11.087   308  7162 V AudioCache: notify(0xb5474800, 1, 0, 0)
09-02 15:27:11.087   308  7162 V AudioCache: prepared
09-02 15:27:11.087   308  1383 V AudioCache: wait - success
09-02 15:27:11.087   308  1383 V MediaPlayerService: start
09-02 15:27:11.087   308  1383 V AwesomePlayer: play_l() 
09-02 15:27:11.087   308  1383 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
09-02 15:27:11.087   308  1383 V AwesomePlayer: createAudioPlayer_l
09-02 15:27:11.087   308  1383 V AwesomePlayer: seekAudioIfNecessary_l() 
09-02 15:27:11.087   308  1383 V AwesomePlayer: startAudioPlayer_l() 
09-02 15:27:11.087   308  1383 D AudioPlayer: start of Playback, useOffload 0
09-02 15:27:11.087   308  1383 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
09-02 15:27:11.087   308  1383 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
,09-02 15:27:11.094   308  7164 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
09-02 15:27:11.094   308  7164 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
09-02 15:27:11.094   308  7164 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
09-02 15:27:11.094   308  7164 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
09-02 15:27:11.094   308  7164 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
09-02 15:27:11.094   308  7164 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
09-02 15:27:11.095   308  7164 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884848
09-02 15:27:11.095   308  7164 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-02 15:27:11.095   308  7164 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885008
09-02 15:27:11.095   308  7164 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-02 15:27:11.095   308  7164 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044782416
09-02 15:27:11.095   308  7164 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-02 15:27:11.095   308  7164 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044782736
09-02 15:27:11.095   308  7164 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-02 15:27:11.095   308  7164 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
09-02 15:27:11.095   308  7164 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
09-02 15:27:11.095   308  7164 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
,09-02 15:27:11.095   308  7164 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
09-02 15:27:11.095   308  7164 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
09-02 15:27:11.095   308  7164 V OMXCodec: allocateBuffersOnPort portIndex=1
09-02 15:27:11.095   308  7164 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
09-02 15:27:11.096   308  7164 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57bb150 on output port
09-02 15:27:11.096   308  7164 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on output port
09-02 15:27:11.096   308  7164 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on output port
09-02 15:27:11.096   308  7164 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57bb6f0 on output port
09-02 15:27:11.096   308  7164 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
09-02 15:27:11.096   308  7164 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
09-02 15:27:11.096   308  1383 V AudioCache: open(48000, 2, 0x0, 1, 4)
09-02 15:27:11.097   308  1383 V AudioCache: notify(0xb5474800, 6, 0, 0)
09-02 15:27:11.097   308  1383 V AudioCache: ignored
09-02 15:27:11.097   308  1383 V MediaPlayerService: wait for playback complete
09-02 15:27:11.098   308  7165 V AudioCache: write(0xb16ad000, 4096)
09-02 15:27:11.098   308  7165 V AudioCache: memcpy(0xac300000, 0xb16ad000, 4096)
09-02 15:27:11.100   308  7165 V AudioCache: write(0xb16ad000, 4096)
09-02 15:27:11.100   308  7165 V AudioCache: memcpy(0xac301000, 0xb16ad000, 4096)
09-02 15:27:11.100   308  7165 V AudioCache: write(0xb16ad000, 4096)
09-02 15:27:11.100   308  7165 V AudioCache: memcpy(0xac302000, 0xb16ad000, 4096)
09-02 15:27:11.101   308  7165 V AudioCache: write(0xb16ad000, 4096)
09-02 15:27:11.101   308  7165 V AudioCache: memcpy(0xac303000, 0xb16ad000, 4096)
09-02 15:27:11.101   308  7165 V AudioCache: write(0xb16ad000, 4096)
09-02 15:27:11.101   308  7165 V AudioCache: memcpy(0xac304000, 0xb16ad000, 4096)
09-02 15:27:11.103   308  7165 V AudioCache: write(0xb16ad000, 4096)
09-02 15:27:11.103   308  7165 V AudioCache: memcpy(0xac305000, 0xb16ad000, 4096)
,09-02 15:27:11.104   308  7165 V AudioCache: write(0xb16ad000, 4096)
,09-02 15:27:11.104   308  7165 V AudioCache: memcpy(0xac306000, 0xb16ad000, 4096)
09-02 15:27:11.105   308  7165 V AudioCache: write(0xb16ad000, 4096)
09-02 15:27:11.105   308  7165 V AudioCache: memcpy(0xac307000, 0xb16ad000, 4096)
09-02 15:27:11.107   308  7165 V AudioCache: write(0xb16ad000, 4096)
09-02 15:27:11.107   308  7165 V AudioCache: memcpy(0xac308000, 0xb16ad000, 4096)
09-02 15:27:11.108   308  7165 V AudioCache: write(0xb16ad000, 4096)
09-02 15:27:11.108   308  7165 V AudioCache: memcpy(0xac309000, 0xb16ad000, 4096)
09-02 15:27:11.110   308  7165 V AudioCache: write(0xb16ad000, 4096)
09-02 15:27:11.110   308  7165 V AudioCache: memcpy(0xac30a000, 0xb16ad000, 4096)
09-02 15:27:11.111   308  7165 V AudioCache: write(0xb16ad000, 4096)
,09-02 15:27:11.111   308  7165 V AudioCache: memcpy(0xac30b000, 0xb16ad000, 4096)
09-02 15:27:11.112   308  7165 V AudioCache: write(0xb16ad000, 4096)
09-02 15:27:11.112   308  7165 V AudioCache: memcpy(0xac30c000, 0xb16ad000, 4096)
09-02 15:27:11.113   308  7165 V AudioCache: write(0xb16ad000, 4096)
09-02 15:27:11.113   308  7165 V AudioCache: memcpy(0xac30d000, 0xb16ad000, 4096)
09-02 15:27:11.114   308  7165 V AudioCache: write(0xb16ad000, 4096)
09-02 15:27:11.114   308  7165 V AudioCache: memcpy(0xac30e000, 0xb16ad000, 4096)
,09-02 15:27:11.115   308  7165 V AudioCache: write(0xb16ad000, 4096)
09-02 15:27:11.115   308  7165 V AudioCache: memcpy(0xac30f000, 0xb16ad000, 4096)
09-02 15:27:11.116   308  7165 V AudioCache: write(0xb16ad000, 4096)
09-02 15:27:11.116   308  7165 V AudioCache: memcpy(0xac310000, 0xb16ad000, 4096)
09-02 15:27:11.117   308  7165 V AudioCache: write(0xb16ad000, 4096)
09-02 15:27:11.117   308  7165 V AudioCache: memcpy(0xac311000, 0xb16ad000, 4096)
09-02 15:27:11.118   308  7165 V AudioCache: write(0xb16ad000, 4096)
09-02 15:27:11.118   308  7165 V AudioCache: memcpy(0xac312000, 0xb16ad000, 4096)
09-02 15:27:11.119   308  7165 V AudioCache: write(0xb16ad000, 4096)
09-02 15:27:11.119   308  7165 V AudioCache: memcpy(0xac313000, 0xb16ad000, 4096)
09-02 15:27:11.120   308  7165 V AudioCache: write(0xb16ad000, 4096)
09-02 15:27:11.120   308  7165 V AudioCache: memcpy(0xac314000, 0xb16ad000, 4096)
09-02 15:27:11.120   308  7165 V AudioCache: write(0xb16ad000, 4096)
09-02 15:27:11.120   308  7165 V AudioCache: memcpy(0xac315000, 0xb16ad000, 4096)
09-02 15:27:11.121   308  7165 V AudioCache: write(0xb16ad000, 4096)
09-02 15:27:11.121   308  7165 V AudioCache: memcpy(0xac316000, 0xb16ad000, 4096)
09-02 15:27:11.122   308  7165 V AudioCache: write(0xb16ad000, 4096)
09-02 15:27:11.122   308  7165 V AudioCache: memcpy(0xac317000, 0xb16ad000, 4096)
09-02 15:27:11.123   308  7165 V AudioCache: write(0xb16ad000, 4096)
09-02 15:27:11.123   308  7165 V AudioCache: memcpy(0xac318000, 0xb16ad000, 4096)
09-02 15:27:11.123   308  7165 V AudioCache: write(0xb16ad000, 4096)
09-02 15:27:11.124   308  7165 V AudioCache: memcpy(0xac319000, 0xb16ad000, 4096)
09-02 15:27:11.124   308  7165 V AudioCache: write(0xb16ad000, 4096)
09-02 15:27:11.124   308  7165 V AudioCache: memcpy(0xac31a000, 0xb16ad000, 4096)
09-02 15:27:11.125   308  7165 V AudioCache: write(0xb16ad000, 4096)
09-02 15:27:11.125   308  7165 V AudioCache: memcpy(0xac31b000, 0xb16ad000, 4096)
09-02 15:27:11.126   308  7165 V AudioCache: write(0xb16ad000, 4096)
09-02 15:27:11.126   308  7165 V AudioCache: memcpy(0xac31c000, 0xb16ad000, 4096)
09-02 15:27:11.127   308  7165 V AudioCache: write(0xb16ad000, 4096)
09-02 15:27:11.127   308  7165 V AudioCache: memcpy(0xac31d000, 0xb16ad000, 4096)
09-02 15:27:11.128   308  7165 V AudioCache: write(0xb16ad000, 4096)
09-02 15:27:11.128   308  7165 V AudioCache: memcpy(0xac31e000, 0xb16ad000, 4096)
09-02 15:27:11.128   308  7165 V AudioCache: write(0xb16ad000, 4096)
09-02 15:27:11.128   308  7165 V AudioCache: memcpy(0xac31f000, 0xb16ad000, 4096)
09-02 15:27:11.129   308  7165 V AudioCache: write(0xb16ad000, 4096)
09-02 15:27:11.129   308  7165 V AudioCache: memcpy(0xac320000, 0xb16ad000, 4096)
09-02 15:27:11.130   308  7165 V AudioCache: write(0xb16ad000, 4096)
09-02 15:27:11.130   308  7165 V AudioCache: memcpy(0xac321000, 0xb16ad000, 4096)
09-02 15:27:11.131   308  7165 V AudioCache: write(0xb16ad000, 4096)
09-02 15:27:11.131   308  7165 V AudioCache: memcpy(0xac322000, 0xb16ad000, 4096)
09-02 15:27:11.132   308  7165 V AudioCache: write(0xb16ad000, 4096)
09-02 15:27:11.132   308  7165 V AudioCache: memcpy(0xac323000, 0xb16ad000, 4096)
09-02 15:27:11.132   308  7165 V AudioCache: write(0xb16ad000, 4096)
09-02 15:27:11.132   308  7165 V AudioCache: memcpy(0xac324000, 0xb16ad000, 4096)
09-02 15:27:11.133   308  7165 V AudioCache: write(0xb16ad000, 4096)
09-02 15:27:11.133   308  7165 V AudioCache: memcpy(0xac325000, 0xb16ad000, 4096)
09-02 15:27:11.134   308  7165 V AudioCache: write(0xb16ad000, 4096)
09-02 15:27:11.134   308  7165 V AudioCache: memcpy(0xac326000, 0xb16ad000, 4096)
09-02 15:27:11.134   308  7165 V AudioCache: write(0xb16ad000, 4096)
09-02 15:27:11.134   308  7165 V AudioCache: memcpy(0xac327000, 0xb16ad000, 4096)
09-02 15:27:11.135   308  7165 V AudioCache: write(0xb16ad000, 4096)
09-02 15:27:11.135   308  7165 V AudioCache: memcpy(0xac328000, 0xb16ad000, 4096)
09-02 15:27:11.136   308  7165 V AudioCache: write(0xb16ad000, 4096)
09-02 15:27:11.136   308  7165 V AudioCache: mem,cpy(0xac329000, 0xb16ad000, 4096)
09-02 15:27:11.137   308  7165 V AudioCache: write(0xb16ad000, 4096)
09-02 15:27:11.137   308  7165 V AudioCache: memcpy(0xac32a000, 0xb16ad000, 4096)
09-02 15:27:11.137  7129  7129 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-02 15:27:11.138   308  7165 V AudioCache: write(0xb16ad000, 4096)
09-02 15:27:11.138   308  7165 V AudioCache: memcpy(0xac32b000, 0xb16ad000, 4096)
,09-02 15:27:11.138   308  7165 V AudioCache: write(0xb16ad000, 4096)
09-02 15:27:11.138   308  7165 V AudioCache: memcpy(0xac32c000, 0xb16ad000, 4096)
09-02 15:27:11.139   308  7165 V AudioCache: write(0xb16ad000, 4096)
09-02 15:27:11.139   308  7165 V AudioCache: memcpy(0xac32d000, 0xb16ad000, 4096)
09-02 15:27:11.140  7129  7129 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-02 15:27:11.140   308  7165 V AudioCache: write(0xb16ad000, 4096)
09-02 15:27:11.140   308  7165 V AudioCache: memcpy(0xac32e000, 0xb16ad000, 4096)
09-02 15:27:11.141  7129  7129 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-02 15:27:11.141  7129  7129 V BluetoothSapReceiver: SapReceiver onReceive 
09-02 15:27:11.141   308  7165 V AudioCache: write(0xb16ad000, 4096)
09-02 15:27:11.141   308  7165 V AudioCache: memcpy(0xac32f000, 0xb16ad000, 4096)
09-02 15:27:11.142   308  7165 V AudioCache: write(0xb16ad000, 4096)
09-02 15:27:11.142  7129  7129 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-02 15:27:11.142   308  7165 V AudioCache: memcpy(0xac330000, 0xb16ad000, 4096)
09-02 15:27:11.142  7129  7129 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
09-02 15:27:11.142   308  7165 V AudioCache: write(0xb16ad000, 4096)
09-02 15:27:11.143   308  7165 V AudioCache: memcpy(0xac331000, 0xb16ad000, 4096)
09-02 15:27:11.143   308  7164 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
09-02 15:27:11.143   308  7165 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
09-02 15:27:11.143   308  7165 V AwesomePlayer: postAudioEOS() 
09-02 15:27:11.143   308  7165 V AudioCache: write(0xb16ad000, 280)
09-02 15:27:11.143   308  7165 V AudioCache: memcpy(0xac332000, 0xb16ad000, 280)
09-02 15:27:11.144   308  7162 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
09-02 15:27:11.144   308  7162 V AwesomePlayer: onStreamDone
09-02 15:27:11.145   308  7162 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
09-02 15:27:11.145   308  7162 V AudioCache: notify(0xb5474800, 2, 0, 0)
09-02 15:27:11.145   308  7162 V AudioCache: playback complete
09-02 15:27:11.145   308  7162 V AwesomePlayer: pause_l() 
09-02 15:27:11.145   308  7162 V AudioCache: notify(0xb5474800, 7, 0, 0)
09-02 15:27:11.145   308  7162 V AudioCache: ignored
09-02 15:27:11.145   308  7162 V AwesomePlayer: cancelPlayerEvents
09-02 15:27:11.145   308  7162 D AudioPlayer: Pause Playback at 1068125
09-02 15:27:11.145   308  1383 V AudioCache: wait - success
09-02 15:27:11.145   308  1383 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
09-02 15:27:11.145   308  1383 V AwesomePlayer: reset_l() 
09-02 15:27:11.145   308  1383 V AudioCache: notify(0xb5474800, 8, 0, 0)
09-02 15:27:11.145   308  1383 V AudioCache: ignored
09-02 15:27:11.145   308  1383 V AwesomePlayer: cancelPlayerEvents
09-02 15:27:11.145   308  1383 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
09-02 15:27:11.146   308  1383 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
09-02 15:27:11.146   308  1383 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
09-02 15:27:11.146   308  1383 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
09-02 15:27:11.146   308  1383 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
09-02 15:27:11.146   308  7164 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
09-02 15:27:11.146   308  7164 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
09-02 15:27:11.146  7063  7063 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
09-02 15:27:11.146   308  7164 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
09-02 15:27:11.146   308  7164 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a60 on port 0
09-02 15:27:11.146   308  7164 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
09-02 15:27:11.147   308  7164 V OMXCodec: [OMX.google.vorb,is.decoder] freeing buffer 0xb54f7a10 on port 0
09-02 15:27:11.147   308  7164 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
09-02 15:27:11.147   308  7164 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f79c0 on port 0
09-02 15:27:11.147   308  7164 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
09-02 15:27:11.147   308  7164 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7740 on port 0
09-02 15:27:11.147   308  7164 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
09-02 15:27:11.147   308  7164 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
09-02 15:27:11.147   308  7164 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb57bb6f0 on port 1
09-02 15:27:11.147   308  7164 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
09-02 15:27:11.147   308  7164 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ab0 on port 1
09-02 15:27:11.147   308  7164 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
09-02 15:27:11.147   308  7164 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b50 on port 1
09-02 15:27:11.147   308  7164 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
09-02 15:27:11.147   308  7164 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb57bb150 on port 1
09-02 15:27:11.147   308  7164 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-02 15:27:11.147   308  7164 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
09-02 15:27:11.147   308  1383 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
09-02 15:27:11.147   308  1383 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
09-02 15:27:11.148   308  7164 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
09-02 15:27:11.148   308  7164 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
09-02 15:27:11.148   308  7164 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
09-02 15:27:11.148   308  1383 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
09-02 15:27:11.148   308  1383 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
09-02 15:27:11.148   308  1383 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
09-02 15:27:11.149   308  1383 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
09-02 15:27:11.149   308  1383 D AudioPlayer: AudioPlayer releasing audio source
09-02 15:27:11.149   308  1383 D AudioPlayer: AudioPlayer done releasing audio source
09-02 15:27:11.149   308  1383 V AwesomePlayer: reset_l() 
09-02 15:27:11.149   308  1383 V AwesomePlayer: cancelPlayerEvents
09-02 15:27:11.149   308  1383 V AwesomePlayer: ~AwesomePlayer call
09-02 15:27:11.149   308  1383 V AwesomePlayer: reset_l() 
09-02 15:27:11.149   308  1383 V AwesomePlayer: cancelPlayerEvents
09-02 15:27:11.150  7063  7160 V SoundPool: close(30)
,09-02 15:27:11.150  7063  7160 V SoundPool: pointer = 0x9fea3000, size = 205080, sampleRate = 48000, numChannels = 2
09-02 15:27:11.150  7080  7080 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
09-02 15:27:11.150  7063  7063 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
,09-02 15:27:11.155  7063  7063 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:4105
,09-02 15:27:11.374  6777  6777 I UEI.SmartControl: Supports setup maps: true,
09-02 15:27:11.377  6777  6777 D UEI.SmartControl: QS start statue = true Error code = 0
,09-02 15:27:11.378  6777  6777 I UEI.SmartControl: QS version = v2.7.10.1_RC1
09-02 15:27:11.378  6777  6777 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
09-02 15:27:11.378  6777  6777 I UEI.SmartControl: ### init IR Blaster...
,09-02 15:27:11.381  6777  6777 D serial_port: Configuring serial port
09-02 15:27:11.381  6777  6777 E UEI.SmartControl: UEIBLaster setting for 616
09-02 15:27:11.381  6777  6777 I UEI.SmartControl: Setting serial record hearder size = 2
09-02 15:27:11.381  6777  6777 I UEI.SmartControl: configuring settings for MAXQ616
09-02 15:27:11.381  6777  6777 I UEI.SmartControl: Get version...
09-02 15:27:11.400  6777  7167 D UEI.SmartControl: serial port data available: 21
,09-02 15:27:11.426  6777  6777 D UEI.SmartControl: MAXQ616 A2-X4 software.
09-02 15:27:11.426  6777  6777 I UEI.SmartControl: IR Blaster version: 256702256704300002
,09-02 15:27:11.426  6777  6777 I UEI.SmartControl: QS saving settings...
,09-02 15:27:11.428  6777  6777 D UEI.SmartControl: IR Blaster version: 25672567
09-02 15:27:11.446  6777  7167 D UEI.SmartControl: serial port data available: 4
,09-02 15:27:11.477  6777  7170 I UEI.SmartControl: Device manager: loading config....
,09-02 15:27:11.478  6777  7170 D UEI.SmartControl: ----------- loading internal config...
09-02 15:27:11.478  6777  6777 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
09-02 15:27:11.480  6777  6777 E UEI.SmartControl: Services init done
09-02 15:27:11.481  6777  6777 D UEI.SmartControl: QS Service init finished
09-02 15:27:11.483  6777  6777 D UEI.SmartControl: QS Service version name: 2.1.91
09-02 15:27:11.483  6777  6777 D UEI.SmartControl: QS Service version code: 201091
09-02 15:27:11.484  6777  6777 D UEI.SmartControl: Service requested: Control
09-02 15:27:11.486  6777  7170 E UEI.SmartControl: Loading SETTINGS...
09-02 15:27:11.489  6777  6777 D UEI.SmartControl: Request IControl service: devices are loaded...
09-02 15:27:11.493  7063  7063 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
09-02 15:27:11.493  6777  6777 D UEI.SmartControl: Internal service binding...
09-02 15:27:11.494  6777  6793 I UEI.SmartControl: ------ IControl API: 11
09-02 15:27:11.494  6777  6793 D UEI.SmartControl: File observer start...
09-02 15:27:11.495  6777  6793 E UEI.SmartControl: IR Port is disabled: false
09-02 15:27:11.496  6777  6793 D UEI.SmartControl: Starting file observer...
,09-02 15:27:11.498  6777  7170 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
09-02 15:27:11.499  6777  6793 I UEI.SmartControl: Registering callback...
09-02 15:27:11.501  6777  6792 I UEI.SmartControl: ------ IControl API: 19
09-02 15:27:11.503  6777  6792 I UEI.SmartControl: Registering Services Ready callback...
09-02 15:27:11.516  6777  7169 I UEI.SmartControl: Notify AllClients services are ready: 0
09-02 15:27:11.516  6777  7169 D UEI.SmartControl: -----service ready thread exits
,09-02 15:27:11.517  7063  7078 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
,09-02 15:27:11.518  7063  7158 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
09-02 15:27:11.518  7063  7158 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
09-02 15:27:11.520  7063  7063 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
09-02 15:27:11.521  7063  7063 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
09-02 15:27:11.522  6777  6793 I UEI.SmartControl: ------ IControl API: 8
09-02 15:27:11.526  7063  7063 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
09-02 15:27:11.527  7063  7063 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
09-02 15:27:11.528  7063  7063 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
09-02 15:27:11.529  7063  7063 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
,09-02 15:27:11.532  7063  7063 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
09-02 15:27:11.536  7063  7063 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
09-02 15:27:11.538  7063  7063 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
09-02 15:27:11.542  7063  7063 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,09-02 15:27:11.544  7063  7063 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
09-02 15:27:11.546  7063  7063 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-02 15:27:11.547  7063  7063 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
09-02 15:27:11.549  7063  7063 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
09-02 15:27:11.551  7063  7063 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
09-02 15:27:11.552  7063  7063 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
,09-02 15:27:11.554  7063  7063 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1472822831554]
09-02 15:27:11.559  7063  7063 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
09-02 15:27:11.564  1043  2014 I ActivityManager: Killing 6593:com.android.gallery3d/u0a27 (adj 15): empty #17
09-02 15:27:11.596  7063  7172 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,09-02 15:27:11.642  1043  2014 I ActivityManager: Killing 6561:com.lge.email/u0a23 (adj 15): empty #18
,09-02 15:27:11.727  1043  1865 W libprocessgroup: failed to open /acct/uid_10023/pid_6561/cgroup.procs: No such file or directory
,09-02 15:27:11.736  1043  1962 W libprocessgroup: failed to open /acct/uid_10027/pid_6593/cgroup.procs: No such file or directory
09-02 15:27:11.737  7063  7063 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
09-02 15:27:11.740  7063  7063 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-02 15:27:11.741  7063  7063 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
09-02 15:27:11.742  7063  7063 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
09-02 15:27:11.743  7063  7063 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
09-02 15:27:11.744  7063  7063 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
09-02 15:27:11.745  7063  7063 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
,09-02 15:27:11.762  7063  7063 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,09-02 15:27:12.462  1043  1059 D WifiServiceImplEx: setWifiEnabled: true pid=6878, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-02 15:27:12.463  1043  1059 D WifiService: setWifiEnabled: true pid=6878, uid=10118
09-02 15:27:12.463  1043  1059 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-02 15:27:12.495  1043  1043 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-02 15:27:12.495  1043  1043 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-02 15:27:12.495  1043  1043 D Ulp_jni : JNI:system_update. Event-4
,09-02 15:27:12.499  1043  1377 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
09-02 15:27:12.499  1043  1377 I LGFTMITEM: [GET_FTM][id=6], offset=12288
09-02 15:27:12.502  1043  1377 E WifiUtil: wfc_util_ffile_check_copy(): pid[1043] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
09-02 15:27:12.502  1043  1377 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-02 15:27:12.502  1043  1377 E WifiUtil: wfc_util_ffile_check_copy(): pid[1043] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
09-02 15:27:12.502  1043  1377 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-02 15:27:12.502  1043  1377 I WifiUtil: Intf0MacAddress=C49A027FFB5D
09-02 15:27:12.502  1043  1377 E WifiHW  : unknown target_country: EU , set to default
09-02 15:27:12.502  1043  1377 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
09-02 15:27:12.502  1043  1377 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
09-02 15:27:12.502  1043  1377 I WifiUtil: gEnableBmps=1
09-02 15:27:12.532  1043  1431 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-02 15:27:12.540  1043  1119 D Tethering: MasterInitialState.processMessage what=3
09-02 15:27:12.548  6878  6878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 15:27:12.553  6878  6878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 15:27:12.554  1043  1431 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-02 15:27:12.561  1043  1114 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-02 15:27:12.563  1043  1119 D Tethering: MasterInitialState.processMessage what=3
09-02 15:27:12.572  6878  6878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 15:27:12.575  6878  6878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 15:27:12.577  6433  6433 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
09-02 15:27:12.581  6433  7034 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-02 15:27:12.592  5708  5708 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,09-02 15:27:12.602  5708  5708 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
09-02 15:27:12.628  2160  2160 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-02 15:27:12.684  1043  1114 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-02 15:27:12.693  1043  1962 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7197 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
09-02 15:27:12.701  1043  1114 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-02 15:27:12.702  1043  1114 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 15:27:12.715   341   341 I art     : Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 456us total 22.337ms
,09-02 15:27:12.735   341   341 I art     : Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 447us total 20.015ms
09-02 15:27:12.755   341   341 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 409us total 19.745ms
,09-02 15:27:12.763  7197  7197 I AppUp4:AppBoxCP: onCreate
09-02 15:27:12.764  7197  7197 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
09-02 15:27:12.774  7197  7197 I AppUp4:DB:  setFingerPrint start
,09-02 15:27:12.774  7197  7197 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
09-02 15:27:12.783  7197  7197 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
09-02 15:27:12.783  7197  7197 I AppUp4:DB:  SDK version = 21
09-02 15:27:12.783  7197  7197 I AppUp4:DB:  beforefinger == newfinger no write in DB
09-02 15:27:12.784  7197  7197 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
09-02 15:27:12.786  7197  7197 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-02 15:27:12.786  7197  7197 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-02 15:27:12.788  7197  7197 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-02 15:27:12.788  7197  7197 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-02 15:27:12.793  7197  7197 I AppUp4:CustModeStarterReceiver: onReceive
,09-02 15:27:12.844  7197  7197 D LgDataFeature: LgDataFeature() Constructor: none
09-02 15:27:12.845  7197  7197 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-02 15:27:12.855  7197  7197 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2f87e5be
,09-02 15:27:12.856  7197  7197 D AppUp4:CustFacade: isCustomizationCompleted : false
09-02 15:27:12.856  7197  7197 D AppUp4:CustFacade: isPhone : true
09-02 15:27:12.857  7197  7197 D AppUp4:CustModeStarterReceiver: begin check event
09-02 15:27:12.858  7197  7197 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
09-02 15:27:12.859  7197  7197 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
09-02 15:27:12.860  7197  7217 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
09-02 15:27:12.860  7197  7217 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
09-02 15:27:12.860  7197  7217 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
,09-02 15:27:12.864  1043  1998 I ActivityManager: Killing 6652:com.google.android.apps.docs/u0a61 (adj 15): empty #17
09-02 15:27:12.985  4743  4743 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-02 15:27:12.987  4743  4743 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-02 15:27:12.988  1043  1891 W libprocessgroup: failed to open /acct/uid_10061/pid_6652/cgroup.procs: No such file or directory
,09-02 15:27:12.992  4743  4743 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-02 15:27:12.995  4743  4743 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-02 15:27:13.004  4743  7223 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,09-02 15:27:13.014  4743  7224 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-02 15:27:13.014  4743  7224 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,09-02 15:27:13.080  1043  2014 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7229 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,09-02 15:27:13.152  7229  7229 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-02 15:27:13.153  7229  7229 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-02 15:27:13.154  7229  7229 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-02 15:27:13.155  7229  7229 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,09-02 15:27:13.248  7229  7229 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,09-02 15:27:13.264  7229  7229 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,09-02 15:27:13.268   304   880 D SoftapController: Softap fwReload - Ok
09-02 15:27:13.270  1043  1377 E NetdConnector: NDC Command {53 softap fwreload wlan0 STA} took too long (761ms)
09-02 15:27:13.271   304   880 D CommandListener: Setting iface cfg
09-02 15:27:13.271   304   880 D CommandListener: Trying to bring down wlan0
09-02 15:27:13.272   304   880 D CommandListener: Clearing all IP addresses on wlan0
09-02 15:27:13.274  1043  1377 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
09-02 15:27:13.275  7259  7259 W wpa_supplicant: type=1400 audit(0.0:167): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-02 15:27:13.275  7259  7259 W wpa_supplicant: type=1400 audit(0.0:168): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-02 15:27:13.297  1043  1119 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-02 15:27:13.302  7259  7259 I wpa_supplicant: Successfully initialized wpa_supplicant
09-02 15:27:13.303  7229  7229 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-02 15:27:13.329  7229  7229 D LgDataFeature: LgDataFeature() Constructor: none
09-02 15:27:13.329  7229  7229 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-02 15:27:13.336  7259  7259 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-02 15:27:13.336  7259  7259 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
09-02 15:27:13.338  1043  1119 D Tethering: InitialState.processMessage what=4
09-02 15:27:13.342  1043  1119 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-02 15:27:13.374  1043  1377 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-02 15:27:13.374  1043  1377 E WifiStateMachine: useWiFiOffloading() : false
09-02 15:27:13.374  1043  1377 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,09-02 15:27:13.376  1928  1928 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
09-02 15:27:13.377  1043  1377 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
09-02 15:27:13.377  1043  1377 D WifiMonitor: connecting to supplicant
09-02 15:27:13.377  1043  1043 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
09-02 15:27:13.378  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 15:27:13.378  6878  6878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 15:27:13.379  6878  6878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 15:27:13.434  7229  7229 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,09-02 15:27:13.436  7259  7259 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-02 15:27:13.467  7229  7229 I HubEmail: JNI_OnLoad()
09-02 15:27:13.467  7229  7229 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-02 15:27:13.467  7229  7229 I HubEmail: registerNatives()
09-02 15:27:13.467  7229  7229 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-02 15:27:13.467  7229  7229 I HubEmail: registerNativeMethods()
09-02 15:27:13.467  7229  7229 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-02 15:27:13.467  7229  7229 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,09-02 15:27:13.472  3395  3395 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-02 15:27:13.472  3395  3395 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-02 15:27:13.473  3395  3395 I LgeMiscReceiver: networkInfo.isConnected() = false
09-02 15:27:13.481  7259  7259 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,09-02 15:27:13.488  1043  1377 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
09-02 15:27:13.488  1043  1377 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
09-02 15:27:13.489  1043  1377 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
09-02 15:27:13.489  1043  1377 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
09-02 15:27:13.490  1043  1377 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
09-02 15:27:13.490  1043  1377 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-02 15:27:13.490  1043  1377 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
09-02 15:27:13.491  1043  1377 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-02 15:27:13.491  1043  1377 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
09-02 15:27:13.491  1043  1377 D WifiNative-wlan0: doString: [DRIVER MACADDR]
09-02 15:27:13.492  7259  7259 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
09-02 15:27:13.493  1043  1377 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
09-02 15:27:13.493  1043  1377 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
09-02 15:27:13.493  1043  1377 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
09-02 15:27:13.495  1043  7268 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
09-02 15:27:13.495  1043  7268 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
09-02 15:27:13.495  1043  7268 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
09-02 15:27:13.495  1043  7268 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,09-02 15:27:13.518  1043  2037 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7269 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,09-02 15:27:13.522  1043  1377 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-02 15:27:13.522  1043  1377 E WifiStateMachine: useWiFiOffloading() : false
09-02 15:27:13.522  1043  1377 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-02 15:27:13.522  1043  1043 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 15:27:13.522  1043  1043 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 15:27:13.522  1043  1043 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 15:27:13.522  1043  1043 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 15:27:13.522  1043  1043 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-02 15:27:13.523  1043  1377 D WifiNative-wlan0: doBoolean: SET update_config 1
09-02 15:27:13.524  1043  1377 D WifiNative-wlan0: SET update_config 1: returned true
09-02 15:27:13.524  1043  1377 D WifiConfigStore: Loading config and enabling all networks 
09-02 15:27:13.524  1043  1377 D WifiNative-wlan0: doString: [LIST_NETWORKS]
09-02 15:27:13.524  1043  1377 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
09-02 15:27:13.528  1928  1928 D WfdService: Waiting for WifiP2p enabling
09-02 15:27:13.529  1043  1043 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
09-02 15:27:13.530  1043  1395 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
09-02 15:27:13.530  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 15:27:13.531  6878  6878 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 15:27:13.531  6878  6878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 15:27:13.531  6878  6878 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 15:27:13.531  6878  6878 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 15:27:13.531  6878  6878 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 15:27:13.531  6878  6878 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 15:27:13.531  6878  6878 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 15:27:13.531  6878  6878 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 15:27:13.531  6878  6878 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-02 15:27:13.531  6878  6878 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 15:27:13.531  6878  6878 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-02 15:27:13.538  1043  1377 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
09-02 15:27:13.539  6878  6878 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 15:27:13.539  6878  6878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 15:27:13.539  6878  6878 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 15:27:13.539  6878  6878 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 15:27:13.539  6878  6878 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 15:27:13.539  6878  6878 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 15:27:13.539  6878  6878 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 15:27:13.539  6878  6878 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 15:27:13.539  6878  6878 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-02 15:27:13.539  6878  6878 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 15:27:13.539  6878  6878 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-02 15:27:13.542  7105  7265 W FormManager: Network not available. Please check & try again.
09-02 15:27:13.543  7229  7267 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 15:27:13.547  7105  7266 V FormManager: Network unavailable.
,09-02 15:27:13.549  7105  7266 V FormManager: Network unavailable.
09-02 15:27:13.554  1043  1377 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
09-02 15:27:13.554  1043  1377 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-02 15:27:13.555  1043  2018 I ActivityManager: Killing 6693:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
09-02 15:27:13.587  1043  1377 D WifiStateMachine: enableVerboseLogging : level 2
09-02 15:27:13.587  1043  1377 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
,09-02 15:27:13.588  1043  1377 D WifiNative-wlan0: SET device_name g3_global_com: returned true
09-02 15:27:13.588  1043  1377 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
09-02 15:27:13.590  1043  1377 D WifiNative-wlan0: SET manufacturer LGE: returned true
09-02 15:27:13.590  1043  1377 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
09-02 15:27:13.591  1043  1891 W libprocessgroup: failed to open /acct/uid_10080/pid_6693/cgroup.procs: No such file or directory
09-02 15:27:13.591  1043  1377 D WifiNative-wlan0: SET model_name LG-D855: returned true
09-02 15:27:13.592  1043  1377 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
09-02 15:27:13.593  1043  1377 D WifiNative-wlan0: SET model_number LG-D855: returned true
09-02 15:27:13.593  1043  1377 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
09-02 15:27:13.594  1043  1377 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
09-02 15:27:13.594  1043  1377 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
09-02 15:27:13.595  1043  1377 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
09-02 15:27:13.595  1043  1377 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
09-02 15:27:13.596  1043  1377 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
09-02 15:27:13.598  1928  1928 D WfdsService: Supplicant Connection state is changed : true
09-02 15:27:13.598  1928  2260 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
09-02 15:27:13.598  1928  2260 D WfdsService: Set the WFDS Monitor: true
09-02 15:27:13.598  1928  2260 D WfdsMonitor: WfdsMonitorThread create
09-02 15:27:13.598  1043  1377 D WifiStateMachine: Setting OUI to DA-A1-19
09-02 15:27:13.598  1043  1377 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
09-02 15:27:13.598  1928  2260 D WfdsMonitor: WFDS Monitor is created and started
09-02 15:27:13.598  1928  2260 D WfdsService: WiFi: Supplicant connection re-established
09-02 15:27:13.598  1043  1377 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
09-02 15:27:13.598  1043  1377 D WifiNative-HAL: Setting external_sim to 1
09-02 15:27:13.598  1043  1377 D WifiNative-wlan0: doBoolean: SET external_sim 1
09-02 15:27:13.599  1928  7292 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
09-02 15:27:13.600  1928  7292 E CtrlSupplicant: Succeed to open control connection
09-02 15:27:13.600  1043  1377 D WifiNative-wlan0: SET external_sim 1: returned true
09-02 15:27:13.600  1043  1377 I WifiNative-HAL: startHal
09-02 15:27:13.600  1043  1377 D wifi    : setting scan oui 0x9538d060
09-02 15:27:13.600  1928  7292 E CtrlSupplicant: Succeed to open monitor connection
09-02 15:27:13.600  1928  7292 D WfdsMonitor: Supplicant connection established
09-02 15:27:13.600  1928  2260 D WfdsService: Connected to the supplicant for wfds
,09-02 15:27:13.601  1043  1377 D WifiStateMachine: Setting OUI to DA-A1-19
09-02 15:27:13.601  1043  1377 I WifiNative-HAL: startHal
09-02 15:27:13.601  1043  1377 D wifi    : setting scan oui 0x9538d060
09-02 15:27:13.602  1043  1377 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
09-02 15:27:13.604  1043  1377 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
09-02 15:27:13.604  1043  1377 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
09-02 15:27:13.605  7259  7259 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
09-02 15:27:13.605  1043  1377 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
09-02 15:27:13.606  1043  1377 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-02 15:27:13.607  7259  7259 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-02 15:27:13.607  1043  1377 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-02 15:27:13.607  1043  1377 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
09-02 15:27:13.607  7259  7259 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
09-02 15:27:13.607  1043  1377 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
09-02 15:27:13.608  1043  1377 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-02 15:27:13.608  7259  7259 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-02 15:27:13.608  1043  1377 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-02 15:27:13.608  1043  1377 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-02 15:27:13.608  7259  7259 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-02 15:27:13.608  1043  1377 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-02 15:27:13.608  1043  1377 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
09-02 15:27:13.609  7259  7259 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
09-02 15:27:13.609  1043  1377 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
09-02 15:27:13.609  1043  1377 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-02 15:27:13.609  7259  7259 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-02 15:27:13.609  1043  1377 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-02 15:27:13.610  1043  1377 E WifiNative: : [186,871,976 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
09-02 15:27:13.610  1043  1377 D WifiNative-wlan0: doBoolean: RECONNECT
09-02 15:27:13.611  1043  1377 D WifiNative-wlan0: RECONNECT: returned true
09-02 15:27:13.611  1043  1377 D WifiNative-wlan0: doString: [STATUS]
09-02 15:27:13.611  1043  7268 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
09-02 15:27:13.611  1043  7268 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
09-02 15:27:13.611  1043  1377 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-02 15:27:13.612  1043  1377 D WifiNative-wlan0: doBoolean: SET ps 1
09-02 15:27:13.612  1043  1377 D WifiNative-wlan0: SET ps 1: returned true
,09-02 15:27:13.612  1043  1374 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=131203 target=com.android.internal.util.StateMachine$SmHandler }
09-02 15:27:13.614   304   880 D CommandListener: Setting iface cfg
09-02 15:27:13.614   304   880 D CommandListener: Trying to bring up p2p0
09-02 15:27:13.614  1043  1374 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-02 15:27:13.614  1043  1374 D LGWifiP2pService: P2pEnablingState
09-02 15:27:13.614  1043  1043 D WifiScanningService: SCAN_AVAILABLE : 3
09-02 15:27:13.614  1043  1374 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
09-02 15:27:13.614  1043  1043 D RttService: SCAN_AVAILABLE : 3
09-02 15:27:13.614  1043  1374 D LGWifiP2pService: P2p socket connection successful
09-02 15:27:13.614  1043  1374 D LGWifiP2pService: P2pEnabledState
09-02 15:27:13.615  1043  1542 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-02 15:27:13.615  1043  1542 I WifiNative-HAL: startHal
09-02 15:27:13.615  1043  1542 D wifi    : getting scan capabilities on interface[1] = 0x9538d060
09-02 15:27:13.615  1043  1542 D wifi    : failed to get capabilities : -3
09-02 15:27:13.615  1043  1542 E WifiScanningService: could not get scan capabilities
09-02 15:27:13.615  1043  1374 D LGWifiP2pService: sending p2p connection changed broadcast
09-02 15:27:13.615  1043  1544 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-02 15:27:13.616  1928  1928 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
09-02 15:27:13.616  1928  1928 D WfdsService: WifiP2pState is changed : true
09-02 15:27:13.616  1043  1374 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
09-02 15:27:13.616  1928  2260 D WfdsService: Receive the WFDS_ENABLE Method
09-02 15:27:13.616  1928  2260 D WfdsService: Set the WFDS Monitor: true
09-02 15:27:13.616  1928  2260 D WfdsService: Connected to the supplicant for wfds
09-02 15:27:13.616  1928  2260 D WfdsJNI : doCommand: WFDS_SET TRUE
09-02 15:27:13.616  1043  1377 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
09-02 15:27:13.616  7259  7259 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
09-02 15:27:13.617  1928  2260 D WfdsService: selectPreferredScanChannel [36]
09-02 15:27:13.617  1928  2260 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
09-02 15:27:13.617  1043  1377 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
09-02 15:27:13.617  1043  1377 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
09-02 15:27:13.617  1043  1374 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
09-02 15:27:13.618  1043  1377 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
09-02 15:27:13.618  1043  1374 D WifiNative-p2p0: doBoolean: SET device_name G3
09-02 15:27:13.618  1043  1377 E WifiStateMachine:  DisconnectedState what:132106 1 0
09-02 15:27:13.618  1928  1928 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
09-02 15:27:13.618  1043  1374 D WifiNative-p2p0: SET device_name G3: returned true
09-02 15:27:13.618  1043  1374 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
09-02 15:27:13.618  1043  1374 D LGWifiP2pService: before postfix = G3
09-02 15:27:13.618  1043  1374 D WifiServerServiceExt: postfix byte check : 2
09-02 15:27:13.618  1043  1374 D LGWifiP2pService: after postfix = G3
09-02 15:27:13.618  1043  1374 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
09-02 15:27:13.618  1043  1377 E WifiStateMachine:  ConnectModeState what:132106 1 0
09-02 15:27:13.618  1928  1928 D WfdsService: isConnected: false
09-02 15:27:13.619  1043  1377 E WifiStateMachine:  DriverStartedState what:132106 1 0
09-02 15:27:13.619  1043  1374 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
09-02 15:27:13.619  1043  1377 I WifiServerServiceExt: setWifiDualbandAPConnection band : ,1
09-02 15:27:13.619  1043  1374 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
09-02 15:27:13.619  7259  7259 E wpa_supplicant: nWIFIDualbandAPConnection: 1
09-02 15:27:13.619  1043  1374 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
09-02 15:27:13.619  1043  1374 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
09-02 15:27:13.620  1043  1374 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
09-02 15:27:13.620  1043  1374 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
09-02 15:27:13.620  1043  1377 E WifiStateMachine:  DisconnectedState what:132096 -100 0
09-02 15:27:13.620  1043  1377 E WifiStateMachine:  ConnectModeState what:132096 -100 0
09-02 15:27:13.621  1043  1374 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
09-02 15:27:13.621  1043  1374 D WifiNative-HAL: p2pGetDeviceAddress
09-02 15:27:13.621  1043  1377 E WifiStateMachine:  DriverStartedState what:132096 -100 0
09-02 15:27:13.621  1043  1377 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
09-02 15:27:13.621  7259  7259 E wpa_supplicant: disconnect_rssi_lvl: -100
09-02 15:27:13.621  1043  1374 D WifiNative-HAL: p2pGetDeviceAddress returning 
09-02 15:27:13.622  1043  1377 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
09-02 15:27:13.622  1043  1374 D LGWifiP2pService: DeviceAddress: 
09-02 15:27:13.622  1043  1374 D WifiNative-p2p0: doBoolean: P2P_FLUSH
09-02 15:27:13.622  1928  1928 I WfdStateTracker: handleP2pThisDeviceChanged
09-02 15:27:13.622  1928  1928 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
09-02 15:27:13.623  1928  1928 D WfdsService: Update P2p Interface State: 3
,09-02 15:27:13.624  1043  1377 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
,09-02 15:27:13.624  1043  1377 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
09-02 15:27:13.624  1043  1377 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
09-02 15:27:13.624  1043  1374 D WifiNative-p2p0: P2P_FLUSH: returned true
09-02 15:27:13.624  1043  1374 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
09-02 15:27:13.625  1043  1374 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
09-02 15:27:13.625  1043  1374 D WifiNative-p2p0: doString: [LIST_NETWORKS]
09-02 15:27:13.625  1043  1374 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
09-02 15:27:13.625  1043  1374 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
09-02 15:27:13.636  1043  1374 D WifiNative-p2p0: SAVE_CONFIG: returned true
09-02 15:27:13.636  1043  1374 D LGWifiP2pService: sending p2p persistent groups changed broadcast
,09-02 15:27:13.636  1043  1374 D LGWifiP2pService: InactiveState
09-02 15:27:13.636  1043  1374 D LGWifiP2pService: InactiveState{ when=-11ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-02 15:27:13.637  1043  1374 D LGWifiP2pService: P2pEnabledState{ when=-11ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-02 15:27:13.637  1043  1374 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
09-02 15:27:13.637  7259  7259 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-02 15:27:13.638  7259  7259 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-02 15:27:13.638  1043  7268 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-02 15:27:13.638  1043  7268 E WifiMonitor: WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-02 15:27:13.638  1043  7268 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-02 15:27:13.638  1043  7268 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-02 15:27:13.638  7259  7259 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-02 15:27:13.639  7259  7259 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 15:27:13.639  1043  1377 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
09-02 15:27:13.639  1043  7268 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-02 15:27:13.639  1043  7268 E WifiMonitor: WifiMonitor:p2p0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 15:27:13.639  1043  7268 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 15:27:13.639  1043  7268 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 15:27:13.640  1043  1377 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
09-02 15:27:13.640  1928  7292 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-02 15:27:13.640  7259  7259 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-02 15:27:13.640  1043  1377 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
09-02 15:27:13.640  1043  1377 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
09-02 15:27:13.640  1043  1377 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
09-02 15:27:13.640  7259  7259 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-02 15:27:13.641  1043  7268 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-02 15:27:13.641  1043  7268 E WifiMonitor: WifiMonitor:p2p0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-02 15:27:13.641  1043  7268 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-02 15:27:13.641  1043  7268 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-02 15:27:13.641  1928  7292 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-02 15:27:13.641  7259  7259 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-02 15:27:13.641  7259  7259 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 15:27:13.641  1928  7292 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-02 15:27:13.641  1043  7268 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-02 15:27:13.641  1043  7268 E WifiMonitor: WifiMonitor:p2p0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 15:27:13.641  1043  7268 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 15:27:13.641  1043  7268 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 15:27:13.641  1043  1374 D WifiNative-p2p0: DRIVER CO,UNTRY CZ: returned true
09-02 15:27:13.642  1043  1374 D LGWifiP2pService: InactiveState{ when=-6ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-02 15:27:13.642  1043  1374 D LGWifiP2pService: P2pEnabledState{ when=-6ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-02 15:27:13.642  1043  1374 D LGWifiP2pService: DefaultState{ when=-6ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-02 15:27:13.642  7259  7259 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
09-02 15:27:13.642  7259  7259 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-02 15:27:13.642  1043  1374 D LGWifiP2pService: InactiveState{ when=-6ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-02 15:27:13.642  1043  7268 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
09-02 15:27:13.642  1043  1374 D LGWifiP2pService: P2pEnabledState{ when=-6ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-02 15:27:13.642  1043  7268 E WifiMonitor: WifiMonitor:wlan0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-02 15:27:13.642  1043  1374 D LGWifiP2pService: DefaultState{ when=-7ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-02 15:27:13.642  1043  7268 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-02 15:27:13.642  1043  7268 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-02 15:27:13.642  1043  1374 D LGWifiP2pService: InactiveState{ when=-7ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-02 15:27:13.643  1928  2260 W WfdsService: DefaultState - msg [9441285] is not handled
09-02 15:27:13.643  1043  1374 D LGWifiP2pService: P2pEnabledState{ when=-7ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-02 15:27:13.643  1043  1374 D LGWifiP2pService: DefaultState{ when=-7ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-02 15:27:13.643  7259  7259 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 15:27:13.643  1928  7292 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-02 15:27:13.643  1043  7268 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-02 15:27:13.643  1043  7268 E WifiMonitor: WifiMonitor:p2p0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 15:27:13.643  1043  7268 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 15:27:13.643  1043  7268 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,09-02 15:27:13.643  1043  1374 D LGWifiP2pService: InactiveState{ when=-8ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-02 15:27:13.643  1043  1377 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
09-02 15:27:13.643  1043  1377 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
09-02 15:27:13.643  1043  1374 D LGWifiP2pService: P2pEnabledState{ when=-8ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-02 15:27:13.643  1043  1374 D LGWifiP2pService: DefaultState{ when=-8ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-02 15:27:13.644  7259  7259 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 15:27:13.644  1043  1043 E WifiServerServiceExt: No p2p device connected
09-02 15:27:13.644  1043  7268 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
,09-02 15:27:13.644  1043  7268 E WifiMonitor: WifiMonitor:p2p0 cnt=30 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 15:27:13.644  1928  7292 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-02 15:27:13.644  1043  7268 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 15:27:13.644  1043  7268 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 15:27:13.644  1043  1377 D WifiNative-wlan0: BSS_FLUSH 0: returned true
09-02 15:27:13.644  1043  1374 D LGWifiP2pService: InactiveState{ when=-5ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-02 15:27:13.644  1043  1377 D WifiNative-wlan0: doBoolean: SCAN
09-02 15:27:13.644  1043  1374 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-02 15:27:13.644  1043  1377 D WifiNative-wlan0: SCAN: returned false
,09-02 15:27:13.645  1043  1377 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=186907  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-02 15:27:13.646  1043  1377 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=186908  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-02 15:27:13.647  1043  1377 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-02 15:27:13.647  1043  1043 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 15:27:13.647  1043  1043 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 15:27:13.647  1043  1043 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-02 15:27:13.647  1043  1377 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
,09-02 15:27:13.647  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 15:27:13.647  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-02 15:27:13.648  1043  1377 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-02 15:27:13.648  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 15:27:13.648  1043  1377 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-02 15:27:13.651  1043  1377 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-02 15:27:13.651  1043  1043 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
,09-02 15:27:13.651  1043  1043 D WifiServerServiceExt: setSupplicantStateSCANNING
,09-02 15:27:13.657  7269  7269 D LgDataFeature: LgDataFeature() Constructor: none
09-02 15:27:13.657  7269  7269 D LgDataFeature: LgDataFeature() Constructor Done, null
09-02 15:27:13.659  7269  7269 D PhoneMonitor: Register our PhoneStateListener
09-02 15:27:13.795  1043  1926 I art     : Explicit concurrent mark sweep GC freed 77460(3MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/64MB, paused 1.831ms total 135.041ms
,09-02 15:27:13.806  7269  7269 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-02 15:27:13.808  7269  7269 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,09-02 15:27:13.828  7269  7269 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
09-02 15:27:13.829  7269  7269 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
09-02 15:27:13.830  7269  7269 D TelephonyAutoProfiling: [parse] Load xml
,09-02 15:27:13.838  7269  7269 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
09-02 15:27:13.838  7269  7269 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
09-02 15:27:13.838  7269  7269 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
09-02 15:27:13.838  7269  7269 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
09-02 15:27:13.838  7269  7269 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
09-02 15:27:13.838  7269  7269 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
09-02 15:27:13.839  7269  7269 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
09-02 15:27:13.839  7269  7269 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
,09-02 15:27:13.839  7269  7269 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
09-02 15:27:13.839  7269  7269 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
09-02 15:27:13.839  7269  7269 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
09-02 15:27:13.839  7269  7269 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
09-02 15:27:13.839  7269  7269 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
09-02 15:27:13.839  7269  7269 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
09-02 15:27:13.839  7269  7269 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
09-02 15:27:13.840  7269  7269 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
09-02 15:27:13.840  7269  7269 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
09-02 15:27:13.844  7269  7269 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,09-02 15:27:13.871  1043  1998 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7296 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-02 15:27:13.872  1043  1998 I ActivityManager: Killing 6740:com.lge.eula/1000 (adj 15): empty #17
09-02 15:27:13.917  1043  1979 W libprocessgroup: failed to open /acct/uid_1000/pid_6740/cgroup.procs: No such file or directory
,09-02 15:27:14.072  1043  1361 D PowerManagerServiceEx: acquireWakeLockInternal: lock=1041877490, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1043
,09-02 15:27:14.077  1043  1361 V AlarmManager: RTC_WAKEUP set : Alarm{3875d49c type 0 when 1472822833815 android} when 1472822833815
09-02 15:27:14.078  1043  1361 V AlarmManager: ELAPSED_WAKEUP set : Alarm{3d9b3ea5 type 2 when 187330 com.google.android.gms} when 187330
09-02 15:27:14.091  1043  7268 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
09-02 15:27:14.091  7259  7259 E wpa_supplicant: USIM:  scard_init function
09-02 15:27:14.091  1043  7268 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
09-02 15:27:14.091  7259  7259 I wpa_supplicant: Trying to associate with SSID 'NG700'
09-02 15:27:14.091  1043  7268 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
09-02 15:27:14.092  1043  7268 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: WPS-AP-AVAILABLE 
09-02 15:27:14.092  1043  7268 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
09-02 15:27:14.092  1043  7268 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
09-02 15:27:14.092  1043  7268 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
09-02 15:27:14.095  1043  1377 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
,09-02 15:27:14.097  1043  1377 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
09-02 15:27:14.098  1043  1377 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
09-02 15:27:14.101  1043  1377 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
09-02 15:27:14.101  1043  1377 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
09-02 15:27:14.154  1043  1873 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7317 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
09-02 15:27:14.155  1043  1873 I ActivityManager: Killing 6715:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,09-02 15:27:14.213  7259  7259 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
09-02 15:27:14.213  1043  7268 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
09-02 15:27:14.213  1043  7268 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
,09-02 15:27:14.216  1043  7268 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
09-02 15:27:14.218  1043  7268 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: Associated with f4:f2:6d:22:99:3e
09-02 15:27:14.218  1043  7268 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-02 15:27:14.218  1043  7268 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-02 15:27:14.225  1043  1377 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=187487  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
09-02 15:27:14.226  1043  2037 W libprocessgroup: failed to open /acct/uid_10097/pid_6715/cgroup.procs: No such file or directory
09-02 15:27:14.226  1043  1377 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=187488  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
09-02 15:27:14.227  1043  1377 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=187489  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-02 15:27:14.228  1043  1377 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=187490  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-02 15:27:14.228  1043  1377 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=187490
09-02 15:27:14.229  1043  1377 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=187491
09-02 15:27:14.229  1043  1377 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=187491
09-02 15:27:14.229  1043  1119 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-02 15:27:14.230  1043  1377 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=187492
09-02 15:27:14.230  1043  1377 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=187492
09-02 15:27:14.231  1043  1377 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=187493  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
,09-02 15:27:14.235  7259  7259 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-02 15:27:14.236  7259  7259 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-02 15:27:14.236  1043  7268 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-02 15:27:14.236  1043  7268 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-02 15:27:14.237  1043  7268 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
09-02 15:27:14.237  1043  7268 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-02 15:27:14.237  1043  7268 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-02 15:27:14.237  1043  7268 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
09-02 15:27:14.237  1043  7268 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-02 15:27:14.237  1043  7268 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-02 15:27:14.239  1043  7268 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-02 15:27:14.239  1043  7268 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-02 15:27:14.240  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 15:27:14.240  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-02 15:27:14.241  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 15:27:14.242  1043  1043 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 15:27:14.242  1043  1043 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 15:27:14.242  1043  1043 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-02 15:27:14.244  1043  1043 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-02 15:27:14.244  1043  1043 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 15:27:14.244  1043  1043 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-02 15:27:14.245  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 15:27:14.245  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-02 15:27:14.246  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 15:27:14.252  2584  2584 D [Concierge]Service: onStartCommand(). Type : 9
09-02 15:27:14.253  1043  1377 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=187515  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
09-02 15:27:14.254  1043  1377 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=187516  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-02 15:27:14.255  1043  1377 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=187517  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-02 15:27:14.256  1043  1377 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=187518
09-02 15:27:14.256  1043  1377 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=187518
,09-02 15:27:14.258  1043  1377 D WifiNative-wlan0: doString: [STATUS]
09-02 15:27:14.258  1043  7268 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-02 15:27:14.258  1043  7268 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-02 15:27:14.264  1043  1043 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 15:27:14.264  1043  1043 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 15:27:14.264  1043  1043 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-02 15:27:14.265  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 15:27:14.266  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-02 15:27:14.266  1043  1377 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-02 15:27:14.268  1043  1377 I WifiServiceExtension: setVHTCapabilityType  : false
09-02 15:27:14.269  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-02 15:27:14.274  1043  1043 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 15:27:14.274  1043  1043 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 15:27:14.274  1043  1043 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
09-02 15:27:14.274  1043  1043 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-02 15:27:14.274  1043  1043 D WifiServerServiceExt: setSupplicantStateASSOCIATED
09-02 15:27:14.278  1043  1377 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
09-02 15:27:14.278  1043  1377 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
,09-02 15:27:14.286  1043  1043 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 15:27:14.286  1043  1043 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 15:27:14.286  1043  1043 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-02 15:27:14.289  1043  1043 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 15:27:14.289  1043  1043 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 15:27:14.289  1043  1043 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-02 15:27:14.293  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 15:27:14.293  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-02 15:27:14.298  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 15:27:14.301  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 15:27:14.301  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-02 15:27:14.303  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 15:27:14.304  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 15:27:14.304  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-02 15:27:14.305  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 15:27:14.306  1043  1377 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
09-02 15:27:14.306  1043  1431 D ConnectivityService: Got NetworkAgent Messenger
09-02 15:27:14.306  1043  1431 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-02 15:27:14.306  1043  1431 D ConnectivityService: NetworkAgent connected
09-02 15:27:14.306  1043  1377 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-02 15:27:14.306  1043  1377 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-02 15:27:14.307  1043  1377 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-02 15:27:14.307  1043  1377 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-02 15:27:14.313  1043  1377 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-02 15:27:14.314  1043  1377 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-02 15:27:14.314  1043  1377 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-02 15:27:14.315  1043  1377 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-02 15:27:14.315  1043  1377 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-02 15:27:14.320  1043  1377 D WifiNative-wlan0: SAVE_CONFIG: returned true
,09-02 15:27:14.322   304   880 D CommandListener: Setting iface cfg
09-02 15:27:14.360  1043  1979 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7341 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-02 15:27:14.361  1043  1979 I ActivityManager: Killing 5548:com.lge.bnr/1000 (adj 15): empty #17
09-02 15:27:14.456  1043  1562 W libprocessgroup: failed to open /acct/uid_1000/pid_5548/cgroup.procs: No such file or directory
,09-02 15:27:14.468  1043  1374 D LGWifiP2pService: InactiveState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-02 15:27:14.468  1043  1374 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-02 15:27:14.468  1043  1374 D LGWifiP2pService: DefaultState{ when=-2ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,09-02 15:27:14.478  1043  7339 D DhcpStateMachine: StoppedState
,09-02 15:27:14.478  1043  1377 E WifiStateMachine: Start Dhcp Watchdog 2
09-02 15:27:14.479  1043  1377 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=187741  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-02 15:27:14.479  1043  1377 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=187741  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-02 15:27:14.480  1043  1377 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=187742  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-02 15:27:14.481  1043  1377 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
09-02 15:27:14.481  1043  1377 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
09-02 15:27:14.482  1043  1377 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
09-02 15:27:14.482  1043  1377 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
09-02 15:27:14.482  1043  1377 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
09-02 15:27:14.483  1043  1377 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-02 15:27:14.484  1043  1377 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=187746  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-02 15:27:14.485  1043  1377 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=187747  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-02 15:27:14.485  1043  7339 D DhcpStateMachine: StoppedState{ when=-8ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
09-02 15:27:14.485  1043  7339 D DhcpStateMachine: WaitBeforeStartState
09-02 15:27:14.486  1043  1377 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=187748  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
,09-02 15:27:14.488  1043  1377 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:141782] from screen [on:0 period:-350948040] gl rssi=-46 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
09-02 15:27:14.489  1043  1377 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-350948039] gl rssi=-46 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
09-02 15:27:14.489  1043  1377 D WifiNative-wlan0: doString: [SIGNAL_POLL]
09-02 15:27:14.498  1043  1431 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
09-02 15:27:14.498  1043  1377 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
,09-02 15:27:14.499  1043  1377 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 15:27:14.500  1043  1377 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 15:27:14.501  1043  1377 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 15:27:14.501  1043  1377 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 15:27:14.501  1043  1377 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 15:27:14.502  1043  1431 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
09-02 15:27:14.503  1043  1377 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=127,0,0
09-02 15:27:14.504  1043  1377 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=127,0,0
09-02 15:27:14.504  1043  1377 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
,09-02 15:27:14.504  7259  7259 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
09-02 15:27:14.504  1043  1377 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
09-02 15:27:14.505  1043  1377 D WifiNative-wlan0: doBoolean: SET ps 0
09-02 15:27:14.505  1043  1377 D WifiNative-wlan0: SET ps 0: returned true
09-02 15:27:14.505  1043  1377 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
09-02 15:27:14.505  7259  7259 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
09-02 15:27:14.506  1043  1377 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
09-02 15:27:14.506  1043  1377 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
09-02 15:27:14.506  1043  1377 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-02 15:27:14.506  1043  1374 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@17ac6ace target=com.android.internal.util.StateMachine$SmHandler }
09-02 15:27:14.506  1043  1377 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-02 15:27:14.506  1043  1374 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@17ac6ace target=com.android.internal.util.StateMachine$SmHandler }
09-02 15:27:14.507  1043  7339 D DhcpStateMachine: WaitBeforeStartState{ when=-1ms what=196615 target=com.android.internal.util.StateMachine$SmHandler }
09-02 15:27:14.507  1043  7339 D DhcpStateMachine: DHCP Start wake lock is acquired.
09-02 15:27:14.509   304   880 D CommandListener: Setting iface cfg
09-02 15:27:14.509   304   880 D CommandListener: Trying to bring up wlan0
09-02 15:27:14.510  1043  1377 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
09-02 15:27:14.511  1043  1377 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 15:27:14.511  1043  1377 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 15:27:14.512  1043  1377 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 15:27:14.512  1043  1377 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 15:27:14.513  1043  1377 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 15:27:14.513  1043  1377 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 15:27:14.514  1043  1431 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
09-02 15:27:14.515  1043  1377 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
09-02 15:27:14.516  1043  1377 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
09-02 15:27:14.516  1043  1377 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-02 15:27:14.516  1043  1374 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-02 15:27:14.516  1043  1374 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-02 15:27:14.516  7259  7259 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-02 15:27:14.517  1043  1377 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-02 15:27:14.517  1043  1377 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
09-02 15:27:14.517  7259  7259 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
09-02 15:27:14.517  1043  1377 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
09-02 15:27:14.517  1043  1377 D WifiNative-wlan0: doBoolean: SET ps 1
,09-02 15:27:14.523  7341  7341 I art     : Almond Protected OAT
09-02 15:27:14.535  1043  1377 D WifiNative-wlan0: SET ps 1: returned true
09-02 15:27:14.536  1043  1377 E WifiStateMachine:  ObtainingIpState CMD_STOP_SUPPLICANT_FAILED 1 0
09-02 15:27:14.536  1043  1043 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-02 15:27:14.536  1043  1043 D WifiServerServiceExt: setSupplicantStateCOMPLETED
,09-02 15:27:14.538  1043  1431 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
09-02 15:27:14.538  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 15:27:14.538  1043  1377 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
09-02 15:27:14.539  1043  1377 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
09-02 15:27:14.539  1043  1377 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
09-02 15:27:14.540  1043  1377 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
09-02 15:27:14.540  1043  1377 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
09-02 15:27:14.540  1043  1377 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-02 15:27:14.541  1043  1377 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-02 15:27:14.541  1043  1377 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
09-02 15:27:14.541  1043  1431 D ConnectivityService: ignoring duplicate network state non-change
09-02 15:27:14.542  1043  1431 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-02 15:27:14.543  1043  1431 D ConnectivityService: Adding iface wlan0 to network 101
09-02 15:27:14.544  1043  1377 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-02 15:27:14.548  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-02 15:27:14.548  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-02 15:27:14.549  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 15:27:14.550  1043  1043 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 15:27:14.550  1043  1043 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 15:27:14.550  1043  1043 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-02 15:27:14.556  1043  1043 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 15:27:14.556  1043  1043 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 15:27:14.556  1043  1043 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,09-02 15:27:14.558  1043  1043 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-02 15:27:14.566  1043  1431 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-02 15:27:14.566  1043  1431 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
09-02 15:27:14.567  1043  1431 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
09-02 15:27:14.568   304   880 E Netd    : netlink response contains error (File exists)
09-02 15:27:14.569  1043  1431 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,09-02 15:27:14.570  1043  1431 D ConnectivityService: addLocalRoutetoDefaultNetwork
09-02 15:27:14.570  1043  1431 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
09-02 15:27:14.571  1043  1431 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
09-02 15:27:14.572  1928  1928 V WfdStateTracker: handleWifiStateChangedEvent: 1
09-02 15:27:14.573  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 15:27:14.573  1043  1043 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 15:27:14.573  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-02 15:27:14.573  1043  1043 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 15:27:14.573  1043  1043 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-02 15:27:14.573  1043  1043 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-02 15:27:14.574  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 15:27:14.576  1043  1043 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 15:27:14.576  1043  1431 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-02 15:27:14.576  1043  1431 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-02 15:27:14.576  1043  1043 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 15:27:14.576  1043  1431 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
09-02 15:27:14.576  1043  1043 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-02 15:27:14.576  1043  1431 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
09-02 15:27:14.576  1043  1431 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-02 15:27:14.576  1043  1431 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-02 15:27:14.576  1043  1431 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-02 15:27:14.576  1043  1431 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 15:27:14.576  1043  1431 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
09-02 15:27:14.576  1043  1431 D ConnectivityService: currentScore = 0, newScore = 20
09-02 15:27:14.576  1043  1431 D ConnectivityService:    accepting network in place of null
09-02 15:27:14.576  1043  1431 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 15:27:14.576  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 15:27:14.577  1043  7334 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
09-02 15:27:14.577  1043  7334 D NetworkMonitor, NetworkAgentInfo [WIFI () - null]: Connected
09-02 15:27:14.577  1043  7334 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-02 15:27:14.577  1589  1589 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-02 15:27:14.577  1043  7334 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
09-02 15:27:14.577  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 15:27:14.577  1043  1377 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 15:27:14.577  1043  1377 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-02 15:27:14.578  1043  1431 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
09-02 15:27:14.578  1043  1431 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-02 15:27:14.578  1043  1431 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-02 15:27:14.579  1836  1836 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 15:27:14.579  1836  1836 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-02 15:27:14.579   304  7362 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
09-02 15:27:14.583  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 15:27:14.583  1043  1431 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-02 15:27:14.583  1589  1589 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-02 15:27:14.584  1043  1431 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
09-02 15:27:14.584  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 15:27:14.584  1043  1431 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} ,}
09-02 15:27:14.586  1043  1043 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
09-02 15:27:14.586  1043  1043 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-02 15:27:14.586  1043  1043 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-02 15:27:14.586  1043  1043 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-02 15:27:14.586  1043  1431 D ConnectivityService: validation of new default Network = false
09-02 15:27:14.586  1043  1431 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
09-02 15:27:14.586  1043  1431 D DSQN    : enableDataServiceNotify 
09-02 15:27:14.586  1043  1431 D DSQN    : start dsqn bin
09-02 15:27:14.590  1043  1373 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
09-02 15:27:14.594  1043  1431 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
09-02 15:27:14.594  1043  1431 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 15:27:14.594  1043  1431 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-02 15:27:14.594  1043  1431 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-02 15:27:14.585  7363  7363 W dsqn    : type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-02 15:27:14.585  7363  7363 W dsqn    : type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-02 15:27:14.595  1589  2084 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-02 15:27:14.610  7363  7363 E DSQN    : DSQN ssw
09-02 15:27:14.610  7341  7341 D WeatherApplication: removeAccount
09-02 15:27:14.613  7341  7341 D WeatherApplication: Account.length = 0
09-02 15:27:14.613  7341  7341 E WeatherApplication: OPERATOR:OPEN
09-02 15:27:14.616  1589  1589 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-02 15:27:14.616  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 15:27:14.617  1801  7365 I CheckinService: active receiver: enabled
09-02 15:27:14.617  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 15:27:14.618  7341  7341 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:27:14
,09-02 15:27:14.627  1801  7365 I CheckinService: Preparing to send checkin request
09-02 15:27:14.627  1801  7365 I EventLogService: Accumulating logs since 1472822689234
09-02 15:27:14.628  7341  7341 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-02 15:27:14.628  7341  7341 D Weather.Utils: 2 : All the weather widget is gone.
09-02 15:27:14.629  7341  7341 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-02 15:27:14.630  7341  7341 D WeatherAncestor: connectivity changed - connection : true
09-02 15:27:14.631  7341  7341 D WeatherService: 2 : isServiceAlived():false forecastCache:null
09-02 15:27:14.636  7341  7341 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-02 15:27:14.636  7341  7341 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-02 15:27:14.636  7341  7341 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
09-02 15:27:14.646   304  7362 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,09-02 15:27:14.654  7341  7341 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-02 15:27:14.654  7341  7341 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:27:14
09-02 15:27:14.682   304  7362 D libc-netbsd: res_queryN name = clients3.google.com succeed
,09-02 15:27:14.695  1043  1562 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7370 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-02 15:27:14.696  1043  1562 I ActivityManager: Killing 2132:com.lge.music/u0a34 (adj 15): empty #17
,09-02 15:27:14.709  1043  7339 D DhcpStateMachine: DHCPV4 request on wlan0
09-02 15:27:14.709  1043  7339 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
09-02 15:27:14.709  1043  7339 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
09-02 15:27:14.705  7387  7387 W dhcpcd  : type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-02 15:27:14.705  7387  7387 W dhcpcd  : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-02 15:27:14.716   308  1384 V AudioFlinger: 2132 died, releasing its sessions
09-02 15:27:14.716   308  1384 V AudioFlinger:  pid 1836 @ 0
09-02 15:27:14.716   308  1384 V AudioFlinger:  pid 3395 @ 1
09-02 15:27:14.716   308  1384 V AudioFlinger:  pid 3395 @ 2
09-02 15:27:14.718   304   879 D LGDataListener: argv[0]=dsqncommand
09-02 15:27:14.718   304   879 D LGDataListener: argv[1]=wlan0
09-02 15:27:14.718   304   879 D LGDataListener: argv[2]=1
09-02 15:27:14.718   304   879 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
09-02 15:27:14.718  1043  1117 D DSQN    : DSQM DsqnNotification wlan0  1
09-02 15:27:14.718  1043  1117 D DSQN    : start to monitor internet connection
09-02 15:27:14.723  7387  7387 I dhcpcd  : version 5.5.6 starting
09-02 15:27:14.725  7387  7387 E dhcpcd  : get_duid: m
09-02 15:27:14.725  7387  7387 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
09-02 15:27:14.725  7387  7387 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,09-02 15:27:14.752  1801  7365 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
09-02 15:27:14.752  1043  1865 W libprocessgroup: failed to open /acct/uid_10034/pid_2132/cgroup.procs: No such file or directory
09-02 15:27:14.754  1043  7334 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 02 Sep 2016 13:27:14 GMT], X-Android-Received-Millis=[1472822834754], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472822834717]}
09-02 15:27:14.754  1043  7334 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
09-02 15:27:14.754  1043  7334 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
09-02 15:27:14.755  1043  1431 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
09-02 15:27:14.755  1043  1431 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
09-02 15:27:14.755  1043  1431 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-02 15:27:14.755  1043  1431 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
,09-02 15:27:14.755  1043  1431 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-02 15:27:14.755  1043  1431 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
09-02 15:27:14.755  1043  1431 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
09-02 15:27:14.755  1043  1431 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 15:27:14.755  1043  1431 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-02 15:27:14.756  1043  1431 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-02 15:27:14.757  1589  2084 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-02 15:27:14.757  1043  1431 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 15:27:14.758  1043  1431 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-02 15:27:14.758  1043  1377 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 15:27:14.758  1043  1377 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-02 15:27:14.759  1836  1836 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 15:27:14.759  1836  1836 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
,09-02 15:27:14.783  1589  1589 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-02 15:27:14.785  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 15:27:14.787  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 15:27:14.796  7387  7387 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
,09-02 15:27:14.796  7387  7387 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-02 15:27:14.796  7387  7387 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-02 15:27:14.796  7387  7387 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
09-02 15:27:14.796  7387  7387 D dhcpcd  : wlan0: sending REQUEST (xid 0x79f44bb3), next in 4.49 seconds
,09-02 15:27:14.826  7387  7387 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
,09-02 15:27:14.846  7387  7387 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
09-02 15:27:14.847  7387  7387 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
,09-02 15:27:14.847  7387  7387 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
09-02 15:27:14.847  7387  7387 D dhcpcd  : wlan0: adding default route via 192.168.1.1
09-02 15:27:14.847  7387  7387 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,09-02 15:27:14.847  7387  7387 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-02 15:27:14.847  7387  7387 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-02 15:27:14.847  7387  7387 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
09-02 15:27:14.876   278   438 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-02 15:27:14.877   278   438 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
09-02 15:27:14.877   278   438 W Vold    : Returning OperationFailed - no handler for errno 0
09-02 15:27:14.883  7370  7399 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,09-02 15:27:14.889   278   438 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-02 15:27:14.889   278   438 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
09-02 15:27:14.889   278   438 W Vold    : Returning OperationFailed - no handler for errno 0
09-02 15:27:14.890  7370  7399 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
09-02 15:27:14.904   278   438 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-02 15:27:14.904   278   438 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
09-02 15:27:14.904   278   438 W Vold    : Returning OperationFailed - no handler for errno 0
09-02 15:27:14.904  7370  7404 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,09-02 15:27:14.909   278   438 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-02 15:27:14.909   278   438 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
09-02 15:27:14.909   278   438 W Vold    : Returning OperationFailed - no handler for errno 0
09-02 15:27:14.914  7370  7404 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
09-02 15:27:14.915  1043  1865 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7406 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,09-02 15:27:14.991  7406  7406 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
09-02 15:27:14.991  7406  7406 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,09-02 15:27:15.021  7406  7406 I MultiDex: VM with version 2.1.0 has multidex support
09-02 15:27:15.021  7406  7406 I MultiDex: install
09-02 15:27:15.021  7406  7406 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,09-02 15:27:15.030  7406  7406 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
09-02 15:27:15.096  7370  7370 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,09-02 15:27:15.106  7370  7370 I LibraryLoader: Loading: webviewchromium
,09-02 15:27:15.110  7370  7370 I LibraryLoader: Time to load native libraries: 5 ms (timestamps 8378-8383)
09-02 15:27:15.110  7370  7370 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-02 15:27:15.113  1043  7339 D DhcpStateMachine: DHCPV4 succeeded on wlan0
09-02 15:27:15.114  1043  7339 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
09-02 15:27:15.114  1043  7339 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-02 15:27:15.115  1043  7339 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
09-02 15:27:15.115  1043  7339 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
09-02 15:27:15.115  1043  7339 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-02 15:27:15.115  1043  7339 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
09-02 15:27:15.115  1043  7339 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
09-02 15:27:15.115  1043  7339 D DhcpStateMachine: RunningState
09-02 15:27:15.117  7370  7370 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {24193121}
09-02 15:27:15.120  7370  7370 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-02 15:27:15.122  7370  7370 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,09-02 15:27:15.144  7370  7370 I BrowserStartupController: Initializing chromium process, renderers=0
,09-02 15:27:15.145  7370  7370 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-02 15:27:15.157  7370  7370 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,09-02 15:27:15.158  7370  7370 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
09-02 15:27:15.159  7370  7370 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
09-02 15:27:15.164   308  2156 V AudioPolicyService: registerClient() client 0xb1020d20, uid 10093
09-02 15:27:15.165  7370  7459 W AudioManagerAndroid: Requires BLUETOOTH permission
09-02 15:27:15.175  7370  7370 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-02 15:27:15.175  7370  7370 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-02 15:27:15.175  7370  7370 I Adreno-EGL: Build Date: 12/12/14 금
09-02 15:27:15.175  7370  7370 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-02 15:27:15.175  7370  7370 I Adreno-EGL: Remote Branch: 
09-02 15:27:15.175  7370  7370 I Adreno-EGL: Local Patches: 
09-02 15:27:15.175  7370  7370 I Adreno-EGL: Reconstruct Branch: 
,09-02 15:27:15.258  7370  7370 I NSApplication: Starting up...
,09-02 15:27:15.287  7406  7426 D LgDataFeature: LgDataFeature() Constructor: none
09-02 15:27:15.287  7406  7426 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-02 15:27:15.355  1043  1562 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7475 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
09-02 15:27:15.357  1043  1722 I ActivityManager: Killing 6613:com.android.vending/u0a44 (adj 15): empty #17
,09-02 15:27:15.398  1043  2014 W libprocessgroup: failed to open /acct/uid_10044/pid_6613/cgroup.procs: No such file or directory
,09-02 15:27:15.427  7475  7475 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-02 15:27:15.479  1043  1377 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-02 15:27:15.480  1043  1377 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-02 15:27:15.481  1043  1377 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-02 15:27:15.483  1043  1377 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-02 15:27:15.484  1043  1377 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-02 15:27:15.485  1043  1377 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-02 15:27:15.490  1043  1431 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
09-02 15:27:15.490  1043  1431 D ConnectivityService: identical MTU - not setting
09-02 15:27:15.490  1043  1431 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-02 15:27:15.490  1043  1431 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-02 15:27:15.491  1043  1431 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 15:27:15.491  1043  1431 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-02 15:27:15.492  1043  1431 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
09-02 15:27:15.493  1589  2084 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,09-02 15:27:15.502  1043  1962 D WifiServiceImplEx: setWifiEnabled: false pid=6878, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-02 15:27:15.502  1043  1962 D WifiService: setWifiEnabled: false pid=6878, uid=10118
09-02 15:27:15.502  1043  1962 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-02 15:27:15.520  1043  1043 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-02 15:27:15.520  1043  1043 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-02 15:27:15.520  1043  1043 D Ulp_jni : JNI:system_update. Event-4
09-02 15:27:15.520  1043  1377 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
09-02 15:27:15.521  1043  1377 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
09-02 15:27:15.521  1043  1377 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
09-02 15:27:15.521  1043  1377 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
09-02 15:27:15.522  1043  1377 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
09-02 15:27:15.522  1043  1377 E WifiStateMachine: WifiStateMachine: Leaving Connected state
09-02 15:27:15.522  1043  1377 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-02 15:27:15.522  1043  1377 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-02 15:27:15.522  1043  1377 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-02 15:27:15.522  1043  1377 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-02 15:27:15.529  1043  1377 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-02 15:27:15.529  1043  1377 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-02 15:27:15.529  1043  1374 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-02 15:27:15.529  1043  1374 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-02 15:27:15.529  7259  7259 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-02 15:27:15.530  1043  1377 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-02 15:27:15.530  1043  1377 D WifiNative-wlan0: doBoolean: SET ps 1
09-02 15:27:15.530  1043  1377 D WifiNative-wlan0: SET ps 1: returned true
09-02 15:27:15.531   304   880 D CommandListener: Clearing all IP addresses on wlan0
09-02 15:27:15.531  1043  7339 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-02 15:27:15.554  1043  1431 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-02 15:27:15.554  1043  1431 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
,09-02 15:27:15.555  1043  1374 D LGWifiP2pService: InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-02 15:27:15.555  1043  1374 D LGWifiP2pService: P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-02 15:27:15.555  1043  1374 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@3ad5a88c
09-02 15:27:15.555  1043  1377 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 15:27:15.555  1043  1374 D LGWifiP2pService: P2pDisablingState
09-02 15:27:15.555  1043  1377 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 15:27:15.555  1043  1374 D LGWifiP2pService: P2pDisablingState{ when=-1ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
,09-02 15:27:15.555  1043  1374 D LGWifiP2pService: p2p socket connection lost
09-02 15:27:15.555  1043  1374 D LGWifiP2pService: P2pDisabledState
09-02 15:27:15.556  1043  1377 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 15:27:15.556  1043  1377 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 15:27:15.556  1043  1377 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 15:27:15.560  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 15:27:15.560  1043  1043 D WifiHS20: hidePasspointNotification off =false
09-02 15:27:15.560  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-02 15:27:15.560  1043  1043 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 15:27:15.560  1043  1043 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 15:27:15.560  1043  1043 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-02 15:27:15.560  1043  1043 D WifiHS20: hidePasspointNotification off =false
09-02 15:27:15.560  1043  1043 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 15:27:15.560  1043  1043 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 15:27:15.560  1043  1043 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-02 15:27:15.560  1043  1043 D WifiScanningService: SCAN_AVAILABLE : 1
09-02 15:27:15.560  1043  1043 D RttService: SCAN_AVAILABLE : 1
09-02 15:27:15.561  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 15:27:15.563  1043  1542 D WifiScanningService: DefaultState got{ when=-2ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
09-02 15:27:15.564  1928  1928 V WfdStateTracker: handleWifiStateChangedEvent: 0
09-02 15:27:15.564  1928  1928 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-02 15:27:15.564  1928  1928 D WfdsService: WifiP2pState is changed : false
09-02 15:27:15.564  1928  2260 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
09-02 15:27:15.564  1928  2260 D WfdsService: Set the WFDS Monitor: false
09-02 15:27:15.564  1043  1544 D RttService: EnabledState got{ when=-4ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-02 15:27:15.565  1928  2260 D WfdsMonitor: WFDS Monitor is stopped
09-02 15:27:15.565  1928  2260 D WfdsService: STATE : WfdsDisabledState - enter
09-02 15:27:15.565  1928  7292 D CtrlSupplicant: Received on exit socket, terminate
09-02 15:27:15.565  1928  7292 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
09-02 15:27:15.565  1928  7292 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
,09-02 15:27:15.565  1928  7292 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
09-02 15:27:15.565  1928  2264 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
09-02 15:27:15.565  1928  2260 W WfdsService: DefaultState - msg [9445378] is not handled
09-02 15:27:15.565  1043  1377 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 15:27:15.566  1043  1377 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-02 15:27:15.566  1043  1377 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
09-02 15:27:15.566  1043  1377 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-02 15:27:15.566  7259  7259 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-02 15:27:15.566  1043  1374 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-02 15:27:15.566  1043  1374 D LGWifiP2pService: DefaultState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-02 15:27:15.567  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 15:27:15.567  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-02 15:27:15.567  1043  1377 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-02 15:27:15.567  1043  1377 D WifiNative-wlan0: doBoolean: SET ps 1
09-02 15:27:15.568  1043  1377 D WifiNative-wlan0: SET ps 1: returned true
09-02 15:27:15.568  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 15:27:15.617   304   880 D CommandListener: Clearing all IP addresses on wlan0
09-02 15:27:15.618  1043  1431 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
09-02 15:27:15.618  1043  1431 D DSQN    : disableDataServiceNotify
09-02 15:27:15.618  1043  1431 D DSQN    : stop dsqn bin
09-02 15:27:15.619  1043  1377 D WifiNative-p2p0: doBoolean: TERMINATE
09-02 15:27:15.620  1043  1043 D WifiHS20: hidePasspointNotification off =false
09-02 15:27:15.620  1043  1043 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 15:27:15.620  1043  1043 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 15:27:15.620  1043  1043 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-02 15:27:15.621  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-02 15:27:15.621  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-02 15:27:15.622  1043  1377 D WifiNative-p2p0: TERMINATE: returned true
09-02 15:27:15.622  1043  1377 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-02 15:27:15.622  1043  1377 E WifiStateMachine: useWiFiOffloading() : false
09-02 15:27:15.622  1043  1377 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,09-02 15:27:15.625  1043  1043 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
09-02 15:27:15.625  1043  1043 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-02 15:27:15.625  1043  1043 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
09-02 15:27:15.625  6878  6878 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 15:27:15.625  6878  6878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 15:27:15.625  6878  6878 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 15:27:15.625  6878  6878 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 15:27:15.625  6878  6878 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 15:27:15.625  6878  6878 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 15:27:15.625  6878  6878 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 15:27:15.625  6878  6878 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 15:27:15.625  6878  6878 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-02 15:27:15.625  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 15:27:15.625  6878  6878 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 15:27:15.625  6878  6878 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-02 15:27:15.626  1928  1928 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
09-02 15:27:15.626  6878  6878 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 15:27:15.626  6878  6878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 15:27:15.626  6878  6878 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 15:27:15.626  6878  6878 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 15:27:15.626  6878  6878 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 15:27:15.626  6878  6878 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 15:27:15.626  6878  6878 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 15:27:15.626  6878  6878 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 15:27:15.626  6878  6878 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-02 15:27:15.626  6878  6878 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 15:27:15.626  6878  6878 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-02 15:27:15.627  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 15:27:15.627  1043  1431 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
09-02 15:27:15.627  1043  1431 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 15:27:15.627  1043  1431 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-02 15:27:15.627  1043  1431 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
09-02 15:27:15.628  1043  1431 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
09-02 15:27:15.628  1043  7334 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-02 15:27:15.628  1043  7334 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-02 15:27:15.628  1043  7334 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
09-02 15:27:15.628  1043  1431 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN Li,nkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
09-02 15:27:15.628  1043  1431 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-02 15:27:15.628  1043  1431 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-02 15:27:15.628  1043  1431 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-02 15:27:15.628  1589  2084 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
09-02 15:27:15.628  1043  1431 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-02 15:27:15.629  1043  1431 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-02 15:27:15.629  1043  1431 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 15:27:15.629  1043  1431 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 15:27:15.629  1043  1431 D NetworkManagementService: Removing idletimer
09-02 15:27:15.629  1043  1431 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 15:27:15.629  1043  1431 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
09-02 15:27:15.630  1836  1836 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 15:27:15.630  1836  1836 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-02 15:27:15.630  1043  1373 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-02 15:27:15.630  1043  1377 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 15:27:15.631  1043  1377 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-02 15:27:15.632  1043  1373 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-02 15:27:15.632  1043  1043 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-02 15:27:15.634  1043  1043 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-02 15:27:15.634  1043  1043 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-02 15:27:15.634  1043  1043 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-02 15:27:15.634  1043  1043 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-02 15:27:15.635  1043  1043 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-02 15:27:15.635  1043  1043 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-02 15:27:15.635  1043  1043 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-02 15:27:15.637  1043  1431 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-02 15:27:15.660  1589  1589 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-02 15:27:15.661  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 15:27:15.662  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 15:27:15.670  7506  7506 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=32 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
09-02 15:27:15.676  6433  6433 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,09-02 15:27:15.677  6433  7034 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,09-02 15:27:15.688  1589  1589 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-02 15:27:15.689  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 15:27:15.689  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 15:27:15.693  2160  2160 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
09-02 15:27:15.709  7197  7197 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-02 15:27:15.709  7197  7197 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-02 15:27:15.710  7197  7197 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-02 15:27:15.710  7197  7197 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-02 15:27:15.711  7197  7197 I AppUp4:CustModeStarterReceiver: onReceive
,09-02 15:27:15.714  7197  7197 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2f87e5be
09-02 15:27:15.714  7197  7197 D AppUp4:CustFacade: isCustomizationCompleted : false
09-02 15:27:15.714  7197  7197 D AppUp4:CustFacade: isPhone : true
09-02 15:27:15.714  7197  7197 D AppUp4:CustModeStarterReceiver: begin check event
09-02 15:27:15.714  7197  7197 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-02 15:27:15.717  7259  7259 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
09-02 15:27:15.718  7259  7259 I wpa_supplicant: monitor socket send errors count : 1
09-02 15:27:15.718  7259  7259 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1928-4\x00 that cannot receive messages
09-02 15:27:15.718  1043  7268 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
09-02 15:27:15.719  1043  7268 D WifiMonitor: Dropping event because (p2p0) is stopped
09-02 15:27:15.720  4743  4743 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-02 15:27:15.720  4743  4743 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-02 15:27:15.721  4743  4743 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-02 15:27:15.723  4743  4743 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-02 15:27:15.727  4743  7516 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,09-02 15:27:15.728  4743  7517 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-02 15:27:15.728  4743  7517 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-02 15:27:15.730  7229  7229 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
09-02 15:27:15.733  7506  7506 I dex2oat : dex2oat took 63.141ms (threads: 4)
09-02 15:27:15.740  7259  7259 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-02 15:27:15.741  1043  7268 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
09-02 15:27:15.741  1043  7268 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-02 15:27:15.741  1043  7268 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-02 15:27:15.741  1043  7268 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
09-02 15:27:15.741  7259  7259 W wpa_supplicant: USIM:  scard_deinit function
,09-02 15:27:15.741  1043  1377 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=189003
09-02 15:27:15.742  1043  1377 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=189004
09-02 15:27:15.742  1043  7268 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-02 15:27:15.742  1043  7268 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,09-02 15:27:15.743  1043  1377 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=189004  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-02 15:27:15.743  1043  7339 D DhcpStateMachine: StoppedState
09-02 15:27:15.743  1043  1377 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=189005  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-02 15:27:15.743  1043  7339 D DhcpStateMachine: StoppedState{ when=-175ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-02 15:27:15.744  1043  1119 D Tethering: InitialState.processMessage what=4
09-02 15:27:15.746  3395  3395 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-02 15:27:15.746  3395  3395 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-02 15:27:15.746  3395  3395 I LgeMiscReceiver: networkInfo.isConnected() = false
09-02 15:27:15.746  1043  1119 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-02 15:27:15.746  1043  1377 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
09-02 15:27:15.747  1043  1377 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
09-02 15:27:15.747  1043  1377 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
09-02 15:27:15.747  1043  1377 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-02 15:27:15.749  7229  7519 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 15:27:15.749  7269  7269 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-02 15:27:15.749  7269  7269 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-02 15:27:15.750  7406  7426 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-02 15:27:15.750  7406  7426 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-02 15:27:15.750  7406  7426 I Adreno-EGL: Build Date: 12/12/14 금
09-02 15:27:15.750  7406  7426 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-02 15:27:15.750  7406  7426 I Adreno-EGL: Remote Branch: 
09-02 15:27:15.750  7406  7426 I Adreno-EGL: Local Patches: 
09-02 15:27:15.750  7406  7426 I Adreno-EGL: Reconstruct Branch: 
09-02 15:27:15.762  7341  7341 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:27:15
,09-02 15:27:15.765  7341  7341 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-02 15:27:15.765  7341  7341 D Weather.Utils: 2 : All the weather widget is gone.
09-02 15:27:15.765  7341  7341 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-02 15:27:15.765  7341  7341 D WeatherAncestor: connectivity changed - connection : true
09-02 15:27:15.765  7341  7341 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@31099d6c
09-02 15:27:15.766  7341  7341 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-02 15:27:15.766  7341  7341 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-02 15:27:15.766  7341  7341 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-02 15:27:15.766  7341  7341 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-02 15:27:15.766  7341  7341 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:27:15
09-02 15:27:15.782  7105  7524 W FormManager: Network not available. Please check & try again.
,09-02 15:27:15.789  7105  7525 V FormManager: Network unavailable.
,09-02 15:27:15.792  7015  7015 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-02 15:27:15.792  7015  7015 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-02 15:27:15.792  7015  7015 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-02 15:27:15.793  7015  7015 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-02 15:27:15.793  7015  7015 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-02 15:27:15.793  7105  7525 V FormManager: Network unavailable.
09-02 15:27:15.798  7015  7015 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-02 15:27:15.798  7015  7015 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-02 15:27:15.798  7015  7015 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
,09-02 15:27:15.798  7015  7015 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-02 15:27:15.798  7015  7015 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-02 15:27:15.798  7015  7015 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,09-02 15:27:15.804  7035  7035 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-02 15:27:15.807  7015  7015 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-02 15:27:15.812  7015  7015 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 15:27:15.816  7105  7531 W FormManager: Network not available. Please check & try again.
09-02 15:27:15.823  7035  7035 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-02 15:27:15.824  7105  7532 V FormManager: Network unavailable.
09-02 15:27:15.825  7406  7426 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-02 15:27:15.825  7406  7426 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-02 15:27:15.825  7406  7426 I Adreno-EGL: Build Date: 12/12/14 금
09-02 15:27:15.825  7406  7426 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-02 15:27:15.825  7406  7426 I Adreno-EGL: Remote Branch: 
09-02 15:27:15.825  7406  7426 I Adreno-EGL: Local Patches: 
09-02 15:27:15.825  7406  7426 I Adreno-EGL: Reconstruct Branch: 
,09-02 15:27:15.826  7015  7015 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-02 15:27:15.828  7105  7532 V FormManager: Network unavailable.
09-02 15:27:15.832  7015  7015 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 15:27:15.838  7105  7533 W FormManager: Network not available. Please check & try again.
,09-02 15:27:15.846  7105  7534 V FormManager: Network unavailable.
,09-02 15:27:15.846  4743  4743 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-02 15:27:15.846  4743  4743 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-02 15:27:15.847  4743  4743 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-02 15:27:15.849  7105  7534 V FormManager: Network unavailable.
09-02 15:27:15.850  4743  4743 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-02 15:27:15.854  4743  7535 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-02 15:27:15.856  4743  7536 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-02 15:27:15.857  4743  7536 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-02 15:27:15.877  7259  7259 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
09-02 15:27:15.877  1043  7268 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
09-02 15:27:15.877  1043  7268 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-TERMINATING 
09-02 15:27:15.877  1043  7268 D WifiMonitor: Disconnecting from the supplicant, no more events
09-02 15:27:15.877  1043  1377 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 44 0
,09-02 15:27:15.895  1043  1722 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7537 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,09-02 15:27:15.978  1043  1377 D WifiOffDelayIfNotUsed: stopMonitoring
09-02 15:27:15.978  1043  1377 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-02 15:27:15.978  1043  1377 E WifiStateMachine: useWiFiOffloading() : false
09-02 15:27:15.978  1043  1377 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,09-02 15:27:15.979  1928  1928 D WfdsService: Supplicant Connection state is changed : false
,09-02 15:27:15.979  1928  2260 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
09-02 15:27:15.979  1928  2260 D WfdsService: Set the WFDS Monitor: false
09-02 15:27:15.979  1928  2260 D WfdsMonitor: WFDS Monitor is stopped
09-02 15:27:15.980  1928  1928 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-02 15:27:15.980  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 15:27:15.981  1043  1043 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
09-02 15:27:15.981  1043  1395 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
09-02 15:27:15.981  1043  1395 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
09-02 15:27:15.981  2469  2469 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 15:27:15.982  6878  6878 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 15:27:15.982  6878  6878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 15:27:15.982  6878  6878 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 15:27:15.982  6878  6878 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 15:27:15.982  6878  6878 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 15:27:15.982  6878  6878 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 15:27:15.982  6878  6878 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 15:27:15.982  6878  6878 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 15:27:15.982  6878  6878 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-02 15:27:15.982  6878  6878 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 15:27:15.982  6878  6878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 15:27:15.982  6878  6878 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 15:27:15.982  6878  6878 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 15:27:15.982  6878  6878 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 15:27:15.982  6878  6878 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 15:27:15.982  6878  6878 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 15:27:15.982  6878  6878 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 15:27:15.982  6878  6878 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-02 15:27:16.011  7537  7537 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-02 15:27:16.011  7537  7537 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,09-02 15:27:16.016  7537  7537 V [BNRBootReceiver]: Boot Receiver Return
09-02 15:27:16.017  7537  7537 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
09-02 15:27:16.020  6433  6433 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-02 15:27:16.025  7015  7015 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-02 15:27:16.032  7015  7015 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 15:27:16.040  7063  7063 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-02 15:27:16.040  7063  7063 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-02 15:27:16.041  7063  7063 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-02 15:27:16.043  1043  1891 I ActivityManager: Killing 6995:com.lge.lifetracker/u0a37 (adj 15): empty #17
,09-02 15:27:16.080  7406  7426 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-02 15:27:16.080  7406  7426 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-02 15:27:16.080  7406  7426 I Adreno-EGL: Build Date: 12/12/14 금
09-02 15:27:16.080  7406  7426 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-02 15:27:16.080  7406  7426 I Adreno-EGL: Remote Branch: 
09-02 15:27:16.080  7406  7426 I Adreno-EGL: Local Patches: 
09-02 15:27:16.080  7406  7426 I Adreno-EGL: Reconstruct Branch: 
,09-02 15:27:16.110  1043  1873 W libprocessgroup: failed to open /acct/uid_10037/pid_6995/cgroup.procs: No such file or directory
09-02 15:27:16.116  1043  1043 D PowerManagerServiceEx: releaseWakeLockInternal: lock=1041877490 [*alarm*], flags=0x0
,09-02 15:27:16.118  7015  7015 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
09-02 15:27:16.120   304  7556 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
09-02 15:27:16.120  1043  1117 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
09-02 15:27:16.127  7015  7015 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
,09-02 15:27:16.130  6433  6433 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-02 15:27:16.137  7015  7015 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-02 15:27:16.141  7015  7015 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 15:27:16.147  7063  7063 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-02 15:27:16.147  7063  7063 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-02 15:27:16.148  7063  7063 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-02 15:27:16.151  6433  6433 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-02 15:27:16.159  7015  7015 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-02 15:27:16.170  7015  7015 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 15:27:16.177  7063  7063 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-02 15:27:16.178  7063  7063 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-02 15:27:16.179  7063  7063 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-02 15:27:16.182  6433  6433 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-02 15:27:16.184  1043  1377 E WifiStateMachine:  InitialState CMD_START_SCAN -2 -2 ic=1 proc(ms):140 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 fiv=20000 [on:0 tx:0 rx:0 period:1687] from screen [on:0 period:-350946344]
09-02 15:27:16.186   304  7558 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
09-02 15:27:16.186  1043  1117 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
09-02 15:27:16.187  1801  7365 E CheckinTask: Checkin failed: https://android.clients.google.com/checkin (request #0): java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
09-02 15:27:16.188  1043  1377 E WifiStateMachine:  DefaultState CMD_START_SCAN -2 -2 ic=1 proc(ms):145 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 fiv=20000 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-350946341]
09-02 15:27:16.188  7015  7015 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-02 15:27:16.198  7015  7015 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 15:27:16.200  1801  7365 I CheckinService: active receiver: disabled
,09-02 15:27:16.213  7063  7063 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-02 15:27:16.213  7063  7063 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-02 15:27:16.213  7063  7063 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-02 15:27:16.215  6433  6433 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-02 15:27:16.221  7015  7015 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-02 15:27:16.227  7015  7015 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 15:27:16.233  7063  7063 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-02 15:27:16.233  7063  7063 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-02 15:27:16.233  7063  7063 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-02 15:27:16.238  6433  6433 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-02 15:27:16.243  7015  7015 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-02 15:27:16.247  7015  7015 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 15:27:16.253  7063  7063 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-02 15:27:16.253  7063  7063 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-02 15:27:16.253  7063  7063 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-02 15:27:16.256  6433  6433 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-02 15:27:16.261  7015  7015 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-02 15:27:16.265  7015  7015 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 15:27:16.270  7063  7063 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-02 15:27:16.270  7063  7063 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-02 15:27:16.271  7063  7063 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-02 15:27:16.281  6433  6433 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-02 15:27:16.295  7015  7015 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-02 15:27:16.303  7015  7015 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-02 15:27:16.310  7063  7063 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-02 15:27:16.311  7063  7063 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-02 15:27:16.315  7063  7063 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-02 15:27:16.322  6433  6433 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-02 15:27:16.337  7015  7015 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-02 15:27:16.347  7015  7015 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 15:27:16.360  7063  7063 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-02 15:27:16.360  7063  7063 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-02 15:27:16.362  7063  7063 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-02 15:27:16.371  6433  6433 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-02 15:27:16.380  7035  7035 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,09-02 15:27:16.395  1043  1429 D WifiService: New client listening to asynchronous messages
09-02 15:27:16.395  7035  7035 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-02 15:27:16.403  7015  7015 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-02 15:27:16.418  7015  7015 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-02 15:27:16.433  7063  7063 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-02 15:27:16.433  7063  7063 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-02 15:27:16.435  7063  7063 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
09-02 15:27:16.436  7063  7063 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-02 15:27:16.437  7063  7063 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
09-02 15:27:16.446  6433  6433 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-02 15:27:16.455  7035  7035 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,09-02 15:27:16.460  7035  7035 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-02 15:27:16.471  7015  7015 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-02 15:27:16.478  6777  7171 D UEI.SmartControl: Internal timer expired: 4
09-02 15:27:16.478  6777  7171 D UEI.SmartControl: unbind internal service
09-02 15:27:16.488  7015  7015 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-02 15:27:16.505  7063  7063 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-02 15:27:16.507  7063  7063 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-02 15:27:16.508  7063  7063 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
09-02 15:27:16.509  7063  7063 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-02 15:27:16.510  7063  7063 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
09-02 15:27:16.520  2160  2160 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
09-02 15:27:16.537  2160  2160 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
09-02 15:27:16.538  2160  2160 D c       : Getting all permits...
09-02 15:27:16.538  2160  2160 D a       : Opening database...
,09-02 15:27:16.547  2160  2160 D a       : Opening database auth.proximity.permit_store...
,09-02 15:27:16.548  2160  2160 D a       : Closing database...
09-02 15:27:16.560  6433  6433 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-02 15:27:16.567  7035  7035 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-02 15:27:16.567  7035  7035 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-02 15:27:16.567  7035  7035 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-02 15:27:16.569  6777  7168 D serial_port: close(fd = 24)
09-02 15:27:16.570  7015  7015 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-02 15:27:16.573  6777  7168 I UEI.SmartControl: Serial port is closed.
,09-02 15:27:16.580  7015  7015 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 15:27:16.588  7063  7063 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-02 15:27:16.588  7063  7063 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-02 15:27:16.590  7063  7063 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-02 15:27:16.595  6433  6433 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-02 15:27:16.600  7035  7035 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-02 15:27:16.600  7035  7035 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-02 15:27:16.600  7035  7035 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-02 15:27:16.605  7015  7015 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-02 15:27:16.613  7015  7015 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 15:27:16.621  7063  7063 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE,
09-02 15:27:16.622  7063  7063 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-02 15:27:16.624  7063  7063 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-02 15:27:16.630  6433  6433 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-02 15:27:16.634  7035  7035 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-02 15:27:16.634  7035  7035 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-02 15:27:16.634  7035  7035 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-02 15:27:16.639  7015  7015 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-02 15:27:16.647  7015  7015 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 15:27:16.655  7063  7063 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-02 15:27:16.655  7063  7063 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-02 15:27:16.660  7063  7063 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-02 15:27:16.671  7035  7035 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-02 15:27:16.677  7015  7015 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-02 15:27:16.687  7105  7566 W FormManager: Network not available. Please check & try again.
09-02 15:27:16.689  7015  7015 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 15:27:16.695  7105  7567 V FormManager: Network unavailable.
,09-02 15:27:16.706  7105  7567 V FormManager: Network unavailable.
09-02 15:27:16.710  4743  4743 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
,09-02 15:27:16.710  4743  4743 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-02 15:27:16.712  4743  4743 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-02 15:27:16.717  4743  4743 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-02 15:27:16.728  7035  7035 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
09-02 15:27:16.728  7035  7035 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
,09-02 15:27:16.728  7035  7035 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-02 15:27:16.729  4743  7569 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-02 15:27:16.729  4743  7569 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-02 15:27:16.730  4743  7568 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-02 15:27:16.736  7015  7015 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-02 15:27:16.741  7105  7571 W FormManager: Network not available. Please check & try again.
09-02 15:27:16.744  7105  7572 V FormManager: Network unavailable.
,09-02 15:27:16.747  7105  7572 V FormManager: Network unavailable.
09-02 15:27:16.748  7015  7015 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 15:27:16.765  2160  2160 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,09-02 15:27:17.500  1043  1377 E WifiStateMachine:  InitialState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1312] from screen [on:0 period:-350945028] gl rssi=-47 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,09-02 15:27:17.502  1043  1377 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-350945026] gl rssi=-47 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,09-02 15:27:17.585  1043  1431 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-02 15:27:17.603  1043  1114 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-02 15:27:17.607  1043  1119 D Tethering: MasterInitialState.processMessage what=3
09-02 15:27:17.611  6878  6878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 15:27:17.613  6878  6878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 15:27:17.618  6433  6433 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,09-02 15:27:17.622  6433  7034 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-02 15:27:17.632  5708  5708 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,09-02 15:27:17.651  2160  2160 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-02 15:27:17.675  7197  7197 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-02 15:27:17.675  7197  7197 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-02 15:27:17.675  7197  7197 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-02 15:27:17.675  7197  7197 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,09-02 15:27:17.681  7197  7197 I AppUp4:CustModeStarterReceiver: onReceive
09-02 15:27:17.685  7197  7197 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2f87e5be
09-02 15:27:17.685  7197  7197 D AppUp4:CustFacade: isCustomizationCompleted : false
09-02 15:27:17.685  7197  7197 D AppUp4:CustFacade: isPhone : true
09-02 15:27:17.685  7197  7197 D AppUp4:CustModeStarterReceiver: begin check event
09-02 15:27:17.685  7197  7197 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-02 15:27:17.690  4743  4743 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-02 15:27:17.690  4743  4743 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-02 15:27:17.692  4743  4743 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-02 15:27:17.702  4743  4743 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-02 15:27:17.710  7229  7229 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,09-02 15:27:17.749  1043  1114 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 15:27:17.749  3395  3395 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-02 15:27:17.749  3395  3395 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-02 15:27:17.750  3395  3395 I LgeMiscReceiver: networkInfo.isConnected() = true
09-02 15:27:17.750  3395  3395 D PhoneState: setPdpRejectCasuse : false
09-02 15:27:17.756  7269  7269 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,09-02 15:27:17.757  7269  7269 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-02 15:27:17.763  7229  7580 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 15:27:17.769  4743  7598 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,09-02 15:27:17.775  7341  7341 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:27:17
09-02 15:27:17.778  7341  7341 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-02 15:27:17.778  7341  7341 D Weather.Utils: 2 : All the weather widget is gone.
09-02 15:27:17.779  7105  7600 V FormManager: Network unavailable.
09-02 15:27:17.779  7341  7341 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-02 15:27:17.780  7341  7341 D WeatherAncestor: connectivity changed - connection : true
09-02 15:27:17.780  7341  7341 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@31099d6c
09-02 15:27:17.780  4743  7601 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-02 15:27:17.780  4743  7601 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-02 15:27:17.781  7341  7341 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-02 15:27:17.781  7105  7599 W FormManager: Network not available. Please check & try again.
09-02 15:27:17.781  7341  7341 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-02 15:27:17.781  7341  7341 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-02 15:27:17.781  7341  7341 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-02 15:27:17.781  7341  7341 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:27:17
,09-02 15:27:17.786  7105  7600 V FormManager: Network unavailable.
,09-02 15:27:18.522  1043  1060 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 15:27:18.523  1043  1060 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,09-02 15:27:18.561  1043  1043 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-02 15:27:18.562  1043  1043 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-02 15:27:18.562  1043  1043 D Ulp_jni : JNI:system_update. Event-4
09-02 15:27:18.563  1043  1119 D BluetoothManagerService: Message: 1
09-02 15:27:18.563  1043  1119 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
09-02 15:27:18.589  1043  1119 D BluetoothManagerService: Message: 20
09-02 15:27:18.590  1043  1119 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1cb0958e:true
,09-02 15:27:18.595  7129  7129 D BluetoothAdapterState: make
09-02 15:27:18.600  7129  7129 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
09-02 15:27:18.601  7129  7129 I bluedroid-qcom: init
09-02 15:27:18.602  7129  7612 I BluetoothAdapterState: Entering OffState
09-02 15:27:18.602  7129  7129 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-02 15:27:18.602  7129  7129 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-02 15:27:18.603  7129  7129 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-02 15:27:18.603  7129  7129 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-02 15:27:18.603  7129  7129 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
09-02 15:27:18.605  7129  7129 I bluedroid-qcom: get_profile_interface socket
09-02 15:27:18.605  7129  7129 I bluedroid-qcom: get_profile_interface map_client
,09-02 15:27:18.610  7129  7616 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
09-02 15:27:18.605  7615  7615 W bdaddr_loader: type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-02 15:27:18.605  7615  7615 W bdaddr_loader: type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-02 15:27:18.623  7615  7615 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
09-02 15:27:18.623  7615  7615 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
09-02 15:27:18.623  7615  7615 I LGFTMITEM: [GET_FTM][id=8], offset=16384
,09-02 15:27:18.628  1043  1043 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
09-02 15:27:18.628  1043  1119 D BluetoothManagerService: Message: 40
09-02 15:27:18.628  1043  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
09-02 15:27:18.629  7129  7147 I bluedroid-qcom: config_hci_snoop_log
09-02 15:27:18.630  1043  1431 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-02 15:27:18.636  7615  7615 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
,09-02 15:27:18.642  6878  6878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 15:27:18.644  6878  6878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 15:27:18.645  1043  1119 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
09-02 15:27:18.646  1043  1119 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
09-02 15:27:18.649  1043  1431 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-02 15:27:18.655  7615  7615 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
09-02 15:27:18.655  7615  7615 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
09-02 15:27:18.666  7129  7616 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,09-02 15:27:18.672  7129  7612 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
09-02 15:27:18.675  1043  1119 D Tethering: MasterInitialState.processMessage what=3
,09-02 15:27:18.675  1043  1119 D Tethering: MasterInitialState.processMessage what=3
09-02 15:27:18.682  6433  6433 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,09-02 15:27:18.687  6433  7034 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-02 15:27:18.689  1043  1114 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-02 15:27:18.690  6878  6878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 15:27:18.691  1043  1043 D BluetoothManagerService: Bluetooth Adapter name changed to G3
09-02 15:27:18.692  1043  1043 D BluetoothManagerService: Stored Bluetooth name: G3
,09-02 15:27:18.698  6878  6878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 15:27:18.699  7129  7616 D BluetoothAdapterProperties: Name is: G3
09-02 15:27:18.700  7129  7612 D BluetoothAdapterProperties: Setting state to 11
09-02 15:27:18.700  7129  7612 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
09-02 15:27:18.702  1043  1119 D BluetoothManagerService: Message: 60
09-02 15:27:18.702  1043  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
09-02 15:27:18.702  1043  1119 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
09-02 15:27:18.704  7129  7612 I LGBluetoothServiceJni: classInitNative: succeeds
09-02 15:27:18.704  1043  1114 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-02 15:27:18.704  5708  5708 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
09-02 15:27:18.705  1043  1114 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 15:27:18.705  1043  1114 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 15:27:18.706  1928  1928 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-02 15:27:18.707  1589  1589 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-02 15:27:18.709  7015  7015 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
,09-02 15:27:18.714  7129  7612 D BluetoothBondStateMachine: make
09-02 15:27:18.717  6878  6878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 15:27:18.720  7129  7129 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-02 15:27:18.720  7129  7129 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-02 15:27:18.721  7129  7129 V BluetoothPbapReceiver: ***********state = 11
09-02 15:27:18.722  7129  7612 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@31099d6c
09-02 15:27:18.722  7129  7612 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
09-02 15:27:18.722  7129  7612 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@31099d6c
09-02 15:27:18.722  7129  7612 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
09-02 15:27:18.723  7129  7612 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
09-02 15:27:18.724  7129  7634 I BluetoothBondStateMachine: StableState(): Entering Off State
09-02 15:27:18.725  6878  6878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 15:27:18.727  2160  2160 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-02 15:27:18.733  7129  7612 E BluetoothAdapterService: File transfer profiles supported!!
09-02 15:27:18.775  1043  1865 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7635 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,09-02 15:27:18.783  7129  7612 E BluetoothAdapterService: File transfer profiles supported!!
09-02 15:27:18.784  5708  5708 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
09-02 15:27:18.785  7129  7129 D HeadsetService: Received start request. Starting profile...
09-02 15:27:18.786  7129  7129 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
09-02 15:27:18.786  7129  7129 D LGBluetoothHfpAdapter: Version 1.6
09-02 15:27:18.788  7129  7612 E BluetoothAdapterService: File transfer profiles supported!!
09-02 15:27:18.789  7129  7129 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
09-02 15:27:18.791  7129  7129 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-02 15:27:18.791  7129  7129 D HeadsetStateMachine: make
,09-02 15:27:18.799  7129  7612 E BluetoothAdapterService: File transfer profiles supported!!
09-02 15:27:18.802  2160  2160 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
09-02 15:27:18.804  7129  7612 E BluetoothAdapterService: File transfer profiles supported!!
09-02 15:27:18.812  7129  7612 E BluetoothAdapterService: File transfer profiles supported!!
09-02 15:27:18.812  7197  7197 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
,09-02 15:27:18.814  7197  7197 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-02 15:27:18.814  7197  7197 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-02 15:27:18.814  7197  7197 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-02 15:27:18.817  7197  7197 I AppUp4:CustModeStarterReceiver: onReceive
09-02 15:27:18.817  7129  7612 E BluetoothAdapterService: File transfer profiles supported!!
09-02 15:27:18.820  7197  7197 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2f87e5be
09-02 15:27:18.820  7197  7197 D AppUp4:CustFacade: isCustomizationCompleted : false
09-02 15:27:18.820  7197  7197 D AppUp4:CustFacade: isPhone : true
09-02 15:27:18.821  7197  7197 D AppUp4:CustModeStarterReceiver: begin check event
09-02 15:27:18.821  7197  7197 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-02 15:27:18.824  4743  4743 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-02 15:27:18.824  4743  4743 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-02 15:27:18.825  4743  4743 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-02 15:27:18.831  4743  4743 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-02 15:27:18.833  7129  7129 D LgDataFeature: LgDataFeature() Constructor: none
09-02 15:27:18.833  7129  7129 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-02 15:27:18.838  7129  7129 D HeadsetStateMachine: max_hf_connections = 1
,09-02 15:27:18.838  7129  7129 I bluedroid-qcom: get_profile_interface handsfree
09-02 15:27:18.838  7229  7229 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
09-02 15:27:18.840  7129  7129 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
09-02 15:27:18.840  7129  7612 V LGMDMManager: Create singleton instance
09-02 15:27:18.840   308  1383 V AudioPolicyService: registerClient() client 0xb1020dc0, uid 1002
09-02 15:27:18.841   308  1384 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
09-02 15:27:18.841   308  1384 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-02 15:27:18.841   308  1384 V AudioPolicyManagerEx: getOutput() returns output 2
09-02 15:27:18.841  7129  7612 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
09-02 15:27:18.842  4743  7654 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-02 15:27:18.843  7129  7129 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
09-02 15:27:18.843   308  2156 V AudioFlinger: registerClient() client 0xb101fad8, pid 7129
09-02 15:27:18.844   308  1378 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-02 15:27:18.844   308  1378 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-02 15:27:18.844  7129  7129 V ToneGenerator: Create Track: 0xb4928080
09-02 15:27:18.844  7129  7129 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
09-02 15:27:18.844  7129  7129 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
09-02 15:27:18.844  1043  2018 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-02 15:27:18.844  1043  2018 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-02 15:27:18.844  1589  2083 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-02 15:27:18.844  1589  2083 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-02 15:27:18.844   308  1379 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-02 15:27:18.844   308  1379 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-02 15:27:18.844  1836  2685 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-02 15:27:18.844  1836  2685 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-02 15:27:18.844  3395  3418 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-02 15:27:18.844   308  1383 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
09-02 15:27:18.844  3395  3418 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-02 15:27:18.844   308  1383 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
09-02 15:27:18.844   308  1383 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-02 15:27:18.844   308  1383 V AudioPolicyManagerEx: getOutput() returns output 2
09-02 15:27:18.844  7129  7147 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-02 15:27:18.844  7129  7147 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
09-02 15:27:18.844  1043  1873 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-02 15:27:18.844  1043  1873 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-02 15:27:18.844  1589  1608 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-02 15:27:18.844  1589  1608 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-02 15:27:18.845  1836  1852 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-02 15:27:18.845  1836  1852 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-02 15:27:18.845  7129  7148 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-02 15:27:18.845  3395  3,417 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-02 15:27:18.845  7129  7148 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
09-02 15:27:18.845  3395  3417 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-02 15:27:18.845   308  2156 I AudioFlinger: isAudioPlaybackHookOn() false
09-02 15:27:18.847   308  2157 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
09-02 15:27:18.847   308  2157 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
09-02 15:27:18.847   308  2157 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-02 15:27:18.847   308  2157 V AudioPolicyManagerEx: getOutput() returns output 2
09-02 15:27:18.847  7129  7129 V AudioSystem: getLatency() output 2, latency 50
09-02 15:27:18.847  7129  7129 V AudioSystem: getFrameCount() output 2, frameCount 960
09-02 15:27:18.847  7129  7129 V AudioTrack: createTrack_l() output 2 afLatency 50
09-02 15:27:18.847   308  1383 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
09-02 15:27:18.847   308  1383 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
09-02 15:27:18.847   308  1383 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
09-02 15:27:18.847   308  1383 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
09-02 15:27:18.847   308  1383 V AudioFlinger: createTrack() lSessionId: 20
09-02 15:27:18.848  7129  7129 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
09-02 15:27:18.849   308  1383 V AudioFlinger: acquiring 20 from 7129, for 7129
09-02 15:27:18.849   308  1383 V AudioFlinger:  added new entry for 20
09-02 15:27:18.849  7129  7129 V ToneGenerator: ToneGenerator INIT OK, time: 192123
09-02 15:27:18.849  7129  7129 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@31099d6c
09-02 15:27:18.851  7129  7129 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@31099d6c
09-02 15:27:18.854  7129  7129 D A2dpService: Received start request. Starting profile...
09-02 15:27:18.855  7129  7129 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-02 15:27:18.856  7129  7129 V Avrcp   : make
09-02 15:27:18.857  7129  7129 D Avrcp   : [BTUI] Use Native AVRCP : init jni
09-02 15:27:18.857  7129  7129 I bluedroid-qcom: get_profile_interface avrcp
09-02 15:27:18.859  7129  7650 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
09-02 15:27:18.859  7129  7650 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-02 15:27:18.859  7129  7650 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-02 15:27:18.859  7129  7650 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
09-02 15:27:18.859   308  1384 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7129
09-02 15:27:18.852  4743  7655 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-02 15:27:18.860   308  1384 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
09-02 15:27:18.860   308  1384 V voice   : voice_set_parameters: enter: bt_samplerate=8000
09-02 15:27:18.860   308  1384 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
09-02 15:27:18.860   308  1384 V compress_voip: voice_extn_compress_voip_set_parameters: exit
09-02 15:27:18.860   308  1384 V voice   : voice_set_parameters: exit with code(0)
09-02 15:27:18.860   308  1384 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
09-02 15:27:18.860   308  1384 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
09-02 15:27:18.860   308  1384 V msm8974_platform: platform_set_parameters: exit with code(0)
09-02 15:27:18.860   308  1384 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
09-02 15:27:18.861   308  1384 V audio_hw_primary: adev_set_parameters: exit with code(0)
09-02 15:27:18.861   308  1384 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
09-02 15:27:18.861  7129  7650 V ToneGenerator: ToneGenerator destructor
09-02 15:27:18.861  7129  7650 V ToneGenerator: stopTone
09-02 15:27:18.861  7129  7650 V ToneGenerator: Delete Track: 0xb4928080
09-02 15:27:18.861  7129  7650 V AudioTrack: ~AudioTrack, releasing session id from 7129 on behalf of 7129
09-02 15:27:18.861   308  2156 V AudioPolicyService: AudioCommandThread() adding release output 2
09-02 15:27:18.861   308  2156 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
09-02 15:27:18.861   308  2156 V AudioFlinger: PlaybackThread::Track destructor
09-02 15:27:18.861   308  1383 V AudioFlinger: releasing 20 from 7129 for 7129
09-02 15:27:18.861   308  1383 V AudioFlinger:  decremented refcount to 0
09-02 15:27:18.861   308  2156 V AudioFlinger: removeClient_l() pid 7129, calling pid 308
09-02 15:27:18.861   308  1383 V AudioFlinger: purging stale effects
09-02 15:27:18.862   308  1273 V AudioPolicyService: AudioCommandThread() waking up
09-02 15:27:18.862   308  1273 V AudioPolicyService: AudioCommandThread() processing release output 2
09-02 15:27:18.862   308  1273 V AudioPolicyManager: releaseOutput() 2
09-02 15:27:18.862   308  1273 V AudioPolicyService: AudioCommandThread() going to sleep
09-02 15:27:18.862  4743  7655 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-02 15:27:18.864  7229  7657 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 15:27:18.865  3395  3395 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-02 15:27:18.865  3395  3395 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-02 15:27:18.865  3395  3395 I LgeMiscReceiver: networkInfo.isConnected() = false
09-02 15:27:18.869  7129  7129 V AudioManager: registerRemoteController: size of Media player list: 0
09-02 15:27:18.870  7129  7129 E AudioManager: No RCC entry present to update
09-02 15:27:18.870  7129  7129 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
09-02 15:27:18.873  7129  7129 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
09-02 15:27:18.874  7129  7129 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
09-02 15:27:18.874  7129  7129 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
09-02 15:27:18.877  7269  7269 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-02 15:27:18.877  7269  7269 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,09-02 15:27:18.879  7129  7129 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
09-02 15:27:18.931  7341  7341 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:27:18
,09-02 15:27:18.932  7635  7635 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
09-02 15:27:18.932  7635  7635 W LG Account v2.2: No ProfileInfo entries
09-02 15:27:18.932  7635  7635 I LG Account v2.2: isEnabled: false
09-02 15:27:18.932  7635  7635 I Feature : [Lifetracker]ver: 4.21.112(40211120)
09-02 15:27:18.933  7635  7635 I Feature : [Lifetracker]Country: EU
09-02 15:27:18.933  7635  7635 I Feature : [Lifetracker]Operator: OPEN
09-02 15:27:18.933  7635  7635 I Feature : [Lifetracker]Ranking support: false
09-02 15:27:18.933  7635  7635 I Feature : [Lifetracker]Comfort support: false
09-02 15:27:18.933  7105  7663 W FormManager: Network not available. Please check & try again.
09-02 15:27:18.933  7635  7635 I Feature : [Lifetracker]Accessory: true
09-02 15:27:18.933  7635  7635 I Feature : [Lifetracker]Health device: true
09-02 15:27:18.933  7635  7635 I Feature : [Lifetracker]Extra Pedometer: false
09-02 15:27:18.933  7635  7635 I Feature : [Lifetracker]Blood glucose device: false
09-02 15:27:18.933  7635  7635 I Feature : [Lifetracker]Device Number: 3
09-02 15:27:18.935  7341  7341 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-02 15:27:18.935  7341  7341 D Weather.Utils: 2 : All the weather widget is gone.
09-02 15:27:18.935  7341  7341 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-02 15:27:18.935  7341  7341 D WeatherAncestor: connectivity changed - connection : true
09-02 15:27:18.935  7341  7341 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@31099d6c
09-02 15:27:18.936  7341  7341 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-02 15:27:18.936  7341  7341 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-02 15:27:18.936  7341  7341 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-02 15:27:18.936  7341  7341 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-02 15:27:18.936  7341  7341 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:27:18
09-02 15:27:18.946  7105  7664 V FormManager: Network unavailable.
,09-02 15:27:18.954  7015  7015 D BluetoothPermissionRequest: onReceive
09-02 15:27:18.958  7105  7664 V FormManager: Network unavailable.
,09-02 15:27:18.959  7015  7015 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-02 15:27:18.972  6433  6433 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,09-02 15:27:18.973  6433  7034 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-02 15:27:18.989  1043  1927 V SIM_STK : Menu title from STK is T-Mobile
,09-02 15:27:18.989  1043  1927 V SIM_STK : Menu title from STK is T-Mobile
09-02 15:27:19.108  1043  1926 I art     : Explicit concurrent mark sweep GC freed 125275(5MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/64MB, paused 1.969ms total 133.076ms
,09-02 15:27:19.111  1043  1979 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
09-02 15:27:19.117  7129  7129 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
09-02 15:27:19.117  2160  2160 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-02 15:27:19.121  7129  7129 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
09-02 15:27:19.121  7129  7129 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
09-02 15:27:19.121  7129  7129 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
09-02 15:27:19.121  7129  7129 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
09-02 15:27:19.122  7129  7129 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-02 15:27:19.122  7129  7129 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
09-02 15:27:19.122  7129  7129 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
09-02 15:27:19.122  7129  7129 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
09-02 15:27:19.122  7129  7129 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-02 15:27:19.122  7129  7129 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
09-02 15:27:19.122  7129  7129 I BluetoothA2dpServiceJni: classInitNative
09-02 15:27:19.122  7129  7129 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-02 15:27:19.122  7129  7129 D A2dpStateMachine: make
09-02 15:27:19.124  7129  7129 I bluedroid-qcom: get_profile_interface a2dp
09-02 15:27:19.124  7129  7668 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
09-02 15:27:19.126  7129  7129 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
09-02 15:27:19.126  7129  7129 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
09-02 15:27:19.127  7129  7129 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@31099d6c
09-02 15:27:19.127  7129  7129 I BluetoothHidServiceJni: classInitNative: succeeds
09-02 15:27:19.129  7129  7667 D A2dpStateMachine: Enter Disconnected: -2
09-02 15:27:19.129  7129  7129 D HidService: Received start request. Starting profile...
09-02 15:27:19.129  7129  7129 I bluedroid-qcom: get_profile_interface hidhost
09-02 15:27:19.129  7129  7129 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@31099d6c
09-02 15:27:19.129  7129  7129 I BluetoothHealthServiceJni: classInitNative: succeeds
09-02 15:27:19.130  7129  7129 D HealthService: Received start request. Starting profile...
09-02 15:27:19.131  7197  7197 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-02 15:27:19.131  7129  7129 I bluedroid-qcom: get_profile_interface health
09-02 15:27:19.131  7197  7197 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-02 15:27:19.132  7129  7129 I LGBluetoothHealthServiceJni: classInitNative: succeeds
09-02 15:27:19.132  7197  7197 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-02 15:27:19.132  7129  7129 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@31099d6c
09-02 15:27:19.132  7197  7197 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,09-02 15:27:19.137  7129  7129 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-02 15:27:19.138  7129  7129 D PanService: Received start request. Starting profile...
09-02 15:27:19.138  7129  7129 D BluetoothPanServiceJni: initializeNative(L110): pan
09-02 15:27:19.138  7129  7129 I bluedroid-qcom: get_profile_interface pan
09-02 15:27:19.142  7197  7197 I AppUp4:CustModeStarterReceiver: onReceive
09-02 15:27:19.143  7129  7129 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
,09-02 15:27:19.143  7129  7129 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@31099d6c
09-02 15:27:19.144  7129  7129 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
09-02 15:27:19.146  7197  7197 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2f87e5be
09-02 15:27:19.146  7197  7197 D AppUp4:CustFacade: isCustomizationCompleted : false
09-02 15:27:19.146  7197  7197 D AppUp4:CustFacade: isPhone : true
09-02 15:27:19.146  7197  7197 D AppUp4:CustModeStarterReceiver: begin check event
09-02 15:27:19.147  7197  7197 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-02 15:27:19.147  7129  7129 D BtGatt.DebugUtils: handleDebugAction() action=null
09-02 15:27:19.148  7129  7129 D BtGatt.GattService: Received start request. Starting profile...
09-02 15:27:19.148  7129  7129 D BtGatt.GattService: start()
09-02 15:27:19.148  7129  7129 I bluedroid-qcom: get_profile_interface gatt
09-02 15:27:19.148  7129  7129 D BtGatt.AdvertiseManager: advertise manager created
09-02 15:27:19.149  4743  4743 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-02 15:27:19.149  4743  4743 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-02 15:27:19.150  4743  4743 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-02 15:27:19.151  4743  4743 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-02 15:27:19.153  7129  7129 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@31099d6c
09-02 15:27:19.153  7129  7129 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@31099d6c
09-02 15:27:19.154  7129  7129 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
09-02 15:27:19.154  4743  7675 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,09-02 15:27:19.154  7129  7129 V BluetoothMapService: BluetoothMapBinder()
09-02 15:27:19.155  7129  7129 D BluetoothMapService: Received start request. Starting profile...
09-02 15:27:19.155  7129  7129 D BluetoothMapService: start()
09-02 15:27:19.157  7229  7229 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,09-02 15:27:19.157  7129  7129 D BluetoothMapEmailSettingsLoader: Found 0 applications
09-02 15:27:19.157  7129  7129 D BluetoothMapEmailAppObserver: createReceiver()
09-02 15:27:19.159  7129  7129 D BluetoothMapEmailAppObserver: initObservers()
09-02 15:27:19.159  7129  7129 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
09-02 15:27:19.164  7129  7129 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@31099d6c
09-02 15:27:19.165  7129  7129 D HeadsetStateMachine: Proxy object connected
09-02 15:27:19.165  7129  7129 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
09-02 15:27:19.165  7129  7129 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
09-02 15:27:19.166  4743  7676 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-02 15:27:19.166  4743  7676 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,09-02 15:27:19.170  7105  7678 W FormManager: Network not available. Please check & try again.
09-02 15:27:19.170  7129  7129 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-02 15:27:19.170  7129  7650 D HeadsetStateMachine: Disconnected process message: 10, size: 0
09-02 15:27:19.171  7129  7650 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-02 15:27:19.171  7129  7650 D HeadsetStateMachine: Disconnected process message: 11, size: 0
09-02 15:27:19.173  7129  7129 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-02 15:27:19.175  7129  7129 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-02 15:27:19.178  7129  7129 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-02 15:27:19.178  3395  3395 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-02 15:27:19.178  3395  3395 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
,09-02 15:27:19.178  3395  3395 I LgeMiscReceiver: networkInfo.isConnected() = false
09-02 15:27:19.180  7229  7680 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 15:27:19.181  7129  7129 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-02 15:27:19.181  7129  7129 V PanService: [BTUI] SIM Extra State :ABSENT
09-02 15:27:19.183  7129  7129 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
09-02 15:27:19.183  7129  7129 V BluetoothMapService: Handler(): got msg=1
09-02 15:27:19.184  7129  7612 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
09-02 15:27:19.184  7129  7612 I bluedroid-qcom: enable
09-02 15:27:19.184  7129  7612 I bt_hci_bdroid: init
09-02 15:27:19.184  7269  7269 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-02 15:27:19.184  7269  7269 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-02 15:27:19.184  7129  7682 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
09-02 15:27:19.185  7129  7612 I bt_vendor: bt-vendor : init
09-02 15:27:19.185  7129  7612 I bt_vendor: bt-vendor : get_bt_soc_type
09-02 15:27:19.185  7129  7612 E bt_vendor: get_bt_soc_type: Failed to get soc type
09-02 15:27:19.185  7129  7612 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
09-02 15:27:19.185  7129  7612 D bt_userial_mct: userial_init
09-02 15:27:19.185  7129  7682 I bt-btu  : btu_task pending for preload complete event
09-02 15:27:19.185  7129  7612 D bt_hci_bdroid: set_power 1
09-02 15:27:19.185  7129  7612 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
09-02 15:27:19.185  7129  7612 I bt_vendor: Starting hciattach daemon
09-02 15:27:19.185  7129  7612 I bt_vendor: try to set true
09-02 15:27:19.187  7129  7129 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-02 15:27:19.185  7685  7685 W sh      : type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-02 15:27:19.185  7685  7685 W sh      : type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-02 15:27:19.188  7129  7129 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-02 15:27:19.188  7129  7129 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-02 15:27:19.188  7129  7129 V BluetoothSapReceiver: SapReceiver onReceive 
09-02 15:27:19.188  7129  7129 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-02 15:27:19.188  7129  7129 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
09-02 15:27:19.189  7105  7679 V FormManager: Network unavailable.
,09-02 15:27:19.199  7341  7341 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:27:19
09-02 15:27:19.201  7105  7679 V FormManager: Network unavailable.
,09-02 15:27:19.202  7341  7341 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-02 15:27:19.202  7341  7341 D Weather.Utils: 2 : All the weather widget is gone.
09-02 15:27:19.203  7341  7341 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-02 15:27:19.203  7341  7341 D WeatherAncestor: connectivity changed - connection : true
09-02 15:27:19.203  7341  7341 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@31099d6c
09-02 15:27:19.203  7686  7686 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
09-02 15:27:19.205  7341  7341 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-02 15:27:19.205  7341  7341 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-02 15:27:19.205  7341  7341 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-02 15:27:19.205  7341  7341 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-02 15:27:19.205  7341  7341 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:27:19
09-02 15:27:19.258  7692  7692 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,09-02 15:27:19.271  7693  7693 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,09-02 15:27:19.304  7695  7695 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-02 15:27:19.319  7696  7696 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,09-02 15:27:19.338  7697  7697 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-02 15:27:19.366  7698  7698 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,09-02 15:27:19.389  7700  7700 I libmdmdetect: ESOC framework not supported
,09-02 15:27:19.390  7700  7700 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,09-02 15:27:19.400  7700  7700 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
,09-02 15:27:19.400  7700  7700 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
09-02 15:27:19.400  7700  7700 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
09-02 15:27:19.400  7700  7700 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
09-02 15:27:19.400  7700  7700 D bthci_qcomm_common: [BTUI]     LE: Class 2
09-02 15:27:19.400  7700  7700 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
09-02 15:27:19.400  7700  7700 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
09-02 15:27:19.440  7700  7701 E QC-QMI  : qmi_client [7700] 14: failed to locate client data
09-02 15:27:19.442   455   455 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
09-02 15:27:19.442   455   455 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
,09-02 15:27:19.480  7705  7705 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,09-02 15:27:19.510  7709  7709 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,09-02 15:27:19.543  7129  7612 I bt_vendor: bluetooth satus is on
09-02 15:27:19.543  7129  7612 D bt_hci_bdroid: preload
09-02 15:27:19.543  7129  7684 D bt_userial_mct: userial_open(port:0)
09-02 15:27:19.543  7129  7684 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,09-02 15:27:19.546  1043  1115 W ProcessCpuTracker: Skipping unknown process pid 7626
09-02 15:27:19.546  7129  7684 I bt_vendor: Done intiailizing UART
09-02 15:27:19.547  7129  7684 I bt_vendor: Done intiailizing UART
09-02 15:27:19.547  7129  7684 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
09-02 15:27:19.547  1043  1115 W ProcessCpuTracker: Skipping unknown process pid 7627
09-02 15:27:19.547  7129  7684 I bt_vendor: Bluetooth Firmware and transport layer are initialized
09-02 15:27:19.547  7129  7682 I bt-btu  : btu_task received preload complete event
09-02 15:27:19.547  7129  7711 D bt_userial_mct: Entering userial_read_thread()
09-02 15:27:19.548  7129  7682 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
09-02 15:27:19.548  7129  7682 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
09-02 15:27:19.548  1043  1115 W ProcessCpuTracker: Skipping unknown process pid 7630
09-02 15:27:19.550  7129  7682 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
09-02 15:27:19.550  1043  1115 W ProcessCpuTracker: Skipping unknown process pid 7658
09-02 15:27:19.551  1043  1115 W ProcessCpuTracker: Skipping unknown process pid 7685
09-02 15:27:19.552  1043  1115 W ProcessCpuTracker: Skipping unknown process pid 7702
09-02 15:27:19.552  7129  7682 I         : BTE_InitTraceLevels -- TRC_HCI
09-02 15:27:19.552  7129  7682 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-02 15:27:19.552  7129  7682 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-02 15:27:19.552  7129  7682 I         : BTE_InitTraceLevels -- TRC_AVDT
09-02 15:27:19.552  7129  7682 I         : BTE_InitTraceLevels -- TRC_AVRC
09-02 15:27:19.552  7129  7682 I         : BTE_InitTraceLevels -- TRC_A2D
09-02 15:27:19.552  7129  7682 I         : BTE_InitTraceLevels -- TRC_BNEP
09-02 15:27:19.552  7129  7682 I         : BTE_InitTraceLevels -- TRC_BTM
09-02 15:27:19.552  7129  7682 I         : BTE_InitTraceLevels -- TRC_HID_HOST
09-02 15:27:19.552  7129  7682 I         : BTE_InitTraceLevels -- TRC_GAP
09-02 15:27:19.552  7129  7682 I         : BTE_InitTraceLevels -- TRC_PAN
09-02 15:27:19.552  7129  7682 I         : BTE_InitTraceLevels -- TRC_SDP
09-02 15:27:19.552  7129  7682 I         : BTE_InitTraceLevels -- TRC_GATT
09-02 15:27:19.552  7129  7682 I         : BTE_InitTraceLevels -- TRC_SMP
09-02 15:27:19.552  7129  7682 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-02 15:27:19.552  7129  7682 I         : BTE_InitTraceLevels -- TRC_BTIF
09-02 15:27:19.552  1043  1115 W ProcessCpuTracker: Skipping unknown process pid 7710
09-02 15:27:19.601  7129  7682 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
09-02 15:27:19.601  7129  7682 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa01af061 
09-02 15:27:19.601  7129  7682 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa01af061 
,09-02 15:27:19.631  7129  7616 E bt-btif : Calling BTA_HhEnable
09-02 15:27:19.631  7129  7682 W bt-l2cap: btif_storage_get_adapter_property service_mask
09-02 15:27:19.631  7129  7616 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
09-02 15:27:19.631  7129  7682 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
09-02 15:27:19.631  7129  7682 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
09-02 15:27:19.632  7129  7682 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
09-02 15:27:19.632  7129  7682 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
09-02 15:27:19.632  7129  7616 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,09-02 15:27:19.634  7129  7616 D BluetoothAdapterProperties: Name is: G3
09-02 15:27:19.637  1043  1043 D BluetoothManagerService: Bluetooth Adapter name changed to G3
09-02 15:27:19.638  1043  1043 D BluetoothManagerService: Stored Bluetooth name: G3
09-02 15:27:19.639  7129  7616 D BluetoothAdapterProperties: Scan Mode:20
09-02 15:27:19.639  7129  7616 D BluetoothAdapterProperties: Discoverable Timeout:120
09-02 15:27:19.640  7129  7616 D bt_hci_bdroid: postload
09-02 15:27:19.641  7129  7684 D bt_hci_bdroid: Used up Tx Cmd credits
09-02 15:27:19.641  7129  7684 D bt_hci_bdroid: Used up Tx Cmd credits
09-02 15:27:19.641  7129  7682 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
09-02 15:27:19.642  7129  7616 D bte_conf: Device ID record 1 : primary
09-02 15:27:19.642  7129  7616 D bte_conf:   vendorId            = 00c4
09-02 15:27:19.642  7129  7616 D bte_conf:   vendorIdSource      = 0001
09-02 15:27:19.642  7129  7616 D bte_conf:   product             = 13a1
09-02 15:27:19.642  7129  7616 D bte_conf:   version             = 1000
09-02 15:27:19.642  7129  7616 D bte_conf:   clientExecutableURL = 
09-02 15:27:19.642  7129  7616 D bte_conf:   serviceDescription  = 
,09-02 15:27:19.642  7129  7616 D bte_conf:   documentationURL    = 
,09-02 15:27:19.642  7129  7616 D bte_conf: bte_load_did_conf no section named DID2.
09-02 15:27:19.643  6878  6878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 15:27:19.651  7129  7682 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
,09-02 15:27:19.651  7129  7682 W bt-smp  : Plain text(LSB ~ MSB) = f4 b6 7e 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-02 15:27:19.651  7129  7616 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-02 15:27:19.651  7129  7612 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
09-02 15:27:19.651  7129  7612 D BluetoothAdapterProperties: ScanMode =  20
09-02 15:27:19.652  7129  7612 D BluetoothAdapterProperties: State =  11
09-02 15:27:19.652  7129  7612 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
,09-02 15:27:19.652  7129  7612 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
09-02 15:27:19.653  7129  7612 D BluetoothAdapterProperties: Setting state to 12
09-02 15:27:19.653  7129  7612 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-02 15:27:19.653  7129  7682 W bt-smp  : Encrypted text(LSB ~ MSB) = 29 36 fe 09 8e 48 7c 50 30 05 b6 1e a5 9c 56 46 
09-02 15:27:19.645  7713  7713 W sh      : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-02 15:27:19.645  7713  7713 W sh      : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-02 15:27:19.654  7129  7616 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-02 15:27:19.655  7129  7682 W bt-btm  : Stopping oneshot timer,
09-02 15:27:19.655  7129  7684 D bt_hci_bdroid: Used up Tx Cmd credits
09-02 15:27:19.655  7129  7684 D bt_hci_bdroid: Used up Tx Cmd credits
09-02 15:27:19.659  7129  7684 D bt_hci_bdroid: Used up Tx Cmd credits
09-02 15:27:19.660  7129  7684 D bt_hci_bdroid: Used up Tx Cmd credits
,09-02 15:27:19.669  7129  7684 D bt_hci_bdroid: Used up Tx Cmd credits
09-02 15:27:19.669  7129  7684 D bt_hci_bdroid: Used up Tx Cmd credits
09-02 15:27:19.673  7129  7711 E bt_mct  : hci lib postload completed
09-02 15:27:19.673  6878  6878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 15:27:19.673  6878  6878 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 15:27:19.673  6878  6878 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 15:27:19.673  6878  6878 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 15:27:19.673  6878  6878 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 15:27:19.673  6878  6878 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 15:27:19.673  6878  6878 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 15:27:19.673  6878  6878 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-02 15:27:19.683  7129  7616 D BluetoothAdapterProperties: Discoverable Timeout:120
09-02 15:27:19.683  7129  7616 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
09-02 15:27:19.684  7129  7612 I BluetoothAdapterState: Entering On State
,09-02 15:27:19.686  1043  1119 D BluetoothManagerService: Message: 60
09-02 15:27:19.686  1043  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
09-02 15:27:19.686  1043  1119 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
09-02 15:27:19.686  1043  1119 D BluetoothA2dp: onBluetoothStateChange: up=true
09-02 15:27:19.689  6878  6878 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-02 15:27:19.690  7129  7612 D LGBluetoothServiceAdapter: [BTUI] OnState
09-02 15:27:19.690  7129  7612 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
09-02 15:27:19.691  7129  7612 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
09-02 15:27:19.692  7129  7612 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
09-02 15:27:19.694  1043  1043 D BluetoothA2dp: Proxy object connected
09-02 15:27:19.700  7015  7031 D BluetoothPan: onBluetoothStateChange on: true
09-02 15:27:19.700  7015  7031 D BluetoothPan: onBluetoothStateChange call bindService
,09-02 15:27:19.703  7129  7682 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-02 15:27:19.703  7129  7682 W bt-smp  : Plain text(LSB ~ MSB) = c7 e1 4d 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-02 15:27:19.703  7129  7682 W bt-smp  : Encrypted text(LSB ~ MSB) = a4 25 cf 8f ac 64 94 ef 28 06 ad 85 80 9e 64 d6 
09-02 15:27:19.703  7129  7682 W bt-btm  : Stopping oneshot timer
09-02 15:27:19.707  1043  1119 D BluetoothHeadset: onBluetoothStateChange: up=true
09-02 15:27:19.708  1836  3496 D BluetoothHeadset: onBluetoothStateChange: up=true
09-02 15:27:19.712  7015  7104 D BluetoothPbap: onBluetoothStateChange: up=true
09-02 15:27:19.714  7015  7015 D BluetoothPan: BluetoothPAN Proxy object connected
09-02 15:27:19.714  7015  7015 D PanProfile: Bluetooth service connected
09-02 15:27:19.715  1836  2685 D BluetoothHeadset: onBluetoothStateChange: up=true
09-02 15:27:19.719  7129  7682 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-02 15:27:19.719  7129  7682 W bt-smp  : Plain text(LSB ~ MSB) = 1f aa 4d 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-02 15:27:19.719  7129  7682 W bt-smp  : Encrypted text(LSB ~ MSB) = 8b f5 ac c7 67 bb c9 41 7a 5d bc bc 1f 2e c8 85 
09-02 15:27:19.719  7129  7682 W bt-btm  : Stopping oneshot timer
,09-02 15:27:19.721  1043  1043 D BluetoothHeadset: Proxy object connected
09-02 15:27:19.724  7015  7031 D BluetoothMap: onBluetoothStateChange: up=true
09-02 15:27:19.727  1836  1836 D BluetoothHeadset: Proxy object connected
09-02 15:27:19.727  1836  1836 D BluetoothHeadset: Proxy object connected
09-02 15:27:19.732  7129  7612 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
09-02 15:27:19.735  1836  1851 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-02 15:27:19.738  7718  7718 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
09-02 15:27:19.740  7129  7682 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-02 15:27:19.740  7129  7682 W bt-smp  : Plain text(LSB ~ MSB) = 87 f1 40 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-02 15:27:19.740  7129  7682 W bt-smp  : Encrypted text(LSB ~ MSB) = 02 be 5e 87 c7 a2 b6 19 a9 ea b2 16 d3 94 90 ac 
09-02 15:27:19.740  7129  7682 W bt-btm  : Stopping oneshot timer
09-02 15:27:19.740  7015  7015 D BluetoothMap: Proxy object connected
09-02 15:27:19.740  7015  7015 D MapProfile: Bluetooth service connected
09-02 15:27:19.740  7015  7015 D BluetoothMap: getConnectedDevices()
09-02 15:27:19.741  1836  1836 D BluetoothHeadset: Proxy object connected
09-02 15:27:19.741  7015  7031 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-02 15:27:19.742  7129  7148 V BluetoothMapService: getConnectedDevices()
09-02 15:27:19.748  7015  7015 D BluetoothInputDevice: Proxy object connected
09-02 15:27:19.748  7015  7015 D HidProfile: Bluetooth service connected
,09-02 15:27:19.752  1043  1119 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
09-02 15:27:19.752  1043  1119 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
09-02 15:27:19.754  1043  1043 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
09-02 15:27:19.756  1928  1928 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-02 15:27:19.756  1589  1589 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-02 15:27:19.756  1928  2066 D LGBluetoothAPIService: Message: 1
09-02 15:27:19.757  1928  2066 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
,09-02 15:27:19.760  7129  7682 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-02 15:27:19.760  7129  7682 W bt-smp  : Plain text(LSB ~ MSB) = 27 80 48 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-02 15:27:19.760  7129  7682 W bt-smp  : Encrypted text(LSB ~ MSB) = c7 8d 1b d8 d0 29 03 77 e8 bd ee 33 24 35 5a d5 
09-02 15:27:19.760  7129  7682 W bt-btm  : Stopping oneshot timer
09-02 15:27:19.763  1928  2066 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
09-02 15:27:19.765  6878  6878 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
09-02 15:27:19.766  1043  1119 D BluetoothManagerService: Message: 40
09-02 15:27:19.766  1043  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
09-02 15:27:19.774  6878  6878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 15:27:19.774  6878  6878 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 15:27:19.774  6878  6878 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 15:27:19.774  6878  6878 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 15:27:19.774  6878  6878 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 15:27:19.774  6878  6878 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 15:27:19.774  6878  6878 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 15:27:19.774  6878  6878 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-02 15:27:19.774  7129  7129 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-02 15:27:19.774  7129  7129 D BluetoothMapService: STATE_ON
09-02 15:27:19.776  7129  7129 D LGBluetoothAPIServer: [BTUI] onCreate()
09-02 15:27:19.777  7129  7129 D LGBluetoothAPIServer: [BTUI] onBind()
,09-02 15:27:19.778  7015  7015 D LocalBluetoothProfileManager: Adding local A2DP profile
09-02 15:27:19.781  6878  6878 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-02 15:27:19.783  1928  1928 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
09-02 15:27:19.783  1928  2066 D LGBluetoothAPIService: Message: 100
09-02 15:27:19.783  1928  2066 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
09-02 15:27:19.784  6878  6878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 15:27:19.786  1043  1119 D BluetoothManagerService: Message: 30
09-02 15:27:19.790  7015  7015 D LocalBluetoothProfileManager: Adding local HEADSET profile
09-02 15:27:19.793  1043  1119 D BluetoothManagerService: Message: 30
,09-02 15:27:19.798  7015  7015 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
09-02 15:27:19.800  7015  7015 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-02 15:27:19.801  7129  7129 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@31099d6c
09-02 15:27:19.801  7129  7129 V BluetoothPbapService: Pbap Service onCreate
09-02 15:27:19.801  7129  7129 V BluetoothPbapService: Starting PBAP service
09-02 15:27:19.802  7015  7015 D BluetoothA2dp: Proxy object connected
09-02 15:27:19.802  7129  7129 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
09-02 15:27:19.803  7129  7129 V BluetoothPbapService: Pbap Service onBind
09-02 15:27:19.803  7015  7015 D A2dpProfile: Bluetooth service connected
09-02 15:27:19.805  7129  7129 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-02 15:27:19.805  7129  7129 V BluetoothPbapService: state: 12
09-02 15:27:19.806  7129  7129 V BluetoothMapService: Handler(): got msg=1
09-02 15:27:19.806  7129  7129 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
09-02 15:27:19.807  7129  7129 V BluetoothPbapService: Handler(): got msg=1
09-02 15:27:19.807  7129  7129 V BluetoothPbapService: Pbap Service startRfcommSocketListener
09-02 15:27:19.808  7015  7015 D BluetoothHeadset: Proxy object connected
09-02 15:27:19.809  7015  7015 D HeadsetProfile: Bluetooth service connected
,09-02 15:27:19.810  7129  7732 D BluetoothMapMasInstance: MAS initSocket()
09-02 15:27:19.810  7129  7129 V BluetoothPbapReceiver: PbapReceiver onReceive 
,09-02 15:27:19.810  7129  7129 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-02 15:27:19.811  7129  7129 V BluetoothPbapReceiver: ***********state = 12
09-02 15:27:19.811  7129  7732 D BluetoothMapMasInstance:   masId = 00
09-02 15:27:19.811  7129  7732 D BluetoothMapMasInstance:   msgTypes = 0e
09-02 15:27:19.811  7129  7732 D BluetoothMapMasInstance:   masName = SMS/MMS
09-02 15:27:19.811  7129  7732 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
09-02 15:27:19.812  1043  1962 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 15:27:19.813  7129  7732 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-02 15:27:19.815  2160  2160 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-02 15:27:19.816  2160  2160 D c       : Getting all permits...
09-02 15:27:19.816  2160  2160 D a       : Opening database...
09-02 15:27:19.816  7129  7732 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
09-02 15:27:19.816  7129  7616 D BluetoothAdapterProperties: Scan Mode:21
09-02 15:27:19.817  7129  7616 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
09-02 15:27:19.817  7129  7732 V BluetoothMapMasInstance: Succeed to create listening socket 
09-02 15:27:19.817  7129  7732 D BluetoothMapMasInstance: Accepting socket connection...
09-02 15:27:19.817  7129  7733 V BluetoothPbapService: Pbap Service initSocket
09-02 15:27:19.819  6878  6878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 15:27:19.820  6878  6878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 15:27:19.820  1043  2014 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-02 15:27:19.821  7129  7733 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-02 15:27:19.822  7015  7015 D DockEventReceiver: finishStartingService: stopping service
09-02 15:27:19.823  7129  7733 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
09-02 15:27:19.823  7129  7733 V BluetoothPbapService: Succeed to create listening socket 
09-02 15:27:19.823  7129  7733 V BluetoothPbapService: Accepting socket connection...
09-02 15:27:19.823  2160  2160 D a       : Opening database auth.proximity.permit_store...
09-02 15:27:19.824  7015  7015 D BluetoothPbap: Proxy object connected
09-02 15:27:19.824  2160  2160 D a       : Closing database...
09-02 15:27:19.825  7015  7015 D PbapServerProfile: Bluetooth service connected
09-02 15:27:19.841  7015  7015 D BluetoothPermissionRequest: onReceive
,09-02 15:27:19.843  7015  7015 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
09-02 15:27:19.846  7015  7015 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-02 15:27:19.849  7129  7129 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
09-02 15:27:19.850  7129  7129 I LGBluetoothOppAdapter: [BTUI] startOppService()
09-02 15:27:19.856  7129  7129 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,09-02 15:27:19.877  7129  7129 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
09-02 15:27:19.877  7129  7129 V BtOppService: onCreate
,09-02 15:27:19.881  7129  7129 V BluetoothOppNotification: send message
09-02 15:27:19.885  7129  7129 V BtOppService: Starting RfcommListener
09-02 15:27:19.889  7129  7129 D BluetoothOppPreference: Dumping Names:  
09-02 15:27:19.889  7129  7129 D BluetoothOppPreference: {}
09-02 15:27:19.889  7129  7129 D BluetoothOppPreference: Dumping Channels:  
09-02 15:27:19.889  7129  7129 D BluetoothOppPreference: {}
09-02 15:27:19.890  7129  7129 V BtOppService: onStartCommand
,09-02 15:27:19.896  7129  7129 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-02 15:27:19.896  7129  7129 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
09-02 15:27:19.898  7129  7741 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-02 15:27:19.898  7370  7401 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
09-02 15:27:19.899  7129  7129 V BluetoothOppNotification: new notify threadi!
09-02 15:27:19.900  7129  7129 V BluetoothOppNotification: send delay message
09-02 15:27:19.901  7129  7129 V BtOppService: start RfcommListener
09-02 15:27:19.906  7129  7129 V BtOppService: RfcommListener started
,09-02 15:27:19.909  7129  7737 V BtOppService: Deleted complete outbound shares, number =  0
09-02 15:27:19.909  7129  7744 V BtOppRfcommListener: Starting RFCOMM listener....
09-02 15:27:19.910  1043  1891 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 15:27:19.911  7129  7744 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-02 15:27:19.912  7129  7744 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=78 mFd=75
09-02 15:27:19.912  7129  7744 V BtOppRfcommListener: Started RFCOMM listener....
09-02 15:27:19.912  7129  7744 I BtOppRfcommListener: Accept thread started.
09-02 15:27:19.912  7129  7744 V BtOppRfcommListener: Accepting connection...
09-02 15:27:19.912  7129  7737 V BtOppService: Deleted complete inbound failed shares, number = 0
09-02 15:27:19.914  7129  7737 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
09-02 15:27:19.916  7129  7741 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-02 15:27:19.916  7129  7743 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
09-02 15:27:19.916  7129  7737 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@ba1d401 on behalf of 
09-02 15:27:19.921  7129  7743 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3c45c2a6 on behalf of 
,09-02 15:27:19.921  7129  7743 V BluetoothOppNotification: mUpdateCompleteNotification = true
09-02 15:27:19.922  7129  7741 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1d66a4e7 on behalf of 
09-02 15:27:19.925  7129  7743 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
09-02 15:27:19.925  7129  7129 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@31099d6c
09-02 15:27:19.926  7129  7129 V BluetoothFtpService: Ftp Service onCreate
09-02 15:27:19.926  7129  7129 I BluetoothFtpService: Ftp Service onCreate
09-02 15:27:19.926  7129  7741 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
09-02 15:27:19.927  7129  7129 V BluetoothFtpService: Ftp Service onStartCommand
09-02 15:27:19.927  7129  7129 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-02 15:27:19.927  7129  7129 V BluetoothFtpService: Starting Listening on sockets
09-02 15:27:19.927  7129  7129 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-02 15:27:19.927  7129  7743 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@a56af3d on behalf of 
09-02 15:27:19.927  7129  7129 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-02 15:27:19.927  7129  7129 V BluetoothSapReceiver: SapReceiver onReceive 
09-02 15:27:19.928  7129  7129 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-02 15:27:19.928  7129  7129 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
09-02 15:27:19.928  7129  7129 V BluetoothSapReceiver: Calling SAP service start service with action = null
09-02 15:27:19.929  7129  7743 V BluetoothOppNotification: outbound: succ-0  fail-0
09-02 15:27:19.930  7129  7129 V BtOppService: ContentObserver received notification
09-02 15:27:19.930  7129  7129 V BtOppService: ContentObserver received notification
09-02 15:27:19.930  7129  7129 V BluetoothFtpService: Handler(): got msg=1
09-02 15:27:19.931  7129  7746 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-02 15:27:19.931  7129  7746 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-02 15:27:19.932  7129  7129 V BluetoothFtpService: Ftp Service startRfcommSocketListener
09-02 15:27:19.932  7129  7129 V BluetoothFtpService: Ftp Service initSocket
,09-02 15:27:19.933  7129  7743 V BluetoothOppNotification: outbound notification was removed.
,09-02 15:27:19.933  7129  7743 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
09-02 15:27:19.937  1043  2018 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 15:27:19.938  7129  7743 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@167b6332 on behalf of 
09-02 15:27:19.938  7129  7746 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@156ea883 on behalf of 
09-02 15:27:19.938  7129  7743 V BluetoothOppNotification: inbound: succ-0  fail-0
09-02 15:27:19.939  7129  7746 V BluetoothOppNotification: update too frequent, put in queue
09-02 15:27:19.940  7129  7129 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-02 15:27:19.940  7129  7746 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
09-02 15:27:19.941  7129  7743 V BluetoothOppNotification: inbound notification was removed.
09-02 15:27:19.941  7129  7129 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=78
09-02 15:27:19.941  7129  7743 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
09-02 15:27:19.941  7129  7129 V BluetoothFtpService: Succeed to create listening socket on channel 20
09-02 15:27:19.942  7129  7743 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2fc7da00 on behalf of 
09-02 15:27:19.943  7129  7747 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
09-02 15:27:19.959  7129  7129 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@31099d6c
09-02 15:27:19.959  7129  7129 V BluetoothSapService: Sap Service onCreate
,09-02 15:27:19.961  7129  7129 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-02 15:27:19.961  7129  7129 V BluetoothSapService: state: 12
09-02 15:27:19.961  7129  7129 V BluetoothSapService: Starting SAP server process
09-02 15:27:19.964  7129  7129 V BluetoothSapService: SAP Service startRfcommListenerThread
09-02 15:27:19.955  7748  7748 W sapd    : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-02 15:27:19.955  7748  7748 W sapd    : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-02 15:27:19.966  7129  7749 V BluetoothSapService: Sap Service initRfcommSocket
09-02 15:27:19.967  1043  1865 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 15:27:19.968  7129  7749 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-02 15:27:19.970  7129  7749 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
09-02 15:27:19.970  7129  7749 V BluetoothSapService: Succeed to create listening socket 
09-02 15:27:19.970  7129  7749 V BluetoothSapService: Accepting socket connection...
09-02 15:27:19.977  7748  7748 V BT_SAP  : Event pipe created
09-02 15:27:19.977  7748  7748 V BT_SAP  : create_server_socket qcom.sap.server
09-02 15:27:19.977  7748  7748 V BT_SAP  : created socket fd 6
,09-02 15:27:20.561  1043  1374 D LGWifiP2pService: P2pDisabledState{ when=-5ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,09-02 15:27:20.561  1043  1374 D LGWifiP2pService: DefaultState{ when=-5ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,09-02 15:27:20.626  1043  1377 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
,09-02 15:27:20.634  1043  1377 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
09-02 15:27:20.698  1043  1562 I ActivityManager: Killing 7537:com.lge.bnr/1000 (adj 15): empty #17
,09-02 15:27:20.729  1043  1060 W libprocessgroup: failed to open /acct/uid_1000/pid_7537/cgroup.procs: No such file or directory
,09-02 15:27:20.903  7129  7129 V BluetoothOppNotification: new notify threadi!
,09-02 15:27:20.904  7129  7129 V BluetoothOppNotification: send delay message
,09-02 15:27:20.915  7129  7759 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,09-02 15:27:20.919  7129  7759 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3d0962c on behalf of 
09-02 15:27:20.924  7129  7759 V BluetoothOppNotification: mUpdateCompleteNotification = true
,09-02 15:27:20.932  7129  7759 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
09-02 15:27:20.935  7129  7759 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3f9988f5 on behalf of 
09-02 15:27:20.940  7129  7759 V BluetoothOppNotification: outbound: succ-0  fail-0
,09-02 15:27:20.943  7129  7759 V BluetoothOppNotification: outbound notification was removed.
,09-02 15:27:20.943  7129  7759 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
09-02 15:27:20.945  7129  7759 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3e98268a on behalf of 
09-02 15:27:20.945  7129  7759 V BluetoothOppNotification: inbound: succ-0  fail-0
09-02 15:27:20.947  7129  7759 V BluetoothOppNotification: inbound notification was removed.
,09-02 15:27:20.947  7129  7759 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
09-02 15:27:20.948  7129  7759 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1b42a4fb on behalf of 
09-02 15:27:21.183  1043  1865 I ActivityManager: Killing 6777:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,09-02 15:27:21.218  7063  7063 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
09-02 15:27:21.219  7063  7063 W System.err: android.os.DeadObjectException
09-02 15:27:21.219  7063  7063 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
09-02 15:27:21.219  7063  7063 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
09-02 15:27:21.219  7063  7063 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
09-02 15:27:21.219  7063  7063 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
09-02 15:27:21.219  7063  7063 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
09-02 15:27:21.219  7063  7063 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
09-02 15:27:21.219  7063  7063 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-02 15:27:21.219  7063  7063 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-02 15:27:21.219  7063  7063 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-02 15:27:21.219  7063  7063 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-02 15:27:21.219  7063  7063 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 15:27:21.219  7063  7063 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-02 15:27:21.220  7063  7063 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-02 15:27:21.220  7063  7063 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-02 15:27:21.220  7063  7063 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
09-02 15:27:21.220  7063  7063 W System.err: android.os.DeadObjectException
09-02 15:27:21.220  7063  7063 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
09-02 15:27:21.220  7063  7063 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
09-02 15:27:21.220  7063  7063 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
09-02 15:27:21.220  7063  7063 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
09-02 15:27:21.220  7063  7063 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
09-02 15:27:21.221  7063  7063 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
09-02 15:27:21.221  7063  7063 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-02 15:27:21.221  7063  7063 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-02 15:27:21.221  7063  7063 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-02 15:27:21.221  7063  7063 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-02 15:27:21.221  7063  7063 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 15:27:21.221  7063  7063 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-02 15:27:21.221  7063  7063 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-02 15:27:21.221  7063  7063 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-02 15:27:21.221  7063  7063 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
09-02 15:27:21.221  7063  7063 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
,09-02 15:27:21.256  1043  1562 W libprocessgroup: failed to open /acct/uid_1000/pid_6777/cgroup.procs: No such file or directory
,09-02 15:27:21.258  1043  1562 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
09-02 15:27:21.263  7063  7063 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
09-02 15:27:21.263  7063  7063 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
09-02 15:27:21.306  1043  1059 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7760 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-02 15:27:21.347   341   341 I art     : Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 3.573ms total 37.090ms
,09-02 15:27:21.382   341   341 I art     : Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 407us total 31.571ms
,09-02 15:27:21.428  7063  7063 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,09-02 15:27:21.431   341   341 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 406us total 26.279ms
,09-02 15:27:21.475  7760  7760 D UEI.SmartControl: Quickset Services start...
,09-02 15:27:21.478  7760  7760 I UEI.SmartControl: Manufacture = LGE
09-02 15:27:21.478  7760  7760 D UEI.SmartControl: Id = LGNevo
09-02 15:27:21.479  7760  7760 D UEI.SmartControl: File observer start...
09-02 15:27:21.480  7760  7760 E UEI.SmartControl: IR Port is disabled: false
09-02 15:27:21.481  7760  7760 D UEI.SmartControl: Starting file observer...
09-02 15:27:21.481  7760  7760 D UEI.SmartControl: Extracting JNI libs...
09-02 15:27:21.481  7760  7760 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
09-02 15:27:21.578  1043  1059 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 15:27:21.578  1043  1059 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@bb30161 mBinding = false
,09-02 15:27:21.580  7760  7760 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
09-02 15:27:21.580  7760  7760 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
09-02 15:27:21.581  7760  7760 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
09-02 15:27:21.590  1043  1119 D BluetoothManagerService: Message: 2
09-02 15:27:21.592  1043  1043 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-02 15:27:21.592  1043  1043 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-02 15:27:21.592  1043  1119 D BluetoothManagerService: Sending off request.
09-02 15:27:21.592  1043  1043 D Ulp_jni : JNI:system_update. Event-4
09-02 15:27:21.595  7129  7730 D LGBluetoothServiceAdapter: [BTUI] Precleanup
09-02 15:27:21.596  7129  7612 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
09-02 15:27:21.597  7129  7612 D BluetoothAdapterProperties: Setting state to 13
09-02 15:27:21.597  7129  7612 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,09-02 15:27:21.598  7129  7612 D BluetoothAdapterProperties: onBluetoothDisable()
09-02 15:27:21.598  7129  7612 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
09-02 15:27:21.601  7129  7616 D BluetoothAdapterProperties: Scan Mode:20
09-02 15:27:21.602  7129  7612 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
09-02 15:27:21.604  7129  7733 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-02 15:27:21.604  7129  7612 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-02 15:27:21.605  6878  6878 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 15:27:21.605  6878  6878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 15:27:21.605  6878  6878 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 15:27:21.605  6878  6878 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 15:27:21.605  6878  6878 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 15:27:21.605  6878  6878 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 15:27:21.605  6878  6878 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 15:27:21.605  6878  6878 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 15:27:21.605  6878  6878 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-02 15:27:21.605  7129  7744 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-02 15:27:21.605  7129  7749 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-02 15:27:21.606  6878  6878 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-02 15:27:21.606  6878  6878 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-02 15:27:21.606  7129  7682 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
09-02 15:27:21.607  7129  7747 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-02 15:27:21.607  7129  7682 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
09-02 15:27:21.608  7129  7732 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
09-02 15:27:21.608  7129  7732 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-02 15:27:21.608  7129  7732 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
09-02 15:27:21.608  7129  7732 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
09-02 15:27:21.608  7129  7732 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
09-02 15:27:21.608  7129  7732 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
09-02 15:27:21.608  7129  7732 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
09-02 15:27:21.608  7129  7732 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
09-02 15:27:21.608  6878  6878 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 15:27:21.608  6878  6878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 15:27:21.608  6878  6878 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 15:27:21.608  6878  6878 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 15:27:21.608  6878  6878 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 15:27:21.608  6878  6878 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 15:27:21.608  6878  6878 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 15:27:21.608  6878  6878 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 15:27:21.608  6878  6878 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-02 15:27:21.608  6878  6878 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 15:27:21.608  6878  6878 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-02 15:27:21.610  7129  7682 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-02 15:27:21.610  7129  7682 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-02 15:27:21.611  7129  7682 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-02 15:27:21.611  7129  7682 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-02 15:27:21.611  7129  7682 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-02 15:27:21.611  7129  7682 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-02 15:27:21.611  7129  7682 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-02 15:27:21.611  7129  7682 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
,09-02 15:27:21.611  7129  7682 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-02 15:27:21.611  7129  7682 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
09-02 15:27:21.611  7129  7682 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013,
09-02 15:27:21.611  7129  7682 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-02 15:27:21.648  1043  1119 D BluetoothManagerService: Message: 60
09-02 15:27:21.648  1043  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
,09-02 15:27:21.648  1043  1119 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
09-02 15:27:21.652  7129  7129 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-02 15:27:21.653  7129  7129 D BluetoothMapService: STATE_TURNING_OFF
,09-02 15:27:21.653  7129  7129 V BluetoothMapService: Handler(): got msg=4
09-02 15:27:21.653  7129  7129 D BluetoothMapService: MAP Service closeService in
09-02 15:27:21.653  7129  7129 D BluetoothMapMasInstance: MAP Service shutdown
,09-02 15:27:21.653  7129  7129 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-02 15:27:21.653  7129  7129 V BluetoothMapService: MAP Service closeService out
09-02 15:27:21.654  1928  1928 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-02 15:27:21.654  1589  1589 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,09-02 15:27:21.659  6878  6878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 15:27:21.660  7015  7015 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
09-02 15:27:21.660  7760  7760 I UEI.SmartControl: --- Selecting new region: 6
09-02 15:27:21.661  7129  7129 V BtOppService: Receiver DISABLED_ACTION 
09-02 15:27:21.661  7129  7129 I BtOppRfcommListener: stopping Accept Thread
09-02 15:27:21.661  7129  7129 V BtOppRfcommListener: close mBtServerSocket
09-02 15:27:21.662  7129  7129 V BtOppRfcommListener: waiting for thread to terminate
09-02 15:27:21.662  7129  7744 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-02 15:27:21.662  7760  7760 I UEI.SmartControl: Model = LG-D855
09-02 15:27:21.662  7129  7129 V BtOppRfcommListener: done waiting for thread to terminate
09-02 15:27:21.663  6878  6878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 15:27:21.664  7129  7129 V BtOppService: onDestroy
09-02 15:27:21.665  7015  7015 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-02 15:27:21.665  7129  7129 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
,09-02 15:27:21.667  7760  7760 D UEI.SmartControl: QS Service created
09-02 15:27:21.672  7015  7015 D DockEventReceiver: finishStartingService: stopping service
09-02 15:27:21.673  7129  7129 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-02 15:27:21.673  7129  7129 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-02 15:27:21.673  7129  7129 V BluetoothPbapReceiver: ***********state = 13
09-02 15:27:21.674  7129  7129 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
09-02 15:27:21.678  7129  7129 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-02 15:27:21.678  7129  7129 V BluetoothPbapService: state: 13
09-02 15:27:21.678  7129  7129 V BluetoothPbapService: Pbap Service closeService in
,09-02 15:27:21.680  7129  7129 V BluetoothPbapService: successfully stopped pbap service
09-02 15:27:21.680  7129  7129 V BluetoothPbapService: Pbap Service closeService out
09-02 15:27:21.680  7015  7015 D BluetoothPbap: Proxy object disconnected
09-02 15:27:21.680  7015  7015 D PbapServerProfile: Bluetooth service disconnected
09-02 15:27:21.681  7129  7129 V BluetoothPbapService: Pbap Service onDestroy
09-02 15:27:21.681  7129  7129 V BluetoothPbapService: Pbap Service closeService in
09-02 15:27:21.681  7129  7129 V BluetoothPbapService: Pbap Service closeService out
09-02 15:27:21.681  7129  7129 D LGBluetoothPbapAdapter: [BTUI] cleanup
09-02 15:27:21.682  2160  2160 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-02 15:27:21.691  7015  7015 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,09-02 15:27:21.695  7015  7015 D BluetoothPermissionRequest: onReceive
09-02 15:27:21.695  7015  7015 D LGBluetoothAuthorization: [BTUI] cancel All Notification
09-02 15:27:21.701  7015  7015 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-02 15:27:21.704  7129  7129 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
09-02 15:27:21.704  7129  7129 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
09-02 15:27:21.705  7129  7129 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
,09-02 15:27:21.707  7760  7760 I UEI.SmartControl: Service initServices...
09-02 15:27:21.709  7129  7129 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-02 15:27:21.709  7129  7129 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
09-02 15:27:21.710  7129  7129 V BluetoothFtpService: Ftp Service onStartCommand
09-02 15:27:21.710  7129  7129 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-02 15:27:21.710  7129  7129 V BluetoothFtpService: Ftp Service closeService
09-02 15:27:21.710  7129  7129 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
09-02 15:27:21.712  7129  7129 V BluetoothFtpService: successfully stopped ftp service
09-02 15:27:21.712  7129  7129 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-02 15:27:21.712  7129  7129 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-02 15:27:21.712  7129  7129 V BluetoothSapReceiver: SapReceiver onReceive 
09-02 15:27:21.712  7129  7129 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-02 15:27:21.712  7129  7129 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
09-02 15:27:21.712  7129  7129 V BluetoothSapReceiver: Calling SAP service start service with action = null
09-02 15:27:21.712  7760  7760 D UEI.SmartControl: QS start get config
09-02 15:27:21.713  7129  7129 V BluetoothFtpService: Ftp Service onDestroy
09-02 15:27:21.713  7129  7129 V BluetoothFtpService: Ftp Service closeService
09-02 15:27:21.716  7129  7129 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-02 15:27:21.716  7129  7129 V BluetoothSapService: state: 13
09-02 15:27:21.716  7129  7129 V BluetoothSapService: Stopping SAP server process
09-02 15:27:21.717  7129  7129 V BluetoothSapService: Sap Service closeSapService in
09-02 15:27:21.717  7129  7129 V BluetoothSapService: Close listen Socket : 
09-02 15:27:21.717  7129  7129 V BluetoothSapService: Close rfcomm Socket : 
09-02 15:27:21.717  7129  7129 V BluetoothSapService: Close sapd  Socket : 
,09-02 15:27:21.719  7129  7129 V BluetoothSapService: Sap Service closeSapService out
09-02 15:27:21.719  7129  7129 V BluetoothSapService: Sap Service onDestroy
09-02 15:27:21.719  7129  7129 V BluetoothSapService: Sap Service closeSapService in
09-02 15:27:21.719  7129  7129 V BluetoothSapService: Close listen Socket : 
09-02 15:27:21.719  7129  7129 V BluetoothSapService: Close rfcomm Socket : 
09-02 15:27:21.719  7129  7129 V BluetoothSapService: Close sapd  Socket : 
09-02 15:27:21.722  7129  7129 V BluetoothSapService: Sap Service closeSapService out
09-02 15:27:21.791  7760  7760 D UEI.SmartControl: Loading JNI Libs...
,09-02 15:27:22.043  7760  7760 I UEI.SmartControl: Supports setup maps: true
,09-02 15:27:22.047  7760  7760 D UEI.SmartControl: QS start statue = true Error code = 0
,09-02 15:27:22.047  7760  7760 I UEI.SmartControl: QS version = v2.7.10.1_RC1
09-02 15:27:22.047  7760  7760 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
09-02 15:27:22.047  7760  7760 I UEI.SmartControl: ### init IR Blaster...
09-02 15:27:22.051  7760  7760 D serial_port: Configuring serial port
09-02 15:27:22.055  7760  7760 E UEI.SmartControl: UEIBLaster setting for 616
09-02 15:27:22.055  7760  7760 I UEI.SmartControl: Setting serial record hearder size = 2
09-02 15:27:22.056  7760  7760 I UEI.SmartControl: configuring settings for MAXQ616
09-02 15:27:22.056  7760  7760 I UEI.SmartControl: Get version...
09-02 15:27:22.073  7760  7804 D UEI.SmartControl: serial port data available: 21
,09-02 15:27:22.101  7760  7760 D UEI.SmartControl: MAXQ616 A2-X4 software.
09-02 15:27:22.101  7760  7760 I UEI.SmartControl: IR Blaster version: 256702256704300002
09-02 15:27:22.101  7760  7760 I UEI.SmartControl: QS saving settings...
09-02 15:27:22.102  7760  7760 D UEI.SmartControl: IR Blaster version: 25672567
,09-02 15:27:22.118  7760  7804 D UEI.SmartControl: serial port data available: 4
,09-02 15:27:22.154  7760  7807 I UEI.SmartControl: Device manager: loading config....
,09-02 15:27:22.155  7760  7807 D UEI.SmartControl: ----------- loading internal config...
,09-02 15:27:22.163  7760  7760 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,09-02 15:27:22.168  7760  7760 E UEI.SmartControl: Services init done
09-02 15:27:22.168  7760  7760 D UEI.SmartControl: QS Service init finished
09-02 15:27:22.170  7760  7760 D UEI.SmartControl: QS Service version name: 2.1.91
09-02 15:27:22.170  7760  7760 D UEI.SmartControl: QS Service version code: 201091
09-02 15:27:22.171  7760  7760 D UEI.SmartControl: Service requested: Control
09-02 15:27:22.176  7760  7760 D UEI.SmartControl: Request IControl service: devices are loaded...
09-02 15:27:22.177  7760  7807 E UEI.SmartControl: Loading SETTINGS...
,09-02 15:27:22.182  7063  7063 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
09-02 15:27:22.182  1043  2037 I ActivityManager: Killing 7063:com.lge.qremote/u0a112 (adj 15): empty #17
09-02 15:27:22.183  7760  7775 I UEI.SmartControl: ------ IControl API: 11
09-02 15:27:22.184  7760  7775 I UEI.SmartControl: Registering callback...
09-02 15:27:22.190  7760  7807 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
09-02 15:27:22.211  1043  1962 W libprocessgroup: failed to open /acct/uid_10112/pid_7063/cgroup.procs: No such file or directory
,09-02 15:27:22.213  7760  7760 D UEI.SmartControl: Internal service binding...
,09-02 15:27:22.213  7760  7806 I UEI.SmartControl: Notify AllClients services are ready: 0
09-02 15:27:22.213  7760  7806 D UEI.SmartControl: -----service ready thread exits
09-02 15:27:22.557  7129  7616 D bt_hci_bdroid: cleanup
,09-02 15:27:22.565  7129  7684 I bt_lpm  : LPM is already off!!!
09-02 15:27:22.566  7129  7711 I bt_userial_mct: exiting userial_read_thread
09-02 15:27:22.566  7129  7711 D bt_userial_mct: Leaving userial_evt_read_thread()
09-02 15:27:22.570  7129  7682 W bt-btif : ag scb idx 1 not allocated
09-02 15:27:22.570  7129  7682 E bt-btif : BTA AG is already disabled, ignoring ...
09-02 15:27:22.570  7129  7682 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-02 15:27:22.570  7129  7682 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-02 15:27:22.570  7129  7682 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-02 15:27:22.570  7129  7682 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-02 15:27:22.570  7129  7682 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-02 15:27:22.570  7129  7682 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-02 15:27:22.570  7129  7682 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-02 15:27:22.570  7129  7682 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-02 15:27:22.570  7129  7682 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-02 15:27:22.570  7129  7682 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-02 15:27:22.571  7129  7682 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-02 15:27:22.571  7129  7682 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-02 15:27:22.571  7129  7682 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-02 15:27:22.571  7129  7682 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-02 15:27:22.571  7129  7682 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-02 15:27:22.571  7129  7682 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-02 15:27:22.571  7129  7682 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-02 15:27:22.571  7129  7682 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-02 15:27:22.571  7129  7682 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-02 15:27:22.573  7129  7616 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
09-02 15:27:22.575  7129  7684 I bt_vendor: hw_epilog_process
,09-02 15:27:22.582  7129  7616 D bt_hci_bdroid: cleanup Finalizing cleanup
09-02 15:27:22.582  7129  7616 D bt_userial_mct: userial_close
09-02 15:27:22.582  7129  7616 E bt_userial_mct: pthread_join() FAILED result:3
09-02 15:27:22.582  7129  7616 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
09-02 15:27:22.588  7129  7616 D bt_hci_bdroid: set_power 0
09-02 15:27:22.588  7129  7616 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
09-02 15:27:22.588  7129  7616 I bt_vendor: bluetooth satus is on
09-02 15:27:22.588  7129  7616 I bt_vendor: bt-vendor : resetting BT status
09-02 15:27:22.588  7129  7616 I bt_vendor: Starting hciattach daemon
09-02 15:27:22.588  7129  7616 I bt_vendor: try to set false
,09-02 15:27:22.593  7129  7616 I bt_vendor: Starting hciattach daemon
09-02 15:27:22.593  7129  7616 I bt_vendor: try to set false
09-02 15:27:22.594  7129  7616 I bt_vendor: cleanup
09-02 15:27:22.594  7129  7682 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
09-02 15:27:22.595  7129  7616 I GKI_LINUX: GKI_exit_task 0 done
09-02 15:27:22.595  7129  7616 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
09-02 15:27:22.597  7129  7612 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
09-02 15:27:22.601  7129  7129 D HeadsetService: Received stop request...Stopping profile...
,09-02 15:27:22.608  7129  7129 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-02 15:27:22.608  7129  7129 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-02 15:27:22.608  7129  7129 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@31099d6c
09-02 15:27:22.609  7129  7650 D HeadsetStateMachine: Exit Disconnected: -1
09-02 15:27:22.613  1836  1836 D BluetoothHeadset: Proxy object disconnected
09-02 15:27:22.613  1836  1836 D BluetoothHeadset: Proxy object disconnected
09-02 15:27:22.614  1836  1836 D BluetoothHeadset: Proxy object disconnected
09-02 15:27:22.615  1043  1043 D BluetoothHeadset: Proxy object disconnected
09-02 15:27:22.615  1043  1043 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,09-02 15:27:22.619  7129  7612 D BluetoothAdapterState: Stopping profile services that were post enabled
09-02 15:27:22.620  7129  7129 D A2dpService: Received stop request...Stopping profile...
09-02 15:27:22.620  7129  7667 D A2dpStateMachine: Exit Disconnected: -1
09-02 15:27:22.622  7129  7129 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
09-02 15:27:22.623  7129  7129 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
09-02 15:27:22.623  7129  7129 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
09-02 15:27:22.623  7129  7129 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@31099d6c
09-02 15:27:22.625  1043  1043 D BluetoothA2dp: Proxy object disconnected
09-02 15:27:22.625  1043  1043 D AudioService: onServiceDisconnected: Bluetooth profile: 2
09-02 15:27:22.626  7129  7129 D HidService: Received stop request...Stopping profile...
09-02 15:27:22.626  7129  7129 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@31099d6c
09-02 15:27:22.630  7129  7129 D HealthService: Received stop request...Stopping profile...
09-02 15:27:22.630  7129  7129 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@31099d6c
,09-02 15:27:22.635  7129  7129 D PanService: Received stop request...Stopping profile...
09-02 15:27:22.635  7129  7129 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@31099d6c
09-02 15:27:22.636  7129  7129 D BtGatt.DebugUtils: handleDebugAction() action=null
09-02 15:27:22.638  7129  7129 D BtGatt.GattService: Received stop request...Stopping profile...
09-02 15:27:22.638  7129  7129 D BtGatt.GattService: stop()
09-02 15:27:22.638  7129  7129 D BtGatt.AdvertiseManager: advertise clients cleared
09-02 15:27:22.640  7129  7129 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@31099d6c
09-02 15:27:22.641  7129  7129 D HeadsetStateMachine: Unbinding service...
09-02 15:27:22.642  7129  7129 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-02 15:27:22.642  7129  7129 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-02 15:27:22.642  7129  7129 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-02 15:27:22.642  7129  7129 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-02 15:27:22.643  7129  7129 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-02 15:27:22.643  7129  7129 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-02 15:27:22.643  7129  7129 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
,09-02 15:27:22.647  7129  7129 D BluetoothMapService: Received stop request...Stopping profile...
09-02 15:27:22.647  7129  7129 D BluetoothMapService: stop()
09-02 15:27:22.648  7129  7129 D BluetoothMapEmailAppObserver: deinitObservers()
09-02 15:27:22.648  7129  7129 D BluetoothMapEmailAppObserver: removeReceiver()
09-02 15:27:22.648  7129  7129 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@31099d6c
09-02 15:27:22.649  7129  7129 I BluetoothA2dpServiceJni: cleanupNative
09-02 15:27:22.651  7129  7668 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
09-02 15:27:22.651  7129  7129 I GKI_LINUX: GKI_exit_task 2 done
09-02 15:27:22.651  7129  7129 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
09-02 15:27:22.652  7129  7129 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-02 15:27:22.652  7129  7129 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-02 15:27:22.652  7129  7129 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-02 15:27:22.652  7129  7129 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-02 15:27:22.653  7129  7129 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-02 15:27:22.653  7129  7129 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-02 15:27:22.653  7129  7129 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-02 15:27:22.658  7129  7129 V BluetoothMapService: Handler(): got msg=4
09-02 15:27:22.658  7129  7129 D BluetoothMapService: MAP Service closeService in
09-02 15:27:22.658  7129  7129 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-02 15:27:22.658  7129  7129 V BluetoothMapService: MAP Service closeService out
,09-02 15:27:22.661  7129  7612 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
09-02 15:27:22.663  7129  7612 D BluetoothAdapterProperties: Setting state to 10
09-02 15:27:22.663  7129  7612 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
09-02 15:27:22.664  7129  7129 D BluetoothMapService: cleanup()
09-02 15:27:22.664  7129  7129 D BluetoothMapService: MAP Service closeService in
09-02 15:27:22.664  7129  7129 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-02 15:27:22.664  7129  7129 V BluetoothMapService: MAP Service closeService out
09-02 15:27:22.665  1043  1119 D BluetoothManagerService: Message: 60
09-02 15:27:22.665  1043  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
09-02 15:27:22.665  1043  1119 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
09-02 15:27:22.665  7129  7612 I BluetoothAdapterState: Entering OffState
09-02 15:27:22.666  7015  7030 D BluetoothHeadset: onBluetoothStateChange: up=false
09-02 15:27:22.666  1043  1119 D BluetoothA2dp: onBluetoothStateChange: up=false
09-02 15:27:22.667  7015  7030 D BluetoothPan: onBluetoothStateChange on: false
09-02 15:27:22.668  7015  7030 D BluetoothA2dp: onBluetoothStateChange: up=false
09-02 15:27:22.668  1043  1119 D BluetoothHeadset: onBluetoothStateChange: up=false
09-02 15:27:22.669  1836  2685 D BluetoothHeadset: onBluetoothStateChange: up=false
09-02 15:27:22.669  7015  7030 D BluetoothPbap: onBluetoothStateChange: up=false
09-02 15:27:22.670  1836  1851 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-02 15:27:22.673  7015  7030 D BluetoothMap: onBluetoothStateChange: up=false
09-02 15:27:22.674  1836  3496 D BluetoothHeadset: onBluetoothStateChange: up=false
09-02 15:27:22.675  7015  7030 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-02 15:27:22.676  1043  1119 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
09-02 15:27:22.676  1043  1119 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
09-02 15:27:22.678  1043  1119 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
09-02 15:27:22.678  1043  1119 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
09-02 15:27:22.678  1043  1119 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@bb30161 mBinding = false
09-02 15:27:22.679  1043  1119 D BluetoothManagerService: Sending unbind request.
09-02 15:27:22.683  7129  7616 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,09-02 15:27:22.686  7129  7129 I GKI_LINUX: GKI_exit_task 1 done
09-02 15:27:22.686  7129  7129 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
09-02 15:27:22.686  7129  7129 I BluetoothServiceJni: cleanupNative: return from cleanup
09-02 15:27:22.687  7129  7129 I art     : --- WEIRD: removing null entry 248
09-02 15:27:22.687  7129  7129 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
09-02 15:27:22.687  7129  7129 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
09-02 15:27:22.688  7129  7129 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
09-02 15:27:22.689  1043  1119 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
09-02 15:27:22.691  7129  7129 I art     : System.exit called, status: 0
09-02 15:27:22.691  7129  7129 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
09-02 15:27:22.711   308  1383 V AudioFlinger: 7129 died, releasing its sessions
09-02 15:27:22.712   308  1383 V AudioFlinger:  pid 1836 @ 0
09-02 15:27:22.712   308  1383 V AudioFlinger:  pid 3395 @ 1
09-02 15:27:22.712   308  1383 V AudioFlinger:  pid 3395 @ 2
,09-02 15:27:22.715  1928  1928 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: disconnected from LGBluetoothAPIAdapter
09-02 15:27:22.716  1928  2066 D LGBluetoothAPIService: Message: 101
09-02 15:27:22.716  1928  2066 E LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED
09-02 15:27:22.716  1928  2066 D LGBluetoothAPIService: Calling onBluetoothServiceDown callbacks
09-02 15:27:22.716  1928  2066 D LGBluetoothAPIService: Broadcasting onBluetoothServiceDown() to 0 receivers.
09-02 15:27:22.719  7015  7015 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
09-02 15:27:22.726  1043  1962 I ActivityManager: Process com.android.bluetooth (pid 7129) has died
09-02 15:27:22.727  1043  1962 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer in 1000ms
09-02 15:27:22.727  1043  1962 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 11000ms
,09-02 15:27:22.736  1928  1928 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-02 15:27:22.736  1928  2066 D LGBluetoothAPIService: Message: 2
09-02 15:27:22.737  1928  2066 D LGBluetoothAPIService: unbindAndFinish(): null mBinding = false
09-02 15:27:22.737  6878  6878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 15:27:22.738  6878  6878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 15:27:22.738  1589  1589 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-02 15:27:22.745  7015  7015 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
09-02 15:27:22.745  7015  7015 D LGBluetoothEventManager: [BTUI] clear device connection state
,09-02 15:27:22.750  7015  7015 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-02 15:27:22.771  1589  1589 D BluetoothAdapter: 644570902: getState() :  mService = null. Returning STATE_OFF
09-02 15:27:22.771  1589  1589 D BluetoothAdapter: 644570902: getState() :  mService = null. Returning STATE_OFF
,09-02 15:27:22.817  1043  1722 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=7830 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
09-02 15:27:22.819  7015  7015 D DockEventReceiver: finishStartingService: stopping service
,09-02 15:27:22.872  7830  7830 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,09-02 15:27:22.873  7830  7830 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-02 15:27:22.873  7830  7830 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
09-02 15:27:22.874  7830  7830 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
09-02 15:27:22.893  7830  7830 D BluetoothAdapterApp: Loading JNI Library
,09-02 15:27:22.929  7830  7830 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@221127d4 Instance Count = 1
,09-02 15:27:22.935  7830  7830 D BluetoothAdapterApp: onCreate
,09-02 15:27:22.962  7830  7830 D ProfileConfigQcom: [BTUI] HeadsetService is supported
09-02 15:27:22.962  7830  7830 D ProfileConfigQcom: Adding HeadsetService
09-02 15:27:22.963  7830  7830 D ProfileConfigQcom: [BTUI] A2dpService is supported
09-02 15:27:22.963  7830  7830 D ProfileConfigQcom: Adding A2dpService
09-02 15:27:22.964  7830  7830 D ProfileConfigQcom: [BTUI] HidService is supported
09-02 15:27:22.964  7830  7830 D ProfileConfigQcom: Adding HidService
09-02 15:27:22.965  7830  7830 D ProfileConfigQcom: [BTUI] HealthService is supported
09-02 15:27:22.966  7830  7830 D ProfileConfigQcom: Adding HealthService
09-02 15:27:22.967  7830  7830 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
,09-02 15:27:22.972  7830  7830 D ProfileConfigQcom: [BTUI] PanService is supported
09-02 15:27:22.972  7830  7830 D ProfileConfigQcom: Adding PanService
09-02 15:27:22.973  7830  7830 D ProfileConfigQcom: [BTUI] GattService is supported
09-02 15:27:22.974  7830  7830 D ProfileConfigQcom: Adding GattService
09-02 15:27:22.975  7830  7830 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
09-02 15:27:22.975  7830  7830 D ProfileConfigQcom: Adding BluetoothMapService
,09-02 15:27:22.976  7830  7830 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
09-02 15:27:22.978  7830  7830 V BluetoothPbapReceiver: PbapReceiver onReceive 
,09-02 15:27:22.981  7830  7830 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-02 15:27:22.982  7830  7830 V BluetoothPbapReceiver: ***********state = 10
,09-02 15:27:22.986  7830  7830 V LGMDMManagerInternal: Create singleton instance
09-02 15:27:23.090  2160  2160 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-02 15:27:23.091  7830  7830 D LGBluetoothAPIServer: [BTUI] onCreate()
09-02 15:27:23.092  7830  7830 D LGBluetoothAPIServer: [BTUI] onBind()
09-02 15:27:23.097  1928  1928 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
09-02 15:27:23.099  1928  2066 D LGBluetoothAPIService: Message: 100
09-02 15:27:23.099  1928  2066 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
09-02 15:27:23.106  7015  7015 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
,09-02 15:27:23.121  7015  7015 D BluetoothPermissionRequest: onReceive
,09-02 15:27:23.123  7015  7015 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
09-02 15:27:23.123  7015  7015 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
09-02 15:27:23.126  7015  7015 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-02 15:27:23.131  7830  7830 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
09-02 15:27:23.136  7830  7830 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,09-02 15:27:23.142  7830  7830 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-02 15:27:23.143  7830  7830 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-02 15:27:23.143  7830  7830 V BluetoothSapReceiver: SapReceiver onReceive 
09-02 15:27:23.145  7830  7830 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-02 15:27:23.145  7830  7830 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
09-02 15:27:23.148  7080  7080 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
09-02 15:27:24.593  6878  6948 D io.jxcore.node.ConnectivityMonitor: stop
,09-02 15:27:24.596  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:27:24.695  1589  1589 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,09-02 15:27:24.712  1043  1364 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-02 15:27:24.780   341   341 I art     : Background concurrent mark sweep GC freed 788(33KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 10.742ms total 41.338ms
,09-02 15:27:24.807  1043  1115 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7860 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,09-02 15:27:24.814  1589  1589 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
09-02 15:27:24.815  1589  1589 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
09-02 15:27:24.839  2019  2019 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,09-02 15:27:24.853  1043  1043 D administrator: Handling package changes for user 0
,09-02 15:27:24.871  2019  2019 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,09-02 15:27:24.897  7860  7860 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,09-02 15:27:24.970  1043  1043 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
,09-02 15:27:24.970  1043  1043 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
09-02 15:27:24.971  7860  7860 D LgDataFeature: LgDataFeature() Constructor: none
09-02 15:27:24.971  7860  7860 D LgDataFeature: LgDataFeature() Constructor Done, null
09-02 15:27:25.040  1043  1114 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-02 15:27:25.048  1043  1114 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
09-02 15:27:25.056  2019  2019 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,09-02 15:27:25.058  2469  2469 V GmsNetworkLocationProvi: DISABLE
,09-02 15:27:25.077  7860  7904 I Babel   : MmsConfig: mnc/mcc: 0/0
09-02 15:27:25.078  7860  7904 I Babel   : MmsConfig.loadMmsSettings
09-02 15:27:25.083  7860  7904 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
09-02 15:27:25.083  7860  7904 I Babel   : MmsConfig.loadFromDatabase
,09-02 15:27:25.097  1043  1114 D LocationProviderProxy: applying state to connected service
09-02 15:27:25.099  7860  7860 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 15:27:25.099  2469  2469 E GCoreFlp: Bound FusedProviderService with LocationManager
,09-02 15:27:25.117  7860  7904 E Babel   : canonicalizeMccMnc: invalid mccmnc 
09-02 15:27:25.117  7860  7904 I Babel   : MmsConfig.loadFromResources
09-02 15:27:25.123  7860  7904 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
09-02 15:27:25.125  7860  7904 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
09-02 15:27:25.125  1801  7907 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
09-02 15:27:25.125  1801  7907 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
,09-02 15:27:25.128  7197  7197 I AppUp4:CustModeStarterReceiver: onReceive
09-02 15:27:25.132  7197  7197 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2f87e5be
09-02 15:27:25.133  7197  7197 D AppUp4:CustFacade: isCustomizationCompleted : false
09-02 15:27:25.133  7197  7197 D AppUp4:CustFacade: isPhone : true
09-02 15:27:25.133  7197  7197 D AppUp4:CustModeStarterReceiver: begin check event
09-02 15:27:25.133  7197  7197 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
09-02 15:27:25.134  1801  5159 I Icing   : updateResources: need to parse e{com.google.android.gms}
09-02 15:27:25.147  7860  7903 W AudioCapabilities: Unsupported mime audio/evrc
09-02 15:27:25.148  7860  7903 W AudioCapabilities: Unsupported mime audio/qcelp
09-02 15:27:25.149  7860  7903 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-02 15:27:25.161  7860  7903 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
,09-02 15:27:25.163  7860  7903 W AudioCapabilities: Unsupported mime audio/qcelp
09-02 15:27:25.164  7860  7903 W AudioCapabilities: Unsupported mime audio/evrc
09-02 15:27:25.169  1043  1059 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7911 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
09-02 15:27:25.173  1043  2018 I ActivityManager: Killing 7035:com.lge.sync/1000 (adj 15): empty #17
,09-02 15:27:25.184  1043  1429 D WifiService: Client connection lost with reason: 4
09-02 15:27:25.185  7860  7903 W VideoCapabilities: Unsupported mime video/x-ms-wmv
09-02 15:27:25.186  7860  7903 W VideoCapabilities: Unsupported mime video/divx
,09-02 15:27:25.188  7860  7903 W VideoCapabilities: Unsupported mime video/divx311
09-02 15:27:25.190  7860  7903 W VideoCapabilities: Unsupported mime video/divx4
09-02 15:27:25.194  7860  7903 W VideoCapabilities: Unsupported mime video/mp4v-esdp
09-02 15:27:25.208  7860  7903 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,09-02 15:27:25.211  7860  7903 W AudioCapabilities: Unsupported mime audio/eac3
09-02 15:27:25.212  7860  7903 W AudioCapabilities: Unsupported mime audio/ac3
09-02 15:27:25.213  7860  7903 W AudioCapabilities: Unsupported mime audio/g726
09-02 15:27:25.214  7860  7903 W AudioCapabilities: Unsupported mime audio/wma-voice
09-02 15:27:25.214  7860  7903 W AudioCapabilities: Unsupported mime audio/x-ms-wma
09-02 15:27:25.215  7860  7903 W AudioCapabilities: Unsupported mime audio/adpcm
09-02 15:27:25.217  7860  7903 W VideoCapabilities: Unsupported mime video/theora
09-02 15:27:25.218  7860  7903 W VideoCapabilities: Unsupported mime video/mjpg
09-02 15:27:25.279  1043  1722 W libprocessgroup: failed to open /acct/uid_1000/pid_7035/cgroup.procs: No such file or directory
,09-02 15:27:25.321  7911  7911 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-02 15:27:25.322  7911  7911 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-02 15:27:25.322  7911  7911 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
09-02 15:27:25.324  7911  7911 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
09-02 15:27:25.325  7911  7911 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,09-02 15:27:25.431  7911  7911 I SystemConfig: BUILD Country: EU
09-02 15:27:25.431  7911  7911 I SystemConfig: BUILD Operator: OPEN
,09-02 15:27:25.487  1043  1060 I ActivityManager: Killing 7229:com.lge.email/u0a23 (adj 15): empty #17
,09-02 15:27:25.591  1043  1771 W libprocessgroup: failed to open /acct/uid_10023/pid_7229/cgroup.procs: No such file or directory
,09-02 15:27:25.647  1043  1060 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7934 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,09-02 15:27:25.653  7911  7929 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
09-02 15:27:25.653  7911  7929 I SystemConfig: existFile = false
09-02 15:27:25.653  7911  7929 I SystemConfig: canReadFile = false
09-02 15:27:25.655  7911  7929 I SystemConfig: systemFeature RCS result false
09-02 15:27:25.655  7911  7929 D SystemConfig: refreshRcsSupport() :false
,09-02 15:27:25.697  7934  7934 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-02 15:27:25.697  7934  7934 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-02 15:27:25.698  7934  7934 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
09-02 15:27:25.698  7934  7934 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-02 15:27:25.808  7934  7934 I AppConfig: Total System Memory = 2995761152
,09-02 15:27:25.823  7934  7934 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
09-02 15:27:25.924  1043  1873 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7953 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-02 15:27:25.928  1043  1873 I ActivityManager: Killing 7105:com.lge.formmanager/u0a26 (adj 15): empty #17
,09-02 15:27:25.977  1043  1927 W libprocessgroup: failed to open /acct/uid_10026/pid_7105/cgroup.procs: No such file or directory
,09-02 15:27:26.226  7953  7953 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,09-02 15:27:26.299  7953  7953 D LgDataFeature: LgDataFeature() Constructor: none
,09-02 15:27:26.299  7953  7953 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-02 15:27:26.340  7953  7953 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,09-02 15:27:26.358  7953  7953 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,09-02 15:27:26.359  7953  7953 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.,
09-02 15:27:26.373  7953  7953 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-02 15:27:26.373  7953  7953 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,09-02 15:27:26.402  1043  1722 I ActivityManager: Killing 6433:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,09-02 15:27:26.431  1043  2018 W libprocessgroup: failed to open /acct/uid_1000/pid_6433/cgroup.procs: No such file or directory
,09-02 15:27:26.438  3474  4179 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
09-02 15:27:26.439  5009  7993 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
09-02 15:27:26.457  3474  4179 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@baf7493 on behalf of 7953
,09-02 15:27:26.479  1043  1865 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7994 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,09-02 15:27:26.528  7953  7953 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,09-02 15:27:26.561  7953  7953 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,09-02 15:27:26.586  7994  7994 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,09-02 15:27:26.609  7994  7994 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
09-02 15:27:26.609  7994  7994 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
09-02 15:27:26.609  7994  7994 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
,09-02 15:27:26.609  7994  7994 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
09-02 15:27:26.609  7994  7994 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
09-02 15:27:26.609  7994  7994 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
09-02 15:27:26.630  1043  2037 I ActivityManager: Killing 7269:com.google.android.setupwizard/u0a46 (adj 15): empty #17
,09-02 15:27:26.667  1043  1865 W libprocessgroup: failed to open /acct/uid_10046/pid_7269/cgroup.procs: No such file or directory
,09-02 15:27:26.806  1043  1059 I art     : Explicit concurrent mark sweep GC freed 35757(1714KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/64MB, paused 1.865ms total 131.922ms
,09-02 15:27:26.922  1043  1060 V SIM_STK : Menu title from STK is T-Mobile
,09-02 15:27:26.943  5009  7993 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 504 ms] updated apps [took 504 ms] 
,09-02 15:27:27.158  7760  7808 D UEI.SmartControl: Internal timer expired: 1
09-02 15:27:27.159  7760  7808 D UEI.SmartControl: unbind internal service
,09-02 15:27:27.168  7760  7760 D UEI.SmartControl: Service.onUnbind: IControl
09-02 15:27:27.180  7760  7760 D UEI.SmartControl: Service.onDestroy
09-02 15:27:27.181  7760  7760 D UEI.SmartControl: Lock is in USE false
09-02 15:27:27.181  7760  7760 D UEI.SmartControl: unbind internal service
,09-02 15:27:27.184  7760  7760 D serial_port: close(fd = 25)
,09-02 15:27:27.187  7760  7760 I UEI.SmartControl: Serial port is closed.
09-02 15:27:27.188  7760  7760 I UEI.SmartControl: Serial port is closed.
09-02 15:27:27.188  7760  7760 D UEI.SmartControl: Blaster closed
09-02 15:27:27.189  7760  7760 D UEI.SmartControl: Shut down QS...
09-02 15:27:27.189  7760  7760 D UEI.SmartControl: Stopping QS lib
09-02 15:27:27.189  7760  7760 D UEI.SmartControl: QS lib stop result = true
09-02 15:27:27.189  7760  7760 D UEI.SmartControl: Stopped QS lib
09-02 15:27:27.190  7760  7760 D UEI.SmartControl: Stopped file observer...
09-02 15:27:27.190  7760  7760 D UEI.SmartControl: QS shutdown complete
09-02 15:27:27.603  6878  6948 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 15:27:27.603  6878  6948 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2af59fa0 added. We now have 6 listener(s)
09-02 15:27:27.603  6878  6948 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-02 15:27:27.620  6878  6948 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 15:27:27.620  6878  6948 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@36f7e759 added. We now have 7 listener(s)
09-02 15:27:27.620  6878  6948 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 15:27:27.624  6878  6948 I System.out: IsBluetoothEnabled
,09-02 15:27:27.629  1043  1926 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 15:27:27.629  1043  1926 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
09-02 15:27:27.630  1043  1119 D BluetoothManagerService: Message: 2
09-02 15:27:27.633  6878  6948 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 15:27:27.635  1043  1722 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 15:27:27.635  1043  1722 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
09-02 15:27:27.649  1043  1043 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-02 15:27:27.650  1043  1043 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-02 15:27:27.650  1043  1043 D Ulp_jni : JNI:system_update. Event-4
,09-02 15:27:27.653  1043  1119 D BluetoothManagerService: Message: 1
09-02 15:27:27.653  1043  1119 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
,09-02 15:27:27.682  1043  1119 D BluetoothManagerService: Message: 20
09-02 15:27:27.682  1043  1119 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@278bace1:true
,09-02 15:27:27.687  7830  7830 D BluetoothAdapterState: make
09-02 15:27:27.692  7830  7830 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
09-02 15:27:27.692  7830  7830 I bluedroid-qcom: init
09-02 15:27:27.693  7830  8039 I BluetoothAdapterState: Entering OffState
09-02 15:27:27.694  7830  7830 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-02 15:27:27.694  7830  7830 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-02 15:27:27.694  7830  7830 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-02 15:27:27.694  7830  7830 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-02 15:27:27.694  7830  7830 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
09-02 15:27:27.696  7830  7830 I bluedroid-qcom: get_profile_interface socket
09-02 15:27:27.696  7830  7830 I bluedroid-qcom: get_profile_interface map_client
,09-02 15:27:27.700  7830  8043 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
09-02 15:27:27.695  8042  8042 W bdaddr_loader: type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-02 15:27:27.695  8042  8042 W bdaddr_loader: type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-02 15:27:27.712  1043  1043 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
,09-02 15:27:27.714  1043  1119 D BluetoothManagerService: Message: 40
09-02 15:27:27.714  1043  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
09-02 15:27:27.716  7830  7846 I bluedroid-qcom: config_hci_snoop_log
09-02 15:27:27.718  1043  1119 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
09-02 15:27:27.718  1043  1119 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
09-02 15:27:27.723  8042  8042 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
09-02 15:27:27.723  8042  8042 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
09-02 15:27:27.723  8042  8042 I LGFTMITEM: [GET_FTM][id=8], offset=16384
09-02 15:27:27.726  8042  8042 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
,09-02 15:27:27.732  7830  8039 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
09-02 15:27:27.734  8042  8042 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
09-02 15:27:27.734  8042  8042 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
09-02 15:27:27.735  7830  8043 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
09-02 15:27:27.737  1043  1043 D BluetoothManagerService: Bluetooth Adapter name changed to G3
09-02 15:27:27.737  1043  1043 D BluetoothManagerService: Stored Bluetooth name: G3
09-02 15:27:27.738  7830  8043 D BluetoothAdapterProperties: Name is: G3
,09-02 15:27:27.740  7830  8039 D BluetoothAdapterProperties: Setting state to 11
09-02 15:27:27.740  7830  8039 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
09-02 15:27:27.741  1043  1119 D BluetoothManagerService: Message: 60
09-02 15:27:27.741  1043  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
09-02 15:27:27.741  1043  1119 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
09-02 15:27:27.746  1928  1928 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-02 15:27:27.746  1589  1589 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-02 15:27:27.751  7015  7015 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
,09-02 15:27:27.754  6878  6878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 15:27:27.763  7830  8039 I LGBluetoothServiceJni: classInitNative: succeeds
09-02 15:27:27.769  7830  7830 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-02 15:27:27.769  7830  7830 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-02 15:27:27.769  7830  7830 V BluetoothPbapReceiver: ***********state = 11
,09-02 15:27:27.774  2160  2160 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-02 15:27:27.791  7015  7015 D BluetoothPermissionRequest: onReceive
,09-02 15:27:27.806  7015  7015 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-02 15:27:27.807  7830  8039 D BluetoothBondStateMachine: make
09-02 15:27:27.811  7830  8039 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c971f35
,09-02 15:27:27.811  7830  8039 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
09-02 15:27:27.811  7830  8039 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c971f35
09-02 15:27:27.811  7830  8039 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
09-02 15:27:27.812  7830  8039 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
09-02 15:27:27.813  7830  8058 I BluetoothBondStateMachine: StableState(): Entering Off State
09-02 15:27:27.817  7830  8039 E BluetoothAdapterService: File transfer profiles supported!!
09-02 15:27:27.820  7830  7830 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-02 15:27:27.822  7830  7830 V BluetoothSapReceiver: [BTUI] checkServiceStart
,09-02 15:27:27.822  7830  7830 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-02 15:27:27.822  7830  7830 V BluetoothSapReceiver: SapReceiver onReceive 
09-02 15:27:27.822  7830  7830 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-02 15:27:27.822  7830  7830 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
09-02 15:27:27.825  7830  8039 E BluetoothAdapterService: File transfer profiles supported!!
09-02 15:27:27.826  7830  7830 D HeadsetService: Received start request. Starting profile...
09-02 15:27:27.827  7830  7830 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
,09-02 15:27:27.827  7830  7830 D LGBluetoothHfpAdapter: Version 1.6
09-02 15:27:27.831  7830  7830 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
09-02 15:27:27.832  7830  7830 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-02 15:27:27.833  7830  7830 D HeadsetStateMachine: make
,09-02 15:27:27.835  7830  8039 E BluetoothAdapterService: File transfer profiles supported!!
09-02 15:27:27.840  7830  8039 E BluetoothAdapterService: File transfer profiles supported!!
09-02 15:27:27.845  7830  8039 E BluetoothAdapterService: File transfer profiles supported!!
,09-02 15:27:27.852  7830  8039 E BluetoothAdapterService: File transfer profiles supported!!
09-02 15:27:27.856  7830  8039 E BluetoothAdapterService: File transfer profiles supported!!
09-02 15:27:27.871  7830  8039 V LGMDMManager: Create singleton instance
,09-02 15:27:27.872  7830  7830 D LgDataFeature: LgDataFeature() Constructor: none
09-02 15:27:27.872  7830  7830 D LgDataFeature: LgDataFeature() Constructor Done, null
09-02 15:27:27.874  7830  8039 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
09-02 15:27:27.877  7830  7830 D HeadsetStateMachine: max_hf_connections = 1
09-02 15:27:27.877  7830  7830 I bluedroid-qcom: get_profile_interface handsfree
09-02 15:27:27.879  7830  7830 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
09-02 15:27:27.879   308  2157 V AudioPolicyService: registerClient() client 0xb558a3e0, uid 1002
09-02 15:27:27.880   308  1384 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
09-02 15:27:27.880   308  1384 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
,09-02 15:27:27.880   308  1384 V AudioPolicyManagerEx: getOutput() returns output 2
09-02 15:27:27.880  7830  7830 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
09-02 15:27:27.880   308  1383 V AudioFlinger: registerClient() client 0xb101faf0, pid 7830
09-02 15:27:27.881   308  1378 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-02 15:27:27.881   308  1378 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-02 15:27:27.881  7830  7830 V ToneGenerator: Create Track: 0xb4928a80
09-02 15:27:27.881  7830  7830 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
09-02 15:27:27.881  7830  7830 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
09-02 15:27:27.881  1589  2083 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-02 15:27:27.881  1589  2083 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-02 15:27:27.881  3395  3418 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-02 15:27:27.881  3395  3418 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-02 15:27:27.881   308  1384 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
09-02 15:27:27.881   308  1384 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
09-02 15:27:27.881   308  1384 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-02 15:27:27.881   308  1384 V AudioPolicyManagerEx: getOutput() returns output 2
09-02 15:27:27.881  7830  7830 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
09-02 15:27:27.881  7830  7847 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-02 15:27:27.881  7830  7847 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
09-02 15:27:27.881  1836  1852 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-02 15:27:27.881  1836  1852 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-02 15:27:27.882   308  2157 I AudioFlinger: isAudioPlaybackHookOn() false
09-02 15:27:27.882  1043  1562 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-02 15:27:27.882  1043  1562 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-02 15:27:27.882   308   308 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
09-02 15:27:27.882   308   308 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
09-02 15:27:27.882   308   308 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-02 15:27:27.882   308   308 V AudioPolicyManagerEx: getOutput() returns output 2
09-02 15:27:27.883  7830  7830 V AudioSystem: getLatency() output 2, latency 50
09-02 15:27:27.883  7830  7830 V AudioSystem: getFrameCount() output 2, frameCount 960
09-02 15:27:27.883  7830  7830 V AudioTrack: createTrack_l() output 2 afLatency 50
,09-02 15:27:27.883   308  1379 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-02 15:27:27.883   308  1379 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-02 15:27:27.884   308  2156 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
09-02 15:27:27.884   308  2156 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
09-02 15:27:27.884   308  2156 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
09-02 15:27:27.884   308  2156 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
09-02 15:27:27.884   308  2156 V AudioFlinger: createTrack() lSessionId: 21
09-02 15:27:27.885  1589  1608 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
,09-02 15:27:27.885  7830  7847 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-02 15:27:27.885  1589  1608 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-02 15:27:27.885  7830  7847 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
09-02 15:27:27.885  1836  1851 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-02 15:27:27.885  1836  1851 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-02 15:27:27.885  3395  3417 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-02 15:27:27.885  3395  3417 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-02 15:27:27.885  1043  2014 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-02 15:27:27.885  1043  2014 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-02 15:27:27.885  7830  7830 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
09-02 15:27:27.886   308   308 V AudioFlinger: acquiring 21 from 7830, for 7830
09-02 15:27:27.886   308   308 V AudioFlinger:  added new entry for 21
09-02 15:27:27.886  7830  7830 V ToneGenerator: ToneGenerator INIT OK, time: 201159
09-02 15:27:27.886  7830  7830 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c971f35
09-02 15:27:27.887  7830  8061 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
09-02 15:27:27.887  7830  8061 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
,09-02 15:27:27.887  7830  8061 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-02 15:27:27.887  7830  8061 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
,09-02 15:27:27.888   308  1384 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7830
,09-02 15:27:27.888  7830  7830 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c971f35
09-02 15:27:27.889   308  1384 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
09-02 15:27:27.889   308  1384 V voice   : voice_set_parameters: enter: bt_samplerate=8000
09-02 15:27:27.889   308  1384 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
09-02 15:27:27.889   308  1384 V compress_voip: voice_extn_compress_voip_set_parameters: exit
09-02 15:27:27.889   308  1384 V voice   : voice_set_parameters: exit with code(0)
09-02 15:27:27.889   308  1384 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
09-02 15:27:27.889   308  1384 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
09-02 15:27:27.889   308  1384 V msm8974_platform: platform_set_parameters: exit with code(0)
09-02 15:27:27.889   308  1384 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
09-02 15:27:27.889   308  1384 V audio_hw_primary: adev_set_parameters: exit with code(0)
09-02 15:27:27.889   308  1384 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
09-02 15:27:27.890  7830  8061 V ToneGenerator: ToneGenerator destructor
09-02 15:27:27.890  7830  8061 V ToneGenerator: stopTone
09-02 15:27:27.890  7830  8061 V ToneGenerator: Delete Track: 0xb4928a80
09-02 15:27:27.891  7830  7830 D A2dpService: Received start request. Starting profile...
09-02 15:27:27.891  7830  8061 V AudioTrack: ~AudioTrack, releasing session id from 7830 on behalf of 7830
09-02 15:27:27.891   308  2156 V AudioPolicyService: AudioCommandThread() adding release output 2
09-02 15:27:27.891   308  2156 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
09-02 15:27:27.891   308  1383 V AudioFlinger: releasing 21 from 7830 for 7830
09-02 15:27:27.891   308  2156 V AudioFlinger: PlaybackThread::Track destructor
09-02 15:27:27.891   308  1383 V AudioFlinger:  decremented refcount to 0
09-02 15:27:27.891   308  1273 V AudioPolicyService: AudioCommandThread() waking up
09-02 15:27:27.891   308  1383 V AudioFlinger: purging stale effects
09-02 15:27:27.891   308  2156 V AudioFlinger: removeClient_l() pid 7830, calling pid 308
09-02 15:27:27.891  7830  7830 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-02 15:27:27.891   308  1273 V AudioPolicyService: AudioCommandThread() processing release output 2
09-02 15:27:27.891   308  1273 V AudioPolicyManager: releaseOutput() 2
09-02 15:27:27.891   308  1273 V AudioPolicyService: AudioCommandThread() going to sleep
09-02 15:27:27.892  7830  7830 V Avrcp   : make
09-02 15:27:27.893  7830  7830 D Avrcp   : [BTUI] Use Native AVRCP : init jni
09-02 15:27:27.893  7830  7830 I bluedroid-qcom: get_profile_interface avrcp
09-02 15:27:27.894  1043  1771 W Process : Unable to open /proc/8063/status
09-02 15:27:27.905  7830  7830 V AudioManager: registerRemoteController: size of Media player list: 0
,09-02 15:27:27.909  7830  7830 E AudioManager: No RCC entry present to update
,09-02 15:27:27.909  7830  7830 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
09-02 15:27:27.914  7830  7830 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
09-02 15:27:27.916  7830  7830 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
09-02 15:27:27.916  7830  7830 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
09-02 15:27:27.921  7830  7830 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,09-02 15:27:28.077  1043  2018 V SIM_STK : Menu title from STK is T-Mobile
09-02 15:27:28.078  1043  2018 V SIM_STK : Menu title from STK is T-Mobile
,09-02 15:27:28.215  1043  1060 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,09-02 15:27:28.228  7830  7830 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
,09-02 15:27:28.235  7830  7830 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
09-02 15:27:28.236  7830  7830 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
,09-02 15:27:28.236  7830  7830 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
09-02 15:27:28.236  7830  7830 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
09-02 15:27:28.236  7830  7830 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-02 15:27:28.236  7830  7830 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
09-02 15:27:28.236  7830  7830 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
09-02 15:27:28.237  7830  7830 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
09-02 15:27:28.237  7830  7830 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-02 15:27:28.237  7830  7830 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
09-02 15:27:28.237  7830  7830 I BluetoothA2dpServiceJni: classInitNative
09-02 15:27:28.237  7830  7830 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-02 15:27:28.238  7830  7830 D A2dpStateMachine: make
,09-02 15:27:28.240  7830  7830 I bluedroid-qcom: get_profile_interface a2dp
,09-02 15:27:28.241  7830  8074 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
09-02 15:27:28.244  7830  7830 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
09-02 15:27:28.244  7830  7830 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
09-02 15:27:28.246  7830  7830 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c971f35
09-02 15:27:28.247  7830  7830 I BluetoothHidServiceJni: classInitNative: succeeds
09-02 15:27:28.250  7830  7830 D HidService: Received start request. Starting profile...
09-02 15:27:28.250  7830  7830 I bluedroid-qcom: get_profile_interface hidhost
09-02 15:27:28.250  7830  7830 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c971f35
,09-02 15:27:28.250  7830  8073 D A2dpStateMachine: Enter Disconnected: -2
,09-02 15:27:28.251  7830  7830 I BluetoothHealthServiceJni: classInitNative: succeeds
09-02 15:27:28.254  7830  7830 D HealthService: Received start request. Starting profile...
09-02 15:27:28.256  7830  7830 I bluedroid-qcom: get_profile_interface health
09-02 15:27:28.257  7830  7830 I LGBluetoothHealthServiceJni: classInitNative: succeeds
09-02 15:27:28.257  7830  7830 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c971f35
09-02 15:27:28.258  7830  7830 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-02 15:27:28.261  7830  7830 D PanService: Received start request. Starting profile...
09-02 15:27:28.261  7830  7830 D BluetoothPanServiceJni: initializeNative(L110): pan
09-02 15:27:28.261  7830  7830 I bluedroid-qcom: get_profile_interface pan
09-02 15:27:28.270  7830  7830 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
09-02 15:27:28.270  7830  7830 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c971f35
09-02 15:27:28.272  7830  7830 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
,09-02 15:27:28.280  7830  7830 D BtGatt.DebugUtils: handleDebugAction() action=null
09-02 15:27:28.280  7830  7830 D BtGatt.GattService: Received start request. Starting profile...
09-02 15:27:28.280  7830  7830 D BtGatt.GattService: start()
09-02 15:27:28.281  7830  7830 I bluedroid-qcom: get_profile_interface gatt
09-02 15:27:28.281  7830  7830 D BtGatt.AdvertiseManager: advertise manager created
09-02 15:27:28.292  7830  7830 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c971f35
,09-02 15:27:28.297  7830  7830 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c971f35
,09-02 15:27:28.298  7830  7830 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
,09-02 15:27:28.300  7830  7830 V BluetoothMapService: BluetoothMapBinder(),
09-02 15:27:28.302  7830  7830 D BluetoothMapService: Received start request. Starting profile...
09-02 15:27:28.302  7830  7830 D BluetoothMapService: start()
09-02 15:27:28.305  7830  7830 D BluetoothMapEmailSettingsLoader: Found 0 applications
09-02 15:27:28.305  7830  7830 D BluetoothMapEmailAppObserver: createReceiver()
09-02 15:27:28.307  7830  7830 D BluetoothMapEmailAppObserver: initObservers()
09-02 15:27:28.308  7830  7830 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
,09-02 15:27:28.324  7830  7830 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c971f35
,09-02 15:27:28.327  7830  7830 D HeadsetStateMachine: Proxy object connected
09-02 15:27:28.328  7830  7830 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
09-02 15:27:28.328  7830  7830 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
09-02 15:27:28.334  7830  7830 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-02 15:27:28.334  7830  8061 D HeadsetStateMachine: Disconnected process message: 10, size: 0
09-02 15:27:28.336  7830  8061 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-02 15:27:28.337  7830  8061 D HeadsetStateMachine: Disconnected process message: 11, size: 0
09-02 15:27:28.339  7830  7830 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,09-02 15:27:28.344  7830  7830 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-02 15:27:28.348  7830  7830 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-02 15:27:28.349  7830  7830 V PanService: [BTUI] SIM Extra State :ABSENT
09-02 15:27:28.353  7830  7830 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,09-02 15:27:28.356  7830  7830 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
09-02 15:27:28.356  7830  7830 V BluetoothMapService: Handler(): got msg=1
09-02 15:27:28.358  7830  8039 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
09-02 15:27:28.358  7830  8039 I bluedroid-qcom: enable
09-02 15:27:28.359  7830  8039 I bt_hci_bdroid: init
09-02 15:27:28.359  7830  8081 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
09-02 15:27:28.362  7830  8039 I bt_vendor: bt-vendor : init
09-02 15:27:28.362  7830  8039 I bt_vendor: bt-vendor : get_bt_soc_type
09-02 15:27:28.362  7830  8039 E bt_vendor: get_bt_soc_type: Failed to get soc type
09-02 15:27:28.362  7830  8039 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
09-02 15:27:28.362  7830  8039 D bt_userial_mct: userial_init
09-02 15:27:28.363  7830  8081 I bt-btu  : btu_task pending for preload complete event
09-02 15:27:28.363  7830  8039 D bt_hci_bdroid: set_power 1
09-02 15:27:28.363  7830  8039 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
09-02 15:27:28.363  7830  8039 I bt_vendor: Starting hciattach daemon
09-02 15:27:28.363  7830  8039 I bt_vendor: try to set true
09-02 15:27:28.365  8084  8084 W sh      : type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-02 15:27:28.365  8084  8084 W sh      : type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-02 15:27:28.404  8085  8085 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,09-02 15:27:28.472  8091  8091 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,09-02 15:27:28.485  8092  8092 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
09-02 15:27:28.512  8094  8094 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-02 15:27:28.526  8095  8095 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,09-02 15:27:28.540  8096  8096 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-02 15:27:28.553  8097  8097 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
09-02 15:27:28.579  8099  8099 I libmdmdetect: ESOC framework not supported
,09-02 15:27:28.581  8099  8099 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,09-02 15:27:28.593  8099  8099 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
09-02 15:27:28.593  8099  8099 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
,09-02 15:27:28.593  8099  8099 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
09-02 15:27:28.593  8099  8099 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
09-02 15:27:28.593  8099  8099 D bthci_qcomm_common: [BTUI]     LE: Class 2
09-02 15:27:28.593  8099  8099 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
09-02 15:27:28.593  8099  8099 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
,09-02 15:27:28.641  8099  8100 E QC-QMI  : qmi_client [8099] 15: failed to locate client data
,09-02 15:27:28.642   455   455 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
09-02 15:27:28.642   455   455 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
,09-02 15:27:28.690  8101  8101 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,09-02 15:27:28.703  8102  8102 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,09-02 15:27:28.768  7830  8039 I bt_vendor: bluetooth satus is on
09-02 15:27:28.768  7830  8039 D bt_hci_bdroid: preload
09-02 15:27:28.769  7830  8083 D bt_userial_mct: userial_open(port:0)
09-02 15:27:28.769  7830  8083 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,09-02 15:27:28.773  7830  8083 I bt_vendor: Done intiailizing UART
,09-02 15:27:28.778  7830  8083 I bt_vendor: Done intiailizing UART
09-02 15:27:28.778  7830  8083 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
09-02 15:27:28.778  7830  8083 I bt_vendor: Bluetooth Firmware and transport layer are initialized
09-02 15:27:28.779  7830  8104 D bt_userial_mct: Entering userial_read_thread()
09-02 15:27:28.779  7830  8081 I bt-btu  : btu_task received preload complete event
09-02 15:27:28.781  7830  8081 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
09-02 15:27:28.781  7830  8081 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
09-02 15:27:28.789  7830  8081 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
,09-02 15:27:28.795  7830  8081 I         : BTE_InitTraceLevels -- TRC_HCI
,09-02 15:27:28.795  7830  8081 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-02 15:27:28.795  7830  8081 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-02 15:27:28.795  7830  8081 I         : BTE_InitTraceLevels -- TRC_AVDT
09-02 15:27:28.795  7830  8081 I         : BTE_InitTraceLevels -- TRC_AVRC
09-02 15:27:28.795  7830  8081 I         : BTE_InitTraceLevels -- TRC_A2D
09-02 15:27:28.795  7830  8081 I         : BTE_InitTraceLevels -- TRC_BNEP
09-02 15:27:28.795  7830  8081 I         : BTE_InitTraceLevels -- TRC_BTM
,09-02 15:27:28.795  7830  8081 I         : BTE_InitTraceLevels -- TRC_HID_HOST,
09-02 15:27:28.795  7830  8081 I         : BTE_InitTraceLevels -- TRC_GAP
,09-02 15:27:28.795  7830  8081 I         : BTE_InitTraceLevels -- TRC_PAN
09-02 15:27:28.795  7830  8081 I         : BTE_InitTraceLevels -- TRC_SDP,
09-02 15:27:28.795  7830  8081 I         : BTE_InitTraceLevels -- TRC_GATT
,09-02 15:27:28.795  7830  8081 I         : BTE_InitTraceLevels -- TRC_SMP
,09-02 15:27:28.795  7830  8081 I         : BTE_InitTraceLevels -- TRC_BTAPP
,09-02 15:27:28.795  7830  8081 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-02 15:27:28.896  7830  8081 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
09-02 15:27:28.896  7830  8081 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa01af061 ,
09-02 15:27:28.896  7830  8081 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa01af061 
,09-02 15:27:28.954  7830  8043 E bt-btif : Calling BTA_HhEnable
09-02 15:27:28.954  7830  8043 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
09-02 15:27:28.954  7830  8043 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,09-02 15:27:28.961  7830  8081 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
09-02 15:27:28.961  7830  8081 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
09-02 15:27:28.961  7830  8081 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
09-02 15:27:28.961  7830  8081 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
09-02 15:27:28.962  7830  8081 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
09-02 15:27:28.964  1043  1043 D BluetoothManagerService: Bluetooth Adapter name changed to G3
09-02 15:27:28.965  1043  1043 D BluetoothManagerService: Stored Bluetooth name: G3
09-02 15:27:28.965  7830  8043 D BluetoothAdapterProperties: Name is: G3
09-02 15:27:28.969  7830  8043 D BluetoothAdapterProperties: Scan Mode:20
09-02 15:27:28.969  7830  8043 D BluetoothAdapterProperties: Discoverable Timeout:120
09-02 15:27:28.969  7830  8043 D bt_hci_bdroid: postload
,09-02 15:27:28.976  7830  8083 D bt_hci_bdroid: Used up Tx Cmd credits
,09-02 15:27:28.977  7830  8081 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
09-02 15:27:28.980  7830  8083 D bt_hci_bdroid: Used up Tx Cmd credits
09-02 15:27:28.981  7830  8043 D bte_conf: Device ID record 1 : primary
,09-02 15:27:28.981  7830  8043 D bte_conf:   vendorId            = 00c4
09-02 15:27:28.981  7830  8043 D bte_conf:   vendorIdSource      = 0001
09-02 15:27:28.981  7830  8043 D bte_conf:   product             = 13a1
09-02 15:27:28.981  7830  8043 D bte_conf:   version             = 1000
09-02 15:27:28.981  7830  8043 D bte_conf:   clientExecutableURL = 
09-02 15:27:28.981  7830  8043 D bte_conf:   serviceDescription  = 
09-02 15:27:28.981  7830  8043 D bte_conf:   documentationURL    = 
09-02 15:27:28.981  7830  8043 D bte_conf: bte_load_did_conf no section named DID2.
09-02 15:27:28.984  7830  8083 D bt_hci_bdroid: Used up Tx Cmd credits
,09-02 15:27:28.991  7830  8081 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-02 15:27:28.991  7830  8081 W bt-smp  : Plain text(LSB ~ MSB) = 2a 78 44 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-02 15:27:28.991  7830  8081 W bt-smp  : Encrypted text(LSB ~ MSB) = 0a c6 10 03 3c 9b fa 74 4a a9 26 35 49 4b 64 c8 
09-02 15:27:28.992  7830  8083 D bt_hci_bdroid: Used up Tx Cmd credits
09-02 15:27:28.993  7830  8081 W bt-btm  : Stopping oneshot timer
09-02 15:27:28.985  8109  8109 W sh      : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-02 15:27:28.985  8109  8109 W sh      : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-02 15:27:28.997  7830  8104 E bt_mct  : hci lib postload completed
09-02 15:27:28.997  7830  8039 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
09-02 15:27:28.998  7830  8039 D BluetoothAdapterProperties: ScanMode =  20
09-02 15:27:28.998  7830  8039 D BluetoothAdapterProperties: State =  11
09-02 15:27:28.998  7830  8039 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
09-02 15:27:28.998  7830  8039 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
09-02 15:27:28.998  7830  8039 D BluetoothAdapterProperties: Setting state to 12
09-02 15:27:28.998  7830  8039 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-02 15:27:29.001  1043  1119 D BluetoothManagerService: Message: 60
09-02 15:27:29.001  1043  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
09-02 15:27:29.001  1043  1119 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
,09-02 15:27:29.005  7830  8039 I BluetoothAdapterState: Entering On State
09-02 15:27:29.013  7830  8043 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-02 15:27:29.013  7830  8043 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-02 15:27:29.037  6878  6878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 15:27:29.037  6878  6878 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 15:27:29.037  6878  6878 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 15:27:29.037  6878  6878 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 15:27:29.037  6878  6878 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 15:27:29.037  6878  6878 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 15:27:29.037  6878  6878 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 15:27:29.037  6878  6878 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-02 15:27:29.054  7830  8081 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-02 15:27:29.054  7830  8081 W bt-smp  : Plain text(LSB ~ MSB) = 8b ce 63 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-02 15:27:29.054  7830  8081 W bt-smp  : Encrypted text(LSB ~ MSB) = 69 ce a8 61 c6 d8 d7 3b a8 21 86 67 bb 69 1b b9 
,09-02 15:27:29.057  7830  8081 W bt-btm  : Stopping oneshot timer
09-02 15:27:29.058  7830  8039 D LGBluetoothServiceAdapter: [BTUI] OnState
09-02 15:27:29.058  7830  8039 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
09-02 15:27:29.058  7830  8039 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
09-02 15:27:29.059  7830  8039 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
09-02 15:27:29.059  7830  8039 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
09-02 15:27:29.070  7830  8081 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-02 15:27:29.070  7830  8081 W bt-smp  : Plain text(LSB ~ MSB) = dc 0c 4d 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-02 15:27:29.070  7830  8081 W bt-smp  : Encrypted text(LSB ~ MSB) = 98 ab ba ea 3c 5a 5d 89 d5 9d 2f ea 64 30 a9 bf 
,09-02 15:27:29.073  7830  8081 W bt-btm  : Stopping oneshot timer
09-02 15:27:29.077  6878  6878 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-02 15:27:29.080  7830  8043 D BluetoothAdapterProperties: Discoverable Timeout:120
09-02 15:27:29.080  7830  8043 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
09-02 15:27:29.087  7830  8081 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-02 15:27:29.087  7830  8081 W bt-smp  : Plain text(LSB ~ MSB) = 87 8a 5a 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-02 15:27:29.087  7830  8081 W bt-smp  : Encrypted text(LSB ~ MSB) = 58 7d b2 ce 21 a7 bb 34 1b 78 bb 95 ff ad 87 b3 
,09-02 15:27:29.090  7830  8081 W bt-btm  : Stopping oneshot timer
09-02 15:27:29.090  7015  7030 D BluetoothHeadset: onBluetoothStateChange: up=true
09-02 15:27:29.102  7830  8081 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-02 15:27:29.102  7830  8081 W bt-smp  : Plain text(LSB ~ MSB) = f9 e8 55 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-02 15:27:29.102  7830  8081 W bt-smp  : Encrypted text(LSB ~ MSB) = 8e 10 19 c8 cb d7 c8 e9 2a 5d 46 51 ed e7 8a 2c 
,09-02 15:27:29.105  7830  8081 W bt-btm  : Stopping oneshot timer
09-02 15:27:29.117  8114  8114 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
,09-02 15:27:29.126  7015  7015 D BluetoothHeadset: Proxy object connected
09-02 15:27:29.126  7015  7015 D HeadsetProfile: Bluetooth service connected
09-02 15:27:29.126  1043  1119 D BluetoothA2dp: onBluetoothStateChange: up=true
09-02 15:27:29.128  7015  7031 D BluetoothPan: onBluetoothStateChange on: true
09-02 15:27:29.129  7015  7031 D BluetoothPan: onBluetoothStateChange call bindService
09-02 15:27:29.134  1043  1043 D BluetoothA2dp: Proxy object connected
,09-02 15:27:29.138  7015  7015 D BluetoothPan: BluetoothPAN Proxy object connected
09-02 15:27:29.139  7015  7015 D PanProfile: Bluetooth service connected
09-02 15:27:29.139  7015  7030 D BluetoothA2dp: onBluetoothStateChange: up=true
09-02 15:27:29.140  1043  1119 D BluetoothHeadset: onBluetoothStateChange: up=true
09-02 15:27:29.141  7015  7015 D BluetoothA2dp: Proxy object connected
09-02 15:27:29.141  7015  7015 D A2dpProfile: Bluetooth service connected
09-02 15:27:29.141  1043  1043 D BluetoothHeadset: Proxy object connected
09-02 15:27:29.142  1836  3496 D BluetoothHeadset: onBluetoothStateChange: up=true
09-02 15:27:29.144  1836  1836 D BluetoothHeadset: Proxy object connected
09-02 15:27:29.144  7015  7031 D BluetoothPbap: onBluetoothStateChange: up=true
09-02 15:27:29.146  1836  1851 D BluetoothHeadset: onBluetoothStateChange: up=true
09-02 15:27:29.147  1836  1836 D BluetoothHeadset: Proxy object connected
,09-02 15:27:29.148  7015  7030 D BluetoothMap: onBluetoothStateChange: up=true
09-02 15:27:29.150  1836  1852 D BluetoothHeadset: onBluetoothStateChange: up=true
09-02 15:27:29.151  7015  7015 D BluetoothMap: Proxy object connected
09-02 15:27:29.151  7015  7015 D MapProfile: Bluetooth service connected
09-02 15:27:29.151  7015  7015 D BluetoothMap: getConnectedDevices()
09-02 15:27:29.152  1836  1836 D BluetoothHeadset: Proxy object connected
09-02 15:27:29.152  7830  8128 V BluetoothMapService: getConnectedDevices()
09-02 15:27:29.153  7015  7031 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-02 15:27:29.155  1043  1119 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
09-02 15:27:29.155  1043  1119 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
09-02 15:27:29.155  7015  7015 D BluetoothInputDevice: Proxy object connected
09-02 15:27:29.155  7015  7015 D HidProfile: Bluetooth service connected
09-02 15:27:29.157  1043  1043 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
09-02 15:27:29.157  1043  1119 D BluetoothManagerService: Message: 40
09-02 15:27:29.157  1043  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
09-02 15:27:29.158  1928  1928 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-02 15:27:29.158  1928  2066 D LGBluetoothAPIService: Message: 1
09-02 15:27:29.158  1928  2066 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
09-02 15:27:29.158  1928  2066 D LGBluetoothAPIService: Calling onBluetoothServiceUp callbacks
09-02 15:27:29.158  1928  2066 D LGBluetoothAPIService: Broadcasting onBluetoothServiceUp() to 0 receivers.
09-02 15:27:29.161  6878  6878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 15:27:29.161  1589  1589 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-02 15:27:29.164  7830  7830 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-02 15:27:29.164  7830  7830 D BluetoothMapService: STATE_ON
09-02 15:27:29.170  7015  7015 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
09-02 15:27:29.171  7015  7015 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-02 15:27:29.179  7015  7015 D DockEventReceiver: finishStartingService: stopping service
,09-02 15:27:29.180  7830  7830 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c971f35
09-02 15:27:29.180  7830  7830 V BluetoothPbapService: Pbap Service onCreate
09-02 15:27:29.180  7830  7830 V BluetoothPbapService: Starting PBAP service
09-02 15:27:29.182  7830  7830 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
09-02 15:27:29.182  7830  7830 V BluetoothMapService: Handler(): got msg=1
,09-02 15:27:29.182  7830  7830 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
09-02 15:27:29.183  7830  7830 V BluetoothPbapService: Pbap Service onBind
09-02 15:27:29.183  7830  7830 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-02 15:27:29.183  7015  7015 D BluetoothPbap: Proxy object connected
09-02 15:27:29.184  7830  7830 V BluetoothPbapService: state: 12
09-02 15:27:29.184  7830  8134 D BluetoothMapMasInstance: MAS initSocket()
09-02 15:27:29.184  7830  7830 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-02 15:27:29.184  7830  7830 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-02 15:27:29.184  7830  7830 V BluetoothPbapReceiver: ***********state = 12
09-02 15:27:29.184  7830  8134 D BluetoothMapMasInstance:   masId = 00
09-02 15:27:29.184  7830  8134 D BluetoothMapMasInstance:   msgTypes = 0e
09-02 15:27:29.184  7830  8134 D BluetoothMapMasInstance:   masName = SMS/MMS
09-02 15:27:29.184  7830  8134 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
09-02 15:27:29.185  1043  1771 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 15:27:29.184  7015  7015 D PbapServerProfile: Bluetooth service connected
09-02 15:27:29.187  7830  7830 V BluetoothPbapService: Handler(): got msg=1
09-02 15:27:29.187  7830  7830 V BluetoothPbapService: Pbap Service startRfcommSocketListener
09-02 15:27:29.188  7830  8135 V BluetoothPbapService: Pbap Service initSocket
09-02 15:27:29.188  2160  2160 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-02 15:27:29.188  7830  8134 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-02 15:27:29.189  2160  2160 D c       : Getting all permits...
09-02 15:27:29.189  2160  2160 D a       : Opening database...
09-02 15:27:29.190  7830  8134 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
09-02 15:27:29.190  7830  8043 D BluetoothAdapterProperties: Scan Mode:21
09-02 15:27:29.190  7830  8043 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
09-02 15:27:29.191  7830  8134 V BluetoothMapMasInstance: Succeed to create listening socket 
09-02 15:27:29.191  7830  8134 D BluetoothMapMasInstance: Accepting socket connection...
,09-02 15:27:29.192  2160  2160 D a       : Opening database auth.proximity.permit_store...
09-02 15:27:29.193  2160  2160 D a       : Closing database...
09-02 15:27:29.196  6878  6878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 15:27:29.198  1043  1998 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 15:27:29.199  7830  8135 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-02 15:27:29.205  7830  8135 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
09-02 15:27:29.206  7830  8135 V BluetoothPbapService: Succeed to create listening socket 
09-02 15:27:29.206  7830  8135 V BluetoothPbapService: Accepting socket connection...
,09-02 15:27:29.210  7015  7015 D BluetoothPermissionRequest: onReceive
,09-02 15:27:29.211  7015  7015 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
09-02 15:27:29.213  7015  7015 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-02 15:27:29.216  7830  7830 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
09-02 15:27:29.217  7830  7830 I LGBluetoothOppAdapter: [BTUI] startOppService()
09-02 15:27:29.222  7830  7830 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,09-02 15:27:29.245  7830  7830 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
09-02 15:27:29.246  7830  7830 V BtOppService: onCreate
,09-02 15:27:29.251  7830  7830 V BluetoothOppNotification: send message
,09-02 15:27:29.254  7830  7830 V BtOppService: Starting RfcommListener
09-02 15:27:29.263  7830  7830 D BluetoothOppPreference: Dumping Names:  
09-02 15:27:29.263  7830  7830 D BluetoothOppPreference: {}
09-02 15:27:29.263  7830  7830 D BluetoothOppPreference: Dumping Channels:  
09-02 15:27:29.263  7830  7830 D BluetoothOppPreference: {}
,09-02 15:27:29.267  7830  7830 V BtOppService: onStartCommand
09-02 15:27:29.272  7830  7830 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,09-02 15:27:29.273  7830  7830 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
09-02 15:27:29.277  7830  8142 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-02 15:27:29.277  7830  7830 V BluetoothOppNotification: new notify threadi!
,09-02 15:27:29.278  7830  8139 V BtOppService: Deleted complete outbound shares, number =  0
09-02 15:27:29.281  7830  7830 V BluetoothOppNotification: send delay message
09-02 15:27:29.282  7830  7830 V BtOppService: start RfcommListener
09-02 15:27:29.283  7830  8142 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-02 15:27:29.283  7830  8139 V BtOppService: Deleted complete inbound failed shares, number = 0
09-02 15:27:29.284  7830  8139 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
09-02 15:27:29.286  7830  8139 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@ba1d401 on behalf of 
09-02 15:27:29.287  7830  8142 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3c45c2a6 on behalf of 
09-02 15:27:29.287  7830  7830 V BtOppService: RfcommListener started
09-02 15:27:29.289  7830  7830 V BtOppService: ContentObserver received notification
09-02 15:27:29.290  7830  8143 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,09-02 15:27:29.295  7830  8144 V BtOppRfcommListener: Starting RFCOMM listener....
09-02 15:27:29.298  1043  1962 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 15:27:29.298  7830  8142 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-02 15:27:29.298  7830  8142 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-02 15:27:29.301  7830  8144 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-02 15:27:29.301  7830  8143 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1d66a4e7 on behalf of 
09-02 15:27:29.301  7830  8142 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3c9cc894 on behalf of 
09-02 15:27:29.302  7830  8143 V BluetoothOppNotification: mUpdateCompleteNotification = true
09-02 15:27:29.303  7830  8144 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=75
09-02 15:27:29.303  7830  8142 V BluetoothOppNotification: update too frequent, put in queue
09-02 15:27:29.304  7830  8143 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,09-02 15:27:29.305  7830  8142 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
09-02 15:27:29.305  7830  8144 V BtOppRfcommListener: Started RFCOMM listener....
09-02 15:27:29.305  7830  8144 I BtOppRfcommListener: Accept thread started.
09-02 15:27:29.305  7830  8144 V BtOppRfcommListener: Accepting connection...
09-02 15:27:29.307  7830  8143 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@a56af3d on behalf of 
09-02 15:27:29.309  7830  8143 V BluetoothOppNotification: outbound: succ-0  fail-0
09-02 15:27:29.312  7830  8143 V BluetoothOppNotification: outbound notification was removed.
09-02 15:27:29.312  7830  8143 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
09-02 15:27:29.313  7830  7830 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c971f35
09-02 15:27:29.313  7830  7830 V BluetoothFtpService: Ftp Service onCreate
09-02 15:27:29.313  7830  7830 I BluetoothFtpService: Ftp Service onCreate
09-02 15:27:29.313  7830  7830 V BluetoothFtpService: Ftp Service onStartCommand
09-02 15:27:29.313  7830  7830 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-02 15:27:29.314  7830  7830 V BluetoothFtpService: Starting Listening on sockets
09-02 15:27:29.314  7830  7830 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-02 15:27:29.314  7830  7830 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-02 15:27:29.314  7830  7830 V BluetoothSapReceiver: SapReceiver onReceive 
09-02 15:27:29.314  7830  7830 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-02 15:27:29.314  7830  8143 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@156ea883 on behalf of 
09-02 15:27:29.314  7830  7830 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
09-02 15:27:29.314  7830  7830 V BluetoothSapReceiver: Calling SAP service start service with action = null
09-02 15:27:29.316  7830  8143 V BluetoothOppNotification: inbound: succ-0  fail-0
09-02 15:27:29.318  7830  7830 V BtOppService: ContentObserver received notification
09-02 15:27:29.318  7830  7830 V BluetoothFtpService: Handler(): got msg=1
,09-02 15:27:29.322  7830  7830 V BluetoothFtpService: Ftp Service startRfcommSocketListener
09-02 15:27:29.322  7830  7830 V BluetoothFtpService: Ftp Service initSocket
09-02 15:27:29.324  7830  8145 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-02 15:27:29.325  7830  8143 V BluetoothOppNotification: inbound notification was removed.
09-02 15:27:29.325  7830  8145 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-02 15:27:29.325  7830  8143 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
09-02 15:27:29.327  7830  8145 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2fc7da00 on behalf of 
09-02 15:27:29.328  7830  8145 V BluetoothOppNotification: update too frequent, put in queue
09-02 15:27:29.330  7830  8145 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
09-02 15:27:29.330  7830  8143 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@18840239 on behalf of 
09-02 15:27:29.330  1043  1771 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 15:27:29.331  7830  7830 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-02 15:27:29.332  7830  7830 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=81 mFd=80
09-02 15:27:29.332  7830  7830 V BluetoothFtpService: Succeed to create listening socket on channel 20
09-02 15:27:29.334  7830  8146 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
,09-02 15:27:29.351  7830  7830 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c971f35
,09-02 15:27:29.351  7830  7830 V BluetoothSapService: Sap Service onCreate
09-02 15:27:29.353  7830  7830 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-02 15:27:29.353  7830  7830 V BluetoothSapService: state: 12
09-02 15:27:29.353  7830  7830 V BluetoothSapService: Starting SAP server process
09-02 15:27:29.355  7830  7830 V BluetoothSapService: SAP Service startRfcommListenerThread
09-02 15:27:29.355  8147  8147 W sapd    : type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-02 15:27:29.355  8147  8147 W sapd    : type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-02 15:27:29.357  7830  8148 V BluetoothSapService: Sap Service initRfcommSocket
09-02 15:27:29.358  1043  1891 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 15:27:29.359  7830  8148 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-02 15:27:29.360  7830  8148 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=81
09-02 15:27:29.360  7830  8148 V BluetoothSapService: Succeed to create listening socket 
09-02 15:27:29.360  7830  8148 V BluetoothSapService: Accepting socket connection...
,09-02 15:27:29.378  8147  8147 V BT_SAP  : Event pipe created
09-02 15:27:29.378  8147  8147 V BT_SAP  : create_server_socket qcom.sap.server
09-02 15:27:29.378  8147  8147 V BT_SAP  : created socket fd 6
,09-02 15:27:29.698  6878  6948 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 15:27:29.698  6878  6948 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 15:27:29.698  6878  6948 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 15:27:29.698  6878  6948 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 15:27:29.698  6878  6948 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 15:27:29.698  6878  6948 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 15:27:29.698  6878  6948 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 15:27:29.698  6878  6948 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-02 15:27:29.703  6878  6948 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-02 15:27:29.706  6878  6948 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 15:27:29.706  6878  6948 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@37e0cf1e added. We now have 8 listener(s)
09-02 15:27:29.706  6878  6948 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 15:27:29.709  1043  1891 D WifiServiceImplEx: setWifiEnabled: false pid=6878, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-02 15:27:29.709  1043  1891 D WifiService: setWifiEnabled: false pid=6878, uid=10118
09-02 15:27:29.709  1043  1891 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-02 15:27:29.714  6878  6948 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 15:27:29.719  1043  1926 D WifiServiceImplEx: setWifiEnabled: true pid=6878, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-02 15:27:29.719  1043  1926 D WifiService: setWifiEnabled: true pid=6878, uid=10118
09-02 15:27:29.719  1043  1926 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-02 15:27:29.736  1043  1043 D LocationManagerService: getAllProviders()=[passive, gps, network]
,09-02 15:27:29.737  1043  1043 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-02 15:27:29.737  1043  1043 D Ulp_jni : JNI:system_update. Event-4
09-02 15:27:29.738  1043  1377 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
09-02 15:27:29.738  1043  1377 I LGFTMITEM: [GET_FTM][id=6], offset=12288
09-02 15:27:29.741  1043  1377 E WifiUtil: wfc_util_ffile_check_copy(): pid[1043] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
09-02 15:27:29.741  1043  1377 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-02 15:27:29.741  1043  1377 E WifiUtil: wfc_util_ffile_check_copy(): pid[1043] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
,09-02 15:27:29.741  1043  1377 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010],
09-02 15:27:29.742  1043  1377 I WifiUtil: Intf0MacAddress=C49A027FFB5D
,09-02 15:27:29.742  1043  1377 E WifiHW  : unknown target_country: EU , set to default,
09-02 15:27:29.742  1043  1377 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
09-02 15:27:29.742  1043  1377 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
,09-02 15:27:29.742  1043  1377 I WifiUtil: gEnableBmps=1
09-02 15:27:30.284  7830  7830 V BluetoothOppNotification: new notify threadi!
09-02 15:27:30.284  7830  7830 V BluetoothOppNotification: send delay message
,09-02 15:27:30.311  7830  8167 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,09-02 15:27:30.332  7830  8167 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3f9988f5 on behalf of 
09-02 15:27:30.333  7830  8167 V BluetoothOppNotification: mUpdateCompleteNotification = true
,09-02 15:27:30.346  7830  8167 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,09-02 15:27:30.351  7830  8167 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3e98268a on behalf of 
09-02 15:27:30.352  7830  8167 V BluetoothOppNotification: outbound: succ-0  fail-0
09-02 15:27:30.353  7830  8167 V BluetoothOppNotification: outbound notification was removed.
09-02 15:27:30.353  7830  8167 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
09-02 15:27:30.354  7830  8167 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1b42a4fb on behalf of 
09-02 15:27:30.355  7830  8167 V BluetoothOppNotification: inbound: succ-0  fail-0
09-02 15:27:30.356  7830  8167 V BluetoothOppNotification: inbound notification was removed.
09-02 15:27:30.357  7830  8167 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
09-02 15:27:30.357  7830  8167 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3ec6e918 on behalf of 
09-02 15:27:30.409   304   880 D SoftapController: Softap fwReload - Ok
,09-02 15:27:30.417  1043  1119 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-02 15:27:30.417  1043  1377 E NetdConnector: NDC Command {84 softap fwreload wlan0 STA} took too long (672ms)
09-02 15:27:30.435   304   880 D CommandListener: Setting iface cfg
09-02 15:27:30.435   304   880 D CommandListener: Trying to bring down wlan0
,09-02 15:27:30.441   304   880 D CommandListener: Clearing all IP addresses on wlan0
,09-02 15:27:30.444  1043  1119 D Tethering: InitialState.processMessage what=4
09-02 15:27:30.445  1043  1119 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-02 15:27:30.459  1043  1377 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
09-02 15:27:30.455  8169  8169 W wpa_supplicant: type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-02 15:27:30.475  8169  8169 W wpa_supplicant: type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-02 15:27:30.485  1043  1377 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-02 15:27:30.485  1043  1377 E WifiStateMachine: useWiFiOffloading() : false
09-02 15:27:30.485  1043  1377 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-02 15:27:30.497  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-02 15:27:30.505  1928  1928 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
09-02 15:27:30.524  6878  6878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 15:27:30.527  1043  1043 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
09-02 15:27:30.539  8169  8169 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-02 15:27:30.553  1043  1377 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
09-02 15:27:30.553  1043  1377 D WifiMonitor: connecting to supplicant
09-02 15:27:30.558  7015  7015 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-02 15:27:30.558  7015  7015 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
,09-02 15:27:30.558  7015  7015 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-02 15:27:30.558  7015  7015 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-02 15:27:30.559  7015  7015 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-02 15:27:30.561  7015  7015 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-02 15:27:30.561  7015  7015 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
09-02 15:27:30.561  7015  7015 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-02 15:27:30.562  7015  7015 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-02 15:27:30.562  7015  7015 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-02 15:27:30.562  7015  7015 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
09-02 15:27:30.563  7015  7015 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-02 15:27:30.565  7015  7015 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-02 15:27:30.565  7015  7015 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-02 15:27:30.566  7015  7015 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-02 15:27:30.566  7015  7015 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-02 15:27:30.567  7015  7015 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-02 15:27:30.568  7015  7015 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-02 15:27:30.568  7015  7015 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-02 15:27:30.568  7015  7015 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-02 15:27:30.568  7015  7015 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-02 15:27:30.568  7015  7015 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-02 15:27:30.568  7015  7015 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-02 15:27:30.589  8169  8169 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-02 15:27:30.590  8169  8169 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,09-02 15:27:30.613  1043  1927 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=8187 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,09-02 15:27:30.645  8169  8169 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-02 15:27:30.737  8169  8169 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,09-02 15:27:30.739  1043  1562 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=8208 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
09-02 15:27:30.741  8169  8169 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
09-02 15:27:30.741  8169  8169 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
09-02 15:27:30.742  1043  1377 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
09-02 15:27:30.743  1043  8217 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
09-02 15:27:30.743  1043  8217 D WifiMonitor: Dropping event because (p2p0) is stopped
09-02 15:27:30.743  1043  1377 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
09-02 15:27:30.743  1043  8217 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
09-02 15:27:30.743  1043  8217 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
09-02 15:27:30.743  1043  8217 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
09-02 15:27:30.743  1043  8217 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
09-02 15:27:30.743  1043  1377 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
09-02 15:27:30.743  1043  1377 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
09-02 15:27:30.744  1043  1377 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
09-02 15:27:30.744  1043  1377 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-02 15:27:30.744  8187  8206 W FormManager: Network not available. Please check & try again.
09-02 15:27:30.744  1043  1377 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
09-02 15:27:30.745  1043  1377 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-02 15:27:30.745  1043  1377 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
09-02 15:27:30.745  1043  1377 D WifiNative-wlan0: doString: [DRIVER MACADDR]
09-02 15:27:30.746  1043  1377 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
09-02 15:27:30.746  1043  1377 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
09-02 15:27:30.746  1043  1377 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
09-02 15:27:30.746  1043  1377 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-02 15:27:30.746  1043  1377 E WifiStateMachine: useWiFiOffloading() : false
09-02 15:27:30.746  1043  1377 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-02 15:27:30.747  1043  1043 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 15:27:30.747  1043  1043 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 15:27:30.747  1043  1043 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 15:27:30.747  1043  1043 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 15:27:30.747  1043  1043 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-02 15:27:30.747  1043  1377 D WifiNative-wlan0: doBoolean: SET update_config 1
09-02 15:27:30.748  1043  1377 D WifiNative-wlan0: SET update_config 1: returned true
09-02 15:27:30.748  1043  1377 D WifiConfigStore: Loading config and enabling all networks 
09-02 15:27:30.748  1043  1377 D WifiNative-wlan0: doString: [LIST_NETWORKS]
09-02 15:27:30.748  1043  1377 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
09-02 15:27:30.749  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 15:27:30.,752  1928  1928 D WfdService: Waiting for WifiP2p enabling
09-02 15:27:30.752  1043  1377 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
,09-02 15:27:30.755  6878  6948 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 15:27:30.755  6878  6948 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 15:27:30.755  6878  6948 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 15:27:30.755  6878  6948 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 15:27:30.755  6878  6948 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 15:27:30.755  6878  6948 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 15:27:30.755  6878  6948 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 15:27:30.755  6878  6948 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-02 15:27:30.756  6878  6948 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-02 15:27:30.760  6878  6948 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
09-02 15:27:30.761  6878  6948 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
09-02 15:27:30.762  1043  1377 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
09-02 15:27:30.762  1043  1377 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-02 15:27:30.762  6878  6948 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@168c2670 Bundle[{}]
09-02 15:27:30.763  6878  6948 I io.jxcore.node.LifeCycleMonitor: start: OK
09-02 15:27:30.763  6878  6948 I io.jxcore.node.LifeCycleMonitor: stop: OK
09-02 15:27:30.764  6878  6948 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
09-02 15:27:30.764  6878  6948 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-02 15:27:30.765  1043  1043 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
09-02 15:27:30.765  1043  1395 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
09-02 15:27:30.765  6878  6878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 15:27:30.765  6878  6878 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 15:27:30.765  6878  6878 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 15:27:30.765  6878  6878 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 15:27:30.765  6878  6878 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 15:27:30.765  6878  6878 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 15:27:30.765  6878  6878 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 15:27:30.765  6878  6878 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-02 15:27:30.766  1043  1377 D WifiStateMachine: enableVerboseLogging : level 2
09-02 15:27:30.766  1043  1377 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
09-02 15:27:30.767  6878  6878 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-02 15:27:30.767  1043  1377 D WifiNative-wlan0: SET device_name g3_global_com: returned true
09-02 15:27:30.767  1043  1377 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
09-02 15:27:30.768  6878  6948 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
09-02 15:27:30.768  1043  1377 D WifiNative-wlan0: SET manufacturer LGE: returned true
09-02 15:27:30.768  1043  1377 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
09-02 15:27:30.768  6878  6948 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
09-02 15:27:30.768  1043  1377 D WifiNative-wlan0: SET model_name LG-D855: returned true
09-02 15:27:30.769  1043  1377 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
09-02 15:27:30.769  1043  1377 D WifiNative-wlan0: SET model_number LG-D855: returned true
09-02 15:27:30.769  1043  1377 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
09-02 15:27:30.769  1043  1377 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
09-02 15:27:30.769  1043  1377 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
09-02 15:27:30.770  1043  1377 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
09-02 15:27:30.770  1043  1377 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
09-02 15:27:30.770  1043  1377 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
09-02 15:27:30.771  1928  1928 D WfdsService: Supplicant Connection state is changed : true
09-02 15:27:30.771  7860  7860 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 15:27:30.771  1928  2260 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
09-02 15:27:30.771  1928  2260 D WfdsService: Set the WFDS Monitor: true
09-02 15:27:30.771  1928  2260 D WfdsMonitor: WfdsMonitorThread create
09-02 15:27:30.772  1928  2260 D WfdsMonitor: WFDS Monitor is created and started
09-02 15:27:30.772  1928  2260 D WfdsService: WiFi: Supplicant connection re-established
09-02 15:27:30.772  1043  1377 D WifiStateMachine: Setting OUI to DA-A1-19
09-02 15:27:30.772  1043  1377 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
09-02 15:27:30.772  1928  8228 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
09-02 15:27:30.772  1043  1377 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
09-02 15:27:30.772  6878  6948 I System.out: Running OutgoingSocketThread
09-02 15:27:30.772  1043  1377 D WifiNative-HAL: Setting external_sim to 1
09-02 15:27:30.772  1043  1377 D WifiNative-wlan0: doBoolean: SET external_sim 1
09-02 15:27:3,0.773  1928  8228 E CtrlSupplicant: Succeed to open control connection
09-02 15:27:30.773  1043  1377 D WifiNative-wlan0: SET external_sim 1: returned true
09-02 15:27:30.773  1043  1377 I WifiNative-HAL: startHal
09-02 15:27:30.773  1043  1377 D wifi    : setting scan oui 0x9538d060
09-02 15:27:30.773  1928  8228 E CtrlSupplicant: Succeed to open monitor connection
09-02 15:27:30.773  6878  8229 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 902)
09-02 15:27:30.773  1043  1377 D WifiStateMachine: Setting OUI to DA-A1-19
09-02 15:27:30.773  1928  8228 D WfdsMonitor: Supplicant connection established
09-02 15:27:30.773  1043  1377 I WifiNative-HAL: startHal
09-02 15:27:30.773  1043  1377 D wifi    : setting scan oui 0x9538d060
09-02 15:27:30.773  1928  2260 D WfdsService: Connected to the supplicant for wfds
09-02 15:27:30.774  1043  1377 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
09-02 15:27:30.774  1043  1377 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
09-02 15:27:30.774  1043  1377 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
09-02 15:27:30.774  8169  8169 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
09-02 15:27:30.775  1043  1377 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
09-02 15:27:30.775  1043  1377 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-02 15:27:30.775  6878  8229 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 44183
09-02 15:27:30.775  6878  8229 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
09-02 15:27:30.775  8169  8169 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-02 15:27:30.776  1043  1377 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-02 15:27:30.776  1043  1377 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
09-02 15:27:30.776  8169  8169 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
,09-02 15:27:30.776  1043  1377 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
09-02 15:27:30.777  1043  1377 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-02 15:27:30.777  8169  8169 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-02 15:27:30.777  1043  1377 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-02 15:27:30.777  1043  1377 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-02 15:27:30.777  8169  8169 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-02 15:27:30.778  1043  1377 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-02 15:27:30.778  1043  1377 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
09-02 15:27:30.778  8169  8169 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
09-02 15:27:30.778  1043  1377 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
09-02 15:27:30.778  1043  1377 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-02 15:27:30.778  8169  8169 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-02 15:27:30.779  1043  1377 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-02 15:27:30.779  8187  8207 V FormManager: Network unavailable.
09-02 15:27:30.780  1043  1377 E WifiNative: : [204,041,528 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
09-02 15:27:30.780  1043  1377 D WifiNative-wlan0: doBoolean: RECONNECT
,09-02 15:27:30.780  1043  1377 D WifiNative-wlan0: RECONNECT: returned true
09-02 15:27:30.781  1043  1377 D WifiNative-wlan0: doString: [STATUS]
09-02 15:27:30.781  8187  8207 V FormManager: Network unavailable.
09-02 15:27:30.781  1043  8217 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
09-02 15:27:30.781  1043  8217 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
09-02 15:27:30.781  1043  1377 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-02 15:27:30.781  1043  1377 D WifiNative-wlan0: doBoolean: SET ps 1
09-02 15:27:30.782  1043  1377 D WifiNative-wlan0: SET ps 1: returned true
09-02 15:27:30.782  1043  1374 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
09-02 15:27:30.783  1043  1043 D WifiScanningService: SCAN_AVAILABLE : 3
09-02 15:27:30.783  1043  1043 D RttService: SCAN_AVAILABLE : 3
09-02 15:27:30.783  1043  1542 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-02 15:27:30.783  1043  1377 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
09-02 15:27:30.783  1043  1542 I WifiNative-HAL: startHal
09-02 15:27:30.783  1043  1542 D wifi    : getting scan capabilities on interface[1] = 0x9538d060
09-02 15:27:30.783  1043  1542 D wifi    : failed to get capabilities : -3
09-02 15:27:30.783  1043  1542 E WifiScanningService: could not get scan capabilities
09-02 15:27:30.783  1043  1544 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-02 15:27:30.783  1043  1377 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
09-02 15:27:30.784   304   880 D CommandListener: Setting iface cfg
09-02 15:27:30.784   304   880 D CommandListener: Trying to bring up p2p0
09-02 15:27:30.784  1043  1377 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
09-02 15:27:30.784  1043  1374 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-02 15:27:30.784  1043  1374 D LGWifiP2pService: P2pEnablingState
09-02 15:27:30.784  1043  1374 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
09-02 15:27:30.784  1043  1374 D LGWifiP2pService: P2p socket connection successful
09-02 15:27:30.784  1043  1374 D LGWifiP2pService: P2pEnabledState
09-02 15:27:30.784  1043  1377 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
09-02 15:27:30.784  1043  1374 D LGWifiP2pService: sending p2p connection changed broadcast
09-02 15:27:30.785  1043  1377 E WifiStateMachine:  DisconnectedState what:132106 1 0
09-02 15:27:30.785  1043  1377 E WifiStateMachine:  ConnectModeState what:132106 1 0
09-02 15:27:30.785  1928  1928 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
09-02 15:27:30.785  1928  1928 D WfdsService: WifiP2pState is changed : true
09-02 15:27:30.785  1928  2260 D WfdsService: Receive the WFDS_ENABLE Method
09-02 15:27:30.785  1928  2260 D WfdsService: Set the WFDS Monitor: true
09-02 15:27:30.785  1928  2260 D WfdsService: Connected to the supplicant for wfds
09-02 15:27:30.785  1928  2260 D WfdsJNI : doCommand: WFDS_SET TRUE
09-02 15:27:30.785  1043  1377 E WifiStateMachine:  DriverStartedState what:132106 1 0
09-02 15:27:30.785  8169  8169 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
09-02 15:27:30.785  1043  1377 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
09-02 15:27:30.786  8169  8169 E wpa_supplicant: nWIFIDualbandAPConnection: 1
09-02 15:27:30.786  1928  2260 D WfdsService: selectPreferredScanChannel [36]
09-02 15:27:30.786  1043  1374 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
09-02 15:27:30.786  1928  2260 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 0,2:9a:02:7f:fb:5d
09-02 15:27:30.786  1043  1374 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
09-02 15:27:30.786  1043  1374 D WifiNative-p2p0: doBoolean: SET device_name G3
09-02 15:27:30.786  1043  1374 D WifiNative-p2p0: SET device_name G3: returned true
09-02 15:27:30.786  1043  1374 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
09-02 15:27:30.786  1043  1374 D LGWifiP2pService: before postfix = G3
09-02 15:27:30.786  1043  1374 D WifiServerServiceExt: postfix byte check : 2
09-02 15:27:30.786  1043  1374 D LGWifiP2pService: after postfix = G3
09-02 15:27:30.786  1043  1374 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
09-02 15:27:30.787  1043  1374 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
09-02 15:27:30.787  1043  1374 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
09-02 15:27:30.787  1928  1928 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
09-02 15:27:30.787  1043  1377 E WifiStateMachine:  DisconnectedState what:132096 -100 0
09-02 15:27:30.787  1043  1374 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
09-02 15:27:30.787  1043  1374 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
09-02 15:27:30.787  1928  1928 D WfdsService: isConnected: false
09-02 15:27:30.787  1043  1377 E WifiStateMachine:  ConnectModeState what:132096 -100 0
09-02 15:27:30.787  1043  1377 E WifiStateMachine:  DriverStartedState what:132096 -100 0
09-02 15:27:30.787  1043  1377 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
,09-02 15:27:30.787  8169  8169 E wpa_supplicant: disconnect_rssi_lvl: -100
09-02 15:27:30.788  1043  1374 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
09-02 15:27:30.788  1043  1377 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
09-02 15:27:30.788  1043  1374 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
09-02 15:27:30.788  1043  1374 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
09-02 15:27:30.788  1043  1374 D WifiNative-HAL: p2pGetDeviceAddress
09-02 15:27:30.788  1043  1374 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
09-02 15:27:30.788  1043  1377 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
09-02 15:27:30.788  1043  1374 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
09-02 15:27:30.788  1043  1377 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
09-02 15:27:30.788  1043  1374 D WifiNative-p2p0: doBoolean: P2P_FLUSH
09-02 15:27:30.789  1043  1377 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
09-02 15:27:30.789  1043  1374 D WifiNative-p2p0: P2P_FLUSH: returned true
09-02 15:27:30.789  1043  1374 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
09-02 15:27:30.789  1043  1374 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
09-02 15:27:30.789  1043  1374 D WifiNative-p2p0: doString: [LIST_NETWORKS]
09-02 15:27:30.789  1043  1374 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
09-02 15:27:30.789  1043  1374 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
09-02 15:27:30.792  1928  1928 I WfdStateTracker: handleP2pThisDeviceChanged
09-02 15:27:30.792  1928  1928 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
09-02 15:27:30.792  1928  1928 D WfdsService: Update P2p Interface State: 3
09-02 15:27:30.797  1043  1926 I ActivityManager: Killing 7296:com.android.chrome/u0a57 (adj 15): empty #17
09-02 15:27:30.801  1043  1374 D WifiNative-p2p0: SAVE_CONFIG: returned true
,09-02 15:27:30.801  1043  1374 D LGWifiP2pService: sending p2p persistent groups changed broadcast
,09-02 15:27:30.802  8169  8169 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-02 15:27:30.803  8169  8169 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-02 15:27:30.803  8169  8169 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-02 15:27:30.803  8169  8169 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 15:27:30.803  1928  8228 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-02 15:27:30.803  8169  8169 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 15:27:30.804  1928  8228 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-02 15:27:30.804  1043  8217 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-02 15:27:30.804  1043  8217 E WifiMonitor: WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-02 15:27:30.804  1043  8217 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-02 15:27:30.804  1043  8217 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-02 15:27:30.804  1043  8217 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-02 15:27:30.804  1043  8217 E WifiMonitor: WifiMonitor:p2p0 cnt=47 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 15:27:30.804  1043  8217 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 15:27:30.804  1043  8217 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 15:27:30.804  1043  8217 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-02 15:27:30.804  1043  8217 E WifiMonitor: WifiMonitor:p2p0 cnt=48 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 15:27:30.804  1043  8217 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 15:27:30.804  1043  8217 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 15:27:30.805  1043  1377 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
09-02 15:27:30.805  1043  1377 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
09-02 15:27:30.806  1043  1377 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
09-02 15:27:30.806  1043  1377 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
09-02 15:27:30.806  1043  1377 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
09-02 15:27:30.806  8169  8169 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
09-02 15:27:30.806  8169  8169 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-02 15:27:30.806  1043  8217 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
09-02 15:27:30.806  1043  8217 E WifiMonitor: WifiMonitor:wlan0 cnt=49 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-02 15:27:30.806  1043  8217 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-02 15:27:30.806  1043  8217 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-02 15:27:30.807  1043  1377 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
09-02 15:27:30.807  1043  1377 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
09-02 15:27:30.807  1043  1377 D WifiNative-wlan0: BSS_FLUSH 0: returned true
09-02 15:27:30.807  1043  1377 D WifiNative-wlan0: doBoolean: SCAN
09-02 15:27:30.808  1043  1377 D WifiNative-wlan0: SCAN: returned false
09-02 15:27:30.808  1043  1377 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=204070  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-02 15:27:30.820  8208  8208 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-02 15:27:30.854  1043  1374 D LGWifiP2pService: InactiveState
09-02 15:27:30.855  1043  1374 D LGWifiP2pService: InactiveState{ when=-65ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-02 15:27:30.855  1043  1374 D LGWifiP2pService: P2pEnabledState{ when=-65ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
,09-02 15:27:30.855  1043  1374 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
09-02 15:27:30.856  8169  8169 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-02 15:27:30.857  8169  8169 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-02 15:27:30.857  1928  8228 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-02 15:27:30.857  1043  8217 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-02 15:27:30.857  1043  8217 E WifiMonitor: WifiMonitor:p2p0 cnt=50 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-02 15:27:30.857  1043  8217 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-02 15:27:30.857  1043  8217 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
,09-02 15:27:30.859  8169  8169 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-02 15:27:30.859  8169  8169 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 15:27:30.859  1928  8228 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-02 15:27:30.860  1043  8217 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-02 15:27:30.860  1043  8217 E WifiMonitor: WifiMonitor:p2p0 cnt=51 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 15:27:30.860  1043  8217 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 15:27:30.860  1043  8217 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 15:27:30.861  1043  1374 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
09-02 15:27:30.861  1043  1374 D LGWifiP2pService: InactiveState{ when=-56ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-02 15:27:30.861  1043  1374 D LGWifiP2pService: P2pEnabledState{ when=-56ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-02 15:27:30.861  8169  8169 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 15:27:30.861  1928  8228 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-02 15:27:30.861  1043  1374 D LGWifiP2pService: InactiveState{ when=-6ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-02 15:27:30.861  1043  1374 D LGWifiP2pService: P2pEnabledState{ when=-7ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-02 15:27:30.862  1043  1374 D LGWifiP2pService: DefaultState{ when=-7ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-02 15:27:30.862  1043  1374 D LGWifiP2pService: InactiveState{ when=-7ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-02 15:27:30.862  1043  1374 D LGWifiP2pService: P2pEnabledState{ when=-7ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-02 15:27:30.862  1043  1374 D LGWifiP2pService: DefaultState{ when=-7ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-02 15:27:30.862  1043  1374 D LGWifiP2pService: InactiveState{ when=-2ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-02 15:27:30.862  1043  1374 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-02 15:27:30.862  1043  1374 D LGWifiP2pService: DefaultState{ when=-2ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-02 15:27:30.863  1043  1374 D LGWifiP2pService: InactiveState{ when=-2ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-02 15:27:30.863  1043  1374 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-02 15:27:30.863  1043  1374 D LGWifiP2pService: DefaultState{ when=-2ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-02 15:27:30.863  1043  8217 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-02 15:27:30.863  1043  8217 E WifiMonitor: WifiMonitor:p2p0 cnt=52 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 15:27:30.863  1043  8217 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 15:27:30.863  1043  8217 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-02 15:27:30.863  1928  2260 W WfdsService: DefaultState - msg [9441285] is not handled
09-02 15:27:30.863  1043  1043 E WifiServerServiceExt: No p2p device connected
09-02 15:27:30.864  1043  1377 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=204126  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-02 15:27:30.865  1043  1043 W Settings: Se,tting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 15:27:30.866  1043  1043 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 15:27:30.866  1043  1377 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-02 15:27:30.866  1043  1043 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-02 15:27:30.867  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 15:27:30.867  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-02 15:27:30.868  1043  1377 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-02 15:27:30.869  7015  7015 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-02 15:27:30.869  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 15:27:30.869  1043  1377 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-02 15:27:30.870  1043  1060 W libprocessgroup: failed to open /acct/uid_10057/pid_7296/cgroup.procs: No such file or directory
09-02 15:27:30.870  1043  1377 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-02 15:27:30.871  1043  1377 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-02 15:27:30.873  1043  1043 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-02 15:27:30.873  1043  1043 D WifiServerServiceExt: setSupplicantStateSCANNING
,09-02 15:27:30.879  7015  7015 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 15:27:30.879  1043  1873 I ActivityManager: Killing 7317:com.lge.drmservice/u0a62 (adj 15): empty #17
09-02 15:27:30.923  1043  1562 W libprocessgroup: failed to open /acct/uid_10062/pid_7317/cgroup.procs: No such file or directory
,09-02 15:27:30.962  8208  8208 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-02 15:27:30.974  7015  7015 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-02 15:27:30.978  8187  8233 W FormManager: Network not available. Please check & try again.
09-02 15:27:30.982  7015  7015 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 15:27:30.995  8187  8234 V FormManager: Network unavailable.
,09-02 15:27:31.001  8187  8234 V FormManager: Network unavailable.
09-02 15:27:31.005  4743  4743 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-02 15:27:31.006  4743  4743 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-02 15:27:31.008  4743  4743 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-02 15:27:31.013  4743  4743 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-02 15:27:31.019  4743  8235 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-02 15:27:31.024  4743  8236 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-02 15:27:31.025  4743  8236 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,09-02 15:27:31.065  1043  1998 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=8237 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,09-02 15:27:31.205  8237  8237 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-02 15:27:31.205  8237  8237 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,09-02 15:27:31.218  8237  8237 V [BNRBootReceiver]: Boot Receiver Return
09-02 15:27:31.219  8237  8237 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,09-02 15:27:31.277  1043  1927 I ActivityManager: Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=8258 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
09-02 15:27:31.278  1043  1927 I ActivityManager: Killing 7341:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
,09-02 15:27:31.291  8169  8169 E wpa_supplicant: USIM:  scard_init function
,09-02 15:27:31.293  8169  8169 I wpa_supplicant: Trying to associate with SSID 'NG700'
09-02 15:27:31.294  1043  8217 E WifiMonitor: WifiMonitor:wlan0 cnt=53 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
09-02 15:27:31.294  1043  8217 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
09-02 15:27:31.295  1043  8217 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
09-02 15:27:31.295  1043  8217 E WifiMonitor: WifiMonitor:wlan0 cnt=54 dispatchEvent: WPS-AP-AVAILABLE 
09-02 15:27:31.295  1043  8217 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
09-02 15:27:31.295  1043  8217 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
09-02 15:27:31.295  1043  8217 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
09-02 15:27:31.298  1043  1377 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
09-02 15:27:31.298  1043  1377 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
09-02 15:27:31.299  1043  1377 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
09-02 15:27:31.299  1043  1377 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
09-02 15:27:31.299  1043  1377 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
09-02 15:27:31.338  1043  1377 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 55 0 rt=204600  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,09-02 15:27:31.344  1043  1962 W libprocessgroup: failed to open /acct/uid_10085/pid_7341/cgroup.procs: No such file or directory
09-02 15:27:31.345  1043  1377 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 55 0 rt=204607  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
09-02 15:27:31.348  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 15:27:31.348  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-02 15:27:31.350  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-02 15:27:31.352  1043  1043 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 15:27:31.352  1043  1043 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 15:27:31.352  1043  1043 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-02 15:27:31.353  1043  1043 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 15:27:31.353  1043  1043 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 15:27:31.353  1043  1043 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-02 15:27:31.356  1043  1043 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-02 15:27:31.356  1043  1043 D WifiServerServiceExt: setSupplicantStateASSOCIATING
09-02 15:27:31.367  8258  8258 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-02 15:27:31.373  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 15:27:31.373  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-02 15:27:31.374  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 15:27:31.390  8258  8258 D PluginManager: init()
,09-02 15:27:31.425  8169  8169 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-02 15:27:31.429  1043  8217 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
09-02 15:27:31.429  1043  8217 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
09-02 15:27:31.430  1043  8217 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
09-02 15:27:31.430  1043  8217 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: Associated with f4:f2:6d:22:99:3e
09-02 15:27:31.430  1043  8217 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-02 15:27:31.430  1043  8217 E WifiMonitor: WifiMonitor:wlan0 cnt=58 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-02 15:27:31.430  1043  1377 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=204692  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-02 15:27:31.431  1043  1377 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=204693  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-02 15:27:31.431  1043  1377 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=204693
09-02 15:27:31.432  1043  1377 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=204694
09-02 15:27:31.432  1043  1377 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=204694
09-02 15:27:31.433  1043  1377 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=204695
09-02 15:27:31.433  1043  1377 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=204695
09-02 15:27:31.434  1043  1377 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=204696  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
09-02 15:27:31.434  1043  1119 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-02 15:27:31.435  8169  8169 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-02 15:27:31.435  8169  8169 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-02 15:27:31.437  1043  8217 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-02 15:27:31.437  1043  8217 E WifiMonitor: WifiMonitor:wlan0 cnt=59 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-02 15:27:31.437  1043  8217 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
09-02 15:27:31.437  1043  8217 E WifiMonitor: WifiMonitor:wlan0 cnt=60 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-02 15:27:31.437  1043  8217 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-02 15:27:31.437  1043  8217 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
09-02 15:27:31.437  1043  8217 E WifiMonitor: WifiMonitor:wlan0 cnt=61 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-02 15:27:31.438  1043  8217 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-02 15:27:31.438  1043  8217 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-02 15:27:31.438  1043  8217 E WifiMonitor: WifiMonitor:wlan0 cnt=62 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,09-02 15:27:31.445  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-02 15:27:31.445  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-02 15:27:31.447  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 15:27:31.448  1043  1043 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 15:27:31.449  1043  1043 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 15:27:31.449  1043  1043 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-02 15:27:31.450  1043  1377 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=204712  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
09-02 15:27:31.451  1043  1377 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
09-02 15:27:31.452  1043  1377 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
09-02 15:27:31.453  1043  1377 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
09-02 15:27:31.453  1043  1377 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
09-02 15:27:31.453  1043  1377 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-02 15:27:31.454  1043  1377 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=204716  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-02 15:27:31.455  1043  1377 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=204717  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-02 15:27:31.455  1043  1377 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=204717
09-02 15:27:31.455  1043  1043 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 15:27:31.455  1043  1043 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 15:27:31.455  1043  1043 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
09-02 15:27:31.455  1043  1043 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-02 15:27:31.456  1043  1043 D WifiServerServiceExt: setSupplicantStateASSOCIATED
09-02 15:27:31.456  1043  1377 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=204718
09-02 15:27:31.456  1043  1377 D WifiNative-wlan0: doString: [STATUS]
09-02 15:27:31.457  1043  8217 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-02 15:27:31.457  1043  8217 E WifiMonitor: WifiMonitor:wlan0 cnt=63 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-02 15:27:31.458  1043  1377 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-02 15:27:31.460  1043  1377 I WifiServiceExtension: setVHTCapabilityType  : false
,09-02 15:27:31.465  1043  1377 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
09-02 15:27:31.465  1043  1377 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
09-02 15:27:31.468  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 15:27:31.468  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-02 15:27:31.469  1043  1043 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 15:27:31.469  1043  1043 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 15:27:31.469  1043  1043 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-02 15:27:31.471  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 15:27:31.473  1043  1043 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 15:27:31.473  1043  1043 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 15:27:31.473  1043  1043 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-02 15:27:31.476  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 15:27:31.476  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-02 15:27:31.477  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 15:27:31.478  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 15:27:31.478  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-02 15:27:31.479  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 15:27:31.483  1043  1377 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
09-02 15:27:31.483  1043  1431 D ConnectivityService: Got NetworkAgent Messenger
09-02 15:27:31.483  1043  1377 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-02 15:27:31.483  1043  1377 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-02 15:27:31.483  1043  1431 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
09-02 15:27:31.483  1043  1431 D ConnectivityService: NetworkAgent connected
09-02 15:27:31.484  1043  1377 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-02 15:27:31.484  1043  1377 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-02 15:27:31.490  1043  1377 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-02 15:27:31.490  1043  1377 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-02 15:27:31.490  1043  1377 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
,09-02 15:27:31.491  1043  1377 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-02 15:27:31.491  1043  1377 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-02 15:27:31.497  1043  1377 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-02 15:27:31.500   304   880 D CommandListener: Setting iface cfg
09-02 15:27:31.502  1043  1377 E WifiStateMachine: Start Dhcp Watchdog 3
09-02 15:27:31.502  1043  8276 D DhcpStateMachine: StoppedState
09-02 15:27:31.502  1043  8276 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
09-02 15:27:31.503  1043  8276 D DhcpStateMachine: WaitBeforeStartState
,09-02 15:27:31.503  1043  1377 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 62 0 rt=204765  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-02 15:27:31.503  1043  1377 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 62 0 rt=204765  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-02 15:27:31.504  1043  1377 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 62 0 rt=204766  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-02 15:27:31.505  1043  1043 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-02 15:27:31.505  1043  1043 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
09-02 15:27:31.506  1043  1043 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-02 15:27:31.506  1043  1043 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
09-02 15:27:31.508  1043  1377 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=204770  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-02 15:27:31.511  1043  1377 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=204773  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-02 15:27:31.512  1043  1377 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=204774  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-02 15:27:31.513  1043  1377 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:14010] from screen [on:0 period:-350931015] gl rssi=-47 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-02 15:27:31.514  1043  1377 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-350931014] gl rssi=-47 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-02 15:27:31.514  1043  1377 D WifiNative-wlan0: doString: [SIGNAL_POLL]
09-02 15:27:31.518  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 15:27:31.519  1043  1431 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,09-02 15:27:31.519  1043  1377 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 15:27:31.519  1043  1377 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 15:27:31.520  1043  1377 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 15:27:31.520  1043  1377 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 15:27:31.521  1043  1377 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 15:27:31.521  1043  1377 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 15:27:31.521  1043  1431 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
09-02 15:27:31.522  1043  1377 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=136,0,0
09-02 15:27:31.522  1043  1377 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=136,0,0
09-02 15:27:31.522  1043  1377 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
09-02 15:27:31.522  8169  8169 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
09-02 15:27:31.523  1043  1377 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
09-02 15:27:31.523  1043  1377 D WifiNative-wlan0: doBoolean: SET ps 0
09-02 15:27:31.523  1043  1377 D WifiNative-wlan0: SET ps 0: returned true
09-02 15:27:31.523  1043  1377 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
09-02 15:27:31.523  8169  8169 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
09-02 15:27:31.524  1043  1377 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
09-02 15:27:31.524  1043  1377 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
09-02 15:27:31.524  1043  1377 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-02 15:27:31.524  1043  1374 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@37afe8ae target=com.android.internal.util.StateMachine$SmHandler }
09-02 15:27:31.524  1043  1374 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@37afe8ae target=com.android.internal.util.StateMachine$SmHandler }
09-02 15:27:31.524  1043  1377 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-02 15:27:31.524  1043  8276 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
09-02 15:27:31.524  1043  8276 D DhcpStateMachine: DHCP Start wake lock is acquired.
09-02 15:27:31.525   304   880 D CommandListener: Setting iface cfg
09-02 15:27:31.525   304   880 D CommandListener: Trying to bring up wlan0
09-02 15:27:31.526  1043  1377 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
09-02 15:27:31.527  1043  1043 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-02 15:27:31.527  1043  1043 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-02 15:27:31.529  1043  1377 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 15:27:31.529  1043  1377 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 15:27:31.530  1043  1377 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 15:27:31.530  1043  1377 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 15:27:31.531  1043  1377 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-02 15:27:31.531  1043  1377 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
,09-02 15:27:31.536  1043  1377 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
,09-02 15:27:31.536  1043  1431 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
09-02 15:27:31.536  1043  1043 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-02 15:27:31.536  1043  1377 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
09-02 15:27:31.536  1043  1043 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-02 15:27:31.537  1043  1377 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-02 15:27:31.537  1043  1374 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-02 15:27:31.537  1043  1374 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-02 15:27:31.537  8169  8169 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-02 15:27:31.538  1043  1377 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-02 15:27:31.538  1043  1377 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
09-02 15:27:31.538  8169  8169 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
09-02 15:27:31.538  1043  1377 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
09-02 15:27:31.538  1043  1377 D WifiNative-wlan0: doBoolean: SET ps 1
09-02 15:27:31.554  1043  1377 D WifiNative-wlan0: SET ps 1: returned true
,09-02 15:27:31.555  1043  1431 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
09-02 15:27:31.555  1043  1377 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-02 15:27:31.556  1043  1377 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-02 15:27:31.556  1043  1377 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
09-02 15:27:31.556  1043  1431 D ConnectivityService: ignoring duplicate network state non-change
,09-02 15:27:31.560  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 15:27:31.560  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-02 15:27:31.564  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 15:27:31.567  1043  1043 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 15:27:31.567  1043  1043 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 15:27:31.567  1043  1043 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-02 15:27:31.569  1043  1431 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-02 15:27:31.570  1043  1431 D ConnectivityService: Adding iface wlan0 to network 102
09-02 15:27:31.576  1043  1043 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 15:27:31.577  1043  1043 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 15:27:31.577  1043  1043 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-02 15:27:31.579  1043  1043 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-02 15:27:31.580  1043  1377 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-02 15:27:31.586  1928  1928 V WfdStateTracker: handleWifiStateChangedEvent: 1
09-02 15:27:31.586  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 15:27:31.586  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-02 15:27:31.587  1043  1043 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 15:27:31.587  1043  1043 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 15:27:31.587  1043  1043 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-02 15:27:31.587  1043  1043 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-02 15:27:31.590  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 15:27:31.592  1043  1043 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 15:27:31.592  1043  1043 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 15:27:31.592  1043  1043 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-02 15:27:31.593  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 15:27:31.593  1589  1589 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-02 15:27:31.593  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 15:27:31.595  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 15:27:31.595  1589  1589 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-02 15:27:31.596  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-02 15:27:31.608  1043  1431 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-02 15:27:31.609  1043  1431 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
09-02 15:27:31.611  1043  1431 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,09-02 15:27:31.611   304   880 E Netd    : netlink response contains error (File exists)
09-02 15:27:31.611  1043  1431 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
09-02 15:27:31.612  1043  1431 D ConnectivityService: addLocalRoutetoDefaultNetwork
09-02 15:27:31.612  1043  1431 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 102
09-02 15:27:31.612  1043  1431 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
09-02 15:27:31.613  1043  1431 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-02 15:27:31.613  1043  1431 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-02 15:27:31.613  1043  1431 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
09-02 15:27:31.613  1043  1431 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
09-02 15:27:31.613  1043  1431 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-02 15:27:31.613  1043  8275 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
09-02 15:27:31.613  1043  8275 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
09-02 15:27:31.613  1043  1431 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-02 15:27:31.613  1043  1431 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-02 15:27:31.613  1043  8275 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-02 15:27:31.613  1043  1431 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 15:27:31.613  1043  1431 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
09-02 15:27:31.613  1043  1431 D ConnectivityService: currentScore = 0, newScore = 20
09-02 15:27:31.613  1043  8275 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
09-02 15:27:31.613  1043  1431 D ConnectivityService:    accepting network in place of null
09-02 15:27:31.613  1043  1431 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 15:27:31.613  1043  1377 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 15:27:31.614  1043  1377 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-02 15:27:31.615  1836  1836 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 15:27:31.615  1836  1836 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-02 15:27:31.617   304  8286 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
09-02 15:27:31.618  1043  1431 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe8,0::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
09-02 15:27:31.618  1043  1431 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
09-02 15:27:31.618  1043  1431 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-02 15:27:31.619  1043  1043 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
09-02 15:27:31.619  1043  1043 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-02 15:27:31.619  1043  1043 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-02 15:27:31.619  1043  1043 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-02 15:27:31.622  1043  1431 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-02 15:27:31.622  1043  1431 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
09-02 15:27:31.622  1043  1431 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
09-02 15:27:31.623  1043  1431 D ConnectivityService: validation of new default Network = false
09-02 15:27:31.623  1043  1431 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
09-02 15:27:31.623  1043  1431 D DSQN    : enableDataServiceNotify 
09-02 15:27:31.623  1043  1431 D DSQN    : start dsqn bin
,09-02 15:27:31.630  1043  1431 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
09-02 15:27:31.631  1043  1431 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 15:27:31.631  1043  1431 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-02 15:27:31.631  1043  1431 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-02 15:27:31.625  8287  8287 W dsqn    : type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-02 15:27:31.631  1589  2084 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-02 15:27:31.625  8287  8287 W dsqn    : type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-02 15:27:31.643  8287  8287 E DSQN    : DSQN ssw
09-02 15:27:31.643  1043  1373 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
,09-02 15:27:31.649  1589  1589 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-02 15:27:31.650  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 15:27:31.651  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 15:27:31.685   304  8286 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,09-02 15:27:31.717   304  8286 D libc-netbsd: res_queryN name = clients3.google.com succeed
,09-02 15:27:31.727  1043  8276 D DhcpStateMachine: DHCPV4 request on wlan0
09-02 15:27:31.728  1043  8276 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
09-02 15:27:31.728  1043  8276 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
09-02 15:27:31.725  8291  8291 W dhcpcd  : type=1400 audit(0.0:193): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-02 15:27:31.725  8291  8291 W dhcpcd  : type=1400 audit(0.0:194): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-02 15:27:31.746   304   879 D LGDataListener: argv[0]=dsqncommand
09-02 15:27:31.746   304   879 D LGDataListener: argv[1]=wlan0
09-02 15:27:31.746   304   879 D LGDataListener: argv[2]=1
09-02 15:27:31.746   304   879 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
09-02 15:27:31.747  1043  1117 D DSQN    : DSQM DsqnNotification wlan0  1
09-02 15:27:31.747  1043  1117 D DSQN    : start to monitor internet connection
09-02 15:27:31.757  8291  8291 I dhcpcd  : version 5.5.6 starting
,09-02 15:27:31.762  8291  8291 E dhcpcd  : get_duid: m
09-02 15:27:31.762  8291  8291 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
09-02 15:27:31.762  8291  8291 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
09-02 15:27:31.773  6878  6948 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 903)
09-02 15:27:31.773  6878  6948 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 903)
,09-02 15:27:31.775  6878  6948 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 908)
09-02 15:27:31.776  6878  6948 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
09-02 15:27:31.776  6878  6948 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 909)
09-02 15:27:31.778  1043  8275 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 02 Sep 2016 13:27:31 GMT], X-Android-Received-Millis=[1472822851777], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472822851745]}
09-02 15:27:31.778  1043  8275 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
09-02 15:27:31.778  1043  8275 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
09-02 15:27:31.778  1043  1431 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
09-02 15:27:31.778  1043  1431 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
09-02 15:27:31.778  1043  1431 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-02 15:27:31.778  1043  1431 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-02 15:27:31.778  1043  1431 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-02 15:27:31.778  1043  1431 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
09-02 15:27:31.779  6878  6948 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-02 15:27:31.779  1043  1431 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
09-02 15:27:31.779  6878  6948 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@190783ff added. We now have 2 listener(s)
09-02 15:27:31.779  1043  1431 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 15:27:31.779  1043  1431 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-02 15:27:31.779  1043  1926 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 15:27:31.779  1043  1431 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-02 15:27:31.779  1043  1431 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 15:27:31.779  1043  1377 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 15:27:31.779  1043  1431 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-02 15:27:31.780  1043  1377 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-02 15:27:31.780  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-02 15:27:31.780  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 15:27:31.780  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-02 15:27:31.780  6878  6948 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
0,9-02 15:27:31.780  6878  6948 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8a515cc added. We now have 9 listener(s)
09-02 15:27:31.780  6878  6948 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 15:27:31.781  6878  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-02 15:27:31.781  1589  2084 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-02 15:27:31.781  1836  1836 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 15:27:31.782  1836  1836 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-02 15:27:31.783  6878  6948 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 15:27:31.787  6878  6948 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 15:27:31.787  6878  6948 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 15:27:31.787  6878  6948 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 15:27:31.787  6878  6948 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 15:27:31.787  6878  6948 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 15:27:31.787  6878  6948 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 15:27:31.787  6878  6948 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 15:27:31.787  6878  6948 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-02 15:27:31.789  6878  6948 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-02 15:27:31.789  6878  6948 D io.jxcore.node.ConnectivityMonitor: start: OK
09-02 15:27:31.789  6878  6948 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-02 15:27:31.789  6878  6948 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@11c6bf2a added. We now have 3 listener(s)
09-02 15:27:31.791  1043  2018 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-02 15:27:31.796  6878  6878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 15:27:31.798  6878  6878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 15:27:31.799  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-02 15:27:31.799  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 15:27:31.799  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-02 15:27:31.799  6878  6948 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 15:27:31.799  6878  6948 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@245a611b added. We now have 10 listener(s)
09-02 15:27:31.799  6878  6948 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 15:27:31.799  6878  6948 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 15:27:31.800  6878  6948 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 15:27:31.800  6878  6948 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 15:27:31.800  6878  6948 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 15:27:31.800  6878  6948 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:27:31.800  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 15:27:31.800  6878  6948 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-02 15:27:31.800  6878  6948 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@190783ff removed from the list
09-02 15:27:31.800  6878  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:27:31.800  6878  6948 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8a515cc removed from the list
09-02 15:27:31.800  6878  6948 D io.jxcore.node.ConnectivityMonitor: stop
09-02 15:27:31.800  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:27:31.801  1589  1589 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-02 15:27:31.802  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 15:27:31.803  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-02 15:27:31.804  6878  6948 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:27:31.804  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 15:27:31.806  6878  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 15:27:31.806  6878  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 15:27:31.806  6878  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:27:31.806  6878  6948 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8a515cc not in the list
09-02 15:27:31.806  6878  6948 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:27:31.806  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:27:31.807  6878  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 15:27:31.807  6878  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 15:27:31.807  6878  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:27:31.807  6878  6948 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@245a611b removed from the list
09-02 15:27:31.807  6878  6948 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 15:27:31.807  6878  6948 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:27:31.807  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:27:31.807  6878  6948 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-02 15:27:31.807  6878  6948 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@11c6bf2a removed from the list
09-02 15:27:31.807  6878  6948 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-02 15:27:31.807  6878  6948 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@39f3c2b8 added. We now have 2 listener(s)
09-02 15:27:31.808  1043  1979 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 15:27:31.809  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-02 15:27:31.809  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 15:27:31.809  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-02 15:27:31.809  6878  6948 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 15:27:31.809  6878  6948 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@46e2891 added. We now have 9 listener(s)
09-02 15:27:31.809  6878  6948 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 15:27:31.810  6878  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-02 15:27:31.811  6878  6948 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 15:27:31.813  6878  6948 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 15:27:31.813  6878  6948 V io.jxcore.node.C,onnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 15:27:31.813  6878  6948 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 15:27:31.813  6878  6948 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 15:27:31.813  6878  6948 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 15:27:31.813  6878  6948 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 15:27:31.813  6878  6948 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 15:27:31.813  6878  6948 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-02 15:27:31.815  6878  6948 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-02 15:27:31.815  6878  6948 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-02 15:27:31.817  6878  6948 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-02 15:27:31.817  6878  6948 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3733f3f7 added. We now have 3 listener(s)
09-02 15:27:31.818  1043  2037 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 15:27:31.818  6878  6878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 15:27:31.819  6878  6878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 15:27:31.821  8291  8291 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-02 15:27:31.821  8291  8291 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-02 15:27:31.821  8291  8291 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-02 15:27:31.821  8291  8291 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
09-02 15:27:31.821  8291  8291 D dhcpcd  : wlan0: sending REQUEST (xid 0xc3c880de), next in 4.39 seconds
09-02 15:27:31.821  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-02 15:27:31.822  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 15:27:31.822  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-02 15:27:31.822  6878  6948 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 15:27:31.822  6878  6948 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d7e5264 added. We now have 10 listener(s)
09-02 15:27:31.822  6878  6948 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 15:27:31.822  6878  6948 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-02 15:27:31.822  6878  6948 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-02 15:27:31.822  6878  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-02 15:27:31.822  6878  6948 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 15:27:31.822  6878  6948 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-02 15:27:31.824  6878  6948 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-02 15:27:31.824  1043  2018 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 15:27:31.828  6878  6948 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-02 15:27:31.829  6878  6948 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-02 15:27:31.830  6878  6948 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-02 15:27:31.831  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 15:27:31.832  6878  6948 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-02 15:27:31.832  6878  6948 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 15:27:31.832  6878  6948 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 15:27:31.833  6878  6948 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 15:27:31.833  6878  6948 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 15:27:31.833  6878  6948 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 15:27:31.833  6878  6948 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 15:27:31.833  6878  6948 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:27:31.833  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 15:27:31.833  6878  6948 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-02 15:27:31.833  6878  6948 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@39f3c2b8 removed from the list
09-02 15:27:31.833  6878  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:27:31.833  6878  6948 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@46e2891 removed from the list
09-02 15:27:31.833  6878  6948 D io.jxcore.node.ConnectivityMonitor: stop
09-02 15:27:31.833  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:27:31.834  6878  6948 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:27:31.834  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:27:31.834  6878  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 15:27:31.834  6878  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 15:27:31.834  6878  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:27:31.834  6878  6948 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@46e2891 not in the list
09-02 15:27:31.834  6878  6948 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:27:31.834  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:27:31.835  6878  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 15:27:31.835  6878  6948 D BluetoothLeScanner: could not find callback wrapper
09-02 15:27:31.835  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stoppe,d
09-02 15:27:31.835  6878  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 15:27:31.835  6878  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:27:31.835  6878  6948 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d7e5264 removed from the list
09-02 15:27:31.835  6878  6948 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 15:27:31.835  6878  6948 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:27:31.835  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:27:31.835  6878  6948 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-02 15:27:31.835  6878  6948 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3733f3f7 removed from the list
09-02 15:27:31.835  6878  6948 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-02 15:27:31.836  6878  6948 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20a9d893 added. We now have 2 listener(s)
09-02 15:27:31.836  1043  1059 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 15:27:31.838  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-02 15:27:31.838  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 15:27:31.838  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-02 15:27:31.838  6878  6948 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 15:27:31.838  6878  6948 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d0030d0 added. We now have 9 listener(s)
09-02 15:27:31.838  6878  6948 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 15:27:31.838  6878  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-02 15:27:31.839  6878  6948 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 15:27:31.841  6878  6948 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 15:27:31.841  6878  6948 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 15:27:31.841  6878  6948 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 15:27:31.841  6878  6948 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 15:27:31.841  6878  6948 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 15:27:31.841  6878  6948 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 15:27:31.841  6878  6948 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 15:27:31.841  6878  6948 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-02 15:27:31.843  6878  6948 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-02 15:27:31.843  6878  6948 D io.jxcore.node.ConnectivityMonitor: start: OK
09-02 15:27:31.843  6878  6948 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-02 15:27:31.843  6878  6948 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@39ed3bce added. We now have 3 listener(s)
09-02 15:27:31.843  1043  1059 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 15:27:31.846  6878  6878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 15:27:31.848  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-02 15:27:31.848  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 15:27:31.848  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-02 15:27:31.848  6878  6948 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 15:27:31.848  6878  6948 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18f6aef added. We now have 10 listener(s)
09-02 15:27:31.848  6878  6948 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 15:27:31.848  6878  6948 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-02 15:27:31.849  6878  6948 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-02 15:27:31.849  6878  6948 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-02 15:27:31.849  6878  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-02 15:27:31.849  6878  6948 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 15:27:31.849  6878  6948 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-02 15:27:31.851  6878  6878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 15:27:31.852  6878  6948 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-02 15:27:31.852  1043  1926 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 15:27:31.854  6878  6948 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-02 15:27:31.856  6878  6948 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-02 15:27:31.857  6878  6948 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-02 15:27:31.858  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 15:27:31.859  6878  6948 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-02 15:27:31.859  6878  6948 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 15:27:31.859  6878  6948 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 15:27:31.859  6878  6948 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 15:27:31.859  6878  6948 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 15:27:31.859  6878  6948 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:27:31.860  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 15:27:31.860  6878  6948 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-02 15:27:31.860  6878  6948 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20a9d893 removed from the list
09-02 15:27:31.860  6878  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:27:31.860  6878  6948 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d0030d0 removed from the list
09-02 15:27:31.860  6878  6948 D io.jxcore.node.ConnectivityMonitor: stop
09-02 15:27:31.860  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:27:31.860  6878  6948 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:27:31.860  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:27:31.861  6878  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 15:27:31.861  6878  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 15:27:31.861  6878  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:27:31.861  6878  6948 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d0030d0 not in the list
09-02 15:27:31.861  6878  6948 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:27:31.861  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:27:31.862  6878  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 15:27:31.862  6878  6948 D BluetoothLeScanner: could not find callback wrapper
09-02 15:27:31.862  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-02 15:27:31.862  6878  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 15:27:31.862  6878  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:27:31.862  687,8  6948 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18f6aef removed from the list
09-02 15:27:31.862  6878  6948 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 15:27:31.862  6878  6948 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:27:31.862  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:27:31.862  6878  6948 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-02 15:27:31.862  6878  6948 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@39ed3bce removed from the list
09-02 15:27:31.863  6878  6948 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-02 15:27:31.863  6878  6948 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@aa546da added. We now have 2 listener(s)
09-02 15:27:31.863  1043  1865 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 15:27:31.865  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-02 15:27:31.865  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 15:27:31.865  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-02 15:27:31.866  6878  6948 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 15:27:31.866  6878  6948 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a91c70b added. We now have 9 listener(s)
09-02 15:27:31.866  6878  6948 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 15:27:31.866  6878  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-02 15:27:31.868  6878  6948 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-02 15:27:31.870  8291  8291 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
09-02 15:27:31.871  6878  6948 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 15:27:31.871  6878  6948 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 15:27:31.871  6878  6948 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 15:27:31.871  6878  6948 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 15:27:31.871  6878  6948 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 15:27:31.871  6878  6948 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 15:27:31.871  6878  6948 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 15:27:31.871  6878  6948 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-02 15:27:31.872  6878  6948 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-02 15:27:31.873  6878  6948 D io.jxcore.node.ConnectivityMonitor: start: OK
09-02 15:27:31.874  6878  6948 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-02 15:27:31.874  6878  6948 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26595801 added. We now have 3 listener(s)
09-02 15:27:31.874  1043  2018 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 15:27:31.874  6878  6878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 15:27:31.877  6878  6878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 15:27:31.878  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-02 15:27:31.878  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 15:27:31.878  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-02 15:27:31.878  6878  6948 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 15:27:31.878  6878  6948 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ea0f6a6 added. We now have 10 listener(s)
09-02 15:27:31.879  6878  6948 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 15:27:31.879  6878  6948 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-02 15:27:31.879  6878  6948 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-02 15:27:31.879  6878  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-02 15:27:31.879  6878  6948 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 15:27:31.879  6878  6948 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-02 15:27:31.881  6878  6948 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-02 15:27:31.882  1043  1059 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0,
09-02 15:27:31.886  6878  6948 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-02 15:27:31.886  6878  6948 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-02 15:27:31.888  6878  6948 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-02 15:27:31.888  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 15:27:31.890  6878  6948 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,09-02 15:27:31.892  6878  6948 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 15:27:31.892  6878  6948 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 15:27:31.892  6878  6948 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 15:27:31.892  6878  6948 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 15:27:31.892  6878  6948 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:27:31.892  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-02 15:27:31.892  6878  6948 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-02 15:27:31.892  6878  6948 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@aa546da removed from the list
09-02 15:27:31.892  6878  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:27:31.892  6878  6948 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a91c70b removed from the list
09-02 15:27:31.892  6878  6948 D io.jxcore.node.ConnectivityMonitor: stop
09-02 15:27:31.892  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:27:31.893  6878  6948 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-02 15:27:31.893  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 15:27:31.893  6878  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 15:27:31.893  6878  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-02 15:27:31.893  6878  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:27:31.894  6878  6948 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a91c70b not in the list
09-02 15:27:31.894  6878  6948 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:27:31.894  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:27:31.895  6878  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 15:27:31.895  6878  6948 D BluetoothLeScanner: could not find callback wrapper
09-02 15:27:31.895  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-02 15:27:31.895  6878  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 15:27:31.895  6878  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:27:31.895  6878  6948 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ea0f6a6 removed from the list
09-02 15:27:31.895  6878  6948 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 15:27:31.895  6878  6948 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:27:31.895  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:27:31.896  6878  6948 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-02 15:27:31.896  6878  6948 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26595801 removed from the list
09-02 15:27:31.896  6878  6948 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-02 15:27:31.896  6878  6948 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3302733d added. We now have 2 listener(s)
09-02 15:27:31.897  1043  1979 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-02 15:27:31.901  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-02 15:27:31.902  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 15:27:31.902  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-02 15:27:31.902  6878  6948 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 15:27:31.902  6878  6948 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1555d732 added. We now have 9 listener(s)
09-02 15:27:31.902  6878  6948 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 15:27:31.903  6878  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-02 15:27:31.905  6878  6948 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-02 15:27:31.906  8291  8291 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds,
09-02 15:27:31.907  8291  8291 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
09-02 15:27:31.907  8291  8291 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
09-02 15:27:31.907  8291  8291 D dhcpcd  : wlan0: adding default route via 192.168.1.1
09-02 15:27:31.908  8291  8291 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease',
09-02 15:27:31.908  8291  8291 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-02 15:27:31.908  6878  6948 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 15:27:31.908  6878  6948 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 15:27:31.908  6878  6948 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 15:27:31.908  6878  6948 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 15:27:31.908  6878  6948 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true,
09-02 15:27:31.908  6878  6948 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 15:27:31.908  6878  6948 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 15:27:31.908  6878  6948 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-02 15:27:31.909  8291  8291 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-02 15:27:31.909  8291  8291 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
09-02 15:27:31.910  6878  6948 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-02 15:27:31.910  6878  6948 D io.jxcore.node.ConnectivityMonitor: start: OK
09-02 15:27:31.912  6878  6878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
09-02 15:27:31.913  6878  6878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 15:27:31.914  6878  6948 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-02 15:27:31.914  6878  6948 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9296e00 added. We now have 3 listener(s)
09-02 15:27:31.914  1043  1722 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-02 15:27:31.917  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-02 15:27:31.917  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 15:27:31.917  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-02 15:27:31.917  6878  6948 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-02 15:27:31.917  6878  6948 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a280639 added. We now have 10 listener(s)
09-02 15:27:31.917  6878  6948 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 15:27:31.917  6878  6948 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 15:27:31.918  6878  6948 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything,
09-02 15:27:31.918  6878  6948 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 15:27:31.918  6878  6948 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 15:27:31.918  6878  6948 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
09-02 15:27:31.918  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 15:27:31.918  6878  6948 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-02 15:27:31.918  6878  6948 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3302733d removed from the list,
09-02 15:27:31.918  6878  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:27:31.918  6878  6948 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1555d732 removed from the list
09-02 15:27:31.918  6878  6948 D io.jxcore.node.ConnectivityMonitor: stop
,09-02 15:27:31.918  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 15:27:31.926  6878  6948 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:27:31.926  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:27:31.927  6878  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 15:27:31.927  6878  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 15:27:31.927  6878  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:27:31.927  6878  6948 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1555d732 not in the list
09-02 15:27:31.927  6878  6948 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:27:31.927  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:27:31.928  6878  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 15:27:31.928  6878  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 15:27:31.928  6878  6948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 15:27:31.928  6878  6948 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a280639 removed from the list
09-02 15:27:31.928  6878  6948 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 15:27:31.928  6878  6948 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 15:27:31.928  6878  6948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 15:27:31.928  6878  6948 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-02 15:27:31.928  6878  6948 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9296e00 removed from the list
09-02 15:27:31.929  6878  6948 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-02 15:27:31.929  6878  6948 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-02 15:27:31.929  6878  6948 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-02 15:27:31.929  6878  6948 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-02 15:27:31.929  6878  6948 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-02 15:27:31.929  6878  6948 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-02 15:27:31.935  6878  8302 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 916, name: My test thread name)
09-02 15:27:31.935  6878  8302 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 916, thread name: My test thread name)
09-02 15,:27:31.936  6878  8302 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 916, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
09-02 15:27:31.937  6878  8303 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 918, name: My test thread name)
09-02 15:27:31.937  6878  8303 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 918, thread name: My test thread name)
09-02 15:27:31.937  6878  8303 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 918, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-02 15:27:31.939  6878  6948 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
09-02 15:27:31.939  6878  6948 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
09-02 15:27:31.939  6878  6948 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
09-02 15:27:31.939  6878  6948 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
09-02 15:27:31.939  6878  6948 D com.test.thalitest.ThaliTestRunner: Total duration: 22778 ms
09-02 15:27:31.940  6878  6948 I jxcore-log: *Native tests were executed*
09-02 15:27:31.940  6878  6948 I jxcore-log: 
09-02 15:27:31.940  6878  6948 I jxcore-log: Total number of executed tests:  80
09-02 15:27:31.940  6878  6948 I jxcore-log: 
09-02 15:27:31.940  6878  6948 I jxcore-log: Number of passed tests:  80
09-02 15:27:31.940  6878  6948 I jxcore-log: 
09-02 15:27:31.940  6878  6948 I jxcore-log: Number of failed tests:  0
09-02 15:27:31.940  6878  6948 I jxcore-log: 
09-02 15:27:31.940  6878  6948 I jxcore-log: Number of ignored tests:  0
09-02 15:27:31.940  6878  6948 I jxcore-log: 
09-02 15:27:31.940  6878  6948 I jxcore-log: Total duration:  22778
09-02 15:27:31.940  6878  6948 I jxcore-log: 
09-02 15:27:31.941  6878  6948 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-02 15:27:31.941  6878  6948 I jxcore-log: 
09-02 15:27:31.942  8258  8258 W ExternalStrings: load override strings
09-02 15:27:31.942  8258  8258 W ExternalStrings: java.lang.RuntimeException: Unexpected tag, got eat-comment
09-02 15:27:31.942  8258  8258 W ExternalStrings: 	at com.mcafee.plugin.af.a(Unknown Source)
09-02 15:27:31.942  8258  8258 W ExternalStrings: 	at com.mcafee.plugin.ac.b(Unknown Source)
09-02 15:27:31.942  8258  8258 W ExternalStrings: 	at com.mcafee.plugin.ak.d(Unknown Source)
09-02 15:27:31.942  8258  8258 W ExternalStrings: 	at com.mcafee.plugin.ak.a(Unknown Source)
09-02 15:27:31.942  8258  8258 W ExternalStrings: 	at com.mcafee.app.s.getClassLoader(Unknown Source)
09-02 15:27:31.942  8258  8258 W ExternalStrings: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
09-02 15:27:31.942  8258  8258 W ExternalStrings: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
09-02 15:27:31.942  8258  8258 W ExternalStrings: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
09-02 15:27:31.942  8258  8258 W ExternalStrings: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
09-02 15:27:31.942  8258  8258 W ExternalStrings: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
09-02 15:27:31.942  8258  8258 W ExternalStrings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 15:27:31.942  8258  8258 W ExternalStrings: 	at android.os.Looper.loop(Looper.java:135)
09-02 15:27:31.942  8258  8258 W ExternalStrings: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-02 15:27:31.942  8258  8258 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 15:27:31.942  8258  8258 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-02 15:27:31.942  8258  8258 W ExternalStrings: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-02 15:27:31.942  8258  8258 W ExternalStrings: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-02 15:27:31.945  6878  6948 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 15:27:31.945  6878  6948 I jxcore-log: 
09-02 15:27:31.947  8258  8258 D StatusProvider: onCreate
09-02 15:27:31.950  6878  6948 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 15:27:31.950  6878  6948 I jxcore-log: 
,09-02 15:27:31.951  6878  6948 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 15:27:31.951  6878  6948 I jxcore-log: 
09-02 15:27:31.952  6878  6948 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 15:27:31.952  6878  6948 I jxcore-log: 
09-02 15:27:31.953  6878  6948 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 15:27:31.953  6878  6948 I jxcore-log: 
09-02 15:27:31.953  6878  6878 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-02 15:27:31.955  6878  6948 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 15:27:31.955  6878  6948 I jxcore-log: 
09-02 15:27:31.960  6878  6948 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-02 15:27:31.960  6878  6948 I jxcore-log: 
09-02 15:27:31.963  6878  6948 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-02 15:27:31.963  6878  6948 I jxcore-log: 
09-02 15:27:31.965  6878  6948 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-02 15:27:31.965  6878  6948 I jxcore-log: 
09-02 15:27:31.966  6878  6948 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-02 15:27:31.966  6878  6948 I jxcore-log: 
09-02 15:27:31.967  6878  6948 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-02 15:27:31.967  6878  6948 I jxcore-log: 
09-02 15:27:31.969  6878  6948 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-02 15:27:31.969  6878  6948 I jxcore-log: 
09-02 15:27:31.971  6878  6948 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-02 15:27:31.971  6878  6948 I jxcore-log: 
09-02 15:27:31.972  6878  6948 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-02 15:27:31.972  6878  6948 I jxcore-log: 
09-02 15:27:31.973  6878  6948 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-02 15:27:31.973  6878  6948 I jxcore-log: 
09-02 15:27:31.974  6878  6948 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-02 15:27:31.974  6878  6948 I jxcore-log: 
09-02 15:27:31.975  6878  6948 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-02 15:27:31.975  6878  6948 I jxcore-log: 
09-02 15:27:31.977  6878  6948 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-02 15:27:31.977  6878  6948 I jxcore-log: 
09-02 15:27:31.978  6878  6948 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-02 15:27:31.978  6878  6948 I jxcore-log: 
,09-02 15:27:31.979  6878  6948 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-02 15:27:31.979  6878  6948 I jxcore-log: 
09-02 15:27:31.980  6878  6948 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-02 15:27:31.980  6878  6948 I jxcore-log: 
09-02 15:27:31.981  6878  6948 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-02 15:27:31.981  6878  6948 I jxcore-log: 
09-02 15:27:31.982  6878  6948 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-02 15:27:31.982  6878  6948 I jxcore-log: 
09-02 15:27:31.983  6878  6948 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 15:27:31.983  6878  6948 I jxcore-log: 
09-02 15:27:31.985  6878  6948 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 15:27:31.985  6878  6948 I jxcore-log: 
09-02 15:27:31.986  6878  6948 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 15:27:31.986  6878  6948 I jxcore-log: 
09-02 15:27:31.987  6878  6948 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 15:27:31.987  6878  6948 I jxcore-log: 
09-02 15:27:31.988  6878  6948 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 15:27:31.988  6878  6948 I jxcore-log: 
09-02 15:27:32.005  8258  8258 V Signer  : override build config not found
09-02 15:27:32.006  8258  8258 D Signer  : value of property debug is false
,09-02 15:27:32.032  8258  8258 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
09-02 15:27:32.032  8258  8258 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
,09-02 15:27:32.032  8258  8258 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
09-02 15:27:32.032  8258  8258 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
09-02 15:27:32.032  8258  8258 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
09-02 15:27:32.032  8258  8258 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
09-02 15:27:32.032  8258  8258 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
09-02 15:27:32.033  8258  8258 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
09-02 15:27:32.033  8258  8258 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
09-02 15:27:32.033  8258  8258 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
09-02 15:27:32.033  8258  8258 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
09-02 15:27:32.033  8258  8258 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
09-02 15:27:32.033  8258  8258 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
09-02 15:27:32.050  8258  8258 V LGMDMManager: Create singleton instance
,09-02 15:27:32.092  8258  8258 D LGMDMWrapper: LG MDM library v4.0.0 is available on this device.
,09-02 15:27:32.132  8258  8258 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-02 15:27:32.135  1043  8276 D DhcpStateMachine: DHCPV4 succeeded on wlan0
09-02 15:27:32.135  1043  8276 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
09-02 15:27:32.135  1043  8276 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-02 15:27:32.135  1043  8276 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
09-02 15:27:32.135  1043  8276 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
09-02 15:27:32.136  1043  8276 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-02 15:27:32.136  1043  8276 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
09-02 15:27:32.136  1043  8276 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
09-02 15:27:32.136  1043  8276 D DhcpStateMachine: RunningState
09-02 15:27:32.137  8258  8326 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-02 15:27:32.140  7015  7015 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-02 15:27:32.143  7015  7015 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 15:27:32.187  8314  8314 D AndroidRuntime: 
09-02 15:27:32.187  8314  8314 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
09-02 15:27:32.189  8314  8314 D AndroidRuntime: CheckJNI is OFF
,09-02 15:27:32.190  1043  1722 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=8329 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,09-02 15:27:32.190  1043  1722 I ActivityManager: Killing 7370:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
09-02 15:27:32.213   341   341 I art     : Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 381us total 21.044ms
,09-02 15:27:32.230   341   341 I art     : Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 294us total 16.220ms
,09-02 15:27:32.244   341   341 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 286us total 13.907ms
,09-02 15:27:32.298  8314  8314 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-02 15:27:32.320  8258  8325 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,09-02 15:27:32.398  1043  1722 E libprocessgroup: failed to kill 1 processes for processgroup 7370
,09-02 15:27:32.503  1043  1125 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
,09-02 15:27:32.507  1043  1125 I ActivityManager: Killing 6878:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
09-02 15:27:32.530  8329  8329 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-02 15:27:32.581  1043  1962 I WindowState: WIN DEATH: Window{3b10889e u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-02 15:27:32.582  1043  1429 D WifiService: Client connection lost with reason: 4
,09-02 15:27:32.587  1043  1962 D InputDispatcher: Window went away: Window{3b10889e u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-02 15:27:32.731  1043  1125 I ActivityManager:   Force finishing activity ActivityRecord{3dd31cbb u0 com.test.thalitest/.MainActivity t6}
,09-02 15:27:32.766   337   344 E GBMv2   : DFP En is all cleared set to be enabled
,09-02 15:27:32.805  1043  1115 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
,09-02 15:27:32.811  1043  1115 I ActivityManager:   Force finishing activity ActivityRecord{3dd31cbb u0 com.test.thalitest/.MainActivity t6 f}
09-02 15:27:32.811  1043  1115 W ActivityManager: Duplicate finish request for ActivityRecord{3dd31cbb u0 com.test.thalitest/.MainActivity t6 f}
09-02 15:27:32.813  1043  1891 W ActivityManager: Spurious death for ProcessRecord{170c31d3 6878:com.test.thalitest/u0a118}, curProc for 6878: null
09-02 15:27:32.814  2019  2019 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
09-02 15:27:32.816  2019  2019 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
09-02 15:27:32.818  2019  2019 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
09-02 15:27:32.818  2019  2064 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=1ms
,09-02 15:27:32.823  1928  2902 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
09-02 15:27:32.823  1892  1892 D ActionManagerService: notifyUserLog: 1000003
09-02 15:27:32.823  1928  2902 D SplitWindowPolicy: topRunningActivity=ActivityInfo{fb9ae45 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
09-02 15:27:32.824  3771  4922 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
09-02 15:27:32.824  2019  2019 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
09-02 15:27:32.825  8329  8329 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
09-02 15:27:32.826  2019  2019 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
09-02 15:27:32.827  2019  2019 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
09-02 15:27:32.828  2019  2019 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
09-02 15:27:32.832  1928  1944 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
09-02 15:27:32.833  2019  2019 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
09-02 15:27:32.833  1928  1944 D SplitWindowPolicy: topRunningActivity=ActivityInfo{1386699a co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
,09-02 15:27:32.839  1892  1892 D ActionManagerService: notifyUserLog: 1000004
09-02 15:27:32.840  3771  4922 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
09-02 15:27:32.840  1589  1589 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
09-02 15:27:32.841  3771  3787 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
,09-02 15:27:32.851  7830  7830 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
09-02 15:27:32.851  7830  7830 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
09-02 15:27:32.852  1981  1981 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
09-02 15:27:32.852  3771  3771 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
09-02 15:27:32.862  1043  1364 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-02 15:27:32.866  2469  2636 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
09-02 15:27:32.886  5009  5009 I art     : Explicit concurrent mark sweep GC freed 8248(471KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 30MB/46MB, paused 599us total 101.432ms
,09-02 15:27:32.893  8329  8329 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
09-02 15:27:32.894  8329  8329 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
09-02 15:27:32.894  8329  8329 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
09-02 15:27:32.894  8329  8329 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
09-02 15:27:32.895  8329  8329 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
09-02 15:27:32.896  8329  8329 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
09-02 15:27:32.920  2019  2019 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
09-02 15:27:32.920  2019  2019 I GBoardWebViewUtils: , create_time: 1430832262123
09-02 15:27:32.920  2019  2019 I GBoardWebViewUtils: , expire_time: 0
09-02 15:27:32.920  2019  2019 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
09-02 15:27:32.920  2019  2019 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
09-02 15:27:32.920  2019  2019 I GBoardWebViewUtils: , display: false
09-02 15:27:32.920  2019  2019 I GBoardWebViewUtils: , animation: false }
09-02 15:27:32.921  2019  2019 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
09-02 15:27:32.921  2019  2019 I GBoardWebViewUtils: , create_time: 1430832262287
09-02 15:27:32.921  2019  2019 I GBoardWebViewUtils: , expire_time: 0
09-02 15:27:32.921  2019  2019 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
09-02 15:27:32.921  2019  2019 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
09-02 15:27:32.921  2019  2019 I GBoardWebViewUtils: , display: false
09-02 15:27:32.921  2019  2019 I GBoardWebViewUtils: , animation: false }
09-02 15:27:32.921  2019  2019 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1472216587976
09-02 15:27:32.921  2019  2019 I GBoardWebViewUtils: , create_time: 1472216588858
09-02 15:27:32.921  2019  2019 I GBoardWebViewUtils: , expire_time: 0
09-02 15:27:32.921  2019  2019 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide.html?id=guide_1111111111116_1472216587976&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
09-02 15:27:32.921  2019  2019 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
09-02 15:27:32.921  2019  2019 I GBoardWebViewUtils: , display: false
09-02 15:27:32.921  2019  2019 I GBoardWebViewUtils: , animation: false }
09-02 15:27:32.922  1589  1589 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
,09-02 15:27:32.929  1589  1649 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
09-02 15:27:32.929  1589  1649 D KeyguardModel: createShortcutInfo...
09-02 15:27:32.937  1589  1649 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
09-02 15:27:32.937  1589  1649 D KeyguardModel: createShortcutInfo...
09-02 15:27:32.937  4902  4902 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
09-02 15:27:32.937  4902  4902 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
09-02 15:27:32.937  4902  4902 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
09-02 15:27:32.937  4902  4902 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
09-02 15:27:32.937  4902  4902 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-02 15:27:32.937  4902  4902 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-02 15:27:32.937  4902  4902 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-02 15:27:32.937  4902  4902 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-02 15:27:32.937  4902  4902 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 15:27:32.937  4902  4902 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-02 15:27:32.937  4902  4902 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-02 15:27:32.937  4902  4902 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,09-02 15:27:32.954  1589  1589 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
09-02 15:27:32.954  1589  1589 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
,09-02 15:27:32.958  8329  8329 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
09-02 15:27:32.959  2019  8371 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
09-02 15:27:32.969  1589  1649 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
,09-02 15:27:32.969  1589  1649 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-02 15:27:32.969  1589  1649 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
09-02 15:27:32.970  1855  1855 D SplitUIManager: split_name #11 / not available #0
09-02 15:27:32.971  1589  1649 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-02 15:27:32.971  1855  1855 D SplitUIService: removed split : 
09-02 15:27:32.973  1589  1649 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-02 15:27:32.973  1589  1649 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
09-02 15:27:32.974  1589  1649 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
09-02 15:27:32.974  1589  1649 D KeyguardModel: createShortcutInfo...
09-02 15:27:32.984  1043  1114 W InputMethodInfo: Duplicated subtype definition found: , voice
,09-02 15:27:32.987  1043  1927 V SIM_STK : Menu title from STK is T-Mobile
09-02 15:27:32.990  2019  2019 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
09-02 15:27:32.992  1589  1649 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
09-02 15:27:32.992  1589  1649 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-02 15:27:32.993  8329  8329 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-02 15:27:32.995  1589  1649 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-02 15:27:32.995  1589  1649 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
09-02 15:27:32.998  1043  1043 I art     : Explicit concurrent mark sweep GC freed 78678(4MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 43MB/65MB, paused 2.730ms total 204.394ms
,09-02 15:27:33.006  1043  1125 I art     : WaitForGcToComplete blocked for 190.690ms for cause Explicit
09-02 15:27:33.009  8329  8329 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-02 15:27:33.012  1589  1649 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
09-02 15:27:33.012  1589  1649 D KeyguardModel: createShortcutInfo...
09-02 15:27:33.020  1589  1649 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-02 15:27:33.020  1589  1649 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-02 15:27:33.020  1589  1649 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
09-02 15:27:33.020  1589  1649 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-02 15:27:33.027  1855  1855 D SplitUIManager: split_name #11 / not available #0
,09-02 15:27:33.027  1855  1855 I SplitUIService: split app #11
09-02 15:27:33.027  1589  1649 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-02 15:27:33.027  1589  1649 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
09-02 15:27:33.028  1589  1649 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
09-02 15:27:33.028  1589  1649 D KeyguardModel: createShortcutInfo...
09-02 15:27:33.035  1589  1589 D KeyguardModel: handleShortcutListChanged...
09-02 15:27:33.035  1589  1589 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
09-02 15:27:33.039  1043  1865 V SIM_STK : Menu title from STK is T-Mobile
09-02 15:27:33.039  1043  1865 V SIM_STK : Menu title from STK is T-Mobile
09-02 15:27:33.040  1589  1649 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
09-02 15:27:33.040  1589  1649 D KeyguardModel: createShortcutInfo...
09-02 15:27:33.042  1589  1649 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
09-02 15:27:33.042  1589  1649 D KeyguardModel: createShortcutInfo...
09-02 15:27:33.043  1589  1649 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-02 15:27:33.043  1589  1649 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
,09-02 15:27:33.062  1589  1649 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
09-02 15:27:33.062  1589  1649 D KeyguardModel: createShortcutInfo...
09-02 15:27:33.063  1589  1649 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-02 15:27:33.063  1589  1649 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
09-02 15:27:33.064  1589  1649 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
09-02 15:27:33.064  1589  1649 D KeyguardModel: createShortcutInfo...
09-02 15:27:33.065  1589  1649 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-02 15:27:33.065  1589  1649 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
09-02 15:27:33.066  1589  1649 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
09-02 15:27:33.066  1589  1649 D KeyguardModel: createShortcutInfo...
,09-02 15:27:33.072  2019  2019 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
09-02 15:27:33.075  2019  2019 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
09-02 15:27:33.082  1043  2014 V SIM_STK : Menu title from STK is T-Mobile
09-02 15:27:33.090  1043  1962 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,09-02 15:27:33.091  7830  7830 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
09-02 15:27:33.091  7830  7830 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
09-02 15:27:33.091  7830  7830 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
09-02 15:27:33.092  7830  7830 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
09-02 15:27:33.092  7830  7830 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
09-02 15:27:33.092  7830  7830 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-02 15:27:33.092  7830  7830 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
09-02 15:27:33.092  7830  7830 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
09-02 15:27:33.092  7830  7830 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
09-02 15:27:33.092  7830  7830 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-02 15:27:33.092  7830  7830 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
09-02 15:27:33.092  1589  1589 D KeyguardModel: handleShortcutListChanged...
09-02 15:27:33.092  1589  1589 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
09-02 15:27:33.097  8329  8329 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-02 15:27:33.099  7015  7015 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
09-02 15:27:33.100  7015  7015 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
09-02 15:27:33.105  8258  8258 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-02 15:27:33.107  8329  8329 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
09-02 15:27:33.107  8258  8326 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-02 15:27:33.118  8329  8329 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
09-02 15:27:33.122  7015  7015 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-02 15:27:33.126  7015  7015 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 15:27:33.128  1043  1043 D administrator: Handling package changes for user 0
09-02 15:27:33.130   318   405 I ThermalEngine: Thermal-Server: Thermal received msg from  override
09-02 15:27:33.131  3337  8380 I Thermal-Lib: Thermal-Lib-Client: Client request sent
09-02 15:27:33.146  2019  2019 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,09-02 15:27:33.149  2019  2019 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-02 15:27:33.150  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
09-02 15:27:33.151  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
09-02 15:27:33.152  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
09-02 15:27:33.153  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
09-02 15:27:33.158  8258  8325 D LgDataFeature: LgDataFeature() Constructor: none
09-02 15:27:33.158  8258  8325 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-02 15:27:33.159  8329  8329 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-02 15:27:33.159  8329  8329 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-02 15:27:33.160  8329  8329 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-02 15:27:33.162  8258  8258 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-02 15:27:33.164  8258  8326 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-02 15:27:33.168  1043  1120 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2299cf66 u0 com.lge.launcher2/.Launcher t5} time:206442
09-02 15:27:33.171  2019  2019 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
09-02 15:27:33.172  2019  2019 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,09-02 15:27:33.181  7015  7015 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-02 15:27:33.186  2019  2146 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
09-02 15:27:33.186  2019  2146 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
09-02 15:27:33.190  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
09-02 15:27:33.191  2019  2019 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
09-02 15:27:33.191  2019  2019 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,09-02 15:27:33.200  2019  2019 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
09-02 15:27:33.201  2584  2584 D [Concierge]Service: onStartCommand(). Type : 8
09-02 15:27:33.201  2584  2584 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
09-02 15:27:33.202  2584  2584 D [Concierge]Service: Update widget ID : 11
09-02 15:27:33.202  7015  7015 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 15:27:33.204  2019  2019 D [Concierge]WidgetView: change position of spinner
09-02 15:27:33.205  2584  2584 D [Concierge]Service: onStartCommand(). Type : 0
09-02 15:27:33.205  2019  2019 I [Concierge]WidgetView: initWebView(). Time : 1472822853205
09-02 15:27:33.213  8329  8329 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-02 15:27:33.213  8329  8329 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-02 15:27:33.213  8329  8329 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-02 15:27:33.216  7015  7015 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-02 15:27:33.216  7015  7015 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-02 15:27:33.216  7015  7015 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-02 15:27:33.216  7015  7015 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-02 15:27:33.217  7015  7015 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-02 15:27:33.217  7015  7015 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-02 15:27:33.217  7015  7015 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
09-02 15:27:33.217  7015  7015 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-02 15:27:33.217  7015  7015 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-02 15:27:33.217  7015  7015 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-02 15:27:33.217  7015  7015 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
09-02 15:27:33.217  7015  7015 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-02 15:27:33.220  1043  1043 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
09-02 15:27:33.221  1043  1043 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
09-02 15:27:33.221  1043  1043 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,09-02 15:27:33.222  8258  8258 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-02 15:27:33.223  8258  8326 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-02 15:27:33.223  1043  1564 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
09-02 15:27:33.232  7015  7015 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-02 15:27:33.236  7015  7015 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 15:27:33.240  2019  2019 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 483928788
09-02 15:27:33.240  2019  2019 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
09-02 15:27:33.240  2019  2019 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
09-02 15:27:33.243  2019  2019 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@2ec81066
09-02 15:27:33.243  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
09-02 15:27:33.245  2019  2019 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
09-02 15:27:33.245  2019  2019 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,09-02 15:27:33.250  8329  8329 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-02 15:27:33.250  8329  8329 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-02 15:27:33.250  8329  8329 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-02 15:27:33.252  8258  8258 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-02 15:27:33.253  8258  8326 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-02 15:27:33.255  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
09-02 15:27:33.255  7015  7015 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-02 15:27:33.255  2019  2019 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
09-02 15:27:33.256  2019  2019 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1472822674068, New one : 1472822853205
09-02 15:27:33.256  2019  2019 D [Concierge]WidgetView: Unregister all receivers
09-02 15:27:33.256  2019  2019 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
09-02 15:27:33.256  2019  2019 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
09-02 15:27:33.257  2019  2019 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-02 15:27:33.258  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
,09-02 15:27:33.259  7015  7015 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 15:27:33.259  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
09-02 15:27:33.260  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
09-02 15:27:33.261  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
09-02 15:27:33.262  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
09-02 15:27:33.263  8329  8329 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-02 15:27:33.264  8329  8329 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-02 15:27:33.264  2019  2019 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-02 15:27:33.264  8329  8329 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-02 15:27:33.264  2019  2019 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-02 15:27:33.267  8258  8258 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-02 15:27:33.267  8258  8326 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-02 15:27:33.268  1043  1125 I art     : Explicit concurrent mark sweep GC freed 9367(557KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 2.813ms total 256.949ms
09-02 15:27:33.272  7015  7015 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-02 15:27:33.277  7015  7015 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 15:27:33.283  8329  8329 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-02 15:27:33.283  8329  8329 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-02 15:27:33.283  8329  8329 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-02 15:27:33.285  8258  8258 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-02 15:27:33.285  8258  8326 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-02 15:27:33.290  7015  7015 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-02 15:27:33.294  7015  7015 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-02 15:27:33.296  2019  2019 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
09-02 15:27:33.301  8258  8325 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
,09-02 15:27:33.303  2019  2019 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
09-02 15:27:33.304  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
09-02 15:27:33.305  2019  2019 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-02 15:27:33.313  8329  8329 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-02 15:27:33.313  8329  8329 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-02 15:27:33.313  8329  8329 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-02 15:27:33.314  8258  8325 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
09-02 15:27:33.319  8258  8258 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-02 15:27:33.320  8258  8326 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-02 15:27:33.321  8258  8325 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
,09-02 15:27:33.321  8258  8325 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
09-02 15:27:33.325  2019  2019 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2984052e time:206599
09-02 15:27:33.328  8258  8325 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
09-02 15:27:33.328  8258  8325 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
09-02 15:27:33.329  8258  8325 I SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
09-02 15:27:33.330  7015  7015 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-02 15:27:33.334  7015  7015 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 15:27:33.337  8258  8325 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
,09-02 15:27:33.338  8329  8329 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-02 15:27:33.338  8329  8329 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-02 15:27:33.338  8258  8325 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
09-02 15:27:33.341  8329  8329 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-02 15:27:33.344  8258  8258 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-02 15:27:33.344  8258  8326 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-02 15:27:33.350  7015  7015 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-02 15:27:33.354  7015  7015 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 15:27:33.358  8329  8329 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-02 15:27:33.358  8329  8329 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-02 15:27:33.359  8329  8329 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-02 15:27:33.361  8258  8258 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-02 15:27:33.361  8258  8326 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-02 15:27:33.363  8208  8208 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,09-02 15:27:33.377  8208  8208 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,09-02 15:27:33.378  8314  8314 D AndroidRuntime: Shutting down VM
09-02 15:27:33.379  7015  7015 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-02 15:27:33.384  7015  7015 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-02 15:27:33.405  1043  1125 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8387 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,09-02 15:27:33.411  8329  8329 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-02 15:27:33.412  8329  8329 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-02 15:27:33.412  8329  8329 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
09-02 15:27:33.413  8329  8329 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-02 15:27:33.413  8329  8329 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
09-02 15:27:33.417  8258  8258 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-02 15:27:33.417  8258  8326 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,09-02 15:27:33.419  8208  8208 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
09-02 15:27:33.421  8208  8208 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
09-02 15:27:33.423  7015  7015 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-02 15:27:33.426  7015  7015 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-02 15:27:33.437  8329  8329 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-02 15:27:33.440  8329  8329 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-02 15:27:33.441  8329  8329 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
09-02 15:27:33.441  8329  8329 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,09-02 15:27:33.442  8329  8329 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
09-02 15:27:33.444  1043  1114 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-02 15:27:33.445  8258  8258 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
09-02 15:27:33.450  1043  1114 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
09-02 15:27:33.453  8258  8258 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
09-02 15:27:33.453  8258  8326 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-02 15:27:33.455  1801  1801 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
,09-02 15:27:33.460  2160  2160 I ConfigService: onCreate
09-02 15:27:33.461  2160  2160 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
09-02 15:27:33.463  1043  1060 I ActivityManager: Killing 7406:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
09-02 15:27:33.468  2160  2160 I ConfigService: onBind returning update interface
,09-02 15:27:33.476  2019  2019 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
09-02 15:27:33.477  1043  1377 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-02 15:27:33.477  1043  1377 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-02 15:27:33.477  1043  1377 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-02 15:27:33.477  1043  1377 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-02 15:27:33.478  1043  1377 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-02 15:27:33.478  1043  1377 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-02 15:27:33.478  1043  1431 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=true
09-02 15:27:33.478  1043  1431 D ConnectivityService: identical MTU - not setting
09-02 15:27:33.478  1043  1431 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-02 15:27:33.478  1043  1431 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-02 15:27:33.478  1043  1431 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 15:27:33.478  1043  1431 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-02 15:27:33.479  1043  1431 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
09-02 15:27:33.479  1589  2084 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
09-02 15:27:33.514  2019  2857 I GBoardtInterface: onReloaded()
,09-02 15:27:33.516  2019  2019 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
09-02 15:27:33.517  1801  1801 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
09-02 15:27:33.517  2160  2160 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
09-02 15:27:33.517  2160  2160 I ConfigService: onBind returning config service
09-02 15:27:33.518  1043  1891 W libprocessgroup: failed to open /acct/uid_10005/pid_7406/cgroup.procs: No such file or directory
09-02 15:27:33.520  3771  3786 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
09-02 15:27:33.522  3771  3787 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
09-02 15:27:33.527  1892  1892 D ActionManagerService: notifyUserLog: 1000001
,09-02 15:27:33.528  3771  4922 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
09-02 15:27:33.529  3771  4922 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
09-02 15:27:33.532  1892  1892 D ActionManagerService: notifyUserLog: 1000001
09-02 15:27:33.533  3771  4922 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
09-02 15:27:33.533  3771  4922 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
09-02 15:27:33.534  3771  3786 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
09-02 15:27:33.534  3771  4922 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
09-02 15:27:33.534  3771  4922 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0,
09-02 15:27:33.535  1801  1801 I ConfigFetchService: service connected
09-02 15:27:33.537  2019  2019 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
09-02 15:27:33.537  2019  2019 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
09-02 15:27:33.539  2019  2019 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
09-02 15:27:33.539  2019  2019 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
,09-02 15:27:33.540  2160  2160 I ConfigService: onDestroy
09-02 15:27:33.541  2019  2019 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1472216587976&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
09-02 15:27:33.541  2019  2019 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1472216587976&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
09-02 15:27:33.542  1801  8408 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
09-02 15:27:33.543  2019  2019 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
09-02 15:27:33.566  5750  8414 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
,09-02 15:27:33.569  1801  8415 I PeopleContactsSync: CP2 sync disabled
09-02 15:27:33.570  1801  5159 I Icing   : doRemovePackageData com.test.thalitest
09-02 15:27:33.577  1801  8413 W GmsApplication: Using Auth Proxy for data requests.
,09-02 15:27:33.582  1801  8413 W GmsApplication: Using Auth Proxy for data requests.
09-02 15:27:33.600  7197  7197 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
,09-02 15:27:33.611  2382  8417 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
09-02 15:27:33.619  2160  2324 I art     : Explicit concurrent mark sweep GC freed 6396(380KB) AllocSpace objects, 0(0B) LOS objects, 52% free, 29MB/61MB, paused 502us total 18.793ms
,09-02 15:27:33.649  1043  1926 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8421 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,09-02 15:27:33.702  8421  8421 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-02 15:27:33.703  8421  8421 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-02 15:27:33.706  8421  8421 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-02 15:27:33.706  8421  8421 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-02 15:27:33.756  8421  8421 E SQLiteDatabase: Failed to open database '/data/data/com.lge.email/databases/Downloads.db'.
09-02 15:27:33.756  8421  8421 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-02 15:27:33.756  8421  8421 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-02 15:27:33.756  8421  8421 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
09-02 15:27:33.756  8421  8421 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
09-02 15:27:33.756  8421  8421 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-02 15:27:33.756  8421  8421 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-02 15:27:33.756  8421  8421 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-02 15:27:33.756  8421  8421 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
09-02 15:27:33.756  8421  8421 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
09-02 15:27:33.756  8421  8421 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
09-02 15:27:33.756  8421  8421 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
09-02 15:27:33.756  8421  8421 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
09-02 15:27:33.756  8421  8421 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-02 15:27:33.756  8421  8421 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-02 15:27:33.756  8421  8421 E SQLiteDatabase: 	at com.lge.email.ui.largefile.DownloadProvider.onCreate(DownloadProvider.java:51)
09-02 15:27:33.756  8421  8421 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
09-02 15:27:33.756  8421  8421 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
09-02 15:27:33.756  8421  8421 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
09-02 15:27:33.756  8421  8421 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
09-02 15:27:33.756  8421  8421 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
09-02 15:27:33.756  8421  8421 E SQLiteDatabase: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
09-02 15:27:33.756  8421  8421 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
09-02 15:27:33.756  8421  8421 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 15:27:33.756  8421  8421 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
09-02 15:27:33.756  8421  8421 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-02 15:27:33.756  8421  8421 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 15:27:33.756  8421  8421 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-02 15:27:33.756  8421  8421 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-02 15:2,7:33.756  8421  8421 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-02 15:27:33.756  8421  8421 W System.err: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-02 15:27:33.756  8421  8421 W System.err: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-02 15:27:33.756  8421  8421 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
09-02 15:27:33.756  8421  8421 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
09-02 15:27:33.756  8421  8421 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-02 15:27:33.756  8421  8421 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-02 15:27:33.756  8421  8421 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-02 15:27:33.756  8421  8421 W System.err: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
09-02 15:27:33.756  8421  8421 W System.err: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
09-02 15:27:33.756  8421  8421 W System.err: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
09-02 15:27:33.756  8421  8421 W System.err: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
09-02 15:27:33.756  8421  8421 W System.err: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
09-02 15:27:33.756  8421  8421 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-02 15:27:33.756  8421  8421 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-02 15:27:33.756  8421  8421 W System.err: 	at com.lge.email.ui.largefile.DownloadProvider.onCreate(DownloadProvider.java:51)
09-02 15:27:33.756  8421  8421 W System.err: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
09-02 15:27:33.756  8421  8421 W System.err: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
09-02 15:27:33.756  8421  8421 W System.err: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
09-02 15:27:33.756  8421  8421 W System.err: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
09-02 15:27:33.756  8421  8421 W System.err: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
,09-02 15:27:33.756  8421  8421 W System.err: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
,09-02 15:27:33.756  8421  8421 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
09-02 15:27:33.757  8421  8421 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 15:27:33.757  8421  8421 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-02 15:27:33.757  8421  8421 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-02 15:27:33.757  8421  8421 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 15:27:33.757  8421  8421 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-02 15:27:33.757  8421  8421 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-02 15:27:33.757  8421  8421 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-02 15:27:33.762  8421  8421 E SQLiteDatabase: Failed to open database '/data/data/com.lge.email/databases/sqt.db'.
09-02 15:27:33.762  8421  8421 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-02 15:27:33.762  8421  8421 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-02 15:27:33.762  8421  8421 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
09-02 15:27:33.762  8421  8421 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
09-02 15:27:33.762  8421  8421 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-02 15:27:33.762  8421  8421 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-02 15:27:33.762  8421  8421 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-02 15:27:33.762  8421  8421 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
09-02 15:27:33.762  8421  8421 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
09-02 15:27:33.762  8421  8421 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
09-02 15:27:33.762  8421  8421 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
09-02 15:27:33.762  8421  8421 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
09-02 15:27:33.762  8421  8421 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-02 15:27:33.762  8421  8421 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-02 15:27:33.762  8421  8421 E SQLiteDatabase: 	at com.lge.email.providers.sqt.SqtProvider.onCreate(SqtProvider.java:155)
09-02 15:27:33.762  8421  8421 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
09-02 15:27:33.762  8421  8421 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
09-02 15:27:33.762  8421  8421 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
09-02 15:27:33.762  8421  8421 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
09-02 15:27:33.762  8421  8421 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
09-02 15:27:33.762  8421  8421 E SQLiteDatabase: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
09-02 15:27:33.762  8421  8421 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
09-02 15:27:33.762  8421  8421 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 15:27:33.762  8421  8421 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
09-02 15:27:33.762  8421  8421 E SQLiteDatabase,: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-02 15:27:33.762  8421  8421 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 15:27:33.762  8421  8421 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-02 15:27:33.762  8421  8421 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-02 15:27:33.762  8421  8421 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-02 15:27:33.762  8421  8421 D AndroidRuntime: Shutting down VM
--------- beginning of crash
09-02 15:27:33.763  8421  8421 E AndroidRuntime: FATAL EXCEPTION: main
09-02 15:27:33.763  8421  8421 E AndroidRuntime: Process: com.lge.email, PID: 8421
09-02 15:27:33.763  8421  8421 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.lge.email.providers.sqt.SqtProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-02 15:27:33.763  8421  8421 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5017)
09-02 15:27:33.763  8421  8421 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
09-02 15:27:33.763  8421  8421 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
09-02 15:27:33.763  8421  8421 E AndroidRuntime: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
09-02 15:27:33.763  8421  8421 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
09-02 15:27:33.763  8421  8421 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 15:27:33.763  8421  8421 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
09-02 15:27:33.763  8421  8421 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-02 15:27:33.763  8421  8421 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 15:27:33.763  8421  8421 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-02 15:27:33.763  8421  8421 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-02 15:27:33.763  8421  8421 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-02 15:27:33.763  8421  8421 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-02 15:27:33.763  8421  8421 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-02 15:27:33.763  8421  8421 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
09-02 15:27:33.763  8421  8421 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
09-02 15:27:33.763  8421  8421 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-02 15:27:33.763  8421  8421 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-02 15:27:33.763  8421  8421 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-02 15:27:33.763  8421  8421 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
09-02 15:27:33.763  8421  8421 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
09-02 15:27:33.763  8421  8421 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
09-02 15:27:33.763  8421  8421 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
09-02 15:27:33.763  8421  8421 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
09-02 15:27:33.763  8421  8421 E AndroidRuntime: 	at android.database.sqlite.,SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-02 15:27:33.763  8421  8421 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-02 15:27:33.763  8421  8421 E AndroidRuntime: 	at com.lge.email.providers.sqt.SqtProvider.onCreate(SqtProvider.java:155)
09-02 15:27:33.763  8421  8421 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
09-02 15:27:33.763  8421  8421 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
09-02 15:27:33.763  8421  8421 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
09-02 15:27:33.763  8421  8421 E AndroidRuntime: 	... 11 more
09-02 15:27:33.768  8421  8421 I Process : Sending signal. PID: 8421 SIG: 9
09-02 15:27:33.772  1043  8440 E DropBoxManagerService: Can't write: system_app_crash
09-02 15:27:33.772  1043  8440 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop131.tmp: open failed: EROFS (Read-only file system)
09-02 15:27:33.772  1043  8440 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
09-02 15:27:33.772  1043  8440 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-02 15:27:33.772  1043  8440 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-02 15:27:33.772  1043  8440 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-02 15:27:33.772  1043  8440 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
09-02 15:27:33.772  1043  8440 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12437)
09-02 15:27:33.772  1043  8440 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-02 15:27:33.772  1043  8440 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-02 15:27:33.772  1043  8440 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-02 15:27:33.772  1043  8440 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-02 15:27:33.772  1043  8440 E DropBoxManagerService: 	... 5 more
,09-02 15:27:33.832  2019  2857 I GBoardtInterface: exportHTML()
,09-02 15:27:33.856  1043  1926 I ActivityManager: Process com.lge.email (pid 8421) has died
,09-02 15:27:33.862  2019  2857 I GBoardtInterface: exportHTML()
09-02 15:27:33.885  2019  2857 I GBoardtInterface: exportHTML()
,09-02 15:27:34.005  4902  4952 E SQLiteLog: (2570) os_unix.c:31441: (30) unlink(/mpt/MPT_CommonData.db-journal) - 
,09-02 15:27:34.006  4902  4952 E SQLiteDatabase: Error inserting f004=20 f005=8421 f002=1472822853775 f003= f006=-1
09-02 15:27:34.006  4902  4952 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 2570)
09-02 15:27:34.006  4902  4952 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
09-02 15:27:34.006  4902  4952 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:787)
09-02 15:27:34.006  4902  4952 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:926)
09-02 15:27:34.006  4902  4952 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
09-02 15:27:34.006  4902  4952 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1572)
09-02 15:27:34.006  4902  4952 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1442)
09-02 15:27:34.006  4902  4952 E SQLiteDatabase: 	at com.lge.mlt.MptCommonLogProvider.insert(MptCommonLogProvider.java:706)
09-02 15:27:34.006  4902  4952 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:238)
09-02 15:27:34.006  4902  4952 E SQLiteDatabase: 	at android.content.ContentResolver.insert(ContentResolver.java:1223)
09-02 15:27:34.006  4902  4952 E SQLiteDatabase: 	at com.lge.mlt.MltMonitorService.insertProcessInfoLog(MltMonitorService.java:2584)
09-02 15:27:34.006  4902  4952 E SQLiteDatabase: 	at com.lge.mlt.MltMonitorService.access$2700(MltMonitorService.java:38)
09-02 15:27:34.006  4902  4952 E SQLiteDatabase: 	at com.lge.mlt.MltMonitorService$DbFlushManager$1.handleMessage(MltMonitorService.java:3409)
09-02 15:27:34.006  4902  4952 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 15:27:34.006  4902  4952 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
09-02 15:27:34.006  4902  4952 E SQLiteDatabase: 	at com.lge.mlt.MltMonitorService$DbFlushManager.run(MltMonitorService.java:3518)

```
