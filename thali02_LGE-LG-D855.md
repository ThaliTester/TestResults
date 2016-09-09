#### Test 83627337ab51778_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
09-09 13:35:29.629  6471  6471 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_ADDED (at PackageChangeReceiver.java onReceive 20)
--------- beginning of system
09-09 13:35:29.641  1036  1051 I ActivityManager: Killing 5745:com.google.android.gm/u0a64 (adj 15): empty #17
09-09 13:35:29.721  2000  2000 D LIA_Service_NativeEventReceiver: onReceive action : android.intent.action.PACKAGE_ADDED = package:com.test.thalitest
09-09 13:35:29.721  2000  2000 I LIA_Service_PlatformUtil: startLIAService() : Trying to start LIA service ...
09-09 13:35:29.727  1036  1052 W libprocessgroup: failed to open /acct/uid_10064/pid_5745/cgroup.procs: No such file or directory
09-09 13:35:29.736  2000  2000 D LIA_Service_LIAService: onStartCommand() : LIAService started! - id :3, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
09-09 13:35:29.773  6373  6373 D PostponalbeReceiver: OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_ADDED'.
09-09 13:35:29.781  6373  6373 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsm.mss.OasPackageScanReceiver.onReceive:-1 android.app.ActivityThread.handleReceiver:2586 
09-09 13:35:29.826  4602  6510 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
09-09 13:35:29.893  1036  1963 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=6511 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-09 13:35:29.898  1036  1981 V SIM_STK : Menu title from STK is T-Mobile
09-09 13:35:30.003  4602  6510 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 178 ms] updated apps [took 178 ms] 
09-09 13:35:30.144  6511  6511 D DocsApplication: Installing DEX configuration.
09-09 13:35:30.162  6511  6511 D DexInstaller: Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
09-09 13:35:30.167  6511  6511 I PackageInfoHelper: Provided clientMode=RELEASE, packageInfo=PackageInfo{3316e735 com.google.android.apps.docs}
09-09 13:35:30.186  6511  6511 D TAG     : onCreate()
09-09 13:35:30.216  6511  6511 D CrossAppStateProvider: Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
09-09 13:35:30.506   333   432 I ThermalEngine: Thermal-Server: Thermal received msg from  override
,09-09 13:35:30.510  3248  6535 I Thermal-Lib: Thermal-Lib-Client: Client request sent
09-09 13:35:30.854  6536  6536 D AndroidRuntime: 
09-09 13:35:30.854  6536  6536 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
09-09 13:35:30.860  6536  6536 D AndroidRuntime: CheckJNI is OFF
09-09 13:35:31.007  1821  4740 I Icing   : Indexing 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4 from com.google.android.googlequicksearchbox
09-09 13:35:31.038  6536  6536 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-09 13:35:31.044  1036  1781 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-09 13:35:31.058  1945  2703 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
09-09 13:35:31.061  1821  4740 D Icing   : Loaded CLD2 Version V2.0 - 20140131
09-09 13:35:31.062  1036  1781 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
09-09 13:35:31.063  1036  1781 D ActivityManager: setTaskToReturnTo : TaskRecord{2cfef043 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
09-09 13:35:31.063  1036  1781 D ActivityManager: setTaskToReturnTo : TaskRecord{2cfef043 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
09-09 13:35:31.064  1036  1781 D WindowStateEx: AppWindowTokenEx init.. 
09-09 13:35:31.065   339   363 E GBMv2   : DFP En is all cleared set to be enabled
09-09 13:35:31.101  1036  1781 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6562 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
09-09 13:35:31.104  6536  6536 D AndroidRuntime: Shutting down VM
09-09 13:35:31.165  1945  2703 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
09-09 13:35:31.165  1945  2703 D SplitWindowPolicy: topRunningActivity=ActivityInfo{276e31c1 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
09-09 13:35:31.166  1945  1961 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
09-09 13:35:31.166  1945  1961 D SplitWindowPolicy: topRunningActivity=ActivityInfo{195a2d66 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
09-09 13:35:31.205  1821  4740 I Icing   : Indexing done 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4
09-09 13:35:31.217  6562  6562 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
09-09 13:35:31.292  6562  6562 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
09-09 13:35:31.300  6562  6562 I LibraryLoader: Loading: webviewchromium
09-09 13:35:31.303  6562  6562 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 4012-4016)
09-09 13:35:31.303  6562  6562 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-09 13:35:31.326  6562  6562 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1c850217}
,09-09 13:35:31.328  6562  6562 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-09 13:35:31.329  6562  6562 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
09-09 13:35:31.338  6562  6562 I BrowserStartupController: Initializing chromium process, renderers=0
09-09 13:35:31.338  6562  6562 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-09 13:35:31.349   315  1403 V AudioPolicyService: registerClient() client 0xb558ac20, uid 10118
09-09 13:35:31.350  6562  6562 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
09-09 13:35:31.350  6562  6562 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=23 off=46780 len=2953
09-09 13:35:31.351  6562  6562 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
09-09 13:35:31.353  1036  1112 D BluetoothManagerService: Message: 20
09-09 13:35:31.354  1036  1112 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1c5192b5:true
,09-09 13:35:31.383  6562  6562 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-09 13:35:31.383  6562  6562 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-09 13:35:31.383  6562  6562 I Adreno-EGL: Build Date: 12/12/14 금
09-09 13:35:31.383  6562  6562 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-09 13:35:31.383  6562  6562 I Adreno-EGL: Remote Branch: 
09-09 13:35:31.383  6562  6562 I Adreno-EGL: Local Patches: 
09-09 13:35:31.383  6562  6562 I Adreno-EGL: Reconstruct Branch: 
,09-09 13:35:31.480  6562  6592 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,09-09 13:35:31.484  6562  6562 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
09-09 13:35:31.508  6562  6562 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-09 13:35:31.514  6562  6562 W AwContents: onDetachedFromWindow called when already detached. Ignoring
09-09 13:35:31.517  6562  6562 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
09-09 13:35:31.520  6562  6562 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
,09-09 13:35:31.520  6562  6562 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
09-09 13:35:31.537  6562  6562 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
09-09 13:35:31.546  6562  6562 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-09 13:35:31.546  6562  6562 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-09 13:35:31.586  6562  6604 D OpenGLRenderer: Render dirty regions requested: true
09-09 13:35:31.586  6562  6604 I OpenGLRenderer: Initialized EGL, version 1.4
09-09 13:35:31.590  6562  6604 D OpenGLRenderer: Enabling debug mode 0
09-09 13:35:31.598  6562  6562 D Atlas   : Validating map...
,09-09 13:35:31.602  1036  1999 D SplitWindow: check instance of lgWin Window{c60ce87 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-09 13:35:31.671  6562  6602 D LgDataFeature: LgDataFeature() Constructor: none
09-09 13:35:31.672  6562  6602 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-09 13:35:31.702  1036  1113 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +542ms (total +636ms)
,09-09 13:35:31.702  1036  1113 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2c92e6c0 u0 com.test.thalitest/.MainActivity t6} time:104416
09-09 13:35:31.702  6562  6562 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2b0cbbd2 time:104416
09-09 13:35:31.852  6562  6562 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-09 13:35:31.933  6562  6614 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435173888
,09-09 13:35:31.943  6562  6614 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-09 13:35:31.943  6562  6614 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-09 13:35:31.943  6562  6614 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-09 13:35:31.943  6562  6614 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-09 13:35:31.943  6562  6614 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
09-09 13:35:31.944  6562  6614 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@52a17f6 added. We now have 1 listener(s)
09-09 13:35:31.947  1036  1051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 13:35:31.951  6562  6614 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
,09-09 13:35:31.957  6562  6614 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-09 13:35:31.960  6562  6614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-09 13:35:31.961  6562  6614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 13:35:31.977  6562  6614 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-09 13:35:31.977  6562  6614 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-09 13:35:31.977  6562  6614 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-09 13:35:31.977  6562  6614 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
09-09 13:35:31.977  6562  6614 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-09 13:35:31.977  6562  6614 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-09 13:35:31.977  6562  6614 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-09 13:35:31.977  6562  6614 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-09 13:35:31.977  6562  6614 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-09 13:35:31.977  6562  6614 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-09 13:35:31.977  6562  6614 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-09 13:35:31.977  6562  6614 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-09 13:35:31.977  6562  6614 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-09 13:35:31.977  6562  6614 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-09 13:35:31.978  6562  6614 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a7dc0cd added. We now have 1 listener(s)
09-09 13:35:31.978  6562  6614 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 13:35:31.982  1036  1412 D WifiService: New client listening to asynchronous messages
09-09 13:35:31.986  6562  6614 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-09 13:35:31.986  6562  6614 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-09 13:35:31.988  6562  6614 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-09 13:35:31.988  6562  6614 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-09 13:35:31.988  6562  6614 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
09-09 13:35:31.991  6562  6614 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:35:31.993  1036  1963 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 13:35:31.996  6562  6614 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
09-09 13:35:32.008  6562  6614 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
,09-09 13:35:32.010  6562  6614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:35:32.010  6562  6614 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:35:32.010  6562  6614 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:35:32.010  6562  6614 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:35:32.010  6562  6614 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:35:32.010  6562  6614 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:35:32.010  6562  6614 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:35:32.010  6562  6614 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:35:32.010  6562  6614 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-09 13:35:32.010  6562  6614 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 13:35:32.012  6562  6562 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:35:32.013  6562  6614 I io.jxcore.node.LifeCycleMonitor: start: OK
09-09 13:35:32.014  6562  6562 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:35:32.064  6562  6602 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
09-09 13:35:32.064  6562  6602 I chromium: 
,09-09 13:35:32.114  6562  6562 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-09 13:35:32.162  6511  6511 D LgDataFeature: LgDataFeature() Constructor: none
,09-09 13:35:32.162  6511  6511 D LgDataFeature: LgDataFeature() Constructor Done, null
09-09 13:35:32.167   339   365 E GBMv2   : DFP En is all cleared set to be enabled
09-09 13:35:32.167   339   365 E GBMv2   : Set value is all cleared set the max
09-09 13:35:32.167   339   365 I GBMv2   : DFP Enabled. Ignore VFP set
09-09 13:35:32.202  6562  6562 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
09-09 13:35:32.202  6562  6562 I chromium: 
,09-09 13:35:32.339  6061  6061 I LockScreenSettings: New app installed broadcast received ..
,09-09 13:35:32.345  6061  6061 I LockScreenSettings: Number of installed packages  1
09-09 13:35:32.353  6511  6511 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,09-09 13:35:32.411  1036  1616 V SIM_STK : Menu title from STK is T-Mobile
,09-09 13:35:32.467  1036  1051 I ActivityManager: Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=6633 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-09 13:35:32.554  6633  6633 D EulaProviderUpdateObserver: action : android.intent.action.PACKAGE_ADDED
09-09 13:35:32.555  6633  6633 D EulaProviderUpdateObserver: uri : package:com.test.thalitest
,09-09 13:35:32.608  1036  1962 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.BNRAppInstallReceiver: pid=6652 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
09-09 13:35:32.609  1036  1962 I ActivityManager: Killing 5432:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
,09-09 13:35:32.687  1036  1578 W libprocessgroup: failed to open /acct/uid_10005/pid_5432/cgroup.procs: No such file or directory
,09-09 13:35:32.756  6652  6652 D [BNRAppListMgrReceiver]: android.intent.action.PACKAGE_ADDED : com.test.thalitest
,09-09 13:35:32.787  6652  6652 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,09-09 13:35:32.787  6373  6373 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.intent.action.PACKAGE_ADDED'.
09-09 13:35:32.834  1036  1944 I ActivityManager: Killing 5604:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,09-09 13:35:32.848  5582  5582 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
,09-09 13:35:32.849  5582  5582 W System.err: android.os.DeadObjectException
09-09 13:35:32.849  5582  5582 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
09-09 13:35:32.849  5582  5582 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
09-09 13:35:32.849  5582  5582 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
09-09 13:35:32.849  5582  5582 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
09-09 13:35:32.849  5582  5582 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
09-09 13:35:32.849  5582  5582 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
09-09 13:35:32.849  5582  5582 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-09 13:35:32.850  5582  5582 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-09 13:35:32.850  5582  5582 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-09 13:35:32.850  5582  5582 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-09 13:35:32.850  5582  5582 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 13:35:32.850  5582  5582 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 13:35:32.850  5582  5582 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-09 13:35:32.850  5582  5582 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-09 13:35:32.850  5582  5582 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
09-09 13:35:32.851  5582  5582 W System.err: android.os.DeadObjectException
09-09 13:35:32.851  5582  5582 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
09-09 13:35:32.851  5582  5582 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
09-09 13:35:32.851  5582  5582 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
09-09 13:35:32.851  5582  5582 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
09-09 13:35:32.851  5582  5582 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
09-09 13:35:32.851  5582  5582 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
09-09 13:35:32.851  5582  5582 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-09 13:35:32.851  5582  5582 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-09 13:35:32.851  5582  5582 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-09 13:35:32.851  5582  5582 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-09 13:35:32.851  5582  5582 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 13:35:32.851  5582  5582 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 13:35:32.851  5582  5582 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-09 13:35:32.851  5582  5582 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-09 13:35:32.851  5582  5582 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
09-09 13:35:32.852  5582  5582 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
09-09 13:35:32.962   278   278 E lowmemorykiller: Error opening /proc/5604/oom_score_adj; errno=2
,09-09 13:35:32.967  1036  1963 W ActivityManager: Exception when unbinding service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service
09-09 13:35:32.967  1036  1963 W ActivityManager: android.os.DeadObjectException
09-09 13:35:32.967  1036  1963 W ActivityManager: 	at android.os.BinderProxy.transactNative(Native Method)
09-09 13:35:32.967  1036  1963 W ActivityManager: 	at android.os.BinderProxy.transact(Binder.java:496)
09-09 13:35:32.967  1036  1963 W ActivityManager: 	at android.app.ApplicationThreadProxy.scheduleUnbindService(ApplicationThreadNative.java:917)
09-09 13:35:32.967  1036  1963 W ActivityManager: 	at com.android.server.am.ActiveServices.removeConnectionLocked(ActiveServices.java:1776)
09-09 13:35:32.967  1036  1963 W ActivityManager: 	at com.android.server.am.ActiveServices.unbindServiceLocked(ActiveServices.java:901)
09-09 13:35:32.967  1036  1963 W ActivityManager: 	at com.android.server.am.ActivityManagerService.unbindService(ActivityManagerService.java:15417)
09-09 13:35:32.967  1036  1963 W ActivityManager: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:963)
09-09 13:35:32.967  1036  1963 W ActivityManager: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2560)
09-09 13:35:32.967  1036  1963 W ActivityManager: 	at com.android.server.am.ActivityManagerServiceEx.onTransact(ActivityManagerServiceEx.java:421)
09-09 13:35:32.967  1036  1963 W ActivityManager: 	at android.os.Binder.execTransact(Binder.java:446)
09-09 13:35:32.971  1036  1981 W libprocessgroup: failed to open /acct/uid_1000/pid_5604/cgroup.procs: No such file or directory
09-09 13:35:32.972  5582  5582 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
09-09 13:35:32.973  5582  5582 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
09-09 13:35:33.049  1036  1943 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=6670 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
09-09 13:35:33.050  5582  5582 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,09-09 13:35:33.082  6562  6617 W jxcore-log: Initializing JXcore engine
09-09 13:35:33.082  6562  6617 W jxcore-log: JXcore engine is ready
,09-09 13:35:33.125  6670  6670 D UEI.SmartControl: Quickset Services start...
,09-09 13:35:33.128  6670  6670 I UEI.SmartControl: Manufacture = LGE
09-09 13:35:33.128  6670  6670 D UEI.SmartControl: Id = LGNevo
09-09 13:35:33.130  6670  6670 D UEI.SmartControl: File observer start...
09-09 13:35:33.131  6670  6670 E UEI.SmartControl: IR Port is disabled: false
09-09 13:35:33.131  6670  6670 D UEI.SmartControl: Starting file observer...
09-09 13:35:33.131  6670  6670 D UEI.SmartControl: Extracting JNI libs...
09-09 13:35:33.131  6670  6670 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
09-09 13:35:33.141  6617  6617 W Thread-761: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[8450]" dev="sockfs" ino=8450 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,09-09 13:35:33.141  6617  6617 W Thread-761: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
09-09 13:35:33.141  6617  6617 W Thread-761: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[10006]" dev="sockfs" ino=10006 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
09-09 13:35:33.141  6617  6617 W Thread-761: type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
09-09 13:35:33.141  6617  6617 W Thread-761: type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[30241]" dev="sockfs" ino=30241 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
09-09 13:35:33.165  6562  6617 W jxcore-log: Starting JXcore engine
,09-09 13:35:33.224  6670  6670 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
09-09 13:35:33.224  6670  6670 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
09-09 13:35:33.224  6670  6670 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,09-09 13:35:33.251  6562  6617 W jxcore-log: Platform android
09-09 13:35:33.251  6562  6617 W jxcore-log: 
09-09 13:35:33.251  6562  6617 W jxcore-log: Process ARCH arm
09-09 13:35:33.251  6562  6617 W jxcore-log: 
,09-09 13:35:33.260  6670  6670 I UEI.SmartControl: --- Selecting new region: 6
09-09 13:35:33.262  6670  6670 I UEI.SmartControl: Model = LG-D855
,09-09 13:35:33.264  6670  6670 D UEI.SmartControl: QS Service created
09-09 13:35:33.283  6670  6670 I UEI.SmartControl: Service initServices...
,09-09 13:35:33.291  6670  6670 D UEI.SmartControl: QS start get config
09-09 13:35:33.343  6670  6670 D UEI.SmartControl: Loading JNI Libs...
,09-09 13:35:33.441  6562  6617 I jxcore-log: JXcore Cordova bridge is ready!
09-09 13:35:33.441  6562  6617 I jxcore-log: 
,09-09 13:35:33.441  6562  6617 W jxcore-log: JXcore engine is started
,09-09 13:35:33.452  6562  6614 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-09 13:35:33.456  6562  6562 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-09 13:35:33.562  2805  2805 I MusicWidget: mDelayedStopHandler : unbind
,09-09 13:35:33.569  2136  2136 I MusicBrowser: [MediaPlaybackService.java:2869:onUnbind()] oooooo 
09-09 13:35:33.570  2136  2136 I MusicBrowser: [MediaPlaybackService.java:2076:saveQueue()] oooooo {full=true}
09-09 13:35:33.570  2136  2136 I MusicBrowser: [MediaPlaybackService.java:2081:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
09-09 13:35:33.571  2136  2136 D MusicBrowser: [MediaPlaybackService.java:2161:saveQueue()] oooooo {queue=}
09-09 13:35:33.572  2136  2136 D MusicBrowser: [MediaPlaybackService.java:2163:saveQueue()] oooooo {mCardId=-1}
09-09 13:35:33.572  2136  2136 D MusicBrowser: [MediaPlaybackService.java:2198:saveQueue()] oooooo {curpos=-1}
09-09 13:35:33.574  2136  2136 I MusicBrowser: [MediaPlaybackService.java:2046:onDestroy()] oooooo 
09-09 13:35:33.574  2136  2136 I MusicBrowser: [MediaPlaybackService.java:8635:clearReceiver()] oooooo 
09-09 13:35:33.575  1036  1052 I MediaFocusControl:  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@27e60834com.lge.music.MediaPlaybackService$5@1fa9865d
09-09 13:35:33.576  2136  2136 D MusicBrowser: [MediaPlaybackService.java:8669:clearReceiver()] oooooo abandonAudioFocus : 1
09-09 13:35:33.576  2136  2136 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
,09-09 13:35:33.579  2136  2136 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-09 13:35:33.580  2136  2136 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-09 13:35:33.580  2136  2136 I MusicBrowser: [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$27@25cda8b3
09-09 13:35:33.581  2136  2136 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-09 13:35:33.581  2136  2136 I MusicBrowser: [MusicUtils.java:6801:endNotiTimer()] oooooo endNotiTimer
09-09 13:35:33.582  2136  2136 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-09 13:35:33.582  2136  2136 I MusicBrowser: [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
09-09 13:35:33.582  2136  2136 I MusicBrowser: [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
09-09 13:35:33.583  2136  2136 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-09 13:35:33.583  2136  2136 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-09 13:35:33.584  2136  2136 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-09 13:35:33.585  2136  2136 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-09 13:35:33.585  2136  2136 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
09-09 13:35:33.587  2136  2136 I MusicBrowser: [MusicUtils.java:10406:isAKACoverSupported()] oooooo aka not support!
09-09 13:35:33.588  2136  2136 I MusicBrowser: [MediaPlaybackService.java:6704:release()] oooooo 
09-09 13:35:33.588  2136  2136 I MusicBrowser: [MediaPlaybackService.java:6665:stop()] oooooo 
09-09 13:35:33.589  2136  2136 V MediaPlayer[Native]: reset
09-09 13:35:33.595  2136  2136 V MediaPlayer[Native]: setListener
09-09 13:35:33.595  2136  2136 V MediaPlayer[Native]: disconnect
09-09 13:35:33.595  2136  2136 V MediaPlayer[Native]: destructor
09-09 13:35:33.596   315  1402 V AudioFlinger: releasing 16 from 2136 for -1
09-09 13:35:33.596   315  1402 V AudioFlinger:  decremented refcount to 0
09-09 13:35:33.596   315  1402 V AudioFlinger: purging stale effects
09-09 13:35:33.597  2136  2136 V MediaPlayer[Native]: disconnect
,09-09 13:35:33.607  2136  2136 D MusicBrowser: [MusicUtils.java:615:getSmartShareVersion()] oooooo versionCode:305000
09-09 13:35:33.608  2136  2136 I SmartShareClient: [SmartShareManagerClient] smartshare client supported version code: 305000
09-09 13:35:33.609  2136  2136 I SmartShareClient: [SmartShareManagerClient] smartshare client enabled
09-09 13:35:33.610  2136  2136 I MusicBrowser: [MusicUtils.java:787:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000018
09-09 13:35:33.610  2136  2136 I MusicBrowser: [MusicUtils.java:635:getSmartShareVersion()] oooooo SmartshareVersion:953
09-09 13:35:33.610  2136  2136 V MusicBrowser: [MediaPlaybackService.java:9312:terminateSmartShareClient()] oooooo 
09-09 13:35:33.610  2136  2136 I SmartShareClient: [SmartShareManagerClient] unregisterListener: 722254802
09-09 13:35:33.611  2136  2136 W SmartShareClient: [SmartShareManagerClient] unregisterListener invalid listener: 722254802
,09-09 13:35:33.620  2136  2136 I SmartShareClient: [SmartShareManagerClient] terminate service: 2136/MediaPlaybackService/148619697
09-09 13:35:33.624  2136  2136 E HomeCloudIF: unregiterHomeCloudBroadcast(), Illegal argument.
09-09 13:35:33.624  2136  2136 I SmartShareClient: [SmartShareManagerClient] unbindService context:android.app.Application@c1224a3
09-09 13:35:33.626  2136  2136 V CloudHub: [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.2.1, versionCode=202001, state=0
09-09 13:35:33.627  2136  2136 V CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
09-09 13:35:33.628  2136  2136 I CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
09-09 13:35:33.628  2136  2136 D MusicBrowser: [MediaPlaybackService.java:9007:setStopForeground()] oooooo bValue : true
,09-09 13:35:33.631  1036  1943 I ActivityManager: Killing 5582:com.lge.qremote/u0a112 (adj 15): empty #17
09-09 13:35:33.639  2136  2136 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29989
,09-09 13:35:33.743  6670  6670 I UEI.SmartControl: Supports setup maps: true
,09-09 13:35:33.749  6670  6670 D UEI.SmartControl: QS start statue = true Error code = 0
09-09 13:35:33.749  6670  6670 I UEI.SmartControl: QS version = v2.7.10.1_RC1
09-09 13:35:33.749  6670  6670 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
09-09 13:35:33.749  6670  6670 I UEI.SmartControl: ### init IR Blaster...
09-09 13:35:33.752  1036  1962 W libprocessgroup: failed to open /acct/uid_10112/pid_5582/cgroup.procs: No such file or directory
09-09 13:35:33.757  6670  6670 D serial_port: Configuring serial port
09-09 13:35:33.761  6670  6670 E UEI.SmartControl: UEIBLaster setting for 616
09-09 13:35:33.761  6670  6670 I UEI.SmartControl: Setting serial record hearder size = 2
09-09 13:35:33.762  6670  6670 I UEI.SmartControl: configuring settings for MAXQ616
09-09 13:35:33.762  6670  6670 I UEI.SmartControl: Get version...
,09-09 13:35:33.777  6670  6691 D UEI.SmartControl: serial port data available: 21
,09-09 13:35:33.804  6670  6670 D UEI.SmartControl: MAXQ616 A2-X4 software.
09-09 13:35:33.804  6670  6670 I UEI.SmartControl: IR Blaster version: 256702256704300002
09-09 13:35:33.804  6670  6670 I UEI.SmartControl: QS saving settings...
09-09 13:35:33.805  6670  6670 D UEI.SmartControl: IR Blaster version: 25672567
,09-09 13:35:33.818  6670  6691 D UEI.SmartControl: serial port data available: 4
,09-09 13:35:33.856  6670  6694 I UEI.SmartControl: Device manager: loading config....
,09-09 13:35:33.858  6670  6694 D UEI.SmartControl: ----------- loading internal config...
09-09 13:35:33.863  6670  6670 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
09-09 13:35:33.870  6670  6670 E UEI.SmartControl: Services init done
,09-09 13:35:33.873  6670  6670 D UEI.SmartControl: QS Service init finished
09-09 13:35:33.874  6670  6670 D UEI.SmartControl: QS Service version name: 2.1.91
09-09 13:35:33.874  6670  6670 D UEI.SmartControl: QS Service version code: 201091
09-09 13:35:33.875  6670  6694 E UEI.SmartControl: Loading SETTINGS...
09-09 13:35:33.878  6670  6670 D UEI.SmartControl: Service requested: Control
09-09 13:35:33.879  6670  6670 D UEI.SmartControl: Service.onUnbind: IControl
09-09 13:35:33.881  6670  6670 D UEI.SmartControl: Service.onDestroy
09-09 13:35:33.881  6670  6670 D UEI.SmartControl: Lock is in USE false
09-09 13:35:33.881  6670  6670 D UEI.SmartControl: unbind internal service
09-09 13:35:33.885  6670  6670 D serial_port: close(fd = 25)
,09-09 13:35:33.888  6670  6670 I UEI.SmartControl: Serial port is closed.
09-09 13:35:33.888  6670  6670 I UEI.SmartControl: Serial port is closed.
09-09 13:35:33.888  6670  6670 D UEI.SmartControl: Blaster closed
09-09 13:35:33.888  6670  6670 D UEI.SmartControl: Shut down QS...
09-09 13:35:33.888  6670  6670 D UEI.SmartControl: Stopping QS lib
09-09 13:35:33.889  6670  6670 D UEI.SmartControl: QS lib stop result = true
09-09 13:35:33.889  6670  6670 D UEI.SmartControl: Stopped QS lib
09-09 13:35:33.889  6670  6670 D UEI.SmartControl: Stopped file observer...
09-09 13:35:33.889  6670  6670 D UEI.SmartControl: QS shutdown complete
09-09 13:35:33.886  6670  6694 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
09-09 13:35:33.890  6670  6670 D UEI.SmartControl: QS Service created
09-09 13:35:33.893  6670  6693 I UEI.SmartControl: Notify AllClients services are ready: 11
09-09 13:35:33.893  6670  6693 D UEI.SmartControl: -----service ready thread exits
09-09 13:35:33.905  6670  6670 I UEI.SmartControl: Service initServices...
09-09 13:35:33.905  6670  6670 D UEI.SmartControl: QS start get config
,09-09 13:35:34.227  6670  6670 I UEI.SmartControl: Supports setup maps: true
09-09 13:35:34.230  6670  6670 D UEI.SmartControl: QS start statue = true Error code = 0
09-09 13:35:34.230  6670  6670 I UEI.SmartControl: QS version = v2.7.10.1_RC1
,09-09 13:35:34.230  6670  6670 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
09-09 13:35:34.230  6670  6670 I UEI.SmartControl: ### init IR Blaster...
09-09 13:35:34.233  6670  6670 D serial_port: Configuring serial port
09-09 13:35:34.234  6670  6670 E UEI.SmartControl: UEIBLaster setting for 616
09-09 13:35:34.234  6670  6670 I UEI.SmartControl: Setting serial record hearder size = 2
09-09 13:35:34.234  6670  6670 I UEI.SmartControl: configuring settings for MAXQ616
09-09 13:35:34.234  6670  6670 I UEI.SmartControl: Get version...
09-09 13:35:34.252  6670  6697 D UEI.SmartControl: serial port data available: 21
,09-09 13:35:34.282  6670  6670 D UEI.SmartControl: MAXQ616 A2-X4 software.
09-09 13:35:34.282  6670  6670 I UEI.SmartControl: IR Blaster version: 256702256704300002
09-09 13:35:34.282  6670  6670 I UEI.SmartControl: QS saving settings...
09-09 13:35:34.284  6670  6670 D UEI.SmartControl: IR Blaster version: 25672567
,09-09 13:35:34.297  6670  6697 D UEI.SmartControl: serial port data available: 4
,09-09 13:35:34.326  6670  6700 I UEI.SmartControl: Device manager: loading config....
09-09 13:35:34.327  6670  6700 D UEI.SmartControl: ----------- loading internal config...
09-09 13:35:34.328  6670  6670 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,09-09 13:35:34.330  6670  6670 E UEI.SmartControl: Services init done
09-09 13:35:34.330  6670  6670 D UEI.SmartControl: QS Service init finished
09-09 13:35:34.331  6670  6670 D UEI.SmartControl: QS Service version name: 2.1.91
09-09 13:35:34.331  6670  6670 D UEI.SmartControl: QS Service version code: 201091
09-09 13:35:34.332  6670  6670 D UEI.SmartControl: Service requested: Control
09-09 13:35:34.339  6670  6700 E UEI.SmartControl: Loading SETTINGS...
,09-09 13:35:34.342  6670  6670 D UEI.SmartControl: Request IControl service: devices are loaded...
09-09 13:35:34.344  1036  1051 I ActivityManager: Killing 5791:com.google.android.talk/u0a72 (adj 15): empty #17
09-09 13:35:34.352  6670  6700 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
09-09 13:35:34.375  6670  6699 I UEI.SmartControl: Notify AllClients services are ready: 0
09-09 13:35:34.375  6670  6699 D UEI.SmartControl: -----service ready thread exits
,09-09 13:35:34.449  1036  1981 W libprocessgroup: failed to open /acct/uid_10072/pid_5791/cgroup.procs: No such file or directory
,09-09 13:35:34.455  6670  6670 E ActivityThread: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.g@25cda8b3 that was originally bound here
09-09 13:35:34.455  6670  6670 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.g@25cda8b3 that was originally bound here
09-09 13:35:34.455  6670  6670 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1167)
09-09 13:35:34.455  6670  6670 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1061)
09-09 13:35:34.455  6670  6670 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1839)
09-09 13:35:34.455  6670  6670 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:1822)
09-09 13:35:34.455  6670  6670 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
09-09 13:35:34.455  6670  6670 E ActivityThread: 	at com.uei.control.Service.b(Unknown Source)
09-09 13:35:34.455  6670  6670 E ActivityThread: 	at com.uei.control.Service.a(Unknown Source)
09-09 13:35:34.455  6670  6670 E ActivityThread: 	at com.uei.control.Service.onCreate(Unknown Source)
09-09 13:35:34.455  6670  6670 E ActivityThread: 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2738)
09-09 13:35:34.455  6670  6670 E ActivityThread: 	at android.app.ActivityThread.access$1800(ActivityThread.java:148)
09-09 13:35:34.455  6670  6670 E ActivityThread: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
09-09 13:35:34.455  6670  6670 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 13:35:34.455  6670  6670 E ActivityThread: 	at android.os.Looper.loop(Looper.java:135)
09-09 13:35:34.455  6670  6670 E ActivityThread: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-09 13:35:34.455  6670  6670 E ActivityThread: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 13:35:34.455  6670  6670 E ActivityThread: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 13:35:34.455  6670  6670 E ActivityThread: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-09 13:35:34.455  6670  6670 E ActivityThread: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,09-09 13:35:34.456  6670  6670 D UEI.SmartControl: Internal service binding...,
09-09 13:35:34.882  6670  6696 D UEI.SmartControl: Internal timer expired: 2
,09-09 13:35:36.268  6511  6511 W GAV2    : Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,09-09 13:35:36.270  1036  1780 I ActivityManager: Killing 6191:com.android.calendar/u0a13 (adj 15): empty #17
09-09 13:35:36.441  1036  1052 W libprocessgroup: failed to open /acct/uid_10013/pid_6191/cgroup.procs: No such file or directory
,09-09 13:35:37.264  6511  6618 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,09-09 13:35:38.132  6670  6681 E UEI.SmartControl: file observer is disposed!
,09-09 13:35:39.028  1821  6427 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,09-09 13:35:39.034   311  6715 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,09-09 13:35:39.034   311  6715 D libc-netbsd: res_queryN name = cloudconfig.googleapis.com, class = 1, type = 1
09-09 13:35:39.034   311  6715 D libc-netbsd: res_queryN name = cloudconfig.googleapis.com succeed
09-09 13:35:39.273  1821  1821 I ConfigFetchService: fetch service done; releasing wakelock
09-09 13:35:39.279  1821  1821 I ConfigFetchService: stopping self
,09-09 13:35:39.294  2180  2180 I ConfigService: onDestroy
09-09 13:35:39.326  6670  6701 D UEI.SmartControl: Internal timer expired: 3
09-09 13:35:39.326  6670  6701 D UEI.SmartControl: unbind internal service
,09-09 13:35:39.331  6670  6670 D UEI.SmartControl: Service.onUnbind: IControl
09-09 13:35:39.331  6670  6670 D UEI.SmartControl: Service.onDestroy
09-09 13:35:39.331  6670  6670 D UEI.SmartControl: Lock is in USE false
09-09 13:35:39.331  6670  6670 D UEI.SmartControl: unbind internal service
09-09 13:35:39.331  6670  6670 W System.err: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@3772b77a
09-09 13:35:39.332  6670  6670 W System.err: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
09-09 13:35:39.332  6670  6670 W System.err: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
09-09 13:35:39.332  6670  6670 W System.err: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
09-09 13:35:39.332  6670  6670 W System.err: 	at com.uei.control.Service.c(Unknown Source)
09-09 13:35:39.332  6670  6670 W System.err: 	at com.uei.control.Service.onDestroy(Unknown Source)
09-09 13:35:39.332  6670  6670 W System.err: 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
09-09 13:35:39.332  6670  6670 W System.err: 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
09-09 13:35:39.332  6670  6670 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
09-09 13:35:39.332  6670  6670 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 13:35:39.332  6670  6670 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-09 13:35:39.332  6670  6670 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-09 13:35:39.332  6670  6670 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 13:35:39.332  6670  6670 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 13:35:39.332  6670  6670 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-09 13:35:39.332  6670  6670 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-09 13:35:39.332  6670  6670 E UEI.SmartControl: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@3772b77a
09-09 13:35:39.334  6670  6670 D serial_port: close(fd = 24)
09-09 13:35:39.338  6670  6670 I UEI.SmartControl: Serial port is closed.
09-09 13:35:39.338  6670  6670 I UEI.SmartControl: Serial port is closed.
09-09 13:35:39.338  6670  6670 D UEI.SmartControl: Blaster closed
09-09 13:35:39.338  6670  6670 D UEI.SmartControl: Shut down QS...
09-09 13:35:39.338  6670  6670 D UEI.SmartControl: Stopping QS lib
09-09 13:35:39.338  6670  6670 D UEI.SmartControl: QS lib stop result = true
09-09 13:35:39.338  6670  6670 D UEI.SmartControl: Stopped QS lib
09-09 13:35:39.338  6670  6670 D UEI.SmartControl: QS shutdown complete
,09-09 13:35:43.617  6562  6617 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-09 13:35:43.617  6562  6617 I jxcore-log: 
,09-09 13:35:43.620  6562  6617 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-09 13:35:43.620  6562  6617 I jxcore-log: 
09-09 13:35:43.624  6562  6617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:35:43.624  6562  6617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:35:43.624  6562  6617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:35:43.624  6562  6617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:35:43.624  6562  6617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:35:43.624  6562  6617 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:35:43.624  6562  6617 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:35:43.624  6562  6617 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:35:43.626  6562  6617 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:35:43.628  6562  6617 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-09 13:35:43.628  6562  6617 I jxcore-log: 
09-09 13:35:43.629  6562  6617 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-09 13:35:43.629  6562  6617 I jxcore-log: 
09-09 13:35:43.647  2136  2136 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19981
,09-09 13:35:44.132  1036  1093 I ActivityManager: Waited long enough for: ServiceRecord{b93a2eb u0 com.google.android.gms/.wearable.service.WearableService}
,09-09 13:35:44.148  6562  6617 I jxcore-log: Unit Test app is loaded
09-09 13:35:44.148  6562  6617 I jxcore-log: 
,09-09 13:35:44.158  6562  6562 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-09 13:35:44.164  6562  6617 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:35:44.164  6562  6617 I jxcore-log: 
09-09 13:35:44.181  6562  6617 D executeNativeTests: Running unit tests
,09-09 13:35:44.182  6562  6617 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 13:35:44.182  6562  6617 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2837ca96 added. We now have 2 listener(s)
09-09 13:35:44.183  1036  1923 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 13:35:44.187  6562  6617 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-09 13:35:44.187  6562  6617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 13:35:44.187  6562  6617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 13:35:44.187  6562  6617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 13:35:44.187  6562  6617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@257f2617 added. We now have 2 listener(s)
09-09 13:35:44.187  6562  6617 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 13:35:44.187  6562  6617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-09 13:35:44.190  6562  6617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:35:44.192  6562  6617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:35:44.192  6562  6617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:35:44.192  6562  6617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:35:44.192  6562  6617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:35:44.192  6562  6617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:35:44.192  6562  6617 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:35:44.192  6562  6617 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:35:44.192  6562  6617 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:35:44.192  6562  6617 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:35:44.193  6562  6617 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 13:35:44.195  6562  6562 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:35:44.196  6562  6562 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:35:45.798  1036  1377 V AlarmManager: RTC_WAKEUP set : Alarm{11ee55fe type 0 when 1473420944799 com.android.vending} when 1473420944799
,09-09 13:35:45.861  4501  6719 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,09-09 13:35:46.001  1036  1923 V SIM_STK : Menu title from STK is T-Mobile
,09-09 13:35:46.083  6013  6013 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.
,09-09 13:35:54.402  6562  6617 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 13:35:54.402  6562  6617 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13a34a5d added. We now have 3 listener(s)
,09-09 13:35:54.405  1036  2036 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 13:35:54.408  6562  6617 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-09 13:35:54.408  6562  6617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 13:35:54.408  6562  6617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 13:35:54.408  6562  6617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 13:35:54.408  6562  6617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3e1d2fd2 added. We now have 3 listener(s)
09-09 13:35:54.408  6562  6617 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 13:35:54.409  6562  6617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-09 13:35:54.412  6562  6617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:35:54.416  6562  6617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:35:54.416  6562  6617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:35:54.416  6562  6617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:35:54.416  6562  6617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:35:54.416  6562  6617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:35:54.416  6562  6617 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:35:54.416  6562  6617 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:35:54.416  6562  6617 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:35:54.421  6562  6617 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:35:54.421  6562  6617 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 13:35:54.423  6562  6562 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:35:54.425  6562  6562 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:35:54.431  6562  6617 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-09 13:35:54.435  6562  6617 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-09 13:35:54.435  6562  6617 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-09 13:35:54.435  6562  6617 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-09 13:35:54.437  6562  6617 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-09 13:35:54.438  6562  6617 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-09 13:35:54.438  6562  6617 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-09 13:35:54.438  6562  6617 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 13:35:54.438  6562  6617 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 13:35:54.439  6562  6617 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 13:35:54.439  6562  6617 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:35:54.439  6562  6617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:54.439  6562  6617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:35:54.439  6562  6617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 13:35:54.440  6562  6617 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13a34a5d removed from the list
09-09 13:35:54.440  6562  6617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:35:54.440  6562  6617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3e1d2fd2 removed from the list
09-09 13:35:54.440  6562  6617 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:35:54.440  6562  6617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:35:54.444  6562  6617 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-09 13:35:54.444  6562  6617 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:35:54.444  6562  6617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:54.444  6562  6617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:35:54.444  6562  6617 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13a34a5d not in the list
09-09 13:35:54.444  6562  6617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:35:54.444  6562  6617 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3e1d2fd2 not in the list
09-09 13:35:54.444  6562  6617 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:35:54.444  6562  6617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:54.444  6562  6617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: relea,se: 2 listener(s) left
,09-09 13:35:54.460  6562  6617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-09 13:35:54.460  6562  6617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-09 13:35:54.460  6562  6617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-09 13:35:54.460  6562  6617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-09 13:35:54.460  6562  6617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-09 13:35:54.460  6562  6617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-09 13:35:54.460  6562  6617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-09 13:35:54.460  6562  6617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-09 13:35:54.460  6562  6617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-09 13:35:54.460  6562  6617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-09 13:35:54.460  6562  6617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-09 13:35:54.460  6562  6617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-09 13:35:54.460  6562  6617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-09 13:35:54.460  6562  6617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-09 13:35:54.460  6562  6617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-09 13:35:54.460  6562  6617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-09 13:35:54.460  6562  6617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-09 13:35:54.460  6562  6617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-09 13:35:54.460  6562  6617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-09 13:35:54.460  6562  6617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-09 13:35:54.460  6562  6617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-09 13:35:54.461  6562  6617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-09 13:35:54.461  6562  6617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-09 13:35:54.461  6562  6617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-09 13:35:54.461  6562  6617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-09 13:35:54.461  6562  6617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-09 13:35:54.461  6562  6617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 3,5:2510:2510:2510:2510:2510]
09-09 13:35:54.461  6562  6617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-09 13:35:54.461  6562  6617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-09 13:35:54.461  6562  6617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-09 13:35:54.461  6562  6617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-09 13:35:54.461  6562  6617 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:35:54.461  6562  6617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:54.461  6562  6617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:35:54.461  6562  6617 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13a34a5d not in the list
09-09 13:35:54.461  6562  6617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 13:35:54.461  6562  6617 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3e1d2fd2 not in the list
09-09 13:35:54.461  6562  6617 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:35:54.461  6562  6617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:54.461  6562  6617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:35:54.462  6562  6617 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-09 13:35:54.472  6562  6617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:35:54.475  6562  6617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:35:54.475  6562  6617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:35:54.475  6562  6617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:35:54.475  6562  6617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:35:54.475  6562  6617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:35:54.475  6562  6617 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:35:54.475  6562  6617 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:35:54.475  6562  6617 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:35:54.477  6562  6617 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:35:54.477  6562  6617 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 13:35:54.481  6562  6562 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:35:54.482  6562  6562 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:35:54.483  6562  6617 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 13:35:54.484  6562  6617 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-09 13:35:54.484  6562  6617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-09 13:35:54.484  6562  6617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:35:54.484  6562  6617 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-09 13:35:54.489  6562  6617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-09 13:35:54.491  1036  1051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 13:35:54.498  6562  6617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-09 13:35:54.505  6562  6617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-09 13:35:54.509  6562  6617 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
09-09 13:35:54.511  6562  6617 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 13:35:54.511  6562  6617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:35:54.513  6562  6617 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-09 13:35:54.514  6562  6617 I io.jxcore.node.ConnectionHelper: start: OK
09-09 13:35:54.515  6562  6617 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
09-09 13:35:54.515  6562  6617 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
09-09 13:35:54.515  6562  6617 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 13:35:54.518  6562  6617 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-09 13:35:54.518  6562  6617 V io.jxcore.node.ConnectivityMonitor: start: Already started
09-09 13:35:54.518  6562  6617 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 13:35:54.518  6562  6617 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-09 13:35:54.518  6562  6617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-09 13:35:54.518  6562  6617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:35:54.519  6562  6617 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-09 13:35:54.528  6562  6617 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 13:35:54.528  6562  6617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:35:54.530  6562  6617 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-09 13:35:54.530  6562  6617 I io.jxcore.node.ConnectionHelper: start: OK
09-09 13:35:54.530  6562  6617 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:35:54.530  6562  6617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:54.530  6562  6617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:35:54.530  6562  6617 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13a34a5d not in the list
09-09 13:35:54.530  6562  6617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:35:54.530  6562  6617 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3e1d2fd2 not in the list
09-09 13:35:54.530  6562  6617 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:35:54.530  6562  6617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:35:54.534  6562  6617 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-09 13:35:54.740  1036  1578 I art     : Explicit concurrent mark sweep GC freed 26435(1368KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/65MB, paused 3.250ms total 203.033ms
,09-09 13:35:54.744  6562  6617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:35:54.749  6562  6617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:35:54.749  6562  6617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:35:54.749  6562  6617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:35:54.749  6562  6617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:35:54.749  6562  6617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:35:54.749  6562  6617 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:35:54.749  6562  6617 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:35:54.749  6562  6617 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:35:54.755  6562  6617 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:35:54.755  6562  6617 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 13:35:54.759  6562  6562 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:35:54.761  6562  6562 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:35:54.761  6562  6617 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 13:35:54.761  6562  6617 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-09 13:35:54.762  6562  6617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-09 13:35:54.762  6562  6617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:35:54.762  6562  6617 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-09 13:35:54.777  6562  6617 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-09 13:35:54.779  6562  6617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:35:54.781  6562  6617 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-09 13:35:54.782  6562  6617 I io.jxcore.node.ConnectionHelper: start: OK
09-09 13:35:54.782  6562  6617 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
09-09 13:35:54.782  6562  6617 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
09-09 13:35:54.782  6562  6617 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 13:35:54.785  6562  6617 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:35:54.785  6562  6617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:54.785  6562  6617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:35:54.785  6562  6617 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13a34a5d not in the list
09-09 13:35:54.785  6562  6617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:35:54.785  6562  6617 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3e1d2fd2 not in the list
09-09 13:35:54.785  6562  6617 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:35:54.785  6562  6617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:35:54.787  6562  6617 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-09 13:35:54.787  6562  6617 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:35:54.787  6562  6617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:54.787  6562  6617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:35:54.788  6562  6617 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13a34a5d not in the list
09-09 13:35:54.788  6562  6617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:35:54.788  6562  6617 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3e1d2fd2 not in the list
09-09 13:35:54.788  6562  6617 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:35:54.788  6562  6617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:54.788  6562  6617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:35:54.789  6562  6617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-09 13:35:54.789  6562  6617 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:35:54.789  6562  6617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:54.789  6562  6617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:35:54.789  6562  6617 E org.thaliproject.p2p.btconnecto,rlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13a34a5d not in the list
09-09 13:35:54.789  6562  6617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:35:54.790  6562  6617 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3e1d2fd2 not in the list
09-09 13:35:54.790  6562  6617 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:35:54.790  6562  6617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:54.790  6562  6617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:35:54.790  6562  6617 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-09 13:35:54.791  6562  6617 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:35:54.791  6562  6617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:54.791  6562  6617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:35:54.791  6562  6617 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13a34a5d not in the list
09-09 13:35:54.791  6562  6617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:35:54.791  6562  6617 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3e1d2fd2 not in the list
09-09 13:35:54.791  6562  6617 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:35:54.791  6562  6617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:54.792  6562  6617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:35:54.793  6562  6617 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-09 13:35:54.794  6562  6617 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:35:54.794  6562  6617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:54.794  6562  6617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:35:54.794  6562  6617 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13a34a5d not in the list
09-09 13:35:54.794  6562  6617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:35:54.794  6562  6617 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3e1d2fd2 not in the list
09-09 13:35:54.794  6562  6617 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:35:54.794  6562  6617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:54.794  6562  6617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:35:54.795  6562  6617 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-09 13:35:54.802  6562  6617 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-09 13:35:54.802  6562  6617 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-09 13:35:54.802  6562  6617 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-09 13:35:54.802  6562  6617 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 13:35:54.802  6562  6617 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 13:35:54.802  6562  6617 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-09 13:35:54.802  6562  6617 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-09 13:35:54.802  6562  6617 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-09 13:35:54.803  6562  6617 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:35:54.803  6562  6617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:54.803  6562  6617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:35:54.803  6562  6617 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13a34a5d not in the list
09-09 13:35:54.803  6562  6617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:35:54.803  6562  6617 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3e1d2fd2 not in the list
09-09 13:35:54.803  6562  6617 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:35:54.803  6562  6617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:54.803  6562  6617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:35:54.804  6562  6617 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 13:35:54.804  6562  6617 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-09 13:35:54.804  6562  6617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-09 13:35:54.808  6562  6617 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 13:35:54.808  6562  6617 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-09 13:35:54.808  6562  6617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-09 13:35:54.808  6562  6617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-09 13:35:54.808  6562  6617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-09 13:35:54.809  6562  6617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-09 13:35:54.809  6562  6617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-09 13:35:54.809  6562  6617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-09 13:35:54.810  6562  6617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-09 13:35:54.810  6562  6617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-09 13:35:54.810  6562  6617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-09 13:35:54.810  6562  6617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-09 13:35:54.810  6562  6617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-09 13:35:54.810  6562  6617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-09 13:35:54.810  6562  6617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-09 13:35:54.810  6562  6617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-09 13:35:54.810  6562  6617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-09 13:35:54.810  6562  6617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-09 13:35:54.810  6562  6617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-09 13:35:54.810  6562  6617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-09 13:35:54.810  6562  6617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-09 13:35:54.810  6562  6617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-09 13:35:54.810  6562  6617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-09 13:35:54.810  6562  6617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-09 13:35:54.810  6562  6617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-09 13:35:54.810  6562  6617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-09 13:35:54.810  6562  6617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-09 13:35:54.810  6562  6617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-09 13:35:54.810  6562  6617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-09 13:35:54.811  6562  6617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-09 13:35:54.811  6562  6617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-09 13:35:54.811  6562  6617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-09 13:35:54.811  6562  6617 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-09 13:35:54.811  6562  6617 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-09 13:35:54.811  6562  6617 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-09 13:35:54.811  6562  6617 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 13:35:54.811  6562  6617 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-09 13:35:54.811  6562  6617 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-09 13:35:54.812  6562  6617 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 13:35:54.812  6562  6617 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-09 13:35:54.812  6562  6617 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-09 13:35:54.815  6562  6617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-09 13:35:54.818  6562  6617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-09 13:35:54.819  6562  6617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-09 13:35:54.820  6562  6617 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-09 13:35:54.820  6562  6617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-09 13:35:54.821  6562  6617 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-09 13:35:54.821  6562  6617 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 13:35:54.821  6562  6617 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-09 13:35:54.821  6562  6617 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:35:54.821  6562  6617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:54.821  6562  6617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:35:54.822  6562  6761 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 858)
09-09 13:35:54.824  6562  6617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-09 13:35:54.826  6562  6617 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13a34a5d not in the list
09-09 13:35:54.826  6562  6617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:35:54.827  6562  6617 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3e1d2fd2 not in the list
09-09 13:35:54.827  6562  6617 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:35:54.827  6562  6617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:54.827  6562  6617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:35:54.828  6562  6617 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-09 13:35:54.828  6562  6617 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:35:54.828  6562  6617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:54.828  6562  6617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:35:54.828  6562  6617 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13a34a5d not in the list
,09-09 13:35:54.829  6562  6617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:35:54.830  6562  6617 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3e1d2fd2 not in the list
09-09 13:35:54.830  6562  6617 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:35:54.830  6562  6617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:54.830  6562  6617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:35:54.833  6562  6762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 858
09-09 13:35:54.834  6562  6762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 858)
09-09 13:35:54.834  6562  6762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 858)
09-09 13:35:54.836  6562  6617 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-09 13:35:54.837  6562  6617 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:35:54.837  6562  6617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:54.837  6562  6617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:35:54.837  6562  6617 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13a34a5d not in the list
09-09 13:35:54.837  6562  6617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:35:54.837  6562  6617 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3e1d2fd2 not in the list
09-09 13:35:54.837  6562  6617 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:35:54.837  6562  6617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:54.837  6562  6617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:35:54.838  6562  6617 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-09 13:35:54.839  6562  6617 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-09 13:35:54.839  6562  6617 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-09 13:35:54.839  6562  6617 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-09 13:35:54.839  6562  6617 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-09 13:35:54.839  6562  6617 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-09 13:35:54.839  6562  6617 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-09 13:35:54.839  6562  6617 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-09 13:35:54.839  6562  6617 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-09 13:35:54.839  6562  6617 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-09 13:35:54.840  6562  6617 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-09 13:35:54.840  6562  6617 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-09 13:35:54.840  6562  6617 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:35:54.840  6562  6617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:54.840  6562  6617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:35:54.840  6562  6617 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13a34a5d not in the list
09-09 13:35:54.840  6562  6617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:35:54.840  6562  6617 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3e1d2fd2 not in the list
09-09 13:35:54.840  6562  6617 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:35:54.840  6562  6617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:54.840  6562  6617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:35:54.841  6562  6617 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-09 13:35:54.842  6562  6617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:35:54.851  6562  6617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:35:54.851  6562  6617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:35:54.851  6562  6617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:35:54.851  6562  6617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:35:54.851  6562  6617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:35:54.851  6562  6617 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:35:54.851  6562  6617 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:35:54.851  6562  6617 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:35:54.855  6562  6617 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:35:54.855  6562  6617 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 13:35:54.856  6562  6617 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 13:35:54.856  6562  6617 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-09 13:35:54.857  6562  6617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-09 13:35:54.857  6562  6617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:35:54.857  6562  6617 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-09 13:35:54.858  6562  6562 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:35:54.862  6562  6562 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:35:54.865  6562  6617 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 13:35:54.866  6562  6617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-09 13:35:54.868  6562  6617 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-09 13:35:54.868  6562  6617 I io.jxcore.node.ConnectionHelper: start: OK
09-09 13:35:54.869  6562  6617 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:35:54.869  6562  6617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:54.869  6562  6617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:35:54.869  6562  6617 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13a34a5d not in the list
09-09 13:35:54.869  6562  6617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:35:54.869  6562  6617 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3e1d2fd2 not in the list
09-09 13:35:54.869  6562  6617 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:35:54.869  6562  6617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:35:54.873  6562  6617 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:35:54.874  6562  6617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:54.874  6562  6617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:35:54.874  6562  6617 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13a34a5d not in the list
09-09 13:35:54.874  6562  6617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:35:54.874  6562  6617 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3e1d2fd2 not in the list
09-09 13:35:54.874  6562  6617 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:35:54.874  6562  6617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:54.874  6562  6617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:35:54.876  6562  6617 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-09 13:35:54.878  6562  6617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:35:54.879  6562  6617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-09 13:35:54.880  6562  6617 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-09 13:35:54.880  6562  6617 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-09 13:35:54.881  6562  6562 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-09 13:35:54.881  6562  6617 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-09 13:35:54.881  6562  6617 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-09 13:35:54.881  1036  2035 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 13:35:54.882  6562  6773 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 13:35:54.882  6562  6617 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:35:54.882  6562  6617 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-09 13:35:54.882  6562  6617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-09 13:35:54.882  6562  6617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-09 13:35:54.883  6562  6617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:35:54.883  6562  6617 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-09 13:35:54.883  6562  6562 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-09 13:35:54.883  6562  6617 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13a34a5d not in the list
09-09 13:35:54.883  6562  6617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:35:54.883  3858  3873 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=84 mFd=82
09-09 13:35:54.883  6562  6617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 13:35:54.883  6562  6617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 13:35:54.883  6562  6617 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-09 13:35:54.884  6562  6773 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-09 13:35:54.884  6562  6773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-09 13:35:54.884  6562  6773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-09 13:35:54.884  6562  6617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-09 13:35:54.887  6562  6617 D BluetoothLeScanner: could not find callback wrapper
09-09 13:35:54.888  6562  6617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 13:35:54.888  6562  6617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-09 13:35:54.888  6562  6617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:54.888  6562  6617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:35:54.890  6562  6617 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 13:35:54.891  6562  6562 I org.thaliproject,.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 13:35:54.891  6562  6617 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3e1d2fd2 not in the list
09-09 13:35:54.891  6562  6562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 13:35:54.891  6562  6617 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:35:54.891  6562  6562 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-09 13:35:54.891  6562  6617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:54.891  6562  6562 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 13:35:54.891  6562  6617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:35:54.894  6562  6617 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-09 13:35:54.895  6562  6617 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-09 13:35:54.895  6562  6617 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-09 13:35:54.895  6562  6617 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 13:35:54.895  6562  6617 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 13:35:54.896  6562  6617 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:35:54.896  6562  6617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:54.896  6562  6617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:35:54.896  6562  6617 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13a34a5d not in the list
09-09 13:35:54.896  6562  6617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:35:54.897  6562  6617 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3e1d2fd2 not in the list
09-09 13:35:54.897  6562  6617 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:35:54.897  6562  6617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:54.897  6562  6617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:35:54.900  1036  1780 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 13:35:54.901  1036  1052 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 13:35:54.903  1036  1051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-09 13:35:54.904  6562  6617 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:35:54.904  6562  6617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:54.904  6562  6617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:35:54.904  6562  6617 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13a34a5d not in the list
09-09 13:35:54.904  6562  6617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:35:54.904  6562  6617 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3e1d2fd2 not in the list
09-09 13:35:54.905  6562  6617 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:35:54.905  6562  6617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:54.905  6562  6617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:35:54.917  6562  6617 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:35:54.917  6562  6617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:54.917  6562  6617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:35:54.917  6562  6617 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13a34a5d not in the list
09-09 13:35:54.917  6562  6617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:35:54.917  6562  6617 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3e1d2fd2 not in the list
09-09 13:35:54.917  6562  6617 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:35:54.917  6562  6617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:54.917  6562  6617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:35:54.918  6562  6617 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-09 13:35:54.918  6562  6617 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-09 13:35:54.919  6562  6617 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-09 13:35:54.919  6562  6617 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-09 13:35:54.919  6562  6617 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-09 13:35:54.919  6562  6617 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-09 13:35:54.921  6562  6617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-09 13:35:54.921  6562  6617 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-09 13:35:54.922  6562  6617 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-09 13:35:54.922  6562  6617 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-09 13:35:54.923  6562  6617 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-09 13:35:54.923  6562  6617 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-09 13:35:54.923  6562  6617 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-09 13:35:54.923  6562  6617 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-09 13:35:54.924  6562  6617 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-09 13:35:54.924  6562  6617 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-09 13:35:54.924  6562  6617 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-09 13:35:54.925  6562  6617 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-09 13:35:54.925  6562  6617 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-09 13:35:54.925  6562  6617 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-09 13:35:54.927  6562  6617 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 13:35:54.928  6562  6617 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f002ab8 added. We now have 3 listener(s)
09-09 13:35:54.928  1036  1999 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 13:35:54.932  6562  6617 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-09 13:35:54.932  6562  6617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 13:35:54.932  6562  6617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 13:35:54.932  6562  6617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 13:35:54.932  65,62  6617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2667091 added. We now have 3 listener(s)
09-09 13:35:54.932  6562  6617 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 13:35:54.937  6562  6617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-09 13:35:54.939  6562  6617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:35:54.943  6562  6617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:35:54.943  6562  6617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:35:54.943  6562  6617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:35:54.943  6562  6617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:35:54.943  6562  6617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:35:54.943  6562  6617 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:35:54.943  6562  6617 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:35:54.943  6562  6617 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:35:54.944  6562  6617 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 13:35:54.944  6562  6617 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 13:35:54.947  6562  6562 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:35:54.948  6562  6617 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:35:54.948  6562  6617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:54.948  6562  6617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:35:54.948  6562  6617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 13:35:54.949  6562  6617 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f002ab8 removed from the list
09-09 13:35:54.949  6562  6617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:35:54.949  6562  6617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2667091 removed from the list
09-09 13:35:54.949  6562  6562 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:35:54.954  6562  6617 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:35:54.954  6562  6617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:35:54.956  6562  6617 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 13:35:54.956  6562  6617 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d597bf7 added. We now have 3 listener(s)
,09-09 13:35:54.957  1036  1981 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 13:35:54.959  6562  6617 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-09 13:35:54.959  6562  6617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 13:35:54.959  6562  6617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 13:35:54.960  6562  6617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 13:35:54.960  6562  6617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ae93a64 added. We now have 3 listener(s)
09-09 13:35:54.960  6562  6617 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 13:35:54.960  6562  6617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-09 13:35:54.962  6562  6617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:35:54.966  6562  6617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:35:54.966  6562  6617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:35:54.966  6562  6617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:35:54.966  6562  6617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:35:54.966  6562  6617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:35:54.966  6562  6617 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:35:54.966  6562  6617 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:35:54.966  6562  6617 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:35:54.968  6562  6617 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:35:54.968  6562  6617 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 13:35:54.969  6562  6617 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:35:54.969  6562  6617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:35:54.969  6562  6617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-09 13:35:54.969  6562  6617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-09 13:35:54.969  6562  6617 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d597bf7 removed from the list
09-09 13:35:54.969  6562  6617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:35:54.969  6562  6617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ae93a64 removed from the list
09-09 13:35:54.971  6562  6562 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:35:54.971  6562  6617 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:35:54.971  6562  6617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:35:54.973  6562  6562 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:35:54.974  6562  6761 W LGMDMUISystemServiceAdapter: checkBluetoothPairing btPolicy: false
09-09 13:35:54.974  6562  6617 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 13:35:54.974  6562  6617 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15ed3182 added. We now have 3 listener(s)
09-09 13:35:54.974  1036  1052 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 13:35:54.975  6562  6761 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 858)
09-09 13:35:54.976  6562  6617 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-09 13:35:54.977  6562  6617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 13:35:54.977  6562  6617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 13:35:54.977  6562  6617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 13:35:54.977  6562  6617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@279fe093 added. We now have 3 listener(s)
09-09 13:35:54.977  6562  6617 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 13:35:54.977  6562  6617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-09 13:35:54.980  6562  6617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:35:54.984  6562  6617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:35:54.984  6562  6617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:35:54.984  6562  6617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:35:54.984  6562  6617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:35:54.984  6562  6617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:35:54.984  6562  6617 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:35:54.984  6562  6617 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:35:54.984  6562  6617 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:35:54.986  6562  6617 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:35:54.986  6562  6617 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 13:35:54.989  6562  6562 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:35:54.990  1036  1578 D WifiServiceImplEx: setWifiEnabled: false pid=6562, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-09 13:35:54.990  1036  1578 D WifiService: setWifiEnabled: false pid=6562, uid=10118
09-09 13:35:54.990  1036  1578 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-09 13:35:54.992  6562  6562 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:35:55.009  1036  1392 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
09-09 13:35:55.011  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-09 13:35:55.012  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-09 13:35:55.012  1036  1036 D Ulp_jni : JNI:system_update. Event-4
09-09 13:35:55.012  1036  1392 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
09-09 13:35:55.014  1036  1392 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
09-09 13:35:55.015  1036  1392 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
09-09 13:35:55.016  1036  1392 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
09-09 13:35:55.017  1036  1392 E WifiStateMachine: WifiStateMachine: Leaving Connected state
09-09 13:35:55.017  1036  1392 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-09 13:35:55.017  1036  1392 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-09 13:35:55.018  1036  1392 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-09 13:35:55.019  1036  1392 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-09 13:35:55.035  1036  1392 D WifiNative-wlan0: SAVE_CONFIG: returned true
,09-09 13:35:55.036  1036  1392 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-09 13:35:55.037  2744  2744 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-09 13:35:55.037  1036  1389 D LGWifiP2pService: InactiveState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:35:55.037  1036  1392 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-09 13:35:55.037  1036  1389 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:35:55.037  1036  1392 D WifiNative-wlan0: doBoolean: SET ps 1
09-09 13:35:55.038  1036  1392 D WifiNative-wlan0: SET ps 1: returned true
09-09 13:35:55.038  1036  2867 D DhcpStateMachine: RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:35:55.044   311   893 D CommandListener: Clearing all IP addresses on wlan0
09-09 13:35:55.093  1036  1435 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-09 13:35:55.094  1036  1435 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,09-09 13:35:55.101  1036  1036 D WifiHS20: hidePasspointNotification off =false
09-09 13:35:55.104  1945  1945 V WfdStateTracker: handleWifiStateChangedEvent: 0
09-09 13:35:55.108  1036  1616 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
09-09 13:35:55.109  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 13:35:55.109  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-09 13:35:55.112  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:35:55.113  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:35:55.113  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-09 13:35:55.114  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 13:35:55.114  1036  2866 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-6ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:35:55.114  1036  2866 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-6ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:35:55.114  1036  2866 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
09-09 13:35:55.114  1036  2866 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=4 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:35:55.114  1036  2866 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on <unknown ssid>
09-09 13:35:55.122  1036  1036 D WifiHS20: hidePasspointNotification off =false
09-09 13:35:55.126  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-09 13:35:55.126  6373  6373 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-09 13:35:55.126  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:35:55.126  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-09 13:35:55.126  1036  1389 D LGWifiP2pService: InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:35:55.126  1036  1389 D LGWifiP2pService: P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:35:55.127  1036  1389 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@cc9388d
09-09 13:35:55.128  1036  1392 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 13:35:55.129  1036  1036 D WifiScanningService: SCAN_AVAILABLE : 1
09-09 13:35:55.129  1036  1392 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 13:35:55.129  1036  1559 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:35:55.129  1036  1392 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 13:35:55.130  1036  1036 D RttService: SCAN_AVAILABLE : 1
09-09 13:35:55.130  1036  1392 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 13:35:55.130  1036  1560 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:35:55.130  1036  1392 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 13:35:55.131  1036  1389 D LGWifiP2pService: P2pDisablingState
09-09 13:35:55.133  1945  1945 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-09 13:35:55.133  1945  1945 D WfdsService: WifiP2pState is changed : false
09-09 13:35:55.133  1945  2280 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
09-09 13:35:55.133  1945  2280 D WfdsService: Set the WFDS Monitor: false
09-09 13:35:55.134  1036  1392 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 13:35:55.135  1036  1392 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-09 13:35:55.135  1036  1389 D LGWifiP2pService: P2pDisablingState{ when=-8ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:35:55.135  1036  1389 D LGWifiP2pService: p2p socket connection lost
09-09 13:35:55.135  1036  1389 D LGWifiP2pService: P2pDisabledState
09-09 13:35:55.135  1945  2280 D WfdsMonitor: WFDS Monitor is stopped
09-09 13:35:55.136  1945  2280 D WfdsService: STATE : WfdsDisabledState - enter
09-09 13:35:55.136  1945  2782 D CtrlSupplicant: Received on exit socket, terminate
09-09 13:35:55.136  1945  2782 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
09-09 13:35:55.136  1945  2782 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
09-09 13:35:55.136  1945  2782 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
09-09 13:35:55.137  1945  2281 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
09-09 13:35:55.137  1945  2280 W WfdsService: DefaultState - msg [9445378] is not handled
,09-09 13:35:55.138  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-09 13:35:55.138  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 13:35:55.140  1036  1392 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
09-09 13:35:55.140  1036  1392 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-09 13:35:55.140  1036  1389 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:35:55.140  1036  1389 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:35:55.141  2744  2744 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-09 13:35:55.141  1036  1392 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-09 13:35:55.141  1036  1392 D WifiNative-wlan0: doBoolean: SET ps 1
09-09 13:35:55.141  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 13:35:55.143  1036  1392 D WifiNative-wlan0: SET ps 1: returned true
09-09 13:35:55.175  1036  2035 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6783 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-09 13:35:55.177  1036  1435 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
09-09 13:35:55.177  1036  1435 D DSQN    : disableDataServiceNotify
09-09 13:35:55.177  1036  1435 D DSQN    : stop dsqn bin
09-09 13:35:55.178   311   893 D CommandListener: Clearing all IP addresses on wlan0
09-09 13:35:55.179   311  6793 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
09-09 13:35:55.179  1036  2866 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
09-09 13:35:55.180  1036  1110 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
09-09 13:35:55.183  1036  1392 D WifiNative-p2p0: doBoolean: TERMINATE
09-09 13:35:55.184  1036  1435 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-09 13:35:55.184  1036  1435 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:35:55.184  1036  1036 D WifiHS20: hidePasspointNotification off =false
,09-09 13:35:55.184  1036  1435 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 13:35:55.185  1036  1435 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 13:35:55.185  1036  1435 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
09-09 13:35:55.185  1605  2090 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
09-09 13:35:55.186  1036  1435 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
09-09 13:35:55.186  1036  1435 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-09 13:35:55.186  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-09 13:35:55.186  1036  1435 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-09 13:35:55.186  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 13:35:55.187  1036  2866 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:35:55.187  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:35:55.187  1036  2866 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:35:55.187  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:35:55.187  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-09 13:35:55.187  1036  2866 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
09-09 13:35:55.187  1036  1392 D WifiNative-p2p0: TERMINATE: returned true
09-09 13:35:55.187  1036  1392 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-09 13:35:55.187  1036  1392 E WifiStateMachine: useWiFiOffloading() : false
09-09 13:35:55.187  1036  1392 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-09 13:35:55.188  1036  1435 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-09 13:35:55.188  1036  1435 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-09 13:35:55.188  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 13:35:55.190  1036  1388 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-09 13:35:55.191  1036  1036 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-09 13:35:55.191  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-09 13:35:55.191  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: fa,lse, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-09 13:35:55.191  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-09 13:35:55.198  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
09-09 13:35:55.198  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-09 13:35:55.198  1036  1036 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
09-09 13:35:55.199  1945  1945 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
09-09 13:35:55.199  1036  1435 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-09 13:35:55.199  1036  1435 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:35:55.199  1036  1435 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:35:55.199  1036  1435 D NetworkManagementService: Removing idletimer
09-09 13:35:55.199  1857  1857 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:35:55.200  1857  1857 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-09 13:35:55.200  1036  1435 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:35:55.200  1036  1392 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:35:55.200  1036  1392 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 13:35:55.201  1036  1388 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-09 13:35:55.201  1036  1036 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-09 13:35:55.203  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-09 13:35:55.203  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-09 13:35:55.203  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-09 13:35:55.204  1036  1435 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,09-09 13:35:55.213  6562  6562 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:35:55.213  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:35:55.213  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:35:55.213  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 13:35:55.213  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:35:55.213  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:35:55.213  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:35:55.213  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:35:55.214  6562  6562 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 13:35:55.217  6562  6562 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:35:55.217  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:35:55.217  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:35:55.217  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 13:35:55.217  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:35:55.217  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:35:55.217  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:35:55.217  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 13:35:55.218  6562  6562 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 13:35:55.220  6562  6562 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:35:55.220  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:35:55.220  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:35:55.220  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 13:35:55.220  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:35:55.220  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:35:55.220  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:35:55.220  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 13:35:55.224  6562  6562 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-09 13:35:55.239  1605  1605 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-09 13:35:55.240  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 13:35:55.241  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 13:35:55.241  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 13:35:55.246  1036  2867 D DhcpStateMachine: StoppedState
09-09 13:35:55.246  1036  2867 D DhcpStateMachine: StoppedState{ when=-104ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:35:55.247  1036  1392 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
09-09 13:35:55.248  1036  1392 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
09-09 13:35:55.256  1605  1605 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-09 13:35:55.257  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-09 13:35:55.257  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 13:35:55.258  2744  2744 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
09-09 13:35:55.258  2744  2744 I wpa_supplicant: monitor socket send errors count : 1
09-09 13:35:55.258  2744  2744 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1945-2\x00 that cannot receive messages
09-09 13:35:55.259  1036  2780 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
09-09 13:35:55.259  1036  2780 D WifiMonitor: Dropping event because (p2p0) is stopped
09-09 13:35:55.272  6783  6783 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,09-09 13:35:55.276  6783  6783 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-09 13:35:55.276  6783  6783 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-09 13:35:55.296  2744  2744 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-09 13:35:55.297  1036  2780 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
09-09 13:35:55.297  1036  2780 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-09 13:35:55.297  2744  2744 W wpa_supplicant: USIM:  scard_deinit function
09-09 13:35:55.297  1036  2780 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-09 13:35:55.298  1036  2780 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
09-09 13:35:55.298  1036  2780 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-09 13:35:55.298  1036  2780 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-09 13:35:55.299  1036  1392 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=128000
09-09 13:35:55.299  1036  1112 D Tethering: InitialState.processMessage what=4
09-09 13:35:55.299  1036  1392 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=128001
09-09 13:35:55.300  1036  1392 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=128001  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-09 13:35:55.300  1036  1392 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=128001  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
,09-09 13:35:55.310  1036  1781 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.wifi.wifioffload.WiFiOffLoadBroadcast: pid=6804 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
09-09 13:35:55.311  1036  1781 I ActivityManager: Killing 6144:com.android.providers.calendar/u0a14 (adj 15): empty #17
09-09 13:35:55.392  6562  6562 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-09 13:35:55.399  1036  1112 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-09 13:35:55.400  1036  1780 W libprocessgroup: failed to open /acct/uid_10014/pid_6144/cgroup.procs: No such file or directory
09-09 13:35:55.409  2744  2744 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-09 13:35:55.415  1036  2780 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
09-09 13:35:55.415  1036  2780 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
09-09 13:35:55.416  1036  2780 D WifiMonitor: Disconnecting from the supplicant, no more events
09-09 13:35:55.418  1036  1392 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
,09-09 13:35:55.462  6804  6804 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-09 13:35:55.462  6804  6804 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
,09-09 13:35:55.463  6804  6804 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-09 13:35:55.463  6804  6804 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
09-09 13:35:55.465  6804  6804 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-09 13:35:55.465  6804  6804 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
09-09 13:35:55.514  1036  1616 D WifiServiceImplEx: setWifiEnabled: true pid=6562, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-09 13:35:55.516  1036  1616 D WifiService: setWifiEnabled: true pid=6562, uid=10118
09-09 13:35:55.516  1036  1616 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-09 13:35:55.520  1036  1392 D WifiOffDelayIfNotUsed: stopMonitoring
09-09 13:35:55.520  1036  1392 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-09 13:35:55.520  1036  1392 E WifiStateMachine: useWiFiOffloading() : false
09-09 13:35:55.520  1036  1392 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-09 13:35:55.523  1945  1945 D WfdsService: Supplicant Connection state is changed : false
09-09 13:35:55.523  1945  2280 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
09-09 13:35:55.523  1945  1945 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-09 13:35:55.524  1945  2280 D WfdsService: Set the WFDS Monitor: false
09-09 13:35:55.524  1945  2280 D WfdsMonitor: WFDS Monitor is stopped
09-09 13:35:55.524  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
09-09 13:35:55.524  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 13:35:55.525  1036  1396 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
09-09 13:35:55.525  1036  1396 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
09-09 13:35:55.526  2477  2477 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:35:55.529  6562  6562 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:35:55.529  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:35:55.529  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:35:55.529  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 13:35:55.529  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:35:55.529  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:35:55.529  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:35:55.529  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 13:35:55.531  6562  6562 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:35:55.532  6562  6562 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:35:55.541  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-09 13:35:55.542  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-09 13:35:55.542  1036  1036 D Ulp_jni : JNI:system_update. Event-4
,09-09 13:35:55.638  6804  6804 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 13:35:55.670  6804  6804 D LgDataFeature: LgDataFeature() Constructor: none
09-09 13:35:55.670  6804  6804 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-09 13:35:55.681  6804  6804 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-09 13:35:55.724  1036  1392 E WifiStateMachine:  InitialState CMD_TETHER_STATE_CHANGE 0 0
09-09 13:35:55.725  1036  1392 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,09-09 13:35:55.727  1036  1392 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
09-09 13:35:55.727  1036  1392 I LGFTMITEM: [GET_FTM][id=6], offset=12288
,09-09 13:35:55.730  1036  1392 E WifiUtil: wfc_util_ffile_check_copy(): pid[1036] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
09-09 13:35:55.730  1036  1392 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-09 13:35:55.730  1036  1392 E WifiUtil: wfc_util_ffile_check_copy(): pid[1036] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
09-09 13:35:55.730  1036  1392 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-09 13:35:55.731  1036  1392 I WifiUtil: Intf0MacAddress=C49A027FFB5D
09-09 13:35:55.731  1036  1392 E WifiHW  : unknown target_country: EU , set to default
09-09 13:35:55.731  1036  1392 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
09-09 13:35:55.731  1036  1392 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
09-09 13:35:55.731  1036  1392 I WifiUtil: gEnableBmps=1
09-09 13:35:55.774  1036  2036 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6825 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,09-09 13:35:55.775  1036  2036 I ActivityManager: Killing 6255:com.android.defcontainer/u0a4 (adj 15): empty #17
09-09 13:35:55.809   343   343 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 880us total 32.671ms
,09-09 13:35:55.832   343   343 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 454us total 21.201ms
,09-09 13:35:55.854   343   343 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 454us total 21.184ms
,09-09 13:35:55.858  1036  1051 W libprocessgroup: failed to open /acct/uid_10004/pid_6255/cgroup.procs: No such file or directory
,09-09 13:35:55.887  6825  6825 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-09 13:35:55.925  6825  6825 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,09-09 13:35:55.964  6825  6825 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
09-09 13:35:55.965  6825  6825 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
09-09 13:35:55.965  6825  6825 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
09-09 13:35:55.966  6825  6825 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
09-09 13:35:55.966  6825  6825 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
09-09 13:35:55.968  6825  6825 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,09-09 13:35:55.974  6825  6825 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
,09-09 13:35:55.981  6825  6825 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-09 13:35:55.986  6825  6825 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-09 13:35:56.018  6825  6825 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-09 13:35:56.021  6825  6825 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
09-09 13:35:56.021  6373  6373 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-09 13:35:56.024  6825  6825 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
09-09 13:35:56.025  6783  6783 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-09 13:35:56.025  6783  6783 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-09 13:35:56.025  6783  6783 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-09 13:35:56.028  6804  6804 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 13:35:56.035  6804  6804 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 13:35:56.043  6825  6825 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-09 13:35:56.043  6825  6825 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 13:35:56.044  6825  6825 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-09 13:35:56.049  6373  6373 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-09 13:35:56.055  6783  6783 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-09 13:35:56.055  6783  6783 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-09 13:35:56.055  6783  6783 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-09 13:35:56.060  6804  6804 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 13:35:56.068  6804  6804 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 13:35:56.077  6825  6825 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-09 13:35:56.078  6825  6825 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-09 13:35:56.081  6825  6825 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-09 13:35:56.144  1036  1999 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6851 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,09-09 13:35:56.246  6783  6783 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-09 13:35:56.249  6804  6804 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-09 13:35:56.256  6804  6804 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 13:35:56.276  6804  6804 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-09 13:35:56.277  6804  6804 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-09 13:35:56.277  6804  6804 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-09 13:35:56.277  6804  6804 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-09 13:35:56.279  6804  6804 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,09-09 13:35:56.306  6804  6804 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-09 13:35:56.306  6804  6804 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
,09-09 13:35:56.307  6804  6804 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-09 13:35:56.307  6804  6804 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-09 13:35:56.307  6804  6804 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-09 13:35:56.307  6804  6804 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-09 13:35:56.313  4328  4328 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-09 13:35:56.313  4328  4328 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-09 13:35:56.317  4328  4328 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-09 13:35:56.319  4328  4328 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-09 13:35:56.326  4328  6878 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-09 13:35:56.330  6783  6783 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
09-09 13:35:56.330  6783  6783 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-09 13:35:56.330  6783  6783 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-09 13:35:56.330  4328  6883 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-09 13:35:56.331  4328  6883 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,09-09 13:35:56.336  6804  6804 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-09 13:35:56.341  6851  6870 W FormManager: Network not available. Please check & try again.
09-09 13:35:56.342  6804  6804 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-09 13:35:56.354  6851  6884 V FormManager: Network unavailable.
,09-09 13:35:56.361  6851  6884 V FormManager: Network unavailable.
09-09 13:35:56.362  6825  6825 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
09-09 13:35:56.364  6825  6825 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
09-09 13:35:56.364  6825  6825 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
09-09 13:35:56.374  6851  6886 W FormManager: Network not available. Please check & try again.
,09-09 13:35:56.378  6851  6887 V FormManager: Network unavailable.
09-09 13:35:56.380  6851  6887 V FormManager: Network unavailable.
09-09 13:35:56.384  1036  1781 I ActivityManager: Killing 6435:com.google.android.partnersetup/u0a8 (adj 15): empty #17
09-09 13:35:56.401  6825  6825 D LgDataFeature: LgDataFeature() Constructor: none
,09-09 13:35:56.401  6825  6825 D LgDataFeature: LgDataFeature() Constructor Done, null
09-09 13:35:56.407  6825  6825 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
09-09 13:35:56.409  6825  6825 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
09-09 13:35:56.409  6825  6825 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
09-09 13:35:56.409  6825  6825 V SoundPool: doLoad: loading sample sampleID=1
09-09 13:35:56.409  6825  6825 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
09-09 13:35:56.410  6825  6896 V SoundPool: Start decode
09-09 13:35:56.410  6825  6896 V MediaPlayer[Native]: decode(31, 10857164, 17813)
09-09 13:35:56.410   315  1403 V MediaPlayerService: decode(23, 10857164, 17813)
09-09 13:35:56.411   315  1403 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
09-09 13:35:56.411   315  1403 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
09-09 13:35:56.411   315  1403 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
09-09 13:35:56.411   315  1403 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
09-09 13:35:56.411   315  1403 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
09-09 13:35:56.411   315  1403 V MediaPlayerService: player type = 3
09-09 13:35:56.411   315  1403 V AwesomePlayer: AwesomePlayer create()
09-09 13:35:56.411   315  1403 V AwesomePlayer: reset_l() 
09-09 13:35:56.411   315  1403 V AwesomePlayer: cancelPlayerEvents
09-09 13:35:56.411   315  1403 V AwesomePlayer: setAudioSink() 
09-09 13:35:56.411   315  1403 V AwesomePlayer: reset_l() 
09-09 13:35:56.412   315  1403 V AudioCache: notify(0xb1012200, 8, 0, 0)
09-09 13:35:56.412   315  1403 V AudioCache: ignored
09-09 13:35:56.412   315  1403 V AwesomePlayer: cancelPlayerEvents
09-09 13:35:56.412   315  1403 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
09-09 13:35:56.412   315  1403 V AwesomePlayer: setDataSource_l dataSource
09-09 13:35:56.412   315  1403 V LGParserOSAL: SniffLGParser start
09-09 13:35:56.412   315  1403 V LGParserOSAL: MainType:5, SubType=0
09-09 13:35:56.412   315  1403 V LGParserOSAL: #### check Mime : application/ogg
09-09 13:35:56.412   315  1403 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
,09-09 13:35:56.412   315  1403 E MediaExtractor: Use LGExtractor :application/ogg 
09-09 13:35:56.430  1036  1944 W libprocessgroup: failed to open /acct/uid_10008/pid_6435/cgroup.procs: No such file or directory
09-09 13:35:56.441  6670  6670 D UEI.SmartControl: QS Service created
09-09 13:35:56.442  6825  6825 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,09-09 13:35:56.444  6825  6825 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-09 13:35:56.444  6825  6825 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
09-09 13:35:56.458  6825  6825 V LGMDMManager: Create singleton instance
,09-09 13:35:56.462  1036  1112 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-09 13:35:56.463  6670  6670 I UEI.SmartControl: Service initServices...
09-09 13:35:56.463  6670  6670 D UEI.SmartControl: QS start get config
09-09 13:35:56.466   311   893 D SoftapController: Softap fwReload - Ok
09-09 13:35:56.467  1036  1392 E NetdConnector: NDC Command {53 softap fwreload wlan0 STA} took too long (728ms)
09-09 13:35:56.471   311   893 D CommandListener: Setting iface cfg
09-09 13:35:56.471   311   893 D CommandListener: Trying to bring down wlan0
09-09 13:35:56.476   311   893 D CommandListener: Clearing all IP addresses on wlan0
,09-09 13:35:56.471  6900  6900 W wpa_supplicant: type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6841 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-09 13:35:56.471  6900  6900 W wpa_supplicant: type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6841 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-09 13:35:56.480  1036  1392 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
09-09 13:35:56.499   315  1403 V LGParserOSAL: supported mime: application/ogg
09-09 13:35:56.499   315  1403 V AwesomePlayer: setDataSource_l() extractor countTracks=1
,09-09 13:35:56.499   315  1403 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
09-09 13:35:56.499   315  1403 V AwesomePlayer: mBitrate = -1 bits/sec
09-09 13:35:56.499   315  1403 V AwesomePlayer: AudioTrack Setting
09-09 13:35:56.499   315  1403 V AwesomePlayer: AudioTrack Setting channelCount = 2
09-09 13:35:56.499   315  1403 V AwesomePlayer: setAudioSource() 
09-09 13:35:56.499   315  1403 V MediaPlayerService: prepare
09-09 13:35:56.499   315  1403 V AwesomePlayer: prepareAsync_l() 
09-09 13:35:56.499   315  1403 V MediaPlayerService: wait for prepare
09-09 13:35:56.501   315  6901 V AwesomePlayer: onPrepareAsyncEvent() 
09-09 13:35:56.501   315  6901 V AwesomePlayer: initAudioDecoder() 
09-09 13:35:56.501   315  6901 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
09-09 13:35:56.501   315  6901 V AudioSystem: isOffloadSupported()
09-09 13:35:56.501   315  6901 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
09-09 13:35:56.502   315  6901 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
09-09 13:35:56.502   315  6901 I AudioFlinger: isAudioPlaybackHookOn() false
09-09 13:35:56.502   315  6901 V AwesomePlayer: getUseOffload() = 0 
09-09 13:35:56.502   315  6901 V OMXCodec: OMXCodec::Create
09-09 13:35:56.502   315  6901 V OMXCodec: findMatchingCodecs()
09-09 13:35:56.502   315  6901 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
09-09 13:35:56.502   315  6901 V OMXCodec: matchingCodecs.size()=1
09-09 13:35:56.502   315  6901 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
09-09 13:35:56.504   315  6901 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
09-09 13:35:56.504   315  6901 V LGCodecAdapter: LG Codec Adapter start
09-09 13:35:56.504   315  6901 V OMXCodec: OMXCodec Createtor
09-09 13:35:56.504   315  6901 V OMXCodec: setComponentRole
09-09 13:35:56.504   315  6901 V OMXCodec: configureCodec protected=0
09-09 13:35:56.504   315  6901 V LGCodecAdapter: called getLGCodecSpecificData
09-09 13:35:56.504   315  6901 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
09-09 13:35:56.504   315  6901 V LGCodecOSAL: Called LGconfigureCodecMETA
09-09 13:35:56.504   315  6901 V LGCodecOSAL: Called LGconfigureCodecMSG
09-09 13:35:56.504   315  6901 V LGCodecOSAL: Not support LGCodec
09-09 13:35:56.504   315  6901 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
09-09 13:35:56.504   315  6901 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
09-09 13:35:56.505   315  6901 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
09-09 13:35:56.505   315  6901 I AwesomePlayer: Could not offload audio decode, try pcm offload
09-09 13:35:56.505   315  6901 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
09-09 13:35:56.505   315  6901 V AudioSystem: isOffloadSupported()
09-09 13:35:56.505   315  6901 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
09-09 13:35:56.505   315  6901 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
09-09 13:35:56.505   315  6901 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
09-09 13:35:56.505   315  6901 V OMXCodec: init()
09-09 13:35:56.505   315  6901 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
09-09 13:35:56.505   315  6901 V OMXCodec: allocateBuffers
09-09 13:35:56.505   315  6901 V OMXCodec: allocateBuffersOnPort portIndex=0
09-0,9 13:35:56.505   315  6901 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
09-09 13:35:56.505   315  6901 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on input port
09-09 13:35:56.505   315  6901 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7bf0 on input port
09-09 13:35:56.505   315  6901 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c40 on input port
09-09 13:35:56.505   315  6901 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57c8510 on input port
09-09 13:35:56.505   315  6901 V OMXCodec: allocateBuffersOnPort portIndex=1
09-09 13:35:56.505   315  6901 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
09-09 13:35:56.505   315  6901 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57c86a0 on output port
09-09 13:35:56.505   315  6901 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57c8790 on output port
09-09 13:35:56.505   315  6901 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57c8830 on output port
09-09 13:35:56.505   315  6901 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57c8880 on output port
09-09 13:35:56.506   315  6901 V OMXCodec: init() mAsyncCompletion wait!!! 
09-09 13:35:56.506   315  6903 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
09-09 13:35:56.506   315  6903 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
09-09 13:35:56.506   315  6903 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
09-09 13:35:56.506   315  6903 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
09-09 13:35:56.506   315  6903 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
09-09 13:35:56.506   315  6903 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
09-09 13:35:56.506   315  6901 V OMXCodec: init() mAsyncCompletion wait free! 
09-09 13:35:56.506   315  6901 V AwesomePlayer: finishAsyncPrepare_l() 
09-09 13:35:56.506   315  6901 V AudioCache: notify(0xb1012200, 5, 0, 0)
09-09 13:35:56.506   315  6901 V AudioCache: ignored
09-09 13:35:56.506   315  6901 V AudioCache: notify(0xb1012200, 1, 0, 0)
09-09 13:35:56.506   315  6901 V AudioCache: prepared
09-09 13:35:56.506   315  1403 V AudioCache: wait - success
09-09 13:35:56.506   315  1403 V MediaPlayerService: start
09-09 13:35:56.506   315  1403 V AwesomePlayer: play_l() 
09-09 13:35:56.506   315  1403 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
09-09 13:35:56.506   315  1403 V AwesomePlayer: createAudioPlayer_l
09-09 13:35:56.506   315  1403 V AwesomePlayer: seekAudioIfNecessary_l() 
09-09 13:35:56.506   315  1403 V AwesomePlayer: startAudioPlayer_l() 
09-09 13:35:56.506   315  1403 D AudioPlayer: start of Playback, useOffload 0
09-09 13:35:56.506   315  1403 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
09-09 13:35:56.506   315  1403 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
09-09 13:35:56.507  6900  6900 I wpa_supplicant: Successfully initialized wpa_supplicant
09-09 13:35:56.509   315  6903 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
09-09 13:35:56.509   315  6903 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
09-09 13:35:56.509   315  6903 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
09-09 13:35:56.509   315  6903 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
09-09 13:35:56.509   315  6903 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
09-09 13:35:56.509   315  6903 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
09-09 13:35:56.509   315  6903 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044837024
09-09 13:35:56.509   315  6903 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-09 13:35:56.509   315  6903 V OMXCodec: [OMX.google.vorbis.decoder] Port is disa,bled, freeing buffer 3044837264
09-09 13:35:56.509   315  6903 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-09 13:35:56.509   315  6903 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044837424
09-09 13:35:56.509   315  6903 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-09 13:35:56.510   315  6903 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044837504
09-09 13:35:56.510   315  6903 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-09 13:35:56.510   315  6903 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
09-09 13:35:56.510   315  6903 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
09-09 13:35:56.510   315  6903 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
09-09 13:35:56.510   315  6903 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
09-09 13:35:56.510   315  6903 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
09-09 13:35:56.510   315  6903 V OMXCodec: allocateBuffersOnPort portIndex=1
09-09 13:35:56.510   315  6903 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
09-09 13:35:56.510   315  6903 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57c8830 on output port
09-09 13:35:56.510   315  6903 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57c8790 on output port
09-09 13:35:56.510   315  6903 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57c86a0 on output port
09-09 13:35:56.510   315  6903 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb04101f0 on output port
09-09 13:35:56.510   315  6903 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
09-09 13:35:56.510   315  6903 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
09-09 13:35:56.511   315  1403 V AudioCache: open(48000, 2, 0x0, 1, 4)
09-09 13:35:56.512   315  1403 V AudioCache: notify(0xb1012200, 6, 0, 0)
09-09 13:35:56.512   315  1403 V AudioCache: ignored
09-09 13:35:56.515   315  6904 V AudioCache: write(0xb16af000, 4096)
09-09 13:35:56.515   315  6904 V AudioCache: memcpy(0xaf006000, 0xb16af000, 4096)
09-09 13:35:56.515   315  1403 V MediaPlayerService: wait for playback complete
09-09 13:35:56.518   315  6904 V AudioCache: write(0xb16af000, 4096)
09-09 13:35:56.518   315  6904 V AudioCache: memcpy(0xaf007000, 0xb16af000, 4096)
09-09 13:35:56.518   315  6904 V AudioCache: write(0xb16af000, 4096)
09-09 13:35:56.518   315  6904 V AudioCache: memcpy(0xaf008000, 0xb16af000, 4096)
09-09 13:35:56.519   315  6904 V AudioCache: write(0xb16af000, 4096)
09-09 13:35:56.519   315  6904 V AudioCache: memcpy(0xaf009000, 0xb16af000, 4096)
09-09 13:35:56.520   315  6904 V AudioCache: write(0xb16af000, 4096)
09-09 13:35:56.520   315  6904 V AudioCache: memcpy(0xaf00a000, 0xb16af000, 4096)
09-09 13:35:56.520   315  6904 V AudioCache: write(0xb16af000, 4096)
09-09 13:35:56.521   315  6904 V AudioCache: memcpy(0xaf00b000, 0xb16af000, 4096)
09-09 13:35:56.521   315  6904 V AudioCache: write(0xb16af000, 4096)
09-09 13:35:56.521   315  6904 V AudioCache: memcpy(0xaf00c000, 0xb16af000, 4096)
09-09 13:35:56.522   315  6904 V AudioCache: write(0xb16af000, 4096)
09-09 13:35:56.522   315  6904 V AudioCache: memcpy(0xaf00d000, 0xb16af000, 4096)
09-09 13:35:56.523   315  6904 V AudioCache: write(0xb16af000, 4096)
09-09 13:35:56.523   315  6904 V AudioCache: memcpy(0xaf00e000, 0xb16af000, 4096)
09-09 13:35:56.523   315  6904 V AudioCache: write(0xb16af000, 4096)
09-09 13:35:56.523   315  6904 V AudioCache: memcpy(0xaf00f000, 0xb16af000, 4096)
09-09 13:35:56.524   315  6904 V AudioCache: write(0xb16af000, 4096)
09-09 13:35:56.524   315  6904 V AudioCache: memcpy(0xaf010000, 0xb16af000, 4096)
09-09 13:35:56.525   315  6904 V AudioCache: write(0xb16af000, 4096)
09-09 13:35:56.525   315  6904 V AudioCache: memcpy(0xaf011000, 0xb16af000, 4096)
09-09 13:35:56.525   315  6904 V AudioCache: write(0xb16af000, 4096)
09-09 13:35:56.525   315  6904 V AudioCache: memcpy(0xaf012000, 0xb16af000, 4096)
09-09 13:35:56.527   315  6904 V AudioCache: write(0xb16af000, 4096)
09-09 13:35:56.527   315  6904 V AudioCache: memcpy(0xaf013000, 0xb16af000, 4096)
09-09 13:35:56.528   315  6904 V AudioCache: write(0xb16af000, 4096)
09-09 13:35:56.528   315  6904 V AudioCache: memcpy(0xaf014000, 0xb16af000, 4096)
09-09 13:35:56.528   315  6904 V AudioCache: write(0xb16af000, 4096)
09-09 13:35:56.528   315  6904 V AudioCache: memcpy(0xaf015000, 0xb16af000, 4096)
09-09 13:35:56.529   315  6904 V AudioCache: write(0xb16af000, 4096)
09-09 13:35:56.529   315  6904 V AudioCache: memcpy(0xaf016000, 0xb16af000, 4096)
09-09 13:35:56.530   315  6904 V AudioCache: write(0xb16af000, 4096)
09-09 13:35:56.530   315  6904 V AudioCache: memcpy(0xaf017000, 0xb16af000, 4096)
09-09 13:35:56.530   315  6904 V AudioCache: write(0xb16af000, 4096)
09-09 13:35:56.530   315  6904 V AudioCache: memcpy(0xaf018000, 0xb16af000, 4096)
09-09 13:35:56.531   315  6904 V AudioCache: write(0xb16af000, 4096)
09-09 13:35:56.531   315  6904 V AudioCache: memcpy(0xaf019000, 0xb16af000, 4096)
09-09 13:35:56.531   315  6904 V AudioCache: write(0xb16af000, 4096)
09-09 13:35:56.532   315  6904 V AudioCache: memcpy(0xaf01a000, 0xb16af000, 4096)
09-09 13:35:56.532   315  6904 V AudioCache: write(0xb16af000, 4096)
09-09 13:35:56.532   315  6904 V AudioCache: memcpy(0xaf01b000, 0xb16af000, 4096)
09-09 13:35:56.532  6900  6900 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-09 13:35:56.533  6900  6900 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
09-09 13:35:56.533   315  6904 V AudioCache: write(0xb16af000, 4096)
09-09 13:35:56.533   315  6904 V AudioCache: memcpy(0xaf01c000, 0xb16af000, 4096)
09-09 13:35:56.533   315  6904 V AudioCache: write(0xb16af000, 4096)
09-09 13:35:56.534   315  6904 V AudioCache: memcpy(0xaf01d000, 0xb16af000, 4096)
09-09 13:35:56.534  1036  1112 D Tethering: InitialState.processMessage what=4
09-09 13:35:56.535   315  6904 V AudioCache: write(0xb16af000, 4096)
09-09 13:35:56.535  1036  1112 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-09 13:35:56.535   315  6904 V AudioCache: memcpy(0xaf01e000, 0xb16af000, 4096)
09-09 13:35:56.535   315  6904 V AudioCache: write(0xb16af000, 4096)
09-09 13:35:56.535   315  6904 V AudioCache: memcpy(0xaf01f000, 0xb16af000, 4096)
09-09 13:35:56.536   315  6904 V AudioCache: write(0xb16af000, 4096)
09-09 13:35:56.536   315  6904 V AudioCache: memcpy(0xaf020000, 0xb16af000, 4096)
,09-09 13:35:56.538   315  6904 V AudioCache: write(0xb16af000, 4096)
09-09 13:35:56.538   315  6904 V AudioCache: memcpy(0xaf021000, 0xb16af000, 4096)
09-09 13:35:56.538   315  6904 V AudioCache: write(0xb16af000, 4096)
09-09 13:35:56.538   315  6904 V AudioCache: memcpy(0xaf022000, 0xb16af000, 4096)
09-09 13:35:56.539   315  6904 V AudioCache: write(0xb16af000, 4096)
09-09 13:35:56.539   315  6904 V AudioCache: memcpy(0xaf023000, 0xb16af000, 4096)
09-09 13:35:56.540   315  6904 V AudioCache: write(0xb16af000, 4096)
09-09 13:35:56.540   315  6904 V AudioCache: memcpy(0xaf024000, 0xb16af000, 4096)
09-09 13:35:56.540   315  6904 V AudioCache: write(0xb16af000, 4096)
09-09 13:35:56.540   315  6904 V AudioCache: memcpy(0xaf025000, 0xb16af000, 4096)
09-09 13:35:56.541   315  6904 V AudioCache: write(0xb16af000, 4096)
09-09 13:35:56.541   315  6904 V AudioCache: memcpy(0xaf026000, 0xb16af000, 4096)
09-09 13:35:56.541   315  6904 V AudioCache: write(0xb16af000, 4096)
09-09 13:35:56.541   315  6904 V AudioCache: memcpy(0xaf027000, 0xb16af000, 4096)
09-09 13:35:56.541   315  6904 V AudioCache: write(0xb16af000, 4096)
09-09 13:35:56.541   315  6904 V AudioCache: memcpy(0xaf028000, 0xb16af000, 4096)
09-09 13:35:56.542   315  6904 V AudioCache: write(0xb16af000, 4096)
09-09 13:35:56.542   315  6904 V AudioCache: memcpy(0xaf029000, 0xb16af000, 4096)
09-09 13:35:56.542   315  6904 V AudioCache: write(0xb16af000, 4096)
09-09 13:35:56.542   315  6904 V AudioCache: memcpy(0xaf02a000, 0xb16af000, 4096)
09-09 13:35:56.542   315  6904 V AudioCache: write(0xb16af000, 4096)
09-09 13:35:56.542   315  6904 V AudioCache: memcpy(0xaf02b000, 0xb16af000, 4096)
09-09 13:35:56.542   315  6904 V AudioCache: write(0xb16af000, 4096)
09-09 13:35:56.542   315  6904 V AudioCache: memcpy(0xaf02c000, 0xb16af000, 4096)
09-09 13:35:56.544   315  6904 V AudioCache: write(0xb16af000, 4096)
09-09 13:35:56.544   315  6904 V AudioCache: memcpy(0xaf02d000, 0xb16af000, 4096)
09-09 13:35:56.544   315  6904 V AudioCache: write(0xb16af000, 4096)
09-09 13:35:56.544   315  6904 V AudioCache: memcpy(0xaf02e000, 0xb16af000, 4096)
09-09 13:35:56.544   315  6904 V AudioCache: write(0xb16af000, 4096)
09-09 13:35:56.544   315  6904 V AudioCache: memcpy(0xaf02f000, 0xb16af000, 4096)
09-09 13:35:56.544   315  6904 V AudioCache: write(0xb16af000, 4096)
09-09 13:35:56.544   315  6904 V AudioCache: memcpy(0xaf030000, 0xb16af000, 4096)
09-09 13:35:56.546   315  6904 V AudioCache: write(0xb16af000, 4096)
09-09 13:35:56.546   315  6904 V AudioCache: memcpy(0xaf031000, 0xb16af000, 4096)
09-09 13:35:56.546   315  6904 V AudioCache: write(0xb16af000, 4096)
09-09 13:35:56.546   315  6904 V AudioCache: memcpy(0xaf032000, 0xb16af000, 4096)
09-09 13:35:56.546   315  6904 V AudioCache: write(0xb16af000, 4096)
09-09 13:35:56.546   315  6904 V AudioCache: memcpy(0xaf033000, 0xb16af000, 4096)
09-09 13:35:56.546   315  6904 V AudioCache: write(0xb16af000, 4096)
09-09 13:35:56.546   315  6904 V AudioCache: memcpy(0xaf034000, 0xb16af000, 4096)
09-09 13:35:56.547   315  6904 V AudioCache: write(0xb16af000, 4096)
09-09 13:35:56.547   315  6904 V AudioCache: memcpy(0xaf035000, 0xb16af000, 4096)
09-09 13:35:56.547   315  6904 V AudioCache: write(0xb16af000, 4096)
09-09 13:35:56.547   315  6904 V AudioCache: memcpy(0xaf036000, 0xb16af000, 4096)
09-09 13:35:56.547   315  6904 V AudioCache: write(0xb16af000, 4096)
09-09 13:35:56.547   315  6904 V AudioCache: memcpy(0xaf037000, 0xb16af000, 4096)
09-09 13:35:56.547   315  6903 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
09-09 13:35:56.548   315  6904 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
09-09 13:35:56.548   315  6904 V AwesomePlayer: postAudioEOS() 
09-09 13:35:56.548   315  6904 V AudioCache: write(0xb16af000, 280)
09-09 13:35:56.548   315  6904 V AudioCache: memcpy(0xaf038000, 0xb16af000, 280)
09-09 13:35:56.549   315  6901 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
09-09 13:35:56.549   315  6901 V AwesomePlayer: onStreamDone
09-09 13:35:56.549   315  6901 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
09-09 13:35:56.549   315  6901 V AudioCache: notify(0xb1012200, 2, 0, 0)
09-09 13:35:56.549   315  6901 V AudioCache: playback complete
09-09 13:35:56.549   315  6901 V AwesomePlayer: pause_l() 
09-09 13:35:56.549   315  6901 V AudioCache: notify(0xb1012200, 7, 0, 0)
09-09 13:35:56.549   315  6901 V AudioCache: ignored
09-09 13:35:56.549   315  6901 V AwesomePlayer: cancelPlayerEvents
09-09 13:35:56.549   315  1403 V AudioCache: wait - success
09-09 13:35:56.549   315  1403 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
09-09 13:35:56.549   315  6901 D AudioPlayer: Pause Playback at 1068125
09-09 13:35:56.551   315  1403 V AwesomePlayer: reset_l() 
09-09 13:35:56.551   315  1403 V AudioCache: notify(0xb1012200, 8, 0, 0)
09-09 13:35:56.551   315  1403 V AudioCache: ignored
09-09 13:35:56.551   315  1403 V AwesomePlayer: cancelPlayerEvents
09-09 13:35:56.551   315  1403 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
09-09 13:35:56.551   315  1403 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
09-09 13:35:56.551   315  1403 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
09-09 13:35:56.551   315  1403 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
09-09 13:35:56.551   315  1403 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
09-09 13:35:56.551   315  6903 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
09-09 13:35:56.551   315  6903 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
09-09 13:35:56.551   315  6903 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
09-09 13:35:56.551   315  6903 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb57c8510 on port 0
09-09 13:35:56.551   315  6903 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
09-09 13:35:56.551   315  6903 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7c40 on port 0
09-09 13:35:56.551   315  6903 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
09-09 13:35:56.551   315  6903 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7bf0 on port 0
09-09 13:35:56.551   315  6903 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
09-09 13:35:56.551   315  6903 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b50 on port 0
09-09 13:35:56.551   315  6903 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
09-09 13:35:56.551   315  6903 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
09-09 13:35:56.551   315  6903 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb04101f0 on port 1
09-09 13:35:56.551   315  6903 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
09-09 13:35:56.551   315  6903 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb57c86a0 on port 1
09-09 13:35:56.551   315  6903 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
09-09 13:35:56.551   315  6903 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb57c8790 on port 1
09-09 13:35:56.551   315  6903 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
09-09 13:35:56.551   315  6903 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb57c8830 on port 1
09-09 13:35:56.551   315  6903 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-09 13:35:56.551   315  6903 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
09-09 13:35:56.551   315  1403 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
09-09 13:35:56.551   315  1403 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
09-09 13:35:56.552   315  6903 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
09-09 13:35:56.552   315  6903 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
09-09 13:35:56.552   315  6903 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
09-09 13:35:56.552   315  1403 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
09-09 13:35:56.552   315  1403 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
09-09 13:35:56.552   315  1403 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
09-09 13:35:56.553   315  1403 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
09-09 13:35:56.553   315  1403 D AudioPlayer: AudioPlayer releasing audio source
09-09 13:35:56.553   315  1403 D AudioPlayer: AudioPlayer done releasing audio source
09-09 13:35:56.553   315  1403 V AwesomePlayer: reset_l() 
09-09 13:35:56.553   315  1403 V AwesomePlayer: cancelPlayerEvents
09-09 13:35:56.553   315  1403 V AwesomePlayer: ~AwesomePlayer call
09-09 13:35:56.553   315  1403 V AwesomePlayer: reset_l() 
09-09 13:35:56.553   315  1403 V AwesomePlayer: cancelPlayerEvents
09-09 13:35:56.554  6825  6896 V SoundPool: close(31)
09-09 13:35:56.554  6825  6896 V SoundPool: pointer = 0xa0000000, size = 205080, sampleRate = 48000, numChannels = 2
09-09 13:35:56.567  6825  6825 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
09-09 13:35:56.568  6825  6825 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
09-09 13:35:56.572  6825  6825 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:816
09-09 13:35:56.574  6804  6804 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-09 13:35:56.574  6804  6804 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-09 13:35:56.574  6804  6804 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-09 13:35:56.574  6804  6804 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-09 13:35:56.574  6804  6804 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-09 13:35:56.575  6804  6804 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-09 13:35:56.575  6804  6804 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-09 13:35:56.575  6804  6804 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-09 13:35:56.575  6804  6804 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-09 13:35:56.575  6804  6804 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-09 13:35:56.575  6804  6804 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-09 13:35:56.580  1036  1392 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-09 13:35:56.580  1036  1392 E WifiStateMachine: useWiFiOffloading() : false
09-09 13:35:56.580  1036  1392 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,09-09 13:35:56.581  1036  1392 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
09-09 13:35:56.581  1036  1392 D WifiMonitor: connecting to supplicant
09-09 13:35:56.583  1945  1945 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
09-09 13:35:56.583  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 13:35:56.584  6562  6562 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:35:56.585  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
09-09 13:35:56.585  6562  6562 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:35:56.586  6562  6562 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:35:56.588  6783  6783 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-09 13:35:56.590  6804  6804 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-09 13:35:56.593  6851  6906 W FormManager: Network not available. Please check & try again.
09-09 13:35:56.595  6851  6907 V FormManager: Network unavailable.
09-09 13:35:56.596  6804  6804 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 13:35:56.599  6851  6907 V FormManager: Network unavailable.
09-09 13:35:56.605  6900  6900 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-09 13:35:56.666  6900  6900 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,09-09 13:35:56.680  1036  1392 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
09-09 13:35:56.681  1036  1392 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
09-09 13:35:56.681  1036  1392 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
09-09 13:35:56.681  1036  1392 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
09-09 13:35:56.682  6900  6900 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
09-09 13:35:56.682  6900  6900 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
,09-09 13:35:56.682  1036  1392 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
09-09 13:35:56.683  1036  1392 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-09 13:35:56.683  1036  1392 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
09-09 13:35:56.684  1036  1392 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-09 13:35:56.684  1036  1392 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
09-09 13:35:56.684  1036  1392 D WifiNative-wlan0: doString: [DRIVER MACADDR]
09-09 13:35:56.684  1036  6908 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
09-09 13:35:56.684  1036  6908 D WifiMonitor: Dropping event because (p2p0) is stopped
09-09 13:35:56.684  1036  6908 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
09-09 13:35:56.684  1036  6908 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
09-09 13:35:56.684  1036  6908 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
09-09 13:35:56.685  1036  6908 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
09-09 13:35:56.685  1036  1392 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
09-09 13:35:56.685  1036  1392 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
09-09 13:35:56.685  1036  1392 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
09-09 13:35:56.686  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:35:56.686  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:35:56.687  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:35:56.687  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:35:56.687  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-09 13:35:56.687  1036  1392 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-09 13:35:56.687  1036  1392 E WifiStateMachine: useWiFiOffloading() : false
09-09 13:35:56.687  1036  1392 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-09 13:35:56.689  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 13:35:56.690  1945  1945 D WfdService: Waiting for WifiP2p enabling
09-09 13:35:56.692  1036  1392 D WifiNative-wlan0: doBoolean: SET update_config 1
09-09 13:35:56.693  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
09-09 13:35:56.694  1036  1396 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
09-09 13:35:56.695  1036  1392 D WifiNative-wlan0: SET update_config 1: returned true
09-09 13:35:56.695  1036  1392 D WifiConfigStore: Loading config and enabling all networks 
09-09 13:35:56.695  1036  1392 D WifiNative-wlan0: doString: [LIST_NETWORKS]
,09-09 13:35:56.696  1036  1392 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
09-09 13:35:56.700  6562  6562 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:35:56.700  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:35:56.700  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:35:56.700  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:35:56.700  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:35:56.700  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:35:56.700  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:35:56.700  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 13:35:56.702  1036  1392 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
09-09 13:35:56.706  6562  6562 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 13:35:56.708  6783  6783 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-09 13:35:56.709  6804  6804 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-09 13:35:56.712  6851  6910 W FormManager: Network not available. Please check & try again.
09-09 13:35:56.712  6562  6562 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:35:56.712  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:35:56.712  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:35:56.712  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:35:56.712  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:35:56.712  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:35:56.712  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:35:56.712  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 13:35:56.713  1036  1392 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
09-09 13:35:56.713  1036  1392 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-09 13:35:56.715  1036  1392 D WifiStateMachine: enableVerboseLogging : level 2
09-09 13:35:56.715  1036  1392 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
09-09 13:35:56.715  1036  1392 D WifiNative-wlan0: SET device_name g3_global_com: returned true
09-09 13:35:56.715  1036  1392 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
09-09 13:35:56.716  1036  1392 D WifiNative-wlan0: SET manufacturer LGE: returned true
09-09 13:35:56.716  1036  1392 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
09-09 13:35:56.716  1036  1392 D WifiNative-wlan0: SET model_name LG-D855: returned true
09-09 13:35:56.716  1036  1392 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
,09-09 13:35:56.717  1036  1392 D WifiNative-wlan0: SET model_number LG-D855: returned true
09-09 13:35:56.717  1036  1392 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
09-09 13:35:56.717  6562  6562 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 13:35:56.717  1036  1392 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
09-09 13:35:56.717  1036  1392 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
09-09 13:35:56.718  1036  1392 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
09-09 13:35:56.718  1036  1392 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
09-09 13:35:56.718  1036  1392 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
09-09 13:35:56.719  1945  1945 D WfdsService: Supplicant Connection state is changed : true
09-09 13:35:56.719  1036  1392 D WifiStateMachine: Setting OUI to DA-A1-19
09-09 13:35:56.719  1036  1392 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
09-09 13:35:56.719  1945  2280 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
09-09 13:35:56.719  1945  2280 D WfdsService: Set the WFDS Monitor: true
09-09 13:35:56.719  1945  2280 D WfdsMonitor: WfdsMonitorThread create
09-09 13:35:56.719  1945  2280 D WfdsMonitor: WFDS Monitor is created and started
09-09 13:35:56.720  1945  2280 D WfdsService: WiFi: Supplicant connection re-established
09-09 13:35:56.720  1036  1392 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
09-09 13:35:56.720  1036  1392 D WifiNative-HAL: Setting external_sim to 1
09-09 13:35:56.720  1036  1392 D WifiNative-wlan0: doBoolean: SET external_sim 1
09-09 13:35:56.720  6562  6562 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:35:56.720  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:35:56.720  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:35:56.720  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:35:56.720  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:35:56.720  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:35:56.720  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:35:56.720  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 13:35:56.720  1036  1392 D WifiNative-wlan0: SET external_sim 1: returned true
,09-09 13:35:56.720  1036  1392 I WifiNative-HAL: startHal
09-09 13:35:56.720  1036  1392 D wifi    : setting scan oui 0x956ec580
09-09 13:35:56.720  1945  6912 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
09-09 13:35:56.720  1945  6912 E CtrlSupplicant: Succeed to open control connection
09-09 13:35:56.720  1036  1392 D WifiStateMachine: Setting OUI to DA-A1-19
09-09 13:35:56.720  1036  1392 I WifiNative-HAL: startHal
09-09 13:35:56.720  1945  6912 E CtrlSupplicant: Succeed to open monitor connection
09-09 13:35:56.720  1036  1392 D wifi    : setting scan oui 0x956ec580
09-09 13:35:56.721  1036  1392 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
09-09 13:35:56.721  1945  6912 D WfdsMonitor: Supplicant connection established
09-09 13:35:56.721  1945  2280 D WfdsService: Connected to the supplicant for wfds
09-09 13:35:56.721  1036  1392 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
09-09 13:35:56.721  1036  1392 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
09-09 13:35:56.721  6900  6900 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
09-09 13:35:56.721  1036  1392 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
09-09 13:35:56.722  1036  1392 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-09 13:35:56.722  6562  6562 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 13:35:56.722  6900  6900 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-09 13:35:56.722  6804  6804 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 13:35:56.722  1036  1392 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-09 13:35:56.722  6851  6911 V FormManager: Network unavailable.
09-09 13:35:56.722  1036  1392 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
09-09 13:35:56.722  6900  6900 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
09-09 13:35:56.723  1036  1392 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
09-09 13:35:56.723  1036  1392 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-09 13:35:56.723  6900  6900 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-09 13:35:56.723  1036  1392 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-09 13:35:56.723  1036  1392 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-09 13:35:56.723  6900  6900 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-09 13:35:56.724  1036  1392 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-09 13:35:56.724  1036  1392 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
09-09 13:35:56.724  6900  6900 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
09-09 13:35:56.725  1036  1392 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
09-09 13:35:56.725  1036  1392 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-09 13:35:56.725  6900  6900 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-09 13:35:56.725  1036  1392 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-09 13:35:56.726  1036  1392 E WifiNative: : [129,427,038 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
09-09 13:35:56.726  1036  1392 D WifiNative-wlan0: doBoolean: RECONNECT
09-09 13:35:56.726  1036  1392 D WifiNative-wlan0: RECONNECT: returned true
09-09 13:35:56.726  1036  1392 D WifiNative-wlan0: doString: [STATUS]
09-09 13:35:56.727  6851  6911 V FormManager: Network unavailable.
09-09 13:35:56.727  1036  6908 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
09-09 13:35:56.727  1036  6908 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
09-09 13:35:56.727  1036  1392 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-09, 13:35:56.727  1036  1392 D WifiNative-wlan0: doBoolean: SET ps 1
09-09 13:35:56.728  1036  1392 D WifiNative-wlan0: SET ps 1: returned true
09-09 13:35:56.728  1036  1389 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:35:56.729   311   893 D CommandListener: Setting iface cfg
09-09 13:35:56.729   311   893 D CommandListener: Trying to bring up p2p0
09-09 13:35:56.730  1036  1389 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-09 13:35:56.730  1036  1389 D LGWifiP2pService: P2pEnablingState
09-09 13:35:56.730  1036  1389 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:35:56.730  1036  1389 D LGWifiP2pService: P2p socket connection successful
09-09 13:35:56.730  1036  1389 D LGWifiP2pService: P2pEnabledState
,09-09 13:35:56.731  1036  1389 D LGWifiP2pService: sending p2p connection changed broadcast
09-09 13:35:56.732  1036  1389 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
09-09 13:35:56.732  1036  1389 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
09-09 13:35:56.732  1945  1945 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
09-09 13:35:56.733  1945  1945 D WfdsService: WifiP2pState is changed : true
09-09 13:35:56.733  1036  1389 D WifiNative-p2p0: doBoolean: SET device_name G3
09-09 13:35:56.733  1945  2280 D WfdsService: Receive the WFDS_ENABLE Method
09-09 13:35:56.733  1945  2280 D WfdsService: Set the WFDS Monitor: true
09-09 13:35:56.733  1945  2280 D WfdsService: Connected to the supplicant for wfds
09-09 13:35:56.733  1945  2280 D WfdsJNI : doCommand: WFDS_SET TRUE
09-09 13:35:56.733  6900  6900 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
09-09 13:35:56.733  1945  2280 D WfdsService: selectPreferredScanChannel [36]
09-09 13:35:56.733  1945  2280 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
09-09 13:35:56.733  1036  1389 D WifiNative-p2p0: SET device_name G3: returned true
09-09 13:35:56.733  1036  1389 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
09-09 13:35:56.733  1036  1389 D LGWifiP2pService: before postfix = G3
09-09 13:35:56.733  1036  1389 D WifiServerServiceExt: postfix byte check : 2
09-09 13:35:56.733  1036  1389 D LGWifiP2pService: after postfix = G3
09-09 13:35:56.733  1036  1036 D WifiScanningService: SCAN_AVAILABLE : 3
09-09 13:35:56.733  1036  1389 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
09-09 13:35:56.733  1036  1036 D RttService: SCAN_AVAILABLE : 3
09-09 13:35:56.734  1036  1559 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:35:56.734  1036  1559 I WifiNative-HAL: startHal
09-09 13:35:56.734  1036  1560 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:35:56.734  1036  1389 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
09-09 13:35:56.734  1036  1389 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
09-09 13:35:56.734  1036  1559 D wifi    : getting scan capabilities on interface[1] = 0x956ec580
09-09 13:35:56.734  1036  1559 D wifi    : failed to get capabilities : -3
09-09 13:35:56.734  1036  1559 E WifiScanningService: could not get scan capabilities
09-09 13:35:56.735  1036  1389 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
09-09 13:35:56.735  1036  1389 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
09-09 13:35:56.735  4328  4328 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-09 13:35:56.735  1036  1389 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
09-09 13:35:56.735  1036  1389 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
09-09 13:35:56.735  4328  4328 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-09 13:35:56.735  1945  1945 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
09-09 13:35:56.736  1036  1389 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
09-09 13:35:56.736  1036  1389 D WifiNative-HAL: p2pGetDeviceAddress
09-09 13:35:56.736  1945  1945 D WfdsService: isConnected: false
09-09 13:35:56.736  1036  1389 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
09-09 13:35:56.736  1036  1389 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
09-09 13:35:56.736  1036  1389 D WifiNative-p2p0: doBoolean: P2P_FLUSH
09-09 13:35:56.737  1036  1389 D WifiNative-p2p0: P2P_FLUSH: returned true
09-09 13:35:56.737  1036  1389 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
09-09 13:35:56.737  1036  1392 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_M,ODE 1 0
09-09 13:35:56.738  1036  1389 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
09-09 13:35:56.738  1036  1389 D WifiNative-p2p0: doString: [LIST_NETWORKS]
09-09 13:35:56.738  1036  1392 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
09-09 13:35:56.738  1036  1389 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
09-09 13:35:56.738  1036  1389 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
09-09 13:35:56.738  1036  1392 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
09-09 13:35:56.739  1036  1392 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
09-09 13:35:56.739  1036  1392 E WifiStateMachine:  DisconnectedState what:132106 1 0
09-09 13:35:56.739  1945  1945 I WfdStateTracker: handleP2pThisDeviceChanged
09-09 13:35:56.739  1945  1945 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
09-09 13:35:56.739  1945  1945 D WfdsService: Update P2p Interface State: 3
09-09 13:35:56.739  1036  1392 E WifiStateMachine:  ConnectModeState what:132106 1 0
09-09 13:35:56.740  1036  1392 E WifiStateMachine:  DriverStartedState what:132106 1 0
09-09 13:35:56.740  1036  1392 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
09-09 13:35:56.740  4328  4328 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-09 13:35:56.742  4328  4328 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-09 13:35:56.747  6900  6900 E wpa_supplicant: nWIFIDualbandAPConnection: 1
09-09 13:35:56.747  6652  6652 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-09 13:35:56.748  6652  6652 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
09-09 13:35:56.748  1036  1389 D WifiNative-p2p0: SAVE_CONFIG: returned true
09-09 13:35:56.748  1036  1389 D LGWifiP2pService: sending p2p persistent groups changed broadcast
09-09 13:35:56.748  1036  1389 D LGWifiP2pService: InactiveState
09-09 13:35:56.748  1036  1389 D LGWifiP2pService: InactiveState{ when=-10ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:35:56.748  1036  1389 D LGWifiP2pService: P2pEnabledState{ when=-10ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:35:56.748  1036  1389 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
09-09 13:35:56.748  6900  6900 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-09 13:35:56.749  1036  1392 E WifiStateMachine:  DisconnectedState what:132096 -100 0
09-09 13:35:56.749  1036  1392 E WifiStateMachine:  ConnectModeState what:132096 -100 0
09-09 13:35:56.750  6900  6900 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-09 13:35:56.750  6900  6900 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-09 13:35:56.750  6900  6900 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 13:35:56.751  6900  6900 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 13:35:56.751  1036  6908 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-09 13:35:56.752  1036  6908 E WifiMonitor: WifiMonitor:p2p0 cnt=24 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-09 13:35:56.752  1036  6908 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-09 13:35:56.752  1036  6908 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-09 13:35:56.752  1036  6908 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-09 13:35:56.752  1036  6908 E WifiMonitor: WifiMonitor:p2p0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 13:35:56.752  1036  6908 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 13:35:56.752  1036  6908 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 13:35:56.752  1036  6908 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-09 13:35:56.752  6652  6652 V [BNRBootReceiver]: Boot Receiver Return
09-09 13:35:56.752  1036  6908 E WifiMonitor: WifiMonitor:p2p0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 13:35:56.752  1036  6908 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 13:35:56.752  1036  6908 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 13:35:56.752  1945  6912 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-09 13:35:56.753  1945  6912 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-09 13:35:56.753  1945  6912 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-09 13:35:56.753  4328  6913 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-09 13:35:56.753  1036  1389 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
,09-09 13:35:56.753  1036  1389 D LGWifiP2pService: InactiveState{ when=-5ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:35:56.753  1036  1389 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:35:56.753  1036  1389 D LGWifiP2pService: DefaultState{ when=-6ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:35:56.753  1036  1389 D LGWifiP2pService: InactiveState{ when=-6ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:35:56.753  1036  1389 D LGWifiP2pService: P2pEnabledState{ when=-6ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:35:56.753  1036  1389 D LGWifiP2pService: DefaultState{ when=-6ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:35:56.753  1036  1389 D LGWifiP2pService: InactiveState{ when=-6ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:35:56.753  1036  1389 D LGWifiP2pService: P2pEnabledState{ when=-6ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:35:56.753  1036  1389 D LGWifiP2pService: DefaultState{ when=-6ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:35:56.754  1036  1389 D LGWifiP2pService: InactiveState{ when=-6ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:35:56.754  1036  1389 D LGWifiP2pService: P2pEnabledState{ when=-6ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:35:56.754  1036  1389 D LGWifiP2pService: DefaultState{ when=-6ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:35:56.754  1945  2280 W WfdsService: DefaultState - msg [9441285] is not handled
09-09 13:35:56.754  1036  1036 E WifiServerServiceExt: No p2p device connected
09-09 13:35:56.754  1036  1392 E WifiStateMachine:  DriverStartedState what:132096 -100 0
09-09 13:35:56.754  1036  1392 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
09-09 13:35:56.754  6900  6900 E wpa_supplicant: disconnect_rssi_lvl: -100
09-09 13:35:56.754  1036  1392 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
09-09 13:35:56.755  1036  1392 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
09-09 13:35:56.755  1036  1392 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
09-09 13:35:56.755  1036  1392 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
09-09 13:35:56.756  4328  6915 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-09 13:35:56.756  4328  6915 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-09 13:35:56.756  6900  6900 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-09 13:35:56.757  6900  6900 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-09 13:35:56.757  6900  6900 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-09 13:35:56.757  6900  6900 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 13:35:56.758  6900  6900 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 13:35:56.759  1945  6912 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-09 13:35:56.759  1945  6912 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-09 13:35:56.759  1036  6908 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-09 13:35:56.759  1036  6908 E WifiMonitor: WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-09 13:35:56.759  1036  6908 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-09 13:35:56.759  1036  6908 E WifiMonitor: ha,ndleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-09 13:35:56.759  1036  6908 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-09 13:35:56.759  1036  6908 E WifiMonitor: WifiMonitor:p2p0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 13:35:56.759  1036  6908 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 13:35:56.759  1036  6908 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 13:35:56.759  1036  6908 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-09 13:35:56.759  1036  6908 E WifiMonitor: WifiMonitor:p2p0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 13:35:56.759  1036  6908 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 13:35:56.759  1036  6908 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 13:35:56.760  1036  1392 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
09-09 13:35:56.760  1036  1392 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
09-09 13:35:56.760  1036  1392 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
09-09 13:35:56.761  1036  1392 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
09-09 13:35:56.761  1036  1392 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
09-09 13:35:56.761  6900  6900 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
09-09 13:35:56.761  6900  6900 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-09 13:35:56.762  1036  6908 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
09-09 13:35:56.762  1036  6908 E WifiMonitor: WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-09 13:35:56.762  1036  6908 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-09 13:35:56.762  1036  6908 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-09 13:35:56.762  1036  1389 D LGWifiP2pService: InactiveState{ when=-3ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:35:56.762  1036  1392 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
09-09 13:35:56.762  1036  1392 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
09-09 13:35:56.763  1036  1392 D WifiNative-wlan0: BSS_FLUSH 0: returned true
09-09 13:35:56.763  1036  1389 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:35:56.763  1036  1392 D WifiNative-wlan0: doBoolean: SCAN
09-09 13:35:56.763  1036  1392 D WifiNative-wlan0: SCAN: returned false
09-09 13:35:56.764  1036  1392 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=129465  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-09 13:35:56.764  1036  1392 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=129466  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-09 13:35:56.765  1036  1392 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-09 13:35:56.765  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 13:35:56.765  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 13:35:56.765  1036  1392 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-09 13:35:56.765  1036  1392 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-09 13:35:56.766  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:35:56.766  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:35:56.766  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-09 13:35:56.766  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 13:35:56.766  1036  1392 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-09 13:35:56.767  1036  1392 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
,09-09 13:35:56.768  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-09 13:35:56.768  1036  1036 D WifiServerServiceExt: setSupplicantStateSCANNING
09-09 13:35:56.768  6373  6373 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-09 13:35:56.774  6804  6804 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-09 13:35:56.777  6804  6804 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 13:35:56.781  6825  6825 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-09 13:35:56.781  6825  6825 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-09 13:35:56.782  6825  6825 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-09 13:35:56.858  6670  6670 I UEI.SmartControl: Supports setup maps: true
,09-09 13:35:56.862  6670  6670 D UEI.SmartControl: QS start statue = true Error code = 0
,09-09 13:35:56.862  6670  6670 I UEI.SmartControl: QS version = v2.7.10.1_RC1
,09-09 13:35:56.862  6670  6670 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
09-09 13:35:56.862  6670  6670 I UEI.SmartControl: ### init IR Blaster...
09-09 13:35:56.866  6670  6670 D serial_port: Configuring serial port
09-09 13:35:56.866  6670  6670 E UEI.SmartControl: UEIBLaster setting for 616
09-09 13:35:56.867  6670  6670 I UEI.SmartControl: Setting serial record hearder size = 2
09-09 13:35:56.867  6670  6670 I UEI.SmartControl: configuring settings for MAXQ616
09-09 13:35:56.867  6670  6670 I UEI.SmartControl: Get version...
09-09 13:35:56.885  6670  6916 D UEI.SmartControl: serial port data available: 21
,09-09 13:35:56.911  6670  6670 D UEI.SmartControl: MAXQ616 A2-X4 software.
,09-09 13:35:56.911  6670  6670 I UEI.SmartControl: IR Blaster version: 256702256704300002
,09-09 13:35:56.911  6670  6670 I UEI.SmartControl: QS saving settings...
09-09 13:35:56.913  6670  6670 D UEI.SmartControl: IR Blaster version: 25672567
,09-09 13:35:56.930  6670  6916 D UEI.SmartControl: serial port data available: 4
,09-09 13:35:56.963  6670  6919 I UEI.SmartControl: Device manager: loading config....
,09-09 13:35:56.965  6670  6919 D UEI.SmartControl: ----------- loading internal config...
09-09 13:35:56.966  6670  6670 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
09-09 13:35:56.970  6670  6670 E UEI.SmartControl: Services init done
09-09 13:35:56.970  6670  6670 D UEI.SmartControl: QS Service init finished
09-09 13:35:56.972  6670  6670 D UEI.SmartControl: QS Service version name: 2.1.91
09-09 13:35:56.972  6670  6670 D UEI.SmartControl: QS Service version code: 201091
09-09 13:35:56.973  6670  6670 D UEI.SmartControl: Service requested: Control
09-09 13:35:56.980  6670  6919 E UEI.SmartControl: Loading SETTINGS...
09-09 13:35:56.984  6670  6670 D UEI.SmartControl: Request IControl service: devices are loaded...
,09-09 13:35:56.990  6670  6670 D UEI.SmartControl: Internal service binding...
09-09 13:35:56.990  6825  6825 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
09-09 13:35:56.991  6670  6919 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
09-09 13:35:56.992  6670  6686 I UEI.SmartControl: ------ IControl API: 11
09-09 13:35:56.992  6670  6686 D UEI.SmartControl: File observer start...
09-09 13:35:56.993  6670  6686 E UEI.SmartControl: IR Port is disabled: false
09-09 13:35:56.993  6670  6686 D UEI.SmartControl: Starting file observer...
09-09 13:35:56.995  6670  6686 I UEI.SmartControl: Registering callback...
,09-09 13:35:56.997  6670  6685 I UEI.SmartControl: ------ IControl API: 19
09-09 13:35:56.998  6670  6685 I UEI.SmartControl: Registering Services Ready callback...
09-09 13:35:56.998  6670  6685 I UEI.SmartControl: Notify client services are ready...
09-09 13:35:56.999  6825  6841 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
09-09 13:35:57.001  6825  6894 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
09-09 13:35:57.001  6825  6894 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
09-09 13:35:57.001  6670  6918 I UEI.SmartControl: Notify AllClients services are ready: 0
09-09 13:35:57.002  6670  6918 D UEI.SmartControl: -----service ready thread exits
09-09 13:35:57.002  6825  6840 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
09-09 13:35:57.002  6825  6825 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
09-09 13:35:57.003  6825  6894 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
09-09 13:35:57.003  6825  6894 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
09-09 13:35:57.004  6825  6825 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
09-09 13:35:57.004  6670  6686 I UEI.SmartControl: ------ IControl API: 8
09-09 13:35:57.008  6825  6825 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
09-09 13:35:57.009  6825  6825 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
09-09 13:35:57.010  6825  6825 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
,09-09 13:35:57.011  6825  6825 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
09-09 13:35:57.013  6825  6825 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
09-09 13:35:57.014  6825  6825 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
09-09 13:35:57.016  6825  6825 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
09-09 13:35:57.019  6825  6825 D QRemote : [RemoteControlManager.java:327:handleMessage()] oooooo 140510:retrieveDevices already complete. Do nothing
09-09 13:35:57.020  6825  6825 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
09-09 13:35:57.020  6825  6825 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
09-09 13:35:57.022  6825  6825 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-09 13:35:57.022  6825  6825 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
,09-09 13:35:57.024  6825  6825 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
09-09 13:35:57.025  6825  6825 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
09-09 13:35:57.025  6825  6825 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
09-09 13:35:57.026  6825  6825 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1473420957026]
09-09 13:35:57.028  6825  6825 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
09-09 13:35:57.032  1036  1616 I ActivityManager: Killing 5943:com.lge.appbox.client/u0a11 (adj 15): empty #17
09-09 13:35:57.050  6562  6617 D BluetoothAdapter: enable(): BT is already enabled..!
,09-09 13:35:57.069  6825  6921 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,09-09 13:35:57.078  1036  2035 W libprocessgroup: failed to open /acct/uid_10011/pid_5943/cgroup.procs: No such file or directory
09-09 13:35:57.091  6825  6825 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,09-09 13:35:57.092  6825  6825 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-09 13:35:57.093  6825  6825 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
09-09 13:35:57.093  6825  6825 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
09-09 13:35:57.094  6825  6825 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
09-09 13:35:57.095  6825  6825 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
09-09 13:35:57.095  6825  6825 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
09-09 13:35:57.110  6825  6825 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,09-09 13:35:57.223  1036  6908 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
,09-09 13:35:57.223  6900  6900 E wpa_supplicant: USIM:  scard_init function
,09-09 13:35:57.223  1036  6908 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
09-09 13:35:57.224  1036  6908 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
09-09 13:35:57.224  1036  6908 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: WPS-AP-AVAILABLE 
09-09 13:35:57.224  1036  6908 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
09-09 13:35:57.224  6900  6900 I wpa_supplicant: Trying to associate with SSID 'NG700'
,09-09 13:35:57.225  1036  1392 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
09-09 13:35:57.226  1036  6908 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
09-09 13:35:57.226  1036  6908 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
09-09 13:35:57.227  1036  1392 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
09-09 13:35:57.228  1036  1392 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
09-09 13:35:57.230  1036  1392 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
09-09 13:35:57.230  1036  1392 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
,09-09 13:35:57.250  6804  6804 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,09-09 13:35:57.255  1036  1392 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=129957  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
09-09 13:35:57.260  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:35:57.261  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:35:57.261  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-09 13:35:57.261  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 13:35:57.262  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 13:35:57.262  6804  6804 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
09-09 13:35:57.265  1036  1392 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=129966  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
09-09 13:35:57.265  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:35:57.265  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:35:57.265  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-09 13:35:57.266  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 13:35:57.271  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 13:35:57.271  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-09 13:35:57.274  6373  6373 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-09 13:35:57.274  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 13:35:57.278  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-09 13:35:57.278  1036  1036 D WifiServerServiceExt: setSupplicantStateASSOCIATING
09-09 13:35:57.284  6804  6804 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 13:35:57.291  6804  6804 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 13:35:57.297  6825  6825 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-09 13:35:57.298  6825  6825 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-09 13:35:57.299  6825  6825 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-09 13:35:57.302  6373  6373 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-09 13:35:57.310  6804  6804 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 13:35:57.317  6804  6804 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-09 13:35:57.323  6825  6825 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-09 13:35:57.323  6825  6825 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 13:35:57.324  6825  6825 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-09 13:35:57.344  1036  6908 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
09-09 13:35:57.344  6900  6900 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
09-09 13:35:57.344  1036  6908 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
,09-09 13:35:57.344  1036  6908 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
09-09 13:35:57.344  1036  6908 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: Associated with f4:f2:6d:22:99:3e
09-09 13:35:57.345  1036  1112 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-09 13:35:57.345  1036  1392 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=130046  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-09 13:35:57.345  1036  1392 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=130047  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-09 13:35:57.346  1036  1392 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=130047
09-09 13:35:57.347  1036  6908 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-09 13:35:57.347  1036  6908 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-09 13:35:57.348  1036  1392 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=130049
09-09 13:35:57.348  1036  1392 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=130050
09-09 13:35:57.349  6804  6804 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-09 13:35:57.349  1036  1392 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=130051
09-09 13:35:57.349  6804  6804 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-09 13:35:57.350  6804  6804 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-09 13:35:57.350  6804  6804 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-09 13:35:57.350  1036  1392 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=130052
09-09 13:35:57.350  6804  6804 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-09 13:35:57.352  1036  1392 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
09-09 13:35:57.352  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-09 13:35:57.352  1036  1036 D WifiServerServiceExt: setSupplicantStateASSOCIATED
09-09 13:35:57.353  1036  1392 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
09-09 13:35:57.353  6804  6804 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-09 13:35:57.353  6804  6804 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
09-09 13:35:57.353  6804  6804 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-09 13:35:57.353  6804  6804 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-09 13:35:57.353  6804  6804 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-09 13:35:57.354  6804  6804 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
09-09 13:35:57.354  1036  1392 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
09-09 13:35:57.354  6804  6804 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-09 13:35:57.354  1036  1392 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
,09-09 13:35:57.355  1036  1392 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-09 13:35:57.357  1036  1392 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=130058  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
09-09 13:35:57.359  1036  6908 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-09 13:35:57.359  1036  6908 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-09 13:35:57.360  6900  6900 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-09 13:35:57.360  6900  6900 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-09 13:35:57.360  1036  6908 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
09-09 13:35:57.360  1036  6908 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-09 13:35:57.360  1036  6908 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-09 13:35:57.361  1036  6908 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
09-09 13:35:57.361  1036  6908 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-09 13:35:57.361  1036  6908 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-09 13:35:57.364  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 13:35:57.364  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 13:35:57.364  1036  6908 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-09 13:35:57.364  1036  6908 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-09 13:35:57.365  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 13:35:57.369  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:35:57.370  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:35:57.370  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-09 13:35:57.375  6373  6373 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-09 13:35:57.376  1036  1392 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=130077  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
,09-09 13:35:57.377  1036  1392 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=130078  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-09 13:35:57.379  1036  1392 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=130080  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-09 13:35:57.380  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:35:57.380  1036  1392 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=130082
09-09 13:35:57.380  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:35:57.380  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
09-09 13:35:57.381  1036  1392 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=130082
09-09 13:35:57.382  1036  1392 D WifiNative-wlan0: doString: [STATUS]
09-09 13:35:57.382  1036  6908 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-09 13:35:57.382  1036  6908 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-09 13:35:57.383  1036  1392 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-09 13:35:57.385  1036  1392 I WifiServiceExtension: setVHTCapabilityType  : false
09-09 13:35:57.389  6804  6804 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-09 13:35:57.389  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 13:35:57.389  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-09 13:35:57.392  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 13:35:57.393  1036  1392 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
,09-09 13:35:57.393  1036  1392 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
09-09 13:35:57.396  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:35:57.396  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:35:57.396  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-09 13:35:57.398  6804  6804 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 13:35:57.399  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:35:57.399  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:35:57.399  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-09 13:35:57.405  6825  6825 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-09 13:35:57.405  6825  6825 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 13:35:57.405  6825  6825 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-09 13:35:57.409  6373  6373 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-09 13:35:57.412  1036  1392 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
09-09 13:35:57.412  1036  1392 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-09 13:35:57.412  1036  1392 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-09 13:35:57.413  1036  1435 D ConnectivityService: Got NetworkAgent Messenger
09-09 13:35:57.413  1036  1435 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
09-09 13:35:57.413  1036  1392 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-09 13:35:57.413  1036  1435 D ConnectivityService: NetworkAgent connected
09-09 13:35:57.413  1036  1392 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-09 13:35:57.414  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 13:35:57.414  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 13:35:57.415  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 13:35:57.416  6804  6804 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 13:35:57.418  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 13:35:57.418  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 13:35:57.418  1036  1392 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-09 13:35:57.418  1036  1392 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-09 13:35:57.418  1036  1392 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-09 13:35:57.419  1036  1392 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-09 13:35:57.419  1036  1392 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-09 13:35:57.420  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 13:35:57.422  1036  1392 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-09 13:35:57.424   311   893 D CommandListener: Setting iface cfg
09-09 13:35:57.424  6804  6804 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 13:35:57.428  1036  1392 E WifiStateMachine: Start Dhcp Watchdog 2
,09-09 13:35:57.428  1036  6924 D DhcpStateMachine: StoppedState
09-09 13:35:57.428  1036  6924 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:35:57.428  1036  6924 D DhcpStateMachine: WaitBeforeStartState
09-09 13:35:57.428  1036  1392 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=130130  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
,09-09 13:35:57.429  1036  1392 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=130131  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-09 13:35:57.430  1036  1392 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=130131  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-09 13:35:57.431  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-09 13:35:57.431  1036  1036 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
09-09 13:35:57.431  6825  6825 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-09 13:35:57.432  6825  6825 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 13:35:57.432  6825  6825 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-09 13:35:57.432  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
,09-09 13:35:57.432  1036  1036 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
09-09 13:35:57.433  1036  1392 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=130134  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-09 13:35:57.433  1036  1392 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=130135  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-09 13:35:57.434  1036  1392 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=130135  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-09 13:35:57.435  1036  1392 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:84316] from screen [on:0 period:247174907] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
09-09 13:35:57.436  1036  1392 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:247174908] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
09-09 13:35:57.436  1036  1392 D WifiNative-wlan0: doString: [SIGNAL_POLL]
09-09 13:35:57.437  6373  6373 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-09 13:35:57.440  1036  1435 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
09-09 13:35:57.440  1036  1392 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 13:35:57.440  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 13:35:57.440  1036  1392 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 13:35:57.441  1036  1392 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 13:35:57.441  1036  1392 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 13:35:57.441  1036  1392 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 13:35:57.442  1036  1392 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 13:35:57.442  1036  1435 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
09-09 13:35:57.442  1036  1392 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=122,0,0
09-09 13:35:57.443  1036  1392 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=122,0,0
09-09 13:35:57.443  1036  1392 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
09-09 13:35:57.443  6900  6900 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
09-09 13:35:57.444  1036  1392 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
09-09 13:35:57.444  1036  1392 D WifiNative-wlan0: doBoolean: SET ps 0
,09-09 13:35:57.444  1036  1392 D WifiNative-wlan0: SET ps 0: returned true
,09-09 13:35:57.444  1036  1392 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
09-09 13:35:57.445  6900  6900 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
09-09 13:35:57.445  1036  1392 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
09-09 13:35:57.446  1036  1389 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1589446 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:35:57.446  1036  1389 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1589446 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:35:57.446  1036  6924 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:35:57.446  1036  6924 D DhcpStateMachine: DHCP Start wake lock is acquired.
09-09 13:35:57.447  6804  6804 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-09 13:35:57.447  1036  1392 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
09-09 13:35:57.447  1036  1392 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-09 13:35:57.447  1036  1392 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-09 13:35:57.448   311   893 D CommandListener: Setting iface cfg
09-09 13:35:57.448   311   893 D CommandListener: Trying to bring up wlan0
09-09 13:35:57.449  1036  1392 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
09-09 13:35:57.450  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-09 13:35:57.450  1036  1036 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-09 13:35:57.451  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
,09-09 13:35:57.451  1036  1036 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-09 13:35:57.452  1036  1392 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 13:35:57.452  1036  1392 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 13:35:57.452  1036  1392 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 13:35:57.453  1036  1392 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 13:35:57.454  1036  1392 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 13:35:57.454  6804  6804 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-09 13:35:57.454  1036  1392 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 13:35:57.454  1036  1435 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
09-09 13:35:57.455  1036  1392 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
09-09 13:35:57.455  1036  1392 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
09-09 13:35:57.455  1036  1392 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-09 13:35:57.455  6900  6900 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-09 13:35:57.455  1036  1389 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:35:57.455  1036  1389 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:35:57.455  1036  1392 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
,09-09 13:35:57.456  1036  1392 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
09-09 13:35:57.456  6900  6900 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
09-09 13:35:57.456  1036  1392 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
09-09 13:35:57.456  1036  1392 D WifiNative-wlan0: doBoolean: SET ps 1
09-09 13:35:57.463  6825  6825 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-09 13:35:57.463  6825  6825 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 13:35:57.464  6825  6825 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-09 13:35:57.466  6373  6373 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-09 13:35:57.472  1036  1392 D WifiNative-wlan0: SET ps 1: returned true
09-09 13:35:57.473  1036  1435 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
09-09 13:35:57.473  1036  1392 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
,09-09 13:35:57.473  1036  1392 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-09 13:35:57.473  1036  1392 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
09-09 13:35:57.474  6804  6804 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-09 13:35:57.475  1036  1435 D ConnectivityService: ignoring duplicate network state non-change
09-09 13:35:57.477  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 13:35:57.477  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 13:35:57.478  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 13:35:57.480  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:35:57.480  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:35:57.481  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-09 13:35:57.482  1036  1435 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-09 13:35:57.482  1036  1435 D ConnectivityService: Adding iface wlan0 to network 101
09-09 13:35:57.483  1036  1392 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-09 13:35:57.484  6804  6804 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-09 13:35:57.490  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:35:57.490  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:35:57.490  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-09 13:35:57.492  1036  1036 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-09 13:35:57.495  1945  1945 V WfdStateTracker: handleWifiStateChangedEvent: 1
09-09 13:35:57.497  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:35:57.497  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:35:57.497  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-09 13:35:57.499  1036  1036 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-09 13:35:57.502  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 13:35:57.502  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 13:35:57.503  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 13:35:57.505  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:35:57.505  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:35:57.505  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
,09-09 13:35:57.507  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 13:35:57.507  1605  1605 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-09 13:35:57.508  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 13:35:57.513  1036  1435 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-09 13:35:57.514  1036  1435 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,09-09 13:35:57.514  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 13:35:57.514  1605  1605 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-09 13:35:57.515  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 13:35:57.515  1036  1435 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
09-09 13:35:57.516   311   893 E Netd    : netlink response contains error (File exists)
09-09 13:35:57.516  1036  1435 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
09-09 13:35:57.517  6825  6825 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-09 13:35:57.517  1036  1435 D ConnectivityService: addLocalRoutetoDefaultNetwork
09-09 13:35:57.517  1036  1435 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
09-09 13:35:57.518  1036  1435 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
09-09 13:35:57.518  6825  6825 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 13:35:57.518  6825  6825 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-09 13:35:57.519  1036  1435 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-09 13:35:57.519  1036  1435 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-09 13:35:57.519  1036  1435 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
09-09 13:35:57.519  1036  1435 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
09-09 13:35:57.519  1036  1435 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 13:35:57.519  1036  1435 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 13:35:57.519  1036  6923 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:35:57.519  1036  6923 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
09-09 13:35:57.519  1036  1435 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-09 13:35:57.519  1036  1435 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:35:57.519  1036  6923 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:35:57.520  1036  1435 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
09-09 13:35:57.520  1036  6923 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
09-09 13:35:57.520  1036  1435 D ConnectivityService: currentScore = 0, newScore = 20
09-09 13:35:57.520  1036  1435 D ConnectivityService:    accepting network in place of null
09-09 13:35:57.520  1036  1435 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-09 13:35:57.524  1857  1857 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:35:57.525  1857  1857 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-09 13:35:57.525  1036  1392 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:35:57.525  1036  1392 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 13:35:57.525   311  6928 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
09-09 13:35:57.526  1036  1435 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
09-09 13:35:57.526  1036  1435 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-09 13:35:57.527  1036  1435 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-09 13:35:57.531  1036  1435 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-09 13:35:57.531  1036  1435 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
09-09 13:35:57.531  1036  1435 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,09-09 13:35:57.532  1036  1036 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
09-09 13:35:57.532  1036  1435 D ConnectivityService: validation of new default Network = false
09-09 13:35:57.532  1036  1435 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
09-09 13:35:57.533  1036  1435 D DSQN    : enableDataServiceNotify 
09-09 13:35:57.533  1036  1435 D DSQN    : start dsqn bin
09-09 13:35:57.534  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-09 13:35:57.534  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-09 13:35:57.534  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-09 13:35:57.538  6373  6373 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-09 13:35:57.531  6929  6929 W dsqn    : type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6841 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-09 13:35:57.531  6929  6929 W dsqn    : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6841 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-09 13:35:57.540  1036  1435 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
09-09 13:35:57.540  1036  1435 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:35:57.540  1036  1435 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 13:35:57.540  1036  1435 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 13:35:57.542  1605  2090 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-09 13:35:57.553  6929  6929 E DSQN    : DSQN ssw
,09-09 13:35:57.554  6804  6804 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-09 13:35:57.559  1036  1388 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
09-09 13:35:57.563  6804  6804 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 13:35:57.566  1605  1605 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,09-09 13:35:57.567  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 13:35:57.568  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 13:35:57.570  6825  6825 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-09 13:35:57.570  6825  6825 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 13:35:57.573  6825  6825 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-09 13:35:57.577  6373  6373 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-09 13:35:57.583  6804  6804 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-09 13:35:57.587  6804  6804 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 13:35:57.592   311  6928 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,09-09 13:35:57.592  6825  6825 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-09 13:35:57.593  6825  6825 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 13:35:57.593  6825  6825 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-09 13:35:57.596  6373  6373 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-09 13:35:57.601  6783  6783 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
09-09 13:35:57.606  6783  6783 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,09-09 13:35:57.610  6804  6804 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 13:35:57.619  6804  6804 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-09 13:35:57.630  6825  6825 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-09 13:35:57.631  6825  6825 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 13:35:57.632  6825  6825 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
09-09 13:35:57.633  6825  6825 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-09 13:35:57.634  6825  6825 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,09-09 13:35:57.637   311  6928 D libc-netbsd: res_queryN name = clients3.google.com succeed
,09-09 13:35:57.643  6373  6373 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-09 13:35:57.648  1036  6924 D DhcpStateMachine: DHCPV4 request on wlan0
09-09 13:35:57.649  6783  6783 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,09-09 13:35:57.650  1036  6924 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
09-09 13:35:57.650  6783  6783 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
09-09 13:35:57.650  1036  6924 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
09-09 13:35:57.655  6804  6804 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-09 13:35:57.651  6933  6933 W dhcpcd  : type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6841 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-09 13:35:57.651  6933  6933 W dhcpcd  : type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6841 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-09 13:35:57.666  6933  6933 I dhcpcd  : version 5.5.6 starting
09-09 13:35:57.667  6804  6804 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 13:35:57.667   311   892 D LGDataListener: argv[0]=dsqncommand
09-09 13:35:57.667   311   892 D LGDataListener: argv[1]=wlan0
09-09 13:35:57.668   311   892 D LGDataListener: argv[2]=1
09-09 13:35:57.668   311   892 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
09-09 13:35:57.668  1036  1110 D DSQN    : DSQM DsqnNotification wlan0  1
09-09 13:35:57.668  1036  1110 D DSQN    : start to monitor internet connection
09-09 13:35:57.668  6933  6933 E dhcpcd  : get_duid: m
09-09 13:35:57.668  6933  6933 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
09-09 13:35:57.668  6933  6933 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
09-09 13:35:57.682  6825  6825 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-09 13:35:57.682  6825  6825 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 13:35:57.685  6825  6825 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,09-09 13:35:57.687  6825  6825 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-09 13:35:57.689  6825  6825 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
09-09 13:35:57.700  1036  6923 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 09 Sep 2016 11:35:57 GMT], X-Android-Received-Millis=[1473420957700], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1473420957667]}
09-09 13:35:57.700  1036  6923 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
09-09 13:35:57.700  1036  6923 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
,09-09 13:35:57.702  1036  1435 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
09-09 13:35:57.702  1036  1435 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
09-09 13:35:57.702  1036  1435 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 13:35:57.703  1036  1435 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 13:35:57.703  1036  1435 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-09 13:35:57.703  1036  1435 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
09-09 13:35:57.703  1036  1435 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
09-09 13:35:57.703  1036  1435 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:35:57.703  1036  1435 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 13:35:57.704  1036  1435 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 13:35:57.706  1036  1435 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:35:57.706  1605  2090 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-09 13:35:57.707  1857  1857 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:35:57.707  1857  1857 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-09 13:35:57.708  1036  1392 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:35:57.708  1036  1392 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 13:35:57.708  1036  1435 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-09 13:35:57.732  1605  1605 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-09 13:35:57.733  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-09 13:35:57.734  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 13:35:57.741  6933  6933 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-09 13:35:57.742  6933  6933 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-09 13:35:57.742  6933  6933 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-09 13:35:57.742  6933  6933 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
09-09 13:35:57.742  6933  6933 D dhcpcd  : wlan0: sending REQUEST (xid 0xbf609ea7), next in 3.85 seconds
09-09 13:35:57.762  6933  6933 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
,09-09 13:35:57.766  6933  6933 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
,09-09 13:35:57.766  6933  6933 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
,09-09 13:35:57.767  6933  6933 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
09-09 13:35:57.767  6933  6933 D dhcpcd  : wlan0: adding default route via 192.168.1.1
09-09 13:35:57.768  6933  6933 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-09 13:35:57.768  6933  6933 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-09 13:35:57.768  6933  6933 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-09 13:35:57.768  6933  6933 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
09-09 13:35:58.188  1036  1435 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:35:58.200  1036  1435 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-09 13:35:58.201  1036  1092 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-09 13:35:58.202  1036  1092 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 13:35:58.204  1036  1112 D Tethering: MasterInitialState.processMessage what=3
,09-09 13:35:58.224  6562  6562 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:35:58.224  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:35:58.224  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:35:58.224  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:35:58.224  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:35:58.224  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:35:58.224  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:35:58.224  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:35:58.228  1036  1112 D Tethering: MasterInitialState.processMessage what=3
09-09 13:35:58.229  6562  6562 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:35:58.231  6373  6373 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
09-09 13:35:58.232  1036  1092 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-09 13:35:58.234  1036  1092 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 13:35:58.236  6562  6562 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:35:58.236  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:35:58.236  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:35:58.236  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:35:58.236  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:35:58.236  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:35:58.236  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:35:58.236  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:35:58.238  6562  6562 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 13:35:58.239  6373  6422 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-09 13:35:58.244  6562  6562 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:35:58.244  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:35:58.244  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:35:58.244  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:35:58.244  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:35:58.244  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:35:58.244  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:35:58.244  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:35:58.246  6562  6562 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 13:35:58.247  5701  5701 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
09-09 13:35:58.250  6562  6562 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:35:58.256  1036  6924 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,09-09 13:35:58.260  1036  6924 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
09-09 13:35:58.260  1036  6924 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-09 13:35:58.260  1036  6924 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
09-09 13:35:58.260  1036  6924 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
09-09 13:35:58.260  1036  6924 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-09 13:35:58.260  1036  6924 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
09-09 13:35:58.260  1036  6924 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
09-09 13:35:58.263  1036  6924 D DhcpStateMachine: RunningState
09-09 13:35:58.264  6562  6562 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:35:58.264  5701  5701 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
09-09 13:35:58.268  6562  6562 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:35:58.285  2180  2180 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:35:58.292   311  6984 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
09-09 13:35:58.293   311  6984 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
09-09 13:35:58.324   311  6984 D libc-netbsd: res_queryN name = mtalk.google.com succeed
,09-09 13:35:58.345  1036  1981 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6985 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,09-09 13:35:58.441  6985  6985 I AppUp4:AppBoxCP: onCreate
,09-09 13:35:58.442  6985  6985 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,09-09 13:35:58.453  6985  6985 I AppUp4:DB:  setFingerPrint start
,09-09 13:35:58.453  6985  6985 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
09-09 13:35:58.462  6985  6985 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
09-09 13:35:58.462  6985  6985 I AppUp4:DB:  SDK version = 21
09-09 13:35:58.462  6985  6985 I AppUp4:DB:  beforefinger == newfinger no write in DB
09-09 13:35:58.465  6985  6985 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
,09-09 13:35:58.467  6985  6985 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-09 13:35:58.467  6985  6985 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-09 13:35:58.470  6985  6985 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
,09-09 13:35:58.470  6985  6985 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-09 13:35:58.482  6985  6985 I AppUp4:CustModeStarterReceiver: onReceive
09-09 13:35:58.539  1036  1435 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-09 13:35:58.552  6985  6985 D LgDataFeature: LgDataFeature() Constructor: none
09-09 13:35:58.552  6985  6985 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-09 13:35:58.567  6985  6985 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1c850217
09-09 13:35:58.568  6985  6985 D AppUp4:CustFacade: isCustomizationCompleted : false
09-09 13:35:58.568  6985  6985 D AppUp4:CustFacade: isPhone : true
,09-09 13:35:58.569  6985  6985 D AppUp4:CustModeStarterReceiver: begin check event
09-09 13:35:58.569  6985  6985 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
09-09 13:35:58.570  6985  6985 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
09-09 13:35:58.571  6985  7004 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
09-09 13:35:58.571  6985  7004 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
09-09 13:35:58.572  6985  7004 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
09-09 13:35:58.574  1036  1981 I ActivityManager: Killing 5966:com.android.contacts/u0a19 (adj 15): empty #17
09-09 13:35:58.609  1036  1944 W libprocessgroup: failed to open /acct/uid_10019/pid_5966/cgroup.procs: No such file or directory
09-09 13:35:58.610  4328  4328 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:35:58.611  4328  4328 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-09 13:35:58.615  4328  4328 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-09 13:35:58.621  4328  4328 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-09 13:35:58.624  2180  7003 D GCM     : Connected
,09-09 13:35:58.629  3489  3489 V DownloadManager: Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
09-09 13:35:58.632  3489  3489 V DownloadManager: DownloadService onCreate
09-09 13:35:58.637  3489  7010 I DownloadManager: in removeSpuriousFiles
09-09 13:35:58.638  3489  7010 V DownloadManager: starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
09-09 13:35:58.645  3489  7010 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@13b7ada on behalf of 3489
,09-09 13:35:58.647  3489  7010 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
09-09 13:35:58.648  3489  7010 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGEIME_5.1.29_release_repacked_ARM_XT9_MYSCRIPT_20160317004155539.apk
09-09 13:35:58.648  3489  7010 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_5.1.24_COM_COM(9012_VDF)_20160401022656759.apk
09-09 13:35:58.648  3489  7010 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
09-09 13:35:58.648  3489  7010 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
09-09 13:35:58.648  3489  7010 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
09-09 13:35:58.648  3489  7010 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
09-09 13:35:58.649  3489  7010 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/ConciergeBoard_4.40.12_COM_COM(VDF)_20160126234417577.apk
09-09 13:35:58.649  3489  7010 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
09-09 13:35:58.649  3489  7010 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
09-09 13:35:58.649  3489  7010 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
09-09 13:35:58.651  3489  7010 I DownloadManager: in trimDatabase
09-09 13:35:58.651  3489  7010 V DownloadManager: starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
09-09 13:35:58.652  3489  7010 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@45deb0b on behalf of 3489
09-09 13:35:58.659  3489  3489 V DownloadManager: DownloadService onStartCommand
09-09 13:35:58.659  3489  7011 V DownloadManager: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,09-09 13:35:58.661  4328  7009 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0,
09-09 13:35:58.663  3489  7011 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@3a666aa6 on behalf of 3489
09-09 13:35:58.665  4328  7013 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-09 13:35:58.665  4328  7013 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-09 13:35:58.665  3489  7011 V DownloadManager: processing inserted download 1
09-09 13:35:58.666  3489  7011 V DownloadManager: processing inserted download 4
,09-09 13:35:58.667  4328  7009 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
09-09 13:35:58.668  2180  7003 D GCM     : Message class com.google.e.a.a.q
09-09 13:35:58.668  3489  7011 V DownloadManager: processing inserted download 7
09-09 13:35:58.669  3489  7011 V DownloadManager: processing inserted download 8
09-09 13:35:58.670  3489  7011 V DownloadManager: processing inserted download 9
09-09 13:35:58.671  3489  7011 V DownloadManager: processing inserted download 10
09-09 13:35:58.673  3489  7011 V DownloadManager: processing inserted download 11
,09-09 13:35:58.674  3489  7011 V DownloadManager: processing inserted download 12
09-09 13:35:58.675  6471  6471 D eas_req : ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
09-09 13:35:58.676  3489  7011 V DownloadManager: processing inserted download 13
09-09 13:35:58.687  3489  7011 V DownloadManager: processing inserted download 14
09-09 13:35:58.687  4328  7009 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
09-09 13:35:58.689  3489  7011 V DownloadManager: processing inserted download 16
,09-09 13:35:58.691  4328  4328 E LGDMClient: [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
09-09 13:35:58.692  4328  4328 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
09-09 13:35:58.692  4328  4328 D LGDMClient: [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
09-09 13:35:58.694  3489  3489 V DownloadManager: DownloadService onDestroy
09-09 13:35:58.694  4328  4328 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [274] : DmConstants.DMAgentState.DMA_STATE_IDLE
09-09 13:35:58.699  4328  4328 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [659] : agentmodeOnOff is OFF. Finish OneDayWiFiCheck
09-09 13:35:58.713  3423  3423 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,09-09 13:35:58.713  3423  3423 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-09 13:35:58.714  3423  3423 I LgeMiscReceiver: networkInfo.isConnected() = false
09-09 13:35:58.726  6471  6471 I HubEmail: JNI_OnLoad()
09-09 13:35:58.726  6471  6471 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-09 13:35:58.726  6471  6471 I HubEmail: registerNatives()
,09-09 13:35:58.726  6471  6471 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-09 13:35:58.726  6471  6471 I HubEmail: registerNativeMethods()
09-09 13:35:58.726  6471  6471 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-09 13:35:58.727  6471  6471 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
09-09 13:35:58.757   311  7025 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
09-09 13:35:58.758   311  7025 D libc-netbsd: res_queryN name = static-avc.lglime.com, class = 1, type = 1
,09-09 13:35:58.776  1036  1944 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7026 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,09-09 13:35:58.781  6471  7022 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-09 13:35:58.927  7026  7026 D LgDataFeature: LgDataFeature() Constructor: none
,09-09 13:35:58.927  7026  7026 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-09 13:35:58.930  7026  7026 D PhoneMonitor: Register our PhoneStateListener
,09-09 13:35:58.947   311  7025 D libc-netbsd: res_queryN name = static-avc.lglime.com succeed
,09-09 13:35:58.952  7026  7026 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-09 13:35:58.953  7026  7026 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,09-09 13:35:58.985  7026  7026 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
09-09 13:35:58.987  7026  7026 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
09-09 13:35:58.988  7026  7026 D TelephonyAutoProfiling: [parse] Load xml
09-09 13:35:58.997  7026  7026 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
09-09 13:35:58.997  7026  7026 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
,09-09 13:35:58.997  7026  7026 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
,09-09 13:35:58.997  7026  7026 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
09-09 13:35:58.997  7026  7026 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
09-09 13:35:58.997  7026  7026 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
09-09 13:35:58.997  7026  7026 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
09-09 13:35:58.997  7026  7026 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
09-09 13:35:58.997  7026  7026 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
09-09 13:35:58.997  7026  7026 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
09-09 13:35:58.997  7026  7026 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
09-09 13:35:58.997  7026  7026 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
09-09 13:35:58.997  7026  7026 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
09-09 13:35:58.997  7026  7026 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
09-09 13:35:58.997  7026  7026 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
09-09 13:35:58.997  7026  7026 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
09-09 13:35:58.997  7026  7026 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
09-09 13:35:59.000  1036  1923 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7046 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-09 13:35:59.006  7026  7026 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,09-09 13:35:59.009  6851  7017 V FormManager: There are no updated forms. The schedule will be deleted.
09-09 13:35:59.019  6851  7017 V FormManager: Alarm would be updated, because LastCheckTime has been updated.
,09-09 13:35:59.023  1821  7059 I CheckinService: active receiver: enabled
,09-09 13:35:59.038  1821  7059 I CheckinService: Preparing to send checkin request
09-09 13:35:59.038  1821  7059 I EventLogService: Accumulating logs since 1473420885160
,09-09 13:35:59.064  1036  1781 I ActivityManager: Killing 5991:com.android.gallery3d/u0a27 (adj 15): empty #17
,09-09 13:35:59.087  1036  1392 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,09-09 13:35:59.088  1036  1392 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-09 13:35:59.088  1036  1392 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-09 13:35:59.088  1036  1392 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,09-09 13:35:59.089  1036  1392 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-09 13:35:59.089  1036  1392 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-09 13:35:59.089  1036  1435 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
09-09 13:35:59.089  1036  1435 D ConnectivityService: identical MTU - not setting
09-09 13:35:59.089  1036  1435 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-09 13:35:59.089  1036  1435 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-09 13:35:59.090  1036  1435 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:35:59.090  1036  1435 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 13:35:59.090  1036  1435 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 13:35:59.091  1605  2090 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
09-09 13:35:59.139  1821  7059 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
09-09 13:35:59.139  1036  1943 W libprocessgroup: failed to open /acct/uid_10027/pid_5991/cgroup.procs: No such file or directory
,09-09 13:35:59.224  1036  1052 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7066 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,09-09 13:35:59.226  1036  1052 I ActivityManager: Killing 6061:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
09-09 13:35:59.308  1036  1923 W libprocessgroup: failed to open /acct/uid_10080/pid_6061/cgroup.procs: No such file or directory
,09-09 13:35:59.426  1036  1578 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7083 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-09 13:35:59.466  1036  1780 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7100 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,09-09 13:35:59.467  1036  1578 I ActivityManager: Killing 6511:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,09-09 13:35:59.573  1036  2036 W libprocessgroup: failed to open /acct/uid_10061/pid_6511/cgroup.procs: No such file or directory
,09-09 13:35:59.608  7100  7100 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
09-09 13:35:59.608  7100  7100 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,09-09 13:35:59.613  7083  7083 I art     : Almond Protected OAT
09-09 13:35:59.641  7100  7100 I MultiDex: VM with version 2.1.0 has multidex support
09-09 13:35:59.641  7100  7100 I MultiDex: install
09-09 13:35:59.641  7100  7100 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,09-09 13:35:59.653  7100  7100 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,09-09 13:35:59.671  7083  7083 D WeatherApplication: removeAccount
,09-09 13:35:59.672  7083  7083 D WeatherApplication: Account.length = 0
09-09 13:35:59.673  7083  7083 E WeatherApplication: OPERATOR:OPEN
09-09 13:35:59.678  7083  7083 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:35:59
09-09 13:35:59.682  7083  7083 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-09 13:35:59.682  7083  7083 D Weather.Utils: 2 : All the weather widget is gone.
09-09 13:35:59.686  7083  7083 D UpdateThreadPoolManager: 2 : This is isUpdating : false
,09-09 13:35:59.689  7083  7083 D WeatherAncestor: connectivity changed - connection : true
09-09 13:35:59.690  7083  7083 D WeatherService: 2 : isServiceAlived():false forecastCache:null
,09-09 13:35:59.704  7083  7083 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-09 13:35:59.704  7083  7083 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-09 13:35:59.704  7083  7083 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
,09-09 13:35:59.725  7083  7083 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-09 13:35:59.726  7083  7083 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:35:59
,09-09 13:35:59.769  1036  1962 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7123 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-09 13:35:59.770  1036  1962 I ActivityManager: Killing 6085:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,09-09 13:35:59.847  1036  1944 W libprocessgroup: failed to open /acct/uid_10097/pid_6085/cgroup.procs: No such file or directory
,09-09 13:35:59.967   280   398 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-09 13:35:59.968   280   398 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
09-09 13:35:59.968   280   398 W Vold    : Returning OperationFailed - no handler for errno 0
,09-09 13:35:59.973  7123  7147 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
09-09 13:35:59.976   280   398 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-09 13:35:59.976   280   398 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
09-09 13:35:59.976   280   398 W Vold    : Returning OperationFailed - no handler for errno 0
,09-09 13:35:59.977  7123  7147 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
09-09 13:35:59.995   280   398 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-09 13:35:59.995   280   398 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
09-09 13:35:59.995   280   398 W Vold    : Returning OperationFailed - no handler for errno 0
,09-09 13:35:59.996  7123  7149 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
09-09 13:36:00.000   280   398 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-09 13:36:00.000   280   398 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
09-09 13:36:00.000   280   398 W Vold    : Returning OperationFailed - no handler for errno 0
09-09 13:36:00.000  7123  7149 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
09-09 13:36:00.039  1605  1605 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-09 13:36:00.039  1605  1605 I KeyguardUpdateMonitor: called onTimeUpdated()
09-09 13:36:00.039  1605  1605 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
09-09 13:36:00.039  1605  1605 I [SystemUI]Clock: called onTimeUpdated()
09-09 13:36:00.040  1605  1605 I LgeClockWidgetControlView: called onTimeUpdated()
09-09 13:36:00.040  1605  1605 I [SystemUI]DateView: called onTimeUpdated()
,09-09 13:36:00.041  1605  1605 I [SystemUI]DateView: called onTimeUpdated()
09-09 13:36:00.041  1605  1605 D KeyguardUpdateMonitor: handleTimeUpdate
09-09 13:36:00.083  7153  7153 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,09-09 13:36:00.130  7153  7153 I dex2oat : dex2oat took 47.361ms (threads: 4)
,09-09 13:36:00.134  1036  1389 D LGWifiP2pService: InactiveState{ when=-3ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:36:00.135  1036  1389 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:36:00.135  1036  1389 D LGWifiP2pService: DefaultState{ when=-3ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:36:00.142  1036  1093 W ProcessCpuTracker: Skipping unknown process pid 7153
09-09 13:36:00.145  7100  7115 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-09 13:36:00.145  7100  7115 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-09 13:36:00.145  7100  7115 I Adreno-EGL: Build Date: 12/12/14 금
09-09 13:36:00.145  7100  7115 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-09 13:36:00.145  7100  7115 I Adreno-EGL: Remote Branch: 
09-09 13:36:00.145  7100  7115 I Adreno-EGL: Local Patches: 
09-09 13:36:00.145  7100  7115 I Adreno-EGL: Reconstruct Branch: 
,09-09 13:36:00.173  7123  7123 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,09-09 13:36:00.178  7123  7123 I LibraryLoader: Loading: webviewchromium
09-09 13:36:00.180  7123  7123 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 2891-2894)
09-09 13:36:00.180  7123  7123 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-09 13:36:00.184  7123  7123 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2656c31e}
,09-09 13:36:00.185  7123  7123 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-09 13:36:00.185  7123  7123 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,09-09 13:36:00.188  1036  1392 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
09-09 13:36:00.189  1036  1392 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
09-09 13:36:00.189  1036  1392 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
09-09 13:36:00.189  1036  1392 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
09-09 13:36:00.190  1036  1392 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
09-09 13:36:00.190  1036  1392 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
09-09 13:36:00.191  7123  7123 I BrowserStartupController: Initializing chromium process, renderers=0
,09-09 13:36:00.192  7123  7123 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-09 13:36:00.201   315  2164 V AudioPolicyService: registerClient() client 0xb558aca0, uid 10093
,09-09 13:36:00.202  7123  7178 W AudioManagerAndroid: Requires BLUETOOTH permission
,09-09 13:36:00.203  7123  7123 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
09-09 13:36:00.204  7123  7123 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
09-09 13:36:00.204  7123  7123 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
09-09 13:36:00.216  7123  7123 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-09 13:36:00.216  7123  7123 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-09 13:36:00.216  7123  7123 I Adreno-EGL: Build Date: 12/12/14 금
09-09 13:36:00.216  7123  7123 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-09 13:36:00.216  7123  7123 I Adreno-EGL: Remote Branch: 
09-09 13:36:00.216  7123  7123 I Adreno-EGL: Local Patches: 
09-09 13:36:00.216  7123  7123 I Adreno-EGL: Reconstruct Branch: 
,09-09 13:36:00.264  7123  7123 I NSApplication: Starting up...
,09-09 13:36:00.310  7100  7115 D LgDataFeature: LgDataFeature() Constructor: none
09-09 13:36:00.310  7100  7115 D LgDataFeature: LgDataFeature() Constructor Done, null
09-09 13:36:00.312  1036  1999 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7191 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,09-09 13:36:00.313  1036  1999 I ActivityManager: Killing 6633:com.lge.eula/1000 (adj 15): empty #17
09-09 13:36:00.431  1036  2036 W libprocessgroup: failed to open /acct/uid_1000/pid_6633/cgroup.procs: No such file or directory
,09-09 13:36:00.432  7100  7115 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-09 13:36:00.432  7100  7115 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-09 13:36:00.432  7100  7115 I Adreno-EGL: Build Date: 12/12/14 금
09-09 13:36:00.432  7100  7115 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-09 13:36:00.432  7100  7115 I Adreno-EGL: Remote Branch: 
09-09 13:36:00.432  7100  7115 I Adreno-EGL: Local Patches: 
09-09 13:36:00.432  7100  7115 I Adreno-EGL: Reconstruct Branch: 
09-09 13:36:00.442  1036  1392 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2437 sc=60 link=72 tx=61.0, 0.0, 0.0  rx=78.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:247177914] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-09 13:36:00.445  1036  1392 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2437 sc=60 link=72 tx=61.0, 0.0, 0.0  rx=78.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:247177917] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-09 13:36:00.445  1036  1392 D WifiNative-wlan0: doString: [SIGNAL_POLL]
09-09 13:36:00.459  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-09 13:36:00.472  7191  7191 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-09 13:36:00.482  7100  7115 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-09 13:36:00.482  7100  7115 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-09 13:36:00.482  7100  7115 I Adreno-EGL: Build Date: 12/12/14 금
09-09 13:36:00.482  7100  7115 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-09 13:36:00.482  7100  7115 I Adreno-EGL: Remote Branch: 
09-09 13:36:00.482  7100  7115 I Adreno-EGL: Local Patches: 
09-09 13:36:00.482  7100  7115 I Adreno-EGL: Reconstruct Branch: 
09-09 13:36:00.494  1036  1393 V WifiInternetCheck: Single check msg out of sync, ignoring.
,09-09 13:36:00.532  1036  1435 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-09 13:36:00.533  1036  1092 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-09 13:36:00.534  1036  1092 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 13:36:00.534  1036  1112 D Tethering: MasterInitialState.processMessage what=3
,09-09 13:36:00.540  6562  6562 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:36:00.541  5701  5701 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
09-09 13:36:00.543  6562  6562 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:36:00.553  6562  6562 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:36:00.561   311  7211 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
09-09 13:36:00.561   311  7211 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
09-09 13:36:00.619   311  7211 D libc-netbsd: res_queryN name = android.clients.google.com succeed
,09-09 13:36:00.767  1821  7059 I CheckinTask: Sending checkin request (8186 bytes)
,09-09 13:36:00.785  6373  6373 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,09-09 13:36:00.789  6373  6422 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,09-09 13:36:00.806  2180  2180 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:36:00.815  6985  6985 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-09 13:36:00.815  6985  6985 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-09 13:36:00.815  6985  6985 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-09 13:36:00.815  6985  6985 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-09 13:36:00.817  6985  6985 I AppUp4:CustModeStarterReceiver: onReceive
,09-09 13:36:00.823  6985  6985 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1c850217
,09-09 13:36:00.823  6985  6985 D AppUp4:CustFacade: isCustomizationCompleted : false
09-09 13:36:00.823  6985  6985 D AppUp4:CustFacade: isPhone : true
09-09 13:36:00.824  6985  6985 D AppUp4:CustModeStarterReceiver: begin check event
09-09 13:36:00.824  6985  6985 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-09 13:36:00.827  4328  4328 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-09 13:36:00.828  4328  4328 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-09 13:36:00.829  4328  4328 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-09 13:36:00.831  4328  4328 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-09 13:36:00.835  3489  3489 V DownloadManager: Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
09-09 13:36:00.836  4328  7217 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-09 13:36:00.838  4328  7217 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
09-09 13:36:00.840  3489  3489 V DownloadManager: DownloadService onCreate
09-09 13:36:00.842  3489  7219 I DownloadManager: in removeSpuriousFiles
09-09 13:36:00.842  3489  7219 V DownloadManager: starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
09-09 13:36:00.844  4328  7218 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-09 13:36:00.844  4328  7218 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-09 13:36:00.855  4328  7217 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
09-09 13:36:00.861  4328  4328 E LGDMClient: [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
09-09 13:36:00.861  4328  4328 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
,09-09 13:36:00.861  4328  4328 D LGDMClient: [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
09-09 13:36:00.863  4328  4328 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [274] : DmConstants.DMAgentState.DMA_STATE_IDLE
09-09 13:36:00.865  6471  7221 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:36:00.869  4328  4328 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [659] : agentmodeOnOff is OFF. Finish OneDayWiFiCheck
09-09 13:36:00.870  3423  3423 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-09 13:36:00.870  3423  3423 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-09 13:36:00.870  3423  3423 I LgeMiscReceiver: networkInfo.isConnected() = false
09-09 13:36:00.876  7026  7026 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-09 13:36:00.877  7026  7026 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-09 13:36:00.888  7083  7083 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:36:0
09-09 13:36:00.890  7083  7083 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-09 13:36:00.890  7083  7083 D Weather.Utils: 2 : All the weather widget is gone.
09-09 13:36:00.890  7083  7083 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-09 13:36:00.890  7083  7083 D WeatherAncestor: connectivity changed - connection : true
,09-09 13:36:00.890  7083  7083 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@a39c7ed
09-09 13:36:00.891  7083  7083 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-09 13:36:00.891  7083  7083 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-09 13:36:00.892  7083  7083 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-09 13:36:00.892  7083  7083 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-09 13:36:00.892  7083  7083 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:36:0
09-09 13:36:00.913  2180  2180 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
09-09 13:36:00.920  2180  2180 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
09-09 13:36:00.921  2180  2180 D c       : Getting all permits...
09-09 13:36:00.921  2180  2180 D a       : Opening database...
09-09 13:36:00.923  6851  7224 V FormManager: There are no updated forms. The schedule will be deleted.
09-09 13:36:00.924  1036  1999 I art     : Explicit concurrent mark sweep GC freed 122346(5MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/65MB, paused 2.533ms total 129.181ms
09-09 13:36:00.924  3489  7219 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@2d11b094 on behalf of 3489
09-09 13:36:00.924  3489  7219 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
09-09 13:36:00.924  3489  7219 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGEIME_5.1.29_release_repacked_ARM_XT9_MYSCRIPT_20160317004155539.apk
09-09 13:36:00.924  3489  7219 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_5.1.24_COM_COM(9012_VDF)_20160401022656759.apk
09-09 13:36:00.925  3489  7219 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
09-09 13:36:00.925  3489  7219 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
09-09 13:36:00.925  3489  7219 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
09-09 13:36:00.925  3489  7219 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
09-09 13:36:00.925  3489  7219 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/ConciergeBoard_4.40.12_COM_COM(VDF)_20160126234417577.apk
09-09 13:36:00.925  3489  7219 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
09-09 13:36:00.925  3489  7219 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
09-09 13:36:00.925  3489  7219 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
09-09 13:36:00.925  6851  7224 V FormManager: Alarm would be updated, because LastCheckTime has been updated.
09-09 13:36:00.928  3489  7219 I DownloadManager: in trimDatabase
09-09 13:36:00.928  3489  7219 V DownloadManager: starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
09-09 13:36:00.929  3489  7219 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@3acd773d on behalf of 3489
09-09 13:36:00.930  2180  2180 D a       : Opening database auth.proximity.permit_store...
09-09 13:36:00.930  2180  2180 D a       : Closing database...
09-09 13:36:00.933  3489  3489 V DownloadManager: DownloadService onStartCommand
09-09 13:36:00.934  3489  7220 V DownloadManager: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
09-09 13:36:00.940  6373  6373 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
09-09 13:36:00.940  3489  7220 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@16a34200 on behalf of 3489
09-09 13:36:00.941  6373  6422 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-09 13:36:00.942  3489  7220 V DownloadManager: processing inserted download 1
09-09 13:36:00.943  3489  7220 V DownloadManager: processing inserted download 4
09-09 13:36:00.944  3489  7220 V DownloadManager: processing inserted download 7
,09-09 13:36:00.945  3489  7220 V DownloadManager: processing inserted download 8
09-09 13:36:00.947  3489  7220 V DownloadManager: processing inserted download 9
09-09 13:36:00.948  3489  7220 V DownloadManager: processing inserted download 10
09-09 13:36:00.949  3489  7220 V DownloadManager: processing inserted download 11
09-09 13:36:00.950  3489  7220 V DownloadManager: processing inserted download 12
09-09 13:36:00.951  3489  7220 V DownloadManager: processing inserted download 13
09-09 13:36:00.952  3489  7220 V DownloadManager: processing inserted download 14
09-09 13:36:00.953  3489  7220 V DownloadManager: processing inserted download 16
09-09 13:36:00.963  3489  3489 V DownloadManager: DownloadService onDestroy
09-09 13:36:00.971  2180  2180 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
09-09 13:36:00.977  6985  6985 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-09 13:36:00.977  6985  6985 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-09 13:36:00.977  6985  6985 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-09 13:36:00.977  6985  6985 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-09 13:36:00.979  6985  6985 I AppUp4:CustModeStarterReceiver: onReceive
09-09 13:36:00.983  6985  6985 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1c850217
09-09 13:36:00.983  6985  6985 D AppUp4:CustFacade: isCustomizationCompleted : false
09-09 13:36:00.983  6985  6985 D AppUp4:CustFacade: isPhone : true
,09-09 13:36:00.983  6985  6985 D AppUp4:CustModeStarterReceiver: begin check event
09-09 13:36:00.983  6985  6985 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-09 13:36:00.987  4328  4328 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-09 13:36:00.987  4328  4328 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-09 13:36:00.988  4328  4328 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-09 13:36:00.990  4328  4328 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-09 13:36:00.994  3489  3489 V DownloadManager: Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:36:00.997  3489  3489 V DownloadManager: DownloadService onCreate
09-09 13:36:00.998  4328  7234 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-09 13:36:00.999  4328  7235 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-09 13:36:00.999  3489  7236 I DownloadManager: in removeSpuriousFiles
09-09 13:36:00.999  4328  7235 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-09 13:36:01.000  4328  7234 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
09-09 13:36:01.006  3489  7236 V DownloadManager: starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
09-09 13:36:01.007  4328  7234 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
,09-09 13:36:01.012  4328  4328 E LGDMClient: [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
09-09 13:36:01.012  4328  4328 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
09-09 13:36:01.012  4328  4328 D LGDMClient: [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
09-09 13:36:01.013  4328  4328 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [274] : DmConstants.DMAgentState.DMA_STATE_IDLE
09-09 13:36:01.016  3489  7236 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@6e9d1df on behalf of 3489
09-09 13:36:01.018  3489  7236 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
09-09 13:36:01.018  3489  7236 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGEIME_5.1.29_release_repacked_ARM_XT9_MYSCRIPT_20160317004155539.apk
09-09 13:36:01.018  3489  7236 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_5.1.24_COM_COM(9012_VDF)_20160401022656759.apk
09-09 13:36:01.018  3489  7236 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
09-09 13:36:01.018  3489  7236 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
09-09 13:36:01.018  3489  7236 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
09-09 13:36:01.018  3489  7236 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
09-09 13:36:01.018  3489  7236 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/ConciergeBoard_4.40.12_COM_COM(VDF)_20160126234417577.apk
09-09 13:36:01.018  3489  7236 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
09-09 13:36:01.018  3489  7236 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
09-09 13:36:01.018  3489  7236 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
09-09 13:36:01.019  3489  7236 I DownloadManager: in trimDatabase
09-09 13:36:01.019  4328  4328 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [659] : agentmodeOnOff is OFF. Finish OneDayWiFiCheck
,09-09 13:36:01.021  3489  3489 V DownloadManager: DownloadService onStartCommand
,09-09 13:36:01.021  3489  7237 V DownloadManager: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
09-09 13:36:01.023  3489  7237 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@1f2150f5 on behalf of 3489
09-09 13:36:01.025  3423  3423 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-09 13:36:01.025  3489  7237 V DownloadManager: processing inserted download 1
09-09 13:36:01.025  3423  3423 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-09 13:36:01.026  3423  3423 I LgeMiscReceiver: networkInfo.isConnected() = true
09-09 13:36:01.026  3423  3423 D PhoneState: setPdpRejectCasuse : false
09-09 13:36:01.026  6471  7238 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:36:01.026  3489  7236 V DownloadManager: starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
09-09 13:36:01.028  3489  7236 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@3a584e8a on behalf of 3489
09-09 13:36:01.028  7026  7026 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-09 13:36:01.028  7026  7026 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-09 13:36:01.032  3489  7237 V DownloadManager: processing inserted download 4
,09-09 13:36:01.035  3489  7237 V DownloadManager: processing inserted download 7
,09-09 13:36:01.037  3489  7237 V DownloadManager: processing inserted download 8
09-09 13:36:01.038  7083  7083 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:36:1
09-09 13:36:01.039  3489  7237 V DownloadManager: processing inserted download 9
09-09 13:36:01.039  7083  7083 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-09 13:36:01.039  7083  7083 D Weather.Utils: 2 : All the weather widget is gone.
09-09 13:36:01.040  7083  7083 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-09 13:36:01.040  7083  7083 D WeatherAncestor: connectivity changed - connection : true
09-09 13:36:01.040  7083  7083 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@a39c7ed
09-09 13:36:01.040  7083  7083 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-09 13:36:01.040  7083  7083 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-09 13:36:01.040  7083  7083 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-09 13:36:01.040  7083  7083 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-09 13:36:01.041  7083  7083 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:36:1
09-09 13:36:01.041  3489  7237 V DownloadManager: processing inserted download 10
09-09 13:36:01.042  3489  7237 V DownloadManager: processing inserted download 11
09-09 13:36:01.043  1821  7059 I CheckinTask: Checkin success: https://android.clients.google.com/checkin (1 requests sent)
09-09 13:36:01.043  3489  7237 V DownloadManager: processing inserted download 12
,09-09 13:36:01.046  3489  7237 V DownloadManager: processing inserted download 13
09-09 13:36:01.048  3489  7237 V DownloadManager: processing inserted download 14
09-09 13:36:01.049  3489  7237 V DownloadManager: processing inserted download 16
,09-09 13:36:01.058  3489  3489 V DownloadManager: DownloadService onDestroy
,09-09 13:36:01.060  1821  7059 I CheckinService: active receiver: disabled
09-09 13:36:01.063  6851  7242 V FormManager: There are no updated forms. The schedule will be deleted.
09-09 13:36:01.066  6851  7242 V FormManager: Alarm would be updated, because LastCheckTime has been updated.
,09-09 13:36:01.085  1821  7244 I CheckinService: active receiver: disabled
,09-09 13:36:01.092  2180  2180 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
09-09 13:36:01.101  2180  2180 I GCM     : GCM config loaded
,09-09 13:36:01.112  7026  7026 V SetupWizard: Connected to Gservices successfully
,09-09 13:36:01.574  1036  1377 D PowerManagerServiceEx: acquireWakeLockInternal: lock=983760471, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1036
,09-09 13:36:01.601  6825  6825 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
09-09 13:36:01.602  6825  6825 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:816
,09-09 13:36:01.644  2601  2601 D [Concierge]Service: onStartCommand(). Type : 9
,09-09 13:36:01.676  1036  1036 D PowerManagerServiceEx: releaseWakeLockInternal: lock=983760471 [*alarm*], flags=0x0
,09-09 13:36:01.716   311  7256 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,09-09 13:36:01.718   311  7256 D libc-netbsd: res_queryN name = www.google.com, class = 1, type = 1
09-09 13:36:01.770   311  7256 D libc-netbsd: res_queryN name = www.google.com succeed
,09-09 13:36:01.782   311  7262 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,09-09 13:36:01.782   311  7262 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,09-09 13:36:01.782   311  7262 D libc-netbsd: res_queryN name = clients3.google.com succeed
09-09 13:36:01.868  1036  1394 V WifiInternetCheck: isHttpConnectionAvailable - We got a valid response : 204
,09-09 13:36:01.964  6670  6920 D UEI.SmartControl: Internal timer expired: 4
,09-09 13:36:01.964  6670  6920 D UEI.SmartControl: unbind internal service
,09-09 13:36:02.035  6670  6917 D serial_port: close(fd = 24)
,09-09 13:36:02.044  6670  6917 I UEI.SmartControl: Serial port is closed.
,09-09 13:36:02.071  6562  6922 E io.jxcore.node.ConnectivityMonitorTest: BT state didn't change after 5s!
,09-09 13:36:02.083  1036  1578 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 13:36:02.083  1036  1578 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@caa1ab7 mBinding = false
,09-09 13:36:02.105  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
,09-09 13:36:02.105  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-09 13:36:02.105  1036  1036 D Ulp_jni : JNI:system_update. Event-4
09-09 13:36:02.106  1036  1112 D BluetoothManagerService: Message: 2
09-09 13:36:02.107  1036  1112 D BluetoothManagerService: Sending off request.
09-09 13:36:02.108  3858  3874 D LGBluetoothServiceAdapter: [BTUI] Precleanup
09-09 13:36:02.109  3858  3945 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
09-09 13:36:02.109  3858  3945 D BluetoothAdapterProperties: Setting state to 13
09-09 13:36:02.109  3858  3945 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-09 13:36:02.110  3858  3945 D BluetoothAdapterProperties: onBluetoothDisable()
09-09 13:36:02.110  3858  3945 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
09-09 13:36:02.115  3858  3951 D BluetoothAdapterProperties: Scan Mode:20
,09-09 13:36:02.121  3858  3945 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
09-09 13:36:02.123  3858  4240 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
09-09 13:36:02.123  3858  4240 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-09 13:36:02.123  3858  4240 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
09-09 13:36:02.123  3858  4240 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
09-09 13:36:02.123  3858  4240 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
09-09 13:36:02.123  3858  4240 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
09-09 13:36:02.123  3858  4240 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
09-09 13:36:02.123  3858  4240 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
09-09 13:36:02.124  3858  3945 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-09 13:36:02.125  3858  4243 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-09 13:36:02.126  3858  4295 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-09 13:36:02.127  3858  4298 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-09 13:36:02.127  3858  4296 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-09 13:36:02.130  3858  4079 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
09-09 13:36:02.131  3858  4079 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
,09-09 13:36:02.136  3858  4079 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-09 13:36:02.136  3858  4079 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-09 13:36:02.136  3858  4079 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-09 13:36:02.136  3858  4079 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-09 13:36:02.136  3858  4079 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-09 13:36:02.136  3858  4079 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-09 13:36:02.136  3858  4079 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-09 13:36:02.136  3858  4079 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-09 13:36:02.136  3858  4079 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-09 13:36:02.136  3858  4079 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
09-09 13:36:02.136  3858  4079 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
09-09 13:36:02.136  3858  4079 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-09 13:36:02.141  6562  6562 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:36:02.141  6562  6562 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:36:02.141  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:36:02.141  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:36:02.141  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:36:02.141  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 13:36:02.141  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:36:02.141  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:36:02.141  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:36:02.143  6562  6562 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:36:02.143  6562  6562 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:36:02.147  6562  6562 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:36:02.148  6562  6562 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:36:02.148  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:36:02.148  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:36:02.148  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:36:02.148  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 13:36:02.148  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:36:02.148  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:36:02.148  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:36:02.159  6562  6562 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:36:02.159  6562  6562 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:36:02.162  6562  6562 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:36:02.162  6562  6562 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:36:02.162  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:36:02.162  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:36:02.162  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:36:02.162  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 13:36:02.162  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:36:02.162  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:36:02.162  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:36:02.166  6562  6562 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:36:02.166  6562  6562 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:36:02.178  1036  1112 D BluetoothManagerService: Message: 60
09-09 13:36:02.178  1036  1112 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
09-09 13:36:02.178  1036  1112 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
,09-09 13:36:02.225  1036  1093 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7270 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,09-09 13:36:02.240  1605  1605 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,09-09 13:36:02.243  1945  1945 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-09 13:36:02.246  3858  3858 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-09 13:36:02.246  3858  3858 D BluetoothMapService: STATE_TURNING_OFF
09-09 13:36:02.246  3858  3858 V BluetoothMapService: Handler(): got msg=4
09-09 13:36:02.246  3858  3858 D BluetoothMapService: MAP Service closeService in
09-09 13:36:02.246  3858  3858 D BluetoothMapMasInstance: MAP Service shutdown
09-09 13:36:02.247  3858  3858 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-09 13:36:02.247  3858  3858 V BluetoothMapService: MAP Service closeService out
09-09 13:36:02.247  3858  3858 V BtOppService: Receiver DISABLED_ACTION 
09-09 13:36:02.247  3858  3858 I BtOppRfcommListener: stopping Accept Thread
09-09 13:36:02.247  3858  3858 V BtOppRfcommListener: close mBtServerSocket
09-09 13:36:02.248  3858  3858 V BtOppRfcommListener: waiting for thread to terminate
09-09 13:36:02.248  3858  4295 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-09 13:36:02.248  3858  3858 V BtOppRfcommListener: done waiting for thread to terminate
09-09 13:36:02.249  6562  6562 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:36:02.251  6562  6562 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:36:02.253  6562  6562 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:36:02.260  3858  3858 V BtOppService: onDestroy
,09-09 13:36:02.261  3858  3858 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
09-09 13:36:02.262  6804  6804 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-09 13:36:02.268  3858  3858 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-09 13:36:02.268  3858  3858 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-09 13:36:02.268  3858  3858 V BluetoothPbapReceiver: ***********state = 13
09-09 13:36:02.270  3858  3858 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
09-09 13:36:02.271  3858  3858 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-09 13:36:02.271  3858  3858 V BluetoothPbapService: state: 13
09-09 13:36:02.271  3858  3858 V BluetoothPbapService: Pbap Service closeService in
09-09 13:36:02.273  3858  3858 V BluetoothPbapService: successfully stopped pbap service
09-09 13:36:02.273  3858  3858 V BluetoothPbapService: Pbap Service closeService out
09-09 13:36:02.273  3858  3858 V BluetoothPbapService: Pbap Service onDestroy
09-09 13:36:02.274  3858  3858 V BluetoothPbapService: Pbap Service closeService in
09-09 13:36:02.274  3858  3858 V BluetoothPbapService: Pbap Service closeService out
09-09 13:36:02.274  3858  3858 D LGBluetoothPbapAdapter: [BTUI] cleanup
09-09 13:36:02.274  2180  2180 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-09 13:36:02.277  1036  1112 D BluetoothManagerService: Message: 20
09-09 13:36:02.277  1036  1112 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@12426f42:true
,09-09 13:36:02.290  1036  1112 D BluetoothManagerService: Message: 30
09-09 13:36:02.297  1036  1112 D BluetoothManagerService: Message: 30
,09-09 13:36:02.304  6804  6804 D LocalBluetoothProfileManager: Adding local MAP profile
09-09 13:36:02.306  6804  6804 D BluetoothMap: Create BluetoothMap proxy object
09-09 13:36:02.306  1036  1112 D BluetoothManagerService: Message: 30
09-09 13:36:02.311  1036  1112 D BluetoothManagerService: Message: 30
09-09 13:36:02.313  6804  6804 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-09 13:36:02.314  6804  6804 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
09-09 13:36:02.328  6804  6804 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
,09-09 13:36:02.330  6804  6804 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
09-09 13:36:02.339  6804  6804 D DockEventReceiver: finishStartingService: stopping service
,09-09 13:36:02.341  6804  6804 D BluetoothInputDevice: Proxy object connected
09-09 13:36:02.342  6804  6804 D HidProfile: Bluetooth service connected
09-09 13:36:02.343  6804  6804 D BluetoothPan: BluetoothPAN Proxy object connected
09-09 13:36:02.343  6804  6804 D PanProfile: Bluetooth service connected
09-09 13:36:02.344  6804  6804 D BluetoothMap: Proxy object connected
09-09 13:36:02.344  6804  6804 D MapProfile: Bluetooth service connected
09-09 13:36:02.345  6804  6804 D BluetoothMap: getConnectedDevices()
09-09 13:36:02.345  6804  6804 D BluetoothMap: Bluetooth is Not enabled
09-09 13:36:02.345  6804  6804 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
09-09 13:36:02.371  7270  7270 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
09-09 13:36:02.372  7270  7270 W LG Account v2.2: No ProfileInfo entries
09-09 13:36:02.372  7270  7270 I LG Account v2.2: isEnabled: false
09-09 13:36:02.372  7270  7270 I Feature : [Lifetracker]ver: 4.21.112(40211120)
09-09 13:36:02.372  7270  7270 I Feature : [Lifetracker]Country: EU
09-09 13:36:02.372  7270  7270 I Feature : [Lifetracker]Operator: OPEN
09-09 13:36:02.373  7270  7270 I Feature : [Lifetracker]Ranking support: false
09-09 13:36:02.373  7270  7270 I Feature : [Lifetracker]Comfort support: false
09-09 13:36:02.373  7270  7270 I Feature : [Lifetracker]Accessory: true
09-09 13:36:02.373  7270  7270 I Feature : [Lifetracker]Health device: true
09-09 13:36:02.373  7270  7270 I Feature : [Lifetracker]Extra Pedometer: false
09-09 13:36:02.373  7270  7270 I Feature : [Lifetracker]Blood glucose device: false
,09-09 13:36:02.373  7270  7270 I Feature : [Lifetracker]Device Number: 3
,09-09 13:36:02.389  6804  6804 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,09-09 13:36:02.395  6804  6804 D BluetoothPermissionRequest: onReceive
,09-09 13:36:02.399  6804  6804 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,09-09 13:36:02.412  6804  6804 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,09-09 13:36:02.418  1036  1981 I ActivityManager: Killing 2136:com.lge.music/u0a34 (adj 15): empty #17
,09-09 13:36:02.451   315  2170 V AudioFlinger: 2136 died, releasing its sessions
09-09 13:36:02.451   315  2170 V AudioFlinger:  pid 1857 @ 0
,09-09 13:36:02.451   315  2170 V AudioFlinger:  pid 3423 @ 1
09-09 13:36:02.451   315  2170 V AudioFlinger:  pid 3423 @ 2
09-09 13:36:02.479  1036  1052 W libprocessgroup: failed to open /acct/uid_10034/pid_2136/cgroup.procs: No such file or directory
,09-09 13:36:02.481  3858  3858 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
09-09 13:36:02.481  3858  3858 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
09-09 13:36:02.483  3858  3858 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
09-09 13:36:02.498  3858  3858 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,09-09 13:36:02.498  3858  3858 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
09-09 13:36:02.502  3858  3858 V BluetoothFtpService: Ftp Service onStartCommand
09-09 13:36:02.503  3858  3858 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-09 13:36:02.504  3858  3858 V BluetoothFtpService: Ftp Service closeService
09-09 13:36:02.504  3858  3858 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
09-09 13:36:02.507  3858  3858 V BluetoothFtpService: successfully stopped ftp service
09-09 13:36:02.508  3858  3858 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-09 13:36:02.508  3858  3858 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-09 13:36:02.508  3858  3858 V BluetoothSapReceiver: SapReceiver onReceive 
09-09 13:36:02.509  3858  3858 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-09 13:36:02.509  3858  3858 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
09-09 13:36:02.509  3858  3858 V BluetoothSapReceiver: Calling SAP service start service with action = null
09-09 13:36:02.512  3858  3858 V BluetoothFtpService: Ftp Service onDestroy
09-09 13:36:02.512  3858  3858 V BluetoothFtpService: Ftp Service closeService
,09-09 13:36:02.593  1036  1943 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=7317 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
09-09 13:36:02.594  3858  3858 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-09 13:36:02.594  3858  3858 V BluetoothSapService: state: 13
09-09 13:36:02.595  3858  3858 V BluetoothSapService: Stopping SAP server process
09-09 13:36:02.598  3858  3858 V BluetoothSapService: Sap Service closeSapService in
09-09 13:36:02.598  3858  3858 V BluetoothSapService: Close listen Socket : 
09-09 13:36:02.598  3858  3858 V BluetoothSapService: Close rfcomm Socket : 
09-09 13:36:02.598  3858  3858 V BluetoothSapService: Close sapd  Socket : 
09-09 13:36:02.599  3858  3858 V BluetoothSapService: Sap Service closeSapService out
09-09 13:36:02.600  3858  3858 V BluetoothSapService: Sap Service onDestroy
09-09 13:36:02.600  3858  3858 V BluetoothSapService: Sap Service closeSapService in
09-09 13:36:02.600  3858  3858 V BluetoothSapService: Close listen Socket : 
09-09 13:36:02.600  3858  3858 V BluetoothSapService: Close rfcomm Socket : 
09-09 13:36:02.600  3858  3858 V BluetoothSapService: Close sapd  Socket : 
09-09 13:36:02.601  3858  3858 V BluetoothSapService: Sap Service closeSapService out
,09-09 13:36:02.619   343   343 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 474us total 25.785ms
,09-09 13:36:02.640   343   343 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 413us total 20.383ms
09-09 13:36:02.658  7317  7317 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-09 13:36:02.659   343   343 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 412us total 19.072ms
,09-09 13:36:02.677  1036  1923 I ActivityManager: Killing 6013:com.android.vending/u0a44 (adj 15): empty #17
,09-09 13:36:02.740  1036  1578 W libprocessgroup: failed to open /acct/uid_10044/pid_6013/cgroup.procs: No such file or directory
,09-09 13:36:03.136  3858  3951 D bt_hci_bdroid: cleanup
,09-09 13:36:03.143  3858  4081 I bt_lpm  : LPM is already off!!!
09-09 13:36:03.144  3858  4233 I bt_userial_mct: exiting userial_read_thread
09-09 13:36:03.144  3858  4233 D bt_userial_mct: Leaving userial_evt_read_thread()
09-09 13:36:03.145  3858  4079 W bt-btif : ag scb idx 1 not allocated
09-09 13:36:03.145  3858  4079 E bt-btif : BTA AG is already disabled, ignoring ...
09-09 13:36:03.145  3858  4079 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-09 13:36:03.145  3858  4079 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-09 13:36:03.145  3858  4079 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-09 13:36:03.146  3858  4079 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-09 13:36:03.146  3858  4079 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-09 13:36:03.146  3858  4079 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-09 13:36:03.146  3858  4079 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-09 13:36:03.146  3858  4079 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-09 13:36:03.146  3858  4079 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-09 13:36:03.146  3858  4079 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-09 13:36:03.149  3858  3951 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
09-09 13:36:03.149  3858  4081 I bt_vendor: hw_epilog_process
09-09 13:36:03.150  3858  3951 D bt_hci_bdroid: cleanup Finalizing cleanup
09-09 13:36:03.150  3858  3951 D bt_userial_mct: userial_close
09-09 13:36:03.150  3858  3951 E bt_userial_mct: pthread_join() FAILED result:3
09-09 13:36:03.150  3858  3951 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
09-09 13:36:03.146  3858  4079 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-09 13:36:03.150  3858  4079 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-09 13:36:03.150  3858  4079 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-09 13:36:03.150  3858  4079 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-09 13:36:03.150  3858  4079 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-09 13:36:03.150  3858  4079 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-09 13:36:03.150  3858  4079 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-09 13:36:03.150  3858  4079 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-09 13:36:03.150  3858  4079 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-09 13:36:03.157  3858  3951 D bt_hci_bdroid: set_power 0
09-09 13:36:03.157  3858  3951 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
09-09 13:36:03.157  3858  3951 I bt_vendor: bluetooth satus is on
09-09 13:36:03.157  3858  3951 I bt_vendor: bt-vendor : resetting BT status
09-09 13:36:03.157  3858  3951 I bt_vendor: Starting hciattach daemon
09-09 13:36:03.157  3858  3951 I bt_vendor: try to set false
,09-09 13:36:03.164  3858  3951 I bt_vendor: Starting hciattach daemon
09-09 13:36:03.164  3858  3951 I bt_vendor: try to set false
09-09 13:36:03.165  3858  3951 I bt_vendor: cleanup
09-09 13:36:03.166  3858  4079 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
09-09 13:36:03.166  3858  3951 I GKI_LINUX: GKI_exit_task 0 done
09-09 13:36:03.166  3858  3951 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
09-09 13:36:03.168  3858  3945 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
09-09 13:36:03.173  3858  3858 D HeadsetService: Received stop request...Stopping profile...
,09-09 13:36:03.177  3858  3858 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-09 13:36:03.177  3858  3858 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-09 13:36:03.177  3858  3858 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@200f1604
09-09 13:36:03.178  3858  3974 D HeadsetStateMachine: Exit Disconnected: -1
09-09 13:36:03.181  1857  1857 D BluetoothHeadset: Proxy object disconnected
09-09 13:36:03.181  1857  1857 D BluetoothHeadset: Proxy object disconnected
09-09 13:36:03.181  1857  1857 D BluetoothHeadset: Proxy object disconnected
09-09 13:36:03.181  1036  1036 D BluetoothHeadset: Proxy object disconnected
09-09 13:36:03.181  1036  1036 D AudioService: onServiceDisconnected: Bluetooth profile: 1
09-09 13:36:03.185  3858  3945 D BluetoothAdapterState: Stopping profile services that were post enabled
,09-09 13:36:03.190  3858  3858 D A2dpService: Received stop request...Stopping profile...
09-09 13:36:03.191  3858  4022 D A2dpStateMachine: Exit Disconnected: -1
09-09 13:36:03.192  3858  3858 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
09-09 13:36:03.194  3858  3858 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
09-09 13:36:03.194  3858  3858 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
09-09 13:36:03.194  3858  3858 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@200f1604
09-09 13:36:03.197  3858  3858 D HidService: Received stop request...Stopping profile...
09-09 13:36:03.197  3858  3858 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@200f1604
,09-09 13:36:03.201  1036  1036 D BluetoothA2dp: Proxy object disconnected
09-09 13:36:03.201  1036  1036 D AudioService: onServiceDisconnected: Bluetooth profile: 2
09-09 13:36:03.202  3858  3858 D HeadsetStateMachine: Unbinding service...
09-09 13:36:03.205  3858  3858 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-09 13:36:03.205  3858  3858 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-09 13:36:03.205  3858  3858 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-09 13:36:03.205  3858  3858 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-09 13:36:03.205  3858  3858 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-09 13:36:03.205  3858  3858 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-09 13:36:03.205  3858  3858 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-09 13:36:03.206  3858  3858 D HealthService: Received stop request...Stopping profile...
09-09 13:36:03.206  3858  3858 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@200f1604
09-09 13:36:03.209  3858  3858 D PanService: Received stop request...Stopping profile...
,09-09 13:36:03.211  3858  3858 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@200f1604
09-09 13:36:03.213  3858  3858 D BtGatt.DebugUtils: handleDebugAction() action=null
09-09 13:36:03.214  3858  3858 D BtGatt.GattService: Received stop request...Stopping profile...
09-09 13:36:03.214  3858  3858 D BtGatt.GattService: stop()
09-09 13:36:03.214  3858  3858 D BtGatt.AdvertiseManager: advertise clients cleared
09-09 13:36:03.216  3858  3858 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@200f1604
09-09 13:36:03.217  3858  3858 D BluetoothMapService: Received stop request...Stopping profile...
09-09 13:36:03.217  3858  3858 D BluetoothMapService: stop()
09-09 13:36:03.218  3858  3858 D BluetoothMapEmailAppObserver: deinitObservers()
09-09 13:36:03.218  3858  3858 D BluetoothMapEmailAppObserver: removeReceiver()
09-09 13:36:03.219  3858  3858 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@200f1604
09-09 13:36:03.220  3858  3858 I BluetoothA2dpServiceJni: cleanupNative
09-09 13:36:03.220  3858  4023 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
,09-09 13:36:03.222  3858  3858 I GKI_LINUX: GKI_exit_task 2 done
09-09 13:36:03.223  3858  3858 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
09-09 13:36:03.223  3858  3858 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-09 13:36:03.223  3858  3858 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-09 13:36:03.223  3858  3858 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-09 13:36:03.224  3858  3858 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-09 13:36:03.224  3858  3858 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-09 13:36:03.224  3858  3858 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-09 13:36:03.224  3858  3858 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-09 13:36:03.227  3858  3858 V BluetoothMapService: Handler(): got msg=4
09-09 13:36:03.227  3858  3858 D BluetoothMapService: MAP Service closeService in
09-09 13:36:03.227  3858  3858 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-09 13:36:03.227  3858  3858 V BluetoothMapService: MAP Service closeService out
09-09 13:36:03.229  3858  3945 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
09-09 13:36:03.229  3858  3945 D BluetoothAdapterProperties: Setting state to 10
09-09 13:36:03.229  3858  3945 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
09-09 13:36:03.229  3858  3858 D BluetoothMapService: cleanup()
09-09 13:36:03.229  3858  3858 D BluetoothMapService: MAP Service closeService in
09-09 13:36:03.229  3858  3858 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-09 13:36:03.229  3858  3858 V BluetoothMapService: MAP Service closeService out
09-09 13:36:03.230  1036  1112 D BluetoothManagerService: Message: 60
09-09 13:36:03.230  1036  1112 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
09-09 13:36:03.230  1036  1112 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
09-09 13:36:03.231  3858  3945 I BluetoothAdapterState: Entering OffState
09-09 13:36:03.231  6804  6820 D BluetoothMap: onBluetoothStateChange: up=false
09-09 13:36:03.232  1857  1873 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-09 13:36:03.237  1036  1112 D BluetoothA2dp: onBluetoothStateChange: up=false
09-09 13:36:03.237  1857  2473 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 13:36:03.238  6804  6820 D BluetoothPan: onBluetoothStateChange on: false
09-09 13:36:03.239  1857  4431 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 13:36:03.241  1036  1112 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 13:36:03.241  6804  6820 D BluetoothPbap: onBluetoothStateChange: up=false
09-09 13:36:03.242  6804  6820 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-09 13:36:03.243  1036  1112 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
09-09 13:36:03.243  1036  1112 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
09-09 13:36:03.245  1036  1112 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
09-09 13:36:03.245  1036  1112 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
09-09 13:36:03.245  1036  1112 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@caa1ab7 mBinding = false
,09-09 13:36:03.248  1036  1112 D BluetoothManagerService: Sending unbind request.
09-09 13:36:03.259  3858  3951 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,09-09 13:36:03.261  3858  3858 I GKI_LINUX: GKI_exit_task 1 done
09-09 13:36:03.261  3858  3858 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
09-09 13:36:03.262  3858  3858 I BluetoothServiceJni: cleanupNative: return from cleanup
09-09 13:36:03.262  3858  3858 I art     : --- WEIRD: removing null entry 246
09-09 13:36:03.262  3858  3858 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
09-09 13:36:03.262  3858  3858 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
09-09 13:36:03.263  3858  3858 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
09-09 13:36:03.264  1036  1112 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
09-09 13:36:03.266  3858  3858 I art     : System.exit called, status: 0
09-09 13:36:03.266  3858  3858 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
09-09 13:36:03.286   315  1403 V AudioFlinger: 3858 died, releasing its sessions
09-09 13:36:03.286   315  1403 V AudioFlinger:  pid 1857 @ 0
09-09 13:36:03.286   315  1403 V AudioFlinger:  pid 3423 @ 1
09-09 13:36:03.286   315  1403 V AudioFlinger:  pid 3423 @ 2
,09-09 13:36:03.290  1945  1945 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: disconnected from LGBluetoothAPIAdapter
09-09 13:36:03.290  1945  2103 D LGBluetoothAPIService: Message: 101
09-09 13:36:03.291  1945  2103 E LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED
09-09 13:36:03.291  1945  2103 D LGBluetoothAPIService: Calling onBluetoothServiceDown callbacks
09-09 13:36:03.291  1945  2103 D LGBluetoothAPIService: Broadcasting onBluetoothServiceDown() to 0 receivers.
09-09 13:36:03.293  6804  6804 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
09-09 13:36:03.302  1036  1616 I ActivityManager: Process com.android.bluetooth (pid 3858) has died
09-09 13:36:03.303  1036  1616 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer in 1000ms
09-09 13:36:03.303  1036  1616 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 11000ms
,09-09 13:36:03.311  1945  1945 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-09 13:36:03.312  1945  2103 D LGBluetoothAPIService: Message: 2
09-09 13:36:03.313  1945  2103 D LGBluetoothAPIService: unbindAndFinish(): null mBinding = false
09-09 13:36:03.313  1605  1605 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-09 13:36:03.317  6562  6562 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:36:03.317  6804  6804 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
09-09 13:36:03.318  6804  6804 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
09-09 13:36:03.318  6562  6562 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:36:03.318  6804  6804 D LGBluetoothEventManager: [BTUI] clear device connection state
09-09 13:36:03.320  6562  6562 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:36:03.321  6804  6804 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,09-09 13:36:03.327  1605  1605 D BluetoothAdapter: 534664732: getState() :  mService = null. Returning STATE_OFF
09-09 13:36:03.328  1605  1605 D BluetoothAdapter: 534664732: getState() :  mService = null. Returning STATE_OFF
09-09 13:36:03.380  1036  1616 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=7358 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,09-09 13:36:03.381  6804  6804 D DockEventReceiver: finishStartingService: stopping service
,09-09 13:36:03.428  7358  7358 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,09-09 13:36:03.428  7358  7358 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-09 13:36:03.428  7358  7358 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
09-09 13:36:03.429  7358  7358 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
09-09 13:36:03.445  7358  7358 D BluetoothAdapterApp: Loading JNI Library
,09-09 13:36:03.464  1036  1392 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2437 sc=60 link=72 tx=42.0, 0.0, 0.0  rx=48.5 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:247180936] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,09-09 13:36:03.469  1036  1392 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2437 sc=60 link=72 tx=42.0, 0.0, 0.0  rx=48.5 bcn=0 [on:0 tx:0 rx:0 period:5] from screen [on:0 period:247180941] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-09 13:36:03.469  1036  1392 D WifiNative-wlan0: doString: [SIGNAL_POLL]
09-09 13:36:03.471  7358  7358 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@3316e735 Instance Count = 1
09-09 13:36:03.475  7358  7358 D BluetoothAdapterApp: onCreate
09-09 13:36:03.493  7358  7358 D ProfileConfigQcom: [BTUI] HeadsetService is supported
09-09 13:36:03.493  7358  7358 D ProfileConfigQcom: Adding HeadsetService
,09-09 13:36:03.494  7358  7358 D ProfileConfigQcom: [BTUI] A2dpService is supported
09-09 13:36:03.494  7358  7358 D ProfileConfigQcom: Adding A2dpService
09-09 13:36:03.494  7358  7358 D ProfileConfigQcom: [BTUI] HidService is supported
09-09 13:36:03.494  7358  7358 D ProfileConfigQcom: Adding HidService
09-09 13:36:03.494  7358  7358 D ProfileConfigQcom: [BTUI] HealthService is supported
09-09 13:36:03.494  7358  7358 D ProfileConfigQcom: Adding HealthService
09-09 13:36:03.494  7358  7358 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
09-09 13:36:03.496  7358  7358 D ProfileConfigQcom: [BTUI] PanService is supported
09-09 13:36:03.496  7358  7358 D ProfileConfigQcom: Adding PanService
09-09 13:36:03.496  7358  7358 D ProfileConfigQcom: [BTUI] GattService is supported
09-09 13:36:03.496  7358  7358 D ProfileConfigQcom: Adding GattService
09-09 13:36:03.496  7358  7358 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
09-09 13:36:03.496  7358  7358 D ProfileConfigQcom: Adding BluetoothMapService
09-09 13:36:03.497  7358  7358 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
09-09 13:36:03.498  7358  7358 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-09 13:36:03.498  7358  7358 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-09 13:36:03.499  7358  7358 V BluetoothPbapReceiver: ***********state = 10
09-09 13:36:03.500  7358  7358 V LGMDMManagerInternal: Create singleton instance
09-09 13:36:03.560  2180  2180 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-09 13:36:03.565  7358  7358 D LGBluetoothAPIServer: [BTUI] onCreate()
09-09 13:36:03.565  7358  7358 D LGBluetoothAPIServer: [BTUI] onBind()
09-09 13:36:03.567  1945  1945 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
09-09 13:36:03.569  1945  2103 D LGBluetoothAPIService: Message: 100
09-09 13:36:03.569  1945  2103 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
09-09 13:36:03.573  6804  6804 D BluetoothPermissionRequest: onReceive
09-09 13:36:03.577  6804  6804 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
,09-09 13:36:03.579  6804  6804 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
09-09 13:36:03.580  6804  6804 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
09-09 13:36:03.582  6804  6804 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-09 13:36:03.588  7358  7358 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
,09-09 13:36:03.592  7358  7358 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-09 13:36:03.595  7358  7358 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-09 13:36:03.596  7358  7358 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-09 13:36:03.596  7358  7358 V BluetoothSapReceiver: SapReceiver onReceive 
09-09 13:36:03.597  7358  7358 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-09 13:36:03.597  7358  7358 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
09-09 13:36:03.604  7317  7317 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,09-09 13:36:05.015  7123  7150 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,09-09 13:36:05.568  1036  1962 I ActivityManager: Killing 6652:com.lge.bnr/1000 (adj 15): empty #17
,09-09 13:36:05.599  1036  1999 W libprocessgroup: failed to open /acct/uid_1000/pid_6652/cgroup.procs: No such file or directory
,09-09 13:36:05.791  1036  1963 I ActivityManager: Killing 6783:com.lge.sync/1000 (adj 15): empty #17
,09-09 13:36:05.823  1036  1923 W libprocessgroup: failed to open /acct/uid_1000/pid_6783/cgroup.procs: No such file or directory
,09-09 13:36:06.481  1036  1392 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2437 sc=60 link=72 tx=34.0, 0.0, 0.0  rx=34.8 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:247183953] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,09-09 13:36:06.484  1036  1392 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2437 sc=60 link=72 tx=34.0, 0.0, 0.0  rx=34.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:247183956] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,09-09 13:36:06.484  1036  1392 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,09-09 13:36:07.208  6562  7269 E io.jxcore.node.ConnectivityMonitorTest: BT state didn't change after 5s!
,09-09 13:36:07.216  6562  6617 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:36:07.216  6562  6617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:36:07.220  6562  6617 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:36:07.220  6562  6617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:36:07.220  6562  6617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:36:07.221  6562  6617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 13:36:07.221  6562  6617 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15ed3182 removed from the list
09-09 13:36:07.221  6562  6617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:36:07.221  6562  6617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@279fe093 removed from the list
09-09 13:36:07.221  6562  6617 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:36:07.221  6562  6617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:36:07.221  6562  6617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:36:07.224  6562  6617 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 13:36:07.224  6562  6617 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@48da0c9 added. We now have 3 listener(s)
09-09 13:36:07.228  1036  1780 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-09 13:36:07.234  6562  6617 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-09 13:36:07.234  6562  6617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 13:36:07.234  6562  6617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 13:36:07.234  6562  6617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 13:36:07.234  6562  6617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3bc0e3ce added. We now have 3 listener(s)
09-09 13:36:07.234  6562  6617 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 13:36:07.235  6562  6617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-09 13:36:07.238  6562  6617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:36:07.240  6562  6617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:36:07.240  6562  6617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:36:07.240  6562  6617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:36:07.240  6562  6617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:36:07.240  6562  6617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:36:07.240  6562  6617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 13:36:07.240  6562  6617 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:36:07.240  6562  6617 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:36:07.240  6562  6617 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:36:07.240  6562  6617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:36:07.240  6562  6617 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:36:07.240  6562  6617 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 13:36:07.242  6562  6562 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:36:07.247  6562  6562 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:36:07.247  6562  6617 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:36:07.248  6562  6617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:36:07.248  6562  6617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:36:07.248  6562  6617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 13:36:07.248  6562  6617 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@48da0c9 removed from the list
09-09 13:36:07.248  6562  6617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:36:07.248  6562  6617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3bc0e3ce removed from the list
09-09 13:36:07.248  6562  6617 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:36:07.248  6562  6617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:36:07.249  6562  6617 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 13:36:07.250  6562  6617 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@235f71fc added. We now have 3 listener(s)
09-09 13:36:07.250  1036  1052 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 13:36:07.252  6562  6617 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-09 13:36:07.253  6562  6617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 13:36:07.253  6562  6617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 13:36:07.253  6562  6617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 13:36:07.253  6562  6617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9468085 added. We now have 3 listener(s)
09-09 13:36:07.253  6562  6617 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 13:36:07.254  6562  6617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 13:36:07.260  6562  6617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:36:07.263  6562  6617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:36:07.263  6562  6617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:36:07.263  6562  6617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:36:07.263  6562  6617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:36:07.263  6562  6617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:36:07.263  6562  6617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 13:36:07.263  6562  6617 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:36:07.263  6562  6617 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:36:07.263  6562  6617 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:36:07.263  6562  6617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:36:07.263  6562  6617 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:36:07.263  6562  6617 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 13:36:07.265  6562  6562 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:36:07.266  6562  6562 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:36:07.269  1036  1963 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 13:36:07.269  1036  1963 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
09-09 13:36:07.269  1036  1112 D BluetoothManagerService: Message: 2
09-09 13:36:07.274  6562  6617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:36:07.275  1036  1944 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 13:36:07.275  1036  1944 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,09-09 13:36:07.291  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-09 13:36:07.292  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-09 13:36:07.292  1036  1036 D Ulp_jni : JNI:system_update. Event-4
09-09 13:36:07.292  1036  1112 D BluetoothManagerService: Message: 1
09-09 13:36:07.293  1036  1112 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
09-09 13:36:07.320  1036  1112 D BluetoothManagerService: Message: 20
09-09 13:36:07.320  1036  1112 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2299aee:true
,09-09 13:36:07.324  7358  7358 D BluetoothAdapterState: make
09-09 13:36:07.328  7358  7358 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
09-09 13:36:07.328  7358  7358 I bluedroid-qcom: init
09-09 13:36:07.330  7358  7393 I BluetoothAdapterState: Entering OffState
09-09 13:36:07.330  7358  7358 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-09 13:36:07.330  7358  7358 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-09 13:36:07.330  7358  7358 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-09 13:36:07.330  7358  7358 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-09 13:36:07.330  7358  7358 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
09-09 13:36:07.332  7358  7358 I bluedroid-qcom: get_profile_interface socket
09-09 13:36:07.332  7358  7358 I bluedroid-qcom: get_profile_interface map_client
,09-09 13:36:07.336  7358  7397 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
09-09 13:36:07.331  7396  7396 W bdaddr_loader: type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6841 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-09 13:36:07.341  7358  7397 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
09-09 13:36:07.331  7396  7396 W bdaddr_loader: type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6841 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-09 13:36:07.348  1036  1036 D BluetoothManagerService: Bluetooth Adapter name changed to G3
09-09 13:36:07.348  1036  1036 D BluetoothManagerService: Stored Bluetooth name: G3
,09-09 13:36:07.355  7396  7396 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
09-09 13:36:07.355  7396  7396 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
09-09 13:36:07.355  7396  7396 I LGFTMITEM: [GET_FTM][id=8], offset=16384
09-09 13:36:07.359  1036  1036 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
09-09 13:36:07.359  1036  1112 D BluetoothManagerService: Message: 40
09-09 13:36:07.359  1036  1112 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
09-09 13:36:07.360  7358  7376 I bluedroid-qcom: config_hci_snoop_log
,09-09 13:36:07.363  7396  7396 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
09-09 13:36:07.365  1036  1112 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
09-09 13:36:07.365  1036  1112 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
09-09 13:36:07.374  7396  7396 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
,09-09 13:36:07.374  7396  7396 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
09-09 13:36:07.387  7358  7397 D BluetoothAdapterProperties: Name is: G3
09-09 13:36:07.389  7358  7393 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
09-09 13:36:07.389  7358  7393 D BluetoothAdapterProperties: Setting state to 11
09-09 13:36:07.390  7358  7393 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
,09-09 13:36:07.391  1036  1112 D BluetoothManagerService: Message: 60
09-09 13:36:07.391  1036  1112 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
09-09 13:36:07.391  1036  1112 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
09-09 13:36:07.392  7358  7393 I LGBluetoothServiceJni: classInitNative: succeeds
09-09 13:36:07.396  1945  1945 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-09 13:36:07.396  1605  1605 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-09 13:36:07.398  6804  6804 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
09-09 13:36:07.399  7358  7393 D BluetoothBondStateMachine: make
09-09 13:36:07.404  6562  6562 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:36:07.404  7358  7358 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-09 13:36:07.404  7358  7358 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-09 13:36:07.404  7358  7358 V BluetoothPbapReceiver: ***********state = 11
,09-09 13:36:07.407  6562  6562 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:36:07.408  7358  7393 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d28622
09-09 13:36:07.409  2180  2180 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-09 13:36:07.409  7358  7393 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
09-09 13:36:07.409  7358  7393 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d28622
09-09 13:36:07.409  7358  7393 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
09-09 13:36:07.409  7358  7393 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
09-09 13:36:07.410  6562  6562 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:36:07.411  7358  7412 I BluetoothBondStateMachine: StableState(): Entering Off State
09-09 13:36:07.413  7358  7393 E BluetoothAdapterService: File transfer profiles supported!!
09-09 13:36:07.422  7358  7358 D HeadsetService: Received start request. Starting profile...
09-09 13:36:07.423  7358  7393 E BluetoothAdapterService: File transfer profiles supported!!
09-09 13:36:07.423  7358  7358 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
09-09 13:36:07.423  7358  7358 D LGBluetoothHfpAdapter: Version 1.6
09-09 13:36:07.428  7358  7358 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
09-09 13:36:07.429  7358  7358 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-09 13:36:07.429  7358  7358 D HeadsetStateMachine: make
,09-09 13:36:07.435  7358  7393 E BluetoothAdapterService: File transfer profiles supported!!
09-09 13:36:07.437  6804  6804 D BluetoothPermissionRequest: onReceive
09-09 13:36:07.442  7358  7393 E BluetoothAdapterService: File transfer profiles supported!!
09-09 13:36:07.442  6804  6804 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-09 13:36:07.455  7358  7393 E BluetoothAdapterService: File transfer profiles supported!!
,09-09 13:36:07.461  7358  7393 E BluetoothAdapterService: File transfer profiles supported!!
09-09 13:36:07.468  7358  7393 E BluetoothAdapterService: File transfer profiles supported!!
,09-09 13:36:07.469  7358  7358 D LgDataFeature: LgDataFeature() Constructor: none
09-09 13:36:07.469  7358  7358 D LgDataFeature: LgDataFeature() Constructor Done, null
09-09 13:36:07.473  7358  7358 D HeadsetStateMachine: max_hf_connections = 1
09-09 13:36:07.473  7358  7358 I bluedroid-qcom: get_profile_interface handsfree
09-09 13:36:07.475  7358  7358 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
09-09 13:36:07.476   315  2170 V AudioPolicyService: registerClient() client 0xb1508640, uid 1002
09-09 13:36:07.476   315  1403 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
09-09 13:36:07.476   315  1403 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-09 13:36:07.476   315  1403 V AudioPolicyManagerEx: getOutput() returns output 2
09-09 13:36:07.476  7358  7358 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
09-09 13:36:07.477   315  2164 V AudioFlinger: registerClient() client 0xb14331a8, pid 7358
09-09 13:36:07.477   315  1397 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-09 13:36:07.477   315  1397 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-09 13:36:07.477  1857  1872 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-09 13:36:07.477  1857  1872 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-09 13:36:07.477  3423  3439 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-09 13:36:07.477  3423  3439 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-09 13:36:07.477  1036  1962 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-09 13:36:07.477  1036  1962 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-09 13:36:07.477  7358  7374 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-09 13:36:07.477  1605  1626 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-09 13:36:07.478  1605  1626 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-09 13:36:07.478   315  1398 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-09 13:36:07.478   315  1398 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-09 13:36:07.478  1036  1981 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-09 13:36:07.478  1036  1981 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-09 13:36:07.478  1605  1624 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-09 13:36:07.478  1605  1624 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-09 13:36:07.478  1857  1873 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-09 13:36:07.478  1857  1873 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-09 13:36:07.478  3423  3438 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-09 13:36:07.478  3423  3438 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-09 13:36:07.479  7358  7374 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
09-09 13:36:07.479  7358  7374 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-09 13:36:07.479  7358  7374 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
09-09 13:36:07.479  7358  7358 V ToneGenerator: Create Track: 0xb4928a80
09-09 13:36:07.479  7358  7358 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
09-09 13:36:07.479  7358  7358 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
09-09 13:36:07.479   315  1402 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
09-09 13:36:07.479   315  1402 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
09-09 13:36:07.479   315  1402 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice,
09-09 13:36:07.479   315  1402 V AudioPolicyManagerEx: getOutput() returns output 2
09-09 13:36:07.479   315  2170 I AudioFlinger: isAudioPlaybackHookOn() false
09-09 13:36:07.479   315  1403 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
09-09 13:36:07.479   315  1403 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
09-09 13:36:07.479   315  1403 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-09 13:36:07.479   315  1403 V AudioPolicyManagerEx: getOutput() returns output 2
09-09 13:36:07.479  7358  7358 V AudioSystem: getLatency() output 2, latency 50
09-09 13:36:07.480  7358  7358 V AudioSystem: getFrameCount() output 2, frameCount 960
09-09 13:36:07.480  7358  7358 V AudioTrack: createTrack_l() output 2 afLatency 50
09-09 13:36:07.480   315  2164 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
09-09 13:36:07.480   315  2164 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
09-09 13:36:07.480   315  2164 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
09-09 13:36:07.480   315  2164 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
09-09 13:36:07.480   315  2164 V AudioFlinger: createTrack() lSessionId: 20
09-09 13:36:07.481  7358  7358 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
09-09 13:36:07.481   315  2164 V AudioFlinger: acquiring 20 from 7358, for 7358
09-09 13:36:07.481   315  2164 V AudioFlinger:  added new entry for 20
09-09 13:36:07.481  7358  7358 V ToneGenerator: ToneGenerator INIT OK, time: 140195
09-09 13:36:07.481  7358  7358 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d28622
09-09 13:36:07.482  7358  7415 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
09-09 13:36:07.482  7358  7415 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-09 13:36:07.482  7358  7415 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-09 13:36:07.482  7358  7415 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
09-09 13:36:07.482  7358  7358 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d28622
09-09 13:36:07.482   315   315 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7358
09-09 13:36:07.483   315   315 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
09-09 13:36:07.483   315   315 V voice   : voice_set_parameters: enter: bt_samplerate=8000
09-09 13:36:07.483   315   315 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
09-09 13:36:07.483   315   315 V compress_voip: voice_extn_compress_voip_set_parameters: exit
09-09 13:36:07.483   315   315 V voice   : voice_set_parameters: exit with code(0)
09-09 13:36:07.483   315   315 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
09-09 13:36:07.483   315   315 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
09-09 13:36:07.483   315   315 V msm8974_platform: platform_set_parameters: exit with code(0)
09-09 13:36:07.483   315   315 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
09-09 13:36:07.483   315   315 V audio_hw_primary: adev_set_parameters: exit with code(0)
09-09 13:36:07.483   315   315 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
09-09 13:36:07.483  7358  7415 V ToneGenerator: ToneGenerator destructor
09-09 13:36:07.483  7358  7415 V ToneGenerator: stopTone
09-09 13:36:07.483  7358  7415 V ToneGenerator: Delete Track: 0xb4928a80
09-09 13:36:07.483  7358  7415 V AudioTrack: ~AudioTrack, releasing session id from 7358 on behalf of 7358
09-09 13:36:07.484   315  1403 V AudioFlinger: releasing 20 from 7358 for 7358
09-09 13:36:07.484   315  1403 V AudioFlinger:  decremente,d refcount to 0
09-09 13:36:07.484   315  1403 V AudioFlinger: purging stale effects
09-09 13:36:07.484   315  1403 V AudioPolicyService: AudioCommandThread() adding release output 2
09-09 13:36:07.484   315  1403 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
09-09 13:36:07.484   315  1274 V AudioPolicyService: AudioCommandThread() waking up
09-09 13:36:07.484   315  1274 V AudioPolicyService: AudioCommandThread() processing release output 2
09-09 13:36:07.484   315  1274 V AudioPolicyManager: releaseOutput() 2
09-09 13:36:07.484   315  1274 V AudioPolicyService: AudioCommandThread() going to sleep
09-09 13:36:07.484   315  1403 V AudioFlinger: PlaybackThread::Track destructor
09-09 13:36:07.484   315  1403 V AudioFlinger: removeClient_l() pid 7358, calling pid 315
09-09 13:36:07.484  7358  7358 D A2dpService: Received start request. Starting profile...
09-09 13:36:07.484  7358  7393 V LGMDMManager: Create singleton instance
09-09 13:36:07.485  7358  7358 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-09 13:36:07.485  7358  7358 V Avrcp   : make
09-09 13:36:07.486  7358  7358 D Avrcp   : [BTUI] Use Native AVRCP : init jni
09-09 13:36:07.486  7358  7358 I bluedroid-qcom: get_profile_interface avrcp
09-09 13:36:07.487  1036  1616 W Process : Unable to open /proc/7418/status
09-09 13:36:07.488  7358  7393 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
09-09 13:36:07.494  7358  7358 V AudioManager: registerRemoteController: size of Media player list: 0
09-09 13:36:07.495  7358  7358 E AudioManager: No RCC entry present to update
09-09 13:36:07.495  7358  7358 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
09-09 13:36:07.498  7358  7358 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
09-09 13:36:07.500  7358  7358 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
09-09 13:36:07.500  7358  7358 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
,09-09 13:36:07.503  7358  7358 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
09-09 13:36:07.589  1036  1052 V SIM_STK : Menu title from STK is T-Mobile
09-09 13:36:07.589  1036  1052 V SIM_STK : Menu title from STK is T-Mobile
,09-09 13:36:07.696  1036  1616 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,09-09 13:36:07.704  7358  7358 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
09-09 13:36:07.708  7358  7358 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
09-09 13:36:07.709  7358  7358 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
09-09 13:36:07.709  7358  7358 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
09-09 13:36:07.709  7358  7358 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
,09-09 13:36:07.709  7358  7358 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-09 13:36:07.709  7358  7358 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
09-09 13:36:07.709  7358  7358 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
09-09 13:36:07.709  7358  7358 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
09-09 13:36:07.709  7358  7358 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-09 13:36:07.709  7358  7358 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
09-09 13:36:07.710  7358  7358 I BluetoothA2dpServiceJni: classInitNative
,09-09 13:36:07.710  7358  7358 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-09 13:36:07.710  7358  7358 D A2dpStateMachine: make
09-09 13:36:07.712  7358  7358 I bluedroid-qcom: get_profile_interface a2dp
09-09 13:36:07.712  7358  7422 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
09-09 13:36:07.715  7358  7358 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
09-09 13:36:07.715  7358  7358 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
09-09 13:36:07.716  7358  7358 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d28622
09-09 13:36:07.716  7358  7421 D A2dpStateMachine: Enter Disconnected: -2
09-09 13:36:07.717  7358  7358 I BluetoothHidServiceJni: classInitNative: succeeds
09-09 13:36:07.718  7358  7358 D HidService: Received start request. Starting profile...
09-09 13:36:07.718  7358  7358 I bluedroid-qcom: get_profile_interface hidhost
09-09 13:36:07.718  7358  7358 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d28622
09-09 13:36:07.719  7358  7358 I BluetoothHealthServiceJni: classInitNative: succeeds
09-09 13:36:07.720  7358  7358 D HealthService: Received start request. Starting profile...
09-09 13:36:07.724  7358  7358 I bluedroid-qcom: get_profile_interface health
09-09 13:36:07.724  7358  7358 I LGBluetoothHealthServiceJni: classInitNative: succeeds
09-09 13:36:07.724  7358  7358 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d28622
,09-09 13:36:07.725  7358  7358 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-09 13:36:07.727  7358  7358 D PanService: Received start request. Starting profile...
09-09 13:36:07.728  7358  7358 D BluetoothPanServiceJni: initializeNative(L110): pan
09-09 13:36:07.728  7358  7358 I bluedroid-qcom: get_profile_interface pan
09-09 13:36:07.742  7358  7358 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
09-09 13:36:07.742  7358  7358 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d28622
,09-09 13:36:07.746  7358  7358 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
09-09 13:36:07.761  7358  7358 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-09 13:36:07.762  7358  7358 D BtGatt.GattService: Received start request. Starting profile...
09-09 13:36:07.762  7358  7358 D BtGatt.GattService: start()
09-09 13:36:07.763  7358  7358 I bluedroid-qcom: get_profile_interface gatt
09-09 13:36:07.764  7358  7358 D BtGatt.AdvertiseManager: advertise manager created
09-09 13:36:07.775  7358  7358 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d28622
,09-09 13:36:07.778  7358  7358 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d28622
,09-09 13:36:07.778  7358  7358 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
09-09 13:36:07.779  7358  7358 V BluetoothMapService: BluetoothMapBinder()
09-09 13:36:07.780  7358  7358 D BluetoothMapService: Received start request. Starting profile...
09-09 13:36:07.780  7358  7358 D BluetoothMapService: start()
09-09 13:36:07.784  7358  7358 D BluetoothMapEmailSettingsLoader: Found 0 applications
09-09 13:36:07.784  7358  7358 D BluetoothMapEmailAppObserver: createReceiver()
09-09 13:36:07.786  7358  7358 D BluetoothMapEmailAppObserver: initObservers()
09-09 13:36:07.786  7358  7358 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
09-09 13:36:07.795  7358  7358 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d28622
,09-09 13:36:07.796  7358  7358 D HeadsetStateMachine: Proxy object connected
09-09 13:36:07.797  7358  7358 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
09-09 13:36:07.797  7358  7358 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
09-09 13:36:07.801  7358  7415 D HeadsetStateMachine: Disconnected process message: 10, size: 0
09-09 13:36:07.802  7358  7415 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-09 13:36:07.803  7358  7415 D HeadsetStateMachine: Disconnected process message: 11, size: 0
09-09 13:36:07.805  7358  7358 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-09 13:36:07.810  7358  7358 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,09-09 13:36:07.813  7358  7358 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-09 13:36:07.816  7358  7358 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-09 13:36:07.823  7358  7358 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-09 13:36:07.823  7358  7358 V PanService: [BTUI] SIM Extra State :ABSENT
09-09 13:36:07.827  7358  7358 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,09-09 13:36:07.830  7358  7358 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
09-09 13:36:07.831  7358  7358 V BluetoothMapService: Handler(): got msg=1
09-09 13:36:07.832  7358  7358 V BluetoothSapReceiver: [BTUI] checkServiceStart
,09-09 13:36:07.832  7358  7358 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-09 13:36:07.832  7358  7358 V BluetoothSapReceiver: SapReceiver onReceive 
09-09 13:36:07.832  7358  7358 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-09 13:36:07.832  7358  7358 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
09-09 13:36:07.832  7358  7393 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
09-09 13:36:07.832  7358  7393 I bluedroid-qcom: enable
09-09 13:36:07.833  7358  7433 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
09-09 13:36:07.835  7358  7433 I bt-btu  : btu_task pending for preload complete event
09-09 13:36:07.836  7358  7393 I bt_hci_bdroid: init
09-09 13:36:07.837  7358  7393 I bt_vendor: bt-vendor : init
09-09 13:36:07.837  7358  7393 I bt_vendor: bt-vendor : get_bt_soc_type
09-09 13:36:07.837  7358  7393 E bt_vendor: get_bt_soc_type: Failed to get soc type
09-09 13:36:07.838  7358  7393 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
09-09 13:36:07.838  7358  7393 D bt_userial_mct: userial_init
09-09 13:36:07.840  7358  7393 D bt_hci_bdroid: set_power 1
09-09 13:36:07.840  7358  7393 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
09-09 13:36:07.840  7358  7393 I bt_vendor: Starting hciattach daemon
09-09 13:36:07.840  7358  7393 I bt_vendor: try to set true
09-09 13:36:07.831  7436  7436 W sh      : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6841 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-09 13:36:07.831  7436  7436 W sh      : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6841 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-09 13:36:07.880  7437  7437 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,09-09 13:36:08.007  7443  7443 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,09-09 13:36:08.022  7444  7444 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,09-09 13:36:08.058  7446  7446 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-09 13:36:08.081  7447  7447 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,09-09 13:36:08.097  7448  7448 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
09-09 13:36:08.110  7449  7449 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,09-09 13:36:08.150  7451  7451 I libmdmdetect: ESOC framework not supported
,09-09 13:36:08.152  7451  7451 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,09-09 13:36:08.163  7451  7451 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
,09-09 13:36:08.163  7451  7451 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
,09-09 13:36:08.163  7451  7451 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
,09-09 13:36:08.163  7451  7451 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
,09-09 13:36:08.163  7451  7451 D bthci_qcomm_common: [BTUI]     LE: Class 2
09-09 13:36:08.163  7451  7451 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
09-09 13:36:08.164  7451  7451 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
,09-09 13:36:08.225  7451  7455 E QC-QMI  : qmi_client [7451] 14: failed to locate client data
09-09 13:36:08.228   484   484 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
09-09 13:36:08.228   484   484 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
,09-09 13:36:08.248  7459  7459 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,09-09 13:36:08.264  7460  7460 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,09-09 13:36:08.294  7358  7393 I bt_vendor: bluetooth satus is on
09-09 13:36:08.294  7358  7393 D bt_hci_bdroid: preload
09-09 13:36:08.294  7358  7435 D bt_userial_mct: userial_open(port:0)
09-09 13:36:08.294  7358  7435 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,09-09 13:36:08.299  7358  7435 I bt_vendor: Done intiailizing UART
,09-09 13:36:08.299  7358  7435 I bt_vendor: Done intiailizing UART
09-09 13:36:08.299  7358  7435 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
,09-09 13:36:08.299  7358  7435 I bt_vendor: Bluetooth Firmware and transport layer are initialized
09-09 13:36:08.299  7358  7433 I bt-btu  : btu_task received preload complete event
,09-09 13:36:08.300  7358  7433 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001,
09-09 13:36:08.300  7358  7433 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
09-09 13:36:08.302  7358  7433 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003,
09-09 13:36:08.304  7358  7462 D bt_userial_mct: Entering userial_read_thread()
09-09 13:36:08.305  7358  7433 I         : BTE_InitTraceLevels -- TRC_HCI,
09-09 13:36:08.305  7358  7433 I         : BTE_InitTraceLevels -- TRC_L2CAP
,09-09 13:36:08.305  7358  7433 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,09-09 13:36:08.305  7358  7433 I         : BTE_InitTraceLevels -- TRC_AVDT
09-09 13:36:08.305  7358  7433 I         : BTE_InitTraceLevels -- TRC_AVRC
,09-09 13:36:08.305  7358  7433 I         : BTE_InitTraceLevels -- TRC_A2D,
,09-09 13:36:08.305  7358  7433 I         : BTE_InitTraceLevels -- TRC_BNEP
,09-09 13:36:08.305  7358  7433 I         : BTE_InitTraceLevels -- TRC_BTM
09-09 13:36:08.305  7358  7433 I         : BTE_InitTraceLevels -- TRC_HID_HOST
09-09 13:36:08.305  7358  7433 I         : BTE_InitTraceLevels -- TRC_GAP
09-09 13:36:08.305  7358  7433 I         : BTE_InitTraceLevels -- TRC_PAN
09-09 13:36:08.305  7358  7433 I         : BTE_InitTraceLevels -- TRC_SDP
09-09 13:36:08.305  7358  7433 I         : BTE_InitTraceLevels -- TRC_GATT
09-09 13:36:08.306  7358  7433 I         : BTE_InitTraceLevels -- TRC_SMP
,09-09 13:36:08.306  7358  7433 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-09 13:36:08.306  7358  7433 I         : BTE_InitTraceLevels -- TRC_BTIF
09-09 13:36:08.405  7358  7433 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
09-09 13:36:08.405  7358  7433 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa020e061 
09-09 13:36:08.405  7358  7433 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa020e061 
,09-09 13:36:08.450  7358  7397 E bt-btif : Calling BTA_HhEnable
09-09 13:36:08.450  7358  7397 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
09-09 13:36:08.451  7358  7397 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,09-09 13:36:08.454  7358  7397 D BluetoothAdapterProperties: Name is: G3
09-09 13:36:08.456  1036  1036 D BluetoothManagerService: Bluetooth Adapter name changed to G3
09-09 13:36:08.456  1036  1036 D BluetoothManagerService: Stored Bluetooth name: G3
09-09 13:36:08.456  7358  7397 D BluetoothAdapterProperties: Scan Mode:20
09-09 13:36:08.457  7358  7397 D BluetoothAdapterProperties: Discoverable Timeout:120
09-09 13:36:08.457  7358  7397 D bt_hci_bdroid: postload
09-09 13:36:08.458  7358  7397 D bte_conf: Device ID record 1 : primary
09-09 13:36:08.458  7358  7397 D bte_conf:   vendorId            = 00c4
09-09 13:36:08.458  7358  7397 D bte_conf:   vendorIdSource      = 0001
09-09 13:36:08.458  7358  7397 D bte_conf:   product             = 13a1
09-09 13:36:08.458  7358  7397 D bte_conf:   version             = 1000
09-09 13:36:08.458  7358  7397 D bte_conf:   clientExecutableURL = 
09-09 13:36:08.458  7358  7397 D bte_conf:   serviceDescription  = 
09-09 13:36:08.458  7358  7397 D bte_conf:   documentationURL    = 
09-09 13:36:08.459  7358  7435 D bt_hci_bdroid: Used up Tx Cmd credits
09-09 13:36:08.459  7358  7397 D bte_conf: bte_load_did_conf no section named DID2.
09-09 13:36:08.462  7358  7393 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
09-09 13:36:08.462  7358  7393 D BluetoothAdapterProperties: ScanMode =  20
09-09 13:36:08.462  7358  7393 D BluetoothAdapterProperties: State =  11
09-09 13:36:08.462  7358  7393 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
09-09 13:36:08.463  7358  7393 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
09-09 13:36:08.463  7358  7393 D BluetoothAdapterProperties: Setting state to 12
09-09 13:36:08.463  7358  7393 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-09 13:36:08.464  7358  7397 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,09-09 13:36:08.461  7464  7464 W sh      : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6841 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-09 13:36:08.461  7464  7464 W sh      : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6841 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-09 13:36:08.487  1036  1112 D BluetoothManagerService: Message: 60
09-09 13:36:08.487  1036  1112 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
09-09 13:36:08.487  1036  1112 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
,09-09 13:36:08.497  7358  7397 D BluetoothAdapterProperties: Discoverable Timeout:120
09-09 13:36:08.498  7358  7397 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
09-09 13:36:08.498  6562  6562 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:36:08.498  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:36:08.498  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:36:08.498  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:36:08.498  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:36:08.498  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:36:08.498  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:36:08.498  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:36:08.506  7358  7393 I BluetoothAdapterState: Entering On State
,09-09 13:36:08.511  6562  6562 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:36:08.518  6562  6562 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:36:08.518  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:36:08.518  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:36:08.518  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:36:08.518  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:36:08.518  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:36:08.518  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:36:08.518  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:36:08.522  7358  7435 D bt_hci_bdroid: Used up Tx Cmd credits
09-09 13:36:08.526  6562  6562 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:36:08.530  7358  7462 E bt_mct  : hci lib postload completed
,09-09 13:36:08.541  6562  6562 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:36:08.541  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:36:08.541  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:36:08.541  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:36:08.541  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:36:08.541  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:36:08.541  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:36:08.541  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:36:08.547  7358  7393 D LGBluetoothServiceAdapter: [BTUI] OnState
09-09 13:36:08.547  7358  7393 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
09-09 13:36:08.547  7358  7393 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
,09-09 13:36:08.549  7358  7393 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
09-09 13:36:08.553  6562  6562 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:36:08.555  7358  7433 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
09-09 13:36:08.555  7358  7433 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
09-09 13:36:08.555  7358  7433 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
09-09 13:36:08.556  7358  7433 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
09-09 13:36:08.556  7358  7433 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
09-09 13:36:08.556  7358  7393 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
09-09 13:36:08.556  7358  7433 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
09-09 13:36:08.556  7358  7397 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-09 13:36:08.567  6804  6820 D BluetoothMap: onBluetoothStateChange: up=true
,09-09 13:36:08.579  1857  4431 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-09 13:36:08.584  7358  7433 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-09 13:36:08.584  7358  7433 W bt-smp  : Plain text(LSB ~ MSB) = 92 8d 71 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-09 13:36:08.584  7358  7433 W bt-smp  : Encrypted text(LSB ~ MSB) = 4f df 2a 0e 8c 26 9a d1 6b 39 cf 21 64 3d 25 19 
09-09 13:36:08.584  7358  7433 W bt-btm  : Stopping oneshot timer
09-09 13:36:08.589  6804  6804 D BluetoothMap: Proxy object connected
09-09 13:36:08.589  6804  6804 D MapProfile: Bluetooth service connected
09-09 13:36:08.589  6804  6804 D BluetoothMap: getConnectedDevices()
09-09 13:36:08.592  1036  1112 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-09 13:36:08.595  1857  1857 D BluetoothHeadset: Proxy object connected
09-09 13:36:08.597  1857  1873 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 13:36:08.599  1036  1036 D BluetoothA2dp: Proxy object connected
09-09 13:36:08.600  7358  7374 V BluetoothMapService: getConnectedDevices()
09-09 13:36:08.601  1857  1857 D BluetoothHeadset: Proxy object connected
09-09 13:36:08.601  6804  6820 D BluetoothPan: onBluetoothStateChange on: true
09-09 13:36:08.601  6804  6820 D BluetoothPan: onBluetoothStateChange call bindService
09-09 13:36:08.607  1857  4431 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 13:36:08.607  6804  6804 D BluetoothPan: BluetoothPAN Proxy object connected
09-09 13:36:08.607  6804  6804 D PanProfile: Bluetooth service connected
,09-09 13:36:08.609  7358  7433 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-09 13:36:08.609  7358  7433 W bt-smp  : Plain text(LSB ~ MSB) = 3a 10 4b 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-09 13:36:08.609  7358  7433 W bt-smp  : Encrypted text(LSB ~ MSB) = 13 c9 92 ce 90 bd b6 02 93 0f be e2 77 02 8c 4e 
09-09 13:36:08.609  7358  7433 W bt-btm  : Stopping oneshot timer
09-09 13:36:08.611  1857  1857 D BluetoothHeadset: Proxy object connected
09-09 13:36:08.611  7485  7485 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
09-09 13:36:08.611  1036  1112 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 13:36:08.612  1036  1036 D BluetoothHeadset: Proxy object connected
09-09 13:36:08.614  6804  6819 D BluetoothPbap: onBluetoothStateChange: up=true
09-09 13:36:08.616  6804  6820 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-09 13:36:08.619  1036  1112 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
09-09 13:36:08.619  1036  1112 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
09-09 13:36:08.620  6804  6804 D BluetoothInputDevice: Proxy object connected
09-09 13:36:08.620  6804  6804 D HidProfile: Bluetooth service connected
,09-09 13:36:08.622  1605  1605 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-09 13:36:08.622  7358  7433 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-09 13:36:08.622  7358  7433 W bt-smp  : Plain text(LSB ~ MSB) = 74 1d 7e 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-09 13:36:08.622  7358  7433 W bt-smp  : Encrypted text(LSB ~ MSB) = 79 77 c3 cf 3c d9 9b 3d 75 cd e3 6b 2d 03 d5 79 
09-09 13:36:08.622  7358  7433 W bt-btm  : Stopping oneshot timer
09-09 13:36:08.626  1945  1945 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-09 13:36:08.627  1945  2103 D LGBluetoothAPIService: Message: 1
09-09 13:36:08.627  1945  2103 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
09-09 13:36:08.627  1945  2103 D LGBluetoothAPIService: Calling onBluetoothServiceUp callbacks
09-09 13:36:08.627  1945  2103 D LGBluetoothAPIService: Broadcasting onBluetoothServiceUp() to 0 receivers.
09-09 13:36:08.629  1036  1036 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
,09-09 13:36:08.629  1036  1112 D BluetoothManagerService: Message: 40
09-09 13:36:08.629  1036  1112 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
09-09 13:36:08.630  6562  6562 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
09-09 13:36:08.633  7358  7433 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-09 13:36:08.633  7358  7433 W bt-smp  : Plain text(LSB ~ MSB) = 2f f3 44 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-09 13:36:08.633  7358  7433 W bt-smp  : Encrypted text(LSB ~ MSB) = 4c 97 a0 3b c0 e6 e1 ac 4b b8 70 09 e0 79 ec 05 
09-09 13:36:08.633  7358  7433 W bt-btm  : Stopping oneshot timer
,09-09 13:36:08.636  7358  7358 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-09 13:36:08.636  7358  7358 D BluetoothMapService: STATE_ON
09-09 13:36:08.637  6804  6804 D LocalBluetoothProfileManager: Adding local A2DP profile
09-09 13:36:08.639  1036  1112 D BluetoothManagerService: Message: 30
09-09 13:36:08.639  6562  6562 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:36:08.642  6562  6562 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:36:08.643  6804  6804 D LocalBluetoothProfileManager: Adding local HEADSET profile
09-09 13:36:08.644  6562  6562 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:36:08.645  7358  7433 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-09 13:36:08.646  7358  7433 W bt-smp  : Plain text(LSB ~ MSB) = 41 e3 52 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-09 13:36:08.646  7358  7433 W bt-smp  : Encrypted text(LSB ~ MSB) = 80 2b b2 20 e5 7e 15 53 cb 30 af ac 22 fe f1 d1 
09-09 13:36:08.646  7358  7433 W bt-btm  : Stopping oneshot timer
,09-09 13:36:08.648  1036  1112 D BluetoothManagerService: Message: 30
09-09 13:36:08.653  6804  6804 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
09-09 13:36:08.654  6804  6804 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-09 13:36:08.655  7358  7358 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d28622
09-09 13:36:08.655  7358  7358 V BluetoothPbapService: Pbap Service onCreate
09-09 13:36:08.655  7358  7358 V BluetoothPbapService: Starting PBAP service
09-09 13:36:08.656  7358  7358 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
09-09 13:36:08.657  7358  7358 V BluetoothPbapService: Pbap Service onBind
09-09 13:36:08.657  6804  6804 D BluetoothA2dp: Proxy object connected
09-09 13:36:08.657  7358  7358 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-09 13:36:08.658  7358  7358 V BluetoothPbapService: state: 12
09-09 13:36:08.658  7358  7358 V BluetoothMapService: Handler(): got msg=1
,09-09 13:36:08.659  7358  7358 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
09-09 13:36:08.659  7358  7358 V BluetoothPbapService: Handler(): got msg=1
09-09 13:36:08.660  7358  7358 V BluetoothPbapService: Pbap Service startRfcommSocketListener
09-09 13:36:08.660  6804  6804 D A2dpProfile: Bluetooth service connected
09-09 13:36:08.660  7358  7358 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-09 13:36:08.660  7358  7358 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-09 13:36:08.660  7358  7358 V BluetoothPbapReceiver: ***********state = 12
09-09 13:36:08.661  7358  7490 D BluetoothMapMasInstance: MAS initSocket()
09-09 13:36:08.662  7358  7490 D BluetoothMapMasInstance:   masId = 00
09-09 13:36:08.662  7358  7490 D BluetoothMapMasInstance:   msgTypes = 0e
09-09 13:36:08.662  7358  7490 D BluetoothMapMasInstance:   masName = SMS/MMS
09-09 13:36:08.662  7358  7490 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
09-09 13:36:08.663  6804  6804 D BluetoothHeadset: Proxy object connected
09-09 13:36:08.663  1036  2036 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 13:36:08.664  6804  6804 D HeadsetProfile: Bluetooth service connected
09-09 13:36:08.664  2180  2180 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-09 13:36:08.664  7358  7491 V BluetoothPbapService: Pbap Service initSocket
09-09 13:36:08.666  2180  2180 D c       : Getting all permits...
09-09 13:36:08.666  7358  7490 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 13:36:08.666  2180  2180 D a       : Opening database...
09-09 13:36:08.670  2180  2180 D a       : Opening database auth.proximity.permit_store...
,09-09 13:36:08.672  1036  1999 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 13:36:08.673  7358  7397 D BluetoothAdapterProperties: Scan Mode:21
09-09 13:36:08.673  2180  2180 D a       : Closing database...
09-09 13:36:08.673  7358  7490 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
09-09 13:36:08.673  7358  7490 V BluetoothMapMasInstance: Succeed to create listening socket 
09-09 13:36:08.673  7358  7490 D BluetoothMapMasInstance: Accepting socket connection...
09-09 13:36:08.674  7358  7397 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
09-09 13:36:08.675  7358  7491 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 13:36:08.676  6562  6562 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:36:08.678  6562  6562 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:36:08.679  7358  7491 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
09-09 13:36:08.679  6804  6804 D BluetoothPbap: Proxy object connected
09-09 13:36:08.679  7358  7491 V BluetoothPbapService: Succeed to create listening socket 
09-09 13:36:08.679  7358  7491 V BluetoothPbapService: Accepting socket connection...
09-09 13:36:08.680  6804  6804 D PbapServerProfile: Bluetooth service connected
09-09 13:36:08.680  6562  6562 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:36:08.684  6804  6804 D DockEventReceiver: finishStartingService: stopping service
,09-09 13:36:08.690  6804  6804 D BluetoothPermissionRequest: onReceive
09-09 13:36:08.692  6804  6804 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
09-09 13:36:08.693  6804  6804 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-09 13:36:08.697  7358  7358 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
,09-09 13:36:08.699  7358  7358 I LGBluetoothOppAdapter: [BTUI] startOppService()
,09-09 13:36:08.704  7358  7358 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
09-09 13:36:08.723  7358  7358 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
09-09 13:36:08.723  7358  7358 V BtOppService: onCreate
,09-09 13:36:08.727  7358  7358 V BluetoothOppNotification: send message
09-09 13:36:08.730  7358  7358 V BtOppService: Starting RfcommListener
09-09 13:36:08.737  7358  7358 D BluetoothOppPreference: Dumping Names:  
,09-09 13:36:08.738  7358  7358 D BluetoothOppPreference: {}
09-09 13:36:08.738  7358  7358 D BluetoothOppPreference: Dumping Channels:  
09-09 13:36:08.738  7358  7358 D BluetoothOppPreference: {}
09-09 13:36:08.739  7358  7358 V BtOppService: onStartCommand
09-09 13:36:08.743  7358  7498 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-09 13:36:08.745  7358  7358 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-09 13:36:08.745  7358  7358 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
09-09 13:36:08.748  7358  7495 V BtOppService: Deleted complete outbound shares, number =  0
09-09 13:36:08.749  7358  7358 V BluetoothOppNotification: new notify threadi!
09-09 13:36:08.749  7358  7498 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-09 13:36:08.750  7358  7495 V BtOppService: Deleted complete inbound failed shares, number = 0
,09-09 13:36:08.750  7358  7495 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
09-09 13:36:08.751  7358  7358 V BluetoothOppNotification: send delay message
09-09 13:36:08.752  7358  7358 V BtOppService: start RfcommListener
09-09 13:36:08.753  7358  7499 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
09-09 13:36:08.757  7358  7495 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1686287e on behalf of 
09-09 13:36:08.758  7358  7498 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@6e9d1df on behalf of 
09-09 13:36:08.761  7358  7358 V BtOppService: RfcommListener started
09-09 13:36:08.761  7358  7358 V BtOppService: ContentObserver received notification
,09-09 13:36:08.762  7358  7499 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@20fa7e2c on behalf of 
09-09 13:36:08.763  7358  7500 V BtOppRfcommListener: Starting RFCOMM listener....
09-09 13:36:08.764  1036  1963 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 13:36:08.765  7358  7499 V BluetoothOppNotification: mUpdateCompleteNotification = true
,09-09 13:36:08.766  7358  7500 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 13:36:08.768  7358  7498 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-09 13:36:08.768  7358  7498 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-09 13:36:08.768  7358  7500 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=78 mFd=75
09-09 13:36:08.768  7358  7499 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
09-09 13:36:08.768  7358  7500 V BtOppRfcommListener: Started RFCOMM listener....
09-09 13:36:08.769  7358  7500 I BtOppRfcommListener: Accept thread started.
09-09 13:36:08.770  7358  7498 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1f2150f5 on behalf of 
09-09 13:36:08.770  7358  7500 V BtOppRfcommListener: Accepting connection...
09-09 13:36:08.771  7358  7498 V BluetoothOppNotification: update too frequent, put in queue
09-09 13:36:08.772  7358  7498 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
09-09 13:36:08.772  7358  7499 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3a584e8a on behalf of 
09-09 13:36:08.774  7358  7499 V BluetoothOppNotification: outbound: succ-0  fail-0
09-09 13:36:08.777  7358  7499 V BluetoothOppNotification: outbound notification was removed.
09-09 13:36:08.777  7358  7499 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
,09-09 13:36:08.782  7358  7499 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@843acfb on behalf of 
09-09 13:36:08.783  7358  7499 V BluetoothOppNotification: inbound: succ-0  fail-0
09-09 13:36:08.788  7358  7499 V BluetoothOppNotification: inbound notification was removed.
09-09 13:36:08.789  7358  7499 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
09-09 13:36:08.789  7358  7358 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d28622
09-09 13:36:08.790  7358  7358 V BluetoothFtpService: Ftp Service onCreate
,09-09 13:36:08.790  7358  7358 I BluetoothFtpService: Ftp Service onCreate
09-09 13:36:08.791  7358  7499 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1a830771 on behalf of 
09-09 13:36:08.791  7358  7358 V BluetoothFtpService: Ftp Service onStartCommand
09-09 13:36:08.792  7358  7358 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-09 13:36:08.793  7358  7358 V BluetoothFtpService: Starting Listening on sockets
09-09 13:36:08.793  7358  7358 V BtOppService: ContentObserver received notification
09-09 13:36:08.794  7358  7358 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-09 13:36:08.794  7358  7358 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-09 13:36:08.794  7358  7358 V BluetoothSapReceiver: SapReceiver onReceive 
09-09 13:36:08.794  7358  7358 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-09 13:36:08.794  7358  7358 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
09-09 13:36:08.794  7358  7358 V BluetoothSapReceiver: Calling SAP service start service with action = null
09-09 13:36:08.796  7358  7501 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-09 13:36:08.797  7358  7501 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-09 13:36:08.797  7358  7358 V BluetoothFtpService: Handler(): got msg=1
09-09 13:36:08.798  7358  7501 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2874c956 on behalf of 
09-09 13:36:08.798  7358  7358 V BluetoothFtpService: Ftp Service startRfcommSocketListener
09-09 13:36:08.798  7358  7358 V BluetoothFtpService: Ftp Service initSocket
09-09 13:36:08.799  7358  7501 V BluetoothOppNotification: update too frequent, put in queue
09-09 13:36:08.800  7358  7501 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
09-09 13:36:08.803  1036  2036 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-09 13:36:08.804  7358  7358 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 13:36:08.808  7358  7358 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=78
09-09 13:36:08.809  7358  7358 V BluetoothFtpService: Succeed to create listening socket on channel 20
09-09 13:36:08.811  7358  7502 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
09-09 13:36:08.830  6562  6617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:36:08.830  6562  6617 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:36:08.830  6562  6617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:36:08.830  6562  6617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:36:08.830  6562  6617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 13:36:08.830  6562  6617 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@235f71fc removed from the list
09-09 13:36:08.830  6562  6617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:36:08.830  6562  6617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9468085 removed from the list
09-09 13:36:08.830  6562  6617 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:36:08.830  6562  6617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:36:08.831  6562  6617 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 13:36:08.831  6562  6617 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2940cf0b added. We now have 3 listener(s)
09-09 13:36:08.832  1036  1780 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 13:36:08.835  6562  6617 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-09 13:36:08.835  6562  6617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 13:36:08.836  6562  6617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 13:36:08.836  6562  6617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 13:36:08.836  6562  6617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d2fb1e8 added. We now have 3 listener(s)
09-09 13:36:08.836  6562  6617 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 13:36:08.836  7358  7358 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d28622
09-09 13:36:08.837  6562  6617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-09 13:36:08.837  7358  7358 V BluetoothSapService: Sap Service onCreate
09-09 13:36:08.839  7358  7358 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-09 13:36:08.839  7358  7358 V BluetoothSapService: state: 12
09-09 13:36:08.839  7358  7358 V BluetoothSapService: Starting SAP server process
09-09 13:36:08.840  6562  6617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:36:08.842  7358  7358 V BluetoothSapService: SAP Service startRfcommListenerThread
,09-09 13:36:08.845  7358  7504 V BluetoothSapService: Sap Service initRfcommSocket
,09-09 13:36:08.847  1036  1944 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 13:36:08.848  6562  6617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:36:08.848  6562  6617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:36:08.848  6562  6617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:36:08.848  6562  6617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:36:08.848  6562  6617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:36:08.848  6562  6617 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:36:08.848  6562  6617 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:36:08.848  6562  6617 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:36:08.831  7503  7503 W sapd    : type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6841 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-09 13:36:08.831  7503  7503 W sapd    : type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6841 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-09 13:36:08.849  7358  7504 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 13:36:08.851  7358  7504 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
09-09 13:36:08.851  7358  7504 V BluetoothSapService: Succeed to create listening socket 
09-09 13:36:08.851  7358  7504 V BluetoothSapService: Accepting socket connection...
09-09 13:36:08.852  6562  6617 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:36:08.852  6562  6617 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 13:36:08.854  1036  1051 D WifiServiceImplEx: setWifiEnabled: false pid=6562, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-09 13:36:08.854  1036  1051 D WifiService: setWifiEnabled: false pid=6562, uid=10118
09-09 13:36:08.855  1036  1051 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-09 13:36:08.856  7503  7503 V BT_SAP  : Event pipe created
,09-09 13:36:08.856  7503  7503 V BT_SAP  : create_server_socket qcom.sap.server
09-09 13:36:08.857  7503  7503 V BT_SAP  : created socket fd 6
09-09 13:36:08.857  6562  6562 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:36:08.860  6562  6562 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:36:08.873  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-09 13:36:08.873  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-09 13:36:08.873  1036  1036 D Ulp_jni : JNI:system_update. Event-4
09-09 13:36:08.875  1036  1392 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
09-09 13:36:08.876  1036  1392 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
09-09 13:36:08.876  1036  1392 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
09-09 13:36:08.877  1036  1392 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
09-09 13:36:08.877  1036  1392 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
09-09 13:36:08.877  1036  1392 E WifiStateMachine: WifiStateMachine: Leaving Connected state
09-09 13:36:08.877  1036  1392 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-09 13:36:08.877  1036  1392 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-09 13:36:08.878  1036  1392 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-09 13:36:08.878  1036  1392 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-09 13:36:08.885  1036  1392 D WifiNative-wlan0: SAVE_CONFIG: returned true
,09-09 13:36:08.886  1036  1389 D LGWifiP2pService: InactiveState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:36:08.886  1036  1389 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:36:08.886  1036  1392 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-09 13:36:08.887  6900  6900 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-09 13:36:08.887  1036  1392 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-09 13:36:08.887  1036  1392 D WifiNative-wlan0: doBoolean: SET ps 1
,09-09 13:36:08.888  1036  1392 D WifiNative-wlan0: SET ps 1: returned true
09-09 13:36:08.889  1036  6924 D DhcpStateMachine: RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:36:08.895   311   893 D CommandListener: Clearing all IP addresses on wlan0
09-09 13:36:08.936  1036  1435 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-09 13:36:08.936  1036  1435 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
,09-09 13:36:08.941  1036  1036 D WifiHS20: hidePasspointNotification off =false
09-09 13:36:08.946  1036  1051 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 101]) by 10005
09-09 13:36:08.946  1036  6923 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:36:08.947  1036  6923 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:36:08.947  1036  6923 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
09-09 13:36:08.947  1036  6923 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:36:08.947  1036  6923 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on <unknown ssid>
09-09 13:36:08.948  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 13:36:08.948  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 13:36:08.949  1945  1945 V WfdStateTracker: handleWifiStateChangedEvent: 0
09-09 13:36:08.949  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-09 13:36:08.950  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:36:08.950  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,09-09 13:36:08.955  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 13:36:08.962  1036  1036 D WifiHS20: hidePasspointNotification off =false
,09-09 13:36:08.967  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:36:08.968  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:36:08.968  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-09 13:36:08.969  1036  1036 D WifiScanningService: SCAN_AVAILABLE : 1
09-09 13:36:08.969  1036  1559 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:36:08.969  1036  1036 D RttService: SCAN_AVAILABLE : 1
09-09 13:36:08.969  1036  1389 D LGWifiP2pService: InactiveState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:36:08.969  1036  1389 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:36:08.969  1036  1389 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@cc9388d
09-09 13:36:08.969  1036  1560 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:36:08.970  1036  1389 D LGWifiP2pService: P2pDisablingState
09-09 13:36:08.970  1036  1392 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 13:36:08.970  1036  1389 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:36:08.970  1036  1389 D LGWifiP2pService: p2p socket connection lost
09-09 13:36:08.970  1036  1389 D LGWifiP2pService: P2pDisabledState
09-09 13:36:08.970  1036  1392 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 13:36:08.971  1036  1392 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 13:36:08.971  1036  1392 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 13:36:08.972  1945  1945 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-09 13:36:08.972  1036  1392 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 13:36:08.972  1036  1392 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 13:36:08.972  1945  1945 D WfdsService: WifiP2pState is changed : false
09-09 13:36:08.972  1945  2280 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
09-09 13:36:08.972  1036  1392 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-09 13:36:08.972  1945  2280 D WfdsService: Set the WFDS Monitor: false
09-09 13:36:08.973  1036  1392 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
09-09 13:36:08.976  1036  1389 D LGWifiP2pService: P2pDisabledState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:36:08.976  1036  1389 D LGWifiP2pService: DefaultState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:36:08.976  1036  1392 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-09 13:36:08.976  6900  6900 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-09 13:36:08.976  1036  1392 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-09 13:36:08.977  1036  1392 D WifiNative-wlan0: doBoolean: SET ps 1
09-09 13:36:08.977  1036  1392 D WifiNative-wlan0: SET ps 1: returned true
09-09 13:36:08.977  1945  2280 D WfdsMonitor: WFDS Monitor is stopped
,09-09 13:36:08.977  1945  2280 D WfdsService: STATE : WfdsDisabledState - enter
09-09 13:36:08.978  1945  2281 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
09-09 13:36:08.978  1945  6912 D CtrlSupplicant: Received on exit socket, terminate
09-09 13:36:08.978  1945  6912 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
09-09 13:36:08.978  1945  6912 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
09-09 13:36:08.978  1945  6912 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
09-09 13:36:08.979  1945  2280 W WfdsService: DefaultState - msg [9445378] is not handled
09-09 13:36:08.981  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 13:36:08.981  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 13:36:08.982  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 13:36:08.984  6373  6373 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-09 13:36:08.999   311   893 D CommandListener: Clearing all IP addresses on wlan0
,09-09 13:36:08.999  1036  1435 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
09-09 13:36:08.999  1036  1435 D DSQN    : disableDataServiceNotify
09-09 13:36:08.999  1036  1435 D DSQN    : stop dsqn bin
09-09 13:36:09.007   311  7511 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
09-09 13:36:09.007  1036  6923 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
09-09 13:36:09.007  1036  1435 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
09-09 13:36:09.007  1036  1435 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:36:09.007  1036  1435 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 13:36:09.008  1036  1110 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
09-09 13:36:09.008  1036  1435 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 13:36:09.008  1036  1435 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
09-09 13:36:09.008  1036  6923 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:36:09.008  1036  6923 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:36:09.008  1036  6923 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
09-09 13:36:09.008  1605  2090 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
09-09 13:36:09.009  1036  1435 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
09-09 13:36:09.009  1036  1435 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-09 13:36:09.009  1036  1435 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-09 13:36:09.028  1036  1923 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7512 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-09 13:36:09.030  1036  1435 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:36:09.030  1036  1435 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-09 13:36:09.030  1036  1392 D WifiNative-p2p0: doBoolean: TERMINATE
09-09 13:36:09.030  1036  1435 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-09 13:36:09.030  1036  1435 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:36:09.030  1036  1435 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:36:09.031  1036  1435 D NetworkManagementService: Removing idletimer
09-09 13:36:09.031  1036  1435 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:36:09.031  1036  1392 D WifiNative-p2p0: TERMINATE: returned true
09-09 13:36:09.031  1036  1392 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-09 13:36:09.031  1036  1392 E WifiStateMachine: useWiFiOffloading() : false
09-09 13:36:09.031  1036  1392 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-09 13:36:09.031  1036  1435 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
09-09 13:36:09.032  1036  1388 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-09 13:36:09.032  1857  1857 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:36:09.032  1857  1857 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-09 13:36:09.034  1036  1036 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-09 13:36:09.035  1036  1036 D WifiHS20: hidePasspointNotification off =false
09-09 13:36:09.035  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:36:09.035  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:36:09.035  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-09 13:36:09.035  1036  1036 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-09 13:36:09.035  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-09 13:36:09.035  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-09 13:36:09.035  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-09 13:36:09.035  1036  1392 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:36:09.035  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-09 13:36:09.036  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-09 13:36:09.036  1036  1392 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 13:36:09.036  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-09 13:36:09.036  1036  1388 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
,09-09 13:36:09.037  1945  1945 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
09-09 13:36:09.042  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
09-09 13:36:09.042  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-09 13:36:09.043  1036  1036 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
09-09 13:36:09.043  6562  6562 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:36:09.043  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:36:09.043  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:36:09.043  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 13:36:09.043  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:36:09.043  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:36:09.043  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:36:09.043  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 13:36:09.047  6562  6562 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 13:36:09.057  6562  6562 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:36:09.057  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:36:09.057  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:36:09.057  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 13:36:09.057  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:36:09.057  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:36:09.057  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:36:09.057  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 13:36:09.059  6562  6562 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 13:36:09.062  6562  6562 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:36:09.062  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:36:09.062  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:36:09.062  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 13:36:09.062  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:36:09.062  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:36:09.062  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:36:09.062  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 13:36:09.064  6562  6562 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 13:36:09.070  1605  1605 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-09 13:36:09.071  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 13:36:09.072  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 13:36:09.072  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-09 13:36:09.072  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-09 13:36:09.074  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 13:36:09.089  6900  6900 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
09-09 13:36:09.089  6900  6900 I wpa_supplicant: monitor socket send errors count : 1
09-09 13:36:09.089  6900  6900 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1945-4\x00 that cannot receive messages
09-09 13:36:09.090  2037  2037 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
09-09 13:36:09.091  1036  6908 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
09-09 13:36:09.091  1036  6908 D WifiMonitor: Dropping event because (p2p0) is stopped
09-09 13:36:09.096  1036  1379 I InputReader: Reconfiguring input devices.  changes=0x00000010
09-09 13:36:09.098  1036  6924 D DhcpStateMachine: StoppedState
09-09 13:36:09.098  1036  6924 D DhcpStateMachine: StoppedState{ when=-120ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:36:09.098  1036  1392 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
09-09 13:36:09.099  1036  1392 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
09-09 13:36:09.117  1605  1605 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,09-09 13:36:09.118  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 13:36:09.118  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 13:36:09.118  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 13:36:09.122  1605  1605 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
09-09 13:36:09.125  1605  1605 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
09-09 13:36:09.125  1605  1605 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
09-09 13:36:09.125  2037  2037 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-09 13:36:09.130  6900  6900 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-09 13:36:09.131  6900  6900 W wpa_supplicant: USIM:  scard_deinit function
,09-09 13:36:09.131  1036  6908 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
09-09 13:36:09.131  1036  6908 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-09 13:36:09.131  1036  6908 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-09 13:36:09.131  1036  6908 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
09-09 13:36:09.131  1036  6908 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-09 13:36:09.132  1036  6908 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-09 13:36:09.132  1036  1112 D Tethering: InitialState.processMessage what=4
09-09 13:36:09.133  1036  1392 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=141834
09-09 13:36:09.134  1036  1392 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=141835
09-09 13:36:09.134  1036  1392 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=141836  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-09 13:36:09.134  1036  1392 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=141836  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-09 13:36:09.137  1036  1112 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-09 13:36:09.144  7512  7512 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,09-09 13:36:09.147  1036  1036 D administrator: Handling package changes for user 0
09-09 13:36:09.148  7512  7512 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-09 13:36:09.148  7512  7512 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-09 13:36:09.151  6804  6804 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-09 13:36:09.154  6804  6804 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 13:36:09.159  6825  6825 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-09 13:36:09.159  6825  6825 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 13:36:09.161  6825  6825 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-09 13:36:09.165  6373  6373 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-09 13:36:09.168  7512  7512 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-09 13:36:09.168  7512  7512 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-09 13:36:09.168  7512  7512 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-09 13:36:09.174  6804  6804 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 13:36:09.178  6804  6804 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 13:36:09.184  6825  6825 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-09 13:36:09.184  6825  6825 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 13:36:09.185  6825  6825 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-09 13:36:09.187  6900  6900 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-09 13:36:09.188  6373  6373 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-09 13:36:09.191  1036  6908 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
09-09 13:36:09.191  1036  6908 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-TERMINATING 
09-09 13:36:09.191  1036  6908 D WifiMonitor: Disconnecting from the supplicant, no more events
09-09 13:36:09.192  1036  1392 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 44 0
09-09 13:36:09.192  1036  1392 D WifiOffDelayIfNotUsed: stopMonitoring
09-09 13:36:09.192  1036  1392 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-09 13:36:09.192  1036  1392 E WifiStateMachine: useWiFiOffloading() : false
09-09 13:36:09.192  1036  1392 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-09 13:36:09.194  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 13:36:09.194  1945  1945 D WfdsService: Supplicant Connection state is changed : false
09-09 13:36:09.195  1945  2280 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
,09-09 13:36:09.195  1945  1945 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-09 13:36:09.195  1945  2280 D WfdsService: Set the WFDS Monitor: false
09-09 13:36:09.195  1945  2280 D WfdsMonitor: WFDS Monitor is stopped
09-09 13:36:09.195  7512  7512 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-09 13:36:09.195  7512  7512 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-09 13:36:09.195  7512  7512 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-09 13:36:09.196  2477  2477 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:36:09.196  6562  6562 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:36:09.197  6562  6562 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:36:09.198  6562  6562 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:36:09.200  6804  6804 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 13:36:09.207  6804  6804 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-09 13:36:09.215  6825  6825 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-09 13:36:09.215  6825  6825 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 13:36:09.216  6825  6825 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-09 13:36:09.222  7512  7512 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-09 13:36:09.225  6804  6804 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-09 13:36:09.230  6851  7533 W FormManager: Network not available. Please check & try again.
09-09 13:36:09.230  6804  6804 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 13:36:09.234  6851  7534 V FormManager: Network unavailable.
09-09 13:36:09.240  6851  7534 V FormManager: Network unavailable.
,09-09 13:36:09.262  1036  1036 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
,09-09 13:36:09.262  1036  1036 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
09-09 13:36:09.282  1036  1092 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-09 13:36:09.287  1036  1092 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
09-09 13:36:09.289  1036  1781 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7535 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
09-09 13:36:09.293  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
09-09 13:36:09.293  1036  1396 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
,09-09 13:36:09.293  1036  1396 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
09-09 13:36:09.294  1036  1981 I ActivityManager: Killing 6985:com.lge.appbox.client/u0a11 (adj 15): empty #17
09-09 13:36:09.351  2037  2037 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,09-09 13:36:09.358  1036  1962 W libprocessgroup: failed to open /acct/uid_10011/pid_6985/cgroup.procs: No such file or directory
09-09 13:36:09.367  2477  2477 V GmsNetworkLocationProvi: DISABLE
,09-09 13:36:09.384  6562  6617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:36:09.391  1036  1051 D WifiServiceImplEx: setWifiEnabled: true pid=6562, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,09-09 13:36:09.392  1036  1051 D WifiService: setWifiEnabled: true pid=6562, uid=10118
09-09 13:36:09.392  1036  1051 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-09 13:36:09.395  1036  1392 E WifiStateMachine:  InitialState CMD_TETHER_STATE_CHANGE 0 0
09-09 13:36:09.397  1036  1392 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,09-09 13:36:09.408  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-09 13:36:09.408  1036  1392 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
09-09 13:36:09.408  1036  1392 I LGFTMITEM: [GET_FTM][id=6], offset=12288
09-09 13:36:09.408  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-09 13:36:09.408  1036  1036 D Ulp_jni : JNI:system_update. Event-4
09-09 13:36:09.409  1036  1392 E WifiUtil: wfc_util_ffile_check_copy(): pid[1036] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
09-09 13:36:09.409  1036  1392 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-09 13:36:09.409  1036  1392 E WifiUtil: wfc_util_ffile_check_copy(): pid[1036] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
09-09 13:36:09.409  1036  1392 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-09 13:36:09.409  1036  1392 I WifiUtil: Intf0MacAddress=C49A027FFB5D
09-09 13:36:09.409  1036  1392 E WifiHW  : unknown target_country: EU , set to default
09-09 13:36:09.409  1036  1392 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
09-09 13:36:09.409  1036  1392 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
09-09 13:36:09.409  1036  1392 I WifiUtil: gEnableBmps=1
,09-09 13:36:09.413  7535  7535 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-09 13:36:09.422  2477  2477 E GCoreFlp: Bound FusedProviderService with LocationManager
,09-09 13:36:09.539  7535  7535 D LgDataFeature: LgDataFeature() Constructor: none
09-09 13:36:09.539  7535  7535 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-09 13:36:09.544  1036  1036 I art     : Explicit concurrent mark sweep GC freed 60293(2MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/65MB, paused 1.538ms total 125.008ms
09-09 13:36:09.545  1036  1092 D LocationProviderProxy: applying state to connected service
,09-09 13:36:09.689  7535  7565 I Babel   : MmsConfig: mnc/mcc: 0/0
09-09 13:36:09.689  7535  7565 I Babel   : MmsConfig.loadMmsSettings
,09-09 13:36:09.702  7535  7565 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
,09-09 13:36:09.702  7535  7565 I Babel   : MmsConfig.loadFromDatabase
09-09 13:36:09.708  7535  7563 W AudioCapabilities: Unsupported mime audio/evrc
09-09 13:36:09.709  7535  7563 W AudioCapabilities: Unsupported mime audio/qcelp
09-09 13:36:09.710  7535  7563 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-09 13:36:09.719  7535  7563 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
09-09 13:36:09.719  7535  7563 W AudioCapabilities: Unsupported mime audio/qcelp
09-09 13:36:09.721  7535  7563 W AudioCapabilities: Unsupported mime audio/evrc
09-09 13:36:09.725  7535  7565 E Babel   : canonicalizeMccMnc: invalid mccmnc 
09-09 13:36:09.725  7535  7565 I Babel   : MmsConfig.loadFromResources
,09-09 13:36:09.730  7535  7565 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
09-09 13:36:09.731  7535  7565 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
09-09 13:36:09.732  7535  7535 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:36:09.736  7535  7563 W VideoCapabilities: Unsupported mime video/x-ms-wmv
09-09 13:36:09.738  7535  7563 W VideoCapabilities: Unsupported mime video/divx
09-09 13:36:09.741  7535  7563 W VideoCapabilities: Unsupported mime video/divx311
,09-09 13:36:09.743  7535  7563 W VideoCapabilities: Unsupported mime video/divx4
09-09 13:36:09.751  1821  7570 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
09-09 13:36:09.751  1821  7570 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
09-09 13:36:09.753  7358  7358 V BluetoothOppNotification: new notify threadi!
09-09 13:36:09.753  7358  7358 V BluetoothOppNotification: send delay message
,09-09 13:36:09.754  7358  7572 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
09-09 13:36:09.755  7358  7572 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@220c24e2 on behalf of 
09-09 13:36:09.755  7535  7563 W VideoCapabilities: Unsupported mime video/mp4v-esdp
09-09 13:36:09.755  7358  7572 V BluetoothOppNotification: mUpdateCompleteNotification = true
09-09 13:36:09.756  7358  7572 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
09-09 13:36:09.757  7358  7572 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1b34c073 on behalf of 
09-09 13:36:09.758  7358  7572 V BluetoothOppNotification: outbound: succ-0  fail-0
09-09 13:36:09.763  7358  7572 V BluetoothOppNotification: outbound notification was removed.
09-09 13:36:09.763  7358  7572 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
09-09 13:36:09.764  7358  7572 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@340b2b30 on behalf of 
09-09 13:36:09.764  7358  7572 V BluetoothOppNotification: inbound: succ-0  fail-0
,09-09 13:36:09.765  7358  7572 V BluetoothOppNotification: inbound notification was removed.
09-09 13:36:09.765  7358  7572 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
09-09 13:36:09.771  7535  7563 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
09-09 13:36:09.774  7358  7572 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@270a33a9 on behalf of 
09-09 13:36:09.775  7535  7563 W AudioCapabilities: Unsupported mime audio/eac3
,09-09 13:36:09.777  7535  7563 W AudioCapabilities: Unsupported mime audio/ac3
09-09 13:36:09.778  7535  7563 W AudioCapabilities: Unsupported mime audio/g726
09-09 13:36:09.779  7535  7563 W AudioCapabilities: Unsupported mime audio/wma-voice
09-09 13:36:09.780  7535  7563 W AudioCapabilities: Unsupported mime audio/x-ms-wma
09-09 13:36:09.780  7535  7563 W AudioCapabilities: Unsupported mime audio/adpcm
09-09 13:36:09.782  7535  7563 W VideoCapabilities: Unsupported mime video/theora
09-09 13:36:09.783  7535  7563 W VideoCapabilities: Unsupported mime video/mjpg
09-09 13:36:09.807  1036  1999 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7574 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,09-09 13:36:09.819  1821  4740 I Icing   : updateResources: need to parse e{com.google.android.gms}
09-09 13:36:09.843  7574  7574 I AppUp4:AppBoxCP: onCreate
09-09 13:36:09.843  7574  7574 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,09-09 13:36:09.848  7574  7574 I AppUp4:DB:  setFingerPrint start
09-09 13:36:09.848  7574  7574 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
09-09 13:36:09.850  1036  1999 I ActivityManager: Killing 6471:com.lge.email/u0a23 (adj 15): empty #17
09-09 13:36:09.855  7574  7574 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
09-09 13:36:09.855  7574  7574 I AppUp4:DB:  SDK version = 21
09-09 13:36:09.855  7574  7574 I AppUp4:DB:  beforefinger == newfinger no write in DB
09-09 13:36:10.007  1036  1923 W libprocessgroup: failed to open /acct/uid_10023/pid_6471/cgroup.procs: No such file or directory
09-09 13:36:10.008  7574  7574 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
,09-09 13:36:10.028  7574  7574 I AppUp4:CustModeStarterReceiver: onReceive
,09-09 13:36:10.061  7574  7574 D LgDataFeature: LgDataFeature() Constructor: none
09-09 13:36:10.062  7574  7574 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-09 13:36:10.068  7574  7574 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@3ce18c58
09-09 13:36:10.068  7574  7574 D AppUp4:CustFacade: isCustomizationCompleted : false
09-09 13:36:10.068  7574  7574 D AppUp4:CustFacade: isPhone : true
09-09 13:36:10.069  7574  7574 D AppUp4:CustModeStarterReceiver: begin check event
09-09 13:36:10.069  7574  7574 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
09-09 13:36:10.129  1036  1781 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7606 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
09-09 13:36:10.131  1036  1781 I ActivityManager: Killing 7046:com.android.chrome/u0a57 (adj 15): empty #17
,09-09 13:36:10.189   311   893 D SoftapController: Softap fwReload - Ok
,09-09 13:36:10.192  1036  1392 E NetdConnector: NDC Command {84 softap fwreload wlan0 STA} took too long (778ms)
09-09 13:36:10.194   311   893 D CommandListener: Setting iface cfg
09-09 13:36:10.194   311   893 D CommandListener: Trying to bring down wlan0
09-09 13:36:10.195   311   893 D CommandListener: Clearing all IP addresses on wlan0
09-09 13:36:10.196  1036  1051 W libprocessgroup: failed to open /acct/uid_10057/pid_7046/cgroup.procs: No such file or directory
09-09 13:36:10.201  1036  1392 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
09-09 13:36:10.208  1036  1112 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-09 13:36:10.208  1036  1112 D Tethering: InitialState.processMessage what=4
09-09 13:36:10.209  1036  1112 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-09 13:36:10.201  7624  7624 W wpa_supplicant: type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6841 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-09 13:36:10.201  7624  7624 W wpa_supplicant: type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6841 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-09 13:36:10.236  7624  7624 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-09 13:36:10.252  7606  7606 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-09 13:36:10.253  7606  7606 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-09 13:36:10.255  7606  7606 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
09-09 13:36:10.258  7606  7606 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
09-09 13:36:10.258  7606  7606 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-09 13:36:10.273  7624  7624 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-09 13:36:10.274  7624  7624 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
09-09 13:36:10.302  1036  1392 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-09 13:36:10.302  1036  1392 E WifiStateMachine: useWiFiOffloading() : false
09-09 13:36:10.302  1036  1392 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-09 13:36:10.303  1036  1392 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
09-09 13:36:10.303  1036  1392 D WifiMonitor: connecting to supplicant
,09-09 13:36:10.306  1945  1945 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
,09-09 13:36:10.308  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-09 13:36:10.309  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
09-09 13:36:10.310  6562  6562 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:36:10.311  6562  6562 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:36:10.312  6562  6562 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:36:10.343  7606  7606 I SystemConfig: BUILD Country: EU
09-09 13:36:10.343  7606  7606 I SystemConfig: BUILD Operator: OPEN
,09-09 13:36:10.359  7624  7624 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-09 13:36:10.412  1036  1944 I ActivityManager: Killing 7066:com.lge.drmservice/u0a62 (adj 15): empty #17
,09-09 13:36:10.428  7624  7624 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,09-09 13:36:10.440  7624  7624 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
09-09 13:36:10.440  7624  7624 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
09-09 13:36:10.442  1036  1392 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
,09-09 13:36:10.444  1036  7627 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
09-09 13:36:10.444  1036  7627 D WifiMonitor: Dropping event because (p2p0) is stopped
09-09 13:36:10.445  1036  7627 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
09-09 13:36:10.445  1036  7627 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
09-09 13:36:10.445  1036  7627 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
09-09 13:36:10.445  1036  1392 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
09-09 13:36:10.445  1036  7627 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
09-09 13:36:10.447  1036  1392 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
09-09 13:36:10.448  1036  1392 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
09-09 13:36:10.450  1036  1392 E WifiStateMachine:  SupplicantStartingState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3937] from screen [on:0 period:247187922] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-09 13:36:10.452  1036  1392 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:247187924] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-09 13:36:10.454  1036  1392 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
09-09 13:36:10.455  1036  1392 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,09-09 13:36:10.456  1036  1392 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
09-09 13:36:10.456  1036  1392 D WifiNative-wlan0: doString: [DRIVER MACADDR]
09-09 13:36:10.457  1036  1392 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
09-09 13:36:10.457  1036  1392 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
09-09 13:36:10.457  1036  1392 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
09-09 13:36:10.461  1036  2035 W libprocessgroup: failed to open /acct/uid_10062/pid_7066/cgroup.procs: No such file or directory
09-09 13:36:10.466  1036  1392 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-09 13:36:10.466  1036  1392 E WifiStateMachine: useWiFiOffloading() : false
09-09 13:36:10.466  1036  1392 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,09-09 13:36:10.468  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:36:10.468  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:36:10.468  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:36:10.469  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:36:10.469  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-09 13:36:10.470  7606  7625 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
09-09 13:36:10.470  7606  7625 I SystemConfig: existFile = false
09-09 13:36:10.470  7606  7625 I SystemConfig: canReadFile = false
09-09 13:36:10.470  7606  7625 I SystemConfig: systemFeature RCS result false
09-09 13:36:10.470  7606  7625 D SystemConfig: refreshRcsSupport() :false
09-09 13:36:10.532  1036  1944 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7628 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,09-09 13:36:10.535  1036  1392 D WifiNative-wlan0: doBoolean: SET update_config 1
09-09 13:36:10.536  1036  1392 D WifiNative-wlan0: SET update_config 1: returned true
09-09 13:36:10.536  1036  1392 D WifiConfigStore: Loading config and enabling all networks 
09-09 13:36:10.536  1036  1392 D WifiNative-wlan0: doString: [LIST_NETWORKS]
09-09 13:36:10.537  1036  1392 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
09-09 13:36:10.537  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 13:36:10.540  1945  1945 D WfdService: Waiting for WifiP2p enabling
09-09 13:36:10.543  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
09-09 13:36:10.543  1036  1396 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
09-09 13:36:10.544  1036  1392 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
09-09 13:36:10.554  6562  6562 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:36:10.554  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:36:10.554  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:36:10.554  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:36:10.554  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:36:10.554  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:36:10.554  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:36:10.554  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 13:36:10.557  6562  6562 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 13:36:10.562  1036  1392 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
09-09 13:36:10.562  6562  6562 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:36:10.562  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:36:10.562  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:36:10.562  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:36:10.562  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:36:10.562  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:36:10.562  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:36:10.562  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 13:36:10.562  1036  1392 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-09 13:36:10.564  1036  1392 D WifiStateMachine: enableVerboseLogging : level 2
09-09 13:36:10.564  1036  1392 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
09-09 13:36:10.564  1036  1392 D WifiNative-wlan0: SET device_name g3_global_com: returned true
09-09 13:36:10.564  1036  1392 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
09-09 13:36:10.564  6562  6562 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 13:36:10.565  1036  1392 D WifiNative-wlan0: SET manufacturer LGE: returned true
09-09 13:36:10.565  1036  1392 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
09-09 13:36:10.565  1036  1392 D WifiNative-wlan0: SET model_name LG-D855: returned true
09-09 13:36:10.566  1036  1392 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
09-09 13:36:10.566  1036  1392 D WifiNative-wlan0: SET model_number LG-D855: returned true
09-09 13:36:10.566  1036  1392 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
09-09 13:36:10.567  1036  1392 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
09-09 13:36:10.567  1036  1392 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
09-09 13:36:10.567  1036  1392 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
09-09 13:36:10.567  1036  1392 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
09-09 13:36:10.568  1036  1392 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
09-09 13:36:10.569  1945  1945 D WfdsService: Supplicant Connection state is changed : true
09-09 13:36:10.569  6562  6562 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:36:10.569  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:36:10.569  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:36:10.569  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:36:10.569  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:36:10.569  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:36:10.569  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:36:10.569  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 13:36:10.569  1036  1392 D WifiStateMachine: Setting OUI to DA-A1-19
09-09 13:36:10.569  1036  1392 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
,09-09 13:36:10.569  1945  2280 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
09-09 13:36:10.569  1945  2280 D WfdsService: Set the WFDS Monitor: true
09-09 13:36:10.569  1945  2280 D WfdsMonitor: WfdsMonitorThread create
09-09 13:36:10.570  1945  2280 D WfdsMonitor: WFDS Monitor is created and started
09-09 13:36:10.570  1945  2280 D WfdsService: WiFi: Supplicant connection re-established
09-09 13:36:10.570  1036  1392 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
09-09 13:36:10.570  1036  1392 D WifiNative-HAL: Setting external_sim to 1
09-09 13:36:10.570  1036  1392 D WifiNative-wlan0: doBoolean: SET external_sim 1
09-09 13:36:10.570  1036  1392 D WifiNative-wlan0: SET external_sim 1: returned true
09-09 13:36:10.570  1036  1392 I WifiNative-HAL: startHal
09-09 13:36:10.570  1036  1392 D wifi    : setting scan oui 0x956ec580
09-09 13:36:10.571  1036  1392 D WifiStateMachine: Setting OUI to DA-A1-19
09-09 13:36:10.571  1036  1392 I WifiNative-HAL: startHal
09-09 13:36:10.571  1036  1392 D wifi    : setting scan oui 0x956ec580
09-09 13:36:10.571  1036  1392 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
09-09 13:36:10.572  1945  7645 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
09-09 13:36:10.572  6562  6562 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 13:36:10.572  1945  7645 E CtrlSupplicant: Succeed to open control connection
09-09 13:36:10.572  1945  7645 E CtrlSupplicant: Succeed to open monitor connection
09-09 13:36:10.572  7535  7535 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-09 13:36:10.576  1945  7645 D WfdsMonitor: Supplicant connection established
09-09 13:36:10.577  1945  2280 D WfdsService: Connected to the supplicant for wfds
09-09 13:36:10.577  1036  1392 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
09-09 13:36:10.577  1036  1392 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
09-09 13:36:10.577  7624  7624 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
09-09 13:36:10.581  1036  1392 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
09-09 13:36:10.581  1036  1392 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-09 13:36:10.581  7624  7624 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-09 13:36:10.581  1036  1392 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-09 13:36:10.581  1036  1392 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
09-09 13:36:10.581  7624  7624 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
09-09 13:36:10.582  1036  1392 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
09-09 13:36:10.582  1036  1392 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-09 13:36:10.582  7624  7624 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-09 13:36:10.582  1036  1392 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-09 13:36:10.582  1036  1392 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-09 13:36:10.583  7624  7624 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-09 13:36:10.583  1036  1392 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-09 13:36:10.583  1036  1392 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
09-09 13:36:10.583  7624  7624 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
09-09 13:36:10.584  1036  1392 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
09-09 13:36:10.584  1036  1392 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-09 13:36:10.584  7624  7624 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-09 13:36:10.584  1036  1392 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-09 13:36:10.585  1036  1392 E WifiNative: : [143,286,180 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
09-09 13:36:10.585  1036  1392 D WifiNative-wlan0: doBoolean: RECONNECT
09-09 13:36:10.585  1036  1392 D WifiNative-wlan0: RECONNECT: returned true
09-09 13:36:10.586  1036  1392 D WifiNative-wlan0: doString: [STATUS]
09-09 13:36:10.586  1036  7627 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
09-09 13:36:10.586  1036  7627 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
09-09 13:36:10.586  1036  1392 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-09 13:36:10.586  1036  1392 D WifiNative-wlan0: doBoolean: SET ps 1
09-09 13:36:10.587  1036  1392 D WifiNative-wlan0: SET ps 1: returned true
09-09 13:36:10.587  1036  1389 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=131203 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:36:10.588  1036  1036 D WifiScanningService: SCAN_AVAILABLE : 3
09-09 13:36:10.588  1036  1036 D RttService: SCAN_AVAILABLE : 3
09-09 13:36:10.588  1036  1560 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:36:10.588  1036  1559 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:36:10.589  1036  1559 I WifiNative-HAL: startHal
09-09 13:36:10.589  1036  1392 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
09-09 13:36:10.589  1036  1559 D wifi    : getting scan capabilities on interface[1] = 0x956ec580
09-09 13:36:10.589  1036  1559 D wifi    : failed to get capabilities : -3
0,9-09 13:36:10.589  1036  1559 E WifiScanningService: could not get scan capabilities
09-09 13:36:10.589  1036  1392 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
09-09 13:36:10.589   311   893 D CommandListener: Setting iface cfg
09-09 13:36:10.589  1036  1392 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
09-09 13:36:10.589   311   893 D CommandListener: Trying to bring up p2p0
09-09 13:36:10.590  1036  1389 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-09 13:36:10.590  1036  1389 D LGWifiP2pService: P2pEnablingState
09-09 13:36:10.590  1036  1392 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
09-09 13:36:10.590  1036  1389 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:36:10.590  1036  1389 D LGWifiP2pService: P2p socket connection successful
09-09 13:36:10.590  1036  1389 D LGWifiP2pService: P2pEnabledState
09-09 13:36:10.590  1036  1389 D LGWifiP2pService: sending p2p connection changed broadcast
,09-09 13:36:10.592  1945  1945 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
09-09 13:36:10.592  1945  1945 D WfdsService: WifiP2pState is changed : true
09-09 13:36:10.592  1945  2280 D WfdsService: Receive the WFDS_ENABLE Method
09-09 13:36:10.592  1945  2280 D WfdsService: Set the WFDS Monitor: true
09-09 13:36:10.592  1945  2280 D WfdsService: Connected to the supplicant for wfds
09-09 13:36:10.592  1945  2280 D WfdsJNI : doCommand: WFDS_SET TRUE
09-09 13:36:10.592  7624  7624 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
09-09 13:36:10.593  1945  2280 D WfdsService: selectPreferredScanChannel [36]
09-09 13:36:10.593  1945  2280 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
09-09 13:36:10.593  1036  1392 E WifiStateMachine:  DisconnectedState what:132106 1 0
09-09 13:36:10.593  1036  1392 E WifiStateMachine:  ConnectModeState what:132106 1 0
09-09 13:36:10.594  1036  1392 E WifiStateMachine:  DriverStartedState what:132106 1 0
09-09 13:36:10.594  1036  1392 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
09-09 13:36:10.594  7624  7624 E wpa_supplicant: nWIFIDualbandAPConnection: 1
09-09 13:36:10.594  1036  1392 E WifiStateMachine:  DisconnectedState what:132096 -100 0
09-09 13:36:10.595  1036  1392 E WifiStateMachine:  ConnectModeState what:132096 -100 0
09-09 13:36:10.595  1036  1392 E WifiStateMachine:  DriverStartedState what:132096 -100 0
09-09 13:36:10.595  1036  1392 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
09-09 13:36:10.596  7624  7624 E wpa_supplicant: disconnect_rssi_lvl: -100
09-09 13:36:10.596  1036  1392 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
09-09 13:36:10.597  1036  1392 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
09-09 13:36:10.597  1036  1392 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
09-09 13:36:10.597  1036  1392 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
09-09 13:36:10.598  7624  7624 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-09 13:36:10.598  7624  7624 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-09 13:36:10.599  7624  7624 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-09 13:36:10.599  7624  7624 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 13:36:10.599  7624  7624 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 13:36:10.600  1036  1392 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
09-09 13:36:10.600  1036  1392 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
09-09 13:36:10.600  1945  7645 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-09 13:36:10.601  1945  7645 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-09 13:36:10.601  1036  1392 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
09-09 13:36:10.601  1036  7627 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-09 13:36:10.601  1036  7627 E WifiMonitor: WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-09 13:36:10.601  1945  1945 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
09-09 13:36:10.601  1036  7627 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-09 13:36:10.601  1036  1392 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
09-09 13:36:10.601  1036  7627 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-09 13:36:10.601  1036  1392 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
09-09 13:36:10.601  1036  7627 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-09 13:36:10.601  1036  7627 E WifiMonitor: WifiMonitor:p2p0 cnt=47 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 13:36:10.601  1036  1389 D WifiNative-p2p0: do,Boolean: SET persistent_reconnect 1
09-09 13:36:10.601  1036  7627 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 13:36:10.601  1036  7627 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 13:36:10.601  7624  7624 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
09-09 13:36:10.601  1036  7627 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-09 13:36:10.601  7624  7624 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-09 13:36:10.601  1036  7627 E WifiMonitor: WifiMonitor:p2p0 cnt=48 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 13:36:10.602  1945  1945 D WfdsService: isConnected: false
09-09 13:36:10.602  1036  7627 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 13:36:10.602  1036  7627 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 13:36:10.602  1036  7627 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
09-09 13:36:10.602  1036  7627 E WifiMonitor: WifiMonitor:wlan0 cnt=49 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-09 13:36:10.602  1036  7627 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-09 13:36:10.602  1036  7627 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-09 13:36:10.602  1036  1392 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
09-09 13:36:10.602  1036  1392 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
09-09 13:36:10.603  1036  1389 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
09-09 13:36:10.603  1036  1389 D WifiNative-p2p0: doBoolean: SET device_name G3
09-09 13:36:10.603  1036  1389 D WifiNative-p2p0: SET device_name G3: returned true
09-09 13:36:10.604  1036  1389 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
09-09 13:36:10.604  1036  1389 D LGWifiP2pService: before postfix = G3
09-09 13:36:10.604  1036  1389 D WifiServerServiceExt: postfix byte check : 2
09-09 13:36:10.604  1036  1389 D LGWifiP2pService: after postfix = G3
09-09 13:36:10.604  1036  1389 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
,09-09 13:36:10.604  1036  1389 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
09-09 13:36:10.604  1036  1389 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
,09-09 13:36:10.605  1036  1389 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
09-09 13:36:10.605  1036  1389 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
09-09 13:36:10.605  1036  1389 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
09-09 13:36:10.605  1036  1389 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
09-09 13:36:10.606  1036  1389 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
09-09 13:36:10.606  1036  1392 D WifiNative-wlan0: BSS_FLUSH 0: returned true
09-09 13:36:10.606  1036  1392 D WifiNative-wlan0: doBoolean: SCAN
09-09 13:36:10.606  1036  1392 D WifiNative-wlan0: SCAN: returned false
09-09 13:36:10.607  1036  1392 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=143308  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-09 13:36:10.609  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 13:36:10.609  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 13:36:10.609  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:36:10.609  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:36:10.609  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-09 13:36:10.610  1036  1389 D WifiNative-HAL: p2pGetDeviceAddress
09-09 13:36:10.610  1036  1389 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
09-09 13:36:10.610  1036  1389 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
09-09 13:36:10.610  1036  1389 D WifiNative-p2p0: doBoolean: P2P_FLUSH
09-09 13:36:10.611  1036  1392 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=143312  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-09 13:36:10.611  1036  1389 D WifiNative-p2p0: P2P_FLUSH: returned true
09-09 13:36:10.611  1036  1389 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
09-09 13:36:10.611  1036  1392 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-09 13:36:10.612  1036  1392 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-09 13:36:10.612  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 13:36:10.612  1945  1945 I WfdStateTracker: handleP2pThisDeviceChanged
09-09 13:36:10.612  1945  1945 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
09-09 13:36:10.612  1945  1945 D WfdsService: Update P2p Interface State: 3
09-09 13:36:10.612  1036  1392 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-09 13:36:10.612  1036  1392 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-09 13:36:10.613  1036  1392 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-09 13:36:10.613  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-09 13:36:10.613  1036  1036 D WifiServerServiceExt: setSupplicantStateSCANNING
09-09 13:36:10.614  1036  1389 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
09-09 13:36:10.614  1036  1389 D WifiNative-p2p0: doString: [LIST_NETWORKS]
09-09 13:36:10.615  1036  1389 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
09-09 13:36:10.615  1036  1389 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
,09-09 13:36:10.624  1036  1389 D WifiNative-p2p0: SAVE_CONFIG: returned true
09-09 13:36:10.624  1036  1389 D LGWifiP2pService: sending p2p persistent groups changed broadcast
09-09 13:36:10.624  1036  1389 D LGWifiP2pService: InactiveState
09-09 13:36:10.624  1036  1389 D LGWifiP2pService: InactiveState{ when=-24ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:36:10.624  1036  1389 D LGWifiP2pService: P2pEnabledState{ when=-24ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:36:10.624  1036  1389 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
09-09 13:36:10.625  7624  7624 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-09 13:36:10.625  7624  7624 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-09 13:36:10.625  1945  7645 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-09 13:36:10.625  1036  7627 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-09 13:36:10.625  1036  7627 E WifiMonitor: WifiMonitor:p2p0 cnt=50 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-09 13:36:10.625  1036  7627 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-09 13:36:10.625  1036  7627 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-09 13:36:10.626  7624  7624 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-09 13:36:10.626  7624  7624 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 13:36:10.626  1036  7627 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-09 13:36:10.626  1036  7627 E WifiMonitor: WifiMonitor:p2p0 cnt=51 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 13:36:10.626  1036  7627 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 13:36:10.626  1945  7645 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-09 13:36:10.626  1036  7627 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 13:36:10.627  7624  7624 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 13:36:10.627  1036  7627 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-09 13:36:10.627  1036  7627 E WifiMonitor: WifiMonitor:p2p0 cnt=52 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 13:36:10.627  1036  1389 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
09-09 13:36:10.627  1036  7627 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 13:36:10.627  1036  7627 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-09 13:36:10.627  1036  1389 D LGWifiP2pService: InactiveState{ when=-12ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:36:10.627  1036  1389 D LGWifiP2pService: P2pEnabledState{ when=-12ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:36:10.627  1036  1389 D LGWifiP2pService: InactiveState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:36:10.627  1036  1389 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:36:10.627  1036  1389 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:36:10.627  1036  1389 D LGWifiP2pService: InactiveState{ when=-1ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:36:10.627  1036  1389 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:36:10.627  1036  1389 D LGWifiP2pService: DefaultState{ when=-1ms what=139285 arg2=,6 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:36:10.628  1036  1389 D LGWifiP2pService: InactiveState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:36:10.628  1036  1389 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:36:10.628  1036  1389 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:36:10.628  1945  7645 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-09 13:36:10.628  1945  2280 W WfdsService: DefaultState - msg [9441285] is not handled
09-09 13:36:10.629  7628  7628 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-09 13:36:10.629  7628  7628 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-09 13:36:10.629  7628  7628 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,09-09 13:36:10.630  7628  7628 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,09-09 13:36:10.634  1036  1389 D LGWifiP2pService: InactiveState{ when=-7ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:36:10.634  1036  1389 D LGWifiP2pService: P2pEnabledState{ when=-8ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:36:10.634  1036  1389 D LGWifiP2pService: DefaultState{ when=-8ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:36:10.635  1036  1036 E WifiServerServiceExt: No p2p device connected
09-09 13:36:10.744  7628  7628 I AppConfig: Total System Memory = 2995761152
,09-09 13:36:10.754  7628  7628 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
09-09 13:36:10.874  1036  1923 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7648 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-09 13:36:10.876  1036  1923 I ActivityManager: Killing 7083:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
,09-09 13:36:10.917  1036  1962 W libprocessgroup: failed to open /acct/uid_10085/pid_7083/cgroup.procs: No such file or directory
,09-09 13:36:10.922  6562  6617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:36:10.923  6562  6617 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:36:10.923  6562  6617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 13:36:10.923  6562  6617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:36:10.923  6562  6617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 13:36:10.923  6562  6617 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2940cf0b removed from the list
09-09 13:36:10.923  6562  6617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:36:10.923  6562  6617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d2fb1e8 removed from the list
09-09 13:36:10.923  6562  6617 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:36:10.923  6562  6617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:36:10.938  6562  7665 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
09-09 13:36:10.938  6562  7665 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-09 13:36:11.127  7648  7648 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,09-09 13:36:11.209  1036  7627 E WifiMonitor: WifiMonitor:wlan0 cnt=53 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
09-09 13:36:11.209  1036  7627 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
09-09 13:36:11.209  7624  7624 E wpa_supplicant: USIM:  scard_init function
09-09 13:36:11.209  1036  7627 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
09-09 13:36:11.209  1036  7627 E WifiMonitor: WifiMonitor:wlan0 cnt=54 dispatchEvent: WPS-AP-AVAILABLE 
09-09 13:36:11.209  1036  7627 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
09-09 13:36:11.210  7624  7624 I wpa_supplicant: Trying to associate with SSID 'NG700'
,09-09 13:36:11.214  1036  1392 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=6 bcn=0
09-09 13:36:11.215  1036  1392 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=6 bcn=0
09-09 13:36:11.215  1036  1392 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=6 bcn=0
09-09 13:36:11.215  1036  1392 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=6 bcn=0
09-09 13:36:11.215  1036  1392 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
09-09 13:36:11.216  1036  7627 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
09-09 13:36:11.216  1036  7627 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
09-09 13:36:11.221  1036  1392 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 55 0 rt=143922  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
09-09 13:36:11.222  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 13:36:11.223  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 13:36:11.224  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:36:11.224  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-09 13:36:11.224  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-09 13:36:11.225  1036  1392 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 55 0 rt=143926  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
09-09 13:36:11.226  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 13:36:11.230  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:36:11.230  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:36:11.231  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-09 13:36:11.231  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-09 13:36:11.231  1036  1036 D WifiServerServiceExt: setSupplicantStateASSOCIATING
09-09 13:36:11.239  7648  7648 D LgDataFeature: LgDataFeature() Constructor: none
09-09 13:36:11.239  7648  7648 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-09 13:36:11.248  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 13:36:11.248  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 13:36:11.250  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-09 13:36:11.286  7648  7648 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,09-09 13:36:11.305  7648  7648 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,09-09 13:36:11.305  7648  7648 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
09-09 13:36:11.322  1036  1112 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-09 13:36:11.325  7624  7624 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
09-09 13:36:11.325  1036  7627 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
09-09 13:36:11.325  1036  7627 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
09-09 13:36:11.325  1036  7627 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
09-09 13:36:11.325  1036  7627 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: Associated with f4:f2:6d:22:99:3e
09-09 13:36:11.325  1036  1392 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
09-09 13:36:11.326  1036  1392 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
09-09 13:36:11.327  1036  1392 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
09-09 13:36:11.327  1036  1392 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
09-09 13:36:11.328  1036  7627 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-09 13:36:11.328  1036  7627 E WifiMonitor: WifiMonitor:wlan0 cnt=58 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-09 13:36:11.328  1036  1392 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-09 13:36:11.329  1036  1392 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=144030  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-09 13:36:11.330  1036  1392 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=144031  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-09 13:36:11.331  1036  1392 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=144032
09-09 13:36:11.331  1036  1392 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=144033
09-09 13:36:11.332  1036  1392 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=144033
09-09 13:36:11.332  1036  1392 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=144034
09-09 13:36:11.335  1036  1392 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=144036
09-09 13:36:11.335  1036  1392 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=144037  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
,09-09 13:36:11.338  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-09 13:36:11.338  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 13:36:11.340  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:36:11.340  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:36:11.340  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-09 13:36:11.341  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 13:36:11.344  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:36:11.344  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:36:11.344  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
09-09 13:36:11.344  7624  7624 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-09 13:36:11.345  7624  7624 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-09 13:36:11.345  1036  1392 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=144047  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
09-09 13:36:11.346  1036  7627 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-09 13:36:11.346  1036  7627 E WifiMonitor: WifiMonitor:wlan0 cnt=59 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-09 13:36:11.346  1036  7627 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
09-09 13:36:11.347  1036  7627 E WifiMonitor: WifiMonitor:wlan0 cnt=60 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-09 13:36:11.347  1036  7627 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-09 13:36:11.347  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-09 13:36:11.347  1036  1036 D WifiServerServiceExt: setSupplicantStateASSOCIATED
09-09 13:36:11.347  1036  7627 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
,09-09 13:36:11.347  1036  7627 E WifiMonitor: WifiMonitor:wlan0 cnt=61 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-09 13:36:11.347  1036  7627 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-09 13:36:11.348  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-09 13:36:11.348  1036  7627 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-09 13:36:11.348  1036  1036 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
09-09 13:36:11.349  1036  7627 E WifiMonitor: WifiMonitor:wlan0 cnt=62 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-09 13:36:11.349  1036  1392 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=144051  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-09 13:36:11.350  1036  1392 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=144052  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-09 13:36:11.351  1036  1392 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=144052
09-09 13:36:11.351  1036  1392 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=144053
09-09 13:36:11.352  1036  1392 D WifiNative-wlan0: doString: [STATUS]
09-09 13:36:11.352  1036  7627 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-09 13:36:11.352  1036  7627 E WifiMonitor: WifiMonitor:wlan0 cnt=63 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-09 13:36:11.352  1036  1392 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-09 13:36:11.354  1036  1392 I WifiServiceExtension: setVHTCapabilityType  : false
09-09 13:36:11.355  7648  7648 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-09 13:36:11.356  7648  7648 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
09-09 13:36:11.361  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 13:36:11.361  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-09 13:36:11.363  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 13:36:11.364  1036  1392 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
09-09 13:36:11.364  1036  1392 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
09-09 13:36:11.371  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:36:11.371  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:36:11.371  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-09 13:36:11.372  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:36:11.372  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:36:11.372  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-09 13:36:11.378  1036  1392 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
09-09 13:36:11.379  1036  1435 D ConnectivityService: Got NetworkAgent Messenger
,09-09 13:36:11.379  1036  1392 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-09 13:36:11.379  1036  1392 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-09 13:36:11.379  1036  1435 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
09-09 13:36:11.381  1036  1435 D ConnectivityService: NetworkAgent connected
09-09 13:36:11.381  1036  1392 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-09 13:36:11.381  1036  1392 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-09 13:36:11.384  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 13:36:11.384  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 13:36:11.386  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 13:36:11.387  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 13:36:11.388  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 13:36:11.388  1036  1392 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-09 13:36:11.388  1036  1392 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-09 13:36:11.388  1036  1392 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-09 13:36:11.389  1036  1392 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-09 13:36:11.389  1036  1392 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-09 13:36:11.389  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 13:36:11.390  1036  1963 I ActivityManager: Killing 7123:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
,09-09 13:36:11.395  1036  1392 D WifiNative-wlan0: SAVE_CONFIG: returned true
,09-09 13:36:11.397   311   893 D CommandListener: Setting iface cfg
09-09 13:36:11.442  6562  7665 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
09-09 13:36:11.442  6562  7665 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-09 13:36:11.442  6562  7665 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-09 13:36:11.442  6562  7665 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-09 13:36:11.443  6562  7696 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
09-09 13:36:11.443  6562  7696 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-09 13:36:11.443  6562  7696 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-09 13:36:11.443  6562  7665 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
09-09 13:36:11.444  6562  7699 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 918, name: OutgoingSocketThread/Sender)
09-09 13:36:11.445  6562  7701 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 919, name: OutgoingSocketThread/Receiver)
09-09 13:36:11.445  6562  7696 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-09 13:36:11.445  6562  7696 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
09-09 13:36:11.446  6562  7701 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 919, thread name: OutgoingSocketThread/Receiver)
09-09 13:36:11.446  6562  7701 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-09 13:36:11.446  6562  7701 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 919, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
09-09 13:36:11.448  6562  7702 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 920, name: IncomingSocketThread/Sender)
09-09 13:36:11.450  6562  7703 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 921, name: IncomingSocketThread/Receiver)
09-09 13:36:11.450  6562  7703 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 921, thread name: IncomingSocketThread/Receiver)
09-09 13:36:11.450  6562  7703 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-09 13:36:11.450  6562  7703 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 921, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
09-09 13:36:11.507  1036  1923 W libprocessgroup: failed to open /acct/uid_10093/pid_7123/cgroup.procs: No such file or directory
,09-09 13:36:11.517  1036  1392 E WifiStateMachine: Start Dhcp Watchdog 3
09-09 13:36:11.518  1036  7691 D DhcpStateMachine: StoppedState
09-09 13:36:11.518  1036  7691 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:36:11.518  1036  7691 D DhcpStateMachine: WaitBeforeStartState
09-09 13:36:11.518  1036  1392 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 62 0 rt=144220  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-09 13:36:11.521  1036  1392 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 62 0 rt=144222  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-09 13:36:11.521  3489  4489 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
09-09 13:36:11.522  1036  1392 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 62 0 rt=144223  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-09 13:36:11.525  1036  1392 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=144226  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
,09-09 13:36:11.525  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-09 13:36:11.525  1036  1036 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
09-09 13:36:11.527  1036  1392 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=144227  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-09 13:36:11.527  3489  4489 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@28a75118 on behalf of 7648
09-09 13:36:11.528  1036  1392 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=144230  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-09 13:36:11.531  1036  1392 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1078] from screen [on:0 period:247189003] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-09 13:36:11.534  1036  1392 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:247189006] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-09 13:36:11.534  1036  1392 D WifiNative-wlan0: doString: [SIGNAL_POLL]
09-09 13:36:11.538  4602  7705 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,09-09 13:36:11.596  1036  1051 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7706 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,09-09 13:36:11.602  1036  1392 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 13:36:11.602  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 13:36:11.602  1036  1392 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 13:36:11.602  1036  1392 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 13:36:11.603  1036  1392 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 13:36:11.603  1036  1392 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 13:36:11.603  1036  1435 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
09-09 13:36:11.604  1036  1392 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 13:36:11.604  1036  1435 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
09-09 13:36:11.604  1036  1392 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=173,0,0
09-09 13:36:11.605  1036  1392 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=173,0,0
09-09 13:36:11.605  1036  1392 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
09-09 13:36:11.606  7624  7624 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
09-09 13:36:11.607  1036  1392 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
09-09 13:36:11.607  1036  1392 D WifiNative-wlan0: doBoolean: SET ps 0
09-09 13:36:11.608  1036  1392 D WifiNative-wlan0: SET ps 0: returned true
09-09 13:36:11.608  1036  1392 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
09-09 13:36:11.608  7624  7624 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
09-09 13:36:11.610  1036  1392 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
09-09 13:36:11.610  1036  1392 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
09-09 13:36:11.610  1036  1389 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@245ff8af target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:36:11.610  1036  1392 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-09 13:36:11.610  1036  1389 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@245ff8af target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:36:11.610  1036  7691 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:36:11.611  1036  7691 D DhcpStateMachine: DHCP Start wake lock is acquired.
09-09 13:36:11.611  1036  1392 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
,09-09 13:36:11.617   311   893 D CommandListener: Setting iface cfg
09-09 13:36:11.618   311   893 D CommandListener: Trying to bring up wlan0
09-09 13:36:11.618  1036  1392 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
09-09 13:36:11.620  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-09 13:36:11.620  1036  1036 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-09 13:36:11.620  1036  1392 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 13:36:11.621  1036  1392 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 13:36:11.621  7648  7648 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
09-09 13:36:11.621  1036  1392 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 13:36:11.622  1036  1392 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 13:36:11.622  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-09 13:36:11.622  1036  1036 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-09 13:36:11.623  1036  1392 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 13:36:11.623  1036  1392 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-09 13:36:11.624  1036  1435 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
09-09 13:36:11.624  1036  1392 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
09-09 13:36:11.625  1036  1392 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
09-09 13:36:11.625  1036  1392 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-09 13:36:11.625  1036  1389 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:36:11.625  1036  1389 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:36:11.625  7624  7624 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-09 13:36:11.625  1036  1392 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-09 13:36:11.625  1036  1392 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
09-09 13:36:11.626  7624  7624 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
,09-09 13:36:11.627  1036  1392 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
09-09 13:36:11.627  1036  1392 D WifiNative-wlan0: doBoolean: SET ps 1
09-09 13:36:11.643  1036  1392 D WifiNative-wlan0: SET ps 1: returned true
09-09 13:36:11.644  1036  1435 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
,09-09 13:36:11.644  1036  1392 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-09 13:36:11.645  1036  1392 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-09 13:36:11.645  1036  1392 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
09-09 13:36:11.645  1036  1435 D ConnectivityService: ignoring duplicate network state non-change
09-09 13:36:11.646  7648  7648 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,09-09 13:36:11.648  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 13:36:11.649  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-09 13:36:11.649  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:36:11.650  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:36:11.650  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-09 13:36:11.653  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 13:36:11.657  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:36:11.657  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:36:11.657  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-09 13:36:11.657  1036  1435 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-09 13:36:11.658  1036  1435 D ConnectivityService: Adding iface wlan0 to network 102
,09-09 13:36:11.665  1036  1036 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-09 13:36:11.666  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:36:11.666  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:36:11.666  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-09 13:36:11.667  1945  1945 V WfdStateTracker: handleWifiStateChangedEvent: 1
09-09 13:36:11.669  1036  1392 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-09 13:36:11.672  1036  1036 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-09 13:36:11.674  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 13:36:11.674  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-09 13:36:11.678  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 13:36:11.678  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:36:11.678  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:36:11.678  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-09 13:36:11.681  1036  1435 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-09 13:36:11.681  1036  1435 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
09-09 13:36:11.682  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 13:36:11.682  1605  1605 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-09 13:36:11.683  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 13:36:11.683  1036  1435 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
09-09 13:36:11.684   311   893 E Netd    : netlink response contains error (File exists)
09-09 13:36:11.684  1036  1435 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
09-09 13:36:11.685  1036  1435 D ConnectivityService: addLocalRoutetoDefaultNetwork
09-09 13:36:11.685  1036  1435 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 102
09-09 13:36:11.685  1036  1435 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
09-09 13:36:11.685  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 13:36:11.686  1605  1605 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-09 13:36:11.686  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 13:36:11.686  1036  1435 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-09 13:36:11.686  1036  1435 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-09 13:36:11.687  1036  1435 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,09-09 13:36:11.687  1036  7690 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:36:11.687  1036  7690 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
09-09 13:36:11.687  1036  7690 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:36:11.687  1036  7690 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
09-09 13:36:11.689  1036  1435 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
09-09 13:36:11.690  1036  1435 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 13:36:11.690  1036  1435 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 13:36:11.690  1036  1435 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-09 13:36:11.690  1036  1435 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:36:11.690  1036  1435 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
09-09 13:36:11.690  1036  1435 D ConnectivityService: currentScore = 0, newScore = 20
09-09 13:36:11.690  1036  1435 D ConnectivityService:    accepting network in place of null
09-09 13:36:11.690  1036  1435 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:36:11.691  1036  1392 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:36:11.691  1036  1392 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 13:36:11.691   311  7729 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
09-09 13:36:11.692  1036  1435 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
09-09 13:36:11.692  1036  1435 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
09-09 13:36:11.692  1036  1435 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-09 13:36:11.694  1857  1857 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:36:11.695  1857  1857 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-09 13:36:11.697  1036  1435 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-09 13:36:11.697  1036  1435 D CSLegacyTypeTracker: [,e] list.add(nai) empty : false size: 1
09-09 13:36:11.697  1036  1435 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,09-09 13:36:11.702  1036  1036 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
09-09 13:36:11.702  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-09 13:36:11.703  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-09 13:36:11.703  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-09 13:36:11.704  1036  1435 D ConnectivityService: validation of new default Network = false
09-09 13:36:11.704  1036  1435 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
09-09 13:36:11.704  1036  1435 D DSQN    : enableDataServiceNotify 
09-09 13:36:11.704  1036  1435 D DSQN    : start dsqn bin
09-09 13:36:11.711  1036  1435 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
09-09 13:36:11.711  1036  1435 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:36:11.711  1036  1435 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 13:36:11.711  1036  1435 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 13:36:11.712  1605  2090 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-09 13:36:11.701  7730  7730 W dsqn    : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6841 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-09 13:36:11.701  7730  7730 W dsqn    : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6841 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-09 13:36:11.714  1036  1388 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
09-09 13:36:11.726  7730  7730 E DSQN    : DSQN ssw
,09-09 13:36:11.729  1605  1605 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-09 13:36:11.729  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 13:36:11.730  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 13:36:11.748  7706  7706 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,09-09 13:36:11.768  7706  7706 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
09-09 13:36:11.768  7706  7706 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
09-09 13:36:11.768  7706  7706 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
09-09 13:36:11.768  7706  7706 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
09-09 13:36:11.768  7706  7706 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,09-09 13:36:11.768  7706  7706 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
09-09 13:36:11.773   311  7729 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
09-09 13:36:11.778  6804  6804 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-09 13:36:11.778  6804  6804 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-09 13:36:11.778  6804  6804 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-09 13:36:11.778  6804  6804 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-09 13:36:11.778  6804  6804 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-09 13:36:11.779  6804  6804 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-09 13:36:11.779  6804  6804 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
09-09 13:36:11.779  6804  6804 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-09 13:36:11.779  6804  6804 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-09 13:36:11.779  6804  6804 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-09 13:36:11.779  6804  6804 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
09-09 13:36:11.779  6804  6804 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-09 13:36:11.781  4328  4328 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-09 13:36:11.781  4328  4328 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-09 13:36:11.782  4328  4328 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-09 13:36:11.785  4328  4328 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-09 13:36:11.788  1036  1963 I ActivityManager: Killing 7026:com.google.android.setupwizard/u0a46 (adj 15): empty #17
,09-09 13:36:11.792  4328  7735 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-09 13:36:11.793  4328  7736 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-09 13:36:11.793  4328  7736 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-09 13:36:11.794  4328  7735 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,09-09 13:36:11.810   311  7729 D libc-netbsd: res_queryN name = clients3.google.com succeed
,09-09 13:36:11.812  1036  7691 D DhcpStateMachine: DHCPV4 request on wlan0
09-09 13:36:11.812  1036  7691 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
,09-09 13:36:11.812  1036  7691 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
09-09 13:36:11.801  7737  7737 W dhcpcd  : type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6841 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-09 13:36:11.801  7737  7737 W dhcpcd  : type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6841 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-09 13:36:11.821  7737  7737 I dhcpcd  : version 5.5.6 starting
09-09 13:36:11.822  7737  7737 E dhcpcd  : get_duid: m
09-09 13:36:11.822  7737  7737 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
09-09 13:36:11.822  7737  7737 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,09-09 13:36:11.829  1036  1962 W libprocessgroup: failed to open /acct/uid_10046/pid_7026/cgroup.procs: No such file or directory
09-09 13:36:11.838   311   892 D LGDataListener: argv[0]=dsqncommand
09-09 13:36:11.838   311   892 D LGDataListener: argv[1]=wlan0
,09-09 13:36:11.838   311   892 D LGDataListener: argv[2]=1
09-09 13:36:11.838   311   892 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
09-09 13:36:11.838  1036  1110 D DSQN    : DSQM DsqnNotification wlan0  1
09-09 13:36:11.839  1036  1110 D DSQN    : start to monitor internet connection
09-09 13:36:11.844  4328  7735 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
09-09 13:36:11.852  4328  4328 E LGDMClient: [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
09-09 13:36:11.853  4328  4328 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
09-09 13:36:11.853  4328  4328 D LGDMClient: [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
09-09 13:36:11.856  4328  4328 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [274] : DmConstants.DMAgentState.DMA_STATE_IDLE
,09-09 13:36:11.858  7512  7512 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
09-09 13:36:11.860  7512  7512 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-09 13:36:11.860  7512  7512 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-09 13:36:11.861  4328  4328 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [659] : agentmodeOnOff is OFF. Finish OneDayWiFiCheck
09-09 13:36:11.862  6804  6804 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-09 13:36:11.870  6804  6804 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-09 13:36:11.876  7737  7737 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-09 13:36:11.877  7737  7737 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-09 13:36:11.877  7737  7737 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-09 13:36:11.877  7737  7737 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
09-09 13:36:11.877  7737  7737 D dhcpcd  : wlan0: sending REQUEST (xid 0x1cbdbf9c), next in 4.57 seconds
09-09 13:36:11.878  1036  7690 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 09 Sep 2016 11:36:11 GMT], X-Android-Received-Millis=[1473420971877], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1473420971837]}
09-09 13:36:11.878  1036  7690 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
09-09 13:36:11.878  1036  7690 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
09-09 13:36:11.878  1036  1435 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
09-09 13:36:11.878  1036  1435 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
09-09 13:36:11.878  1036  1435 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 13:36:11.878  1036  1435 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 13:36:11.878  1036  1435 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-09 13:36:11.878  1036  1435 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
09-09 13:36:11.878  1036  1435 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
09-09 13:36:11.879  1036  1435 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:36:11.879  1036  1435 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 13:36:11.879  1036  1435 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 13:36:11.879  1036  1435 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:36:11.879  1036  1435 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-09 13:36:11.879  1605  2090 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-09 13:36:11.880  1857  1857 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:36:11.880  1857  1857 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-09 13:36:11.880  1036  1392 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:36:11.880  1036  1392 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 13:36:11.890  7512  7512 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-09 13:36:11.892   311  7750 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
09-09 13:36:11.893   311  7750 D libc-netbsd: res_queryN name = static-avc.lglime.com, class = 1, type = 1
09-09 13:36:11.895  6804  6804 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-09 13:36:11.902  6804  6804 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 13:36:11.907  1605  1605 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-09 13:36:11.908  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 13:36:11.908  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 13:36:11.915  7512  7512 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-09 13:36:11.919  6804  6804 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-09 13:36:11.926  6804  6804 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 13:36:11.940  4328  4328 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-09 13:36:11.941  4328  4328 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-09 13:36:11.942  4328  4328 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-09 13:36:11.942  7737  7737 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
,09-09 13:36:11.944  4328  4328 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-09 13:36:11.945  6562  6617 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
09-09 13:36:11.946  6562  6617 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
09-09 13:36:11.949  6562  6617 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@306f7921 Bundle[{}]
09-09 13:36:11.950  6562  6617 I io.jxcore.node.LifeCycleMonitor: start: OK
09-09 13:36:11.950  6562  6617 I io.jxcore.node.LifeCycleMonitor: stop: OK
09-09 13:36:11.951  6562  6617 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
09-09 13:36:11.951  6562  6617 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-09 13:36:11.952  6562  6617 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
09-09 13:36:11.953  6562  6617 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-09 13:36:11.957  4328  7751 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,09-09 13:36:11.958   311  7750 D libc-netbsd: res_queryN name = static-avc.lglime.com succeed
09-09 13:36:11.958  4328  7751 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
09-09 13:36:11.966  6562  7753 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
09-09 13:36:11.966  6562  7753 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-09 13:36:11.968  1036  1051 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7754 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
09-09 13:36:11.975  4328  7752 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-09 13:36:11.975  4328  7752 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-09 13:36:11.976  7737  7737 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
09-09 13:36:11.976  7737  7737 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
09-09 13:36:11.976  7737  7737 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
09-09 13:36:11.977  7737  7737 D dhcpcd  : wlan0: adding default route via 192.168.1.1
09-09 13:36:11.977  7737  7737 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-09 13:36:11.977  7737  7737 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-09 13:36:11.977  7737  7737 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-09 13:36:11.977  7737  7737 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
09-09 13:36:11.977  6562  7753 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
09-09 13:36:11.977  6562  7753 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-09 13:36:11.978  6562  7753 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-09 13:36:11.978  6562  7753 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-09 13:36:11.978  4328  7751 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
09-09 13:36:11.978  6562  7761 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
09-09 13:36:11.978  6562  7761 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-09 13:36:11.978  6562  7761 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-09 13:36:11.979  6562  7753 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
09-09 13:36:11.979  6562  7761 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-09 13:36:11.979  6562  7761 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
09-09 13:36:11.980  4328  4328 E LGDMClient: [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
09-09 13:36:11.980  4328  4328 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
09-09 13:36:11.981  4328  4328 D LGDMClient: [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
09-09 13:36:11.981  6562  7772 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 932, name: OutgoingSocketThread/Sender)
09-09 13:36:11.982  6562  7775 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 934, name: IncomingSocketThread/Sender)
09-09 13:36:11.982  4328  4328 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [274] : DmConstants.DMAgentState.DMA_STATE_IDLE
09-09 13:36:11.982  6562  7774 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 933, name: OutgoingSocketThread/Receiver)
09-09 13:36:11.982  6562  7774 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 933, thread name: ,OutgoingSocketThread/Receiver)
09-09 13:36:11.982  6562  7774 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-09 13:36:11.982  6562  7774 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 933, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-09 13:36:11.987  6562  7776 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 935, name: IncomingSocketThread/Receiver)
09-09 13:36:11.987  6562  7776 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 935, thread name: IncomingSocketThread/Receiver)
09-09 13:36:11.987  6562  7776 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-09 13:36:11.987  6562  7776 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 935, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
09-09 13:36:11.989  4328  4328 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [659] : agentmodeOnOff is OFF. Finish OneDayWiFiCheck
09-09 13:36:11.997  1036  1051 V SIM_STK : Menu title from STK is T-Mobile
,09-09 13:36:12.009  4602  7705 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 471 ms] updated apps [took 471 ms] 
,09-09 13:36:12.029  1036  1435 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:36:12.031  1036  1435 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-09 13:36:12.032  1036  1112 D Tethering: MasterInitialState.processMessage what=3
09-09 13:36:12.034  1036  1112 D Tethering: MasterInitialState.processMessage what=3
09-09 13:36:12.037  6562  6562 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:36:12.037  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:36:12.037  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:36:12.037  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:36:12.037  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:36:12.037  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:36:12.037  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:36:12.037  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:36:12.038  5701  5701 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
09-09 13:36:12.039  6562  6562 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:36:12.042  5701  5701 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
09-09 13:36:12.044  6562  6562 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:36:12.044  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:36:12.044  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:36:12.044  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:36:12.044  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:36:12.044  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:36:12.044  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:36:12.044  6562  6562 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:36:12.047  6562  6562 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 13:36:12.049  6562  6562 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:36:12.050  6562  6562 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:36:12.054  7754  7754 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-09 13:36:12.054  7754  7754 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
09-09 13:36:12.058  7754  7754 V [BNRBootReceiver]: Boot Receiver Return
09-09 13:36:12.061  6373  6373 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-09 13:36:12.064  7754  7754 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
09-09 13:36:12.068  6804  6804 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-09 13:36:12.073  6804  6804 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-09 13:36:12.078  6825  6825 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-09 13:36:12.078  6825  6825 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 13:36:12.079  6825  6825 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-09 13:36:12.081  6804  6804 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
09-09 13:36:12.083  6804  6804 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
09-09 13:36:12.086  1036  1092 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-09 13:36:12.086  6373  6373 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-09 13:36:12.087  1036  1092 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-09 13:36:12.088  1036  1092 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 13:36:12.088  1036  1092 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 13:36:12.090  6804  6804 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-09 13:36:12.094  6804  6804 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 13:36:12.098  6825  6825 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-09 13:36:12.099  6825  6825 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-09 13:36:12.100  6825  6825 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-09 13:36:12.102  6373  6373 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-09 13:36:12.108  6804  6804 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 13:36:12.112  6804  6804 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 13:36:12.116  6825  6825 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-09 13:36:12.117  6825  6825 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 13:36:12.117  6825  6825 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-09 13:36:12.121  6373  6373 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-09 13:36:12.126  6804  6804 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-09 13:36:12.131  6804  6804 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 13:36:12.135  6825  6825 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-09 13:36:12.135  6825  6825 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 13:36:12.135  6825  6825 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-09 13:36:12.138  6373  6373 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-09 13:36:12.143  6804  6804 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 13:36:12.150  6804  6804 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 13:36:12.155  6825  6825 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-09 13:36:12.155  6825  6825 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 13:36:12.155  6825  6825 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-09 13:36:12.159  6373  6373 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-09 13:36:12.164  6804  6804 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 13:36:12.171  6804  6804 D WiFiOffLoadBroadcast: MCCMNC not supported: null,
09-09 13:36:12.182  6825  6825 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-09 13:36:12.183  6825  6825 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 13:36:12.183  6825  6825 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-09 13:36:12.191  6373  6373 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-09 13:36:12.202  6804  6804 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 13:36:12.211  6804  6804 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 13:36:12.217  1036  7691 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,09-09 13:36:12.219  1036  7691 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
09-09 13:36:12.219  1036  7691 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-09 13:36:12.219  1036  7691 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
09-09 13:36:12.220  1036  7691 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
09-09 13:36:12.220  1036  7691 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-09 13:36:12.220  1036  7691 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
09-09 13:36:12.220  1036  7691 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
09-09 13:36:12.222  1036  7691 D DhcpStateMachine: RunningState
09-09 13:36:12.222  6825  6825 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-09 13:36:12.223  6825  6825 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 13:36:12.223  6825  6825 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-09 13:36:12.232  6373  6373 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-09 13:36:12.252  6804  6804 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 13:36:12.263  6804  6804 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-09 13:36:12.274  6825  6825 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-09 13:36:12.275  6825  6825 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 13:36:12.277  6825  6825 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-09 13:36:12.286  6373  6373 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-09 13:36:12.300  6804  6804 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 13:36:12.307  6804  6804 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 13:36:12.321  6825  6825 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-09 13:36:12.321  6825  6825 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 13:36:12.323  6825  6825 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-09 13:36:12.328  6373  6373 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-09 13:36:12.336  7512  7512 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,09-09 13:36:12.341  7512  7512 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
09-09 13:36:12.345  6804  6804 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 13:36:12.351  6804  6804 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 13:36:12.361  6825  6825 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-09 13:36:12.361  6825  6825 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 13:36:12.362  6825  6825 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
09-09 13:36:12.363  6825  6825 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-09 13:36:12.364  6825  6825 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,09-09 13:36:12.371  6373  6373 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-09 13:36:12.378  7512  7512 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
09-09 13:36:12.380  7512  7512 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,09-09 13:36:12.387  6804  6804 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-09 13:36:12.402  6804  6804 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-09 13:36:12.417  6825  6825 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-09 13:36:12.418  6825  6825 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-09 13:36:12.420  6825  6825 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
09-09 13:36:12.422  6825  6825 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-09 13:36:12.423  6825  6825 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
09-09 13:36:12.433  6373  6373 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
09-09 13:36:12.437  6373  6422 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,09-09 13:36:12.475  2180  2180 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:36:12.481  6562  6617 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 944)
09-09 13:36:12.482  6562  6617 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
09-09 13:36:12.482  6562  6617 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 945)
09-09 13:36:12.490  6562  6617 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 13:36:12.490  6562  6617 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2419ea6 added. We now have 3 listener(s)
09-09 13:36:12.490  1036  2036 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-09 13:36:12.491   311  7802 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
09-09 13:36:12.492   311  7802 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
09-09 13:36:12.494  7574  7574 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-09 13:36:12.494  7574  7574 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-09 13:36:12.497  7574  7574 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-09 13:36:12.497  7574  7574 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-09 13:36:12.498  6562  6617 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-09 13:36:12.498  6562  6617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 13:36:12.498  6562  6617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 13:36:12.498  1036  1377 V AlarmManager: ELAPSED_WAKEUP set : Alarm{25c22e33 type 2 when 145198 com.google.android.gms} when 145198
09-09 13:36:12.498  6562  6617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 13:36:12.498  6562  6617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eab50e7 added. We now have 3 listener(s)
09-09 13:36:12.498  6562  6617 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 13:36:12.498  6562  6617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-09 13:36:12.499  7574  7574 I AppUp4:CustModeStarterReceiver: onReceive
09-09 13:36:12.501  6562  6617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:36:12.506  7574  7574 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@3ce18c58
09-09 13:36:12.506  7574  7574 D AppUp4:CustFacade: isCustomizationCompleted : false
09-09 13:36:12.506  7574  7574 D AppUp4:CustFacade: isPhone : true
09-09 13:36:12.506  6562  6617 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:36:12.506  6562  6617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:36:12.506  6562  6617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-09 13:36:12.506  6562  6617 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:36:12.506  6562  6617 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:36:12.506  6562  6617 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:36:12.506  6562  6617 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:36:12.506  6562  6617 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:36:12.507  7574  7574 D AppUp4:CustModeStarterReceiver: begin check event
09-09 13:36:12.507  7574  7574 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
09-09 13:36:12.507  7574  7574 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
09-09 13:36:12.508  6562  6617 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:36:12.508  6562  6617 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 13:36:12.509  7574  7604 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
,09-09 13:36:12.509  7574  7604 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
09-09 13:36:12.509  7574  7604 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
09-09 13:36:12.513  6562  6617 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:36:12.513  6562  6617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:36:12.513  6562  6617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:36:12.513  6562  6617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 13:36:12.513  6562  6617 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2419ea6 removed from the list
09-09 13:36:12.513  6562  6617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:36:12.513  6562  6617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eab50e7 removed from the list
09-09 13:36:12.513  4328  4328 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-09 13:36:12.513  4328  4328 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-09 13:36:12.514  6562  6562 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:36:12.514  6562  6617 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:36:12.514  6562  6617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:36:12.515  6562  6617 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 13:36:12.515  6562  6617 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-09 13:36:12.515  6562  6617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-09 13:36:12.515  6562  6617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:36:12.515  6562  6617 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-09 13:36:12.515  4328  4328 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-09 13:36:12.516  6562  6562 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:36:12.518  4328  4328 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-09 13:36:12.522  6562  6617 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-09 13:36:12.525  1036  1981 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 13:36:12.525  4328  7803 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-09 13:36:12.527  3489  3489 V DownloadManager: Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:36:12.530  6562  6617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-09 13:36:12.530  3489  3489 V DownloadManager: DownloadService onCreate
09-09 13:36:12.531  6562  6617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-09 13:36:12.533  6562  6617 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 13:36:12.534  4328  7803 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
09-09 13:36:12.538  3489  7805 I DownloadManager: in removeSpuriousFiles
09-09 13:36:12.538  3489  7805 V DownloadManager: starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
09-09 13:36:12.541  3489  7805 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@1a830771 on behalf of 3489
09-09 13:36:12.541  3489  7805 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
09-09 13:36:12.541  3489  7805 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGEIME_5.1.29_release_repacked_ARM_XT9_MYSCRIPT_20160317004155539.apk
09-09 13:36:12.542  3489  7805 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_5.1.24_COM_COM(9012_VDF)_20160401022656759.apk
09-09 13:36:12.542  3489  7805 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
09-09 13:36:12.542  3489  7805 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
09-09 13:36:12.542  3489  7805 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
09-09 13:36:12.542  3489  7805 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
09-09 13:36:12.542  3489  7805 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/ConciergeBoard_4.40.12_COM_COM(VDF)_20160126234417577.apk
09-09 13:36:12.542  3489  7805 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
09-09 13:36:12.542  3489  7805 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
09-09 13:36:12.543  3489  7805 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
,09-09 13:36:12.544  3489  7805 I DownloadManager: in trimDatabase
09-09 13:36:12.544  4328  7804 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-09 13:36:12.544  4328  7804 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-09 13:36:12.545  3489  7805 V DownloadManager: starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
09-09 13:36:12.546  3489  7805 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@1d961dd7 on behalf of 3489
09-09 13:36:12.569  1036  2036 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7808 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
09-09 13:36:12.571  3489  3489 V DownloadManager: DownloadService onStartCommand
,09-09 13:36:12.573  6562  6617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:36:12.574  4328  7803 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
09-09 13:36:12.574  3489  7806 V DownloadManager: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
09-09 13:36:12.576  6562  6617 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-09 13:36:12.577  3489  7806 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@146fa9ad on behalf of 3489
09-09 13:36:12.577  4328  4328 E LGDMClient: [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
09-09 13:36:12.577  4328  4328 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
09-09 13:36:12.578  4328  4328 D LGDMClient: [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
09-09 13:36:12.579  4328  4328 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [274] : DmConstants.DMAgentState.DMA_STATE_IDLE
09-09 13:36:12.579  3489  7806 V DownloadManager: processing inserted download 1
09-09 13:36:12.582  3489  7806 V DownloadManager: processing inserted download 4
09-09 13:36:12.583  4328  4328 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [659] : agentmodeOnOff is OFF. Finish OneDayWiFiCheck
09-09 13:36:12.583  3489  7806 V DownloadManager: processing inserted download 7
,09-09 13:36:12.584  3489  7806 V DownloadManager: processing inserted download 8
09-09 13:36:12.585  3489  7806 V DownloadManager: processing inserted download 9
09-09 13:36:12.587  3489  7806 V DownloadManager: processing inserted download 10
09-09 13:36:12.588  3489  7806 V DownloadManager: processing inserted download 11
09-09 13:36:12.589  3489  7806 V DownloadManager: processing inserted download 12
09-09 13:36:12.591  3489  7806 V DownloadManager: processing inserted download 13
09-09 13:36:12.592  3489  7806 V DownloadManager: processing inserted download 14
09-09 13:36:12.593  3489  7806 V DownloadManager: processing inserted download 16
09-09 13:36:12.596  3489  3489 V DownloadManager: DownloadService onDestroy
,09-09 13:36:12.611  6851  7748 V FormManager: There are no updated forms. The schedule will be deleted.
,09-09 13:36:12.614  6851  7748 V FormManager: Alarm would be updated, because LastCheckTime has been updated.
,09-09 13:36:12.637  7808  7808 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-09 13:36:12.637  7808  7808 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-09 13:36:12.638  7808  7808 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-09 13:36:12.639  7808  7808 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-09 13:36:12.678  1036  1392 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,09-09 13:36:12.678  1036  1392 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-09 13:36:12.678  1036  1392 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-09 13:36:12.679  1036  1392 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-09 13:36:12.679  1036  1392 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-09 13:36:12.680  1036  1392 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-09 13:36:12.680  1036  1435 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=true
09-09 13:36:12.680  1036  1435 D ConnectivityService: identical MTU - not setting
09-09 13:36:12.680  1036  1435 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-09 13:36:12.680  1036  1435 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-09 13:36:12.681  1036  1435 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:36:12.681  1036  1435 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 13:36:12.681  1036  1435 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
09-09 13:36:12.682  1605  2090 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
09-09 13:36:12.692  6851  7826 V FormManager: There are no updated forms. The schedule will be deleted.
,09-09 13:36:12.697  6851  7826 V FormManager: Alarm would be updated, because LastCheckTime has been updated.
09-09 13:36:12.711  1036  1435 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,09-09 13:36:12.732  7808  7808 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,09-09 13:36:12.747  7808  7808 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,09-09 13:36:12.775  6851  7828 V FormManager: There are no updated forms. The schedule will be deleted.
,09-09 13:36:12.778  6851  7828 V FormManager: Alarm would be updated, because LastCheckTime has been updated.
,09-09 13:36:12.803  7808  7808 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-09 13:36:12.807  1036  1962 I ActivityManager: Killing 7100:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
,09-09 13:36:12.869  1036  1616 W libprocessgroup: failed to open /acct/uid_10005/pid_7100/cgroup.procs: No such file or directory
,09-09 13:36:12.916  7808  7808 D LgDataFeature: LgDataFeature() Constructor: none
,09-09 13:36:12.916  7808  7808 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-09 13:36:13.057  7808  7808 D eas_req : ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,09-09 13:36:13.103  7808  7808 I HubEmail: JNI_OnLoad()
09-09 13:36:13.103  7808  7808 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,09-09 13:36:13.103  7808  7808 I HubEmail: registerNatives()
09-09 13:36:13.103  7808  7808 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-09 13:36:13.103  7808  7808 I HubEmail: registerNativeMethods()
09-09 13:36:13.103  7808  7808 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-09 13:36:13.103  7808  7808 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
09-09 13:36:13.116  3423  3423 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-09 13:36:13.116  3423  3423 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-09 13:36:13.116  3423  3423 I LgeMiscReceiver: networkInfo.isConnected() = false
09-09 13:36:13.169  6851  7838 V FormManager: There are no updated forms. The schedule will be deleted.
,09-09 13:36:13.176  6851  7838 V FormManager: Alarm would be updated, because LastCheckTime has been updated.
09-09 13:36:13.179  1036  1051 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7841 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
09-09 13:36:13.181  7808  7840 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-09 13:36:13.212   343   343 I art     : Explicit concurrent mark sweep GC freed 704(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 458us total 33.577ms
09-09 13:36:13.214  1036  1780 I ActivityManager: Killing 7270:com.lge.lifetracker/u0a37 (adj 15): empty #17
09-09 13:36:13.233   343   343 I art     : Explicit concurrent mark sweep GC freed 7(224B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 439us total 20.214ms
,09-09 13:36:13.254   343   343 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 441us total 20.087ms
,09-09 13:36:13.272  7841  7841 D LgDataFeature: LgDataFeature() Constructor: none
09-09 13:36:13.272  7841  7841 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-09 13:36:13.274  7841  7841 D PhoneMonitor: Register our PhoneStateListener
09-09 13:36:13.287  1036  1616 W libprocessgroup: failed to open /acct/uid_10037/pid_7270/cgroup.procs: No such file or directory
,09-09 13:36:13.306  7841  7841 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,09-09 13:36:13.308  7841  7841 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-09 13:36:13.324  7841  7841 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
09-09 13:36:13.325  7841  7841 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
09-09 13:36:13.327  7841  7841 D TelephonyAutoProfiling: [parse] Load xml
,09-09 13:36:13.335  7841  7841 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
09-09 13:36:13.335  7841  7841 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
09-09 13:36:13.335  7841  7841 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
09-09 13:36:13.335  7841  7841 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
09-09 13:36:13.335  7841  7841 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
09-09 13:36:13.336  7841  7841 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
09-09 13:36:13.336  7841  7841 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
09-09 13:36:13.336  7841  7841 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
,09-09 13:36:13.336  7841  7841 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
09-09 13:36:13.336  7841  7841 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
09-09 13:36:13.336  7841  7841 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
09-09 13:36:13.336  7841  7841 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
09-09 13:36:13.336  7841  7841 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
,09-09 13:36:13.336  7841  7841 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
09-09 13:36:13.336  7841  7841 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
09-09 13:36:13.337  7841  7841 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
09-09 13:36:13.337  7841  7841 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
,09-09 13:36:13.346  1036  1943 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7860 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-09 13:36:13.350  1036  1943 I ActivityManager: Killing 7317:com.lge.settings.easy/1000 (adj 15): empty #17
09-09 13:36:13.355  7841  7841 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
09-09 13:36:13.389  1036  1781 W libprocessgroup: failed to open /acct/uid_1000/pid_7317/cgroup.procs: No such file or directory
,09-09 13:36:13.413  1821  7877 I CheckinService: active receiver: disabled
09-09 13:36:13.623  1036  1052 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7879 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
09-09 13:36:13.624  1036  1052 I ActivityManager: Killing 7535:com.google.android.talk/u0a72 (adj 15): empty #17
,09-09 13:36:13.749  1036  2035 W libprocessgroup: failed to open /acct/uid_10072/pid_7535/cgroup.procs: No such file or directory
,09-09 13:36:13.918  1036  1981 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7899 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-09 13:36:13.921  1036  1981 I ActivityManager: Killing 7606:com.android.contacts/u0a19 (adj 15): empty #17
09-09 13:36:13.972  1036  1389 D LGWifiP2pService: InactiveState{ when=-3ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:36:13.973  1036  1389 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:36:13.973  1036  1389 D LGWifiP2pService: DefaultState{ when=-3ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,09-09 13:36:13.979  1036  1052 W libprocessgroup: failed to open /acct/uid_10019/pid_7606/cgroup.procs: No such file or directory
09-09 13:36:14.011  7899  7899 I art     : Almond Protected OAT
,09-09 13:36:14.033  1036  1392 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT_FAILED 2 0
09-09 13:36:14.034  1036  1392 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT_FAILED 2 0
09-09 13:36:14.035  1036  1392 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 2 0
09-09 13:36:14.036  1036  1392 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 2 0
09-09 13:36:14.037  1036  1392 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 2 0
09-09 13:36:14.037  1036  1392 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
09-09 13:36:14.083  7899  7899 D WeatherApplication: removeAccount
,09-09 13:36:14.086  7899  7899 D WeatherApplication: Account.length = 0
,09-09 13:36:14.086  7899  7899 E WeatherApplication: OPERATOR:OPEN
,09-09 13:36:14.110  7899  7899 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:36:14
,09-09 13:36:14.118  7899  7899 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
,09-09 13:36:14.118  7899  7899 D Weather.Utils: 2 : All the weather widget is gone.
,09-09 13:36:14.120  7899  7899 D UpdateThreadPoolManager: 2 : This is isUpdating : false
,09-09 13:36:14.123  7899  7899 D WeatherAncestor: connectivity changed - connection : true
09-09 13:36:14.125  7899  7899 D WeatherService: 2 : isServiceAlived():false forecastCache:null
09-09 13:36:14.138  7899  7899 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
,09-09 13:36:14.138  7899  7899 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
,09-09 13:36:14.138  7899  7899 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
09-09 13:36:14.160  7899  7899 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-09 13:36:14.160  7899  7899 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:36:14
09-09 13:36:14.222  1036  2036 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7917 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-09 13:36:14.235  1036  2036 I ActivityManager: Killing 7628:com.android.gallery3d/u0a27 (adj 15): empty #17
,09-09 13:36:14.295  1036  1616 W libprocessgroup: failed to open /acct/uid_10027/pid_7628/cgroup.procs: No such file or directory
,09-09 13:36:14.534  1036  1051 I art     : Explicit concurrent mark sweep GC freed 83853(3MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/65MB, paused 2.579ms total 152.104ms
,09-09 13:36:14.574   280   398 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-09 13:36:14.574   280   398 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
,09-09 13:36:14.574   280   398 W Vold    : Returning OperationFailed - no handler for errno 0
09-09 13:36:14.575  7917  7936 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,09-09 13:36:14.576   280   398 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-09 13:36:14.576   280   398 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
09-09 13:36:14.576   280   398 W Vold    : Returning OperationFailed - no handler for errno 0
09-09 13:36:14.576  7917  7936 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
09-09 13:36:14.584   280   398 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-09 13:36:14.584   280   398 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
09-09 13:36:14.584   280   398 W Vold    : Returning OperationFailed - no handler for errno 0
09-09 13:36:14.589  7917  7938 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,09-09 13:36:14.594   280   398 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-09 13:36:14.594   280   398 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
09-09 13:36:14.594   280   398 W Vold    : Returning OperationFailed - no handler for errno 0
09-09 13:36:14.595  7917  7938 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
09-09 13:36:14.602  1036  1392 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2437 sc=60 link=72 tx=86.5, 0.0, 0.0  rx=99.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:247192074] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-09 13:36:14.603  1036  1392 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2437 sc=60 link=72 tx=86.5, 0.0, 0.0  rx=99.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:247192075] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-09 13:36:14.603  1036  1392 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,09-09 13:36:14.613  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-09 13:36:14.666  1036  1393 V WifiInternetCheck: Single check msg out of sync, ignoring.
,09-09 13:36:14.698  1036  1435 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:36:14.703  1036  1112 D Tethering: MasterInitialState.processMessage what=3
09-09 13:36:14.710  1036  1092 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-09 13:36:14.720  6562  6562 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:36:14.723  6562  6562 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:36:14.724  5701  5701 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
09-09 13:36:14.728  1036  1092 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 13:36:14.873  7917  7917 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,09-09 13:36:14.885  7917  7917 I LibraryLoader: Loading: webviewchromium
,09-09 13:36:14.889  7917  7917 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 7598-7602)
,09-09 13:36:14.889  7917  7917 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-09 13:36:14.899  7917  7917 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2656c31e}
,09-09 13:36:14.903  7917  7917 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-09 13:36:14.904  7917  7917 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,09-09 13:36:14.928  7917  7917 I BrowserStartupController: Initializing chromium process, renderers=0
09-09 13:36:14.930  7917  7917 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-09 13:36:14.944  7917  7917 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
09-09 13:36:14.946  7917  7917 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
,09-09 13:36:14.948  7917  7917 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
09-09 13:36:14.950   315  1403 V AudioPolicyService: registerClient() client 0xb558a580, uid 10093
09-09 13:36:14.951  7917  7960 W AudioManagerAndroid: Requires BLUETOOTH permission
09-09 13:36:14.970  7917  7917 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-09 13:36:14.970  7917  7917 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-09 13:36:14.970  7917  7917 I Adreno-EGL: Build Date: 12/12/14 금
09-09 13:36:14.970  7917  7917 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-09 13:36:14.970  7917  7917 I Adreno-EGL: Remote Branch: 
09-09 13:36:14.970  7917  7917 I Adreno-EGL: Local Patches: 
09-09 13:36:14.970  7917  7917 I Adreno-EGL: Reconstruct Branch: 
,09-09 13:36:15.054  7917  7917 I NSApplication: Starting up...
,09-09 13:36:15.087  1036  1981 I ActivityManager: Killing 7648:com.android.vending/u0a44 (adj 15): empty #17
,09-09 13:36:15.161  1036  1943 W libprocessgroup: failed to open /acct/uid_10044/pid_7648/cgroup.procs: No such file or directory
,09-09 13:36:15.188  6373  6373 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,09-09 13:36:15.193  6373  6422 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-09 13:36:15.216  2180  2180 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:36:15.230  7574  7574 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-09 13:36:15.230  7574  7574 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-09 13:36:15.230  7574  7574 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-09 13:36:15.230  7574  7574 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,09-09 13:36:15.234  7574  7574 I AppUp4:CustModeStarterReceiver: onReceive
09-09 13:36:15.239  7574  7574 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@3ce18c58
09-09 13:36:15.239  7574  7574 D AppUp4:CustFacade: isCustomizationCompleted : false
09-09 13:36:15.239  7574  7574 D AppUp4:CustFacade: isPhone : true
09-09 13:36:15.240  7574  7574 D AppUp4:CustModeStarterReceiver: begin check event
09-09 13:36:15.240  7574  7574 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-09 13:36:15.251  4328  4328 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:36:15.252  4328  4328 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-09 13:36:15.255  4328  4328 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-09 13:36:15.260  4328  4328 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-09 13:36:15.267  4328  7979 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,09-09 13:36:15.269  3489  3489 V DownloadManager: Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:36:15.274  4328  7980 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-09 13:36:15.274  4328  7980 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-09 13:36:15.276  3489  3489 V DownloadManager: DownloadService onCreate
09-09 13:36:15.282  3489  7981 I DownloadManager: in removeSpuriousFiles
09-09 13:36:15.282  3489  7981 V DownloadManager: starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
09-09 13:36:15.283  3489  7981 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@1b34c073 on behalf of 3489
09-09 13:36:15.285  3489  7981 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
09-09 13:36:15.285  3489  7981 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGEIME_5.1.29_release_repacked_ARM_XT9_MYSCRIPT_20160317004155539.apk
09-09 13:36:15.285  3489  7981 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_5.1.24_COM_COM(9012_VDF)_20160401022656759.apk
09-09 13:36:15.285  3489  7981 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
09-09 13:36:15.285  3489  7981 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
,09-09 13:36:15.285  3489  7981 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
09-09 13:36:15.285  3489  7981 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
09-09 13:36:15.286  3489  7981 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/ConciergeBoard_4.40.12_COM_COM(VDF)_20160126234417577.apk
09-09 13:36:15.286  3489  7981 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
09-09 13:36:15.286  3489  7981 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
09-09 13:36:15.286  3489  7981 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
09-09 13:36:15.289  4328  7979 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
09-09 13:36:15.290  3489  7981 I DownloadManager: in trimDatabase
09-09 13:36:15.290  3489  7981 V DownloadManager: starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
09-09 13:36:15.291  3489  7981 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@270a33a9 on behalf of 3489
09-09 13:36:15.295  3489  3489 V DownloadManager: DownloadService onStartCommand
09-09 13:36:15.296  3489  7982 V DownloadManager: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
09-09 13:36:15.302  3489  7982 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@3d10f0cf on behalf of 3489
,09-09 13:36:15.303  4328  7979 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
09-09 13:36:15.311  4328  4328 E LGDMClient: [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
09-09 13:36:15.312  3423  3423 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-09 13:36:15.312  3489  7982 V DownloadManager: processing inserted download 1
09-09 13:36:15.312  3423  3423 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-09 13:36:15.312  4328  4328 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
09-09 13:36:15.313  4328  4328 D LGDMClient: [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
09-09 13:36:15.313  3423  3423 I LgeMiscReceiver: networkInfo.isConnected() = false
09-09 13:36:15.313  3489  7982 V DownloadManager: processing inserted download 4
09-09 13:36:15.314  4328  4328 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [274] : DmConstants.DMAgentState.DMA_STATE_IDLE
09-09 13:36:15.315  3489  7982 V DownloadManager: processing inserted download 7
09-09 13:36:15.318  3489  7982 V DownloadManager: processing inserted download 8
09-09 13:36:15.318  4328  4328 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [659] : agentmodeOnOff is OFF. Finish OneDayWiFiCheck
,09-09 13:36:15.321  7841  7841 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-09 13:36:15.321  7841  7841 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-09 13:36:15.321  7808  7985 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:36:15.327  3489  7982 V DownloadManager: processing inserted download 9
09-09 13:36:15.329  3489  7982 V DownloadManager: processing inserted download 10
09-09 13:36:15.331  7899  7899 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:36:15
09-09 13:36:15.332  3489  7982 V DownloadManager: processing inserted download 11
,09-09 13:36:15.333  7899  7899 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
,09-09 13:36:15.333  7899  7899 D Weather.Utils: 2 : All the weather widget is gone.
09-09 13:36:15.333  7899  7899 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-09 13:36:15.333  7899  7899 D WeatherAncestor: connectivity changed - connection : true
09-09 13:36:15.333  7899  7899 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@a39c7ed
09-09 13:36:15.334  3489  7982 V DownloadManager: processing inserted download 12
09-09 13:36:15.335  7899  7899 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
,09-09 13:36:15.335  7899  7899 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-09 13:36:15.335  7899  7899 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-09 13:36:15.335  7899  7899 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-09 13:36:15.336  7899  7899 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:36:15
09-09 13:36:15.336  3489  7982 V DownloadManager: processing inserted download 13
09-09 13:36:15.338  3489  7982 V DownloadManager: processing inserted download 14
09-09 13:36:15.340  3489  7982 V DownloadManager: processing inserted download 16
09-09 13:36:15.345  3489  3489 V DownloadManager: DownloadService onDestroy
,09-09 13:36:15.366  2180  2180 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,09-09 13:36:15.372  6851  7987 V FormManager: There are no updated forms. The schedule will be deleted.
09-09 13:36:15.377  6851  7987 V FormManager: Alarm would be updated, because LastCheckTime has been updated.
09-09 13:36:15.382  6373  6373 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,09-09 13:36:15.387  6373  6422 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-09 13:36:15.402  2180  2180 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:36:15.411  7574  7574 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-09 13:36:15.411  7574  7574 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:36:15.411  7574  7574 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-09 13:36:15.411  7574  7574 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-09 13:36:15.412  7574  7574 I AppUp4:CustModeStarterReceiver: onReceive
,09-09 13:36:15.417  7574  7574 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@3ce18c58
09-09 13:36:15.417  7574  7574 D AppUp4:CustFacade: isCustomizationCompleted : false
09-09 13:36:15.417  7574  7574 D AppUp4:CustFacade: isPhone : true
09-09 13:36:15.418  7574  7574 D AppUp4:CustModeStarterReceiver: begin check event
09-09 13:36:15.418  7574  7574 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-09 13:36:15.422  4328  4328 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-09 13:36:15.423  4328  4328 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-09 13:36:15.425  4328  4328 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-09 13:36:15.427  4328  4328 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-09 13:36:15.433  4328  7995 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-09 13:36:15.433  3489  3489 V DownloadManager: Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
09-09 13:36:15.435  3489  3489 V DownloadManager: DownloadService onCreate
09-09 13:36:15.435  4328  7996 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-09 13:36:15.436  4328  7996 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-09 13:36:15.436  4328  7995 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
09-09 13:36:15.440  3489  7997 I DownloadManager: in removeSpuriousFiles
09-09 13:36:15.441  3489  7997 V DownloadManager: starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,09-09 13:36:15.442  3489  7997 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@11a96165 on behalf of 3489
09-09 13:36:15.443  3489  7997 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
09-09 13:36:15.443  3489  7997 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGEIME_5.1.29_release_repacked_ARM_XT9_MYSCRIPT_20160317004155539.apk
09-09 13:36:15.443  3489  7997 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_5.1.24_COM_COM(9012_VDF)_20160401022656759.apk
09-09 13:36:15.443  3489  7997 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
09-09 13:36:15.443  3489  7997 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
09-09 13:36:15.443  3489  7997 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
09-09 13:36:15.443  3489  7997 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
09-09 13:36:15.444  3489  7997 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/ConciergeBoard_4.40.12_COM_COM(VDF)_20160126234417577.apk
09-09 13:36:15.444  3489  7997 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
09-09 13:36:15.444  3489  7997 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
09-09 13:36:15.444  3489  7997 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
,09-09 13:36:15.446  3489  7997 I DownloadManager: in trimDatabase
09-09 13:36:15.446  3489  7997 V DownloadManager: starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
09-09 13:36:15.448  3489  7997 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@22d5caeb on behalf of 3489
09-09 13:36:15.448  4328  7995 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
09-09 13:36:15.451  3489  3489 V DownloadManager: DownloadService onStartCommand
09-09 13:36:15.452  3489  7998 V DownloadManager: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
09-09 13:36:15.453  3489  7998 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@3853aee1 on behalf of 3489
,09-09 13:36:15.457  4328  4328 E LGDMClient: [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
09-09 13:36:15.458  4328  4328 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
09-09 13:36:15.458  4328  4328 D LGDMClient: [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
09-09 13:36:15.460  4328  4328 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [274] : DmConstants.DMAgentState.DMA_STATE_IDLE
09-09 13:36:15.462  7808  8000 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:36:15.464  4328  4328 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [659] : agentmodeOnOff is OFF. Finish OneDayWiFiCheck
09-09 13:36:15.465  3423  3423 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-09 13:36:15.465  3423  3423 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-09 13:36:15.465  3423  3423 I LgeMiscReceiver: networkInfo.isConnected() = true
09-09 13:36:15.465  3423  3423 D PhoneState: setPdpRejectCasuse : false
09-09 13:36:15.469  3489  7998 V DownloadManager: processing inserted download 1
,09-09 13:36:15.471  7841  7841 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-09 13:36:15.472  7841  7841 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-09 13:36:15.478  3489  7998 V DownloadManager: processing inserted download 4
09-09 13:36:15.480  3489  7998 V DownloadManager: processing inserted download 7
09-09 13:36:15.481  3489  7998 V DownloadManager: processing inserted download 8
09-09 13:36:15.482  3489  7998 V DownloadManager: processing inserted download 9
09-09 13:36:15.482  7899  7899 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:36:15
,09-09 13:36:15.483  3489  7998 V DownloadManager: processing inserted download 10
09-09 13:36:15.485  7899  7899 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-09 13:36:15.485  7899  7899 D Weather.Utils: 2 : All the weather widget is gone.
09-09 13:36:15.485  3489  7998 V DownloadManager: processing inserted download 11
09-09 13:36:15.486  7899  7899 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-09 13:36:15.486  7899  7899 D WeatherAncestor: connectivity changed - connection : true
09-09 13:36:15.486  7899  7899 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@a39c7ed
09-09 13:36:15.487  3489  7998 V DownloadManager: processing inserted download 12
09-09 13:36:15.488  3489  7998 V DownloadManager: processing inserted download 13
09-09 13:36:15.489  3489  7998 V DownloadManager: processing inserted download 14
09-09 13:36:15.490  3489  7998 V DownloadManager: processing inserted download 16
09-09 13:36:15.491  7899  7899 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-09 13:36:15.491  7899  7899 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-09 13:36:15.491  7899  7899 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-09 13:36:15.491  7899  7899 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-09 13:36:15.491  7899  7899 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:36:15
09-09 13:36:15.498  3489  3489 V DownloadManager: DownloadService onDestroy
,09-09 13:36:15.556  6851  8004 V FormManager: There are no updated forms. The schedule will be deleted.
,09-09 13:36:15.563  6851  8004 V FormManager: Alarm would be updated, because LastCheckTime has been updated.
09-09 13:36:15.577  6562  6617 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,09-09 13:36:15.577  6562  6617 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-09 13:36:15.583  6562  6617 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:36:15.583  6562  6617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:36:15.583  6562  6617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:36:15.583  6562  6617 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2419ea6 not in the list
,09-09 13:36:15.583  6562  6617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:36:15.583  6562  6617 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eab50e7 not in the list
09-09 13:36:15.583  6562  6617 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:36:15.584  6562  6617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:36:15.584  6562  6617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:36:15.586  6562  6617 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-09 13:36:15.588  6562  6617 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
09-09 13:36:15.588  6562  6617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
09-09 13:36:15.589  6562  6617 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-09 13:36:15.589  6562  6617 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-09 13:36:15.589  6562  6617 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-09 13:36:15.589  6562  6617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:36:15.590  6562  6617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-09 13:36:15.592  6562  6617 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-09 13:36:15.592  6562  6617 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-09 13:36:15.592  6562  6562 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-09 13:36:15.596  6562  6617 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,09-09 13:36:15.597  6562  6617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-09 13:36:15.597  6562  6617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:36:15.597  6562  6617 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-09 13:36:15.600  1036  2035 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-09 13:36:15.604  6562  8006 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 13:36:15.607  7358  7374 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=84 mFd=82
09-09 13:36:15.608  6562  8006 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-09 13:36:15.610  6562  6617 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-09 13:36:15.610  6562  6617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:36:15.614  6562  6617 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-09 13:36:15.615  6562  6617 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:36:15.615  6562  6617 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-09 13:36:15.615  6562  6617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-09 13:36:15.615  6562  6617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-09 13:36:15.615  6562  6617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:36:15.616  6562  6617 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-09 13:36:15.616  6562  8006 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-09 13:36:15.616  6562  8006 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-09 13:36:15.616  6562  8006 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-09 13:36:15.616  6562  6562 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-09 13:36:15.617  6562  6562 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-09 13:36:15.618  6562  6617 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2419ea6 not in the list
09-09 13:36:15.618  6562  6617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:36:15.618  6562  6617 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eab50e7 not in the list
09-09 13:36:15.618  6562  6617 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:36:15.618  6562  6617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:36:15.618  6562  6617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:36:15.619  6562  6617 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 13:36:15.619  6562  6617 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-09 13:36:15.619  6562  6617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-09 13:36:15.619  6562  6617 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:36:15.619  6562  6617 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-09 13:36:15.625  6562  6617 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 13:36:15.625  6562  6617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:36:15.628  6562  6617 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager,
09-09 13:36:15.888   311  8016 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,09-09 13:36:15.891   311  8016 D libc-netbsd: res_queryN name = www.google.com, class = 1, type = 1
09-09 13:36:15.940   311  8016 D libc-netbsd: res_queryN name = www.google.com succeed
,09-09 13:36:15.960   311  8018 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,09-09 13:36:15.968   311  8018 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,09-09 13:36:15.968   311  8018 D libc-netbsd: res_queryN name = clients3.google.com succeed
09-09 13:36:16.026  1036  1394 V WifiInternetCheck: isHttpConnectionAvailable - We got a valid response : 204
,09-09 13:36:17.538   311  7802 D libc-netbsd: res_queryN name = mtalk.google.com succeed
,09-09 13:36:17.616  1036  1392 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2437 sc=60 link=72 tx=53.8, 0.0, 0.0  rx=56.5 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:247195087] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,09-09 13:36:17.621  1036  1392 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2437 sc=60 link=72 tx=53.8, 0.0, 0.0  rx=56.5 bcn=0 [on:0 tx:0 rx:0 period:5] from screen [on:0 period:247195092] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-09 13:36:17.621  1036  1392 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,09-09 13:36:17.839  2180  8020 D GCM     : Connected
,09-09 13:36:17.872  2180  8020 D GCM     : Message class com.google.e.a.a.q
,09-09 13:36:18.630  6562  6617 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 13:36:18.630  6562  6617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 13:36:18.630  6562  6617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:36:18.630  6562  6617 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2419ea6 not in the list
09-09 13:36:18.630  6562  6617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:36:18.630  6562  6617 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eab50e7 not in the list
09-09 13:36:18.630  6562  6617 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 13:36:18.630  6562  6617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:36:18.631  6562  6617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:36:18.634  6562  6617 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:36:18.634  6562  6617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:36:18.634  6562  6617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:36:18.635  6562  6617 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2419ea6 not in the list
09-09 13:36:18.635  6562  6617 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:36:18.635  6562  6617 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eab50e7 not in the list
09-09 13:36:18.635  6562  6617 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 13:36:18.635  6562  6617 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:36:18.635  6562  6617 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:36:18.652  6562  6617 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-09 13:36:18.652  6562  6617 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-09 13:36:18.652  6562  6617 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-09 13:36:18.653  6562  6617 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 13:36:18.653  6562  6617 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-09 13:36:18.653  6562  6617 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-09 13:36:18.665  6562  8021 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 964, name: My test thread name)
,09-09 13:36:19.608  7917  7939 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,09-09 13:36:20.631  1036  1392 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2437 sc=60 link=72 tx=33.9, 0.0, 0.0  rx=32.8 bcn=0 [on:0 tx:0 rx:0 period:3006] from screen [on:0 period:247198103] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,09-09 13:36:20.634  1036  1392 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-45 f=2437 sc=60 link=72 tx=33.9, 0.0, 0.0  rx=32.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:247198106] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,09-09 13:36:20.634  1036  1392 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,09-09 13:36:20.664  6562  6617 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 964
,09-09 13:36:20.664  6562  6617 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 964, name: My test thread name)
,09-09 13:36:20.681  6562  8024 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 965, name: My test thread name)
09-09 13:36:20.681  6562  8024 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 965, thread name: My test thread name)
09-09 13:36:20.681  6562  8024 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 965, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
09-09 13:36:20.688  6562  6617 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-09 13:36:20.694  6562  8025 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 969, name: My test thread name)
,09-09 13:36:20.695  6562  8025 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 969, thread name: My test thread name): Test exception.
09-09 13:36:20.695  6562  8025 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 969, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
09-09 13:36:20.699  6562  6617 I jxcore-log: Total number of executed tests:  82
09-09 13:36:20.699  6562  6617 I jxcore-log: 
09-09 13:36:20.700  6562  6617 I jxcore-log: Number of passed tests:  82
09-09 13:36:20.700  6562  6617 I jxcore-log: 
09-09 13:36:20.700  6562  6617 I jxcore-log: Number of failed tests:  0
09-09 13:36:20.700  6562  6617 I jxcore-log: 
09-09 13:36:20.700  6562  6617 I jxcore-log: Number of ignored tests:  0
09-09 13:36:20.700  6562  6617 I jxcore-log: 
09-09 13:36:20.701  6562  6617 I jxcore-log: Total duration:  26299
09-09 13:36:20.701  6562  6617 I jxcore-log: 
09-09 13:36:20.702  6562  6617 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-09 13:36:20.702  6562  6617 I jxcore-log: 
09-09 13:36:20.703  6562  6617 I jxcore-log: My device name is: LGE-LG-D855
09-09 13:36:20.703  6562  6617 I jxcore-log: 
09-09 13:36:20.717  6562  6617 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:36:20.717  6562  6617 I jxcore-log: 
09-09 13:36:20.718  6562  6617 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:36:20.718  6562  6617 I jxcore-log: 
09-09 13:36:20.719  6562  6617 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:36:20.719  6562  6617 I jxcore-log: 
09-09 13:36:20.721  6562  6617 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:36:20.721  6562  6617 I jxcore-log: 
09-09 13:36:20.722  6562  6617 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:36:20.722  6562  6617 I jxcore-log: 
09-09 13:36:20.725  6562  6617 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:36:20.725  6562  6617 I jxcore-log: 
,09-09 13:36:20.739  6562  6617 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:36:20.739  6562  6617 I jxcore-log: 
09-09 13:36:20.740  6562  6617 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:36:20.740  6562  6617 I jxcore-log: 
09-09 13:36:20.741  6562  6617 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 13:36:20.741  6562  6617 I jxcore-log: 
09-09 13:36:20.742  6562  6617 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 13:36:20.742  6562  6617 I jxcore-log: 
09-09 13:36:20.743  6562  6617 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 13:36:20.743  6562  6617 I jxcore-log: 
09-09 13:36:20.744  6562  6617 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-09 13:36:20.744  6562  6617 I jxcore-log: 
09-09 13:36:20.745  6562  6617 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 13:36:20.745  6562  6617 I jxcore-log: 
09-09 13:36:20.746  6562  6617 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 13:36:20.746  6562  6617 I jxcore-log: 
09-09 13:36:20.747  6562  6617 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 13:36:20.747  6562  6617 I jxcore-log: 
09-09 13:36:20.748  6562  6617 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:36:20.748  6562  6617 I jxcore-log: 
,09-09 13:36:20.752  6562  6617 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:36:20.752  6562  6617 I jxcore-log: 
,09-09 13:36:20.754  6562  6617 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:36:20.754  6562  6617 I jxcore-log: 
09-09 13:36:20.755  6562  6617 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:36:20.755  6562  6617 I jxcore-log: 
09-09 13:36:20.756  6562  6617 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:36:20.756  6562  6617 I jxcore-log: 
09-09 13:36:20.757  6562  6617 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:36:20.757  6562  6617 I jxcore-log: 
09-09 13:36:20.758  6562  6617 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:36:20.758  6562  6617 I jxcore-log: 
09-09 13:36:20.759  6562  6617 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:36:20.759  6562  6617 I jxcore-log: 
09-09 13:36:20.759  6562  6617 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:36:20.759  6562  6617 I jxcore-log: 
09-09 13:36:20.760  6562  6617 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:36:20.760  6562  6617 I jxcore-log: 
09-09 13:36:20.761  6562  6617 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:36:20.761  6562  6617 I jxcore-log: 
09-09 13:36:20.762  6562  6617 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:36:20.762  6562  6617 I jxcore-log: 
09-09 13:36:20.763  6562  6617 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 13:36:20.763  6562  6617 I jxcore-log: 
09-09 13:36:20.763  6562  6617 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 13:36:20.763  6562  6617 I jxcore-log: 
09-09 13:36:20.764  6562  6617 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 13:36:20.764  6562  6617 I jxcore-log: 
09-09 13:36:20.765  6562  6617 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 13:36:20.765  6562  6617 I jxcore-log: 
09-09 13:36:20.767  6562  6617 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 13:36:20.767  6562  6617 I jxcore-log: 
09-09 13:36:20.768  6562  6617 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 13:36:20.768  6562  6617 I jxcore-log: 
09-09 13:36:20.769  6562  6617 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on,","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:36:20.769  6562  6617 I jxcore-log: 
09-09 13:36:20.769  6562  6617 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:36:20.769  6562  6617 I jxcore-log: 
09-09 13:36:20.770  6562  6617 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:36:20.770  6562  6617 I jxcore-log: 
,09-09 13:36:20.881  6562  8021 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 964, name: My test thread name), during the lifetime of the thread the total number of bytes read was 187 and the total number of bytes written 187
,09-09 13:36:21.056  8026  8026 D AndroidRuntime: 
09-09 13:36:21.056  8026  8026 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,09-09 13:36:21.060  8026  8026 D AndroidRuntime: CheckJNI is OFF
09-09 13:36:21.246  8026  8026 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-09 13:36:21.274  1036  1093 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
,09-09 13:36:21.275  1036  1093 I ActivityManager: Killing 6562:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
09-09 13:36:21.334  1036  2036 I WindowState: WIN DEATH: Window{c60ce87 u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-09 13:36:21.335  1036  1412 D WifiService: Client connection lost with reason: 4
,09-09 13:36:21.343  1036  2036 D InputDispatcher: Window went away: Window{c60ce87 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-09 13:36:21.493  1036  1093 I ActivityManager:   Force finishing activity ActivityRecord{2c92e6c0 u0 com.test.thalitest/.MainActivity t6}
,09-09 13:36:21.569   339   363 E GBMv2   : DFP En is all cleared set to be enabled
,09-09 13:36:21.576  1036  1963 W ActivityManager: Spurious death for ProcessRecord{186cbc09 6562:com.test.thalitest/u0a118}, curProc for 6562: null
09-09 13:36:21.577  1036  1125 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
09-09 13:36:21.581  1036  1125 I ActivityManager:   Force finishing activity ActivityRecord{2c92e6c0 u0 com.test.thalitest/.MainActivity t6 f}
09-09 13:36:21.581  1036  1125 W ActivityManager: Duplicate finish request for ActivityRecord{2c92e6c0 u0 com.test.thalitest/.MainActivity t6 f}
,09-09 13:36:21.621  2037  2037 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
09-09 13:36:21.621  1945  1960 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
09-09 13:36:21.622  1945  1960 D SplitWindowPolicy: topRunningActivity=ActivityInfo{37eb28fd co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
09-09 13:36:21.622  2037  2037 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
09-09 13:36:21.623  1945  1961 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
09-09 13:36:21.624  1945  1961 D SplitWindowPolicy: topRunningActivity=ActivityInfo{264bb9f2 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
,09-09 13:36:21.626  2037  2037 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
09-09 13:36:21.629  2037  2105 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
09-09 13:36:21.630  1605  1605 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
09-09 13:36:21.640  1036  1379 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-09 13:36:21.640  2477  2619 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
09-09 13:36:21.640  2000  2000 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
09-09 13:36:21.642  3810  3810 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
09-09 13:36:21.654  7358  7358 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
09-09 13:36:21.654  7358  7358 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
09-09 13:36:21.667  4602  4602 I art     : Explicit concurrent mark sweep GC freed 8191(469KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 29MB/45MB, paused 531us total 66.158ms
09-09 13:36:21.669  4501  4501 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
09-09 13:36:21.669  4501  4501 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
09-09 13:36:21.669  4501  4501 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
09-09 13:36:21.669  4501  4501 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
09-09 13:36:21.669  4501  4501 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-09 13:36:21.669  4501  4501 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-09 13:36:21.669  4501  4501 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-09 13:36:21.669  4501  4501 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-09 13:36:21.669  4501  4501 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 13:36:21.669  4501  4501 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 13:36:21.669  4501  4501 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-09 13:36:21.670  4501  4501 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,09-09 13:36:21.684  1036  2036 V SIM_STK : Menu title from STK is T-Mobile
09-09 13:36:21.689  1036  1092 W InputMethodInfo: Duplicated subtype definition found: , voice
,09-09 13:36:21.699  6373  6373 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
09-09 13:36:21.707  1908  1908 D ActionManagerService: notifyUserLog: 1000003
09-09 13:36:21.707  2037  2037 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
,09-09 13:36:21.708  3810  4486 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
09-09 13:36:21.709  2037  2037 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
09-09 13:36:21.710  1605  1605 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
09-09 13:36:21.710  1605  1664 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
09-09 13:36:21.710  1605  1664 D KeyguardModel: createShortcutInfo...
09-09 13:36:21.712  1821  1821 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
09-09 13:36:21.712  2037  2037 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
09-09 13:36:21.713  1605  1664 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
09-09 13:36:21.713  1605  1664 D KeyguardModel: createShortcutInfo...
09-09 13:36:21.719  2180  2180 I ConfigService: onCreate
09-09 13:36:21.719  1605  1664 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
09-09 13:36:21.720  1605  1664 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-09 13:36:21.720  1605  1664 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
09-09 13:36:21.721  1605  1664 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,09-09 13:36:21.727  1605  1664 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-09 13:36:21.727  2180  2180 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
09-09 13:36:21.728  1605  1664 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
09-09 13:36:21.729  1605  1664 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
09-09 13:36:21.729  1605  1664 D KeyguardModel: createShortcutInfo...
09-09 13:36:21.730  2180  2180 I ConfigService: onBind returning update interface
09-09 13:36:21.737  1605  1664 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
09-09 13:36:21.737  1605  1664 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-09 13:36:21.738  1605  1664 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-09 13:36:21.738  1605  1664 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
,09-09 13:36:21.744  1605  1664 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
09-09 13:36:21.744  1605  1664 D KeyguardModel: createShortcutInfo...
09-09 13:36:21.747  1605  1664 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-09 13:36:21.747  1605  1664 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-09 13:36:21.747  1605  1664 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
09-09 13:36:21.747  1605  1664 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-09 13:36:21.748  1605  1664 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-09 13:36:21.748  1605  1664 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
09-09 13:36:21.750  1036  1036 I art     : Explicit concurrent mark sweep GC freed 30577(1746KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/65MB, paused 3.444ms total 141.343ms
09-09 13:36:21.751  1605  1664 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
09-09 13:36:21.751  1605  1664 D KeyguardModel: createShortcutInfo...
09-09 13:36:21.753  1605  1605 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
09-09 13:36:21.753  1605  1605 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
,09-09 13:36:21.755  2037  2037 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
09-09 13:36:21.757  1821  1821 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
09-09 13:36:21.759  2180  2180 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
09-09 13:36:21.759  2180  2180 I ConfigService: onBind returning config service
09-09 13:36:21.761  1036  1962 V SIM_STK : Menu title from STK is T-Mobile
09-09 13:36:21.761  2037  2037 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
09-09 13:36:21.761  1036  1962 V SIM_STK : Menu title from STK is T-Mobile
09-09 13:36:21.762  1908  1908 D ActionManagerService: notifyUserLog: 1000004
09-09 13:36:21.762  3810  4486 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
09-09 13:36:21.762  1874  1874 D SplitUIManager: split_name #11 / not available #0
09-09 13:36:21.763  1874  1874 D SplitUIService: removed split : 
09-09 13:36:21.766  3810  3826 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
,09-09 13:36:21.774  1605  1605 D KeyguardModel: handleShortcutListChanged...
09-09 13:36:21.774  1605  1605 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
09-09 13:36:21.777  2037  2037 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
09-09 13:36:21.777  2037  2037 I GBoardWebViewUtils: , create_time: 1430832262123
09-09 13:36:21.777  2037  2037 I GBoardWebViewUtils: , expire_time: 0
09-09 13:36:21.777  2037  2037 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
09-09 13:36:21.777  2037  2037 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
09-09 13:36:21.777  2037  2037 I GBoardWebViewUtils: , display: false
09-09 13:36:21.777  2037  2037 I GBoardWebViewUtils: , animation: false }
09-09 13:36:21.777  2037  2037 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
09-09 13:36:21.777  2037  2037 I GBoardWebViewUtils: , create_time: 1430832262287
09-09 13:36:21.777  2037  2037 I GBoardWebViewUtils: , expire_time: 0
09-09 13:36:21.777  2037  2037 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
09-09 13:36:21.777  2037  2037 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
09-09 13:36:21.777  2037  2037 I GBoardWebViewUtils: , display: false
09-09 13:36:21.777  2037  2037 I GBoardWebViewUtils: , animation: false }
09-09 13:36:21.777  2037  2037 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1473420112499
09-09 13:36:21.777  2037  2037 I GBoardWebViewUtils: , create_time: 1473420113195
09-09 13:36:21.777  2037  2037 I GBoardWebViewUtils: , expire_time: 0
09-09 13:36:21.777  2037  2037 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide.html?id=guide_1111111111116_1473420112499&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
09-09 13:36:21.777  2037  2037 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
09-09 13:36:21.777  2037  2037 I GBoardWebViewUtils: , display: false
09-09 13:36:21.777  2037  2037 I GBoardWebViewUtils: , animation: false }
09-09 13:36:21.793  2037  8060 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
09-09 13:36:21.793  1605  1664 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
09-09 13:36:21.793  1605  1664 D KeyguardModel: createShortcutInfo...
09-09 13:36:21.795  1605  1664 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
09-09 13:36:21.795  1605  1664 D KeyguardModel: createShortcutInfo...
,09-09 13:36:21.798  1605  1664 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-09 13:36:21.798  1605  1664 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
09-09 13:36:21.801  1605  1664 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
09-09 13:36:21.801  1605  1664 D KeyguardModel: createShortcutInfo...
09-09 13:36:21.804  1605  1664 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-09 13:36:21.804  1605  1664 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
09-09 13:36:21.807  1605  1664 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
09-09 13:36:21.807  1605  1664 D KeyguardModel: createShortcutInfo...
09-09 13:36:21.808  1821  1821 I ConfigFetchService: service connected
,09-09 13:36:21.809  1605  1664 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-09 13:36:21.810  1605  1664 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
09-09 13:36:21.811  1605  1664 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
09-09 13:36:21.811  1605  1664 D KeyguardModel: createShortcutInfo...
09-09 13:36:21.813  2037  2037 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
09-09 13:36:21.813  2037  2037 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
09-09 13:36:21.815  2180  2180 I ConfigService: onDestroy
09-09 13:36:21.824  1036  1616 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
09-09 13:36:21.824  7358  7358 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
09-09 13:36:21.824  7358  7358 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
09-09 13:36:21.824  7358  7358 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
09-09 13:36:21.824  7358  7358 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
09-09 13:36:21.824  7358  7358 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
09-09 13:36:21.824  7358  7358 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-09 13:36:21.824  7358  7358 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
09-09 13:36:21.824  7358  7358 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
09-09 13:36:21.824  7358  7358 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
09-09 13:36:21.824  7358  7358 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-09 13:36:21.824  7358  7358 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
09-09 13:36:21.826  1821  8062 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,09-09 13:36:21.827  1874  1874 D SplitUIManager: split_name #11 / not available #0
09-09 13:36:21.827  1874  1874 I SplitUIService: split app #11
09-09 13:36:21.838  1036  1999 V SIM_STK : Menu title from STK is T-Mobile
,09-09 13:36:21.843  1605  1605 D KeyguardModel: handleShortcutListChanged...
09-09 13:36:21.843  1605  1605 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
09-09 13:36:21.857  1036  1036 D administrator: Handling package changes for user 0
,09-09 13:36:21.873  5879  8067 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
09-09 13:36:21.878  1821  8069 I PeopleContactsSync: CP2 sync disabled
09-09 13:36:21.888  2037  2037 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
,09-09 13:36:21.902   333   432 I ThermalEngine: Thermal-Server: Thermal received msg from  override
09-09 13:36:21.903  3248  8070 I Thermal-Lib: Thermal-Lib-Client: Client request sent
09-09 13:36:21.904  1821  4740 I Icing   : doRemovePackageData com.test.thalitest
,09-09 13:36:21.908  2180  2339 I art     : Explicit concurrent mark sweep GC freed 9946(578KB) AllocSpace objects, 4(64KB) LOS objects, 52% free, 29MB/61MB, paused 657us total 21.980ms
09-09 13:36:21.917  1821  8068 W GmsApplication: Using Auth Proxy for data requests.
,09-09 13:36:21.920  1036  1036 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
09-09 13:36:21.920  1036  1036 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
09-09 13:36:21.920  1036  1036 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
09-09 13:36:21.923  1821  8068 W GmsApplication: Using Auth Proxy for data requests.
09-09 13:36:21.928  1036  1580 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
,09-09 13:36:21.958  7574  7574 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
,09-09 13:36:21.992  1036  2035 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=8073 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,09-09 13:36:22.003  1036  1092 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-09 13:36:22.005  2037  2037 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,09-09 13:36:22.007  1036  1092 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
09-09 13:36:22.010  2037  2037 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-09 13:36:22.011  2037  2037 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
09-09 13:36:22.012  2037  2037 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
09-09 13:36:22.013  2037  2037 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
09-09 13:36:22.014  2037  2037 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
,09-09 13:36:22.029  2037  2037 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
09-09 13:36:22.030  2037  2037 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
,09-09 13:36:22.030  2037  2037 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-09 13:36:22.033  2037  2179 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
09-09 13:36:22.033  2037  2179 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
09-09 13:36:22.043  1036  1113 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3e3abf4a u0 com.lge.launcher2/.Launcher t5} time:154757
,09-09 13:36:22.045  2037  2037 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
09-09 13:36:22.046  2037  2037 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
09-09 13:36:22.046  2037  2037 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-09 13:36:22.061  2037  2037 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
,09-09 13:36:22.062  1036  1125 I art     : Explicit concurrent mark sweep GC freed 12148(762KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/65MB, paused 6.699ms total 306.702ms
09-09 13:36:22.063  2601  2601 D [Concierge]Service: onStartCommand(). Type : 8
09-09 13:36:22.063  2601  2601 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
09-09 13:36:22.064  2601  2601 D [Concierge]Service: Update widget ID : 11
09-09 13:36:22.065  2037  2037 D [Concierge]WidgetView: change position of spinner
09-09 13:36:22.066  2037  2037 I [Concierge]WidgetView: initWebView(). Time : 1473420982066
09-09 13:36:22.070  8073  8073 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-09 13:36:22.070  8073  8073 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-09 13:36:22.070  8073  8073 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
09-09 13:36:22.071  8073  8073 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
09-09 13:36:22.071  8073  8073 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-09 13:36:22.072  2601  2601 D [Concierge]Service: onStartCommand(). Type : 0
09-09 13:36:22.107  2037  2037 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 481329520
09-09 13:36:22.107  2037  2037 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
09-09 13:36:22.107  2037  2037 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
09-09 13:36:22.110  2037  2037 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@1e11c7a7
09-09 13:36:22.110  2037  2037 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
,09-09 13:36:22.112  2037  2037 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
09-09 13:36:22.112  2037  2037 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-09 13:36:22.113  8073  8073 I SystemConfig: BUILD Country: EU
09-09 13:36:22.114  8073  8073 I SystemConfig: BUILD Operator: OPEN
09-09 13:36:22.116  2037  2037 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
09-09 13:36:22.117  2037  2037 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
09-09 13:36:22.117  2037  2037 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
09-09 13:36:22.117  2037  2037 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1473420855187, New one : 1473420982066
09-09 13:36:22.118  2037  2037 D [Concierge]WidgetView: Unregister all receivers
09-09 13:36:22.118  2037  2037 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
09-09 13:36:22.118  2037  2037 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-09 13:36:22.119  2037  2037 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
09-09 13:36:22.120  2037  2037 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
09-09 13:36:22.121  2037  2037 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
09-09 13:36:22.122  2037  2037 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
09-09 13:36:22.123  2037  2037 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
,09-09 13:36:22.129  2037  2037 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-09 13:36:22.129  2037  2037 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-09 13:36:22.143  8026  8026 D AndroidRuntime: Shutting down VM
,09-09 13:36:22.157  1036  1962 I ActivityManager: Killing 7754:com.lge.bnr/1000 (adj 15): empty #17
,09-09 13:36:22.175  2037  2037 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,09-09 13:36:22.182  2037  2037 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,09-09 13:36:22.183  2037  2037 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
09-09 13:36:22.184  2037  2037 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-09 13:36:22.203  2037  2037 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@159d3048 time:154917
,09-09 13:36:22.218  1036  1943 W libprocessgroup: failed to open /acct/uid_1000/pid_7754/cgroup.procs: No such file or directory
,09-09 13:36:22.223  7808  7808 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
09-09 13:36:22.224  8073  8093 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
09-09 13:36:22.224  8073  8093 I SystemConfig: existFile = false
09-09 13:36:22.224  8073  8093 I SystemConfig: canReadFile = false
09-09 13:36:22.224  8073  8093 I SystemConfig: systemFeature RCS result false
09-09 13:36:22.224  8073  8093 D SystemConfig: refreshRcsSupport() :false
09-09 13:36:22.225  2342  8095 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
09-09 13:36:22.252  1036  1781 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=8096 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,09-09 13:36:22.283  8096  8096 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-09 13:36:22.283  8096  8096 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,09-09 13:36:22.283  8096  8096 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
09-09 13:36:22.283  8096  8096 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-09 13:36:22.321  2037  2037 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,09-09 13:36:22.330  8096  8096 I AppConfig: Total System Memory = 2995761152
,09-09 13:36:22.335  8096  8096 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
09-09 13:36:22.359  2037  2868 I GBoardtInterface: onReloaded()
,09-09 13:36:22.361  2037  2037 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
,09-09 13:36:22.371  1036  1125 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8115 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
09-09 13:36:22.372  1036  1616 I ActivityManager: Killing 7512:com.lge.sync/1000 (adj 15): empty #17
09-09 13:36:22.407  2000  2000 D LIA_Service_NativeEventReceiver: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
09-09 13:36:22.407  2000  2000 I LIA_Service_PlatformUtil: startLIAService() : Trying to start LIA service ...
09-09 13:36:22.408  1036  2035 W libprocessgroup: failed to open /acct/uid_1000/pid_7512/cgroup.procs: No such file or directory
09-09 13:36:22.408  2000  2000 D LIA_Service_LIAService: onStartCommand() : LIAService started! - id :4, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
,09-09 13:36:22.410  3810  3826 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
09-09 13:36:22.413  6373  6373 D PostponalbeReceiver: OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
09-09 13:36:22.414  3810  3825 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
09-09 13:36:22.444  1036  1578 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.core.receiver.CoreEventReceiver: pid=8135 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,09-09 13:36:22.447  1036  2035 I ActivityManager: Killing 6670:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
09-09 13:36:22.460  6825  6825 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
09-09 13:36:22.461  6825  6825 W System.err: android.os.DeadObjectException

```
