#### Test 807613740d5db28_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
08-16 14:40:32.704  1983  1983 D LIA_Service_NativeEventReceiver: onReceive action : android.intent.action.PACKAGE_ADDED = package:com.test.thalitest
08-16 14:40:32.704  1983  1983 I LIA_Service_PlatformUtil: startLIAService() : Trying to start LIA service ...
08-16 14:40:32.714  1983  1983 D LIA_Service_LIAService: onStartCommand() : LIAService started! - id :3, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
08-16 14:40:32.755  6411  6411 D PostponalbeReceiver: OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_ADDED'.
--------- beginning of system
08-16 14:40:32.761  6411  6411 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsm.mss.OasPackageScanReceiver.onReceive:-1 android.app.ActivityThread.handleReceiver:2586 
08-16 14:40:32.796  4570  6550 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
08-16 14:40:32.857  1038  1944 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=6552 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-16 14:40:32.868  1038  1909 V SIM_STK : Menu title from STK is T-Mobile
08-16 14:40:32.971  4570  6550 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 175 ms] updated apps [took 175 ms] 
08-16 14:40:33.121  6552  6552 D DocsApplication: Installing DEX configuration.
08-16 14:40:33.150  6552  6552 D DexInstaller: Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
08-16 14:40:33.156  6552  6552 I PackageInfoHelper: Provided clientMode=RELEASE, packageInfo=PackageInfo{3ccfb600 com.google.android.apps.docs}
08-16 14:40:33.175  6552  6552 D TAG     : onCreate()
08-16 14:40:33.203  6552  6552 D CrossAppStateProvider: Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
08-16 14:40:33.634   341   424 I ThermalEngine: Thermal-Server: Thermal received msg from  override
,08-16 14:40:33.638  3247  6576 I Thermal-Lib: Thermal-Lib-Client: Client request sent
08-16 14:40:33.949  6577  6577 D AndroidRuntime: 
08-16 14:40:33.949  6577  6577 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-16 14:40:33.952  6577  6577 D AndroidRuntime: CheckJNI is OFF
08-16 14:40:33.971  1803  4710 I Icing   : Indexing 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4 from com.google.android.googlequicksearchbox
08-16 14:40:34.015  1803  4710 D Icing   : Loaded CLD2 Version V2.0 - 20140131
08-16 14:40:34.057  1803  4710 I Icing   : Indexing done 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4
08-16 14:40:34.063  6577  6577 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-16 14:40:34.066  1038  1946 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-16 14:40:34.083  1927  2661 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-16 14:40:34.086  1038  1946 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-16 14:40:34.087  1038  1946 D ActivityManager: setTaskToReturnTo : TaskRecord{39268b #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-16 14:40:34.087  1038  1946 D ActivityManager: setTaskToReturnTo : TaskRecord{39268b #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-16 14:40:34.088  1038  1946 D WindowStateEx: AppWindowTokenEx init.. 
08-16 14:40:34.089   347   365 E GBMv2   : DFP En is all cleared set to be enabled
08-16 14:40:34.132  1038  1946 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6608 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-16 14:40:34.134  6577  6577 D AndroidRuntime: Shutting down VM
08-16 14:40:34.177  1927  2661 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-16 14:40:34.178  1927  2661 D SplitWindowPolicy: topRunningActivity=ActivityInfo{25c3237c co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-16 14:40:34.181  1927  2661 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-16 14:40:34.182  1927  2661 D SplitWindowPolicy: topRunningActivity=ActivityInfo{36ce1405 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-16 14:40:34.226  6608  6608 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-16 14:40:34.296  6608  6608 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
08-16 14:40:34.306  6608  6608 I LibraryLoader: Loading: webviewchromium
08-16 14:40:34.310  6608  6608 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 1485-1489)
08-16 14:40:34.310  6608  6608 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-16 14:40:34.327  6608  6608 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2701228a}
08-16 14:40:34.328  6608  6608 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-16 14:40:34.329  6608  6608 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-16 14:40:34.338  6608  6608 I BrowserStartupController: Initializing chromium process, renderers=0
08-16 14:40:34.339  6608  6608 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-16 14:40:34.357  6608  6608 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,08-16 14:40:34.360  6608  6608 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
08-16 14:40:34.370  6608  6608 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
,08-16 14:40:34.371   325  2114 V AudioPolicyService: registerClient() client 0xb558a860, uid 10118
08-16 14:40:34.376  1038  1120 D BluetoothManagerService: Message: 20
08-16 14:40:34.376  1038  1120 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1642d6bd:true
08-16 14:40:34.399  6608  6608 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-16 14:40:34.399  6608  6608 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-16 14:40:34.399  6608  6608 I Adreno-EGL: Build Date: 12/12/14 금
08-16 14:40:34.399  6608  6608 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-16 14:40:34.399  6608  6608 I Adreno-EGL: Remote Branch: 
08-16 14:40:34.399  6608  6608 I Adreno-EGL: Local Patches: 
08-16 14:40:34.399  6608  6608 I Adreno-EGL: Reconstruct Branch: 
,08-16 14:40:34.489  6608  6639 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,08-16 14:40:34.498  6608  6608 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
08-16 14:40:34.526  6608  6608 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-16 14:40:34.531  6608  6608 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-16 14:40:34.534  6608  6608 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-16 14:40:34.537  6608  6608 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-16 14:40:34.537  6608  6608 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
,08-16 14:40:34.556  6608  6608 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-16 14:40:34.562  6608  6608 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-16 14:40:34.562  6608  6608 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-16 14:40:34.600  6608  6651 D OpenGLRenderer: Render dirty regions requested: true
,08-16 14:40:34.600  6608  6651 I OpenGLRenderer: Initialized EGL, version 1.4
08-16 14:40:34.606  6608  6651 D OpenGLRenderer: Enabling debug mode 0
08-16 14:40:34.618  6608  6608 D Atlas   : Validating map...
,08-16 14:40:34.623  1038  2019 D SplitWindow: check instance of lgWin Window{13cf344f u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-16 14:40:34.657  6608  6649 D LgDataFeature: LgDataFeature() Constructor: none
,08-16 14:40:34.657  6608  6649 D LgDataFeature: LgDataFeature() Constructor Done, null
08-16 14:40:34.743  1038  1121 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +566ms (total +653ms)
,08-16 14:40:34.744  1038  1121 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1c95f368 u0 com.test.thalitest/.MainActivity t6} time:111923
08-16 14:40:34.748  6608  6608 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2ca292e1 time:111928
08-16 14:40:34.861  6608  6608 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-16 14:40:34.861  6608  6608 I chromium: 
,08-16 14:40:34.906  6608  6608 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
08-16 14:40:34.906  6552  6552 D LgDataFeature: LgDataFeature() Constructor: none
08-16 14:40:34.906  6552  6552 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 14:40:34.990  6608  6649 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-16 14:40:34.990  6608  6649 I chromium: 
,08-16 14:40:35.103  6608  6667 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435155968
,08-16 14:40:35.117  6608  6667 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-16 14:40:35.117  6608  6667 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-16 14:40:35.117  6608  6667 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-16 14:40:35.117  6608  6667 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-16 14:40:35.117  6608  6667 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-16 14:40:35.117  6608  6667 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b2811d5 added. We now have 1 listener(s)
08-16 14:40:35.119  6052  6052 I LockScreenSettings: New app installed broadcast received ..
08-16 14:40:35.122  6052  6052 I LockScreenSettings: Number of installed packages  1
,08-16 14:40:35.124  1038  1946 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 14:40:35.126  6608  6667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-16 14:40:35.128  6608  6667 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-16 14:40:35.129  6608  6667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 14:40:35.129  6608  6667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 14:40:35.135  6552  6552 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,08-16 14:40:35.139  6608  6667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-16 14:40:35.139  6608  6667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-16 14:40:35.139  6608  6667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-16 14:40:35.139  6608  6667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-16 14:40:35.139  6608  6667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-16 14:40:35.139  6608  6667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-16 14:40:35.139  6608  6667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-16 14:40:35.139  6608  6667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-16 14:40:35.139  6608  6667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-16 14:40:35.139  6608  6667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-16 14:40:35.139  6608  6667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-16 14:40:35.139  6608  6667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-16 14:40:35.139  6608  6667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-16 14:40:35.139  6608  6667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-16 14:40:35.139  6608  6667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c722f78 added. We now have 1 listener(s)
08-16 14:40:35.139  6608  6667 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 14:40:35.144  1038  1431 D WifiService: New client listening to asynchronous messages
08-16 14:40:35.147  6608  6667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 14:40:35.147  6608  6667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-16 14:40:35.149  6608  6667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-16 14:40:35.149  6608  6667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-16 14:40:35.149  6608  6667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-16 14:40:35.156  6608  6667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 14:40:35.157  1038  1890 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 14:40:35.158  6608  6667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-16 14:40:35.166  6608  6667 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
,08-16 14:40:35.167  6608  6667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 14:40:35.167  6608  6667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:40:35.167  6608  6667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 14:40:35.167  6608  6667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 14:40:35.167  6608  6667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 14:40:35.167  6608  6667 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 14:40:35.167  6608  6667 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 14:40:35.167  6608  6667 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 14:40:35.167  6608  6667 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-16 14:40:35.167  6608  6667 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 14:40:35.169  6608  6667 I io.jxcore.node.LifeCycleMonitor: start: OK
08-16 14:40:35.170  6608  6608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:40:35.173  6608  6608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:40:35.186  1038  1945 V SIM_STK : Menu title from STK is T-Mobile
,08-16 14:40:35.214  6608  6608 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-16 14:40:35.245  1038  1711 I ActivityManager: Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=6685 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-16 14:40:35.318  6685  6685 D EulaProviderUpdateObserver: action : android.intent.action.PACKAGE_ADDED
08-16 14:40:35.318  6685  6685 D EulaProviderUpdateObserver: uri : package:com.test.thalitest
,08-16 14:40:35.391  1038  1909 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.BNRAppInstallReceiver: pid=6703 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-16 14:40:35.391  1038  1909 I ActivityManager: Killing 5781:com.google.android.talk/u0a72 (adj 15): empty #17
08-16 14:40:35.481  1038  2037 W libprocessgroup: failed to open /acct/uid_10072/pid_5781/cgroup.procs: No such file or directory
,08-16 14:40:35.589  6703  6703 D [BNRAppListMgrReceiver]: android.intent.action.PACKAGE_ADDED : com.test.thalitest
,08-16 14:40:35.617  6703  6703 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-16 14:40:35.617  6411  6411 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.intent.action.PACKAGE_ADDED'.
,08-16 14:40:35.656  1038  1945 I ActivityManager: Killing 5580:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,08-16 14:40:35.657   347   367 E GBMv2   : DFP En is all cleared set to be enabled
08-16 14:40:35.657   347   367 E GBMv2   : Set value is all cleared set the max
08-16 14:40:35.657   347   367 I GBMv2   : DFP Enabled. Ignore VFP set
08-16 14:40:35.671  5555  5555 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
08-16 14:40:35.671  5555  5555 W System.err: android.os.DeadObjectException
08-16 14:40:35.671  5555  5555 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-16 14:40:35.671  5555  5555 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-16 14:40:35.672  5555  5555 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-16 14:40:35.672  5555  5555 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-16 14:40:35.672  5555  5555 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-16 14:40:35.672  5555  5555 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-16 14:40:35.672  5555  5555 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-16 14:40:35.672  5555  5555 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-16 14:40:35.672  5555  5555 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-16 14:40:35.672  5555  5555 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-16 14:40:35.672  5555  5555 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 14:40:35.672  5555  5555 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 14:40:35.672  5555  5555 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-16 14:40:35.672  5555  5555 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-16 14:40:35.672  5555  5555 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-16 14:40:35.672  5555  5555 W System.err: android.os.DeadObjectException
08-16 14:40:35.673  5555  5555 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-16 14:40:35.673  5555  5555 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-16 14:40:35.673  5555  5555 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-16 14:40:35.673  5555  5555 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-16 14:40:35.673  5555  5555 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
,08-16 14:40:35.677  5555  5555 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-16 14:40:35.677  5555  5555 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-16 14:40:35.677  5555  5555 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-16 14:40:35.677  5555  5555 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-16 14:40:35.677  5555  5555 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-16 14:40:35.677  5555  5555 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 14:40:35.677  5555  5555 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 14:40:35.677  5555  5555 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-16 14:40:35.677  5555  5555 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-16 14:40:35.678  5555  5555 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-16 14:40:35.678  5555  5555 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
08-16 14:40:35.876   279   279 E lowmemorykiller: Error opening /proc/5580/oom_score_adj; errno=2
,08-16 14:40:35.885  1038  1711 W ActivityManager: Exception when unbinding service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service
08-16 14:40:35.885  1038  1711 W ActivityManager: android.os.DeadObjectException
08-16 14:40:35.885  1038  1711 W ActivityManager: 	at android.os.BinderProxy.transactNative(Native Method)
08-16 14:40:35.885  1038  1711 W ActivityManager: 	at android.os.BinderProxy.transact(Binder.java:496)
08-16 14:40:35.885  1038  1711 W ActivityManager: 	at android.app.ApplicationThreadProxy.scheduleUnbindService(ApplicationThreadNative.java:917)
08-16 14:40:35.885  1038  1711 W ActivityManager: 	at com.android.server.am.ActiveServices.removeConnectionLocked(ActiveServices.java:1776)
08-16 14:40:35.885  1038  1711 W ActivityManager: 	at com.android.server.am.ActiveServices.unbindServiceLocked(ActiveServices.java:901)
08-16 14:40:35.885  1038  1711 W ActivityManager: 	at com.android.server.am.ActivityManagerService.unbindService(ActivityManagerService.java:15417)
08-16 14:40:35.885  1038  1711 W ActivityManager: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:963)
08-16 14:40:35.885  1038  1711 W ActivityManager: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2560)
08-16 14:40:35.885  1038  1711 W ActivityManager: 	at com.android.server.am.ActivityManagerServiceEx.onTransact(ActivityManagerServiceEx.java:421)
08-16 14:40:35.885  1038  1711 W ActivityManager: 	at android.os.Binder.execTransact(Binder.java:446)
08-16 14:40:35.889  1038  1944 W libprocessgroup: failed to open /acct/uid_1000/pid_5580/cgroup.procs: No such file or directory
08-16 14:40:35.891  5555  5555 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-16 14:40:35.892  5555  5555 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-16 14:40:35.931  1038  1562 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=6724 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-16 14:40:35.931  5555  5555 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-16 14:40:36.025  6724  6724 D UEI.SmartControl: Quickset Services start...
,08-16 14:40:36.028  6724  6724 I UEI.SmartControl: Manufacture = LGE
08-16 14:40:36.028  6724  6724 D UEI.SmartControl: Id = LGNevo
08-16 14:40:36.030  6724  6724 D UEI.SmartControl: File observer start...
08-16 14:40:36.030  6724  6724 E UEI.SmartControl: IR Port is disabled: false
08-16 14:40:36.031  6724  6724 D UEI.SmartControl: Starting file observer...
08-16 14:40:36.031  6724  6724 D UEI.SmartControl: Extracting JNI libs...
08-16 14:40:36.031  6724  6724 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
08-16 14:40:36.119  6724  6724 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,08-16 14:40:36.119  6724  6724 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-16 14:40:36.119  6724  6724 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
08-16 14:40:36.152  6724  6724 I UEI.SmartControl: --- Selecting new region: 6
,08-16 14:40:36.154  6724  6724 I UEI.SmartControl: Model = LG-D855
08-16 14:40:36.156  6724  6724 D UEI.SmartControl: QS Service created
08-16 14:40:36.173  6724  6724 I UEI.SmartControl: Service initServices...
,08-16 14:40:36.177  6724  6724 D UEI.SmartControl: QS start get config
08-16 14:40:36.249  6608  6679 W jxcore-log: Initializing JXcore engine
08-16 14:40:36.249  6608  6679 W jxcore-log: JXcore engine is ready
,08-16 14:40:36.255  6724  6724 D UEI.SmartControl: Loading JNI Libs...
08-16 14:40:36.289  6679  6679 W Thread-757: type=1400 audit(0.0:162): avc: denied { ioctl } for path="socket:[6093]" dev="sockfs" ino=6093 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-16 14:40:36.289  6679  6679 W Thread-757: type=1400 audit(0.0:163): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-16 14:40:36.289  6679  6679 W Thread-757: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[7851]" dev="sockfs" ino=7851 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-16 14:40:36.289  6679  6679 W Thread-757: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-16 14:40:36.289  6679  6679 W Thread-757: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[31937]" dev="sockfs" ino=31937 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,08-16 14:40:36.310  6608  6679 W jxcore-log: Starting JXcore engine
08-16 14:40:36.396  6608  6679 W jxcore-log: Platform android
08-16 14:40:36.396  6608  6679 W jxcore-log: 
08-16 14:40:36.396  6608  6679 W jxcore-log: Process ARCH arm
08-16 14:40:36.396  6608  6679 W jxcore-log: 
,08-16 14:40:36.603  6724  6724 I UEI.SmartControl: Supports setup maps: true
,08-16 14:40:36.609  6724  6724 D UEI.SmartControl: QS start statue = true Error code = 0
08-16 14:40:36.609  6724  6724 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-16 14:40:36.610  6724  6724 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-16 14:40:36.610  6724  6724 I UEI.SmartControl: ### init IR Blaster...
08-16 14:40:36.615  6724  6724 D serial_port: Configuring serial port
,08-16 14:40:36.620  6724  6724 E UEI.SmartControl: UEIBLaster setting for 616
08-16 14:40:36.620  6724  6724 I UEI.SmartControl: Setting serial record hearder size = 2
08-16 14:40:36.621  6724  6724 I UEI.SmartControl: configuring settings for MAXQ616
08-16 14:40:36.621  6724  6724 I UEI.SmartControl: Get version...
08-16 14:40:36.638  6724  6742 D UEI.SmartControl: serial port data available: 21
,08-16 14:40:36.642  6608  6679 I jxcore-log: JXcore Cordova bridge is ready!
08-16 14:40:36.642  6608  6679 I jxcore-log: 
08-16 14:40:36.643  6608  6679 W jxcore-log: JXcore engine is started
08-16 14:40:36.652  6608  6667 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-16 14:40:36.657  6608  6608 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
08-16 14:40:36.667  6724  6724 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-16 14:40:36.667  6724  6724 I UEI.SmartControl: IR Blaster version: 256702256704300002
,08-16 14:40:36.667  6724  6724 I UEI.SmartControl: QS saving settings...
08-16 14:40:36.669  6724  6724 D UEI.SmartControl: IR Blaster version: 25672567
08-16 14:40:36.686  6724  6742 D UEI.SmartControl: serial port data available: 4
,08-16 14:40:36.720  6724  6745 I UEI.SmartControl: Device manager: loading config....
,08-16 14:40:36.722  6724  6724 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-16 14:40:36.723  6724  6745 D UEI.SmartControl: ----------- loading internal config...
08-16 14:40:36.731  6724  6724 E UEI.SmartControl: Services init done
08-16 14:40:36.731  6724  6724 D UEI.SmartControl: QS Service init finished
08-16 14:40:36.733  6724  6724 D UEI.SmartControl: QS Service version name: 2.1.91
08-16 14:40:36.733  6724  6724 D UEI.SmartControl: QS Service version code: 201091
,08-16 14:40:36.734  6724  6724 D UEI.SmartControl: Service requested: Control
08-16 14:40:36.740  6724  6745 E UEI.SmartControl: Loading SETTINGS...
08-16 14:40:36.744  6724  6724 D UEI.SmartControl: Request IControl service: devices are loaded...
08-16 14:40:36.747  5555  5555 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
,08-16 14:40:36.748  6724  6740 I UEI.SmartControl: ------ IControl API: 11
08-16 14:40:36.749  6724  6740 I UEI.SmartControl: Registering callback...
08-16 14:40:36.749  1038  1890 I ActivityManager: Killing 5555:com.lge.qremote/u0a112 (adj 15): empty #17
08-16 14:40:36.755  6724  6745 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-16 14:40:36.779  6724  6744 I UEI.SmartControl: Notify AllClients services are ready: 0
08-16 14:40:36.779  6724  6744 D UEI.SmartControl: -----service ready thread exits
,08-16 14:40:36.852  6724  6724 D UEI.SmartControl: Internal service binding...
08-16 14:40:36.852  1038  1946 W libprocessgroup: failed to open /acct/uid_10112/pid_5555/cgroup.procs: No such file or directory
,08-16 14:40:39.036  6552  6552 W GAV2    : Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,08-16 14:40:39.043  1038  1711 I ActivityManager: Killing 6171:com.android.calendar/u0a13 (adj 15): empty #17
08-16 14:40:39.051  2113  2113 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19990
08-16 14:40:39.153  1038  1944 W libprocessgroup: failed to open /acct/uid_10013/pid_6171/cgroup.procs: No such file or directory
,08-16 14:40:40.004  6552  6665 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,08-16 14:40:41.731  6724  6746 D UEI.SmartControl: Internal timer expired: 1,
08-16 14:40:41.731  6724  6746 D UEI.SmartControl: unbind internal service
,08-16 14:40:41.754  6724  6724 D UEI.SmartControl: Service.onUnbind: IControl
,08-16 14:40:41.771  6724  6724 D UEI.SmartControl: Service.onDestroy
08-16 14:40:41.771  6724  6724 D UEI.SmartControl: Lock is in USE false
08-16 14:40:41.771  6724  6724 D UEI.SmartControl: unbind internal service
08-16 14:40:41.771  6724  6724 W System.err: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@18d6dd56
08-16 14:40:41.772  6724  6724 W System.err: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
08-16 14:40:41.772  6724  6724 W System.err: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
08-16 14:40:41.772  6724  6724 W System.err: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
08-16 14:40:41.772  6724  6724 W System.err: 	at com.uei.control.Service.c(Unknown Source)
08-16 14:40:41.772  6724  6724 W System.err: 	at com.uei.control.Service.onDestroy(Unknown Source)
08-16 14:40:41.772  6724  6724 W System.err: 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
08-16 14:40:41.772  6724  6724 W System.err: 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
08-16 14:40:41.772  6724  6724 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
08-16 14:40:41.772  6724  6724 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 14:40:41.772  6724  6724 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-16 14:40:41.772  6724  6724 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-16 14:40:41.772  6724  6724 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 14:40:41.772  6724  6724 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 14:40:41.772  6724  6724 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-16 14:40:41.772  6724  6724 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-16 14:40:41.772  6724  6724 E UEI.SmartControl: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@18d6dd56
,08-16 14:40:41.841  6724  6724 D serial_port: close(fd = 25)
,08-16 14:40:41.849  6724  6724 I UEI.SmartControl: Serial port is closed.
08-16 14:40:41.849  6724  6724 I UEI.SmartControl: Serial port is closed.
08-16 14:40:41.849  6724  6724 D UEI.SmartControl: Blaster closed
08-16 14:40:41.849  6724  6724 D UEI.SmartControl: Shut down QS...
08-16 14:40:41.849  6724  6724 D UEI.SmartControl: Stopping QS lib
08-16 14:40:41.849  6724  6724 D UEI.SmartControl: QS lib stop result = true
08-16 14:40:41.849  6724  6724 D UEI.SmartControl: Stopped QS lib
08-16 14:40:41.849  6724  6724 D UEI.SmartControl: Stopped file observer...
08-16 14:40:41.849  6724  6724 D UEI.SmartControl: QS shutdown complete
08-16 14:40:42.024  1803  6474 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,08-16 14:40:42.030   321  6771 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-16 14:40:42.031   321  6771 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
08-16 14:40:42.031   321  6771 D libc-netbsd: res_queryN name = android.clients.google.com succeed
08-16 14:40:42.361  1803  1803 I ConfigFetchService: fetch service done; releasing wakelock
,08-16 14:40:42.366  1803  1803 I ConfigFetchService: stopping self
08-16 14:40:42.375  2178  2178 I ConfigService: onDestroy
,08-16 14:40:47.105  1038  1109 I ActivityManager: Waited long enough for: ServiceRecord{3e0083ee u0 com.google.android.gms/.wearable.service.WearableService}
,08-16 14:40:49.943  1038  1365 V AlarmManager: RTC_WAKEUP set : Alarm{3f58243c type 0 when 1471351247774 com.android.vending} when 1471351247774
,08-16 14:40:50.017  4457  6781 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,08-16 14:40:50.071  1038  1946 V SIM_STK : Menu title from STK is T-Mobile
,08-16 14:40:50.252  6014  6014 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.
,08-16 14:40:53.204  6608  6679 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-16 14:40:53.204  6608  6679 I jxcore-log: 
,08-16 14:40:53.207  6608  6679 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-16 14:40:53.207  6608  6679 I jxcore-log: 
,08-16 14:40:53.212  6608  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 14:40:53.212  6608  6679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:40:53.212  6608  6679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 14:40:53.212  6608  6679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 14:40:53.212  6608  6679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 14:40:53.212  6608  6679 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 14:40:53.212  6608  6679 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 14:40:53.212  6608  6679 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 14:40:53.214  6608  6679 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 14:40:53.217  6608  6679 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-16 14:40:53.217  6608  6679 I jxcore-log: 
08-16 14:40:53.218  6608  6679 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-16 14:40:53.218  6608  6679 I jxcore-log: 
,08-16 14:40:53.560  6608  6679 I jxcore-log: Running unit tests
08-16 14:40:53.560  6608  6679 I jxcore-log: 
08-16 14:40:53.561  6608  6679 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-16 14:40:53.562  6608  6679 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d898987 added. We now have 2 listener(s)
08-16 14:40:53.562  1038  1909 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 14:40:53.564  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-16 14:40:53.564  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 14:40:53.564  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-16 14:40:53.564  6608  6679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 14:40:53.565  6608  6679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10e0e0b4 added. We now have 2 listener(s)
08-16 14:40:53.565  6608  6679 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 14:40:53.565  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-16 14:40:53.567  6608  6679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 14:40:53.569  6608  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 14:40:53.569  6608  6679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:40:53.569  6608  6679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 14:40:53.569  6608  6679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 14:40:53.569  6608  6679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 14:40:53.569  6608  6679 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 14:40:53.569  6608  6679 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 14:40:53.569  6608  6679 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 14:40:53.570  6608  6679 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 14:40:53.570  6608  6679 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 14:40:53.571  6608  6608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:40:53.572  6608  6608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:40:53.573  6608  6679 D ExecuteNativeTests: Running unit tests
,08-16 14:40:53.723  6608  6679 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 14:40:53.723  6608  6679 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21c3aa02 added. We now have 3 listener(s)
08-16 14:40:53.723  1038  1982 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-16 14:40:53.726  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-16 14:40:53.726  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 14:40:53.726  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 14:40:53.726  6608  6679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 14:40:53.726  6608  6679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3da82f13 added. We now have 3 listener(s)
08-16 14:40:53.727  6608  6679 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 14:40:53.727  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 14:40:53.733  6608  6679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 14:40:53.738  6608  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 14:40:53.738  6608  6679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:40:53.738  6608  6679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 14:40:53.738  6608  6679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 14:40:53.738  6608  6679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 14:40:53.738  6608  6679 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 14:40:53.738  6608  6679 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 14:40:53.738  6608  6679 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 14:40:53.740  6608  6679 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 14:40:53.740  6608  6679 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 14:40:53.743  6608  6608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:40:53.745  6608  6608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:40:53.746  6608  6679 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-16 14:40:53.746  6608  6679 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-16 14:40:53.746  6608  6679 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-16 14:40:53.746  6608  6679 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-16 14:40:53.748  6608  6679 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-16 14:40:53.749  6608  6679 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-16 14:40:53.749  6608  6679 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-16 14:40:53.749  6608  6679 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 14:40:53.749  6608  6679 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 14:40:53.749  6608  6679 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 14:40:53.750  6608  6679 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 14:40:53.751  6608  6679 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 14:40:53.752  6608  6679 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 14:40:53.752  6608  6679 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:40:53.752  6608  6679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:40:53.753  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 14:40:53.753  6608  6679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 14:40:53.753  6608  6679 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21c3aa02 removed from the list
08-16 14:40:53.753  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:40:53.753  6608  6679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3da82f13 removed from the list
08-16 14:40:53.753  6608  6679 D io.jxcore.node.ConnectivityMonitor: stop
08-16 14:40:53.753  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:40:53.755  6608  6679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:40:53.755  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:40:53.756  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:40:53.757  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 14:40:53.757  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:40:53.757  6608  6679 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3da82f13 not in the list
08-16 14:40:53.759  6608  6679 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-16 14:40:53.759  6608  6679 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 14:40:53.760  6608  6679 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 14:40:53.760  6608  6679 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 14:40:53.760  6608  6679 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:40:53.760  6608  6679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:40:53.760  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:40:53.760  6608  6679 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21c3aa02 not in the list
08-16 14:40:53.760  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:40:53.761  6608  6679 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3da82f13 not in the list
08-16 14:40:53.761  6608  6679 D io.jxcore.node.ConnectivityMonitor: stop
08-16 14:40:53.761  6608  6679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:40:53.761  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08,-16 14:40:53.761  6608  6679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:40:53.761  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:40:53.762  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:40:53.762  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 14:40:53.762  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:40:53.762  6608  6679 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3da82f13 not in the list
08-16 14:40:53.772  6608  6679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-16 14:40:53.772  6608  6679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-16 14:40:53.772  6608  6679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-16 14:40:53.772  6608  6679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-16 14:40:53.772  6608  6679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-16 14:40:53.773  6608  6679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-16 14:40:53.773  6608  6679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-16 14:40:53.773  6608  6679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-16 14:40:53.773  6608  6679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-16 14:40:53.773  6608  6679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-16 14:40:53.773  6608  6679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,08-16 14:40:53.777  6608  6679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-16 14:40:53.777  6608  6679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-16 14:40:53.777  6608  6679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-16 14:40:53.777  6608  6679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-16 14:40:53.777  6608  6679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-16 14:40:53.777  6608  6679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-16 14:40:53.777  6608  6679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-16 14:40:53.777  6608  6679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-16 14:40:53.777  6608  6679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-16 14:40:53.777  6608  6679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-16 14:40:53.777  6608  6679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-16 14:40:53.777  6608  6679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-16 14:40:53.778  6608  6679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-16 14:40:53.778  6608  6679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-16 14:40:53.778  6608  6679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-16 14:40:53.778  6608  6679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-16 14:40:53.778  6608  6679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-16 14:40:53.778  6608  6679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-16 14:40:53.779  6608  6679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-16 14:40:53.779  6608  6679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-16 14:40:53.779  6608  6679 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 14:40:53.779  6608  6679 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 14:40:53.779  6608  6679 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 14:40:53.779  6608  6679 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:40:53.779  6608  6679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:40:53.779  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:40:53.779  6608  6679 E org.thal,iproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21c3aa02 not in the list
08-16 14:40:53.779  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:40:53.779  6608  6679 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3da82f13 not in the list
08-16 14:40:53.779  6608  6679 D io.jxcore.node.ConnectivityMonitor: stop
08-16 14:40:53.779  6608  6679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:40:53.779  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:40:53.779  6608  6679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:40:53.779  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:40:53.781  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:40:53.781  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 14:40:53.781  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:40:53.781  6608  6679 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3da82f13 not in the list
08-16 14:40:53.782  6608  6679 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-16 14:40:53.784  6608  6679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 14:40:53.787  6608  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 14:40:53.787  6608  6679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:40:53.787  6608  6679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 14:40:53.787  6608  6679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 14:40:53.787  6608  6679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 14:40:53.787  6608  6679 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 14:40:53.787  6608  6679 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 14:40:53.787  6608  6679 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 14:40:53.792  6608  6679 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 14:40:53.792  6608  6679 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 14:40:53.792  6608  6679 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 14:40:53.793  6608  6679 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 14:40:53.793  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 14:40:53.793  6608  6679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 14:40:53.793  6608  6679 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 14:40:53.795  6608  6608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:40:53.797  6608  6608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:40:53.799  6608  6679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-16 14:40:53.799  1038  1909 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 14:40:53.806  6608  6679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-16 14:40:53.813  6608  6679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-16 14:40:53.816  6608  6679 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
,08-16 14:40:53.816  6608  6679 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-16 14:40:53.818  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 14:40:53.820  6608  6679 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-16 14:40:53.820  6608  6679 I io.jxcore.node.ConnectionHelper: start: OK
,08-16 14:40:58.832  6608  6679 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 14:40:58.832  6608  6679 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 14:40:58.832  6608  6679 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 14:40:58.843  6608  6679 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:40:58.843  6608  6679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:40:58.843  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 14:40:58.843  6608  6679 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21c3aa02 not in the list
08-16 14:40:58.843  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:40:58.843  6608  6679 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3da82f13 not in the list
08-16 14:40:58.843  6608  6679 D io.jxcore.node.ConnectivityMonitor: stop
08-16 14:40:58.844  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:40:59.051  2113  2113 I CloudHub: [CLIENT][CloudHubClientFactory$1|onFinish] Time is up to exit
,08-16 14:40:59.059  2113  2113 I CloudHub: [CLIENT][CloudHubClientFactory$1|onFinish] Scheduler destroyed
08-16 14:41:00.071  1589  1589 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-16 14:41:00.071  1589  1589 I KeyguardUpdateMonitor: called onTimeUpdated()
08-16 14:41:00.071  1589  1589 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-16 14:41:00.072  1589  1589 I [SystemUI]Clock: called onTimeUpdated()
,08-16 14:41:00.083  1589  1589 I LgeClockWidgetControlView: called onTimeUpdated()
08-16 14:41:00.084  1589  1589 I [SystemUI]DateView: called onTimeUpdated()
08-16 14:41:00.086  1589  1589 I [SystemUI]DateView: called onTimeUpdated()
08-16 14:41:00.088  1589  1589 D KeyguardUpdateMonitor: handleTimeUpdate
,08-16 14:41:03.845  6608  6679 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-16 14:41:04.020  1038  1053 I art     : Explicit concurrent mark sweep GC freed 20106(1054KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/64MB, paused 2.985ms total 152.120ms
,08-16 14:41:04.023  6608  6679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 14:41:04.027  6608  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 14:41:04.027  6608  6679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:41:04.027  6608  6679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 14:41:04.027  6608  6679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 14:41:04.027  6608  6679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 14:41:04.027  6608  6679 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 14:41:04.027  6608  6679 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 14:41:04.027  6608  6679 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 14:41:04.028  6608  6679 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 14:41:04.028  6608  6679 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 14:41:04.030  6608  6608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:41:04.032  6608  6608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 14:41:04.033  6608  6679 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 14:41:04.034  6608  6679 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 14:41:04.034  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 14:41:04.034  6608  6679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 14:41:04.034  6608  6679 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 14:41:04.038  6608  6679 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 14:41:04.039  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 14:41:04.040  6608  6679 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-16 14:41:04.041  6608  6679 I io.jxcore.node.ConnectionHelper: start: OK
08-16 14:41:04.043  6608  6679 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 14:41:04.043  6608  6679 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 14:41:04.043  6608  6679 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 14:41:04.045  6608  6679 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:41:04.045  6608  6679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:41:04.045  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 14:41:04.045  6608  6679 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21c3aa02 not in the list
08-16 14:41:04.045  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:41:04.045  6608  6679 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3da82f13 not in the list
08-16 14:41:04.045  6608  6679 D io.jxcore.node.ConnectivityMonitor: stop
08-16 14:41:04.045  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:41:04.046  6608  6679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:41:04.047  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:41:04.047  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:41:04.047  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 14:41:04.049  6608  6679 D BluetoothLeScanner: could not find callback wrapper
08-16 14:41:04.049  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 14:41:04.049  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:41:04.050  6608  6679 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3da82f13 not in the list
08-16 14:41:04.051  6608  6679 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-16 14:41:04.054  6608  6679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 14:41:04.059  6608  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 14:41:04.059  6608  6679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:41:04.059  6608  6679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 14:41:04.059  6608  6679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 14:41:04.059  6608  6679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 14:41:04.059  6608  6679 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 14:41:04.059  6608  6679 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 14:41:04.059  6608  6679 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 14:41:04.062  6608  6679 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 14:41:04.062  6608  6679 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 14:41:04.064  6608  6608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:41:04.065  6608  6608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 14:41:04.067  6608  6679 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-16 14:41:04.067  6608  6679 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-16 14:41:04.067  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 14:41:04.067  6608  6679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 14:41:04.067  6608  6679 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 14:41:04.072  6608  6679 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 14:41:04.073  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 14:41:04.075  6608  6679 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-16 14:41:04.075  6608  6679 I io.jxcore.node.ConnectionHelper: start: OK
,08-16 14:41:09.076  6608  6679 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 14:41:09.076  6608  6679 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 14:41:09.076  6608  6679 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 14:41:14.093  6608  6679 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 14:41:14.093  6608  6679 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 14:41:14.093  6608  6679 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 14:41:14.095  6608  6679 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:41:14.096  6608  6679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:41:14.096  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 14:41:14.096  6608  6679 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21c3aa02 not in the list
08-16 14:41:14.096  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:41:14.097  6608  6679 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3da82f13 not in the list
08-16 14:41:14.097  6608  6679 D io.jxcore.node.ConnectivityMonitor: stop
08-16 14:41:14.097  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:41:14.098  6608  6679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:41:14.098  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:41:14.099  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:41:14.099  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 14:41:14.099  6608  6679 D BluetoothLeScanner: could not find callback wrapper
08-16 14:41:14.099  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 14:41:14.099  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:41:14.099  6608  6679 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3da82f13 not in the list
08-16 14:41:14.101  6608  6679 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-16 14:41:14.101  6608  6679 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 14:41:14.101  6608  6679 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 14:41:14.101  6608  6679 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 14:41:14.110  6608  6679 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:41:14.110  6608  6679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:41:14.110  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:41:14.110  6608  6679 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21c3aa02 not in the list
08-16 14:41:14.110  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:41:14.110  6608  6679 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3da82f13 not in the list
08-16 14:41:14.110  6608  6679 D io.jxcore.node.ConnectivityMonitor: stop
08-16 14:41:14.110  6608  6679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:41:14.110  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.Blu,etoothManager: release: 2 listener(s) left
08-16 14:41:14.110  6608  6679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:41:14.110  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 14:41:14.116  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:41:14.116  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 14:41:14.117  6608  6679 D BluetoothLeScanner: could not find callback wrapper
08-16 14:41:14.117  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 14:41:14.117  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:41:14.117  6608  6679 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3da82f13 not in the list
08-16 14:41:14.119  6608  6679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-16 14:41:14.119  6608  6679 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 14:41:14.119  6608  6679 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 14:41:14.119  6608  6679 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 14:41:14.120  6608  6679 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:41:14.120  6608  6679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:41:14.120  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:41:14.120  6608  6679 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21c3aa02 not in the list
08-16 14:41:14.120  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:41:14.120  6608  6679 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3da82f13 not in the list
08-16 14:41:14.120  6608  6679 D io.jxcore.node.ConnectivityMonitor: stop
08-16 14:41:14.120  6608  6679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:41:14.120  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:41:14.120  6608  6679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:41:14.120  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:41:14.122  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:41:14.122  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 14:41:14.122  6608  6679 D BluetoothLeScanner: could not find callback wrapper
08-16 14:41:14.122  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 14:41:14.122  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:41:14.122  6608  6679 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3da82f13 not in the list
08-16 14:41:14.123  6608  6679 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-16 14:41:14.124  6608  6679 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 14:41:14.124  6608  6679 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: ,false, is advertising: false - Stop operation: Should start/stop everything
08-16 14:41:14.124  6608  6679 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 14:41:14.124  6608  6679 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:41:14.124  6608  6679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:41:14.124  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:41:14.124  6608  6679 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21c3aa02 not in the list
08-16 14:41:14.124  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:41:14.125  6608  6679 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3da82f13 not in the list
08-16 14:41:14.125  6608  6679 D io.jxcore.node.ConnectivityMonitor: stop
08-16 14:41:14.125  6608  6679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:41:14.125  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:41:14.125  6608  6679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:41:14.125  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 14:41:14.131  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:41:14.131  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 14:41:14.132  6608  6679 D BluetoothLeScanner: could not find callback wrapper
08-16 14:41:14.132  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 14:41:14.132  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:41:14.132  6608  6679 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3da82f13 not in the list
08-16 14:41:14.133  6608  6679 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-16 14:41:14.133  6608  6679 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 14:41:14.133  6608  6679 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 14:41:14.133  6608  6679 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 14:41:14.134  6608  6679 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:41:14.134  6608  6679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:41:14.134  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:41:14.134  6608  6679 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21c3aa02 not in the list
08-16 14:41:14.134  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:41:14.134  6608  6679 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3da82f13 not in the list
08-16 14:41:14.134  6608  6679 D io.jxcore.node.ConnectivityMonitor: stop
08-16 14:41:14.134  6608  6679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:41:14.134  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:41:14.134  6608  6679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:41:14.134  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:41:14.135  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:41:14.136  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 14:41:14.136  6608  6679 D BluetoothLeScanner: could not find callback wrapper
08-16 14:41:14.136  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 14:41:14.136  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:41:14.136  6608  6679 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3da82f13 not in the list
08-16 14:41:14.137  6608  6679 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-16 14:41:14.140  6608  6679 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> ,1
08-16 14:41:14.140  6608  6679 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-16 14:41:14.144  6608  6679 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-16 14:41:14.145  6608  6679 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 14:41:14.145  6608  6679 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 14:41:14.146  6608  6679 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-16 14:41:14.147  6608  6679 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-16 14:41:14.147  6608  6679 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-16 14:41:14.147  6608  6679 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 14:41:14.147  6608  6679 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 14:41:14.147  6608  6679 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 14:41:14.148  6608  6679 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:41:14.148  6608  6679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:41:14.148  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:41:14.148  6608  6679 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21c3aa02 not in the list
08-16 14:41:14.148  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:41:14.148  6608  6679 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3da82f13 not in the list
08-16 14:41:14.148  6608  6679 D io.jxcore.node.ConnectivityMonitor: stop
08-16 14:41:14.148  6608  6679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:41:14.148  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:41:14.148  6608  6679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:41:14.148  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:41:14.149  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:41:14.149  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 14:41:14.150  6608  6679 D BluetoothLeScanner: could not find callback wrapper
08-16 14:41:14.150  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 14:41:14.150  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:41:14.151  6608  6679 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3da82f13 not in the list
08-16 14:41:14.151  6608  6679 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 14:41:14.152  6608  6679 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-16 14:41:1,4.152  6608  6679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-16 14:41:14.156  6608  6679 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 14:41:14.156  6608  6679 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-16 14:41:14.156  6608  6679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-16 14:41:14.156  6608  6679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-16 14:41:14.156  6608  6679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-16 14:41:14.156  6608  6679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-16 14:41:14.156  6608  6679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-16 14:41:14.156  6608  6679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-16 14:41:14.156  6608  6679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-16 14:41:14.156  6608  6679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-16 14:41:14.157  6608  6679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810],
08-16 14:41:14.157  6608  6679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-16 14:41:14.157  6608  6679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-16 14:41:14.157  6608  6679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-16 14:41:14.157  6608  6679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-16 14:41:14.157  6608  6679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-16 14:41:14.157  6608  6679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,08-16 14:41:14.157  6608  6679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-16 14:41:14.157  6608  6679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-16 14:41:14.157  6608  6679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-16 14:41:14.157  6608  6679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-16 14:41:14.157  6608  6679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-16 14:41:14.157  6608  6679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,08-16 14:41:14.157  6608  6679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-16 14:41:14.157  6608  6679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-16 14:41:14.157  6608  6679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-16 14:41:14.157  6608  6679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-16 14:41:14.157  6608  6679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,08-16 14:41:14.157  6608  6679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-16 14:41:14.157  6608  6679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-16 14:41:14.157  6608  6679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-16 14:41:14.157  6608  6679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910],
08-16 14:41:14.158  6608  6679 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-16 14:41:14.158  6608  6679 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-16 14:41:14.158  6608  6679 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
,08-16 14:41:14.171  6608  6679 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 14:41:14.171  6608  6679 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-16 14:41:14.171  6608  6679 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-16 14:41:14.171  6608  6679 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 14:41:14.171  6608  6679 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-16 14:41:14.171  6608  6679 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,08-16 14:41:14.175  6608  6679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-16 14:41:14.179  6608  6679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-16 14:41:14.179  6608  6679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-16 14:41:14.180  6608  6679 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-16 14:41:14.181  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-16 14:41:14.181  6608  6679 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-16 14:41:14.181  6608  6679 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 14:41:14.181  6608  6679 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-16 14:41:14.182  6608  6679 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 14:41:14.182  6608  6679 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 14:41:14.182  6608  6679 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 14:41:14.183  6608  6679 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:41:14.183  6608  6679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:41:14.183  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:41:14.183  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-16 14:41:14.184  6608  6679 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21c3aa02 not in the list
08-16 14:41:14.184  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:41:14.184  6608  6679 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3da82f13 not in the list
08-16 14:41:14.184  6608  6679 D io.jxcore.node.ConnectivityMonitor: stop
08-16 14:41:14.184  6608  6679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:41:14.184  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:41:14.184  6608  6679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:41:14.184  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
,08-16 14:41:14.188  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:41:14.191  6608  6808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 821)
08-16 14:41:14.205  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 14:41:14.208  6608  6679 D BluetoothLeScanner: could not find callback wrapper
08-16 14:41:14.208  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 14:41:14.208  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:41:14.208  6608  6679 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3da82f13 not in the list
08-16 14:41:14.209  6608  6679 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-16 14:41:14.210  6608  6679 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 14:41:14.210  6608  6679 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 14:41:14.210  6608  6679 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 14:41:14.230  6608  6679 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:41:14.230  6608  6679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:41:14.230  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 14:41:14.230  6608  6679 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21c3aa02 not in the list
08-16 14:41:14.230  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:41:14.230  6608  6679 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3da82f13 not in the list
08-16 14:41:14.230  6608  6679 D io.jxcore.node.ConnectivityMonitor: stop
08-16 14:41:14.230  6608  6679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:41:14.231  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:41:14.231  6608  6679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:41:14.231  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:41:14.232  6608  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 821
08-16 14:41:14.232  6608  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 821)
08-16 14:41:14.232  6608  6809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 821)
08-16 14:41:14.234  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 14:41:14.234  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 14:41:14.235  6608  6679 D BluetoothLeScanner: could not find callback wrapper
08-16 14:41:14.235  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 14:41:14.235  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:41:14.235  6608  6679 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3da82f13 not in the list
08-16 14:41:14.236  6608  6679 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-16 14:41:14.237  6608  6679 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 14:41:14.237  6608  6679 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 14:41:14.237  6608  6679 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 14:41:14.237  6608  6679 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:41:14.237  6608  6679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:41:14.237  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:41:14.237  6608  6679 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21c3aa02 not in the list
08-16 14:41:14.237  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:41:14.237  6608  6679 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3da82f13 not in the list
08-16 14:41:14.237  6608  6679 D io.jxcore.node.ConnectivityMonitor: stop
08-16 14:41:14.237  6608  6679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:41:14.237  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:41:14.238  6608  6679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:41:14.238  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:41:14.238  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:41:14.238  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 14:41:14.239  6608  6679 D BluetoothLeScanner: could not find callback wrapper
08-16 14:41:14.239  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 14:41:14.239  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:41:14.239  6608  6679 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3da82f13 not in the list
08-16 14:41:14.240  6608  6679 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-16 14:41:14.240  6608  6679 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-16 14:41:14.240  6608  6679 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s,) left
08-16 14:41:14.241  6608  6679 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-16 14:41:14.241  6608  6679 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-16 14:41:14.241  6608  6679 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-16 14:41:14.241  6608  6679 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-16 14:41:14.241  6608  6679 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-16 14:41:14.241  6608  6679 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-16 14:41:14.241  6608  6679 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-16 14:41:14.241  6608  6679 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-16 14:41:14.241  6608  6679 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-16 14:41:14.241  6608  6679 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 14:41:14.241  6608  6679 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 14:41:14.241  6608  6679 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 14:41:14.252  6608  6679 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:41:14.253  6608  6679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:41:14.253  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:41:14.253  6608  6679 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21c3aa02 not in the list
08-16 14:41:14.253  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:41:14.253  6608  6679 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3da82f13 not in the list
08-16 14:41:14.253  6608  6679 D io.jxcore.node.ConnectivityMonitor: stop
08-16 14:41:14.253  6608  6679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:41:14.253  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:41:14.253  6608  6679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:41:14.253  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:41:14.254  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:41:14.254  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 14:41:14.259  6608  6679 D BluetoothLeScanner: could not find callback wrapper
,08-16 14:41:14.259  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 14:41:14.260  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:41:14.260  6608  6679 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3da82f13 not in the list
08-16 14:41:14.262  6608  6679 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:41:14.262  6608  6679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:41:14.262  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:41:14.262  6608  6679 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21c3aa02 not in the list
08-16 14:41:14.262  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:41:14.262  6608  6679 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3da82f13 not in the list
08-16 14:41:14.262  6608  6679 D io.jxcore.node.ConnectivityMonitor: stop
08-16 14:41:14.262  6608  6679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:41:14.262  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:41:14.336  6608  6808 W LGMDMUISystemServiceAdapter: checkBluetoothPairing btPolicy: false
08-16 14:41:14.336  6608  6808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 821)
,08-16 14:41:19.264  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:41:19.264  6608  6679 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3da82f13 not in the list
08-16 14:41:19.264  6608  6679 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:41:19.264  6608  6679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:41:19.264  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:41:19.265  6608  6679 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21c3aa02 not in the list
08-16 14:41:19.265  6608  6679 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 14:41:19.265  6608  6679 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 14:41:19.265  6608  6679 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 14:41:19.275  6608  6679 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:41:19.275  6608  6679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:41:19.275  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:41:19.275  6608  6679 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21c3aa02 not in the list
08-16 14:41:19.275  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:41:19.275  6608  6679 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3da82f13 not in the list
08-16 14:41:19.275  6608  6679 D io.jxcore.node.ConnectivityMonitor: stop
08-16 14:41:19.276  6608  6679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:41:19.276  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:41:19.276  6608  6679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:41:19.276  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:41:19.281  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:41:19.281  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 14:41:19.283  6608  6679 D BluetoothLeScanner: could not find callback wrapper
08-16 14:41:19.283  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 14:41:19.283  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:41:19.283  6608  6679 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3da82f13 not in the list
,08-16 14:41:19.288  6608  6679 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-16 14:41:19.289  6608  6679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 14:41:19.290  6608  6679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-16 14:41:19.291  6608  6679 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-16 14:41:19.291  6608  6679 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-16 14:41:19.291  6608  6608 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-16 14:41:19.292  6608  6679 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-16 14:41:19.292  6608  6679 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-16 14:41:19.293  6608  6679 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:41:19.293  6608  6679 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-16 14:41:19.293  6608  6679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-16 14:41:19.293  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-16 14:41:19.293  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:41:19.293  6608  6679 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-16 14:41:19.296  6608  6836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-16 14:41:19.296  6608  6836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,08-16 14:41:19.299  6608  6608 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-16 14:41:19.300  6608  6679 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21c3aa02 not in the list
08-16 14:41:19.300  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:41:19.300  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-16 14:41:19.300  6608  6679 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-16 14:41:19.300  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-16 14:41:19.302  6608  6679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-16 14:41:19.303  6608  6679 D BluetoothLeScanner: could not find callback wrapper
08-16 14:41:19.303  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 14:41:19.303  6608  6679 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-16 14:41:19.304  6608  6679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:41:19.304  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:41:19.305  6608  6679 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 14:41:19.306  6608  6608 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 14:41:19.306  6608  6608 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-16 14:41:19.306  6608  6608 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 14:41:19.306  6608  6608 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 14:41:19.306  6608  6679 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3da82f13 not in the list
08-16 14:41:19.306  6608  6679 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 14:41:19.306  6608  6679 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 14:41:19.306  6608  6679 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 14:41:19.307  6608  6679 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:41:19.307  6608  6679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:41:19.307  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:41:19.307  6608  6679 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21c3aa02 not in the list
08-16 14:41:19.307  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:41:19.307  6608  6679 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3da82f13 not in the list
08-16 14:41:19.307  6608  6679 D io.jxcore.node.ConnectivityMonitor: stop
08-16 14:41:19.307  6608 , 6679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:41:19.307  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:41:19.307  6608  6679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:41:19.307  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:41:19.309  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:41:19.309  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 14:41:19.309  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:41:19.309  6608  6679 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3da82f13 not in the list
08-16 14:41:19.310  6608  6679 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
,08-16 14:41:19.315  6608  6679 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-16 14:41:19.315  6608  6679 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-16 14:41:19.318  6608  6679 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 14:41:19.318  6608  6679 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 14:41:19.319  6608  6679 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 14:41:19.319  6608  6679 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 14:41:19.319  6608  6679 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 14:41:19.321  6608  6679 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:41:19.321  6608  6679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:41:19.321  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:41:19.321  6608  6679 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21c3aa02 not in the list
08-16 14:41:19.321  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:41:19.322  6608  6679 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3da82f13 not in the list
08-16 14:41:19.322  6608  6679 D io.jxcore.node.ConnectivityMonitor: stop
08-16 14:41:19.322  6608  6679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:41:19.322  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:41:19.322  6608  6679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:41:19.322  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:41:19.323  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:41:19.323  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 14:41:19.323  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:41:19.323  6608  6679 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3da82f13 not in the list
,08-16 14:41:19.329  1038  1982 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 14:41:19.331  1038  1054 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 14:41:19.332  1038  2019 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 14:41:19.333  6608  6679 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 14:41:19.333  6608  6679 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 14:41:19.333  6608  6679 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 14:41:19.334  6608  6679 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:41:19.334  6608  6679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:41:19.334  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:41:19.334  6608  6679 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21c3aa02 not in the list
08-16 14:41:19.334  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:41:19.334  6608  6679 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3da82f13 not in the list
08-16 14:41:19.334  6608  6679 D io.jxcore.node.ConnectivityMonitor: stop
08-16 14:41:19.334  6608  6679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:41:19.334  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:41:19.334  6608  6679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:41:19.334  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:41:19.335  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:41:19.335  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 14:41:19.335  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:41:19.336  6608  6679 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3da82f13 not in the list
08-16 14:41:19.338  6608  6679 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 14:41:19.338  6608  6679 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 14:41:19.338  6608  6679 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 14:41:19.342  6608  6679 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:41:19.342  6608  6679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:41:19.342  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:41:19.342  6608  6679 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21c3aa02 not in the list
08-16 14:41:19.342  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:41:19.342  6608  6679 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3da82f13 not in the list
08-16 14:41:19.342  6608  6679 D io.jxcore.node.ConnectivityMonitor: stop
08-16 14:41:19.342  6608  6679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:41:19.342  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:41:19.342  6608  6679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:41:19.342  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:41:19.344  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:41:19.344  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 14:41:19.344  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:41:19.344  6608  6679 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3da82f13 not in the list
08-16 14:41:19.346  6608  6679 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-16 14:41:19.346  6608  6679 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-16 14:41:19.347  6608  6679 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-16 14:41:19.347  6608  6679 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-16 14:41:19.347  6608  6679 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-16 14:41:19.347  6608  6679 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-16 14:41:19.349  6608  6679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-16 14:41:19.349  6608  6679 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-16 14:41:19.351  6608  6679 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-16 14:41:19.351  6608  6679 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-16 14:41:19.352  6608  6679 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-16 14:41:19.352  6608  6679 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-16 14:41:19.352  6608  6679 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-16 14:41:19.352  6608  6679 D io.jxcore.node.Connecti,onModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-16 14:41:19.353  6608  6679 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-16 14:41:19.353  6608  6679 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-16 14:41:19.353  6608  6679 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-16 14:41:19.354  6608  6679 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-16 14:41:19.354  6608  6679 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-16 14:41:19.354  6608  6679 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-16 14:41:19.355  6608  6679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 14:41:19.355  6608  6679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1352e68 added. We now have 3 listener(s)
08-16 14:41:19.355  6608  6679 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 14:41:19.363  6608  6679 D BluetoothAdapter: enable(): BT is already enabled..!
08-16 14:41:19.364  1038  2037 D WifiServiceImplEx: setWifiEnabled: true pid=6608, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-16 14:41:19.365  1038  2037 D WifiService: setWifiEnabled: true pid=6608, uid=10118
08-16 14:41:19.365  1038  2037 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-16 14:41:19.807  6608  6608 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-16 14:41:24.373  6608  6679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 14:41:24.373  6608  6679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@438a281 added. We now have 4 listener(s)
,08-16 14:41:24.373  6608  6679 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 14:41:24.387  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:41:24.387  6608  6679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@438a281 removed from the list
08-16 14:41:24.387  6608  6679 D io.jxcore.node.ConnectivityMonitor: stop
08-16 14:41:24.387  6608  6679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:41:24.387  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:41:24.388  6608  6679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 14:41:24.388  6608  6679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3e66af26 added. We now have 4 listener(s)
08-16 14:41:24.388  6608  6679 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 14:41:24.390  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:41:24.390  6608  6679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3e66af26 removed from the list
08-16 14:41:24.390  6608  6679 D io.jxcore.node.ConnectivityMonitor: stop
08-16 14:41:24.390  6608  6679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:41:24.390  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:41:24.391  6608  6679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 14:41:24.391  6608  6679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@387a5767 added. We now have 4 listener(s)
08-16 14:41:24.391  6608  6679 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 14:41:24.396  1038  2037 D WifiServiceImplEx: setWifiEnabled: false pid=6608, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,08-16 14:41:24.399  1038  2037 D WifiService: setWifiEnabled: false pid=6608, uid=10118
08-16 14:41:24.399  1038  2037 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-16 14:41:24.422  1038  1038 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-16 14:41:24.422  1038  1038 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-16 14:41:24.423  1038  1038 D Ulp_jni : JNI:system_update. Event-4
08-16 14:41:24.424  1038  1381 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-16 14:41:24.425  1038  1381 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-16 14:41:24.425  1038  1381 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-16 14:41:24.425  1038  1381 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-16 14:41:24.426  1038  1381 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-16 14:41:24.426  1038  1381 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-16 14:41:24.426  1038  1381 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-16 14:41:24.426  1038  1381 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-16 14:41:24.427  1038  1381 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-16 14:41:24.427  1038  1381 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-16 14:41:24.429  1038  1981 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 14:41:24.430  1038  1981 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@17950aed mBinding = false
,08-16 14:41:24.445  1038  1381 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-16 14:41:24.445  1038  1381 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-16 14:41:24.446  2755  2755 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
,08-16 14:41:24.448  1038  1377 D LGWifiP2pService: InactiveState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:41:24.448  1038  1377 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:41:24.448  1038  1381 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-16 14:41:24.448  1038  1381 D WifiNative-wlan0: doBoolean: SET ps 1
08-16 14:41:24.449  1038  1381 D WifiNative-wlan0: SET ps 1: returned true
08-16 14:41:24.449   321   895 D CommandListener: Clearing all IP addresses on wlan0
08-16 14:41:24.460  1038  2857 D DhcpStateMachine: RunningState{ when=-11ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,08-16 14:41:24.490  1038  1120 D BluetoothManagerService: Message: 2
,08-16 14:41:24.494  1038  1120 D BluetoothManagerService: Sending off request.
08-16 14:41:24.511  1038  1038 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-16 14:41:24.511  1038  1038 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-16 14:41:24.511  1038  1038 D Ulp_jni : JNI:system_update. Event-4
,08-16 14:41:24.514  6608  6679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 14:41:24.515  3825  4331 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-16 14:41:24.520  3825  3901 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-16 14:41:24.520  3825  3901 D BluetoothAdapterProperties: Setting state to 13
08-16 14:41:24.520  3825  3901 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-16 14:41:24.521  3825  3901 D BluetoothAdapterProperties: onBluetoothDisable()
08-16 14:41:24.521  3825  3901 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-16 14:41:24.551  3825  3906 D BluetoothAdapterProperties: Scan Mode:20
08-16 14:41:24.551  3825  3901 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,08-16 14:41:24.554  3825  4221 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 14:41:24.555  3825  3901 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-16 14:41:24.555  3825  4281 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 14:41:24.561  1038  1448 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-16 14:41:24.562  1038  1448 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
08-16 14:41:24.567  3825  4278 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 14:41:24.567  3825  4277 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-16 14:41:24.567  3825  4220 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-16 14:41:24.567  3825  4220 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 14:41:24.567  3825  4220 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-16 14:41:24.567  3825  4220 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-16 14:41:24.567  3825  4220 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-16 14:41:24.567  3825  4220 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-16 14:41:24.567  3825  4220 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-16 14:41:24.567  3825  4220 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
,08-16 14:41:24.569  1038  1120 D BluetoothManagerService: Message: 60
08-16 14:41:24.570  1038  1120 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-16 14:41:24.570  1038  1120 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-16 14:41:24.570  3825  4012 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-16 14:41:24.570  3825  4012 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-16 14:41:24.571  3825  4012 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 14:41:24.571  3825  4012 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 14:41:24.571  3825  4012 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 14:41:24.571  3825  4012 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 14:41:24.571  3825  4012 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 14:41:24.571  3825  4012 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 14:41:24.571  3825  4012 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 14:41:24.571  3825  4012 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 14:41:24.571  3825  4012 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 14:41:24.571  3825  4012 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-16 14:41:24.571  3825  4012 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-16 14:41:24.572  3825  4012 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-16 14:41:24.583  1038  1562 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
,08-16 14:41:24.584  1038  2855 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:41:24.584  1038  2855 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:41:24.585  1038  2855 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-16 14:41:24.585  1038  2855 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:41:24.585  1038  2855 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on <unknown ssid>
08-16 14:41:24.593  1038  1109 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6857 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
08-16 14:41:24.594  6608  6679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:41:24.594  6608  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 14:41:24.594  6608  6679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:41:24.594  6608  6679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 14:41:24.594  6608  6679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 14:41:24.594  6608  6679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 14:41:24.594  6608  6679 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 14:41:24.594  6608  6679 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 14:41:24.594  6608  6679 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 14:41:24.595  6608  6679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 14:41:24.595  6608  6679 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 14:41:24.595  6608  6679 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 14:41:24.597  6608  6608 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:41:24.597  6608  6608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 14:41:24.597  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:41:24.597  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 14:41:24.597  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 14:41:24.597  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 14:41:24.597  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 14:41:24.597  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 14:41:24.597  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 14:41:24.598  6608  6608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:41:24.599  6608  6608 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:41:24.599  6608  6608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 14:41:24.599  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:41:24.599  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 14:41:24.599  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 14:41:24.599  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 14:41:24.599  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 14:41:24.599  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 14:41:24.599  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 14:41:24.600  6608  6608 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:41:24.600  6608  6608 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 14:41:24.601  6608  6608 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:41:24.601  6608  6608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 14:41:24.601  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:41:24.601  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 14:41:24.601  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 14:41:24.601  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 14:41:24.601  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 14:41:24.601  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 14:41:24.601  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - activ,e network type is Wi-Fi: true
08-16 14:41:24.602  6608  6608 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:41:24.602  6608  6608 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 14:41:24.604  6608  6608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:41:24.609  1038  1038 D WifiHS20: hidePasspointNotification off =false
08-16 14:41:24.609  1038  1038 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:41:24.609  1038  1038 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 14:41:24.609  1038  1038 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-16 14:41:24.609  1038  1038 D WifiHS20: hidePasspointNotification off =false
08-16 14:41:24.609  1038  1038 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:41:24.609  1038  1038 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:41:24.609  1038  1038 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-16 14:41:24.612  1927  1927 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-16 14:41:24.614  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 14:41:24.614  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 14:41:24.615  1038  1377 D LGWifiP2pService: InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:41:24.615  1038  1377 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:41:24.615  1038  1377 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@3bac0238
08-16 14:41:24.616  1038  1381 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 14:41:24.616  1038  1381 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 14:41:24.616  1038  1381 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 14:41:24.617  1038  1381 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 14:41:24.617  1038  1381 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 14:41:24.617  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 14:41:24.617  1038  1381 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 14:41:24.618  1038  1381 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-16 14:41:24.618  1038  1381 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 14:41:24.619  1038  1381 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 14:41:24.619  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 14:41:24.619  1038  1381 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 14:41:24.619  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 14:41:24.619  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 14:41:24.620  1038  1038 D WifiScanningService: SCAN_AVAILABLE : 1
08-16 14:41:24.620  1038  1038 D RttService: SCAN_AVAILABLE : 1
08-16 14:41:24.622  1038  1542 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:41:24.622  1038  1543 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:41:24.622  1038  1377 D LGWifiP2pService: P2pDisablingState
08-16 14:41:24.622  1038  1377 D LGWifiP2pService: P2pDisablingState{ when=-7ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:41:24.622  1038  1377 D LGWifiP2pService: p2p socket connection lost
08-16 14:41:24.622  1038  1377 D LGWifiP2pService: P2pDisabledState
,08-16 14:41:24.623  3825  3825 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-16 14:41:24.623  3825  3825 D BluetoothMapService: STATE_TURNING_OFF
08-16 14:41:24.623  3825  3825 V BluetoothMapService: Handler(): got msg=4
08-16 14:41:24.623  3825  3825 D BluetoothMapService: MAP Service closeService in
08-16 14:41:24.624  3825  3825 D BluetoothMapMasInstance: MAP Service shutdown
,08-16 14:41:24.624  3825  3825 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-16 14:41:24.624  1038  1381 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-16 14:41:24.624  3825  3825 V BluetoothMapService: MAP Service closeService out
08-16 14:41:24.624  1038  1377 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:41:24.624  1038  1377 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:41:24.624  1038  1381 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-16 14:41:24.625  2755  2755 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-16 14:41:24.625  1038  1381 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-16 14:41:24.625  1038  1381 D WifiNative-wlan0: doBoolean: SET ps 1
08-16 14:41:24.627  6608  6608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:41:24.628  1038  1381 D WifiNative-wlan0: SET ps 1: returned true
08-16 14:41:24.629  1927  1927 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-16 14:41:24.630  3825  3825 V BtOppService: Receiver DISABLED_ACTION 
08-16 14:41:24.630  3825  3825 I BtOppRfcommListener: stopping Accept Thread
08-16 14:41:24.630  3825  3825 V BtOppRfcommListener: close mBtServerSocket
08-16 14:41:24.630  3825  3825 V BtOppRfcommListener: waiting for thread to terminate
08-16 14:41:24.631  3825  4277 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-16 14:41:24.631  3825  3825 V BtOppRfcommListener: done waiting for thread to terminate
08-16 14:41:24.632  6608  6608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:41:24.633  6608  6608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:41:24.638  1589  1589 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,08-16 14:41:24.641   321   895 D CommandListener: Clearing all IP addresses on wlan0
08-16 14:41:24.642  1038  1448 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-16 14:41:24.642  1038  1448 D DSQN    : disableDataServiceNotify
08-16 14:41:24.642  1038  1448 D DSQN    : stop dsqn bin
08-16 14:41:24.643   321  6880 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-16 14:41:24.644  1038  1118 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-16 14:41:24.644  1038  2855 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
08-16 14:41:24.646  1038  1109 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6879 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-16 14:41:24.647  1927  1927 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-16 14:41:24.647  1927  1927 D WfdsService: WifiP2pState is changed : false
08-16 14:41:24.647  1927  2284 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-16 14:41:24.647  1927  2284 D WfdsService: Set the WFDS Monitor: false
08-16 14:41:24.648  1038  1381 D WifiNative-p2p0: doBoolean: TERMINATE
08-16 14:41:24.648  1038  1038 D WifiHS20: hidePasspointNotification off =false
08-16 14:41:24.649  3825  3825 V BtOppService: onDestroy
08-16 14:41:24.649  1038  1038 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:41:24.649  1038  1038 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:41:24.649  1038  1038 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-16 14:41:24.649  1038  1381 D WifiNative-p2p0: TERMINATE: returned true
08-16 14:41:24.649  1038  1381 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-16 14:41:24.649  1038  1381 E WifiStateMachine: useWiFiOffloading() : false
08-16 14:41:24.649  1038  1381 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-16 14:41:24.651  1927  2284 D WfdsMonitor: WFDS Monitor is stopped
08-16 14:41:24.652  1927  2284 D WfdsService: STATE : WfdsDisabledState - enter
08-16 14:41:24.652  1927  2285 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-16 14:41:24.652  1927  2796 D CtrlSupplicant: Received on exit socket, terminate
08-16 14:41:24.652  1927  2796 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-16 14:41:24.652  1927  2796 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
,08-16 14:41:24.652  1927  2796 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-16 14:41:24.652  1927  2284 W WfdsService: DefaultState - msg [9445378] is not handled
08-16 14:41:24.652  3825  3825 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-16 14:41:24.653  1927  1927 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-16 14:41:24.655  1038  1448 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-16 14:41:24.655  1038  1448 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 14:41:24.655  1038  1448 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 14:41:24.655  1038  1448 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 14:41:24.655  1038  1448 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-16 14:41:24.656  1038  1448 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-16 14:41:24.656  1038  1448 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-16 14:41:24.656  1038  1448 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-16 14:41:24.656  1038  2855 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:41:24.656  1038  2855 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:41:24.656  1038  2855 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-16 14:41:24.657  1589  1837 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-16 14:41:24.659  1038  1038 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-16 14:41:24.659  1038  1038 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 14:41:24.659  1038  1038 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-16 14:41:24.659  1038  1448 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-16 14:41:24.659  1038  1448 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-16 14:41:24.659  1038  1448 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-16 14:41:24.660  1038  1448 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 14:41:24.660  1038  1448 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 14:41:24.660  1038  1448 D NetworkManagementService: Removing idletimer
08-16 14:41:24.660  1839  1839 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 14:,41:24.660  1038  1448 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:41:24.661  1839  1839 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-16 14:41:24.661  1038  1448 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-16 14:41:24.662  1038  1381 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 14:41:24.662  1038  1381 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 14:41:24.662  1038  1038 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-16 14:41:24.663  1038  1375 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-16 14:41:24.663  1038  1038 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-16 14:41:24.663  1038  1038 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-16 14:41:24.663  1038  1038 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-16 14:41:24.667  1038  1038 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-16 14:41:24.667  1038  1038 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-16 14:41:24.667  1038  1038 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-16 14:41:24.667  1038  1038 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-16 14:41:24.667  1038  1375 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-16 14:41:24.676  6608  6608 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:41:24.676  6608  6608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 14:41:24.676  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:41:24.676  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 14:41:24.676  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 14:41:24.676  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 14:41:24.676  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 14:41:24.676  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 14:41:24.676  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 14:41:24.677  6608  6608 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:41:24.677  6608  6608 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 14:41:24.677  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-16 14:41:24.677  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 14:41:24.678  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 14:41:24.679  6608  6608 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:41:24.679  6608  6608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 14:41:24.679  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:41:24.679  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 14:41:24.679  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 14:41:24.679  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 14:41:24.679  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 14:41:24.679  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 14:41:24.679  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 14:41:24.680  6608  6608 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:41:24.680  6608  6608 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 14:41:24.683  6608  6608 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:41:24.683  6608  6608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 14:41:24.683  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:41:24.683  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 14:41:24.683  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 14:41:24.683  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 14:41:24.683  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 14:41:24.683  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 14:41:24.683  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 14:41:24.684  6608  6608 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:41:24.684  6608  6608 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 14:41:24.698  6879  6879 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 14:41:24.698  6879  6879 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
,08-16 14:41:24.698  6879  6879 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-16 14:41:24.699  6879  6879 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
08-16 14:41:24.700  6879  6879 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-16 14:41:24.701  6879  6879 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-16 14:41:24.707  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 14:41:24.712  6857  6857 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-16 14:41:24.713  6857  6857 W LG Account v2.2: No ProfileInfo entries
08-16 14:41:24.713  6857  6857 I LG Account v2.2: isEnabled: false
,08-16 14:41:24.713  6857  6857 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-16 14:41:24.713  6857  6857 I Feature : [Lifetracker]Country: EU
08-16 14:41:24.713  6857  6857 I Feature : [Lifetracker]Operator: OPEN
08-16 14:41:24.713  6857  6857 I Feature : [Lifetracker]Ranking support: false
08-16 14:41:24.713  6857  6857 I Feature : [Lifetracker]Comfort support: false
08-16 14:41:24.713  6857  6857 I Feature : [Lifetracker]Accessory: true
08-16 14:41:24.713  6857  6857 I Feature : [Lifetracker]Health device: true
08-16 14:41:24.713  6857  6857 I Feature : [Lifetracker]Extra Pedometer: false
08-16 14:41:24.713  6857  6857 I Feature : [Lifetracker]Blood glucose device: false
08-16 14:41:24.713  6857  6857 I Feature : [Lifetracker]Device Number: 3
08-16 14:41:24.719  6411  6411 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 14:41:24.754  1038  2019 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6899 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-16 14:41:24.755  1038  2019 I ActivityManager: Killing 6141:com.android.providers.calendar/u0a14 (adj 15): empty #17
,08-16 14:41:24.762  2755  2755 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-16 14:41:24.762  2755  2755 I wpa_supplicant: monitor socket send errors count : 1
,08-16 14:41:24.762  2755  2755 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1927-2\x00 that cannot receive messages
08-16 14:41:24.763  1038  2791 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-16 14:41:24.763  1038  2791 D WifiMonitor: Dropping event because (p2p0) is stopped
08-16 14:41:24.791  1038  1982 W libprocessgroup: failed to open /acct/uid_10014/pid_6141/cgroup.procs: No such file or directory
,08-16 14:41:24.794  1038  2857 D DhcpStateMachine: StoppedState
08-16 14:41:24.794  1038  2857 D DhcpStateMachine: StoppedState{ when=-166ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:41:24.796  1038  1381 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-16 14:41:24.796  1038  1381 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-16 14:41:24.799  1589  1589 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-16 14:41:24.800  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 14:41:24.801  2755  2755 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-16 14:41:24.801  2755  2755 W wpa_supplicant: USIM:  scard_deinit function
08-16 14:41:24.802  1038  1120 D Tethering: InitialState.processMessage what=4
08-16 14:41:24.802  1038  2791 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-16 14:41:24.802  1038  2791 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-16 14:41:24.802  1038  2791 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-16 14:41:24.802  1038  2791 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-16 14:41:24.802  1038  2791 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 14:41:24.802  1038  2791 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-16 14:41:24.803  1038  1381 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=161970
08-16 14:41:24.803  1038  1120 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-16 14:41:24.803  1038  1381 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=161971
08-16 14:41:24.804  1038  1381 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=161971  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-16 14:41:24.805  1038  1381 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=161972  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-16 14:41:24.806  1038  1381 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-16 14:41:24.806  1038  1381 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-16 14:41:24.807  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 14:41:24.827  1589  1589 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,08-16 14:41:24.828  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-16 14:41:24.829  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 14:41:24.839  6899  6899 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,08-16 14:41:24.843  6899  6899 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
,08-16 14:41:24.843  6899  6899 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-16 14:41:24.844  1038  2018 I ActivityManager: Killing 2113:com.lge.music/u0a34 (adj 15): empty #17
08-16 14:41:24.851  6879  6879 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-16 14:41:24.855   325  2115 V AudioFlinger: 2113 died, releasing its sessions
08-16 14:41:24.855   325  2115 V AudioFlinger:  pid 1839 @ 0
08-16 14:41:24.856   325  2115 V AudioFlinger:  pid 3346 @ 1
08-16 14:41:24.856   325  2115 V AudioFlinger:  pid 3346 @ 2
08-16 14:41:24.877  1038  1054 W libprocessgroup: failed to open /acct/uid_10034/pid_2113/cgroup.procs: No such file or directory
,08-16 14:41:24.881  3825  3825 V BluetoothPbapReceiver: PbapReceiver onReceive 
,08-16 14:41:24.881  3825  3825 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 14:41:24.882  3825  3825 V BluetoothPbapReceiver: ***********state = 13
08-16 14:41:24.883  3825  3825 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-16 14:41:24.884  3825  3825 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 14:41:24.884  3825  3825 V BluetoothPbapService: state: 13
08-16 14:41:24.884  3825  3825 V BluetoothPbapService: Pbap Service closeService in
08-16 14:41:24.886  3825  3825 V BluetoothPbapService: successfully stopped pbap service
08-16 14:41:24.886  3825  3825 V BluetoothPbapService: Pbap Service closeService out
08-16 14:41:24.886  3825  3825 V BluetoothPbapService: Pbap Service onDestroy
08-16 14:41:24.886  2178  2178 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-16 14:41:24.886  3825  3825 V BluetoothPbapService: Pbap Service closeService in
08-16 14:41:24.886  3825  3825 V BluetoothPbapService: Pbap Service closeService out
08-16 14:41:24.886  3825  3825 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-16 14:41:24.893  6879  6879 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 14:41:24.902  2755  2755 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-16 14:41:24.904  1038  2791 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-16 14:41:24.904  1038  2791 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
,08-16 14:41:24.905  1038  2791 D WifiMonitor: Disconnecting from the supplicant, no more events
08-16 14:41:24.907  1038  1381 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
,08-16 14:41:24.941  6879  6879 D LgDataFeature: LgDataFeature() Constructor: none
08-16 14:41:24.941  6879  6879 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 14:41:24.955  6879  6879 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 14:41:24.963  1038  1120 D BluetoothManagerService: Message: 20
08-16 14:41:24.963  1038  1120 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@932709c:true
08-16 14:41:24.975  1038  1120 D BluetoothManagerService: Message: 30
,08-16 14:41:24.982  1038  1120 D BluetoothManagerService: Message: 30
08-16 14:41:24.984  6879  6879 D LocalBluetoothProfileManager: Adding local MAP profile
08-16 14:41:24.986  6879  6879 D BluetoothMap: Create BluetoothMap proxy object
08-16 14:41:24.987  1038  1120 D BluetoothManagerService: Message: 30
08-16 14:41:24.997  1038  1120 D BluetoothManagerService: Message: 30
,08-16 14:41:25.002  6879  6879 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
08-16 14:41:25.004  6879  6879 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
08-16 14:41:25.011  1038  1381 D WifiOffDelayIfNotUsed: stopMonitoring
08-16 14:41:25.011  1038  1381 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-16 14:41:25.011  1038  1381 E WifiStateMachine: useWiFiOffloading() : false
08-16 14:41:25.011  1038  1381 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-16 14:41:25.015  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 14:41:25.016  1927  1927 D WfdsService: Supplicant Connection state is changed : false
08-16 14:41:25.016  1927  2284 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-16 14:41:25.016  1927  2284 D WfdsService: Set the WFDS Monitor: false
08-16 14:41:25.016  1927  2284 D WfdsMonitor: WFDS Monitor is stopped
08-16 14:41:25.017  1927  1927 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-16 14:41:25.019  2494  2494 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:41:25.019  1038  1038 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-16 14:41:25.020  1038  1428 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-16 14:41:25.021  1038  1428 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-16 14:41:25.022  6608  6608 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:41:25.023  6608  6608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 14:41:25.023  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:41:25.023  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 14:41:25.023  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 14:41:25.023  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 14:41:25.023  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 14:41:25.023  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 14:41:25.023  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 14:41:25.025  6608  6608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:41:25.026  6608  6608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 14:41:25.042  6879  6879 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
,08-16 14:41:25.045  6879  6879 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
08-16 14:41:25.054  6879  6879 D DockEventReceiver: finishStartingService: stopping service
,08-16 14:41:25.066  6879  6879 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-16 14:41:25.069  6879  6879 D BluetoothInputDevice: Proxy object connected
08-16 14:41:25.070  6879  6879 D HidProfile: Bluetooth service connected
,08-16 14:41:25.071  6879  6879 D BluetoothPan: BluetoothPAN Proxy object connected
08-16 14:41:25.073  6879  6879 D PanProfile: Bluetooth service connected
08-16 14:41:25.074  6879  6879 D BluetoothMap: Proxy object connected
08-16 14:41:25.074  6879  6879 D MapProfile: Bluetooth service connected
08-16 14:41:25.074  6879  6879 D BluetoothMap: getConnectedDevices()
08-16 14:41:25.075  6879  6879 D BluetoothMap: Bluetooth is Not enabled
08-16 14:41:25.075  6879  6879 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-16 14:41:25.077  6879  6879 D BluetoothPermissionRequest: onReceive
08-16 14:41:25.079  6879  6879 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-16 14:41:25.088  1038  1908 I ActivityManager: Killing 6278:com.android.defcontainer/u0a4 (adj 15): empty #17
08-16 14:41:25.089  6879  6879 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-16 14:41:25.120  3825  3825 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
,08-16 14:41:25.120  3825  3825 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-16 14:41:25.121  3825  3825 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-16 14:41:25.121  1038  1944 W libprocessgroup: failed to open /acct/uid_10004/pid_6278/cgroup.procs: No such file or directory
08-16 14:41:25.130  3825  3825 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-16 14:41:25.131  3825  3825 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-16 14:41:25.212  1038  2019 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6932 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,08-16 14:41:25.215  3825  3825 V BluetoothFtpService: Ftp Service onStartCommand
,08-16 14:41:25.215  3825  3825 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 14:41:25.216  3825  3825 V BluetoothFtpService: Ftp Service closeService
08-16 14:41:25.216  3825  3825 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-16 14:41:25.218  3825  3825 V BluetoothFtpService: successfully stopped ftp service
08-16 14:41:25.220  3825  3825 V BluetoothFtpService: Ftp Service onDestroy
08-16 14:41:25.220  3825  3825 V BluetoothFtpService: Ftp Service closeService
08-16 14:41:25.226  3825  3825 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-16 14:41:25.227  3825  3825 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-16 14:41:25.227  3825  3825 V BluetoothSapReceiver: SapReceiver onReceive 
08-16 14:41:25.227  3825  3825 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 14:41:25.227  3825  3825 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-16 14:41:25.227  3825  3825 V BluetoothSapReceiver: Calling SAP service start service with action = null
,08-16 14:41:25.232  3825  3825 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 14:41:25.232  3825  3825 V BluetoothSapService: state: 13
08-16 14:41:25.232  3825  3825 V BluetoothSapService: Stopping SAP server process
08-16 14:41:25.234  3825  3825 V BluetoothSapService: Sap Service closeSapService in
08-16 14:41:25.234  3825  3825 V BluetoothSapService: Close listen Socket : 
08-16 14:41:25.235  3825  3825 V BluetoothSapService: Close rfcomm Socket : 
08-16 14:41:25.235  3825  3825 V BluetoothSapService: Close sapd  Socket : 
08-16 14:41:25.237   351   351 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 467us total 25.138ms
08-16 14:41:25.259   351   351 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 441us total 21.206ms
,08-16 14:41:25.281   351   351 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 437us total 20.699ms
,08-16 14:41:25.330  1038  1945 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6949 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-16 14:41:25.334  3825  3825 V BluetoothSapService: Sap Service closeSapService out
08-16 14:41:25.334  3825  3825 V BluetoothSapService: Sap Service onDestroy
08-16 14:41:25.334  3825  3825 V BluetoothSapService: Sap Service closeSapService in
08-16 14:41:25.334  3825  3825 V BluetoothSapService: Close listen Socket : 
08-16 14:41:25.334  3825  3825 V BluetoothSapService: Close rfcomm Socket : 
08-16 14:41:25.335  3825  3825 V BluetoothSapService: Close sapd  Socket : 
08-16 14:41:25.340  3825  3825 V BluetoothSapService: Sap Service closeSapService out
,08-16 14:41:25.390  6932  6932 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-16 14:41:25.399  6949  6949 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-16 14:41:25.419  1038  1588 I ActivityManager: Killing 6477:com.google.android.partnersetup/u0a8 (adj 15): empty #17
,08-16 14:41:25.494  1038  2037 W libprocessgroup: failed to open /acct/uid_10008/pid_6477/cgroup.procs: No such file or directory
,08-16 14:41:25.499  6932  6932 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,08-16 14:41:25.553  6932  6932 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
08-16 14:41:25.553  6932  6932 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-16 14:41:25.554  6932  6932 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-16 14:41:25.554  6932  6932 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-16 14:41:25.554  6932  6932 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-16 14:41:25.557  6932  6932 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,08-16 14:41:25.564  6932  6932 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-16 14:41:25.574  6932  6932 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 14:41:25.575  3825  4015 I bt_lpm  : LPM is already off!!!
,08-16 14:41:25.576  3825  3906 D bt_hci_bdroid: cleanup
08-16 14:41:25.577  3825  4209 I bt_userial_mct: exiting userial_read_thread
08-16 14:41:25.577  3825  4209 D bt_userial_mct: Leaving userial_evt_read_thread()
08-16 14:41:25.579  3825  3906 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-16 14:41:25.579  3825  4012 W bt-btif : ag scb idx 1 not allocated
08-16 14:41:25.579  3825  4012 E bt-btif : BTA AG is already disabled, ignoring ...
08-16 14:41:25.580  3825  4012 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 14:41:25.580  3825  4015 I bt_vendor: hw_epilog_process
08-16 14:41:25.580  3825  4012 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 14:41:25.580  3825  4012 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 14:41:25.580  3825  4012 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 14:41:25.580  3825  4012 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 14:41:25.580  3825  4012 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 14:41:25.580  3825  4012 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 14:41:25.580  3825  4012 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 14:41:25.580  3825  4012 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 14:41:25.580  3825  4012 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 14:41:25.580  3825  4012 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 14:41:25.580  3825  3906 D bt_hci_bdroid: cleanup Finalizing cleanup
08-16 14:41:25.580  3825  4012 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 14:41:25.580  3825  3906 D bt_userial_mct: userial_close
08-16 14:41:25.581  3825  4012 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 14:41:25.581  3825  3906 E bt_userial_mct: pthread_join() FAILED result:3
08-16 14:41:25.581  3825  4012 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 14:41:25.581  3825  3906 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-16 14:41:25.581  3825  4012 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 14:41:25.581  3825  4012 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 14:41:25.581  3825  4012 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 14:41:25.581  3825  4012 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 14:41:25.581  3825  4012 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-16 14:41:25.582  6932  6932 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 14:41:25.611  6932  6932 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-16 14:41:25.613  6932  6932 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-16 14:41:25.615  6411  6411 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-16 14:41:25.619  6932  6932 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
,08-16 14:41:25.621  6899  6899 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-16 14:41:25.621  6899  6899 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-16 14:41:25.622  6899  6899 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-16 14:41:25.629  6879  6879 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 14:41:25.638  6879  6879 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 14:41:25.640  3825  3906 D bt_hci_bdroid: set_power 0
08-16 14:41:25.640  3825  3906 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-16 14:41:25.640  3825  3906 I bt_vendor: bluetooth satus is on
08-16 14:41:25.640  3825  3906 I bt_vendor: bt-vendor : resetting BT status
08-16 14:41:25.640  3825  3906 I bt_vendor: Starting hciattach daemon
,08-16 14:41:25.640  3825  3906 I bt_vendor: try to set false
08-16 14:41:25.641  3825  3906 I bt_vendor: Starting hciattach daemon
08-16 14:41:25.641  3825  3906 I bt_vendor: try to set false
08-16 14:41:25.642  3825  3906 I bt_vendor: cleanup
08-16 14:41:25.643  3825  4012 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
,08-16 14:41:25.644  3825  3906 I GKI_LINUX: GKI_exit_task 0 done
08-16 14:41:25.644  3825  3906 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-16 14:41:25.645  3825  3901 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-16 14:41:25.648  3825  3825 D HeadsetService: Received stop request...Stopping profile...
08-16 14:41:25.649  3825  3825 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-16 14:41:25.649  6932  6932 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 14:41:25.649  3825  3825 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-16 14:41:25.649  3825  3825 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@34bdf0fb
08-16 14:41:25.650  3825  3934 D HeadsetStateMachine: Exit Disconnected: -1
08-16 14:41:25.651  1839  1839 D BluetoothHeadset: Proxy object disconnected
08-16 14:41:25.651  1839  1839 D BluetoothHeadset: Proxy object disconnected
08-16 14:41:25.652  1839  1839 D BluetoothHeadset: Proxy object disconnected
08-16 14:41:25.652  1038  1038 D BluetoothHeadset: Proxy object disconnected
08-16 14:41:25.652  1038  1038 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-16 14:41:25.652  3825  3825 D A2dpService: Received stop request...Stopping profile...
,08-16 14:41:25.653  3825  3971 D A2dpStateMachine: Exit Disconnected: -1
08-16 14:41:25.653  6932  6932 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-16 14:41:25.655  3825  3825 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-16 14:41:25.655  6932  6932 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-16 14:41:25.659  6411  6411 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-16 14:41:25.664  6899  6899 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,08-16 14:41:25.664  6899  6899 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-16 14:41:25.665  6899  6899 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-16 14:41:25.666  3825  3825 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-16 14:41:25.666  3825  3901 D BluetoothAdapterState: Stopping profile services that were post enabled
08-16 14:41:25.666  3825  3825 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-16 14:41:25.666  3825  3825 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@34bdf0fb
08-16 14:41:25.669  6879  6879 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-16 14:41:25.670  1038  1038 D BluetoothA2dp: Proxy object disconnected
08-16 14:41:25.670  1038  1038 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-16 14:41:25.671  3825  3825 D HeadsetStateMachine: Unbinding service...
,08-16 14:41:25.672  3825  3825 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-16 14:41:25.672  3825  3825 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
,08-16 14:41:25.672  3825  3825 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-16 14:41:25.672  3825  3825 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-16 14:41:25.672  3825  3825 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-16 14:41:25.672  3825  3825 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-16 14:41:25.672  3825  3825 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-16 14:41:25.673  3825  3825 D HidService: Received stop request...Stopping profile...
08-16 14:41:25.673  3825  3825 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@34bdf0fb
08-16 14:41:25.675  3825  3825 D HealthService: Received stop request...Stopping profile...
08-16 14:41:25.675  3825  3825 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@34bdf0fb
08-16 14:41:25.676  3825  3825 D PanService: Received stop request...Stopping profile...
08-16 14:41:25.677  3825  3825 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@34bdf0fb
08-16 14:41:25.678  3825  3825 D BtGatt.DebugUtils: handleDebugAction() action=null
08-16 14:41:25.678  3825  3825 D BtGatt.GattService: Received stop request...Stopping profile...
08-16 14:41:25.678  3825  3825 D BtGatt.GattService: stop()
08-16 14:41:25.678  3825  3825 D BtGatt.AdvertiseManager: advertise clients cleared
08-16 14:41:25.679  3825  3825 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@34bdf0fb
08-16 14:41:25.681  3825  3825 D BluetoothMapService: Received stop request...Stopping profile...
08-16 14:41:25.681  3825  3825 D BluetoothMapService: stop()
08-16 14:41:25.681  3825  3825 D BluetoothMapEmailAppObserver: deinitObservers()
08-16 14:41:25.682  3825  3825 D BluetoothMapEmailAppObserver: removeReceiver()
08-16 14:41:25.683  3825  3825 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@34bdf0fb
,08-16 14:41:25.686  3825  3825 I BluetoothA2dpServiceJni: cleanupNative
,08-16 14:41:25.686  3825  3972 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-16 14:41:25.686  6879  6879 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 14:41:25.687  3825  3825 I GKI_LINUX: GKI_exit_task 2 done
08-16 14:41:25.687  3825  3825 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-16 14:41:25.687  3825  3825 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-16 14:41:25.687  3825  3825 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-16 14:41:25.687  3825  3825 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-16 14:41:25.688  3825  3825 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-16 14:41:25.688  3825  3825 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-16 14:41:25.688  3825  3825 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-16 14:41:25.688  3825  3825 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-16 14:41:25.689  6879  6879 D BluetoothInputDevice: Proxy object disconnected
08-16 14:41:25.689  3825  3825 V BluetoothMapService: Handler(): got msg=4
08-16 14:41:25.689  3825  3825 D BluetoothMapService: MAP Service closeService in
08-16 14:41:25.689  3825  3825 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-16 14:41:25.689  6879  6879 D HidProfile: Bluetooth service disconnected
08-16 14:41:25.689  3825  3825 V BluetoothMapService: MAP Service closeService out
08-16 14:41:25.689  6879  6879 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-16 14:41:25.689  6879  6879 D PanProfile: Bluetooth service disconnected
08-16 14:41:25.689  6879  6879 D BluetoothMap: Proxy object disconnected
08-16 14:41:25.689  6879  6879 D MapProfile: Bluetooth service disconnected
08-16 14:41:25.690  3825  3901 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-16 14:41:25.690  3825  3901 D BluetoothAdapterProperties: Setting state to 10
08-16 14:41:25.690  3825  3901 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-16 14:41:25.690  3825  3825 D BluetoothMapService: cleanup()
08-16 14:41:25.690  3825  3825 D BluetoothMapService: MAP Service closeService in
08-16 14:41:25.690  3825  3825 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-16 14:41:25.690  3825  3825 V BluetoothMapService: MAP Service closeService out
08-16 14:41:25.690  1038  1120 D BluetoothManagerService: Message: 60
08-16 14:41:25.690  1038  1120 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-16 14:41:25.691  1038  1120 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
08-16 14:41:25.691  3825  3901 I BluetoothAdapterState: Entering OffState
08-16 14:41:25.691  1839  1855 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 14:41:25.696  6932  6932 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 14:41:25.697  6932  6932 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-16 14:41:25.699  6879  6895 D BluetoothPan: onBluetoothStateChange on: false
08-16 14:41:25.699  1038  1120 D BluetoothA2dp: onBluetoothStateChange: up=false
08-16 14:41:25.700  1839  1854 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 14:41:25.700  6932  6932 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-16 14:41:25.701  1839  3938 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 14:41:25.701  1038  1120 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 14:41:25.766  1038  1945 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6976 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-16 14:41:25.768  6879  6896 D BluetoothPbap: onBluetoothStateChange: up=false
08-16 14:41:25.769  6879  6895 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-16 14:41:25.769  6879  6896 D BluetoothMap: onBluetoothStateChange: up=false
08-16 14:41:25.771  1038  1120 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-16 14:41:25.771  1038  1120 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-16 14:41:25.775  1038  1120 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-16 14:41:25.775  1038  1120 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-16 14:41:25.775  1038  1120 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@17950aed mBinding = false
08-16 14:41:25.776  1038  1120 D BluetoothManagerService: Sending unbind request.
08-16 14:41:25.780  1038  1120 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
,08-16 14:41:25.785  1589  1589 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-16 14:41:25.789  1927  1927 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-16 14:41:25.789  1927  2129 D LGBluetoothAPIService: Message: 2
08-16 14:41:25.790  3825  3906 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-16 14:41:25.790  3825  3825 I GKI_LINUX: GKI_exit_task 1 done
08-16 14:41:25.790  3825  3825 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-16 14:41:25.790  1927  2129 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@20b63c5a mBinding = false
08-16 14:41:25.791  3825  3825 I BluetoothServiceJni: cleanupNative: return from cleanup
08-16 14:41:25.791  3825  3825 I art     : --- WEIRD: removing null entry 246
08-16 14:41:25.791  3825  3825 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
08-16 14:41:25.791  3825  3825 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-16 14:41:25.792  6608  6608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:41:25.792  1927  2129 D LGBluetoothAPIService: Sending unbind request.
08-16 14:41:25.792  6608  6608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:41:25.793  6608  6608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:41:25.794  1589  1589 D BluetoothAdapter: 388559202: getState() :  mService = null. Returning STATE_OFF
08-16 14:41:25.794  1589  1589 D BluetoothAdapter: 388559202: getState() :  mService = null. Returning STATE_OFF
08-16 14:41:25.794  6879  6879 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,08-16 14:41:25.795  6879  6879 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-16 14:41:25.795  6879  6879 D LGBluetoothEventManager: [BTUI] clear device connection state
08-16 14:41:25.799  3825  3825 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-16 14:41:25.802  3825  3825 I art     : System.exit called, status: 0
08-16 14:41:25.802  3825  3825 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-16 14:41:25.802  6879  6879 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-16 14:41:25.811  6879  6879 D DockEventReceiver: finishStartingService: stopping service
,08-16 14:41:25.822   325  1385 V AudioFlinger: 3825 died, releasing its sessions
08-16 14:41:25.822   325  1385 V AudioFlinger:  pid 1839 @ 0
08-16 14:41:25.822   325  1385 V AudioFlinger:  pid 3346 @ 1
08-16 14:41:25.822   325  1385 V AudioFlinger:  pid 3346 @ 2
08-16 14:41:25.823  6879  6879 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-16 14:41:25.841  1038  2018 I ActivityManager: Process com.android.bluetooth (pid 3825) has died
08-16 14:41:25.841  1038  2018 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
,08-16 14:41:25.846  2178  2178 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-16 14:41:25.856  6879  6879 D BluetoothPermissionRequest: onReceive
,08-16 14:41:25.859  6879  6879 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-16 14:41:25.859  6879  6879 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-16 14:41:25.866  6879  6879 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-16 14:41:25.867  6899  6899 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-16 14:41:25.915  1038  2019 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=6999 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-16 14:41:25.924  6976  6997 W FormManager: Network not available. Please check & try again.
08-16 14:41:25.928  6879  6879 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-16 14:41:25.937  6879  6879 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 14:41:25.940  6976  6998 V FormManager: Network unavailable.
08-16 14:41:25.943  6976  6998 V FormManager: Network unavailable.
,08-16 14:41:25.960  1038  1890 I ActivityManager: Killing 5938:com.lge.appbox.client/u0a11 (adj 15): empty #17
,08-16 14:41:25.994  1038  1588 W libprocessgroup: failed to open /acct/uid_10011/pid_5938/cgroup.procs: No such file or directory
,08-16 14:41:26.000  6879  6879 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
,08-16 14:41:26.001  6879  6879 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-16 14:41:26.001  6879  6879 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-16 14:41:26.001  6879  6879 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-16 14:41:26.014  6879  6879 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,08-16 14:41:26.038  6879  6879 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-16 14:41:26.039  6879  6879 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
,08-16 14:41:26.039  6879  6879 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-16 14:41:26.039  6879  6879 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-16 14:41:26.040  6879  6879 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-16 14:41:26.040  6999  6999 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-16 14:41:26.040  6999  6999 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-16 14:41:26.041  6999  6999 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-16 14:41:26.042  6999  6999 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-16 14:41:26.042  6879  6879 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,08-16 14:41:26.050  4286  4286 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-16 14:41:26.051  4286  4286 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-16 14:41:26.054  4286  4286 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-16 14:41:26.059  4286  4286 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-16 14:41:26.063  6999  6999 D BluetoothAdapterApp: Loading JNI Library
08-16 14:41:26.070  4286  7018 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-16 14:41:26.079  6899  6899 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-16 14:41:26.080  6899  6899 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-16 14:41:26.080  6899  6899 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-16 14:41:26.086  4286  7019 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
,08-16 14:41:26.086  4286  7019 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-16 14:41:26.091  6879  6879 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-16 14:41:26.102  6999  6999 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@3ccfb600 Instance Count = 1
,08-16 14:41:26.108  6976  7021 W FormManager: Network not available. Please check & try again.
08-16 14:41:26.108  6999  6999 D BluetoothAdapterApp: onCreate
08-16 14:41:26.113  6879  6879 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-16 14:41:26.115  6976  7022 V FormManager: Network unavailable.
08-16 14:41:26.124  6976  7022 V FormManager: Network unavailable.
,08-16 14:41:26.140  6932  6932 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,08-16 14:41:26.141  6932  6932 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-16 14:41:26.141  6999  6999 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-16 14:41:26.142  6932  6932 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
08-16 14:41:26.142  6999  6999 D ProfileConfigQcom: Adding HeadsetService
08-16 14:41:26.142  6999  6999 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-16 14:41:26.142  6999  6999 D ProfileConfigQcom: Adding A2dpService
08-16 14:41:26.142  6999  6999 D ProfileConfigQcom: [BTUI] HidService is supported
08-16 14:41:26.142  6999  6999 D ProfileConfigQcom: Adding HidService
08-16 14:41:26.143  6999  6999 D ProfileConfigQcom: [BTUI] HealthService is supported
08-16 14:41:26.143  6999  6999 D ProfileConfigQcom: Adding HealthService
08-16 14:41:26.143  6999  6999 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-16 14:41:26.144  6999  6999 D ProfileConfigQcom: [BTUI] PanService is supported
08-16 14:41:26.144  6999  6999 D ProfileConfigQcom: Adding PanService
08-16 14:41:26.144  6999  6999 D ProfileConfigQcom: [BTUI] GattService is supported
08-16 14:41:26.144  6999  6999 D ProfileConfigQcom: Adding GattService
08-16 14:41:26.145  6999  6999 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-16 14:41:26.145  6999  6999 D ProfileConfigQcom: Adding BluetoothMapService
08-16 14:41:26.145  6999  6999 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-16 14:41:26.147  6999  6999 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-16 14:41:26.152  6879  6879 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
,08-16 14:41:26.154  6999  6999 V LGMDMManagerInternal: Create singleton instance
08-16 14:41:26.181  6932  6932 D LgDataFeature: LgDataFeature() Constructor: none
08-16 14:41:26.181  6932  6932 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 14:41:26.190  6932  6932 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
08-16 14:41:26.191  6932  6932 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-16 14:41:26.191  6932  6932 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-16 14:41:26.191  6932  6932 V SoundPool: doLoad: loading sample sampleID=1
08-16 14:41:26.192  6932  6932 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-16 14:41:26.196  6932  7026 V SoundPool: Start decode
,08-16 14:41:26.196  6932  7026 V MediaPlayer[Native]: decode(31, 10857164, 17813)
08-16 14:41:26.196  6724  6724 D UEI.SmartControl: QS Service created
08-16 14:41:26.198   325  1384 V MediaPlayerService: decode(23, 10857164, 17813)
08-16 14:41:26.198   325  1384 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-16 14:41:26.198   325  1384 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-16 14:41:26.198   325  1384 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-16 14:41:26.198   325  1384 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-16 14:41:26.198   325  1384 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-16 14:41:26.198   325  1384 V MediaPlayerService: player type = 3
08-16 14:41:26.198   325  1384 V AwesomePlayer: AwesomePlayer create()
08-16 14:41:26.199   325  1384 V AwesomePlayer: reset_l() 
08-16 14:41:26.199   325  1384 V AwesomePlayer: cancelPlayerEvents
08-16 14:41:26.199   325  1384 V AwesomePlayer: setAudioSink() 
08-16 14:41:26.199   325  1384 V AwesomePlayer: reset_l() 
08-16 14:41:26.199   325  1384 V AudioCache: notify(0xb16a6940, 8, 0, 0)
08-16 14:41:26.199   325  1384 V AudioCache: ignored
08-16 14:41:26.199   325  1384 V AwesomePlayer: cancelPlayerEvents
08-16 14:41:26.199   325  1384 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
08-16 14:41:26.199   325  1384 V AwesomePlayer: setDataSource_l dataSource
08-16 14:41:26.199   325  1384 V LGParserOSAL: SniffLGParser start
08-16 14:41:26.199   325  1384 V LGParserOSAL: MainType:5, SubType=0
08-16 14:41:26.199   325  1384 V LGParserOSAL: #### check Mime : application/ogg
08-16 14:41:26.199   325  1384 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-16 14:41:26.199   325  1384 E MediaExtractor: Use LGExtractor :application/ogg 
08-16 14:41:26.201  6932  6932 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-16 14:41:26.207  6932  6932 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-16 14:41:26.208  6932  6932 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
,08-16 14:41:26.212  6724  6724 I UEI.SmartControl: Service initServices...
08-16 14:41:26.212  6724  6724 D UEI.SmartControl: QS start get config
08-16 14:41:26.231  6932  6932 V LGMDMManager: Create singleton instance
,08-16 14:41:26.241   325  1384 V LGParserOSAL: supported mime: application/ogg
08-16 14:41:26.241   325  1384 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-16 14:41:26.241   325  1384 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-16 14:41:26.241   325  1384 V AwesomePlayer: mBitrate = -1 bits/sec
08-16 14:41:26.241   325  1384 V AwesomePlayer: AudioTrack Setting
08-16 14:41:26.241   325  1384 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-16 14:41:26.241   325  1384 V AwesomePlayer: setAudioSource() 
08-16 14:41:26.241   325  1384 V MediaPlayerService: prepare
08-16 14:41:26.241   325  1384 V AwesomePlayer: prepareAsync_l() 
08-16 14:41:26.241   325  1384 V MediaPlayerService: wait for prepare
08-16 14:41:26.241   325  7027 V AwesomePlayer: onPrepareAsyncEvent() 
08-16 14:41:26.242   325  7027 V AwesomePlayer: initAudioDecoder() 
08-16 14:41:26.242   325  7027 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-16 14:41:26.242   325  7027 V AudioSystem: isOffloadSupported()
08-16 14:41:26.242   325  7027 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-16 14:41:26.242   325  7027 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-16 14:41:26.242   325  7027 I AudioFlinger: isAudioPlaybackHookOn() false
08-16 14:41:26.242   325  7027 V AwesomePlayer: getUseOffload() = 0 
08-16 14:41:26.242   325  7027 V OMXCodec: OMXCodec::Create
08-16 14:41:26.242   325  7027 V OMXCodec: findMatchingCodecs()
08-16 14:41:26.242   325  7027 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-16 14:41:26.242   325  7027 V OMXCodec: matchingCodecs.size()=1
08-16 14:41:26.242   325  7027 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
08-16 14:41:26.244   325  7027 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-16 14:41:26.244   325  7027 V LGCodecAdapter: LG Codec Adapter start
08-16 14:41:26.244   325  7027 V OMXCodec: OMXCodec Createtor
08-16 14:41:26.244   325  7027 V OMXCodec: setComponentRole
08-16 14:41:26.244   325  7027 V OMXCodec: configureCodec protected=0
08-16 14:41:26.244   325  7027 V LGCodecAdapter: called getLGCodecSpecificData
08-16 14:41:26.244   325  7027 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-16 14:41:26.244   325  7027 V LGCodecOSAL: Called LGconfigureCodecMETA
08-16 14:41:26.244   325  7027 V LGCodecOSAL: Called LGconfigureCodecMSG
08-16 14:41:26.244   325  7027 V LGCodecOSAL: Not support LGCodec
08-16 14:41:26.244   325  7027 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-16 14:41:26.244   325  7027 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-16 14:41:26.244   325  7027 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-16 14:41:26.244   325  7027 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-16 14:41:26.244   325  7027 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-16 14:41:26.244   325  7027 V AudioSystem: isOffloadSupported()
,08-16 14:41:26.244   325  7027 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-16 14:41:26.244   325  7027 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-16 14:41:26.244   325  7027 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-16 14:41:26.244   325  7027 V OMXCodec: init()
08-16 14:41:26.244   325  7027 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-16 14:41:26.244   325  7027 V OMXCodec: allocateBuffers
08-16 14:41:26.244   325  7027 V OMXCodec: allocateBuffersOnPort portIndex=0
08-16 14:41:26.244   325  7027 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-16 14:41:26.245   325  7027 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f76a0 on input port
08-16 14:41:26.245   325  7027 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7790 on input port
08-16 14:41:26.245   325  7027 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7920 on input port
08-16 14:41:26.245   325  7027 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f79c0 on input port
08-16 14:41:26.245   325  7027 V OMXCodec: allocateBuffersOnPort portIndex=1
08-16 14:41:26.245   325  7027 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-16 14:41:26.245   325  7027 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a10 on output port
08-16 14:41:26.245   325  7027 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on output port
08-16 14:41:26.245   325  7027 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b00 on output port
08-16 14:41:26.245   325  7027 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7f60 on output port
08-16 14:41:26.245   325  7027 V OMXCodec: init() mAsyncCompletion wait!!! 
08-16 14:41:26.245   325  7029 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-16 14:41:26.245   325  7029 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-16 14:41:26.245   325  7029 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-16 14:41:26.245   325  7027 V OMXCodec: init() mAsyncCompletion wait!!! 
08-16 14:41:26.245   325  7029 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-16 14:41:26.245   325  7029 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-16 14:41:26.245   325  7029 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-16 14:41:26.245   325  7027 V OMXCodec: init() mAsyncCompletion wait free! 
08-16 14:41:26.245   325  7027 V AwesomePlayer: finishAsyncPrepare_l() 
08-16 14:41:26.245   325  7027 V AudioCache: notify(0xb16a6940, 5, 0, 0)
08-16 14:41:26.245   325  7027 V AudioCache: ignored
08-16 14:41:26.245   325  7027 V AudioCache: notify(0xb16a6940, 1, 0, 0)
,08-16 14:41:26.245   325  7027 V AudioCache: prepared
08-16 14:41:26.246   325  1384 V AudioCache: wait - success
08-16 14:41:26.246   325  1384 V MediaPlayerService: start
08-16 14:41:26.246   325  1384 V AwesomePlayer: play_l() 
08-16 14:41:26.246   325  1384 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-16 14:41:26.246   325  1384 V AwesomePlayer: createAudioPlayer_l
08-16 14:41:26.246   325  1384 V AwesomePlayer: seekAudioIfNecessary_l() 
,08-16 14:41:26.246   325  1384 V AwesomePlayer: startAudioPlayer_l() 
08-16 14:41:26.246   325  1384 D AudioPlayer: start of Playback, useOffload 0
08-16 14:41:26.246   325  1384 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-16 14:41:26.246   325  1384 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-16 14:41:26.247   325  7029 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-16 14:41:26.247   325  7029 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1),
08-16 14:41:26.247   325  7029 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-16 14:41:26.247   325  7029 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-16 14:41:26.247   325  7029 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-16 14:41:26.247   325  7029 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-16 14:41:26.248   325  7029 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884688
08-16 14:41:26.248   325  7029 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
,08-16 14:41:26.248   325  7029 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884848
08-16 14:41:26.248   325  7029 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-16 14:41:26.248   325  7029 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884928
08-16 14:41:26.248   325  7029 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-16 14:41:26.248   325  7029 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041886048
08-16 14:41:26.248   325  7029 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
,08-16 14:41:26.248   325  7029 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-16 14:41:26.248   325  7029 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-16 14:41:26.248   325  7029 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-16 14:41:26.248   325  7029 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-16 14:41:26.248   325  7029 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-16 14:41:26.248   325  7029 V OMXCodec: allocateBuffersOnPort portIndex=1
,08-16 14:41:26.248   325  7029 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-16 14:41:26.249   325  7029 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b00 on output port
08-16 14:41:26.249   325  7029 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on output port
08-16 14:41:26.249   325  7029 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a10 on output port
08-16 14:41:26.249   325  7029 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57f73d0 on output port
08-16 14:41:26.249   325  7029 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
,08-16 14:41:26.249   325  7029 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-16 14:41:26.249   325  1384 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-16 14:41:26.249   325  1384 V AudioCache: notify(0xb16a6940, 6, 0, 0)
08-16 14:41:26.249   325  1384 V AudioCache: ignored
08-16 14:41:26.250   325  1384 V MediaPlayerService: wait for playback complete
08-16 14:41:26.251   325  7030 V AudioCache: write(0xb1786000, 4096)
08-16 14:41:26.251   325  7030 V AudioCache: memcpy(0xac300000, 0xb1786000, 4096)
08-16 14:41:26.252   325  7030 V AudioCache: write(0xb1786000, 4096),
08-16 14:41:26.252   325  7030 V AudioCache: memcpy(0xac301000, 0xb1786000, 4096)
08-16 14:41:26.252   325  7030 V AudioCache: write(0xb1786000, 4096)
08-16 14:41:26.252   325  7030 V AudioCache: memcpy(0xac302000, 0xb1786000, 4096)
08-16 14:41:26.253   325  7030 V AudioCache: write(0xb1786000, 4096)
08-16 14:41:26.253   325  7030 V AudioCache: memcpy(0xac303000, 0xb1786000, 4096)
08-16 14:41:26.253   325  7030 V AudioCache: write(0xb1786000, 4096),
08-16 14:41:26.253   325  7030 V AudioCache: memcpy(0xac304000, 0xb1786000, 4096)
08-16 14:41:26.254   325  7030 V AudioCache: write(0xb1786000, 4096)
08-16 14:41:26.254   325  7030 V AudioCache: memcpy(0xac305000, 0xb1786000, 4096)
08-16 14:41:26.254   325  7030 V AudioCache: write(0xb1786000, 4096)
08-16 14:41:26.254   325  7030 V AudioCache: memcpy(0xac306000, 0xb1786000, 4096)
08-16 14:41:26.255   325  7030 V AudioCache: write(0xb1786000, 4096)
,08-16 14:41:26.255   325  7030 V AudioCache: memcpy(0xac307000, 0xb1786000, 4096)
08-16 14:41:26.255   325  7030 V AudioCache: write(0xb1786000, 4096)
08-16 14:41:26.255   325  7030 V AudioCache: memcpy(0xac308000, 0xb1786000, 4096)
08-16 14:41:26.256   325  7030 V AudioCache: write(0xb1786000, 4096)
08-16 14:41:26.256   325  7030 V AudioCache: memcpy(0xac309000, 0xb1786000, 4096)
08-16 14:41:26.256   325  7030 V AudioCache: write(0xb1786000, 4096)
,08-16 14:41:26.256   325  7030 V AudioCache: memcpy(0xac30a000, 0xb1786000, 4096)
08-16 14:41:26.257   325  7030 V AudioCache: write(0xb1786000, 4096)
08-16 14:41:26.257   325  7030 V AudioCache: memcpy(0xac30b000, 0xb1786000, 4096)
08-16 14:41:26.257   325  7030 V AudioCache: write(0xb1786000, 4096)
08-16 14:41:26.257   325  7030 V AudioCache: memcpy(0xac30c000, 0xb1786000, 4096)
08-16 14:41:26.257   325  7030 V AudioCache: write(0xb1786000, 4096)
08-16 14:41:26.257   325  7030 V AudioCache: memcpy(0xac30d000, 0xb1786000, 4096),
08-16 14:41:26.258   325  7030 V AudioCache: write(0xb1786000, 4096)
08-16 14:41:26.258   325  7030 V AudioCache: memcpy(0xac30e000, 0xb1786000, 4096)
08-16 14:41:26.258  6999  6999 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-16 14:41:26.258   325  7030 V AudioCache: write(0xb1786000, 4096)
08-16 14:41:26.258   325  7030 V AudioCache: memcpy(0xac30f000, 0xb1786000, 4096)
08-16 14:41:26.259   325  7030 V AudioCache: write(0xb1786000, 4096)
,08-16 14:41:26.259   325  7030 V AudioCache: memcpy(0xac310000, 0xb1786000, 4096)
08-16 14:41:26.259   325  7030 V AudioCache: write(0xb1786000, 4096)
08-16 14:41:26.259   325  7030 V AudioCache: memcpy(0xac311000, 0xb1786000, 4096)
08-16 14:41:26.262  6999  6999 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-16 14:41:26.262   325  7030 V AudioCache: write(0xb1786000, 4096)
08-16 14:41:26.262   325  7030 V AudioCache: memcpy(0xac312000, 0xb1786000, 4096)
,08-16 14:41:26.262  6999  6999 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-16 14:41:26.263  6999  6999 V BluetoothSapReceiver: SapReceiver onReceive 
08-16 14:41:26.263   325  7030 V AudioCache: write(0xb1786000, 4096)
08-16 14:41:26.263   325  7030 V AudioCache: memcpy(0xac313000, 0xb1786000, 4096)
08-16 14:41:26.263   325  7030 V AudioCache: write(0xb1786000, 4096)
08-16 14:41:26.263   325  7030 V AudioCache: memcpy(0xac314000, 0xb1786000, 4096)
08-16 14:41:26.264   325  7030 V AudioCache: write(0xb1786000, 4096)
,08-16 14:41:26.264   325  7030 V AudioCache: memcpy(0xac315000, 0xb1786000, 4096)
08-16 14:41:26.264  6999  6999 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 14:41:26.264  6999  6999 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-16 14:41:26.264   325  7030 V AudioCache: write(0xb1786000, 4096)
08-16 14:41:26.264   325  7030 V AudioCache: memcpy(0xac316000, 0xb1786000, 4096)
08-16 14:41:26.265   325  7030 V AudioCache: write(0xb1786000, 4096)
,08-16 14:41:26.265   325  7030 V AudioCache: memcpy(0xac317000, 0xb1786000, 4096)
08-16 14:41:26.265   325  7030 V AudioCache: write(0xb1786000, 4096)
08-16 14:41:26.265   325  7030 V AudioCache: memcpy(0xac318000, 0xb1786000, 4096)
08-16 14:41:26.265   325  7030 V AudioCache: write(0xb1786000, 4096)
08-16 14:41:26.265   325  7030 V AudioCache: memcpy(0xac319000, 0xb1786000, 4096)
08-16 14:41:26.266   325  7030 V AudioCache: write(0xb1786000, 4096)
,08-16 14:41:26.266   325  7030 V AudioCache: memcpy(0xac31a000, 0xb1786000, 4096)
08-16 14:41:26.266   325  7030 V AudioCache: write(0xb1786000, 4096)
08-16 14:41:26.266   325  7030 V AudioCache: memcpy(0xac31b000, 0xb1786000, 4096)
08-16 14:41:26.267   325  7030 V AudioCache: write(0xb1786000, 4096)
08-16 14:41:26.267   325  7030 V AudioCache: memcpy(0xac31c000, 0xb1786000, 4096)
,08-16 14:41:26.267   325  7030 V AudioCache: write(0xb1786000, 4096),
08-16 14:41:26.267   325  7030 V AudioCache: memcpy(0xac31d000, 0xb1786000, 4096)
08-16 14:41:26.268   325  7030 V AudioCache: write(0xb1786000, 4096)
08-16 14:41:26.268   325  7030 V AudioCache: memcpy(0xac31e000, 0xb1786000, 4096)
08-16 14:41:26.268   325  7030 V AudioCache: write(0xb1786000, 4096)
08-16 14:41:26.268   325  7030 V AudioCache: memcpy(0xac31f000, 0xb1786000, 4096)
08-16 14:41:26.269   325  7030 V AudioCache: write(0xb1786000, 4096)
,08-16 14:41:26.269   325  7030 V AudioCache: memcpy(0xac320000, 0xb1786000, 4096)
08-16 14:41:26.269   325  7030 V AudioCache: write(0xb1786000, 4096)
08-16 14:41:26.269   325  7030 V AudioCache: memcpy(0xac321000, 0xb1786000, 4096)
08-16 14:41:26.270   325  7030 V AudioCache: write(0xb1786000, 4096)
08-16 14:41:26.270   325  7030 V AudioCache: memcpy(0xac322000, 0xb1786000, 4096)
08-16 14:41:26.270   325  7030 V AudioCache: write(0xb1786000, 4096)
,08-16 14:41:26.270   325  7030 V AudioCache: memcpy(0xac323000, 0xb1786000, 4096)
08-16 14:41:26.271   325  7030 V AudioCache: write(0xb1786000, 4096)
08-16 14:41:26.271   325  7030 V AudioCache: memcpy(0xac324000, 0xb1786000, 4096)
08-16 14:41:26.271   325  7030 V AudioCache: write(0xb1786000, 4096)
08-16 14:41:26.271   325  7030 V AudioCache: memcpy(0xac325000, 0xb1786000, 4096)
08-16 14:41:26.272   325  7030 V AudioCache: write(0xb1786000, 4096),
08-16 14:41:26.272   325  7030 V AudioCache: memcpy(0xac326000, 0xb1786000, 4096)
08-16 14:41:26.272   325  7030 V AudioCache: write(0xb1786000, 4096)
08-16 14:41:26.272   325  7030 V AudioCache: memcpy(0xac327000, 0xb1786000, 4096)
08-16 14:41:26.273   325  7030 V AudioCache: write(0xb1786000, 4096)
08-16 14:41:26.273   325  7030 V AudioCache: memcpy(0xac328000, 0xb1786000, 4096)
08-16 14:41:26.273  6949  6949 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings,
08-16 14:41:26.273   325  7030 V AudioCache: write(0xb1786000, 4096)
08-16 14:41:26.273   325  7030 V AudioCache: memcpy(0xac329000, 0xb1786000, 4096)
08-16 14:41:26.273   325  7030 V AudioCache: write(0xb1786000, 4096)
08-16 14:41:26.273   325  7030 V AudioCache: memcpy(0xac32a000, 0xb1786000, 4096)
08-16 14:41:26.274   325  7030 V AudioCache: write(0xb1786000, 4096)
08-16 14:41:26.274   325  7030 V AudioCache: memcpy(0xac32b000, 0xb1786000, 4096)
,08-16 14:41:26.274   325  7030 V AudioCache: write(0xb1786000, 4096)
08-16 14:41:26.274   325  7030 V AudioCache: memcpy(0xac32c000, 0xb1786000, 4096)
08-16 14:41:26.275   325  7030 V AudioCache: write(0xb1786000, 4096)
08-16 14:41:26.275   325  7030 V AudioCache: memcpy(0xac32d000, 0xb1786000, 4096)
08-16 14:41:26.275   325  7030 V AudioCache: write(0xb1786000, 4096)
08-16 14:41:26.275   325  7030 V AudioCache: memcpy(0xac32e000, 0xb1786000, 4096)
,08-16 14:41:26.277   325  7030 V AudioCache: write(0xb1786000, 4096)
08-16 14:41:26.277   325  7030 V AudioCache: memcpy(0xac32f000, 0xb1786000, 4096)
08-16 14:41:26.277   325  7030 V AudioCache: write(0xb1786000, 4096)
08-16 14:41:26.277   325  7030 V AudioCache: memcpy(0xac330000, 0xb1786000, 4096)
08-16 14:41:26.277   325  7030 V AudioCache: write(0xb1786000, 4096)
08-16 14:41:26.277   325  7030 V AudioCache: memcpy(0xac331000, 0xb1786000, 4096)
,08-16 14:41:26.278   325  7029 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-16 14:41:26.278   325  7030 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-16 14:41:26.278   325  7030 V AwesomePlayer: postAudioEOS() 
08-16 14:41:26.278   325  7030 V AudioCache: write(0xb1786000, 280)
08-16 14:41:26.278   325  7030 V AudioCache: memcpy(0xac332000, 0xb1786000, 280)
08-16 14:41:26.280   325  7027 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
,08-16 14:41:26.280   325  7027 V AwesomePlayer: onStreamDone
08-16 14:41:26.280   325  7027 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-16 14:41:26.280   325  7027 V AudioCache: notify(0xb16a6940, 2, 0, 0)
08-16 14:41:26.280   325  7027 V AudioCache: playback complete
08-16 14:41:26.280   325  7027 V AwesomePlayer: pause_l() 
08-16 14:41:26.280   325  7027 V AudioCache: notify(0xb16a6940, 7, 0, 0)
,08-16 14:41:26.280   325  7027 V AudioCache: ignored
08-16 14:41:26.280   325  7027 V AwesomePlayer: cancelPlayerEvents
08-16 14:41:26.280   325  1384 V AudioCache: wait - success
08-16 14:41:26.280   325  1384 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-16 14:41:26.280   325  7027 D AudioPlayer: Pause Playback at 1068125
08-16 14:41:26.280   325  1384 V AwesomePlayer: reset_l() 
,08-16 14:41:26.280   325  1384 V AudioCache: notify(0xb16a6940, 8, 0, 0)
08-16 14:41:26.280   325  1384 V AudioCache: ignored
08-16 14:41:26.280   325  1384 V AwesomePlayer: cancelPlayerEvents
08-16 14:41:26.280   325  1384 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-16 14:41:26.280   325  1384 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-16 14:41:26.280   325  1384 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-16 14:41:26.280   325  1384 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
,08-16 14:41:26.280   325  1384 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-16 14:41:26.281   325  7029 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-16 14:41:26.281   325  7029 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-16 14:41:26.281   325  7029 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-16 14:41:26.281   325  7029 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f79c0 on port 0
,08-16 14:41:26.281   325  7029 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-16 14:41:26.281   325  7029 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7920 on port 0
08-16 14:41:26.281   325  7029 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-16 14:41:26.281   325  7029 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7790 on port 0
08-16 14:41:26.281   325  7029 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-16 14:41:26.281   325  7029 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f76a0 on port 0
,08-16 14:41:26.281   325  7029 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-16 14:41:26.281   325  7029 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-16 14:41:26.281   325  7029 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb57f73d0 on port 1
08-16 14:41:26.281   325  7029 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-16 14:41:26.281   325  7029 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a10 on port 1
08-16 14:41:26.281   325  7029 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
,08-16 14:41:26.281   325  7029 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ab0 on port 1
08-16 14:41:26.281   325  7029 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-16 14:41:26.281   325  7029 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b00 on port 1
08-16 14:41:26.281   325  7029 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-16 14:41:26.281   325  7029 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-16 14:41:26.281   325  1384 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
,08-16 14:41:26.281   325  1384 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-16 14:41:26.282   325  7029 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-16 14:41:26.282   325  7029 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-16 14:41:26.282   325  7029 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-16 14:41:26.282   325  1384 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-16 14:41:26.282   325  1384 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
,08-16 14:41:26.282   325  1384 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-16 14:41:26.282   325  1384 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-16 14:41:26.282   325  1384 D AudioPlayer: AudioPlayer releasing audio source
08-16 14:41:26.282   325  1384 D AudioPlayer: AudioPlayer done releasing audio source
08-16 14:41:26.282   325  1384 V AwesomePlayer: reset_l() 
08-16 14:41:26.282   325  1384 V AwesomePlayer: cancelPlayerEvents
08-16 14:41:26.282   325  1384 V AwesomePlayer: ~AwesomePlayer call,
08-16 14:41:26.283   325  1384 V AwesomePlayer: reset_l() 
08-16 14:41:26.283   325  1384 V AwesomePlayer: cancelPlayerEvents
08-16 14:41:26.283  6932  7026 V SoundPool: close(31)
08-16 14:41:26.283  6932  7026 V SoundPool: pointer = 0x9fff5000, size = 205080, sampleRate = 48000, numChannels = 2
,08-16 14:41:26.309  6932  6932 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
,08-16 14:41:26.310  6932  6932 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting,
08-16 14:41:26.312  6932  6932 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:9652
,08-16 14:41:26.488  6724  6724 I UEI.SmartControl: Supports setup maps: true
,08-16 14:41:26.491  6724  6724 D UEI.SmartControl: QS start statue = true Error code = 0
08-16 14:41:26.491  6724  6724 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-16 14:41:26.491  6724  6724 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-16 14:41:26.491  6724  6724 I UEI.SmartControl: ### init IR Blaster...
08-16 14:41:26.494  6724  6724 D serial_port: Configuring serial port
08-16 14:41:26.495  6724  6724 E UEI.SmartControl: UEIBLaster setting for 616
08-16 14:41:26.495  6724  6724 I UEI.SmartControl: Setting serial record hearder size = 2
08-16 14:41:26.495  6724  6724 I UEI.SmartControl: configuring settings for MAXQ616
08-16 14:41:26.495  6724  6724 I UEI.SmartControl: Get version...
08-16 14:41:26.513  6724  7032 D UEI.SmartControl: serial port data available: 21
,08-16 14:41:26.539  6724  6724 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-16 14:41:26.540  6724  6724 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-16 14:41:26.540  6724  6724 I UEI.SmartControl: QS saving settings...
,08-16 14:41:26.542  6724  6724 D UEI.SmartControl: IR Blaster version: 25672567
,08-16 14:41:26.560  6724  7032 D UEI.SmartControl: serial port data available: 4
,08-16 14:41:26.589  6724  7035 I UEI.SmartControl: Device manager: loading config....
,08-16 14:41:26.592  6724  6724 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-16 14:41:26.593  6724  7035 D UEI.SmartControl: ----------- loading internal config...
08-16 14:41:26.594  6724  6724 E UEI.SmartControl: Services init done
08-16 14:41:26.594  6724  6724 D UEI.SmartControl: QS Service init finished
08-16 14:41:26.595  6724  6724 D UEI.SmartControl: QS Service version name: 2.1.91
08-16 14:41:26.595  6724  6724 D UEI.SmartControl: QS Service version code: 201091
08-16 14:41:26.596  6724  6724 D UEI.SmartControl: Service requested: Control
08-16 14:41:26.603  6724  7035 E UEI.SmartControl: Loading SETTINGS...
,08-16 14:41:26.607  6724  6724 D UEI.SmartControl: Request IControl service: devices are loaded...
08-16 14:41:26.610  6724  6724 D UEI.SmartControl: Internal service binding...
08-16 14:41:26.611  6932  6932 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-16 14:41:26.615  6724  6740 I UEI.SmartControl: ------ IControl API: 11
08-16 14:41:26.615  6724  6740 D UEI.SmartControl: File observer start...
08-16 14:41:26.616  6724  6740 E UEI.SmartControl: IR Port is disabled: false
08-16 14:41:26.616  6724  7035 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-16 14:41:26.616  6724  6740 D UEI.SmartControl: Starting file observer...
08-16 14:41:26.616  6724  6740 I UEI.SmartControl: Registering callback...
,08-16 14:41:26.617  6724  6739 I UEI.SmartControl: ------ IControl API: 19
08-16 14:41:26.619  6724  6739 I UEI.SmartControl: Registering Services Ready callback...
08-16 14:41:26.628  6724  7034 I UEI.SmartControl: Notify AllClients services are ready: 0
08-16 14:41:26.628  6724  7034 D UEI.SmartControl: -----service ready thread exits
08-16 14:41:26.629  6932  6947 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
,08-16 14:41:26.630  6932  7024 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-16 14:41:26.632  6932  7024 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-16 14:41:26.633  6932  6932 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-16 14:41:26.635  6932  6932 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-16 14:41:26.635  6724  6740 I UEI.SmartControl: ------ IControl API: 8
08-16 14:41:26.639  6932  6932 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-16 14:41:26.639  6932  6932 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-16 14:41:26.640  6932  6932 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-16 14:41:26.641  6932  6932 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
,08-16 14:41:26.643  6932  6932 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-16 14:41:26.645  6932  6932 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-16 14:41:26.648  6932  6932 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
08-16 14:41:26.651  6932  6932 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-16 14:41:26.652  6932  6932 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-16 14:41:26.654  6932  6932 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-16 14:41:26.654  6932  6932 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
,08-16 14:41:26.658  6932  6932 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-16 14:41:26.660  6932  6932 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-16 14:41:26.661  6932  6932 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-16 14:41:26.663  6932  6932 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1471351286662]
08-16 14:41:26.668  6932  6932 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
,08-16 14:41:26.671  1038  1711 I ActivityManager: Killing 6516:com.lge.email/u0a23 (adj 15): empty #17
,08-16 14:41:26.708  6932  7037 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-16 14:41:26.757  1038  1711 I ActivityManager: Killing 5957:com.android.contacts/u0a19 (adj 15): empty #18
,08-16 14:41:26.791  1038  2019 W libprocessgroup: failed to open /acct/uid_10023/pid_6516/cgroup.procs: No such file or directory
,08-16 14:41:26.795  1038  2018 W libprocessgroup: failed to open /acct/uid_10019/pid_5957/cgroup.procs: No such file or directory,
08-16 14:41:26.800  6932  6932 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
08-16 14:41:26.801  6932  6932 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-16 14:41:26.801  6932  6932 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-16 14:41:26.801  6932  6932 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-16 14:41:26.802  6932  6932 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-16 14:41:26.802  6932  6932 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-16 14:41:26.802  6932  6932 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
08-16 14:41:26.812  6932  6932 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,08-16 14:41:27.662  1038  1448 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-16 14:41:27.677  1038  1120 D Tethering: MasterInitialState.processMessage what=3
08-16 14:41:27.692  6608  6608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 14:41:27.697  6608  6608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:41:27.699  6608  6608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:41:27.700  1038  1448 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-16 14:41:27.704  1038  1107 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-16 14:41:27.707  1038  1120 D Tethering: MasterInitialState.processMessage what=3
08-16 14:41:27.717  6608  6608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 14:41:27.720  6608  6608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:41:27.721  6608  6608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:41:27.723  6411  6411 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-16 14:41:27.726  6411  6455 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-16 14:41:27.737  5680  5680 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-16 14:41:27.746  5680  5680 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-16 14:41:27.764  2178  2178 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-16 14:41:27.800  1038  1107 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-16 14:41:27.843  1038  1946 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7047 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,08-16 14:41:27.846  1038  1107 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 14:41:27.847  1038  1107 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-16 14:41:27.913  7047  7047 I AppUp4:AppBoxCP: onCreate
,08-16 14:41:27.914  7047  7047 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,08-16 14:41:27.925  7047  7047 I AppUp4:DB:  setFingerPrint start
08-16 14:41:27.925  7047  7047 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
08-16 14:41:27.933  7047  7047 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
08-16 14:41:27.933  7047  7047 I AppUp4:DB:  SDK version = 21
08-16 14:41:27.933  7047  7047 I AppUp4:DB:  beforefinger == newfinger no write in DB
,08-16 14:41:27.935  7047  7047 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
08-16 14:41:27.936  7047  7047 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-16 14:41:27.936  7047  7047 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-16 14:41:27.939  7047  7047 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-16 14:41:27.939  7047  7047 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-16 14:41:27.948  7047  7047 I AppUp4:CustModeStarterReceiver: onReceive
,08-16 14:41:28.005  7047  7047 D LgDataFeature: LgDataFeature() Constructor: none
,08-16 14:41:28.005  7047  7047 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 14:41:28.014  7047  7047 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2701228a
,08-16 14:41:28.014  7047  7047 D AppUp4:CustFacade: isCustomizationCompleted : false
08-16 14:41:28.014  7047  7047 D AppUp4:CustFacade: isPhone : true
,08-16 14:41:28.015  7047  7047 D AppUp4:CustModeStarterReceiver: begin check event
08-16 14:41:28.016  7047  7047 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
08-16 14:41:28.016  7047  7047 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
08-16 14:41:28.017  7047  7081 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
08-16 14:41:28.017  7047  7081 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
08-16 14:41:28.017  7047  7081 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
08-16 14:41:28.019  1038  1562 I ActivityManager: Killing 5983:com.android.gallery3d/u0a27 (adj 15): empty #17
08-16 14:41:28.114  1038  1054 W libprocessgroup: failed to open /acct/uid_10027/pid_5983/cgroup.procs: No such file or directory
08-16 14:41:28.118  4286  4286 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-16 14:41:28.119  4286  4286 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-16 14:41:28.125  4286  4286 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-16 14:41:28.134  4286  4286 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-16 14:41:28.153  4286  7084 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-16 14:41:28.162  4286  7085 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-16 14:41:28.163  4286  7085 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-16 14:41:28.216  1038  2037 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7086 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-16 14:41:28.309  7086  7086 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-16 14:41:28.310  7086  7086 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-16 14:41:28.313  7086  7086 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-16 14:41:28.313  7086  7086 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-16 14:41:28.418  7086  7086 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-16 14:41:28.441  7086  7086 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,08-16 14:41:28.490  7086  7086 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-16 14:41:28.530  7086  7086 D LgDataFeature: LgDataFeature() Constructor: none
08-16 14:41:28.530  7086  7086 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 14:41:28.668  7086  7086 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-16 14:41:28.719  7086  7086 I HubEmail: JNI_OnLoad()
08-16 14:41:28.719  7086  7086 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-16 14:41:28.719  7086  7086 I HubEmail: registerNatives()
08-16 14:41:28.719  7086  7086 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-16 14:41:28.719  7086  7086 I HubEmail: registerNativeMethods()
08-16 14:41:28.719  7086  7086 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-16 14:41:28.720  7086  7086 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,08-16 14:41:28.721  3346  3346 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-16 14:41:28.721  3346  3346 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-16 14:41:28.721  3346  3346 I LgeMiscReceiver: networkInfo.isConnected() = false
08-16 14:41:28.758  1038  1562 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7118 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,08-16 14:41:28.768  7086  7115 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:41:28.778  6976  7117 V FormManager: Network unavailable.
,08-16 14:41:28.781  6976  7117 V FormManager: Network unavailable.
08-16 14:41:28.774  6976  7116 W FormManager: Network not available. Please check & try again.
,08-16 14:41:28.796  1038  1054 I ActivityManager: Killing 6552:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,08-16 14:41:28.831  1038  1944 W libprocessgroup: failed to open /acct/uid_10061/pid_6552/cgroup.procs: No such file or directory
08-16 14:41:28.899  7118  7118 D LgDataFeature: LgDataFeature() Constructor: none
08-16 14:41:28.899  7118  7118 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 14:41:28.903  7118  7118 D PhoneMonitor: Register our PhoneStateListener
,08-16 14:41:28.929  7118  7118 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,08-16 14:41:28.933  7118  7118 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-16 14:41:28.953  7118  7118 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
08-16 14:41:28.954  7118  7118 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
08-16 14:41:28.954  7118  7118 D TelephonyAutoProfiling: [parse] Load xml
08-16 14:41:28.957  7118  7118 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
08-16 14:41:28.957  7118  7118 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
08-16 14:41:28.958  7118  7118 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-16 14:41:28.958  7118  7118 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
08-16 14:41:28.958  7118  7118 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
08-16 14:41:28.958  7118  7118 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
08-16 14:41:28.958  7118  7118 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-16 14:41:28.958  7118  7118 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-16 14:41:28.958  7118  7118 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-16 14:41:28.958  7118  7118 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-16 14:41:28.958  7118  7118 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-16 14:41:28.958  7118  7118 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-16 14:41:28.958  7118  7118 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-16 14:41:28.958  7118  7118 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-16 14:41:28.958  7118  7118 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-16 14:41:28.958  7118  7118 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-16 14:41:28.958  7118  7118 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
,08-16 14:41:28.965  7118  7118 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
08-16 14:41:28.989  1038  1944 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7143 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-16 14:41:28.990  1038  1944 I ActivityManager: Killing 6052:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,08-16 14:41:29.044  1038  1562 W libprocessgroup: failed to open /acct/uid_10080/pid_6052/cgroup.procs: No such file or directory
,08-16 14:41:29.341  1038  1944 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7167 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,08-16 14:41:29.348  1038  1944 I ActivityManager: Killing 6083:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,08-16 14:41:29.463  1038  1981 W libprocessgroup: failed to open /acct/uid_10097/pid_6083/cgroup.procs: No such file or directory
08-16 14:41:29.586  1038  1053 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7184 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-16 14:41:29.592  1038  1053 I ActivityManager: Killing 6685:com.lge.eula/1000 (adj 15): empty #17
08-16 14:41:29.623  1038  1377 D LGWifiP2pService: P2pDisabledState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:41:29.623  1038  1377 D LGWifiP2pService: DefaultState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,08-16 14:41:29.650  1038  1381 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 1 0
08-16 14:41:29.651  1038  1381 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
,08-16 14:41:29.793  1038  1890 D WifiServiceImplEx: setWifiEnabled: true pid=6608, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,08-16 14:41:29.795  1038  1890 D WifiService: setWifiEnabled: true pid=6608, uid=10118
08-16 14:41:29.795  1038  1890 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-16 14:41:29.816  1038  1054 W libprocessgroup: failed to open /acct/uid_1000/pid_6685/cgroup.procs: No such file or directory
08-16 14:41:29.823  1038  1381 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
,08-16 14:41:29.823  1038  1381 I LGFTMITEM: [GET_FTM][id=6], offset=12288
,08-16 14:41:29.826  1038  1038 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-16 14:41:29.826  1038  1038 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-16 14:41:29.826  1038  1038 D Ulp_jni : JNI:system_update. Event-4
08-16 14:41:29.827  1038  1381 E WifiUtil: wfc_util_ffile_check_copy(): pid[1038] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-16 14:41:29.827  1038  1381 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-16 14:41:29.827  1038  1381 E WifiUtil: wfc_util_ffile_check_copy(): pid[1038] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-16 14:41:29.827  1038  1381 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-16 14:41:29.827  1038  1381 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-16 14:41:29.827  1038  1381 E WifiHW  : unknown target_country: EU , set to default
08-16 14:41:29.827  1038  1381 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-16 14:41:29.827  1038  1381 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-16 14:41:29.827  1038  1381 I WifiUtil: gEnableBmps=1
08-16 14:41:29.852  7184  7184 I art     : Almond Protected OAT
,08-16 14:41:29.905  7184  7184 D WeatherApplication: removeAccount
,08-16 14:41:29.910  7184  7184 D WeatherApplication: Account.length = 0
08-16 14:41:29.910  7184  7184 E WeatherApplication: OPERATOR:OPEN
08-16 14:41:29.923  7184  7184 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:41:29
,08-16 14:41:29.928  7184  7184 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-16 14:41:29.928  7184  7184 D Weather.Utils: 2 : All the weather widget is gone.
08-16 14:41:29.930  7184  7184 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-16 14:41:29.933  7184  7184 D WeatherAncestor: connectivity changed - connection : true
08-16 14:41:29.934  7184  7184 D WeatherService: 2 : isServiceAlived():false forecastCache:null
,08-16 14:41:29.946  7184  7184 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
,08-16 14:41:29.946  7184  7184 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-16 14:41:29.947  7184  7184 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
08-16 14:41:29.969  7184  7184 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
,08-16 14:41:29.970  7184  7184 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:41:29
,08-16 14:41:30.049  1038  1562 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7220 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-16 14:41:30.050  1038  1562 I ActivityManager: Killing 6703:com.lge.bnr/1000 (adj 15): empty #17
08-16 14:41:30.124  1038  1909 W libprocessgroup: failed to open /acct/uid_1000/pid_6703/cgroup.procs: No such file or directory
,08-16 14:41:30.269   281   332 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-16 14:41:30.269   281   332 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
,08-16 14:41:30.269   281   332 W Vold    : Returning OperationFailed - no handler for errno 0
,08-16 14:41:30.274  7220  7241 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,08-16 14:41:30.277   281   332 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,08-16 14:41:30.277   281   332 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-16 14:41:30.277   281   332 W Vold    : Returning OperationFailed - no handler for errno 0
08-16 14:41:30.277  7220  7241 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-16 14:41:30.285   281   332 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-16 14:41:30.285   281   332 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-16 14:41:30.285   281   332 W Vold    : Returning OperationFailed - no handler for errno 0
08-16 14:41:30.286  7220  7245 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,08-16 14:41:30.289   281   332 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-16 14:41:30.289   281   332 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-16 14:41:30.289   281   332 W Vold    : Returning OperationFailed - no handler for errno 0
08-16 14:41:30.290  7220  7245 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-16 14:41:30.538  7220  7220 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-16 14:41:30.542  1038  1120 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-16 14:41:30.546  1038  1120 D Tethering: InitialState.processMessage what=4
08-16 14:41:30.546  1038  1120 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-16 14:41:30.556   321   895 D SoftapController: Softap fwReload - Ok
08-16 14:41:30.556  1038  1381 E NetdConnector: NDC Command {52 softap fwreload wlan0 STA} took too long (721ms)
,08-16 14:41:30.559   321   895 D CommandListener: Setting iface cfg
08-16 14:41:30.559   321   895 D CommandListener: Trying to bring down wlan0
08-16 14:41:30.559   321   895 D CommandListener: Clearing all IP addresses on wlan0
08-16 14:41:30.562  1038  1381 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
08-16 14:41:30.563  1038  1381 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-16 14:41:30.563  1038  1381 E WifiStateMachine: useWiFiOffloading() : false
08-16 14:41:30.563  1038  1381 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-16 14:41:30.566  1038  1038 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-16 14:41:30.568  1927  1927 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-16 14:41:30.568  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 14:41:30.570  6608  6608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:41:30.571  6608  6608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:41:30.569  7268  7268 W wpa_supplicant: type=1400 audit(0.0:167): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-16 14:41:30.569  7268  7268 W wpa_supplicant: type=1400 audit(0.0:168): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 14:41:30.571  6608  6608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:41:30.571  1038  1381 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-16 14:41:30.571  1038  1381 D WifiMonitor: connecting to supplicant
08-16 14:41:30.585  7220  7220 I LibraryLoader: Loading: webviewchromium
08-16 14:41:30.588  7220  7220 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 7764-7768)
08-16 14:41:30.588  7220  7220 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-16 14:41:30.594  7220  7220 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2347aec7}
08-16 14:41:30.594  7268  7268 I wpa_supplicant: Successfully initialized wpa_supplicant
08-16 14:41:30.595  7220  7220 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-16 14:41:30.596  7220  7220 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-16 14:41:30.606  7220  7220 I BrowserStartupController: Initializing chromium process, renderers=0
08-16 14:41:30.607  7220  7220 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-16 14:41:30.619  7220  7220 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-16 14:41:30.623  7220  7220 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
08-16 14:41:30.623  7220  7220 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
,08-16 14:41:30.630   325  2115 V AudioPolicyService: registerClient() client 0xb558ab20, uid 10093
08-16 14:41:30.631  7220  7274 W AudioManagerAndroid: Requires BLUETOOTH permission
08-16 14:41:30.631  7268  7268 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-16 14:41:30.632  7268  7268 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
08-16 14:41:30.640  7220  7220 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-16 14:41:30.640  7220  7220 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-16 14:41:30.640  7220  7220 I Adreno-EGL: Build Date: 12/12/14 금
08-16 14:41:30.640  7220  7220 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-16 14:41:30.640  7220  7220 I Adreno-EGL: Remote Branch: 
08-16 14:41:30.640  7220  7220 I Adreno-EGL: Local Patches: 
08-16 14:41:30.640  7220  7220 I Adreno-EGL: Reconstruct Branch: 
,08-16 14:41:30.700  7220  7220 I NSApplication: Starting up...
,08-16 14:41:30.728  7268  7268 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-16 14:41:30.780  1038  2037 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7292 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,08-16 14:41:30.783  7268  7268 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-16 14:41:30.783  1038  1890 I ActivityManager: Killing 6014:com.android.vending/u0a44 (adj 15): empty #17
08-16 14:41:30.789  7268  7268 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
08-16 14:41:30.789  7268  7268 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-16 14:41:30.790  1038  1381 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-16 14:41:30.791  1038  1381 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-16 14:41:30.791  1038  1381 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-16 14:41:30.791  1038  7301 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
08-16 14:41:30.791  1038  7301 D WifiMonitor: Dropping event because (p2p0) is stopped
08-16 14:41:30.791  1038  7301 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-16 14:41:30.791  1038  7301 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-16 14:41:30.792  1038  7301 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-16 14:41:30.792  1038  7301 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-16 14:41:30.792  1038  1381 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-16 14:41:30.792  1038  1381 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-16 14:41:30.793  1038  1381 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-16 14:41:30.793  1038  1381 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-16 14:41:30.793  1038  1381 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-16 14:41:30.794  1038  1381 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-16 14:41:30.794  1038  1381 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-16 14:41:30.795  1038  1381 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-16 14:41:30.795  1038  1381 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-16 14:41:30.795  1038  1381 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-16 14:41:30.811   351   351 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 489us total 26.155ms
,08-16 14:41:30.833   351   351 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 388us total 20.166ms
,08-16 14:41:30.856   351   351 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 479us total 21.591ms
,08-16 14:41:30.873  1038  1381 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-16 14:41:30.873  1038  1381 E WifiStateMachine: useWiFiOffloading() : false
08-16 14:41:30.873  1038  1381 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-16 14:41:30.873  1038  1908 W libprocessgroup: failed to open /acct/uid_10044/pid_6014/cgroup.procs: No such file or directory
08-16 14:41:30.874  1038  1038 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:41:30.874  1038  1038 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:41:30.874  1038  1038 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:41:30.874  1038  1038 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:41:30.874  1038  1038 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-16 14:41:30.884  1038  1381 D WifiNative-wlan0: doBoolean: SET update_config 1
08-16 14:41:30.885  1038  1381 D WifiNative-wlan0: SET update_config 1: returned true
08-16 14:41:30.885  1038  1381 D WifiConfigStore: Loading config and enabling all networks 
08-16 14:41:30.885  1038  1381 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-16 14:41:30.886  1927  1927 D WfdService: Waiting for WifiP2p enabling
,08-16 14:41:30.887  1038  1381 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-16 14:41:30.887  1038  1038 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-16 14:41:30.888  1038  1428 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-16 14:41:30.889  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 14:41:30.889  6608  6608 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:41:30.889  6608  6608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 14:41:30.889  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:41:30.889  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 14:41:30.889  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 14:41:30.889  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 14:41:30.889  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 14:41:30.889  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 14:41:30.889  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 14:41:30.889  6608  6608 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:41:30.889  6608  6608 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 14:41:30.893  6608  6608 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:41:30.893  6608  6608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 14:41:30.893  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:41:30.893  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 14:41:30.893  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 14:41:30.893  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 14:41:30.893  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 14:41:30.893  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 14:41:30.893  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 14:41:30.893  6608  6608 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:41:30.893  6608  6608 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 14:41:30.895  6608  6608 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:41:30.895  6608  6608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 14:41:30.895  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:41:30.895  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 14:41:30.895  6608  6608 V io.jxco,re.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 14:41:30.895  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 14:41:30.895  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 14:41:30.895  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 14:41:30.895  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 14:41:30.895  6608  6608 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:41:30.896  6608  6608 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 14:41:30.903  1038  1381 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
,08-16 14:41:30.917  1038  1381 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-16 14:41:30.917  1038  1381 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-16 14:41:30.918  1038  1381 D WifiStateMachine: enableVerboseLogging : level 2
08-16 14:41:30.918  1038  1381 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
,08-16 14:41:30.919  1038  1381 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-16 14:41:30.919  1038  1381 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-16 14:41:30.919  7292  7292 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 14:41:30.919  1038  1381 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-16 14:41:30.919  1038  1381 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-16 14:41:30.920  1038  1381 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-16 14:41:30.920  1038  1381 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-16 14:41:30.921  1038  1381 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-16 14:41:30.921  1038  1381 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-16 14:41:30.921  1038  1381 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-16 14:41:30.921  1038  1381 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-16 14:41:30.922  1038  1381 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-16 14:41:30.922  1038  1381 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-16 14:41:30.922  1038  1381 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-16 14:41:30.923  1038  1381 D WifiStateMachine: Setting OUI to DA-A1-19
08-16 14:41:30.923  1038  1381 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-16 14:41:30.923  1927  1927 D WfdsService: Supplicant Connection state is changed : true
08-16 14:41:30.923  1038  1381 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-16 14:41:30.923  1927  2284 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-16 14:41:30.923  1038  1381 D WifiNative-HAL: Setting external_sim to 1
08-16 14:41:30.923  1927  2284 D WfdsService: Set the WFDS Monitor: true
08-16 14:41:30.923  1038  1381 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-16 14:41:30.923  1927  2284 D WfdsMonitor: WfdsMonitorThread create
08-16 14:41:30.924  1927  2284 D WfdsMonitor: WFDS Monitor is created and started
08-16 14:41:30.924  1927  2284 D WfdsService: WiFi: Supplicant connection re-established
08-16 14:41:30.924  1038  1381 D WifiNative-wlan0: SET external_sim 1: returned true
08-16 14:41:30.924  1038  1381 I WifiNative-HAL: startHal
08-16 14:41:30.924  1038  1381 D wifi    : setting scan oui 0xaf549bc0
08-16 14:41:30.924  1038  1381 D WifiStateMachine: Setting OUI to DA-A1-19
08-16 14:41:30.924  1038  1381 I WifiNative-HAL: startHal
08-16 14:41:30.924  1038  1381 D wifi    : setting scan oui 0xaf549bc0
08-16 14:41:30.925  1038  1381 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-16 14:41:30.925  1927  7311 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-16 14:41:30.925  1038  1381 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-16 14:41:30.925  1927  7311 E CtrlSupplicant: Succeed to open control connection
08-16 14:41:30.925  1038  1381 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-16 14:41:30.926  7268  7268 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-16 14:41:30.926  1927  7311 E CtrlSupplicant: Succeed to open monitor connection
08-16 14:41:30.926  1927  7311 D WfdsMonitor: Supplicant connection established
08-16 14:41:30.926  1038  1381 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-16 14:41:30.926  1927  2284 D WfdsService: Connected to the supplicant for wfds
08-16 14:41:30.927  1038  1381 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-16 14:41:30.927  7268  7268 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-16 14:41:30.927  1038  1381 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-16 14:41:30.927  1038  1381 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-16 14:41:30.927  7268  7268 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-16 14:41:30.927  1038  1381 D WifiNative-wlan0,: DRIVER RXFILTER-REMOVE 3: returned true
08-16 14:41:30.928  1038  1381 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-16 14:41:30.928  7268  7268 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-16 14:41:30.928  1038  1381 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-16 14:41:30.928  1038  1381 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-16 14:41:30.928  7268  7268 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-16 14:41:30.928  1038  1381 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-16 14:41:30.928  1038  1381 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-16 14:41:30.929  7268  7268 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-16 14:41:30.929  1038  1381 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-16 14:41:30.929  1038  1381 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-16 14:41:30.929  7268  7268 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-16 14:41:30.929  1038  1381 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-16 14:41:30.930  1038  1381 E WifiNative: : [168,097,118 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-16 14:41:30.931  1038  1381 D WifiNative-wlan0: doBoolean: RECONNECT
08-16 14:41:30.931  1038  1381 D WifiNative-wlan0: RECONNECT: returned true
08-16 14:41:30.931  1038  1381 D WifiNative-wlan0: doString: [STATUS]
08-16 14:41:30.931  1038  7301 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-16 14:41:30.931  1038  7301 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-16 14:41:30.932  1038  1381 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-16 14:41:30.932  1038  1381 D WifiNative-wlan0: doBoolean: SET ps 1
08-16 14:41:30.932  1038  1381 D WifiNative-wlan0: SET ps 1: returned true
08-16 14:41:30.933  1038  1377 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
,08-16 14:41:30.933  1038  1038 D WifiScanningService: SCAN_AVAILABLE : 3
08-16 14:41:30.934  1038  1038 D RttService: SCAN_AVAILABLE : 3
08-16 14:41:30.934  1038  1543 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:41:30.934  1038  1542 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:41:30.934  1038  1542 I WifiNative-HAL: startHal
08-16 14:41:30.934  1038  1381 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-16 14:41:30.934  1038  1542 D wifi    : getting scan capabilities on interface[1] = 0xaf549bc0
08-16 14:41:30.934  1038  1542 D wifi    : failed to get capabilities : -3
08-16 14:41:30.934  1038  1542 E WifiScanningService: could not get scan capabilities
08-16 14:41:30.934   321   895 D CommandListener: Setting iface cfg
08-16 14:41:30.934   321   895 D CommandListener: Trying to bring up p2p0
08-16 14:41:30.934  1038  1381 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-16 14:41:30.935  1038  1377 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-16 14:41:30.935  1038  1377 D LGWifiP2pService: P2pEnablingState
08-16 14:41:30.935  1038  1377 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:41:30.935  1038  1377 D LGWifiP2pService: P2p socket connection successful
08-16 14:41:30.935  1038  1381 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-16 14:41:30.935  1038  1377 D LGWifiP2pService: P2pEnabledState
08-16 14:41:30.935  1038  1377 D LGWifiP2pService: sending p2p connection changed broadcast
08-16 14:41:30.936  1927  1927 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-16 14:41:30.936  1927  1927 D WfdsService: WifiP2pState is changed : true
08-16 14:41:30.937  1927  2284 D WfdsService: Receive the WFDS_ENABLE Method
08-16 14:41:30.937  1927  2284 D WfdsService: Set the WFDS Monitor: true
08-16 14:41:30.937  1927  2284 D WfdsService: Connected to the supplicant for wfds
08-16 14:41:30.937  1038  1381 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-16 14:41:30.937  1927  2284 D WfdsJNI : doCommand: WFDS_SET TRUE
08-16 14:41:30.937  7268  7268 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-16 14:41:30.937  1927  2284 D WfdsService: selectPreferredScanChannel [36]
08-16 14:41:30.937  1927  2284 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-16 14:41:30.938  1038  1381 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-16 14:41:30.938  1038  1381 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-16 14:41:30.939  1927  1927 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-16 14:41:30.939  1038  1377 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-16 14:41:30.939  1038  1377 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-16 14:41:30.939  1927  1927 D WfdsService: isConnected: false
08-16 14:41:30.940  1038  1377 D WifiNative-p2p0: doBoolean: SET device_name G3
08-16 14:41:30.940  1038  1377 D WifiNative-p2p0: SET device_name G3: returned true
08-16 14:41:30.940  1038  1381 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-16 14:41:30.940  1038  1377 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-16 14:41:30.940  1038  1381 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-16 14:41:30.940  1038  1377 D LGWifiP2pService: before postfix = G3
08-16 14:41:30.940  1038  1377 D WifiServerServiceExt: postfix byte check : 2
08-16 14:41:30.940  1038  1377 D LGWifiP2pService: after postfix = G3
08-16 14:41:30.940  1038  1377 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-16 14:41:30.940  7268  7268 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-16 14:41:30.941  1038  1377 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-16 14:41:30.941  1038  1377 D WifiNative-p2p0: doBoolean: SET ,device_type 10-0050F204-5
08-16 14:41:30.941  1038  1377 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-16 14:41:30.941  1038  1377 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-16 14:41:30.941  1038  1377 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-16 14:41:30.941  1038  1377 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-16 14:41:30.942  1038  1381 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-16 14:41:30.942  1038  1377 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-16 14:41:30.942  1038  1377 D WifiNative-HAL: p2pGetDeviceAddress
08-16 14:41:30.942  1038  1381 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-16 14:41:30.942  1038  1377 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-16 14:41:30.943  1038  1381 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-16 14:41:30.943  1038  1377 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-16 14:41:30.943  1038  1377 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-16 14:41:30.944  1927  1927 I WfdStateTracker: handleP2pThisDeviceChanged
08-16 14:41:30.944  1927  1927 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-16 14:41:30.944  1927  1927 D WfdsService: Update P2p Interface State: 3
08-16 14:41:30.944  1038  1377 D WifiNative-p2p0: P2P_FLUSH: returned true
08-16 14:41:30.944  1038  1377 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-16 14:41:30.945  1038  1377 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-16 14:41:30.945  1038  1377 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-16 14:41:30.945  1038  1377 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-16 14:41:30.945  1038  1377 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
,08-16 14:41:30.947  1038  1381 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100,
08-16 14:41:30.955  7268  7268 E wpa_supplicant: disconnect_rssi_lvl: -100
08-16 14:41:30.955  1038  1381 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
08-16 14:41:30.956  1038  1381 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
08-16 14:41:30.956  1038  1381 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
08-16 14:41:30.956  1038  1381 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-16 14:41:30.957  1038  1377 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-16 14:41:30.957  1038  1377 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-16 14:41:30.957  1038  1377 D LGWifiP2pService: InactiveState
,08-16 14:41:30.957  1038  1377 D LGWifiP2pService: InactiveState{ when=-13ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:41:30.957  1038  1377 D LGWifiP2pService: P2pEnabledState{ when=-13ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:41:30.957  1038  1377 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-16 14:41:30.957  7268  7268 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-16 14:41:30.958  7268  7268 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
,08-16 14:41:30.959  7268  7268 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-16 14:41:30.959  7268  7268 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 14:41:30.959  1038  1381 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-16 14:41:30.960  7268  7268 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 14:41:30.960  1038  1381 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
,08-16 14:41:30.960  1038  7301 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-16 14:41:30.960  1038  7301 E WifiMonitor: WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 14:41:30.960  1038  7301 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 14:41:30.960  1038  7301 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 14:41:30.961  1038  7301 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 14:41:30.961  1038  7301 E WifiMonitor: WifiMonitor:p2p0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 14:41:30.961  1038  7301 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 14:41:30.961  1927  7311 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 14:41:30.961  1038  7301 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 14:41:30.961  1038  7301 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
,08-16 14:41:30.961  1038  7301 E WifiMonitor: WifiMonitor:p2p0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 14:41:30.961  1927  7311 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 14:41:30.961  1038  1381 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-16 14:41:30.961  1038  7301 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 14:41:30.961  1038  7301 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 14:41:30.961  1038  1381 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-16 14:41:30.961  1038  1381 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-16 14:41:30.962  7268  7268 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-16 14:41:30.962  7268  7268 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-16 14:41:30.962  1038  7301 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-16 14:41:30.962  1038  7301 E WifiMonitor: WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-16 14:41:30.962  1038  7301 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-16 14:41:30.962  1038  7301 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-16 14:41:30.963  1038  1381 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-16 14:41:30.963  1038  1381 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-16 14:41:30.964  1038  1381 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-16 14:41:30.964  1038  1381 D WifiNative-wlan0: doBoolean: SCAN
08-16 14:41:30.964  1038  1381 D WifiNative-wlan0: SCAN: returned false
08-16 14:41:30.965  1038  1381 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=168132  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-16 14:41:30.967  1038  1381 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=168134  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-16 14:41:30.967  7268  7268 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-16 14:41:30.967  7268  7268 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 14:41:30.968  1038  7301 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-16 14:41:30.968  1038  1038 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:41:30.968  1038  7301 E WifiMonitor: WifiMonitor:p2p0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 14:41:30.968  1038  1038 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:41:30.968  1038  7301 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 14:41:30.968  1038  7301 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 14:41:30.968  1038  1038 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-16 14:41:30.968  7268  7268 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-16 14:41:30.968  1927  7311 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-16 14:41:30.969  7268  7268 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 14:41:30.969  1038  7301 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 14:41:30.969  1038  1377 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-16 14:41:30.969  1038  7301 E WifiMonitor: WifiMonitor:p2p0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 14:41:30.969  1038  7301 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init,=DRIVER type=WORLD
08-16 14:41:30.969  1038  1377 D LGWifiP2pService: InactiveState{ when=-12ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:41:30.969  1038  7301 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 14:41:30.969  1038  1377 D LGWifiP2pService: P2pEnabledState{ when=-12ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:41:30.969  1038  1377 D LGWifiP2pService: DefaultState{ when=-12ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:41:30.969  1038  1377 D LGWifiP2pService: InactiveState{ when=-12ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:41:30.969  1038  1377 D LGWifiP2pService: P2pEnabledState{ when=-12ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:41:30.969  1038  1377 D LGWifiP2pService: DefaultState{ when=-12ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:41:30.969  1038  1377 D LGWifiP2pService: InactiveState{ when=-12ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:41:30.969  1038  1377 D LGWifiP2pService: P2pEnabledState{ when=-12ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:41:30.970  1038  1377 D LGWifiP2pService: DefaultState{ when=-12ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:41:30.970  7268  7268 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 14:41:30.970  1038  1377 D LGWifiP2pService: InactiveState{ when=-12ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:41:30.970  1038  1377 D LGWifiP2pService: P2pEnabledState{ when=-12ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:41:30.970  1038  7301 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 14:41:30.971  1927  2284 W WfdsService: DefaultState - msg [9441285] is not handled
08-16 14:41:30.971  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 14:41:30.971  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 14:41:30.971  1927  7311 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 14:41:30.971  1927  7311 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 14:41:30.971  1038  1377 D LGWifiP2pService: DefaultState{ when=-12ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
,08-16 14:41:30.972  1038  7301 E WifiMonitor: WifiMonitor:p2p0 cnt=30 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 14:41:30.972  1038  7301 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 14:41:30.972  1038  7301 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 14:41:30.972  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-16 14:41:30.973  1038  1381 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 14:41:30.974  1038  1038 E WifiServerServiceExt: No p2p device connected
08-16 14:41:30.974  1038  1377 D LGWifiP2pService: InactiveState{ when=-14ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:41:30.974  1038  1377 D LGWifiP2pService: P2pEnabledState{ when=-15ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:41:30.974  1038  1381 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 14:41:30.975  1038  1381 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 14:41:30.975  1038  1381 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 14:41:30.976  1038  1381 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 14:41:30.977  1038  1038 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 14:41:30.977  1038  1038 D WifiServerServiceExt: setSupplicantStateSCANNING
,08-16 14:41:31.268  6411  6411 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-16 14:41:31.270  6411  6455 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-16 14:41:31.291  2178  2178 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-16 14:41:31.304  1038  1365 D PowerManagerServiceEx: acquireWakeLockInternal: lock=448744860, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1038
,08-16 14:41:31.310  7047  7047 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-16 14:41:31.310  7047  7047 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-16 14:41:31.310  7047  7047 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-16 14:41:31.310  7047  7047 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-16 14:41:31.312  7047  7047 I AppUp4:CustModeStarterReceiver: onReceive
08-16 14:41:31.315  7047  7047 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2701228a
08-16 14:41:31.315  7047  7047 D AppUp4:CustFacade: isCustomizationCompleted : false
08-16 14:41:31.316  7047  7047 D AppUp4:CustFacade: isPhone : true
08-16 14:41:31.316  7047  7047 D AppUp4:CustModeStarterReceiver: begin check event
08-16 14:41:31.316  7047  7047 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
,08-16 14:41:31.321  4286  4286 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-16 14:41:31.322  4286  4286 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-16 14:41:31.323  4286  4286 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 14:41:31.326  4286  4286 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 14:41:31.337  7086  7086 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-16 14:41:31.340  2559  2559 D [Concierge]Service: onStartCommand(). Type : 9
08-16 14:41:31.342  4286  7326 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-16 14:41:31.353  4286  7327 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-16 14:41:31.353  4286  7327 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-16 14:41:31.370  7086  7328 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 14:41:31.383  7268  7268 E wpa_supplicant: USIM:  scard_init function
08-16 14:41:31.383  7268  7268 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-16 14:41:31.384  1038  7301 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-16 14:41:31.384  1038  7301 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-16 14:41:31.384  1038  7301 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-16 14:41:31.385  1038  7301 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: WPS-AP-AVAILABLE 
08-16 14:41:31.385  1038  7301 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-16 14:41:31.385  1038  7301 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-16 14:41:31.385  1038  7301 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-16 14:41:31.386  1038  1381 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-16 14:41:31.386  1038  1381 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-16 14:41:31.386  1038  1038 D PowerManagerServiceEx: releaseWakeLockInternal: lock=448744860 [*alarm*], flags=0x0
08-16 14:41:31.387  1038  1381 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-16 14:41:31.387  1038  1381 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
,08-16 14:41:31.387  1038  1381 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-16 14:41:31.387  6976  7330 W FormManager: Network not available. Please check & try again.
08-16 14:41:31.392  3346  3346 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-16 14:41:31.392  3346  3346 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-16 14:41:31.392  3346  3346 I LgeMiscReceiver: networkInfo.isConnected() = false
08-16 14:41:31.393  1038  1381 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=168561  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-16 14:41:31.396  1038  1981 I art     : Explicit concurrent mark sweep GC freed 73620(3MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/65MB, paused 2.786ms total 191.094ms
08-16 14:41:31.398  7118  7118 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-16 14:41:31.398  7118  7118 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-16 14:41:31.398  1038  1381 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=168566  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-16 14:41:31.401  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 14:41:31.402  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-16 14:41:31.402  1038  1038 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:41:31.402  1038  1038 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:41:31.403  1038  1038 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-16 14:41:31.404  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 14:41:31.405  1038  1038 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:41:31.405  1038  1038 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:41:31.405  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 14:41:31.405  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 14:41:31.405  1038  1038 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-16 14:41:31.405  1038  1038 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 14:41:31.405  1038  1038 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-16 14:41:31.406  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 14:41:31.408  6976  7332 V FormManager: Network unavailable.
08-16 14:41:31.413  6976  7332 V FormManager: Network unavailable.
,08-16 14:41:31.426  7184  7184 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:41:31
08-16 14:41:31.429  7184  7184 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
,08-16 14:41:31.429  7184  7184 D Weather.Utils: 2 : All the weather widget is gone.
08-16 14:41:31.430  7184  7184 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-16 14:41:31.430  7184  7184 D WeatherAncestor: connectivity changed - connection : true
08-16 14:41:31.430  7184  7184 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@316e4518
08-16 14:41:31.431  7184  7184 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-16 14:41:31.431  7184  7184 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-16 14:41:31.431  7184  7184 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-16 14:41:31.431  7184  7184 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-16 14:41:31.431  7184  7184 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:41:31
08-16 14:41:31.455  6879  6879 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-16 14:41:31.455  6879  6879 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-16 14:41:31.455  6879  6879 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-16 14:41:31.455  6879  6879 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
,08-16 14:41:31.456  6879  6879 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-16 14:41:31.457  6879  6879 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-16 14:41:31.457  6879  6879 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-16 14:41:31.457  6879  6879 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-16 14:41:31.457  6879  6879 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-16 14:41:31.457  6879  6879 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-16 14:41:31.457  6879  6879 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-16 14:41:31.465  6899  6899 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-16 14:41:31.468  6879  6879 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-16 14:41:31.470  6976  7341 W FormManager: Network not available. Please check & try again.
,08-16 14:41:31.477  6976  7342 V FormManager: Network unavailable.
08-16 14:41:31.479  6976  7342 V FormManager: Network unavailable.
08-16 14:41:31.480  6879  6879 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-16 14:41:31.489  7268  7268 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
08-16 14:41:31.489  1038  7301 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-16 14:41:31.489  1038  7301 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-16 14:41:31.490  1038  7301 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-16 14:41:31.490  1038  7301 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-16 14:41:31.491  1038  1381 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=168658  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-16 14:41:31.491  1038  1381 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=168658  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-16 14:41:31.493  1038  1038 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 14:41:31.493  1038  1038 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-16 14:41:31.493  1038  1120 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-16 14:41:31.496  1038  7301 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 14:41:31.496  1038  7301 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-16 14:41:31.497  1038  1381 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
08-16 14:41:31.498  1038  1381 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-16 14:41:31.498  7268  7268 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-16 14:41:31.498  7268  7268 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-16 14:41:31.498  1038  1381 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-16 14:41:31.500  1038  7301 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
,08-16 14:41:31.500  1038  7301 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-16 14:41:31.500  1038  7301 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-16 14:41:31.500  1038  7301 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-16 14:41:31.500  1038  1381 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-16 14:41:31.500  1038  7301 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-16 14:41:31.500  1038  7301 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-16 14:41:31.500  1038  7301 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-16 14:41:31.501  1038  7301 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-16 14:41:31.501  1038  1381 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-16 14:41:31.501  1038  7301 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 14:41:31.501  1038  7301 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-16 14:41:31.501  1038  1381 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=168668
08-16 14:41:31.502  1038  1381 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=168669
08-16 14:41:31.502  1038  1381 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=168669
08-16 14:41:31.502  1038  1381 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=168670
08-16 14:41:31.503  1038  1381 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=168670
08-16 14:41:31.503  1038  1381 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=168671  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-16 14:41:31.506  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 14:41:31.506  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 14:41:31.506  1038  1038 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:41:31.506  1038  1038 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:41:31.506  1038  1038 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-16 14:41:31.507  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-16 14:41:31.509  1038  1381 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=168676  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
,08-16 14:41:31.510  1038  1381 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=168677  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-16 14:41:31.510  1038  1381 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=168677  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-16 14:41:31.511  1038  1381 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=168678
08-16 14:41:31.511  1038  1038 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:41:31.511  1038  1038 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:41:31.511  1038  1381 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=168679
08-16 14:41:31.512  1038  1038 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-16 14:41:31.512  1038  1381 D WifiNative-wlan0: doString: [STATUS]
08-16 14:41:31.512  1038  7301 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 14:41:31.513  1038  7301 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-16 14:41:31.513  1038  1381 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-16 14:41:31.514  1038  1381 I WifiServiceExtension: setVHTCapabilityType  : false
08-16 14:41:31.518  6899  6899 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-16 14:41:31.522  1038  1381 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-16 14:41:31.522  1038  1381 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
08-16 14:41:31.523  6879  6879 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-16 14:41:31.525  1038  1038 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:41:31.525  1038  1038 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:41:31.525  1038  1038 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-16 14:41:31.527  6976  7344 W FormManager: Network not available. Please check & try again.
08-16 14:41:31.527  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 14:41:31.527  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 14:41:31.531  1038  1038 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:41:31.531  1038  1038 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:41:31.531  1038  1038 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,08-16 14:41:31.533  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 14:41:31.536  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 14:41:31.536  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 14:41:31.537  1038  1381 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-16 14:41:31.537  1038  1381 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-16 14:41:31.537  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 14:41:31.537  1038  1381 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-16 14:41:31.538  1038  1448 D ConnectivityService: Got NetworkAgent Messenger
08-16 14:41:31.538  1038  1381 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-16 14:41:31.538  1038  1381 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-16 14:41:31.538  1038  1448 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-16 14:41:31.538  1038  1448 D ConnectivityService: NetworkAgent connected
08-16 14:41:31.538  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 14:41:31.539  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 14:41:31.540  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 14:41:31.541  6879  6879 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 14:41:31.541  1038  1381 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-16 14:41:31.542  1038  1381 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-16 14:41:31.542  1038  1381 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-16 14:41:31.542  1038  1381 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-16 14:41:31.543  1038  1381 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-16 14:41:31.546  6976  7345 V FormManager: Network unavailable.
08-16 14:41:31.547  1038  1381 D WifiNative-wlan0: SAVE_CONFIG: returned true
,08-16 14:41:31.550   321   895 D CommandListener: Setting iface cfg
08-16 14:41:31.551  6976  7345 V FormManager: Network unavailable.
08-16 14:41:31.553  1038  1381 E WifiStateMachine: Start Dhcp Watchdog 2
08-16 14:41:31.553  1038  7347 D DhcpStateMachine: StoppedState
08-16 14:41:31.553  1038  7347 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:41:31.553  1038  7347 D DhcpStateMachine: WaitBeforeStartState
08-16 14:41:31.553  1038  1381 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=168721  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 14:41:31.554  1038  1381 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=168721  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 14:41:31.554  1038  1381 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=168721  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 14:41:31.555  1038  1038 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 14:41:31.555  1038  1038 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-16 14:41:31.556  1038  1381 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=168723  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 14:41:31.557  1038  1381 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=168724  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 14:41:31.558  1038  1381 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=168725  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 14:41:31.559  1038  1381 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:121838] from screen [on:0 period:-1822490969] gl rssi=-55 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-16 14:41:31.559  4286  4286 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-16 14:41:31.559  4286  4286 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-16 14:41:31.560  1038  1381 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1822490968] gl rssi=-55 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-16 14:41:31.560  1038  1381 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-16 14:41:31.560  1038  1038 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 14:41:31.560  1038  1038 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-16 14:41:31.561  4286  4286 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-16 14:41:31.564  1038  1448 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
08-16 14:41:31.564  1038  1381 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 14:41:31.564  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 14:41:31.564  1038  1381 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 14:41:31.565  1038  1381 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 14:41:31.565  4286  4286 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 14:41:31.565  1038  1381 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 14:41:31.565  1038  1381 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 14:41:31.565  1038  1381 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 14:41:31.566  1038  1448 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-16 14:41:31.566  1038  1381 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=98,0,0
08-16 14:41:31.566  1038  1381 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=98,0,0
08-16 14:41:31.566  1038  1381 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-16 14:41:31.567  7268  7268 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-16 14:41:31.567  1038  1381 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-16 14:41:31.567  1038  1381 D WifiNative-wlan0: doBoolean: SET ps 0
08-16 14:41:31.567  1038  1381 D WifiNative-wlan0: SET ps 0: returned true
08-16 14:41:31.567  1038  1381 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-16 14:41:31.567  7268  7268 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-16 14:41:31.568  1038  1381 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-16 14:41:31.568  1038  1377 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@88a2f9e target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:41:31.568  1038  1377 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@88a2f9e target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:41:31.568  1038  7347 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:41:31.568  1038  7347 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-16 14:41:31.568  1038  1381 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-16 14:41:31.568  1038  1381 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-16 14:41:31.568  1038  1381 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-16 14:41:31.569   321   895 D CommandListener: Setting iface cfg
08-16 14:41:31.569   321   895 D CommandListener: Trying to bring up wlan0
08-16 14:41:31.570  1038  1381 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.135/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-16 14:41:31.572  4286  7348 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-16 14:41:31.573  4286  7349 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-16 14:41:31.573  4286  7349 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null,
,08-16 14:41:31.589  6724  7036 D UEI.SmartControl: Internal timer expired: 2
08-16 14:41:31.589  6724  7036 D UEI.SmartControl: unbind internal service
,08-16 14:41:31.613  1038  1945 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7350 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-16 14:41:31.616  1038  1038 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
,08-16 14:41:31.616  1038  1038 D WifiServerServiceExt: setSupplicantStateCOMPLETED
,08-16 14:41:31.618  1038  1038 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 14:41:31.618  1038  1038 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-16 14:41:31.619  1038  1381 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 14:41:31.620  1038  1381 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 14:41:31.621  1038  1381 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 14:41:31.622  1038  1381 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 14:41:31.624  1038  1381 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 14:41:31.625  1038  1381 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 14:41:31.625  1038  1448 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-16 14:41:31.627  1038  1381 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-16 14:41:31.628  1038  1381 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-16 14:41:31.628  1038  1381 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-16 14:41:31.628  1038  1377 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:41:31.628  1038  1377 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:41:31.628  7268  7268 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-16 14:41:31.630  1038  1381 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-16 14:41:31.630  1038  1381 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-16 14:41:31.630  7268  7268 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-16 14:41:31.631  1038  1381 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
,08-16 14:41:31.631  1038  1381 D WifiNative-wlan0: doBoolean: SET ps 1
08-16 14:41:31.646  1038  1381 D WifiNative-wlan0: SET ps 1: returned true
,08-16 14:41:31.647  1038  1448 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-16 14:41:31.647  1038  1381 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-16 14:41:31.648  1038  1381 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-16 14:41:31.648  1038  1381 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-16 14:41:31.648  1038  1448 D ConnectivityService: ignoring duplicate network state non-change
08-16 14:41:31.651  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 14:41:31.651  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 14:41:31.654  1038  1038 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:41:31.654  1038  1038 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:41:31.654  1038  1038 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-16 14:41:31.654  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 14:41:31.656  1038  1448 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-16 14:41:31.656  1038  1448 D ConnectivityService: Adding iface wlan0 to network 101
,08-16 14:41:31.665  1038  1038 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:41:31.665  1038  1038 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:41:31.666  1038  1038 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-16 14:41:31.668  1038  1038 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-16 14:41:31.672  1927  1927 V WfdStateTracker: handleWifiStateChangedEvent: 1
,08-16 14:41:31.679  1038  1038 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:41:31.679  1038  1038 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:41:31.679  1038  1038 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-16 14:41:31.681  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 14:41:31.681  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 14:41:31.682  1038  1381 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-16 14:41:31.682  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 14:41:31.683  1038  1038 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-16 14:41:31.687  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-16 14:41:31.687  1589  1589 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-16 14:41:31.687  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 14:41:31.692  1038  1448 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-16 14:41:31.692  1038  1448 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
08-16 14:41:31.692  6724  7033 D serial_port: close(fd = 24)
08-16 14:41:31.693  1038  1038 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:41:31.693  1038  1038 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:41:31.693  1038  1038 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-16 14:41:31.694  1038  1448 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
08-16 14:41:31.694   321   895 E Netd    : netlink response contains error (File exists)
08-16 14:41:31.695  1038  1448 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
08-16 14:41:31.696  1038  1448 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-16 14:41:31.696  1038  1448 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
08-16 14:41:31.696  1038  1448 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
08-16 14:41:31.697  6724  7033 I UEI.SmartControl: Serial port is closed.
08-16 14:41:31.697  1038  1448 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-16 14:41:31.697  1038  1448 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-16 14:41:31.698  1038  1448 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-16 14:41:31.698  1038  1448 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-16 14:41:31.698  1038  7346 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:41:31.698  1038  7346 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-16 14:41:31.698  1038  1448 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 14:41:31.698  1038  1448 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 14:41:31.698  1038  7346 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-1ms what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:41:31.698  1038  1448 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-16 14:41:31.698  1038  7346 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-16 14:41:31.698  1038  1448 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 14:41:31.698  1038  1448 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-16 14:41:31.698  1038  1448 D ConnectivityService: currentScore = 0, newScore = 20
08-16 14:41:31.698  1038  1448 D ConnectivityService:    accepting network in place of null
08-16 14:41:31.698  1038  1448 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 14:41:31.700  1038  1381 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTER,NET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-16 14:41:31.701  1038  1381 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 14:41:31.701  1839  1839 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 14:41:31.701  1839  1839 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-16 14:41:31.702  1038  1448 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-16 14:41:31.702  1038  1448 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-16 14:41:31.702  1038  1448 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-16 14:41:31.702   321  7370 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-16 14:41:31.707  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 14:41:31.707  1589  1589 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-16 14:41:31.708  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 14:41:31.711  1038  1448 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-16 14:41:31.711  1038  1448 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-16 14:41:31.712  1038  1448 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,08-16 14:41:31.713  1038  1038 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-16 14:41:31.713  1038  1038 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-16 14:41:31.713  1038  1038 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-16 14:41:31.713  1038  1038 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-16 14:41:31.714  1038  1448 D ConnectivityService: validation of new default Network = false
08-16 14:41:31.714  1038  1448 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-16 14:41:31.714  1038  1448 D DSQN    : enableDataServiceNotify 
08-16 14:41:31.714  1038  1448 D DSQN    : start dsqn bin
08-16 14:41:31.719  7371  7371 W dsqn    : type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 14:41:31.719  7371  7371 W dsqn    : type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 14:41:31.720  1038  1448 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-16 14:41:31.720  1038  1448 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 14:41:31.720  1038  1448 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 14:41:31.720  1038  1448 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 14:41:31.730  1589  1837 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-16 14:41:31.737  1038  1375 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
08-16 14:41:31.747  7371  7371 E DSQN    : DSQN ssw
,08-16 14:41:31.753  1803  7373 I CheckinService: active receiver: enabled
08-16 14:41:31.756  1589  1589 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-16 14:41:31.756  7350  7350 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-16 14:41:31.757  7350  7350 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
08-16 14:41:31.757  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 14:41:31.758  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-16 14:41:31.763  1803  7373 I CheckinService: Preparing to send checkin request
,08-16 14:41:31.763  1803  7373 I EventLogService: Accumulating logs since 1471351180072
08-16 14:41:31.763  7350  7350 V [BNRBootReceiver]: Boot Receiver Return
08-16 14:41:31.763  7350  7350 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-16 14:41:31.763   321  7370 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-16 14:41:31.766  6411  6411 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 14:41:31.770  1038  7347 D DhcpStateMachine: DHCPV4 request on wlan0
08-16 14:41:31.771  1038  7347 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-16 14:41:31.771  1038  7347 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-16 14:41:31.771  6879  6879 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-16 14:41:31.769  7378  7378 W dhcpcd  : type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 14:41:31.769  7378  7378 W dhcpcd  : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-16 14:41:31.777  6879  6879 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 14:41:31.781  7378  7378 I dhcpcd  : version 5.5.6 starting
08-16 14:41:31.783  7378  7378 E dhcpcd  : get_duid: m
08-16 14:41:31.783  7378  7378 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-16 14:41:31.783  7378  7378 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-16 14:41:31.786  6932  6932 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-16 14:41:31.787  6932  6932 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 14:41:31.788  6932  6932 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-16 14:41:31.792  6879  6879 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
08-16 14:41:31.794  6879  6879 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-16 14:41:31.797  6411  6411 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 14:41:31.803   321  7370 D libc-netbsd: res_queryN name = clients3.google.com succeed
08-16 14:41:31.803  6879  6879 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 14:41:31.808  6879  6879 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 14:41:31.815  6932  6932 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-16 14:41:31.815  6932  6932 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 14:41:31.817  6932  6932 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-16 14:41:31.819  1803  7373 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
08-16 14:41:31.819  6411  6411 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 14:41:31.827  6879  6879 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 14:41:31.834  6879  6879 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 14:41:31.834   321   894 D LGDataListener: argv[0]=dsqncommand
08-16 14:41:31.835   321   894 D LGDataListener: argv[1]=wlan0
08-16 14:41:31.835   321   894 D LGDataListener: argv[2]=1
08-16 14:41:31.835   321   894 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-16 14:41:31.838  1038  1118 D DSQN    : DSQM DsqnNotification wlan0  1
08-16 14:41:31.838  1038  1118 D DSQN    : start to monitor internet connection
,08-16 14:41:31.840  7378  7378 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-16 14:41:31.840  6932  6932 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 14:41:31.841  7378  7378 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-16 14:41:31.841  7378  7378 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-16 14:41:31.841  7378  7378 I dhcpcd  : wlan0: rebinding lease of 192.168.1.135
08-16 14:41:31.841  6932  6932 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 14:41:31.841  7378  7378 D dhcpcd  : wlan0: sending REQUEST (xid 0x7f9870f), next in 3.50 seconds
08-16 14:41:31.841  6932  6932 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-16 14:41:31.844  6879  6879 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-16 14:41:31.844  6879  6879 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-16 14:41:31.844  6879  6879 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-16 14:41:31.844  6879  6879 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-16 14:41:31.845  6879  6879 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-16 14:41:31.845  6879  6879 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-16 14:41:31.845  6879  6879 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-16 14:41:31.845  6879  6879 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-16 14:41:31.845  6879  6879 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-16 14:41:31.845  6879  6879 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-16 14:41:31.845  6879  6879 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-16 14:41:31.846  6879  6879 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-16 14:41:31.848  6411  6411 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-16 14:41:31.853  6879  6879 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-16 14:41:31.858  6879  6879 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 14:41:31.864  6932  6932 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 14:41:31.864  6932  6932 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 14:41:31.865  6932  6932 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-16 14:41:31.868  6411  6411 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 14:41:31.871  7378  7378 I dhcpcd  : wlan0: acknowledged 192.168.1.135 from 192.168.1.1
08-16 14:41:31.872  1038  7346 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 16 Aug 2016 12:41:31 GMT], X-Android-Received-Millis=[1471351291871], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1471351291834]}
08-16 14:41:31.872  1038  7346 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-16 14:41:31.872  1038  7346 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-16 14:41:31.872  1038  1448 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
08-16 14:41:31.872  1038  1448 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-16 14:41:31.872  1038  1448 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 14:41:31.872  1038  1448 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 14:41:31.873  1038  1448 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-16 14:41:31.873  1038  1448 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
08-16 14:41:31.873  1038  1448 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-16 14:41:31.873  1038  1448 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 14:41:31.873  1038  1448 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 14:41:31.873  1038  1448 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 14:41:31.873  1038  1448 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 14:41:31.874  1038  1448 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-16 14:41:31.874  1589  1837 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-16 14:41:31.874  1038  1381 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 14:41:31.874  1038  1381 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 14:41:31.874  1839  1839 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 14:41:31.875  1839  1839 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-16 14:41:31.875  6879  6879 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 14:41:31.881  6879  6879 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 14:41:31.882  7378  7378 I dhcpcd  : wlan0: leased 192.168.1.135 for 172800 seconds
08-16 14:41:31.882  7378  7378 D dhcpcd  : wlan0: adding IP address 192.168.1.135/24
08-16 14:41:31.882  7378  7378 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-16 14:41:31.882  7378  7378 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-16 14:41:31.883  7378  7378 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-16 14:41:31.883  7378  7378 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-16 14:41:31.883  7378  7378 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-16 14:41:31.883  7378  7378 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-16 14:41:31.894  6932  6932 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 14:41:31.894  6932  6932 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 14:41:31.894  6932  6932 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-16 14:41:31.901  6411  6411 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 14:41:31.909  6879  6879 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 14:41:31.916  1589  1589 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-16 14:41:31.917  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 14:41:31.917  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 14:41:31.919  6879  6879 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 14:41:31.969  1038  1562 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7395 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,08-16 14:41:31.982  6932  6932 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-16 14:41:31.982  6932  6932 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 14:41:31.982  6932  6932 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-16 14:41:31.988  6411  6411 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-16 14:41:31.998  6879  6879 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 14:41:32.006  6879  6879 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 14:41:32.012  6932  6932 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 14:41:32.012  6932  6932 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 14:41:32.012  6932  6932 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-16 14:41:32.018  6411  6411 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-16 14:41:32.020  7395  7395 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-16 14:41:32.020  7395  7395 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
08-16 14:41:32.028  6879  6879 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 14:41:32.045  7395  7395 I MultiDex: VM with version 2.1.0 has multidex support
08-16 14:41:32.045  7395  7395 I MultiDex: install
08-16 14:41:32.045  6879  6879 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 14:41:32.045  7395  7395 I MultiDex: VM has multidex support, MultiDex support library is disabled.
08-16 14:41:32.059  6932  6932 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 14:41:32.060  6932  6932 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-16 14:41:32.063  6932  6932 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-16 14:41:32.063  7395  7395 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
08-16 14:41:32.067  6411  6411 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 14:41:32.073  6879  6879 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 14:41:32.077  6879  6879 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 14:41:32.082  6932  6932 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 14:41:32.083  6932  6932 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 14:41:32.083  6932  6932 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-16 14:41:32.086  6411  6411 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-16 14:41:32.091  6899  6899 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-16 14:41:32.094  6899  6899 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-16 14:41:32.096  6879  6879 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 14:41:32.101  6879  6879 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 14:41:32.106  6932  6932 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 14:41:32.106  6932  6932 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-16 14:41:32.107  6932  6932 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-16 14:41:32.108  6932  6932 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-16 14:41:32.108  6932  6932 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-16 14:41:32.113  6411  6411 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 14:41:32.116  6899  6899 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-16 14:41:32.117  6899  6899 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-16 14:41:32.119  6879  6879 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 14:41:32.124  6879  6879 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 14:41:32.129  6932  6932 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 14:41:32.130  6932  6932 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 14:41:32.131  6932  6932 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,08-16 14:41:32.132  6932  6932 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-16 14:41:32.132  6932  6932 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,08-16 14:41:32.134  1038  1909 I ActivityManager: Killing 6857:com.lge.lifetracker/u0a37 (adj 15): empty #17
08-16 14:41:32.175  1038  7347 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,08-16 14:41:32.178  1038  7347 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-16 14:41:32.178  1038  7347 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-16 14:41:32.178  1038  7347 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.135
08-16 14:41:32.178  1038  7347 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-16 14:41:32.179  1038  7347 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-16 14:41:32.179  1038  7347 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-16 14:41:32.179  1038  7347 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-16 14:41:32.180  1038  7347 D DhcpStateMachine: RunningState
08-16 14:41:32.202  1038  1890 W libprocessgroup: failed to open /acct/uid_10037/pid_6857/cgroup.procs: No such file or directory
,08-16 14:41:32.206  2178  2178 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
08-16 14:41:32.221  2178  2178 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
08-16 14:41:32.222  2178  2178 D c       : Getting all permits...
08-16 14:41:32.222  2178  2178 D a       : Opening database...
,08-16 14:41:32.231  2178  2178 D a       : Opening database auth.proximity.permit_store...
,08-16 14:41:32.233  2178  2178 D a       : Closing database...
08-16 14:41:32.560  7395  7413 D LgDataFeature: LgDataFeature() Constructor: none
08-16 14:41:32.561  7395  7413 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 14:41:32.615  7435  7435 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=32 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-16 14:41:32.708  7435  7435 I dex2oat : dex2oat took 92.438ms (threads: 4)
,08-16 14:41:32.721  1038  1448 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-16 14:41:32.729  7395  7413 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-16 14:41:32.729  7395  7413 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-16 14:41:32.729  7395  7413 I Adreno-EGL: Build Date: 12/12/14 금
08-16 14:41:32.729  7395  7413 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-16 14:41:32.729  7395  7413 I Adreno-EGL: Remote Branch: 
08-16 14:41:32.729  7395  7413 I Adreno-EGL: Local Patches: 
08-16 14:41:32.729  7395  7413 I Adreno-EGL: Reconstruct Branch: 
,08-16 14:41:32.864  7395  7413 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-16 14:41:32.864  7395  7413 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-16 14:41:32.864  7395  7413 I Adreno-EGL: Build Date: 12/12/14 금
08-16 14:41:32.864  7395  7413 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-16 14:41:32.864  7395  7413 I Adreno-EGL: Remote Branch: 
08-16 14:41:32.864  7395  7413 I Adreno-EGL: Local Patches: 
08-16 14:41:32.864  7395  7413 I Adreno-EGL: Reconstruct Branch: 
,08-16 14:41:32.962  7395  7413 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-16 14:41:32.962  7395  7413 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-16 14:41:32.962  7395  7413 I Adreno-EGL: Build Date: 12/12/14 금
08-16 14:41:32.962  7395  7413 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-16 14:41:32.962  7395  7413 I Adreno-EGL: Remote Branch: 
08-16 14:41:32.962  7395  7413 I Adreno-EGL: Local Patches: 
08-16 14:41:32.962  7395  7413 I Adreno-EGL: Reconstruct Branch: 
,08-16 14:41:33.022  1038  1381 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-16 14:41:33.022  1038  1381 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-16 14:41:33.022  1038  1381 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 14:41:33.023  1038  1381 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 14:41:33.023  1038  1381 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-16 14:41:33.023  1038  1381 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 14:41:33.024  1038  1448 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
08-16 14:41:33.024  1038  1448 D ConnectivityService: identical MTU - not setting,
08-16 14:41:33.024  1038  1448 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-16 14:41:33.024  1038  1448 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-16 14:41:33.024  1038  1448 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 14:41:33.024  1038  1448 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 14:41:33.024  1038  1448 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 14:41:33.026  1589  1837 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,08-16 14:41:33.231   321  7442 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-16 14:41:33.231   321  7442 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
,08-16 14:41:33.267   321  7442 D libc-netbsd: res_queryN name = android.clients.google.com succeed
,08-16 14:41:33.425  1803  7373 I CheckinTask: Sending checkin request (7901 bytes)
,08-16 14:41:33.671  1803  7373 I CheckinTask: Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,08-16 14:41:33.685  1803  7373 I CheckinService: active receiver: disabled
,08-16 14:41:33.708  2178  2178 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,08-16 14:41:33.727  2178  2178 I GCM     : GCM config loaded
,08-16 14:41:33.751   321  7453 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-16 14:41:33.751   321  7453 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
,08-16 14:41:33.759  7118  7118 V SetupWizard: Connected to Gservices successfully
08-16 14:41:33.782   321  7453 D libc-netbsd: res_queryN name = mtalk.google.com succeed
,08-16 14:41:34.072  2178  7456 D GCM     : Connected
,08-16 14:41:34.104  2178  7456 D GCM     : Message class com.google.e.a.a.q
,08-16 14:41:34.569  1038  1381 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-55 f=2447 sc=60 link=72 tx=49.0, 0.0, 0.0  rx=50.5 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1822487959] gl rssi=-55 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-16 14:41:34.581  1038  1381 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-55 f=2447 sc=60 link=72 tx=49.0, 0.0, 0.0  rx=50.5 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1822487948] gl rssi=-55 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-16 14:41:34.581  1038  1381 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-16 14:41:34.605  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-16 14:41:34.670  1038  1424 V WifiInternetCheck: Single check msg out of sync, ignoring.
,08-16 14:41:34.712  1038  1448 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-16 14:41:34.726  1038  1120 D Tethering: MasterInitialState.processMessage what=3
08-16 14:41:34.744  6608  6608 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:41:34.745  6608  6608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 14:41:34.745  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:41:34.745  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 14:41:34.745  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 14:41:34.745  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 14:41:34.745  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 14:41:34.745  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 14:41:34.745  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 14:41:34.745  6608  6608 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:41:34.745  6608  6608 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 14:41:34.750  6608  6608 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:41:34.750  6608  6608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 14:41:34.750  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:41:34.750  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 14:41:34.750  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 14:41:34.750  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 14:41:34.750  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 14:41:34.750  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 14:41:34.750  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 14:41:34.750  6608  6608 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:41:34.750  6608  6608 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 14:41:34.753  6608  6608 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:41:34.753  6608  6608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 14:41:34.753  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:41:34.753  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 14:41:34.753  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 14:41:34.753  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 14:41:34.753  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 14:41:34.753  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 14:41:34.753  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 14:41:34.754  6608  6608 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:41:34.754  6608  6608 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 14:41:34.759  1038  1107 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-16 14:41:34.766  6411  6411 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-16 14:41:34.767  6411  6455 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-16 14:41:34.778  5680  5680 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,08-16 14:41:34.798  2178  2178 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-16 14:41:34.823  1038  1981 D WifiServiceImplEx: setWifiEnabled: false pid=6608, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-16 14:41:34.823  1038  1981 D WifiService: setWifiEnabled: false pid=6608, uid=10118
08-16 14:41:34.823  1038  1981 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-16 14:41:34.834  1038  1038 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-16 14:41:34.834  1038  1038 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-16 14:41:34.834  1038  1038 D Ulp_jni : JNI:system_update. Event-4
08-16 14:41:34.835  1038  1381 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-16 14:41:34.836  1038  1381 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-16 14:41:34.836  1038  1381 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-16 14:41:34.836  1038  1381 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-16 14:41:34.837  1038  1381 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-16 14:41:34.837  1038  1381 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-16 14:41:34.837  1038  1381 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-16 14:41:34.837  1038  1381 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-16 14:41:34.838  1038  1381 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-16 14:41:34.838  1038  1381 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
,08-16 14:41:34.846  1038  1381 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-16 14:41:34.846  1038  1381 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-16 14:41:34.847  7268  7268 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-16 14:41:34.847  1038  1377 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:41:34.847  1038  1377 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:41:34.847  1038  1381 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-16 14:41:34.847  1038  1381 D WifiNative-wlan0: doBoolean: SET ps 1
08-16 14:41:34.848  1038  1381 D WifiNative-wlan0: SET ps 1: returned true
08-16 14:41:34.848   321   895 D CommandListener: Clearing all IP addresses on wlan0
08-16 14:41:34.860  1038  7347 D DhcpStateMachine: RunningState{ when=-12ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,08-16 14:41:34.886  7047  7047 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-16 14:41:34.886  7047  7047 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-16 14:41:34.886  7047  7047 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-16 14:41:34.886  7047  7047 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-16 14:41:34.889  7047  7047 I AppUp4:CustModeStarterReceiver: onReceive
08-16 14:41:34.893  7047  7047 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2701228a
08-16 14:41:34.893  7047  7047 D AppUp4:CustFacade: isCustomizationCompleted : false
08-16 14:41:34.893  7047  7047 D AppUp4:CustFacade: isPhone : true
08-16 14:41:34.893  7047  7047 D AppUp4:CustModeStarterReceiver: begin check event
08-16 14:41:34.893  7047  7047 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-16 14:41:34.903  4286  4286 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-16 14:41:34.903  4286  4286 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-16 14:41:34.905  4286  4286 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-16 14:41:34.909  1038  1448 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-16 14:41:34.909  1038  1448 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
08-16 14:41:34.913  1927  1927 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-16 14:41:34.913  1038  1038 D WifiHS20: hidePasspointNotification off =false
08-16 14:41:34.914  1038  1038 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:41:34.914  1038  1038 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:41:34.914  1038  1038 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-16 14:41:34.915  1038  1038 D WifiHS20: hidePasspointNotification off =false
08-16 14:41:34.915  1038  1038 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:41:34.915  1038  1038 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:41:34.915  1038  1038 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-16 14:41:34.917  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 14:41:34.917  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 14:41:34.918  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 14:41:34.920  4286  4286 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-16 14:41:34.931  1038  1038 D WifiScanningService: SCAN_AVAILABLE : 1
08-16 14:41:34.931  1038  1038 D RttService: SCAN_AVAILABLE : 1
08-16 14:41:34.931  1038  1381 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 14:41:34.931  1038  1381 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 14:41:34.932  1038  1381 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 14:41:34.932  1038  1381 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-16 14:41:34.937  1038  1543 D RttService: EnabledState got{ when=-7ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,08-16 14:41:34.940  1038  1542 D WifiScanningService: DefaultState got{ when=-10ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:41:34.940  1038  1377 D LGWifiP2pService: InactiveState{ when=-10ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:41:34.940  1038  1377 D LGWifiP2pService: P2pEnabledState{ when=-10ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:41:34.940  1038  1377 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@3bac0238
08-16 14:41:34.941  1038  1377 D LGWifiP2pService: P2pDisablingState
08-16 14:41:34.941  1038  1377 D LGWifiP2pService: P2pDisablingState{ when=-1ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:41:34.941  1038  1377 D LGWifiP2pService: p2p socket connection lost
08-16 14:41:34.941  1038  1377 D LGWifiP2pService: P2pDisabledState
08-16 14:41:34.942  1038  1381 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-16 14:41:34.942  1038  1377 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:41:34.942  1038  1377 D LGWifiP2pService: DefaultState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:41:34.942  1038  1381 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-16 14:41:34.942  7268  7268 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-16 14:41:34.943  1038  1381 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-16 14:41:34.943  1038  1381 D WifiNative-wlan0: doBoolean: SET ps 1
08-16 14:41:34.943  1038  1381 D WifiNative-wlan0: SET ps 1: returned true
08-16 14:41:34.944  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 14:41:34.944  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 14:41:34.947  1927  1927 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-16 14:41:34.947  1927  1927 D WfdsService: WifiP2pState is changed : false
08-16 14:41:34.948  1927  2284 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-16 14:41:34.948  1927  2284 D WfdsService: Set the WFDS Monitor: false
08-16 14:41:34.949  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 14:41:34.951  1927  2284 D WfdsMonitor: WFDS Monitor is stopped
08-16 14:41:34.951  1927  2284 D WfdsService: STATE : WfdsDisabledState - enter
,08-16 14:41:34.951  1927  7311 D CtrlSupplicant: Received on exit socket, terminate
08-16 14:41:34.951  1927  7311 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-16 14:41:34.951  1927  7311 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-16 14:41:34.951  1927  7311 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-16 14:41:34.952  1927  2285 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-16 14:41:34.952  1927  2284 W WfdsService: DefaultState - msg [9445378] is not handled
08-16 14:41:34.957  1038  1908 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 101]) by 10005
08-16 14:41:34.957  1038  7346 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:41:34.957  1038  7346 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:41:34.957  1038  7346 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-16 14:41:34.958  1038  7346 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:41:34.958  1038  7346 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on <unknown ssid>
08-16 14:41:34.967  4286  7484 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-16 14:41:34.970  4286  7485 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-16 14:41:34.971  4286  7485 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-16 14:41:34.971  1038  1448 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-16 14:41:34.971  1038  1448 D DSQN    : disableDataServiceNotify
08-16 14:41:34.971  1038  1448 D DSQN    : stop dsqn bin
08-16 14:41:34.972   321   895 D CommandListener: Clearing all IP addresses on wlan0
08-16 14:41:34.974  1038  1381 D WifiNative-p2p0: doBoolean: TERMINATE
,08-16 14:41:34.975   321  7486 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-16 14:41:34.975  1038  1118 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-16 14:41:34.976  1038  7346 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
08-16 14:41:34.976  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-16 14:41:34.976  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 14:41:34.977  1038  1038 D WifiHS20: hidePasspointNotification off =false
08-16 14:41:34.977  1038  1038 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:41:34.977  1038  1038 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:41:34.977  1038  1038 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-16 14:41:34.978  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 14:41:34.979  1038  1381 D WifiNative-p2p0: TERMINATE: returned true
08-16 14:41:34.979  1038  1381 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-16 14:41:34.979  1038  1381 E WifiStateMachine: useWiFiOffloading() : false
08-16 14:41:34.979  1038  1381 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-16 14:41:34.981  1038  1448 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
08-16 14:41:34.981  1038  1448 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 14:41:34.981  1038  1448 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 14:41:34.981  1038  1448 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 14:41:34.981  1038  1448 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-16 14:41:34.981  1038  7346 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,08-16 14:41:34.981  1038  7346 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:41:34.982  1038  7346 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-16 14:41:34.982  1589  1837 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-16 14:41:34.982  7086  7086 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-16 14:41:34.982  1038  1448 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-16 14:41:34.982  1038  1448 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-16 14:41:34.982  1038  1448 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-16 14:41:34.971  1038  1107 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 14:41:34.983  1927  1927 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-16 14:41:34.984  1038  1038 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-16 14:41:34.984  1038  1038 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 14:41:34.984  1038  1038 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-16 14:41:34.985  6608  6608 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:41:34.985  6608  6608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 14:41:34.985  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:41:34.985  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 14:41:34.985  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 14:41:34.985  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 14:41:34.985  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 14:41:34.985  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 14:41:34.985  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 14:41:34.985  6608  6608 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:41:34.985  6608  6608 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 14:41:34.990  1038  1448 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-16 14:41:34.990  1038  1448 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-16 14:41:34.990  1038  1375 V Network,Policy: [LG_RESTRICTED] !!!isConnected  type  :1
08-16 14:41:34.991  6608  6608 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:41:34.991  6608  6608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 14:41:34.991  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:41:34.991  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 14:41:34.991  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 14:41:34.991  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 14:41:34.991  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 14:41:34.991  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 14:41:34.991  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 14:41:34.991  6608  6608 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:41:34.991  6608  6608 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 14:41:34.991  1038  1038 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-16 14:41:34.991  1038  1448 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-16 14:41:34.991  1038  1038 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-16 14:41:34.991  1038  1448 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 14:41:34.991  1038  1038 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-16 14:41:34.991  1038  1038 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-16 14:41:34.992  1038  1448 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 14:41:34.993  1038  1038 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-16 14:41:34.994  1038  1038 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-16 14:41:34.994  1038  1038 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-16 14:41:34.994  1038  1038 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-16 14:41:34.994  1038  1375 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-16 14:41:34.994  1038  1381 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 14:41:34.994  1038  1381 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 14:41:34.995  1038  1448 D NetworkManagementService: Removing idletimer
08-16 14:41:34.995  1038  1448 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:41:34.996  1038  1448 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-16 14:41:34.996  1839  1839 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 14:41:34.996  1839  1839 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-16 14:41:34.997  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 14:41:34.997  6608  6608 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:41:34.997  6608  6608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 14:41:34.997  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:41:34.997  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 14:41:34.997  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 14:41:34.997  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 14:41:34.997  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 14:41:34.997  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 14:41:34.997  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 14:41:34.997  6608  6608 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:41:34.998  6608  6608 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 14:41:35.011  7086  7487 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:41:35.013  3346  3346 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-16 14:41:35.013  3346  3346 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-16 14:41:35.013  3346  3346 I LgeMiscReceiver: networkInfo.isConnected() = true
08-16 14:41:35.014  3346  3346 D PhoneState: setPdpRejectCasuse : false
08-16 14:41:35.016  7118  7118 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-16 14:41:35.016  7118  7118 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-16 14:41:35.016  6976  7489 W FormManager: Network not available. Please check & try again.
08-16 14:41:35.022  7268  7268 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,08-16 14:41:35.022  7268  7268 I wpa_supplicant: monitor socket send errors count : 1
08-16 14:41:35.022  7268  7268 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1927-4\x00 that cannot receive messages
08-16 14:41:35.023  1038  7301 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-16 14:41:35.024  6976  7490 V FormManager: Network unavailable.
08-16 14:41:35.024  1038  7301 D WifiMonitor: Dropping event because (p2p0) is stopped
08-16 14:41:35.027  7184  7184 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:41:35
08-16 14:41:35.029  6976  7490 V FormManager: Network unavailable.
08-16 14:41:35.029  7184  7184 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-16 14:41:35.029  7184  7184 D Weather.Utils: 2 : All the weather widget is gone.
08-16 14:41:35.030  7184  7184 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-16 14:41:35.030  7184  7184 D WeatherAncestor: connectivity changed - connection : true
08-16 14:41:35.030  7184  7184 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@316e4518
08-16 14:41:35.031  7184  7184 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-16 14:41:35.031  7184  7184 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-16 14:41:35.031  7184  7184 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-16 14:41:35.031  7184  7184 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-16 14:41:35.031  7184  7184 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:41:35
08-16 14:41:35.047  7268  7268 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-16 14:41:35.047  1038  7301 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-16 14:41:35.047  1038  7301 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-16 14:41:35.047  1038  7301 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-16 14:41:35.047  1038  7301 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-16 14:41:35.048  7268  7268 W wpa_supplicant: USIM:  scard_deinit function
08-16 14:41:35.049  1038  7301 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 14:41:35.049  1038  7301 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-16 14:41:35.049  1038  1381 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=172216
08-16 14:41:35.049  1038  1381 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=172217
08-16 14:41:35.050  1038  1381 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=172217  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-16 14:41:35.050  1038  1120 D Tethering: InitialState.processMessage what=4
08-16 14:41:35.051  1038  1120 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-16 14:41:35.052  1038  1381 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=172219  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-16 14:41:35.053  1038  1381 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-16 14:41:35.053  1038  1381 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-16 14:41:35.056  6411  6411 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 14:41:35.060  6899  6899 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-16 14:41:35.060  6899  6899 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-16 14:41:35.060  6899  6899 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-16 14:41:35.064  6879  6879 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 14:41:35.071  1589  1589 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,08-16 14:41:35.071  6879  6879 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-16 14:41:35.072  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 14:41:35.072  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 14:41:35.080  6932  6932 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 14:41:35.081  6932  6932 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 14:41:35.083  6932  6932 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-16 14:41:35.087  6411  6411 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-16 14:41:35.091  6899  6899 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-16 14:41:35.091  6899  6899 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
,08-16 14:41:35.091  7268  7268 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-16 14:41:35.091  6899  6899 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-16 14:41:35.091  1038  7301 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-16 14:41:35.091  1038  7301 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-TERMINATING 
08-16 14:41:35.092  1038  7301 D WifiMonitor: Disconnecting from the supplicant, no more events
08-16 14:41:35.092  1038  1381 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 44 0
08-16 14:41:35.096  1038  7347 D DhcpStateMachine: StoppedState
08-16 14:41:35.096  1038  7347 D DhcpStateMachine: StoppedState{ when=-153ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:41:35.100  6879  6879 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 14:41:35.106  6879  6879 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 14:41:35.111  1589  1589 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-16 14:41:35.113  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-16 14:41:35.113  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 14:41:35.115  6932  6932 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 14:41:35.115  6932  6932 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 14:41:35.116  6932  6932 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-16 14:41:35.120  6411  6411 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 14:41:35.125  6899  6899 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-16 14:41:35.125  6899  6899 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-16 14:41:35.125  6899  6899 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-16 14:41:35.130  6879  6879 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-16 14:41:35.136  6879  6879 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 14:41:35.144  6932  6932 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 14:41:35.144  6932  6932 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 14:41:35.146  6932  6932 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-16 14:41:35.154  6899  6899 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-16 14:41:35.159  6879  6879 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-16 14:41:35.165  6976  7493 W FormManager: Network not available. Please check & try again.
08-16 14:41:35.172  6976  7494 V FormManager: Network unavailable.
,08-16 14:41:35.175  6976  7494 V FormManager: Network unavailable.
08-16 14:41:35.178  6879  6879 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 14:41:35.194  1038  1381 D WifiOffDelayIfNotUsed: stopMonitoring
,08-16 14:41:35.194  1038  1381 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-16 14:41:35.194  1038  1381 E WifiStateMachine: useWiFiOffloading() : false
08-16 14:41:35.194  1038  1381 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-16 14:41:35.194  1927  1927 D WfdsService: Supplicant Connection state is changed : false
08-16 14:41:35.195  1927  2284 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
,08-16 14:41:35.195  1927  2284 D WfdsService: Set the WFDS Monitor: false
08-16 14:41:35.195  1927  2284 D WfdsMonitor: WFDS Monitor is stopped
08-16 14:41:35.196  1927  1927 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-16 14:41:35.196  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 14:41:35.197  1038  1038 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-16 14:41:35.197  1038  1428 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-16 14:41:35.197  1038  1428 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-16 14:41:35.199  2494  2494 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:41:35.204  6608  6608 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:41:35.204  6608  6608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 14:41:35.204  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:41:35.204  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 14:41:35.204  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 14:41:35.204  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 14:41:35.204  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 14:41:35.204  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 14:41:35.204  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 14:41:35.205  6608  6608 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:41:35.205  6608  6608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 14:41:35.205  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:41:35.205  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 14:41:35.205  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 14:41:35.205  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 14:41:35.205  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 14:41:35.205  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 14:41:35.205  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 14:41:35.206  6608  6608 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:41:35.206  6608  6608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 14:41:35.206  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:41:35.206  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 14:41:35.206  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 14:41:35.206  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 14:41:35.206  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 14:41:35.206  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: f,alse
08-16 14:41:35.206  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 14:41:35.210  6879  6879 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-16 14:41:35.210  6879  6879 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-16 14:41:35.210  6879  6879 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-16 14:41:35.210  6879  6879 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-16 14:41:35.211  6879  6879 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-16 14:41:35.212  6879  6879 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-16 14:41:35.212  6879  6879 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-16 14:41:35.212  6879  6879 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-16 14:41:35.212  6879  6879 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-16 14:41:35.212  6879  6879 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-16 14:41:35.212  6879  6879 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-16 14:41:35.218  4286  4286 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-16 14:41:35.218  4286  4286 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-16 14:41:35.221  4286  4286 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 14:41:35.224  4286  4286 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 14:41:35.230  4286  7495 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-16 14:41:35.235  6899  6899 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-16 14:41:35.235  6899  6899 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
,08-16 14:41:35.235  6899  6899 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-16 14:41:35.236  4286  7496 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-16 14:41:35.237  4286  7496 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-16 14:41:35.242  6879  6879 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-16 14:41:35.246  6976  7498 W FormManager: Network not available. Please check & try again.
,08-16 14:41:35.248  6879  6879 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 14:41:35.255  6976  7499 V FormManager: Network unavailable.
08-16 14:41:35.259  6976  7499 V FormManager: Network unavailable.
08-16 14:41:35.285  7220  7243 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,08-16 14:41:35.398  1038  1381 E WifiStateMachine:  InitialState CMD_ON_QUIT 0 0
,08-16 14:41:35.399  1038  1381 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
,08-16 14:41:35.617  1038  1109 W ProcessCpuTracker: Skipping unknown process pid 7462
,08-16 14:41:35.627  1038  1109 W ProcessCpuTracker: Skipping unknown process pid 7465
,08-16 14:41:35.629  1038  1109 W ProcessCpuTracker: Skipping unknown process pid 7471
08-16 14:41:35.629  1038  1109 W ProcessCpuTracker: Skipping unknown process pid 7472
08-16 14:41:35.631  1038  1109 W ProcessCpuTracker: Skipping unknown process pid 7477
08-16 14:41:35.631  1038  1109 W ProcessCpuTracker: Skipping unknown process pid 7480
08-16 14:41:35.632  1038  1109 W ProcessCpuTracker: Skipping unknown process pid 7481
08-16 14:41:35.632  1038  1109 W ProcessCpuTracker: Skipping unknown process pid 7502
08-16 14:41:35.633  1038  1109 W ProcessCpuTracker: Skipping unknown process pid 7505
08-16 14:41:36.273  1038  1944 I ActivityManager: Killing 6949:com.lge.settings.easy/1000 (adj 15): empty #17
,08-16 14:41:36.306  1038  1908 W libprocessgroup: failed to open /acct/uid_1000/pid_6949/cgroup.procs: No such file or directory
,08-16 14:41:37.615  1038  1381 E WifiStateMachine:  InitialState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1822484913] gl rssi=-54 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-16 14:41:37.618  1038  1381 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1822484911] gl rssi=-54 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-16 14:41:37.993  1038  1448 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-16 14:41:38.007  1038  1120 D Tethering: MasterInitialState.processMessage what=3
08-16 14:41:38.022  6608  6608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 14:41:38.027  6608  6608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:41:38.029  6608  6608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:41:38.031  1038  1448 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-16 14:41:38.033  1038  1107 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-16 14:41:38.036  1038  1120 D Tethering: MasterInitialState.processMessage what=3
,08-16 14:41:38.047  6608  6608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:41:38.049  6608  6608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 14:41:38.052  6608  6608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:41:38.055  6411  6411 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-16 14:41:38.057  6411  6455 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-16 14:41:38.068  5680  5680 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-16 14:41:38.082  5680  5680 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-16 14:41:38.099  2178  2178 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-16 14:41:38.118  7047  7047 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-16 14:41:38.118  7047  7047 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-16 14:41:38.118  7047  7047 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-16 14:41:38.118  7047  7047 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-16 14:41:38.123  7047  7047 I AppUp4:CustModeStarterReceiver: onReceive
08-16 14:41:38.126  7047  7047 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2701228a
08-16 14:41:38.126  7047  7047 D AppUp4:CustFacade: isCustomizationCompleted : false
08-16 14:41:38.126  7047  7047 D AppUp4:CustFacade: isPhone : true
08-16 14:41:38.127  7047  7047 D AppUp4:CustModeStarterReceiver: begin check event
08-16 14:41:38.127  7047  7047 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-16 14:41:38.132  4286  4286 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-16 14:41:38.132  4286  4286 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-16 14:41:38.134  4286  4286 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-16 14:41:38.139  4286  4286 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 14:41:38.147  7086  7086 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-16 14:41:38.157  1038  1107 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-16 14:41:38.159  1038  1107 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-16 14:41:38.159  1038  1107 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 14:41:38.161  4286  7523 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-16 14:41:38.172  4286  7524 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,08-16 14:41:38.172  4286  7524 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-16 14:41:38.186  7086  7527 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 14:41:38.192  3346  3346 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-16 14:41:38.192  3346  3346 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-16 14:41:38.192  3346  3346 I LgeMiscReceiver: networkInfo.isConnected() = false
08-16 14:41:38.195  6976  7529 W FormManager: Network not available. Please check & try again.
08-16 14:41:38.199  7118  7118 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-16 14:41:38.199  7118  7118 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-16 14:41:38.205  6976  7530 V FormManager: Network unavailable.
08-16 14:41:38.213  7184  7184 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:41:38
,08-16 14:41:38.215  6976  7530 V FormManager: Network unavailable.
08-16 14:41:38.217  7184  7184 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
,08-16 14:41:38.217  7184  7184 D Weather.Utils: 2 : All the weather widget is gone.
08-16 14:41:38.217  7184  7184 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-16 14:41:38.218  7184  7184 D WeatherAncestor: connectivity changed - connection : true
08-16 14:41:38.218  7184  7184 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@316e4518
08-16 14:41:38.218  7184  7184 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-16 14:41:38.218  7184  7184 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-16 14:41:38.218  7184  7184 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-16 14:41:38.219  7184  7184 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-16 14:41:38.219  7184  7184 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:41:38
08-16 14:41:38.237  1038  1588 I ActivityManager: Killing 7350:com.lge.bnr/1000 (adj 15): empty #17
,08-16 14:41:38.262  1038  1908 W libprocessgroup: failed to open /acct/uid_1000/pid_7350/cgroup.procs: No such file or directory
,08-16 14:41:38.275  6411  6411 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-16 14:41:38.279  6411  6455 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-16 14:41:38.297  2178  2178 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-16 14:41:38.310  7047  7047 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-16 14:41:38.310  7047  7047 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-16 14:41:38.310  7047  7047 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-16 14:41:38.310  7047  7047 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-16 14:41:38.313  7047  7047 I AppUp4:CustModeStarterReceiver: onReceive
,08-16 14:41:38.318  7047  7047 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2701228a
08-16 14:41:38.318  7047  7047 D AppUp4:CustFacade: isCustomizationCompleted : false
08-16 14:41:38.318  7047  7047 D AppUp4:CustFacade: isPhone : true
08-16 14:41:38.319  7047  7047 D AppUp4:CustModeStarterReceiver: begin check event
08-16 14:41:38.319  7047  7047 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-16 14:41:38.323  4286  4286 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,08-16 14:41:38.324  4286  4286 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-16 14:41:38.327  4286  4286 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 14:41:38.330  4286  4286 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 14:41:38.337  4286  7536 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-16 14:41:38.342  4286  7537 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-16 14:41:38.342  4286  7537 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-16 14:41:38.342  7086  7086 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-16 14:41:38.370  7086  7538 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 14:41:38.380  6976  7540 W FormManager: Network not available. Please check & try again.,
08-16 14:41:38.386  3346  3346 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-16 14:41:38.386  3346  3346 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-16 14:41:38.387  3346  3346 I LgeMiscReceiver: networkInfo.isConnected() = false
,08-16 14:41:38.392  7118  7118 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,08-16 14:41:38.393  7118  7118 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-16 14:41:38.408  6976  7541 V FormManager: Network unavailable.
,08-16 14:41:38.413  7184  7184 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:41:38
08-16 14:41:38.417  6976  7541 V FormManager: Network unavailable.
08-16 14:41:38.418  7184  7184 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-16 14:41:38.418  7184  7184 D Weather.Utils: 2 : All the weather widget is gone.
08-16 14:41:38.419  7184  7184 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-16 14:41:38.419  7184  7184 D WeatherAncestor: connectivity changed - connection : true
08-16 14:41:38.419  7184  7184 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@316e4518
08-16 14:41:38.421  7184  7184 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-16 14:41:38.421  7184  7184 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
,08-16 14:41:38.421  7184  7184 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
,08-16 14:41:38.421  7184  7184 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
,08-16 14:41:38.421  7184  7184 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:41:38
,08-16 14:41:39.840  1038  2019 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 14:41:39.841  1038  2019 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-16 14:41:39.873  1038  1038 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-16 14:41:39.874  1038  1038 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-16 14:41:39.874  1038  1038 D Ulp_jni : JNI:system_update. Event-4
08-16 14:41:39.874  1038  1120 D BluetoothManagerService: Message: 1
08-16 14:41:39.875  1038  1120 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-16 14:41:39.902  1038  1120 D BluetoothManagerService: Message: 20
08-16 14:41:39.902  1038  1120 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2f8e03b0:true
,08-16 14:41:39.907  6999  6999 D BluetoothAdapterState: make
08-16 14:41:39.913  6999  6999 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-16 14:41:39.913  6999  6999 I bluedroid-qcom: init
08-16 14:41:39.915  6999  7553 I BluetoothAdapterState: Entering OffState
,08-16 14:41:39.917  6999  6999 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-16 14:41:39.917  6999  6999 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-16 14:41:39.917  6999  6999 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-16 14:41:39.917  6999  6999 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-16 14:41:39.917  6999  6999 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-16 14:41:39.920  6999  6999 I bluedroid-qcom: get_profile_interface socket
08-16 14:41:39.920  6999  6999 I bluedroid-qcom: get_profile_interface map_client
08-16 14:41:39.922  6999  7557 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-16 14:41:39.924  6999  7557 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-16 14:41:39.919  7556  7556 W bdaddr_loader: type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 14:41:39.919  7556  7556 W bdaddr_loader: type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-16 14:41:39.940  1038  1038 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-16 14:41:39.941  1038  1038 D BluetoothManagerService: Stored Bluetooth name: G3
,08-16 14:41:39.945  1038  1038 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-16 14:41:39.945  1038  1120 D BluetoothManagerService: Message: 40
08-16 14:41:39.945  1038  1120 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-16 14:41:39.946  6999  7015 I bluedroid-qcom: config_hci_snoop_log
08-16 14:41:39.946  1038  1377 D LGWifiP2pService: P2pDisabledState{ when=-5ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:41:39.946  1038  1377 D LGWifiP2pService: DefaultState{ when=-5ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:41:39.948  1038  1120 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-16 14:41:39.948  1038  1120 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-16 14:41:39.949  7556  7556 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-16 14:41:39.949  7556  7556 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-16 14:41:39.949  7556  7556 I LGFTMITEM: [GET_FTM][id=8], offset=16384
08-16 14:41:39.952  7556  7556 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-16 14:41:39.957  7556  7556 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-16 14:41:39.957  7556  7556 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
,08-16 14:41:39.963  6999  7553 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-16 14:41:39.963  6999  7557 D BluetoothAdapterProperties: Name is: G3
08-16 14:41:39.964  6999  7553 D BluetoothAdapterProperties: Setting state to 11
08-16 14:41:39.964  6999  7553 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-16 14:41:39.965  1038  1120 D BluetoothManagerService: Message: 60
08-16 14:41:39.965  1038  1120 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-16 14:41:39.965  1038  1120 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-16 14:41:39.966  6999  7553 I LGBluetoothServiceJni: classInitNative: succeeds
08-16 14:41:39.973  1927  1927 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-16 14:41:39.976  1589  1589 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-16 14:41:39.980  6608  6608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:41:39.980  1038  1381 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
08-16 14:41:39.981  1038  1381 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
08-16 14:41:39.982  6608  6608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:41:39.983  6608  6608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:41:39.986  6879  6879 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
,08-16 14:41:39.996  6999  6999 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-16 14:41:39.997  6999  6999 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 14:41:39.997  6999  6999 V BluetoothPbapReceiver: ***********state = 11
08-16 14:41:40.005  6999  7553 D BluetoothBondStateMachine: make
,08-16 14:41:40.022  2178  2178 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-16 14:41:40.032  6999  7553 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@316e4518
08-16 14:41:40.032  6999  7553 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-16 14:41:40.032  6999  7553 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@316e4518
08-16 14:41:40.032  6999  7553 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-16 14:41:40.035  6999  7559 I BluetoothBondStateMachine: StableState(): Entering Off State
08-16 14:41:40.036  6999  7553 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-16 14:41:40.042  6999  7553 E BluetoothAdapterService: File transfer profiles supported!!
,08-16 14:41:40.105  1038  1944 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7576 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-16 14:41:40.118  6999  7553 E BluetoothAdapterService: File transfer profiles supported!!
08-16 14:41:40.125  6999  7553 E BluetoothAdapterService: File transfer profiles supported!!
08-16 14:41:40.125  6999  6999 D HeadsetService: Received start request. Starting profile...
,08-16 14:41:40.126  6999  6999 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-16 14:41:40.127  6999  6999 D LGBluetoothHfpAdapter: Version 1.6
08-16 14:41:40.130  6999  7553 E BluetoothAdapterService: File transfer profiles supported!!
08-16 14:41:40.132  6999  6999 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-16 14:41:40.134  6999  6999 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-16 14:41:40.134  6999  6999 D HeadsetStateMachine: make
08-16 14:41:40.136  6999  7553 E BluetoothAdapterService: File transfer profiles supported!!
,08-16 14:41:40.152  6999  7553 E BluetoothAdapterService: File transfer profiles supported!!
08-16 14:41:40.158  6999  7553 E BluetoothAdapterService: File transfer profiles supported!!
,08-16 14:41:40.180  6999  7553 V LGMDMManager: Create singleton instance
08-16 14:41:40.181  6999  6999 D LgDataFeature: LgDataFeature() Constructor: none
,08-16 14:41:40.182  6999  6999 D LgDataFeature: LgDataFeature() Constructor Done, null
08-16 14:41:40.184  6999  7553 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-16 14:41:40.187  6999  6999 D HeadsetStateMachine: max_hf_connections = 1
,08-16 14:41:40.187  6999  6999 I bluedroid-qcom: get_profile_interface handsfree
08-16 14:41:40.190  6999  6999 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-16 14:41:40.190   325   325 V AudioPolicyService: registerClient() client 0xb558ad60, uid 1002
08-16 14:41:40.191   325  1384 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-16 14:41:40.191   325  1384 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-16 14:41:40.191   325  1384 V AudioPolicyManagerEx: getOutput() returns output 2
08-16 14:41:40.191  6999  6999 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-16 14:41:40.191   325  2115 V AudioFlinger: registerClient() client 0xb1433640, pid 6999
08-16 14:41:40.192   325  1378 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 14:41:40.192   325  1378 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 14:41:40.192  3346  3363 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 14:41:40.192  3346  3363 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 14:41:40.193  1038  1944 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 14:41:40.193  1038  1944 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 14:41:40.193  1589  3466 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 14:41:40.193  6999  7015 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 14:41:40.193  1589  3466 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 14:41:40.193  1839  2434 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 14:41:40.193  1839  2434 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 14:41:40.194   325  1379 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 14:41:40.194   325  1379 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-16 14:41:40.194  1038  2037 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 14:41:40.194  1038  2037 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-16 14:41:40.194  1589  2082 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 14:41:40.194  1589  2082 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-16 14:41:40.195  3346  3367 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 14:41:40.195  3346  3367 V AudioSystem: ioConfigChanged() opening already existing output! 4
,08-16 14:41:40.195  1839  1855 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 14:41:40.195  1839  1855 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-16 14:41:40.195  6999  7015 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-16 14:41:40.195  6999  7015 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 14:41:40.195  6999  7015 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-16 14:41:40.195  6999  6999 V ToneGenerator: Create Track: 0xb4928a80
08-16 14:41:40.195  6999  6999 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-16 14:41:40.195  6999  6999 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-16 14:41:40.196   325  1385 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-16 14:41:40.196   325  1385 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-16 14:41:40.196   325  1385 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-16 14:41:40.196   325  1385 V AudioPolicyManagerEx: getOutput() returns output 2
08-16 14:41:40.196   325   325 I AudioFlinger: isAudioPlaybackHookOn() false
08-16 14:41:40.197   325  1384 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-16 14:41:40.197   325  1384 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-16 14:41:40.197   325  1384 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-16 14:41:40.197   325  1384 V AudioPolicyManagerEx: getOutput() returns output 2
08-16 14:41:40.197  6999  6999 V AudioSystem: getLatency() output 2, latency 50
08-16 14:41:40.197  6999  6999 V AudioSystem: getFrameCount() output 2, frameCount 960
08-16 14:41:40.197  6999  6999 V AudioTrack: createTrack_l() output 2 afLatency 50
08-16 14:41:40.198   325  2115 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-16 14:41:40.198   325  2115 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-16 14:41:40.198   325  2115 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-16 14:41:40.198   325  2115 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-16 14:41:40.198   325  2115 V AudioFlinger: createTrack() lSessionId: 20
08-16 14:41:40.199  6999  6999 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-16 14:41:40.199   325  2115 V AudioFlinger: acquiring 20 from 6999, for 6999
08-16 14:41:40.199   325  2115 V AudioFlinger:  added new entry for 20
08-16 14:41:40.199  6999  6999 V ToneGenerator: ToneGenerator INIT OK, time: 177379
08-16 14:41:40.200  6999  6999 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@316e4518
08-16 14:41:40.200  6999  7594 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-16 14:41:40.200  6999  7594 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-16 14:41:40.200  6999  7594 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-16 14:41:40.201  6999  7594 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-16 14:41:40.201   325  2114 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 6999
08-16 14:41:40.202   325  2114 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-16 14:41:40.202   325  2114 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-16 14:41:40.202   325  2114 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-16 14:41:40.202   325  2114 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-16 14:41:40.202   ,325  2114 V voice   : voice_set_parameters: exit with code(0)
08-16 14:41:40.202  6999  6999 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@316e4518
08-16 14:41:40.202   325  2114 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-16 14:41:40.202   325  2114 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-16 14:41:40.202   325  2114 V msm8974_platform: platform_set_parameters: exit with code(0)
08-16 14:41:40.202   325  2114 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-16 14:41:40.202   325  2114 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-16 14:41:40.202   325  2114 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-16 14:41:40.202  6999  7594 V ToneGenerator: ToneGenerator destructor
08-16 14:41:40.202  6999  7594 V ToneGenerator: stopTone
08-16 14:41:40.202  6999  7594 V ToneGenerator: Delete Track: 0xb4928a80
08-16 14:41:40.203  6999  7594 V AudioTrack: ~AudioTrack, releasing session id from 6999 on behalf of 6999
08-16 14:41:40.203   325  1385 V AudioFlinger: releasing 20 from 6999 for 6999
08-16 14:41:40.203   325  1385 V AudioFlinger:  decremented refcount to 0
08-16 14:41:40.203   325  1385 V AudioFlinger: purging stale effects
08-16 14:41:40.203   325  1385 V AudioPolicyService: AudioCommandThread() adding release output 2
08-16 14:41:40.203   325  1385 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-16 14:41:40.203   325  1385 V AudioFlinger: PlaybackThread::Track destructor
08-16 14:41:40.203   325  1271 V AudioPolicyService: AudioCommandThread() waking up
08-16 14:41:40.203   325  1271 V AudioPolicyService: AudioCommandThread() processing release output 2
08-16 14:41:40.203   325  1271 V AudioPolicyManager: releaseOutput() 2
08-16 14:41:40.203   325  1271 V AudioPolicyService: AudioCommandThread() going to sleep
08-16 14:41:40.203   325  1385 V AudioFlinger: removeClient_l() pid 6999, calling pid 325
08-16 14:41:40.204  6999  6999 D A2dpService: Received start request. Starting profile...
08-16 14:41:40.205  6999  6999 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-16 14:41:40.206  6999  6999 V Avrcp   : make
08-16 14:41:40.207  6999  6999 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-16 14:41:40.207  6999  6999 I bluedroid-qcom: get_profile_interface avrcp
,08-16 14:41:40.220  6999  6999 V AudioManager: registerRemoteController: size of Media player list: 0
,08-16 14:41:40.223  6999  6999 E AudioManager: No RCC entry present to update
08-16 14:41:40.223  6999  6999 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-16 14:41:40.228  6999  6999 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
,08-16 14:41:40.229  6999  6999 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-16 14:41:40.229  6999  6999 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-16 14:41:40.235  6999  6999 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,08-16 14:41:40.239  7576  7576 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
,08-16 14:41:40.240  7576  7576 W LG Account v2.2: No ProfileInfo entries
08-16 14:41:40.240  7576  7576 I LG Account v2.2: isEnabled: false
08-16 14:41:40.240  7576  7576 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-16 14:41:40.240  7576  7576 I Feature : [Lifetracker]Country: EU
08-16 14:41:40.240  7576  7576 I Feature : [Lifetracker]Operator: OPEN
08-16 14:41:40.241  7576  7576 I Feature : [Lifetracker]Ranking support: false
08-16 14:41:40.241  7576  7576 I Feature : [Lifetracker]Comfort support: false
08-16 14:41:40.241  7576  7576 I Feature : [Lifetracker]Accessory: true
08-16 14:41:40.241  7576  7576 I Feature : [Lifetracker]Health device: true
08-16 14:41:40.241  7576  7576 I Feature : [Lifetracker]Extra Pedometer: false
08-16 14:41:40.241  7576  7576 I Feature : [Lifetracker]Blood glucose device: false
08-16 14:41:40.241  7576  7576 I Feature : [Lifetracker]Device Number: 3
08-16 14:41:40.315  6879  6879 D BluetoothPermissionRequest: onReceive
,08-16 14:41:40.323  6879  6879 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-16 14:41:40.364  1038  1909 V SIM_STK : Menu title from STK is T-Mobile
08-16 14:41:40.364  1038  1909 V SIM_STK : Menu title from STK is T-Mobile
,08-16 14:41:40.436  1038  1711 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-16 14:41:40.444  6999  6999 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-16 14:41:40.448  6999  6999 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-16 14:41:40.449  6999  6999 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-16 14:41:40.449  6999  6999 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-16 14:41:40.449  6999  6999 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-16 14:41:40.449  6999  6999 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-16 14:41:40.449  6999  6999 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-16 14:41:40.449  6999  6999 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-16 14:41:40.449  6999  6999 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-16 14:41:40.449  6999  6999 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-16 14:41:40.449  6999  6999 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
,08-16 14:41:40.450  6999  6999 I BluetoothA2dpServiceJni: classInitNative
08-16 14:41:40.450  6999  6999 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-16 14:41:40.450  6999  6999 D A2dpStateMachine: make
,08-16 14:41:40.451  6999  6999 I bluedroid-qcom: get_profile_interface a2dp
08-16 14:41:40.451  6999  7605 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-16 14:41:40.457  6999  6999 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-16 14:41:40.457  6999  6999 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-16 14:41:40.458  6999  6999 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@316e4518
08-16 14:41:40.458  6999  6999 I BluetoothHidServiceJni: classInitNative: succeeds
08-16 14:41:40.459  6999  7604 D A2dpStateMachine: Enter Disconnected: -2
08-16 14:41:40.460  6999  6999 D HidService: Received start request. Starting profile...
08-16 14:41:40.460  6999  6999 I bluedroid-qcom: get_profile_interface hidhost
08-16 14:41:40.460  6999  6999 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@316e4518
08-16 14:41:40.460  6999  6999 I BluetoothHealthServiceJni: classInitNative: succeeds
08-16 14:41:40.462  6999  6999 D HealthService: Received start request. Starting profile...
08-16 14:41:40.465  6999  6999 I bluedroid-qcom: get_profile_interface health
08-16 14:41:40.465  6999  6999 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-16 14:41:40.465  6999  6999 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@316e4518
08-16 14:41:40.466  6999  6999 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-16 14:41:40.467  6999  6999 D PanService: Received start request. Starting profile...
08-16 14:41:40.467  6999  6999 D BluetoothPanServiceJni: initializeNative(L110): pan
08-16 14:41:40.467  6999  6999 I bluedroid-qcom: get_profile_interface pan
,08-16 14:41:40.473  6999  6999 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
,08-16 14:41:40.473  6999  6999 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@316e4518
08-16 14:41:40.473  6999  6999 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-16 14:41:40.477  6999  6999 D BtGatt.DebugUtils: handleDebugAction() action=null
08-16 14:41:40.478  6999  6999 D BtGatt.GattService: Received start request. Starting profile...
08-16 14:41:40.478  6999  6999 D BtGatt.GattService: start()
08-16 14:41:40.478  6999  6999 I bluedroid-qcom: get_profile_interface gatt
08-16 14:41:40.478  6999  6999 D BtGatt.AdvertiseManager: advertise manager created
08-16 14:41:40.490  6999  6999 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@316e4518
,08-16 14:41:40.494  6999  6999 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@316e4518
,08-16 14:41:40.495  6999  6999 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-16 14:41:40.498  6999  6999 V BluetoothMapService: BluetoothMapBinder()
08-16 14:41:40.499  6999  6999 D BluetoothMapService: Received start request. Starting profile...
08-16 14:41:40.500  6999  6999 D BluetoothMapService: start()
08-16 14:41:40.506  6999  6999 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-16 14:41:40.506  6999  6999 D BluetoothMapEmailAppObserver: createReceiver()
,08-16 14:41:40.506  6999  6999 D BluetoothMapEmailAppObserver: initObservers()
08-16 14:41:40.506  6999  6999 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-16 14:41:40.512  6999  6999 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@316e4518
08-16 14:41:40.512  6999  6999 D HeadsetStateMachine: Proxy object connected
08-16 14:41:40.513  6999  6999 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-16 14:41:40.513  6999  6999 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-16 14:41:40.514  6999  7594 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-16 14:41:40.515  6999  7594 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-16 14:41:40.516  6999  7594 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-16 14:41:40.516  6999  6999 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-16 14:41:40.520  6999  6999 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-16 14:41:40.524  6999  6999 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-16 14:41:40.526  6999  6999 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-16 14:41:40.529  6999  6999 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-16 14:41:40.529  6999  6999 V PanService: [BTUI] SIM Extra State :ABSENT
08-16 14:41:40.532  6999  6999 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-16 14:41:40.532  6999  6999 V BluetoothMapService: Handler(): got msg=1
,08-16 14:41:40.534  6999  7553 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-16 14:41:40.534  6999  7553 I bluedroid-qcom: enable
08-16 14:41:40.534  6999  6999 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-16 14:41:40.535  6999  7553 I bt_hci_bdroid: init
08-16 14:41:40.536  6999  7553 I bt_vendor: bt-vendor : init
08-16 14:41:40.536  6999  7553 I bt_vendor: bt-vendor : get_bt_soc_type
08-16 14:41:40.536  6999  7553 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-16 14:41:40.536  6999  7553 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-16 14:41:40.536  6999  7553 D bt_userial_mct: userial_init
08-16 14:41:40.536  6999  7612 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-16 14:41:40.536  6999  7553 D bt_hci_bdroid: set_power 1
08-16 14:41:40.536  6999  7553 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-16 14:41:40.536  6999  7553 I bt_vendor: Starting hciattach daemon
08-16 14:41:40.536  6999  7553 I bt_vendor: try to set true
08-16 14:41:40.536  6999  6999 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-16 14:41:40.536  6999  6999 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-16 14:41:40.536  6999  6999 V BluetoothSapReceiver: SapReceiver onReceive 
08-16 14:41:40.537  6999  6999 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 14:41:40.537  6999  6999 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-16 14:41:40.538  6999  7612 I bt-btu  : btu_task pending for preload complete event
08-16 14:41:40.529  7615  7615 W sh      : type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 14:41:40.529  7615  7615 W sh      : type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 14:41:40.563  7616  7616 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-16 14:41:40.587  1038  1981 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=7618 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-16 14:41:40.647  7639  7639 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
08-16 14:41:40.648  7618  7618 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-16 14:41:40.658  7640  7640 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
08-16 14:41:40.664  1038  2019 I ActivityManager: Killing 6724:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,08-16 14:41:40.681  6932  6932 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
,08-16 14:41:40.681  6932  6932 W System.err: android.os.DeadObjectException
08-16 14:41:40.681  6932  6932 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-16 14:41:40.681  6932  6932 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-16 14:41:40.681  6932  6932 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-16 14:41:40.681  6932  6932 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-16 14:41:40.681  6932  6932 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-16 14:41:40.681  6932  6932 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-16 14:41:40.681  6932  6932 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-16 14:41:40.681  6932  6932 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-16 14:41:40.682  6932  6932 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-16 14:41:40.682  6932  6932 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-16 14:41:40.682  6932  6932 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 14:41:40.682  6932  6932 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 14:41:40.682  6932  6932 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-16 14:41:40.682  7642  7642 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
08-16 14:41:40.683  6932  6932 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-16 14:41:40.683  6932  6932 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-16 14:41:40.683  6932  6932 W System.err: android.os.DeadObjectException
08-16 14:41:40.684  6932  6932 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-16 14:41:40.684  6932  6932 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-16 14:41:40.684  6932  6932 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-16 14:41:40.684  6932  6932 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-16 14:41:40.684  6932  6932 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-16 14:41:40.684  6932  6932 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-16 14:41:40.684  6932  6932 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-16 14:41:40.685  6932  6932 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-16 14:41:40.685  6932  6932 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-16 14:41:40.685  6932  6932 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-16 14:41:40.685  6932  6932 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 14:41:40.685  6932  6932 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 14:41:40.685  6932  6932 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-16 14:41:40.685  6932  6932 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-16 14:41:40.685  6932  6932 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-16 14:41:40.686  6932  6932 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
08-16 14:41:40.694  7643  7643 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-16 14:41:40.706  7644  7644 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
08-16 14:41:40.716  7645  7645 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-16 14:41:40.749  7647  7647 I libmdmdetect: ESOC framework not supported
,08-16 14:41:40.750  7647  7647 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
08-16 14:41:40.759  7647  7647 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-16 14:41:40.759  7647  7647 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-16 14:41:40.759  7647  7647 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-16 14:41:40.759  7647  7647 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-16 14:41:40.759  7647  7647 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-16 14:41:40.760  7647  7647 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-16 14:41:40.760  7647  7647 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-16 14:41:40.774  1038  1981 W libprocessgroup: failed to open /acct/uid_1000/pid_6724/cgroup.procs: No such file or directory
08-16 14:41:40.775  1038  1981 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,08-16 14:41:40.779  6932  6932 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-16 14:41:40.779  6932  6932 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-16 14:41:40.805  7647  7649 E QC-QMI  : qmi_client [7647] 14: failed to locate client data
08-16 14:41:40.806   485   485 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
,08-16 14:41:40.806   485   485 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
,08-16 14:41:40.845  1038  1909 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7650 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-16 14:41:40.852  6932  6932 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-16 14:41:40.891  7665  7665 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-16 14:41:40.908  7668  7668 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-16 14:41:40.939  6999  7553 I bt_vendor: bluetooth satus is on
08-16 14:41:40.939  6999  7553 D bt_hci_bdroid: preload
,08-16 14:41:40.939  6999  7614 D bt_userial_mct: userial_open(port:0)
08-16 14:41:40.940  6999  7614 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
08-16 14:41:40.943  6999  7614 I bt_vendor: Done intiailizing UART
08-16 14:41:40.944  6999  7614 I bt_vendor: Done intiailizing UART
08-16 14:41:40.944  6999  7614 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-16 14:41:40.944  6999  7614 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-16 14:41:40.944  6999  7670 D bt_userial_mct: Entering userial_read_thread()
08-16 14:41:40.944  6999  7612 I bt-btu  : btu_task received preload complete event
08-16 14:41:40.945  7650  7650 D UEI.SmartControl: Quickset Services start...
08-16 14:41:40.945  6999  7612 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-16 14:41:40.945  6999  7612 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-16 14:41:40.947  6999  7612 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-16 14:41:40.947  7650  7650 I UEI.SmartControl: Manufacture = LGE
08-16 14:41:40.948  7650  7650 D UEI.SmartControl: Id = LGNevo
08-16 14:41:40.949  7650  7650 D UEI.SmartControl: File observer start...
08-16 14:41:40.950  6999  7612 I         : BTE_InitTraceLevels -- TRC_HCI
08-16 14:41:40.950  6999  7612 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-16 14:41:40.950  6999  7612 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-16 14:41:40.950  6999  7612 I         : BTE_InitTraceLevels -- TRC_AVDT
08-16 14:41:40.950  6999  7612 I         : BTE_InitTraceLevels -- TRC_AVRC
08-16 14:41:40.950  6999  7612 I         : BTE_InitTraceLevels -- TRC_A2D
08-16 14:41:40.950  6999  7612 I         : BTE_InitTraceLevels -- TRC_BNEP
08-16 14:41:40.950  6999  7612 I         : BTE_InitTraceLevels -- TRC_BTM
08-16 14:41:40.950  7650  7650 E UEI.SmartControl: IR Port is disabled: false
08-16 14:41:40.950  6999  7612 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-16 14:41:40.950  6999  7612 I         : BTE_InitTraceLevels -- TRC_GAP
08-16 14:41:40.950  7650  7650 D UEI.SmartControl: Starting file observer...
08-16 14:41:40.950  6999  7612 I         : BTE_InitTraceLevels -- TRC_PAN
08-16 14:41:40.950  6999  7612 I         : BTE_InitTraceLevels -- TRC_SDP
08-16 14:41:40.950  6999  7612 I         : BTE_InitTraceLevels -- TRC_GATT
08-16 14:41:40.950  6999  7612 I         : BTE_InitTraceLevels -- TRC_SMP
08-16 14:41:40.950  6999  7612 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-16 14:41:40.950  6999  7612 I         : BTE_InitTraceLevels -- TRC_BTIF
08-16 14:41:40.950  7650  7650 D UEI.SmartControl: Extracting JNI libs...
08-16 14:41:40.950  7650  7650 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
,08-16 14:41:41.019  6999  7612 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled,
08-16 14:41:41.019  6999  7612 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa0203061 
08-16 14:41:41.019  6999  7612 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0203061 
,08-16 14:41:41.051  7650  7650 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,08-16 14:41:41.051  7650  7650 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-16 14:41:41.051  7650  7650 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,08-16 14:41:41.064  6999  7557 E bt-btif : Calling BTA_HhEnable
08-16 14:41:41.064  6999  7557 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-16 14:41:41.065  6999  7557 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-16 14:41:41.065  6999  7612 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-16 14:41:41.065  6999  7612 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-16 14:41:41.065  6999  7612 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-16 14:41:41.066  6999  7612 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-16 14:41:41.066  6999  7612 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-16 14:41:41.068  1038  1038 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-16 14:41:41.069  1038  1038 D BluetoothManagerService: Stored Bluetooth name: G3
,08-16 14:41:41.069  6999  7557 D BluetoothAdapterProperties: Name is: G3
08-16 14:41:41.080  6999  7557 D BluetoothAdapterProperties: Scan Mode:20
,08-16 14:41:41.080  6999  7557 D BluetoothAdapterProperties: Discoverable Timeout:120
08-16 14:41:41.082  6999  7557 D bt_hci_bdroid: postload
08-16 14:41:41.082  6608  6608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:41:41.082  6999  7614 D bt_hci_bdroid: Used up Tx Cmd credits
08-16 14:41:41.086  6999  7612 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-16 14:41:41.087  6608  6608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:41:41.088  6999  7612 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-16 14:41:41.088  6999  7612 W bt-smp  : Plain text(LSB ~ MSB) = f1 89 40 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-16 14:41:41.088  6999  7612 W bt-smp  : Encrypted text(LSB ~ MSB) = 8f f7 db c7 42 26 07 3a 4e 7d e7 2b 33 5c ee c5 
08-16 14:41:41.090  7650  7650 I UEI.SmartControl: --- Selecting new region: 6
08-16 14:41:41.090  6608  6608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:41:41.090  6999  7612 W bt-btm  : Stopping oneshot timer
08-16 14:41:41.091  6999  7614 D bt_hci_bdroid: Used up Tx Cmd credits
08-16 14:41:41.091  6999  7614 D bt_hci_bdroid: Used up Tx Cmd credits
08-16 14:41:41.091  6999  7614 D bt_hci_bdroid: Used up Tx Cmd credits
08-16 14:41:41.091  6999  7557 D bte_conf: Device ID record 1 : primary
08-16 14:41:41.091  6999  7557 D bte_conf:   vendorId            = 00c4
08-16 14:41:41.091  6999  7557 D bte_conf:   vendorIdSource      = 0001
08-16 14:41:41.091  6999  7557 D bte_conf:   product             = 13a1
08-16 14:41:41.091  6999  7557 D bte_conf:   version             = 1000
08-16 14:41:41.091  6999  7557 D bte_conf:   clientExecutableURL = 
08-16 14:41:41.091  6999  7557 D bte_conf:   serviceDescription  = 
08-16 14:41:41.091  6999  7557 D bte_conf:   documentationURL    = 
08-16 14:41:41.091  6999  7557 D bte_conf: bte_load_did_conf no section named DID2.
08-16 14:41:41.093  7650  7650 I UEI.SmartControl: Model = LG-D855
,08-16 14:41:41.089  7673  7673 W sh      : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 14:41:41.089  7673  7673 W sh      : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 14:41:41.096  7650  7650 D UEI.SmartControl: QS Service created
08-16 14:41:41.098  6999  7614 D bt_hci_bdroid: Used up Tx Cmd credits
08-16 14:41:41.098  6999  7670 E bt_mct  : hci lib postload completed
08-16 14:41:41.099  6999  7557 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-16 14:41:41.099  6999  7553 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-16 14:41:41.099  6999  7553 D BluetoothAdapterProperties: ScanMode =  20
08-16 14:41:41.099  6999  7553 D BluetoothAdapterProperties: State =  11
08-16 14:41:41.099  6999  7553 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-16 14:41:41.100  6999  7553 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-16 14:41:41.100  6999  7553 D BluetoothAdapterProperties: Setting state to 12
08-16 14:41:41.100  6999  7553 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-16 14:41:41.101  1038  1120 D BluetoothManagerService: Message: 60
08-16 14:41:41.101  1038  1120 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-16 14:41:41.101  1038  1120 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
08-16 14:41:41.102  6999  7553 I BluetoothAdapterState: Entering On State
08-16 14:41:41.103  6999  7557 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-16 14:41:41.105  1839  3933 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 14:41:41.107  6999  7553 D LGBluetoothServiceAdapter: [BTUI] OnState
08-16 14:41:41.108  6999  7553 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-16 14:41:41.108  6999  7553 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
,08-16 14:41:41.110  6999  7553 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-16 14:41:41.114  1839  1839 D BluetoothHeadset: Proxy object connected
08-16 14:41:41.116  6999  7557 D BluetoothAdapterProperties: Discoverable Timeout:120
08-16 14:41:41.116  6999  7557 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-16 14:41:41.118  7650  7650 I UEI.SmartControl: Service initServices...
08-16 14:41:41.118  6879  6895 D BluetoothPan: onBluetoothStateChange on: true
08-16 14:41:41.118  6879  6895 D BluetoothPan: onBluetoothStateChange call bindService
08-16 14:41:41.121  1038  1120 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-16 14:41:41.123  1038  1038 D BluetoothA2dp: Proxy object connected
08-16 14:41:41.123  1839  3935 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 14:41:41.125  6879  6879 D BluetoothPan: BluetoothPAN Proxy object connected
08-16 14:41:41.125  6879  6879 D PanProfile: Bluetooth service connected
08-16 14:41:41.126  6999  7612 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-16 14:41:41.126  6999  7612 W bt-smp  : Plain text(LSB ~ MSB) = 25 1f 45 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-16 14:41:41.126  6999  7612 W bt-smp  : Encrypted text(LSB ~ MSB) = 68 a2 1f 47 87 b5 de 78 ca e4 98 dd fc 93 d5 b2 
08-16 14:41:41.126  6999  7612 W bt-btm  : Stopping oneshot timer
08-16 14:41:41.128  1839  1839 D BluetoothHeadset: Proxy object connected
08-16 14:41:41.128  1839  1855 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 14:41:41.130  1839  1839 D BluetoothHeadset: Proxy object connected
08-16 14:41:41.132  1038  1120 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 14:41:41.132  1038  1038 D BluetoothHeadset: Proxy object connected
08-16 14:41:41.133  6879  6895 D BluetoothPbap: onBluetoothStateChange: up=true
,08-16 14:41:41.136  6879  6896 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-16 14:41:41.138  7650  7650 D UEI.SmartControl: QS start get config
08-16 14:41:41.140  6879  6879 D BluetoothInputDevice: Proxy object connected
08-16 14:41:41.141  6879  6896 D BluetoothMap: onBluetoothStateChange: up=true
08-16 14:41:41.141  6879  6879 D HidProfile: Bluetooth service connected
08-16 14:41:41.143  6999  7612 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-16 14:41:41.143  6999  7612 W bt-smp  : Plain text(LSB ~ MSB) = 7b c0 52 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-16 14:41:41.143  6999  7612 W bt-smp  : Encrypted text(LSB ~ MSB) = ad 5e 98 20 ef a9 be 1b 70 df 49 08 e9 d2 ad 87 
08-16 14:41:41.143  6999  7612 W bt-btm  : Stopping oneshot timer
08-16 14:41:41.145  6879  6879 D BluetoothMap: Proxy object connected
08-16 14:41:41.145  6879  6879 D MapProfile: Bluetooth service connected
08-16 14:41:41.145  6879  6879 D BluetoothMap: getConnectedDevices()
,08-16 14:41:41.146  1038  1038 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-16 14:41:41.146  1038  1120 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-16 14:41:41.147  1038  1120 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-16 14:41:41.147  6999  7558 V BluetoothMapService: getConnectedDevices()
08-16 14:41:41.149  1927  1927 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-16 14:41:41.150  1927  2129 D LGBluetoothAPIService: Message: 1
08-16 14:41:41.150  1927  2129 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-16 14:41:41.151  1589  1589 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-16 14:41:41.152  6999  7553 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-16 14:41:41.153  6999  7612 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-16 14:41:41.153  6999  7612 W bt-smp  : Plain text(LSB ~ MSB) = 3c 9f 55 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-16 14:41:41.153  6999  7612 W bt-smp  : Encrypted text(LSB ~ MSB) = 06 85 c9 29 cc 08 e5 89 60 d1 d0 03 59 39 66 ab 
08-16 14:41:41.153  6999  7612 W bt-btm  : Stopping oneshot timer
08-16 14:41:41.155  1038  1120 D BluetoothManagerService: Message: 40
08-16 14:41:41.155  1038  1120 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-16 14:41:41.162  6608  6608 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
,08-16 14:41:41.165  6999  7612 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-16 14:41:41.165  6999  7612 W bt-smp  : Plain text(LSB ~ MSB) = d5 fd 5a 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-16 14:41:41.165  6999  7612 W bt-smp  : Encrypted text(LSB ~ MSB) = 3e 84 c1 74 dc 04 b7 e7 da 59 fa 7d 3a 04 c2 f4 
08-16 14:41:41.165  6999  7612 W bt-btm  : Stopping oneshot timer
08-16 14:41:41.165  7678  7678 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-16 14:41:41.167  6608  6608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 14:41:41.167  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:41:41.167  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 14:41:41.167  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 14:41:41.167  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 14:41:41.167  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 14:41:41.167  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 14:41:41.167  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 14:41:41.169  6608  6608 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 14:41:41.176  6999  6999 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-16 14:41:41.176  6999  6999 D BluetoothMapService: STATE_ON
08-16 14:41:41.178  6608  6608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 14:41:41.178  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:41:41.178  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 14:41:41.178  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 14:41:41.178  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 14:41:41.178  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 14:41:41.178  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 14:41:41.178  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 14:41:41.179  6999  6999 D LGBluetoothAPIServer: [BTUI] onCreate()
08-16 14:41:41.180  6999  6999 D LGBluetoothAPIServer: [BTUI] onBind()
08-16 14:41:41.180  6879  6879 D LocalBluetoothProfileManager: Adding local A2DP profile
08-16 14:41:41.182  1927  2129 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
08-16 14:41:41.182  1927  1927 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-16 14:41:41.182  1038  1120 D BluetoothManagerService: Message: 30
08-16 14:41:41.184  6608  6608 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 14:41:41.185  1927  2129 D LGBluetoothAPIService: Message: 100
08-16 14:41:41.185  1927  2129 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-16 14:41:41.186  6879  6879 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-16 14:41:41.189  1038  1120 D BluetoothManagerService: Message: 30
,08-16 14:41:41.192  6608  6608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 14:41:41.192  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:41:41.192  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 14:41:41.192  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 14:41:41.192  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 14:41:41.192  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 14:41:41.192  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 14:41:41.192  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 14:41:41.195  6608  6608 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 14:41:41.199  6879  6879 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-16 14:41:41.200  6999  6999 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@316e4518
,08-16 14:41:41.200  6999  6999 V BluetoothPbapService: Pbap Service onCreate
08-16 14:41:41.200  6999  6999 V BluetoothPbapService: Starting PBAP service
08-16 14:41:41.200  6879  6879 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-16 14:41:41.202  6999  6999 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-16 14:41:41.202  6999  6999 V BluetoothPbapService: Pbap Service onBind
08-16 14:41:41.203  6879  6879 D BluetoothA2dp: Proxy object connected
08-16 14:41:41.203  6999  6999 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 14:41:41.203  6999  6999 V BluetoothPbapService: state: 12
08-16 14:41:41.204  6999  6999 V BluetoothMapService: Handler(): got msg=1
08-16 14:41:41.204  6879  6879 D A2dpProfile: Bluetooth service connected
08-16 14:41:41.204  6999  6999 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-16 14:41:41.204  6999  6999 V BluetoothPbapService: Handler(): got msg=1
08-16 14:41:41.205  6999  6999 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-16 14:41:41.205  6999  7685 D BluetoothMapMasInstance: MAS initSocket()
08-16 14:41:41.206  6999  6999 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-16 14:41:41.206  6999  6999 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 14:41:41.206  6999  6999 V BluetoothPbapReceiver: ***********state = 12
08-16 14:41:41.206  6999  7685 D BluetoothMapMasInstance:   masId = 00
08-16 14:41:41.206  6999  7685 D BluetoothMapMasInstance:   msgTypes = 0e
08-16 14:41:41.206  6999  7685 D BluetoothMapMasInstance:   masName = SMS/MMS
08-16 14:41:41.206  6999  7685 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-16 14:41:41.206  6879  6879 D BluetoothHeadset: Proxy object connected
08-16 14:41:41.207  6999  7686 V BluetoothPbapService: Pbap Service initSocket
08-16 14:41:41.207  6879  6879 D HeadsetProfile: Bluetooth service connected
08-16 14:41:41.207  1038  2019 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 14:41:41.208  1038  1588 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 14:41:41.209  6999  7685 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 14:41:41.209  6999  7686 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 14:41:41.210  2178  2178 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-16 14:41:41.211  2178  2178 D c       : Getting all permits...
08-16 14:41:41.211  2178  2178 D a       : Opening database...
08-16 14:41:41.212  6999  7686 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-16 14:41:41.212  6999  7686 V BluetoothPbapService: Succeed to create listening socket 
08-16 14:41:41.212  6999  7686 V BluetoothPbapService: Accepting socket connection...
08-16 14:41:41.213  6999  7557 D BluetoothAdapterProperties: Scan Mode:21
08-16 14:41:41.214  6999  7557 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-16 14:41:41.214  6999  7685 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-16 14:41:41.214  6999  7685 V BluetoothMapMasInstance: Succeed to create listening socket 
08-16 14:41:41.214  6999  7685 D BluetoothMapMasInstance: Accepting socket connection...
08-16 14:41:41.215  2178  2178 D a       : Opening database auth.proximity.permit_store...
08-16 14:41:41.215  2178  2178 D a       : Closing databa,se...
08-16 14:41:41.216  6608  6608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 14:41:41.220  6608  6608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:41:41.221  6608  6608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:41:41.226  6879  6879 D DockEventReceiver: finishStartingService: stopping service
08-16 14:41:41.227  6879  6879 D BluetoothPbap: Proxy object connected
08-16 14:41:41.228  6879  6879 D PbapServerProfile: Bluetooth service connected
,08-16 14:41:41.232  6879  6879 D BluetoothPermissionRequest: onReceive
08-16 14:41:41.234  6879  6879 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-16 14:41:41.236  6879  6879 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-16 14:41:41.239  6999  6999 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-16 14:41:41.240  6999  6999 I LGBluetoothOppAdapter: [BTUI] startOppService()
,08-16 14:41:41.246  6999  6999 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
08-16 14:41:41.264  7650  7650 D UEI.SmartControl: Loading JNI Libs...
,08-16 14:41:41.265  6999  6999 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-16 14:41:41.266  6999  6999 V BtOppService: onCreate
08-16 14:41:41.269  6999  6999 V BluetoothOppNotification: send message
08-16 14:41:41.274  6999  6999 V BtOppService: Starting RfcommListener
08-16 14:41:41.279  6999  6999 D BluetoothOppPreference: Dumping Names:  
08-16 14:41:41.279  6999  6999 D BluetoothOppPreference: {}
08-16 14:41:41.280  6999  6999 D BluetoothOppPreference: Dumping Channels:  
08-16 14:41:41.280  6999  6999 D BluetoothOppPreference: {}
,08-16 14:41:41.284  6999  6999 V BtOppService: onStartCommand
08-16 14:41:41.284  6999  7694 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-16 14:41:41.289  6999  7694 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-16 14:41:41.290  6999  7691 V BtOppService: Deleted complete outbound shares, number =  0
08-16 14:41:41.290  6999  6999 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-16 14:41:41.290  6999  6999 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
,08-16 14:41:41.295  6999  6999 V BluetoothOppNotification: new notify threadi!
08-16 14:41:41.295  6999  6999 V BluetoothOppNotification: send delay message
08-16 14:41:41.296  6999  7695 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-16 14:41:41.300  6999  6999 V BtOppService: start RfcommListener
08-16 14:41:41.304  6999  6999 V BtOppService: RfcommListener started
08-16 14:41:41.304  6999  6999 V BtOppService: ContentObserver received notification
08-16 14:41:41.305  6999  7696 V BtOppRfcommListener: Starting RFCOMM listener....
,08-16 14:41:41.305  1038  1945 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 14:41:41.308  6999  7696 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 14:41:41.308  6999  7696 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=78 mFd=75
08-16 14:41:41.309  6999  7696 V BtOppRfcommListener: Started RFCOMM listener....
08-16 14:41:41.309  6999  7696 I BtOppRfcommListener: Accept thread started.
08-16 14:41:41.309  6999  7696 V BtOppRfcommListener: Accepting connection...
08-16 14:41:41.321  6999  6999 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@316e4518
08-16 14:41:41.321  6999  6999 V BluetoothFtpService: Ftp Service onCreate
08-16 14:41:41.321  6999  6999 I BluetoothFtpService: Ftp Service onCreate
08-16 14:41:41.321  6999  6999 V BluetoothFtpService: Ftp Service onStartCommand
08-16 14:41:41.321  6999  6999 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 14:41:41.321  6999  6999 V BluetoothFtpService: Starting Listening on sockets
08-16 14:41:41.322  6999  6999 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-16 14:41:41.322  6999  6999 V BluetoothSapReceiver: [BTUI] region:EU country:EU
,08-16 14:41:41.322  6999  6999 V BluetoothSapReceiver: SapReceiver onReceive 
08-16 14:41:41.322  6999  6999 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 14:41:41.322  6999  6999 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-16 14:41:41.322  6999  6999 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-16 14:41:41.325  6999  6999 V BluetoothFtpService: Handler(): got msg=1
08-16 14:41:41.326  6999  6999 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-16 14:41:41.326  6999  6999 V BluetoothFtpService: Ftp Service initSocket
08-16 14:41:41.330  1038  1562 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 14:41:41.330  6999  6999 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 14:41:41.331  6999  6999 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=78
08-16 14:41:41.331  6999  6999 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-16 14:41:41.333  6999  7697 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
,08-16 14:41:41.345  6999  6999 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@316e4518
,08-16 14:41:41.345  6999  6999 V BluetoothSapService: Sap Service onCreate
08-16 14:41:41.347  6999  6999 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 14:41:41.347  6999  6999 V BluetoothSapService: state: 12
08-16 14:41:41.347  6999  6999 V BluetoothSapService: Starting SAP server process
08-16 14:41:41.348  6999  6999 V BluetoothSapService: SAP Service startRfcommListenerThread
08-16 14:41:41.349  6999  7699 V BluetoothSapService: Sap Service initRfcommSocket
08-16 14:41:41.350  1038  1054 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-16 14:41:41.352  6999  7699 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 14:41:41.353  6999  7699 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-16 14:41:41.353  6999  7699 V BluetoothSapService: Succeed to create listening socket 
08-16 14:41:41.353  6999  7699 V BluetoothSapService: Accepting socket connection...
08-16 14:41:41.339  7698  7698 W sapd    : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 14:41:41.339  7698  7698 W sapd    : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 14:41:41.364  7698  7698 V BT_SAP  : Event pipe created
,08-16 14:41:41.364  7698  7698 V BT_SAP  : create_server_socket qcom.sap.server
08-16 14:41:41.364  7698  7698 V BT_SAP  : created socket fd 6
08-16 14:41:41.418  1038  2018 I art     : Explicit concurrent mark sweep GC freed 124997(5MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/64MB, paused 2.555ms total 125.535ms
08-16 14:41:41.419  6999  7694 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1c8fbbf9 on behalf of 
08-16 14:41:41.420  6999  6999 V BtOppService: ContentObserver received notification
,08-16 14:41:41.421  6999  7691 V BtOppService: Deleted complete inbound failed shares, number = 0
08-16 14:41:41.422  6999  7691 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-16 14:41:41.423  6999  7695 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@100f173e on behalf of 
08-16 14:41:41.423  6999  7691 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2775f99f on behalf of 
08-16 14:41:41.427  6999  7695 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-16 14:41:41.428  6999  7694 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-16 14:41:41.428  6999  7694 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-16 14:41:41.430  6999  7694 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2f43eaec on behalf of 
08-16 14:41:41.432  6999  7694 V BluetoothOppNotification: update too frequent, put in queue
,08-16 14:41:41.433  6999  7694 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-16 14:41:41.435  6999  7695 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-16 14:41:41.436  6999  7695 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@30071eb5 on behalf of 
08-16 14:41:41.437  6999  7695 V BluetoothOppNotification: outbound: succ-0  fail-0
08-16 14:41:41.438  6999  7695 V BluetoothOppNotification: outbound notification was removed.
08-16 14:41:41.438  6999  7695 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-16 14:41:41.439  6999  7695 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1361694a on behalf of 
,08-16 14:41:41.440  6999  7695 V BluetoothOppNotification: inbound: succ-0  fail-0
08-16 14:41:41.441  6999  7695 V BluetoothOppNotification: inbound notification was removed.
08-16 14:41:41.441  6999  7695 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
,08-16 14:41:41.442  6999  7695 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@27ca90bb on behalf of ,
,08-16 14:41:41.552  7650  7650 I UEI.SmartControl: Supports setup maps: true
,08-16 14:41:41.555  7650  7650 D UEI.SmartControl: QS start statue = true Error code = 0
,08-16 14:41:41.555  7650  7650 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-16 14:41:41.555  7650  7650 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-16 14:41:41.555  7650  7650 I UEI.SmartControl: ### init IR Blaster...
,08-16 14:41:41.560  7650  7650 D serial_port: Configuring serial port
08-16 14:41:41.563  7650  7650 E UEI.SmartControl: UEIBLaster setting for 616
08-16 14:41:41.563  7650  7650 I UEI.SmartControl: Setting serial record hearder size = 2
08-16 14:41:41.563  7650  7650 I UEI.SmartControl: configuring settings for MAXQ616
08-16 14:41:41.563  7650  7650 I UEI.SmartControl: Get version...
08-16 14:41:41.580  7650  7700 D UEI.SmartControl: serial port data available: 21
,08-16 14:41:41.609  7650  7650 D UEI.SmartControl: MAXQ616 A2-X4 software.
,08-16 14:41:41.609  7650  7650 I UEI.SmartControl: IR Blaster version: 256702256704300002
,08-16 14:41:41.609  7650  7650 I UEI.SmartControl: QS saving settings...
08-16 14:41:41.611  7650  7650 D UEI.SmartControl: IR Blaster version: 25672567
,08-16 14:41:41.629  7650  7700 D UEI.SmartControl: serial port data available: 4
,08-16 14:41:41.673  7650  7703 I UEI.SmartControl: Device manager: loading config....
,08-16 14:41:41.674  7650  7703 D UEI.SmartControl: ----------- loading internal config...
,08-16 14:41:41.677  7650  7650 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-16 14:41:41.685  7650  7650 E UEI.SmartControl: Services init done
08-16 14:41:41.685  7650  7650 D UEI.SmartControl: QS Service init finished
08-16 14:41:41.688  7650  7650 D UEI.SmartControl: QS Service version name: 2.1.91
08-16 14:41:41.688  7650  7650 D UEI.SmartControl: QS Service version code: 201091
08-16 14:41:41.691  7650  7650 D UEI.SmartControl: Service requested: Control
,08-16 14:41:41.697  7650  7703 E UEI.SmartControl: Loading SETTINGS...
08-16 14:41:41.701  7650  7650 D UEI.SmartControl: Request IControl service: devices are loaded...
08-16 14:41:41.703  1038  1909 I ActivityManager: Killing 6932:com.lge.qremote/u0a112 (adj 15): empty #17
,08-16 14:41:41.710  7650  7703 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-16 14:41:41.731  7650  7702 I UEI.SmartControl: Notify AllClients services are ready: 0
08-16 14:41:41.731  7650  7702 D UEI.SmartControl: -----service ready thread exits
,08-16 14:41:41.744  1038  1981 W libprocessgroup: failed to open /acct/uid_10112/pid_6932/cgroup.procs: No such file or directory
,08-16 14:41:41.747  7650  7650 D UEI.SmartControl: Internal service binding...
,08-16 14:41:41.840  1589  1589 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,08-16 14:41:41.860  1038  1367 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-16 14:41:41.896  2020  2020 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-16 14:41:41.904  1038  1038 D administrator: Handling package changes for user 0
08-16 14:41:41.986  1038  1109 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7714 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-16 14:41:42.009  1589  1589 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
,08-16 14:41:42.011  1589  1589 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
08-16 14:41:42.031  2020  2020 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-16 14:41:42.074  7714  7714 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-16 14:41:42.098  1038  1038 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
08-16 14:41:42.098  1038  1038 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-16 14:41:42.161  1038  1107 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-16 14:41:42.168  1038  1107 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,08-16 14:41:42.175  7714  7714 D LgDataFeature: LgDataFeature() Constructor: none
08-16 14:41:42.175  7714  7714 D LgDataFeature: LgDataFeature() Constructor Done, null
08-16 14:41:42.177  2020  2020 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-16 14:41:42.178  2494  2494 V GmsNetworkLocationProvi: DISABLE
,08-16 14:41:42.215  1038  1107 D LocationProviderProxy: applying state to connected service
,08-16 14:41:42.219  2494  2494 E GCoreFlp: Bound FusedProviderService with LocationManager
,08-16 14:41:42.297  6999  6999 V BluetoothOppNotification: new notify threadi!
08-16 14:41:42.298  6999  6999 V BluetoothOppNotification: send delay message
,08-16 14:41:42.301  6999  7758 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-16 14:41:42.303  6999  7758 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@14fac9d8 on behalf of 
08-16 14:41:42.305  6999  7758 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-16 14:41:42.307  6999  7758 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-16 14:41:42.309  6999  7758 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@d57f131 on behalf of 
08-16 14:41:42.311  6999  7758 V BluetoothOppNotification: outbound: succ-0  fail-0
,08-16 14:41:42.313  6999  7758 V BluetoothOppNotification: outbound notification was removed.
08-16 14:41:42.313  6999  7758 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-16 14:41:42.314  6999  7758 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@36d4d016 on behalf of 
08-16 14:41:42.315  6999  7758 V BluetoothOppNotification: inbound: succ-0  fail-0
08-16 14:41:42.320  6999  7758 V BluetoothOppNotification: inbound notification was removed.
,08-16 14:41:42.320  6999  7758 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-16 14:41:42.321  6999  7758 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@37077d97 on behalf of 
,08-16 14:41:42.339  7714  7761 I Babel   : MmsConfig: mnc/mcc: 0/0
08-16 14:41:42.339  7714  7761 I Babel   : MmsConfig.loadMmsSettings
08-16 14:41:42.346  7714  7761 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
,08-16 14:41:42.346  7714  7761 I Babel   : MmsConfig.loadFromDatabase
,08-16 14:41:42.363  7714  7761 E Babel   : canonicalizeMccMnc: invalid mccmnc 
08-16 14:41:42.363  7714  7761 I Babel   : MmsConfig.loadFromResources
08-16 14:41:42.365  7714  7761 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
08-16 14:41:42.365  7714  7761 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-16 14:41:42.373  7714  7714 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 14:41:42.384  7714  7759 W AudioCapabilities: Unsupported mime audio/evrc
,08-16 14:41:42.386  7714  7759 W AudioCapabilities: Unsupported mime audio/qcelp
08-16 14:41:42.388  7714  7759 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
08-16 14:41:42.403  1803  7763 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
08-16 14:41:42.403  1803  7763 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
,08-16 14:41:42.408  7047  7047 I AppUp4:CustModeStarterReceiver: onReceive
08-16 14:41:42.411  7714  7759 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
08-16 14:41:42.412  7714  7759 W AudioCapabilities: Unsupported mime audio/qcelp
08-16 14:41:42.416  7047  7047 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2701228a
08-16 14:41:42.416  7047  7047 D AppUp4:CustFacade: isCustomizationCompleted : false
08-16 14:41:42.416  7047  7047 D AppUp4:CustFacade: isPhone : true
,08-16 14:41:42.417  7047  7047 D AppUp4:CustModeStarterReceiver: begin check event
08-16 14:41:42.418  7047  7047 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
08-16 14:41:42.418  7714  7759 W AudioCapabilities: Unsupported mime audio/evrc
08-16 14:41:42.422  1803  4710 I Icing   : updateResources: need to parse e{com.google.android.gms}
,08-16 14:41:42.440  7714  7759 W VideoCapabilities: Unsupported mime video/x-ms-wmv
08-16 14:41:42.447  7714  7759 W VideoCapabilities: Unsupported mime video/divx
08-16 14:41:42.451  7714  7759 W VideoCapabilities: Unsupported mime video/divx311
,08-16 14:41:42.456  7714  7759 W VideoCapabilities: Unsupported mime video/divx4
08-16 14:41:42.458  1038  1890 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7766 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
08-16 14:41:42.463  1038  2037 I ActivityManager: Killing 6899:com.lge.sync/1000 (adj 15): empty #17
,08-16 14:41:42.481  7714  7759 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,08-16 14:41:42.497  7714  7759 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-16 14:41:42.502  7714  7759 W AudioCapabilities: Unsupported mime audio/eac3
08-16 14:41:42.503  7714  7759 W AudioCapabilities: Unsupported mime audio/ac3
08-16 14:41:42.504  7714  7759 W AudioCapabilities: Unsupported mime audio/g726
08-16 14:41:42.505  7714  7759 W AudioCapabilities: Unsupported mime audio/wma-voice
08-16 14:41:42.506  7714  7759 W AudioCapabilities: Unsupported mime audio/x-ms-wma
08-16 14:41:42.507  7714  7759 W AudioCapabilities: Unsupported mime audio/adpcm
08-16 14:41:42.509  7714  7759 W VideoCapabilities: Unsupported mime video/theora
,08-16 14:41:42.511  7714  7759 W VideoCapabilities: Unsupported mime video/mjpg
08-16 14:41:42.521  1038  1944 W libprocessgroup: failed to open /acct/uid_1000/pid_6899/cgroup.procs: No such file or directory
,08-16 14:41:42.548  7766  7766 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 14:41:42.549  7766  7766 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-16 14:41:42.549  7766  7766 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,08-16 14:41:42.551  7766  7766 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
08-16 14:41:42.552  7766  7766 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-16 14:41:42.632  7766  7766 I SystemConfig: BUILD Country: EU
08-16 14:41:42.632  7766  7766 I SystemConfig: BUILD Operator: OPEN
,08-16 14:41:42.683  1038  2018 I ActivityManager: Killing 7395:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
,08-16 14:41:42.805  1038  1908 W libprocessgroup: failed to open /acct/uid_10005/pid_7395/cgroup.procs: No such file or directory
,08-16 14:41:42.815  7766  7784 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
08-16 14:41:42.815  7766  7784 I SystemConfig: existFile = false
08-16 14:41:42.815  7766  7784 I SystemConfig: canReadFile = false
08-16 14:41:42.815  7766  7784 I SystemConfig: systemFeature RCS result false
08-16 14:41:42.815  7766  7784 D SystemConfig: refreshRcsSupport() :false
08-16 14:41:42.867  1038  2018 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7789 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,08-16 14:41:42.929  7789  7789 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 14:41:42.929  7789  7789 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-16 14:41:42.930  7789  7789 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-16 14:41:42.932  7789  7789 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-16 14:41:43.023  7789  7789 I AppConfig: Total System Memory = 2995761152
,08-16 14:41:43.034  7789  7789 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
08-16 14:41:43.114  1038  1053 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7808 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-16 14:41:43.115  1038  1053 I ActivityManager: Killing 7086:com.lge.email/u0a23 (adj 15): empty #17
,08-16 14:41:43.203  1038  1981 W libprocessgroup: failed to open /acct/uid_10023/pid_7086/cgroup.procs: No such file or directory
,08-16 14:41:43.269  1038  1365 V AlarmManager: ELAPSED_WAKEUP set : Alarm{ac6b731 type 2 when 180429 com.google.android.gms} when 180429
,08-16 14:41:43.414  7808  7808 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,08-16 14:41:43.498  7808  7808 D LgDataFeature: LgDataFeature() Constructor: none
08-16 14:41:43.498  7808  7808 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 14:41:43.553  7808  7808 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,08-16 14:41:43.576  7808  7808 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-16 14:41:43.577  7808  7808 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-16 14:41:43.594  7808  7808 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-16 14:41:43.594  7808  7808 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,08-16 14:41:43.635  1038  1908 I ActivityManager: Killing 6976:com.lge.formmanager/u0a26 (adj 15): empty #17
,08-16 14:41:43.702  1038  1562 W libprocessgroup: failed to open /acct/uid_10026/pid_6976/cgroup.procs: No such file or directory
,08-16 14:41:43.712  3472  3489 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
08-16 14:41:43.714  3472  3489 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@351f1e89 on behalf of 7808
08-16 14:41:43.727  4570  7848 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,08-16 14:41:43.734  7808  7808 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
08-16 14:41:43.781  1038  2019 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7850 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,08-16 14:41:43.833  7808  7808 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,08-16 14:41:43.889  7850  7850 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,08-16 14:41:43.918  7850  7850 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
08-16 14:41:43.918  7850  7850 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
08-16 14:41:43.918  7850  7850 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
08-16 14:41:43.918  7850  7850 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
08-16 14:41:43.918  7850  7850 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
08-16 14:41:43.918  7850  7850 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
,08-16 14:41:43.933   321  7870 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,08-16 14:41:43.941  1038  1118 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,08-16 14:41:43.968  1038  1944 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=7872 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,08-16 14:41:43.988  1038  1562 I ActivityManager: Killing 6411:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,08-16 14:41:44.001   351   351 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 2.991ms total 28.591ms
,08-16 14:41:44.021   351   351 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 405us total 19.904ms
,08-16 14:41:44.041   351   351 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 406us total 18.683ms
,08-16 14:41:44.052  1038  1946 W libprocessgroup: failed to open /acct/uid_1000/pid_6411/cgroup.procs: No such file or directory
,08-16 14:41:44.082  7872  7872 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-16 14:41:44.102  7872  7872 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,08-16 14:41:44.138  7872  7872 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
08-16 14:41:44.138  7872  7872 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
,08-16 14:41:44.138  7872  7872 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-16 14:41:44.138  7872  7872 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-16 14:41:44.139  7872  7872 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-16 14:41:44.140  7872  7872 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-16 14:41:44.146  7872  7872 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
,08-16 14:41:44.160  7872  7872 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
08-16 14:41:44.161  7872  7872 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:9652
,08-16 14:41:44.166  7872  7872 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
,08-16 14:41:44.168  7872  7872 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-16 14:41:44.168  7872  7872 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-16 14:41:44.169  7872  7872 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-16 14:41:44.169  7872  7872 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
08-16 14:41:44.184  1038  1053 V SIM_STK : Menu title from STK is T-Mobile
,08-16 14:41:44.190  7872  7872 D LgDataFeature: LgDataFeature() Constructor: none
08-16 14:41:44.190  7872  7872 D LgDataFeature: LgDataFeature() Constructor Done, null
08-16 14:41:44.196  7872  7872 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
08-16 14:41:44.197  7872  7872 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-16 14:41:44.197  7872  7872 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-16 14:41:44.197  7872  7872 V SoundPool: doLoad: loading sample sampleID=1
,08-16 14:41:44.197  7872  7872 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-16 14:41:44.198  7872  7904 V SoundPool: Start decode
08-16 14:41:44.198  7872  7904 V MediaPlayer[Native]: decode(31, 10857164, 17813)
08-16 14:41:44.198   325  1384 V MediaPlayerService: decode(23, 10857164, 17813)
08-16 14:41:44.198   325  1384 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-16 14:41:44.198   325  1384 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-16 14:41:44.199   325  1384 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-16 14:41:44.199   325  1384 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-16 14:41:44.199   325  1384 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-16 14:41:44.199   325  1384 V MediaPlayerService: player type = 3
08-16 14:41:44.199   325  1384 V AwesomePlayer: AwesomePlayer create()
08-16 14:41:44.199   325  1384 V AwesomePlayer: reset_l() 
08-16 14:41:44.199   325  1384 V AwesomePlayer: cancelPlayerEvents
08-16 14:41:44.199   325  1384 V AwesomePlayer: setAudioSink() 
08-16 14:41:44.199   325  1384 V AwesomePlayer: reset_l() 
08-16 14:41:44.199   325  1384 V AudioCache: notify(0xb16a6940, 8, 0, 0)
08-16 14:41:44.199   325  1384 V AudioCache: ignored
08-16 14:41:44.199   325  1384 V AwesomePlayer: cancelPlayerEvents
08-16 14:41:44.199   325  1384 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
08-16 14:41:44.199   325  1384 V AwesomePlayer: setDataSource_l dataSource
08-16 14:41:44.199   325  1384 V LGParserOSAL: SniffLGParser start
08-16 14:41:44.199   325  1384 V LGParserOSAL: MainType:5, SubType=0
08-16 14:41:44.199   325  1384 V LGParserOSAL: #### check Mime : application/ogg
08-16 14:41:44.200   325  1384 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-16 14:41:44.200   325  1384 E MediaExtractor: Use LGExtractor :application/ogg 
08-16 14:41:44.204  7872  7872 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-16 14:41:44.207  7872  7872 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-16 14:41:44.207  7872  7872 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-16 14:41:44.217  4570  7848 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 489 ms] updated apps [took 489 ms] 
,08-16 14:41:44.239  7872  7872 V LGMDMManager: Create singleton instance
,08-16 14:41:44.240   325  1384 V LGParserOSAL: supported mime: application/ogg
08-16 14:41:44.240   325  1384 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-16 14:41:44.240   325  1384 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-16 14:41:44.240   325  1384 V AwesomePlayer: mBitrate = -1 bits/sec
08-16 14:41:44.240   325  1384 V AwesomePlayer: AudioTrack Setting
08-16 14:41:44.240   325  1384 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-16 14:41:44.240   325  1384 V AwesomePlayer: setAudioSource() 
08-16 14:41:44.240   325  1384 V MediaPlayerService: prepare
08-16 14:41:44.240   325  1384 V AwesomePlayer: prepareAsync_l() 
08-16 14:41:44.240   325  1384 V MediaPlayerService: wait for prepare
08-16 14:41:44.240   325  7905 V AwesomePlayer: onPrepareAsyncEvent() 
08-16 14:41:44.241   325  7905 V AwesomePlayer: initAudioDecoder() 
08-16 14:41:44.241   325  7905 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-16 14:41:44.241   325  7905 V AudioSystem: isOffloadSupported()
08-16 14:41:44.241   325  7905 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-16 14:41:44.241   325  7905 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-16 14:41:44.241   325  7905 I AudioFlinger: isAudioPlaybackHookOn() false
08-16 14:41:44.241   325  7905 V AwesomePlayer: getUseOffload() = 0 
08-16 14:41:44.241   325  7905 V OMXCodec: OMXCodec::Create
08-16 14:41:44.241   325  7905 V OMXCodec: findMatchingCodecs()
08-16 14:41:44.241   325  7905 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-16 14:41:44.241   325  7905 V OMXCodec: matchingCodecs.size()=1
08-16 14:41:44.241   325  7905 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
08-16 14:41:44.243   325  7905 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-16 14:41:44.243   325  7905 V LGCodecAdapter: LG Codec Adapter start
08-16 14:41:44.243   325  7905 V OMXCodec: OMXCodec Createtor
08-16 14:41:44.243   325  7905 V OMXCodec: setComponentRole
08-16 14:41:44.243   325  7905 V OMXCodec: configureCodec protected=0
08-16 14:41:44.243   325  7905 V LGCodecAdapter: called getLGCodecSpecificData
08-16 14:41:44.243   325  7905 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-16 14:41:44.243   325  7905 V LGCodecOSAL: Called LGconfigureCodecMETA
08-16 14:41:44.243   325  7905 V LGCodecOSAL: Called LGconfigureCodecMSG
08-16 14:41:44.243   325  7905 V LGCodecOSAL: Not support LGCodec
08-16 14:41:44.243   325  7905 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-16 14:41:44.243   325  7905 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-16 14:41:44.243   325  7905 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-16 14:41:44.243   325  7905 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-16 14:41:44.243   325  7905 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-16 14:41:44.243   325  7905 V AudioSystem: isOffloadSupported()
08-16 14:41:44.243   325  7905 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-16 14:41:44.243   325  7905 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-16 14:41:44.243   325  7905 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-16 14:41:44.243   325  7905 V OMXCodec: init()
08-16 14:41:44.243   325  7905 V OMXCodec: [OMX.google.vorbis.decoder] set,State mState=1 , newState=2
08-16 14:41:44.243   325  7905 V OMXCodec: allocateBuffers
08-16 14:41:44.243   325  7905 V OMXCodec: allocateBuffersOnPort portIndex=0
08-16 14:41:44.243   325  7905 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-16 14:41:44.244   325  7905 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f76a0 on input port
08-16 14:41:44.244   325  7905 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7790 on input port
08-16 14:41:44.244   325  7905 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7920 on input port
08-16 14:41:44.244   325  7905 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f79c0 on input port
08-16 14:41:44.244   325  7905 V OMXCodec: allocateBuffersOnPort portIndex=1
08-16 14:41:44.244   325  7905 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-16 14:41:44.244   325  7905 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a10 on output port
08-16 14:41:44.244   325  7905 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on output port
08-16 14:41:44.244   325  7905 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b00 on output port
08-16 14:41:44.244   325  7905 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57f7150 on output port
08-16 14:41:44.244   325  7905 V OMXCodec: init() mAsyncCompletion wait!!! 
08-16 14:41:44.244   325  7907 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-16 14:41:44.244   325  7907 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-16 14:41:44.244   325  7907 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-16 14:41:44.244   325  7905 V OMXCodec: init() mAsyncCompletion wait!!! 
08-16 14:41:44.244   325  7907 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-16 14:41:44.244   325  7907 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-16 14:41:44.244   325  7907 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-16 14:41:44.244   325  7905 V OMXCodec: init() mAsyncCompletion wait free! 
08-16 14:41:44.244   325  7905 V AwesomePlayer: finishAsyncPrepare_l() 
08-16 14:41:44.244   325  7905 V AudioCache: notify(0xb16a6940, 5, 0, 0)
08-16 14:41:44.244   325  7905 V AudioCache: ignored
08-16 14:41:44.244   325  7905 V AudioCache: notify(0xb16a6940, 1, 0, 0)
08-16 14:41:44.244   325  7905 V AudioCache: prepared
08-16 14:41:44.244   325  1384 V AudioCache: wait - success
08-16 14:41:44.244   325  1384 V MediaPlayerService: start
08-16 14:41:44.244   325  1384 V AwesomePlayer: play_l() 
08-16 14:41:44.244   325  1384 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-16 14:41:44.244   325  1384 V AwesomePlayer: createAudioPlayer_l
08-16 14:41:44.244   325  1384 V AwesomePlayer: seekAudioIfNecessary_l() 
08-16 14:41:44.244   325  1384 V AwesomePlayer: startAudioPlayer_l() 
08-16 14:41:44.244   325  1384 D AudioPlayer: start of Playback, useOffload 0
,08-16 14:41:44.244   325  1384 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-16 14:41:44.244   325  1384 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-16 14:41:44.245   325  7907 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-16 14:41:44.245   325  7907 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-16 14:41:44.245   325  7907 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-16 14:41:44.245   325  7907 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-16 14:41:44.245   325  7907 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-16 14:41:44.245   325  7907 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
,08-16 14:41:44.246   325  7907 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884688
08-16 14:41:44.246   325  7907 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-16 14:41:44.246   325  7907 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884848
08-16 14:41:44.246   325  7907 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-16 14:41:44.246   325  7907 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884928
08-16 14:41:44.246   325  7907 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-16 14:41:44.246   325  7907 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3045028176
08-16 14:41:44.246   325  7907 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
,08-16 14:41:44.246   325  7907 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-16 14:41:44.246   325  7907 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-16 14:41:44.246   325  7907 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-16 14:41:44.246   325  7907 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-16 14:41:44.246   325  7907 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-16 14:41:44.246   325  7907 V OMXCodec: allocateBuffersOnPort portIndex=1
08-16 14:41:44.246   325  7907 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,08-16 14:41:44.246   325  7907 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b00 on output port
08-16 14:41:44.246   325  7907 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on output port
08-16 14:41:44.246   325  7907 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a10 on output port
08-16 14:41:44.246   325  7907 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57f7510 on output port
08-16 14:41:44.246   325  7907 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-16 14:41:44.247   325  7907 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-16 14:41:44.247   325  1384 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-16 14:41:44.248   325  1384 V AudioCache: notify(0xb16a6940, 6, 0, 0)
,08-16 14:41:44.248   325  1384 V AudioCache: ignored
08-16 14:41:44.248   325  1384 V MediaPlayerService: wait for playback complete
08-16 14:41:44.249   325  7908 V AudioCache: write(0xb16a7000, 4096)
08-16 14:41:44.249   325  7908 V AudioCache: memcpy(0xabe08000, 0xb16a7000, 4096)
08-16 14:41:44.251   325  7908 V AudioCache: write(0xb16a7000, 4096)
08-16 14:41:44.251   325  7908 V AudioCache: memcpy(0xabe09000, 0xb16a7000, 4096)
08-16 14:41:44.252   325  7908 V AudioCache: write(0xb16a7000, 4096)
08-16 14:41:44.252   325  7908 V AudioCache: memcpy(0xabe0a000, 0xb16a7000, 4096)
08-16 14:41:44.253   325  7908 V AudioCache: write(0xb16a7000, 4096)
08-16 14:41:44.253   325  7908 V AudioCache: memcpy(0xabe0b000, 0xb16a7000, 4096)
08-16 14:41:44.253   325  7908 V AudioCache: write(0xb16a7000, 4096)
08-16 14:41:44.253   325  7908 V AudioCache: memcpy(0xabe0c000, 0xb16a7000, 4096)
08-16 14:41:44.254   325  7908 V AudioCache: write(0xb16a7000, 4096)
08-16 14:41:44.254   325  7908 V AudioCache: memcpy(0xabe0d000, 0xb16a7000, 4096)
,08-16 14:41:44.255   325  7908 V AudioCache: write(0xb16a7000, 4096)
08-16 14:41:44.255   325  7908 V AudioCache: memcpy(0xabe0e000, 0xb16a7000, 4096)
08-16 14:41:44.255   325  7908 V AudioCache: write(0xb16a7000, 4096)
08-16 14:41:44.255   325  7908 V AudioCache: memcpy(0xabe0f000, 0xb16a7000, 4096)
08-16 14:41:44.256   325  7908 V AudioCache: write(0xb16a7000, 4096)
08-16 14:41:44.256   325  7908 V AudioCache: memcpy(0xabe10000, 0xb16a7000, 4096)
08-16 14:41:44.257   325  7908 V AudioCache: write(0xb16a7000, 4096)
,08-16 14:41:44.257   325  7908 V AudioCache: memcpy(0xabe11000, 0xb16a7000, 4096)
08-16 14:41:44.257   325  7908 V AudioCache: write(0xb16a7000, 4096)
08-16 14:41:44.257   325  7908 V AudioCache: memcpy(0xabe12000, 0xb16a7000, 4096)
08-16 14:41:44.257   325  7908 V AudioCache: write(0xb16a7000, 4096)
08-16 14:41:44.257   325  7908 V AudioCache: memcpy(0xabe13000, 0xb16a7000, 4096)
08-16 14:41:44.257   325  7908 V AudioCache: write(0xb16a7000, 4096)
,08-16 14:41:44.257   325  7908 V AudioCache: memcpy(0xabe14000, 0xb16a7000, 4096)
08-16 14:41:44.259   325  7908 V AudioCache: write(0xb16a7000, 4096)
08-16 14:41:44.259   325  7908 V AudioCache: memcpy(0xabe15000, 0xb16a7000, 4096)
08-16 14:41:44.259   325  7908 V AudioCache: write(0xb16a7000, 4096)
08-16 14:41:44.259   325  7908 V AudioCache: memcpy(0xabe16000, 0xb16a7000, 4096)
08-16 14:41:44.259   325  7908 V AudioCache: write(0xb16a7000, 4096)
,08-16 14:41:44.259   325  7908 V AudioCache: memcpy(0xabe17000, 0xb16a7000, 4096)
08-16 14:41:44.259   325  7908 V AudioCache: write(0xb16a7000, 4096)
08-16 14:41:44.259   325  7908 V AudioCache: memcpy(0xabe18000, 0xb16a7000, 4096)
08-16 14:41:44.261   325  7908 V AudioCache: write(0xb16a7000, 4096)
08-16 14:41:44.261   325  7908 V AudioCache: memcpy(0xabe19000, 0xb16a7000, 4096)
08-16 14:41:44.261   325  7908 V AudioCache: write(0xb16a7000, 4096)
08-16 14:41:44.261   325  7908 V AudioCache: memcpy(0xabe1a000, 0xb16a7000, 4096)
08-16 14:41:44.261   325  7908 V AudioCache: write(0xb16a7000, 4096)
08-16 14:41:44.261   325  7908 V AudioCache: memcpy(0xabe1b000, 0xb16a7000, 4096)
,08-16 14:41:44.261   325  7908 V AudioCache: write(0xb16a7000, 4096)
08-16 14:41:44.261   325  7908 V AudioCache: memcpy(0xabe1c000, 0xb16a7000, 4096)
08-16 14:41:44.262   325  7908 V AudioCache: write(0xb16a7000, 4096)
08-16 14:41:44.262   325  7908 V AudioCache: memcpy(0xabe1d000, 0xb16a7000, 4096)
08-16 14:41:44.262   325  7908 V AudioCache: write(0xb16a7000, 4096)
08-16 14:41:44.262   325  7908 V AudioCache: memcpy(0xabe1e000, 0xb16a7000, 4096)
08-16 14:41:44.263   325  7908 V AudioCache: write(0xb16a7000, 4096)
08-16 14:41:44.263   325  7908 V AudioCache: memcpy(0xabe1f000, 0xb16a7000, 4096)
08-16 14:41:44.264   325  7908 V AudioCache: write(0xb16a7000, 4096)
08-16 14:41:44.264   325  7908 V AudioCache: memcpy(0xabe20000, 0xb16a7000, 4096)
08-16 14:41:44.264   325  7908 V AudioCache: write(0xb16a7000, 4096)
08-16 14:41:44.264   325  7908 V AudioCache: memcpy(0xabe21000, 0xb16a7000, 4096)
08-16 14:41:44.264   325  7908 V AudioCache: write(0xb16a7000, 4096)
08-16 14:41:44.264   325  7908 V AudioCache: memcpy(0xabe22000, 0xb16a7000, 4096)
08-16 14:41:44.265   325  7908 V AudioCache: write(0xb16a7000, 4096)
08-16 14:41:44.265   325  7908 V AudioCache: memcpy(0xabe23000, 0xb16a7000, 4096)
08-16 14:41:44.266   325  7908 V AudioCache: write(0xb16a7000, 4096)
08-16 14:41:44.266   325  7908 V AudioCache: memcpy(0xabe24000, 0xb16a7000, 4096)
08-16 14:41:44.266   325  7908 V AudioCache: write(0xb16a7000, 4096)
,08-16 14:41:44.266   325  7908 V AudioCache: memcpy(0xabe25000, 0xb16a7000, 4096)
,08-16 14:41:44.267   325  7908 V AudioCache: write(0xb16a7000, 4096),
08-16 14:41:44.267   325  7908 V AudioCache: memcpy(0xabe26000, 0xb16a7000, 4096)
08-16 14:41:44.268   325  7908 V AudioCache: write(0xb16a7000, 4096)
08-16 14:41:44.268   325  7908 V AudioCache: memcpy(0xabe27000, 0xb16a7000, 4096)
08-16 14:41:44.269   325  7908 V AudioCache: write(0xb16a7000, 4096),
08-16 14:41:44.269   325  7908 V AudioCache: memcpy(0xabe28000, 0xb16a7000, 4096)
08-16 14:41:44.270   325  7908 V AudioCache: write(0xb16a7000, 4096)
08-16 14:41:44.270   325  7908 V AudioCache: memcpy(0xabe29000, 0xb16a7000, 4096)
08-16 14:41:44.271   325  7908 V AudioCache: write(0xb16a7000, 4096)
,08-16 14:41:44.271   325  7908 V AudioCache: memcpy(0xabe2a000, 0xb16a7000, 4096)
08-16 14:41:44.272   325  7908 V AudioCache: write(0xb16a7000, 4096)
08-16 14:41:44.272   325  7908 V AudioCache: memcpy(0xabe2b000, 0xb16a7000, 4096)
08-16 14:41:44.272   325  7908 V AudioCache: write(0xb16a7000, 4096)
08-16 14:41:44.272   325  7908 V AudioCache: memcpy(0xabe2c000, 0xb16a7000, 4096),
08-16 14:41:44.273   325  7908 V AudioCache: write(0xb16a7000, 4096)
08-16 14:41:44.273   325  7908 V AudioCache: memcpy(0xabe2d000, 0xb16a7000, 4096)
08-16 14:41:44.274   325  7908 V AudioCache: write(0xb16a7000, 4096)
08-16 14:41:44.274   325  7908 V AudioCache: memcpy(0xabe2e000, 0xb16a7000, 4096)
08-16 14:41:44.274   325  7908 V AudioCache: write(0xb16a7000, 4096),
08-16 14:41:44.274   325  7908 V AudioCache: memcpy(0xabe2f000, 0xb16a7000, 4096)
08-16 14:41:44.275   325  7908 V AudioCache: write(0xb16a7000, 4096)
08-16 14:41:44.275   325  7908 V AudioCache: memcpy(0xabe30000, 0xb16a7000, 4096)
08-16 14:41:44.276   325  7908 V AudioCache: write(0xb16a7000, 4096)
,08-16 14:41:44.276   325  7908 V AudioCache: memcpy(0xabe31000, 0xb16a7000, 4096)
08-16 14:41:44.277   325  7908 V AudioCache: write(0xb16a7000, 4096)
08-16 14:41:44.277   325  7908 V AudioCache: memcpy(0xabe32000, 0xb16a7000, 4096)
08-16 14:41:44.277   325  7908 V AudioCache: write(0xb16a7000, 4096)
08-16 14:41:44.277   325  7908 V AudioCache: memcpy(0xabe33000, 0xb16a7000, 4096)
08-16 14:41:44.278   325  7908 V AudioCache: write(0xb16a7000, 4096)
08-16 14:41:44.278   325  7908 V AudioCache: memcpy(0xabe34000, 0xb16a7000, 4096),
,08-16 14:41:44.279   325  7908 V AudioCache: write(0xb16a7000, 4096)
,08-16 14:41:44.279   325  7908 V AudioCache: memcpy(0xabe35000, 0xb16a7000, 4096)
08-16 14:41:44.279   325  7908 V AudioCache: write(0xb16a7000, 4096)
08-16 14:41:44.279   325  7908 V AudioCache: memcpy(0xabe36000, 0xb16a7000, 4096)
08-16 14:41:44.280   325  7908 V AudioCache: write(0xb16a7000, 4096)
08-16 14:41:44.280   325  7908 V AudioCache: memcpy(0xabe37000, 0xb16a7000, 4096)
08-16 14:41:44.281   325  7908 V AudioCache: write(0xb16a7000, 4096)
08-16 14:41:44.281   325  7908 V AudioCache: memcpy(0xabe38000, 0xb16a7000, 4096)
08-16 14:41:44.281   325  7908 V AudioCache: write(0xb16a7000, 4096)
08-16 14:41:44.281   325  7908 V AudioCache: memcpy(0xabe39000, 0xb16a7000, 4096)
08-16 14:41:44.281   325  7907 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-16 14:41:44.281   325  7908 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-16 14:41:44.281   325  7908 V AwesomePlayer: postAudioEOS() 
08-16 14:41:44.281   325  7908 V AudioCache: write(0xb16a7000, 280)
08-16 14:41:44.281   325  7908 V AudioCache: memcpy(0xabe3a000, 0xb16a7000, 280)
08-16 14:41:44.283   325  7905 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-16 14:41:44.283   325  7905 V AwesomePlayer: onStreamDone
08-16 14:41:44.283   325  7905 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-16 14:41:44.283   325  7905 V AudioCache: notify(0xb16a6940, 2, 0, 0)
08-16 14:41:44.283   325  7905 V AudioCache: playback complete
08-16 14:41:44.283   325  7905 V AwesomePlayer: pause_l() 
08-16 14:41:44.283   325  7905 V AudioCache: notify(0xb16a6940, 7, 0, 0)
08-16 14:41:44.283   325  7905 V AudioCache: ignored
08-16 14:41:44.283   325  7905 V AwesomePlayer: cancelPlayerEvents
08-16 14:41:44.283   325  1384 V AudioCache: wait - success
08-16 14:41:44.283   325  1384 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-16 14:41:44.283   325  7905 D AudioPlayer: Pause Playback at 1068125
08-16 14:41:44.283   325  1384 V AwesomePlayer: reset_l() 
08-16 14:41:44.283   325  1384 V AudioCache: notify(0xb16a6940, 8, 0, 0)
08-16 14:41:44.283   325  1384 V AudioCache: ignored
08-16 14:41:44.283   325  1384 V AwesomePlayer: cancelPlayerEvents
08-16 14:41:44.283   325  1384 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-16 14:41:44.283   325  1384 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-16 14:41:44.283   325  1384 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-16 14:41:44.283   325  1384 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-16 14:41:44.284   325  1384 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-16 14:41:44.284   325  7907 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-16 14:41:44.284   325  7907 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-16 14:41:44.284   325  7907 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-16 14:41:44.284   325  7907 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f79c0 on port 0
08-16 14:41:44.284   325  7907 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-16 14:41:44.284   325  7907 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7920 on port 0
08-16 14:41:44.284   325  7907 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-16 14:41:44.284   325  7907 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7790 on port 0
08-16 14:41:44.284   325  7907 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-16 14:41:44.284   325  7907 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f76a0 on port 0
08-16 14:41:44.284   325  7907 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-16 14:41:44.284   325  7907 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-16 14:41:44.284   325  7907 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb57f7510 on port 1
0,8-16 14:41:44.284   325  7907 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-16 14:41:44.284   325  7907 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a10 on port 1
08-16 14:41:44.284   325  7907 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-16 14:41:44.284   325  7907 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ab0 on port 1
08-16 14:41:44.284   325  7907 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-16 14:41:44.284   325  7907 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b00 on port 1
08-16 14:41:44.284   325  7907 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-16 14:41:44.285   325  7907 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-16 14:41:44.285   325  1384 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-16 14:41:44.285   325  1384 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-16 14:41:44.285   325  7907 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-16 14:41:44.285   325  7907 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-16 14:41:44.285   325  7907 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-16 14:41:44.285   325  1384 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-16 14:41:44.285   325  1384 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-16 14:41:44.285   325  1384 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-16 14:41:44.286   325  1384 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-16 14:41:44.286   325  1384 D AudioPlayer: AudioPlayer releasing audio source
08-16 14:41:44.286   325  1384 D AudioPlayer: AudioPlayer done releasing audio source
08-16 14:41:44.286   325  1384 V AwesomePlayer: reset_l() 
08-16 14:41:44.286   325  1384 V AwesomePlayer: cancelPlayerEvents
08-16 14:41:44.286   325  1384 V AwesomePlayer: ~AwesomePlayer call
08-16 14:41:44.286   325  1384 V AwesomePlayer: reset_l() 
08-16 14:41:44.286   325  1384 V AwesomePlayer: cancelPlayerEvents
08-16 14:41:44.287  7872  7904 V SoundPool: close(31)
08-16 14:41:44.287  7872  7904 V SoundPool: pointer = 0x9fff5000, size = 205080, sampleRate = 48000, numChannels = 2
08-16 14:41:44.307  7872  7872 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-16 14:41:44.308  7872  7872 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
08-16 14:41:44.310  7872  7872 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:9042
,08-16 14:41:44.311  7872  7872 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-16 14:41:44.312  7650  7666 I UEI.SmartControl: ------ IControl API: 11
08-16 14:41:44.313  7650  7666 I UEI.SmartControl: Registering callback...
08-16 14:41:44.314  7650  7667 I UEI.SmartControl: ------ IControl API: 19
08-16 14:41:44.314  7650  7667 I UEI.SmartControl: Registering Services Ready callback...
08-16 14:41:44.315  7650  7667 I UEI.SmartControl: Notify client services are ready...
08-16 14:41:44.316  7872  7896 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-16 14:41:44.316  7872  7902 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-16 14:41:44.316  7872  7902 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-16 14:41:44.317  7872  7872 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-16 14:41:44.317  7872  7872 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-16 14:41:44.317  7650  7666 I UEI.SmartControl: ------ IControl API: 8
08-16 14:41:44.318  7872  7872 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-16 14:41:44.319  7872  7872 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-16 14:41:44.319  7872  7872 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-16 14:41:44.319  7872  7872 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-16 14:41:44.320  7872  7872 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-16 14:41:44.320  7872  7872 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-16 14:41:44.321  7872  7872 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
,08-16 14:41:44.327  7872  7872 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-16 14:41:44.328  7872  7872 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-16 14:41:44.329  7872  7872 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-16 14:41:44.329  7872  7872 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-16 14:41:44.330  7872  7872 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-16 14:41:44.330  7872  7872 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-16 14:41:44.331  7872  7872 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-16 14:41:44.332  7872  7872 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1471351304331]
08-16 14:41:44.333  7872  7872 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
,08-16 14:41:44.336  1038  1945 I ActivityManager: Killing 7118:com.google.android.setupwizard/u0a46 (adj 15): empty #17
08-16 14:41:44.356  7872  7909 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-16 14:41:44.364  1038  1588 W libprocessgroup: failed to open /acct/uid_10046/pid_7118/cgroup.procs: No such file or directory
08-16 14:41:44.369  7872  7872 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,08-16 14:41:44.369  7872  7872 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-16 14:41:44.369  7872  7872 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-16 14:41:44.370  7872  7872 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-16 14:41:44.370  7872  7872 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-16 14:41:44.370  7872  7872 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-16 14:41:44.370  7872  7872 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
08-16 14:41:44.378  7872  7872 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
08-16 14:41:44.893  1038  1909 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 14:41:44.894  1038  1909 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@35edde9b mBinding = false
,08-16 14:41:44.923  1038  1038 D LocationManagerService: getAllProviders()=[passive, gps, network]
,08-16 14:41:44.923  1038  1038 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-16 14:41:44.923  1038  1038 D Ulp_jni : JNI:system_update. Event-4
08-16 14:41:44.924  1038  1120 D BluetoothManagerService: Message: 2
08-16 14:41:44.925  1038  1120 D BluetoothManagerService: Sending off request.
08-16 14:41:44.926  6999  7015 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-16 14:41:44.927  6999  7553 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-16 14:41:44.927  6999  7553 D BluetoothAdapterProperties: Setting state to 13
08-16 14:41:44.927  6999  7553 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-16 14:41:44.928  6999  7553 D BluetoothAdapterProperties: onBluetoothDisable()
08-16 14:41:44.928  6999  7553 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-16 14:41:44.930  6999  7557 D BluetoothAdapterProperties: Scan Mode:20
08-16 14:41:44.931  6999  7553 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,08-16 14:41:44.936  6999  7686 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 14:41:44.938  6999  7685 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-16 14:41:44.938  6999  7685 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 14:41:44.938  6999  7685 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-16 14:41:44.938  6999  7685 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-16 14:41:44.938  6999  7685 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-16 14:41:44.938  6999  7685 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-16 14:41:44.938  6999  7685 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-16 14:41:44.938  6999  7685 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-16 14:41:44.939  6999  7696 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 14:41:44.939  6999  7697 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 14:41:44.940  6999  7699 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 14:41:44.940  6999  7612 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-16 14:41:44.940  6999  7612 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-16 14:41:44.943  6999  7553 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-16 14:41:44.947  6999  7612 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 14:41:44.947  6999  7612 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 14:41:44.947  6999  7612 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 14:41:44.947  6999  7612 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 14:41:44.947  6999  7612 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 14:41:44.947  6999  7612 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 14:41:44.947  6999  7612 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 14:41:44.947  6999  7612 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 14:41:44.947  6999  7612 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 14:41:44.947  6999  7612 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-16 14:41:44.947  6999  7612 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-16 14:41:44.947  6999  7612 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
,08-16 14:41:44.960  6608  6608 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:41:44.961  6608  6608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 14:41:44.961  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:41:44.961  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 14:41:44.961  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 14:41:44.961  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 14:41:44.961  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 14:41:44.961  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 14:41:44.961  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 14:41:44.965  6608  6608 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:41:44.965  6608  6608 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 14:41:44.968  6608  6608 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:41:44.968  6608  6608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 14:41:44.968  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:41:44.968  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 14:41:44.968  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 14:41:44.968  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 14:41:44.968  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 14:41:44.968  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 14:41:44.968  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 14:41:44.969  6608  6608 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:41:44.969  6608  6608 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 14:41:44.972  6608  6608 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:41:44.972  6608  6608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 14:41:44.972  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:41:44.972  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 14:41:44.972  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 14:41:44.972  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 14:41:44.972  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 14:41:44.972  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 14:41:44.972  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 14:41:44.975  6608  6608 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:41:44.975  6608  6608 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 14:41:44.980  1038  1120 D BluetoothManagerService: Message: 60
08-16 14:41:44.980  1038  1120 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-16 14:41:44.980  1038  1120 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-16 14:41:44.982  1927  1927 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-16 14:41:44.992  1589  1589 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-16 14:41:44.997  6608  6608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:41:44.999  6608  6608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 14:41:45.001  1038  1448 D ConnectivityService: Failed to find a new network - expiring NetTransition Wakelock
08-16 14:41:45.003  6608  6608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:41:45.005  6999  6999 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-16 14:41:45.005  6999  6999 D BluetoothMapService: STATE_TURNING_OFF
08-16 14:41:45.005  6999  6999 V BluetoothMapService: Handler(): got msg=4
08-16 14:41:45.005  6999  6999 D BluetoothMapService: MAP Service closeService in
08-16 14:41:45.006  6999  6999 D BluetoothMapMasInstance: MAP Service shutdown
08-16 14:41:45.006  6999  6999 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-16 14:41:45.006  6999  6999 V BluetoothMapService: MAP Service closeService out
08-16 14:41:45.007  6999  6999 V BtOppService: Receiver DISABLED_ACTION 
08-16 14:41:45.007  6999  6999 I BtOppRfcommListener: stopping Accept Thread
08-16 14:41:45.007  6999  6999 V BtOppRfcommListener: close mBtServerSocket
08-16 14:41:45.008  6999  7696 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-16 14:41:45.008  6999  6999 V BtOppRfcommListener: waiting for thread to terminate
08-16 14:41:45.008  6999  6999 V BtOppRfcommListener: done waiting for thread to terminate
08-16 14:41:45.015  6879  6879 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
,08-16 14:41:45.022  6608  6679 D io.jxcore.node.ConnectivityMonitor: stop
08-16 14:41:45.022  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:41:45.023  6879  6879 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-16 14:41:45.027  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:41:45.027  6608  6679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@387a5767 removed from the list
08-16 14:41:45.027  6608  6679 D io.jxcore.node.ConnectivityMonitor: stop
08-16 14:41:45.027  6608  6679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:41:45.027  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:41:45.028  6608  6679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 14:41:45.028  6608  6679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@33cbe5bd added. We now have 4 listener(s)
08-16 14:41:45.028  6608  6679 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 14:41:45.032  6999  6999 V BtOppService: onDestroy
08-16 14:41:45.034  6999  6999 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-16 14:41:45.038  6999  6999 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-16 14:41:45.038  6999  6999 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 14:41:45.038  6999  6999 V BluetoothPbapReceiver: ***********state = 13
08-16 14:41:45.040  6999  6999 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-16 14:41:45.042  6999  6999 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 14:41:45.042  6999  6999 V BluetoothPbapService: state: 13
08-16 14:41:45.042  6999  6999 V BluetoothPbapService: Pbap Service closeService in
,08-16 14:41:45.048  2178  2178 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-16 14:41:45.049  6999  6999 V BluetoothPbapService: successfully stopped pbap service
08-16 14:41:45.049  6999  6999 V BluetoothPbapService: Pbap Service closeService out
08-16 14:41:45.057  6999  6999 V BluetoothPbapService: Pbap Service onDestroy
08-16 14:41:45.057  6999  6999 V BluetoothPbapService: Pbap Service closeService in
08-16 14:41:45.057  6999  6999 V BluetoothPbapService: Pbap Service closeService out
08-16 14:41:45.057  6999  6999 D LGBluetoothPbapAdapter: [BTUI] cleanup
,08-16 14:41:45.059  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:41:45.059  6608  6679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@33cbe5bd removed from the list
08-16 14:41:45.059  6608  6679 D io.jxcore.node.ConnectivityMonitor: stop
08-16 14:41:45.059  6608  6679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:41:45.059  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:41:45.067  6608  6679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 14:41:45.067  6608  6679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1afe97b2 added. We now have 4 listener(s)
08-16 14:41:45.067  6608  6679 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 14:41:45.071  1038  1945 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 14:41:45.071  1038  1945 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@35edde9b mBinding = false
08-16 14:41:45.071  6879  6879 D DockEventReceiver: finishStartingService: stopping service
08-16 14:41:45.072  1038  1120 D BluetoothManagerService: Message: 2
08-16 14:41:45.072  1038  1120 D BluetoothManagerService: Sending off request.
08-16 14:41:45.072  6999  7015 D LGBluetoothServiceAdapter: [BTUI] Precleanup
,08-16 14:41:45.073  6879  6879 D BluetoothPbap: Proxy object disconnected
08-16 14:41:45.073  6879  6879 D PbapServerProfile: Bluetooth service disconnected
08-16 14:41:45.074  6999  7015 D BluetoothAdapterService: disable() : BT State is not STATE_ON. Can't disable BT
08-16 14:41:45.074  1038  1120 E BluetoothManagerService: IBluetooth.disable() returned false
08-16 14:41:45.076  6879  6879 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-16 14:41:45.081  6879  6879 D BluetoothPermissionRequest: onReceive
08-16 14:41:45.081  6879  6879 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-16 14:41:45.087  6879  6879 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-16 14:41:45.090  6999  6999 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-16 14:41:45.090  6999  6999 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-16 14:41:45.091  6999  6999 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-16 14:41:45.094  6999  6999 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-16 14:41:45.094  6999  6999 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-16 14:41:45.096  6999  6999 V BluetoothFtpService: Ftp Service onStartCommand
08-16 14:41:45.097  6999  6999 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 14:41:45.097  6999  6999 V BluetoothFtpService: Ftp Service closeService
08-16 14:41:45.097  6999  6999 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-16 14:41:45.098  6999  6999 V BluetoothFtpService: successfully stopped ftp service
08-16 14:41:45.098  6999  6999 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-16 14:41:45.099  6999  6999 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-16 14:41:45.099  6999  6999 V BluetoothSapReceiver: SapReceiver onReceive 
08-16 14:41:45.099  6999  6999 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 14:41:45.099  6999  6999 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-16 14:41:45.099  6999  6999 V BluetoothSapReceiver: Calling SAP service start service with action = null
,08-16 14:41:45.100  6999  6999 V BluetoothFtpService: Ftp Service onDestroy
08-16 14:41:45.100  6999  6999 V BluetoothFtpService: Ftp Service closeService
08-16 14:41:45.104  6999  6999 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 14:41:45.104  6999  6999 V BluetoothSapService: state: 13
08-16 14:41:45.104  6999  6999 V BluetoothSapService: Stopping SAP server process
,08-16 14:41:45.105  6999  6999 V BluetoothSapService: Sap Service closeSapService in
08-16 14:41:45.106  6999  6999 V BluetoothSapService: Close listen Socket : 
08-16 14:41:45.106  6999  6999 V BluetoothSapService: Close rfcomm Socket : 
08-16 14:41:45.106  6999  6999 V BluetoothSapService: Close sapd  Socket : 
08-16 14:41:45.110  6999  6999 V BluetoothSapService: Sap Service closeSapService out
08-16 14:41:45.110  6999  6999 V BluetoothSapService: Sap Service onDestroy
08-16 14:41:45.110  6999  6999 V BluetoothSapService: Sap Service closeSapService in
08-16 14:41:45.110  6999  6999 V BluetoothSapService: Close listen Socket : 
08-16 14:41:45.110  6999  6999 V BluetoothSapService: Close rfcomm Socket : 
08-16 14:41:45.110  6999  6999 V BluetoothSapService: Close sapd  Socket : 
08-16 14:41:45.111  6999  6999 V BluetoothSapService: Sap Service closeSapService out
,08-16 14:41:45.851  6999  7557 D bt_hci_bdroid: cleanup
,08-16 14:41:45.858  6999  7614 I bt_lpm  : LPM is already off!!!
08-16 14:41:45.858  6999  7670 I bt_userial_mct: exiting userial_read_thread
08-16 14:41:45.858  6999  7670 D bt_userial_mct: Leaving userial_evt_read_thread()
08-16 14:41:45.861  6999  7612 W bt-btif : ag scb idx 1 not allocated
08-16 14:41:45.861  6999  7612 E bt-btif : BTA AG is already disabled, ignoring ...
08-16 14:41:45.862  6999  7612 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 14:41:45.862  6999  7612 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 14:41:45.862  6999  7612 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 14:41:45.862  6999  7612 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 14:41:45.862  6999  7612 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 14:41:45.862  6999  7612 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 14:41:45.862  6999  7612 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 14:41:45.862  6999  7612 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 14:41:45.862  6999  7612 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 14:41:45.862  6999  7612 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 14:41:45.863  6999  7612 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 14:41:45.863  6999  7612 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 14:41:45.863  6999  7612 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 14:41:45.863  6999  7612 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 14:41:45.863  6999  7612 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 14:41:45.863  6999  7612 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 14:41:45.863  6999  7612 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 14:41:45.863  6999  7612 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 14:41:45.863  6999  7612 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-16 14:41:45.864  6999  7557 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-16 14:41:45.864  6999  7614 I bt_vendor: hw_epilog_process
08-16 14:41:45.864  6999  7557 D bt_hci_bdroid: cleanup Finalizing cleanup
08-16 14:41:45.864  6999  7557 D bt_userial_mct: userial_close
08-16 14:41:45.864  6999  7557 E bt_userial_mct: pthread_join() FAILED result:3
08-16 14:41:45.864  6999  7557 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-16 14:41:45.871  6999  7557 D bt_hci_bdroid: set_power 0
08-16 14:41:45.871  6999  7557 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-16 14:41:45.871  6999  7557 I bt_vendor: bluetooth satus is on
08-16 14:41:45.871  6999  7557 I bt_vendor: bt-vendor : resetting BT status
08-16 14:41:45.871  6999  7557 I bt_vendor: Starting hciattach daemon
08-16 14:41:45.871  6999  7557 I bt_vendor: try to set false
,08-16 14:41:45.877  6999  7557 I bt_vendor: Starting hciattach daemon
08-16 14:41:45.877  6999  7557 I bt_vendor: try to set false
08-16 14:41:45.878  6999  7557 I bt_vendor: cleanup
08-16 14:41:45.879  6999  7612 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-16 14:41:45.879  6999  7557 I GKI_LINUX: GKI_exit_task 0 done
08-16 14:41:45.879  6999  7557 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-16 14:41:45.881  6999  7553 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-16 14:41:45.886  6999  6999 D HeadsetService: Received stop request...Stopping profile...
,08-16 14:41:45.891  6999  6999 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-16 14:41:45.891  6999  6999 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-16 14:41:45.891  6999  6999 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@316e4518
08-16 14:41:45.893  6999  7594 D HeadsetStateMachine: Exit Disconnected: -1
08-16 14:41:45.895  1839  1839 D BluetoothHeadset: Proxy object disconnected
08-16 14:41:45.895  1839  1839 D BluetoothHeadset: Proxy object disconnected
08-16 14:41:45.895  1839  1839 D BluetoothHeadset: Proxy object disconnected
08-16 14:41:45.895  1038  1038 D BluetoothHeadset: Proxy object disconnected
08-16 14:41:45.895  1038  1038 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-16 14:41:45.898  6999  6999 D A2dpService: Received stop request...Stopping profile...
,08-16 14:41:45.902  6999  7604 D A2dpStateMachine: Exit Disconnected: -1
08-16 14:41:45.905  6999  7553 D BluetoothAdapterState: Stopping profile services that were post enabled
08-16 14:41:45.905  6999  6999 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-16 14:41:45.907  6999  6999 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-16 14:41:45.907  6999  6999 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-16 14:41:45.907  6999  6999 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@316e4518
08-16 14:41:45.909  6999  6999 D HidService: Received stop request...Stopping profile...
08-16 14:41:45.909  6999  6999 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@316e4518
08-16 14:41:45.911  1038  1038 D BluetoothA2dp: Proxy object disconnected
08-16 14:41:45.911  1038  1038 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,08-16 14:41:45.916  6999  6999 D HealthService: Received stop request...Stopping profile...
08-16 14:41:45.916  6999  6999 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@316e4518
08-16 14:41:45.918  6999  6999 D HeadsetStateMachine: Unbinding service...
08-16 14:41:45.919  6999  6999 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-16 14:41:45.919  6999  6999 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-16 14:41:45.919  6999  6999 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-16 14:41:45.919  6999  6999 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-16 14:41:45.919  6999  6999 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-16 14:41:45.919  6999  6999 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-16 14:41:45.919  6999  6999 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-16 14:41:45.921  6999  6999 D PanService: Received stop request...Stopping profile...
08-16 14:41:45.921  6999  6999 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@316e4518
08-16 14:41:45.922  6999  6999 D BtGatt.DebugUtils: handleDebugAction() action=null
08-16 14:41:45.923  6999  6999 D BtGatt.GattService: Received stop request...Stopping profile...
08-16 14:41:45.923  6999  6999 D BtGatt.GattService: stop()
08-16 14:41:45.923  6999  6999 D BtGatt.AdvertiseManager: advertise clients cleared
08-16 14:41:45.924  6999  6999 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@316e4518
,08-16 14:41:45.929  6999  6999 D BluetoothMapService: Received stop request...Stopping profile...
08-16 14:41:45.929  6999  6999 D BluetoothMapService: stop()
08-16 14:41:45.930  6999  6999 D BluetoothMapEmailAppObserver: deinitObservers()
08-16 14:41:45.930  6999  6999 D BluetoothMapEmailAppObserver: removeReceiver()
08-16 14:41:45.931  6999  6999 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@316e4518
08-16 14:41:45.932  6999  6999 I BluetoothA2dpServiceJni: cleanupNative
08-16 14:41:45.933  6999  7605 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-16 14:41:45.933  6999  6999 I GKI_LINUX: GKI_exit_task 2 done
08-16 14:41:45.933  6999  6999 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-16 14:41:45.933  6999  6999 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-16 14:41:45.933  6999  6999 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-16 14:41:45.934  6999  6999 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-16 14:41:45.934  6999  6999 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-16 14:41:45.934  6999  6999 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-16 14:41:45.934  6999  6999 V BluetoothMapService: Handler(): got msg=4
08-16 14:41:45.934  6999  6999 D BluetoothMapService: MAP Service closeService in
08-16 14:41:45.934  6999  6999 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-16 14:41:45.934  6999  6999 V BluetoothMapService: MAP Service closeService out
08-16 14:41:45.935  6999  7553 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-16 14:41:45.935  6999  7553 D BluetoothAdapterProperties: Setting state to 10
08-16 14:41:45.935  6999  7553 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-16 14:41:45.937  1038  1120 D BluetoothManagerService: Message: 60
08-16 14:41:45.937  1038  1120 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-16 14:41:45.937  1038  1120 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
,08-16 14:41:45.943  6999  7553 I BluetoothAdapterState: Entering OffState
08-16 14:41:45.943  1839  2434 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 14:41:45.945  6999  6999 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-16 14:41:45.945  6999  6999 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-16 14:41:45.944  6879  6895 D BluetoothPan: onBluetoothStateChange on: false
08-16 14:41:45.950  6879  6895 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-16 14:41:45.953  6999  6999 D BluetoothMapService: cleanup()
08-16 14:41:45.953  6999  6999 D BluetoothMapService: MAP Service closeService in
08-16 14:41:45.953  6999  6999 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-16 14:41:45.953  6999  6999 V BluetoothMapService: MAP Service closeService out
08-16 14:41:45.954  1038  1120 D BluetoothA2dp: onBluetoothStateChange: up=false
08-16 14:41:45.955  1839  1855 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 14:41:45.955  6879  6895 D BluetoothA2dp: onBluetoothStateChange: up=false
08-16 14:41:45.956  1839  3933 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 14:41:45.956  1038  1120 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 14:41:45.957  6879  6895 D BluetoothPbap: onBluetoothStateChange: up=false
08-16 14:41:45.957  6879  6895 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-16 14:41:45.958  6879  6895 D BluetoothMap: onBluetoothStateChange: up=false
08-16 14:41:45.959  1038  1120 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-16 14:41:45.959  1038  1120 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-16 14:41:45.961  1038  1120 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-16 14:41:45.961  1038  1120 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-16 14:41:45.961  1038  1120 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@35edde9b mBinding = false
08-16 14:41:45.961  1038  1120 D BluetoothManagerService: Sending unbind request.
08-16 14:41:45.966  6999  7557 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-16 14:41:45.970  6999  6999 I GKI_LINUX: GKI_exit_task 1 done
08-16 14:41:45.970  6999  6999 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-16 14:41:45.970  6999  6999 I BluetoothServiceJni: cleanupNative: return from cleanup
08-16 14:41:45.970  6999  6999 I art     : --- WEIRD: removing null entry 248
08-16 14:41:45.970  6999  6999 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
08-16 14:41:45.970  6999  6999 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-16 14:41:45.972  6999  6999 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-16 14:41:45.973  1038  1120 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-16 14:41:45.975  6999  6999 I art     : System.exit called, status: 0
08-16 14:41:45.975  6999  6999 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-16 14:41:45.994   325   325 V AudioFlinger: 6999 died, releasing its sessions
08-16 14:41:45.994   325   325 V AudioFlinger:  pid 1839 @ 0
08-16 14:41:45.994   325   325 V AudioFlinger:  pid 3346 @ 1
08-16 14:41:45.994   325   325 V AudioFlinger:  pid 3346 @ 2
,08-16 14:41:45.998  1927  1927 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: disconnected from LGBluetoothAPIAdapter
08-16 14:41:45.999  1927  2129 D LGBluetoothAPIService: Message: 101
08-16 14:41:45.999  1927  2129 E LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED
08-16 14:41:45.999  1927  2129 D LGBluetoothAPIService: Calling onBluetoothServiceDown callbacks
08-16 14:41:45.999  1927  2129 D LGBluetoothAPIService: Broadcasting onBluetoothServiceDown() to 0 receivers.
08-16 14:41:46.004  6879  6879 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-16 14:41:46.188  1038  1981 I ActivityManager: Process com.android.bluetooth (pid 6999) has died
,08-16 14:41:46.189  1038  1981 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer in 1000ms
08-16 14:41:46.189  1038  1981 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 11000ms
08-16 14:41:46.201  1589  1589 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-16 14:41:46.202  1927  1927 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-16 14:41:46.202  1927  2129 D LGBluetoothAPIService: Message: 2
08-16 14:41:46.202  1927  2129 D LGBluetoothAPIService: unbindAndFinish(): null mBinding = false
08-16 14:41:46.207  1589  1589 D BluetoothAdapter: 388559202: getState() :  mService = null. Returning STATE_OFF
08-16 14:41:46.207  1589  1589 D BluetoothAdapter: 388559202: getState() :  mService = null. Returning STATE_OFF
,08-16 14:41:46.208  6879  6879 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-16 14:41:46.209  6879  6879 D LGBluetoothEventManager: [BTUI] clear device connection state
08-16 14:41:46.212  6608  6608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:41:46.213  6879  6879 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-16 14:41:46.213  6608  6608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:41:46.275  1038  1053 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=7968 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
08-16 14:41:46.277  6879  6879 D DockEventReceiver: finishStartingService: stopping service
,08-16 14:41:46.377  7968  7968 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-16 14:41:46.377  7968  7968 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-16 14:41:46.378  7968  7968 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
,08-16 14:41:46.378  7968  7968 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-16 14:41:46.399  7968  7968 D BluetoothAdapterApp: Loading JNI Library
,08-16 14:41:46.437  7968  7968 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@3ccfb600 Instance Count = 1
,08-16 14:41:46.445  7968  7968 D BluetoothAdapterApp: onCreate
,08-16 14:41:46.475  7968  7968 D ProfileConfigQcom: [BTUI] HeadsetService is supported
,08-16 14:41:46.475  7968  7968 D ProfileConfigQcom: Adding HeadsetService
08-16 14:41:46.475  7968  7968 D ProfileConfigQcom: [BTUI] A2dpService is supported
,08-16 14:41:46.475  7968  7968 D ProfileConfigQcom: Adding A2dpService
08-16 14:41:46.475  7968  7968 D ProfileConfigQcom: [BTUI] HidService is supported
08-16 14:41:46.476  7968  7968 D ProfileConfigQcom: Adding HidService
08-16 14:41:46.476  7968  7968 D ProfileConfigQcom: [BTUI] HealthService is supported
08-16 14:41:46.476  7968  7968 D ProfileConfigQcom: Adding HealthService
08-16 14:41:46.476  7968  7968 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-16 14:41:46.477  7968  7968 D ProfileConfigQcom: [BTUI] PanService is supported
08-16 14:41:46.478  7968  7968 D ProfileConfigQcom: Adding PanService
08-16 14:41:46.478  7968  7968 D ProfileConfigQcom: [BTUI] GattService is supported
08-16 14:41:46.478  7968  7968 D ProfileConfigQcom: Adding GattService
08-16 14:41:46.478  7968  7968 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-16 14:41:46.478  7968  7968 D ProfileConfigQcom: Adding BluetoothMapService
08-16 14:41:46.479  7968  7968 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-16 14:41:46.480  7968  7968 V BluetoothPbapReceiver: PbapReceiver onReceive 
,08-16 14:41:46.481  7968  7968 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED,
08-16 14:41:46.481  7968  7968 V BluetoothPbapReceiver: ***********state = 10
,08-16 14:41:46.483  7968  7968 V LGMDMManagerInternal: Create singleton instance,
08-16 14:41:46.573  7968  7968 D LGBluetoothAPIServer: [BTUI] onCreate()
08-16 14:41:46.573  7968  7968 D LGBluetoothAPIServer: [BTUI] onBind()
,08-16 14:41:46.581  2178  2178 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-16 14:41:46.582  1927  1927 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-16 14:41:46.583  1927  2129 D LGBluetoothAPIService: Message: 100
08-16 14:41:46.583  1927  2129 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
,08-16 14:41:46.593  6879  6879 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
,08-16 14:41:46.599  6879  6879 D BluetoothPermissionRequest: onReceive
08-16 14:41:46.601  6879  6879 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-16 14:41:46.601  6879  6879 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-16 14:41:46.603  6879  6879 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-16 14:41:46.608  7968  7968 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
,08-16 14:41:46.613  7968  7968 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-16 14:41:46.616  7968  7968 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-16 14:41:46.616  7968  7968 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-16 14:41:46.617  7968  7968 V BluetoothSapReceiver: SapReceiver onReceive 
08-16 14:41:46.618  7968  7968 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 14:41:46.618  7968  7968 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-16 14:41:46.626  7618  7618 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,08-16 14:41:46.672  7650  7704 D UEI.SmartControl: Internal timer expired: 1
,08-16 14:41:46.672  7650  7704 D UEI.SmartControl: unbind internal service
,08-16 14:41:46.998  7650  7701 D serial_port: close(fd = 25)
,08-16 14:41:47.011  7650  7701 I UEI.SmartControl: Serial port is closed.
,08-16 14:41:50.081  6608  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 14:41:50.091  1038  1588 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 14:41:50.091  1038  1588 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
08-16 14:41:50.104  1038  1038 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-16 14:41:50.104  1038  1038 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-16 14:41:50.104  1038  1038 D Ulp_jni : JNI:system_update. Event-4
,08-16 14:41:50.107  1038  1120 D BluetoothManagerService: Message: 1
08-16 14:41:50.107  1038  1120 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
,08-16 14:41:50.134  1038  1120 D BluetoothManagerService: Message: 20
08-16 14:41:50.135  1038  1120 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1a95fd02:true
,08-16 14:41:50.138  7968  7968 D BluetoothAdapterState: make
08-16 14:41:50.143  7968  7968 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-16 14:41:50.143  7968  7968 I bluedroid-qcom: init
08-16 14:41:50.144  7968  7998 I BluetoothAdapterState: Entering OffState
08-16 14:41:50.145  7968  7968 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-16 14:41:50.145  7968  7968 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-16 14:41:50.145  7968  7968 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-16 14:41:50.145  7968  7968 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-16 14:41:50.145  7968  7968 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-16 14:41:50.147  7968  7968 I bluedroid-qcom: get_profile_interface socket
08-16 14:41:50.147  7968  7968 I bluedroid-qcom: get_profile_interface map_client
,08-16 14:41:50.152  7968  8002 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-16 14:41:50.149  8001  8001 W bdaddr_loader: type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 14:41:50.157  7968  8002 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-16 14:41:50.149  8001  8001 W bdaddr_loader: type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 14:41:50.167  8001  8001 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-16 14:41:50.167  8001  8001 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-16 14:41:50.167  8001  8001 I LGFTMITEM: [GET_FTM][id=8], offset=16384
,08-16 14:41:50.171  1038  1038 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-16 14:41:50.172  1038  1038 D BluetoothManagerService: Stored Bluetooth name: G3
08-16 14:41:50.172  1038  1038 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-16 14:41:50.172  1038  1120 D BluetoothManagerService: Message: 40
08-16 14:41:50.172  1038  1120 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-16 14:41:50.173  7968  7984 I bluedroid-qcom: config_hci_snoop_log
08-16 14:41:50.174  1038  1120 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-16 14:41:50.175  1038  1120 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-16 14:41:50.175  8001  8001 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-16 14:41:50.182  8001  8001 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-16 14:41:50.182  8001  8001 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
,08-16 14:41:50.188  7968  7998 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-16 14:41:50.188  7968  8002 D BluetoothAdapterProperties: Name is: G3
08-16 14:41:50.188  7968  7998 D BluetoothAdapterProperties: Setting state to 11
08-16 14:41:50.189  7968  7998 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-16 14:41:50.189  1038  1120 D BluetoothManagerService: Message: 60
08-16 14:41:50.189  1038  1120 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-16 14:41:50.190  1038  1120 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-16 14:41:50.191  7968  7998 I LGBluetoothServiceJni: classInitNative: succeeds
08-16 14:41:50.198  1927  1927 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-16 14:41:50.201  1589  1589 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-16 14:41:50.202  6608  6608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:41:50.203  6608  6608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:41:50.211  6879  6879 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
,08-16 14:41:50.217  7968  7968 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-16 14:41:50.217  7968  7968 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 14:41:50.217  7968  7968 V BluetoothPbapReceiver: ***********state = 11
08-16 14:41:50.222  2178  2178 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-16 14:41:50.227  7968  7998 D BluetoothBondStateMachine: make
,08-16 14:41:50.237  7968  7998 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d90eb71
08-16 14:41:50.237  7968  7998 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-16 14:41:50.237  7968  7998 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d90eb71
08-16 14:41:50.238  7968  7998 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-16 14:41:50.239  7968  7998 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
,08-16 14:41:50.246  7968  8003 I BluetoothBondStateMachine: StableState(): Entering Off State
08-16 14:41:50.253  7968  7998 E BluetoothAdapterService: File transfer profiles supported!!
08-16 14:41:50.269  7968  7968 D HeadsetService: Received start request. Starting profile...
08-16 14:41:50.270  7968  7968 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-16 14:41:50.270  7968  7968 D LGBluetoothHfpAdapter: Version 1.6
08-16 14:41:50.271  7968  7998 E BluetoothAdapterService: File transfer profiles supported!!
,08-16 14:41:50.274  7968  7968 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,08-16 14:41:50.275  6879  6879 D BluetoothPermissionRequest: onReceive
08-16 14:41:50.275  7968  7968 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-16 14:41:50.276  7968  7968 D HeadsetStateMachine: make
08-16 14:41:50.283  6879  6879 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-16 14:41:50.287  7968  7998 E BluetoothAdapterService: File transfer profiles supported!!
08-16 14:41:50.292  7968  7998 E BluetoothAdapterService: File transfer profiles supported!!
08-16 14:41:50.297  7968  7998 E BluetoothAdapterService: File transfer profiles supported!!
,08-16 14:41:50.303  7968  7998 E BluetoothAdapterService: File transfer profiles supported!!
08-16 14:41:50.308  7968  7998 E BluetoothAdapterService: File transfer profiles supported!!
08-16 14:41:50.317  7968  7968 D LgDataFeature: LgDataFeature() Constructor: none
08-16 14:41:50.317  7968  7968 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 14:41:50.322  7968  7968 D HeadsetStateMachine: max_hf_connections = 1
08-16 14:41:50.323  7968  7968 I bluedroid-qcom: get_profile_interface handsfree
08-16 14:41:50.324  7968  7998 V LGMDMManager: Create singleton instance
08-16 14:41:50.325  7968  7968 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-16 14:41:50.325   325  1384 V AudioPolicyService: registerClient() client 0xb558a3a0, uid 1002
08-16 14:41:50.325   325   325 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-16 14:41:50.325   325   325 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-16 14:41:50.325   325   325 V AudioPolicyManagerEx: getOutput() returns output 2
08-16 14:41:50.326  7968  7998 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-16 14:41:50.326  7968  7968 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-16 14:41:50.326   325  1385 V AudioFlinger: registerClient() client 0xb101dac0, pid 7968
08-16 14:41:50.327   325  1378 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 14:41:50.327   325  1378 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 14:41:50.327  7968  7968 V ToneGenerator: Create Track: 0xb4928a80
08-16 14:41:50.327  7968  7968 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-16 14:41:50.327  7968  7968 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-16 14:41:50.327  1839  1855 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 14:41:50.327  1589  1609 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 14:41:50.327  1839  1855 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 14:41:50.327  1589  1609 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 14:41:50.327   325  1379 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 14:41:50.327   325  1379 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-16 14:41:50.327   325  2115 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-16 14:41:50.327   325  2115 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-16 14:41:50.327   325  2115 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-16 14:41:50.327   325  2115 V AudioPolicyManagerEx: getOutput() returns output 2
08-16 14:41:50.327  7968  7968 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-16 14:41:50.327  7968  7984 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 14:41:50.327  1038  1562 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 14:41:50.327  1038  1562 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 14:41:50.327  7968  7984 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-16 14:41:50.328   325  2115 I AudioFlinger: isAudioPlaybackHookOn() false
08-16 14:41:50.329  3346  3363 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 14:41:50.329  3346  3363 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 14:41:50.329  3346  3363 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 14:41:50.329  3346  3363 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-16 14:41:50.329  7968  7984 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 14:41:50.329  1038  1944 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 14:41:50.329  7968  7984 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-16 14:41:50.329  1038  1944 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-16 14:41:50.329  1589  1613 V AudioSystem: ioCon,figChanged() event 0, ioHandle 4
08-16 14:41:50.329  1589  1613 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-16 14:41:50.329  1839  3933 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 14:41:50.329  1839  3933 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-16 14:41:50.329   325  2114 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-16 14:41:50.329   325  2114 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-16 14:41:50.329   325  2114 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-16 14:41:50.329   325  2114 V AudioPolicyManagerEx: getOutput() returns output 2
08-16 14:41:50.330  7968  7968 V AudioSystem: getLatency() output 2, latency 50
08-16 14:41:50.330  7968  7968 V AudioSystem: getFrameCount() output 2, frameCount 960
08-16 14:41:50.330  7968  7968 V AudioTrack: createTrack_l() output 2 afLatency 50
08-16 14:41:50.330   325  1384 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-16 14:41:50.330   325  1384 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-16 14:41:50.330   325  1384 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-16 14:41:50.330   325  1384 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-16 14:41:50.330   325  1384 V AudioFlinger: createTrack() lSessionId: 21
08-16 14:41:50.331  7968  7968 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-16 14:41:50.331   325  1384 V AudioFlinger: acquiring 21 from 7968, for 7968
08-16 14:41:50.331   325  1384 V AudioFlinger:  added new entry for 21
,08-16 14:41:50.336  7968  7968 V ToneGenerator: ToneGenerator INIT OK, time: 187516
08-16 14:41:50.336  7968  7968 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d90eb71
08-16 14:41:50.337  7968  8019 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-16 14:41:50.337  7968  8019 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-16 14:41:50.337  7968  8019 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-16 14:41:50.337  7968  8019 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-16 14:41:50.338   325  1385 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7968
08-16 14:41:50.338   325  1385 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-16 14:41:50.338   325  1385 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-16 14:41:50.338   325  1385 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-16 14:41:50.338   325  1385 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-16 14:41:50.338   325  1385 V voice   : voice_set_parameters: exit with code(0)
08-16 14:41:50.338   325  1385 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-16 14:41:50.338   325  1385 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-16 14:41:50.338   325  1385 V msm8974_platform: platform_set_parameters: exit with code(0)
08-16 14:41:50.338   325  1385 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-16 14:41:50.338   325  1385 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-16 14:41:50.338   325  1385 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-16 14:41:50.338  7968  8019 V ToneGenerator: ToneGenerator destructor
08-16 14:41:50.338  7968  8019 V ToneGenerator: stopTone
08-16 14:41:50.339  7968  8019 V ToneGenerator: Delete Track: 0xb4928a80
08-16 14:41:50.339  7968  7968 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d90eb71
08-16 14:41:50.340  7968  8019 V AudioTrack: ~AudioTrack, releasing session id from 7968 on behalf of 7968
08-16 14:41:50.340   325   325 V AudioFlinger: releasing 21 from 7968 for 7968
08-16 14:41:50.340   325   325 V AudioFlinger:  decremented refcount to 0
08-16 14:41:50.340   325   325 V AudioFlinger: purging stale effects
08-16 14:41:50.340   325  2115 V AudioPolicyService: AudioCommandThread() adding release output 2
08-16 14:41:50.340   325  2115 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-16 14:41:50.340   325  1271 V AudioPolicyService: AudioCommandThread() waking up
08-16 14:41:50.340   325  1271 V AudioPolicyService: AudioCommandThread() processing release output 2
08-16 14:41:50.340   325  1271 V AudioPolicyManager: releaseOutput() 2
08-16 14:41:50.340   325  1271 V AudioPolicyService: AudioCommandThread() going to sleep
08-16 14:41:50.340   325  2115 V AudioFlinger: PlaybackThread::Track destructor
08-16 14:41:50.340   325  2115 V AudioFlinger: removeClient_l() pid 7968, calling pid 325
08-16 14:41:50.341  7968  7968 D A2dpService: Received start request. Starting profile...
08-16 14:41:50.342  7968  7968 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-16 14:41:50.343  7968  7968 V Avrcp   : make
08-16 14:41:50.344  7968  7968 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-16 14:41:50.344  7968  7968 I bluedroid-qcom: get_profile_interface avrcp
08-16 14:41:50.353  7968  7968 V AudioManager: registerRemoteController: size of Media player list: 0
08-16 14:41:50.355  7968  7968 E AudioManager: No RCC entry present to update
08-16 14:41:50.355  7968  7968 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-16 14:41:50.359  7968  7968 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
,08-16 14:41:50.360  7968  7968 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-16 14:41:50.360  7968  7968 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-16 14:41:50.365  7968  7968 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-16 14:41:50.520  1038  1909 V SIM_STK : Menu title from STK is T-Mobile
08-16 14:41:50.520  1038  1909 V SIM_STK : Menu title from STK is T-Mobile
,08-16 14:41:50.648  1038  1981 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-16 14:41:50.672  7968  7968 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
,08-16 14:41:50.677  7968  7968 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
,08-16 14:41:50.678  7968  7968 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-16 14:41:50.678  7968  7968 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-16 14:41:50.678  7968  7968 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-16 14:41:50.678  7968  7968 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-16 14:41:50.679  7968  7968 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-16 14:41:50.679  7968  7968 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-16 14:41:50.679  7968  7968 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-16 14:41:50.679  7968  7968 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-16 14:41:50.679  7968  7968 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-16 14:41:50.680  7968  7968 I BluetoothA2dpServiceJni: classInitNative
08-16 14:41:50.680  7968  7968 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-16 14:41:50.681  7968  7968 D A2dpStateMachine: make
08-16 14:41:50.684  7968  7968 I bluedroid-qcom: get_profile_interface a2dp
08-16 14:41:50.684  7968  8032 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-16 14:41:50.687  7968  7968 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-16 14:41:50.688  7968  7968 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-16 14:41:50.689  7968  7968 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d90eb71
08-16 14:41:50.691  7968  8031 D A2dpStateMachine: Enter Disconnected: -2
,08-16 14:41:50.696  7968  7968 I BluetoothHidServiceJni: classInitNative: succeeds
08-16 14:41:50.698  7968  7968 D HidService: Received start request. Starting profile...
08-16 14:41:50.699  7968  7968 I bluedroid-qcom: get_profile_interface hidhost
08-16 14:41:50.699  7968  7968 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d90eb71
08-16 14:41:50.700  7968  7968 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-16 14:41:50.702  7968  7968 D HealthService: Received start request. Starting profile...
,08-16 14:41:50.706  7968  7968 I bluedroid-qcom: get_profile_interface health
08-16 14:41:50.706  7968  7968 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-16 14:41:50.706  7968  7968 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d90eb71
08-16 14:41:50.707  7968  7968 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-16 14:41:50.710  7968  7968 D PanService: Received start request. Starting profile...
08-16 14:41:50.710  7968  7968 D BluetoothPanServiceJni: initializeNative(L110): pan
08-16 14:41:50.710  7968  7968 I bluedroid-qcom: get_profile_interface pan
08-16 14:41:50.717  7968  7968 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-16 14:41:50.717  7968  7968 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d90eb71
08-16 14:41:50.718  7968  7968 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
,08-16 14:41:50.725  7968  7968 D BtGatt.DebugUtils: handleDebugAction() action=null
08-16 14:41:50.726  7968  7968 D BtGatt.GattService: Received start request. Starting profile...
08-16 14:41:50.726  7968  7968 D BtGatt.GattService: start()
08-16 14:41:50.726  7968  7968 I bluedroid-qcom: get_profile_interface gatt
08-16 14:41:50.726  7968  7968 D BtGatt.AdvertiseManager: advertise manager created
08-16 14:41:50.733  7968  7968 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d90eb71
,08-16 14:41:50.736  7968  7968 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d90eb71
08-16 14:41:50.737  7968  7968 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-16 14:41:50.738  7968  7968 V BluetoothMapService: BluetoothMapBinder()
08-16 14:41:50.739  7968  7968 D BluetoothMapService: Received start request. Starting profile...
08-16 14:41:50.739  7968  7968 D BluetoothMapService: start()
08-16 14:41:50.742  7968  7968 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-16 14:41:50.743  7968  7968 D BluetoothMapEmailAppObserver: createReceiver()
08-16 14:41:50.744  7968  7968 D BluetoothMapEmailAppObserver: initObservers()
08-16 14:41:50.744  7968  7968 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
,08-16 14:41:50.754  7968  7968 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d90eb71
08-16 14:41:50.755  7968  7968 D HeadsetStateMachine: Proxy object connected
,08-16 14:41:50.755  7968  7968 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
,08-16 14:41:50.756  7968  7968 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-16 14:41:50.757  7968  8019 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-16 14:41:50.758  7968  8019 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-16 14:41:50.758  7968  8019 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-16 14:41:50.763  7968  7968 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-16 14:41:50.767  7968  7968 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-16 14:41:50.769  7968  7968 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-16 14:41:50.775  7968  7968 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-16 14:41:50.778  7968  7968 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-16 14:41:50.779  7968  7968 V PanService: [BTUI] SIM Extra State :ABSENT
08-16 14:41:50.784  7968  7968 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-16 14:41:50.788  7968  7968 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-16 14:41:50.788  7968  7968 V BluetoothMapService: Handler(): got msg=1
08-16 14:41:50.789  7968  7968 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-16 14:41:50.789  7968  7968 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-16 14:41:50.789  7968  7968 V BluetoothSapReceiver: SapReceiver onReceive 
08-16 14:41:50.789  7968  7968 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 14:41:50.789  7968  7998 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-16 14:41:50.789  7968  7968 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-16 14:41:50.790  7968  7998 I bluedroid-qcom: enable
08-16 14:41:50.790  7968  7998 I bt_hci_bdroid: init
08-16 14:41:50.794  7968  7998 I bt_vendor: bt-vendor : init
08-16 14:41:50.794  7968  7998 I bt_vendor: bt-vendor : get_bt_soc_type
08-16 14:41:50.795  7968  7998 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-16 14:41:50.795  7968  7998 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-16 14:41:50.795  7968  7998 D bt_userial_mct: userial_init
08-16 14:41:50.795  7968  8039 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-16 14:41:50.796  7968  8039 I bt-btu  : btu_task pending for preload complete event
08-16 14:41:50.796  7968  7998 D bt_hci_bdroid: set_power 1
08-16 14:41:50.796  7968  7998 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-16 14:41:50.796  7968  7998 I bt_vendor: Starting hciattach daemon
08-16 14:41:50.796  7968  7998 I bt_vendor: try to set true
,08-16 14:41:50.799  8042  8042 W sh      : type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-16 14:41:50.799  8042  8042 W sh      : type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 14:41:50.837  8043  8043 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-16 14:41:50.913  8049  8049 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-16 14:41:50.927  8050  8050 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-16 14:41:50.969  8052  8052 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-16 14:41:50.983  8053  8053 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-16 14:41:51.002  8054  8054 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-16 14:41:51.019  8055  8055 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-16 14:41:51.040  8057  8057 I libmdmdetect: ESOC framework not supported
,08-16 14:41:51.041  8057  8057 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-16 14:41:51.051  8057  8057 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
,08-16 14:41:51.051  8057  8057 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
,08-16 14:41:51.051  8057  8057 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
,08-16 14:41:51.051  8057  8057 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-16 14:41:51.051  8057  8057 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-16 14:41:51.051  8057  8057 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
,08-16 14:41:51.051  8057  8057 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-16 14:41:51.089  8057  8058 E QC-QMI  : qmi_client [8057] 15: failed to locate client data
,08-16 14:41:51.090   485   485 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-16 14:41:51.090   485   485 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
,08-16 14:41:51.144  8059  8059 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-16 14:41:51.162  8060  8060 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-16 14:41:51.198  7968  7998 I bt_vendor: bluetooth satus is on
08-16 14:41:51.199  7968  7998 D bt_hci_bdroid: preload
08-16 14:41:51.199  7968  8041 D bt_userial_mct: userial_open(port:0)
08-16 14:41:51.199  7968  8041 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-16 14:41:51.202  7968  8041 I bt_vendor: Done intiailizing UART
,08-16 14:41:51.204  7968  8041 I bt_vendor: Done intiailizing UART
08-16 14:41:51.204  7968  8041 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
,08-16 14:41:51.204  7968  8041 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-16 14:41:51.204  7968  8039 I bt-btu  : btu_task received preload complete event
08-16 14:41:51.205  7968  8039 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-16 14:41:51.205  7968  8039 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-16 14:41:51.207  7968  8039 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-16 14:41:51.204  7968  8062 D bt_userial_mct: Entering userial_read_thread()
08-16 14:41:51.370  1038  1890 I art     : Explicit concurrent mark sweep GC freed 27503(1359KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/64MB, paused 2.964ms total 155.537ms
,08-16 14:41:51.379  7968  8039 I         : BTE_InitTraceLevels -- TRC_HCI
08-16 14:41:51.379  7968  8039 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-16 14:41:51.379  7968  8039 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-16 14:41:51.379  7968  8039 I         : BTE_InitTraceLevels -- TRC_AVDT
08-16 14:41:51.379  7968  8039 I         : BTE_InitTraceLevels -- TRC_AVRC
08-16 14:41:51.379  7968  8039 I         : BTE_InitTraceLevels -- TRC_A2D
08-16 14:41:51.379  7968  8039 I         : BTE_InitTraceLevels -- TRC_BNEP
08-16 14:41:51.379  7968  8039 I         : BTE_InitTraceLevels -- TRC_BTM
08-16 14:41:51.379  7968  8039 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-16 14:41:51.379  7968  8039 I         : BTE_InitTraceLevels -- TRC_GAP
08-16 14:41:51.379  7968  8039 I         : BTE_InitTraceLevels -- TRC_PAN
08-16 14:41:51.379  7968  8039 I         : BTE_InitTraceLevels -- TRC_SDP
08-16 14:41:51.379  7968  8039 I         : BTE_InitTraceLevels -- TRC_GATT
08-16 14:41:51.379  7968  8039 I         : BTE_InitTraceLevels -- TRC_SMP
08-16 14:41:51.380  7968  8039 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-16 14:41:51.380  7968  8039 I         : BTE_InitTraceLevels -- TRC_BTIF
08-16 14:41:51.427  7968  8039 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-16 14:41:51.427  7968  8039 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa0203061 
08-16 14:41:51.427  7968  8039 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0203061 
,08-16 14:41:51.444  7968  8002 E bt-btif : Calling BTA_HhEnable
08-16 14:41:51.444  7968  8002 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
,08-16 14:41:51.444  7968  8002 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-16 14:41:51.445  1038  1038 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-16 14:41:51.446  1038  1038 D BluetoothManagerService: Stored Bluetooth name: G3
08-16 14:41:51.446  7968  8002 D BluetoothAdapterProperties: Name is: G3
08-16 14:41:51.447  7968  8002 D BluetoothAdapterProperties: Scan Mode:20
08-16 14:41:51.448  7968  8002 D BluetoothAdapterProperties: Discoverable Timeout:120
08-16 14:41:51.448  7968  8002 D bt_hci_bdroid: postload
08-16 14:41:51.449  7968  8041 D bt_hci_bdroid: Used up Tx Cmd credits
08-16 14:41:51.449  7968  8039 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-16 14:41:51.449  7968  8039 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-16 14:41:51.449  7968  8039 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-16 14:41:51.450  7968  8039 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-16 14:41:51.450  7968  8039 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-16 14:41:51.450  7968  8039 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-16 14:41:51.450  7968  8002 D bte_conf: Device ID record 1 : primary
08-16 14:41:51.450  7968  8002 D bte_conf:   vendorId            = 00c4
08-16 14:41:51.450  7968  8002 D bte_conf:   vendorIdSource      = 0001
08-16 14:41:51.450  7968  8002 D bte_conf:   product             = 13a1
08-16 14:41:51.450  7968  8002 D bte_conf:   version             = 1000
08-16 14:41:51.450  7968  8002 D bte_conf:   clientExecutableURL = 
08-16 14:41:51.450  7968  8002 D bte_conf:   serviceDescription  = 
08-16 14:41:51.450  7968  8002 D bte_conf:   documentationURL    = 
08-16 14:41:51.450  7968  8002 D bte_conf: bte_load_did_conf no section named DID2.
08-16 14:41:51.453  7968  8041 D bt_hci_bdroid: Used up Tx Cmd credits
08-16 14:41:51.453  7968  8041 D bt_hci_bdroid: Used up Tx Cmd credits
08-16 14:41:51.454  7968  8041 D bt_hci_bdroid: Used up Tx Cmd credits
08-16 14:41:51.455  7968  8002 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-16 14:41:51.449  8065  8065 W sh      : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 14:41:51.449  8065  8065 W sh      : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 14:41:51.455  7968  7998 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
,08-16 14:41:51.456  7968  7998 D BluetoothAdapterProperties: ScanMode =  20
08-16 14:41:51.456  7968  7998 D BluetoothAdapterProperties: State =  11
08-16 14:41:51.456  7968  7998 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-16 14:41:51.457  7968  7998 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-16 14:41:51.457  7968  7998 D BluetoothAdapterProperties: Setting state to 12
,08-16 14:41:51.457  7968  7998 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-16 14:41:51.459  7968  8002 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-16 14:41:51.461  7968  8062 E bt_mct  : hci lib postload completed
,08-16 14:41:51.477  7968  8039 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-16 14:41:51.477  7968  8039 W bt-smp  : Plain text(LSB ~ MSB) = 3b 32 68 00 00 00 00 00 00 00 00 00 00 00 00 00 
,08-16 14:41:51.477  7968  8039 W bt-smp  : Encrypted text(LSB ~ MSB) = de 29 fb 0e d7 ce cd 77 cb 9d 2c 30 ca b7 89 25 
08-16 14:41:51.478  7968  8039 W bt-btm  : Stopping oneshot timer
,08-16 14:41:51.482  7968  8002 D BluetoothAdapterProperties: Discoverable Timeout:120
08-16 14:41:51.482  7968  8002 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-16 14:41:51.485  6608  6608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 14:41:51.485  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:41:51.485  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 14:41:51.485  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 14:41:51.485  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 14:41:51.485  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 14:41:51.485  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 14:41:51.485  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 14:41:51.487  6608  6608 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 14:41:51.487  1038  1120 D BluetoothManagerService: Message: 60
08-16 14:41:51.487  1038  1120 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-16 14:41:51.487  1038  1120 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
08-16 14:41:51.488  7968  7998 I BluetoothAdapterState: Entering On State
08-16 14:41:51.488  1839  1855 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 14:41:51.494  6608  6608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 14:41:51.494  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:41:51.494  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 14:41:51.494  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 14:41:51.494  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 14:41:51.494  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 14:41:51.494  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 14:41:51.494  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 14:41:51.497  7968  8039 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-16 14:41:51.497  7968  8039 W bt-smp  : Plain text(LSB ~ MSB) = dc 99 66 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-16 14:41:51.497  7968  8039 W bt-smp  : Encrypted text(LSB ~ MSB) = 2f 4c e7 69 db a0 45 49 b9 32 b8 02 a4 0b ef 72 
08-16 14:41:51.497  7968  8039 W bt-btm  : Stopping oneshot timer
08-16 14:41:51.501  6608  6608 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 14:41:51.504  7968  7998 D LGBluetoothServiceAdapter: [BTUI] OnState
08-16 14:41:51.504  7968  7998 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-16 14:41:51.505  7968  7998 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-16 14:41:51.506  7968  7998 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-16 14:41:51.507  6879  6895 D BluetoothPan: onBluetoothStateChange on: true
08-16 14:41:51.508  6879  6895 D BluetoothPan: onBluetoothStateChange call bindService
08-16 14:41:51.510  7968  8039 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-16 14:41:51.510  7968  8039 W bt-smp  : Plain text(LSB ~ MSB) = a4 f8 54 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-16 14:41:51.510  7968  8039 W bt-smp  : Encrypted text(LSB ~ MSB) = e0 e0 ac 65 9b d8 29 70 96 f5 8f e1 a0 48 53 db 
08-16 14:41:51.510  7968  8039 W bt-btm  : Stopping oneshot timer
,08-16 14:41:51.516  1839  1839 D BluetoothHeadset: Proxy object connected
08-16 14:41:51.519  6879  8063 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 14:41:51.521  6879  6879 D BluetoothPan: BluetoothPAN Proxy object connected
08-16 14:41:51.521  6879  6879 D PanProfile: Bluetooth service connected
08-16 14:41:51.525  1038  1120 D BluetoothA2dp: onBluetoothStateChange: up=true
08-16 14:41:51.525  7968  8039 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-16 14:41:51.525  7968  8039 W bt-smp  : Plain text(LSB ~ MSB) = ea 92 68 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-16 14:41:51.525  7968  8039 W bt-smp  : Encrypted text(LSB ~ MSB) = 0c 10 6b ab 5f 14 e6 47 cc fb 3e b6 87 e5 95 d1 
08-16 14:41:51.525  7968  8039 W bt-btm  : Stopping oneshot timer
,08-16 14:41:51.529  1038  1038 D BluetoothA2dp: Proxy object connected
08-16 14:41:51.531  1839  3938 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 14:41:51.532  8070  8070 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-16 14:41:51.533  1839  1839 D BluetoothHeadset: Proxy object connected
,08-16 14:41:51.533  6879  6879 D BluetoothHeadset: Proxy object connected
08-16 14:41:51.533  6879  6879 D HeadsetProfile: Bluetooth service connected
08-16 14:41:51.534  6879  6895 D BluetoothA2dp: onBluetoothStateChange: up=true
08-16 14:41:51.536  7968  8039 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-16 14:41:51.536  7968  8039 W bt-smp  : Plain text(LSB ~ MSB) = 05 8b 7c 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-16 14:41:51.536  7968  8039 W bt-smp  : Encrypted text(LSB ~ MSB) = b9 08 ee 25 11 56 fa db be 9b d6 9c 43 1c f7 12 
08-16 14:41:51.536  7968  8039 W bt-btm  : Stopping oneshot timer
08-16 14:41:51.536  6879  6879 D BluetoothA2dp: Proxy object connected
08-16 14:41:51.536  1839  1854 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 14:41:51.536  6879  6879 D A2dpProfile: Bluetooth service connected
08-16 14:41:51.538  1839  1839 D BluetoothHeadset: Proxy object connected
08-16 14:41:51.538  1038  1120 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 14:41:51.539  7968  7998 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
,08-16 14:41:51.541  1038  1038 D BluetoothHeadset: Proxy object connected
,08-16 14:41:51.541  6879  8063 D BluetoothPbap: onBluetoothStateChange: up=true
,08-16 14:41:51.544  6879  6896 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-16 14:41:51.548  6879  8063 D BluetoothMap: onBluetoothStateChange: up=true
08-16 14:41:51.548  6879  6879 D BluetoothInputDevice: Proxy object connected
08-16 14:41:51.548  6879  6879 D HidProfile: Bluetooth service connected
08-16 14:41:51.554  1038  1038 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
,08-16 14:41:51.556  1038  1120 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-16 14:41:51.557  1038  1120 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-16 14:41:51.557  6879  6879 D BluetoothMap: Proxy object connected
08-16 14:41:51.557  6879  6879 D MapProfile: Bluetooth service connected
08-16 14:41:51.557  6879  6879 D BluetoothMap: getConnectedDevices()
08-16 14:41:51.558  7968  7984 V BluetoothMapService: getConnectedDevices()
08-16 14:41:51.561  1589  1589 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-16 14:41:51.565  1927  1927 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-16 14:41:51.565  1927  2129 D LGBluetoothAPIService: Message: 1
08-16 14:41:51.565  1927  2129 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-16 14:41:51.565  1927  2129 D LGBluetoothAPIService: Calling onBluetoothServiceUp callbacks
08-16 14:41:51.565  1927  2129 D LGBluetoothAPIService: Broadcasting onBluetoothServiceUp() to 0 receivers.
08-16 14:41:51.567  6608  6608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:41:51.568  6608  6608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:41:51.570  1038  1120 D BluetoothManagerService: Message: 40
08-16 14:41:51.570  1038  1120 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
,08-16 14:41:51.575  7968  7968 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-16 14:41:51.575  7968  7968 D BluetoothMapService: STATE_ON
08-16 14:41:51.577  6879  6879 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-16 14:41:51.579  6879  6879 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-16 14:41:51.589  6879  6879 D DockEventReceiver: finishStartingService: stopping service
08-16 14:41:51.592  7968  7968 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d90eb71
08-16 14:41:51.592  7968  7968 V BluetoothPbapService: Pbap Service onCreate
08-16 14:41:51.592  7968  7968 V BluetoothPbapService: Starting PBAP service
,08-16 14:41:51.594  7968  7968 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-16 14:41:51.594  7968  7968 V BluetoothMapService: Handler(): got msg=1
08-16 14:41:51.595  7968  7968 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-16 14:41:51.595  7968  7968 V BluetoothPbapService: Pbap Service onBind
08-16 14:41:51.596  7968  8084 D BluetoothMapMasInstance: MAS initSocket()
08-16 14:41:51.597  7968  8084 D BluetoothMapMasInstance:   masId = 00
08-16 14:41:51.597  7968  8084 D BluetoothMapMasInstance:   msgTypes = 0e
08-16 14:41:51.597  7968  8084 D BluetoothMapMasInstance:   masName = SMS/MMS
08-16 14:41:51.597  7968  8084 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-16 14:41:51.598  7968  7968 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 14:41:51.598  7968  7968 V BluetoothPbapService: state: 12
08-16 14:41:51.598  7968  7968 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-16 14:41:51.598  7968  7968 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 14:41:51.598  7968  7968 V BluetoothPbapReceiver: ***********state = 12
08-16 14:41:51.599  1038  1909 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 14:41:51.600  7968  8084 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 14:41:51.600  7968  7968 V BluetoothPbapService: Handler(): got msg=1
08-16 14:41:51.601  7968  7968 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-16 14:41:51.602  6879  6879 D BluetoothPbap: Proxy object connected
08-16 14:41:51.602  6879  6879 D PbapServerProfile: Bluetooth service connected
08-16 14:41:51.603  7968  8084 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-16 14:41:51.603  7968  8084 V BluetoothMapMasInstance: Succeed to create listening socket 
08-16 14:41:51.603  7968  8084 D BluetoothMapMasInstance: Accepting socket connection...
08-16 14:41:51.604  7968  8085 V BluetoothPbapService: Pbap Service initSocket
08-16 14:41:51.605  7968  8002 D BluetoothAdapterProperties: Scan Mode:21
08-16 14:41:51.605  1038  1890 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 14:41:51.605  7968  8002 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
,08-16 14:41:51.608  7968  8085 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 14:41:51.611  6608  6608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:41:51.612  7968  8085 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-16 14:41:51.612  7968  8085 V BluetoothPbapService: Succeed to create listening socket 
08-16 14:41:51.612  7968  8085 V BluetoothPbapService: Accepting socket connection...
08-16 14:41:51.613  6608  6608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:41:51.613  2178  2178 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-16 14:41:51.614  2178  2178 D c       : Getting all permits...
08-16 14:41:51.614  2178  2178 D a       : Opening database...
08-16 14:41:51.619  2178  2178 D a       : Opening database auth.proximity.permit_store...
,08-16 14:41:51.620  2178  2178 D a       : Closing database...
08-16 14:41:51.631  6879  6879 D BluetoothPermissionRequest: onReceive
,08-16 14:41:51.634  6879  6879 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
,08-16 14:41:51.636  6879  6879 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-16 14:41:51.639  7968  7968 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-16 14:41:51.641  7968  7968 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-16 14:41:51.650  7968  7968 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-16 14:41:51.688  7968  7968 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-16 14:41:51.689  7968  7968 V BtOppService: onCreate
,08-16 14:41:51.694  7968  7968 V BluetoothOppNotification: send message
08-16 14:41:51.698  7968  7968 V BtOppService: Starting RfcommListener
08-16 14:41:51.713  7968  7968 D BluetoothOppPreference: Dumping Names:  
08-16 14:41:51.713  7968  7968 D BluetoothOppPreference: {}
,08-16 14:41:51.713  7968  7968 D BluetoothOppPreference: Dumping Channels:  
08-16 14:41:51.713  7968  7968 D BluetoothOppPreference: {}
08-16 14:41:51.714  7968  7968 V BtOppService: onStartCommand
08-16 14:41:51.719  7968  8092 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-16 14:41:51.721  7968  7968 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-16 14:41:51.722  7968  7968 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-16 14:41:51.723  7968  8089 V BtOppService: Deleted complete outbound shares, number =  0
08-16 14:41:51.725  7968  8092 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-16 14:41:51.726  7968  8089 V BtOppService: Deleted complete inbound failed shares, number = 0
08-16 14:41:51.727  7968  8089 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-16 14:41:51.728  7968  8092 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@7a64cfd on behalf of 
,08-16 14:41:51.729  7968  8089 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@35f20df2 on behalf of 
,08-16 14:41:51.731  7968  7968 V BluetoothOppNotification: new notify threadi!
08-16 14:41:51.734  7968  7968 V BluetoothOppNotification: send delay message
08-16 14:41:51.735  7968  8092 V BluetoothOppNotification: update too frequent, put in queue
08-16 14:41:51.736  7968  7968 V BtOppService: start RfcommListener
08-16 14:41:51.737  7968  8093 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-16 14:41:51.739  7968  7968 V BtOppService: RfcommListener started
08-16 14:41:51.740  7968  8092 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-16 14:41:51.741  7968  7968 V BtOppService: ContentObserver received notification
08-16 14:41:51.741  7968  8093 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@337bdc43 on behalf of 
08-16 14:41:51.743  7968  8093 V BluetoothOppNotification: mUpdateCompleteNotification = true
,08-16 14:41:51.745  7968  7968 V BtOppService: ContentObserver received notification
08-16 14:41:51.745  7968  8094 V BtOppRfcommListener: Starting RFCOMM listener....
,08-16 14:41:51.746  7968  8093 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-16 14:41:51.746  1038  1945 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 14:41:51.748  7968  8094 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 14:41:51.751  7968  8094 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=78 mFd=75
08-16 14:41:51.751  7968  8094 V BtOppRfcommListener: Started RFCOMM listener....
08-16 14:41:51.752  7968  8094 I BtOppRfcommListener: Accept thread started.
08-16 14:41:51.752  7968  8094 V BtOppRfcommListener: Accepting connection...
08-16 14:41:51.752  7968  8095 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-16 14:41:51.753  7968  8095 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-16 14:41:51.755  7968  8093 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@7ab62c0 on behalf of 
08-16 14:41:51.755  7968  8095 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1c8fbbf9 on behalf of 
08-16 14:41:51.758  7968  8095 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-16 14:41:51.759  7968  8093 V BluetoothOppNotification: outbound: succ-0  fail-0
,08-16 14:41:51.763  7968  8093 V BluetoothOppNotification: outbound notification was removed.
08-16 14:41:51.763  7968  8093 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-16 14:41:51.767  7968  8093 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@100f173e on behalf of 
,08-16 14:41:51.768  7968  8093 V BluetoothOppNotification: inbound: succ-0  fail-0
08-16 14:41:51.771  7968  8093 V BluetoothOppNotification: inbound notification was removed.
08-16 14:41:51.771  7968  8093 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-16 14:41:51.772  7968  7968 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d90eb71
08-16 14:41:51.772  7968  7968 V BluetoothFtpService: Ftp Service onCreate
08-16 14:41:51.772  7968  7968 I BluetoothFtpService: Ftp Service onCreate
08-16 14:41:51.773  7968  7968 V BluetoothFtpService: Ftp Service onStartCommand
08-16 14:41:51.773  7968  7968 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 14:41:51.773  7968  7968 V BluetoothFtpService: Starting Listening on sockets
,08-16 14:41:51.774  7968  7968 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-16 14:41:51.774  7968  7968 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-16 14:41:51.775  7968  7968 V BluetoothSapReceiver: SapReceiver onReceive 
08-16 14:41:51.775  7968  7968 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 14:41:51.775  7968  7968 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-16 14:41:51.775  7968  7968 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-16 14:41:51.776  7968  8093 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2f43eaec on behalf of 
08-16 14:41:51.778  7968  7968 V BluetoothFtpService: Handler(): got msg=1
08-16 14:41:51.779  7968  7968 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-16 14:41:51.779  7968  7968 V BluetoothFtpService: Ftp Service initSocket
08-16 14:41:51.784  1038  1562 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-16 14:41:51.785  7968  7968 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 14:41:51.790  7968  7968 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=78
08-16 14:41:51.790  7968  7968 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-16 14:41:51.792  7968  8097 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-16 14:41:51.816  7968  7968 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d90eb71
,08-16 14:41:51.816  7968  7968 V BluetoothSapService: Sap Service onCreate
08-16 14:41:51.819  7968  7968 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 14:41:51.819  7968  7968 V BluetoothSapService: state: 12
08-16 14:41:51.819  7968  7968 V BluetoothSapService: Starting SAP server process
08-16 14:41:51.821  7968  7968 V BluetoothSapService: SAP Service startRfcommListenerThread
,08-16 14:41:51.819  8098  8098 W sapd    : type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 14:41:51.823  7968  8099 V BluetoothSapService: Sap Service initRfcommSocket
08-16 14:41:51.824  1038  2037 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 14:41:51.819  8098  8098 W sapd    : type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 14:41:51.825  7968  8099 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 14:41:51.827  7968  8099 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-16 14:41:51.827  7968  8099 V BluetoothSapService: Succeed to create listening socket 
08-16 14:41:51.827  7968  8099 V BluetoothSapService: Accepting socket connection...
08-16 14:41:51.848  8098  8098 V BT_SAP  : Event pipe created
08-16 14:41:51.848  8098  8098 V BT_SAP  : create_server_socket qcom.sap.server
08-16 14:41:51.848  8098  8098 V BT_SAP  : created socket fd 6
,08-16 14:41:52.737  7968  7968 V BluetoothOppNotification: new notify threadi!
,08-16 14:41:52.737  7968  7968 V BluetoothOppNotification: send delay message
,08-16 14:41:52.751  7968  8109 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-16 14:41:52.753  7968  8109 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@14fac9d8 on behalf of 
08-16 14:41:52.755  7968  8109 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-16 14:41:52.757  7968  8109 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,08-16 14:41:52.760  7968  8109 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@d57f131 on behalf of 
,08-16 14:41:52.761  7968  8109 V BluetoothOppNotification: outbound: succ-0  fail-0
08-16 14:41:52.762  7968  8109 V BluetoothOppNotification: outbound notification was removed.
08-16 14:41:52.763  7968  8109 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-16 14:41:52.764  7968  8109 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@36d4d016 on behalf of 
08-16 14:41:52.764  7968  8109 V BluetoothOppNotification: inbound: succ-0  fail-0
08-16 14:41:52.767  7968  8109 V BluetoothOppNotification: inbound notification was removed.
08-16 14:41:52.767  7968  8109 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-16 14:41:52.768  7968  8109 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@37077d97 on behalf of 
08-16 14:41:53.863  1038  1365 V AlarmManager: ELAPSED_WAKEUP set : Alarm{338fea27 type 2 when 191017 com.google.android.gms} when 191017
,08-16 14:41:53.872  7872  7872 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
08-16 14:41:53.872  7872  7872 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:9042
08-16 14:41:53.877   321  8111 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,08-16 14:41:53.882  1038  1118 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,08-16 14:41:55.138  6608  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 14:41:55.138  6608  6679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:41:55.138  6608  6679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 14:41:55.138  6608  6679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 14:41:55.138  6608  6679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 14:41:55.138  6608  6679 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 14:41:55.138  6608  6679 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 14:41:55.138  6608  6679 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 14:41:55.146  6608  6679 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 14:41:55.147  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 14:41:55.147  6608  6679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1afe97b2 removed from the list
,08-16 14:41:55.147  6608  6679 D io.jxcore.node.ConnectivityMonitor: stop
,08-16 14:41:55.147  6608  6679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:41:55.147  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:41:55.148  6608  6679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 14:41:55.148  6608  6679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@164b0303 added. We now have 4 listener(s)
08-16 14:41:55.148  6608  6679 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 14:41:55.150  1038  1562 D WifiServiceImplEx: setWifiEnabled: false pid=6608, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-16 14:41:55.150  1038  1562 D WifiService: setWifiEnabled: false pid=6608, uid=10118
08-16 14:41:55.151  1038  1562 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-16 14:42:00.059  1589  1589 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged(),
08-16 14:42:00.060  1589  1589 I KeyguardUpdateMonitor: called onTimeUpdated()
,08-16 14:42:00.060  1589  1589 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
,08-16 14:42:00.074  1589  1589 I [SystemUI]Clock: called onTimeUpdated()
,08-16 14:42:00.076  1589  1589 I LgeClockWidgetControlView: called onTimeUpdated()
,08-16 14:42:00.076  1589  1589 I [SystemUI]DateView: called onTimeUpdated()
,08-16 14:42:00.077  1589  1589 I [SystemUI]DateView: called onTimeUpdated()
,08-16 14:42:00.078  1589  1589 D KeyguardUpdateMonitor: handleTimeUpdate
08-16 14:42:00.159  6608  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 14:42:00.174  1038  1944 D WifiServiceImplEx: setWifiEnabled: true pid=6608, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,08-16 14:42:00.174  1038  1944 D WifiService: setWifiEnabled: true pid=6608, uid=10118
08-16 14:42:00.174  1038  1944 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-16 14:42:00.194  1038  1038 D LocationManagerService: getAllProviders()=[passive, gps, network]
,08-16 14:42:00.195  1038  1038 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-16 14:42:00.195  1038  1038 D Ulp_jni : JNI:system_update. Event-4
08-16 14:42:00.196  1038  1381 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-16 14:42:00.196  1038  1381 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-16 14:42:00.199  1038  1381 E WifiUtil: wfc_util_ffile_check_copy(): pid[1038] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-16 14:42:00.199  1038  1381 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-16 14:42:00.199  1038  1381 E WifiUtil: wfc_util_ffile_check_copy(): pid[1038] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-16 14:42:00.199  1038  1381 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-16 14:42:00.199  1038  1381 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-16 14:42:00.199  1038  1381 E WifiHW  : unknown target_country: EU , set to default
08-16 14:42:00.199  1038  1381 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-16 14:42:00.199  1038  1381 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-16 14:42:00.200  1038  1381 I WifiUtil: gEnableBmps=1
08-16 14:42:00.772   321   895 D SoftapController: Softap fwReload - Ok
,08-16 14:42:00.781  1038  1381 E NetdConnector: NDC Command {83 softap fwreload wlan0 STA} took too long (578ms)
08-16 14:42:00.791   321   895 D CommandListener: Setting iface cfg
08-16 14:42:00.791   321   895 D CommandListener: Trying to bring down wlan0
,08-16 14:42:00.796  1038  1120 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-16 14:42:00.814   321   895 D CommandListener: Clearing all IP addresses on wlan0
08-16 14:42:00.818  1038  1381 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
08-16 14:42:00.819  8122  8122 W wpa_supplicant: type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-16 14:42:00.829  8122  8122 W wpa_supplicant: type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 14:42:00.889  6879  6879 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-16 14:42:00.889  6879  6879 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-16 14:42:00.890  6879  6879 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-16 14:42:00.890  6879  6879 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-16 14:42:00.893  1038  1381 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-16 14:42:00.893  1038  1381 E WifiStateMachine: useWiFiOffloading() : false
08-16 14:42:00.893  1038  1381 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-16 14:42:00.897  1038  1381 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-16 14:42:00.898  6879  6879 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-16 14:42:00.900  8122  8122 I wpa_supplicant: Successfully initialized wpa_supplicant
08-16 14:42:00.901  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 14:42:00.901  1038  1381 D WifiMonitor: connecting to supplicant
08-16 14:42:00.902  1927  1927 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-16 14:42:00.904  6608  6608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:42:00.905  1038  1038 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-16 14:42:00.907  6608  6608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:42:00.909  6879  6879 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-16 14:42:00.910  6879  6879 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-16 14:42:00.910  6879  6879 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-16 14:42:00.910  6879  6879 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-16 14:42:00.910  6879  6879 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-16 14:42:00.910  6879  6879 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-16 14:42:00.910  6879  6879 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-16 14:42:00.939  8122  8122 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-16 14:42:00.940  8122  8122 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,08-16 14:42:00.943  1038  1120 D Tethering: InitialState.processMessage what=4
08-16 14:42:00.955  1038  1054 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=8140 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
08-16 14:42:00.957  1038  1120 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-16 14:42:01.031  8122  8122 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-16 14:42:01.086  8122  8122 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
08-16 14:42:01.088  1038  1054 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=8163 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-16 14:42:01.100  8140  8161 W FormManager: Network not available. Please check & try again.
08-16 14:42:01.102  8122  8122 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
,08-16 14:42:01.104  1038  1381 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-16 14:42:01.104  1038  1381 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-16 14:42:01.104  1038  8172 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-16 14:42:01.104  1038  8172 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-16 14:42:01.104  1038  8172 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-16 14:42:01.104  1038  8172 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-16 14:42:01.105  1038  1381 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-16 14:42:01.106  1038  1381 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-16 14:42:01.106  1038  1381 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-16 14:42:01.107  1038  1381 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-16 14:42:01.107  1038  1381 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-16 14:42:01.107  1038  1381 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-16 14:42:01.108  1038  1381 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-16 14:42:01.108  1038  1381 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-16 14:42:01.109  1038  1381 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-16 14:42:01.109  1038  1381 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-16 14:42:01.109  1038  1381 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-16 14:42:01.109  1038  1381 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-16 14:42:01.109  1038  1381 E WifiStateMachine: useWiFiOffloading() : false
08-16 14:42:01.109  1038  1381 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-16 14:42:01.110  1038  1038 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:42:01.110  1038  1038 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:42:01.110  1038  1381 D WifiNative-wlan0: doBoolean: SET update_config 1
08-16 14:42:01.110  1038  1038 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:42:01.110  1038  1038 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:42:01.110  1038  1038 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-16 14:42:01.111  1038  1381 D WifiNative-wlan0: SET update_config 1: returned true
08-16 14:42:01.111  1038  1381 D WifiConfigStore: Loading config and enabling all networks 
08-16 14:42:01.111  1038  1381 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-16 14:42:01.111  1927  1927 D WfdService: Waiting for WifiP2p enabling
08-16 14:42:01.111  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 14:42:01.112  1038  1381 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-16 14:42:01.113  1038  1038 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-16 14:42:01.115  1038  1428 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
,08-16 14:42:01.119  6608  6608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 14:42:01.119  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:42:01.119  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 14:42:01.119  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 14:42:01.119  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 14:42:01.119  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 14:42:01.119  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 14:42:01.119  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 14:42:01.122  6608  6608 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 14:42:01.125  6608  6608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 14:42:01.125  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:42:01.125  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 14:42:01.125  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 14:42:01.125  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 14:42:01.125  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 14:42:01.125  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 14:42:01.125  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 14:42:01.126  1038  1381 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-16 14:42:01.127  6608  6608 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 14:42:01.130  8140  8162 V FormManager: Network unavailable.
,08-16 14:42:01.135  1038  1381 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-16 14:42:01.135  1038  1381 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-16 14:42:01.136  1038  1381 D WifiStateMachine: enableVerboseLogging : level 2
08-16 14:42:01.136  1038  1381 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-16 14:42:01.136  1038  1381 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-16 14:42:01.136  1038  1381 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-16 14:42:01.137  1038  1381 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-16 14:42:01.137  1038  1381 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-16 14:42:01.137  1038  1381 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-16 14:42:01.137  1038  1381 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-16 14:42:01.137  1038  1381 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-16 14:42:01.137  1038  1381 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-16 14:42:01.137  8140  8162 V FormManager: Network unavailable.
08-16 14:42:01.138  1038  1381 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-16 14:42:01.138  1038  1381 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-16 14:42:01.138  1038  1381 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-16 14:42:01.138  1038  1381 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-16 14:42:01.138  1038  1381 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-16 14:42:01.142  1038  1381 D WifiStateMachine: Setting OUI to DA-A1-19
08-16 14:42:01.142  1038  1381 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
,08-16 14:42:01.143  1038  1381 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-16 14:42:01.143  1038  1381 D WifiNative-HAL: Setting external_sim to 1
,08-16 14:42:01.143  1038  1381 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-16 14:42:01.143  1927  1927 D WfdsService: Supplicant Connection state is changed : true
08-16 14:42:01.143  1038  1381 D WifiNative-wlan0: SET external_sim 1: returned true
08-16 14:42:01.143  1927  2284 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-16 14:42:01.143  1038  1381 I WifiNative-HAL: startHal
08-16 14:42:01.143  1927  2284 D WfdsService: Set the WFDS Monitor: true
08-16 14:42:01.143  1927  2284 D WfdsMonitor: WfdsMonitorThread create
08-16 14:42:01.143  1038  1381 D wifi    : setting scan oui 0xaf549bc0
08-16 14:42:01.144  7714  7714 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:42:01.144  1927  2284 D WfdsMonitor: WFDS Monitor is created and started
08-16 14:42:01.144  1927  2284 D WfdsService: WiFi: Supplicant connection re-established
08-16 14:42:01.144  1038  1381 D WifiStateMachine: Setting OUI to DA-A1-19
08-16 14:42:01.144  1038  1381 I WifiNative-HAL: startHal
08-16 14:42:01.144  1038  1381 D wifi    : setting scan oui 0xaf549bc0
08-16 14:42:01.144  1038  1381 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-16 14:42:01.145  1927  8182 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-16 14:42:01.145  1038  1381 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-16 14:42:01.145  1038  1381 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-16 14:42:01.146  8122  8122 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-16 14:42:01.146  1927  8182 E CtrlSupplicant: Succeed to open control connection
08-16 14:42:01.146  1927  8182 E CtrlSupplicant: Succeed to open monitor connection
08-16 14:42:01.146  1038  1381 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-16 14:42:01.146  1927  8182 D WfdsMonitor: Supplicant connection established
08-16 14:42:01.146  1927  2284 D WfdsService: Connected to the supplicant for wfds
08-16 14:42:01.146  1038  1381 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-16 14:42:01.146  8122  8122 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-16 14:42:01.147  1038  1381 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-16 14:42:01.147  1038  1381 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-16 14:42:01.147  8122  8122 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-16 14:42:01.148  1038  1381 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-16 14:42:01.148  1038  1381 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-16 14:42:01.148  8122  8122 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-16 14:42:01.148  1038  1381 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-16 14:42:01.148  1038  1381 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-16 14:42:01.148  8122  8122 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-16 14:42:01.149  1038  1381 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-16 14:42:01.149  1038  1381 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-16 14:42:01.149  8122  8122 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-16 14:42:01.150  1038  1381 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-16 14:42:01.150  1038  1381 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-16 14:42:01.150  8122  8122 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-16 14:42:01.150  1038  1381 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-16 14:42:01.152  1038  1381 E WifiNative: : [198,318,412 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-16 14:42:01.152  1038  1381 D WifiNative-wlan0: doBoolean: RECONNECT
08-16 14:42:01.152  1038  1381 D WifiNative-wlan0: RECONNECT: returned true
08-16 14:42:01.152  1038  1381 D WifiNative-wlan0: doString: [STATUS]
08-16 14:42:01.152  103,8  8172 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-16 14:42:01.152  1038  8172 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-16 14:42:01.153  1038  1381 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-16 14:42:01.153  1038  1381 D WifiNative-wlan0: doBoolean: SET ps 1
08-16 14:42:01.153  1038  1381 D WifiNative-wlan0: SET ps 1: returned true
08-16 14:42:01.154  1038  1377 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:42:01.155   321   895 D CommandListener: Setting iface cfg
08-16 14:42:01.155   321   895 D CommandListener: Trying to bring up p2p0
08-16 14:42:01.155  1038  1377 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-16 14:42:01.156  1038  1377 D LGWifiP2pService: P2pEnablingState
08-16 14:42:01.156  1038  1377 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:42:01.156  1038  1377 D LGWifiP2pService: P2p socket connection successful
08-16 14:42:01.156  1038  1038 D WifiScanningService: SCAN_AVAILABLE : 3
08-16 14:42:01.156  1038  1377 D LGWifiP2pService: P2pEnabledState
08-16 14:42:01.156  1038  1038 D RttService: SCAN_AVAILABLE : 3
08-16 14:42:01.156  1038  1377 D LGWifiP2pService: sending p2p connection changed broadcast
08-16 14:42:01.156  1038  1542 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:42:01.156  1038  1542 I WifiNative-HAL: startHal
08-16 14:42:01.156  1038  1542 D wifi    : getting scan capabilities on interface[1] = 0xaf549bc0
08-16 14:42:01.156  1038  1542 D wifi    : failed to get capabilities : -3
08-16 14:42:01.156  1038  1542 E WifiScanningService: could not get scan capabilities
08-16 14:42:01.156  1038  1543 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:42:01.156  1038  1377 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-16 14:42:01.157  1038  1377 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-16 14:42:01.157  1038  1377 D WifiNative-p2p0: doBoolean: SET device_name G3
08-16 14:42:01.158  1038  1381 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-16 14:42:01.158  1038  1377 D WifiNative-p2p0: SET device_name G3: returned true
08-16 14:42:01.158  1038  1377 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-16 14:42:01.158  1038  1377 D LGWifiP2pService: before postfix = G3
08-16 14:42:01.158  1038  1377 D WifiServerServiceExt: postfix byte check : 2
08-16 14:42:01.158  1038  1377 D LGWifiP2pService: after postfix = G3
08-16 14:42:01.158  1038  1377 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-16 14:42:01.158  1038  1381 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-16 14:42:01.158  1038  1381 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-16 14:42:01.158  1038  1381 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
,08-16 14:42:01.159  1038  1377 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-16 14:42:01.159  1038  1377 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-16 14:42:01.159  1038  1381 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-16 14:42:01.159  1038  1381 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-16 14:42:01.159  1038  1377 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-16 14:42:01.159  1038  1377 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-16 14:42:01.159  1038  1381 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-16 14:42:01.159  1038  1381 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-16 14:42:01.159  8122  8122 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-16 14:42:01.159  1038  1377 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-16 14:42:01.160  1038  1377 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-16 14:42:01.160  1038  1381 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-16 14:42:01.160  1038  1377 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-16 14:42:01.160  1038  1377 D WifiNative-HAL: p2pGetDeviceAddress
08-16 14:42:01.161  1038  1381 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-16 14:42:01.161  1038  1377 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-16 14:42:01.161  1038  1381 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-16 14:42:01.161  1038  1381 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-16 14:42:01.161  8122  8122 E wpa_supplicant: disconnect_rssi_lvl: -100
08-16 14:42:01.162  1038  1381 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
08-16 14:42:01.162  1038  1381 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
,08-16 14:42:01.163  1927  1927 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-16 14:42:01.163  1038  1381 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
08-16 14:42:01.163  1038  1381 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-16 14:42:01.163  8122  8122 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-16 14:42:01.164  8122  8122 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 14:42:01.164  1038  8172 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-16 14:42:01.164  1038  8172 E WifiMonitor: WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 14:42:01.164  8122  8122 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-16 14:42:01.164  1038  8172 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 14:42:01.164  1038  8172 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 14:42:01.164  8122  8122 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 14:42:01.164  1927  1927 D WfdsService: WifiP2pState is changed : true
,08-16 14:42:01.165  1927  1927 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
,08-16 14:42:01.165  1927  1927 D WfdsService: isConnected: false
08-16 14:42:01.165  1927  2284 D WfdsService: Receive the WFDS_ENABLE Method
,08-16 14:42:01.165  8122  8122 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 14:42:01.165  1927  2284 D WfdsService: Set the WFDS Monitor: true
08-16 14:42:01.165  1927  2284 D WfdsService: Connected to the supplicant for wfds
08-16 14:42:01.165  1927  2284 D WfdsJNI : doCommand: WFDS_SET TRUE
08-16 14:42:01.165  1038  8172 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 14:42:01.165  1038  8172 E WifiMonitor: WifiMonitor:p2p0 cnt=47 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 14:42:01.165  1038  8172 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 14:42:01.165  1038  8172 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 14:42:01.165  1038  8172 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 14:42:01.165  1038  8172 E WifiMonitor: WifiMonitor:p2p0 cnt=48 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 14:42:01.165  1038  8172 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 14:42:01.165  1038  8172 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 14:42:01.166  8122  8122 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-16 14:42:01.166  1927  8182 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 14:42:01.167  1927  8182 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 14:42:01.167  1038  1381 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
,08-16 14:42:01.167  1927  2284 D WfdsService: selectPreferredScanChannel [36]
08-16 14:42:01.167  1927  2284 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-16 14:42:01.167  1038  1381 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-16 14:42:01.168  1038  1945 I ActivityManager: Killing 7143:com.android.chrome/u0a57 (adj 15): empty #17
08-16 14:42:01.169  1038  1381 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-16 14:42:01.169  1038  1381 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-16 14:42:01.169  1038  1381 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-16 14:42:01.169  8122  8122 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-16 14:42:01.169  8122  8122 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-16 14:42:01.169  1038  8172 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-16 14:42:01.169  1038  8172 E WifiMonitor: WifiMonitor:wlan0 cnt=49 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-16 14:42:01.169  1038  8172 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-16 14:42:01.169  1038  8172 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-16 14:42:01.170  1038  1381 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-16 14:42:01.170  1038  1381 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-16 14:42:01.171  1038  1381 D WifiNative-wlan0: BSS_FLUSH 0: returned true
,08-16 14:42:01.171  1038  1381 D WifiNative-wlan0: doBoolean: SCAN
08-16 14:42:01.171  1038  1381 D WifiNative-wlan0: SCAN: returned false
08-16 14:42:01.171  1038  1381 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=198339  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-16 14:42:01.186  8163  8163 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-16 14:42:01.201  1038  1377 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
,08-16 14:42:01.201  1038  1377 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-16 14:42:01.201  1038  1377 D WifiNative-p2p0: P2P_FLUSH: returned true
08-16 14:42:01.201  1038  1377 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-16 14:42:01.202  1038  1377 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-16 14:42:01.202  1038  1377 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-16 14:42:01.202  1927  1927 I WfdStateTracker: handleP2pThisDeviceChanged
08-16 14:42:01.202  1038  1377 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-16 14:42:01.202  1927  1927 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-16 14:42:01.202  1038  1377 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-16 14:42:01.202  1927  1927 D WfdsService: Update P2p Interface State: 3
08-16 14:42:01.205  6879  6879 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-16 14:42:01.205  1038  1981 W libprocessgroup: failed to open /acct/uid_10057/pid_7143/cgroup.procs: No such file or directory
08-16 14:42:01.206  1038  1381 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=198373  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-16 14:42:01.206  1038  1381 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
,08-16 14:42:01.207  1038  1381 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 14:42:01.207  1038  1381 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 14:42:01.208  1038  1381 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 14:42:01.208  1038  1381 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 14:42:01.209  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 14:42:01.209  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 14:42:01.209  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 14:42:01.210  1038  1038 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:42:01.210  1038  1038 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:42:01.210  1038  1038 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-16 14:42:01.211  1038  1038 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION,
08-16 14:42:01.211  1038  1038 D WifiServerServiceExt: setSupplicantStateSCANNING
08-16 14:42:01.213  1038  1377 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-16 14:42:01.213  1038  1377 D LGWifiP2pService: sending p2p persistent groups changed broadcast
,08-16 14:42:01.213  1038  1377 D LGWifiP2pService: InactiveState
08-16 14:42:01.213  1038  1377 D LGWifiP2pService: InactiveState{ when=-46ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:42:01.213  1038  1377 D LGWifiP2pService: P2pEnabledState{ when=-46ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:42:01.213  1038  1377 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-16 14:42:01.213  8122  8122 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-16 14:42:01.214  8122  8122 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
,08-16 14:42:01.214  8122  8122 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-16 14:42:01.214  8122  8122 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 14:42:01.214  8122  8122 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 14:42:01.215  1927  8182 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-16 14:42:01.215  1927  8182 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
,08-16 14:42:01.215  1927  8182 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 14:42:01.215  1038  8172 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-16 14:42:01.215  1038  8172 E WifiMonitor: WifiMonitor:p2p0 cnt=50 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 14:42:01.215  1038  8172 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 14:42:01.215  1038  8172 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 14:42:01.215  1038  8172 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 14:42:01.215  1038  8172 E WifiMonitor: WifiMonitor:p2p0 cnt=51 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 14:42:01.215  1038  8172 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,08-16 14:42:01.215  1038  8172 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 14:42:01.215  1038  8172 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 14:42:01.215  1038  8172 E WifiMonitor: WifiMonitor:p2p0 cnt=52 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 14:42:01.215  1038  8172 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 14:42:01.215  1038  8172 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 14:42:01.216  1038  1377 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-16 14:42:01.216  6879  6879 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 14:42:01.216  1038  1377 D LGWifiP2pService: InactiveState{ when=-14ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:42:01.216  1038  1377 D LGWifiP2pService: P2pEnabledState{ when=-14ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
,08-16 14:42:01.216  1038  1377 D LGWifiP2pService: InactiveState{ when=-2ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:42:01.216  1038  1377 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:42:01.216  1038  1377 D LGWifiP2pService: DefaultState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:42:01.216  1038  1377 D LGWifiP2pService: InactiveState{ when=-3ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:42:01.216  1038  1377 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:42:01.216  1038  1377 D LGWifiP2pService: DefaultState{ when=-3ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:42:01.216  1038  1377 D LGWifiP2pService: InactiveState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:42:01.216  1038  1377 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:42:01.216  1038  1377 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
,08-16 14:42:01.216  1038  1377 D LGWifiP2pService: InactiveState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:42:01.216  1038  1377 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:42:01.216  1038  1377 D LGWifiP2pService: DefaultState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:42:01.217  1038  1038 E WifiServerServiceExt: No p2p device connected
08-16 14:42:01.217  1038  1890 I ActivityManager: Killing 7167:com.lge.drmservice/u0a62 (adj 15): empty #17
08-16 14:42:01.217  1927  2284 W WfdsService: DefaultState - msg [9441285] is not handled
,08-16 14:42:01.293  1038  1054 W libprocessgroup: failed to open /acct/uid_10062/pid_7167/cgroup.procs: No such file or directory,
,08-16 14:42:01.324  6879  6879 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
,08-16 14:42:01.324  6879  6879 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
,08-16 14:42:01.324  6879  6879 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-16 14:42:01.324  6879  6879 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-16 14:42:01.324  6879  6879 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-16 14:42:01.325  6879  6879 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-16 14:42:01.325  6879  6879 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-16 14:42:01.325  6879  6879 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-16 14:42:01.325  6879  6879 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-16 14:42:01.325  6879  6879 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-16 14:42:01.326  6879  6879 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-16 14:42:01.338  8163  8163 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-16 14:42:01.346  6879  6879 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-16 14:42:01.355  8140  8186 W FormManager: Network not available. Please check & try again.
,08-16 14:42:01.356  6879  6879 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 14:42:01.367  8140  8187 V FormManager: Network unavailable.
,08-16 14:42:01.371  8140  8187 V FormManager: Network unavailable.
08-16 14:42:01.382  4286  4286 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-16 14:42:01.383  4286  4286 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-16 14:42:01.385  4286  4286 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-16 14:42:01.388  4286  4286 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 14:42:01.404  4286  8188 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-16 14:42:01.414  4286  8189 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-16 14:42:01.415  4286  8189 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-16 14:42:01.441  1038  1908 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=8190 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-16 14:42:01.564  8190  8190 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-16 14:42:01.564  8190  8190 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-16 14:42:01.574  8190  8190 V [BNRBootReceiver]: Boot Receiver Return
08-16 14:42:01.577  8190  8190 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-16 14:42:01.639  1038  1908 I ActivityManager: Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=8211 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-16 14:42:01.641  1038  1908 I ActivityManager: Killing 7184:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
,08-16 14:42:01.691  1038  1053 W libprocessgroup: failed to open /acct/uid_10085/pid_7184/cgroup.procs: No such file or directory
,08-16 14:42:01.715  8211  8211 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-16 14:42:01.726  8122  8122 E wpa_supplicant: USIM:  scard_init function
,08-16 14:42:01.726  8122  8122 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-16 14:42:01.729  1038  8172 E WifiMonitor: WifiMonitor:wlan0 cnt=53 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-16 14:42:01.729  1038  8172 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-16 14:42:01.730  1038  8172 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-16 14:42:01.730  1038  8172 E WifiMonitor: WifiMonitor:wlan0 cnt=54 dispatchEvent: WPS-AP-AVAILABLE 
,08-16 14:42:01.730  1038  8172 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
,08-16 14:42:01.730  1038  8172 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-16 14:42:01.730  1038  8172 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-16 14:42:01.731  1038  1381 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-16 14:42:01.731  1038  1381 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-16 14:42:01.732  1038  1381 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-16 14:42:01.733  1038  1381 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-16 14:42:01.733  1038  1381 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-16 14:42:01.739  1038  1381 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 55 0 rt=198906  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-16 14:42:01.742  1038  1038 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:42:01.742  1038  1038 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:42:01.742  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 14:42:01.742  1038  1038 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-16 14:42:01.742  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 14:42:01.746  8211  8211 D PluginManager: init()
08-16 14:42:01.746  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-16 14:42:01.752  1038  1381 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 55 0 rt=198919  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-16 14:42:01.754  1038  1038 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:42:01.754  1038  1038 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:42:01.754  1038  1038 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-16 14:42:01.755  1038  1038 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 14:42:01.755  1038  1038 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-16 14:42:01.767  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 14:42:01.767  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 14:42:01.769  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-16 14:42:01.847  8122  8122 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-16 14:42:01.851  1038  8172 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-16 14:42:01.851  1038  8172 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-16 14:42:01.852  1038  8172 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-16 14:42:01.852  1038  8172 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-16 14:42:01.852  1038  8172 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 14:42:01.852  1038  8172 E WifiMonitor: WifiMonitor:wlan0 cnt=58 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-16 14:42:01.855  1038  1381 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=199022  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-16 14:42:01.856  1038  1381 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=199023  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-16 14:42:01.858  1038  1381 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=199025
08-16 14:42:01.859  1038  1381 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=199026
08-16 14:42:01.861  1038  1381 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=199027
,08-16 14:42:01.868  8122  8122 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-16 14:42:01.868  8122  8122 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-16 14:42:01.869  1038  1381 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=199036
08-16 14:42:01.871  1038  1381 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=199038
08-16 14:42:01.874  1038  8172 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 14:42:01.874  1038  8172 E WifiMonitor: WifiMonitor:wlan0 cnt=59 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-16 14:42:01.874  1038  8172 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-16 14:42:01.874  1038  8172 E WifiMonitor: WifiMonitor:wlan0 cnt=60 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-16 14:42:01.874  1038  1381 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=199042  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-16 14:42:01.875  1038  8172 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-16 14:42:01.875  1038  8172 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-16 14:42:01.875  1038  8172 E WifiMonitor: WifiMonitor:wlan0 cnt=61 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-16 14:42:01.875  1038  8172 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-16 14:42:01.875  1038  8172 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 14:42:01.875  1038  8172 E WifiMonitor: WifiMonitor:wlan0 cnt=62 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-16 14:42:01.875  1038  1120 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-16 14:42:01.877  1038  1038 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:42:01.877  1038  1038 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:42:01.877  1038  1038 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-16 14:42:01.879  1038  1381 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=199046  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
,08-16 14:42:01.883  1038  1038 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:42:01.883  1038  1038 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:42:01.883  1038  1038 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-16 14:42:01.883  1038  1038 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 14:42:01.883  1038  1038 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-16 14:42:01.883  1038  1381 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
08-16 14:42:01.884  1038  1381 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-16 14:42:01.884  1038  1381 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-16 14:42:01.885  1038  1381 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-16 14:42:01.885  1038  1381 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-16 14:42:01.885  1038  1381 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=199053  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-16 14:42:01.886  1038  1381 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=199053  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-16 14:42:01.887  1038  1381 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=199054
08-16 14:42:01.887  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-16 14:42:01.887  1038  1381 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=199054
08-16 14:42:01.887  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 14:42:01.888  1038  1381 D WifiNative-wlan0: doString: [STATUS]
08-16 14:42:01.888  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 14:42:01.889  1038  8172 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 14:42:01.889  1038  8172 E WifiMonitor: WifiMonitor:wlan0 cnt=63 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-16 14:42:01.890  1038  1381 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-16 14:42:01.892  1038  1381 I WifiServiceExtension: setVHTCapabilityType  : false
08-16 14:42:01.894  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 14:42:01.894  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 14:42:01.895  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-16 14:42:01.899  1038  1381 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-16 14:42:01.899  1038  1381 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
08-16 14:42:01.902  1038  1038 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:42:01.902  1038  1038 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:42:01.902  1038  1038 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-16 14:42:01.909  1038  1038 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:42:01.909  1038  1038 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:42:01.909  1038  1038 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,08-16 14:42:01.912  1038  1381 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-16 14:42:01.912  1038  1381 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-16 14:42:01.912  1038  1448 D ConnectivityService: Got NetworkAgent Messenger
08-16 14:42:01.912  1038  1381 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-16 14:42:01.912  1038  1448 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-16 14:42:01.912  1038  1448 D ConnectivityService: NetworkAgent connected
08-16 14:42:01.912  1038  1381 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-16 14:42:01.913  1038  1381 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-16 14:42:01.914  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 14:42:01.914  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 14:42:01.915  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 14:42:01.916  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 14:42:01.916  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 14:42:01.917  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 14:42:01.919  1038  1381 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-16 14:42:01.919  1038  1381 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-16 14:42:01.919  1038  1381 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-16 14:42:01.920  1038  1381 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-16 14:42:01.920  1038  1381 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-16 14:42:01.923  1038  1381 D WifiNative-wlan0: SAVE_CONFIG: returned true
,08-16 14:42:01.925   321   895 D CommandListener: Setting iface cfg
08-16 14:42:01.928  1038  8229 D DhcpStateMachine: StoppedState
08-16 14:42:01.928  1038  1381 E WifiStateMachine: Start Dhcp Watchdog 3
08-16 14:42:01.928  1038  8229 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:42:01.928  1038  8229 D DhcpStateMachine: WaitBeforeStartState
08-16 14:42:01.928  1038  1381 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 62 0 rt=199095  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 14:42:01.929  1038  1381 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 62 0 rt=199096  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 14:42:01.929  1038  1381 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 62 0 rt=199096  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 14:42:01.930  1038  1038 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 14:42:01.930  1038  1038 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-16 14:42:01.933  1038  1038 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 14:42:01.933  1038  1038 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-16 14:42:01.933  1038  1381 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=199100  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 14:42:01.934  1038  1381 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=199101  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 14:42:01.934  1038  1381 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=199101  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 14:42:01.935  1038  1381 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:24316] from screen [on:0 period:-1822460593] gl rssi=-54 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-16 14:42:01.936  1038  1381 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1822460592] gl rssi=-54 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-16 14:42:01.936  1038  1381 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-16 14:42:01.942  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 14:42:01.944  1038  1381 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
,08-16 14:42:01.945  1038  1381 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
,08-16 14:42:01.945  1038  1381 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 14:42:01.946  1038  1381 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 14:42:01.946  1038  1381 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 14:42:01.946  1038  1381 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 14:42:01.947  1038  1381 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=137,0,0
08-16 14:42:01.947  1038  1381 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=137,0,0
08-16 14:42:01.947  1038  1381 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-16 14:42:01.948  1038  1448 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
08-16 14:42:01.948  1038  1448 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-16 14:42:01.948  8122  8122 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
,08-16 14:42:01.948  1038  1381 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-16 14:42:01.948  1038  1381 D WifiNative-wlan0: doBoolean: SET ps 0
08-16 14:42:01.948  1038  1381 D WifiNative-wlan0: SET ps 0: returned true
08-16 14:42:01.948  1038  1381 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-16 14:42:01.949  8122  8122 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-16 14:42:01.949  1038  1381 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-16 14:42:01.949  1038  1377 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3e2d3bb8 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:42:01.949  1038  1377 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3e2d3bb8 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:42:01.950  1038  8229 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:42:01.950  1038  8229 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-16 14:42:01.951  1038  1381 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-16 14:42:01.951  1038  1381 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-16 14:42:01.951  1038  1381 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-16 14:42:01.952   321   895 D CommandListener: Setting iface cfg
08-16 14:42:01.952   321   895 D CommandListener: Trying to bring up wlan0
08-16 14:42:01.954  1038  1381 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.135/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-16 14:42:01.954  1038  1038 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 14:42:01.954  1038  1038 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-16 14:42:01.955  1038  1038 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 14:42:01.955  1038  1038 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-16 14:42:01.956  1038  1381 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 14:42:01.956  1038  1381 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 14:42:01.957  1038  1381 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 14:42:01.957  1038  1381 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 14:42:01.957  1038  1381 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 14:42:01.958  1038  1381 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 14:42:01.958  1038  1448 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-16 14:42:01.959  1038  1381 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-16 14:42:01.959  1038  1381 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-16 14:42:01.959  1038  1381 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-16 14:42:01.959  8122  8122 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-16 14:42:01.959  1038  1377 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:42:01.960  1038  1377 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:42:01.960  1038  1381 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-16 14:42:01.960  1038  1381 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-16 14:42:01.961  8122  8122 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-16 14:42:01.963  1038  1381 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-16 14:42:01.963  1038  1381 D WifiNative-wlan0: doBoolean: SET ps 1
,08-16 14:42:01.976  1038  1381 D WifiNative-wlan0: SET ps 1: returned true
,08-16 14:42:01.977  1038  1448 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
,08-16 14:42:01.977  1038  1381 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-16 14:42:01.978  1038  1381 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-16 14:42:01.978  1038  1381 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-16 14:42:01.978  1038  1448 D ConnectivityService: ignoring duplicate network state non-change
08-16 14:42:01.981  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 14:42:01.981  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 14:42:01.982  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 14:42:01.985  1038  1038 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:42:01.985  1038  1038 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:42:01.985  1038  1038 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-16 14:42:01.988  1038  1448 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-16 14:42:01.989  1038  1448 D ConnectivityService: Adding iface wlan0 to network 102
08-16 14:42:02.003  1038  1038 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:42:02.003  1038  1038 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:42:02.003  1038  1038 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,08-16 14:42:02.008  1038  1038 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-16 14:42:02.008  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 14:42:02.008  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 14:42:02.008  1038  1038 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:42:02.008  1038  1038 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:42:02.008  1038  1038 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-16 14:42:02.010  1927  1927 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-16 14:42:02.011  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 14:42:02.014  1038  1038 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-16 14:42:02.014  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 14:42:02.014  1589  1589 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-16 14:42:02.014  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 14:42:02.020  1038  1038 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:42:02.020  1038  1038 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:42:02.020  1038  1038 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
,08-16 14:42:02.022  1038  1381 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-16 14:42:02.023  1038  1448 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-16 14:42:02.023  1038  1448 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
08-16 14:42:02.026  1038  1448 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
08-16 14:42:02.027   321   895 E Netd    : netlink response contains error (File exists)
08-16 14:42:02.027  1038  1448 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
08-16 14:42:02.029  1038  1448 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-16 14:42:02.029  1038  1448 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 102
08-16 14:42:02.029  1038  1448 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
08-16 14:42:02.032  1038  1448 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-16 14:42:02.032  1038  1448 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-16 14:42:02.032  1038  1448 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-16 14:42:02.034  1038  8228 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-2ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:42:02.034  1038  8228 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-16 14:42:02.035  1038  8228 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:42:02.035  1038  8228 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-16 14:42:02.036  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 14:42:02.036  1589  1589 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-16 14:42:02.037  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 14:42:02.039   321  8238 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-16 14:42:02.039  1038  1448 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-16 14:42:02.039  1038  1448 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 14:42:02.040  1038  1448 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 14:42:02.040  1038  1448 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-16 14:42:02.040  1038  1448 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-16 14:42:02.042  1038  1448 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-16 14:42:02.042  1038  1448 D ConnectivityService: currentScore = 0, newScore = 20
08-16 14:42:02.042  1038  1448 D ConnectivityService:    accepting network in place of null
08-16 14:42:02.042  1038  1448 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 14:42:02.042  1038  1381 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 14:42:02.042  1038  1381 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 14:42:02.043  1839  1839 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 14:42:02.043  1839  1839 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-16 14:42:02.044  1038  1448 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-16 14:42:02.044  1038  1448 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
08-16 14:42:02.045  1038  1448 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-16 14:42:02.045  1038  1448 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-16 14:42:02.045  1038  1448 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-16 14:42:02.046  1038  1448 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-16 14:42:02.047  1038  1448 D ConnectivityService: validation of new default Network = false
08-16 14:42:02.047  1038  1448 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-16 14:42:02.047  1038  1448 D DSQN    : enableDataServiceNotify 
08-16 14:42:02.047  1038  1448 D DSQN    : start dsqn bin
08-16 14:42:02.047  1038  1038 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-16 14:42:02.048  1038  1038 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-16 14:42:02.048  1038  1038 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified),, extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-16 14:42:02.048  1038  1038 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-16 14:42:02.052  1038  1448 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-16 14:42:02.052  1038  1448 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 14:42:02.052  1038  1448 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 14:42:02.052  1038  1448 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 14:42:02.049  8240  8240 W dsqn    : type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-16 14:42:02.049  8240  8240 W dsqn    : type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 14:42:02.066  1038  1375 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
08-16 14:42:02.067  8240  8240 E DSQN    : DSQN ssw
,08-16 14:42:02.079  1589  1589 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-16 14:42:02.080  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 14:42:02.081  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 14:42:02.088   321  8238 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-16 14:42:02.122   321  8238 D libc-netbsd: res_queryN name = clients3.google.com succeed
,08-16 14:42:02.153  1038  8229 D DhcpStateMachine: DHCPV4 request on wlan0
,08-16 14:42:02.154  1038  8229 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-16 14:42:02.155  1038  8229 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-16 14:42:02.161   321   894 D LGDataListener: argv[0]=dsqncommand
08-16 14:42:02.161   321   894 D LGDataListener: argv[1]=wlan0
08-16 14:42:02.161   321   894 D LGDataListener: argv[2]=1
08-16 14:42:02.161   321   894 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-16 14:42:02.159  8244  8244 W dhcpcd  : type=1400 audit(0.0:193): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 14:42:02.162  1038  1118 D DSQN    : DSQM DsqnNotification wlan0  1
08-16 14:42:02.159  8244  8244 W dhcpcd  : type=1400 audit(0.0:194): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 14:42:02.162  1038  1118 D DSQN    : start to monitor internet connection
08-16 14:42:02.167  8244  8244 I dhcpcd  : version 5.5.6 starting
08-16 14:42:02.168  8244  8244 E dhcpcd  : get_duid: m
08-16 14:42:02.168  8244  8244 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-16 14:42:02.168  8244  8244 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,08-16 14:42:02.195  1038  8228 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 16 Aug 2016 12:42:02 GMT], X-Android-Received-Millis=[1471351322195], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1471351322159]}
08-16 14:42:02.196  1038  8228 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-16 14:42:02.196  1038  8228 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-16 14:42:02.196  1038  1448 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
08-16 14:42:02.196  1038  1448 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-16 14:42:02.196  1038  1448 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 14:42:02.196  1038  1448 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 14:42:02.196  1038  1448 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-16 14:42:02.196  1038  1448 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
08-16 14:42:02.197  1038  1448 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-16 14:42:02.197  1038  1448 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 14:42:02.197  1038  1448 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 14:42:02.197  1038  1448 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 14:42:02.197  1038  1448 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 14:42:02.198  1038  1448 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-16 14:42:02.198  1038  1381 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 14:42:02.198  1038  1381 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 14:42:02.199  1839  1839 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 14:42:02.199  1589  1837 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-16 14:42:02.200  1839  1839 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
,08-16 14:42:02.230  1589  1589 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-16 14:42:02.231  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 14:42:02.232  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 14:42:02.251  8211  8211 W ExternalStrings: load override strings
08-16 14:42:02.251  8211  8211 W ExternalStrings: java.lang.RuntimeException: Unexpected tag, got eat-comment
08-16 14:42:02.251  8211  8211 W ExternalStrings: 	at com.mcafee.plugin.af.a(Unknown Source)
08-16 14:42:02.251  8211  8211 W ExternalStrings: 	at com.mcafee.plugin.ac.b(Unknown Source)
08-16 14:42:02.251  8211  8211 W ExternalStrings: 	at com.mcafee.plugin.ak.d(Unknown Source)
08-16 14:42:02.251  8211  8211 W ExternalStrings: 	at com.mcafee.plugin.ak.a(Unknown Source)
08-16 14:42:02.251  8211  8211 W ExternalStrings: 	at com.mcafee.app.s.getClassLoader(Unknown Source)
08-16 14:42:02.251  8211  8211 W ExternalStrings: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
08-16 14:42:02.251  8211  8211 W ExternalStrings: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-16 14:42:02.251  8211  8211 W ExternalStrings: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-16 14:42:02.251  8211  8211 W ExternalStrings: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-16 14:42:02.251  8211  8211 W ExternalStrings: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-16 14:42:02.251  8211  8211 W ExternalStrings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 14:42:02.251  8211  8211 W ExternalStrings: 	at android.os.Looper.loop(Looper.java:135)
08-16 14:42:02.251  8211  8211 W ExternalStrings: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-16 14:42:02.251  8211  8211 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 14:42:02.251  8211  8211 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 14:42:02.251  8211  8211 W ExternalStrings: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-16 14:42:02.251  8211  8211 W ExternalStrings: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,08-16 14:42:02.252  8211  8211 D StatusProvider: onCreate
08-16 14:42:02.288  8244  8244 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-16 14:42:02.288  8244  8244 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
,08-16 14:42:02.288  8244  8244 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-16 14:42:02.289  8244  8244 I dhcpcd  : wlan0: rebinding lease of 192.168.1.135
08-16 14:42:02.289  8244  8244 D dhcpcd  : wlan0: sending REQUEST (xid 0xefbf1bb6), next in 4.34 seconds
08-16 14:42:02.296  8211  8211 V Signer  : override build config not found
08-16 14:42:02.296  8211  8211 D Signer  : value of property debug is false
08-16 14:42:02.309  8244  8244 I dhcpcd  : wlan0: acknowledged 192.168.1.135 from 192.168.1.1
,08-16 14:42:02.325  8211  8211 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
08-16 14:42:02.325  8211  8211 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
,08-16 14:42:02.326  8211  8211 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
,08-16 14:42:02.326  8211  8211 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
08-16 14:42:02.326  8211  8211 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
08-16 14:42:02.326  8211  8211 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
08-16 14:42:02.326  8211  8211 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
,08-16 14:42:02.327  8211  8211 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
08-16 14:42:02.327  8211  8211 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
08-16 14:42:02.327  8211  8211 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
08-16 14:42:02.327  8211  8211 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
08-16 14:42:02.328  8211  8211 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
08-16 14:42:02.328  8211  8211 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
08-16 14:42:02.337  8211  8211 V LGMDMManager: Create singleton instance
08-16 14:42:02.350  8244  8244 I dhcpcd  : wlan0: leased 192.168.1.135 for 172800 seconds
08-16 14:42:02.350  8244  8244 D dhcpcd  : wlan0: adding IP address 192.168.1.135/24
08-16 14:42:02.351  8244  8244 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-16 14:42:02.351  8244  8244 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-16 14:42:02.352  8244  8244 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-16 14:42:02.352  8244  8244 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-16 14:42:02.353  8244  8244 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-16 14:42:02.353  8244  8244 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,08-16 14:42:02.388  8211  8211 D LGMDMWrapper: LG MDM library v4.0.0 is available on this device.
,08-16 14:42:02.461  8211  8211 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-16 14:42:02.466  8211  8262 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-16 14:42:02.473  6879  6879 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 14:42:02.479  6879  6879 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 14:42:02.485  7872  7872 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 14:42:02.488  7872  7872 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 14:42:02.497  7872  7872 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-16 14:42:02.500  6879  6879 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
08-16 14:42:02.503  6879  6879 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-16 14:42:02.510  8211  8211 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-16 14:42:02.511  8211  8262 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-16 14:42:02.516  6879  6879 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 14:42:02.524  6879  6879 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 14:42:02.531  7872  7872 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-16 14:42:02.531  7872  7872 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 14:42:02.532  7872  7872 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-16 14:42:02.607  8211  8211 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 14:42:02.607  8211  8262 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-16 14:42:02.612  6879  6879 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-16 14:42:02.612  8211  8260 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
08-16 14:42:02.620  6879  6879 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 14:42:02.629  7872  7872 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 14:42:02.629  7872  7872 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-16 14:42:02.629  7872  7872 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-16 14:42:02.632  6879  6879 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-16 14:42:02.632  6879  6879 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-16 14:42:02.632  6879  6879 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-16 14:42:02.632  6879  6879 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-16 14:42:02.632  6879  6879 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-16 14:42:02.633  6879  6879 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-16 14:42:02.633  6879  6879 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-16 14:42:02.633  6879  6879 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-16 14:42:02.633  6879  6879 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-16 14:42:02.633  6879  6879 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-16 14:42:02.633  6879  6879 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-16 14:42:02.633  6879  6879 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-16 14:42:02.639  8211  8211 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 14:42:02.641  8211  8262 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-16 14:42:02.654  6879  6879 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 14:42:02.667  6879  6879 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 14:42:02.677  7872  7872 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 14:42:02.678  7872  7872 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 14:42:02.679  7872  7872 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-16 14:42:02.682  8211  8211 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 14:42:02.683  8211  8262 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-16 14:42:02.694  6879  6879 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 14:42:02.706  6879  6879 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 14:42:02.717  7872  7872 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-16 14:42:02.718  7872  7872 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 14:42:02.719  7872  7872 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-16 14:42:02.727  8211  8211 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 14:42:02.728  8211  8262 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-16 14:42:02.742  6879  6879 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 14:42:02.756  6879  6879 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-16 14:42:02.761  1038  8229 D DhcpStateMachine: DHCPV4 succeeded on wlan0
08-16 14:42:02.763  1038  8229 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
,08-16 14:42:02.764  1038  8229 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-16 14:42:02.764  1038  8229 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.135
08-16 14:42:02.764  1038  8229 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-16 14:42:02.764  1038  8229 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-16 14:42:02.764  1038  8229 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-16 14:42:02.764  1038  8229 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-16 14:42:02.765  1038  8229 D DhcpStateMachine: RunningState
08-16 14:42:02.766  7872  7872 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 14:42:02.766  7872  7872 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 14:42:02.766  7872  7872 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-16 14:42:02.769  8211  8211 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 14:42:02.769  8211  8262 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-16 14:42:02.778  6879  6879 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 14:42:02.785  6879  6879 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 14:42:02.794  7872  7872 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 14:42:02.794  7872  7872 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 14:42:02.795  7872  7872 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-16 14:42:02.818  8211  8211 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 14:42:02.818  8211  8262 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-16 14:42:02.831  6879  6879 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 14:42:02.836  6879  6879 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 14:42:02.842  7872  7872 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 14:42:02.842  7872  7872 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 14:42:02.848  7872  7872 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-16 14:42:02.851  8211  8211 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 14:42:02.851  8211  8262 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-16 14:42:02.858  6879  6879 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-16 14:42:02.863  6879  6879 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 14:42:02.869  7872  7872 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 14:42:02.869  7872  7872 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 14:42:02.870  7872  7872 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-16 14:42:02.873  8211  8211 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 14:42:02.873  8211  8262 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-16 14:42:02.876  8163  8163 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-16 14:42:02.879  8163  8163 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-16 14:42:02.880  8211  8260 D LgDataFeature: LgDataFeature() Constructor: none
08-16 14:42:02.880  8211  8260 D LgDataFeature: LgDataFeature() Constructor Done, null
08-16 14:42:02.882  6879  6879 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 14:42:02.888  6879  6879 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 14:42:02.894  7872  7872 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 14:42:02.894  7872  7872 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-16 14:42:02.895  7872  7872 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-16 14:42:02.896  7872  7872 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-16 14:42:02.897  7872  7872 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-16 14:42:02.902  8211  8211 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 14:42:02.902  8211  8262 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-16 14:42:02.905  8163  8163 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-16 14:42:02.906  8163  8163 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,08-16 14:42:02.909  6879  6879 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-16 14:42:02.914  6879  6879 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 14:42:02.921  7872  7872 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 14:42:02.921  7872  7872 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 14:42:02.922  7872  7872 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-16 14:42:02.922  7872  7872 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-16 14:42:02.923  7872  7872 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,08-16 14:42:02.926  8211  8211 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-16 14:42:02.927  8211  8211 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-16 14:42:02.929  8211  8211 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-16 14:42:02.930  8211  8211 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-16 14:42:02.932  8211  8211 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-16 14:42:02.934  8211  8211 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-16 14:42:02.936  8211  8211 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
,08-16 14:42:02.938  8211  8211 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-16 14:42:02.939  8211  8211 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-16 14:42:02.941  8211  8211 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-16 14:42:02.943  8211  8211 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-16 14:42:02.944  1038  1054 I ActivityManager: Killing 7220:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
08-16 14:42:03.004  8211  8260 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
,08-16 14:42:03.186  1038  1945 W libprocessgroup: failed to open /acct/uid_10093/pid_7220/cgroup.procs: No such file or directory
,08-16 14:42:03.233  1038  1381 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-16 14:42:03.236  8211  8260 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
08-16 14:42:03.240  1038  1381 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 14:42:03.241  1038  1381 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 14:42:03.243  1038  1381 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 14:42:03.244  1038  1381 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 14:42:03.245  1038  1381 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 14:42:03.246  8211  8260 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
08-16 14:42:03.246  8211  8260 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-16 14:42:03.246  1038  1448 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=true
08-16 14:42:03.247  1038  1448 D ConnectivityService: identical MTU - not setting
08-16 14:42:03.247  1038  1448 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-16 14:42:03.247  1038  1448 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-16 14:42:03.247  1038  1448 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 14:42:03.247  1038  1448 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 14:42:03.247  1038  1448 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 14:42:03.248  1589  1837 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
08-16 14:42:03.249  8211  8260 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-16 14:42:03.249  8211  8260 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
08-16 14:42:03.250  8211  8260 I SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
,08-16 14:42:03.253  8211  8260 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
,08-16 14:42:03.258  8211  8260 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
,08-16 14:42:04.948  1038  1381 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-54 f=2447 sc=60 link=72 tx=68.5, 0.0, 0.0  rx=65.5 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1822457580] gl rssi=-54 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-16 14:42:04.959  1038  1381 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-54 f=2447 sc=60 link=72 tx=68.5, 0.0, 0.0  rx=65.5 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1822457569] gl rssi=-54 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-16 14:42:04.959  1038  1381 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-16 14:42:04.975  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-16 14:42:05.012  1038  1424 V WifiInternetCheck: Single check msg out of sync, ignoring.
,08-16 14:42:05.047  1038  1448 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-16 14:42:05.062  1038  1120 D Tethering: MasterInitialState.processMessage what=3
,08-16 14:42:05.083  6608  6608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 14:42:05.083  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:42:05.083  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 14:42:05.083  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 14:42:05.083  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 14:42:05.083  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 14:42:05.083  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 14:42:05.083  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 14:42:05.088  6608  6608 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 14:42:05.093  6608  6608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 14:42:05.093  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:42:05.093  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 14:42:05.093  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 14:42:05.093  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 14:42:05.093  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 14:42:05.093  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 14:42:05.093  6608  6608 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 14:42:05.094  6608  6608 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 14:42:05.098  1038  1107 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-16 14:42:05.103  8211  8211 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-16 14:42:05.106  5680  5680 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,08-16 14:42:05.141  1038  1107 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-16 14:42:05.149  8211  8260 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-16 14:42:05.167  2178  2178 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-16 14:42:05.184  1038  1890 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 102]) by 10005
,08-16 14:42:05.186  1038  8228 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-2ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:42:05.187  1038  8228 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-2ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:42:05.187  1038  8228 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-16 14:42:05.187  1038  8228 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:42:05.187  1038  8228 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-16 14:42:05.198   321  8305 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,08-16 14:42:05.205   321  8305 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
,08-16 14:42:05.213  6608  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 14:42:05.213  6608  6679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:42:05.213  6608  6679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 14:42:05.213  6608  6679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 14:42:05.213  6608  6679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 14:42:05.213  6608  6679 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 14:42:05.213  6608  6679 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 14:42:05.213  6608  6679 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 14:42:05.215  6608  6679 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 14:42:05.215  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:42:05.215  6608  6679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@164b0303 removed from the list
08-16 14:42:05.216  6608  6679 D io.jxcore.node.ConnectivityMonitor: stop
08-16 14:42:05.216  6608  6679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:42:05.216  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:42:05.216  7047  7047 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-16 14:42:05.216  7047  7047 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-16 14:42:05.216  7047  7047 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-16 14:42:05.216  7047  7047 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-16 14:42:05.221  7047  7047 I AppUp4:CustModeStarterReceiver: onReceive
08-16 14:42:05.222  6608  8314 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
08-16 14:42:05.222  6608  8314 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-16 14:42:05.228  7047  7047 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2701228a
08-16 14:42:05.228  7047  7047 D AppUp4:CustFacade: isCustomizationCompleted : false
08-16 14:42:05.228  7047  7047 D AppUp4:CustFacade: isPhone : true
08-16 14:42:05.228  1038  8228 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 16 Aug 2016 12:42:05 GMT], X-Android-Received-Millis=[1471351325228], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1471351325190]}
08-16 14:42:05.228  1038  8228 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-16 14:42:05.229  1038  8228 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-16 14:42:05.229  1038  1448 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
08-16 14:42:05.229  1038  1448 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-16 14:42:05.230  1038  1448 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 14:42:05.230  1038  1448 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 14:42:05.230  1038  1448 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-16 14:42:05.230  1038  1448 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
08-16 14:42:05.230  1038  1448 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-16 14:42:05.230  1038  1448 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 14:42:05.230  1038  1448 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 14:42:05.230  1038  1448 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 14:42:05.231  1589  1837 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-16 14:42:05.231  7047  7047 D AppUp4:CustModeStarterReceiver: begin check event
08-16 14:42:05.231  7047  7047 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-16 14:42:05.236  4286  4286 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,08-16 14:42:05.237   321  8305 D libc-netbsd: res_queryN name = mtalk.google.com succeed
,08-16 14:42:05.242  4286  4286 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-16 14:42:05.244  4286  4286 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 14:42:05.246  4286  4286 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 14:42:05.250  3472  3472 V DownloadManager: Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,08-16 14:42:05.254  3472  3472 V DownloadManager: DownloadService onCreate
08-16 14:42:05.256  3472  8323 I DownloadManager: in removeSpuriousFiles
08-16 14:42:05.257  3472  8323 V DownloadManager: starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
08-16 14:42:05.257  4286  8317 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-16 14:42:05.258  3472  8323 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@83ee8e on behalf of 3472
08-16 14:42:05.259  3472  8323 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
08-16 14:42:05.259  3472  8323 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGEIME_5.1.29_release_repacked_ARM_XT9_MYSCRIPT_20160317004155539.apk
08-16 14:42:05.259  3472  8323 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_5.1.24_COM_COM(9012_VDF)_20160401022656759.apk
08-16 14:42:05.259  3472  8323 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
08-16 14:42:05.259  3472  8323 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
08-16 14:42:05.259  3472  8323 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
08-16 14:42:05.259  3472  8323 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
08-16 14:42:05.259  3472  8323 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/ConciergeBoard_4.40.12_COM_COM(VDF)_20160126234417577.apk
08-16 14:42:05.259  3472  8323 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
08-16 14:42:05.259  3472  8323 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
08-16 14:42:05.259  3472  8323 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
08-16 14:42:05.261  4286  8317 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,08-16 14:42:05.263  3472  8323 I DownloadManager: in trimDatabase
08-16 14:42:05.263  3472  8323 V DownloadManager: starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
08-16 14:42:05.264  3472  8323 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@3ab006af on behalf of 3472
08-16 14:42:05.266  4286  8322 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-16 14:42:05.267  4286  8322 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-16 14:42:05.304  1038  2019 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=8327 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
08-16 14:42:05.306  3472  3472 V DownloadManager: DownloadService onStartCommand
,08-16 14:42:05.310  4286  8317 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
08-16 14:42:05.311  3472  8324 V DownloadManager: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
08-16 14:42:05.312  3472  8324 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@2dd4659a on behalf of 3472
08-16 14:42:05.314  4286  4286 E LGDMClient: [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
08-16 14:42:05.314  4286  4286 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
08-16 14:42:05.315  3472  8324 V DownloadManager: processing inserted download 1
08-16 14:42:05.315  4286  4286 D LGDMClient: [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
08-16 14:42:05.316  3472  8324 V DownloadManager: processing inserted download 4
08-16 14:42:05.316  4286  4286 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [274] : DmConstants.DMAgentState.DMA_STATE_IDLE
08-16 14:42:05.317  3472  8324 V DownloadManager: processing inserted download 7
08-16 14:42:05.318  3472  8324 V DownloadManager: processing inserted download 8
08-16 14:42:05.319  3472  8324 V DownloadManager: processing inserted download 9
08-16 14:42:05.320  4286  4286 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [659] : agentmodeOnOff is OFF. Finish OneDayWiFiCheck
,08-16 14:42:05.323  3472  8324 V DownloadManager: processing inserted download 10
08-16 14:42:05.325  3472  8324 V DownloadManager: processing inserted download 11
08-16 14:42:05.341  3472  8324 V DownloadManager: processing inserted download 12
08-16 14:42:05.342  3472  8324 V DownloadManager: processing inserted download 13
,08-16 14:42:05.343  3472  8324 V DownloadManager: processing inserted download 14
08-16 14:42:05.345  3472  8324 V DownloadManager: processing inserted download 16
08-16 14:42:05.355  3472  3472 V DownloadManager: DownloadService onDestroy
,08-16 14:42:05.373  8327  8327 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-16 14:42:05.373  8327  8327 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-16 14:42:05.375  8327  8327 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,08-16 14:42:05.375  8327  8327 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-16 14:42:05.451  8327  8327 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-16 14:42:05.462  8327  8327 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
08-16 14:42:05.494  8327  8327 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-16 14:42:05.518  8327  8327 D LgDataFeature: LgDataFeature() Constructor: none
08-16 14:42:05.518  8327  8327 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 14:42:05.700  8327  8327 D eas_req : ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-16 14:42:05.789  8327  8327 I HubEmail: JNI_OnLoad()
08-16 14:42:05.789  8327  8327 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-16 14:42:05.789  8327  8327 I HubEmail: registerNatives()
08-16 14:42:05.789  8327  8327 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-16 14:42:05.789  8327  8327 I HubEmail: registerNativeMethods()
08-16 14:42:05.789  8327  8327 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-16 14:42:05.789  8327  8327 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,08-16 14:42:05.796  3346  3346 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-16 14:42:05.796  3346  3346 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-16 14:42:05.796  3346  3346 I LgeMiscReceiver: networkInfo.isConnected() = true
08-16 14:42:05.796  3346  3346 D PhoneState: setPdpRejectCasuse : false
08-16 14:42:05.853  1038  2018 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=8365 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,08-16 14:42:05.916  8327  8390 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 14:42:05.924   321  8392 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-16 14:42:05.924   321  8392 D libc-netbsd: res_queryN name = static-avc.lglime.com, class = 1, type = 1
08-16 14:42:05.975   321  8392 D libc-netbsd: res_queryN name = static-avc.lglime.com succeed
,08-16 14:42:05.985  8365  8365 D LgDataFeature: LgDataFeature() Constructor: none
08-16 14:42:05.985  8365  8365 D LgDataFeature: LgDataFeature() Constructor Done, null
08-16 14:42:05.989  8365  8365 D PhoneMonitor: Register our PhoneStateListener
,08-16 14:42:06.011  8365  8365 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,08-16 14:42:06.015  8365  8365 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-16 14:42:06.044  8365  8365 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,08-16 14:42:06.045  8365  8365 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
,08-16 14:42:06.046  8365  8365 D TelephonyAutoProfiling: [parse] Load xml
08-16 14:42:06.051  8365  8365 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
08-16 14:42:06.051  8365  8365 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
08-16 14:42:06.052  8365  8365 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-16 14:42:06.052  8365  8365 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
08-16 14:42:06.052  8365  8365 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
08-16 14:42:06.052  8365  8365 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
08-16 14:42:06.052  8365  8365 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-16 14:42:06.052  8365  8365 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-16 14:42:06.052  8365  8365 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-16 14:42:06.052  8365  8365 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-16 14:42:06.052  8365  8365 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-16 14:42:06.052  8365  8365 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-16 14:42:06.052  8365  8365 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-16 14:42:06.052  8365  8365 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-16 14:42:06.054  8365  8365 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-16 14:42:06.054  8365  8365 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-16 14:42:06.054  8365  8365 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
,08-16 14:42:06.064  8365  8365 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
08-16 14:42:06.077  1038  1054 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=8404 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-16 14:42:06.078  8140  8363 V FormManager: There are no updated forms. The schedule will be deleted.
08-16 14:42:06.079  1038  1054 I ActivityManager: Killing 7714:com.google.android.talk/u0a72 (adj 15): empty #17
,08-16 14:42:06.085  8140  8363 V FormManager: Alarm would be updated, because LastCheckTime has been updated.
,08-16 14:42:06.183  1038  2019 W libprocessgroup: failed to open /acct/uid_10072/pid_7714/cgroup.procs: No such file or directory
,08-16 14:42:06.227   321  8422 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-16 14:42:06.227   321  8422 D libc-netbsd: res_queryN name = www.google.com, class = 1, type = 1
08-16 14:42:06.229  1038  1588 I ActivityManager: Killing 7766:com.android.contacts/u0a19 (adj 15): empty #17
08-16 14:42:06.262   321  8422 D libc-netbsd: res_queryN name = www.google.com succeed
,08-16 14:42:06.271   321  8426 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,08-16 14:42:06.271   321  8426 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-16 14:42:06.271   321  8426 D libc-netbsd: res_queryN name = clients3.google.com succeed
08-16 14:42:06.291  1038  1944 W libprocessgroup: failed to open /acct/uid_10019/pid_7766/cgroup.procs: No such file or directory
08-16 14:42:06.291  1803  8421 I CheckinService: active receiver: enabled
,08-16 14:42:06.305  1803  8421 I CheckinService: Preparing to send checkin request
08-16 14:42:06.305  1803  8421 I EventLogService: Accumulating logs since 1471351291763
,08-16 14:42:06.341  1038  1425 V WifiInternetCheck: isHttpConnectionAvailable - We got a valid response : 204
,08-16 14:42:06.415  1038  1945 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=8431 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,08-16 14:42:06.417  1038  1945 I ActivityManager: Killing 7789:com.android.gallery3d/u0a27 (adj 15): empty #17
,08-16 14:42:06.474  1038  1053 W libprocessgroup: failed to open /acct/uid_10027/pid_7789/cgroup.procs: No such file or directory
08-16 14:42:06.473  1803  8421 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,08-16 14:42:06.589  1038  1909 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=8448 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-16 14:42:06.591  1038  1909 I ActivityManager: Killing 7808:com.android.vending/u0a44 (adj 15): empty #17
,08-16 14:42:06.707  1038  1945 W libprocessgroup: failed to open /acct/uid_10044/pid_7808/cgroup.procs: No such file or directory
,08-16 14:42:06.757  8448  8448 I art     : Almond Protected OAT
,08-16 14:42:06.822  1038  1982 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=8465 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
08-16 14:42:06.823  8448  8448 D WeatherApplication: removeAccount
08-16 14:42:06.824  8448  8448 D WeatherApplication: Account.length = 0
08-16 14:42:06.825  8448  8448 E WeatherApplication: OPERATOR:OPEN
,08-16 14:42:06.830  8448  8448 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:42:6
08-16 14:42:06.851   351   351 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 458us total 27.457ms
,08-16 14:42:06.862  8448  8448 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-16 14:42:06.862  8448  8448 D Weather.Utils: 2 : All the weather widget is gone.
08-16 14:42:06.870   351   351 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 375us total 17.995ms
,08-16 14:42:06.874  8448  8448 D UpdateThreadPoolManager: 2 : This is isUpdating : false
,08-16 14:42:06.879  8448  8448 D WeatherAncestor: connectivity changed - connection : true
08-16 14:42:06.882  8448  8448 D WeatherService: 2 : isServiceAlived():false forecastCache:null
,08-16 14:42:06.888   351   351 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 359us total 17.354ms
08-16 14:42:06.900  8448  8448 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-16 14:42:06.900  8448  8448 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-16 14:42:06.901  8448  8448 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
08-16 14:42:06.908  8465  8465 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-16 14:42:06.908  8465  8465 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-16 14:42:06.921  8448  8448 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-16 14:42:06.922  8448  8448 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:42:6
08-16 14:42:06.938  8465  8465 I MultiDex: VM with version 2.1.0 has multidex support
,08-16 14:42:06.939  8465  8465 I MultiDex: install
08-16 14:42:06.939  8465  8465 I MultiDex: VM has multidex support, MultiDex support library is disabled.
08-16 14:42:06.955  1038  1908 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=8489 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-16 14:42:06.956  1038  1908 I ActivityManager: Killing 7850:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,08-16 14:42:06.991  1038  1054 W libprocessgroup: failed to open /acct/uid_10080/pid_7850/cgroup.procs: No such file or directory
,08-16 14:42:07.125  1038  1890 I art     : Explicit concurrent mark sweep GC freed 76839(3MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/65MB, paused 2.556ms total 131.915ms
,08-16 14:42:07.135  8465  8465 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
08-16 14:42:07.233   281   332 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-16 14:42:07.233   281   332 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-16 14:42:07.233   281   332 W Vold    : Returning OperationFailed - no handler for errno 0
08-16 14:42:07.233  8489  8510 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,08-16 14:42:07.234   281   332 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-16 14:42:07.234   281   332 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-16 14:42:07.234   281   332 W Vold    : Returning OperationFailed - no handler for errno 0
08-16 14:42:07.235  8489  8510 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,08-16 14:42:07.240   281   332 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-16 14:42:07.240   281   332 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-16 14:42:07.240   281   332 W Vold    : Returning OperationFailed - no handler for errno 0
08-16 14:42:07.240  8489  8514 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-16 14:42:07.243   281   332 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-16 14:42:07.243   281   332 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-16 14:42:07.243   281   332 W Vold    : Returning OperationFailed - no handler for errno 0
08-16 14:42:07.243  8489  8514 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-16 14:42:07.437  8489  8489 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-16 14:42:07.443  8489  8489 I LibraryLoader: Loading: webviewchromium
08-16 14:42:07.445  8489  8489 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 4622-4625)
08-16 14:42:07.445  8489  8489 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-16 14:42:07.449  8489  8489 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {13547c1d}
,08-16 14:42:07.451  8489  8489 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-16 14:42:07.451  8489  8489 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-16 14:42:07.463  8489  8489 I BrowserStartupController: Initializing chromium process, renderers=0
,08-16 14:42:07.464  8489  8489 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-16 14:42:07.475  8489  8489 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-16 14:42:07.476  8489  8489 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=39 off=46780 len=2953
08-16 14:42:07.476  8489  8489 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:40 off:229536 len:643667
,08-16 14:42:07.482   325   325 V AudioPolicyService: registerClient() client 0xb558ae60, uid 10093
08-16 14:42:07.483  8489  8537 W AudioManagerAndroid: Requires BLUETOOTH permission
08-16 14:42:07.493  8489  8489 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-16 14:42:07.493  8489  8489 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-16 14:42:07.493  8489  8489 I Adreno-EGL: Build Date: 12/12/14 금
08-16 14:42:07.493  8489  8489 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-16 14:42:07.493  8489  8489 I Adreno-EGL: Remote Branch: 
08-16 14:42:07.493  8489  8489 I Adreno-EGL: Local Patches: 
08-16 14:42:07.493  8489  8489 I Adreno-EGL: Reconstruct Branch: 
,08-16 14:42:07.557  8465  8480 D LgDataFeature: LgDataFeature() Constructor: none
,08-16 14:42:07.557  8465  8480 D LgDataFeature: LgDataFeature() Constructor Done, null
08-16 14:42:07.572  8489  8489 I NSApplication: Starting up...
,08-16 14:42:07.598  1038  1944 I ActivityManager: Killing 7576:com.lge.lifetracker/u0a37 (adj 15): empty #17
,08-16 14:42:07.600  8550  8550 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=32 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-16 14:42:07.643  8550  8550 I dex2oat : dex2oat took 42.421ms (threads: 4)
08-16 14:42:07.643  1038  1890 W libprocessgroup: failed to open /acct/uid_10037/pid_7576/cgroup.procs: No such file or directory
,08-16 14:42:07.654  2178  2178 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
08-16 14:42:07.665  2178  2178 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
08-16 14:42:07.665  2178  2178 D c       : Getting all permits...
08-16 14:42:07.665  2178  2178 D a       : Opening database...
,08-16 14:42:07.665  8465  8480 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-16 14:42:07.665  8465  8480 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-16 14:42:07.665  8465  8480 I Adreno-EGL: Build Date: 12/12/14 금
08-16 14:42:07.665  8465  8480 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-16 14:42:07.665  8465  8480 I Adreno-EGL: Remote Branch: 
08-16 14:42:07.665  8465  8480 I Adreno-EGL: Local Patches: 
08-16 14:42:07.665  8465  8480 I Adreno-EGL: Reconstruct Branch: 
,08-16 14:42:07.667  2178  2178 D a       : Opening database auth.proximity.permit_store...
08-16 14:42:07.668  2178  2178 D a       : Closing database...
,08-16 14:42:07.804  8465  8480 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-16 14:42:07.804  8465  8480 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-16 14:42:07.804  8465  8480 I Adreno-EGL: Build Date: 12/12/14 금
08-16 14:42:07.804  8465  8480 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-16 14:42:07.804  8465  8480 I Adreno-EGL: Remote Branch: 
08-16 14:42:07.804  8465  8480 I Adreno-EGL: Local Patches: 
08-16 14:42:07.804  8465  8480 I Adreno-EGL: Reconstruct Branch: 
,08-16 14:42:07.909  8465  8480 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-16 14:42:07.909  8465  8480 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-16 14:42:07.909  8465  8480 I Adreno-EGL: Build Date: 12/12/14 금
08-16 14:42:07.909  8465  8480 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-16 14:42:07.909  8465  8480 I Adreno-EGL: Remote Branch: 
08-16 14:42:07.909  8465  8480 I Adreno-EGL: Local Patches: 
08-16 14:42:07.909  8465  8480 I Adreno-EGL: Reconstruct Branch: 
,08-16 14:42:07.983  1038  1381 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-53 f=2447 sc=60 link=72 tx=38.8, 0.0, 0.0  rx=35.8 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1822454545] gl rssi=-53 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-16 14:42:07.996  1038  1381 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-53 f=2447 sc=60 link=72 tx=38.8, 0.0, 0.0  rx=35.8 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:-1822454532] gl rssi=-53 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-16 14:42:07.997  1038  1381 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-16 14:42:08.225  6608  8314 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
,08-16 14:42:08.225  6608  8314 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,08-16 14:42:08.226  6608  8314 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-16 14:42:08.226  6608  8314 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-16 14:42:08.227  6608  8314 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,08-16 14:42:08.228  6608  8564 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 852, name: OutgoingSocketThread/Sender)
08-16 14:42:08.228  6608  8562 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
08-16 14:42:08.229  6608  8562 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
08-16 14:42:08.229  6608  8562 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-16 14:42:08.229  6608  8565 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 853, name: OutgoingSocketThread/Receiver)
08-16 14:42:08.230  6608  8565 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 853, thread name: OutgoingSocketThread/Receiver)
08-16 14:42:08.230  6608  8565 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
08-16 14:42:08.230  6608  8565 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 853, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
08-16 14:42:08.230  6608  8562 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-16 14:42:08.231  6608  8562 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
08-16 14:42:08.232  6608  8567 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 855, name: IncomingSocketThread/Receiver)
08-16 14:42:08.232  6608  8567 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 855, thread name: IncomingSocketThread/Receiver)
08-16 14:42:08.232  6608  8567 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
08-16 14:42:08.232  6608  8567 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 855, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
08-16 14:42:08.233  6608  8566 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 854, name: IncomingSocketThread/Sender)
08-16 14:42:08.236   321  8569 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-16 14:42:08.236   321  8569 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
,08-16 14:42:08.269   321  8569 D libc-netbsd: res_queryN name = android.clients.google.com succeed
,08-16 14:42:08.504  1803  8421 I CheckinTask: Sending checkin request (7894 bytes)
,08-16 14:42:08.767  2178  2195 I art     : Explicit concurrent mark sweep GC freed 7178(470KB) AllocSpace objects, 4(64KB) LOS objects, 52% free, 29MB/61MB, paused 1.722ms total 38.673ms
,08-16 14:42:08.784  1803  8421 I CheckinTask: Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,08-16 14:42:08.798  1803  8421 I CheckinService: active receiver: disabled
,08-16 14:42:08.823  2178  2178 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,08-16 14:42:08.853  2178  2178 I GCM     : GCM config loaded
,08-16 14:42:08.868   321  8580 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-16 14:42:08.868   321  8580 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
08-16 14:42:08.869   321  8580 D libc-netbsd: res_queryN name = mtalk.google.com succeed
08-16 14:42:08.881  8365  8365 V SetupWizard: Connected to Gservices successfully
,08-16 14:42:09.162  2178  8589 D GCM     : Connected
,08-16 14:42:09.184  2178  8589 D GCM     : Message class com.google.e.a.a.q
,08-16 14:42:11.019  1038  1381 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-55 f=2447 sc=60 link=72 tx=29.4, 0.0, 0.0  rx=25.4 bcn=0 [on:0 tx:0 rx:0 period:3007] from screen [on:0 period:-1822451509] gl rssi=-55 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-16 14:42:11.032  1038  1381 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-55 f=2447 sc=60 link=72 tx=29.4, 0.0, 0.0  rx=25.4 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:-1822451496] gl rssi=-55 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-16 14:42:11.032  1038  1381 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-16 14:42:11.227  6608  6679 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
08-16 14:42:11.228  6608  6679 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-16 14:42:11.235  6608  6679 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@10847e5c Bundle[{}]
08-16 14:42:11.236  6608  6679 I io.jxcore.node.LifeCycleMonitor: start: OK
08-16 14:42:11.236  6608  6679 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-16 14:42:11.237  6608  6679 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-16 14:42:11.237  6608  6679 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-16 14:42:11.238  6608  6679 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-16 14:42:11.239  6608  6679 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-16 14:42:11.246  6608  6679 I System.out: Running OutgoingSocketThread
,08-16 14:42:11.251  6608  8596 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
,08-16 14:42:11.251  6608  8596 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-16 14:42:11.556  1038  1381 E WifiStateMachine:  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,08-16 14:42:11.557  1038  1381 E WifiStateMachine:  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
08-16 14:42:11.559  1038  1381 E WifiStateMachine:  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,08-16 14:42:11.572  1038  1381 E WifiStateMachine:  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,08-16 14:42:11.573  1038  1381 E WifiStateMachine:  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
08-16 14:42:11.573  1038  1381 E WifiStateMachine:  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
08-16 14:42:12.249  8489  8512 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,08-16 14:42:13.236  1038  1562 I ActivityManager: Killing 7618:com.lge.settings.easy/1000 (adj 15): empty #17
,08-16 14:42:13.273  1038  1053 W libprocessgroup: failed to open /acct/uid_1000/pid_7618/cgroup.procs: No such file or directory
,08-16 14:42:14.051  1038  1381 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-54 f=2447 sc=60 link=72 tx=28.7, 0.0, 0.0  rx=23.7 bcn=0 [on:0 tx:0 rx:0 period:3006] from screen [on:0 period:-1822448477] gl rssi=-54 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-16 14:42:14.054  1038  1381 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-54 f=2447 sc=60 link=72 tx=28.7, 0.0, 0.0  rx=23.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1822448474] gl rssi=-54 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-16 14:42:14.054  1038  1381 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-16 14:42:14.263  6608  8596 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
08-16 14:42:14.263  6608  8596 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
08-16 14:42:14.263  6608  8596 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-16 14:42:14.263  6608  8596 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-16 14:42:14.263  6608  8596 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,08-16 14:42:14.268  6608  8599 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
08-16 14:42:14.268  6608  8599 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
08-16 14:42:14.268  6608  8599 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-16 14:42:14.268  6608  8599 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-16 14:42:14.269  6608  8599 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
08-16 14:42:14.271  6608  8602 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 865, name: OutgoingSocketThread/Receiver)
08-16 14:42:14.271  6608  8602 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 865, thread name: OutgoingSocketThread/Receiver)
08-16 14:42:14.271  6608  8602 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
08-16 14:42:14.271  6608  8602 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 865, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
08-16 14:42:14.274  6608  8601 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 864, name: OutgoingSocketThread/Sender)
08-16 14:42:14.275  6608  8603 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 866, name: IncomingSocketThread/Sender)
08-16 14:42:14.276  6608  8604 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 867, name: IncomingSocketThread/Receiver)
08-16 14:42:14.277  6608  8604 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 867, thread name: IncomingSocketThread/Receiver)
08-16 14:42:14.277  6608  8604 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
08-16 14:42:14.277  6608  8604 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 867, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,08-16 14:42:16.389  1589  1589 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,08-16 14:42:16.441  1038  1367 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-16 14:42:16.476  1038  1109 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=8605 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-16 14:42:16.487  1589  1589 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
08-16 14:42:16.487  1589  1589 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
08-16 14:42:16.501  2020  2020 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-16 14:42:16.529  1038  1038 D administrator: Handling package changes for user 0
,08-16 14:42:16.534  2020  2020 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-16 14:42:16.575  8605  8605 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-16 14:42:16.646  1038  1038 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
08-16 14:42:16.646  1038  1038 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-16 14:42:16.660  8605  8605 D LgDataFeature: LgDataFeature() Constructor: none
08-16 14:42:16.660  8605  8605 D LgDataFeature: LgDataFeature() Constructor Done, null
08-16 14:42:16.682  1038  1107 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-16 14:42:16.691  1038  1107 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-16 14:42:16.704  2020  2020 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-16 14:42:16.706  2494  2494 V GmsNetworkLocationProvi: DISABLE
,08-16 14:42:16.752  8605  8649 I Babel   : MmsConfig: mnc/mcc: 0/0
08-16 14:42:16.752  8605  8649 I Babel   : MmsConfig.loadMmsSettings
08-16 14:42:16.754  2494  2494 E GCoreFlp: Bound FusedProviderService with LocationManager
08-16 14:42:16.760  8605  8649 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-16 14:42:16.760  8605  8649 I Babel   : MmsConfig.loadFromDatabase
,08-16 14:42:16.782  8605  8649 E Babel   : canonicalizeMccMnc: invalid mccmnc 
08-16 14:42:16.782  8605  8649 I Babel   : MmsConfig.loadFromResources
08-16 14:42:16.784  8605  8649 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
08-16 14:42:16.784  8605  8649 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
,08-16 14:42:16.793  8605  8647 W AudioCapabilities: Unsupported mime audio/evrc
08-16 14:42:16.800  8605  8647 W AudioCapabilities: Unsupported mime audio/qcelp
08-16 14:42:16.802  8605  8605 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 14:42:16.811  8605  8647 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
08-16 14:42:16.820  8605  8647 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
08-16 14:42:16.821  8605  8647 W AudioCapabilities: Unsupported mime audio/qcelp
08-16 14:42:16.823  8605  8647 W AudioCapabilities: Unsupported mime audio/evrc
,08-16 14:42:16.827  1803  8652 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
08-16 14:42:16.827  1803  8652 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
08-16 14:42:16.831  7047  7047 I AppUp4:CustModeStarterReceiver: onReceive
,08-16 14:42:16.837  7047  7047 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2701228a
08-16 14:42:16.837  7047  7047 D AppUp4:CustFacade: isCustomizationCompleted : false
08-16 14:42:16.837  7047  7047 D AppUp4:CustFacade: isPhone : true
08-16 14:42:16.837  7047  7047 D AppUp4:CustModeStarterReceiver: begin check event
08-16 14:42:16.837  7047  7047 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
08-16 14:42:16.837  1803  4710 I Icing   : updateResources: need to parse e{com.google.android.gms}
08-16 14:42:16.842  8605  8647 W VideoCapabilities: Unsupported mime video/x-ms-wmv
08-16 14:42:16.844  8605  8647 W VideoCapabilities: Unsupported mime video/divx
08-16 14:42:16.847  8605  8647 W VideoCapabilities: Unsupported mime video/divx311
08-16 14:42:16.850  8605  8647 W VideoCapabilities: Unsupported mime video/divx4
,08-16 14:42:16.855  8605  8647 W VideoCapabilities: Unsupported mime video/mp4v-esdp
08-16 14:42:16.867  1038  1054 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=8655 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,08-16 14:42:16.871  1038  1982 I ActivityManager: Killing 8190:com.lge.bnr/1000 (adj 15): empty #17
08-16 14:42:16.889  8605  8647 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-16 14:42:16.892  8605  8647 W AudioCapabilities: Unsupported mime audio/eac3
08-16 14:42:16.892  8605  8647 W AudioCapabilities: Unsupported mime audio/ac3
08-16 14:42:16.893  8605  8647 W AudioCapabilities: Unsupported mime audio/g726
08-16 14:42:16.894  8605  8647 W AudioCapabilities: Unsupported mime audio/wma-voice
08-16 14:42:16.894  8605  8647 W AudioCapabilities: Unsupported mime audio/x-ms-wma
08-16 14:42:16.895  8605  8647 W AudioCapabilities: Unsupported mime audio/adpcm
08-16 14:42:16.896  8605  8647 W VideoCapabilities: Unsupported mime video/theora
08-16 14:42:16.897  8605  8647 W VideoCapabilities: Unsupported mime video/mjpg
08-16 14:42:17.002  1038  1944 W libprocessgroup: failed to open /acct/uid_1000/pid_8190/cgroup.procs: No such file or directory
08-16 14:42:17.005  1038  1107 D LocationProviderProxy: applying state to connected service
,08-16 14:42:17.045  8655  8655 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 14:42:17.045  8655  8655 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-16 14:42:17.045  8655  8655 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,08-16 14:42:17.046  8655  8655 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
08-16 14:42:17.046  8655  8655 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-16 14:42:17.087  1038  1381 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-55 f=2447 sc=60 link=72 tx=14.8, 0.0, 0.0  rx=11.8 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1822445441] gl rssi=-55 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-16 14:42:17.090  1038  1381 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-55 f=2447 sc=60 link=72 tx=14.8, 0.0, 0.0  rx=11.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1822445438] gl rssi=-55 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-16 14:42:17.090  1038  1381 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-16 14:42:17.096  8655  8655 I SystemConfig: BUILD Country: EU
08-16 14:42:17.096  8655  8655 I SystemConfig: BUILD Operator: OPEN
08-16 14:42:17.132  1038  1053 I ActivityManager: Killing 8163:com.lge.sync/1000 (adj 15): empty #17
,08-16 14:42:17.247  1038  1982 W libprocessgroup: failed to open /acct/uid_1000/pid_8163/cgroup.procs: No such file or directory
,08-16 14:42:17.266  6608  6679 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 876)
,08-16 14:42:17.268  6608  6679 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,08-16 14:42:17.268  6608  6679 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 877)
08-16 14:42:17.274  6608  6679 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 14:42:17.274  6608  6679 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@302d6280 added. We now have 3 listener(s)
08-16 14:42:17.335  1038  1053 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=8676 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,08-16 14:42:17.337  1038  1562 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 14:42:17.342  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-16 14:42:17.342  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 14:42:17.342  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 14:42:17.343  6608  6679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 14:42:17.343  6608  6679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@65620b9 added. We now have 4 listener(s)
08-16 14:42:17.343  6608  6679 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 14:42:17.343  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 14:42:17.343  8655  8674 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
08-16 14:42:17.343  8655  8674 I SystemConfig: existFile = false
08-16 14:42:17.344  8655  8674 I SystemConfig: canReadFile = false
08-16 14:42:17.344  8655  8674 I SystemConfig: systemFeature RCS result false
08-16 14:42:17.344  8655  8674 D SystemConfig: refreshRcsSupport() :false
08-16 14:42:17.347  6608  6679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 14:42:17.354  6608  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 14:42:17.354  6608  6679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:42:17.354  6608  6679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 14:42:17.354  6608  6679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 14:42:17.354  6608  6679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 14:42:17.354  6608  6679 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 14:42:17.354  6608  6679 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 14:42:17.354  6608  6679 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 14:42:17.356  6608  6679 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 14:42:17.356  6608  6679 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 14:42:17.356  6608  6679 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 14:42:17.356  6608  6679 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 14:42:17.357  6608  6679 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 14:42:17.357  6608  6679 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:42:17.357  6608  6679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:42:17.357  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 14:42:17.357  6608  6679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.,BluetoothConnector: shutdown: Shutting down...
08-16 14:42:17.357  6608  6679 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@302d6280 removed from the list
08-16 14:42:17.357  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:42:17.357  6608  6679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@65620b9 removed from the list
08-16 14:42:17.357  6608  6679 D io.jxcore.node.ConnectivityMonitor: stop
08-16 14:42:17.357  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:42:17.358  6608  6679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:42:17.358  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:42:17.359  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:42:17.359  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 14:42:17.359  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:42:17.359  6608  6679 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@65620b9 not in the list
08-16 14:42:17.359  6608  6679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:42:17.359  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:42:17.361  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 14:42:17.361  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:42:17.361  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:42:17.361  6608  6679 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@65620b9 not in the list
08-16 14:42:17.361  6608  6679 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:42:17.361  6608  6679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:42:17.361  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:42:17.361  6608  6679 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@302d6280 not in the list
08-16 14:42:17.362  6608  6679 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 14:42:17.362  6608  6679 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23f0cc5f added. We now have 3 listener(s)
08-16 14:42:17.362  1038  1981 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 14:42:17.364  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-16 14:42:17.364  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 14:42:17.364  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 14:42:17.365  6608  6679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 14:42:17.365  6608  6679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c4626ac added. We now have 4 listener(s)
08-16 14:42:17.365  6608  6679 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 14:42:17.365  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 14:42:17.365  6608  6608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:42:17.367  6608  6679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 14:42:17.372  6608  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 14:42:17.372  6608  6679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:42:17.372  6608  6679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 14:42:17.372  6608  6679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 14:42:17.372  6608  6679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 14:42:17.372  6608  6679 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 14:42:17.372  6608  6679 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 14:42:17.372  6608  6679 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 14:42:17.374  6608  6679 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 14:42:17.374  6608  6679 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 14:42:17.374  6608  6679 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 14:42:17.374  6608  6679 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 14:42:17.374  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 14:42:17.374  6608  6679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 14:42:17.374  6608  6679 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 14:42:17.378  6608  6608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:42:17.380  6608  6608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:42:17.381  6608  6679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-16 14:42:17.381  1038  1945 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 14:42:17.385  6608  6679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-16 14:42:17.386  6608  6679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-16 14:42:17.388  6608  6679 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 14:42:17.388  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 14:42:17.390  6608  6679 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-16 14:42:17.390  6608  6679 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 14:42:17.390  6608  6679 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 14:42:17.441  8676  8676 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-16 14:42:17.441  8676  8676 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-16 14:42:17.442  8676  8676 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-16 14:42:17.442  8676  8676 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-16 14:42:17.569  8676  8676 I AppConfig: Total System Memory = 2995761152
,08-16 14:42:17.579  8676  8676 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
08-16 14:42:17.682  1038  2037 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=8698 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-16 14:42:17.689  1038  2037 I ActivityManager: Killing 7650:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
08-16 14:42:17.708  7872  7872 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
08-16 14:42:17.708  7872  7872 W System.err: android.os.DeadObjectException
08-16 14:42:17.709  7872  7872 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-16 14:42:17.709  7872  7872 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-16 14:42:17.709  7872  7872 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-16 14:42:17.709  7872  7872 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-16 14:42:17.709  7872  7872 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-16 14:42:17.709  7872  7872 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-16 14:42:17.709  7872  7872 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-16 14:42:17.709  7872  7872 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-16 14:42:17.709  7872  7872 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-16 14:42:17.709  7872  7872 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-16 14:42:17.709  7872  7872 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 14:42:17.709  7872  7872 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 14:42:17.709  7872  7872 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-16 14:42:17.709  7872  7872 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-16 14:42:17.710  7872  7872 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
,08-16 14:42:17.715  7872  7872 W System.err: android.os.DeadObjectException
08-16 14:42:17.716  7872  7872 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-16 14:42:17.716  7872  7872 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-16 14:42:17.716  7872  7872 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-16 14:42:17.716  7872  7872 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-16 14:42:17.716  7872  7872 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-16 14:42:17.716  7872  7872 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-16 14:42:17.716  7872  7872 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-16 14:42:17.716  7872  7872 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-16 14:42:17.716  7872  7872 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-16 14:42:17.716  7872  7872 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-16 14:42:17.716  7872  7872 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 14:42:17.716  7872  7872 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 14:42:17.716  7872  7872 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-16 14:42:17.716  7872  7872 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-16 14:42:17.716  7872  7872 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-16 14:42:17.717  7872  7872 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
08-16 14:42:17.744  1038  1890 W libprocessgroup: failed to open /acct/uid_1000/pid_7650/cgroup.procs: No such file or directory
,08-16 14:42:17.744  1038  1890 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
08-16 14:42:17.753  7872  7872 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-16 14:42:17.754  7872  7872 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-16 14:42:17.803  1038  1909 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=8720 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-16 14:42:17.808  7872  7872 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-16 14:42:17.887  8720  8720 D UEI.SmartControl: Quickset Services start...
08-16 14:42:17.889  8720  8720 I UEI.SmartControl: Manufacture = LGE
08-16 14:42:17.889  8720  8720 D UEI.SmartControl: Id = LGNevo
,08-16 14:42:17.893  8720  8720 D UEI.SmartControl: File observer start...
08-16 14:42:17.894  8720  8720 E UEI.SmartControl: IR Port is disabled: false
08-16 14:42:17.894  8720  8720 D UEI.SmartControl: Starting file observer...
08-16 14:42:17.894  8720  8720 D UEI.SmartControl: Extracting JNI libs...
08-16 14:42:17.895  8720  8720 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
08-16 14:42:17.952  8698  8698 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,08-16 14:42:18.012  8720  8720 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
08-16 14:42:18.012  8720  8720 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-16 14:42:18.012  8720  8720 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,08-16 14:42:18.026  8698  8698 D LgDataFeature: LgDataFeature() Constructor: none
08-16 14:42:18.026  8698  8698 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 14:42:18.050  8720  8720 I UEI.SmartControl: --- Selecting new region: 6
,08-16 14:42:18.052  8720  8720 I UEI.SmartControl: Model = LG-D855
08-16 14:42:18.054  8720  8720 D UEI.SmartControl: QS Service created
08-16 14:42:18.069  8720  8720 I UEI.SmartControl: Service initServices...
,08-16 14:42:18.073  8720  8720 D UEI.SmartControl: QS start get config
,08-16 14:42:18.087  8698  8698 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,08-16 14:42:18.112  8698  8698 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-16 14:42:18.113  8698  8698 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
08-16 14:42:18.114  8720  8720 D UEI.SmartControl: Loading JNI Libs...
,08-16 14:42:18.128  8698  8698 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-16 14:42:18.128  8698  8698 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,08-16 14:42:18.146  1038  1054 I ActivityManager: Killing 6879:com.android.settings/1000 (adj 15): empty #17
,08-16 14:42:18.313  1038  1982 W libprocessgroup: failed to open /acct/uid_1000/pid_6879/cgroup.procs: No such file or directory
,08-16 14:42:18.324  4570  8771 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
08-16 14:42:18.330  3472  6167 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
,08-16 14:42:18.344  8720  8720 I UEI.SmartControl: Supports setup maps: true
08-16 14:42:18.347  8720  8720 D UEI.SmartControl: QS start statue = true Error code = 0
08-16 14:42:18.347  8720  8720 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-16 14:42:18.347  8720  8720 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-16 14:42:18.347  8720  8720 I UEI.SmartControl: ### init IR Blaster...
08-16 14:42:18.350  3472  6167 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@248c66a8 on behalf of 8698
08-16 14:42:18.353  8720  8720 D serial_port: Configuring serial port
08-16 14:42:18.356  8720  8720 E UEI.SmartControl: UEIBLaster setting for 616
08-16 14:42:18.356  8720  8720 I UEI.SmartControl: Setting serial record hearder size = 2
08-16 14:42:18.356  8720  8720 I UEI.SmartControl: configuring settings for MAXQ616
08-16 14:42:18.356  8720  8720 I UEI.SmartControl: Get version...
08-16 14:42:18.368  1038  1908 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=8774 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,08-16 14:42:18.379  8720  8773 D UEI.SmartControl: serial port data available: 21
,08-16 14:42:18.382  8698  8698 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,08-16 14:42:18.412  8720  8720 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-16 14:42:18.412  8720  8720 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-16 14:42:18.412  8720  8720 I UEI.SmartControl: QS saving settings...
,08-16 14:42:18.413  8720  8720 D UEI.SmartControl: IR Blaster version: 25672567
08-16 14:42:18.415  8698  8698 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
08-16 14:42:18.427  8774  8774 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,08-16 14:42:18.429  8720  8773 D UEI.SmartControl: serial port data available: 4
08-16 14:42:18.444  8774  8774 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
08-16 14:42:18.444  8774  8774 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
,08-16 14:42:18.444  8774  8774 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
08-16 14:42:18.444  8774  8774 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
08-16 14:42:18.444  8774  8774 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
08-16 14:42:18.444  8774  8774 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
08-16 14:42:18.457  1038  1909 I ActivityManager: Killing 7872:com.lge.qremote/u0a112 (adj 15): empty #17
,08-16 14:42:18.459  8720  8720 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-16 14:42:18.460  8720  8803 I UEI.SmartControl: Device manager: loading config....
08-16 14:42:18.460  8720  8803 D UEI.SmartControl: ----------- loading internal config...
08-16 14:42:18.465  8720  8803 E UEI.SmartControl: Loading SETTINGS...
08-16 14:42:18.469  8720  8803 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,08-16 14:42:18.479  8720  8802 I UEI.SmartControl: Notify AllClients services are ready: 0
08-16 14:42:18.479  8720  8802 D UEI.SmartControl: -----service ready thread exits
08-16 14:42:18.485  1038  1711 W libprocessgroup: failed to open /acct/uid_10112/pid_7872/cgroup.procs: No such file or directory
,08-16 14:42:18.486  8720  8720 E UEI.SmartControl: Services init done
08-16 14:42:18.486  8720  8720 D UEI.SmartControl: QS Service init finished
08-16 14:42:18.487  8720  8720 D UEI.SmartControl: QS Service version name: 2.1.91
08-16 14:42:18.487  8720  8720 D UEI.SmartControl: QS Service version code: 201091
08-16 14:42:18.488  8720  8720 D UEI.SmartControl: Service requested: Control
08-16 14:42:18.490  1038  1890 I ActivityManager: Killing 8327:com.lge.email/u0a23 (adj 15): empty #17
08-16 14:42:18.559  8720  8720 D UEI.SmartControl: Internal service binding...
,08-16 14:42:18.560  1038  2019 W libprocessgroup: failed to open /acct/uid_10023/pid_8327/cgroup.procs: No such file or directory
,08-16 14:42:18.781  1038  1562 V SIM_STK : Menu title from STK is T-Mobile
,08-16 14:42:18.796  4570  8771 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 471 ms] updated apps [took 471 ms] 
,08-16 14:42:20.111  1038  1381 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-55 f=2447 sc=60 link=72 tx=7.4, 0.0, 0.0  rx=5.9 bcn=0 [on:0 tx:0 rx:0 period:3007] from screen [on:0 period:-1822442417] gl rssi=-55 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-16 14:42:20.114  1038  1381 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-55 f=2447 sc=60 link=72 tx=7.4, 0.0, 0.0  rx=5.9 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1822442414] gl rssi=-55 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-16 14:42:20.114  1038  1381 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-16 14:42:20.391  6608  6679 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 14:42:20.392  6608  6679 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-16 14:42:20.392  6608  6679 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 14:42:20.403  6608  6679 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:42:20.403  6608  6679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:42:20.403  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 14:42:20.403  6608  6679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 14:42:20.404  6608  6679 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23f0cc5f removed from the list
08-16 14:42:20.404  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:42:20.404  6608  6679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c4626ac removed from the list
08-16 14:42:20.404  6608  6679 D io.jxcore.node.ConnectivityMonitor: stop
08-16 14:42:20.404  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:42:20.407  6608  6679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:42:20.407  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:42:20.411  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:42:20.411  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 14:42:20.414  6608  6679 D BluetoothLeScanner: could not find callback wrapper
08-16 14:42:20.414  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 14:42:20.414  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:42:20.414  6608  6679 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c4626ac not in the list
08-16 14:42:20.414  6608  6679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:42:20.414  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 14:42:20.418  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 14:42:20.418  6608  6679 D BluetoothLeScanner: could not find callback wrapper
08-16 14:42:20.418  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 14:42:20.418  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:42:20.418  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:42:20.418  6608  6679 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c4626ac not in the list
08-16 14:42:20.418  6608  6679 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:42:20.418  6608  6679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:42:20.418  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:42:20.419  6608  6679 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23f0cc5f not in the list
08-16 14:42:20.419  6608  6679 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 14:42:20.419  6608  6679 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@14450198 added. We now have 3 listener(s)
08-16 14:42:20.420  1038  1981 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 14:42:20.423  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-16 14:42:20.423  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 14:42:20.423  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 14:42:20.423  6608  6679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 14:42:20.423  6608  6679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b6e2df1 added. We now have 4 listener(s)
08-16 14:42:20.423  6608  6679 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 14:42:20.425  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-16 14:42:20.432  6608  6679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 14:42:20.436  6608  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 14:42:20.436  6608  6679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:42:20.436  6608  6679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 14:42:20.436  6608  6679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 14:42:20.436  6608  6679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 14:42:20.436  6608  6679 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 14:42:20.436  6608  6679 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 14:42:20.436  6608  6679 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 14:42:20.439  6608  6679 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 14:42:20.439  6608  6679 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 14:42:20.443  6608  6608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:42:20.445  6608  6608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:42:20.445  6608  6679 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-16 14:42:20.446  6608  6679 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
08-16 14:42:20.446  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
08-16 14:42:20.449  6608  6679 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-16 14:42:20.449  6608  6679 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
08-16 14:42:20.449  6608  6679 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-16 14:42:20.449  6608  6679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 14:42:20.455  6608  6679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-16 14:42:20.455  6608  6679 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-16 14:42:20.456  6608  6679 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-16 14:42:20.456  6608  6608 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-16 14:42:20.458  6608  6679 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-16 14:42:20.458  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
08-16 14:42:20.458  6608  6679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 14:42:20.458  6608  6679 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 14:42:20.464  6608  6679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-16 14:42:20.467  1038  2019 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 14:42:20.472  6608  6679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-16 14:42:20.472  1038  1054 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 14:42:20.474  6608  6679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-16 14:42:20.475  6608  6679 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-16 14:42:20.478  6608  8815 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 14:42:20.479  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-16 14:42:20.481  7968  7984 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=84 mFd=82
,08-16 14:42:20.482  6608  8815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
08-16 14:42:20.483  6608  6679 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,08-16 14:42:23.139  1038  1381 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-55 f=2447 sc=60 link=72 tx=3.7, 0.0, 0.0  rx=3.0 bcn=0 [on:0 tx:0 rx:0 period:3006] from screen [on:0 period:-1822439389] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0,
,08-16 14:42:23.153  1038  1381 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-55 f=2447 sc=60 link=72 tx=3.7, 0.0, 0.0  rx=3.0 bcn=0 [on:0 tx:0 rx:0 period:14] from screen [on:0 period:-1822439375] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-16 14:42:23.154  1038  1381 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-16 14:42:23.459  8720  8804 D UEI.SmartControl: Internal timer expired: 1
08-16 14:42:23.459  8720  8804 D UEI.SmartControl: unbind internal service
,08-16 14:42:23.468  8720  8720 D UEI.SmartControl: Service.onUnbind: IControl
08-16 14:42:23.469  8720  8720 D UEI.SmartControl: Service.onDestroy
08-16 14:42:23.469  8720  8720 D UEI.SmartControl: Lock is in USE false
08-16 14:42:23.469  8720  8720 D UEI.SmartControl: unbind internal service
08-16 14:42:23.469  8720  8720 W System.err: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@18d6dd56
08-16 14:42:23.469  8720  8720 W System.err: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
08-16 14:42:23.470  8720  8720 W System.err: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
08-16 14:42:23.470  8720  8720 W System.err: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
08-16 14:42:23.470  8720  8720 W System.err: 	at com.uei.control.Service.c(Unknown Source)
08-16 14:42:23.470  8720  8720 W System.err: 	at com.uei.control.Service.onDestroy(Unknown Source)
08-16 14:42:23.470  8720  8720 W System.err: 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
08-16 14:42:23.470  8720  8720 W System.err: 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
08-16 14:42:23.471  8720  8720 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
08-16 14:42:23.471  8720  8720 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 14:42:23.471  8720  8720 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-16 14:42:23.471  8720  8720 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-16 14:42:23.471  8720  8720 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 14:42:23.471  8720  8720 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 14:42:23.471  8720  8720 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-16 14:42:23.471  8720  8720 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-16 14:42:23.471  8720  8720 E UEI.SmartControl: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@18d6dd56
08-16 14:42:23.473  8720  8720 D serial_port: close(fd = 25)
,08-16 14:42:23.481  8720  8720 I UEI.SmartControl: Serial port is closed.
08-16 14:42:23.481  8720  8720 I UEI.SmartControl: Serial port is closed.
08-16 14:42:23.481  8720  8720 D UEI.SmartControl: Blaster closed
08-16 14:42:23.481  8720  8720 D UEI.SmartControl: Shut down QS...
08-16 14:42:23.481  8720  8720 D UEI.SmartControl: Stopping QS lib
08-16 14:42:23.481  8720  8720 D UEI.SmartControl: QS lib stop result = true
08-16 14:42:23.481  8720  8720 D UEI.SmartControl: Stopped QS lib
08-16 14:42:23.482  8720  8720 D UEI.SmartControl: Stopped file observer...
08-16 14:42:23.482  8720  8720 D UEI.SmartControl: QS shutdown complete
08-16 14:42:23.485  6608  6679 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 14:42:23.485  6608  6679 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 14:42:23.486  6608  6679 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-16 14:42:23.486  6608  6679 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-16 14:42:23.486  6608  6679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-16 14:42:23.486  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,08-16 14:42:23.489  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 14:42:23.489  6608  6679 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-16 14:42:23.491  6608  6608 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-16 14:42:23.491  6608  6679 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-16 14:42:23.491  6608  6679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:42:23.491  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 14:42:23.491  6608  8815 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-16 14:42:23.492  6608  8815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-16 14:42:23.492  6608  8815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-16 14:42:23.495  6608  6608 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 14:42:23.495  6608  6608 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-16 14:42:23.495  6608  6608 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-16 14:42:23.495  6608  6679 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:42:23.495  6608  6679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:42:23.495  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 14:42:23.495  6608  6679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 14:42:23.495  6608  6679 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@14450198 removed from the list
08-16 14:42:23.495  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:42:23.495  6608  6679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b6e2df1 removed from the list
08-16 14:42:23.495  6608  6679 D io.jxcore.node.ConnectivityMonitor: stop
08-16 14:42:23.495  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:42:23.496  6608  6679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:42:23.496  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:42:23.497  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:42:23.497  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 14:42:23.498  6608  6679 D BluetoothLeScanner: could not find callback wrapper
08-16 14:42:23.498  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 14:42:23.498  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:42:23.498  6608  6679 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b6e2df1 not in the list
08-16 14:42:23.498  6608  6679 W org.thalipr,oject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:42:23.498  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 14:42:23.504  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 14:42:23.506  6608  6679 D BluetoothLeScanner: could not find callback wrapper
08-16 14:42:23.506  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 14:42:23.506  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:42:23.506  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:42:23.506  6608  6679 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b6e2df1 not in the list
08-16 14:42:23.506  6608  6679 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:42:23.506  6608  6679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:42:23.506  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:42:23.506  6608  6679 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@14450198 not in the list
08-16 14:42:23.507  6608  6679 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 14:42:23.507  6608  6679 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1326b82d added. We now have 3 listener(s)
08-16 14:42:23.511  1038  1946 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-16 14:42:23.516  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-16 14:42:23.516  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 14:42:23.516  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 14:42:23.516  6608  6679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 14:42:23.516  6608  6679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13685162 added. We now have 4 listener(s)
08-16 14:42:23.516  6608  6679 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 14:42:23.518  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 14:42:23.521  6608  6679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 14:42:23.525  6608  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 14:42:23.525  6608  6679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:42:23.525  6608  6679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 14:42:23.525  6608  6679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 14:42:23.525  6608  6679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 14:42:23.525  6608  6679 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 14:42:23.525  6608  6679 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 14:42:23.525  6608  6679 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 14:42:23.529  6608  6679 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 14:42:23.529  6608  6679 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 14:42:23.532  6608  6608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:42:23.534  6608  6608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:42:23.534  6608  6679 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 14:42:23.534  6608  6679 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 14:42:23.535  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 14:42:23.535  6608  6679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 14:42:23.535  6608  6679 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 14:42:23.538  6608  6679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-16 14:42:23.541  1038  1588 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 14:42:23.546  6608  6679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-16 14:42:23.547  6608  6679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-16 14:42:23.548  6608  6679 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 14:42:23.549  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 14:42:23.551  6608  6679 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,08-16 14:42:25.406  1038  1053 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 102]) by 10005
,08-16 14:42:25.409  1038  8228 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-3ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
,08-16 14:42:25.409  1038  8228 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-3ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:42:25.409  1038  8228 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-16 14:42:25.409  1038  8228 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:42:25.410  1038  8228 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-16 14:42:26.172  1038  1381 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-55 f=2447 sc=60 link=72 tx=1.9, 0.0, 0.0  rx=1.5 bcn=0 [on:0 tx:0 rx:0 period:3006] from screen [on:0 period:-1822436356] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-16 14:42:26.175  1038  1381 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-55 f=2447 sc=60 link=72 tx=1.9, 0.0, 0.0  rx=1.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1822436353] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-16 14:42:26.176  1038  1381 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-16 14:42:26.559  6608  6679 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 14:42:26.559  6608  6679 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-16 14:42:26.559  6608  6679 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 14:42:26.571  6608  6679 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:42:26.571  6608  6679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:42:26.571  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 14:42:26.571  6608  6679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 14:42:26.571  6608  6679 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1326b82d removed from the list
08-16 14:42:26.571  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:42:26.571  6608  6679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13685162 removed from the list
08-16 14:42:26.571  6608  6679 D io.jxcore.node.ConnectivityMonitor: stop
08-16 14:42:26.572  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:42:26.573  6608  6679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:42:26.573  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:42:26.574  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:42:26.574  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 14:42:26.574  6608  6679 D BluetoothLeScanner: could not find callback wrapper
08-16 14:42:26.574  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 14:42:26.574  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:42:26.575  6608  6679 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13685162 not in the list
08-16 14:42:26.575  6608  6679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:42:26.575  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:42:26.576  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 14:42:26.576  6608  6679 D BluetoothLeScanner: could not find callback wrapper
08-16 14:42:26.576  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 14:42:26.576  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:42:26.576  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:42:26.576  6608  6679 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13685162 not in the list
08-16 14:42:26.576  6608  6679 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:42:26.576  6608  6679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:42:26.577  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:42:26.577  6608  6679 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1326b82d not in the list
08-16 14:42:26.580  6608  6679 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 14:42:26.580  660,8  6679 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24fe21ae added. We now have 3 listener(s)
,08-16 14:42:26.584  1038  1908 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-16 14:42:26.587  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-16 14:42:26.587  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 14:42:26.587  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 14:42:26.587  6608  6679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 14:42:26.588  6608  6679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@290b8b4f added. We now have 4 listener(s)
08-16 14:42:26.588  6608  6679 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 14:42:26.589  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 14:42:26.593  6608  6679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 14:42:26.601  6608  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 14:42:26.601  6608  6679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:42:26.601  6608  6679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 14:42:26.601  6608  6679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 14:42:26.601  6608  6679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 14:42:26.601  6608  6679 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 14:42:26.601  6608  6679 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 14:42:26.601  6608  6679 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 14:42:26.602  6608  6679 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 14:42:26.602  6608  6679 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 14:42:26.604  6608  6608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:42:26.606  6608  6608 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 14:42:26.611  6608  6679 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 14:42:26.611  6608  6679 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-16 14:42:26.611  6608  6679 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 14:42:26.612  6608  6679 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:42:26.612  6608  6679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:42:26.612  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 14:42:26.612  6608  6679 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 14:42:26.612  6608  6679 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24fe21ae removed from the list
08-16 14:42:26.612  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:42:26.612  6608  6679 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@290b8b4f removed from the list
08-16 14:42:26.612  6608  6679 D io.jxcore.node.ConnectivityMonitor: stop
08-16 14:42:26.612  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:42:26.613  6608  6679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:42:26.613  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 14:42:26.614  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:42:26.614  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
08-16 14:42:26.614  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:42:26.614  6608  6679 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@290b8b4f not in the list
08-16 14:42:26.614  6608  6679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:42:26.614  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
08-16 14:42:26.615  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 14:42:26.615  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:42:26.615  6608  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:42:26.615  6608  6679 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@290b8b4f not in the list
,08-16 14:42:26.615  6608  6679 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:42:26.615  6608  6679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:42:26.615  6608  6679 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:42:26.615  6608  6679 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24fe21ae not in the list,
08-16 14:42:26.617  6608  6679 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-16 14:42:26.617  6608  6679 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-16 14:42:26.617  6608  6679 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-16 14:42:26.617  6608  6679 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only,
08-16 14:42:26.617  6608  6679 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only,
08-16 14:42:26.618  6608  6679 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-16 14:42:26.644  1038  1365 D PowerManagerServiceEx: acquireWakeLockInternal: lock=448744860, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1038
,08-16 14:42:26.665  1038  1365 V AlarmManager: ELAPSED_WAKEUP set : Alarm{cbacde9 type 2 when 223811 com.google.android.gms} when 223811
,08-16 14:42:26.676   321  8817 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,08-16 14:42:26.676   321  8817 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
08-16 14:42:26.677   321  8817 D libc-netbsd: res_queryN name = mtalk.google.com succeed
08-16 14:42:26.703  2559  2559 D [Concierge]Service: onStartCommand(). Type : 9
,08-16 14:42:26.733  1038  1038 D PowerManagerServiceEx: releaseWakeLockInternal: lock=448744860 [*alarm*], flags=0x0
,08-16 14:42:27.965  2178  8818 D GCM     : Connected
,08-16 14:42:27.998  2178  8818 D GCM     : Message class com.google.e.a.a.q
,08-16 14:42:28.639  6608  8819 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 886, name: My test thread name)
,08-16 14:42:28.892  1038  8228 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 16 Aug 2016 12:42:28 GMT], X-Android-Received-Millis=[1471351348889], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1471351345419]}
,08-16 14:42:28.892  1038  8228 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
,08-16 14:42:28.892  1038  8228 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
,08-16 14:42:28.901  1038  1448 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
,08-16 14:42:28.902  1038  1448 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
,08-16 14:42:28.902  1038  1448 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 14:42:28.902  1038  1448 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
,08-16 14:42:28.902  1038  1448 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
,08-16 14:42:28.903  1038  1448 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
08-16 14:42:28.903  1038  1448 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-16 14:42:28.903  1038  1448 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 14:42:28.903  1038  1448 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 14:42:28.903  1038  1448 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 14:42:28.904  1589  1837 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-16 14:42:29.193  1038  1381 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-55 f=2447 sc=60 link=72 tx=4.4, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1822433335] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-16 14:42:29.196  1038  1381 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-55 f=2447 sc=60 link=72 tx=4.4, 0.0, 0.0  rx=0.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1822433332] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-16 14:42:29.196  1038  1381 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-16 14:42:30.637  6608  6679 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 886
,08-16 14:42:30.637  6608  6679 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 886, name: My test thread name)
,08-16 14:42:30.655  6608  8820 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 887, name: My test thread name)
08-16 14:42:30.655  6608  8820 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 887, thread name: My test thread name)
08-16 14:42:30.655  6608  8820 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 887, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
08-16 14:42:30.659  6608  6679 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-16 14:42:30.670  6608  8821 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 891, name: My test thread name)
,08-16 14:42:30.671  6608  8821 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 891, thread name: My test thread name): Test exception.
08-16 14:42:30.671  6608  8821 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 891, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
08-16 14:42:30.674  6608  6679 I jxcore-log: Total number of executed tests:  82
08-16 14:42:30.674  6608  6679 I jxcore-log: 
08-16 14:42:30.675  6608  6679 I jxcore-log: Number of passed tests:  82
08-16 14:42:30.675  6608  6679 I jxcore-log: 
08-16 14:42:30.675  6608  6679 I jxcore-log: Number of failed tests:  0
08-16 14:42:30.675  6608  6679 I jxcore-log: 
08-16 14:42:30.675  6608  6679 I jxcore-log: Number of ignored tests:  0
08-16 14:42:30.675  6608  6679 I jxcore-log: 
,08-16 14:42:30.680  6608  6679 I jxcore-log: Total duration:  96954
08-16 14:42:30.680  6608  6679 I jxcore-log: 
08-16 14:42:30.680  6608  6679 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-16 14:42:30.680  6608  6679 I jxcore-log: 
08-16 14:42:30.692  6608  6679 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 14:42:30.692  6608  6679 I jxcore-log: 
08-16 14:42:30.695  6608  6679 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 14:42:30.695  6608  6679 I jxcore-log: 
08-16 14:42:30.697  6608  6679 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 14:42:30.697  6608  6679 I jxcore-log: 
08-16 14:42:30.698  6608  6679 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 14:42:30.698  6608  6679 I jxcore-log: 
08-16 14:42:30.699  6608  6679 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 14:42:30.699  6608  6679 I jxcore-log: 
,08-16 14:42:30.715  6608  8819 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 886, name: My test thread name), during the lifetime of the thread the total number of bytes read was 154 and the total number of bytes written 154
,08-16 14:42:30.720  6608  6608 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
08-16 14:42:30.719  6608  6679 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 14:42:30.719  6608  6679 I jxcore-log: 
08-16 14:42:30.724  6608  6679 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-16 14:42:30.724  6608  6679 I jxcore-log: 
08-16 14:42:30.726  6608  6679 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 14:42:30.726  6608  6679 I jxcore-log: 
08-16 14:42:30.727  6608  6679 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 14:42:30.727  6608  6679 I jxcore-log: 
08-16 14:42:30.728  6608  6679 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 14:42:30.728  6608  6679 I jxcore-log: 
08-16 14:42:30.728  6608  6679 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 14:42:30.728  6608  6679 I jxcore-log: 
08-16 14:42:30.729  6608  6679 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 14:42:30.729  6608  6679 I jxcore-log: 
08-16 14:42:30.734  6608  6679 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 14:42:30.734  6608  6679 I jxcore-log: 
08-16 14:42:30.735  6608  6679 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 14:42:30.735  6608  6679 I jxcore-log: 
08-16 14:42:30.735  6608  6679 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 14:42:30.735  6608  6679 I jxcore-log: 
08-16 14:42:30.736  6608  6679 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 14:42:30.736  6608  6679 I jxcore-log: 
08-16 14:42:30.737  6608  6679 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 14:42:30.737  6608  6679 I jxcore-log: 
08-16 14:42:30.738  6608  6679 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 14:42:30.738  6608  6679 I jxcore-log: 
08-16 14:42:30.738  6608  6679 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 14:42:30.738  6608  6679 I jxcore-log: 
08-16 14:42:30.739  6608  6679 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 14:42:30.739  6608  6679 I jxcore-log: 
,08-16 14:42:30.744  6608  6679 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 14:42:30.744  6608  6679 I jxcore-log: 
08-16 14:42:30.745  6608  6679 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 14:42:30.745  6608  6679 I jxcore-log: 
08-16 14:42:30.746  6608  6679 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 14:42:30.746  6608  6679 I jxcore-log: 
,08-16 14:42:30.746  6608  6679 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 14:42:30.746  6608  6679 I jxcore-log: 
08-16 14:42:30.747  6608  6679 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 14:42:30.747  6608  6679 I jxcore-log: 
08-16 14:42:30.748  6608  6679 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 14:42:30.748  6608  6679 I jxcore-log: 
08-16 14:42:30.749  6608  6679 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 14:42:30.749  6608  6679 I jxcore-log: 
08-16 14:42:30.749  6608  6679 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 14:42:30.749  6608  6679 I jxcore-log: 
08-16 14:42:30.750  6608  6679 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 14:42:30.750  6608  6679 I jxcore-log: 
08-16 14:42:30.751  6608  6679 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 14:42:30.751  6608  6679 I jxcore-log: 
08-16 14:42:30.752  6608  6679 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 14:42:30.752  6608  6679 I jxcore-log: 
08-16 14:42:30.753  6608  6679 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-16 14:42:30.753  6608  6679 I jxcore-log: 
08-16 14:42:30.753  6608  6679 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-16 14:42:30.753  6608  6679 I jxcore-log: 
08-16 14:42:30.754  6608  6679 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 14:42:30.754  6608  6679 I jxcore-log: 
08-16 14:42:30.755  6608  6679 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 14:42:30.755  6608  6679 I jxcore-log: 
08-16 14:42:30.756  6608  6679 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 14:42:30.756  6608  6679 I jxcore-log: 
08-16 14:42:30.757  6608  6679 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 14:42:30.757  6608  6679 I jxcore-log: 
08-16 14:42:30.757  6608  6679 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 14:42:30.757  6608  6679 I jxcore-log: 
08-16 14:42:30.758  6608  6679 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 14:42:30.758  6608  6679 I jxcore-log: 
08-16 14:42:30.759  6608  6679 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 14:42:30.759  6608  6679 I jxcore-log: 
08-16 14:42:30.760 , 6608  6679 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 14:42:30.760  6608  6679 I jxcore-log: 
08-16 14:42:31.027  8822  8822 D AndroidRuntime: 
08-16 14:42:31.027  8822  8822 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-16 14:42:31.038  8822  8822 D AndroidRuntime: CheckJNI is OFF
08-16 14:42:31.249  8822  8822 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-16 14:42:31.268  1038  1109 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
,08-16 14:42:31.269  1038  1109 I ActivityManager: Killing 6608:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
,08-16 14:42:31.339  1038  1981 I WindowState: WIN DEATH: Window{13cf344f u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-16 14:42:31.349  1038  1431 D WifiService: Client connection lost with reason: 4
08-16 14:42:31.365  1038  1981 D InputDispatcher: Window went away: Window{13cf344f u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-16 14:42:31.487  1038  1109 E libprocessgroup: failed to kill 1 processes for processgroup 6608
,08-16 14:42:31.493  1038  1109 I ActivityManager:   Force finishing activity ActivityRecord{1c95f368 u0 com.test.thalitest/.MainActivity t6}
,08-16 14:42:31.537   347   365 E GBMv2   : DFP En is all cleared set to be enabled
,08-16 14:42:31.543  1038  1982 W ActivityManager: Spurious death for ProcessRecord{17cda6e 6608:com.test.thalitest/u0a118}, curProc for 6608: null
08-16 14:42:31.544  1038  1126 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
08-16 14:42:31.548  1038  1126 I ActivityManager:   Force finishing activity ActivityRecord{1c95f368 u0 com.test.thalitest/.MainActivity t6 f}
08-16 14:42:31.548  1038  1126 W ActivityManager: Duplicate finish request for ActivityRecord{1c95f368 u0 com.test.thalitest/.MainActivity t6 f}
,08-16 14:42:31.572  2020  2020 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
,08-16 14:42:31.572  1927  1942 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
08-16 14:42:31.573  1927  1942 D SplitWindowPolicy: topRunningActivity=ActivityInfo{2caa4867 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-16 14:42:31.574  2020  2020 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
08-16 14:42:31.574  1927  2661 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
08-16 14:42:31.574  1927  2661 D SplitWindowPolicy: topRunningActivity=ActivityInfo{d3a6614 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
,08-16 14:42:31.575  2020  2020 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
08-16 14:42:31.576  2020  2110 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
08-16 14:42:31.578  1589  1589 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
08-16 14:42:31.582  1038  1367 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-16 14:42:31.587  2494  2670 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-16 14:42:31.588  2689  2689 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
08-16 14:42:31.589  1983  1983 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-16 14:42:31.591  7968  7968 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
08-16 14:42:31.591  7968  7968 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-16 14:42:31.593  1038  1107 W InputMethodInfo: Duplicated subtype definition found: , voice
,08-16 14:42:31.601  4457  4457 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-16 14:42:31.602  4457  4457 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-16 14:42:31.602  4457  4457 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-16 14:42:31.602  4457  4457 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-16 14:42:31.602  4457  4457 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-16 14:42:31.602  4457  4457 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-16 14:42:31.602  4457  4457 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-16 14:42:31.602  4457  4457 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-16 14:42:31.602  4457  4457 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 14:42:31.603  4457  4457 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 14:42:31.603  4457  4457 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-16 14:42:31.603  4457  4457 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-16 14:42:31.620  4570  4570 I art     : Explicit concurrent mark sweep GC freed 15417(885KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 29MB/45MB, paused 583us total 66.650ms
,08-16 14:42:31.642  1038  2037 V SIM_STK : Menu title from STK is T-Mobile
,08-16 14:42:31.654  8211  8211 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-16 14:42:31.672  1803  1803 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
,08-16 14:42:31.673  2020  2020 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
08-16 14:42:31.673  1891  1891 D ActionManagerService: notifyUserLog: 1000003
08-16 14:42:31.674  2689  4448 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
08-16 14:42:31.675  2020  2020 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
08-16 14:42:31.675  1589  1589 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
08-16 14:42:31.676  1589  1641 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-16 14:42:31.676  1589  1641 D KeyguardModel: createShortcutInfo...
08-16 14:42:31.676  2020  2020 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
08-16 14:42:31.677  2020  2020 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
08-16 14:42:31.688  1038  1038 I art     : Explicit concurrent mark sweep GC freed 47367(2MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/65MB, paused 1.683ms total 125.566ms
08-16 14:42:31.688  1038  1944 I art     : WaitForGcToComplete blocked for 11.782ms for cause Explicit
,08-16 14:42:31.692  1589  1641 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-16 14:42:31.692  1589  1641 D KeyguardModel: createShortcutInfo...
08-16 14:42:31.693  1589  1589 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-16 14:42:31.697  1589  1641 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-16 14:42:31.698  1589  1641 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 14:42:31.698  1589  1641 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-16 14:42:31.699  1589  1641 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-16 14:42:31.699  1589  1641 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-16 14:42:31.699  1589  1641 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-16 14:42:31.701  1589  1641 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-16 14:42:31.701  1589  1641 D KeyguardModel: createShortcutInfo...
,08-16 14:42:31.704  1589  1641 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-16 14:42:31.704  1589  1641 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-16 14:42:31.705  1589  1641 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-16 14:42:31.705  1589  1641 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-16 14:42:31.706  1589  1641 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-16 14:42:31.706  1589  1641 D KeyguardModel: createShortcutInfo...
08-16 14:42:31.711  1589  1589 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
08-16 14:42:31.711  1589  1641 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 14:42:31.711  1589  1641 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-16 14:42:31.711  1589  1641 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-16 14:42:31.711  1589  1641 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-16 14:42:31.712  1589  1641 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-16 14:42:31.712  1589  1641 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
,08-16 14:42:31.713  1589  1641 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-16 14:42:31.713  1589  1641 D KeyguardModel: createShortcutInfo...
08-16 14:42:31.761  1856  1856 D SplitUIManager: split_name #11 / not available #0
08-16 14:42:31.762  1856  1856 D SplitUIService: removed split : 
,08-16 14:42:31.766  1038  1038 D administrator: Handling package changes for user 0
08-16 14:42:31.790  1856  1856 D SplitUIManager: split_name #11 / not available #0
08-16 14:42:31.790  1856  1856 I SplitUIService: split app #11
,08-16 14:42:31.821  1038  2018 V SIM_STK : Menu title from STK is T-Mobile
08-16 14:42:31.821  1038  2018 V SIM_STK : Menu title from STK is T-Mobile
,08-16 14:42:31.844  1038  1944 I art     : Explicit concurrent mark sweep GC freed 8156(602KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/65MB, paused 3.123ms total 155.668ms
,08-16 14:42:31.848  1038  1126 I art     : WaitForGcToComplete blocked for 132.157ms for cause Explicit
08-16 14:42:31.850  2178  2178 I ConfigService: onCreate
08-16 14:42:31.851  2178  2178 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
08-16 14:42:31.854  2178  2178 I ConfigService: onBind returning update interface
08-16 14:42:31.856  1891  1891 D ActionManagerService: notifyUserLog: 1000004
08-16 14:42:31.856  2020  2020 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
,08-16 14:42:31.857  2689  4448 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
08-16 14:42:31.857  1038  1890 V SIM_STK : Menu title from STK is T-Mobile
08-16 14:42:31.872  1589  1589 D KeyguardModel: handleShortcutListChanged...
08-16 14:42:31.872  1589  1589 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
,08-16 14:42:31.879  1803  1803 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
08-16 14:42:31.884  1038  1890 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-16 14:42:31.884  7968  7968 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-16 14:42:31.884  7968  7968 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-16 14:42:31.884  7968  7968 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-16 14:42:31.884  7968  7968 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-16 14:42:31.884  7968  7968 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-16 14:42:31.884  7968  7968 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-16 14:42:31.884  7968  7968 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-16 14:42:31.884  2689  2761 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
,08-16 14:42:31.884  7968  7968 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-16 14:42:31.884  7968  7968 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-16 14:42:31.884  7968  7968 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-16 14:42:31.884  7968  7968 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-16 14:42:31.885  2178  2178 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-16 14:42:31.885  2178  2178 I ConfigService: onBind returning config service
08-16 14:42:31.889  2020  2020 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-16 14:42:31.889  2020  2020 I GBoardWebViewUtils: , create_time: 1430832262123
08-16 14:42:31.889  2020  2020 I GBoardWebViewUtils: , expire_time: 0
08-16 14:42:31.889  2020  2020 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-16 14:42:31.889  2020  2020 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-16 14:42:31.889  2020  2020 I GBoardWebViewUtils: , display: false
08-16 14:42:31.889  2020  2020 I GBoardWebViewUtils: , animation: false }
08-16 14:42:31.889  2020  2020 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-16 14:42:31.889  2020  2020 I GBoardWebViewUtils: , create_time: 1430832262287
08-16 14:42:31.889  2020  2020 I GBoardWebViewUtils: , expire_time: 0
08-16 14:42:31.889  2020  2020 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-16 14:42:31.889  2020  2020 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-16 14:42:31.889  2020  2020 I GBoardWebViewUtils: , display: false
08-16 14:42:31.889  2020  2020 I GBoardWebViewUtils: , animation: false }
08-16 14:42:31.889  2020  2020 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1471007225619
08-16 14:42:31.889  2020  2020 I GBoardWebViewUtils: , create_time: 1471007226523
08-16 14:42:31.889  2020  2020 I GBoardWebViewUtils: , expire_time: 0
08-16 14:42:31.889  2020  2020 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/4/userguide.html?id=guide_1111111111116_1471007225619&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-16 14:42:31.889  2020  2020 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-16 14:42:31.889  2020  2020 I GBoardWebViewUtils: , display: false
08-16 14:42:31.889  2020  2020 I GBoardWebViewUtils: , animation: false }
08-16 14:42:31.891  2178  2178 I ConfigService: onDestroy
08-16 14:42:31.891  1589  1641 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-16 14:42:31.891  1589  1641 D KeyguardModel: createShortcutInfo...
08-16 14:42:31.893  1589  1641 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-16 14:42:31.894  1589  1641 D KeyguardModel: createShortcutInfo...
08-16 14:42:31.895  1589  1641 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-16 14:42:31.895  1589  1641 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-16 14:42:31.896  2020  8855 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
08-16 14:42:31.896  1589  1641 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-16 14:42:31.896  1589  1641 D KeyguardModel: createShortcutInfo...
,08-16 14:42:31.900  1589  1641 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-16 14:42:31.900  1589  1641 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-16 14:42:31.902  1589  1641 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-16 14:42:31.902  1589  1641 D KeyguardModel: createShortcutInfo...
08-16 14:42:31.903  1589  1641 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-16 14:42:31.903  1589  1641 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-16 14:42:31.904  1589  1641 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-16 14:42:31.905  1589  1641 D KeyguardModel: createShortcutInfo...
08-16 14:42:31.908  2020  2020 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-16 14:42:31.909  2020  2020 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
,08-16 14:42:31.913  1803  8856 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
08-16 14:42:31.920  1589  1589 D KeyguardModel: handleShortcutListChanged...
08-16 14:42:31.920  1589  1589 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
,08-16 14:42:31.946  1038  1038 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-16 14:42:31.947  1038  1038 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-16 14:42:31.947  1038  1038 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-16 14:42:31.949  1038  1563 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
08-16 14:42:31.969  5868  8863 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
,08-16 14:42:31.971  1803  8865 I PeopleContactsSync: CP2 sync disabled
08-16 14:42:31.974  2020  2020 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
08-16 14:42:31.975  7047  7047 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
08-16 14:42:31.978  1803  4710 I Icing   : doRemovePackageData com.test.thalitest
08-16 14:42:31.995  2341  8867 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-16 14:42:32.014  1038  1944 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8869 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-16 14:42:32.027  1803  8864 W GmsApplication: Using Auth Proxy for data requests.
,08-16 14:42:32.036  1803  8864 W GmsApplication: Using Auth Proxy for data requests.
08-16 14:42:32.054  2020  2020 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,08-16 14:42:32.057  2020  2020 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-16 14:42:32.058  2020  2020 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
08-16 14:42:32.060  2020  2020 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-16 14:42:32.061  2020  2020 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-16 14:42:32.062  2020  2020 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
08-16 14:42:32.078  1038  1121 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{345199ba u0 com.lge.launcher2/.Launcher t5} time:229258
,08-16 14:42:32.081  2020  2020 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
08-16 14:42:32.081  2020  2020 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-16 14:42:32.094  1803  8858 I art     : Explicit concurrent mark sweep GC freed 46636(3MB) AllocSpace objects, 31(488KB) LOS objects, 51% free, 30MB/62MB, paused 1.320ms total 31.369ms
,08-16 14:42:32.095  2020  2151 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-16 14:42:32.095  2020  2151 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
08-16 14:42:32.097  2020  2020 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
08-16 14:42:32.097  2020  2020 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-16 14:42:32.097  2020  2020 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-16 14:42:32.099  1803  1815 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/history_query.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
08-16 14:42:32.101  1803  1815 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/help_responses.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
08-16 14:42:32.102  1803  1815 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/metrics.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
08-16 14:42:32.107  2020  2020 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
08-16 14:42:32.111  2559  2559 D [Concierge]Service: onStartCommand(). Type : 8
,08-16 14:42:32.111  2559  2559 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
08-16 14:42:32.113  2559  2559 D [Concierge]Service: Update widget ID : 11
08-16 14:42:32.113  2020  2020 D [Concierge]WidgetView: change position of spinner
08-16 14:42:32.115  2020  2020 I [Concierge]WidgetView: initWebView(). Time : 1471351352115
08-16 14:42:32.115  2559  2559 D [Concierge]Service: onStartCommand(). Type : 0
08-16 14:42:32.118  1038  1107 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 14:42:32.121  1038  1107 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,08-16 14:42:32.134  8869  8869 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 14:42:32.134  8869  8869 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-16 14:42:32.135  8869  8869 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-16 14:42:32.135  8869  8869 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-16 14:42:32.139  2020  2020 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 1016008361
08-16 14:42:32.140  2020  2020 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
08-16 14:42:32.140  2020  2020 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-16 14:42:32.145  2020  2020 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@30c70280
08-16 14:42:32.145  2020  2020 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
,08-16 14:42:32.149  2020  2020 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-16 14:42:32.149  2020  2020 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-16 14:42:32.154  2020  2020 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
08-16 14:42:32.154  2020  2020 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-16 14:42:32.154  2020  2020 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-16 14:42:32.160  1038  1126 I art     : Explicit concurrent mark sweep GC freed 8812(495KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 1.373ms total 311.550ms
08-16 14:42:32.160  2020  2020 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1471351150361, New one : 1471351352115
,08-16 14:42:32.160  2020  2020 D [Concierge]WidgetView: Unregister all receivers
08-16 14:42:32.160  2020  2020 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-16 14:42:32.161  2020  2020 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-16 14:42:32.163  2020  2020 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-16 14:42:32.166  2020  2020 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
08-16 14:42:32.169  2020  2020 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
08-16 14:42:32.171  2020  2020 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
,08-16 14:42:32.173  2020  2020 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
08-16 14:42:32.175  2020  2020 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
08-16 14:42:32.176  2020  2020 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-16 14:42:32.176  2020  2020 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-16 14:42:32.201  8869  8869 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-16 14:42:32.214  8869  8869 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
08-16 14:42:32.218  1038  1381 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-55 f=2447 sc=60 link=72 tx=9.2, 0.0, 0.0  rx=5.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1822430310] gl rssi=-55 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-16 14:42:32.219  1038  1381 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-55 f=2447 sc=60 link=72 tx=9.2, 0.0, 0.0  rx=5.4 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1822430309] gl rssi=-55 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-16 14:42:32.219  1038  1381 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-16 14:42:32.238  8869  8869 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-16 14:42:32.253  2020  2020 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,08-16 14:42:32.266  8869  8869 D LgDataFeature: LgDataFeature() Constructor: none
08-16 14:42:32.266  8869  8869 D LgDataFeature: LgDataFeature() Constructor Done, null
08-16 14:42:32.266  2020  2020 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
08-16 14:42:32.266  2020  2020 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
,08-16 14:42:32.270  2020  2020 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-16 14:42:32.291  2020  2020 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@33ceb8fa time:229470
,08-16 14:42:32.311  8822  8822 D AndroidRuntime: Shutting down VM
,08-16 14:42:32.341  8869  8869 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,08-16 14:42:32.356  1038  1944 I ActivityManager: Killing 8140:com.lge.formmanager/u0a26 (adj 15): empty #17
,08-16 14:42:32.392  2020  2020 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,08-16 14:42:32.429  2020  2847 I GBoardtInterface: onReloaded()
,08-16 14:42:32.431  2020  2020 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
08-16 14:42:32.443  1983  1983 D LIA_Service_NativeEventReceiver: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-16 14:42:32.444  1983  1983 I LIA_Service_PlatformUtil: startLIAService() : Trying to start LIA service ...
,08-16 14:42:32.445  1038  1890 W libprocessgroup: failed to open /acct/uid_10026/pid_8140/cgroup.procs: No such file or directory
08-16 14:42:32.452  1983  1983 D LIA_Service_LIAService: onStartCommand() : LIAService started! - id :4, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
08-16 14:42:32.452  2689  2763 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-16 14:42:32.459  2689  2718 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
,08-16 14:42:32.461  8211  8211 D PostponalbeReceiver: OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-16 14:42:32.534  1038  2018 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.core.receiver.CoreEventReceiver: pid=8894 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-16 14:42:32.540  1891  1891 D ActionManagerService: notifyUserLog: 1000001
08-16 14:42:32.543  2689  4448 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-16 14:42:32.543  2689  4448 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-16 14:42:32.552  1891  1891 D ActionManagerService: notifyUserLog: 1000001
,08-16 14:42:32.554  2689  4448 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-16 14:42:32.554  2689  4448 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-16 14:42:32.554  2689  4448 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
08-16 14:42:32.554  2689  4448 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
08-16 14:42:32.556  2689  2718 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
,08-16 14:42:32.601  1038  1126 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8915 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
08-16 14:42:32.602  2020  2020 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
08-16 14:42:32.602  2020  2020 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
08-16 14:42:32.608  2020  2020 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
08-16 14:42:32.608  2020  2020 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-16 14:42:32.614  2020  2020 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/4/userguide2.html?id=guide_1111111111116_1471007225619&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
08-16 14:42:32.614  2020  2020 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/4/userguide2.html?id=guide_1111111111116_1471007225619&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
,08-16 14:42:32.675   347   367 E GBMv2   : DFP En is all cleared set to be enabled
08-16 14:42:32.676   347   367 E GBMv2   : Set value is all cleared set the max
08-16 14:42:32.676   347   367 I GBMv2   : DFP Enabled. Ignore VFP set
,08-16 14:42:32.698  1038  1908 I ActivityManager: Killing 8404:com.android.chrome/u0a57 (adj 15): empty #17

```
