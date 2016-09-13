#### Test 836273379690449_thali02_LGE-LG-D855 Logs


```
--------- beginning of system
09-13 14:17:57.179  1045  1700 I ActivityManager: Killing 5483:com.google.android.setupwizard/u0a46 (adj 15): empty #17
--------- beginning of main
09-13 14:17:57.276  1983  1983 D LIA_Service_NativeEventReceiver: onReceive action : android.intent.action.PACKAGE_ADDED = package:com.test.thalitest
09-13 14:17:57.276  1045  1061 W libprocessgroup: failed to open /acct/uid_10046/pid_5483/cgroup.procs: No such file or directory
09-13 14:17:57.277  1983  1983 I LIA_Service_PlatformUtil: startLIAService() : Trying to start LIA service ...
09-13 14:17:57.284  1983  1983 D LIA_Service_LIAService: onStartCommand() : LIAService started! - id :3, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
09-13 14:17:57.321  6528  6528 D PostponalbeReceiver: OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_ADDED'.
09-13 14:17:57.326  6528  6528 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsm.mss.OasPackageScanReceiver.onReceive:-1 android.app.ActivityThread.handleReceiver:2586 
09-13 14:17:57.354  4652  6668 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
09-13 14:17:57.396  1045  1637 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=6669 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-13 14:17:57.415  1045  1946 V SIM_STK : Menu title from STK is T-Mobile
09-13 14:17:57.542  1805  4821 I art     : Explicit concurrent mark sweep GC freed 23706(1535KB) AllocSpace objects, 15(240KB) LOS objects, 51% free, 29MB/61MB, paused 1.556ms total 54.176ms
09-13 14:17:57.574  4652  6668 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 220 ms] updated apps [took 220 ms] 
09-13 14:17:57.622  6669  6669 D DocsApplication: Installing DEX configuration.
09-13 14:17:57.637  6669  6669 D DexInstaller: Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
09-13 14:17:57.640  6669  6669 I PackageInfoHelper: Provided clientMode=RELEASE, packageInfo=PackageInfo{296b7299 com.google.android.apps.docs}
09-13 14:17:57.656  6669  6669 D TAG     : onCreate()
09-13 14:17:57.676  6669  6669 D CrossAppStateProvider: Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
,09-13 14:17:58.122   323   410 I ThermalEngine: Thermal-Server: Thermal received msg from  override
09-13 14:17:58.124  3167  6687 I Thermal-Lib: Thermal-Lib-Client: Client request sent
09-13 14:17:58.406  6688  6688 D AndroidRuntime: 
09-13 14:17:58.406  6688  6688 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
09-13 14:17:58.409  6688  6688 D AndroidRuntime: CheckJNI is OFF
09-13 14:17:58.555  6688  6688 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-13 14:17:58.561  1045  1637 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-13 14:17:58.574  1929  1945 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
09-13 14:17:58.577  1045  1637 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
09-13 14:17:58.578  1805  4821 I Icing   : Indexing 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4 from com.google.android.googlequicksearchbox
09-13 14:17:58.578  1045  1637 D ActivityManager: setTaskToReturnTo : TaskRecord{66ad51d #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
09-13 14:17:58.578  1045  1637 D ActivityManager: setTaskToReturnTo : TaskRecord{66ad51d #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
09-13 14:17:58.579  1045  1637 D WindowStateEx: AppWindowTokenEx init.. 
09-13 14:17:58.580   329   352 E GBMv2   : DFP En is all cleared set to be enabled
09-13 14:17:58.601  1045  1637 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6708 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
09-13 14:17:58.603  6688  6688 D AndroidRuntime: Shutting down VM
09-13 14:17:58.620  1805  4821 D Icing   : Loaded CLD2 Version V2.0 - 20140131
09-13 14:17:58.643  1929  1945 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
09-13 14:17:58.644  1929  1945 D SplitWindowPolicy: topRunningActivity=ActivityInfo{2db62665 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
09-13 14:17:58.645  1929  1944 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
09-13 14:17:58.645  1929  1944 D SplitWindowPolicy: topRunningActivity=ActivityInfo{d5f4f3a co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
09-13 14:17:58.676  6708  6708 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
09-13 14:17:58.704  1805  4821 I Icing   : Indexing done 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4
09-13 14:17:58.754  6708  6708 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
09-13 14:17:58.760  6708  6708 I LibraryLoader: Loading: webviewchromium
09-13 14:17:58.763  6708  6708 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 3038-3041)
09-13 14:17:58.763  6708  6708 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-13 14:17:58.775  6708  6708 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {260f925b}
09-13 14:17:58.776  6708  6708 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-13 14:17:58.776  6708  6708 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
09-13 14:17:58.783  6708  6708 I BrowserStartupController: Initializing chromium process, renderers=0
09-13 14:17:58.784  6708  6708 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-13 14:17:58.801   313  2160 V AudioPolicyService: registerClient() client 0xb558a560, uid 10118
,09-13 14:17:58.802  6708  6708 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
09-13 14:17:58.802  6708  6708 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
09-13 14:17:58.803  6708  6708 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
09-13 14:17:58.809  1045  1120 D BluetoothManagerService: Message: 20
09-13 14:17:58.810  1045  1120 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1a6140bf:true
09-13 14:17:58.817  6708  6708 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-13 14:17:58.817  6708  6708 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-13 14:17:58.817  6708  6708 I Adreno-EGL: Build Date: 12/12/14 금
09-13 14:17:58.817  6708  6708 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-13 14:17:58.817  6708  6708 I Adreno-EGL: Remote Branch: 
09-13 14:17:58.817  6708  6708 I Adreno-EGL: Local Patches: 
09-13 14:17:58.817  6708  6708 I Adreno-EGL: Reconstruct Branch: 
,09-13 14:17:58.891  6708  6742 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,09-13 14:17:58.894  6708  6708 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
09-13 14:17:58.906  6708  6708 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-13 14:17:58.909  6708  6708 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-13 14:17:58.912  6708  6708 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
09-13 14:17:58.915  6708  6708 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
09-13 14:17:58.915  6708  6708 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
09-13 14:17:58.925  6708  6708 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,09-13 14:17:58.930  6708  6708 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-13 14:17:58.930  6708  6708 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-13 14:17:58.962  6669  6669 D LgDataFeature: LgDataFeature() Constructor: none
09-13 14:17:58.962  6669  6669 D LgDataFeature: LgDataFeature() Constructor Done, null
09-13 14:17:58.967  6708  6755 D OpenGLRenderer: Render dirty regions requested: true
09-13 14:17:58.967  6708  6755 I OpenGLRenderer: Initialized EGL, version 1.4
,09-13 14:17:58.973  6708  6755 D OpenGLRenderer: Enabling debug mode 0
09-13 14:17:58.988  6708  6708 D Atlas   : Validating map...,
,09-13 14:17:58.992  1045  1874 D SplitWindow: check instance of lgWin Window{1c4a5ec1 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-13 14:17:59.018  6708  6753 D LgDataFeature: LgDataFeature() Constructor: none
09-13 14:17:59.018  6708  6753 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-13 14:17:59.107  6216  6216 I LockScreenSettings: New app installed broadcast received ..
,09-13 14:17:59.111  1045  1121 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +470ms (total +530ms)
09-13 14:17:59.111  1045  1121 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{39d9c392 u0 com.test.thalitest/.MainActivity t6} time:103389
09-13 14:17:59.112  6708  6708 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@da0d8e6 time:103390
09-13 14:17:59.115  6216  6216 I LockScreenSettings: Number of installed packages  1
09-13 14:17:59.126  6669  6669 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,09-13 14:17:59.165  1045  1928 V SIM_STK : Menu title from STK is T-Mobile
,09-13 14:17:59.215  6708  6708 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
09-13 14:17:59.215  6708  6708 I chromium: 
,09-13 14:17:59.219  1045  1946 I ActivityManager: Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=6784 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
09-13 14:17:59.242  6708  6708 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-13 14:17:59.297  6708  6753 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
09-13 14:17:59.297  6708  6753 I chromium: 
,09-13 14:17:59.309  6784  6784 D EulaProviderUpdateObserver: action : android.intent.action.PACKAGE_ADDED
09-13 14:17:59.309  6784  6784 D EulaProviderUpdateObserver: uri : package:com.test.thalitest
,09-13 14:17:59.365  1045  2019 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.BNRAppInstallReceiver: pid=6803 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,09-13 14:17:59.368  1045  2019 I ActivityManager: Killing 5897:com.google.android.gm/u0a64 (adj 15): empty #17
09-13 14:17:59.408  6708  6820 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435165696
,09-13 14:17:59.416  6708  6820 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-13 14:17:59.416  6708  6820 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-13 14:17:59.416  6708  6820 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-13 14:17:59.416  6708  6820 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-13 14:17:59.416  6708  6820 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
09-13 14:17:59.417  6708  6820 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13f368ca added. We now have 1 listener(s)
,09-13 14:17:59.480  1045  2020 W libprocessgroup: failed to open /acct/uid_10064/pid_5897/cgroup.procs: No such file or directory
,09-13 14:17:59.487  1045  1700 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 14:17:59.491  6708  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
09-13 14:17:59.494  6708  6820 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,09-13 14:17:59.495  6708  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 14:17:59.496  6708  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 14:17:59.504  6708  6820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-13 14:17:59.504  6708  6820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-13 14:17:59.504  6708  6820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-13 14:17:59.504  6708  6820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
09-13 14:17:59.504  6708  6820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-13 14:17:59.504  6708  6820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-13 14:17:59.504  6708  6820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-13 14:17:59.504  6708  6820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-13 14:17:59.504  6708  6820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-13 14:17:59.504  6708  6820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-13 14:17:59.504  6708  6820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-13 14:17:59.504  6708  6820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-13 14:17:59.504  6708  6820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-13 14:17:59.504  6708  6820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-13 14:17:59.504  6708  6820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2db396b1 added. We now have 1 listener(s)
09-13 14:17:59.504  6708  6820 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 14:17:59.512  1045  1528 D WifiService: New client listening to asynchronous messages
,09-13 14:17:59.515  6708  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-13 14:17:59.515  6708  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-13 14:17:59.517  6708  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-13 14:17:59.517  6708  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-13 14:17:59.517  6708  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
09-13 14:17:59.522  6708  6820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 14:17:59.527  1045  1060 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 14:17:59.528  6708  6820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
09-13 14:17:59.539  6708  6820 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
,09-13 14:17:59.539  6708  6820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 14:17:59.539  6708  6820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 14:17:59.539  6708  6820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 14:17:59.539  6708  6820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 14:17:59.539  6708  6820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 14:17:59.539  6708  6820 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 14:17:59.539  6708  6820 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 14:17:59.539  6708  6820 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 14:17:59.539  6708  6820 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-13 14:17:59.539  6708  6820 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 14:17:59.541  6708  6820 I io.jxcore.node.LifeCycleMonitor: start: OK
09-13 14:17:59.542  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 14:17:59.544  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 14:17:59.579  6803  6803 D [BNRAppListMgrReceiver]: android.intent.action.PACKAGE_ADDED : com.test.thalitest
,09-13 14:17:59.586  6708  6708 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
09-13 14:17:59.601  6803  6803 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,09-13 14:17:59.608  6528  6528 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.intent.action.PACKAGE_ADDED'.
09-13 14:17:59.654  1045  1946 I ActivityManager: Killing 5938:com.google.android.talk/u0a72 (adj 15): empty #17
,09-13 14:17:59.733  1045  2038 W libprocessgroup: failed to open /acct/uid_10072/pid_5938/cgroup.procs: No such file or directory
,09-13 14:18:00.039  1591  1591 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-13 14:18:00.040  1591  1591 I KeyguardUpdateMonitor: called onTimeUpdated()
09-13 14:18:00.040  1591  1591 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
,09-13 14:18:00.040  1591  1591 I [SystemUI]Clock: called onTimeUpdated()
09-13 14:18:00.046  1591  1591 I LgeClockWidgetControlView: called onTimeUpdated()
09-13 14:18:00.046  1591  1591 I [SystemUI]DateView: called onTimeUpdated()
09-13 14:18:00.048  1591  1591 I [SystemUI]DateView: called onTimeUpdated()
09-13 14:18:00.050  1591  1591 D KeyguardUpdateMonitor: handleTimeUpdate
09-13 14:18:00.262  6708  6823 W jxcore-log: Initializing JXcore engine
09-13 14:18:00.262  6708  6823 W jxcore-log: JXcore engine is ready
,09-13 14:18:00.362  6823  6823 W Thread-762: type=1400 audit(0.0:162): avc: denied { ioctl } for path="socket:[7664]" dev="sockfs" ino=7664 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,09-13 14:18:00.362  6823  6823 W Thread-762: type=1400 audit(0.0:163): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
09-13 14:18:00.362  6823  6823 W Thread-762: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[8431]" dev="sockfs" ino=8431 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
09-13 14:18:00.362  6823  6823 W Thread-762: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
09-13 14:18:00.362  6823  6823 W Thread-762: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[31015]" dev="sockfs" ino=31015 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
09-13 14:18:00.411  6708  6823 W jxcore-log: Starting JXcore engine
,09-13 14:18:00.480   329   354 E GBMv2   : DFP En is all cleared set to be enabled
09-13 14:18:00.480   329   354 E GBMv2   : Set value is all cleared set the max
09-13 14:18:00.480   329   354 I GBMv2   : DFP Enabled. Ignore VFP set
,09-13 14:18:00.563  6708  6823 W jxcore-log: Platform android
09-13 14:18:00.563  6708  6823 W jxcore-log: 
09-13 14:18:00.564  6708  6823 W jxcore-log: Process ARCH arm
09-13 14:18:00.564  6708  6823 W jxcore-log: 
,09-13 14:18:00.894  6708  6823 I jxcore-log: JXcore Cordova bridge is ready!
09-13 14:18:00.894  6708  6823 I jxcore-log: 
09-13 14:18:00.895  6708  6823 W jxcore-log: JXcore engine is started
,09-13 14:18:00.911  6708  6820 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-13 14:18:00.918  6708  6708 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
09-13 14:18:03.052  6669  6669 W GAV2    : Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
09-13 14:18:03.054  1045  1700 I ActivityManager: Killing 5739:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,09-13 14:18:03.071  5711  5711 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
09-13 14:18:03.072  5711  5711 W System.err: android.os.DeadObjectException
09-13 14:18:03.072  5711  5711 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
09-13 14:18:03.072  5711  5711 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
09-13 14:18:03.072  5711  5711 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
09-13 14:18:03.072  5711  5711 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
09-13 14:18:03.072  5711  5711 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
09-13 14:18:03.072  5711  5711 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
09-13 14:18:03.073  5711  5711 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-13 14:18:03.073  5711  5711 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-13 14:18:03.073  5711  5711 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-13 14:18:03.073  5711  5711 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-13 14:18:03.073  5711  5711 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 14:18:03.073  5711  5711 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-13 14:18:03.073  5711  5711 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-13 14:18:03.073  5711  5711 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-13 14:18:03.074  5711  5711 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
09-13 14:18:03.074  5711  5711 W System.err: android.os.DeadObjectException
09-13 14:18:03.074  5711  5711 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
09-13 14:18:03.074  5711  5711 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
09-13 14:18:03.074  5711  5711 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
09-13 14:18:03.074  5711  5711 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
09-13 14:18:03.074  5711  5711 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
09-13 14:18:03.074  5711  5711 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
09-13 14:18:03.074  5711  5711 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-13 14:18:03.074  5711  5711 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-13 14:18:03.074  5711  5711 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-13 14:18:03.074  5711  5711 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-13 14:18:03.074  5711  5711 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 14:18:03.074  5711  5711 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-13 14:18:03.076  5711  5711 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-13 14:18:03.076  5711  5711 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-13 14:18:03.076  5711  5711 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
09-13 14:18:03.076  5711  5711 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
09-13 14:18:03.294  1045  1982 W libprocessgroup: failed to open /acct/uid_1000/pid_5739/cgroup.procs: No such file or directory
09-13 14:18:03.295  1045  1982 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,09-13 14:18:03.304  5711  5711 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
09-13 14:18:03.305  5711  5711 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
09-13 14:18:03.349  1045  1874 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=6832 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
09-13 14:18:03.350  5711  5711 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,09-13 14:18:03.398  6832  6832 D UEI.SmartControl: Quickset Services start...
09-13 14:18:03.399  6832  6832 I UEI.SmartControl: Manufacture = LGE
09-13 14:18:03.399  6832  6832 D UEI.SmartControl: Id = LGNevo
09-13 14:18:03.400  6832  6832 D UEI.SmartControl: File observer start...
09-13 14:18:03.400  6832  6832 E UEI.SmartControl: IR Port is disabled: false
09-13 14:18:03.400  6832  6832 D UEI.SmartControl: Starting file observer...
09-13 14:18:03.401  6832  6832 D UEI.SmartControl: Extracting JNI libs...
09-13 14:18:03.401  6832  6832 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
,09-13 14:18:03.446  6832  6832 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
09-13 14:18:03.447  6832  6832 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
09-13 14:18:03.447  6832  6832 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,09-13 14:18:03.466  6832  6832 I UEI.SmartControl: --- Selecting new region: 6
,09-13 14:18:03.467  6832  6832 I UEI.SmartControl: Model = LG-D855
09-13 14:18:03.468  6832  6832 D UEI.SmartControl: QS Service created
09-13 14:18:03.476  6832  6832 I UEI.SmartControl: Service initServices...
09-13 14:18:03.479  6832  6832 D UEI.SmartControl: QS start get config
,09-13 14:18:03.513  6832  6832 D UEI.SmartControl: Loading JNI Libs...
,09-13 14:18:03.753  6832  6832 I UEI.SmartControl: Supports setup maps: true
,09-13 14:18:03.756  6832  6832 D UEI.SmartControl: QS start statue = true Error code = 0
09-13 14:18:03.756  6832  6832 I UEI.SmartControl: QS version = v2.7.10.1_RC1
09-13 14:18:03.756  6832  6832 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
09-13 14:18:03.756  6832  6832 I UEI.SmartControl: ### init IR Blaster...
09-13 14:18:03.760  6832  6832 D serial_port: Configuring serial port
09-13 14:18:03.763  6832  6832 E UEI.SmartControl: UEIBLaster setting for 616
09-13 14:18:03.763  6832  6832 I UEI.SmartControl: Setting serial record hearder size = 2
09-13 14:18:03.763  6832  6832 I UEI.SmartControl: configuring settings for MAXQ616
09-13 14:18:03.763  6832  6832 I UEI.SmartControl: Get version...
09-13 14:18:03.779  6832  6855 D UEI.SmartControl: serial port data available: 21
,09-13 14:18:03.807  6832  6832 D UEI.SmartControl: MAXQ616 A2-X4 software.
09-13 14:18:03.807  6832  6832 I UEI.SmartControl: IR Blaster version: 256702256704300002
,09-13 14:18:03.808  6832  6832 I UEI.SmartControl: QS saving settings...
09-13 14:18:03.810  6832  6832 D UEI.SmartControl: IR Blaster version: 25672567
09-13 14:18:03.826  6832  6855 D UEI.SmartControl: serial port data available: 4
,09-13 14:18:03.864  6832  6858 I UEI.SmartControl: Device manager: loading config....
,09-13 14:18:03.865  6832  6858 D UEI.SmartControl: ----------- loading internal config...
,09-13 14:18:03.870  6832  6832 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
09-13 14:18:03.873  6832  6832 E UEI.SmartControl: Services init done
09-13 14:18:03.873  6832  6832 D UEI.SmartControl: QS Service init finished
09-13 14:18:03.875  6832  6832 D UEI.SmartControl: QS Service version name: 2.1.91
,09-13 14:18:03.875  6832  6832 D UEI.SmartControl: QS Service version code: 201091
09-13 14:18:03.877  6832  6832 D UEI.SmartControl: Service requested: Control
,09-13 14:18:03.883  6832  6832 D UEI.SmartControl: Request IControl service: devices are loaded...
09-13 14:18:03.883  6832  6858 E UEI.SmartControl: Loading SETTINGS...
09-13 14:18:03.888  5711  5711 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
09-13 14:18:03.889  6832  6847 I UEI.SmartControl: ------ IControl API: 11
09-13 14:18:03.890  1045  1982 I ActivityManager: Killing 5711:com.lge.qremote/u0a112 (adj 15): empty #17
09-13 14:18:03.890  6832  6847 I UEI.SmartControl: Registering callback...
09-13 14:18:03.895  6832  6858 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,09-13 14:18:03.910  6832  6857 I UEI.SmartControl: Notify AllClients services are ready: 0
09-13 14:18:03.910  6832  6857 D UEI.SmartControl: -----service ready thread exits
,09-13 14:18:04.004  1045  1582 W libprocessgroup: failed to open /acct/uid_10112/pid_5711/cgroup.procs: No such file or directory
,09-13 14:18:04.009  6832  6832 D UEI.SmartControl: Internal service binding...
09-13 14:18:04.040  6669  6763 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,09-13 14:18:04.865  1045  1367 D PowerManagerServiceEx: acquireWakeLockInternal: lock=1061446684, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1045
,09-13 14:18:04.905  2588  2588 D [Concierge]Service: onStartCommand(). Type : 9
,09-13 14:18:04.929  1045  1045 D PowerManagerServiceEx: releaseWakeLockInternal: lock=1061446684 [*alarm*], flags=0x0
,09-13 14:18:04.958  4535  6867 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,09-13 14:18:05.095  2879  2879 I MusicWidget: mDelayedStopHandler : unbind
,09-13 14:18:05.097  2161  2161 I MusicBrowser: [MediaPlaybackService.java:2869:onUnbind()] oooooo 
09-13 14:18:05.097  2161  2161 I MusicBrowser: [MediaPlaybackService.java:2076:saveQueue()] oooooo {full=true}
09-13 14:18:05.098  2161  2161 I MusicBrowser: [MediaPlaybackService.java:2081:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
09-13 14:18:05.101  2161  2161 D MusicBrowser: [MediaPlaybackService.java:2161:saveQueue()] oooooo {queue=}
09-13 14:18:05.101  2161  2161 D MusicBrowser: [MediaPlaybackService.java:2163:saveQueue()] oooooo {mCardId=-1}
09-13 14:18:05.102  2161  2161 D MusicBrowser: [MediaPlaybackService.java:2198:saveQueue()] oooooo {curpos=-1}
09-13 14:18:05.103  2161  2161 I MusicBrowser: [MediaPlaybackService.java:2046:onDestroy()] oooooo 
09-13 14:18:05.104  2161  2161 I MusicBrowser: [MediaPlaybackService.java:8635:clearReceiver()] oooooo 
09-13 14:18:05.105  1045  1060 I MediaFocusControl:  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@20cf5228com.lge.music.MediaPlaybackService$5@163e5b41
09-13 14:18:05.105  2161  2161 D MusicBrowser: [MediaPlaybackService.java:8669:clearReceiver()] oooooo abandonAudioFocus : 1
09-13 14:18:05.106  2161  2161 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-13 14:18:05.106  2161  2161 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
,09-13 14:18:05.109  2161  2161 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-13 14:18:05.110  2161  2161 I MusicBrowser: [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$27@1f2af937
09-13 14:18:05.110  2161  2161 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-13 14:18:05.111  2161  2161 I MusicBrowser: [MusicUtils.java:6801:endNotiTimer()] oooooo endNotiTimer
09-13 14:18:05.111  2161  2161 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-13 14:18:05.122  2161  2161 I MusicBrowser: [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
09-13 14:18:05.122  2161  2161 I MusicBrowser: [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
09-13 14:18:05.122  2161  2161 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
,09-13 14:18:05.132  2161  2161 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-13 14:18:05.133  2161  2161 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-13 14:18:05.133  2161  2161 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-13 14:18:05.134  2161  2161 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
,09-13 14:18:05.142  2161  2161 I MusicBrowser: [MusicUtils.java:10406:isAKACoverSupported()] oooooo aka not support!
09-13 14:18:05.144  2161  2161 I MusicBrowser: [MediaPlaybackService.java:6704:release()] oooooo 
09-13 14:18:05.144  2161  2161 I MusicBrowser: [MediaPlaybackService.java:6665:stop()] oooooo 
09-13 14:18:05.144  2161  2161 V MediaPlayer[Native]: reset
,09-13 14:18:05.151  2161  2161 V MediaPlayer[Native]: setListener
09-13 14:18:05.151  2161  2161 V MediaPlayer[Native]: disconnect
09-13 14:18:05.151  2161  2161 V MediaPlayer[Native]: destructor
09-13 14:18:05.151   313  2159 V AudioFlinger: releasing 18 from 2161 for -1
09-13 14:18:05.151   313  2159 V AudioFlinger:  decremented refcount to 0
09-13 14:18:05.151   313  2159 V AudioFlinger: purging stale effects
09-13 14:18:05.151  2161  2161 V MediaPlayer[Native]: disconnect
09-13 14:18:05.153  2161  2161 D MusicBrowser: [MusicUtils.java:615:getSmartShareVersion()] oooooo versionCode:305000
09-13 14:18:05.155  2161  2161 I SmartShareClient: [SmartShareManagerClient] smartshare client supported version code: 305000
09-13 14:18:05.156  2161  2161 I SmartShareClient: [SmartShareManagerClient] smartshare client enabled
09-13 14:18:05.157  2161  2161 I MusicBrowser: [MusicUtils.java:787:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000018
09-13 14:18:05.157  2161  2161 I MusicBrowser: [MusicUtils.java:635:getSmartShareVersion()] oooooo SmartshareVersion:953
09-13 14:18:05.157  2161  2161 V MusicBrowser: [MediaPlaybackService.java:9312:terminateSmartShareClient()] oooooo 
09-13 14:18:05.158  2161  2161 I SmartShareClient: [SmartShareManagerClient] unregisterListener: 228645094
09-13 14:18:05.158  2161  2161 W SmartShareClient: [SmartShareManagerClient] unregisterListener invalid listener: 228645094
09-13 14:18:05.162  2161  2161 I SmartShareClient: [SmartShareManagerClient] terminate service: 2161/MediaPlaybackService/301440853
09-13 14:18:05.165  2161  2161 E HomeCloudIF: unregiterHomeCloudBroadcast(), Illegal argument.
09-13 14:18:05.166  2161  2161 I SmartShareClient: [SmartShareManagerClient] unbindService context:android.app.Application@37769e27
,09-13 14:18:05.168  2161  2161 V CloudHub: [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.2.1, versionCode=202001, state=0
09-13 14:18:05.168  2161  2161 V CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
09-13 14:18:05.169  2161  2161 I CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
09-13 14:18:05.170  2161  2161 D MusicBrowser: [MediaPlaybackService.java:9007:setStopForeground()] oooooo bValue : true
09-13 14:18:05.173  2161  2161 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29997
09-13 14:18:05.173  1045  1910 I ActivityManager: Killing 6408:com.android.calendar/u0a13 (adj 15): empty #17
09-13 14:18:05.364  1045  1928 W libprocessgroup: failed to open /acct/uid_10013/pid_6408/cgroup.procs: No such file or directory
,09-13 14:18:06.510  1805  6587 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,09-13 14:18:06.533   308  6891 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,09-13 14:18:06.535   308  6891 D libc-netbsd: res_queryN name = cloudconfig.googleapis.com, class = 1, type = 1
,09-13 14:18:06.535   308  6891 D libc-netbsd: res_queryN name = cloudconfig.googleapis.com succeed
,09-13 14:18:06.771  1805  1805 I ConfigFetchService: fetch service done; releasing wakelock
,09-13 14:18:06.772  1805  1805 I ConfigFetchService: stopping self
09-13 14:18:06.788  2117  2117 I ConfigService: onDestroy
,09-13 14:18:08.870  6832  6856 D serial_port: close(fd = 25)
,09-13 14:18:08.871  6832  6859 D UEI.SmartControl: Internal timer expired: 1
,09-13 14:18:08.871  6832  6859 D UEI.SmartControl: unbind internal service
,09-13 14:18:08.880  6832  6856 I UEI.SmartControl: Serial port is closed.
,09-13 14:18:08.888  6832  6832 D UEI.SmartControl: Service.onUnbind: IControl
,09-13 14:18:08.912  6832  6832 D UEI.SmartControl: Service.onDestroy
09-13 14:18:08.912  6832  6832 D UEI.SmartControl: Lock is in USE false
09-13 14:18:08.912  6832  6832 D UEI.SmartControl: unbind internal service
09-13 14:18:08.912  6832  6832 I UEI.SmartControl: Serial port is closed.
09-13 14:18:08.912  6832  6832 I UEI.SmartControl: Serial port is closed.
09-13 14:18:08.912  6832  6832 D UEI.SmartControl: Blaster closed
09-13 14:18:08.912  6832  6832 D UEI.SmartControl: Shut down QS...
09-13 14:18:08.912  6832  6832 D UEI.SmartControl: Stopping QS lib
,09-13 14:18:08.913  6832  6832 D UEI.SmartControl: QS lib stop result = true
09-13 14:18:08.913  6832  6832 D UEI.SmartControl: Stopped QS lib
09-13 14:18:08.913  6832  6832 D UEI.SmartControl: Stopped file observer...
09-13 14:18:08.913  6832  6832 D UEI.SmartControl: QS shutdown complete
09-13 14:18:11.362  6708  6823 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-13 14:18:11.362  6708  6823 I jxcore-log: 
,09-13 14:18:11.364  6708  6823 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-13 14:18:11.364  6708  6823 I jxcore-log: 
,09-13 14:18:11.370  6708  6823 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 14:18:11.370  6708  6823 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 14:18:11.370  6708  6823 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 14:18:11.370  6708  6823 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 14:18:11.370  6708  6823 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 14:18:11.370  6708  6823 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 14:18:11.370  6708  6823 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 14:18:11.370  6708  6823 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 14:18:11.373  6708  6823 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 14:18:11.376  6708  6823 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-13 14:18:11.376  6708  6823 I jxcore-log: 
09-13 14:18:11.377  6708  6823 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-13 14:18:11.377  6708  6823 I jxcore-log: 
,09-13 14:18:11.616  1045  1116 I ActivityManager: Waited long enough for: ServiceRecord{359d9985 u0 com.google.android.gms/.wearable.service.WearableService}
,09-13 14:18:11.902  6708  6823 I jxcore-log: Unit Test app is loaded
09-13 14:18:11.902  6708  6823 I jxcore-log: 
,09-13 14:18:11.911  6708  6708 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-13 14:18:11.918  6708  6823 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 14:18:11.918  6708  6823 I jxcore-log: 
09-13 14:18:11.935  6708  6823 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 14:18:11.935  6708  6823 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3972aa36 added. We now have 2 listener(s)
,09-13 14:18:11.936  1045  1874 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 14:18:11.938  6708  6823 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-13 14:18:11.938  6708  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 14:18:11.938  6708  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 14:18:11.939  6708  6823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 14:18:11.939  6708  6823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1731d37 added. We now have 2 listener(s)
09-13 14:18:11.939  6708  6823 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 14:18:11.939  6708  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-13 14:18:11.941  6708  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 14:18:11.943  6708  6823 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 14:18:11.943  6708  6823 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 14:18:11.943  6708  6823 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 14:18:11.943  6708  6823 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 14:18:11.943  6708  6823 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 14:18:11.943  6708  6823 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 14:18:11.943  6708  6823 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 14:18:11.943  6708  6823 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 14:18:11.944  6708  6823 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 14:18:11.944  6708  6823 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 14:18:11.945  6708  6823 D ExecuteNativeTests: Running unit tests
09-13 14:18:11.946  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 14:18:11.946  6708  6823 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 14:18:11.946  6708  6823 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1674280d added. We now have 3 listener(s)
09-13 14:18:11.946  1045  2020 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 14:18:11.947  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 14:18:11.950  6708  6823 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-13 14:18:11.950  6708  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 14:18:11.950  6708  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 14:18:11.950  6708  6823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 14:18:11.950  6708  6823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ab733c2 added. We now have 3 listener(s)
09-13 14:18:11.950  6708  6823 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 14:18:11.951  6708  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-13 14:18:11.954  6708  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 14:18:11.956  6708  6823 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 14:18:11.956  6708  6823 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 14:18:11.956  6708  6823 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 14:18:11.956  6708  6823 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 14:18:11.956  6708  6823 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 14:18:11.956  6708  6823 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 14:18:11.956  6708  6823 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 14:18:11.956  6708  6823 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 14:18:11.958  6708  6823 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 14:18:11.958  6708  6823 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-13 14:18:11.960  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 14:18:11.962  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 14:18:15.184  2161  2161 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19987
,09-13 14:18:15.546  1045  1367 V AlarmManager: RTC_WAKEUP set : Alarm{1f3a93d9 type 0 when 1473769092339 com.android.vending} when 1473769092339
,09-13 14:18:15.640  1045  1061 V SIM_STK : Menu title from STK is T-Mobile
,09-13 14:18:15.762  6178  6178 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.
,09-13 14:18:22.114  6708  6823 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 14:18:22.114  6708  6823 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35ac59c3 added. We now have 4 listener(s)
,09-13 14:18:22.115  1045  2019 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 14:18:22.122  6708  6823 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-13 14:18:22.122  6708  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 14:18:22.122  6708  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 14:18:22.122  6708  6823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 14:18:22.122  6708  6823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d8dd240 added. We now have 4 listener(s)
09-13 14:18:22.122  6708  6823 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 14:18:22.123  6708  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-13 14:18:22.125  6708  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 14:18:22.128  6708  6823 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 14:18:22.128  6708  6823 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 14:18:22.128  6708  6823 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 14:18:22.128  6708  6823 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 14:18:22.128  6708  6823 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 14:18:22.128  6708  6823 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 14:18:22.128  6708  6823 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 14:18:22.128  6708  6823 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 14:18:22.130  6708  6823 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 14:18:22.130  6708  6823 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 14:18:22.133  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 14:18:22.134  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 14:18:22.139  6708  6823 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-13 14:18:22.140  6708  6823 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 14:18:22.140  6708  6823 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 14:18:22.140  6708  6823 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 14:18:22.141  6708  6823 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-13 14:18:22.143  6708  6823 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-13 14:18:22.145  6708  6823 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-13 14:18:22.145  6708  6823 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-13 14:18:22.145  6708  6823 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 14:18:22.145  6708  6823 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 14:18:22.145  6708  6823 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 14:18:22.145  6708  6823 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 14:18:22.146  6708  6823 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 14:18:22.146  6708  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:22.146  6708  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-13 14:18:22.146  6708  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 14:18:22.146  6708  6823 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35ac59c3 removed from the list
09-13 14:18:22.146  6708  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 14:18:22.146  6708  6823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d8dd240 removed from the list
09-13 14:18:22.146  6708  6823 D io.jxcore.node.ConnectivityMonitor: stop
09-13 14:18:22.147  6708  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:22.149  6708  6823 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-13 14:18:22.150  6708  6823 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 14:18:22.150  6708  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:22.150  6708  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:22.150  6708  6823 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35ac59c3 not in the list
09-13 14:18:22.150  6708  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 14:18:22.150  6708  6823 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d8dd240 not in the list
09-13 14:18:22.150  6708  6823 D io.jxcore.node.ConnectivityMonitor: stop
09-13 14:18:22.150  6708  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:22.150  6708  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:22.157  6708  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-13 14:18:22.157  6708  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> ,10:010:010:010:010:010]
09-13 14:18:22.157  6708  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-13 14:18:22.158  6708  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-13 14:18:22.158  6708  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-13 14:18:22.158  6708  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-13 14:18:22.158  6708  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-13 14:18:22.158  6708  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-13 14:18:22.158  6708  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-13 14:18:22.158  6708  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-13 14:18:22.158  6708  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-13 14:18:22.158  6708  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-13 14:18:22.158  6708  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-13 14:18:22.158  6708  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,09-13 14:18:22.158  6708  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,09-13 14:18:22.158  6708  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-13 14:18:22.158  6708  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-13 14:18:22.158  6708  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-13 14:18:22.158  6708  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-13 14:18:22.158  6708  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-13 14:18:22.158  6708  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-13 14:18:22.158  6708  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-13 14:18:22.158  6708  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-13 14:18:22.158  6708  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-13 14:18:22.158  6708  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-13 14:18:22.158  6708  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-13 14:18:22.159  6708  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-13 14:18:22.159  6708  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-13 14:18:22.159  6708  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-13 14:18:22.159  6708  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-13 14:18:22.159  6708  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-13 14:18:22.159  6708  6823 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 14:18:22.159  6708  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:22.159  6708  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:22.159  6708  6823 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35ac59c3 not in the list
09-13 14:18:22.159  6708  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 14:18:22.159  6708  6823 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d8dd240 not in the list
09-13 14:18:22.159  6708  6823 D io.jxcore.node.ConnectivityMonitor: stop
09-13 14:18:22.159  6708  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:22.159  6708  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:22.160  6708  6823 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-13 14:18:22.162  6708  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 14:18:22.168  6708  6823 V io.jxcore.n,ode.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 14:18:22.168  6708  6823 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 14:18:22.168  6708  6823 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 14:18:22.168  6708  6823 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 14:18:22.168  6708  6823 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 14:18:22.168  6708  6823 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 14:18:22.168  6708  6823 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 14:18:22.168  6708  6823 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 14:18:22.170  6708  6823 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 14:18:22.170  6708  6823 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 14:18:22.171  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 14:18:22.173  6708  6823 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 14:18:22.173  6708  6823 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-13 14:18:22.173  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 14:18:22.173  6708  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-13 14:18:22.173  6708  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 14:18:22.173  6708  6823 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-13 14:18:22.178  6708  6823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-13 14:18:22.178  1045  1946 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 14:18:22.185  6708  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-13 14:18:22.192  6708  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-13 14:18:22.194  6708  6823 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
09-13 14:18:22.194  6708  6823 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 14:18:22.195  6708  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-13 14:18:22.197  6708  6823 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-13 14:18:22.197  6708  6823 I io.jxcore.node.ConnectionHelper: start: OK
,09-13 14:18:22.200  6708  6823 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
09-13 14:18:22.201  6708  6823 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
09-13 14:18:22.201  6708  6823 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 14:18:22.203  6708  6823 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-13 14:18:22.203  6708  6823 V io.jxcore.node.ConnectivityMonitor: start: Already started
09-13 14:18:22.203  6708  6823 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 14:18:22.203  6708  6823 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-13 14:18:22.203  6708  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-13 14:18:22.203  6708  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 14:18:22.203  6708  6823 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 14:18:22.207  6708  6823 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 14:18:22.208  6708  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-13 14:18:22.209  6708  6823 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,09-13 14:18:22.209  6708  6823 I io.jxcore.node.ConnectionHelper: start: OK
,09-13 14:18:22.210  6708  6823 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 14:18:22.210  6708  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:22.210  6708  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-13 14:18:22.210  6708  6823 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35ac59c3 not in the list
09-13 14:18:22.210  6708  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 14:18:22.210  6708  6823 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d8dd240 not in the list
09-13 14:18:22.210  6708  6823 D io.jxcore.node.ConnectivityMonitor: stop
09-13 14:18:22.210  6708  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:22.212  6708  6823 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-13 14:18:22.322  1045  1947 I art     : Explicit concurrent mark sweep GC freed 26935(1379KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/64MB, paused 1.724ms total 107.478ms
,09-13 14:18:22.325  6708  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 14:18:22.328  6708  6823 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 14:18:22.328  6708  6823 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 14:18:22.328  6708  6823 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 14:18:22.328  6708  6823 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 14:18:22.328  6708  6823 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 14:18:22.328  6708  6823 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 14:18:22.328  6708  6823 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 14:18:22.328  6708  6823 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 14:18:22.329  6708  6823 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 14:18:22.329  6708  6823 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 14:18:22.330  6708  6823 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 14:18:22.330  6708  6823 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-13 14:18:22.330  6708  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-13 14:18:22.330  6708  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 14:18:22.330  6708  6823 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 14:18:22.333  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 14:18:22.335  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 14:18:22.341  6708  6823 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 14:18:22.342  6708  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-13 14:18:22.343  6708  6823 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-13 14:18:22.344  6708  6823 I io.jxcore.node.ConnectionHelper: start: OK
09-13 14:18:22.344  6708  6823 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
09-13 14:18:22.344  6708  6823 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
09-13 14:18:22.344  6708  6823 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 14:18:22.347  6708  6823 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 14:18:22.347  6708  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 14:18:22.347  6708  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-13 14:18:22.348  6708  6823 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35ac59c3 not in the list
09-13 14:18:22.348  6708  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 14:18:22.348  6708  6823 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d8dd240 not in the list
09-13 14:18:22.348  6708  6823 D io.jxcore.node.ConnectivityMonitor: stop
09-13 14:18:22.348  6708  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:22.351  6708  6823 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-13 14:18:22.352  6708  6823 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 14:18:22.352  6708  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:22.352  6708  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:22.353  6708  6823 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35ac59c3 not in the list
09-13 14:18:22.353  6708  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 14:18:22.353  6708  6823 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d8dd240 not in the list
09-13 14:18:22.353  6708  6823 D io.jxcore.node.ConnectivityMonitor: stop
09-13 14:18:22.353  6708  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:22.353  6708  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:22.356  6708  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-13 14:18:22.356  6708  6823 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 14:18:22.356  6708  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:22.356  6708  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:22.357  6708  6823 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35ac59c3 not in the list
09-13 14:18:22.357  6708  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 14:18:22.357  6708  6823 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d8dd240 not in the list
09-13 14:18:22.357  6708  6823 D io.jxcore.node.ConnectivityMonitor: stop
09-13 14:18:22.357  6708  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:22.357  6708  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 14:18:22.359  6708  6823 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-13 14:18:22.359  6708  6823 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 14:18:22.360  6708  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:22.360  6708  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:22.360  6708  6823 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35ac59c3 not in the list
09-13 14:18:22.360  6708  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 14:18:22.360  6708  6823 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d8dd240 not in the list
09-13 14:18:22.360  6708  6823 D io.jxcore.node.ConnectivityMonitor: stop
09-13 14:18:22.360  6708  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:22.360  6708  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:22.363  6708  6823 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-13 14:18:22.363  6708  6823 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 14:18:22.363  6708  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:22.363  6708  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:22.363  6708  6823 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35ac59c3 not in the list
09-13 14:18:22.363  6708  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 14:18:22.363  6708  6823 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d8dd240 not in the list
09-13 14:18:22.364  6708  6823 D io.jxcore.node.ConnectivityMonitor: stop
09-13 14:18:22.364  6708  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:22.364  6708  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:22.365  6708  6823 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-13 14:18:22.367  6708  6823 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 14:18:22.367  6708  6823 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 14:18:22.367  6708  6823 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 14:18:22.367  6708  6823 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-13 14:18:22.367  6708  6823 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 14:18:22.367  6708  6823 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 14:18:22.367  6708  6823 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.Bl,uetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 14:18:22.367  6708  6823 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-13 14:18:22.367  6708  6823 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 14:18:22.367  6708  6823 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 14:18:22.367  6708  6823 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 14:18:22.368  6708  6823 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 14:18:22.368  6708  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:22.368  6708  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:22.368  6708  6823 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35ac59c3 not in the list
09-13 14:18:22.368  6708  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 14:18:22.368  6708  6823 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d8dd240 not in the list
09-13 14:18:22.368  6708  6823 D io.jxcore.node.ConnectivityMonitor: stop
09-13 14:18:22.368  6708  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:22.368  6708  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:22.369  6708  6823 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 14:18:22.369  6708  6823 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-13 14:18:22.369  6708  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-13 14:18:22.373  6708  6823 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 14:18:22.373  6708  6823 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-13 14:18:22.374  6708  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-13 14:18:22.374  6708  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-13 14:18:22.374  6708  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-13 14:18:22.374  6708  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-13 14:18:22.374  6708  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-13 14:18:22.374  6708  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-13 14:18:22.374  6708  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-13 14:18:22.374  6708  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-13 14:18:22.374  6708  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-13 14:18:22.374  6708  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-13 14:18:22.374  6708  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-13 14:18:22.374  6708  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-13 14:18:22.374  6708  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-13 14:18:22.374  6708  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-13 14:18:22.374  6708  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-13 14:18:22.374  6708  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-13 14:18:22.374  6708  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-13 14:18:22.374  6708  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-13 14:18:22.374  6708  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-13 14:18:22.374  6708  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-13 14:18:22.375  6708  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-13 14:18:22.375  6708  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-13 14:18:22.375  6708  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-13 14:18:22.375  6708  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-13 14:18:22.375  6708  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-13 14:18:22.375  6708  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-13 14:18:22.375  6708  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-13 14:18:22.375  6708  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-13 14:18:22.375  6708  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-13 14:18:22.375  6708  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-13 14:18:22.375  6708  6823 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-13 14:18:22.375  6708  6823 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-13 14:18:22.375  6708  6823 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-13 14:18:22.376  6708  6823 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 14:18:22.376  6708  6823 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-13 14:18:22.376  6708  6823 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-13 14:18:22.376  6708  6823 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 14:18:22.376  6708  6823 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-13 14:18:22.376  6708  6823 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-13 14:18:22.380  6708  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-13 14:18:22.381  6708  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-13 14:18:22.382  6708  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-13 14:18:22.382  6708  6823 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-13 14:18:22.383  6708  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-13 14:18:22.383  6708  6823 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-13 14:18:22.383  6708  6823 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 14:18:22.383  6708  6823 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-13 14:18:22.385  6708  6823 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 14:18:22.386  6708  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:22.386  6708  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:22.386  6708  6910 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 859)
09-13 14:18:22.387  6708  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-13 14:18:22.388  6708  6823 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35ac59c3 not in the list
09-13 14:18:22.388  6708  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 14:18:22.388  6708  6823 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d8dd240 not in the list
09-13 14:18:22.388  6708  6823 D io.jxcore.node.ConnectivityMonitor: stop
09-13 14:18:22.388  6708  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:22.388  6708  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:22.389  6708  6823 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-13 14:18:22.390  6708  6823 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 14:18:22.390  6708  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:22.390  6708  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:22.390  6708  6823 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35ac59c3 not in the list
09-13 14:18:22.390  6708  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 14:18:22.390  6708  6823 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d8dd240 not in the list
09-13 14:18:22.390  6708  6823 D io.jxcore.node.ConnectivityMonitor: stop
09-13 14:18:22.390  6708  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:22.390  6708  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:22.391  6708  6823 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-13 14:18:22.393  6708  6823 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 14:18:22.393  6708  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:22.393  6708  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:22.393  6708  6823 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35ac59c3 not in the list
09-13 14:18:22.393  6708  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 14:18:22.393  6708  6823 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d8dd240 not in the list
09-13 14:18:22.393  6708  6823 D io.jxcore.node.ConnectivityMonitor: stop
09-13 14:18:22.393  6708  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:22.393  6708  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:22.394  6708  6823 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-13 14:18:22.395  6708  6823 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-13 14:18:22.395  6708  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-13 14:18:22.395  6708  6823 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-13 14:18:22.395  6708  6823 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-13 14:18:22.395  6708  6823 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-13 14:18:22.395  6708  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-13 14:18:22.395  6708  6823 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-13 14:18:22.395  6708  6823 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-13 14:18:22.395  6708  6823 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-13 14:18:22.395  6708  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-13 14:18:22.396  6708  6823 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-13 14:18:22.396  6708  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 859
09-13 14:18:22.396  6708  6823 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 14:18:22.396  6708  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:22.396  6708  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 859)
09-13 14:18:22.396  6708  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:22.396  6708  6823 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35ac59c3 not in the list
09-13 14:18:22.396  6708  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 14:18:22.396  6708  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 859)
09-13 14:18:22.396  6708  6823 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d8dd240 not in the list
09-13 14:18:22.396  6708  6823 D io.jxcore.node.ConnectivityMonitor: stop
09-13 14:18:22.396  6708  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:22.396  6708  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:22.397  6708  6823 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-13 14:18:22.398  6708  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 14:18:22.402  6708  6823 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 14:18:22.402  6708  6823 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 14:18:22.402  6708  6823 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 14:18:22.402  6708  6823 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 14:18:22.402  6708  6823 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 14:18:22.402  6708  6823 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 14:18:22.402  6708  6823 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 14:18:22.402  6708  6823 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 14:18:22.404  6708  6823 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 14:18:22.404  6708  6823 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 14:18:22.404  6708  6823 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 14:18:22.404  6708  6823 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-13 14:18:22.404  6708  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-13 14:18:22.404  6708  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 14:18:22.404  6708  6823 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 14:18:22.406  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 14:18:22.408  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 14:18:22.410  6708  6823 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 14:18:22.411  6708  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-13 14:18:22.413  6708  6823 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-13 14:18:22.413  6708  6823 I io.jxcore.node.ConnectionHelper: start: OK
09-13 14:18:22.413  6708  6823 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 14:18:22.413  6708  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:22.413  6708  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-13 14:18:22.413  6708  6823 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35ac59c3 not in the list
09-13 14:18:22.413  6708  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 14:18:22.413  6708  6823 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d8dd240 not in the list
09-13 14:18:22.413  6708  6823 D io.jxcore.node.ConnectivityMonitor: stop
09-13 14:18:22.413  6708  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:22.416  6708  6823 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 14:18:22.416  6708  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:22.416  6708  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:22.416  6708  6823 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35ac59c3 not in the list
09-13 14:18:22.417  6708  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 14:18:22.417  6708  6823 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d8dd240 not in the list
09-13 14:18:22.417  6708  6823 D io.jxcore.node.ConnectivityMonitor: stop
09-13 14:18:22.417  6708  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:22.417  6708  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:22.419  6708  6823 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-13 14:18:22.419  6708  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 14:18:22.422  6708  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-13 14:18:22.423  6708  6823 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-13 14:18:22.423  6708  6823 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-13 14:18:22.424  6708  6708 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-13 14:18:22.424  6708  6823 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-13 14:18:22.424  6708  6823 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-13 14:18:22.425  1045  1700 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 14:18:22.425  6708  6823 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 14:18:22.425  6708  6823 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-13 14:18:22.426  6708  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-13 14:18:22.426  6708  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-13 14:18:22.426  6708  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:22.426  6708  6823 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-13 14:18:22.426  6708  6913 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 14:18:22.426  6708  6708 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-13 14:18:22.426  6708  6823 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35ac59c3 not in the list
09-13 14:18:22.426  6708  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 14:18:22.426  6708  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-13 14:18:22.427  6708  6823 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-13 14:18:22.427  6708  6823 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-13 14:18:22.427  3936  3966 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=84 mFd=82
09-13 14:18:22.428  6708  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-13 14:18:22.428  6708  6913 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-13 14:18:22.428  6708  6913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-13 14:18:22.428  6708  6913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-13 14:18:22.429  6708  6823 D BluetoothLeScanner: could not find callback wrapper
09-13 14:18:22.430  6708  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 14:18:22.430  6708  6823 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-13 14:18:22.430  6708  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:22.430  6708  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:22.431  6708  6823 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 14:18:22.432  6708  6708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 14:18:22.432  6708  6708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 14:18:22.432  6708  6708 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-13 14:18:22.432  6708  6708 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 14:18:22.432  6708  6823 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d8dd240 not in the list
09-13 14:18:22.432  6708  6823 D io.jxcore.node.ConnectivityMonitor: stop
09-13 14:18:22.432  6708  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:22.432  6708  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:22.434  6708  6823 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-13 14:18:22.435  6708  6823 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-13 14:18:22.435  6708  6823 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-13 14:18:22.435  6708  6823 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 14:18:22.435  6708  6823 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 14:18:22.435  6708  6823 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 14:18:22.435  6708  6823 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 14:18:22.435  6708  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:22.435  6708  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:22.435  6708  6823 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35ac59c3 not in the list
09-13 14:18:22.435  6708  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 14:18:22.436  6708  6823 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d8dd240 not in the list
09-13 14:18:22.436  6708  6823 D io.jxcore.node.ConnectivityMonitor: stop
09-13 14:18:22.436  6708  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:22.436  6708  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:22.438  1045  1910 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 14:18:22.439  1045  1982 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 14:18:22.440  1045  2020 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 14:18:22.441  6708  6823 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 14:18:22.441  6708  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:22.441  6708  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:22.441  6708  6823 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35ac59c3 not in the list
09-13 14:18:22.441  6708  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 14:18:22.441  6708  6823 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d8dd240 not in the list
09-13 14:18:22.441  6708  6823 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 14:18:22.441  6708  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:22.441  6708  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:22.443  6708  6823 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 14:18:22.443  6708  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:22.443  6708  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:22.443  6708  6823 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35ac59c3 not in the list
09-13 14:18:22.443  6708  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 14:18:22.443  6708  6823 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d8dd240 not in the list
09-13 14:18:22.443  6708  6823 D io.jxcore.node.ConnectivityMonitor: stop
09-13 14:18:22.443  6708  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:22.443  6708  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:22.445  6708  6823 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-13 14:18:22.445  6708  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-13 14:18:22.445  6708  6823 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-13 14:18:22.446  6708  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-13 14:18:22.446  6708  6823 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-13 14:18:22.446  6708  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,09-13 14:18:22.448  6708  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-13 14:18:22.448  6708  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-13 14:18:22.449  6708  6823 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-13 14:18:22.449  6708  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-13 14:18:22.450  6708  6823 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-13 14:18:22.450  6708  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-13 14:18:22.450  6708  6823 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-13 14:18:22.450  6708  6823 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-13 14:18:22.451  6708  6823 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-13 14:18:22.451  6708  6823 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-13 14:18:22.452  6708  6823 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-13 14:18:22.452  6708  6823 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-13 14:18:22.452  6708  6823 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-13 14:18:22.452  6708  6823 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-13 14:18:22.459  6708  6914 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
09-13 14:18:22.459  6708  6914 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
09-13 14:18:22.470  6708  6914 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
09-13 14:18:22.470  6708  6914 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-13 14:18:22.472  6708  6916 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
09-13 14:18:22.472  6708  6916 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,09-13 14:18:22.472  6708  6914 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 14:18:22.472  6708  6916 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 14:18:22.472  6708  6914 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 14:18:22.472  6708  6914 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
09-13 14:18:22.474  6708  6916 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 14:18:22.475  6708  6916 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
09-13 14:18:22.477  6708  6921 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 912, name: IncomingSocketThread/Sender)
09-13 14:18:22.478  6708  6920 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 913, name: OutgoingSocketThread/Receiver)
09-13 14:18:22.478  6708  6920 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 913, thread name: OutgoingSocketThread/Receiver)
09-13 14:18:22.480  6708  6920 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-13 14:18:22.482  6708  6920 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 913, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
09-13 14:18:22.483  6708  6919 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 911, name: OutgoingSocketThread/Sender)
,09-13 14:18:22.488  6708  6922 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 914, name: IncomingSocketThread/Receiver)
,09-13 14:18:22.488  6708  6922 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 914, thread name: IncomingSocketThread/Receiver)
09-13 14:18:22.488  6708  6922 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-13 14:18:22.488  6708  6922 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 914, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
09-13 14:18:22.531  6708  6910 W LGMDMUISystemServiceAdapter: checkBluetoothPairing btPolicy: false
,09-13 14:18:22.532  6708  6910 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 859)
09-13 14:18:22.937  6708  6708 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-13 14:18:22.974  6708  6823 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
09-13 14:18:22.975  6708  6823 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
09-13 14:18:22.977  6708  6823 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@316007c5 Bundle[{}]
09-13 14:18:22.978  6708  6823 I io.jxcore.node.LifeCycleMonitor: start: OK
09-13 14:18:22.978  6708  6823 I io.jxcore.node.LifeCycleMonitor: stop: OK
09-13 14:18:22.979  6708  6823 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
09-13 14:18:22.979  6708  6823 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-13 14:18:22.980  6708  6823 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
09-13 14:18:22.981  6708  6823 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-13 14:18:22.995  6708  6930 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
09-13 14:18:22.995  6708  6930 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-13 14:18:23.513  6708  6930 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
,09-13 14:18:23.513  6708  6930 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-13 14:18:23.514  6708  6930 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-13 14:18:23.514  6708  6930 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 14:18:23.515  6708  6930 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-13 14:18:23.525  6708  6932 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
09-13 14:18:23.525  6708  6932 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-13 14:18:23.525  6708  6932 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 14:18:23.525  6708  6932 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 14:18:23.525  6708  6932 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
09-13 14:18:23.528  6708  6935 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 926, name: OutgoingSocketThread/Receiver)
09-13 14:18:23.528  6708  6935 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 926, thread name: OutgoingSocketThread/Receiver)
09-13 14:18:23.528  6708  6935 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-13 14:18:23.528  6708  6935 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 926, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
09-13 14:18:23.531  6708  6934 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 925, name: OutgoingSocketThread/Sender)
09-13 14:18:23.532  6708  6937 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 928, name: IncomingSocketThread/Receiver)
09-13 14:18:23.532  6708  6937 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 928, thread name: IncomingSocketThread/Receiver)
09-13 14:18:23.532  6708  6937 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-13 14:18:23.533  6708  6937 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 928, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
09-13 14:18:23.535  6708  6936 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 927, name: IncomingSocketThread/Sender)
,09-13 14:18:24.025  6708  6823 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 937)
09-13 14:18:24.026  6708  6823 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
09-13 14:18:24.026  6708  6823 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 938)
09-13 14:18:24.029  6708  6823 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 14:18:24.029  6708  6823 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@33f37b96 added. We now have 4 listener(s)
,09-13 14:18:24.032  1045  2038 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 14:18:24.035  6708  6823 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-13 14:18:24.035  6708  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 14:18:24.035  6708  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 14:18:24.036  6708  6823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 14:18:24.036  6708  6823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a578317 added. We now have 4 listener(s)
09-13 14:18:24.036  6708  6823 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 14:18:24.036  6708  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-13 14:18:24.040  6708  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 14:18:24.043  6708  6823 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 14:18:24.043  6708  6823 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 14:18:24.043  6708  6823 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 14:18:24.043  6708  6823 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 14:18:24.043  6708  6823 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 14:18:24.043  6708  6823 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 14:18:24.043  6708  6823 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 14:18:24.043  6708  6823 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 14:18:24.048  6708  6823 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 14:18:24.048  6708  6823 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 14:18:24.050  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 14:18:24.052  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 14:18:24.055  6708  6823 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 14:18:24.055  6708  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:24.055  6708  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-13 14:18:24.055  6708  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 14:18:24.055  6708  6823 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@33f37b96 removed from the list
09-13 14:18:24.055  6708  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 14:18:24.055  6708  6823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a578317 removed from the list
09-13 14:18:24.055  6708  6823 D io.jxcore.node.ConnectivityMonitor: stop
09-13 14:18:24.055  6708  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 14:18:24.059  6708  6823 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 14:18:24.059  6708  6823 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-13 14:18:24.059  6708  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-13 14:18:24.059  6708  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 14:18:24.059  6708  6823 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 14:18:24.065  6708  6823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-13 14:18:24.065  1045  2038 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 14:18:24.069  6708  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-13 14:18:24.072  6708  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-13 14:18:24.074  6708  6823 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 14:18:24.074  6708  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:24.076  6708  6823 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-13 14:18:27.077  6708  6823 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
09-13 14:18:27.077  6708  6823 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-13 14:18:27.091  6708  6823 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 14:18:27.091  6708  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 14:18:27.095  6708  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:27.096  6708  6823 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@33f37b96 not in the list
09-13 14:18:27.096  6708  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 14:18:27.096  6708  6823 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a578317 not in the list
09-13 14:18:27.096  6708  6823 D io.jxcore.node.ConnectivityMonitor: stop
09-13 14:18:27.096  6708  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:27.096  6708  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:27.097  6708  6823 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-13 14:18:27.098  6708  6823 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
09-13 14:18:27.098  6708  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
09-13 14:18:27.101  6708  6823 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-13 14:18:27.101  6708  6823 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-13 14:18:27.101  6708  6823 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-13 14:18:27.101  6708  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 14:18:27.103  6708  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-13 14:18:27.104  6708  6823 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-13 14:18:27.104  6708  6823 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,09-13 14:18:27.108  6708  6708 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-13 14:18:27.111  6708  6823 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-13 14:18:27.111  6708  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-13 14:18:27.111  6708  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 14:18:27.111  6708  6823 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 14:18:27.117  6708  6823 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-13 14:18:27.120  6708  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-13 14:18:27.122  6708  6823 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-13 14:18:27.123  6708  6823 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 14:18:27.123  6708  6823 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-13 14:18:27.123  6708  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-13 14:18:27.123  6708  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-13 14:18:27.123  6708  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:27.123  6708  6823 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-13 14:18:27.124  6708  6939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-13 14:18:27.124  6708  6939 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-13 14:18:27.124  6708  6708 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-13 14:18:27.124  6708  6823 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@33f37b96 not in the list
09-13 14:18:27.124  6708  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 14:18:27.124  6708  6823 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a578317 not in the list
09-13 14:18:27.125  6708  6823 D io.jxcore.node.ConnectivityMonitor: stop
09-13 14:18:27.125  6708  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:27.125  6708  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:27.126  6708  6708 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-13 14:18:27.127  6708  6823 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 14:18:27.127  6708  6823 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-13 14:18:27.127  6708  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-13 14:18:27.127  6708  6823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 14:18:27.127  6708  6823 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 14:18:27.133  6708  6823 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-13 14:18:27.137  6708  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 14:18:27.139  6708  6823 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,09-13 14:18:30.141  6708  6823 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 14:18:30.141  6708  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 14:18:30.141  6708  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:30.141  6708  6823 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@33f37b96 not in the list
09-13 14:18:30.141  6708  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 14:18:30.153  6708  6823 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a578317 not in the list
09-13 14:18:30.154  6708  6823 D io.jxcore.node.ConnectivityMonitor: stop
09-13 14:18:30.154  6708  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:30.154  6708  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:30.155  6708  6823 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 14:18:30.155  6708  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:30.155  6708  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:30.156  6708  6823 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@33f37b96 not in the list
09-13 14:18:30.156  6708  6823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 14:18:30.156  6708  6823 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a578317 not in the list
09-13 14:18:30.156  6708  6823 D io.jxcore.node.ConnectivityMonitor: stop
09-13 14:18:30.156  6708  6823 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:30.156  6708  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:30.157  6708  6823 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-13 14:18:30.157  6708  6823 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-13 14:18:30.158  6708  6823 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-13 14:18:30.158  6708  6823 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 14:18:30.158  6708  6823 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-13 14:18:30.158  6708  6823 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-13 14:18:30.171  6708  6940 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 957, name: My test thread name)
,09-13 14:18:32.170  6708  6823 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 957
,09-13 14:18:32.171  6708  6823 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 957, name: My test thread name)
,09-13 14:18:32.184  6708  6941 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 958, name: My test thread name)
09-13 14:18:32.184  6708  6941 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 958, thread name: My test thread name)
09-13 14:18:32.184  6708  6941 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 958, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
09-13 14:18:32.186  6708  6823 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 14:18:32.189  6708  6942 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 962, name: My test thread name)
09-13 14:18:32.190  6708  6942 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 962, thread name: My test thread name): Test exception.
09-13 14:18:32.190  6708  6942 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 962, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
09-13 14:18:32.195  6708  6823 I jxcore-log: Total number of executed tests:  76
09-13 14:18:32.195  6708  6823 I jxcore-log: 
09-13 14:18:32.196  6708  6823 I jxcore-log: Number of passed tests:  76
09-13 14:18:32.196  6708  6823 I jxcore-log: 
09-13 14:18:32.196  6708  6823 I jxcore-log: Number of failed tests:  0
09-13 14:18:32.196  6708  6823 I jxcore-log: 
09-13 14:18:32.197  6708  6823 I jxcore-log: Number of ignored tests:  0
09-13 14:18:32.197  6708  6823 I jxcore-log: 
09-13 14:18:32.197  6708  6823 I jxcore-log: Total duration:  10093
09-13 14:18:32.197  6708  6823 I jxcore-log: 
09-13 14:18:32.198  6708  6823 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-13 14:18:32.198  6708  6823 I jxcore-log: 
09-13 14:18:32.200  6708  6823 I jxcore-log: My device name is: LGE-LG-D855
09-13 14:18:32.200  6708  6823 I jxcore-log: 
,09-13 14:18:32.213  6708  6823 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 14:18:32.213  6708  6823 I jxcore-log: 
09-13 14:18:32.214  6708  6823 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 14:18:32.214  6708  6823 I jxcore-log: 
09-13 14:18:32.215  6708  6823 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 14:18:32.215  6708  6823 I jxcore-log: 
09-13 14:18:32.217  6708  6823 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 14:18:32.217  6708  6823 I jxcore-log: 
09-13 14:18:32.218  6708  6823 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 14:18:32.218  6708  6823 I jxcore-log: 
09-13 14:18:32.221  6708  6823 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 14:18:32.221  6708  6823 I jxcore-log: 
,09-13 14:18:32.227  6708  6940 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 957, name: My test thread name), during the lifetime of the thread the total number of bytes read was 143 and the total number of bytes written 143
09-13 14:18:32.234  6708  6823 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-13 14:18:32.234  6708  6823 I jxcore-log: 
09-13 14:18:32.235  6708  6823 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 14:18:32.235  6708  6823 I jxcore-log: 
,09-13 14:18:32.534  6943  6943 D AndroidRuntime: 
09-13 14:18:32.534  6943  6943 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
09-13 14:18:32.537  6943  6943 D AndroidRuntime: CheckJNI is OFF
,09-13 14:18:32.659  6943  6943 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-13 14:18:32.672  1045  1116 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
09-13 14:18:32.673  1045  1116 I ActivityManager: Killing 6708:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
,09-13 14:18:32.707  1045  1947 I WindowState: WIN DEATH: Window{1c4a5ec1 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-13 14:18:32.708  1045  1528 D WifiService: Client connection lost with reason: 4
09-13 14:18:32.714  1045  1947 D InputDispatcher: Window went away: Window{1c4a5ec1 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-13 14:18:32.798  1045  1116 I ActivityManager:   Force finishing activity ActivityRecord{39d9c392 u0 com.test.thalitest/.MainActivity t6}
,09-13 14:18:32.830   329   352 E GBMv2   : DFP En is all cleared set to be enabled
,09-13 14:18:32.841  1045  1582 W ActivityManager: Spurious death for ProcessRecord{2153750a 6708:com.test.thalitest/u0a118}, curProc for 6708: null
09-13 14:18:32.842  1045  1126 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
09-13 14:18:32.846  1045  1126 I ActivityManager:   Force finishing activity ActivityRecord{39d9c392 u0 com.test.thalitest/.MainActivity t6 f}
09-13 14:18:32.847  1045  1126 W ActivityManager: Duplicate finish request for ActivityRecord{39d9c392 u0 com.test.thalitest/.MainActivity t6 f}
,09-13 14:18:32.895  4652  4652 I art     : Explicit concurrent mark sweep GC freed 493(32KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 30MB/46MB, paused 582us total 37.045ms
,09-13 14:18:32.897  2021  2021 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
09-13 14:18:32.898  2021  2021 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
09-13 14:18:32.900  1929  2789 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
09-13 14:18:32.900  1929  2789 D SplitWindowPolicy: topRunningActivity=ActivityInfo{3c9497eb co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
09-13 14:18:32.901  2021  2021 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
09-13 14:18:32.902  1929  1944 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
09-13 14:18:32.902  1929  1944 D SplitWindowPolicy: topRunningActivity=ActivityInfo{3c507948 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
09-13 14:18:32.903  2021  2069 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
09-13 14:18:32.908  1591  1591 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,09-13 14:18:32.917  1045  1369 I InputReader: Reconfiguring input devices.  changes=0x00000010
09-13 14:18:32.941  3936  3936 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
09-13 14:18:32.941  3936  3936 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,09-13 14:18:32.946  3871  3871 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
09-13 14:18:32.946  1983  1983 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
09-13 14:18:32.960  1045  2038 V SIM_STK : Menu title from STK is T-Mobile
,09-13 14:18:32.978  4535  4535 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
09-13 14:18:32.979  4535  4535 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
09-13 14:18:32.979  4535  4535 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
09-13 14:18:32.979  4535  4535 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
09-13 14:18:32.979  4535  4535 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-13 14:18:32.979  4535  4535 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-13 14:18:32.979  4535  4535 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-13 14:18:32.979  4535  4535 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-13 14:18:32.979  4535  4535 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 14:18:32.979  4535  4535 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-13 14:18:32.979  4535  4535 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-13 14:18:32.979  4535  4535 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-13 14:18:32.980  2490  2713 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
09-13 14:18:33.013  6528  6528 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
,09-13 14:18:33.017  2021  2021 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
09-13 14:18:33.017  1893  1893 D ActionManagerService: notifyUserLog: 1000003
09-13 14:18:33.018  3871  4559 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
09-13 14:18:33.024  1805  1805 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
09-13 14:18:33.025  2021  2021 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
,09-13 14:18:33.039  2021  2021 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
,09-13 14:18:33.042  2117  2117 I ConfigService: onCreate
09-13 14:18:33.043  2117  2117 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
09-13 14:18:33.046  2021  2021 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
09-13 14:18:33.048  2117  2117 I ConfigService: onBind returning update interface
09-13 14:18:33.049  1857  1857 D SplitUIManager: split_name #11 / not available #0
09-13 14:18:33.049  1857  1857 D SplitUIService: removed split : 
09-13 14:18:33.050  1805  1805 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
09-13 14:18:33.050  1893  1893 D ActionManagerService: notifyUserLog: 1000004
09-13 14:18:33.050  3871  4559 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
09-13 14:18:33.052  1045  1045 I art     : Explicit concurrent mark sweep GC freed 12386(945KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/64MB, paused 2.755ms total 182.534ms
09-13 14:18:33.052  1045  1126 I art     : WaitForGcToComplete blocked for 15.013ms for cause Explicit
09-13 14:18:33.053  1591  1591 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
,09-13 14:18:33.055  2117  2117 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
09-13 14:18:33.055  2117  2117 I ConfigService: onBind returning config service
09-13 14:18:33.056  2021  2021 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
09-13 14:18:33.058  1805  1805 I ConfigFetchService: service connected
09-13 14:18:33.059  3871  3887 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
09-13 14:18:33.071  1591  1652 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
09-13 14:18:33.071  1591  1652 D KeyguardModel: createShortcutInfo...
,09-13 14:18:33.076  1591  1652 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
09-13 14:18:33.076  1591  1652 D KeyguardModel: createShortcutInfo...
09-13 14:18:33.077  1591  1652 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-13 14:18:33.077  1591  1652 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
09-13 14:18:33.079  1591  1652 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
09-13 14:18:33.079  1591  1652 D KeyguardModel: createShortcutInfo...
09-13 14:18:33.082  1591  1652 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-13 14:18:33.083  1591  1652 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
09-13 14:18:33.084  1591  1652 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
09-13 14:18:33.084  1591  1652 D KeyguardModel: createShortcutInfo...
09-13 14:18:33.084  1857  1857 D SplitUIManager: split_name #11 / not available #0
09-13 14:18:33.084  1857  1857 I SplitUIService: split app #11
09-13 14:18:33.085  1591  1652 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-13 14:18:33.085  1591  1652 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
09-13 14:18:33.087  1591  1652 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
09-13 14:18:33.087  1591  1652 D KeyguardModel: createShortcutInfo...
09-13 14:18:33.090  1045  1982 V SIM_STK : Menu title from STK is T-Mobile
09-13 14:18:33.090  1045  1982 V SIM_STK : Menu title from STK is T-Mobile
,09-13 14:18:33.096  2117  2117 I ConfigService: onDestroy
09-13 14:18:33.097  2021  2021 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
09-13 14:18:33.097  2021  2021 I GBoardWebViewUtils: , create_time: 1430832262123
09-13 14:18:33.097  2021  2021 I GBoardWebViewUtils: , expire_time: 0
09-13 14:18:33.097  2021  2021 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
09-13 14:18:33.097  2021  2021 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
09-13 14:18:33.097  2021  2021 I GBoardWebViewUtils: , display: false
09-13 14:18:33.097  2021  2021 I GBoardWebViewUtils: , animation: false }
09-13 14:18:33.097  2021  2021 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
09-13 14:18:33.097  2021  2021 I GBoardWebViewUtils: , create_time: 1430832262287
09-13 14:18:33.097  2021  2021 I GBoardWebViewUtils: , expire_time: 0
09-13 14:18:33.097  2021  2021 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
09-13 14:18:33.097  2021  2021 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
09-13 14:18:33.097  2021  2021 I GBoardWebViewUtils: , display: false
09-13 14:18:33.097  2021  2021 I GBoardWebViewUtils: , animation: false }
09-13 14:18:33.097  2021  2021 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1473420112499
09-13 14:18:33.097  2021  2021 I GBoardWebViewUtils: , create_time: 1473420113195
09-13 14:18:33.097  2021  2021 I GBoardWebViewUtils: , expire_time: 0
09-13 14:18:33.097  2021  2021 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide.html?id=guide_1111111111116_1473420112499&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
09-13 14:18:33.097  2021  2021 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
09-13 14:18:33.097  2021  2021 I GBoardWebViewUtils: , display: false
09-13 14:18:33.097  2021  2021 I GBoardWebViewUtils: , animation: false }
09-13 14:18:33.108  1591  1591 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
09-13 14:18:33.108  1591  1591 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
09-13 14:18:33.110  1591  1591 D KeyguardModel: handleShortcutListChanged...
09-13 14:18:33.110  1591  1591 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
09-13 14:18:33.111  2021  6977 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
09-13 14:18:33.119  2021  2021 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
09-13 14:18:33.120  2021  2021 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
09-13 14:18:33.121  1805  6979 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,09-13 14:18:33.134  1045  1045 D administrator: Handling package changes for user 0
,09-13 14:18:33.144  1045  1582 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
09-13 14:18:33.144  3936  3936 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
09-13 14:18:33.144  3936  3936 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
09-13 14:18:33.144  3936  3936 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
09-13 14:18:33.144  3936  3936 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
09-13 14:18:33.144  3936  3936 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
09-13 14:18:33.144  3936  3936 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-13 14:18:33.144  3936  3936 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
09-13 14:18:33.144  3936  3936 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
09-13 14:18:33.144  3936  3936 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
09-13 14:18:33.144  3936  3936 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-13 14:18:33.144  3936  3936 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
09-13 14:18:33.149  6021  6984 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
,09-13 14:18:33.170  1591  1652 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
,09-13 14:18:33.170  1591  1652 D KeyguardModel: createShortcutInfo...
09-13 14:18:33.175  1591  1652 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
09-13 14:18:33.175  1591  1652 D KeyguardModel: createShortcutInfo...
09-13 14:18:33.176  1591  1652 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-13 14:18:33.176  1591  1652 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
09-13 14:18:33.178  1591  1652 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
09-13 14:18:33.178  1591  1652 D KeyguardModel: createShortcutInfo...
09-13 14:18:33.179  1591  1652 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-13 14:18:33.179  1591  1652 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
09-13 14:18:33.180  1591  1652 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
09-13 14:18:33.180  1591  1652 D KeyguardModel: createShortcutInfo...
09-13 14:18:33.181  1591  1652 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-13 14:18:33.181  1591  1652 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
09-13 14:18:33.182  1591  1652 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
09-13 14:18:33.182  1591  1652 D KeyguardModel: createShortcutInfo...
,09-13 14:18:33.189  1805  6986 I PeopleContactsSync: CP2 sync disabled
09-13 14:18:33.190  1805  6985 W GmsApplication: Using Auth Proxy for data requests.
09-13 14:18:33.192  1045  1999 V SIM_STK : Menu title from STK is T-Mobile
09-13 14:18:33.193  2021  2021 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
09-13 14:18:33.194  1591  1591 D KeyguardModel: handleShortcutListChanged...
09-13 14:18:33.194  1591  1591 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
09-13 14:18:33.198  1805  4821 I Icing   : doRemovePackageData com.test.thalitest
,09-13 14:18:33.200  1805  6985 W GmsApplication: Using Auth Proxy for data requests.
,09-13 14:18:33.228  2021  2035 I art     : Background partial concurrent mark sweep GC freed 7042(321KB) AllocSpace objects, 5(19MB) LOS objects, 34% free, 60MB/92MB, paused 5.757ms total 41.579ms
,09-13 14:18:33.236  6101  6101 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
09-13 14:18:33.248   323   410 I ThermalEngine: Thermal-Server: Thermal received msg from  override
09-13 14:18:33.248  3167  6989 I Thermal-Lib: Thermal-Lib-Client: Client request sent
,09-13 14:18:33.266  1045  1045 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
09-13 14:18:33.266  1045  1045 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
09-13 14:18:33.266  6628  6628 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,09-13 14:18:33.267  1045  1045 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
09-13 14:18:33.270  1045  1565 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
09-13 14:18:33.275  2356  6990 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
09-13 14:18:33.279  1983  1983 D LIA_Service_NativeEventReceiver: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
09-13 14:18:33.279  1983  1983 I LIA_Service_PlatformUtil: startLIAService() : Trying to start LIA service ...
09-13 14:18:33.279  1983  1983 D LIA_Service_LIAService: onStartCommand() : LIAService started! - id :4, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
,09-13 14:18:33.282  6528  6528 D PostponalbeReceiver: OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
09-13 14:18:33.307  1045  1061 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.core.receiver.CoreEventReceiver: pid=6992 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,09-13 14:18:33.314  2021  2021 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
09-13 14:18:33.316  2021  2021 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-13 14:18:33.318  2021  2021 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
09-13 14:18:33.319  2021  2021 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
09-13 14:18:33.320  2021  2021 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
09-13 14:18:33.321  2021  2021 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
09-13 14:18:33.335  1045  1121 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{118658de u0 com.lge.launcher2/.Launcher t5} time:137613
,09-13 14:18:33.338  2021  2021 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
09-13 14:18:33.338  2021  2021 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-13 14:18:33.352  2021  2158 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
09-13 14:18:33.352  2021  2021 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
09-13 14:18:33.352  2021  2158 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
09-13 14:18:33.353  2021  2021 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
09-13 14:18:33.353  2021  2021 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,09-13 14:18:33.361  2021  2021 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
09-13 14:18:33.362  2588  2588 D [Concierge]Service: onStartCommand(). Type : 8
09-13 14:18:33.362  2588  2588 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
09-13 14:18:33.363  2588  2588 D [Concierge]Service: Update widget ID : 11
09-13 14:18:33.364  2021  2021 D [Concierge]WidgetView: change position of spinner
09-13 14:18:33.367  2021  2021 I [Concierge]WidgetView: initWebView(). Time : 1473769113367
09-13 14:18:33.367  2588  2588 D [Concierge]Service: onStartCommand(). Type : 0
,09-13 14:18:33.375  1045  1126 I art     : Explicit concurrent mark sweep GC freed 8947(638KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/64MB, paused 1.710ms total 318.221ms
09-13 14:18:33.383  2021  2021 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 795754766
09-13 14:18:33.383  2021  2021 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
09-13 14:18:33.383  2021  2021 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,09-13 14:18:33.386  2021  2021 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@30ea4519
09-13 14:18:33.386  2021  2021 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
09-13 14:18:33.387  2021  2021 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
09-13 14:18:33.387  2021  2021 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-13 14:18:33.392  2021  2021 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
09-13 14:18:33.393  2021  2021 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
09-13 14:18:33.393  2021  2021 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
09-13 14:18:33.394  2021  2021 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1473769003793, New one : 1473769113367
09-13 14:18:33.394  2021  2021 D [Concierge]WidgetView: Unregister all receivers
,09-13 14:18:33.394  2021  2021 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
09-13 14:18:33.395  2021  2021 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-13 14:18:33.396  2021  2021 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
09-13 14:18:33.397  2021  2021 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
09-13 14:18:33.398  2021  2021 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
09-13 14:18:33.399  2021  2021 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
09-13 14:18:33.400  2021  2021 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
,09-13 14:18:33.404  2021  2021 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-13 14:18:33.404  2021  2021 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-13 14:18:33.405  6992  6992 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
09-13 14:18:33.405  6992  6992 W LG Account v2.2: No ProfileInfo entries
09-13 14:18:33.405  6992  6992 I LG Account v2.2: isEnabled: false
09-13 14:18:33.405  6992  6992 I Feature : [Lifetracker]ver: 4.21.112(40211120)
09-13 14:18:33.405  6992  6992 I Feature : [Lifetracker]Country: EU
09-13 14:18:33.405  6992  6992 I Feature : [Lifetracker]Operator: OPEN
09-13 14:18:33.407  6992  6992 I Feature : [Lifetracker]Ranking support: false
09-13 14:18:33.407  6992  6992 I Feature : [Lifetracker]Comfort support: false
09-13 14:18:33.407  6992  6992 I Feature : [Lifetracker]Accessory: true
09-13 14:18:33.407  6992  6992 I Feature : [Lifetracker]Health device: true
09-13 14:18:33.407  6992  6992 I Feature : [Lifetracker]Extra Pedometer: false
09-13 14:18:33.407  6992  6992 I Feature : [Lifetracker]Blood glucose device: false
09-13 14:18:33.407  6992  6992 I Feature : [Lifetracker]Device Number: 3
09-13 14:18:33.408  6992  6992 D CoreEventReceiver: [onReceive] Action=android.intent.action.PACKAGE_REMOVED
09-13 14:18:33.436  1045  1060 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=7014 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-13 14:18:33.437  1045  1060 I ActivityManager: Killing 6362:com.android.providers.calendar/u0a14 (adj 15): empty #17
09-13 14:18:33.452  6943  6943 D AndroidRuntime: Shutting down VM
09-13 14:18:33.454  2021  2021 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,09-13 14:18:33.461  2021  2021 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
09-13 14:18:33.462  2021  2021 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
,09-13 14:18:33.463  2021  2021 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,09-13 14:18:33.482  2021  2021 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@27f2380b time:137760
,09-13 14:18:33.503  1045  2038 W libprocessgroup: failed to open /acct/uid_10014/pid_6362/cgroup.procs: No such file or directory
,09-13 14:18:33.533  7014  7014 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-13 14:18:33.534  7014  7014 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
09-13 14:18:33.534  7014  7014 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-13 14:18:33.534  7014  7014 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
09-13 14:18:33.535  7014  7014 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-13 14:18:33.535  7014  7014 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-13 14:18:33.540  1045  1115 W InputMethodInfo: Duplicated subtype definition found: , voice
09-13 14:18:33.599  2021  2021 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,09-13 14:18:33.610  7014  7014 D PackageIntentReceiver: Not supported Hotkey customization function 
,09-13 14:18:33.617  7014  7014 D HideNavigationAppsReceiver: Receive package name : com.test.thalitest, replacing=false, action=android.intent.action.PACKAGE_REMOVED
09-13 14:18:33.617  7014  7014 D HideNavigationAppsReceiver: replacing : false
09-13 14:18:33.619  7014  7014 D HideNavigationAppsReceiver: Delete mPackageMame : com.test.thalitest
,09-13 14:18:33.623  7014  7014 D ButtonCombinationReceiver: Receive package name : com.test.thalitest
09-13 14:18:33.623  7014  7014 D ButtonCombinationReceiver: replacing : false
,09-13 14:18:33.629  1045  1999 I ActivityManager: Killing 6593:com.google.android.partnersetup/u0a8 (adj 15): empty #17
09-13 14:18:33.645  2021  2889 I GBoardtInterface: onReloaded()
,09-13 14:18:33.646  2021  2021 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
09-13 14:18:33.670  1045  1115 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-13 14:18:33.674  1045  1115 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,09-13 14:18:33.683  1045  1947 W libprocessgroup: failed to open /acct/uid_10008/pid_6593/cgroup.procs: No such file or directory
,09-13 14:18:33.685  3871  3887 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
09-13 14:18:33.687  4652  7032 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
09-13 14:18:33.692  3871  3886 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
09-13 14:18:33.707  1045  1874 V SIM_STK : Menu title from STK is T-Mobile
,09-13 14:18:33.721  1045  1582 I ActivityManager: Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=7034 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
09-13 14:18:33.727  1893  1893 D ActionManagerService: notifyUserLog: 1000001
09-13 14:18:33.728  3871  4559 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
09-13 14:18:33.728  3871  4559 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
09-13 14:18:33.731  1893  1893 D ActionManagerService: notifyUserLog: 1000001
09-13 14:18:33.731   345   345 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 208us total 9.434ms
09-13 14:18:33.733  3871  4559 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
09-13 14:18:33.733  3871  4559 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
09-13 14:18:33.733  3871  4559 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
09-13 14:18:33.733  3871  3887 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
09-13 14:18:33.733  3871  4559 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
,09-13 14:18:33.735  2021  2021 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
09-13 14:18:33.735  2021  2021 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
09-13 14:18:33.737  2021  2021 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
09-13 14:18:33.737  2021  2021 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
09-13 14:18:33.739  2021  2021 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide2.html?id=guide_1111111111116_1473420112499&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
09-13 14:18:33.739  2021  2021 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide2.html?id=guide_1111111111116_1473420112499&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
09-13 14:18:33.741   345   345 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 186us total 9.278ms
09-13 14:18:33.742  2021  2021 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
09-13 14:18:33.750   345   345 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 190us total 8.771ms
,09-13 14:18:33.769  4652  7032 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 82 ms] updated apps [took 81 ms] 
,09-13 14:18:33.772  7034  7034 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2586 
09-13 14:18:33.778  6216  6216 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
09-13 14:18:33.778  6216  6216 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
09-13 14:18:33.778  6216  6216 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
,09-13 14:18:33.778  6216  6216 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
09-13 14:18:33.778  6216  6216 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
09-13 14:18:33.778  6216  6216 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
09-13 14:18:33.786  6803  6803 D [BNRAppListMgrReceiver]: android.intent.action.PACKAGE_REMOVED : com.test.thalitest
,09-13 14:18:33.791  7014  7014 D PackageIntentReceiver: Not supported Hotkey customization function 
09-13 14:18:33.791  7034  7052 E SQLiteDatabase: Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
09-13 14:18:33.791  7034  7052 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 14:18:33.791  7034  7052 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-13 14:18:33.791  7034  7052 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
09-13 14:18:33.791  7034  7052 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
09-13 14:18:33.791  7034  7052 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-13 14:18:33.791  7034  7052 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-13 14:18:33.791  7034  7052 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-13 14:18:33.791  7034  7052 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
09-13 14:18:33.791  7034  7052 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
09-13 14:18:33.791  7034  7052 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
09-13 14:18:33.791  7034  7052 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
09-13 14:18:33.791  7034  7052 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
09-13 14:18:33.791  7034  7052 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-13 14:18:33.791  7034  7052 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-13 14:18:33.791  7034  7052 E SQLiteDatabase: 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
09-13 14:18:33.791  7034  7052 E SQLiteDatabase: 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
09-13 14:18:33.791  7034  7052 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
09-13 14:18:33.791  7034  7052 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 14:18:33.791  7034  7052 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
09-13 14:18:33.791  7034  7052 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
--------- beginning of crash
09-13 14:18:33.791  7034  7052 E AndroidRuntime: FATAL EXCEPTION: IntentService[KeyChainService]
09-13 14:18:33.791  7034  7052 E AndroidRuntime: Process: com.android.keychain, PID: 7034
09-13 14:18:33.791  7034  7052 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 14:18:33.791  7034  7052 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-13 14:18:33.791  7034  7052 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
09-13 14:18:33.791  7034  7052 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
09-13 14:18:33.791  7034  7052 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-13 14:18:33.791  7034  7052 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-13 14:18:33.791  7034  7052 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-13 14:18:33.791  7034  7052 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDa,tabase.java:907)
09-13 14:18:33.791  7034  7052 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
09-13 14:18:33.791  7034  7052 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
09-13 14:18:33.791  7034  7052 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
09-13 14:18:33.791  7034  7052 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
09-13 14:18:33.791  7034  7052 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-13 14:18:33.791  7034  7052 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-13 14:18:33.791  7034  7052 E AndroidRuntime: 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
09-13 14:18:33.791  7034  7052 E AndroidRuntime: 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
09-13 14:18:33.791  7034  7052 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
09-13 14:18:33.791  7034  7052 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 14:18:33.791  7034  7052 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
09-13 14:18:33.791  7034  7052 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-13 14:18:33.824  1045  1060 I ActivityManager: Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=7056 uid=10060 gids={50060, 9997, 1028, 4002} abi=armeabi-v7a

```
