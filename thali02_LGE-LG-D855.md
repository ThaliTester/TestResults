#### Test 82728424c383411_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
08-26 10:52:23.861  6501  6501 D PostponalbeReceiver: OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_ADDED'.
--------- beginning of system
08-26 10:52:23.867  6501  6501 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsm.mss.OasPackageScanReceiver.onReceive:-1 android.app.ActivityThread.handleReceiver:2586 
08-26 10:52:23.903  4600  6631 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
08-26 10:52:23.959  1036  1784 V SIM_STK : Menu title from STK is T-Mobile
08-26 10:52:23.960  1036  2033 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=6639 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-26 10:52:24.058  4600  6631 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 155 ms] updated apps [took 155 ms] 
08-26 10:52:24.187  6639  6639 D DocsApplication: Installing DEX configuration.
08-26 10:52:24.209  6639  6639 D DexInstaller: Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
08-26 10:52:24.214  6639  6639 I PackageInfoHelper: Provided clientMode=RELEASE, packageInfo=PackageInfo{2da98743 com.google.android.apps.docs}
08-26 10:52:24.233  6639  6639 D TAG     : onCreate()
08-26 10:52:24.262  6639  6639 D CrossAppStateProvider: Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
08-26 10:52:24.558   339   428 I ThermalEngine: Thermal-Server: Thermal received msg from  override
,08-26 10:52:24.562  3222  6665 I Thermal-Lib: Thermal-Lib-Client: Client request sent
08-26 10:52:25.078  1819  4666 I Icing   : Indexing 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4 from com.google.android.googlequicksearchbox
08-26 10:52:25.158  1819  4666 D Icing   : Loaded CLD2 Version V2.0 - 20140131
08-26 10:52:25.162  6666  6666 D AndroidRuntime: 
08-26 10:52:25.162  6666  6666 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-26 10:52:25.167  6666  6666 D AndroidRuntime: CheckJNI is OFF
08-26 10:52:25.225  1819  4666 I Icing   : Indexing done 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4
08-26 10:52:25.333  6666  6666 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-26 10:52:25.337  1036  1737 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-26 10:52:25.376  1943  1958 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-26 10:52:25.380  1036  1737 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-26 10:52:25.381  1036  1737 D ActivityManager: setTaskToReturnTo : TaskRecord{32c4abbe #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-26 10:52:25.381  1036  1737 D ActivityManager: setTaskToReturnTo : TaskRecord{32c4abbe #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-26 10:52:25.382  1036  1737 D WindowStateEx: AppWindowTokenEx init.. 
08-26 10:52:25.383   347   372 E GBMv2   : DFP En is all cleared set to be enabled
08-26 10:52:25.432  1036  1737 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6692 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-26 10:52:25.433  6666  6666 D AndroidRuntime: Shutting down VM
08-26 10:52:25.478  1943  2943 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-26 10:52:25.478  1943  2943 D SplitWindowPolicy: topRunningActivity=ActivityInfo{737492f co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-26 10:52:25.479  1943  1959 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-26 10:52:25.479  1943  1959 D SplitWindowPolicy: topRunningActivity=ActivityInfo{3430ab3c co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-26 10:52:25.517  6692  6692 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-26 10:52:25.574  6692  6692 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
08-26 10:52:25.580  6692  6692 I LibraryLoader: Loading: webviewchromium
08-26 10:52:25.582  6692  6692 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 4832-4835)
08-26 10:52:25.582  6692  6692 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-26 10:52:25.611  6692  6692 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3f8f71b5}
08-26 10:52:25.612  6692  6692 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-26 10:52:25.612  6692  6692 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-26 10:52:25.623  6692  6692 I BrowserStartupController: Initializing chromium process, renderers=0
08-26 10:52:25.624  6692  6692 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-26 10:52:25.636  6692  6692 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-26 10:52:25.636  6692  6692 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
08-26 10:52:25.637  6692  6692 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
,08-26 10:52:25.639   329  2193 V AudioPolicyService: registerClient() client 0xb1030fc0, uid 10118
08-26 10:52:25.643  1036  1112 D BluetoothManagerService: Message: 20
08-26 10:52:25.643  1036  1112 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2b0fba58:true
08-26 10:52:25.659  6692  6692 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-26 10:52:25.659  6692  6692 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-26 10:52:25.659  6692  6692 I Adreno-EGL: Build Date: 12/12/14 금
08-26 10:52:25.659  6692  6692 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-26 10:52:25.659  6692  6692 I Adreno-EGL: Remote Branch: 
08-26 10:52:25.659  6692  6692 I Adreno-EGL: Local Patches: 
08-26 10:52:25.659  6692  6692 I Adreno-EGL: Reconstruct Branch: 
,08-26 10:52:25.720  6692  6722 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,08-26 10:52:25.726  6692  6692 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
08-26 10:52:25.741  6692  6692 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-26 10:52:25.744  6692  6692 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-26 10:52:25.747  6692  6692 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-26 10:52:25.749  6692  6692 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-26 10:52:25.749  6692  6692 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
08-26 10:52:25.762  6692  6692 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-26 10:52:25.768  6692  6692 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-26 10:52:25.768  6692  6692 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-26 10:52:25.811  6692  6734 D OpenGLRenderer: Render dirty regions requested: true
,08-26 10:52:25.811  6692  6734 I OpenGLRenderer: Initialized EGL, version 1.4
08-26 10:52:25.822  6692  6734 D OpenGLRenderer: Enabling debug mode 0
08-26 10:52:25.831  6692  6692 D Atlas   : Validating map...
,08-26 10:52:25.835  1036  2005 D SplitWindow: check instance of lgWin Window{344f9d2 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-26 10:52:25.869  6692  6732 D LgDataFeature: LgDataFeature() Constructor: none
,08-26 10:52:25.870  6692  6732 D LgDataFeature: LgDataFeature() Constructor Done, null
08-26 10:52:25.948  1036  1113 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +471ms (total +565ms)
08-26 10:52:25.949  1036  1113 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1d05341f u0 com.test.thalitest/.MainActivity t6} time:105201
,08-26 10:52:25.950  6692  6692 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@3700c808 time:105202
08-26 10:52:25.976  6639  6639 D LgDataFeature: LgDataFeature() Constructor: none
08-26 10:52:25.976  6639  6639 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-26 10:52:26.067  6692  6692 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-26 10:52:26.067  6692  6692 I chromium: 
,08-26 10:52:26.079  6692  6692 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
08-26 10:52:26.164  6692  6732 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-26 10:52:26.164  6692  6732 I chromium: 
,08-26 10:52:26.175  6133  6133 I LockScreenSettings: New app installed broadcast received ..
08-26 10:52:26.178  6133  6133 I LockScreenSettings: Number of installed packages  1
08-26 10:52:26.189  6639  6639 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,08-26 10:52:26.240  1036  1923 V SIM_STK : Menu title from STK is T-Mobile
,08-26 10:52:26.293  6692  6756 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435060736
,08-26 10:52:26.295  1036  1978 I ActivityManager: Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=6761 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-26 10:52:26.305  6692  6756 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-26 10:52:26.305  6692  6756 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-26 10:52:26.305  6692  6756 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-26 10:52:26.305  6692  6756 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-26 10:52:26.305  6692  6756 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-26 10:52:26.306  6692  6756 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2fec8e4c added. We now have 1 listener(s)
08-26 10:52:26.311  1036  1736 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 10:52:26.314  6692  6756 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-26 10:52:26.315  6692  6756 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-26 10:52:26.316  6692  6756 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 10:52:26.317  6692  6756 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-26 10:52:26.324  6692  6756 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-26 10:52:26.324  6692  6756 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-26 10:52:26.324  6692  6756 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-26 10:52:26.324  6692  6756 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-26 10:52:26.324  6692  6756 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-26 10:52:26.324  6692  6756 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-26 10:52:26.324  6692  6756 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-26 10:52:26.324  6692  6756 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-26 10:52:26.324  6692  6756 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-26 10:52:26.324  6692  6756 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-26 10:52:26.324  6692  6756 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-26 10:52:26.324  6692  6756 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-26 10:52:26.324  6692  6756 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-26 10:52:26.324  6692  6756 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-26 10:52:26.325  6692  6756 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ce0939b added. We now have 1 listener(s)
08-26 10:52:26.325  6692  6756 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 10:52:26.330  1036  1485 D WifiService: New client listening to asynchronous messages
,08-26 10:52:26.334  6692  6756 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-26 10:52:26.334  6692  6756 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-26 10:52:26.334  6692  6756 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-26 10:52:26.335  6692  6756 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-26 10:52:26.335  6692  6756 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-26 10:52:26.339  6692  6756 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 10:52:26.339  1036  1942 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 10:52:26.342  6692  6756 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
,08-26 10:52:26.354  6692  6756 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
,08-26 10:52:26.354  6692  6756 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 10:52:26.354  6692  6756 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 10:52:26.354  6692  6756 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 10:52:26.354  6692  6756 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 10:52:26.354  6692  6756 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 10:52:26.354  6692  6756 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 10:52:26.354  6692  6756 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 10:52:26.354  6692  6756 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 10:52:26.354  6692  6756 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-26 10:52:26.354  6692  6756 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 10:52:26.356  6692  6756 I io.jxcore.node.LifeCycleMonitor: start: OK
08-26 10:52:26.357  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 10:52:26.359  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 10:52:26.378  6761  6761 D EulaProviderUpdateObserver: action : android.intent.action.PACKAGE_ADDED
08-26 10:52:26.378  6761  6761 D EulaProviderUpdateObserver: uri : package:com.test.thalitest
,08-26 10:52:26.399  6692  6692 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-26 10:52:26.426  1036  1889 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.BNRAppInstallReceiver: pid=6783 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
08-26 10:52:26.427  1036  1889 I ActivityManager: Killing 5812:com.google.android.gm/u0a64 (adj 15): empty #17
,08-26 10:52:26.540  1036  1784 W libprocessgroup: failed to open /acct/uid_10064/pid_5812/cgroup.procs: No such file or directory
08-26 10:52:26.598   347   374 E GBMv2   : DFP En is all cleared set to be enabled
08-26 10:52:26.598   347   374 E GBMv2   : Set value is all cleared set the max
08-26 10:52:26.598   347   374 I GBMv2   : DFP Enabled. Ignore VFP set
,08-26 10:52:26.630  6783  6783 D [BNRAppListMgrReceiver]: android.intent.action.PACKAGE_ADDED : com.test.thalitest
,08-26 10:52:26.671  6783  6783 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-26 10:52:26.674  6501  6501 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.intent.action.PACKAGE_ADDED'.
08-26 10:52:26.707  1036  1924 I ActivityManager: Killing 5852:com.google.android.talk/u0a72 (adj 15): empty #17
,08-26 10:52:26.792  1036  1053 W libprocessgroup: failed to open /acct/uid_10072/pid_5852/cgroup.procs: No such file or directory
,08-26 10:52:27.294  6692  6782 W jxcore-log: Initializing JXcore engine
08-26 10:52:27.294  6692  6782 W jxcore-log: JXcore engine is ready
,08-26 10:52:27.363  6782  6782 W Thread-757: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[9656]" dev="sockfs" ino=9656 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,08-26 10:52:27.363  6782  6782 W Thread-757: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-26 10:52:27.363  6782  6782 W Thread-757: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[9798]" dev="sockfs" ino=9798 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-26 10:52:27.363  6782  6782 W Thread-757: type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-26 10:52:27.363  6782  6782 W Thread-757: type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[29677]" dev="sockfs" ino=29677 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
08-26 10:52:27.397  6692  6782 W jxcore-log: Starting JXcore engine
,08-26 10:52:27.550  6692  6782 W jxcore-log: Platform android
08-26 10:52:27.550  6692  6782 W jxcore-log: 
08-26 10:52:27.550  6692  6782 W jxcore-log: Process ARCH arm
08-26 10:52:27.550  6692  6782 W jxcore-log: 
,08-26 10:52:27.572  2797  2797 I MusicWidget: mDelayedStopHandler : unbind
08-26 10:52:27.574  2172  2172 I MusicBrowser: [MediaPlaybackService.java:2869:onUnbind()] oooooo 
08-26 10:52:27.575  2172  2172 I MusicBrowser: [MediaPlaybackService.java:2076:saveQueue()] oooooo {full=true}
08-26 10:52:27.575  2172  2172 I MusicBrowser: [MediaPlaybackService.java:2081:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
,08-26 10:52:27.582  2172  2172 D MusicBrowser: [MediaPlaybackService.java:2161:saveQueue()] oooooo {queue=}
08-26 10:52:27.583  2172  2172 D MusicBrowser: [MediaPlaybackService.java:2163:saveQueue()] oooooo {mCardId=-1}
08-26 10:52:27.583  2172  2172 D MusicBrowser: [MediaPlaybackService.java:2198:saveQueue()] oooooo {curpos=-1}
08-26 10:52:27.586  2172  2172 I MusicBrowser: [MediaPlaybackService.java:2046:onDestroy()] oooooo 
08-26 10:52:27.587  2172  2172 I MusicBrowser: [MediaPlaybackService.java:8635:clearReceiver()] oooooo 
,08-26 10:52:27.590  1036  1978 I MediaFocusControl:  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@252de9abcom.lge.music.MediaPlaybackService$5@3700c808
08-26 10:52:27.592  2172  2172 D MusicBrowser: [MediaPlaybackService.java:8669:clearReceiver()] oooooo abandonAudioFocus : 1
08-26 10:52:27.593  2172  2172 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-26 10:52:27.595  2172  2172 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-26 10:52:27.595  2172  2172 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-26 10:52:27.596  2172  2172 I MusicBrowser: [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$27@28927431
08-26 10:52:27.596  2172  2172 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-26 10:52:27.598  2172  2172 I MusicBrowser: [MusicUtils.java:6801:endNotiTimer()] oooooo endNotiTimer
08-26 10:52:27.598  2172  2172 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-26 10:52:27.599  2172  2172 I MusicBrowser: [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
08-26 10:52:27.599  2172  2172 I MusicBrowser: [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
08-26 10:52:27.599  2172  2172 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-26 10:52:27.601  2172  2172 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
,08-26 10:52:27.606  2172  2172 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-26 10:52:27.608  2172  2172 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-26 10:52:27.610  2172  2172 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-26 10:52:27.611  2172  2172 I MusicBrowser: [MusicUtils.java:10406:isAKACoverSupported()] oooooo aka not support!
08-26 10:52:27.613  2172  2172 I MusicBrowser: [MediaPlaybackService.java:6704:release()] oooooo 
,08-26 10:52:27.616  2172  2172 I MusicBrowser: [MediaPlaybackService.java:6665:stop()] oooooo 
08-26 10:52:27.616  2172  2172 V MediaPlayer[Native]: reset
08-26 10:52:27.633  2172  2172 V MediaPlayer[Native]: setListener
08-26 10:52:27.633  2172  2172 V MediaPlayer[Native]: disconnect
08-26 10:52:27.633  2172  2172 V MediaPlayer[Native]: destructor
,08-26 10:52:27.633   329  1399 V AudioFlinger: releasing 18 from 2172 for -1
08-26 10:52:27.633   329  1399 V AudioFlinger:  decremented refcount to 0
08-26 10:52:27.633   329  1399 V AudioFlinger: purging stale effects
08-26 10:52:27.634  2172  2172 V MediaPlayer[Native]: disconnect
08-26 10:52:27.638  2172  2172 D MusicBrowser: [MusicUtils.java:615:getSmartShareVersion()] oooooo versionCode:305000
08-26 10:52:27.639  2172  2172 I SmartShareClient: [SmartShareManagerClient] smartshare client supported version code: 305000
08-26 10:52:27.640  2172  2172 I SmartShareClient: [SmartShareManagerClient] smartshare client enabled
08-26 10:52:27.641  2172  2172 I MusicBrowser: [MusicUtils.java:787:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000018
08-26 10:52:27.642  2172  2172 I MusicBrowser: [MusicUtils.java:635:getSmartShareVersion()] oooooo SmartshareVersion:953
08-26 10:52:27.642  2172  2172 V MusicBrowser: [MediaPlaybackService.java:9312:terminateSmartShareClient()] oooooo 
08-26 10:52:27.642  2172  2172 I SmartShareClient: [SmartShareManagerClient] unregisterListener: 645385121
08-26 10:52:27.642  2172  2172 W SmartShareClient: [SmartShareManagerClient] unregisterListener invalid listener: 645385121
08-26 10:52:27.653  2172  2172 I SmartShareClient: [SmartShareManagerClient] terminate service: 2172/MediaPlaybackService/777213087
,08-26 10:52:27.658  2172  2172 E HomeCloudIF: unregiterHomeCloudBroadcast(), Illegal argument.
08-26 10:52:27.658  2172  2172 I SmartShareClient: [SmartShareManagerClient] unbindService context:android.app.Application@92f1c6
08-26 10:52:27.662  2172  2172 V CloudHub: [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.2.1, versionCode=202001, state=0
08-26 10:52:27.663  2172  2172 V CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
08-26 10:52:27.664  2172  2172 I CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
08-26 10:52:27.664  2172  2172 D MusicBrowser: [MediaPlaybackService.java:9007:setStopForeground()] oooooo bValue : true
08-26 10:52:27.665  2172  2172 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29999
08-26 10:52:27.666  1036  1889 I ActivityManager: Killing 5631:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
08-26 10:52:27.683  5605  5605 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
08-26 10:52:27.683  5605  5605 W System.err: android.os.DeadObjectException
08-26 10:52:27.683  5605  5605 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-26 10:52:27.683  5605  5605 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-26 10:52:27.683  5605  5605 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-26 10:52:27.683  5605  5605 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-26 10:52:27.684  5605  5605 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-26 10:52:27.684  5605  5605 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-26 10:52:27.684  5605  5605 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-26 10:52:27.684  5605  5605 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-26 10:52:27.684  5605  5605 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-26 10:52:27.684  5605  5605 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-26 10:52:27.684  5605  5605 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 10:52:27.684  5605  5605 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 10:52:27.684  5605  5605 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-26 10:52:27.684  5605  5605 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-26 10:52:27.684  5605  5605 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-26 10:52:27.684  5605  5605 W System.err: android.os.DeadObjectException
08-26 10:52:27.685  5605  5605 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
,08-26 10:52:27.685  5605  5605 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-26 10:52:27.685  5605  5605 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-26 10:52:27.685  5605  5605 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-26 10:52:27.685  5605  5605 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-26 10:52:27.685  5605  5605 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-26 10:52:27.685  5605  5605 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-26 10:52:27.685  5605  5605 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-26 10:52:27.685  5605  5605 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-26 10:52:27.685  5605  5605 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-26 10:52:27.685  5605  5605 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 10:52:27.685  5605  5605 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 10:52:27.685  5605  5605 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-26 10:52:27.685  5605  5605 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-26 10:52:27.686  5605  5605 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-26 10:52:27.686  5605  5605 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
08-26 10:52:27.894  6692  6782 I jxcore-log: JXcore Cordova bridge is ready!
08-26 10:52:27.894  6692  6782 I jxcore-log: 
08-26 10:52:27.895  6692  6782 W jxcore-log: JXcore engine is started
,08-26 10:52:27.899  1036  1737 W libprocessgroup: failed to open /acct/uid_1000/pid_5631/cgroup.procs: No such file or directory
08-26 10:52:27.900  1036  1737 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
08-26 10:52:27.902  5605  5605 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-26 10:52:27.902  5605  5605 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-26 10:52:27.912  6692  6756 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-26 10:52:27.917  6692  6692 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
08-26 10:52:27.950  1036  1889 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=6804 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-26 10:52:27.951  5605  5605 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-26 10:52:28.034  6804  6804 D UEI.SmartControl: Quickset Services start...
08-26 10:52:28.036  6804  6804 I UEI.SmartControl: Manufacture = LGE
08-26 10:52:28.036  6804  6804 D UEI.SmartControl: Id = LGNevo
08-26 10:52:28.038  6804  6804 D UEI.SmartControl: File observer start...
,08-26 10:52:28.041  6804  6804 E UEI.SmartControl: IR Port is disabled: false
08-26 10:52:28.042  6804  6804 D UEI.SmartControl: Starting file observer...
08-26 10:52:28.042  6804  6804 D UEI.SmartControl: Extracting JNI libs...
08-26 10:52:28.042  6804  6804 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
08-26 10:52:28.153  6804  6804 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
08-26 10:52:28.153  6804  6804 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-26 10:52:28.153  6804  6804 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,08-26 10:52:28.189  6804  6804 I UEI.SmartControl: --- Selecting new region: 6
,08-26 10:52:28.192  6804  6804 I UEI.SmartControl: Model = LG-D855
08-26 10:52:28.194  6804  6804 D UEI.SmartControl: QS Service created
08-26 10:52:28.211  6804  6804 I UEI.SmartControl: Service initServices...
,08-26 10:52:28.217  6804  6804 D UEI.SmartControl: QS start get config
,08-26 10:52:28.289  6804  6804 D UEI.SmartControl: Loading JNI Libs...
,08-26 10:52:28.638  6804  6804 I UEI.SmartControl: Supports setup maps: true
,08-26 10:52:28.647  6804  6804 D UEI.SmartControl: QS start statue = true Error code = 0
08-26 10:52:28.647  6804  6804 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-26 10:52:28.647  6804  6804 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-26 10:52:28.647  6804  6804 I UEI.SmartControl: ### init IR Blaster...
08-26 10:52:28.653  6804  6804 D serial_port: Configuring serial port
08-26 10:52:28.657  6804  6804 E UEI.SmartControl: UEIBLaster setting for 616
08-26 10:52:28.657  6804  6804 I UEI.SmartControl: Setting serial record hearder size = 2
,08-26 10:52:28.660  6804  6804 I UEI.SmartControl: configuring settings for MAXQ616
08-26 10:52:28.660  6804  6804 I UEI.SmartControl: Get version...
08-26 10:52:28.678  6804  6825 D UEI.SmartControl: serial port data available: 21
,08-26 10:52:28.706  6804  6804 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-26 10:52:28.706  6804  6804 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-26 10:52:28.706  6804  6804 I UEI.SmartControl: QS saving settings...
,08-26 10:52:28.710  6804  6804 D UEI.SmartControl: IR Blaster version: 25672567
08-26 10:52:28.728  6804  6825 D UEI.SmartControl: serial port data available: 4
,08-26 10:52:28.766  6804  6804 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-26 10:52:28.775  6804  6828 I UEI.SmartControl: Device manager: loading config....
08-26 10:52:28.775  6804  6828 D UEI.SmartControl: ----------- loading internal config...
08-26 10:52:28.786  6804  6804 E UEI.SmartControl: Services init done
08-26 10:52:28.787  6804  6804 D UEI.SmartControl: QS Service init finished
,08-26 10:52:28.790  6804  6804 D UEI.SmartControl: QS Service version name: 2.1.91
08-26 10:52:28.790  6804  6804 D UEI.SmartControl: QS Service version code: 201091
08-26 10:52:28.791  6804  6804 D UEI.SmartControl: Service requested: Control
08-26 10:52:28.793  6804  6828 E UEI.SmartControl: Loading SETTINGS...
08-26 10:52:28.797  6804  6804 D UEI.SmartControl: Request IControl service: devices are loaded...
08-26 10:52:28.800  1036  1978 I ActivityManager: Killing 5605:com.lge.qremote/u0a112 (adj 15): empty #17
08-26 10:52:28.804  6804  6828 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-26 10:52:28.813  6804  6827 I UEI.SmartControl: Notify AllClients services are ready: 0
08-26 10:52:28.813  6804  6827 D UEI.SmartControl: -----service ready thread exits
,08-26 10:52:28.868  6804  6804 D UEI.SmartControl: Internal service binding...
08-26 10:52:28.869  1036  2014 W libprocessgroup: failed to open /acct/uid_10112/pid_5605/cgroup.procs: No such file or directory
,08-26 10:52:30.089  6639  6639 W GAV2    : Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,08-26 10:52:30.099  1036  1970 I ActivityManager: Killing 6310:com.android.calendar/u0a13 (adj 15): empty #17
08-26 10:52:30.201  1036  1942 W libprocessgroup: failed to open /acct/uid_10013/pid_6310/cgroup.procs: No such file or directory
,08-26 10:52:31.063  6639  6745 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,08-26 10:52:33.760  6804  6826 D serial_port: close(fd = 25)
,08-26 10:52:33.765  6804  6829 D UEI.SmartControl: Internal timer expired: 1
08-26 10:52:33.766  6804  6829 D UEI.SmartControl: unbind internal service
08-26 10:52:33.772  6804  6804 D UEI.SmartControl: Service.onUnbind: IControl
08-26 10:52:33.772  6804  6804 D UEI.SmartControl: Service.onDestroy
08-26 10:52:33.772  6804  6804 D UEI.SmartControl: Lock is in USE false
08-26 10:52:33.772  6804  6804 D UEI.SmartControl: unbind internal service
08-26 10:52:33.773  6804  6804 W System.err: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@28927431
08-26 10:52:33.773  6804  6804 W System.err: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
08-26 10:52:33.773  6804  6804 W System.err: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
08-26 10:52:33.773  6804  6804 W System.err: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
08-26 10:52:33.773  6804  6804 W System.err: 	at com.uei.control.Service.c(Unknown Source)
08-26 10:52:33.773  6804  6804 W System.err: 	at com.uei.control.Service.onDestroy(Unknown Source)
08-26 10:52:33.773  6804  6804 W System.err: 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
08-26 10:52:33.773  6804  6804 W System.err: 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
08-26 10:52:33.773  6804  6804 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
08-26 10:52:33.773  6804  6804 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 10:52:33.773  6804  6804 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-26 10:52:33.773  6804  6804 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-26 10:52:33.773  6804  6804 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 10:52:33.773  6804  6804 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 10:52:33.774  6804  6804 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-26 10:52:33.774  6804  6804 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-26 10:52:33.774  6804  6804 E UEI.SmartControl: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@28927431
,08-26 10:52:33.778  6804  6826 I UEI.SmartControl: Serial port is closed.
08-26 10:52:33.778  6804  6804 I UEI.SmartControl: Serial port is closed.
08-26 10:52:33.778  6804  6804 I UEI.SmartControl: Serial port is closed.
08-26 10:52:33.778  6804  6804 D UEI.SmartControl: Blaster closed
08-26 10:52:33.778  6804  6804 D UEI.SmartControl: Shut down QS...
08-26 10:52:33.778  6804  6804 D UEI.SmartControl: Stopping QS lib
08-26 10:52:33.779  6804  6804 D UEI.SmartControl: QS lib stop result = true
08-26 10:52:33.779  6804  6804 D UEI.SmartControl: Stopped QS lib
08-26 10:52:33.780  6804  6804 D UEI.SmartControl: Stopped file observer...
08-26 10:52:33.780  6804  6804 D UEI.SmartControl: QS shutdown complete
,08-26 10:52:37.544  6692  6782 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-26 10:52:37.544  6692  6782 I jxcore-log: 
,08-26 10:52:37.547  6692  6782 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-26 10:52:37.547  6692  6782 I jxcore-log: 
08-26 10:52:37.552  6692  6782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 10:52:37.552  6692  6782 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 10:52:37.552  6692  6782 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 10:52:37.552  6692  6782 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 10:52:37.552  6692  6782 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 10:52:37.552  6692  6782 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 10:52:37.552  6692  6782 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 10:52:37.552  6692  6782 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 10:52:37.554  6692  6782 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 10:52:37.557  6692  6782 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-26 10:52:37.557  6692  6782 I jxcore-log: 
,08-26 10:52:37.558  6692  6782 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-26 10:52:37.558  6692  6782 I jxcore-log: 
08-26 10:52:37.676  2172  2172 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19989
,08-26 10:52:38.062  6692  6782 D executeNativeTests: Running unit tests
,08-26 10:52:38.134  1036  1097 I ActivityManager: Waited long enough for: ServiceRecord{109c8c86 u0 com.google.android.gms/.wearable.service.WearableService}
,08-26 10:52:38.142  6692  6782 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 10:52:38.142  6692  6782 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a7d3a1c added. We now have 2 listener(s)
08-26 10:52:38.143  1036  1970 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 10:52:38.144  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-26 10:52:38.144  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 10:52:38.144  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 10:52:38.144  6692  6782 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 10:52:38.144  6692  6782 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3cae7625 added. We now have 2 listener(s)
08-26 10:52:38.144  6692  6782 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 10:52:38.145  6692  6782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-26 10:52:38.147  6692  6782 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 10:52:38.154  6692  6782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 10:52:38.154  6692  6782 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 10:52:38.154  6692  6782 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 10:52:38.154  6692  6782 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 10:52:38.154  6692  6782 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 10:52:38.154  6692  6782 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 10:52:38.154  6692  6782 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 10:52:38.154  6692  6782 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 10:52:38.156  6692  6782 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 10:52:38.156  6692  6782 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 10:52:38.158  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 10:52:38.159  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 10:52:38.161  6692  6782 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-26 10:52:38.164  6692  6782 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-26 10:52:38.164  6692  6782 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-26 10:52:38.166  6692  6782 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-26 10:52:38.167  6692  6782 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-26 10:52:38.167  6692  6782 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-26 10:52:38.167  6692  6782 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-26 10:52:38.167  6692  6782 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-26 10:52:38.168  6692  6782 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
08-26 10:52:38.168  6692  6782 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-26 10:52:38.168  6692  6782 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...,
08-26 10:52:38.169  6692  6782 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
,08-26 10:52:38.169  6692  6782 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 10:52:38.169  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 10:52:38.169  6692  6782 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 10:52:38.169  6692  6782 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a7d3a1c removed from the list
,08-26 10:52:38.169  6692  6782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 10:52:38.169  6692  6782 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3cae7625 removed from the list
08-26 10:52:38.169  6692  6782 D io.jxcore.node.ConnectivityMonitor: stop,
08-26 10:52:38.169  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 10:52:38.170  6692  6782 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:38.170  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
08-26 10:52:38.170  6692  6782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 10:52:38.170  6692  6782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
08-26 10:52:38.170  6692  6782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 10:52:38.170  6692  6782 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3cae7625 not in the list,
08-26 10:52:38.172  6692  6782 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-26 10:52:38.172  6692  6782 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 10:52:38.172  6692  6782 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 10:52:38.172  6692  6782 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-26 10:52:38.172  6692  6782 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 10:52:38.172  6692  6782 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:38.172  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:38.172  6692  6782 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a7d3a1c not in the list
08-26 10:52:38.172  6692  6782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-26 10:52:38.172  6692  6782 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3cae7625 not in the list
08-26 10:52:38.173  6692  6782 D io.jxcore.node.ConnectivityMonitor: stop
08-26 10:52:38.173  6692  6782 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:38.173  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:38.173  6692  6782 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:38.173  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:38.174  6692  6782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
08-26 10:52:38.174  6692  6782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 10:52:38.174  6692  6782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:38.174  6692  6782 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3cae7625 not in the list
08-26 10:52:38.178  6692  6782 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-26 10:52:38.178  6692  6782 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-26 10:52:38.178  6692  6782 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,08-26 10:52:38.178  6692  6782 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-26 10:52:38.178  6692  6782 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-26 10:52:38.178  6692  6782 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-26 10:52:38.178  6692  6782 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-26 10:52:38.178  6692  6782 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-26 10:52:38.178  6692  6782 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710],
08-26 10:52:38.178  6692  6782 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-26 10:52:38.178  6692  6782 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-26 10:52:38.178  6692  6782 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-26 10:52:38.178  6692  6782 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-26 10:52:38.178  6692  6782 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,08-26 10:52:38.178  6692  6782 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-26 10:52:38.178  6692  6782 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-26 10:52:38.178  6692  6782 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-26 10:52:38.178  6692  6782 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-26 10:52:38.178  6692  6782 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-26 10:52:38.178  6692  6782 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,08-26 10:52:38.178  6692  6782 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-26 10:52:38.178  6692  6782 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-26 10:52:38.178  6692  6782 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-26 10:52:38.178  6692  6782 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-26 10:52:38.178  6692  6782 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-26 10:52:38.180  6692  6782 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410],
08-26 10:52:38.180  6692  6782 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-26 10:52:38.180  6692  6782 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-26 10:52:38.180  6692  6782 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-26 10:52:38.180  6692  6782 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-26 10:52:38.180  6692  6782 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-26 10:52:38.180  6692  6782 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
08-26 10:52:38.180  6692  6782 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 10:52:38.180  6692  6782 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 10:52:38.181  6692  6782 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 10:52:38.181  6692  6782 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:38.181  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 10:52:38.181  6692  6782 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a7d3a1c not in the list
08-26 10:52:38.181  6692  6782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:38.181  6692  6782 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3cae7625 not in the list
08-26 10:52:38.181  6692  6782 D io.jxcore.node.ConnectivityMonitor: stop
08-26 10:52:38.181  6692  6782 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:38.181  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 10:52:38.181  6692  6782 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:38.181  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:38.182  6692  6782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 10:52:38.182  6692  6782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 10:52:38.182  6692  6782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:38.182  6692  6782 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3cae7625 not in the list,
08-26 10:52:38.183  6692  6782 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-26 10:52:38.185  6692  6782 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 10:52:38.187  6692  6782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 10:52:38.187  6692  6782 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 10:52:38.187  6692  6782 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 10:52:38.187  6692  6782 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 10:52:38.187  6692  6782 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 10:52:38.187  6692  6782 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
,08-26 10:52:38.187  6692  6782 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 10:52:38.187  6692  6782 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 10:52:38.188  6692  6782 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 10:52:38.188  6692  6782 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 10:52:38.190  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
08-26 10:52:38.191  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 10:52:38.191  6692  6782 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 10:52:38.191  6692  6782 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 10:52:38.191  6692  6782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 10:52:38.191  6692  6782 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 10:52:38.191  6692  6782 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-26 10:52:38.194  6692  6782 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-26 10:52:38.195  1036  1923 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 10:52:38.198  6692  6782 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-26 10:52:38.202  6692  6782 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-26 10:52:38.204  6692  6782 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage,
08-26 10:52:38.205  6692  6782 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-26 10:52:38.205  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 10:52:38.206  6692  6782 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,08-26 10:52:38.206  6692  6782 I io.jxcore.node.ConnectionHelper: start: OK
08-26 10:52:38.208  6692  6782 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 10:52:38.209  6692  6782 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 10:52:38.209  6692  6782 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 10:52:38.209  6692  6782 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
08-26 10:52:38.209  6692  6782 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:38.209  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 10:52:38.209  6692  6782 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a7d3a1c not in the list
08-26 10:52:38.209  6692  6782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:38.209  6692  6782 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3cae7625 not in the list
,08-26 10:52:38.209  6692  6782 D io.jxcore.node.ConnectivityMonitor: stop
08-26 10:52:38.209  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:38.209  6692  6782 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-26 10:52:38.210  6692  6782 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 10:52:38.212  6692  6782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 10:52:38.212  6692  6782 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 10:52:38.212  6692  6782 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
,08-26 10:52:38.212  6692  6782 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 10:52:38.212  6692  6782 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 10:52:38.212  6692  6782 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 10:52:38.212  6692  6782 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 10:52:38.212  6692  6782 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 10:52:38.213  6692  6782 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 10:52:38.213  6692  6782 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 10:52:38.215  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 10:52:38.216  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 10:52:38.216  6692  6782 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 10:52:38.216  6692  6782 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 10:52:38.216  6692  6782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 10:52:38.216  6692  6782 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 10:52:38.216  6692  6782 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-26 10:52:38.220  6692  6782 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-26 10:52:38.220  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 10:52:38.221  6692  6782 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-26 10:52:38.221  6692  6782 I io.jxcore.node.ConnectionHelper: start: OK
08-26 10:52:38.222  6692  6782 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 10:52:38.222  6692  6782 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 10:52:38.222  6692  6782 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 10:52:38.222  6692  6782 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 10:52:38.222  6692  6782 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:38.222  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 10:52:38.222  6692  6782 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a7d3a1c not in the list
08-26 10:52:38.222  6692  6782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:38.222  6692  6782 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3cae7625 not in the list
08-26 10:52:38.222  6692  6782 D io.jxcore.node.ConnectivityMonitor: stop
08-26 10:52:38.222  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:38.223  6692  6782 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:38.223  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:38.223  6692  6782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 10:52:38.223  6692  6782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 10:52:38.224  6692  6782 D BluetoothLeScanner: could not find callback wrapper
08-26 10:52:38.224  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 10:52:38.224  6692  6782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52,:38.224  6692  6782 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3cae7625 not in the list
08-26 10:52:38.225  6692  6782 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-26 10:52:38.227  6692  6782 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 10:52:38.229  6692  6782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 10:52:38.229  6692  6782 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 10:52:38.229  6692  6782 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 10:52:38.229  6692  6782 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 10:52:38.229  6692  6782 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 10:52:38.229  6692  6782 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 10:52:38.229  6692  6782 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 10:52:38.229  6692  6782 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 10:52:38.230  6692  6782 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 10:52:38.230  6692  6782 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 10:52:38.230  6692  6782 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 10:52:38.230  6692  6782 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 10:52:38.230  6692  6782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 10:52:38.230  6692  6782 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 10:52:38.231  6692  6782 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-26 10:52:38.232  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 10:52:38.234  6692  6782 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-26 10:52:38.234  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 10:52:38.234  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 10:52:38.235  6692  6782 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-26 10:52:38.235  6692  6782 I io.jxcore.node.ConnectionHelper: start: OK
08-26 10:52:38.235  6692  6782 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 10:52:38.235  6692  6782 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 10:52:38.235  6692  6782 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 10:52:38.236  6692  6782 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 10:52:38.236  6692  6782 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 10:52:38.236  6692  6782 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 10:52:38.236  6692  6782 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 10:52:38.236  6692  6782 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:38.236  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 10:52:38.236  6692  6782 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a7d3a1c not in the list
08-26 10:52:38.236  6692  6782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:38.236  6692  6782 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3cae7625 not in the list
08-26 10:52:38.236  6692  6782 D io.jxcore.node.ConnectivityMonitor: stop
08-26 10:52:38.236  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:38.236  6692  6782 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:38.236  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:38.237  6692  6782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 10:52:38.237  6692  6782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 10:52:38.238  6692  6782 D BluetoothLeScanner: could not find callback wrapper
08-26 10:52:38.238  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 10:52:38.239  6692  6782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:38.239  6692  6782 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3cae7625 not in the list
08-26 10:52:38.242  6692  6782 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-26 10:52:38.242  6692  6782 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 10:52:38.242  6692  6782 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 10:52:38.242  6692  6782 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 10:52:38.242  6692  6782 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 10:52:38.242  6692  6782 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:38.242  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:38.242  6692  6782 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a7d3a1c not in the list
08-26 10:52:38.242  6692  6782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:38.242  6692  6782 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3cae7625 not in the list
08-26 10:52:38.243  6692  6782 D io.jxcore.node.ConnectivityMonitor: stop
08-26 10:52:38.243  6692  6782 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:38.243  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:38.243  6692  6782 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:38.243  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:38.244  6692  6782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 10:52:38.244  6692  6782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 10:52:38.245  6692  6782 D BluetoothLeScanner: could not find callback wrapper
08-26 10:52:38.245  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 10:52:38.245  6692  6782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:38.245  6692  6782 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3cae7625 not in the list
08-26 10:52:38.246  6692  6782 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-26 10:52:38.246  6692  6782 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 10:52:38.246  6692  6782 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 10:52:38.246  6692  6782 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 10:52:38.246  6692  6782 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 10:52:38.246  6692  6782 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:38.246  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:38.246  6692  6782 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a7d3a1c not in the list
08-26 10:52:38.246  6692  6782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:38.246  6692  6782 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3cae7625 not in the list
08-26 10:52:38.246  6692  6782 D io.jxcore.node.ConnectivityMonitor: stop
08-26 10:52:38.246  6692  6782 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:38.246  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:38.246  6692  6782 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:38.247  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 10:52:38.250  6692  6782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 10:52:38.250  6692  6782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 10:52:38.250  6692  6782 D BluetoothLeScanner: could not find callback wrapper
08-26 10:52:38.250  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 10:52:38.250  6692  6782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:38.250  6692  6782 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3cae7625 not in the list
08-26 10:52:38.251  6692  6782 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-26 10:52:38.251  6692  6782 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 10:52:38.251  6692  6782 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 10:52:38.251  6692  6782 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 10:52:38.251  6692  6782 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 10:52:38.251  6692  6782 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:38.251  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:38.251  6692  6782 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a7d3a1c not in the list
08-26 10:52:38.251  6692  6782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:38.251  6692  6782 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3cae7625 not in the list
08-26 10:52:38.251  6692  6782 D io.jxcore.node.ConnectivityMonitor: stop
08-26 10:52:38.251  6692  6782 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:38.251  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:38.251  6692  6782 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:38.251  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:38.252  6692  6782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 10:52:38.252  6692  6782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 10:52:38.252  6692  6782 D BluetoothLeScanner: could not find callback wrapper
08-26 10:52:38.252  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 10:52:38.252  6692  6782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:38.252  6692  6782 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3cae7625 not in the list
08-26 10:52:38.253  6692  6782 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-26 10:52:38.253  6692  6782 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 10:52:38.253  6692  6782 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 10:52:38.253  6692  6782 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 10:52:38.253  6692  6782 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 10:52:38.253  6692  6782 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:38.253  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:38.253  6692  6782 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a7d3a1c not in the list
08-26 10:52:38.253  6692  6782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:38.253  6692  6782 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3cae7625 not in the list
08-26 10:52:38.253  6692  6782 D io.jxcore.node.ConnectivityMonitor: stop
08-26 10:52:38.253  6692  6782 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:38.253  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:38.253  6692  6782 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:38.253  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:38.254  6692  6782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 10:52:38.254  6692  6782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 10:52:38.254  6692  6782 D BluetoothLeScanner: could not find callback wrapper
08-26 10:52:38.254  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 10:52:38.254  6692  6782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:38.254  6692  6782 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3cae7625 not in the list
08-26 10:52:38.255  6692  6782 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-26 10:52:38.255  6692  6782 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-26 10:52:38.255  6692  6782 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-26 10:52:38.255  6692  6782 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-26 10:52:38.255  6692  6782 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-26 10:52:38.255  6692  6782 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-26 10:52:38.255  6692  6782 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 10:52:38.255  6692  6782 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 10:52:38.255  6692  6782 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 10:52:38.255  6692  6782 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 10:52:38.255  6692  6782 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:38.255  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:38.255  6692  6782 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a7d3a1c not in the list
08-26 10:52:38.255  6692  6782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:38.255  6692  6782 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3cae7625 not in the list
08-26 10:52:38.255  6692  6782 D io.jxcore.node.ConnectivityMonitor: stop
08-26 10:52:38.255  6692  6782 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:38.255  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:38.255  6692  6782 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:38.255  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:38.256  6692  6782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 10:52:38.256  6692  6782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 10:52:38.256  6692  6782 D BluetoothLeScanner: could not find callback wrapper
08-26 10:52:38.256  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 10:52:38.256  6692  6782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:38.256  6692  6782 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3cae7625 not in the list
08-26 10:52:38.257  6692  6782 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 10:52:38.257  6692  6782 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-26 10:52:38.257  6692  6782 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-26 10:52:38.259  6692  6782 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 10:52:38.259  6692  6782 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-26 10:52:38.259  6692  6782 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-26 10:52:38.259  6692  6782 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-26 10:52:38.259  6692  6782 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-26 10:52:38.259  6692  6782 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-26 10:52:38.259  6692  6782 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-26 10:52:38.259  6692  6782 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-26 10:52:38.259  6692  6782 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-26 10:52:38.259  6692  6782 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-26 10:52:38.259  6692  6782 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-26 10:52:38.259  6692  6782 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-26 10:52:38.259  6692  6782 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-26 10:52:38.259  6692  6782 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-26 10:52:38.259  6692  6782 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-26 10:52:38.260  6692  6782 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-26 10:52:38.260  6692  6782 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-26 10:52:38.260  6692  6782 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-26 10:52:38.260  6692  6782 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-26 10:52:38.260  6692  6782 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-26 10:52:38.260  6692  6782 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-26 10:52:38.260  6692  6782 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-26 10:52:38.260  6692  6782 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-26 10:52:38.260  6692  6782 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-26 10:52:38.260  6692  6782 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-26 10:52:38.260  6692  6782 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-26 10:52:38.260  6692  6782 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-26 10:52:38.260  6692  6782 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-26 10:52:38.260  6692  6782 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-26 10:52:38.260  6692  6782 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-26 10:52:38.260  6692  6782 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-26 10:52:38.260  6692  6782 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-26 10:52:38.260  6692  6782 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-26 10:52:38.260  6692  6782 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-26 10:52:38.260  6692  6782 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-26 10:52:38.260  6692  6782 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 10:52:38.260  6692  6782 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-26 10:52:38.260  6692  6782 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-26 10:52:38.260  6692  6782 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 10:52:38.260  6692  6782 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-26 10:52:38.260  6692  6782 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-26 10:52:38.262  6692  6782 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-26 10:52:38.263  6692  6782 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-26 10:52:38.263  6692  6782 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-26 10:52:38.264  6692  6782 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-26 10:52:38.264  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-26 10:52:38.264  6692  6782 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-26 10:52:38.264  6692  6782 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 10:52:38.264  6692  6782 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-26 10:52:38.265  6692  6838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 821)
08-26 10:52:38.265  6692  6782 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 10:52:38.265  6692  6782 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 10:52:38.265  6692  6782 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 10:52:38.265  6692  6782 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 10:52:38.265  6692  6782 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:38.265  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:38.265  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-26 10:52:38.266  6692  6782 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a7d3a1c not in the list
08-26 10:52:38.266  6692  6782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:38.266  6692  6782 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3cae7625 not in the list
08-26 10:52:38.266  6692  6782 D io.jxcore.node.ConnectivityMonitor: stop
08-26 10:52:38.266  6692  6782 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:38.266  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:38.266  6692  6782 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:38.266  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:38.267  6692  6782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 10:52:38.267  6692  6782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 10:52:38.268  6692  6782 D BluetoothLeScanner: could not find callback wrapper
08-26 10:52:38.268  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 10:52:38.268  6692  6782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:38.268  6692  6782 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3cae7625 not in the list
08-26 10:52:38.269  6692  6782 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-26 10:52:38.269  6692  6782 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 10:52:38.269  6692  6782 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 10:52:38.269  6692  6782 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 10:52:38.269  6692  6782 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 10:52:38.269  6692  6782 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:38.269  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:38.269  6692  6782 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a7d3a1c not in the list
08-26 10:52:38.269  6692  6782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:38.269  6692  6782 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3cae7625 not in the list
08-26 10:52:38.269  6692  6782 D io.jxcore.node.ConnectivityMonitor: stop
08-26 10:52:38.269  6692  6782 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:38.269  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:38.269  6692  6782 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:38.269  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:38.270  6692  6839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 821
08-26 10:52:38.270  6692  6839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 821)
08-26 10:52:38.270  6692  6839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 821)
08-26 10:52:38.270  6692  6782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 10:52:38.270  6692  6782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 10:52:38.271  6692  6782 D BluetoothLeScanner: could not find callback wrapper
08-26 10:52:38.271  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 10:52:38.271  6692  6782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:38.271  6692  6782 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3cae7625 not in the list
08-26 10:52:38.271  6692  6782 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-26 10:52:38.272  6692  6782 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 10:52:38.272  6692  6782 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 10:52:38.272  6692  6782 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 10:52:38.272  6692  6782 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 10:52:38.272  6692  6782 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:38.272  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:38.272  6692  6782 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a7d3a1c not in the list
08-26 10:52:38.272  6692  6782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:38.272  6692  6782 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3cae7625 not in the list
08-26 10:52:38.272  6692  6782 D io.jxcore.node.ConnectivityMonitor: stop
08-26 10:52:38.272  6692  6782 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:38.272  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:38.272  6692  6782 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:38.272  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:38.274  6692  6782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 10:52:38.274  6692  6782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 10:52:38.275  6692  6782 D BluetoothLeScanner: could not find callback wrapper
08-26 10:52:38.275  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 10:52:38.275  6692  6782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:38.275  6692  6782 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3cae7625 not in the list
08-26 10:52:38.276  6692  6782 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-26 10:52:38.276  6692  6782 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-26 10:52:38.276  6692  6782 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-26 10:52:38.276  6692  6782 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-26 10:52:38.277  6692  6782 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-26 10:52:38.277  6692  6782 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-26 10:52:38.277  6692  6782 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-26 10:52:38.277  6692  6782 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-26 10:52:38.277  6692  6782 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-26 10:52:38.277  6692  6782 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-26 10:52:38.277  6692  6782 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-26 10:52:38.277  6692  6782 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-26 10:52:38.277  6692  6782 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 10:52:38.277  6692  6782 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 10:52:38.277  6692  6782 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 10:52:38.278  6692  6782 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 10:52:38.278  6692  6782 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:38.278  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:38.278  6692  6782 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a7d3a1c not in the list
08-26 10:52:38.278  6692  6782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:38.278  6692  6782 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3cae7625 not in the list
08-26 10:52:38.278  6692  6782 D io.jxcore.node.ConnectivityMonitor: stop
08-26 10:52:38.278  6692  6782 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:38.278  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:38.278  6692  6782 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:38.278  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:38.280  6692  6782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 10:52:38.280  6692  6782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 10:52:38.281  6692  6782 D BluetoothLeScanner: could not find callback wrapper
08-26 10:52:38.281  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 10:52:38.281  6692  6782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:38.281  6692  6782 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3cae7625 not in the list
08-26 10:52:38.281  6692  6782 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 10:52:38.281  6692  6782 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:38.281  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:38.281  6692  6782 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a7d3a1c not in the list
08-26 10:52:38.281  6692  6782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:38.281  6692  6782 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3cae7625 not in the list
08-26 10:52:38.281  6692  6782 D io.jxcore.node.ConnectivityMonitor: stop
,08-26 10:52:38.281  6692  6782 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:38.281  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:38.281  6692  6782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:38.281  6692  6782 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3cae7625 not in the list
08-26 10:52:38.281  6692  6782 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 10:52:38.282  6692  6782 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:38.282  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:38.282  6692  6782 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a7d3a1c not in the list
08-26 10:52:38.282  6692  6782 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 10:52:38.282  6692  6782 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 10:52:38.282  6692  6782 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 10:52:38.282  6692  6782 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 10:52:38.282  6692  6782 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:38.282  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:38.282  6692  6782 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a7d3a1c not in the list
08-26 10:52:38.282  6692  6782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:38.282  6692  6782 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3cae7625 not in the list
08-26 10:52:38.282  6692  6782 D io.jxcore.node.ConnectivityMonitor: stop
08-26 10:52:38.282  6692  6782 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:38.282  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:38.282  6692  6782 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:38.282  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:38.287  6692  6782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 10:52:38.287  6692  6782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 10:52:38.288  6692  6782 D BluetoothLeScanner: could not find callback wrapper
08-26 10:52:38.288  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 10:52:38.288  6692  6782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:38.288  6692  6782 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3cae7625 not in the list
08-26 10:52:38.289  6692  6782 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-26 10:52:38.289  6692  6782 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 10:52:38.290  6692  6782 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-26 10:52:38.290  6692  6782 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-26 10:52:38.290  6692  6782 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-26 10:52:38.290  6692  6692 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-26 10:52:38.290  6692  6782 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-26 10:52:38.290  6692  6782 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-26 10:52:38.291  6692  6782 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 10:52:38.291  6692  6782 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-26 10:52:38.291  6692  6782 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-26 10:52:38.291  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-26 10:52:38.291  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:38.291  6692  6782 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-26 10:52:38.291  6692  6692 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-26 10:52:38.292  6692  6782 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a7d3a1c not in the list
08-26 10:52:38.292  6692  6782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:38.292  6692  6782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 10:52:38.292  6692  6782 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 10:52:38.292  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 10:52:38.292  6692  6782 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-26 10:52:38.293  6692  6782 D BluetoothLeScanner: could not find callback wrapper
08-26 10:52:38.293  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 10:52:38.293  6692  6782 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-26 10:52:38.293  6692  6782 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:38.293  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:38.293  6692  6782 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 10:52:38.297  6692  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 10:52:38.297  6692  6782 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3cae7625 not in the list
08-26 10:52:38.297  6692  6692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 10:52:38.297  6692  6692 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 10:52:38.297  6692  6782 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 10:52:38.298  6692  6782 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 10:52:38.298  6692  6782 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 10:52:38.298  6692  6782 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 10:52:38.298  6692  6782 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:38.298  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:38.298  6692  6782 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a7d3a1c not in the list
08-26 10:52:38.298  6692  6782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:38.298  6692  6782 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3cae7625 not in the list
08-26 10:52:38.298  6692  6782 D io.jxcore.node.ConnectivityMonitor: stop
08-26 10:52:38.298  6692  6782 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:38.298  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:38.298  6692  6782 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:38.298  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:38.299  6692  6782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 10:52:38.299  6692  6782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 10:52:38.299  6692  6782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:38.299  6692  6782 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3cae7625 not in the list
08-26 10:52:38.300  6692  6782 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-26 10:52:38.300  6692  6782 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-26 10:52:38.300  6692  6782 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-26 10:52:38.300  6692  6782 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-26 10:52:38.300  6692  6782 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 10:52:38.300  6692  6782 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 10:52:38.300  6692  6782 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 10:52:38.300  6692  6782 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 10:52:38.300  6692  6782 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:38.300  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:38.300  6692  6782 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a7d3a1c not in the list
08-26 10:52:38.300  6692  6782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:38.300  6692  6782 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3cae7625 not in the list
08-26 10:52:38.300  6692  6782 D io.jxcore.node.ConnectivityMonitor: stop
08-26 10:52:38.300  6692  6782 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:38.300  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:38.300  6692  6782 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:38.300  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:38.302  6692  6782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 10:52:38.302  6692  6782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 10:52:38.302  6692  6782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:38.302  6692  6782 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3cae7625 not in the list
08-26 10:52:38.303  1036  1784 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 10:52:38.303  6692  6840 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-26 10:52:38.303  6692  6840 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-26 10:52:38.303  6692  6692 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-26 10:52:38.303  1036  2005 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 10:52:38.304  1036  2033 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 10:52:38.304  6692  6782 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 10:52:38.304  6692  6782 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 10:52:38.304  6692  6782 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 10:52:38.304  6692  6782 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 10:52:38.305  6692  6782 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:38.305  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:38.305  6692  6782 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a7d3a1c not in the list
08-26 10:52:38.305  6692  6782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:38.305  6692  6782 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3cae7625 not in the list
08-26 10:52:38.305  6692  6782 D io.jxcore.node.ConnectivityMonitor: stop
08-26 10:52:38.305  6692  6782 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:38.305  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:38.305  6692  6782 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:38.305  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:38.305  6692  6782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 10:52:38.305  6692  6782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 10:52:38.305  6692  6782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:38.305  6692  6782 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3cae7625 not in the list
08-26 10:52:38.306  6692  6782 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 10:52:38.306  6692  6782 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 10:52:38.306  6692  6782 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 10:52:38.306  6692  6782 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 10:52:38.306  6692  6782 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:38.306  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:38.306  6692  6782 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a7d3a1c not in the list
08-26 10:52:38.306  6692  6782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:38.306  6692  6782 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3cae7625 not in the list
08-26 10:52:38.306  6692  6782 D io.jxcore.node.ConnectivityMonitor: stop
08-26 10:52:38.306  6692  6782 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:38.306  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:38.306  6692  6782 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:38.306  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:38.307  6692  6782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 10:52:38.307  6692  6782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 10:52:38.307  6692  6782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:38.307  6692  6782 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3cae7625 not in the list
08-26 10:52:38.309  6692  6782 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-26 10:52:38.309  6692  6782 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-26 10:52:38.309  6692  6782 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-26 10:52:38.309  6692  6782 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-26 10:52:38.309  6692  6782 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-26 10:52:38.309  6692  6782 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-26 10:52:38.311  6692  6782 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-26 10:52:38.311  6692  6782 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-26 10:52:38.312  6692  6782 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-26 10:52:38.312  6692  6782 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-26 10:52:38.312  6692  6782 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-26 10:52:38.312  6692  6782 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-26 10:52:38.313  6692  6782 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-26 10:52:38.313  6692  6782 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-26 10:52:38.313  6692  6782 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-26 10:52:38.313  6692  6782 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-26 10:52:38.314  6692  6782 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-26 10:52:38.314  6692  6782 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-26 10:52:38.314  6692  6782 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-26 10:52:38.314  6692  6782 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-26 10:52:38.315  6692  6782 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 10:52:38.315  6692  6782 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@844d852 added. We now have 2 listener(s)
08-26 10:52:38.315  6692  6782 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 10:52:38.316  6692  6782 D BluetoothAdapter: enable(): BT is already enabled..!
08-26 10:52:38.317  1036  1584 D WifiServiceImplEx: setWifiEnabled: true pid=6692, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-26 10:52:38.317  1036  1584 D WifiService: setWifiEnabled: true pid=6692, uid=10118
08-26 10:52:38.317  1036  1584 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-26 10:52:38.318  6692  6782 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 10:52:38.318  6692  6782 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@20a54723 added. W,e now have 3 listener(s)
08-26 10:52:38.318  6692  6782 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 10:52:38.330  6692  6782 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 10:52:38.330  6692  6782 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2a1e2420 added. We now have 4 listener(s)
08-26 10:52:38.330  6692  6782 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 10:52:38.331  6692  6782 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 10:52:38.332  6692  6782 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2e9751d9 added. We now have 5 listener(s)
08-26 10:52:38.332  6692  6782 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 10:52:38.333  6692  6838 W LGMDMUISystemServiceAdapter: checkBluetoothPairing btPolicy: false
08-26 10:52:38.333  6692  6838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 821)
08-26 10:52:38.334  1036  1736 D WifiServiceImplEx: setWifiEnabled: false pid=6692, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-26 10:52:38.334  1036  1736 D WifiService: setWifiEnabled: false pid=6692, uid=10118
08-26 10:52:38.334  1036  1736 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-26 10:52:38.353  1036  1970 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 10:52:38.354  1036  1970 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@86e2e2 mBinding = false
08-26 10:52:38.354  1036  1440 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-26 10:52:38.354  1036  1440 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-26 10:52:38.354  1036  1440 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-26 10:52:38.354  1036  1440 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-26 10:52:38.355  1036  1440 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-26 10:52:38.355  1036  1440 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-26 10:52:38.355  1036  1440 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-26 10:52:38.355  1036  1440 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-26 10:52:38.356  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-26 10:52:38.356  1036  1440 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-26 10:52:38.356  1036  1440 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-26 10:52:38.356  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-26 10:52:38.356  1036  1036 D Ulp_jni : JNI:system_update. Event-4
08-26 10:52:38.365  1036  1440 D WifiNative-wlan0: SAVE_CONFIG: returned true
,08-26 10:52:38.367  1036  1393 D LGWifiP2pService: InactiveState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-26 10:52:38.367  1036  1393 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-26 10:52:38.368  1036  1440 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
,08-26 10:52:38.368  2744  2744 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-26 10:52:38.368  1036  1112 D BluetoothManagerService: Message: 2
08-26 10:52:38.368  1036  1440 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-26 10:52:38.368  1036  1440 D WifiNative-wlan0: doBoolean: SET ps 1
08-26 10:52:38.369  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-26 10:52:38.369  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-26 10:52:38.369  1036  1036 D Ulp_jni : JNI:system_update. Event-4
08-26 10:52:38.369  1036  1112 D BluetoothManagerService: Sending off request.
08-26 10:52:38.369  1036  1440 D WifiNative-wlan0: SET ps 1: returned true
08-26 10:52:38.369  3827  3842 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-26 10:52:38.370  1036  2866 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-26 10:52:38.370  3827  3911 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-26 10:52:38.370  3827  3911 D BluetoothAdapterProperties: Setting state to 13
08-26 10:52:38.370  3827  3911 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-26 10:52:38.370  3827  3911 D BluetoothAdapterProperties: onBluetoothDisable()
08-26 10:52:38.370  3827  3911 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-26 10:52:38.373  6692  6782 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 10:52:38.373   324   895 D CommandListener: Clearing all IP addresses on wlan0
08-26 10:52:38.377  1036  1112 D BluetoothManagerService: Message: 60
08-26 10:52:38.377  1036  1112 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-26 10:52:38.377  1036  1112 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
,08-26 10:52:38.380  1943  1943 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-26 10:52:38.380  1604  1604 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-26 10:52:38.382  3827  3827 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-26 10:52:38.382  3827  3827 D BluetoothMapService: STATE_TURNING_OFF
08-26 10:52:38.382  3827  3827 V BluetoothMapService: Handler(): got msg=4
08-26 10:52:38.383  3827  3827 D BluetoothMapService: MAP Service closeService in
08-26 10:52:38.383  3827  3827 D BluetoothMapMasInstance: MAP Service shutdown
08-26 10:52:38.383  3827  4167 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-26 10:52:38.383  3827  4167 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 10:52:38.383  3827  4167 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-26 10:52:38.383  3827  4167 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-26 10:52:38.383  3827  4167 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-26 10:52:38.383  3827  4167 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-26 10:52:38.383  3827  4167 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-26 10:52:38.383  3827  4167 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-26 10:52:38.384  3827  3827 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-26 10:52:38.384  3827  3827 V BluetoothMapService: MAP Service closeService out
08-26 10:52:38.384  3827  3827 V BtOppService: Receiver DISABLED_ACTION 
08-26 10:52:38.384  3827  3827 I BtOppRfcommListener: stopping Accept Thread
08-26 10:52:38.384  3827  3827 V BtOppRfcommListener: close mBtServerSocket
08-26 10:52:38.385  3827  3827 V BtOppRfcommListener: waiting for thread to terminate
08-26 10:52:38.385  3827  4200 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 10:52:38.385  3827  4200 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-26 10:52:38.385  3827  3827 V BtOppRfcommListener: done waiting for thread to terminate
08-26 10:52:38.411  6692  6782 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 10:52:38.411  6692  6782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 10:52:38.411  6692  6782 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 10:52:38.411  6692  6782 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 10:52:38.411  6692  6782 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 10:52:38.411  6692  6782 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 10:52:38.411  6692  6782 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 10:52:38.411  6692  6782 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 10:52:38.411  6692  6782 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 10:52:38.411  6692  6782 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 10:52:38.411  6692  6782 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_,CARE, BSSID name: null
08-26 10:52:38.411  6692  6782 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 10:52:38.412  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 10:52:38.414  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 10:52:38.415  6692  6692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 10:52:38.415  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 10:52:38.415  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 10:52:38.415  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 10:52:38.415  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 10:52:38.415  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 10:52:38.415  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 10:52:38.415  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 10:52:38.415  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 10:52:38.416  6692  6692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 10:52:38.416  6692  6692 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-26 10:52:38.417  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 10:52:38.417  1036  1495 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-26 10:52:38.425  1036  1097 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6844 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-26 10:52:38.425  1036  1495 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
08-26 10:52:38.449  1036  1036 D WifiHS20: hidePasspointNotification off =false
,08-26 10:52:38.452  3827  3827 V BtOppService: onDestroy
08-26 10:52:38.454  1943  1943 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-26 10:52:38.455  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 10:52:38.455  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-26 10:52:38.455  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-26 10:52:38.459  1036  1393 D LGWifiP2pService: InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-26 10:52:38.459  1036  1393 D LGWifiP2pService: P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-26 10:52:38.460  1036  1393 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@16ddb95b
08-26 10:52:38.460  1036  1393 D LGWifiP2pService: P2pDisablingState
08-26 10:52:38.460  1036  1393 D LGWifiP2pService: P2pDisablingState{ when=-1ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-26 10:52:38.460  1036  1393 D LGWifiP2pService: p2p socket connection lost
08-26 10:52:38.460  1036  1393 D LGWifiP2pService: P2pDisabledState
08-26 10:52:38.461  1036  1440 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 10:52:38.462  1036  1440 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 10:52:38.462  1036  1440 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 10:52:38.463  1036  1440 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 10:52:38.463  1036  1440 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 10:52:38.464  1036  1440 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 10:52:38.464  1036  1495 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-26 10:52:38.464  1036  1495 D DSQN    : disableDataServiceNotify
08-26 10:52:38.464  1036  1495 D DSQN    : stop dsqn bin
,08-26 10:52:38.465  1036  1924 I art     : Explicit concurrent mark sweep GC freed 24672(1234KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/65MB, paused 1.634ms total 89.625ms
08-26 10:52:38.467  1036  1036 D WifiHS20: hidePasspointNotification off =false
08-26 10:52:38.469  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 10:52:38.469  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 10:52:38.469  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-26 10:52:38.469  1036  1036 D WifiScanningService: SCAN_AVAILABLE : 1
08-26 10:52:38.469  1036  1036 D RttService: SCAN_AVAILABLE : 1
08-26 10:52:38.469  1036  1558 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-26 10:52:38.469  1036  1559 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-26 10:52:38.470  1036  1440 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 10:52:38.470  1036  1440 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 10:52:38.470  1036  1440 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 10:52:38.470  1036  1440 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-26 10:52:38.471  1036  1440 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-26 10:52:38.471  1036  1440 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-26 10:52:38.471  2744  2744 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-26 10:52:38.471  1036  1393 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-26 10:52:38.471  1036  1393 D LGWifiP2pService: DefaultState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-26 10:52:38.471  1943  1943 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-26 10:52:38.472  1943  1943 D WfdsService: WifiP2pState is changed : false
08-26 10:52:38.472  1943  2260 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-26 10:52:38.472  1943  2260 D WfdsService: Set the WFDS Monitor: false
08-26 10:52:38.472  3827  3918 D BluetoothAdapterProperties: Scan Mode:20
08-26 10:52:38.473  3827  3911 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-26 10:52:38.473  3827  3992 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-26 10:52:38.473  3827  4177 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 10:52:38.473  3827  4202 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 10:52:38.473  3827  3992 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-26 10:52:38.473  3827  4201 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 10:52:38.473  3827  3827 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-26 10:52:38.474  1036  1440 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-26 10:52:38.474  1036  1440 D WifiNative-wlan0: doBoolean: SET ps 1
08-26 10:52:38.475  3827  3992 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-26 10:52:38.475  3827  3992 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-26 10:52:38.475  3827  3992 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-26 10:52:38.475  3827  3992 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-26 10:52:38.475  3827  3992 W bt-l2cap: L2CAP - PSM: 0x0019 n,ot found for deregistration
08-26 10:52:38.475  3827  3992 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-26 10:52:38.475  3827  3992 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 10:52:38.475  3827  3992 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-26 10:52:38.475  3827  3992 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 10:52:38.475  1036  1440 D WifiNative-wlan0: SET ps 1: returned true
08-26 10:52:38.475  3827  3992 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-26 10:52:38.475  3827  3992 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-26 10:52:38.475  3827  3992 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-26 10:52:38.476   324   895 D CommandListener: Clearing all IP addresses on wlan0
08-26 10:52:38.476  1943  2260 D WfdsMonitor: WFDS Monitor is stopped
08-26 10:52:38.476  1943  2777 D CtrlSupplicant: Received on exit socket, terminate
08-26 10:52:38.476  1943  2777 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-26 10:52:38.476  1943  2260 D WfdsService: STATE : WfdsDisabledState - enter
08-26 10:52:38.476  1943  2777 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-26 10:52:38.476  1943  2777 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-26 10:52:38.476  1943  2260 W WfdsService: DefaultState - msg [9445378] is not handled
08-26 10:52:38.476  1943  2268 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-26 10:52:38.476  3827  3911 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-26 10:52:38.477  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 10:52:38.477  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-26 10:52:38.478  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 10:52:38.480  6692  6692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 10:52:38.481  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 10:52:38.481  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 10:52:38.481  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 10:52:38.481  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 10:52:38.481  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 10:52:38.481  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 10:52:38.481  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 10:52:38.481  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 10:52:38.482  1036  1495 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-26 10:52:38.483  1036  1495 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 10:52:38.483  1036  1495 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 10:52:38.483  1036  1052 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
08-26 10:52:38.483  1036  1495 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 10:52:38.483  1036  1495 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-26 10:52:38.484  1036  1495 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-26 10:52:38.484  1036  1495 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-26 10:52:38.484  1036  1495 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-26 10:52:38.484  1036  1495 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-26 10:52:38.484  1036  1495 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-26 10:52:38.484  1604  2075 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-26 10:52:38.484  1036  1495 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-26 10:52:38.484  1036  1495 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 10:52:38.484  1036  1495 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 10:52:38.485  1036  1495, D NetworkManagementService: Removing idletimer
08-26 10:52:38.485  1036  1495 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 10:52:38.485  1036  1495 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-26 10:52:38.486  1036  2865 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-3ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-26 10:52:38.486  1036  2865 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-3ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-26 10:52:38.486  1036  2865 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-26 10:52:38.486  1036  2865 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-26 10:52:38.486  1036  1392 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-26 10:52:38.486  1036  2865 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-26 10:52:38.486  1036  1392 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-26 10:52:38.486  1036  2865 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-26 10:52:38.486  1036  1036 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-26 10:52:38.486  1036  2865 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=4 target=com.android.internal.util.StateMachine$SmHandler }
08-26 10:52:38.486  1036  2865 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on <unknown ssid>
08-26 10:52:38.486  1036  1036 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-26 10:52:38.486  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-26 10:52:38.486  1854  1854 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 10:52:38.486  1854  1854 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-26 10:52:38.487  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-26 10:52:38.487  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-26 10:52:38.487  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-26 10:52:38.487  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-26 10:52:38.487  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-26 10:52:38.489  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 10:52:38.489  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 10:52:38.489   324  6863 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-26 10:52:38.489  6692  6692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 10:52:38.489  6692  6692 V io.jxcore.node.,ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 10:52:38.489  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 10:52:38.489  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 10:52:38.489  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 10:52:38.489  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 10:52:38.489  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 10:52:38.489  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 10:52:38.489  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 10:52:38.489  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 10:52:38.490  1036  2865 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
08-26 10:52:38.490  1036  1110 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-26 10:52:38.495  6501  6501 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 10:52:38.497  1036  1440 D WifiNative-p2p0: doBoolean: TERMINATE
08-26 10:52:38.497  1036  1036 D WifiHS20: hidePasspointNotification off =false
08-26 10:52:38.498  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 10:52:38.498  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 10:52:38.498  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-26 10:52:38.498  1036  1440 D WifiNative-p2p0: TERMINATE: returned true
08-26 10:52:38.499  1036  1440 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-26 10:52:38.499  1036  1440 E WifiStateMachine: useWiFiOffloading() : false
08-26 10:52:38.499  1036  1440 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-26 10:52:38.499  1036  1440 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 10:52:38.499  1036  1440 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 10:52:38.500  1943  1943 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
,08-26 10:52:38.502  6692  6692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 10:52:38.502  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 10:52:38.502  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 10:52:38.502  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 10:52:38.502  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 10:52:38.502  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 10:52:38.502  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 10:52:38.502  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 10:52:38.502  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 10:52:38.503  6692  6692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 10:52:38.503  6692  6692 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 10:52:38.507  6692  6692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 10:52:38.507  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 10:52:38.507  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 10:52:38.507  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 10:52:38.507  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 10:52:38.507  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 10:52:38.507  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 10:52:38.507  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 10:52:38.507  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 10:52:38.508  6692  6692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 10:52:38.508  6692  6692 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 10:52:38.543  1036  1978 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6872 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-26 10:52:38.548  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-26 10:52:38.553  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 10:52:38.553  1036  1036 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
,08-26 10:52:38.559  2744  2744 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-26 10:52:38.559  2744  2744 I wpa_supplicant: monitor socket send errors count : 1
08-26 10:52:38.559  2744  2744 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1943-2\x00 that cannot receive messages
08-26 10:52:38.559  1036  2776 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-26 10:52:38.559  1036  2776 D WifiMonitor: Dropping event because (p2p0) is stopped
08-26 10:52:38.565  6844  6844 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-26 10:52:38.566  6844  6844 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
,08-26 10:52:38.566  6844  6844 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-26 10:52:38.566  6844  6844 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
,08-26 10:52:38.567  6844  6844 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-26 10:52:38.568  6844  6844 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-26 10:52:38.589  1604  1604 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-26 10:52:38.589  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 10:52:38.590  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-26 10:52:38.601  2744  2744 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-26 10:52:38.601  1036  2776 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-26 10:52:38.601  1036  2776 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-26 10:52:38.601  1036  2776 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-26 10:52:38.601  1036  1112 D Tethering: InitialState.processMessage what=4
08-26 10:52:38.602  2744  2744 W wpa_supplicant: USIM:  scard_deinit function
08-26 10:52:38.605  1036  2776 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-26 10:52:38.605  1036  2776 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-26 10:52:38.605  1036  2776 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-26 10:52:38.605  1036  1112 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-26 10:52:38.606  1036  1440 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=117846
08-26 10:52:38.606  1036  1440 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=117846
08-26 10:52:38.606  1036  1440 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=117847  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-26 10:52:38.607  1036  1440 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=117847  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-26 10:52:38.607  1036  1440 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-26 10:52:38.607  1036  1440 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-26 10:52:38.609  1036  2866 D DhcpStateMachine: StoppedState
08-26 10:52:38.609  1036  2866 D DhcpStateMachine: StoppedState{ when=-134ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-26 10:52:38.609  1604  1604 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,08-26 10:52:38.610  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 10:52:38.610  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 10:52:38.613  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-26 10:52:38.613  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 10:52:38.613  1036  1440 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-26 10:52:38.613  1036  1440 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-26 10:52:38.614  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 10:52:38.627  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-26 10:52:38.640  6872  6872 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,08-26 10:52:38.651  6872  6872 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
,08-26 10:52:38.652  6872  6872 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-26 10:52:38.653  1036  1889 I ActivityManager: Killing 6266:com.android.providers.calendar/u0a14 (adj 15): empty #17
08-26 10:52:38.659  6844  6844 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-26 10:52:38.679  1036  1053 W libprocessgroup: failed to open /acct/uid_10014/pid_6266/cgroup.procs: No such file or directory
,08-26 10:52:38.689  3827  3827 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-26 10:52:38.689  3827  3827 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 10:52:38.689  3827  3827 V BluetoothPbapReceiver: ***********state = 13
08-26 10:52:38.690  3827  3827 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
,08-26 10:52:38.692  3827  3827 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-26 10:52:38.692  3827  3827 V BluetoothPbapService: state: 13
08-26 10:52:38.692  3827  3827 V BluetoothPbapService: Pbap Service closeService in
08-26 10:52:38.692  3827  3827 V BluetoothPbapService: successfully stopped pbap service
08-26 10:52:38.692  3827  3827 V BluetoothPbapService: Pbap Service closeService out
08-26 10:52:38.693  3827  3827 V BluetoothPbapService: Pbap Service onDestroy
08-26 10:52:38.693  3827  3827 V BluetoothPbapService: Pbap Service closeService in
08-26 10:52:38.693  3827  3827 V BluetoothPbapService: Pbap Service closeService out
08-26 10:52:38.693  3827  3827 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-26 10:52:38.693  2128  2128 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-26 10:52:38.700  2744  2744 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-26 10:52:38.700  1036  2776 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-26 10:52:38.700  1036  2776 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
08-26 10:52:38.700  1036  2776 D WifiMonitor: Disconnecting from the supplicant, no more events
08-26 10:52:38.701  1036  1440 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
08-26 10:52:38.717  6844  6844 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 10:52:38.744  1036  1970 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6894 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-26 10:52:38.757  6844  6844 D LgDataFeature: LgDataFeature() Constructor: none
08-26 10:52:38.757  6844  6844 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-26 10:52:38.767  6844  6844 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 10:52:38.779  1036  1112 D BluetoothManagerService: Message: 20
08-26 10:52:38.779  1036  1112 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1ca4985c:true
,08-26 10:52:38.791  1036  1112 D BluetoothManagerService: Message: 30
,08-26 10:52:38.796  1036  1112 D BluetoothManagerService: Message: 30
08-26 10:52:38.798  6692  6692 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-26 10:52:38.799  6844  6844 D LocalBluetoothProfileManager: Adding local MAP profile
08-26 10:52:38.801  6844  6844 D BluetoothMap: Create BluetoothMap proxy object
08-26 10:52:38.805  1036  1112 D BluetoothManagerService: Message: 30
,08-26 10:52:38.813  1036  1440 D WifiOffDelayIfNotUsed: stopMonitoring
08-26 10:52:38.813  1036  1440 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-26 10:52:38.813  1036  1440 E WifiStateMachine: useWiFiOffloading() : false
08-26 10:52:38.813  1036  1440 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-26 10:52:38.814  1943  1943 D WfdsService: Supplicant Connection state is changed : false
08-26 10:52:38.814  1943  2260 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-26 10:52:38.814  1943  2260 D WfdsService: Set the WFDS Monitor: false
08-26 10:52:38.814  1943  2260 D WfdsMonitor: WFDS Monitor is stopped
08-26 10:52:38.816  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 10:52:38.816  1943  1943 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
,08-26 10:52:38.818  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-26 10:52:38.819  1036  1468 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-26 10:52:38.819  1036  1468 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-26 10:52:38.820  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 10:52:38.820  2454  2454 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 10:52:38.823  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 10:52:38.826  1036  1112 D BluetoothManagerService: Message: 30
08-26 10:52:38.828  6844  6844 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
08-26 10:52:38.830  6844  6844 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
,08-26 10:52:38.847  6844  6844 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
,08-26 10:52:38.850  6844  6844 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
08-26 10:52:38.859  6844  6844 D DockEventReceiver: finishStartingService: stopping service
,08-26 10:52:38.873  6844  6844 D BluetoothInputDevice: Proxy object connected
,08-26 10:52:38.875  6844  6844 D HidProfile: Bluetooth service connected
08-26 10:52:38.876  6844  6844 D BluetoothPan: BluetoothPAN Proxy object connected
08-26 10:52:38.877  6844  6844 D PanProfile: Bluetooth service connected
08-26 10:52:38.878  6844  6844 D BluetoothMap: Proxy object connected
08-26 10:52:38.879  6844  6844 D MapProfile: Bluetooth service connected
,08-26 10:52:38.879  6844  6844 D BluetoothMap: getConnectedDevices()
08-26 10:52:38.879  6844  6844 D BluetoothMap: Bluetooth is Not enabled
08-26 10:52:38.880  6844  6844 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-26 10:52:38.927  1036  1584 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6918 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,08-26 10:52:38.930  1036  1584 I ActivityManager: Killing 6368:com.android.defcontainer/u0a4 (adj 15): empty #17
08-26 10:52:38.955   351   351 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 473us total 28.239ms
,08-26 10:52:38.978   351   351 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 418us total 22.153ms
,08-26 10:52:38.997   351   351 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 366us total 17.983ms
08-26 10:52:38.998  1036  1381 V AlarmManager: RTC_WAKEUP set : Alarm{3f2aa524 type 0 when 1472201558879 com.android.vending} when 1472201558879
,08-26 10:52:39.014  1036  1924 W libprocessgroup: failed to open /acct/uid_10004/pid_6368/cgroup.procs: No such file or directory
,08-26 10:52:39.018  6894  6894 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-26 10:52:39.019  6894  6894 W LG Account v2.2: No ProfileInfo entries
08-26 10:52:39.019  6894  6894 I LG Account v2.2: isEnabled: false
08-26 10:52:39.020  6894  6894 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-26 10:52:39.020  6894  6894 I Feature : [Lifetracker]Country: EU
08-26 10:52:39.021  6894  6894 I Feature : [Lifetracker]Operator: OPEN
08-26 10:52:39.021  6894  6894 I Feature : [Lifetracker]Ranking support: false
08-26 10:52:39.021  6894  6894 I Feature : [Lifetracker]Comfort support: false
08-26 10:52:39.022  6894  6894 I Feature : [Lifetracker]Accessory: true
08-26 10:52:39.022  6894  6894 I Feature : [Lifetracker]Health device: true
08-26 10:52:39.022  6894  6894 I Feature : [Lifetracker]Extra Pedometer: false
08-26 10:52:39.023  6894  6894 I Feature : [Lifetracker]Blood glucose device: false
08-26 10:52:39.023  6894  6894 I Feature : [Lifetracker]Device Number: 3
08-26 10:52:39.037  6918  6918 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-26 10:52:39.043  6844  6844 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-26 10:52:39.052  6844  6844 D BluetoothPermissionRequest: onReceive
,08-26 10:52:39.054  6844  6844 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-26 10:52:39.066  6844  6844 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-26 10:52:39.073  3827  3827 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-26 10:52:39.073  3827  3827 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-26 10:52:39.074  3827  3827 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-26 10:52:39.078  6918  6918 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,08-26 10:52:39.081  3827  3827 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-26 10:52:39.081  3827  3827 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-26 10:52:39.081  1036  1889 V SIM_STK : Menu title from STK is T-Mobile
08-26 10:52:39.083  3827  3827 V BluetoothFtpService: Ftp Service onStartCommand
08-26 10:52:39.083  3827  3827 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-26 10:52:39.084  3827  3827 V BluetoothFtpService: Ftp Service closeService
08-26 10:52:39.084  3827  3827 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-26 10:52:39.086  3827  3827 V BluetoothFtpService: successfully stopped ftp service
08-26 10:52:39.086  3827  3827 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-26 10:52:39.086  3827  3827 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-26 10:52:39.086  3827  3827 V BluetoothSapReceiver: SapReceiver onReceive 
08-26 10:52:39.086  3827  3827 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 10:52:39.087  3827  3827 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-26 10:52:39.087  3827  3827 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-26 10:52:39.088  3827  3827 V BluetoothFtpService: Ftp Service onDestroy
08-26 10:52:39.088  3827  3827 V BluetoothFtpService: Ftp Service closeService
08-26 10:52:39.108  6918  6918 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
08-26 10:52:39.109  6918  6918 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-26 10:52:39.109  6918  6918 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-26 10:52:39.110  6918  6918 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-26 10:52:39.110  6918  6918 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
,08-26 10:52:39.112  6918  6918 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-26 10:52:39.116  6918  6918 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-26 10:52:39.130  1036  1784 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6937 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-26 10:52:39.130  3827  3827 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-26 10:52:39.130  3827  3827 V BluetoothSapService: state: 13
08-26 10:52:39.130  3827  3827 V BluetoothSapService: Stopping SAP server process
08-26 10:52:39.131  3827  3827 V BluetoothSapService: Sap Service closeSapService in
08-26 10:52:39.131  3827  3827 V BluetoothSapService: Close listen Socket : 
08-26 10:52:39.131  3827  3827 V BluetoothSapService: Close rfcomm Socket : 
08-26 10:52:39.131  3827  3827 V BluetoothSapService: Close sapd  Socket : 
08-26 10:52:39.133  3827  3827 V BluetoothSapService: Sap Service closeSapService out
08-26 10:52:39.133  3827  3827 V BluetoothSapService: Sap Service onDestroy
08-26 10:52:39.133  3827  3827 V BluetoothSapService: Sap Service closeSapService in
08-26 10:52:39.133  3827  3827 V BluetoothSapService: Close listen Socket : 
08-26 10:52:39.133  3827  3827 V BluetoothSapService: Close rfcomm Socket : 
08-26 10:52:39.133  3827  3827 V BluetoothSapService: Close sapd  Socket : 
08-26 10:52:39.134  3827  3827 V BluetoothSapService: Sap Service closeSapService out
08-26 10:52:39.141  6918  6918 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-26 10:52:39.143  6918  6918 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 10:52:39.156  6918  6918 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-26 10:52:39.158  6501  6501 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 10:52:39.160  6918  6918 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-26 10:52:39.161  6872  6872 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-26 10:52:39.161  6872  6872 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-26 10:52:39.161  6872  6872 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-26 10:52:39.164  6844  6844 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-26 10:52:39.166  6918  6918 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
,08-26 10:52:39.173  6844  6844 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 10:52:39.180  6918  6918 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 10:52:39.180  6918  6918 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-26 10:52:39.181  6918  6918 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-26 10:52:39.187  6501  6501 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 10:52:39.190  6937  6937 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-26 10:52:39.190  6872  6872 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-26 10:52:39.190  6872  6872 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-26 10:52:39.190  6872  6872 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-26 10:52:39.193  6844  6844 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 10:52:39.200  6844  6844 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 10:52:39.206  6918  6918 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 10:52:39.206  6918  6918 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-26 10:52:39.208  1036  1942 I ActivityManager: Killing 6547:com.google.android.partnersetup/u0a8 (adj 15): empty #17
08-26 10:52:39.251  1036  1889 W libprocessgroup: failed to open /acct/uid_10008/pid_6547/cgroup.procs: No such file or directory
,08-26 10:52:39.258  6918  6918 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-26 10:52:39.324  1036  1052 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6957 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-26 10:52:39.357  6080  6080 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.
,08-26 10:52:39.361  1036  1784 I ActivityManager: Killing 6009:com.lge.appbox.client/u0a11 (adj 15): empty #17
,08-26 10:52:39.456  1036  1737 W libprocessgroup: failed to open /acct/uid_10011/pid_6009/cgroup.procs: No such file or directory
,08-26 10:52:39.479  3827  3918 D bt_hci_bdroid: cleanup
,08-26 10:52:39.479  3827  4002 I bt_lpm  : LPM is already off!!!
08-26 10:52:39.479  3827  4135 I bt_userial_mct: exiting userial_read_thread
08-26 10:52:39.479  3827  4135 D bt_userial_mct: Leaving userial_evt_read_thread()
08-26 10:52:39.479  3827  3918 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-26 10:52:39.480  3827  4002 I bt_vendor: hw_epilog_process
08-26 10:52:39.480  3827  3992 W bt-btif : ag scb idx 1 not allocated
08-26 10:52:39.480  3827  3992 E bt-btif : BTA AG is already disabled, ignoring ...
08-26 10:52:39.480  3827  3992 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-26 10:52:39.480  3827  3992 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 10:52:39.480  3827  3992 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-26 10:52:39.480  3827  3992 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 10:52:39.480  3827  3992 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-26 10:52:39.480  3827  3992 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 10:52:39.480  3827  3992 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-26 10:52:39.480  3827  3992 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 10:52:39.480  3827  3992 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-26 10:52:39.480  3827  3992 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 10:52:39.480  3827  3992 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-26 10:52:39.480  3827  3992 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 10:52:39.480  3827  3992 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-26 10:52:39.480  3827  3992 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 10:52:39.480  3827  3992 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-26 10:52:39.480  3827  3992 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 10:52:39.480  3827  3992 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-26 10:52:39.480  3827  3992 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 10:52:39.481  3827  3992 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-26 10:52:39.481  3827  3918 D bt_hci_bdroid: cleanup Finalizing cleanup
08-26 10:52:39.481  3827  3918 D bt_userial_mct: userial_close
08-26 10:52:39.481  3827  3918 E bt_userial_mct: pthread_join() FAILED result:3
08-26 10:52:39.481  3827  3918 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-26 10:52:39.519  6872  6872 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-26 10:52:39.528  6844  6844 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-26 10:52:39.537  6844  6844 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 10:52:39.538  3827  3918 D bt_hci_bdroid: set_power 0
08-26 10:52:39.538  3827  3918 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-26 10:52:39.538  3827  3918 I bt_vendor: bluetooth satus is on
08-26 10:52:39.538  3827  3918 I bt_vendor: bt-vendor : resetting BT status
08-26 10:52:39.538  3827  3918 I bt_vendor: Starting hciattach daemon
08-26 10:52:39.538  3827  3918 I bt_vendor: try to set false
08-26 10:52:39.539  3827  3918 I bt_vendor: Starting hciattach daemon
08-26 10:52:39.539  3827  3918 I bt_vendor: try to set false
08-26 10:52:39.539  3827  3918 I bt_vendor: cleanup
08-26 10:52:39.540  3827  3992 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-26 10:52:39.540  3827  3918 I GKI_LINUX: GKI_exit_task 0 done
08-26 10:52:39.540  3827  3918 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-26 10:52:39.541  3827  3911 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-26 10:52:39.546  3827  3827 D HeadsetService: Received stop request...Stopping profile...
,08-26 10:52:39.549  3827  3827 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-26 10:52:39.549  3827  3827 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-26 10:52:39.549  3827  3827 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2bb6c04a
08-26 10:52:39.551  1036  1036 D BluetoothHeadset: Proxy object disconnected
08-26 10:52:39.551  1036  1036 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-26 10:52:39.552  1854  1854 D BluetoothHeadset: Proxy object disconnected
08-26 10:52:39.552  1854  1854 D BluetoothHeadset: Proxy object disconnected
08-26 10:52:39.553  3827  3827 D A2dpService: Received stop request...Stopping profile...
08-26 10:52:39.553  1854  1854 D BluetoothHeadset: Proxy object disconnected
08-26 10:52:39.553  3827  3946 D HeadsetStateMachine: Exit Disconnected: -1
08-26 10:52:39.554  3827  3977 D A2dpStateMachine: Exit Disconnected: -1
08-26 10:52:39.555  3827  3827 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-26 10:52:39.558  3827  3827 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-26 10:52:39.558  3827  3827 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-26 10:52:39.558  3827  3827 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2bb6c04a
,08-26 10:52:39.562  3827  3911 D BluetoothAdapterState: Stopping profile services that were post enabled
08-26 10:52:39.563  1036  1036 D BluetoothA2dp: Proxy object disconnected
08-26 10:52:39.563  1036  1036 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-26 10:52:39.563  3827  3827 D HidService: Received stop request...Stopping profile...
08-26 10:52:39.563  3827  3827 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2bb6c04a
08-26 10:52:39.565  3827  3827 D HeadsetStateMachine: Unbinding service...
08-26 10:52:39.566  6844  6844 D BluetoothInputDevice: Proxy object disconnected
08-26 10:52:39.566  6844  6844 D HidProfile: Bluetooth service disconnected
08-26 10:52:39.566  3827  3827 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-26 10:52:39.566  3827  3827 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-26 10:52:39.566  3827  3827 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-26 10:52:39.566  3827  3827 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-26 10:52:39.566  3827  3827 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-26 10:52:39.566  3827  3827 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-26 10:52:39.566  3827  3827 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-26 10:52:39.568  3827  3827 D HealthService: Received stop request...Stopping profile...
08-26 10:52:39.568  3827  3827 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2bb6c04a
08-26 10:52:39.569  3827  3827 D PanService: Received stop request...Stopping profile...
08-26 10:52:39.573  3827  3827 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2bb6c04a
,08-26 10:52:39.575  3827  3827 D BtGatt.DebugUtils: handleDebugAction() action=null
08-26 10:52:39.575  3827  3827 D BtGatt.GattService: Received stop request...Stopping profile...
08-26 10:52:39.575  3827  3827 D BtGatt.GattService: stop()
,08-26 10:52:39.575  3827  3827 D BtGatt.AdvertiseManager: advertise clients cleared
08-26 10:52:39.577  6844  6844 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-26 10:52:39.577  6844  6844 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-26 10:52:39.577  6844  6844 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-26 10:52:39.577  6844  6844 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-26 10:52:39.578  6957  6981 W FormManager: Network not available. Please check & try again.
08-26 10:52:39.578  6844  6844 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-26 10:52:39.578  3827  3827 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2bb6c04a
08-26 10:52:39.579  3827  3827 D BluetoothMapService: Received stop request...Stopping profile...
08-26 10:52:39.579  3827  3827 D BluetoothMapService: stop()
08-26 10:52:39.580  3827  3827 D BluetoothMapEmailAppObserver: deinitObservers()
08-26 10:52:39.580  3827  3827 D BluetoothMapEmailAppObserver: removeReceiver()
08-26 10:52:39.580  3827  3827 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2bb6c04a
08-26 10:52:39.581  3827  3827 I BluetoothA2dpServiceJni: cleanupNative
08-26 10:52:39.582  3827  3978 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-26 10:52:39.582  3827  3827 I GKI_LINUX: GKI_exit_task 2 done
08-26 10:52:39.582  3827  3827 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-26 10:52:39.582  3827  3827 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-26 10:52:39.582  3827  3827 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-26 10:52:39.583  3827  3827 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-26 10:52:39.583  3827  3827 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-26 10:52:39.583  3827  3827 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-26 10:52:39.583  3827  3827 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-26 10:52:39.583  3827  3827 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-26 10:52:39.584  3827  3827 V BluetoothMapService: Handler(): got msg=4
08-26 10:52:39.584  3827  3827 D BluetoothMapService: MAP Service closeService in
08-26 10:52:39.584  3827  3827 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-26 10:52:39.585  3827  3827 V BluetoothMapService: MAP Service closeService out
08-26 10:52:39.585  3827  3911 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-26 10:52:39.586  3827  3911 D BluetoothAdapterProperties: Setting state to 10
08-26 10:52:39.586  3827  3911 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-26 10:52:39.586  1036  1112 D BluetoothManagerService: Message: 60
08-26 10:52:39.586  1036  1112 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-26 10:52:39.586  1036  1112 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
08-26 10:52:39.586  3827  3911 I BluetoothAdapterState: Entering OffState
08-26 10:52:39.586  1854  1870 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 10:52:39.587  3827  3827 D BluetoothMapService: cleanup()
08-26 10:52:39.587  3827  3827 D BluetoothMapService: MAP Service closeService in
08-26 10:52:39.587  3827  3827 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-26 10:52:39.587  3827  3827 V BluetoothMapService: MAP Service closeService out
08-26 10:52:39.587  1854  2466 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-26 10:52:39.589  6844  6870 D BluetoothPan: onBluetoothStateChange on: false
08-26 10:52:39.590  1036  1112 D BluetoothA2dp: onBluetoothStateChange: up=false
08-26 10:52:39.590  6844  6871 D BluetoothMap: onBluetoothStateChange: up=false
08-26 10:52:39.591  6844  6870 D BluetoothPbap: onBluetoothStateChange: up=false
08-26 10:52:39.592  1854  1869 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 10:52:39.592  1036  1112 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 10:52:39.592  6844  6871 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-26 10:52:39.593  1036  1112 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-26 10:52:39.594  1036  1112 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-26 10:52:39.596  1036  1112 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-26 10:52:39.596  1036  1112 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-26 10:52:39.596  1036  1112 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@86e2e2 mBinding = false
08-26 10:52:39.597  1036  1112 D BluetoothManagerService: Sending unbind request.
08-26 10:52:39.598  6957  6982 V FormManager: Network unavailable.
08-26 10:52:39.599  1036  1112 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-26 10:52:39.602  1943  1943 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-26 10:52:39.602  1604  1604 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-26 10:52:39.605  1943  2118 D LGBluetoothAPIService: Message: 2
08-26 10:52:39.605  1943  2118 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@394d60c5 mBinding = false
08-26 10:52:39.605  1943  2118 D LGBluetoothAPIService: Sending unbind request.
,08-26 10:52:39.605  3827  3918 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-26 10:52:39.606  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 10:52:39.607  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 10:52:39.608  3827  3827 I GKI_LINUX: GKI_exit_task 1 done
08-26 10:52:39.608  3827  3827 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-26 10:52:39.608  3827  3827 I BluetoothServiceJni: cleanupNative: return from cleanup
08-26 10:52:39.608  3827  3827 I art     : --- WEIRD: removing null entry 246
08-26 10:52:39.608  3827  3827 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
08-26 10:52:39.608  3827  3827 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-26 10:52:39.611  1604  1604 D BluetoothAdapter: 847447842: getState() :  mService = null. Returning STATE_OFF
08-26 10:52:39.611  1604  1604 D BluetoothAdapter: 847447842: getState() :  mService = null. Returning STATE_OFF
08-26 10:52:39.613  6844  6844 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-26 10:52:39.614  6844  6844 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-26 10:52:39.614  6844  6844 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-26 10:52:39.614  6844  6844 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-26 10:52:39.614  6844  6844 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-26 10:52:39.614  6844  6844 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-26 10:52:39.614  3827  3827 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-26 10:52:39.615  6844  6844 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-26 10:52:39.616  6844  6844 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-26 10:52:39.616  6844  6844 D LGBluetoothEventManager: [BTUI] clear device connection state
08-26 10:52:39.618  3827  3827 I art     : System.exit called, status: 0
08-26 10:52:39.618  3827  3827 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-26 10:52:39.619  6844  6844 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-26 10:52:39.633  4298  4298 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-26 10:52:39.633  4298  4298 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-26 10:52:39.635  4298  4298 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-26 10:52:39.637  4298  4298 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 10:52:39.638  6957  6982 V FormManager: Network unavailable.
08-26 10:52:39.642  4298  6992 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-26 10:52:39.644   329  2193 V AudioFlinger: 3827 died, releasing its sessions
08-26 10:52:39.644   329  2193 V AudioFlinger:  pid 1854 @ 0
08-26 10:52:39.644   329  2193 V AudioFlinger:  pid 3460 @ 1
08-26 10:52:39.644   329  2193 V AudioFlinger:  pid 3460 @ 2
08-26 10:52:39.645  6844  6844 D DockEventReceiver: finishStartingService: stopping service
08-26 10:52:39.646  6844  6844 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-26 10:52:39.648  4298  6993 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-26 10:52:39.648  4298  6993 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-26 10:52:39.667  1036  1923 I ActivityManager: Process com.android.bluetooth (pid 3827) has died
08-26 10:52:39.668  1036  1923 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
,08-26 10:52:39.674  2128  2128 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-26 10:52:39.676  6957  6995 W FormManager: Network not available. Please check & try again.
08-26 10:52:39.679  6872  6872 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-26 10:52:39.679  6872  6872 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-26 10:52:39.679  6872  6872 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-26 10:52:39.686  6844  6844 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-26 10:52:39.695  6957  6996 V FormManager: Network unavailable.
08-26 10:52:39.697  6844  6844 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 10:52:39.701  6957  6996 V FormManager: Network unavailable.
08-26 10:52:39.704  6844  6844 D BluetoothPermissionRequest: onReceive
,08-26 10:52:39.708  6844  6844 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-26 10:52:39.709  6844  6844 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-26 10:52:39.713  6844  6844 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-26 10:52:39.792  1036  1923 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=6997 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
08-26 10:52:39.793  1036  1923 I ActivityManager: Killing 6028:com.android.contacts/u0a19 (adj 15): empty #17
,08-26 10:52:39.849  1036  1889 W libprocessgroup: failed to open /acct/uid_10019/pid_6028/cgroup.procs: No such file or directory
,08-26 10:52:39.878  6997  6997 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-26 10:52:39.879  6997  6997 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-26 10:52:39.879  6997  6997 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-26 10:52:39.880  6997  6997 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-26 10:52:39.899  6918  6918 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-26 10:52:39.899  6997  6997 D BluetoothAdapterApp: Loading JNI Library
08-26 10:52:39.900  6918  6918 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
,08-26 10:52:39.901  6918  6918 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
08-26 10:52:39.924  4496  7014 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,08-26 10:52:39.933  6997  6997 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@2da98743 Instance Count = 1
08-26 10:52:39.938  6997  6997 D BluetoothAdapterApp: onCreate
,08-26 10:52:39.960  6997  6997 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-26 10:52:39.960  6997  6997 D ProfileConfigQcom: Adding HeadsetService
08-26 10:52:39.960  6997  6997 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-26 10:52:39.961  6997  6997 D ProfileConfigQcom: Adding A2dpService
08-26 10:52:39.961  6997  6997 D ProfileConfigQcom: [BTUI] HidService is supported
08-26 10:52:39.961  6997  6997 D ProfileConfigQcom: Adding HidService
08-26 10:52:39.961  6997  6997 D ProfileConfigQcom: [BTUI] HealthService is supported
08-26 10:52:39.961  6997  6997 D ProfileConfigQcom: Adding HealthService
08-26 10:52:39.962  6997  6997 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-26 10:52:39.962  6997  6997 D ProfileConfigQcom: [BTUI] PanService is supported
08-26 10:52:39.962  6997  6997 D ProfileConfigQcom: Adding PanService
08-26 10:52:39.963  6997  6997 D ProfileConfigQcom: [BTUI] GattService is supported
08-26 10:52:39.963  6997  6997 D ProfileConfigQcom: Adding GattService
,08-26 10:52:39.963  6997  6997 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-26 10:52:39.963  6997  6997 D ProfileConfigQcom: Adding BluetoothMapService
08-26 10:52:39.963  6997  6997 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-26 10:52:39.965  6997  6997 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-26 10:52:39.968  6844  6844 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-26 10:52:39.969  6997  6997 V LGMDMManagerInternal: Create singleton instance
08-26 10:52:39.973  6918  6918 D LgDataFeature: LgDataFeature() Constructor: none
08-26 10:52:39.973  6918  6918 D LgDataFeature: LgDataFeature() Constructor Done, null
08-26 10:52:39.979  6918  6918 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
08-26 10:52:39.980  6918  6918 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-26 10:52:39.980  6918  6918 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-26 10:52:39.980  6918  6918 V SoundPool: doLoad: loading sample sampleID=1
08-26 10:52:39.980  6918  7026 V SoundPool: Start decode
08-26 10:52:39.980  6918  7026 V MediaPlayer[Native]: decode(31, 10857164, 17813)
08-26 10:52:39.981   329  1399 V MediaPlayerService: decode(23, 10857164, 17813)
08-26 10:52:39.981   329  1399 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-26 10:52:39.981   329  1399 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-26 10:52:39.981   329  1399 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-26 10:52:39.981   329  1399 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-26 10:52:39.981   329  1399 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-26 10:52:39.981   329  1399 V MediaPlayerService: player type = 3
08-26 10:52:39.981   329  1399 V AwesomePlayer: AwesomePlayer create()
08-26 10:52:39.981   329  1399 V AwesomePlayer: reset_l() 
08-26 10:52:39.981   329  1399 V AwesomePlayer: cancelPlayerEvents
08-26 10:52:39.981   329  1399 V AwesomePlayer: setAudioSink() 
08-26 10:52:39.981   329  1399 V AwesomePlayer: reset_l() 
08-26 10:52:39.981   329  1399 V AudioCache: notify(0xb04096c0, 8, 0, 0)
08-26 10:52:39.981   329  1399 V AudioCache: ignored
08-26 10:52:39.981   329  1399 V AwesomePlayer: cancelPlayerEvents
08-26 10:52:39.981   329  1399 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
08-26 10:52:39.981   329  1399 V AwesomePlayer: setDataSource_l dataSource
08-26 10:52:39.981   329  1399 V LGParserOSAL: SniffLGParser start
08-26 10:52:39.981   329  1399 V LGParserOSAL: MainType:5, SubType=0
08-26 10:52:39.981   329  1399 V LGParserOSAL: #### check Mime : application/ogg
08-26 10:52:39.981   329  1399 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-26 10:52:39.981   329  1399 E MediaExtractor: Use LGExtractor :application/ogg 
08-26 10:52:39.998  6918  6918 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
,08-26 10:52:40.005  6804  6804 D UEI.SmartControl: QS Service created
08-26 10:52:40.018  6918  6918 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-26 10:52:40.018  6997  6997 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-26 10:52:40.020  6997  6997 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-26 10:52:40.020  6918  6918 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-26 10:52:40.021  6997  6997 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-26 10:52:40.021  6997  6997 V BluetoothSapReceiver: SapReceiver onReceive 
08-26 10:52:40.021  6997  6997 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 10:52:40.022  6997  6997 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-26 10:52:40.023   329  1399 V LGParserOSAL: supported mime: application/ogg
08-26 10:52:40.023   329  1399 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-26 10:52:40.023   329  1399 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-26 10:52:40.023   329  1399 V AwesomePlayer: mBitrate = -1 bits/sec
08-26 10:52:40.023   329  1399 V AwesomePlayer: AudioTrack Setting
08-26 10:52:40.023   329  1399 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-26 10:52:40.023   329  1399 V AwesomePlayer: setAudioSource() 
08-26 10:52:40.023   329  1399 V MediaPlayerService: prepare
08-26 10:52:40.023   329  1399 V AwesomePlayer: prepareAsync_l() 
08-26 10:52:40.023   329  1399 V MediaPlayerService: wait for prepare
08-26 10:52:40.024   329  7031 V AwesomePlayer: onPrepareAsyncEvent() 
08-26 10:52:40.024   329  7031 V AwesomePlayer: initAudioDecoder() 
08-26 10:52:40.024   329  7031 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-26 10:52:40.024   329  7031 V AudioSystem: isOffloadSupported()
08-26 10:52:40.024   329  7031 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-26 10:52:40.024  6918  6918 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-26 10:52:40.024   329  7031 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-26 10:52:40.024   329  7031 I AudioFlinger: isAudioPlaybackHookOn() false
08-26 10:52:40.024   329  7031 V AwesomePlayer: getUseOffload() = 0 
08-26 10:52:40.024   329  7031 V OMXCodec: OMXCodec::Create
08-26 10:52:40.024   329  7031 V OMXCodec: findMatchingCodecs()
08-26 10:52:40.024   329  7031 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-26 10:52:40.025   329  7031 V OMXCodec: matchingCodecs.size()=1
08-26 10:52:40.025   329  7031 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
08-26 10:52:40.026  6804  6804 I UEI.SmartControl: Service initServices...
08-26 10:52:40.026  6804  6804 D UEI.SmartControl: QS start get config
08-26 10:52:40.028  6937  6937 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
08-26 10:52:40.028   329  7031 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-26 10:52:40.028   329  7031 V LGCodecAdapter: LG Codec Adapter start
08-26 10:52:40.029   329  7031 V OMXCodec: OMXCodec Createtor
08-26 10:52:40.029   329  7031 V OMXCodec: setComponentRole
08-26 10:52:40.029   329  7031 V OMXCodec: configureCodec protected=0
08-26 10:52:40.029   329  7031 V LGCodecAdapter: called getLGCodecSpecificData
08-26 10:52:40.029   329  7031 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-26 10:52:40.029   329  7031 V LGCodecOSAL: Called LGconfigureCodecMETA
08-26 10:52:40.029   329  7031 V LGCodecOSAL: Called LGconfigureCodecMSG
08-26 10:52:40.029   329  7031 V LGCodecOSAL: Not support LGCodec
08-26 10:52:40.029   329  7031 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-26 10:52:40.030   329  7031 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-26 10:52:40.030   329  7031 V OMXCodec: Codec outputs at different samplin,g rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-26 10:52:40.030   329  7031 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-26 10:52:40.030   329  7031 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-26 10:52:40.030   329  7031 V AudioSystem: isOffloadSupported()
08-26 10:52:40.030   329  7031 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-26 10:52:40.030   329  7031 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-26 10:52:40.030   329  7031 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-26 10:52:40.030   329  7031 V OMXCodec: init()
08-26 10:52:40.030   329  7031 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-26 10:52:40.030   329  7031 V OMXCodec: allocateBuffers
08-26 10:52:40.030   329  7031 V OMXCodec: allocateBuffersOnPort portIndex=0
08-26 10:52:40.031   329  7031 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-26 10:52:40.031   329  7031 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7740 on input port
08-26 10:52:40.031   329  7031 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7970 on input port
08-26 10:52:40.031   329  7031 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f79c0 on input port
08-26 10:52:40.031   329  7031 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a60 on input port
08-26 10:52:40.032   329  7031 V OMXCodec: allocateBuffersOnPort portIndex=1
08-26 10:52:40.032   329  7031 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-26 10:52:40.032   329  7031 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on output port
08-26 10:52:40.032   329  7031 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on output port
08-26 10:52:40.032   329  7031 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ba0 on output port
08-26 10:52:40.032   329  7031 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7bf0 on output port
08-26 10:52:40.032   329  7031 V OMXCodec: init() mAsyncCompletion wait!!! 
08-26 10:52:40.033   329  7034 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-26 10:52:40.033   329  7034 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-26 10:52:40.033   329  7034 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-26 10:52:40.033   329  7031 V OMXCodec: init() mAsyncCompletion wait!!! 
08-26 10:52:40.036   329  7034 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-26 10:52:40.036   329  7034 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-26 10:52:40.036   329  7034 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-26 10:52:40.037   329  7031 V OMXCodec: init() mAsyncCompletion wait free! 
08-26 10:52:40.037   329  7031 V AwesomePlayer: finishAsyncPrepare_l() 
08-26 10:52:40.037   329  7031 V AudioCache: notify(0xb04096c0, 5, 0, 0)
08-26 10:52:40.037   329  7031 V AudioCache: ignored
08-26 10:52:40.037   329  7031 V AudioCache: notify(0xb04096c0, 1, 0, 0)
08-26 10:52:40.037   329  7031 V AudioCache: prepared
08-26 10:52:40.037   329  1399 V AudioCache: wait - success
08-26 10:52:40.037   329  1399 V MediaPlayerService: start
08-26 10:52:40.037   329  1399 V AwesomePlayer: play_l() 
08-26 10:52:40.037   329  1399 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-26 10:52:40.037   329  1399 V AwesomePlayer: createAudioPlayer_l
08-26 10:52:40.037   329  1399 V AwesomePlayer: seekAudioIfNecessary_l() 
08-26 10:52:40.038   329  1399 V AwesomePlayer: startAudioPlayer_l() 
08-26 10:52:40.038   329  1399 D AudioPlayer: start of Playback, useOffload 0
08-26 10:52:40.038   329  1399 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-26 10:52:40.038   329  1399 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-26 10:52:40.040   329  7034 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-26 10:52:40.040   329  7034 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-26 10:52:40.040   329  7034 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-26 10:52:40.040   329  7034 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-26 10:52:40.040   329  7034 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-26 10:52:40.041   329  7034 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-26 10:52:40.041   329  7034 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884848
08-26 10:52:40.041   329  7034 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-26 10:52:40.041   329  7034 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885008
08-26 10:52:40.041   329  7034 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-26 10:52:40.041   329  7034 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885088
08-26 10:52:40.041   329  7034 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-26 10:52:40.041   329  7034 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885168
08-26 10:52:40.041   329  7034 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-26 10:52:40.041   329  7034 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-26 10:52:40.041   329  7034 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-26 10:52:40.041   329  7034 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-26 10:52:40.041   329  7034 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-26 10:52:40.041   329  7034 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-26 10:52:40.041   329  7034 V OMXCodec: allocateBuffersOnPort portIndex=1
08-26 10:52:40.041   329  7034 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-26 10:52:40.042   329  7034 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ba0 on output port
08-26 10:52:40.042   329  7034 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on output port
08-26 10:52:40.042   329  7034 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on output port
08-26 10:52:40.042   329  7034 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57db2e0 on output port
08-26 10:52:40.042   329  7034 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-26 10:52:40.042   329  7034 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-26 10:52:40.042   329  1399 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-26 10:52:40.043   329  1399 V AudioCache: notify(0xb04096c0, 6, 0, 0)
08-26 10:52:40.043   329  1399 V AudioCache: ignored
08-26 10:52:40.043   329  1399 V MediaPlayerService: wait for playback complete
08-26 10:52:40.045   329  7037 V AudioCache: write(0xb16df000, 4096)
08-26 10:52:40.045   329  7037 V AudioCache: memcpy(0xaf004000, 0xb16df000, 4096)
08-26 10:52:40.048   329  7037 V AudioCache: write(0xb16df000, 4096)
08-26 10:52:40.048   329  7037 V AudioCache: memcpy(0xaf005000, 0xb16df000, 4096)
08-26 10:52:40.050  6918  6918 V LGMDMManager: Create singleton instance
08-26 10:52:40.050   329  7037 V AudioCache: write(0xb16df000, 4096)
08-26 10:52:40.050   329  7037 V AudioCache: memcpy(0xaf006000, 0xb16df000, 4096)
08-26 10:52:40.051   329  7037 V AudioCache: write(0xb16df000, 4096)
08-26 10:52:40.051   329  7037 V AudioCache: memcpy(0xaf007000, 0xb16df000, 4096)
08-26 10:52:40.051   329  7037 V AudioCache: write(0xb16df000, 4096)
08-26 10:52:40.051   329  7037 V AudioCache: memcpy(0xaf008000, 0xb16df000, 4096)
08-26 10:52:40.051   329  7037 V AudioCache: write(0xb16df000, 4096)
08-26 10:52:40.051   329  7037 V AudioCache: memcpy(0xaf009000, 0xb16df000, 4096)
08-26 10:52:40.051   329  7037 V AudioCache: write(0xb16df000, 4096)
08-26 10:52:40.051   329  7037 V AudioCache: memcpy(0xaf00a000, 0xb16df000, 4096)
08-26 10:52:40.053   329  7037 V AudioCache: write(0xb16df000, 4096)
08-26 10:52:40.053   329  7037 V AudioCache: memcpy(0xaf00b000, 0xb16df000, 4096)
08-26 10:52:40.053   329  7037 V AudioCache: write(0xb16df000, 4096)
08-26 10:52:40.053   329  7037 V AudioCache: memcpy(0xaf00c000, 0xb16df000, 4096)
08-26 10:52:40.053   329  7037 V AudioCache: write(0xb16df000, 4096)
08-26 10:52:40.054   329  7037 V AudioCache: memcpy(0xaf00d000, 0xb16df000, 4096)
08-26 10:52:40.054   329  7037 V AudioCache: write(0xb16df000, 4096)
08-26 10:52:40.054   329  7037 V AudioCache: memcpy(0xaf00e000, 0xb16df000, 4096)
08-26 10:52:40.056   329  7037 V AudioCache: write(0xb16df000, 4096)
08-26 10:52:40.056   329  7037 V AudioCache: memcpy(0xaf00f000, 0xb16df000, 4096)
08-26 10:52:40.056   329  7037 V AudioCache: write(0xb16df000, 4096)
08-26 10:52:40.056   329  7037 V AudioCache: memcpy(0xaf010000, 0xb16df000, 4096)
08-26 10:52:40.056   329  7037 V AudioCache: write(0xb16df000, 4096)
08-26 10:52:40.056   329  7037 V AudioCache: memcpy(0xaf011000, 0xb16df000, 4096)
08-26 10:52:40.056   329  7037 V AudioCache: write(0xb16df000, 4096)
08-26 10:52:40.056   329  7037 V AudioCache: memcpy(0xaf012000, 0xb16df000, 4096)
08-26 10:52:40.057   329  7037 V AudioCache: write(0xb16df000, 4096)
08-26 10:52:40.057   329  7037 V AudioCache: memcpy(0xaf013000, 0xb16df000, 4096)
08-26 10:52:40.057   329  7037 V AudioCache: write(0xb16df000, 4096)
08-26 10:52:40.057   329  7037 V AudioCache: memcpy(0xaf014000, 0xb16df000, 4096)
08-26 10:52:40.058   329  7037 V AudioCache: write(0xb16df000, 4096)
,08-26 10:52:40.058   329  7037 V AudioCache: memcpy(0xaf015000, 0xb16df000, 4096)
08-26 10:52:40.058   329  7037 V AudioCache: write(0xb16df000, 4096)
08-26 10:52:40.059   329  7037 V AudioCache: memcpy(0xaf016000, 0xb16df000, 4096)
08-26 10:52:40.059   329  7037 V AudioCache: write(0xb16df000, 4096)
08-26 10:52:40.059   329  7037 V AudioCache: memcpy(0xaf017000, 0xb16df000, 4096)
08-26 10:52:40.060   329  7037 V AudioCache: write(0xb16df000, 4096)
08-26 10:52:40.060   329  7037 V AudioCache: memcpy(0xaf018000, 0xb16df000, 4096)
08-26 10:52:40.061   329  7037 V AudioCache: write(0xb16df000, 4096)
08-26 10:52:40.061   329  7037 V AudioCache: memcpy(0xaf019000, 0xb16df000, 4096)
08-26 10:52:40.061   329  7037 V AudioCache: write(0xb16df000, 4096)
08-26 10:52:40.061   329  7037 V AudioCache: memcpy(0xaf01a000, 0xb16df000, 4096)
08-26 10:52:40.062   329  7037 V AudioCache: write(0xb16df000, 4096)
08-26 10:52:40.062   329  7037 V AudioCache: memcpy(0xaf01b000, 0xb16df000, 4096)
08-26 10:52:40.062   329  7037 V AudioCache: write(0xb16df000, 4096)
08-26 10:52:40.062   329  7037 V AudioCache: memcpy(0xaf01c000, 0xb16df000, 4096)
08-26 10:52:40.063   329  7037 V AudioCache: write(0xb16df000, 4096)
08-26 10:52:40.063   329  7037 V AudioCache: memcpy(0xaf01d000, 0xb16df000, 4096)
08-26 10:52:40.064   329  7037 V AudioCache: write(0xb16df000, 4096)
08-26 10:52:40.064   329  7037 V AudioCache: memcpy(0xaf01e000, 0xb16df000, 4096)
08-26 10:52:40.064   329  7037 V AudioCache: write(0xb16df000, 4096)
08-26 10:52:40.064   329  7037 V AudioCache: memcpy(0xaf01f000, 0xb16df000, 4096)
08-26 10:52:40.066   329  7037 V AudioCache: write(0xb16df000, 4096)
08-26 10:52:40.066   329  7037 V AudioCache: memcpy(0xaf020000, 0xb16df000, 4096)
08-26 10:52:40.067   329  7037 V AudioCache: write(0xb16df000, 4096)
08-26 10:52:40.067   329  7037 V AudioCache: memcpy(0xaf021000, 0xb16df000, 4096)
08-26 10:52:40.068   329  7037 V AudioCache: write(0xb16df000, 4096)
08-26 10:52:40.068   329  7037 V AudioCache: memcpy(0xaf022000, 0xb16df000, 4096)
08-26 10:52:40.068   329  7037 V AudioCache: write(0xb16df000, 4096)
08-26 10:52:40.068   329  7037 V AudioCache: memcpy(0xaf023000, 0xb16df000, 4096)
08-26 10:52:40.069   329  7037 V AudioCache: write(0xb16df000, 4096)
08-26 10:52:40.069   329  7037 V AudioCache: memcpy(0xaf024000, 0xb16df000, 4096)
08-26 10:52:40.070   329  7037 V AudioCache: write(0xb16df000, 4096)
08-26 10:52:40.070   329  7037 V AudioCache: memcpy(0xaf025000, 0xb16df000, 4096)
08-26 10:52:40.070   329  7037 V AudioCache: write(0xb16df000, 4096)
,08-26 10:52:40.070   329  7037 V AudioCache: memcpy(0xaf026000, 0xb16df000, 4096)
,08-26 10:52:40.071   329  7037 V AudioCache: write(0xb16df000, 4096)
08-26 10:52:40.071   329  7037 V AudioCache: memcpy(0xaf027000, 0xb16df000, 4096)
08-26 10:52:40.072   329  7037 V AudioCache: write(0xb16df000, 4096)
08-26 10:52:40.072   329  7037 V AudioCache: memcpy(0xaf028000, 0xb16df000, 4096)
08-26 10:52:40.072   329  7037 V AudioCache: write(0xb16df000, 4096)
08-26 10:52:40.072   329  7037 V AudioCache: memcpy(0xaf029000, 0xb16df000, 4096)
08-26 10:52:40.073   329  7037 V AudioCache: write(0xb16df000, 4096)
08-26 10:52:40.073   329  7037 V AudioCache: memcpy(0xaf02a000, 0xb16df000, 4096)
08-26 10:52:40.074   329  7037 V AudioCache: write(0xb16df000, 4096)
08-26 10:52:40.074   329  7037 V AudioCache: memcpy(0xaf02b000, 0xb16df000, 4096)
08-26 10:52:40.075   329  7037 V AudioCache: write(0xb16df000, 4096)
08-26 10:52:40.075   329  7037 V AudioCache: memcpy(0xaf02c000, 0xb16df000, 4096)
08-26 10:52:40.075   329  7037 V AudioCache: write(0xb16df000, 4096)
,08-26 10:52:40.075   329  7037 V AudioCache: memcpy(0xaf02d000, 0xb16df000, 4096),
08-26 10:52:40.076   329  7037 V AudioCache: write(0xb16df000, 4096)
08-26 10:52:40.076   329  7037 V AudioCache: memcpy(0xaf02e000, 0xb16df000, 4096)
,08-26 10:52:40.077   329  7037 V AudioCache: write(0xb16df000, 4096)
08-26 10:52:40.077   329  7037 V AudioCache: memcpy(0xaf02f000, 0xb16df000, 4096),
08-26 10:52:40.078   329  7037 V AudioCache: write(0xb16df000, 4096)
08-26 10:52:40.078   329  7037 V AudioCache: memcpy(0xaf030000, 0xb16df000, 4096)
,08-26 10:52:40.079   329  7037 V AudioCache: write(0xb16df000, 4096)
,08-26 10:52:40.079   329  7037 V AudioCache: memcpy(0xaf031000, 0xb16df000, 4096)
08-26 10:52:40.080   329  7037 V AudioCache: write(0xb16df000, 4096)
08-26 10:52:40.080   329  7037 V AudioCache: memcpy(0xaf032000, 0xb16df000, 4096)
,08-26 10:52:40.080   329  7037 V AudioCache: write(0xb16df000, 4096)
08-26 10:52:40.080   329  7037 V AudioCache: memcpy(0xaf033000, 0xb16df000, 4096)
08-26 10:52:40.081   329  7037 V AudioCache: write(0xb16df000, 4096)
08-26 10:52:40.081   329  7037 V AudioCache: memcpy(0xaf034000, 0xb16df000, 4096)
,08-26 10:52:40.081   329  7037 V AudioCache: write(0xb16df000, 4096)
08-26 10:52:40.081   329  7037 V AudioCache: memcpy(0xaf035000, 0xb16df000, 4096)
08-26 10:52:40.082   329  7034 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-26 10:52:40.082   329  7037 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-26 10:52:40.082   329  7037 V AwesomePlayer: postAudioEOS() 
,08-26 10:52:40.082   329  7037 V AudioCache: write(0xb16df000, 280)
08-26 10:52:40.082   329  7037 V AudioCache: memcpy(0xaf036000, 0xb16df000, 280)
08-26 10:52:40.087   329  7031 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-26 10:52:40.087   329  7031 V AwesomePlayer: onStreamDone
,08-26 10:52:40.087   329  7031 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-26 10:52:40.087   329  7031 V AudioCache: notify(0xb04096c0, 2, 0, 0)
08-26 10:52:40.087   329  7031 V AudioCache: playback complete
08-26 10:52:40.087   329  7031 V AwesomePlayer: pause_l() 
,08-26 10:52:40.087   329  7031 V AudioCache: notify(0xb04096c0, 7, 0, 0)
08-26 10:52:40.087   329  7031 V AudioCache: ignored
08-26 10:52:40.087   329  7031 V AwesomePlayer: cancelPlayerEvents
08-26 10:52:40.087   329  1399 V AudioCache: wait - success
,08-26 10:52:40.087   329  1399 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-26 10:52:40.088   329  7031 D AudioPlayer: Pause Playback at 1068125
08-26 10:52:40.088   329  1399 V AwesomePlayer: reset_l() 
08-26 10:52:40.088   329  1399 V AudioCache: notify(0xb04096c0, 8, 0, 0)
,08-26 10:52:40.088   329  1399 V AudioCache: ignored
08-26 10:52:40.088   329  1399 V AwesomePlayer: cancelPlayerEvents
08-26 10:52:40.088   329  1399 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
,08-26 10:52:40.088   329  1399 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-26 10:52:40.088   329  1399 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-26 10:52:40.088   329  1399 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-26 10:52:40.088   329  1399 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
,08-26 10:52:40.088  6918  6918 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-26 10:52:40.088   329  7034 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-26 10:52:40.088   329  7034 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-26 10:52:40.088   329  7034 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
,08-26 10:52:40.088   329  7034 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a60 on port 0
08-26 10:52:40.088   329  7034 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-26 10:52:40.088   329  7034 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f79c0 on port 0
,08-26 10:52:40.088   329  7034 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-26 10:52:40.089   329  7034 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7970 on port 0
08-26 10:52:40.089   329  7034 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-26 10:52:40.089   329  7034 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7740 on port 0
,08-26 10:52:40.089   329  7034 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-26 10:52:40.089  6918  6918 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
08-26 10:52:40.089   329  7034 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-26 10:52:40.089   329  7034 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb57db2e0 on port 1
,08-26 10:52:40.089   329  7034 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-26 10:52:40.089   329  7034 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ab0 on port 1
08-26 10:52:40.089   329  7034 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-26 10:52:40.089   329  7034 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b50 on port 1
,08-26 10:52:40.089   329  7034 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-26 10:52:40.089   329  7034 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ba0 on port 1
08-26 10:52:40.089   329  7034 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-26 10:52:40.089   329  7034 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
,08-26 10:52:40.089   329  7034 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-26 10:52:40.089   329  7034 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-26 10:52:40.089   329  7034 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-26 10:52:40.089   329  1399 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
,08-26 10:52:40.089   329  1399 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-26 10:52:40.089   329  1399 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-26 10:52:40.090  6918  6918 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:5121
08-26 10:52:40.090   329  1399 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
,08-26 10:52:40.090   329  1399 D AudioPlayer: AudioPlayer releasing audio source
08-26 10:52:40.090   329  1399 D AudioPlayer: AudioPlayer done releasing audio source
08-26 10:52:40.090   329  1399 V AwesomePlayer: reset_l() 
08-26 10:52:40.090   329  1399 V AwesomePlayer: cancelPlayerEvents
,08-26 10:52:40.090   329  1399 V AwesomePlayer: ~AwesomePlayer call
08-26 10:52:40.091   329  1399 V AwesomePlayer: reset_l() 
08-26 10:52:40.091   329  1399 V AwesomePlayer: cancelPlayerEvents
,08-26 10:52:40.092  6918  7026 V SoundPool: close(31)
08-26 10:52:40.092  6918  7026 V SoundPool: pointer = 0x9ffeb000, size = 205080, sampleRate = 48000, numChannels = 2
08-26 10:52:40.468  6804  6804 I UEI.SmartControl: Supports setup maps: true
08-26 10:52:40.474  6804  6804 D UEI.SmartControl: QS start statue = true Error code = 0
,08-26 10:52:40.474  6804  6804 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-26 10:52:40.474  6804  6804 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-26 10:52:40.474  6804  6804 I UEI.SmartControl: ### init IR Blaster...
,08-26 10:52:40.479  6804  6804 D serial_port: Configuring serial port,
08-26 10:52:40.480  6804  6804 E UEI.SmartControl: UEIBLaster setting for 616
08-26 10:52:40.480  6804  6804 I UEI.SmartControl: Setting serial record hearder size = 2
08-26 10:52:40.480  6804  6804 I UEI.SmartControl: configuring settings for MAXQ616
08-26 10:52:40.480  6804  6804 I UEI.SmartControl: Get version...
08-26 10:52:40.498  6804  7045 D UEI.SmartControl: serial port data available: 21
,08-26 10:52:40.526  6804  6804 D UEI.SmartControl: MAXQ616 A2-X4 software.
,08-26 10:52:40.526  6804  6804 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-26 10:52:40.526  6804  6804 I UEI.SmartControl: QS saving settings...
08-26 10:52:40.527  6804  6804 D UEI.SmartControl: IR Blaster version: 25672567
,08-26 10:52:40.543  6804  7045 D UEI.SmartControl: serial port data available: 4
,08-26 10:52:40.576  6804  7048 I UEI.SmartControl: Device manager: loading config....
,08-26 10:52:40.577  6804  7048 D UEI.SmartControl: ----------- loading internal config...
,08-26 10:52:40.578  6804  6804 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-26 10:52:40.587  6804  6804 E UEI.SmartControl: Services init done
08-26 10:52:40.587  6804  6804 D UEI.SmartControl: QS Service init finished
08-26 10:52:40.602  6804  6804 D UEI.SmartControl: QS Service version name: 2.1.91
08-26 10:52:40.602  6804  6804 D UEI.SmartControl: QS Service version code: 201091
08-26 10:52:40.603  6804  6804 D UEI.SmartControl: Service requested: Control
08-26 10:52:40.606  6804  7048 E UEI.SmartControl: Loading SETTINGS...
08-26 10:52:40.608  6804  6804 D UEI.SmartControl: Request IControl service: devices are loaded...
08-26 10:52:40.611  6918  6918 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
,08-26 10:52:40.614  6804  6820 I UEI.SmartControl: ------ IControl API: 11
08-26 10:52:40.614  6804  6820 D UEI.SmartControl: File observer start...
08-26 10:52:40.615  6804  6820 E UEI.SmartControl: IR Port is disabled: false
08-26 10:52:40.615  6804  6820 D UEI.SmartControl: Starting file observer...
08-26 10:52:40.616  6804  6820 I UEI.SmartControl: Registering callback...
08-26 10:52:40.617  6804  6804 D UEI.SmartControl: Internal service binding...
08-26 10:52:40.617  6804  6819 I UEI.SmartControl: ------ IControl API: 19
08-26 10:52:40.618  6804  6819 I UEI.SmartControl: Registering Services Ready callback...
08-26 10:52:40.620  6804  7048 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-26 10:52:40.642  6804  7047 I UEI.SmartControl: Notify AllClients services are ready: 0
,08-26 10:52:40.645  6918  6933 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-26 10:52:40.646  6918  7024 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-26 10:52:40.646  6918  7024 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-26 10:52:40.646  6918  6918 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-26 10:52:40.647  6918  6918 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-26 10:52:40.647  6804  6820 I UEI.SmartControl: ------ IControl API: 8
08-26 10:52:40.648  6804  7047 D UEI.SmartControl: -----service ready thread exits
08-26 10:52:40.649  6918  6918 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-26 10:52:40.650  6918  6918 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-26 10:52:40.650  6918  6918 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-26 10:52:40.651  6918  6918 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-26 10:52:40.652  6918  6918 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-26 10:52:40.652  6918  6918 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-26 10:52:40.655  6918  6918 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
,08-26 10:52:40.661  6918  6918 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-26 10:52:40.661  6918  6918 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-26 10:52:40.662  6918  6918 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-26 10:52:40.662  6918  6918 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-26 10:52:40.663  6918  6918 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-26 10:52:40.664  6918  6918 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-26 10:52:40.665  6918  6918 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-26 10:52:40.666  6918  6918 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1472201560665]
08-26 10:52:40.670  6918  6918 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
,08-26 10:52:40.675  1036  1052 I ActivityManager: Killing 6056:com.android.gallery3d/u0a27 (adj 15): empty #17
08-26 10:52:40.712  6918  7053 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-26 10:52:40.716  1036  1052 I ActivityManager: Killing 6592:com.lge.email/u0a23 (adj 15): empty #18
08-26 10:52:40.748  1036  1978 W libprocessgroup: failed to open /acct/uid_10027/pid_6056/cgroup.procs: No such file or directory
,08-26 10:52:40.754  1036  1053 W libprocessgroup: failed to open /acct/uid_10023/pid_6592/cgroup.procs: No such file or directory
08-26 10:52:40.760  6918  6918 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
08-26 10:52:40.761  6918  6918 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-26 10:52:40.761  6918  6918 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-26 10:52:40.762  6918  6918 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-26 10:52:40.762  6918  6918 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-26 10:52:40.762  6918  6918 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-26 10:52:40.763  6918  6918 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
,08-26 10:52:40.774  6918  6918 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,08-26 10:52:41.422  1036  1736 D WifiServiceImplEx: setWifiEnabled: true pid=6692, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,08-26 10:52:41.424  1036  1736 D WifiService: setWifiEnabled: true pid=6692, uid=10118
08-26 10:52:41.424  1036  1736 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-26 10:52:41.447  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-26 10:52:41.448  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-26 10:52:41.448  1036  1036 D Ulp_jni : JNI:system_update. Event-4
,08-26 10:52:41.451  1036  1440 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-26 10:52:41.451  1036  1440 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-26 10:52:41.454  1036  1440 E WifiUtil: wfc_util_ffile_check_copy(): pid[1036] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-26 10:52:41.454  1036  1440 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-26 10:52:41.454  1036  1440 E WifiUtil: wfc_util_ffile_check_copy(): pid[1036] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-26 10:52:41.454  1036  1440 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-26 10:52:41.454  1036  1440 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-26 10:52:41.455  1036  1440 E WifiHW  : unknown target_country: EU , set to default
08-26 10:52:41.455  1036  1440 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-26 10:52:41.455  1036  1440 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-26 10:52:41.455  1036  1440 I WifiUtil: gEnableBmps=1
08-26 10:52:41.486  1036  1495 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-26 10:52:41.494  1036  1112 D Tethering: MasterInitialState.processMessage what=3
08-26 10:52:41.504  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 10:52:41.507  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 10:52:41.508  1036  1495 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-26 10:52:41.513  1036  1095 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-26 10:52:41.514  1036  1112 D Tethering: MasterInitialState.processMessage what=3
08-26 10:52:41.523  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 10:52:41.527  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 10:52:41.529  6501  6501 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-26 10:52:41.531  6501  6530 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-26 10:52:41.543  5758  5758 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-26 10:52:41.551  5758  5758 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-26 10:52:41.568  2128  2128 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-26 10:52:41.633  1036  1095 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-26 10:52:41.652  1036  1923 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7067 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
08-26 10:52:41.654  1036  1095 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 10:52:41.655  1036  1095 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-26 10:52:41.724  7067  7067 I AppUp4:AppBoxCP: onCreate
,08-26 10:52:41.725  7067  7067 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
08-26 10:52:41.736  7067  7067 I AppUp4:DB:  setFingerPrint start
08-26 10:52:41.736  7067  7067 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
08-26 10:52:41.745  7067  7067 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
,08-26 10:52:41.745  7067  7067 I AppUp4:DB:  SDK version = 21
,08-26 10:52:41.745  7067  7067 I AppUp4:DB:  beforefinger == newfinger no write in DB
08-26 10:52:41.747  7067  7067 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
08-26 10:52:41.749  7067  7067 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-26 10:52:41.749  7067  7067 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-26 10:52:41.751  7067  7067 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-26 10:52:41.752  7067  7067 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-26 10:52:41.760  7067  7067 I AppUp4:CustModeStarterReceiver: onReceive
,08-26 10:52:41.813  7067  7067 D LgDataFeature: LgDataFeature() Constructor: none
,08-26 10:52:41.813  7067  7067 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-26 10:52:41.823  7067  7067 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@3f8f71b5
,08-26 10:52:41.823  7067  7067 D AppUp4:CustFacade: isCustomizationCompleted : false
08-26 10:52:41.823  7067  7067 D AppUp4:CustFacade: isPhone : true
,08-26 10:52:41.824  7067  7067 D AppUp4:CustModeStarterReceiver: begin check event
08-26 10:52:41.824  7067  7067 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
08-26 10:52:41.824  7067  7067 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
,08-26 10:52:41.825  7067  7089 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
08-26 10:52:41.826  7067  7089 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
08-26 10:52:41.826  7067  7089 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
,08-26 10:52:41.829  1036  2033 I ActivityManager: Killing 6639:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,08-26 10:52:41.930  1036  1737 W libprocessgroup: failed to open /acct/uid_10061/pid_6639/cgroup.procs: No such file or directory
,08-26 10:52:41.936  4298  4298 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-26 10:52:41.937  4298  4298 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-26 10:52:41.940  4298  4298 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 10:52:41.943  4298  4298 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 10:52:41.948  4298  7094 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-26 10:52:41.960  4298  7095 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-26 10:52:41.961  4298  7095 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-26 10:52:42.001  1036  1736 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7102 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-26 10:52:42.071  7102  7102 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-26 10:52:42.072  7102  7102 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-26 10:52:42.074  7102  7102 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-26 10:52:42.074  7102  7102 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-26 10:52:42.128   324   895 D SoftapController: Softap fwReload - Ok
,08-26 10:52:42.131  1036  1440 E NetdConnector: NDC Command {53 softap fwreload wlan0 STA} took too long (671ms)
08-26 10:52:42.134   324   895 D CommandListener: Setting iface cfg
08-26 10:52:42.134   324   895 D CommandListener: Trying to bring down wlan0
08-26 10:52:42.135   324   895 D CommandListener: Clearing all IP addresses on wlan0
08-26 10:52:42.141  1036  1112 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-26 10:52:42.148  1036  1440 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
08-26 10:52:42.150  1036  1440 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-26 10:52:42.150  1036  1440 E WifiStateMachine: useWiFiOffloading() : false
08-26 10:52:42.150  1036  1440 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-26 10:52:42.143  7120  7120 W wpa_supplicant: type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 10:52:42.143  7120  7120 W wpa_supplicant: type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 10:52:42.168  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-26 10:52:42.176  7120  7120 I wpa_supplicant: Successfully initialized wpa_supplicant
08-26 10:52:42.177  1036  1440 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-26 10:52:42.177  1036  1440 D WifiMonitor: connecting to supplicant
,08-26 10:52:42.183  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-26 10:52:42.183  1943  1943 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-26 10:52:42.183  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 10:52:42.184  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 10:52:42.211  7102  7102 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-26 10:52:42.212  7120  7120 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-26 10:52:42.212  7120  7120 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
08-26 10:52:42.214  1036  1112 D Tethering: InitialState.processMessage what=4
08-26 10:52:42.215  1036  1112 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-26 10:52:42.226  7102  7102 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,08-26 10:52:42.270  7102  7102 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-26 10:52:42.307  7102  7102 D LgDataFeature: LgDataFeature() Constructor: none
,08-26 10:52:42.307  7102  7102 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-26 10:52:42.322  7120  7120 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-26 10:52:42.366  7120  7120 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-26 10:52:42.383  1036  1440 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
,08-26 10:52:42.384  1036  1440 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-26 10:52:42.385  7120  7120 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
08-26 10:52:42.386  7120  7120 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-26 10:52:42.386  1036  1440 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-26 10:52:42.386  1036  7131 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
08-26 10:52:42.386  1036  7131 D WifiMonitor: Dropping event because (p2p0) is stopped
08-26 10:52:42.386  1036  7131 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-26 10:52:42.386  1036  7131 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-26 10:52:42.387  1036  7131 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-26 10:52:42.387  1036  7131 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-26 10:52:42.387  1036  1440 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-26 10:52:42.388  1036  1440 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-26 10:52:42.388  1036  1440 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-26 10:52:42.389  1036  1440 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-26 10:52:42.389  1036  1440 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-26 10:52:42.390  1036  1440 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-26 10:52:42.390  1036  1440 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-26 10:52:42.391  1036  1440 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-26 10:52:42.391  1036  1440 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-26 10:52:42.391  1036  1440 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-26 10:52:42.392  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 10:52:42.392  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 10:52:42.392  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 10:52:42.392  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 10:52:42.392  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-26 10:52:42.393  1036  1440 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-26 10:52:42.393  1036  1440 E WifiStateMachine: useWiFiOffloading() : false
08-26 10:52:42.393  1036  1440 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-26 10:52:42.395  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-26 10:52:42.398  1943  1943 D WfdService: Waiting for WifiP2p enabling
08-26 10:52:42.398  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-26 10:52:42.399  1036  1468 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-26 10:52:42.399  6692  6692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 10:52:42.399  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 10:52:42.399  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 10:52:42.399  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 10:52:42.399  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 10:52:42.399  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 10:52:42.399  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 10:52:42.399  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 10:52:42.399  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 10:52:42.400  6692  6692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 10:52:42.400  6692  6692 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-26 10:52:42.400  6692  6692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 10:52:42.400  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 10:52:42.400  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 10:52:42.400  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 10:52:42.400  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 10:52:42.400  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 10:52:42.400  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 10:52:42.400  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 10:52:42.400  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 10:52:42.401  6692  6692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 10:52:42.401  6692  6692 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-26 10:52:42.399  1036  1440 D WifiNative-wlan0: doBoolean: SET update_config 1
08-26 10:52:42.401  1036  1440 D WifiNative-wlan0: SET update_config 1: returned true
08-26 10:52:42.401  1036  1440 D WifiConfigStore: Loading config and enabling all networks 
08-26 10:52:42.401  1036  1440 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-26 10:52:42.402  1036  1440 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-26 10:52:42.409  1036  1440 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
,08-26 10:52:42.418  1036  1440 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-26 10:52:42.418  1036  1440 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-26 10:52:42.420  1036  1440 D WifiStateMachine: enableVerboseLogging : level 2
08-26 10:52:42.420  1036  1440 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
,08-26 10:52:42.420  1036  1440 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-26 10:52:42.420  1036  1440 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-26 10:52:42.421  1036  1440 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-26 10:52:42.421  1036  1440 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-26 10:52:42.421  1036  1440 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-26 10:52:42.421  1036  1440 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-26 10:52:42.422  1036  1440 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-26 10:52:42.422  1036  1440 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-26 10:52:42.422  1036  1440 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-26 10:52:42.422  1036  1440 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-26 10:52:42.423  1036  1440 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-26 10:52:42.423  1036  1440 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-26 10:52:42.423  1036  1440 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
,08-26 10:52:42.424  1036  1440 D WifiStateMachine: Setting OUI to DA-A1-19
08-26 10:52:42.424  1036  1440 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-26 10:52:42.425  1036  1440 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-26 10:52:42.425  1036  1440 D WifiNative-HAL: Setting external_sim to 1
08-26 10:52:42.425  1036  1440 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-26 10:52:42.425  1943  1943 D WfdsService: Supplicant Connection state is changed : true
08-26 10:52:42.425  1943  2260 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-26 10:52:42.425  1943  2260 D WfdsService: Set the WFDS Monitor: true
08-26 10:52:42.425  1943  2260 D WfdsMonitor: WfdsMonitorThread create
08-26 10:52:42.425  1036  1440 D WifiNative-wlan0: SET external_sim 1: returned true
08-26 10:52:42.426  1036  1440 I WifiNative-HAL: startHal
08-26 10:52:42.426  1036  1440 D wifi    : setting scan oui 0xaf707080
08-26 10:52:42.426  1943  2260 D WfdsMonitor: WFDS Monitor is created and started
08-26 10:52:42.426  1943  2260 D WfdsService: WiFi: Supplicant connection re-established
08-26 10:52:42.426  1036  1440 D WifiStateMachine: Setting OUI to DA-A1-19
08-26 10:52:42.426  1036  1440 I WifiNative-HAL: startHal
08-26 10:52:42.426  1036  1440 D wifi    : setting scan oui 0xaf707080
08-26 10:52:42.426  1036  1440 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-26 10:52:42.427  1036  1440 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-26 10:52:42.427  1036  1440 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-26 10:52:42.428  7120  7120 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-26 10:52:42.428  1036  1440 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-26 10:52:42.428  1036  1440 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-26 10:52:42.428  7120  7120 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-26 10:52:42.428  1943  7132 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-26 10:52:42.429  1036  1440 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-26 10:52:42.429  1943  7132 E CtrlSupplicant: Succeed to open control connection
08-26 10:52:42.429  1036  1440 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-26 10:52:42.429  1943  7132 E CtrlSupplicant: Succeed to open monitor connection
08-26 10:52:42.429  7120  7120 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-26 10:52:42.429  1943  7132 D WfdsMonitor: Supplicant connection established
08-26 10:52:42.430  1943  2260 D WfdsService: Connected to the supplicant for wfds
08-26 10:52:42.430  1036  1440 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-26 10:52:42.430  1036  1440 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-26 10:52:42.430  7120  7120 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-26 10:52:42.430  1036  1440 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-26 10:52:42.430  1036  1440 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-26 10:52:42.431  7120  7120 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-26 10:52:42.431  1036  1440 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-26 10:52:42.431  1036  1440 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-26 10:52:42.431  7120  7120 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-26 10:52:42.432  1036  1440 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-26 10:52:42.432  1036  1440 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-26 10:52:42.432  7120  7120 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-26 10:52:42.432  1036  1440 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-26 10:52:42.433  1036  1440 E WifiNative: : [121,673,062 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-26 10:52:42.433  1036  1440 D WifiNative-wlan0: doBoolean: RECONNECT
08-26 10:52:42.434  1036  1440 D W,ifiNative-wlan0: RECONNECT: returned true
08-26 10:52:42.434  1036  1440 D WifiNative-wlan0: doString: [STATUS]
08-26 10:52:42.434  1036  7131 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-26 10:52:42.434  1036  7131 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-26 10:52:42.434  1036  1440 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-26 10:52:42.434  1036  1440 D WifiNative-wlan0: doBoolean: SET ps 1
08-26 10:52:42.435  1036  1440 D WifiNative-wlan0: SET ps 1: returned true
08-26 10:52:42.435  1036  1393 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
,08-26 10:52:42.436  1036  1440 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-26 10:52:42.436  1036  1036 D WifiScanningService: SCAN_AVAILABLE : 3
08-26 10:52:42.436  1036  1036 D RttService: SCAN_AVAILABLE : 3
08-26 10:52:42.436  1036  1440 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
,08-26 10:52:42.436  1036  1558 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-26 10:52:42.437  1036  1558 I WifiNative-HAL: startHal
08-26 10:52:42.437  1036  1558 D wifi    : getting scan capabilities on interface[1] = 0xaf707080
08-26 10:52:42.437  1036  1558 D wifi    : failed to get capabilities : -3
08-26 10:52:42.437  1036  1440 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-26 10:52:42.437  1036  1558 E WifiScanningService: could not get scan capabilities
08-26 10:52:42.437   324   895 D CommandListener: Setting iface cfg
08-26 10:52:42.437   324   895 D CommandListener: Trying to bring up p2p0
08-26 10:52:42.437  1036  1559 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-26 10:52:42.437  1036  1440 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-26 10:52:42.438  1036  1440 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-26 10:52:42.438  1036  1393 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-26 10:52:42.438  1036  1440 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-26 10:52:42.438  1036  1393 D LGWifiP2pService: P2pEnablingState
08-26 10:52:42.438  1036  1393 D LGWifiP2pService: P2pEnablingState{ when=-1ms what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-26 10:52:42.438  1036  1393 D LGWifiP2pService: P2p socket connection successful
08-26 10:52:42.438  1036  1393 D LGWifiP2pService: P2pEnabledState
08-26 10:52:42.439  1036  1440 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-26 10:52:42.439  1036  1440 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-26 10:52:42.439  7120  7120 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-26 10:52:42.440  1036  1440 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-26 10:52:42.440  1036  1440 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-26 10:52:42.440  1036  1440 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-26 10:52:42.440  1036  1440 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-26 10:52:42.440  7120  7120 E wpa_supplicant: disconnect_rssi_lvl: -100
08-26 10:52:42.441  1036  1440 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
08-26 10:52:42.442  1036  1393 D LGWifiP2pService: sending p2p connection changed broadcast
08-26 10:52:42.442  1036  1440 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
08-26 10:52:42.443  1036  1440 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
08-26 10:52:42.443  1036  1440 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-26 10:52:42.443  1036  1393 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-26 10:52:42.443  7120  7120 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-26 10:52:42.444  7120  7120 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 10:52:42.444  1036  7131 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-26 10:52:42.444  1036  7131 E WifiMonitor: WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 10:52:42.444  1036  7131 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 10:52:42.444  1036  7131 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 10:52:42.445  7120  7120 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-26 10:52:42.445  7120  7120 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 10:52:42.445  1943  7132 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 10:52:42.445  1036  1440 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
,08-26 10:52:42.445  1036  7131 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 10:52:42.445  1036  7131 E WifiMonitor: WifiMonitor:p2p0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 10:52:42.445  1036  7131 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 10:52:42.445  1036  7131 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 10:52:42.445  7120  7120 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 10:52:42.446  1943  7132 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 10:52:42.446  1036  1393 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-26 10:52:42.446  1036  7131 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 10:52:42.446  1036  7131 E WifiMonitor: WifiMonitor:p2p0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 10:52:42.446  1036  7131 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 10:52:42.446  1036  1393 D WifiNative-p2p0: doBoolean: SET device_name G3
08-26 10:52:42.446  1036  7131 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 10:52:42.446  1036  1393 D WifiNative-p2p0: SET device_name G3: returned true
08-26 10:52:42.446  1036  1393 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-26 10:52:42.446  1036  1393 D LGWifiP2pService: before postfix = G3
08-26 10:52:42.446  1036  1393 D WifiServerServiceExt: postfix byte check : 2
08-26 10:52:42.446  1036  1393 D LGWifiP2pService: after postfix = G3
08-26 10:52:42.446  1036  1393 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-26 10:52:42.447  1036  1440 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-26 10:52:42.447  1036  1440 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-26 10:52:42.448  1036  1393 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-26 10:52:42.448  1036  1393 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-26 10:52:42.448  1036  1393 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-26 10:52:42.448  1036  1393 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-26 10:52:42.448  1036  1440 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-26 10:52:42.448  1036  1440 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-26 10:52:42.448  1943  1943 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-26 10:52:42.448  1036  1393 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-26 10:52:42.448  1036  1393 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-26 10:52:42.449  7120  7120 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-26 10:52:42.449  7120  7120 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-26 10:52:42.449  1036  7131 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-26 10:52:42.449  1036  7131 E WifiMonitor: WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-26 10:52:42.449  1036  7131 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-26 10:52:42.449  1036  7131 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-26 10:52:42.449  1036  1440 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-26 10:52:42.449  1943  1943 D WfdsService: WifiP2pState is changed : true
08-26 10:52:42.450  1036  1440 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-26 10:52:42.450  1036  1393 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-26 10:52:42.450  1036  1393 D WifiNative-HAL: p2pGetDeviceAddress
,08-26 10:52:42.450  1943  1943 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-26 10:52:42.450  1036  1393 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-26 10:52:42.451  1943  2260 D WfdsService: Receive the WFDS_ENABLE Method
08-26 10:52:42.451  1943  2260 D WfdsService: Set the WFDS Monitor: true
08-26 10:52:42.451  1943  2260 D WfdsService: Connected to the supplicant for wfds
08-26 10:52:42.452  1943  2260 D WfdsJNI : doCommand: WFDS_SET TRUE
08-26 10:52:42.452  7120  7120 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-26 10:52:42.452  1943  2260 D WfdsService: selectPreferredScanChannel [36]
08-26 10:52:42.452  1943  2260 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-26 10:52:42.453  1943  1943 D WfdsService: isConnected: false
08-26 10:52:42.453  1036  1440 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-26 10:52:42.453  1036  1440 D WifiNative-wlan0: doBoolean: SCAN
,08-26 10:52:42.453  1036  1440 D WifiNative-wlan0: SCAN: returned false
08-26 10:52:42.454  1036  1440 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=121694  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
,08-26 10:52:42.459  1036  1393 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-26 10:52:42.459  1036  1393 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-26 10:52:42.460  1036  1393 D WifiNative-p2p0: P2P_FLUSH: returned true
08-26 10:52:42.460  1036  1393 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-26 10:52:42.460  1036  1393 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-26 10:52:42.460  1036  1393 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-26 10:52:42.461  1036  1393 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-26 10:52:42.461  1036  1393 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-26 10:52:42.463  1943  1943 I WfdStateTracker: handleP2pThisDeviceChanged
08-26 10:52:42.463  1943  1943 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-26 10:52:42.464  1943  1943 D WfdsService: Update P2p Interface State: 3
08-26 10:52:42.465  1036  1440 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=121705  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-26 10:52:42.465  1036  1440 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
,08-26 10:52:42.466  1036  1440 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-26 10:52:42.466  1036  1440 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-26 10:52:42.467  1036  1440 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-26 10:52:42.467  1036  1440 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-26 10:52:42.471  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 10:52:42.471  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 10:52:42.472  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 10:52:42.472  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 10:52:42.472  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-26 10:52:42.472  7102  7102 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-26 10:52:42.472  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 10:52:42.472  1036  1036 D WifiServerServiceExt: setSupplicantStateSCANNING
08-26 10:52:42.473  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 10:52:42.474  1036  1393 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-26 10:52:42.474  1036  1393 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-26 10:52:42.474  1036  1393 D LGWifiP2pService: InactiveState
08-26 10:52:42.474  1036  1393 D LGWifiP2pService: InactiveState{ when=-29ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-26 10:52:42.474  1036  1393 D LGWifiP2pService: P2pEnabledState{ when=-29ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-26 10:52:42.474  1036  1393 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-26 10:52:42.475  7120  7120 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-26 10:52:42.475  7120  7120 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 10:52:42.475  1943  7132 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-26 10:52:42.475  1036  7131 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-26 10:52:42.475  1036  7131 E WifiMonitor: WifiMonitor:p2p0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 10:52:42.475  1036  7131 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 10:52:42.475  1036  7131 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 10:52:42.476  7120  7120 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-26 10:52:42.476  7120  7120 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 10:52:42.476  1036  1393 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-26 10:52:42.476  1036  1393 D LGWifiP2pService: InactiveState{ when=-15ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-26 10:52:42.476  1036  1393 D LGWifiP2pService: P2pEnabledState{ when=-15ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-26 10:52:42.476  1036  1393 D LGWifiP2pService: InactiveState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-26 10:52:42.476  1036  1393 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=3 target=com.android.internal.uti,l.StateMachine$SmHandler }
08-26 10:52:42.476  1036  1393 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-26 10:52:42.476  7120  7120 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 10:52:42.476  1036  1393 D LGWifiP2pService: InactiveState{ when=-1ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-26 10:52:42.477  1036  1393 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-26 10:52:42.477  1036  1393 D LGWifiP2pService: DefaultState{ when=-1ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-26 10:52:42.477  1036  1393 D LGWifiP2pService: InactiveState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-26 10:52:42.477  1036  1393 D LGWifiP2pService: P2pEnabledState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-26 10:52:42.477  1036  1393 D LGWifiP2pService: DefaultState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-26 10:52:42.477  1036  1393 D LGWifiP2pService: InactiveState{ when=0 what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-26 10:52:42.477  1036  1393 D LGWifiP2pService: P2pEnabledState{ when=0 what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-26 10:52:42.477  1036  1393 D LGWifiP2pService: DefaultState{ when=0 what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-26 10:52:42.478  1943  2260 W WfdsService: DefaultState - msg [9441285] is not handled
08-26 10:52:42.478  1943  7132 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 10:52:42.478  1943  7132 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 10:52:42.478  1036  7131 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
,08-26 10:52:42.478  1036  7131 E WifiMonitor: WifiMonitor:p2p0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 10:52:42.478  1036  7131 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 10:52:42.478  1036  7131 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 10:52:42.478  1036  7131 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 10:52:42.478  1036  7131 E WifiMonitor: WifiMonitor:p2p0 cnt=30 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 10:52:42.478  1036  7131 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 10:52:42.478  1036  7131 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 10:52:42.478  1036  1036 E WifiServerServiceExt: No p2p device connected
08-26 10:52:42.504  3460  3460 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,08-26 10:52:42.504  3460  3460 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
,08-26 10:52:42.505  3460  3460 I LgeMiscReceiver: networkInfo.isConnected() = false
08-26 10:52:42.507  7102  7102 I HubEmail: JNI_OnLoad()
08-26 10:52:42.507  7102  7102 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-26 10:52:42.507  7102  7102 I HubEmail: registerNatives()
08-26 10:52:42.507  7102  7102 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-26 10:52:42.507  7102  7102 I HubEmail: registerNativeMethods()
08-26 10:52:42.507  7102  7102 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-26 10:52:42.508  7102  7102 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
08-26 10:52:42.549  1036  2005 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7138 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,08-26 10:52:42.555  6957  7134 W FormManager: Network not available. Please check & try again.
08-26 10:52:42.558  7102  7137 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-26 10:52:42.559  6957  7135 V FormManager: Network unavailable.
08-26 10:52:42.567  6957  7135 V FormManager: Network unavailable.
,08-26 10:52:42.583  1036  1923 I ActivityManager: Killing 6133:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,08-26 10:52:42.639  1036  1978 W libprocessgroup: failed to open /acct/uid_10080/pid_6133/cgroup.procs: No such file or directory
,08-26 10:52:42.719  7138  7138 D LgDataFeature: LgDataFeature() Constructor: none
08-26 10:52:42.720  7138  7138 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-26 10:52:42.722  7138  7138 D PhoneMonitor: Register our PhoneStateListener
,08-26 10:52:42.746  7138  7138 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,08-26 10:52:42.751  7138  7138 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-26 10:52:42.782  7138  7138 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,08-26 10:52:42.783  7138  7138 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
08-26 10:52:42.784  7138  7138 D TelephonyAutoProfiling: [parse] Load xml
,08-26 10:52:42.791  7138  7138 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
08-26 10:52:42.791  7138  7138 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
08-26 10:52:42.791  7138  7138 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-26 10:52:42.791  7138  7138 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
08-26 10:52:42.791  7138  7138 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
08-26 10:52:42.792  7138  7138 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
08-26 10:52:42.792  7138  7138 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-26 10:52:42.792  7138  7138 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-26 10:52:42.792  7138  7138 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-26 10:52:42.792  7138  7138 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-26 10:52:42.792  7138  7138 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-26 10:52:42.792  7138  7138 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-26 10:52:42.792  7138  7138 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-26 10:52:42.792  7138  7138 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-26 10:52:42.792  7138  7138 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-26 10:52:42.793  7138  7138 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-26 10:52:42.793  7138  7138 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
,08-26 10:52:42.804  1036  2005 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7161 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-26 10:52:42.805  1036  2005 I ActivityManager: Killing 6163:com.google.android.apps.plus/u0a97 (adj 15): empty #17
08-26 10:52:42.811  7138  7138 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
08-26 10:52:42.862  1036  1736 W libprocessgroup: failed to open /acct/uid_10097/pid_6163/cgroup.procs: No such file or directory
,08-26 10:52:42.921  7120  7120 E wpa_supplicant: USIM:  scard_init function
,08-26 10:52:42.922  7120  7120 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-26 10:52:42.923  1036  7131 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-26 10:52:42.923  1036  7131 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-26 10:52:42.925  1036  1440 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
08-26 10:52:42.926  1036  1440 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
08-26 10:52:42.926  1036  7131 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
,08-26 10:52:42.926  1036  7131 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: WPS-AP-AVAILABLE 
08-26 10:52:42.927  1036  7131 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-26 10:52:42.927  1036  7131 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-26 10:52:42.927  1036  7131 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-26 10:52:42.927  1036  1440 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
08-26 10:52:42.929  1036  1440 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
08-26 10:52:42.929  1036  1440 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-26 10:52:42.939  1036  1440 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=122179  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-26 10:52:42.945  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 10:52:42.945  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 10:52:42.945  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-26 10:52:42.946  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 10:52:42.946  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 10:52:42.947  1036  1440 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=122187  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-26 10:52:42.952  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 10:52:42.952  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 10:52:42.952  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-26 10:52:42.954  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 10:52:42.954  1036  1036 D WifiServerServiceExt: setSupplicantStateASSOCIATING
,08-26 10:52:42.956  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 10:52:42.958  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 10:52:42.958  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 10:52:42.959  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 10:52:43.037  7120  7120 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-26 10:52:43.040  1036  7131 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-26 10:52:43.040  1036  7131 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-26 10:52:43.040  1036  7131 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-26 10:52:43.041  1036  7131 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: Associated with f4:f2:6d:22:99:3e
,08-26 10:52:43.041  1036  7131 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-26 10:52:43.041  1036  7131 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-26 10:52:43.043  1036  1440 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=122283  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-26 10:52:43.043  1036  1440 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=122284  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-26 10:52:43.044  1036  1440 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=122284
08-26 10:52:43.044  1036  1440 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=122285
08-26 10:52:43.045  1036  1440 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=122285
08-26 10:52:43.045  1036  1440 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=122286
08-26 10:52:43.046  1036  1440 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=122286
08-26 10:52:43.046  1036  1440 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=122287  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-26 10:52:43.050  7120  7120 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-26 10:52:43.051  7120  7120 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-26 10:52:43.051  1036  7131 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-26 10:52:43.051  1036  7131 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-26 10:52:43.052  1036  7131 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-26 10:52:43.052  1036  7131 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-26 10:52:43.052  1036  7131 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-26 10:52:43.052  1036  7131 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-26 10:52:43.054  1036  7131 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-26 10:52:43.054  1036  7131 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-26 10:52:43.055  1036  7131 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-26 10:52:43.055  1036  7131 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,08-26 10:52:43.088  1036  1052 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7179 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
08-26 10:52:43.089  1036  1052 I ActivityManager: Killing 6761:com.lge.eula/1000 (adj 15): empty #17
,08-26 10:52:43.140  1036  1440 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=122380  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-26 10:52:43.140  1036  1737 W libprocessgroup: failed to open /acct/uid_1000/pid_6761/cgroup.procs: No such file or directory
,08-26 10:52:43.145  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 10:52:43.145  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 10:52:43.145  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-26 10:52:43.148  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 10:52:43.148  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 10:52:43.150  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 10:52:43.150  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 10:52:43.150  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-26 10:52:43.151  1036  1112 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-26 10:52:43.151  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 10:52:43.154  1036  1440 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=122394  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-26 10:52:43.156  1036  1440 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=122396  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
,08-26 10:52:43.158  1036  1440 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=122397
08-26 10:52:43.158  1036  1440 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=122398
08-26 10:52:43.159  1036  1440 D WifiNative-wlan0: doString: [STATUS]
08-26 10:52:43.159  1036  7131 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-26 10:52:43.159  1036  7131 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-26 10:52:43.160  1036  1440 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-26 10:52:43.161  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 10:52:43.161  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 10:52:43.162  1036  1440 I WifiServiceExtension: setVHTCapabilityType  : false
08-26 10:52:43.165  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 10:52:43.165  1036  1036 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-26 10:52:43.166  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 10:52:43.168  1036  1440 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-26 10:52:43.168  1036  1440 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
,08-26 10:52:43.173  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 10:52:43.173  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 10:52:43.173  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-26 10:52:43.176  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 10:52:43.176  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 10:52:43.176  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-26 10:52:43.180  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 10:52:43.180  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 10:52:43.184  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-26 10:52:43.186  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 10:52:43.186  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 10:52:43.187  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 10:52:43.190  1036  1440 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-26 10:52:43.190  1036  1495 D ConnectivityService: Got NetworkAgent Messenger
08-26 10:52:43.190  1036  1440 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-26 10:52:43.190  1036  1440 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-26 10:52:43.190  1036  1495 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-26 10:52:43.190  1036  1495 D ConnectivityService: NetworkAgent connected
08-26 10:52:43.191  1036  1440 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-26 10:52:43.191  1036  1440 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-26 10:52:43.195  1036  1440 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-26 10:52:43.195  1036  1440 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-26 10:52:43.196  1036  1440 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-26 10:52:43.196  1036  1440 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
,08-26 10:52:43.196  1036  1440 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-26 10:52:43.201  1036  1440 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-26 10:52:43.204   324   895 D CommandListener: Setting iface cfg
08-26 10:52:43.207  1036  1440 E WifiStateMachine: Start Dhcp Watchdog 2
08-26 10:52:43.208  1036  1440 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=122448  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-26 10:52:43.208  1036  1440 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=122449  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-26 10:52:43.209  1036  1440 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=122449  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-26 10:52:43.210  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 10:52:43.210  1036  1036 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-26 10:52:43.212  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 10:52:43.212  1036  1036 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-26 10:52:43.212  1036  1440 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
08-26 10:52:43.213  1036  1440 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
08-26 10:52:43.213  1036  1440 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-26 10:52:43.214  1036  1440 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-26 10:52:43.214  1036  1440 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-26 10:52:43.214  1036  1440 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-26 10:52:43.215  1036  1440 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=122455  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-26 10:52:43.215  1036  1440 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=122456  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-26 10:52:43.216  1036  1440 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=122456  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-26 10:52:43.218  1036  7197 D DhcpStateMachine: StoppedState
08-26 10:52:43.218  1036  7197 D DhcpStateMachine: StoppedState{ when=-10ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-26 10:52:43.218  1036  7197 D DhcpStateMachine: WaitBeforeStartState
08-26 10:52:43.218  1036  1440 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:76075] from screen [on:0 period:-972219311] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-26 10:52:43.219  1036  1440 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-972219309] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-26 10:52:43.219  1036  1440 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-26 10:52:43.223  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 10:52:43.224  1036  1495 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
08-26 10:52:43.224  1036  1440 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 10:52:43.225  1036  1440 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 10:52:43.225  1036  1440 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 10:52:43.226  1036  1440 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 10:52:43.226  1036  1440 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 10:52:43.226  1036  1440 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 10:52:43.227  1036  1495 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-26 10:52:43.271  1036  1784 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7203 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-26 10:52:43.273  1036  1784 I ActivityManager: Killing 6783:com.lge.bnr/1000 (adj 15): empty #17
,08-26 10:52:43.383  1036  1440 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=129,0,0
08-26 10:52:43.384  1036  1440 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=129,0,0
08-26 10:52:43.384  1036  1440 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-26 10:52:43.386  7120  7120 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-26 10:52:43.386  1036  1440 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-26 10:52:43.387  1036  1440 D WifiNative-wlan0: doBoolean: SET ps 0
08-26 10:52:43.389  1036  1440 D WifiNative-wlan0: SET ps 0: returned true
08-26 10:52:43.389  1036  1440 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-26 10:52:43.390  7120  7120 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-26 10:52:43.391  1036  1440 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-26 10:52:43.392  1036  1393 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@36d0e6b2 target=com.android.internal.util.StateMachine$SmHandler }
08-26 10:52:43.392  1036  1393 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@36d0e6b2 target=com.android.internal.util.StateMachine$SmHandler }
08-26 10:52:43.393  1036  7197 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-26 10:52:43.393  1036  7197 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-26 10:52:43.394  1036  1440 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-26 10:52:43.394  1036  1440 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-26 10:52:43.394  1036  1440 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-26 10:52:43.398  1036  2033 W libprocessgroup: failed to open /acct/uid_1000/pid_6783/cgroup.procs: No such file or directory
,08-26 10:52:43.402   324   895 D CommandListener: Setting iface cfg
08-26 10:52:43.402   324   895 D CommandListener: Trying to bring up wlan0
08-26 10:52:43.403  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 10:52:43.403  1036  1036 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-26 10:52:43.403  1036  1440 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-26 10:52:43.404  1036  1440 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 10:52:43.404  1036  1440 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 10:52:43.405  1036  1440 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 10:52:43.405  1036  1440 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,08-26 10:52:43.406  1036  1440 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 10:52:43.406  1036  1440 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 10:52:43.406  1036  1495 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-26 10:52:43.407  1036  1440 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-26 10:52:43.407  1036  1440 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-26 10:52:43.408  1036  1393 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-26 10:52:43.408  1036  1393 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-26 10:52:43.408  1036  1440 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-26 10:52:43.408  7120  7120 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-26 10:52:43.408  1036  1440 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-26 10:52:43.409  1036  1440 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-26 10:52:43.409  7120  7120 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-26 10:52:43.409  1036  1440 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-26 10:52:43.409  1036  1440 D WifiNative-wlan0: doBoolean: SET ps 1
08-26 10:52:43.425  1036  1440 D WifiNative-wlan0: SET ps 1: returned true
08-26 10:52:43.426  1036  1495 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-26 10:52:43.426  1036  1440 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-26 10:52:43.427  1036  1440 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-26 10:52:43.427  1036  1440 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-26 10:52:43.427  1036  1495 D ConnectivityService: ignoring duplicate network state non-change
,08-26 10:52:43.431  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 10:52:43.432  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 10:52:43.434  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 10:52:43.435  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 10:52:43.435  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 10:52:43.436  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-26 10:52:43.437  1036  1495 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-26 10:52:43.438  1036  1495 D ConnectivityService: Adding iface wlan0 to network 101
08-26 10:52:43.438  7203  7203 I art     : Almond Protected OAT
,08-26 10:52:43.443  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 10:52:43.443  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 10:52:43.443  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-26 10:52:43.445  1036  1440 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-26 10:52:43.447  1036  1036 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-26 10:52:43.450  1943  1943 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-26 10:52:43.453  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 10:52:43.453  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-26 10:52:43.453  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-26 10:52:43.454  1036  1036 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-26 10:52:43.455  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 10:52:43.455  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 10:52:43.458  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 10:52:43.461  1036  1393 D LGWifiP2pService: InactiveState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-26 10:52:43.461  1036  1393 D LGWifiP2pService: P2pEnabledState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-26 10:52:43.461  1036  1393 D LGWifiP2pService: DefaultState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-26 10:52:43.463  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 10:52:43.464  1604  1604 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-26 10:52:43.464  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 10:52:43.464  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 10:52:43.464  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 10:52:43.464  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-26 10:52:43.473  1036  1495 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-26 10:52:43.473  1036  1495 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
08-26 10:52:43.475  1036  1495 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
08-26 10:52:43.475   324   895 E Netd    : netlink response contains error (File exists)
08-26 10:52:43.476  1036  1495 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
08-26 10:52:43.477  1036  1495 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-26 10:52:43.477  1036  1495 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
08-26 10:52:43.477  1036  1495 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-26 10:52:43.478  1036  1495 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-26 10:52:43.478  1036  1495 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-26 10:52:43.478  1036  1495 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-26 10:52:43.479  1036  1495 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-26 10:52:43.479  1036  1495 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 10:52:43.479  1036  1495 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 10:52:43.479  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 10:52:43.479  1036  1495 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-26 10:52:43.479  1036  1495 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 10:52:43.479  1604  1604 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-26 10:52:43.479  1036  1495 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-26 10:52:43.479  1036  1495 D ConnectivityService: currentScore = 0, newScore = 20
08-26 10:52:43.479  1036  1495 D ConnectivityService:    accepting network in place of null
08-26 10:52:43.479  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 10:52:43.479  1036  1495 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 10:52:43.479  1036  7196 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-26 10:52:43.480  1036  7196 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-26 10:52:43.480  1036  7196 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-26 10:52:43.480  1036  7196 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-26 10:52:43.482  1036  1440 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 10:52:43.482  1036  1440 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 10:52:43.483  1854  1854 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 10:52:43.483   324  7224 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-26 10:52:43.483  1854  1854 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-26 10:52:43.485  1036  1495 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> ,192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-26 10:52:43.485  1036  1495 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-26 10:52:43.485  1036  1495 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-26 10:52:43.485  1036  1495 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-26 10:52:43.485  1036  1495 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-26 10:52:43.486  1036  1495 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-26 10:52:43.487  1036  1495 D ConnectivityService: validation of new default Network = false
08-26 10:52:43.487  1036  1495 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-26 10:52:43.487  1036  1495 D DSQN    : enableDataServiceNotify 
08-26 10:52:43.487  1036  1495 D DSQN    : start dsqn bin
08-26 10:52:43.495  1036  1495 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-26 10:52:43.495  1036  1495 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 10:52:43.495  1036  1495 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 10:52:43.483  7225  7225 W dsqn    : type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 10:52:43.483  7225  7225 W dsqn    : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-26 10:52:43.496  1604  2075 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-26 10:52:43.500  1036  1440 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-26 10:52:43.501  1036  1440 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-26 10:52:43.501  1036  1440 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
08-26 10:52:43.502  1036  1440 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-26 10:52:43.502  1036  1440 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-26 10:52:43.503  1036  1440 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
08-26 10:52:43.512  7225  7225 E DSQN    : DSQN ssw
,08-26 10:52:43.520  1036  1097 W ProcessCpuTracker: Skipping unknown process pid 7222
08-26 10:52:43.525  1036  1036 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
,08-26 10:52:43.529  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-26 10:52:43.529  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-26 10:52:43.529  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-26 10:52:43.538   324  7224 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,08-26 10:52:43.551  1036  1392 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
08-26 10:52:43.555  7203  7203 D WeatherApplication: removeAccount
08-26 10:52:43.559  1819  7229 I CheckinService: active receiver: enabled
,08-26 10:52:43.559  7203  7203 D WeatherApplication: Account.length = 0
08-26 10:52:43.559  7203  7203 E WeatherApplication: OPERATOR:OPEN
08-26 10:52:43.570   324  7224 D libc-netbsd: res_queryN name = clients3.google.com succeed
,08-26 10:52:43.592  1819  7229 I CheckinService: Preparing to send checkin request
08-26 10:52:43.593  1819  7229 I EventLogService: Accumulating logs since 1472201498654
08-26 10:52:43.598  1036  7197 D DhcpStateMachine: DHCPV4 request on wlan0
08-26 10:52:43.599  1036  7197 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-26 10:52:43.599  1036  7197 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-26 10:52:43.599   324   894 D LGDataListener: argv[0]=dsqncommand
08-26 10:52:43.600   324   894 D LGDataListener: argv[1]=wlan0
08-26 10:52:43.600   324   894 D LGDataListener: argv[2]=1
08-26 10:52:43.600   324   894 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-26 10:52:43.600  1036  1110 D DSQN    : DSQM DsqnNotification wlan0  1
08-26 10:52:43.600  1036  1110 D DSQN    : start to monitor internet connection
08-26 10:52:43.593  7233  7233 W dhcpcd  : type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 10:52:43.593  7233  7233 W dhcpcd  : type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 10:52:43.602  1604  1604 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-26 10:52:43.605  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 10:52:43.608  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 10:52:43.609  7203  7203 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 10:52:43
08-26 10:52:43.609  7233  7233 I dhcpcd  : version 5.5.6 starting
,08-26 10:52:43.612  7233  7233 E dhcpcd  : get_duid: m
08-26 10:52:43.612  7233  7233 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-26 10:52:43.612  7233  7233 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-26 10:52:43.618  7203  7203 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-26 10:52:43.618  7203  7203 D Weather.Utils: 2 : All the weather widget is gone.
08-26 10:52:43.622  7203  7203 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-26 10:52:43.625  7203  7203 D WeatherAncestor: connectivity changed - connection : true
,08-26 10:52:43.626  7203  7203 D WeatherService: 2 : isServiceAlived():false forecastCache:null
08-26 10:52:43.631  1036  7196 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 26 Aug 2016 08:52:43 GMT], X-Android-Received-Millis=[1472201563631], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472201563599]}
08-26 10:52:43.631  1036  7196 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-26 10:52:43.631  1036  7196 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-26 10:52:43.631  1036  1495 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
08-26 10:52:43.632  1036  1495 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-26 10:52:43.632  1036  1495 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 10:52:43.632  1036  1495 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 10:52:43.632  1036  1495 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-26 10:52:43.632  1036  1495 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
08-26 10:52:43.632  1036  1495 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-26 10:52:43.632  1036  1495 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 10:52:43.632  1036  1495 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 10:52:43.632  1036  1495 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 10:52:43.633  1036  1495 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 10:52:43.633  1036  1495 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-26 10:52:43.634  1604  2075 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-26 10:52:43.634  1036  1440 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 10:52:43.634  1036  1440 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 10:52:43.637  1854  1854 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-26 10:52:43.637  1854  1854 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-26 10:52:43.642  7203  7203 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-26 10:52:43.642  7203  7203 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-26 10:52:43.643  7203  7203 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
,08-26 10:52:43.655  1604  1604 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-26 10:52:43.655  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 10:52:43.656  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 10:52:43.660  7203  7203 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-26 10:52:43.660  7203  7203 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 10:52:43
08-26 10:52:43.669  7233  7233 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-26 10:52:43.669  7233  7233 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-26 10:52:43.669  7233  7233 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-26 10:52:43.669  7233  7233 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
08-26 10:52:43.669  7233  7233 D dhcpcd  : wlan0: sending REQUEST (xid 0x6e6e0857), next in 3.47 seconds
,08-26 10:52:43.694  1036  1052 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7241 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-26 10:52:43.695  1036  1052 I ActivityManager: Killing 2172:com.lge.music/u0a34 (adj 15): empty #17
08-26 10:52:43.706  7233  7233 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
,08-26 10:52:43.712   329  2193 V AudioFlinger: 2172 died, releasing its sessions
08-26 10:52:43.712   329  2193 V AudioFlinger:  pid 1854 @ 0
08-26 10:52:43.712   329  2193 V AudioFlinger:  pid 3460 @ 1
08-26 10:52:43.712   329  2193 V AudioFlinger:  pid 3460 @ 2
08-26 10:52:43.727  7233  7233 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
08-26 10:52:43.727  7233  7233 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
,08-26 10:52:43.728  7233  7233 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-26 10:52:43.728  7233  7233 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-26 10:52:43.728  7233  7233 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-26 10:52:43.728  7233  7233 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-26 10:52:43.728  7233  7233 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-26 10:52:43.728  7233  7233 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-26 10:52:43.739  1819  7229 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,08-26 10:52:43.740  1036  1924 W libprocessgroup: failed to open /acct/uid_10034/pid_2172/cgroup.procs: No such file or directory
,08-26 10:52:43.844   278   343 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-26 10:52:43.844   278   343 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-26 10:52:43.844   278   343 W Vold    : Returning OperationFailed - no handler for errno 0
08-26 10:52:43.844  7241  7270 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-26 10:52:43.847  1036  1784 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7273 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,08-26 10:52:43.853   278   343 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-26 10:52:43.853   278   343 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-26 10:52:43.853   278   343 W Vold    : Returning OperationFailed - no handler for errno 0
08-26 10:52:43.854  7241  7270 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-26 10:52:43.859   351   351 I art     : Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 345us total 13.680ms
,08-26 10:52:43.873   351   351 I art     : Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 335us total 13.351ms
,08-26 10:52:43.887   351   351 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 251us total 12.276ms
,08-26 10:52:43.896   278   343 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-26 10:52:43.896   278   343 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-26 10:52:43.896   278   343 W Vold    : Returning OperationFailed - no handler for errno 0
08-26 10:52:43.897  7241  7290 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-26 10:52:43.901  7273  7273 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,08-26 10:52:43.901  7273  7273 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
08-26 10:52:43.903   278   343 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-26 10:52:43.903   278   343 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-26 10:52:43.903   278   343 W Vold    : Returning OperationFailed - no handler for errno 0
08-26 10:52:43.904  7241  7290 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-26 10:52:43.930  7273  7273 I MultiDex: VM with version 2.1.0 has multidex support
08-26 10:52:43.930  7273  7273 I MultiDex: install
08-26 10:52:43.930  7273  7273 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-26 10:52:43.939  7273  7273 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,08-26 10:52:44.001  1036  7197 D DhcpStateMachine: DHCPV4 succeeded on wlan0
08-26 10:52:44.002  1036  7197 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-26 10:52:44.002  1036  7197 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-26 10:52:44.002  1036  7197 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
08-26 10:52:44.003  1036  7197 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-26 10:52:44.003  1036  7197 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-26 10:52:44.003  1036  7197 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-26 10:52:44.003  1036  7197 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-26 10:52:44.003  1036  7197 D DhcpStateMachine: RunningState
,08-26 10:52:44.109  7241  7241 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-26 10:52:44.130  7241  7241 I LibraryLoader: Loading: webviewchromium
,08-26 10:52:44.134  7241  7241 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 3382-3386)
08-26 10:52:44.134  7241  7241 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-26 10:52:44.143  7241  7241 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {de5cb4}
,08-26 10:52:44.147  7241  7241 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-26 10:52:44.148  7241  7241 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-26 10:52:44.168  7241  7241 I BrowserStartupController: Initializing chromium process, renderers=0
08-26 10:52:44.169  7241  7241 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-26 10:52:44.190  7241  7241 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,08-26 10:52:44.191  7241  7241 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
,08-26 10:52:44.192  7241  7241 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
08-26 10:52:44.202   329  1400 V AudioPolicyService: registerClient() client 0xb1030de0, uid 10093
08-26 10:52:44.203  7241  7323 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-26 10:52:44.218  7241  7241 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-26 10:52:44.218  7241  7241 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-26 10:52:44.218  7241  7241 I Adreno-EGL: Build Date: 12/12/14 금
08-26 10:52:44.218  7241  7241 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-26 10:52:44.218  7241  7241 I Adreno-EGL: Remote Branch: 
08-26 10:52:44.218  7241  7241 I Adreno-EGL: Local Patches: 
08-26 10:52:44.218  7241  7241 I Adreno-EGL: Reconstruct Branch: 
,08-26 10:52:44.266  7331  7331 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=32 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-26 10:52:44.291  7241  7241 I NSApplication: Starting up...
,08-26 10:52:44.338  7331  7331 I dex2oat : dex2oat took 71.958ms (threads: 4)
,08-26 10:52:44.355  7273  7292 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-26 10:52:44.355  7273  7292 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-26 10:52:44.355  7273  7292 I Adreno-EGL: Build Date: 12/12/14 금
08-26 10:52:44.355  7273  7292 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-26 10:52:44.355  7273  7292 I Adreno-EGL: Remote Branch: 
08-26 10:52:44.355  7273  7292 I Adreno-EGL: Local Patches: 
08-26 10:52:44.355  7273  7292 I Adreno-EGL: Reconstruct Branch: 
,08-26 10:52:44.377  1036  2014 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7342 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,08-26 10:52:44.380  1036  2033 I ActivityManager: Killing 6080:com.android.vending/u0a44 (adj 15): empty #17
08-26 10:52:44.457  7273  7292 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-26 10:52:44.457  7273  7292 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-26 10:52:44.457  7273  7292 I Adreno-EGL: Build Date: 12/12/14 금
08-26 10:52:44.457  7273  7292 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-26 10:52:44.457  7273  7292 I Adreno-EGL: Remote Branch: 
08-26 10:52:44.457  7273  7292 I Adreno-EGL: Local Patches: 
08-26 10:52:44.457  7273  7292 I Adreno-EGL: Reconstruct Branch: 
,08-26 10:52:44.496  1036  1495 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-26 10:52:44.534  1036  1052 W libprocessgroup: failed to open /acct/uid_10044/pid_6080/cgroup.procs: No such file or directory
,08-26 10:52:44.551  1036  1584 D WifiServiceImplEx: setWifiEnabled: false pid=6692, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-26 10:52:44.551  1036  1584 D WifiService: setWifiEnabled: false pid=6692, uid=10118
08-26 10:52:44.551  1036  1584 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-26 10:52:44.571  1036  1440 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
,08-26 10:52:44.571  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-26 10:52:44.571  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-26 10:52:44.571  1036  1036 D Ulp_jni : JNI:system_update. Event-4
08-26 10:52:44.571  1036  1440 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-26 10:52:44.572  1036  1440 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-26 10:52:44.572  1036  1440 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-26 10:52:44.573  1036  1440 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-26 10:52:44.573  1036  1440 E WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-26 10:52:44.573  1036  1440 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-26 10:52:44.573  1036  1440 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-26 10:52:44.575  1036  1440 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-26 10:52:44.575  1036  1440 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-26 10:52:44.582  1036  1440 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-26 10:52:44.582  1036  1440 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-26 10:52:44.583  7120  7120 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-26 10:52:44.583  1036  1393 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-26 10:52:44.583  1036  1393 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-26 10:52:44.584  1036  1440 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-26 10:52:44.584  1036  1440 D WifiNative-wlan0: doBoolean: SET ps 1
,08-26 10:52:44.585  1036  1440 D WifiNative-wlan0: SET ps 1: returned true
08-26 10:52:44.585  1036  7197 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-26 10:52:44.586   324   895 D CommandListener: Clearing all IP addresses on wlan0
08-26 10:52:44.614  1036  1495 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-26 10:52:44.614  1036  1495 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
08-26 10:52:44.616  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 10:52:44.616  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 10:52:44.617  1036  1036 D WifiHS20: hidePasspointNotification off =false
08-26 10:52:44.617  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 10:52:44.617  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 10:52:44.617  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 10:52:44.617  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-26 10:52:44.619  1943  1943 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-26 10:52:44.622  1036  1036 D WifiHS20: hidePasspointNotification off =false
08-26 10:52:44.625  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 10:52:44.625  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 10:52:44.625  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,08-26 10:52:44.626  1036  1440 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 10:52:44.626  1036  1440 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 10:52:44.627  1036  1440 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 10:52:44.627  1036  1440 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 10:52:44.628  1036  1393 D LGWifiP2pService: InactiveState{ when=-2ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-26 10:52:44.628  1036  1393 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-26 10:52:44.628  1036  1393 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@16ddb95b
08-26 10:52:44.628  1036  1393 D LGWifiP2pService: P2pDisablingState
08-26 10:52:44.628  1036  1393 D LGWifiP2pService: P2pDisablingState{ when=-1ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-26 10:52:44.628  1036  1393 D LGWifiP2pService: p2p socket connection lost
08-26 10:52:44.628  1036  1393 D LGWifiP2pService: P2pDisabledState
08-26 10:52:44.630  1036  1036 D WifiScanningService: SCAN_AVAILABLE : 1
08-26 10:52:44.630  1036  1036 D RttService: SCAN_AVAILABLE : 1
08-26 10:52:44.630  1036  1558 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-26 10:52:44.630  1036  1559 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-26 10:52:44.630  1943  1943 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-26 10:52:44.631  1943  1943 D WfdsService: WifiP2pState is changed : false
08-26 10:52:44.631  1943  2260 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-26 10:52:44.631  1943  2260 D WfdsService: Set the WFDS Monitor: false
08-26 10:52:44.631  1036  1440 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 10:52:44.632  1036  1440 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 10:52:44.632  1036  1440 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-26 10:52:44.632  1036  1440 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-26 10:52:44.633  1943  2260 D WfdsMonitor: WFDS Monitor is stopped
08-26 10:52:44.633  1943  2260 D WfdsService: STATE : WfdsDisabledState - enter
08-26 10:52:44.633  1943  7132 D CtrlSupplicant: Received on exit socket, terminate
08-26 10:52:44.633  1943  7132 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-26 10:52:44.633  1943  7132 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-26 10:52:44.633  1943  7132 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-26 10:52:44.633  1943  2268 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-26 10:52:44.634  1943  2260 W WfdsService: DefaultState - msg [9445378] is not handled
08-26 10:52:44.634  1036  1393 D LGWifiP2pService: P2pDisabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-26 10:52:44.634  1036  1393 D LGWifiP2pService: DefaultState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-26 10:52:44.634  1036  1440 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-26 10:52:44.634  7120  7120 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-26 10:52:44.635  1036  1440 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-26 10:52:44.635  1036  1440 D WifiNative-wlan0: doBoolean: SET ps 1
08-26 10:52:44.635  1036  1440 D WifiNative-wlan0: SET ps 1: returned true
08-26 10:52:44.640  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, is,ConnectedToProvisioningNetwork: false]
08-26 10:52:44.640  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-26 10:52:44.642  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 10:52:44.669   324   895 D CommandListener: Clearing all IP addresses on wlan0
08-26 10:52:44.669  1036  1495 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-26 10:52:44.669  1036  1495 D DSQN    : disableDataServiceNotify
08-26 10:52:44.670  1036  1495 D DSQN    : stop dsqn bin
,08-26 10:52:44.671  1036  1440 D WifiNative-p2p0: doBoolean: TERMINATE
08-26 10:52:44.672  1036  1036 D WifiHS20: hidePasspointNotification off =false
08-26 10:52:44.672  1036  1440 D WifiNative-p2p0: TERMINATE: returned true
08-26 10:52:44.672  1036  1440 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-26 10:52:44.672  1036  1440 E WifiStateMachine: useWiFiOffloading() : false
08-26 10:52:44.672  1036  1440 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-26 10:52:44.673  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-26 10:52:44.673  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 10:52:44.673  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 10:52:44.674  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 10:52:44.674  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 10:52:44.674  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-26 10:52:44.675  1943  1943 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-26 10:52:44.677  1036  1495 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
08-26 10:52:44.677  1036  1495 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 10:52:44.677  1036  1495 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 10:52:44.678  1036  1495 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 10:52:44.678  1036  1495 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-26 10:52:44.678  1604  2075 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-26 10:52:44.678  1036  1495 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-26 10:52:44.678  1036  1495 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-26 10:52:44.678  1036  1495 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-26 10:52:44.679  1036  1495 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-26 10:52:44.679  1036  1495 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-26 10:52:44.679  1036  1392 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-26 10:52:44.679  1036  7196 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-26 10:52:44.679  1036  7196 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-2ms what=532487 target=com.andr,oid.internal.util.StateMachine$SmHandler }
08-26 10:52:44.679  1036  7196 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-26 10:52:44.680  1036  1495 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-26 10:52:44.680  1036  1495 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 10:52:44.680  1036  1495 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 10:52:44.681  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
,08-26 10:52:44.681  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 10:52:44.681  1036  1036 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-26 10:52:44.681  1036  1036 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-26 10:52:44.681  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-26 10:52:44.681  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-26 10:52:44.681  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-26 10:52:44.682  1036  1392 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-26 10:52:44.682  1036  1440 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 10:52:44.683  1036  1440 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 10:52:44.684  1036  1495 D NetworkManagementService: Removing idletimer
08-26 10:52:44.684  1036  1495 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 10:52:44.684  1854  1854 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 10:52:44.684  1036  1495 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-26 10:52:44.684  1854  1854 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-26 10:52:44.685  1036  1036 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-26 10:52:44.685  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-26 10:52:44.685  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-26 10:52:44.685  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-26 10:52:44.686  6692  6692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 10:52:44.686  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 10:52:44.686  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 10:52:44.686  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 10:52:44.686  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 10:52:44.686  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 10:52:44.686  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 10:52:44.686  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 10:52:44.686  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 10:52:44.686  6692  6692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 10:52:44.686  6692  6692 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 ,10:52:44.688  6692  6692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 10:52:44.688  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 10:52:44.688  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 10:52:44.688  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 10:52:44.688  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 10:52:44.688  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 10:52:44.688  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 10:52:44.688  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 10:52:44.688  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 10:52:44.688  6692  6692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 10:52:44.688  6692  6692 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 10:52:44.692  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 10:52:44.707  1604  1604 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-26 10:52:44.708  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-26 10:52:44.708  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-26 10:52:44.721  1604  1604 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,08-26 10:52:44.722  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 10:52:44.722  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 10:52:44.728  1036  1053 I art     : Explicit concurrent mark sweep GC freed 119701(5MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/65MB, paused 1.561ms total 168.663ms
08-26 10:52:44.754  7342  7342 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-26 10:52:44.768  7120  7120 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,08-26 10:52:44.768  7120  7120 I wpa_supplicant: monitor socket send errors count : 1
08-26 10:52:44.768  7120  7120 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1943-4\x00 that cannot receive messages
08-26 10:52:44.769  1036  7131 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-26 10:52:44.769  1036  7131 D WifiMonitor: Dropping event because (p2p0) is stopped
,08-26 10:52:44.792  1036  7197 D DhcpStateMachine: StoppedState
,08-26 10:52:44.792  1036  7197 D DhcpStateMachine: StoppedState{ when=-157ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-26 10:52:44.793  1036  1440 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-26 10:52:44.794  1036  1440 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-26 10:52:44.808  7120  7120 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-26 10:52:44.809  1036  7131 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
,08-26 10:52:44.809  1036  7131 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-26 10:52:44.809  7120  7120 W wpa_supplicant: USIM:  scard_deinit function
08-26 10:52:44.809  1036  7131 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-26 10:52:44.810  1036  7131 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-26 10:52:44.811  1036  7131 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-26 10:52:44.811  1036  7131 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-26 10:52:44.812  1036  1112 D Tethering: InitialState.processMessage what=4
08-26 10:52:44.813  1036  1112 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-26 10:52:44.813  1036  1440 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=124053
08-26 10:52:44.814  1036  1440 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=124054
08-26 10:52:44.814  1036  1440 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=124054  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-26 10:52:44.815  1036  1440 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=124055  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-26 10:52:44.815  1036  1440 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-26 10:52:44.815  1036  1440 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-26 10:52:44.837  7273  7292 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-26 10:52:44.837  7273  7292 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-26 10:52:44.837  7273  7292 I Adreno-EGL: Build Date: 12/12/14 금
08-26 10:52:44.837  7273  7292 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-26 10:52:44.837  7273  7292 I Adreno-EGL: Remote Branch: 
08-26 10:52:44.837  7273  7292 I Adreno-EGL: Local Patches: 
08-26 10:52:44.837  7273  7292 I Adreno-EGL: Reconstruct Branch: 
,08-26 10:52:44.931  7120  7120 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-26 10:52:44.931  1036  7131 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-26 10:52:44.931  1036  7131 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-TERMINATING 
08-26 10:52:44.931  1036  7131 D WifiMonitor: Disconnecting from the supplicant, no more events
08-26 10:52:44.932  1036  1440 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 44 0
,08-26 10:52:44.976  6501  6501 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-26 10:52:44.981  6501  6530 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-26 10:52:44.993  2128  2128 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-26 10:52:45.003  7067  7067 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
,08-26 10:52:45.003  7067  7067 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-26 10:52:45.003  7067  7067 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-26 10:52:45.003  7067  7067 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-26 10:52:45.005  7067  7067 I AppUp4:CustModeStarterReceiver: onReceive
,08-26 10:52:45.008  7067  7067 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@3f8f71b5
08-26 10:52:45.008  7067  7067 D AppUp4:CustFacade: isCustomizationCompleted : false
08-26 10:52:45.008  7067  7067 D AppUp4:CustFacade: isPhone : true
08-26 10:52:45.009  7067  7067 D AppUp4:CustModeStarterReceiver: begin check event
08-26 10:52:45.009  7067  7067 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-26 10:52:45.011  4298  4298 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-26 10:52:45.012  4298  4298 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-26 10:52:45.013  4298  4298 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 10:52:45.018  4298  4298 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-26 10:52:45.024  4298  7378 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-26 10:52:45.027  7102  7102 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-26 10:52:45.029  4298  7381 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-26 10:52:45.029  4298  7381 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-26 10:52:45.034  1943  1943 D WfdsService: Supplicant Connection state is changed : false
08-26 10:52:45.034  7273  7292 D LgDataFeature: LgDataFeature() Constructor: none
08-26 10:52:45.034  1943  2260 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-26 10:52:45.034  7273  7292 D LgDataFeature: LgDataFeature() Constructor Done, null
08-26 10:52:45.034  1943  2260 D WfdsService: Set the WFDS Monitor: false
08-26 10:52:45.034  1943  2260 D WfdsMonitor: WFDS Monitor is stopped
08-26 10:52:45.036  1036  1440 D WifiOffDelayIfNotUsed: stopMonitoring
08-26 10:52:45.036  1036  1440 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-26 10:52:45.036  1036  1440 E WifiStateMachine: useWiFiOffloading() : false
08-26 10:52:45.036  1036  1440 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-26 10:52:45.041  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 10:52:45.043  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-26 10:52:45.044  1036  1468 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-26 10:52:45.044  1036  1468 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-26 10:52:45.044  2454  2454 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 10:52:45.044  1943  1943 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-26 10:52:45.047  6692  6692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 10:52:45.047  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 10:52:45.047  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 10:52:45.047  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 10:52:45.047  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 10:52:45.047  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 10:52:45.047  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 10:52:45.047  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 10:52:45.047  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 10:52:45.052  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 10:52:45.058  7102  7382 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 10:52:45.063  3460  3460 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-26 10:52:45.063  3460  3460 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-26 10:52:45.063  3460  3460 I LgeMiscReceiver: networkInfo.isConnected() = false
08-26 10:52:45.065  7138  7138 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,08-26 10:52:45.066  7138  7138 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-26 10:52:45.066  6957  7384 W FormManager: Network not available. Please check & try again.
08-26 10:52:45.070  6957  7385 V FormManager: Network unavailable.
08-26 10:52:45.076  7203  7203 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 10:52:45
,08-26 10:52:45.078  7203  7203 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
,08-26 10:52:45.078  7203  7203 D Weather.Utils: 2 : All the weather widget is gone.
08-26 10:52:45.078  7203  7203 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-26 10:52:45.078  7203  7203 D WeatherAncestor: connectivity changed - connection : true
08-26 10:52:45.078  7203  7203 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@ea29bbb
08-26 10:52:45.080  7203  7203 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-26 10:52:45.080  7203  7203 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-26 10:52:45.080  7203  7203 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-26 10:52:45.080  7203  7203 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-26 10:52:45.080  7203  7203 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 10:52:45
08-26 10:52:45.080  6957  7385 V FormManager: Network unavailable.
08-26 10:52:45.082   324  7388 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-26 10:52:45.083  1036  1110 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-26 10:52:45.084  1819  7229 E CheckinTask: Checkin failed: https://android.clients.google.com/checkin (request #0): java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,08-26 10:52:45.095  1819  7229 I CheckinService: active receiver: disabled
,08-26 10:52:45.116  6844  6844 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-26 10:52:45.116  6844  6844 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
,08-26 10:52:45.116  6844  6844 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
,08-26 10:52:45.116  6844  6844 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-26 10:52:45.116  6844  6844 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-26 10:52:45.117  6844  6844 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-26 10:52:45.117  6844  6844 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-26 10:52:45.117  6844  6844 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-26 10:52:45.117  6844  6844 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-26 10:52:45.118  6844  6844 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-26 10:52:45.119  6844  6844 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-26 10:52:45.127  6872  6872 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-26 10:52:45.130  6844  6844 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-26 10:52:45.134  6957  7390 W FormManager: Network not available. Please check & try again.
08-26 10:52:45.137  6844  6844 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 10:52:45.143  6957  7391 V FormManager: Network unavailable.
,08-26 10:52:45.147  6957  7391 V FormManager: Network unavailable.
08-26 10:52:45.156  6872  6872 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-26 10:52:45.159  6844  6844 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-26 10:52:45.164  6957  7393 W FormManager: Network not available. Please check & try again.
,08-26 10:52:45.165  6844  6844 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 10:52:45.175  6957  7394 V FormManager: Network unavailable.
08-26 10:52:45.177  6957  7394 V FormManager: Network unavailable.
08-26 10:52:45.183  4298  4298 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
,08-26 10:52:45.183  4298  4298 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-26 10:52:45.185  4298  4298 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 10:52:45.189  4298  4298 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 10:52:45.194  4298  7395 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-26 10:52:45.197  4298  7396 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
,08-26 10:52:45.197  4298  7396 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-26 10:52:45.242  1036  1978 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7397 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-26 10:52:45.365  7397  7397 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-26 10:52:45.366  7397  7397 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-26 10:52:45.374  7397  7397 V [BNRBootReceiver]: Boot Receiver Return
,08-26 10:52:45.375  7397  7397 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-26 10:52:45.381  6501  6501 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-26 10:52:45.396  6844  6844 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 10:52:45.401  6844  6844 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 10:52:45.417  6918  6918 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 10:52:45.418  6918  6918 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-26 10:52:45.421  6918  6918 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-26 10:52:45.430  6844  6844 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,08-26 10:52:45.439  6844  6844 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
,08-26 10:52:45.449  6501  6501 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-26 10:52:45.469  6844  6844 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 10:52:45.477  6844  6844 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 10:52:45.487  6918  6918 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-26 10:52:45.488  6918  6918 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-26 10:52:45.491  6918  6918 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-26 10:52:45.498  6501  6501 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-26 10:52:45.521  6844  6844 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 10:52:45.535  6844  6844 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 10:52:45.546  6918  6918 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-26 10:52:45.547  6918  6918 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 10:52:45.549  6918  6918 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-26 10:52:45.556  6501  6501 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 10:52:45.567  6844  6844 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 10:52:45.574  6844  6844 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 10:52:45.578  6804  7046 D serial_port: close(fd = 24)
08-26 10:52:45.582  6918  6918 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-26 10:52:45.582  6918  6918 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 10:52:45.582  6918  6918 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-26 10:52:45.584  6804  7046 I UEI.SmartControl: Serial port is closed.
08-26 10:52:45.585  6501  6501 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 10:52:45.594  6844  6844 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-26 10:52:45.595  6804  7049 D UEI.SmartControl: Internal timer expired: 2
08-26 10:52:45.595  6804  7049 D UEI.SmartControl: unbind internal service
,08-26 10:52:45.601  6844  6844 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 10:52:45.611  6918  6918 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 10:52:45.611  6918  6918 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-26 10:52:45.612  6918  6918 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-26 10:52:45.620  6501  6501 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-26 10:52:45.632  6844  6844 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 10:52:45.642  6844  6844 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 10:52:45.652  6918  6918 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 10:52:45.653  6918  6918 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-26 10:52:45.654  6918  6918 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-26 10:52:45.662  6501  6501 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 10:52:45.678  6844  6844 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 10:52:45.690  6844  6844 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 10:52:45.707  6918  6918 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 10:52:45.708  6918  6918 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 10:52:45.710  6918  6918 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-26 10:52:45.726  6501  6501 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-26 10:52:45.745  6844  6844 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 10:52:45.755  6844  6844 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 10:52:45.769  6918  6918 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 10:52:45.769  6918  6918 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-26 10:52:45.777  6918  6918 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-26 10:52:45.789  6501  6501 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-26 10:52:45.808  6844  6844 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 10:52:45.815  6844  6844 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 10:52:45.824  6918  6918 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 10:52:45.824  6918  6918 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 10:52:45.826  6918  6918 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-26 10:52:45.833  6501  6501 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 10:52:45.841  6872  6872 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,08-26 10:52:45.858  1036  1485 D WifiService: New client listening to asynchronous messages
08-26 10:52:45.859  6872  6872 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-26 10:52:45.869  6844  6844 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 10:52:45.883  6844  6844 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 10:52:45.898  6918  6918 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-26 10:52:45.898  6918  6918 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 10:52:45.900  6918  6918 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-26 10:52:45.903  6918  6918 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-26 10:52:45.904  6918  6918 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-26 10:52:45.919  6501  6501 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-26 10:52:45.935  6872  6872 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,08-26 10:52:45.940  6872  6872 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-26 10:52:45.947  6844  6844 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 10:52:45.962  6844  6844 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 10:52:45.978  6918  6918 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-26 10:52:45.979  6918  6918 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-26 10:52:45.981  6918  6918 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,08-26 10:52:45.982  6918  6918 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-26 10:52:45.983  6918  6918 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-26 10:52:45.991  1036  1970 I ActivityManager: Killing 6894:com.lge.lifetracker/u0a37 (adj 15): empty #17
08-26 10:52:46.053  1036  1736 W libprocessgroup: failed to open /acct/uid_10037/pid_6894/cgroup.procs: No such file or directory
,08-26 10:52:46.059  2128  2128 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
08-26 10:52:46.071  2128  2128 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,08-26 10:52:46.072  2128  2128 D c       : Getting all permits...
08-26 10:52:46.072  2128  2128 D a       : Opening database...
08-26 10:52:46.077  2128  2128 D a       : Opening database auth.proximity.permit_store...
08-26 10:52:46.078  2128  2128 D a       : Closing database...
08-26 10:52:46.100  6501  6501 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-26 10:52:46.106  6872  6872 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-26 10:52:46.106  6872  6872 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
,08-26 10:52:46.106  6872  6872 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-26 10:52:46.112  6844  6844 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 10:52:46.123  6844  6844 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 10:52:46.135  6918  6918 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 10:52:46.135  6918  6918 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-26 10:52:46.139  6918  6918 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-26 10:52:46.148  6501  6501 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 10:52:46.154  6872  6872 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,08-26 10:52:46.154  6872  6872 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-26 10:52:46.154  6872  6872 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-26 10:52:46.162  6844  6844 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 10:52:46.173  6844  6844 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-26 10:52:46.187  6918  6918 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-26 10:52:46.189  6918  6918 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 10:52:46.191  6918  6918 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-26 10:52:46.198  6501  6501 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 10:52:46.207  6872  6872 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-26 10:52:46.207  6872  6872 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-26 10:52:46.208  6872  6872 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-26 10:52:46.217  6844  6844 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 10:52:46.227  1036  1440 E WifiStateMachine:  InitialState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-972216301] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-26 10:52:46.228  6844  6844 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 10:52:46.230  1036  1440 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-972216299] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-26 10:52:46.242  6918  6918 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-26 10:52:46.243  6918  6918 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 10:52:46.248  6918  6918 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-26 10:52:46.261  6872  6872 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-26 10:52:46.267  6844  6844 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-26 10:52:46.273  6957  7422 W FormManager: Network not available. Please check & try again.
08-26 10:52:46.274  6957  7423 V FormManager: Network unavailable.
,08-26 10:52:46.278  6957  7423 V FormManager: Network unavailable.
08-26 10:52:46.279  6844  6844 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 10:52:46.302  4298  4298 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-26 10:52:46.303  4298  4298 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-26 10:52:46.306  4298  4298 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-26 10:52:46.310  4298  4298 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 10:52:46.320  4298  7424 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-26 10:52:46.326  6872  6872 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-26 10:52:46.326  4298  7425 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-26 10:52:46.326  6872  6872 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-26 10:52:46.326  6872  6872 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-26 10:52:46.327  4298  7425 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-26 10:52:46.332  6844  6844 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-26 10:52:46.344  6957  7427 W FormManager: Network not available. Please check & try again.
,08-26 10:52:46.349  6957  7428 V FormManager: Network unavailable.
08-26 10:52:46.351  6844  6844 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 10:52:46.352  6957  7428 V FormManager: Network unavailable.
08-26 10:52:46.370  2128  2128 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,08-26 10:52:46.487  1036  1495 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-26 10:52:46.493  1036  1112 D Tethering: MasterInitialState.processMessage what=3
08-26 10:52:46.508  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 10:52:46.508  1036  1095 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-26 10:52:46.513  5758  5758 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-26 10:52:46.514  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 10:52:46.514  6501  6501 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-26 10:52:46.516  1036  1095 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 10:52:46.516  6501  6530 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-26 10:52:46.532  2128  2128 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-26 10:52:46.542  7067  7067 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-26 10:52:46.542  7067  7067 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-26 10:52:46.543  7067  7067 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-26 10:52:46.543  7067  7067 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-26 10:52:46.544  7067  7067 I AppUp4:CustModeStarterReceiver: onReceive
,08-26 10:52:46.549  7067  7067 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@3f8f71b5
08-26 10:52:46.549  7067  7067 D AppUp4:CustFacade: isCustomizationCompleted : false
08-26 10:52:46.549  7067  7067 D AppUp4:CustFacade: isPhone : true
08-26 10:52:46.550  7067  7067 D AppUp4:CustModeStarterReceiver: begin check event
08-26 10:52:46.550  7067  7067 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-26 10:52:46.554  4298  4298 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-26 10:52:46.554  4298  4298 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-26 10:52:46.556  4298  4298 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 10:52:46.558  4298  4298 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-26 10:52:46.565  4298  7429 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-26 10:52:46.566  7102  7102 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-26 10:52:46.570  4298  7430 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-26 10:52:46.570  4298  7430 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-26 10:52:46.594  6957  7433 W FormManager: Network not available. Please check & try again.
,08-26 10:52:46.596  7102  7432 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 10:52:46.602  3460  3460 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-26 10:52:46.602  3460  3460 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
,08-26 10:52:46.603  3460  3460 I LgeMiscReceiver: networkInfo.isConnected() = true
08-26 10:52:46.603  3460  3460 D PhoneState: setPdpRejectCasuse : false
08-26 10:52:46.608  7138  7138 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-26 10:52:46.608  7138  7138 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-26 10:52:46.611  6957  7434 V FormManager: Network unavailable.
08-26 10:52:46.618  6957  7434 V FormManager: Network unavailable.
08-26 10:52:46.620  7203  7203 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 10:52:46
,08-26 10:52:46.622  7203  7203 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
,08-26 10:52:46.622  7203  7203 D Weather.Utils: 2 : All the weather widget is gone.
,08-26 10:52:46.622  7203  7203 D UpdateThreadPoolManager: 2 : This is isUpdating : false
,08-26 10:52:46.623  7203  7203 D WeatherAncestor: connectivity changed - connection : true
08-26 10:52:46.623  7203  7203 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@ea29bbb
,08-26 10:52:46.626  7203  7203 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
,08-26 10:52:46.626  7203  7203 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-26 10:52:46.626  7203  7203 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-26 10:52:46.626  7203  7203 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
,08-26 10:52:46.626  7203  7203 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 10:52:46
08-26 10:52:47.571  1036  2014 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 10:52:47.572  1036  2014 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-26 10:52:47.601  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-26 10:52:47.603  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-26 10:52:47.603  1036  1036 D Ulp_jni : JNI:system_update. Event-4
,08-26 10:52:47.605  1036  1112 D BluetoothManagerService: Message: 1
08-26 10:52:47.605  1036  1112 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
,08-26 10:52:47.634  1036  1112 D BluetoothManagerService: Message: 20
08-26 10:52:47.634  1036  1112 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4358dc3:true
,08-26 10:52:47.638  6997  6997 D BluetoothAdapterState: make
08-26 10:52:47.643  6997  6997 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-26 10:52:47.643  6997  6997 I bluedroid-qcom: init
08-26 10:52:47.644  6997  7443 I BluetoothAdapterState: Entering OffState
08-26 10:52:47.645  6997  6997 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-26 10:52:47.645  6997  6997 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-26 10:52:47.645  6997  6997 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-26 10:52:47.645  6997  6997 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-26 10:52:47.645  6997  6997 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-26 10:52:47.647  6997  6997 I bluedroid-qcom: get_profile_interface socket
08-26 10:52:47.647  6997  6997 I bluedroid-qcom: get_profile_interface map_client
,08-26 10:52:47.653  7446  7446 W bdaddr_loader: type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 10:52:47.653  7446  7446 W bdaddr_loader: type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 10:52:47.666  7446  7446 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-26 10:52:47.666  7446  7446 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-26 10:52:47.666  7446  7446 I LGFTMITEM: [GET_FTM][id=8], offset=16384
,08-26 10:52:47.670  6997  7447 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-26 10:52:47.673  1036  1036 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-26 10:52:47.673  1036  1112 D BluetoothManagerService: Message: 40
08-26 10:52:47.673  1036  1112 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-26 10:52:47.674  6997  7012 I bluedroid-qcom: config_hci_snoop_log
08-26 10:52:47.676  7446  7446 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-26 10:52:47.677  1036  1112 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-26 10:52:47.677  1036  1112 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-26 10:52:47.679  1036  1495 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-26 10:52:47.684  7446  7446 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-26 10:52:47.684  7446  7446 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-26 10:52:47.689  1036  1495 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-26 10:52:47.696  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 10:52:47.700  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 10:52:47.712  6997  7447 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-26 10:52:47.718  6997  7443 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-26 10:52:47.718  1036  1112 D Tethering: MasterInitialState.processMessage what=3
08-26 10:52:47.718  1036  1112 D Tethering: MasterInitialState.processMessage what=3
08-26 10:52:47.743  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 10:52:47.746  6501  6501 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-26 10:52:47.751  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 10:52:47.754  6997  7447 D BluetoothAdapterProperties: Name is: G3
08-26 10:52:47.756  1036  1381 V AlarmManager: ELAPSED_WAKEUP set : Alarm{bd9431f type 2 when 126948 com.google.android.gms} when 126948
08-26 10:52:47.758  6997  7443 D BluetoothAdapterProperties: Setting state to 11
08-26 10:52:47.759  6997  7443 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-26 10:52:47.759  1036  1036 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-26 10:52:47.759  1036  1036 D BluetoothManagerService: Stored Bluetooth name: G3
08-26 10:52:47.762  6501  6530 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-26 10:52:47.763  1036  1095 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-26 10:52:47.767  1036  1112 D BluetoothManagerService: Message: 60
08-26 10:52:47.767  1036  1112 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-26 10:52:47.767  1036  1112 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
,08-26 10:52:47.774  1943  1943 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-26 10:52:47.775  6844  6844 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-26 10:52:47.775  1604  1604 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-26 10:52:47.777  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 10:52:47.779  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 10:52:47.783  6997  7443 I LGBluetoothServiceJni: classInitNative: succeeds
08-26 10:52:47.785  1036  1095 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-26 10:52:47.786  1036  1095 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 10:52:47.786  1036  1095 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 10:52:47.788  6997  6997 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-26 10:52:47.789  6997  6997 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 10:52:47.789  6997  6997 V BluetoothPbapReceiver: ***********state = 11
08-26 10:52:47.790  6997  7443 D BluetoothBondStateMachine: make
,08-26 10:52:47.791  5758  5758 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-26 10:52:47.794  2128  2128 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-26 10:52:47.795  6997  7443 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ea29bbb
08-26 10:52:47.796  6997  7466 I BluetoothBondStateMachine: StableState(): Entering Off State
08-26 10:52:47.796  6997  7443 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-26 10:52:47.796  6997  7443 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ea29bbb
08-26 10:52:47.796  6997  7443 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-26 10:52:47.796  6997  7443 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-26 10:52:47.803  6997  7443 E BluetoothAdapterService: File transfer profiles supported!!
,08-26 10:52:47.846  1036  1978 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7468 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-26 10:52:47.852  6997  7443 E BluetoothAdapterService: File transfer profiles supported!!
08-26 10:52:47.853  6997  6997 D HeadsetService: Received start request. Starting profile...
08-26 10:52:47.854  6997  6997 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-26 10:52:47.854  6997  6997 D LGBluetoothHfpAdapter: Version 1.6
08-26 10:52:47.856  5758  5758 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-26 10:52:47.857  6997  6997 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-26 10:52:47.858  6997  6997 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-26 10:52:47.858  6997  6997 D HeadsetStateMachine: make
08-26 10:52:47.861  6997  7443 E BluetoothAdapterService: File transfer profiles supported!!
,08-26 10:52:47.871  6997  7443 E BluetoothAdapterService: File transfer profiles supported!!
08-26 10:52:47.879  2128  2128 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-26 10:52:47.884  6997  7443 E BluetoothAdapterService: File transfer profiles supported!!
08-26 10:52:47.889  7067  7067 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-26 10:52:47.889  7067  7067 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-26 10:52:47.889  7067  7067 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-26 10:52:47.889  7067  7067 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-26 10:52:47.892  7067  7067 I AppUp4:CustModeStarterReceiver: onReceive
08-26 10:52:47.892  6997  7443 E BluetoothAdapterService: File transfer profiles supported!!
,08-26 10:52:47.893  6997  6997 D LgDataFeature: LgDataFeature() Constructor: none
08-26 10:52:47.893  6997  6997 D LgDataFeature: LgDataFeature() Constructor Done, null
08-26 10:52:47.900  7067  7067 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@3f8f71b5
08-26 10:52:47.900  7067  7067 D AppUp4:CustFacade: isCustomizationCompleted : false
,08-26 10:52:47.900  7067  7067 D AppUp4:CustFacade: isPhone : true
08-26 10:52:47.900  7067  7067 D AppUp4:CustModeStarterReceiver: begin check event
08-26 10:52:47.900  7067  7067 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-26 10:52:47.902  6997  7443 E BluetoothAdapterService: File transfer profiles supported!!
08-26 10:52:47.905  6997  6997 D HeadsetStateMachine: max_hf_connections = 1
08-26 10:52:47.905  6997  6997 I bluedroid-qcom: get_profile_interface handsfree
08-26 10:52:47.907  4298  4298 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-26 10:52:47.907  4298  4298 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-26 10:52:47.907  6997  6997 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-26 10:52:47.908   329  1399 V AudioPolicyService: registerClient() client 0xb57f5900, uid 1002
08-26 10:52:47.908   329  2193 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-26 10:52:47.908   329  2193 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-26 10:52:47.908   329  2193 V AudioPolicyManagerEx: getOutput() returns output 2
,08-26 10:52:47.908  6997  6997 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-26 10:52:47.909   329  1400 V AudioFlinger: registerClient() client 0xb1032070, pid 6997
08-26 10:52:47.909   329  1394 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-26 10:52:47.909   329  1394 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-26 10:52:47.909  1604  2559 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-26 10:52:47.909  1604  2559 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-26 10:52:47.909   329  1395 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-26 10:52:47.909   329  1395 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-26 10:52:47.909  3460  3476 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-26 10:52:47.909  3460  3476 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-26 10:52:47.909  1854  2466 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-26 10:52:47.909  1854  2466 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-26 10:52:47.910  1854  2466 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-26 10:52:47.910  3460  3475 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-26 10:52:47.910  1854  2466 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-26 10:52:47.910  3460  3475 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-26 10:52:47.910  1036  1052 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-26 10:52:47.910  1036  1052 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-26 10:52:47.910  1036  1052 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-26 10:52:47.910  1036  1052 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-26 10:52:47.910  6997  7013 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-26 10:52:47.910  6997  7013 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-26 10:52:47.910  6997  7013 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-26 10:52:47.910  6997  7013 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-26 10:52:47.910  6997  6997 V ToneGenerator: Create Track: 0xb4928a80
08-26 10:52:47.910  1604  1620 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-26 10:52:47.910  6997  6997 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-26 10:52:47.910  1604  1620 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-26 10:52:47.910  6997  6997 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-26 10:52:47.911   329   329 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-26 10:52:47.911   329   329 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-26 10:52:47.911   329   329 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-26 10:52:47.911   329   329 V AudioPolicyManagerEx: getOutput() returns output 2
08-26 10:52:47.912   329  1399 I AudioFlinger: isAudioPlaybackHookOn() false
08-26 10:52:47.912   329  2193 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-26 10:52:47.912   329  2193 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-26 10:52:47.912   329  2193 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-26 10:52:47.912   329  2193 V AudioPolicyManagerEx: getOutput() returns output 2
08-26 10:52:47.912  6997  6997 V AudioSystem: getLatency() output 2, latency 50
08-26 10:52:47.912  6997  6997 V AudioSystem: getFrameCount() output 2, frameCount 960
08-26 10:52:47.912  6997  6997 V AudioTrack: createTrack_l() output 2 afLatency 50
08-2,6 10:52:47.913   329  1400 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-26 10:52:47.913   329  1400 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-26 10:52:47.913   329  1400 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-26 10:52:47.913   329  1400 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-26 10:52:47.913   329  1400 V AudioFlinger: createTrack() lSessionId: 22
08-26 10:52:47.914  6997  6997 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-26 10:52:47.914   329  1400 V AudioFlinger: acquiring 22 from 6997, for 6997
08-26 10:52:47.914   329  1400 V AudioFlinger:  added new entry for 22
08-26 10:52:47.914  6997  6997 V ToneGenerator: ToneGenerator INIT OK, time: 127166
08-26 10:52:47.914  6997  6997 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ea29bbb
08-26 10:52:47.915  6997  7483 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-26 10:52:47.915  6997  6997 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ea29bbb
08-26 10:52:47.916  6997  7443 V LGMDMManager: Create singleton instance
08-26 10:52:47.917  6997  6997 D A2dpService: Received start request. Starting profile...
08-26 10:52:47.917  6997  7483 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-26 10:52:47.918  6997  6997 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-26 10:52:47.918  6997  7483 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-26 10:52:47.919  6997  6997 V Avrcp   : make
08-26 10:52:47.920  6997  6997 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-26 10:52:47.920  6997  7483 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-26 10:52:47.920  6997  6997 I bluedroid-qcom: get_profile_interface avrcp
08-26 10:52:47.920   329  2194 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 6997
08-26 10:52:47.920   329  2194 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-26 10:52:47.920   329  2194 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-26 10:52:47.920   329  2194 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-26 10:52:47.920   329  2194 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-26 10:52:47.920   329  2194 V voice   : voice_set_parameters: exit with code(0)
08-26 10:52:47.920   329  2194 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-26 10:52:47.920   329  2194 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-26 10:52:47.920   329  2194 V msm8974_platform: platform_set_parameters: exit with code(0)
08-26 10:52:47.920   329  2194 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-26 10:52:47.920   329  2194 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-26 10:52:47.920   329  2194 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
,08-26 10:52:47.921  4298  4298 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 10:52:47.924  6997  7483 V ToneGenerator: ToneGenerator destructor
08-26 10:52:47.924  6997  7483 V ToneGenerator: stopTone
08-26 10:52:47.924  6997  7483 V ToneGenerator: Delete Track: 0xb4928a80
08-26 10:52:47.924  4298  4298 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 10:52:47.924  6997  7483 V AudioTrack: ~AudioTrack, releasing session id from 6997 on behalf of 6997
08-26 10:52:47.924   329  1399 V AudioPolicyService: AudioCommandThread() adding release output 2
08-26 10:52:47.924   329  1399 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-26 10:52:47.924   329  1399 V AudioFlinger: PlaybackThread::Track destructor
08-26 10:52:47.924   329  1258 V AudioPolicyService: AudioCommandThread() waking up
,08-26 10:52:47.924   329  1400 V AudioFlinger: releasing 22 from 6997 for 6997
08-26 10:52:47.924   329  1400 V AudioFlinger:  decremented refcount to 0
08-26 10:52:47.924   329  1258 V AudioPolicyService: AudioCommandThread() processing release output 2
08-26 10:52:47.924   329  1400 V AudioFlinger: purging stale effects
08-26 10:52:47.924   329  1399 V AudioFlinger: removeClient_l() pid 6997, calling pid 329
08-26 10:52:47.924   329  1258 V AudioPolicyManager: releaseOutput() 2
08-26 10:52:47.924   329  1258 V AudioPolicyService: AudioCommandThread() going to sleep
08-26 10:52:47.929  6997  7443 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-26 10:52:47.931  7102  7102 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-26 10:52:47.933  6997  6997 V AudioManager: registerRemoteController: size of Media player list: 0
08-26 10:52:47.934  4298  7488 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-26 10:52:47.938  6997  6997 E AudioManager: No RCC entry present to update
08-26 10:52:47.938  6997  6997 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-26 10:52:47.940  4298  7490 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-26 10:52:47.940  4298  7490 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-26 10:52:47.942  6997  6997 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-26 10:52:47.943  6997  6997 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-26 10:52:47.943  6997  6997 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-26 10:52:47.948  6997  6997 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,08-26 10:52:47.989  7102  7493 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-26 10:52:47.993  3460  3460 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-26 10:52:47.993  3460  3460 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-26 10:52:47.994  3460  3460 I LgeMiscReceiver: networkInfo.isConnected() = false
08-26 10:52:47.994  7468  7468 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-26 10:52:47.994  7468  7468 W LG Account v2.2: No ProfileInfo entries
08-26 10:52:47.994  7468  7468 I LG Account v2.2: isEnabled: false
08-26 10:52:47.995  6957  7494 W FormManager: Network not available. Please check & try again.
08-26 10:52:47.995  7468  7468 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-26 10:52:47.995  7468  7468 I Feature : [Lifetracker]Country: EU
08-26 10:52:47.995  7468  7468 I Feature : [Lifetracker]Operator: OPEN
08-26 10:52:47.995  7468  7468 I Feature : [Lifetracker]Ranking support: false
08-26 10:52:47.995  7468  7468 I Feature : [Lifetracker]Comfort support: false
08-26 10:52:47.995  7468  7468 I Feature : [Lifetracker]Accessory: true
08-26 10:52:47.996  7468  7468 I Feature : [Lifetracker]Health device: true
08-26 10:52:47.996  7468  7468 I Feature : [Lifetracker]Extra Pedometer: false
08-26 10:52:47.996  7468  7468 I Feature : [Lifetracker]Blood glucose device: false
08-26 10:52:47.996  7468  7468 I Feature : [Lifetracker]Device Number: 3
08-26 10:52:47.997  7138  7138 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-26 10:52:47.998  7138  7138 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-26 10:52:47.998  6957  7495 V FormManager: Network unavailable.
08-26 10:52:48.014  6957  7495 V FormManager: Network unavailable.
,08-26 10:52:48.017  6844  6844 D BluetoothPermissionRequest: onReceive
08-26 10:52:48.021  7203  7203 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 10:52:48
08-26 10:52:48.023  7203  7203 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-26 10:52:48.023  7203  7203 D Weather.Utils: 2 : All the weather widget is gone.
08-26 10:52:48.023  7203  7203 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-26 10:52:48.023  7203  7203 D WeatherAncestor: connectivity changed - connection : true
08-26 10:52:48.024  7203  7203 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@ea29bbb
08-26 10:52:48.024  7203  7203 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-26 10:52:48.024  7203  7203 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-26 10:52:48.024  7203  7203 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-26 10:52:48.024  7203  7203 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-26 10:52:48.025  7203  7203 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 10:52:48
08-26 10:52:48.026  6844  6844 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-26 10:52:48.037  1036  1889 V SIM_STK : Menu title from STK is T-Mobile
08-26 10:52:48.037  1036  1889 V SIM_STK : Menu title from STK is T-Mobile
,08-26 10:52:48.049  6501  6501 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-26 10:52:48.050  6501  6530 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-26 10:52:48.065  2128  2128 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-26 10:52:48.074  7067  7067 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-26 10:52:48.074  7067  7067 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-26 10:52:48.074  7067  7067 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-26 10:52:48.074  7067  7067 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-26 10:52:48.076  7067  7067 I AppUp4:CustModeStarterReceiver: onReceive
,08-26 10:52:48.079  7067  7067 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@3f8f71b5
08-26 10:52:48.079  7067  7067 D AppUp4:CustFacade: isCustomizationCompleted : false
08-26 10:52:48.079  7067  7067 D AppUp4:CustFacade: isPhone : true
08-26 10:52:48.080  7067  7067 D AppUp4:CustModeStarterReceiver: begin check event
08-26 10:52:48.080  7067  7067 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-26 10:52:48.083  4298  4298 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-26 10:52:48.083  4298  4298 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-26 10:52:48.085  4298  4298 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 10:52:48.086  4298  4298 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 10:52:48.089  1036  1053 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-26 10:52:48.092  7102  7102 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-26 10:52:48.093  4298  7499 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-26 10:52:48.094  6997  6997 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-26 10:52:48.096  4298  7500 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-26 10:52:48.096  4298  7500 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-26 10:52:48.097  6997  6997 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-26 10:52:48.097  6997  6997 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-26 10:52:48.097  6997  6997 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-26 10:52:48.097  6997  6997 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-26 10:52:48.097  6997  6997 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-26 10:52:48.097  6997  6997 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-26 10:52:48.097  6997  6997 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-26 10:52:48.097  6997  6997 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-26 10:52:48.097  6997  6997 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-26 10:52:48.097  6997  6997 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-26 10:52:48.098  6997  6997 I BluetoothA2dpServiceJni: classInitNative
08-26 10:52:48.098  6997  6997 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-26 10:52:48.098  6997  6997 D A2dpStateMachine: make
08-26 10:52:48.099  6997  6997 I bluedroid-qcom: get_profile_interface a2dp
08-26 10:52:48.099  6997  7502 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-26 10:52:48.101  6997  6997 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-26 10:52:48.101  6997  6997 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
,08-26 10:52:48.102  6997  6997 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ea29bbb
08-26 10:52:48.103  6997  6997 I BluetoothHidServiceJni: classInitNative: succeeds
08-26 10:52:48.104  6997  7501 D A2dpStateMachine: Enter Disconnected: -2
08-26 10:52:48.105  6997  6997 D HidService: Received start request. Starting profile...
08-26 10:52:48.105  6997  6997 I bluedroid-qcom: get_profile_interface hidhost
08-26 10:52:48.105  6997  6997 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ea29bbb
08-26 10:52:48.106  6997  6997 I BluetoothHealthServiceJni: classInitNative: succeeds
08-26 10:52:48.107  6997  6997 D HealthService: Received start request. Starting profile...
08-26 10:52:48.108  7102  7505 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 10:52:48.109  6997  6997 I bluedroid-qcom: get_profile_interface health
08-26 10:52:48.109  6997  6997 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-26 10:52:48.109  6997  6997 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ea29bbb
08-26 10:52:48.110  6997  6997 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-26 10:52:48.112  6997  6997 D PanService: Received start request. Starting profile...
08-26 10:52:48.112  6997  6997 D BluetoothPanServiceJni: initializeNative(L110): pan
08-26 10:52:48.112  6997  6997 I bluedroid-qcom: get_profile_interface pan
08-26 10:52:48.115  3460  3460 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-26 10:52:48.115  3460  3460 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-26 10:52:48.115  3460  3460 I LgeMiscReceiver: networkInfo.isConnected() = false
,08-26 10:52:48.118  7138  7138 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-26 10:52:48.118  7138  7138 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-26 10:52:48.120  6997  6997 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-26 10:52:48.120  6997  6997 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ea29bbb
08-26 10:52:48.120  6957  7506 W FormManager: Network not available. Please check & try again.
08-26 10:52:48.121  6997  6997 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-26 10:52:48.126  7203  7203 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 10:52:48
08-26 10:52:48.127  7203  7203 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-26 10:52:48.127  7203  7203 D Weather.Utils: 2 : All the weather widget is gone.
08-26 10:52:48.127  6957  7510 V FormManager: Network unavailable.
08-26 10:52:48.127  7203  7203 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-26 10:52:48.127  7203  7203 D WeatherAncestor: connectivity changed - connection : true
08-26 10:52:48.127  6997  6997 D BtGatt.DebugUtils: handleDebugAction() action=null
08-26 10:52:48.127  7203  7203 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@ea29bbb
08-26 10:52:48.128  6997  6997 D BtGatt.GattService: Received start request. Starting profile...
08-26 10:52:48.128  6997  6997 D BtGatt.GattService: start()
08-26 10:52:48.128  6997  6997 I bluedroid-qcom: get_profile_interface gatt
08-26 10:52:48.128  7203  7203 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-26 10:52:48.128  7203  7203 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-26 10:52:48.128  7203  7203 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-26 10:52:48.128  7203  7203 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-26 10:52:48.128  7203  7203 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 10:52:48
08-26 10:52:48.128  6997  6997 D BtGatt.AdvertiseManager: advertise manager created
,08-26 10:52:48.138  6957  7510 V FormManager: Network unavailable.
08-26 10:52:48.144  6997  6997 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ea29bbb
,08-26 10:52:48.145  6997  6997 D HeadsetStateMachine: Proxy object connected
08-26 10:52:48.146  6997  6997 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-26 10:52:48.146  6997  6997 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-26 10:52:48.148   324  7515 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-26 10:52:48.148  6997  6997 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ea29bbb
08-26 10:52:48.148  6918  6918 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
08-26 10:52:48.148  6997  6997 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-26 10:52:48.149  6918  6918 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:5121
08-26 10:52:48.149  1036  1110 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-26 10:52:48.150  6997  6997 V BluetoothMapService: BluetoothMapBinder()
08-26 10:52:48.150  6997  6997 D BluetoothMapService: Received start request. Starting profile...
08-26 10:52:48.150  6997  6997 D BluetoothMapService: start()
08-26 10:52:48.156  6997  6997 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-26 10:52:48.156  6997  6997 D BluetoothMapEmailAppObserver: createReceiver()
,08-26 10:52:48.157  6997  6997 D BluetoothMapEmailAppObserver: initObservers()
08-26 10:52:48.157  6997  6997 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-26 10:52:48.165  6997  6997 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ea29bbb
08-26 10:52:48.167  6997  7483 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-26 10:52:48.168  6997  7483 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-26 10:52:48.168  6997  7483 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-26 10:52:48.170  6997  6997 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-26 10:52:48.174  6997  6997 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-26 10:52:48.177  6997  6997 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-26 10:52:48.180  6997  6997 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-26 10:52:48.185  6997  6997 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-26 10:52:48.185  6997  6997 V PanService: [BTUI] SIM Extra State :ABSENT
08-26 10:52:48.188  6997  6997 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
,08-26 10:52:48.188  6997  6997 V BluetoothMapService: Handler(): got msg=1
08-26 10:52:48.189  6997  7443 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-26 10:52:48.189  6997  7443 I bluedroid-qcom: enable
08-26 10:52:48.190  6997  7443 I bt_hci_bdroid: init
08-26 10:52:48.190  6997  7516 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-26 10:52:48.190  6997  7516 I bt-btu  : btu_task pending for preload complete event
08-26 10:52:48.191  6997  7443 I bt_vendor: bt-vendor : init
08-26 10:52:48.191  6997  7443 I bt_vendor: bt-vendor : get_bt_soc_type
08-26 10:52:48.191  6997  7443 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-26 10:52:48.191  6997  7443 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-26 10:52:48.191  6997  6997 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-26 10:52:48.191  6997  7443 D bt_userial_mct: userial_init
08-26 10:52:48.191  6997  7443 D bt_hci_bdroid: set_power 1
08-26 10:52:48.191  6997  7443 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-26 10:52:48.191  6997  7443 I bt_vendor: Starting hciattach daemon
08-26 10:52:48.191  6997  7443 I bt_vendor: try to set true
08-26 10:52:48.183  7519  7519 W sh      : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 10:52:48.194  6997  6997 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-26 10:52:48.183  7519  7519 W sh      : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-26 10:52:48.194  6997  6997 V BluetoothSapReceiver: SapReceiver onReceive 
,08-26 10:52:48.194  6997  6997 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 10:52:48.194  6997  6997 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-26 10:52:48.216  7520  7520 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-26 10:52:48.323  7526  7526 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-26 10:52:48.350  7527  7527 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-26 10:52:48.385  7529  7529 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-26 10:52:48.416  7530  7530 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-26 10:52:48.446  7531  7531 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-26 10:52:48.459  7535  7535 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
08-26 10:52:48.495  7537  7537 I libmdmdetect: ESOC framework not supported
,08-26 10:52:48.496  7537  7537 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-26 10:52:48.504  7537  7537 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-26 10:52:48.504  7537  7537 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-26 10:52:48.504  7537  7537 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-26 10:52:48.504  7537  7537 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-26 10:52:48.504  7537  7537 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-26 10:52:48.504  7537  7537 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-26 10:52:48.504  7537  7537 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-26 10:52:48.545  7537  7538 E QC-QMI  : qmi_client [7537] 14: failed to locate client data
08-26 10:52:48.546   476   476 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-26 10:52:48.546   476   476 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
,08-26 10:52:48.610  7539  7539 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-26 10:52:48.627  7540  7540 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-26 10:52:48.695  6997  7443 I bt_vendor: bluetooth satus is on
08-26 10:52:48.695  6997  7443 D bt_hci_bdroid: preload
08-26 10:52:48.696  6997  7518 D bt_userial_mct: userial_open(port:0)
08-26 10:52:48.696  6997  7518 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-26 10:52:48.700  6997  7518 I bt_vendor: Done intiailizing UART
08-26 10:52:48.704  6997  7518 I bt_vendor: Done intiailizing UART
08-26 10:52:48.704  6997  7518 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-26 10:52:48.705  6997  7518 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-26 10:52:48.705  6997  7516 I bt-btu  : btu_task received preload complete event
08-26 10:52:48.705  6997  7542 D bt_userial_mct: Entering userial_read_thread()
08-26 10:52:48.706  6997  7516 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-26 10:52:48.707  6997  7516 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-26 10:52:48.714  6997  7516 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
,08-26 10:52:48.723  6997  7516 I         : BTE_InitTraceLevels -- TRC_HCI
,08-26 10:52:48.724  6997  7516 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-26 10:52:48.724  6997  7516 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-26 10:52:48.724  6997  7516 I         : BTE_InitTraceLevels -- TRC_AVDT
08-26 10:52:48.724  6997  7516 I         : BTE_InitTraceLevels -- TRC_AVRC
08-26 10:52:48.724  6997  7516 I         : BTE_InitTraceLevels -- TRC_A2D
08-26 10:52:48.724  6997  7516 I         : BTE_InitTraceLevels -- TRC_BNEP
08-26 10:52:48.724  6997  7516 I         : BTE_InitTraceLevels -- TRC_BTM
08-26 10:52:48.724  6997  7516 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-26 10:52:48.724  6997  7516 I         : BTE_InitTraceLevels -- TRC_GAP
08-26 10:52:48.724  6997  7516 I         : BTE_InitTraceLevels -- TRC_PAN
08-26 10:52:48.724  6997  7516 I         : BTE_InitTraceLevels -- TRC_SDP
08-26 10:52:48.724  6997  7516 I         : BTE_InitTraceLevels -- TRC_GATT
08-26 10:52:48.724  6997  7516 I         : BTE_InitTraceLevels -- TRC_SMP
08-26 10:52:48.724  6997  7516 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-26 10:52:48.724  6997  7516 I         : BTE_InitTraceLevels -- TRC_BTIF
08-26 10:52:48.809  6997  7516 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-26 10:52:48.809  6997  7516 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa01f9061 
08-26 10:52:48.809  6997  7516 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa01f9061 
,08-26 10:52:48.825  6997  7447 E bt-btif : Calling BTA_HhEnable
,08-26 10:52:48.825  6997  7516 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-26 10:52:48.825  6997  7516 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-26 10:52:48.825  6997  7516 W bt-l2cap: L2CAP - L2CA_Register() called fo service_mask
08-26 10:52:48.825  6997  7447 E bt-btif : L2CAP - L2CA_Register() called fo service_mask
08-26 10:52:48.825  6997  7516 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-26 10:52:48.825  6997  7516 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-26 10:52:48.826  6997  7447 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-26 10:52:48.828  1036  1036 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-26 10:52:48.829  1036  1036 D BluetoothManagerService: Stored Bluetooth name: G3
08-26 10:52:48.829  6997  7447 D BluetoothAdapterProperties: Name is: G3
08-26 10:52:48.831  6997  7447 D BluetoothAdapterProperties: Scan Mode:20
08-26 10:52:48.831  6997  7447 D BluetoothAdapterProperties: Discoverable Timeout:120
08-26 10:52:48.832  6997  7447 D bt_hci_bdroid: postload
08-26 10:52:48.832  6997  7518 D bt_hci_bdroid: Used up Tx Cmd credits
08-26 10:52:48.833  6997  7516 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-26 10:52:48.833  6997  7447 D bte_conf: Device ID record 1 : primary
08-26 10:52:48.833  6997  7447 D bte_conf:   vendorId            = 00c4
08-26 10:52:48.833  6997  7447 D bte_conf:   vendorIdSource      = 0001
08-26 10:52:48.833  6997  7447 D bte_conf:   product             = 13a1
08-26 10:52:48.833  6997  7447 D bte_conf:   version             = 1000
08-26 10:52:48.833  6997  7447 D bte_conf:   clientExecutableURL = 
08-26 10:52:48.833  6997  7447 D bte_conf:   serviceDescription  = 
08-26 10:52:48.833  6997  7447 D bte_conf:   documentationURL    = 
08-26 10:52:48.833  6997  7447 D bte_conf: bte_load_did_conf no section named DID2.
08-26 10:52:48.836  6997  7447 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-26 10:52:48.836  6997  7443 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-26 10:52:48.837  6997  7443 D BluetoothAdapterProperties: ScanMode =  20
08-26 10:52:48.837  6997  7443 D BluetoothAdapterProperties: State =  11
08-26 10:52:48.837  6997  7516 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-26 10:52:48.837  6997  7516 W bt-smp  : Plain text(LSB ~ MSB) = dc b1 67 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-26 10:52:48.837  6997  7516 W bt-smp  : Encrypted text(LSB ~ MSB) = 72 6a f8 3d 58 25 57 b2 85 48 5e f5 d1 9c 6d 0f 
08-26 10:52:48.837  6997  7516 W bt-btm  : Stopping oneshot timer
08-26 10:52:48.837  6997  7518 D bt_hci_bdroid: Used up Tx Cmd credits
08-26 10:52:48.833  7544  7544 W sh      : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-26 10:52:48.838  6997  7443 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
,08-26 10:52:48.839  6997  7518 D bt_hci_bdroid: Used up Tx Cmd credits
08-26 10:52:48.839  6997  7443 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-26 10:52:48.839  6997  7443 D BluetoothAdapterProperties: Setting state to 12
08-26 10:52:48.839  6997  7443 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-26 10:52:48.843  6997  7447 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-26 10:52:48.833  7544  7544 W sh      : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 10:52:48.850  6997  7518 D bt_hci_bdroid: Used up Tx Cmd credits
08-26 10:52:48.855  1036  1112 D BluetoothManagerService: Message: 60
08-26 10:52:48.855  1036  1112 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-26 10:52:48.856  6997  7443 I BluetoothAdapterState: Entering On State
08-26 10:52:48.858  6997  7542 E bt_mct  : hci lib postload completed
,08-26 10:52:48.860  6997  7447 D BluetoothAdapterProperties: Discoverable Timeout:120
08-26 10:52:48.860  6997  7447 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-26 10:52:48.862  6997  7443 D LGBluetoothServiceAdapter: [BTUI] OnState
08-26 10:52:48.863  6997  7443 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-26 10:52:48.863  6997  7443 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-26 10:52:48.863  6997  7443 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-26 10:52:48.855  1036  1112 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
08-26 10:52:48.865  1854  4180 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 10:52:48.870  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 10:52:48.870  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 10:52:48.870  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 10:52:48.870  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 10:52:48.870  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 10:52:48.870  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 10:52:48.870  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 10:52:48.870  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 10:52:48.873  6692  6692 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 10:52:48.877  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 10:52:48.877  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 10:52:48.877  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 10:52:48.877  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 10:52:48.877  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 10:52:48.877  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 10:52:48.877  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 10:52:48.877  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 10:52:48.880  6997  7516 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-26 10:52:48.880  6997  7516 W bt-smp  : Plain text(LSB ~ MSB) = 69 05 64 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-26 10:52:48.880  6997  7516 W bt-smp  : Encrypted text(LSB ~ MSB) = 6e b0 4a 16 e6 dd cd 2f a4 0b 6f 81 e3 82 f5 58 
08-26 10:52:48.880  6997  7516 W bt-btm  : Stopping oneshot timer
08-26 10:52:48.881  6692  6692 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 10:52:48.883  1854  1854 D BluetoothHeadset: Proxy object connected
08-26 10:52:48.883  1854  1870 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 10:52:48.886  1854  1854 D BluetoothHeadset: Proxy object connected
08-26 10:52:48.889  6844  6870 D BluetoothPan: onBluetoothStateChange on: true
08-26 10:52:48.889  6844  6870 D BluetoothPan: onBluetoothStateChange call bindService
,08-26 10:52:48.897  1036  1112 D BluetoothA2dp: onBluetoothStateChange: up=true
08-26 10:52:48.899  1036  1036 D BluetoothA2dp: Proxy object connected
08-26 10:52:48.901  6997  7516 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-26 10:52:48.901  6997  7516 W bt-smp  : Plain text(LSB ~ MSB) = ac 78 53 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-26 10:52:48.901  6997  7516 W bt-smp  : Encrypted text(LSB ~ MSB) = f3 66 81 1c 6c d3 95 b0 35 c2 37 bf cb 41 b2 af 
08-26 10:52:48.901  6997  7516 W bt-btm  : Stopping oneshot timer
08-26 10:52:48.906  6997  7443 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
,08-26 10:52:48.911  6844  6871 D BluetoothMap: onBluetoothStateChange: up=true
08-26 10:52:48.915  6997  7516 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-26 10:52:48.915  6997  7516 W bt-smp  : Plain text(LSB ~ MSB) = 98 75 6f 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-26 10:52:48.915  6997  7516 W bt-smp  : Encrypted text(LSB ~ MSB) = f4 eb 86 18 17 8e ed 7e 63 9a bc 2d a6 51 cf 29 
08-26 10:52:48.915  6997  7516 W bt-btm  : Stopping oneshot timer
08-26 10:52:48.917  6844  6871 D BluetoothPbap: onBluetoothStateChange: up=true
08-26 10:52:48.920  6844  6844 D BluetoothPan: BluetoothPAN Proxy object connected
08-26 10:52:48.920  6844  6844 D PanProfile: Bluetooth service connected
,08-26 10:52:48.925  6844  6844 D BluetoothMap: Proxy object connected
08-26 10:52:48.925  6844  6844 D MapProfile: Bluetooth service connected
08-26 10:52:48.925  6844  6844 D BluetoothMap: getConnectedDevices()
08-26 10:52:48.927  6997  7013 V BluetoothMapService: getConnectedDevices()
08-26 10:52:48.928  7553  7553 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-26 10:52:48.930  1854  1869 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 10:52:48.931  1854  1854 D BluetoothHeadset: Proxy object connected
,08-26 10:52:48.932  1036  1112 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 10:52:48.933  1036  1036 D BluetoothHeadset: Proxy object connected
08-26 10:52:48.934  6844  6870 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-26 10:52:48.938  6844  6844 D BluetoothInputDevice: Proxy object connected
08-26 10:52:48.938  6844  6844 D HidProfile: Bluetooth service connected
08-26 10:52:48.939  1036  1112 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-26 10:52:48.939  1036  1112 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-26 10:52:48.940  1036  1036 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-26 10:52:48.940  1036  1112 D BluetoothManagerService: Message: 40
,08-26 10:52:48.940  1036  1112 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-26 10:52:48.942  6997  7516 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-26 10:52:48.942  6997  7516 W bt-smp  : Plain text(LSB ~ MSB) = 82 81 6b 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-26 10:52:48.942  6997  7516 W bt-smp  : Encrypted text(LSB ~ MSB) = 26 97 c7 ac ba e2 1d be 67 7c 00 90 a5 8e 85 82 
08-26 10:52:48.942  6997  7516 W bt-btm  : Stopping oneshot timer
08-26 10:52:48.945  7241  7288 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
08-26 10:52:48.948  1604  1604 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-26 10:52:48.953  1943  1943 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-26 10:52:48.953  1943  2118 D LGBluetoothAPIService: Message: 1
08-26 10:52:48.954  1943  2118 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-26 10:52:48.958  6997  6997 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-26 10:52:48.958  6997  6997 D BluetoothMapService: STATE_ON
08-26 10:52:48.961  6844  6844 D LocalBluetoothProfileManager: Adding local A2DP profile
08-26 10:52:48.964  6692  6692 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
08-26 10:52:48.966  1036  1112 D BluetoothManagerService: Message: 30
08-26 10:52:48.968  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 10:52:48.969  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 10:52:48.970  1943  2118 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
,08-26 10:52:48.970  6844  6844 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-26 10:52:48.978  1036  1112 D BluetoothManagerService: Message: 30
08-26 10:52:48.983  6844  6844 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
,08-26 10:52:48.984  6844  6844 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-26 10:52:48.987  6844  6844 D BluetoothA2dp: Proxy object connected
08-26 10:52:48.987  6997  6997 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ea29bbb
08-26 10:52:48.987  6997  6997 V BluetoothPbapService: Pbap Service onCreate
08-26 10:52:48.988  6997  6997 V BluetoothPbapService: Starting PBAP service
08-26 10:52:48.988  6844  6844 D A2dpProfile: Bluetooth service connected
08-26 10:52:48.989  6997  6997 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-26 10:52:48.989  6997  6997 V BluetoothPbapService: Pbap Service onBind
08-26 10:52:48.990  6844  6844 D BluetoothHeadset: Proxy object connected
08-26 10:52:48.990  6997  6997 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-26 10:52:48.991  6997  6997 V BluetoothPbapService: state: 12
08-26 10:52:48.991  6997  6997 V BluetoothMapService: Handler(): got msg=1
08-26 10:52:48.991  6844  6844 D HeadsetProfile: Bluetooth service connected
08-26 10:52:48.991  6997  6997 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-26 10:52:48.993  6997  7565 D BluetoothMapMasInstance: MAS initSocket()
08-26 10:52:48.993  6997  6997 D LGBluetoothAPIServer: [BTUI] onCreate()
08-26 10:52:48.993  6997  7565 D BluetoothMapMasInstance:   masId = 00
08-26 10:52:48.993  6997  7565 D BluetoothMapMasInstance:   msgTypes = 0e
08-26 10:52:48.993  6997  7565 D BluetoothMapMasInstance:   masName = SMS/MMS
08-26 10:52:48.993  6997  7565 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-26 10:52:48.993  6997  6997 D LGBluetoothAPIServer: [BTUI] onBind()
08-26 10:52:48.994  6997  6997 V BluetoothPbapService: Handler(): got msg=1
08-26 10:52:48.995  1036  1942 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-26 10:52:48.995  6997  6997 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-26 10:52:48.996  6997  6997 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-26 10:52:48.996  6997  6997 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 10:52:48.996  1943  1943 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-26 10:52:48.996  6997  6997 V BluetoothPbapReceiver: ***********state = 12
08-26 10:52:48.996  1943  2118 D LGBluetoothAPIService: Message: 100
08-26 10:52:48.996  1943  2118 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-26 10:52:48.999  6997  7565 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 10:52:49.000  6997  7567 V BluetoothPbapService: Pbap Service initSocket
08-26 10:52:49.001  2128  2128 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-26 10:52:49.001  1036  1052 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 10:52:49.002  6997  7565 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-26 10:52:49.002  6997  7565 V BluetoothMapMasInstance: Succeed to create listening socket 
08-26 10:52:49.002  6997  7565 D BluetoothMapMasInstance: Accepting socket connection...
08-26 10:52:49.003  6997  7447 D BluetoothAdapterProperties: Scan Mode:21
08-26 10:52:49.003  6997  7447 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-26 10:52:49.003  2128  2128 D c       : Getting all permits...
08-26 10:52:49.003  2128  2128 D a       : Opening database...
08-26 10:52:49.005  6844  6844 D DockEventReceiver: finishStartingService: stopping service
08-26 10:52:49.007  2128  2128 D a       : Opening database auth.proximity.permit_store...
,08-26 10:52:49.008  6844  6844 D BluetoothPbap: Proxy object connected
08-26 10:52:49.008  2128  2128 D a       : Closing database...
08-26 10:52:49.008  6844  6844 D PbapServerProfile: Bluetooth service connected
08-26 10:52:49.009  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 10:52:49.010  6997  7567 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 10:52:49.011  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 10:52:49.013  6997  7567 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-26 10:52:49.013  6997  7567 V BluetoothPbapService: Succeed to create listening socket 
08-26 10:52:49.013  6997  7567 V BluetoothPbapService: Accepting socket connection...
08-26 10:52:49.025  6844  6844 D BluetoothPermissionRequest: onReceive
,08-26 10:52:49.027  6844  6844 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-26 10:52:49.030  6844  6844 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-26 10:52:49.032  6997  6997 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-26 10:52:49.034  6997  6997 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-26 10:52:49.042  6997  6997 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-26 10:52:49.074  6997  6997 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,08-26 10:52:49.075  6997  6997 V BtOppService: onCreate
,08-26 10:52:49.079  6997  6997 V BluetoothOppNotification: send message
,08-26 10:52:49.084  6997  6997 V BtOppService: Starting RfcommListener
08-26 10:52:49.092  6997  6997 D BluetoothOppPreference: Dumping Names:  
08-26 10:52:49.092  6997  6997 D BluetoothOppPreference: {}
08-26 10:52:49.092  6997  6997 D BluetoothOppPreference: Dumping Channels:  
08-26 10:52:49.092  6997  6997 D BluetoothOppPreference: {}
08-26 10:52:49.094  6997  6997 V BtOppService: onStartCommand
,08-26 10:52:49.101  6997  7574 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-26 10:52:49.103  6997  6997 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-26 10:52:49.103  6997  7574 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-26 10:52:49.103  6997  6997 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-26 10:52:49.103  6997  7571 V BtOppService: Deleted complete outbound shares, number =  0
08-26 10:52:49.107  6997  6997 V BluetoothOppNotification: new notify threadi!
,08-26 10:52:49.108  6997  7571 V BtOppService: Deleted complete inbound failed shares, number = 0
08-26 10:52:49.109  6997  7571 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
,08-26 10:52:49.111  6997  7571 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@17ce4514 on behalf of 
08-26 10:52:49.111  6997  7574 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3d57b1bd on behalf of 
08-26 10:52:49.112  6997  6997 V BluetoothOppNotification: send delay message
08-26 10:52:49.113  6997  6997 V BtOppService: start RfcommListener
08-26 10:52:49.115  6997  7575 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-26 10:52:49.118  6997  7574 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-26 10:52:49.120  6997  7575 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@bac73b2 on behalf of 
08-26 10:52:49.120  6997  6997 V BtOppService: RfcommListener started
08-26 10:52:49.121  6997  6997 V BtOppService: ContentObserver received notification
,08-26 10:52:49.124  6997  7576 V BtOppRfcommListener: Starting RFCOMM listener....
08-26 10:52:49.125  6997  7575 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-26 10:52:49.126  1036  1052 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-26 10:52:49.128  6997  7576 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 10:52:49.130  6997  7575 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-26 10:52:49.130  6997  7577 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-26 10:52:49.130  6997  7577 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-26 10:52:49.130  6997  7576 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=78 mFd=75
08-26 10:52:49.130  6997  7576 V BtOppRfcommListener: Started RFCOMM listener....
08-26 10:52:49.131  6997  7576 I BtOppRfcommListener: Accept thread started.
,08-26 10:52:49.131  6997  7576 V BtOppRfcommListener: Accepting connection...
08-26 10:52:49.133  6997  7577 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3159af03 on behalf of 
08-26 10:52:49.133  6997  7577 V BluetoothOppNotification: update too frequent, put in queue
08-26 10:52:49.134  6997  7575 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@35d49e80 on behalf of 
08-26 10:52:49.135  6997  7577 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
,08-26 10:52:49.138  6997  7575 V BluetoothOppNotification: outbound: succ-0  fail-0
08-26 10:52:49.139  6997  7575 V BluetoothOppNotification: outbound notification was removed.
08-26 10:52:49.139  6997  7575 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-26 10:52:49.141  6997  7575 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@ad2acb9 on behalf of 
08-26 10:52:49.142  6997  7575 V BluetoothOppNotification: inbound: succ-0  fail-0
08-26 10:52:49.144  6997  7575 V BluetoothOppNotification: inbound notification was removed.
08-26 10:52:49.144  6997  7575 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-26 10:52:49.144  6997  6997 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ea29bbb
08-26 10:52:49.144  6997  6997 V BluetoothFtpService: Ftp Service onCreate
08-26 10:52:49.144  6997  6997 I BluetoothFtpService: Ftp Service onCreate
08-26 10:52:49.145  6997  6997 V BluetoothFtpService: Ftp Service onStartCommand
08-26 10:52:49.145  6997  6997 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-26 10:52:49.145  6997  6997 V BluetoothFtpService: Starting Listening on sockets
08-26 10:52:49.145  6997  6997 V BtOppService: ContentObserver received notification
08-26 10:52:49.145  6997  7575 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3f3e385f on behalf of 
08-26 10:52:49.145  6997  6997 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-26 10:52:49.146  6997  6997 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-26 10:52:49.146  6997  6997 V BluetoothSapReceiver: SapReceiver onReceive 
08-26 10:52:49.146  6997  6997 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 10:52:49.146  6997  6997 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-26 10:52:49.146  6997  6997 V BluetoothSapReceiver: Calling SAP service start service with action = null
,08-26 10:52:49.148  6997  7578 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-26 10:52:49.149  6997  6997 V BluetoothFtpService: Handler(): got msg=1
08-26 10:52:49.150  6997  6997 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-26 10:52:49.150  6997  6997 V BluetoothFtpService: Ftp Service initSocket
08-26 10:52:49.150  6997  7578 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-26 10:52:49.154  6997  7578 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1b2522ac on behalf of 
08-26 10:52:49.155  6997  7578 V BluetoothOppNotification: update too frequent, put in queue
08-26 10:52:49.156  1036  1970 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 10:52:49.156  6997  7578 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-26 10:52:49.157  6997  6997 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 10:52:49.158  6997  6997 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=78
08-26 10:52:49.158  6997  6997 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-26 10:52:49.161  6997  7579 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
,08-26 10:52:49.174  6997  6997 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ea29bbb
,08-26 10:52:49.174  6997  6997 V BluetoothSapService: Sap Service onCreate
08-26 10:52:49.176  6997  6997 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-26 10:52:49.176  6997  6997 V BluetoothSapService: state: 12
08-26 10:52:49.176  6997  6997 V BluetoothSapService: Starting SAP server process
08-26 10:52:49.179  6997  6997 V BluetoothSapService: SAP Service startRfcommListenerThread
08-26 10:52:49.173  7580  7580 W sapd    : type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 10:52:49.173  7580  7580 W sapd    : type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 10:52:49.181  6997  7581 V BluetoothSapService: Sap Service initRfcommSocket
08-26 10:52:49.184  1036  1978 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 10:52:49.187  6997  7581 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 10:52:49.188  6997  7581 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-26 10:52:49.189  6997  7581 V BluetoothSapService: Succeed to create listening socket 
08-26 10:52:49.189  6997  7581 V BluetoothSapService: Accepting socket connection...
,08-26 10:52:49.194  7580  7580 V BT_SAP  : Event pipe created
08-26 10:52:49.194  7580  7580 V BT_SAP  : create_server_socket qcom.sap.server
08-26 10:52:49.194  7580  7580 V BT_SAP  : created socket fd 6
08-26 10:52:49.630  1036  1393 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-26 10:52:49.630  1036  1393 D LGWifiP2pService: DefaultState{ when=-1ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-26 10:52:49.675  1036  1440 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-26 10:52:49.676  1036  1440 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-26 10:52:49.999  1036  1052 I ActivityManager: Killing 7397:com.lge.bnr/1000 (adj 15): empty #17
,08-26 10:52:50.031  1036  1978 W libprocessgroup: failed to open /acct/uid_1000/pid_7397/cgroup.procs: No such file or directory
,08-26 10:52:50.064  1036  1923 I ActivityManager: Killing 6872:com.lge.sync/1000 (adj 15): empty #17
,08-26 10:52:50.095  1036  1485 D WifiService: Client connection lost with reason: 4
,08-26 10:52:50.102  1036  1942 W libprocessgroup: failed to open /acct/uid_1000/pid_6872/cgroup.procs: No such file or directory
08-26 10:52:50.113  6997  6997 V BluetoothOppNotification: new notify threadi!
08-26 10:52:50.113  6997  6997 V BluetoothOppNotification: send delay message
,08-26 10:52:50.117  6997  7591 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-26 10:52:50.118  6997  7591 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@817bd98 on behalf of 
08-26 10:52:50.119  6997  7591 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-26 10:52:50.120  6997  7591 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-26 10:52:50.121  6997  7591 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@297039f1 on behalf of 
08-26 10:52:50.122  6997  7591 V BluetoothOppNotification: outbound: succ-0  fail-0
08-26 10:52:50.123  6997  7591 V BluetoothOppNotification: outbound notification was removed.
08-26 10:52:50.123  6997  7591 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-26 10:52:50.279  1036  1970 I art     : Explicit concurrent mark sweep GC freed 75000(3MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/64MB, paused 3.001ms total 144.921ms
,08-26 10:52:50.281  6997  7591 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@17d649d6 on behalf of 
,08-26 10:52:50.284  6997  7591 V BluetoothOppNotification: inbound: succ-0  fail-0
,08-26 10:52:50.286  6997  7591 V BluetoothOppNotification: inbound notification was removed.
,08-26 10:52:50.286  6997  7591 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
,08-26 10:52:50.287  6997  7591 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2240d457 on behalf of 
,08-26 10:52:50.621  1036  1784 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0,
08-26 10:52:50.621  1036  1784 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@12d1b38c mBinding = false
,08-26 10:52:50.658  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-26 10:52:50.658  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-26 10:52:50.658  1036  1036 D Ulp_jni : JNI:system_update. Event-4
08-26 10:52:50.659  1036  1112 D BluetoothManagerService: Message: 2
08-26 10:52:50.660  1036  1112 D BluetoothManagerService: Sending off request.
08-26 10:52:50.660  6997  7465 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-26 10:52:50.661  6997  7443 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-26 10:52:50.661  6997  7443 D BluetoothAdapterProperties: Setting state to 13
08-26 10:52:50.661  6997  7443 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-26 10:52:50.662  6997  7443 D BluetoothAdapterProperties: onBluetoothDisable()
08-26 10:52:50.662  6997  7443 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-26 10:52:50.664  6997  7447 D BluetoothAdapterProperties: Scan Mode:20
08-26 10:52:50.666  6997  7443 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,08-26 10:52:50.671  6997  7443 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-26 10:52:50.673  6997  7565 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-26 10:52:50.673  6997  7565 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 10:52:50.673  6997  7565 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-26 10:52:50.673  6997  7565 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-26 10:52:50.673  6997  7565 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-26 10:52:50.673  6997  7565 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-26 10:52:50.673  6997  7565 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-26 10:52:50.673  6997  7565 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-26 10:52:50.674  6997  7567 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 10:52:50.674  6997  7576 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 10:52:50.675  6997  7579 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 10:52:50.675  6997  7581 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 10:52:50.676  6997  7516 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-26 10:52:50.676  6997  7516 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-26 10:52:50.683  6997  7516 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-26 10:52:50.683  6997  7516 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-26 10:52:50.683  6997  7516 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-26 10:52:50.684  6997  7516 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-26 10:52:50.684  6997  7516 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 10:52:50.684  6997  7516 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-26 10:52:50.684  6997  7516 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 10:52:50.684  6997  7516 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-26 10:52:50.684  6997  7516 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 10:52:50.684  6997  7516 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-26 10:52:50.684  6997  7516 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-26 10:52:50.684  6997  7516 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
,08-26 10:52:50.693  6692  6692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 10:52:50.693  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 10:52:50.693  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 10:52:50.693  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 10:52:50.693  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 10:52:50.693  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 10:52:50.693  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 10:52:50.693  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 10:52:50.693  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 10:52:50.694  6692  6692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 10:52:50.694  6692  6692 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 10:52:50.699  6692  6692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 10:52:50.699  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 10:52:50.699  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 10:52:50.699  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 10:52:50.699  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 10:52:50.699  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 10:52:50.699  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 10:52:50.699  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 10:52:50.699  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 10:52:50.703  6692  6692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 10:52:50.703  6692  6692 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 10:52:50.705  1036  1112 D BluetoothManagerService: Message: 60
08-26 10:52:50.705  1036  1112 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-26 10:52:50.705  1036  1112 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-26 10:52:50.707  1943  1943 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-26 10:52:50.710  1604  1604 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-26 10:52:50.716  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 10:52:50.721  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 10:52:50.721  6997  6997 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-26 10:52:50.722  6997  6997 D BluetoothMapService: STATE_TURNING_OFF
08-26 10:52:50.722  6997  6997 V BluetoothMapService: Handler(): got msg=4
08-26 10:52:50.722  6997  6997 D BluetoothMapService: MAP Service closeService in
08-26 10:52:50.722  6997  6997 D BluetoothMapMasInstance: MAP Service shutdown
08-26 10:52:50.722  6997  6997 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-26 10:52:50.723  6997  6997 V BluetoothMapService: MAP Service closeService out
08-26 10:52:50.723  6997  6997 V BtOppService: Receiver DISABLED_ACTION 
08-26 10:52:50.723  6997  6997 I BtOppRfcommListener: stopping Accept Thread
08-26 10:52:50.724  6997  6997 V BtOppRfcommListener: close mBtServerSocket
08-26 10:52:50.724  6997  7576 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-26 10:52:50.724  6997  6997 V BtOppRfcommListener: waiting for thread to terminate
08-26 10:52:50.724  6997  6997 V BtOppRfcommListener: done waiting for thread to terminate
08-26 10:52:50.728  6844  6844 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
,08-26 10:52:50.736  6844  6844 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-26 10:52:50.741  6997  6997 V BtOppService: onDestroy
08-26 10:52:50.743  6997  6997 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-26 10:52:50.747  6997  6997 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-26 10:52:50.748  6997  6997 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 10:52:50.748  6997  6997 V BluetoothPbapReceiver: ***********state = 13
08-26 10:52:50.749  6997  6997 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
,08-26 10:52:50.754  6997  6997 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-26 10:52:50.754  6997  6997 V BluetoothPbapService: state: 13
08-26 10:52:50.754  6997  6997 V BluetoothPbapService: Pbap Service closeService in
08-26 10:52:50.757  2128  2128 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-26 10:52:50.758  6997  6997 V BluetoothPbapService: successfully stopped pbap service
08-26 10:52:50.758  6997  6997 V BluetoothPbapService: Pbap Service closeService out
08-26 10:52:50.761  6997  6997 V BluetoothPbapService: Pbap Service onDestroy
08-26 10:52:50.761  6997  6997 V BluetoothPbapService: Pbap Service closeService in
08-26 10:52:50.761  6997  6997 V BluetoothPbapService: Pbap Service closeService out
08-26 10:52:50.761  6997  6997 D LGBluetoothPbapAdapter: [BTUI] cleanup
,08-26 10:52:50.784  6844  6844 D DockEventReceiver: finishStartingService: stopping service
,08-26 10:52:50.791  6844  6844 D BluetoothPbap: Proxy object disconnected
08-26 10:52:50.791  6844  6844 D PbapServerProfile: Bluetooth service disconnected
08-26 10:52:50.800  6844  6844 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-26 10:52:50.806  6844  6844 D BluetoothPermissionRequest: onReceive
,08-26 10:52:50.807  6844  6844 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-26 10:52:50.813  6844  6844 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-26 10:52:50.818  6997  6997 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-26 10:52:50.818  6997  6997 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-26 10:52:50.819  6997  6997 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-26 10:52:50.822  6997  6997 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-26 10:52:50.822  6997  6997 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-26 10:52:50.824  6997  6997 V BluetoothFtpService: Ftp Service onStartCommand
08-26 10:52:50.824  6997  6997 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-26 10:52:50.824  6997  6997 V BluetoothFtpService: Ftp Service closeService
08-26 10:52:50.824  6997  6997 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-26 10:52:50.826  6997  6997 V BluetoothFtpService: successfully stopped ftp service
08-26 10:52:50.826  6997  6997 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-26 10:52:50.826  6997  6997 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-26 10:52:50.826  6997  6997 V BluetoothSapReceiver: SapReceiver onReceive 
08-26 10:52:50.826  6997  6997 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 10:52:50.826  6997  6997 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-26 10:52:50.826  6997  6997 V BluetoothSapReceiver: Calling SAP service start service with action = null
,08-26 10:52:50.829  6997  6997 V BluetoothFtpService: Ftp Service onDestroy
,08-26 10:52:50.829  6997  6997 V BluetoothFtpService: Ftp Service closeService
08-26 10:52:50.834  6997  6997 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-26 10:52:50.834  6997  6997 V BluetoothSapService: state: 13
08-26 10:52:50.834  6997  6997 V BluetoothSapService: Stopping SAP server process
08-26 10:52:50.835  6997  6997 V BluetoothSapService: Sap Service closeSapService in
08-26 10:52:50.836  6997  6997 V BluetoothSapService: Close listen Socket : 
08-26 10:52:50.836  6997  6997 V BluetoothSapService: Close rfcomm Socket : 
08-26 10:52:50.836  6997  6997 V BluetoothSapService: Close sapd  Socket : 
08-26 10:52:50.837  6997  6997 V BluetoothSapService: Sap Service closeSapService out
08-26 10:52:50.837  6997  6997 V BluetoothSapService: Sap Service onDestroy
08-26 10:52:50.838  6997  6997 V BluetoothSapService: Sap Service closeSapService in
,08-26 10:52:50.838  6997  6997 V BluetoothSapService: Close listen Socket : 
,08-26 10:52:50.838  6997  6997 V BluetoothSapService: Close rfcomm Socket : 
,08-26 10:52:50.838  6997  6997 V BluetoothSapService: Close sapd  Socket : 
,08-26 10:52:50.838  6997  6997 V BluetoothSapService: Sap Service closeSapService out
,08-26 10:52:51.584  6997  7447 D bt_hci_bdroid: cleanup
,08-26 10:52:51.596  6997  7518 I bt_lpm  : LPM is already off!!!
08-26 10:52:51.596  6997  7542 I bt_userial_mct: exiting userial_read_thread
08-26 10:52:51.597  6997  7542 D bt_userial_mct: Leaving userial_evt_read_thread()
08-26 10:52:51.598  6997  7516 W bt-btif : ag scb idx 1 not allocated
08-26 10:52:51.598  6997  7516 E bt-btif : BTA AG is already disabled, ignoring ...
08-26 10:52:51.599  6997  7516 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-26 10:52:51.599  6997  7516 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 10:52:51.599  6997  7516 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-26 10:52:51.599  6997  7516 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 10:52:51.599  6997  7516 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-26 10:52:51.599  6997  7516 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 10:52:51.599  6997  7516 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-26 10:52:51.599  6997  7516 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 10:52:51.599  6997  7516 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-26 10:52:51.599  6997  7516 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 10:52:51.599  6997  7516 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-26 10:52:51.599  6997  7516 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 10:52:51.599  6997  7516 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-26 10:52:51.599  6997  7516 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 10:52:51.599  6997  7516 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-26 10:52:51.599  6997  7516 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 10:52:51.599  6997  7516 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-26 10:52:51.599  6997  7516 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 10:52:51.599  6997  7516 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-26 10:52:51.600  6997  7447 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-26 10:52:51.600  6997  7518 I bt_vendor: hw_epilog_process
08-26 10:52:51.600  6997  7447 D bt_hci_bdroid: cleanup Finalizing cleanup
08-26 10:52:51.600  6997  7447 D bt_userial_mct: userial_close
08-26 10:52:51.600  6997  7447 E bt_userial_mct: pthread_join() FAILED result:3
08-26 10:52:51.600  6997  7447 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-26 10:52:51.608  6997  7447 D bt_hci_bdroid: set_power 0
08-26 10:52:51.608  6997  7447 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-26 10:52:51.608  6997  7447 I bt_vendor: bluetooth satus is on
08-26 10:52:51.608  6997  7447 I bt_vendor: bt-vendor : resetting BT status
08-26 10:52:51.608  6997  7447 I bt_vendor: Starting hciattach daemon
08-26 10:52:51.608  6997  7447 I bt_vendor: try to set false
,08-26 10:52:51.615  6997  7447 I bt_vendor: Starting hciattach daemon
08-26 10:52:51.615  6997  7447 I bt_vendor: try to set false
08-26 10:52:51.616  6997  7447 I bt_vendor: cleanup
08-26 10:52:51.617  6997  7516 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-26 10:52:51.617  6997  7447 I GKI_LINUX: GKI_exit_task 0 done
08-26 10:52:51.617  6997  7447 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-26 10:52:51.619  6997  7443 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-26 10:52:51.626  6997  6997 D HeadsetService: Received stop request...Stopping profile...
,08-26 10:52:51.631  6997  6997 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-26 10:52:51.631  6997  6997 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-26 10:52:51.631  6997  6997 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ea29bbb
08-26 10:52:51.632  6997  7483 D HeadsetStateMachine: Exit Disconnected: -1
08-26 10:52:51.633  6997  7443 D BluetoothAdapterState: Stopping profile services that were post enabled
08-26 10:52:51.635  1854  1854 D BluetoothHeadset: Proxy object disconnected
08-26 10:52:51.635  1854  1854 D BluetoothHeadset: Proxy object disconnected
08-26 10:52:51.635  1854  1854 D BluetoothHeadset: Proxy object disconnected
08-26 10:52:51.635  1036  1036 D BluetoothHeadset: Proxy object disconnected
08-26 10:52:51.635  1036  1036 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-26 10:52:51.636  6997  6997 D A2dpService: Received stop request...Stopping profile...
08-26 10:52:51.637  6997  7501 D A2dpStateMachine: Exit Disconnected: -1
08-26 10:52:51.639  6997  6997 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
,08-26 10:52:51.644  6997  6997 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-26 10:52:51.644  6997  6997 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-26 10:52:51.644  6997  6997 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ea29bbb
08-26 10:52:51.646  6997  6997 D HidService: Received stop request...Stopping profile...
08-26 10:52:51.646  6997  6997 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ea29bbb
08-26 10:52:51.647  1036  1036 D BluetoothA2dp: Proxy object disconnected
08-26 10:52:51.647  1036  1036 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-26 10:52:51.649  6997  6997 D HealthService: Received stop request...Stopping profile...
08-26 10:52:51.649  6997  6997 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ea29bbb
08-26 10:52:51.653  6997  6997 D PanService: Received stop request...Stopping profile...
,08-26 10:52:51.656  6997  6997 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ea29bbb
08-26 10:52:51.658  6997  6997 D BtGatt.DebugUtils: handleDebugAction() action=null
08-26 10:52:51.659  6997  6997 D BtGatt.GattService: Received stop request...Stopping profile...
08-26 10:52:51.659  6997  6997 D BtGatt.GattService: stop()
08-26 10:52:51.659  6997  6997 D BtGatt.AdvertiseManager: advertise clients cleared
08-26 10:52:51.660  6997  6997 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ea29bbb
08-26 10:52:51.662  6997  6997 D BluetoothMapService: Received stop request...Stopping profile...
08-26 10:52:51.662  6997  6997 D BluetoothMapService: stop()
08-26 10:52:51.662  6997  6997 D BluetoothMapEmailAppObserver: deinitObservers()
08-26 10:52:51.663  6997  6997 D BluetoothMapEmailAppObserver: removeReceiver()
08-26 10:52:51.663  6997  6997 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ea29bbb
08-26 10:52:51.664  6997  6997 D HeadsetStateMachine: Unbinding service...
08-26 10:52:51.666  6997  6997 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-26 10:52:51.666  6997  6997 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-26 10:52:51.666  6997  6997 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-26 10:52:51.666  6997  6997 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-26 10:52:51.666  6997  6997 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-26 10:52:51.666  6997  6997 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-26 10:52:51.666  6997  6997 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-26 10:52:51.666  6997  6997 I BluetoothA2dpServiceJni: cleanupNative
,08-26 10:52:51.670  6997  7502 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-26 10:52:51.671  6997  6997 I GKI_LINUX: GKI_exit_task 2 done
08-26 10:52:51.671  6997  6997 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-26 10:52:51.671  6997  6997 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-26 10:52:51.671  6997  6997 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-26 10:52:51.671  6997  6997 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-26 10:52:51.672  6997  6997 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-26 10:52:51.672  6997  6997 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-26 10:52:51.672  6997  6997 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-26 10:52:51.672  6997  6997 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-26 10:52:51.675  6997  6997 V BluetoothMapService: Handler(): got msg=4
08-26 10:52:51.675  6997  6997 D BluetoothMapService: MAP Service closeService in
08-26 10:52:51.675  6997  6997 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-26 10:52:51.675  6997  6997 V BluetoothMapService: MAP Service closeService out
08-26 10:52:51.675  6997  7443 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-26 10:52:51.675  6997  7443 D BluetoothAdapterProperties: Setting state to 10
08-26 10:52:51.675  6997  7443 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-26 10:52:51.676  6997  6997 D BluetoothMapService: cleanup()
08-26 10:52:51.676  6997  6997 D BluetoothMapService: MAP Service closeService in
08-26 10:52:51.676  6997  6997 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-26 10:52:51.676  6997  6997 V BluetoothMapService: MAP Service closeService out
08-26 10:52:51.677  1036  1112 D BluetoothManagerService: Message: 60
08-26 10:52:51.677  1036  1112 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-26 10:52:51.677  1036  1112 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
08-26 10:52:51.678  6997  7443 I BluetoothAdapterState: Entering OffState
08-26 10:52:51.678  1854  1870 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-26 10:52:51.684  1854  1869 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 10:52:51.686  6844  6870 D BluetoothPan: onBluetoothStateChange on: false
08-26 10:52:51.687  1036  1112 D BluetoothA2dp: onBluetoothStateChange: up=false
08-26 10:52:51.688  6844  6870 D BluetoothMap: onBluetoothStateChange: up=false
08-26 10:52:51.688  6844  6870 D BluetoothPbap: onBluetoothStateChange: up=false
08-26 10:52:51.690  6844  6870 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-26 10:52:51.692  1854  2466 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 10:52:51.693  6844  6871 D BluetoothA2dp: onBluetoothStateChange: up=false
08-26 10:52:51.694  1036  1112 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 10:52:51.694  6844  7366 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-26 10:52:51.695  1036  1112 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-26 10:52:51.695  1036  1112 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-26 10:52:51.697  1036  1112 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-26 10:52:51.697  1036  1112 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-26 10:52:51.697  1036  1112 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@12d1b38c mBinding = false
08-26 10:52:51.699  1036  1112 D BluetoothManagerService: Sending unbind request.
08-26 10:52:51.703  6997  7447 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-26 10:52:51.706  6997  6997 I GKI_LINUX: GKI_exit_task 1 done
08-26 10:52:51.706  6997  6997 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-26 10:52:51.706  6997  6997 I BluetoothServiceJni: cleanupNative: return from cleanup
08-26 10:52:51.707  6997  6997 I art     : --- WEIRD: removing null entry 248
08-26 10:52:51.707  6997  6997 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
08-26 10:52:51.707  6997  6997 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-26 10:52:51.708  6997  6997 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-26 10:52:51.709  1036  1112 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-26 10:52:51.716  1943  1943 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-26 10:52:51.719  1943  2118 D LGBluetoothAPIService: Message: 2
08-26 10:52:51.719  1943  2118 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@16cc6a1a mBinding = false
08-26 10:52:51.719  1943  2118 D LGBluetoothAPIService: Sending unbind request.
08-26 10:52:51.719  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 10:52:51.720  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 10:52:51.721  1604  1604 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-26 10:52:51.728  6844  6844 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-26 10:52:51.728  6844  6844 D LGBluetoothEventManager: [BTUI] clear device connection state
,08-26 10:52:51.731  6997  6997 I art     : System.exit called, status: 0
08-26 10:52:51.731  6997  6997 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-26 10:52:51.753  1604  1604 D BluetoothAdapter: 847447842: getState() :  mService = null. Returning STATE_OFF
08-26 10:52:51.753  1604  1604 D BluetoothAdapter: 847447842: getState() :  mService = null. Returning STATE_OFF
,08-26 10:52:51.757  6844  6844 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-26 10:52:51.766  6844  6844 D DockEventReceiver: finishStartingService: stopping service
08-26 10:52:51.768  1036  1924 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,08-26 10:52:51.771   329  1400 V AudioFlinger: 6997 died, releasing its sessions
08-26 10:52:51.771   329  1400 V AudioFlinger:  pid 1854 @ 0
08-26 10:52:51.771   329  1400 V AudioFlinger:  pid 3460 @ 1
08-26 10:52:51.771   329  1400 V AudioFlinger:  pid 3460 @ 2
08-26 10:52:51.772  6844  6844 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-26 10:52:51.818  1036  2033 I ActivityManager: Process com.android.bluetooth (pid 6997) has died
08-26 10:52:51.819  1036  2033 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 4000ms
,08-26 10:52:51.827  1036  1381 V AlarmManager: ELAPSED_WAKEUP set : Alarm{332dbf51 type 2 when 131023 com.google.android.gms} when 131023
08-26 10:52:51.832  2128  2128 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-26 10:52:51.839   324  7639 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,08-26 10:52:51.842  1036  1110 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-26 10:52:51.853  6844  6844 D BluetoothPermissionRequest: onReceive
,08-26 10:52:51.859  6844  6844 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
,08-26 10:52:51.859  6844  6844 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-26 10:52:51.861  6844  6844 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-26 10:52:51.924  1036  1889 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7641 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-26 10:52:52.012  7641  7641 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-26 10:52:52.012  7641  7641 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-26 10:52:52.013  7641  7641 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-26 10:52:52.014  7641  7641 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-26 10:52:52.035  7641  7641 D BluetoothAdapterApp: Loading JNI Library
,08-26 10:52:52.084  7641  7641 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@2da98743 Instance Count = 1
,08-26 10:52:52.093  7641  7641 D BluetoothAdapterApp: onCreate
,08-26 10:52:52.141  7641  7641 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-26 10:52:52.141  7641  7641 D ProfileConfigQcom: Adding HeadsetService
08-26 10:52:52.141  7641  7641 D ProfileConfigQcom: [BTUI] A2dpService is supported
,08-26 10:52:52.141  7641  7641 D ProfileConfigQcom: Adding A2dpService
08-26 10:52:52.142  7641  7641 D ProfileConfigQcom: [BTUI] HidService is supported
08-26 10:52:52.142  7641  7641 D ProfileConfigQcom: Adding HidService
08-26 10:52:52.142  7641  7641 D ProfileConfigQcom: [BTUI] HealthService is supported
08-26 10:52:52.142  7641  7641 D ProfileConfigQcom: Adding HealthService
08-26 10:52:52.143  7641  7641 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-26 10:52:52.144  7641  7641 D ProfileConfigQcom: [BTUI] PanService is supported
08-26 10:52:52.144  7641  7641 D ProfileConfigQcom: Adding PanService
08-26 10:52:52.144  7641  7641 D ProfileConfigQcom: [BTUI] GattService is supported
08-26 10:52:52.145  7641  7641 D ProfileConfigQcom: Adding GattService
08-26 10:52:52.145  7641  7641 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-26 10:52:52.146  7641  7641 D ProfileConfigQcom: Adding BluetoothMapService
,08-26 10:52:52.147  7641  7641 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-26 10:52:52.150  7641  7641 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-26 10:52:52.158  6844  6844 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-26 10:52:52.162  7641  7641 V LGMDMManagerInternal: Create singleton instance
,08-26 10:52:52.269  7641  7641 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-26 10:52:52.274  7641  7641 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-26 10:52:52.275  7641  7641 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-26 10:52:52.275  7641  7641 V BluetoothSapReceiver: SapReceiver onReceive 
08-26 10:52:52.277  7641  7641 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 10:52:52.277  7641  7641 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-26 10:52:52.285  6937  6937 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,08-26 10:52:52.290  1036  1784 I ActivityManager: Killing 7067:com.lge.appbox.client/u0a11 (adj 15): empty #17
08-26 10:52:52.320  1036  1978 W libprocessgroup: failed to open /acct/uid_10011/pid_7067/cgroup.procs: No such file or directory
,08-26 10:52:53.649  1604  1604 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,08-26 10:52:53.694  1036  1383 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-26 10:52:53.728  6692  6782 D io.jxcore.node.ConnectivityMonitor: stop
08-26 10:52:53.728  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 10:52:53.736  1036  1097 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7669 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
08-26 10:52:53.745  1604  1604 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
,08-26 10:52:53.749  1604  1604 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
,08-26 10:52:53.772  2034  2034 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-26 10:52:53.807  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-26 10:52:53.819  1036  1036 D administrator: Handling package changes for user 0
08-26 10:52:53.840  7669  7669 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-26 10:52:53.915  7669  7669 D LgDataFeature: LgDataFeature() Constructor: none
08-26 10:52:53.915  7669  7669 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-26 10:52:53.929  1036  1036 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
08-26 10:52:53.929  1036  1036 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-26 10:52:53.962  1036  1095 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-26 10:52:53.969  1036  1095 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-26 10:52:53.975  2034  2034 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,08-26 10:52:53.977  2454  2454 V GmsNetworkLocationProvi: DISABLE
08-26 10:52:54.001  1036  1095 D LocationProviderProxy: applying state to connected service
,08-26 10:52:54.006  2454  2454 E GCoreFlp: Bound FusedProviderService with LocationManager
08-26 10:52:54.025  7669  7713 I Babel   : MmsConfig: mnc/mcc: 0/0
08-26 10:52:54.026  7669  7713 I Babel   : MmsConfig.loadMmsSettings
,08-26 10:52:54.031  7669  7713 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-26 10:52:54.031  7669  7713 I Babel   : MmsConfig.loadFromDatabase
,08-26 10:52:54.042  7669  7713 E Babel   : canonicalizeMccMnc: invalid mccmnc 
08-26 10:52:54.043  7669  7713 I Babel   : MmsConfig.loadFromResources
08-26 10:52:54.045  7669  7713 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
,08-26 10:52:54.046  7669  7713 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
,08-26 10:52:54.072  7669  7669 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 10:52:54.080  7669  7711 W AudioCapabilities: Unsupported mime audio/evrc
,08-26 10:52:54.083  7669  7711 W AudioCapabilities: Unsupported mime audio/qcelp
08-26 10:52:54.085  7669  7711 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
08-26 10:52:54.101  7669  7711 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
,08-26 10:52:54.102  7669  7711 W AudioCapabilities: Unsupported mime audio/qcelp
08-26 10:52:54.103  1819  7714 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
08-26 10:52:54.103  1819  7714 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
08-26 10:52:54.104  7669  7711 W AudioCapabilities: Unsupported mime audio/evrc
,08-26 10:52:54.121  7669  7711 W VideoCapabilities: Unsupported mime video/x-ms-wmv
08-26 10:52:54.122  7669  7711 W VideoCapabilities: Unsupported mime video/divx
08-26 10:52:54.124  7669  7711 W VideoCapabilities: Unsupported mime video/divx311
08-26 10:52:54.126  7669  7711 W VideoCapabilities: Unsupported mime video/divx4
,08-26 10:52:54.136  7669  7711 W VideoCapabilities: Unsupported mime video/mp4v-esdp
08-26 10:52:54.144  1036  2014 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7719 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,08-26 10:52:54.150  1036  1942 I ActivityManager: Killing 7102:com.lge.email/u0a23 (adj 15): empty #17
08-26 10:52:54.159  1819  4666 I Icing   : updateResources: need to parse e{com.google.android.gms}
,08-26 10:52:54.172  7669  7711 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
08-26 10:52:54.175  7669  7711 W AudioCapabilities: Unsupported mime audio/eac3
08-26 10:52:54.176  7669  7711 W AudioCapabilities: Unsupported mime audio/ac3
08-26 10:52:54.177  7669  7711 W AudioCapabilities: Unsupported mime audio/g726
08-26 10:52:54.178  7669  7711 W AudioCapabilities: Unsupported mime audio/wma-voice
,08-26 10:52:54.179  7669  7711 W AudioCapabilities: Unsupported mime audio/x-ms-wma
08-26 10:52:54.180  7669  7711 W AudioCapabilities: Unsupported mime audio/adpcm
08-26 10:52:54.181  7669  7711 W VideoCapabilities: Unsupported mime video/theora
08-26 10:52:54.183  7669  7711 W VideoCapabilities: Unsupported mime video/mjpg
,08-26 10:52:54.417  1036  1053 W libprocessgroup: failed to open /acct/uid_10023/pid_7102/cgroup.procs: No such file or directory
,08-26 10:52:54.455  7719  7719 I AppUp4:AppBoxCP: onCreate
,08-26 10:52:54.456  7719  7719 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,08-26 10:52:54.466  7719  7719 I AppUp4:DB:  setFingerPrint start
08-26 10:52:54.466  7719  7719 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
08-26 10:52:54.474  7719  7719 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
08-26 10:52:54.474  7719  7719 I AppUp4:DB:  SDK version = 21
08-26 10:52:54.474  7719  7719 I AppUp4:DB:  beforefinger == newfinger no write in DB
,08-26 10:52:54.476  7719  7719 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
,08-26 10:52:54.492  7719  7719 I AppUp4:CustModeStarterReceiver: onReceive
,08-26 10:52:54.528  7719  7719 D LgDataFeature: LgDataFeature() Constructor: none
08-26 10:52:54.528  7719  7719 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-26 10:52:54.535  7719  7719 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@3aecfe3e
08-26 10:52:54.535  7719  7719 D AppUp4:CustFacade: isCustomizationCompleted : false
08-26 10:52:54.535  7719  7719 D AppUp4:CustFacade: isPhone : true
08-26 10:52:54.536  7719  7719 D AppUp4:CustModeStarterReceiver: begin check event
08-26 10:52:54.536  7719  7719 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
08-26 10:52:54.601  1036  1970 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7742 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,08-26 10:52:54.606  1036  1970 I ActivityManager: Killing 6957:com.lge.formmanager/u0a26 (adj 15): empty #17
08-26 10:52:54.692  1036  1495 D ConnectivityService: Failed to find a new network - expiring NetTransition Wakelock
,08-26 10:52:54.720  1036  1584 W libprocessgroup: failed to open /acct/uid_10026/pid_6957/cgroup.procs: No such file or directory
,08-26 10:52:54.749  7742  7742 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-26 10:52:54.750  7742  7742 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-26 10:52:54.750  7742  7742 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-26 10:52:54.751  7742  7742 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
08-26 10:52:54.751  7742  7742 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,08-26 10:52:54.818  7742  7742 I SystemConfig: BUILD Country: EU
08-26 10:52:54.818  7742  7742 I SystemConfig: BUILD Operator: OPEN
,08-26 10:52:54.862  1036  1052 I ActivityManager: Killing 6501:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,08-26 10:52:54.917  1036  2014 W libprocessgroup: failed to open /acct/uid_1000/pid_6501/cgroup.procs: No such file or directory
,08-26 10:52:54.979  1036  1052 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7764 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,08-26 10:52:54.991  7742  7759 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
08-26 10:52:54.991  7742  7759 I SystemConfig: existFile = false
08-26 10:52:54.991  7742  7759 I SystemConfig: canReadFile = false
08-26 10:52:54.991  7742  7759 I SystemConfig: systemFeature RCS result false
08-26 10:52:54.991  7742  7759 D SystemConfig: refreshRcsSupport() :false
,08-26 10:52:55.045  7764  7764 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-26 10:52:55.046  7764  7764 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-26 10:52:55.046  7764  7764 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-26 10:52:55.047  7764  7764 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-26 10:52:55.183  7764  7764 I AppConfig: Total System Memory = 2995761152
,08-26 10:52:55.193  7764  7764 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
08-26 10:52:55.266  1036  1970 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7783 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-26 10:52:55.270  1036  1970 I ActivityManager: Killing 7138:com.google.android.setupwizard/u0a46 (adj 15): empty #17
08-26 10:52:55.325  1036  1978 W libprocessgroup: failed to open /acct/uid_10046/pid_7138/cgroup.procs: No such file or directory
,08-26 10:52:55.516  7783  7783 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,08-26 10:52:55.624  7783  7783 D LgDataFeature: LgDataFeature() Constructor: none
08-26 10:52:55.624  7783  7783 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-26 10:52:55.682  7783  7783 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,08-26 10:52:55.706  7783  7783 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-26 10:52:55.707  7783  7783 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
08-26 10:52:55.724  7783  7783 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-26 10:52:55.724  7783  7783 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,08-26 10:52:55.750  1036  1923 I ActivityManager: Killing 7161:com.android.chrome/u0a57 (adj 15): empty #17
,08-26 10:52:55.864  1036  2005 W libprocessgroup: failed to open /acct/uid_10057/pid_7161/cgroup.procs: No such file or directory
,08-26 10:52:55.875  4600  7819 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
08-26 10:52:55.923  1036  1053 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7821 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,08-26 10:52:55.934  2842  2857 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
08-26 10:52:55.935  2842  2857 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@5305f49 on behalf of 7783
,08-26 10:52:55.980  7783  7783 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
08-26 10:52:56.002  7783  7783 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,08-26 10:52:56.022  7821  7821 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,08-26 10:52:56.053  7821  7821 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
,08-26 10:52:56.053  7821  7821 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
08-26 10:52:56.053  7821  7821 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
08-26 10:52:56.053  7821  7821 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
08-26 10:52:56.053  7821  7821 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
08-26 10:52:56.053  7821  7821 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
08-26 10:52:56.078  1036  2014 I ActivityManager: Killing 7179:com.lge.drmservice/u0a62 (adj 15): empty #17
,08-26 10:52:56.120  1036  1924 W libprocessgroup: failed to open /acct/uid_10062/pid_7179/cgroup.procs: No such file or directory
,08-26 10:52:56.265  1036  1053 V SIM_STK : Menu title from STK is T-Mobile
,08-26 10:52:56.299  4600  7819 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 424 ms] updated apps [took 424 ms] 
,08-26 10:52:56.749  6692  6782 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 10:52:56.750  6692  6782 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@347b327f added. We now have 6 listener(s)
,08-26 10:52:56.750  6692  6782 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 10:52:56.764  6692  6782 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 10:52:56.764  6692  6782 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2f11624c added. We now have 7 listener(s)
08-26 10:52:56.764  6692  6782 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 10:52:56.766  6692  6782 I System.out: IsBluetoothEnabled
08-26 10:52:56.770  1036  1784 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 10:52:56.770  1036  1784 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
,08-26 10:52:56.772  1036  1112 D BluetoothManagerService: Message: 2
08-26 10:52:56.776  6692  6782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 10:52:56.776  1036  2005 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 10:52:56.776  1036  2005 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-26 10:52:56.795  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-26 10:52:56.795  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-26 10:52:56.795  1036  1036 D Ulp_jni : JNI:system_update. Event-4
08-26 10:52:56.796  1036  1112 D BluetoothManagerService: Message: 1
08-26 10:52:56.796  1036  1112 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-26 10:52:56.825  1036  1112 D BluetoothManagerService: Message: 20
08-26 10:52:56.825  1036  1112 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@eaca50c:true
,08-26 10:52:56.829  7641  7641 D BluetoothAdapterState: make
08-26 10:52:56.834  7641  7641 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-26 10:52:56.834  7641  7641 I bluedroid-qcom: init
08-26 10:52:56.835  7641  7865 I BluetoothAdapterState: Entering OffState
08-26 10:52:56.835  7641  7641 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-26 10:52:56.836  7641  7641 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-26 10:52:56.836  7641  7641 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-26 10:52:56.836  7641  7641 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-26 10:52:56.836  7641  7641 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-26 10:52:56.838  7641  7641 I bluedroid-qcom: get_profile_interface socket
08-26 10:52:56.838  7641  7641 I bluedroid-qcom: get_profile_interface map_client
,08-26 10:52:56.842  7641  7869 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-26 10:52:56.833  7868  7868 W bdaddr_loader: type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 10:52:56.846  7641  7869 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-26 10:52:56.833  7868  7868 W bdaddr_loader: type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 10:52:56.856  7868  7868 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-26 10:52:56.856  7868  7868 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-26 10:52:56.856  7868  7868 I LGFTMITEM: [GET_FTM][id=8], offset=16384
,08-26 10:52:56.861  1036  1036 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-26 10:52:56.861  1036  1036 D BluetoothManagerService: Stored Bluetooth name: G3
08-26 10:52:56.867  7868  7868 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-26 10:52:56.874  7868  7868 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-26 10:52:56.874  7868  7868 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
,08-26 10:52:56.879  7641  7869 D BluetoothAdapterProperties: Name is: G3
08-26 10:52:56.880  1036  1036 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-26 10:52:56.880  1036  1112 D BluetoothManagerService: Message: 40
08-26 10:52:56.880  1036  1112 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-26 10:52:56.881  7641  7657 I bluedroid-qcom: config_hci_snoop_log
08-26 10:52:56.882  1036  1112 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-26 10:52:56.882  1036  1112 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-26 10:52:56.888  7641  7865 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-26 10:52:56.889  7641  7865 D BluetoothAdapterProperties: Setting state to 11
08-26 10:52:56.889  7641  7865 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
,08-26 10:52:56.893  1036  1112 D BluetoothManagerService: Message: 60
08-26 10:52:56.893  1036  1112 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
,08-26 10:52:56.893  1036  1112 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-26 10:52:56.894  7641  7865 I LGBluetoothServiceJni: classInitNative: succeeds
,08-26 10:52:56.900  1943  1943 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-26 10:52:56.910  1604  1604 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,08-26 10:52:56.916  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 10:52:56.917  6844  6844 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-26 10:52:56.919  7641  7865 D BluetoothBondStateMachine: make
08-26 10:52:56.922  7641  7865 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ea29bbb
08-26 10:52:56.922  7641  7885 I BluetoothBondStateMachine: StableState(): Entering Off State
08-26 10:52:56.922  7641  7865 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-26 10:52:56.922  7641  7865 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ea29bbb
08-26 10:52:56.922  7641  7865 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-26 10:52:56.923  7641  7865 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-26 10:52:56.923  7641  7641 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-26 10:52:56.924  7641  7641 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 10:52:56.924  7641  7641 V BluetoothPbapReceiver: ***********state = 11
,08-26 10:52:56.928  2128  2128 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-26 10:52:56.932  7641  7865 E BluetoothAdapterService: File transfer profiles supported!!
08-26 10:52:56.942  7641  7641 D HeadsetService: Received start request. Starting profile...
08-26 10:52:56.942  6844  6844 D BluetoothPermissionRequest: onReceive
,08-26 10:52:56.943  7641  7641 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-26 10:52:56.943  7641  7641 D LGBluetoothHfpAdapter: Version 1.6
08-26 10:52:56.946  7641  7641 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-26 10:52:56.948  7641  7641 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-26 10:52:56.949  7641  7641 D HeadsetStateMachine: make
08-26 10:52:56.951  7641  7865 E BluetoothAdapterService: File transfer profiles supported!!
08-26 10:52:56.952  6844  6844 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-26 10:52:56.961  7641  7865 E BluetoothAdapterService: File transfer profiles supported!!
,08-26 10:52:56.970  7641  7865 E BluetoothAdapterService: File transfer profiles supported!!
08-26 10:52:56.975  7641  7865 E BluetoothAdapterService: File transfer profiles supported!!
,08-26 10:52:56.983  7641  7865 E BluetoothAdapterService: File transfer profiles supported!!
08-26 10:52:56.989  7641  7865 E BluetoothAdapterService: File transfer profiles supported!!
,08-26 10:52:56.990  7641  7641 D LgDataFeature: LgDataFeature() Constructor: none
08-26 10:52:56.990  7641  7641 D LgDataFeature: LgDataFeature() Constructor Done, null
08-26 10:52:56.995  7641  7641 D HeadsetStateMachine: max_hf_connections = 1
08-26 10:52:56.995  7641  7641 I bluedroid-qcom: get_profile_interface handsfree
08-26 10:52:56.998  7641  7641 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-26 10:52:56.999   329  2193 V AudioPolicyService: registerClient() client 0xb57f5820, uid 1002
08-26 10:52:56.999   329   329 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-26 10:52:56.999   329   329 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-26 10:52:56.999   329   329 V AudioPolicyManagerEx: getOutput() returns output 2
08-26 10:52:56.999  7641  7641 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-26 10:52:57.000   329  1400 V AudioFlinger: registerClient() client 0xb1032100, pid 7641
,08-26 10:52:57.000   329  1394 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-26 10:52:57.000   329  1394 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-26 10:52:57.001  1854  4180 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-26 10:52:57.001  1854  4180 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-26 10:52:57.001   329  1395 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-26 10:52:57.001  7641  7641 V ToneGenerator: Create Track: 0xb4928a80
08-26 10:52:57.001   329  1395 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-26 10:52:57.001  7641  7641 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-26 10:52:57.001  7641  7641 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-26 10:52:57.001  7641  7658 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-26 10:52:57.001  7641  7658 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
,08-26 10:52:57.001  7641  7658 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-26 10:52:57.001  7641  7658 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-26 10:52:57.002  1854  1870 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-26 10:52:57.002  1854  1870 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-26 10:52:57.002   329  1399 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-26 10:52:57.002   329  1399 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-26 10:52:57.002   329  1399 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-26 10:52:57.002   329  1399 V AudioPolicyManagerEx: getOutput() returns output 2
08-26 10:52:57.002  1036  1737 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-26 10:52:57.002  1036  1737 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-26 10:52:57.002  3460  3476 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-26 10:52:57.002  3460  3476 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-26 10:52:57.002  3460  3476 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-26 10:52:57.002  3460  3476 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-26 10:52:57.003   329  2193 I AudioFlinger: isAudioPlaybackHookOn() false
08-26 10:52:57.003   329  1399 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-26 10:52:57.003   329  1399 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-26 10:52:57.003   329  1399 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-26 10:52:57.003   329  1399 V AudioPolicyManagerEx: getOutput() returns output 2
08-26 10:52:57.003  1604  1620 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-26 10:52:57.003  1604  1620 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-26 10:52:57.003  1604  1620 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-26 10:52:57.003  1604  1620 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-26 10:52:57.003  7641  7641 V AudioSystem: getLatency() output 2, latency 50
08-26 10:52:57.003  1036  1737 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-26 10:52:57.003  1036  1737 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-26 10:52:57.003  7641  7641 V AudioSystem: getFrameCount() output 2, frameCount 960
08-26 10:52:57.003  7641  7641 V AudioTrack: createTrack_l() output 2 afLatency 50
08-26 10:52:57.004   329  2194 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-26 10:52:57.004   329  2194 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-26 10:52:57.004   329  2194 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-26 10:52:57.004   329  2194 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-26 10:52:57.004   329  2194 V AudioFlinger: createTrack() lSessionId: 23
08-26 10:52:57.007  7641  7641 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
,08-26 10:52:57.008   329  2194 V AudioFlinger: acquiring 23 from 7641, for 7641
08-26 10:52:57.008   329  2194 V AudioFlinger:  added new entry for 23
08-26 10:52:57.008  7641  7641 V ToneGenerator: ToneGenerator INIT OK, time: 136260
08-26 10:52:57.008  7641  7641 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ea29bbb
08-26 10:52:57.008  7641  7886 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-26 10:52:57.009  7641  7865 V LGMDMManager: Create singleton instance
08-26 10:52:57.009  7641  7886 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-26 10:52:57.009  7641  7886 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-26 10:52:57.009  7641  7886 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-26 10:52:57.009   329  2193 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7641
08-26 10:52:57.010   329  2193 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-26 10:52:57.010   329  2193 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-26 10:52:57.010   329  2193 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-26 10:52:57.010   329  2193 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-26 10:52:57.010   329  2193 V voice   : voice_set_parameters: exit with code(0)
08-26 10:52:57.010   329  2193 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-26 10:52:57.010   329  2193 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-26 10:52:57.010   329  2193 V msm8974_platform: platform_set_parameters: exit with code(0)
08-26 10:52:57.010   329  2193 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-26 10:52:57.010   329  2193 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-26 10:52:57.010   329  2193 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-26 10:52:57.011  7641  7886 V ToneGenerator: ToneGenerator destructor
08-26 10:52:57.011  7641  7886 V ToneGenerator: stopTone
08-26 10:52:57.011  7641  7886 V ToneGenerator: Delete Track: 0xb4928a80
08-26 10:52:57.012  7641  7641 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ea29bbb
08-26 10:52:57.012  7641  7886 V AudioTrack: ~AudioTrack, releasing session id from 7641 on behalf of 7641
08-26 10:52:57.012  7641  7865 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-26 10:52:57.012   329   329 V AudioPolicyService: AudioCommandThread() adding release output 2
08-26 10:52:57.012   329  1399 V AudioFlinger: releasing 23 from 7641 for 7641
08-26 10:52:57.012   329   329 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-26 10:52:57.012   329  1399 V AudioFlinger:  decremented refcount to 0
08-26 10:52:57.012   329  1399 V AudioFlinger: purging stale effects
08-26 10:52:57.012   329   329 V AudioFlinger: PlaybackThread::Track destructor
08-26 10:52:57.012   329   329 V AudioFlinger: removeClient_l() pid 7641, calling pid 329
08-26 10:52:57.014   329  1258 V AudioPolicyService: AudioCommandThread() waking up
08-26 10:52:57.014   329  1258 V AudioPolicyService: AudioCommandThread() processing release output 2
08-26 10:52:57.014   329  1258 V AudioPolicyManager: releaseOutput() 2
08-26 10:52:57.014   329  1258 V AudioPolicyService: AudioCommandThread() going to sleep
08-26 10:52:57.014  7641  7641 D A2dpService: Received start request. Starting profile...
08-26 10:52:57.015  7641  7641 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-26 10:52:57.016  7641  7641 V Avrcp   : make
08-26 10:52:57.017  7641  7641 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-26 10:52:57.017  7641  7641 I bluedroid-qcom: get_profile_interface avrcp
,08-26 10:52:57.028  7641  7641 V AudioManager: registerRemoteController: size of Media player list: 0
08-26 10:52:57.030  7641  7641 E AudioManager: No RCC entry present to update
,08-26 10:52:57.030  7641  7641 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-26 10:52:57.034  7641  7641 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
,08-26 10:52:57.035  7641  7641 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
,08-26 10:52:57.035  7641  7641 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
,08-26 10:52:57.042  7641  7641 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-26 10:52:57.177  1036  1736 V SIM_STK : Menu title from STK is T-Mobile
08-26 10:52:57.177  1036  1736 V SIM_STK : Menu title from STK is T-Mobile
,08-26 10:52:57.294  1036  1970 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-26 10:52:57.304  7641  7641 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-26 10:52:57.309  7641  7641 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
,08-26 10:52:57.309  7641  7641 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-26 10:52:57.310  7641  7641 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-26 10:52:57.310  7641  7641 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-26 10:52:57.310  7641  7641 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-26 10:52:57.310  7641  7641 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-26 10:52:57.310  7641  7641 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-26 10:52:57.310  7641  7641 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-26 10:52:57.310  7641  7641 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-26 10:52:57.310  7641  7641 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-26 10:52:57.311  7641  7641 I BluetoothA2dpServiceJni: classInitNative
08-26 10:52:57.311  7641  7641 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-26 10:52:57.311  7641  7641 D A2dpStateMachine: make
08-26 10:52:57.316  7641  7641 I bluedroid-qcom: get_profile_interface a2dp
08-26 10:52:57.316  7641  7900 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-26 10:52:57.318  7641  7641 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-26 10:52:57.318  7641  7641 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-26 10:52:57.319  7641  7641 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ea29bbb
08-26 10:52:57.319  7641  7641 I BluetoothHidServiceJni: classInitNative: succeeds
08-26 10:52:57.321  7641  7641 D HidService: Received start request. Starting profile...
08-26 10:52:57.321  7641  7641 I bluedroid-qcom: get_profile_interface hidhost
08-26 10:52:57.321  7641  7641 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ea29bbb
08-26 10:52:57.322  7641  7641 I BluetoothHealthServiceJni: classInitNative: succeeds
08-26 10:52:57.323  7641  7641 D HealthService: Received start request. Starting profile...
08-26 10:52:57.323  7641  7897 D A2dpStateMachine: Enter Disconnected: -2
08-26 10:52:57.324  7641  7641 I bluedroid-qcom: get_profile_interface health
08-26 10:52:57.325  7641  7641 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-26 10:52:57.325  7641  7641 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ea29bbb
08-26 10:52:57.325  7641  7641 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-26 10:52:57.326  7641  7641 D PanService: Received start request. Starting profile...
08-26 10:52:57.327  7641  7641 D BluetoothPanServiceJni: initializeNative(L110): pan
08-26 10:52:57.327  7641  7641 I bluedroid-qcom: get_profile_interface pan
08-26 10:52:57.332  7641  7641 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
,08-26 10:52:57.332  7641  7641 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ea29bbb
08-26 10:52:57.333  7641  7641 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-26 10:52:57.336  7641  7641 D BtGatt.DebugUtils: handleDebugAction() action=null
08-26 10:52:57.337  7641  7641 D BtGatt.GattService: Received start request. Starting profile...
08-26 10:52:57.337  7641  7641 D BtGatt.GattService: start()
08-26 10:52:57.337  7641  7641 I bluedroid-qcom: get_profile_interface gatt
08-26 10:52:57.337  7641  7641 D BtGatt.AdvertiseManager: advertise manager created
08-26 10:52:57.341  7641  7641 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ea29bbb
08-26 10:52:57.342  7641  7641 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ea29bbb
08-26 10:52:57.343  7641  7641 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-26 10:52:57.344  7641  7641 V BluetoothMapService: BluetoothMapBinder()
08-26 10:52:57.344  7641  7641 D BluetoothMapService: Received start request. Starting profile...
08-26 10:52:57.344  7641  7641 D BluetoothMapService: start()
,08-26 10:52:57.348  7641  7641 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-26 10:52:57.348  7641  7641 D BluetoothMapEmailAppObserver: createReceiver()
08-26 10:52:57.349  7641  7641 D BluetoothMapEmailAppObserver: initObservers()
,08-26 10:52:57.349  7641  7641 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-26 10:52:57.358  7641  7641 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ea29bbb
08-26 10:52:57.359  7641  7641 D HeadsetStateMachine: Proxy object connected
08-26 10:52:57.360  7641  7641 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-26 10:52:57.360  7641  7641 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-26 10:52:57.361  7641  7886 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-26 10:52:57.361  7641  7886 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-26 10:52:57.361  7641  7886 D HeadsetStateMachine: Disconnected process message: 11, size: 0
,08-26 10:52:57.364  7641  7641 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-26 10:52:57.365  7641  7641 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-26 10:52:57.367  7641  7641 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-26 10:52:57.370  7641  7641 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-26 10:52:57.373  7641  7641 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-26 10:52:57.374  7641  7641 V PanService: [BTUI] SIM Extra State :ABSENT
08-26 10:52:57.377  7641  7641 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-26 10:52:57.379  7641  7641 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
,08-26 10:52:57.380  7641  7641 V BluetoothMapService: Handler(): got msg=1
08-26 10:52:57.380  7641  7641 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-26 10:52:57.381  7641  7641 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-26 10:52:57.381  7641  7641 V BluetoothSapReceiver: SapReceiver onReceive 
08-26 10:52:57.381  7641  7641 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 10:52:57.381  7641  7641 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-26 10:52:57.381  7641  7865 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-26 10:52:57.381  7641  7865 I bluedroid-qcom: enable
08-26 10:52:57.382  7641  7865 I bt_hci_bdroid: init
08-26 10:52:57.383  7641  7865 I bt_vendor: bt-vendor : init
08-26 10:52:57.383  7641  7865 I bt_vendor: bt-vendor : get_bt_soc_type
08-26 10:52:57.383  7641  7865 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-26 10:52:57.383  7641  7865 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-26 10:52:57.383  7641  7865 D bt_userial_mct: userial_init
08-26 10:52:57.386  7641  7865 D bt_hci_bdroid: set_power 1
08-26 10:52:57.386  7641  7865 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-26 10:52:57.386  7641  7865 I bt_vendor: Starting hciattach daemon
08-26 10:52:57.386  7641  7865 I bt_vendor: try to set true
08-26 10:52:57.388  7641  7907 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-26 10:52:57.388  7641  7907 I bt-btu  : btu_task pending for preload complete event
08-26 10:52:57.383  7910  7910 W sh      : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 10:52:57.383  7910  7910 W sh      : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 10:52:57.412  7911  7911 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-26 10:52:57.496  7921  7921 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-26 10:52:57.524  7922  7922 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-26 10:52:57.558  7925  7925 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-26 10:52:57.571  7926  7926 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-26 10:52:57.584  7927  7927 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-26 10:52:57.608  7928  7928 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-26 10:52:57.630  7930  7930 I libmdmdetect: ESOC framework not supported
,08-26 10:52:57.631  7930  7930 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
08-26 10:52:57.640  7930  7930 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-26 10:52:57.640  7930  7930 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-26 10:52:57.640  7930  7930 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-26 10:52:57.640  7930  7930 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-26 10:52:57.640  7930  7930 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-26 10:52:57.640  7930  7930 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-26 10:52:57.640  7930  7930 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-26 10:52:57.680  7930  7931 E QC-QMI  : qmi_client [7930] 15: failed to locate client data
,08-26 10:52:57.685   476   476 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-26 10:52:57.686   476   476 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
08-26 10:52:57.733  7932  7932 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-26 10:52:57.753  7936  7936 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-26 10:52:57.797  7641  7865 I bt_vendor: bluetooth satus is on
,08-26 10:52:57.797  7641  7865 D bt_hci_bdroid: preload
,08-26 10:52:57.797  7641  7909 D bt_userial_mct: userial_open(port:0)
08-26 10:52:57.797  7641  7909 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-26 10:52:57.801  7641  7909 I bt_vendor: Done intiailizing UART
08-26 10:52:57.801  7641  7909 I bt_vendor: Done intiailizing UART
08-26 10:52:57.801  7641  7909 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-26 10:52:57.802  7641  7909 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-26 10:52:57.802  7641  7907 I bt-btu  : btu_task received preload complete event
08-26 10:52:57.802  7641  7907 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-26 10:52:57.803  7641  7907 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
,08-26 10:52:57.805  7641  7907 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
,08-26 10:52:57.806  7641  7938 D bt_userial_mct: Entering userial_read_thread()
08-26 10:52:57.811  7641  7907 I         : BTE_InitTraceLevels -- TRC_HCI
08-26 10:52:57.811  7641  7907 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-26 10:52:57.812  7641  7907 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-26 10:52:57.812  7641  7907 I         : BTE_InitTraceLevels -- TRC_AVDT
08-26 10:52:57.812  7641  7907 I         : BTE_InitTraceLevels -- TRC_AVRC
08-26 10:52:57.812  7641  7907 I         : BTE_InitTraceLevels -- TRC_A2D
08-26 10:52:57.812  7641  7907 I         : BTE_InitTraceLevels -- TRC_BNEP
08-26 10:52:57.812  7641  7907 I         : BTE_InitTraceLevels -- TRC_BTM
08-26 10:52:57.812  7641  7907 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-26 10:52:57.812  7641  7907 I         : BTE_InitTraceLevels -- TRC_GAP
08-26 10:52:57.812  7641  7907 I         : BTE_InitTraceLevels -- TRC_PAN
08-26 10:52:57.812  7641  7907 I         : BTE_InitTraceLevels -- TRC_SDP
08-26 10:52:57.812  7641  7907 I         : BTE_InitTraceLevels -- TRC_GATT
08-26 10:52:57.812  7641  7907 I         : BTE_InitTraceLevels -- TRC_SMP
08-26 10:52:57.812  7641  7907 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-26 10:52:57.812  7641  7907 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-26 10:52:57.920  7641  7907 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
,08-26 10:52:57.920  7641  7907 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa01f9061 
,08-26 10:52:57.920  7641  7907 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa01f9061 
,08-26 10:52:57.970  7641  7869 E bt-btif : Calling BTA_HhEnable
,08-26 10:52:57.971  7641  7869 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
,08-26 10:52:57.971  7641  7869 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-26 10:52:57.984  1036  1036 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-26 10:52:57.984  1036  1036 D BluetoothManagerService: Stored Bluetooth name: G3
08-26 10:52:57.985  7641  7869 D BluetoothAdapterProperties: Name is: G3
08-26 10:52:57.989  7641  7869 D BluetoothAdapterProperties: Scan Mode:20
08-26 10:52:57.989  7641  7869 D BluetoothAdapterProperties: Discoverable Timeout:120
08-26 10:52:57.989  7641  7869 D bt_hci_bdroid: postload
08-26 10:52:57.992  7641  7869 D bte_conf: Device ID record 1 : primary
08-26 10:52:57.992  7641  7869 D bte_conf:   vendorId            = 00c4
08-26 10:52:57.992  7641  7869 D bte_conf:   vendorIdSource      = 0001
08-26 10:52:57.992  7641  7869 D bte_conf:   product             = 13a1
08-26 10:52:57.992  7641  7869 D bte_conf:   version             = 1000
08-26 10:52:57.992  7641  7869 D bte_conf:   clientExecutableURL = 
08-26 10:52:57.992  7641  7869 D bte_conf:   serviceDescription  = 
08-26 10:52:57.992  7641  7869 D bte_conf:   documentationURL    = 
,08-26 10:52:57.994  7641  7909 D bt_hci_bdroid: Used up Tx Cmd credits
08-26 10:52:57.994  7641  7869 D bte_conf: bte_load_did_conf no section named DID2.
08-26 10:52:57.998  7641  7865 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-26 10:52:57.999  7641  7865 D BluetoothAdapterProperties: ScanMode =  20
08-26 10:52:57.999  7641  7865 D BluetoothAdapterProperties: State =  11
08-26 10:52:57.999  7641  7865 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-26 10:52:57.999  7641  7865 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-26 10:52:57.999  7641  7865 D BluetoothAdapterProperties: Setting state to 12
08-26 10:52:57.999  7641  7865 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-26 10:52:58.000  7641  7869 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-26 10:52:57.993  7943  7943 W sh      : type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-26 10:52:58.003  7943  7943 W sh      : type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 10:52:58.014  1036  1112 D BluetoothManagerService: Message: 60
08-26 10:52:58.014  1036  1112 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-26 10:52:58.014  1036  1112 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
08-26 10:52:58.018  7641  7909 D bt_hci_bdroid: Used up Tx Cmd credits
,08-26 10:52:58.023  7641  7938 E bt_mct  : hci lib postload completed
08-26 10:52:58.029  1854  2466 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 10:52:58.030  7641  7865 I BluetoothAdapterState: Entering On State
,08-26 10:52:58.037  7641  7865 D LGBluetoothServiceAdapter: [BTUI] OnState
08-26 10:52:58.038  7641  7865 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-26 10:52:58.038  7641  7865 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-26 10:52:58.040  7641  7865 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-26 10:52:58.040  7641  7869 D BluetoothAdapterProperties: Discoverable Timeout:120
08-26 10:52:58.041  7641  7869 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-26 10:52:58.055  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 10:52:58.055  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 10:52:58.055  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 10:52:58.055  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 10:52:58.055  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 10:52:58.055  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 10:52:58.055  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 10:52:58.055  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 10:52:58.065  6692  6692 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 10:52:58.077  1854  1854 D BluetoothHeadset: Proxy object connected
,08-26 10:52:58.079  7641  7865 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-26 10:52:58.080  1854  1870 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 10:52:58.082  1854  1854 D BluetoothHeadset: Proxy object connected
08-26 10:52:58.083  7641  7907 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-26 10:52:58.083  7641  7907 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-26 10:52:58.083  7641  7907 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-26 10:52:58.084  7641  7907 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-26 10:52:58.084  7641  7907 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-26 10:52:58.084  7641  7907 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-26 10:52:58.084  7641  7869 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-26 10:52:58.116  7948  7948 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
,08-26 10:52:58.121  6844  6870 D BluetoothPan: onBluetoothStateChange on: true
08-26 10:52:58.122  6844  6870 D BluetoothPan: onBluetoothStateChange call bindService
,08-26 10:52:58.125  1036  1112 D BluetoothA2dp: onBluetoothStateChange: up=true
08-26 10:52:58.127  1036  1036 D BluetoothA2dp: Proxy object connected
08-26 10:52:58.129  6844  6844 D BluetoothPan: BluetoothPAN Proxy object connected
08-26 10:52:58.129  6844  6844 D PanProfile: Bluetooth service connected
08-26 10:52:58.140  7641  7907 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-26 10:52:58.140  7641  7907 W bt-smp  : Plain text(LSB ~ MSB) = 1c ac 71 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-26 10:52:58.140  7641  7907 W bt-smp  : Encrypted text(LSB ~ MSB) = e5 76 c9 21 ef 8c 6a 05 4d 1b 68 ac ee 11 73 da ,
08-26 10:52:58.140  7641  7907 W bt-btm  : Stopping oneshot timer
08-26 10:52:58.143  6844  6870 D BluetoothMap: onBluetoothStateChange: up=true
,08-26 10:52:58.151  6844  6871 D BluetoothPbap: onBluetoothStateChange: up=true
08-26 10:52:58.152  6844  6844 D BluetoothMap: Proxy object connected
08-26 10:52:58.152  6844  6844 D MapProfile: Bluetooth service connected
08-26 10:52:58.152  6844  6844 D BluetoothMap: getConnectedDevices()
08-26 10:52:58.154  7641  7658 V BluetoothMapService: getConnectedDevices()
08-26 10:52:58.156  6844  7366 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-26 10:52:58.159  1854  4180 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 10:52:58.159  6844  6844 D BluetoothHeadset: Proxy object connected
08-26 10:52:58.159  6844  6844 D HeadsetProfile: Bluetooth service connected
08-26 10:52:58.161  7641  7907 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-26 10:52:58.161  7641  7907 W bt-smp  : Plain text(LSB ~ MSB) = 7d c4 6e 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-26 10:52:58.161  7641  7907 W bt-smp  : Encrypted text(LSB ~ MSB) = 04 7c 73 cd 94 ca 86 3b 06 e7 7c 0f 64 32 cb 45 
08-26 10:52:58.161  7641  7907 W bt-btm  : Stopping oneshot timer
08-26 10:52:58.162  1854  1854 D BluetoothHeadset: Proxy object connected
,08-26 10:52:58.162  6844  6870 D BluetoothA2dp: onBluetoothStateChange: up=true
08-26 10:52:58.164  1036  1112 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 10:52:58.164  6844  6844 D BluetoothA2dp: Proxy object connected
08-26 10:52:58.164  6844  6844 D A2dpProfile: Bluetooth service connected
08-26 10:52:58.165  1036  1036 D BluetoothHeadset: Proxy object connected
08-26 10:52:58.166  6844  6870 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-26 10:52:58.169  1036  1112 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-26 10:52:58.169  1036  1112 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-26 10:52:58.170  6844  6844 D BluetoothInputDevice: Proxy object connected
08-26 10:52:58.170  6844  6844 D HidProfile: Bluetooth service connected
,08-26 10:52:58.172  1943  1943 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-26 10:52:58.173  1943  2118 D LGBluetoothAPIService: Message: 1
08-26 10:52:58.173  1943  2118 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-26 10:52:58.173  7641  7907 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-26 10:52:58.173  7641  7907 W bt-smp  : Plain text(LSB ~ MSB) = ba 50 69 00 00 00 00 00 00 00 00 00 00 00 00 00 
,08-26 10:52:58.173  7641  7907 W bt-smp  : Encrypted text(LSB ~ MSB) = d9 6e 71 ed 38 34 4e 26 39 94 b7 0b 36 cd 55 41 
08-26 10:52:58.173  7641  7907 W bt-btm  : Stopping oneshot timer
08-26 10:52:58.174  1604  1604 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-26 10:52:58.180  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 10:52:58.181  1036  1036 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-26 10:52:58.183  1036  1112 D BluetoothManagerService: Message: 40
08-26 10:52:58.183  1036  1112 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
,08-26 10:52:58.185  1943  2118 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
08-26 10:52:58.187  7641  7641 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-26 10:52:58.187  7641  7641 D BluetoothMapService: STATE_ON
08-26 10:52:58.188  7641  7907 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-26 10:52:58.188  7641  7907 W bt-smp  : Plain text(LSB ~ MSB) = d0 c1 7f 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-26 10:52:58.188  7641  7907 W bt-smp  : Encrypted text(LSB ~ MSB) = 6a 72 7e 18 03 6e 24 4a d4 fc 87 1e b7 1d 02 44 
08-26 10:52:58.188  7641  7907 W bt-btm  : Stopping oneshot timer
08-26 10:52:58.190  6844  6844 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-26 10:52:58.191  7641  7641 D LGBluetoothAPIServer: [BTUI] onCreate()
08-26 10:52:58.191  7641  7641 D LGBluetoothAPIServer: [BTUI] onBind()
08-26 10:52:58.191  6844  6844 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-26 10:52:58.192  1943  1943 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-26 10:52:58.192  7641  7641 V BluetoothMapService: Handler(): got msg=1
08-26 10:52:58.192  1943  2118 D LGBluetoothAPIService: Message: 100
08-26 10:52:58.192  1943  2118 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-26 10:52:58.193  7641  7641 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-26 10:52:58.194  7641  7967 D BluetoothMapMasInstance: MAS initSocket()
08-26 10:52:58.195  7641  7967 D BluetoothMapMasInstance:   masId = 00
08-26 10:52:58.195  7641  7967 D BluetoothMapMasInstance:   msgTypes = 0e
08-26 10:52:58.195  7641  7967 D BluetoothMapMasInstance:   masName = SMS/MMS
08-26 10:52:58.195  7641  7967 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
,08-26 10:52:58.197  1036  1942 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 10:52:58.199  7641  7907 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-26 10:52:58.199  7641  7907 W bt-smp  : Plain text(LSB ~ MSB) = 41 ab 49 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-26 10:52:58.200  7641  7907 W bt-smp  : Encrypted text(LSB ~ MSB) = 4b 4e 72 1f fe f4 1f c7 98 ca 3e 38 e9 04 c2 07 
08-26 10:52:58.200  7641  7907 W bt-btm  : Stopping oneshot timer
08-26 10:52:58.207  7641  7967 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 10:52:58.208  6844  6844 D DockEventReceiver: finishStartingService: stopping service
08-26 10:52:58.209  7641  7967 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-26 10:52:58.209  7641  7967 V BluetoothMapMasInstance: Succeed to create listening socket 
08-26 10:52:58.209  7641  7967 D BluetoothMapMasInstance: Accepting socket connection...
,08-26 10:52:58.211  7641  7869 D BluetoothAdapterProperties: Scan Mode:21
08-26 10:52:58.211  7641  7869 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-26 10:52:58.216  7641  7641 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ea29bbb
08-26 10:52:58.216  7641  7641 V BluetoothPbapService: Pbap Service onCreate
08-26 10:52:58.216  7641  7641 V BluetoothPbapService: Starting PBAP service
08-26 10:52:58.217  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 10:52:58.218  7641  7641 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-26 10:52:58.218  7641  7641 V BluetoothPbapService: Pbap Service onBind
08-26 10:52:58.221  7641  7641 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-26 10:52:58.221  7641  7641 V BluetoothPbapService: state: 12
08-26 10:52:58.221  7641  7641 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-26 10:52:58.221  7641  7641 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 10:52:58.221  7641  7641 V BluetoothPbapReceiver: ***********state = 12
08-26 10:52:58.222  6844  6844 D BluetoothPbap: Proxy object connected
,08-26 10:52:58.222  6844  6844 D PbapServerProfile: Bluetooth service connected
08-26 10:52:58.225  7641  7641 V BluetoothPbapService: Handler(): got msg=1
08-26 10:52:58.226  7641  7641 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-26 10:52:58.228  7641  7970 V BluetoothPbapService: Pbap Service initSocket
08-26 10:52:58.228  2128  2128 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-26 10:52:58.228  1036  1737 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 10:52:58.228  2128  2128 D c       : Getting all permits...
08-26 10:52:58.229  2128  2128 D a       : Opening database...
08-26 10:52:58.229  7641  7970 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 10:52:58.230  7641  7970 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-26 10:52:58.230  7641  7970 V BluetoothPbapService: Succeed to create listening socket 
08-26 10:52:58.230  7641  7970 V BluetoothPbapService: Accepting socket connection...
08-26 10:52:58.232  2128  2128 D a       : Opening database auth.proximity.permit_store...
08-26 10:52:58.233  2128  2128 D a       : Closing database...
08-26 10:52:58.243  6844  6844 D BluetoothPermissionRequest: onReceive
,08-26 10:52:58.245  6844  6844 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
,08-26 10:52:58.247  6844  6844 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-26 10:52:58.250  7641  7641 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-26 10:52:58.251  7641  7641 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-26 10:52:58.256  7641  7641 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-26 10:52:58.274  7641  7641 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,08-26 10:52:58.275  7641  7641 V BtOppService: onCreate
,08-26 10:52:58.278  7641  7641 V BluetoothOppNotification: send message
08-26 10:52:58.281  7641  7641 V BtOppService: Starting RfcommListener
08-26 10:52:58.286  7641  7641 D BluetoothOppPreference: Dumping Names:  
,08-26 10:52:58.286  7641  7641 D BluetoothOppPreference: {}
08-26 10:52:58.286  7641  7641 D BluetoothOppPreference: Dumping Channels:  
08-26 10:52:58.286  7641  7641 D BluetoothOppPreference: {}
08-26 10:52:58.287  7641  7641 V BtOppService: onStartCommand
08-26 10:52:58.291  7641  7641 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-26 10:52:58.291  7641  7974 V BtOppService: Deleted complete outbound shares, number =  0
08-26 10:52:58.292  7641  7641 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-26 10:52:58.292  7641  7974 V BtOppService: Deleted complete inbound failed shares, number = 0
08-26 10:52:58.293  7641  7974 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-26 10:52:58.295  7641  7977 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-26 10:52:58.295  7641  7977 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-26 10:52:58.296  7641  7974 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@17ce4514 on behalf of 
08-26 10:52:58.296  7641  7641 V BluetoothOppNotification: new notify threadi!
08-26 10:52:58.297  7641  7641 V BluetoothOppNotification: send delay message
08-26 10:52:58.298  7641  7641 V BtOppService: start RfcommListener
08-26 10:52:58.301  7641  7978 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-26 10:52:58.301  7641  7641 V BtOppService: RfcommListener started
08-26 10:52:58.302  7641  7641 V BtOppService: ContentObserver received notification
08-26 10:52:58.302  7641  7641 V BtOppService: ContentObserver received notification
,08-26 10:52:58.304  7641  7979 V BtOppRfcommListener: Starting RFCOMM listener....
,08-26 10:52:58.305  1036  1736 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 10:52:58.306  7641  7979 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 10:52:58.307  7641  7979 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=79 mFd=75
08-26 10:52:58.307  7641  7979 V BtOppRfcommListener: Started RFCOMM listener....
08-26 10:52:58.308  7641  7979 I BtOppRfcommListener: Accept thread started.
08-26 10:52:58.308  7641  7979 V BtOppRfcommListener: Accepting connection...
08-26 10:52:58.327  7641  7641 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ea29bbb
08-26 10:52:58.327  7641  7641 V BluetoothFtpService: Ftp Service onCreate
08-26 10:52:58.327  7641  7641 I BluetoothFtpService: Ftp Service onCreate
08-26 10:52:58.328  7641  7641 V BluetoothFtpService: Ftp Service onStartCommand
08-26 10:52:58.328  7641  7641 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-26 10:52:58.328  7641  7641 V BluetoothFtpService: Starting Listening on sockets
08-26 10:52:58.328  7641  7641 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-26 10:52:58.328  7641  7641 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-26 10:52:58.328  7641  7641 V BluetoothSapReceiver: SapReceiver onReceive 
08-26 10:52:58.328  7641  7641 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
,08-26 10:52:58.329  7641  7641 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-26 10:52:58.329  7641  7641 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-26 10:52:58.331  7641  7641 V BluetoothFtpService: Handler(): got msg=1
08-26 10:52:58.331  7641  7641 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-26 10:52:58.331  7641  7641 V BluetoothFtpService: Ftp Service initSocket
08-26 10:52:58.337  1036  1923 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 10:52:58.337  7641  7641 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 10:52:58.338  7641  7641 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=81 mFd=79
08-26 10:52:58.339  7641  7641 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-26 10:52:58.340  7641  7980 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
,08-26 10:52:58.355  7641  7641 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ea29bbb
,08-26 10:52:58.355  7641  7641 V BluetoothSapService: Sap Service onCreate
,08-26 10:52:58.357  7641  7641 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-26 10:52:58.357  7641  7641 V BluetoothSapService: state: 12
08-26 10:52:58.357  7641  7641 V BluetoothSapService: Starting SAP server process
08-26 10:52:58.359  7641  7641 V BluetoothSapService: SAP Service startRfcommListenerThread
08-26 10:52:58.353  7981  7981 W sapd    : type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 10:52:58.353  7981  7981 W sapd    : type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 10:52:58.361  7641  7982 V BluetoothSapService: Sap Service initRfcommSocket
08-26 10:52:58.361  1036  1970 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 10:52:58.362  7641  7982 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 10:52:58.363  7641  7982 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=83 mFd=81
08-26 10:52:58.363  7641  7982 V BluetoothSapService: Succeed to create listening socket 
08-26 10:52:58.363  7641  7982 V BluetoothSapService: Accepting socket connection...
08-26 10:52:58.371  7981  7981 V BT_SAP  : Event pipe created
08-26 10:52:58.371  7981  7981 V BT_SAP  : create_server_socket qcom.sap.server
08-26 10:52:58.371  7981  7981 V BT_SAP  : created socket fd 6
,08-26 10:52:58.421  1036  1053 I art     : Explicit concurrent mark sweep GC freed 26234(1283KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 2.425ms total 124.829ms
08-26 10:52:58.423  7641  7978 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@ad2acb9 on behalf of 
,08-26 10:52:58.423  7641  7978 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-26 10:52:58.424  7641  7977 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1c6a18fe on behalf of 
08-26 10:52:58.424  7641  7977 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-26 10:52:58.424  7641  7977 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-26 10:52:58.425  7641  7978 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-26 10:52:58.426  7641  7977 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3f3e385f on behalf of 
08-26 10:52:58.426  7641  7977 V BluetoothOppNotification: update too frequent, put in queue
08-26 10:52:58.426  7641  7978 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1b2522ac on behalf of 
08-26 10:52:58.427  7641  7978 V BluetoothOppNotification: outbound: succ-0  fail-0
08-26 10:52:58.431  7641  7978 V BluetoothOppNotification: outbound notification was removed.
08-26 10:52:58.431  7641  7978 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-26 10:52:58.431  7641  7977 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-26 10:52:58.431  7641  7978 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1c685b75 on behalf of 
08-26 10:52:58.433  7641  7978 V BluetoothOppNotification: inbound: succ-0  fail-0
08-26 10:52:58.435  7641  7978 V BluetoothOppNotification: inbound notification was removed.
08-26 10:52:58.435  7641  7978 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-26 10:52:58.437  7641  7978 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@15cac70a on behalf of 
,08-26 10:52:58.829  6692  6782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 10:52:58.829  6692  6782 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 10:52:58.829  6692  6782 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 10:52:58.829  6692  6782 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 10:52:58.829  6692  6782 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 10:52:58.829  6692  6782 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 10:52:58.829  6692  6782 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 10:52:58.829  6692  6782 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 10:52:58.841  6692  6782 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 10:52:58.843  6692  6782 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 10:52:58.843  6692  6782 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@29223295 added. We now have 8 listener(s)
08-26 10:52:58.843  6692  6782 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 10:52:58.850  1036  1978 D WifiServiceImplEx: setWifiEnabled: false pid=6692, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-26 10:52:58.850  1036  1978 D WifiService: setWifiEnabled: false pid=6692, uid=10118
08-26 10:52:58.850  1036  1978 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-26 10:52:58.857  6692  6782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 10:52:58.858  1036  1924 D WifiServiceImplEx: setWifiEnabled: true pid=6692, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-26 10:52:58.859  1036  1924 D WifiService: setWifiEnabled: true pid=6692, uid=10118
08-26 10:52:58.859  1036  1924 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-26 10:52:58.876  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-26 10:52:58.876  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-26 10:52:58.876  1036  1036 D Ulp_jni : JNI:system_update. Event-4
,08-26 10:52:58.880  1036  1440 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
,08-26 10:52:58.880  1036  1440 I LGFTMITEM: [GET_FTM][id=6], offset=12288
,08-26 10:52:58.883  1036  1440 E WifiUtil: wfc_util_ffile_check_copy(): pid[1036] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
,08-26 10:52:58.883  1036  1440 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
,08-26 10:52:58.883  1036  1440 E WifiUtil: wfc_util_ffile_check_copy(): pid[1036] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-26 10:52:58.883  1036  1440 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-26 10:52:58.883  1036  1440 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-26 10:52:58.883  1036  1440 E WifiHW  : unknown target_country: EU , set to default
08-26 10:52:58.883  1036  1440 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-26 10:52:58.883  1036  1440 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-26 10:52:58.883  1036  1440 I WifiUtil: gEnableBmps=1
08-26 10:52:59.109  1036  1381 V AlarmManager: ELAPSED_WAKEUP set : Alarm{588b1fc type 2 when 138342 com.google.android.gms} when 138342
,08-26 10:52:59.126   324  7996 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-26 10:52:59.131  1036  1110 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,08-26 10:52:59.310  7641  7641 V BluetoothOppNotification: new notify threadi!
,08-26 10:52:59.318  7641  7641 V BluetoothOppNotification: send delay message
,08-26 10:52:59.323  7641  7997 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-26 10:52:59.330  7641  7997 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@bb7fb7b on behalf of 
,08-26 10:52:59.345  7641  7997 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-26 10:52:59.350  7641  7997 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,08-26 10:52:59.353  7641  7997 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@817bd98 on behalf of 
08-26 10:52:59.354  7641  7997 V BluetoothOppNotification: outbound: succ-0  fail-0
08-26 10:52:59.356  7641  7997 V BluetoothOppNotification: outbound notification was removed.
08-26 10:52:59.356  7641  7997 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-26 10:52:59.359  7641  7997 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@297039f1 on behalf of 
08-26 10:52:59.359  7641  7997 V BluetoothOppNotification: inbound: succ-0  fail-0
08-26 10:52:59.361  7641  7997 V BluetoothOppNotification: inbound notification was removed.
08-26 10:52:59.361  7641  7997 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-26 10:52:59.362  7641  7997 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@17d649d6 on behalf of 
,08-26 10:52:59.530   324   895 D SoftapController: Softap fwReload - Ok
,08-26 10:52:59.545  1036  1440 E NetdConnector: NDC Command {84 softap fwreload wlan0 STA} took too long (658ms)
,08-26 10:52:59.556   324   895 D CommandListener: Setting iface cfg
08-26 10:52:59.556   324   895 D CommandListener: Trying to bring down wlan0
08-26 10:52:59.559  1036  1112 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-26 10:52:59.559  1036  1112 D Tethering: InitialState.processMessage what=4
08-26 10:52:59.560  1036  1112 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-26 10:52:59.564   324   895 D CommandListener: Clearing all IP addresses on wlan0
,08-26 10:52:59.583  1036  1440 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
08-26 10:52:59.583  8005  8005 W wpa_supplicant: type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-26 10:52:59.593  1036  1440 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-26 10:52:59.593  1036  1440 E WifiStateMachine: useWiFiOffloading() : false
08-26 10:52:59.593  1036  1440 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-26 10:52:59.593  8005  8005 W wpa_supplicant: type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 10:52:59.603  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-26 10:52:59.608  1943  1943 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-26 10:52:59.628  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 10:52:59.630  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-26 10:52:59.642  1036  1440 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-26 10:52:59.643  1036  1440 D WifiMonitor: connecting to supplicant
,08-26 10:52:59.648  6844  6844 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-26 10:52:59.648  6844  6844 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-26 10:52:59.649  6844  6844 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-26 10:52:59.649  6844  6844 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-26 10:52:59.650  6844  6844 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-26 10:52:59.651  6844  6844 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-26 10:52:59.651  6844  6844 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-26 10:52:59.651  6844  6844 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-26 10:52:59.651  6844  6844 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-26 10:52:59.651  6844  6844 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-26 10:52:59.652  6844  6844 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-26 10:52:59.655  6844  6844 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-26 10:52:59.655  6844  6844 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-26 10:52:59.655  6844  6844 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-26 10:52:59.656  6844  6844 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-26 10:52:59.656  6844  6844 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-26 10:52:59.658  6844  6844 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-26 10:52:59.658  6844  6844 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-26 10:52:59.658  6844  6844 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-26 10:52:59.658  6844  6844 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-26 10:52:59.658  6844  6844 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-26 10:52:59.659  6844  6844 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,08-26 10:52:59.664  8005  8005 I wpa_supplicant: Successfully initialized wpa_supplicant
08-26 10:52:59.698  1036  2014 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=8023 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-26 10:52:59.700  8005  8005 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-26 10:52:59.700  8005  8005 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
08-26 10:52:59.722   351   351 I art     : Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 376us total 24.379ms
,08-26 10:52:59.741   351   351 I art     : Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 399us total 18.345ms
08-26 10:52:59.756   351   351 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 288us total 13.447ms
,08-26 10:52:59.783  8005  8005 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-26 10:52:59.818  1036  1924 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=8044 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-26 10:52:59.822  8005  8005 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
08-26 10:52:59.825  8023  8042 W FormManager: Network not available. Please check & try again.
08-26 10:52:59.829  8023  8043 V FormManager: Network unavailable.
08-26 10:52:59.831  8023  8043 V FormManager: Network unavailable.
08-26 10:52:59.832  1036  1440 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-26 10:52:59.832  1036  1440 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-26 10:52:59.833  1036  1440 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-26 10:52:59.834  1036  1440 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-26 10:52:59.834  1036  1440 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-26 10:52:59.835  1036  1440 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-26 10:52:59.836  1036  1440 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-26 10:52:59.836  1036  1440 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-26 10:52:59.837  1036  1440 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-26 10:52:59.837  1036  1440 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-26 10:52:59.838  1036  1440 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-26 10:52:59.838  1036  1440 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-26 10:52:59.838  1036  1440 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-26 10:52:59.839  1036  8062 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-26 10:52:59.839  1036  8062 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-26 10:52:59.839  8005  8005 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-26 10:52:59.839  1036  8062 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-26 10:52:59.839  1036  8062 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-26 10:52:59.839  1036  8062 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-26 10:52:59.839  1036  8062 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-26 10:52:59.839  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 10:52:59.839  1036  1440 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-26 10:52:59.839  1036  1440 E WifiStateMachine: useWiFiOffloading() : false
08-26 10:52:59.839  1036  1440 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-26 10:52:59.840  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-26 10:52:59.840  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 10:52:59.840  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 10:52:59.840  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-26 10:52:59.842  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-26 10:52:59.843  1036  1468 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-26 10:52:59.845  1943  1943 D WfdService: Waiting for WifiP2p enabling
08-26 10:52:59.845  1036  1440 D WifiNative-wlan0: doBoolean: SET update_config 1
08-26 10:52:59.846  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 10:52:59.846  1036  1440 D WifiNative-wlan0: SET update_config 1: returned true
08-26 10:52:59.846  1036  1440 D WifiConfigStore: Loading config and enabling all networks 
08-26 10:52:59.846  1036  1440 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-26 10:52:59.846  1036  1440 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-26 10:52:59.848  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 10:52:59.848  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 10:52:59.848  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 10:52:59.848  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 10:52:59.848  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 10:52:59.848  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 10:52:59.848  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 10:52:59.848  6692  6692 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 10:52:59.850  6692  6692 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-26 10:52:59.852  1036  1440 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-26 10:52:59.860  1036  1440 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-26 10:52:59.861  1036  1440 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-26 10:52:59.862  1036  1440 D WifiStateMachine: enableVerboseLogging : level 2
08-26 10:52:59.862  1036  1440 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-26 10:52:59.862  1036  1440 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-26 10:52:59.862  1036  1440 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-26 10:52:59.863  1036  1440 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-26 10:52:59.863  1036  1440 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-26 10:52:59.863  1036  1440 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-26 10:52:59.863  1036  1440 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-26 10:52:59.864  1036  1440 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-26 10:52:59.864  1036  1440 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-26 10:52:59.864  1036  1440 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-26 10:52:59.864  1036  1440 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-26 10:52:59.865  1036  1440 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-26 10:52:59.865  1036  1440 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-26 10:52:59.865  1036  1440 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-26 10:52:59.866  1943  1943 D WfdsService: Supplicant Connection state is changed : true
08-26 10:52:59.866  1036  1440 D WifiStateMachine: Setting OUI to DA-A1-19
08-26 10:52:59.866  1943  2260 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-26 10:52:59.866  1036  1440 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-26 10:52:59.867  1943  2260 D WfdsService: Set the WFDS Monitor: true
08-26 10:52:59.867  1943  2260 D WfdsMonitor: WfdsMonitorThread create
08-26 10:52:59.867  7669  7669 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 10:52:59.867  1943  2260 D WfdsMonitor: WFDS Monitor is created and started
08-26 10:52:59.867  1943  2260 D WfdsService: WiFi: Supplicant connection re-established
08-26 10:52:59.867  1036  1440 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-26 10:52:59.867  1036  1440 D WifiNative-HAL: Setting external_sim to 1
08-26 10:52:59.867  1036  1440 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-26 10:52:59.867  1036  1440 D WifiNative-wlan0: SET external_sim 1: returned true
08-26 10:52:59.867  1036  1440 I WifiNative-HAL: startHal
08-26 10:52:59.868  1036  1440 D wifi    : setting scan oui 0xaf707080
08-26 10:52:59.868  1943  8063 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-26 10:52:59.868  1943  8063 E CtrlSupplicant: Succeed to open control connection
08-26 10:52:59.868  1036  1440 D WifiStateMachine: Setting OUI to DA-A1-19
08-26 10:52:59.868  1036  1440 I WifiNative-HAL: startHal
08-26 10:52:59.868  1943  8063 E CtrlSupplicant: Succeed to open monitor connection
08-26 10:52:59.868  1943  8063 D WfdsMonitor: Supplicant connection established
08-26 10:52:59.868  1036  1440 D wifi    : setting scan oui 0xaf707080
08-26 10:52:59.868  1943  2260 D WfdsService: Connected to the supplicant for wfds
08-26 10:52:59.869  1036  1440 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-26 10:52:59.869  1036  1440 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-26 10:52:59.869  1036  1440 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-26 10:52:59.869  8005  8005 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-26 10:52:59.869  1036  1440 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-26 10:52:59.869  1036  1440 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-26 10:52:59.870  8005  8005 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-26 10:52:59.870  1036  1440 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-26 10:52:59.870  1036  1440 D W,ifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-26 10:52:59.870  8005  8005 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-26 10:52:59.870  1036  1440 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-26 10:52:59.870  1036  1440 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-26 10:52:59.871  8005  8005 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-26 10:52:59.871  1036  1440 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-26 10:52:59.871  1036  1440 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-26 10:52:59.871  8005  8005 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-26 10:52:59.872  1036  1440 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
,08-26 10:52:59.872  1036  1440 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-26 10:52:59.872  8005  8005 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-26 10:52:59.872  1036  1440 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-26 10:52:59.872  1036  1440 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-26 10:52:59.872  8005  8005 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-26 10:52:59.872  1036  1440 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-26 10:52:59.873  1036  1440 E WifiNative: : [139,113,367 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-26 10:52:59.873  1036  1440 D WifiNative-wlan0: doBoolean: RECONNECT
08-26 10:52:59.874  1036  1440 D WifiNative-wlan0: RECONNECT: returned true
08-26 10:52:59.874  1036  1440 D WifiNative-wlan0: doString: [STATUS]
08-26 10:52:59.875  1036  8062 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-26 10:52:59.875  1036  8062 E WifiMonitor: WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-26 10:52:59.875  1036  1440 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-26 10:52:59.875  1036  1440 D WifiNative-wlan0: doBoolean: SET ps 1
08-26 10:52:59.876  1036  1440 D WifiNative-wlan0: SET ps 1: returned true
08-26 10:52:59.876  1036  1393 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-26 10:52:59.877  1036  1036 D WifiScanningService: SCAN_AVAILABLE : 3
08-26 10:52:59.877  1036  1036 D RttService: SCAN_AVAILABLE : 3
08-26 10:52:59.877  1036  1558 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-26 10:52:59.877  1036  1558 I WifiNative-HAL: startHal
08-26 10:52:59.877  1036  1559 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-26 10:52:59.878  1036  1558 D wifi    : getting scan capabilities on interface[1] = 0xaf707080
08-26 10:52:59.878  1036  1558 D wifi    : failed to get capabilities : -3
08-26 10:52:59.878  1036  1558 E WifiScanningService: could not get scan capabilities
08-26 10:52:59.878  1036  1440 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-26 10:52:59.878   324   895 D CommandListener: Setting iface cfg
08-26 10:52:59.878   324   895 D CommandListener: Trying to bring up p2p0
08-26 10:52:59.878  1036  1440 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-26 10:52:59.878  1036  1393 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-26 10:52:59.878  1036  1393 D LGWifiP2pService: P2pEnablingState
08-26 10:52:59.878  1036  1393 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-26 10:52:59.878  1036  1393 D LGWifiP2pService: P2p socket connection successful
08-26 10:52:59.878  1036  1393 D LGWifiP2pService: P2pEnabledState
08-26 10:52:59.878  1036  1440 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-26 10:52:59.879  1036  1440 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-26 10:52:59.879  1036  1440 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=139120  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-26 10:52:59.880  1943  1943 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-26 10:52:59.880  1943  1943 D WfdsService: WifiP2pState is changed : true
08-26 10:52:59.880  1943  2260 D WfdsService: Receive the WFDS_ENABLE Method
08-26 10:52:59.880  1943  2260 D WfdsService: Set the WFDS Monitor: true
08-26 10:52:59.880  1943  2260 D WfdsService: Connected to the supplicant for wfds
08-26 10:52:59.880  1943  2260 D WfdsJNI : doCommand: WFDS_SET TRUE,
08-26 10:52:59.880  8005  8005 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-26 10:52:59.880  1943  2260 D WfdsService: selectPreferredScanChannel [36]
08-26 10:52:59.880  1943  2260 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-26 10:52:59.880  1036  1393 D LGWifiP2pService: sending p2p connection changed broadcast
08-26 10:52:59.881  1036  1440 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=139121  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-26 10:52:59.881  1036  1440 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-26 10:52:59.882  1036  1440 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-26 10:52:59.882  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 10:52:59.882  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 10:52:59.882  1036  1440 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-26 10:52:59.882  1036  1440 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-26 10:52:59.882  8005  8005 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-26 10:52:59.883  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 10:52:59.883  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 10:52:59.883  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-26 10:52:59.883  1036  1440 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-26 10:52:59.883  1036  1393 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-26 10:52:59.884  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 10:52:59.884  8044  8044 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-26 10:52:59.884  1943  1943 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-26 10:52:59.885  1943  1943 D WfdsService: isConnected: false
08-26 10:52:59.885  1036  1440 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-26 10:52:59.885  1036  1393 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
,08-26 10:52:59.886  1036  1393 D WifiNative-p2p0: doBoolean: SET device_name G3
08-26 10:52:59.886  1036  1393 D WifiNative-p2p0: SET device_name G3: returned true
08-26 10:52:59.886  1036  1393 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-26 10:52:59.886  1036  1393 D LGWifiP2pService: before postfix = G3
08-26 10:52:59.886  1036  1393 D WifiServerServiceExt: postfix byte check : 2
08-26 10:52:59.886  1036  1393 D LGWifiP2pService: after postfix = G3
08-26 10:52:59.886  1036  1393 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-26 10:52:59.886  1036  1393 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-26 10:52:59.886  1036  1393 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-26 10:52:59.886  1036  1393 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-26 10:52:59.886  1036  1393 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-26 10:52:59.887  1036  1393 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-26 10:52:59.887  1036  1393 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
,08-26 10:52:59.888  1036  1393 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-26 10:52:59.888  1036  1393 D WifiNative-HAL: p2pGetDeviceAddress
08-26 10:52:59.888  1036  1393 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-26 10:52:59.888  1036  1393 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-26 10:52:59.888  1036  1393 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-26 10:52:59.889  1943  1943 I WfdStateTracker: handleP2pThisDeviceChanged
08-26 10:52:59.889  1943  1943 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-26 10:52:59.889  1943  1943 D WfdsService: Update P2p Interface State: 3
08-26 10:52:59.889  1036  1393 D WifiNative-p2p0: P2P_FLUSH: returned true
,08-26 10:52:59.890  1036  1393 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-26 10:52:59.890  1036  1393 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-26 10:52:59.890  1036  1393 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-26 10:52:59.890  1036  1393 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-26 10:52:59.890  1036  1393 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-26 10:52:59.891  1036  1440 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-26 10:52:59.891  1036  1440 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-26 10:52:59.894  6844  6844 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-26 10:52:59.900  8005  8005 E wpa_supplicant: disconnect_rssi_lvl: -100
08-26 10:52:59.900  6692  6782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 10:52:59.900  6692  6782 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 10:52:59.900  6692  6782 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 10:52:59.900  6692  6782 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 10:52:59.900  6692  6782 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 10:52:59.900  6692  6782 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 10:52:59.900  6692  6782 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 10:52:59.900  6692  6782 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 10:52:59.900  1036  1393 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-26 10:52:59.900  1036  1393 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-26 10:52:59.900  1036  1393 D LGWifiP2pService: InactiveState
08-26 10:52:59.900  1036  1393 D LGWifiP2pService: InactiveState{ when=-11ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-26 10:52:59.900  1036  1393 D LGWifiP2pService: P2pEnabledState{ when=-11ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-26 10:52:59.901  1036  1393 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-26 10:52:59.901  8005  8005 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-26 10:52:59.901  8005  8005 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 10:52:59.901  1943  8063 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-26 10:52:59.902  1036  8062 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-26 10:52:59.902  1036  8062 E WifiMonitor: WifiMonitor:p2p0 cnt=47 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 10:52:59.902  1036  8062 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 10:52:59.902  1036  8062 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 10:52:59.902  8005  8005 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-26 10:52:59.902  8005  8005 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,08-26 10:52:59.902  1943  8063 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 10:52:59.902  1036  8062 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 10:52:59.902  1036  8062 E WifiMonitor: WifiMonitor:p2p0 cnt=48 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 10:52:59.902  1036  8062 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 10:52:59.902  1036  8062 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 10:52:59.902  8005  8005 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 10:52:59.902  6692  6782 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-26 10:52:59.903  1943  8063 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 10:52:59.903  1036  8062 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 10:52:59.903  1036  8062 E WifiMonitor: WifiMonitor:p2p0 cnt=49 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 10:52:59.903  1036  8062 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 10:52:59.903  1036  8062 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 10:52:59.903  1036  1440 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
08-26 10:52:59.903  1036  1440 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
08-26 10:52:59.903  1036  1440 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
08-26 10:52:59.903  1036  1440 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-26 10:52:59.903  1036  1393 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-26 10:52:59.904  1036  1393 D LGWifiP2pService: InactiveState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-26 10:52:59.904  1036  1393 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-26 10:52:59.904  1036  1393 D LGWifiP2pService: DefaultState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-26 10:52:59.904  1036  1393 D LGWifiP2pService: InactiveState{ when=-3ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-26 10:52:59.904  1036  1393 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-26 10:52:59.904  1036  1393 D LGWifiP2pService: DefaultState{ when=-3ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-26 10:52:59.904  1036  1393 D LGWifiP2pService: InactiveState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-26 10:52:59.904  1036  1393 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-26 10:52:59.904  1036  1393 D LGWifiP2pService: DefaultState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-26 10:52:59.904  1036  1393 D LGWifiP2pService: InactiveState{ when=-3ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-26 10:52:59.904  1036  1393 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-26 10:52:59.904  1036  1393 D LGWifiP2pService: DefaultState{ when=-4ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-26 10:52:59.904  1036  1036 E WifiServerServiceExt: No p2p device connected
08-26 10:52:59.905  1943  2260 W WfdsService: DefaultState - msg [9441285] is not handled
08-26 10:52:59.905  8005  8005 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-26 10:52:59.905  8005  8005 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHA,NGE init=USER type=COUNTRY alpha2=CZ
08-26 10:52:59.906  1036  8062 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-26 10:52:59.906  1036  8062 E WifiMonitor: WifiMonitor:wlan0 cnt=50 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 10:52:59.906  1036  8062 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 10:52:59.906  1036  8062 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 10:52:59.906  8005  8005 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-26 10:52:59.906  8005  8005 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 10:52:59.906  1943  8063 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 10:52:59.906  1036  8062 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 10:52:59.906  1036  8062 E WifiMonitor: WifiMonitor:p2p0 cnt=51 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 10:52:59.906  1036  8062 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 10:52:59.906  1036  8062 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 10:52:59.906  8005  8005 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 10:52:59.906  1943  8063 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 10:52:59.906  1036  8062 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 10:52:59.906  1036  8062 E WifiMonitor: WifiMonitor:p2p0 cnt=52 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 10:52:59.906  1036  8062 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 10:52:59.907  1036  8062 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 10:52:59.907  1036  1440 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-26 10:52:59.908  1036  1440 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-26 10:52:59.908  6844  6844 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 10:52:59.908  1036  1440 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-26 10:52:59.908  1036  1440 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-26 10:52:59.908  6692  6782 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
08-26 10:52:59.908  1036  1440 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-26 10:52:59.908  8005  8005 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-26 10:52:59.908  8005  8005 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-26 10:52:59.909  1036  8062 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-26 10:52:59.909  1036  8062 E WifiMonitor: WifiMonitor:wlan0 cnt=53 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-26 10:52:59.909  1036  8062 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-26 10:52:59.909  1036  8062 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-26 10:52:59.909  6692  6782 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-26 10:52:59.909  1036  1737 I ActivityManager: Killing 7203:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
08-26 10:52:59.910  1036  1393 D LGWifiP2pService: InactiveState{ when=-2ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-26 10:52:59.910  1036  1393 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-26 10:52:59.910  1036  1440 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-26 10:52:59.910  1036  1440 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-26 10:52:59.911  1036  1440 D WifiNative-wlan0: BSS_FLUS,H 0: returned true
08-26 10:52:59.911  1036  1440 D WifiNative-wlan0: doBoolean: SCAN
08-26 10:52:59.911  1036  1440 D WifiNative-wlan0: SCAN: returned false
08-26 10:52:59.911  6692  6782 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@1240a38f Bundle[{}]
08-26 10:52:59.911  1036  1440 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=139151  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-26 10:52:59.912  6692  6782 I io.jxcore.node.LifeCycleMonitor: start: OK
08-26 10:52:59.912  6692  6782 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-26 10:52:59.912  6692  6782 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-26 10:52:59.913  6692  6782 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-26 10:52:59.914  6692  6782 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-26 10:52:59.914  6692  6782 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-26 10:52:59.920  6692  6782 I System.out: Running OutgoingSocketThread
08-26 10:52:59.922  6692  8067 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 851)
08-26 10:52:59.923  6692  8067 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 34332
08-26 10:52:59.923  6692  8067 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
08-26 10:52:59.939  1036  1923 W libprocessgroup: failed to open /acct/uid_10085/pid_7203/cgroup.procs: No such file or directory
08-26 10:52:59.940  1036  1440 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=139180  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-26 10:52:59.942  1036  1440 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-26 10:52:59.943  1036  1440 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-26 10:52:59.943  1036  1440 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-26 10:52:59.943  1036  1440 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-26 10:52:59.943  1036  1440 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-26 10:52:59.945  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 10:52:59.945  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 10:52:59.945  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-26 10:52:59.945  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 10:52:59.945  1036  1036 D WifiServerServiceExt: setSupplicantStateSCANNING
08-26 10:52:59.945  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 10:52:59.945  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 10:52:59.946  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 10:52:59.954  8044  8044 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-26 10:52:59.959  6844  6844 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-26 10:52:59.962  8023  8069 W FormManager: Network not available. Please check & try again.
08-26 10:52:59.963  8023  8070 V FormManager: Network unavailable.
08-26 10:52:59.963  6844  6844 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 10:52:59.968  8023  8070 V FormManager: Network unavailable.
,08-26 10:52:59.978  4298  4298 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-26 10:52:59.978  4298  4298 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-26 10:52:59.980  4298  4298 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 10:52:59.983  4298  4298 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-26 10:52:59.988  4298  8071 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-26 10:52:59.993  4298  8072 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-26 10:52:59.993  4298  8072 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-26 10:53:00.040  1604  1604 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-26 10:53:00.040  1604  1604 I KeyguardUpdateMonitor: called onTimeUpdated()
08-26 10:53:00.041  1604  1604 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-26 10:53:00.041  1604  1604 I [SystemUI]Clock: called onTimeUpdated()
,08-26 10:53:00.044  1604  1604 I LgeClockWidgetControlView: called onTimeUpdated()
08-26 10:53:00.044  1604  1604 I [SystemUI]DateView: called onTimeUpdated()
08-26 10:53:00.046  1604  1604 I [SystemUI]DateView: called onTimeUpdated()
,08-26 10:53:00.047  1604  1604 D KeyguardUpdateMonitor: handleTimeUpdate
08-26 10:53:00.048  1036  1784 I ActivityManager: Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=8073 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-26 10:53:00.135  8073  8073 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-26 10:53:00.166  8073  8073 D PluginManager: init()
,08-26 10:53:00.513  8005  8005 E wpa_supplicant: USIM:  scard_init function
,08-26 10:53:00.513  8005  8005 I wpa_supplicant: Trying to associate with SSID 'NG700'
,08-26 10:53:00.522  1036  8062 E WifiMonitor: WifiMonitor:wlan0 cnt=54 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
,08-26 10:53:00.523  1036  8062 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
,08-26 10:53:00.523  1036  8062 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-26 10:53:00.523  1036  8062 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: WPS-AP-AVAILABLE 
,08-26 10:53:00.523  1036  1440 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
,08-26 10:53:00.523  1036  8062 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
,08-26 10:53:00.523  1036  8062 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
,08-26 10:53:00.523  1036  1440 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
,08-26 10:53:00.523  1036  8062 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
,08-26 10:53:00.524  1036  1440 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-26 10:53:00.524  1036  1440 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-26 10:53:00.524  1036  1440 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-26 10:53:00.532  1036  1440 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=139772  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-26 10:53:00.536  1036  1440 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=139776  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-26 10:53:00.537  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 10:53:00.538  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-26 10:53:00.539  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 10:53:00.539  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 10:53:00.539  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 10:53:00.539  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
,08-26 10:53:00.539  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 10:53:00.539  1036  1036 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-26 10:53:00.637  8005  8005 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-26 10:53:00.647  1036  8062 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-26 10:53:00.647  1036  8062 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-26 10:53:00.648  1036  8062 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-26 10:53:00.648  1036  8062 E WifiMonitor: WifiMonitor:wlan0 cnt=58 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-26 10:53:00.648  1036  8062 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-26 10:53:00.648  1036  8062 E WifiMonitor: WifiMonitor:wlan0 cnt=59 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-26 10:53:00.649  8005  8005 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-26 10:53:00.649  1036  1440 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=139889  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-26 10:53:00.649  8005  8005 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-26 10:53:00.651  1036  8062 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-26 10:53:00.651  1036  8062 E WifiMonitor: WifiMonitor:wlan0 cnt=60 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-26 10:53:00.651  1036  8062 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-26 10:53:00.651  1036  8062 E WifiMonitor: WifiMonitor:wlan0 cnt=61 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-26 10:53:00.651  1036  8062 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP],
08-26 10:53:00.651  1036  8062 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-26 10:53:00.651  1036  8062 E WifiMonitor: WifiMonitor:wlan0 cnt=62 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-26 10:53:00.651  1036  8062 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-26 10:53:00.651  1036  1440 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=139891  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-26 10:53:00.653  1036  8062 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-26 10:53:00.653  1036  1440 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=139893
08-26 10:53:00.653  1036  8062 E WifiMonitor: WifiMonitor:wlan0 cnt=63 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-26 10:53:00.654  1036  1440 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=139894
08-26 10:53:00.655  1036  1440 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=139895
08-26 10:53:00.656  1036  1440 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=139896
08-26 10:53:00.660  1036  1440 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=139900
,08-26 10:53:00.662  1036  1112 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-26 10:53:00.669  1036  1440 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=139909  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-26 10:53:00.673  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 10:53:00.673  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 10:53:00.673  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
,08-26 10:53:00.674  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 10:53:00.674  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 10:53:00.678  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 10:53:00.683  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 10:53:00.683  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 10:53:00.683  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-26 10:53:00.684  1036  1440 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=139924  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-26 10:53:00.684  1036  1440 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=139925  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-26 10:53:00.685  1036  1440 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=139925  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-26 10:53:00.686  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 10:53:00.686  1036  1036 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-26 10:53:00.687  1036  1440 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=139928
,08-26 10:53:00.688  1036  1440 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=139928
08-26 10:53:00.688  1036  1440 D WifiNative-wlan0: doString: [STATUS]
08-26 10:53:00.689  1036  8062 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-26 10:53:00.689  1036  8062 E WifiMonitor: WifiMonitor:wlan0 cnt=64 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-26 10:53:00.690  1036  1440 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-26 10:53:00.691  1036  1440 I WifiServiceExtension: setVHTCapabilityType  : false
,08-26 10:53:00.698  1036  1440 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-26 10:53:00.698  1036  1440 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
08-26 10:53:00.699  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 10:53:00.699  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 10:53:00.700  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 10:53:00.706  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 10:53:00.706  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 10:53:00.706  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-26 10:53:00.707  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 10:53:00.707  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 10:53:00.707  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,08-26 10:53:00.716  1036  1440 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-26 10:53:00.717  1036  1495 D ConnectivityService: Got NetworkAgent Messenger
08-26 10:53:00.717  1036  1440 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-26 10:53:00.717  1036  1495 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-26 10:53:00.717  1036  1495 D ConnectivityService: NetworkAgent connected
08-26 10:53:00.717  1036  1440 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
,08-26 10:53:00.722  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 10:53:00.722  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 10:53:00.722  1036  1440 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-26 10:53:00.722  1036  1440 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-26 10:53:00.723  8073  8073 W ExternalStrings: load override strings
08-26 10:53:00.723  8073  8073 W ExternalStrings: java.lang.RuntimeException: Unexpected tag, got eat-comment
08-26 10:53:00.723  8073  8073 W ExternalStrings: 	at com.mcafee.plugin.af.a(Unknown Source)
08-26 10:53:00.723  8073  8073 W ExternalStrings: 	at com.mcafee.plugin.ac.b(Unknown Source)
08-26 10:53:00.723  8073  8073 W ExternalStrings: 	at com.mcafee.plugin.ak.d(Unknown Source)
08-26 10:53:00.723  8073  8073 W ExternalStrings: 	at com.mcafee.plugin.ak.a(Unknown Source)
08-26 10:53:00.723  8073  8073 W ExternalStrings: 	at com.mcafee.app.s.getClassLoader(Unknown Source)
08-26 10:53:00.723  8073  8073 W ExternalStrings: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
08-26 10:53:00.723  8073  8073 W ExternalStrings: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-26 10:53:00.723  8073  8073 W ExternalStrings: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-26 10:53:00.723  8073  8073 W ExternalStrings: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-26 10:53:00.723  8073  8073 W ExternalStrings: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-26 10:53:00.723  8073  8073 W ExternalStrings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 10:53:00.723  8073  8073 W ExternalStrings: 	at android.os.Looper.loop(Looper.java:135)
08-26 10:53:00.723  8073  8073 W ExternalStrings: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-26 10:53:00.723  8073  8073 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 10:53:00.723  8073  8073 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 10:53:00.723  8073  8073 W ExternalStrings: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-26 10:53:00.723  8073  8073 W ExternalStrings: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-26 10:53:00.724  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 10:53:00.726  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 10:53:00.726  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 10:53:00.728  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 10:53:00.728  8073  8073 D StatusProvider: onCreate
08-26 10:53:00.730  1036  1440 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-26 10:53:00.730  1036  1440 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-26 10:53:00.730  1036  1440 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-26 10:53:00.731  1036  1440 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-26 10:53:00.731  1036  1440 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
,08-26 10:53:00.735  1036  1440 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-26 10:53:00.738   324   895 D CommandListener: Setting iface cfg
08-26 10:53:00.741  1036  1440 E WifiStateMachine: Start Dhcp Watchdog 3
08-26 10:53:00.741  1036  8108 D DhcpStateMachine: StoppedState
08-26 10:53:00.741  1036  8108 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-26 10:53:00.741  1036  8108 D DhcpStateMachine: WaitBeforeStartState
08-26 10:53:00.742  1036  1440 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=139982  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-26 10:53:00.742  1036  1440 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=139983  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-26 10:53:00.743  1036  1440 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=139983  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
,08-26 10:53:00.744  1036  1440 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
08-26 10:53:00.744  1036  1440 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
08-26 10:53:00.744  1036  1440 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-26 10:53:00.745  1036  1440 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-26 10:53:00.745  1036  1440 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-26 10:53:00.745  1036  1440 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-26 10:53:00.747  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 10:53:00.747  1036  1036 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-26 10:53:00.749  1036  1440 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=139989  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-26 10:53:00.749  1036  1440 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=139990  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-26 10:53:00.750  1036  1440 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=139990  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-26 10:53:00.751  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 10:53:00.751  1036  1036 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-26 10:53:00.752  1036  1440 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:14522] from screen [on:0 period:-972201776] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-26 10:53:00.753  1036  1440 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-972201775] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-26 10:53:00.753  1036  1440 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-26 10:53:00.756  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 10:53:00.758  1036  1440 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 10:53:00.758  1036  1495 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
08-26 10:53:00.758  1036  1440 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
,08-26 10:53:00.759  1036  1440 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 10:53:00.759  1036  1440 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 10:53:00.762  1036  1440 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 10:53:00.762  1036  1440 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 10:53:00.763  1036  1495 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-26 10:53:00.763  1036  1440 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=139,0,0
08-26 10:53:00.764  1036  1440 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=139,0,0
08-26 10:53:00.764  1036  1440 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-26 10:53:00.764  8005  8005 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-26 10:53:00.764  1036  1440 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-26 10:53:00.764  1036  1440 D WifiNative-wlan0: doBoolean: SET ps 0
08-26 10:53:00.765  1036  1440 D WifiNative-wlan0: SET ps 0: returned true
08-26 10:53:00.765  1036  1440 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-26 10:53:00.765  8005  8005 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-26 10:53:00.765  1036  1440 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-26 10:53:00.766  1036  1440 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-26 10:53:00.766  1036  1440 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-26 10:53:00.766  1036  1440 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-26 10:53:00.766  1036  1393 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@14233e92 target=com.android.internal.util.StateMachine$SmHandler }
08-26 10:53:00.766  1036  1393 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@14233e92 target=com.android.internal.util.StateMachine$SmHandler }
08-26 10:53:00.766  1036  8108 D DhcpStateMachine: WaitBeforeStartState{ when=-1ms what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-26 10:53:00.766  1036  8108 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-26 10:53:00.768   324   895 D CommandListener: Setting iface cfg
08-26 10:53:00.768   324   895 D CommandListener: Trying to bring up wlan0
08-26 10:53:00.769  1036  1440 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-26 10:53:00.769  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 10:53:00.769  1036  1036 D WifiServerServiceExt: setSupplicantStateCOMPLETED
,08-26 10:53:00.771  1036  1440 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK 
08-26 10:53:00.771  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 10:53:00.771  1036  1036 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-26 10:53:00.771  1036  1440 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK 
08-26 10:53:00.771  1036  1440 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-26 10:53:00.771  8005  8005 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-26 10:53:00.772  1036  1393 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-26 10:53:00.772  1036  1393 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-26 10:53:00.772  1036  1440 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-26 10:53:00.772  1036  1440 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-26 10:53:00.773  8005  8005 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-26 10:53:00.773  1036  1440 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-26 10:53:00.773  1036  1440 D WifiNative-wlan0: doBoolean: SET ps 1
08-26 10:53:00.792  1036  1440 D WifiNative-wlan0: SET ps 1: returned true
08-26 10:53:00.793  1036  1495 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-26 10:53:00.793  1036  1440 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-26 10:53:00.794  8073  8073 V Signer  : override build config not found
,08-26 10:53:00.794  1036  1440 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-26 10:53:00.794  8073  8073 D Signer  : value of property debug is false
08-26 10:53:00.795  1036  1440 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-26 10:53:00.796  1036  1440 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-26 10:53:00.797  1036  1440 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-26 10:53:00.798  1036  1440 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-26 10:53:00.799  1036  1495 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-26 10:53:00.800  1036  1440 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-26 10:53:00.800  1036  1440 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-26 10:53:00.800  1036  1440 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-26 10:53:00.801  1036  1495 D ConnectivityService: ignoring duplicate network state non-change
08-26 10:53:00.804  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 10:53:00.804  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 10:53:00.805  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 10:53:00.805  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 10:53:00.805  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 10:53:00.805  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-26 10:53:00.806  1036  1495 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-26 10:53:00.808  1036  1495 D ConnectivityService: Adding iface wlan0 to network 102
08-26 10:53:00.809  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 10:53:00.809  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 10:53:00.809  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-26 10:53:00.811  1036  1440 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-26 10:53:00.813  1036  1036 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-26 10:53:00.815  1943  1943 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-26 10:53:00.817  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 10:53:00.817  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 10:53:00.817  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-26 10:53:00.818  1036  1036 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-26 10:53:00.822  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 10:53:00.822  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 10:53:00.822  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-26 10:53:00.825  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 10:53:00.825  1604  1604 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 10:53:00.826  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-26 10:53:00.828  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 10:53:00.828  1604  1604 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-26 10:53:00.828  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 10:53:00.831  1604  1604 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 10:53:00.831  1604  1604 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-26 10:53:00.831  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 10:53:00.837  8073  8073 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
08-26 10:53:00.837  8073  8073 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
08-26 10:53:00.837  8073  8073 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
08-26 10:53:00.838  1036  1495 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-26 10:53:00.838  8073  8073 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
08-26 10:53:00.838  1036  1495 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
08-26 10:53:00.838  8073  8073 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
08-26 10:53:00.838  8073  8073 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
08-26 10:53:00.839  8073  8073 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
08-26 10:53:00.839  1036  1495 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
08-26 10:53:00.839  8073  8073 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
08-26 10:53:00.839   324   895 E Netd    : netlink response contains error (File exists)
08-26 10:53:00.839  1036  1495 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,08-26 10:53:00.840  8073  8073 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
08-26 10:53:00.840  8073  8073 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
08-26 10:53:00.840  8073  8073 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
08-26 10:53:00.840  8073  8073 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
08-26 10:53:00.841  8073  8073 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
,08-26 10:53:00.841  1036  1495 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-26 10:53:00.841  1036  1495 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 102
08-26 10:53:00.841  1036  1495 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
08-26 10:53:00.842  1036  1495 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-26 10:53:00.842  1036  1495 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-26 10:53:00.842  1036  1495 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-26 10:53:00.842  1036  1495 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-26 10:53:00.842  1036  1495 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 10:53:00.842  1036  1495 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 10:53:00.842  1036  1495 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-26 10:53:00.842  1036  1495 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 10:53:00.842  1036  1495 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-26 10:53:00.842  1036  1495 D ConnectivityService: currentScore = 0, newScore = 20
08-26 10:53:00.842  1036  1495 D ConnectivityService:    accepting network in place of null
08-26 10:53:00.842  1036  1495 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 10:53:00.842  1036  8096 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-26 10:53:00.842  1036  8096 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-26 10:53:00.843  1036  8096 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-26 10:53:00.843  1036  8096 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-26 10:53:00.843  1854  1854 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 10:53:00.843  1854  1854 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-26 10:53:00.844  1036  1495 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-26 10:53:00.844  1036  1495 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
08-26 10:53:00.844   324  8113 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
,08-26 10:53:00.844  1036  1495 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-26 10:53:00.845  1036  1440 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 10:53:00.846  1036  1440 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 10:53:00.848  1036  1495 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-26 10:53:00.848  1036  1495 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-26 10:53:00.848  1036  1495 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-26 10:53:00.849  1036  1495 D ConnectivityService: validation of new default Network = false
08-26 10:53:00.849  1036  1495 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-26 10:53:00.849  1036  1495 D DSQN    : enableDataServiceNotify 
08-26 10:53:00.849  1036  1495 D DSQN    : start dsqn bin
08-26 10:53:00.850  1036  1036 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-26 10:53:00.850  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-26 10:53:00.850  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-26 10:53:00.850  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-26 10:53:00.856  1036  1495 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-26 10:53:00.856  1036  1495 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 10:53:00.856  1036  1495 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 10:53:00.856  1036  1495 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 10:53:00.853  8114  8114 W dsqn    : type=1400 audit(0.0:193): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 10:53:00.853  8114  8114 W dsqn    : type=1400 audit(0.0:194): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 10:53:00.859  8073  8073 V LGMDMManager: Create singleton instance
08-26 10:53:00.861  1604  2075 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-26 10:53:00.863  1036  1392 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
08-26 10:53:00.870  8114  8114 E DSQN    : DSQN ssw
,08-26 10:53:00.875  1604  1604 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-26 10:53:00.876  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 10:53:00.877  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 10:53:00.896   324  8113 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,08-26 10:53:00.908  8073  8073 D LGMDMWrapper: LG MDM library v4.0.0 is available on this device.
,08-26 10:53:00.923  6692  6782 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 852)
08-26 10:53:00.923  6692  6782 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 852)
,08-26 10:53:00.928   324  8113 D libc-netbsd: res_queryN name = clients3.google.com succeed
08-26 10:53:00.932  6692  6782 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 857)
08-26 10:53:00.936  6692  6782 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-26 10:53:00.936  6692  6782 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 858)
08-26 10:53:00.940  6692  6782 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 10:53:00.940  6692  6782 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23371faa added. We now have 2 listener(s)
08-26 10:53:00.941  1036  2005 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 10:53:00.944  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-26 10:53:00.944  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 10:53:00.944  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-26 10:53:00.944  6692  6782 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 10:53:00.944  6692  6782 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@319a779b added. We now have 9 listener(s)
08-26 10:53:00.944  6692  6782 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 10:53:00.944  8073  8073 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 10:53:00.944  6692  6782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-26 10:53:00.945  8073  8120 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-26 10:53:00.950  6692  6782 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 10:53:00.954  6844  6844 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-26 10:53:00.955  6692  6782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 10:53:00.955  6692  6782 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 10:53:00.955  6692  6782 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 10:53:00.955  6692  6782 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 10:53:00.955  6692  6782 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 10:53:00.955  6692  6782 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 10:53:00.955  6692  6782 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 10:53:00.955  6692  6782 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 10:53:00.957  6692  6782 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 10:53:00.957  6692  6782 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 10:53:00.957  6692  6782 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 10:53:00.957  6692  6782 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e406311 added. We now have 3 listener(s)
08-26 10:53:00.957  1036  1923 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 10:53:00.958   324   894 D LGDataListener: argv[0]=dsqncommand
08-26 10:53:00.958   324   894 D LGDataListener: argv[1]=wlan0
08-26 10:53:00.958   324   894 D LGDataListener: argv[2]=1
08-26 10:53:00.958   324   894 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-26 10:53:00.959  1036  1110 D DSQN    : DSQM DsqnNotification wlan0  1
,08-26 10:53:00.959  1036  1110 D DSQN    : start to monitor internet connection
08-26 10:53:00.960  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 10:53:00.962  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-26 10:53:00.962  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 10:53:00.962  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 10:53:00.962  6692  6782 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 10:53:00.962  6692  6782 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fbf8c76 added. We now have 10 listener(s)
08-26 10:53:00.962  6692  6782 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 10:53:00.963  6692  6782 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 10:53:00.963  6692  6782 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 10:53:00.963  6692  6782 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 10:53:00.963  6692  6782 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 10:53:00.963  6692  6782 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:53:00.963  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 10:53:00.963  6692  6782 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 10:53:00.963  6692  6782 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23371faa removed from the list
08-26 10:53:00.963  6692  6782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:53:00.963  6692  6782 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@319a779b removed from the list
08-26 10:53:00.964  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 10:53:00.964  6844  6844 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 10:53:00.964  6692  6782 D io.jxcore.node.ConnectivityMonitor: stop
,08-26 10:53:00.964  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:53:00.968  6692  6782 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:53:00.968  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 10:53:00.970  6692  6782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 10:53:00.970  6692  6782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 10:53:00.970  6692  6782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:53:00.970  6692  6782 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@319a779b not in the list
08-26 10:53:00.970  6692  6782 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:53:00.970  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:53:00.971  6692  6782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 10:53:00.971  6692  6782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 10:53:00.971  6692  6782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:53:00.971  6692  6782 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fbf8c76 removed from the list
08-26 10:53:00.971  6692  6782 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 10:53:00.971  6692  6782 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:53:00.973  8125  8125 W dhcpcd  : type=1400 audit(0.0:195): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 10:53:00.973  8125  8125 W dhcpcd  : type=1400 audit(0.0:196): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 10:53:00.971  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:53:00.971  6692  6782 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 10:53:00.972  6692  6782 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e406311 removed from the list
08-26 10:53:00.973  6692  6782 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 10:53:00.973  6692  6782 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a9ef277 added. We now have 2 listener(s)
,08-26 10:53:00.973  1036  1784 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 10:53:00.981  1036  8108 D DhcpStateMachine: DHCPV4 request on wlan0
08-26 10:53:00.982  1036  8108 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-26 10:53:00.983  1036  8108 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-26 10:53:00.984  6918  6918 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 10:53:00.985  6918  6918 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 10:53:00.986  6918  6918 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-26 10:53:00.986  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-26 10:53:00.986  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 10:53:00.989  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 10:53:00.989  6692  6782 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 10:53:00.989  6692  6782 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1297aee4 added. We now have 9 listener(s)
08-26 10:53:00.989  6692  6782 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 10:53:00.990  1036  8096 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 26 Aug 2016 08:53:00 GMT], X-Android-Received-Millis=[1472201580989], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472201580958]}
08-26 10:53:00.990  1036  8096 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-26 10:53:00.990  1036  8096 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-26 10:53:00.991  6692  6782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-26 10:53:00.993  1036  1495 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
08-26 10:53:00.993  1036  1495 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-26 10:53:00.993  1036  1495 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 10:53:00.993  1036  1495 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 10:53:00.993  1036  1495 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-26 10:53:00.993  1036  1495 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
08-26 10:53:00.993  1036  1495 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-26 10:53:00.993  1036  1495 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 10:53:00.993  1036  1495 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 10:53:00.994  1036  1495 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 10:53:00.994  1036  1495 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTE,D&TRUSTED&NOT_VPN] ]
08-26 10:53:00.994  8125  8125 I dhcpcd  : version 5.5.6 starting
08-26 10:53:00.995  1604  2075 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-26 10:53:00.995  1036  1440 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 10:53:00.995  1036  1440 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 10:53:00.995  1036  1495 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-26 10:53:00.995  1854  1854 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 10:53:00.995  1854  1854 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-26 10:53:00.996  8125  8125 E dhcpcd  : get_duid: m
08-26 10:53:00.996  8125  8125 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-26 10:53:00.996  8125  8125 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-26 10:53:01.031  1036  1053 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=8131 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-26 10:53:01.032  1036  1053 I ActivityManager: Killing 7241:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
08-26 10:53:01.043  8125  8125 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-26 10:53:01.043  8125  8125 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-26 10:53:01.043  8125  8125 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-26 10:53:01.044  8125  8125 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
08-26 10:53:01.044  8125  8125 D dhcpcd  : wlan0: sending REQUEST (xid 0x204d0e77), next in 4.34 seconds
,08-26 10:53:01.088  8125  8125 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
,08-26 10:53:01.117  8125  8125 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
,08-26 10:53:01.118  8125  8125 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
08-26 10:53:01.118  8125  8125 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-26 10:53:01.119  8125  8125 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-26 10:53:01.119  8125  8125 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-26 10:53:01.120  8125  8125 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
,08-26 10:53:01.120  8125  8125 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-26 10:53:01.120  8125  8125 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-26 10:53:01.139  8073  8119 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-26 10:53:01.259  1036  1736 W libprocessgroup: failed to open /acct/uid_10093/pid_7241/cgroup.procs: No such file or directory
,08-26 10:53:01.260  6692  6782 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 10:53:01.271  6692  6782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 10:53:01.271  6692  6782 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 10:53:01.271  6692  6782 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 10:53:01.271  6692  6782 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 10:53:01.271  6692  6782 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 10:53:01.271  6692  6782 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 10:53:01.271  6692  6782 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 10:53:01.271  6692  6782 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 10:53:01.278  6692  6782 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 10:53:01.278  6692  6782 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 10:53:01.280  6692  6782 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 10:53:01.280  6692  6782 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@278ffa02 added. We now have 3 listener(s)
08-26 10:53:01.283  1036  1053 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 10:53:01.285  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 10:53:01.290  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-26 10:53:01.290  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 10:53:01.290  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 10:53:01.290  6692  6782 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 10:53:01.290  6692  6782 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16063f13 added. We now have 10 listener(s)
08-26 10:53:01.290  6692  6782 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 10:53:01.290  6692  6782 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 10:53:01.290  6692  6782 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 10:53:01.291  6692  6782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 10:53:01.291  6692  6782 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 10:53:01.291  6692  6782 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-26 10:53:01.297  6692  6782 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-26 10:53:01.297  1036  1970 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 10:53:01.298  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 10:53:01.304  6692  6782 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-26 10:53:01.304  6692  6782 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-26 10:53:01.309  1604  1604 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-26 10:53:01.310  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 10:53:01.311  1604  1604 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 10:53:01.311  6692  6782 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-26 10:53:01.312  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 10:53:01.315  6692  6782 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-26 10:53:01.315  6692  6782 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 10:53:01.315  6692  6782 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-26 10:53:01.317  6692  6782 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 10:53:01.317  6692  6782 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 10:53:01.317  6692  6782 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 10:53:01.318  6692  6782 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 10:53:01.318  6692  6782 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:53:01.318  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 10:53:01.318  6692  6782 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 10:53:01.318  6692  6782 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a9ef277 removed from the list
08-26 10:53:01.318  6692  6782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:53:01.318  6692  6782 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1297aee4 removed from the list
08-26 10:53:01.318  6692  6782 D io.jxcore.node.ConnectivityMonitor: stop
08-26 10:53:01.318  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:53:01.319  6692  6782 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 10:53:01.319  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:53:01.321  6692  6782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 10:53:01.321  6692  6782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 10:53:01.321  6692  6782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:53:01.321  6692  6782 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1297aee4 not in the list
08-26 10:53:01.321  6692  6782 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:53:01.321  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:53:01.322  6692  6782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 10:53:01.323  6692  6782 D BluetoothLeScanner: could not find callback wrapper
08-26 10:53:01.323  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 10:53:01.323  6692  6782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 10:53:01.323  6692  6782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:53:01.323  6692  6782 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16063f13 removed from the list
08-26 10:53:01.323  6692  6782 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 10:53:01.323  6692  6782 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:53:01.323  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:53:01.323  6692  6782 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 10:53:01.323  6692  6782 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@278ffa02 removed from the list
08-26 10:53:01.324  6692  6782 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 10:53:01.324  6692  6782 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1c07b44e added. We now have 2 listener(s)
08-26 10:53:01.324  1036  1053 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 10:53:01.328  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-26 10:53:01.328  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 10:53:01.328  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 10:53:01.329  6692  6782 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 10:53:01.329  6692  6782 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8bb96f added. We now have 9 listener(s)
08-26 10:53:01.329  6692  6782 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 10:53:01.329  6692  6782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscover,yMode: Discovery mode BLE is supported
08-26 10:53:01.332  6692  6782 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 10:53:01.335  6692  6782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 10:53:01.335  6692  6782 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 10:53:01.335  6692  6782 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 10:53:01.335  6692  6782 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 10:53:01.335  6692  6782 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 10:53:01.335  6692  6782 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 10:53:01.335  6692  6782 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 10:53:01.335  6692  6782 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 10:53:01.337  6692  6782 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 10:53:01.337  6692  6782 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 10:53:01.337  6692  6782 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 10:53:01.338  6692  6782 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2af5eb05 added. We now have 3 listener(s)
08-26 10:53:01.338  1036  1053 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 10:53:01.340  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 10:53:01.341  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-26 10:53:01.341  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 10:53:01.341  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 10:53:01.341  6692  6782 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 10:53:01.341  6692  6782 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32ec75a added. We now have 10 listener(s)
08-26 10:53:01.341  6692  6782 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 10:53:01.342  6692  6782 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 10:53:01.342  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 10:53:01.343  6692  6782 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 10:53:01.343  6692  6782 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 10:53:01.343  6692  6782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 10:53:01.343  6692  6782 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 10:53:01.343  6692  6782 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-26 10:53:01.346  6692  6782 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-26 10:53:01.346  1036  2014 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 10:53:01.355  6692  6782 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-26 10:53:01.356  6692  6782 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-26 10:53:01.357  6692  6782 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-26 10:53:01.358  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 10:53:01.359  6692  6782 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-26 10:53:01.359  6692  6782 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 10:53:01.359  6692  6782 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 10:53:01.359  6692  6782 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 10:53:01.359  6692  6782 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 10:53:01.359  6692  6782 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:53:01.359  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 10:53:01.359  6692  6782 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 10:53:01.359  6692  6782 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1c07b44e removed from the list
08-26 10:53:01.359  6692  6782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:53:01.359  6692  6782 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8bb96f removed from the list
08-26 10:53:01.359  6692  6782 D io.jxcore.node.ConnectivityMonitor: stop
08-26 10:53:01.360  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:53:01.360  6692  6782 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:53:01.360  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:53:01.361  6692  6782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 10:53:01.361  6692  6782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 10:53:01.361  6692  6782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:53:01.361  6692  6782 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8bb96f not in the list
08-26 10:53:01.361  6692  6782 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:53:01.361  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:53:01.362  6692  6782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-26 10:53:01.363  6692  6782 D BluetoothLeScanner: could not find callback wrapper
08-26 10:53:01.363  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 10:53:01.363  6692  6782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 10:53:01.363  6692  6782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:53:01.363  6692  6782 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32ec75a removed from the list
08-26 10:53:01.363  6692  6782 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 10:53:01.363  6692  6782 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:53:01.363  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:53:01.363  6692  6782 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 10:53:01.363  6692  6782 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2af5eb05 removed from the list
08-26 10:53:01.363  6692  6782 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 10:53:01.363  6692  6782 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@186f3281 added. We now have 2 listener(s)
08-26 10:53:01.364  1036  2033 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 10:53:01.367  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-26 10:53:01.367  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 10:53:01.367  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 10:53:01.367  6692  6782 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 10:53:01.367  6692  6782 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1981ff26 added. We now have 9 listener(s)
08-26 10:53:01.367  6692  6782 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 10:53:01.369  6692  6782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-26 10:53:01.371  6692  6782 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 10:53:01.373  6692  6782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 10:53:01.373  6692  6782 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 10:53:01.373  6692  6782 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 10:53:01.373  6692  6782 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 10:53:01.373  6692  6782 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 10:53:01.373  6692  6782 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 10:53:01.373  6692  6782 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 10:53:01.373  6692  6782 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 10:53:01.375  6692  6782 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 10:53:01.375  6692  6782 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 10:53:01.375  6692  6782 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 10:53:01.375  6692  6782 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3fb69914 added. We now have 3 listener(s)
08-26 10:53:01.375  1036  2014 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 10:53:01.378  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 10:53:01.379  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-26 10:53:01.379  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 10:53:01.379  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 10:53:01.379  6692  6782 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 10:53:01.379  6692  6782 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3cdb75bd added. We now have 10 listener(s)
08-26 10:53:01.379  6692  6782 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 10:53:01.379  6692  6782 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 10:53:01.379  6692  6782 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 10:53:01.379  6692  6782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 10:53:01.379  6692  6782 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 10:53:01.379  6692  6782 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-26 10:53:01.381  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 10:53:01.381  6692  6782 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-26 10:53:01.382  1036  1736 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 10:53:01.382  8131  8131 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-26 10:53:01.382  8131  8131 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
08-26 10:53:01.385  6692  6782 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-26 10:53:01.386  1036  8108 D DhcpStateMachine: DHCPV4 succeeded on wlan0
08-26 10:53:01.388  6692  6782 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-26 10:53:01.388  1036  8108 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-26 10:53:01.388  1036  8108 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-26 10:53:01.388  1036  8108 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
08-26 10:53:01.388  1036  8108 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-26 10:53:01.388  1036  8108 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-26 10:53:01.388  1036  8108 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-26 10:53:01.388  1036  8108 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-26 10:53:01.389  1036  8108 D DhcpStateMachine: RunningState
08-26 10:53:01.389  8131  8131 V [BNRBootReceiver]: Boot Receiver Return
08-26 10:53:01.389  8131  8131 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-26 10:53:01.390  6692  6782 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-26 10:53:01.392  8073  8073 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 10:53:01.392  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 10:53:01.393  8073  8120 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-26 10:53:01.393  6692  6782 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-26 10:53:01.395  6692  6782 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 10:53:01.395  6692  6782 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 10:53:01.395  6692  6782 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 10:53:01.395  6692  6782 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 10:53:01.395  6692  6782 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:53:01.395  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 10:53:01.395  6692  6782 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 10:53:01.395  6692  6782 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@186f3281 removed from the list
08-26 10:53:01.395  6692  6782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:53:01.395  6692  6782 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1981ff26 removed from the list
08-26 10:53:01.395  6692  6782 D io.jxcore.node.ConnectivityMonitor: stop
08-26 10:53:01.395  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:53:01.397  6692  6782 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:53:01.397  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:53:01.398  6692  6782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 10:53:01.398  6692  6782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 10:53:01.398  6692  6782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:53:01.398  6692  6782 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1981ff26 not in the list
08-26 10:53:01.398  6692  6782 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:53:01.398  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 10:53:01.399  6692  6782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 10:53:01.400  6692  6782 D BluetoothLeScanner: could not find callback wrapper
08-26 10:53:01.400  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 10:53:01.400  6692  6782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 10:53:01.400  6692  6782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:53:01.400  6692  6782 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3cdb75bd removed from the list
08-26 10:53:01.400  6692  6782 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 10:53:01.400  6692  6782 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:53:01.400  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:53:01.400  6692  6782 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 10:53:01.400  6692  6782 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3fb69914 removed from the list
08-26 10:53:01.402  6692  6782 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 10:53:01.402  6692  6782 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15ee3280 added. We now have 2 listener(s)
08-26 10:53:01.404  6844  6844 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-26 10:53:01.406  1036  2014 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 10:53:01.408  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-26 10:53:01.408  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 10:53:01.408  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 10:53:01.408  6692  6782 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 10:53:01.408  6692  6782 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38ceb0b9 added. We now have 9 listener(s)
08-26 10:53:01.408  6692  6782 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 10:53:01.408  6692  6782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-26 10:53:01.410  6692  6782 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 10:53:01.412  6844  6844 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 10:53:01.414  6692  6782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 10:53:01.414  6692  6782 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 10:53:01.414  6692  6782 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 10:53:01.414  6692  6782 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 10:53:01.414  6692  6782 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 10:53:01.414  6692  6782 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 10:53:01.414  6692  6782 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 10:53:01.414  6692  6782 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 10:53:01.416  6692  6782 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 10:53:01.416  6692  6782 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 10:53:01.416  6692  6782 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 10:53:01.417  6692  6782 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e03dc5f added. We now have 3 listener(s)
08-26 10:53:01.417  1036  1978 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 10:53:01.417  6918  6918 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 10:53:01.418  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 10:53:01.418  6918  6918 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 10:53:01.419  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-26 10:53:01.419  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 10:53:01.419  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 10:53:01.419  6692  6782 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 10:53:01.419  6692  6782 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2543f6ac added. We now have 10 listener(s)
08-26 10:53:01.419  6692  6782 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 10:53:01.419  6692  6692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 10:53:01.419  6692  6782 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 10:53:01.419  6692  6782 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 10:53:01.419  6692  6782 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 10:53:01.419  6692  6782 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 10:53:01.419  6692  6782 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:53:01.419  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 10:53:01.419  6692  6782 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 10:53:01.419  6918  6918 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-26 10:53:01.419  6692  6782 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15ee3280 removed from the list
08-26 10:53:01.419  6692  6782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:53:01.419  6692  6782 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38ceb0b9 removed from the list
08-26 10:53:01.419  6692  6782 D io.jxcore.node.ConnectivityMonitor: stop
08-26 10:53:01.419  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:53:01.422  6844  6844 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
08-26 10:53:01.422  6692  6782 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:53:01.422  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:53:01.423  6692  6782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 10:53:01.423  6692  6782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 10:53:01.423  6692  6782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:53:01.423  6692  6782 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38ceb0b9 not in the list
08-26 10:53:01.423  6692  6782 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:53:01.423  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:53:01.424  6692  6782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 10:53:01.424  6692  6782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 10:53:01.424  6692  6782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:53:01.424  6692  6782 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2543f6ac removed from the list
08-26 10:53:01.424  6692  6782 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 10:53:01.424  6692  6782 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:53:01.424  6692  6782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:53:01.424  6692  6782 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 10:53:01.424  6692  6782 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e03dc5f removed from the list
08-26 10:53:01.425  6692  6782 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-26 10:53:01.425  6692  6782 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-26 10:53:01.425  6692  6782 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-26 10:53:01.425  6692  6782 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 10:53:01.425  6692  6782 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-26 10:53:01.425  6692  6782 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-26 10:53:01.427  6844  6844 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-26 10:53:01.429  8073  8073 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 10:53:01.429  8073  8120 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-26 10:53:01.429  8073  8119 D LgDataFeature: LgDataFeature() Constructor: none
08-26 10:53:01.429  8073  8119 D LgDataFeature: LgDataFeature() Constructor Done, null
08-26 10:53:01.433  6844  6844 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-26 10:53:01.434  6692  8178 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 865, name: My test thread name)
08-26 10:53:01.434  6692  8178 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 865, thread name: My test thread name)
08-26 10:53:01.434  6692  8178 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 865, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-26 10:53:01.436  6692  8179 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 867, name: My test thread name)
08-26 10:53:01.436  6692  8179 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 867, thread name: My test thread name)
08-26 10:53:01.436  6692  8179 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 867, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-26 10:53:01.438  6692  6782 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-26 10:53:01.438  6692  6782 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-26 10:53:01.438  6692  6782 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-26 10:53:01.438  6692  6782 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-26 10:53:01.438  6692  6782 D com.test.thalitest.ThaliTestRunner: Total duration: 23298 ms
08-26 10:53:01.438  6844  6844 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 10:53:01.439  6692  6782 I jxcore-log: *Native tests were executed*
08-26 10:53:01.439  6692  6782 I jxcore-log: 
08-26 10:53:01.439  6692  6782 I jxcore-log: Total number of executed tests:  80
08-26 10:53:01.439  6692  6782 I jxcore-log: 
08-26 10:53:01.439  6692  6782 I jxcore-log: Number of passed tests:  80
08-26 10:53:01.439  6692  6782 I jxcore-log: 
08-26 10:53:01.439  6692  6782 I jxcore-log: Number of failed tests:  0
08-26 10:53:01.439  6692  6782 I jxcore-log: 
,08-26 10:53:01.439  6692  6782 I jxcore-log: Number of ignored tests:  0
08-26 10:53:01.439  6692  6782 I jxcore-log: 
08-26 10:53:01.440  6692  6782 I jxcore-log: Total duration:  23298
08-26 10:53:01.440  6692  6782 I jxcore-log: 
08-26 10:53:01.440  6692  6782 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-26 10:53:01.440  6692  6782 I jxcore-log: 
08-26 10:53:01.442  6692  6782 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 10:53:01.442  6692  6782 I jxcore-log: 
08-26 10:53:01.444  6918  6918 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 10:53:01.444  6692  6782 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 10:53:01.444  6692  6782 I jxcore-log: 
08-26 10:53:01.445  6918  6918 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 10:53:01.445  6918  6918 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-26 10:53:01.448  6692  6782 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 10:53:01.448  6692  6782 I jxcore-log: 
08-26 10:53:01.448  6844  6844 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-26 10:53:01.448  6844  6844 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-26 10:53:01.448  6844  6844 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-26 10:53:01.448  6844  6844 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-26 10:53:01.449  6692  6782 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 10:53:01.449  6692  6782 I jxcore-log: 
08-26 10:53:01.449  6844  6844 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-26 10:53:01.449  6692  6782 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 10:53:01.449  6692  6782 I jxcore-log: 
08-26 10:53:01.450  6844  6844 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-26 10:53:01.450  6844  6844 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-26 10:53:01.450  6844  6844 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-26 10:53:01.450  6844  6844 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-26 10:53:01.450  6844  6844 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-26 10:53:01.450  6844  6844 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-26 10:53:01.451  6844  6844 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-26 10:53:01.451  6692  6782 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-26 10:53:01.451  6692  6782 I jxcore-log: 
08-26 10:53:01.453  6692  6782 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-26 10:53:01.453  6692  6782 I jxcore-log: 
08-26 10:53:01.453  8073  8073 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 10:53:01.454  8073  8120 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-26 10:53:01.455  6692  6782 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 10:53:01.455  6692  6782 I jxcore-log: 
08-26 10:53:01.455  6692  6782 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 10:53:01.455  6692  6782 I jxcore-log: 
08-26 10:53:01.456  6692  6782 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-26 10:53:01.456  6692  6782 I jxcore-log: 
08-26 10:53:01.456  6692  6692 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-26 10:53:01.457  6692  6782 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-26 10:53:01.457  6692  6782 I jxcore-log: 
08-26 10:53:01.458  6692  6782 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-26 10:53:01.458  6692  6782 I jxcore-log: 
08-26 10:53:01.458  6692  6782 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 10:53:01.458  6692  6782 I jxcore-log: 
08-26 10:53:01.459  6692  6782 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 10:53:01.459  6692  6782 I jxcore-log: 
08-26 10:53:01.459  6844  6844 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-26 10:53:01.460  6692  6782 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 10:53:01.460  6692  6782 I jxcore-log: 
08-26 10:53:01.460  6692  6782 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 10:53:01.460  6692  6782 I jxcore-log: 
08-26 10:53:01.461  6692  6782 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 10:53:01.461  6692  6782 I jxcore-log: 
08-26 10:53:01.462  6692  6782 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 10:53:01.462  6692  6782 I jxcore-log: 
08-26 10:53:01.462  6692  6782 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 10:53:01.462  6692  6782 I jxcore-log: 
,08-26 10:53:01.463  6692  6782 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 10:53:01.463  6692  6782 I jxcore-log: 
08-26 10:53:01.463  6692  6782 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-26 10:53:01.463  6692  6782 I jxcore-log: 
08-26 10:53:01.464  6692  6782 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-26 10:53:01.464  6692  6782 I jxcore-log: 
08-26 10:53:01.464  6844  6844 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 10:53:01.464  6692  6782 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 10:53:01.464  6692  6782 I jxcore-log: 
08-26 10:53:01.465  6692  6782 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 10:53:01.465  6692  6782 I jxcore-log: 
08-26 10:53:01.465  6692  6782 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 10:53:01.465  6692  6782 I jxcore-log: 
08-26 10:53:01.466  6692  6782 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 10:53:01.466  6692  6782 I jxcore-log: 
08-26 10:53:01.466  6692  6782 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 10:53:01.466  6692  6782 I jxcore-log: 
08-26 10:53:01.469  6918  6918 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 10:53:01.469  6918  6918 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 10:53:01.469  6918  6918 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-26 10:53:01.472  8073  8073 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 10:53:01.472  8073  8120 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-26 10:53:01.478  6844  6844 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-26 10:53:01.483  6844  6844 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 10:53:01.488  6918  6918 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 10:53:01.489  6918  6918 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 10:53:01.489  6918  6918 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-26 10:53:01.491  8073  8073 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 10:53:01.491  8073  8120 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-26 10:53:01.499  6844  6844 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 10:53:01.505  6844  6844 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 10:53:01.510  6918  6918 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 10:53:01.510  6918  6918 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 10:53:01.511  6918  6918 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-26 10:53:01.513  8073  8073 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-26 10:53:01.513  8073  8120 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-26 10:53:01.519  6844  6844 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-26 10:53:01.524  6844  6844 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 10:53:01.528  8073  8119 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
,08-26 10:53:01.530  6918  6918 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 10:53:01.530  6918  6918 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 10:53:01.531  6918  6918 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-26 10:53:01.538  8073  8073 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 10:53:01.539  8073  8120 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-26 10:53:01.546  8073  8119 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
,08-26 10:53:01.551  6844  6844 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 10:53:01.554  8073  8119 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
08-26 10:53:01.555  8073  8119 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-26 10:53:01.555  8073  8119 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-26 10:53:01.555  8073  8119 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
08-26 10:53:01.556  8073  8119 I SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
08-26 10:53:01.557  6844  6844 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 10:53:01.559  8073  8119 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
08-26 10:53:01.560  8073  8119 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
,08-26 10:53:01.566  6918  6918 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 10:53:01.567  6918  6918 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 10:53:01.568  6918  6918 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-26 10:53:01.571  8073  8073 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 10:53:01.571  8073  8120 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-26 10:53:01.580  6844  6844 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-26 10:53:01.585  6844  6844 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-26 10:53:01.591  6918  6918 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 10:53:01.592  6918  6918 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 10:53:01.593  6918  6918 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-26 10:53:01.598  8073  8120 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-26 10:53:01.600  8073  8073 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 10:53:01.603  8044  8044 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,08-26 10:53:01.608  8044  8044 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-26 10:53:01.610  6844  6844 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 10:53:01.616  6844  6844 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 10:53:01.622  6918  6918 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 10:53:01.622  6918  6918 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 10:53:01.623  6918  6918 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-26 10:53:01.624  6918  6918 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-26 10:53:01.624  6918  6918 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-26 10:53:01.630  8073  8073 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 10:53:01.630  8073  8120 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-26 10:53:01.634  8044  8044 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-26 10:53:01.634  8044  8044 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-26 10:53:01.639  6844  6844 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 10:53:01.650  6844  6844 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 10:53:01.656  6918  6918 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 10:53:01.656  6918  6918 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-26 10:53:01.658  6918  6918 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,08-26 10:53:01.659  6918  6918 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-26 10:53:01.659  6918  6918 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-26 10:53:01.664  8073  8073 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 10:53:01.694  8073  8073 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-26 10:53:01.695  8073  8073 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 10:53:01.697  8073  8073 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 10:53:01.699  8073  8073 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 10:53:01.701  8073  8073 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 10:53:01.702  8073  8073 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 10:53:01.704  8073  8073 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 10:53:01.706  8073  8073 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-26 10:53:01.708  8073  8073 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 10:53:01.711  8073  8073 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 10:53:01.712  1036  1942 I ActivityManager: Killing 7273:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
,08-26 10:53:01.782  1036  1053 W libprocessgroup: failed to open /acct/uid_10005/pid_7273/cgroup.procs: No such file or directory
,08-26 10:53:01.792  8182  8182 D AndroidRuntime: 
08-26 10:53:01.792  8182  8182 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-26 10:53:01.797  8182  8182 D AndroidRuntime: CheckJNI is OFF
,08-26 10:53:02.047  8182  8182 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-26 10:53:02.059  1036  1097 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
,08-26 10:53:02.062  1036  1097 I ActivityManager: Killing 6692:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
08-26 10:53:02.099  1036  2033 I WindowState: WIN DEATH: Window{344f9d2 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-26 10:53:02.101  1036  1485 D WifiService: Client connection lost with reason: 4
08-26 10:53:02.105  1036  2033 D InputDispatcher: Window went away: Window{344f9d2 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-26 10:53:02.243  1036  1097 I ActivityManager:   Force finishing activity ActivityRecord{1d05341f u0 com.test.thalitest/.MainActivity t6}
,08-26 10:53:02.285   347   372 E GBMv2   : DFP En is all cleared set to be enabled
,08-26 10:53:02.292  1036  1052 W ActivityManager: Spurious death for ProcessRecord{8ce70bb 6692:com.test.thalitest/u0a118}, curProc for 6692: null
08-26 10:53:02.294  1036  1125 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
08-26 10:53:02.299  1036  1125 I ActivityManager:   Force finishing activity ActivityRecord{1d05341f u0 com.test.thalitest/.MainActivity t6 f}
,08-26 10:53:02.299  1036  1125 W ActivityManager: Duplicate finish request for ActivityRecord{1d05341f u0 com.test.thalitest/.MainActivity t6 f}
,08-26 10:53:02.325  1943  2943 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
,08-26 10:53:02.326  1943  2943 D SplitWindowPolicy: topRunningActivity=ActivityInfo{32284441 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-26 10:53:02.326  2034  2034 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
08-26 10:53:02.328  2034  2034 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
,08-26 10:53:02.332  2034  2034 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
08-26 10:53:02.334  2034  2123 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
08-26 10:53:02.336  1943  1958 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
08-26 10:53:02.337  1943  1958 D SplitWindowPolicy: topRunningActivity=ActivityInfo{2b370de6 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-26 10:53:02.340  2034  2034 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
08-26 10:53:02.341  2034  2034 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
,08-26 10:53:02.341  1906  1906 D ActionManagerService: notifyUserLog: 1000003
08-26 10:53:02.346  3780  4456 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
08-26 10:53:02.346  2034  2034 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
08-26 10:53:02.358  2034  2034 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
,08-26 10:53:02.362  1604  1604 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
08-26 10:53:02.372  1996  1996 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
,08-26 10:53:02.372  3780  3780 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
08-26 10:53:02.373  1036  1440 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-26 10:53:02.374  7641  7641 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
08-26 10:53:02.374  7641  7641 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-26 10:53:02.375  1036  1440 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-26 10:53:02.376  1036  1440 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-26 10:53:02.377  1036  1440 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-26 10:53:02.378  1036  1440 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-26 10:53:02.378  1036  1440 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-26 10:53:02.382  4496  4496 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-26 10:53:02.382  4496  4496 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-26 10:53:02.382  4496  4496 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-26 10:53:02.382  4496  4496 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-26 10:53:02.382  4496  4496 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-26 10:53:02.382  4496  4496 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-26 10:53:02.382  4496  4496 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-26 10:53:02.382  4496  4496 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-26 10:53:02.382  4496  4496 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 10:53:02.382  4496  4496 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 10:53:02.382  4496  4496 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-26 10:53:02.382  4496  4496 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,08-26 10:53:02.390  1036  1495 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=true
08-26 10:53:02.390  1036  1495 D ConnectivityService: identical MTU - not setting
08-26 10:53:02.390  1036  1495 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-26 10:53:02.390  1036  1495 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-26 10:53:02.390  1036  1495 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 10:53:02.390  1036  1495 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 10:53:02.390  1036  1495 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 10:53:02.391  2454  2620 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-26 10:53:02.391  1604  2075 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
08-26 10:53:02.396  1036  1383 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-26 10:53:02.432  4600  4600 I art     : Explicit concurrent mark sweep GC freed 8220(471KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 30MB/46MB, paused 1.560ms total 117.378ms
,08-26 10:53:02.436  1036  1784 V SIM_STK : Menu title from STK is T-Mobile
08-26 10:53:02.448  1036  1095 W InputMethodInfo: Duplicated subtype definition found: , voice
08-26 10:53:02.456  1906  1906 D ActionManagerService: notifyUserLog: 1000004
08-26 10:53:02.455  8073  8073 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
,08-26 10:53:02.459  2034  2034 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
08-26 10:53:02.459  3780  4456 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
08-26 10:53:02.466  1036  1036 D administrator: Handling package changes for user 0
08-26 10:53:02.480  1819  1819 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
,08-26 10:53:02.484  1604  1604 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
08-26 10:53:02.486  3780  4441 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-26 10:53:02.491  1604  1651 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
,08-26 10:53:02.491  1604  1651 D KeyguardModel: createShortcutInfo...
08-26 10:53:02.493  2128  2128 I ConfigService: onCreate
08-26 10:53:02.493  2128  2128 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
08-26 10:53:02.495  1604  1651 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-26 10:53:02.495  1604  1651 D KeyguardModel: createShortcutInfo...
08-26 10:53:02.496  1871  1871 D SplitUIManager: split_name #11 / not available #0
,08-26 10:53:02.496  1871  1871 D SplitUIService: removed split : 
08-26 10:53:02.501  2034  2034 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-26 10:53:02.501  2034  2034 I GBoardWebViewUtils: , create_time: 1430832262123
08-26 10:53:02.501  2034  2034 I GBoardWebViewUtils: , expire_time: 0
08-26 10:53:02.501  2034  2034 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-26 10:53:02.501  2034  2034 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-26 10:53:02.501  2034  2034 I GBoardWebViewUtils: , display: false
08-26 10:53:02.501  2034  2034 I GBoardWebViewUtils: , animation: false }
08-26 10:53:02.501  2034  2034 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-26 10:53:02.501  2034  2034 I GBoardWebViewUtils: , create_time: 1430832262287
08-26 10:53:02.501  2034  2034 I GBoardWebViewUtils: , expire_time: 0
08-26 10:53:02.501  2034  2034 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-26 10:53:02.501  2034  2034 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-26 10:53:02.501  2034  2034 I GBoardWebViewUtils: , display: false
08-26 10:53:02.501  2034  2034 I GBoardWebViewUtils: , animation: false }
08-26 10:53:02.501  2034  2034 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1471602815280
08-26 10:53:02.501  2034  2034 I GBoardWebViewUtils: , create_time: 1471602816196
08-26 10:53:02.501  2034  2034 I GBoardWebViewUtils: , expire_time: 0
08-26 10:53:02.501  2034  2034 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/0/userguide.html?id=guide_1111111111116_1471602815280&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-26 10:53:02.501  2034  2034 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-26 10:53:02.501  2034  2034 I GBoardWebViewUtils: , display: false
08-26 10:53:02.501  2034  2034 I GBoardWebViewUtils: , animation: false }
08-26 10:53:02.506  2128  2128 I ConfigService: onBind returning update interface
,08-26 10:53:02.516  1604  1651 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-26 10:53:02.516  1604  1651 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-26 10:53:02.516  1604  1651 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-26 10:53:02.517  1604  1651 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-26 10:53:02.518  1604  1604 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-26 10:53:02.518  1604  1604 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
08-26 10:53:02.518  1604  1651 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-26 10:53:02.518  1604  1651 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
,08-26 10:53:02.520  2128  2128 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-26 10:53:02.520  1604  1651 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-26 10:53:02.520  2128  2128 I ConfigService: onBind returning config service
08-26 10:53:02.520  1604  1651 D KeyguardModel: createShortcutInfo...
08-26 10:53:02.522  1819  1819 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
08-26 10:53:02.524  1604  1651 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-26 10:53:02.524  1604  1651 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-26 10:53:02.530  2034  8219 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
08-26 10:53:02.530  1819  1819 I ConfigFetchService: service connected
08-26 10:53:02.530  1819  1819 I ConfigClient: service connected
,08-26 10:53:02.533  1036  1584 V SIM_STK : Menu title from STK is T-Mobile
08-26 10:53:02.533  1036  1584 V SIM_STK : Menu title from STK is T-Mobile
08-26 10:53:02.539  1604  1651 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-26 10:53:02.539  1604  1651 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-26 10:53:02.548  2128  2128 I ConfigService: onDestroy
,08-26 10:53:02.550  1604  1651 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-26 10:53:02.550  1604  1651 D KeyguardModel: createShortcutInfo...
08-26 10:53:02.552  2034  2034 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
08-26 10:53:02.555  1604  1651 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-26 10:53:02.555  1604  1651 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-26 10:53:02.555  1604  1651 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-26 10:53:02.555  1604  1651 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-26 10:53:02.556  1871  1871 D SplitUIManager: split_name #11 / not available #0
08-26 10:53:02.556  1871  1871 I SplitUIService: split app #11
08-26 10:53:02.556  1604  1651 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-26 10:53:02.556  1604  1651 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-26 10:53:02.563  1604  1651 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-26 10:53:02.563  1604  1651 D KeyguardModel: createShortcutInfo...
08-26 10:53:02.564  1819  8221 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,08-26 10:53:02.588  1604  1604 D KeyguardModel: handleShortcutListChanged...
08-26 10:53:02.588  1604  1604 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
,08-26 10:53:02.594  7719  7719 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
,08-26 10:53:02.612  1036  1736 V SIM_STK : Menu title from STK is T-Mobile
08-26 10:53:02.620  1036  1052 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-26 10:53:02.620  1604  1651 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-26 10:53:02.620  1604  1651 D KeyguardModel: createShortcutInfo...
08-26 10:53:02.621  7641  7641 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-26 10:53:02.621  7641  7641 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-26 10:53:02.621  7641  7641 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-26 10:53:02.621  7641  7641 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-26 10:53:02.621  7641  7641 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-26 10:53:02.621  7641  7641 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
,08-26 10:53:02.621  7641  7641 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-26 10:53:02.621  7641  7641 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-26 10:53:02.621  7641  7641 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-26 10:53:02.621  7641  7641 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-26 10:53:02.621  7641  7641 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
,08-26 10:53:02.623  1604  1651 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-26 10:53:02.623  1604  1651 D KeyguardModel: createShortcutInfo...
08-26 10:53:02.626  1604  1651 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-26 10:53:02.626  1604  1651 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-26 10:53:02.639  5939  8228 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
08-26 10:53:02.639  2034  2034 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,08-26 10:53:02.645  1604  1651 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-26 10:53:02.645  1604  1651 D KeyguardModel: createShortcutInfo...
08-26 10:53:02.648  1604  1651 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-26 10:53:02.648  1604  1651 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-26 10:53:02.649  1604  1651 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-26 10:53:02.649  1604  1651 D KeyguardModel: createShortcutInfo...
08-26 10:53:02.650  2034  2034 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
08-26 10:53:02.651  1604  1651 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-26 10:53:02.651  1604  1651 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-26 10:53:02.652  1604  1651 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-26 10:53:02.652  1604  1651 D KeyguardModel: createShortcutInfo...
,08-26 10:53:02.660  1604  1604 D KeyguardModel: handleShortcutListChanged...
08-26 10:53:02.660  1604  1604 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-26 10:53:02.679  1819  8229 I PeopleContactsSync: CP2 sync disabled
,08-26 10:53:02.692  2360  8232 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-26 10:53:02.704  1036  1036 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-26 10:53:02.704  1036  1036 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-26 10:53:02.704  1036  1036 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-26 10:53:02.709  1036  1923 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8233 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-26 10:53:02.712  1819  4666 I Icing   : doRemovePackageData com.test.thalitest
08-26 10:53:02.713  1036  1578 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
08-26 10:53:02.720  1819  8227 W GmsApplication: Using Auth Proxy for data requests.
08-26 10:53:02.728  1819  8227 W GmsApplication: Using Auth Proxy for data requests.
,08-26 10:53:02.762  8233  8233 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-26 10:53:02.763  8233  8233 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-26 10:53:02.768  2034  2034 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
08-26 10:53:02.770  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-26 10:53:02.771  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
08-26 10:53:02.772  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-26 10:53:02.773  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-26 10:53:02.774  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
08-26 10:53:02.775  1036  1125 I art     : Explicit concurrent mark sweep GC freed 83893(4MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 43MB/65MB, paused 2.130ms total 437.959ms
08-26 10:53:02.780  2128  2148 I art     : Explicit concurrent mark sweep GC freed 7235(432KB) AllocSpace objects, 0(0B) LOS objects, 52% free, 29MB/61MB, paused 2.755ms total 35.313ms
,08-26 10:53:02.783  8233  8233 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-26 10:53:02.783  8233  8233 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-26 10:53:02.790  2034  2034 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
08-26 10:53:02.790  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-26 10:53:02.790  1036  1113 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1e5971b1 u0 com.lge.launcher2/.Launcher t5} time:142042
,08-26 10:53:02.797  2034  2201 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-26 10:53:02.797  2034  2201 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
08-26 10:53:02.804  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
08-26 10:53:02.805  2034  2034 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-26 10:53:02.805  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-26 10:53:02.812  2034  2034 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
,08-26 10:53:02.814  2630  2630 D [Concierge]Service: onStartCommand(). Type : 8
08-26 10:53:02.814  2630  2630 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
08-26 10:53:02.816  2034  2034 D [Concierge]WidgetView: change position of spinner
08-26 10:53:02.817  2630  2630 D [Concierge]Service: Update widget ID : 11
08-26 10:53:02.817  2630  2630 D [Concierge]Service: onStartCommand(). Type : 0
08-26 10:53:02.818  2034  2034 I [Concierge]WidgetView: initWebView(). Time : 1472201582818
08-26 10:53:02.834  2034  2034 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 618888688
,08-26 10:53:02.834  2034  2034 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
08-26 10:53:02.834  2034  2034 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-26 10:53:02.837  2034  2034 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@1a9f98e6
08-26 10:53:02.837  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
08-26 10:53:02.838  2034  2034 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-26 10:53:02.838  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-26 10:53:02.843  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
08-26 10:53:02.843  2034  2034 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-26 10:53:02.843  2034  2034 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-26 10:53:02.844  2034  2034 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1472201469042, New one : 1472201582818
08-26 10:53:02.844  2034  2034 D [Concierge]WidgetView: Unregister all receivers
08-26 10:53:02.844  2034  2034 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-26 10:53:02.845  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-26 10:53:02.846  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
08-26 10:53:02.847  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
,08-26 10:53:02.850  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
08-26 10:53:02.851  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
08-26 10:53:02.853  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
08-26 10:53:02.855  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-26 10:53:02.855  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-26 10:53:02.857  8182  8182 D AndroidRuntime: Shutting down VM
08-26 10:53:02.895  1036  1125 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8253 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-26 10:53:02.902  8233  8233 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
08-26 10:53:02.902  1036  1095 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-26 10:53:02.902  2034  2034 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-26 10:53:02.908  1036  1095 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,08-26 10:53:02.911  2034  2034 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
08-26 10:53:02.911  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
08-26 10:53:02.912  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-26 10:53:02.929  8233  8233 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
08-26 10:53:02.929  2034  2034 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-26 10:53:02.933  2034  2034 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@36080be5 time:142185
,08-26 10:53:02.946  1036  1784 I ActivityManager: Killing 7669:com.google.android.talk/u0a72 (adj 15): empty #17
08-26 10:53:02.951  8233  8233 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-26 10:53:03.019  1036  2033 W libprocessgroup: failed to open /acct/uid_10072/pid_7669/cgroup.procs: No such file or directory
,08-26 10:53:03.065  8233  8233 D LgDataFeature: LgDataFeature() Constructor: none
08-26 10:53:03.065  8233  8233 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-26 10:53:03.092  2034  2034 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,08-26 10:53:03.141  2034  2868 I GBoardtInterface: onReloaded()
,08-26 10:53:03.143  2034  2034 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
08-26 10:53:03.144  3780  4441 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-26 10:53:03.146  3780  3795 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-26 10:53:03.151  8233  8233 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
08-26 10:53:03.155  1906  1906 D ActionManagerService: notifyUserLog: 1000001
,08-26 10:53:03.158  3780  4456 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-26 10:53:03.158  3780  4456 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-26 10:53:03.161  1906  1906 D ActionManagerService: notifyUserLog: 1000001
08-26 10:53:03.162  3780  4456 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-26 10:53:03.162  3780  4456 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-26 10:53:03.162  3780  4456 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
08-26 10:53:03.162  3780  4456 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
08-26 10:53:03.163  3780  4441 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-26 10:53:03.166  2034  2034 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
08-26 10:53:03.166  2034  2034 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
08-26 10:53:03.168  2034  2034 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
,08-26 10:53:03.168  2034  2034 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
,08-26 10:53:03.170  1036  2005 I ActivityManager: Killing 7783:com.android.vending/u0a44 (adj 15): empty #17
08-26 10:53:03.171  2034  2034 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/0/userguide2.html?id=guide_1111111111116_1471602815280&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
08-26 10:53:03.171  2034  2034 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/0/userguide2.html?id=guide_1111111111116_1471602815280&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-26 10:53:03.209  1996  1996 D LIA_Service_NativeEventReceiver: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-26 10:53:03.209  1996  1996 I LIA_Service_PlatformUtil: startLIAService() : Trying to start LIA service ...
,08-26 10:53:03.210  1996  1996 D LIA_Service_LIAService: onStartCommand() : LIAService started! - id :4, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
08-26 10:53:03.211  1036  1924 W libprocessgroup: failed to open /acct/uid_10044/pid_7783/cgroup.procs: No such file or directory
08-26 10:53:03.219  8073  8073 E SQLiteDatabase: Failed to open database '/data/data/com.wsandroid.suite.lge/databases/CLOUDREPUTATIONDB'.
08-26 10:53:03.219  8073  8073 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 10:53:03.219  8073  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 10:53:03.219  8073  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
08-26 10:53:03.219  8073  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
08-26 10:53:03.219  8073  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-26 10:53:03.219  8073  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-26 10:53:03.219  8073  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-26 10:53:03.219  8073  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
08-26 10:53:03.219  8073  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
08-26 10:53:03.219  8073  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
08-26 10:53:03.219  8073  8073 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
08-26 10:53:03.219  8073  8073 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-26 10:53:03.219  8073  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 10:53:03.219  8073  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-26 10:53:03.219  8073  8073 E SQLiteDatabase: 	at com.mcafee.cloudscan.mc20.i.a(Unknown Source)
08-26 10:53:03.219  8073  8073 E SQLiteDatabase: 	at com.mcafee.cloudscan.mc20.ad.a(Unknown Source)
08-26 10:53:03.219  8073  8073 E SQLiteDatabase: 	at com.mcafee.cloudscan.mc20.ab.j(Unknown Source)
08-26 10:53:03.219  8073  8073 E SQLiteDatabase: 	at com.mcafee.cloudscan.mc20.k.b(Unknown Source)
08-26 10:53:03.219  8073  8073 E SQLiteDatabase: 	at com.mcafee.cloudscan.mc20.k.a(Unknown Source)
08-26 10:53:03.219  8073  8073 E SQLiteDatabase: 	at com.mcafee.cloudscan.mc20.CloudScanReceiver.onReceive(Unknown Source)
08-26 10:53:03.219  8073  8073 E SQLiteDatabase: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2586)
08-26 10:53:03.219  8073  8073 E SQLiteDatabase: 	at android.app.ActivityThread.access$1700(ActivityThread.java:148)
08-26 10:53:03.219  8073  8073 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1360)
08-26 10:53:03.219  8073  8073 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 10:53:03.219  8073  8073 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
08-26 10:53:03.219  8073  8073 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-26 10:53:03.219  8073  8073 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 10:53:03.219  8073  8073 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 10:53:03.219  8073  8073 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-26 10:53:03.219  8073  8073 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-26 10:53:03.221  8073  ,8073 D PostponalbeReceiver: OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
,08-26 10:53:03.227  7468  7468 D CoreEventReceiver: [onReceive] Action=android.intent.action.PACKAGE_REMOVED
,08-26 10:53:03.230  6844  6844 D PackageIntentReceiver: Not supported Hotkey customization function 
08-26 10:53:03.237  6844  6844 D HideNavigationAppsReceiver: Receive package name : com.test.thalitest, replacing=false, action=android.intent.action.PACKAGE_REMOVED
08-26 10:53:03.237  6844  6844 D HideNavigationAppsReceiver: replacing : false

```
