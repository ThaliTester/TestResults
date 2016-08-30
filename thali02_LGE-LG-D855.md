#### Test 82883341b26c908_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
08-30 10:20:43.320  6573  6573 D TAG     : onCreate()
08-30 10:20:43.343  6573  6573 D CrossAppStateProvider: Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
08-30 10:20:43.948   331   415 I ThermalEngine: Thermal-Server: Thermal received msg from  override
,08-30 10:20:43.953  3238  6599 I Thermal-Lib: Thermal-Lib-Client: Client request sent
08-30 10:20:44.206  1826  4822 I Icing   : Indexing 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4 from com.google.android.googlequicksearchbox
08-30 10:20:44.265  1826  4822 D Icing   : Loaded CLD2 Version V2.0 - 20140131
08-30 10:20:44.311  1826  4822 I Icing   : Indexing done 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4
08-30 10:20:44.352  6600  6600 D AndroidRuntime: 
08-30 10:20:44.352  6600  6600 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-30 10:20:44.354  6600  6600 D AndroidRuntime: CheckJNI is OFF
08-30 10:20:44.484  6600  6600 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-30 10:20:44.489  1036  1051 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-30 10:20:44.499  1955  1978 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-30 10:20:44.502  1036  1051 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-30 10:20:44.504  1036  1051 D ActivityManager: setTaskToReturnTo : TaskRecord{ee92e89 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-30 10:20:44.504  1036  1051 D ActivityManager: setTaskToReturnTo : TaskRecord{ee92e89 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-30 10:20:44.505  1036  1051 D WindowStateEx: AppWindowTokenEx init.. 
08-30 10:20:44.505   344   383 E GBMv2   : DFP En is all cleared set to be enabled
08-30 10:20:44.540  1036  1051 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6615 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-30 10:20:44.543  6600  6600 D AndroidRuntime: Shutting down VM
08-30 10:20:44.575  1955  1978 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-30 10:20:44.575  1955  1978 D SplitWindowPolicy: topRunningActivity=ActivityInfo{1775cd90 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-30 10:20:44.576  1955  1977 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-30 10:20:44.577  1955  1977 D SplitWindowPolicy: topRunningActivity=ActivityInfo{2f2a9689 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-30 10:20:44.596  6573  6573 D LgDataFeature: LgDataFeature() Constructor: none
08-30 10:20:44.596  6573  6573 D LgDataFeature: LgDataFeature() Constructor Done, null
08-30 10:20:44.631  6615  6615 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-30 10:20:44.733  6615  6615 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
08-30 10:20:44.744  6615  6615 I LibraryLoader: Loading: webviewchromium
08-30 10:20:44.747  6615  6615 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 2452-2455)
08-30 10:20:44.748  6615  6615 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-30 10:20:44.750  6165  6165 I LockScreenSettings: New app installed broadcast received ..
,08-30 10:20:44.752  6165  6165 I LockScreenSettings: Number of installed packages  1
08-30 10:20:44.765  6615  6615 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3af539be}
08-30 10:20:44.766  6615  6615 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-30 10:20:44.767  6615  6615 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-30 10:20:44.782  6573  6573 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
08-30 10:20:44.783  6615  6615 I BrowserStartupController: Initializing chromium process, renderers=0
08-30 10:20:44.784  6615  6615 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-30 10:20:44.794  1036  1052 V SIM_STK : Menu title from STK is T-Mobile
08-30 10:20:44.800   321  4054 V AudioPolicyService: registerClient() client 0xb558a380, uid 10118
,08-30 10:20:44.803  6615  6615 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-30 10:20:44.804  6615  6615 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
08-30 10:20:44.804  6615  6615 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
08-30 10:20:44.816  1036  1118 D BluetoothManagerService: Message: 20
08-30 10:20:44.816  1036  1118 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3e8c9554:true
,08-30 10:20:44.823  6615  6615 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-30 10:20:44.823  6615  6615 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-30 10:20:44.823  6615  6615 I Adreno-EGL: Build Date: 12/12/14 금
08-30 10:20:44.823  6615  6615 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-30 10:20:44.823  6615  6615 I Adreno-EGL: Remote Branch: 
08-30 10:20:44.823  6615  6615 I Adreno-EGL: Local Patches: 
08-30 10:20:44.823  6615  6615 I Adreno-EGL: Reconstruct Branch: 
08-30 10:20:44.836  1036  2002 I ActivityManager: Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=6662 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-30 10:20:44.895  6662  6662 D EulaProviderUpdateObserver: action : android.intent.action.PACKAGE_ADDED
08-30 10:20:44.895  6662  6662 D EulaProviderUpdateObserver: uri : package:com.test.thalitest
,08-30 10:20:44.932  1036  2002 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.BNRAppInstallReceiver: pid=6686 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-30 10:20:44.934  1036  2002 I ActivityManager: Killing 5555:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
08-30 10:20:45.023  1036  1561 W libprocessgroup: failed to open /acct/uid_10005/pid_5555/cgroup.procs: No such file or directory
,08-30 10:20:45.067  6615  6660 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,08-30 10:20:45.070  6615  6615 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
08-30 10:20:45.073  1036  1104 W ActivityManager: Activity pause timeout for ActivityRecord{2c6cbe8e u0 com.test.thalitest/.MainActivity t6}
08-30 10:20:45.088  6615  6615 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-30 10:20:45.093  6615  6615 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-30 10:20:45.096  6615  6615 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-30 10:20:45.098  6615  6615 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-30 10:20:45.098  6615  6615 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
,08-30 10:20:45.110  6686  6686 D [BNRAppListMgrReceiver]: android.intent.action.PACKAGE_ADDED : com.test.thalitest
08-30 10:20:45.112  6615  6615 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
08-30 10:20:45.119  6615  6615 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-30 10:20:45.119  6615  6615 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-30 10:20:45.130  6686  6686 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-30 10:20:45.133  6433  6433 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.intent.action.PACKAGE_ADDED'.
,08-30 10:20:45.158  6433  6433 D PostponalbeReceiver: OasPackageInstalledReceiver is now processing the previously postponed broadcast action 'android.intent.action.PACKAGE_ADDED'.
,08-30 10:20:45.159  1036  2054 I ActivityManager: Killing 5899:com.google.android.talk/u0a72 (adj 15): empty #17
08-30 10:20:45.165  6615  6714 D OpenGLRenderer: Render dirty regions requested: true
08-30 10:20:45.165  6615  6714 I OpenGLRenderer: Initialized EGL, version 1.4
08-30 10:20:45.176  6615  6714 D OpenGLRenderer: Enabling debug mode 0
,08-30 10:20:45.207  6615  6615 D Atlas   : Validating map...
,08-30 10:20:45.225  1036  2002 D SplitWindow: check instance of lgWin Window{8a12f25 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-30 10:20:45.233  1036  1764 W libprocessgroup: failed to open /acct/uid_10072/pid_5899/cgroup.procs: No such file or directory
,08-30 10:20:45.275  6615  6712 D LgDataFeature: LgDataFeature() Constructor: none
08-30 10:20:45.275  6615  6712 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 10:20:45.363  6615  6615 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@302ca3a5 time:103071
,08-30 10:20:45.365  1036  1119 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +792ms (total +858ms)
08-30 10:20:45.366  1036  1119 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2c6cbe8e u0 com.test.thalitest/.MainActivity t6} time:103074
08-30 10:20:45.488  6615  6615 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-30 10:20:45.488  6615  6615 I chromium: 
,08-30 10:20:45.523  6615  6615 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-30 10:20:45.600  6615  6712 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-30 10:20:45.600  6615  6712 I chromium: 
,08-30 10:20:45.749  6615  6727 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435165696
,08-30 10:20:45.763  6615  6727 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-30 10:20:45.763  6615  6727 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-30 10:20:45.763  6615  6727 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-30 10:20:45.763  6615  6727 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-30 10:20:45.763  6615  6727 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-30 10:20:45.763  6615  6727 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c60759 added. We now have 1 listener(s)
08-30 10:20:45.769  1036  2054 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 10:20:45.772  6615  6727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-30 10:20:45.775  6615  6727 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,08-30 10:20:45.776  6615  6727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 10:20:45.776  6615  6727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 10:20:45.785  6615  6727 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-30 10:20:45.785  6615  6727 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-30 10:20:45.785  6615  6727 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-30 10:20:45.785  6615  6727 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-30 10:20:45.785  6615  6727 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-30 10:20:45.785  6615  6727 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-30 10:20:45.785  6615  6727 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-30 10:20:45.785  6615  6727 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-30 10:20:45.785  6615  6727 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-30 10:20:45.785  6615  6727 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-30 10:20:45.785  6615  6727 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-30 10:20:45.785  6615  6727 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-30 10:20:45.785  6615  6727 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-30 10:20:45.785  6615  6727 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-30 10:20:45.785  6615  6727 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20e1b5cc added. We now have 1 listener(s)
08-30 10:20:45.785  6615  6727 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 10:20:45.790  1036  1529 D WifiService: New client listening to asynchronous messages
,08-30 10:20:45.796  6615  6727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 10:20:45.796  6615  6727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-30 10:20:45.796  6615  6727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-30 10:20:45.796  6615  6727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-30 10:20:45.796  6615  6727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-30 10:20:45.803  6615  6727 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 10:20:45.804  1036  2307 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 10:20:45.805  6615  6727 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-30 10:20:45.815  6615  6727 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-30 10:20:45.815  6615  6727 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 10:20:45.815  6615  6727 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 10:20:45.815  6615  6727 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 10:20:45.815  6615  6727 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 10:20:45.815  6615  6727 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 10:20:45.815  6615  6727 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 10:20:45.815  6615  6727 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 10:20:45.815  6615  6727 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 10:20:45.816  6615  6727 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-30 10:20:45.816  6615  6727 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 10:20:45.819  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 10:20:45.821  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 10:20:45.822  6615  6727 I io.jxcore.node.LifeCycleMonitor: start: OK
08-30 10:20:45.859  6615  6615 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-30 10:20:46.143   344   385 E GBMv2   : DFP En is all cleared set to be enabled
08-30 10:20:46.143   344   385 E GBMv2   : Set value is all cleared set the max
08-30 10:20:46.143   344   385 I GBMv2   : DFP Enabled. Ignore VFP set
,08-30 10:20:46.700  6615  6733 W jxcore-log: Initializing JXcore engine
08-30 10:20:46.700  6615  6733 W jxcore-log: JXcore engine is ready
,08-30 10:20:46.730  6733  6733 W Thread-762: type=1400 audit(0.0:162): avc: denied { ioctl } for path="socket:[10274]" dev="sockfs" ino=10274 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,08-30 10:20:46.730  6733  6733 W Thread-762: type=1400 audit(0.0:163): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-30 10:20:46.730  6733  6733 W Thread-762: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[9654]" dev="sockfs" ino=9654 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-30 10:20:46.730  6733  6733 W Thread-762: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-30 10:20:46.730  6733  6733 W Thread-762: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[31406]" dev="sockfs" ino=31406 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
08-30 10:20:46.753  6615  6733 W jxcore-log: Starting JXcore engine
,08-30 10:20:46.835  6615  6733 W jxcore-log: Platform android
08-30 10:20:46.835  6615  6733 W jxcore-log: 
08-30 10:20:46.835  6615  6733 W jxcore-log: Process ARCH arm
08-30 10:20:46.835  6615  6733 W jxcore-log: 
,08-30 10:20:47.045  6615  6733 I jxcore-log: JXcore Cordova bridge is ready!
08-30 10:20:47.045  6615  6733 I jxcore-log: 
,08-30 10:20:47.045  6615  6733 W jxcore-log: JXcore engine is started
,08-30 10:20:47.055  6615  6727 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-30 10:20:47.061  6615  6615 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-30 10:20:48.705  6573  6573 W GAV2    : Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
08-30 10:20:48.706  1036  2022 I ActivityManager: Killing 5716:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,08-30 10:20:48.724  5688  5688 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
08-30 10:20:48.724  5688  5688 W System.err: android.os.DeadObjectException
,08-30 10:20:48.724  5688  5688 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-30 10:20:48.724  5688  5688 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-30 10:20:48.724  5688  5688 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-30 10:20:48.724  5688  5688 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-30 10:20:48.724  5688  5688 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-30 10:20:48.724  5688  5688 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-30 10:20:48.724  5688  5688 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-30 10:20:48.724  5688  5688 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-30 10:20:48.724  5688  5688 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-30 10:20:48.724  5688  5688 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-30 10:20:48.724  5688  5688 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 10:20:48.724  5688  5688 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 10:20:48.724  5688  5688 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-30 10:20:48.724  5688  5688 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-30 10:20:48.724  5688  5688 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-30 10:20:48.724  5688  5688 W System.err: android.os.DeadObjectException
08-30 10:20:48.725  5688  5688 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-30 10:20:48.725  5688  5688 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-30 10:20:48.725  5688  5688 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-30 10:20:48.726  5688  5688 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-30 10:20:48.726  5688  5688 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-30 10:20:48.726  5688  5688 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-30 10:20:48.726  5688  5688 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-30 10:20:48.726  5688  5688 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-30 10:20:48.726  5688  5688 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-30 10:20:48.726  5688  5688 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-30 10:20:48.726  5688  5688 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 10:20:48.727  5688  5688 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 10:20:48.727  5688  5688 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-30 10:20:48.727  5688  5688 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-30 10:20:48.727  5688  5688 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-30 10:20:48.727  5688  5688 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
08-30 10:20:48.912  2787  2787 I MusicWidget: mDelayedStopHandler : unbind
,08-30 10:20:48.920  1036  2022 E libprocessgroup: failed to kill 1 processes for processgroup 5716
,08-30 10:20:49.002  1036  1729 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,08-30 10:20:49.007  2209  2209 I MusicBrowser: [MediaPlaybackService.java:2869:onUnbind()] oooooo 
08-30 10:20:49.007  5688  5688 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-30 10:20:49.007  2209  2209 I MusicBrowser: [MediaPlaybackService.java:2076:saveQueue()] oooooo {full=true}
08-30 10:20:49.008  2209  2209 I MusicBrowser: [MediaPlaybackService.java:2081:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
08-30 10:20:49.008  5688  5688 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-30 10:20:49.009  2209  2209 D MusicBrowser: [MediaPlaybackService.java:2161:saveQueue()] oooooo {queue=}
08-30 10:20:49.009  2209  2209 D MusicBrowser: [MediaPlaybackService.java:2163:saveQueue()] oooooo {mCardId=-1}
08-30 10:20:49.009  2209  2209 D MusicBrowser: [MediaPlaybackService.java:2198:saveQueue()] oooooo {curpos=-1}
08-30 10:20:49.058  1036  2080 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=6735 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-30 10:20:49.061  2209  2209 I MusicBrowser: [MediaPlaybackService.java:2046:onDestroy()] oooooo 
08-30 10:20:49.061  2209  2209 I MusicBrowser: [MediaPlaybackService.java:8635:clearReceiver()] oooooo 
08-30 10:20:49.062  1036  2075 I MediaFocusControl:  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@32e3590fcom.lge.music.MediaPlaybackService$5@2089ad9c
08-30 10:20:49.062  2209  2209 D MusicBrowser: [MediaPlaybackService.java:8669:clearReceiver()] oooooo abandonAudioFocus : 1
08-30 10:20:49.062  2209  2209 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-30 10:20:49.062  5688  5688 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-30 10:20:49.063  2209  2209 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-30 10:20:49.064  2209  2209 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-30 10:20:49.065  2209  2209 I MusicBrowser: [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$27@26c733ca
08-30 10:20:49.070  2209  2209 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-30 10:20:49.071  2209  2209 I MusicBrowser: [MusicUtils.java:6801:endNotiTimer()] oooooo endNotiTimer
08-30 10:20:49.071  2209  2209 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
,08-30 10:20:49.076  2209  2209 I MusicBrowser: [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
08-30 10:20:49.076  2209  2209 I MusicBrowser: [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
08-30 10:20:49.077  2209  2209 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-30 10:20:49.091  2209  2209 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
,08-30 10:20:49.099  2209  2209 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-30 10:20:49.103  2209  2209 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
,08-30 10:20:49.103  2209  2209 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-30 10:20:49.106  2209  2209 I MusicBrowser: [MusicUtils.java:10406:isAKACoverSupported()] oooooo aka not support!
08-30 10:20:49.108  2209  2209 I MusicBrowser: [MediaPlaybackService.java:6704:release()] oooooo 
08-30 10:20:49.108  2209  2209 I MusicBrowser: [MediaPlaybackService.java:6665:stop()] oooooo 
08-30 10:20:49.108  2209  2209 V MediaPlayer[Native]: reset
08-30 10:20:49.117  2209  2209 V MediaPlayer[Native]: setListener
08-30 10:20:49.117  2209  2209 V MediaPlayer[Native]: disconnect
08-30 10:20:49.117  2209  2209 V MediaPlayer[Native]: destructor
08-30 10:20:49.117   321   321 V AudioFlinger: releasing 18 from 2209 for -1
08-30 10:20:49.117   321   321 V AudioFlinger:  decremented refcount to 0
08-30 10:20:49.117   321   321 V AudioFlinger: purging stale effects
08-30 10:20:49.118  2209  2209 V MediaPlayer[Native]: disconnect
,08-30 10:20:49.121  2209  2209 D MusicBrowser: [MusicUtils.java:615:getSmartShareVersion()] oooooo versionCode:305000
08-30 10:20:49.123  2209  2209 I SmartShareClient: [SmartShareManagerClient] smartshare client supported version code: 305000
08-30 10:20:49.124  2209  2209 I SmartShareClient: [SmartShareManagerClient] smartshare client enabled
08-30 10:20:49.125  2209  2209 I MusicBrowser: [MusicUtils.java:787:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000018
08-30 10:20:49.125  2209  2209 I MusicBrowser: [MusicUtils.java:635:getSmartShareVersion()] oooooo SmartshareVersion:953
08-30 10:20:49.126  2209  2209 V MusicBrowser: [MediaPlaybackService.java:9312:terminateSmartShareClient()] oooooo 
08-30 10:20:49.126  2209  2209 I SmartShareClient: [SmartShareManagerClient] unregisterListener: 808231845
08-30 10:20:49.128  2209  2209 W SmartShareClient: [SmartShareManagerClient] unregisterListener invalid listener: 808231845
08-30 10:20:49.135  2209  2209 I SmartShareClient: [SmartShareManagerClient] terminate service: 2209/MediaPlaybackService/617816384
08-30 10:20:49.137  2209  2209 E HomeCloudIF: unregiterHomeCloudBroadcast(), Illegal argument.
08-30 10:20:49.138  2209  2209 I SmartShareClient: [SmartShareManagerClient] unbindService context:android.app.Application@137c237a
,08-30 10:20:49.140  2209  2209 V CloudHub: [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.2.1, versionCode=202001, state=0
08-30 10:20:49.140  2209  2209 V CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
08-30 10:20:49.141  2209  2209 I CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
08-30 10:20:49.141  2209  2209 D MusicBrowser: [MediaPlaybackService.java:9007:setStopForeground()] oooooo bValue : true
08-30 10:20:49.142  1036  2307 I ActivityManager: Killing 5688:com.lge.qremote/u0a112 (adj 15): empty #17
08-30 10:20:49.143  2209  2209 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29997
08-30 10:20:49.145  6735  6735 D UEI.SmartControl: Quickset Services start...
08-30 10:20:49.149  6735  6735 I UEI.SmartControl: Manufacture = LGE
08-30 10:20:49.149  6735  6735 D UEI.SmartControl: Id = LGNevo
08-30 10:20:49.151  6735  6735 D UEI.SmartControl: File observer start...
,08-30 10:20:49.152  6735  6735 E UEI.SmartControl: IR Port is disabled: false
08-30 10:20:49.152  6735  6735 D UEI.SmartControl: Starting file observer...
08-30 10:20:49.153  6735  6735 D UEI.SmartControl: Extracting JNI libs...
08-30 10:20:49.153  6735  6735 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
08-30 10:20:49.233  6735  6735 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
08-30 10:20:49.234  6735  6735 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
,08-30 10:20:49.234  6735  6735 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
08-30 10:20:49.260  6735  6735 I UEI.SmartControl: --- Selecting new region: 6
,08-30 10:20:49.262  6735  6735 I UEI.SmartControl: Model = LG-D855
08-30 10:20:49.263  6735  6735 D UEI.SmartControl: QS Service created
08-30 10:20:49.265  1036  1763 W libprocessgroup: failed to open /acct/uid_10112/pid_5688/cgroup.procs: No such file or directory
08-30 10:20:49.283  6735  6735 I UEI.SmartControl: Service initServices...
08-30 10:20:49.286  6735  6735 D UEI.SmartControl: QS start get config
,08-30 10:20:49.325  6735  6735 D UEI.SmartControl: Loading JNI Libs...
,08-30 10:20:49.620  6735  6735 I UEI.SmartControl: Supports setup maps: true
08-30 10:20:49.624  6735  6735 D UEI.SmartControl: QS start statue = true Error code = 0
08-30 10:20:49.624  6735  6735 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-30 10:20:49.624  6735  6735 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-30 10:20:49.624  6735  6735 I UEI.SmartControl: ### init IR Blaster...
,08-30 10:20:49.629  6735  6735 D serial_port: Configuring serial port
08-30 10:20:49.633  6735  6735 E UEI.SmartControl: UEIBLaster setting for 616
08-30 10:20:49.633  6735  6735 I UEI.SmartControl: Setting serial record hearder size = 2
08-30 10:20:49.633  6735  6735 I UEI.SmartControl: configuring settings for MAXQ616
08-30 10:20:49.633  6735  6735 I UEI.SmartControl: Get version...
08-30 10:20:49.649  6735  6766 D UEI.SmartControl: serial port data available: 21
,08-30 10:20:49.672  6573  6637 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,08-30 10:20:49.676  6735  6735 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-30 10:20:49.676  6735  6735 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-30 10:20:49.676  6735  6735 I UEI.SmartControl: QS saving settings...
08-30 10:20:49.677  6735  6735 D UEI.SmartControl: IR Blaster version: 25672567
08-30 10:20:49.693  6735  6766 D UEI.SmartControl: serial port data available: 4
,08-30 10:20:49.724  6735  6771 I UEI.SmartControl: Device manager: loading config....
08-30 10:20:49.724  6735  6771 D UEI.SmartControl: ----------- loading internal config...
,08-30 10:20:49.729  6735  6735 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-30 10:20:49.734  6735  6735 E UEI.SmartControl: Services init done
08-30 10:20:49.734  6735  6735 D UEI.SmartControl: QS Service init finished
08-30 10:20:49.735  6735  6735 D UEI.SmartControl: QS Service version name: 2.1.91
08-30 10:20:49.735  6735  6735 D UEI.SmartControl: QS Service version code: 201091
,08-30 10:20:49.737  6735  6735 D UEI.SmartControl: Service requested: Control
08-30 10:20:49.741  6735  6771 E UEI.SmartControl: Loading SETTINGS...
08-30 10:20:49.743  6735  6735 D UEI.SmartControl: Request IControl service: devices are loaded...
08-30 10:20:49.746  6735  6735 D UEI.SmartControl: Service.onUnbind: IControl
08-30 10:20:49.747  6735  6735 D UEI.SmartControl: Service.onDestroy
08-30 10:20:49.747  6735  6735 D UEI.SmartControl: Lock is in USE false
08-30 10:20:49.747  6735  6735 D UEI.SmartControl: unbind internal service
,08-30 10:20:49.753  6735  6735 D serial_port: close(fd = 25)
08-30 10:20:49.755  6735  6771 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-30 10:20:49.762  6735  6735 I UEI.SmartControl: Serial port is closed.
08-30 10:20:49.762  6735  6735 I UEI.SmartControl: Serial port is closed.
08-30 10:20:49.762  6735  6735 D UEI.SmartControl: Blaster closed
08-30 10:20:49.763  6735  6735 D UEI.SmartControl: Shut down QS...
08-30 10:20:49.763  6735  6735 D UEI.SmartControl: Stopping QS lib
08-30 10:20:49.763  6735  6735 D UEI.SmartControl: QS lib stop result = true
08-30 10:20:49.764  6735  6735 D UEI.SmartControl: Stopped QS lib
08-30 10:20:49.764  6735  6770 I UEI.SmartControl: Notify AllClients services are ready: 0
08-30 10:20:49.764  6735  6770 D UEI.SmartControl: -----service ready thread exits
,08-30 10:20:49.767  6735  6735 D UEI.SmartControl: Stopped file observer...
08-30 10:20:49.768  6735  6735 D UEI.SmartControl: QS shutdown complete
08-30 10:20:49.770  6735  6735 D UEI.SmartControl: QS Service created
08-30 10:20:49.798  6735  6735 I UEI.SmartControl: Service initServices...
08-30 10:20:49.798  6735  6735 D UEI.SmartControl: QS start get config
,08-30 10:20:50.172  6735  6735 I UEI.SmartControl: Supports setup maps: true
,08-30 10:20:50.175  6735  6735 D UEI.SmartControl: QS start statue = true Error code = 0
08-30 10:20:50.175  6735  6735 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-30 10:20:50.175  6735  6735 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-30 10:20:50.175  6735  6735 I UEI.SmartControl: ### init IR Blaster...
08-30 10:20:50.179  6735  6735 D serial_port: Configuring serial port
08-30 10:20:50.179  6735  6735 E UEI.SmartControl: UEIBLaster setting for 616
08-30 10:20:50.179  6735  6735 I UEI.SmartControl: Setting serial record hearder size = 2
08-30 10:20:50.179  6735  6735 I UEI.SmartControl: configuring settings for MAXQ616
08-30 10:20:50.179  6735  6735 I UEI.SmartControl: Get version...
08-30 10:20:50.197  6735  6775 D UEI.SmartControl: serial port data available: 21
,08-30 10:20:50.228  6735  6735 D UEI.SmartControl: MAXQ616 A2-X4 software.
,08-30 10:20:50.228  6735  6735 I UEI.SmartControl: IR Blaster version: 256702256704300002
,08-30 10:20:50.228  6735  6735 I UEI.SmartControl: QS saving settings...
,08-30 10:20:50.230  6735  6735 D UEI.SmartControl: IR Blaster version: 25672567
,08-30 10:20:50.246  6735  6775 D UEI.SmartControl: serial port data available: 4
08-30 10:20:50.276  6735  6779 I UEI.SmartControl: Device manager: loading config....
08-30 10:20:50.277  6735  6779 D UEI.SmartControl: ----------- loading internal config...
08-30 10:20:50.278  6735  6735 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-30 10:20:50.282  6735  6735 E UEI.SmartControl: Services init done
08-30 10:20:50.282  6735  6735 D UEI.SmartControl: QS Service init finished
08-30 10:20:50.284  6735  6735 D UEI.SmartControl: QS Service version name: 2.1.91
08-30 10:20:50.284  6735  6735 D UEI.SmartControl: QS Service version code: 201091
08-30 10:20:50.285  6735  6735 D UEI.SmartControl: Service requested: Control
08-30 10:20:50.288  6735  6779 E UEI.SmartControl: Loading SETTINGS...
08-30 10:20:50.290  6735  6735 D UEI.SmartControl: Request IControl service: devices are loaded...
08-30 10:20:50.295  1036  1764 I ActivityManager: Killing 6280:com.android.calendar/u0a13 (adj 15): empty #17
,08-30 10:20:50.303  6735  6779 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-30 10:20:50.317  6735  6778 I UEI.SmartControl: Notify AllClients services are ready: 0
08-30 10:20:50.317  6735  6778 D UEI.SmartControl: -----service ready thread exits
,08-30 10:20:50.383  1036  1561 W libprocessgroup: failed to open /acct/uid_10013/pid_6280/cgroup.procs: No such file or directory
,08-30 10:20:50.389  6735  6735 E ActivityThread: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.g@26c733ca that was originally bound here
08-30 10:20:50.389  6735  6735 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.g@26c733ca that was originally bound here
08-30 10:20:50.389  6735  6735 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1167)
08-30 10:20:50.389  6735  6735 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1061)
08-30 10:20:50.389  6735  6735 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1839)
08-30 10:20:50.389  6735  6735 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:1822)
08-30 10:20:50.389  6735  6735 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
08-30 10:20:50.389  6735  6735 E ActivityThread: 	at com.uei.control.Service.b(Unknown Source)
08-30 10:20:50.389  6735  6735 E ActivityThread: 	at com.uei.control.Service.a(Unknown Source)
08-30 10:20:50.389  6735  6735 E ActivityThread: 	at com.uei.control.Service.onCreate(Unknown Source)
08-30 10:20:50.389  6735  6735 E ActivityThread: 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2738)
08-30 10:20:50.389  6735  6735 E ActivityThread: 	at android.app.ActivityThread.access$1800(ActivityThread.java:148)
08-30 10:20:50.389  6735  6735 E ActivityThread: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
08-30 10:20:50.389  6735  6735 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 10:20:50.389  6735  6735 E ActivityThread: ,	at android.os.Looper.loop(Looper.java:135)
08-30 10:20:50.389  6735  6735 E ActivityThread: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-30 10:20:50.389  6735  6735 E ActivityThread: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 10:20:50.389  6735  6735 E ActivityThread: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 10:20:50.389  6735  6735 E ActivityThread: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-30 10:20:50.389  6735  6735 E ActivityThread: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,08-30 10:20:50.390  6735  6735 D UEI.SmartControl: Internal service binding...
08-30 10:20:50.748  6735  6773 D UEI.SmartControl: Internal timer expired: 2
,08-30 10:20:52.374  1826  6476 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,08-30 10:20:52.383   316  6784 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,08-30 10:20:52.384   316  6784 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
08-30 10:20:52.384   316  6784 D libc-netbsd: res_queryN name = android.clients.google.com succeed
08-30 10:20:52.584  1826  1826 I ConfigFetchService: fetch service done; releasing wakelock
,08-30 10:20:52.590  1826  1826 I ConfigFetchService: stopping self
08-30 10:20:52.602  2229  2229 I ConfigService: onDestroy
,08-30 10:20:54.143  6735  6746 E UEI.SmartControl: file observer is disposed!
,08-30 10:20:55.281  6735  6780 D UEI.SmartControl: Internal timer expired: 3
,08-30 10:20:55.282  6735  6780 D UEI.SmartControl: unbind internal service
,08-30 10:20:55.301  6735  6735 D UEI.SmartControl: Service.onUnbind: IControl
08-30 10:20:55.302  6735  6735 D UEI.SmartControl: Service.onDestroy
08-30 10:20:55.302  6735  6735 D UEI.SmartControl: Lock is in USE false
08-30 10:20:55.302  6735  6735 D UEI.SmartControl: unbind internal service
08-30 10:20:55.302  6735  6735 D serial_port: close(fd = 24)
,08-30 10:20:55.310  6735  6735 I UEI.SmartControl: Serial port is closed.
,08-30 10:20:55.310  6735  6735 I UEI.SmartControl: Serial port is closed.
,08-30 10:20:55.310  6735  6735 D UEI.SmartControl: Blaster closed
,08-30 10:20:55.310  6735  6735 D UEI.SmartControl: Shut down QS...
08-30 10:20:55.310  6735  6735 D UEI.SmartControl: Stopping QS lib
08-30 10:20:55.310  6735  6735 D UEI.SmartControl: QS lib stop result = true
08-30 10:20:55.310  6735  6735 D UEI.SmartControl: Stopped QS lib
08-30 10:20:55.311  6735  6735 D UEI.SmartControl: QS shutdown complete
08-30 10:20:56.716  6615  6733 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-30 10:20:56.716  6615  6733 I jxcore-log: 
08-30 10:20:56.719  6615  6733 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-30 10:20:56.719  6615  6733 I jxcore-log: 
,08-30 10:20:56.722  6615  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 10:20:56.722  6615  6733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 10:20:56.722  6615  6733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 10:20:56.722  6615  6733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 10:20:56.722  6615  6733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 10:20:56.722  6615  6733 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 10:20:56.722  6615  6733 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 10:20:56.722  6615  6733 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 10:20:56.724  6615  6733 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e,
08-30 10:20:56.726  6615  6733 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native,
08-30 10:20:56.726  6615  6733 I jxcore-log: 
,08-30 10:20:56.728  6615  6733 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native,
08-30 10:20:56.728  6615  6733 I jxcore-log: 
,08-30 10:20:57.232  6615  6733 I jxcore-log: Unit Test app is loaded
,08-30 10:20:57.232  6615  6733 I jxcore-log: 
,08-30 10:20:57.245  6615  6733 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 10:20:57.245  6615  6733 I jxcore-log: 
08-30 10:20:57.247  6615  6615 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-30 10:20:57.251  6615  6733 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 10:20:57.251  6615  6733 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36eeedbe added. We now have 2 listener(s)
08-30 10:20:57.251  1036  2305 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 10:20:57.256  6615  6733 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 10:20:57.256  6615  6733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 10:20:57.256  6615  6733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 10:20:57.256  6615  6733 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 10:20:57.257  6615  6733 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f1f4e1f added. We now have 2 listener(s)
08-30 10:20:57.257  6615  6733 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 10:20:57.257  6615  6733 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 10:20:57.259  6615  6733 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 10:20:57.261  6615  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 10:20:57.261  6615  6733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 10:20:57.261  6615  6733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 10:20:57.261  6615  6733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 10:20:57.261  6615  6733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 10:20:57.261  6615  6733 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 10:20:57.261  6615  6733 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 10:20:57.261  6615  6733 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 10:20:57.262  6615  6733 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 10:20:57.262  6615  6733 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 10:20:57.263  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 10:20:57.264  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 10:20:57.265  6615  6733 D ExecuteNativeTests: Running unit tests
08-30 10:20:57.417  6615  6733 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 10:20:57.418  6615  6733 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3581e7a5 added. We now have 3 listener(s)
08-30 10:20:57.418  1036  1933 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-30 10:20:57.422  6615  6733 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 10:20:57.422  6615  6733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 10:20:57.422  6615  6733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 10:20:57.422  6615  6733 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 10:20:57.422  6615  6733 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b82177a added. We now have 3 listener(s)
08-30 10:20:57.422  6615  6733 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 10:20:57.423  6615  6733 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 10:20:57.426  6615  6733 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 10:20:57.431  6615  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 10:20:57.431  6615  6733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 10:20:57.431  6615  6733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 10:20:57.431  6615  6733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 10:20:57.431  6615  6733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 10:20:57.431  6615  6733 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 10:20:57.431  6615  6733 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 10:20:57.431  6615  6733 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 10:20:57.433  6615  6733 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 10:20:57.433  6615  6733 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 10:20:57.435  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 10:20:57.438  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 10:20:57.441  1036  1104 I ActivityManager: Waited long enough for: ServiceRecord{3d20fb71 u0 com.google.android.gms/.wearable.service.WearableService}
08-30 10:20:57.441  6615  6733 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-30 10:20:57.443  6615  6733 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 10:20:57.444  6615  6733 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 10:20:57.444  6615  6733 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-30 10:20:57.451  6615  6733 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-30 10:20:57.452  6615  6733 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-30 10:20:57.452  6615  6733 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-30 10:20:57.454  6615  6733 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 10:20:57.454  6615  6733 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 10:20:57.454  6615  6733 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 10:20:57.455  6615  6733 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 10:20:57.456  6615  6733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 10:20:57.456  6615  6733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 10:20:57.456  6615  6733 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 10:20:57.456  6615  6733 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3581e7a5 removed from the list
08-30 10:20:57.456  6615  6733 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 10:20:57.456  6615  6733 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b82177a removed from the list
08-30 10:20:57.456  6615  6733 D io.jxcore.node.ConnectivityMonitor: stop
08-30 10:20:57.457  6615  6733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 10:20:57.459  6615  6733 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-30 10:20:57.460  6615  6733 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 10:20:57.460  6615  6733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 10:20:57.460  6615  6733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 10:20:57.460  6615  6733 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3581e7a5 not in the list
08-30 10:20:57.460  6615  6733 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 10:20:57.460  6615  6733 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b82177a not in the list
08-30 10:20:57.460  6615  6733 D io.jxcore.node.ConnectivityMonitor: stop
08-30 10:20:57.460  6615  6733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 10:20:57.460  6615  6733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 10:20:57.467  6615  6733 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-30 10:20:57.468  6615  6733 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-30 10:20:57.468  6615  6733 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-30 10:20:57.468  6615  6733 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-30 10:20:57.468  6615  6733 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-30 10:20:57.468  6615  6733 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-30 10:20:57.468  6615  6733 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-30 10:20:57.468  6615  6733 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-30 10:20:57.468  6615  6733 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-30 10:20:57.468  6615  6733 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-30 10:20:57.468  6615  6733 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-30 10:20:57.468  6615  6733 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-30 10:20:57.468  6615  6733 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-30 10:20:57.468  6615  6733 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-30 10:20:57.468  6615  6733 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-30 10:20:57.468  6615  6733 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-30 10:20:57.468  6615  6733 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-30 10:20:57.468  6615  6733 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-30 10:20:57.468  6615  6733 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-30 10:20:57.468  6615  6733 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-30 10:20:57.468  6615  6733 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,08-30 10:20:57.468  6615  6733 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-30 10:20:57.469  6615  6733 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-30 10:20:57.469  6615  6733 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-30 10:20:57.469  6615  6733 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310],
08-30 10:20:57.469  6615  6733 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-30 10:20:57.469  6615  6733 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-30 10:20:57.469  6615  6733 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610],
08-30 10:20:57.469  6615  6733 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-30 10:20:57.469  6615  6733 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-30 10:20:57.469  6615  6733 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,08-30 10:20:57.469  6615  6733 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 10:20:57.469  6615  6733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 10:20:57.469  6615  6733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 10:20:57.469  6615  6733 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3581e7a5 not in the list
08-30 10:20:57.469  6615  6733 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 10:20:57.469  6615  6733 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b82177a not in the list
,08-30 10:20:57.469  6615  6733 D io.jxcore.node.ConnectivityMonitor: stop
08-30 10:20:57.469  6615  6733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 10:20:57.469  6615  6733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 10:20:57.474  6615  6733 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-30 10:20:57.476  6615  6733 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 10:20:57.479  6615  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
,08-30 10:20:57.479  6615  6733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 10:20:57.479  6615  6733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 10:20:57.479  6615  6733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 10:20:57.479  6615  6733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 10:20:57.479  6615  6733 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 10:20:57.479  6615  6733 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 10:20:57.479  6615  6733 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 10:20:57.480  6615  6733 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 10:20:57.480  6615  6733 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 10:20:57.482  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 10:20:57.484  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 10:20:57.485  6615  6733 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 10:20:57.486  6615  6733 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-30 10:20:57.486  6615  6733 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 10:20:57.486  6615  6733 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 10:20:57.486  6615  6733 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-30 10:20:57.490  6615  6733 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-30 10:20:57.491  1036  1729 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 10:20:57.497  6615  6733 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-30 10:20:57.503  6615  6733 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-30 10:20:57.505  6615  6733 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
,08-30 10:20:57.506  6615  6733 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 10:20:57.507  6615  6733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 10:20:57.508  6615  6733 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-30 10:20:57.509  6615  6733 I io.jxcore.node.ConnectionHelper: start: OK
08-30 10:20:58.086  1036  1364 V AlarmManager: RTC_WAKEUP set : Alarm{32accebd type 0 when 1472545257953 com.android.vending} when 1472545257953
,08-30 10:20:58.144  4541  6788 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,08-30 10:20:58.279  1036  2080 V SIM_STK : Menu title from STK is T-Mobile
,08-30 10:20:58.391  6127  6127 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.
,08-30 10:20:59.147  2209  2209 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19995
,08-30 10:21:00.055  1586  1586 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-30 10:21:00.056  1586  1586 I KeyguardUpdateMonitor: called onTimeUpdated()
08-30 10:21:00.056  1586  1586 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
,08-30 10:21:00.061  1586  1586 I [SystemUI]Clock: called onTimeUpdated()
08-30 10:21:00.066  1586  1586 I LgeClockWidgetControlView: called onTimeUpdated()
08-30 10:21:00.066  1586  1586 I [SystemUI]DateView: called onTimeUpdated()
08-30 10:21:00.070  1586  1586 I [SystemUI]DateView: called onTimeUpdated()
,08-30 10:21:00.077  1586  1586 D KeyguardUpdateMonitor: handleTimeUpdate
08-30 10:21:02.523  6615  6733 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 10:21:02.527  6615  6733 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-30 10:21:02.527  6615  6733 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 10:21:07.534  6615  6733 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-30 10:21:07.534  6615  6733 V io.jxcore.node.ConnectivityMonitor: start: Already started
08-30 10:21:07.534  6615  6733 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 10:21:07.534  6615  6733 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 10:21:07.535  6615  6733 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 10:21:07.535  6615  6733 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 10:21:07.535  6615  6733 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-30 10:21:07.550  6615  6733 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 10:21:07.550  6615  6733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 10:21:07.552  6615  6733 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-30 10:21:07.553  6615  6733 I io.jxcore.node.ConnectionHelper: start: OK
08-30 10:21:12.559  6615  6733 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 10:21:12.559  6615  6733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 10:21:12.559  6615  6733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 10:21:12.560  6615  6733 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3581e7a5 not in the list
08-30 10:21:12.560  6615  6733 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 10:21:12.560  6615  6733 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b82177a not in the list
08-30 10:21:12.560  6615  6733 D io.jxcore.node.ConnectivityMonitor: stop
08-30 10:21:12.560  6615  6733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 10:21:12.577  6615  6733 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-30 10:21:12.580  6615  6733 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 10:21:12.585  6615  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 10:21:12.585  6615  6733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 10:21:12.585  6615  6733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 10:21:12.585  6615  6733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 10:21:12.585  6615  6733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 10:21:12.585  6615  6733 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 10:21:12.585  6615  6733 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 10:21:12.585  6615  6733 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 10:21:12.588  6615  6733 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 10:21:12.588  6615  6733 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 10:21:12.590  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 10:21:12.592  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 10:21:12.593  6615  6733 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 10:21:12.593  6615  6733 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 10:21:12.593  6615  6733 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 10:21:12.593  6615  6733 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 10:21:12.593  6615  6733 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 10:21:12.599  6615  6733 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-30 10:21:12.601  6615  6733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-30 10:21:12.603  6615  6733 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-30 10:21:12.603  6615  6733 I io.jxcore.node.ConnectionHelper: start: OK
08-30 10:21:17.604  6615  6733 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 10:21:17.604  6615  6733 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 10:21:17.604  6615  6733 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-30 10:21:19.150  2209  2209 I CloudHub: [CLIENT][CloudHubClientFactory$1|onFinish] Time is up to exit
,08-30 10:21:19.157  2209  2209 I CloudHub: [CLIENT][CloudHubClientFactory$1|onFinish] Scheduler destroyed
,08-30 10:21:22.615  6615  6733 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 10:21:22.615  6615  6733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 10:21:22.616  6615  6733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 10:21:22.616  6615  6733 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3581e7a5 not in the list
08-30 10:21:22.616  6615  6733 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 10:21:22.616  6615  6733 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b82177a not in the list
08-30 10:21:22.616  6615  6733 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 10:21:22.616  6615  6733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
,08-30 10:21:22.633  6615  6733 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-30 10:21:22.633  6615  6733 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 10:21:22.633  6615  6733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 10:21:22.633  6615  6733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 10:21:22.633  6615  6733 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3581e7a5 not in the list
08-30 10:21:22.633  6615  6733 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 10:21:22.634  6615  6733 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b82177a not in the list
08-30 10:21:22.634  6615  6733 D io.jxcore.node.ConnectivityMonitor: stop
08-30 10:21:22.634  6615  6733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 10:21:22.634  6615  6733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 10:21:22.635  6615  6733 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-30 10:21:22.636  6615  6733 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 10:21:22.636  6615  6733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 10:21:22.637  6615  6733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 10:21:22.637  6615  6733 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3581e7a5 not in the list
08-30 10:21:22.637  6615  6733 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 10:21:22.637  6615  6733 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b82177a not in the list
08-30 10:21:22.637  6615  6733 D io.jxcore.node.ConnectivityMonitor: stop
08-30 10:21:22.637  6615  6733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 10:21:22.637  6615  6733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 10:21:22.638  6615  6733 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-30 10:21:22.638  6615  6733 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 10:21:22.638  6615  6733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 10:21:22.638  6615  6733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 10:21:22.638  6615  6733 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3581e7a5 not in the list
08-30 10:21:22.638  6615  6733 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 10:21:22.638  6615  6733 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b82177a not in the list
08-30 10:21:22.638  6615  6733 D io.jxcore.node.ConnectivityMonitor: stop
08-30 10:21:22.638  6615  6733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.Bluetooth,Manager: release: The given listener does not exist in the list - probably already removed
08-30 10:21:22.638  6615  6733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 10:21:22.639  6615  6733 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-30 10:21:22.639  6615  6733 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 10:21:22.639  6615  6733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 10:21:22.639  6615  6733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 10:21:22.639  6615  6733 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3581e7a5 not in the list
08-30 10:21:22.639  6615  6733 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 10:21:22.639  6615  6733 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b82177a not in the list
08-30 10:21:22.640  6615  6733 D io.jxcore.node.ConnectivityMonitor: stop
08-30 10:21:22.640  6615  6733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-30 10:21:22.640  6615  6733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 10:21:22.640  6615  6733 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-30 10:21:22.644  6615  6733 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 10:21:22.644  6615  6733 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-30 10:21:22.644  6615  6733 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-30 10:21:22.644  6615  6733 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 10:21:22.644  6615  6733 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 10:21:22.644  6615  6733 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-30 10:21:22.644  6615  6733 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 10:21:22.644  6615  6733 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1,
08-30 10:21:22.645  6615  6733 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 10:21:22.645  6615  6733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 10:21:22.645  6615  6733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 10:21:22.645  6615  6733 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3581e7a5 not in the list
08-30 10:21:22.645  6615  6733 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 10:21:22.645  6615  6733 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b82177a not in the list
,08-30 10:21:22.645  6615  6733 D io.jxcore.node.ConnectivityMonitor: stop
08-30 10:21:22.645  6615  6733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 10:21:22.645  6615  6733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 10:21:22.646  6615  6733 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-30 10:21:22.655  6615  6733 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-30 10:21:22.655  6615  6733 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-30 10:21:22.663  6615  6733 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 10:21:22.664  6615  6733 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-30 10:21:22.664  6615  6733 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-30 10:21:22.664  6615  6733 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-30 10:21:22.664  6615  6733 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-30 10:21:22.664  6615  6733 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-30 10:21:22.664  6615  6733 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-30 10:21:22.664  6615  6733 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-30 10:21:22.664  6615  6733 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-30 10:21:22.664  6615  6733 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-30 10:21:22.664  6615  6733 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,08-30 10:21:22.667  6615  6733 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-30 10:21:22.667  6615  6733 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-30 10:21:22.667  6615  6733 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-30 10:21:22.667  6615  6733 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-30 10:21:22.670  6615  6733 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-30 10:21:22.670  6615  6733 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-30 10:21:22.670  6615  6733 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-30 10:21:22.670  6615  6733 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-30 10:21:22.671  6615  6733 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-30 10:21:22.671  6615  6733 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-30 10:21:22.671  6615  6733 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-30 10:21:22.671  6615  6733 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-30 10:21:22.671  6615  6733 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-30 10:21:22.671  6615  6733 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-30 10:21:22.671  6615  6733 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-30 10:21:22.672  6615  6733 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-30 10:21:22.672  6615  6733 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-30 10:21:22.672  6615  6733 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-30 10:21:22.672  6615  6733 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-30 10:21:22.672  6615  6733 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-30 10:21:22.672  6615  6733 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-30 10:21:22.673  6615  6733 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-30 10:21:22.673  6615  6733 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-30 10:21:22.674  6615  6733 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-30 10:21:22.675  6615  6733 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 10:21:22.675  6615  6733 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-30 10:21:22.675  6615  6733 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-30 10:21:22.675  6615  6733 I io.jxcore.node.Connect,ionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 10:21:22.675  6615  6733 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-30 10:21:22.675  6615  6733 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-30 10:21:22.678  6615  6733 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-30 10:21:22.679  6615  6733 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-30 10:21:22.679  6615  6733 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-30 10:21:22.680  6615  6733 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-30 10:21:22.680  6615  6733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-30 10:21:22.680  6615  6733 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-30 10:21:22.681  6615  6733 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 10:21:22.681  6615  6733 E io.jxcore.node.ConnectionHelper: connect: Callback is null
,08-30 10:21:22.688  6615  6813 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 826)
08-30 10:21:22.681  6615  6733 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 10:21:22.691  6615  6733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 10:21:22.691  6615  6733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 10:21:22.691  6615  6733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-30 10:21:22.692  6615  6733 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3581e7a5 not in the list
08-30 10:21:22.692  6615  6733 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 10:21:22.692  6615  6733 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b82177a not in the list
08-30 10:21:22.692  6615  6733 D io.jxcore.node.ConnectivityMonitor: stop
08-30 10:21:22.692  6615  6733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 10:21:22.692  6615  6733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 10:21:22.694  6615  6733 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-30 10:21:22.694  6615  6733 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 10:21:22.694  6615  6733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 10:21:22.694  6615  6733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 10:21:22.694  6615  6733 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3581e7a5 not in the list
08-30 10:21:22.694  6615  6733 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 10:21:22.694  6615  6733 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b82177a not in the list
08-30 10:21:22.694  6615  6733 D io.jxcore.node.ConnectivityMonitor: stop
08-30 10:21:22.694  6615  6733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 10:21:22.694  6615  6733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 10:21:22.695  6615  6733 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-30 10:21:22.696  6615  6733 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 10:21:22.696  6615  6733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 10:21:22.696  6615  6733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 10:21:22.696  6615  6733 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3581e7a5 not in the list
08-30 10:21:22.696  6615  6733 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 10:21:22.696  6615  6733 E org.thaliproject.p2p.btconnectorlib.DiscoveryMa,nagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b82177a not in the list
08-30 10:21:22.696  6615  6733 D io.jxcore.node.ConnectivityMonitor: stop
08-30 10:21:22.696  6615  6733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 10:21:22.696  6615  6733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 10:21:22.697  6615  6733 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-30 10:21:22.697  6615  6733 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-30 10:21:22.697  6615  6733 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-30 10:21:22.697  6615  6733 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-30 10:21:22.697  6615  6733 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-30 10:21:22.698  6615  6733 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-30 10:21:22.698  6615  6733 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,08-30 10:21:22.698  6615  6733 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-30 10:21:22.698  6615  6733 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-30 10:21:22.698  6615  6733 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55,
08-30 10:21:22.698  6615  6733 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-30 10:21:22.698  6615  6733 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-30 10:21:22.698  6615  6733 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 10:21:22.698  6615  6733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 10:21:22.698  6615  6733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 10:21:22.698  6615  6733 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3581e7a5 not in the list
08-30 10:21:22.698  6615  6733 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 10:21:22.698  6615  6733 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b82177a not in the list
08-30 10:21:22.698  6615  6733 D io.jxcore.node.ConnectivityMonitor: stop
08-30 10:21:22.698  6615  6733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 10:21:22.698  6615  6733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 10:21:22.715  6615  6733 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-30 10:21:22.724  6615  6814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 826
08-30 10:21:22.725  6615  6814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 826)
08-30 10:21:22.725  6615  6814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 826)
08-30 10:21:22.843  6615  6813 W LGMDMUISystemServiceAdapter: checkBluetoothPairing btPolicy: false
08-30 10:21:22.844  6615  6813 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 826)
,08-30 10:21:22.872  1036  1933 I art     : Explicit concurrent mark sweep GC freed 19442(924KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/64MB, paused 1.464ms total 143.308ms
,08-30 10:21:22.874  6615  6733 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 10:21:22.879  6615  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 10:21:22.879  6615  6733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 10:21:22.879  6615  6733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 10:21:22.879  6615  6733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 10:21:22.879  6615  6733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 10:21:22.879  6615  6733 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 10:21:22.879  6615  6733 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 10:21:22.879  6615  6733 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 10:21:22.881  6615  6733 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 10:21:22.882  6615  6733 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 10:21:22.882  6615  6733 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 10:21:22.883  6615  6733 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 10:21:22.883  6615  6733 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 10:21:22.883  6615  6733 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 10:21:22.883  6615  6733 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 10:21:22.884  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 10:21:22.888  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 10:21:22.893  6615  6733 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 10:21:22.893  6615  6733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 10:21:22.894  6615  6733 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-30 10:21:22.894  6615  6733 I io.jxcore.node.ConnectionHelper: start: OK
,08-30 10:21:27.895  6615  6733 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 10:21:27.895  6615  6733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 10:21:27.895  6615  6733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 10:21:27.895  6615  6733 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3581e7a5 not in the list
08-30 10:21:27.895  6615  6733 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 10:21:27.895  6615  6733 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b82177a not in the list
08-30 10:21:27.895  6615  6733 D io.jxcore.node.ConnectivityMonitor: stop
08-30 10:21:27.895  6615  6733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 10:21:32.902  6615  6733 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 10:21:32.902  6615  6733 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b82177a not in the list
08-30 10:21:32.902  6615  6733 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 10:21:32.903  6615  6733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 10:21:32.903  6615  6733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 10:21:32.903  6615  6733 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3581e7a5 not in the list
08-30 10:21:32.903  6615  6733 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 10:21:32.903  6615  6733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 10:21:32.903  6615  6733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 10:21:32.904  6615  6733 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3581e7a5 not in the list
08-30 10:21:32.904  6615  6733 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 10:21:32.904  6615  6733 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b82177a not in the list
08-30 10:21:32.904  6615  6733 D io.jxcore.node.ConnectivityMonitor: stop
08-30 10:21:32.904  6615  6733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 10:21:32.904  6615  6733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 10:21:32.910  6615  6733 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-30 10:21:32.911  6615  6733 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 10:21:32.920  6615  6733 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-30 10:21:32.921  6615  6733 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-30 10:21:32.921  6615  6733 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-30 10:21:32.922  6615  6615 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-30 10:21:32.922  6615  6733 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-30 10:21:32.922  6615  6733 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-30 10:21:32.923  6615  6733 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 10:21:32.924  6615  6733 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-30 10:21:32.924  6615  6733 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-30 10:21:32.924  6615  6733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-30 10:21:32.924  6615  6733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 10:21:32.924  6615  6733 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-30 10:21:32.926  6615  6841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-30 10:21:32.926  6615  6841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-30 10:21:32.927  6615  6615 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-30 10:21:32.927  6615  6733 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3581e7a5 not in the list
08-30 10:21:32.927  6615  6733 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 10:21:32.927  6615  6733 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 10:21:32.927  6615  6733 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 10:21:32.927  6615  6733 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 10:21:32.928  6615  6733 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-30 10:21:32.935  6615  6733 D BluetoothLeScanner: could not find callback wrapper
08-30 10:21:32.935  6615  6733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 10:21:32.935  6615  6733 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-30 10:21:32.935  6615  6733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 10:21:32.935  6615  6733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 10:21:32.937  6615  6733 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 10:21:32.937  6615  6615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 10:21:32.937  6615  6615 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-30 10:21:32.937  6615  6615 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 10:21:32.938  6615  6615 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 10:21:32.938  6615  6733 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b82177a not in the list
08-30 10:21:32.938  6615  6733 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 10:21:32.938  6615  6733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 10:21:32.938  6615  6733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 10:21:32.938  6615  6733 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3581e7a5 not in the list
08-30 10:21:32.938  6615  6733 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 10:21:32.938  6615  6733 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b82177a not in the list
08-30 10:21:32.938  6615  6733 D io.jxcore.node.ConnectivityMonitor: stop
08-30 10:21:32.938  6615  6733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 10:21:32.938  6615  6733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 10:21:32.940  6615  6733 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-30 10:21:32.941  6615  6733 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-30 10:21:32.941  6615  6733 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-30 10:21:32.947  6615  6733 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 10:21:32.947  6615  6733 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 10:21:32.948  6615  6733 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 10:21:32.948  6615  6733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 10:21:32.948  6615  6733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 10:21:32.949  6615  6733 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3581e7a5 not in the list
08-30 10:21:32.949  6615  6733 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 10:21:32.949  6615  6733 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b82177a not in the list
08-30 10:21:32.949  6615  6733 D io.jxcore.node.ConnectivityMonitor: stop
08-30 10:21:32.949  6615  6733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 10:21:32.949  6615  6733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 10:21:32.952  1036  1933 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-30 10:21:32.956  1036  1763 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 10:21:32.959  1036  1951 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 10:21:32.959  6615  6733 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 10:21:32.960  6615  6733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 10:21:32.960  6615  6733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 10:21:32.960  6615  6733 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3581e7a5 not in the list
08-30 10:21:32.960  6615  6733 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 10:21:32.960  6615  6733 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b82177a not in the list
08-30 10:21:32.960  6615  6733 D io.jxcore.node.ConnectivityMonitor: stop
08-30 10:21:32.960  6615  6733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 10:21:32.960  6615  6733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 10:21:32.961  6615  6733 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 10:21:32.961  6615  6733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 10:21:32.962  6615  6733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 10:21:32.962  6615  6733 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3581e7a5 not in the list
08-30 10:21:32.962  6615  6733 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 10:21:32.962  6615  6733 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b82177a not in the list
08-30 10:21:32.962  6615  6733 D io.jxcore.node.ConnectivityMonitor: stop
08-30 10:21:32.962  6615  6733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 10:21:32.962  6615  6733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 10:21:32.964  6615  6733 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-30 10:21:32.964  6615  6733 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-30 10:21:32.964  6615  6733 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-30 10:21:32.964  6615  6733 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-30 10:21:32.964  6615  6733 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-30 10:21:32.964  6615  6733 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-30 10:21:32.966  6615  6733 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-30 10:21:32.966  6615  6733 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-30 10:21:32.967  6615  6733 I io.jxcore.node.ConnectionMode,l: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-30 10:21:32.968  6615  6733 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-30 10:21:32.968  6615  6733 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-30 10:21:32.968  6615  6733 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-30 10:21:32.968  6615  6733 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-30 10:21:32.968  6615  6733 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-30 10:21:32.969  6615  6733 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-30 10:21:32.969  6615  6733 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-30 10:21:32.970  6615  6733 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-30 10:21:32.970  6615  6733 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
,08-30 10:21:32.970  6615  6733 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-30 10:21:32.970  6615  6733 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-30 10:21:32.973  6615  6733 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 10:21:32.973  6615  6733 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@256fd3a0 added. We now have 3 listener(s)
08-30 10:21:32.973  6615  6733 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 10:21:32.980  6615  6733 D BluetoothAdapter: enable(): BT is already enabled..!
08-30 10:21:32.982  1036  2002 D WifiServiceImplEx: setWifiEnabled: true pid=6615, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-30 10:21:32.982  1036  2002 D WifiService: setWifiEnabled: true pid=6615, uid=10118
08-30 10:21:32.982  1036  2002 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-30 10:21:33.438  6615  6615 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-30 10:21:37.990  6615  6733 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 10:21:37.990  6615  6733 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@10d80b59 added. We now have 4 listener(s)
,08-30 10:21:37.991  6615  6733 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 10:21:38.007  6615  6733 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 10:21:38.007  6615  6733 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@10d80b59 removed from the list
08-30 10:21:38.007  6615  6733 D io.jxcore.node.ConnectivityMonitor: stop
08-30 10:21:38.007  6615  6733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 10:21:38.007  6615  6733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 10:21:38.008  6615  6733 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 10:21:38.008  6615  6733 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1f48231e added. We now have 4 listener(s)
08-30 10:21:38.008  6615  6733 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 10:21:38.011  6615  6733 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 10:21:38.011  6615  6733 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1f48231e removed from the list
08-30 10:21:38.011  6615  6733 D io.jxcore.node.ConnectivityMonitor: stop
08-30 10:21:38.011  6615  6733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 10:21:38.011  6615  6733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 10:21:38.012  6615  6733 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 10:21:38.012  6615  6733 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@139e47ff added. We now have 4 listener(s)
08-30 10:21:38.012  6615  6733 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 10:21:38.017  1036  1052 D WifiServiceImplEx: setWifiEnabled: false pid=6615, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-30 10:21:38.017  1036  1052 D WifiService: setWifiEnabled: false pid=6615, uid=10118
08-30 10:21:38.018  1036  1052 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 10:21:38.039  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-30 10:21:38.040  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-30 10:21:38.040  1036  1036 D Ulp_jni : JNI:system_update. Event-4
08-30 10:21:38.042  1036  1523 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-30 10:21:38.042  1036  1523 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-30 10:21:38.043  1036  1523 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-30 10:21:38.043  1036  1523 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-30 10:21:38.044  1036  1523 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-30 10:21:38.044  1036  1523 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-30 10:21:38.044  1036  1523 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-30 10:21:38.044  1036  1523 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-30 10:21:38.045  1036  1523 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-30 10:21:38.045  1036  1523 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-30 10:21:38.047  1036  1764 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 10:21:38.047  1036  1764 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@1493e12d mBinding = false
,08-30 10:21:38.056  1036  1523 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-30 10:21:38.057  1036  1522 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 10:21:38.057  1036  1522 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 10:21:38.058  1036  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-30 10:21:38.058  2713  2713 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-30 10:21:38.059  1036  1523 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-30 10:21:38.059  1036  1523 D WifiNative-wlan0: doBoolean: SET ps 1
08-30 10:21:38.063  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-30 10:21:38.063  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-30 10:21:38.063  1036  1036 D Ulp_jni : JNI:system_update. Event-4
,08-30 10:21:38.066  1036  1118 D BluetoothManagerService: Message: 2
08-30 10:21:38.067  1036  1118 D BluetoothManagerService: Sending off request.
08-30 10:21:38.070  3938  4042 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-30 10:21:38.070  6615  6733 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 10:21:38.071  3938  4012 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-30 10:21:38.071  3938  4012 D BluetoothAdapterProperties: Setting state to 13
08-30 10:21:38.071  3938  4012 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-30 10:21:38.072  3938  4012 D BluetoothAdapterProperties: onBluetoothDisable()
08-30 10:21:38.072  3938  4012 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-30 10:21:38.076  3938  4018 D BluetoothAdapterProperties: Scan Mode:20
,08-30 10:21:38.078  3938  4012 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-30 10:21:38.079  3938  4012 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-30 10:21:38.081  3938  4247 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 10:21:38.082  3938  4245 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-30 10:21:38.082  3938  4245 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 10:21:38.082  3938  4245 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-30 10:21:38.082  3938  4245 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-30 10:21:38.082  3938  4245 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-30 10:21:38.082  3938  4245 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-30 10:21:38.082  3938  4245 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-30 10:21:38.082  3938  4245 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-30 10:21:38.082  3938  4270 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 10:21:38.083  3938  4271 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 10:21:38.083  3938  4275 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 10:21:38.085  3938  4124 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-30 10:21:38.085  3938  4124 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-30 10:21:38.090  3938  4124 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 10:21:38.090  3938  4124 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
,08-30 10:21:38.093  3938  4124 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 10:21:38.094  3938  4124 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 10:21:38.094  3938  4124 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 10:21:38.094  3938  4124 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-30 10:21:38.094  3938  4124 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 10:21:38.094  3938  4124 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 10:21:38.094  3938  4124 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 10:21:38.094  3938  4124 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-30 10:21:38.094  3938  4124 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-30 10:21:38.095  3938  4124 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-30 10:21:38.113  1036  1118 D BluetoothManagerService: Message: 60
08-30 10:21:38.113  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-30 10:21:38.113  1036  1118 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
,08-30 10:21:38.118  6615  6733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 10:21:38.118  6615  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 10:21:38.118  6615  6733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 10:21:38.118  6615  6733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 10:21:38.118  6615  6733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 10:21:38.118  6615  6733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 10:21:38.118  6615  6733 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 10:21:38.118  6615  6733 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 10:21:38.118  6615  6733 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 10:21:38.119  6615  6733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 10:21:38.119  6615  6733 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 10:21:38.119  1036  1523 D WifiNative-wlan0: SET ps 1: returned true
08-30 10:21:38.120  1036  2855 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-30 10:21:38.122   316   894 D CommandListener: Clearing all IP addresses on wlan0
08-30 10:21:38.133  6615  6733 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 10:21:38.143  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 10:21:38.148  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 10:21:38.172  6615  6615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 10:21:38.172  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 10:21:38.172  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 10:21:38.172  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 10:21:38.172  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 10:21:38.172  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 10:21:38.172  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 10:21:38.172  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 10:21:38.172  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 10:21:38.187  6615  6615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 10:21:38.187  6615  6615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 10:21:38.194  1036  1104 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6868 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-30 10:21:38.201  1036  1530 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-30 10:21:38.201  1036  1530 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
08-30 10:21:38.201  3938  3938 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-30 10:21:38.201  6615  6615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 10:21:38.201  3938  3938 D BluetoothMapService: STATE_TURNING_OFF
08-30 10:21:38.202  3938  3938 V BluetoothMapService: Handler(): got msg=4
08-30 10:21:38.202  3938  3938 D BluetoothMapService: MAP Service closeService in
08-30 10:21:38.202  3938  3938 D BluetoothMapMasInstance: MAP Service shutdown
08-30 10:21:38.201  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 10:21:38.201  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 10:21:38.201  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 10:21:38.201  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 10:21:38.201  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 10:21:38.201  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 10:21:38.201  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 10:21:38.201  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 10:21:38.202  3938  3938 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-30 10:21:38.202  3938  3938 V BluetoothMapService: MAP Service closeService out
08-30 10:21:38.202  3938  3938 V BtOppService: Receiver DISABLED_ACTION 
08-30 10:21:38.202  3938  3938 I BtOppRfcommListener: stopping Accept Thread
08-30 10:21:38.202  3938  3938 V BtOppRfcommListener: close mBtServerSocket
08-30 10:21:38.203  3938  3938 V BtOppRfcommListener: waiting for thread to terminate
08-30 10:21:38.203  3938  4270 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-30 10:21:38.203  3938  3938 V BtOppRfcommListener: done waiting for thread to terminate
08-30 10:21:38.206  6615  6615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 10:21:38.206  6615  6615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 10:21:38.208  1955  1955 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-30 10:21:38.209  1586  1586 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-30 10:21:38.227  1036  2307 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
,08-30 10:21:38.228  1036  2853 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-30 10:21:38.228  1036  2853 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-30 10:21:38.228  1036  2853 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-30 10:21:38.228  1036  2853 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=4 target=com.android.internal.util.StateMachine$SmHandler }
08-30 10:21:38.228  1036  2853 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on <unknown ssid>
08-30 10:21:38.233  6615  6615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 10:21:38.233  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 10:21:38.233  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 10:21:38.233  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 10:21:38.233  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 10:21:38.233  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 10:21:38.233  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 10:21:38.233  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 10:21:38.233  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 10:21:38.233  6615  6615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 10:21:38.233  6615  6615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 10:21:38.235  6615  6615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 10:21:38.235  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 10:21:38.235  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 10:21:38.235  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 10:21:38.235  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 10:21:38.235  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 10:21:38.235  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 10:21:38.235  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 10:21:38.235  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 10:21:38.235  6615  6615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 10:21:38.235  6615  6615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 10:21:38.236  6615  6615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 10:21:3,8.236  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 10:21:38.236  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 10:21:38.236  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 10:21:38.236  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 10:21:38.236  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 10:21:38.236  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 10:21:38.236  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 10:21:38.236  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 10:21:38.237  6615  6615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 10:21:38.237  6615  6615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 10:21:38.237  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 10:21:38.250  1036  1104 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6890 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-30 10:21:38.252  3938  3938 V BtOppService: onDestroy
08-30 10:21:38.254  1036  1036 D WifiHS20: hidePasspointNotification off =false
08-30 10:21:38.254  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 10:21:38.254  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 10:21:38.254  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,08-30 10:21:38.255  1955  1955 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-30 10:21:38.260   316  6900 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-30 10:21:38.260  1036  1116 D DSQN    : Dns fail occured do internet check.
08-30 10:21:38.260  1036  2853 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
08-30 10:21:38.261  1036  1036 D DSQN    : EVENT_INTERNET_CHECK_REQUEST received
08-30 10:21:38.261  1036  1530 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-30 10:21:38.261  1036  1530 D DSQN    : disableDataServiceNotify
08-30 10:21:38.261  1036  1530 D DSQN    : stop dsqn bin
08-30 10:21:38.261  1036  1036 D DSQN    : try Internet connection check
08-30 10:21:38.262  1036  1036 D WifiHS20: hidePasspointNotification off =false
08-30 10:21:38.263  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 10:21:38.263  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 10:21:38.263  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-30 10:21:38.263  1036  1036 D WifiScanningService: SCAN_AVAILABLE : 1
08-30 10:21:38.263  1036  1523 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 10:21:38.263  1036  1036 D RttService: SCAN_AVAILABLE : 1
,08-30 10:21:38.263  1036  1542 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-30 10:21:38.263  1036  1522 D LGWifiP2pService: InactiveState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-30 10:21:38.263  1036  1543 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-30 10:21:38.263  1036  1522 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-30 10:21:38.263  3938  3938 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-30 10:21:38.263  1036  1522 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@20b31c8c
08-30 10:21:38.264  1036  1530 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-30 10:21:38.264  1036  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 10:21:38.264  1036  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 10:21:38.264  1036  1530 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 10:21:38.265  1036  1523 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 10:21:38.265  1036  1522 D LGWifiP2pService: P2pDisablingState
08-30 10:21:38.265  1036  1522 D LGWifiP2pService: P2pDisablingState{ when=-1ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-30 10:21:38.265  1036  1523 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 10:21:38.265  1036  1522 D LGWifiP2pService: p2p socket connection lost
08-30 10:21:38.265  1036  1522 D LGWifiP2pService: P2pDisabledState
08-30 10:21:38.265  1036  1523 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 10:21:38.265  1036  1523 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 10:21:38.266  1036  1523 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 10:21:38.266  1036  1523 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-30 10:21:38.266  1036  1523 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 10:21:38.267  1036  1523 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 10:21:38.267  1036  1523 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 10:21:38.267  1036  1523 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-30 10:21:38.267  1036  1522 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 10:21:38.267  1036  1522 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 10:21:38.267  1036  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-30 10:21:38.268  2713  2713 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-30 10:21:38.268  1036  1523 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-30 10:21:38.268  1036  1523 D WifiNative-wlan0: doBoolean: SET ps 1
08-30 10:21:38.268  1036  1523 D WifiNative-wlan0: SET ps 1: returned true
08-30 10:21:38.268   316   894 D CommandListener: Clearing all IP addresses on wlan0
,08-30 10:21:38.269  1036  1530 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-30 10:21:38.269  1036  1530 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-30 10:21:38.269  1036  1530 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-30 10:21:38.270  1036  1530 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-30 10:21:38.270  1036  2853 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-30 10:21:38.270  1036  2853 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-30 10:21:38.270  1036  2853 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-30 10:21:38.271  1586  1797 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-30 10:21:38.271  1955  1955 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-30 10:21:38.271  1955  1955 D WfdsService: WifiP2pState is changed : false
08-30 10:21:38.271  1955  2317 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-30 10:21:38.271  1955  2317 D WfdsService: Set the WFDS Monitor: false
08-30 10:21:38.271  1955  2317 D WfdsMonitor: WFDS Monitor is stopped
08-30 10:21:38.271  1955  2317 D WfdsService: STATE : WfdsDisabledState - enter
08-30 10:21:38.272  1955  2753 D CtrlSupplicant: Received on exit socket, terminate
08-30 10:21:38.272  1955  2753 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-30 10:21:38.272  1955  2753 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-30 10:21:38.272  1955  2753 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-30 10:21:38.272  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 10:21:38.272  1955  2319 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-30 10:21:38.272  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 10:21:38.272  1955  2317 W WfdsService: DefaultState - msg [9445378] is not handled
08-30 10:21:38.273  1036  1523 D WifiNative-p2p0: doBoolean: TERMINATE
08-30 10:21:38.273  1036  1523 D WifiNative-p2p0: TERMINATE: returned true
08-30 10:21:38.273  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 10:21:38.274  1036  1036 D WifiHS20: hidePasspointNotification off =false
08-30 10:21:38.274  1036  1523 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-30 10:21:38.274  1036  1523 E WifiStateMachine: useWiFiOffloading() : false
08-30 10:21:38.274  1036  1523 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-30 10:21:38.274  1036  1530 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-30 10:21:38.274  1036  1530 D ConnectivitySe,rvice: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-30 10:21:38.275   316  6910 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-30 10:21:38.275  1036  6903 D DSQN    : ThreadTCPConnectionCheck DNS fail internet is not possible
08-30 10:21:38.275  1036  1116 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-30 10:21:38.275  1036  6902 D DSQN    : ThreadInternetCheck internet check NOK 
08-30 10:21:38.275  1036  6902 D DSQN    : L3_DATA_SERVICE_QUALITY STATUS 0 DataEnabled: false
08-30 10:21:38.277  1036  1521 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-30 10:21:38.277  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 10:21:38.277  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 10:21:38.277  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-30 10:21:38.277  1036  1036 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-30 10:21:38.278  1036  6902 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 com.android.server.DataServiceQualityMonitor.sendDSqualityIntent:1103 com.android.server.DataServiceQualityMonitor.access$200:55 com.android.server.DataServiceQualityMonitor$ThreadInternetCheck.run:921 <bottom of call stack> 
08-30 10:21:38.279  1036  1530 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-30 10:21:38.279  1036  1530 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 10:21:38.279  1036  1530 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 10:21:38.280  1036  1530 D NetworkManagementService: Removing idletimer
08-30 10:21:38.280  1036  1530 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 10:21:38.282  1036  1521 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-30 10:21:38.283  1036  1036 D WifiDataContinuityService: L3_DATA_SERVICE_QUALITY_ACTION, resultStatus : 0
08-30 10:21:38.283  1864  1864 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 10:21:38.283  1864  1864 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-30 10:21:38.284  1036  1523 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 10:21:38.284  1036  1523 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 10:21:38.284  1036  1530 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-30 10:21:38.286  1955  1978 D WifiServiceExtension: isInternetCheckAvailable return false
08-30 10:21:38.286  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-30 10:21:38.287  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-30 10:21:38.287  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-30 10:21:38.288  1955  1955 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-30 10:21:38.289  1036  1036 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-30 10:21:38.292  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 10:21:38.292  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-30 10:21:38.292  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 10:21:38.292  6615  6615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 10:21:38.292  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 10:21:38.292  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 10:21:38.292  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 10:21:38.292  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 10:21:38.292  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 10:21:38.292  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 10:21:38.292  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 10:21:38.292  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 10:21:38.292  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-30 10:21:38.292  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-30 10:21:38.292  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-30 10:21:38.293  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 10:21:38.293  6615  6615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 10:21:38.293  6615  6615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 10:21:38.295  6615  6615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 10:21:38.295  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 10:21:38.295  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 10:21:38.295  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 10:21:38.295  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 10:21:38.295  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 10:21:38.295  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 10:21:38.295  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 10:21:38.295  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 10:21:38.295  6615  6615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 10:21:38.295  6615  6615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 10:21:38.297  6615  6615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 10:21:38.297  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 10:21:38.297  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 10:21:38.297  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 10:21:38.297  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 10:21:38.297  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 10:21:38.297  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 10:21:38.297  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 10:21:38.297  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 10:21:38.297  6615  6615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 10:21:38.297  6615  6615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 10:21:38.299  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 10:21:38.299  1036  1036 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-30 10:21:38.301  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-30 10:21:38.301  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 10:21:38.301  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 10:21:38.312  6890  6890 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 10:21:38.312  6890  6890 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
08-30 10:21:38.312  6890  6890 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-30 10:21:38.313  6890  6890 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
08-30 10:21:38.313  6890  6890 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-30 10:21:38.314  6890  6890 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-30 10:21:38.316  1586  1586 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-30 10:21:38.317  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 10:21:38.318  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 10:21:38.329  1586  1586 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-30 10:21:38.329  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 10:21:38.330  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 10:21:38.330  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 10:21:38.341  6868  6868 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-30 10:21:38.342  6868  6868 W LG Account v2.2: No ProfileInfo entries
08-30 10:21:38.342  6868  6868 I LG Account v2.2: isEnabled: false
08-30 10:21:38.342  6868  6868 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-30 10:21:38.342  6868  6868 I Feature : [Lifetracker]Country: EU
08-30 10:21:38.342  6868  6868 I Feature : [Lifetracker]Operator: OPEN
08-30 10:21:38.342  6868  6868 I Feature : [Lifetracker]Ranking support: false
08-30 10:21:38.342  6868  6868 I Feature : [Lifetracker]Comfort support: false
08-30 10:21:38.342  6868  6868 I Feature : [Lifetracker]Accessory: true
08-30 10:21:38.342  6868  6868 I Feature : [Lifetracker]Health device: true
08-30 10:21:38.342  6868  6868 I Feature : [Lifetracker]Extra Pedometer: false
08-30 10:21:38.342  6868  6868 I Feature : [Lifetracker]Blood glucose device: false
08-30 10:21:38.342  6868  6868 I Feature : [Lifetracker]Device Number: 3
08-30 10:21:38.348  6433  6433 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 10:21:38.352  2713  2713 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-30 10:21:38.352  2713  2713 I wpa_supplicant: monitor socket send errors count : 1
08-30 10:21:38.352  2713  2713 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1955-2\x00 that cannot receive messages
,08-30 10:21:38.353  1036  2751 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-30 10:21:38.353  1036  2751 D WifiMonitor: Dropping event because (p2p0) is stopped
08-30 10:21:38.379  1036  2022 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6915 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-30 10:21:38.380  1036  2022 I ActivityManager: Killing 6257:com.android.providers.calendar/u0a14 (adj 15): empty #17
08-30 10:21:38.391   348   348 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 211us total 10.637ms
,08-30 10:21:38.394  2713  2713 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-30 10:21:38.395  2713  2713 W wpa_supplicant: USIM:  scard_deinit function
08-30 10:21:38.396  1036  2751 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-30 10:21:38.396  1036  2751 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-30 10:21:38.396  1036  2751 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-30 10:21:38.396  1036  2751 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-30 10:21:38.396  1036  2751 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 10:21:38.396  1036  2751 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-30 10:21:38.398  1036  1523 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=156094
08-30 10:21:38.398  1036  1523 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=156094
08-30 10:21:38.400  1036  1523 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=156095  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-30 10:21:38.400  1036  1118 D Tethering: InitialState.processMessage what=4
08-30 10:21:38.400  1036  1523 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=156096  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-30 10:21:38.401   348   348 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 198us total 9.336ms
08-30 10:21:38.401  1036  2855 D DhcpStateMachine: StoppedState
08-30 10:21:38.401  1036  2855 D DhcpStateMachine: StoppedState{ when=-133ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-30 10:21:38.410   348   348 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 191us total 9.050ms
,08-30 10:21:38.427  1036  1729 W libprocessgroup: failed to open /acct/uid_10014/pid_6257/cgroup.procs: No such file or directory
,08-30 10:21:38.430  1036  1118 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-30 10:21:38.431  1036  1523 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-30 10:21:38.432  1036  1523 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-30 10:21:38.434  1036  1523 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-30 10:21:38.435  1036  1523 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
,08-30 10:21:38.467  6890  6890 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-30 10:21:38.475  3938  3938 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-30 10:21:38.475  3938  3938 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 10:21:38.475  3938  3938 V BluetoothPbapReceiver: ***********state = 13
08-30 10:21:38.476  3938  3938 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-30 10:21:38.477  3938  3938 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 10:21:38.477  3938  3938 V BluetoothPbapService: state: 13
08-30 10:21:38.477  3938  3938 V BluetoothPbapService: Pbap Service closeService in
08-30 10:21:38.478  3938  3938 V BluetoothPbapService: successfully stopped pbap service
08-30 10:21:38.478  3938  3938 V BluetoothPbapService: Pbap Service closeService out
,08-30 10:21:38.479  3938  3938 V BluetoothPbapService: Pbap Service onDestroy
08-30 10:21:38.479  3938  3938 V BluetoothPbapService: Pbap Service closeService in
08-30 10:21:38.479  3938  3938 V BluetoothPbapService: Pbap Service closeService out
08-30 10:21:38.479  3938  3938 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-30 10:21:38.479  1036  1118 D BluetoothManagerService: Message: 20
08-30 10:21:38.480  1036  1118 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@34e35fdc:true
08-30 10:21:38.480  2229  2229 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-30 10:21:38.482  2713  2713 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-30 10:21:38.483  1036  2751 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-30 10:21:38.483  1036  2751 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
08-30 10:21:38.483  1036  2751 D WifiMonitor: Disconnecting from the supplicant, no more events
08-30 10:21:38.484  1036  1523 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
08-30 10:21:38.490  6915  6915 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,08-30 10:21:38.497  6915  6915 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-30 10:21:38.498  6915  6915 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-30 10:21:38.499  1036  2305 I ActivityManager: Killing 6358:com.android.defcontainer/u0a4 (adj 15): empty #17
08-30 10:21:38.500  1036  1118 D BluetoothManagerService: Message: 30
08-30 10:21:38.524  1036  1561 W libprocessgroup: failed to open /acct/uid_10004/pid_6358/cgroup.procs: No such file or directory
,08-30 10:21:38.530  1036  1118 D BluetoothManagerService: Message: 30
08-30 10:21:38.535  6890  6890 D LocalBluetoothProfileManager: Adding local MAP profile
08-30 10:21:38.538  6890  6890 D BluetoothMap: Create BluetoothMap proxy object
,08-30 10:21:38.539  1036  1118 D BluetoothManagerService: Message: 30
08-30 10:21:38.546  1036  1118 D BluetoothManagerService: Message: 30
08-30 10:21:38.549  6890  6890 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-30 10:21:38.552  6890  6890 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
08-30 10:21:38.574  6890  6890 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
,08-30 10:21:38.579  6890  6890 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
08-30 10:21:38.586  1955  1955 D WfdsService: Supplicant Connection state is changed : false
08-30 10:21:38.586  1036  1523 D WifiOffDelayIfNotUsed: stopMonitoring
08-30 10:21:38.586  1036  1523 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-30 10:21:38.586  1036  1523 E WifiStateMachine: useWiFiOffloading() : false
08-30 10:21:38.586  1036  1523 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-30 10:21:38.587  1955  2317 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-30 10:21:38.587  1955  2317 D WfdsService: Set the WFDS Monitor: false
08-30 10:21:38.587  1955  2317 D WfdsMonitor: WFDS Monitor is stopped
,08-30 10:21:38.589  1955  1955 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
,08-30 10:21:38.592  2438  2438 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 10:21:38.593  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 10:21:38.593  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-30 10:21:38.594  1036  1528 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-30 10:21:38.594  1036  1528 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-30 10:21:38.595  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 10:21:38.597  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 10:21:38.600  6890  6890 D DockEventReceiver: finishStartingService: stopping service
08-30 10:21:38.600  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 10:21:38.627  6890  6890 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 10:21:38.663  6890  6890 D LgDataFeature: LgDataFeature() Constructor: none
08-30 10:21:38.664  6890  6890 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 10:21:38.677  6890  6890 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 10:21:38.678  6890  6890 D BluetoothInputDevice: Proxy object connected
08-30 10:21:38.680  6890  6890 D HidProfile: Bluetooth service connected
08-30 10:21:38.681  6890  6890 D BluetoothPan: BluetoothPAN Proxy object connected
08-30 10:21:38.682  6890  6890 D PanProfile: Bluetooth service connected
08-30 10:21:38.683  6890  6890 D BluetoothMap: Proxy object connected
08-30 10:21:38.683  6890  6890 D MapProfile: Bluetooth service connected
08-30 10:21:38.684  6890  6890 D BluetoothMap: getConnectedDevices()
08-30 10:21:38.684  6890  6890 D BluetoothMap: Bluetooth is Not enabled
08-30 10:21:38.684  6890  6890 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-30 10:21:38.686  6890  6890 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-30 10:21:38.691  6890  6890 D BluetoothPermissionRequest: onReceive
08-30 10:21:38.696  6890  6890 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-30 10:21:38.704  1036  1051 I ActivityManager: Killing 6484:com.google.android.partnersetup/u0a8 (adj 15): empty #17
,08-30 10:21:38.706  6890  6890 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-30 10:21:38.812  3938  3938 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
,08-30 10:21:38.813  3938  3938 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
,08-30 10:21:38.823  3938  3938 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-30 10:21:38.824  1036  1951 W libprocessgroup: failed to open /acct/uid_10008/pid_6484/cgroup.procs: No such file or directory
08-30 10:21:38.903  1036  2080 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6950 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,08-30 10:21:38.908  3938  3938 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-30 10:21:38.908  3938  3938 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-30 10:21:38.910  3938  3938 V BluetoothFtpService: Ftp Service onStartCommand
08-30 10:21:38.910  3938  3938 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 10:21:38.911  3938  3938 V BluetoothFtpService: Ftp Service closeService
08-30 10:21:38.911  3938  3938 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-30 10:21:38.912  3938  3938 V BluetoothFtpService: successfully stopped ftp service
08-30 10:21:38.912  3938  3938 V BluetoothFtpService: Ftp Service onDestroy
08-30 10:21:38.912  3938  3938 V BluetoothFtpService: Ftp Service closeService
08-30 10:21:38.916  3938  3938 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-30 10:21:38.916  3938  3938 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-30 10:21:38.916  3938  3938 V BluetoothSapReceiver: SapReceiver onReceive 
08-30 10:21:38.916  3938  3938 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 10:21:38.916  3938  3938 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-30 10:21:38.916  3938  3938 V BluetoothSapReceiver: Calling SAP service start service with action = null
,08-30 10:21:38.919  3938  3938 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 10:21:38.919  3938  3938 V BluetoothSapService: state: 13
08-30 10:21:38.919  3938  3938 V BluetoothSapService: Stopping SAP server process
08-30 10:21:38.921  3938  3938 V BluetoothSapService: Sap Service closeSapService in
08-30 10:21:38.921  3938  3938 V BluetoothSapService: Close listen Socket : 
08-30 10:21:38.921  3938  3938 V BluetoothSapService: Close rfcomm Socket : 
08-30 10:21:38.921  3938  3938 V BluetoothSapService: Close sapd  Socket : 
08-30 10:21:38.923  3938  3938 V BluetoothSapService: Sap Service closeSapService out
08-30 10:21:38.923  3938  3938 V BluetoothSapService: Sap Service onDestroy
08-30 10:21:38.923  3938  3938 V BluetoothSapService: Sap Service closeSapService in
08-30 10:21:38.923  3938  3938 V BluetoothSapService: Close listen Socket : 
08-30 10:21:38.923  3938  3938 V BluetoothSapService: Close rfcomm Socket : 
08-30 10:21:38.923  3938  3938 V BluetoothSapService: Close sapd  Socket : 
08-30 10:21:38.923  3938  3938 V BluetoothSapService: Sap Service closeSapService out
08-30 10:21:38.962  1036  2080 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6967 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-30 10:21:39.020  6950  6950 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-30 10:21:39.027  6967  6967 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-30 10:21:39.045  1036  1052 I ActivityManager: Killing 6057:com.lge.appbox.client/u0a11 (adj 15): empty #17
,08-30 10:21:39.088  3938  4124 W bt-btif : ag scb idx 1 not allocated
08-30 10:21:39.088  3938  4018 D bt_hci_bdroid: cleanup
08-30 10:21:39.088  3938  4124 E bt-btif : BTA AG is already disabled, ignoring ...
08-30 10:21:39.088  3938  4124 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 10:21:39.088  3938  4124 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 10:21:39.088  3938  4124 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-30 10:21:39.088  3938  4124 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 10:21:39.088  3938  4124 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 10:21:39.088  3938  4124 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 10:21:39.088  3938  4124 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 10:21:39.088  3938  4124 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 10:21:39.088  3938  4124 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-30 10:21:39.088  3938  4124 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 10:21:39.088  3938  4124 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 10:21:39.088  3938  4124 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 10:21:39.088  3938  4124 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 10:21:39.088  3938  4124 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 10:21:39.088  3938  4124 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-30 10:21:39.088  3938  4124 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 10:21:39.088  3938  4205 I bt_userial_mct: exiting userial_read_thread
08-30 10:21:39.088  3938  4124 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 10:21:39.088  3938  4205 D bt_userial_mct: Leaving userial_evt_read_thread()
08-30 10:21:39.088  3938  4124 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 10:21:39.089  3938  4124 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-30 10:21:39.089  3938  4126 I bt_lpm  : LPM is already off!!!
08-30 10:21:39.089  3938  4018 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-30 10:21:39.089  3938  4126 I bt_vendor: hw_epilog_process
08-30 10:21:39.089  3938  4018 D bt_hci_bdroid: cleanup Finalizing cleanup
08-30 10:21:39.089  3938  4018 D bt_userial_mct: userial_close
08-30 10:21:39.089  3938  4018 E bt_userial_mct: pthread_join() FAILED result:3
08-30 10:21:39.089  3938  4018 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,08-30 10:21:39.122  3938  4018 D bt_hci_bdroid: set_power 0
08-30 10:21:39.122  3938  4018 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-30 10:21:39.122  3938  4018 I bt_vendor: bluetooth satus is on
08-30 10:21:39.122  3938  4018 I bt_vendor: bt-vendor : resetting BT status
08-30 10:21:39.122  3938  4018 I bt_vendor: Starting hciattach daemon
08-30 10:21:39.122  3938  4018 I bt_vendor: try to set false
08-30 10:21:39.124  3938  4018 I bt_vendor: Starting hciattach daemon
08-30 10:21:39.124  3938  4018 I bt_vendor: try to set false
,08-30 10:21:39.127  3938  4018 I bt_vendor: cleanup
08-30 10:21:39.128  1036  2305 W libprocessgroup: failed to open /acct/uid_10011/pid_6057/cgroup.procs: No such file or directory
08-30 10:21:39.129  3938  4124 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-30 10:21:39.131  3938  4018 I GKI_LINUX: GKI_exit_task 0 done
08-30 10:21:39.131  3938  4018 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-30 10:21:39.135  3938  4012 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-30 10:21:39.138  6950  6950 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,08-30 10:21:39.144  3938  3938 D HeadsetService: Received stop request...Stopping profile...
08-30 10:21:39.146  3938  3938 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-30 10:21:39.146  3938  3938 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-30 10:21:39.146  3938  3938 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38f5aa1f
08-30 10:21:39.147  3938  4048 D HeadsetStateMachine: Exit Disconnected: -1
08-30 10:21:39.148  1036  1036 D BluetoothHeadset: Proxy object disconnected
08-30 10:21:39.148  1036  1036 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-30 10:21:39.149  1864  1864 D BluetoothHeadset: Proxy object disconnected
08-30 10:21:39.149  1864  1864 D BluetoothHeadset: Proxy object disconnected
08-30 10:21:39.149  1864  1864 D BluetoothHeadset: Proxy object disconnected
08-30 10:21:39.151  3938  3938 D A2dpService: Received stop request...Stopping profile...
08-30 10:21:39.153  3938  3938 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-30 10:21:39.153  3938  4083 D A2dpStateMachine: Exit Disconnected: -1
,08-30 10:21:39.163  3938  4012 D BluetoothAdapterState: Stopping profile services that were post enabled
08-30 10:21:39.163  3938  3938 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-30 10:21:39.163  3938  3938 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-30 10:21:39.163  3938  3938 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38f5aa1f
08-30 10:21:39.164  1036  1036 D BluetoothA2dp: Proxy object disconnected
08-30 10:21:39.164  1036  1036 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-30 10:21:39.165  3938  3938 D HidService: Received stop request...Stopping profile...
08-30 10:21:39.165  3938  3938 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38f5aa1f
08-30 10:21:39.167  6890  6890 D BluetoothInputDevice: Proxy object disconnected
08-30 10:21:39.167  6890  6890 D HidProfile: Bluetooth service disconnected
08-30 10:21:39.167  3938  3938 D HealthService: Received stop request...Stopping profile...
08-30 10:21:39.167  3938  3938 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38f5aa1f
,08-30 10:21:39.169  3938  3938 D HeadsetStateMachine: Unbinding service...
08-30 10:21:39.170  3938  3938 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-30 10:21:39.170  3938  3938 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-30 10:21:39.170  3938  3938 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-30 10:21:39.170  3938  3938 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-30 10:21:39.170  3938  3938 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-30 10:21:39.170  3938  3938 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-30 10:21:39.170  3938  3938 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-30 10:21:39.171  3938  3938 D PanService: Received stop request...Stopping profile...
08-30 10:21:39.171  3938  3938 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38f5aa1f
08-30 10:21:39.172  6890  6890 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-30 10:21:39.172  6890  6890 D PanProfile: Bluetooth service disconnected
08-30 10:21:39.173  3938  3938 D BtGatt.DebugUtils: handleDebugAction() action=null
08-30 10:21:39.174  3938  3938 D BtGatt.GattService: Received stop request...Stopping profile...
08-30 10:21:39.174  3938  3938 D BtGatt.GattService: stop()
08-30 10:21:39.174  3938  3938 D BtGatt.AdvertiseManager: advertise clients cleared
08-30 10:21:39.176  3938  3938 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38f5aa1f
08-30 10:21:39.177  3938  3938 D BluetoothMapService: Received stop request...Stopping profile...
08-30 10:21:39.177  3938  3938 D BluetoothMapService: stop()
,08-30 10:21:39.178  3938  3938 D BluetoothMapEmailAppObserver: deinitObservers()
08-30 10:21:39.178  3938  3938 D BluetoothMapEmailAppObserver: removeReceiver()
08-30 10:21:39.178  3938  3938 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38f5aa1f
08-30 10:21:39.179  6890  6890 D BluetoothMap: Proxy object disconnected
08-30 10:21:39.179  6890  6890 D MapProfile: Bluetooth service disconnected
08-30 10:21:39.182  3938  3938 I BluetoothA2dpServiceJni: cleanupNative
,08-30 10:21:39.182  3938  4085 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-30 10:21:39.183  3938  3938 I GKI_LINUX: GKI_exit_task 2 done
08-30 10:21:39.183  3938  3938 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-30 10:21:39.183  3938  3938 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-30 10:21:39.183  3938  3938 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-30 10:21:39.183  3938  3938 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-30 10:21:39.183  3938  3938 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-30 10:21:39.183  3938  3938 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-30 10:21:39.184  3938  3938 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-30 10:21:39.184  3938  3938 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-30 10:21:39.185  3938  3938 V BluetoothMapService: Handler(): got msg=4
08-30 10:21:39.185  3938  3938 D BluetoothMapService: MAP Service closeService in
08-30 10:21:39.185  3938  3938 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-30 10:21:39.185  3938  3938 V BluetoothMapService: MAP Service closeService out
08-30 10:21:39.185  3938  4012 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-30 10:21:39.185  3938  4012 D BluetoothAdapterProperties: Setting state to 10
08-30 10:21:39.185  3938  4012 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-30 10:21:39.186  3938  3938 D BluetoothMapService: cleanup()
08-30 10:21:39.186  3938  3938 D BluetoothMapService: MAP Service closeService in
08-30 10:21:39.186  3938  3938 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-30 10:21:39.186  3938  3938 V BluetoothMapService: MAP Service closeService out
08-30 10:21:39.186  1036  1118 D BluetoothManagerService: Message: 60
08-30 10:21:39.186  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-30 10:21:39.186  1036  1118 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
08-30 10:21:39.186  1036  1118 D BluetoothA2dp: onBluetoothStateChange: up=false
08-30 10:21:39.186  3938  4012 I BluetoothAdapterState: Entering OffState
08-30 10:21:39.187  1864  1880 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 10:21:39.188  6890  6909 D BluetoothPan: onBluetoothStateChange on: false
08-30 10:21:39.189  1864  1879 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 10:21:39.189  6890  6911 D BluetoothPbap: onBluetoothStateChange: up=false
08-30 10:21:39.190  1864  2551 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 10:21:39.191  6890  6909 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-30 10:21:39.191  1036  1118 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 10:21:39.192  6890  6911 D BluetoothMap: onBluetoothStateChange: up=false
08-30 10:21:39.193  1036  1118 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-30 10:21:39.193  1036  1118 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-30 10:21:39.195  1036  1118 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-30 10:21:39.195  1036  1118 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-30 10:21:39.195  1036  1118 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@1493e12d mBinding = false
08-30 10:21:39.196  1036  1118 D BluetoothManagerService: Sending unbind request.
,08-30 10:21:39.201  1036  1118 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-30 10:21:39.203  1955  1955 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-30 10:21:39.203  1955  2155 D LGBluetoothAPIService: Message: 2
08-30 10:21:39.203  1955  2155 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@5f6068e mBinding = false
08-30 10:21:39.203  1955  2155 D LGBluetoothAPIService: Sending unbind request.
08-30 10:21:39.205  3938  4018 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-30 10:21:39.206  3938  3938 I GKI_LINUX: GKI_exit_task 1 done
08-30 10:21:39.206  3938  3938 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-30 10:21:39.206  3938  3938 I BluetoothServiceJni: cleanupNative: return from cleanup
08-30 10:21:39.207  3938  3938 I art     : --- WEIRD: removing null entry 246
08-30 10:21:39.207  3938  3938 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
08-30 10:21:39.207  3938  3938 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
,08-30 10:21:39.208  1586  1586 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-30 10:21:39.211  3938  3938 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-30 10:21:39.212  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 10:21:39.213  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 10:21:39.213  1586  1586 D BluetoothAdapter: 855244849: getState() :  mService = null. Returning STATE_OFF
08-30 10:21:39.213  1586  1586 D BluetoothAdapter: 855244849: getState() :  mService = null. Returning STATE_OFF
08-30 10:21:39.214  3938  3938 I art     : System.exit called, status: 0
08-30 10:21:39.214  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 10:21:39.214  3938  3938 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-30 10:21:39.216  6890  6890 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-30 10:21:39.217  6890  6890 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-30 10:21:39.217  6890  6890 D LGBluetoothEventManager: [BTUI] clear device connection state
08-30 10:21:39.219  6890  6890 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-30 10:21:39.225  6890  6890 D DockEventReceiver: finishStartingService: stopping service
08-30 10:21:39.234  6950  6950 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,08-30 10:21:39.234  6950  6950 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-30 10:21:39.235  6950  6950 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-30 10:21:39.235  6950  6950 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-30 10:21:39.236  6950  6950 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-30 10:21:39.238  6950  6950 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-30 10:21:39.241   321  4054 V AudioFlinger: 3938 died, releasing its sessions
08-30 10:21:39.241  6890  6890 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-30 10:21:39.241   321  4054 V AudioFlinger:  pid 1864 @ 0
08-30 10:21:39.241   321  4054 V AudioFlinger:  pid 3444 @ 1
08-30 10:21:39.241   321  4054 V AudioFlinger:  pid 3444 @ 2
08-30 10:21:39.244  6950  6950 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-30 10:21:39.261  1036  1561 I ActivityManager: Process com.android.bluetooth (pid 3938) has died
08-30 10:21:39.262  1036  1561 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
,08-30 10:21:39.266  2229  2229 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-30 10:21:39.274  6950  6950 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 10:21:39.277  6950  6950 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 10:21:39.278  1036  1036 D DSQN    : EVENT_INTERNET_CHECK_ENABLE received
,08-30 10:21:39.286  6890  6890 D BluetoothPermissionRequest: onReceive
,08-30 10:21:39.290  6890  6890 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
,08-30 10:21:39.292  6890  6890 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
,08-30 10:21:39.293  6950  6950 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-30 10:21:39.296  6950  6950 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-30 10:21:39.297  6890  6890 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-30 10:21:39.299  6433  6433 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 10:21:39.300  6950  6950 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-30 10:21:39.369  1036  2080 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7002 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-30 10:21:39.379  6915  6915 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-30 10:21:39.379  6915  6915 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-30 10:21:39.379  6915  6915 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-30 10:21:39.385  6890  6890 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 10:21:39.401  6890  6890 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 10:21:39.413  6950  6950 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 10:21:39.413  6950  6950 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-30 10:21:39.420  6950  6950 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-30 10:21:39.426  6433  6433 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 10:21:39.433  6915  6915 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-30 10:21:39.433  6915  6915 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-30 10:21:39.433  6915  6915 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-30 10:21:39.441  6890  6890 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 10:21:39.456  6890  6890 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 10:21:39.469  6950  6950 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-30 10:21:39.470  6950  6950 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 10:21:39.472  6950  6950 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-30 10:21:39.477  7002  7002 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-30 10:21:39.478  7002  7002 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-30 10:21:39.478  7002  7002 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-30 10:21:39.479  7002  7002 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-30 10:21:39.507  7002  7002 D BluetoothAdapterApp: Loading JNI Library
,08-30 10:21:39.524  1036  1764 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7019 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
08-30 10:21:39.544  7002  7002 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@13461bd4 Instance Count = 1
,08-30 10:21:39.548  7002  7002 D BluetoothAdapterApp: onCreate
08-30 10:21:39.569  7002  7002 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-30 10:21:39.570  7002  7002 D ProfileConfigQcom: Adding HeadsetService
08-30 10:21:39.570  7002  7002 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-30 10:21:39.570  7002  7002 D ProfileConfigQcom: Adding A2dpService
08-30 10:21:39.570  7002  7002 D ProfileConfigQcom: [BTUI] HidService is supported
08-30 10:21:39.570  7002  7002 D ProfileConfigQcom: Adding HidService
08-30 10:21:39.571  7002  7002 D ProfileConfigQcom: [BTUI] HealthService is supported
08-30 10:21:39.571  7002  7002 D ProfileConfigQcom: Adding HealthService
08-30 10:21:39.571  7002  7002 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
,08-30 10:21:39.572  7002  7002 D ProfileConfigQcom: [BTUI] PanService is supported
08-30 10:21:39.572  7002  7002 D ProfileConfigQcom: Adding PanService
08-30 10:21:39.573  7002  7002 D ProfileConfigQcom: [BTUI] GattService is supported
08-30 10:21:39.573  7002  7002 D ProfileConfigQcom: Adding GattService
08-30 10:21:39.573  7002  7002 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-30 10:21:39.573  7002  7002 D ProfileConfigQcom: Adding BluetoothMapService
08-30 10:21:39.574  7002  7002 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-30 10:21:39.575  7002  7002 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-30 10:21:39.582  6890  6890 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
,08-30 10:21:39.584  7002  7002 V LGMDMManagerInternal: Create singleton instance
08-30 10:21:39.635  6915  6915 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-30 10:21:39.645  6890  6890 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-30 10:21:39.653  6890  6890 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 10:21:39.656  7019  7039 W FormManager: Network not available. Please check & try again.
08-30 10:21:39.668  6890  6890 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
,08-30 10:21:39.668  6890  6890 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-30 10:21:39.668  6890  6890 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-30 10:21:39.669  6890  6890 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-30 10:21:39.671  7019  7040 V FormManager: Network unavailable.
,08-30 10:21:39.672  6890  6890 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,08-30 10:21:39.673  7019  7040 V FormManager: Network unavailable.
08-30 10:21:39.675  7002  7002 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-30 10:21:39.678  7002  7002 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-30 10:21:39.678  7002  7002 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-30 10:21:39.678  7002  7002 V BluetoothSapReceiver: SapReceiver onReceive 
08-30 10:21:39.679  7002  7002 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 10:21:39.679  7002  7002 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-30 10:21:39.686  6967  6967 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
08-30 10:21:39.687  6890  6890 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-30 10:21:39.687  6890  6890 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-30 10:21:39.687  6890  6890 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-30 10:21:39.687  6890  6890 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-30 10:21:39.687  6890  6890 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-30 10:21:39.688  6890  6890 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,08-30 10:21:39.690  1036  2022 I ActivityManager: Killing 6532:com.lge.email/u0a23 (adj 15): empty #17
08-30 10:21:39.712  1036  2022 I ActivityManager: Killing 6079:com.android.contacts/u0a19 (adj 15): empty #18
,08-30 10:21:39.744  4383  4383 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
,08-30 10:21:39.744  4383  4383 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-30 10:21:39.744  1036  1052 W libprocessgroup: failed to open /acct/uid_10023/pid_6532/cgroup.procs: No such file or directory
08-30 10:21:39.746  4383  4383 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 10:21:39.748  1036  2307 W libprocessgroup: failed to open /acct/uid_10019/pid_6079/cgroup.procs: No such file or directory
08-30 10:21:39.757  4383  4383 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-30 10:21:39.769  4383  7044 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-30 10:21:39.774  6915  6915 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-30 10:21:39.775  6915  6915 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
,08-30 10:21:39.775  6915  6915 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-30 10:21:39.779  4383  7045 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-30 10:21:39.780  4383  7045 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-30 10:21:39.781  6890  6890 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-30 10:21:39.794  7019  7047 W FormManager: Network not available. Please check & try again.
,08-30 10:21:39.795  6890  6890 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 10:21:39.803  7019  7048 V FormManager: Network unavailable.
,08-30 10:21:39.807  7019  7048 V FormManager: Network unavailable.
,08-30 10:21:39.821  6950  6950 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-30 10:21:39.823  6950  6950 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
,08-30 10:21:39.824  6950  6950 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
08-30 10:21:39.864  6950  6950 D LgDataFeature: LgDataFeature() Constructor: none
,08-30 10:21:39.865  6950  6950 D LgDataFeature: LgDataFeature() Constructor Done, null
08-30 10:21:39.875  6950  6950 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
08-30 10:21:39.878  6950  6950 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-30 10:21:39.878  6950  6950 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-30 10:21:39.878  6950  6950 V SoundPool: doLoad: loading sample sampleID=1
08-30 10:21:39.879  6950  6950 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-30 10:21:39.881  6950  7051 V SoundPool: Start decode
,08-30 10:21:39.882  6950  7051 V MediaPlayer[Native]: decode(31, 10857164, 17813)
08-30 10:21:39.886   321   321 V MediaPlayerService: decode(23, 10857164, 17813)
08-30 10:21:39.886   321   321 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-30 10:21:39.886   321   321 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-30 10:21:39.886   321   321 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-30 10:21:39.886   321   321 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-30 10:21:39.886   321   321 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-30 10:21:39.886   321   321 V MediaPlayerService: player type = 3
,08-30 10:21:39.886   321   321 V AwesomePlayer: AwesomePlayer create()
08-30 10:21:39.887   321   321 V AwesomePlayer: reset_l() 
08-30 10:21:39.887   321   321 V AwesomePlayer: cancelPlayerEvents
08-30 10:21:39.887   321   321 V AwesomePlayer: setAudioSink() 
08-30 10:21:39.887   321   321 V AwesomePlayer: reset_l() 
08-30 10:21:39.887   321   321 V AudioCache: notify(0xb5474740, 8, 0, 0)
08-30 10:21:39.887   321   321 V AudioCache: ignored
08-30 10:21:39.887   321   321 V AwesomePlayer: cancelPlayerEvents
08-30 10:21:39.887   321   321 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
08-30 10:21:39.887   321   321 V AwesomePlayer: setDataSource_l dataSource
08-30 10:21:39.887   321   321 V LGParserOSAL: SniffLGParser start
08-30 10:21:39.887   321   321 V LGParserOSAL: MainType:5, SubType=0
08-30 10:21:39.887   321   321 V LGParserOSAL: #### check Mime : application/ogg
08-30 10:21:39.887   321   321 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-30 10:21:39.887   321   321 E MediaExtractor: Use LGExtractor :application/ogg 
08-30 10:21:39.888  6950  6950 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-30 10:21:39.890  6735  6735 D UEI.SmartControl: QS Service created
08-30 10:21:39.893  6950  6950 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
,08-30 10:21:39.894  6950  6950 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-30 10:21:39.920  6950  6950 V LGMDMManager: Create singleton instance
08-30 10:21:39.923  6735  6735 I UEI.SmartControl: Service initServices...
,08-30 10:21:39.923  6735  6735 D UEI.SmartControl: QS start get config
08-30 10:21:39.926   321   321 V LGParserOSAL: supported mime: application/ogg
08-30 10:21:39.926   321   321 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-30 10:21:39.926   321   321 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-30 10:21:39.926   321   321 V AwesomePlayer: mBitrate = -1 bits/sec
08-30 10:21:39.926   321   321 V AwesomePlayer: AudioTrack Setting
08-30 10:21:39.927   321   321 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-30 10:21:39.927   321   321 V AwesomePlayer: setAudioSource() 
08-30 10:21:39.927   321   321 V MediaPlayerService: prepare
08-30 10:21:39.927   321   321 V AwesomePlayer: prepareAsync_l() 
08-30 10:21:39.927   321   321 V MediaPlayerService: wait for prepare
08-30 10:21:39.927   321  7052 V AwesomePlayer: onPrepareAsyncEvent() 
08-30 10:21:39.927   321  7052 V AwesomePlayer: initAudioDecoder() 
08-30 10:21:39.927   321  7052 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-30 10:21:39.927   321  7052 V AudioSystem: isOffloadSupported()
08-30 10:21:39.927   321  7052 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-30 10:21:39.927   321  7052 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-30 10:21:39.927   321  7052 I AudioFlinger: isAudioPlaybackHookOn() false
08-30 10:21:39.927   321  7052 V AwesomePlayer: getUseOffload() = 0 
08-30 10:21:39.927   321  7052 V OMXCodec: OMXCodec::Create
08-30 10:21:39.927   321  7052 V OMXCodec: findMatchingCodecs()
08-30 10:21:39.928   321  7052 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-30 10:21:39.928   321  7052 V OMXCodec: matchingCodecs.size()=1
08-30 10:21:39.928   321  7052 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
08-30 10:21:39.929   321  7052 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-30 10:21:39.929   321  7052 V LGCodecAdapter: LG Codec Adapter start
08-30 10:21:39.929   321  7052 V OMXCodec: OMXCodec Createtor
08-30 10:21:39.929   321  7052 V OMXCodec: setComponentRole
08-30 10:21:39.929   321  7052 V OMXCodec: configureCodec protected=0
08-30 10:21:39.929   321  7052 V LGCodecAdapter: called getLGCodecSpecificData
08-30 10:21:39.929   321  7052 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-30 10:21:39.930   321  7052 V LGCodecOSAL: Called LGconfigureCodecMETA
08-30 10:21:39.930   321  7052 V LGCodecOSAL: Called LGconfigureCodecMSG
08-30 10:21:39.930   321  7052 V LGCodecOSAL: Not support LGCodec
08-30 10:21:39.930   321  7052 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-30 10:21:39.930   321  7052 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-30 10:21:39.930   321  7052 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-30 10:21:39.930   321  7052 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-30 10:21:39.930   321  7052 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-30 10:21:39.930   321  7052 V AudioSystem: isOffloadSupported()
08-30 10:21:39.930   321  7052 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-30 10:21:39.930   321  7052 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-30 10:21:39.930   321  7052 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-30 10:21:39.930   321  7052 V OMXCodec: init()
08,-30 10:21:39.930   321  7052 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-30 10:21:39.930   321  7052 V OMXCodec: allocateBuffers
08-30 10:21:39.930   321  7052 V OMXCodec: allocateBuffersOnPort portIndex=0
08-30 10:21:39.930   321  7052 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-30 10:21:39.930   321  7052 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a60 on input port
08-30 10:21:39.930   321  7052 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on input port
08-30 10:21:39.930   321  7052 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ba0 on input port
08-30 10:21:39.930   321  7052 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ce0 on input port
08-30 10:21:39.930   321  7052 V OMXCodec: allocateBuffersOnPort portIndex=1
08-30 10:21:39.930   321  7052 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-30 10:21:39.931   321  7052 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7dd0 on output port
08-30 10:21:39.931   321  7052 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7f10 on output port
08-30 10:21:39.931   321  7052 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7f60 on output port
08-30 10:21:39.931   321  7052 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57c8060 on output port
08-30 10:21:39.931   321  7052 V OMXCodec: init() mAsyncCompletion wait!!! 
08-30 10:21:39.931   321  7054 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
,08-30 10:21:39.931   321  7054 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-30 10:21:39.931   321  7054 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
,08-30 10:21:39.931   321  7052 V OMXCodec: init() mAsyncCompletion wait!!! 
,08-30 10:21:39.931   321  7054 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-30 10:21:39.931   321  7054 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-30 10:21:39.931   321  7054 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-30 10:21:39.931   321  7052 V OMXCodec: init() mAsyncCompletion wait free! 
08-30 10:21:39.931   321  7052 V AwesomePlayer: finishAsyncPrepare_l() 
08-30 10:21:39.931   321  7052 V AudioCache: notify(0xb5474740, 5, 0, 0)
08-30 10:21:39.931   321  7052 V AudioCache: ignored
,08-30 10:21:39.931   321  7052 V AudioCache: notify(0xb5474740, 1, 0, 0)
08-30 10:21:39.931   321  7052 V AudioCache: prepared
08-30 10:21:39.932   321   321 V AudioCache: wait - success
08-30 10:21:39.932   321   321 V MediaPlayerService: start
08-30 10:21:39.932   321   321 V AwesomePlayer: play_l() 
08-30 10:21:39.932   321   321 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-30 10:21:39.932   321   321 V AwesomePlayer: createAudioPlayer_l
08-30 10:21:39.932   321   321 V AwesomePlayer: seekAudioIfNecessary_l() 
,08-30 10:21:39.932   321   321 V AwesomePlayer: startAudioPlayer_l() 
08-30 10:21:39.932   321   321 D AudioPlayer: start of Playback, useOffload 0
08-30 10:21:39.932   321   321 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-30 10:21:39.932   321   321 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-30 10:21:39.935   321  7054 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-30 10:21:39.935   321  7054 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-30 10:21:39.935   321  7054 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-30 10:21:39.935   321  7054 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
,08-30 10:21:39.935   321  7054 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-30 10:21:39.935   321  7054 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-30 10:21:39.935   321  7054 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885648
08-30 10:21:39.935   321  7054 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-30 10:21:39.935   321  7054 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885968
08-30 10:21:39.935   321  7054 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-30 10:21:39.935   321  7054 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041886048
,08-30 10:21:39.935   321  7054 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-30 10:21:39.935   321  7054 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044835424
08-30 10:21:39.935   321  7054 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-30 10:21:39.935   321  7054 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-30 10:21:39.935   321  7054 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-30 10:21:39.935   321  7054 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-30 10:21:39.935   321  7054 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
,08-30 10:21:39.935   321  7054 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-30 10:21:39.935   321  7054 V OMXCodec: allocateBuffersOnPort portIndex=1
08-30 10:21:39.935   321  7054 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-30 10:21:39.936   321  7054 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7f60 on output port
08-30 10:21:39.936   321  7054 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7f10 on output port
08-30 10:21:39.936   321  7054 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7dd0 on output port
08-30 10:21:39.936   321  7054 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f240 on output port
,08-30 10:21:39.936   321  7054 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1),
08-30 10:21:39.936   321  7054 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-30 10:21:39.937   321   321 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-30 10:21:39.937   321   321 V AudioCache: notify(0xb5474740, 6, 0, 0)
,08-30 10:21:39.937   321   321 V AudioCache: ignored
08-30 10:21:39.938   321  7055 V AudioCache: write(0xb1507000, 4096)
08-30 10:21:39.938   321  7055 V AudioCache: memcpy(0xac300000, 0xb1507000, 4096)
08-30 10:21:39.939   321   321 V MediaPlayerService: wait for playback complete
08-30 10:21:39.942   321  7055 V AudioCache: write(0xb1507000, 4096)
08-30 10:21:39.942   321  7055 V AudioCache: memcpy(0xac301000, 0xb1507000, 4096)
08-30 10:21:39.943   321  7055 V AudioCache: write(0xb1507000, 4096)
,08-30 10:21:39.943   321  7055 V AudioCache: memcpy(0xac302000, 0xb1507000, 4096)
08-30 10:21:39.944   321  7055 V AudioCache: write(0xb1507000, 4096)
08-30 10:21:39.944   321  7055 V AudioCache: memcpy(0xac303000, 0xb1507000, 4096)
08-30 10:21:39.945   321  7055 V AudioCache: write(0xb1507000, 4096)
08-30 10:21:39.945   321  7055 V AudioCache: memcpy(0xac304000, 0xb1507000, 4096)
08-30 10:21:39.946   321  7055 V AudioCache: write(0xb1507000, 4096)
,08-30 10:21:39.946   321  7055 V AudioCache: memcpy(0xac305000, 0xb1507000, 4096)
08-30 10:21:39.946   321  7055 V AudioCache: write(0xb1507000, 4096)
08-30 10:21:39.947   321  7055 V AudioCache: memcpy(0xac306000, 0xb1507000, 4096)
08-30 10:21:39.947   321  7055 V AudioCache: write(0xb1507000, 4096)
08-30 10:21:39.947   321  7055 V AudioCache: memcpy(0xac307000, 0xb1507000, 4096)
08-30 10:21:39.948   321  7055 V AudioCache: write(0xb1507000, 4096)
08-30 10:21:39.948   321  7055 V AudioCache: memcpy(0xac308000, 0xb1507000, 4096)
,08-30 10:21:39.949   321  7055 V AudioCache: write(0xb1507000, 4096)
08-30 10:21:39.949   321  7055 V AudioCache: memcpy(0xac309000, 0xb1507000, 4096)
08-30 10:21:39.950   321  7055 V AudioCache: write(0xb1507000, 4096)
08-30 10:21:39.950   321  7055 V AudioCache: memcpy(0xac30a000, 0xb1507000, 4096)
,08-30 10:21:39.950   321  7055 V AudioCache: write(0xb1507000, 4096)
08-30 10:21:39.951   321  7055 V AudioCache: memcpy(0xac30b000, 0xb1507000, 4096)
08-30 10:21:39.951   321  7055 V AudioCache: write(0xb1507000, 4096)
08-30 10:21:39.951   321  7055 V AudioCache: memcpy(0xac30c000, 0xb1507000, 4096)
08-30 10:21:39.952   321  7055 V AudioCache: write(0xb1507000, 4096)
08-30 10:21:39.952   321  7055 V AudioCache: memcpy(0xac30d000, 0xb1507000, 4096)
08-30 10:21:39.953   321  7055 V AudioCache: write(0xb1507000, 4096)
08-30 10:21:39.953   321  7055 V AudioCache: memcpy(0xac30e000, 0xb1507000, 4096)
08-30 10:21:39.953   321  7055 V AudioCache: write(0xb1507000, 4096)
08-30 10:21:39.954   321  7055 V AudioCache: memcpy(0xac30f000, 0xb1507000, 4096)
08-30 10:21:39.954   321  7055 V AudioCache: write(0xb1507000, 4096)
08-30 10:21:39.954   321  7055 V AudioCache: memcpy(0xac310000, 0xb1507000, 4096)
08-30 10:21:39.955   321  7055 V AudioCache: write(0xb1507000, 4096)
08-30 10:21:39.955   321  7055 V AudioCache: memcpy(0xac311000, 0xb1507000, 4096)
08-30 10:21:39.956   321  7055 V AudioCache: write(0xb1507000, 4096)
08-30 10:21:39.956   321  7055 V AudioCache: memcpy(0xac312000, 0xb1507000, 4096)
08-30 10:21:39.957   321  7055 V AudioCache: write(0xb1507000, 4096)
08-30 10:21:39.957   321  7055 V AudioCache: memcpy(0xac313000, 0xb1507000, 4096)
08-30 10:21:39.957   321  7055 V AudioCache: write(0xb1507000, 4096)
08-30 10:21:39.957   321  7055 V AudioCache: memcpy(0xac314000, 0xb1507000, 4096)
08-30 10:21:39.958   321  7055 V AudioCache: write(0xb1507000, 4096)
08-30 10:21:39.958   321  7055 V AudioCache: memcpy(0xac315000, 0xb1507000, 4096)
08-30 10:21:39.959   321  7055 V AudioCache: write(0xb1507000, 4096)
08-30 10:21:39.959   321  7055 V AudioCache: memcpy(0xac316000, 0xb1507000, 4096)
08-30 10:21:39.959   321  7055 V AudioCache: write(0xb1507000, 4096)
08-30 10:21:39.959   321  7055 V AudioCache: memcpy(0xac317000, 0xb1507000, 4096)
08-30 10:21:39.959   321  7055 V AudioCache: write(0xb1507000, 4096)
08-30 10:21:39.959   321  7055 V AudioCache: memcpy(0xac318000, 0xb1507000, 4096)
08-30 10:21:39.959   321  7055 V AudioCache: write(0xb1507000, 4096)
08-30 10:21:39.959   321  7055 V AudioCache: memcpy(0xac319000, 0xb1507000, 4096)
08-30 10:21:39.961   321  7055 V AudioCache: write(0xb1507000, 4096)
08-30 10:21:39.961   321  7055 V AudioCache: memcpy(0xac31a000, 0xb1507000, 4096)
08-30 10:21:39.961   321  7055 V AudioCache: write(0xb1507000, 4096)
08-30 10:21:39.961   321  7055 V AudioCache: memcpy(0xac31b000, 0xb1507000, 4096)
,08-30 10:21:39.962   321  7055 V AudioCache: write(0xb1507000, 4096)
08-30 10:21:39.962   321  7055 V AudioCache: memcpy(0xac31c000, 0xb1507000, 4096)
08-30 10:21:39.962   321  7055 V AudioCache: write(0xb1507000, 4096)
08-30 10:21:39.962   321  7055 V AudioCache: memcpy(0xac31d000, 0xb1507000, 4096)
08-30 10:21:39.963   321  7055 V AudioCache: write(0xb1507000, 4096)
08-30 10:21:39.963   321  7055 V AudioCache: memcpy(0xac31e000, 0xb1507000, 4096)
08-30 10:21:39.963   321  7055 V AudioCache: write(0xb1507000, 4096)
08-30 10:21:39.963   321  7055 V AudioCache: memcpy(0xac31f000, 0xb1507000, 4096)
08-30 10:21:39.964   321  7055 V AudioCache: write(0xb1507000, 4096)
08-30 10:21:39.964   321  7055 V AudioCache: memcpy(0xac320000, 0xb1507000, 4096)
08-30 10:21:39.964   321  7055 V AudioCache: write(0xb1507000, 4096)
08-30 10:21:39.964   321  7055 V AudioCache: memcpy(0xac321000, 0xb1507000, 4096)
08-30 10:21:39.965   321  7055 V AudioCache: write(0xb1507000, 4096)
08-30 10:21:39.965   321  7055 V AudioCache: memcpy(0xac322000, 0xb1507000, 4096)
08-30 10:21:39.966   321  7055 V AudioCache: write(0xb1507000, 4096)
08-30 10:21:39.966   321  7055 V AudioCache: memcpy(0xac323000, 0xb1507000, 4096)
08-30 10:21:39.966   321  7055 V AudioCache: write(0xb1507000, 4096)
08-30 10:21:39.966   321  7055 V AudioCache: memcpy(0xac324000, 0xb1507000, 4096)
08-30 10:21:39.967   321  7055 V AudioCache: write(0xb1507000, 4096)
08-30 10:21:39.967   321  7055 V AudioCache: memcpy(0xac325000, 0xb1507000, 4096)
08-30 10:21:39.967   321  7055 V AudioCache: write(0xb1507000, 4096)
08-30 10:21:39.967   321  7055 V AudioCache: memcpy(0xac326000, 0xb1507000, 4096)
08-30 10:21:39.968   321  7055 V AudioCache: write(0xb1507000, 4096)
08-30 10:21:39.968   321  7055 V AudioCache: memcpy(0xac327000, 0xb1507000, 4096)
08-30 10:21:39.969   321  7055 V AudioCache: write(0xb1507000, 4096)
08-30 10:21:39.969   321  7055 V AudioCache: memcpy(0xac328000, 0xb1507000, 4096)
08-30 10:21:39.969   321  7055 V AudioCache: write(0xb1507000, 4096)
08-30 10:21:39.969   321  7055 V AudioCache: memcpy(0xac329000, 0xb1507000, 4096)
08-30 10:21:39.970   321  7055 V AudioCache: write(0xb1507000, 4096)
08-30 10:21:39.970   321  7055 V AudioCache: memcpy(0xac32a000, 0xb1507000, 4096)
08-30 10:21:39.971   321  7055 V AudioCache: write(0xb1507000, 4096)
08-30 10:21:39.971   321  7055 V AudioCache: memcpy(0xac32b000, 0xb1507000, 4096)
08-30 10:21:39.971   321  7055 V AudioCache: write(0xb1507000, 4096)
08-30 10:21:39.971   321  7055 V AudioCache: memcpy(0xac32c000, 0xb1507000, 4096)
08-30 10:21:39.972   321  7055 V AudioCache: write(0xb1507000, 4096)
08-30 10:21:39.972   321  7055 V AudioCache: memcpy(0xac32d000, 0xb1507000, 4096)
08-30 10:21:39.972   321  7055 V AudioCache: write(0xb1507000, 4096)
08-30 10:21:39.973   321  7055 V AudioCache: memcpy(0xac32e000, 0xb1507000, 4096)
08-30 10:21:39.973   321  7055 V AudioCache: write(0xb1507000, 4096)
08-30 10:21:39.973   321  7055 V AudioCache: memcpy(0xac32f000, 0xb1507000, 4096)
,08-30 10:21:39.974   321  7055 V AudioCache: write(0xb1507000, 4096)
08-30 10:21:39.974   321  7055 V AudioCache: memcpy(0xac330000, 0xb1507000, 4096)
08-30 10:21:39.974   321  7055 V AudioCache: write(0xb1507000, 4096)
08-30 10:21:39.974   321  7055 V AudioCache: memcpy(0xac331000, 0xb1507000, 4096)
08-30 10:21:39.974   321  7054 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-30 10:21:39.974   321  7055 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-30 10:21:39.974   321  7055 V AwesomePlayer: postAudioEOS() 
08-30 10:21:39.974   321  7055 V AudioCache: write(0xb1507000, 280)
08-30 10:21:39.974   321  7055 V AudioCache: memcpy(0xac332000, 0xb1507000, 280)
08-30 10:21:39.976   321  7052 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-30 10:21:39.976   321  7052 V AwesomePlayer: onStreamDone
08-30 10:21:39.976   321  7052 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-30 10:21:39.976   321  7052 V AudioCache: notify(0xb5474740, 2, 0, 0)
08-30 10:21:39.976   321  7052 V AudioCache: playback complete
08-30 10:21:39.976   321  7052 V AwesomePlayer: pause_l() 
08-30 10:21:39.976   321  7052 V AudioCache: notify(0xb5474740, 7, 0, 0)
08-30 10:21:39.976   321  7052 V AudioCache: ignored
08-30 10:21:39.976   321  7052 V AwesomePlayer: cancelPlayerEvents
08-30 10:21:39.976   321   321 V AudioCache: wait - success
08-30 10:21:39.976   321   321 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-30 10:21:39.976   321  7052 D AudioPlayer: Pause Playback at 1068125
08-30 10:21:39.977   321   321 V AwesomePlayer: reset_l() 
08-30 10:21:39.977   321   321 V AudioCache: notify(0xb5474740, 8, 0, 0)
08-30 10:21:39.977   321   321 V AudioCache: ignored
08-30 10:21:39.977   321   321 V AwesomePlayer: cancelPlayerEvents
08-30 10:21:39.977   321   321 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-30 10:21:39.977   321   321 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-30 10:21:39.977   321   321 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-30 10:21:39.977   321   321 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-30 10:21:39.977   321   321 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-30 10:21:39.977   321  7054 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-30 10:21:39.977   321  7054 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-30 10:21:39.977   321  7054 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-30 10:21:39.977   321  7054 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ce0 on port 0
08-30 10:21:39.977   321  7054 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-30 10:21:39.977   321  7054 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ba0 on port 0
08-30 10:21:39.977   321  7054 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-30 10:21:39.977   321  7054 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b50 on port 0
08-30 10:21:39.977   321  7054 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-30 10:21:39.977   321  7054 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a60 on port 0
08-30 10:21:39.977   321  7054 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-30 10:21:39.978   321  7054 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-30 10:21:39.978   321  7054 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f240 on port 1
08-30 10:21:39.978   321  7054 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-30 10:21:39.978   321  7054 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7dd0 on port 1
08-30 10:21:39.978   321  7054 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-30 10:21:39.978   321  7054 V OMXCodec: [OMX.google.vorbis.decoder], freeing buffer 0xb54f7f10 on port 1
08-30 10:21:39.978   321  7054 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-30 10:21:39.978   321  7054 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7f60 on port 1
08-30 10:21:39.978   321  7054 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-30 10:21:39.978   321  7054 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-30 10:21:39.978   321   321 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-30 10:21:39.978   321   321 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-30 10:21:39.978   321  7054 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-30 10:21:39.978   321  7054 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-30 10:21:39.978   321  7054 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-30 10:21:39.978   321   321 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-30 10:21:39.978   321   321 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-30 10:21:39.978   321   321 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-30 10:21:39.979   321   321 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-30 10:21:39.979   321   321 D AudioPlayer: AudioPlayer releasing audio source
08-30 10:21:39.979   321   321 D AudioPlayer: AudioPlayer done releasing audio source
08-30 10:21:39.979   321   321 V AwesomePlayer: reset_l() 
08-30 10:21:39.979   321   321 V AwesomePlayer: cancelPlayerEvents
08-30 10:21:39.979   321   321 V AwesomePlayer: ~AwesomePlayer call
08-30 10:21:39.979   321   321 V AwesomePlayer: reset_l() 
08-30 10:21:39.980   321   321 V AwesomePlayer: cancelPlayerEvents
08-30 10:21:39.980  6950  7051 V SoundPool: close(31)
08-30 10:21:39.980  6950  7051 V SoundPool: pointer = 0xa0037000, size = 205080, sampleRate = 48000, numChannels = 2
08-30 10:21:39.990  6950  6950 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-30 10:21:39.991  6950  6950 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
,08-30 10:21:39.993  6950  6950 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:638
08-30 10:21:40.196  6735  6735 I UEI.SmartControl: Supports setup maps: true
,08-30 10:21:40.198  6735  6735 D UEI.SmartControl: QS start statue = true Error code = 0,
08-30 10:21:40.199  6735  6735 I UEI.SmartControl: QS version = v2.7.10.1_RC1
,08-30 10:21:40.199  6735  6735 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-30 10:21:40.199  6735  6735 I UEI.SmartControl: ### init IR Blaster...,
08-30 10:21:40.202  6735  6735 D serial_port: Configuring serial port
,08-30 10:21:40.202  6735  6735 E UEI.SmartControl: UEIBLaster setting for 616
,08-30 10:21:40.202  6735  6735 I UEI.SmartControl: Setting serial record hearder size = 2
08-30 10:21:40.202  6735  6735 I UEI.SmartControl: configuring settings for MAXQ616
08-30 10:21:40.202  6735  6735 I UEI.SmartControl: Get version...
08-30 10:21:40.221  6735  7056 D UEI.SmartControl: serial port data available: 21
,08-30 10:21:40.248  6735  6735 D UEI.SmartControl: MAXQ616 A2-X4 software.
,08-30 10:21:40.248  6735  6735 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-30 10:21:40.248  6735  6735 I UEI.SmartControl: QS saving settings...
,08-30 10:21:40.251  6735  6735 D UEI.SmartControl: IR Blaster version: 25672567
,08-30 10:21:40.268  6735  7056 D UEI.SmartControl: serial port data available: 4
,08-30 10:21:40.303  6735  7065 I UEI.SmartControl: Device manager: loading config....,
,08-30 10:21:40.306  6735  6735 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-30 10:21:40.307  6735  6735 E UEI.SmartControl: Services init done
08-30 10:21:40.307  6735  6735 D UEI.SmartControl: QS Service init finished
08-30 10:21:40.308  6735  7065 D UEI.SmartControl: ----------- loading internal config...
08-30 10:21:40.309  6735  6735 D UEI.SmartControl: QS Service version name: 2.1.91
08-30 10:21:40.309  6735  6735 D UEI.SmartControl: QS Service version code: 201091
08-30 10:21:40.313  6735  6735 D UEI.SmartControl: Service requested: Control
08-30 10:21:40.315  6735  7065 E UEI.SmartControl: Loading SETTINGS...
08-30 10:21:40.318  6735  6735 D UEI.SmartControl: Request IControl service: devices are loaded...
,08-30 10:21:40.320  6735  7065 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-30 10:21:40.326  6950  6950 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-30 10:21:40.327  6735  6735 D UEI.SmartControl: Internal service binding...
08-30 10:21:40.327  6735  6751 I UEI.SmartControl: ------ IControl API: 11
08-30 10:21:40.327  6735  6751 D UEI.SmartControl: File observer start...
08-30 10:21:40.328  6735  6751 E UEI.SmartControl: IR Port is disabled: false
08-30 10:21:40.328  6735  6751 D UEI.SmartControl: Starting file observer...
08-30 10:21:40.329  6735  6751 I UEI.SmartControl: Registering callback...
08-30 10:21:40.330  6735  6750 I UEI.SmartControl: ------ IControl API: 19
08-30 10:21:40.330  6735  7064 I UEI.SmartControl: Notify AllClients services are ready: 0
08-30 10:21:40.331  6735  7064 D UEI.SmartControl: -----service ready thread exits
,08-30 10:21:40.331  6735  6750 I UEI.SmartControl: Registering Services Ready callback...
08-30 10:21:40.332  6735  6750 I UEI.SmartControl: Notify client services are ready...
08-30 10:21:40.334  6950  6965 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-30 10:21:40.334  6950  7049 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-30 10:21:40.335  6950  7049 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-30 10:21:40.335  6950  6950 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-30 10:21:40.336  6950  6950 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-30 10:21:40.336  6735  6751 I UEI.SmartControl: ------ IControl API: 8
08-30 10:21:40.338  6950  6950 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-30 10:21:40.339  6950  6950 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-30 10:21:40.340  6950  6950 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-30 10:21:40.340  6950  6950 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-30 10:21:40.341  6950  6950 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-30 10:21:40.341  6950  6950 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-30 10:21:40.344  6950  6950 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
,08-30 10:21:40.348  6950  6950 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-30 10:21:40.349  6950  6950 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-30 10:21:40.351  6950  6950 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-30 10:21:40.352  6950  6950 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-30 10:21:40.353  6950  6950 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-30 10:21:40.354  6950  6950 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-30 10:21:40.354  6950  6950 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-30 10:21:40.355  6950  6950 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1472545300355]
08-30 10:21:40.358  6950  6950 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
08-30 10:21:40.359  1036  1729 I ActivityManager: Killing 6108:com.android.gallery3d/u0a27 (adj 15): empty #17
,08-30 10:21:40.381  6950  7067 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-30 10:21:40.430  1036  1933 W libprocessgroup: failed to open /acct/uid_10027/pid_6108/cgroup.procs: No such file or directory
,08-30 10:21:40.440  6950  6950 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
08-30 10:21:40.441  6950  6950 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-30 10:21:40.442  6950  6950 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
,08-30 10:21:40.443  6950  6950 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
,08-30 10:21:40.444  6950  6950 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-30 10:21:40.444  6950  6950 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-30 10:21:40.445  6950  6950 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
08-30 10:21:40.465  6950  6950 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,08-30 10:21:41.278  1036  1530 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-30 10:21:41.291  1036  1118 D Tethering: MasterInitialState.processMessage what=3
08-30 10:21:41.304  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 10:21:41.309  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 10:21:41.310  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 10:21:41.311  1036  1530 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-30 10:21:41.316  1036  1118 D Tethering: MasterInitialState.processMessage what=3
,08-30 10:21:41.327  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 10:21:41.330  1036  1102 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-30 10:21:41.331  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 10:21:41.332  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 10:21:41.334  6433  6433 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-30 10:21:41.337  6433  6469 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-30 10:21:41.349  5808  5808 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-30 10:21:41.357  5808  5808 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-30 10:21:41.375  2229  2229 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-30 10:21:41.404  1036  1102 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-30 10:21:41.452  1036  1952 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7078 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,08-30 10:21:41.457  1036  1102 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 10:21:41.457  1036  1102 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-30 10:21:41.523  7078  7078 I AppUp4:AppBoxCP: onCreate
,08-30 10:21:41.524  7078  7078 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
08-30 10:21:41.534  7078  7078 I AppUp4:DB:  setFingerPrint start
08-30 10:21:41.534  7078  7078 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
08-30 10:21:41.543  7078  7078 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
08-30 10:21:41.543  7078  7078 I AppUp4:DB:  SDK version = 21
08-30 10:21:41.543  7078  7078 I AppUp4:DB:  beforefinger == newfinger no write in DB
,08-30 10:21:41.545  7078  7078 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
,08-30 10:21:41.547  7078  7078 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-30 10:21:41.547  7078  7078 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-30 10:21:41.549  7078  7078 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-30 10:21:41.550  7078  7078 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-30 10:21:41.557  7078  7078 I AppUp4:CustModeStarterReceiver: onReceive
,08-30 10:21:41.601  7078  7078 D LgDataFeature: LgDataFeature() Constructor: none
,08-30 10:21:41.601  7078  7078 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 10:21:41.610  7078  7078 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@3af539be
08-30 10:21:41.610  7078  7078 D AppUp4:CustFacade: isCustomizationCompleted : false
08-30 10:21:41.610  7078  7078 D AppUp4:CustFacade: isPhone : true
08-30 10:21:41.611  7078  7078 D AppUp4:CustModeStarterReceiver: begin check event
08-30 10:21:41.612  7078  7078 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
08-30 10:21:41.612  7078  7078 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
08-30 10:21:41.613  7078  7105 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
08-30 10:21:41.613  7078  7105 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
08-30 10:21:41.613  7078  7105 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
,08-30 10:21:41.619  1036  2054 I ActivityManager: Killing 6573:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,08-30 10:21:41.686  4383  4383 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-30 10:21:41.686  4383  4383 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-30 10:21:41.687  1036  2080 W libprocessgroup: failed to open /acct/uid_10061/pid_6573/cgroup.procs: No such file or directory
,08-30 10:21:41.692  1036  1364 D PowerManagerServiceEx: acquireWakeLockInternal: lock=179175549, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1036
,08-30 10:21:41.693  4383  4383 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 10:21:41.693  1036  1364 V AlarmManager: ELAPSED_WAKEUP set : Alarm{2dea7b72 type 2 when 159360 com.google.android.gms} when 159360
08-30 10:21:41.701  4383  4383 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-30 10:21:41.711  4383  7108 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-30 10:21:41.715  4383  7109 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-30 10:21:41.715  4383  7109 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-30 10:21:41.771  1036  1952 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7110 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-30 10:21:41.792  2632  2632 D [Concierge]Service: onStartCommand(). Type : 9
,08-30 10:21:41.844  7110  7110 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 10:21:41.844  7110  7110 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-30 10:21:41.846  7110  7110 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-30 10:21:41.846  7110  7110 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-30 10:21:41.940  7110  7110 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-30 10:21:41.959  7110  7110 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,08-30 10:21:42.014  7110  7110 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-30 10:21:42.055  7110  7110 D LgDataFeature: LgDataFeature() Constructor: none
,08-30 10:21:42.055  7110  7110 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 10:21:42.189  7110  7110 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-30 10:21:42.248  3444  3444 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-30 10:21:42.248  3444  3444 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
,08-30 10:21:42.248  3444  3444 I LgeMiscReceiver: networkInfo.isConnected() = false
08-30 10:21:42.260  7110  7110 I HubEmail: JNI_OnLoad()
08-30 10:21:42.260  7110  7110 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-30 10:21:42.260  7110  7110 I HubEmail: registerNatives()
08-30 10:21:42.261  7110  7110 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-30 10:21:42.261  7110  7110 I HubEmail: registerNativeMethods()
08-30 10:21:42.261  7110  7110 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,08-30 10:21:42.261  7110  7110 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
08-30 10:21:42.304  1036  1561 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7140 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,08-30 10:21:42.310  7019  7136 W FormManager: Network not available. Please check & try again.
08-30 10:21:42.314  7110  7139 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 10:21:42.322  7019  7137 V FormManager: Network unavailable.
,08-30 10:21:42.327  7019  7137 V FormManager: Network unavailable.
08-30 10:21:42.337  1036  1763 I ActivityManager: Killing 6165:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,08-30 10:21:42.382  1036  2075 W libprocessgroup: failed to open /acct/uid_10080/pid_6165/cgroup.procs: No such file or directory
,08-30 10:21:42.465  7140  7140 D LgDataFeature: LgDataFeature() Constructor: none
08-30 10:21:42.465  7140  7140 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 10:21:42.469  7140  7140 D PhoneMonitor: Register our PhoneStateListener
08-30 10:21:42.486  7140  7140 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-30 10:21:42.488  7140  7140 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-30 10:21:42.503  7140  7140 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
08-30 10:21:42.504  7140  7140 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
08-30 10:21:42.505  7140  7140 D TelephonyAutoProfiling: [parse] Load xml
08-30 10:21:42.507  7140  7140 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
08-30 10:21:42.507  7140  7140 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
08-30 10:21:42.507  7140  7140 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-30 10:21:42.507  7140  7140 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
08-30 10:21:42.507  7140  7140 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
08-30 10:21:42.508  7140  7140 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
08-30 10:21:42.508  7140  7140 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-30 10:21:42.508  7140  7140 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-30 10:21:42.508  7140  7140 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-30 10:21:42.508  7140  7140 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-30 10:21:42.508  7140  7140 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-30 10:21:42.508  7140  7140 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-30 10:21:42.508  7140  7140 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-30 10:21:42.508  7140  7140 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-30 10:21:42.508  7140  7140 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-30 10:21:42.508  7140  7140 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-30 10:21:42.508  7140  7140 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
,08-30 10:21:42.521  7140  7140 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
08-30 10:21:42.527  1036  2075 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7159 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-30 10:21:42.529  1036  2075 I ActivityManager: Killing 6197:com.google.android.apps.plus/u0a97 (adj 15): empty #17
08-30 10:21:42.572  1036  1764 W libprocessgroup: failed to open /acct/uid_10097/pid_6197/cgroup.procs: No such file or directory
,08-30 10:21:42.794  1036  2075 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7177 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
08-30 10:21:42.795  1036  2075 I ActivityManager: Killing 6662:com.lge.eula/1000 (adj 15): empty #17
08-30 10:21:42.852  1036  1561 W libprocessgroup: failed to open /acct/uid_1000/pid_6662/cgroup.procs: No such file or directory
,08-30 10:21:42.954  1036  2080 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7194 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-30 10:21:42.955  1036  2080 I ActivityManager: Killing 6686:com.lge.bnr/1000 (adj 15): empty #17
,08-30 10:21:43.013  1036  2075 W libprocessgroup: failed to open /acct/uid_1000/pid_6686/cgroup.procs: No such file or directory
,08-30 10:21:43.044  7194  7194 I art     : Almond Protected OAT
,08-30 10:21:43.124  7194  7194 D WeatherApplication: removeAccount
,08-30 10:21:43.126  7194  7194 D WeatherApplication: Account.length = 0
08-30 10:21:43.126  7194  7194 E WeatherApplication: OPERATOR:OPEN
08-30 10:21:43.131  7194  7194 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 10:21:43
08-30 10:21:43.133  7194  7194 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-30 10:21:43.133  7194  7194 D Weather.Utils: 2 : All the weather widget is gone.
08-30 10:21:43.135  7194  7194 D UpdateThreadPoolManager: 2 : This is isUpdating : false
,08-30 10:21:43.138  7194  7194 D WeatherAncestor: connectivity changed - connection : true
08-30 10:21:43.139  7194  7194 D WeatherService: 2 : isServiceAlived():false forecastCache:null
08-30 10:21:43.146  7194  7194 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-30 10:21:43.146  7194  7194 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-30 10:21:43.146  7194  7194 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
,08-30 10:21:43.161  7194  7194 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-30 10:21:43.161  7194  7194 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 10:21:43
,08-30 10:21:43.212  1036  1933 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7212 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-30 10:21:43.213  1036  1933 I ActivityManager: Killing 2209:com.lge.music/u0a34 (adj 15): empty #17
,08-30 10:21:43.250   348   348 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 486us total 35.229ms
,08-30 10:21:43.271  1036  1522 D LGWifiP2pService: P2pDisabledState{ when=-6ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-30 10:21:43.271  1036  1522 D LGWifiP2pService: DefaultState{ when=-7ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,08-30 10:21:43.276   348   348 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 442us total 23.002ms
08-30 10:21:43.278  1036  1523 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 1 0
08-30 10:21:43.278  1036  1523 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
08-30 10:21:43.301   321  4055 V AudioFlinger: 2209 died, releasing its sessions
08-30 10:21:43.301   321  4055 V AudioFlinger:  pid 1864 @ 0
08-30 10:21:43.301   321  4055 V AudioFlinger:  pid 3444 @ 1
08-30 10:21:43.301   321  4055 V AudioFlinger:  pid 3444 @ 2
,08-30 10:21:43.303   348   348 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 412us total 21.613ms
08-30 10:21:43.363  1036  1052 D WifiServiceImplEx: setWifiEnabled: true pid=6615, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,08-30 10:21:43.364  1036  1052 D WifiService: setWifiEnabled: true pid=6615, uid=10118
08-30 10:21:43.364  1036  1052 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-30 10:21:43.369  1036  1764 W libprocessgroup: failed to open /acct/uid_10034/pid_2209/cgroup.procs: No such file or directory
,08-30 10:21:43.386  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-30 10:21:43.387  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-30 10:21:43.387  1036  1036 D Ulp_jni : JNI:system_update. Event-4
08-30 10:21:43.387  1036  1523 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-30 10:21:43.388  1036  1523 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-30 10:21:43.390  1036  1523 E WifiUtil: wfc_util_ffile_check_copy(): pid[1036] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-30 10:21:43.390  1036  1523 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-30 10:21:43.390  1036  1523 E WifiUtil: wfc_util_ffile_check_copy(): pid[1036] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-30 10:21:43.390  1036  1523 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-30 10:21:43.391  1036  1523 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-30 10:21:43.391  1036  1523 E WifiHW  : unknown target_country: EU , set to default
08-30 10:21:43.391  1036  1523 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-30 10:21:43.391  1036  1523 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-30 10:21:43.391  1036  1523 I WifiUtil: gEnableBmps=1
,08-30 10:21:43.508   280   340 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,08-30 10:21:43.508   280   340 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
,08-30 10:21:43.508   280   340 W Vold    : Returning OperationFailed - no handler for errno 0
08-30 10:21:43.510  7212  7241 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,08-30 10:21:43.517   280   340 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,08-30 10:21:43.517   280   340 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-30 10:21:43.518   280   340 W Vold    : Returning OperationFailed - no handler for errno 0
08-30 10:21:43.518  7212  7241 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-30 10:21:43.532   280   340 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-30 10:21:43.532   280   340 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-30 10:21:43.532   280   340 W Vold    : Returning OperationFailed - no handler for errno 0
08-30 10:21:43.533  7212  7246 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,08-30 10:21:43.546   280   340 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,08-30 10:21:43.546   280   340 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-30 10:21:43.546   280   340 W Vold    : Returning OperationFailed - no handler for errno 0
,08-30 10:21:43.548  7212  7246 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,08-30 10:21:43.827  7212  7212 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-30 10:21:43.839  7212  7212 I LibraryLoader: Loading: webviewchromium
,08-30 10:21:43.843  7212  7212 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 1547-1551)
,08-30 10:21:43.843  7212  7212 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-30 10:21:43.849  7212  7212 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {906772b}
08-30 10:21:43.851  7212  7212 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-30 10:21:43.851  7212  7212 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-30 10:21:43.865  7212  7212 I BrowserStartupController: Initializing chromium process, renderers=0
,08-30 10:21:43.866  7212  7212 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-30 10:21:43.883   321  1370 V AudioPolicyService: registerClient() client 0xb1021e20, uid 10093
,08-30 10:21:43.888  7212  7273 W AudioManagerAndroid: Requires BLUETOOTH permission
08-30 10:21:43.894  7212  7212 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-30 10:21:43.896  7212  7212 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
08-30 10:21:43.897  7212  7212 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
,08-30 10:21:43.924  7212  7212 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-30 10:21:43.924  7212  7212 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-30 10:21:43.924  7212  7212 I Adreno-EGL: Build Date: 12/12/14 금
08-30 10:21:43.924  7212  7212 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-30 10:21:43.924  7212  7212 I Adreno-EGL: Remote Branch: 
08-30 10:21:43.924  7212  7212 I Adreno-EGL: Local Patches: 
08-30 10:21:43.924  7212  7212 I Adreno-EGL: Reconstruct Branch: 
,08-30 10:21:44.024  7212  7212 I NSApplication: Starting up...
,08-30 10:21:44.075  1036  1561 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7292 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
08-30 10:21:44.077  1036  1561 I ActivityManager: Killing 6127:com.android.vending/u0a44 (adj 15): empty #17
,08-30 10:21:44.105   316   894 D SoftapController: Softap fwReload - Ok
,08-30 10:21:44.106  1036  1523 E NetdConnector: NDC Command {53 softap fwreload wlan0 STA} took too long (710ms)
08-30 10:21:44.108   316   894 D CommandListener: Setting iface cfg
08-30 10:21:44.108   316   894 D CommandListener: Trying to bring down wlan0
08-30 10:21:44.109   316   894 D CommandListener: Clearing all IP addresses on wlan0
08-30 10:21:44.115  1036  1523 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
08-30 10:21:44.117  1036  1523 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-30 10:21:44.117  1036  1523 E WifiStateMachine: useWiFiOffloading() : false
08-30 10:21:44.117  1036  1523 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-30 10:21:44.110  7318  7318 W wpa_supplicant: type=1400 audit(0.0:167): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 10:21:44.110  7318  7318 W wpa_supplicant: type=1400 audit(0.0:168): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-30 10:21:44.143  7318  7318 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-30 10:21:44.174  7318  7318 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-30 10:21:44.174  7318  7318 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,08-30 10:21:44.275  1036  1118 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-30 10:21:44.275  1036  1118 D Tethering: InitialState.processMessage what=4
08-30 10:21:44.277  1036  1118 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-30 10:21:44.278  1036  1523 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-30 10:21:44.278  1036  1523 D WifiMonitor: connecting to supplicant
08-30 10:21:44.280  1036  1051 W libprocessgroup: failed to open /acct/uid_10044/pid_6127/cgroup.procs: No such file or directory
,08-30 10:21:44.302  7318  7318 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-30 10:21:44.303  1955  1955 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-30 10:21:44.305  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 10:21:44.307  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 10:21:44.309  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 10:21:44.309  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-30 10:21:44.310  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 10:21:44.341  7292  7292 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-30 10:21:44.345  7318  7318 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
08-30 10:21:44.353  7318  7318 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
08-30 10:21:44.353  1036  1523 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
,08-30 10:21:44.353  7318  7318 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-30 10:21:44.353  1036  1523 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-30 10:21:44.354  1036  1523 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-30 10:21:44.354  1036  1523 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-30 10:21:44.355  1036  1523 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-30 10:21:44.355  1036  1523 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-30 10:21:44.355  1036  7323 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
08-30 10:21:44.355  1036  7323 D WifiMonitor: Dropping event because (p2p0) is stopped
08-30 10:21:44.356  1036  7323 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-30 10:21:44.356  1036  1523 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-30 10:21:44.356  1036  7323 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-30 10:21:44.356  1036  7323 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-30 10:21:44.356  1036  7323 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-30 10:21:44.356  1036  1523 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-30 10:21:44.357  1036  1523 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-30 10:21:44.357  1036  1523 D WifiNative-wlan0: doString: [DRIVER MACADDR]
,08-30 10:21:44.357  1036  1523 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-30 10:21:44.358  1036  1523 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-30 10:21:44.358  1036  1523 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-30 10:21:44.358  1036  1523 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-30 10:21:44.358  1036  1523 E WifiStateMachine: useWiFiOffloading() : false
08-30 10:21:44.358  1036  1523 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-30 10:21:44.359  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 10:21:44.359  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 10:21:44.359  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 10:21:44.359  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 10:21:44.359  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-30 10:21:44.359  1036  1523 D WifiNative-wlan0: doBoolean: SET update_config 1
08-30 10:21:44.360  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 10:21:44.361  1955  1955 D WfdService: Waiting for WifiP2p enabling
08-30 10:21:44.362  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-30 10:21:44.362  1036  1523 D WifiNative-wlan0: SET update_config 1: returned true
08-30 10:21:44.362  1036  1523 D WifiConfigStore: Loading config and enabling all networks 
08-30 10:21:44.362  1036  1523 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-30 10:21:44.362  1036  1528 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-30 10:21:44.362  6615  6615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 10:21:44.362  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 10:21:44.362  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 10:21:44.362  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 10:21:44.362  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 10:21:44.362  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 10:21:44.362  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 10:21:44.362  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 10:21:44.362  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 10:21:44.362  6615  6615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 10:21:44.362  6615  6615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 10:21:44.363  6615  6615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 10:21:44.364  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 10:21:44.364  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 10:21:44.364  6615  6615, V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 10:21:44.364  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 10:21:44.364  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 10:21:44.364  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 10:21:44.364  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 10:21:44.364  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 10:21:44.364  6615  6615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 10:21:44.364  6615  6615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 10:21:44.365  6615  6615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 10:21:44.365  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 10:21:44.365  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 10:21:44.365  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 10:21:44.365  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 10:21:44.365  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 10:21:44.365  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 10:21:44.365  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 10:21:44.365  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 10:21:44.365  6615  6615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 10:21:44.365  6615  6615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 10:21:44.363  1036  1523 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-30 10:21:44.374  1036  1523 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
,08-30 10:21:44.385  1036  1523 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk,
08-30 10:21:44.385  1036  1523 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-30 10:21:44.386  1036  1523 D WifiStateMachine: enableVerboseLogging : level 2
08-30 10:21:44.386  1036  1523 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-30 10:21:44.387  1036  1523 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-30 10:21:44.387  1036  1523 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
,08-30 10:21:44.387  1036  1523 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-30 10:21:44.387  1036  1523 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-30 10:21:44.388  1036  1523 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-30 10:21:44.388  1036  1523 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-30 10:21:44.388  1036  1523 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-30 10:21:44.388  1036  1523 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-30 10:21:44.389  1036  1523 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-30 10:21:44.389  1036  1523 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-30 10:21:44.389  1036  1523 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-30 10:21:44.389  1036  1523 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-30 10:21:44.390  1036  1523 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-30 10:21:44.390  1036  1523 D WifiStateMachine: Setting OUI to DA-A1-19
08-30 10:21:44.391  1036  1523 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-30 10:21:44.391  1955  1955 D WfdsService: Supplicant Connection state is changed : true
,08-30 10:21:44.391  1955  2317 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-30 10:21:44.391  1955  2317 D WfdsService: Set the WFDS Monitor: true
08-30 10:21:44.391  1955  2317 D WfdsMonitor: WfdsMonitorThread create
08-30 10:21:44.391  1955  2317 D WfdsMonitor: WFDS Monitor is created and started
08-30 10:21:44.391  1955  2317 D WfdsService: WiFi: Supplicant connection re-established
08-30 10:21:44.392  1036  1523 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-30 10:21:44.392  1036  1523 D WifiNative-HAL: Setting external_sim to 1
08-30 10:21:44.392  1036  1523 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-30 10:21:44.392  1036  1523 D WifiNative-wlan0: SET external_sim 1: returned true
08-30 10:21:44.392  1036  1523 I WifiNative-HAL: startHal
08-30 10:21:44.392  1036  1523 D wifi    : setting scan oui 0xaf6b9760
08-30 10:21:44.393  1955  7324 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-30 10:21:44.393  1036  1523 D WifiStateMachine: Setting OUI to DA-A1-19
08-30 10:21:44.393  1036  1523 I WifiNative-HAL: startHal
08-30 10:21:44.393  1036  1523 D wifi    : setting scan oui 0xaf6b9760
08-30 10:21:44.393  1036  1523 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-30 10:21:44.393  1955  7324 E CtrlSupplicant: Succeed to open control connection
08-30 10:21:44.393  1955  7324 E CtrlSupplicant: Succeed to open monitor connection
08-30 10:21:44.394  1955  7324 D WfdsMonitor: Supplicant connection established
08-30 10:21:44.394  1955  2317 D WfdsService: Connected to the supplicant for wfds
08-30 10:21:44.394  1036  1523 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-30 10:21:44.394  1036  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-30 10:21:44.394  7318  7318 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-30 10:21:44.394  1036  1523 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-30 10:21:44.395  1036  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-30 10:21:44.395  7318  7318 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-30 10:21:44.395  1036  1523 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-30 10:21:44.395  1036  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-30 10:21:44.395  7318  7318 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-30 10:21:44.396  1036  1523 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-30 10:21:44.396  1036  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-30 10:21:44.396  7318  7318 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-30 10:21:44.396  1036  1523 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-30 10:21:44.396  1036  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-30 10:21:44.396  7318  7318 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-30 10:21:44.397  1036  1523 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-30 10:21:44.397  1036  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-30 10:21:44.397  7318  7318 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-30 10:21:44.397  1036  1523 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-30 10:21:44.397  1036  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-30 10:21:44.398  7318  7318 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-30 10:21:44.398  1036  1523 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-30 10:21:44.399  1036  1523 E WifiNative: : [162,094,073 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-30 10:21:44.399  1036  1523 D WifiNative-wlan0: doBoolean: RECONNECT
08-30 10:21:44.399  1036  1523 D WifiNative-wlan0: RECONNECT: returned true
08-30 10:21:44.399  1036  1523 D WifiNative-wlan0: doString: [STATUS]
08-30 10:21:44.400  1036  7323 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
,08-30 10:21:44.400  1036  7323 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
,08-30 10:21:44.401  1036  1523 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-30 10:21:44.401  1036  1523 D WifiNative-wlan0: doBoolean: SET ps 1
08-30 10:21:44.402  1036  1523 D WifiNative-wlan0: SET ps 1: returned true
08-30 10:21:44.402  1036  1522 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-30 10:21:44.403  1036  1036 D WifiScanningService: SCAN_AVAILABLE : 3
08-30 10:21:44.404   316   894 D CommandListener: Setting iface cfg
08-30 10:21:44.404   316   894 D CommandListener: Trying to bring up p2p0
08-30 10:21:44.404  1036  1036 D RttService: SCAN_AVAILABLE : 3
08-30 10:21:44.404  1036  1542 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-30 10:21:44.404  1036  1542 I WifiNative-HAL: startHal
08-30 10:21:44.404  1036  1522 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-30 10:21:44.404  1036  1542 D wifi    : getting scan capabilities on interface[1] = 0xaf6b9760
08-30 10:21:44.404  1036  1543 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-30 10:21:44.404  1036  1542 D wifi    : failed to get capabilities : -3
08-30 10:21:44.404  1036  1522 D LGWifiP2pService: P2pEnablingState
08-30 10:21:44.404  1036  1542 E WifiScanningService: could not get scan capabilities
08-30 10:21:44.404  1036  1522 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-30 10:21:44.404  1036  1522 D LGWifiP2pService: P2p socket connection successful
08-30 10:21:44.404  1036  1522 D LGWifiP2pService: P2pEnabledState
08-30 10:21:44.405  1036  1522 D LGWifiP2pService: sending p2p connection changed broadcast
08-30 10:21:44.405  1955  1955 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-30 10:21:44.405  1036  1523 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-30 10:21:44.406  1955  1955 D WfdsService: WifiP2pState is changed : true
08-30 10:21:44.406  1036  1522 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-30 10:21:44.406  1955  2317 D WfdsService: Receive the WFDS_ENABLE Method
08-30 10:21:44.406  1955  2317 D WfdsService: Set the WFDS Monitor: true
08-30 10:21:44.406  1036  1523 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-30 10:21:44.406  1955  2317 D WfdsService: Connected to the supplicant for wfds
08-30 10:21:44.406  1955  2317 D WfdsJNI : doCommand: WFDS_SET TRUE
08-30 10:21:44.406  7318  7318 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-30 10:21:44.406  1955  2317 D WfdsService: selectPreferredScanChannel [36]
08-30 10:21:44.406  1036  1523 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-30 10:21:44.406  1955  2317 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-30 10:21:44.407  1036  1522 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-30 10:21:44.407  1036  1522 D WifiNative-p2p0: doBoolean: SET device_name G3
08-30 10:21:44.407  1036  1523 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-30 10:21:44.407  1036  1522 D WifiNative-p2p0: SET device_name G3: returned true
08-30 10:21:44.407  1036  1523 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-30 10:21:44.407  1036  1522 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-30 10:21:44.407  1036  1522 D LGWifiP2pService: before postfix = G3
08-30 10:21:44.407  1036  1522 D WifiServerServiceExt: postfix byte check : 2
08-30 10:21:44.407  1036  1522 D LGWifiP2pService: after postfix = G3
08-30 10:21:44.407  1036  1522 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-30 10:21:44.407  1955  1955 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-30 10:21:44.408  1036  1523 E WifiStateMachine:  ConnectModeState what:132106 1 0,
08-30 10:21:44.408  1036  1522 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-30 10:21:44.408  1036  1522 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-30 10:21:44.408  1036  1523 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-30 10:21:44.408  1036  1523 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-30 10:21:44.408  1036  1522 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-30 10:21:44.408  1955  1955 D WfdsService: isConnected: false
08-30 10:21:44.408  7318  7318 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-30 10:21:44.408  1036  1522 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-30 10:21:44.409  1036  1522 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-30 10:21:44.409  1036  1522 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-30 10:21:44.409  1036  1522 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-30 10:21:44.409  1036  1522 D WifiNative-HAL: p2pGetDeviceAddress
08-30 10:21:44.409  1036  1522 D WifiNative-HAL: p2pGetDeviceAddress returning 
08-30 10:21:44.410  1036  1523 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-30 10:21:44.410  1036  1523 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-30 10:21:44.410  1036  1523 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-30 10:21:44.411  1036  1523 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-30 10:21:44.411  7318  7318 E wpa_supplicant: disconnect_rssi_lvl: -100
08-30 10:21:44.411  1036  1522 D LGWifiP2pService: DeviceAddress: 
08-30 10:21:44.411  1036  1522 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-30 10:21:44.412  1036  1523 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
08-30 10:21:44.412  1036  1522 D WifiNative-p2p0: P2P_FLUSH: returned true
08-30 10:21:44.412  1036  1522 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-30 10:21:44.412  1036  1522 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-30 10:21:44.412  1036  1523 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
08-30 10:21:44.412  1036  1522 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-30 10:21:44.412  1955  1955 I WfdStateTracker: handleP2pThisDeviceChanged
08-30 10:21:44.413  1955  1955 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-30 10:21:44.413  1036  1522 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-30 10:21:44.413  1955  1955 D WfdsService: Update P2p Interface State: 3
08-30 10:21:44.413  1036  1522 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-30 10:21:44.413  1036  1523 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
08-30 10:21:44.414  1036  1523 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
,08-30 10:21:44.423  1036  1522 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-30 10:21:44.423  1036  1522 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-30 10:21:44.423  1036  1522 D LGWifiP2pService: InactiveState
08-30 10:21:44.423  1036  1522 D LGWifiP2pService: InactiveState{ when=-11ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-30 10:21:44.423  1036  1522 D LGWifiP2pService: P2pEnabledState{ when=-11ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-30 10:21:44.423  1036  1522 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-30 10:21:44.424  7318  7318 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-30 10:21:44.425  7318  7318 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 10:21:44.425  1036  7323 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-30 10:21:44.425  1036  7323 E WifiMonitor: WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 10:21:44.425  1036  7323 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 10:21:44.425  1036  7323 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 10:21:44.425  7318  7318 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-30 10:21:44.425  7318  7318 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 10:21:44.425  1955  7324 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 10:21:44.426  1036  7323 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 10:21:44.426  1036  7323 E WifiMonitor: WifiMonitor:p2p0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 10:21:44.426  1036  7323 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 10:21:44.426  1036  7323 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 10:21:44.426  1036  1523 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-30 10:21:44.426  7318  7318 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 10:21:44.426  1036  1523 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-30 10:21:44.427  1036  1523 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-30 10:21:44.427  1036  1523 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-30 10:21:44.427  1036  1523 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-30 10:21:44.427  7318  7318 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-30 10:21:44.427  7318  7318 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
,08-30 10:21:44.428  1955  7324 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
,08-30 10:21:44.428  1036  7323 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 10:21:44.428  1036  7323 E WifiMonitor: WifiMonitor:p2p0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 10:21:44.428  1036  7323 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 10:21:44.428  1036  7323 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 10:21:44.428  1036  7323 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-30 10:21:44.428  1036  7323 E WifiMonitor: WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-30 10:21:44.428  1036  7323 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-30 10:21:44.428  1036  7323 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-30 10:21:44.428  1036  1523 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-30 10:21:44.428  1036  1523 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-30 10:21:44.428  1036  1523 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-30 10:21:44.429  1036  1523 D WifiNative-wlan0: doBoolean: SCAN
08-30 10:21:44.429  1036  1523 D WifiNative-wlan0: SCAN: returned false
08-30 10:21:44.429  1036  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=162125  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-30 10:21:44.430  7318  7318 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-30 10:21:44.431  7318  7318 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 10:21:44.431  7318  7318 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-30 10:21:44.431  1955  7324 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-30 10:21:44.432  7318  7318 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 10:21:44.432  1036  7323 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-30 10:21:44.432  1036  7323 E WifiMonitor: WifiMonitor:p2p0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 10:21:44.432  1036  7323 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 10:21:44.432  1036  7323 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 10:21:44.432  1036  1522 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-30 10:21:44.432  1036  7323 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 10:21:44.432  1036  7323 E WifiMonitor: WifiMonitor:p2p0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 10:21:44.432  1036  1522 D LGWifiP2pService: InactiveState{ when=-8ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-30 10:21:44.432  7318  7318 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 10:21:44.432  1036  7323 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 10:21:44.432  1036  7323 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 10:21:44.432  1036  1522 D LGWifiP2pService: P2pEnabledState{ when=-8ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-30 10:21:44.432  1036  7323 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 10:21:44.432  1036  7323 E WifiMonitor: WifiMonitor:p2p0 cnt=30 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 10:21:44.432  1036  1522 D LGWifiP2pService: DefaultState{ when=-9ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-30 10:21:44.432  1036  7323 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 10:21:44.432  1036  7323 E WifiMonitor: handleEvent u,nknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 10:21:44.432  1036  1522 D LGWifiP2pService: InactiveState{ when=-9ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-30 10:21:44.432  1036  1522 D LGWifiP2pService: P2pEnabledState{ when=-9ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-30 10:21:44.432  1955  7324 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 10:21:44.433  1036  1522 D LGWifiP2pService: DefaultState{ when=-9ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-30 10:21:44.433  1955  7324 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 10:21:44.433  1036  1522 D LGWifiP2pService: InactiveState{ when=-9ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-30 10:21:44.433  1036  1522 D LGWifiP2pService: P2pEnabledState{ when=-9ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-30 10:21:44.433  1036  1522 D LGWifiP2pService: DefaultState{ when=-9ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-30 10:21:44.433  1036  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=162129  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-30 10:21:44.433  1036  1522 D LGWifiP2pService: InactiveState{ when=-9ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-30 10:21:44.433  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 10:21:44.433  1036  1523 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 10:21:44.433  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 10:21:44.433  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-30 10:21:44.434  1036  1523 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 10:21:44.434  1036  1523 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 10:21:44.434  1036  1522 D LGWifiP2pService: P2pEnabledState{ when=-9ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-30 10:21:44.434  1955  2317 W WfdsService: DefaultState - msg [9441285] is not handled
08-30 10:21:44.434  1036  1522 D LGWifiP2pService: DefaultState{ when=-10ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-30 10:21:44.434  1036  1522 D LGWifiP2pService: InactiveState{ when=-9ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-30 10:21:44.434  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 10:21:44.434  1036  1522 D LGWifiP2pService: P2pEnabledState{ when=-9ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-30 10:21:44.434  1036  1036 E WifiServerServiceExt: No p2p device connected
08-30 10:21:44.434  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 10:21:44.435  1036  1523 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 10:21:44.435  1036  1523 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
,08-30 10:21:44.436  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 10:21:44.436  1036  1036 D WifiServerServiceExt: setSupplicantStateSCANNING
08-30 10:21:44.437  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-30 10:21:44.588  6433  6433 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-30 10:21:44.591  6433  6469 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-30 10:21:44.618  2229  2229 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-30 10:21:44.629  7078  7078 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-30 10:21:44.629  7078  7078 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-30 10:21:44.629  7078  7078 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-30 10:21:44.629  7078  7078 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-30 10:21:44.631  7078  7078 I AppUp4:CustModeStarterReceiver: onReceive
,08-30 10:21:44.635  7078  7078 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@3af539be
08-30 10:21:44.635  7078  7078 D AppUp4:CustFacade: isCustomizationCompleted : false
08-30 10:21:44.636  7078  7078 D AppUp4:CustFacade: isPhone : true
08-30 10:21:44.636  7078  7078 D AppUp4:CustModeStarterReceiver: begin check event
08-30 10:21:44.636  7078  7078 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-30 10:21:44.639  4383  4383 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-30 10:21:44.639  4383  4383 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-30 10:21:44.641  4383  4383 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 10:21:44.645  4383  4383 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-30 10:21:44.654  7110  7110 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-30 10:21:44.654  4383  7331 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-30 10:21:44.655  4383  7332 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-30 10:21:44.655  4383  7332 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-30 10:21:44.685  1036  2307 I art     : Explicit concurrent mark sweep GC freed 73725(3MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/64MB, paused 1.723ms total 148.803ms
08-30 10:21:44.685  7110  7333 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 10:21:44.691  3444  3444 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-30 10:21:44.691  3444  3444 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-30 10:21:44.691  3444  3444 I LgeMiscReceiver: networkInfo.isConnected() = false
08-30 10:21:44.692  7019  7335 W FormManager: Network not available. Please check & try again.
08-30 10:21:44.695  7140  7140 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-30 10:21:44.695  7140  7140 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-30 10:21:44.707  7019  7337 V FormManager: Network unavailable.
,08-30 10:21:44.711  7194  7194 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 10:21:44
08-30 10:21:44.712  7194  7194 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-30 10:21:44.712  7194  7194 D Weather.Utils: 2 : All the weather widget is gone.
08-30 10:21:44.712  7194  7194 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-30 10:21:44.712  7194  7194 D WeatherAncestor: connectivity changed - connection : true
08-30 10:21:44.712  7194  7194 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@d69116c
08-30 10:21:44.713  7194  7194 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-30 10:21:44.713  7194  7194 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-30 10:21:44.713  7194  7194 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-30 10:21:44.713  7194  7194 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-30 10:21:44.713  7194  7194 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 10:21:44
08-30 10:21:44.713  7019  7337 V FormManager: Network unavailable.
08-30 10:21:44.734  1036  1036 D PowerManagerServiceEx: releaseWakeLockInternal: lock=179175549 [*alarm*], flags=0x0
,08-30 10:21:44.736   316  7341 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-30 10:21:44.737  1036  1116 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-30 10:21:44.737  6890  6890 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-30 10:21:44.737  6890  6890 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-30 10:21:44.738  6890  6890 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-30 10:21:44.738  6890  6890 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-30 10:21:44.738  6890  6890 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-30 10:21:44.739  6890  6890 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-30 10:21:44.739  6890  6890 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-30 10:21:44.739  6890  6890 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-30 10:21:44.739  6890  6890 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-30 10:21:44.739  6890  6890 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-30 10:21:44.740  6890  6890 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-30 10:21:44.746  6915  6915 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-30 10:21:44.750  6890  6890 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-30 10:21:44.752  7019  7343 W FormManager: Network not available. Please check & try again.
08-30 10:21:44.756  7019  7344 V FormManager: Network unavailable.
08-30 10:21:44.757  7019  7344 V FormManager: Network unavailable.
08-30 10:21:44.758  6890  6890 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 10:21:44.777  6915  6915 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-30 10:21:44.780  6890  6890 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-30 10:21:44.785  7019  7348 W FormManager: Network not available. Please check & try again.
08-30 10:21:44.785  7019  7349 V FormManager: Network unavailable.
08-30 10:21:44.787  7019  7349 V FormManager: Network unavailable.
08-30 10:21:44.787  6890  6890 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-30 10:21:44.806  4383  4383 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-30 10:21:44.807  4383  4383 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-30 10:21:44.809  4383  4383 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 10:21:44.812  4383  4383 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-30 10:21:44.819  4383  7353 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-30 10:21:44.820  4383  7354 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-30 10:21:44.821  4383  7354 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-30 10:21:44.858  1036  1951 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7355 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-30 10:21:44.945  7318  7318 E wpa_supplicant: USIM:  scard_init function
08-30 10:21:44.945  1036  7323 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-30 10:21:44.946  1036  7323 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
,08-30 10:21:44.946  7318  7318 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-30 10:21:44.946  1036  7323 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-30 10:21:44.946  1036  7323 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: WPS-AP-AVAILABLE 
08-30 10:21:44.946  1036  7323 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-30 10:21:44.946  1036  7323 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-30 10:21:44.946  1036  7323 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-30 10:21:44.948  1036  1523 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=11 bcn=0
08-30 10:21:44.951  1036  1523 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=11 bcn=0
08-30 10:21:44.952  1036  1523 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=11 bcn=0
08-30 10:21:44.954  1036  1523 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=11 bcn=0
08-30 10:21:44.954  1036  1523 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-30 10:21:44.964  1036  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=162659  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-30 10:21:44.966  1036  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=162662  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-30 10:21:44.970  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 10:21:44.970  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 10:21:44.971  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 10:21:44.971  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 10:21:44.972  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 10:21:44.972  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
,08-30 10:21:44.978  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 10:21:44.978  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 10:21:44.978  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-30 10:21:44.979  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 10:21:44.979  1036  1036 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-30 10:21:44.989  7355  7355 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-30 10:21:44.989  7355  7355 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-30 10:21:44.993  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 10:21:44.993  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 10:21:44.994  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 10:21:44.997  7355  7355 V [BNRBootReceiver]: Boot Receiver Return
08-30 10:21:44.997  7355  7355 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-30 10:21:44.999  6433  6433 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 10:21:45.005  6890  6890 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 10:21:45.009  6890  6890 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-30 10:21:45.018  6950  6950 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 10:21:45.018  6950  6950 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-30 10:21:45.020  6950  6950 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-30 10:21:45.022  6890  6890 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
08-30 10:21:45.025  6890  6890 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-30 10:21:45.028  6433  6433 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 10:21:45.034  6890  6890 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 10:21:45.039  6890  6890 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 10:21:45.047  6950  6950 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-30 10:21:45.047  6950  6950 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 10:21:45.049  6950  6950 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-30 10:21:45.053  6433  6433 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 10:21:45.065  7318  7318 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
08-30 10:21:45.065  1036  7323 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-30 10:21:45.065  1036  7323 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-30 10:21:45.065  1036  7323 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-30 10:21:45.066  1036  7323 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: Associated with f4:f2:6d:22:99:3e
,08-30 10:21:45.066  1036  7323 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 10:21:45.066  1036  7323 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-30 10:21:45.067  1036  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=162763  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-30 10:21:45.068  1036  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=162764  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-30 10:21:45.069  1036  1118 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-30 10:21:45.070  1036  1523 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=162766
08-30 10:21:45.071  1036  1523 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=162767
08-30 10:21:45.072  1036  1523 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=162768
08-30 10:21:45.072  6890  6890 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-30 10:21:45.073  1036  1523 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=162769
08-30 10:21:45.074  1036  1523 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=162769
08-30 10:21:45.075  1036  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=162770  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
,08-30 10:21:45.078  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 10:21:45.079  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 10:21:45.080  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 10:21:45.080  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 10:21:45.080  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-30 10:21:45.082  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 10:21:45.084  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 10:21:45.084  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 10:21:45.084  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-30 10:21:45.085  1036  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=162781  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-30 10:21:45.086  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 10:21:45.086  1036  1036 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-30 10:21:45.087  1036  1523 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
08-30 10:21:45.087  1036  1523 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-30 10:21:45.087  1036  1523 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-30 10:21:45.088  1036  1523 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-30 10:21:45.088  6890  6890 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 10:21:45.088  1036  1523 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,08-30 10:21:45.093  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 10:21:45.093  1036  1036 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-30 10:21:45.098  6950  6950 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 10:21:45.098  6950  6950 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 10:21:45.099  6950  6950 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-30 10:21:45.100  1036  7323 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 10:21:45.100  1036  7323 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-30 10:21:45.100  7318  7318 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-30 10:21:45.100  7318  7318 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-30 10:21:45.100  1036  7323 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-30 10:21:45.100  1036  7323 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-30 10:21:45.100  1036  7323 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-30 10:21:45.100  1036  7323 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-30 10:21:45.100  1036  7323 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-30 10:21:45.100  1036  7323 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-30 10:21:45.101  1036  7323 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 10:21:45.101  1036  7323 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-30 10:21:45.101  1036  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=162797  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-30 10:21:45.102  1036  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=162798  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-30 10:21:45.103  1036  1523 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=162799
08-30 10:21:45.103  1036  1523 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=162799
08-30 10:21:45.104  1036  1523 D WifiNative-wlan0: doString: [STATUS]
08-30 10:21:45.104  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 10:21:45.104  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 10:21:45.104  1036  7323 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 10:21:45.104  1036  7323 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,08-30 10:21:45.105  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 10:21:45.105  1036  1523 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-30 10:21:45.105  6890  6890 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-30 10:21:45.105  6890  6890 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-30 10:21:45.106  6890  6890 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-30 10:21:45.106  6890  6890 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-30 10:21:45.106  6890  6890 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-30 10:21:45.107  6890  6890 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-30 10:21:45.107  6890  6890 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-30 10:21:45.107  1036  1523 I WifiServiceExtension: setVHTCapabilityType  : false
08-30 10:21:45.107  6890  6890 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-30 10:21:45.107  6890  6890 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-30 10:21:45.107  6890  6890 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-30 10:21:45.107  6890  6890 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-30 10:21:45.108  6890  6890 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-30 10:21:45.110  6433  6433 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 10:21:45.116  1036  1523 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-30 10:21:45.116  1036  1523 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
,08-30 10:21:45.121  6890  6890 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-30 10:21:45.126  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 10:21:45.126  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 10:21:45.127  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 10:21:45.127  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 10:21:45.127  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-30 10:21:45.127  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 10:21:45.128  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 10:21:45.128  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 10:21:45.128  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-30 10:21:45.128  6890  6890 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-30 10:21:45.129  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 10:21:45.129  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 10:21:45.131  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 10:21:45.132  1036  1523 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-30 10:21:45.132  1036  1530 D ConnectivityService: Got NetworkAgent Messenger
08-30 10:21:45.132  1036  1523 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-30 10:21:45.132  1036  1523 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-30 10:21:45.132  1036  1530 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-30 10:21:45.132  1036  1530 D ConnectivityService: NetworkAgent connected
08-30 10:21:45.133  1036  1523 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-30 10:21:45.133  1036  1523 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-30 10:21:45.137  6950  6950 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 10:21:45.137  6950  6950 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 10:21:45.137  6950  6950 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-30 10:21:45.140  1036  1523 D WifiNative-wlan0: SAVE_CONFIG: returned true
,08-30 10:21:45.140  1036  1523 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-30 10:21:45.141  1036  1523 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-30 10:21:45.141  1036  1523 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-30 10:21:45.141  1036  1523 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
,08-30 10:21:45.143  6433  6433 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 10:21:45.146  1036  1523 D WifiNative-wlan0: SAVE_CONFIG: returned true
,08-30 10:21:45.148   316   894 D CommandListener: Setting iface cfg
08-30 10:21:45.152  1036  1523 E WifiStateMachine: Start Dhcp Watchdog 2
08-30 10:21:45.152  1036  7374 D DhcpStateMachine: StoppedState
08-30 10:21:45.152  6890  6890 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-30 10:21:45.152  1036  7374 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-30 10:21:45.152  1036  7374 D DhcpStateMachine: WaitBeforeStartState
08-30 10:21:45.152  1036  1523 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=162848  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 10:21:45.153  1036  1523 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=162849  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 10:21:45.153  1036  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=162849  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 10:21:45.154  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 10:21:45.154  1036  1036 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-30 10:21:45.154  1036  1523 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=162850  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 10:21:45.155  1036  1523 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=162850  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 10:21:45.155  1036  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=162851  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 10:21:45.156  6890  6890 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 10:21:45.156  1036  1523 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:116766] from screen [on:0 period:-628477372] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-30 10:21:45.157  1036  1523 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-628477371] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-30 10:21:45.157  1036  1523 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-30 10:21:45.162  1036  1530 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
08-30 10:21:45.162  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 10:21:45.162  1036  1523 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 10:21:45.162  1036  1523 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 10:21:45.163  1036  1523 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 10:21:45.163  1036  1523 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 10:21:45.164  6950  6950 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 10:21:45.164  1036  1523 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 10:21:45.164  6950  6950 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 10:21:45.164  1036  1523 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 10:21:45.164  6950  6950 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-30 10:21:45.165  1036  1523 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=114,0,0
08-30 10:21:45.165  1036  1523 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=114,0,0
08-30 10:21:45.165  1036  1523 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-30 10:21:45.166  7318  7318 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-30 10:21:45.166  1036  1530 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-30 10:21:45.166  1036  1523 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-30 10:21:45.166  1036  1523 D WifiNative-wlan0: doBoolean: SET ps 0
08-30 10:21:45.166  6433  6433 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 10:21:45.167  1036  1523 D WifiNative-wlan0: SET ps 0: returned true
08-30 10:21:45.167  1036  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-30 10:21:45.167  7318  7318 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-30 10:21:45.168  1036  1523 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-30 10:21:45.168  1036  1522 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@24597db target=com.android.internal.util.StateMachine$SmHandler }
08-30 10:21:45.168  1036  1522 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@24597db target=com.android.internal.util.StateMachine$SmHandler }
08-30 10:21:45.168  1036  7374 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-30 10:21:45.168  1036  7374 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-30 10:21:45.168  1036  1523 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-30 10:21:45.168  1036  1523 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-30 10:21:45.168  1036  1523 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-30 10:21:45.169   316   894 D CommandListener: Setting iface cfg
08-30 10:21:45.170   316   894 D CommandListener: Trying to bring up wlan0
08-30 10:21:45.171  1036  1523 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
,08-30 10:21:45.175  6890  6890 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-30 10:21:45.176  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 10:21:45.176  1036  1036 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-30 10:21:45.177  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 10:21:45.177  1036  1036 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-30 10:21:45.177  1036  1523 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 10:21:45.177  1036  1523 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 10:21:45.178  1036  1523 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 10:21:45.178  1036  1523 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 10:21:45.178  1036  1523 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 10:21:45.179  1036  1523 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 10:21:45.179  1036  1530 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-30 10:21:45.180  1036  1523 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-30 10:21:45.180  6890  6890 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 10:21:45.180  1036  1523 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-30 10:21:45.180  1036  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-30 10:21:45.180  7318  7318 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-30 10:21:45.180  1036  1522 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 10:21:45.180  1036  1522 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 10:21:45.180  1036  1523 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-30 10:21:45.180  1036  1523 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-30 10:21:45.181  7318  7318 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-30 10:21:45.181  1036  1523 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-30 10:21:45.181  1036  1523 D WifiNative-wlan0: doBoolean: SET ps 1
08-30 10:21:45.185  6950  6950 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 10:21:45.185  6950  6950 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 10:21:45.186  6950  6950 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-30 10:21:45.189  6433  6433 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 10:21:45.196  6890  6890 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-30 10:21:45.198  1036  1523 D WifiNative-wlan0: SET ps 1: returned true
,08-30 10:21:45.198  1036  1523 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-30 10:21:45.198  1036  1530 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-30 10:21:45.198  1036  1523 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-30 10:21:45.199  1036  1523 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-30 10:21:45.199  1036  1530 D ConnectivityService: ignoring duplicate network state non-change
08-30 10:21:45.201  1036  1530 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-30 10:21:45.201  1036  1530 D ConnectivityService: Adding iface wlan0 to network 101
08-30 10:21:45.203  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 10:21:45.204  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 10:21:45.204  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-30 10:21:45.204  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 10:21:45.204  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 10:21:45.205  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 10:21:45.208  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 10:21:45.208  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 10:21:45.209  6890  6890 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-30 10:21:45.212  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 10:21:45.212  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 10:21:45.212  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 10:21:45.212  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-30 10:21:45.213  1036  1036 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-30 10:21:45.217  1955  1955 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-30 10:21:45.218  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 10:21:45.218  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 10:21:45.218  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-30 10:21:45.220  1036  1036 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-30 10:21:45.220  1036  1523 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-30 10:21:45.224  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 10:21:45.224  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 10:21:45.224  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-30 10:21:45.229  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 10:21:45.229  1586  1586 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-30 10:21:45.229  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 10:21:45.229  1036  1530 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-30 10:21:45.230  1036  1530 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
08-30 10:21:45.230  1036  1530 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
08-30 10:21:45.231   316   894 E Netd    : netlink response contains error (File exists)
08-30 10:21:45.231  1036  1530 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
08-30 10:21:45.232  6950  6950 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 10:21:45.232  6950  6950 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 10:21:45.232  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 10:21:45.232  1586  1586 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-30 10:21:45.232  1036  1530 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-30 10:21:45.232  6950  6950 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-30 10:21:45.232  1036  1530 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
08-30 10:21:45.232  1036  1530 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
08-30 10:21:45.232  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 10:21:45.236  1036  1530 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-30 10:21:45.236  1036  1530 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-30 10:21:45.236  1036  1530 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-30 10:21:45.237  1036  1530 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-30 10:21:45.237  1036  1530 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 10:21:45.237  1036  1530 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 10:21:45.237  1036  7373 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-2ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-30 10:21:45.237  1036  7373 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
,08-30 10:21:45.237  1036  7373 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-30 10:21:45.237  1036  7373 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-30 10:21:45.239  6433  6433 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 10:21:45.242  1036  1530 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-30 10:21:45.242  1036  1530 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 10:21:45.242   316  7378 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-30 10:21:45.242  1036  1530 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-30 10:21:45.242  1036  1530 D ConnectivityService: currentScore = 0, newScore = 20
08-30 10:21:45.242  1036  1530 D ConnectivityService:    accepting network in place of null
08-30 10:21:45.242  1036  1530 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 10:21:45.243  1036  1523 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 10:21:45.243  1036  1523 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 10:21:45.243  1864  1864 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 10:21:45.243  1864  1864 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-30 10:21:45.243  1036  1530 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-30 10:21:45.244  1036  1530 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-30 10:21:45.244  1036  1530 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-30 10:21:45.244  1036  1530 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-30 10:21:45.244  1036  1530 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-30 10:21:45.245  1036  1530 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBuf,ferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-30 10:21:45.246  1036  1036 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-30 10:21:45.246  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-30 10:21:45.247  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-30 10:21:45.247  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-30 10:21:45.247  1036  1530 D ConnectivityService: validation of new default Network = false
08-30 10:21:45.247  1036  1530 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-30 10:21:45.247  1036  1530 D DSQN    : enableDataServiceNotify 
08-30 10:21:45.248  1036  1530 D DSQN    : start dsqn bin
,08-30 10:21:45.250  7379  7379 W dsqn    : type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-30 10:21:45.250  7379  7379 W dsqn    : type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 10:21:45.254  1036  1530 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-30 10:21:45.254  1036  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 10:21:45.254  1036  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 10:21:45.254  1036  1530 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 10:21:45.256  1586  1797 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-30 10:21:45.259  1036  1764 I ActivityManager: Killing 6868:com.lge.lifetracker/u0a37 (adj 15): empty #17
08-30 10:21:45.271  7379  7379 E DSQN    : DSQN ssw
,08-30 10:21:45.285  1036  1051 W libprocessgroup: failed to open /acct/uid_10037/pid_6868/cgroup.procs: No such file or directory
,08-30 10:21:45.286  6890  6890 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 10:21:45.293  6890  6890 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 10:21:45.296  1826  7383 I CheckinService: active receiver: enabled
,08-30 10:21:45.304  6735  7066 D UEI.SmartControl: Internal timer expired: 4
,08-30 10:21:45.304  6735  7066 D UEI.SmartControl: unbind internal service
08-30 10:21:45.306  1826  7383 I CheckinService: Preparing to send checkin request
08-30 10:21:45.306  1826  7383 I EventLogService: Accumulating logs since 1472545200404
08-30 10:21:45.311  6950  6950 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 10:21:45.311  6950  6950 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-30 10:21:45.313  1036  1521 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
08-30 10:21:45.316  6950  6950 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-30 10:21:45.320  6433  6433 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 10:21:45.327  6890  6890 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 10:21:45.331  1586  1586 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-30 10:21:45.332  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 10:21:45.333  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-30 10:21:45.334  6890  6890 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 10:21:45.339  6950  6950 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 10:21:45.339  6950  6950 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 10:21:45.340  6950  6950 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-30 10:21:45.342   316  7378 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-30 10:21:45.342  6433  6433 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 10:21:45.347  6915  6915 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-30 10:21:45.351  1826  7383 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,08-30 10:21:45.352  6915  6915 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-30 10:21:45.357  6890  6890 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 10:21:45.362  6890  6890 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-30 10:21:45.368  6950  6950 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 10:21:45.369  6950  6950 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 10:21:45.369  6950  6950 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-30 10:21:45.370  1036  7374 D DhcpStateMachine: DHCPV4 request on wlan0
08-30 10:21:45.370  6950  6950 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-30 10:21:45.370  6950  6950 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-30 10:21:45.370  1036  7374 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-30 10:21:45.371  1036  7374 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-30 10:21:45.371  6735  7060 D serial_port: close(fd = 24)
08-30 10:21:45.375  6433  6433 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 10:21:45.370  7385  7385 W dhcpcd  : type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 10:21:45.370  7385  7385 W dhcpcd  : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 10:21:45.380  7385  7385 I dhcpcd  : version 5.5.6 starting
08-30 10:21:45.381  7385  7385 E dhcpcd  : get_duid: m
08-30 10:21:45.381  7385  7385 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-30 10:21:45.381  7385  7385 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-30 10:21:45.382  6735  7060 I UEI.SmartControl: Serial port is closed.
08-30 10:21:45.382  6915  6915 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-30 10:21:45.383  6915  6915 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-30 10:21:45.387  6890  6890 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 10:21:45.389   316  7378 D libc-netbsd: res_queryN name = clients3.google.com succeed
08-30 10:21:45.396  6890  6890 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 10:21:45.403  6950  6950 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 10:21:45.403  6950  6950 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-30 10:21:45.404  6950  6950 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-30 10:21:45.404  6950  6950 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-30 10:21:45.405  6950  6950 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-30 10:21:45.415   316   893 D LGDataListener: argv[0]=dsqncommand
08-30 10:21:45.415   316   893 D LGDataListener: argv[1]=wlan0
08-30 10:21:45.415   316   893 D LGDataListener: argv[2]=1
08-30 10:21:45.415   316   893 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-30 10:21:45.415  1036  1116 D DSQN    : DSQM DsqnNotification wlan0  1
08-30 10:21:45.415  1036  1116 D DSQN    : start to monitor internet connection
,08-30 10:21:45.444  1036  7373 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 30 Aug 2016 08:21:45 GMT], X-Android-Received-Millis=[1472545305443], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472545305415]}
,08-30 10:21:45.444  1036  7373 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-30 10:21:45.444  1036  7373 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-30 10:21:45.445  1036  1530 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101],
08-30 10:21:45.445  1036  1530 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-30 10:21:45.446  1036  1530 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 10:21:45.446  1036  1530 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 10:21:45.446  1036  1530 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-30 10:21:45.446  1036  1530 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
08-30 10:21:45.446  1036  1530 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-30 10:21:45.446  1036  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 10:21:45.447  1036  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 10:21:45.448  1036  1530 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 10:21:45.448  1586  1797 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-30 10:21:45.448  1036  1530 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 10:21:45.449  7385  7385 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-30 10:21:45.449  7385  7385 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-30 10:21:45.449  7385  7385 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-30 10:21:45.449  7385  7385 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
08-30 10:21:45.449  7385  7385 D dhcpcd  : wlan0: sending REQUEST (xid 0xb193bbc), next in 4.10 seconds
08-30 10:21:45.450  1036  1523 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 10:21:45.451  1036  1523 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 10:21:45.451  1864  1864 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 10:21:45.451  1864  1864 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-30 10:21:45.452  1036  1530 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-30 10:21:45.481  1036  1052 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7394 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,08-30 10:21:45.482  7385  7385 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
08-30 10:21:45.495  7385  7385 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
08-30 10:21:45.495  7385  7385 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
08-30 10:21:45.495  7385  7385 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-30 10:21:45.495  7385  7385 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-30 10:21:45.496  7385  7385 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,08-30 10:21:45.496  7385  7385 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-30 10:21:45.496  7385  7385 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-30 10:21:45.496  7385  7385 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,08-30 10:21:45.508  1586  1586 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-30 10:21:45.510  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 10:21:45.511  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-30 10:21:45.562  7394  7394 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,08-30 10:21:45.562  7394  7394 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-30 10:21:45.588  7394  7394 I MultiDex: VM with version 2.1.0 has multidex support
08-30 10:21:45.588  7394  7394 I MultiDex: install
08-30 10:21:45.588  7394  7394 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-30 10:21:45.597  7394  7394 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
08-30 10:21:45.601  2229  2229 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,08-30 10:21:45.612  2229  2229 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
08-30 10:21:45.612  2229  2229 D c       : Getting all permits...
08-30 10:21:45.612  2229  2229 D a       : Opening database...
08-30 10:21:45.617  2229  2229 D a       : Opening database auth.proximity.permit_store...
,08-30 10:21:45.618  2229  2229 D a       : Closing database...
08-30 10:21:45.774  1036  7374 D DhcpStateMachine: DHCPV4 succeeded on wlan0
08-30 10:21:45.776  1036  7374 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-30 10:21:45.776  1036  7374 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-30 10:21:45.776  1036  7374 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
08-30 10:21:45.776  1036  7374 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-30 10:21:45.776  1036  7374 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-30 10:21:45.776  1036  7374 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-30 10:21:45.776  1036  7374 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-30 10:21:45.776  1036  7374 D DhcpStateMachine: RunningState
,08-30 10:21:45.849  7394  7412 D LgDataFeature: LgDataFeature() Constructor: none
08-30 10:21:45.850  7394  7412 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 10:21:46.125  7437  7437 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=32 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-30 10:21:46.204  7437  7437 I dex2oat : dex2oat took 79.328ms (threads: 4)
,08-30 10:21:46.214  1036  1523 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-30 10:21:46.214  1036  1523 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-30 10:21:46.215  1036  1523 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-30 10:21:46.215  1036  1523 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-30 10:21:46.215  1036  1523 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-30 10:21:46.216  1036  1523 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-30 10:21:46.217  1036  1530 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
08-30 10:21:46.217  1036  1530 D ConnectivityService: identical MTU - not setting
08-30 10:21:46.217  1036  1530 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-30 10:21:46.217  1036  1530 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-30 10:21:46.218  1036  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 10:21:46.218  1036  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 10:21:46.218  1036  1530 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 10:21:46.219  1586  1797 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
08-30 10:21:46.229  7394  7412 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-30 10:21:46.229  7394  7412 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-30 10:21:46.229  7394  7412 I Adreno-EGL: Build Date: 12/12/14 금
08-30 10:21:46.229  7394  7412 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-30 10:21:46.229  7394  7412 I Adreno-EGL: Remote Branch: 
08-30 10:21:46.229  7394  7412 I Adreno-EGL: Local Patches: 
08-30 10:21:46.229  7394  7412 I Adreno-EGL: Reconstruct Branch: 
,08-30 10:21:46.254  1036  1530 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-30 10:21:46.376  7394  7412 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-30 10:21:46.376  7394  7412 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-30 10:21:46.376  7394  7412 I Adreno-EGL: Build Date: 12/12/14 금
08-30 10:21:46.376  7394  7412 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-30 10:21:46.376  7394  7412 I Adreno-EGL: Remote Branch: 
08-30 10:21:46.376  7394  7412 I Adreno-EGL: Local Patches: 
08-30 10:21:46.376  7394  7412 I Adreno-EGL: Reconstruct Branch: 
,08-30 10:21:46.543  7394  7412 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-30 10:21:46.543  7394  7412 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-30 10:21:46.543  7394  7412 I Adreno-EGL: Build Date: 12/12/14 금
08-30 10:21:46.543  7394  7412 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-30 10:21:46.543  7394  7412 I Adreno-EGL: Remote Branch: 
08-30 10:21:46.543  7394  7412 I Adreno-EGL: Local Patches: 
08-30 10:21:46.543  7394  7412 I Adreno-EGL: Reconstruct Branch: 
,08-30 10:21:46.737   316  7448 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,08-30 10:21:46.737   316  7448 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
,08-30 10:21:46.785   316  7448 D libc-netbsd: res_queryN name = android.clients.google.com succeed
,08-30 10:21:46.903  1826  7383 I CheckinTask: Sending checkin request (7859 bytes)
,08-30 10:21:47.195  1826  7383 I CheckinTask: Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,08-30 10:21:47.209  1826  7383 I CheckinService: active receiver: disabled
,08-30 10:21:47.236  2229  2229 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,08-30 10:21:47.254  2229  2229 I GCM     : GCM config loaded
,08-30 10:21:47.274   316  7455 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,08-30 10:21:47.276   316  7455 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
08-30 10:21:47.281  7140  7140 V SetupWizard: Connected to Gservices successfully
08-30 10:21:47.309   316  7455 D libc-netbsd: res_queryN name = mtalk.google.com succeed
,08-30 10:21:47.593  2229  7457 D GCM     : Connected
,08-30 10:21:47.628  2229  7457 D GCM     : Message class com.google.e.a.a.q
,08-30 10:21:48.164  1036  1523 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2437 sc=60 link=72 tx=57.0, 0.0, 0.0  rx=54.5 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-628474364] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-30 10:21:48.165  1036  1523 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2437 sc=60 link=72 tx=57.0, 0.0, 0.0  rx=54.5 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-628474363] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-30 10:21:48.165  1036  1523 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-30 10:21:48.189  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-30 10:21:48.216  1036  1525 V WifiInternetCheck: Single check msg out of sync, ignoring.
,08-30 10:21:48.246  1036  1530 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-30 10:21:48.261  1036  1118 D Tethering: MasterInitialState.processMessage what=3
08-30 10:21:48.279  6615  6615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 10:21:48.279  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 10:21:48.279  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 10:21:48.279  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 10:21:48.279  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 10:21:48.279  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 10:21:48.279  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 10:21:48.279  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 10:21:48.279  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 10:21:48.279  6615  6615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 10:21:48.279  6615  6615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 10:21:48.285  6615  6615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 10:21:48.285  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 10:21:48.285  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 10:21:48.285  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 10:21:48.285  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 10:21:48.285  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 10:21:48.285  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 10:21:48.285  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 10:21:48.285  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 10:21:48.285  6615  6615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 10:21:48.285  6615  6615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 10:21:48.288  6615  6615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 10:21:48.288  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 10:21:48.288  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 10:21:48.288  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 10:21:48.288  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 10:21:48.288  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 10:21:48.288  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 10:21:48.288  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 10:21:48.288  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 10:21:48.288  6615  6615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 10:21:48.288  6615  6615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 10:21:48.293  1036  1102 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-30 10:21:48.298  6433  6433 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-30 10:21:48.299  6433  6469 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-30 10:21:48.310  5808  5808 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,08-30 10:21:48.329  2229  2229 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-30 10:21:48.346  7078  7078 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-30 10:21:48.346  7078  7078 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-30 10:21:48.346  7078  7078 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-30 10:21:48.346  7078  7078 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-30 10:21:48.354  7078  7078 I AppUp4:CustModeStarterReceiver: onReceive
,08-30 10:21:48.360  7078  7078 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@3af539be
08-30 10:21:48.360  7078  7078 D AppUp4:CustFacade: isCustomizationCompleted : false
08-30 10:21:48.360  7078  7078 D AppUp4:CustFacade: isPhone : true
08-30 10:21:48.361  7078  7078 D AppUp4:CustModeStarterReceiver: begin check event
08-30 10:21:48.361  7078  7078 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-30 10:21:48.366  4383  4383 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-30 10:21:48.366  4383  4383 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-30 10:21:48.368  4383  4383 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 10:21:48.370  4383  4383 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-30 10:21:48.385  3486  3486 V DownloadManager: Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,08-30 10:21:48.389  1036  1764 D WifiServiceImplEx: setWifiEnabled: false pid=6615, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-30 10:21:48.390  1036  1764 D WifiService: setWifiEnabled: false pid=6615, uid=10118
08-30 10:21:48.390  1036  1764 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-30 10:21:48.396  7110  7110 D eas_req : ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
08-30 10:21:48.396  3486  3486 V DownloadManager: DownloadService onCreate
,08-30 10:21:48.409  1036  1523 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
,08-30 10:21:48.410  1036  1523 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
,08-30 10:21:48.414  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-30 10:21:48.415  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-30 10:21:48.415  1036  1036 D Ulp_jni : JNI:system_update. Event-4
08-30 10:21:48.416  1036  1523 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-30 10:21:48.417  1036  1523 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-30 10:21:48.419  3486  7473 I DownloadManager: in removeSpuriousFiles
08-30 10:21:48.419  1036  1523 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-30 10:21:48.419  1036  1523 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-30 10:21:48.419  1036  1523 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-30 10:21:48.419  1036  1523 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-30 10:21:48.420  3486  7473 V DownloadManager: starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
08-30 10:21:48.421  3486  7473 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@30b5a982 on behalf of 3486
08-30 10:21:48.421  1036  1523 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-30 10:21:48.421  1036  1523 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-30 10:21:48.421  3486  7473 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
08-30 10:21:48.421  3486  7473 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGEIME_5.1.29_release_repacked_ARM_XT9_MYSCRIPT_20160317004155539.apk
08-30 10:21:48.421  3486  7473 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_5.1.24_COM_COM(9012_VDF)_20160401022656759.apk
08-30 10:21:48.421  3486  7473 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
08-30 10:21:48.421  3486  7473 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
08-30 10:21:48.421  3486  7473 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
08-30 10:21:48.422  3486  7473 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
08-30 10:21:48.422  3486  7473 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/ConciergeBoard_4.40.12_COM_COM(VDF)_20160126234417577.apk
08-30 10:21:48.422  3486  7473 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
08-30 10:21:48.422  3486  7473 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
08-30 10:21:48.422  3486  7473 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
08-30 10:21:48.424  3486  7473 I DownloadManager: in trimDatabase
08-30 10:21:48.425  3486  7473 V DownloadManager: starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,08-30 10:21:48.427  3486  7473 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@338af893 on behalf of 3486
08-30 10:21:48.430  3486  3486 V DownloadManager: DownloadService onStartCommand
08-30 10:21:48.430  3486  7474 V DownloadManager: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
08-30 10:21:48.431  1036  1523 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-30 10:21:48.431  1036  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-30 10:21:48.431  3486  7474 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@698dbce on behalf of 3486
08-30 10:21:48.431  7318  7318 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-30 10:21:48.431  1036  1522 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 10:21:48.431  1036  1522 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 10:21:48.432  1036  1523 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-30 10:21:48.432  1036  1523 D WifiNative-wlan0: doBoolean: SET ps 1
08-30 10:21:48.432  1036  1523 D WifiNative-wlan0: SET ps 1: returned true
08-30 10:21:48.432   316   894 D CommandListener: Clearing all IP addresses on wlan0
08-30 10:21:48.432  1036  7374 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-30 10:21:48.442  3444  3444 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-30 10:21:48.442  3444  3444 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-30 10:21:48.442  3444  3444 I LgeMiscReceiver: networkInfo.isConnected() = true
08-30 10:21:48.442  3444  3444 D PhoneState: setPdpRejectCasuse : false
08-30 10:21:48.446  7140  7140 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-30 10:21:48.446  7140  7140 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-30 10:21:48.449  1036  1729 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 101]) by 10005
08-30 10:21:48.449  1036  7373 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-30 10:21:48.449  1036  7373 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-30 10:21:48.449  1036  7373 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-30 10:21:48.449  1036  7373 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-30 10:21:48.449  1036  7373 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-30 10:21:48.452   316  7484 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-30 10:21:48.452  1036  7373 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
08-30 10:21:48.452  1036  1116 D DSQN    : Dns fail occured do internet check.
08-30 10:21:48.452  1036  1036 D DSQN    : EVENT_INTERNET_CHECK_REQUEST received
08-30 10:21:48.452  1036  1036 D DSQN    : try Internet connection check
08-30 10:21:48.455   316  7487 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,08-30 10:21:48.456  1036  7486 D DSQN    : ThreadTCPConnectionCheck DNS fail internet is not possible
08-30 10:21:48.456  1036  7485 D DSQN    : ThreadInternetCheck internet check NOK 
08-30 10:21:48.456  1036  7485 D DSQN    : L3_DATA_SERVICE_QUALITY STATUS 0 DataEnabled: false
08-30 10:21:48.456  1036  7485 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 com.android.server.DataServiceQualityMonitor.sendDSqualityIntent:1103 com.android.server.DataServiceQualityMonitor.access$200:55 com.android.server.DataServiceQualityMonitor$ThreadInternetCheck.run:921 <bottom of call stack> 
08-30 10:21:48.456  1036  1116 D DSQN    : Dns timeout INTERNET_CHECK already in progress ignore!
08-30 10:21:48.458  1036  1036 D WifiDataContinuityService: L3_DATA_SERVICE_QUALITY_ACTION, resultStatus : 0
08-30 10:21:48.458  1955  1977 D WifiServiceExtension: isInternetCheckAvailable return false
08-30 10:21:48.458  3486  7474 V DownloadManager: processing inserted download 1
08-30 10:21:48.459  3486  7474 V DownloadManager: processing inserted download 4
08-30 10:21:48.460  3486  7474 V DownloadManager: processing inserted download 7
08-30 10:21:48.460  3486  7474 V DownloadManager: processing inserted download 8
08-30 10:21:48.461  3486  7474 V DownloadManager: processing inserted download 9
08-30 10:21:48.463  1036  1523 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 10:21:48.463  1036  1523 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 10:21:48.463  1036  1523 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 10:21:48.463  1036  1530 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-30 10:21:48.463  1036  1530 D ConnectivityService: ignoring duplicate network state non-change
08-30 10:21:48.463  1036  1530 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
08-30 10:21:48.465  1036  1522 D LGWifiP2pService: InactiveState{ when=-2ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-30 10:21:48.465  1036  1522 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-30 10:21:48.465  1036  1522 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@20b31c8c
08-30 10:21:48.465  1036  1522 D LGWifiP2pService: P2pDisablingState
08-30 10:21:48.465  1036  1522 D LGWifiP2pService: P2pDisablingState{ when=-1ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-30 10:21:48.465  1036  1522 D LGWifiP2pService: p2p socket connection lost
08-30 10:21:48.465  1036  1522 D LGWifiP2pService: P2pDisabledState
08-30 10:21:48.470  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 10:21:48.470  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 10:21:48.470  1955  1955 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-30 10:21:48.471  1036  1036 D WifiHS20: hidePasspointNotification off =false
08-30 10:21:48.471  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 10:21:48.471  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 10:21:48.471  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-30 10:21:48.472  1036  1036 D WifiHS20: hidePasspointNotification off =false
08-30 10:21:48.472  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 10:21:48.472  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 10:21:48.476  3486  7474 V DownloadManager: processing inserted download 10
08-30 10:21:48.477  3486  7474 V DownloadManager: processing inserted download 11
08-30 10:21:48.477  3486  7474 V DownloadManager: processing inserted download 12
08-30 10:21:48.478  3486  7474 V DownloadManager: processing inserted download 13
08-30 10:21:48.478  3486  7474 V DownloadManager: processing inserted download 14
08-30 10:21:48.479  3486  7474 V DownloadManager: processing inserted download 16
08-30 10:21:48.479  1036  1102 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 10:21:48.482  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 10:21:48.483  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-30 10:21:48.483  1036  1036 D WifiScanningService: SCAN_AVAILABLE : 1
08-30 10:21:48.483  1036  1036 D RttService: SCAN_AVAILABLE : 1
08-30 10:21:48.483  1036  1542 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-30 10:21:48.484  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 10:21:48.484  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 10:21:48.484  1036  1523 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-30 10:21:48.484  1036  1523 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-30 10:21:48.484  1036  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-30 10:21:48.484  7318  7318 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-30 10:21:48.485  1036  1522 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 10:21:48.485  1036  1522 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 10:21:48.485  1036  1523 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-30 10:21:48.485  1036  1523 D WifiNative-wlan0: doBoolean: SET ps 1
08-30 10:21:48.485  1036  1523 D WifiNative-wlan0: SET ps 1: returned true
08-30 10:21:48.488  1955  1955 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-30 10:21:48.488  1955  1955 D WfdsService: WifiP2pState is changed : false
08-30 10:21:48.488  1955  2317 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-30 10:21:48.489  1955  2317 D WfdsService: Set the WFDS Monitor: false
08-30 10:21:48.489  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 10:21:48.490  1955  2317 D WfdsMonitor: WFDS Monitor is stopped
08-30 10:21:48.490  1955  2317 D WfdsService: STATE : WfdsDisabledState - enter
08-30 10:21:48.490  4383  7478 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-30 10:21:48.490  1955  7324 D CtrlSupplicant: Received on exit socket, terminate
08-30 10:21:48.490  1955  7324 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-30 10:21:48.490  1955  7324 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-30 10:21:48.490  1955  7324 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-30 10:21:48.490  1955  2319 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-30 10:21:48.491  4383  7482 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-30 10:21:48.491  1955  2317 W WfdsService: DefaultState - msg [9445378] is not handled
08-30 10:21:48.494  1036  1543 D RttService: EnabledState got{ when=-12ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-30 10:21:48.496  3486  3486 V DownloadManager: DownloadService onDestroy
,08-30 10:21:48.496  7019  7488 W FormManager: Network not available. Please check & try again.
08-30 10:21:48.501  7019  7489 V FormManager: Network unavailable.
08-30 10:21:48.504  7110  7483 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 10:21:48.504  7194  7194 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 10:21:48
08-30 10:21:48.505  7194  7194 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-30 10:21:48.505  7194  7194 D Weather.Utils: 2 : All the weather widget is gone.
08-30 10:21:48.505  7194  7194 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-30 10:21:48.506  7194  7194 D WeatherAncestor: connectivity changed - connection : true
08-30 10:21:48.506  7194  7194 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@d69116c
08-30 10:21:48.506  7194  7194 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-30 10:21:48.506  7194  7194 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-30 10:21:48.506  7194  7194 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-30 10:21:48.506  7194  7194 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-30 10:21:48.507  7194  7194 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 10:21:48
08-30 10:21:48.511  7019  7489 V FormManager: Network unavailable.
08-30 10:21:48.514   316   894 D CommandListener: Clearing all IP addresses on wlan0
08-30 10:21:48.514  1036  1530 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-30 10:21:48.515  1036  1530 D DSQN    : disableDataServiceNotify
08-30 10:21:48.515  1036  1530 D DSQN    : stop dsqn bin
08-30 10:21:48.517  1036  1523 D WifiNative-p2p0: doBoolean: TERMINATE
08-30 10:21:48.517  1036  1523 D WifiNative-p2p0: TERMINATE: returned true
08-30 10:21:48.517  1036  1523 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-30 10:21:48.517  1036  1523 E WifiStateMachine: useWiFiOffloading() : false
08-30 10:21:48.517  1036  1523 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-30 10:21:48.517  1036  1036 D WifiHS20: hidePasspointNotification off =false
08-30 10:21:48.517  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-30 10:21:48.517  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 10:21:48.518  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 10:21:48.518  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 10:21:48.518  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-30 10:21:48.518  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 10:21:48.519  4383  7482 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-30 10:21:48.520  1036  1530 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
08-30 10:21:48.520  1036  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 10:21:48.520  1036  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 10:21:48.521  1036  1530 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 10:21:48.521  1036  1530 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-30 10:21:48.521  1036  7373 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-30 10:21:48.521  1036  7373 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-30 10:21:48.521  1036  7373 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-30 10:21:48.522  1586  1797 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-30 10:21:48.522  1036  1530 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-30 10:21:48.522  1036  1530 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-30 10:21:48.522  1036  1530 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-30 10:21:48.523  1955  1955 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-30 10:21:48.525  7212  7244 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
08-30 10:21:48.525  1036  1530 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-30 10:21:48.525  1036  1530 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-30 10:21:48.525  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-30 10:21:48.525  1036  1530 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-30 10:21:48.525  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 10:21:48.526  1036  1036 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-30 10:21:48.526  1036  1530 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 10:21:48.526  1036  1530 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 10:21:48.526  1036  1530 D NetworkManagementService: Removing idletimer
08-30 10:21:48.526  1036  1530 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 10:21:48.526  1864  1864 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 10:21:48.527  1864  1864 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-30 10:21:48.527  1036  1523 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 10:21:48.527  1036  1523 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 10:21:48.527  1036  1521 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-30 10:21:48.528  1036  1036 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-30 10:21:48.528  1036  1036 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-30 10:21:48.528  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-30 10:21:48.528  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-30 10:21:48.529  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-30 10:21:48.529  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-30 10:21:48.529  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-30 10:21:48.529  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-30 10:21:48.529  1036  1521 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-30 10:21:48.531  6615  6615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 10:21:48.531  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 10:21:48.531  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 10:21:48.531  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 10:21:48.531  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 10:21:48.531  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 10:21:48.531  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 10:21:48.531  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 10:21:48.531  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 10:21:48.531  6615  6615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 10:21:48.531  6615  6615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 10:21:48.532  6615  6615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 10:21:48.532  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 10:21:48.532  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 10:21:48.532  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 10:21:48.532  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 10:21:48.532  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 10:21:48.532  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 10:21:48.532  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 10:21:48.532  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 10:21:48.532  6615  6615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 10:21:48.532  6615  6615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 10:21:48.532  6615  6615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 10:21:48.532  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 10:21:48.532  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 10:21:48.532  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 10:21:48.532  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 10:21:48.532  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 10:21:48.532  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 10:21:48.532  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 10:21:48.532  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 10:21:48.532  6615  6615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 10:21:48.532  6615  6615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 10:21:48.533  6433  6433 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 10:21:48.538  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 10:21:48.538  6915  6915 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-30 10:21:48.538  6915  6915 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-30 10:21:48.538  6915  6915 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-30 10:21:48.541  6890  6890 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-30 10:21:48.545  6890  6890 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 10:21:48.550  6950  6950 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 10:21:48.551  6950  6950 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 10:21:48.552  6950  6950 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-30 10:21:48.554  6433  6433 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 10:21:48.557  6915  6915 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-30 10:21:48.557  6915  6915 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-30 10:21:48.557  6915  6915 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-30 10:21:48.559  6890  6890 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-30 10:21:48.564  6890  6890 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 10:21:48.568  6950  6950 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 10:21:48.568  6950  6950 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 10:21:48.569  1586  1586 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-30 10:21:48.569  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 10:21:48.570  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 10:21:48.573  6950  6950 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-30 10:21:48.575  6433  6433 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 10:21:48.577  6915  6915 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-30 10:21:48.577  6915  6915 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-30 10:21:48.577  6915  6915 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-30 10:21:48.579  6890  6890 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-30 10:21:48.582  7318  7318 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-30 10:21:48.582  7318  7318 I wpa_supplicant: monitor socket send errors count : 1
08-30 10:21:48.582  7318  7318 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1955-4\x00 that cannot receive messages
08-30 10:21:48.583  1036  7323 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-30 10:21:48.583  1036  7323 D WifiMonitor: Dropping event because (p2p0) is stopped
08-30 10:21:48.584  6890  6890 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 10:21:48.591  1586  1586 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,08-30 10:21:48.591  6950  6950 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-30 10:21:48.591  6950  6950 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 10:21:48.592  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 10:21:48.592  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 10:21:48.592  6950  6950 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-30 10:21:48.598  6915  6915 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-30 10:21:48.602  7019  7500 W FormManager: Network not available. Please check & try again.
08-30 10:21:48.602  6890  6890 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-30 10:21:48.605  7019  7501 V FormManager: Network unavailable.
08-30 10:21:48.607  7318  7318 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-30 10:21:48.607  1036  7323 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-30 10:21:48.608  1036  7323 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-30 10:21:48.608  1036  7323 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-30 10:21:48.608  1036  7323 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-30 10:21:48.608  7318  7318 W wpa_supplicant: USIM:  scard_deinit function
08-30 10:21:48.608  1036  7323 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 10:21:48.608  1036  7323 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-30 10:21:48.609  1036  1523 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=166304
08-30 10:21:48.609  1036  1118 D Tethering: InitialState.processMessage what=4
08-30 10:21:48.609  1036  1523 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=166305
08-30 10:21:48.609  1036  1523 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=166305  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-30 10:21:48.610  6890  6890 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 10:21:48.610  1036  1523 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=166305  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-30 10:21:48.610  1036  1118 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-30 10:21:48.610  1036  1523 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-30 10:21:48.611  1036  1523 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-30 10:21:48.615  7019  7501 V FormManager: Network unavailable.
,08-30 10:21:48.628  6890  6890 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-30 10:21:48.628  6890  6890 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-30 10:21:48.628  6890  6890 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-30 10:21:48.628  6890  6890 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
,08-30 10:21:48.629  6890  6890 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-30 10:21:48.630  6890  6890 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-30 10:21:48.630  6890  6890 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-30 10:21:48.630  6890  6890 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-30 10:21:48.630  6890  6890 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-30 10:21:48.630  6890  6890 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-30 10:21:48.630  6890  6890 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-30 10:21:48.643  7318  7318 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,08-30 10:21:48.643  1036  7323 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-30 10:21:48.643  1036  7323 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-TERMINATING 
08-30 10:21:48.643  1036  7323 D WifiMonitor: Disconnecting from the supplicant, no more events
,08-30 10:21:48.644  1036  1523 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 44 0
08-30 10:21:48.647  1036  7374 D DhcpStateMachine: StoppedState
08-30 10:21:48.647  1036  7374 D DhcpStateMachine: StoppedState{ when=-161ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-30 10:21:48.748  1955  1955 D WfdsService: Supplicant Connection state is changed : false
08-30 10:21:48.748  1955  2317 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-30 10:21:48.748  1955  2317 D WfdsService: Set the WFDS Monitor: false
08-30 10:21:48.748  1955  2317 D WfdsMonitor: WFDS Monitor is stopped
,08-30 10:21:48.752  1036  1523 D WifiOffDelayIfNotUsed: stopMonitoring
,08-30 10:21:48.752  1036  1523 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-30 10:21:48.752  1036  1523 E WifiStateMachine: useWiFiOffloading() : false
08-30 10:21:48.752  1036  1523 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-30 10:21:48.754  4383  4383 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
,08-30 10:21:48.755  4383  4383 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-30 10:21:48.757  1955  1955 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-30 10:21:48.757  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-30 10:21:48.762  2438  2438 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 10:21:48.768  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 10:21:48.773  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 10:21:48.774  4383  4383 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 10:21:48.775  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-30 10:21:48.775  1036  1528 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-30 10:21:48.775  1036  1528 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-30 10:21:48.777  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 10:21:48.778  4383  4383 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 10:21:48.786  4383  7502 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-30 10:21:48.788  6915  6915 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-30 10:21:48.788  6915  6915 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-30 10:21:48.788  6915  6915 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-30 10:21:48.792  6890  6890 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-30 10:21:48.794  7019  7504 W FormManager: Network not available. Please check & try again.
08-30 10:21:48.799  6890  6890 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-30 10:21:48.801  4383  7506 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-30 10:21:48.801  4383  7506 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-30 10:21:48.809  7019  7505 V FormManager: Network unavailable.
08-30 10:21:48.817  7019  7505 V FormManager: Network unavailable.
,08-30 10:21:48.903  1036  1364 V AlarmManager: ELAPSED_WAKEUP set : Alarm{3cd8d23e type 2 when 166597 com.google.android.gms} when 166597
,08-30 10:21:48.914  6950  6950 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
08-30 10:21:48.915  6950  6950 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:638
,08-30 10:21:48.956  1036  1523 E WifiStateMachine:  InitialState CMD_ON_QUIT 0 0
08-30 10:21:48.957  1036  1523 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
,08-30 10:21:49.593  1036  2305 I ActivityManager: Killing 6967:com.lge.settings.easy/1000 (adj 15): empty #17
,08-30 10:21:49.625  1036  2002 W libprocessgroup: failed to open /acct/uid_1000/pid_6967/cgroup.procs: No such file or directory
,08-30 10:21:49.828  1036  1364 V AlarmManager: ELAPSED_WAKEUP set : Alarm{1254989f type 2 when 167516 com.google.android.gms} when 167516
,08-30 10:21:49.840   316  7518 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-30 10:21:49.845  1036  1116 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,08-30 10:21:51.200  1036  1523 E WifiStateMachine:  InitialState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-628471328] gl rssi=-42 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-30 10:21:51.210  1036  1523 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-628471319] gl rssi=-42 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-30 10:21:51.528  1036  1530 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-30 10:21:51.544  1036  1118 D Tethering: MasterInitialState.processMessage what=3
08-30 10:21:51.555  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 10:21:51.560  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 10:21:51.561  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 10:21:51.564  1036  1530 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-30 10:21:51.568  1036  1118 D Tethering: MasterInitialState.processMessage what=3
,08-30 10:21:51.576  1036  1102 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-30 10:21:51.580  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 10:21:51.583  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 10:21:51.585  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 10:21:51.588  6433  6433 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-30 10:21:51.589  6433  6469 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-30 10:21:51.601  5808  5808 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-30 10:21:51.609  5808  5808 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-30 10:21:51.628  2229  2229 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-30 10:21:51.647  7078  7078 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-30 10:21:51.647  7078  7078 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-30 10:21:51.647  7078  7078 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-30 10:21:51.647  7078  7078 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-30 10:21:51.652  7078  7078 I AppUp4:CustModeStarterReceiver: onReceive
08-30 10:21:51.655  7078  7078 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@3af539be
08-30 10:21:51.655  7078  7078 D AppUp4:CustFacade: isCustomizationCompleted : false
08-30 10:21:51.655  7078  7078 D AppUp4:CustFacade: isPhone : true
08-30 10:21:51.656  7078  7078 D AppUp4:CustModeStarterReceiver: begin check event
08-30 10:21:51.656  7078  7078 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-30 10:21:51.661  4383  4383 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-30 10:21:51.661  4383  4383 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-30 10:21:51.663  4383  4383 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-30 10:21:51.668  4383  4383 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 10:21:51.675  7110  7110 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-30 10:21:51.691  1036  1102 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-30 10:21:51.699  4383  7531 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-30 10:21:51.700  1036  1102 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 10:21:51.700  1036  1102 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 10:21:51.710  7110  7532 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 10:21:51.714  3444  3444 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-30 10:21:51.714  3444  3444 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
,08-30 10:21:51.714  3444  3444 I LgeMiscReceiver: networkInfo.isConnected() = false
08-30 10:21:51.716  4383  7538 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-30 10:21:51.716  4383  7538 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-30 10:21:51.718  7140  7140 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-30 10:21:51.718  7140  7140 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-30 10:21:51.728  7019  7537 W FormManager: Network not available. Please check & try again.
,08-30 10:21:51.734  7019  7540 V FormManager: Network unavailable.
08-30 10:21:51.740  7194  7194 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 10:21:51
08-30 10:21:51.741  7019  7540 V FormManager: Network unavailable.
,08-30 10:21:51.742  7194  7194 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-30 10:21:51.742  7194  7194 D Weather.Utils: 2 : All the weather widget is gone.
08-30 10:21:51.742  7194  7194 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-30 10:21:51.742  7194  7194 D WeatherAncestor: connectivity changed - connection : true
08-30 10:21:51.742  7194  7194 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@d69116c
08-30 10:21:51.743  7194  7194 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-30 10:21:51.743  7194  7194 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-30 10:21:51.743  7194  7194 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-30 10:21:51.743  7194  7194 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-30 10:21:51.743  7194  7194 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 10:21:51
08-30 10:21:51.754  1036  1051 I ActivityManager: Killing 7355:com.lge.bnr/1000 (adj 15): empty #17
,08-30 10:21:51.846  1036  1764 W libprocessgroup: failed to open /acct/uid_1000/pid_7355/cgroup.procs: No such file or directory
,08-30 10:21:51.880  6433  6433 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-30 10:21:51.887  6433  6469 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-30 10:21:51.909  2229  2229 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-30 10:21:51.926  7078  7078 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-30 10:21:51.926  7078  7078 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-30 10:21:51.926  7078  7078 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-30 10:21:51.927  7078  7078 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-30 10:21:51.929  7078  7078 I AppUp4:CustModeStarterReceiver: onReceive
08-30 10:21:51.938  7078  7078 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@3af539be
08-30 10:21:51.938  7078  7078 D AppUp4:CustFacade: isCustomizationCompleted : false
08-30 10:21:51.938  7078  7078 D AppUp4:CustFacade: isPhone : true
08-30 10:21:51.939  7078  7078 D AppUp4:CustModeStarterReceiver: begin check event
08-30 10:21:51.939  7078  7078 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-30 10:21:51.946  4383  4383 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,08-30 10:21:51.948  4383  4383 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-30 10:21:51.952  4383  4383 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 10:21:51.958  4383  4383 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-30 10:21:51.970  4383  7543 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-30 10:21:51.974  7110  7110 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-30 10:21:51.975  4383  7544 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-30 10:21:51.975  4383  7544 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-30 10:21:52.006  7110  7545 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 10:21:52.019  7019  7547 W FormManager: Network not available. Please check & try again.
08-30 10:21:52.026  3444  3444 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-30 10:21:52.026  3444  3444 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-30 10:21:52.026  3444  3444 I LgeMiscReceiver: networkInfo.isConnected() = false
,08-30 10:21:52.033  7140  7140 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-30 10:21:52.034  7140  7140 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-30 10:21:52.035  7019  7548 V FormManager: Network unavailable.
08-30 10:21:52.050  7019  7548 V FormManager: Network unavailable.
,08-30 10:21:52.062  7194  7194 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 10:21:52
08-30 10:21:52.064  7194  7194 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-30 10:21:52.065  7194  7194 D Weather.Utils: 2 : All the weather widget is gone.
08-30 10:21:52.065  7194  7194 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-30 10:21:52.066  7194  7194 D WeatherAncestor: connectivity changed - connection : true
,08-30 10:21:52.066  7194  7194 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@d69116c
,08-30 10:21:52.067  7194  7194 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-30 10:21:52.068  7194  7194 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-30 10:21:52.068  7194  7194 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-30 10:21:52.068  7194  7194 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-30 10:21:52.068  7194  7194 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 10:21:52
08-30 10:21:53.423  1036  1952 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 10:21:53.424  1036  1952 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-30 10:21:53.442  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-30 10:21:53.443  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-30 10:21:53.443  1036  1036 D Ulp_jni : JNI:system_update. Event-4
08-30 10:21:53.443  1036  1118 D BluetoothManagerService: Message: 1
08-30 10:21:53.443  1036  1118 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-30 10:21:53.468  1036  1118 D BluetoothManagerService: Message: 20
08-30 10:21:53.468  1036  1118 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a22fc08:true
,08-30 10:21:53.471  1036  1522 D LGWifiP2pService: P2pDisabledState{ when=-5ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-30 10:21:53.471  1036  1522 D LGWifiP2pService: DefaultState{ when=-5ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-30 10:21:53.473  7002  7002 D BluetoothAdapterState: make
08-30 10:21:53.478  7002  7002 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-30 10:21:53.478  7002  7002 I bluedroid-qcom: init
08-30 10:21:53.479  7002  7561 I BluetoothAdapterState: Entering OffState
08-30 10:21:53.480  7002  7002 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-30 10:21:53.480  7002  7002 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-30 10:21:53.480  7002  7002 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-30 10:21:53.480  7002  7002 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-30 10:21:53.480  7002  7002 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
,08-30 10:21:53.484  7002  7002 I bluedroid-qcom: get_profile_interface socket
08-30 10:21:53.484  7002  7002 I bluedroid-qcom: get_profile_interface map_client
08-30 10:21:53.487  7002  7565 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-30 10:21:53.489  7002  7565 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-30 10:21:53.480  7564  7564 W bdaddr_loader: type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-30 10:21:53.490  7564  7564 W bdaddr_loader: type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 10:21:53.504  1036  1036 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-30 10:21:53.504  1036  1036 D BluetoothManagerService: Stored Bluetooth name: G3
,08-30 10:21:53.508  1036  1036 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-30 10:21:53.508  1036  1118 D BluetoothManagerService: Message: 40
08-30 10:21:53.508  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-30 10:21:53.509  7002  7017 I bluedroid-qcom: config_hci_snoop_log
08-30 10:21:53.510  1036  1118 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-30 10:21:53.510  1036  1118 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-30 10:21:53.511  7564  7564 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-30 10:21:53.511  7564  7564 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-30 10:21:53.511  7564  7564 I LGFTMITEM: [GET_FTM][id=8], offset=16384
08-30 10:21:53.514  7564  7564 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-30 10:21:53.520  7564  7564 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-30 10:21:53.520  7564  7564 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
,08-30 10:21:53.525  1036  1523 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
08-30 10:21:53.526  1036  1523 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
08-30 10:21:53.526  7002  7561 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-30 10:21:53.527  7002  7565 D BluetoothAdapterProperties: Name is: G3
08-30 10:21:53.527  7002  7561 D BluetoothAdapterProperties: Setting state to 11
08-30 10:21:53.527  7002  7561 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-30 10:21:53.528  1036  1118 D BluetoothManagerService: Message: 60
08-30 10:21:53.528  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-30 10:21:53.528  1036  1118 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-30 10:21:53.532  1955  1955 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-30 10:21:53.534  1586  1586 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-30 10:21:53.539  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 10:21:53.541  6890  6890 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-30 10:21:53.546  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 10:21:53.549  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 10:21:53.552  7002  7561 I LGBluetoothServiceJni: classInitNative: succeeds
08-30 10:21:53.558  7002  7002 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-30 10:21:53.558  7002  7002 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 10:21:53.559  7002  7002 V BluetoothPbapReceiver: ***********state = 11
,08-30 10:21:53.564  2229  2229 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-30 10:21:53.607  1036  2080 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7566 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-30 10:21:53.611  7002  7561 D BluetoothBondStateMachine: make
08-30 10:21:53.613  7002  7561 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d69116c
08-30 10:21:53.613  7002  7561 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-30 10:21:53.613  7002  7561 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d69116c
08-30 10:21:53.613  7002  7561 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-30 10:21:53.613  7002  7561 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-30 10:21:53.623  7002  7561 E BluetoothAdapterService: File transfer profiles supported!!
,08-30 10:21:53.631  7002  7002 D HeadsetService: Received start request. Starting profile...
08-30 10:21:53.632  7002  7002 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-30 10:21:53.632  7002  7002 D LGBluetoothHfpAdapter: Version 1.6
08-30 10:21:53.634  7002  7002 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-30 10:21:53.635  7002  7002 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-30 10:21:53.635  7002  7002 D HeadsetStateMachine: make
08-30 10:21:53.636  7002  7572 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-30 10:21:53.663  7002  7002 D LgDataFeature: LgDataFeature() Constructor: none
08-30 10:21:53.663  7002  7002 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 10:21:53.667  7002  7002 D HeadsetStateMachine: max_hf_connections = 1
,08-30 10:21:53.667  7002  7002 I bluedroid-qcom: get_profile_interface handsfree
08-30 10:21:53.669  7002  7002 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-30 10:21:53.670   321   321 V AudioPolicyService: registerClient() client 0xb1021ee0, uid 1002
08-30 10:21:53.670   321  4055 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-30 10:21:53.670   321  4055 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-30 10:21:53.670   321  4055 V AudioPolicyManagerEx: getOutput() returns output 2
08-30 10:21:53.670  7002  7002 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
,08-30 10:21:53.670   321  1371 V AudioFlinger: registerClient() client 0xb101fc40, pid 7002
08-30 10:21:53.671   321  1365 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 10:21:53.671   321  1365 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 10:21:53.673  1036  1051 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 10:21:53.673  1036  1051 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 10:21:53.674  7002  7018 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 10:21:53.675  3444  3461 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 10:21:53.675  3444  3461 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 10:21:53.675  1864  1879 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 10:21:53.675  1864  1879 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 10:21:53.676  1586  2554 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 10:21:53.676  1586  2554 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 10:21:53.682   321  1366 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 10:21:53.682   321  1366 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 10:21:53.683  1586  1604 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 10:21:53.683  1586  1604 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 10:21:53.683  1864  2551 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 10:21:53.683  1864  2551 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 10:21:53.683  3444  3459 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 10:21:53.683  3444  3459 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 10:21:53.683  1036  1764 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 10:21:53.683  1036  1764 V AudioSystem: ioConfigChanged() opening already existing output! 4
,08-30 10:21:53.685  7002  7018 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-30 10:21:53.685  7002  7018 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 10:21:53.685  7002  7018 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-30 10:21:53.685  7002  7002 V ToneGenerator: Create Track: 0xb4928a80
08-30 10:21:53.685  7002  7002 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-30 10:21:53.685  7002  7002 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-30 10:21:53.686   321  4054 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-30 10:21:53.686   321  4054 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-30 10:21:53.686   321  4054 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-30 10:21:53.686   321  4054 V AudioPolicyManagerEx: getOutput() returns output 2
08-30 10:21:53.687   321   321 I AudioFlinger: isAudioPlaybackHookOn() false
08-30 10:21:53.687  7002  7561 E BluetoothAdapterService: File transfer profiles supported!!
08-30 10:21:53.687   321  4055 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-30 10:21:53.687   321  4055 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-30 10:21:53.687   321  4055 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-30 10:21:53.687   321  4055 V AudioPolicyManagerEx: getOutput() returns output 2
08-30 10:21:53.688  7002  7002 V AudioSystem: getLatency() output 2, latency 50
08-30 10:21:53.688  7002  7002 V AudioSystem: getFrameCount() output 2, frameCount 960
08-30 10:21:53.688  7002  7002 V AudioTrack: createTrack_l() output 2 afLatency 50
08-30 10:21:53.689   321  1371 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-30 10:21:53.689   321  1371 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-30 10:21:53.689   321  1371 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-30 10:21:53.689   321  1371 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-30 10:21:53.689   321  1371 V AudioFlinger: createTrack() lSessionId: 22
08-30 10:21:53.692  7002  7002 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-30 10:21:53.692   321  1371 V AudioFlinger: acquiring 22 from 7002, for 7002
08-30 10:21:53.692   321  1371 V AudioFlinger:  added new entry for 22
08-30 10:21:53.692  7002  7002 V ToneGenerator: ToneGenerator INIT OK, time: 171401
08-30 10:21:53.692  7002  7002 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d69116c
08-30 10:21:53.694  7002  7002 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d69116c
08-30 10:21:53.694  7002  7002 D HeadsetStateMachine: Proxy object connected
08-30 10:21:53.695  7002  7002 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-30 10:21:53.695  7002  7002 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-30 10:21:53.697  7002  7002 D A2dpService: Received start request. Starting profile...
08-30 10:21:53.698  7002  7002 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-30 10:21:53.698  7002  7002 V Avrcp   : make
08-30 10:21:53.699  7002  7002 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-30 10:21:53.699  7002  7002 I bluedroid-qcom: get_profile_interface avrcp
08-30 10:21:53.700  7002  7576 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-30 10:21:53.700  7002  7576 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-30 10:21:53.700  7002  7576 D LGBluetoothHfpManager: [BTUI] listenForMultiSi,mPhoneState : start = false
08-30 10:21:53.700  7002  7576 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-30 10:21:53.701   321  1370 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7002
08-30 10:21:53.701   321  1370 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-30 10:21:53.701   321  1370 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-30 10:21:53.701   321  1370 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-30 10:21:53.701   321  1370 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-30 10:21:53.701   321  1370 V voice   : voice_set_parameters: exit with code(0)
08-30 10:21:53.701   321  1370 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-30 10:21:53.701   321  1370 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-30 10:21:53.702   321  1370 V msm8974_platform: platform_set_parameters: exit with code(0)
08-30 10:21:53.702   321  1370 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-30 10:21:53.703   321  1370 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-30 10:21:53.703   321  1370 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-30 10:21:53.703  7002  7576 V ToneGenerator: ToneGenerator destructor
08-30 10:21:53.703  7002  7576 V ToneGenerator: stopTone
08-30 10:21:53.703  7002  7576 V ToneGenerator: Delete Track: 0xb4928a80
08-30 10:21:53.704   321   321 V AudioPolicyService: AudioCommandThread() adding release output 2
08-30 10:21:53.704   321   321 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-30 10:21:53.704   321   321 V AudioFlinger: PlaybackThread::Track destructor
08-30 10:21:53.704   321  1273 V AudioPolicyService: AudioCommandThread() waking up
08-30 10:21:53.704   321   321 V AudioFlinger: removeClient_l() pid 7002, calling pid 321
08-30 10:21:53.704   321  1273 V AudioPolicyService: AudioCommandThread() processing release output 2
08-30 10:21:53.704   321  1273 V AudioPolicyManager: releaseOutput() 2
08-30 10:21:53.704   321  1273 V AudioPolicyService: AudioCommandThread() going to sleep
08-30 10:21:53.704  7002  7576 V AudioTrack: ~AudioTrack, releasing session id from 7002 on behalf of 7002
,08-30 10:21:53.704   321  4054 V AudioFlinger: releasing 22 from 7002 for 7002
08-30 10:21:53.704   321  4054 V AudioFlinger:  decremented refcount to 0
08-30 10:21:53.704   321  4054 V AudioFlinger: purging stale effects
08-30 10:21:53.705  7002  7561 E BluetoothAdapterService: File transfer profiles supported!!
08-30 10:21:53.715  7002  7002 V AudioManager: registerRemoteController: size of Media player list: 0
,08-30 10:21:53.718  7002  7002 E AudioManager: No RCC entry present to update
08-30 10:21:53.718  7002  7561 E BluetoothAdapterService: File transfer profiles supported!!
08-30 10:21:53.718  7002  7002 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-30 10:21:53.723  7002  7002 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-30 10:21:53.724  7002  7561 E BluetoothAdapterService: File transfer profiles supported!!
08-30 10:21:53.724  7002  7002 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-30 10:21:53.724  7002  7002 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-30 10:21:53.728  7002  7002 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,08-30 10:21:53.732  7002  7561 E BluetoothAdapterService: File transfer profiles supported!!
,08-30 10:21:53.791  7002  7561 E BluetoothAdapterService: File transfer profiles supported!!
08-30 10:21:53.808  7002  7561 V LGMDMManager: Create singleton instance
,08-30 10:21:53.812  7002  7561 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-30 10:21:53.866  1036  2075 V SIM_STK : Menu title from STK is T-Mobile
,08-30 10:21:53.866  1036  2075 V SIM_STK : Menu title from STK is T-Mobile
08-30 10:21:53.885  7566  7566 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
,08-30 10:21:53.886  7566  7566 W LG Account v2.2: No ProfileInfo entries
08-30 10:21:53.886  7566  7566 I LG Account v2.2: isEnabled: false
08-30 10:21:53.887  7566  7566 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-30 10:21:53.887  7566  7566 I Feature : [Lifetracker]Country: EU
08-30 10:21:53.887  7566  7566 I Feature : [Lifetracker]Operator: OPEN
08-30 10:21:53.887  7566  7566 I Feature : [Lifetracker]Ranking support: false
08-30 10:21:53.887  7566  7566 I Feature : [Lifetracker]Comfort support: false
08-30 10:21:53.888  7566  7566 I Feature : [Lifetracker]Accessory: true
08-30 10:21:53.888  7566  7566 I Feature : [Lifetracker]Health device: true
08-30 10:21:53.888  7566  7566 I Feature : [Lifetracker]Extra Pedometer: false
08-30 10:21:53.888  7566  7566 I Feature : [Lifetracker]Blood glucose device: false
08-30 10:21:53.888  7566  7566 I Feature : [Lifetracker]Device Number: 3
08-30 10:21:53.903  6890  6890 D BluetoothPermissionRequest: onReceive
,08-30 10:21:53.912  6890  6890 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-30 10:21:53.935  1036  2080 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-30 10:21:53.943  7002  7002 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-30 10:21:53.946  7002  7002 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
,08-30 10:21:53.947  7002  7002 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-30 10:21:53.947  7002  7002 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-30 10:21:53.947  7002  7002 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-30 10:21:53.947  7002  7002 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-30 10:21:53.948  7002  7002 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-30 10:21:53.948  7002  7002 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-30 10:21:53.948  7002  7002 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-30 10:21:53.948  7002  7002 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-30 10:21:53.948  7002  7002 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-30 10:21:53.948  7002  7002 I BluetoothA2dpServiceJni: classInitNative
,08-30 10:21:53.948  7002  7002 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-30 10:21:53.948  7002  7002 D A2dpStateMachine: make
08-30 10:21:53.950  7002  7002 I bluedroid-qcom: get_profile_interface a2dp
08-30 10:21:53.951  7002  7606 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-30 10:21:53.953  7002  7002 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-30 10:21:53.953  7002  7002 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-30 10:21:53.953  7002  7002 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d69116c
08-30 10:21:53.954  7002  7605 D A2dpStateMachine: Enter Disconnected: -2
08-30 10:21:53.957  7002  7002 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-30 10:21:53.958  7002  7002 I BluetoothHidServiceJni: classInitNative: succeeds
08-30 10:21:53.959  7002  7576 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-30 10:21:53.960  7002  7576 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-30 10:21:53.960  7002  7576 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-30 10:21:53.961  7002  7002 D HidService: Received start request. Starting profile...
08-30 10:21:53.961  7002  7002 I bluedroid-qcom: get_profile_interface hidhost
08-30 10:21:53.961  7002  7002 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d69116c
08-30 10:21:53.962  7002  7002 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-30 10:21:53.964  7002  7002 D HealthService: Received start request. Starting profile...
08-30 10:21:53.966  7002  7002 I bluedroid-qcom: get_profile_interface health
08-30 10:21:53.966  7002  7002 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-30 10:21:53.966  7002  7002 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d69116c
,08-30 10:21:53.967  7002  7002 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-30 10:21:53.968  7002  7002 D PanService: Received start request. Starting profile...
08-30 10:21:53.968  7002  7002 D BluetoothPanServiceJni: initializeNative(L110): pan
08-30 10:21:53.968  7002  7002 I bluedroid-qcom: get_profile_interface pan
08-30 10:21:53.982  7002  7002 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-30 10:21:53.982  7002  7002 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d69116c
,08-30 10:21:53.983  7002  7002 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-30 10:21:53.986  7002  7002 D BtGatt.DebugUtils: handleDebugAction() action=null
08-30 10:21:53.987  7002  7002 D BtGatt.GattService: Received start request. Starting profile...
08-30 10:21:53.987  7002  7002 D BtGatt.GattService: start()
08-30 10:21:53.987  7002  7002 I bluedroid-qcom: get_profile_interface gatt
08-30 10:21:53.987  7002  7002 D BtGatt.AdvertiseManager: advertise manager created
08-30 10:21:53.995  7002  7002 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d69116c
,08-30 10:21:53.996  7002  7002 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d69116c
08-30 10:21:53.996  7002  7002 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-30 10:21:53.997  7002  7002 V BluetoothMapService: BluetoothMapBinder()
08-30 10:21:53.997  7002  7002 D BluetoothMapService: Received start request. Starting profile...
08-30 10:21:53.997  7002  7002 D BluetoothMapService: start()
08-30 10:21:54.000  7002  7002 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-30 10:21:54.000  7002  7002 D BluetoothMapEmailAppObserver: createReceiver()
08-30 10:21:54.001  7002  7002 D BluetoothMapEmailAppObserver: initObservers()
08-30 10:21:54.001  7002  7002 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-30 10:21:54.006  7002  7002 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d69116c
,08-30 10:21:54.012  7002  7002 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-30 10:21:54.014  7002  7002 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-30 10:21:54.017  7002  7002 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-30 10:21:54.017  7002  7002 V PanService: [BTUI] SIM Extra State :ABSENT
08-30 10:21:54.020  7002  7002 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-30 10:21:54.023  7002  7002 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-30 10:21:54.023  7002  7002 V BluetoothMapService: Handler(): got msg=1
08-30 10:21:54.024  7002  7561 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-30 10:21:54.024  7002  7561 I bluedroid-qcom: enable
08-30 10:21:54.024  7002  7561 I bt_hci_bdroid: init
08-30 10:21:54.025  7002  7561 I bt_vendor: bt-vendor : init
08-30 10:21:54.025  7002  7561 I bt_vendor: bt-vendor : get_bt_soc_type
08-30 10:21:54.025  7002  7561 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-30 10:21:54.025  7002  7561 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-30 10:21:54.025  7002  7561 D bt_userial_mct: userial_init
08-30 10:21:54.025  7002  7002 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-30 10:21:54.025  7002  7617 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-30 10:21:54.026  7002  7617 I bt-btu  : btu_task pending for preload complete event
08-30 10:21:54.026  7002  7561 D bt_hci_bdroid: set_power 1
08-30 10:21:54.026  7002  7561 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-30 10:21:54.026  7002  7561 I bt_vendor: Starting hciattach daemon
08-30 10:21:54.026  7002  7561 I bt_vendor: try to set true
08-30 10:21:54.020  7620  7620 W sh      : type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 10:21:54.020  7620  7620 W sh      : type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 10:21:54.029  7002  7002 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-30 10:21:54.030  7002  7002 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-30 10:21:54.030  7002  7002 V BluetoothSapReceiver: SapReceiver onReceive 
08-30 10:21:54.030  7002  7002 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 10:21:54.030  7002  7002 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-30 10:21:54.043  7621  7621 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-30 10:21:54.077  1036  1729 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=7627 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-30 10:21:54.112  7645  7645 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
08-30 10:21:54.119  7627  7627 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-30 10:21:54.122  7646  7646 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
08-30 10:21:54.135  1036  2307 I ActivityManager: Killing 6915:com.lge.sync/1000 (adj 15): empty #17
,08-30 10:21:54.143  7648  7648 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-30 10:21:54.154  7649  7649 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-30 10:21:54.165  7650  7650 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
08-30 10:21:54.176  7651  7651 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-30 10:21:54.193  1036  2054 W libprocessgroup: failed to open /acct/uid_1000/pid_6915/cgroup.procs: No such file or directory
,08-30 10:21:54.202  7653  7653 I libmdmdetect: ESOC framework not supported
,08-30 10:21:54.203  7653  7653 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
08-30 10:21:54.211  7653  7653 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-30 10:21:54.211  7653  7653 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-30 10:21:54.212  7653  7653 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-30 10:21:54.212  7653  7653 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
,08-30 10:21:54.212  7653  7653 D bthci_qcomm_common: [BTUI]     LE: Class 2
,08-30 10:21:54.212  7653  7653 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
,08-30 10:21:54.212  7653  7653 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-30 10:21:54.250  7653  7654 E QC-QMI  : qmi_client [7653] 14: failed to locate client data
08-30 10:21:54.251   476   476 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-30 10:21:54.251   476   476 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
,08-30 10:21:54.292  7655  7655 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-30 10:21:54.309  7656  7656 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-30 10:21:54.329  7002  7561 I bt_vendor: bluetooth satus is on
,08-30 10:21:54.330  7002  7561 D bt_hci_bdroid: preload
08-30 10:21:54.330  7002  7619 D bt_userial_mct: userial_open(port:0)
08-30 10:21:54.330  7002  7619 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-30 10:21:54.334  7002  7619 I bt_vendor: Done intiailizing UART
,08-30 10:21:54.335  7002  7619 I bt_vendor: Done intiailizing UART
08-30 10:21:54.335  7002  7619 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-30 10:21:54.335  7002  7619 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-30 10:21:54.335  7002  7658 D bt_userial_mct: Entering userial_read_thread()
08-30 10:21:54.336  7002  7617 I bt-btu  : btu_task received preload complete event
08-30 10:21:54.336  7002  7617 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-30 10:21:54.337  7002  7617 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-30 10:21:54.342  7002  7617 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-30 10:21:54.348  7002  7617 I         : BTE_InitTraceLevels -- TRC_HCI
08-30 10:21:54.348  7002  7617 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-30 10:21:54.348  7002  7617 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-30 10:21:54.348  7002  7617 I         : BTE_InitTraceLevels -- TRC_AVDT
08-30 10:21:54.348  7002  7617 I         : BTE_InitTraceLevels -- TRC_AVRC
08-30 10:21:54.348  7002  7617 I         : BTE_InitTraceLevels -- TRC_A2D
08-30 10:21:54.348  7002  7617 I         : BTE_InitTraceLevels -- TRC_BNEP
08-30 10:21:54.348  7002  7617 I         : BTE_InitTraceLevels -- TRC_BTM
,08-30 10:21:54.348  7002  7617 I         : BTE_InitTraceLevels -- TRC_HID_HOST
,08-30 10:21:54.348  7002  7617 I         : BTE_InitTraceLevels -- TRC_GAP
08-30 10:21:54.348  7002  7617 I         : BTE_InitTraceLevels -- TRC_PAN
08-30 10:21:54.349  7002  7617 I         : BTE_InitTraceLevels -- TRC_SDP
08-30 10:21:54.349  7002  7617 I         : BTE_InitTraceLevels -- TRC_GATT
08-30 10:21:54.349  7002  7617 I         : BTE_InitTraceLevels -- TRC_SMP
08-30 10:21:54.349  7002  7617 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-30 10:21:54.349  7002  7617 I         : BTE_InitTraceLevels -- TRC_BTIF
08-30 10:21:54.441  7002  7617 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-30 10:21:54.441  7002  7617 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa0245061 
08-30 10:21:54.441  7002  7617 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0245061 
,08-30 10:21:54.462  7002  7565 E bt-btif : Calling BTA_HhEnable
08-30 10:21:54.462  7002  7565 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-30 10:21:54.463  7002  7617 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
,08-30 10:21:54.463  7002  7617 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-30 10:21:54.463  7002  7617 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-30 10:21:54.463  7002  7617 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-30 10:21:54.463  7002  7617 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-30 10:21:54.464  7002  7565 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-30 10:21:54.468  7002  7565 D BluetoothAdapterProperties: Name is: G3
08-30 10:21:54.469  1036  1036 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-30 10:21:54.470  1036  1036 D BluetoothManagerService: Stored Bluetooth name: G3
08-30 10:21:54.471  7002  7565 D BluetoothAdapterProperties: Scan Mode:20
08-30 10:21:54.472  7002  7565 D BluetoothAdapterProperties: Discoverable Timeout:120
08-30 10:21:54.472  7002  7565 D bt_hci_bdroid: postload
08-30 10:21:54.472  7002  7619 D bt_hci_bdroid: Used up Tx Cmd credits
08-30 10:21:54.474  7002  7619 D bt_hci_bdroid: Used up Tx Cmd credits
08-30 10:21:54.474  7002  7617 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-30 10:21:54.475  7002  7619 D bt_hci_bdroid: Used up Tx Cmd credits
,08-30 10:21:54.475  7002  7619 D bt_hci_bdroid: Used up Tx Cmd credits
08-30 10:21:54.476  7002  7565 D bte_conf: Device ID record 1 : primary
08-30 10:21:54.476  7002  7565 D bte_conf:   vendorId            = 00c4
08-30 10:21:54.476  7002  7565 D bte_conf:   vendorIdSource      = 0001
08-30 10:21:54.476  7002  7565 D bte_conf:   product             = 13a1
08-30 10:21:54.476  7002  7565 D bte_conf:   version             = 1000
08-30 10:21:54.476  7002  7565 D bte_conf:   clientExecutableURL = 
08-30 10:21:54.476  7002  7565 D bte_conf:   serviceDescription  = 
,08-30 10:21:54.476  7002  7565 D bte_conf:   documentationURL    = 
08-30 10:21:54.476  7002  7565 D bte_conf: bte_load_did_conf no section named DID2.
08-30 10:21:54.482  7002  7617 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-30 10:21:54.482  7002  7617 W bt-smp  : Plain text(LSB ~ MSB) = 84 4e 69 00 00 00 00 00 00 00 00 00 00 00 00 00 
,08-30 10:21:54.482  7002  7617 W bt-smp  : Encrypted text(LSB ~ MSB) = da 6e 3e 68 6b 73 14 2b f5 03 39 47 a6 ff 8a fa 
08-30 10:21:54.482  7002  7617 W bt-btm  : Stopping oneshot timer
08-30 10:21:54.482  7002  7619 D bt_hci_bdroid: Used up Tx Cmd credits
08-30 10:21:54.482  7002  7619 D bt_hci_bdroid: Used up Tx Cmd credits
08-30 10:21:54.480  7663  7663 W sh      : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 10:21:54.480  7663  7663 W sh      : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 10:21:54.487  7002  7658 E bt_mct  : hci lib postload completed
08-30 10:21:54.487  7002  7561 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-30 10:21:54.488  7002  7561 D BluetoothAdapterProperties: ScanMode =  20
08-30 10:21:54.488  7002  7561 D BluetoothAdapterProperties: State =  11
08-30 10:21:54.488  7002  7561 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-30 10:21:54.488  7002  7561 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-30 10:21:54.488  7002  7561 D BluetoothAdapterProperties: Setting state to 12
08-30 10:21:54.488  7002  7561 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-30 10:21:54.489  1036  1118 D BluetoothManagerService: Message: 60
08-30 10:21:54.490  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-30 10:21:54.490  1036  1118 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
08-30 10:21:54.490  1036  1118 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-30 10:21:54.494  7002  7561 I BluetoothAdapterState: Entering On State
08-30 10:21:54.499  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 10:21:54.499  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 10:21:54.499  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 10:21:54.499  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 10:21:54.499  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 10:21:54.499  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 10:21:54.499  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 10:21:54.499  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 10:21:54.501  7002  7565 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-30 10:21:54.501  7002  7565 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-30 10:21:54.504  1036  1036 D BluetoothA2dp: Proxy object connected
,08-30 10:21:54.507  7002  7561 D LGBluetoothServiceAdapter: [BTUI] OnState
08-30 10:21:54.507  7002  7561 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-30 10:21:54.508  7002  7561 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-30 10:21:54.509  7002  7561 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-30 10:21:54.510  6615  6615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 10:21:54.515  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 10:21:54.515  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 10:21:54.515  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 10:21:54.515  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 10:21:54.515  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 10:21:54.515  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 10:21:54.515  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 10:21:54.515  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 10:21:54.519  6615  6615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 10:21:54.524  1864  1879 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 10:21:54.526  7002  7565 D BluetoothAdapterProperties: Discoverable Timeout:120
08-30 10:21:54.526  7002  7565 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-30 10:21:54.529  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 10:21:54.529  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 10:21:54.529  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 10:21:54.529  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 10:21:54.529  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 10:21:54.529  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 10:21:54.529  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 10:21:54.529  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 10:21:54.534  6615  6615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 10:21:54.537  1864  1864 D BluetoothHeadset: Proxy object connected
08-30 10:21:54.538  7002  7617 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-30 10:21:54.538  7002  7617 W bt-smp  : Plain text(LSB ~ MSB) = 2e 0a 61 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-30 10:21:54.538  7002  7617 W bt-smp  : Encrypted text(LSB ~ MSB) = f1 cb 33 cc 91 17 63 37 22 2f a3 c0 e6 74 58 cc 
08-30 10:21:54.539  7002  7617 W bt-btm  : Stopping oneshot timer
08-30 10:21:54.539  6890  6911 D BluetoothPan: onBluetoothStateChange on: true
08-30 10:21:54.539  6890  6911 D BluetoothPan: onBluetoothStateChange call bindService
08-30 10:21:54.544  7002  7561 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-30 10:21:54.547  1864  1880 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-30 10:21:54.552  6890  6890 D BluetoothPan: BluetoothPAN Proxy object connected
08-30 10:21:54.552  6890  6890 D PanProfile: Bluetooth service connected
08-30 10:21:54.563  1864  1864 D BluetoothHeadset: Proxy object connected
08-30 10:21:54.564  6890  6909 D BluetoothPbap: onBluetoothStateChange: up=true
,08-30 10:21:54.567  7002  7617 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-30 10:21:54.567  7002  7617 W bt-smp  : Plain text(LSB ~ MSB) = 6c da 69 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-30 10:21:54.567  7002  7617 W bt-smp  : Encrypted text(LSB ~ MSB) = 07 5c b4 30 ce 62 b4 89 1e 88 0d 36 70 af 9c dc 
08-30 10:21:54.567  7002  7617 W bt-btm  : Stopping oneshot timer
08-30 10:21:54.571  1864  1879 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 10:21:54.573  1864  1864 D BluetoothHeadset: Proxy object connected
08-30 10:21:54.574  6890  6911 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-30 10:21:54.577  1036  1118 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 10:21:54.577  6890  6890 D BluetoothInputDevice: Proxy object connected
08-30 10:21:54.577  6890  6890 D HidProfile: Bluetooth service connected
08-30 10:21:54.577  7678  7678 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-30 10:21:54.578  1036  1036 D BluetoothHeadset: Proxy object connected
08-30 10:21:54.580  6890  6909 D BluetoothMap: onBluetoothStateChange: up=true
,08-30 10:21:54.582  7002  7617 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-30 10:21:54.582  7002  7617 W bt-smp  : Plain text(LSB ~ MSB) = 50 3e 7b 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-30 10:21:54.582  7002  7617 W bt-smp  : Encrypted text(LSB ~ MSB) = 60 5b d3 f3 d1 de 66 3a 7d e3 58 1e 41 f3 6a b3 
08-30 10:21:54.583  7002  7617 W bt-btm  : Stopping oneshot timer
08-30 10:21:54.582  1036  1118 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-30 10:21:54.583  1036  1118 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-30 10:21:54.584  6890  6890 D BluetoothMap: Proxy object connected
08-30 10:21:54.584  6890  6890 D MapProfile: Bluetooth service connected
08-30 10:21:54.584  6890  6890 D BluetoothMap: getConnectedDevices()
08-30 10:21:54.584  1036  1036 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-30 10:21:54.585  1036  1118 D BluetoothManagerService: Message: 40
08-30 10:21:54.585  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-30 10:21:54.585  7002  7018 V BluetoothMapService: getConnectedDevices()
08-30 10:21:54.586  1955  1955 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-30 10:21:54.586  1955  2155 D LGBluetoothAPIService: Message: 1
08-30 10:21:54.586  1955  2155 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-30 10:21:54.587  1586  1586 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-30 10:21:54.592  7002  7617 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-30 10:21:54.592  7002  7617 W bt-smp  : Plain text(LSB ~ MSB) = 85 b8 55 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-30 10:21:54.592  7002  7617 W bt-smp  : Encrypted text(LSB ~ MSB) = c3 84 cd 2b 5d be 2d 61 3b ea 96 3b 29 1f 09 cf 
08-30 10:21:54.592  7002  7617 W bt-btm  : Stopping oneshot timer
,08-30 10:21:54.593  1955  2155 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
08-30 10:21:54.596  7002  7002 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-30 10:21:54.596  7002  7002 D BluetoothMapService: STATE_ON
08-30 10:21:54.597  6890  6890 D LocalBluetoothProfileManager: Adding local A2DP profile
08-30 10:21:54.598  7002  7002 D LGBluetoothAPIServer: [BTUI] onCreate()
08-30 10:21:54.598  7002  7002 V BluetoothMapService: Handler(): got msg=1
08-30 10:21:54.599  6615  6615 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
08-30 10:21:54.600  1036  1118 D BluetoothManagerService: Message: 30
08-30 10:21:54.600  7002  7002 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-30 10:21:54.601  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 10:21:54.602  7002  7002 D LGBluetoothAPIServer: [BTUI] onBind()
08-30 10:21:54.604  1955  1955 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-30 10:21:54.604  1955  2155 D LGBluetoothAPIService: Message: 100
08-30 10:21:54.604  1955  2155 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-30 10:21:54.605  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 10:21:54.608  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 10:21:54.611  6890  6890 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-30 10:21:54.612  7002  7683 D BluetoothMapMasInstance: MAS initSocket()
08-30 10:21:54.612  7002  7683 D BluetoothMapMasInstance:   masId = 00
08-30 10:21:54.612  7002  7683 D BluetoothMapMasInstance:   msgTypes = 0e
08-30 10:21:54.612  7002  7683 D BluetoothMapMasInstance:   masName = SMS/MMS
08-30 10:21:54.612  7002  7683 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-30 10:21:54.615  1036  1118 D BluetoothManagerService: Message: 30
08-30 10:21:54.617  1036  2080 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 10:21:54.619  7002  7683 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 10:21:54.620  7002  7002 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d69116c
08-30 10:21:54.620  7002  7002 V BluetoothPbapService: Pbap Service onCreate
08-30 10:21:54.620  7002  7002 V BluetoothPbapService: Starting PBAP service
08-30 10:21:54.622  7002  7683 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-30 10:21:54.622  7002  7683 V BluetoothMapMasInstance: Succeed to create listening socket 
08-30 10:21:54.622  7002  7683 D BluetoothMapMasInstance: Accepting socket connection...
08-30 10:21:54.622  7002  7002 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-30 10:21:54.623  7002  7002 V BluetoothPbapService: Pbap Service onBind
08-30 10:21:54.738  1036  2054 I art     : Explicit concurrent mark sweep GC freed 121548(5MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/64MB, paused 1.797ms total 117.638ms
,08-30 10:21:54.740  7002  7002 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 10:21:54.740  7002  7002 V BluetoothPbapService: state: 12
08-30 10:21:54.740  7002  7002 V BluetoothPbapService: Handler(): got msg=1
08-30 10:21:54.740  7002  7565 D BluetoothAdapterProperties: Scan Mode:21
08-30 10:21:54.740  7002  7565 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-30 10:21:54.741  7002  7002 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-30 10:21:54.743  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 10:21:54.745  7002  7684 V BluetoothPbapService: Pbap Service initSocket
08-30 10:21:54.746  1036  1561 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 10:21:54.748  7002  7684 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 10:21:54.750  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 10:21:54.752  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 10:21:54.754  7002  7684 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-30 10:21:54.754  6890  6890 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-30 10:21:54.754  7002  7684 V BluetoothPbapService: Succeed to create listening socket 
,08-30 10:21:54.754  7002  7684 V BluetoothPbapService: Accepting socket connection...
08-30 10:21:54.755  6890  6890 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-30 10:21:54.757  6890  6890 D BluetoothA2dp: Proxy object connected
08-30 10:21:54.758  6890  6890 D A2dpProfile: Bluetooth service connected
08-30 10:21:54.761  7002  7002 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-30 10:21:54.761  7002  7002 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 10:21:54.761  7002  7002 V BluetoothPbapReceiver: ***********state = 12
,08-30 10:21:54.763  6890  6890 D BluetoothHeadset: Proxy object connected
08-30 10:21:54.763  6890  6890 D HeadsetProfile: Bluetooth service connected
08-30 10:21:54.765  6890  6890 D BluetoothPbap: Proxy object connected
08-30 10:21:54.766  6890  6890 D PbapServerProfile: Bluetooth service connected
08-30 10:21:54.768  2229  2229 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-30 10:21:54.770  2229  2229 D c       : Getting all permits...
08-30 10:21:54.770  2229  2229 D a       : Opening database...
,08-30 10:21:54.775  6890  6890 D DockEventReceiver: finishStartingService: stopping service
,08-30 10:21:54.781  2229  2229 D a       : Opening database auth.proximity.permit_store...
08-30 10:21:54.783  2229  2229 D a       : Closing database...
08-30 10:21:54.799  6890  6890 D BluetoothPermissionRequest: onReceive
,08-30 10:21:54.803  6890  6890 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
,08-30 10:21:54.805  6890  6890 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-30 10:21:54.810  7002  7002 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-30 10:21:54.813  7002  7002 I LGBluetoothOppAdapter: [BTUI] startOppService()
,08-30 10:21:54.826  7002  7002 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-30 10:21:54.863  7002  7002 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-30 10:21:54.863  7002  7002 V BtOppService: onCreate
,08-30 10:21:54.872  7002  7002 V BluetoothOppNotification: send message
08-30 10:21:54.876  7002  7002 V BtOppService: Starting RfcommListener
08-30 10:21:54.882  7002  7002 D BluetoothOppPreference: Dumping Names:  
08-30 10:21:54.882  7002  7002 D BluetoothOppPreference: {}
08-30 10:21:54.883  7002  7002 D BluetoothOppPreference: Dumping Channels:  
08-30 10:21:54.883  7002  7002 D BluetoothOppPreference: {}
08-30 10:21:54.883  7002  7002 V BtOppService: onStartCommand
,08-30 10:21:54.885  7002  7692 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-30 10:21:54.888  7002  7002 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-30 10:21:54.888  7002  7002 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-30 10:21:54.892  7002  7002 V BluetoothOppNotification: new notify threadi!
08-30 10:21:54.893  7002  7002 V BluetoothOppNotification: send delay message
08-30 10:21:54.894  7002  7002 V BtOppService: start RfcommListener
08-30 10:21:54.898  7002  7002 V BtOppService: RfcommListener started
,08-30 10:21:54.901  7002  7694 V BtOppRfcommListener: Starting RFCOMM listener....
08-30 10:21:54.902  1036  1561 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 10:21:54.903  7002  7692 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-30 10:21:54.903  7002  7689 V BtOppService: Deleted complete outbound shares, number =  0
08-30 10:21:54.904  7002  7694 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 10:21:54.905  7002  7693 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-30 10:21:54.906  7002  7692 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2a937801 on behalf of 
08-30 10:21:54.907  7002  7694 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=79 mFd=75
08-30 10:21:54.907  7002  7694 V BtOppRfcommListener: Started RFCOMM listener....
08-30 10:21:54.908  7002  7694 I BtOppRfcommListener: Accept thread started.
08-30 10:21:54.908  7002  7694 V BtOppRfcommListener: Accepting connection...
08-30 10:21:54.908  7002  7689 V BtOppService: Deleted complete inbound failed shares, number = 0
08-30 10:21:54.909  7002  7689 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-30 10:21:54.910  7002  7693 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@212096a6 on behalf of 
,08-30 10:21:54.913  7002  7692 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
,08-30 10:21:54.913  7002  7692 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-30 10:21:54.913  7002  7689 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@332ae8e7 on behalf of 
08-30 10:21:54.914  7002  7693 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-30 10:21:54.915  7002  7693 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-30 10:21:54.918  7002  7692 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@25e5bc94 on behalf of 
08-30 10:21:54.918  7002  7693 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@10be933d on behalf of 
08-30 10:21:54.920  7002  7693 V BluetoothOppNotification: outbound: succ-0  fail-0
08-30 10:21:54.921  7002  7692 V BluetoothOppNotification: update too frequent, put in queue
08-30 10:21:54.922  7002  7002 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d69116c
08-30 10:21:54.922  7002  7002 V BluetoothFtpService: Ftp Service onCreate
08-30 10:21:54.922  7002  7002 I BluetoothFtpService: Ftp Service onCreate
08-30 10:21:54.922  7002  7002 V BluetoothFtpService: Ftp Service onStartCommand
08-30 10:21:54.922  7002  7002 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 10:21:54.923  7002  7002 V BluetoothFtpService: Starting Listening on sockets
08-30 10:21:54.923  7002  7693 V BluetoothOppNotification: outbound notification was removed.
,08-30 10:21:54.923  7002  7002 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-30 10:21:54.923  7002  7002 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-30 10:21:54.923  7002  7693 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-30 10:21:54.923  7002  7002 V BluetoothSapReceiver: SapReceiver onReceive 
08-30 10:21:54.923  7002  7002 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 10:21:54.923  7002  7002 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-30 10:21:54.923  7002  7002 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-30 10:21:54.924  7002  7692 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-30 10:21:54.925  7002  7002 V BtOppService: ContentObserver received notification
08-30 10:21:54.925  7002  7002 V BtOppService: ContentObserver received notification
08-30 10:21:54.925  7002  7002 V BluetoothFtpService: Handler(): got msg=1
08-30 10:21:54.926  7002  7693 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3d332c83 on behalf of 
08-30 10:21:54.926  7002  7002 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-30 10:21:54.926  7002  7002 V BluetoothFtpService: Ftp Service initSocket
08-30 10:21:54.926  7002  7695 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-30 10:21:54.927  7002  7695 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-30 10:21:54.928  7002  7693 V BluetoothOppNotification: inbound: succ-0  fail-0
08-30 10:21:54.930  7002  7695 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@16ac0e00 on behalf of 
08-30 10:21:54.930  7002  7693 V BluetoothOppNotification: inbound notification was removed.
08-30 10:21:54.930  7002  7693 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-30 10:21:54.930  7002  7695 V BluetoothOppNotification: update too frequent, put in queue
08-30 10:21:54.931  1036  1764 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 10:21:54.932  7002  7002 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 10:21:54.932  7002  7693 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@27862639 on behalf of 
08-30 10:21:54.933  7002  7002 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=81 mFd=79
08-30 10:21:54.933  7002  7002 V BluetoothFtpService: Succeed to create listening socket on channel 20
,08-30 10:21:54.932  7002  7695 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
,08-30 10:21:54.941  7002  7696 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-30 10:21:54.949  7002  7002 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d69116c
08-30 10:21:54.949  7002  7002 V BluetoothSapService: Sap Service onCreate
08-30 10:21:54.952  7002  7002 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 10:21:54.952  7002  7002 V BluetoothSapService: state: 12
08-30 10:21:54.952  7002  7002 V BluetoothSapService: Starting SAP server process
,08-30 10:21:54.955  7002  7002 V BluetoothSapService: SAP Service startRfcommListenerThread
,08-30 10:21:54.950  7697  7697 W sapd    : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 10:21:54.950  7697  7697 W sapd    : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 10:21:54.956  7002  7698 V BluetoothSapService: Sap Service initRfcommSocket
08-30 10:21:54.957  1036  2022 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 10:21:54.958  7002  7698 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 10:21:54.959  7002  7698 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=81
08-30 10:21:54.959  7002  7698 V BluetoothSapService: Succeed to create listening socket 
08-30 10:21:54.959  7002  7698 V BluetoothSapService: Accepting socket connection...
08-30 10:21:54.966  7697  7697 V BT_SAP  : Event pipe created
08-30 10:21:54.967  7697  7697 V BT_SAP  : create_server_socket qcom.sap.server
08-30 10:21:54.967  7697  7697 V BT_SAP  : created socket fd 6
,08-30 10:21:55.380  1586  1586 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,08-30 10:21:55.394  1036  1414 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-30 10:21:55.476  1036  1104 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7708 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-30 10:21:55.483  1586  1586 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
,08-30 10:21:55.483  1586  1586 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
08-30 10:21:55.525  2081  2081 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-30 10:21:55.543  1036  1036 D administrator: Handling package changes for user 0
,08-30 10:21:55.578  2081  2081 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-30 10:21:55.607  7708  7708 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-30 10:21:55.655  1036  1036 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
08-30 10:21:55.655  1036  1036 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-30 10:21:55.698  7708  7708 D LgDataFeature: LgDataFeature() Constructor: none
,08-30 10:21:55.698  7708  7708 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 10:21:55.714  1036  1102 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-30 10:21:55.720  1036  1102 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,08-30 10:21:55.729  2081  2081 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-30 10:21:55.730  2438  2438 V GmsNetworkLocationProvi: DISABLE
,08-30 10:21:55.766  2438  2438 E GCoreFlp: Bound FusedProviderService with LocationManager
,08-30 10:21:55.770  1036  1102 D LocationProviderProxy: applying state to connected service
,08-30 10:21:55.828  7708  7753 I Babel   : MmsConfig: mnc/mcc: 0/0
08-30 10:21:55.828  7708  7753 I Babel   : MmsConfig.loadMmsSettings
,08-30 10:21:55.831  7708  7753 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
,08-30 10:21:55.831  7708  7753 I Babel   : MmsConfig.loadFromDatabase
,08-30 10:21:55.851  7708  7753 E Babel   : canonicalizeMccMnc: invalid mccmnc 
08-30 10:21:55.851  7708  7753 I Babel   : MmsConfig.loadFromResources
08-30 10:21:55.857  7708  7753 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
08-30 10:21:55.858  7708  7753 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
,08-30 10:21:55.882  7708  7708 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 10:21:55.895  7002  7002 V BluetoothOppNotification: new notify threadi!
08-30 10:21:55.895  7708  7752 W AudioCapabilities: Unsupported mime audio/evrc
08-30 10:21:55.895  7002  7002 V BluetoothOppNotification: send delay message
,08-30 10:21:55.897  7002  7755 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-30 10:21:55.899  7002  7755 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2699ecf5 on behalf of 
08-30 10:21:55.900  7002  7755 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-30 10:21:55.900  7708  7752 W AudioCapabilities: Unsupported mime audio/qcelp
08-30 10:21:55.901  7002  7755 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-30 10:21:55.903  7002  7755 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@103aba8a on behalf of 
08-30 10:21:55.904  7002  7755 V BluetoothOppNotification: outbound: succ-0  fail-0
08-30 10:21:55.905  7708  7752 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
08-30 10:21:55.906  7002  7755 V BluetoothOppNotification: outbound notification was removed.
08-30 10:21:55.906  7002  7755 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-30 10:21:55.908  7002  7755 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1e93a8fb on behalf of 
08-30 10:21:55.909  7002  7755 V BluetoothOppNotification: inbound: succ-0  fail-0
08-30 10:21:55.910  7002  7755 V BluetoothOppNotification: inbound notification was removed.
08-30 10:21:55.910  7002  7755 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
,08-30 10:21:55.915  7002  7755 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2f7d9d18 on behalf of 
08-30 10:21:55.916  1826  7757 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
08-30 10:21:55.916  1826  7757 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
08-30 10:21:55.922  7078  7078 I AppUp4:CustModeStarterReceiver: onReceive
,08-30 10:21:55.931  7078  7078 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@3af539be
08-30 10:21:55.931  7078  7078 D AppUp4:CustFacade: isCustomizationCompleted : false
08-30 10:21:55.931  7078  7078 D AppUp4:CustFacade: isPhone : true
08-30 10:21:55.931  1826  4822 I Icing   : updateResources: need to parse e{com.google.android.gms}
08-30 10:21:55.931  7078  7078 D AppUp4:CustModeStarterReceiver: begin check event
08-30 10:21:55.931  7078  7078 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
08-30 10:21:55.940  7708  7752 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
,08-30 10:21:55.945  7708  7752 W AudioCapabilities: Unsupported mime audio/qcelp
08-30 10:21:55.946  7708  7752 W AudioCapabilities: Unsupported mime audio/evrc
08-30 10:21:55.956  7708  7752 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-30 10:21:55.959  7708  7752 W VideoCapabilities: Unsupported mime video/divx
08-30 10:21:55.962  7708  7752 W VideoCapabilities: Unsupported mime video/divx311
08-30 10:21:55.965  1036  2054 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7760 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
08-30 10:21:55.966  7708  7752 W VideoCapabilities: Unsupported mime video/divx4
08-30 10:21:55.968  1036  1729 I ActivityManager: Killing 6735:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,08-30 10:21:55.983  7708  7752 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,08-30 10:21:55.985  6950  6950 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
08-30 10:21:55.985  6950  6950 W System.err: android.os.DeadObjectException
08-30 10:21:55.990  6950  6950 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-30 10:21:55.990  6950  6950 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-30 10:21:55.990  6950  6950 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-30 10:21:55.991  6950  6950 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-30 10:21:55.991  6950  6950 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-30 10:21:55.991  6950  6950 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-30 10:21:55.991  6950  6950 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-30 10:21:55.991  6950  6950 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-30 10:21:55.991  6950  6950 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-30 10:21:55.991  6950  6950 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-30 10:21:55.991  6950  6950 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 10:21:55.991  6950  6950 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 10:21:55.991  6950  6950 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-30 10:21:55.991  6950  6950 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-30 10:21:55.991  6950  6950 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-30 10:21:55.991  6950  6950 W System.err: android.os.DeadObjectException
08-30 10:21:55.991  6950  6950 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-30 10:21:55.991  6950  6950 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-30 10:21:55.992  6950  6950 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-30 10:21:55.992  6950  6950 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-30 10:21:55.992  6950  6950 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-30 10:21:55.992  6950  6950 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-30 10:21:55.992  6950  6950 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-30 10:21:55.992  6950  6950 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-30 10:21:55.992  6950  6950 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-30 10:21:55.992  6950  6950 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-30 10:21:55.992  6950  6950 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 10:21:55.992  6950  6950 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 10:21:55.992  6950  6950 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-30 10:21:55.992  6950  6950 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-30 10:21:55.992  6950  6950 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-30 10:21:55.992  6950  6950 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
08-30 10:21:56.007  7708  7752 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-30 10:21:56.011  7708  7752 W AudioCapabilities: Unsupported mime audio/eac3
,08-30 10:21:56.017  7708  7752 W AudioCapabilities: Unsupported mime audio/ac3
08-30 10:21:56.017  7708  7752 W AudioCapabilities: Unsupported mime audio/g726
08-30 10:21:56.018  7708  7752 W AudioCapabilities: Unsupported mime audio/wma-voice
08-30 10:21:56.018  7708  7752 W AudioCapabilities: Unsupported mime audio/x-ms-wma
08-30 10:21:56.019  7708  7752 W AudioCapabilities: Unsupported mime audio/adpcm
,08-30 10:21:56.021  7708  7752 W VideoCapabilities: Unsupported mime video/theora
08-30 10:21:56.023  7708  7752 W VideoCapabilities: Unsupported mime video/mjpg
,08-30 10:21:56.233  1036  1933 W libprocessgroup: failed to open /acct/uid_1000/pid_6735/cgroup.procs: No such file or directory
,08-30 10:21:56.234  1036  1933 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
08-30 10:21:56.242  6950  6950 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-30 10:21:56.244  6950  6950 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-30 10:21:56.258  7760  7760 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 10:21:56.258  7760  7760 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-30 10:21:56.258  7760  7760 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,08-30 10:21:56.259  7760  7760 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
08-30 10:21:56.259  7760  7760 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-30 10:21:56.279  1036  2307 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7780 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-30 10:21:56.280  6950  6950 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-30 10:21:56.330  7780  7780 D UEI.SmartControl: Quickset Services start...
08-30 10:21:56.331  7780  7780 I UEI.SmartControl: Manufacture = LGE
08-30 10:21:56.331  7780  7780 D UEI.SmartControl: Id = LGNevo
,08-30 10:21:56.335  7780  7780 D UEI.SmartControl: File observer start...
08-30 10:21:56.337  7780  7780 E UEI.SmartControl: IR Port is disabled: false
08-30 10:21:56.337  7780  7780 D UEI.SmartControl: Starting file observer...
08-30 10:21:56.338  7780  7780 D UEI.SmartControl: Extracting JNI libs...
08-30 10:21:56.338  7780  7780 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
08-30 10:21:56.366  7760  7760 I SystemConfig: BUILD Country: EU
08-30 10:21:56.367  7760  7760 I SystemConfig: BUILD Operator: OPEN
,08-30 10:21:56.402  1036  1952 I ActivityManager: Killing 6950:com.lge.qremote/u0a112 (adj 15): empty #17
,08-30 10:21:56.427  7780  7780 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,08-30 10:21:56.427  7780  7780 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
,08-30 10:21:56.427  7780  7780 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
08-30 10:21:56.454  7780  7780 I UEI.SmartControl: --- Selecting new region: 6
,08-30 10:21:56.455  7780  7780 I UEI.SmartControl: Model = LG-D855
,08-30 10:21:56.457  7780  7780 D UEI.SmartControl: QS Service created
08-30 10:21:56.464  1036  1729 W libprocessgroup: failed to open /acct/uid_10112/pid_6950/cgroup.procs: No such file or directory
08-30 10:21:56.478  7760  7804 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
08-30 10:21:56.479  7780  7780 I UEI.SmartControl: Service initServices...
08-30 10:21:56.479  7760  7804 I SystemConfig: existFile = false
,08-30 10:21:56.479  7760  7804 I SystemConfig: canReadFile = false
08-30 10:21:56.479  7760  7804 I SystemConfig: systemFeature RCS result false
08-30 10:21:56.480  7760  7804 D SystemConfig: refreshRcsSupport() :false
08-30 10:21:56.484  7780  7780 D UEI.SmartControl: QS start get config
08-30 10:21:56.517  7780  7780 D UEI.SmartControl: Loading JNI Libs...
,08-30 10:21:56.524  1036  2307 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7807 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,08-30 10:21:56.586  7807  7807 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 10:21:56.586  7807  7807 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-30 10:21:56.587  7807  7807 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-30 10:21:56.587  7807  7807 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-30 10:21:56.697  7807  7807 I AppConfig: Total System Memory = 2995761152
,08-30 10:21:56.707  7807  7807 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
08-30 10:21:56.802  1036  1763 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7829 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-30 10:21:56.805  1036  1763 I ActivityManager: Killing 7394:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
08-30 10:21:56.856  7780  7780 I UEI.SmartControl: Supports setup maps: true
,08-30 10:21:56.862  7780  7780 D UEI.SmartControl: QS start statue = true Error code = 0
08-30 10:21:56.862  7780  7780 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-30 10:21:56.862  7780  7780 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-30 10:21:56.862  7780  7780 I UEI.SmartControl: ### init IR Blaster...
08-30 10:21:56.867  7780  7780 D serial_port: Configuring serial port
,08-30 10:21:56.871  7780  7780 E UEI.SmartControl: UEIBLaster setting for 616
08-30 10:21:56.872  7780  7780 I UEI.SmartControl: Setting serial record hearder size = 2
08-30 10:21:56.872  7780  7780 I UEI.SmartControl: configuring settings for MAXQ616
08-30 10:21:56.872  7780  7780 I UEI.SmartControl: Get version...
08-30 10:21:56.883  1036  1052 W libprocessgroup: failed to open /acct/uid_10005/pid_7394/cgroup.procs: No such file or directory
,08-30 10:21:56.892  7780  7846 D UEI.SmartControl: serial port data available: 21
08-30 10:21:56.920  7780  7780 D UEI.SmartControl: MAXQ616 A2-X4 software.
,08-30 10:21:56.920  7780  7780 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-30 10:21:56.920  7780  7780 I UEI.SmartControl: QS saving settings...
08-30 10:21:56.922  7780  7780 D UEI.SmartControl: IR Blaster version: 25672567
08-30 10:21:56.938  7780  7846 D UEI.SmartControl: serial port data available: 4
,08-30 10:21:56.972  7780  7850 I UEI.SmartControl: Device manager: loading config....
08-30 10:21:56.973  7780  7850 D UEI.SmartControl: ----------- loading internal config...
08-30 10:21:56.976  7780  7780 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-30 10:21:56.983  7780  7780 E UEI.SmartControl: Services init done
08-30 10:21:56.983  7780  7780 D UEI.SmartControl: QS Service init finished
08-30 10:21:56.984  7780  7780 D UEI.SmartControl: QS Service version name: 2.1.91
08-30 10:21:56.984  7780  7780 D UEI.SmartControl: QS Service version code: 201091
08-30 10:21:56.985  7780  7780 D UEI.SmartControl: Service requested: Control
,08-30 10:21:56.988  7780  7850 E UEI.SmartControl: Loading SETTINGS...
08-30 10:21:56.990  7780  7780 D UEI.SmartControl: Request IControl service: devices are loaded...
08-30 10:21:56.992  7780  7780 D UEI.SmartControl: Service.onUnbind: IControl
,08-30 10:21:56.992  7780  7780 D UEI.SmartControl: Service.onDestroy
08-30 10:21:56.992  7780  7780 D UEI.SmartControl: Lock is in USE false
08-30 10:21:56.992  7780  7780 D UEI.SmartControl: unbind internal service
08-30 10:21:56.994  7780  7780 D serial_port: close(fd = 25)
,08-30 10:21:56.997  7780  7780 I UEI.SmartControl: Serial port is closed.
08-30 10:21:56.998  7780  7780 I UEI.SmartControl: Serial port is closed.
08-30 10:21:56.998  7780  7780 D UEI.SmartControl: Blaster closed
08-30 10:21:56.999  7780  7780 D UEI.SmartControl: Shut down QS...
08-30 10:21:56.999  7780  7780 D UEI.SmartControl: Stopping QS lib
08-30 10:21:56.999  7780  7850 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-30 10:21:57.001  7780  7780 D UEI.SmartControl: QS lib stop result = true
08-30 10:21:57.001  7780  7780 D UEI.SmartControl: Stopped QS lib
08-30 10:21:57.002  7780  7780 D UEI.SmartControl: Stopped file observer...
08-30 10:21:57.002  7780  7780 D UEI.SmartControl: QS shutdown complete
08-30 10:21:57.003  7780  7780 D UEI.SmartControl: QS Service created
08-30 10:21:57.012  7780  7849 I UEI.SmartControl: Notify AllClients services are ready: 11
,08-30 10:21:57.012  7780  7849 D UEI.SmartControl: -----service ready thread exits
08-30 10:21:57.022  7780  7780 I UEI.SmartControl: Service initServices...
08-30 10:21:57.023  7780  7780 D UEI.SmartControl: QS start get config
08-30 10:21:57.104  7829  7829 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,08-30 10:21:57.190  7829  7829 D LgDataFeature: LgDataFeature() Constructor: none
08-30 10:21:57.190  7829  7829 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 10:21:57.254  7829  7829 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,08-30 10:21:57.279  7829  7829 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-30 10:21:57.280  7829  7829 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
08-30 10:21:57.297  7829  7829 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-30 10:21:57.298  7829  7829 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,08-30 10:21:57.317  1036  2002 I ActivityManager: Killing 7110:com.lge.email/u0a23 (adj 15): empty #17
08-30 10:21:57.441  7780  7780 I UEI.SmartControl: Supports setup maps: true
,08-30 10:21:57.446  7780  7780 D UEI.SmartControl: QS start statue = true Error code = 0
,08-30 10:21:57.446  7780  7780 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-30 10:21:57.446  7780  7780 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-30 10:21:57.446  7780  7780 I UEI.SmartControl: ### init IR Blaster...
08-30 10:21:57.450  7780  7780 D serial_port: Configuring serial port
08-30 10:21:57.450  7780  7780 E UEI.SmartControl: UEIBLaster setting for 616
08-30 10:21:57.450  7780  7780 I UEI.SmartControl: Setting serial record hearder size = 2
08-30 10:21:57.450  7780  7780 I UEI.SmartControl: configuring settings for MAXQ616
08-30 10:21:57.450  7780  7780 I UEI.SmartControl: Get version...
08-30 10:21:57.468  1036  1052 W libprocessgroup: failed to open /acct/uid_10023/pid_7110/cgroup.procs: No such file or directory
,08-30 10:21:57.476  7780  7871 D UEI.SmartControl: serial port data available: 21
08-30 10:21:57.483  4652  7873 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
08-30 10:21:57.503  7780  7780 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-30 10:21:57.503  7780  7780 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-30 10:21:57.503  7780  7780 I UEI.SmartControl: QS saving settings...
08-30 10:21:57.504  7780  7780 D UEI.SmartControl: IR Blaster version: 25672567
,08-30 10:21:57.520  7780  7871 D UEI.SmartControl: serial port data available: 4
,08-30 10:21:57.542  1036  2080 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7875 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,08-30 10:21:57.567   348   348 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 463us total 25.065ms
,08-30 10:21:57.569  3486  3501 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
08-30 10:21:57.573  3486  3501 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@312429fc on behalf of 7829
08-30 10:21:57.582  7780  7780 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-30 10:21:57.586  7780  7893 I UEI.SmartControl: Device manager: loading config....
08-30 10:21:57.587  7780  7893 D UEI.SmartControl: ----------- loading internal config...
08-30 10:21:57.589   348   348 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 453us total 21.766ms
08-30 10:21:57.594  7780  7780 E UEI.SmartControl: Services init done
08-30 10:21:57.594  7780  7780 D UEI.SmartControl: QS Service init finished
08-30 10:21:57.595  7780  7780 D UEI.SmartControl: QS Service version name: 2.1.91
08-30 10:21:57.595  7780  7780 D UEI.SmartControl: QS Service version code: 201091
08-30 10:21:57.596  7780  7780 D UEI.SmartControl: Service requested: Control
,08-30 10:21:57.606  7829  7829 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
08-30 10:21:57.611   348   348 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 444us total 20.940ms
08-30 10:21:57.613  7780  7893 E UEI.SmartControl: Loading SETTINGS...
08-30 10:21:57.617  7780  7780 D UEI.SmartControl: Request IControl service: devices are loaded...
,08-30 10:21:57.619  7780  7893 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-30 10:21:57.623  7780  7780 E ActivityThread: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.g@26c733ca that was originally bound here
08-30 10:21:57.623  7780  7780 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.g@26c733ca that was originally bound here
08-30 10:21:57.623  7780  7780 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1167)
08-30 10:21:57.623  7780  7780 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1061)
08-30 10:21:57.623  7780  7780 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1839)
08-30 10:21:57.623  7780  7780 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:1822)
08-30 10:21:57.623  7780  7780 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
08-30 10:21:57.623  7780  7780 E ActivityThread: 	at com.uei.control.Service.b(Unknown Source)
08-30 10:21:57.623  7780  7780 E ActivityThread: 	at com.uei.control.Service.a(Unknown Source)
08-30 10:21:57.623  7780  7780 E ActivityThread: 	at com.uei.control.Service.onCreate(Unknown Source)
08-30 10:21:57.623  7780  7780 E ActivityThread: 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2738)
08-30 10:21:57.623  7780  7780 E ActivityThread: 	at android.app.ActivityThread.access$1800(ActivityThread.java:148)
08-30 10:21:57.623  7780  7780 E ActivityThread: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
08-30 10:21:57.623  7780  7780 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 10:21:57.623  7780  7780 E ActivityThread: 	at android.os.Looper.loop(Looper.java:135)
08-30 10:21:57.623  7780  7780 E ActivityThread: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-30 10:21:57.623  7780  7780 E ActivityThread: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 10:21:57.623  7780  7780 E ActivityThread: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 10:21:57.623  7780  7780 E ActivityThread: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-30 10:21:57.623  7780  7780 E ActivityThread: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-30 10:21:57.624  7780  7780 D UEI.SmartControl: Internal service binding...
08-30 10:21:57.629  7829  7829 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,08-30 10:21:57.629  7780  7892 I UEI.SmartControl: Notify AllClients services are ready: 0
08-30 10:21:57.629  7780  7892 D UEI.SmartControl: -----service ready thread exits
,08-30 10:21:57.632  1036  2022 I ActivityManager: Killing 7019:com.lge.formmanager/u0a26 (adj 15): empty #17
08-30 10:21:57.640  7875  7875 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,08-30 10:21:57.734  1036  2080 W libprocessgroup: failed to open /acct/uid_10026/pid_7019/cgroup.procs: No such file or directory
,08-30 10:21:57.767  7875  7875 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
,08-30 10:21:57.768  7875  7875 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
08-30 10:21:57.768  7875  7875 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
08-30 10:21:57.768  7875  7875 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
08-30 10:21:57.768  7875  7875 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
08-30 10:21:57.768  7875  7875 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
08-30 10:21:57.800  1036  2305 I ActivityManager: Killing 6433:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,08-30 10:21:57.860  1036  1561 W libprocessgroup: failed to open /acct/uid_1000/pid_6433/cgroup.procs: No such file or directory
,08-30 10:21:57.993  7780  7852 D UEI.SmartControl: Internal timer expired: 2
,08-30 10:21:58.149  1036  1952 V SIM_STK : Menu title from STK is T-Mobile
,08-30 10:21:58.179  4652  7873 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 696 ms] updated apps [took 696 ms] 
,08-30 10:21:58.466  1036  1763 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-30 10:21:58.466  1036  1763 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@16a145b7 mBinding = false
,08-30 10:21:58.492  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-30 10:21:58.493  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-30 10:21:58.493  1036  1036 D Ulp_jni : JNI:system_update. Event-4
,08-30 10:21:58.496  1036  1118 D BluetoothManagerService: Message: 2
08-30 10:21:58.497  1036  1118 D BluetoothManagerService: Sending off request.
08-30 10:21:58.497  7002  7665 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-30 10:21:58.498  7002  7561 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-30 10:21:58.498  7002  7561 D BluetoothAdapterProperties: Setting state to 13
08-30 10:21:58.498  7002  7561 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-30 10:21:58.499  7002  7561 D BluetoothAdapterProperties: onBluetoothDisable()
08-30 10:21:58.499  7002  7561 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-30 10:21:58.502  7002  7565 D BluetoothAdapterProperties: Scan Mode:20
08-30 10:21:58.504  7002  7561 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-30 10:21:58.505  7002  7561 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-30 10:21:58.513  7002  7694 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 10:21:58.513  7002  7696 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 10:21:58.514  7002  7684 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 10:21:58.515  7002  7683 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-30 10:21:58.515  7002  7683 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 10:21:58.515  7002  7683 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-30 10:21:58.515  7002  7683 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-30 10:21:58.515  7002  7683 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-30 10:21:58.515  7002  7683 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-30 10:21:58.515  7002  7683 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-30 10:21:58.515  7002  7683 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-30 10:21:58.515  7002  7698 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 10:21:58.516  7002  7617 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-30 10:21:58.516  7002  7617 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-30 10:21:58.524  7002  7617 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 10:21:58.524  7002  7617 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-30 10:21:58.524  7002  7617 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 10:21:58.524  7002  7617 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 10:21:58.524  7002  7617 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 10:21:58.524  7002  7617 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-30 10:21:58.524  7002  7617 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 10:21:58.524  7002  7617 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 10:21:58.524  7002  7617 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 10:21:58.524  7002  7617 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-30 10:21:58.524  7002  7617 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-30 10:21:58.524  7002  7617 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
,08-30 10:21:58.532  1036  1530 D ConnectivityService: Failed to find a new network - expiring NetTransition Wakelock
08-30 10:21:58.534  6615  6615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 10:21:58.534  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 10:21:58.534  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 10:21:58.534  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 10:21:58.534  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 10:21:58.534  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 10:21:58.534  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 10:21:58.534  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 10:21:58.534  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 10:21:58.535  6615  6615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 10:21:58.535  6615  6615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 10:21:58.539  6615  6615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 10:21:58.539  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 10:21:58.539  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 10:21:58.539  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 10:21:58.539  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 10:21:58.539  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 10:21:58.539  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 10:21:58.539  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 10:21:58.539  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 10:21:58.543  6615  6615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 10:21:58.543  6615  6615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 10:21:58.545  6615  6615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 10:21:58.545  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 10:21:58.545  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 10:21:58.545  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 10:21:58.545  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 10:21:58.545  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 10:21:58.545  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 10:21:58.545  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 10:21:58.545  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 10:21:58.546  6615  6615 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 10:21:58.546  6615  6615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 10:21:58.547  1036  1118 D BluetoothManagerService: Message: 60
08-30 10:21:58.547  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-30 10:21:58.547  1036  1118 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-30 10:21:58.550  1955  1955 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-30 10:21:58.553  1586  1586 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-30 10:21:58.567  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 10:21:58.571  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 10:21:58.573  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 10:21:58.575  7002  7002 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-30 10:21:58.575  7002  7002 D BluetoothMapService: STATE_TURNING_OFF
08-30 10:21:58.575  7002  7002 V BluetoothMapService: Handler(): got msg=4
08-30 10:21:58.575  7002  7002 D BluetoothMapService: MAP Service closeService in
08-30 10:21:58.575  7002  7002 D BluetoothMapMasInstance: MAP Service shutdown
08-30 10:21:58.575  7002  7002 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-30 10:21:58.575  7002  7002 V BluetoothMapService: MAP Service closeService out
08-30 10:21:58.576  7002  7002 V BtOppService: Receiver DISABLED_ACTION 
08-30 10:21:58.577  7002  7002 I BtOppRfcommListener: stopping Accept Thread
08-30 10:21:58.577  7002  7002 V BtOppRfcommListener: close mBtServerSocket
08-30 10:21:58.577  7002  7694 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-30 10:21:58.578  7002  7002 V BtOppRfcommListener: waiting for thread to terminate
08-30 10:21:58.578  7002  7002 V BtOppRfcommListener: done waiting for thread to terminate
08-30 10:21:58.580  6890  6890 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
,08-30 10:21:58.590  6890  6890 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-30 10:21:58.592  7002  7002 V BtOppService: onDestroy
,08-30 10:21:58.595  7002  7002 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-30 10:21:58.602  7002  7002 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-30 10:21:58.602  7002  7002 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 10:21:58.602  7002  7002 V BluetoothPbapReceiver: ***********state = 13
08-30 10:21:58.603  7002  7002 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
,08-30 10:21:58.607  7002  7002 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 10:21:58.607  7002  7002 V BluetoothPbapService: state: 13
08-30 10:21:58.607  7002  7002 V BluetoothPbapService: Pbap Service closeService in
08-30 10:21:58.611  2229  2229 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-30 10:21:58.615  7002  7002 V BluetoothPbapService: successfully stopped pbap service
08-30 10:21:58.615  7002  7002 V BluetoothPbapService: Pbap Service closeService out
08-30 10:21:58.616  7002  7002 V BluetoothPbapService: Pbap Service onDestroy
08-30 10:21:58.616  7002  7002 V BluetoothPbapService: Pbap Service closeService in
08-30 10:21:58.616  7002  7002 V BluetoothPbapService: Pbap Service closeService out
08-30 10:21:58.616  7002  7002 D LGBluetoothPbapAdapter: [BTUI] cleanup
,08-30 10:21:58.630  6890  6890 D DockEventReceiver: finishStartingService: stopping service
,08-30 10:21:58.635  6890  6890 D BluetoothPbap: Proxy object disconnected
08-30 10:21:58.635  6890  6890 D PbapServerProfile: Bluetooth service disconnected
08-30 10:21:58.639  6890  6890 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-30 10:21:58.645  6890  6890 D BluetoothPermissionRequest: onReceive
08-30 10:21:58.645  6890  6890 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-30 10:21:58.651  6890  6890 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-30 10:21:58.657  7002  7002 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
,08-30 10:21:58.657  7002  7002 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-30 10:21:58.658  7002  7002 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-30 10:21:58.662  7002  7002 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-30 10:21:58.662  7002  7002 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-30 10:21:58.663  7002  7002 V BluetoothFtpService: Ftp Service onStartCommand
08-30 10:21:58.663  7002  7002 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 10:21:58.663  7002  7002 V BluetoothFtpService: Ftp Service closeService
08-30 10:21:58.664  7002  7002 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-30 10:21:58.667  7002  7002 V BluetoothFtpService: successfully stopped ftp service
08-30 10:21:58.667  7002  7002 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-30 10:21:58.667  7002  7002 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-30 10:21:58.667  7002  7002 V BluetoothSapReceiver: SapReceiver onReceive 
08-30 10:21:58.667  7002  7002 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 10:21:58.667  7002  7002 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-30 10:21:58.667  7002  7002 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-30 10:21:58.668  7002  7002 V BluetoothFtpService: Ftp Service onDestroy
08-30 10:21:58.668  7002  7002 V BluetoothFtpService: Ftp Service closeService
08-30 10:21:58.672  7002  7002 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 10:21:58.672  7002  7002 V BluetoothSapService: state: 13
08-30 10:21:58.672  7002  7002 V BluetoothSapService: Stopping SAP server process
08-30 10:21:58.673  7002  7002 V BluetoothSapService: Sap Service closeSapService in
08-30 10:21:58.673  7002  7002 V BluetoothSapService: Close listen Socket : 
08-30 10:21:58.673  7002  7002 V BluetoothSapService: Close rfcomm Socket : 
08-30 10:21:58.673  7002  7002 V BluetoothSapService: Close sapd  Socket : 
,08-30 10:21:58.674  7002  7002 V BluetoothSapService: Sap Service closeSapService out
,08-30 10:21:58.676  7002  7002 V BluetoothSapService: Sap Service onDestroy
08-30 10:21:58.676  7002  7002 V BluetoothSapService: Sap Service closeSapService in
08-30 10:21:58.676  7002  7002 V BluetoothSapService: Close listen Socket : 
08-30 10:21:58.676  7002  7002 V BluetoothSapService: Close rfcomm Socket : 
08-30 10:21:58.676  7002  7002 V BluetoothSapService: Close sapd  Socket : 
08-30 10:21:58.677  7002  7002 V BluetoothSapService: Sap Service closeSapService out
08-30 10:21:59.139  1036  1364 V AlarmManager: ELAPSED_WAKEUP set : Alarm{2bbfc48d type 2 when 176832 com.google.android.gms} when 176832
,08-30 10:21:59.152   316  7943 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-30 10:21:59.155  1036  1116 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,08-30 10:21:59.434  7002  7565 D bt_hci_bdroid: cleanup
,08-30 10:21:59.440  7002  7619 I bt_lpm  : LPM is already off!!!
08-30 10:21:59.443  7002  7658 I bt_userial_mct: exiting userial_read_thread
08-30 10:21:59.443  7002  7658 D bt_userial_mct: Leaving userial_evt_read_thread()
08-30 10:21:59.444  7002  7617 W bt-btif : ag scb idx 1 not allocated
08-30 10:21:59.444  7002  7617 E bt-btif : BTA AG is already disabled, ignoring ...
08-30 10:21:59.444  7002  7617 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 10:21:59.444  7002  7617 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 10:21:59.444  7002  7617 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-30 10:21:59.444  7002  7617 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 10:21:59.444  7002  7617 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 10:21:59.444  7002  7617 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 10:21:59.444  7002  7617 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 10:21:59.444  7002  7617 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 10:21:59.444  7002  7617 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-30 10:21:59.444  7002  7617 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 10:21:59.444  7002  7617 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 10:21:59.444  7002  7617 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 10:21:59.444  7002  7617 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 10:21:59.444  7002  7617 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 10:21:59.444  7002  7617 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-30 10:21:59.444  7002  7617 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 10:21:59.444  7002  7617 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 10:21:59.444  7002  7617 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 10:21:59.444  7002  7617 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-30 10:21:59.445  7002  7565 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-30 10:21:59.445  7002  7619 I bt_vendor: hw_epilog_process
08-30 10:21:59.446  7002  7565 D bt_hci_bdroid: cleanup Finalizing cleanup
08-30 10:21:59.446  7002  7565 D bt_userial_mct: userial_close
08-30 10:21:59.446  7002  7565 E bt_userial_mct: pthread_join() FAILED result:3
08-30 10:21:59.446  7002  7565 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-30 10:21:59.452  7002  7565 D bt_hci_bdroid: set_power 0
08-30 10:21:59.452  7002  7565 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-30 10:21:59.452  7002  7565 I bt_vendor: bluetooth satus is on
08-30 10:21:59.452  7002  7565 I bt_vendor: bt-vendor : resetting BT status
08-30 10:21:59.452  7002  7565 I bt_vendor: Starting hciattach daemon
08-30 10:21:59.452  7002  7565 I bt_vendor: try to set false
,08-30 10:21:59.458  7002  7565 I bt_vendor: Starting hciattach daemon
08-30 10:21:59.458  7002  7565 I bt_vendor: try to set false
08-30 10:21:59.459  7002  7565 I bt_vendor: cleanup
08-30 10:21:59.459  7002  7617 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-30 10:21:59.460  7002  7565 I GKI_LINUX: GKI_exit_task 0 done
08-30 10:21:59.460  7002  7565 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-30 10:21:59.461  7002  7561 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-30 10:21:59.468  7002  7002 D HeadsetService: Received stop request...Stopping profile...
,08-30 10:21:59.472  7002  7002 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-30 10:21:59.472  7002  7002 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-30 10:21:59.472  7002  7002 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d69116c
08-30 10:21:59.472  7002  7576 D HeadsetStateMachine: Exit Disconnected: -1
08-30 10:21:59.477  1864  1864 D BluetoothHeadset: Proxy object disconnected
08-30 10:21:59.477  1864  1864 D BluetoothHeadset: Proxy object disconnected
08-30 10:21:59.477  1864  1864 D BluetoothHeadset: Proxy object disconnected
08-30 10:21:59.477  7002  7561 D BluetoothAdapterState: Stopping profile services that were post enabled
08-30 10:21:59.478  1036  1036 D BluetoothHeadset: Proxy object disconnected
08-30 10:21:59.478  1036  1036 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-30 10:21:59.479  7002  7002 D A2dpService: Received stop request...Stopping profile...
08-30 10:21:59.479  7002  7605 D A2dpStateMachine: Exit Disconnected: -1
08-30 10:21:59.481  7002  7002 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
,08-30 10:21:59.486  7002  7002 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-30 10:21:59.486  7002  7002 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-30 10:21:59.486  7002  7002 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d69116c
08-30 10:21:59.488  7002  7002 D HidService: Received stop request...Stopping profile...
08-30 10:21:59.488  7002  7002 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d69116c
08-30 10:21:59.489  1036  1036 D BluetoothA2dp: Proxy object disconnected
08-30 10:21:59.489  1036  1036 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-30 10:21:59.491  7002  7002 D HealthService: Received stop request...Stopping profile...
08-30 10:21:59.491  7002  7002 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d69116c
08-30 10:21:59.493  7002  7002 D PanService: Received stop request...Stopping profile...
,08-30 10:21:59.498  7002  7002 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d69116c
08-30 10:21:59.499  7002  7002 D BtGatt.DebugUtils: handleDebugAction() action=null
08-30 10:21:59.501  7002  7002 D BtGatt.GattService: Received stop request...Stopping profile...
08-30 10:21:59.501  7002  7002 D BtGatt.GattService: stop()
08-30 10:21:59.501  7002  7002 D BtGatt.AdvertiseManager: advertise clients cleared
08-30 10:21:59.502  7002  7002 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d69116c
08-30 10:21:59.503  7002  7002 D HeadsetStateMachine: Unbinding service...
08-30 10:21:59.504  7002  7002 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-30 10:21:59.504  7002  7002 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-30 10:21:59.505  7002  7002 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-30 10:21:59.505  7002  7002 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-30 10:21:59.505  7002  7002 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-30 10:21:59.505  7002  7002 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-30 10:21:59.505  7002  7002 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-30 10:21:59.506  7002  7002 D BluetoothMapService: Received stop request...Stopping profile...
08-30 10:21:59.506  7002  7002 D BluetoothMapService: stop()
,08-30 10:21:59.510  7002  7002 D BluetoothMapEmailAppObserver: deinitObservers()
08-30 10:21:59.510  7002  7002 D BluetoothMapEmailAppObserver: removeReceiver()
08-30 10:21:59.511  7002  7002 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d69116c
08-30 10:21:59.513  7002  7002 I BluetoothA2dpServiceJni: cleanupNative
08-30 10:21:59.513  7002  7606 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-30 10:21:59.513  7002  7002 I GKI_LINUX: GKI_exit_task 2 done
08-30 10:21:59.514  7002  7002 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-30 10:21:59.514  7002  7002 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-30 10:21:59.514  7002  7002 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-30 10:21:59.514  7002  7002 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-30 10:21:59.515  7002  7002 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-30 10:21:59.515  7002  7002 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-30 10:21:59.515  7002  7002 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-30 10:21:59.515  7002  7002 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-30 10:21:59.518  7002  7002 V BluetoothMapService: Handler(): got msg=4
08-30 10:21:59.518  7002  7002 D BluetoothMapService: MAP Service closeService in
08-30 10:21:59.518  7002  7002 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-30 10:21:59.518  7002  7002 V BluetoothMapService: MAP Service closeService out
,08-30 10:21:59.523  7002  7561 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-30 10:21:59.523  7002  7561 D BluetoothAdapterProperties: Setting state to 10
08-30 10:21:59.523  7002  7561 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-30 10:21:59.524  7002  7002 D BluetoothMapService: cleanup()
08-30 10:21:59.524  7002  7002 D BluetoothMapService: MAP Service closeService in
08-30 10:21:59.524  7002  7002 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-30 10:21:59.524  7002  7002 V BluetoothMapService: MAP Service closeService out
08-30 10:21:59.525  1036  1118 D BluetoothManagerService: Message: 60
08-30 10:21:59.525  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-30 10:21:59.525  1036  1118 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
08-30 10:21:59.525  1036  1118 D BluetoothA2dp: onBluetoothStateChange: up=false
08-30 10:21:59.526  7002  7561 I BluetoothAdapterState: Entering OffState
08-30 10:21:59.526  1864  1880 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 10:21:59.527  6890  7668 D BluetoothPan: onBluetoothStateChange on: false
08-30 10:21:59.528  6890  7668 D BluetoothA2dp: onBluetoothStateChange: up=false
08-30 10:21:59.528  1864  2551 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 10:21:59.529  6890  7668 D BluetoothPbap: onBluetoothStateChange: up=false
08-30 10:21:59.529  6890  7668 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 10:21:59.533  1864  1879 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-30 10:21:59.537  6890  7668 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-30 10:21:59.538  1036  1118 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 10:21:59.538  6890  7668 D BluetoothMap: onBluetoothStateChange: up=false
08-30 10:21:59.539  1036  1118 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-30 10:21:59.539  1036  1118 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-30 10:21:59.542  1036  1118 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-30 10:21:59.542  1036  1118 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-30 10:21:59.542  1036  1118 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@16a145b7 mBinding = false
08-30 10:21:59.543  1036  1118 D BluetoothManagerService: Sending unbind request.
08-30 10:21:59.547  7002  7565 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-30 10:21:59.550  7002  7002 I GKI_LINUX: GKI_exit_task 1 done
08-30 10:21:59.550  7002  7002 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-30 10:21:59.551  7002  7002 I BluetoothServiceJni: cleanupNative: return from cleanup
08-30 10:21:59.551  7002  7002 I art     : --- WEIRD: removing null entry 248
08-30 10:21:59.551  7002  7002 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
08-30 10:21:59.551  7002  7002 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-30 10:21:59.552  7002  7002 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-30 10:21:59.553  1036  1118 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-30 10:21:59.555  7002  7002 I art     : System.exit called, status: 0
08-30 10:21:59.555  7002  7002 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-30 10:21:59.575   321  1371 V AudioFlinger: 7002 died, releasing its sessions
08-30 10:21:59.575   321  1371 V AudioFlinger:  pid 1864 @ 0
08-30 10:21:59.575   321  1371 V AudioFlinger:  pid 3444 @ 1
08-30 10:21:59.575   321  1371 V AudioFlinger:  pid 3444 @ 2
,08-30 10:21:59.579  1955  1955 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: disconnected from LGBluetoothAPIAdapter
08-30 10:21:59.579  1955  2155 D LGBluetoothAPIService: Message: 101
08-30 10:21:59.579  1955  2155 E LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED
08-30 10:21:59.579  1955  2155 D LGBluetoothAPIService: Calling onBluetoothServiceDown callbacks
08-30 10:21:59.580  1955  2155 D LGBluetoothAPIService: Broadcasting onBluetoothServiceDown() to 0 receivers.
08-30 10:21:59.586  6890  6890 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-30 10:21:59.631  1036  2305 I ActivityManager: Process com.android.bluetooth (pid 7002) has died
08-30 10:21:59.632  1036  2305 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer in 1000ms
08-30 10:21:59.632  1036  2305 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 11000ms
,08-30 10:21:59.641  1955  1955 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-30 10:21:59.641  1955  2155 D LGBluetoothAPIService: Message: 2
08-30 10:21:59.641  1586  1586 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-30 10:21:59.641  1955  2155 D LGBluetoothAPIService: unbindAndFinish(): null mBinding = false
08-30 10:21:59.642  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 10:21:59.643  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 10:21:59.644  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 10:21:59.646  6890  6890 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-30 10:21:59.646  6890  6890 D LGBluetoothEventManager: [BTUI] clear device connection state
08-30 10:21:59.650  6890  6890 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-30 10:21:59.662  1586  1586 D BluetoothAdapter: 855244849: getState() :  mService = null. Returning STATE_OFF
08-30 10:21:59.662  1586  1586 D BluetoothAdapter: 855244849: getState() :  mService = null. Returning STATE_OFF
08-30 10:21:59.711  1036  2002 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=7956 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
08-30 10:21:59.716  6890  6890 D DockEventReceiver: finishStartingService: stopping service
,08-30 10:21:59.794  7956  7956 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-30 10:21:59.794  7956  7956 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-30 10:21:59.795  7956  7956 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-30 10:21:59.796  7956  7956 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-30 10:21:59.818  7956  7956 D BluetoothAdapterApp: Loading JNI Library
,08-30 10:21:59.855  7956  7956 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@13461bd4 Instance Count = 1
,08-30 10:21:59.862  7956  7956 D BluetoothAdapterApp: onCreate
08-30 10:21:59.887  7956  7956 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-30 10:21:59.887  7956  7956 D ProfileConfigQcom: Adding HeadsetService
08-30 10:21:59.888  7956  7956 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-30 10:21:59.888  7956  7956 D ProfileConfigQcom: Adding A2dpService
08-30 10:21:59.888  7956  7956 D ProfileConfigQcom: [BTUI] HidService is supported
08-30 10:21:59.888  7956  7956 D ProfileConfigQcom: Adding HidService
08-30 10:21:59.888  7956  7956 D ProfileConfigQcom: [BTUI] HealthService is supported
08-30 10:21:59.889  7956  7956 D ProfileConfigQcom: Adding HealthService
08-30 10:21:59.889  7956  7956 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
,08-30 10:21:59.890  7956  7956 D ProfileConfigQcom: [BTUI] PanService is supported
08-30 10:21:59.891  7956  7956 D ProfileConfigQcom: Adding PanService
08-30 10:21:59.892  7956  7956 D ProfileConfigQcom: [BTUI] GattService is supported
08-30 10:21:59.892  7956  7956 D ProfileConfigQcom: Adding GattService
08-30 10:21:59.893  7956  7956 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-30 10:21:59.894  7956  7956 D ProfileConfigQcom: Adding BluetoothMapService
08-30 10:21:59.895  7956  7956 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-30 10:21:59.897  7956  7956 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-30 10:21:59.900  7956  7956 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 10:21:59.900  7956  7956 V BluetoothPbapReceiver: ***********state = 10
,08-30 10:21:59.906  7956  7956 V LGMDMManagerInternal: Create singleton instance
,08-30 10:22:00.018  2229  2229 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 10:22:00.027  7956  7956 D LGBluetoothAPIServer: [BTUI] onCreate()
08-30 10:22:00.027  7956  7956 D LGBluetoothAPIServer: [BTUI] onBind()
08-30 10:22:00.033  1955  1955 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
,08-30 10:22:00.035  1955  2155 D LGBluetoothAPIService: Message: 100
08-30 10:22:00.035  1955  2155 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-30 10:22:00.045  6890  6890 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-30 10:22:00.048  6890  6890 D BluetoothPermissionRequest: onReceive
08-30 10:22:00.051  6890  6890 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-30 10:22:00.051  6890  6890 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
,08-30 10:22:00.054  6890  6890 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-30 10:22:00.055  1586  1586 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-30 10:22:00.055  1586  1586 I KeyguardUpdateMonitor: called onTimeUpdated()
08-30 10:22:00.055  1586  1586 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-30 10:22:00.055  1586  1586 I [SystemUI]Clock: called onTimeUpdated()
08-30 10:22:00.057  1586  1586 I LgeClockWidgetControlView: called onTimeUpdated()
08-30 10:22:00.058  1586  1586 I [SystemUI]DateView: called onTimeUpdated()
08-30 10:22:00.058  1586  1586 I [SystemUI]DateView: called onTimeUpdated()
08-30 10:22:00.059  1586  1586 D KeyguardUpdateMonitor: handleTimeUpdate
08-30 10:22:00.064  7956  7956 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
,08-30 10:22:00.071  7956  7956 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-30 10:22:00.080  7956  7956 V BluetoothSapReceiver: [BTUI] checkServiceStart
,08-30 10:22:00.081  7956  7956 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-30 10:22:00.084  7956  7956 V BluetoothSapReceiver: SapReceiver onReceive 
,08-30 10:22:00.086  7956  7956 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 10:22:00.086  7956  7956 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-30 10:22:00.102  7627  7627 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,08-30 10:22:01.348  7780  7791 E UEI.SmartControl: file observer is disposed!
,08-30 10:22:02.582  7780  7894 D UEI.SmartControl: Internal timer expired: 3
,08-30 10:22:02.582  7780  7894 D UEI.SmartControl: unbind internal service
,08-30 10:22:02.604  7780  7780 D UEI.SmartControl: Service.onUnbind: IControl
,08-30 10:22:02.606  7780  7780 D UEI.SmartControl: Service.onDestroy
,08-30 10:22:02.607  7780  7780 D UEI.SmartControl: Lock is in USE false
,08-30 10:22:02.607  7780  7780 D UEI.SmartControl: unbind internal service
,08-30 10:22:02.607  7780  7780 W System.err: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@1d2de3ed
,08-30 10:22:02.607  7780  7780 W System.err: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
,08-30 10:22:02.608  7780  7780 W System.err: 	,at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
,08-30 10:22:02.608  7780  7780 W System.err: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550),
08-30 10:22:02.608  7780  7780 W System.err: 	at com.uei.control.Service.c(Unknown Source)
08-30 10:22:02.608  7780  7780 W System.err: 	at com.uei.control.Service.onDestroy(Unknown Source)
,08-30 10:22:02.608  7780  7780 W System.err: 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
,08-30 10:22:02.608  7780  7780 W System.err: 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
,08-30 10:22:02.608  7780  7780 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386),
08-30 10:22:02.608  7780  7780 W System.err: ,	,at android.os.Handler.dispatchMessage(Handler.java:102)
,08-30 10:22:02.608  7780  7780 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-30 10:22:02.608  7780  7780 W System.err: ,	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-30 10:22:02.608  7780  7780 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 10:22:02.608  7780  7780 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 10:22:02.608  7780  7780 W System.err: ,	,at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-30 10:22:02.608  7780  7780 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-30 10:22:02.608  7780  7780 E UEI.SmartControl: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@1d2de3ed
08-30 10:22:02.610  7780  7780 D serial_port: close(fd = 24)
,08-30 10:22:02.613  7780  7780 I UEI.SmartControl: Serial port is closed.
08-30 10:22:02.613  7780  7780 I UEI.SmartControl: Serial port is closed.,
08-30 10:22:02.613  7780  7780 D UEI.SmartControl: Blaster closed
08-30 10:22:02.613  7780  7780 D UEI.SmartControl: Shut down QS...
08-30 10:22:02.613  7780  7780 D UEI.SmartControl: Stopping QS lib
08-30 10:22:02.614  7780  7780 D UEI.SmartControl: QS lib stop result = true
08-30 10:22:02.614  7780  7780 D UEI.SmartControl: Stopped QS lib,
,08-30 10:22:02.614  7780  7780 D UEI.SmartControl: QS shutdown complete
08-30 10:22:03.574  6615  6733 D io.jxcore.node.ConnectivityMonitor: stop
08-30 10:22:03.574  6615  6733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 10:22:03.608  6615  6733 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-30 10:22:03.608  6615  6733 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@139e47ff removed from the list
08-30 10:22:03.608  6615  6733 D io.jxcore.node.ConnectivityMonitor: stop
08-30 10:22:03.608  6615  6733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 10:22:03.608  6615  6733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
,08-30 10:22:03.613  6615  6733 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 10:22:03.613  6615  6733 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@24750415 added. We now have 4 listener(s)
,08-30 10:22:03.613  6615  6733 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 10:22:03.614  6615  6733 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 10:22:03.614  6615  6733 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@24750415 removed from the list
08-30 10:22:03.614  6615  6733 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 10:22:03.614  6615  6733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 10:22:03.615  6615  6733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 10:22:03.615  6615  6733 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 10:22:03.615  6615  6733 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2a4f532a added. We now have 4 listener(s)
,08-30 10:22:03.615  6615  6733 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 10:22:03.616  1036  1051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 10:22:03.616  1036  1051 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
08-30 10:22:03.617  1036  1118 D BluetoothManagerService: Message: 2
,08-30 10:22:08.624  6615  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 10:22:08.636  1036  2305 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 10:22:08.636  1036  2305 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
08-30 10:22:08.650  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-30 10:22:08.650  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-30 10:22:08.650  1036  1036 D Ulp_jni : JNI:system_update. Event-4
,08-30 10:22:08.654  1036  1118 D BluetoothManagerService: Message: 1
08-30 10:22:08.654  1036  1118 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
,08-30 10:22:08.680  1036  1118 D BluetoothManagerService: Message: 20
08-30 10:22:08.681  1036  1118 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1b9d34af:true
,08-30 10:22:08.684  7956  7956 D BluetoothAdapterState: make
08-30 10:22:08.689  7956  7956 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-30 10:22:08.689  7956  7956 I bluedroid-qcom: init
08-30 10:22:08.690  7956  7986 I BluetoothAdapterState: Entering OffState
08-30 10:22:08.691  7956  7956 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-30 10:22:08.691  7956  7956 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-30 10:22:08.691  7956  7956 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-30 10:22:08.691  7956  7956 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-30 10:22:08.691  7956  7956 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-30 10:22:08.693  7956  7956 I bluedroid-qcom: get_profile_interface socket
08-30 10:22:08.693  7956  7956 I bluedroid-qcom: get_profile_interface map_client
,08-30 10:22:08.698  7956  7990 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-30 10:22:08.700  7956  7990 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-30 10:22:08.701  7989  7989 W bdaddr_loader: type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 10:22:08.701  7989  7989 W bdaddr_loader: type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 10:22:08.709  7989  7989 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-30 10:22:08.709  7989  7989 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-30 10:22:08.709  7989  7989 I LGFTMITEM: [GET_FTM][id=8], offset=16384
,08-30 10:22:08.715  1036  1036 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-30 10:22:08.716  1036  1036 D BluetoothManagerService: Stored Bluetooth name: G3
08-30 10:22:08.717  1036  1036 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-30 10:22:08.717  1036  1118 D BluetoothManagerService: Message: 40
08-30 10:22:08.717  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-30 10:22:08.718  7956  7973 I bluedroid-qcom: config_hci_snoop_log
08-30 10:22:08.719  1036  1118 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-30 10:22:08.719  1036  1118 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-30 10:22:08.720  7989  7989 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-30 10:22:08.723  7956  7990 D BluetoothAdapterProperties: Name is: G3
,08-30 10:22:08.729  7989  7989 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-30 10:22:08.729  7989  7989 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-30 10:22:08.733  7956  7986 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-30 10:22:08.733  7956  7986 D BluetoothAdapterProperties: Setting state to 11
08-30 10:22:08.734  7956  7986 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-30 10:22:08.734  1036  1118 D BluetoothManagerService: Message: 60
08-30 10:22:08.734  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-30 10:22:08.734  1036  1118 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
,08-30 10:22:08.741  1955  1955 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-30 10:22:08.742  1586  1586 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-30 10:22:08.745  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 10:22:08.747  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 10:22:08.753  6890  6890 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-30 10:22:08.758  7956  7956 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-30 10:22:08.758  7956  7956 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 10:22:08.758  7956  7956 V BluetoothPbapReceiver: ***********state = 11
,08-30 10:22:08.763  2229  2229 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-30 10:22:08.781  7956  7986 I LGBluetoothServiceJni: classInitNative: succeeds
,08-30 10:22:08.794  6890  6890 D BluetoothPermissionRequest: onReceive
08-30 10:22:08.797  7956  7986 D BluetoothBondStateMachine: make
08-30 10:22:08.797  6890  6890 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-30 10:22:08.802  7956  8007 I BluetoothBondStateMachine: StableState(): Entering Off State
08-30 10:22:08.802  7956  7986 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1e938335
08-30 10:22:08.803  7956  7986 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-30 10:22:08.803  7956  7986 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1e938335
08-30 10:22:08.803  7956  7986 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-30 10:22:08.805  7956  7986 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-30 10:22:08.807  7956  7956 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-30 10:22:08.811  7956  7956 V BluetoothSapReceiver: [BTUI] checkServiceStart
,08-30 10:22:08.811  7956  7956 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-30 10:22:08.811  7956  7956 V BluetoothSapReceiver: SapReceiver onReceive 
08-30 10:22:08.811  7956  7956 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 10:22:08.811  7956  7956 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-30 10:22:08.813  7956  7986 E BluetoothAdapterService: File transfer profiles supported!!
,08-30 10:22:08.820  7956  7956 D HeadsetService: Received start request. Starting profile...
08-30 10:22:08.820  7956  7956 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-30 10:22:08.820  7956  7956 D LGBluetoothHfpAdapter: Version 1.6
08-30 10:22:08.823  7956  7986 E BluetoothAdapterService: File transfer profiles supported!!
08-30 10:22:08.823  7956  7956 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-30 10:22:08.824  7956  7956 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-30 10:22:08.825  7956  7956 D HeadsetStateMachine: make
,08-30 10:22:08.828  7956  7986 E BluetoothAdapterService: File transfer profiles supported!!
08-30 10:22:08.833  7956  7986 E BluetoothAdapterService: File transfer profiles supported!!
08-30 10:22:08.838  7956  7986 E BluetoothAdapterService: File transfer profiles supported!!
,08-30 10:22:08.842  7956  7986 E BluetoothAdapterService: File transfer profiles supported!!
,08-30 10:22:08.847  7956  7986 E BluetoothAdapterService: File transfer profiles supported!!
08-30 10:22:08.856  7956  7986 V LGMDMManager: Create singleton instance
,08-30 10:22:08.858  7956  7986 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-30 10:22:08.859  7956  7956 D LgDataFeature: LgDataFeature() Constructor: none
08-30 10:22:08.859  7956  7956 D LgDataFeature: LgDataFeature() Constructor Done, null
08-30 10:22:08.863  7956  7956 D HeadsetStateMachine: max_hf_connections = 1
08-30 10:22:08.863  7956  7956 I bluedroid-qcom: get_profile_interface handsfree
08-30 10:22:08.865  7956  7956 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-30 10:22:08.866   321  4055 V AudioPolicyService: registerClient() client 0xb1021b80, uid 1002
08-30 10:22:08.866   321  1371 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-30 10:22:08.866   321  1371 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-30 10:22:08.866   321  1371 V AudioPolicyManagerEx: getOutput() returns output 2
08-30 10:22:08.866  7956  7956 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-30 10:22:08.866   321   321 V AudioFlinger: registerClient() client 0xb5581610, pid 7956
08-30 10:22:08.867   321  1366 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 10:22:08.867   321  1366 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 10:22:08.867  7956  7956 V ToneGenerator: Create Track: 0xb4928a80
08-30 10:22:08.867  7956  7956 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-30 10:22:08.867  7956  7956 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-30 10:22:08.867  1586  1606 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 10:22:08.867  1586  1606 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 10:22:08.867   321  4055 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-30 10:22:08.867   321  4055 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-30 10:22:08.867   321  4055 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
,08-30 10:22:08.867  1864  2551 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 10:22:08.867  1864  2551 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 10:22:08.867   321  4055 V AudioPolicyManagerEx: getOutput() returns output 2
08-30 10:22:08.867   321  1365 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 10:22:08.867   321  1365 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 10:22:08.867  7956  7956 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-30 10:22:08.867  1586  1925 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 10:22:08.868  1586  1925 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 10:22:08.868  3444  3461 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 10:22:08.868  3444  3461 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 10:22:08.868   321  4055 I AudioFlinger: isAudioPlaybackHookOn() false
08-30 10:22:08.868  3444  3461 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 10:22:08.868  3444  3461 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 10:22:08.868   321  4055 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-30 10:22:08.868   321  4055 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-30 10:22:08.868   321  4055 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-30 10:22:08.868   321  4055 V AudioPolicyManagerEx: getOutput() returns output 2
08-30 10:22:08.868  1864  1879 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 10:22:08.868  1864  1879 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 10:22:08.868  7956  7973 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 10:22:08.868  7956  7973 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-30 10:22:08.868  7956  7973 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 10:22:08.868  7956  7973 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-30 10:22:08.868  7956  7956 V AudioSystem: getLatency() output 2, latency 50
08-30 10:22:08.868  7956  7956 V AudioSystem: getFrameCount() output 2, frameCount 960
08-30 10:22:08.868  1036  1561 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 10:22:08.868  7956  7956 V AudioTrack: createTrack_l() output 2 afLatency 50
08-30 10:22:08.868  1036  1561 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 10:22:08.869  1036  1561 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 10:22:08.869  1036  1561 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 10:22:08.869   321  4055 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-30 10:22:08.869   321  4055 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-30 10:22:08.869   321  4055 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-30 10:22:08.869   321  4055 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-30 10:22:08.869   321  4055 V AudioFlinger: createTrack() lSessionId: 23
08-30 10:22:08.870  7956  7956 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-30 10:22:08.870   321  4055 V AudioFlinger: acquiring 23 from 7956, for 7956
08-30 10:22:08.870   321  4055 V AudioFlinger:  added new entry for 23
08-30 10:22:08.870  7956  7956 V ToneGenerator: ToneGenerator INIT OK, time: 186578
08-30 10:22:08.870  7956  7956 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1e938335
,08-30 10:22:08.872  7956  7956 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1e938335
08-30 10:22:08.873  7956  8009 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-30 10:22:08.873  7956  8009 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-30 10:22:08.874  7956  7956 D A2dpService: Received start request. Starting profile...
08-30 10:22:08.874  7956  7956 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-30 10:22:08.875  7956  7956 V Avrcp   : make
08-30 10:22:08.875  7956  7956 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-30 10:22:08.876  7956  7956 I bluedroid-qcom: get_profile_interface avrcp
08-30 10:22:08.876  7956  8009 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-30 10:22:08.876  7956  8009 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-30 10:22:08.877   321   321 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7956
08-30 10:22:08.877   321   321 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-30 10:22:08.877   321   321 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-30 10:22:08.877   321   321 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-30 10:22:08.877   321   321 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-30 10:22:08.877   321   321 V voice   : voice_set_parameters: exit with code(0)
08-30 10:22:08.877   321   321 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-30 10:22:08.877   321   321 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-30 10:22:08.877   321   321 V msm8974_platform: platform_set_parameters: exit with code(0)
08-30 10:22:08.877   321   321 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-30 10:22:08.877   321   321 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-30 10:22:08.877   321   321 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-30 10:22:08.878  7956  8009 V ToneGenerator: ToneGenerator destructor
08-30 10:22:08.878  7956  8009 V ToneGenerator: stopTone
08-30 10:22:08.878  7956  8009 V ToneGenerator: Delete Track: 0xb4928a80
08-30 10:22:08.881  7956  8009 V AudioTrack: ~AudioTrack, releasing session id from 7956 on behalf of 7956
08-30 10:22:08.881   321  4055 V AudioFlinger: releasing 23 from 7956 for 7956
08-30 10:22:08.881   321  4055 V AudioFlinger:  decremented refcount to 0
08-30 10:22:08.881   321  1370 V AudioPolicyService: AudioCommandThread() adding release output 2
08-30 10:22:08.881   321  4055 V AudioFlinger: purging stale effects
08-30 10:22:08.881   321  1370 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-30 10:22:08.881   321  1273 V AudioPolicyService: AudioCommandThread() waking up
08-30 10:22:08.881   321  1273 V AudioPolicyService: AudioCommandThread() processing release output 2
08-30 10:22:08.881   321  1273 V AudioPolicyManager: releaseOutput() 2
08-30 10:22:08.881   321  1273 V AudioPolicyService: AudioCommandThread() going to sleep
08-30 10:22:08.881   321  1370 V AudioFlinger: PlaybackThread::Track destructor
08-30 10:22:08.882   321  1370 V AudioFlinger: removeClient_l() pid 7956, calling pid 321
,08-30 10:22:08.885  7956  7956 V AudioManager: registerRemoteController: size of Media player list: 0
08-30 10:22:08.970  1036  2075 I art     : Explicit concurrent mark sweep GC freed 26458(1267KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 1.440ms total 83.923ms
,08-30 10:22:08.971  7956  7956 E AudioManager: No RCC entry present to update
,08-30 10:22:08.971  7956  7956 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-30 10:22:08.973  7956  7956 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
,08-30 10:22:08.974  7956  7956 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-30 10:22:08.974  7956  7956 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-30 10:22:08.980  7956  7956 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-30 10:22:09.157  1036  1764 V SIM_STK : Menu title from STK is T-Mobile
08-30 10:22:09.157  1036  1764 V SIM_STK : Menu title from STK is T-Mobile
,08-30 10:22:09.298  1036  2080 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-30 10:22:09.318  7956  7956 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
,08-30 10:22:09.324  7956  7956 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
,08-30 10:22:09.325  7956  7956 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
,08-30 10:22:09.325  7956  7956 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-30 10:22:09.325  7956  7956 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-30 10:22:09.325  7956  7956 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-30 10:22:09.326  7956  7956 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-30 10:22:09.326  7956  7956 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
,08-30 10:22:09.326  7956  7956 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-30 10:22:09.326  7956  7956 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-30 10:22:09.326  7956  7956 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-30 10:22:09.326  7956  7956 I BluetoothA2dpServiceJni: classInitNative
08-30 10:22:09.327  7956  7956 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-30 10:22:09.327  7956  7956 D A2dpStateMachine: make
08-30 10:22:09.329  7956  7956 I bluedroid-qcom: get_profile_interface a2dp,
,08-30 10:22:09.329  7956  8021 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,08-30 10:22:09.333  7956  7956 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-30 10:22:09.333  7956  7956 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
,08-30 10:22:09.334  7956  7956 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1e938335
,08-30 10:22:09.336  7956  7956 I BluetoothHidServiceJni: classInitNative: succeeds
,08-30 10:22:09.338  7956  8020 D A2dpStateMachine: Enter Disconnected: -2
08-30 10:22:09.342  7956  7956 D HidService: Received start request. Starting profile...,
,08-30 10:22:09.342  7956  7956 I bluedroid-qcom: get_profile_interface hidhost
08-30 10:22:09.343  7956  7956 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1e938335
,08-30 10:22:09.344  7956  7956 I BluetoothHealthServiceJni: classInitNative: succeeds
08-30 10:22:09.346  7956  7956 D HealthService: Received start request. Starting profile...
08-30 10:22:09.349  7956  7956 I bluedroid-qcom: get_profile_interface health
08-30 10:22:09.349  7956  7956 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-30 10:22:09.350  7956  7956 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1e938335
08-30 10:22:09.351  7956  7956 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-30 10:22:09.354  7956  7956 D PanService: Received start request. Starting profile...
08-30 10:22:09.354  7956  7956 D BluetoothPanServiceJni: initializeNative(L110): pan
08-30 10:22:09.355  7956  7956 I bluedroid-qcom: get_profile_interface pan
,08-30 10:22:09.363  7956  7956 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-30 10:22:09.363  7956  7956 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1e938335
08-30 10:22:09.364  7956  7956 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
,08-30 10:22:09.371  7956  7956 D BtGatt.DebugUtils: handleDebugAction() action=null
08-30 10:22:09.371  7956  7956 D BtGatt.GattService: Received start request. Starting profile...
08-30 10:22:09.371  7956  7956 D BtGatt.GattService: start()
08-30 10:22:09.372  7956  7956 I bluedroid-qcom: get_profile_interface gatt
08-30 10:22:09.372  7956  7956 D BtGatt.AdvertiseManager: advertise manager created
08-30 10:22:09.381  7956  7956 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1e938335
08-30 10:22:09.383  7956  7956 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1e938335
,08-30 10:22:09.384  7956  7956 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-30 10:22:09.385  7956  7956 V BluetoothMapService: BluetoothMapBinder()
08-30 10:22:09.386  7956  7956 D BluetoothMapService: Received start request. Starting profile...
08-30 10:22:09.386  7956  7956 D BluetoothMapService: start()
08-30 10:22:09.389  7956  7956 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-30 10:22:09.389  7956  7956 D BluetoothMapEmailAppObserver: createReceiver()
08-30 10:22:09.391  7956  7956 D BluetoothMapEmailAppObserver: initObservers()
08-30 10:22:09.391  7956  7956 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-30 10:22:09.401  7956  7956 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1e938335
08-30 10:22:09.402  7956  7956 D HeadsetStateMachine: Proxy object connected
08-30 10:22:09.403  7956  7956 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-30 10:22:09.404  7956  7956 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
,08-30 10:22:09.406  7956  8009 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-30 10:22:09.406  7956  8009 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-30 10:22:09.407  7956  8009 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-30 10:22:09.409  7956  7956 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-30 10:22:09.412  7956  7956 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-30 10:22:09.415  7956  7956 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-30 10:22:09.419  7956  7956 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-30 10:22:09.419  7956  7956 V PanService: [BTUI] SIM Extra State :ABSENT
08-30 10:22:09.422  7956  7956 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-30 10:22:09.425  7956  7956 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-30 10:22:09.425  7956  7956 V BluetoothMapService: Handler(): got msg=1
08-30 10:22:09.427  7956  7986 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-30 10:22:09.427  7956  7986 I bluedroid-qcom: enable
08-30 10:22:09.429  7956  7986 I bt_hci_bdroid: init
,08-30 10:22:09.430  7956  8032 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
,08-30 10:22:09.430  7956  8032 I bt-btu  : btu_task pending for preload complete event
08-30 10:22:09.430  7956  7986 I bt_vendor: bt-vendor : init
08-30 10:22:09.430  7956  7986 I bt_vendor: bt-vendor : get_bt_soc_type
08-30 10:22:09.431  7956  7986 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-30 10:22:09.431  7956  7986 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-30 10:22:09.431  7956  7986 D bt_userial_mct: userial_init
08-30 10:22:09.431  7956  7986 D bt_hci_bdroid: set_power 1
08-30 10:22:09.431  7956  7986 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-30 10:22:09.431  7956  7986 I bt_vendor: Starting hciattach daemon
08-30 10:22:09.431  7956  7986 I bt_vendor: try to set true
08-30 10:22:09.430  8036  8036 W sh      : type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 10:22:09.430  8036  8036 W sh      : type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 10:22:09.457  8037  8037 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-30 10:22:09.565  8044  8044 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-30 10:22:09.579  8045  8045 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
08-30 10:22:09.610  8047  8047 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-30 10:22:09.626  8048  8048 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-30 10:22:09.639  8049  8049 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-30 10:22:09.655  8050  8050 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-30 10:22:09.695  8052  8052 I libmdmdetect: ESOC framework not supported
,08-30 10:22:09.696  8052  8052 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-30 10:22:09.705  8052  8052 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
,08-30 10:22:09.705  8052  8052 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
,08-30 10:22:09.705  8052  8052 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-30 10:22:09.705  8052  8052 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-30 10:22:09.705  8052  8052 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-30 10:22:09.705  8052  8052 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-30 10:22:09.705  8052  8052 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-30 10:22:09.743  8052  8053 E QC-QMI  : qmi_client [8052] 15: failed to locate client data
08-30 10:22:09.743   476   476 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-30 10:22:09.743   476   476 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
,08-30 10:22:09.870  8060  8060 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-30 10:22:09.885  8061  8061 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-30 10:22:09.899  7956  7986 I bt_vendor: bluetooth satus is on
08-30 10:22:09.899  7956  7986 D bt_hci_bdroid: preload
,08-30 10:22:09.902  7956  8035 D bt_userial_mct: userial_open(port:0)
08-30 10:22:09.902  7956  8035 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
08-30 10:22:09.908  7956  8035 I bt_vendor: Done intiailizing UART
08-30 10:22:09.909  7956  8035 I bt_vendor: Done intiailizing UART
08-30 10:22:09.909  7956  8035 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-30 10:22:09.910  7956  8035 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-30 10:22:09.910  7956  8032 I bt-btu  : btu_task received preload complete event
08-30 10:22:09.910  7956  8032 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-30 10:22:09.910  7956  8032 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-30 10:22:09.912  7956  8063 D bt_userial_mct: Entering userial_read_thread()
,08-30 10:22:09.916  7956  8032 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-30 10:22:09.919  7956  8032 I         : BTE_InitTraceLevels -- TRC_HCI
08-30 10:22:09.919  7956  8032 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-30 10:22:09.919  7956  8032 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-30 10:22:09.919  7956  8032 I         : BTE_InitTraceLevels -- TRC_AVDT
08-30 10:22:09.919  7956  8032 I         : BTE_InitTraceLevels -- TRC_AVRC
08-30 10:22:09.919  7956  8032 I         : BTE_InitTraceLevels -- TRC_A2D
08-30 10:22:09.919  7956  8032 I         : BTE_InitTraceLevels -- TRC_BNEP
08-30 10:22:09.919  7956  8032 I         : BTE_InitTraceLevels -- TRC_BTM
08-30 10:22:09.919  7956  8032 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-30 10:22:09.920  7956  8032 I         : BTE_InitTraceLevels -- TRC_GAP
08-30 10:22:09.920  7956  8032 I         : BTE_InitTraceLevels -- TRC_PAN
08-30 10:22:09.920  7956  8032 I         : BTE_InitTraceLevels -- TRC_SDP
08-30 10:22:09.920  7956  8032 I         : BTE_InitTraceLevels -- TRC_GATT
08-30 10:22:09.920  7956  8032 I         : BTE_InitTraceLevels -- TRC_SMP
08-30 10:22:09.920  7956  8032 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-30 10:22:09.920  7956  8032 I         : BTE_InitTraceLevels -- TRC_BTIF
08-30 10:22:09.968  7956  8032 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-30 10:22:09.968  7956  8032 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa0245061 
08-30 10:22:09.968  7956  8032 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0245061 
,08-30 10:22:09.995  7956  7990 E bt-btif : Calling BTA_HhEnable
08-30 10:22:09.995  7956  7990 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-30 10:22:09.995  7956  7990 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-30 10:22:09.999  7956  8032 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
,08-30 10:22:09.999  7956  8032 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-30 10:22:10.000  7956  8032 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-30 10:22:10.000  7956  8032 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-30 10:22:10.000  7956  8032 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-30 10:22:10.002  1036  1036 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-30 10:22:10.003  1036  1036 D BluetoothManagerService: Stored Bluetooth name: G3
08-30 10:22:10.003  7956  7990 D BluetoothAdapterProperties: Name is: G3
08-30 10:22:10.005  7956  7990 D BluetoothAdapterProperties: Scan Mode:20
08-30 10:22:10.005  7956  7990 D BluetoothAdapterProperties: Discoverable Timeout:120
08-30 10:22:10.006  7956  7990 D bt_hci_bdroid: postload
08-30 10:22:10.006  7956  8035 D bt_hci_bdroid: Used up Tx Cmd credits
08-30 10:22:10.007  7956  8032 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-30 10:22:10.008  7956  7990 D bte_conf: Device ID record 1 : primary
08-30 10:22:10.008  7956  7990 D bte_conf:   vendorId            = 00c4
08-30 10:22:10.008  7956  7990 D bte_conf:   vendorIdSource      = 0001
,08-30 10:22:10.008  7956  7990 D bte_conf:   product             = 13a1
08-30 10:22:10.008  7956  7990 D bte_conf:   version             = 1000
,08-30 10:22:10.008  7956  7990 D bte_conf:   clientExecutableURL = 
08-30 10:22:10.008  7956  7990 D bte_conf:   serviceDescription  = 
08-30 10:22:10.008  7956  7990 D bte_conf:   documentationURL    = 
08-30 10:22:10.008  7956  7990 D bte_conf: bte_load_did_conf no section named DID2.,
,08-30 10:22:10.016  7956  8035 D bt_hci_bdroid: Used up Tx Cmd credits
08-30 10:22:10.023  7956  8035 D bt_hci_bdroid: Used up Tx Cmd credits
08-30 10:22:10.020  8065  8065 W sh      : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-30 10:22:10.028  7956  8035 D bt_hci_bdroid: Used up Tx Cmd credits
08-30 10:22:10.028  7956  7986 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-30 10:22:10.028  7956  7986 D BluetoothAdapterProperties: ScanMode =  20
08-30 10:22:10.029  7956  7986 D BluetoothAdapterProperties: State =  11
08-30 10:22:10.029  7956  7986 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-30 10:22:10.029  7956  7986 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-30 10:22:10.029  7956  7986 D BluetoothAdapterProperties: Setting state to 12
08-30 10:22:10.029  7956  7986 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-30 10:22:10.030  7956  7990 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-30 10:22:10.030  7956  7990 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-30 10:22:10.030  8065  8065 W sh      : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 10:22:10.042  1036  1118 D BluetoothManagerService: Message: 60
08-30 10:22:10.042  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-30 10:22:10.042  1036  1118 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
08-30 10:22:10.042  1036  1118 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-30 10:22:10.047  7956  8063 E bt_mct  : hci lib postload completed
08-30 10:22:10.049  7956  7986 I BluetoothAdapterState: Entering On State
08-30 10:22:10.057  7956  8032 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
,08-30 10:22:10.059  7956  8032 W bt-smp  : Plain text(LSB ~ MSB) = 36 16 66 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-30 10:22:10.059  7956  8032 W bt-smp  : Encrypted text(LSB ~ MSB) = ff 37 8c c2 37 59 9c 07 ca 99 84 0c 54 f4 80 34 
08-30 10:22:10.060  7956  8032 W bt-btm  : Stopping oneshot timer
08-30 10:22:10.072  7956  7990 D BluetoothAdapterProperties: Discoverable Timeout:120
08-30 10:22:10.073  7956  7990 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
,08-30 10:22:10.080  1864  1879 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 10:22:10.090  7956  8032 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-30 10:22:10.090  7956  8032 W bt-smp  : Plain text(LSB ~ MSB) = f0 b2 4b 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-30 10:22:10.090  7956  8032 W bt-smp  : Encrypted text(LSB ~ MSB) = cf 7d 3d c1 88 11 ea 33 aa 16 7b 1c e0 b5 15 5c 
,08-30 10:22:10.093  7956  8032 W bt-btm  : Stopping oneshot timer
08-30 10:22:10.102  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 10:22:10.102  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 10:22:10.102  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 10:22:10.102  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 10:22:10.102  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 10:22:10.102  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 10:22:10.102  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 10:22:10.102  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 10:22:10.108  7956  8032 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-30 10:22:10.108  7956  8032 W bt-smp  : Plain text(LSB ~ MSB) = 11 48 54 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-30 10:22:10.108  7956  8032 W bt-smp  : Encrypted text(LSB ~ MSB) = e8 82 7a 3d 83 9e 3b 44 65 f6 85 59 41 37 3d 22 
08-30 10:22:10.108  7956  8032 W bt-btm  : Stopping oneshot timer
08-30 10:22:10.112  6615  6615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 10:22:10.122  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 10:22:10.122  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 10:22:10.122  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 10:22:10.122  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 10:22:10.122  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 10:22:10.122  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 10:22:10.122  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 10:22:10.122  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 10:22:10.126  7956  8032 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-30 10:22:10.126  7956  8032 W bt-smp  : Plain text(LSB ~ MSB) = 15 c1 5b 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-30 10:22:10.126  7956  8032 W bt-smp  : Encrypted text(LSB ~ MSB) = 9c 56 b4 a2 5e 24 44 be c7 2e 98 d8 43 84 b3 bb 
08-30 10:22:10.127  7956  8032 W bt-btm  : Stopping oneshot timer
08-30 10:22:10.130  6615  6615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 10:22:10.141  7956  7986 D LGBluetoothServiceAdapter: [BTUI] OnState
08-30 10:22:10.141  7956  7986 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-30 10:22:10.141  7956  7986 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
,08-30 10:22:10.145  7956  7986 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-30 10:22:10.145  7956  7986 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-30 10:22:10.147  1036  1036 D BluetoothA2dp: Proxy object connected
08-30 10:22:10.158  7956  8032 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-30 10:22:10.158  7956  8032 W bt-smp  : Plain text(LSB ~ MSB) = c7 07 79 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-30 10:22:10.158  7956  8032 W bt-smp  : Encrypted text(LSB ~ MSB) = 2f 2f 94 c3 c1 68 07 ef 94 67 f3 a0 50 58 07 4b 
,08-30 10:22:10.160  7956  8032 W bt-btm  : Stopping oneshot timer
,08-30 10:22:10.162  1864  1864 D BluetoothHeadset: Proxy object connected
,08-30 10:22:10.163  6890  6909 D BluetoothPan: onBluetoothStateChange on: true
08-30 10:22:10.163  6890  6909 D BluetoothPan: onBluetoothStateChange call bindService
08-30 10:22:10.165  8071  8071 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-30 10:22:10.176  6890  6911 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-30 10:22:10.185  6890  6890 D BluetoothPan: BluetoothPAN Proxy object connected
08-30 10:22:10.186  6890  6890 D PanProfile: Bluetooth service connected
08-30 10:22:10.189  6890  6890 D BluetoothA2dp: Proxy object connected
08-30 10:22:10.189  6890  6890 D A2dpProfile: Bluetooth service connected
08-30 10:22:10.190  1864  1880 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 10:22:10.193  1864  1864 D BluetoothHeadset: Proxy object connected
08-30 10:22:10.193  6890  6909 D BluetoothPbap: onBluetoothStateChange: up=true
,08-30 10:22:10.195  6890  7668 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 10:22:10.196  6890  6890 D BluetoothHeadset: Proxy object connected
08-30 10:22:10.196  1864  1879 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 10:22:10.196  6890  6890 D HeadsetProfile: Bluetooth service connected
08-30 10:22:10.198  1864  1864 D BluetoothHeadset: Proxy object connected
08-30 10:22:10.198  6890  6909 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-30 10:22:10.200  6890  6890 D BluetoothInputDevice: Proxy object connected
08-30 10:22:10.200  6890  6890 D HidProfile: Bluetooth service connected
08-30 10:22:10.200  1036  1118 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 10:22:10.200  1036  1036 D BluetoothHeadset: Proxy object connected
08-30 10:22:10.201  6890  6911 D BluetoothMap: onBluetoothStateChange: up=true
08-30 10:22:10.203  6890  6890 D BluetoothMap: Proxy object connected
08-30 10:22:10.203  6890  6890 D MapProfile: Bluetooth service connected
08-30 10:22:10.203  6890  6890 D BluetoothMap: getConnectedDevices()
08-30 10:22:10.203  1036  1118 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-30 10:22:10.203  1036  1118 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-30 10:22:10.205  1586  1586 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,08-30 10:22:10.208  1955  1955 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-30 10:22:10.208  1955  2155 D LGBluetoothAPIService: Message: 1
08-30 10:22:10.208  1955  2155 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-30 10:22:10.208  1955  2155 D LGBluetoothAPIService: Calling onBluetoothServiceUp callbacks
08-30 10:22:10.208  1955  2155 D LGBluetoothAPIService: Broadcasting onBluetoothServiceUp() to 0 receivers.
08-30 10:22:10.209  1036  1036 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-30 10:22:10.209  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 10:22:10.211  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 10:22:10.211  1036  1118 D BluetoothManagerService: Message: 40
08-30 10:22:10.211  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-30 10:22:10.212  7956  7973 V BluetoothMapService: getConnectedDevices()
08-30 10:22:10.212  7956  7956 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-30 10:22:10.212  7956  7956 D BluetoothMapService: STATE_ON
08-30 10:22:10.212  7956  7956 V BluetoothMapService: Handler(): got msg=1
08-30 10:22:10.213  7956  7956 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-30 10:22:10.214  7956  8087 D BluetoothMapMasInstance: MAS initSocket()
08-30 10:22:10.214  7956  8087 D BluetoothMapMasInstance:   masId = 00
08-30 10:22:10.214  7956  8087 D BluetoothMapMasInstance:   msgTypes = 0e
08-30 10:22:10.214  7956  8087 D BluetoothMapMasInstance:   masName = SMS/MMS
08-30 10:22:10.214  7956  8087 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-30 10:22:10.215  1036  2307 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 10:22:10.217  7956  8087 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 10:22:10.220  7956  8087 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-30 10:22:10.220  7956  8087 V BluetoothMapMasInstance: Succeed to create listening socket 
08-30 10:22:10.220  7956  8087 D BluetoothMapMasInstance: Accepting socket connection...
,08-30 10:22:10.221  7956  7990 D BluetoothAdapterProperties: Scan Mode:21
08-30 10:22:10.221  7956  7990 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-30 10:22:10.222  6890  6890 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-30 10:22:10.223  7956  7956 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1e938335
08-30 10:22:10.223  7956  7956 V BluetoothPbapService: Pbap Service onCreate
08-30 10:22:10.223  7956  7956 V BluetoothPbapService: Starting PBAP service
08-30 10:22:10.223  6890  6890 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-30 10:22:10.224  7956  7956 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-30 10:22:10.224  7956  7956 V BluetoothPbapService: Pbap Service onBind
08-30 10:22:10.227  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 10:22:10.229  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 10:22:10.231  7956  7956 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 10:22:10.231  7956  7956 V BluetoothPbapService: state: 12
08-30 10:22:10.231  7956  7956 V BluetoothPbapService: Handler(): got msg=1
08-30 10:22:10.232  7956  7956 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-30 10:22:10.233  7956  7956 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-30 10:22:10.233  7956  7956 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 10:22:10.233  7956  7956 V BluetoothPbapReceiver: ***********state = 12
08-30 10:22:10.235  6890  6890 D DockEventReceiver: finishStartingService: stopping service
08-30 10:22:10.235  7956  8089 V BluetoothPbapService: Pbap Service initSocket
,08-30 10:22:10.236  6890  6890 D BluetoothPbap: Proxy object connected
08-30 10:22:10.236  6890  6890 D PbapServerProfile: Bluetooth service connected
08-30 10:22:10.236  1036  2075 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 10:22:10.236  2229  2229 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-30 10:22:10.237  2229  2229 D c       : Getting all permits...
08-30 10:22:10.237  2229  2229 D a       : Opening database...
08-30 10:22:10.238  7956  8089 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 10:22:10.239  7956  8089 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-30 10:22:10.240  7956  8089 V BluetoothPbapService: Succeed to create listening socket 
08-30 10:22:10.240  7956  8089 V BluetoothPbapService: Accepting socket connection...
08-30 10:22:10.241  2229  2229 D a       : Opening database auth.proximity.permit_store...
08-30 10:22:10.242  2229  2229 D a       : Closing database...
08-30 10:22:10.250  6890  6890 D BluetoothPermissionRequest: onReceive
,08-30 10:22:10.252  6890  6890 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-30 10:22:10.253  6890  6890 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-30 10:22:10.256  7956  7956 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-30 10:22:10.257  7956  7956 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-30 10:22:10.260  7956  7956 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
08-30 10:22:10.284  7956  7956 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,08-30 10:22:10.284  7956  7956 V BtOppService: onCreate
08-30 10:22:10.288  7956  7956 V BluetoothOppNotification: send message
08-30 10:22:10.290  7956  7956 V BtOppService: Starting RfcommListener
08-30 10:22:10.298  7956  7956 D BluetoothOppPreference: Dumping Names:  
08-30 10:22:10.298  7956  7956 D BluetoothOppPreference: {}
08-30 10:22:10.298  7956  7956 D BluetoothOppPreference: Dumping Channels:  
08-30 10:22:10.298  7956  7956 D BluetoothOppPreference: {}
,08-30 10:22:10.299  7956  8095 V BtOppService: Deleted complete outbound shares, number =  0
08-30 10:22:10.299  7956  7956 V BtOppService: onStartCommand
08-30 10:22:10.300  7956  8098 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
,08-30 10:22:10.300  7956  8095 V BtOppService: Deleted complete inbound failed shares, number = 0
08-30 10:22:10.301  7956  8095 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-30 10:22:10.301  7956  8098 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-30 10:22:10.303  7956  7956 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-30 10:22:10.303  7956  7956 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-30 10:22:10.303  7956  8098 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2a937801 on behalf of 
08-30 10:22:10.304  7956  8098 V BluetoothOppNotification: update too frequent, put in queue
08-30 10:22:10.305  7956  8098 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
,08-30 10:22:10.305  7956  8098 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-30 10:22:10.305  7956  8095 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@212096a6 on behalf of 
08-30 10:22:10.306  7956  7956 V BluetoothOppNotification: new notify threadi!
08-30 10:22:10.307  7956  8098 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@332ae8e7 on behalf of 
08-30 10:22:10.307  7956  7956 V BluetoothOppNotification: send delay message
08-30 10:22:10.307  7956  8098 V BluetoothOppNotification: update too frequent, put in queue
08-30 10:22:10.307  7956  7956 V BtOppService: start RfcommListener
08-30 10:22:10.308  7956  8098 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-30 10:22:10.308  7956  8099 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-30 10:22:10.309  7956  8099 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@25e5bc94 on behalf of 
08-30 10:22:10.310  7956  8099 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-30 10:22:10.311  7956  7956 V BtOppService: RfcommListener started
08-30 10:22:10.311  7956  8099 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-30 10:22:10.311  7956  7956 V BtOppService: ContentObserver received notification
08-30 10:22:10.312  7956  8100 V BtOppRfcommListener: Starting RFCOMM listener....
,08-30 10:22:10.312  7956  7956 V BtOppService: ContentObserver received notification
08-30 10:22:10.313  7956  8101 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-30 10:22:10.313  7956  8101 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-30 10:22:10.315  1036  1051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 10:22:10.316  7956  8100 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 10:22:10.317  7956  8100 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=78 mFd=75
08-30 10:22:10.317  7956  8101 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@10be933d on behalf of 
08-30 10:22:10.317  7956  8099 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@102f7732 on behalf of 
08-30 10:22:10.317  7956  8100 V BtOppRfcommListener: Started RFCOMM listener....
08-30 10:22:10.317  7956  8100 I BtOppRfcommListener: Accept thread started.
08-30 10:22:10.318  7956  8100 V BtOppRfcommListener: Accepting connection...
08-30 10:22:10.318  7956  8099 V BluetoothOppNotification: outbound: succ-0  fail-0
08-30 10:22:10.319  7956  8101 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-30 10:22:10.320  7956  8099 V BluetoothOppNotification: outbound notification was removed.
08-30 10:22:10.320  7956  8099 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-30 10:22:10.321  7956  8099 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3d332c83 on behalf of 
08-30 10:22:10.321  7956  8099 V BluetoothOppNotification: inbound: succ-0  fail-0
08-30 10:22:10.323  7956  8099 V BluetoothOppNotification: inbound notification was removed.
08-30 10:22:10.323  7956  8099 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-30 10:22:10.324  7956  8099 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@16ac0e00 on behalf of 
,08-30 10:22:10.331  7956  7956 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1e938335
08-30 10:22:10.331  7956  7956 V BluetoothFtpService: Ftp Service onCreate
08-30 10:22:10.331  7956  7956 I BluetoothFtpService: Ftp Service onCreate
08-30 10:22:10.332  7956  7956 V BluetoothFtpService: Ftp Service onStartCommand
08-30 10:22:10.332  7956  7956 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 10:22:10.332  7956  7956 V BluetoothFtpService: Starting Listening on sockets
08-30 10:22:10.332  7956  7956 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-30 10:22:10.332  7956  7956 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-30 10:22:10.332  7956  7956 V BluetoothSapReceiver: SapReceiver onReceive 
,08-30 10:22:10.332  7956  7956 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 10:22:10.333  7956  7956 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-30 10:22:10.333  7956  7956 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-30 10:22:10.335  7956  7956 V BluetoothFtpService: Handler(): got msg=1
,08-30 10:22:10.336  7956  7956 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-30 10:22:10.336  7956  7956 V BluetoothFtpService: Ftp Service initSocket
08-30 10:22:10.339  1036  2307 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 10:22:10.340  7956  7956 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 10:22:10.341  7956  7956 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=78
08-30 10:22:10.342  7956  7956 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-30 10:22:10.345  7956  8102 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-30 10:22:10.361  7956  7956 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1e938335
,08-30 10:22:10.361  7956  7956 V BluetoothSapService: Sap Service onCreate
08-30 10:22:10.364  7956  7956 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 10:22:10.364  7956  7956 V BluetoothSapService: state: 12
08-30 10:22:10.364  7956  7956 V BluetoothSapService: Starting SAP server process
08-30 10:22:10.360  8103  8103 W sapd    : type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 10:22:10.360  8103  8103 W sapd    : type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 10:22:10.370  7956  7956 V BluetoothSapService: SAP Service startRfcommListenerThread
08-30 10:22:10.372  7956  8104 V BluetoothSapService: Sap Service initRfcommSocket
08-30 10:22:10.373  1036  2075 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 10:22:10.374  7956  8104 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 10:22:10.375  7956  8104 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
,08-30 10:22:10.377  7956  8104 V BluetoothSapService: Succeed to create listening socket 
08-30 10:22:10.377  7956  8104 V BluetoothSapService: Accepting socket connection...
,08-30 10:22:10.388  8103  8103 V BT_SAP  : Event pipe created
,08-30 10:22:10.388  8103  8103 V BT_SAP  : create_server_socket qcom.sap.server
,08-30 10:22:10.388  8103  8103 V BT_SAP  : created socket fd 6
08-30 10:22:11.309  7956  7956 V BluetoothOppNotification: new notify threadi!
,08-30 10:22:11.310  7956  7956 V BluetoothOppNotification: send delay message
,08-30 10:22:11.326  7956  8114 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-30 10:22:11.330  7956  8114 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2699ecf5 on behalf of 
08-30 10:22:11.335  7956  8114 V BluetoothOppNotification: mUpdateCompleteNotification = true
,08-30 10:22:11.339  7956  8114 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-30 10:22:11.340  7956  8114 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@103aba8a on behalf of 
08-30 10:22:11.340  7956  8114 V BluetoothOppNotification: outbound: succ-0  fail-0
08-30 10:22:11.342  7956  8114 V BluetoothOppNotification: outbound notification was removed.
08-30 10:22:11.342  7956  8114 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-30 10:22:11.343  7956  8114 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1e93a8fb on behalf of 
08-30 10:22:11.344  7956  8114 V BluetoothOppNotification: inbound: succ-0  fail-0
08-30 10:22:11.347  7956  8114 V BluetoothOppNotification: inbound notification was removed.
08-30 10:22:11.347  7956  8114 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
,08-30 10:22:11.350  7956  8114 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2f7d9d18 on behalf of 
,08-30 10:22:13.678  6615  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 10:22:13.678  6615  6733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 10:22:13.678  6615  6733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 10:22:13.678  6615  6733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 10:22:13.678  6615  6733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 10:22:13.678  6615  6733 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 10:22:13.678  6615  6733 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 10:22:13.678  6615  6733 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 10:22:13.687  6615  6733 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 10:22:13.688  6615  6733 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 10:22:13.688  6615  6733 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2a4f532a removed from the list
,08-30 10:22:13.688  6615  6733 D io.jxcore.node.ConnectivityMonitor: stop
08-30 10:22:13.688  6615  6733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 10:22:13.688  6615  6733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 10:22:13.689  6615  6733 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 10:22:13.689  6615  6733 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2b99651b added. We now have 4 listener(s)
08-30 10:22:13.689  6615  6733 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 10:22:13.691  1036  1561 D WifiServiceImplEx: setWifiEnabled: false pid=6615, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-30 10:22:13.692  1036  1561 D WifiService: setWifiEnabled: false pid=6615, uid=10118
08-30 10:22:13.692  1036  1561 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 10:22:17.623  1036  1364 D PowerManagerServiceEx: acquireWakeLockInternal: lock=179175549, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1036
,08-30 10:22:17.640  1036  1364 V AlarmManager: ELAPSED_WAKEUP set : Alarm{1e448580 type 2 when 191286 com.google.android.gms} when 191286
08-30 10:22:17.654   316  8117 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,08-30 10:22:17.658  1036  1116 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,08-30 10:22:17.700  2632  2632 D [Concierge]Service: onStartCommand(). Type : 9
,08-30 10:22:17.730  1036  1036 D PowerManagerServiceEx: releaseWakeLockInternal: lock=179175549 [*alarm*], flags=0x0
,08-30 10:22:18.700  6615  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 10:22:18.712  1036  1952 D WifiServiceImplEx: setWifiEnabled: true pid=6615, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-30 10:22:18.713  1036  1952 D WifiService: setWifiEnabled: true pid=6615, uid=10118
08-30 10:22:18.713  1036  1952 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-30 10:22:18.729  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-30 10:22:18.729  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-30 10:22:18.729  1036  1036 D Ulp_jni : JNI:system_update. Event-4
,08-30 10:22:18.733  1036  1523 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-30 10:22:18.733  1036  1523 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-30 10:22:18.736  1036  1523 E WifiUtil: wfc_util_ffile_check_copy(): pid[1036] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-30 10:22:18.736  1036  1523 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-30 10:22:18.736  1036  1523 E WifiUtil: wfc_util_ffile_check_copy(): pid[1036] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-30 10:22:18.736  1036  1523 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-30 10:22:18.736  1036  1523 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-30 10:22:18.736  1036  1523 E WifiHW  : unknown target_country: EU , set to default
08-30 10:22:18.736  1036  1523 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-30 10:22:18.736  1036  1523 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-30 10:22:18.736  1036  1523 I WifiUtil: gEnableBmps=1
,08-30 10:22:19.318   316   894 D SoftapController: Softap fwReload - Ok
,08-30 10:22:19.329  1036  1523 E NetdConnector: NDC Command {84 softap fwreload wlan0 STA} took too long (590ms)
08-30 10:22:19.331   316   894 D CommandListener: Setting iface cfg
08-30 10:22:19.331   316   894 D CommandListener: Trying to bring down wlan0
,08-30 10:22:19.337   316   894 D CommandListener: Clearing all IP addresses on wlan0
08-30 10:22:19.341  1036  1118 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-30 10:22:19.343  1036  1118 D Tethering: InitialState.processMessage what=4
08-30 10:22:19.344  1036  1118 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-30 10:22:19.354  1036  1523 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,08-30 10:22:19.373  1036  1523 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-30 10:22:19.373  1036  1523 E WifiStateMachine: useWiFiOffloading() : false
08-30 10:22:19.373  1036  1523 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-30 10:22:19.376  6890  6890 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-30 10:22:19.376  6890  6890 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-30 10:22:19.376  6890  6890 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-30 10:22:19.376  6890  6890 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-30 10:22:19.378  1036  1523 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-30 10:22:19.378  1036  1523 D WifiMonitor: connecting to supplicant
08-30 10:22:19.378  1036  1523 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
08-30 10:22:19.380  8144  8144 W wpa_supplicant: type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-30 10:22:19.380  8144  8144 W wpa_supplicant: type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-30 10:22:19.405   311   311 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x6 conn_h=0xb6403090
08-30 10:22:19.405   311   311 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
08-30 10:22:19.405   311   311 I rmt_storage: wakelock acquired: 1, error no: 42
08-30 10:22:19.406   311   914 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1236806912)
08-30 10:22:19.422  1955  1955 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
,08-30 10:22:19.426  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 10:22:19.433  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
,08-30 10:22:19.449  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 10:22:19.453  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 10:22:19.466  6890  6890 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,08-30 10:22:19.479  6890  6890 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-30 10:22:19.480  6890  6890 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-30 10:22:19.480  6890  6890 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-30 10:22:19.480  6890  6890 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-30 10:22:19.480  6890  6890 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-30 10:22:19.480  6890  6890 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-30 10:22:19.481  6890  6890 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,08-30 10:22:19.487  8144  8144 I wpa_supplicant: Successfully initialized wpa_supplicant
08-30 10:22:19.493  6890  6890 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-30 10:22:19.494  6890  6890 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-30 10:22:19.494  6890  6890 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-30 10:22:19.494  6890  6890 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-30 10:22:19.497  6890  6890 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-30 10:22:19.498  6890  6890 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-30 10:22:19.499  6890  6890 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-30 10:22:19.499  6890  6890 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-30 10:22:19.499  6890  6890 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-30 10:22:19.499  6890  6890 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-30 10:22:19.499  6890  6890 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,08-30 10:22:19.530   311   914 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 1572864
08-30 10:22:19.530   311   914 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
08-30 10:22:19.530   311   914 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1236806912) wakelock released: 1, error no: 0
08-30 10:22:19.530   311   914 I rmt_storage: 
,08-30 10:22:19.532  8144  8144 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-30 10:22:19.532  8144  8144 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
08-30 10:22:19.532   311   311 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x0x6 conn_h=0x0xb6403090
08-30 10:22:19.533   900   912 E Diag_Lib: [IMS_FATAL]| 3347 | 912 |ims-rtp-daemon ims_rtp_qmi_handler_thread_func waiting on select thread>
,08-30 10:22:19.550  1036  1763 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=8162 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-30 10:22:19.594  8144  8144 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-30 10:22:19.638  1036  1763 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=8184 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-30 10:22:19.643  8162  8182 W FormManager: Network not available. Please check & try again.
08-30 10:22:19.643  8144  8144 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
08-30 10:22:19.647  8162  8183 V FormManager: Network unavailable.
08-30 10:22:19.650  8162  8183 V FormManager: Network unavailable.
08-30 10:22:19.654  8144  8144 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
,08-30 10:22:19.663  1036  1561 I ActivityManager: Killing 7140:com.google.android.setupwizard/u0a46 (adj 15): empty #17
08-30 10:22:19.702  1036  2305 W libprocessgroup: failed to open /acct/uid_10046/pid_7140/cgroup.procs: No such file or directory
,08-30 10:22:19.771  8184  8184 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-30 10:22:19.778  6890  6890 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-30 10:22:19.791  6890  6890 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-30 10:22:19.793  1036  1561 I ActivityManager: Killing 7159:com.android.chrome/u0a57 (adj 15): empty #17
08-30 10:22:19.844  1036  2022 W libprocessgroup: failed to open /acct/uid_10057/pid_7159/cgroup.procs: No such file or directory
,08-30 10:22:20.317  8144  8144 E wpa_supplicant: USIM:  scard_init function
,08-30 10:22:20.325  8144  8144 I wpa_supplicant: Trying to associate with SSID 'NG700'
,08-30 10:22:20.383  1036  1523 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-30 10:22:20.384  1036  1523 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-30 10:22:20.384  1036  1523 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-30 10:22:20.385  1036  1523 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-30 10:22:20.386  1036  1523 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-30 10:22:20.386  1036  1523 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-30 10:22:20.387  1036  1523 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-30 10:22:20.387  1036  1523 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-30 10:22:20.388  1036  1523 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-30 10:22:20.388  1036  1523 D WifiNative-wlan0: doString: [DRIVER MACADDR]
,08-30 10:22:20.398  1036  1523 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-30 10:22:20.398  1036  1523 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-30 10:22:20.398  1036  1523 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-30 10:22:20.401  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 10:22:20.402  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 10:22:20.402  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 10:22:20.403  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 10:22:20.403  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-30 10:22:20.404  1036  1523 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-30 10:22:20.404  1036  1523 E WifiStateMachine: useWiFiOffloading() : false
08-30 10:22:20.404  1036  1523 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-30 10:22:20.414  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 10:22:20.410  1955  1955 D WfdService: Waiting for WifiP2p enabling
,08-30 10:22:20.420  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 10:22:20.420  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 10:22:20.420  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 10:22:20.420  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 10:22:20.420  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 10:22:20.420  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 10:22:20.420  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 10:22:20.420  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 10:22:20.422  6615  6615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 10:22:20.428  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 10:22:20.428  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 10:22:20.428  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 10:22:20.428  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 10:22:20.428  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 10:22:20.428  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 10:22:20.428  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 10:22:20.428  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 10:22:20.431  6615  6615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 10:22:20.443  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
,08-30 10:22:20.446  1036  1528 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-30 10:22:20.446  1036  1523 D WifiNative-wlan0: doBoolean: SET update_config 1
08-30 10:22:20.447  1036  1523 D WifiNative-wlan0: SET update_config 1: returned true
08-30 10:22:20.447  1036  1523 D WifiConfigStore: Loading config and enabling all networks 
08-30 10:22:20.447  1036  1523 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-30 10:22:20.448  1036  1523 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	[CURRENT]
08-30 10:22:20.457  8144  8144 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-30 10:22:20.468  1036  1118 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-30 10:22:20.464  1036  8213 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-30 10:22:20.469  8144  8144 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-30 10:22:20.469  8144  8144 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,08-30 10:22:20.477  1036  8213 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-30 10:22:20.477  1036  8213 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-30 10:22:20.477  1036  8213 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-30 10:22:20.477  1036  8213 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 10:22:20.477  1036  8213 E WifiMonitor: WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-30 10:22:20.478  1036  8213 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 10:22:20.478  1036  8213 E WifiMonitor: WifiMonitor:wlan0 cnt=47 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-30 10:22:20.478  1036  8213 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-30 10:22:20.482  1036  8213 E WifiMonitor: WifiMonitor:wlan0 cnt=48 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-30 10:22:20.482  1036  8213 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-30 10:22:20.482  1036  8213 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-30 10:22:20.482  1036  8213 E WifiMonitor: WifiMonitor:wlan0 cnt=49 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-30 10:22:20.482  1036  8213 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-30 10:22:20.482  1036  8213 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 10:22:20.482  1036  8213 E WifiMonitor: WifiMonitor:wlan0 cnt=50 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,08-30 10:22:20.491  1036  1523 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-30 10:22:20.499  1036  1523 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-30 10:22:20.499  1036  1523 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-30 10:22:20.505  1036  1523 D WifiStateMachine: enableVerboseLogging : level 2
08-30 10:22:20.505  1036  1523 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
,08-30 10:22:20.508  1036  1523 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-30 10:22:20.508  1036  1523 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-30 10:22:20.509  1036  1523 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-30 10:22:20.509  1036  1523 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-30 10:22:20.509  1036  1523 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-30 10:22:20.509  1036  1523 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-30 10:22:20.510  1036  1523 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-30 10:22:20.510  1036  1523 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-30 10:22:20.510  1036  1523 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-30 10:22:20.510  1036  1523 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-30 10:22:20.511  1036  1523 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-30 10:22:20.511  1036  1523 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-30 10:22:20.511  1036  1523 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-30 10:22:20.513  1036  1523 D WifiStateMachine: Setting OUI to DA-A1-19
08-30 10:22:20.513  1036  1523 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-30 10:22:20.514  1036  1523 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-30 10:22:20.514  1036  1523 D WifiNative-HAL: Setting external_sim to 1
08-30 10:22:20.514  1036  1523 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-30 10:22:20.514  1036  1523 D WifiNative-wlan0: SET external_sim 1: returned true
08-30 10:22:20.514  1036  1523 I WifiNative-HAL: startHal
08-30 10:22:20.514  1036  1523 D wifi    : setting scan oui 0xaf6b9760
08-30 10:22:20.515  1036  1523 D WifiStateMachine: Setting OUI to DA-A1-19
08-30 10:22:20.515  1036  1523 I WifiNative-HAL: startHal
,08-30 10:22:20.515  1036  1523 D wifi    : setting scan oui 0xaf6b9760,
,08-30 10:22:20.515  1036  1523 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1,
08-30 10:22:20.516  1036  1523 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-30 10:22:20.516  1036  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-30 10:22:20.516  8144  8144 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-30 10:22:20.517  1036  1523 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-30 10:22:20.517  1036  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-30 10:22:20.517  8144  8144 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-30 10:22:20.517  1036  1523 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-30 10:22:20.517  1036  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-30 10:22:20.518  8144  8144 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
,08-30 10:22:20.530  1955  1955 D WfdsService: Supplicant Connection state is changed : true
,08-30 10:22:20.532  1955  2317 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-30 10:22:20.532  1955  2317 D WfdsService: Set the WFDS Monitor: true
08-30 10:22:20.532  1955  2317 D WfdsMonitor: WfdsMonitorThread create
08-30 10:22:20.534  1955  2317 D WfdsMonitor: WFDS Monitor is created and started
08-30 10:22:20.534  1955  2317 D WfdsService: WiFi: Supplicant connection re-established
08-30 10:22:20.536  1036  1523 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-30 10:22:20.536  1036  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-30 10:22:20.536  8144  8144 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-30 10:22:20.536  1036  1523 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-30 10:22:20.537  1036  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-30 10:22:20.537  8144  8144 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-30 10:22:20.537  1036  1523 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-30 10:22:20.537  1036  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-30 10:22:20.537  8144  8144 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-30 10:22:20.538  1955  8228 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-30 10:22:20.538  1036  1523 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-30 10:22:20.538  1036  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-30 10:22:20.539  8144  8144 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-30 10:22:20.539  1955  8228 E CtrlSupplicant: Succeed to open control connection
08-30 10:22:20.539  1955  8228 E CtrlSupplicant: Succeed to open monitor connection
08-30 10:22:20.541  1036  1523 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-30 10:22:20.542  1955  8228 D WfdsMonitor: Supplicant connection established
08-30 10:22:20.542  1036  1523 E WifiNative: : [198,237,762 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-30 10:22:20.542  1036  1523 D WifiNative-wlan0: doBoolean: RECONNECT
08-30 10:22:20.543  7708  7708 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 10:22:20.543  1955  2317 D WfdsService: Connected to the supplicant for wfds
08-30 10:22:20.548  8184  8184 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-30 10:22:20.548  1036  1523 D WifiNative-wlan0: RECONNECT: returned true
08-30 10:22:20.549  1036  1523 D WifiNative-wlan0: doString: [STATUS]
08-30 10:22:20.550  1036  8213 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 10:22:20.550  1036  8213 E WifiMonitor: WifiMonitor:wlan0 cnt=51 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-30 10:22:20.550  1036  1523 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-30 10:22:20.550  1036  1523 D WifiNative-wlan0: doBoolean: SET ps 1
08-30 10:22:20.551  1036  1523 D WifiNative-wlan0: SET ps 1: returned true
08-30 10:22:20.552  1036  1522 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
,08-30 10:22:20.558  6890  6890 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-30 10:22:20.559   316   894 D CommandListener: Setting iface cfg
08-30 10:22:20.559   316   894 D CommandListener: Trying to bring up p2p0
08-30 10:22:20.560  1036  1522 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-30 10:22:20.560  1036  1522 D LGWifiP2pService: P2pEnablingState
08-30 10:22:20.560  1036  1522 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-30 10:22:20.560  1036  1522 D LGWifiP2pService: P2p socket connection successful
08-30 10:22:20.560  1036  1522 D LGWifiP2pService: P2pEnabledState
08-30 10:22:20.563  1036  1522 D LGWifiP2pService: sending p2p connection changed broadcast
,08-30 10:22:20.564  1036  1522 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-30 10:22:20.565  1036  1522 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-30 10:22:20.565  1036  1522 D WifiNative-p2p0: doBoolean: SET device_name G3
08-30 10:22:20.566  1036  1522 D WifiNative-p2p0: SET device_name G3: returned true
08-30 10:22:20.566  1036  1522 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-30 10:22:20.567  1036  1522 D LGWifiP2pService: before postfix = G3
08-30 10:22:20.567  1036  1522 D WifiServerServiceExt: postfix byte check : 2
08-30 10:22:20.567  1036  1522 D LGWifiP2pService: after postfix = G3
08-30 10:22:20.567  1036  1522 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-30 10:22:20.567  1036  1036 D WifiScanningService: SCAN_AVAILABLE : 3
08-30 10:22:20.568  1036  1036 D RttService: SCAN_AVAILABLE : 3
08-30 10:22:20.568  1955  1955 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-30 10:22:20.568  1955  1955 D WfdsService: WifiP2pState is changed : true
08-30 10:22:20.568  1955  1955 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-30 10:22:20.569  1955  1955 D WfdsService: isConnected: false
08-30 10:22:20.569  1036  1522 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-30 10:22:20.569  1955  2317 D WfdsService: Receive the WFDS_ENABLE Method
08-30 10:22:20.569  1036  1542 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-30 10:22:20.569  1955  2317 D WfdsService: Set the WFDS Monitor: true
08-30 10:22:20.569  1036  1522 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-30 10:22:20.569  1036  1542 I WifiNative-HAL: startHal
08-30 10:22:20.569  1955  2317 D WfdsService: Connected to the supplicant for wfds
08-30 10:22:20.569  1955  2317 D WfdsJNI : doCommand: WFDS_SET TRUE
08-30 10:22:20.569  8144  8144 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-30 10:22:20.569  1036  1543 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-30 10:22:20.569  1955  2317 D WfdsService: selectPreferredScanChannel [36]
08-30 10:22:20.569  1955  2317 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-30 10:22:20.571  1036  1522 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-30 10:22:20.571  1036  1522 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-30 10:22:20.572  1036  1523 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-30 10:22:20.573  1036  1523 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-30 10:22:20.573  1036  1523 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-30 10:22:20.573  1036  1523 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-30 10:22:20.574  1036  1522 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-30 10:22:20.574  1036  1523 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-30 10:22:20.574  1036  1542 D wifi    : getting scan capabilities on interface[1] = 0xaf6b9760
08-30 10:22:20.574  1036  1542 D wifi    : failed to get capabilities : -3
08-30 10:22:20.574  1036  1542 E WifiScanningService: could not get scan capabilities
08-30 10:22:20.574  1036  1522 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-30 10:22:20.574  1036  1523 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-30 10:22:20.574  1036  1522 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-30 10:22:20.574  1036  1522 D WifiNative-HAL: p2pGetDeviceAddress
08-30 10:22:20.575  1036  1523 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-30 10:22:20.575  1036  1522 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-30 10:22:20.575  1036  1523 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-30 10:22:20.575  8144  8144 E wpa_supplicant: nWIFIDua,lbandAPConnection: 1
08-30 10:22:20.575  1036  1523 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-30 10:22:20.576  1036  1523 E WifiStateMachine:  ConnectModeState what:132096 -100 0
,08-30 10:22:20.576  1036  1523 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-30 10:22:20.576  1036  1523 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-30 10:22:20.576  8144  8144 E wpa_supplicant: disconnect_rssi_lvl: -100
,08-30 10:22:20.577  1036  1523 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
08-30 10:22:20.577  1036  1523 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-30 10:22:20.578  1036  1523 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-30 10:22:20.578  1036  1523 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-30 10:22:20.579  1036  1523 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-30 10:22:20.579  1036  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=198275  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-30 10:22:20.581  1955  1955 I WfdStateTracker: handleP2pThisDeviceChanged
08-30 10:22:20.581  1955  1955 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-30 10:22:20.581  1955  1955 D WfdsService: Update P2p Interface State: 3
08-30 10:22:20.581  1036  1522 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-30 10:22:20.581  1036  1522 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-30 10:22:20.582  1036  1522 D WifiNative-p2p0: P2P_FLUSH: returned true
,08-30 10:22:20.582  1036  1522 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-30 10:22:20.582  1036  1522 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-30 10:22:20.583  1036  1522 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-30 10:22:20.583  1036  1522 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-30 10:22:20.583  1036  1522 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-30 10:22:20.584  1036  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=198279  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-30 10:22:20.584  1036  1523 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 45 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=198280
08-30 10:22:20.585  1036  1523 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 45 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=198281
08-30 10:22:20.585  1036  1523 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 45 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=198281
08-30 10:22:20.586  1036  1523 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 45 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=198281
08-30 10:22:20.586  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 10:22:20.586  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 10:22:20.586  1036  1523 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 45 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=198282
08-30 10:22:20.587  1036  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=198282  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-30 10:22:20.587  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 10:22:20.587  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 10:22:20.587  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-30 10:22:20.588  1036  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=198284  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-30 10:22:20.588  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 10:22:20.589  1036  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 47 0 rt=198284  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-30 10:22:20.589  1036  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 47 0 rt=198285  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-30 10:22:20.590  1036  1523 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=198286
08-30 10:22:20.590  1036  1523 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=198286
08-30 10:22:20.591  1036  1523 D WifiNative-wlan0: doString: [STATUS]
08-30 10:22:20.592  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 10:22:20.592  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 10:22:20.592  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
,08-30 10:22:20.594  1036  1522 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-30 10:22:20.594  1036  1522 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-30 10:22:20.594  1036  8213 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 10:22:20.594  1036  8213 E WifiMonitor: WifiMonitor:wlan0 cnt=52 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-30 10:22:20.595  1036  1523 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-30 10:22:20.596  1036  1523 I WifiServiceExtension: setVHTCapabilityType  : false
08-30 10:22:20.596  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 10:22:20.596  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 10:22:20.597  1036  1522 D LGWifiP2pService: InactiveState
08-30 10:22:20.597  1036  1522 D LGWifiP2pService: InactiveState{ when=-15ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-30 10:22:20.597  1036  1522 D LGWifiP2pService: P2pEnabledState{ when=-15ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-30 10:22:20.597  1036  1522 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-30 10:22:20.598  8144  8144 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-30 10:22:20.598  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 10:22:20.599  8144  8144 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
,08-30 10:22:20.599  8144  8144 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-30 10:22:20.599  8144  8144 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 10:22:20.600  1036  8213 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-30 10:22:20.600  1036  8213 E WifiMonitor: WifiMonitor:p2p0 cnt=53 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 10:22:20.600  1036  8213 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 10:22:20.600  8144  8144 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 10:22:20.600  1036  8213 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 10:22:20.600  1036  8213 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 10:22:20.600  1036  8213 E WifiMonitor: WifiMonitor:p2p0 cnt=54 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 10:22:20.600  1036  8213 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 10:22:20.600  1036  8213 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 10:22:20.600  1036  8213 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 10:22:20.600  1036  8213 E WifiMonitor: WifiMonitor:p2p0 cnt=55 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 10:22:20.601  1036  8213 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 10:22:20.601  1036  8213 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 10:22:20.602  1955  8228 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-30 10:22:20.602  1955  8228 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 10:22:20.602  1955  8228 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 10:22:20.602  1036  1522 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-30 10:22:20.602  1036  1522 D LGWifiP2pService: InactiveState{ when=-4ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-30 10:22:20.602  1036  1522 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-30 10:22:20.602  1036  1522 D LGWifiP2pService: DefaultState{ when=-4ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-30 10:22:20.602  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 10:22:20.602  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 10:22:20.602  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-30 10:22:20.603  1036  1522 D LGWifiP2pService: InactiveState{ when=-5ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-30 10:22:20.603  1036  1522 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-30 10:22:20.603  1036  1522 D LGWifiP2pService: DefaultState{ when=-5ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-30 10:22:20.603  1036  1522 D LGWifiP2pService: InactiveState{ when=-5ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-30 10:22:20.603  1036  1522 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-30 10:22:20.603  1036  1522 D LGWifiP2pService: DefaultState{ when=-5ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-30 10:22:20.603  1036  1522 D LGWifiP2pService: Inact,iveState{ when=-5ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-30 10:22:20.603  1955  2317 W WfdsService: DefaultState - msg [9441285] is not handled
08-30 10:22:20.603  1036  1522 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-30 10:22:20.603  1036  1522 D LGWifiP2pService: DefaultState{ when=-5ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-30 10:22:20.603  1036  1523 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-30 10:22:20.603  1036  1523 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
08-30 10:22:20.604  1036  1036 E WifiServerServiceExt: No p2p device connected
08-30 10:22:20.604  8162  8231 W FormManager: Network not available. Please check & try again.
08-30 10:22:20.604  8162  8232 V FormManager: Network unavailable.
08-30 10:22:20.606  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 10:22:20.606  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 10:22:20.606  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,08-30 10:22:20.609  8162  8232 V FormManager: Network unavailable.
08-30 10:22:20.610  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 10:22:20.610  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 10:22:20.610  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-30 10:22:20.612  6890  6890 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 10:22:20.614  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 10:22:20.614  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 10:22:20.615  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 10:22:20.617  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 10:22:20.617  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 10:22:20.617  1036  1523 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-30 10:22:20.617  1036  1530 D ConnectivityService: Got NetworkAgent Messenger
08-30 10:22:20.617  1036  1530 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-30 10:22:20.617  1036  1530 D ConnectivityService: NetworkAgent connected
08-30 10:22:20.617  1036  1523 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-30 10:22:20.617  1036  1523 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-30 10:22:20.617  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 10:22:20.619  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 10:22:20.619  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 10:22:20.619  1036  1523 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-30 10:22:20.619  1036  1523 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
,08-30 10:22:20.622  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 10:22:20.624  1036  1523 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-30 10:22:20.624  1036  1523 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-30 10:22:20.624  1036  1523 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-30 10:22:20.624  1036  1523 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-30 10:22:20.624  1036  1523 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-30 10:22:20.626  6890  6890 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-30 10:22:20.626  6890  6890 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-30 10:22:20.626  6890  6890 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-30 10:22:20.626  6890  6890 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-30 10:22:20.627  6890  6890 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-30 10:22:20.627  1036  1523 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-30 10:22:20.628   316   894 D CommandListener: Setting iface cfg
08-30 10:22:20.629  6890  6890 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-30 10:22:20.630  6890  6890 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-30 10:22:20.630  6890  6890 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-30 10:22:20.630  6890  6890 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-30 10:22:20.630  6890  6890 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-30 10:22:20.630  6890  6890 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-30 10:22:20.630  6890  6890 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-30 10:22:20.633  4383  4383 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-30 10:22:20.634  1036  1523 E WifiStateMachine: Start Dhcp Watchdog 3
08-30 10:22:20.634  1036  8237 D DhcpStateMachine: StoppedState
08-30 10:22:20.634  1036  8237 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-30 10:22:20.634  4383  4383 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-30 10:22:20.634  1036  8237 D DhcpStateMachine: WaitBeforeStartState
08-30 10:22:20.634  1036  1523 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 50 0 rt=198330  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 10:22:20.635  1036  1523 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 50 0 rt=198330  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 10:22:20.635  1036  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 50 0 rt=198331  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 10:22:20.635  4383  4383 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 10:22:20.636  1036  1523 E WifiStateMachine:  ObtainingIpState CMD_SET_COUNTRY_CODE 3 0 cz
08-30 10:22:20.636  1036  1523 E WifiStateMachine:  L2ConnectedState CMD_SET_COUNTRY_CODE 3 0 cz
08-30 10:22:20.636  1036  1523 E WifiStateMachine:  ObtainingIpState CMD_SET_FREQUENCY_BAND 0 0
08-30 10:22:20.636  1036  1523 E WifiStateMachine:  L2ConnectedState CMD_SET_FREQUENCY_BAND 0 0
08-30 10:22:20.636  1036  1523 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-30 10:22:20.637  1036  1523 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0, 0
08-30 10:22:20.637  1036  1523 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-30 10:22:20.637  8144  8144 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-30 10:22:20.637  8144  8144 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
,08-30 10:22:20.637  1036  8213 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-30 10:22:20.637  1036  8213 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-30 10:22:20.637  1036  8213 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-30 10:22:20.637  1036  8213 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-30 10:22:20.638  1036  1523 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-30 10:22:20.638  1036  1523 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-30 10:22:20.639  1036  1523 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-30 10:22:20.639  1036  1523 D WifiNative-wlan0: doBoolean: SCAN
08-30 10:22:20.639  4383  4383 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 10:22:20.639  8144  8144 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-30 10:22:20.640  1036  1523 D WifiNative-wlan0: SCAN: returned true
08-30 10:22:20.640  1036  8213 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-30 10:22:20.640  1036  8213 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-30 10:22:20.640  1036  8213 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-30 10:22:20.640  1036  8213 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-30 10:22:20.641  1036  1523 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 51 0 rt=198336  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 10:22:20.641  1036  1523 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 51 0 rt=198337  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 10:22:20.642  1036  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 51 0 rt=198337  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 10:22:20.642  1036  1523 E WifiStateMachine:  ObtainingIpState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 10:22:20.642  1036  1523 E WifiStateMachine:  L2ConnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 10:22:20.643  1036  1523 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 10:22:20.643  1036  1523 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 10:22:20.643  1036  1523 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 10:22:20.643  1036  1523 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 10:22:20.645  4383  8238 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-30 10:22:20.647  4383  8239 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-30 10:22:20.647  4383  8239 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-30 10:22:20.689  1036  2054 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=8240 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-30 10:22:20.694  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 10:22:20.694  1036  1036 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-30 10:22:20.695  1036  1523 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 52 0 rt=198391  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 10:22:20.696  1036  1523 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 52 0 rt=198391  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 10:22:20.696  1036  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 52 0 rt=198392  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 10:22:20.697  1036  1523 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:29486] from screen [on:0 period:-628441831] gl rssi=-42 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-30 10:22:20.698  1036  1523 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-628441830] gl rssi=-42 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-30 10:22:20.698  1036  1523 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-30 10:22:20.699  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 10:22:20.699  1036  1036 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
,08-30 10:22:20.777  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-30 10:22:20.779  1036  1530 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,08-30 10:22:20.780  1036  1523 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 10:22:20.781  1036  1523 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 10:22:20.783  1036  1523 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
,08-30 10:22:20.784  1036  1523 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 10:22:20.785  1036  1523 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 10:22:20.786  1036  1523 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 10:22:20.787  1036  1530 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-30 10:22:20.788  1036  1523 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=150,0,0
,08-30 10:22:20.789  1036  1523 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=150,0,0
08-30 10:22:20.789  1036  1523 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-30 10:22:20.790  8144  8144 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-30 10:22:20.791  1036  1523 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-30 10:22:20.791  1036  1523 D WifiNative-wlan0: doBoolean: SET ps 0
08-30 10:22:20.792  1036  1523 D WifiNative-wlan0: SET ps 0: returned true
08-30 10:22:20.792  1036  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-30 10:22:20.792  8144  8144 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-30 10:22:20.793  1036  8213 E WifiMonitor: WifiMonitor:wlan0 cnt=58 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-30 10:22:20.793  1036  8213 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-30 10:22:20.794  1036  8213 E WifiMonitor: WifiMonitor:p2p0 cnt=59 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-30 10:22:20.794  1955  8228 D WfdsMonitor: Event [CTRL-EVENT-SCAN-RESULTS ]
08-30 10:22:20.794  1036  8213 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-30 10:22:20.794  1955  8228 D WfdsMonitor: Event [WPS-AP-AVAILABLE ]
08-30 10:22:20.795  1036  8213 D WifiMonitor: Event [IFNAME=p2p0 WPS-AP-AVAILABLE ]
08-30 10:22:20.795  1036  8213 E WifiMonitor: WifiMonitor:p2p0 cnt=60 dispatchEvent: WPS-AP-AVAILABLE 
08-30 10:22:20.795  1036  1523 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-30 10:22:20.795  1036  1523 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-30 10:22:20.795  1036  1523 V DhcpStateMachine: Current State is mWaitBeforeStartState.
,08-30 10:22:20.795  1036  8213 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-30 10:22:20.795  1036  1523 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-30 10:22:20.795  1036  1522 D LGWifiP2pService: InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
08-30 10:22:20.795  1036  1522 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
08-30 10:22:20.796  1036  1522 D LGWifiP2pService: DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
08-30 10:22:20.796   316   894 D CommandListener: Setting iface cfg
08-30 10:22:20.796  1036  1522 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@22cf8a36 target=com.android.internal.util.StateMachine$SmHandler }
08-30 10:22:20.796  1036  1522 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@22cf8a36 target=com.android.internal.util.StateMachine$SmHandler }
08-30 10:22:20.796   316   894 D CommandListener: Trying to bring up wlan0
08-30 10:22:20.797  1036  8237 D DhcpStateMachine: WaitBeforeStartState{ when=-1ms what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-30 10:22:20.797  1036  8237 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-30 10:22:20.797  1036  1523 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-30 10:22:20.798  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 10:22:20.798  1036  1036 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-30 10:22:20.799  1036  1523 E WifiStateMachine:  ObtainingIpState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-30 10:22:20.799  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 10:22:20.799  1036  1036 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-30 10:22:20.800  1036  1523 E WifiStateMachine:  L2ConnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-30 10:22:20.800  1036  1523 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-30 10:22:20.801  1036  1523 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-30 10:22:20.801  1036  1523 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-30 10:22:20.801  1036  1523 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-30 10:22:20.807  1036  1523 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 10:22:20.807  1036  1523 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 10:22:20.808  1036  1523 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 10:22:20.808  1036  1523 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 10:22:20.809  1036  1523 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 10:22:20.809  1036  1523 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 10:22:20.809  8240  8240 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-30 10:22:20.809  1036  1530 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-30 10:22:20.810  8240  8240 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
08-30 10:22:20.810  1036  1523 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-30 10:22:20.810  1036  1523 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-30 10:22:20.811  1036  1522 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 10:22:20.811  103,6  1522 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 10:22:20.811  1036  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-30 10:22:20.811  8144  8144 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-30 10:22:20.812  1036  1523 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-30 10:22:20.812  1036  1523 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-30 10:22:20.812  8144  8144 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-30 10:22:20.813  1036  1523 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-30 10:22:20.813  1036  1523 D WifiNative-wlan0: doBoolean: SET ps 1
08-30 10:22:20.818  8240  8240 V [BNRBootReceiver]: Boot Receiver Return
08-30 10:22:20.819  8240  8240 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-30 10:22:20.829  1036  1523 D WifiNative-wlan0: SET ps 1: returned true
08-30 10:22:20.829  1036  1530 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-30 10:22:20.829  1036  1523 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-30 10:22:20.830  1036  1523 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-30 10:22:20.830  1036  1523 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-30 10:22:20.830  1036  1530 D ConnectivityService: ignoring duplicate network state non-change
08-30 10:22:20.864  1036  2075 I ActivityManager: Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=8258 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-30 10:22:20.866  1036  2075 I ActivityManager: Killing 7177:com.lge.drmservice/u0a62 (adj 15): empty #17
,08-30 10:22:20.914  1036  2002 W libprocessgroup: failed to open /acct/uid_10062/pid_7177/cgroup.procs: No such file or directory
,08-30 10:22:20.923  1036  1530 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-30 10:22:20.924  1036  1530 D ConnectivityService: Adding iface wlan0 to network 102
08-30 10:22:20.926  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 10:22:20.926  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-30 10:22:20.928  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 10:22:20.932  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 10:22:20.932  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 10:22:20.932  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-30 10:22:20.934  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 10:22:20.935  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 10:22:20.935  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-30 10:22:20.940  1036  1523 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-30 10:22:20.946  1955  1955 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-30 10:22:20.948  1036  1036 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-30 10:22:20.948  8258  8258 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-30 10:22:20.948  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 10:22:20.948  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 10:22:20.948  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-30 10:22:20.949  1036  1036 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
,08-30 10:22:20.952  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 10:22:20.952  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 10:22:20.952  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-30 10:22:20.958  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 10:22:20.958  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 10:22:20.960  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 10:22:20.963  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-30 10:22:20.963  1586  1586 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-30 10:22:20.964  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 10:22:20.967  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 10:22:20.967  1586  1586 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-30 10:22:20.968  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 10:22:20.973  1036  1530 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-30 10:22:20.973  1036  1530 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,08-30 10:22:20.974  1036  1530 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
08-30 10:22:20.975   316   894 E Netd    : netlink response contains error (File exists)
08-30 10:22:20.975  1036  1523 E WifiStateMachine:  ConnectedState CMD_SET_COUNTRY_CODE 3 0 cz
08-30 10:22:20.975  1036  1530 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
08-30 10:22:20.975  1036  1523 E WifiStateMachine:  L2ConnectedState CMD_SET_COUNTRY_CODE 3 0 cz
08-30 10:22:20.976  1036  1530 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-30 10:22:20.976  1036  1530 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 102
08-30 10:22:20.976  1036  1530 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
08-30 10:22:20.977  1036  1530 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-30 10:22:20.978  1036  1530 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-30 10:22:20.978  1036  1530 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-30 10:22:20.978  1036  1530 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-30 10:22:20.978  1036  1530 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 10:22:20.978  1036  1530 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 10:22:20.978  1036  1530 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-30 10:22:20.978  1036  1530 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-30 10:22:20.978  1036  1530 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-30 10:22:20.978  1036  1530 D ConnectivityService: currentScore = 0, newScore = 20
08-30 10:22:20.978  1036  1530 D ConnectivityService:    accepting network in place of null
08-30 10:22:20.978  1036  8236 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-30 10:22:20.978  1036  8236 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-30 10:22:20.978  1036  1530 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 10:22:20.978  1036  8236 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-30 10:22:20.979  1036  8236 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-30 10:22:20.979  1036  1523 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 10:22:20.979  1036  1523 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 10:22:20.980  1864  1864 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 10:22:20.980  1864  1864 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-30 10:22:20.982  1036  1530 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-30 10:22:20.982  1036  1530 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
08-30 10:22:20.982  1036  1530 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-30 10:22:20.985  8258  8258 D PluginManager: init()
08-30 10:22:20.986   316  8278 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-30 10:22:20.987  1036  1530 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-30 10:22:20.987  1036  1530 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-30 10:22:20.988  1036  1530 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBan,dwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-30 10:22:20.990  1036  1036 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-30 10:22:20.990  1036  1530 D ConnectivityService: validation of new default Network = false
08-30 10:22:20.990  1036  1530 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-30 10:22:20.990  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-30 10:22:20.990  1036  1530 D DSQN    : enableDataServiceNotify 
08-30 10:22:20.990  1036  1530 D DSQN    : start dsqn bin
08-30 10:22:20.990  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-30 10:22:20.990  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
,08-30 10:22:20.990  8279  8279 W dsqn    : type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 10:22:20.990  8279  8279 W dsqn    : type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 10:22:20.997  1036  1530 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-30 10:22:20.997  1036  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 10:22:20.997  1036  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 10:22:20.997  1036  1530 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 10:22:20.998  1586  1797 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-30 10:22:21.000  1036  8237 D DhcpStateMachine: DHCPV4 request on wlan0
08-30 10:22:21.000  1036  8237 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-30 10:22:21.000  1036  8237 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-30 10:22:21.000  8280  8280 W dhcpcd  : type=1400 audit(0.0:193): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-30 10:22:21.000  8280  8280 W dhcpcd  : type=1400 audit(0.0:194): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 10:22:21.012  8280  8280 I dhcpcd  : version 5.5.6 starting
08-30 10:22:21.013  8279  8279 E DSQN    : DSQN ssw
08-30 10:22:21.014  8280  8280 E dhcpcd  : get_duid: m
08-30 10:22:21.014  8280  8280 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-30 10:22:21.014  8280  8280 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-30 10:22:21.014  1036  1521 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
,08-30 10:22:21.027  1586  1586 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,08-30 10:22:21.028  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 10:22:21.028  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 10:22:21.070  8280  8280 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-30 10:22:21.070  8280  8280 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-30 10:22:21.070  8280  8280 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-30 10:22:21.070  8280  8280 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
08-30 10:22:21.070  8280  8280 D dhcpcd  : wlan0: sending REQUEST (xid 0x7cd76ae1), next in 3.49 seconds
,08-30 10:22:21.145  8280  8280 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
,08-30 10:22:21.148   316  8278 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,08-30 10:22:21.181  8280  8280 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
08-30 10:22:21.181  8280  8280 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
08-30 10:22:21.182  8280  8280 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-30 10:22:21.183  8280  8280 D dhcpcd  : wlan0: adding default route via 192.168.1.1
,08-30 10:22:21.183  8280  8280 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,08-30 10:22:21.184  8280  8280 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-30 10:22:21.184  8280  8280 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-30 10:22:21.184  8280  8280 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-30 10:22:21.237   316  8278 D libc-netbsd: res_queryN name = clients3.google.com succeed
,08-30 10:22:21.267   316   893 D LGDataListener: argv[0]=dsqncommand
08-30 10:22:21.267   316   893 D LGDataListener: argv[1]=wlan0
08-30 10:22:21.267   316   893 D LGDataListener: argv[2]=1
08-30 10:22:21.267   316   893 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-30 10:22:21.268  1036  1116 D DSQN    : DSQM DsqnNotification wlan0  1
08-30 10:22:21.268  1036  1116 D DSQN    : start to monitor internet connection
,08-30 10:22:21.312  1036  8236 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 30 Aug 2016 08:22:21 GMT], X-Android-Received-Millis=[1472545341312], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472545341266]}
08-30 10:22:21.312  1036  8236 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-30 10:22:21.312  1036  8236 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-30 10:22:21.313  1036  1530 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
08-30 10:22:21.313  1036  1530 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-30 10:22:21.313  1036  1530 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 10:22:21.313  1036  1530 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 10:22:21.313  1036  1530 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-30 10:22:21.313  1036  1530 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
08-30 10:22:21.313  1036  1530 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-30 10:22:21.313  1036  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 10:22:21.313  1036  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 10:22:21.314  1036  1530 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 10:22:21.314  1036  1530 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 10:22:21.314  1036  1530 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-30 10:22:21.314  1036  1523 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 10:22:21.314  1036  1523 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 10:22:21.314  1586  1797 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-30 10:22:21.316  1864  1864 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 10:22:21.317  1864  1864 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
,08-30 10:22:21.343  1586  1586 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-30 10:22:21.344  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 10:22:21.345  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 10:22:21.389  8258  8258 W ExternalStrings: load override strings
08-30 10:22:21.389  8258  8258 W ExternalStrings: java.lang.RuntimeException: Unexpected tag, got eat-comment
08-30 10:22:21.389  8258  8258 W ExternalStrings: 	at com.mcafee.plugin.af.a(Unknown Source)
08-30 10:22:21.389  8258  8258 W ExternalStrings: 	at com.mcafee.plugin.ac.b(Unknown Source)
08-30 10:22:21.389  8258  8258 W ExternalStrings: 	at com.mcafee.plugin.ak.d(Unknown Source)
08-30 10:22:21.389  8258  8258 W ExternalStrings: 	at com.mcafee.plugin.ak.a(Unknown Source)
08-30 10:22:21.389  8258  8258 W ExternalStrings: 	at com.mcafee.app.s.getClassLoader(Unknown Source)
08-30 10:22:21.389  8258  8258 W ExternalStrings: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
08-30 10:22:21.389  8258  8258 W ExternalStrings: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-30 10:22:21.389  8258  8258 W ExternalStrings: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-30 10:22:21.389  8258  8258 W ExternalStrings: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148),
08-30 10:22:21.389  8258  8258 W ExternalStrings: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-30 10:22:21.389  8258  8258 W ExternalStrings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 10:22:21.389  8258  8258 W ExternalStrings: 	at android.os.Looper.loop(Looper.java:135)
08-30 10:22:21.389  8258  8258 W ExternalStrings: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-30 10:22:21.389  8258  8258 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 10:22:21.389  8258  8258 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 10:22:21.389  8258  8258 W ExternalStrings: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-30 10:22:21.389  8258  8258 W ExternalStrings: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,08-30 10:22:21.393  8258  8258 D StatusProvider: onCreate
08-30 10:22:21.459  8258  8258 V Signer  : override build config not found
,08-30 10:22:21.459  8258  8258 D Signer  : value of property debug is false
,08-30 10:22:21.505  8258  8258 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
08-30 10:22:21.505  8258  8258 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
08-30 10:22:21.505  8258  8258 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
08-30 10:22:21.506  8258  8258 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
08-30 10:22:21.506  8258  8258 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
08-30 10:22:21.506  8258  8258 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
08-30 10:22:21.507  8258  8258 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
,08-30 10:22:21.507  8258  8258 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
08-30 10:22:21.507  8258  8258 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
08-30 10:22:21.507  8258  8258 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
08-30 10:22:21.508  8258  8258 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
08-30 10:22:21.508  8258  8258 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
08-30 10:22:21.508  8258  8258 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
,08-30 10:22:21.523  8258  8258 V LGMDMManager: Create singleton instance
08-30 10:22:21.600  8258  8258 D LGMDMWrapper: LG MDM library v4.0.0 is available on this device.
,08-30 10:22:21.603  1036  8237 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,08-30 10:22:21.605  1036  8237 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-30 10:22:21.605  1036  8237 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-30 10:22:21.605  1036  8237 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
,08-30 10:22:21.606  1036  8237 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-30 10:22:21.606  1036  8237 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-30 10:22:21.606  1036  8237 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
,08-30 10:22:21.606  1036  8237 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-30 10:22:21.606  1036  8237 D DhcpStateMachine: RunningState
08-30 10:22:21.696  8258  8258 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 10:22:21.697  8258  8317 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-30 10:22:21.723  6890  6890 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 10:22:21.730  6890  6890 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 10:22:21.800  1036  1952 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=8320 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,08-30 10:22:21.805  1036  1952 I ActivityManager: Killing 7194:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
08-30 10:22:21.898  8258  8316 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-30 10:22:21.924  1036  1729 W libprocessgroup: failed to open /acct/uid_10085/pid_7194/cgroup.procs: No such file or directory
,08-30 10:22:21.972  8320  8320 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-30 10:22:22.000  8320  8320 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,08-30 10:22:22.034  8320  8320 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,08-30 10:22:22.034  8320  8320 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
,08-30 10:22:22.035  8320  8320 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-30 10:22:22.035  8320  8320 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-30 10:22:22.036  8320  8320 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-30 10:22:22.039  8320  8320 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,08-30 10:22:22.046  8320  8320 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
,08-30 10:22:22.060  8320  8320 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 10:22:22.065  8320  8320 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-30 10:22:22.077  8320  8320 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-30 10:22:22.080  8258  8258 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 10:22:22.081  8258  8317 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-30 10:22:22.083  8320  8320 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
,08-30 10:22:22.089  8320  8320 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-30 10:22:22.092  6890  6890 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 10:22:22.099  6890  6890 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-30 10:22:22.109  8320  8320 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-30 10:22:22.109  8320  8320 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 10:22:22.110  8320  8320 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-30 10:22:22.114  8258  8258 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 10:22:22.114  8258  8317 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-30 10:22:22.124  6890  6890 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 10:22:22.131  6890  6890 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 10:22:22.137  8320  8320 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 10:22:22.137  8320  8320 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 10:22:22.138  8320  8320 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-30 10:22:22.140  8258  8258 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 10:22:22.141  8258  8317 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-30 10:22:22.146  6890  6890 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 10:22:22.153  6890  6890 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 10:22:22.159  8320  8320 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 10:22:22.159  8320  8320 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 10:22:22.160  8320  8320 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-30 10:22:22.163  8258  8258 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 10:22:22.163  8258  8317 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-30 10:22:22.170  6890  6890 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 10:22:22.176  6890  6890 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 10:22:22.182  8320  8320 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 10:22:22.182  8320  8320 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 10:22:22.182  8320  8320 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-30 10:22:22.185  6890  6890 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
08-30 10:22:22.186  8258  8316 D LgDataFeature: LgDataFeature() Constructor: none
08-30 10:22:22.186  8258  8316 D LgDataFeature: LgDataFeature() Constructor Done, null
08-30 10:22:22.188  6890  6890 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
,08-30 10:22:22.200  8258  8317 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-30 10:22:22.201  8258  8258 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 10:22:22.217  6890  6890 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 10:22:22.225  6890  6890 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 10:22:22.234  8320  8320 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 10:22:22.234  8320  8320 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 10:22:22.241  8320  8320 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-30 10:22:22.245  8258  8258 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 10:22:22.246  8258  8317 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-30 10:22:22.254  6890  6890 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 10:22:22.260  6890  6890 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 10:22:22.268  8320  8320 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-30 10:22:22.268  8320  8320 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 10:22:22.270  8320  8320 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-30 10:22:22.276  8258  8258 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 10:22:22.276  8258  8317 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-30 10:22:22.283  8184  8184 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,08-30 10:22:22.290  8184  8184 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-30 10:22:22.294  1036  1523 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-30 10:22:22.295  6890  6890 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-30 10:22:22.296  1036  1523 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-30 10:22:22.297  1036  1523 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-30 10:22:22.299  1036  1523 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-30 10:22:22.301  1036  1523 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-30 10:22:22.301  6890  6890 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 10:22:22.302  1036  1523 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-30 10:22:22.303  1036  1530 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=true
08-30 10:22:22.303  1036  1530 D ConnectivityService: identical MTU - not setting
08-30 10:22:22.303  1036  1530 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-30 10:22:22.303  1036  1530 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-30 10:22:22.303  1036  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 10:22:22.303  1036  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 10:22:22.304  1036  1530 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 10:22:22.305  1586  1797 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
08-30 10:22:22.312  8320  8320 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-30 10:22:22.312  8320  8320 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 10:22:22.313  8320  8320 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-30 10:22:22.320  8320  8320 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-30 10:22:22.321  8320  8320 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-30 10:22:22.325  8258  8258 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 10:22:22.325  8258  8317 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-30 10:22:22.330  8184  8184 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-30 10:22:22.331  8184  8184 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-30 10:22:22.334  6890  6890 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 10:22:22.341  6890  6890 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 10:22:22.349  8320  8320 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 10:22:22.350  8320  8320 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 10:22:22.351  8320  8320 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,08-30 10:22:22.353  8320  8320 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-30 10:22:22.353  8320  8320 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-30 10:22:22.360  8258  8258 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-30 10:22:22.361  8258  8316 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
08-30 10:22:22.368  8320  8320 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,08-30 10:22:22.369  8320  8320 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-30 10:22:22.369  8320  8320 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
08-30 10:22:22.394  8258  8316 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
,08-30 10:22:22.407  8258  8316 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
,08-30 10:22:22.412  8258  8316 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-30 10:22:22.414  8258  8316 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-30 10:22:22.415  8258  8316 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
08-30 10:22:22.416  8258  8316 I SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
08-30 10:22:22.420  8258  8316 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
08-30 10:22:22.420  8320  8320 D LgDataFeature: LgDataFeature() Constructor: none
08-30 10:22:22.421  8320  8320 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 10:22:22.425  8258  8316 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
08-30 10:22:22.430  8320  8320 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
08-30 10:22:22.431  8320  8320 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-30 10:22:22.431  8320  8320 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-30 10:22:22.431  8320  8320 V SoundPool: doLoad: loading sample sampleID=1
08-30 10:22:22.432  8320  8320 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-30 10:22:22.435  8320  8359 V SoundPool: Start decode
,08-30 10:22:22.435  8320  8359 V MediaPlayer[Native]: decode(31, 10857164, 17813)
08-30 10:22:22.436   321  4055 V MediaPlayerService: decode(23, 10857164, 17813)
08-30 10:22:22.436   321  4055 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-30 10:22:22.436   321  4055 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-30 10:22:22.436   321  4055 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-30 10:22:22.436   321  4055 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-30 10:22:22.436   321  4055 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-30 10:22:22.436   321  4055 V MediaPlayerService: player type = 3
08-30 10:22:22.436   321  4055 V AwesomePlayer: AwesomePlayer create()
08-30 10:22:22.437   321  4055 V AwesomePlayer: reset_l() 
08-30 10:22:22.437   321  4055 V AwesomePlayer: cancelPlayerEvents
08-30 10:22:22.437   321  4055 V AwesomePlayer: setAudioSink() 
08-30 10:22:22.437   321  4055 V AwesomePlayer: reset_l() 
08-30 10:22:22.437   321  4055 V AudioCache: notify(0xb5474c80, 8, 0, 0)
08-30 10:22:22.437   321  4055 V AudioCache: ignored
08-30 10:22:22.437   321  4055 V AwesomePlayer: cancelPlayerEvents
08-30 10:22:22.437   321  4055 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
08-30 10:22:22.437   321  4055 V AwesomePlayer: setDataSource_l dataSource
08-30 10:22:22.437   321  4055 V LGParserOSAL: SniffLGParser start
08-30 10:22:22.437   321  4055 V LGParserOSAL: MainType:5, SubType=0
08-30 10:22:22.437   321  4055 V LGParserOSAL: #### check Mime : application/ogg
08-30 10:22:22.437   321  4055 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-30 10:22:22.437   321  4055 E MediaExtractor: Use LGExtractor :application/ogg 
08-30 10:22:22.441  7780  7780 D UEI.SmartControl: QS Service created
08-30 10:22:22.442  8320  8320 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-30 10:22:22.447  8320  8320 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-30 10:22:22.448  8320  8320 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-30 10:22:22.460  7780  7780 I UEI.SmartControl: Service initServices...
08-30 10:22:22.460  7780  7780 D UEI.SmartControl: QS start get config
,08-30 10:22:22.464  8320  8320 V LGMDMManager: Create singleton instance
08-30 10:22:22.494   321  4055 V LGParserOSAL: supported mime: application/ogg
08-30 10:22:22.494   321  4055 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-30 10:22:22.494   321  4055 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-30 10:22:22.494   321  4055 V AwesomePlayer: mBitrate = -1 bits/sec
08-30 10:22:22.495   321  4055 V AwesomePlayer: AudioTrack Setting
08-30 10:22:22.495   321  4055 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-30 10:22:22.495   321  4055 V AwesomePlayer: setAudioSource() 
08-30 10:22:22.495   321  4055 V MediaPlayerService: prepare
08-30 10:22:22.495   321  4055 V AwesomePlayer: prepareAsync_l() 
08-30 10:22:22.495   321  4055 V MediaPlayerService: wait for prepare
08-30 10:22:22.495   321  8360 V AwesomePlayer: onPrepareAsyncEvent() 
08-30 10:22:22.495   321  8360 V AwesomePlayer: initAudioDecoder() 
08-30 10:22:22.495   321  8360 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-30 10:22:22.495   321  8360 V AudioSystem: isOffloadSupported()
08-30 10:22:22.495   321  8360 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-30 10:22:22.495   321  8360 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-30 10:22:22.495   321  8360 I AudioFlinger: isAudioPlaybackHookOn() false
08-30 10:22:22.495   321  8360 V AwesomePlayer: getUseOffload() = 0 
08-30 10:22:22.495   321  8360 V OMXCodec: OMXCodec::Create
08-30 10:22:22.495   321  8360 V OMXCodec: findMatchingCodecs()
08-30 10:22:22.495   321  8360 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-30 10:22:22.495   321  8360 V OMXCodec: matchingCodecs.size()=1
08-30 10:22:22.495   321  8360 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,08-30 10:22:22.499   321  8360 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-30 10:22:22.499   321  8360 V LGCodecAdapter: LG Codec Adapter start
08-30 10:22:22.499   321  8360 V OMXCodec: OMXCodec Createtor
08-30 10:22:22.499   321  8360 V OMXCodec: setComponentRole
08-30 10:22:22.499   321  8360 V OMXCodec: configureCodec protected=0
08-30 10:22:22.499   321  8360 V LGCodecAdapter: called getLGCodecSpecificData
08-30 10:22:22.499   321  8360 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-30 10:22:22.500   321  8360 V LGCodecOSAL: Called LGconfigureCodecMETA
08-30 10:22:22.500   321  8360 V LGCodecOSAL: Called LGconfigureCodecMSG
08-30 10:22:22.500   321  8360 V LGCodecOSAL: Not support LGCodec
08-30 10:22:22.500   321  8360 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-30 10:22:22.500   321  8360 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-30 10:22:22.500   321  8360 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-30 10:22:22.500   321  8360 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-30 10:22:22.500   321  8360 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-30 10:22:22.500   321  8360 V AudioSystem: isOffloadSupported()
08-30 10:22:22.501   321  8360 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-30 10:22:22.501   321  8360 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-30 10:22:22.501   321  8360 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-30 10:22:22.501   321  8360 V OMXCodec: init()
08-30 10:22:22.501   321  8360 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-30 10:22:22.501   321  8360 V OMXCodec: allocateBuffers
08-30 10:22:22.501   321  8360 V OMXCodec: allocateBuffersOnPort portIndex=0
08-30 10:22:22.501   321  8360 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-30 10:22:22.501   321  8360 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7650 on input port
08-30 10:22:22.501   321  8360 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a60 on input port
08-30 10:22:22.501   321  8360 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on input port
08-30 10:22:22.501   321  8360 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ba0 on input port
08-30 10:22:22.501   321  8360 V OMXCodec: allocateBuffersOnPort portIndex=1
08-30 10:22:22.501   321  8360 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-30 10:22:22.502   321  8360 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c40 on output port
08-30 10:22:22.502   321  8360 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7dd0 on output port
08-30 10:22:22.502   321  8360 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7e20 on output port
08-30 10:22:22.502   321  8360 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7f10 on output port
08-30 10:22:22.502   321  8360 V OMXCodec: init() mAsyncCompletion wait!!! 
08-30 10:22:22.502   321  8362 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-30 10:22:22.502   321  8362 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-30 10:22:22.502   321  8362 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-30 10:22:22.502   321  8362 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-30 10:22:22.502   321  8362 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-30 10:22:22.502   321  8362 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=,4
08-30 10:22:22.502   321  8360 V OMXCodec: init() mAsyncCompletion wait free! 
08-30 10:22:22.502   321  8360 V AwesomePlayer: finishAsyncPrepare_l() 
08-30 10:22:22.502   321  8360 V AudioCache: notify(0xb5474c80, 5, 0, 0)
08-30 10:22:22.502   321  8360 V AudioCache: ignored
08-30 10:22:22.502   321  8360 V AudioCache: notify(0xb5474c80, 1, 0, 0)
08-30 10:22:22.502   321  8360 V AudioCache: prepared
08-30 10:22:22.502   321  4055 V AudioCache: wait - success
08-30 10:22:22.502   321  4055 V MediaPlayerService: start
08-30 10:22:22.502   321  4055 V AwesomePlayer: play_l() 
08-30 10:22:22.502   321  4055 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-30 10:22:22.502   321  4055 V AwesomePlayer: createAudioPlayer_l
08-30 10:22:22.502   321  4055 V AwesomePlayer: seekAudioIfNecessary_l() 
08-30 10:22:22.502   321  4055 V AwesomePlayer: startAudioPlayer_l() 
08-30 10:22:22.502   321  4055 D AudioPlayer: start of Playback, useOffload 0
08-30 10:22:22.502   321  4055 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-30 10:22:22.502   321  4055 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-30 10:22:22.504   321  8362 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-30 10:22:22.504   321  8362 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-30 10:22:22.504   321  8362 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-30 10:22:22.504   321  8362 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-30 10:22:22.504   321  8362 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-30 10:22:22.504   321  8362 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-30 10:22:22.505   321  8362 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885248
08-30 10:22:22.505   321  8362 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-30 10:22:22.505   321  8362 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885648
08-30 10:22:22.505   321  8362 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-30 10:22:22.505   321  8362 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885728
08-30 10:22:22.505   321  8362 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-30 10:22:22.505   321  8362 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885968
08-30 10:22:22.505   321  8362 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-30 10:22:22.505   321  8362 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-30 10:22:22.505   321  8362 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-30 10:22:22.505   321  8362 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-30 10:22:22.505   321  8362 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-30 10:22:22.505   321  8362 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-30 10:22:22.505   321  8362 V OMXCodec: allocateBuffersOnPort portIndex=1
08-30 10:22:22.505   321  8362 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-30 10:22:22.505   321  8362 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7e20 on output port
08-30 10:22:22.505   321  8362 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7dd0 on output port
08-30 10:22:22.505   321  8362 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c40 on output port
,08-30 10:22:22.505   321  8362 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fba0 on output port
08-30 10:22:22.505   321  8362 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-30 10:22:22.505   321  8362 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-30 10:22:22.506   321  4055 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-30 10:22:22.506   321  4055 V AudioCache: notify(0xb5474c80, 6, 0, 0)
08-30 10:22:22.507   321  4055 V AudioCache: ignored
08-30 10:22:22.507   321  8363 V AudioCache: write(0xb1508000, 4096)
08-30 10:22:22.507   321  8363 V AudioCache: memcpy(0xac300000, 0xb1508000, 4096)
08-30 10:22:22.507   321  4055 V MediaPlayerService: wait for playback complete
08-30 10:22:22.508   321  8363 V AudioCache: write(0xb1508000, 4096)
08-30 10:22:22.508   321  8363 V AudioCache: memcpy(0xac301000, 0xb1508000, 4096)
08-30 10:22:22.508   321  8363 V AudioCache: write(0xb1508000, 4096)
08-30 10:22:22.508   321  8363 V AudioCache: memcpy(0xac302000, 0xb1508000, 4096)
,08-30 10:22:22.511   321  8363 V AudioCache: write(0xb1508000, 4096)
08-30 10:22:22.511   321  8363 V AudioCache: memcpy(0xac303000, 0xb1508000, 4096)
08-30 10:22:22.512   321  8363 V AudioCache: write(0xb1508000, 4096)
,08-30 10:22:22.512   321  8363 V AudioCache: memcpy(0xac304000, 0xb1508000, 4096)
08-30 10:22:22.513   321  8363 V AudioCache: write(0xb1508000, 4096)
08-30 10:22:22.513   321  8363 V AudioCache: memcpy(0xac305000, 0xb1508000, 4096)
08-30 10:22:22.513   321  8363 V AudioCache: write(0xb1508000, 4096)
08-30 10:22:22.513   321  8363 V AudioCache: memcpy(0xac306000, 0xb1508000, 4096)
08-30 10:22:22.514   321  8363 V AudioCache: write(0xb1508000, 4096)
08-30 10:22:22.514   321  8363 V AudioCache: memcpy(0xac307000, 0xb1508000, 4096)
08-30 10:22:22.515   321  8363 V AudioCache: write(0xb1508000, 4096)
08-30 10:22:22.515   321  8363 V AudioCache: memcpy(0xac308000, 0xb1508000, 4096)
08-30 10:22:22.515   321  8363 V AudioCache: write(0xb1508000, 4096)
08-30 10:22:22.515   321  8363 V AudioCache: memcpy(0xac309000, 0xb1508000, 4096)
08-30 10:22:22.516   321  8363 V AudioCache: write(0xb1508000, 4096)
08-30 10:22:22.516   321  8363 V AudioCache: memcpy(0xac30a000, 0xb1508000, 4096)
08-30 10:22:22.516   321  8363 V AudioCache: write(0xb1508000, 4096)
08-30 10:22:22.516   321  8363 V AudioCache: memcpy(0xac30b000, 0xb1508000, 4096)
08-30 10:22:22.517   321  8363 V AudioCache: write(0xb1508000, 4096)
08-30 10:22:22.517   321  8363 V AudioCache: memcpy(0xac30c000, 0xb1508000, 4096)
08-30 10:22:22.517   321  8363 V AudioCache: write(0xb1508000, 4096)
08-30 10:22:22.517   321  8363 V AudioCache: memcpy(0xac30d000, 0xb1508000, 4096)
08-30 10:22:22.518   321  8363 V AudioCache: write(0xb1508000, 4096)
08-30 10:22:22.518   321  8363 V AudioCache: memcpy(0xac30e000, 0xb1508000, 4096)
08-30 10:22:22.518   321  8363 V AudioCache: write(0xb1508000, 4096)
08-30 10:22:22.518   321  8363 V AudioCache: memcpy(0xac30f000, 0xb1508000, 4096)
08-30 10:22:22.519   321  8363 V AudioCache: write(0xb1508000, 4096)
08-30 10:22:22.519   321  8363 V AudioCache: memcpy(0xac310000, 0xb1508000, 4096)
08-30 10:22:22.519   321  8363 V AudioCache: write(0xb1508000, 4096)
08-30 10:22:22.519   321  8363 V AudioCache: memcpy(0xac311000, 0xb1508000, 4096)
08-30 10:22:22.520   321  8363 V AudioCache: write(0xb1508000, 4096)
08-30 10:22:22.520   321  8363 V AudioCache: memcpy(0xac312000, 0xb1508000, 4096)
08-30 10:22:22.520   321  8363 V AudioCache: write(0xb1508000, 4096)
08-30 10:22:22.520   321  8363 V AudioCache: memcpy(0xac313000, 0xb1508000, 4096)
08-30 10:22:22.521   321  8363 V AudioCache: write(0xb1508000, 4096)
08-30 10:22:22.521   321  8363 V AudioCache: memcpy(0xac314000, 0xb1508000, 4096)
,08-30 10:22:22.522   321  8363 V AudioCache: write(0xb1508000, 4096)
08-30 10:22:22.522   321  8363 V AudioCache: memcpy(0xac315000, 0xb1508000, 4096)
08-30 10:22:22.522   321  8363 V AudioCache: write(0xb1508000, 4096)
08-30 10:22:22.522   321  8363 V AudioCache: memcpy(0xac316000, 0xb1508000, 4096)
08-30 10:22:22.523   321  8363 V AudioCache: write(0xb1508000, 4096)
08-30 10:22:22.523   321  8363 V AudioCache: memcpy(0xac317000, 0xb1508000, 4096)
08-30 10:22:22.524   321  8363 V AudioCache: write(0xb1508000, 4096)
08-30 10:22:22.524   321  8363 V AudioCache: memcpy(0xac318000, 0xb1508000, 4096)
08-30 10:22:22.524   321  8363 V AudioCache: write(0xb1508000, 4096)
08-30 10:22:22.524   321  8363 V AudioCache: memcpy(0xac319000, 0xb1508000, 4096)
08-30 10:22:22.525   321  8363 V AudioCache: write(0xb1508000, 4096)
08-30 10:22:22.525   321  8363 V AudioCache: memcpy(0xac31a000, 0xb1508000, 4096)
08-30 10:22:22.526   321  8363 V AudioCache: write(0xb1508000, 4096)
08-30 10:22:22.526   321  8363 V AudioCache: memcpy(0xac31b000, 0xb1508000, 4096)
08-30 10:22:22.526   321  8363 V AudioCache: write(0xb1508000, 4096)
08-30 10:22:22.526   321  8363 V AudioCache: memcpy(0xac31c000, 0xb1508000, 4096)
08-30 10:22:22.527   321  8363 V AudioCache: write(0xb1508000, 4096)
08-30 10:22:22.527   321  8363 V AudioCache: memcpy(0xac31d000, 0xb1508000, 4096)
08-30 10:22:22.527   321  8363 V AudioCache: write(0xb1508000, 4096)
08-30 10:22:22.527   321  8363 V AudioCache: memcpy(0xac31e000, 0xb1508000, 4096)
08-30 10:22:22.528   321  8363 V AudioCache: write(0xb1508000, 4096)
08-30 10:22:22.528   321  8363 V AudioCache: memcpy(0xac31f000, 0xb1508000, 4096)
08-30 10:22:22.528   321  8363 V AudioCache: write(0xb1508000, 4096)
08-30 10:22:22.529   321  8363 V AudioCache: memcpy(0xac320000, 0xb1508000, 4096)
08-30 10:22:22.529   321  8363 V AudioCache: write(0xb1508000, 4096)
08-30 10:22:22.529   321  8363 V AudioCache: memcpy(0xac321000, 0xb1508000, 4096)
08-30 10:22:22.529   321  8363 V AudioCache: write(0xb1508000, 4096)
08-30 10:22:22.529   321  8363 V AudioCache: memcpy(0xac322000, 0xb1508000, 4096)
08-30 10:22:22.529   321  8363 V AudioCache: write(0xb1508000, 4096)
08-30 10:22:22.529   321  8363 V AudioCache: memcpy(0xac323000, 0xb1508000, 4096)
08-30 10:22:22.531   321  8363 V AudioCache: write(0xb1508000, 4096)
08-30 10:22:22.531   321  8363 V AudioCache: memcpy(0xac324000, 0xb1508000, 4096)
08-30 10:22:22.531   321  8363 V AudioCache: write(0xb1508000, 4096)
08-30 10:22:22.531   321  8363 V AudioCache: memcpy(0xac325000, 0xb1508000, 4096)
08-30 10:22:22.531   321  8363 V AudioCache: write(0xb1508000, 4096)
08-30 10:22:22.531   321  8363 V AudioCache: memcpy(0xac326000, 0xb1508000, 4096)
08-30 10:22:22.531   321  8363 V AudioCache: write(0xb1508000, 4096)
08-30 10:22:22.531   321  8363 V AudioCache: memcpy(0xac327000, 0xb1508000, 4096)
08-30 10:22:22.533   321  8363 V AudioCache: write(0xb1508000, 4096)
08-30 10:22:22.533   321  8363 V AudioCache: memcpy(0xac328000, 0xb1508000, 4096)
08-30 10:22:22.533   321  8363 V AudioCache: write(0xb1508000, 4096)
08-30 10:22:22.533   321  8363 V AudioCache: memcpy(0xac329000, 0xb1508000, 4096)
08-30 10:22:22.533   321  8363 V AudioCache: write(0xb1508000, 4096)
08-30 10:22:22.533   321  8363 V AudioCache: memcpy(0xac32a000, 0xb1508000, 4096)
08-30 10:22:22.533   321  8363 V AudioCache: write(0xb1508000, 4096)
08-30 10:22:22.533   321  8363 V AudioCache: memcpy(0xac32b000, 0xb1508000, 4096)
08-30 10:22:22.534  8320  8320 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
,08-30 10:22:22.534   321  8363 V AudioCache: write(0xb1508000, 4096)
08-30 10:22:22.534   321  8363 V AudioCache: memcpy(0xac32c000, 0xb1508000, 4096)
08-30 10:22:22.534   321  8363 V AudioCache: write(0xb1508000, 4096)
08-30 10:22:22.534   321  8363 V AudioCache: memcpy(0xac32d000, 0xb1508000, 4096)
08-30 10:22:22.534   321  8363 V AudioCache: write(0xb1508000, 4096)
08-30 10:22:22.535   321  8363 V AudioCache: memcpy(0xac32e000, 0xb1508000, 4096)
08-30 10:22:22.535   321  8363 V AudioCache: write(0xb1508000, 4096)
08-30 10:22:22.535   321  8363 V AudioCache: memcpy(0xac32f000, 0xb1508000, 4096)
08-30 10:22:22.535   321  8363 V AudioCache: write(0xb1508000, 4096)
08-30 10:22:22.535   321  8363 V AudioCache: memcpy(0xac330000, 0xb1508000, 4096)
08-30 10:22:22.535   321  8363 V AudioCache: write(0xb1508000, 4096)
08-30 10:22:22.535   321  8363 V AudioCache: memcpy(0xac331000, 0xb1508000, 4096)
08-30 10:22:22.536   321  8362 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-30 10:22:22.536   321  8363 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-30 10:22:22.536   321  8363 V AwesomePlayer: postAudioEOS() 
08-30 10:22:22.536   321  8363 V AudioCache: write(0xb1508000, 280)
08-30 10:22:22.536   321  8363 V AudioCache: memcpy(0xac332000, 0xb1508000, 280)
08-30 10:22:22.537  8320  8320 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
08-30 10:22:22.538   321  8360 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-30 10:22:22.538   321  8360 V AwesomePlayer: onStreamDone
08-30 10:22:22.538   321  8360 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-30 10:22:22.538   321  8360 V AudioCache: notify(0xb5474c80, 2, 0, 0)
08-30 10:22:22.538   321  8360 V AudioCache: playback complete
08-30 10:22:22.538   321  8360 V AwesomePlayer: pause_l() 
08-30 10:22:22.538   321  8360 V AudioCache: notify(0xb5474c80, 7, 0, 0)
08-30 10:22:22.538   321  8360 V AudioCache: ignored
08-30 10:22:22.538   321  8360 V AwesomePlayer: cancelPlayerEvents
08-30 10:22:22.538   321  4055 V AudioCache: wait - success
08-30 10:22:22.538   321  4055 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-30 10:22:22.538   321  8360 D AudioPlayer: Pause Playback at 1068125
08-30 10:22:22.538   321  4055 V AwesomePlayer: reset_l() 
08-30 10:22:22.538   321  4055 V AudioCache: notify(0xb5474c80, 8, 0, 0)
08-30 10:22:22.538   321  4055 V AudioCache: ignored
08-30 10:22:22.538   321  4055 V AwesomePlayer: cancelPlayerEvents
08-30 10:22:22.538   321  4055 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-30 10:22:22.538   321  4055 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-30 10:22:22.538   321  4055 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-30 10:22:22.538   321  4055 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-30 10:22:22.538   321  4055 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-30 10:22:22.539   321  8362 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-30 10:22:22.539   321  8362 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-30 10:22:22.539   321  8362 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-30 10:22:22.539   321  8362 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ba0 on port 0
08-30 10:22:22.539   321  8362 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-30 10:22:22.539   321  8362 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b50 on port 0
08-30 10:22:22.539   321  8362 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-30 10:22:22.539   321  8362 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a60 on port 0
08-30 10:22:22.539   321  8362 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-30 10:22:22.539   321  8362 V OMXCodec: [OMX.goog,le.vorbis.decoder] freeing buffer 0xb54f7650 on port 0
08-30 10:22:22.539   321  8362 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-30 10:22:22.539   321  8362 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-30 10:22:22.539   321  8362 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fba0 on port 1
08-30 10:22:22.539   321  8362 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-30 10:22:22.539   321  8362 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7c40 on port 1
08-30 10:22:22.539   321  8362 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-30 10:22:22.539   321  8362 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7dd0 on port 1
08-30 10:22:22.539   321  8362 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-30 10:22:22.539   321  8362 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7e20 on port 1
08-30 10:22:22.539   321  8362 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-30 10:22:22.539   321  8362 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-30 10:22:22.539   321  4055 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-30 10:22:22.539   321  4055 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-30 10:22:22.539   321  8362 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-30 10:22:22.539   321  8362 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-30 10:22:22.539   321  8362 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-30 10:22:22.539   321  4055 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-30 10:22:22.539   321  4055 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-30 10:22:22.539   321  4055 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-30 10:22:22.540   321  4055 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-30 10:22:22.540   321  4055 D AudioPlayer: AudioPlayer releasing audio source
08-30 10:22:22.540   321  4055 D AudioPlayer: AudioPlayer done releasing audio source
08-30 10:22:22.540   321  4055 V AwesomePlayer: reset_l() 
08-30 10:22:22.540   321  4055 V AwesomePlayer: cancelPlayerEvents
08-30 10:22:22.540   321  4055 V AwesomePlayer: ~AwesomePlayer call
08-30 10:22:22.540   321  4055 V AwesomePlayer: reset_l() 
08-30 10:22:22.540   321  4055 V AwesomePlayer: cancelPlayerEvents
08-30 10:22:22.540  8320  8359 V SoundPool: close(31)
08-30 10:22:22.541  8320  8359 V SoundPool: pointer = 0xa0037000, size = 205080, sampleRate = 48000, numChannels = 2
08-30 10:22:22.541  8320  8320 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:1423
08-30 10:22:22.543  8258  8258 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-30 10:22:22.546  8258  8258 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-30 10:22:22.547  8258  8258 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
,08-30 10:22:22.550  8258  8258 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-30 10:22:22.552  8258  8258 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 10:22:22.573  8258  8258 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 10:22:22.576  8258  8258 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 10:22:22.577  8258  8258 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 10:22:22.757  7780  7780 I UEI.SmartControl: Supports setup maps: true
,08-30 10:22:22.759  7780  7780 D UEI.SmartControl: QS start statue = true Error code = 0
,08-30 10:22:22.759  7780  7780 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-30 10:22:22.759  7780  7780 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-30 10:22:22.759  7780  7780 I UEI.SmartControl: ### init IR Blaster...
08-30 10:22:22.763  7780  7780 D serial_port: Configuring serial port
,08-30 10:22:22.763  7780  7780 E UEI.SmartControl: UEIBLaster setting for 616
08-30 10:22:22.763  7780  7780 I UEI.SmartControl: Setting serial record hearder size = 2
08-30 10:22:22.763  7780  7780 I UEI.SmartControl: configuring settings for MAXQ616
08-30 10:22:22.763  7780  7780 I UEI.SmartControl: Get version...
08-30 10:22:22.782  7780  8367 D UEI.SmartControl: serial port data available: 21
,08-30 10:22:22.808  7780  7780 D UEI.SmartControl: MAXQ616 A2-X4 software.
,08-30 10:22:22.808  7780  7780 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-30 10:22:22.809  7780  7780 I UEI.SmartControl: QS saving settings...
08-30 10:22:22.810  7780  7780 D UEI.SmartControl: IR Blaster version: 25672567
,08-30 10:22:22.827  7780  8367 D UEI.SmartControl: serial port data available: 4
,08-30 10:22:22.858  7780  8373 I UEI.SmartControl: Device manager: loading config....
,08-30 10:22:22.859  7780  8373 D UEI.SmartControl: ----------- loading internal config...
,08-30 10:22:22.860  7780  7780 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-30 10:22:22.865  7780  7780 E UEI.SmartControl: Services init done
08-30 10:22:22.865  7780  7780 D UEI.SmartControl: QS Service init finished
,08-30 10:22:22.867  7780  7780 D UEI.SmartControl: QS Service version name: 2.1.91
,08-30 10:22:22.867  7780  7780 D UEI.SmartControl: QS Service version code: 201091
08-30 10:22:22.868  7780  7780 D UEI.SmartControl: Service requested: Control
08-30 10:22:22.868  7780  8373 E UEI.SmartControl: Loading SETTINGS...
08-30 10:22:22.873  7780  7780 D UEI.SmartControl: Request IControl service: devices are loaded...
08-30 10:22:22.875  7780  7780 D UEI.SmartControl: Internal service binding...
08-30 10:22:22.875  8320  8320 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
,08-30 10:22:22.876  7780  7795 I UEI.SmartControl: ------ IControl API: 11
08-30 10:22:22.876  7780  7795 D UEI.SmartControl: File observer start...
08-30 10:22:22.877  7780  7795 E UEI.SmartControl: IR Port is disabled: false
08-30 10:22:22.878  7780  7795 D UEI.SmartControl: Starting file observer...
08-30 10:22:22.880  7780  7795 I UEI.SmartControl: Registering callback...
08-30 10:22:22.882  7780  7897 I UEI.SmartControl: ------ IControl API: 19
08-30 10:22:22.883  7780  8373 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,08-30 10:22:22.884  7780  7897 I UEI.SmartControl: Registering Services Ready callback...
08-30 10:22:22.896  7780  8372 I UEI.SmartControl: Notify AllClients services are ready: 0
,08-30 10:22:22.898  8320  8335 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-30 10:22:22.898  7780  8372 D UEI.SmartControl: -----service ready thread exits
08-30 10:22:22.900  8320  8356 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-30 10:22:22.900  8320  8356 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-30 10:22:22.900  8320  8320 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-30 10:22:22.901  8320  8320 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-30 10:22:22.901  7780  7796 I UEI.SmartControl: ------ IControl API: 8
08-30 10:22:22.903  8320  8320 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-30 10:22:22.903  8320  8320 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-30 10:22:22.903  8320  8320 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-30 10:22:22.903  8320  8320 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-30 10:22:22.904  8320  8320 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-30 10:22:22.905  8320  8320 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-30 10:22:22.906  8320  8320 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
08-30 10:22:22.912  8320  8320 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-30 10:22:22.913  8320  8320 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-30 10:22:22.914  8320  8320 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-30 10:22:22.914  8320  8320 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-30 10:22:22.915  8320  8320 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
,08-30 10:22:22.918  8320  8320 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-30 10:22:22.919  8320  8320 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-30 10:22:22.922  8320  8320 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1472545342920]
08-30 10:22:22.925  8320  8320 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
,08-30 10:22:22.927  1036  2305 I ActivityManager: Killing 7212:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
,08-30 10:22:22.965  8320  8375 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-30 10:22:23.035  1036  1764 W libprocessgroup: failed to open /acct/uid_10093/pid_7212/cgroup.procs: No such file or directory
,08-30 10:22:23.052  8320  8320 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,08-30 10:22:23.055  8320  8320 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
,08-30 10:22:23.056  8320  8320 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-30 10:22:23.057  8320  8320 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-30 10:22:23.058  8320  8320 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-30 10:22:23.059  8320  8320 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-30 10:22:23.060  8320  8320 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
08-30 10:22:23.085  8320  8320 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,08-30 10:22:23.756  6615  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 10:22:23.756  6615  6733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 10:22:23.756  6615  6733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 10:22:23.756  6615  6733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 10:22:23.756  6615  6733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 10:22:23.756  6615  6733 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 10:22:23.756  6615  6733 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 10:22:23.756  6615  6733 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 10:22:23.765  6615  6733 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 10:22:23.766  6615  6733 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 10:22:23.766  6615  6733 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2b99651b removed from the list
08-30 10:22:23.766  6615  6733 D io.jxcore.node.ConnectivityMonitor: stop
08-30 10:22:23.766  6615  6733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 10:22:23.766  6615  6733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 10:22:23.773  6615  8382 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
08-30 10:22:23.776  6615  8382 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-30 10:22:23.780  1036  1523 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2437 sc=60 link=72 tx=75.0, 0.0, 0.0  rx=67.5 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-628438748] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-30 10:22:23.781  1036  1523 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2437 sc=60 link=72 tx=75.0, 0.0, 0.0  rx=67.5 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-628438747] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-30 10:22:23.781  1036  1523 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-30 10:22:23.794  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-30 10:22:23.951  1036  1525 V WifiInternetCheck: Single check msg out of sync, ignoring.
,08-30 10:22:23.989  1036  1530 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-30 10:22:24.004  1036  1118 D Tethering: MasterInitialState.processMessage what=3
,08-30 10:22:24.027  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 10:22:24.027  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 10:22:24.027  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 10:22:24.027  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 10:22:24.027  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 10:22:24.027  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 10:22:24.027  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 10:22:24.027  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 10:22:24.032  6615  6615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 10:22:24.037  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 10:22:24.037  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 10:22:24.037  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 10:22:24.037  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 10:22:24.037  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 10:22:24.037  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 10:22:24.037  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 10:22:24.037  6615  6615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 10:22:24.038  6615  6615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 10:22:24.042  1036  1102 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-30 10:22:24.049  8258  8258 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-30 10:22:24.057  5808  5808 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,08-30 10:22:24.068  8258  8316 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-30 10:22:24.082  2229  2229 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-30 10:22:24.098  7078  7078 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-30 10:22:24.098  7078  7078 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-30 10:22:24.098  7078  7078 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-30 10:22:24.098  7078  7078 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-30 10:22:24.103  7078  7078 I AppUp4:CustModeStarterReceiver: onReceive
08-30 10:22:24.107  7078  7078 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@3af539be
08-30 10:22:24.107  7078  7078 D AppUp4:CustFacade: isCustomizationCompleted : false
08-30 10:22:24.107  7078  7078 D AppUp4:CustFacade: isPhone : true
08-30 10:22:24.109  7078  7078 D AppUp4:CustModeStarterReceiver: begin check event
08-30 10:22:24.109  7078  7078 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-30 10:22:24.114  4383  4383 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-30 10:22:24.114  4383  4383 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-30 10:22:24.116  4383  4383 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-30 10:22:24.122  4383  4383 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 10:22:24.126  3486  3486 V DownloadManager: Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
08-30 10:22:24.142  3486  3486 V DownloadManager: DownloadService onCreate
,08-30 10:22:24.150  3486  8384 I DownloadManager: in removeSpuriousFiles
08-30 10:22:24.150  3486  8384 V DownloadManager: starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
08-30 10:22:24.170  3486  8384 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@66ae6da on behalf of 3486
08-30 10:22:24.171   316  8402 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-30 10:22:24.171   316  8402 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
,08-30 10:22:24.175  3486  8384 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
08-30 10:22:24.175  3486  8384 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGEIME_5.1.29_release_repacked_ARM_XT9_MYSCRIPT_20160317004155539.apk
08-30 10:22:24.175  3486  8384 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_5.1.24_COM_COM(9012_VDF)_20160401022656759.apk
08-30 10:22:24.175  3486  8384 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
08-30 10:22:24.175  3486  8384 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
08-30 10:22:24.175  3486  8384 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
08-30 10:22:24.175  3486  8384 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
08-30 10:22:24.175  3486  8384 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/ConciergeBoard_4.40.12_COM_COM(VDF)_20160126234417577.apk
08-30 10:22:24.175  3486  8384 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
08-30 10:22:24.175  3486  8384 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
08-30 10:22:24.175  3486  8384 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
08-30 10:22:24.177  4383  8386 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-30 10:22:24.177  3486  8384 I DownloadManager: in trimDatabase
08-30 10:22:24.178  3486  8384 V DownloadManager: starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
08-30 10:22:24.181  4383  8400 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-30 10:22:24.181  4383  8386 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
08-30 10:22:24.181  4383  8400 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-30 10:22:24.182  3486  8384 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@3476e70b on behalf of 3486
,08-30 10:22:24.198  1036  1764 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=8406 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
08-30 10:22:24.202  3486  3486 V DownloadManager: DownloadService onStartCommand
08-30 10:22:24.202  3486  8385 V DownloadManager: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
08-30 10:22:24.204  4383  8386 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
08-30 10:22:24.205  3486  8385 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@2a937801 on behalf of 3486
08-30 10:22:24.208  4383  4383 E LGDMClient: [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
08-30 10:22:24.210  4383  4383 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
08-30 10:22:24.210  4383  4383 D LGDMClient: [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,08-30 10:22:24.212  3486  8385 V DownloadManager: processing inserted download 1
08-30 10:22:24.213  3486  8385 V DownloadManager: processing inserted download 4
,08-30 10:22:24.214  3486  8385 V DownloadManager: processing inserted download 7
08-30 10:22:24.215  3486  8385 V DownloadManager: processing inserted download 8
08-30 10:22:24.216   316  8402 D libc-netbsd: res_queryN name = mtalk.google.com succeed
08-30 10:22:24.216  3486  8385 V DownloadManager: processing inserted download 9
08-30 10:22:24.218  3486  8385 V DownloadManager: processing inserted download 10
08-30 10:22:24.219  3486  8385 V DownloadManager: processing inserted download 11
08-30 10:22:24.220  3486  8385 V DownloadManager: processing inserted download 12
08-30 10:22:24.221  3486  8385 V DownloadManager: processing inserted download 13
08-30 10:22:24.223  3486  8385 V DownloadManager: processing inserted download 14
08-30 10:22:24.224  3486  8385 V DownloadManager: processing inserted download 16
08-30 10:22:24.227  3486  3486 V DownloadManager: DownloadService onDestroy
08-30 10:22:24.232  4383  4383 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [274] : DmConstants.DMAgentState.DMA_STATE_IDLE
,08-30 10:22:24.235  4383  4383 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [659] : agentmodeOnOff is OFF. Finish OneDayWiFiCheck
,08-30 10:22:24.258  8406  8406 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 10:22:24.258  8406  8406 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-30 10:22:24.259  8406  8406 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-30 10:22:24.260  8406  8406 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-30 10:22:24.266  1036  1102 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-30 10:22:24.363  8406  8406 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-30 10:22:24.393  8406  8406 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,08-30 10:22:24.444  8406  8406 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-30 10:22:24.481  2229  8425 D GCM     : Connected
,08-30 10:22:24.484  8406  8406 D LgDataFeature: LgDataFeature() Constructor: none
,08-30 10:22:24.485  8406  8406 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 10:22:24.519  2229  8425 D GCM     : Message class com.google.e.a.a.q
,08-30 10:22:24.683  8406  8406 D eas_req : ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-30 10:22:24.735  8406  8406 I HubEmail: JNI_OnLoad()
,08-30 10:22:24.735  8406  8406 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-30 10:22:24.735  8406  8406 I HubEmail: registerNatives()
08-30 10:22:24.735  8406  8406 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-30 10:22:24.735  8406  8406 I HubEmail: registerNativeMethods()
08-30 10:22:24.735  8406  8406 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-30 10:22:24.735  8406  8406 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,08-30 10:22:24.752  8406  8437 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 10:22:24.771  3444  3444 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-30 10:22:24.771  3444  3444 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-30 10:22:24.772  3444  3444 I LgeMiscReceiver: networkInfo.isConnected() = true
08-30 10:22:24.772  3444  3444 D PhoneState: setPdpRejectCasuse : false
,08-30 10:22:24.777   316  8440 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-30 10:22:24.777   316  8440 D libc-netbsd: res_queryN name = static-avc.lglime.com, class = 1, type = 1
08-30 10:22:24.812  1036  1052 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=8441 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,08-30 10:22:24.819   316  8440 D libc-netbsd: res_queryN name = static-avc.lglime.com succeed
,08-30 10:22:24.882  8162  8436 V FormManager: There are no updated forms. The schedule will be deleted.
,08-30 10:22:24.886  8162  8436 V FormManager: Alarm would be updated, because LastCheckTime has been updated.
08-30 10:22:24.918  1036  1952 I ActivityManager: Killing 7708:com.google.android.talk/u0a72 (adj 15): empty #17
,08-30 10:22:24.972  8441  8441 D LgDataFeature: LgDataFeature() Constructor: none
,08-30 10:22:24.972  8441  8441 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 10:22:24.975  8441  8441 D PhoneMonitor: Register our PhoneStateListener
08-30 10:22:24.983  1036  2002 W libprocessgroup: failed to open /acct/uid_10072/pid_7708/cgroup.procs: No such file or directory
08-30 10:22:25.004  8441  8441 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,08-30 10:22:25.009  8441  8441 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-30 10:22:25.036  8441  8441 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
08-30 10:22:25.036  8441  8441 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
08-30 10:22:25.037  8441  8441 D TelephonyAutoProfiling: [parse] Load xml
08-30 10:22:25.040  8441  8441 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
08-30 10:22:25.040  8441  8441 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
08-30 10:22:25.040  8441  8441 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-30 10:22:25.040  8441  8441 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
08-30 10:22:25.040  8441  8441 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
08-30 10:22:25.040  8441  8441 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
08-30 10:22:25.040  8441  8441 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-30 10:22:25.040  8441  8441 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-30 10:22:25.040  8441  8441 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-30 10:22:25.040  8441  8441 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-30 10:22:25.040  8441  8441 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-30 10:22:25.040  8441  8441 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-30 10:22:25.040  8441  8441 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-30 10:22:25.040  8441  8441 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-30 10:22:25.040  8441  8441 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-30 10:22:25.040  8441  8441 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-30 10:22:25.040  8441  8441 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
,08-30 10:22:25.051  8441  8441 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
08-30 10:22:25.072  1036  2307 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=8460 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-30 10:22:25.074  1036  2307 I ActivityManager: Killing 7760:com.android.contacts/u0a19 (adj 15): empty #17
,08-30 10:22:25.132  1036  1729 W libprocessgroup: failed to open /acct/uid_10019/pid_7760/cgroup.procs: No such file or directory
,08-30 10:22:25.153  1036  1523 E WifiStateMachine:  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
08-30 10:22:25.154  1036  1523 E WifiStateMachine:  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
08-30 10:22:25.154  1036  1523 E WifiStateMachine:  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
08-30 10:22:25.155  1036  1523 E WifiStateMachine:  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
08-30 10:22:25.155  1036  1523 E WifiStateMachine:  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
08-30 10:22:25.155  1036  1523 E WifiStateMachine:  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
08-30 10:22:25.168   316  8477 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,08-30 10:22:25.168   316  8477 D libc-netbsd: res_queryN name = www.google.com, class = 1, type = 1
08-30 10:22:25.200   316  8477 D libc-netbsd: res_queryN name = www.google.com succeed
,08-30 10:22:25.206   316  8480 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-30 10:22:25.207   316  8480 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-30 10:22:25.207   316  8480 D libc-netbsd: res_queryN name = clients3.google.com succeed
08-30 10:22:25.265  1036  1526 V WifiInternetCheck: isHttpConnectionAvailable - We got a valid response : 204
,08-30 10:22:25.308  1036  2307 I art     : Explicit concurrent mark sweep GC freed 76524(3MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/65MB, paused 3.366ms total 154.430ms
,08-30 10:22:25.353  1036  2002 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=8482 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,08-30 10:22:25.355  1036  2002 I ActivityManager: Killing 7807:com.android.gallery3d/u0a27 (adj 15): empty #17
08-30 10:22:25.406  1826  8481 I CheckinService: active receiver: enabled
08-30 10:22:25.406  1036  2075 W libprocessgroup: failed to open /acct/uid_10027/pid_7807/cgroup.procs: No such file or directory
,08-30 10:22:25.420  1826  8481 I CheckinService: Preparing to send checkin request
08-30 10:22:25.420  1826  8481 I EventLogService: Accumulating logs since 1472545305306
,08-30 10:22:25.468  1826  8481 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,08-30 10:22:25.556  1036  1952 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=8500 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-30 10:22:25.557  1036  1952 I ActivityManager: Killing 7875:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,08-30 10:22:25.578   348   348 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 433us total 23.021ms
,08-30 10:22:25.599   348   348 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 412us total 19.331ms
,08-30 10:22:25.617   348   348 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 364us total 17.427ms
,08-30 10:22:25.623  1036  1052 W libprocessgroup: failed to open /acct/uid_10080/pid_7875/cgroup.procs: No such file or directory
08-30 10:22:25.650  8500  8500 I art     : Almond Protected OAT
,08-30 10:22:25.702  1036  1052 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=8517 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,08-30 10:22:25.726  8500  8500 D WeatherApplication: removeAccount
08-30 10:22:25.728  8500  8500 D WeatherApplication: Account.length = 0
08-30 10:22:25.728  8500  8500 E WeatherApplication: OPERATOR:OPEN
,08-30 10:22:25.740  8500  8500 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 10:22:25
08-30 10:22:25.745  8500  8500 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-30 10:22:25.745  8500  8500 D Weather.Utils: 2 : All the weather widget is gone.
08-30 10:22:25.747  8500  8500 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-30 10:22:25.750  8500  8500 D WeatherAncestor: connectivity changed - connection : true
,08-30 10:22:25.751  8500  8500 D WeatherService: 2 : isServiceAlived():false forecastCache:null
08-30 10:22:25.758  8517  8517 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,08-30 10:22:25.758  8517  8517 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
08-30 10:22:25.760  8500  8500 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-30 10:22:25.760  8500  8500 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-30 10:22:25.760  8500  8500 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
08-30 10:22:25.779  8500  8500 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-30 10:22:25.779  8500  8500 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 10:22:25
,08-30 10:22:25.791  8517  8517 I MultiDex: VM with version 2.1.0 has multidex support
08-30 10:22:25.791  8517  8517 I MultiDex: install
08-30 10:22:25.791  8517  8517 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-30 10:22:25.831  1036  1763 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=8536 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-30 10:22:25.833  1036  1763 I ActivityManager: Killing 7829:com.android.vending/u0a44 (adj 15): empty #17
,08-30 10:22:25.947  1036  2305 W libprocessgroup: failed to open /acct/uid_10044/pid_7829/cgroup.procs: No such file or directory
,08-30 10:22:25.971  8517  8517 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,08-30 10:22:26.048  2229  2247 I art     : Explicit concurrent mark sweep GC freed 9731(587KB) AllocSpace objects, 4(64KB) LOS objects, 52% free, 29MB/61MB, paused 1.681ms total 37.084ms
,08-30 10:22:26.079   280   340 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-30 10:22:26.079   280   340 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-30 10:22:26.079   280   340 W Vold    : Returning OperationFailed - no handler for errno 0
08-30 10:22:26.081  8536  8559 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,08-30 10:22:26.083   280   340 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-30 10:22:26.083   280   340 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-30 10:22:26.083   280   340 W Vold    : Returning OperationFailed - no handler for errno 0
08-30 10:22:26.084  8536  8559 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-30 10:22:26.101   280   340 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,08-30 10:22:26.101   280   340 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-30 10:22:26.101   280   340 W Vold    : Returning OperationFailed - no handler for errno 0
08-30 10:22:26.101  8536  8562 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-30 10:22:26.105   280   340 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-30 10:22:26.105   280   340 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-30 10:22:26.105   280   340 W Vold    : Returning OperationFailed - no handler for errno 0
08-30 10:22:26.106  8536  8562 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-30 10:22:26.327  8517  8553 D LgDataFeature: LgDataFeature() Constructor: none
08-30 10:22:26.327  8517  8553 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 10:22:26.338  8536  8536 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
08-30 10:22:26.346  8536  8536 I LibraryLoader: Loading: webviewchromium
,08-30 10:22:26.349  8536  8536 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 4054-4057)
08-30 10:22:26.350  8536  8536 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-30 10:22:26.357  8536  8536 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2a68d521}
08-30 10:22:26.360  8536  8536 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-30 10:22:26.361  8536  8536 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,08-30 10:22:26.385  8536  8536 I BrowserStartupController: Initializing chromium process, renderers=0
08-30 10:22:26.386  8536  8536 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-30 10:22:26.399   321  4055 V AudioPolicyService: registerClient() client 0xb0403e40, uid 10093
,08-30 10:22:26.402  8536  8536 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,08-30 10:22:26.403  8536  8585 W AudioManagerAndroid: Requires BLUETOOTH permission
08-30 10:22:26.403  8536  8536 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
08-30 10:22:26.404  8536  8536 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
08-30 10:22:26.423  8536  8536 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-30 10:22:26.423  8536  8536 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-30 10:22:26.423  8536  8536 I Adreno-EGL: Build Date: 12/12/14 금
08-30 10:22:26.423  8536  8536 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-30 10:22:26.423  8536  8536 I Adreno-EGL: Remote Branch: 
08-30 10:22:26.423  8536  8536 I Adreno-EGL: Local Patches: 
08-30 10:22:26.423  8536  8536 I Adreno-EGL: Reconstruct Branch: 
,08-30 10:22:26.490  8536  8536 I NSApplication: Starting up...
,08-30 10:22:26.493  8593  8593 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=32 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
08-30 10:22:26.514  1036  1951 I ActivityManager: Killing 7566:com.lge.lifetracker/u0a37 (adj 15): empty #17
,08-30 10:22:26.547  8593  8593 I dex2oat : dex2oat took 53.188ms (threads: 4)
,08-30 10:22:26.560  8517  8553 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-30 10:22:26.560  8517  8553 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-30 10:22:26.560  8517  8553 I Adreno-EGL: Build Date: 12/12/14 금
08-30 10:22:26.560  8517  8553 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-30 10:22:26.560  8517  8553 I Adreno-EGL: Remote Branch: 
08-30 10:22:26.560  8517  8553 I Adreno-EGL: Local Patches: 
08-30 10:22:26.560  8517  8553 I Adreno-EGL: Reconstruct Branch: 
,08-30 10:22:26.573  1036  1561 W libprocessgroup: failed to open /acct/uid_10037/pid_7566/cgroup.procs: No such file or directory
,08-30 10:22:26.597  2229  2229 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,08-30 10:22:26.609  2229  2229 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
08-30 10:22:26.609  2229  2229 D c       : Getting all permits...
08-30 10:22:26.609  2229  2229 D a       : Opening database...
,08-30 10:22:26.614  2229  2229 D a       : Opening database auth.proximity.permit_store...
08-30 10:22:26.615  2229  2229 D a       : Closing database...
08-30 10:22:26.693  8517  8553 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-30 10:22:26.693  8517  8553 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-30 10:22:26.693  8517  8553 I Adreno-EGL: Build Date: 12/12/14 금
08-30 10:22:26.693  8517  8553 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-30 10:22:26.693  8517  8553 I Adreno-EGL: Remote Branch: 
08-30 10:22:26.693  8517  8553 I Adreno-EGL: Local Patches: 
08-30 10:22:26.693  8517  8553 I Adreno-EGL: Reconstruct Branch: 
,08-30 10:22:26.779  6615  8382 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
08-30 10:22:26.779  6615  8382 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
08-30 10:22:26.780  6615  8382 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-30 10:22:26.781  6615  8382 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-30 10:22:26.782  6615  8382 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
08-30 10:22:26.784  6615  8608 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
08-30 10:22:26.784  6615  8608 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
08-30 10:22:26.787  6615  8610 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 857, name: OutgoingSocketThread/Sender)
08-30 10:22:26.787  6615  8608 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-30 10:22:26.790  6615  8608 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-30 10:22:26.791  6615  8608 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
08-30 10:22:26.792  6615  8611 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 858, name: OutgoingSocketThread/Receiver)
08-30 10:22:26.793  6615  8611 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 858, thread name: OutgoingSocketThread/Receiver)
08-30 10:22:26.794  6615  8611 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
08-30 10:22:26.794  6615  8611 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 858, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,08-30 10:22:26.795  6615  8612 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 859, name: IncomingSocketThread/Sender)
08-30 10:22:26.799  6615  8613 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 860, name: IncomingSocketThread/Receiver)
08-30 10:22:26.800  6615  8613 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 860, thread name: IncomingSocketThread/Receiver)
08-30 10:22:26.800  6615  8613 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
08-30 10:22:26.800  6615  8613 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 860, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
08-30 10:22:26.801  1036  1523 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2437 sc=60 link=72 tx=42.0, 0.0, 0.0  rx=36.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-628435727] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-30 10:22:26.802  1036  1523 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2437 sc=60 link=72 tx=42.0, 0.0, 0.0  rx=36.8 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-628435726] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-30 10:22:26.802  1036  1523 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-30 10:22:26.826  8517  8553 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-30 10:22:26.826  8517  8553 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-30 10:22:26.826  8517  8553 I Adreno-EGL: Build Date: 12/12/14 금
08-30 10:22:26.826  8517  8553 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-30 10:22:26.826  8517  8553 I Adreno-EGL: Remote Branch: 
08-30 10:22:26.826  8517  8553 I Adreno-EGL: Local Patches: 
08-30 10:22:26.826  8517  8553 I Adreno-EGL: Reconstruct Branch: 
,08-30 10:22:27.047   316  8618 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-30 10:22:27.048   316  8618 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
,08-30 10:22:27.105   316  8618 D libc-netbsd: res_queryN name = android.clients.google.com succeed
,08-30 10:22:27.218  1826  8481 I CheckinTask: Sending checkin request (7857 bytes)
,08-30 10:22:27.484  1826  8481 I CheckinTask: Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,08-30 10:22:27.499  1826  8481 I CheckinService: active receiver: disabled
,08-30 10:22:27.528  2229  2229 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,08-30 10:22:27.548  2229  2229 I GCM     : GCM config loaded
,08-30 10:22:27.566  8441  8441 V SetupWizard: Connected to Gservices successfully
,08-30 10:22:27.860  7780  8374 D UEI.SmartControl: Internal timer expired: 4
,08-30 10:22:27.860  7780  8374 D UEI.SmartControl: unbind internal service
,08-30 10:22:27.929  7780  8368 D serial_port: close(fd = 24)
,08-30 10:22:27.938  7780  8368 I UEI.SmartControl: Serial port is closed.
,08-30 10:22:29.784  6615  6733 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-30 10:22:29.785  6615  6733 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-30 10:22:29.792  6615  6733 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@6915a70 Bundle[{}]
08-30 10:22:29.793  6615  6733 I io.jxcore.node.LifeCycleMonitor: start: OK
08-30 10:22:29.793  6615  6733 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-30 10:22:29.794  6615  6733 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-30 10:22:29.795  6615  6733 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-30 10:22:29.795  6615  6733 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-30 10:22:29.796  6615  6733 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-30 10:22:29.803  6615  6733 I System.out: Running OutgoingSocketThread
,08-30 10:22:29.808  6615  8627 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
08-30 10:22:29.808  6615  8627 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
08-30 10:22:29.817  1036  1523 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2437 sc=60 link=72 tx=31.5, 0.0, 0.0  rx=27.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-628432712] gl rssi=-46 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-30 10:22:29.818  1036  1523 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2437 sc=60 link=72 tx=31.5, 0.0, 0.0  rx=27.4 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-628432711] gl rssi=-46 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-30 10:22:29.818  1036  1523 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-30 10:22:31.113  8536  8563 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,08-30 10:22:32.050  1036  2305 I ActivityManager: Killing 7627:com.lge.settings.easy/1000 (adj 15): empty #17
,08-30 10:22:32.084  1036  1729 W libprocessgroup: failed to open /acct/uid_1000/pid_7627/cgroup.procs: No such file or directory
,08-30 10:22:32.819  6615  8627 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
,08-30 10:22:32.819  6615  8627 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
08-30 10:22:32.820  6615  8627 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-30 10:22:32.820  6615  8627 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-30 10:22:32.821  6615  8627 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,08-30 10:22:32.829  6615  8630 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
08-30 10:22:32.829  6615  8630 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
08-30 10:22:32.829  6615  8630 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-30 10:22:32.829  6615  8630 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-30 10:22:32.829  6615  8630 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
08-30 10:22:32.832  6615  8633 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 870, name: OutgoingSocketThread/Receiver)
08-30 10:22:32.832  6615  8633 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 870, thread name: OutgoingSocketThread/Receiver)
08-30 10:22:32.832  6615  8633 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
08-30 10:22:32.832  6615  8633 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 870, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
08-30 10:22:32.835  6615  8632 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 869, name: OutgoingSocketThread/Sender)
08-30 10:22:32.838  1036  1523 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2437 sc=60 link=72 tx=22.8, 0.0, 0.0  rx=18.7 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-628429691] gl rssi=-46 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-30 10:22:32.839  1036  1523 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2437 sc=60 link=72 tx=22.8, 0.0, 0.0  rx=18.7 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-628429690] gl rssi=-46 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-30 10:22:32.839  1036  1523 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-30 10:22:32.843  6615  8635 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 872, name: IncomingSocketThread/Receiver)
,08-30 10:22:32.845  6615  8634 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 871, name: IncomingSocketThread/Sender)
08-30 10:22:32.845  6615  8635 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 872, thread name: IncomingSocketThread/Receiver)
08-30 10:22:32.845  6615  8635 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
08-30 10:22:32.845  6615  8635 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 872, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
08-30 10:22:35.488  1586  1586 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,08-30 10:22:35.552  1036  1414 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-30 10:22:35.606  1036  1104 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=8636 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-30 10:22:35.608  2081  2081 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
08-30 10:22:35.614  1036  1036 D administrator: Handling package changes for user 0
08-30 10:22:35.646  1586  1586 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
08-30 10:22:35.648  1586  1586 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
08-30 10:22:35.654  2081  2081 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-30 10:22:35.696  8636  8636 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-30 10:22:35.721  1036  1036 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
,08-30 10:22:35.721  1036  1036 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-30 10:22:35.759  8636  8636 D LgDataFeature: LgDataFeature() Constructor: none
08-30 10:22:35.759  8636  8636 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 10:22:35.801  1036  1102 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-30 10:22:35.806  1036  1102 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-30 10:22:35.810  6615  6733 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 881)
08-30 10:22:35.810  6615  6733 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-30 10:22:35.810  6615  6733 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 882)
08-30 10:22:35.812  2081  2081 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,08-30 10:22:35.813  6615  6733 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 10:22:35.813  6615  6733 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b0076b8 added. We now have 3 listener(s)
08-30 10:22:35.814  1036  1052 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 10:22:35.815  2438  2438 V GmsNetworkLocationProvi: DISABLE
08-30 10:22:35.816  6615  6733 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 10:22:35.816  6615  6733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 10:22:35.816  6615  6733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 10:22:35.816  6615  6733 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 10:22:35.816  6615  6733 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2daecc91 added. We now have 4 listener(s)
08-30 10:22:35.816  6615  6733 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 10:22:35.817  6615  6733 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 10:22:35.819  6615  6733 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 10:22:35.823  6615  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 10:22:35.823  6615  6733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 10:22:35.823  6615  6733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 10:22:35.823  6615  6733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 10:22:35.823  6615  6733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 10:22:35.823  6615  6733 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 10:22:35.823  6615  6733 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 10:22:35.823  6615  6733 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 10:22:35.825  6615  6733 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 10:22:35.825  6615  6733 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 10:22:35.825  6615  6733 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 10:22:35.825  6615  6733 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 10:22:35.825  6615  6733 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-30 10:22:35.825  6615  6733 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 10:22:35.825  6615  6733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 10:22:35.825  6615  6733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 10:22:35.825  6615  6733 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 10:22:35.825  6615  6733 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b0076b8 removed from the list
08-30 10:22:35.825  6615  6733 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 10:22:35.825  6615  6733 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2daecc91 removed from the list
08-30 10:22:35.826  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 10:22:35.826  6615  6733 D io.jxcore.node.ConnectivityMonitor: stop
08-30 10:22:35.826  6615  6733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 10:22:35.828  6615  6733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 10:22:35.828  6615  6733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 10:22:35.832  6615  6733 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 10:22:35.832  6615  6733 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 10:22:35.832  6615  6733 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 10:22:35.832  6615  6733 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2daecc91 not in the list
08-30 10:22:35.832  6615  6733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 10:22:35.832  6615  6733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 10:22:35.832  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 10:22:35.832  6615  6733 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 10:22:35.832  6615  6733 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 10:22:35.832  6615  6733 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 10:22:35.832  6615  6733 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2daecc91 not in the list
08-30 10:22:35.832  6615  6733 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 10:22:35.832  6615  6733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 10:22:35.832  6615  6733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 10:22:35.832  6615  6733 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b0076b8 not in the list
08-30 10:22:35.833  6615  6733 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 10:22:35.833  6615  6733 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d5f37f7 added. We n,ow have 3 listener(s)
08-30 10:22:35.835  1036  1764 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 10:22:35.837  6615  6733 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 10:22:35.837  6615  6733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 10:22:35.837  6615  6733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 10:22:35.837  6615  6733 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 10:22:35.837  6615  6733 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34a24664 added. We now have 4 listener(s)
08-30 10:22:35.837  6615  6733 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 10:22:35.838  6615  6733 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 10:22:35.839  6615  6733 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 10:22:35.843  6615  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 10:22:35.843  6615  6733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 10:22:35.843  6615  6733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 10:22:35.843  6615  6733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 10:22:35.843  6615  6733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 10:22:35.843  6615  6733 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 10:22:35.843  6615  6733 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 10:22:35.843  6615  6733 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 10:22:35.844  6615  6733 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 10:22:35.844  6615  6733 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 10:22:35.844  6615  6733 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 10:22:35.844  6615  6733 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 10:22:35.844  6615  6733 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 10:22:35.844  6615  6733 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 10:22:35.844  6615  6733 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 10:22:35.847  6615  6733 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-30 10:22:35.847  1036  2002 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 10:22:35.847  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 10:22:35.849  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 10:22:35.850  6615  6733 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-30 10:22:35.851  6615  6733 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-30 10:22:35.852  6615  6733 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 10:22:35.853  6615  6733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 10:22:35.854  6615  6733 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-30 10:22:35.854  6615  6733 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 10:22:35.854  6615  6733 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 10:22:35.856  1036  1102 D LocationProviderProxy: applying state to connected service
08-30 10:22:35.858  2438  2438 E GCoreFlp: Bound FusedProviderService with LocationManager
08-30 10:22:35.858  1036  1523 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2437 sc=60 link=72 tx=11.9, 0.0, 0.0  rx=9.3 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-628426670] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-30 10:22:35.859  1036  1523 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2437 sc=60 link=72 tx=11.9, 0.0, 0.0  rx=9.3 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-628426669] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-30 10:22:35.859  1036  1523 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-30 10:22:35.871  8636  8681 I Babel   : MmsConfig: mnc/mcc: 0/0
08-30 10:22:35.871  8636  8681 I Babel   : MmsConfig.loadMmsSettings
,08-30 10:22:35.873  8636  8681 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-30 10:22:35.873  8636  8681 I Babel   : MmsConfig.loadFromDatabase
,08-30 10:22:35.884  8636  8681 E Babel   : canonicalizeMccMnc: invalid mccmnc 
08-30 10:22:35.884  8636  8681 I Babel   : MmsConfig.loadFromResources
08-30 10:22:35.888  8636  8681 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
08-30 10:22:35.891  8636  8681 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
,08-30 10:22:35.905  8636  8636 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 10:22:35.910  8636  8679 W AudioCapabilities: Unsupported mime audio/evrc
08-30 10:22:35.911  8636  8679 W AudioCapabilities: Unsupported mime audio/qcelp
08-30 10:22:35.913  8636  8679 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-30 10:22:35.926  8636  8679 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
,08-30 10:22:35.928  8636  8679 W AudioCapabilities: Unsupported mime audio/qcelp
08-30 10:22:35.934  8636  8679 W AudioCapabilities: Unsupported mime audio/evrc
08-30 10:22:35.942  1826  8684 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
08-30 10:22:35.942  1826  8684 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
,08-30 10:22:35.951  7078  7078 I AppUp4:CustModeStarterReceiver: onReceive
08-30 10:22:35.954  7078  7078 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@3af539be
08-30 10:22:35.954  7078  7078 D AppUp4:CustFacade: isCustomizationCompleted : false
08-30 10:22:35.954  7078  7078 D AppUp4:CustFacade: isPhone : true
08-30 10:22:35.955  7078  7078 D AppUp4:CustModeStarterReceiver: begin check event
08-30 10:22:35.955  7078  7078 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
08-30 10:22:35.956  1826  4822 I Icing   : updateResources: need to parse e{com.google.android.gms}
08-30 10:22:35.978  8636  8679 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-30 10:22:35.982  8636  8679 W VideoCapabilities: Unsupported mime video/divx
08-30 10:22:35.984  8636  8679 W VideoCapabilities: Unsupported mime video/divx311
08-30 10:22:35.992  8636  8679 W VideoCapabilities: Unsupported mime video/divx4
,08-30 10:22:35.998  8636  8679 W VideoCapabilities: Unsupported mime video/mp4v-esdp
08-30 10:22:36.013  1036  1763 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=8687 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,08-30 10:22:36.016  8636  8679 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
08-30 10:22:36.018  1036  1951 I ActivityManager: Killing 8240:com.lge.bnr/1000 (adj 15): empty #17
08-30 10:22:36.023  8636  8679 W AudioCapabilities: Unsupported mime audio/eac3
08-30 10:22:36.024  8636  8679 W AudioCapabilities: Unsupported mime audio/ac3
08-30 10:22:36.024  8636  8679 W AudioCapabilities: Unsupported mime audio/g726
08-30 10:22:36.025  8636  8679 W AudioCapabilities: Unsupported mime audio/wma-voice
,08-30 10:22:36.027  8636  8679 W AudioCapabilities: Unsupported mime audio/x-ms-wma
08-30 10:22:36.028  8636  8679 W AudioCapabilities: Unsupported mime audio/adpcm
08-30 10:22:36.030  8636  8679 W VideoCapabilities: Unsupported mime video/theora
08-30 10:22:36.032  8636  8679 W VideoCapabilities: Unsupported mime video/mjpg
08-30 10:22:36.102  1036  2307 W libprocessgroup: failed to open /acct/uid_1000/pid_8240/cgroup.procs: No such file or directory
,08-30 10:22:36.145  8687  8687 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 10:22:36.145  8687  8687 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-30 10:22:36.145  8687  8687 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-30 10:22:36.147  8687  8687 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
08-30 10:22:36.147  8687  8687 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,08-30 10:22:36.230  8687  8687 I SystemConfig: BUILD Country: EU
08-30 10:22:36.231  8687  8687 I SystemConfig: BUILD Operator: OPEN
,08-30 10:22:36.282  1036  2075 I ActivityManager: Killing 8184:com.lge.sync/1000 (adj 15): empty #17
,08-30 10:22:36.368  1036  1051 W libprocessgroup: failed to open /acct/uid_1000/pid_8184/cgroup.procs: No such file or directory
,08-30 10:22:36.380  8687  8708 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
08-30 10:22:36.381  8687  8708 I SystemConfig: existFile = false
,08-30 10:22:36.381  8687  8708 I SystemConfig: canReadFile = false
08-30 10:22:36.382  8687  8708 I SystemConfig: systemFeature RCS result false
08-30 10:22:36.383  8687  8708 D SystemConfig: refreshRcsSupport() :false
08-30 10:22:36.430  1036  2075 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=8710 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,08-30 10:22:36.477  8710  8710 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 10:22:36.477  8710  8710 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-30 10:22:36.477  8710  8710 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-30 10:22:36.478  8710  8710 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-30 10:22:36.570  8710  8710 I AppConfig: Total System Memory = 2995761152
,08-30 10:22:36.583  8710  8710 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
,08-30 10:22:36.670  1036  2054 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=8732 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
08-30 10:22:36.672  1036  2054 I ActivityManager: Killing 6890:com.android.settings/1000 (adj 15): empty #17
08-30 10:22:36.732  1036  2080 W libprocessgroup: failed to open /acct/uid_1000/pid_6890/cgroup.procs: No such file or directory
,08-30 10:22:36.924  8732  8732 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,08-30 10:22:37.003  8732  8732 D LgDataFeature: LgDataFeature() Constructor: none
,08-30 10:22:37.003  8732  8732 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 10:22:37.075  8732  8732 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,08-30 10:22:37.102  8732  8732 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-30 10:22:37.104  8732  8732 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
08-30 10:22:37.121  8732  8732 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-30 10:22:37.121  8732  8732 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,08-30 10:22:37.155  1036  1561 I ActivityManager: Killing 7780:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,08-30 10:22:37.162  3486  3501 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
08-30 10:22:37.167  3486  3501 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@332ae8e7 on behalf of 8732
08-30 10:22:37.171  8320  8320 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
08-30 10:22:37.171  8320  8320 W System.err: android.os.DeadObjectException
08-30 10:22:37.172  8320  8320 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-30 10:22:37.172  8320  8320 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-30 10:22:37.172  8320  8320 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-30 10:22:37.172  8320  8320 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-30 10:22:37.172  8320  8320 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-30 10:22:37.172  8320  8320 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-30 10:22:37.172  8320  8320 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-30 10:22:37.172  8320  8320 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-30 10:22:37.172  8320  8320 W System.err: 	at android.os.Looper.loop(Looper.java:135)
,08-30 10:22:37.172  8320  8320 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-30 10:22:37.172  8320  8320 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 10:22:37.172  8320  8320 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 10:22:37.172  8320  8320 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-30 10:22:37.172  8320  8320 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-30 10:22:37.172  8320  8320 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-30 10:22:37.173  8320  8320 W System.err: android.os.DeadObjectException
08-30 10:22:37.173  8320  8320 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-30 10:22:37.173  8320  8320 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-30 10:22:37.173  8320  8320 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-30 10:22:37.173  8320  8320 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-30 10:22:37.173  8320  8320 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-30 10:22:37.173  8320  8320 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-30 10:22:37.173  8320  8320 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-30 10:22:37.173  8320  8320 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-30 10:22:37.173  8320  8320 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-30 10:22:37.173  8320  8320 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-30 10:22:37.173  8320  8320 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 10:22:37.173  8320  8320 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 10:22:37.173  8320  8320 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-30 10:22:37.173  8320  8320 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-30 10:22:37.173  8320  8320 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-30 10:22:37.174  8320  8320 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
,08-30 10:22:37.220   278   278 E lowmemorykiller: Error opening /proc/7780/oom_score_adj; errno=2
,08-30 10:22:37.229  1036  1052 W ActivityManager: Exception when unbinding service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service
08-30 10:22:37.229  1036  1052 W ActivityManager: android.os.DeadObjectException
08-30 10:22:37.229  1036  1052 W ActivityManager: 	at android.os.BinderProxy.transactNative(Native Method)
08-30 10:22:37.229  1036  1052 W ActivityManager: 	at android.os.BinderProxy.transact(Binder.java:496)
08-30 10:22:37.229  1036  1052 W ActivityManager: 	at android.app.ApplicationThreadProxy.scheduleUnbindService(ApplicationThreadNative.java:917)
08-30 10:22:37.229  1036  1052 W ActivityManager: 	at com.android.server.am.ActiveServices.removeConnectionLocked(ActiveServices.java:1776)
08-30 10:22:37.229  1036  1052 W ActivityManager: 	at com.android.server.am.ActiveServices.unbindServiceLocked(ActiveServices.java:901)
08-30 10:22:37.229  1036  1052 W ActivityManager: 	at com.android.server.am.ActivityManagerService.unbindService(ActivityManagerService.java:15417)
08-30 10:22:37.229  1036  1052 W ActivityManager: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:963)
08-30 10:22:37.229  1036  1052 W ActivityManager: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2560)
08-30 10:22:37.229  1036  1052 W ActivityManager: 	at com.android.server.am.ActivityManagerServiceEx.onTransact(ActivityManagerServiceEx.java:421)
08-30 10:22:37.229  1036  1052 W ActivityManager: 	at android.os.Binder.execTransact(Binder.java:446)
08-30 10:22:37.234  1036  2022 W libprocessgroup: failed to open /acct/uid_1000/pid_7780/cgroup.procs: No such file or directory
,08-30 10:22:37.235  8320  8320 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-30 10:22:37.237  8320  8320 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
,08-30 10:22:37.257  4652  8775 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,08-30 10:22:37.324  1036  1951 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=8776 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-30 10:22:37.326  8320  8320 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-30 10:22:37.398  1036  1729 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=8794 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,08-30 10:22:37.424  8732  8732 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,08-30 10:22:37.456  8732  8732 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
08-30 10:22:37.473  8776  8776 D UEI.SmartControl: Quickset Services start...
,08-30 10:22:37.476  8776  8776 I UEI.SmartControl: Manufacture = LGE
08-30 10:22:37.476  8776  8776 D UEI.SmartControl: Id = LGNevo
08-30 10:22:37.477  8776  8776 D UEI.SmartControl: File observer start...
08-30 10:22:37.480  8776  8776 E UEI.SmartControl: IR Port is disabled: false
08-30 10:22:37.480  8776  8776 D UEI.SmartControl: Starting file observer...
08-30 10:22:37.481  8776  8776 D UEI.SmartControl: Extracting JNI libs...
08-30 10:22:37.481  8776  8776 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
08-30 10:22:37.491  8794  8794 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,08-30 10:22:37.524  8794  8794 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
08-30 10:22:37.524  8794  8794 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
08-30 10:22:37.524  8794  8794 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
08-30 10:22:37.524  8794  8794 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
08-30 10:22:37.524  8794  8794 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
08-30 10:22:37.524  8794  8794 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
,08-30 10:22:37.543  1036  1561 I ActivityManager: Killing 8320:com.lge.qremote/u0a112 (adj 15): empty #17
,08-30 10:22:37.581  8776  8776 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,08-30 10:22:37.582  8776  8776 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-30 10:22:37.582  8776  8776 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
08-30 10:22:37.607  8776  8776 I UEI.SmartControl: --- Selecting new region: 6
08-30 10:22:37.609  8776  8776 I UEI.SmartControl: Model = LG-D855
,08-30 10:22:37.610  8776  8776 D UEI.SmartControl: QS Service created
,08-30 10:22:37.645  1036  1952 W libprocessgroup: failed to open /acct/uid_10112/pid_8320/cgroup.procs: No such file or directory
,08-30 10:22:37.677  8776  8776 I UEI.SmartControl: Service initServices...
,08-30 10:22:37.683  8776  8776 D UEI.SmartControl: QS start get config
,08-30 10:22:37.769  8776  8776 D UEI.SmartControl: Loading JNI Libs...
,08-30 10:22:37.823  1036  1764 V SIM_STK : Menu title from STK is T-Mobile
,08-30 10:22:37.834  4652  8775 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 577 ms] updated apps [took 577 ms] 
,08-30 10:22:38.068  8776  8776 I UEI.SmartControl: Supports setup maps: true
,08-30 10:22:38.072  8776  8776 D UEI.SmartControl: QS start statue = true Error code = 0
08-30 10:22:38.072  8776  8776 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-30 10:22:38.072  8776  8776 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-30 10:22:38.072  8776  8776 I UEI.SmartControl: ### init IR Blaster...
08-30 10:22:38.078  8776  8776 D serial_port: Configuring serial port
08-30 10:22:38.082  8776  8776 E UEI.SmartControl: UEIBLaster setting for 616
08-30 10:22:38.082  8776  8776 I UEI.SmartControl: Setting serial record hearder size = 2
08-30 10:22:38.083  8776  8776 I UEI.SmartControl: configuring settings for MAXQ616
08-30 10:22:38.084  8776  8776 I UEI.SmartControl: Get version...
,08-30 10:22:38.100  8776  8827 D UEI.SmartControl: serial port data available: 21
,08-30 10:22:38.128  8776  8776 D UEI.SmartControl: MAXQ616 A2-X4 software.
,08-30 10:22:38.128  8776  8776 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-30 10:22:38.128  8776  8776 I UEI.SmartControl: QS saving settings...
08-30 10:22:38.130  8776  8776 D UEI.SmartControl: IR Blaster version: 25672567
,08-30 10:22:38.147  8776  8827 D UEI.SmartControl: serial port data available: 4
,08-30 10:22:38.181  8776  8830 I UEI.SmartControl: Device manager: loading config....
,08-30 10:22:38.182  8776  8830 D UEI.SmartControl: ----------- loading internal config...
,08-30 10:22:38.192  8776  8776 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-30 10:22:38.204  8776  8830 E UEI.SmartControl: Loading SETTINGS...
,08-30 10:22:38.213  8776  8830 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-30 10:22:38.231  8776  8829 I UEI.SmartControl: Notify AllClients services are ready: 0
,08-30 10:22:38.231  8776  8829 D UEI.SmartControl: -----service ready thread exits
08-30 10:22:38.342  1036  1951 I art     : Explicit concurrent mark sweep GC freed 33246(1682KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/65MB, paused 2.379ms total 142.704ms
,08-30 10:22:38.349  8776  8776 E UEI.SmartControl: Services init done
08-30 10:22:38.349  8776  8776 D UEI.SmartControl: QS Service init finished
08-30 10:22:38.351  8776  8776 D UEI.SmartControl: QS Service version name: 2.1.91
08-30 10:22:38.351  8776  8776 D UEI.SmartControl: QS Service version code: 201091
08-30 10:22:38.353  8776  8776 D UEI.SmartControl: Service requested: Control
08-30 10:22:38.354  8776  8776 D UEI.SmartControl: Service.onUnbind: IControl
08-30 10:22:38.356  8776  8776 D UEI.SmartControl: unbind internal service
,08-30 10:22:38.358  8776  8776 D UEI.SmartControl: Service.onDestroy
08-30 10:22:38.358  8776  8776 D UEI.SmartControl: Lock is in USE false
08-30 10:22:38.358  8776  8776 D UEI.SmartControl: unbind internal service
08-30 10:22:38.364  8776  8776 D serial_port: close(fd = 25)
08-30 10:22:38.367  8776  8776 I UEI.SmartControl: Serial port is closed.
08-30 10:22:38.367  8776  8776 I UEI.SmartControl: Serial port is closed.
08-30 10:22:38.367  8776  8776 D UEI.SmartControl: Blaster closed
08-30 10:22:38.367  8776  8776 D UEI.SmartControl: Shut down QS...
08-30 10:22:38.367  8776  8776 D UEI.SmartControl: Stopping QS lib
08-30 10:22:38.367  8776  8776 D UEI.SmartControl: QS lib stop result = true
08-30 10:22:38.367  8776  8776 D UEI.SmartControl: Stopped QS lib
08-30 10:22:38.368  8776  8776 D UEI.SmartControl: Stopped file observer...
08-30 10:22:38.368  8776  8776 D UEI.SmartControl: QS shutdown complete
08-30 10:22:38.368  8776  8776 D UEI.SmartControl: QS Service created
08-30 10:22:38.377  8776  8776 I UEI.SmartControl: Service initServices...
08-30 10:22:38.377  8776  8776 D UEI.SmartControl: QS start get config
,08-30 10:22:38.642  8776  8776 I UEI.SmartControl: Supports setup maps: true
,08-30 10:22:38.645  8776  8776 D UEI.SmartControl: QS start statue = true Error code = 0
08-30 10:22:38.645  8776  8776 I UEI.SmartControl: QS version = v2.7.10.1_RC1
,08-30 10:22:38.645  8776  8776 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-30 10:22:38.645  8776  8776 I UEI.SmartControl: ### init IR Blaster...
,08-30 10:22:38.651  8776  8776 D serial_port: Configuring serial port
,08-30 10:22:38.651  8776  8776 E UEI.SmartControl: UEIBLaster setting for 616
08-30 10:22:38.651  8776  8776 I UEI.SmartControl: Setting serial record hearder size = 2
,08-30 10:22:38.651  8776  8776 I UEI.SmartControl: configuring settings for MAXQ616
08-30 10:22:38.651  8776  8776 I UEI.SmartControl: Get version...
,08-30 10:22:38.668  8776  8832 D UEI.SmartControl: serial port data available: 21
,08-30 10:22:38.694  8776  8776 D UEI.SmartControl: MAXQ616 A2-X4 software.
,08-30 10:22:38.694  8776  8776 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-30 10:22:38.694  8776  8776 I UEI.SmartControl: QS saving settings...
08-30 10:22:38.696  8776  8776 D UEI.SmartControl: IR Blaster version: 25672567
,08-30 10:22:38.713  8776  8832 D UEI.SmartControl: serial port data available: 4
,08-30 10:22:38.747  8776  8835 I UEI.SmartControl: Device manager: loading config....
,08-30 10:22:38.747  8776  8835 D UEI.SmartControl: ----------- loading internal config...
08-30 10:22:38.749  8776  8776 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-30 10:22:38.752  8776  8776 E UEI.SmartControl: Services init done
08-30 10:22:38.752  8776  8776 D UEI.SmartControl: QS Service init finished
,08-30 10:22:38.762  8776  8776 D UEI.SmartControl: QS Service version name: 2.1.91
,08-30 10:22:38.762  8776  8776 D UEI.SmartControl: QS Service version code: 201091
08-30 10:22:38.764  8776  8776 D UEI.SmartControl: Service requested: Control
,08-30 10:22:38.766  8776  8835 E UEI.SmartControl: Loading SETTINGS...
08-30 10:22:38.771  8776  8776 D UEI.SmartControl: Request IControl service: devices are loaded...
,08-30 10:22:38.778  1036  2075 I ActivityManager: Killing 8406:com.lge.email/u0a23 (adj 15): empty #17
,08-30 10:22:38.785  8776  8835 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-30 10:22:38.807  8776  8834 I UEI.SmartControl: Notify AllClients services are ready: 0
08-30 10:22:38.807  8776  8834 D UEI.SmartControl: -----service ready thread exits
,08-30 10:22:38.814  1036  1052 W libprocessgroup: failed to open /acct/uid_10023/pid_8406/cgroup.procs: No such file or directory
,08-30 10:22:38.816  8776  8776 E ActivityThread: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.g@26c733ca that was originally bound here
08-30 10:22:38.816  8776  8776 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.g@26c733ca that was originally bound here
08-30 10:22:38.816  8776  8776 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1167)
08-30 10:22:38.816  8776  8776 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1061)
08-30 10:22:38.816  8776  8776 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1839)
08-30 10:22:38.816  8776  8776 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:1822)
08-30 10:22:38.816  8776  8776 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
08-30 10:22:38.816  8776  8776 E ActivityThread: 	at com.uei.control.Service.b(Unknown Source)
08-30 10:22:38.816  8776  8776 E ActivityThread: 	at com.uei.control.Service.a(Unknown Source)
08-30 10:22:38.816  8776  8776 E ActivityThread: 	at com.uei.control.Service.onCreate(Unknown Source)
08-30 10:22:38.816  8776  8776 E ActivityThread: 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2738)
08-30 10:22:38.816  8776  8776 E ActivityThread: 	at android.app.ActivityThread.access$1800(ActivityThread.java:148)
08-30 10:22:38.816  8776  8776 E ActivityThread: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
08-30 10:22:38.816  8776  8776 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 10:22:38.816  8776  8776 E ActivityThread: 	at android.os.Looper.loop(Looper.java:135)
08-30 10:22:38.816  8776  8776 E ActivityThread: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-30 10:22:38.816  8776  8776 E ActivityThread: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 10:22:38.816  8776  8776 E ActivityThread: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 10:22:38.816  8776  8776 E ActivityThread: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-30 10:22:38.816  8776  8776 E ActivityThread: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,08-30 10:22:38.817  8776  8776 D UEI.SmartControl: Internal service binding...,
08-30 10:22:38.855  6615  6733 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
08-30 10:22:38.855  6615  6733 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 10:22:38.855  6615  6733 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 10:22:38.856  6615  6733 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 10:22:38.856  6615  6733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 10:22:38.856  6615  6733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-30 10:22:38.856  6615  6733 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 10:22:38.857  6615  6733 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d5f37f7 removed from the list
,08-30 10:22:38.857  6615  6733 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 10:22:38.857  6615  6733 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34a24664 removed from the list
08-30 10:22:38.857  6615  6733 D io.jxcore.node.ConnectivityMonitor: stop
08-30 10:22:38.857  6615  6733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 10:22:38.859  6615  6733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 10:22:38.859  6615  6733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 10:22:38.863  6615  6733 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 10:22:38.863  6615  6733 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 10:22:38.865  6615  6733 D BluetoothLeScanner: could not find callback wrapper
08-30 10:22:38.865  6615  6733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 10:22:38.865  6615  6733 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 10:22:38.865  6615  6733 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34a24664 not in the list
08-30 10:22:38.866  6615  6733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 10:22:38.866  6615  6733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 10:22:38.871  6615  6733 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 10:22:38.873  6615  6733 D BluetoothLeScanner: could not find callback wrapper
08-30 10:22:38.873  6615  6733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 10:22:38.873  6615  6733 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 10:22:38.873  6615  6733 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 10:22:38.873  6615  6733 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34a24664 not in the list
08-30 10:22:38.873  6615  6733 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 10:22:38.873  6615  6733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 10:22:38.873  6615  6733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 10:22:38.873  6615  6733 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d5f37f7 not in the list
08-30 10:22:38.874  6615  6733 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 10:22:38.874  6615  6733 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@346f64d0 added. We now have 3 listener(s)
08-30 10:22:38.878  1036  2080 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 10:22:38.878  1036  1523 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2437 sc=60 link=72 tx=5.9, 0.0, 0.0  rx=4.7 bcn=0 [on:0 tx:0 rx:0 period:3009] from screen [on:0 period:-628423650] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-30 10:22:38.881  1036  1523 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2437 sc=60 ,link=72 tx=5.9, 0.0, 0.0  rx=4.7 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-628423648] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-30 10:22:38.881  6615  6733 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 10:22:38.881  1036  1523 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-30 10:22:38.881  6615  6733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 10:22:38.881  6615  6733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 10:22:38.881  6615  6733 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 10:22:38.884  6615  6733 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d057cc9 added. We now have 4 listener(s)
08-30 10:22:38.885  6615  6733 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 10:22:38.885  6615  6733 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 10:22:38.888  6615  6733 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 10:22:38.893  6615  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 10:22:38.893  6615  6733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 10:22:38.893  6615  6733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 10:22:38.893  6615  6733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 10:22:38.893  6615  6733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 10:22:38.893  6615  6733 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 10:22:38.893  6615  6733 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 10:22:38.893  6615  6733 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 10:22:38.895  6615  6733 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 10:22:38.895  6615  6733 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 10:22:38.897  6615  6733 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-30 10:22:38.898  6615  6733 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
08-30 10:22:38.899  6615  6733 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
08-30 10:22:38.899  6615  6733 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-30 10:22:38.899  6615  6733 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
08-30 10:22:38.899  6615  6733 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-30 10:22:38.899  6615  6733 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 10:22:38.900  6615  6733 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-30 10:22:38.900  6615  6733 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-30 10:22:38.901  6615  6733 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-30 10:22:38.901  6615  6733 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-30 10:22:38.901  6615  6733 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
08-30 10:22:38.901  6615  6733 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 10:22:38.901  6615  6733 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 10:22:38.901  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 10:22:38.906  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 10:22:38.906  6615  6615 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-30 10:22:38.907  1036  2307 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-30 10:22:38.908  6615  6733 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-30 10:22:38.908  6615  8847 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 10:22:38.910  1036  1051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 10:22:38.913  7956  8068 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=84 mFd=82
08-30 10:22:38.915  6615  8847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
08-30 10:22:38.916  6615  6733 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-30 10:22:38.917  6615  6733 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-30 10:22:38.919  6615  6733 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 10:22:38.919  6615  6733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,08-30 10:22:38.921  6615  6733 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,08-30 10:22:41.897  1036  1523 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2437 sc=60 link=72 tx=3.0, 0.0, 0.0  rx=2.3 bcn=0 [on:0 tx:0 rx:0 period:3006] from screen [on:0 period:-628420631] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-30 10:22:41.900  1036  1523 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2437 sc=60 link=72 tx=3.0, 0.0, 0.0  rx=2.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-628420628] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-30 10:22:41.900  1036  1523 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-30 10:22:41.924  6615  6733 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 10:22:41.924  6615  6733 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 10:22:41.924  6615  6733 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-30 10:22:41.924  6615  6733 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-30 10:22:41.924  6615  6733 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-30 10:22:41.924  6615  6733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,08-30 10:22:41.928  6615  6733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 10:22:41.928  6615  6733 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-30 10:22:41.928  6615  6615 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-30 10:22:41.929  6615  6733 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-30 10:22:41.929  6615  6733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 10:22:41.929  6615  6733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 10:22:41.930  6615  8847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-30 10:22:41.930  6615  8847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-30 10:22:41.930  6615  8847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-30 10:22:41.933  6615  6615 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 10:22:41.933  6615  6615 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-30 10:22:41.933  6615  6615 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-30 10:22:41.933  6615  6733 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 10:22:41.933  6615  6733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 10:22:41.933  6615  6733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 10:22:41.933  6615  6733 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 10:22:41.933  6615  6733 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@346f64d0 removed from the list
08-30 10:22:41.933  6615  6733 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 10:22:41.933  6615  6733 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d057cc9 removed from the list
08-30 10:22:41.933  6615  6733 D io.jxcore.node.ConnectivityMonitor: stop
08-30 10:22:41.933  6615  6733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 10:22:41.934  6615  6733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 10:22:41.934  6615  6733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 10:22:41.935  6615  6733 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 10:22:41.935  6615  6733 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 10:22:41.936  6615  6733 D BluetoothLeScanner: could not find callback wrapper
08-30 10:22:41.936  6615  6733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 10:22:41.936  6615  6733 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 10:22:41.936  6615  6733 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d057cc9 not in the list
08-30 10:22:41.936  6615  6733 W org.thaliproj,ect.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 10:22:41.936  6615  6733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 10:22:41.941  6615  6733 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 10:22:41.944  6615  6733 D BluetoothLeScanner: could not find callback wrapper
08-30 10:22:41.944  6615  6733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 10:22:41.944  6615  6733 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 10:22:41.944  6615  6733 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 10:22:41.944  6615  6733 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d057cc9 not in the list
08-30 10:22:41.944  6615  6733 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 10:22:41.945  6615  6733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 10:22:41.945  6615  6733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 10:22:41.945  6615  6733 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@346f64d0 not in the list
08-30 10:22:41.946  6615  6733 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 10:22:41.946  6615  6733 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@37601c85 added. We now have 3 listener(s)
08-30 10:22:41.946  1036  1051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 10:22:41.949  6615  6733 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 10:22:41.949  6615  6733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 10:22:41.949  6615  6733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 10:22:41.949  6615  6733 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 10:22:41.949  6615  6733 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@307adada added. We now have 4 listener(s)
08-30 10:22:41.949  6615  6733 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 10:22:41.953  6615  6733 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 10:22:41.958  6615  6733 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 10:22:41.962  6615  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 10:22:41.962  6615  6733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 10:22:41.962  6615  6733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 10:22:41.962  6615  6733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 10:22:41.962  6615  6733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 10:22:41.962  6615  6733 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 10:22:41.962  6615  6733 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 10:22:41.962  6615  6733 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 10:22:41.966  6615  6733 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 10:22:41.966  6615  6733 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 10:22:41.969  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 10:22:41.971  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 10:22:41.971  6615  6733 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 10:22:41.972  6615  6733 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 10:22:41.972  6615  6733 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 10:22:41.972  6615  6733 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 10:22:41.972  6615  6733 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 10:22:41.977  6615  6733 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-30 10:22:41.979  1036  2022 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 10:22:41.984  6615  6733 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-30 10:22:41.985  6615  6733 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-30 10:22:41.986  6615  6733 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 10:22:41.987  6615  6733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 10:22:41.988  6615  6733 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,08-30 10:22:42.476  8776  8787 E UEI.SmartControl: file observer is disposed!
,08-30 10:22:43.748  8776  8836 D UEI.SmartControl: Internal timer expired: 2
08-30 10:22:43.749  8776  8836 D UEI.SmartControl: unbind internal service
08-30 10:22:43.768  8776  8776 D UEI.SmartControl: Service.onUnbind: IControl
,08-30 10:22:43.775  8776  8776 D UEI.SmartControl: Service.onDestroy
,08-30 10:22:43.775  8776  8776 D UEI.SmartControl: Lock is in USE false
,08-30 10:22:43.775  8776  8776 D UEI.SmartControl: unbind internal service
,08-30 10:22:43.776  8776  8776 D serial_port: close(fd = 24)
,08-30 10:22:43.779  8776  8776 I UEI.SmartControl: Serial port is closed.
08-30 10:22:43.779  8776  8776 I UEI.SmartControl: Serial port is closed.
08-30 10:22:43.779  8776  8776 D UEI.SmartControl: Blaster closed
08-30 10:22:43.779  8776  8776 D UEI.SmartControl: Shut down QS...
,08-30 10:22:43.779  8776  8776 D UEI.SmartControl: Stopping QS lib
08-30 10:22:43.779  8776  8776 D UEI.SmartControl: QS lib stop result = true
08-30 10:22:43.780  8776  8776 D UEI.SmartControl: Stopped QS lib
08-30 10:22:43.780  8776  8776 D UEI.SmartControl: QS shutdown complete
08-30 10:22:44.928  1036  1523 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2437 sc=60 link=72 tx=1.5, 0.0, 0.0  rx=1.2 bcn=0 [on:0 tx:0 rx:0 period:3006] from screen [on:0 period:-628417601] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-30 10:22:44.931  1036  1523 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2437 sc=60 link=72 tx=1.5, 0.0, 0.0  rx=1.2 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-628417597] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-30 10:22:44.945  1036  1523 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-30 10:22:44.998  6615  6733 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 10:22:44.998  6615  6733 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-30 10:22:44.998  6615  6733 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-30 10:22:45.010  6615  6733 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 10:22:45.010  6615  6733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 10:22:45.011  6615  6733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 10:22:45.011  6615  6733 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 10:22:45.011  6615  6733 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@37601c85 removed from the list
08-30 10:22:45.011  6615  6733 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 10:22:45.011  6615  6733 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@307adada removed from the list
08-30 10:22:45.011  6615  6733 D io.jxcore.node.ConnectivityMonitor: stop
08-30 10:22:45.011  6615  6733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 10:22:45.014  6615  6733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 10:22:45.014  6615  6733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 10:22:45.020  6615  6733 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 10:22:45.020  6615  6733 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 10:22:45.025  6615  6733 D BluetoothLeScanner: could not find callback wrapper
08-30 10:22:45.025  6615  6733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 10:22:45.025  6615  6733 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 10:22:45.025  6615  6733 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@307adada not in the list
08-30 10:22:45.025  6615  6733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 10:22:45.025  6615  6733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 10:22:45.026  6615  6733 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 10:22:45.027  6615  6733 D BluetoothLeScanner: could not find callback wrapper
08-30 10:22:45.027  6615  6733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 10:22:45.027  6615  6733 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 10:22:45.027  6615  6733 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 10:22:45.027  6615  6733 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@307adada not in the list
08-30 10:22:45.027  6615  6733 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 10:22:45.027  6615  6733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 10:22:45.027  6615  6733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 10:22:45.027  6615  6733 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@37601c85 not in the list
08-30 10:22:45.028  6615  6733 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 10:22:45.028  6615  6733 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e3bcaa6 added. We now have 3 listener(s)
08-30 10:22:45.029  1036  1951 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 10:22:45.033  6615  6733 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 10:22:45.033  6615  6733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 10:22:45.033  6615  6733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 10:22:45.034  6615  6733 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 10:22:45.034  6615  6733 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@29980ce7 added. We now have 4 listener(s)
08-30 10:22:45.034  6615  6733 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 10:22:45.035  6615  6733 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 10:22:45.042  6615  6733 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 10:22:45.047  6615  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 10:22:45.047  6615  6733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 10:22:45.047  6615  6733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 10:22:45.047  6615  6733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 10:22:45.047  6615  6733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 10:22:45.047  6615  6733 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 10:22:45.047  6615  6733 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 10:22:45.047  6615  6733 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 10:22:45.050  6615  6733 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 10:22:45.050  6615  6733 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 10:22:45.053  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 10:22:45.055  6615  6615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 10:22:45.057  6615  6733 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 10:22:45.057  6615  6733 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 10:22:45.057  6615  6733 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 10:22:45.057  6615  6733 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 10:22:45.057  6615  6733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 10:22:45.057  6615  6733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 10:22:45.057  6615  6733 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 10:22:45.057  6615  6733 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e3bcaa6 removed from the list
08-30 10:22:45.058  6615  6733 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 10:22:45.058  6615  6733 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@29980ce7 removed from the list
08-30 10:22:45.058  6615  6733 D io.jxcore.node.ConnectivityMonitor: stop
08-30 10:22:45.058  6615  6733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 10:22:45.059  6615  6733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 10:22:45.059  6615  6733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 10:22:45.063  6615  6733 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 10:22:45.063  6615  6733 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 10:22:45.063  6615  6733 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 10:22:45.063  6615  6733 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@29980ce7 not in the list,
08-30 10:22:45.063  6615  6733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 10:22:45.063  6615  6733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 10:22:45.064  6615  6733 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 10:22:45.064  6615  6733 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 10:22:45.064  6615  6733 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 10:22:45.064  6615  6733 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@29980ce7 not in the list
08-30 10:22:45.064  6615  6733 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 10:22:45.064  6615  6733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 10:22:45.064  6615  6733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 10:22:45.064  6615  6733 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e3bcaa6 not in the list
08-30 10:22:45.065  6615  6733 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,08-30 10:22:45.066  6615  6733 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-30 10:22:45.066  6615  6733 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-30 10:22:45.066  6615  6733 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 10:22:45.066  6615  6733 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-30 10:22:45.066  6615  6733 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-30 10:22:47.088  6615  8859 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 891, name: My test thread name)
,08-30 10:22:47.964  1036  1523 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2437 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.6 bcn=0 [on:0 tx:0 rx:0 period:3006] from screen [on:0 period:-628414564] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-30 10:22:47.967  1036  1523 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2437 sc=60 link=72 tx=0.7, 0.0, 0.0  rx=0.6 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-628414561] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-30 10:22:47.967  1036  1523 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-30 10:22:49.084  6615  6733 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 891
,08-30 10:22:49.085  6615  6733 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 891, name: My test thread name)
,08-30 10:22:49.103  6615  8860 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 892, name: My test thread name)
08-30 10:22:49.103  6615  8860 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 892, thread name: My test thread name)
08-30 10:22:49.103  6615  8860 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 892, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
08-30 10:22:49.105  6615  6733 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-30 10:22:49.108  6615  8861 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 896, name: My test thread name)
08-30 10:22:49.109  6615  8861 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 896, thread name: My test thread name): Test exception.
08-30 10:22:49.109  6615  8861 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 896, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,08-30 10:22:49.115  6615  6733 I jxcore-log: Total number of executed tests:  82
08-30 10:22:49.115  6615  6733 I jxcore-log: 
08-30 10:22:49.116  6615  6733 I jxcore-log: Number of passed tests:  82
08-30 10:22:49.116  6615  6733 I jxcore-log: 
08-30 10:22:49.116  6615  6733 I jxcore-log: Number of failed tests:  0
08-30 10:22:49.116  6615  6733 I jxcore-log: 
08-30 10:22:49.117  6615  6733 I jxcore-log: Number of ignored tests:  0
08-30 10:22:49.117  6615  6733 I jxcore-log: 
08-30 10:22:49.117  6615  6733 I jxcore-log: Total duration:  111700
08-30 10:22:49.117  6615  6733 I jxcore-log: 
08-30 10:22:49.118  6615  6733 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-30 10:22:49.118  6615  6733 I jxcore-log: 
08-30 10:22:49.119  6615  6733 I jxcore-log: My device name is: LGE-LG-D855
08-30 10:22:49.119  6615  6733 I jxcore-log: 
08-30 10:22:49.133  6615  6733 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 10:22:49.133  6615  6733 I jxcore-log: 
08-30 10:22:49.135  6615  6733 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 10:22:49.135  6615  6733 I jxcore-log: 
08-30 10:22:49.136  6615  6733 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 10:22:49.136  6615  6733 I jxcore-log: 
08-30 10:22:49.137  6615  6733 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 10:22:49.137  6615  6733 I jxcore-log: 
08-30 10:22:49.138  6615  6733 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 10:22:49.138  6615  6733 I jxcore-log: 
,08-30 10:22:49.145  6615  8859 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 891, name: My test thread name), during the lifetime of the thread the total number of bytes read was 176 and the total number of bytes written 176
08-30 10:22:49.153  6615  6733 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-30 10:22:49.153  6615  6733 I jxcore-log: 
08-30 10:22:49.155  6615  6733 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 10:22:49.155  6615  6733 I jxcore-log: 
08-30 10:22:49.156  6615  6733 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 10:22:49.156  6615  6733 I jxcore-log: 
08-30 10:22:49.157  6615  6733 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 10:22:49.157  6615  6733 I jxcore-log: 
08-30 10:22:49.158  6615  6733 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 10:22:49.158  6615  6733 I jxcore-log: 
08-30 10:22:49.159  6615  6733 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 10:22:49.159  6615  6733 I jxcore-log: 
08-30 10:22:49.160  6615  6733 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 10:22:49.160  6615  6733 I jxcore-log: 
08-30 10:22:49.161  6615  6733 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 10:22:49.161  6615  6733 I jxcore-log: 
08-30 10:22:49.162  6615  6733 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 10:22:49.162  6615  6733 I jxcore-log: 
08-30 10:22:49.163  6615  6733 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 10:22:49.163  6615  6733 I jxcore-log: 
,08-30 10:22:49.168  6615  6733 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 10:22:49.168  6615  6733 I jxcore-log: 
08-30 10:22:49.169  6615  6733 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 10:22:49.169  6615  6733 I jxcore-log: 
08-30 10:22:49.170  6615  6733 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 10:22:49.170  6615  6733 I jxcore-log: 
08-30 10:22:49.172  6615  6733 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 10:22:49.172  6615  6733 I jxcore-log: 
08-30 10:22:49.172  6615  6733 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 10:22:49.172  6615  6733 I jxcore-log: 
08-30 10:22:49.173  6615  6733 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 10:22:49.173  6615  6733 I jxcore-log: 
08-30 10:22:49.174  6615  6733 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 10:22:49.174  6615  6733 I jxcore-log: 
08-30 10:22:49.176  6615  6733 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 10:22:49.176  6615  6733 I jxcore-log: 
,08-30 10:22:49.179  6615  6733 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 10:22:49.179  6615  6733 I jxcore-log: 
08-30 10:22:49.181  6615  6733 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 10:22:49.181  6615  6733 I jxcore-log: 
08-30 10:22:49.182  6615  6733 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 10:22:49.182  6615  6733 I jxcore-log: 
08-30 10:22:49.183  6615  6733 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 10:22:49.183  6615  6733 I jxcore-log: 
08-30 10:22:49.184  6615  6733 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 10:22:49.184  6615  6733 I jxcore-log: 
08-30 10:22:49.184  6615  6733 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 10:22:49.184  6615  6733 I jxcore-log: 
08-30 10:22:49.185  6615  6733 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 10:22:49.185  6615  6733 I jxcore-log: 
08-30 10:22:49.186  6615  6733 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 10:22:49.186  6615  6733 I jxcore-log: 
08-30 10:22:49.187  6615  6733 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 10:22:49.187  6615  6733 I jxcore-log: 
08-30 10:22:49.187  6615  6733 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 10:22:49.187  6615  6733 I jxcore-log: 
08-30 10:22:49.188  6615  6733 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-30 10:22:49.188  6615  6733 I jxcore-log: 
08-30 10:22:49.189  6615  6733 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-30 10:22:49.189  6615  6733 I jxcore-log: 
08-30 10:22:49.190  6615  6733 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 10:22:49.190  6615  6733 I jxcore-log: 
08-30 10:22:49.190  6615  6733 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 10:22:49.190  6615  6733 I jxcore-log: 
08-30 10:22:49.192  6615  6733 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 10:22:49.192  6615  6733 I jxcore-log: 
08-30 10:22:49.193  6615  6733 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 10:22:49.193  6615  6733 I jxcore-log: 
08-30 10:22:49.194  6615  6733 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 10:22:49.194  6615  6733 I jxcore-log: 
08-30 10:22:49.195  6615  6733 I jxcore-log: DEBUG thaliMobileNativeWrapper: net,workChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 10:22:49.195  6615  6733 I jxcore-log: 
08-30 10:22:49.196  6615  6733 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 10:22:49.196  6615  6733 I jxcore-log: 
08-30 10:22:49.196  6615  6733 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 10:22:49.196  6615  6733 I jxcore-log: 
,08-30 10:22:49.430  8862  8862 D AndroidRuntime: 
08-30 10:22:49.430  8862  8862 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-30 10:22:49.435  8862  8862 D AndroidRuntime: CheckJNI is OFF
08-30 10:22:49.545  8862  8862 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-30 10:22:49.553  1036  1104 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
08-30 10:22:49.554  1036  1104 I ActivityManager: Killing 6615:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
08-30 10:22:49.586  1036  1952 I WindowState: WIN DEATH: Window{8a12f25 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-30 10:22:49.590  1036  1529 D WifiService: Client connection lost with reason: 4
08-30 10:22:49.592  1036  1952 D InputDispatcher: Window went away: Window{8a12f25 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-30 10:22:49.771  1036  1104 I ActivityManager:   Force finishing activity ActivityRecord{2c6cbe8e u0 com.test.thalitest/.MainActivity t6}
,08-30 10:22:49.824   344   383 E GBMv2   : DFP En is all cleared set to be enabled
,08-30 10:22:49.830  1036  2305 W ActivityManager: Spurious death for ProcessRecord{f93b43f 6615:com.test.thalitest/u0a118}, curProc for 6615: null
08-30 10:22:49.830  1036  1124 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
08-30 10:22:49.836  1036  1124 I ActivityManager:   Force finishing activity ActivityRecord{2c6cbe8e u0 com.test.thalitest/.MainActivity t6 f}
08-30 10:22:49.836  1036  1124 W ActivityManager: Duplicate finish request for ActivityRecord{2c6cbe8e u0 com.test.thalitest/.MainActivity t6 f}
,08-30 10:22:49.890  2081  2081 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
,08-30 10:22:49.890  1955  4029 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
08-30 10:22:49.890  1955  4029 D SplitWindowPolicy: topRunningActivity=ActivityInfo{247016cb co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-30 10:22:49.892  2081  2081 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
,08-30 10:22:49.893  2081  2081 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
08-30 10:22:49.895  1955  1977 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
08-30 10:22:49.896  2081  2169 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=1ms
08-30 10:22:49.896  1955  1977 D SplitWindowPolicy: topRunningActivity=ActivityInfo{16adbea8 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-30 10:22:49.903  1586  1586 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,08-30 10:22:49.912  1036  1414 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-30 10:22:49.918  1036  1102 W InputMethodInfo: Duplicated subtype definition found: , voice
,08-30 10:22:49.932  2438  2580 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-30 10:22:49.934  2025  2025 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-30 10:22:49.934  4652  4652 I art     : Explicit concurrent mark sweep GC freed 15424(885KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 29MB/45MB, paused 548us total 46.546ms
08-30 10:22:49.934  3885  3885 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
08-30 10:22:49.937  7956  7956 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
08-30 10:22:49.937  7956  7956 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-30 10:22:49.988  4541  4541 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-30 10:22:49.988  4541  4541 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-30 10:22:49.988  4541  4541 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-30 10:22:49.988  4541  4541 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-30 10:22:49.988  8258  8258 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-30 10:22:49.988  4541  4541 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-30 10:22:49.988  4541  4541 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-30 10:22:49.988  4541  4541 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-30 10:22:49.988  4541  4541 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-30 10:22:49.988  4541  4541 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 10:22:49.988  4541  4541 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 10:22:49.988  4541  4541 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-30 10:22:49.988  4541  4541 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,08-30 10:22:49.991  1036  1036 I art     : Explicit concurrent mark sweep GC freed 14865(1000KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/65MB, paused 2.268ms total 139.587ms
08-30 10:22:49.997  2081  2081 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
08-30 10:22:49.998  1915  1915 D ActionManagerService: notifyUserLog: 1000003
08-30 10:22:49.998  3885  4540 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
08-30 10:22:50.001  2081  2081 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
,08-30 10:22:50.008  1036  2305 V SIM_STK : Menu title from STK is T-Mobile
08-30 10:22:50.011  1826  1826 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
08-30 10:22:50.033  2081  2081 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
,08-30 10:22:50.040  1586  1586 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
08-30 10:22:50.045  2229  2229 I ConfigService: onCreate
08-30 10:22:50.045  2229  2229 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
,08-30 10:22:50.047  1881  1881 D SplitUIManager: split_name #11 / not available #0
08-30 10:22:50.047  1881  1881 D SplitUIService: removed split : 
08-30 10:22:50.050  1586  1635 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-30 10:22:50.050  1586  1635 D KeyguardModel: createShortcutInfo...
08-30 10:22:50.050  1826  1826 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
08-30 10:22:50.052  2081  2081 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
08-30 10:22:50.053  1586  1635 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-30 10:22:50.053  1586  1635 D KeyguardModel: createShortcutInfo...
08-30 10:22:50.055  1586  1635 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-30 10:22:50.056  1586  1635 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-30 10:22:50.059  1586  1635 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-30 10:22:50.059  1586  1635 D KeyguardModel: createShortcutInfo...
,08-30 10:22:50.062  2229  2229 I ConfigService: onBind returning update interface
08-30 10:22:50.062  1586  1635 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-30 10:22:50.062  1586  1635 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-30 10:22:50.066  1586  1586 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-30 10:22:50.066  1586  1586 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
08-30 10:22:50.066  1036  1036 D administrator: Handling package changes for user 0
08-30 10:22:50.067  1915  1915 D ActionManagerService: notifyUserLog: 1000004
08-30 10:22:50.067  2081  2081 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
08-30 10:22:50.068  3885  4540 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
08-30 10:22:50.069  1036  2080 V SIM_STK : Menu title from STK is T-Mobile
08-30 10:22:50.069  1036  2080 V SIM_STK : Menu title from STK is T-Mobile
08-30 10:22:50.071  3885  3900 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-30 10:22:50.073  2229  2229 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-30 10:22:50.073  2229  2229 I ConfigService: onBind returning config service
,08-30 10:22:50.075  1586  1635 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-30 10:22:50.075  1586  1635 D KeyguardModel: createShortcutInfo...
08-30 10:22:50.077  2229  2229 I ConfigService: onDestroy
08-30 10:22:50.079  2081  2081 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-30 10:22:50.079  2081  2081 I GBoardWebViewUtils: , create_time: 1430832262123
08-30 10:22:50.079  2081  2081 I GBoardWebViewUtils: , expire_time: 0
08-30 10:22:50.079  2081  2081 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-30 10:22:50.079  2081  2081 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-30 10:22:50.079  2081  2081 I GBoardWebViewUtils: , display: false
08-30 10:22:50.079  2081  2081 I GBoardWebViewUtils: , animation: false }
08-30 10:22:50.079  2081  2081 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-30 10:22:50.079  2081  2081 I GBoardWebViewUtils: , create_time: 1430832262287
08-30 10:22:50.079  2081  2081 I GBoardWebViewUtils: , expire_time: 0
08-30 10:22:50.079  2081  2081 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-30 10:22:50.079  2081  2081 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-30 10:22:50.079  2081  2081 I GBoardWebViewUtils: , display: false
08-30 10:22:50.079  2081  2081 I GBoardWebViewUtils: , animation: false }
08-30 10:22:50.080  2081  2081 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1472216587976
08-30 10:22:50.080  2081  2081 I GBoardWebViewUtils: , create_time: 1472216588858
08-30 10:22:50.080  2081  2081 I GBoardWebViewUtils: , expire_time: 0
08-30 10:22:50.080  2081  2081 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide.html?id=guide_1111111111116_1472216587976&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-30 10:22:50.080  2081  2081 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-30 10:22:50.080  2081  2081 I GBoardWebViewUtils: , display: false
08-30 10:22:50.080  2081  2081 I GBoardWebViewUtils: , animation: false }
08-30 10:22:50.084  2081  8895 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
08-30 10:22:50.085  1826  8896 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,08-30 10:22:50.098  1586  1635 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-30 10:22:50.098  1586  1635 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
,08-30 10:22:50.102  2081  2081 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-30 10:22:50.102  2081  2081 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
08-30 10:22:50.104  1881  1881 D SplitUIManager: split_name #11 / not available #0
08-30 10:22:50.104  1881  1881 I SplitUIService: split app #11
08-30 10:22:50.110  1586  1635 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-30 10:22:50.110  1586  1635 D KeyguardModel: createShortcutInfo...
,08-30 10:22:50.114  1586  1586 D KeyguardModel: handleShortcutListChanged...
08-30 10:22:50.114  1586  1586 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-30 10:22:50.119  1586  1635 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-30 10:22:50.120  1586  1635 D KeyguardModel: createShortcutInfo...
08-30 10:22:50.123  1586  1635 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-30 10:22:50.123  1586  1635 D KeyguardModel: createShortcutInfo...
,08-30 10:22:50.126  1586  1635 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-30 10:22:50.126  1586  1635 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
,08-30 10:22:50.129  1586  1635 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-30 10:22:50.129  1586  1635 D KeyguardModel: createShortcutInfo...
08-30 10:22:50.130  1586  1635 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-30 10:22:50.130  1586  1635 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-30 10:22:50.133  1586  1635 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-30 10:22:50.133  1586  1635 D KeyguardModel: createShortcutInfo...
08-30 10:22:50.134  1586  1635 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-30 10:22:50.134  1586  1635 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-30 10:22:50.143  1586  1635 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-30 10:22:50.144  1586  1635 D KeyguardModel: createShortcutInfo...
,08-30 10:22:50.149  5982  8900 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
08-30 10:22:50.150  1036  1051 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-30 10:22:50.150  7956  7956 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-30 10:22:50.150  7956  7956 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-30 10:22:50.150  7956  7956 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-30 10:22:50.150  7956  7956 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-30 10:22:50.150  7956  7956 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-30 10:22:50.150  7956  7956 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-30 10:22:50.150  7956  7956 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-30 10:22:50.150  7956  7956 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-30 10:22:50.150  7956  7956 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-30 10:22:50.151  7956  7956 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
,08-30 10:22:50.151  7956  7956 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-30 10:22:50.159  1826  8904 I PeopleContactsSync: CP2 sync disabled
08-30 10:22:50.159  1036  1951 V SIM_STK : Menu title from STK is T-Mobile
,08-30 10:22:50.162  1586  1586 D KeyguardModel: handleShortcutListChanged...
08-30 10:22:50.162  1586  1586 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-30 10:22:50.171  1826  4822 I Icing   : doRemovePackageData com.test.thalitest
,08-30 10:22:50.183  1826  8903 W GmsApplication: Using Auth Proxy for data requests.
08-30 10:22:50.187  1826  8903 W GmsApplication: Using Auth Proxy for data requests.
08-30 10:22:50.193  2081  2081 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
,08-30 10:22:50.215  1036  1036 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-30 10:22:50.215  1036  1036 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,08-30 10:22:50.215  1036  1036 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-30 10:22:50.217  1036  1563 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
08-30 10:22:50.218  7078  7078 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
08-30 10:22:50.231  2175  8908 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-30 10:22:50.254   331   415 I ThermalEngine: Thermal-Server: Thermal received msg from  override
08-30 10:22:50.256  3238  8909 I Thermal-Lib: Thermal-Lib-Client: Client request sent
,08-30 10:22:50.262  1036  1951 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8910 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
08-30 10:22:50.267  2081  2081 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
08-30 10:22:50.271  2081  2081 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-30 10:22:50.273  2081  2081 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
08-30 10:22:50.274  2081  2081 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-30 10:22:50.275  2081  2081 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-30 10:22:50.276  2081  2081 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
08-30 10:22:50.290  1036  1119 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2c80a595 u0 com.lge.launcher2/.Launcher t5} time:227998
08-30 10:22:50.293  2081  2081 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
08-30 10:22:50.293  2081  2081 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-30 10:22:50.293  2081  2274 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-30 10:22:50.293  2081  2274 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
,08-30 10:22:50.306  1826  8899 I art     : Explicit concurrent mark sweep GC freed 39557(2MB) AllocSpace objects, 27(432KB) LOS objects, 51% free, 30MB/62MB, paused 1.770ms total 24.898ms
08-30 10:22:50.308  1826  1839 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/history_query.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
08-30 10:22:50.308  1826  1839 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/help_responses.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
08-30 10:22:50.308  2081  2081 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
08-30 10:22:50.308  1826  1839 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/metrics.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
08-30 10:22:50.309  2081  2081 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-30 10:22:50.309  2081  2081 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-30 10:22:50.321  2081  2081 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
,08-30 10:22:50.324  2081  2081 D [Concierge]WidgetView: change position of spinner
,08-30 10:22:50.325  2081  2081 I [Concierge]WidgetView: initWebView(). Time : 1472545370325
08-30 10:22:50.328  1036  1102 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 10:22:50.330  2632  2632 D [Concierge]Service: onStartCommand(). Type : 8
08-30 10:22:50.330  2632  2632 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
08-30 10:22:50.331  2632  2632 D [Concierge]Service: Update widget ID : 11
08-30 10:22:50.331  2632  2632 D [Concierge]Service: onStartCommand(). Type : 0
08-30 10:22:50.336  1036  1102 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,08-30 10:22:50.341  8910  8910 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 10:22:50.341  8910  8910 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-30 10:22:50.342  8910  8910 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-30 10:22:50.342  8910  8910 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-30 10:22:50.344  2081  2081 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 553838717
08-30 10:22:50.344  2081  2081 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
08-30 10:22:50.345  2081  2081 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-30 10:22:50.347  2081  2081 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@254c8bfd
08-30 10:22:50.347  2081  2081 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
08-30 10:22:50.348  2081  2081 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-30 10:22:50.348  2081  2081 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-30 10:22:50.355  2081  2081 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
08-30 10:22:50.355  2081  2081 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-30 10:22:50.356  2081  2081 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1472545170549, New one : 1472545370325
08-30 10:22:50.356  2081  2081 D [Concierge]WidgetView: Unregister all receivers
08-30 10:22:50.356  2081  2081 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-30 10:22:50.357  2081  2081 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-30 10:22:50.357  2081  2081 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-30 10:22:50.358  2081  2081 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-30 10:22:50.359  2081  2081 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
08-30 10:22:50.361  2081  2081 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
,08-30 10:22:50.362  2081  2081 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
08-30 10:22:50.363  2081  2081 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
08-30 10:22:50.364  2081  2081 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
08-30 10:22:50.365  2081  2081 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-30 10:22:50.365  2081  2081 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-30 10:22:50.381  1036  1124 I art     : Explicit concurrent mark sweep GC freed 13729(859KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/65MB, paused 1.877ms total 310.558ms
,08-30 10:22:50.401  8910  8910 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
08-30 10:22:50.402  2081  2081 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,08-30 10:22:50.410  8910  8910 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,08-30 10:22:50.411  2081  2081 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
08-30 10:22:50.411  2081  2081 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
08-30 10:22:50.413  2081  2081 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-30 10:22:50.433  2081  2081 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@162592e time:228141
,08-30 10:22:50.444  8910  8910 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-30 10:22:50.456  8862  8862 D AndroidRuntime: Shutting down VM
08-30 10:22:50.466  8910  8910 D LgDataFeature: LgDataFeature() Constructor: none
,08-30 10:22:50.466  8910  8910 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 10:22:50.511  8910  8910 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,08-30 10:22:50.521  1036  2307 I ActivityManager: Killing 8162:com.lge.formmanager/u0a26 (adj 15): empty #17
,08-30 10:22:50.569  2081  2081 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,08-30 10:22:50.602  2081  2940 I GBoardtInterface: onReloaded()
,08-30 10:22:50.604  2081  2081 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
08-30 10:22:50.604  2025  2025 D LIA_Service_NativeEventReceiver: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-30 10:22:50.604  2025  2025 I LIA_Service_PlatformUtil: startLIAService() : Trying to start LIA service ...
08-30 10:22:50.604  1036  1052 W libprocessgroup: failed to open /acct/uid_10026/pid_8162/cgroup.procs: No such file or directory
08-30 10:22:50.606  3885  3900 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-30 10:22:50.606  2025  2025 D LIA_Service_LIAService: onStartCommand() : LIAService started! - id :4, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
08-30 10:22:50.609  8258  8258 D PostponalbeReceiver: OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-30 10:22:50.610  3885  4559 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-30 10:22:50.639  1036  2022 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.core.receiver.CoreEventReceiver: pid=8935 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-30 10:22:50.645  1915  1915 D ActionManagerService: notifyUserLog: 1000001
08-30 10:22:50.646  3885  4540 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-30 10:22:50.646  3885  4540 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-30 10:22:50.649  1915  1915 D ActionManagerService: notifyUserLog: 1000001
08-30 10:22:50.650  3885  4540 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-30 10:22:50.650  3885  4540 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-30 10:22:50.650  3885  4540 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
08-30 10:22:50.650  3885  4540 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
08-30 10:22:50.650  3885  3900 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
,08-30 10:22:50.652  2081  2081 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
,08-30 10:22:50.653  2081  2081 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
08-30 10:22:50.655  2081  2081 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
08-30 10:22:50.655  2081  2081 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-30 10:22:50.656  2081  2081 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1472216587976&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
08-30 10:22:50.656  2081  2081 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1472216587976&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-30 10:22:50.693  1036  1124 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8952 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-30 10:22:50.704   348   348 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 220us total 10.818ms
,08-30 10:22:50.707  8935  8935 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-30 10:22:50.707  8935  8935 W LG Account v2.2: No ProfileInfo entries
08-30 10:22:50.707  8935  8935 I LG Account v2.2: isEnabled: false
08-30 10:22:50.707  8935  8935 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-30 10:22:50.707  8935  8935 I Feature : [Lifetracker]Country: EU
08-30 10:22:50.707  8935  8935 I Feature : [Lifetracker]Operator: OPEN
08-30 10:22:50.707  8935  8935 I Feature : [Lifetracker]Ranking support: false
08-30 10:22:50.707  8935  8935 I Feature : [Lifetracker]Comfort support: false
08-30 10:22:50.707  8935  8935 I Feature : [Lifetracker]Accessory: true
08-30 10:22:50.707  8935  8935 I Feature : [Lifetracker]Health device: true
08-30 10:22:50.707  8935  8935 I Feature : [Lifetracker]Extra Pedometer: false
08-30 10:22:50.707  8935  8935 I Feature : [Lifetracker]Blood glucose device: false
08-30 10:22:50.707  8935  8935 I Feature : [Lifetracker]Device Number: 3
08-30 10:22:50.708  8935  8935 D CoreEventReceiver: [onReceive] Action=android.intent.action.PACKAGE_REMOVED
08-30 10:22:50.713   348   348 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 194us total 9.133ms
,08-30 10:22:50.722   348   348 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 252us total 9.053ms
08-30 10:22:50.739  1036  2080 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=8972 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-30 10:22:50.740  1036  2080 I ActivityManager: Killing 8460:com.android.chrome/u0a57 (adj 15): empty #17
,08-30 10:22:50.813  1036  1051 W libprocessgroup: failed to open /acct/uid_10057/pid_8460/cgroup.procs: No such file or directory
08-30 10:22:50.832  8972  8972 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 10:22:50.832  8972  8972 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
08-30 10:22:50.832  8972  8972 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-30 10:22:50.832  8972  8972 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.

```
