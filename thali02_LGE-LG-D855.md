#### Test 7976383051d2164_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
08-30 11:36:40.752  6373  6373 D PostponalbeReceiver: OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_ADDED'.
--------- beginning of system
08-30 11:36:40.758  6373  6373 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsm.mss.OasPackageScanReceiver.onReceive:-1 android.app.ActivityThread.handleReceiver:2586 
08-30 11:36:40.794  4620  6499 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
08-30 11:36:40.858  1028  1914 V SIM_STK : Menu title from STK is T-Mobile
08-30 11:36:40.859  1028  2040 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=6503 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-30 11:36:40.994  1808  4777 I art     : Explicit concurrent mark sweep GC freed 25689(1793KB) AllocSpace objects, 15(240KB) LOS objects, 51% free, 29MB/61MB, paused 1.927ms total 63.172ms
08-30 11:36:41.028  4620  6499 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 234 ms] updated apps [took 233 ms] 
08-30 11:36:41.086  6503  6503 D DocsApplication: Installing DEX configuration.
08-30 11:36:41.104  6503  6503 D DexInstaller: Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
08-30 11:36:41.108  6503  6503 I PackageInfoHelper: Provided clientMode=RELEASE, packageInfo=PackageInfo{172d23d com.google.android.apps.docs}
08-30 11:36:41.124  6503  6503 D TAG     : onCreate()
08-30 11:36:41.145  6503  6503 D CrossAppStateProvider: Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
08-30 11:36:41.514   334   416 I ThermalEngine: Thermal-Server: Thermal received msg from  override
,08-30 11:36:41.522  3194  6524 I Thermal-Lib: Thermal-Lib-Client: Client request sent
08-30 11:36:41.908  6525  6525 D AndroidRuntime: 
08-30 11:36:41.908  6525  6525 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-30 11:36:41.910  6525  6525 D AndroidRuntime: CheckJNI is OFF
08-30 11:36:42.021  6525  6525 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-30 11:36:42.025  1028  1710 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-30 11:36:42.031  1808  4777 I Icing   : Indexing 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4 from com.google.android.googlequicksearchbox
08-30 11:36:42.032  1933  1949 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-30 11:36:42.035  1028  1710 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-30 11:36:42.037  1028  1710 D ActivityManager: setTaskToReturnTo : TaskRecord{192ca6e4 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-30 11:36:42.037  1028  1710 D ActivityManager: setTaskToReturnTo : TaskRecord{192ca6e4 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-30 11:36:42.038  1028  1710 D WindowStateEx: AppWindowTokenEx init.. 
08-30 11:36:42.039   340   355 E GBMv2   : DFP En is all cleared set to be enabled
08-30 11:36:42.062  1028  1710 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6540 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-30 11:36:42.064  6525  6525 D AndroidRuntime: Shutting down VM
08-30 11:36:42.093  1808  4777 D Icing   : Loaded CLD2 Version V2.0 - 20140131
08-30 11:36:42.111  1933  1949 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-30 11:36:42.111  1933  1949 D SplitWindowPolicy: topRunningActivity=ActivityInfo{2d2be349 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-30 11:36:42.112  1933  1948 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-30 11:36:42.112  1933  1948 D SplitWindowPolicy: topRunningActivity=ActivityInfo{2e66344e co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-30 11:36:42.148  1808  4777 I Icing   : Indexing done 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4
08-30 11:36:42.161  6540  6540 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-30 11:36:42.233  6540  6540 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
08-30 11:36:42.248  6540  6540 I LibraryLoader: Loading: webviewchromium
08-30 11:36:42.251  6540  6540 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 3292-3296)
08-30 11:36:42.251  6540  6540 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-30 11:36:42.269  6540  6540 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {23ac54df}
08-30 11:36:42.270  6540  6540 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-30 11:36:42.271  6540  6540 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,08-30 11:36:42.283  6540  6540 I BrowserStartupController: Initializing chromium process, renderers=0
,08-30 11:36:42.284  6540  6540 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-30 11:36:42.297  6540  6540 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-30 11:36:42.297  6540  6540 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
08-30 11:36:42.298  6540  6540 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
,08-30 11:36:42.300   320   320 V AudioPolicyService: registerClient() client 0xb558af20, uid 10118
08-30 11:36:42.321  6540  6540 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-30 11:36:42.321  6540  6540 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-30 11:36:42.321  6540  6540 I Adreno-EGL: Build Date: 12/12/14 금
08-30 11:36:42.321  6540  6540 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-30 11:36:42.321  6540  6540 I Adreno-EGL: Remote Branch: 
08-30 11:36:42.321  6540  6540 I Adreno-EGL: Local Patches: 
08-30 11:36:42.321  6540  6540 I Adreno-EGL: Reconstruct Branch: 
08-30 11:36:42.323  1028  1110 D BluetoothManagerService: Message: 20
08-30 11:36:42.323  1028  1110 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@334ec4e:true
,08-30 11:36:42.359  6503  6503 D LgDataFeature: LgDataFeature() Constructor: none
08-30 11:36:42.359  6503  6503 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 11:36:42.399  6540  6580 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,08-30 11:36:42.407  6540  6540 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
08-30 11:36:42.447  6540  6540 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-30 11:36:42.452  6540  6540 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-30 11:36:42.456  6540  6540 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-30 11:36:42.459  6540  6540 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-30 11:36:42.459  6540  6540 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
,08-30 11:36:42.475  6540  6540 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-30 11:36:42.482  6540  6540 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-30 11:36:42.483  6540  6540 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-30 11:36:42.514  6540  6595 D OpenGLRenderer: Render dirty regions requested: true
08-30 11:36:42.514  6540  6595 I OpenGLRenderer: Initialized EGL, version 1.4
,08-30 11:36:42.519  6164  6164 I LockScreenSettings: New app installed broadcast received ..
08-30 11:36:42.522  6540  6595 D OpenGLRenderer: Enabling debug mode 0
08-30 11:36:42.522  6164  6164 I LockScreenSettings: Number of installed packages  1
08-30 11:36:42.535  6503  6503 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,08-30 11:36:42.538  6540  6540 D Atlas   : Validating map...
08-30 11:36:42.542  1028  1968 D SplitWindow: check instance of lgWin Window{26e3e02d u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-30 11:36:42.562  1028  2040 V SIM_STK : Menu title from STK is T-Mobile
08-30 11:36:42.581  6540  6593 D LgDataFeature: LgDataFeature() Constructor: none
,08-30 11:36:42.581  6540  6593 D LgDataFeature: LgDataFeature() Constructor Done, null
08-30 11:36:42.592  1028  1043 I ActivityManager: Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=6608 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-30 11:36:42.655  6608  6608 D EulaProviderUpdateObserver: action : android.intent.action.PACKAGE_ADDED
08-30 11:36:42.655  6608  6608 D EulaProviderUpdateObserver: uri : package:com.test.thalitest
,08-30 11:36:42.693  6540  6540 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@3e09cd3a time:103738
,08-30 11:36:42.699  1028  1932 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.BNRAppInstallReceiver: pid=6628 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
08-30 11:36:42.702  1028  1932 I ActivityManager: Killing 5880:com.google.android.gm/u0a64 (adj 15): empty #17
08-30 11:36:42.786  1028  2005 W libprocessgroup: failed to open /acct/uid_10064/pid_5880/cgroup.procs: No such file or directory
,08-30 11:36:42.797  1028  1111 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +688ms (total +757ms)
,08-30 11:36:42.798  1028  1111 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{b34b74d u0 com.test.thalitest/.MainActivity t6} time:103843
08-30 11:36:42.812  6540  6540 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-30 11:36:42.812  6540  6540 I chromium: 
,08-30 11:36:42.851  6628  6628 D [BNRAppListMgrReceiver]: android.intent.action.PACKAGE_ADDED : com.test.thalitest
,08-30 11:36:42.866  6540  6540 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-30 11:36:42.875  6628  6628 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-30 11:36:42.879  6373  6373 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.intent.action.PACKAGE_ADDED'.
,08-30 11:36:42.917  1028  2040 I ActivityManager: Killing 5921:com.google.android.talk/u0a72 (adj 15): empty #17
,08-30 11:36:42.944  6540  6593 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-30 11:36:42.944  6540  6593 I chromium: 
,08-30 11:36:43.007  1028  1877 W libprocessgroup: failed to open /acct/uid_10072/pid_5921/cgroup.procs: No such file or directory
,08-30 11:36:43.083  6540  6653 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1434963456
,08-30 11:36:43.098  6540  6653 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-30 11:36:43.098  6540  6653 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-30 11:36:43.098  6540  6653 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-30 11:36:43.098  6540  6653 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-30 11:36:43.098  6540  6653 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-30 11:36:43.099  6540  6653 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1295ecde added. We now have 1 listener(s)
08-30 11:36:43.105  1028  1932 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 11:36:43.108  6540  6653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-30 11:36:43.111  6540  6653 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,08-30 11:36:43.112  6540  6653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 11:36:43.113  6540  6653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 11:36:43.122  6540  6653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-30 11:36:43.122  6540  6653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-30 11:36:43.122  6540  6653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-30 11:36:43.122  6540  6653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-30 11:36:43.122  6540  6653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-30 11:36:43.122  6540  6653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-30 11:36:43.122  6540  6653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-30 11:36:43.122  6540  6653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-30 11:36:43.122  6540  6653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-30 11:36:43.122  6540  6653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-30 11:36:43.122  6540  6653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-30 11:36:43.122  6540  6653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-30 11:36:43.122  6540  6653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-30 11:36:43.122  6540  6653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-30 11:36:43.122  6540  6653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d5da8d5 added. We now have 1 listener(s)
08-30 11:36:43.122  6540  6653 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 11:36:43.129  1028  1433 D WifiService: New client listening to asynchronous messages
,08-30 11:36:43.133  6540  6653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 11:36:43.133  6540  6653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-30 11:36:43.134  6540  6653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-30 11:36:43.134  6540  6653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-30 11:36:43.134  6540  6653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-30 11:36:43.139  6540  6653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 11:36:43.140  1028  1044 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 11:36:43.142  6540  6653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
,08-30 11:36:43.154  6540  6653 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-30 11:36:43.154  6540  6653 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 11:36:43.154  6540  6653 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 11:36:43.154  6540  6653 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 11:36:43.154  6540  6653 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 11:36:43.154  6540  6653 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 11:36:43.154  6540  6653 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 11:36:43.154  6540  6653 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 11:36:43.154  6540  6653 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 11:36:43.154  6540  6653 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-30 11:36:43.155  6540  6653 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 11:36:43.157  6540  6540 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 11:36:43.159  6540  6540 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 11:36:43.160  6540  6653 I io.jxcore.node.LifeCycleMonitor: start: OK
08-30 11:36:43.198  6540  6540 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-30 11:36:43.825   340   357 E GBMv2   : DFP En is all cleared set to be enabled
,08-30 11:36:43.826   340   357 E GBMv2   : Set value is all cleared set the max
08-30 11:36:43.826   340   357 I GBMv2   : DFP Enabled. Ignore VFP set
,08-30 11:36:44.009  6540  6656 W jxcore-log: Initializing JXcore engine
08-30 11:36:44.009  6540  6656 W jxcore-log: JXcore engine is ready
,08-30 11:36:44.087  6656  6656 W Thread-752: type=1400 audit(0.0:162): avc: denied { ioctl } for path="socket:[8399]" dev="sockfs" ino=8399 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,08-30 11:36:44.087  6656  6656 W Thread-752: type=1400 audit(0.0:163): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-30 11:36:44.087  6656  6656 W Thread-752: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[8492]" dev="sockfs" ino=8492 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-30 11:36:44.087  6656  6656 W Thread-752: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-30 11:36:44.087  6656  6656 W Thread-752: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[30210]" dev="sockfs" ino=30210 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
08-30 11:36:44.119  6540  6656 W jxcore-log: Starting JXcore engine
,08-30 11:36:44.246  6540  6656 W jxcore-log: Platform android
08-30 11:36:44.246  6540  6656 W jxcore-log: 
08-30 11:36:44.246  6540  6656 W jxcore-log: Process ARCH arm
08-30 11:36:44.246  6540  6656 W jxcore-log: 
,08-30 11:36:44.462  6540  6656 I jxcore-log: JXcore Cordova bridge is ready!
08-30 11:36:44.462  6540  6656 I jxcore-log: 
08-30 11:36:44.463  6540  6656 W jxcore-log: JXcore engine is started
,08-30 11:36:44.473  6540  6653 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-30 11:36:44.480  6540  6540 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-30 11:36:45.659  2782  2782 I MusicWidget: mDelayedStopHandler : unbind
,08-30 11:36:45.668  2124  2124 I MusicBrowser: [MediaPlaybackService.java:2869:onUnbind()] oooooo 
,08-30 11:36:45.669  2124  2124 I MusicBrowser: [MediaPlaybackService.java:2076:saveQueue()] oooooo {full=true}
08-30 11:36:45.670  2124  2124 I MusicBrowser: [MediaPlaybackService.java:2081:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
08-30 11:36:45.673  2124  2124 D MusicBrowser: [MediaPlaybackService.java:2161:saveQueue()] oooooo {queue=}
08-30 11:36:45.674  2124  2124 D MusicBrowser: [MediaPlaybackService.java:2163:saveQueue()] oooooo {mCardId=-1}
08-30 11:36:45.674  2124  2124 D MusicBrowser: [MediaPlaybackService.java:2198:saveQueue()] oooooo {curpos=-1}
08-30 11:36:45.678  2124  2124 I MusicBrowser: [MediaPlaybackService.java:2046:onDestroy()] oooooo 
08-30 11:36:45.678  2124  2124 I MusicBrowser: [MediaPlaybackService.java:8635:clearReceiver()] oooooo 
08-30 11:36:45.681  1028  1567 I MediaFocusControl:  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@36b515ccom.lge.music.MediaPlaybackService$5@30a3dc65
08-30 11:36:45.682  2124  2124 D MusicBrowser: [MediaPlaybackService.java:8669:clearReceiver()] oooooo abandonAudioFocus : 1
08-30 11:36:45.683  2124  2124 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
,08-30 11:36:45.684  2124  2124 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
,08-30 11:36:45.693  2124  2124 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-30 11:36:45.695  2124  2124 I MusicBrowser: [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$27@22b5ffb
08-30 11:36:45.695  2124  2124 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-30 11:36:45.696  2124  2124 I MusicBrowser: [MusicUtils.java:6801:endNotiTimer()] oooooo endNotiTimer
08-30 11:36:45.696  2124  2124 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-30 11:36:45.697  2124  2124 I MusicBrowser: [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
08-30 11:36:45.697  2124  2124 I MusicBrowser: [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
08-30 11:36:45.697  2124  2124 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-30 11:36:45.698  2124  2124 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-30 11:36:45.698  2124  2124 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-30 11:36:45.699  2124  2124 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-30 11:36:45.699  2124  2124 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-30 11:36:45.700  2124  2124 I MusicBrowser: [MusicUtils.java:10406:isAKACoverSupported()] oooooo aka not support!
08-30 11:36:45.702  2124  2124 I MusicBrowser: [MediaPlaybackService.java:6704:release()] oooooo 
08-30 11:36:45.702  2124  2124 I MusicBrowser: [MediaPlaybackService.java:6665:stop()] oooooo 
08-30 11:36:45.702  2124  2124 V MediaPlayer[Native]: reset
,08-30 11:36:45.710  2124  2124 V MediaPlayer[Native]: setListener
08-30 11:36:45.710  2124  2124 V MediaPlayer[Native]: disconnect
08-30 11:36:45.710  2124  2124 V MediaPlayer[Native]: destructor
08-30 11:36:45.710   320  1390 V AudioFlinger: releasing 16 from 2124 for -1
08-30 11:36:45.710   320  1390 V AudioFlinger:  decremented refcount to 0
08-30 11:36:45.710   320  1390 V AudioFlinger: purging stale effects
08-30 11:36:45.711  2124  2124 V MediaPlayer[Native]: disconnect
08-30 11:36:45.712  2124  2124 D MusicBrowser: [MusicUtils.java:615:getSmartShareVersion()] oooooo versionCode:305000
08-30 11:36:45.713  2124  2124 I SmartShareClient: [SmartShareManagerClient] smartshare client supported version code: 305000
08-30 11:36:45.713  2124  2124 I SmartShareClient: [SmartShareManagerClient] smartshare client enabled
08-30 11:36:45.714  2124  2124 I MusicBrowser: [MusicUtils.java:787:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000018
08-30 11:36:45.714  2124  2124 I MusicBrowser: [MusicUtils.java:635:getSmartShareVersion()] oooooo SmartshareVersion:953
08-30 11:36:45.715  2124  2124 V MusicBrowser: [MediaPlaybackService.java:9312:terminateSmartShareClient()] oooooo 
08-30 11:36:45.715  2124  2124 I SmartShareClient: [SmartShareManagerClient] unregisterListener: 1040829754
08-30 11:36:45.715  2124  2124 W SmartShareClient: [SmartShareManagerClient] unregisterListener invalid listener: 1040829754
,08-30 11:36:45.728  2124  2124 I SmartShareClient: [SmartShareManagerClient] terminate service: 2124/MediaPlaybackService/146756921
08-30 11:36:45.731  2124  2124 E HomeCloudIF: unregiterHomeCloudBroadcast(), Illegal argument.
08-30 11:36:45.732  2124  2124 I SmartShareClient: [SmartShareManagerClient] unbindService context:android.app.Application@1b903deb
08-30 11:36:45.734  2124  2124 V CloudHub: [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.2.1, versionCode=202001, state=0
08-30 11:36:45.734  2124  2124 V CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
08-30 11:36:45.735  2124  2124 I CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
08-30 11:36:45.736  2124  2124 D MusicBrowser: [MediaPlaybackService.java:9007:setStopForeground()] oooooo bValue : true
08-30 11:36:45.737  1028  1968 I ActivityManager: Killing 5652:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,08-30 11:36:45.740  2124  2124 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29995
08-30 11:36:45.755  5628  5628 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
08-30 11:36:45.755  5628  5628 W System.err: android.os.DeadObjectException
08-30 11:36:45.756  5628  5628 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-30 11:36:45.756  5628  5628 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-30 11:36:45.756  5628  5628 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-30 11:36:45.756  5628  5628 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-30 11:36:45.756  5628  5628 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
,08-30 11:36:45.756  5628  5628 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-30 11:36:45.756  5628  5628 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-30 11:36:45.756  5628  5628 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-30 11:36:45.756  5628  5628 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-30 11:36:45.756  5628  5628 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-30 11:36:45.756  5628  5628 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 11:36:45.756  5628  5628 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 11:36:45.756  5628  5628 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-30 11:36:45.756  5628  5628 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-30 11:36:45.756  5628  5628 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-30 11:36:45.757  5628  5628 W System.err: android.os.DeadObjectException
08-30 11:36:45.765  5628  5628 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-30 11:36:45.765  5628  5628 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-30 11:36:45.765  5628  5628 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-30 11:36:45.765  5628  5628 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-30 11:36:45.765  5628  5628 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-30 11:36:45.765  5628  5628 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-30 11:36:45.766  5628  5628 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-30 11:36:45.766  5628  5628 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-30 11:36:45.766  5628  5628 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-30 11:36:45.766  5628  5628 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-30 11:36:45.766  5628  5628 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 11:36:45.766  5628  5628 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 11:36:45.766  5628  5628 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-30 11:36:45.766  5628  5628 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-30 11:36:45.767  5628  5628 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-30 11:36:45.767  5628  5628 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
08-30 11:36:45.950  1028  1968 E libprocessgroup: failed to kill 1 processes for processgroup 5652
,08-30 11:36:46.176  1028  1914 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
08-30 11:36:46.184  5628  5628 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-30 11:36:46.185  5628  5628 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-30 11:36:46.224  1028  2040 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=6687 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-30 11:36:46.232  5628  5628 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-30 11:36:46.300  6687  6687 D UEI.SmartControl: Quickset Services start...
08-30 11:36:46.302  6687  6687 I UEI.SmartControl: Manufacture = LGE
08-30 11:36:46.302  6687  6687 D UEI.SmartControl: Id = LGNevo
08-30 11:36:46.303  6687  6687 D UEI.SmartControl: File observer start...
08-30 11:36:46.304  6687  6687 E UEI.SmartControl: IR Port is disabled: false
08-30 11:36:46.304  6687  6687 D UEI.SmartControl: Starting file observer...
08-30 11:36:46.304  6687  6687 D UEI.SmartControl: Extracting JNI libs...
08-30 11:36:46.304  6687  6687 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
,08-30 11:36:46.398  6687  6687 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,08-30 11:36:46.398  6687  6687 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-30 11:36:46.398  6687  6687 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,08-30 11:36:46.435  6687  6687 I UEI.SmartControl: --- Selecting new region: 6
,08-30 11:36:46.438  6687  6687 I UEI.SmartControl: Model = LG-D855
08-30 11:36:46.439  6687  6687 D UEI.SmartControl: QS Service created
08-30 11:36:46.454  6687  6687 I UEI.SmartControl: Service initServices...
,08-30 11:36:46.458  6687  6687 D UEI.SmartControl: QS start get config
08-30 11:36:46.464  6503  6503 W GAV2    : Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
08-30 11:36:46.469  1028  1878 I ActivityManager: Killing 5628:com.lge.qremote/u0a112 (adj 15): empty #17
,08-30 11:36:46.497  6687  6687 D UEI.SmartControl: Loading JNI Libs...
,08-30 11:36:46.575  1028  1043 W libprocessgroup: failed to open /acct/uid_10112/pid_5628/cgroup.procs: No such file or directory
,08-30 11:36:46.741  6687  6687 I UEI.SmartControl: Supports setup maps: true
,08-30 11:36:46.744  6687  6687 D UEI.SmartControl: QS start statue = true Error code = 0
08-30 11:36:46.744  6687  6687 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-30 11:36:46.745  6687  6687 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-30 11:36:46.745  6687  6687 I UEI.SmartControl: ### init IR Blaster...
08-30 11:36:46.749  6687  6687 D serial_port: Configuring serial port
08-30 11:36:46.753  6687  6687 E UEI.SmartControl: UEIBLaster setting for 616
08-30 11:36:46.753  6687  6687 I UEI.SmartControl: Setting serial record hearder size = 2
08-30 11:36:46.753  6687  6687 I UEI.SmartControl: configuring settings for MAXQ616
08-30 11:36:46.753  6687  6687 I UEI.SmartControl: Get version...
,08-30 11:36:46.770  6687  6718 D UEI.SmartControl: serial port data available: 21
,08-30 11:36:46.797  6687  6687 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-30 11:36:46.797  6687  6687 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-30 11:36:46.797  6687  6687 I UEI.SmartControl: QS saving settings...
08-30 11:36:46.798  6687  6687 D UEI.SmartControl: IR Blaster version: 25672567
,08-30 11:36:46.814  6687  6718 D UEI.SmartControl: serial port data available: 4
,08-30 11:36:46.850  6687  6724 I UEI.SmartControl: Device manager: loading config....
,08-30 11:36:46.853  6687  6724 D UEI.SmartControl: ----------- loading internal config...
08-30 11:36:46.856  6687  6687 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-30 11:36:46.862  6687  6687 E UEI.SmartControl: Services init done,
08-30 11:36:46.863  6687  6687 D UEI.SmartControl: QS Service init finished
,08-30 11:36:46.866  6687  6724 E UEI.SmartControl: Loading SETTINGS...
08-30 11:36:46.869  6687  6687 D UEI.SmartControl: QS Service version name: 2.1.91
08-30 11:36:46.869  6687  6687 D UEI.SmartControl: QS Service version code: 201091
08-30 11:36:46.870  6687  6724 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-30 11:36:46.871  6687  6687 D UEI.SmartControl: Service requested: Control
08-30 11:36:46.873  6687  6687 D UEI.SmartControl: Service.onUnbind: IControl
08-30 11:36:46.875  6687  6687 D UEI.SmartControl: Service.onDestroy
08-30 11:36:46.875  6687  6687 D UEI.SmartControl: Lock is in USE false
08-30 11:36:46.875  6687  6687 D UEI.SmartControl: unbind internal service
,08-30 11:36:46.878  6687  6687 D serial_port: close(fd = 25)
08-30 11:36:46.881  6687  6687 I UEI.SmartControl: Serial port is closed.
08-30 11:36:46.881  6687  6687 I UEI.SmartControl: Serial port is closed.
08-30 11:36:46.881  6687  6687 D UEI.SmartControl: Blaster closed
08-30 11:36:46.881  6687  6687 D UEI.SmartControl: Shut down QS...
08-30 11:36:46.881  6687  6687 D UEI.SmartControl: Stopping QS lib
08-30 11:36:46.882  6687  6687 D UEI.SmartControl: QS lib stop result = true
08-30 11:36:46.882  6687  6687 D UEI.SmartControl: Stopped QS lib
08-30 11:36:46.882  6687  6687 D UEI.SmartControl: Stopped file observer...
08-30 11:36:46.882  6687  6687 D UEI.SmartControl: QS shutdown complete
08-30 11:36:46.882  6687  6687 D UEI.SmartControl: QS Service created
08-30 11:36:46.888  6687  6723 I UEI.SmartControl: Notify AllClients services are ready: 11
08-30 11:36:46.888  6687  6723 D UEI.SmartControl: -----service ready thread exits
08-30 11:36:46.896  6687  6687 I UEI.SmartControl: Service initServices...
,08-30 11:36:46.896  6687  6687 D UEI.SmartControl: QS start get config
08-30 11:36:47.200  6687  6687 I UEI.SmartControl: Supports setup maps: true
08-30 11:36:47.203  6687  6687 D UEI.SmartControl: QS start statue = true Error code = 0
08-30 11:36:47.203  6687  6687 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-30 11:36:47.203  6687  6687 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-30 11:36:47.203  6687  6687 I UEI.SmartControl: ### init IR Blaster...
,08-30 11:36:47.206  6687  6687 D serial_port: Configuring serial port
08-30 11:36:47.206  6687  6687 E UEI.SmartControl: UEIBLaster setting for 616
08-30 11:36:47.206  6687  6687 I UEI.SmartControl: Setting serial record hearder size = 2
08-30 11:36:47.206  6687  6687 I UEI.SmartControl: configuring settings for MAXQ616
08-30 11:36:47.206  6687  6687 I UEI.SmartControl: Get version...
08-30 11:36:47.223  6687  6727 D UEI.SmartControl: serial port data available: 21
,08-30 11:36:47.248  6687  6687 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-30 11:36:47.248  6687  6687 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-30 11:36:47.248  6687  6687 I UEI.SmartControl: QS saving settings...
08-30 11:36:47.249  6687  6687 D UEI.SmartControl: IR Blaster version: 25672567
,08-30 11:36:47.262  6687  6727 D UEI.SmartControl: serial port data available: 4
,08-30 11:36:47.291  6687  6735 I UEI.SmartControl: Device manager: loading config....
,08-30 11:36:47.292  6687  6687 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-30 11:36:47.293  6687  6735 D UEI.SmartControl: ----------- loading internal config...
08-30 11:36:47.294  6687  6687 E UEI.SmartControl: Services init done
08-30 11:36:47.294  6687  6687 D UEI.SmartControl: QS Service init finished
08-30 11:36:47.295  6687  6687 D UEI.SmartControl: QS Service version name: 2.1.91
08-30 11:36:47.295  6687  6687 D UEI.SmartControl: QS Service version code: 201091
08-30 11:36:47.295  6687  6687 D UEI.SmartControl: Service requested: Control
08-30 11:36:47.298  6687  6735 E UEI.SmartControl: Loading SETTINGS...
08-30 11:36:47.301  6687  6687 D UEI.SmartControl: Request IControl service: devices are loaded...
08-30 11:36:47.303  1028  1914 I ActivityManager: Killing 5217:com.android.calendar/u0a13 (adj 15): empty #17
,08-30 11:36:47.309  6687  6735 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-30 11:36:47.330  6687  6734 I UEI.SmartControl: Notify AllClients services are ready: 0
08-30 11:36:47.330  6687  6734 D UEI.SmartControl: -----service ready thread exits
,08-30 11:36:47.477  1028  1043 W libprocessgroup: failed to open /acct/uid_10013/pid_5217/cgroup.procs: No such file or directory
,08-30 11:36:47.479  6687  6687 E ActivityThread: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.g@22b5ffb that was originally bound here
08-30 11:36:47.479  6687  6687 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.g@22b5ffb that was originally bound here
08-30 11:36:47.479  6687  6687 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1167)
08-30 11:36:47.479  6687  6687 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1061)
08-30 11:36:47.479  6687  6687 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1839)
08-30 11:36:47.479  6687  6687 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:1822)
08-30 11:36:47.479  6687  6687 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
08-30 11:36:47.479  6687  6687 E ActivityThread: 	at com.uei.control.Service.b(Unknown Source)
08-30 11:36:47.479  6687  6687 E ActivityThread: 	at com.uei.control.Service.a(Unknown Source)
08-30 11:36:47.479  6687  6687 E ActivityThread: 	at com.uei.control.Service.onCreate(Unknown Source)
08-30 11:36:47.479  6687  6687 E ActivityThread: 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2738)
08-30 11:36:47.479  6687  6687 E ActivityThread: 	at android.app.ActivityThread.access$1800(ActivityThread.java:148)
08-30 11:36:47.479  6687  6687 E ActivityThread: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
08-30 11:36:47.479  6687  6687 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 11:36:47.479  6687  6687 E ActivityThread: 	at android.os.Looper.loop(Looper.java:135)
08-30 11:36:47.479  6687  6687 E ActivityThread: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-30 11:36:47.479  6687  6687 E ActivityThread: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 11:36:47.479  6687  6687 E ActivityThread: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 11:36:47.479  6687  6687 E ActivityThread: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-30 11:36:47.479  6687  6687 E ActivityThread: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-30 11:36:47.486  6687  6687 D UEI.SmartControl: Internal service binding...
08-30 11:36:47.518  6503  6586 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,08-30 11:36:47.876  6687  6726 D UEI.SmartControl: Internal timer expired: 2
,08-30 11:36:49.945  1808  6416 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,08-30 11:36:49.948   315  6746 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-30 11:36:49.948   315  6746 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
08-30 11:36:49.949   315  6746 D libc-netbsd: res_queryN name = android.clients.google.com succeed
08-30 11:36:50.172  1808  1808 I ConfigFetchService: fetch service done; releasing wakelock
,08-30 11:36:50.177  1808  1808 I ConfigFetchService: stopping self
08-30 11:36:50.185  2195  2195 I ConfigService: onDestroy
,08-30 11:36:51.309  6687  6698 E UEI.SmartControl: file observer is disposed!
,08-30 11:36:52.269  6687  6732 D serial_port: close(fd = 24)
,08-30 11:36:52.276  6687  6732 I UEI.SmartControl: Serial port is closed.
,08-30 11:36:52.291  6687  6736 D UEI.SmartControl: Internal timer expired: 3
08-30 11:36:52.291  6687  6736 D UEI.SmartControl: unbind internal service
,08-30 11:36:52.309  6687  6687 D UEI.SmartControl: Service.onUnbind: IControl
,08-30 11:36:52.312  6687  6687 D UEI.SmartControl: Service.onDestroy
,08-30 11:36:52.312  6687  6687 D UEI.SmartControl: Lock is in USE false
,08-30 11:36:52.313  6687  6687 D UEI.SmartControl: unbind internal service
,08-30 11:36:52.313  6687  6687 I UEI.SmartControl: Serial port is closed.
,08-30 11:36:52.313  6687  6687 I UEI.SmartControl: Serial port is closed.
08-30 11:36:52.313  6687  6687 D UEI.SmartControl: Blaster closed
08-30 11:36:52.313  6687  6687 D UEI.SmartControl: Shut down QS...
08-30 11:36:52.313  6687  6687 D UEI.SmartControl: Stopping QS lib
,08-30 11:36:52.314  6687  6687 D UEI.SmartControl: QS lib stop result = true
,08-30 11:36:52.314  6687  6687 D UEI.SmartControl: Stopped QS lib
08-30 11:36:52.314  6687  6687 D UEI.SmartControl: QS shutdown complete
08-30 11:36:54.527  6540  6656 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-30 11:36:54.527  6540  6656 I jxcore-log: 
08-30 11:36:54.531  6540  6656 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-30 11:36:54.531  6540  6656 I jxcore-log: 
08-30 11:36:54.533  6540  6656 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 11:36:54.533  6540  6656 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 11:36:54.533  6540  6656 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 11:36:54.533  6540  6656 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 11:36:54.533  6540  6656 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 11:36:54.533  6540  6656 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 11:36:54.533  6540  6656 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 11:36:54.533  6540  6656 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 11:36:54.535  6540  6656 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e,
08-30 11:36:54.538  6540  6656 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-30 11:36:54.538  6540  6656 I jxcore-log: 
,08-30 11:36:54.539  6540  6656 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-30 11:36:54.539  6540  6656 I jxcore-log: 
,08-30 11:36:55.046  6540  6656 D executeNativeTests: Running unit tests
,08-30 11:36:55.099  1028  1106 I ActivityManager: Waited long enough for: ServiceRecord{38be6c4a u0 com.google.android.gms/.wearable.service.WearableService}
,08-30 11:36:55.128  6540  6656 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-30 11:36:55.128  6540  6656 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30c6d02e added. We now have 2 listener(s)
,08-30 11:36:55.129  1028  1968 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 11:36:55.131  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,08-30 11:36:55.131  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-30 11:36:55.131  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-30 11:36:55.131  6540  6656 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
08-30 11:36:55.131  6540  6656 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a8d7cf added. We now have 2 listener(s)
,08-30 11:36:55.131  6540  6656 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 11:36:55.132  6540  6656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 11:36:55.134  6540  6656 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 11:36:55.136  6540  6656 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 11:36:55.136  6540  6656 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 11:36:55.136  6540  6656 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 11:36:55.136  6540  6656 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 11:36:55.136  6540  6656 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 11:36:55.136  6540  6656 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 11:36:55.136  6540  6656 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 11:36:55.136  6540  6656 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 11:36:55.137  6540  6656 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 11:36:55.137  6540  6656 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 11:36:55.139  6540  6540 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 11:36:55.140  6540  6540 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 11:36:55.142  6540  6656 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-30 11:36:55.142  6540  6656 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 11:36:55.142  6540  6656 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 11:36:55.144  6540  6656 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-30 11:36:55.145  6540  6656 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-30 11:36:55.145  6540  6656 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-30 11:36:55.145  6540  6656 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 11:36:55.145  6540  6656 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 11:36:55.146  6540  6656 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 11:36:55.146  6540  6656 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 11:36:55.146  6540  6656 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 11:36:55.147  6540  6656 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 11:36:55.147  6540  6656 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:55.147  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 11:36:55.147  6540  6656 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 11:36:55.147  6540  6656 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30c6d02e removed from the list
08-30 11:36:55.147  6540  6656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:36:55.147  6540  6656, V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a8d7cf removed from the list
08-30 11:36:55.147  6540  6656 D io.jxcore.node.ConnectivityMonitor: stop
08-30 11:36:55.147  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 11:36:55.148  6540  6656 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-30 11:36:55.148  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:55.149  6540  6656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 11:36:55.149  6540  6656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 11:36:55.149  6540  6656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:36:55.149  6540  6656 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a8d7cf not in the list
08-30 11:36:55.150  6540  6656 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-30 11:36:55.151  6540  6656 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
08-30 11:36:55.151  6540  6656 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 11:36:55.151  6540  6656 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 11:36:55.151  6540  6656 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 11:36:55.151  6540  6656 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:55.151  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 11:36:55.151  6540  6656 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30c6d02e not in the list
08-30 11:36:55.151  6540  6656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:36:55.151  6540  6656 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a8d7cf not in the list
08-30 11:36:55.151  6540  6656 D io.jxcore.node.ConnectivityMonitor: stop
08-30 11:36:55.151  6540  6656 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 11:36:55.151  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:55.151  6540  6656 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:55.151  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:55.152  6540  6656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 11:36:55.152  6540  6656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 11:36:55.152  6540  6656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-30 11:36:55.152  6540  6656 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a8d7cf not in the list
08-30 11:36:55.156  6540  6656 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-30 11:36:55.156  6540  6656 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-30 11:36:55.156  6540  6656 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-30 11:36:55.156  6540  6656 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-30 11:36:55.156  6540  6656 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-30 11:36:55.156  6540  6656 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-30 11:36:55.156  6540  6656 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-30 11:36:55.156  6540  6656 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-30 11:36:55.156  6540  6656 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-30 11:36:55.157  6540  6656 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-30 11:36:55.157  6540  6656 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-30 11:36:55.157  6540  6656 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-30 11:36:55.157  6540  6656 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-30 11:36:55.157  6540  6656 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-30 11:36:55.157  6540  6656 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-30 11:36:55.157  6540  6656 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-30 11:36:55.157  6540  6656 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-30 11:36:55.157  6540  6656 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-30 11:36:55.157  6540  6656 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-30 11:36:55.157  6540  6656 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-30 11:36:55.157  6540  6656 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-30 11:36:55.157  6540  6656 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-30 11:36:55.157  6540  6656 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-30 11:36:55.157  6540  6656 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-30 11:36:55.157  6540  6656 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-30 11:36:55.157  6540  6656 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-30 11:36:55.157  6540  6656 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-30 11:36:55.157  6540  6656 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-30 11:36:55.157  6540  6656 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-30 11:36:55.157  6540  6656 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-30 11:36:55.157  6540  6656 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-30 11:36:55.157  6540  6656 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 11:36:55.157  6540  6656 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 11:36:55.157  6540  6656 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 11:36:55.158  6540  6656 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 11:36:55.158  6540  6656 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:55.158  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:55.158  6540  6656 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30c6d02e not in the list
08-30 11:36:55.158  6540  6656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:36:55.158  6540  6656 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a8d7cf not in the list
08-30 11:36:55.158  6540  6656 D io.jxcore.node.ConnectivityMonitor: stop
08-30 11:36:55.158  6540  6656 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:55.158  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:55.158  6540  6656 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:55.158  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:55.159  6540  6656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 11:36:55.159  6540  6656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 11:36:55.159  6540  6656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:36:55.159  6540  6656 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a8d7cf not in the list
08-30 11:36:55.160  6540  6656 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-30 11:36:55.162  6540  6656 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 11:36:55.163  6540  6656 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 11:36:55.163  6540  6656 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 11:36:55.163  6540  6656 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 11:36:55.163  6540  6656 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 11:36:55.163  6540  6656 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 11:36:55.163  6540  6656 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 11:36:55.163  6540  6656 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 11:36:55.163  6540  6656 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 11:36:55.164  6540  6656 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 11:36:55.164  6540  6656 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 11:36:55.165  6540  6540 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 11:36:55.166  6540  6540 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 11:36:55.167  6540  6656 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 11:36:55.167  6540  6656 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 11:36:55.167  6540  6656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 11:36:55.167  6540  6656 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 11:36:55.167  6540  6656 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 11:36:55.170  6540  6656 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-30 11:36:55.170  1028  1912 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 11:36:55.173  6540  6656 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-30 11:36:55.187  6540  6656 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-30 11:36:55.194  6540  6656 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
08-30 11:36:55.195  6540  6656 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 11:36:55.195  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 11:36:55.196  6540  6656 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-30 11:36:55.196  6540  6656 I io.jxcore.node.ConnectionHelper: start: OK
08-30 11:36:55.198  6540  6656 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 11:36:55.198  6540  6656 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 11:36:55.198  6540  6656 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 11:36:55.199  6540  6656 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 11:36:55.199  6540  6656 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:55.199  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 11:36:55.199  6540  6656 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30c6d02e not in the list
08-30 11:36:55.199  6540  6656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:36:55.199  6540  6656 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a8d7cf not in the list
08-30 11:36:55.199  6540  6656 D io.jxcore.node.ConnectivityMonitor: stop
08-30 11:36:55.199  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:55.199  6540  6656 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-30 11:36:55.200  6540  6656 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 11:36:55.202  6540  6656 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 11:36:55.202  6540  6656 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 11:36:55.202  6540  6656 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 11:36:55.202  6540  6656 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 11:36:55.202  6540  6656 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 11:36:55.202  6540  6656 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 11:36:55.202  6540  6656 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 11:36:55.202  6540  6656 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 11:36:55.203  6540  6656 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 11:36:55.203  6540  6656 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 11:36:55.204  6540  6540 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 11:36:55.205  6540  6656 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 11:36:55.205  6540  6656 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 11:36:55.205  6540  6656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 11:36:55.205  6540  6656 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 11:36:55.205  6540  6656 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 11:36:55.205  6540  6540 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 11:36:55.209  6540  6656 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 11:36:55.209  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 11:36:55.210  6540  6656 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-30 11:36:55.210  6540  6656 I io.jxcore.node.ConnectionHelper: start: OK
08-30 11:36:55.212  6540  6656 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 11:36:55.212  6540  6656 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 11:36:55.212  6540  6656 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 11:36:55.212  6540  6656 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 11:36:55.212  6540  6656 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:55.212  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 11:36:55.212  6540  6656 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30c6d02e not in the list
08-30 11:36:55.212  6540  6656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:36:55.212  6540  6656 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a8d7cf not in the list
08-30 11:36:55.212  6540  6656 D io.jxcore.node.ConnectivityMonitor: stop
08-30 11:36:55.212  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:55.212  6540  6656 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:55.212  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:55.213  6540  6656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 11:36:55.213  6540  6656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 11:36:55.214  6540  6656 D BluetoothLeScanner: could not find callback wrapper
08-30 11:36:55.214  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 11:36:55.214  6540  6656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:36:55.214  6540  6656 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a8d7cf not in the list
08-30 11:36:55.215  6540  6656 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-30 11:36:55.216  6540  6656 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 11:36:55.218  6540  6656 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 11:36:55.218  6540  6656 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 11:36:55.218  6540  6656 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 11:36:55.218  6540  6656 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 11:36:55.218  6540  6656 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 11:36:55.218  6540  6656 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 11:36:55.218  6540  6656 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 11:36:55.218  6540  6656 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 11:36:55.219  6540  6656 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 11:36:55.219  6540  6656 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 11:36:55.220  6540  6540 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 11:36:55.221  6540  6540 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 11:36:55.221  6540  6656 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 11:36:55.221  6540  6656 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 11:36:55.221  6540  6656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 11:36:55.221  6540  6656 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 11:36:55.221  6540  6656 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 11:36:55.224  6540  6656 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 11:36:55.224  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 11:36:55.226  6540  6656 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-30 11:36:55.227  6540  6656 I io.jxcore.node.ConnectionHelper: start: OK
08-30 11:36:55.227  6540  6656 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 11:36:55.227  6540  6656 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 11:36:55.227  6540  6656 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 11:36:55.228  6540  6656 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 11:36:55.228  6540  6656 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 11:36:55.228  6540  6656 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 11:36:55.228  6540  6656 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 11:36:55.228  6540  6656 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:55.228  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 11:36:55.228  6540  6656 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30c6d02e not in the list
08-30 11:36:55.228  6540  6656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:36:55.228  6540  6656 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a8d7cf not in the list
08-30 11:36:55.228  6540  6656 D io.jxcore.node.ConnectivityMonitor: stop
08-30 11:36:55.228  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:55.229  6540  6656 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:55.229  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:55.229  6540  6656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 11:36:55.229  6540  6656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 11:36:55.230  6540  6656 D BluetoothLeScanner: could not find callback wrapper
08-30 11:36:55.230  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 11:36:55.230  6540  6656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:36:55.230  6540  6656 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a8d7cf not in the list
08-30 11:36:55.230  6540  6656 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-30 11:36:55.230  6540  6656 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 11:36:55.230  6540  6656 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 11:36:55.230  6540  6656 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 11:36:55.230  6540  6656 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 11:36:55.230  6540  6656 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:55.230  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:55.230  6540  6656 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30c6d02e not in the list
08-30 11:36:55.230  6540  6656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:36:55.230  6540  6656 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a8d7cf not in the list
08-30 11:36:55.230  6540  6656 D io.jxcore.node.ConnectivityMonitor: stop
08-30 11:36:55.231  6540  6656 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:55.231  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:55.231  6540  6656 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:55.231  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:55.231  6540  6656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 11:36:55.231  6540  6656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 11:36:55.231  6540  6656 D BluetoothLeScanner: could not find callback wrapper
08-30 11:36:55.231  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 11:36:55.231  6540  6656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:36:55.231  6540  6656 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a8d7cf not in the list
08-30 11:36:55.232  6540  6656 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-30 11:36:55.232  6540  6656 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 11:36:55.232  6540  6656 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 11:36:55.232  6540  6656 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 11:36:55.232  6540  6656 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 11:36:55.232  6540  6656 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:55.232  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:55.232  6540  6656 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30c6d02e not in the list
08-30 11:36:55.232  6540  6656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:36:55.232  6540  6656 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a8d7cf not in the list
,08-30 11:36:55.232  6540  6656 D io.jxcore.node.ConnectivityMonitor: stop
08-30 11:36:55.232  6540  6656 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:55.233  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:55.233  6540  6656 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:55.233  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:55.233  6540  6656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 11:36:55.233  6540  6656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 11:36:55.233  6540  6656 D BluetoothLeScanner: could not find callback wrapper
08-30 11:36:55.233  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 11:36:55.233  6540  6656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:36:55.233  6540  6656 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a8d7cf not in the list
08-30 11:36:55.234  6540  6656 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-30 11:36:55.234  6540  6656 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 11:36:55.234  6540  6656 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 11:36:55.234  6540  6656 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 11:36:55.234  6540  6656 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 11:36:55.234  6540  6656 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:55.234  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:55.234  6540  6656 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30c6d02e not in the list
08-30 11:36:55.234  6540  6656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:36:55.234  6540  6656 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a8d7cf not in the list
08-30 11:36:55.234  6540  6656 D io.jxcore.node.ConnectivityMonitor: stop
08-30 11:36:55.234  6540  6656 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:55.234  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:55.234  6540  6656 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:55.234  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:55.235  6540  6656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 11:36:55.235  6540  6656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 11:36:55.235  6540  6656 D BluetoothLeScanner: could not find callback wrapper
08-30 11:36:55.235  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 11:36:55.235  6540  6656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:36:55.235  6540  6656 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a8d7cf not in the list
08-30 11:36:55.236  6540  6656 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-30 11:36:55.236  6540  6656 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 11:36:55.236  6540  6656 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 11:36:55.236  6540  6656 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 11:36:55.236  6540  6656 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 11:36:55.236  6540  6656 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:55.236  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:55.236  6540  6656 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30c6d02e not in the list
08-30 11:36:55.236  6540  6656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:36:55.236  6540  6656 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a8d7cf not in the list
08-30 11:36:55.236  6540  6656 D io.jxcore.node.ConnectivityMonitor: stop
08-30 11:36:55.236  6540  6656 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:55.236  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:55.236  6540  6656 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:55.236  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:55.237  6540  6656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 11:36:55.237  6540  6656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 11:36:55.237  6540  6656 D BluetoothLeScanner: could not find callback wrapper
08-30 11:36:55.237  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 11:36:55.237  6540  6656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:36:55.237  6540  6656 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a8d7cf not in the list
08-30 11:36:55.238  6540  6656 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-30 11:36:55.239  6540  6656 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 11:36:55.239  6540  6656 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-30 11:36:55.239  6540  6656 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 11:36:55.239  6540  6656 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-30 11:36:55.239  6540  6656 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 11:36:55.239  6540  6656 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 11:36:55.239  6540  6656 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 11:36:55.239  6540  6656 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 11:36:55.240  6540  6656 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 11:36:55.240  6540  6656 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:55.240  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:55.240  6540  6656 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30c6d02e not in the list
08-30 11:36:55.240  6540  6656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:36:55.240  6540  6656 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a8d7cf not in the list
08-30 11:36:55.240  6540  6656 D io.jxcore.node.ConnectivityMonitor: stop
08-30 11:36:55.240  6540  6656 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:55.240  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:55.240  6540  6656 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:55.240  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:55.240  6540  6656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 11:36:55.240  6540  6656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 11:36:55.241  6540  6656 D BluetoothLeScanner: could not find callback wrapper
08-30 11:36:55.241  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 11:36:55.241  6540  6656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:36:55.241  6540  6656 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a8d7cf not in the list
08-30 11:36:55.241  6540  6656 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 11:36:55.241  6540  6656 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-30 11:36:55.241  6540  6656 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-30 11:36:55.243  6540  6656 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 11:36:55.243  6540  6656 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-30 11:36:55.243  6540  6656 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-30 11:36:55.243  6540  6656 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-30 11:36:55.243  6540  6656 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-30 11:36:55.243  6540  6656 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-30 11:36:55.243  6540  6656 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-30 11:36:55.243  6540  6656 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-30 11:36:55.243  6540  6656 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-30 11:36:55.243  6540  6656 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-30 11:36:55.243  6540  6656 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-30 11:36:55.243  6540  6656 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-30 11:36:55.243  6540  6656 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-30 11:36:55.243  6540  6656 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-30 11:36:55.243  6540  6656 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-30 11:36:55.243  6540  6656 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-30 11:36:55.243  6540  6656 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-30 11:36:55.243  6540  6656 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-30 11:36:55.243  6540  6656 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-30 11:36:55.244  6540  6656 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-30 11:36:55.244  6540  6656 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-30 11:36:55.244  6540  6656 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-30 11:36:55.244  6540  6656 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-30 11:36:55.244  6540  6656 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-30 11:36:55.244  6540  6656 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-30 11:36:55.244  6540  6656 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-30 11:36:55.244  6540  6656 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-30 11:36:55.244  6540  6656 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-30 11:36:55.244  6540  6656 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-30 11:36:55.244  6540  6656 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-30 11:36:55.244  6540  6656 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-30 11:36:55.244  6540  6656 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-30 11:36:55.244  6540  6656 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-30 11:36:55.244  6540  6656 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-30 11:36:55.244  6540  6656 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-30 11:36:55.244  6540  6656 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 11:36:55.244  6540  6656 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-30 11:36:55.244  6540  6656 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-30 11:36:55.244  6540  6656 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 11:36:55.244  6540  6656 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-30 11:36:55.244  6540  6656 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-30 11:36:55.246  6540  6656 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-30 11:36:55.247  6540  6656 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-30 11:36:55.247  6540  6656 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-30 11:36:55.248  6540  6656 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-30 11:36:55.248  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-30 11:36:55.248  6540  6656 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-30 11:36:55.248  6540  6656 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 11:36:55.248  6540  6656 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-30 11:36:55.248  6540  6656 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 11:36:55.248  6540  6656 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 11:36:55.248  6540  6656 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 11:36:55.249  6540  6656 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 11:36:55.249  6540  6656 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:55.249  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:55.249  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-30 11:36:55.249  6540  6656 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30c6d02e not in the list
08-30 11:36:55.249  6540  6656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:36:55.249  6540  6656 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a8d7cf not in the list
08-30 11:36:55.249  6540  6656 D io.jxcore.node.ConnectivityMonitor: stop
08-30 11:36:55.249  6540  6656 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:55.249  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:55.249  6540  6656 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:55.249  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:55.250  6540  6656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 11:36:55.250  6540  6656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 11:36:55.251  6540  6656 D BluetoothLeScanner: could not find callback wrapper
08-30 11:36:55.251  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 11:36:55.251  6540  6656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:36:55.251  6540  6656 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a8d7cf not in the list
08-30 11:36:55.251  6540  6656 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-30 11:36:55.252  6540  6656 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 11:36:55.252  6540  6656 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 11:36:55.252  6540  6656 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 11:36:55.252  6540  6656 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 11:36:55.252  6540  6656 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:55.252  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 11:36:55.253  6540  6656 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30c6d02e not in the list
08-30 11:36:55.253  6540  6656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:36:55.253  6540  6656 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a8d7cf not in the list
08-30 11:36:55.253  6540  6656 D io.jxcore.node.ConnectivityMonitor: stop
08-30 11:36:55.253  6540  6656 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:55.253  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:55.253  6540  6656 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:55.253  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:55.253  6540  6748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 816
08-30 11:36:55.254  6540  6656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 11:36:55.254  6540  6656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 11:36:55.255  6540  6656 D BluetoothLeScanner: could not find callback wrapper
08-30 11:36:55.255  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 11:36:55.255  6540  6656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:36:55.255  6540  6656 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a8d7cf not in the list
08-30 11:36:55.258  6540  6656 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-30 11:36:55.258  6540  6656 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 11:36:55.258  6540  6656 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 11:36:55.259  6540  6656 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 11:36:55.259  6540  6747 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 816)
08-30 11:36:55.259  6540  6747 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 816)
08-30 11:36:55.259  6540  6656 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 11:36:55.259  6540  6656 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:55.259  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:55.259  6540  6656 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30c6d02e not in the list
08-30 11:36:55.259  6540  6656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:36:55.259  6540  6656 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a8d7cf not in the list
08-30 11:36:55.259  6540  6656 D io.jxcore.node.ConnectivityMonitor: stop
08-30 11:36:55.259  6540  6656 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:55.259  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:55.260  6540  6656 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:55.260  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:55.261  6540  6656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 11:36:55.261  6540  6656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 11:36:55.262  6540  6656 D BluetoothLeScanner: could not find callback wrapper
08-30 11:36:55.262  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 11:36:55.262  6540  6656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:36:55.262  6540  6656 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a8d7cf not in the list
08-30 11:36:55.263  6540  6656 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-30 11:36:55.263  6540  6656 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-30 11:36:55.263  6540  6656 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-30 11:36:55.263  6540  6656 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-30 11:36:55.263  6540  6656 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-30 11:36:55.263  6540  6656 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-30 11:36:55.263  6540  6656 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-30 11:36:55.263  6540  6656 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-30 11:36:55.266  6540  6656 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-30 11:36:55.266  6540  6656 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-30 11:36:55.266  6540  6656 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-30 11:36:55.266  6540  6656 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-30 11:36:55.266  6540  6656 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 11:36:55.266  6540  6656 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 11:36:55.266  6540  6656 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 11:36:55.266  6540  6656 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 11:36:55.266  6540  6656 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:55.266  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:55.266  6540  6656 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30c6d02e not in the list
08-30 11:36:55.266  6540  6656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:36:55.266  6540  6656 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a8d7cf not in the list
08-30 11:36:55.266  6540  6656 D io.jxcore.node.ConnectivityMonitor: stop
08-30 11:36:55.266  6540  6656 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:55.266  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:55.266  6540  6656 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:55.266  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:55.267  6540  6656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 11:36:55.267  6540  6656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 11:36:55.267  6540  6656 D BluetoothLeScanner: could not find callback wrapper
08-30 11:36:55.267  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 11:36:55.267  6540  6656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:36:55.267  6540  6656 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a8d7cf not in the list
08-30 11:36:55.268  6540  6656 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 11:36:55.268  6540  6656 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:55.268  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:55.268  6540  6656 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30c6d02e not in the list
08-30 11:36:55.268  6540  6656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:36:55.268  6540  6656 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a8d7cf not in the list
08-30 11:36:55.268  6540  6656 D io.jxcore.node.ConnectivityMonitor: stop
08-30 11:36:55.268  6540  6656 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:55.268  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:55.269  6540  6656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:36:55.270  6540  6656 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a8d7cf not in the list
08-30 11:36:55.270  6540  6656 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 11:36:55.270  6540  6656 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:55.270  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:55.270  6540  6656 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30c6d02e not in the list
08-30 11:36:55.270  6540  6656 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 11:36:55.270  6540  6656 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 11:36:55.270  6540  6656 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 11:36:55.270  6540  6656 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 11:36:55.270  6540  6656 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:55.270  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:55.270  6540  6656 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30c6d02e not in the list
08-30 11:36:55.270  6540  6656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:36:55.270  6540  6656 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a8d7cf not in the list
08-30 11:36:55.270  6540  6656 D io.jxcore.node.ConnectivityMonitor: stop
08-30 11:36:55.270  6540  6656 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:55.270  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:55.270  6540  6656 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:55.270  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:55.271  6540  6656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 11:36:55.271  6540  6656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 11:36:55.272  6540  6656 D BluetoothLeScanner: could not find callback wrapper
08-30 11:36:55.272  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 11:36:55.272  6540  6656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:36:55.273  6540  6656 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a8d7cf not in the list
08-30 11:36:55.274  6540  6656 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-30 11:36:55.274  6540  6656 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 11:36:55.275  6540  6656 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-30 11:36:55.275  6540  6656 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-30 11:36:55.275  6540  6656 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-30 11:36:55.275  6540  6540 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-30 11:36:55.276  6540  6656 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-30 11:36:55.276  6540  6656 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-30 11:36:55.276  6540  6656 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 11:36:55.276  6540  6656 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-30 11:36:55.276  6540  6656 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-30 11:36:55.276  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-30 11:36:55.276  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:55.276  6540  6656 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-30 11:36:55.277  6540  6540 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-30 11:36:55.277  6540  6656 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30c6d02e not in the list
08-30 11:36:55.277  6540  6656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:36:55.277  6540  6656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 11:36:55.277  6540  6656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 11:36:55.277  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 11:36:55.278  6540  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-30 11:36:55.278  6540  6749 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-30 11:36:55.279  6540  6656 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-30 11:36:55.279  6540  6656 D BluetoothLeScanner: could not find callback wrapper
08-30 11:36:55.279  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 11:36:55.279  6540  6656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-30 11:36:55.279  6540  6656 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:55.279  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:55.280  6540  6656 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 11:36:55.280  6540  6540 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 11:36:55.280  6540  6540 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 11:36:55.280  6540  6540 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 11:36:55.280  6540  6656 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a8d7cf not in the list
08-30 11:36:55.280  6540  6656 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 11:36:55.280  6540  6656 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 11:36:55.280  6540  6656 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 11:36:55.281  6540  6540 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-30 11:36:55.281  6540  6656 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 11:36:55.281  6540  6656 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:55.281  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:55.281  6540  6656 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30c6d02e not in the list
08-30 11:36:55.281  6540  6656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:36:55.281  6540  6656 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a8d7cf not in the list
08-30 11:36:55.281  6540  6656 D io.jxcore.node.ConnectivityMonitor: stop
08-30 11:36:55.281  6540  6656 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:55.281  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:55.282  6540  6656 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:55.282  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:55.282  6540  6656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 11:36:55.282  6540  6656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 11:36:55.282  6540  6656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:36:55.282  6540  6656 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a8d7cf not in the list
08-30 11:36:55.283  6540  6656 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-30 11:36:55.283  6540  6656 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-30 11:36:55.283  6540  6656 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-30 11:36:55.283  6540  6656 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 11:36:55.283  6540  6656 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 11:36:55.283  6540  6656 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 11:36:55.283  6540  6656 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 11:36:55.285  6540  6656 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 11:36:55.285  6540  6656 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:55.285  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 11:36:55.285  6540  6656 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30c6d02e not in the list
08-30 11:36:55.285  6540  6656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:36:55.285  6540  6656 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a8d7cf not in the list
08-30 11:36:55.285  6540  6656 D io.jxcore.node.ConnectivityMonitor: stop
08-30 11:36:55.285  6540  6656 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:55.285  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:55.285  6540  6656 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:55.285  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:55.286  6540  6656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 11:36:55.286  6540  6656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 11:36:55.286  6540  6656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:36:55.286  6540  6656 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a8d7cf not in the list
08-30 11:36:55.287  1028  2005 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 11:36:55.288  1028  1932 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 11:36:55.288  1028  1912 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 11:36:55.289  6540  6656 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 11:36:55.289  6540  6656 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 11:36:55.289  6540  6656 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 11:36:55.289  6540  6656 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 11:36:55.289  6540  6656 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:55.289  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:55.289  6540  6656 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30c6d02e not in the list
08-30 11:36:55.289  6540  6656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:36:55.289  6540  6656 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a8d7cf not in the list
08-30 11:36:55.289  6540  6656 D io.jxcore.node.ConnectivityMonitor: stop
08-30 11:36:55.289  6540  6656 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:55.289  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:55.289  6540  6656 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:55.289  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:55.290  6540  6656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 11:36:55.290  6540  6656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 11:36:55.290  6540  6656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:36:55.290  6540  6656 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a8d7cf not in the list
08-30 11:36:55.290  6540  6656 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 11:36:55.290  6540  6656 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 11:36:55.290  6540  6656 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 11:36:55.291  6540  6656 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 11:36:55.291  6540  6656 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:55.291  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:55.291  6540  6656 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30c6d02e not in the list
08-30 11:36:55.291  6540  6656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:36:55.291  6540  6656 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a8d7cf not in the list
08-30 11:36:55.291  6540  6656 D io.jxcore.node.ConnectivityMonitor: stop
08-30 11:36:55.291  6540  6656 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:55.291  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:55.291  6540  6656 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:36:55.291  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:36:55.292  6540  6656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 11:36:55.292  6540  6656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 11:36:55.292  6540  6656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:36:55.292  6540  6656 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a8d7cf not in the list
08-30 11:36:55.293  6540  6656 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-30 11:36:55.293  6540  6656 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-30 11:36:55.293  6540  6656 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-30 11:36:55.293  6540  6656 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-30 11:36:55.293  6540  6656 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-30 11:36:55.293  6540  6656 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-30 11:36:55.294  6540  6656 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-30 11:36:55.294  6540  6656 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-30 11:36:55.295  6540  6656 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-30 11:36:55.295  6540  6656 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-30 11:36:55.295  6540  6656 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-30 11:36:55.295  6540  6656 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-30 11:36:55.295  6540  6656 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-30 11:36:55.295  6540  6656 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-30 11:36:55.296  6540  6656 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-30 11:36:55.296  6540  6656 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-30 11:36:55.296  6540  6656 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-30 11:36:55.296  6540  6656 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-30 11:36:55.296  6540  6656 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-30 11:36:55.297  6540  6656 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-30 11:36:55.297  6540  6656 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 11:36:55.297  6540  6656 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@32b8c3f4 added. We now have 2 listener(s)
08-30 11:36:55.297  6540  6656 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 11:36:55.301  6540  6656 D BluetoothAdapter: enable(): BT is already enabled..!
08-30 11:36:55.301  1028  1914 D WifiServiceImplEx: setWifiEnabled: true pid=6540, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-30 11:36:55.302  1028  1914 D WifiService: setWifiEnabled: true pid=6540, uid=10118
08-30 11:36:55.302  1028  1914 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-30 11:36:55.304  6540  6656 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 11:36:55.304  6540  6656 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2717f71d added. We now have 3 listener(s)
08-30 11:36:55.304  6540  6656 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 11:36:55.308  6540  6656 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 11:36:55.308  6540  6656 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2fed3d92 added. We now have 4 listener(s)
08-30 11:36:55.308  6540  6656 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 11:36:55.309  6540  6656 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 11:36:55.309  6540  6656 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@21b1e363 added. We now have 5 listener(s)
08-30 11:36:55.309  6540  6656 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 11:36:55.312  1028  1043 D WifiServiceImplEx: setWifiEnabled: false pid=6540, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-30 11:36:55.312  1028  1043 D WifiService: setWifiEnabled: false pid=6540, uid=10118
08-30 11:36:55.312  1028  1043 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-30 11:36:55.320  1028  1383 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-30 11:36:55.320  1028  1383 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-30 11:36:55.320  1028  1383 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-30 11:36:55.320  1028  1383 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-30 11:36:55.320  1028  1028 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-30 11:36:55.320  1028  1383 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-30 11:36:55.320  1028  1383 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-30 11:36:55.321  1028  1028 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-30 11:36:55.321  1028  1028 D Ulp_jni : JNI:system_update. Event-4
08-30 11:36:55.321  1028  1383 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-30 11:36:55.321  1028  1383 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-30 11:36:55.322  1028  2040 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 11:36:55.322  1028  2040 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@340cd740 mBinding = false
08-30 11:36:55.322  1028  1383 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-30 11:36:55.323  1028  1383 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-30 11:36:55.329  1028  1383 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-30 11:36:55.329  1028  1379 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 11:36:55.329  1028  1379 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 11:36:55.330  1028  1383 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-30 11:36:55.330  1028  1110 D BluetoothManagerService: Message: 2
08-30 11:36:55.330  1028  1028 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-30 11:36:55.330  1028  1110 D BluetoothManagerService: Sending off request.
08-30 11:36:55.331  1028  1028 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-30 11:36:55.331  1028  1028 D Ulp_jni : JNI:system_update. Event-4
08-30 11:36:55.331  3895  3912 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-30 11:36:55.331  2685  2685 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-30 11:36:55.333  6540  6656 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 11:36:55.333  3895  3975 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-30 11:36:55.333  3895  3975 D BluetoothAdapterProperties: Setting state to 13
08-30 11:36:55.333  3895  3975 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-30 11:36:55.334  1028  1383 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-30 11:36:55.334  1028  1383 D WifiNative-wlan0: doBoolean: SET ps 1
08-30 11:36:55.335  3895  3975 D BluetoothAdapterProperties: onBluetoothDisable()
08-30 11:36:55.335  3895  3975 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-30 11:36:55.336  1028  1383 D WifiNative-wlan0: SET ps 1: returned true
08-30 11:36:55.341  6540  6656 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 11:36:55.341  6540  6656 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 11:36:55.341  6540  6656 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 11:36:55.341  6540  6656 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 11:36:55.341  6540  6656 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 11:36:55.341  6540  6656 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 11:36:55.341  6540  6656 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 11:36:55.341  6540  6656 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 11:36:55.341  6540  6656 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 11:36:55.341  6540  6656 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 11:36:55.341  6540  6656 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 11:36:55.341  6540  6656 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 11:36:55.345  6540  6540 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 11:36:55.347  6540  6540 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 11:36:55.352  1028  2858 D DhcpStateMachine: RunningState{ when=-16ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,08-30 11:36:55.357   315   891 D CommandListener: Clearing all IP addresses on wlan0
08-30 11:36:55.382  1028  1110 D BluetoothManagerService: Message: 60
08-30 11:36:55.382  1028  1110 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-30 11:36:55.382  1028  1110 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
,08-30 11:36:55.384  1028  1437 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-30 11:36:55.384  1028  1437 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
08-30 11:36:55.384  1933  1933 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-30 11:36:55.385  1595  1595 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-30 11:36:55.387  3895  3895 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-30 11:36:55.387  3895  3895 D BluetoothMapService: STATE_TURNING_OFF
08-30 11:36:55.387  3895  3895 V BluetoothMapService: Handler(): got msg=4
08-30 11:36:55.387  3895  3895 D BluetoothMapService: MAP Service closeService in
08-30 11:36:55.387  3895  3895 D BluetoothMapMasInstance: MAP Service shutdown
08-30 11:36:55.388  3895  4180 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-30 11:36:55.388  3895  4180 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 11:36:55.388  3895  4180 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-30 11:36:55.388  3895  4180 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-30 11:36:55.388  3895  4180 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-30 11:36:55.388  3895  4180 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-30 11:36:55.388  3895  4180 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-30 11:36:55.388  3895  4180 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-30 11:36:55.388  3895  3895 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-30 11:36:55.388  3895  3895 V BluetoothMapService: MAP Service closeService out
08-30 11:36:55.389  3895  3895 V BtOppService: Receiver DISABLED_ACTION 
08-30 11:36:55.389  3895  3895 I BtOppRfcommListener: stopping Accept Thread
08-30 11:36:55.389  3895  3895 V BtOppRfcommListener: close mBtServerSocket
08-30 11:36:55.389  3895  3895 V BtOppRfcommListener: waiting for thread to terminate
08-30 11:36:55.389  3895  4232 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 11:36:55.389  3895  4232 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-30 11:36:55.389  3895  3895 V BtOppRfcommListener: done waiting for thread to terminate
08-30 11:36:55.391  6540  6540 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 11:36:55.391  6540  6540 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 11:36:55.391  6540  6540 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 11:36:55.391  6540  6540 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 11:36:55.391  6540  6540 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 11:36:55.391  6540  6540 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 11:36:55.391  6540  6540 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 11:36:55.391  6540  6540 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 11:36:55.391  6540  6540 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 11:36:55.391  6540  6540 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager:, Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 11:36:55.391  6540  6540 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 11:36:55.392  6540  6540 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 11:36:55.392  6540  6540 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 11:36:55.392  6540  6540 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 11:36:55.392  6540  6540 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 11:36:55.392  6540  6540 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 11:36:55.392  6540  6540 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 11:36:55.392  6540  6540 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 11:36:55.392  6540  6540 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 11:36:55.392  6540  6540 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 11:36:55.393  6540  6540 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 11:36:55.393  6540  6540 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 11:36:55.427  1028  2024 I art     : Explicit concurrent mark sweep GC freed 25663(1318KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/64MB, paused 1.577ms total 90.314ms
,08-30 11:36:55.432  1028  1106 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6767 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-30 11:36:55.437  3895  3895 V BtOppService: onDestroy
08-30 11:36:55.438  3895  3895 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-30 11:36:55.439  1028  1437 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-30 11:36:55.439  1028  1437 D DSQN    : disableDataServiceNotify
08-30 11:36:55.439  1028  1383 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 11:36:55.439  1028  1437 D DSQN    : stop dsqn bin
08-30 11:36:55.439  1028  1383 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 11:36:55.439  1028  1379 D LGWifiP2pService: InactiveState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-30 11:36:55.439  1028  1379 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-30 11:36:55.439  1028  1383 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 11:36:55.440  3895  3979 D BluetoothAdapterProperties: Scan Mode:20
08-30 11:36:55.440  1028  1379 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@2c09a895
08-30 11:36:55.440  3895  3975 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-30 11:36:55.440  1028  1379 D LGWifiP2pService: P2pDisablingState
08-30 11:36:55.440  1028  1379 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-30 11:36:55.440  3895  4181 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 11:36:55.440  1028  1379 D LGWifiP2pService: p2p socket connection lost
08-30 11:36:55.440  1028  1379 D LGWifiP2pService: P2pDisabledState
08-30 11:36:55.440  1028  2005 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
08-30 11:36:55.440  3895  3975 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-30 11:36:55.441  3895  4081 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-30 11:36:55.441  1028  2857 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-30 11:36:55.441  1028  2857 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-30 11:36:55.441  1028  2857 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-30 11:36:55.441  1028  1383 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 11:36:55.441  1028  2857 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-30 11:36:55.441  1028  2857 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on <unknown ssid>
08-30 11:36:55.441  1028  1383 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 11:36:55.441  3895  4235 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-30 11:36:55.442  3895  4081 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-30 11:36:55.442  3895  4233 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 11:36:55.442  1028  1383 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 11:36:55.444  3895  4081 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 11:36:55.444  3895  4081 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-30 11:36:55.444  3895  4081 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 11:36:55.444  3895  4081 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 11:36:55.444  3895  4081 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 11:36:55.444  3895  4081 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-30 11:36:55.444  3895  4081 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 11:36:55.444  3895  4081 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 11:36:55.444  3895  4081 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 11:36:55.444  3895  4081 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-30 11:36:55.444  3895  4081 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-30 11:36:55.444  3895  4081 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-30 11:36:55.448  1028  1437 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-30 11:36:55.448  1028  1437 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 11:36:55.448  1028  1437 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 11:36:55.448  1028  1437 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 11:36:55.448  1028  1437 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-30 11:36:55.449  1028  1437 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-30 11:36:55.449  1028  1437 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-30 11:36:55.449  1595  2063 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-30 11:36:55.450  1028  1437 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-30 11:36:55.451  1933  1933 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-30 11:36:55.451  1028  1028 D WifiHS20: hidePasspointNotification off =false
,08-30 11:36:55.453  1028  1028 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 11:36:55.453  1028  1028 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 11:36:55.453  1028  1028 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-30 11:36:55.453  1028  1383 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-30 11:36:55.454  1028  1028 D WifiHS20: hidePasspointNotification off =false
08-30 11:36:55.455  1028  1383 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 11:36:55.456  1028  1028 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 11:36:55.456  1028  1028 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 11:36:55.456  1028  1028 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-30 11:36:55.456  1028  1383 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 11:36:55.456  1028  1028 D WifiScanningService: SCAN_AVAILABLE : 1
08-30 11:36:55.456  1028  1383 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 11:36:55.456  1028  1028 D RttService: SCAN_AVAILABLE : 1
08-30 11:36:55.456  1028  1547 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-30 11:36:55.457  1028  1548 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-30 11:36:55.457  1028  1383 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-30 11:36:55.457  1028  1379 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 11:36:55.457  1028  1379 D LGWifiP2pService: DefaultState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 11:36:55.458  1933  1933 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-30 11:36:55.458  1933  1933 D WfdsService: WifiP2pState is changed : false
08-30 11:36:55.458  1933  2352 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-30 11:36:55.458  1933  2352 D WfdsService: Set the WFDS Monitor: false
08-30 11:36:55.458  1028  1383 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-30 11:36:55.458  2685  2685 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-30 11:36:55.459  1933  2352 D WfdsMonitor: WFDS Monitor is stopped
08-30 11:36:55.459  1933  2352 D WfdsService: STATE : WfdsDisabledState - enter
08-30 11:36:55.459  1933  2353 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-30 11:36:55.459  1933  2735 D CtrlSupplicant: Received on exit socket, terminate
08-30 11:36:55.459  1933  2735 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-30 11:36:55.459  1933  2735 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-30 11:36:55.459  1933  2735 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-30 11:36:55.459  1028  1383 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-30 11:36:55.459  1028  1383 D WifiNative-wlan0: doBoolean: SET ps 1
08-30 11:36:55.460  1933  2352 W WfdsService: DefaultState - msg [9445378] is not handled
08-30 11:36:55.460  1028  1383 D WifiNative-wlan0: SET ps 1: returned true
08-30 11:36:55.460   315   891 D CommandListener: Clearing all IP addresses on wlan0
08-30 11:36:55.460   315  6785 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-30 11:36:55.460  1028  1437 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-3,0 11:36:55.461  1028  1437 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-30 11:36:55.461  1595  1595 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 11:36:55.461  1595  1595 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 11:36:55.461  1028  1108 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-30 11:36:55.461  1028  1028 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-30 11:36:55.461  1028  1028 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-30 11:36:55.461  1595  1595 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 11:36:55.462  1028  1028 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-30 11:36:55.462  1028  1028 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-30 11:36:55.462  1028  2857 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
08-30 11:36:55.462  1028  2857 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-13ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-30 11:36:55.463  1028  1378 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-30 11:36:55.463  1595  1595 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 11:36:55.463  1595  1595 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 11:36:55.463  1028  1437 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-30 11:36:55.463  1028  1437 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 11:36:55.463  1028  1437 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 11:36:55.464  1028  1437 D NetworkManagementService: Removing idletimer
08-30 11:36:55.464  1843  1843 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 11:36:55.464  1843  1843 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-30 11:36:55.464  1028  1437 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 11:36:55.464  1595  1595 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 11:36:55.464  1028  1437 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-30 11:36:55.465  1028  2857 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-13ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-30 11:36:55.465  1028  2857 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
,08-30 11:36:55.467  6373  6373 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 11:36:55.468  1028  1378 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-30 11:36:55.469  1028  1028 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-30 11:36:55.469  1028  1028 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-30 11:36:55.469  1028  1028 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-30 11:36:55.469  1028  1028 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-30 11:36:55.500  1028  1912 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6788 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-30 11:36:55.505  1028  1383 D WifiNative-p2p0: doBoolean: TERMINATE
08-30 11:36:55.506  1028  1028 D WifiHS20: hidePasspointNotification off =false
08-30 11:36:55.506  1028  1383 D WifiNative-p2p0: TERMINATE: returned true
08-30 11:36:55.506  1028  1383 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-30 11:36:55.506  1028  1383 E WifiStateMachine: useWiFiOffloading() : false
08-30 11:36:55.506  1028  1383 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-30 11:36:55.506  6540  6540 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 11:36:55.507  1028  1028 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 11:36:55.507  1028  1028 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 11:36:55.507  1028  1028 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-30 11:36:55.508  1028  1383 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 11:36:55.508  1028  1383 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 11:36:55.509  1933  1933 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-30 11:36:55.510  6540  6540 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 11:36:55.510  6540  6540 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 11:36:55.510  6540  6540 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 11:36:55.510  6540  6540 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 11:36:55.510  6540  6540 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 11:36:55.510  6540  6540 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 11:36:55.510  6540  6540 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 11:36:55.510  6540  6540 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 11:36:55.510  6540  6540 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 11:36:55.510  1028  1028 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-30 11:36:55.510  6540  6540 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 11:36:55.510  6540  6540 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 11:36:55.511  1028  1028 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 11:36:55.511  1028  1028 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-30 11:36:55.515  6540  6540 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 11:36:55.515  6540  6540 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 11:36:55.515  6540  6540 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 11:36:55.515  6540  6540 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 11:36:55.515  6540  6540 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 11:36:55.515  6540  6540 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 11:36:55.515  6540  6540 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 11:36:55.515  6540  6540 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 11:36:55.515  6540  6540 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 11:36:55.515  6540  6540 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 11:36:55.515  6540  6540 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 11:36:55.516  6540  6540 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 11:36:55.524  1595  1595 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-30 11:36:55.525  1595  1595 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 11:36:55.525  1595  1595 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-30 11:36:55.529  6767  6767 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 11:36:55.530  6767  6767 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
08-30 11:36:55.531  6767  6767 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-30 11:36:55.531  6767  6767 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
08-30 11:36:55.533  6767  6767 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-30 11:36:55.534  6767  6767 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-30 11:36:55.539  1595  1595 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-30 11:36:55.540  1595  1595 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 11:36:55.540  1595  1595 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 11:36:55.542  1595  1595 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-30 11:36:55.542  1595  1595 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 11:36:55.543  1595  1595 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-30 11:36:55.557  6788  6788 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,08-30 11:36:55.561  1595  1595 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 11:36:55.562  6788  6788 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-30 11:36:55.562  6788  6788 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-30 11:36:55.563  1028  1914 I ActivityManager: Killing 5972:com.android.providers.calendar/u0a14 (adj 15): empty #17
08-30 11:36:55.565  2685  2685 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-30 11:36:55.566  2685  2685 I wpa_supplicant: monitor socket send errors count : 1
08-30 11:36:55.566  2685  2685 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1933-2\x00 that cannot receive messages
08-30 11:36:55.566  1028  2714 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-30 11:36:55.566  1028  2714 D WifiMonitor: Dropping event because (p2p0) is stopped
08-30 11:36:55.577  1028  2858 D DhcpStateMachine: StoppedState
08-30 11:36:55.577  1028  2858 D DhcpStateMachine: StoppedState{ when=-117ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,08-30 11:36:55.596  1028  1043 W libprocessgroup: failed to open /acct/uid_10014/pid_5972/cgroup.procs: No such file or directory
,08-30 11:36:55.602  1028  1383 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-30 11:36:55.603  1028  1383 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-30 11:36:55.604  2685  2685 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-30 11:36:55.605  1028  2714 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-30 11:36:55.605  1028  2714 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-30 11:36:55.605  1028  2714 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-30 11:36:55.605  1028  2714 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-30 11:36:55.605  1028  1110 D Tethering: InitialState.processMessage what=4
08-30 11:36:55.605  1028  1383 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=116635
08-30 11:36:55.605  1028  1383 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=116635
08-30 11:36:55.606  1028  1110 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-30 11:36:55.606  1028  1383 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-30 11:36:55.607  1028  2714 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 11:36:55.607  1028  2714 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-30 11:36:55.607  2685  2685 W wpa_supplicant: USIM:  scard_deinit function
08-30 11:36:55.607  1028  1383 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-30 11:36:55.607  1028  1383 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=116637  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-30 11:36:55.608  1028  1383 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=116637  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
,08-30 11:36:55.651  6767  6767 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-30 11:36:55.657  3895  3895 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-30 11:36:55.657  3895  3895 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 11:36:55.657  3895  3895 V BluetoothPbapReceiver: ***********state = 13
08-30 11:36:55.659  3895  3895 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-30 11:36:55.661  3895  3895 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 11:36:55.661  3895  3895 V BluetoothPbapService: state: 13
08-30 11:36:55.661  3895  3895 V BluetoothPbapService: Pbap Service closeService in
08-30 11:36:55.662  2195  2195 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-30 11:36:55.662  3895  3895 V BluetoothPbapService: successfully stopped pbap service
08-30 11:36:55.663  3895  3895 V BluetoothPbapService: Pbap Service closeService out
08-30 11:36:55.663  3895  3895 V BluetoothPbapService: Pbap Service onDestroy
08-30 11:36:55.663  3895  3895 V BluetoothPbapService: Pbap Service closeService in
08-30 11:36:55.663  3895  3895 V BluetoothPbapService: Pbap Service closeService out
08-30 11:36:55.663  3895  3895 D LGBluetoothPbapAdapter: [BTUI] cleanup
,08-30 11:36:55.679  6767  6767 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 11:36:55.689  1028  1878 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6810 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-30 11:36:55.716  6767  6767 D LgDataFeature: LgDataFeature() Constructor: none
08-30 11:36:55.717  6767  6767 D LgDataFeature: LgDataFeature() Constructor Done, null
08-30 11:36:55.722  2685  2685 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-30 11:36:55.722  1028  2714 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-30 11:36:55.722  1028  2714 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
08-30 11:36:55.723  1028  2714 D WifiMonitor: Disconnecting from the supplicant, no more events
08-30 11:36:55.725  1028  1383 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
,08-30 11:36:55.727  6767  6767 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 11:36:55.729  1933  1933 D WfdsService: Supplicant Connection state is changed : false
08-30 11:36:55.730  1933  2352 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-30 11:36:55.730  1933  2352 D WfdsService: Set the WFDS Monitor: false
08-30 11:36:55.730  1933  2352 D WfdsMonitor: WFDS Monitor is stopped
08-30 11:36:55.730  1028  1383 D WifiOffDelayIfNotUsed: stopMonitoring
08-30 11:36:55.730  1028  1383 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-30 11:36:55.730  1028  1383 E WifiStateMachine: useWiFiOffloading() : false
08-30 11:36:55.730  1028  1383 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-30 11:36:55.732  1933  1933 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-30 11:36:55.733  1028  1028 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-30 11:36:55.733  1028  1395 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-30 11:36:55.733  1028  1395 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-30 11:36:55.733  1595  1595 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 11:36:55.734  2500  2500 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 11:36:55.734  6540  6540 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 11:36:55.735  6540  6540 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 11:36:55.740  1028  1110 D BluetoothManagerService: Message: 20
08-30 11:36:55.740  1028  1110 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3cf7573b:true
,08-30 11:36:55.747  2124  2124 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19988
08-30 11:36:55.750  1028  1110 D BluetoothManagerService: Message: 30
08-30 11:36:55.756  1028  1110 D BluetoothManagerService: Message: 30
,08-30 11:36:55.759  6767  6767 D LocalBluetoothProfileManager: Adding local MAP profile
08-30 11:36:55.761  6767  6767 D BluetoothMap: Create BluetoothMap proxy object
08-30 11:36:55.761  1028  1110 D BluetoothManagerService: Message: 30
08-30 11:36:55.764  1028  1110 D BluetoothManagerService: Message: 30
08-30 11:36:55.766  6767  6767 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
08-30 11:36:55.767  6767  6767 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
,08-30 11:36:55.780  6767  6767 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
,08-30 11:36:55.781  6540  6540 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-30 11:36:55.783  6767  6767 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
08-30 11:36:55.787  6810  6810 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-30 11:36:55.787  6810  6810 W LG Account v2.2: No ProfileInfo entries
08-30 11:36:55.787  6810  6810 I LG Account v2.2: isEnabled: false
08-30 11:36:55.788  6810  6810 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-30 11:36:55.788  6810  6810 I Feature : [Lifetracker]Country: EU
08-30 11:36:55.788  6810  6810 I Feature : [Lifetracker]Operator: OPEN
08-30 11:36:55.788  6810  6810 I Feature : [Lifetracker]Ranking support: false
08-30 11:36:55.788  6810  6810 I Feature : [Lifetracker]Comfort support: false
08-30 11:36:55.788  6810  6810 I Feature : [Lifetracker]Accessory: true
08-30 11:36:55.788  6810  6810 I Feature : [Lifetracker]Health device: true
08-30 11:36:55.788  6810  6810 I Feature : [Lifetracker]Extra Pedometer: false
08-30 11:36:55.788  6810  6810 I Feature : [Lifetracker]Blood glucose device: false
08-30 11:36:55.788  6810  6810 I Feature : [Lifetracker]Device Number: 3
08-30 11:36:55.790  1028  2024 I ActivityManager: Killing 6295:com.android.defcontainer/u0a4 (adj 15): empty #17
,08-30 11:36:55.818  1028  1914 W libprocessgroup: failed to open /acct/uid_10004/pid_6295/cgroup.procs: No such file or directory
,08-30 11:36:55.818  6767  6767 D DockEventReceiver: finishStartingService: stopping service
08-30 11:36:55.831  6767  6767 D BluetoothInputDevice: Proxy object connected
08-30 11:36:55.832  6767  6767 D HidProfile: Bluetooth service connected
,08-30 11:36:55.833  6767  6767 D BluetoothPan: BluetoothPAN Proxy object connected
,08-30 11:36:55.834  6767  6767 D PanProfile: Bluetooth service connected
08-30 11:36:55.835  6767  6767 D BluetoothMap: Proxy object connected
08-30 11:36:55.836  6767  6767 D MapProfile: Bluetooth service connected
08-30 11:36:55.837  6767  6767 D BluetoothMap: getConnectedDevices()
08-30 11:36:55.837  6767  6767 D BluetoothMap: Bluetooth is Not enabled
08-30 11:36:55.837  6767  6767 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-30 11:36:55.841  6767  6767 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-30 11:36:55.845  6767  6767 D BluetoothPermissionRequest: onReceive
,08-30 11:36:55.851  6767  6767 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-30 11:36:55.858  1028  2040 I ActivityManager: Killing 6423:com.google.android.partnersetup/u0a8 (adj 15): empty #17
,08-30 11:36:55.863  6767  6767 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-30 11:36:55.919  3895  3895 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
,08-30 11:36:55.920  3895  3895 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-30 11:36:55.921  3895  3895 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-30 11:36:55.922  1028  1968 W libprocessgroup: failed to open /acct/uid_10008/pid_6423/cgroup.procs: No such file or directory
,08-30 11:36:56.014  1028  2040 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6836 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,08-30 11:36:56.022  3895  3895 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-30 11:36:56.023  3895  3895 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-30 11:36:56.024  3895  3895 V BluetoothFtpService: Ftp Service onStartCommand
08-30 11:36:56.025  3895  3895 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 11:36:56.025  3895  3895 V BluetoothFtpService: Ftp Service closeService
08-30 11:36:56.026  3895  3895 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-30 11:36:56.027  3895  3895 V BluetoothFtpService: successfully stopped ftp service
,08-30 11:36:56.027  3895  3895 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-30 11:36:56.028  3895  3895 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-30 11:36:56.028  3895  3895 V BluetoothSapReceiver: SapReceiver onReceive 
08-30 11:36:56.028  3895  3895 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 11:36:56.028  3895  3895 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-30 11:36:56.028  3895  3895 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-30 11:36:56.030  3895  3895 V BluetoothFtpService: Ftp Service onDestroy
08-30 11:36:56.030  3895  3895 V BluetoothFtpService: Ftp Service closeService
08-30 11:36:56.086  1028  1567 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6853 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-30 11:36:56.093  3895  3895 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 11:36:56.093  3895  3895 V BluetoothSapService: state: 13
08-30 11:36:56.093  3895  3895 V BluetoothSapService: Stopping SAP server process
08-30 11:36:56.095  3895  3895 V BluetoothSapService: Sap Service closeSapService in
08-30 11:36:56.095  3895  3895 V BluetoothSapService: Close listen Socket : 
08-30 11:36:56.095  3895  3895 V BluetoothSapService: Close rfcomm Socket : 
08-30 11:36:56.095  3895  3895 V BluetoothSapService: Close sapd  Socket : 
08-30 11:36:56.098  3895  3895 V BluetoothSapService: Sap Service closeSapService out
08-30 11:36:56.098  3895  3895 V BluetoothSapService: Sap Service onDestroy
08-30 11:36:56.098  3895  3895 V BluetoothSapService: Sap Service closeSapService in
08-30 11:36:56.098  3895  3895 V BluetoothSapService: Close listen Socket : 
08-30 11:36:56.098  3895  3895 V BluetoothSapService: Close rfcomm Socket : 
08-30 11:36:56.098  3895  3895 V BluetoothSapService: Close sapd  Socket : 
08-30 11:36:56.099  3895  3895 V BluetoothSapService: Sap Service closeSapService out
,08-30 11:36:56.109   344   344 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 466us total 19.993ms
08-30 11:36:56.127   344   344 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 369us total 17.882ms
,08-30 11:36:56.135  6836  6836 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-30 11:36:56.143   344   344 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 292us total 15.387ms
08-30 11:36:56.157  6853  6853 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-30 11:36:56.160  6836  6836 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
08-30 11:36:56.174  1028  2040 I ActivityManager: Killing 6094:com.lge.appbox.client/u0a11 (adj 15): empty #17
,08-30 11:36:56.197  6836  6836 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,08-30 11:36:56.198  6836  6836 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-30 11:36:56.199  6836  6836 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-30 11:36:56.199  6836  6836 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-30 11:36:56.200  6836  6836 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-30 11:36:56.202  6836  6836 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-30 11:36:56.208  6836  6836 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-30 11:36:56.226  1028  1912 W libprocessgroup: failed to open /acct/uid_10011/pid_6094/cgroup.procs: No such file or directory
,08-30 11:36:56.239  6836  6836 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-30 11:36:56.244  6836  6836 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 11:36:56.267  6836  6836 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-30 11:36:56.272  6836  6836 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
,08-30 11:36:56.279  6836  6836 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-30 11:36:56.279  6373  6373 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 11:36:56.288  6788  6788 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,08-30 11:36:56.288  6788  6788 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-30 11:36:56.288  6788  6788 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-30 11:36:56.293  6767  6767 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 11:36:56.300  6767  6767 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 11:36:56.317  6836  6836 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 11:36:56.318  6836  6836 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-30 11:36:56.320  6836  6836 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-30 11:36:56.325  6373  6373 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 11:36:56.331  6788  6788 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-30 11:36:56.332  6788  6788 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-30 11:36:56.332  6788  6788 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-30 11:36:56.340  6767  6767 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 11:36:56.352  6767  6767 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 11:36:56.366  6836  6836 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 11:36:56.367  6836  6836 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-30 11:36:56.370  6836  6836 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-30 11:36:56.438  1028  2005 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6876 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
08-30 11:36:56.446  3895  4083 I bt_lpm  : LPM is already off!!!
08-30 11:36:56.446  3895  3979 D bt_hci_bdroid: cleanup
08-30 11:36:56.446  3895  4159 I bt_userial_mct: exiting userial_read_thread
08-30 11:36:56.446  3895  4159 D bt_userial_mct: Leaving userial_evt_read_thread()
08-30 11:36:56.446  3895  4081 W bt-btif : ag scb idx 1 not allocated
08-30 11:36:56.446  3895  4081 E bt-btif : BTA AG is already disabled, ignoring ...
08-30 11:36:56.447  3895  4081 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 11:36:56.447  3895  4081 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 11:36:56.447  3895  4081 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-30 11:36:56.447  3895  4081 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 11:36:56.447  3895  4081 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 11:36:56.447  3895  4081 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 11:36:56.447  3895  4081 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 11:36:56.447  3895  4081 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 11:36:56.447  3895  4081 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-30 11:36:56.447  3895  4081 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 11:36:56.447  3895  4081 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 11:36:56.447  3895  4081 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 11:36:56.447  3895  4081 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 11:36:56.447  3895  4081 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 11:36:56.447  3895  4081 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-30 11:36:56.447  3895  4081 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 11:36:56.447  3895  4081 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 11:36:56.448  3895  4081 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 11:36:56.448  3895  4081 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-30 11:36:56.448  3895  3979 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-30 11:36:56.448  3895  4083 I bt_vendor: hw_epilog_process
08-30 11:36:56.449  3895  3979 D bt_hci_bdroid: cleanup Finalizing cleanup
08-30 11:36:56.449  3895  3979 D bt_userial_mct: userial_close
08-30 11:36:56.449  3895  3979 E bt_userial_mct: pthread_join() FAILED result:3
08-30 11:36:56.449  3895  3979 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-30 11:36:56.505  3895  3979 D bt_hci_bdroid: set_power 0
08-30 11:36:56.505  3895  3979 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-30 11:36:56.505  3895  3979 I bt_vendor: bluetooth satus is on
08-30 11:36:56.505  3895  3979 I bt_vendor: bt-vendor : resetting BT status
08-30 11:36:56.505  3895  3979 I bt_vendor: Starting hciattach daemon
08-30 11:36:56.505  3895  3979 I bt_vendor: try to set false
08-30 11:36:56.507  3895  3979 I bt_vendor: Starting hciattach daemon
08-30 11:36:56.507  3895  3979 I bt_vendor: try to set false
,08-30 11:36:56.511  3895  3979 I bt_vendor: cleanup
08-30 11:36:56.512  3895  4081 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-30 11:36:56.513  3895  3979 I GKI_LINUX: GKI_exit_task 0 done
08-30 11:36:56.513  3895  3979 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-30 11:36:56.516  3895  3975 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-30 11:36:56.518  3895  3895 D HeadsetService: Received stop request...Stopping profile...
08-30 11:36:56.519  3895  3895 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-30 11:36:56.519  3895  3895 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-30 11:36:56.519  3895  3895 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@35b6452c
08-30 11:36:56.520  3895  4005 D HeadsetStateMachine: Exit Disconnected: -1
08-30 11:36:56.522  1843  1843 D BluetoothHeadset: Proxy object disconnected
,08-30 11:36:56.522  1843  1843 D BluetoothHeadset: Proxy object disconnected
08-30 11:36:56.523  3895  3895 D A2dpService: Received stop request...Stopping profile...
08-30 11:36:56.524  3895  4057 D A2dpStateMachine: Exit Disconnected: -1
08-30 11:36:56.524  3895  3895 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-30 11:36:56.524  1028  1028 D BluetoothHeadset: Proxy object disconnected
08-30 11:36:56.524  1028  1028 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-30 11:36:56.525  1843  1843 D BluetoothHeadset: Proxy object disconnected
08-30 11:36:56.528  3895  3895 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-30 11:36:56.528  3895  3895 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-30 11:36:56.529  3895  3895 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@35b6452c
08-30 11:36:56.529  3895  3975 D BluetoothAdapterState: Stopping profile services that were post enabled
08-30 11:36:56.530  1028  1028 D BluetoothA2dp: Proxy object disconnected
08-30 11:36:56.530  1028  1028 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-30 11:36:56.531  3895  3895 D HidService: Received stop request...Stopping profile...
08-30 11:36:56.531  3895  3895 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@35b6452c
08-30 11:36:56.532  6767  6767 D BluetoothInputDevice: Proxy object disconnected
08-30 11:36:56.533  3895  3895 D HealthService: Received stop request...Stopping profile...
08-30 11:36:56.533  6767  6767 D HidProfile: Bluetooth service disconnected
08-30 11:36:56.533  3895  3895 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@35b6452c
08-30 11:36:56.534  3895  3895 D HeadsetStateMachine: Unbinding service...
08-30 11:36:56.534  3895  3895 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-30 11:36:56.535  3895  3895 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-30 11:36:56.535  3895  3895 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-30 11:36:56.535  3895  3895 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-30 11:36:56.535  3895  3895 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-30 11:36:56.535  3895  3895 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-30 11:36:56.535  3895  3895 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-30 11:36:56.535  3895  3895 D PanService: Received stop request...Stopping profile...
08-30 11:36:56.536  3895  3895 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@35b6452c
,08-30 11:36:56.538  3895  3895 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-30 11:36:56.538  6767  6767 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-30 11:36:56.538  6767  6767 D PanProfile: Bluetooth service disconnected
08-30 11:36:56.538  3895  3895 D BtGatt.GattService: Received stop request...Stopping profile...
08-30 11:36:56.539  3895  3895 D BtGatt.GattService: stop()
08-30 11:36:56.539  3895  3895 D BtGatt.AdvertiseManager: advertise clients cleared
08-30 11:36:56.540  3895  3895 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@35b6452c
08-30 11:36:56.541  3895  3895 D BluetoothMapService: Received stop request...Stopping profile...
08-30 11:36:56.541  3895  3895 D BluetoothMapService: stop()
08-30 11:36:56.541  3895  3895 D BluetoothMapEmailAppObserver: deinitObservers()
08-30 11:36:56.541  3895  3895 D BluetoothMapEmailAppObserver: removeReceiver()
08-30 11:36:56.542  3895  3895 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@35b6452c
08-30 11:36:56.543  3895  3895 I BluetoothA2dpServiceJni: cleanupNative
08-30 11:36:56.543  3895  4059 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-30 11:36:56.543  3895  3895 I GKI_LINUX: GKI_exit_task 2 done
08-30 11:36:56.543  3895  3895 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-30 11:36:56.543  3895  3895 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-30 11:36:56.543  3895  3895 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-30 11:36:56.544  3895  3895 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-30 11:36:56.544  3895  3895 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-30 11:36:56.544  3895  3895 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-30 11:36:56.544  3895  3895 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-30 11:36:56.544  3895  3895 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-30 11:36:56.544  6767  6767 D BluetoothMap: Proxy object disconnected
08-30 11:36:56.544  6767  6767 D MapProfile: Bluetooth service disconnected
08-30 11:36:56.545  3895  3895 V BluetoothMapService: Handler(): got msg=4
08-30 11:36:56.545  3895  3895 D BluetoothMapService: MAP Service closeService in
08-30 11:36:56.545  3895  3895 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-30 11:36:56.545  3895  3895 V BluetoothMapService: MAP Service closeService out
08-30 11:36:56.546  3895  3975 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-30 11:36:56.546  3895  3975 D BluetoothAdapterProperties: Setting state to 10
08-30 11:36:56.546  3895  3975 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-30 11:36:56.546  1028  1110 D BluetoothManagerService: Message: 60
08-30 11:36:56.546  1028  1110 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-30 11:36:56.546  3895  3895 D BluetoothMapService: cleanup()
08-30 11:36:56.546  1028  1110 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
08-30 11:36:56.546  3895  3895 D BluetoothMapService: MAP Service closeService in
08-30 11:36:56.546  3895  3895 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-30 11:36:56.546  1028  1110 D BluetoothA2dp: onBluetoothStateChange: up=false
08-30 11:36:56.546  3895  3895 V BluetoothMapService: MAP Service closeService out
08-30 11:36:56.547  3895  3975 I BluetoothAdapterState: Entering OffState
08-30 11:36:56.547  1843  4011 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 11:36:56.548  6767  6787 D BluetoothMap: onBluetoothStateChange: up=false
08-30 11:36:56.549  6767  6786 D BluetoothPan: onBluetoothStateChange on: false
08-30 11:36:56.550  1843  3563 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-30 11:36:56.550  6767  6787 D BluetoothPbap: onBluetoothStateChange: up=false
08-30 11:36:56.551  1028  1110 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 11:36:56.551  6767  6786 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-30 11:36:56.552  1843  4010 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-30 11:36:56.553  1028  1110 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-30 11:36:56.553  1028  1110 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-30 11:36:56.556  1028  1110 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-30 11:36:56.556  1028  1110 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-30 11:36:56.556  1028  1110 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@340cd740 mBinding = false
08-30 11:36:56.556  1028  1110 D BluetoothManagerService: Sending unbind request.
08-30 11:36:56.565  1028  1110 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-30 11:36:56.566  3895  3979 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-30 11:36:56.566  3895  3895 I GKI_LINUX: GKI_exit_task 1 done
08-30 11:36:56.566  3895  3895 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
,08-30 11:36:56.567  3895  3895 I BluetoothServiceJni: cleanupNative: return from cleanup
08-30 11:36:56.567  3895  3895 I art     : --- WEIRD: removing null entry 246
08-30 11:36:56.567  3895  3895 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
08-30 11:36:56.567  3895  3895 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-30 11:36:56.570  6767  6767 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-30 11:36:56.571  6767  6767 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-30 11:36:56.571  6767  6767 D LGBluetoothEventManager: [BTUI] clear device connection state
08-30 11:36:56.572  1933  1933 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-30 11:36:56.572  1933  2123 D LGBluetoothAPIService: Message: 2
08-30 11:36:56.572  1933  2123 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@27c8396f mBinding = false
08-30 11:36:56.572  1933  2123 D LGBluetoothAPIService: Sending unbind request.
08-30 11:36:56.573  1595  1595 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-30 11:36:56.574  6767  6767 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-30 11:36:56.576  6540  6540 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 11:36:56.577  6540  6540 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 11:36:56.578  3895  3895 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
,08-30 11:36:56.581  1595  1595 D BluetoothAdapter: 319402564: getState() :  mService = null. Returning STATE_OFF
08-30 11:36:56.581  1595  1595 D BluetoothAdapter: 319402564: getState() :  mService = null. Returning STATE_OFF
08-30 11:36:56.585  6767  6767 D DockEventReceiver: finishStartingService: stopping service
08-30 11:36:56.587  3895  3895 I art     : System.exit called, status: 0
08-30 11:36:56.587  3895  3895 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-30 11:36:56.594  6788  6788 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-30 11:36:56.599  6767  6767 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-30 11:36:56.606   320   320 V AudioFlinger: 3895 died, releasing its sessions
08-30 11:36:56.606   320   320 V AudioFlinger:  pid 1843 @ 0
08-30 11:36:56.606   320   320 V AudioFlinger:  pid 3470 @ 1
08-30 11:36:56.606   320   320 V AudioFlinger:  pid 3470 @ 2
,08-30 11:36:56.606  6767  6767 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-30 11:36:56.606  6767  6767 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-30 11:36:56.769  1028  1967 I ActivityManager: Process com.android.bluetooth (pid 3895) has died
08-30 11:36:56.770  1028  1967 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
,08-30 11:36:56.794  2195  2195 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 11:36:56.823  6876  6902 W FormManager: Network not available. Please check & try again.
,08-30 11:36:56.828  6876  6903 V FormManager: Network unavailable.
08-30 11:36:56.837  6767  6767 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
,08-30 11:36:56.838  6767  6767 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-30 11:36:56.838  6767  6767 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-30 11:36:56.838  6767  6767 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-30 11:36:56.839  6767  6767 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-30 11:36:56.840  6876  6903 V FormManager: Network unavailable.
08-30 11:36:56.848  6767  6767 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
,08-30 11:36:56.851  6767  6767 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-30 11:36:56.851  6767  6767 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-30 11:36:56.851  6767  6767 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-30 11:36:56.851  6767  6767 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-30 11:36:56.852  6767  6767 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-30 11:36:56.854  6767  6767 D BluetoothPermissionRequest: onReceive
08-30 11:36:56.856  6767  6767 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-30 11:36:56.856  6767  6767 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-30 11:36:56.858  6767  6767 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-30 11:36:56.907  1028  1567 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=6913 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-30 11:36:56.917  1028  1878 I ActivityManager: Killing 6117:com.android.contacts/u0a19 (adj 15): empty #17
08-30 11:36:56.919  4330  4330 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-30 11:36:56.919  4330  4330 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-30 11:36:56.921  4330  4330 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 11:36:56.968  1028  1044 W libprocessgroup: failed to open /acct/uid_10019/pid_6117/cgroup.procs: No such file or directory
,08-30 11:36:56.971  4330  4330 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 11:36:56.994  6788  6788 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-30 11:36:56.995  6788  6788 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-30 11:36:56.995  6788  6788 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-30 11:36:56.999  6767  6767 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-30 11:36:57.006  4330  6930 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-30 11:36:57.006  6913  6913 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-30 11:36:57.007  6913  6913 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-30 11:36:57.007  6913  6913 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-30 11:36:57.008  6913  6913 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-30 11:36:57.022  6876  6934 V FormManager: Network unavailable.
,08-30 11:36:57.027  6913  6913 D BluetoothAdapterApp: Loading JNI Library
08-30 11:36:57.028  6876  6934 V FormManager: Network unavailable.
08-30 11:36:57.032  6876  6933 W FormManager: Network not available. Please check & try again.
,08-30 11:36:57.043  6767  6767 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 11:36:57.058  6836  6836 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-30 11:36:57.059  6836  6836 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-30 11:36:57.059  6836  6836 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
,08-30 11:36:57.066  6913  6913 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@172d23d Instance Count = 1
08-30 11:36:57.072  6913  6913 D BluetoothAdapterApp: onCreate
08-30 11:36:57.072  4330  6932 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-30 11:36:57.072  4330  6932 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-30 11:36:57.099  6913  6913 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-30 11:36:57.099  6913  6913 D ProfileConfigQcom: Adding HeadsetService
08-30 11:36:57.099  6913  6913 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-30 11:36:57.100  6913  6913 D ProfileConfigQcom: Adding A2dpService
08-30 11:36:57.100  6913  6913 D ProfileConfigQcom: [BTUI] HidService is supported
08-30 11:36:57.100  6913  6913 D ProfileConfigQcom: Adding HidService
08-30 11:36:57.100  6913  6913 D ProfileConfigQcom: [BTUI] HealthService is supported
08-30 11:36:57.100  6913  6913 D ProfileConfigQcom: Adding HealthService
08-30 11:36:57.101  6913  6913 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
,08-30 11:36:57.103  6913  6913 D ProfileConfigQcom: [BTUI] PanService is supported
08-30 11:36:57.104  6913  6913 D ProfileConfigQcom: Adding PanService
08-30 11:36:57.104  6913  6913 D ProfileConfigQcom: [BTUI] GattService is supported
08-30 11:36:57.104  6913  6913 D ProfileConfigQcom: Adding GattService
08-30 11:36:57.105  6913  6913 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-30 11:36:57.105  6913  6913 D ProfileConfigQcom: Adding BluetoothMapService
08-30 11:36:57.105  6913  6913 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-30 11:36:57.107  6913  6913 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-30 11:36:57.113  6767  6767 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
,08-30 11:36:57.114  6836  6836 D LgDataFeature: LgDataFeature() Constructor: none
08-30 11:36:57.115  6836  6836 D LgDataFeature: LgDataFeature() Constructor Done, null
08-30 11:36:57.120  6913  6913 V LGMDMManagerInternal: Create singleton instance
08-30 11:36:57.121  6836  6836 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
08-30 11:36:57.122  6836  6836 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-30 11:36:57.123  6836  6836 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-30 11:36:57.123  6836  6836 V SoundPool: doLoad: loading sample sampleID=1
08-30 11:36:57.124  6836  6947 V SoundPool: Start decode
08-30 11:36:57.124  6836  6947 V MediaPlayer[Native]: decode(31, 10857164, 17813)
08-30 11:36:57.124   320  1390 V MediaPlayerService: decode(23, 10857164, 17813)
,08-30 11:36:57.125  6836  6836 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-30 11:36:57.126   320  1390 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-30 11:36:57.126   320  1390 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-30 11:36:57.126   320  1390 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-30 11:36:57.126   320  1390 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-30 11:36:57.126   320  1390 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-30 11:36:57.126   320  1390 V MediaPlayerService: player type = 3
08-30 11:36:57.126   320  1390 V AwesomePlayer: AwesomePlayer create()
08-30 11:36:57.127   320  1390 V AwesomePlayer: reset_l() 
08-30 11:36:57.127   320  1390 V AwesomePlayer: cancelPlayerEvents
08-30 11:36:57.127   320  1390 V AwesomePlayer: setAudioSink() 
08-30 11:36:57.127   320  1390 V AwesomePlayer: reset_l() 
08-30 11:36:57.127   320  1390 V AudioCache: notify(0xb5474940, 8, 0, 0)
08-30 11:36:57.127   320  1390 V AudioCache: ignored
08-30 11:36:57.127   320  1390 V AwesomePlayer: cancelPlayerEvents
08-30 11:36:57.128   320  1390 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
08-30 11:36:57.128   320  1390 V AwesomePlayer: setDataSource_l dataSource
08-30 11:36:57.128   320  1390 V LGParserOSAL: SniffLGParser start
08-30 11:36:57.128   320  1390 V LGParserOSAL: MainType:5, SubType=0
08-30 11:36:57.128   320  1390 V LGParserOSAL: #### check Mime : application/ogg
08-30 11:36:57.128   320  1390 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-30 11:36:57.128   320  1390 E MediaExtractor: Use LGExtractor :application/ogg 
08-30 11:36:57.129  6687  6687 D UEI.SmartControl: QS Service created
08-30 11:36:57.145  6836  6836 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-30 11:36:57.150  6836  6836 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-30 11:36:57.150  6836  6836 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-30 11:36:57.163  6836  6836 V LGMDMManager: Create singleton instance
08-30 11:36:57.163  6687  6687 I UEI.SmartControl: Service initServices...
08-30 11:36:57.164  6687  6687 D UEI.SmartControl: QS start get config
08-30 11:36:57.171   320  1390 V LGParserOSAL: supported mime: application/ogg
08-30 11:36:57.171   320  1390 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-30 11:36:57.171   320  1390 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-30 11:36:57.171   320  1390 V AwesomePlayer: mBitrate = -1 bits/sec
08-30 11:36:57.171   320  1390 V AwesomePlayer: AudioTrack Setting
08-30 11:36:57.171   320  1390 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-30 11:36:57.171   320  1390 V AwesomePlayer: setAudioSource() 
08-30 11:36:57.171   320  1390 V MediaPlayerService: prepare
08-30 11:36:57.171   320  1390 V AwesomePlayer: prepareAsync_l() 
08-30 11:36:57.171   320  1390 V MediaPlayerService: wait for prepare
,08-30 11:36:57.175   320  6949 V AwesomePlayer: onPrepareAsyncEvent() 
08-30 11:36:57.175   320  6949 V AwesomePlayer: initAudioDecoder() 
08-30 11:36:57.175   320  6949 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-30 11:36:57.175   320  6949 V AudioSystem: isOffloadSupported()
08-30 11:36:57.175   320  6949 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-30 11:36:57.175   320  6949 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-30 11:36:57.175   320  6949 I AudioFlinger: isAudioPlaybackHookOn() false
08-30 11:36:57.175   320  6949 V AwesomePlayer: getUseOffload() = 0 
08-30 11:36:57.175   320  6949 V OMXCodec: OMXCodec::Create
08-30 11:36:57.175   320  6949 V OMXCodec: findMatchingCodecs()
08-30 11:36:57.176   320  6949 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-30 11:36:57.176   320  6949 V OMXCodec: matchingCodecs.size()=1
08-30 11:36:57.176   320  6949 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
08-30 11:36:57.190   320  6949 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-30 11:36:57.190   320  6949 V LGCodecAdapter: LG Codec Adapter start
08-30 11:36:57.190   320  6949 V OMXCodec: OMXCodec Createtor
08-30 11:36:57.190   320  6949 V OMXCodec: setComponentRole
08-30 11:36:57.190   320  6949 V OMXCodec: configureCodec protected=0
08-30 11:36:57.190   320  6949 V LGCodecAdapter: called getLGCodecSpecificData
08-30 11:36:57.190   320  6949 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-30 11:36:57.190   320  6949 V LGCodecOSAL: Called LGconfigureCodecMETA
08-30 11:36:57.190   320  6949 V LGCodecOSAL: Called LGconfigureCodecMSG
,08-30 11:36:57.191   320  6949 V LGCodecOSAL: Not support LGCodec
08-30 11:36:57.191   320  6949 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
,08-30 11:36:57.191   320  6949 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-30 11:36:57.191   320  6949 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-30 11:36:57.191   320  6949 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-30 11:36:57.191   320  6949 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-30 11:36:57.191   320  6949 V AudioSystem: isOffloadSupported()
08-30 11:36:57.191   320  6949 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-30 11:36:57.191   320  6949 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-30 11:36:57.191   320  6949 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-30 11:36:57.191   320  6949 V OMXCodec: init()
08-30 11:36:57.192   320  6949 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-30 11:36:57.192   320  6949 V OMXCodec: allocateBuffers
08-30 11:36:57.192   320  6949 V OMXCodec: allocateBuffersOnPort portIndex=0
08-30 11:36:57.192   320  6949 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-30 11:36:57.192   320  6949 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a10 on input port
08-30 11:36:57.192   320  6949 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b00 on input port
08-30 11:36:57.192   320  6949 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ba0 on input port
08-30 11:36:57.192   320  6949 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7dd0 on input port
08-30 11:36:57.193   320  6949 V OMXCodec: allocateBuffersOnPort portIndex=1
08-30 11:36:57.193   320  6949 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-30 11:36:57.193   320  6949 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7e20 on output port
08-30 11:36:57.193   320  6949 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7fb0 on output port
08-30 11:36:57.193   320  6949 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57bb060 on output port
08-30 11:36:57.193   320  6949 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57bb420 on output port
08-30 11:36:57.193   320  6949 V OMXCodec: init() mAsyncCompletion wait!!! 
08-30 11:36:57.194   320  6952 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-30 11:36:57.194   320  6952 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-30 11:36:57.194   320  6952 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-30 11:36:57.194   320  6949 V OMXCodec: init() mAsyncCompletion wait!!! 
08-30 11:36:57.195   320  6952 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-30 11:36:57.195   320  6952 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-30 11:36:57.195   320  6952 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-30 11:36:57.195   320  6949 V OMXCodec: init() mAsyncCompletion wait free! 
08-30 11:36:57.195   320  6949 V AwesomePlayer: finishAsyncPrepare_l() 
08-30 11:36:57.195   320  6949 V AudioCache: notify(0xb5474940, 5, 0, 0)
08-30 11:36:57.195   320  6949 V AudioCache: ignored
08-30 11:36:57.195   320  6949 V AudioCache: notify(0xb5474940, 1, 0, 0)
08-30 11:36:57.195   320  6949 V AudioCache: prepared
08-30 11:36:57.195   320  1390 V AudioCache: wait - success
08-30 11:36:57.195   320  1390 V MediaPlayerService: start
08-30 11:36:57.195   320  1390 V AwesomePlayer: play_l() 
08-30 11:36:57.195   320  1390 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-30 11:36:57.195   320  1390 V AwesomePlayer: createAudioPlayer_l
08-30 11:36:57,.195   320  1390 V AwesomePlayer: seekAudioIfNecessary_l() 
08-30 11:36:57.195   320  1390 V AwesomePlayer: startAudioPlayer_l() 
08-30 11:36:57.195   320  1390 D AudioPlayer: start of Playback, useOffload 0
08-30 11:36:57.195   320  1390 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-30 11:36:57.195   320  1390 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-30 11:36:57.198   320  6952 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-30 11:36:57.198   320  6952 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-30 11:36:57.198   320  6952 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-30 11:36:57.198   320  6952 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-30 11:36:57.198   320  6952 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-30 11:36:57.198   320  6952 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-30 11:36:57.198   320  6952 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885728
08-30 11:36:57.198   320  6952 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-30 11:36:57.198   320  6952 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041886128
08-30 11:36:57.198   320  6952 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-30 11:36:57.198   320  6952 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044782176
08-30 11:36:57.198   320  6952 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-30 11:36:57.198   320  6952 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044783136
08-30 11:36:57.198   320  6952 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-30 11:36:57.198   320  6952 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-30 11:36:57.198   320  6952 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-30 11:36:57.198   320  6952 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-30 11:36:57.198   320  6952 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-30 11:36:57.198   320  6952 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-30 11:36:57.198   320  6952 V OMXCodec: allocateBuffersOnPort portIndex=1
08-30 11:36:57.199   320  6952 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-30 11:36:57.199   320  6952 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57bb060 on output port
08-30 11:36:57.199   320  6952 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7fb0 on output port
08-30 11:36:57.199   320  6952 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7e20 on output port
08-30 11:36:57.199   320  6952 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57bb6f0 on output port
08-30 11:36:57.199   320  6952 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-30 11:36:57.199   320  6952 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-30 11:36:57.199   320  1390 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-30 11:36:57.200   320  1390 V AudioCache: notify(0xb5474940, 6, 0, 0)
08-30 11:36:57.200   320  1390 V AudioCache: ignored
08-30 11:36:57.200   320  1390 V MediaPlayerService: wait for playback complete
08-30 11:36:57.200   320  6953 V AudioCache: write(0xb1786000, 4096)
08-30 11:36:57.200   320  6953 V AudioCache: memcpy(0xaf006000, 0xb1786000, 4096)
08-30 11:36:57.201   320  6953 V AudioCache: write(0xb1786000, 4096)
08-30 11:36:57.201   320  6953 V AudioCache: memcpy(0xaf007000, 0xb1786000, 4096)
,08-30 11:36:57.202   320  6953 V AudioCache: write(0xb1786000, 4096)
08-30 11:36:57.202   320  6953 V AudioCache: memcpy(0xaf008000, 0xb1786000, 4096)
08-30 11:36:57.202   320  6953 V AudioCache: write(0xb1786000, 4096)
08-30 11:36:57.202   320  6953 V AudioCache: memcpy(0xaf009000, 0xb1786000, 4096)
08-30 11:36:57.203   320  6953 V AudioCache: write(0xb1786000, 4096)
08-30 11:36:57.203   320  6953 V AudioCache: memcpy(0xaf00a000, 0xb1786000, 4096)
08-30 11:36:57.203   320  6953 V AudioCache: write(0xb1786000, 4096)
08-30 11:36:57.203   320  6953 V AudioCache: memcpy(0xaf00b000, 0xb1786000, 4096)
08-30 11:36:57.203   320  6953 V AudioCache: write(0xb1786000, 4096)
08-30 11:36:57.203   320  6953 V AudioCache: memcpy(0xaf00c000, 0xb1786000, 4096)
08-30 11:36:57.204   320  6953 V AudioCache: write(0xb1786000, 4096)
08-30 11:36:57.204   320  6953 V AudioCache: memcpy(0xaf00d000, 0xb1786000, 4096)
08-30 11:36:57.204   320  6953 V AudioCache: write(0xb1786000, 4096)
08-30 11:36:57.204   320  6953 V AudioCache: memcpy(0xaf00e000, 0xb1786000, 4096)
08-30 11:36:57.204   320  6953 V AudioCache: write(0xb1786000, 4096)
,08-30 11:36:57.204   320  6953 V AudioCache: memcpy(0xaf00f000, 0xb1786000, 4096)
08-30 11:36:57.205   320  6953 V AudioCache: write(0xb1786000, 4096)
08-30 11:36:57.205   320  6953 V AudioCache: memcpy(0xaf010000, 0xb1786000, 4096)
08-30 11:36:57.206   320  6953 V AudioCache: write(0xb1786000, 4096)
08-30 11:36:57.206   320  6953 V AudioCache: memcpy(0xaf011000, 0xb1786000, 4096)
08-30 11:36:57.206   320  6953 V AudioCache: write(0xb1786000, 4096)
08-30 11:36:57.206   320  6953 V AudioCache: memcpy(0xaf012000, 0xb1786000, 4096)
08-30 11:36:57.207   320  6953 V AudioCache: write(0xb1786000, 4096)
08-30 11:36:57.207   320  6953 V AudioCache: memcpy(0xaf013000, 0xb1786000, 4096)
08-30 11:36:57.207   320  6953 V AudioCache: write(0xb1786000, 4096)
08-30 11:36:57.207   320  6953 V AudioCache: memcpy(0xaf014000, 0xb1786000, 4096)
08-30 11:36:57.207   320  6953 V AudioCache: write(0xb1786000, 4096)
08-30 11:36:57.207   320  6953 V AudioCache: memcpy(0xaf015000, 0xb1786000, 4096)
,08-30 11:36:57.208   320  6953 V AudioCache: write(0xb1786000, 4096)
08-30 11:36:57.208   320  6953 V AudioCache: memcpy(0xaf016000, 0xb1786000, 4096)
08-30 11:36:57.208   320  6953 V AudioCache: write(0xb1786000, 4096)
08-30 11:36:57.208   320  6953 V AudioCache: memcpy(0xaf017000, 0xb1786000, 4096)
08-30 11:36:57.208   320  6953 V AudioCache: write(0xb1786000, 4096)
08-30 11:36:57.208   320  6953 V AudioCache: memcpy(0xaf018000, 0xb1786000, 4096)
08-30 11:36:57.209   320  6953 V AudioCache: write(0xb1786000, 4096)
08-30 11:36:57.209   320  6953 V AudioCache: memcpy(0xaf019000, 0xb1786000, 4096)
08-30 11:36:57.209   320  6953 V AudioCache: write(0xb1786000, 4096)
08-30 11:36:57.209   320  6953 V AudioCache: memcpy(0xaf01a000, 0xb1786000, 4096)
08-30 11:36:57.210   320  6953 V AudioCache: write(0xb1786000, 4096)
08-30 11:36:57.210   320  6953 V AudioCache: memcpy(0xaf01b000, 0xb1786000, 4096)
,08-30 11:36:57.210   320  6953 V AudioCache: write(0xb1786000, 4096)
08-30 11:36:57.210   320  6953 V AudioCache: memcpy(0xaf01c000, 0xb1786000, 4096)
08-30 11:36:57.210   320  6953 V AudioCache: write(0xb1786000, 4096)
08-30 11:36:57.210   320  6953 V AudioCache: memcpy(0xaf01d000, 0xb1786000, 4096)
08-30 11:36:57.211   320  6953 V AudioCache: write(0xb1786000, 4096)
08-30 11:36:57.211   320  6953 V AudioCache: memcpy(0xaf01e000, 0xb1786000, 4096)
,08-30 11:36:57.215   320  6953 V AudioCache: write(0xb1786000, 4096)
08-30 11:36:57.215   320  6953 V AudioCache: memcpy(0xaf01f000, 0xb1786000, 4096)
08-30 11:36:57.215   320  6953 V AudioCache: write(0xb1786000, 4096)
08-30 11:36:57.215   320  6953 V AudioCache: memcpy(0xaf020000, 0xb1786000, 4096)
08-30 11:36:57.216   320  6953 V AudioCache: write(0xb1786000, 4096)
08-30 11:36:57.216   320  6953 V AudioCache: memcpy(0xaf021000, 0xb1786000, 4096)
08-30 11:36:57.217   320  6953 V AudioCache: write(0xb1786000, 4096)
08-30 11:36:57.217   320  6953 V AudioCache: memcpy(0xaf022000, 0xb1786000, 4096)
08-30 11:36:57.217   320  6953 V AudioCache: write(0xb1786000, 4096)
08-30 11:36:57.217   320  6953 V AudioCache: memcpy(0xaf023000, 0xb1786000, 4096)
08-30 11:36:57.218   320  6953 V AudioCache: write(0xb1786000, 4096)
08-30 11:36:57.218   320  6953 V AudioCache: memcpy(0xaf024000, 0xb1786000, 4096)
08-30 11:36:57.219   320  6953 V AudioCache: write(0xb1786000, 4096)
08-30 11:36:57.219   320  6953 V AudioCache: memcpy(0xaf025000, 0xb1786000, 4096)
08-30 11:36:57.220   320  6953 V AudioCache: write(0xb1786000, 4096)
08-30 11:36:57.220   320  6953 V AudioCache: memcpy(0xaf026000, 0xb1786000, 4096)
08-30 11:36:57.220   320  6953 V AudioCache: write(0xb1786000, 4096)
08-30 11:36:57.220   320  6953 V AudioCache: memcpy(0xaf027000, 0xb1786000, 4096)
08-30 11:36:57.221   320  6953 V AudioCache: write(0xb1786000, 4096)
08-30 11:36:57.221   320  6953 V AudioCache: memcpy(0xaf028000, 0xb1786000, 4096)
08-30 11:36:57.221   320  6953 V AudioCache: write(0xb1786000, 4096)
08-30 11:36:57.221   320  6953 V AudioCache: memcpy(0xaf029000, 0xb1786000, 4096)
08-30 11:36:57.222  6913  6913 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-30 11:36:57.222   320  6953 V AudioCache: write(0xb1786000, 4096)
08-30 11:36:57.222   320  6953 V AudioCache: memcpy(0xaf02a000, 0xb1786000, 4096)
08-30 11:36:57.223   320  6953 V AudioCache: write(0xb1786000, 4096)
08-30 11:36:57.223   320  6953 V AudioCache: memcpy(0xaf02b000, 0xb1786000, 4096)
08-30 11:36:57.224   320  6953 V AudioCache: write(0xb1786000, 4096)
08-30 11:36:57.224   320  6953 V AudioCache: memcpy(0xaf02c000, 0xb1786000, 4096)
08-30 11:36:57.224  6913  6913 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-30 11:36:57.224   320  6953 V AudioCache: write(0xb1786000, 4096)
08-30 11:36:57.224   320  6953 V AudioCache: memcpy(0xaf02d000, 0xb1786000, 4096)
08-30 11:36:57.225  6913  6913 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-30 11:36:57.225  6913  6913 V BluetoothSapReceiver: SapReceiver onReceive 
08-30 11:36:57.225   320  6953 V AudioCache: write(0xb1786000, 4096)
08-30 11:36:57.225   320  6953 V AudioCache: memcpy(0xaf02e000, 0xb1786000, 4096)
08-30 11:36:57.225   320  6953 V AudioCache: write(0xb1786000, 4096)
08-30 11:36:57.225   320  6953 V AudioCache: memcpy(0xaf02f000, 0xb1786000, 4096)
08-30 11:36:57.226  6913  6913 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 11:36:57.226  6913  6913 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-30 11:36:57.226   320  6953 V AudioCache: write(0xb1786000, 4096)
08-30 11:36:57.226   320  6953 V AudioCache: memcpy(0xaf030000, 0xb1786000, 4096)
08-30 11:36:57.226   320  6953 V AudioCache: write(0xb1786000, 4096)
08-30 11:36:57.226   320  6953 V AudioCache: memcpy(0xaf031000, 0xb1786000, 4096)
08-30 11:36:57.227   320  6953 V AudioCache: write(0xb1786000, 4096)
08-30 11:36:57.227   320  6953 V AudioCache: memcpy(0xaf032000, 0xb1786000, 4096)
08-30 11:36:57.227   320  6953 V AudioCache: write(0xb1786000, 4096)
08-30 11:36:57.227   320  6953 V AudioCache: memcpy(0xaf033000, 0xb1786000, 4096)
08-30 11:36:57.228   320  6953 V AudioCache: write(0xb1786000, 4096)
08-30 11:36:57.228   320  6953 V AudioCache: memcpy(0xaf034000, 0xb1786000, 4096)
08-30 11:36:57.228   320  6953 V AudioCache: write(0xb1786000, 4096)
08-30 11:36:57.228   320  6953 V AudioCache: memcpy(0xaf035000, 0xb1786000, 4096)
,08-30 11:36:57.229   320  6953 V AudioCache: write(0xb1786000, 4096)
08-30 11:36:57.229   320  6953 V AudioCache: memcpy(0xaf036000, 0xb1786000, 4096)
08-30 11:36:57.229   320  6953 V AudioCache: write(0xb1786000, 4096)
08-30 11:36:57.229   320  6953 V AudioCache: memcpy(0xaf037000, 0xb1786000, 4096)
08-30 11:36:57.229   320  6952 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-30 11:36:57.229   320  6953 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-30 11:36:57.229   320  6953 V AwesomePlayer: postAudioEOS() 
08-30 11:36:57.229   320  6953 V AudioCache: write(0xb1786000, 280)
08-30 11:36:57.229   320  6953 V AudioCache: memcpy(0xaf038000, 0xb1786000, 280)
,08-30 11:36:57.231   320  6949 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-30 11:36:57.231   320  6949 V AwesomePlayer: onStreamDone
08-30 11:36:57.231   320  6949 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-30 11:36:57.231   320  6949 V AudioCache: notify(0xb5474940, 2, 0, 0)
08-30 11:36:57.231   320  6949 V AudioCache: playback complete
08-30 11:36:57.231   320  6949 V AwesomePlayer: pause_l() 
08-30 11:36:57.231   320  6949 V AudioCache: notify(0xb5474940, 7, 0, 0)
08-30 11:36:57.231   320  6949 V AudioCache: ignored
08-30 11:36:57.231   320  6949 V AwesomePlayer: cancelPlayerEvents
08-30 11:36:57.231   320  1390 V AudioCache: wait - success
08-30 11:36:57.231   320  1390 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-30 11:36:57.231   320  6949 D AudioPlayer: Pause Playback at 1068125
08-30 11:36:57.231  6836  6836 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-30 11:36:57.232   320  1390 V AwesomePlayer: reset_l() 
08-30 11:36:57.232   320  1390 V AudioCache: notify(0xb5474940, 8, 0, 0)
08-30 11:36:57.232   320  1390 V AudioCache: ignored
08-30 11:36:57.232   320  1390 V AwesomePlayer: cancelPlayerEvents
08-30 11:36:57.232   320  1390 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-30 11:36:57.232   320  1390 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-30 11:36:57.232   320  1390 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-30 11:36:57.232   320  1390 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-30 11:36:57.232   320  1390 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-30 11:36:57.232  6836  6836 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
08-30 11:36:57.232   320  6952 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-30 11:36:57.232   320  6952 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-30 11:36:57.233   320  6952 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-30 11:36:57.233   320  6952 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7dd0 on port 0
08-30 11:36:57.233   320  6952 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-30 11:36:57.233   320  6952 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ba0 on port 0
08-30 11:36:57.233   320  6952 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-30 11:36:57.233   320  6952 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b00 on port 0
08-30 11:36:57.233   320  6952 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-30 11:36:57.233   320  6952 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a10 on port 0
08-30 11:36:57.233   320  6952 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-30 11:36:57.233  6853  6853 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
08-30 11:36:57.233   320  6952 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-30 11:36:57.233   320  6952 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb57bb6f0 on port 1
08-30 11:36:57.233   320  6952 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-30 11:36:57.233   320  6952 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7e20 on port 1
08-30 11:36:57.233   320  6952 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-30 11:36:57.233   320  6952 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7fb0 on port 1
08-30 11:36:57.233   320  6952 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-30 11:36:57.233   320  6952 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb57bb060 on port 1
08-30 11:36:57.233   320  6952 V OMXCodec: [OMX.google.vorbis.decoder] fre,eBuffer portIndex=1,bufIndex=0
08-30 11:36:57.234   320  6952 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-30 11:36:57.234   320  1390 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-30 11:36:57.234   320  1390 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-30 11:36:57.234   320  6952 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-30 11:36:57.234   320  6952 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-30 11:36:57.234  6836  6836 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:1338
08-30 11:36:57.234   320  6952 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-30 11:36:57.234   320  1390 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-30 11:36:57.234   320  1390 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-30 11:36:57.234   320  1390 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-30 11:36:57.235   320  1390 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-30 11:36:57.235   320  1390 D AudioPlayer: AudioPlayer releasing audio source
08-30 11:36:57.235   320  1390 D AudioPlayer: AudioPlayer done releasing audio source
08-30 11:36:57.235   320  1390 V AwesomePlayer: reset_l() 
08-30 11:36:57.235   320  1390 V AwesomePlayer: cancelPlayerEvents
08-30 11:36:57.235   320  1390 V AwesomePlayer: ~AwesomePlayer call
08-30 11:36:57.236   320  1390 V AwesomePlayer: reset_l() 
08-30 11:36:57.236   320  1390 V AwesomePlayer: cancelPlayerEvents
08-30 11:36:57.236  6836  6947 V SoundPool: close(31)
08-30 11:36:57.236  6836  6947 V SoundPool: pointer = 0x9fe38000, size = 205080, sampleRate = 48000, numChannels = 2
08-30 11:36:57.448  6687  6687 I UEI.SmartControl: Supports setup maps: true
08-30 11:36:57.450  6687  6687 D UEI.SmartControl: QS start statue = true Error code = 0
08-30 11:36:57.450  6687  6687 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-30 11:36:57.450  6687  6687 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-30 11:36:57.450  6687  6687 I UEI.SmartControl: ### init IR Blaster...
,08-30 11:36:57.456  6687  6687 D serial_port: Configuring serial port
,08-30 11:36:57.456  6687  6687 E UEI.SmartControl: UEIBLaster setting for 616
08-30 11:36:57.456  6687  6687 I UEI.SmartControl: Setting serial record hearder size = 2
08-30 11:36:57.456  6687  6687 I UEI.SmartControl: configuring settings for MAXQ616
08-30 11:36:57.456  6687  6687 I UEI.SmartControl: Get version...
,08-30 11:36:57.475  6687  6956 D UEI.SmartControl: serial port data available: 21
,08-30 11:36:57.501  6687  6687 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-30 11:36:57.501  6687  6687 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-30 11:36:57.502  6687  6687 I UEI.SmartControl: QS saving settings...
08-30 11:36:57.503  6687  6687 D UEI.SmartControl: IR Blaster version: 25672567
,08-30 11:36:57.520  6687  6956 D UEI.SmartControl: serial port data available: 4
,08-30 11:36:57.557  6687  6687 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-30 11:36:57.561  6687  6965 I UEI.SmartControl: Device manager: loading config....
08-30 11:36:57.562  6687  6965 D UEI.SmartControl: ----------- loading internal config...
08-30 11:36:57.564  6687  6687 E UEI.SmartControl: Services init done
08-30 11:36:57.565  6687  6687 D UEI.SmartControl: QS Service init finished
08-30 11:36:57.568  6687  6687 D UEI.SmartControl: QS Service version name: 2.1.91
08-30 11:36:57.569  6687  6687 D UEI.SmartControl: QS Service version code: 201091
08-30 11:36:57.570  6687  6687 D UEI.SmartControl: Service requested: Control
08-30 11:36:57.570  6687  6965 E UEI.SmartControl: Loading SETTINGS...
08-30 11:36:57.573  6687  6687 D UEI.SmartControl: Internal service binding...
,08-30 11:36:57.576  6687  6965 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-30 11:36:57.577  6836  6836 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-30 11:36:57.579  6687  6702 I UEI.SmartControl: ------ IControl API: 11
08-30 11:36:57.579  6687  6702 D UEI.SmartControl: File observer start...
08-30 11:36:57.580  6687  6702 E UEI.SmartControl: IR Port is disabled: false
08-30 11:36:57.580  6687  6702 D UEI.SmartControl: Starting file observer...
08-30 11:36:57.582  6687  6702 I UEI.SmartControl: Registering callback...
08-30 11:36:57.583  6687  6703 I UEI.SmartControl: ------ IControl API: 19
08-30 11:36:57.585  6687  6703 I UEI.SmartControl: Registering Services Ready callback...
08-30 11:36:57.586  6687  6703 I UEI.SmartControl: Notify client services are ready...
,08-30 11:36:57.586  6836  6851 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-30 11:36:57.587  6836  6945 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-30 11:36:57.587  6836  6945 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-30 11:36:57.587  6687  6964 I UEI.SmartControl: Notify AllClients services are ready: 0
08-30 11:36:57.588  6836  6852 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-30 11:36:57.588  6836  6945 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-30 11:36:57.588  6836  6945 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-30 11:36:57.588  6836  6836 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-30 11:36:57.589  6687  6964 D UEI.SmartControl: -----service ready thread exits
08-30 11:36:57.589  6836  6836 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-30 11:36:57.590  6687  6702 I UEI.SmartControl: ------ IControl API: 8
08-30 11:36:57.591  6836  6836 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-30 11:36:57.592  6836  6836 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-30 11:36:57.592  6836  6836 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-30 11:36:57.592  6836  6836 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-30 11:36:57.593  6836  6836 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-30 11:36:57.594  6836  6836 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-30 11:36:57.595  6836  6836 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
08-30 11:36:57.597  6836  6836 D QRemote : [RemoteControlManager.java:327:handleMessage()] oooooo 140510:retrieveDevices already complete. Do nothing
08-30 11:36:57.598  6836  6836 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-30 11:36:57.599  6836  6836 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
,08-30 11:36:57.600  6836  6836 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-30 11:36:57.600  6836  6836 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-30 11:36:57.601  6836  6836 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-30 11:36:57.603  6836  6836 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-30 11:36:57.603  6836  6836 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-30 11:36:57.604  6836  6836 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1472549817604]
08-30 11:36:57.605  6836  6836 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
08-30 11:36:57.608  1028  1710 I ActivityManager: Killing 6138:com.android.gallery3d/u0a27 (adj 15): empty #17
08-30 11:36:57.628  6836  6967 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-30 11:36:57.645  1028  1710 I ActivityManager: Killing 6466:com.lge.email/u0a23 (adj 15): empty #18
,08-30 11:36:57.674  1028  1932 W libprocessgroup: failed to open /acct/uid_10027/pid_6138/cgroup.procs: No such file or directory
,08-30 11:36:57.678  1028  1912 W libprocessgroup: failed to open /acct/uid_10023/pid_6466/cgroup.procs: No such file or directory
08-30 11:36:57.682  6836  6836 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
08-30 11:36:57.683  6836  6836 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-30 11:36:57.684  6836  6836 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-30 11:36:57.684  6836  6836 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-30 11:36:57.684  6836  6836 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-30 11:36:57.685  6836  6836 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-30 11:36:57.685  6836  6836 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
08-30 11:36:57.697  6836  6836 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,08-30 11:36:58.352  1028  1043 D WifiServiceImplEx: setWifiEnabled: true pid=6540, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,08-30 11:36:58.353  1028  1043 D WifiService: setWifiEnabled: true pid=6540, uid=10118
08-30 11:36:58.353  1028  1043 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 11:36:58.382  1028  1028 D LocationManagerService: getAllProviders()=[passive, gps, network]
,08-30 11:36:58.382  1028  1028 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-30 11:36:58.383  1028  1028 D Ulp_jni : JNI:system_update. Event-4
08-30 11:36:58.384  1028  1383 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-30 11:36:58.384  1028  1383 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-30 11:36:58.387  1028  1383 E WifiUtil: wfc_util_ffile_check_copy(): pid[1028] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-30 11:36:58.387  1028  1383 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-30 11:36:58.387  1028  1383 E WifiUtil: wfc_util_ffile_check_copy(): pid[1028] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin],
08-30 11:36:58.387  1028  1383 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010],
08-30 11:36:58.387  1028  1383 I WifiUtil: Intf0MacAddress=C49A027FFB5D,
,08-30 11:36:58.387  1028  1383 E WifiHW  : unknown target_country: EU , set to default,
,08-30 11:36:58.387  1028  1383 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
,08-30 11:36:58.387  1028  1383 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
,08-30 11:36:58.387  1028  1383 I WifiUtil: gEnableBmps=1
08-30 11:36:58.465  1028  1437 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE,
,08-30 11:36:58.491  1028  1110 D Tethering: MasterInitialState.processMessage what=3
08-30 11:36:58.518  6540  6540 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 11:36:58.522  6540  6540 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 11:36:58.523  1028  1437 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-30 11:36:58.526  1028  1110 D Tethering: MasterInitialState.processMessage what=3
08-30 11:36:58.529  1028  1105 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-30 11:36:58.539  6540  6540 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 11:36:58.542  6540  6540 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 11:36:58.544  6373  6373 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-30 11:36:58.547  6373  6401 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-30 11:36:58.559  5783  5783 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-30 11:36:58.566  5783  5783 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-30 11:36:58.583  2195  2195 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-30 11:36:58.619  1028  1105 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-30 11:36:58.659  1028  1044 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6972 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
08-30 11:36:58.666  1028  1105 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 11:36:58.666  1028  1105 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-30 11:36:58.737  6972  6972 I AppUp4:AppBoxCP: onCreate
08-30 11:36:58.738  6972  6972 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,08-30 11:36:58.748  6972  6972 I AppUp4:DB:  setFingerPrint start
,08-30 11:36:58.749  6972  6972 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
08-30 11:36:58.758  6972  6972 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
08-30 11:36:58.758  6972  6972 I AppUp4:DB:  SDK version = 21
08-30 11:36:58.758  6972  6972 I AppUp4:DB:  beforefinger == newfinger no write in DB
,08-30 11:36:58.760  6972  6972 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
08-30 11:36:58.761  6972  6972 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-30 11:36:58.761  6972  6972 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-30 11:36:58.764  6972  6972 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-30 11:36:58.764  6972  6972 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-30 11:36:58.772  6972  6972 I AppUp4:CustModeStarterReceiver: onReceive
,08-30 11:36:58.824  6972  6972 D LgDataFeature: LgDataFeature() Constructor: none
,08-30 11:36:58.824  6972  6972 D LgDataFeature: LgDataFeature() Constructor Done, null
08-30 11:36:58.833  6972  6972 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@23ac54df
,08-30 11:36:58.833  6972  6972 D AppUp4:CustFacade: isCustomizationCompleted : false
08-30 11:36:58.833  6972  6972 D AppUp4:CustFacade: isPhone : true
08-30 11:36:58.834  6972  6972 D AppUp4:CustModeStarterReceiver: begin check event
08-30 11:36:58.834  6972  6972 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
,08-30 11:36:58.835  6972  6972 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
08-30 11:36:58.836  6972  7005 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
08-30 11:36:58.836  6972  7005 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
08-30 11:36:58.836  6972  7005 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
08-30 11:36:58.838  1028  1968 I ActivityManager: Killing 5817:com.android.vending/u0a44 (adj 15): empty #17
,08-30 11:36:58.947  4330  4330 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-30 11:36:58.947  4330  4330 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-30 11:36:58.948  1028  1878 W libprocessgroup: failed to open /acct/uid_10044/pid_5817/cgroup.procs: No such file or directory
,08-30 11:36:58.956  4330  4330 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-30 11:36:58.960  4330  4330 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 11:36:58.974  4330  7021 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-30 11:36:58.989  4330  7022 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-30 11:36:58.989  4330  7022 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-30 11:36:59.020  1028  1914 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7023 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-30 11:36:59.083  1028  1110 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-30 11:36:59.083  1028  1110 D Tethering: InitialState.processMessage what=4
08-30 11:36:59.084  1028  1110 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-30 11:36:59.090   315   891 D SoftapController: Softap fwReload - Ok
08-30 11:36:59.091  1028  1383 E NetdConnector: NDC Command {53 softap fwreload wlan0 STA} took too long (697ms)
08-30 11:36:59.092   315   891 D CommandListener: Setting iface cfg
08-30 11:36:59.092   315   891 D CommandListener: Trying to bring down wlan0
08-30 11:36:59.094   315   891 D CommandListener: Clearing all IP addresses on wlan0
08-30 11:36:59.098  1028  1383 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,08-30 11:36:59.105  1028  1383 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-30 11:36:59.105  1028  1383 E WifiStateMachine: useWiFiOffloading() : false
08-30 11:36:59.105  1028  1383 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-30 11:36:59.108  1028  1028 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-30 11:36:59.111  1933  1933 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
,08-30 11:36:59.113  6540  6540 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 11:36:59.097  7041  7041 W wpa_supplicant: type=1400 audit(0.0:167): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6837 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 11:36:59.097  7041  7041 W wpa_supplicant: type=1400 audit(0.0:168): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6837 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 11:36:59.114  6540  6540 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 11:36:59.114  1028  1383 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-30 11:36:59.114  1028  1383 D WifiMonitor: connecting to supplicant
08-30 11:36:59.115  1595  1595 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 11:36:59.141  7023  7023 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 11:36:59.141  7041  7041 I wpa_supplicant: Successfully initialized wpa_supplicant
08-30 11:36:59.141  7023  7023 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-30 11:36:59.143  7023  7023 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-30 11:36:59.143  7023  7023 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-30 11:36:59.177  7041  7041 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-30 11:36:59.177  7041  7041 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,08-30 11:36:59.229  7023  7023 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-30 11:36:59.258  7023  7023 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,08-30 11:36:59.295  7041  7041 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-30 11:36:59.323  7023  7023 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-30 11:36:59.336  7041  7041 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
08-30 11:36:59.349  1028  1383 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-30 11:36:59.350  1028  1383 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-30 11:36:59.350  1028  1383 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-30 11:36:59.350  1028  1383 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-30 11:36:59.351  1028  1383 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-30 11:36:59.351  1028  1383 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-30 11:36:59.352  1028  1383 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-30 11:36:59.352  1028  1383 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-30 11:36:59.348  7041  7041 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
08-30 11:36:59.352  7041  7041 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-30 11:36:59.353  1028  1383 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-30 11:36:59.353  1028  1383 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-30 11:36:59.353  1028  1383 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-30 11:36:59.354  1028  7053 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
08-30 11:36:59.354  1028  7053 D WifiMonitor: Dropping event because (p2p0) is stopped
08-30 11:36:59.354  1028  7053 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-30 11:36:59.354  1028  7053 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-30 11:36:59.354  1028  7053 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-30 11:36:59.354  1028  7053 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,08-30 11:36:59.355  1028  1028 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 11:36:59.355  1028  1028 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 11:36:59.355  1028  1028 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 11:36:59.356  1028  1028 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 11:36:59.356  1028  1028 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-30 11:36:59.356  1028  1383 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-30 11:36:59.356  1028  1383 E WifiStateMachine: useWiFiOffloading() : false
08-30 11:36:59.356  1028  1383 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-30 11:36:59.358  1933  1933 D WfdService: Waiting for WifiP2p enabling
08-30 11:36:59.358  1028  1383 D WifiNative-wlan0: doBoolean: SET update_config 1
08-30 11:36:59.359  1028  1383 D WifiNative-wlan0: SET update_config 1: returned true
08-30 11:36:59.359  1028  1383 D WifiConfigStore: Loading config and enabling all networks 
08-30 11:36:59.359  1028  1383 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-30 11:36:59.359  1595  1595 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 11:36:59.360  1028  1028 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-30 11:36:59.361  1028  1395 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-30 11:36:59.362  1028  1383 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-30 11:36:59.362  6540  6540 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 11:36:59.362  6540  6540 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 11:36:59.362  6540  6540 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 11:36:59.362  6540  6540 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 11:36:59.362  6540  6540 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 11:36:59.362  6540  6540 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 11:36:59.362  6540  6540 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 11:36:59.362  6540  6540 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 11:36:59.362  6540  6540 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 11:36:59.362  6540  6540 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 11:36:59.362  6540  6540 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 11:36:59.363  6540  6540 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 11:36:59.364  6540  6540 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 11:36:59.364  6540  6540 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 11:36:59.364  6540  6540 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 11:36:59.364  6540  6540 V io.jxcore.node.Co,nnectivityMonitor:     - is Wi-Fi enabled: true
08-30 11:36:59.364  6540  6540 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 11:36:59.364  6540  6540 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 11:36:59.364  6540  6540 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 11:36:59.364  6540  6540 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 11:36:59.364  6540  6540 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 11:36:59.364  6540  6540 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 11:36:59.368  7023  7023 D LgDataFeature: LgDataFeature() Constructor: none
08-30 11:36:59.369  7023  7023 D LgDataFeature: LgDataFeature() Constructor Done, null
08-30 11:36:59.369  1028  1383 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
,08-30 11:36:59.378  1028  1383 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-30 11:36:59.378  1028  1383 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-30 11:36:59.379  1028  1383 D WifiStateMachine: enableVerboseLogging : level 2
08-30 11:36:59.379  1028  1383 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-30 11:36:59.379  1028  1383 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-30 11:36:59.380  1028  1383 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-30 11:36:59.380  1028  1383 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-30 11:36:59.380  1028  1383 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-30 11:36:59.380  1028  1383 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-30 11:36:59.380  1028  1383 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-30 11:36:59.381  1028  1383 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-30 11:36:59.381  1028  1383 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-30 11:36:59.381  1028  1383 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-30 11:36:59.381  1028  1383 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-30 11:36:59.382  1028  1383 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
,08-30 11:36:59.382  1028  1383 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-30 11:36:59.382  1028  1383 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-30 11:36:59.383  1028  1383 D WifiStateMachine: Setting OUI to DA-A1-19
08-30 11:36:59.383  1028  1383 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-30 11:36:59.384  1028  1383 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-30 11:36:59.384  1028  1383 D WifiNative-HAL: Setting external_sim to 1
08-30 11:36:59.384  1028  1383 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-30 11:36:59.384  1933  1933 D WfdsService: Supplicant Connection state is changed : true
08-30 11:36:59.384  1933  2352 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-30 11:36:59.384  1933  2352 D WfdsService: Set the WFDS Monitor: true
08-30 11:36:59.384  1933  2352 D WfdsMonitor: WfdsMonitorThread create
08-30 11:36:59.384  1028  1383 D WifiNative-wlan0: SET external_sim 1: returned true
08-30 11:36:59.384  1028  1383 I WifiNative-HAL: startHal
08-30 11:36:59.384  1933  2352 D WfdsMonitor: WFDS Monitor is created and started
08-30 11:36:59.384  1028  1383 D wifi    : setting scan oui 0xaf6bdbc0
08-30 11:36:59.384  1933  2352 D WfdsService: WiFi: Supplicant connection re-established
08-30 11:36:59.385  1028  1383 D WifiStateMachine: Setting OUI to DA-A1-19
08-30 11:36:59.385  1028  1383 I WifiNative-HAL: startHal
08-30 11:36:59.385  1028  1383 D wifi    : setting scan oui 0xaf6bdbc0
08-30 11:36:59.386  1933  7057 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-30 11:36:59.386  1028  1383 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-30 11:36:59.386  1933  7057 E CtrlSupplicant: Succeed to open control connection
08-30 11:36:59.386  1933  7057 E CtrlSupplicant: Succeed to open monitor connection
08-30 11:36:59.386  1028  1383 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
,08-30 11:36:59.386  1028  1383 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-30 11:36:59.387  7041  7041 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-30 11:36:59.387  1933  7057 D WfdsMonitor: Supplicant connection established
08-30 11:36:59.387  1933  2352 D WfdsService: Connected to the supplicant for wfds
08-30 11:36:59.387  1028  1383 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-30 11:36:59.387  1028  1383 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-30 11:36:59.387  7041  7041 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-30 11:36:59.388  1028  1383 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-30 11:36:59.388  1028  1383 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-30 11:36:59.388  7041  7041 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-30 11:36:59.388  1028  1383 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-30 11:36:59.388  1028  1383 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-30 11:36:59.388  7041  7041 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-30 11:36:59.388  1028  1383 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-30 11:36:59.388  1028  1383 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-30 11:36:59.388  7041  7041 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-30 11:36:59.389  1028  1383 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-30 11:36:59.389  1028  1383 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-30 11:36:59.389  7041  7041 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-30 11:36:59.389  1028  1383 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-30 11:36:59.389  1028  1383 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-30 11:36:59.389  7041  7041 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-30 11:36:59.389  1028  1383 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-30 11:36:59.390  1028  1383 E WifiNative: : [120,420,076 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-30 11:36:59.390  1028  1383 D WifiNative-wlan0: doBoolean: RECONNECT
08-30 11:36:59.391  1028  1383 D WifiNative-wlan0: RECONNECT: returned true
08-30 11:36:59.391  1028  1383 D WifiNative-wlan0: doString: [STATUS]
08-30 11:36:59.391  1028  7053 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-30 11:36:59.391  1028  7053 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-30 11:36:59.392  1028  1383 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-30 11:36:59.392  1028  1383 D WifiNative-wlan0: doBoolean: SET ps 1
08-30 11:36:59.392  1028  1383 D WifiNative-wlan0: SET ps 1: returned true
08-30 11:36:59.392  1028  1379 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-30 11:36:59.392  1028  1028 D WifiScanningService: SCAN_AVAILABLE : 3
08-30 11:36:59.393  1028  1028 D RttService: SCAN_AVAILABLE : 3
08-30 11:36:59.393  1028  1548 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-30 11:36:59.393  1028  1547 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-30 11:36:59.393  1028  1547 I WifiNative-HAL: startHal
08-30 11:36:59.393  1028  1547 D wifi    : getting scan capabilities on interface[1] = 0xaf6bdbc0
08-30 11:36:59.393  1028  1547 D wifi    : failed to get capabilities : -3
08-30 11:36:59.393  1028  1547 E WifiScanningService: could not get scan capabilities
08-30 11:36:59.394  1028  1383 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0,
08-30 11:36:59.394   315   891 D CommandListener: Setting iface cfg
08-30 11:36:59.394   315   891 D CommandListener: Trying to bring up p2p0
08-30 11:36:59.394  1028  1383 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-30 11:36:59.394  1028  1383 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-30 11:36:59.395  1028  1383 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-30 11:36:59.395  1028  1383 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-30 11:36:59.396  1028  1383 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-30 11:36:59.396  1028  1383 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-30 11:36:59.396  1028  1383 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-30 11:36:59.396  7041  7041 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-30 11:36:59.397  1028  1383 E WifiStateMachine:  DisconnectedState what:132096 -100 0
,08-30 11:36:59.397  1028  1383 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-30 11:36:59.398  1028  1383 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-30 11:36:59.398  1028  1383 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-30 11:36:59.398  7041  7041 E wpa_supplicant: disconnect_rssi_lvl: -100
08-30 11:36:59.398  1028  1383 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
08-30 11:36:59.398  1028  1383 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
08-30 11:36:59.399  1028  1383 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
08-30 11:36:59.399  1028  1383 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-30 11:36:59.399  7041  7041 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-30 11:36:59.400  1028  1379 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-30 11:36:59.400  1028  1379 D LGWifiP2pService: P2pEnablingState
08-30 11:36:59.400  1028  1379 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-30 11:36:59.400  7041  7041 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 11:36:59.400  1028  7053 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-30 11:36:59.400  7041  7041 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-30 11:36:59.401  7041  7041 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 11:36:59.400  1028  7053 E WifiMonitor: WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 11:36:59.401  1028  7053 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 11:36:59.401  1028  7053 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 11:36:59.401  1028  7053 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 11:36:59.401  1028  1383 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-30 11:36:59.401  1028  7053 E WifiMonitor: WifiMonitor:p2p0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 11:36:59.401  1028  7053 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 11:36:59.401  1028  7053 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 11:36:59.401  7041  7041 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 11:36:59.401  1933  7057 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 11:36:59.401  1933  7057 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 11:36:59.401  1028  1383 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-30 11:36:59.402  1028  7053 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 11:36:59.402  1028  7053 E WifiMonitor: WifiMonitor:p2p0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 11:36:59.402  1028  7053 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 11:36:59.402  1028  1383 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-30 11:36:59.402  1028  7053 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 11:36:59.400  1028  1379 D LGWifiP2pService: P2p socket connection successful
08-30 11:36:59.402  1028  1379 D LGWifiP2pService: P2pEnabledState
08-30 11:36:59.402  1028  1383 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-30 11:36:59.402  1028  1383 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-30 11:36:59.402  7041  7041 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-30 11:36:59.403  7041  7041 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-30 11:36:59.403  1028  7053 D Wifi,Monitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-30 11:36:59.403  1028  7053 E WifiMonitor: WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-30 11:36:59.403  1028  7053 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-30 11:36:59.403  1028  7053 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-30 11:36:59.404  1028  1383 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-30 11:36:59.404  1028  1383 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-30 11:36:59.404  1933  1933 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-30 11:36:59.404  1933  1933 D WfdsService: WifiP2pState is changed : true
08-30 11:36:59.404  1028  1383 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-30 11:36:59.404  1028  1383 D WifiNative-wlan0: doBoolean: SCAN
08-30 11:36:59.404  1933  2352 D WfdsService: Receive the WFDS_ENABLE Method
08-30 11:36:59.404  1028  1383 D WifiNative-wlan0: SCAN: returned false
08-30 11:36:59.404  1933  2352 D WfdsService: Set the WFDS Monitor: true
08-30 11:36:59.404  1933  2352 D WfdsService: Connected to the supplicant for wfds
08-30 11:36:59.405  1933  2352 D WfdsJNI : doCommand: WFDS_SET TRUE
08-30 11:36:59.405  7041  7041 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-30 11:36:59.405  1933  2352 D WfdsService: selectPreferredScanChannel [36]
08-30 11:36:59.405  1933  2352 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-30 11:36:59.405  1028  1383 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=120435  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-30 11:36:59.407  1028  1379 D LGWifiP2pService: sending p2p connection changed broadcast
08-30 11:36:59.407  1595  1595 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 11:36:59.407  1595  1595 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 11:36:59.409  1028  1028 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 11:36:59.409  1028  1383 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=120439  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-30 11:36:59.409  1028  1028 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 11:36:59.409  1028  1028 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-30 11:36:59.409  1595  1595 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-30 11:36:59.412  1028  1379 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-30 11:36:59.413  1028  1028 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 11:36:59.413  1028  1028 D WifiServerServiceExt: setSupplicantStateSCANNING
08-30 11:36:59.414  1933  1933 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-30 11:36:59.414  1933  1933 D WfdsService: isConnected: false
08-30 11:36:59.415  1028  1379 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-30 11:36:59.415  1028  1383 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 11:36:59.415  1028  1379 D WifiNative-p2p0: doBoolean: SET device_name G3
08-30 11:36:59.416  1028  1383 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 11:36:59.416  1028  1379 D WifiNative-p2p0: SET device_name G3: returned true
08-30 11:36:59.416  1028  1379 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-30 11:36:59.416  1028  1379 D LGWifiP2pService: before postfix = G3
08-30 11:36:59.416  1028  1379 D WifiServerServiceExt: postfix byte check : 2
08-30 11:36:59.416  1028  1379 D LGWifiP2pService: after postfix = G3
08-30 11:36:59.416  1028  1379 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-30 11:36:59.416  1028  1383 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 11:36:59.416  1028  1379 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-30 11:36:59.416  1028  1379 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-30 11:36:59.416  1028  1383 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 11:36:59.417  1028  1379 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-30 11:36:59.417  1028  1379 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-30 11:36:59.417  1028  1383 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 11:36:59.417  1028  1379 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-30 11:36:59.417  1028  1379 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-30 11:36:59.417  1028  1379 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-30 11:36:59.417  1028  1379 D WifiNative-HAL: p2pGetDeviceAddress
08-30 11:36:59.417  1028  1379 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-30 11:36:59.418  1028  1379 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-30 11:36:59.418  1028  1379 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-30 11:36:59.419  1933  1933 I WfdStateTracker: handleP2pThisDeviceChanged
08-30 11:36:59.418  1028  1379 D WifiNative-p2p0: P2P_FLUSH: returned true
08-30 11:36:59.419  1933  1933 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-30 11:36:59.419  1028  1379 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-30 11:36:59.419  1933  1933 D WfdsService: Update P2p Interface State: 3
08-30 11:36:59.419  1028  1379 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-30 11:36:59.419  1028  1379 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-30 11:36:59.419  1028  1379 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-30 11:36:59.419  1028  1379 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-30 11:36:59.427  1028  1379 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-30 11:36:59.427  1028  1379 D LGWifiP2pService: sending p2p persistent groups changed broadcast
,08-30 11:36:59.427  1028  1379 D LGWifiP2pService: InactiveState
08-30 11:36:59.427  1028  1379 D LGWifiP2pService: InactiveState{ when=-26ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-30 11:36:59.427  1028  1379 D LGWifiP2pService: P2pEnabledState{ when=-26ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-30 11:36:59.427  1028  1379 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-30 11:36:59.428  7041  7041 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-30 11:36:59.428  7041  7041 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 11:36:59.429  7041  7041 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-30 11:36:59.429  7041  7041 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 11:36:59.430  7041  7041 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 11:36:59.430  1028  7053 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-30 11:36:59.430  1028  7053 E WifiMonitor: WifiMonitor:p2p0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 11:36:59.430  1028  7053 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 11:36:59.430  1028  7053 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 11:36:59.430  1028  7053 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 11:36:59.430  1028  7053 E WifiMonitor: WifiMonitor:p2p0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 11:36:59.430  1028  7053 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 11:36:59.430  1028  7053 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 11:36:59.430  1028  7053 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 11:36:59.430  1933  7057 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-30 11:36:59.430  1028  7053 E WifiMonitor: WifiMonitor:p2p0 cnt=30 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 11:36:59.430  1933  7057 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 11:36:59.430  1028  7053 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 11:36:59.430  1028  7053 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 11:36:59.430  1933  7057 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 11:36:59.431  1028  1379 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-30 11:36:59.433  1028  1379 D LGWifiP2pService: InactiveState{ when=-14ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-30 11:36:59.433  1028  1379 D LGWifiP2pService: P2pEnabledState{ when=-14ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-30 11:36:59.433  1028  1379 D LGWifiP2pService: InactiveState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-30 11:36:59.433  1028  1379 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-30 11:36:59.433  1028  1379 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-30 11:36:59.433  1028  1379 D LGWifiP2pService: InactiveState{ when=-1ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-30 11:36:59.433  1028  1379 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-30 11:36:59.433  1028  1379 D LGWifiP2pService: DefaultState{ when=-1ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-30 11:36:59,.433  1028  1379 D LGWifiP2pService: InactiveState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-30 11:36:59.433  1028  1379 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-30 11:36:59.433  1028  1379 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-30 11:36:59.433  1933  2352 W WfdsService: DefaultState - msg [9441285] is not handled
08-30 11:36:59.434  1028  1379 D LGWifiP2pService: InactiveState{ when=-2ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-30 11:36:59.434  1028  1379 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-30 11:36:59.434  1028  1379 D LGWifiP2pService: DefaultState{ when=-2ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-30 11:36:59.434  1028  1028 E WifiServerServiceExt: No p2p device connected
,08-30 11:36:59.478  7023  7023 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-30 11:36:59.515  7023  7023 I HubEmail: JNI_OnLoad()
08-30 11:36:59.515  7023  7023 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-30 11:36:59.515  7023  7023 I HubEmail: registerNatives()
,08-30 11:36:59.515  7023  7023 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-30 11:36:59.515  7023  7023 I HubEmail: registerNativeMethods()
08-30 11:36:59.515  7023  7023 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-30 11:36:59.515  7023  7023 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
08-30 11:36:59.519  3470  3470 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-30 11:36:59.519  3470  3470 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-30 11:36:59.520  3470  3470 I LgeMiscReceiver: networkInfo.isConnected() = false
08-30 11:36:59.583  1028  1578 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7065 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,08-30 11:36:59.591  7023  7063 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 11:36:59.594  6876  7062 W FormManager: Network not available. Please check & try again.
08-30 11:36:59.598  6876  7064 V FormManager: Network unavailable.
,08-30 11:36:59.601  6876  7064 V FormManager: Network unavailable.
08-30 11:36:59.608  1028  1914 I ActivityManager: Killing 6164:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
08-30 11:36:59.657  1028  2024 W libprocessgroup: failed to open /acct/uid_10080/pid_6164/cgroup.procs: No such file or directory
,08-30 11:36:59.752  7065  7065 D LgDataFeature: LgDataFeature() Constructor: none
08-30 11:36:59.752  7065  7065 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 11:36:59.756  7065  7065 D PhoneMonitor: Register our PhoneStateListener
08-30 11:36:59.781  7065  7065 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,08-30 11:36:59.787  7065  7065 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-30 11:36:59.806  7065  7065 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
08-30 11:36:59.807  7065  7065 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
08-30 11:36:59.807  7065  7065 D TelephonyAutoProfiling: [parse] Load xml
08-30 11:36:59.809  7065  7065 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
08-30 11:36:59.810  7065  7065 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
08-30 11:36:59.810  7065  7065 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-30 11:36:59.810  7065  7065 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
08-30 11:36:59.810  7065  7065 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
08-30 11:36:59.810  7065  7065 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
08-30 11:36:59.810  7065  7065 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-30 11:36:59.810  7065  7065 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-30 11:36:59.810  7065  7065 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-30 11:36:59.810  7065  7065 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-30 11:36:59.810  7065  7065 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-30 11:36:59.810  7065  7065 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-30 11:36:59.810  7065  7065 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-30 11:36:59.810  7065  7065 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-30 11:36:59.810  7065  7065 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-30 11:36:59.810  7065  7065 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-30 11:36:59.810  7065  7065 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
,08-30 11:36:59.816  7065  7065 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
08-30 11:36:59.864  1028  1968 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7084 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-30 11:36:59.865  1028  1968 I ActivityManager: Killing 6503:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,08-30 11:36:59.926  1028  1578 W libprocessgroup: failed to open /acct/uid_10061/pid_6503/cgroup.procs: No such file or directory
,08-30 11:36:59.979  1028  7053 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
,08-30 11:36:59.979  7041  7041 E wpa_supplicant: USIM:  scard_init function
08-30 11:36:59.979  1028  7053 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-30 11:36:59.979  7041  7041 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-30 11:36:59.979  1028  7053 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-30 11:36:59.979  1028  7053 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: WPS-AP-AVAILABLE 
08-30 11:36:59.980  1028  7053 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-30 11:36:59.980  1028  1383 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-30 11:36:59.980  1028  7053 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-30 11:36:59.980  1028  7053 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-30 11:36:59.980  1028  1383 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-30 11:36:59.983  1028  1383 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-30 11:36:59.983  1028  1383 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-30 11:36:59.983  1028  1383 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
,08-30 11:36:59.990  1028  1383 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=121020  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-30 11:36:59.994  1595  1595 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 11:36:59.994  1595  1595 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 11:36:59.995  1028  1028 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 11:36:59.995  1028  1028 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 11:36:59.995  1028  1028 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-30 11:36:59.996  1595  1595 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 11:37:00.000  1028  1028 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 11:37:00.000  1028  1028 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 11:37:00.000  1028  1028 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-30 11:37:00.001  1028  1383 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=121031  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-30 11:37:00.001  1028  1028 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 11:37:00.001  1028  1028 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-30 11:37:00.017  1595  1595 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 11:37:00.017  1595  1595 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 11:37:00.019  1595  1595 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-30 11:37:00.042  1595  1595 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,08-30 11:37:00.042  1595  1595 I KeyguardUpdateMonitor: called onTimeUpdated()
08-30 11:37:00.042  1595  1595 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-30 11:37:00.042  1595  1595 I [SystemUI]Clock: called onTimeUpdated()
08-30 11:37:00.044  1595  1595 I LgeClockWidgetControlView: called onTimeUpdated()
08-30 11:37:00.044  1595  1595 I [SystemUI]DateView: called onTimeUpdated()
08-30 11:37:00.045  1595  1595 I [SystemUI]DateView: called onTimeUpdated()
08-30 11:37:00.046  1595  1595 D KeyguardUpdateMonitor: handleTimeUpdate
08-30 11:37:00.101  7041  7041 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
08-30 11:37:00.103  1028  7053 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-30 11:37:00.103  1028  7053 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-30 11:37:00.104  1028  7053 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-30 11:37:00.104  1028  7053 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: Associated with f4:f2:6d:22:99:3e
,08-30 11:37:00.104  1028  7053 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 11:37:00.104  1028  7053 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-30 11:37:00.105  1028  1383 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=121134  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-30 11:37:00.106  1028  1383 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=121136  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-30 11:37:00.106  1028  1383 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=121136
08-30 11:37:00.108  1028  1383 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=121138
08-30 11:37:00.108  1028  1383 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=121138
08-30 11:37:00.109  1028  1383 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=121139
08-30 11:37:00.109  1028  1383 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=121139
08-30 11:37:00.110  1028  1383 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=121140  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-30 11:37:00.147  1028  1968 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7105 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
08-30 11:37:00.147  1028  7053 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 11:37:00.147  1028  7053 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-30 11:37:00.148  1028  1968 I ActivityManager: Killing 6194:com.google.android.apps.plus/u0a97 (adj 15): empty #17
08-30 11:37:00.149  7041  7041 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-30 11:37:00.149  7041  7041 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-30 11:37:00.149  1028  7053 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-30 11:37:00.149  1028  7053 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-30 11:37:00.149  1028  7053 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-30 11:37:00.149  1028  7053 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-30 11:37:00.149  1028  7053 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-30 11:37:00.150  1028  7053 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-30 11:37:00.153  1028  7053 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 11:37:00.153  1028  7053 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,08-30 11:37:00.260  1028  1877 W libprocessgroup: failed to open /acct/uid_10097/pid_6194/cgroup.procs: No such file or directory
,08-30 11:37:00.262  1028  1383 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=121291  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
,08-30 11:37:00.288  1595  1595 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-30 11:37:00.288  1595  1595 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 11:37:00.292  1595  1595 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 11:37:00.293  1028  1028 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 11:37:00.293  1028  1028 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 11:37:00.293  1028  1028 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
,08-30 11:37:00.305  1028  1028 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 11:37:00.305  1028  1028 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 11:37:00.305  1028  1028 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-30 11:37:00.306  1028  1110 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-30 11:37:00.306  1028  1383 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=121336  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-30 11:37:00.307  1028  1028 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 11:37:00.307  1028  1028 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-30 11:37:00.307  1028  1383 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=121337  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-30 11:37:00.308  1028  1383 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=121338
08-30 11:37:00.308  1028  1383 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=121338
08-30 11:37:00.309  1028  1383 D WifiNative-wlan0: doString: [STATUS]
08-30 11:37:00.310  1028  7053 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 11:37:00.310  1028  7053 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-30 11:37:00.311  1028  1383 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-30 11:37:00.312  1028  1383 I WifiServiceExtension: setVHTCapabilityType  : false
08-30 11:37:00.313  1595  1595 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 11:37:00.313  1595  1595 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 11:37:00.315  1595  1595 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-30 11:37:00.322  1028  1383 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-30 11:37:00.322  1028  1383 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
08-30 11:37:00.327  1028  1028 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 11:37:00.327  1028  1028 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 11:37:00.327  1028  1028 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,08-30 11:37:00.334  1028  1028 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 11:37:00.335  1028  1028 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 11:37:00.335  1028  1028 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-30 11:37:00.339  1595  1595 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 11:37:00.339  1595  1595 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 11:37:00.340  1595  1595 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 11:37:00.344  1595  1595 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 11:37:00.344  1595  1595 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-30 11:37:00.346  1595  1595 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 11:37:00.347  1028  1383 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-30 11:37:00.347  1028  1437 D ConnectivityService: Got NetworkAgent Messenger
08-30 11:37:00.347  1028  1437 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-30 11:37:00.347  1028  1437 D ConnectivityService: NetworkAgent connected
08-30 11:37:00.347  1028  1383 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-30 11:37:00.347  1028  1383 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-30 11:37:00.348  1028  1383 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-30 11:37:00.348  1028  1383 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-30 11:37:00.357  1028  1383 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-30 11:37:00.357  1028  1383 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-30 11:37:00.357  1028  1383 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
,08-30 11:37:00.360  1028  1383 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-30 11:37:00.360  1028  1383 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-30 11:37:00.365  1028  1383 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-30 11:37:00.367   315   891 D CommandListener: Setting iface cfg
08-30 11:37:00.395  1028  1914 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7130 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-30 11:37:00.398  1028  1914 I ActivityManager: Killing 6608:com.lge.eula/1000 (adj 15): empty #17
08-30 11:37:00.441  1028  1379 D LGWifiP2pService: InactiveState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-30 11:37:00.441  1028  1379 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-30 11:37:00.441  1028  1379 D LGWifiP2pService: DefaultState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,08-30 11:37:00.465  1028  1383 E WifiStateMachine: Start Dhcp Watchdog 2
08-30 11:37:00.467  1028  1383 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=121497  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 11:37:00.468  1028  1383 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=121498  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 11:37:00.469  1028  7129 D DhcpStateMachine: StoppedState
08-30 11:37:00.469  1028  7129 D DhcpStateMachine: StoppedState{ when=-4ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-30 11:37:00.469  1028  7129 D DhcpStateMachine: WaitBeforeStartState
08-30 11:37:00.473  1028  1383 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=121503  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 11:37:00.476  1028  1578 W libprocessgroup: failed to open /acct/uid_1000/pid_6608/cgroup.procs: No such file or directory
08-30 11:37:00.481  1028  1383 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=121511  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 11:37:00.483  1028  1383 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=121512  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 11:37:00.484  1028  1383 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=121514  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 11:37:00.486  1028  1383 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
08-30 11:37:00.486  1028  1383 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
08-30 11:37:00.487  1028  1383 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-30 11:37:00.487  1028  1383 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-30 11:37:00.487  1028  1383 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-30 11:37:00.488  1028  1383 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-30 11:37:00.490  1028  1383 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:75627] from screen [on:0 period:-623962039] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-30 11:37:00.491  1028  1383 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-623962037] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-30 11:37:00.491  1028  1383 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-30 11:37:00.496  1028  1437 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
08-30 11:37:00.497  1028  1383 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 11:37:00.497  1028  1383 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 11:37:00.498  1028  1383 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 11:37:00.498  1028  1383 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 11:37:00.499  1028  1383 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 11:37:00.499  1028  1383 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
,08-30 11:37:00.500  1028  1437 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-30 11:37:00.501  1028  1383 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=128,0,0
08-30 11:37:00.501  1028  1383 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=128,0,0
08-30 11:37:00.501  1028  1383 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-30 11:37:00.502  7041  7041 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-30 11:37:00.502  1028  1383 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-30 11:37:00.502  1028  1383 D WifiNative-wlan0: doBoolean: SET ps 0
08-30 11:37:00.503  1028  1383 D WifiNative-wlan0: SET ps 0: returned true
08-30 11:37:00.503  1028  1383 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-30 11:37:00.504  7041  7041 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
,08-30 11:37:00.504  1028  1383 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-30 11:37:00.504  1028  1383 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-30 11:37:00.504  1028  1383 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-30 11:37:00.505  1028  1383 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-30 11:37:00.505  1028  1379 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@25820390 target=com.android.internal.util.StateMachine$SmHandler }
08-30 11:37:00.505  1028  1379 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@25820390 target=com.android.internal.util.StateMachine$SmHandler }
08-30 11:37:00.506  1028  7129 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-30 11:37:00.506  1028  7129 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-30 11:37:00.507   315   891 D CommandListener: Setting iface cfg
08-30 11:37:00.509   315   891 D CommandListener: Trying to bring up wlan0
08-30 11:37:00.510  1028  1383 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-30 11:37:00.511  1028  1383 E WifiStateMachine:  ObtainingIpState CMD_STOP_SUPPLICANT_FAILED 1 0
08-30 11:37:00.512  1028  1383 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-30 11:37:00.512  1028  1383 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
08-30 11:37:00.513  1028  1383 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-30 11:37:00.513  1028  1383 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-30 11:37:00.513  1028  1383 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
08-30 11:37:00.514  7130  7130 I art     : Almond Protected OAT
08-30 11:37:00.514  1028  1383 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 11:37:00.514  1028  1383 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 11:37:00.516  1028  1383 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 11:37:00.516  1028  1383 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 11:37:00.517  1028  1383 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 11:37:00.517  1028  1383 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 11:37:00.517  1028  1437 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-30 11:37:00.518  1028  1383 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-30 11:37:00.518  1028  1383 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
,08-30 11:37:00.519  1028  1383 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-30 11:37:00.519  1028  1379 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 11:37:00.519  1028  1379 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 11:37:00.519  7041  7041 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-30 11:37:00.519  1028  1383 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-30 11:37:00.519  1028  1383 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-30 11:37:00.519  7041  7041 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-30 11:37:00.520  1028  1383 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-30 11:37:00.520  1028  1383 D WifiNative-wlan0: doBoolean: SET ps 1
08-30 11:37:00.526  1028  1028 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 11:37:00.526  1028  1028 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-30 11:37:00.527  1595  1595 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 11:37:00.535  1028  1383 D WifiNative-wlan0: SET ps 1: returned true
08-30 11:37:00.536  1028  1437 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-30 11:37:00.536  1028  1383 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-30 11:37:00.537  1028  1383 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-30 11:37:00.537  1028  1383 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-30 11:37:00.537  1028  1437 D ConnectivityService: ignoring duplicate network state non-change
,08-30 11:37:00.540  1028  1028 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 11:37:00.540  1028  1028 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 11:37:00.540  1028  1028 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-30 11:37:00.541  1595  1595 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 11:37:00.541  1595  1595 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 11:37:00.541  1028  1437 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-30 11:37:00.542  1028  1437 D ConnectivityService: Adding iface wlan0 to network 101
08-30 11:37:00.542  1595  1595 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 11:37:00.542  1028  1383 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-30 11:37:00.544  1028  1028 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 11:37:00.544  1028  1028 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 11:37:00.544  1028  1028 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-30 11:37:00.544  1028  1028 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-30 11:37:00.549  1933  1933 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-30 11:37:00.549  1028  1028 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 11:37:00.549  1028  1028 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 11:37:00.549  1028  1028 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
,08-30 11:37:00.550  1028  1028 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-30 11:37:00.553  1028  1028 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 11:37:00.553  1028  1028 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 11:37:00.553  1028  1028 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-30 11:37:00.564  1595  1595 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-30 11:37:00.564  1595  1595 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 11:37:00.565  1595  1595 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 11:37:00.566  1028  1437 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-30 11:37:00.566  1028  1437 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
08-30 11:37:00.567  1028  1437 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
08-30 11:37:00.567   315   891 E Netd    : netlink response contains error (File exists)
08-30 11:37:00.567  1595  1595 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 11:37:00.567  1595  1595 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-30 11:37:00.567  1595  1595 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 11:37:00.568  1028  1437 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
08-30 11:37:00.568  1028  1437 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-30 11:37:00.568  1028  1437 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
08-30 11:37:00.568  1028  1437 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
08-30 11:37:00.569  1028  1437 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-30 11:37:00.569  1028  1437 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-30 11:37:00.569  1028  1437 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-30 11:37:00.570  1028  7126 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-30 11:37:00.570  1028  7126 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-30 11:37:00.570  1028  7126 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-30 11:37:00.570  1028  7126 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-30 11:37:00.572  1028  1437 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-30 11:37:00.572  1595  1595 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 11:37:00.572  1028  1437 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 11:37:00.572  1595  1595 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-30 11:37:00.572  1028  1437 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 11:37:00.572  1028  1437 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-30 11:37:00.572  1028  1437 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 11:37:00.572  1028  1437 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-30 11:37:00.572  1595  1595 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 11:37:00.572  1028  1437 D ConnectivityService: currentScore = 0, newScore = 20
08-30 11:37:00.572  1028  1437 D ConnectivityService:    acc,epting network in place of null
08-30 11:37:00.572  1028  1437 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 11:37:00.573  1028  1383 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 11:37:00.573  1028  1383 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 11:37:00.573   315  7150 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-30 11:37:00.573  1843  1843 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 11:37:00.574  1843  1843 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-30 11:37:00.574  1028  1437 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-30 11:37:00.574  1028  1437 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-30 11:37:00.574  1028  1437 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-30 11:37:00.574  1028  1437 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-30 11:37:00.576  1028  1028 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-30 11:37:00.576  1028  1028 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-30 11:37:00.576  1028  1028 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-30 11:37:00.576  1028  1028 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-30 11:37:00.576  1028  1437 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-30 11:37:00.578  1028  1437 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,08-30 11:37:00.579  1028  1437 D ConnectivityService: validation of new default Network = false
08-30 11:37:00.579  1028  1437 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-30 11:37:00.579  1028  1437 D DSQN    : enableDataServiceNotify 
08-30 11:37:00.579  1028  1437 D DSQN    : start dsqn bin
08-30 11:37:00.582  1028  1378 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
08-30 11:37:00.586  7130  7130 D WeatherApplication: removeAccount
08-30 11:37:00.587  7130  7130 D WeatherApplication: Account.length = 0
08-30 11:37:00.587  7130  7130 E WeatherApplication: OPERATOR:OPEN
08-30 11:37:00.588  1028  1437 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-30 11:37:00.588  1028  1437 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 11:37:00.588  1028  1437 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 11:37:00.588  1028  1437 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 11:37:00.589  1595  2063 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-30 11:37:00.577  7151  7151 W dsqn    : type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6837 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 11:37:00.577  7151  7151 W dsqn    : type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6837 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 11:37:00.599  7130  7130 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:37:0
,08-30 11:37:00.601  7151  7151 E DSQN    : DSQN ssw
08-30 11:37:00.603  7130  7130 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-30 11:37:00.603  7130  7130 D Weather.Utils: 2 : All the weather widget is gone.
08-30 11:37:00.606  7130  7130 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-30 11:37:00.607  1808  7153 I CheckinService: active receiver: enabled
08-30 11:37:00.609  1595  1595 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-30 11:37:00.610  1595  1595 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 11:37:00.611  7130  7130 D WeatherAncestor: connectivity changed - connection : true
08-30 11:37:00.611  1595  1595 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 11:37:00.611  7130  7130 D WeatherService: 2 : isServiceAlived():false forecastCache:null
,08-30 11:37:00.614  1808  7153 I CheckinService: Preparing to send checkin request
08-30 11:37:00.614  1808  7153 I EventLogService: Accumulating logs since 1472549757280
08-30 11:37:00.618  7130  7130 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-30 11:37:00.619  7130  7130 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-30 11:37:00.619  7130  7130 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
,08-30 11:37:00.627   315  7150 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-30 11:37:00.631  7130  7130 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-30 11:37:00.631  7130  7130 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:37:0
08-30 11:37:00.666   315  7150 D libc-netbsd: res_queryN name = clients3.google.com succeed
,08-30 11:37:00.669  1028  2040 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7158 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-30 11:37:00.670  1028  2040 I ActivityManager: Killing 6628:com.lge.bnr/1000 (adj 15): empty #17
08-30 11:37:00.691   315   890 D LGDataListener: argv[0]=dsqncommand
08-30 11:37:00.691   315   890 D LGDataListener: argv[1]=wlan0
08-30 11:37:00.691   315   890 D LGDataListener: argv[2]=1
08-30 11:37:00.691   315   890 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
,08-30 11:37:00.691  1028  1108 D DSQN    : DSQM DsqnNotification wlan0  1
08-30 11:37:00.691  1028  1108 D DSQN    : start to monitor internet connection
08-30 11:37:00.708  1028  7129 D DhcpStateMachine: DHCPV4 request on wlan0
,08-30 11:37:00.710  1028  7129 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-30 11:37:00.710  1028  7129 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-30 11:37:00.707  7177  7177 W dhcpcd  : type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6837 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 11:37:00.707  7177  7177 W dhcpcd  : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6837 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 11:37:00.720  1028  7126 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 30 Aug 2016 09:37:00 GMT], X-Android-Received-Millis=[1472549820719], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472549820691]}
08-30 11:37:00.720  1028  7126 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-30 11:37:00.721  1028  7126 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-30 11:37:00.721  1028  1437 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
08-30 11:37:00.721  1028  1437 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-30 11:37:00.722  1028  1437 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 11:37:00.722  1028  1437 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 11:37:00.722  1028  1437 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-30 11:37:00.722  1028  1437 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
08-30 11:37:00.722  1028  1437 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-30 11:37:00.723  1028  1437 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-30 11:37:00.723  1028  1437 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 11:37:00.723  7177  7177 I dhcpcd  : version 5.5.6 starting
08-30 11:37:00.724  1028  1437 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 11:37:00.725  7177  7177 E dhcpcd  : get_duid: m
08-30 11:37:00.725  7177  7177 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-30 11:37:00.725  7177  7177 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-30 11:37:00.726  1595  2063 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-30 11:37:00.726  1028  1437 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 11:37:00.726  1028  1383 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 11:37:00.726  1028  1437 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-30 11:37:00.726  1028  1383 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 11:37:00.727  1843  1843 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 11:37:00.729  1843  1843 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-30 11:37:00.746  1808  7153 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
08-30 11:37:00.746  1028  1878 W libprocessgroup: failed to open /acct/uid_1000/pid_6628/cgroup.procs: No such file or directory
,08-30 11:37:00.778  1595  1595 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-30 11:37:00.780  1595  1595 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 11:37:00.780  1595  1595 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 11:37:00.801  7177  7177 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
,08-30 11:37:00.801  7177  7177 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-30 11:37:00.801  7177  7177 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-30 11:37:00.801  7177  7177 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
08-30 11:37:00.801  7177  7177 D dhcpcd  : wlan0: sending REQUEST (xid 0x438a0895), next in 3.84 seconds
08-30 11:37:00.843   278   455 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-30 11:37:00.843   278   455 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-30 11:37:00.843   278   455 W Vold    : Returning OperationFailed - no handler for errno 0
,08-30 11:37:00.844  7158  7185 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-30 11:37:00.847   278   455 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-30 11:37:00.847   278   455 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-30 11:37:00.847   278   455 W Vold    : Returning OperationFailed - no handler for errno 0
08-30 11:37:00.847  7158  7185 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-30 11:37:00.856   278   455 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-30 11:37:00.856   278   455 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-30 11:37:00.856   278   455 W Vold    : Returning OperationFailed - no handler for errno 0
08-30 11:37:00.856  7158  7189 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,08-30 11:37:00.858  7177  7177 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
08-30 11:37:00.858   278   455 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-30 11:37:00.858   278   455 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-30 11:37:00.858   278   455 W Vold    : Returning OperationFailed - no handler for errno 0
08-30 11:37:00.859  1028  2024 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7187 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
08-30 11:37:00.859  7158  7189 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-30 11:37:00.885  7177  7177 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
08-30 11:37:00.885  7177  7177 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
08-30 11:37:00.885  7177  7177 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-30 11:37:00.885  7177  7177 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-30 11:37:00.885  7177  7177 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-30 11:37:00.885  7177  7177 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-30 11:37:00.885  7177  7177 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-30 11:37:00.885  7177  7177 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,08-30 11:37:00.916  7187  7187 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-30 11:37:00.916  7187  7187 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-30 11:37:00.933  7187  7187 I MultiDex: VM with version 2.1.0 has multidex support
08-30 11:37:00.933  7187  7187 I MultiDex: install
08-30 11:37:00.933  7187  7187 I MultiDex: VM has multidex support, MultiDex support library is disabled.
08-30 11:37:00.942  7187  7187 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,08-30 11:37:01.053  7158  7158 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-30 11:37:01.067  7158  7158 I LibraryLoader: Loading: webviewchromium
,08-30 11:37:01.069  7158  7158 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 2111-2114)
08-30 11:37:01.069  7158  7158 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-30 11:37:01.072  7158  7158 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {d378306}
08-30 11:37:01.073  7158  7158 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-30 11:37:01.074  7158  7158 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-30 11:37:01.082  7158  7158 I BrowserStartupController: Initializing chromium process, renderers=0
08-30 11:37:01.082  7158  7158 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-30 11:37:01.092   320  2150 V AudioPolicyService: registerClient() client 0xb558a540, uid 10093
08-30 11:37:01.093  7158  7248 W AudioManagerAndroid: Requires BLUETOOTH permission
08-30 11:37:01.093  7158  7158 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-30 11:37:01.094  7158  7158 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
08-30 11:37:01.095  7158  7158 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
,08-30 11:37:01.110  7158  7158 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-30 11:37:01.110  7158  7158 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-30 11:37:01.110  7158  7158 I Adreno-EGL: Build Date: 12/12/14 금
08-30 11:37:01.110  7158  7158 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-30 11:37:01.110  7158  7158 I Adreno-EGL: Remote Branch: 
08-30 11:37:01.110  7158  7158 I Adreno-EGL: Local Patches: 
08-30 11:37:01.110  7158  7158 I Adreno-EGL: Reconstruct Branch: 
08-30 11:37:01.115  1028  7129 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,08-30 11:37:01.116  1028  7129 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-30 11:37:01.116  1028  7129 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-30 11:37:01.116  1028  7129 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
08-30 11:37:01.116  1028  7129 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-30 11:37:01.116  1028  7129 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-30 11:37:01.116  1028  7129 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-30 11:37:01.116  1028  7129 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-30 11:37:01.116  1028  7129 D DhcpStateMachine: RunningState
08-30 11:37:01.209  7158  7158 I NSApplication: Starting up...
,08-30 11:37:01.286  7187  7206 D LgDataFeature: LgDataFeature() Constructor: none
,08-30 11:37:01.286  7187  7206 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 11:37:01.307  1028  2040 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7261 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,08-30 11:37:01.308  1028  1932 I ActivityManager: Killing 2124:com.lge.music/u0a34 (adj 15): empty #17
08-30 11:37:01.337   344   344 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 483us total 30.514ms
,08-30 11:37:01.340   320  1389 V AudioFlinger: 2124 died, releasing its sessions
08-30 11:37:01.340   320  1389 V AudioFlinger:  pid 1843 @ 0
08-30 11:37:01.340   320  1389 V AudioFlinger:  pid 3470 @ 1
08-30 11:37:01.340   320  1389 V AudioFlinger:  pid 3470 @ 2
08-30 11:37:01.357   344   344 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 453us total 19.329ms
,08-30 11:37:01.375   344   344 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 355us total 17.264ms
,08-30 11:37:01.407  1028  1567 W libprocessgroup: failed to open /acct/uid_10034/pid_2124/cgroup.procs: No such file or directory
,08-30 11:37:01.413  1028  1043 D WifiServiceImplEx: setWifiEnabled: false pid=6540, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-30 11:37:01.413  1028  1043 D WifiService: setWifiEnabled: false pid=6540, uid=10118
08-30 11:37:01.413  1028  1043 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 11:37:01.424  1028  1383 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-30 11:37:01.425  1028  1383 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-30 11:37:01.425  1028  1383 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-30 11:37:01.425  1028  1383 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-30 11:37:01.425  1028  1383 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-30 11:37:01.425  1028  1383 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-30 11:37:01.425  1028  1383 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-30 11:37:01.425  1028  1383 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-30 11:37:01.426  1028  1383 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-30 11:37:01.426  1028  1383 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-30 11:37:01.429  1028  1028 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-30 11:37:01.430  1028  1028 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-30 11:37:01.430  1028  1028 D Ulp_jni : JNI:system_update. Event-4
08-30 11:37:01.432  1028  1383 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-30 11:37:01.432  1028  1383 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-30 11:37:01.432  7041  7041 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-30 11:37:01.432  1028  1379 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 11:37:01.432  1028  1379 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 11:37:01.433  1028  1383 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-30 11:37:01.433  1028  1383 D WifiNative-wlan0: doBoolean: SET ps 1
08-30 11:37:01.433  1028  1383 D WifiNative-wlan0: SET ps 1: returned true
08-30 11:37:01.433  1028  7129 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-30 11:37:01.440   315   891 D CommandListener: Clearing all IP addresses on wlan0
,08-30 11:37:01.442  7261  7261 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 11:37:01.444  1028  1368 D PowerManagerServiceEx: acquireWakeLockInternal: lock=774595123, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1028
08-30 11:37:01.459  7279  7279 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=32 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-30 11:37:01.465  1028  1437 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-30 11:37:01.465  1028  1437 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
08-30 11:37:01.489  1028  1437 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-30 11:37:01.489  1028  1437 D DSQN    : disableDataServiceNotify
08-30 11:37:01.489  1028  1437 D DSQN    : stop dsqn bin
,08-30 11:37:01.493  1028  1368 I ActivityManager: Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=7286 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-30 11:37:01.494  1028  1368 V AlarmManager: RTC_WAKEUP set : Alarm{6d689f0 type 0 when 1472549815768 com.android.vending} when 1472549815768
08-30 11:37:01.498  1028  1437 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
08-30 11:37:01.498  1028  1437 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 11:37:01.498  1028  1437 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 11:37:01.499  1028  1437 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 11:37:01.499  1028  1437 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-30 11:37:01.499  1028  7126 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-30 11:37:01.499  1028  7126 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-30 11:37:01.499  1028  7126 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-30 11:37:01.499  1028  1437 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-30 11:37:01.499  1028  1437 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-30 11:37:01.499  1028  1437 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-30 11:37:01.500  1028  1437 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-30 11:37:01.500  1028  1437 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-30 11:37:01.500  1028  1028 D WifiHS20: hidePasspointNotification off =false
08-30 11:37:01.500  1595  2063 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-30 11:37:01.500  1028  1437 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-30 11:37:01.500  1028  1028 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 11:37:01.500  1028  1437 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 11:37:01.500  1028  1028 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 11:37:01.500  1028  1437 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 11:37:01.500  1028  1028 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-30 11:37:01.500  193,3  1933 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-30 11:37:01.500  1028  1437 D NetworkManagementService: Removing idletimer
08-30 11:37:01.500  1028  1437 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 11:37:01.500  1028  1437 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-30 11:37:01.500  1843  1843 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 11:37:01.501  1843  1843 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-30 11:37:01.501  1028  1379 D LGWifiP2pService: InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-30 11:37:01.501  1028  1379 D LGWifiP2pService: P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-30 11:37:01.501  1028  1379 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@2c09a895
08-30 11:37:01.501  1028  1378 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-30 11:37:01.501  1028  1383 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 11:37:01.502  1028  1383 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 11:37:01.502  1028  1383 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 11:37:01.502  1028  1383 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 11:37:01.503  1028  1383 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 11:37:01.503  1028  1383 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 11:37:01.503  1028  1383 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-30 11:37:01.503  1028  1383 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-30 11:37:01.503  1028  1383 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 11:37:01.505  1028  1028 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-30 11:37:01.505  1028  1378 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-30 11:37:01.505  1028  1028 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-30 11:37:01.505  1028  1028 D WifiHS20: hidePasspointNotification off =false
08-30 11:37:01.505  1028  1028 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 11:37:01.506  1028  1028 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 11:37:01.506  1028  1028 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-30 11:37:01.506  1028  1028 D WifiScanningService: SCAN_AVAILABLE : 1
08-30 11:37:01.506  1028  1028 D RttService: SCAN_AVAILABLE : 1
08-30 11:37:01.506  1028  1028 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-30 11:37:01.506  1028  1028 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-30 11:37:01.506  1028  1028 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-30 11:37:01.506  1028  1028 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-30 11:37:01.506  1028  1028 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-30 11:37:01.506  1028  1028 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-30 11:37:01.506  1028  1547 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-30 11:37:01.506  1028  1548 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-30 11:37:01.510  1028  1379 D LGWifiP2pService: P2pDisablingState
08-30 11:37:01.510  1028  1379 D LGWifiP2pService: P2pDisablingState{ when=-9ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-30 11:37:01.510  1028  1379 D LGWifiP2pService: p2p socket connection lost
08-30 11:37:01.510  1028  1379 D LGWifiP2pService: P2pDisabledState
08-30 11:37:01.511  1933  1933 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-30 11:37:01.511  1933  1933 D WfdsService: WifiP2pState is changed : false
08-30 11:37:01.511  1933  2352 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-30 11:37:01.511  1933  2352 D WfdsService: Set the WFDS Monitor: false
08-30 11:37:01.512  1028  1383 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-30 11:37:01.512  1028  1383 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-30 11:37:01.512  7041  7041 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-30 11:37:01.513  1595  1595 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 11:37:01.513  1595  1595 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 11:37:01.514  1028  1383 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-30 11:37:01.514  1028  1383 D WifiNative-wlan0: doBoolean: SET ps 1
08-30 11:37:01.514  1028  1379 D LGWifiP2pService: P2pDisabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 11:37:01.514,  1028  1379 D LGWifiP2pService: DefaultState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 11:37:01.514  1028  1383 D WifiNative-wlan0: SET ps 1: returned true
08-30 11:37:01.514   315   891 D CommandListener: Clearing all IP addresses on wlan0
08-30 11:37:01.516  1028  1383 D WifiNative-p2p0: doBoolean: TERMINATE
08-30 11:37:01.516  1028  1383 D WifiNative-p2p0: TERMINATE: returned true
08-30 11:37:01.516  1028  1383 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-30 11:37:01.516  1028  1383 E WifiStateMachine: useWiFiOffloading() : false
08-30 11:37:01.516  1028  1383 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-30 11:37:01.516  1028  1028 D WifiHS20: hidePasspointNotification off =false
08-30 11:37:01.521  1933  2352 D WfdsMonitor: WFDS Monitor is stopped
08-30 11:37:01.521  1933  7057 D CtrlSupplicant: Received on exit socket, terminate
08-30 11:37:01.521  1933  2352 D WfdsService: STATE : WfdsDisabledState - enter
08-30 11:37:01.521  1933  7057 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-30 11:37:01.521  1933  7057 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-30 11:37:01.521  1933  7057 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-30 11:37:01.522  1933  2353 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-30 11:37:01.522  1933  2352 W WfdsService: DefaultState - msg [9445378] is not handled
08-30 11:37:01.522  1595  1595 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 11:37:01.523  1028  1028 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 11:37:01.523  1028  1028 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 11:37:01.523  1028  1028 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-30 11:37:01.524  1028  1028 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-30 11:37:01.524  1028  1028 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 11:37:01.524  1028  1028 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-30 11:37:01.524  1933  1933 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-30 11:37:01.525  6540  6540 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 11:37:01.525  6540  6540 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 11:37:01.525  6540  6540 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 11:37:01.525  6540  6540 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 11:37:01.525  6540  6540 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 11:37:01.525  6540  6540 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 11:37:01.525  6540  6540 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 11:37:01.525  6540  6540 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 11:37:01.525  6540  6540 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 11:37:01.525  6540  6540 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 11:37:01.526  6540  6540 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 11:37:01.529  6540  6540 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 11:37:01.529  6540  6540 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 11:37:01.529  6540  6540 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 11:37:01.529  6540  6540 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 11:37:01.529  6540  6540 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 11:37:01.529  6540  6540 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enab,led: false
08-30 11:37:01.529  6540  6540 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 11:37:01.529  6540  6540 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 11:37:01.529  6540  6540 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 11:37:01.529  6540  6540 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 11:37:01.529  6540  6540 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 11:37:01.538  7279  7279 I dex2oat : dex2oat took 79.073ms (threads: 4)
08-30 11:37:01.549  7187  7206 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-30 11:37:01.549  7187  7206 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-30 11:37:01.549  7187  7206 I Adreno-EGL: Build Date: 12/12/14 금
08-30 11:37:01.549  7187  7206 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-30 11:37:01.549  7187  7206 I Adreno-EGL: Remote Branch: 
08-30 11:37:01.549  7187  7206 I Adreno-EGL: Local Patches: 
08-30 11:37:01.549  7187  7206 I Adreno-EGL: Reconstruct Branch: 
,08-30 11:37:01.589  1028  1437 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-30 11:37:01.622  7187  7206 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-30 11:37:01.622  7187  7206 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-30 11:37:01.622  7187  7206 I Adreno-EGL: Build Date: 12/12/14 금
08-30 11:37:01.622  7187  7206 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-30 11:37:01.622  7187  7206 I Adreno-EGL: Remote Branch: 
08-30 11:37:01.622  7187  7206 I Adreno-EGL: Local Patches: 
08-30 11:37:01.622  7187  7206 I Adreno-EGL: Reconstruct Branch: 
,08-30 11:37:01.635  1028  1967 I art     : Explicit concurrent mark sweep GC freed 111767(5MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/64MB, paused 1.517ms total 100.614ms
,08-30 11:37:01.638  7041  7041 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-30 11:37:01.639  7041  7041 I wpa_supplicant: monitor socket send errors count : 1
08-30 11:37:01.639  7041  7041 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1933-4\x00 that cannot receive messages
08-30 11:37:01.641  1028  7053 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-30 11:37:01.641  1028  7053 D WifiMonitor: Dropping event because (p2p0) is stopped
08-30 11:37:01.662  1028  7129 D DhcpStateMachine: StoppedState
08-30 11:37:01.663  1028  7129 D DhcpStateMachine: StoppedState{ when=-149ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,08-30 11:37:01.663  7041  7041 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-30 11:37:01.664  7041  7041 W wpa_supplicant: USIM:  scard_deinit function
08-30 11:37:01.664  1028  1383 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-30 11:37:01.665  1028  1383 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-30 11:37:01.665  1028  7053 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-30 11:37:01.665  1028  7053 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-30 11:37:01.665  1028  7053 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-30 11:37:01.665  1028  7053 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-30 11:37:01.665  1028  7053 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 11:37:01.665  1028  7053 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-30 11:37:01.666  1028  1383 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=122696
08-30 11:37:01.666  1028  1110 D Tethering: InitialState.processMessage what=4
08-30 11:37:01.666  1028  1383 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=122696
08-30 11:37:01.666  1028  1110 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-30 11:37:01.667  1028  1383 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=122697  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-30 11:37:01.668  1028  1383 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=122697  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-30 11:37:01.668  1028  1383 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-30 11:37:01.669  1028  1383 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-30 11:37:01.672  1595  1595 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-30 11:37:01.674  1595  1595 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-30 11:37:01.675  1595  1595 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-30 11:37:01.705  1595  1595 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-30 11:37:01.706  1595  1595 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 11:37:01.707  1595  1595 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 11:37:01.707  1595  1595 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 11:37:01.707  1595  1595 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 11:37:01.708  1595  1595 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 11:37:01.709  1595  1595 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-30 11:37:01.709  1595  1595 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 11:37:01.711  1595  1595 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 11:37:01.716  2569  2569 D [Concierge]Service: onStartCommand(). Type : 9
,08-30 11:37:01.718  1595  1595 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 11:37:01.730  7187  7206 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-30 11:37:01.730  7187  7206 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-30 11:37:01.730  7187  7206 I Adreno-EGL: Build Date: 12/12/14 금
08-30 11:37:01.730  7187  7206 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-30 11:37:01.730  7187  7206 I Adreno-EGL: Remote Branch: 
08-30 11:37:01.730  7187  7206 I Adreno-EGL: Local Patches: 
08-30 11:37:01.730  7187  7206 I Adreno-EGL: Reconstruct Branch: 
,08-30 11:37:01.794  6373  6373 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-30 11:37:01.795  7041  7041 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-30 11:37:01.796  1028  7053 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ],
08-30 11:37:01.796  1028  7053 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-TERMINATING 
08-30 11:37:01.796  1028  7053 D WifiMonitor: Disconnecting from the supplicant, no more events
08-30 11:37:01.796  1028  1383 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 44 0
08-30 11:37:01.801  6373  6401 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-30 11:37:01.810  2195  2195 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-30 11:37:01.816  7286  7286 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
08-30 11:37:01.818  6972  6972 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-30 11:37:01.818  6972  6972 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-30 11:37:01.818  6972  6972 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-30 11:37:01.818  6972  6972 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-30 11:37:01.820  6972  6972 I AppUp4:CustModeStarterReceiver: onReceive
,08-30 11:37:01.827  6972  6972 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@23ac54df
08-30 11:37:01.827  6972  6972 D AppUp4:CustFacade: isCustomizationCompleted : false
08-30 11:37:01.827  6972  6972 D AppUp4:CustFacade: isPhone : true
08-30 11:37:01.828  6972  6972 D AppUp4:CustModeStarterReceiver: begin check event
08-30 11:37:01.828  6972  6972 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-30 11:37:01.835  4330  4330 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-30 11:37:01.835  4330  4330 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-30 11:37:01.836  4330  4330 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 11:37:01.838  4330  4330 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-30 11:37:01.843  4330  7328 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-30 11:37:01.851  7023  7023 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-30 11:37:01.854  4330  7332 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-30 11:37:01.854  4330  7332 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null,
08-30 11:37:01.866  7023  7339 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 11:37:01.869  3470  3470 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-30 11:37:01.869  3470  3470 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-30 11:37:01.869  3470  3470 I LgeMiscReceiver: networkInfo.isConnected() = false
08-30 11:37:01.873  7065  7065 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-30 11:37:01.873  7065  7065 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-30 11:37:01.874  6876  7341 W FormManager: Network not available. Please check & try again.
08-30 11:37:01.877  7286  7286 D LgDataFeature: LgDataFeature() Constructor: none
,08-30 11:37:01.877  7286  7286 D LgDataFeature: LgDataFeature() Constructor Done, null
08-30 11:37:01.881  7130  7130 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:37:1
08-30 11:37:01.881   315  7344 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-30 11:37:01.882  1028  1108 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-30 11:37:01.882  1808  7153 E CheckinTask: Checkin failed: https://android.clients.google.com/checkin (request #0): java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
08-30 11:37:01.890  7130  7130 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
,08-30 11:37:01.890  7130  7130 D Weather.Utils: 2 : All the weather widget is gone.
,08-30 11:37:01.891  7130  7130 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-30 11:37:01.891  7130  7130 D WeatherAncestor: connectivity changed - connection : true
08-30 11:37:01.891  7130  7130 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@13b70bf5
08-30 11:37:01.892  7130  7130 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-30 11:37:01.892  7130  7130 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-30 11:37:01.892  7130  7130 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-30 11:37:01.892  7130  7130 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-30 11:37:01.892  7130  7130 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:37:1
08-30 11:37:01.895  6876  7342 V FormManager: Network unavailable.
08-30 11:37:01.895  1808  7153 I CheckinService: active receiver: disabled
,08-30 11:37:01.908  1028  1383 D WifiOffDelayIfNotUsed: stopMonitoring
08-30 11:37:01.908  1028  1383 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-30 11:37:01.908  1028  1383 E WifiStateMachine: useWiFiOffloading() : false
08-30 11:37:01.908  1028  1383 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-30 11:37:01.909  1933  1933 D WfdsService: Supplicant Connection state is changed : false
08-30 11:37:01.909  1933  2352 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-30 11:37:01.909  1933  2352 D WfdsService: Set the WFDS Monitor: false
08-30 11:37:01.909  1933  2352 D WfdsMonitor: WFDS Monitor is stopped
08-30 11:37:01.910  1595  1595 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 11:37:01.910  6876  7342 V FormManager: Network unavailable.
08-30 11:37:01.911  6540  6540 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 11:37:01.912  6540  6540 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 11:37:01.912  7286  7286 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
08-30 11:37:01.912  1933  1933 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-30 11:37:01.913  2500  2500 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 11:37:01.913  1028  1028 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-30 11:37:01.913  1028  1395 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-30 11:37:01.913  1028  1395 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-30 11:37:01.923  6767  6767 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-30 11:37:01.923  6767  6767 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-30 11:37:01.924  6767  6767 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-30 11:37:01.924  6767  6767 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-30 11:37:01.924  7286  7286 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
08-30 11:37:01.924  7286  7286 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-30 11:37:01.926  6767  6767 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-30 11:37:01.927  6767  6767 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-30 11:37:01.927  6767  6767 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-30 11:37:01.927  6767  6767 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-30 11:37:01.927  6767  6767 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-30 11:37:01.927  6767  6767 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-30 11:37:01.927  6767  6767 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-30 11:37:01.933  6788  6788 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-30 11:37:01.933  7286  7286 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-30 11:37:01.933  7286  7286 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
08-30 11:37:01.935  6767  6767 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-30 11:37:01.943  6876  7349 W FormManager: Network not available. Please check & try again.
08-30 11:37:01.948  6876  7350 V FormManager: Network unavailable.
,08-30 11:37:01.950  6767  6767 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 11:37:01.950  6876  7350 V FormManager: Network unavailable.
08-30 11:37:01.952  3527  3544 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
08-30 11:37:01.953  3527  3544 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@3502bb42 on behalf of 7286
08-30 11:37:01.963  6788  6788 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-30 11:37:01.963  7286  7286 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,08-30 11:37:01.965  6767  6767 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-30 11:37:01.969  6767  6767 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 11:37:01.975  6876  7354 W FormManager: Network not available. Please check & try again.
08-30 11:37:01.976  6876  7355 V FormManager: Network unavailable.
08-30 11:37:01.978  6876  7355 V FormManager: Network unavailable.
,08-30 11:37:01.980  7286  7286 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
08-30 11:37:01.981  4330  4330 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-30 11:37:01.981  4330  4330 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-30 11:37:01.982  4330  4330 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 11:37:01.985  4330  4330 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 11:37:01.987  6373  6373 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 11:37:01.988  4330  7357 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-30 11:37:01.989  1028  1710 V SIM_STK : Menu title from STK is T-Mobile
,08-30 11:37:01.991  6767  6767 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-30 11:37:01.993  4330  7358 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-30 11:37:01.993  4330  7358 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-30 11:37:01.996  6767  6767 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 11:37:02.002  6836  6836 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 11:37:02.002  6836  6836 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-30 11:37:02.003  6836  6836 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-30 11:37:02.040  1028  1877 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7359 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-30 11:37:02.111  7286  7286 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.
,08-30 11:37:02.114  1028  1567 I ActivityManager: Killing 6810:com.lge.lifetracker/u0a37 (adj 15): empty #17
,08-30 11:37:02.208  1028  1932 W libprocessgroup: failed to open /acct/uid_10037/pid_6810/cgroup.procs: No such file or directory
,08-30 11:37:02.225  7359  7359 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-30 11:37:02.226  7359  7359 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-30 11:37:02.237  7359  7359 V [BNRBootReceiver]: Boot Receiver Return
08-30 11:37:02.238  7359  7359 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-30 11:37:02.244  6767  6767 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,08-30 11:37:02.251  6767  6767 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-30 11:37:02.260  6373  6373 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 11:37:02.270  6767  6767 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 11:37:02.278  6767  6767 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 11:37:02.289  6836  6836 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 11:37:02.289  6836  6836 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-30 11:37:02.291  6836  6836 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-30 11:37:02.299  6373  6373 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 11:37:02.310  6767  6767 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 11:37:02.317  6767  6767 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 11:37:02.323  6836  6836 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-30 11:37:02.324  6836  6836 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 11:37:02.324  6836  6836 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-30 11:37:02.330  6373  6373 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 11:37:02.340  6767  6767 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 11:37:02.348  6767  6767 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 11:37:02.359  6836  6836 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-30 11:37:02.359  6836  6836 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-30 11:37:02.359  6836  6836 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-30 11:37:02.363  6373  6373 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 11:37:02.374  6767  6767 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 11:37:02.383  6767  6767 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-30 11:37:02.395  6836  6836 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 11:37:02.395  6836  6836 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 11:37:02.396  6836  6836 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-30 11:37:02.405  6373  6373 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 11:37:02.415  6767  6767 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 11:37:02.421  6767  6767 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 11:37:02.430  6836  6836 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 11:37:02.430  6836  6836 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 11:37:02.431  6836  6836 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-30 11:37:02.437  6373  6373 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 11:37:02.450  6767  6767 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 11:37:02.457  6767  6767 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 11:37:02.465  6836  6836 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 11:37:02.465  6836  6836 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 11:37:02.466  6836  6836 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-30 11:37:02.477  6373  6373 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 11:37:02.493  6767  6767 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 11:37:02.501  6767  6767 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 11:37:02.511  6836  6836 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-30 11:37:02.511  6836  6836 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 11:37:02.517  6836  6836 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-30 11:37:02.522  6373  6373 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 11:37:02.532  6767  6767 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 11:37:02.540  6767  6767 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 11:37:02.550  6687  6966 D UEI.SmartControl: Internal timer expired: 4
08-30 11:37:02.550  6687  6966 D UEI.SmartControl: unbind internal service
,08-30 11:37:02.555  6836  6836 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 11:37:02.555  6836  6836 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 11:37:02.557  6836  6836 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-30 11:37:02.565  6373  6373 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 11:37:02.573  6788  6788 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-30 11:37:02.586  1028  1433 D WifiService: New client listening to asynchronous messages
,08-30 11:37:02.589  6788  6788 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-30 11:37:02.597  6767  6767 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 11:37:02.608  6767  6767 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 11:37:02.620  6836  6836 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 11:37:02.621  6836  6836 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 11:37:02.623  6836  6836 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,08-30 11:37:02.626  6836  6836 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-30 11:37:02.627  6836  6836 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-30 11:37:02.640  6373  6373 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 11:37:02.651  6788  6788 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-30 11:37:02.654  6788  6788 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-30 11:37:02.666  6767  6767 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 11:37:02.678  6767  6767 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-30 11:37:02.695  6836  6836 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 11:37:02.695  6836  6836 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 11:37:02.696  6836  6836 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-30 11:37:02.697  6836  6836 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-30 11:37:02.697  6836  6836 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,08-30 11:37:02.698  6687  6960 D serial_port: close(fd = 24)
08-30 11:37:02.706  1028  2005 I ActivityManager: Killing 6853:com.lge.settings.easy/1000 (adj 15): empty #17
08-30 11:37:02.709  6687  6960 I UEI.SmartControl: Serial port is closed.
,08-30 11:37:02.738  1028  1878 W libprocessgroup: failed to open /acct/uid_1000/pid_6853/cgroup.procs: No such file or directory
,08-30 11:37:02.741  2195  2195 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
08-30 11:37:02.751  2195  2195 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
08-30 11:37:02.752  2195  2195 D c       : Getting all permits...
08-30 11:37:02.752  2195  2195 D a       : Opening database...
,08-30 11:37:02.757  2195  2195 D a       : Opening database auth.proximity.permit_store...
08-30 11:37:02.760  2195  2195 D a       : Closing database...
08-30 11:37:02.772  1028  1028 D PowerManagerServiceEx: releaseWakeLockInternal: lock=774595123 [*alarm*], flags=0x0
,08-30 11:37:02.775  6373  6373 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 11:37:02.780  6788  6788 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-30 11:37:02.780  6788  6788 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-30 11:37:02.780  6788  6788 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-30 11:37:02.784  6767  6767 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 11:37:02.793  6767  6767 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 11:37:02.802  6836  6836 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 11:37:02.802  6836  6836 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 11:37:02.806  4506  7387 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
08-30 11:37:02.808  6836  6836 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-30 11:37:02.813  6373  6373 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 11:37:02.821  6788  6788 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-30 11:37:02.821  6788  6788 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-30 11:37:02.821  6788  6788 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-30 11:37:02.824  6767  6767 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-30 11:37:02.832  6767  6767 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 11:37:02.837  6836  6836 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 11:37:02.838  6836  6836 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-30 11:37:02.839  6836  6836 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-30 11:37:02.845  6373  6373 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 11:37:02.849  6788  6788 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-30 11:37:02.849  6788  6788 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-30 11:37:02.849  6788  6788 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-30 11:37:02.853  6767  6767 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-30 11:37:02.861  6767  6767 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 11:37:02.869  6836  6836 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 11:37:02.869  6836  6836 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-30 11:37:02.871  6836  6836 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-30 11:37:02.883  6788  6788 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-30 11:37:02.886  6767  6767 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-30 11:37:02.892  6767  6767 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 11:37:02.908  6876  7404 W FormManager: Network not available. Please check & try again.
,08-30 11:37:02.918  6876  7405 V FormManager: Network unavailable.
08-30 11:37:02.918  4330  4330 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-30 11:37:02.919  4330  4330 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-30 11:37:02.920  6876  7405 V FormManager: Network unavailable.
08-30 11:37:02.920  4330  4330 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 11:37:02.925  4330  4330 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-30 11:37:02.930  4330  7407 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-30 11:37:02.933  6788  6788 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-30 11:37:02.933  6788  6788 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-30 11:37:02.933  6788  6788 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-30 11:37:02.936  6767  6767 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-30 11:37:02.939  4330  7408 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-30 11:37:02.940  4330  7408 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-30 11:37:02.943  6767  6767 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 11:37:02.944  6876  7410 W FormManager: Network not available. Please check & try again.
08-30 11:37:02.951  6876  7411 V FormManager: Network unavailable.
,08-30 11:37:02.956  6876  7411 V FormManager: Network unavailable.
,08-30 11:37:02.957  2195  2195 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,08-30 11:37:03.499  1028  1383 E WifiStateMachine:  InitialState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-623959029] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-30 11:37:03.501  1028  1383 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-623959027] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-30 11:37:03.576  1028  1437 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-30 11:37:03.590  1028  1110 D Tethering: MasterInitialState.processMessage what=3
08-30 11:37:03.602  6540  6540 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 11:37:03.606  6540  6540 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 11:37:03.609  1028  1105 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-30 11:37:03.612  6373  6373 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-30 11:37:03.613  6373  6401 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-30 11:37:03.623  5783  5783 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-30 11:37:03.645  2195  2195 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-30 11:37:03.662  6972  6972 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-30 11:37:03.662  6972  6972 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-30 11:37:03.662  6972  6972 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-30 11:37:03.662  6972  6972 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-30 11:37:03.669  6972  6972 I AppUp4:CustModeStarterReceiver: onReceive
08-30 11:37:03.673  6972  6972 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@23ac54df
08-30 11:37:03.673  6972  6972 D AppUp4:CustFacade: isCustomizationCompleted : false
08-30 11:37:03.673  6972  6972 D AppUp4:CustFacade: isPhone : true
08-30 11:37:03.674  6972  6972 D AppUp4:CustModeStarterReceiver: begin check event
08-30 11:37:03.674  6972  6972 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
,08-30 11:37:03.680  4330  4330 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-30 11:37:03.681  4330  4330 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-30 11:37:03.682  4330  4330 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 11:37:03.687  4330  4330 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-30 11:37:03.696  7023  7023 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-30 11:37:03.732  3470  3470 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-30 11:37:03.732  3470  3470 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-30 11:37:03.733  3470  3470 I LgeMiscReceiver: networkInfo.isConnected() = true
08-30 11:37:03.733  3470  3470 D PhoneState: setPdpRejectCasuse : false
,08-30 11:37:03.745  1028  1105 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 11:37:03.750  7065  7065 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-30 11:37:03.751  7065  7065 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-30 11:37:03.752  7023  7423 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 11:37:03.754  4330  7424 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-30 11:37:03.766  4330  7438 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-30 11:37:03.767  4330  7438 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-30 11:37:03.775  7130  7130 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:37:3
,08-30 11:37:03.776  7130  7130 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-30 11:37:03.776  7130  7130 D Weather.Utils: 2 : All the weather widget is gone.
08-30 11:37:03.776  7130  7130 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-30 11:37:03.776  7130  7130 D WeatherAncestor: connectivity changed - connection : true
08-30 11:37:03.777  7130  7130 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@13b70bf5
08-30 11:37:03.777  6876  7442 W FormManager: Network not available. Please check & try again.
08-30 11:37:03.777  7130  7130 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-30 11:37:03.778  7130  7130 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-30 11:37:03.778  7130  7130 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-30 11:37:03.778  7130  7130 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-30 11:37:03.778  7130  7130 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:37:3
08-30 11:37:03.786  6876  7443 V FormManager: Network unavailable.
,08-30 11:37:03.789  6876  7443 V FormManager: Network unavailable.
,08-30 11:37:04.426  1028  1877 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-30 11:37:04.427  1028  1877 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-30 11:37:04.459  1028  1028 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-30 11:37:04.459  1028  1028 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-30 11:37:04.459  1028  1028 D Ulp_jni : JNI:system_update. Event-4
,08-30 11:37:04.462  1028  1110 D BluetoothManagerService: Message: 1
08-30 11:37:04.462  1028  1110 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
,08-30 11:37:04.493  1028  1110 D BluetoothManagerService: Message: 20
08-30 11:37:04.493  1028  1110 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@28122181:true
,08-30 11:37:04.497  6913  6913 D BluetoothAdapterState: make
08-30 11:37:04.501  1028  1437 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-30 11:37:04.506  1028  1110 D Tethering: MasterInitialState.processMessage what=3
,08-30 11:37:04.509  1028  1437 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-30 11:37:04.513  6913  6913 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-30 11:37:04.513  6913  6913 I bluedroid-qcom: init
08-30 11:37:04.514  6913  7455 I BluetoothAdapterState: Entering OffState
08-30 11:37:04.515  6913  6913 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-30 11:37:04.516  6913  6913 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-30 11:37:04.516  6913  6913 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-30 11:37:04.516  6913  6913 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-30 11:37:04.516  6913  6913 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-30 11:37:04.518  6913  6913 I bluedroid-qcom: get_profile_interface socket
08-30 11:37:04.518  6913  6913 I bluedroid-qcom: get_profile_interface map_client
08-30 11:37:04.519  6913  7459 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-30 11:37:04.521  6913  7459 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-30 11:37:04.517  7458  7458 W bdaddr_loader: type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6837 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 11:37:04.517  7458  7458 W bdaddr_loader: type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6837 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 11:37:04.533  7458  7458 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-30 11:37:04.533  7458  7458 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-30 11:37:04.533  7458  7458 I LGFTMITEM: [GET_FTM][id=8], offset=16384
,08-30 11:37:04.542  1028  1110 D Tethering: MasterInitialState.processMessage what=3
08-30 11:37:04.544  7458  7458 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-30 11:37:04.552  6540  6540 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 11:37:04.555  7458  7458 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-30 11:37:04.555  7458  7458 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-30 11:37:04.558  6540  6540 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 11:37:04.558  6540  6540 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 11:37:04.559  6540  6540 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 11:37:04.566  6913  7459 D BluetoothAdapterProperties: Name is: G3
,08-30 11:37:04.568  1028  1028 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-30 11:37:04.569  1028  1110 D BluetoothManagerService: Message: 40
08-30 11:37:04.569  1028  1110 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-30 11:37:04.570  6913  6929 I bluedroid-qcom: config_hci_snoop_log
08-30 11:37:04.571  1028  1110 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-30 11:37:04.571  1028  1110 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-30 11:37:04.576  1028  1028 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-30 11:37:04.576  1028  1028 D BluetoothManagerService: Stored Bluetooth name: G3
08-30 11:37:04.578  6913  7455 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-30 11:37:04.578  6913  7455 D BluetoothAdapterProperties: Setting state to 11
08-30 11:37:04.578  6913  7455 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
,08-30 11:37:04.582  6913  7455 I LGBluetoothServiceJni: classInitNative: succeeds
08-30 11:37:04.586  1028  1110 D BluetoothManagerService: Message: 60
08-30 11:37:04.586  1028  1110 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-30 11:37:04.586  1028  1110 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-30 11:37:04.591  6913  7455 D BluetoothBondStateMachine: make
,08-30 11:37:04.597  6913  7455 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13b70bf5
08-30 11:37:04.597  6913  7455 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-30 11:37:04.597  6913  7455 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13b70bf5
08-30 11:37:04.597  6913  7455 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-30 11:37:04.597  6913  7455 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-30 11:37:04.599  6913  7460 I BluetoothBondStateMachine: StableState(): Entering Off State
08-30 11:37:04.599  6373  6373 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-30 11:37:04.601  6373  6401 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-30 11:37:04.603  1933  1933 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-30 11:37:04.606  6767  6767 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-30 11:37:04.608  1595  1595 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-30 11:37:04.610  6540  6540 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 11:37:04.612  6540  6540 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 11:37:04.622  5783  5783 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-30 11:37:04.624  6913  6913 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-30 11:37:04.626  1028  1105 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-30 11:37:04.626  6913  6913 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 11:37:04.627  6913  6913 V BluetoothPbapReceiver: ***********state = 11
,08-30 11:37:04.630  6913  7455 E BluetoothAdapterService: File transfer profiles supported!!
,08-30 11:37:04.643  2195  2195 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 11:37:04.649  5783  5783 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-30 11:37:04.649  6913  7455 E BluetoothAdapterService: File transfer profiles supported!!
,08-30 11:37:04.650  6913  6913 D HeadsetService: Received start request. Starting profile...
08-30 11:37:04.651  6913  6913 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-30 11:37:04.652  6913  6913 D LGBluetoothHfpAdapter: Version 1.6
08-30 11:37:04.654  6913  6913 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-30 11:37:04.655  6913  6913 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-30 11:37:04.655  6913  6913 D HeadsetStateMachine: make
08-30 11:37:04.686  1028  1932 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7479 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-30 11:37:04.693  1028  1105 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-30 11:37:04.694  1028  1105 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 11:37:04.694  1028  1105 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 11:37:04.694  6913  7455 E BluetoothAdapterService: File transfer profiles supported!!
08-30 11:37:04.698  6913  6913 D LgDataFeature: LgDataFeature() Constructor: none
08-30 11:37:04.698  6913  6913 D LgDataFeature: LgDataFeature() Constructor Done, null
08-30 11:37:04.698  6913  7455 E BluetoothAdapterService: File transfer profiles supported!!
,08-30 11:37:04.702  6913  6913 D HeadsetStateMachine: max_hf_connections = 1
08-30 11:37:04.702  6913  6913 I bluedroid-qcom: get_profile_interface handsfree
08-30 11:37:04.703  6913  6913 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-30 11:37:04.704   320  1390 V AudioPolicyService: registerClient() client 0xb558a220, uid 1002
08-30 11:37:04.704   320  1390 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-30 11:37:04.704   320  1390 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-30 11:37:04.704   320  1390 V AudioPolicyManagerEx: getOutput() returns output 2
08-30 11:37:04.704  6913  6913 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-30 11:37:04.705   320   320 V AudioFlinger: registerClient() client 0xb1433850, pid 6913
08-30 11:37:04.705   320  1384 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
,08-30 11:37:04.705   320  1384 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 11:37:04.705  1595  1612 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 11:37:04.705  1595  1612 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 11:37:04.705  1843  4011 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 11:37:04.705  1843  4011 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 11:37:04.705   320  1385 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 11:37:04.705   320  1385 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 11:37:04.706  1595  2083 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 11:37:04.706  1595  2083 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 11:37:04.706  1843  3563 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 11:37:04.706  1843  3563 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 11:37:04.706  1028  1877 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 11:37:04.706  1028  1877 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 11:37:04.706  1028  1877 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 11:37:04.706  1028  1877 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 11:37:04.706  6913  6929 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 11:37:04.706  6913  6929 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-30 11:37:04.706  6913  6929 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 11:37:04.706  6913  6929 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-30 11:37:04.708  6913  6913 V ToneGenerator: Create Track: 0xb4928080
08-30 11:37:04.708  6913  6913 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-30 11:37:04.708  6913  6913 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-30 11:37:04.710   320  1389 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-30 11:37:04.710   320  1389 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-30 11:37:04.710   320  1389 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-30 11:37:04.710   320  1389 V AudioPolicyManagerEx: getOutput() returns output 2
08-30 11:37:04.711   320  2150 I AudioFlinger: isAudioPlaybackHookOn() false
08-30 11:37:04.711  6913  7455 E BluetoothAdapterService: File transfer profiles supported!!
08-30 11:37:04.712  2195  2195 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
08-30 11:37:04.712   320  1390 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-30 11:37:04.712   320  1390 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
,08-30 11:37:04.712   320  1390 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-30 11:37:04.712   320  1390 V AudioPolicyManagerEx: getOutput() returns output 2
08-30 11:37:04.712  6913  6913 V AudioSystem: getLatency() output 2, latency 50
08-30 11:37:04.712  6913  6913 V AudioSystem: getFrameCount() output 2, frameCount 960
08-30 11:37:04.712  6913  6913 V AudioTrack: createTrack_l() output 2 afLatency 50
08-30 11:37:04.712  3470  3485 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 11:37:04.712  3470  3485 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 11:37:04.712  3470  3485 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 11:37:04.712  3470  3485 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 11:37:04.712   320   320 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-30 11:37:04.712   320   320 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-30 11:37:04.712   320   320 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-30 11:37:04.712   320   320 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-30 11:37:04.712   320   320 V AudioFlinger: createTrack() lSessionId: 20
08-30 11:37:04.713  6913  6913 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-30 11:37:04.714   320   320 V AudioFlinger: acquiring 20 from 6913, for 6913
08-30 11:37:04.714   320   320 V AudioFlinger:  added new entry for 20
08-30 11:37:04.714  6913  6913 V ToneGenerator: ToneGenerator INIT OK, time: 125759
08-30 11:37:04.714  6913  6913 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13b70bf5
08-30 11:37:04.715  6913  7478 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-30 11:37:04.715  6913  7478 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-30 11:37:04.715  6913  7478 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-30 11:37:04.715  6913  7478 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-30 11:37:04.715   320  2151 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 6913
08-30 11:37:04.716   320  2151 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-30 11:37:04.716   320  2151 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-30 11:37:04.716   320  2151 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-30 11:37:04.716   320  2151 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-30 11:37:04.716   320  2151 V voice   : voice_set_parameters: exit with code(0)
08-30 11:37:04.716   320  2151 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-30 11:37:04.716   320  2151 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-30 11:37:04.716   320  2151 V msm8974_platform: platform_set_parameters: exit with code(0)
08-30 11:37:04.716   320  2151 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-30 11:37:04.716   320  2151 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-30 11:37:04.716   320  2151 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-30 11:37:04.716  6913  7478 V ToneGenerator: ToneGenerator destructor
08-30 11:37:04.716  6913  7478 V ToneGenerator: stopTone
08-30 11:37:04.716  6913  7478 V ToneGenerator: Delete Track: 0xb4928080
08-30 11:37:04.718  6913  6913 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13b70bf5
08-30 11:37:04.719  6913  7478 V AudioTrack: ~AudioTrack, releasing session id from 6913 on behalf of 6913
08-30 11:37:04.719   320  2150 V AudioFlinger: releasing 20 from 6913 for 6913
08-30 11:37:04.719   320  2150 V AudioFlinger:  decremented refcount to 0
08-30 11:37:04.719   320 , 2150 V AudioFlinger: purging stale effects
08-30 11:37:04.719  6913  6913 D A2dpService: Received start request. Starting profile...
08-30 11:37:04.719   320  2150 V AudioPolicyService: AudioCommandThread() adding release output 2
08-30 11:37:04.719   320  2150 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-30 11:37:04.719   320  2150 V AudioFlinger: PlaybackThread::Track destructor
08-30 11:37:04.719   320  1265 V AudioPolicyService: AudioCommandThread() waking up
08-30 11:37:04.719   320  2150 V AudioFlinger: removeClient_l() pid 6913, calling pid 320
08-30 11:37:04.719   320  1265 V AudioPolicyService: AudioCommandThread() processing release output 2
08-30 11:37:04.719   320  1265 V AudioPolicyManager: releaseOutput() 2
08-30 11:37:04.719   320  1265 V AudioPolicyService: AudioCommandThread() going to sleep
08-30 11:37:04.720  6913  6913 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-30 11:37:04.720  6913  7455 E BluetoothAdapterService: File transfer profiles supported!!
08-30 11:37:04.720  6913  6913 V Avrcp   : make
08-30 11:37:04.721  6913  6913 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-30 11:37:04.721  6913  6913 I bluedroid-qcom: get_profile_interface avrcp
08-30 11:37:04.725  6972  6972 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-30 11:37:04.725  6972  6972 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-30 11:37:04.725  6972  6972 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
,08-30 11:37:04.725  6972  6972 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-30 11:37:04.727  6913  7455 E BluetoothAdapterService: File transfer profiles supported!!
,08-30 11:37:04.730  6972  6972 I AppUp4:CustModeStarterReceiver: onReceive
08-30 11:37:04.730  6913  6913 V AudioManager: registerRemoteController: size of Media player list: 0
08-30 11:37:04.732  6913  6913 E AudioManager: No RCC entry present to update
08-30 11:37:04.732  6913  6913 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-30 11:37:04.735  6913  6913 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-30 11:37:04.735  6972  6972 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@23ac54df
08-30 11:37:04.735  6972  6972 D AppUp4:CustFacade: isCustomizationCompleted : false
08-30 11:37:04.735  6972  6972 D AppUp4:CustFacade: isPhone : true
08-30 11:37:04.736  6913  6913 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-30 11:37:04.736  6913  6913 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-30 11:37:04.737  6972  6972 D AppUp4:CustModeStarterReceiver: begin check event
08-30 11:37:04.737  6972  6972 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-30 11:37:04.737  6913  7455 V LGMDMManager: Create singleton instance
08-30 11:37:04.739  6913  7455 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-30 11:37:04.740  4330  4330 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-30 11:37:04.740  4330  4330 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-30 11:37:04.741  6913  6913 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-30 11:37:04.741  4330  4330 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-30 11:37:04.743  4330  4330 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 11:37:04.789  4330  7500 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-30 11:37:04.790  4330  7501 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-30 11:37:04.791  4330  7501 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-30 11:37:04.791  7023  7023 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-30 11:37:04.815  7023  7502 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 11:37:04.817  3470  3470 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,08-30 11:37:04.817  3470  3470 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-30 11:37:04.817  3470  3470 I LgeMiscReceiver: networkInfo.isConnected() = false
08-30 11:37:04.823  7065  7065 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-30 11:37:04.824  7065  7065 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-30 11:37:04.826  1028  2024 V SIM_STK : Menu title from STK is T-Mobile
08-30 11:37:04.826  1028  2024 V SIM_STK : Menu title from STK is T-Mobile
08-30 11:37:04.833  7479  7479 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-30 11:37:04.833  7479  7479 W LG Account v2.2: No ProfileInfo entries
08-30 11:37:04.833  7479  7479 I LG Account v2.2: isEnabled: false
08-30 11:37:04.833  7479  7479 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-30 11:37:04.834  7479  7479 I Feature : [Lifetracker]Country: EU
08-30 11:37:04.834  7479  7479 I Feature : [Lifetracker]Operator: OPEN
08-30 11:37:04.834  7479  7479 I Feature : [Lifetracker]Ranking support: false
08-30 11:37:04.834  7479  7479 I Feature : [Lifetracker]Comfort support: false
08-30 11:37:04.834  7479  7479 I Feature : [Lifetracker]Accessory: true
08-30 11:37:04.834  7479  7479 I Feature : [Lifetracker]Health device: true
08-30 11:37:04.834  7479  7479 I Feature : [Lifetracker]Extra Pedometer: false
08-30 11:37:04.834  7479  7479 I Feature : [Lifetracker]Blood glucose device: false
08-30 11:37:04.834  7479  7479 I Feature : [Lifetracker]Device Number: 3
,08-30 11:37:04.836  7130  7130 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:37:4
08-30 11:37:04.842  7130  7130 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-30 11:37:04.842  7130  7130 D Weather.Utils: 2 : All the weather widget is gone.
08-30 11:37:04.842  7130  7130 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-30 11:37:04.843  7130  7130 D WeatherAncestor: connectivity changed - connection : true
08-30 11:37:04.843  7130  7130 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@13b70bf5
08-30 11:37:04.844  7130  7130 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-30 11:37:04.844  7130  7130 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-30 11:37:04.844  7130  7130 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-30 11:37:04.844  7130  7130 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-30 11:37:04.844  7130  7130 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:37:4
08-30 11:37:04.847  6876  7506 W FormManager: Network not available. Please check & try again.
,08-30 11:37:04.854  6767  6767 D BluetoothPermissionRequest: onReceive
08-30 11:37:04.854  6876  7507 V FormManager: Network unavailable.
08-30 11:37:04.859  6876  7507 V FormManager: Network unavailable.
,08-30 11:37:04.861  6767  6767 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-30 11:37:04.876  6373  6373 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-30 11:37:04.878  6373  6401 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-30 11:37:04.882  1028  1044 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-30 11:37:04.886  6913  6913 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-30 11:37:04.889  6913  6913 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
,08-30 11:37:04.890  6913  6913 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-30 11:37:04.890  6913  6913 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-30 11:37:04.890  6913  6913 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-30 11:37:04.890  6913  6913 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-30 11:37:04.890  6913  6913 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-30 11:37:04.890  6913  6913 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-30 11:37:04.890  6913  6913 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-30 11:37:04.890  6913  6913 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-30 11:37:04.890  6913  6913 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-30 11:37:04.890  6913  6913 I BluetoothA2dpServiceJni: classInitNative
08-30 11:37:04.890  6913  6913 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-30 11:37:04.890  6913  6913 D A2dpStateMachine: make
08-30 11:37:04.891  2195  2195 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
08-30 11:37:04.892  6913  6913 I bluedroid-qcom: get_profile_interface a2dp
08-30 11:37:04.893  6913  7510 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-30 11:37:04.895  6913  6913 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-30 11:37:04.895  6913  6913 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-30 11:37:04.896  6913  6913 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13b70bf5
08-30 11:37:04.896  6913  6913 I BluetoothHidServiceJni: classInitNative: succeeds
08-30 11:37:04.897  6913  7509 D A2dpStateMachine: Enter Disconnected: -2
08-30 11:37:04.898  6913  6913 D HidService: Received start request. Starting profile...
08-30 11:37:04.898  6913  6913 I bluedroid-qcom: get_profile_interface hidhost
08-30 11:37:04.898  6913  6913 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13b70bf5
08-30 11:37:04.898  6913  6913 I BluetoothHealthServiceJni: classInitNative: succeeds
08-30 11:37:04.899  6972  6972 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-30 11:37:04.899  6972  6972 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-30 11:37:04.899  6913  6913 D HealthService: Received start request. Starting profile...
08-30 11:37:04.899  6972  6972 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-30 11:37:04.899  6972  6972 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-30 11:37:04.901  6972  6972 I AppUp4:CustModeStarterReceiver: onReceive
,08-30 11:37:04.902  6913  6913 I bluedroid-qcom: get_profile_interface health
08-30 11:37:04.902  6913  6913 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-30 11:37:04.902  6913  6913 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13b70bf5
08-30 11:37:04.903  6913  6913 D HeadsetStateMachine: Proxy object connected
08-30 11:37:04.903  6913  6913 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-30 11:37:04.903  6913  6913 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-30 11:37:04.905  6913  6913 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-30 11:37:04.906  6913  6913 D PanService: Received start request. Starting profile...
08-30 11:37:04.906  6913  6913 D BluetoothPanServiceJni: initializeNative(L110): pan
08-30 11:37:04.906  6913  6913 I bluedroid-qcom: get_profile_interface pan
08-30 11:37:04.910  6972  6972 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@23ac54df
08-30 11:37:04.910  6972  6972 D AppUp4:CustFacade: isCustomizationCompleted : false
08-30 11:37:04.910  6972  6972 D AppUp4:CustFacade: isPhone : true
08-30 11:37:04.911  6972  6972 D AppUp4:CustModeStarterReceiver: begin check event
08-30 11:37:04.911  6972  6972 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-30 11:37:04.914  4330  4330 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-30 11:37:04.914  4330  4330 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-30 11:37:04.914  6913  6913 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-30 11:37:04.914  6913  6913 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13b70bf5
,08-30 11:37:04.915  6913  7478 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-30 11:37:04.916  6913  7478 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-30 11:37:04.916  6913  7478 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-30 11:37:04.917  4330  4330 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 11:37:04.918  6913  6913 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-30 11:37:04.918  4330  4330 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 11:37:04.918  6913  6913 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-30 11:37:04.922  6913  6913 D BtGatt.DebugUtils: handleDebugAction() action=null
08-30 11:37:04.922  6913  6913 D BtGatt.GattService: Received start request. Starting profile...
08-30 11:37:04.922  6913  6913 D BtGatt.GattService: start()
08-30 11:37:04.922  6913  6913 I bluedroid-qcom: get_profile_interface gatt
08-30 11:37:04.923  6913  6913 D BtGatt.AdvertiseManager: advertise manager created
08-30 11:37:04.924  4330  7515 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-30 11:37:04.925  7023  7023 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-30 11:37:04.925  4330  7517 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-30 11:37:04.926  4330  7517 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-30 11:37:04.928  6913  6913 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13b70bf5
08-30 11:37:04.929  6913  6913 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13b70bf5
08-30 11:37:04.930  6913  6913 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-30 11:37:04.930  6913  6913 V BluetoothMapService: BluetoothMapBinder()
08-30 11:37:04.931  6913  6913 D BluetoothMapService: Received start request. Starting profile...
08-30 11:37:04.931  6913  6913 D BluetoothMapService: start()
08-30 11:37:04.938  6913  6913 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-30 11:37:04.938  6913  6913 D BluetoothMapEmailAppObserver: createReceiver()
,08-30 11:37:04.940  6913  6913 D BluetoothMapEmailAppObserver: initObservers()
08-30 11:37:04.940  6913  6913 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-30 11:37:04.946  3470  3470 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-30 11:37:04.946  3470  3470 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-30 11:37:04.946  3470  3470 I LgeMiscReceiver: networkInfo.isConnected() = false
08-30 11:37:04.949  7065  7065 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-30 11:37:04.949  7065  7065 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-30 11:37:04.950  6913  6913 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13b70bf5
08-30 11:37:04.952  6876  7520 W FormManager: Network not available. Please check & try again.
,08-30 11:37:04.954  6913  6913 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-30 11:37:04.958  6913  6913 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-30 11:37:04.961  7023  7523 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 11:37:04.962  6913  6913 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-30 11:37:04.964  6876  7521 V FormManager: Network unavailable.
,08-30 11:37:04.966  6913  6913 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-30 11:37:04.966  6913  6913 V PanService: [BTUI] SIM Extra State :ABSENT
08-30 11:37:04.969  6913  6913 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-30 11:37:04.969  6913  6913 V BluetoothMapService: Handler(): got msg=1
08-30 11:37:04.970  6913  7455 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-30 11:37:04.970  6913  7455 I bluedroid-qcom: enable
08-30 11:37:04.970  6913  7525 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-30 11:37:04.970  6913  7525 I bt-btu  : btu_task pending for preload complete event
08-30 11:37:04.971  6913  7455 I bt_hci_bdroid: init
08-30 11:37:04.972  6913  7455 I bt_vendor: bt-vendor : init
08-30 11:37:04.972  6913  7455 I bt_vendor: bt-vendor : get_bt_soc_type
08-30 11:37:04.972  6913  7455 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-30 11:37:04.972  6913  7455 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-30 11:37:04.972  6913  7455 D bt_userial_mct: userial_init
08-30 11:37:04.972  6913  6913 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-30 11:37:04.973  6913  7455 D bt_hci_bdroid: set_power 1
08-30 11:37:04.973  6913  7455 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-30 11:37:04.973  6913  7455 I bt_vendor: Starting hciattach daemon
08-30 11:37:04.973  6913  7455 I bt_vendor: try to set true
08-30 11:37:04.967  7528  7528 W sh      : type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6837 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 11:37:04.967  7528  7528 W sh      : type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6837 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 11:37:04.977  7130  7130 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:37:4
,08-30 11:37:04.979  7130  7130 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-30 11:37:04.979  7130  7130 D Weather.Utils: 2 : All the weather widget is gone.
08-30 11:37:04.980  6913  6913 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-30 11:37:04.980  6876  7521 V FormManager: Network unavailable.
08-30 11:37:04.980  6913  6913 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-30 11:37:04.980  6913  6913 V BluetoothSapReceiver: SapReceiver onReceive 
08-30 11:37:04.980  6913  6913 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 11:37:04.980  6913  6913 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-30 11:37:04.981  7130  7130 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-30 11:37:04.982  7130  7130 D WeatherAncestor: connectivity changed - connection : true
08-30 11:37:04.982  7130  7130 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@13b70bf5
08-30 11:37:04.984  7130  7130 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-30 11:37:04.984  7130  7130 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-30 11:37:04.984  7130  7130 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-30 11:37:04.984  7130  7130 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-30 11:37:04.984  7130  7130 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:37:4
08-30 11:37:04.998  7529  7529 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-30 11:37:05.019  1028  1567 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=7532 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-30 11:37:05.071  7552  7552 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
08-30 11:37:05.074  7532  7532 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-30 11:37:05.082  7553  7553 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
08-30 11:37:05.086  1028  1967 I ActivityManager: Killing 7286:com.android.vending/u0a44 (adj 15): empty #17
,08-30 11:37:05.101  7555  7555 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-30 11:37:05.111  7556  7556 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
08-30 11:37:05.120  7557  7557 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-30 11:37:05.130  7558  7558 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
08-30 11:37:05.137  1028  2040 W libprocessgroup: failed to open /acct/uid_10044/pid_7286/cgroup.procs: No such file or directory
,08-30 11:37:05.164  7560  7560 I libmdmdetect: ESOC framework not supported
08-30 11:37:05.165  7560  7560 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-30 11:37:05.172  7560  7560 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
,08-30 11:37:05.172  7560  7560 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-30 11:37:05.172  7560  7560 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-30 11:37:05.172  7560  7560 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-30 11:37:05.172  7560  7560 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-30 11:37:05.173  7560  7560 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-30 11:37:05.173  7560  7560 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-30 11:37:05.209  7560  7561 E QC-QMI  : qmi_client [7560] 14: failed to locate client data
,08-30 11:37:05.211   464   464 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
,08-30 11:37:05.211   464   464 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
08-30 11:37:05.259  7562  7562 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-30 11:37:05.290  7563  7563 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-30 11:37:05.325  6913  7455 I bt_vendor: bluetooth satus is on
08-30 11:37:05.325  6913  7455 D bt_hci_bdroid: preload
08-30 11:37:05.325  6913  7527 D bt_userial_mct: userial_open(port:0)
08-30 11:37:05.325  6913  7527 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-30 11:37:05.329  6913  7527 I bt_vendor: Done intiailizing UART
08-30 11:37:05.330  6913  7527 I bt_vendor: Done intiailizing UART
08-30 11:37:05.330  6913  7527 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-30 11:37:05.330  6913  7527 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-30 11:37:05.331  6913  7568 D bt_userial_mct: Entering userial_read_thread()
08-30 11:37:05.331  6913  7525 I bt-btu  : btu_task received preload complete event
08-30 11:37:05.331  6913  7525 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-30 11:37:05.332  6913  7525 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-30 11:37:05.334  6913  7525 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-30 11:37:05.338  6913  7525 I         : BTE_InitTraceLevels -- TRC_HCI
08-30 11:37:05.338  6913  7525 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-30 11:37:05.338  6913  7525 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-30 11:37:05.338  6913  7525 I         : BTE_InitTraceLevels -- TRC_AVDT
08-30 11:37:05.338  6913  7525 I         : BTE_InitTraceLevels -- TRC_AVRC
08-30 11:37:05.339  6913  7525 I         : BTE_InitTraceLevels -- TRC_A2D
08-30 11:37:05.339  6913  7525 I         : BTE_InitTraceLevels -- TRC_BNEP
08-30 11:37:05.339  6913  7525 I         : BTE_InitTraceLevels -- TRC_BTM
08-30 11:37:05.339  6913  7525 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-30 11:37:05.339  6913  7525 I         : BTE_InitTraceLevels -- TRC_GAP
08-30 11:37:05.339  6913  7525 I         : BTE_InitTraceLevels -- TRC_PAN
08-30 11:37:05.339  6913  7525 I         : BTE_InitTraceLevels -- TRC_SDP
08-30 11:37:05.339  6913  7525 I         : BTE_InitTraceLevels -- TRC_GATT
08-30 11:37:05.339  6913  7525 I         : BTE_InitTraceLevels -- TRC_SMP
08-30 11:37:05.339  6913  7525 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-30 11:37:05.339  6913  7525 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-30 11:37:05.460  6913  7525 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-30 11:37:05.461  6913  7525 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa014e061 
08-30 11:37:05.461  6913  7525 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa014e061 
,08-30 11:37:05.478  6913  7459 E bt-btif : Calling BTA_HhEnable
08-30 11:37:05.478  6913  7459 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-30 11:37:05.478  6913  7459 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-30 11:37:05.481  6913  7525 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-30 11:37:05.481  6913  7525 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-30 11:37:05.481  6913  7525 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-30 11:37:05.481  6913  7525 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-30 11:37:05.481  6913  7525 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-30 11:37:05.482  1028  1028 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-30 11:37:05.483  1028  1028 D BluetoothManagerService: Stored Bluetooth name: G3
08-30 11:37:05.483  6913  7459 D BluetoothAdapterProperties: Name is: G3
08-30 11:37:05.484  6913  7459 D BluetoothAdapterProperties: Scan Mode:20
08-30 11:37:05.484  6913  7459 D BluetoothAdapterProperties: Discoverable Timeout:120
08-30 11:37:05.484  6913  7459 D bt_hci_bdroid: postload
08-30 11:37:05.489  6913  7459 D bte_conf: Device ID record 1 : primary
08-30 11:37:05.489  6913  7459 D bte_conf:   vendorId            = 00c4
08-30 11:37:05.489  6913  7459 D bte_conf:   vendorIdSource      = 0001
08-30 11:37:05.489  6913  7459 D bte_conf:   product             = 13a1
08-30 11:37:05.489  6913  7459 D bte_conf:   version             = 1000
08-30 11:37:05.489  6913  7459 D bte_conf:   clientExecutableURL = 
08-30 11:37:05.489  6913  7459 D bte_conf:   serviceDescription  = 
08-30 11:37:05.489  6913  7459 D bte_conf:   documentationURL    = 
08-30 11:37:05.489  6913  7459 D bte_conf: bte_load_did_conf no section named DID2.
08-30 11:37:05.491  6913  7527 D bt_hci_bdroid: Used up Tx Cmd credits
,08-30 11:37:05.495  6913  7527 D bt_hci_bdroid: Used up Tx Cmd credits
08-30 11:37:05.495  6913  7527 D bt_hci_bdroid: Used up Tx Cmd credits
08-30 11:37:05.495  6913  7525 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-30 11:37:05.499  6913  7527 D bt_hci_bdroid: Used up Tx Cmd credits
08-30 11:37:05.501  6913  7455 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-30 11:37:05.502  6913  7455 D BluetoothAdapterProperties: ScanMode =  20
08-30 11:37:05.502  6913  7455 D BluetoothAdapterProperties: State =  11
08-30 11:37:05.502  6913  7455 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-30 11:37:05.502  6913  7455 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-30 11:37:05.502  6913  7455 D BluetoothAdapterProperties: Setting state to 12
08-30 11:37:05.503  6913  7455 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-30 11:37:05.503  6913  7459 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-30 11:37:05.507  1028  1110 D BluetoothManagerService: Message: 60
08-30 11:37:05.507  1028  1110 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-30 11:37:05.507  1028  1110 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
08-30 11:37:05.507  1028  1110 D BluetoothA2dp: onBluetoothStateChange: up=true
08-30 11:37:05.509  6913  7568 E bt_mct  : hci lib postload completed
08-30 11:37:05.497  7576  7576 W sh      : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6837 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 11:37:05.497  7576  7576 W sh      : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6837 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 11:37:05.515  6913  7459 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-30 11:37:05.518  6913  7525 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-30 11:37:05.518  6913  7525 W bt-smp  : Plain text(LSB ~ MSB) = 47 0f 5b 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-30 11:37:05.519  6913  7525 W bt-smp  : Encrypted text(LSB ~ MSB) = b4 2f 63 a3 23 83 e4 6d 2f c9 b8 24 e0 8a 43 23 
08-30 11:37:05.519  6913  7525 W bt-btm  : Stopping oneshot timer
08-30 11:37:05.533  1843  4011 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-30 11:37:05.539  6913  7455 I BluetoothAdapterState: Entering On State
08-30 11:37:05.550  6540  6540 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 11:37:05.550  6540  6540 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 11:37:05.550  6540  6540 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 11:37:05.550  6540  6540 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 11:37:05.550  6540  6540 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 11:37:05.550  6540  6540 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 11:37:05.550  6540  6540 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 11:37:05.550  6540  6540 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 11:37:05.553  6913  7459 D BluetoothAdapterProperties: Discoverable Timeout:120
08-30 11:37:05.553  6913  7459 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-30 11:37:05.554  6913  7525 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-30 11:37:05.554  6913  7525 W bt-smp  : Plain text(LSB ~ MSB) = 2d 71 48 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-30 11:37:05.554  6913  7525 W bt-smp  : Encrypted text(LSB ~ MSB) = 44 42 7d 88 10 0f 79 e2 97 c4 2d 20 40 4b 18 2a 
08-30 11:37:05.554  6913  7525 W bt-btm  : Stopping oneshot timer
08-30 11:37:05.564  6540  6540 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 11:37:05.569  6913  7525 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-30 11:37:05.569  6913  7525 W bt-smp  : Plain text(LSB ~ MSB) = ab 69 50 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-30 11:37:05.569  6913  7525 W bt-smp  : Encrypted text(LSB ~ MSB) = 41 10 79 66 6f d2 16 cc 5e d1 8c b1 9a 57 6b aa 
08-30 11:37:05.570  6913  7525 W bt-btm  : Stopping oneshot timer
08-30 11:37:05.582  6540  6540 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 11:37:05.582  6540  6540 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 11:37:05.582  6540  6540 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 11:37:05.582  6540  6540 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 11:37:05.582  6540  6540 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 11:37:05.582  6540  6540 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 11:37:05.582  6540  6540 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 11:37:05.582  6540  6540 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 11:37:05.586  6913  7525 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-30 11:37:05.586  6913  7525 W bt-smp  : Plain text(LSB ~ MSB) = 8f 61 6a 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-30 11:37:05.586  6913  7525 W bt-smp  : Encrypted text(LSB ~ MSB) = b8 7d 18 fa 07 ba a2 cd f1 40 84 35 b8 77 f8 bf 
08-30 11:37:05.586  6913  7525 W bt-btm  : Stopping oneshot timer
08-30 11:37:05.593  6540  6540 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 11:37:05.597  6913  7525 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-30 11:37:05.597  6913  7525 W bt-smp  : Plain text(LSB ~ MSB) = 84 af 59 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-30 11:37:05.597  6913  7525 W bt-smp  : Encrypted text(LSB ~ MSB) = 34 a3 dc 26 cc a2 14 96 cd 05 e0 d3 e3 f4 86 85 
,08-30 11:37:05.600  6913  7525 W bt-btm  : Stopping oneshot timer
,08-30 11:37:05.605  6913  7455 D LGBluetoothServiceAdapter: [BTUI] OnState
08-30 11:37:05.605  6913  7455 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-30 11:37:05.605  6913  7455 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-30 11:37:05.607  6913  7455 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-30 11:37:05.608  6913  7455 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-30 11:37:05.608  1028  1028 D BluetoothA2dp: Proxy object connected
08-30 11:37:05.640  1843  1843 D BluetoothHeadset: Proxy object connected
,08-30 11:37:05.646  7581  7581 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
,08-30 11:37:05.655  6767  6787 D BluetoothMap: onBluetoothStateChange: up=true
,08-30 11:37:05.679  6767  6786 D BluetoothPan: onBluetoothStateChange on: true
,08-30 11:37:05.679  6767  6786 D BluetoothPan: onBluetoothStateChange call bindService
08-30 11:37:05.680  6767  6767 D BluetoothMap: Proxy object connected
08-30 11:37:05.680  6767  6767 D MapProfile: Bluetooth service connected
08-30 11:37:05.680  6767  6767 D BluetoothMap: getConnectedDevices()
08-30 11:37:05.684  1843  2414 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 11:37:05.689  1843  1843 D BluetoothHeadset: Proxy object connected
08-30 11:37:05.690  6767  7593 D BluetoothPbap: onBluetoothStateChange: up=true
08-30 11:37:05.692  1028  1110 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 11:37:05.695  6767  6786 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-30 11:37:05.695  1028  1028 D BluetoothHeadset: Proxy object connected
08-30 11:37:05.695  1028  1106 W ProcessCpuTracker: Skipping unknown process pid 7576
08-30 11:37:05.696  1028  1106 W ProcessCpuTracker: Skipping unknown process pid 7581
08-30 11:37:05.698  6913  6929 V BluetoothMapService: getConnectedDevices()
08-30 11:37:05.699  1843  1859 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-30 11:37:05.700  6767  6767 D BluetoothPan: BluetoothPAN Proxy object connected
08-30 11:37:05.700  6767  6767 D PanProfile: Bluetooth service connected
08-30 11:37:05.701  1843  1843 D BluetoothHeadset: Proxy object connected
08-30 11:37:05.702  1028  1110 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-30 11:37:05.702  1028  1110 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-30 11:37:05.702  6767  6767 D BluetoothInputDevice: Proxy object connected
08-30 11:37:05.702  6767  6767 D HidProfile: Bluetooth service connected
08-30 11:37:05.703  1933  1933 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-30 11:37:05.703  1933  2123 D LGBluetoothAPIService: Message: 1
08-30 11:37:05.703  1933  2123 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-30 11:37:05.704  1595  1595 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-30 11:37:05.708  6540  6540 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
08-30 11:37:05.710  1028  1028 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
,08-30 11:37:05.711  1028  1110 D BluetoothManagerService: Message: 40
08-30 11:37:05.711  1028  1110 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-30 11:37:05.711  6540  6540 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 11:37:05.714  6540  6540 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 11:37:05.715  1933  2123 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
08-30 11:37:05.715  6913  6913 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-30 11:37:05.716  6913  6913 D BluetoothMapService: STATE_ON
08-30 11:37:05.716  6767  6767 D LocalBluetoothProfileManager: Adding local A2DP profile
08-30 11:37:05.717  6913  6913 D LGBluetoothAPIServer: [BTUI] onCreate()
08-30 11:37:05.717  6913  6913 D LGBluetoothAPIServer: [BTUI] onBind()
08-30 11:37:05.718  6913  6913 V BluetoothMapService: Handler(): got msg=1
08-30 11:37:05.718  1028  1110 D BluetoothManagerService: Message: 30
08-30 11:37:05.718  1933  1933 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-30 11:37:05.719  1933  2123 D LGBluetoothAPIService: Message: 100
08-30 11:37:05.719  1933  2123 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-30 11:37:05.719  6913  6913 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-30 11:37:05.720  6913  7601 D BluetoothMapMasInstance: MAS initSocket()
08-30 11:37:05.721  6913  7601 D BluetoothMapMasInstance:   masId = 00
08-30 11:37:05.721  6913  7601 D BluetoothMapMasInstance:   msgTypes = 0e
08-30 11:37:05.721  6913  7601 D BluetoothMapMasInstance:   masName = SMS/MMS
08-30 11:37:05.721  6913  7601 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-30 11:37:05.721  6767  6767 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-30 11:37:05.722  1028  1567 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 11:37:05.723  6913  7601 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 11:37:05.724  1028  1110 D BluetoothManagerService: Message: 30
08-30 11:37:05.725  6913  7601 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-30 11:37:05.725  6913  7601 V BluetoothMapMasInstance: Succeed to create listening socket 
08-30 11:37:05.725  6913  7601 D BluetoothMapMasInstance: Accepting socket connection...
08-30 11:37:05.725  6913  7459 D BluetoothAdapterProperties: Scan Mode:21
08-30 11:37:05.726  6913  7459 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-30 11:37:05.728  6540  6540 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 11:37:05.730  6540  6540 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 11:37:05.733  6767  6767 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-30 11:37:05.734  6767  6767 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-30 11:37:05.738  6913  6913 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13b70bf5
08-30 11:37:05.739  6767  6767 D BluetoothA2dp: Proxy object connected
08-30 11:37:05.739  6913  6913 V BluetoothPbapService: Pbap Service onCreate
08-30 11:37:05.739  6913  6913 V BluetoothPbapService: Starting PBAP service
08-30 11:37:05.740  6767  6767 D A2dpProfile: Bluetooth service connected
08-30 11:37:05.741  6913  6913 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-30 11:37:05.741  6913  6913 V BluetoothPbapService: Pbap Service onBind
08-30 11:37:05.742  6913  6913 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 11:37:05.742  6913  6913 V BluetoothPbapService: state: 12
08-30 11:37:05.742  6913  6913 V BluetoothPbapService: Handler(): got msg=1
08-30 11:37:05.742  6913  6913 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-30 11:37:05.743  6913  6913 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-30 11:37:05.743  6913  6913 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 11:37:05.743  6913  6913 V BluetoothPbapReceiver: ***********state = 12
08-30 11:37:05.744  6913  7602 V BluetoothPbapService: Pbap Service initSocket
08-30 11:37:05.744  6767  6767 D BluetoothHeadset: Proxy object connected
08-30 11:37:05.745  6767  6767 D HeadsetProfile: Bluetooth service connected
08-30 11:37:05.746  2195  2195 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-30 11:37:05.746  1028  1968 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-30 11:37:05.747  2195  2195 D c       : Getting all permits...
08-30 11:37:05.747  2195  2195 D a       : Opening database...
08-30 11:37:05.748  6913  7602 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 11:37:05.749  6913  7602 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-30 11:37:05.749  6913  7602 V BluetoothPbapService: Succeed to create listening socket 
08-30 11:37:05.749  6913  7602 V BluetoothPbapService: Accepting socket connection...
08-30 11:37:05.751  2195  2195 D a       : Opening database auth.proximity.permit_store...
08-30 11:37:05.751  2195  2195 D a       : Closing database...
08-30 11:37:05.756  6767  6767 D DockEventReceiver: finishStartingService: stopping service
08-30 11:37:05.757  6767  6767 D BluetoothPbap: Proxy object connected
08-30 11:37:05.758  6767  6767 D PbapServerProfile: Bluetooth service connected
08-30 11:37:05.765  6767  6767 D BluetoothPermissionRequest: onReceive
,08-30 11:37:05.767  6767  6767 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-30 11:37:05.769  6767  6767 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-30 11:37:05.772  6913  6913 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-30 11:37:05.773  6913  6913 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-30 11:37:05.778  6913  6913 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-30 11:37:05.800  6913  6913 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,08-30 11:37:05.800  6913  6913 V BtOppService: onCreate
08-30 11:37:05.804  6913  6913 V BluetoothOppNotification: send message
08-30 11:37:05.807  6913  6913 V BtOppService: Starting RfcommListener
08-30 11:37:05.810  6913  6913 D BluetoothOppPreference: Dumping Names:  
08-30 11:37:05.810  6913  6913 D BluetoothOppPreference: {}
08-30 11:37:05.810  6913  6913 D BluetoothOppPreference: Dumping Channels:  
08-30 11:37:05.810  6913  6913 D BluetoothOppPreference: {}
08-30 11:37:05.811  6913  6913 V BtOppService: onStartCommand
,08-30 11:37:05.813  6913  7610 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-30 11:37:05.814  6913  6913 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-30 11:37:05.814  6913  6913 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-30 11:37:05.817  6913  6913 V BluetoothOppNotification: new notify threadi!
08-30 11:37:05.818  6913  7607 V BtOppService: Deleted complete outbound shares, number =  0
08-30 11:37:05.819  6913  6913 V BluetoothOppNotification: send delay message
08-30 11:37:05.820  6913  7610 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-30 11:37:05.820  6913  7607 V BtOppService: Deleted complete inbound failed shares, number = 0
08-30 11:37:05.820  6913  7607 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-30 11:37:05.821  6913  6913 V BtOppService: start RfcommListener
08-30 11:37:05.821  6913  7607 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3074fc66 on behalf of 
08-30 11:37:05.822  6913  7611 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-30 11:37:05.823  6913  7610 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@239abba7 on behalf of 
,08-30 11:37:05.824  6913  6913 V BtOppService: RfcommListener started
08-30 11:37:05.825  6913  7612 V BtOppRfcommListener: Starting RFCOMM listener....
08-30 11:37:05.826  1028  1044 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 11:37:05.827  6913  7610 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-30 11:37:05.827  6913  7611 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1838f854 on behalf of 
08-30 11:37:05.827  6913  7612 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 11:37:05.828  6913  7612 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=79 mFd=75
08-30 11:37:05.828  6913  7612 V BtOppRfcommListener: Started RFCOMM listener....
08-30 11:37:05.829  6913  7612 I BtOppRfcommListener: Accept thread started.
08-30 11:37:05.829  6913  7612 V BtOppRfcommListener: Accepting connection...
08-30 11:37:05.829  6913  7611 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-30 11:37:05.831  6913  7611 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-30 11:37:05.833  6913  7611 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@10e383fd on behalf of 
08-30 11:37:05.835  6913  7611 V BluetoothOppNotification: outbound: succ-0  fail-0
,08-30 11:37:05.837  6913  7611 V BluetoothOppNotification: outbound notification was removed.
08-30 11:37:05.837  6913  7611 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-30 11:37:05.838  6913  7611 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@15c478f2 on behalf of 
08-30 11:37:05.839  6913  7611 V BluetoothOppNotification: inbound: succ-0  fail-0
08-30 11:37:05.840  6913  6913 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13b70bf5
08-30 11:37:05.841  6913  6913 V BluetoothFtpService: Ftp Service onCreate
08-30 11:37:05.841  6913  6913 I BluetoothFtpService: Ftp Service onCreate
08-30 11:37:05.841  6913  7611 V BluetoothOppNotification: inbound notification was removed.
08-30 11:37:05.841  6913  7611 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-30 11:37:05.841  6913  6913 V BluetoothFtpService: Ftp Service onStartCommand
08-30 11:37:05.841  6913  6913 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 11:37:05.841  6913  6913 V BluetoothFtpService: Starting Listening on sockets
08-30 11:37:05.841  6913  6913 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-30 11:37:05.841  6913  6913 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-30 11:37:05.841  6913  6913 V BluetoothSapReceiver: SapReceiver onReceive 
08-30 11:37:05.842  6913  6913 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 11:37:05.842  6913  6913 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-30 11:37:05.842  6913  6913 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-30 11:37:05.842  6913  7611 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1f5745c0 on behalf of 
08-30 11:37:05.844  6913  6913 V BtOppService: ContentObserver received notification
08-30 11:37:05.844  6913  6913 V BtOppService: ContentObserver received notification
08-30 11:37:05.844  6913  6913 V BluetoothFtpService: Handler(): got msg=1
08-30 11:37:05.844  6913  6913 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-30 11:37:05.845  6913  6913 V BluetoothFtpService: Ftp Service initSocket
08-30 11:37:05.846  6913  7613 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-30 11:37:05.846  6913  7613 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
,08-30 11:37:05.849  1028  1967 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-30 11:37:05.850  6913  6913 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 11:37:05.851  6913  6913 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=79
08-30 11:37:05.852  6913  6913 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-30 11:37:05.853  6913  7614 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-30 11:37:05.872  6913  6913 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13b70bf5
08-30 11:37:05.872  6913  6913 V BluetoothSapService: Sap Service onCreate
,08-30 11:37:05.977  1028  1914 I art     : Explicit concurrent mark sweep GC freed 89621(4MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/64MB, paused 2.136ms total 125.712ms
,08-30 11:37:05.979  6913  6913 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
,08-30 11:37:05.979  6913  6913 V BluetoothSapService: state: 12
08-30 11:37:05.979  6913  6913 V BluetoothSapService: Starting SAP server process
08-30 11:37:05.982  7158  7194 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
08-30 11:37:05.983  6913  6913 V BluetoothSapService: SAP Service startRfcommListenerThread
08-30 11:37:05.983  6913  7613 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@194afdec on behalf of 
08-30 11:37:05.985  6913  7618 V BluetoothSapService: Sap Service initRfcommSocket
08-30 11:37:05.986  1028  2040 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 11:37:05.986  6913  7618 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 11:37:05.987  6913  7613 V BluetoothOppNotification: update too frequent, put in queue
08-30 11:37:05.987  6913  7618 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=83 mFd=80
08-30 11:37:05.987  6913  7618 V BluetoothSapService: Succeed to create listening socket 
08-30 11:37:05.987  6913  7618 V BluetoothSapService: Accepting socket connection...
08-30 11:37:05.988  6913  7613 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-30 11:37:05.977  7617  7617 W sapd    : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6837 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 11:37:05.977  7617  7617 W sapd    : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6837 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 11:37:06.003  7617  7617 V BT_SAP  : Event pipe created
08-30 11:37:06.003  7617  7617 V BT_SAP  : create_server_socket qcom.sap.server
08-30 11:37:06.003  7617  7617 V BT_SAP  : created socket fd 6
,08-30 11:37:06.515  1028  1379 D LGWifiP2pService: P2pDisabledState{ when=-5ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-30 11:37:06.516  1028  1379 D LGWifiP2pService: DefaultState{ when=-6ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-30 11:37:06.526  1028  1383 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-30 11:37:06.528  1028  1383 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-30 11:37:06.817  1028  1967 I ActivityManager: Killing 7359:com.lge.bnr/1000 (adj 15): empty #17
,08-30 11:37:06.827  6913  6913 V BluetoothOppNotification: new notify threadi!
,08-30 11:37:06.828  6913  6913 V BluetoothOppNotification: send delay message
08-30 11:37:06.838  6913  7630 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,08-30 11:37:06.851  6913  7630 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2ed435b5 on behalf of 
,08-30 11:37:06.852  6913  7630 V BluetoothOppNotification: mUpdateCompleteNotification = true
,08-30 11:37:06.859  6913  7630 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-30 11:37:06.860  6913  7630 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@17b6344a on behalf of 
08-30 11:37:06.860  6913  7630 V BluetoothOppNotification: outbound: succ-0  fail-0
08-30 11:37:06.862  6913  7630 V BluetoothOppNotification: outbound notification was removed.
08-30 11:37:06.862  6913  7630 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-30 11:37:06.863  6913  7630 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@17beffbb on behalf of 
08-30 11:37:06.864  6913  7630 V BluetoothOppNotification: inbound: succ-0  fail-0
08-30 11:37:06.867  6913  7630 V BluetoothOppNotification: inbound notification was removed.
08-30 11:37:06.867  6913  7630 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
,08-30 11:37:06.871  6913  7630 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@13e00cd8 on behalf of 
08-30 11:37:06.884  1028  1932 W libprocessgroup: failed to open /acct/uid_1000/pid_7359/cgroup.procs: No such file or directory
,08-30 11:37:06.895  1028  1968 I ActivityManager: Killing 6687:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
08-30 11:37:06.912  6836  6836 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
08-30 11:37:06.913  6836  6836 W System.err: android.os.DeadObjectException
08-30 11:37:06.913  6836  6836 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-30 11:37:06.913  6836  6836 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-30 11:37:06.913  6836  6836 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-30 11:37:06.913  6836  6836 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-30 11:37:06.913  6836  6836 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-30 11:37:06.913  6836  6836 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-30 11:37:06.913  6836  6836 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-30 11:37:06.913  6836  6836 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-30 11:37:06.913  6836  6836 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-30 11:37:06.913  6836  6836 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-30 11:37:06.914  6836  6836 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 11:37:06.914  6836  6836 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 11:37:06.914  6836  6836 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-30 11:37:06.914  6836  6836 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-30 11:37:06.914  6836  6836 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-30 11:37:06.914  6836  6836 W System.err: android.os.DeadObjectException
08-30 11:37:06.914  6836  6836 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-30 11:37:06.914  6836  6836 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-30 11:37:06.914  6836  6836 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
,08-30 11:37:06.920  6836  6836 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-30 11:37:06.920  6836  6836 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-30 11:37:06.920  6836  6836 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-30 11:37:06.921  6836  6836 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-30 11:37:06.921  6836  6836 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-30 11:37:06.921  6836  6836 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-30 11:37:06.921  6836  6836 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-30 11:37:06.921  6836  6836 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 11:37:06.921  6836  6836 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 11:37:06.921  6836  6836 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-30 11:37:06.921  6836  6836 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-30 11:37:06.921  6836  6836 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-30 11:37:06.921  6836  6836 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
08-30 11:37:06.949  1028  1877 W libprocessgroup: failed to open /acct/uid_1000/pid_6687/cgroup.procs: No such file or directory
08-30 11:37:06.950  1028  1877 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,08-30 11:37:06.958  6836  6836 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-30 11:37:06.958  6836  6836 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-30 11:37:07.010  1028  1967 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7631 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-30 11:37:07.025  6836  6836 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-30 11:37:07.088  7631  7631 D UEI.SmartControl: Quickset Services start...
08-30 11:37:07.090  7631  7631 I UEI.SmartControl: Manufacture = LGE
,08-30 11:37:07.093  7631  7631 D UEI.SmartControl: Id = LGNevo
08-30 11:37:07.094  7631  7631 D UEI.SmartControl: File observer start...
08-30 11:37:07.095  7631  7631 E UEI.SmartControl: IR Port is disabled: false
08-30 11:37:07.095  7631  7631 D UEI.SmartControl: Starting file observer...
08-30 11:37:07.096  7631  7631 D UEI.SmartControl: Extracting JNI libs...
08-30 11:37:07.096  7631  7631 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
08-30 11:37:07.170  7631  7631 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
08-30 11:37:07.170  7631  7631 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-30 11:37:07.170  7631  7631 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,08-30 11:37:07.199  7631  7631 I UEI.SmartControl: --- Selecting new region: 6
08-30 11:37:07.200  7631  7631 I UEI.SmartControl: Model = LG-D855
08-30 11:37:07.201  7631  7631 D UEI.SmartControl: QS Service created
,08-30 11:37:07.215  7631  7631 I UEI.SmartControl: Service initServices...
,08-30 11:37:07.221  7631  7631 D UEI.SmartControl: QS start get config
08-30 11:37:07.257  7631  7631 D UEI.SmartControl: Loading JNI Libs...
,08-30 11:37:07.477  1028  1932 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-30 11:37:07.477  1028  1932 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@2ca6a8a0 mBinding = false
,08-30 11:37:07.490  1028  1110 D BluetoothManagerService: Message: 2
,08-30 11:37:07.491  1028  1028 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-30 11:37:07.491  1028  1028 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-30 11:37:07.491  1028  1028 D Ulp_jni : JNI:system_update. Event-4
,08-30 11:37:07.494  1028  1110 D BluetoothManagerService: Sending off request.
08-30 11:37:07.495  6913  6929 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-30 11:37:07.496  6913  7455 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-30 11:37:07.496  6913  7455 D BluetoothAdapterProperties: Setting state to 13
08-30 11:37:07.496  6913  7455 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-30 11:37:07.496  6913  7455 D BluetoothAdapterProperties: onBluetoothDisable()
08-30 11:37:07.496  6913  7455 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-30 11:37:07.497  6913  7459 D BluetoothAdapterProperties: Scan Mode:20
08-30 11:37:07.498  6913  7455 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-30 11:37:07.498  6913  7455 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-30 11:37:07.500  6913  7601 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-30 11:37:07.500  6913  7601 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 11:37:07.500  6913  7601 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-30 11:37:07.500  6913  7601 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-30 11:37:07.500  6913  7601 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-30 11:37:07.500  6913  7601 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-30 11:37:07.500  6913  7601 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-30 11:37:07.500  6913  7601 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-30 11:37:07.500  6913  7602 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 11:37:07.501  6913  7525 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-30 11:37:07.501  6913  7618 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 11:37:07.501  6913  7614 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 11:37:07.501  6913  7612 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 11:37:07.501  6913  7525 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-30 11:37:07.504  6913  7525 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
,08-30 11:37:07.504  6913  7525 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-30 11:37:07.504  6913  7525 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 11:37:07.504  6913  7525 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 11:37:07.504  6913  7525 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 11:37:07.504  6913  7525 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-30 11:37:07.504  6913  7525 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 11:37:07.504  6913  7525 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 11:37:07.504  6913  7525 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 11:37:07.504  6913  7525 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-30 11:37:07.504  6913  7525 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-30 11:37:07.504  6913  7525 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-30 11:37:07.510  1028  1110 D BluetoothManagerService: Message: 60
08-30 11:37:07.510  1028  1110 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-30 11:37:07.510  1028  1110 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-30 11:37:07.511  6540  6540 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 11:37:07.511  6540  6540 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 11:37:07.511  6540  6540 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 11:37:07.511  6540  6540 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 11:37:07.511  6540  6540 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 11:37:07.511  6540  6540 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 11:37:07.511  6540  6540 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 11:37:07.511  6540  6540 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 11:37:07.511  6540  6540 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 11:37:07.514  6540  6540 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 11:37:07.514  6540  6540 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 11:37:07.515  6540  6540 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 11:37:07.515  6540  6540 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 11:37:07.515  6540  6540 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 11:37:07.515  6540  6540 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 11:37:07.515  6540  6540 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 11:37:07.515  6540  6540 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 11:37:07.515  6540  6540 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 11:37:07.515  6540  6540 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 11:37:07.515  6540  6540 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 11:37:07.515  6540  6540 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for mult,iple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 11:37:07.515  6540  6540 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 11:37:07.516  1933  1933 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-30 11:37:07.518  1595  1595 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-30 11:37:07.521  6913  6913 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-30 11:37:07.521  6913  6913 D BluetoothMapService: STATE_TURNING_OFF
08-30 11:37:07.521  6913  6913 V BluetoothMapService: Handler(): got msg=4
08-30 11:37:07.521  6913  6913 D BluetoothMapService: MAP Service closeService in
08-30 11:37:07.521  6913  6913 D BluetoothMapMasInstance: MAP Service shutdown
08-30 11:37:07.521  6913  6913 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-30 11:37:07.521  6913  6913 V BluetoothMapService: MAP Service closeService out
08-30 11:37:07.521  6540  6540 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 11:37:07.523  6540  6540 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 11:37:07.523  6767  6767 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
08-30 11:37:07.523  6913  6913 V BtOppService: Receiver DISABLED_ACTION 
08-30 11:37:07.523  6913  6913 I BtOppRfcommListener: stopping Accept Thread
08-30 11:37:07.523  6913  6913 V BtOppRfcommListener: close mBtServerSocket
08-30 11:37:07.523  6913  6913 V BtOppRfcommListener: waiting for thread to terminate
08-30 11:37:07.524  6913  7612 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-30 11:37:07.524  6913  6913 V BtOppRfcommListener: done waiting for thread to terminate
08-30 11:37:07.525  6767  6767 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-30 11:37:07.526  6913  6913 V BtOppService: onDestroy
08-30 11:37:07.530  6913  6913 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-30 11:37:07.530  6913  6913 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-30 11:37:07.530  6913  6913 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
,08-30 11:37:07.530  6913  6913 V BluetoothPbapReceiver: ***********state = 13
08-30 11:37:07.533  6913  6913 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-30 11:37:07.534  6767  6767 D DockEventReceiver: finishStartingService: stopping service
08-30 11:37:07.534  6913  6913 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 11:37:07.534  6913  6913 V BluetoothPbapService: state: 13
08-30 11:37:07.534  6913  6913 V BluetoothPbapService: Pbap Service closeService in
08-30 11:37:07.536  2195  2195 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-30 11:37:07.536  6767  6767 D BluetoothPbap: Proxy object disconnected
08-30 11:37:07.536  6767  6767 D PbapServerProfile: Bluetooth service disconnected
08-30 11:37:07.537  6913  6913 V BluetoothPbapService: successfully stopped pbap service
08-30 11:37:07.537  6913  6913 V BluetoothPbapService: Pbap Service closeService out
08-30 11:37:07.538  6913  6913 V BluetoothPbapService: Pbap Service onDestroy
08-30 11:37:07.538  6913  6913 V BluetoothPbapService: Pbap Service closeService in
08-30 11:37:07.538  6913  6913 V BluetoothPbapService: Pbap Service closeService out
08-30 11:37:07.538  6913  6913 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-30 11:37:07.545  6767  6767 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-30 11:37:07.550  6767  6767 D BluetoothPermissionRequest: onReceive
08-30 11:37:07.550  6767  6767 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-30 11:37:07.560  6767  6767 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-30 11:37:07.564  6913  6913 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-30 11:37:07.564  6913  6913 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-30 11:37:07.565  6913  6913 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-30 11:37:07.569  6913  6913 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-30 11:37:07.569  6913  6913 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-30 11:37:07.570  6913  6913 V BluetoothFtpService: Ftp Service onStartCommand
08-30 11:37:07.570  6913  6913 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 11:37:07.570  6913  6913 V BluetoothFtpService: Ftp Service closeService
08-30 11:37:07.571  6913  6913 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-30 11:37:07.571  6913  6913 V BluetoothFtpService: successfully stopped ftp service
08-30 11:37:07.572  6913  6913 V BluetoothFtpService: Ftp Service onDestroy
08-30 11:37:07.572  6913  6913 V BluetoothFtpService: Ftp Service closeService
,08-30 11:37:07.575  6913  6913 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-30 11:37:07.575  6913  6913 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-30 11:37:07.575  6913  6913 V BluetoothSapReceiver: SapReceiver onReceive 
08-30 11:37:07.575  6913  6913 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 11:37:07.575  6913  6913 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-30 11:37:07.575  6913  6913 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-30 11:37:07.576  6913  6913 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 11:37:07.576  6913  6913 V BluetoothSapService: state: 13
08-30 11:37:07.576  6913  6913 V BluetoothSapService: Stopping SAP server process
08-30 11:37:07.577  6913  6913 V BluetoothSapService: Sap Service closeSapService in
08-30 11:37:07.577  6913  6913 V BluetoothSapService: Close listen Socket : 
08-30 11:37:07.577  6913  6913 V BluetoothSapService: Close rfcomm Socket : 
08-30 11:37:07.577  6913  6913 V BluetoothSapService: Close sapd  Socket : 
08-30 11:37:07.578  7631  7631 I UEI.SmartControl: Supports setup maps: true
08-30 11:37:07.580  6913  6913 V BluetoothSapService: Sap Service closeSapService out
08-30 11:37:07.580  6913  6913 V BluetoothSapService: Sap Service onDestroy
08-30 11:37:07.580  6913  6913 V BluetoothSapService: Sap Service closeSapService in
08-30 11:37:07.580  6913  6913 V BluetoothSapService: Close listen Socket : 
08-30 11:37:07.580  6913  6913 V BluetoothSapService: Close rfcomm Socket : 
08-30 11:37:07.580  6913  6913 V BluetoothSapService: Close sapd  Socket : 
08-30 11:37:07.581  6913  6913 V BluetoothSapService: Sap Service closeSapService out
08-30 11:37:07.584  7631  7631 D UEI.SmartControl: QS start statue = true Error code = 0
,08-30 11:37:07.584  7631  7631 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-30 11:37:07.584  7631  7631 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-30 11:37:07.584  7631  7631 I UEI.SmartControl: ### init IR Blaster...
08-30 11:37:07.589  7631  7631 D serial_port: Configuring serial port
08-30 11:37:07.593  7631  7631 E UEI.SmartControl: UEIBLaster setting for 616
08-30 11:37:07.593  7631  7631 I UEI.SmartControl: Setting serial record hearder size = 2
08-30 11:37:07.594  7631  7631 I UEI.SmartControl: configuring settings for MAXQ616
08-30 11:37:07.594  7631  7631 I UEI.SmartControl: Get version...
08-30 11:37:07.616  7631  7663 D UEI.SmartControl: serial port data available: 21
,08-30 11:37:07.644  7631  7631 D UEI.SmartControl: MAXQ616 A2-X4 software.
,08-30 11:37:07.645  7631  7631 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-30 11:37:07.645  7631  7631 I UEI.SmartControl: QS saving settings...
08-30 11:37:07.647  7631  7631 D UEI.SmartControl: IR Blaster version: 25672567
,08-30 11:37:07.663  7631  7663 D UEI.SmartControl: serial port data available: 4
,08-30 11:37:07.706  7631  7670 I UEI.SmartControl: Device manager: loading config....
,08-30 11:37:07.708  7631  7670 D UEI.SmartControl: ----------- loading internal config...
08-30 11:37:07.710  7631  7631 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-30 11:37:07.714  7631  7631 E UEI.SmartControl: Services init done
08-30 11:37:07.715  7631  7631 D UEI.SmartControl: QS Service init finished
08-30 11:37:07.719  7631  7631 D UEI.SmartControl: QS Service version name: 2.1.91
08-30 11:37:07.720  7631  7631 D UEI.SmartControl: QS Service version code: 201091
08-30 11:37:07.721  7631  7631 D UEI.SmartControl: Service requested: Control
,08-30 11:37:07.727  7631  7631 D UEI.SmartControl: Request IControl service: devices are loaded...
08-30 11:37:07.731  6836  6836 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-30 11:37:07.733  7631  7647 I UEI.SmartControl: ------ IControl API: 11
08-30 11:37:07.734  1028  1578 I ActivityManager: Killing 6836:com.lge.qremote/u0a112 (adj 15): empty #17
,08-30 11:37:07.737  7631  7647 I UEI.SmartControl: Registering callback...
08-30 11:37:07.739  7631  7670 E UEI.SmartControl: Loading SETTINGS...
08-30 11:37:07.754  7631  7670 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,08-30 11:37:07.782  7631  7669 I UEI.SmartControl: Notify AllClients services are ready: 0
08-30 11:37:07.782  7631  7669 D UEI.SmartControl: -----service ready thread exits
,08-30 11:37:07.817  1028  1878 W libprocessgroup: failed to open /acct/uid_10112/pid_6836/cgroup.procs: No such file or directory
,08-30 11:37:07.820  7631  7631 D UEI.SmartControl: Internal service binding...
,08-30 11:37:08.409  6913  7459 D bt_hci_bdroid: cleanup
,08-30 11:37:08.414  6913  7527 I bt_lpm  : LPM is already off!!!
,08-30 11:37:08.417  6913  7568 I bt_userial_mct: exiting userial_read_thread
,08-30 11:37:08.417  6913  7568 D bt_userial_mct: Leaving userial_evt_read_thread()
08-30 11:37:08.418  6913  7525 W bt-btif : ag scb idx 1 not allocated
08-30 11:37:08.418  6913  7525 E bt-btif : BTA AG is already disabled, ignoring ...
08-30 11:37:08.418  6913  7525 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 11:37:08.418  6913  7525 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 11:37:08.418  6913  7525 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-30 11:37:08.418  6913  7525 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 11:37:08.418  6913  7525 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 11:37:08.418  6913  7525 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 11:37:08.418  6913  7525 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 11:37:08.418  6913  7525 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 11:37:08.419  6913  7525 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-30 11:37:08.419  6913  7525 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 11:37:08.419  6913  7525 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 11:37:08.419  6913  7525 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 11:37:08.419  6913  7525 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
,08-30 11:37:08.419  6913  7525 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 11:37:08.419  6913  7525 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-30 11:37:08.419  6913  7525 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 11:37:08.419  6913  7525 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 11:37:08.419  6913  7525 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 11:37:08.419  6913  7525 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-30 11:37:08.422  6913  7459 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-30 11:37:08.430  6913  7527 I bt_vendor: hw_epilog_process
,08-30 11:37:08.439  6913  7459 D bt_hci_bdroid: cleanup Finalizing cleanup
08-30 11:37:08.440  6913  7459 D bt_userial_mct: userial_close
08-30 11:37:08.440  6913  7459 E bt_userial_mct: pthread_join() FAILED result:3
08-30 11:37:08.440  6913  7459 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-30 11:37:08.445  6913  7459 D bt_hci_bdroid: set_power 0
08-30 11:37:08.445  6913  7459 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-30 11:37:08.445  6913  7459 I bt_vendor: bluetooth satus is on
08-30 11:37:08.445  6913  7459 I bt_vendor: bt-vendor : resetting BT status
08-30 11:37:08.445  6913  7459 I bt_vendor: Starting hciattach daemon
08-30 11:37:08.447  6913  7459 I bt_vendor: try to set false
08-30 11:37:08.448  6913  7459 I bt_vendor: Starting hciattach daemon
08-30 11:37:08.448  6913  7459 I bt_vendor: try to set false
08-30 11:37:08.449  6913  7459 I bt_vendor: cleanup
,08-30 11:37:08.451  6913  7525 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-30 11:37:08.452  6913  7459 I GKI_LINUX: GKI_exit_task 0 done
08-30 11:37:08.452  6913  7459 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-30 11:37:08.453  6913  7455 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-30 11:37:08.458  6913  6913 D HeadsetService: Received stop request...Stopping profile...
08-30 11:37:08.462  6913  6913 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-30 11:37:08.462  6913  6913 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-30 11:37:08.462  6913  6913 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13b70bf5
,08-30 11:37:08.464  6913  7478 D HeadsetStateMachine: Exit Disconnected: -1
08-30 11:37:08.466  1843  1843 D BluetoothHeadset: Proxy object disconnected
08-30 11:37:08.466  1843  1843 D BluetoothHeadset: Proxy object disconnected
08-30 11:37:08.466  1843  1843 D BluetoothHeadset: Proxy object disconnected
08-30 11:37:08.468  1028  1028 D BluetoothHeadset: Proxy object disconnected
08-30 11:37:08.468  1028  1028 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-30 11:37:08.469  6913  6913 D A2dpService: Received stop request...Stopping profile...
08-30 11:37:08.469  6913  7509 D A2dpStateMachine: Exit Disconnected: -1
08-30 11:37:08.472  6913  6913 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-30 11:37:08.477  6913  7455 D BluetoothAdapterState: Stopping profile services that were post enabled
,08-30 11:37:08.479  6913  6913 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-30 11:37:08.480  6913  6913 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-30 11:37:08.480  6913  6913 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13b70bf5
08-30 11:37:08.481  1028  1028 D BluetoothA2dp: Proxy object disconnected
08-30 11:37:08.481  1028  1028 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-30 11:37:08.483  6913  6913 D HidService: Received stop request...Stopping profile...
08-30 11:37:08.483  6913  6913 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13b70bf5
08-30 11:37:08.486  6913  6913 D HealthService: Received stop request...Stopping profile...
08-30 11:37:08.486  6913  6913 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13b70bf5
08-30 11:37:08.490  6913  6913 D HeadsetStateMachine: Unbinding service...
,08-30 11:37:08.493  6913  6913 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-30 11:37:08.493  6913  6913 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-30 11:37:08.493  6913  6913 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-30 11:37:08.493  6913  6913 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-30 11:37:08.493  6913  6913 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-30 11:37:08.493  6913  6913 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-30 11:37:08.493  6913  6913 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-30 11:37:08.494  6913  6913 D PanService: Received stop request...Stopping profile...
08-30 11:37:08.495  6913  6913 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13b70bf5
08-30 11:37:08.496  6913  6913 D BtGatt.DebugUtils: handleDebugAction() action=null
08-30 11:37:08.497  6913  6913 D BtGatt.GattService: Received stop request...Stopping profile...
08-30 11:37:08.497  6913  6913 D BtGatt.GattService: stop()
08-30 11:37:08.497  6913  6913 D BtGatt.AdvertiseManager: advertise clients cleared
08-30 11:37:08.498  6913  6913 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13b70bf5
08-30 11:37:08.501  6913  6913 D BluetoothMapService: Received stop request...Stopping profile...
08-30 11:37:08.502  6913  6913 D BluetoothMapService: stop()
,08-30 11:37:08.508  6913  6913 D BluetoothMapEmailAppObserver: deinitObservers(),
08-30 11:37:08.508  6913  6913 D BluetoothMapEmailAppObserver: removeReceiver()
08-30 11:37:08.509  6913  6913 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13b70bf5
08-30 11:37:08.510  6913  6913 I BluetoothA2dpServiceJni: cleanupNative
08-30 11:37:08.511  6913  7510 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-30 11:37:08.512  6913  6913 I GKI_LINUX: GKI_exit_task 2 done
08-30 11:37:08.512  6913  6913 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-30 11:37:08.512  6913  6913 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-30 11:37:08.512  6913  6913 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-30 11:37:08.512  6913  6913 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-30 11:37:08.513  6913  6913 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-30 11:37:08.513  6913  6913 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-30 11:37:08.513  6913  6913 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-30 11:37:08.513  6913  6913 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-30 11:37:08.517  6913  6913 V BluetoothMapService: Handler(): got msg=4
08-30 11:37:08.517  6913  6913 D BluetoothMapService: MAP Service closeService in
08-30 11:37:08.517  6913  6913 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-30 11:37:08.517  6913  6913 V BluetoothMapService: MAP Service closeService out
08-30 11:37:08.518  6913  7455 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-30 11:37:08.518  6913  7455 D BluetoothAdapterProperties: Setting state to 10
08-30 11:37:08.518  6913  7455 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-30 11:37:08.519  1028  1110 D BluetoothManagerService: Message: 60
08-30 11:37:08.519  1028  1110 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-30 11:37:08.519  1028  1110 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
08-30 11:37:08.519  6913  7455 I BluetoothAdapterState: Entering OffState
08-30 11:37:08.520  6767  6786 D BluetoothA2dp: onBluetoothStateChange: up=false
08-30 11:37:08.522  6913  6913 D BluetoothMapService: cleanup()
08-30 11:37:08.522  6913  6913 D BluetoothMapService: MAP Service closeService in
08-30 11:37:08.522  6913  6913 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-30 11:37:08.522  6913  6913 V BluetoothMapService: MAP Service closeService out
08-30 11:37:08.524  1028  1110 D BluetoothA2dp: onBluetoothStateChange: up=false
08-30 11:37:08.524  1843  1858 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 11:37:08.525  6767  6786 D BluetoothMap: onBluetoothStateChange: up=false
,08-30 11:37:08.528  6767  6786 D BluetoothPan: onBluetoothStateChange on: false
08-30 11:37:08.529  1843  1859 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 11:37:08.529  6767  6786 D BluetoothPbap: onBluetoothStateChange: up=false
08-30 11:37:08.530  1028  1110 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 11:37:08.530  6767  6786 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 11:37:08.530  6767  6786 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-30 11:37:08.531  1843  3563 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 11:37:08.532  1028  1110 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-30 11:37:08.532  1028  1110 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-30 11:37:08.534  1028  1110 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-30 11:37:08.534  1028  1110 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-30 11:37:08.534  1028  1110 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@2ca6a8a0 mBinding = false
08-30 11:37:08.536  1028  1110 D BluetoothManagerService: Sending unbind request.
08-30 11:37:08.540  6913  7459 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-30 11:37:08.543  6913  6913 I GKI_LINUX: GKI_exit_task 1 done
08-30 11:37:08.543  6913  6913 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-30 11:37:08.543  6913  6913 I BluetoothServiceJni: cleanupNative: return from cleanup
08-30 11:37:08.544  6913  6913 I art     : --- WEIRD: removing null entry 248
08-30 11:37:08.544  6913  6913 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
08-30 11:37:08.544  6913  6913 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-30 11:37:08.545  6913  6913 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-30 11:37:08.546  1028  1110 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-30 11:37:08.549  6913  6913 I art     : System.exit called, status: 0
08-30 11:37:08.549  6913  6913 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-30 11:37:08.569  1933  1933 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: disconnected from LGBluetoothAPIAdapter
,08-30 11:37:08.571  1933  2123 D LGBluetoothAPIService: Message: 101
08-30 11:37:08.572  1933  2123 E LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED
08-30 11:37:08.572  1933  2123 D LGBluetoothAPIService: Calling onBluetoothServiceDown callbacks
08-30 11:37:08.568   320  2150 V AudioFlinger: 6913 died, releasing its sessions
08-30 11:37:08.572   320  2150 V AudioFlinger:  pid 1843 @ 0
08-30 11:37:08.572   320  2150 V AudioFlinger:  pid 3470 @ 1
08-30 11:37:08.572   320  2150 V AudioFlinger:  pid 3470 @ 2
08-30 11:37:08.572  1933  2123 D LGBluetoothAPIService: Broadcasting onBluetoothServiceDown() to 0 receivers.
08-30 11:37:08.574  6767  6767 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-30 11:37:08.585  1028  1043 I ActivityManager: Process com.android.bluetooth (pid 6913) has died
08-30 11:37:08.585  1028  1043 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 4000ms
08-30 11:37:08.585  1028  1043 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer in 14000ms
,08-30 11:37:08.593  1933  1933 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-30 11:37:08.594  1595  1595 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-30 11:37:08.595  1933  2123 D LGBluetoothAPIService: Message: 2
08-30 11:37:08.595  1933  2123 D LGBluetoothAPIService: unbindAndFinish(): null mBinding = false
08-30 11:37:08.596  6540  6540 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 11:37:08.596  6540  6540 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 11:37:08.597  6767  6767 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-30 11:37:08.597  6767  6767 D LGBluetoothEventManager: [BTUI] clear device connection state
,08-30 11:37:08.613  6767  6767 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-30 11:37:08.618  1595  1595 D BluetoothAdapter: 319402564: getState() :  mService = null. Returning STATE_OFF
08-30 11:37:08.618  1595  1595 D BluetoothAdapter: 319402564: getState() :  mService = null. Returning STATE_OFF
08-30 11:37:08.670  1028  1968 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=7702 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-30 11:37:08.674  6767  6767 D DockEventReceiver: finishStartingService: stopping service
,08-30 11:37:08.734  7702  7702 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-30 11:37:08.735  7702  7702 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-30 11:37:08.735  7702  7702 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-30 11:37:08.736  7702  7702 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-30 11:37:08.756  7702  7702 D BluetoothAdapterApp: Loading JNI Library
,08-30 11:37:08.791  7702  7702 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@172d23d Instance Count = 1
,08-30 11:37:08.797  7702  7702 D BluetoothAdapterApp: onCreate
,08-30 11:37:08.820  7702  7702 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-30 11:37:08.820  7702  7702 D ProfileConfigQcom: Adding HeadsetService
08-30 11:37:08.820  7702  7702 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-30 11:37:08.821  7702  7702 D ProfileConfigQcom: Adding A2dpService
08-30 11:37:08.821  7702  7702 D ProfileConfigQcom: [BTUI] HidService is supported
08-30 11:37:08.821  7702  7702 D ProfileConfigQcom: Adding HidService
08-30 11:37:08.821  7702  7702 D ProfileConfigQcom: [BTUI] HealthService is supported
08-30 11:37:08.821  7702  7702 D ProfileConfigQcom: Adding HealthService
08-30 11:37:08.822  7702  7702 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-30 11:37:08.823  7702  7702 D ProfileConfigQcom: [BTUI] PanService is supported
08-30 11:37:08.824  7702  7702 D ProfileConfigQcom: Adding PanService
,08-30 11:37:08.824  7702  7702 D ProfileConfigQcom: [BTUI] GattService is supported
08-30 11:37:08.825  7702  7702 D ProfileConfigQcom: Adding GattService
08-30 11:37:08.826  7702  7702 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
,08-30 11:37:08.826  7702  7702 D ProfileConfigQcom: Adding BluetoothMapService
08-30 11:37:08.826  7702  7702 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-30 11:37:08.827  7702  7702 V BluetoothPbapReceiver: PbapReceiver onReceive 
,08-30 11:37:08.828  7702  7702 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 11:37:08.829  7702  7702 V BluetoothPbapReceiver: ***********state = 10
08-30 11:37:08.830  7702  7702 V LGMDMManagerInternal: Create singleton instance
08-30 11:37:08.895  2195  2195 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 11:37:08.912  6767  6767 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
,08-30 11:37:08.917  7702  7702 D LGBluetoothAPIServer: [BTUI] onCreate()
08-30 11:37:08.917  7702  7702 D LGBluetoothAPIServer: [BTUI] onBind()
08-30 11:37:08.922  1933  1933 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-30 11:37:08.922  1933  2123 D LGBluetoothAPIService: Message: 100
08-30 11:37:08.922  1933  2123 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-30 11:37:08.926  6767  6767 D BluetoothPermissionRequest: onReceive
,08-30 11:37:08.928  6767  6767 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-30 11:37:08.929  6767  6767 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-30 11:37:08.930  6767  6767 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-30 11:37:08.933  7702  7702 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-30 11:37:08.937  7702  7702 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-30 11:37:08.939  7702  7702 V BluetoothSapReceiver: [BTUI] checkServiceStart
,08-30 11:37:08.940  7702  7702 V BluetoothSapReceiver: [BTUI] region:EU country:EU
,08-30 11:37:08.940  7702  7702 V BluetoothSapReceiver: SapReceiver onReceive 
,08-30 11:37:08.941  7702  7702 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
,08-30 11:37:08.941  7702  7702 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
,08-30 11:37:08.947  7532  7532 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,08-30 11:37:10.490  6540  6656 D io.jxcore.node.ConnectivityMonitor: stop,
08-30 11:37:10.490  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 11:37:10.686  1595  1595 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,08-30 11:37:10.751  1028  1370 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-30 11:37:10.794  1028  1106 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7733 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-30 11:37:10.810  1595  1595 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
08-30 11:37:10.811  1595  1595 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
08-30 11:37:10.835  2025  2025 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-30 11:37:10.853  1028  1028 D administrator: Handling package changes for user 0
,08-30 11:37:10.885  1028  1368 V AlarmManager: ELAPSED_WAKEUP set : Alarm{3ac307a6 type 2 when 131914 com.google.android.gms} when 131914
,08-30 11:37:10.887  2025  2025 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-30 11:37:10.902  7733  7733 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-30 11:37:10.973  7733  7733 D LgDataFeature: LgDataFeature() Constructor: none
08-30 11:37:10.973  7733  7733 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 11:37:11.011  1028  1028 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
08-30 11:37:11.011  1028  1028 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-30 11:37:11.064  1028  1105 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-30 11:37:11.066  7733  7776 I Babel   : MmsConfig: mnc/mcc: 0/0
08-30 11:37:11.066  7733  7776 I Babel   : MmsConfig.loadMmsSettings
08-30 11:37:11.069  7733  7776 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-30 11:37:11.070  7733  7776 I Babel   : MmsConfig.loadFromDatabase
08-30 11:37:11.074  1028  1105 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,08-30 11:37:11.082  2025  2025 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-30 11:37:11.086  7733  7776 E Babel   : canonicalizeMccMnc: invalid mccmnc 
08-30 11:37:11.087  7733  7776 I Babel   : MmsConfig.loadFromResources
08-30 11:37:11.087  2500  2500 V GmsNetworkLocationProvi: DISABLE
08-30 11:37:11.088  7733  7776 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
08-30 11:37:11.088  7733  7776 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
,08-30 11:37:11.128  1028  1105 D LocationProviderProxy: applying state to connected service
08-30 11:37:11.130  2500  2500 E GCoreFlp: Bound FusedProviderService with LocationManager
08-30 11:37:11.131  7733  7733 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 11:37:11.141  7733  7775 W AudioCapabilities: Unsupported mime audio/evrc
,08-30 11:37:11.142  7733  7775 W AudioCapabilities: Unsupported mime audio/qcelp
08-30 11:37:11.143  7733  7775 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-30 11:37:11.162  7733  7775 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
08-30 11:37:11.163  7733  7775 W AudioCapabilities: Unsupported mime audio/qcelp
08-30 11:37:11.164  7733  7775 W AudioCapabilities: Unsupported mime audio/evrc
08-30 11:37:11.167  1808  7780 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
08-30 11:37:11.167  1808  7780 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
08-30 11:37:11.178  6972  6972 I AppUp4:CustModeStarterReceiver: onReceive
,08-30 11:37:11.184  6972  6972 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@23ac54df
08-30 11:37:11.184  6972  6972 D AppUp4:CustFacade: isCustomizationCompleted : false
08-30 11:37:11.184  6972  6972 D AppUp4:CustFacade: isPhone : true
08-30 11:37:11.184  6972  6972 D AppUp4:CustModeStarterReceiver: begin check event
08-30 11:37:11.184  6972  6972 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
08-30 11:37:11.187  1808  4777 I Icing   : updateResources: need to parse e{com.google.android.gms}
08-30 11:37:11.197  7733  7775 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-30 11:37:11.206  7733  7775 W VideoCapabilities: Unsupported mime video/divx
08-30 11:37:11.208  7733  7775 W VideoCapabilities: Unsupported mime video/divx311
,08-30 11:37:11.210  7733  7775 W VideoCapabilities: Unsupported mime video/divx4
08-30 11:37:11.214  7733  7775 W VideoCapabilities: Unsupported mime video/mp4v-esdp
08-30 11:37:11.227  7733  7775 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-30 11:37:11.231  7733  7775 W AudioCapabilities: Unsupported mime audio/eac3
08-30 11:37:11.232  7733  7775 W AudioCapabilities: Unsupported mime audio/ac3
08-30 11:37:11.233  7733  7775 W AudioCapabilities: Unsupported mime audio/g726
08-30 11:37:11.234  7733  7775 W AudioCapabilities: Unsupported mime audio/wma-voice
08-30 11:37:11.234  1028  1932 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7783 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
08-30 11:37:11.235  7733  7775 W AudioCapabilities: Unsupported mime audio/x-ms-wma
08-30 11:37:11.236  7733  7775 W AudioCapabilities: Unsupported mime audio/adpcm
08-30 11:37:11.240  1028  1914 I ActivityManager: Killing 6788:com.lge.sync/1000 (adj 15): empty #17
,08-30 11:37:11.255  7733  7775 W VideoCapabilities: Unsupported mime video/theora
,08-30 11:37:11.258  1028  1433 D WifiService: Client connection lost with reason: 4
08-30 11:37:11.259  7733  7775 W VideoCapabilities: Unsupported mime video/mjpg
08-30 11:37:11.317  1028  1912 W libprocessgroup: failed to open /acct/uid_1000/pid_6788/cgroup.procs: No such file or directory
,08-30 11:37:11.347  7783  7783 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 11:37:11.347  7783  7783 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-30 11:37:11.348  7783  7783 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-30 11:37:11.348  7783  7783 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
08-30 11:37:11.349  7783  7783 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,08-30 11:37:11.400  7783  7783 I SystemConfig: BUILD Country: EU
08-30 11:37:11.400  7783  7783 I SystemConfig: BUILD Operator: OPEN
,08-30 11:37:11.436  1028  1044 I ActivityManager: Killing 7023:com.lge.email/u0a23 (adj 15): empty #17
,08-30 11:37:11.542  1028  1877 W libprocessgroup: failed to open /acct/uid_10023/pid_7023/cgroup.procs: No such file or directory
,08-30 11:37:11.557  7783  7802 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
08-30 11:37:11.557  7783  7802 I SystemConfig: existFile = false
08-30 11:37:11.557  7783  7802 I SystemConfig: canReadFile = false
08-30 11:37:11.558  7783  7802 I SystemConfig: systemFeature RCS result false
08-30 11:37:11.558  7783  7802 D SystemConfig: refreshRcsSupport() :false
,08-30 11:37:11.597  1028  1044 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7804 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,08-30 11:37:11.635  7804  7804 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 11:37:11.635  7804  7804 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-30 11:37:11.635  7804  7804 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-30 11:37:11.635  7804  7804 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-30 11:37:11.683  7804  7804 I AppConfig: Total System Memory = 2995761152
,08-30 11:37:11.688  7804  7804 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
08-30 11:37:11.760  1028  1914 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7826 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-30 11:37:11.761  1028  1914 I ActivityManager: Killing 6876:com.lge.formmanager/u0a26 (adj 15): empty #17
,08-30 11:37:11.857  1028  1043 W libprocessgroup: failed to open /acct/uid_10026/pid_6876/cgroup.procs: No such file or directory
,08-30 11:37:12.096  7826  7826 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,08-30 11:37:12.185  7826  7826 D LgDataFeature: LgDataFeature() Constructor: none
08-30 11:37:12.185  7826  7826 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 11:37:12.260  7826  7826 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,08-30 11:37:12.283  7826  7826 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-30 11:37:12.285  7826  7826 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-30 11:37:12.302  7826  7826 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-30 11:37:12.303  7826  7826 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,08-30 11:37:12.333  1028  2040 I ActivityManager: Killing 6373:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,08-30 11:37:12.472  1028  2005 W libprocessgroup: failed to open /acct/uid_1000/pid_6373/cgroup.procs: No such file or directory
,08-30 11:37:12.478  3527  3544 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
08-30 11:37:12.480  3527  3544 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@3e440753 on behalf of 7826
08-30 11:37:12.487  4620  7863 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,08-30 11:37:12.555  1028  1578 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7864 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,08-30 11:37:12.572  7826  7826 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,08-30 11:37:12.586   344   344 I art     : Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 468us total 41.795ms
,08-30 11:37:12.609   344   344 I art     : Explicit concurrent mark sweep GC freed 7(224B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 446us total 21.186ms
08-30 11:37:12.612  7826  7826 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
08-30 11:37:12.638   344   344 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 457us total 28.927ms
,08-30 11:37:12.651  7864  7864 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,08-30 11:37:12.676  7864  7864 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
08-30 11:37:12.677  7864  7864 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
08-30 11:37:12.677  7864  7864 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
08-30 11:37:12.677  7864  7864 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
08-30 11:37:12.677  7864  7864 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
08-30 11:37:12.677  7864  7864 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
,08-30 11:37:12.690   315  7891 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,08-30 11:37:12.691  1028  1108 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-30 11:37:12.703  7631  7671 D UEI.SmartControl: Internal timer expired: 1
08-30 11:37:12.703  7631  7671 D UEI.SmartControl: unbind internal service
,08-30 11:37:12.741  1028  1578 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=7892 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,08-30 11:37:12.749  7631  7631 D UEI.SmartControl: Service.onUnbind: IControl
08-30 11:37:12.749  7631  7631 D UEI.SmartControl: Service.onDestroy
08-30 11:37:12.749  7631  7631 D UEI.SmartControl: Lock is in USE false
08-30 11:37:12.749  7631  7631 D UEI.SmartControl: unbind internal service
08-30 11:37:12.749  7631  7631 W System.err: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@22b5ffb
08-30 11:37:12.750  7631  7631 W System.err: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
08-30 11:37:12.750  7631  7631 W System.err: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
08-30 11:37:12.750  7631  7631 W System.err: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
08-30 11:37:12.750  7631  7631 W System.err: 	at com.uei.control.Service.c(Unknown Source)
08-30 11:37:12.750  7631  7631 W System.err: 	at com.uei.control.Service.onDestroy(Unknown Source)
08-30 11:37:12.750  7631  7631 W System.err: 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
08-30 11:37:12.750  7631  7631 W System.err: 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
08-30 11:37:12.750  7631  7631 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
08-30 11:37:12.750  7631  7631 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 11:37:12.750  7631  7631 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-30 11:37:12.750  7631  7631 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-30 11:37:12.750  7631  7631 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 11:37:12.750  7631  7631 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 11:37:12.750  7631  7631 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-30 11:37:12.750  7631  7631 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-30 11:37:12.750  7631  7631 E UEI.SmartControl: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@22b5ffb
08-30 11:37:12.751  7631  7631 D serial_port: close(fd = 25)
08-30 11:37:12.756  7631  7631 I UEI.SmartControl: Serial port is closed.
08-30 11:37:12.756  7631  7631 I UEI.SmartControl: Serial port is closed.
08-30 11:37:12.756  7631  7631 D UEI.SmartControl: Blaster closed
08-30 11:37:12.756  7631  7631 D UEI.SmartControl: Shut down QS...
08-30 11:37:12.756  7631  7631 D UEI.SmartControl: Stopping QS lib
08-30 11:37:12.756  7631  7631 D UEI.SmartControl: QS lib stop result = true
08-30 11:37:12.756  7631  7631 D UEI.SmartControl: Stopped QS lib
08-30 11:37:12.757  7631  7631 D UEI.SmartControl: Stopped file observer...
08-30 11:37:12.757  7631  7631 D UEI.SmartControl: QS shutdown complete
,08-30 11:37:12.762  1028  1912 I ActivityManager: Killing 7065:com.google.android.setupwizard/u0a46 (adj 15): empty #17
08-30 11:37:12.796  1028  2040 W libprocessgroup: failed to open /acct/uid_10046/pid_7065/cgroup.procs: No such file or directory
,08-30 11:37:12.826  7892  7892 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-30 11:37:12.873  7892  7892 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,08-30 11:37:12.910  7892  7892 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
08-30 11:37:12.910  7892  7892 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-30 11:37:12.910  7892  7892 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-30 11:37:12.911  7892  7892 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-30 11:37:12.911  7892  7892 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
,08-30 11:37:12.913  7892  7892 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-30 11:37:12.918  7892  7892 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-30 11:37:12.924  7892  7892 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
,08-30 11:37:12.925  7892  7892 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:1338
08-30 11:37:12.928  7892  7892 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-30 11:37:12.930  7892  7892 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-30 11:37:12.931  7892  7892 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-30 11:37:12.932  7892  7892 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-30 11:37:12.932  7892  7892 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
08-30 11:37:12.957  1028  1968 V SIM_STK : Menu title from STK is T-Mobile
,08-30 11:37:12.976  4620  7863 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 489 ms] updated apps [took 489 ms] 
,08-30 11:37:12.982  7892  7892 D LgDataFeature: LgDataFeature() Constructor: none
,08-30 11:37:12.983  7892  7892 D LgDataFeature: LgDataFeature() Constructor Done, null
08-30 11:37:12.992  7892  7892 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
,08-30 11:37:12.994  7892  7892 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-30 11:37:12.994  7892  7892 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-30 11:37:12.994  7892  7892 V SoundPool: doLoad: loading sample sampleID=1
08-30 11:37:12.994  7892  7892 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-30 11:37:12.996  7892  7913 V SoundPool: Start decode
08-30 11:37:12.996  7892  7913 V MediaPlayer[Native]: decode(31, 10857164, 17813)
08-30 11:37:12.997   320  1390 V MediaPlayerService: decode(23, 10857164, 17813)
08-30 11:37:12.997   320  1390 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-30 11:37:12.997   320  1390 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-30 11:37:12.997   320  1390 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-30 11:37:12.997   320  1390 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-30 11:37:12.997   320  1390 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-30 11:37:12.997   320  1390 V MediaPlayerService: player type = 3
08-30 11:37:12.997   320  1390 V AwesomePlayer: AwesomePlayer create()
08-30 11:37:12.998   320  1390 V AwesomePlayer: reset_l() 
08-30 11:37:12.998   320  1390 V AwesomePlayer: cancelPlayerEvents
08-30 11:37:12.998   320  1390 V AwesomePlayer: setAudioSink() 
08-30 11:37:12.998   320  1390 V AwesomePlayer: reset_l() 
08-30 11:37:12.998   320  1390 V AudioCache: notify(0xb1003280, 8, 0, 0)
08-30 11:37:12.998   320  1390 V AudioCache: ignored
08-30 11:37:12.998   320  1390 V AwesomePlayer: cancelPlayerEvents
,08-30 11:37:12.998   320  1390 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
08-30 11:37:12.998   320  1390 V AwesomePlayer: setDataSource_l dataSource
08-30 11:37:12.998   320  1390 V LGParserOSAL: SniffLGParser start
08-30 11:37:12.998   320  1390 V LGParserOSAL: MainType:5, SubType=0
08-30 11:37:12.998   320  1390 V LGParserOSAL: #### check Mime : application/ogg
08-30 11:37:12.998   320  1390 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-30 11:37:12.998   320  1390 E MediaExtractor: Use LGExtractor :application/ogg 
08-30 11:37:13.000  7631  7631 D UEI.SmartControl: QS Service created
08-30 11:37:13.006  7892  7892 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-30 11:37:13.008  7892  7892 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-30 11:37:13.008  7892  7892 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-30 11:37:13.020  7892  7892 V LGMDMManager: Create singleton instance
,08-30 11:37:13.027  7631  7631 I UEI.SmartControl: Service initServices...
08-30 11:37:13.027  7631  7631 D UEI.SmartControl: QS start get config
,08-30 11:37:13.046   320  1390 V LGParserOSAL: supported mime: application/ogg
08-30 11:37:13.046   320  1390 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-30 11:37:13.046   320  1390 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-30 11:37:13.046   320  1390 V AwesomePlayer: mBitrate = -1 bits/sec
08-30 11:37:13.046   320  1390 V AwesomePlayer: AudioTrack Setting
08-30 11:37:13.046   320  1390 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-30 11:37:13.046   320  1390 V AwesomePlayer: setAudioSource() 
08-30 11:37:13.046   320  1390 V MediaPlayerService: prepare
08-30 11:37:13.046   320  1390 V AwesomePlayer: prepareAsync_l() 
08-30 11:37:13.046   320  1390 V MediaPlayerService: wait for prepare
08-30 11:37:13.046   320  7914 V AwesomePlayer: onPrepareAsyncEvent() 
08-30 11:37:13.047   320  7914 V AwesomePlayer: initAudioDecoder() 
08-30 11:37:13.047   320  7914 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-30 11:37:13.047   320  7914 V AudioSystem: isOffloadSupported()
08-30 11:37:13.047   320  7914 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-30 11:37:13.047   320  7914 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-30 11:37:13.047   320  7914 I AudioFlinger: isAudioPlaybackHookOn() false
08-30 11:37:13.047   320  7914 V AwesomePlayer: getUseOffload() = 0 
08-30 11:37:13.047   320  7914 V OMXCodec: OMXCodec::Create
08-30 11:37:13.047   320  7914 V OMXCodec: findMatchingCodecs()
08-30 11:37:13.047   320  7914 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-30 11:37:13.047   320  7914 V OMXCodec: matchingCodecs.size()=1
08-30 11:37:13.047   320  7914 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,08-30 11:37:13.051   320  7914 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-30 11:37:13.051   320  7914 V LGCodecAdapter: LG Codec Adapter start
08-30 11:37:13.051   320  7914 V OMXCodec: OMXCodec Createtor
08-30 11:37:13.051   320  7914 V OMXCodec: setComponentRole
08-30 11:37:13.051   320  7914 V OMXCodec: configureCodec protected=0
08-30 11:37:13.051   320  7914 V LGCodecAdapter: called getLGCodecSpecificData
08-30 11:37:13.051   320  7914 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-30 11:37:13.051   320  7914 V LGCodecOSAL: Called LGconfigureCodecMETA
08-30 11:37:13.052   320  7914 V LGCodecOSAL: Called LGconfigureCodecMSG
08-30 11:37:13.052   320  7914 V LGCodecOSAL: Not support LGCodec
08-30 11:37:13.052   320  7914 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-30 11:37:13.052   320  7914 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-30 11:37:13.052   320  7914 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-30 11:37:13.052   320  7914 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-30 11:37:13.052   320  7914 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-30 11:37:13.052   320  7914 V AudioSystem: isOffloadSupported()
08-30 11:37:13.052   320  7914 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-30 11:37:13.052   320  7914 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-30 11:37:13.052   320  7914 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-30 11:37:13.052   320  7914 V OMXCodec: init()
08-30 11:37:13.053   320  7914 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-30 11:37:13.053   320  7914 V OMXCodec: allocateBuffers
08-30 11:37:13.053   320  7914 V OMXCodec: allocateBuffersOnPort portIndex=0
08-30 11:37:13.053   320  7914 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-30 11:37:13.053   320  7914 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b00 on input port
08-30 11:37:13.053   320  7914 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ba0 on input port
08-30 11:37:13.053   320  7914 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7dd0 on input port
08-30 11:37:13.054   320  7914 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7e20 on input port
08-30 11:37:13.054   320  7914 V OMXCodec: allocateBuffersOnPort portIndex=1
08-30 11:37:13.054   320  7914 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-30 11:37:13.054   320  7914 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ec0 on output port
08-30 11:37:13.054   320  7914 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57bb060 on output port
08-30 11:37:13.054   320  7914 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57bb470 on output port
08-30 11:37:13.054   320  7914 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57bb560 on output port
08-30 11:37:13.054   320  7914 V OMXCodec: init() mAsyncCompletion wait!!! 
08-30 11:37:13.055   320  7916 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-30 11:37:13.055   320  7916 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-30 11:37:13.055   320  7916 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-30 11:37:13.055   320  7916 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-30 11:37:13.055   320  7916 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-30 11:37:13.055   320  7916 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=,4
08-30 11:37:13.061   320  7914 V OMXCodec: init() mAsyncCompletion wait free! 
08-30 11:37:13.061   320  7914 V AwesomePlayer: finishAsyncPrepare_l() 
08-30 11:37:13.061   320  7914 V AudioCache: notify(0xb1003280, 5, 0, 0)
08-30 11:37:13.061   320  7914 V AudioCache: ignored
08-30 11:37:13.061   320  7914 V AudioCache: notify(0xb1003280, 1, 0, 0)
08-30 11:37:13.061   320  7914 V AudioCache: prepared
08-30 11:37:13.061   320  1390 V AudioCache: wait - success
08-30 11:37:13.061   320  1390 V MediaPlayerService: start
08-30 11:37:13.061   320  1390 V AwesomePlayer: play_l() 
08-30 11:37:13.061   320  1390 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-30 11:37:13.062   320  1390 V AwesomePlayer: createAudioPlayer_l
08-30 11:37:13.062   320  1390 V AwesomePlayer: seekAudioIfNecessary_l() 
08-30 11:37:13.062   320  1390 V AwesomePlayer: startAudioPlayer_l() 
08-30 11:37:13.062   320  1390 D AudioPlayer: start of Playback, useOffload 0
08-30 11:37:13.062   320  1390 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-30 11:37:13.062   320  1390 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-30 11:37:13.063   320  7916 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-30 11:37:13.063   320  7916 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-30 11:37:13.064   320  7916 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-30 11:37:13.064   320  7916 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-30 11:37:13.064   320  7916 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-30 11:37:13.064   320  7916 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-30 11:37:13.064   320  7916 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885888
08-30 11:37:13.064   320  7916 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-30 11:37:13.064   320  7916 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044782176
08-30 11:37:13.064   320  7916 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-30 11:37:13.065   320  7916 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044783216
08-30 11:37:13.065   320  7916 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
,08-30 11:37:13.065   320  7916 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044783456,
08-30 11:37:13.065   320  7916 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-30 11:37:13.065   320  7916 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-30 11:37:13.065   320  7916 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-30 11:37:13.065   320  7916 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-30 11:37:13.065   320  7916 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-30 11:37:13.065   320  7916 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-30 11:37:13.065   320  7916 V OMXCodec: allocateBuffersOnPort portIndex=1
08-30 11:37:13.065   320  7916 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-30 11:37:13.066   320  7916 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57bb470 on output port
,08-30 11:37:13.066   320  7916 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57bb060 on output port
08-30 11:37:13.066   320  7916 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ec0 on output port
08-30 11:37:13.066   320  7916 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f240 on output port
08-30 11:37:13.066   320  7916 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-30 11:37:13.066   320  7916 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-30 11:37:13.070   320  1390 V AudioCache: open(48000, 2, 0x0, 1, 4),
08-30 11:37:13.070   320  1390 V AudioCache: notify(0xb1003280, 6, 0, 0)
08-30 11:37:13.070   320  1390 V AudioCache: ignored
08-30 11:37:13.071   320  1390 V MediaPlayerService: wait for playback complete
08-30 11:37:13.072   320  7917 V AudioCache: write(0xb178b000, 4096)
08-30 11:37:13.072   320  7917 V AudioCache: memcpy(0xaf006000, 0xb178b000, 4096)
,08-30 11:37:13.074   320  7917 V AudioCache: write(0xb178b000, 4096)
08-30 11:37:13.074   320  7917 V AudioCache: memcpy(0xaf007000, 0xb178b000, 4096)
08-30 11:37:13.075   320  7917 V AudioCache: write(0xb178b000, 4096)
08-30 11:37:13.075   320  7917 V AudioCache: memcpy(0xaf008000, 0xb178b000, 4096)
08-30 11:37:13.076   320  7917 V AudioCache: write(0xb178b000, 4096)
08-30 11:37:13.076   320  7917 V AudioCache: memcpy(0xaf009000, 0xb178b000, 4096)
08-30 11:37:13.076   320  7917 V AudioCache: write(0xb178b000, 4096)
,08-30 11:37:13.076   320  7917 V AudioCache: memcpy(0xaf00a000, 0xb178b000, 4096)
08-30 11:37:13.077   320  7917 V AudioCache: write(0xb178b000, 4096)
08-30 11:37:13.077   320  7917 V AudioCache: memcpy(0xaf00b000, 0xb178b000, 4096)
08-30 11:37:13.078   320  7917 V AudioCache: write(0xb178b000, 4096)
08-30 11:37:13.078   320  7917 V AudioCache: memcpy(0xaf00c000, 0xb178b000, 4096)
08-30 11:37:13.078   320  7917 V AudioCache: write(0xb178b000, 4096),
08-30 11:37:13.078   320  7917 V AudioCache: memcpy(0xaf00d000, 0xb178b000, 4096)
,08-30 11:37:13.081   320  7917 V AudioCache: write(0xb178b000, 4096)
08-30 11:37:13.081   320  7917 V AudioCache: memcpy(0xaf00e000, 0xb178b000, 4096)
08-30 11:37:13.082   320  7917 V AudioCache: write(0xb178b000, 4096)
08-30 11:37:13.082   320  7917 V AudioCache: memcpy(0xaf00f000, 0xb178b000, 4096)
08-30 11:37:13.082   320  7917 V AudioCache: write(0xb178b000, 4096)
08-30 11:37:13.082   320  7917 V AudioCache: memcpy(0xaf010000, 0xb178b000, 4096)
08-30 11:37:13.082   320  7917 V AudioCache: write(0xb178b000, 4096)
08-30 11:37:13.082   320  7917 V AudioCache: memcpy(0xaf011000, 0xb178b000, 4096)
08-30 11:37:13.083   320  7917 V AudioCache: write(0xb178b000, 4096)
08-30 11:37:13.083   320  7917 V AudioCache: memcpy(0xaf012000, 0xb178b000, 4096)
08-30 11:37:13.084   320  7917 V AudioCache: write(0xb178b000, 4096)
08-30 11:37:13.084   320  7917 V AudioCache: memcpy(0xaf013000, 0xb178b000, 4096)
08-30 11:37:13.084   320  7917 V AudioCache: write(0xb178b000, 4096)
08-30 11:37:13.084   320  7917 V AudioCache: memcpy(0xaf014000, 0xb178b000, 4096)
08-30 11:37:13.085   320  7917 V AudioCache: write(0xb178b000, 4096)
08-30 11:37:13.085   320  7917 V AudioCache: memcpy(0xaf015000, 0xb178b000, 4096)
08-30 11:37:13.085   320  7917 V AudioCache: write(0xb178b000, 4096)
08-30 11:37:13.085   320  7917 V AudioCache: memcpy(0xaf016000, 0xb178b000, 4096)
08-30 11:37:13.086   320  7917 V AudioCache: write(0xb178b000, 4096)
08-30 11:37:13.086   320  7917 V AudioCache: memcpy(0xaf017000, 0xb178b000, 4096)
08-30 11:37:13.087   320  7917 V AudioCache: write(0xb178b000, 4096)
08-30 11:37:13.087   320  7917 V AudioCache: memcpy(0xaf018000, 0xb178b000, 4096)
08-30 11:37:13.088   320  7917 V AudioCache: write(0xb178b000, 4096)
08-30 11:37:13.088   320  7917 V AudioCache: memcpy(0xaf019000, 0xb178b000, 4096)
08-30 11:37:13.088   320  7917 V AudioCache: write(0xb178b000, 4096)
08-30 11:37:13.088   320  7917 V AudioCache: memcpy(0xaf01a000, 0xb178b000, 4096)
08-30 11:37:13.089   320  7917 V AudioCache: write(0xb178b000, 4096)
,08-30 11:37:13.089   320  7917 V AudioCache: memcpy(0xaf01b000, 0xb178b000, 4096)
08-30 11:37:13.089   320  7917 V AudioCache: write(0xb178b000, 4096)
08-30 11:37:13.089   320  7917 V AudioCache: memcpy(0xaf01c000, 0xb178b000, 4096)
08-30 11:37:13.089   320  7917 V AudioCache: write(0xb178b000, 4096)
08-30 11:37:13.089   320  7917 V AudioCache: memcpy(0xaf01d000, 0xb178b000, 4096)
08-30 11:37:13.090   320  7917 V AudioCache: write(0xb178b000, 4096)
08-30 11:37:13.090   320  7917 V AudioCache: memcpy(0xaf01e000, 0xb178b000, 4096)
08-30 11:37:13.090   320  7917 V AudioCache: write(0xb178b000, 4096)
08-30 11:37:13.090   320  7917 V AudioCache: memcpy(0xaf01f000, 0xb178b000, 4096)
08-30 11:37:13.090   320  7917 V AudioCache: write(0xb178b000, 4096)
08-30 11:37:13.090   320  7917 V AudioCache: memcpy(0xaf020000, 0xb178b000, 4096)
08-30 11:37:13.091   320  7917 V AudioCache: write(0xb178b000, 4096)
08-30 11:37:13.091   320  7917 V AudioCache: memcpy(0xaf021000, 0xb178b000, 4096)
08-30 11:37:13.091   320  7917 V AudioCache: write(0xb178b000, 4096)
08-30 11:37:13.091   320  7917 V AudioCache: memcpy(0xaf022000, 0xb178b000, 4096)
08-30 11:37:13.092   320  7917 V AudioCache: write(0xb178b000, 4096)
08-30 11:37:13.092   320  7917 V AudioCache: memcpy(0xaf023000, 0xb178b000, 4096)
08-30 11:37:13.092   320  7917 V AudioCache: write(0xb178b000, 4096)
08-30 11:37:13.092   320  7917 V AudioCache: memcpy(0xaf024000, 0xb178b000, 4096)
08-30 11:37:13.092   320  7917 V AudioCache: write(0xb178b000, 4096)
08-30 11:37:13.092   320  7917 V AudioCache: memcpy(0xaf025000, 0xb178b000, 4096)
08-30 11:37:13.093   320  7917 V AudioCache: write(0xb178b000, 4096)
08-30 11:37:13.093   320  7917 V AudioCache: memcpy(0xaf026000, 0xb178b000, 4096)
08-30 11:37:13.093   320  7917 V AudioCache: write(0xb178b000, 4096)
08-30 11:37:13.093   320  7917 V AudioCache: memcpy(0xaf027000, 0xb178b000, 4096)
08-30 11:37:13.093   320  7917 V AudioCache: write(0xb178b000, 4096)
08-30 11:37:13.093   320  7917 V AudioCache: memcpy(0xaf028000, 0xb178b000, 4096)
08-30 11:37:13.094   320  7917 V AudioCache: write(0xb178b000, 4096)
08-30 11:37:13.094   320  7917 V AudioCache: memcpy(0xaf029000, 0xb178b000, 4096)
08-30 11:37:13.094   320  7917 V AudioCache: write(0xb178b000, 4096)
08-30 11:37:13.094   320  7917 V AudioCache: memcpy(0xaf02a000, 0xb178b000, 4096)
08-30 11:37:13.094   320  7917 V AudioCache: write(0xb178b000, 4096)
08-30 11:37:13.094   320  7917 V AudioCache: memcpy(0xaf02b000, 0xb178b000, 4096)
08-30 11:37:13.096   320  7917 V AudioCache: write(0xb178b000, 4096)
08-30 11:37:13.096   320  7917 V AudioCache: memcpy(0xaf02c000, 0xb178b000, 4096)
08-30 11:37:13.096   320  7917 V AudioCache: write(0xb178b000, 4096)
08-30 11:37:13.096   320  7917 V AudioCache: memcpy(0xaf02d000, 0xb178b000, 4096)
08-30 11:37:13.096   320  7917 V AudioCache: write(0xb178b000, 4096)
08-30 11:37:13.096   320  7917 V AudioCache: memcpy(0xaf02e000, 0xb178b000, 4096)
08-30 11:37:13.096   320  7917 V AudioCache: write(0xb178b000, 4096)
08-30 11:37:13.096   320  7917 V AudioCache: memcpy(0xaf02f000, 0xb178b000, 4096)
08-30 11:37:13.098   320  7917 V AudioCache: write(0xb178b000, 4096)
08-30 11:37:13.098   320  7917 V AudioCache: memcpy(0xaf030000, 0xb178b000, 4096)
08-30 11:37:13.098   320  7917 V AudioCache: write(0xb178b000, 4096)
08-30 11:37:13.098   320  7917 V AudioCache: memcpy(0xaf031000, 0xb178b000, 4096)
08-30 11:37:13.100   320  7917 V AudioCache: write(0xb178b000, 4096)
08-30 11:37:13.100   320  7917 V AudioCache: memcpy(0xaf032000, 0xb178b000, 4096)
08-30 11:37:13.100   320  7917 V AudioCache: write(0xb178b000, 4096)
08-30 11:37:13.100   320  7917 V AudioCache: memcpy(0xaf033000, 0xb178b000, 4096)
08-30 11:37:13.100   320  7917 V AudioCache: write(0xb178b000, 4096)
08-30 11:37:13.100   320  7917 V AudioCache: memcpy(0xaf034000, 0xb178b000, 4096)
08-30 11:37:13.100   320  7917 V AudioCache: write(0xb178b000, 4096)
08-30 11:37:13.100   320  7917 V AudioCache: memcpy(0xaf035000, 0xb178b000, 4096)
08-30 11:37:13.101   320  7917 V Au,dioCache: write(0xb178b000, 4096)
08-30 11:37:13.101   320  7917 V AudioCache: memcpy(0xaf036000, 0xb178b000, 4096)
08-30 11:37:13.101   320  7917 V AudioCache: write(0xb178b000, 4096)
08-30 11:37:13.101   320  7917 V AudioCache: memcpy(0xaf037000, 0xb178b000, 4096)
08-30 11:37:13.101   320  7916 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-30 11:37:13.102   320  7917 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-30 11:37:13.102   320  7917 V AwesomePlayer: postAudioEOS() 
08-30 11:37:13.102   320  7917 V AudioCache: write(0xb178b000, 280)
08-30 11:37:13.102   320  7917 V AudioCache: memcpy(0xaf038000, 0xb178b000, 280)
08-30 11:37:13.104   320  7914 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-30 11:37:13.104   320  7914 V AwesomePlayer: onStreamDone
08-30 11:37:13.104   320  7914 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-30 11:37:13.104   320  7914 V AudioCache: notify(0xb1003280, 2, 0, 0)
08-30 11:37:13.104   320  7914 V AudioCache: playback complete
08-30 11:37:13.104   320  7914 V AwesomePlayer: pause_l() 
08-30 11:37:13.104   320  7914 V AudioCache: notify(0xb1003280, 7, 0, 0)
08-30 11:37:13.104   320  7914 V AudioCache: ignored
08-30 11:37:13.104   320  7914 V AwesomePlayer: cancelPlayerEvents
08-30 11:37:13.104   320  1390 V AudioCache: wait - success
08-30 11:37:13.104   320  1390 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-30 11:37:13.104   320  7914 D AudioPlayer: Pause Playback at 1068125
08-30 11:37:13.105   320  1390 V AwesomePlayer: reset_l() 
08-30 11:37:13.105   320  1390 V AudioCache: notify(0xb1003280, 8, 0, 0)
08-30 11:37:13.105   320  1390 V AudioCache: ignored
08-30 11:37:13.105   320  1390 V AwesomePlayer: cancelPlayerEvents
08-30 11:37:13.105   320  1390 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-30 11:37:13.105   320  1390 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-30 11:37:13.105   320  1390 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-30 11:37:13.105   320  1390 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-30 11:37:13.105   320  1390 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-30 11:37:13.106   320  7916 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-30 11:37:13.106   320  7916 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-30 11:37:13.106   320  7916 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-30 11:37:13.106   320  7916 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7e20 on port 0
08-30 11:37:13.106   320  7916 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-30 11:37:13.106   320  7916 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7dd0 on port 0
08-30 11:37:13.106   320  7916 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-30 11:37:13.106   320  7916 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ba0 on port 0
08-30 11:37:13.106   320  7916 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-30 11:37:13.106   320  7916 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b00 on port 0
08-30 11:37:13.106   320  7916 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-30 11:37:13.106   320  7916 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1,
08-30 11:37:13.106   320  7916 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f240 on port 1
08-30 11:37:13.106   320  7916 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-30 11:37:13.106   320  7916 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ec0 on port 1
08-30 11:37:13.106   320  7916 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-30 11:37:13.106   320  7916 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb57bb060 on port 1
08-30 11:37:13.106   320  7916 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-30 11:37:13.106   320  7916 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb57bb470 on port 1
,08-30 11:37:13.106   320  7916 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-30 11:37:13.106   320  7916 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-30 11:37:13.107   320  1390 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-30 11:37:13.107   320  1390 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-30 11:37:13.107   320  7916 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-30 11:37:13.107   320  7916 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
,08-30 11:37:13.107   320  7916 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-30 11:37:13.107   320  1390 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-30 11:37:13.107   320  1390 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-30 11:37:13.107   320  1390 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-30 11:37:13.108   320  1390 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
,08-30 11:37:13.108   320  1390 D AudioPlayer: AudioPlayer releasing audio source
08-30 11:37:13.108   320  1390 D AudioPlayer: AudioPlayer done releasing audio source
08-30 11:37:13.108   320  1390 V AwesomePlayer: reset_l() 
08-30 11:37:13.108   320  1390 V AwesomePlayer: cancelPlayerEvents
08-30 11:37:13.109   320  1390 V AwesomePlayer: ~AwesomePlayer call
08-30 11:37:13.109   320  1390 V AwesomePlayer: reset_l() ,
08-30 11:37:13.109   320  1390 V AwesomePlayer: cancelPlayerEvents
08-30 11:37:13.109  7892  7913 V SoundPool: close(31)
08-30 11:37:13.109  7892  7913 V SoundPool: pointer = 0x9fe38000, size = 205080, sampleRate = 48000, numChannels = 2
,08-30 11:37:13.126  7892  7892 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view,
08-30 11:37:13.127  7892  7892 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
,08-30 11:37:13.129  7892  7892 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:4335,
08-30 11:37:13.335  7631  7631 I UEI.SmartControl: Supports setup maps: true
08-30 11:37:13.338  7631  7631 D UEI.SmartControl: QS start statue = true Error code = 0
,08-30 11:37:13.338  7631  7631 I UEI.SmartControl: QS version = v2.7.10.1_RC1,
,08-30 11:37:13.338  7631  7631 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-30 11:37:13.339  7631  7631 I UEI.SmartControl: ### init IR Blaster...
08-30 11:37:13.342  7631  7631 D serial_port: Configuring serial port
08-30 11:37:13.343  7631  7631 E UEI.SmartControl: UEIBLaster setting for 616
08-30 11:37:13.343  7631  7631 I UEI.SmartControl: Setting serial record hearder size = 2
08-30 11:37:13.343  7631  7631 I UEI.SmartControl: configuring settings for MAXQ616
08-30 11:37:13.343  7631  7631 I UEI.SmartControl: Get version...
08-30 11:37:13.361  7631  7918 D UEI.SmartControl: serial port data available: 21
,08-30 11:37:13.388  7631  7631 D UEI.SmartControl: MAXQ616 A2-X4 software.
,08-30 11:37:13.388  7631  7631 I UEI.SmartControl: IR Blaster version: 256702256704300002
,08-30 11:37:13.388  7631  7631 I UEI.SmartControl: QS saving settings...
08-30 11:37:13.390  7631  7631 D UEI.SmartControl: IR Blaster version: 25672567
,08-30 11:37:13.408  7631  7918 D UEI.SmartControl: serial port data available: 4
,08-30 11:37:13.448  7631  7924 I UEI.SmartControl: Device manager: loading config....
,08-30 11:37:13.449  7631  7924 D UEI.SmartControl: ----------- loading internal config...
,08-30 11:37:13.451  7631  7631 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-30 11:37:13.461  7631  7631 E UEI.SmartControl: Services init done
08-30 11:37:13.462  7631  7631 D UEI.SmartControl: QS Service init finished
08-30 11:37:13.463  7631  7631 D UEI.SmartControl: QS Service version name: 2.1.91
08-30 11:37:13.464  7631  7631 D UEI.SmartControl: QS Service version code: 201091
08-30 11:37:13.465  7631  7631 D UEI.SmartControl: Service requested: Control
08-30 11:37:13.467  7631  7924 E UEI.SmartControl: Loading SETTINGS...
08-30 11:37:13.470  7631  7631 D UEI.SmartControl: Request IControl service: devices are loaded...
08-30 11:37:13.474  7631  7631 D UEI.SmartControl: Internal service binding...
08-30 11:37:13.474  7892  7892 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
,08-30 11:37:13.475  7631  7924 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-30 11:37:13.478  7631  7647 I UEI.SmartControl: ------ IControl API: 11
08-30 11:37:13.478  7631  7647 D UEI.SmartControl: File observer start...
08-30 11:37:13.478  7631  7647 E UEI.SmartControl: IR Port is disabled: false
08-30 11:37:13.478  7631  7647 D UEI.SmartControl: Starting file observer...
08-30 11:37:13.478  7631  7647 I UEI.SmartControl: Registering callback...
08-30 11:37:13.479  7631  7673 I UEI.SmartControl: ------ IControl API: 19
08-30 11:37:13.480  7631  7673 I UEI.SmartControl: Registering Services Ready callback...
08-30 11:37:13.481  7631  7673 I UEI.SmartControl: Notify client services are ready...
08-30 11:37:13.481  7892  7907 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-30 11:37:13.482  7892  7911 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-30 11:37:13.482  7892  7911 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-30 11:37:13.483  7892  7892 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-30 11:37:13.483  7892  7892 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-30 11:37:13.483  7631  7646 I UEI.SmartControl: ------ IControl API: 8
08-30 11:37:13.485  7892  7892 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-30 11:37:13.485  7892  7892 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-30 11:37:13.486  7892  7892 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-30 11:37:13.486  7892  7892 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
,08-30 11:37:13.487  7892  7892 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-30 11:37:13.487  7892  7892 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-30 11:37:13.489  7892  7892 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
08-30 11:37:13.493  7892  7892 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-30 11:37:13.494  7892  7892 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-30 11:37:13.494  7892  7892 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-30 11:37:13.495  7892  7892 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-30 11:37:13.496  7892  7892 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-30 11:37:13.498  7892  7892 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-30 11:37:13.498  7631  7923 I UEI.SmartControl: Notify AllClients services are ready: 0
08-30 11:37:13.498  7892  7892 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-30 11:37:13.498  7892  7907 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-30 11:37:13.499  7892  7911 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-30 11:37:13.499  7892  7911 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-30 11:37:13.499  7631  7923 D UEI.SmartControl: -----service ready thread exits
08-30 11:37:13.499  7892  7892 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1472549833499]
,08-30 11:37:13.502  7892  7892 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
08-30 11:37:13.503  7892  7892 D QRemote : [RemoteControlManager.java:327:handleMessage()] oooooo 140510:retrieveDevices already complete. Do nothing
08-30 11:37:13.504  1028  1967 I ActivityManager: Killing 7084:com.android.chrome/u0a57 (adj 15): empty #17
08-30 11:37:13.509  6540  6656 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 11:37:13.509  6540  6656 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1341e819 added. We now have 6 listener(s)
08-30 11:37:13.509  6540  6656 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 11:37:13.510  6540  6656 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 11:37:13.510  6540  6656 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@241da0de added. We now have 7 listener(s)
08-30 11:37:13.510  6540  6656 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 11:37:13.511  6540  6656 I System.out: IsBluetoothEnabled
,08-30 11:37:13.533  7892  7929 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-30 11:37:13.538  1028  1877 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 11:37:13.538  1028  1877 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
08-30 11:37:13.539  1028  1578 W libprocessgroup: failed to open /acct/uid_10057/pid_7084/cgroup.procs: No such file or directory
,08-30 11:37:13.540  1028  1110 D BluetoothManagerService: Message: 2
08-30 11:37:13.545  6540  6656 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 11:37:13.546  1028  1043 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 11:37:13.546  1028  1043 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-30 11:37:13.548  7892  7892 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
08-30 11:37:13.550  7892  7892 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-30 11:37:13.551  7892  7892 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-30 11:37:13.551  7892  7892 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-30 11:37:13.551  7892  7892 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-30 11:37:13.552  7892  7892 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-30 11:37:13.552  7892  7892 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
,08-30 11:37:13.568  1028  1110 D BluetoothManagerService: Message: 1
08-30 11:37:13.569  1028  1110 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-30 11:37:13.572  1028  1028 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-30 11:37:13.572  1028  1028 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-30 11:37:13.572  1028  1028 D Ulp_jni : JNI:system_update. Event-4
08-30 11:37:13.580  7892  7892 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,08-30 11:37:13.590  1028  1110 D BluetoothManagerService: Message: 20
08-30 11:37:13.591  1028  1110 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b42a802:true
08-30 11:37:13.592  7702  7702 D BluetoothAdapterState: make
08-30 11:37:13.596  7702  7702 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
,08-30 11:37:13.597  7702  7702 I bluedroid-qcom: init
08-30 11:37:13.598  7702  7702 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-30 11:37:13.598  7702  7944 I BluetoothAdapterState: Entering OffState
08-30 11:37:13.598  7702  7702 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-30 11:37:13.598  7702  7702 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-30 11:37:13.598  7702  7702 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-30 11:37:13.598  7702  7702 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-30 11:37:13.600  7702  7702 I bluedroid-qcom: get_profile_interface socket
08-30 11:37:13.600  7702  7702 I bluedroid-qcom: get_profile_interface map_client
08-30 11:37:13.587  7947  7947 W bdaddr_loader: type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6837 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-30 11:37:13.587  7947  7947 W bdaddr_loader: type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6837 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 11:37:13.601  7702  7948 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-30 11:37:13.604  1028  1028 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-30 11:37:13.604  1028  1110 D BluetoothManagerService: Message: 40
08-30 11:37:13.604  1028  1110 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-30 11:37:13.606  7702  7718 I bluedroid-qcom: config_hci_snoop_log
08-30 11:37:13.607  1028  1110 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-30 11:37:13.607  1028  1110 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-30 11:37:13.608  7947  7947 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-30 11:37:13.608  7947  7947 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-30 11:37:13.608  7947  7947 I LGFTMITEM: [GET_FTM][id=8], offset=16384
08-30 11:37:13.608  7702  7948 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-30 11:37:13.608  7947  7947 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-30 11:37:13.611  1028  1028 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-30 11:37:13.611  7702  7948 D BluetoothAdapterProperties: Name is: G3
08-30 11:37:13.611  1028  1028 D BluetoothManagerService: Stored Bluetooth name: G3
,08-30 11:37:13.614  7947  7947 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-30 11:37:13.614  7947  7947 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-30 11:37:13.617  7702  7944 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-30 11:37:13.617  7702  7944 D BluetoothAdapterProperties: Setting state to 11
08-30 11:37:13.618  7702  7944 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-30 11:37:13.618  1028  1110 D BluetoothManagerService: Message: 60
08-30 11:37:13.618  1028  1110 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-30 11:37:13.618  1028  1110 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-30 11:37:13.620  1595  1595 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-30 11:37:13.621  6767  6767 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-30 11:37:13.621  1933  1933 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-30 11:37:13.621  7702  7944 I LGBluetoothServiceJni: classInitNative: succeeds
08-30 11:37:13.623  6540  6540 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 11:37:13.627  7702  7702 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-30 11:37:13.627  7702  7702 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 11:37:13.627  7702  7702 V BluetoothPbapReceiver: ***********state = 11
,08-30 11:37:13.628  7702  7944 D BluetoothBondStateMachine: make
08-30 11:37:13.631  2195  2195 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-30 11:37:13.632  7702  7944 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f12ed8a
08-30 11:37:13.632  7702  7944 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-30 11:37:13.632  7702  7944 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f12ed8a
08-30 11:37:13.632  7702  7944 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-30 11:37:13.632  7702  7944 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-30 11:37:13.633  7702  7950 I BluetoothBondStateMachine: StableState(): Entering Off State
08-30 11:37:13.637  7702  7944 E BluetoothAdapterService: File transfer profiles supported!!
08-30 11:37:13.646  7702  7702 D HeadsetService: Received start request. Starting profile...
08-30 11:37:13.646  6767  6767 D BluetoothPermissionRequest: onReceive
08-30 11:37:13.647  7702  7702 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
,08-30 11:37:13.647  7702  7702 D LGBluetoothHfpAdapter: Version 1.6
08-30 11:37:13.647  7702  7944 E BluetoothAdapterService: File transfer profiles supported!!
08-30 11:37:13.650  7702  7702 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-30 11:37:13.650  6767  6767 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-30 11:37:13.651  7702  7702 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-30 11:37:13.651  7702  7702 D HeadsetStateMachine: make
08-30 11:37:13.655  7702  7944 E BluetoothAdapterService: File transfer profiles supported!!
08-30 11:37:13.659  7702  7944 E BluetoothAdapterService: File transfer profiles supported!!
,08-30 11:37:13.663  7702  7944 E BluetoothAdapterService: File transfer profiles supported!!
,08-30 11:37:13.668  7702  7944 E BluetoothAdapterService: File transfer profiles supported!!
08-30 11:37:13.672  7702  7944 E BluetoothAdapterService: File transfer profiles supported!!
,08-30 11:37:13.684  7702  7702 D LgDataFeature: LgDataFeature() Constructor: none
08-30 11:37:13.684  7702  7702 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 11:37:13.687  7702  7944 V LGMDMManager: Create singleton instance
08-30 11:37:13.688  7702  7702 D HeadsetStateMachine: max_hf_connections = 1
08-30 11:37:13.688  7702  7702 I bluedroid-qcom: get_profile_interface handsfree
08-30 11:37:13.689  7702  7944 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-30 11:37:13.690  7702  7702 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-30 11:37:13.690   320   320 V AudioPolicyService: registerClient() client 0xb558ac60, uid 1002
08-30 11:37:13.690   320  2150 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-30 11:37:13.690   320  2150 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-30 11:37:13.690   320  2150 V AudioPolicyManagerEx: getOutput() returns output 2
08-30 11:37:13.690  7702  7702 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-30 11:37:13.691   320  2151 V AudioFlinger: registerClient() client 0xb14331a8, pid 7702
08-30 11:37:13.691   320  1384 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 11:37:13.691   320  1384 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 11:37:13.691  1028  1932 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 11:37:13.691  1028  1932 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 11:37:13.691  7702  7702 V ToneGenerator: Create Track: 0xb4928080
08-30 11:37:13.691  7702  7702 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-30 11:37:13.691  7702  7702 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-30 11:37:13.692  1595  1616 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 11:37:13.692   320  1390 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-30 11:37:13.692  1595  1616 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 11:37:13.692  7702  7719 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 11:37:13.692   320  1390 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-30 11:37:13.692   320  1390 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-30 11:37:13.692  7702  7719 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-30 11:37:13.692   320  1390 V AudioPolicyManagerEx: getOutput() returns output 2
08-30 11:37:13.692  1843  1859 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 11:37:13.692  1843  1859 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 11:37:13.692  3470  3487 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 11:37:13.692  3470  3487 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 11:37:13.692   320  2150 I AudioFlinger: isAudioPlaybackHookOn() false
08-30 11:37:13.692   320  1385 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 11:37:13.692   320  1385 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 11:37:13.692   320  2150 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-30 11:37:13.692   320  2150 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-30 11:37:13.692   320  2150 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-30 11:37:13.692   320  2150 V AudioPolicyManagerEx: getOutput() returns output 2
08-30 11:37:13.692  1028  1968 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 11:37:13.692  1028  1968 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 11:37:13.692  7702  7702 V AudioSystem: getLatency() output 2, latency 50
08-30 11:37:13.692  7702  7702 V AudioSystem: getFrameCount() output 2, fram,eCount 960
08-30 11:37:13.692  7702  7702 V AudioTrack: createTrack_l() output 2 afLatency 50
08-30 11:37:13.692  1595  1612 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 11:37:13.692  1595  1612 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 11:37:13.692  1843  3563 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 11:37:13.692  1843  3563 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 11:37:13.692  3470  3485 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 11:37:13.693  3470  3485 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 11:37:13.693   320  2150 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-30 11:37:13.693   320  2150 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-30 11:37:13.693   320  2150 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-30 11:37:13.693  7702  7718 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 11:37:13.693   320  2150 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-30 11:37:13.693   320  2150 V AudioFlinger: createTrack() lSessionId: 21
08-30 11:37:13.693  7702  7718 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-30 11:37:13.693  7702  7702 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-30 11:37:13.693   320  2150 V AudioFlinger: acquiring 21 from 7702, for 7702
08-30 11:37:13.693   320  2150 V AudioFlinger:  added new entry for 21
08-30 11:37:13.694  7702  7702 V ToneGenerator: ToneGenerator INIT OK, time: 134739
08-30 11:37:13.694  7702  7702 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f12ed8a
08-30 11:37:13.694  7702  7951 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-30 11:37:13.694  7702  7951 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-30 11:37:13.695  7702  7951 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-30 11:37:13.695  7702  7951 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-30 11:37:13.695   320  1389 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7702
08-30 11:37:13.695  7702  7702 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f12ed8a
08-30 11:37:13.695   320  1389 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-30 11:37:13.695   320  1389 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-30 11:37:13.695   320  1389 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-30 11:37:13.695   320  1389 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-30 11:37:13.695   320  1389 V voice   : voice_set_parameters: exit with code(0)
08-30 11:37:13.696   320  1389 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-30 11:37:13.696   320  1389 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-30 11:37:13.696   320  1389 V msm8974_platform: platform_set_parameters: exit with code(0)
08-30 11:37:13.696   320  1389 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-30 11:37:13.696   320  1389 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-30 11:37:13.696   320  1389 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-30 11:37:13.696  7702  7951 V ToneGenerator: ToneGenerator destructor
08-30 11:37:13.696  7702  7951 V ToneGenerator: stopTone
08-30 11:37:13.696  7702  7951 V ToneGenerator: Delete Track: 0xb4928080
08-30 11:37:13.697  7702  7702 D A2dpService: Received start request. Starting profile...
08-30 11:37:13.697   320  2151 V AudioPolicyService: AudioCommandThread() adding release output 2
08-30 11:37:13.69,7   320  2151 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-30 11:37:13.697   320  1265 V AudioPolicyService: AudioCommandThread() waking up
08-30 11:37:13.697   320  1265 V AudioPolicyService: AudioCommandThread() processing release output 2
08-30 11:37:13.697   320  1265 V AudioPolicyManager: releaseOutput() 2
08-30 11:37:13.697   320  1265 V AudioPolicyService: AudioCommandThread() going to sleep
08-30 11:37:13.697  7702  7702 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-30 11:37:13.697   320  2151 V AudioFlinger: PlaybackThread::Track destructor
08-30 11:37:13.697   320  2151 V AudioFlinger: removeClient_l() pid 7702, calling pid 320
08-30 11:37:13.697  7702  7951 V AudioTrack: ~AudioTrack, releasing session id from 7702 on behalf of 7702
08-30 11:37:13.697   320  2150 V AudioFlinger: releasing 21 from 7702 for 7702
08-30 11:37:13.697   320  2150 V AudioFlinger:  decremented refcount to 0
08-30 11:37:13.697   320  2150 V AudioFlinger: purging stale effects
08-30 11:37:13.698  7702  7702 V Avrcp   : make
08-30 11:37:13.698  7702  7702 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-30 11:37:13.698  7702  7702 I bluedroid-qcom: get_profile_interface avrcp
08-30 11:37:13.705  1028  2024 W Process : Unable to open /proc/7952/status
08-30 11:37:13.705  7702  7702 V AudioManager: registerRemoteController: size of Media player list: 0
08-30 11:37:13.707  7702  7702 E AudioManager: No RCC entry present to update
08-30 11:37:13.707  7702  7702 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-30 11:37:13.710  7702  7702 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-30 11:37:13.711  7702  7702 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-30 11:37:13.711  7702  7702 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
,08-30 11:37:13.839  1028  1932 I art     : Explicit concurrent mark sweep GC freed 25506(1215KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 1.857ms total 125.599ms
08-30 11:37:13.840  7702  7702 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,08-30 11:37:13.926  1028  1914 V SIM_STK : Menu title from STK is T-Mobile
08-30 11:37:13.926  1028  1914 V SIM_STK : Menu title from STK is T-Mobile
,08-30 11:37:14.050  1028  1968 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-30 11:37:14.062  7702  7702 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-30 11:37:14.068  7702  7702 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
,08-30 11:37:14.069  7702  7702 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
,08-30 11:37:14.069  7702  7702 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
,08-30 11:37:14.069  7702  7702 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-30 11:37:14.069  7702  7702 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-30 11:37:14.069  7702  7702 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-30 11:37:14.069  7702  7702 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-30 11:37:14.069  7702  7702 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-30 11:37:14.069  7702  7702 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-30 11:37:14.069  7702  7702 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-30 11:37:14.070  7702  7702 I BluetoothA2dpServiceJni: classInitNative
08-30 11:37:14.070  7702  7702 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-30 11:37:14.070  7702  7702 D A2dpStateMachine: make
,08-30 11:37:14.074  7702  7702 I bluedroid-qcom: get_profile_interface a2dp
08-30 11:37:14.074  7702  7963 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,08-30 11:37:14.077  7702  7702 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-30 11:37:14.077  7702  7702 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-30 11:37:14.079  7702  7702 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f12ed8a
,08-30 11:37:14.080  7702  7702 I BluetoothHidServiceJni: classInitNative: succeeds
08-30 11:37:14.082  7702  7962 D A2dpStateMachine: Enter Disconnected: -2
08-30 11:37:14.086  7702  7702 D HidService: Received start request. Starting profile...
,08-30 11:37:14.087  7702  7702 I bluedroid-qcom: get_profile_interface hidhost
08-30 11:37:14.087  7702  7702 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f12ed8a
,08-30 11:37:14.088  7702  7702 I BluetoothHealthServiceJni: classInitNative: succeeds
08-30 11:37:14.091  7702  7702 D HealthService: Received start request. Starting profile...
08-30 11:37:14.095  7702  7702 I bluedroid-qcom: get_profile_interface health
08-30 11:37:14.095  7702  7702 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-30 11:37:14.096  7702  7702 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f12ed8a
08-30 11:37:14.097  7702  7702 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-30 11:37:14.099  7702  7702 D PanService: Received start request. Starting profile...
08-30 11:37:14.099  7702  7702 D BluetoothPanServiceJni: initializeNative(L110): pan
08-30 11:37:14.099  7702  7702 I bluedroid-qcom: get_profile_interface pan
,08-30 11:37:14.107  7702  7702 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-30 11:37:14.107  7702  7702 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f12ed8a
08-30 11:37:14.108  7702  7702 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
,08-30 11:37:14.115  7702  7702 D BtGatt.DebugUtils: handleDebugAction() action=null
08-30 11:37:14.115  7702  7702 D BtGatt.GattService: Received start request. Starting profile...
08-30 11:37:14.116  7702  7702 D BtGatt.GattService: start()
08-30 11:37:14.116  7702  7702 I bluedroid-qcom: get_profile_interface gatt
08-30 11:37:14.116  7702  7702 D BtGatt.AdvertiseManager: advertise manager created
08-30 11:37:14.127  7702  7702 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f12ed8a
,08-30 11:37:14.129  7702  7702 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f12ed8a
08-30 11:37:14.129  7702  7702 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-30 11:37:14.131  7702  7702 V BluetoothMapService: BluetoothMapBinder()
08-30 11:37:14.132  7702  7702 D BluetoothMapService: Received start request. Starting profile...
08-30 11:37:14.132  7702  7702 D BluetoothMapService: start()
08-30 11:37:14.135  7702  7702 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-30 11:37:14.135  7702  7702 D BluetoothMapEmailAppObserver: createReceiver()
08-30 11:37:14.137  7702  7702 D BluetoothMapEmailAppObserver: initObservers()
08-30 11:37:14.137  7702  7702 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-30 11:37:14.148  7702  7702 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f12ed8a
,08-30 11:37:14.149  7702  7702 D HeadsetStateMachine: Proxy object connected
08-30 11:37:14.150  7702  7702 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
,08-30 11:37:14.150  7702  7702 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-30 11:37:14.157  7702  7702 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-30 11:37:14.158  7702  7951 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-30 11:37:14.159  7702  7951 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-30 11:37:14.160  7702  7951 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-30 11:37:14.164  7702  7702 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-30 11:37:14.171  7702  7702 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-30 11:37:14.177  7702  7702 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-30 11:37:14.181  7702  7702 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-30 11:37:14.182  7702  7702 V PanService: [BTUI] SIM Extra State :ABSENT
08-30 11:37:14.185  7702  7702 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-30 11:37:14.189  7702  7702 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-30 11:37:14.189  7702  7702 V BluetoothMapService: Handler(): got msg=1
08-30 11:37:14.190  7702  7702 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-30 11:37:14.190  7702  7702 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-30 11:37:14.190  7702  7702 V BluetoothSapReceiver: SapReceiver onReceive 
08-30 11:37:14.190  7702  7702 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 11:37:14.190  7702  7944 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-30 11:37:14.190  7702  7702 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-30 11:37:14.190  7702  7944 I bluedroid-qcom: enable
08-30 11:37:14.190  7702  7944 I bt_hci_bdroid: init
08-30 11:37:14.193  7702  7944 I bt_vendor: bt-vendor : init
08-30 11:37:14.193  7702  7944 I bt_vendor: bt-vendor : get_bt_soc_type
08-30 11:37:14.193  7702  7944 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-30 11:37:14.193  7702  7944 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-30 11:37:14.193  7702  7944 D bt_userial_mct: userial_init
,08-30 11:37:14.195  7702  7970 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-30 11:37:14.195  7702  7970 I bt-btu  : btu_task pending for preload complete event
08-30 11:37:14.200  7702  7944 D bt_hci_bdroid: set_power 1
08-30 11:37:14.200  7702  7944 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-30 11:37:14.200  7702  7944 I bt_vendor: Starting hciattach daemon
08-30 11:37:14.200  7702  7944 I bt_vendor: try to set true
08-30 11:37:14.187  7973  7973 W sh      : type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6837 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 11:37:14.187  7973  7973 W sh      : type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6837 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-30 11:37:14.227  7974  7974 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-30 11:37:14.324  7980  7980 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-30 11:37:14.337  7981  7981 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
08-30 11:37:14.362  7983  7983 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-30 11:37:14.387  7984  7984 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-30 11:37:14.399  7985  7985 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-30 11:37:14.412  7986  7986 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-30 11:37:14.433  7988  7988 I libmdmdetect: ESOC framework not supported
,08-30 11:37:14.434  7988  7988 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-30 11:37:14.440  7988  7988 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
,08-30 11:37:14.441  7988  7988 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
,08-30 11:37:14.441  7988  7988 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-30 11:37:14.441  7988  7988 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
,08-30 11:37:14.441  7988  7988 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-30 11:37:14.441  7988  7988 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-30 11:37:14.441  7988  7988 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-30 11:37:14.477  7988  7989 E QC-QMI  : qmi_client [7988] 15: failed to locate client data
08-30 11:37:14.478   464   464 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-30 11:37:14.478   464   464 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
,08-30 11:37:14.500  1595  1595 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
,08-30 11:37:14.500  1595  1595 I [SystemUI]LGPowerUI: On Skip Timer : true
,08-30 11:37:14.516  7990  7990 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-30 11:37:14.526  1595  1595 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 292
08-30 11:37:14.526  1028  1433 D WifiController: battery changed pluggedType: 2
08-30 11:37:14.529  7991  7991 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
08-30 11:37:14.529  1933  2090 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-30 11:37:14.529  1933  2090 D LEDHandler: Battery Level Remaining: 100%
08-30 11:37:14.529  1933  2090 D LEDHandler: Battery Temp: 292, mChargingStatus=5, mChargingStop=false
08-30 11:37:14.529  1595  1595 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
,08-30 11:37:14.534  7702  7951 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-30 11:37:14.543  1595  1595 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-30 11:37:14.555  7702  7944 I bt_vendor: bluetooth satus is on
08-30 11:37:14.555  7702  7944 D bt_hci_bdroid: preload
08-30 11:37:14.556  7702  7972 D bt_userial_mct: userial_open(port:0)
,08-30 11:37:14.556  7702  7972 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
08-30 11:37:14.559  7702  7972 I bt_vendor: Done intiailizing UART
08-30 11:37:14.560  7702  7972 I bt_vendor: Done intiailizing UART
08-30 11:37:14.560  7702  7972 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-30 11:37:14.560  7702  7972 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-30 11:37:14.560  7702  7993 D bt_userial_mct: Entering userial_read_thread()
08-30 11:37:14.560  7702  7970 I bt-btu  : btu_task received preload complete event
08-30 11:37:14.561  7702  7970 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-30 11:37:14.561  7702  7970 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-30 11:37:14.563  7702  7970 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-30 11:37:14.566  7702  7970 I         : BTE_InitTraceLevels -- TRC_HCI
08-30 11:37:14.566  7702  7970 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-30 11:37:14.566  7702  7970 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-30 11:37:14.566  7702  7970 I         : BTE_InitTraceLevels -- TRC_AVDT
08-30 11:37:14.567  7702  7970 I         : BTE_InitTraceLevels -- TRC_AVRC
08-30 11:37:14.567  7702  7970 I         : BTE_InitTraceLevels -- TRC_A2D
08-30 11:37:14.567  7702  7970 I         : BTE_InitTraceLevels -- TRC_BNEP
08-30 11:37:14.567  7702  7970 I         : BTE_InitTraceLevels -- TRC_BTM
08-30 11:37:14.567  7702  7970 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-30 11:37:14.567  7702  7970 I         : BTE_InitTraceLevels -- TRC_GAP
08-30 11:37:14.567  7702  7970 I         : BTE_InitTraceLevels -- TRC_PAN
08-30 11:37:14.567  7702  7970 I         : BTE_InitTraceLevels -- TRC_SDP
08-30 11:37:14.567  7702  7970 I         : BTE_InitTraceLevels -- TRC_GATT
08-30 11:37:14.567  7702  7970 I         : BTE_InitTraceLevels -- TRC_SMP
08-30 11:37:14.567  7702  7970 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-30 11:37:14.567  7702  7970 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-30 11:37:14.661  7702  7970 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
,08-30 11:37:14.661  7702  7970 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa014e061 
,08-30 11:37:14.662  7702  7970 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa014e061 
,08-30 11:37:14.706  7702  7948 E bt-btif : Calling BTA_HhEnable
,08-30 11:37:14.706  7702  7948 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-30 11:37:14.706  7702  7970 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
,08-30 11:37:14.706  7702  7970 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-30 11:37:14.706  7702  7970 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-30 11:37:14.707  7702  7948 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-30 11:37:14.707  7702  7970 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-30 11:37:14.707  7702  7970 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-30 11:37:14.712  7702  7948 D BluetoothAdapterProperties: Name is: G3
,08-30 11:37:14.717  1028  1028 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-30 11:37:14.718  1028  1028 D BluetoothManagerService: Stored Bluetooth name: G3
08-30 11:37:14.719  7702  7948 D BluetoothAdapterProperties: Scan Mode:20
08-30 11:37:14.719  7702  7948 D BluetoothAdapterProperties: Discoverable Timeout:120
08-30 11:37:14.720  7702  7948 D bt_hci_bdroid: postload
08-30 11:37:14.724  6540  6540 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 11:37:14.726  7702  7948 D bte_conf: Device ID record 1 : primary
08-30 11:37:14.726  7702  7948 D bte_conf:   vendorId            = 00c4
08-30 11:37:14.727  7702  7948 D bte_conf:   vendorIdSource      = 0001
08-30 11:37:14.727  7702  7948 D bte_conf:   product             = 13a1
08-30 11:37:14.727  7702  7948 D bte_conf:   version             = 1000
08-30 11:37:14.727  7702  7948 D bte_conf:   clientExecutableURL = 
08-30 11:37:14.727  7702  7948 D bte_conf:   serviceDescription  = 
08-30 11:37:14.727  7702  7948 D bte_conf:   documentationURL    = 
08-30 11:37:14.727  7702  7948 D bte_conf: bte_load_did_conf no section named DID2.
,08-30 11:37:14.730  7702  7993 E bt_mct  : hci lib postload completed
08-30 11:37:14.730  7702  7944 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-30 11:37:14.730  7702  7944 D BluetoothAdapterProperties: ScanMode =  20
08-30 11:37:14.730  7702  7944 D BluetoothAdapterProperties: State =  11
08-30 11:37:14.731  7702  7944 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
,08-30 11:37:14.731  7702  7944 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-30 11:37:14.731  7702  7944 D BluetoothAdapterProperties: Setting state to 12
08-30 11:37:14.731  7702  7944 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-30 11:37:14.731  7702  7948 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-30 11:37:14.732  7702  7944 I BluetoothAdapterState: Entering On State
08-30 11:37:14.733  7702  7970 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-30 11:37:14.735  1028  1110 D BluetoothManagerService: Message: 60
08-30 11:37:14.735  1028  1110 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-30 11:37:14.735  1028  1110 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
08-30 11:37:14.736  7702  7944 D LGBluetoothServiceAdapter: [BTUI] OnState
08-30 11:37:14.736  7702  7944 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-30 11:37:14.736  7702  7944 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-30 11:37:14.727  7995  7995 W sh      : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6837 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 11:37:14.727  7995  7995 W sh      : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6837 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-30 11:37:14.745  7702  7944 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-30 11:37:14.745  6767  6787 D BluetoothA2dp: onBluetoothStateChange: up=true
08-30 11:37:14.751  1028  1110 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-30 11:37:14.752  1028  1028 D BluetoothA2dp: Proxy object connected
08-30 11:37:14.754  1843  1859 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 11:37:14.759  6767  6767 D BluetoothA2dp: Proxy object connected
08-30 11:37:14.759  6767  6767 D A2dpProfile: Bluetooth service connected
08-30 11:37:14.760  7702  7970 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-30 11:37:14.760  7702  7970 W bt-smp  : Plain text(LSB ~ MSB) = 41 4a 6f 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-30 11:37:14.760  7702  7970 W bt-smp  : Encrypted text(LSB ~ MSB) = 2e 50 18 a4 c8 e0 c2 1e 6e 86 07 64 d2 ad 50 d8 
08-30 11:37:14.760  7702  7970 W bt-btm  : Stopping oneshot timer
08-30 11:37:14.767  6767  6786 D BluetoothMap: onBluetoothStateChange: up=true
,08-30 11:37:14.778  1843  1843 D BluetoothHeadset: Proxy object connected
08-30 11:37:14.779  6767  7955 D BluetoothPan: onBluetoothStateChange on: true
08-30 11:37:14.779  6767  7955 D BluetoothPan: onBluetoothStateChange call bindService
,08-30 11:37:14.782  7702  7944 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-30 11:37:14.785  7702  7948 D BluetoothAdapterProperties: Discoverable Timeout:120
08-30 11:37:14.785  7702  7948 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-30 11:37:14.785  7702  7948 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-30 11:37:14.785  6767  6767 D BluetoothMap: Proxy object connected
08-30 11:37:14.785  6767  6767 D MapProfile: Bluetooth service connected
08-30 11:37:14.785  6767  6767 D BluetoothMap: getConnectedDevices()
08-30 11:37:14.786  7702  8002 V BluetoothMapService: getConnectedDevices()
08-30 11:37:14.792  7702  7970 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-30 11:37:14.792  7702  7970 W bt-smp  : Plain text(LSB ~ MSB) = a0 a1 6a 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-30 11:37:14.792  7702  7970 W bt-smp  : Encrypted text(LSB ~ MSB) = 57 41 f9 bc 0c 8c 32 b3 90 62 6f 28 e4 25 49 25 
08-30 11:37:14.792  7702  7970 W bt-btm  : Stopping oneshot timer
,08-30 11:37:14.797  6767  6767 D BluetoothPan: BluetoothPAN Proxy object connected
,08-30 11:37:14.797  6767  6767 D PanProfile: Bluetooth service connected
08-30 11:37:14.799  1843  4011 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 11:37:14.801  1843  1843 D BluetoothHeadset: Proxy object connected
08-30 11:37:14.801  6767  6786 D BluetoothPbap: onBluetoothStateChange: up=true
08-30 11:37:14.805  1028  1110 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 11:37:14.806  1028  1028 D BluetoothHeadset: Proxy object connected
08-30 11:37:14.808  6767  7593 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 11:37:14.810  7702  7970 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
,08-30 11:37:14.810  7702  7970 W bt-smp  : Plain text(LSB ~ MSB) = 0b 63 73 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-30 11:37:14.810  7702  7970 W bt-smp  : Encrypted text(LSB ~ MSB) = 6c 7e 95 ee be ac 02 69 5c 33 cd 0a 66 9c 6d 66 
08-30 11:37:14.810  7702  7970 W bt-btm  : Stopping oneshot timer
08-30 11:37:14.810  6767  6767 D BluetoothHeadset: Proxy object connected
08-30 11:37:14.810  6767  6767 D HeadsetProfile: Bluetooth service connected
08-30 11:37:14.811  6767  7955 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-30 11:37:14.812  8011  8011 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-30 11:37:14.813  1843  2414 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 11:37:14.813  6767  6767 D BluetoothInputDevice: Proxy object connected
08-30 11:37:14.813  6767  6767 D HidProfile: Bluetooth service connected
08-30 11:37:14.815  1843  1843 D BluetoothHeadset: Proxy object connected
08-30 11:37:14.815  1028  1110 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-30 11:37:14.815  1028  1110 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-30 11:37:14.816  1933  1933 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-30 11:37:14.817  1933  2123 D LGBluetoothAPIService: Message: 1
08-30 11:37:14.817  1933  2123 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-30 11:37:14.817  1933  2123 D LGBluetoothAPIService: Calling onBluetoothServiceUp callbacks
08-30 11:37:14.817  1933  2123 D LGBluetoothAPIService: Broadcasting onBluetoothServiceUp() to 0 receivers.
08-30 11:37:14.817  1595  1595 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-30 11:37:14.819  7702  7970 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-30 11:37:14.820  7702  7970 W bt-smp  : Plain text(LSB ~ MSB) = ef d2 5e 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-30 11:37:14.820  7702  7970 W bt-smp  : Encrypted text(LSB ~ MSB) = 93 98 c8 d3 2f 89 22 d7 55 bc 17 78 37 0c 73 42 
08-30 11:37:14.820  7702  7970 W bt-btm  : Stopping oneshot timer
08-30 11:37:14.822  1028  1028 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
,08-30 11:37:14.823  1028  1110 D BluetoothManagerService: Message: 40
08-30 11:37:14.823  1028  1110 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-30 11:37:14.824  6540  6540 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 11:37:14.824  6540  6540 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 11:37:14.824  6540  6540 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 11:37:14.824  6540  6540 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 11:37:14.824  6540  6540 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 11:37:14.824  6540  6540 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 11:37:14.824  6540  6540 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 11:37:14.824  6540  6540 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 11:37:14.825  6540  6540 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 11:37:14.827  7702  7702 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-30 11:37:14.827  7702  7702 D BluetoothMapService: STATE_ON
08-30 11:37:14.828  6767  6767 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-30 11:37:14.830  6767  6767 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-30 11:37:14.832  7702  7970 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-30 11:37:14.832  7702  7970 W bt-smp  : Plain text(LSB ~ MSB) = fb 34 46 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-30 11:37:14.832  7702  7970 W bt-smp  : Encrypted text(LSB ~ MSB) = 08 fa 38 b3 0c bb d2 01 76 0e 6f 1f fc 60 fd 72 
08-30 11:37:14.832  7702  7970 W bt-btm  : Stopping oneshot timer
08-30 11:37:14.835  7702  7702 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f12ed8a
08-30 11:37:14.835  7702  7702 V BluetoothPbapService: Pbap Service onCreate
08-30 11:37:14.835  7702  7702 V BluetoothPbapService: Starting PBAP service
,08-30 11:37:14.836  7702  7702 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-30 11:37:14.836  7702  7702 V BluetoothMapService: Handler(): got msg=1
08-30 11:37:14.837  7702  7702 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-30 11:37:14.838  7702  7702 V BluetoothPbapService: Pbap Service onBind
08-30 11:37:14.839  7702  8014 D BluetoothMapMasInstance: MAS initSocket()
08-30 11:37:14.839  7702  8014 D BluetoothMapMasInstance:   masId = 00
08-30 11:37:14.839  7702  8014 D BluetoothMapMasInstance:   msgTypes = 0e
08-30 11:37:14.839  7702  8014 D BluetoothMapMasInstance:   masName = SMS/MMS
08-30 11:37:14.839  7702  8014 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-30 11:37:14.839  6767  6767 D DockEventReceiver: finishStartingService: stopping service
08-30 11:37:14.839  7702  7702 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 11:37:14.839  7702  7702 V BluetoothPbapService: state: 12
08-30 11:37:14.840  7702  7702 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-30 11:37:14.840  6767  6767 D BluetoothPbap: Proxy object connected
08-30 11:37:14.840  6767  6767 D PbapServerProfile: Bluetooth service connected
08-30 11:37:14.840  7702  7702 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 11:37:14.840  7702  7702 V BluetoothPbapReceiver: ***********state = 12
08-30 11:37:14.841  7702  7702 V BluetoothPbapService: Handler(): got msg=1
08-30 11:37:14.841  7702  7702 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-30 11:37:14.842  7702  8015 V BluetoothPbapService: Pbap Service initSocket
08-30 11:37:14.843  1028  1914 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 11:37:14.843  1028  1044 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 11:37:14.843  7702  8014 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 11:37:14.844  7702  8015 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 11:37:14.845  2195  2195 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-30 11:37:14.845  2195  2195 D c       : Getting all permits...
08-30 11:37:14.845  2195  2195 D a       : Opening database...
08-30 11:37:14.847  7702  8014 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-30 11:37:14.847  7702  8014 V BluetoothMapMasInstance: Succeed to create listening socket 
08-30 11:37:14.847  7702  8014 D BluetoothMapMasInstance: Accepting socket connection...
08-30 11:37:14.848  7702  8015 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-30 11:37:14.848  7702  8015 V BluetoothPbapService: Succeed to create listening socket 
08-30 11:37:14.848  7702  8015 V BluetoothPbapService: Accepting socket connection...
08-30 11:37:14.848  2195  2195 D a       : Opening database auth.proximity.permit_store...
,08-30 11:37:14.849  7702  7948 D BluetoothAdapterProperties: Scan Mode:21
08-30 11:37:14.849  7702  7948 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-30 11:37:14.850  2195  2195 D a       : Closing database...
08-30 11:37:14.853  6540  6540 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 11:37:14.858  6767  6767 D BluetoothPermissionRequest: onReceive
,08-30 11:37:14.859  6767  6767 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-30 11:37:14.860  6767  6767 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-30 11:37:14.861  7702  7702 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
,08-30 11:37:14.862  7702  7702 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-30 11:37:14.868  7702  7702 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
08-30 11:37:14.890  7702  7702 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,08-30 11:37:14.891  7702  7702 V BtOppService: onCreate
08-30 11:37:14.895  7702  7702 V BluetoothOppNotification: send message
08-30 11:37:14.899  7702  7702 V BtOppService: Starting RfcommListener
08-30 11:37:14.905  7702  7702 D BluetoothOppPreference: Dumping Names:  
,08-30 11:37:14.905  7702  7702 D BluetoothOppPreference: {}
08-30 11:37:14.905  7702  7702 D BluetoothOppPreference: Dumping Channels:  
08-30 11:37:14.905  7702  7702 D BluetoothOppPreference: {}
08-30 11:37:14.906  7702  7702 V BtOppService: onStartCommand
08-30 11:37:14.909  7702  8022 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-30 11:37:14.911  7702  7702 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-30 11:37:14.911  7702  7702 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-30 11:37:14.914  7702  7702 V BluetoothOppNotification: new notify threadi!
08-30 11:37:14.915  7702  7702 V BluetoothOppNotification: send delay message
08-30 11:37:14.915  7702  7702 V BtOppService: start RfcommListener
08-30 11:37:14.918  7702  7702 V BtOppService: RfcommListener started
,08-30 11:37:14.924  7702  8022 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
,08-30 11:37:14.925  7702  8019 V BtOppService: Deleted complete outbound shares, number =  0
08-30 11:37:14.926  7702  8023 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-30 11:37:14.928  7702  8022 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3074fc66 on behalf of 
08-30 11:37:14.928  7702  8024 V BtOppRfcommListener: Starting RFCOMM listener....
,08-30 11:37:14.929  1028  1878 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 11:37:14.929  7702  8019 V BtOppService: Deleted complete inbound failed shares, number = 0
08-30 11:37:14.930  7702  8019 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-30 11:37:14.931  7702  8024 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 11:37:14.933  7702  8024 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=79 mFd=75
08-30 11:37:14.933  7702  8023 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@239abba7 on behalf of 
08-30 11:37:14.935  7702  8024 V BtOppRfcommListener: Started RFCOMM listener....
08-30 11:37:14.935  7702  8024 I BtOppRfcommListener: Accept thread started.
08-30 11:37:14.935  7702  7702 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f12ed8a
08-30 11:37:14.935  7702  8024 V BtOppRfcommListener: Accepting connection...
08-30 11:37:14.935  7702  7702 V BluetoothFtpService: Ftp Service onCreate
08-30 11:37:14.935  7702  7702 I BluetoothFtpService: Ftp Service onCreate
08-30 11:37:14.935  7702  8019 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@10e383fd on behalf of 
08-30 11:37:14.935  7702  7702 V BluetoothFtpService: Ftp Service onStartCommand
,08-30 11:37:14.936  7702  7702 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 11:37:14.936  7702  7702 V BluetoothFtpService: Starting Listening on sockets
08-30 11:37:14.936  7702  7702 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-30 11:37:14.936  7702  7702 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-30 11:37:14.936  7702  7702 V BluetoothSapReceiver: SapReceiver onReceive 
08-30 11:37:14.936  7702  7702 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 11:37:14.936  7702  7702 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-30 11:37:14.936  7702  7702 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-30 11:37:14.939  7702  7702 V BtOppService: ContentObserver received notification
08-30 11:37:14.939  7702  7702 V BtOppService: ContentObserver received notification
08-30 11:37:14.939  7702  7702 V BluetoothFtpService: Handler(): got msg=1
08-30 11:37:14.940  7702  8022 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-30 11:37:14.940  7702  8022 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-30 11:37:14.941  7702  7702 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-30 11:37:14.941  7702  7702 V BluetoothFtpService: Ftp Service initSocket
08-30 11:37:14.944  7702  8023 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-30 11:37:14.946  7702  8022 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@15c478f2 on behalf of 
08-30 11:37:14.947  1028  1877 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 11:37:14.947  7702  8022 V BluetoothOppNotification: update too frequent, put in queue
08-30 11:37:14.948  7702  7702 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 11:37:14.948  7702  8023 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-30 11:37:14.949  7702  8023 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1ead6b43 on behalf of 
08-30 11:37:14.950  7702  8022 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-30 11:37:14.950  7702  8023 V BluetoothOppNotification: outbound: succ-0  fail-0
,08-30 11:37:14.952  7702  7702 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=81 mFd=79
08-30 11:37:14.953  7702  7702 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-30 11:37:14.955  7702  8023 V BluetoothOppNotification: outbound notification was removed.
08-30 11:37:14.955  7702  8023 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-30 11:37:14.956  7702  8025 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-30 11:37:14.957  7702  8023 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1f5745c0 on behalf of 
08-30 11:37:14.958  7702  8023 V BluetoothOppNotification: inbound: succ-0  fail-0
08-30 11:37:14.959  7702  8023 V BluetoothOppNotification: inbound notification was removed.
08-30 11:37:14.959  7702  8023 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-30 11:37:14.961  7702  8023 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@21e962f9 on behalf of 
08-30 11:37:14.980  7702  7702 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f12ed8a
,08-30 11:37:14.980  7702  7702 V BluetoothSapService: Sap Service onCreate
08-30 11:37:14.982  7702  7702 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 11:37:14.982  7702  7702 V BluetoothSapService: state: 12
08-30 11:37:14.982  7702  7702 V BluetoothSapService: Starting SAP server process
08-30 11:37:14.984  7702  7702 V BluetoothSapService: SAP Service startRfcommListenerThread
08-30 11:37:14.977  8026  8026 W sapd    : type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6837 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 11:37:14.986  7702  8027 V BluetoothSapService: Sap Service initRfcommSocket
08-30 11:37:14.977  8026  8026 W sapd    : type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6837 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 11:37:14.986  1028  2024 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 11:37:14.987  7702  8027 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 11:37:14.988  7702  8027 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=81
08-30 11:37:14.988  7702  8027 V BluetoothSapService: Succeed to create listening socket 
08-30 11:37:14.988  7702  8027 V BluetoothSapService: Accepting socket connection...
08-30 11:37:15.002  8026  8026 V BT_SAP  : Event pipe created
08-30 11:37:15.002  8026  8026 V BT_SAP  : create_server_socket qcom.sap.server
08-30 11:37:15.002  8026  8026 V BT_SAP  : created socket fd 6
,08-30 11:37:15.591  6540  6656 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 11:37:15.591  6540  6656 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 11:37:15.591  6540  6656 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 11:37:15.591  6540  6656 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 11:37:15.591  6540  6656 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 11:37:15.591  6540  6656 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 11:37:15.591  6540  6656 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 11:37:15.591  6540  6656 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 11:37:15.601  6540  6656 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 11:37:15.603  6540  6656 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 11:37:15.603  6540  6656 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@315552bf added. We now have 8 listener(s)
08-30 11:37:15.603  6540  6656 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 11:37:15.606  1028  1912 D WifiServiceImplEx: setWifiEnabled: false pid=6540, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-30 11:37:15.606  1028  1912 D WifiService: setWifiEnabled: false pid=6540, uid=10118
08-30 11:37:15.606  1028  1912 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-30 11:37:15.611  6540  6656 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 11:37:15.616  1028  2005 D WifiServiceImplEx: setWifiEnabled: true pid=6540, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-30 11:37:15.616  1028  2005 D WifiService: setWifiEnabled: true pid=6540, uid=10118
08-30 11:37:15.616  1028  2005 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 11:37:15.643  1028  1028 D LocationManagerService: getAllProviders()=[passive, gps, network]
,08-30 11:37:15.643  1028  1028 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
,08-30 11:37:15.643  1028  1028 D Ulp_jni : JNI:system_update. Event-4
08-30 11:37:15.645  1028  1383 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-30 11:37:15.645  1028  1383 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-30 11:37:15.648  1028  1383 E WifiUtil: wfc_util_ffile_check_copy(): pid[1028] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-30 11:37:15.648  1028  1383 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-30 11:37:15.648  1028  1383 E WifiUtil: wfc_util_ffile_check_copy(): pid[1028] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-30 11:37:15.648  1028  1383 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-30 11:37:15.648  1028  1383 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-30 11:37:15.648  1028  1383 E WifiHW  : unknown target_country: EU , set to default
08-30 11:37:15.648  1028  1383 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-30 11:37:15.648  1028  1383 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-30 11:37:15.648  1028  1383 I WifiUtil: gEnableBmps=1
08-30 11:37:15.916  7702  7702 V BluetoothOppNotification: new notify threadi!
,08-30 11:37:15.917  7702  7702 V BluetoothOppNotification: send delay message
,08-30 11:37:15.942  7702  8040 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,08-30 11:37:15.956  7702  8040 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2ed435b5 on behalf of 
08-30 11:37:15.957  7702  8040 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-30 11:37:15.974  7702  8040 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,08-30 11:37:15.987  7702  8040 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@17b6344a on behalf of 
08-30 11:37:15.988  7702  8040 V BluetoothOppNotification: outbound: succ-0  fail-0
,08-30 11:37:16.010  7702  8040 V BluetoothOppNotification: outbound notification was removed.
08-30 11:37:16.017  7702  8040 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
,08-30 11:37:16.038  7702  8040 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@17beffbb on behalf of 
,08-30 11:37:16.047  7702  8040 V BluetoothOppNotification: inbound: succ-0  fail-0
,08-30 11:37:16.056  7702  8040 V BluetoothOppNotification: inbound notification was removed.
08-30 11:37:16.056  7702  8040 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-30 11:37:16.072  7702  8040 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@13e00cd8 on behalf of 
,08-30 11:37:16.210   315   891 D SoftapController: Softap fwReload - Ok
,08-30 11:37:16.222  1028  1110 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-30 11:37:16.222  1028  1110 D Tethering: InitialState.processMessage what=4
08-30 11:37:16.223  1028  1110 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-30 11:37:16.228  6767  6767 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-30 11:37:16.228  6767  6767 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-30 11:37:16.228  6767  6767 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-30 11:37:16.228  6767  6767 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
,08-30 11:37:16.231  6767  6767 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-30 11:37:16.232  6767  6767 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-30 11:37:16.232  6767  6767 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-30 11:37:16.232  6767  6767 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-30 11:37:16.232  6767  6767 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-30 11:37:16.232  6767  6767 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-30 11:37:16.232  6767  6767 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-30 11:37:16.236  1028  1383 E NetdConnector: NDC Command {83 softap fwreload wlan0 STA} took too long (583ms)
08-30 11:37:16.239   315   891 D CommandListener: Setting iface cfg
08-30 11:37:16.239   315   891 D CommandListener: Trying to bring down wlan0
08-30 11:37:16.241   315   891 D CommandListener: Clearing all IP addresses on wlan0
,08-30 11:37:16.244  6767  6767 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-30 11:37:16.244  6767  6767 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-30 11:37:16.244  6767  6767 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-30 11:37:16.244  6767  6767 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-30 11:37:16.245  6767  6767 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-30 11:37:16.246  6767  6767 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-30 11:37:16.247  6767  6767 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-30 11:37:16.247  6767  6767 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-30 11:37:16.247  6767  6767 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-30 11:37:16.247  6767  6767 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-30 11:37:16.247  6767  6767 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-30 11:37:16.248  1028  1383 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
08-30 11:37:16.250  1028  1383 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-30 11:37:16.250  1028  1383 E WifiStateMachine: useWiFiOffloading() : false
08-30 11:37:16.250  1028  1383 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-30 11:37:16.251  1028  1383 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-30 11:37:16.251  1028  1383 D WifiMonitor: connecting to supplicant
08-30 11:37:16.252  1028  1383 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
08-30 11:37:16.237  8059  8059 W wpa_supplicant: type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6837 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-30 11:37:16.247  8059  8059 W wpa_supplicant: type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6837 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 11:37:16.256  1933  1933 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-30 11:37:16.257  1595  1595 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 11:37:16.260  6540  6540 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 11:37:16.284  8059  8059 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-30 11:37:16.309  1028  1106 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=8064 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
08-30 11:37:16.309  1028  1028 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
,08-30 11:37:16.325  8059  8059 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-30 11:37:16.326  8059  8059 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,08-30 11:37:16.384  8059  8059 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-30 11:37:16.416  8059  8059 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
08-30 11:37:16.422  8059  8059 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
,08-30 11:37:16.447  1028  1967 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=8087 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-30 11:37:16.452  8064  8085 W FormManager: Network not available. Please check & try again.
08-30 11:37:16.458  8064  8086 V FormManager: Network unavailable.
08-30 11:37:16.460  8064  8086 V FormManager: Network unavailable.
,08-30 11:37:16.466  8059  8059 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-30 11:37:16.476  1028  1567 I ActivityManager: Killing 7105:com.lge.drmservice/u0a62 (adj 15): empty #17
,08-30 11:37:16.536  1028  1877 W libprocessgroup: failed to open /acct/uid_10062/pid_7105/cgroup.procs: No such file or directory
08-30 11:37:16.600  8087  8087 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-30 11:37:16.606  6767  6767 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-30 11:37:16.616  6767  6767 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-30 11:37:16.619  1028  1877 I ActivityManager: Killing 7130:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
08-30 11:37:16.667  1028  1912 W libprocessgroup: failed to open /acct/uid_10085/pid_7130/cgroup.procs: No such file or directory
,08-30 11:37:17.108  8059  8059 E wpa_supplicant: USIM:  scard_init function
,08-30 11:37:17.109  8059  8059 I wpa_supplicant: Trying to associate with SSID 'NG700'
,08-30 11:37:17.262  8059  8059 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-30 11:37:17.287  8059  8059 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-30 11:37:17.287  8059  8059 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,08-30 11:37:17.294  1028  1110 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-30 11:37:17.303  1028  1383 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-30 11:37:17.304  1028  1383 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-30 11:37:17.304  1028  1383 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
,08-30 11:37:17.313  1028  1383 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-30 11:37:17.313  1028  1383 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-30 11:37:17.314  1028  1383 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-30 11:37:17.314  1028  1383 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-30 11:37:17.317  1028  8117 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 11:37:17.317  1028  8117 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-30 11:37:17.317  1028  8117 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-30 11:37:17.317  1028  8117 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-30 11:37:17.317  1028  8117 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-30 11:37:17.317  1028  8117 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-30 11:37:17.317  1028  8117 E WifiMonitor: WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-30 11:37:17.317  1028  8117 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-30 11:37:17.318  1028  8117 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 11:37:17.318  1028  8117 E WifiMonitor: WifiMonitor:wlan0 cnt=47 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-30 11:37:17.318  1028  1383 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-30 11:37:17.319  1028  1383 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-30 11:37:17.319  1028  1383 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-30 11:37:17.320  1028  1383 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-30 11:37:17.320  1028  1383 D WifiNative-wlan0: doString: [DRIVER MACADDR]
,08-30 11:37:17.324  1028  1383 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-30 11:37:17.324  1028  1383 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-30 11:37:17.325  1028  1383 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-30 11:37:17.326  1028  1028 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 11:37:17.326  1028  1028 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 11:37:17.326  1028  1028 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 11:37:17.326  1028  1028 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 11:37:17.326  1028  1028 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-30 11:37:17.327  1028  1383 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-30 11:37:17.327  1028  1383 E WifiStateMachine: useWiFiOffloading() : false
08-30 11:37:17.327  1028  1383 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-30 11:37:17.329  1028  1028 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-30 11:37:17.332  1028  1395 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
,08-30 11:37:17.334  1595  1595 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 11:37:17.336  1933  1933 D WfdService: Waiting for WifiP2p enabling
08-30 11:37:17.340  6540  6540 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 11:37:17.340  6540  6540 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 11:37:17.340  6540  6540 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 11:37:17.340  6540  6540 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 11:37:17.340  6540  6540 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 11:37:17.340  6540  6540 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 11:37:17.340  6540  6540 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 11:37:17.340  6540  6540 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 11:37:17.342  6540  6540 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 11:37:17.349  1028  1383 D WifiNative-wlan0: doBoolean: SET update_config 1
,08-30 11:37:17.352  1028  1383 D WifiNative-wlan0: SET update_config 1: returned true
08-30 11:37:17.352  1028  1383 D WifiConfigStore: Loading config and enabling all networks 
08-30 11:37:17.352  1028  1383 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-30 11:37:17.353  1028  1383 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	[CURRENT]
08-30 11:37:17.359  1028  1383 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-30 11:37:17.371  1028  1383 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-30 11:37:17.371  1028  1383 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-30 11:37:17.376  1028  1383 D WifiStateMachine: enableVerboseLogging : level 2
08-30 11:37:17.376  1028  1383 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-30 11:37:17.376  1028  1383 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-30 11:37:17.376  1028  1383 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-30 11:37:17.377  1028  1383 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-30 11:37:17.377  1028  1383 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-30 11:37:17.377  1028  1383 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-30 11:37:17.377  1028  1383 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-30 11:37:17.378  1028  1383 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-30 11:37:17.378  1028  1383 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-30 11:37:17.378  1028  1383 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-30 11:37:17.378  1028  1383 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-30 11:37:17.379  1028  1383 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-30 11:37:17.379  1028  1383 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-30 11:37:17.379  1028  1383 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-30 11:37:17.382  1933  1933 D WfdsService: Supplicant Connection state is changed : true
08-30 11:37:17.382  1933  2352 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-30 11:37:17.382  1933  2352 D WfdsService: Set the WFDS Monitor: true
08-30 11:37:17.382  1933  2352 D WfdsMonitor: WfdsMonitorThread create
08-30 11:37:17.383  1933  2352 D WfdsMonitor: WFDS Monitor is created and started
08-30 11:37:17.383  1933  2352 D WfdsService: WiFi: Supplicant connection re-established
,08-30 11:37:17.386  1028  1383 D WifiStateMachine: Setting OUI to DA-A1-19
08-30 11:37:17.387  1028  1383 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-30 11:37:17.388  1028  1383 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-30 11:37:17.388  1028  1383 D WifiNative-HAL: Setting external_sim to 1
08-30 11:37:17.388  1028  1383 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-30 11:37:17.389  1028  1383 D WifiNative-wlan0: SET external_sim 1: returned true
08-30 11:37:17.389  1028  1383 I WifiNative-HAL: startHal
08-30 11:37:17.389  1028  1383 D wifi    : setting scan oui 0xaf6bdbc0
08-30 11:37:17.389  1028  1383 D WifiStateMachine: Setting OUI to DA-A1-19
08-30 11:37:17.389  1028  1383 I WifiNative-HAL: startHal
08-30 11:37:17.389  1028  1383 D wifi    : setting scan oui 0xaf6bdbc0
08-30 11:37:17.390  1028  1383 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-30 11:37:17.390  1028  1383 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-30 11:37:17.390  1028  1383 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-30 11:37:17.390  8059  8059 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-30 11:37:17.391  1028  1383 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-30 11:37:17.391  1028  1383 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-30 11:37:17.391  8059  8059 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-30 11:37:17.392  1933  8118 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-30 11:37:17.393  1933  8118 E CtrlSupplicant: Succeed to open control connection
08-30 11:37:17.393  1933  8118 E CtrlSupplicant: Succeed to open monitor connection
08-30 11:37:17.394  1028  1383 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-30 11:37:17.394  1028  1383 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-30 11:37:17.394  8059  8059 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-30 11:37:17.394  1028  1383 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-30 11:37:17.394  1028  1383 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-30 11:37:17.394  8059  8059 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-30 11:37:17.395  1028  1383 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-30 11:37:17.395  1028  1383 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-30 11:37:17.395  8059  8059 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
,08-30 11:37:17.399  1028  1383 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-30 11:37:17.399  1028  1383 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-30 11:37:17.399  8059  8059 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-30 11:37:17.401  1028  1383 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-30 11:37:17.401  1028  1383 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-30 11:37:17.401  8059  8059 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-30 11:37:17.401  1933  8118 D WfdsMonitor: Supplicant connection established
08-30 11:37:17.401  1933  2352 D WfdsService: Connected to the supplicant for wfds
08-30 11:37:17.402  1028  1383 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-30 11:37:17.403  1028  1383 E WifiNative: : [138,432,532 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-30 11:37:17.403  1028  1383 D WifiNative-wlan0: doBoolean: RECONNECT
08-30 11:37:17.403  1028  1383 D WifiNative-wlan0: RECONNECT: returned true
08-30 11:37:17.403  1028  1383 D WifiNative-wlan0: doString: [STATUS]
08-30 11:37:17.404  1028  8117 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 11:37:17.404  1028  8117 E WifiMonitor: WifiMonitor:wlan0 cnt=48 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-30 11:37:17.405  1028  1383 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-30 11:37:17.405  1028  1383 D WifiNative-wlan0: doBoolean: SET ps 1
08-30 11:37:17.405  1028  1383 D WifiNative-wlan0: SET ps 1: returned true
08-30 11:37:17.406  1028  1379 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-30 11:37:17.407   315   891 D CommandListener: Setting iface cfg
08-30 11:37:17.407   315   891 D CommandListener: Trying to bring up p2p0
,08-30 11:37:17.410  1028  1379 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-30 11:37:17.411  1028  1379 D LGWifiP2pService: P2pEnablingState
08-30 11:37:17.411  1028  1379 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-30 11:37:17.411  1028  1379 D LGWifiP2pService: P2p socket connection successful
08-30 11:37:17.412  1028  1379 D LGWifiP2pService: P2pEnabledState
08-30 11:37:17.414  1933  1933 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-30 11:37:17.415  1933  1933 D WfdsService: WifiP2pState is changed : true
08-30 11:37:17.415  1933  2352 D WfdsService: Receive the WFDS_ENABLE Method
08-30 11:37:17.415  1933  2352 D WfdsService: Set the WFDS Monitor: true
08-30 11:37:17.415  1933  2352 D WfdsService: Connected to the supplicant for wfds
08-30 11:37:17.415  1933  2352 D WfdsJNI : doCommand: WFDS_SET TRUE
08-30 11:37:17.415  8059  8059 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-30 11:37:17.416  1933  2352 D WfdsService: selectPreferredScanChannel [36]
08-30 11:37:17.416  1933  2352 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-30 11:37:17.418  1028  1379 D LGWifiP2pService: sending p2p connection changed broadcast
08-30 11:37:17.421  1933  1933 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-30 11:37:17.421  1933  1933 D WfdsService: isConnected: false
,08-30 11:37:17.424  1028  1379 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-30 11:37:17.429  1028  1379 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
,08-30 11:37:17.430  1028  1379 D WifiNative-p2p0: doBoolean: SET device_name G3
08-30 11:37:17.431  1028  1379 D WifiNative-p2p0: SET device_name G3: returned true
08-30 11:37:17.431  1028  1379 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-30 11:37:17.431  1028  1379 D LGWifiP2pService: before postfix = G3
08-30 11:37:17.431  1028  1379 D WifiServerServiceExt: postfix byte check : 2
08-30 11:37:17.431  1028  1379 D LGWifiP2pService: after postfix = G3
08-30 11:37:17.431  1028  1379 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-30 11:37:17.433  1028  1379 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-30 11:37:17.433  1028  1379 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-30 11:37:17.434  1028  1379 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-30 11:37:17.434  1028  1379 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
,08-30 11:37:17.439  1028  1028 D WifiScanningService: SCAN_AVAILABLE : 3
08-30 11:37:17.439  1028  1028 D RttService: SCAN_AVAILABLE : 3
08-30 11:37:17.439  1028  1547 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-30 11:37:17.439  1028  1547 I WifiNative-HAL: startHal
08-30 11:37:17.440  1028  1548 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-30 11:37:17.441  1028  1379 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-30 11:37:17.442  1028  1379 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-30 11:37:17.442  1028  1547 D wifi    : getting scan capabilities on interface[1] = 0xaf6bdbc0
08-30 11:37:17.442  1028  1547 D wifi    : failed to get capabilities : -3
08-30 11:37:17.442  1028  1547 E WifiScanningService: could not get scan capabilities
08-30 11:37:17.443  1028  1379 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-30 11:37:17.443  1028  1379 D WifiNative-HAL: p2pGetDeviceAddress
08-30 11:37:17.443  1028  1383 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-30 11:37:17.443  1028  1379 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-30 11:37:17.444  6767  6767 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-30 11:37:17.444  6767  6767 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-30 11:37:17.444  6767  6767 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-30 11:37:17.444  1028  1379 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-30 11:37:17.444  6767  6767 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-30 11:37:17.444  1028  1379 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-30 11:37:17.445  7733  7733 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 11:37:17.445  1028  1379 D WifiNative-p2p0: P2P_FLUSH: returned true
08-30 11:37:17.445  1028  1379 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-30 11:37:17.446  1028  1379 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-30 11:37:17.446  1028  1379 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-30 11:37:17.446  1028  1379 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-30 11:37:17.446  1028  1379 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-30 11:37:17.446  6767  6767 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-30 11:37:17.447  1933  1933 I WfdStateTracker: handleP2pThisDeviceChanged
08-30 11:37:17.447  1933  1933 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-30 11:37:17.447  6767  6767 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-30 11:37:17.447  1933  1933 D WfdsService: Update P2p Interface State: 3
08-30 11:37:17.447  6767  6767 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-30 11:37:17.447  6767  6767 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-30 11:37:17.447  6767  6767 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-30 11:37:17.447  6767  6767 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-30 11:37:17.447  1028  1383 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-30 11:37:17.447  6767  6767 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-30 11:37:17.448  6767  6767 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-30 11:37:17.448  1028  1383 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-30 11:37:17.450  1028  1383 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
,08-30 11:37:17.451  1028  1383 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=138481  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-30 11:37:17.454  1028  1383 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=138484  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
,08-30 11:37:17.456  1028  1383 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=138486
,08-30 11:37:17.456  1028  1383 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=138486
08-30 11:37:17.457  1028  1383 D WifiNative-wlan0: doString: [STATUS]
08-30 11:37:17.457  1595  1595 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 11:37:17.457  1595  1595 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 11:37:17.458  1028  1028 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 11:37:17.458  1028  1028 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 11:37:17.458  1028  1028 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-30 11:37:17.459  1595  1595 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 11:37:17.459  1028  1379 D WifiNative-p2p0: SAVE_CONFIG: returned true
,08-30 11:37:17.460  1028  1379 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-30 11:37:17.461  1028  1383 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-30 11:37:17.461  1028  8117 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 11:37:17.461  1028  8117 E WifiMonitor: WifiMonitor:wlan0 cnt=49 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-30 11:37:17.462  1028  1379 D LGWifiP2pService: InactiveState
08-30 11:37:17.462  1028  1379 D LGWifiP2pService: InactiveState{ when=-16ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-30 11:37:17.463  1028  1379 D LGWifiP2pService: P2pEnabledState{ when=-17ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-30 11:37:17.463  1028  1379 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-30 11:37:17.463  1028  1383 I WifiServiceExtension: setVHTCapabilityType  : false
08-30 11:37:17.463  8059  8059 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-30 11:37:17.464  8059  8059 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 11:37:17.464  8087  8087 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-30 11:37:17.464  1028  8117 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-30 11:37:17.464  1028  8117 E WifiMonitor: WifiMonitor:p2p0 cnt=50 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 11:37:17.464  1028  8117 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 11:37:17.464  1028  8117 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 11:37:17.464  8059  8059 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-30 11:37:17.465  8059  8059 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 11:37:17.465  8059  8059 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 11:37:17.466  1028  8117 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 11:37:17.466  1028  8117 E WifiMonitor: WifiMonitor:p2p0 cnt=51 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 11:37:17.466  1028  8117 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 11:37:17.466  1028  8117 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 11:37:17.466  1028  8117 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 11:37:17.466  1028  8117 E WifiMonitor: WifiMonitor:p2p0 cnt=52 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 11:37:17.467  1028  8117 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 11:37:17.467  1028  8117 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 11:37:17.467  1028  1379 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-30 11:37:17.467  1028  1379 D LGWifiP2pService: InactiveState{ when=-5ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-30 11:37:17.467  1028  1379 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-30 11:37:17.467  6767  6767 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-30 11:37:17.467  1028  1379 D LGWifiP2pService: DefaultState{ when=-5ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-30 11:37:17.468  1933  8118 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHAN,GE init=USER type=COUNTRY alpha2=CZ]
08-30 11:37:17.468  1933  8118 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 11:37:17.468  1933  8118 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 11:37:17.469  1028  1379 D LGWifiP2pService: InactiveState{ when=-7ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-30 11:37:17.469  1028  1379 D LGWifiP2pService: P2pEnabledState{ when=-7ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-30 11:37:17.469  1028  1379 D LGWifiP2pService: DefaultState{ when=-7ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-30 11:37:17.469  1028  1379 D LGWifiP2pService: InactiveState{ when=-7ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-30 11:37:17.469  1028  1379 D LGWifiP2pService: P2pEnabledState{ when=-7ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-30 11:37:17.469  1028  1379 D LGWifiP2pService: DefaultState{ when=-7ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-30 11:37:17.469  1028  1379 D LGWifiP2pService: InactiveState{ when=-7ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-30 11:37:17.469  1028  1379 D LGWifiP2pService: P2pEnabledState{ when=-7ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-30 11:37:17.469  1028  1379 D LGWifiP2pService: DefaultState{ when=-7ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-30 11:37:17.469  1028  1028 E WifiServerServiceExt: No p2p device connected
08-30 11:37:17.471  1028  1383 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-30 11:37:17.471  1028  1383 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
08-30 11:37:17.475  1933  2352 W WfdsService: DefaultState - msg [9441285] is not handled
08-30 11:37:17.477  1028  1028 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 11:37:17.477  1028  1028 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 11:37:17.477  1028  1028 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-30 11:37:17.479  1028  1028 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 11:37:17.479  1028  1028 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 11:37:17.479  1028  1028 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-30 11:37:17.479  1595  1595 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 11:37:17.479  1595  1595 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 11:37:17.481  1028  1028 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 11:37:17.481  1028  1028 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 11:37:17.481  1028  1028 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-30 11:37:17.484  1595  1595 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 11:37:17.487  1595  1595 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 11:37:17.487  1595  1595 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 11:37:17.488  1595  1595 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 11:37:17.488  1028  1383 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-30 11:37:17.489  1028  1383 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-30 11:37:17.489  1028  1383 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-30 11:37:17.489  1595  1595 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 11:37:17.489  1595  1595 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 11:37:17.489  1028  1383 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-30 11:37:17.489  1028  1383 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-30 11:37:17.490  1595  1595 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 11:37:17.491  1028  1437 D ConnectivityService: Got NetworkAgent Messenger
08-30 11:37:17.491  1028  1437 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-30 11:37:17.491  1028  1437 D ConnectivityService: NetworkAgent connected
08-30 11:37:17.492  6767  6767 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 11:37:17.494  1028  1383 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-30 11:37:17.494  1028  1383 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-30 11:37:17.494  1028  1383 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-30 11:37:17.495  1028  1383 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-30 11:37:17.495  1028  1383 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-30 11:37:17.498  1028  1383 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-30 11:37:17.500   315   891 D CommandListener: Setting iface cfg
08-30 11:37:17.503  1028  1383 E WifiStateMachine: Start Dhcp Watchdog 3
08-30 11:37:17.504  1028  1383 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 47 0 rt=138534  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 11:37:17.504  1028  1383 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 47 0 rt=138534  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 11:37:17.505  1028  1383 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 47 0 rt=138535  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 11:37:17.505  1028  1383 E WifiStateMachine:  ObtainingIpState what:132106 1 0
08-30 11:37:17.506  1028  8140 D DhcpStateMachine: StoppedState
08-30 11:37:17.506  1028  8140 D DhcpStateMachine: StoppedState{ when=-3ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-30 11:37:17.506  1028  8140 D DhcpStateMachine: WaitBeforeStartState
08-30 11:37:17.506  1028  1383 E WifiStateMachine:  L2ConnectedState what:132106 1 0
08-30 11:37:17.507  1028  1383 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-30 11:37:17.507  1028  1383 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-30 11:37:17.507  1028  1383 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-30 11:37:17.507  8059  8059 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-30 11:37:17.508  1028  1383 E WifiStateMachine:  ObtainingIpState what:132096 -100 0
08-30 11:37:17.508  1028  1383 E WifiStateMachine:  L2ConnectedState what:132096 -100 0
08-30 11:37:17.508  1028  1383 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-30 11:37:17.509  1028  1383 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-30 11:37:17.509  1028  1383 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
,08-30 11:37:17.509  8059  8059 E wpa_supplicant: disconnect_rssi_lvl: -100
08-30 11:37:17.509  8064  8137 V FormManager: Network unavailable.
08-30 11:37:17.509  8064  8136 W FormManager: Network not available. Please check & try again.
08-30 11:37:17.510  4330  4330 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-30 11:37:17.510  4330  4330 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-30 11:37:17.511  8064  8137 V FormManager: Network unavailable.
08-30 11:37:17.511  4330  4330 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 11:37:17.512  1028  1383 E WifiStateMachine:  ObtainingIpState CMD_SET_COUNTRY_CODE 3 0 cz
08-30 11:37:17.512  1028  1383 E WifiStateMachine:  L2ConnectedState CMD_SET_COUNTRY_CODE 3 0 cz
08-30 11:37:17.512  1028  1383 E WifiStateMachine:  ObtainingIpState CMD_SET_FREQUENCY_BAND 0 0
08-30 11:37:17.513  1028  1383 E WifiStateMachine:  L2ConnectedState CMD_SET_FREQUENCY_BAND 0 0
08-30 11:37:17.513  4330  4330 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 11:37:17.513  1028  1383 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-30 11:37:17.513  1028  1383 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-30 11:37:17.514  1028  1383 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-30 11:37:17.514  8059  8059 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-30 11:37:17.514  8059  8059 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-30 11:37:17.514  1028  8117 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-30 11:37:17.514  1028  8117 E WifiMonitor: WifiMonitor:wlan0 cnt=53 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-30 11:37:17.514  1028  8117 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-30 11:37:17.514  1028  8117 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-30 11:37:17.515  1028  1383 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-30 11:37:17.515  1028  1383 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-30 11:37:17.516  1028  1383 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-30 11:37:17.516  1028  1383 D WifiNative-wlan0: doBoolean: SCAN
08-30 11:37:17.516  8059  8059 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-30 11:37:17.516  1028  8117 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-30 11:37:17.516  1028  8117 E WifiMonitor: WifiMonitor:wlan0 cnt=54 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-30 11:37:17.516  1028  8117 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-30 11:37:17.516  1028  8117 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-30 11:37:17.517  1028  1383 D WifiNative-wlan0: SCAN: returned true
08-30 11:37:17.517  1028  1383 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 48 0 rt=138547  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 11:37:17.517  4330  8142 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-30 11:37:17.518  4330  8143 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-30 11:37:17.518  4330  8143 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-30 11:37:17.519  1028  1383 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 48 0 rt=138549  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 11:37:17.519  1028  1383 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 48 0 rt=138549  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 11:37:17.520  1028  1383 E WifiStateMachine:  ObtainingIpState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 11:37:17.520  1028  1383 E WifiStateMachine:  L2ConnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 11:37:17.521  1028  1383 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 11:37:17.521  1028  1383 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 11:37:17.521  1028  1383 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 11:37:17.522  1028  1383 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
,08-30 11:37:17.570  1028  2005 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=8144 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-30 11:37:17.575  1028  1383 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 49 0 rt=138605  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 11:37:17.577  1028  1383 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 49 0 rt=138606  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 11:37:17.577  1028  1028 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 11:37:17.578  1028  1028 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-30 11:37:17.579  1028  1383 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 49 0 rt=138608  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 11:37:17.582  1028  1383 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:14080] from screen [on:0 period:-623944946] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-30 11:37:17.585  1028  1383 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-623944943] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-30 11:37:17.585  1028  1383 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-30 11:37:17.619  1595  1595 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 11:37:17.620  1028  1437 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,08-30 11:37:17.620  1028  1383 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 11:37:17.621  1028  1383 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 11:37:17.621  1028  1383 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 11:37:17.622  1028  1383 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 11:37:17.623  1028  1383 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 11:37:17.623  1028  1383 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 11:37:17.624  1028  1437 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-30 11:37:17.624  1028  1028 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 11:37:17.624  1028  1383 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=137,0,0
08-30 11:37:17.624  1028  1028 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-30 11:37:17.625  1028  1383 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=137,0,0
08-30 11:37:17.625  1028  1383 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-30 11:37:17.626  8059  8059 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-30 11:37:17.630  1028  1383 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-30 11:37:17.631  1028  1383 D WifiNative-wlan0: doBoolean: SET ps 0
,08-30 11:37:17.632  1028  1383 D WifiNative-wlan0: SET ps 0: returned true
08-30 11:37:17.632  1028  1383 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-30 11:37:17.633  8059  8059 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-30 11:37:17.634  1028  8117 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-30 11:37:17.635  1028  1383 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-30 11:37:17.635  1028  8117 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-30 11:37:17.635  1028  1383 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-30 11:37:17.635  1028  1383 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-30 11:37:17.635  1028  1379 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@de391cc target=com.android.internal.util.StateMachine$SmHandler }
08-30 11:37:17.635  1028  1383 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-30 11:37:17.635  1028  1379 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@de391cc target=com.android.internal.util.StateMachine$SmHandler }
08-30 11:37:17.636  1933  8118 D WfdsMonitor: Event [CTRL-EVENT-SCAN-RESULTS ]
08-30 11:37:17.636  1933  8118 D WfdsMonitor: Event [WPS-AP-AVAILABLE ]
,08-30 11:37:17.636  1028  8117 E WifiMonitor: WifiMonitor:p2p0 cnt=56 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
,08-30 11:37:17.636  1028  8117 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-30 11:37:17.636  1028  8140 D DhcpStateMachine: WaitBeforeStartState{ when=-1ms what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-30 11:37:17.636  1028  8140 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-30 11:37:17.636  1028  8117 D WifiMonitor: Event [IFNAME=p2p0 WPS-AP-AVAILABLE ]
08-30 11:37:17.636  1028  8117 E WifiMonitor: WifiMonitor:p2p0 cnt=57 dispatchEvent: WPS-AP-AVAILABLE 
08-30 11:37:17.636   315   891 D CommandListener: Setting iface cfg
08-30 11:37:17.636  1028  8117 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-30 11:37:17.636   315   891 D CommandListener: Trying to bring up wlan0
08-30 11:37:17.637  1028  1379 D LGWifiP2pService: InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
08-30 11:37:17.637  1028  1379 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
08-30 11:37:17.637  1028  1379 D LGWifiP2pService: DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
08-30 11:37:17.637  1028  1383 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-30 11:37:17.638  1028  1028 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 11:37:17.638  1028  1028 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-30 11:37:17.639  1028  1028 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 11:37:17.639  1028  1028 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-30 11:37:17.639  1028  1383 E WifiStateMachine:  ObtainingIpState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
08-30 11:37:17.640  1028  1383 E WifiStateMachine:  L2ConnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
08-30 11:37:17.641  1028  1383 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
08-30 11:37:17.641  1028  1383 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
08-30 11:37:17.641  1028  1383 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
08-30 11:37:17.641  1028  1383 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-30 11:37:17.647  1028  1383 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 11:37:17.648  1028  1383 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 11:37:17.648  1028  1383 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 11:37:17.649  1028  1383 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 11:37:17.649  1028  1383 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 11:37:17.650  1028  1383 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 11:37:17.650  1028  1437 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-30 11:37:17.650  1028  1383 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-30 11:37:17.651  1028  1383 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-30 11:37:17.651  1028  1379 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 11:37:17.651  1028  1379 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 11:37:17.651  1028  1383 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-30 11:37:17.651  8059  8059 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-30 11:37:17.652  1028  1383 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-30 11:37:17.652  1028  1383 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-,30 11:37:17.652  8059  8059 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-30 11:37:17.652  1028  1383 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-30 11:37:17.652  1028  1383 D WifiNative-wlan0: doBoolean: SET ps 1
,08-30 11:37:17.661  6540  6656 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
,08-30 11:37:17.661  6540  6656 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 11:37:17.661  6540  6656 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 11:37:17.661  6540  6656 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 11:37:17.661  6540  6656 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 11:37:17.661  6540  6656 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 11:37:17.661  6540  6656 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 11:37:17.661  6540  6656 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 11:37:17.663  6540  6656 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 11:37:17.668  6540  6656 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-30 11:37:17.669  6540  6656 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-30 11:37:17.669  1028  1383 D WifiNative-wlan0: SET ps 1: returned true
08-30 11:37:17.669  1028  1437 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-30 11:37:17.670  1028  1383 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-30 11:37:17.670  1028  1383 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-30 11:37:17.670  1028  1383 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
,08-30 11:37:17.671  6540  6656 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@bc2fea9 Bundle[{}]
08-30 11:37:17.671  1028  1437 D ConnectivityService: ignoring duplicate network state non-change
08-30 11:37:17.672  6540  6656 I io.jxcore.node.LifeCycleMonitor: start: OK
08-30 11:37:17.672  6540  6656 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-30 11:37:17.673  6540  6656 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-30 11:37:17.674  6540  6656 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-30 11:37:17.675  1028  1028 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 11:37:17.675  1595  1595 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 11:37:17.675  1595  1595 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 11:37:17.675  1028  1028 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 11:37:17.675  1028  1028 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-30 11:37:17.676  6540  6656 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-30 11:37:17.676  6540  6656 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-30 11:37:17.677  1595  1595 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 11:37:17.681  1028  1437 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-30 11:37:17.682  1028  1437 D ConnectivityService: Adding iface wlan0 to network 102
08-30 11:37:17.683  1028  1028 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 11:37:17.683  1028  1028 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 11:37:17.683  1028  1028 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-30 11:37:17.687  6540  6656 I System.out: Running OutgoingSocketThread
08-30 11:37:17.687  1028  1028 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-30 11:37:17.690  6540  8162 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 846)
08-30 11:37:17.690  1933  1933 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-30 11:37:17.691  6540  8162 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 45420
08-30 11:37:17.691  6540  8162 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
08-30 11:37:17.694  1028  1028 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 11:37:17.694  1028  1028 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 11:37:17.694  1028  1028 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-30 11:37:17.698  1028  1383 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-30 11:37:17.699  1595  1595 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 11:37:17.699  1595  1595 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 11:37:17.700  1595  1595 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 11:37:17.701  1028  1028 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-30 11:37:17.704  1595  1595 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 11:37:17.705  1595  1595 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-30 11:37:17.705  1595  1595 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 11:37:17.707  1028  1028 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 11:37:17.707  1028  1028 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 11:37:17.707  1028  1028 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-30 11:37:17.712  8144  8144 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-30 11:37:17.712  8144  8144 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-30 11:37:17.718  1028  1437 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-30 11:37:17.718  1028  1437 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
08-30 11:37:17.719  1028  1383 E WifiStateMachine:  ConnectedState CMD_SET_COUNTRY_CODE 3 0 cz
08-30 11:37:17.719  1028  1383 E WifiStateMachine:  L2ConnectedState CMD_SET_COUNTRY_CODE 3 0 cz
08-30 11:37:17.721  1028  1437 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
08-30 11:37:17.721   315   891 E Netd    : netlink response contains error (File exists)
08-30 11:37:17.722  1028  1437 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
08-30 11:37:17.723  1028  1437 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-30 11:37:17.723  1028  1437 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 102
08-30 11:37:17.723  1028  1437 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
08-30 11:37:17.723  1595  1595 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 11:37:17.723  1595  1595 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-30 11:37:17.724  1595  1595 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 11:37:17.727  8144  8144 V [BNRBootReceiver]: Boot Receiver Return
,08-30 11:37:17.728  8144  8144 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-30 11:37:17.729  1028  1437 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-30 11:37:17.730  1028  1437 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-30 11:37:17.730  1028  1437 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-30 11:37:17.730  1028  8138 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-30 11:37:17.730  1028  8138 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-30 11:37:17.730  1028  8138 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-30 11:37:17.730  1028  8138 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-30 11:37:17.732  1028  1437 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-30 11:37:17.732  1028  1437 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 11:37:17.732  1028  1437 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 11:37:17.732  1028  1437 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-30 11:37:17.732  1028  1437 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 11:37:17.732  1028  1437 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-30 11:37:17.732  1028  1437 D ConnectivityService: currentScore = 0, newScore = 20
08-30 11:37:17.732  1028  1437 D ConnectivityService:    accepting network in place of null
08-30 11:37:17.733  1028  1437 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 11:37:17.733  1028  1383 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 11:37:17.733  1028  1383 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 11:37:17.733  1843  1843 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 11:37:17.734  1843  1843 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-30 11:37:17.734  1028  1437 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-30 11:37:17.734  1028  1437 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
08-30 11:37:17.734   315  8166 D libc-netbsd: res_queryN name = clients3.go,ogle.com, class = 1, type = 28
08-30 11:37:17.734  1028  1437 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-30 11:37:17.776  1028  1044 I ActivityManager: Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=8167 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-30 11:37:17.776  1028  1437 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-30 11:37:17.776  1028  1437 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-30 11:37:17.777  1028  1437 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-30 11:37:17.778  1028  1044 I ActivityManager: Killing 7158:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
08-30 11:37:17.778  1028  1028 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-30 11:37:17.778  1028  1028 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-30 11:37:17.778  1028  1028 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-30 11:37:17.779  1028  1028 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-30 11:37:17.779  1028  1437 D ConnectivityService: validation of new default Network = false
08-30 11:37:17.779  1028  1437 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-30 11:37:17.779  1028  1437 D DSQN    : enableDataServiceNotify 
,08-30 11:37:17.780  1028  1437 D DSQN    : start dsqn bin
,08-30 11:37:17.787  1028  1437 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-30 11:37:17.787  1028  1437 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 11:37:17.787  1028  1437 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 11:37:17.777  8176  8176 W dsqn    : type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6837 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 11:37:17.777  8176  8176 W dsqn    : type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6837 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 11:37:17.790  1028  1437 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 11:37:17.791  1595  2063 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-30 11:37:17.801  8176  8176 E DSQN    : DSQN ssw
,08-30 11:37:17.838  1028  8140 D DhcpStateMachine: DHCPV4 request on wlan0
,08-30 11:37:17.839  1028  8140 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-30 11:37:17.839  1028  8140 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
,08-30 11:37:17.827  8188  8188 W dhcpcd  : type=1400 audit(0.0:193): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6837 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 11:37:17.827  8188  8188 W dhcpcd  : type=1400 audit(0.0:194): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6837 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 11:37:17.849  8188  8188 I dhcpcd  : version 5.5.6 starting
08-30 11:37:17.851  8188  8188 E dhcpcd  : get_duid: m
08-30 11:37:17.851  8188  8188 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-30 11:37:17.851  8188  8188 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,08-30 11:37:17.910  1028  1710 W libprocessgroup: failed to open /acct/uid_10093/pid_7158/cgroup.procs: No such file or directory
,08-30 11:37:17.953  8167  8167 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-30 11:37:17.971  1028  1378 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
08-30 11:37:17.973  8188  8188 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
,08-30 11:37:17.973  8188  8188 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-30 11:37:17.973  8188  8188 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-30 11:37:17.973  8188  8188 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
08-30 11:37:17.973  8188  8188 D dhcpcd  : wlan0: sending REQUEST (xid 0x2e63ecc3), next in 3.31 seconds
,08-30 11:37:17.985  1595  1595 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-30 11:37:17.986  1595  1595 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 11:37:17.987  1595  1595 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 11:37:17.991  8167  8167 D PluginManager: init()
,08-30 11:37:18.048  8188  8188 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
,08-30 11:37:18.105  8188  8188 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
,08-30 11:37:18.105  8188  8188 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
,08-30 11:37:18.106  8188  8188 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
,08-30 11:37:18.106  8188  8188 D dhcpcd  : wlan0: adding default route via 192.168.1.1
,08-30 11:37:18.106  8188  8188 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,08-30 11:37:18.107  8188  8188 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-30 11:37:18.107  8188  8188 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-30 11:37:18.107  8188  8188 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,08-30 11:37:18.344  8167  8167 W ExternalStrings: load override strings
08-30 11:37:18.344  8167  8167 W ExternalStrings: java.lang.RuntimeException: Unexpected tag, got eat-comment
08-30 11:37:18.344  8167  8167 W ExternalStrings: 	at com.mcafee.plugin.af.a(Unknown Source)
08-30 11:37:18.344  8167  8167 W ExternalStrings: 	at com.mcafee.plugin.ac.b(Unknown Source)
08-30 11:37:18.344  8167  8167 W ExternalStrings: 	at com.mcafee.plugin.ak.d(Unknown Source)
08-30 11:37:18.344  8167  8167 W ExternalStrings: 	at com.mcafee.plugin.ak.a(Unknown Source)
08-30 11:37:18.344  8167  8167 W ExternalStrings: 	at com.mcafee.app.s.getClassLoader(Unknown Source)
08-30 11:37:18.344  8167  8167 W ExternalStrings: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
08-30 11:37:18.344  8167  8167 W ExternalStrings: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-30 11:37:18.344  8167  8167 W ExternalStrings: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-30 11:37:18.344  8167  8167 W ExternalStrings: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-30 11:37:18.344  8167  8167 W ExternalStrings: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-30 11:37:18.344  8167  8167 W ExternalStrings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 11:37:18.344  8167  8167 W ExternalStrings: 	at android.os.Looper.loop(Looper.java:135)
08-30 11:37:18.344  8167  8167 W ExternalStrings: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-30 11:37:18.344  8167  8167 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 11:37:18.344  8167  8167 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 11:37:18.344  8167  8167 W ExternalStrings: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-30 11:37:18.344  8167  8167 W ExternalStrings: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,08-30 11:37:18.346  8167  8167 D StatusProvider: onCreate
,08-30 11:37:18.385  8167  8167 V Signer  : override build config not found
08-30 11:37:18.385  8167  8167 D Signer  : value of property debug is false
,08-30 11:37:18.426  8167  8167 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
,08-30 11:37:18.426  8167  8167 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
08-30 11:37:18.426  8167  8167 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
08-30 11:37:18.426  8167  8167 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
08-30 11:37:18.427  8167  8167 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
08-30 11:37:18.427  8167  8167 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
08-30 11:37:18.427  8167  8167 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
08-30 11:37:18.427  8167  8167 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
08-30 11:37:18.427  8167  8167 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
08-30 11:37:18.427  8167  8167 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
08-30 11:37:18.427  8167  8167 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
08-30 11:37:18.427  8167  8167 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
08-30 11:37:18.428  8167  8167 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
,08-30 11:37:18.436  8167  8167 V LGMDMManager: Create singleton instance,
08-30 11:37:18.441  7631  7927 D UEI.SmartControl: Internal timer expired: 2
08-30 11:37:18.441  7631  7927 D UEI.SmartControl: unbind internal service
08-30 11:37:18.442  1028  8140 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,08-30 11:37:18.446  1028  8140 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-30 11:37:18.447  1028  8140 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-30 11:37:18.447  1028  8140 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
08-30 11:37:18.447  1028  8140 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-30 11:37:18.447  1028  8140 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-30 11:37:18.447  1028  8140 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-30 11:37:18.447  1028  8140 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-30 11:37:18.448  1028  8140 D DhcpStateMachine: RunningState
08-30 11:37:18.473  8167  8167 D LGMDMWrapper: LG MDM library v4.0.0 is available on this device.
,08-30 11:37:18.542  8167  8167 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 11:37:18.558  8167  8223 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-30 11:37:18.568  6767  6767 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 11:37:18.576  6767  6767 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 11:37:18.585  7892  7892 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 11:37:18.587  7892  7892 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-30 11:37:18.592  7892  7892 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-30 11:37:18.598  8167  8167 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 11:37:18.598  8167  8223 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-30 11:37:18.608  6767  6767 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-30 11:37:18.615  6767  6767 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 11:37:18.620  7892  7892 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-30 11:37:18.623  7892  7892 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 11:37:18.624  7892  7892 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-30 11:37:18.627  8167  8167 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 11:37:18.628  8167  8223 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-30 11:37:18.633  6767  6767 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 11:37:18.640  6767  6767 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 11:37:18.649  7892  7892 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 11:37:18.649  7892  7892 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 11:37:18.649  7892  7892 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-30 11:37:18.688  6540  6656 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 847)
08-30 11:37:18.688  6540  6656 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 847)
,08-30 11:37:18.692  6540  6656 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 852)
08-30 11:37:18.693  6540  6656 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-30 11:37:18.693  6540  6656 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 853)
08-30 11:37:18.696  6540  6656 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 11:37:18.696  6540  6656 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f449d8c added. We now have 2 listener(s)
08-30 11:37:18.696  1028  1968 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-30 11:37:18.699  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 11:37:18.699  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 11:37:18.699  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 11:37:18.700  6540  6656 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 11:37:18.700  6540  6656 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3e7fecd5 added. We now have 9 listener(s)
08-30 11:37:18.700  6540  6656 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 11:37:18.700  6540  6656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 11:37:18.702  6540  6656 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 11:37:18.707  6540  6656 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 11:37:18.707  6540  6656 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 11:37:18.707  6540  6656 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 11:37:18.707  6540  6656 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 11:37:18.707  6540  6656 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 11:37:18.707  6540  6656 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 11:37:18.707  6540  6656 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 11:37:18.707  6540  6656 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 11:37:18.710  6540  6656 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 11:37:18.710  6540  6656 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 11:37:18.710  6540  6656 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 11:37:18.710  6540  6656 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@33965bdb added. We now have 3 listener(s)
,08-30 11:37:18.712  1028  1877 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 11:37:18.713  6540  6540 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 11:37:18.715  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 11:37:18.715  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 11:37:18.715  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 11:37:18.716  6540  6656 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 11:37:18.716  6540  6656 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d640678 added. We now have 10 listener(s)
08-30 11:37:18.716  6540  6656 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 11:37:18.716  6540  6656 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 11:37:18.716  6540  6656 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 11:37:18.716  6540  6656 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 11:37:18.716  6540  6656 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 11:37:18.716  6540  6656 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:37:18.716  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 11:37:18.716  6540  6656 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 11:37:18.717  6540  6656 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f449d8c removed from the list
08-30 11:37:18.717  6540  6656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:37:18.717  6540  6656 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3e7fecd5 removed from the list
08-30 11:37:18.717  6540  6540 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 11:37:18.717  6540  6656 D io.jxcore.node.ConnectivityMonitor: stop
08-30 11:37:18.717  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:37:18.718  6540  6656 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:37:18.718  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:37:18.719  6540  6656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 11:37:18.719  6540  6656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 11:37:18.719  6540  6656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:37:18.719  6540  6656 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3e7fecd5 not in the list
08-30 11:37:18.719  6540  6656 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:37:18.719  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:37:18.720  6540  6656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 11:37:18.720  6540  6656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 11:37:18.720  6540  6656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:37:18.721  6540  6656 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d640678 removed from the list
08-30 11:37:18.721  6540  6656 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 11:37:18.721  6540  6656 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:37:18.721  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:37:18.721  6540  6656 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 11:37:18.721  6540  6656 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@33965bdb removed from the list
08-30 11:37:18.722  6540  6656 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 11:37:18.722  6540  6656 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@65f8151 added. We now have 2 listener(s)
08-30 11:37:18.722  1028  2024 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-30 11:37:18.726  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 11:37:18.726  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 11:37:18.726  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 11:37:18.727  6540  6656 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 11:37:18.727  6540  6656 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25b6edb6 added. We now have 9 listener(s)
08-30 11:37:18.727  6540  6656 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 11:37:18.727  6540  6656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 11:37:18.730   315  8166 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-30 11:37:18.731  6540  6656 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 11:37:18.735  6540  6656 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 11:37:18.735  6540  6656 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 11:37:18.735  6540  6656 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 11:37:18.735  6540  6656 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 11:37:18.735  6540  6656 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 11:37:18.735  6540  6656 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 11:37:18.735  6540  6656 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 11:37:18.735  6540  6656 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 11:37:18.739  6540  6656 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 11:37:18.740  6540  6656 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 11:37:18.740  6540  6656 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 11:37:18.740  6540  6656 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@300f1224 added. We now have 3 listener(s)
08-30 11:37:18.740  1028  2005 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 11:37:18.742  6540  6540 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 11:37:18.744  8167  8167 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 11:37:18.745  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 11:37:18.745  8167  8223 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-30 11:37:18.746  6540  6540 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 11:37:18.745  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 11:37:18.746  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 11:37:18.746  6540  6656 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 11:37:18.746  6540  6656 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39c9e18d added. We now have 10 listener(s)
08-30 11:37:18.746  6540  6656 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 11:37:18.746  6540  6656 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 11:37:18.747  6540  6656 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 11:37:18.747  6540  6656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 11:37:18.747  6540  6656 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 11:37:18.748  6540  6656 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-30 11:37:18.751  6540  6656 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-30 11:37:18.752  1028  2005 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 11:37:18.756  8167  8222 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
08-30 11:37:18.756  6767  6767 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-30 11:37:18.758  6540  6656 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-30 11:37:18.760  7631  7922 D serial_port: close(fd = 24)
08-30 11:37:18.761  6540  6656 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-30 11:37:18.763  7631  7922 I UEI.SmartControl: Serial port is closed.
,08-30 11:37:18.767  6540  6656 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 11:37:18.767  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 11:37:18.768  6767  6767 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 11:37:18.770  6540  6656 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-30 11:37:18.770  6540  6656 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 11:37:18.770  6540  6656 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 11:37:18.776  6540  6656 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 11:37:18.776  6540  6656 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 11:37:18.776  6540  6656 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 11:37:18.777  6540  6656 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 11:37:18.777  6540  6656 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:37:18.777  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 11:37:18.777  6540  6656 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 11:37:18.777  6540  6656 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@65f8151 removed from the list
08-30 11:37:18.777  6540  6656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:37:18.777  6540  6656 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25b6edb6 removed from the list
08-30 11:37:18.777  6540  6656 D io.jxcore.node.ConnectivityMonitor: stop
08-30 11:37:18.777  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:37:18.777  7892  7892 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 11:37:18.777  6540  6656 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:37:18.777  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:37:18.777  7892  7892 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-30 11:37:18.778  6540  6656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 11:37:18.778  6540  6656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 11:37:18.778  6540  6656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:37:18.778  6540  6656 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25b6edb6 not in the list
08-30 11:37:18.778  6540  6656 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 11:37:18.778  7892  7892 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-30 11:37:18.778  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:37:18.779  6540  6656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 11:37:18.779  6540  6656 D BluetoothLeScanner: could not find callback wrapper
08-30 11:37:18.779  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 11:37:18.779  6540  6656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 11:37:18.779  6540  6656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:37:18.779  6540  6656 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39c9e18d removed from the list
08-30 11:37:18.779  6540  6656 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 11:37:18.779  6540  6656 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:37:18.780  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:37:18.780  6540  6656 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 11:37:18.780  6540  6656 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@300f1224 removed from the list
08-30 11:37:18.780  6540  6656 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-30 11:37:18.780  6540  6656 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@263d2c90 added. We now have 2 listener(s)
08-30 11:37:18.780  1028  2040 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 11:37:18.783  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 11:37:18.783  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 11:37:18.783  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 11:37:18.783  6540  6656 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 11:37:18.783  6540  6656 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33000989 added. We now have 9 listener(s)
08-30 11:37:18.783  6540  6656 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 11:37:18.784  6540  6656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 11:37:18.787  6540  6656 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 11:37:18.790  6767  6767 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
08-30 11:37:18.791  6540  6656 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 11:37:18.791  6540  6656 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 11:37:18.791  6540  6656 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 11:37:18.791  6540  6656 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 11:37:18.791  6540  6656 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 11:37:18.791  6540  6656 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 11:37:18.791  6540  6656 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 11:37:18.791  6540  6656 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 11:37:18.792  6540  6656 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 11:37:18.792  6540  6656 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 11:37:18.794  6540  6656 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 11:37:18.794  6540  6656 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f4e69af added. We now have 3 listener(s)
08-30 11:37:18.794  6540  6540 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 11:37:18.796  6767  6767 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-30 11:37:18.797  1028  1967 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 11:37:18.797  6540  6540 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 11:37:18.800  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 11:37:18.800  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 11:37:18.800  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-30 11:37:18.800  6540  6656 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 11:37:18.800  6540  6656 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24f081bc added. We now have 10 listener(s)
08-30 11:37:18.800  6540  6656 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 11:37:18.800  6540  6656 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 11:37:18.801  6540  6656 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 11:37:18.801  6540  6656 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 11:37:18.801  6540  6656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 11:37:18.801  6540  6656 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 11:37:18.801  6540  6656 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 11:37:18.801  8167  8223 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-30 11:37:18.802  8167  8167 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 11:37:18.804  6540  6656 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-30 11:37:18.805  1028  1912 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 11:37:18.812  6767  6767 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-30 11:37:18.812  6540  6656 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-30 11:37:18.813  6540  6656 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-30 11:37:18.814  6540  6656 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 11:37:18.814  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 11:37:18.816  6540  6656 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-30 11:37:18.817  6767  6767 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 11:37:18.817  6540  6656 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 11:37:18.817  6540  6656 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 11:37:18.817  6540  6656 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 11:37:18.818  6540  6656 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 11:37:18.818  6540  6656 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given, listener does not exist in the list - probably already removed
08-30 11:37:18.818  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 11:37:18.818  6540  6656 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 11:37:18.818  6540  6656 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@263d2c90 removed from the list
08-30 11:37:18.818  6540  6656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:37:18.818  6540  6656 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33000989 removed from the list
08-30 11:37:18.818  6540  6656 D io.jxcore.node.ConnectivityMonitor: stop
08-30 11:37:18.818  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:37:18.818  6540  6656 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:37:18.818  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:37:18.819  6540  6656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 11:37:18.819  6540  6656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 11:37:18.819  6540  6656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:37:18.819  6540  6656 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33000989 not in the list
08-30 11:37:18.819  6540  6656 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:37:18.819  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:37:18.821  7892  7892 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-30 11:37:18.821  6540  6656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 11:37:18.821  7892  7892 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 11:37:18.822  6540  6656 D BluetoothLeScanner: could not find callback wrapper
08-30 11:37:18.822  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 11:37:18.822  6540  6656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 11:37:18.822  6540  6656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:37:18.822  6540  6656 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24f081bc removed from the list
08-30 11:37:18.822  6540  6656 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 11:37:18.822  6540  6656 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:37:18.822  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:37:18.822  6540  6656 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 11:37:18.822  6540  6656 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f4e69af removed from the list
08-30 11:37:18.823  6540  6656 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 11:37:18.823  6540  6656 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d21f1cb added. We now have 2 listener(s)
08-30 11:37:18.823  1028  2024 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 11:37:18.825  7892  7892 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-30 11:37:18.826  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 11:37:18.827  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 11:37:18.827  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 11:37:18.827  6540  6656 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 11:37:18.827  6540  6656 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d21fda8 added. We now have 9 listener(s)
08-30 11:37:18.827  6540  6656 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 11:37:18.827  8167  8167 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 11:37:18.828  8167  8223 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-30 11:37:18.829  6540  6656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 11:37:18.833  6767  6767 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 11:37:18.835  6540  6656 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 11:37:18.838  6540  6656 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 11:37:18.838  6540  6656 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 11:37:18.838  6540  6656 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 11:37:18.838  6540  6656 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 11:37:18.838  6540  6656 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 11:37:18.838  6540  6656 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 11:37:18.838  6540  6656 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 11:37:18.838  6540  6656 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 11:37:18.838  6767  6767 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 11:37:18.839  6540  6656 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 11:37:18.839  6540  6656 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 11:37:18.839  6540  6656 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 11:37:18.839  6540  6656 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1db43066 added. We now have 3 listener(s)
08-30 11:37:18.840  6540  6540 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 11:37:18.841  1028  1044 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 11:37:18.842  6540  6540 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 11:37:18.843  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 11:37:18.844  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 11:37:18.844  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 11:37:18.844  6540  6656 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 11:37:18.844  6540  6656 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@215bdfa7 added. We now have 10 listener(s)
08-30 11:37:18.844  6540  6656 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 11:37:18.844  6540  6656 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 11:37:18.844  6540  6656 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 11:37:18.844  6540  6656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 11:37:18.844  6540  6656 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 11:37:18.844  6540  6656 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-30 11:37:18.847  6540  6656 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-30 11:37:18.847  1028  1567 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 11:37:18.850  6540  6656 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-30 11:37:18.852  6540  6656 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-30 11:37:18.852  7892  7892 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 11:37:18.853  7892  7892 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 11:37:18.854  6540  6656 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 11:37:18.854  7892  7892 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-30 11:37:18.855  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 11:37:18.857  6540  6656 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,08-30 11:37:18.858  8167  8167 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 11:37:18.858  8167  8223 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-30 11:37:18.860  6540  6656 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 11:37:18.860  6540  6656 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 11:37:18.860  6540  6656 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 11:37:18.860  6540  6656 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 11:37:18.860  6540  6656 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 11:37:18.860  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 11:37:18.861  6540  6656 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 11:37:18.861  6540  6656 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d21f1cb removed from the list
08-30 11:37:18.861  6540  6656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:37:18.861  6540  6656 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d21fda8 removed from the list
08-30 11:37:18.861  6540  6656 D io.jxcore.node.ConnectivityMonitor: stop
08-30 11:37:18.861  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:37:18.864  8087  8087 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-30 11:37:18.865  6540  6656 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:37:18.865  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:37:18.865  6540  6656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 11:37:18.865  6540  6656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 11:37:18.865  6540  6656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:37:18.866  6540  6656 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d21fda8 not in the list
08-30 11:37:18.866  6540  6656 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:37:18.866  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:37:18.866  6540  6656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 11:37:18.867  6540  6656 D BluetoothLeScanner: could not find callback wrapper
08-30 11:37:18.867  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 11:37:18.867  6540  6656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 11:37:18.867  6540  6656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:37:18.867  6540  6656 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@215bdfa7 removed from the list
08-30 11:37:18.867  6540  6656 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 11:37:18.867  6540  6656 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:37:18.867  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:37:18.867  6540  6656 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 11:37:18.867  6540  6656 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1db43066 removed from the list
08-30 11:37:18.867  8087  8087 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-30 11:37:18.869  6540  6656 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 11:37:18.869  6540  6656 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproj,ect.p2p.btconnectorlib.ConnectionManager@29c2ecf2 added. We now have 2 listener(s)
08-30 11:37:18.869  1028  1043 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 11:37:18.869  6767  6767 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 11:37:18.873  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 11:37:18.873  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 11:37:18.873  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 11:37:18.873  6540  6656 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 11:37:18.874  6540  6656 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@215ccf43 added. We now have 9 listener(s)
08-30 11:37:18.874  6540  6656 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 11:37:18.874  6540  6656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 11:37:18.876  6540  6656 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 11:37:18.878  6540  6656 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 11:37:18.878  6540  6656 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 11:37:18.878  6540  6656 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 11:37:18.878  6540  6656 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 11:37:18.878  6540  6656 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 11:37:18.878  6540  6656 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 11:37:18.878  6540  6656 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 11:37:18.878  6540  6656 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 11:37:18.879  6767  6767 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 11:37:18.881  6540  6656 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 11:37:18.881  6540  6656 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 11:37:18.881  6540  6656 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 11:37:18.881  6540  6656 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@60166f9 added. We now have 3 listener(s)
,08-30 11:37:18.883  6540  6540 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 11:37:18.885  6540  6540 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 11:37:18.886  1028  1877 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 11:37:18.886  7892  7892 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 11:37:18.886  7892  7892 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 11:37:18.887  7892  7892 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-30 11:37:18.887  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 11:37:18.887  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 11:37:18.887  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 11:37:18.887  6540  6656 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 11:37:18.887  6540  6656 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@198ee63e added. We now have 10 listener(s)
08-30 11:37:18.888  6540  6656 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 11:37:18.888  6540  6656 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 11:37:18.888  6540  6656 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 11:37:18.888  6540  6656 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 11:37:18.888  6540  6656 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 11:37:18.888  6540  6656 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:37:18.888  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 11:37:18.888  6540  6656 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 11:37:18.888  6540  6656 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@29c2ecf2 removed from the list
08-30 11:37:18.888  6540  6656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:37:18.888  6540  6656 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@215ccf43 removed from the list
08-30 11:37:18.888  6540  6656 D io.jxcore.node.ConnectivityMonitor: stop
08-30 11:37:18.888  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:37:18.888  6540  6656 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:37:18.888  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:37:18.889  6540  6656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 11:37:18.889  6,540  6656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 11:37:18.889  6540  6656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:37:18.889  6540  6656 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@215ccf43 not in the list
08-30 11:37:18.889  6540  6656 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:37:18.889  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:37:18.890  6540  6656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 11:37:18.890  6540  6656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 11:37:18.890  6540  6656 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 11:37:18.890  6540  6656 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@198ee63e removed from the list
08-30 11:37:18.890  6540  6656 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 11:37:18.890  6540  6656 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 11:37:18.890  6540  6656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 11:37:18.890  6540  6656 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 11:37:18.890  6540  6656 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@60166f9 removed from the list
08-30 11:37:18.890  6540  6656 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-30 11:37:18.890  6540  6656 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-30 11:37:18.891  6540  6656 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-30 11:37:18.891  6540  6656 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 11:37:18.891  6540  6656 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-30 11:37:18.891  6540  6656 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-30 11:37:18.897  7892  7892 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,08-30 11:37:18.897  7892  7892 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-30 11:37:18.898  6540  8245 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 860, name: My test thread name)
08-30 11:37:18.898  6540  8245 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 860, thread name: My test thread name)
08-30 11:37:18.898  6540  8245 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 860, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-30 11:37:18.901  6540  8246 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 862, name: My test thread name)
08-30 11:37:18.901  6540  8246 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 862, thread name: My test thread name)
08-30 11:37:18.901  6540  8246 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 862, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-30 11:37:18.903  8167  8167 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 11:37:18.903  6540  6656 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-30 11:37:18.903  6540  6656 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-30 11:37:18.903  8167  8223 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-30 11:37:18.904  6540  6656 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-30 11:37:18.904  6540  6656 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-30 11:37:18.904  6540  6656 D com.test.thalitest.ThaliTestRunner: Total duration: 23778 ms
08-30 11:37:18.905  6540  6656 I jxcore-log: *Native tests were executed*
08-30 11:37:18.905  6540  6656 I jxcore-log: 
08-30 11:37:18.905  8087  8087 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-30 11:37:18.905  6540  6656 I jxcore-log: Total number of executed tests:  80
08-30 11:37:18.905  6540  6656 I jxcore-log: 
08-30 11:37:18.905  6540  6656 I jxcore-log: Number of passed tests:  80
08-30 11:37:18.905  6540  6656 I jxcore-log: 
08-30 11:37:18.906  8087  8087 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-30 11:37:18.906  6540  6656 I jxcore-log: Number of failed tests:  0
08-30 11:37:18.906  6540  6656 I jxcore-log: 
08-30 11:37:18.906  6540  6656 I jxcore-log: Number of ignored tests:  0
08-30 11:37:18.906  6540  6656 I jxcore-log: 
,08-30 11:37:18.907  6540  6656 I jxcore-log: Total duration:  23778
08-30 11:37:18.907  6540  6656 I jxcore-log: 
08-30 11:37:18.907  6540  6656 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-30 11:37:18.907  6540  6656 I jxcore-log: 
08-30 11:37:18.908  6767  6767 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-30 11:37:18.910  6540  6656 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 11:37:18.910  6540  6656 I jxcore-log: 
08-30 11:37:18.913  6540  6656 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 11:37:18.913  6540  6656 I jxcore-log: 
08-30 11:37:18.916  6540  6656 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 11:37:18.916  6540  6656 I jxcore-log: 
08-30 11:37:18.917  6540  6656 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 11:37:18.917  6540  6656 I jxcore-log: 
08-30 11:37:18.918  6540  6656 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 11:37:18.918  6540  6656 I jxcore-log: 
08-30 11:37:18.918  6540  6540 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-30 11:37:18.919  6540  6656 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 11:37:18.919  6540  6656 I jxcore-log: 
,08-30 11:37:18.920  6767  6767 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 11:37:18.923  6540  6656 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 11:37:18.923  6540  6656 I jxcore-log: 
08-30 11:37:18.924  7892  7892 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 11:37:18.924  7892  7892 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 11:37:18.925  7892  7892 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-30 11:37:18.925  7892  7892 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-30 11:37:18.925  7892  7892 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-30 11:37:18.925  6540  6656 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 11:37:18.925  6540  6656 I jxcore-log: 
08-30 11:37:18.926  6540  6656 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 11:37:18.926  6540  6656 I jxcore-log: 
08-30 11:37:18.928  6540  6656 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 11:37:18.928  6540  6656 I jxcore-log: 
08-30 11:37:18.928  8167  8167 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-30 11:37:18.929  6540  6656 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-30 11:37:18.929  6540  6656 I jxcore-log: 
08-30 11:37:18.930  8167  8167 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-30 11:37:18.930  6540  6656 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 11:37:18.930  6540  6656 I jxcore-log: 
08-30 11:37:18.931  8167  8167 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-30 11:37:18.931  6540  6656 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 11:37:18.931  6540  6656 I jxcore-log: 
08-30 11:37:18.932  6540  6656 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 11:37:18.932  6540  6656 I jxcore-log: 
08-30 11:37:18.932  8167  8167 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-30 11:37:18.933  6540  6656 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 11:37:18.933  6540  6656 I jxcore-log: 
08-30 11:37:18.933  6540  6656 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 11:37:18.933  6540  6656 I jxcore-log: 
08-30 11:37:18.933  8167  8167 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-30 11:37:18.934  6540  6656 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 11:37:18.934  6540  6656 I jxcore-log: 
08-30 11:37:18.935  8167  8167 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-30 11:37:18.935  6540  6656 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 11:37:18.935  6540  6656 I jxcore-log: 
,08-30 11:37:18.936  6540  6656 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 11:37:18.936  6540  6656 I jxcore-log: 
08-30 11:37:18.936  8167  8167 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-30 11:37:18.936  6540  6656 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 11:37:18.936  6540  6656 I jxcore-log: 
08-30 11:37:18.937  6540  6656 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 11:37:18.937  6540  6656 I jxcore-log: 
08-30 11:37:18.938  6540  6656 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-30 11:37:18.938  6540  6656 I jxcore-log: 
08-30 11:37:18.938  8167  8167 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-30 11:37:18.939  6540  6656 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-30 11:37:18.939  6540  6656 I jxcore-log: 
08-30 11:37:18.939  1028  2024 I ActivityManager: Killing 7187:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
08-30 11:37:18.940  6540  6656 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 11:37:18.940  6540  6656 I jxcore-log: 
08-30 11:37:18.940  6540  6656 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 11:37:18.940  6540  6656 I jxcore-log: 
08-30 11:37:18.941  6540  6656 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 11:37:18.941  6540  6656 I jxcore-log: 
08-30 11:37:18.942  6540  6656 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 11:37:18.942  6540  6656 I jxcore-log: 
08-30 11:37:18.943  6540  6656 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 11:37:18.943  6540  6656 I jxcore-log: 
08-30 11:37:18.944  8167  8222 D LgDataFeature: LgDataFeature() Constructor: none
08-30 11:37:18.944  8167  8222 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 11:37:18.985   315  8166 D libc-netbsd: res_queryN name = clients3.google.com succeed
,08-30 11:37:18.997  1028  2040 W libprocessgroup: failed to open /acct/uid_10005/pid_7187/cgroup.procs: No such file or directory
,08-30 11:37:19.024  8167  8222 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
,08-30 11:37:19.042  8167  8222 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
,08-30 11:37:19.047  8167  8222 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
08-30 11:37:19.048  8167  8222 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-30 11:37:19.048  8167  8222 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-30 11:37:19.049  8167  8222 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
08-30 11:37:19.049  8167  8222 I SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
08-30 11:37:19.052  8167  8222 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
08-30 11:37:19.053  8167  8222 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
,08-30 11:37:19.179  8249  8249 D AndroidRuntime: 
08-30 11:37:19.179  8249  8249 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-30 11:37:19.182  8249  8249 D AndroidRuntime: CheckJNI is OFF
,08-30 11:37:19.359  1028  1383 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-30 11:37:19.360  1028  1383 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-30 11:37:19.362  1028  1383 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-30 11:37:19.363  1028  1383 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-30 11:37:19.366  1028  1383 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-30 11:37:19.367  1028  1383 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-30 11:37:19.369  1028  1437 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=true
08-30 11:37:19.369  1028  1437 D ConnectivityService: identical MTU - not setting
08-30 11:37:19.369  1028  1437 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-30 11:37:19.369  1028  1437 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-30 11:37:19.369  1028  1437 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 11:37:19.369  1028  1437 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 11:37:19.371  1028  1437 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 11:37:19.373  1595  2063 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
08-30 11:37:19.401  8249  8249 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-30 11:37:19.422  1028  1106 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
,08-30 11:37:19.425  1028  1106 I ActivityManager: Killing 6540:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
08-30 11:37:19.435   315   890 D LGDataListener: argv[0]=dsqncommand
08-30 11:37:19.435   315   890 D LGDataListener: argv[1]=wlan0
08-30 11:37:19.435   315   890 D LGDataListener: argv[2]=1
08-30 11:37:19.435   315   890 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
,08-30 11:37:19.445  1028  1108 D DSQN    : DSQM DsqnNotification wlan0  1
08-30 11:37:19.445  1028  1108 D DSQN    : start to monitor internet connection
08-30 11:37:19.499  1028  1433 D WifiService: Client connection lost with reason: 4
08-30 11:37:19.499  1028  2024 I WindowState: WIN DEATH: Window{26e3e02d u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-30 11:37:19.508  1028  2024 D InputDispatcher: Window went away: Window{26e3e02d u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-30 11:37:19.558  1028  1106 I ActivityManager:   Force finishing activity ActivityRecord{b34b74d u0 com.test.thalitest/.MainActivity t6}
,08-30 11:37:19.593   340   355 E GBMv2   : DFP En is all cleared set to be enabled
,08-30 11:37:19.597  1028  1567 W ActivityManager: Spurious death for ProcessRecord{1d61f1ad 6540:com.test.thalitest/u0a118}, curProc for 6540: null
08-30 11:37:19.597  1028  1116 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
08-30 11:37:19.600  1028  1116 I ActivityManager:   Force finishing activity ActivityRecord{b34b74d u0 com.test.thalitest/.MainActivity t6 f}
08-30 11:37:19.600  1028  1116 W ActivityManager: Duplicate finish request for ActivityRecord{b34b74d u0 com.test.thalitest/.MainActivity t6 f}
,08-30 11:37:19.634  2025  2025 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
08-30 11:37:19.636  1933  1948 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
,08-30 11:37:19.636  1933  1948 D SplitWindowPolicy: topRunningActivity=ActivityInfo{1cf5475a co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-30 11:37:19.636  2025  2025 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
08-30 11:37:19.639  2025  2025 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
08-30 11:37:19.640  2025  2122 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
08-30 11:37:19.644  2025  2025 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
08-30 11:37:19.644  1896  1896 D ActionManagerService: notifyUserLog: 1000003
08-30 11:37:19.645  3835  4499 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
08-30 11:37:19.646  1933  1949 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
08-30 11:37:19.646  1933  1949 D SplitWindowPolicy: topRunningActivity=ActivityInfo{19c8fd8b co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-30 11:37:19.650  1595  1595 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,08-30 11:37:19.651  2025  2025 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
08-30 11:37:19.657  1028  1370 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-30 11:37:19.668  1988  1988 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
,08-30 11:37:19.669  3835  3835 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
08-30 11:37:19.671  2500  2693 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-30 11:37:19.673  7702  7702 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
08-30 11:37:19.673  7702  7702 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-30 11:37:19.698  4620  4620 I art     : Explicit concurrent mark sweep GC freed 8234(470KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 30MB/46MB, paused 720us total 89.453ms
,08-30 11:37:19.718  1595  1595 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
08-30 11:37:19.722  2025  2025 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
,08-30 11:37:19.723  2025  2025 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
08-30 11:37:19.723  4506  4506 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-30 11:37:19.724  4506  4506 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-30 11:37:19.724  4506  4506 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-30 11:37:19.724  4506  4506 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-30 11:37:19.724  4506  4506 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-30 11:37:19.724  4506  4506 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-30 11:37:19.724  4506  4506 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-30 11:37:19.724  4506  4506 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-30 11:37:19.724  4506  4506 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 11:37:19.724  4506  4506 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 11:37:19.724  4506  4506 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-30 11:37:19.724  4506  4506 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-30 11:37:19.726  1595  1660 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-30 11:37:19.726  1595  1660 D KeyguardModel: createShortcutInfo...
08-30 11:37:19.728  1595  1660 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-30 11:37:19.728  1595  1660 D KeyguardModel: createShortcutInfo...
08-30 11:37:19.733  1896  1896 D ActionManagerService: notifyUserLog: 1000004
08-30 11:37:19.733  3835  4499 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
08-30 11:37:19.735  2025  2025 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
08-30 11:37:19.736  3835  3853 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-30 11:37:19.738  1595  1660 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-30 11:37:19.738  1595  1660 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 11:37:19.738  1595  1660 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-30 11:37:19.739  1595  1660 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-30 11:37:19.742  2025  2025 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-30 11:37:19.742  2025  2025 I GBoardWebViewUtils: , create_time: 1430832262123
08-30 11:37:19.742  2025  2025 I GBoardWebViewUtils: , expire_time: 0
08-30 11:37:19.742  2025  2025 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-30 11:37:19.742  2025  2025 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-30 11:37:19.742  2025  2025 I GBoardWebViewUtils: , display: false
08-30 11:37:19.742  2025  2025 I GBoardWebViewUtils: , animation: false }
08-30 11:37:19.742  2025  2025 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-30 11:37:19.742  2025  2025 I GBoardWebViewUtils: , create_time: 1430832262287
08-30 11:37:19.742  2025  2025 I GBoardWebViewUtils: , expire_time: 0
08-30 11:37:19.742  2025  2025 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-30 11:37:19.742  2025  2025 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-30 11:37:19.742  2025  2025 I GBoardWebViewUtils: , display: false
08-30 11:37:19.742  2025  2025 I GBoardWebViewUtils: , animation: false }
08-30 11:37:19.742  2025  2025 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1472216587976
08-30 11:37:19.742  2025  2025 I GBoardWebViewUtils: , create_time: 1472216588858
08-30 11:37:19.742  2025  2025 I GBoardWebViewUtils: , expire_time: 0
08-30 11:37:19.742  2025  2025 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide.html?id=guide_1111111111116_1472216587976&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-30 11:37:19.742  2025  2025 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-30 11:37:19.742  2025  2025 I GBoardWebViewUtils: , display: false
08-30 11:37:19.742  2025  2025 I GBoardWebViewUtils: , animation: false }
08-30 11:37:19.746  1028  1710 V SIM_STK : Menu title from STK is T-Mobile
08-30 11:37:19.747  1595  1660 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-30 11:37:19.747  1595  1660 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-30 11:37:19.748  8167  8167 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-30 11:37:19.759  1595  1595 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-30 11:37:19.759  1595  1595 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
,08-30 11:37:19.761  2025  8288 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
,08-30 11:37:19.785  1028  1105 W InputMethodInfo: Duplicated subtype definition found: , voice
,08-30 11:37:19.788  1595  1660 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-30 11:37:19.788  1595  1660 D KeyguardModel: createShortcutInfo...
08-30 11:37:19.799  1595  1660 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-30 11:37:19.800  1595  1660 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-30 11:37:19.802  1028  1028 I art     : Explicit concurrent mark sweep GC freed 71326(3MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 43MB/65MB, paused 2.916ms total 182.096ms
,08-30 11:37:19.803  1808  1808 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
08-30 11:37:19.810  1595  1660 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-30 11:37:19.810  1595  1660 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-30 11:37:19.810  1860  1860 D SplitUIManager: split_name #11 / not available #0
08-30 11:37:19.811  1860  1860 D SplitUIService: removed split : 
08-30 11:37:19.813  1028  1116 I art     : WaitForGcToComplete blocked for 48.165ms for cause Explicit
08-30 11:37:19.817  1595  1660 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-30 11:37:19.817  1595  1660 D KeyguardModel: createShortcutInfo...
,08-30 11:37:19.822  2195  2195 I ConfigService: onCreate
08-30 11:37:19.823  1028  1878 V SIM_STK : Menu title from STK is T-Mobile
08-30 11:37:19.823  1028  1878 V SIM_STK : Menu title from STK is T-Mobile
08-30 11:37:19.824  2195  2195 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
08-30 11:37:19.825  2025  2025 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
08-30 11:37:19.831  2195  2195 I ConfigService: onBind returning update interface
,08-30 11:37:19.836  1808  1808 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
08-30 11:37:19.837  1595  1660 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 11:37:19.837  1595  1660 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-30 11:37:19.837  1595  1660 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-30 11:37:19.837  1595  1660 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-30 11:37:19.856  2195  2195 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-30 11:37:19.856  2195  2195 I ConfigService: onBind returning config service
,08-30 11:37:19.865  1595  1660 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-30 11:37:19.865  1595  1660 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-30 11:37:19.866  1595  1660 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-30 11:37:19.866  1595  1660 D KeyguardModel: createShortcutInfo...
08-30 11:37:19.869  1595  1595 D KeyguardModel: handleShortcutListChanged...
08-30 11:37:19.869  1595  1595 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
,08-30 11:37:19.873  1028  1044 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-30 11:37:19.873  7702  7702 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-30 11:37:19.873  7702  7702 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-30 11:37:19.873  7702  7702 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-30 11:37:19.873  7702  7702 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-30 11:37:19.874  7702  7702 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-30 11:37:19.874  7702  7702 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-30 11:37:19.874  7702  7702 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-30 11:37:19.874  7702  7702 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-30 11:37:19.874  7702  7702 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-30 11:37:19.874  7702  7702 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-30 11:37:19.874  7702  7702 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-30 11:37:19.874  1595  1660 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-30 11:37:19.874  1595  1660 D KeyguardModel: createShortcutInfo...
08-30 11:37:19.875  1860  1860 D SplitUIManager: split_name #11 / not available #0
08-30 11:37:19.875  1860  1860 I SplitUIService: split app #11
08-30 11:37:19.877  1595  1660 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-30 11:37:19.877  1595  1660 D KeyguardModel: createShortcutInfo...
08-30 11:37:19.878  1595  1660 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-30 11:37:19.878  1595  1660 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-30 11:37:19.879  1595  1660 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
,08-30 11:37:19.879  1595  1660 D KeyguardModel: createShortcutInfo...
08-30 11:37:19.880  1595  1660 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-30 11:37:19.880  1595  1660 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-30 11:37:19.881  1595  1660 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-30 11:37:19.881  1595  1660 D KeyguardModel: createShortcutInfo...
08-30 11:37:19.882  1595  1660 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-30 11:37:19.883  1595  1660 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-30 11:37:19.884  1595  1660 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-30 11:37:19.884  1595  1660 D KeyguardModel: createShortcutInfo...
08-30 11:37:19.894  2195  2195 I ConfigService: onDestroy
,08-30 11:37:19.901  1808  8293 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
08-30 11:37:19.903  2025  2025 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-30 11:37:19.906  2025  2025 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
,08-30 11:37:19.914  1028  2024 V SIM_STK : Menu title from STK is T-Mobile
08-30 11:37:19.918  6018  8298 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
08-30 11:37:19.921  1595  1595 D KeyguardModel: handleShortcutListChanged...
08-30 11:37:19.921  1595  1595 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-30 11:37:19.934   334   416 I ThermalEngine: Thermal-Server: Thermal received msg from  override
,08-30 11:37:19.936  3194  8300 I Thermal-Lib: Thermal-Lib-Client: Client request sent
08-30 11:37:19.945  1028  8138 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 30 Aug 2016 09:37:19 GMT], X-Android-Received-Millis=[1472549839945], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472549839429]}
08-30 11:37:19.945  1028  8138 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-30 11:37:19.945  1028  8138 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-30 11:37:19.946  1028  1437 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
08-30 11:37:19.946  1028  1437 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-30 11:37:19.946  1028  1437 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 11:37:19.946  1028  1437 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 11:37:19.946  1028  1437 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-30 11:37:19.946  1028  1437 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
08-30 11:37:19.946  1028  1437 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-30 11:37:19.946  1028  1437 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 11:37:19.946  1028  1437 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 11:37:19.946  1028  1437 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 11:37:19.946  1028  1437 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 11:37:19.946  1028  1437 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-30 11:37:19.947  1028  1383 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 11:37:19.947  1028  1383 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 11:37:19.947  1595  2063 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-30 11:37:19.948  1843  1843 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-30 11:37:19.948  1843  1843 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-30 11:37:19.950  1028  1028 D administrator: Handling package changes for user 0
08-30 11:37:19.953  1808  8302 I PeopleContactsSync: CP2 sync disabled
08-30 11:37:19.969  1808  4777 I Icing   : doRemovePackageData com.test.thalitest
,08-30 11:37:19.973  6972  6972 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
08-30 11:37:19.983  2025  2025 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
08-30 11:37:19.986  2025  2025 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-30 11:37:19.987  2025  2025 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
08-30 11:37:19.988  2025  2025 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-30 11:37:19.990  2025  2025 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-30 11:37:19.991  2025  2025 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
,08-30 11:37:20.014  2025  2025 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
08-30 11:37:20.014  2025  2025 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-30 11:37:20.018  2025  2220 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
,08-30 11:37:20.018  2025  2220 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
08-30 11:37:20.028  2025  2025 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
08-30 11:37:20.029  2025  2025 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-30 11:37:20.029  2025  2025 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-30 11:37:20.046  1028  1028 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-30 11:37:20.046  1028  1028 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,08-30 11:37:20.048  1028  1111 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2108a2b9 u0 com.lge.launcher2/.Launcher t5} time:141093
08-30 11:37:20.050  1028  1028 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-30 11:37:20.052  2025  2025 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
08-30 11:37:20.053  2330  8307 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
08-30 11:37:20.057  1028  1116 I art     : Explicit concurrent mark sweep GC freed 12984(888KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/65MB, paused 1.667ms total 242.284ms
08-30 11:37:20.076  1028  1912 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8308 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-30 11:37:20.080  1028  1569 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
08-30 11:37:20.081  2025  2025 D [Concierge]WidgetView: change position of spinner
08-30 11:37:20.081  2569  2569 D [Concierge]Service: onStartCommand(). Type : 8
08-30 11:37:20.082  2569  2569 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
08-30 11:37:20.082  2025  2025 I [Concierge]WidgetView: initWebView(). Time : 1472549840082
08-30 11:37:20.082  2569  2569 D [Concierge]Service: Update widget ID : 11
08-30 11:37:20.082  2569  2569 D [Concierge]Service: onStartCommand(). Type : 0
08-30 11:37:20.083  1808  8299 W GmsApplication: Using Auth Proxy for data requests.
,08-30 11:37:20.091  1595  1595 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-30 11:37:20.092  1808  8299 W GmsApplication: Using Auth Proxy for data requests.
08-30 11:37:20.092  1595  1595 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 11:37:20.093  1595  1595 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 11:37:20.096  2025  2025 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 918390066
08-30 11:37:20.096  2025  2025 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
08-30 11:37:20.096  2025  2025 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-30 11:37:20.099  2025  2025 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@296e1667
,08-30 11:37:20.099  2025  2025 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
08-30 11:37:20.100  2025  2025 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-30 11:37:20.100  2025  2025 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-30 11:37:20.105  2025  2025 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
08-30 11:37:20.106  2025  2025 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-30 11:37:20.106  2025  2025 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-30 11:37:20.107  2025  2025 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1472549726918, New one : 1472549840082
08-30 11:37:20.107  2025  2025 D [Concierge]WidgetView: Unregister all receivers
08-30 11:37:20.107  2025  2025 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-30 11:37:20.107  2025  2025 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-30 11:37:20.109  2025  2025 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
08-30 11:37:20.111  2025  2025 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
08-30 11:37:20.112  2025  2025 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
08-30 11:37:20.113  2025  2025 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
08-30 11:37:20.114  2025  2025 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
08-30 11:37:20.117  2025  2025 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-30 11:37:20.117  2025  2025 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-30 11:37:20.120  2195  2328 I art     : Explicit concurrent mark sweep GC freed 7288(430KB) AllocSpace objects, 0(0B) LOS objects, 52% free, 29MB/61MB, paused 525us total 27.326ms
08-30 11:37:20.142  8308  8308 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-30 11:37:20.145  8308  8308 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-30 11:37:20.146  8308  8308 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-30 11:37:20.146  8308  8308 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-30 11:37:20.151  2025  2025 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,08-30 11:37:20.158  2025  2025 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
08-30 11:37:20.158  2025  2025 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
08-30 11:37:20.159  2025  2025 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-30 11:37:20.175  8249  8249 D AndroidRuntime: Shutting down VM
,08-30 11:37:20.181  2025  2025 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@f6fc78f time:141226
08-30 11:37:20.210  1028  1105 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-30 11:37:20.214  1028  1105 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-30 11:37:20.219  2025  2025 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-30 11:37:20.226  8308  8308 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-30 11:37:20.233  8308  8308 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
08-30 11:37:20.252  8308  8308 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-30 11:37:20.271  8308  8308 D LgDataFeature: LgDataFeature() Constructor: none
,08-30 11:37:20.271  8308  8308 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 11:37:20.316  8308  8308 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,08-30 11:37:20.325  1028  1043 I ActivityManager: Killing 7733:com.google.android.talk/u0a72 (adj 15): empty #17
,08-30 11:37:20.329  2025  2025 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,08-30 11:37:20.362  2025  2870 I GBoardtInterface: onReloaded()
,08-30 11:37:20.364  2025  2025 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
08-30 11:37:20.375  1988  1988 D LIA_Service_NativeEventReceiver: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-30 11:37:20.375  1988  1988 I LIA_Service_PlatformUtil: startLIAService() : Trying to start LIA service ...
08-30 11:37:20.376  1028  1710 W libprocessgroup: failed to open /acct/uid_10072/pid_7733/cgroup.procs: No such file or directory
,08-30 11:37:20.378  1988  1988 D LIA_Service_LIAService: onStartCommand() : LIAService started! - id :4, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
08-30 11:37:20.378  3835  3853 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-30 11:37:20.380  3835  3854 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
,08-30 11:37:20.404  1028  1116 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8330 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
08-30 11:37:20.404  1896  1896 D ActionManagerService: notifyUserLog: 1000001
08-30 11:37:20.406  8167  8167 D PostponalbeReceiver: OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-30 11:37:20.408  3835  4499 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-30 11:37:20.408  3835  4499 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-30 11:37:20.410  7479  7479 D CoreEventReceiver: [onReceive] Action=android.intent.action.PACKAGE_REMOVED
08-30 11:37:20.410  1896  1896 D ActionManagerService: notifyUserLog: 1000001
08-30 11:37:20.411  3835  4499 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-30 11:37:20.411  3835  4499 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-30 11:37:20.411  3835  4499 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
08-30 11:37:20.411  3835  4499 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
08-30 11:37:20.412  3835  3853 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-30 11:37:20.415  6767  6767 D PackageIntentReceiver: Not supported Hotkey customization function 
,08-30 11:37:20.416  2025  2025 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
08-30 11:37:20.416  2025  2025 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
08-30 11:37:20.418  2025  2025 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
08-30 11:37:20.418  2025  2025 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-30 11:37:20.420  2025  2025 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1472216587976&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
08-30 11:37:20.420  2025  2025 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1472216587976&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-30 11:37:20.421  6767  6767 D HideNavigationAppsReceiver: Receive package name : com.test.thalitest, replacing=false, action=android.intent.action.PACKAGE_REMOVED
08-30 11:37:20.421  6767  6767 D HideNavigationAppsReceiver: replacing : false
08-30 11:37:20.423  6767  6767 D HideNavigationAppsReceiver: Delete mPackageMame : com.test.thalitest
08-30 11:37:20.427  6767  6767 D ButtonCombinationReceiver: Receive package name : com.test.thalitest
08-30 11:37:20.427  6767  6767 D ButtonCombinationReceiver: replacing : false
,08-30 11:37:20.451  4620  8349 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,08-30 11:37:20.479  1028  1567 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=8351 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-30 11:37:20.484  1028  1878 I ActivityManager: Killing 7261:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,08-30 11:37:20.491  1028  1932 V SIM_STK : Menu title from STK is T-Mobile
,08-30 11:37:20.497  4620  8349 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
--------- beginning of crash
08-30 11:37:20.500  4620  8349 E AndroidRuntime: FATAL EXCEPTION: IntentService[UpdateCorporaService]
08-30 11:37:20.500  4620  8349 E AndroidRuntime: Process: com.google.android.googlequicksearchbox:search, PID: 4620
08-30 11:37:20.500  4620  8349 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-30 11:37:20.500  4620  8349 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-30 11:37:20.500  4620  8349 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:560)
08-30 11:37:20.500  4620  8349 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-30 11:37:20.500  4620  8349 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-30 11:37:20.500  4620  8349 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-30 11:37:20.500  4620  8349 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
08-30 11:37:20.500  4620  8349 E AndroidRuntime: 	at csx.d(PG:186)
08-30 11:37:20.500  4620  8349 E AndroidRuntime: 	at cun.g(PG:594)
08-30 11:37:20.500  4620  8349 E AndroidRuntime: 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(PG:301)
08-30 11:37:20.500  4620  8349 E AndroidRuntime: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:328)
08-30 11:37:20.500  4620  8349 E AndroidRuntime: 	at android.content.ContentResolver.update(ContentResolver.java:1349)
08-30 11:37:20.500  4620  8349 E AndroidRuntime: 	at cuw.Tg(PG:368)
08-30 11:37:20.500  4620  8349 E AndroidRuntime: 	at cuy.ub(PG:301)
08-30 11:37:20.500  4620  8349 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(PG:268)
08-30 11:37:20.500  4620  8349 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(PG:186)
08-30 11:37:20.500  4620  8349 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-30 11:37:20.500  4620  8349 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 11:37:20.500  4620  8349 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
08-30 11:37:20.500  4620  8349 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 11:37:20.545  1028  2040 W libprocessgroup: failed to open /acct/uid_10097/pid_7261/cgroup.procs: No such file or directory

```
