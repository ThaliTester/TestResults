#### Test 828946826925cd3_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
08-31 17:06:44.072  2028  2028 D LIA_Service_NativeEventReceiver: onReceive action : android.intent.action.PACKAGE_ADDED = package:com.test.thalitest
08-31 17:06:44.072  2028  2028 I LIA_Service_PlatformUtil: startLIAService() : Trying to start LIA service ...
--------- beginning of system
08-31 17:06:44.074  1042  1762 W libprocessgroup: failed to open /acct/uid_10064/pid_5810/cgroup.procs: No such file or directory
08-31 17:06:44.081  2028  2028 D LIA_Service_LIAService: onStartCommand() : LIAService started! - id :3, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
08-31 17:06:44.133  6479  6479 D PostponalbeReceiver: OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_ADDED'.
08-31 17:06:44.139  6479  6479 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsm.mss.OasPackageScanReceiver.onReceive:-1 android.app.ActivityThread.handleReceiver:2586 
08-31 17:06:44.168  4594  6620 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
08-31 17:06:44.202  1042  2027 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=6621 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-31 17:06:44.220  1042  2248 V SIM_STK : Menu title from STK is T-Mobile
08-31 17:06:44.346  1827  1827 I art     : Explicit concurrent mark sweep GC freed 26430(1796KB) AllocSpace objects, 17(272KB) LOS objects, 51% free, 29MB/61MB, paused 1.687ms total 53.110ms
08-31 17:06:44.361  4594  6620 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 193 ms] updated apps [took 192 ms] 
08-31 17:06:44.437  6621  6621 D DocsApplication: Installing DEX configuration.
08-31 17:06:44.455  6621  6621 D DexInstaller: Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
08-31 17:06:44.459  6621  6621 I PackageInfoHelper: Provided clientMode=RELEASE, packageInfo=PackageInfo{23334c5c com.google.android.apps.docs}
08-31 17:06:44.474  6621  6621 D TAG     : onCreate()
08-31 17:06:44.491  6621  6621 D CrossAppStateProvider: Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
,08-31 17:06:45.294  6660  6660 D AndroidRuntime: 
08-31 17:06:45.294  6660  6660 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-31 17:06:45.299  6660  6660 D AndroidRuntime: CheckJNI is OFF
08-31 17:06:45.369  1827  4758 I Icing   : Indexing 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4 from com.google.android.googlequicksearchbox
08-31 17:06:45.422  1827  4758 D Icing   : Loaded CLD2 Version V2.0 - 20140131
08-31 17:06:45.461   329   408 I ThermalEngine: Thermal-Server: Thermal received msg from  override
08-31 17:06:45.461  3224  6687 I Thermal-Lib: Thermal-Lib-Client: Client request sent
08-31 17:06:45.478  1827  4758 I Icing   : Indexing done 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4
08-31 17:06:45.536  6660  6660 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-31 17:06:45.542  1042  2342 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-31 17:06:45.567  1956  3966 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-31 17:06:45.571  1042  2342 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-31 17:06:45.573  1042  2342 D ActivityManager: setTaskToReturnTo : TaskRecord{29e5a60a #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-31 17:06:45.573  1042  2342 D ActivityManager: setTaskToReturnTo : TaskRecord{29e5a60a #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-31 17:06:45.575  1042  2342 D WindowStateEx: AppWindowTokenEx init.. 
08-31 17:06:45.575   347   417 E GBMv2   : DFP En is all cleared set to be enabled
08-31 17:06:45.623  1042  2342 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6694 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-31 17:06:45.624  6660  6660 D AndroidRuntime: Shutting down VM
08-31 17:06:45.697  1956  3966 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-31 17:06:45.698  1956  3966 D SplitWindowPolicy: topRunningActivity=ActivityInfo{f9c3c98 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-31 17:06:45.699  1956  1972 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-31 17:06:45.699  1956  1972 D SplitWindowPolicy: topRunningActivity=ActivityInfo{358c4cf1 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-31 17:06:45.780  6694  6694 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
,08-31 17:06:45.875  6694  6694 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-31 17:06:45.885  6694  6694 I LibraryLoader: Loading: webviewchromium
08-31 17:06:45.889  6694  6694 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 3976-3980)
,08-31 17:06:45.889  6694  6694 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-31 17:06:45.908  6694  6694 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2107a606}
,08-31 17:06:45.910  6694  6694 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-31 17:06:45.910  6694  6694 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-31 17:06:45.921  6694  6694 I BrowserStartupController: Initializing chromium process, renderers=0
,08-31 17:06:45.923  6694  6694 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-31 17:06:45.934  6694  6694 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,08-31 17:06:45.935  6694  6694 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
08-31 17:06:45.935  6694  6694 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
08-31 17:06:45.949  6694  6694 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-31 17:06:45.949  6694  6694 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-31 17:06:45.949  6694  6694 I Adreno-EGL: Build Date: 12/12/14 금
08-31 17:06:45.949  6694  6694 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-31 17:06:45.949  6694  6694 I Adreno-EGL: Remote Branch: 
08-31 17:06:45.949  6694  6694 I Adreno-EGL: Local Patches: 
08-31 17:06:45.949  6694  6694 I Adreno-EGL: Reconstruct Branch: 
,08-31 17:06:45.954   317   317 V AudioPolicyService: registerClient() client 0xb04104a0, uid 10118
08-31 17:06:45.972  1042  1117 D BluetoothManagerService: Message: 20
08-31 17:06:45.972  1042  1117 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3c830244:true
,08-31 17:06:46.030  6621  6621 D LgDataFeature: LgDataFeature() Constructor: none
08-31 17:06:46.031  6621  6621 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-31 17:06:46.047  6694  6723 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,08-31 17:06:46.049  6694  6694 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
08-31 17:06:46.076  6694  6694 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-31 17:06:46.081  6694  6694 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-31 17:06:46.090  6694  6694 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-31 17:06:46.093  6694  6694 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-31 17:06:46.093  6694  6694 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
,08-31 17:06:46.106  6694  6694 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
08-31 17:06:46.115  6694  6694 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-31 17:06:46.115  6694  6694 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-31 17:06:46.147  6694  6740 D OpenGLRenderer: Render dirty regions requested: true
08-31 17:06:46.147  6694  6740 I OpenGLRenderer: Initialized EGL, version 1.4
08-31 17:06:46.158  6694  6740 D OpenGLRenderer: Enabling debug mode 0
,08-31 17:06:46.166  6694  6694 D Atlas   : Validating map...
08-31 17:06:46.170  1042  1762 D SplitWindow: check instance of lgWin Window{1385d5e u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-31 17:06:46.224  6122  6122 I LockScreenSettings: New app installed broadcast received ..
,08-31 17:06:46.226  6122  6122 I LockScreenSettings: Number of installed packages  1
08-31 17:06:46.234  6694  6738 D LgDataFeature: LgDataFeature() Constructor: none
08-31 17:06:46.234  6694  6738 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-31 17:06:46.254  6621  6621 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,08-31 17:06:46.286  1042  1058 V SIM_STK : Menu title from STK is T-Mobile
,08-31 17:06:46.314  6694  6694 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@262d9c8d time:104406
,08-31 17:06:46.346  1042  1954 I ActivityManager: Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=6762 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-31 17:06:46.349  1042  1118 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +653ms (total +773ms)
08-31 17:06:46.350  1042  1118 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{51aee7b u0 com.test.thalitest/.MainActivity t6} time:104441
,08-31 17:06:46.412  6762  6762 D EulaProviderUpdateObserver: action : android.intent.action.PACKAGE_ADDED
08-31 17:06:46.412  6762  6762 D EulaProviderUpdateObserver: uri : package:com.test.thalitest
,08-31 17:06:46.413  6694  6694 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-31 17:06:46.458  1042  2342 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.BNRAppInstallReceiver: pid=6783 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
08-31 17:06:46.459  6694  6694 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-31 17:06:46.459  6694  6694 I chromium: 
08-31 17:06:46.460  1042  2342 I ActivityManager: Killing 5477:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
08-31 17:06:46.482  6694  6738 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-31 17:06:46.482  6694  6738 I chromium: 
,08-31 17:06:46.520  1042  2046 W libprocessgroup: failed to open /acct/uid_10005/pid_5477/cgroup.procs: No such file or directory
,08-31 17:06:46.573  6694  6800 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435169792
,08-31 17:06:46.585  6694  6800 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-31 17:06:46.585  6694  6800 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-31 17:06:46.585  6694  6800 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-31 17:06:46.585  6694  6800 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-31 17:06:46.585  6694  6800 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-31 17:06:46.585  6694  6800 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1dd92bc1 added. We now have 1 listener(s)
08-31 17:06:46.590  1042  1057 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 17:06:46.593  6694  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-31 17:06:46.594  6694  6800 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-31 17:06:46.595  6694  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 17:06:46.596  6694  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 17:06:46.601  6783  6783 D [BNRAppListMgrReceiver]: android.intent.action.PACKAGE_ADDED : com.test.thalitest
,08-31 17:06:46.603  6694  6800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-31 17:06:46.603  6694  6800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-31 17:06:46.603  6694  6800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-31 17:06:46.603  6694  6800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-31 17:06:46.603  6694  6800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-31 17:06:46.603  6694  6800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-31 17:06:46.603  6694  6800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-31 17:06:46.603  6694  6800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-31 17:06:46.603  6694  6800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-31 17:06:46.603  6694  6800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-31 17:06:46.603  6694  6800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-31 17:06:46.603  6694  6800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-31 17:06:46.603  6694  6800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-31 17:06:46.603  6694  6800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-31 17:06:46.603  6694  6800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1aeed354 added. We now have 1 listener(s)
08-31 17:06:46.604  6694  6800 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 17:06:46.608  1042  1529 D WifiService: New client listening to asynchronous messages
08-31 17:06:46.612  6694  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-31 17:06:46.612  6694  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-31 17:06:46.613  6694  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-31 17:06:46.613  6694  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-31 17:06:46.613  6694  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-31 17:06:46.618  6694  6800 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 17:06:46.619  1042  2341 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 17:06:46.620  6694  6800 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-31 17:06:46.628  6783  6783 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-31 17:06:46.629  6479  6479 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.intent.action.PACKAGE_ADDED'.
08-31 17:06:46.635  6694  6800 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-31 17:06:46.635  6694  6800 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 17:06:46.635  6694  6800 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 17:06:46.635  6694  6800 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 17:06:46.635  6694  6800 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 17:06:46.635  6694  6800 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 17:06:46.635  6694  6800 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 17:06:46.635  6694  6800 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 17:06:46.635  6694  6800 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 17:06:46.635  6694  6800 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-31 17:06:46.635  6694  6800 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 17:06:46.638  6694  6694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 17:06:46.638  6694  6800 I io.jxcore.node.LifeCycleMonitor: start: OK
08-31 17:06:46.640  6694  6694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 17:06:46.676  1042  1955 I ActivityManager: Killing 5850:com.google.android.talk/u0a72 (adj 15): empty #17
,08-31 17:06:46.683  6694  6694 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
08-31 17:06:46.759   347   419 E GBMv2   : DFP En is all cleared set to be enabled
08-31 17:06:46.759   347   419 E GBMv2   : Set value is all cleared set the max
08-31 17:06:46.759   347   419 I GBMv2   : DFP Enabled. Ignore VFP set
,08-31 17:06:46.760  1042  2342 W libprocessgroup: failed to open /acct/uid_10072/pid_5850/cgroup.procs: No such file or directory
08-31 17:06:46.961  2790  2790 I MusicWidget: mDelayedStopHandler : unbind
,08-31 17:06:46.966  2168  2168 I MusicBrowser: [MediaPlaybackService.java:2869:onUnbind()] oooooo 
08-31 17:06:46.966  2168  2168 I MusicBrowser: [MediaPlaybackService.java:2076:saveQueue()] oooooo {full=true}
08-31 17:06:46.967  2168  2168 I MusicBrowser: [MediaPlaybackService.java:2081:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
08-31 17:06:46.972  2168  2168 D MusicBrowser: [MediaPlaybackService.java:2161:saveQueue()] oooooo {queue=}
08-31 17:06:46.972  2168  2168 D MusicBrowser: [MediaPlaybackService.java:2163:saveQueue()] oooooo {mCardId=-1}
08-31 17:06:46.973  2168  2168 D MusicBrowser: [MediaPlaybackService.java:2198:saveQueue()] oooooo {curpos=-1}
,08-31 17:06:46.979  2168  2168 I MusicBrowser: [MediaPlaybackService.java:2046:onDestroy()] oooooo 
08-31 17:06:46.979  2168  2168 I MusicBrowser: [MediaPlaybackService.java:8635:clearReceiver()] oooooo 
08-31 17:06:46.981  1042  1561 I MediaFocusControl:  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@2c755db7com.lge.music.MediaPlaybackService$5@2310d924
08-31 17:06:46.982  2168  2168 D MusicBrowser: [MediaPlaybackService.java:8669:clearReceiver()] oooooo abandonAudioFocus : 1
08-31 17:06:46.982  2168  2168 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-31 17:06:46.983  2168  2168 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-31 17:06:46.983  2168  2168 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-31 17:06:46.984  2168  2168 I MusicBrowser: [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$27@b681c92
08-31 17:06:46.984  2168  2168 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-31 17:06:46.985  2168  2168 I MusicBrowser: [MusicUtils.java:6801:endNotiTimer()] oooooo endNotiTimer
08-31 17:06:46.986  2168  2168 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-31 17:06:46.986  2168  2168 I MusicBrowser: [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
08-31 17:06:46.986  2168  2168 I MusicBrowser: [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
08-31 17:06:46.987  2168  2168 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
,08-31 17:06:46.987  2168  2168 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-31 17:06:46.988  2168  2168 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-31 17:06:46.989  2168  2168 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-31 17:06:46.989  2168  2168 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-31 17:06:46.991  2168  2168 I MusicBrowser: [MusicUtils.java:10406:isAKACoverSupported()] oooooo aka not support!
08-31 17:06:46.992  2168  2168 I MusicBrowser: [MediaPlaybackService.java:6704:release()] oooooo 
,08-31 17:06:46.993  2168  2168 I MusicBrowser: [MediaPlaybackService.java:6665:stop()] oooooo 
08-31 17:06:46.993  2168  2168 V MediaPlayer[Native]: reset
08-31 17:06:46.999  2168  2168 V MediaPlayer[Native]: setListener
08-31 17:06:46.999  2168  2168 V MediaPlayer[Native]: disconnect
08-31 17:06:46.999  2168  2168 V MediaPlayer[Native]: destructor
08-31 17:06:47.000   317   317 V AudioFlinger: releasing 18 from 2168 for -1
08-31 17:06:47.000   317   317 V AudioFlinger:  decremented refcount to 0
08-31 17:06:47.000   317   317 V AudioFlinger: purging stale effects
08-31 17:06:47.000  2168  2168 V MediaPlayer[Native]: disconnect
08-31 17:06:47.001  2168  2168 D MusicBrowser: [MusicUtils.java:615:getSmartShareVersion()] oooooo versionCode:305000
,08-31 17:06:47.002  2168  2168 I SmartShareClient: [SmartShareManagerClient] smartshare client supported version code: 305000
08-31 17:06:47.003  2168  2168 I SmartShareClient: [SmartShareManagerClient] smartshare client enabled
08-31 17:06:47.003  2168  2168 I MusicBrowser: [MusicUtils.java:787:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000018
08-31 17:06:47.003  2168  2168 I MusicBrowser: [MusicUtils.java:635:getSmartShareVersion()] oooooo SmartshareVersion:953
08-31 17:06:47.004  2168  2168 V MusicBrowser: [MediaPlaybackService.java:9312:terminateSmartShareClient()] oooooo 
08-31 17:06:47.004  2168  2168 I SmartShareClient: [SmartShareManagerClient] unregisterListener: 640523405
08-31 17:06:47.004  2168  2168 W SmartShareClient: [SmartShareManagerClient] unregisterListener invalid listener: 640523405
08-31 17:06:47.008  2168  2168 I SmartShareClient: [SmartShareManagerClient] terminate service: 2168/MediaPlaybackService/836162120
08-31 17:06:47.011  2168  2168 E HomeCloudIF: unregiterHomeCloudBroadcast(), Illegal argument.
08-31 17:06:47.011  2168  2168 I SmartShareClient: [SmartShareManagerClient] unbindService context:android.app.Application@92cce42
08-31 17:06:47.014  2168  2168 V CloudHub: [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.2.1, versionCode=202001, state=0
,08-31 17:06:47.014  2168  2168 V CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
08-31 17:06:47.015  2168  2168 I CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
08-31 17:06:47.015  2168  2168 D MusicBrowser: [MediaPlaybackService.java:9007:setStopForeground()] oooooo bValue : true
08-31 17:06:47.017  1042  1728 I ActivityManager: Killing 5651:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
08-31 17:06:47.018  2168  2168 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29997
08-31 17:06:47.033  5626  5626 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
08-31 17:06:47.034  5626  5626 W System.err: android.os.DeadObjectException
08-31 17:06:47.035  5626  5626 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
,08-31 17:06:47.035  5626  5626 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-31 17:06:47.035  5626  5626 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-31 17:06:47.035  5626  5626 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-31 17:06:47.035  5626  5626 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-31 17:06:47.035  5626  5626 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-31 17:06:47.035  5626  5626 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-31 17:06:47.036  5626  5626 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
,08-31 17:06:47.036  5626  5626 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-31 17:06:47.036  5626  5626 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-31 17:06:47.036  5626  5626 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 17:06:47.036  5626  5626 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 17:06:47.036  5626  5626 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-31 17:06:47.036  5626  5626 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-31 17:06:47.037  5626  5626 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-31 17:06:47.037  5626  5626 W System.err: android.os.DeadObjectException
08-31 17:06:47.038  5626  5626 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-31 17:06:47.038  5626  5626 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-31 17:06:47.038  5626  5626 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-31 17:06:47.039  5626  5626 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-31 17:06:47.039  5626  5626 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-31 17:06:47.039  5626  5626 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-31 17:06:47.039  5626  5626 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-31 17:06:47.039  5626  5626 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-31 17:06:47.039  5626  5626 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-31 17:06:47.039  5626  5626 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-31 17:06:47.039  5626  5626 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 17:06:47.039  5626  5626 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 17:06:47.039  5626  5626 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-31 17:06:47.040  5626  5626 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-31 17:06:47.040  5626  5626 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-31 17:06:47.041  5626  5626 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
08-31 17:06:47.249  1042  2342 W libprocessgroup: failed to open /acct/uid_1000/pid_5651/cgroup.procs: No such file or directory
08-31 17:06:47.250  1042  2342 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,08-31 17:06:47.267  5626  5626 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-31 17:06:47.267  5626  5626 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-31 17:06:47.329  1042  2341 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=6814 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-31 17:06:47.330  5626  5626 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-31 17:06:47.438  6814  6814 D UEI.SmartControl: Quickset Services start...
,08-31 17:06:47.443  6814  6814 I UEI.SmartControl: Manufacture = LGE
08-31 17:06:47.443  6814  6814 D UEI.SmartControl: Id = LGNevo
08-31 17:06:47.447  6814  6814 D UEI.SmartControl: File observer start...
08-31 17:06:47.449  6814  6814 E UEI.SmartControl: IR Port is disabled: false
08-31 17:06:47.449  6814  6814 D UEI.SmartControl: Starting file observer...
,08-31 17:06:47.450  6814  6814 D UEI.SmartControl: Extracting JNI libs...
08-31 17:06:47.450  6814  6814 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
08-31 17:06:47.513  6694  6804 W jxcore-log: Initializing JXcore engine
,08-31 17:06:47.513  6694  6804 W jxcore-log: JXcore engine is ready
08-31 17:06:47.594  6804  6804 W Thread-752: type=1400 audit(0.0:162): avc: denied { ioctl } for path="socket:[7565]" dev="sockfs" ino=7565 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,08-31 17:06:47.594  6804  6804 W Thread-752: type=1400 audit(0.0:163): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-31 17:06:47.594  6804  6804 W Thread-752: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[10051]" dev="sockfs" ino=10051 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-31 17:06:47.594  6804  6804 W Thread-752: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-31 17:06:47.594  6804  6804 W Thread-752: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[31895]" dev="sockfs" ino=31895 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
08-31 17:06:47.610  6814  6814 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
08-31 17:06:47.610  6814  6814 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-31 17:06:47.610  6814  6814 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
08-31 17:06:47.634  6694  6804 W jxcore-log: Starting JXcore engine
,08-31 17:06:47.651  6814  6814 I UEI.SmartControl: --- Selecting new region: 6
08-31 17:06:47.654  6814  6814 I UEI.SmartControl: Model = LG-D855
08-31 17:06:47.656  6814  6814 D UEI.SmartControl: QS Service created
,08-31 17:06:47.672  6814  6814 I UEI.SmartControl: Service initServices...
08-31 17:06:47.677  6814  6814 D UEI.SmartControl: QS start get config
,08-31 17:06:47.728  6814  6814 D UEI.SmartControl: Loading JNI Libs...
,08-31 17:06:47.739  6694  6804 W jxcore-log: Platform android
08-31 17:06:47.739  6694  6804 W jxcore-log: 
,08-31 17:06:47.739  6694  6804 W jxcore-log: Process ARCH arm
08-31 17:06:47.739  6694  6804 W jxcore-log: 
08-31 17:06:47.928  6694  6804 I jxcore-log: JXcore Cordova bridge is ready!
08-31 17:06:47.928  6694  6804 I jxcore-log: 
08-31 17:06:47.928  6694  6804 W jxcore-log: JXcore engine is started
,08-31 17:06:47.938  6694  6800 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-31 17:06:47.946  6694  6694 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-31 17:06:47.967  6814  6814 I UEI.SmartControl: Supports setup maps: true
,08-31 17:06:47.970  6814  6814 D UEI.SmartControl: QS start statue = true Error code = 0
08-31 17:06:47.970  6814  6814 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-31 17:06:47.970  6814  6814 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-31 17:06:47.971  6814  6814 I UEI.SmartControl: ### init IR Blaster...
08-31 17:06:47.975  6814  6814 D serial_port: Configuring serial port
08-31 17:06:47.978  6814  6814 E UEI.SmartControl: UEIBLaster setting for 616
08-31 17:06:47.978  6814  6814 I UEI.SmartControl: Setting serial record hearder size = 2
08-31 17:06:47.978  6814  6814 I UEI.SmartControl: configuring settings for MAXQ616
08-31 17:06:47.979  6814  6814 I UEI.SmartControl: Get version...
08-31 17:06:47.996  6814  6841 D UEI.SmartControl: serial port data available: 21
,08-31 17:06:48.024  6814  6814 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-31 17:06:48.024  6814  6814 I UEI.SmartControl: IR Blaster version: 256702256704300002
,08-31 17:06:48.025  6814  6814 I UEI.SmartControl: QS saving settings...
08-31 17:06:48.026  6814  6814 D UEI.SmartControl: IR Blaster version: 25672567
08-31 17:06:48.042  6814  6841 D UEI.SmartControl: serial port data available: 4
,08-31 17:06:48.081  6814  6844 I UEI.SmartControl: Device manager: loading config....
,08-31 17:06:48.081  6814  6844 D UEI.SmartControl: ----------- loading internal config...
,08-31 17:06:48.087  6814  6814 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-31 17:06:48.091  6814  6814 E UEI.SmartControl: Services init done
08-31 17:06:48.091  6814  6814 D UEI.SmartControl: QS Service init finished
08-31 17:06:48.092  6814  6814 D UEI.SmartControl: QS Service version name: 2.1.91
08-31 17:06:48.093  6814  6814 D UEI.SmartControl: QS Service version code: 201091
08-31 17:06:48.094  6814  6814 D UEI.SmartControl: Service requested: Control
,08-31 17:06:48.104  6814  6844 E UEI.SmartControl: Loading SETTINGS...
,08-31 17:06:48.109  6814  6814 D UEI.SmartControl: Request IControl service: devices are loaded...
,08-31 17:06:48.112  1042  1762 I ActivityManager: Killing 5626:com.lge.qremote/u0a112 (adj 15): empty #17
08-31 17:06:48.116  6814  6844 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-31 17:06:48.138  6814  6843 I UEI.SmartControl: Notify AllClients services are ready: 0
08-31 17:06:48.138  6814  6843 D UEI.SmartControl: -----service ready thread exits
,08-31 17:06:48.201  1042  1918 W libprocessgroup: failed to open /acct/uid_10112/pid_5626/cgroup.procs: No such file or directory
08-31 17:06:48.201  6814  6814 D UEI.SmartControl: Internal service binding...
,08-31 17:06:50.175  6621  6621 W GAV2    : Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,08-31 17:06:50.176  1042  2027 I ActivityManager: Killing 6284:com.android.calendar/u0a13 (adj 15): empty #17
08-31 17:06:50.280  1042  2248 W libprocessgroup: failed to open /acct/uid_10013/pid_6284/cgroup.procs: No such file or directory
,08-31 17:06:51.117  6621  6734 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,08-31 17:06:53.082  6814  6845 D UEI.SmartControl: Internal timer expired: 1
,08-31 17:06:53.082  6814  6845 D UEI.SmartControl: unbind internal service
,08-31 17:06:53.099  6814  6814 D UEI.SmartControl: Service.onUnbind: IControl
,08-31 17:06:53.101  6814  6814 D UEI.SmartControl: Service.onDestroy
08-31 17:06:53.102  6814  6814 D UEI.SmartControl: Lock is in USE false
08-31 17:06:53.102  6814  6814 D UEI.SmartControl: unbind internal service
08-31 17:06:53.103  6814  6842 D serial_port: close(fd = 25)
08-31 17:06:53.106  6814  6842 I UEI.SmartControl: Serial port is closed.
08-31 17:06:53.106  6814  6814 I UEI.SmartControl: Serial port is closed.
08-31 17:06:53.106  6814  6814 I UEI.SmartControl: Serial port is closed.
08-31 17:06:53.107  6814  6814 D UEI.SmartControl: Blaster closed
08-31 17:06:53.107  6814  6814 D UEI.SmartControl: Shut down QS...
08-31 17:06:53.107  6814  6814 D UEI.SmartControl: Stopping QS lib
08-31 17:06:53.107  6814  6814 D UEI.SmartControl: QS lib stop result = true
08-31 17:06:53.107  6814  6814 D UEI.SmartControl: Stopped QS lib
08-31 17:06:53.108  6814  6814 D UEI.SmartControl: Stopped file observer...
08-31 17:06:53.108  6814  6814 D UEI.SmartControl: QS shutdown complete
,08-31 17:06:53.433  1827  6528 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,08-31 17:06:53.439   313  6855 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,08-31 17:06:53.440   313  6855 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
,08-31 17:06:53.440   313  6855 D libc-netbsd: res_queryN name = android.clients.google.com succeed
08-31 17:06:53.668  1827  1827 I ConfigFetchService: fetch service done; releasing wakelock
,08-31 17:06:53.677  1827  1827 I ConfigFetchService: stopping self
08-31 17:06:53.686  2230  2230 I ConfigService: onDestroy
,08-31 17:06:57.029  2168  2168 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19987
,08-31 17:06:57.446  6694  6804 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-31 17:06:57.446  6694  6804 I jxcore-log: 
,08-31 17:06:57.449  6694  6804 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-31 17:06:57.449  6694  6804 I jxcore-log: 
,08-31 17:06:57.452  6694  6804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 17:06:57.452  6694  6804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 17:06:57.452  6694  6804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 17:06:57.452  6694  6804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 17:06:57.452  6694  6804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 17:06:57.452  6694  6804 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 17:06:57.452  6694  6804 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 17:06:57.452  6694  6804 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 17:06:57.454  6694  6804 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-31 17:06:57.456  6694  6804 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-31 17:06:57.456  6694  6804 I jxcore-log: 
,08-31 17:06:57.458  6694  6804 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-31 17:06:57.458  6694  6804 I jxcore-log: 
,08-31 17:06:57.958  6694  6804 D executeNativeTests: Running unit tests
,08-31 17:06:58.040  6694  6804 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 17:06:58.040  6694  6804 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@14801051 added. We now have 2 listener(s)
,08-31 17:06:58.041  1042  2341 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 17:06:58.043  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-31 17:06:58.043  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 17:06:58.043  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 17:06:58.043  6694  6804 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 17:06:58.043  6694  6804 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f25d0b6 added. We now have 2 listener(s)
08-31 17:06:58.043  6694  6804 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 17:06:58.043  6694  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-31 17:06:58.044  6694  6804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 17:06:58.047  6694  6804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 17:06:58.047  6694  6804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 17:06:58.047  6694  6804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 17:06:58.047  6694  6804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 17:06:58.047  6694  6804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 17:06:58.047  6694  6804 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 17:06:58.047  6694  6804 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 17:06:58.047  6694  6804 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 17:06:58.048  6694  6804 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 17:06:58.048  6694  6804 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 17:06:58.049  6694  6694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 17:06:58.050  6694  6694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 17:06:58.053  6694  6804 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-31 17:06:58.053  6694  6804 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-31 17:06:58.053  6694  6804 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-31 17:06:58.055  6694  6804 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-31 17:06:58.057  6694  6804 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed,
08-31 17:06:58.057  6694  6804 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-31 17:06:58.057  6694  6804 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-31 17:06:58.057  6694  6804 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-31 17:06:58.058  6694  6804 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-31 17:06:58.059  6694  6804 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 17:06:58.059  6694  6804 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 17:06:58.060  6694  6804 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 17:06:58.060  6694  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 17:06:58.060  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 17:06:58.060  6694  6804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 17:06:58.060  6694  6804 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@14801051 removed from the list
08-31 17:06:58.060  6694  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:06:58.060  6694  6804 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f25d0b6 removed from the list
,08-31 17:06:58.060  6694  6804 D io.jxcore.node.ConnectivityMonitor: stop
08-31 17:06:58.060  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:06:58.061  6694  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:06:58.061  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:06:58.062  6694  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-31 17:06:58.062  6694  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 17:06:58.062  6694  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:06:58.062  6694  6804 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f25d0b6 not in the list
08-31 17:06:58.063  6694  6804 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-31 17:06:58.064  6694  6804 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-31 17:06:58.064  6694  6804 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 17:06:58.064  6694  6804 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 17:06:58.064  6694  6804 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 17:06:58.064  6694  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 17:06:58.064  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:06:58.064  6694  6804 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@14801051 not in the list
08-31 17:06:58.064  6694  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:06:58.064  6694  6804 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f25d0b6 not in the list
08-31 17:06:58.064  6694  6804 D io.jxcore.node.ConnectivityMonitor: stop
,08-31 17:06:58.064  6694  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:06:58.064  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:06:58.064  6694  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:06:58.064  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:06:58.065  6694  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
08-31 17:06:58.065  6694  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 17:06:58.065  6694  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:06:58.065  6694  6804 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f25d0b6 not in the list
08-31 17:06:58.069  6694  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-31 17:06:58.069  6694  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-31 17:06:58.069  6694  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-31 17:06:58.069  6694  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-31 17:06:58.069  6694  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-31 17:06:58.069  6694  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410],
08-31 17:06:58.069  6694  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-31 17:06:58.069  6694  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-31 17:06:58.069  6694  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-31 17:06:58.069  6694  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-31 17:06:58.069  6694  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,08-31 17:06:58.069  6694  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-31 17:06:58.070  6694  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-31 17:06:58.070  6694  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-31 17:06:58.070  6694  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,08-31 17:06:58.070  6694  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-31 17:06:58.070  6694  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-31 17:06:58.070  6694  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-31 17:06:58.070  6694  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-31 17:06:58.070  6694  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,08-31 17:06:58.070  6694  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-31 17:06:58.070  6694  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-31 17:06:58.070  6694  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110],
08-31 17:06:58.070  6694  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,08-31 17:06:58.070  6694  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-31 17:06:58.070  6694  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-31 17:06:58.070  6694  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-31 17:06:58.070  6694  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,08-31 17:06:58.070  6694  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-31 17:06:58.070  6694  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-31 17:06:58.070  6694  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-31 17:06:58.070  6694  6804 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 17:06:58.070  6694  6804 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything,
08-31 17:06:58.070  6694  6804 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 17:06:58.070  6694  6804 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 17:06:58.070  6694  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:06:58.070  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 17:06:58.070  6694  6804 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@14801051 not in the list
08-31 17:06:58.070  6694  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:06:58.070  6694  6804 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f25d0b6 not in the list
,08-31 17:06:58.070  6694  6804 D io.jxcore.node.ConnectivityMonitor: stop
08-31 17:06:58.070  6694  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:06:58.070  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:06:58.070  6694  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 17:06:58.070  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
08-31 17:06:58.071  6694  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 17:06:58.071  6694  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 17:06:58.071  6694  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-31 17:06:58.071  6694  6804 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f25d0b6 not in the list
08-31 17:06:58.071  6694  6804 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-31 17:06:58.073  6694  6804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 17:06:58.074  6694  6804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
08-31 17:06:58.074  6694  6804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 17:06:58.074  6694  6804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 17:06:58.074  6694  6804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 17:06:58.074  6694  6804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 17:06:58.074  6694  6804 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 17:06:58.074  6694  6804 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 17:06:58.074  6694  6804 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 17:06:58.075  6694  6804 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-31 17:06:58.075  6694  6804 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 17:06:58.076  6694  6694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 17:06:58.077  6694  6694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
08-31 17:06:58.078  6694  6804 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 17:06:58.078  6694  6804 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-31 17:06:58.078  6694  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-31 17:06:58.078  6694  6804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 17:06:58.078  6694  6804 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-31 17:06:58.081  6694  6804 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-31 17:06:58.081  1042  2342 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-31 17:06:58.084  6694  6804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false,
08-31 17:06:58.088  6694  6804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-31 17:06:58.089  6694  6804 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
08-31 17:06:58.089  6694  6804 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...,
08-31 17:06:58.090  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 17:06:58.091  6694  6804 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-31 17:06:58.091  6694  6804 I io.jxcore.node.ConnectionHelper: start: OK
08-31 17:06:58.093  6694  6804 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-31 17:06:58.093  6694  6804 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 17:06:58.093  6694  6804 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 17:06:58.093  6694  6804 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 17:06:58.093  6694  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:06:58.093  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-31 17:06:58.093  6694  6804 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@14801051 not in the list
08-31 17:06:58.093  6694  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:06:58.093  6694  6804 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f25d0b6 not in the list
08-31 17:06:58.093  6694  6804 D io.jxcore.node.ConnectivityMonitor: stop
08-31 17:06:58.093  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
08-31 17:06:58.093  6694  6804 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-31 17:06:58.095  6694  6804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 17:06:58.097  6694  6804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 17:06:58.097  6694  6804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 17:06:58.097  6694  6804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 17:06:58.097  6694  6804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 17:06:58.097  6694  6804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true,
08-31 17:06:58.097  6694  6804 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 17:06:58.097  6694  6804 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 17:06:58.097  6694  6804 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 17:06:58.097  6694  6804 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 17:06:58.097  6694  6804 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 17:06:58.099  6694  6694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
08-31 17:06:58.099  6694  6694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 17:06:58.100  6694  6804 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only,
08-31 17:06:58.100  6694  6804 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-31 17:06:58.100  6694  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-31 17:06:58.100  6694  6804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 17:06:58.100  6694  6804 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-31 17:06:58.103  6694  6804 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-31 17:06:58.103  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 17:06:58.104  6694  6804 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-31 17:06:58.104  6694  6804 I io.jxcore.node.ConnectionHelper: start: OK
,08-31 17:06:58.105  6694  6804 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 17:06:58.105  6694  6804 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 17:06:58.105  6694  6804 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 17:06:58.105  6694  6804 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 17:06:58.106  6694  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 17:06:58.106  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 17:06:58.106  6694  6804 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@14801051 not in the list
08-31 17:06:58.106  6694  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:06:58.106  6694  6804 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f25d0b6 not in the list
08-31 17:06:58.106  6694  6804 D io.jxcore.node.ConnectivityMonitor: stop,
08-31 17:06:58.106  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:06:58.106  6694  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:06:58.106  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:06:58.106  6694  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 17:06:58.107  6694  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
08-31 17:06:58.108  6694  6804 D BluetoothLeScanner: could not find callback wrapper
08-31 17:06:58.108  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 17:06:58.108  6694  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:06:58.108  6694  6804 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f25d0b6 not in the list
08-31 17:06:58.109  6694  6804 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false,
08-31 17:06:58.110  6694  6804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 17:06:58.112  6694  6804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 17:06:58.112  6694  6804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 17:06:58.112  6694  6804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 17:06:58.112  6694  6804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 17:06:58.112  6694  6804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 17:06:58.112  6694  6804 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e,
08-31 17:06:58.112  6694  6804 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 17:06:58.112  6694  6804 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 17:06:58.113  6694  6804 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e,
08-31 17:06:58.113  6694  6804 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 17:06:58.114  6694  6694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 17:06:58.115  6694  6694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 17:06:58.115  6694  6804 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-31 17:06:58.116  6694  6804 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-31 17:06:58.116  6694  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-31 17:06:58.116  6694  6804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 17:06:58.116  6694  6804 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-31 17:06:58.119  6694  6804 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...,
08-31 17:06:58.119  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 17:06:58.120  6694  6804 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-31 17:06:58.120  6694  6804 I io.jxcore.node.ConnectionHelper: start: OK
08-31 17:06:58.120  6694  6804 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 17:06:58.120  6694  6804 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything,
08-31 17:06:58.120  6694  6804 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 17:06:58.121  6694  6804 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 17:06:58.121  6694  6804 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 17:06:58.121  6694  6804 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-31 17:06:58.121  6694  6804 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 17:06:58.121  6694  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:06:58.121  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 17:06:58.121  6694  6804 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@14801051 not in the list
08-31 17:06:58.121  6694  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-31 17:06:58.121  6694  6804 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f25d0b6 not in the list
08-31 17:06:58.121  6694  6804 D io.jxcore.node.ConnectivityMonitor: stop
08-31 17:06:58.121  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:06:58.121  6694  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-31 17:06:58.121  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:06:58.122  6694  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 17:06:58.122  6694  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 17:06:58.122  6694  6804 D BluetoothLeScanner: could not find callback wrapper
,08-31 17:06:58.122  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 17:06:58.122  6694  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:06:58.122  6694  6804 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f25d0b6 not in the list
08-31 17:06:58.123  6694  6804 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-31 17:06:58.123  6694  6804 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-31 17:06:58.123  6694  6804 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 17:06:58.123  6694  6804 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 17:06:58.123  6694  6804 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 17:06:58.123  6694  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:06:58.123  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 17:06:58.123  6694  6804 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@14801051 not in the list
08-31 17:06:58.123  6694  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:06:58.123  6694  6804 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f25d0b6 not in the list
08-31 17:06:58.123  6694  6804 D io.jxcore.node.ConnectivityMonitor: stop
,08-31 17:06:58.124  6694  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:06:58.124  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:06:58.124  6694  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:06:58.124  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 17:06:58.125  6694  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
,08-31 17:06:58.125  6694  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 17:06:58.125  6694  6804 D BluetoothLeScanner: could not find callback wrapper
08-31 17:06:58.125  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 17:06:58.125  6694  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-31 17:06:58.125  6694  6804 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f25d0b6 not in the list
08-31 17:06:58.126  6694  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming],
08-31 17:06:58.126  6694  6804 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 17:06:58.126  6694  6804 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything,
,08-31 17:06:58.126  6694  6804 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 17:06:58.127  6694  6804 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 17:06:58.127  6694  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 17:06:58.127  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:06:58.127  6694  6804 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@14801051 not in the list
08-31 17:06:58.127  6694  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-31 17:06:58.127  6694  6804 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f25d0b6 not in the list
08-31 17:06:58.127  6694  6804 D io.jxcore.node.ConnectivityMonitor: stop
08-31 17:06:58.127  6694  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 17:06:58.127  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
,08-31 17:06:58.127  6694  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:06:58.127  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:06:58.127  6694  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-31 17:06:58.128  6694  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 17:06:58.128  6694  6804 D BluetoothLeScanner: could not find callback wrapper
08-31 17:06:58.128  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 17:06:58.128  6694  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-31 17:06:58.128  6694  6804 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f25d0b6 not in the list
08-31 17:06:58.128  6694  6804 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-31 17:06:58.129  6694  6804 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 17:06:58.129  6694  6804 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-31 17:06:58.129  6694  6804 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 17:06:58.129  6694  6804 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 17:06:58.129  6694  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:06:58.129  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
08-31 17:06:58.129  6694  6804 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@14801051 not in the list
08-31 17:06:58.129  6694  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-31 17:06:58.129  6694  6804 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f25d0b6 not in the list
08-31 17:06:58.129  6694  6804 D io.jxcore.node.ConnectivityMonitor: stop
08-31 17:06:58.129  6694  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:06:58.129  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 17:06:58.129  6694  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:06:58.129  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:06:58.130  6694  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 17:06:58.130  6694  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 17:06:58.130  6694  6804 D BluetoothLeScanner: could not find callback wrapper
08-31 17:06:58.130  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-31 17:06:58.130  6694  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:06:58.130  6694  6804 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f25d0b6 not in the list
08-31 17:06:58.131  6694  6804 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-31 17:06:58.131  6694  6804 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 17:06:58.131  6694  6804 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 17:06:58.131  6694  6804 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-31 17:06:58.131  6694  6804 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 17:06:58.131  6694  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:06:58.131  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:06:58.131  6694  6804 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@14801051 not in the list
08-31 17:06:58.131  6694  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:06:58.131  6694  6804 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f25d0b6 not in the list
,08-31 17:06:58.131  6694  6804 D io.jxcore.node.ConnectivityMonitor: stop
08-31 17:06:58.131  6694  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:06:58.131  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:06:58.131  6694  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:06:58.131  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:06:58.132  6694  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 17:06:58.132  6694  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 17:06:58.132  6694  6804 D BluetoothLeScanner: could not find callback wrapper
,08-31 17:06:58.132  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 17:06:58.132  6694  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:06:58.132  6694  6804 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f25d0b6 not in the list
08-31 17:06:58.133  6694  6804 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-31 17:06:58.133  6694  6804 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-31 17:06:58.133  6694  6804 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-31 17:06:58.133  6694  6804 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-31 17:06:58.133  6694  6804 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-31 17:06:58.133  6694  6804 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-31 17:06:58.133  6694  6804 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 17:06:58.133  6694  6804 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-31 17:06:58.133  6694  6804 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 17:06:58.133  6694  6804 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 17:06:58.133  6694  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:06:58.133  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:06:58.134  6694  6804 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@14801051 not in the list
08-31 17:06:58.134  6694  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-31 17:06:58.134  6694  6804 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f25d0b6 not in the list
08-31 17:06:58.134  6694  6804 D io.jxcore.node.ConnectivityMonitor: stop
08-31 17:06:58.134  6694  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:06:58.134  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:06:58.134  6694  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 17:06:58.134  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:06:58.134  6694  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 17:06:58.134  6694  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 17:06:58.135  6694  6804 D BluetoothLeScanner: could not find callback wrapper
08-31 17:06:58.135  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-31 17:06:58.135  6694  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:06:58.135  6694  6804 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f25d0b6 not in the list
08-31 17:06:58.135  6694  6804 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-31 17:06:58.135  6694  6804 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55,
08-31 17:06:58.135  6694  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-31 17:06:58.137  6694  6804 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-31 17:06:58.137  6694  6804 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-31 17:06:58.137  6694  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-31 17:06:58.137  6694  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110],
08-31 17:06:58.137  6694  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-31 17:06:58.137  6694  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-31 17:06:58.137  6694  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-31 17:06:58.137  6694  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-31 17:06:58.137  6694  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610],
08-31 17:06:58.137  6694  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-31 17:06:58.137  6694  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-31 17:06:58.137  6694  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-31 17:06:58.138  6694  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,08-31 17:06:58.138  6694  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-31 17:06:58.138  6694  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-31 17:06:58.138  6694  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-31 17:06:58.138  6694  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,08-31 17:06:58.138  6694  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-31 17:06:58.138  6694  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-31 17:06:58.138  6694  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-31 17:06:58.138  6694  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,08-31 17:06:58.138  6694  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-31 17:06:58.138  6694  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-31 17:06:58.138  6694  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-31 17:06:58.138  6694  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-31 17:06:58.138  6694  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-31 17:06:58.138  6694  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-31 17:06:58.138  6694  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-31 17:06:58.138  6694  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-31 17:06:58.138  6694  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-31 17:06:58.138  6694  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-31 17:06:58.138  6694  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-31 17:06:58.138  6694  6804 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-31 17:06:58.138  6694  6804 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-31 17:06:58.138  6694  6804 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-31 17:06:58.138  6694  6804 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-31 17:06:58.138  6694  6804 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-31 17:06:58.138  6694  6804 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-31 17:06:58.139  6694  6804 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-31 17:06:58.139  6694  6804 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-31 17:06:58.139  6694  6804 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-31 17:06:58.141  6694  6804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-31 17:06:58.141  6694  6804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-31 17:06:58.141  6694  6804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-31 17:06:58.142  6694  6804 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-31 17:06:58.142  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-31 17:06:58.142  6694  6804 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-31 17:06:58.142  6694  6804 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-31 17:06:58.142  6694  6804 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-31 17:06:58.143  6694  6804 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 17:06:58.143  6694  6804 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 17:06:58.143  6694  6804 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 17:06:58.144  6694  6856 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 816)
08-31 17:06:58.148  6694  6804 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 17:06:58.148  6694  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:06:58.148  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:06:58.149  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-31 17:06:58.149  6694  6804 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@14801051 not in the list
08-31 17:06:58.149  6694  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:06:58.149  6694  6804 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f25d0b6 not in the list
08-31 17:06:58.149  6694  6804 D io.jxcore.node.ConnectivityMonitor: stop
08-31 17:06:58.149  6694  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:06:58.149  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:06:58.149  6694  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:06:58.149  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:06:58.150  6694  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 17:06:58.150  6694  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 17:06:58.150  6694  6804 D BluetoothLeScanner: could not find callback wrapper
08-31 17:06:58.150  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 17:06:58.150  6694  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:06:58.150  6694  6804 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f25d0b6 not in the list
08-31 17:06:58.151  6694  6804 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-31 17:06:58.151  6694  6804 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 17:06:58.152  6694  6804 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 17:06:58.152  6694  6804 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 17:06:58.152  6694  6804 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 17:06:58.152  6694  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:06:58.152  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:06:58.152  6694  6804 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@14801051 not in the list
08-31 17:06:58.152  6694  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:06:58.152  6694  6804 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f25d0b6 not in the list
08-31 17:06:58.152  6694  6804 D io.jxcore.node.ConnectivityMonitor: stop
08-31 17:06:58.152  6694  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:06:58.152  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:06:58.152  6694  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:06:58.152  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:06:58.153  6694  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 17:06:58.153  6694  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 17:06:58.154  6694  6804 D BluetoothLeScanner: could not find callback wrapper
08-31 17:06:58.154  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 17:06:58.154  6694  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:06:58.154  6694  6804 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f25d0b6 not in the list
08-31 17:06:58.155  6694  6804 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-31 17:06:58.155  6694  6804 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 17:06:58.155  6694  6804 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 17:06:58.155  6694  6804 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 17:06:58.156  6694  6804 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 17:06:58.156  6694  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:06:58.156  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:06:58.156  6694  6804 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@14801051 not in the list
08-31 17:06:58.156  6694  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:06:58.156  6694  6804 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f25d0b6 not in the list
08-31 17:06:58.156  6694  6804 D io.jxcore.node.ConnectivityMonitor: stop
08-31 17:06:58.156  6694  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:06:58.156  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:06:58.157  6694  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:06:58.157  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:06:58.157  6694  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 17:06:58.157  6694  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 17:06:58.158  6694  6804 D BluetoothLeScanner: could not find callback wrapper
08-31 17:06:58.158  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 17:06:58.158  6694  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:06:58.158  6694  6804 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f25d0b6 not in the list
08-31 17:06:58.160  6694  6804 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-31 17:06:58.160  6694  6804 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-31 17:06:58.160  6694  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-31 17:06:58.160  6694  6804 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-31 17:06:58.160  6694  6804 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-31 17:06:58.160  6694  6804 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-31 17:06:58.160  6694  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-31 17:06:58.160  6694  6804 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-31 17:06:58.160  6694  6804 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-31 17:06:58.160  6694  6804 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-31 17:06:58.160  6694  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-31 17:06:58.160  6694  6804 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-31 17:06:58.160  6694  6804 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 17:06:58.160  6694  6804 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 17:06:58.160  6694  6804 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 17:06:58.169  6694  6857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 816
08-31 17:06:58.169  6694  6857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 816)
08-31 17:06:58.169  6694  6857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 816)
08-31 17:06:58.169  6694  6804 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 17:06:58.169  6694  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:06:58.169  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:06:58.170  6694  6804 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@14801051 not in the list
08-31 17:06:58.170  6694  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:06:58.170  6694  6804 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f25d0b6 not in the list
08-31 17:06:58.170  6694  6804 D io.jxcore.node.ConnectivityMonitor: stop
08-31 17:06:58.170  6694  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:06:58.170  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:06:58.170  6694  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:06:58.170  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:06:58.171  6694  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 17:06:58.171  6694  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 17:06:58.171  6694  6804 D BluetoothLeScanner: could not find callback wrapper
08-31 17:06:58.171  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 17:06:58.171  6694  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:06:58.171  6694  6804 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f25d0b6 not in the list
08-31 17:06:58.188  6694  6804 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 17:06:58.188  6694  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:06:58.189  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:06:58.189  6694  6804 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@14801051 not in the list
08-31 17:06:58.189  6694  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:06:58.189  6694  6804 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f25d0b6 not in the list
08-31 17:06:58.189  6694  6804 D io.jxcore.node.ConnectivityMonitor: stop
08-31 17:06:58.189  6694  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:06:58.189  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 17:06:58.192  6694  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:06:58.193  6694  6804 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f25d0b6 not in the list
08-31 17:06:58.193  6694  6804 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 17:06:58.193  6694  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:06:58.193  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:06:58.193  6694  6804 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@14801051 not in the list
08-31 17:06:58.193  6694  6804 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 17:06:58.193  6694  6804 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 17:06:58.193  6694  6804 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 17:06:58.193  6694  6804 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 17:06:58.193  6694  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:06:58.193  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:06:58.193  6694  6804 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@14801051 not in the list
08-31 17:06:58.193  6694  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:06:58.193  6694  6804 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f25d0b6 not in the list
08-31 17:06:58.193  6694  6804 D io.jxcore.node.ConnectivityMonitor: stop
08-31 17:06:58.193  6694  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:06:58.193  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:06:58.193  6694  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:06:58.193  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:06:58.198  6694  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 17:06:58.198  6694  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 17:06:58.198  6694  6804 D BluetoothLeScanner: could not find callback wrapper
08-31 17:06:58.199  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 17:06:58.199  6694  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:06:58.199  6694  6804 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f25d0b6 not in the list
08-31 17:06:58.200  6694  6804 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-31 17:06:58.200  6694  6804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 17:06:58.200  6694  6804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-31 17:06:58.201  6694  6804 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-31 17:06:58.201  6694  6804 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-31 17:06:58.201  6694  6804 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-31 17:06:58.201  6694  6694 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-31 17:06:58.201  6694  6804 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-31 17:06:58.202  6694  6804 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 17:06:58.202  6694  6804 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-31 17:06:58.202  6694  6804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-31 17:06:58.203  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-31 17:06:58.203  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:06:58.203  6694  6804 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-31 17:06:58.203  6694  6694 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-31 17:06:58.203  6694  6804 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@14801051 not in the list
08-31 17:06:58.203  6694  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:06:58.203  6694  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-31 17:06:58.203  6694  6804 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-31 17:06:58.203  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-31 17:06:58.204  6694  6804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-31 17:06:58.204  6694  6869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-31 17:06:58.204  6694  6869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-31 17:06:58.205  6694  6804 D BluetoothLeScanner: could not find callback wrapper
08-31 17:06:58.205  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 17:06:58.205  6694  6804 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-31 17:06:58.206  6694  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:06:58.206  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:06:58.206  6694  6804 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 17:06:58.207  6694  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 17:06:58.207  6694  6804 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f25d0b6 not in the list
08-31 17:06:58.207  6694  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 17:06:58.207  6694  6804 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 17:06:58.207  6694  6804 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 17:06:58.207  6694  6694 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-31 17:06:58.207  6694  6804 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 17:06:58.207  6694  6804 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 17:06:58.207  6694  6694 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 17:06:58.207  6694  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:06:58.207  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:06:58.207  6694  6804 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@14801051 not in the list
08-31 17:06:58.207  6694  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:06:58.207  6694  6804 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f25d0b6 not in the list
08-31 17:06:58.207  6694  6804 D io.jxcore.node.ConnectivityMonitor: stop
08-31 17:06:58.207  6694  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:06:58.207  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:06:58.207  6694  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:06:58.207  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:06:58.208  6694  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 17:06:58.208  6694  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 17:06:58.208  6694  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:06:58.208  6694  6804 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f25d0b6 not in the list
08-31 17:06:58.209  6694  6804 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-31 17:06:58.209  6694  6804 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-31 17:06:58.209  6694  6804 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-31 17:06:58.209  6694  6804 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-31 17:06:58.209  6694  6804 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 17:06:58.210  6694  6804 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 17:06:58.210  6694  6804 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 17:06:58.210  6694  6804 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 17:06:58.210  6694  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:06:58.210  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:06:58.210  6694  6804 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@14801051 not in the list
08-31 17:06:58.210  6694  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:06:58.213  6694  6804 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f25d0b6 not in the list
08-31 17:06:58.213  6694  6804 D io.jxcore.node.ConnectivityMonitor: stop
08-31 17:06:58.213  6694  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:06:58.213  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:06:58.213  6694  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:06:58.213  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:06:58.214  6694  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 17:06:58.214  6694  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 17:06:58.214  6694  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:06:58.214  6694  6804 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f25d0b6 not in the list
08-31 17:06:58.215  1042  1955 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 17:06:58.216  1042  1728 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 17:06:58.216  1042  1058 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 17:06:58.217  6694  6804 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 17:06:58.217  6694  6804 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 17:06:58.217  6694  6804 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 17:06:58.218  6694  6804 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 17:06:58.218  6694  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:06:58.218  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:06:58.218  6694  6804 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@14801051 not in the list
08-31 17:06:58.218  6694  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:06:58.218  6694  6804 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f25d0b6 not in the list
08-31 17:06:58.218  6694  6804 D io.jxcore.node.ConnectivityMonitor: stop
08-31 17:06:58.218  6694  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:06:58.218  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:06:58.218  6694  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:06:58.218  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:06:58.219  6694  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 17:06:58.219  6694  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 17:06:58.219  6694  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:06:58.219  6694  6804 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f25d0b6 not in the list
08-31 17:06:58.220  6694  6804 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 17:06:58.220  6694  6804 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 17:06:58.220  6694  6804 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 17:06:58.221  6694  6804 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 17:06:58.221  6694  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:06:58.221  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:06:58.221  6694  6804 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@14801051 not in the list
08-31 17:06:58.221  6694  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:06:58.221  6694  6804 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f25d0b6 not in the list
08-31 17:06:58.221  6694  6804 D io.jxcore.node.ConnectivityMonitor: stop
08-31 17:06:58.221  6694  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:06:58.221  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:06:58.221  6694  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:06:58.221  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:06:58.222  6694  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 17:06:58.222  6694  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 17:06:58.222  6694  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:06:58.222  6694  6804 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f25d0b6 not in the list
08-31 17:06:58.224  6694  6804 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-31 17:06:58.224  6694  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-31 17:06:58.224  6694  6804 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-31 17:06:58.224  6694  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-31 17:06:58.224  6694  6804 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-31 17:06:58.224  6694  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,08-31 17:06:58.227  6694  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-31 17:06:58.227  6694  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-31 17:06:58.228  6694  6804 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-31 17:06:58.228  6694  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-31 17:06:58.228  6694  6804 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-31 17:06:58.228  6694  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-31 17:06:58.228  6694  6804 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-31 17:06:58.228  6694  6804 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-31 17:06:58.229  6694  6804 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-31 17:06:58.229  6694  6804 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-31 17:06:58.230  6694  6804 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-31 17:06:58.230  6694  6804 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-31 17:06:58.230  6694  6804 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-31 17:06:58.230  6694  6804 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-31 17:06:58.232  6694  6804 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 17:06:58.232  6694  6804 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@73cf0af added. We now have 2 listener(s)
08-31 17:06:58.232  6694  6804 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 17:06:58.233  6694  6804 D BluetoothAdapter: enable(): BT is already enabled..!
08-31 17:06:58.234  1042  1057 D WifiServiceImplEx: setWifiEnabled: true pid=6694, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-31 17:06:58.234  1042  1057 D WifiService: setWifiEnabled: true pid=6694, uid=10118
08-31 17:06:58.234  1042  1057 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-31 17:06:58.235  6694  6804 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 17:06:58.235  6694  6804 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3ca1fcbc added. We now have 3 listener(s)
08-31 17:06:58.235  6694  6804 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 17:06:58.239  6694  6804 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 17:06:58.239  6694  6804 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@21621445 added. We now have 4 listener(s)
08-31 17:06:58.239  6694  6804 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 17:06:58.241  6694  6804 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 17:06:58.241  6694  6804 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b4dd79a added. We now have 5 listener(s)
08-31 17:06:58.241  6694  6804 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 17:06:58.243  1042  1057 D WifiServiceImplEx: setWifiEnabled: false pid=6694, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-31 17:06:58.243  1042  1057 D WifiService: setWifiEnabled: false pid=6694, uid=10118
08-31 17:06:58.243  1042  1057 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-31 17:06:58.261  1042  2046 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 17:06:58.261  1042  2046 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@2a6dfc2b mBinding = false
08-31 17:06:58.261  1042  1042 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-31 17:06:58.262  1042  1042 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-31 17:06:58.262  1042  1042 D Ulp_jni : JNI:system_update. Event-4
08-31 17:06:58.262  1042  1523 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-31 17:06:58.262  1042  1523 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-31 17:06:58.263  1042  1523 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-31 17:06:58.263  1042  1523 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-31 17:06:58.263  1042  1523 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-31 17:06:58.263  1042  1523 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-31 17:06:58.263  1042  1523 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-31 17:06:58.263  1042  1523 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-31 17:06:58.264  1042  1523 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-31 17:06:58.264  1042  1523 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-31 17:06:58.266  6694  6856 W LGMDMUISystemServiceAdapter: checkBluetoothPairing btPolicy: false
08-31 17:06:58.267  6694  6856 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 816)
08-31 17:06:58.273  1042  1523 D WifiNative-wlan0: SAVE_CONFIG: returned true
,08-31 17:06:58.273  1042  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-31 17:06:58.274  1042  1522 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-31 17:06:58.274  1042  1522 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-31 17:06:58.274  2686  2686 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-31 17:06:58.274  1042  1523 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-31 17:06:58.274  1042  1523 D WifiNative-wlan0: doBoolean: SET ps 1
08-31 17:06:58.275  1042  1523 D WifiNative-wlan0: SET ps 1: returned true
08-31 17:06:58.276  1042  2839 D DhcpStateMachine: RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-31 17:06:58.277  1042  1042 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-31 17:06:58.277  1042  1042 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-31 17:06:58.277  1042  1042 D Ulp_jni : JNI:system_update. Event-4
08-31 17:06:58.278  1042  1117 D BluetoothManagerService: Message: 2
08-31 17:06:58.278  1042  1117 D BluetoothManagerService: Sending off request.
08-31 17:06:58.279  6694  6804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 17:06:58.279  3870  3889 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-31 17:06:58.279  3870  3948 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-31 17:06:58.279  3870  3948 D BluetoothAdapterProperties: Setting state to 13
08-31 17:06:58.279   313   893 D CommandListener: Clearing all IP addresses on wlan0
08-31 17:06:58.279  3870  3948 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-31 17:06:58.280  3870  3948 D BluetoothAdapterProperties: onBluetoothDisable()
08-31 17:06:58.280  1042  1117 D BluetoothManagerService: Message: 60
08-31 17:06:58.280  3870  3948 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-31 17:06:58.280  1042  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-31 17:06:58.280  1042  1117 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-31 17:06:58.282  1956  1956 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-31 17:06:58.282  1589  1589 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-31 17:06:58.284  3870  3870 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-31 17:06:58.284  3870  3870 D BluetoothMapService: STATE_TURNING_OFF
08-31 17:06:58.284  3870  3870 V BluetoothMapService: Handler(): got msg=4
08-31 17:06:58.284  3870  3870 D BluetoothMapService: MAP Service closeService in
08-31 17:06:58.284  3870  3870 D BluetoothMapMasInstance: MAP Service shutdown
,08-31 17:06:58.287  3870  4266 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-31 17:06:58.287  3870  4266 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-31 17:06:58.287  3870  4266 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-31 17:06:58.287  3870  4266 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-31 17:06:58.287  3870  4266 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-31 17:06:58.287  3870  4266 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-31 17:06:58.287  3870  4266 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-31 17:06:58.287  3870  4266 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-31 17:06:58.287  3870  3870 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-31 17:06:58.287  3870  3870 V BluetoothMapService: MAP Service closeService out
08-31 17:06:58.288  3870  3870 V BtOppService: Receiver DISABLED_ACTION 
08-31 17:06:58.288  3870  3870 I BtOppRfcommListener: stopping Accept Thread
08-31 17:06:58.288  3870  3870 V BtOppRfcommListener: close mBtServerSocket
08-31 17:06:58.288  3870  3870 V BtOppRfcommListener: waiting for thread to terminate
08-31 17:06:58.289  3870  4326 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-31 17:06:58.289  3870  4326 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-31 17:06:58.289  3870  3870 V BtOppRfcommListener: done waiting for thread to terminate
08-31 17:06:58.291  6694  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 17:06:58.291  6694  6804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 17:06:58.291  6694  6804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 17:06:58.291  6694  6804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 17:06:58.291  6694  6804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 17:06:58.291  6694  6804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 17:06:58.291  6694  6804 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 17:06:58.291  6694  6804 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 17:06:58.291  6694  6804 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 17:06:58.291  6694  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 17:06:58.291  6694  6804 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 17:06:58.292  6694  6804 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 17:06:58.294  6694  6694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 17:06:58.299  6694  6694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 17:06:58.304  6694  6694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 17:06:58.304  6694  6694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 17:06:58.304  6694  6694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 17:06:58.304  6694  6694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 17:06:58.304  6694  6694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 17:06:58.304  6694  6694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 17:06:58.304  6694  6694 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 17:06:58.304  6694  6694 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 17:06:58.304  6694  6694 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 17:06:58.304  6694  6694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 17:06:58.304  6694  6694 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 17:06:58.306  6694  6694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 17:06:58.316  1042  2027 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
,08-31 17:06:58.316  1042  2836 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-31 17:06:58.316  1042  2836 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-31 17:06:58.316  1042  2836 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-31 17:06:58.316  1042  2836 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=4 target=com.android.internal.util.StateMachine$SmHandler }
08-31 17:06:58.316  1042  2836 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-31 17:06:58.318  1042  1530 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-31 17:06:58.318  1042  1530 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
08-31 17:06:58.320   313  6873 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-31 17:06:58.321  1042  1115 D DSQN    : Dns fail occured do internet check.
08-31 17:06:58.322  1042  1042 D DSQN    : EVENT_INTERNET_CHECK_REQUEST received
08-31 17:06:58.322  1042  1042 D DSQN    : try Internet connection check
08-31 17:06:58.331  1042  2836 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
08-31 17:06:58.332  1042  1110 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6878 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-31 17:06:58.332  3870  3952 D BluetoothAdapterProperties: Scan Mode:20
08-31 17:06:58.332  3870  3948 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-31 17:06:58.333  3870  4289 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-31 17:06:58.334  3870  4068 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-31 17:06:58.334  3870  4068 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-31 17:06:58.334  3870  4068 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-31 17:06:58.334  3870  4068 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-31 17:06:58.334  3870  4068 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-31 17:06:58.334  3870  4068 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-31 17:06:58.334  3870  4068 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-31 17:06:58.334  3870  4068 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-31 17:06:58.334  3870  4068 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-31 17:06:58.334  3870  4068 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-31 17:06:58.334  3870  4068 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-31 17:06:58.334  3870  4068 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-31 17:06:58.334  3870  4068 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-31 17:06:58.335  3870  4068 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-31 17:06:58.335  3870  4327 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-31 17:06:58.335  3870  4330 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-31 17:06:58.337  1042  1523 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 17:06:58.337  1042  1523 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 17:06:58.337  1042  1523 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 17:06:58.337  1042  1523 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 17:06:58.337  1042  1523 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 17:06:58.338  1042  1522 D LGWifiP2pService: InactiveState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-31 17:06:58.338  1042  1523 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 17:06:58.338  1042  1522 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-31 17:06:58.338  1042  1522 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@22e4214
08-31 17:06:58.338  3870  3948 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-31 17:06:58.338  1042  1522 D LGWifiP2pService: P2pDisablingState
08-31 17:06:58.339  1042  1522 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-31 17:06:58.339  1042  1522 D LGWifiP2pService: p2p socket connection lost
08-31 17:06:58.339  3870  3870 V BtOppService: onDestroy
08-31 17:06:58.340  1042  1523 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-31 17:06:58.340  1042  1522 D LGWifiP2pService: P2pDisabledState
08-31 17:06:58.340  1042  1523 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-31 17:06:58.340  1042  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-31 17:06:58.340  1042  1522 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-31 17:06:58.340  2686  2686 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-31 17:06:58.340  1042  1522 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-31 17:06:58.341  1042  1523 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-31 17:06:58.341  1042  1523 D WifiNative-wlan0: doBoolean: SET ps 1
08-31 17:06,:58.341  1042  1523 D WifiNative-wlan0: SET ps 1: returned true
08-31 17:06:58.343  1042  1042 D WifiHS20: hidePasspointNotification off =false
08-31 17:06:58.344  1956  1956 V WfdStateTracker: handleWifiStateChangedEvent: 0
,08-31 17:06:58.346  1042  1042 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 17:06:58.346  1042  1042 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 17:06:58.347  1042  1042 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-31 17:06:58.347  1042  1042 D WifiHS20: hidePasspointNotification off =false
08-31 17:06:58.348  6694  6694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 17:06:58.348  6694  6694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 17:06:58.348  6694  6694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 17:06:58.348  6694  6694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 17:06:58.348  6694  6694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 17:06:58.348  6694  6694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 17:06:58.348  6694  6694 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 17:06:58.348  6694  6694 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 17:06:58.348  6694  6694 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 17:06:58.349  1042  1042 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 17:06:58.349  1042  1042 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 17:06:58.349  1042  1042 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-31 17:06:58.349  6694  6694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 17:06:58.349  6694  6694 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-31 17:06:58.349  1042  1042 D WifiScanningService: SCAN_AVAILABLE : 1
08-31 17:06:58.349  1042  1542 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-31 17:06:58.349  1042  1042 D RttService: SCAN_AVAILABLE : 1
08-31 17:06:58.350  1042  1543 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-31 17:06:58.351  6694  6694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 17:06:58.351  6694  6694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 17:06:58.351  6694  6694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 17:06:58.351  6694  6694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 17:06:58.351  6694  6694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 17:06:58.351  6694  6694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 17:06:58.351  6694  6694 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 17:06:58.351  6694  6694 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 17:06:58.351  6694  6694 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-,31 17:06:58.351  6694  6694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 17:06:58.352  6694  6694 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-31 17:06:58.352  1956  1956 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-31 17:06:58.352  1956  1956 D WfdsService: WifiP2pState is changed : false
08-31 17:06:58.352  1956  2323 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-31 17:06:58.352  1956  2323 D WfdsService: Set the WFDS Monitor: false
08-31 17:06:58.353  1956  2323 D WfdsMonitor: WFDS Monitor is stopped
08-31 17:06:58.353  1956  2323 D WfdsService: STATE : WfdsDisabledState - enter
08-31 17:06:58.353  1956  2752 D CtrlSupplicant: Received on exit socket, terminate
08-31 17:06:58.353  1956  2752 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-31 17:06:58.353  1956  2752 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-31 17:06:58.353  1956  2752 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-31 17:06:58.354  1956  2324 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-31 17:06:58.354  1956  2323 W WfdsService: DefaultState - msg [9445378] is not handled
08-31 17:06:58.359  1042  1530 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-31 17:06:58.359  1042  1530 D DSQN    : disableDataServiceNotify
08-31 17:06:58.359  1042  1530 D DSQN    : stop dsqn bin
,08-31 17:06:58.360   313   893 D CommandListener: Clearing all IP addresses on wlan0
08-31 17:06:58.363   313  6894 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-31 17:06:58.363  1042  6876 D DSQN    : ThreadTCPConnectionCheck DNS fail internet is not possible
08-31 17:06:58.364  1042  6875 D DSQN    : ThreadInternetCheck internet check NOK 
08-31 17:06:58.364  1042  1115 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-31 17:06:58.364  1042  6875 D DSQN    : InternetcheckProgress is not set don't send DS quality intent
08-31 17:06:58.372  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 17:06:58.372  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 17:06:58.373  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-31 17:06:58.375  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 17:06:58.375  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 17:06:58.375  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 17:06:58.376  1042  1530 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-31 17:06:58.376  1042  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 17:06:58.376  1042  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 17:06:58.376  1042  1530 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 17:06:58.377  1042  1530 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-31 17:06:58.377  1589  1799 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-31 17:06:58.377  1042  2836 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-31 17:06:58.377  1042  2836 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-31 17:06:58.377  1042  1530 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-31 17:06:58.377  1042  2836 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-31 17:06:58.377  1042  1530 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-31 17:06:58.377  1042  1530 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-31 17:06:58.388  1042  1110 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6898 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-31 17:06:58.390  1042  1523 D WifiNative-p2p0: doBoolean: TERMINATE
08-31 17:06:58.390  3870  3870 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-31 17:06:58.390  1042  1523 D WifiNative-p2p0: TERMINATE: returned true
08-31 17:06:58.390  1042  1523 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-31 17:06:58.390  1042  1523 E WifiStateMachine: useWiFiOffloading() : false
08-31 17:06:58.390  1042  1523 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-31 17:06:58.396  1042  1042 D WifiHS20: hidePasspointNotification off =false
08-31 17:06:58.396  1042  1042 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 17:06:58.396  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-31 17:06:58.396  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 17:06:58.396  1042  1042 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 17:06:58.396  1042  1042 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-31 17:06:58.398  1956  1956 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-31 17:06:58.404  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 17:06:58.404  1042  1530 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-31 17:06:58.404  1042  1530 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-31 17:06:58.404  1042  1521 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-31 17:06:58.405  1042  1042 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-31 17:06:58.405  1042  1042 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-31 17:06:58.405  1042  1042 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-31 17:06:58.405  1042  1042 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-31 17:06:58.405  1042  1042 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
,08-31 17:06:58.408  1042  1530 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-31 17:06:58.408  1042  1530 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 17:06:58.408  1042  1530 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 17:06:58.409  1042  1523 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 17:06:58.409  1042  1523 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-31 17:06:58.411  1042  1521 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-31 17:06:58.411  1042  1530 D NetworkManagementService: Removing idletimer
08-31 17:06:58.411  1042  1530 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 17:06:58.412  1042  1042 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-31 17:06:58.412  1042  1042 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-31 17:06:58.412  1042  1042 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-31 17:06:58.412  1866  1866 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 17:06:58.412  1866  1866 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-31 17:06:58.412  1042  1530 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-31 17:06:58.412  1042  1042 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-31 17:06:58.413  1042  1042 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-31 17:06:58.413  1042  1042 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-31 17:06:58.414  6694  6694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 17:06:58.414  6694  6694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 17:06:58.414  6694  6694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 17:06:58.414  6694  6694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 17:06:58.414  6694  6694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 17:06:58.414  6694  6694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 17:06:58.414  6694  6694 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 17:06:58.414  6694  6694 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 17:06:58.414  6694  6694 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 17:06:58.414  6694  6694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 17:06:58.414  6694  6694 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 17:06:58.418  6694  6694 W org,.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 17:06:58.418  6694  6694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 17:06:58.418  6694  6694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 17:06:58.418  6694  6694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 17:06:58.418  6694  6694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 17:06:58.418  6694  6694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 17:06:58.418  6694  6694 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 17:06:58.418  6694  6694 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 17:06:58.418  6694  6694 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 17:06:58.419  6694  6694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 17:06:58.419  6694  6694 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-31 17:06:58.429  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-31 17:06:58.445  1589  1589 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-31 17:06:58.445  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 17:06:58.446  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-31 17:06:58.457  1589  1589 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-31 17:06:58.458  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 17:06:58.458  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 17:06:58.483  1042  2027 I art     : Explicit concurrent mark sweep GC freed 44626(2MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/65MB, paused 1.389ms total 85.655ms
,08-31 17:06:58.497  6878  6878 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-31 17:06:58.497  6878  6878 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
08-31 17:06:58.497  6878  6878 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-31 17:06:58.498  6878  6878 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
08-31 17:06:58.499  6878  6878 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-31 17:06:58.499  6878  6878 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-31 17:06:58.503  2686  2686 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,08-31 17:06:58.503  2686  2686 I wpa_supplicant: monitor socket send errors count : 1
08-31 17:06:58.503  2686  2686 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1956-2\x00 that cannot receive messages
08-31 17:06:58.504  1042  2750 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-31 17:06:58.504  1042  2750 D WifiMonitor: Dropping event because (p2p0) is stopped
08-31 17:06:58.523  1042  1110 I ActivityManager: Waited long enough for: ServiceRecord{b36a720 u0 com.google.android.gms/.wearable.service.WearableService}
,08-31 17:06:58.527  1042  2839 D DhcpStateMachine: StoppedState
08-31 17:06:58.527  1042  2839 D DhcpStateMachine: StoppedState{ when=-186ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-31 17:06:58.528  1042  1523 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-31 17:06:58.529  1042  1523 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-31 17:06:58.529  6898  6898 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-31 17:06:58.529  6898  6898 W LG Account v2.2: No ProfileInfo entries
08-31 17:06:58.529  6898  6898 I LG Account v2.2: isEnabled: false
08-31 17:06:58.529  6898  6898 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-31 17:06:58.529  6898  6898 I Feature : [Lifetracker]Country: EU
08-31 17:06:58.529  6898  6898 I Feature : [Lifetracker]Operator: OPEN
08-31 17:06:58.529  6898  6898 I Feature : [Lifetracker]Ranking support: false
08-31 17:06:58.529  6898  6898 I Feature : [Lifetracker]Comfort support: false
08-31 17:06:58.529  6898  6898 I Feature : [Lifetracker]Accessory: true
08-31 17:06:58.529  6898  6898 I Feature : [Lifetracker]Health device: true
08-31 17:06:58.530  6898  6898 I Feature : [Lifetracker]Extra Pedometer: false
08-31 17:06:58.530  6898  6898 I Feature : [Lifetracker]Blood glucose device: false
08-31 17:06:58.530  6898  6898 I Feature : [Lifetracker]Device Number: 3
08-31 17:06:58.537  6479  6479 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-31 17:06:58.541  2686  2686 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-31 17:06:58.542  1042  2750 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-31 17:06:58.542  1042  2750 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-31 17:06:58.542  1042  2750 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-31 17:06:58.542  1042  1117 D Tethering: InitialState.processMessage what=4
08-31 17:06:58.542  2686  2686 W wpa_supplicant: USIM:  scard_deinit function
08-31 17:06:58.542  1042  2750 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-31 17:06:58.542  1042  2750 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-31 17:06:58.543  1042  2750 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-31 17:06:58.543  1042  1523 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=116619
08-31 17:06:58.543  1042  1523 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=116619
08-31 17:06:58.543  1042  1523 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=116619  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-31 17:06:58.544  1042  1523 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=116620  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-31 17:06:58.566  1042  1728 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6917 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-31 17:06:58.567  1042  1728 I ActivityManager: Killing 6238:com.android.providers.calendar/u0a14 (adj 15): empty #17
,08-31 17:06:58.587  6878  6878 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-31 17:06:58.609  2686  2686 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,08-31 17:06:58.609  1042  2750 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-31 17:06:58.609  1042  2750 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
08-31 17:06:58.610  1042  2750 D WifiMonitor: Disconnecting from the supplicant, no more events
08-31 17:06:58.610  1042  1117 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-31 17:06:58.610  1042  1058 W libprocessgroup: failed to open /acct/uid_10014/pid_6238/cgroup.procs: No such file or directory
08-31 17:06:58.610  1042  1523 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
08-31 17:06:58.618  3870  3870 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-31 17:06:58.619  3870  3870 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-31 17:06:58.619  3870  3870 V BluetoothPbapReceiver: ***********state = 13
08-31 17:06:58.623  3870  3870 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
,08-31 17:06:58.623  1042  1117 D BluetoothManagerService: Message: 20
08-31 17:06:58.623  1042  1117 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@dbfff5d:true
08-31 17:06:58.626  3870  3870 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-31 17:06:58.626  3870  3870 V BluetoothPbapService: state: 13
08-31 17:06:58.626  3870  3870 V BluetoothPbapService: Pbap Service closeService in
08-31 17:06:58.627  2230  2230 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-31 17:06:58.627  3870  3870 V BluetoothPbapService: successfully stopped pbap service
08-31 17:06:58.628  3870  3870 V BluetoothPbapService: Pbap Service closeService out
08-31 17:06:58.628  3870  3870 V BluetoothPbapService: Pbap Service onDestroy
08-31 17:06:58.628  3870  3870 V BluetoothPbapService: Pbap Service closeService in
08-31 17:06:58.628  3870  3870 V BluetoothPbapService: Pbap Service closeService out
08-31 17:06:58.628  3870  3870 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-31 17:06:58.644  1042  1117 D BluetoothManagerService: Message: 30
,08-31 17:06:58.648  1042  1117 D BluetoothManagerService: Message: 30
08-31 17:06:58.651  6878  6878 D LocalBluetoothProfileManager: Adding local MAP profile
08-31 17:06:58.652  6878  6878 D BluetoothMap: Create BluetoothMap proxy object
08-31 17:06:58.653  1042  1117 D BluetoothManagerService: Message: 30
08-31 17:06:58.656  1042  1117 D BluetoothManagerService: Message: 30
08-31 17:06:58.658  6878  6878 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-31 17:06:58.659  6878  6878 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
08-31 17:06:58.660  6917  6917 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-31 17:06:58.663  6917  6917 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-31 17:06:58.663  6917  6917 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-31 17:06:58.665  1042  1762 I ActivityManager: Killing 6349:com.android.defcontainer/u0a4 (adj 15): empty #17
08-31 17:06:58.708  6694  6694 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-31 17:06:58.724  1042  1058 W libprocessgroup: failed to open /acct/uid_10004/pid_6349/cgroup.procs: No such file or directory
,08-31 17:06:58.732  1042  1523 D WifiOffDelayIfNotUsed: stopMonitoring
08-31 17:06:58.732  1042  1523 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-31 17:06:58.732  1042  1523 E WifiStateMachine: useWiFiOffloading() : false
08-31 17:06:58.732  1042  1523 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-31 17:06:58.734  6878  6878 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
08-31 17:06:58.741  6878  6878 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
,08-31 17:06:58.759  6878  6878 D DockEventReceiver: finishStartingService: stopping service
,08-31 17:06:58.771  1956  1956 D WfdsService: Supplicant Connection state is changed : false
08-31 17:06:58.771  1956  2323 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
,08-31 17:06:58.771  1956  2323 D WfdsService: Set the WFDS Monitor: false
08-31 17:06:58.771  1956  2323 D WfdsMonitor: WFDS Monitor is stopped
08-31 17:06:58.772  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 17:06:58.772  1956  1956 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-31 17:06:58.774  6878  6878 D BluetoothInputDevice: Proxy object connected
08-31 17:06:58.775  6878  6878 D HidProfile: Bluetooth service connected
08-31 17:06:58.777  1042  1042 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-31 17:06:58.777  1042  1528 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-31 17:06:58.778  1042  1528 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-31 17:06:58.779  2479  2479 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 17:06:58.780  6878  6878 D BluetoothPan: BluetoothPAN Proxy object connected
08-31 17:06:58.781  6694  6694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 17:06:58.781  6694  6694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 17:06:58.781  6694  6694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 17:06:58.781  6694  6694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 17:06:58.781  6694  6694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 17:06:58.781  6694  6694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 17:06:58.781  6694  6694 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 17:06:58.781  6694  6694 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 17:06:58.781  6694  6694 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 17:06:58.783  6694  6694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 17:06:58.784  6878  6878 D PanProfile: Bluetooth service connected
08-31 17:06:58.785  6878  6878 D BluetoothMap: Proxy object connected
08-31 17:06:58.786  6878  6878 D MapProfile: Bluetooth service connected
08-31 17:06:58.786  6878  6878 D BluetoothMap: getConnectedDevices()
08-31 17:06:58.787  6878  6878 D BluetoothMap: Bluetooth is Not enabled
08-31 17:06:58.799  6878  6878 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 17:06:58.832  6878  6878 D LgDataFeature: LgDataFeature() Constructor: none
08-31 17:06:58.832  6878  6878 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-31 17:06:58.844  6878  6878 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 17:06:58.845  6878  6878 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-31 17:06:58.849  6878  6878 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-31 17:06:58.854  6878  6878 D BluetoothPermissionRequest: onReceive
08-31 17:06:58.858  6878  6878 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-31 17:06:58.869  6878  6878 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-31 17:06:58.870  1042  2011 I ActivityManager: Killing 6533:com.google.android.partnersetup/u0a8 (adj 15): empty #17
08-31 17:06:58.904  3870  3870 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
,08-31 17:06:58.905  3870  3870 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-31 17:06:58.905  1042  1057 W libprocessgroup: failed to open /acct/uid_10008/pid_6533/cgroup.procs: No such file or directory
08-31 17:06:58.906  3870  3870 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-31 17:06:58.936  1042  1523 E WifiStateMachine:  InitialState CMD_TETHER_STATE_CHANGE 0 0
08-31 17:06:58.937  1042  1523 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,08-31 17:06:58.996  1042  2011 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6945 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,08-31 17:06:58.999  3870  3870 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-31 17:06:59.000  3870  3870 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-31 17:06:59.002  3870  3870 V BluetoothFtpService: Ftp Service onStartCommand
08-31 17:06:59.002  3870  3870 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-31 17:06:59.002  3870  3870 V BluetoothFtpService: Ftp Service closeService
08-31 17:06:59.003  3870  3870 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-31 17:06:59.004  3870  3870 V BluetoothFtpService: successfully stopped ftp service
08-31 17:06:59.004  3870  3870 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-31 17:06:59.005  3870  3870 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-31 17:06:59.005  3870  3870 V BluetoothSapReceiver: SapReceiver onReceive 
08-31 17:06:59.005  3870  3870 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-31 17:06:59.005  3870  3870 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-31 17:06:59.005  3870  3870 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-31 17:06:59.007  3870  3870 V BluetoothFtpService: Ftp Service onDestroy
08-31 17:06:59.007  3870  3870 V BluetoothFtpService: Ftp Service closeService
,08-31 17:06:59.067  1042  1983 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6962 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-31 17:06:59.069  3870  3870 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-31 17:06:59.069  3870  3870 V BluetoothSapService: state: 13
08-31 17:06:59.069  3870  3870 V BluetoothSapService: Stopping SAP server process
08-31 17:06:59.070  3870  3870 V BluetoothSapService: Sap Service closeSapService in
08-31 17:06:59.071  3870  3870 V BluetoothSapService: Close listen Socket : 
08-31 17:06:59.071  3870  3870 V BluetoothSapService: Close rfcomm Socket : 
08-31 17:06:59.071  3870  3870 V BluetoothSapService: Close sapd  Socket : 
08-31 17:06:59.081  3870  3870 V BluetoothSapService: Sap Service closeSapService out
08-31 17:06:59.082  3870  3870 V BluetoothSapService: Sap Service onDestroy
08-31 17:06:59.082  3870  3870 V BluetoothSapService: Sap Service closeSapService in
08-31 17:06:59.082  3870  3870 V BluetoothSapService: Close listen Socket : 
08-31 17:06:59.082  3870  3870 V BluetoothSapService: Close rfcomm Socket : 
08-31 17:06:59.082  3870  3870 V BluetoothSapService: Close sapd  Socket : 
,08-31 17:06:59.085  3870  3870 V BluetoothSapService: Sap Service closeSapService out
08-31 17:06:59.087   351   351 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 449us total 21.687ms
08-31 17:06:59.106   351   351 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 372us total 18.647ms
,08-31 17:06:59.111  6945  6945 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-31 17:06:59.123   351   351 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 290us total 16.334ms
,08-31 17:06:59.138  6945  6945 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,08-31 17:06:59.153  6962  6962 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-31 17:06:59.168  6945  6945 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,08-31 17:06:59.169  6945  6945 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
,08-31 17:06:59.169  1042  1955 I ActivityManager: Killing 6011:com.lge.appbox.client/u0a11 (adj 15): empty #17
08-31 17:06:59.169  6945  6945 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
,08-31 17:06:59.170  6945  6945 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-31 17:06:59.170  6945  6945 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-31 17:06:59.172  6945  6945 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-31 17:06:59.177  6945  6945 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-31 17:06:59.211  1042  1762 W libprocessgroup: failed to open /acct/uid_10011/pid_6011/cgroup.procs: No such file or directory
,08-31 17:06:59.221  6945  6945 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 17:06:59.227  6945  6945 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-31 17:06:59.260  6945  6945 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-31 17:06:59.263  6479  6479 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 17:06:59.268  6945  6945 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-31 17:06:59.270  6917  6917 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-31 17:06:59.270  6917  6917 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-31 17:06:59.271  6917  6917 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-31 17:06:59.274  6945  6945 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
,08-31 17:06:59.278  6878  6878 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-31 17:06:59.284  6878  6878 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 17:06:59.292  6945  6945 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 17:06:59.293  6945  6945 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-31 17:06:59.295  6945  6945 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-31 17:06:59.298  6479  6479 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 17:06:59.304  6917  6917 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-31 17:06:59.304  6917  6917 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-31 17:06:59.304  6917  6917 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-31 17:06:59.311  6878  6878 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 17:06:59.319  6878  6878 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 17:06:59.330  6945  6945 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 17:06:59.330  6945  6945 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-31 17:06:59.333  6945  6945 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-31 17:06:59.337  3870  3952 D bt_hci_bdroid: cleanup
08-31 17:06:59.337  3870  4068 W bt-btif : ag scb idx 1 not allocated
08-31 17:06:59.337  3870  4068 E bt-btif : BTA AG is already disabled, ignoring ...
08-31 17:06:59.337  3870  4068 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-31 17:06:59.337  3870  4068 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-31 17:06:59.337  3870  4068 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-31 17:06:59.337  3870  4068 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-31 17:06:59.337  3870  4068 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-31 17:06:59.337  3870  4068 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-31 17:06:59.337  3870  4068 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-31 17:06:59.337  3870  4068 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-31 17:06:59.337  3870  4068 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-31 17:06:59.338  3870  4068 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-31 17:06:59.338  3870  4068 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-31 17:06:59.338  3870  4068 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-31 17:06:59.338  3870  4068 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-31 17:06:59.338  3870  4068 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-31 17:06:59.338  3870  4068 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-31 17:06:59.338  3870  4068 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-31 17:06:59.338  3870  4068 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-31 17:06:59.338  3870  4071 I bt_lpm  : LPM is already off!!!
08-31 17:06:59.338  3870  4247 I bt_userial_mct: exiting userial_read_thread
08-31 17:06:59.338  3870  4247 D bt_userial_mct: Leaving userial_evt_read_thread()
08-31 17:06:59.338  3870  4068 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-31 17:06:59.338  3870  4068 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-31 17:06:59.339  3870  3952 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-31 17:06:59.339  3870  4071 I bt_vendor: hw_epilog_process
08-31 17:06:59.340  3870  3952 D bt_hci_bdroid: cleanup Finalizing cleanup
08-31 17:06:59.341  3870  3952 D bt_userial_mct: userial_close
08-31 17:06:59.341  3870  3952 E bt_userial_mct: pthread_join() FAILED result:3
08-31 17:06:59.341  3870  3952 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-31 17:06:59.365  1042  1042 D DSQN    : EVENT_INTERNET_CHECK_ENABLE received
,08-31 17:06:59.440  1042  1561 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6986 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-31 17:06:59.465  1042  1363 V AlarmManager: RTC_WAKEUP set : Alarm{36d58501 type 0 when 1472656019152 com.android.vending} when 1472656019152
,08-31 17:06:59.469  3870  3952 D bt_hci_bdroid: set_power 0
08-31 17:06:59.469  3870  3952 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-31 17:06:59.469  3870  3952 I bt_vendor: bluetooth satus is on
08-31 17:06:59.469  3870  3952 I bt_vendor: bt-vendor : resetting BT status
08-31 17:06:59.469  3870  3952 I bt_vendor: Starting hciattach daemon
08-31 17:06:59.469  3870  3952 I bt_vendor: try to set false
08-31 17:06:59.470  3870  3952 I bt_vendor: Starting hciattach daemon
08-31 17:06:59.470  3870  3952 I bt_vendor: try to set false
08-31 17:06:59.470  3870  3952 I bt_vendor: cleanup
08-31 17:06:59.471  3870  4068 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-31 17:06:59.480  3870  3952 I GKI_LINUX: GKI_exit_task 0 done
08-31 17:06:59.480  3870  3952 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
,08-31 17:06:59.481  3870  3948 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-31 17:06:59.484  3870  3870 D HeadsetService: Received stop request...Stopping profile...
08-31 17:06:59.485  3870  3870 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-31 17:06:59.486  3870  3870 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-31 17:06:59.486  3870  3870 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@137bb4c7
08-31 17:06:59.486  3870  3986 D HeadsetStateMachine: Exit Disconnected: -1
08-31 17:06:59.488  1866  1866 D BluetoothHeadset: Proxy object disconnected
08-31 17:06:59.488  1866  1866 D BluetoothHeadset: Proxy object disconnected
08-31 17:06:59.488  1866  1866 D BluetoothHeadset: Proxy object disconnected
08-31 17:06:59.488  1042  1042 D BluetoothHeadset: Proxy object disconnected
08-31 17:06:59.488  1042  1042 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-31 17:06:59.489  3870  3870 D A2dpService: Received stop request...Stopping profile...
08-31 17:06:59.490  3870  4046 D A2dpStateMachine: Exit Disconnected: -1
08-31 17:06:59.491  3870  3870 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-31 17:06:59.492  3870  3870 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-31 17:06:59.492  3870  3870 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-31 17:06:59.492  3870  3870 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@137bb4c7
,08-31 17:06:59.495  1042  1042 D BluetoothA2dp: Proxy object disconnected
08-31 17:06:59.495  1042  1042 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,08-31 17:06:59.498  3870  3870 D HidService: Received stop request...Stopping profile...
08-31 17:06:59.498  3870  3870 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@137bb4c7
08-31 17:06:59.499  3870  3870 D HeadsetStateMachine: Unbinding service...
08-31 17:06:59.500  3870  3870 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-31 17:06:59.500  3870  3870 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-31 17:06:59.500  3870  3870 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-31 17:06:59.500  3870  3870 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-31 17:06:59.500  3870  3870 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-31 17:06:59.500  3870  3870 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-31 17:06:59.500  3870  3870 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-31 17:06:59.502  3870  3948 D BluetoothAdapterState: Stopping profile services that were post enabled
08-31 17:06:59.502  6878  6878 D BluetoothInputDevice: Proxy object disconnected
08-31 17:06:59.503  6878  6878 D HidProfile: Bluetooth service disconnected
08-31 17:06:59.507  3870  3870 D HealthService: Received stop request...Stopping profile...
08-31 17:06:59.507  3870  3870 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@137bb4c7
08-31 17:06:59.508  3870  3870 I BluetoothA2dpServiceJni: cleanupNative
,08-31 17:06:59.511  3870  4047 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-31 17:06:59.511  3870  3870 I GKI_LINUX: GKI_exit_task 2 done
08-31 17:06:59.511  3870  3870 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-31 17:06:59.512  3870  3870 D PanService: Received stop request...Stopping profile...
08-31 17:06:59.515  3870  3870 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@137bb4c7
08-31 17:06:59.516  3870  3870 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-31 17:06:59.516  3870  3870 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-31 17:06:59.516  3870  3870 D BtGatt.DebugUtils: handleDebugAction() action=null
08-31 17:06:59.517  3870  3870 D BtGatt.GattService: Received stop request...Stopping profile...
08-31 17:06:59.517  3870  3870 D BtGatt.GattService: stop()
08-31 17:06:59.517  3870  3870 D BtGatt.AdvertiseManager: advertise clients cleared
08-31 17:06:59.518  3870  3870 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@137bb4c7
08-31 17:06:59.519  3870  3870 D BluetoothMapService: Received stop request...Stopping profile...
08-31 17:06:59.519  3870  3870 D BluetoothMapService: stop()
08-31 17:06:59.519  3870  3870 D BluetoothMapEmailAppObserver: deinitObservers()
08-31 17:06:59.520  3870  3870 D BluetoothMapEmailAppObserver: removeReceiver()
,08-31 17:06:59.520  3870  3870 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@137bb4c7
08-31 17:06:59.523  3870  3870 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-31 17:06:59.523  3870  3870 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-31 17:06:59.523  3870  3870 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-31 17:06:59.524  3870  3870 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-31 17:06:59.524  3870  3870 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-31 17:06:59.525  3870  3870 V BluetoothMapService: Handler(): got msg=4
08-31 17:06:59.525  3870  3870 D BluetoothMapService: MAP Service closeService in
08-31 17:06:59.525  3870  3870 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-31 17:06:59.525  3870  3870 V BluetoothMapService: MAP Service closeService out
08-31 17:06:59.526  3870  3948 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-31 17:06:59.526  3870  3948 D BluetoothAdapterProperties: Setting state to 10
08-31 17:06:59.526  3870  3948 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-31 17:06:59.526  3870  3870 D BluetoothMapService: cleanup()
08-31 17:06:59.526  3870  3870 D BluetoothMapService: MAP Service closeService in
08-31 17:06:59.526  3870  3870 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-31 17:06:59.526  3870  3870 V BluetoothMapService: MAP Service closeService out
08-31 17:06:59.527  1042  1117 D BluetoothManagerService: Message: 60
08-31 17:06:59.527  1042  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-31 17:06:59.527  1042  1117 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
08-31 17:06:59.528  3870  3948 I BluetoothAdapterState: Entering OffState
08-31 17:06:59.528  1866  2552 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 17:06:59.529  1866  2524 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 17:06:59.530  6878  6896 D BluetoothPbap: onBluetoothStateChange: up=false
08-31 17:06:59.530  1042  1117 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 17:06:59.531  1866  1881 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 17:06:59.531  6878  6896 D BluetoothMap: onBluetoothStateChange: up=false
,08-31 17:06:59.532  1042  1117 D BluetoothA2dp: onBluetoothStateChange: up=false
08-31 17:06:59.532  6878  6897 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-31 17:06:59.533  6878  6896 D BluetoothPan: onBluetoothStateChange on: false
08-31 17:06:59.534  6878  6878 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-31 17:06:59.534  6878  6878 D PanProfile: Bluetooth service disconnected
08-31 17:06:59.535  1042  1117 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-31 17:06:59.535  1042  1117 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-31 17:06:59.537  1042  1117 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-31 17:06:59.537  1042  1117 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-31 17:06:59.537  1042  1117 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@2a6dfc2b mBinding = false
08-31 17:06:59.538  1042  1117 D BluetoothManagerService: Sending unbind request.
08-31 17:06:59.540  1042  1117 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-31 17:06:59.548  3870  3952 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-31 17:06:59.548  1956  1956 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-31 17:06:59.549  1956  2166 D LGBluetoothAPIService: Message: 2
08-31 17:06:59.549  1956  2166 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@3f9460d6 mBinding = false
08-31 17:06:59.549  1956  2166 D LGBluetoothAPIService: Sending unbind request.
08-31 17:06:59.551  3870  3870 I GKI_LINUX: GKI_exit_task 1 done
08-31 17:06:59.551  3870  3870 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-31 17:06:59.552  3870  3870 I BluetoothServiceJni: cleanupNative: return from cleanup
08-31 17:06:59.553  3870  3870 I art     : --- WEIRD: removing null entry 246
08-31 17:06:59.553  3870  3870 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
08-31 17:06:59.553  3870  3870 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-31 17:06:59.557  6878  6878 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-31 17:06:59.558  6694  6694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 17:06:59.558  6878  6878 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-31 17:06:59.558  1589  1589 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-31 17:06:59.558  6878  6878 D LGBluetoothEventManager: [BTUI] clear device connection state
08-31 17:06:59.559  6694  6694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 17:06:59.563  6878  6878 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-31 17:06:59.564  3870  3870 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-31 17:06:59.568  1589  1589 D BluetoothAdapter: 316630425: getState() :  mService = null. Returning STATE_OFF
08-31 17:06:59.568  1589  1589 D BluetoothAdapter: 316630425: getState() :  mService = null. Returning STATE_OFF
08-31 17:06:59.569  3870  3870 I art     : System.exit called, status: 0
08-31 17:06:59.569  3870  3870 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-31 17:06:59.572  6878  6878 D DockEventReceiver: finishStartingService: stopping service
08-31 17:06:59.587   317  1370 V AudioFlinger: 3870 died, releasing its sessions
08-31 17:06:59.587   317  1370 V AudioFlinger:  pid 1866 @ 0
08-31 17:06:59.587   317  1370 V AudioFlinger:  pid 3366 @ 1
08-31 17:06:59.587   317  1370 V AudioFlinger:  pid 3366 @ 2
,08-31 17:06:59.594  6917  6917 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-31 17:06:59.594  6878  6878 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-31 17:06:59.614  1042  1983 V SIM_STK : Menu title from STK is T-Mobile
,08-31 17:06:59.629  1042  2011 I ActivityManager: Process com.android.bluetooth (pid 3870) has died
08-31 17:06:59.629  1042  2011 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
,08-31 17:06:59.638  6878  6878 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-31 17:06:59.639  2230  2230 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-31 17:06:59.647  6986  7020 W FormManager: Network not available. Please check & try again.
08-31 17:06:59.651  6878  6878 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 17:06:59.654  6878  6878 D BluetoothPermissionRequest: onReceive
08-31 17:06:59.656  6878  6878 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-31 17:06:59.656  6878  6878 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
,08-31 17:06:59.658  6878  6878 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-31 17:06:59.696  1042  1955 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7025 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-31 17:06:59.703  6986  7021 V FormManager: Network unavailable.
08-31 17:06:59.705  6986  7021 V FormManager: Network unavailable.
08-31 17:06:59.716  6878  6878 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-31 17:06:59.716  6878  6878 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-31 17:06:59.716  6878  6878 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-31 17:06:59.716  6878  6878 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-31 17:06:59.717  6878  6878 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,08-31 17:06:59.730  6878  6878 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-31 17:06:59.731  6878  6878 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-31 17:06:59.731  6878  6878 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-31 17:06:59.731  6878  6878 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-31 17:06:59.731  6878  6878 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-31 17:06:59.731  6878  6878 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,08-31 17:06:59.736  4304  4304 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-31 17:06:59.736  4304  4304 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-31 17:06:59.738  4304  4304 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-31 17:06:59.743  4304  4304 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-31 17:06:59.751  4304  7043 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-31 17:06:59.752  6917  6917 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-31 17:06:59.752  6917  6917 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-31 17:06:59.752  6917  6917 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-31 17:06:59.755  6878  6878 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-31 17:06:59.757  7025  7025 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-31 17:06:59.758  7025  7025 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-31 17:06:59.758  7025  7025 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-31 17:06:59.759  7025  7025 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-31 17:06:59.761  6986  7046 W FormManager: Network not available. Please check & try again.
08-31 17:06:59.762  4304  7045 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-31 17:06:59.762  4304  7045 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-31 17:06:59.763  6986  7047 V FormManager: Network unavailable.
08-31 17:06:59.766  6878  6878 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-31 17:06:59.775  6986  7047 V FormManager: Network unavailable.
08-31 17:06:59.777  7025  7025 D BluetoothAdapterApp: Loading JNI Library
08-31 17:06:59.782  6945  6945 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,08-31 17:06:59.783  6945  6945 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-31 17:06:59.784  6945  6945 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
08-31 17:06:59.809  7025  7025 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@23334c5c Instance Count = 1
,08-31 17:06:59.812  7025  7025 D BluetoothAdapterApp: onCreate
08-31 17:06:59.820  6945  6945 D LgDataFeature: LgDataFeature() Constructor: none
08-31 17:06:59.820  6945  6945 D LgDataFeature: LgDataFeature() Constructor Done, null
08-31 17:06:59.824  6080  6080 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.
,08-31 17:06:59.827  1042  1058 I ActivityManager: Killing 6033:com.android.contacts/u0a19 (adj 15): empty #17
08-31 17:06:59.828  6945  6945 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
08-31 17:06:59.829  6945  6945 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
,08-31 17:06:59.829  6945  6945 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-31 17:06:59.829  6945  6945 V SoundPool: doLoad: loading sample sampleID=1
08-31 17:06:59.829  7025  7025 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-31 17:06:59.830  6945  6945 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-31 17:06:59.830  7025  7025 D ProfileConfigQcom: Adding HeadsetService
08-31 17:06:59.830  7025  7025 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-31 17:06:59.830  7025  7025 D ProfileConfigQcom: Adding A2dpService
08-31 17:06:59.830  7025  7025 D ProfileConfigQcom: [BTUI] HidService is supported
08-31 17:06:59.830  7025  7025 D ProfileConfigQcom: Adding HidService
08-31 17:06:59.830  7025  7025 D ProfileConfigQcom: [BTUI] HealthService is supported
08-31 17:06:59.830  7025  7025 D ProfileConfigQcom: Adding HealthService
08-31 17:06:59.831  7025  7025 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-31 17:06:59.831  6945  7052 V SoundPool: Start decode
08-31 17:06:59.831  6945  7052 V MediaPlayer[Native]: decode(31, 10857164, 17813)
08-31 17:06:59.831  7025  7025 D ProfileConfigQcom: [BTUI] PanService is supported
08-31 17:06:59.831  7025  7025 D ProfileConfigQcom: Adding PanService
08-31 17:06:59.831  7025  7025 D ProfileConfigQcom: [BTUI] GattService is supported
08-31 17:06:59.832  7025  7025 D ProfileConfigQcom: Adding GattService
08-31 17:06:59.832  7025  7025 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-31 17:06:59.832  7025  7025 D ProfileConfigQcom: Adding BluetoothMapService
08-31 17:06:59.832   317   317 V MediaPlayerService: decode(23, 10857164, 17813)
08-31 17:06:59.832   317   317 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-31 17:06:59.832   317   317 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-31 17:06:59.832  7025  7025 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-31 17:06:59.832   317   317 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-31 17:06:59.832   317   317 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-31 17:06:59.832   317   317 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-31 17:06:59.832   317   317 V MediaPlayerService: player type = 3
08-31 17:06:59.832   317   317 V AwesomePlayer: AwesomePlayer create()
08-31 17:06:59.832   317   317 V AwesomePlayer: reset_l() 
08-31 17:06:59.832   317   317 V AwesomePlayer: cancelPlayerEvents
08-31 17:06:59.833   317   317 V AwesomePlayer: setAudioSink() 
08-31 17:06:59.833   317   317 V AwesomePlayer: reset_l() 
08-31 17:06:59.833   317   317 V AudioCache: notify(0xb1004380, 8, 0, 0)
08-31 17:06:59.833   317   317 V AudioCache: ignored
08-31 17:06:59.833   317   317 V AwesomePlayer: cancelPlayerEvents
08-31 17:06:59.833   317   317 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
08-31 17:06:59.833   317   317 V AwesomePlayer: setDataSource_l dataSource
08-31 17:06:59.833   317   317 V LGParserOSAL: SniffLGParser start
08-31 17:06:59.833   317   317 V LGParserOSAL: MainType:5, SubType=0
,08-31 17:06:59.833   317   317 V LGParserOSAL: #### check Mime : application/ogg
,08-31 17:06:59.833   317   317 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
,08-31 17:06:59.833   317   317 E MediaExtractor: Use LGExtractor :application/ogg 
08-31 17:06:59.833  7025  7025 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-31 17:06:59.878   317   317 V LGParserOSAL: supported mime: application/ogg
,08-31 17:06:59.878   317   317 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-31 17:06:59.878   317   317 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-31 17:06:59.878   317   317 V AwesomePlayer: mBitrate = -1 bits/sec
,08-31 17:06:59.878   317   317 V AwesomePlayer: AudioTrack Setting
08-31 17:06:59.878   317   317 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-31 17:06:59.878   317   317 V AwesomePlayer: setAudioSource() 
,08-31 17:06:59.878   317   317 V MediaPlayerService: prepare
08-31 17:06:59.878   317   317 V AwesomePlayer: prepareAsync_l() 
,08-31 17:06:59.879   317   317 V MediaPlayerService: wait for prepare
08-31 17:06:59.879   317  7053 V AwesomePlayer: onPrepareAsyncEvent() 
08-31 17:06:59.879   317  7053 V AwesomePlayer: initAudioDecoder() 
,08-31 17:06:59.879   317  7053 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-31 17:06:59.879   317  7053 V AudioSystem: isOffloadSupported()
08-31 17:06:59.879   317  7053 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
,08-31 17:06:59.879   317  7053 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-31 17:06:59.879   317  7053 I AudioFlinger: isAudioPlaybackHookOn() false
08-31 17:06:59.879   317  7053 V AwesomePlayer: getUseOffload() = 0 
,08-31 17:06:59.879   317  7053 V OMXCodec: OMXCodec::Create
08-31 17:06:59.879   317  7053 V OMXCodec: findMatchingCodecs()
08-31 17:06:59.879   317  7053 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
,08-31 17:06:59.879   317  7053 V OMXCodec: matchingCodecs.size()=1
08-31 17:06:59.879   317  7053 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,08-31 17:06:59.883   317  7053 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-31 17:06:59.883   317  7053 V LGCodecAdapter: LG Codec Adapter start
08-31 17:06:59.883   317  7053 V OMXCodec: OMXCodec Createtor
08-31 17:06:59.883   317  7053 V OMXCodec: setComponentRole
08-31 17:06:59.883   317  7053 V OMXCodec: configureCodec protected=0
08-31 17:06:59.883   317  7053 V LGCodecAdapter: called getLGCodecSpecificData
08-31 17:06:59.883   317  7053 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-31 17:06:59.883   317  7053 V LGCodecOSAL: Called LGconfigureCodecMETA
08-31 17:06:59.883   317  7053 V LGCodecOSAL: Called LGconfigureCodecMSG
08-31 17:06:59.883   317  7053 V LGCodecOSAL: Not support LGCodec
08-31 17:06:59.883   317  7053 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-31 17:06:59.883   317  7053 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-31 17:06:59.884   317  7053 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-31 17:06:59.884   317  7053 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-31 17:06:59.884   317  7053 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-31 17:06:59.884   317  7053 V AudioSystem: isOffloadSupported()
08-31 17:06:59.884   317  7053 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-31 17:06:59.884   317  7053 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-31 17:06:59.884   317  7053 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-31 17:06:59.884   317  7053 V OMXCodec: init()
08-31 17:06:59.884   317  7053 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-31 17:06:59.884   317  7053 V OMXCodec: allocateBuffers
08-31 17:06:59.884   317  7053 V OMXCodec: allocateBuffersOnPort portIndex=0
08-31 17:06:59.884   317  7053 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-31 17:06:59.885   317  7053 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f920 on input port
08-31 17:06:59.885   317  7053 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f970 on input port
08-31 17:06:59.885   317  7053 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f9c0 on input port
08-31 17:06:59.885   317  7053 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fa10 on input port
08-31 17:06:59.885   317  7053 V OMXCodec: allocateBuffersOnPort portIndex=1
08-31 17:06:59.885   317  7053 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-31 17:06:59.886   317  7053 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fa60 on output port
08-31 17:06:59.886   317  7053 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fb00 on output port
08-31 17:06:59.886   317  7053 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fba0 on output port
08-31 17:06:59.886   317  7053 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fd30 on output port
08-31 17:06:59.886   317  7053 V OMXCodec: init() mAsyncCompletion wait!!! 
08-31 17:06:59.888   317  7055 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-31 17:06:59.888   317  7055 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-31 17:06:59.889   317  7055 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-31 17:06:59.889   317  7053 V OMXCodec: init() mAsyncCompletion wait!!! 
08-31 17:06:59.889   317  7055 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-31 17:06:59.889   317  7055 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-31 17:06:59.889   31,7  7055 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-31 17:06:59.889   317  7053 V OMXCodec: init() mAsyncCompletion wait free! 
08-31 17:06:59.889   317  7053 V AwesomePlayer: finishAsyncPrepare_l() 
08-31 17:06:59.889   317  7053 V AudioCache: notify(0xb1004380, 5, 0, 0)
08-31 17:06:59.889   317  7053 V AudioCache: ignored
08-31 17:06:59.889   317  7053 V AudioCache: notify(0xb1004380, 1, 0, 0)
08-31 17:06:59.889   317  7053 V AudioCache: prepared
08-31 17:06:59.889   317   317 V AudioCache: wait - success
08-31 17:06:59.889   317   317 V MediaPlayerService: start
08-31 17:06:59.889   317   317 V AwesomePlayer: play_l() 
08-31 17:06:59.889   317   317 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-31 17:06:59.889   317   317 V AwesomePlayer: createAudioPlayer_l
08-31 17:06:59.889   317   317 V AwesomePlayer: seekAudioIfNecessary_l() 
08-31 17:06:59.889   317   317 V AwesomePlayer: startAudioPlayer_l() 
08-31 17:06:59.889   317   317 D AudioPlayer: start of Playback, useOffload 0
08-31 17:06:59.889   317   317 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-31 17:06:59.890   317   317 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-31 17:06:59.894   317  7055 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-31 17:06:59.894   317  7055 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-31 17:06:59.894   317  7055 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-31 17:06:59.894   317  7055 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-31 17:06:59.894   317  7055 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-31 17:06:59.894   317  7055 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-31 17:06:59.894   317  7055 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957048416
08-31 17:06:59.894   317  7055 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-31 17:06:59.894   317  7055 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957048576
08-31 17:06:59.894   317  7055 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-31 17:06:59.894   317  7055 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957048736
08-31 17:06:59.894   317  7055 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-31 17:06:59.894   317  7055 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957049136
08-31 17:06:59.894   317  7055 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-31 17:06:59.894   317  7055 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-31 17:06:59.894   317  7055 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-31 17:06:59.894   317  7055 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-31 17:06:59.895   317  7055 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-31 17:06:59.895   317  7055 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-31 17:06:59.895   317  7055 V OMXCodec: allocateBuffersOnPort portIndex=1
08-31 17:06:59.895   317  7055 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-31 17:06:59.895   317  7055 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fba0 on output port
08-31 17:06:59.895   317  7055 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fb00 on output port
08-31 17:06:59.895   317  7055 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fa60 on output port
08-31 17:06:59.895   317  7055 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1434330 on output port
08-31 17:06:59.895   317  7055 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-31 17:06:59.895   317  7055 V OMXCod,ec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-31 17:06:59.896   317   317 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-31 17:06:59.897   317   317 V AudioCache: notify(0xb1004380, 6, 0, 0)
08-31 17:06:59.897   317   317 V AudioCache: ignored
08-31 17:06:59.897   317   317 V MediaPlayerService: wait for playback complete
08-31 17:06:59.907  1042  2342 W libprocessgroup: failed to open /acct/uid_10019/pid_6033/cgroup.procs: No such file or directory
08-31 17:06:59.907  6814  6814 D UEI.SmartControl: QS Service created
08-31 17:06:59.907   317  7056 V AudioCache: write(0xb57cc000, 4096)
08-31 17:06:59.907   317  7056 V AudioCache: memcpy(0xac200000, 0xb57cc000, 4096)
08-31 17:06:59.908  6878  6878 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-31 17:06:59.909   317  7056 V AudioCache: write(0xb57cc000, 4096)
08-31 17:06:59.910   317  7056 V AudioCache: memcpy(0xac201000, 0xb57cc000, 4096)
08-31 17:06:59.911   317  7056 V AudioCache: write(0xb57cc000, 4096)
08-31 17:06:59.911   317  7056 V AudioCache: memcpy(0xac202000, 0xb57cc000, 4096)
08-31 17:06:59.911  6945  6945 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-31 17:06:59.912   317  7056 V AudioCache: write(0xb57cc000, 4096)
08-31 17:06:59.912   317  7056 V AudioCache: memcpy(0xac203000, 0xb57cc000, 4096)
08-31 17:06:59.914   317  7056 V AudioCache: write(0xb57cc000, 4096)
08-31 17:06:59.914   317  7056 V AudioCache: memcpy(0xac204000, 0xb57cc000, 4096)
08-31 17:06:59.914  6945  6945 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-31 17:06:59.915   317  7056 V AudioCache: write(0xb57cc000, 4096)
08-31 17:06:59.915   317  7056 V AudioCache: memcpy(0xac205000, 0xb57cc000, 4096)
08-31 17:06:59.915  6945  6945 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-31 17:06:59.916   317  7056 V AudioCache: write(0xb57cc000, 4096)
08-31 17:06:59.916   317  7056 V AudioCache: memcpy(0xac206000, 0xb57cc000, 4096)
08-31 17:06:59.917   317  7056 V AudioCache: write(0xb57cc000, 4096)
08-31 17:06:59.917   317  7056 V AudioCache: memcpy(0xac207000, 0xb57cc000, 4096)
,08-31 17:06:59.919   317  7056 V AudioCache: write(0xb57cc000, 4096)
08-31 17:06:59.919   317  7056 V AudioCache: memcpy(0xac208000, 0xb57cc000, 4096)
08-31 17:06:59.920   317  7056 V AudioCache: write(0xb57cc000, 4096)
08-31 17:06:59.920   317  7056 V AudioCache: memcpy(0xac209000, 0xb57cc000, 4096)
08-31 17:06:59.920   317  7056 V AudioCache: write(0xb57cc000, 4096)
08-31 17:06:59.920   317  7056 V AudioCache: memcpy(0xac20a000, 0xb57cc000, 4096)
08-31 17:06:59.921   317  7056 V AudioCache: write(0xb57cc000, 4096)
08-31 17:06:59.921   317  7056 V AudioCache: memcpy(0xac20b000, 0xb57cc000, 4096)
08-31 17:06:59.922   317  7056 V AudioCache: write(0xb57cc000, 4096)
08-31 17:06:59.922   317  7056 V AudioCache: memcpy(0xac20c000, 0xb57cc000, 4096)
08-31 17:06:59.922  7025  7025 V LGMDMManagerInternal: Create singleton instance
08-31 17:06:59.923   317  7056 V AudioCache: write(0xb57cc000, 4096)
08-31 17:06:59.923   317  7056 V AudioCache: memcpy(0xac20d000, 0xb57cc000, 4096)
08-31 17:06:59.923   317  7056 V AudioCache: write(0xb57cc000, 4096)
08-31 17:06:59.923   317  7056 V AudioCache: memcpy(0xac20e000, 0xb57cc000, 4096)
08-31 17:06:59.924   317  7056 V AudioCache: write(0xb57cc000, 4096)
08-31 17:06:59.924   317  7056 V AudioCache: memcpy(0xac20f000, 0xb57cc000, 4096)
08-31 17:06:59.924   317  7056 V AudioCache: write(0xb57cc000, 4096)
08-31 17:06:59.924   317  7056 V AudioCache: memcpy(0xac210000, 0xb57cc000, 4096)
08-31 17:06:59.925   317  7056 V AudioCache: write(0xb57cc000, 4096)
08-31 17:06:59.925   317  7056 V AudioCache: memcpy(0xac211000, 0xb57cc000, 4096)
08-31 17:06:59.926   317  7056 V AudioCache: write(0xb57cc000, 4096)
08-31 17:06:59.926   317  7056 V AudioCache: memcpy(0xac212000, 0xb57cc000, 4096)
08-31 17:06:59.926   317  7056 V AudioCache: write(0xb57cc000, 4096)
08-31 17:06:59.926   317  7056 V AudioCache: memcpy(0xac213000, 0xb57cc000, 4096)
08-31 17:06:59.927   317  7056 V AudioCache: write(0xb57cc000, 4096)
08-31 17:06:59.927   317  7056 V AudioCache: memcpy(0xac214000, 0xb57cc000, 4096)
08-31 17:06:59.927  6814  6814 I UEI.SmartControl: Service initServices...
08-31 17:06:59.927  6814  6814 D UEI.SmartControl: QS start get config
08-31 17:06:59.928   317  7056 V AudioCache: write(0xb57cc000, 4096)
08-31 17:06:59.928   317  7056 V AudioCache: memcpy(0xac215000, 0xb57cc000, 4096)
08-31 17:06:59.929   317  7056 V AudioCache: write(0xb57cc000, 4096)
08-31 17:06:59.929   317  7056 V AudioCache: memcpy(0xac216000, 0xb57cc000, 4096)
08-31 17:06:59.929   317  7056 V AudioCache: write(0xb57cc000, 4096)
08-31 17:06:59.929   317  7056 V AudioCache: memcpy(0xac217000, 0xb57cc000, 4096)
08-31 17:06:59.930   317  7056 V AudioCache: write(0xb57cc000, 4096)
08-31 17:06:59.930   317  7056 V AudioCache: memcpy(0xac218000, 0xb57cc000, 4096)
08-31 17:06:59.931   317  7056 V AudioCache: write(0xb57cc000, 4096)
08-31 17:06:59.931   317  7056 V AudioCache: memcpy(0xac219000, 0xb57cc000, 4096)
08-31 17:06:59.932   317  7056 V AudioCache: write(0xb57cc000, 4096)
08-31 17:06:59.932   317  7056 V AudioCache: memcpy(0xac21a000, 0xb57cc000, 4096)
08-31 17:06:59.932  6945  6945 V LGMDMManager: Create singleton instance
08-31 17:06:59.932   317  7056 V AudioCache: write(0xb57cc000, 4096)
08-31 17:06:59.932   317  7056 V AudioCache: memcpy(0xac21b000, 0xb57cc000, 4096)
08-31 17:06:59.933   317  7056 V AudioCache: write(0xb57cc000, 4096)
08-31 17:06:59.933   317  7056 V AudioCache: memcpy(0xac21c000, 0xb57cc000, 4096)
08-31 17:06:59.934   317  7056 V AudioCache: write(0xb57cc000, 4096)
08-31 17:06:59.934   317  7056 V AudioCache: memcpy(0xac21d000, 0xb57cc000, 4096)
08-31 17:06:59.934   317  7056 V AudioCache: write(0xb57cc000, 4096)
08-31 17:06:59.934   317  7056 V AudioCache: memcpy(0xac21e000, 0xb57cc000, 4096)
08-31 17:06:59.935   317  7056 V AudioCache: write(0xb57cc000, 4096)
08-31 17:06:59.935   317  7056 V AudioCache: memcpy(0xac21f000, 0xb57cc000, 4096)
08-31 17:06:59.936   317  7056 V AudioCache: write(0xb57cc000, 4096)
08-31 17:06:59.936   317  7056 V AudioCache: memcp,y(0xac220000, 0xb57cc000, 4096)
08-31 17:06:59.937   317  7056 V AudioCache: write(0xb57cc000, 4096)
08-31 17:06:59.937   317  7056 V AudioCache: memcpy(0xac221000, 0xb57cc000, 4096)
08-31 17:06:59.937   317  7056 V AudioCache: write(0xb57cc000, 4096)
08-31 17:06:59.937   317  7056 V AudioCache: memcpy(0xac222000, 0xb57cc000, 4096)
08-31 17:06:59.938   317  7056 V AudioCache: write(0xb57cc000, 4096)
08-31 17:06:59.938   317  7056 V AudioCache: memcpy(0xac223000, 0xb57cc000, 4096)
08-31 17:06:59.939   317  7056 V AudioCache: write(0xb57cc000, 4096)
08-31 17:06:59.939   317  7056 V AudioCache: memcpy(0xac224000, 0xb57cc000, 4096)
08-31 17:06:59.939   317  7056 V AudioCache: write(0xb57cc000, 4096)
08-31 17:06:59.939   317  7056 V AudioCache: memcpy(0xac225000, 0xb57cc000, 4096)
08-31 17:06:59.940   317  7056 V AudioCache: write(0xb57cc000, 4096)
08-31 17:06:59.940   317  7056 V AudioCache: memcpy(0xac226000, 0xb57cc000, 4096)
08-31 17:06:59.941   317  7056 V AudioCache: write(0xb57cc000, 4096)
08-31 17:06:59.941   317  7056 V AudioCache: memcpy(0xac227000, 0xb57cc000, 4096)
08-31 17:06:59.941   317  7056 V AudioCache: write(0xb57cc000, 4096)
08-31 17:06:59.941   317  7056 V AudioCache: memcpy(0xac228000, 0xb57cc000, 4096)
08-31 17:06:59.942   317  7056 V AudioCache: write(0xb57cc000, 4096)
08-31 17:06:59.942   317  7056 V AudioCache: memcpy(0xac229000, 0xb57cc000, 4096)
08-31 17:06:59.943   317  7056 V AudioCache: write(0xb57cc000, 4096)
08-31 17:06:59.943   317  7056 V AudioCache: memcpy(0xac22a000, 0xb57cc000, 4096)
08-31 17:06:59.943   317  7056 V AudioCache: write(0xb57cc000, 4096)
08-31 17:06:59.943   317  7056 V AudioCache: memcpy(0xac22b000, 0xb57cc000, 4096)
08-31 17:06:59.944   317  7056 V AudioCache: write(0xb57cc000, 4096)
08-31 17:06:59.944   317  7056 V AudioCache: memcpy(0xac22c000, 0xb57cc000, 4096)
08-31 17:06:59.945   317  7056 V AudioCache: write(0xb57cc000, 4096)
08-31 17:06:59.945   317  7056 V AudioCache: memcpy(0xac22d000, 0xb57cc000, 4096)
08-31 17:06:59.945   317  7056 V AudioCache: write(0xb57cc000, 4096)
08-31 17:06:59.945   317  7056 V AudioCache: memcpy(0xac22e000, 0xb57cc000, 4096)
08-31 17:06:59.946   317  7056 V AudioCache: write(0xb57cc000, 4096)
08-31 17:06:59.946   317  7056 V AudioCache: memcpy(0xac22f000, 0xb57cc000, 4096)
08-31 17:06:59.946   317  7056 V AudioCache: write(0xb57cc000, 4096)
08-31 17:06:59.947   317  7056 V AudioCache: memcpy(0xac230000, 0xb57cc000, 4096)
08-31 17:06:59.947   317  7056 V AudioCache: write(0xb57cc000, 4096)
08-31 17:06:59.947   317  7056 V AudioCache: memcpy(0xac231000, 0xb57cc000, 4096)
08-31 17:06:59.947   317  7055 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-31 17:06:59.947   317  7056 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-31 17:06:59.947   317  7056 V AwesomePlayer: postAudioEOS() 
08-31 17:06:59.947   317  7056 V AudioCache: write(0xb57cc000, 280)
08-31 17:06:59.947   317  7056 V AudioCache: memcpy(0xac232000, 0xb57cc000, 280)
,08-31 17:06:59.956   317  7053 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-31 17:06:59.956   317  7053 V AwesomePlayer: onStreamDone
08-31 17:06:59.956   317  7053 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-31 17:06:59.956   317  7053 V AudioCache: notify(0xb1004380, 2, 0, 0)
08-31 17:06:59.956   317  7053 V AudioCache: playback complete
08-31 17:06:59.956   317  7053 V AwesomePlayer: pause_l() 
08-31 17:06:59.956   317  7053 V AudioCache: notify(0xb1004380, 7, 0, 0)
08-31 17:06:59.956   317  7053 V AudioCache: ignored
08-31 17:06:59.956   317  7053 V AwesomePlayer: cancelPlayerEvents
08-31 17:06:59.956   317  7053 D AudioPlayer: Pause Playback at 1068125
08-31 17:06:59.957   317   317 V AudioCache: wait - success
08-31 17:06:59.957   317   317 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-31 17:06:59.957   317   317 V AwesomePlayer: reset_l() 
08-31 17:06:59.957   317   317 V AudioCache: notify(0xb1004380, 8, 0, 0)
08-31 17:06:59.957   317   317 V AudioCache: ignored
08-31 17:06:59.957   317   317 V AwesomePlayer: cancelPlayerEvents
08-31 17:06:59.957   317   317 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-31 17:06:59.957   317   317 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-31 17:06:59.957   317   317 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-31 17:06:59.957   317   317 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-31 17:06:59.957   317   317 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-31 17:06:59.958   317  7055 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-31 17:06:59.958   317  7055 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-31 17:06:59.958   317  7055 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-31 17:06:59.958   317  7055 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fa10 on port 0
08-31 17:06:59.958   317  7055 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-31 17:06:59.958   317  7055 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f9c0 on port 0
08-31 17:06:59.958   317  7055 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-31 17:06:59.958   317  7055 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f970 on port 0
08-31 17:06:59.958   317  7055 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-31 17:06:59.958   317  7055 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f920 on port 0
08-31 17:06:59.958   317  7055 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-31 17:06:59.958   317  7055 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-31 17:06:59.958   317  7055 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb1434330 on port 1
08-31 17:06:59.958   317  7055 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-31 17:06:59.958   317  7055 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fa60 on port 1
08-31 17:06:59.958   317  7055 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-31 17:06:59.958   317  7055 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fb00 on port 1
08-31 17:06:59.958   317  7055 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-31 17:06:59.958   317  7055 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fba0 on port 1
08-31 17:06:59.958   317  7055 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-31 17:06:59.959   317  7055 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-31 17:06:59.959   317   317 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-31 17:06:59.959   317   317 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-31 17:06:59.959   317  7055 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-31, 17:06:59.959   317  7055 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-31 17:06:59.959   317  7055 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-31 17:06:59.959   317   317 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-31 17:06:59.959   317   317 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-31 17:06:59.959   317   317 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-31 17:06:59.960   317   317 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-31 17:06:59.960   317   317 D AudioPlayer: AudioPlayer releasing audio source
08-31 17:06:59.960   317   317 D AudioPlayer: AudioPlayer done releasing audio source
08-31 17:06:59.960   317   317 V AwesomePlayer: reset_l() 
08-31 17:06:59.960   317   317 V AwesomePlayer: cancelPlayerEvents
08-31 17:06:59.960   317   317 V AwesomePlayer: ~AwesomePlayer call
08-31 17:06:59.960   317   317 V AwesomePlayer: reset_l() 
08-31 17:06:59.960   317   317 V AwesomePlayer: cancelPlayerEvents
08-31 17:06:59.960  6945  7052 V SoundPool: close(31)
08-31 17:06:59.960  6945  7052 V SoundPool: pointer = 0xa0033000, size = 205080, sampleRate = 48000, numChannels = 2
08-31 17:07:00.002  7025  7025 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-31 17:07:00.008  7025  7025 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-31 17:07:00.009  7025  7025 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-31 17:07:00.009  7025  7025 V BluetoothSapReceiver: SapReceiver onReceive 
08-31 17:07:00.010  7025  7025 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-31 17:07:00.010  7025  7025 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-31 17:07:00.017  6962  6962 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,08-31 17:07:00.023  6945  6945 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-31 17:07:00.024  6945  6945 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
08-31 17:07:00.026  6945  6945 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:7543
08-31 17:07:00.047  4477  7058 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
08-31 17:07:00.047  1589  1589 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,08-31 17:07:00.047  1589  1589 I KeyguardUpdateMonitor: called onTimeUpdated()
,08-31 17:07:00.047  1589  1589 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-31 17:07:00.047  1589  1589 I [SystemUI]Clock: called onTimeUpdated()
08-31 17:07:00.048  1589  1589 I LgeClockWidgetControlView: called onTimeUpdated()
08-31 17:07:00.048  1589  1589 I [SystemUI]DateView: called onTimeUpdated()
08-31 17:07:00.048  1589  1589 I [SystemUI]DateView: called onTimeUpdated()
08-31 17:07:00.049  1589  1589 D KeyguardUpdateMonitor: handleTimeUpdate
08-31 17:07:00.221  6814  6814 I UEI.SmartControl: Supports setup maps: true
08-31 17:07:00.224  6814  6814 D UEI.SmartControl: QS start statue = true Error code = 0
08-31 17:07:00.224  6814  6814 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-31 17:07:00.224  6814  6814 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
,08-31 17:07:00.224  6814  6814 I UEI.SmartControl: ### init IR Blaster...
08-31 17:07:00.227  6814  6814 D serial_port: Configuring serial port
08-31 17:07:00.227  6814  6814 E UEI.SmartControl: UEIBLaster setting for 616
08-31 17:07:00.227  6814  6814 I UEI.SmartControl: Setting serial record hearder size = 2
08-31 17:07:00.227  6814  6814 I UEI.SmartControl: configuring settings for MAXQ616
08-31 17:07:00.227  6814  6814 I UEI.SmartControl: Get version...
08-31 17:07:00.246  6814  7066 D UEI.SmartControl: serial port data available: 21
,08-31 17:07:00.273  6814  6814 D UEI.SmartControl: MAXQ616 A2-X4 software.
,08-31 17:07:00.273  6814  6814 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-31 17:07:00.273  6814  6814 I UEI.SmartControl: QS saving settings...
08-31 17:07:00.275  6814  6814 D UEI.SmartControl: IR Blaster version: 25672567
,08-31 17:07:00.292  6814  7066 D UEI.SmartControl: serial port data available: 4
,08-31 17:07:00.327  6814  6814 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-31 17:07:00.328  6814  7069 I UEI.SmartControl: Device manager: loading config....
08-31 17:07:00.329  6814  7069 D UEI.SmartControl: ----------- loading internal config...
08-31 17:07:00.330  6814  6814 E UEI.SmartControl: Services init done
08-31 17:07:00.330  6814  6814 D UEI.SmartControl: QS Service init finished
,08-31 17:07:00.332  6814  6814 D UEI.SmartControl: QS Service version name: 2.1.91
08-31 17:07:00.333  6814  6814 D UEI.SmartControl: QS Service version code: 201091
08-31 17:07:00.334  6814  6814 D UEI.SmartControl: Service requested: Control
08-31 17:07:00.340  6814  7069 E UEI.SmartControl: Loading SETTINGS...
08-31 17:07:00.342  1042  1363 D PowerManagerServiceEx: acquireWakeLockInternal: lock=908914171, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1042
08-31 17:07:00.343  1042  1363 V AlarmManager: ELAPSED_WAKEUP set : Alarm{cc5fe18 type 2 when 118416 com.google.android.gms} when 118416
,08-31 17:07:00.345  6814  6814 D UEI.SmartControl: Request IControl service: devices are loaded...
08-31 17:07:00.348  6814  7069 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-31 17:07:00.350  6814  6814 D UEI.SmartControl: Internal service binding...
08-31 17:07:00.351  6945  6945 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-31 17:07:00.353  6814  6830 I UEI.SmartControl: ------ IControl API: 11
08-31 17:07:00.353  6814  6830 D UEI.SmartControl: File observer start...
08-31 17:07:00.354  6814  6830 E UEI.SmartControl: IR Port is disabled: false
08-31 17:07:00.355  6814  6830 D UEI.SmartControl: Starting file observer...
08-31 17:07:00.355   313  7072 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-31 17:07:00.356  1042  1115 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-31 17:07:00.359  6814  6830 I UEI.SmartControl: Registering callback...
,08-31 17:07:00.360  6814  6829 I UEI.SmartControl: ------ IControl API: 19
,08-31 17:07:00.361  6814  6829 I UEI.SmartControl: Registering Services Ready callback...
08-31 17:07:00.362  6814  6829 I UEI.SmartControl: Notify client services are ready...
08-31 17:07:00.362  6945  6961 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-31 17:07:00.363  6945  7049 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-31 17:07:00.363  6945  7049 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-31 17:07:00.364  6945  6945 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-31 17:07:00.365  6814  7068 I UEI.SmartControl: Notify AllClients services are ready: 0
08-31 17:07:00.365  6945  6945 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-31 17:07:00.365  6945  6960 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-31 17:07:00.365  6814  6830 I UEI.SmartControl: ------ IControl API: 8
08-31 17:07:00.365  6814  7068 D UEI.SmartControl: -----service ready thread exits
08-31 17:07:00.365  6945  7049 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-31 17:07:00.365  6945  7049 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-31 17:07:00.368  6945  6945 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-31 17:07:00.369  6945  6945 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-31 17:07:00.369  6945  6945 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-31 17:07:00.370  6945  6945 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-31 17:07:00.371  6945  6945 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-31 17:07:00.372  6945  6945 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
,08-31 17:07:00.374  6945  6945 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
08-31 17:07:00.380  6945  6945 D QRemote : [RemoteControlManager.java:327:handleMessage()] oooooo 140510:retrieveDevices already complete. Do nothing
08-31 17:07:00.381  6945  6945 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-31 17:07:00.383  6945  6945 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-31 17:07:00.384  6945  6945 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-31 17:07:00.384  6945  6945 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-31 17:07:00.385  6945  6945 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
,08-31 17:07:00.386  6945  6945 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-31 17:07:00.387  6945  6945 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-31 17:07:00.388  6945  6945 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1472656020388]
08-31 17:07:00.396  6945  6945 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
,08-31 17:07:00.400  2639  2639 D [Concierge]Service: onStartCommand(). Type : 9
,08-31 17:07:00.403  1042  1058 I ActivityManager: Killing 6061:com.android.gallery3d/u0a27 (adj 15): empty #17
08-31 17:07:00.424  6945  7073 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-31 17:07:00.432  1042  1058 I ActivityManager: Killing 6581:com.lge.email/u0a23 (adj 15): empty #18
08-31 17:07:00.470  1042  1057 W libprocessgroup: failed to open /acct/uid_10027/pid_6061/cgroup.procs: No such file or directory
,08-31 17:07:00.474  1042  1762 W libprocessgroup: failed to open /acct/uid_10023/pid_6581/cgroup.procs: No such file or directory
,08-31 17:07:00.488  6945  6945 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,08-31 17:07:00.491  6945  6945 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-31 17:07:00.492  6945  6945 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-31 17:07:00.493  6945  6945 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-31 17:07:00.494  6945  6945 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-31 17:07:00.494  6945  6945 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-31 17:07:00.495  6945  6945 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
08-31 17:07:00.503  1042  1042 D PowerManagerServiceEx: releaseWakeLockInternal: lock=908914171 [*alarm*], flags=0x0
,08-31 17:07:00.511  6945  6945 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,08-31 17:07:01.312  1042  2341 D WifiServiceImplEx: setWifiEnabled: true pid=6694, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-31 17:07:01.313  1042  2341 D WifiService: setWifiEnabled: true pid=6694, uid=10118
08-31 17:07:01.313  1042  2341 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-31 17:07:01.345  1042  1042 D LocationManagerService: getAllProviders()=[passive, gps, network]
,08-31 17:07:01.345  1042  1042 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
,08-31 17:07:01.345  1042  1042 D Ulp_jni : JNI:system_update. Event-4
08-31 17:07:01.347  1042  1523 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
,08-31 17:07:01.347  1042  1523 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-31 17:07:01.349  1042  1523 E WifiUtil: wfc_util_ffile_check_copy(): pid[1042] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-31 17:07:01.349  1042  1523 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-31 17:07:01.349  1042  1523 E WifiUtil: wfc_util_ffile_check_copy(): pid[1042] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
,08-31 17:07:01.349  1042  1523 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-31 17:07:01.349  1042  1523 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-31 17:07:01.349  1042  1523 E WifiHW  : unknown target_country: EU , set to default
08-31 17:07:01.349  1042  1523 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-31 17:07:01.349  1042  1523 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-31 17:07:01.349  1042  1523 I WifiUtil: gEnableBmps=1
08-31 17:07:01.408  1042  1530 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-31 17:07:01.427  1042  1117 D Tethering: MasterInitialState.processMessage what=3
08-31 17:07:01.437  6694  6694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 17:07:01.440  6694  6694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 17:07:01.443  1042  1530 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-31 17:07:01.446  1042  1117 D Tethering: MasterInitialState.processMessage what=3
08-31 17:07:01.456  6694  6694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 17:07:01.461  6694  6694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 17:07:01.462  6479  6479 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-31 17:07:01.465  6479  6511 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-31 17:07:01.466  1042  1108 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-31 17:07:01.484  5759  5759 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-31 17:07:01.499  5759  5759 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-31 17:07:01.515  2230  2230 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-31 17:07:01.555  1042  1108 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-31 17:07:01.606  1042  1955 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7098 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,08-31 17:07:01.617  1042  1108 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 17:07:01.617  1042  1108 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-31 17:07:01.704  7098  7098 I AppUp4:AppBoxCP: onCreate
08-31 17:07:01.705  7098  7098 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,08-31 17:07:01.716  7098  7098 I AppUp4:DB:  setFingerPrint start
,08-31 17:07:01.716  7098  7098 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
08-31 17:07:01.726  7098  7098 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
,08-31 17:07:01.726  7098  7098 I AppUp4:DB:  SDK version = 21
,08-31 17:07:01.726  7098  7098 I AppUp4:DB:  beforefinger == newfinger no write in DB
,08-31 17:07:01.728  7098  7098 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
08-31 17:07:01.731  7098  7098 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
,08-31 17:07:01.731  7098  7098 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-31 17:07:01.734  7098  7098 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-31 17:07:01.734  7098  7098 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-31 17:07:01.742  7098  7098 I AppUp4:CustModeStarterReceiver: onReceive
,08-31 17:07:01.786  7098  7098 D LgDataFeature: LgDataFeature() Constructor: none
,08-31 17:07:01.787  7098  7098 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-31 17:07:01.796  7098  7098 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2107a606
08-31 17:07:01.797  7098  7098 D AppUp4:CustFacade: isCustomizationCompleted : false
08-31 17:07:01.797  7098  7098 D AppUp4:CustFacade: isPhone : true
08-31 17:07:01.797  7098  7098 D AppUp4:CustModeStarterReceiver: begin check event
08-31 17:07:01.798  7098  7098 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
08-31 17:07:01.799  7098  7098 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
08-31 17:07:01.800  7098  7117 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
08-31 17:07:01.800  7098  7117 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
08-31 17:07:01.800  7098  7117 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
,08-31 17:07:01.804  1042  1058 I ActivityManager: Killing 6122:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
08-31 17:07:01.870  1042  1983 W libprocessgroup: failed to open /acct/uid_10080/pid_6122/cgroup.procs: No such file or directory
,08-31 17:07:01.878  4304  4304 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-31 17:07:01.879  4304  4304 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-31 17:07:01.882  4304  4304 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-31 17:07:01.885  4304  4304 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-31 17:07:01.900  4304  7129 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-31 17:07:01.900  4304  7131 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-31 17:07:01.900  4304  7131 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-31 17:07:01.945  1042  1728 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7132 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-31 17:07:02.056  1042  1117 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-31 17:07:02.057  1042  1117 D Tethering: InitialState.processMessage what=4
,08-31 17:07:02.057  1042  1117 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-31 17:07:02.067  7132  7132 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-31 17:07:02.068  7132  7132 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-31 17:07:02.069   313   893 D SoftapController: Softap fwReload - Ok
08-31 17:07:02.070  1042  1523 E NetdConnector: NDC Command {53 softap fwreload wlan0 STA} took too long (713ms)
08-31 17:07:02.070  7132  7132 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,08-31 17:07:02.071  7132  7132 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-31 17:07:02.072   313   893 D CommandListener: Setting iface cfg
08-31 17:07:02.072   313   893 D CommandListener: Trying to bring down wlan0
08-31 17:07:02.075   313   893 D CommandListener: Clearing all IP addresses on wlan0
08-31 17:07:02.077  1042  1523 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,08-31 17:07:02.085  1042  1523 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-31 17:07:02.085  1042  1523 E WifiStateMachine: useWiFiOffloading() : false
08-31 17:07:02.085  1042  1523 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-31 17:07:02.088  1042  1042 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-31 17:07:02.091  1956  1956 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-31 17:07:02.091  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 17:07:02.094  6694  6694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 17:07:02.095  6694  6694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 17:07:02.095  1042  1523 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-31 17:07:02.095  1042  1523 D WifiMonitor: connecting to supplicant
,08-31 17:07:02.107  7150  7150 I wpa_supplicant: Successfully initialized wpa_supplicant
08-31 17:07:02.074  7150  7150 W wpa_supplicant: type=1400 audit(0.0:167): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 17:07:02.074  7150  7150 W wpa_supplicant: type=1400 audit(0.0:168): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-31 17:07:02.142  7150  7150 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-31 17:07:02.143  7150  7150 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,08-31 17:07:02.183  7132  7132 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-31 17:07:02.198  7132  7132 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,08-31 17:07:02.225  7150  7150 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-31 17:07:02.274  7132  7132 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-31 17:07:02.287  7150  7150 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-31 17:07:02.306  7150  7150 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
08-31 17:07:02.307  7150  7150 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-31 17:07:02.307  1042  7152 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
08-31 17:07:02.307  1042  1523 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-31 17:07:02.307  1042  7152 D WifiMonitor: Dropping event because (p2p0) is stopped
08-31 17:07:02.307  1042  7152 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-31 17:07:02.307  1042  7152 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-31 17:07:02.307  1042  7152 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-31 17:07:02.307  1042  7152 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,08-31 17:07:02.308  1042  1523 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-31 17:07:02.309  1042  1523 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-31 17:07:02.309  1042  1523 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-31 17:07:02.310  1042  1523 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-31 17:07:02.310  1042  1523 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-31 17:07:02.311  1042  1523 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-31 17:07:02.311  1042  1523 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-31 17:07:02.313  1042  1523 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-31 17:07:02.315  1042  1523 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-31 17:07:02.315  1042  1523 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-31 17:07:02.316  7132  7132 D LgDataFeature: LgDataFeature() Constructor: none
08-31 17:07:02.316  7132  7132 D LgDataFeature: LgDataFeature() Constructor Done, null
08-31 17:07:02.317  1042  1042 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 17:07:02.317  1042  1042 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 17:07:02.317  1042  1523 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-31 17:07:02.317  1042  1523 E WifiStateMachine: useWiFiOffloading() : false
08-31 17:07:02.317  1042  1523 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-31 17:07:02.317  1042  1042 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 17:07:02.317  1042  1042 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 17:07:02.317  1042  1042 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-31 17:07:02.320  1042  1523 D WifiNative-wlan0: doBoolean: SET update_config 1
,08-31 17:07:02.320  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 17:07:02.322  1956  1956 D WfdService: Waiting for WifiP2p enabling
08-31 17:07:02.323  1042  1523 D WifiNative-wlan0: SET update_config 1: returned true
08-31 17:07:02.323  1042  1523 D WifiConfigStore: Loading config and enabling all networks 
08-31 17:07:02.323  1042  1523 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-31 17:07:02.324  1042  1523 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-31 17:07:02.330  1042  1042 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-31 17:07:02.331  1042  1528 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-31 17:07:02.332  6694  6694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 17:07:02.332  6694  6694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 17:07:02.332  6694  6694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 17:07:02.332  6694  6694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 17:07:02.332  6694  6694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 17:07:02.332  6694  6694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 17:07:02.332  6694  6694 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 17:07:02.332  6694  6694 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 17:07:02.332  6694  6694 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 17:07:02.333  6694  6694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 17:07:02.333  6694  6694 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-31 17:07:02.339  6694  6694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 17:07:02.339  6694  6694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 17:07:02.339  6694  6694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 17:07:02.339  6694  6694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 17:07:02.339  6694  6694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 17:07:02.339  6694  6694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 17:07:02.339  6694  6694 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 17:07:02.339  6694  6694 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 17:07:02.339  6694  6694 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 17:07:02.339  6694  6694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 17:07:02.339  6694  6694 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-31 17:07:02.343  1042  1523 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-31 17:07:02.353  1042  1523 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-31 17:07:02.353  1042  1523 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-31 17:07:02.354  1042  1523 D WifiStateMachine: enableVerboseLogging : level 2
08-31 17:07:02.354  1042  1523 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-31 17:07:02.356  1042  1523 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-31 17:07:02.356  1042  1523 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-31 17:07:02.356  1042  1523 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-31 17:07:02.356  1042  1523 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-31 17:07:02.357  1042  1523 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-31 17:07:02.357  1042  1523 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-31 17:07:02.357  1042  1523 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-31 17:07:02.357  1042  1523 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-31 17:07:02.357  1042  1523 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-31 17:07:02.357  1042  1523 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-31 17:07:02.358  1042  1523 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-31 17:07:02.358  1042  1523 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-31 17:07:02.358  1042  1523 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
,08-31 17:07:02.359  1956  1956 D WfdsService: Supplicant Connection state is changed : true
08-31 17:07:02.359  1956  2323 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-31 17:07:02.360  1956  2323 D WfdsService: Set the WFDS Monitor: true
08-31 17:07:02.360  1956  2323 D WfdsMonitor: WfdsMonitorThread create
08-31 17:07:02.360  1956  2323 D WfdsMonitor: WFDS Monitor is created and started
08-31 17:07:02.360  1956  2323 D WfdsService: WiFi: Supplicant connection re-established
08-31 17:07:02.360  1042  1523 D WifiStateMachine: Setting OUI to DA-A1-19
08-31 17:07:02.360  1042  1523 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-31 17:07:02.360  1042  1523 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-31 17:07:02.361  1042  1523 D WifiNative-HAL: Setting external_sim to 1
,08-31 17:07:02.361  1042  1523 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-31 17:07:02.361  1042  1523 D WifiNative-wlan0: SET external_sim 1: returned true
08-31 17:07:02.361  1042  1523 I WifiNative-HAL: startHal
08-31 17:07:02.361  1042  1523 D wifi    : setting scan oui 0xaf6ca040
08-31 17:07:02.361  1956  7154 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-31 17:07:02.362  1042  1523 D WifiStateMachine: Setting OUI to DA-A1-19
08-31 17:07:02.362  1042  1523 I WifiNative-HAL: startHal
08-31 17:07:02.362  1956  7154 E CtrlSupplicant: Succeed to open control connection
08-31 17:07:02.362  1042  1523 D wifi    : setting scan oui 0xaf6ca040
08-31 17:07:02.362  1956  7154 E CtrlSupplicant: Succeed to open monitor connection
08-31 17:07:02.362  1042  1523 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-31 17:07:02.362  1956  7154 D WfdsMonitor: Supplicant connection established
08-31 17:07:02.363  1042  1523 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-31 17:07:02.363  1042  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-31 17:07:02.363  7150  7150 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-31 17:07:02.363  1956  2323 D WfdsService: Connected to the supplicant for wfds
08-31 17:07:02.363  1042  1523 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-31 17:07:02.363  1042  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-31 17:07:02.364  7150  7150 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-31 17:07:02.364  1042  1523 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-31 17:07:02.364  1042  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-31 17:07:02.364  7150  7150 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-31 17:07:02.364  1042  1523 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-31 17:07:02.364  1042  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-31 17:07:02.364  7150  7150 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-31 17:07:02.365  1042  1523 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-31 17:07:02.365  1042  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-31 17:07:02.365  7150  7150 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-31 17:07:02.365  1042  1523 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-31 17:07:02.365  1042  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-31 17:07:02.365  7150  7150 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-31 17:07:02.365  1042  1523 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-31 17:07:02.365  1042  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-31 17:07:02.366  7150  7150 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-31 17:07:02.366  1042  1523 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-31 17:07:02.367  1042  1523 E WifiNative: : [120,442,378 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-31 17:07:02.367  1042  1523 D WifiNative-wlan0: doBoolean: RECONNECT
08-31 17:07:02.367  1042  1523 D WifiNative-wlan0: RECONNECT: returned true
08-31 17:07:02.367  1042  1523 D WifiNative-wlan0: doString: [STATUS]
08-31 17:07:02.368  1042  7152 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-31 17:07:02.368  1042  7152 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-31 17:07:02.369  1042  1523 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-31 17:07:02.369  1042  1523 D WifiNative-wlan0: doBoolean: SET ps 1
08-31 17:07:02.369  1042  1523 D WifiNative-wlan0: SET ps 1: returned true
08-31 17:07:02.369  1042  1522 D LGWifiP2pService: P2pDisabledState{ when=0 w,hat=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-31 17:07:02.370  1042  1042 D WifiScanningService: SCAN_AVAILABLE : 3
08-31 17:07:02.370  1042  1042 D RttService: SCAN_AVAILABLE : 3
08-31 17:07:02.370  1042  1542 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-31 17:07:02.370  1042  1542 I WifiNative-HAL: startHal
08-31 17:07:02.370  1042  1523 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-31 17:07:02.370  1042  1542 D wifi    : getting scan capabilities on interface[1] = 0xaf6ca040
08-31 17:07:02.370  1042  1542 D wifi    : failed to get capabilities : -3
08-31 17:07:02.370  1042  1542 E WifiScanningService: could not get scan capabilities
08-31 17:07:02.371  1042  1543 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-31 17:07:02.371  1042  1523 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-31 17:07:02.371  1042  1523 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-31 17:07:02.371   313   893 D CommandListener: Setting iface cfg
08-31 17:07:02.371   313   893 D CommandListener: Trying to bring up p2p0
08-31 17:07:02.371  1042  1523 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-31 17:07:02.371  1042  1522 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-31 17:07:02.372  1042  1522 D LGWifiP2pService: P2pEnablingState
08-31 17:07:02.372  1042  1522 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-31 17:07:02.372  1042  1522 D LGWifiP2pService: P2p socket connection successful
08-31 17:07:02.372  1042  1522 D LGWifiP2pService: P2pEnabledState
08-31 17:07:02.372  1042  1523 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-31 17:07:02.372  1042  1522 D LGWifiP2pService: sending p2p connection changed broadcast
08-31 17:07:02.372  1042  1523 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-31 17:07:02.373  1042  1523 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-31 17:07:02.373  1042  1523 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-31 17:07:02.373  7150  7150 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-31 17:07:02.373  1956  1956 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-31 17:07:02.373  1042  1522 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-31 17:07:02.373  1956  1956 D WfdsService: WifiP2pState is changed : true
08-31 17:07:02.373  1956  2323 D WfdsService: Receive the WFDS_ENABLE Method
08-31 17:07:02.373  1956  2323 D WfdsService: Set the WFDS Monitor: true
08-31 17:07:02.373  1956  2323 D WfdsService: Connected to the supplicant for wfds
08-31 17:07:02.373  1956  2323 D WfdsJNI : doCommand: WFDS_SET TRUE
08-31 17:07:02.374  7150  7150 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-31 17:07:02.374  1956  2323 D WfdsService: selectPreferredScanChannel [36]
08-31 17:07:02.374  1956  2323 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-31 17:07:02.374  1042  1522 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-31 17:07:02.374  1042  1522 D WifiNative-p2p0: doBoolean: SET device_name G3
08-31 17:07:02.375  1042  1522 D WifiNative-p2p0: SET device_name G3: returned true
08-31 17:07:02.375  1042  1522 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-31 17:07:02.375  1042  1522 D LGWifiP2pService: before postfix = G3
08-31 17:07:02.375  1042  1522 D WifiServerServiceExt: postfix byte check : 2
08-31 17:07:02.375  1042  1522 D LGWifiP2pService: after postfix = G3
08-31 17:07:02.375  1042  1522 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-31 17:07:02.377  1042  1522 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-31 17:07:02.377  1042  1522 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-31 17:07:02.377  1956  1956 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-31 17:07:02.378  1956  1956 D WfdsService: isConnected: false
08-31 17:07:02.378  1042  1522 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-31 17:07:02.378  1042  1522 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-31 17:07:02.378  1042  1522 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-31 17:07:02.378  1042  1522 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-31 17:07:02.379  1042  1522 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-31 17:07:02.379  1042  1523 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-31 17:07:02.379  1042  1522 D WifiNative-HAL: p2pGetDeviceAddress
08-31 17:07:02.379  1042  1523 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-31 17:07:02.380  1042  1522 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-31 17:07:02.380  1042  1523 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-31 17:07:02.380  1042  1523 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-31 17:07:02.380  7150  7150 E wpa_supplicant: disconnect_rssi_lvl: -100
08-31 17:07:02.380  1042  1523 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
08-31 17:07:02.381  1042  1523 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
08-31 17:07:02.381  1042  1523 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
08-31 17:07:02.383  1042  1522 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-31 17:07:02.383  1042  1522 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-31 17:07:02.383  1956  1956 I WfdStateTracker: handleP2pThisDeviceChanged
08-31 17:07:02.383  1956  1956 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-31 17:07:02.383  1956  1956 D WfdsService: Update P2p Interface State: 3
08-31 17:07:02.384  1042  1523 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-31 17:07:02.384  1042  1522 D WifiNative-p2p0: P2P_FLUSH: returned true
08-31 17:07:02.384  1042  1522 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-31 17:07:02.385  7150  7150 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-31 17:07:02.385  7150  7150 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-31 17:07:02.385  1042  7152 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-31 17:07:02.385  1042  7152 E WifiMonitor: WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-31 17:07:02.385  1042  7152 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-31 17:07:02.385  1042  7152 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-31 17:07:02.386  7150  7150 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-31 17:07:02.386  7150  7150 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 17:07:02.386  1042  7152 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-31 17:07:02.386  1042  7152 E WifiMonitor: WifiMonitor:p2p0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 17:07:02.386  1042  7152 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 17:07:02.386  1042  7152 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 17:07:02.387  7150  7150 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 17:07:02.387  1042  7152 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-31 17:07:02.387  1042  7152 E WifiMonitor: WifiMonitor:p2p0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 17:07:02.387  1042  7152 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 17:07:02.387  1042  7152 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 17:07:02.387  1956  7154 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-31 17:07:02.388  1956  7154 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-31 17:07:02.388  1042  1523 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-31 17:07:02.388  1042  1522 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-31 17:07:02.389  1042  1522 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-31 17:07:02.389  1042  1522 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-31 17:07:02.389  1042  1522 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-31 17:07:02.390  1042  1523 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-31 17:07:02.390  1042  1523 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-31 17:07:02.391  1042  1523 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-31 17:07:02.391  1042  1523 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-31 17:07:02.409  1042  1522 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-31 17:07:02.409  1042  1522 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-31 17:07:02.409  7150  7150 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-31 17:07:02.409  1042  1522 D LGWifiP2pService: InactiveState
08-31 17:07:02.409  7150  7150 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-31 17:07:02.409  1042  1522 D LGWifiP2pService: InactiveState{ when=-22ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-31 17:07:02.410  1042  1523 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-31 17:07:02.410  1042  1523 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-31 17:07:02.411  1042  1523 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-31 17:07:02.411  1042  1523 D WifiNative-wlan0: doBoolean: SCAN
,08-31 17:07:02.411  1042  1523 D WifiNative-wlan0: SCAN: returned false
08-31 17:07:02.412  1042  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=120488  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-31 17:07:02.412  1042  1522 D LGWifiP2pService: P2pEnabledState{ when=-22ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-31 17:07:02.412  1042  1522 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-31 17:07:02.413  1042  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=120489  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-31 17:07:02.413  7150  7150 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-31 17:07:02.413  1042  1523 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-31 17:07:02.414  7150  7150 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-31 17:07:02.414  1042  1523 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-31 17:07:02.414  1042  1523 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-31 17:07:02.415  7150  7150 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-31 17:07:02.415  7150  7150 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 17:07:02.415  1042  1523 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-31 17:07:02.415  1042  1523 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-31 17:07:02.415  7150  7150 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 17:07:02.417  1042  7152 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-31 17:07:02.417  1042  7152 E WifiMonitor: WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-31 17:07:02.417  1042  7152 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-31 17:07:02.417  1956  7154 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-31 17:07:02.417  1042  7152 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-31 17:07:02.417  1042  7152 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-31 17:07:02.417  1042  7152 E WifiMonitor: WifiMonitor:p2p0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-31 17:07:02.417  1956  7154 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-31 17:07:02.417  1042  7152 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-31 17:07:02.417  1042  7152 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-31 17:07:02.417  1042  7152 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-31 17:07:02.417  1042  7152 E WifiMonitor: WifiMonitor:p2p0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 17:07:02.417  1956  7154 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-31 17:07:02.417  1042  7152 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 17:07:02.417  1042  7152 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 17:07:02.417  1042  7152 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-31 17:07:02.417  1042  7152 E WifiMonitor: WifiMonitor:p2p0 cnt=30 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 17:07:02.417  1042  7152 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 17:07:02.417  1042  7152 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 17:07:02.420  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 17:07:02.420  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 17:07:02.421  1042  1042 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 17:07:02.421  1042  1042 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 17:07:02.421  1042  1042 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-31 17:07:02.421  1042  1042 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-31 17:07:02.421  1042  1042 D WifiServerServiceExt: setSupplicantStateSCANNING
08-31 17:07:02.423  1042  1522 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-31 17:07:02.423  1042  1522 D LGWifiP2pService: InactiveState{ when=-35ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-31 17:07:02.424  1042  1522 D LGWifiP2pService: P2pEnabledState{ when=-35ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-31 17:07:02.424  1042  1522 D LGWifiP2pService: InactiveState{ when=-14ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-31 17:07:02.424  1042  1522 D LGWifiP2pService: P2pEnabledState{ when=-14ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-31 17:07:02.424  1042  1522 D LGWifiP2pService: DefaultState{ when=-14ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-31 17:07:02.424  1042  1522 D LGWifiP2pService: InactiveState{ when=-15ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-31 17:07:02.424  1042  1522 D LGWifiP2pService: P2pEnabledState{ when=-15ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-31 17:07:02.424  1042  1522 D LGWifiP2pService: DefaultState{ when=-15ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-31 17:07:02.424  1042  1522 D LGWifiP2pService: InactiveState{ when=-15ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-31 17:07:02.424  1042  1522 D LGWifiP2pService: P2pEnabledState{ when=-15ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-31 17:07:02.424  1042  1522 D LGWifiP2pService: DefaultState{ when=-15ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-31 17:07:02.425  1956  2323 W WfdsService: DefaultState - msg [9441285] is not handled
08-31 17:07:02.427  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 17:07:02.430  1042  1522 D LGWifiP2pService: InactiveState{ when=-20ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-31 17:07:02.430  1042  1522 D LGWifiP2pService: P2pEnabledState{ when=-20ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-31 17:07:02.430  1042  1522 D LGWifiP2pService: DefaultState{ when=-21ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-31 17:07:02.430  1042  1042 E WifiServerServiceExt: No p2p device connected
,08-31 17:07:02.477  7132  7132 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-31 17:07:02.510  3366  3366 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,08-31 17:07:02.511  3366  3366 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-31 17:07:02.511  3366  3366 I LgeMiscReceiver: networkInfo.isConnected() = false
,08-31 17:07:02.519  7132  7132 I HubEmail: JNI_OnLoad()
08-31 17:07:02.519  7132  7132 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-31 17:07:02.519  7132  7132 I HubEmail: registerNatives()
08-31 17:07:02.519  7132  7132 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-31 17:07:02.519  7132  7132 I HubEmail: registerNativeMethods()
08-31 17:07:02.519  7132  7132 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-31 17:07:02.519  7132  7132 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
08-31 17:07:02.561  1042  1983 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7168 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,08-31 17:07:02.571  6986  7164 W FormManager: Network not available. Please check & try again.
08-31 17:07:02.574  7132  7167 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-31 17:07:02.575  6986  7165 V FormManager: Network unavailable.
08-31 17:07:02.578  6986  7165 V FormManager: Network unavailable.
08-31 17:07:02.587  1042  1762 I ActivityManager: Killing 6149:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,08-31 17:07:02.703  1042  1058 W libprocessgroup: failed to open /acct/uid_10097/pid_6149/cgroup.procs: No such file or directory
08-31 17:07:02.810  7168  7168 D LgDataFeature: LgDataFeature() Constructor: none
08-31 17:07:02.810  7168  7168 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-31 17:07:02.814  7168  7168 D PhoneMonitor: Register our PhoneStateListener
,08-31 17:07:02.836  7168  7168 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,08-31 17:07:02.838  7168  7168 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-31 17:07:02.871  7168  7168 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
08-31 17:07:02.878  7168  7168 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
,08-31 17:07:02.879  7168  7168 D TelephonyAutoProfiling: [parse] Load xml
08-31 17:07:02.887  7168  7168 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
08-31 17:07:02.887  7168  7168 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
08-31 17:07:02.887  7168  7168 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-31 17:07:02.888  7168  7168 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
08-31 17:07:02.888  7168  7168 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
08-31 17:07:02.888  7168  7168 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
08-31 17:07:02.888  7168  7168 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-31 17:07:02.890  1042  1561 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7191 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-31 17:07:02.891  1042  1561 I ActivityManager: Killing 6621:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,08-31 17:07:02.894  7168  7168 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-31 17:07:02.894  7168  7168 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-31 17:07:02.894  7168  7168 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-31 17:07:02.894  7168  7168 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-31 17:07:02.894  7168  7168 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-31 17:07:02.894  7168  7168 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-31 17:07:02.894  7168  7168 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-31 17:07:02.894  7168  7168 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-31 17:07:02.894  7168  7168 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-31 17:07:02.895  7168  7168 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
,08-31 17:07:02.911  7168  7168 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
08-31 17:07:02.930  1042  7152 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-31 17:07:02.930  1042  7152 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-31 17:07:02.930  1042  7152 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-31 17:07:02.930  7150  7150 E wpa_supplicant: USIM:  scard_init function
08-31 17:07:02.930  1042  7152 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: WPS-AP-AVAILABLE 
08-31 17:07:02.930  1042  7152 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-31 17:07:02.931  7150  7150 I wpa_supplicant: Trying to associate with SSID 'NG700'
,08-31 17:07:02.933  1042  7152 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-31 17:07:02.933  1042  1523 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-31 17:07:02.933  1042  7152 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-31 17:07:02.933  1042  1523 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-31 17:07:02.934  1042  1523 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-31 17:07:02.934  1042  1523 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-31 17:07:02.934  1042  1523 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-31 17:07:02.949  1042  1918 W libprocessgroup: failed to open /acct/uid_10061/pid_6621/cgroup.procs: No such file or directory
,08-31 17:07:02.953  1042  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=121029  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-31 17:07:02.958  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 17:07:02.958  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 17:07:02.959  1042  1042 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 17:07:02.959  1042  1042 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 17:07:02.959  1042  1042 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-31 17:07:02.960  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 17:07:02.967  1042  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=121043  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-31 17:07:02.970  1042  1042 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-31 17:07:02.970  1042  1042 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 17:07:02.970  1042  1042 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-31 17:07:02.970  1042  1042 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-31 17:07:02.970  1042  1042 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-31 17:07:02.985  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 17:07:02.985  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-31 17:07:02.988  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 17:07:03.054  7150  7150 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
08-31 17:07:03.057  1042  7152 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-31 17:07:03.057  1042  7152 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-31 17:07:03.058  1042  7152 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-31 17:07:03.058  1042  7152 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: Associated with f4:f2:6d:22:99:3e
,08-31 17:07:03.059  1042  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=121135  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-31 17:07:03.059  1042  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=121135  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-31 17:07:03.060  1042  1523 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=121136
08-31 17:07:03.060  1042  1523 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=121136
08-31 17:07:03.061  1042  1523 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=121137
08-31 17:07:03.061  1042  7152 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-31 17:07:03.061  1042  7152 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-31 17:07:03.061  1042  1523 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=121137
08-31 17:07:03.062  1042  1523 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=121138
08-31 17:07:03.063  1042  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=121138  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-31 17:07:03.063  1042  1117 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-31 17:07:03.064  1042  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=121140  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-31 17:07:03.066  7150  7150 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-31 17:07:03.066  7150  7150 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-31 17:07:03.067  1042  7152 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-31 17:07:03.067  1042  7152 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-31 17:07:03.068  1042  7152 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-31 17:07:03.068  1042  7152 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-31 17:07:03.068  1042  7152 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-31 17:07:03.068  1042  7152 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-31 17:07:03.068  1042  7152 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-31 17:07:03.068  1042  7152 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-31 17:07:03.068  1042  7152 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-31 17:07:03.068  1042  7152 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-31 17:07:03.068  1042  1042 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-31 17:07:03.068  1042  1042 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-31 17:07:03.069  1042  1042 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 17:07:03.069  1042  1042 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.Sy,stem to android.provider.Settings.Global, returning read-only value.
08-31 17:07:03.069  1042  1042 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
,08-31 17:07:03.072  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 17:07:03.072  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 17:07:03.077  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 17:07:03.079  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 17:07:03.079  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 17:07:03.080  1042  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=121156  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-31 17:07:03.080  1042  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=121156  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-31 17:07:03.081  1042  1523 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=121157
08-31 17:07:03.081  1042  1523 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=121157
08-31 17:07:03.082  1042  1523 D WifiNative-wlan0: doString: [STATUS]
,08-31 17:07:03.083  1042  7152 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-31 17:07:03.083  1042  7152 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-31 17:07:03.084  1042  1042 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 17:07:03.085  1042  1042 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 17:07:03.085  1042  1042 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-31 17:07:03.085  1042  1523 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-31 17:07:03.087  1042  1523 I WifiServiceExtension: setVHTCapabilityType  : false
08-31 17:07:03.087  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 17:07:03.098  1042  1523 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-31 17:07:03.098  1042  1523 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
,08-31 17:07:03.103  1042  1042 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 17:07:03.104  1042  1042 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 17:07:03.104  1042  1042 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,08-31 17:07:03.113  1042  1042 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 17:07:03.113  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 17:07:03.113  1042  1042 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 17:07:03.113  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 17:07:03.113  1042  1042 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-31 17:07:03.114  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 17:07:03.116  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 17:07:03.116  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 17:07:03.117  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 17:07:03.120  1042  1523 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-31 17:07:03.120  1042  1523 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-31 17:07:03.120  1042  1523 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-31 17:07:03.121  1042  1530 D ConnectivityService: Got NetworkAgent Messenger
08-31 17:07:03.121  1042  1530 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-31 17:07:03.121  1042  1523 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-31 17:07:03.121  1042  1530 D ConnectivityService: NetworkAgent connected
08-31 17:07:03.121  1042  1523 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-31 17:07:03.134  1042  1523 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-31 17:07:03.135  1042  1523 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-31 17:07:03.135  1042  1523 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
,08-31 17:07:03.137  1042  1523 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-31 17:07:03.138  1042  1523 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-31 17:07:03.145  1042  1523 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-31 17:07:03.147   313   893 D CommandListener: Setting iface cfg
,08-31 17:07:03.151  1042  1523 E WifiStateMachine: Start Dhcp Watchdog 2
08-31 17:07:03.151  1042  7210 D DhcpStateMachine: StoppedState
08-31 17:07:03.151  1042  7210 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-31 17:07:03.151  1042  7210 D DhcpStateMachine: WaitBeforeStartState
08-31 17:07:03.152  1042  1523 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=121228  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-31 17:07:03.152  1042  1523 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=121228  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-31 17:07:03.153  1042  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=121229  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-31 17:07:03.153  1042  1523 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
,08-31 17:07:03.154  1042  1523 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
08-31 17:07:03.154  1042  1523 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-31 17:07:03.154  1042  1523 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-31 17:07:03.155  1042  1523 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-31 17:07:03.155  1042  1523 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-31 17:07:03.157  1042  1042 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-31 17:07:03.157  1042  1042 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-31 17:07:03.157  1042  1523 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=121233  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-31 17:07:03.158  1042  1523 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=121234  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-31 17:07:03.158  1042  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=121234  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
,08-31 17:07:03.160  1042  1523 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:75033] from screen [on:0 period:-517759368] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-31 17:07:03.161  1042  1523 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-517759367] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-31 17:07:03.161  1042  1523 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-31 17:07:03.170  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-31 17:07:03.173  1042  1530 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
08-31 17:07:03.175  1042  1523 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 17:07:03.176  1042  1523 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 17:07:03.177  1042  1523 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 17:07:03.178  1042  1523 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 17:07:03.179  1042  1523 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 17:07:03.180  1042  1523 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 17:07:03.181  1042  1530 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-31 17:07:03.183  1042  1523 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=131,0,0
,08-31 17:07:03.184  1042  1523 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=131,0,0
08-31 17:07:03.184  1042  1523 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-31 17:07:03.185  7150  7150 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-31 17:07:03.185  1042  1523 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-31 17:07:03.185  1042  1523 D WifiNative-wlan0: doBoolean: SET ps 0
08-31 17:07:03.186  1042  1523 D WifiNative-wlan0: SET ps 0: returned true
08-31 17:07:03.186  1042  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-31 17:07:03.187  7150  7150 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-31 17:07:03.187  1042  1523 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-31 17:07:03.187  1042  1523 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-31 17:07:03.187  1042  1522 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@562b116 target=com.android.internal.util.StateMachine$SmHandler }
08-31 17:07:03.187  1042  1523 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-31 17:07:03.188  1042  1522 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@562b116 target=com.android.internal.util.StateMachine$SmHandler }
08-31 17:07:03.188  1042  7210 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-31 17:07:03.188  1042  1523 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-31 17:07:03.188  1042  7210 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-31 17:07:03.190   313   893 D CommandListener: Setting iface cfg
08-31 17:07:03.191   313   893 D CommandListener: Trying to bring up wlan0
08-31 17:07:03.193  1042  1523 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-31 17:07:03.212  1042  2011 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7215 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
08-31 17:07:03.214  1042  2011 I ActivityManager: Killing 6762:com.lge.eula/1000 (adj 15): empty #17
,08-31 17:07:03.262  1042  1042 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-31 17:07:03.262  1042  1042 D WifiServerServiceExt: setSupplicantStateCOMPLETED
,08-31 17:07:03.271  1042  1726 W libprocessgroup: failed to open /acct/uid_1000/pid_6762/cgroup.procs: No such file or directory
08-31 17:07:03.271  1042  1523 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 17:07:03.271  1042  1523 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 17:07:03.272  1042  1523 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 17:07:03.272  1042  1523 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 17:07:03.273  1042  1523 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 17:07:03.273  1042  1523 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 17:07:03.274  1042  1530 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-31 17:07:03.275  1042  1523 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-31 17:07:03.275  1042  1523 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-31 17:07:03.275  1042  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-31 17:07:03.276  7150  7150 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-31 17:07:03.277  1042  1523 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-31 17:07:03.277  1042  1523 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
,08-31 17:07:03.279  1042  1522 D LGWifiP2pService: InactiveState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-31 17:07:03.279  1042  1522 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-31 17:07:03.279  7150  7150 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-31 17:07:03.279  1042  1523 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-31 17:07:03.279  1042  1523 D WifiNative-wlan0: doBoolean: SET ps 1
08-31 17:07:03.280  1042  1042 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-31 17:07:03.280  1042  1042 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-31 17:07:03.299  1042  1523 D WifiNative-wlan0: SET ps 1: returned true
08-31 17:07:03.300  1042  1530 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-31 17:07:03.302  1042  1523 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
,08-31 17:07:03.303  1042  1523 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-31 17:07:03.303  1042  1523 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-31 17:07:03.305  1042  1530 D ConnectivityService: ignoring duplicate network state non-change
08-31 17:07:03.313  1042  1042 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 17:07:03.314  1042  1042 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 17:07:03.314  1042  1042 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-31 17:07:03.314  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 17:07:03.314  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 17:07:03.316  1042  1530 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-31 17:07:03.318  1042  1530 D ConnectivityService: Adding iface wlan0 to network 101
08-31 17:07:03.320  1042  1042 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 17:07:03.320  1042  1042 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 17:07:03.320  1042  1042 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-31 17:07:03.322  1042  1042 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-31 17:07:03.326  1042  1042 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 17:07:03.326  1042  1042 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 17:07:03.326  1042  1042 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-31 17:07:03.327  1956  1956 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-31 17:07:03.329  1042  1042 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
,08-31 17:07:03.333  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 17:07:03.336  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 17:07:03.336  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 17:07:03.338  1042  1523 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-31 17:07:03.339  1042  1522 D LGWifiP2pService: InactiveState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-31 17:07:03.339  1042  1522 D LGWifiP2pService: P2pEnabledState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-31 17:07:03.339  1042  1522 D LGWifiP2pService: DefaultState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-31 17:07:03.343  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-31 17:07:03.344  1042  1042 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-31 17:07:03.344  1042  1042 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 17:07:03.344  1042  1042 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-31 17:07:03.346  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 17:07:03.346  1589  1589 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-31 17:07:03.346  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 17:07:03.352  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 17:07:03.353  1589  1589 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-31 17:07:03.353  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 17:07:03.355  1042  1530 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-31 17:07:03.356  1042  1530 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
08-31 17:07:03.357  1042  1530 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
08-31 17:07:03.357   313   893 E Netd    : netlink response contains error (File exists)
,08-31 17:07:03.359  1042  1530 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
08-31 17:07:03.360  1042  1530 D ConnectivityService: addLocalRoutetoDefaultNetwork
,08-31 17:07:03.360  1042  1530 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
08-31 17:07:03.361  1042  1530 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
08-31 17:07:03.390  1042  7210 D DhcpStateMachine: DHCPV4 request on wlan0
08-31 17:07:03.391  1042  7210 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-31 17:07:03.391  1042  7210 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
,08-31 17:07:03.384  7236  7236 W dhcpcd  : type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 17:07:03.384  7236  7236 W dhcpcd  : type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 17:07:03.399  1042  1523 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-31 17:07:03.400  1042  1523 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-31 17:07:03.400  1042  1523 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
08-31 17:07:03.401  1042  1762 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7237 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-31 17:07:03.401  1042  1523 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-31 17:07:03.401  1042  1523 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-31 17:07:03.401  1042  1762 I ActivityManager: Killing 6783:com.lge.bnr/1000 (adj 15): empty #17
08-31 17:07:03.401  1042  1523 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
,08-31 17:07:03.403  7236  7236 I dhcpcd  : version 5.5.6 starting
08-31 17:07:03.404  7236  7236 E dhcpcd  : get_duid: m
08-31 17:07:03.404  7236  7236 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-31 17:07:03.404  7236  7236 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-31 17:07:03.453  7236  7236 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-31 17:07:03.453  7236  7236 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-31 17:07:03.453  7236  7236 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-31 17:07:03.453  7236  7236 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
,08-31 17:07:03.454  7236  7236 D dhcpcd  : wlan0: sending REQUEST (xid 0x850771ce), next in 4.99 seconds
08-31 17:07:03.459  1042  1530 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-31 17:07:03.459  1042  1530 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-31 17:07:03.459  1042  1530 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-31 17:07:03.459  1042  1530 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-31 17:07:03.459  1042  1530 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-31 17:07:03.459  1042  1530 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 17:07:03.459  1042  1530 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-31 17:07:03.459  1042  1530 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 17:07:03.459  1042  7209 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-31 17:07:03.459  1042  1530 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-31 17:07:03.459  1042  7209 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-31 17:07:03.459  1042  1530 D ConnectivityService: currentScore = 0, newScore = 20
08-31 17:07:03.459  1042  1530 D ConnectivityService:    accepting network in place of null
08-31 17:07:03.459  1042  1530 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 17:07:03.459  1042  7209 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-31 17:07:03.459  1042  7209 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-31 17:07:03.460  1866  1866 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 17:07:03.460  1866  1866 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-31 17:07:03.460  1042  1523 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 17:07:03.461  1042  1523 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-31 17:07:03.461  1042  1530 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-31 17:07:03.461  1042  1530 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI, () - 101] isDefaultNetwork=true
08-31 17:07:03.461  1042  1530 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-31 17:07:03.463   313  7261 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-31 17:07:03.468  1042  2342 W libprocessgroup: failed to open /acct/uid_1000/pid_6783/cgroup.procs: No such file or directory
,08-31 17:07:03.474  1042  1530 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-31 17:07:03.474  1042  1530 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-31 17:07:03.474  1042  1530 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-31 17:07:03.476  1042  1042 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-31 17:07:03.476  1042  1042 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-31 17:07:03.476  1042  1042 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-31 17:07:03.476  1042  1042 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-31 17:07:03.476  1042  1530 D ConnectivityService: validation of new default Network = false
08-31 17:07:03.476  1042  1530 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-31 17:07:03.476  1042  1530 D DSQN    : enableDataServiceNotify 
08-31 17:07:03.476  1042  1530 D DSQN    : start dsqn bin
,08-31 17:07:03.493  7237  7237 I art     : Almond Protected OAT
,08-31 17:07:03.498  1042  1521 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
08-31 17:07:03.501  1042  1530 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-31 17:07:03.501  1042  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 17:07:03.501  1042  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 17:07:03.502  1042  1530 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 17:07:03.502  1589  1799 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-31 17:07:03.494  7263  7263 W dsqn    : type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 17:07:03.494  7263  7263 W dsqn    : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-31 17:07:03.508  1827  7262 I CheckinService: active receiver: enabled
08-31 17:07:03.508  1589  1589 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-31 17:07:03.508  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 17:07:03.509  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 17:07:03.514  7263  7263 E DSQN    : DSQN ssw
08-31 17:07:03.518  1827  7262 I CheckinService: Preparing to send checkin request
08-31 17:07:03.518  1827  7262 I EventLogService: Accumulating logs since 1472655958862
,08-31 17:07:03.544  7237  7237 D WeatherApplication: removeAccount
,08-31 17:07:03.545  7236  7236 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
08-31 17:07:03.546  1827  7262 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
08-31 17:07:03.547  7237  7237 D WeatherApplication: Account.length = 0
08-31 17:07:03.547  7237  7237 E WeatherApplication: OPERATOR:OPEN
08-31 17:07:03.549  7236  7236 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
08-31 17:07:03.549  7236  7236 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
08-31 17:07:03.550  7236  7236 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-31 17:07:03.550  7236  7236 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-31 17:07:03.550  7236  7236 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-31 17:07:03.550  7236  7236 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-31 17:07:03.550  7236  7236 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-31 17:07:03.550  7236  7236 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-31 17:07:03.550  7237  7237 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:7:3
08-31 17:07:03.554  7237  7237 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-31 17:07:03.554  7237  7237 D Weather.Utils: 2 : All the weather widget is gone.
,08-31 17:07:03.556  7237  7237 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-31 17:07:03.558  7237  7237 D WeatherAncestor: connectivity changed - connection : true
08-31 17:07:03.562  7237  7237 D WeatherService: 2 : isServiceAlived():false forecastCache:null
08-31 17:07:03.571  7237  7237 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-31 17:07:03.571  7237  7237 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-31 17:07:03.571  7237  7237 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
,08-31 17:07:03.595  7237  7237 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
,08-31 17:07:03.595  7237  7237 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:7:3
,08-31 17:07:03.622  1042  2027 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7278 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,08-31 17:07:03.664  1042  1954 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7298 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-31 17:07:03.665  1042  1954 I ActivityManager: Killing 2168:com.lge.music/u0a34 (adj 15): empty #17
,08-31 17:07:03.703   317  1370 V AudioFlinger: 2168 died, releasing its sessions
,08-31 17:07:03.705   317  1370 V AudioFlinger:  pid 1866 @ 0
08-31 17:07:03.705   317  1370 V AudioFlinger:  pid 3366 @ 1
08-31 17:07:03.705   317  1370 V AudioFlinger:  pid 3366 @ 2
,08-31 17:07:03.747  1042  1726 W libprocessgroup: failed to open /acct/uid_10034/pid_2168/cgroup.procs: No such file or directory
08-31 17:07:03.770  7278  7278 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-31 17:07:03.770  7278  7278 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-31 17:07:03.794  1042  7210 D DhcpStateMachine: DHCPV4 succeeded on wlan0
08-31 17:07:03.796  1042  7210 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-31 17:07:03.796  1042  7210 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-31 17:07:03.796  1042  7210 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
08-31 17:07:03.796  1042  7210 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-31 17:07:03.796  1042  7210 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-31 17:07:03.796  1042  7210 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
,08-31 17:07:03.796  1042  7210 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-31 17:07:03.797  1042  7210 D DhcpStateMachine: RunningState
08-31 17:07:03.804  7278  7278 I MultiDex: VM with version 2.1.0 has multidex support
08-31 17:07:03.804  7278  7278 I MultiDex: install
08-31 17:07:03.804  7278  7278 I MultiDex: VM has multidex support, MultiDex support library is disabled.
08-31 17:07:03.817  7278  7278 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,08-31 17:07:03.874   278   429 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,08-31 17:07:03.874   278   429 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-31 17:07:03.874   278   429 W Vold    : Returning OperationFailed - no handler for errno 0
08-31 17:07:03.874  7298  7325 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,08-31 17:07:03.876   278   429 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-31 17:07:03.876   278   429 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-31 17:07:03.877   278   429 W Vold    : Returning OperationFailed - no handler for errno 0
08-31 17:07:03.877  7298  7325 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,08-31 17:07:03.892   278   429 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-31 17:07:03.892   278   429 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-31 17:07:03.892   278   429 W Vold    : Returning OperationFailed - no handler for errno 0
,08-31 17:07:03.895  7298  7327 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-31 17:07:03.910   278   429 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-31 17:07:03.910   278   429 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
,08-31 17:07:03.911   278   429 W Vold    : Returning OperationFailed - no handler for errno 0
,08-31 17:07:03.911  7298  7327 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-31 17:07:04.018   313  7261 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,08-31 17:07:04.148  7298  7298 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-31 17:07:04.159  7298  7298 I LibraryLoader: Loading: webviewchromium
,08-31 17:07:04.163  7298  7298 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 2250-2254)
08-31 17:07:04.163  7298  7298 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-31 17:07:04.169  7298  7298 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1647489}
08-31 17:07:04.170  7298  7298 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-31 17:07:04.170  7298  7298 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-31 17:07:04.182  7298  7298 I BrowserStartupController: Initializing chromium process, renderers=0
,08-31 17:07:04.183  7298  7298 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-31 17:07:04.197   313  7261 D libc-netbsd: res_queryN name = clients3.google.com succeed
,08-31 17:07:04.202  7298  7298 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-31 17:07:04.203  7298  7298 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
08-31 17:07:04.204  7298  7298 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
08-31 17:07:04.205   317  1369 V AudioPolicyService: registerClient() client 0xb558aae0, uid 10093
08-31 17:07:04.207  7298  7349 W AudioManagerAndroid: Requires BLUETOOTH permission
08-31 17:07:04.219  7278  7296 D LgDataFeature: LgDataFeature() Constructor: none
08-31 17:07:04.219  7278  7296 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-31 17:07:04.221  7298  7298 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-31 17:07:04.221  7298  7298 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-31 17:07:04.221  7298  7298 I Adreno-EGL: Build Date: 12/12/14 금
08-31 17:07:04.221  7298  7298 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-31 17:07:04.221  7298  7298 I Adreno-EGL: Remote Branch: 
08-31 17:07:04.221  7298  7298 I Adreno-EGL: Local Patches: 
08-31 17:07:04.221  7298  7298 I Adreno-EGL: Reconstruct Branch: 
08-31 17:07:04.294  7298  7298 I NSApplication: Starting up...
,08-31 17:07:04.318   313   892 D LGDataListener: argv[0]=dsqncommand
,08-31 17:07:04.318   313   892 D LGDataListener: argv[1]=wlan0
08-31 17:07:04.318   313   892 D LGDataListener: argv[2]=1
08-31 17:07:04.318   313   892 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-31 17:07:04.318  1042  1115 D DSQN    : DSQM DsqnNotification wlan0  1
,08-31 17:07:04.319  1042  1115 D DSQN    : start to monitor internet connection
08-31 17:07:04.349  1042  2027 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7364 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,08-31 17:07:04.350  1042  2027 I ActivityManager: Killing 6080:com.android.vending/u0a44 (adj 15): empty #17
08-31 17:07:04.363   351   351 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 267us total 14.971ms
,08-31 17:07:04.375   351   351 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 230us total 11.555ms
08-31 17:07:04.386   351   351 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 229us total 10.483ms
,08-31 17:07:04.399  1042  1762 D WifiServiceImplEx: setWifiEnabled: false pid=6694, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-31 17:07:04.400  1042  1762 D WifiService: setWifiEnabled: false pid=6694, uid=10118
,08-31 17:07:04.400  1042  1762 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-31 17:07:04.401  1042  2046 W libprocessgroup: failed to open /acct/uid_10044/pid_6080/cgroup.procs: No such file or directory
08-31 17:07:04.412  1042  1042 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-31 17:07:04.412  1042  1042 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-31 17:07:04.412  1042  1042 D Ulp_jni : JNI:system_update. Event-4
,08-31 17:07:04.413  1042  1523 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-31 17:07:04.413  1042  1523 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-31 17:07:04.414  1042  1523 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-31 17:07:04.414  1042  1523 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-31 17:07:04.415  1042  1523 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-31 17:07:04.415  1042  1523 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-31 17:07:04.415  1042  1523 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-31 17:07:04.415  1042  1523 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-31 17:07:04.415  1042  1523 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-31 17:07:04.415  1042  1523 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-31 17:07:04.422  1042  1523 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-31 17:07:04.422  1042  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-31 17:07:04.422  7150  7150 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-31 17:07:04.422  1042  1522 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-31 17:07:04.422  1042  1522 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-31 17:07:04.422  1042  1523 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-31 17:07:04.422  1042  1523 D WifiNative-wlan0: doBoolean: SET ps 1
08-31 17:07:04.423  1042  1523 D WifiNative-wlan0: SET ps 1: returned true
08-31 17:07:04.423   313   893 D CommandListener: Clearing all IP addresses on wlan0
08-31 17:07:04.423  1042  7210 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-31 17:07:04.437  1042  7209 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.ConnectException: failed to connect to clients3.google.com/2a00:1450:4001:817::200e (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
,08-31 17:07:04.444  7364  7364 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-31 17:07:04.461  1042  1523 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 17:07:04.462  1042  1523 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 17:07:04.462  1042  1523 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 17:07:04.463  1042  1523 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 17:07:04.463  1042  1523 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 17:07:04.464  1042  1523 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
,08-31 17:07:04.466  1042  1530 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-31 17:07:04.466  1042  1530 D ConnectivityService: ignoring duplicate network state non-change
08-31 17:07:04.466  1042  1523 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-31 17:07:04.466  1042  1530 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
08-31 17:07:04.467  7382  7382 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=32 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
08-31 17:07:04.468  1042  1522 D LGWifiP2pService: InactiveState{ when=-7ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-31 17:07:04.468  1042  1522 D LGWifiP2pService: P2pEnabledState{ when=-7ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-31 17:07:04.468  1042  1522 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@22e4214
08-31 17:07:04.468  1042  1522 D LGWifiP2pService: P2pDisablingState
08-31 17:07:04.469  1042  1522 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-31 17:07:04.469  1042  1522 D LGWifiP2pService: p2p socket connection lost
08-31 17:07:04.469  1042  1522 D LGWifiP2pService: P2pDisabledState
08-31 17:07:04.469  1042  1523 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-31 17:07:04.469  1042  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-31 17:07:04.469  7150  7150 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-31 17:07:04.470  1042  1522 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-31 17:07:04.470  1042  1522 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-31 17:07:04.469  1042  1042 D WifiHS20: hidePasspointNotification off =false
08-31 17:07:04.471  1956  1956 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-31 17:07:04.471  1042  1523 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-31 17:07:04.471  1042  1523 D WifiNative-wlan0: doBoolean: SET ps 1
08-31 17:07:04.471  1042  1042 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 17:07:04.472  1042  1042 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 17:07:04.472  1042  1042 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-31 17:07:04.472  1042  1042 D WifiHS20: hidePasspointNotification off =false
08-31 17:07:04.472  1042  1523 D WifiNative-wlan0: SET ps 1: returned true
08-31 17:07:04.473  1042  1042 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 17:07:04.473  1042  1042 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 17:07:04.473  1042  1042 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-31 17:07:04.473  1042  1042 D WifiScanningService: SCAN_AVAILABLE : 1
08-31 17:07:04.473  1042  1042 D RttService: SCAN_AVAILABLE : 1
08-31 17:07:04.473  1042  1542 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-31 17:07:04.474  1042  1543 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHand,ler }
08-31 17:07:04.475  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 17:07:04.475  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 17:07:04.476  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 17:07:04.476  1956  1956 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-31 17:07:04.476  1956  1956 D WfdsService: WifiP2pState is changed : false
,08-31 17:07:04.481  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 17:07:04.481  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 17:07:04.482  1956  2323 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-31 17:07:04.482  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 17:07:04.482  1956  2323 D WfdsService: Set the WFDS Monitor: false
08-31 17:07:04.483  1956  2323 D WfdsMonitor: WFDS Monitor is stopped
08-31 17:07:04.483  1956  2323 D WfdsService: STATE : WfdsDisabledState - enter
08-31 17:07:04.483  1956  7154 D CtrlSupplicant: Received on exit socket, terminate
08-31 17:07:04.483  1956  7154 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-31 17:07:04.483  1956  7154 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-31 17:07:04.483  1956  7154 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-31 17:07:04.483  1956  2324 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-31 17:07:04.483  1956  2323 W WfdsService: DefaultState - msg [9445378] is not handled
08-31 17:07:04.531  1042  1530 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-31 17:07:04.531  1042  1530 D DSQN    : disableDataServiceNotify
08-31 17:07:04.531  1042  1530 D DSQN    : stop dsqn bin
08-31 17:07:04.531   313   893 D CommandListener: Clearing all IP addresses on wlan0
,08-31 17:07:04.532  7382  7382 I dex2oat : dex2oat took 64.355ms (threads: 4)
08-31 17:07:04.533  1042  1523 D WifiNative-p2p0: doBoolean: TERMINATE
08-31 17:07:04.533  1042  1523 D WifiNative-p2p0: TERMINATE: returned true
08-31 17:07:04.534  1042  1523 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-31 17:07:04.534  1042  1523 E WifiStateMachine: useWiFiOffloading() : false
08-31 17:07:04.534  1042  1523 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-31 17:07:04.534  1042  1042 D WifiHS20: hidePasspointNotification off =false
08-31 17:07:04.534  1042  1530 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
08-31 17:07:04.535  1042  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 17:07:04.535  1042  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 17:07:04.535  1042  1530 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 17:07:04.535  1042  1530 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-31 17:07:04.535  1042  1530 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-31 17:07:04.535  1042  1530 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-31 17:07:04.535  1042  1530 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-31 17:07:04.536  1042  7209 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-31 17:07:04.536  1042  7209 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-31 17:07:04.536  1589  1799 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-31 17:07:04.536  1042  7209 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-31 17:07:04.537  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-31 17:07:04.537  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 17:07:04.537  1042  1042 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 17:07:04.537  1042  1042 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 17:07:04.537  1042  1042 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-31 17:07:04.538  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 17:07:04.538  1042  1042 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-31 17:07:04.538  1042  1042 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-31 17:07:04.539  1042  1042 D WifiServerServiceExt: setSu,pplicantStateDISCONNECTED
08-31 17:07:04.539  1956  1956 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
,08-31 17:07:04.540  1042  1530 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-31 17:07:04.540  1042  1530 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-31 17:07:04.540  1042  1530 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-31 17:07:04.540  1042  1530 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 17:07:04.540  1042  1530 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 17:07:04.540  1042  1523 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 17:07:04.540  1042  1523 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-31 17:07:04.541  1866  1866 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 17:07:04.541  1866  1866 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-31 17:07:04.541  1042  1530 D NetworkManagementService: Removing idletimer
08-31 17:07:04.542  1042  1530 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 17:07:04.542  1042  1530 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
08-31 17:07:04.544  6694  6694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 17:07:04.544  6694  6694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 17:07:04.544  6694  6694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 17:07:04.544  6694  6694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 17:07:04.544  6694  6694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 17:07:04.544  6694  6694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 17:07:04.544  6694  6694 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 17:07:04.544  6694  6694 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 17:07:04.544  6694  6694 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 17:07:04.544  6694  6694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 17:07:04.544  6694  6694 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 17:07:04.544  6694  6694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 17:07:04.545  6694  6694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 17:07:04.545  6694  6694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 17:07:04.545  6694  6694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE ,multiple advertisement supported: NOT_SUPPORTED
08-31 17:07:04.545  6694  6694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 17:07:04.545  6694  6694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 17:07:04.545  6694  6694 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 17:07:04.545  6694  6694 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 17:07:04.545  6694  6694 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 17:07:04.545  6694  6694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 17:07:04.545  6694  6694 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 17:07:04.546  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 17:07:04.547  1042  1521 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-31 17:07:04.547  1042  1042 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-31 17:07:04.547  1042  1042 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-31 17:07:04.547  1042  1042 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-31 17:07:04.547  1042  1042 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-31 17:07:04.550  1042  1521 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-31 17:07:04.550  1042  1042 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-31 17:07:04.550  1042  1042 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-31 17:07:04.550  1042  1042 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-31 17:07:04.550  1042  1042 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-31 17:07:04.555  7278  7296 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-31 17:07:04.555  7278  7296 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-31 17:07:04.555  7278  7296 I Adreno-EGL: Build Date: 12/12/14 금
08-31 17:07:04.555  7278  7296 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-31 17:07:04.555  7278  7296 I Adreno-EGL: Remote Branch: 
08-31 17:07:04.555  7278  7296 I Adreno-EGL: Local Patches: 
08-31 17:07:04.555  7278  7296 I Adreno-EGL: Reconstruct Branch: 
,08-31 17:07:04.585  1589  1589 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-31 17:07:04.586  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 17:07:04.586  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-31 17:07:04.611  1589  1589 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-31 17:07:04.612  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 17:07:04.612  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 17:07:04.626  1042  7210 D DhcpStateMachine: StoppedState
08-31 17:07:04.626  1042  7210 D DhcpStateMachine: StoppedState{ when=-154ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,08-31 17:07:04.627  1042  1523 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-31 17:07:04.627  1042  1523 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-31 17:07:04.655  7150  7150 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-31 17:07:04.655  7150  7150 I wpa_supplicant: monitor socket send errors count : 1
08-31 17:07:04.655  7150  7150 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1956-4\x00 that cannot receive messages
,08-31 17:07:04.656  1042  7152 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-31 17:07:04.656  1042  7152 D WifiMonitor: Dropping event because (p2p0) is stopped
08-31 17:07:04.679  7278  7296 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-31 17:07:04.679  7278  7296 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-31 17:07:04.679  7278  7296 I Adreno-EGL: Build Date: 12/12/14 금
08-31 17:07:04.679  7278  7296 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-31 17:07:04.679  7278  7296 I Adreno-EGL: Remote Branch: 
08-31 17:07:04.679  7278  7296 I Adreno-EGL: Local Patches: 
08-31 17:07:04.679  7278  7296 I Adreno-EGL: Reconstruct Branch: 
08-31 17:07:04.680  1042  1058 I art     : Explicit concurrent mark sweep GC freed 100321(4MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/65MB, paused 1.533ms total 100.688ms
,08-31 17:07:04.692  7150  7150 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-31 17:07:04.693  7150  7150 W wpa_supplicant: USIM:  scard_deinit function
08-31 17:07:04.694  1042  1117 D Tethering: InitialState.processMessage what=4
08-31 17:07:04.694  1042  7152 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-31 17:07:04.695  1042  7152 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-31 17:07:04.695  1042  7152 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-31 17:07:04.695  1042  7152 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-31 17:07:04.695  1042  7152 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-31 17:07:04.695  1042  7152 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-31 17:07:04.695  1042  1117 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-31 17:07:04.695  1042  1523 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=122771
08-31 17:07:04.696  1042  1523 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=122772
08-31 17:07:04.697  1042  1523 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=122772  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-31 17:07:04.697  1042  1523 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=122773  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-31 17:07:04.697  1042  1523 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-31 17:07:04.698  1042  1523 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,08-31 17:07:04.766  7278  7296 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-31 17:07:04.766  7278  7296 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-31 17:07:04.766  7278  7296 I Adreno-EGL: Build Date: 12/12/14 금
08-31 17:07:04.766  7278  7296 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-31 17:07:04.766  7278  7296 I Adreno-EGL: Remote Branch: 
08-31 17:07:04.766  7278  7296 I Adreno-EGL: Local Patches: 
08-31 17:07:04.766  7278  7296 I Adreno-EGL: Reconstruct Branch: 
,08-31 17:07:04.809  7150  7150 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-31 17:07:04.809  1042  7152 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-31 17:07:04.809  1042  7152 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-TERMINATING 
08-31 17:07:04.810  1042  7152 D WifiMonitor: Disconnecting from the supplicant, no more events
08-31 17:07:04.810  1042  1523 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 44 0
,08-31 17:07:04.818  6479  6479 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-31 17:07:04.821  6479  6511 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-31 17:07:04.843  2230  2230 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-31 17:07:04.851  7098  7098 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-31 17:07:04.851  7098  7098 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-31 17:07:04.851  7098  7098 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-31 17:07:04.851  7098  7098 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-31 17:07:04.853  7098  7098 I AppUp4:CustModeStarterReceiver: onReceive
,08-31 17:07:04.857  7098  7098 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2107a606
,08-31 17:07:04.857  7098  7098 D AppUp4:CustFacade: isCustomizationCompleted : false
08-31 17:07:04.857  7098  7098 D AppUp4:CustFacade: isPhone : true
08-31 17:07:04.858  7098  7098 D AppUp4:CustModeStarterReceiver: begin check event
08-31 17:07:04.858  7098  7098 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-31 17:07:04.861  4304  4304 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-31 17:07:04.861  4304  4304 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-31 17:07:04.864  4304  4304 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-31 17:07:04.865  4304  4304 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-31 17:07:04.870  7132  7132 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-31 17:07:04.879  4304  7408 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-31 17:07:04.879  4304  7408 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-31 17:07:04.880  4304  7407 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-31 17:07:04.889  7132  7409 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-31 17:07:04.894  3366  3366 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-31 17:07:04.895  3366  3366 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-31 17:07:04.895  3366  3366 I LgeMiscReceiver: networkInfo.isConnected() = false
08-31 17:07:04.898  7168  7168 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-31 17:07:04.898  7168  7168 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-31 17:07:04.906  6986  7411 W FormManager: Network not available. Please check & try again.
08-31 17:07:04.906  6986  7412 V FormManager: Network unavailable.
,08-31 17:07:04.908  6986  7412 V FormManager: Network unavailable.
08-31 17:07:04.911  1042  1523 D WifiOffDelayIfNotUsed: stopMonitoring
08-31 17:07:04.911  1042  1523 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-31 17:07:04.911  1042  1523 E WifiStateMachine: useWiFiOffloading() : false
08-31 17:07:04.911  1042  1523 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-31 17:07:04.911  1956  1956 D WfdsService: Supplicant Connection state is changed : false
08-31 17:07:04.911  1956  2323 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-31 17:07:04.911  1956  2323 D WfdsService: Set the WFDS Monitor: false
08-31 17:07:04.911  1956  2323 D WfdsMonitor: WFDS Monitor is stopped
08-31 17:07:04.914  7237  7237 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:7:4
08-31 17:07:04.915  7237  7237 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-31 17:07:04.915  7237  7237 D Weather.Utils: 2 : All the weather widget is gone.
08-31 17:07:04.916  7237  7237 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-31 17:07:04.916  7237  7237 D WeatherAncestor: connectivity changed - connection : true
08-31 17:07:04.916  7237  7237 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@15aacaf4
08-31 17:07:04.917  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-31 17:07:04.918  1956  1956 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-31 17:07:04.918  7237  7237 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-31 17:07:04.918  7237  7237 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-31 17:07:04.918  7237  7237 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-31 17:07:04.918  7237  7237 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-31 17:07:04.918  7237  7237 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:7:4
,08-31 17:07:04.920  2479  2479 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 17:07:04.922  6694  6694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 17:07:04.925  1042  1042 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-31 17:07:04.925  1042  1528 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-31 17:07:04.925  1042  1528 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-31 17:07:04.927  6694  6694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 17:07:04.945  6878  6878 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-31 17:07:04.945  6878  6878 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-31 17:07:04.945  6878  6878 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-31 17:07:04.945  6878  6878 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
,08-31 17:07:04.946  6878  6878 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-31 17:07:04.947  6878  6878 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-31 17:07:04.947  6878  6878 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-31 17:07:04.947  6878  6878 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-31 17:07:04.947  6878  6878 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-31 17:07:04.947  6878  6878 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-31 17:07:04.947  6878  6878 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-31 17:07:04.953  6917  6917 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-31 17:07:04.956  6878  6878 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-31 17:07:04.961  6986  7415 W FormManager: Network not available. Please check & try again.
08-31 17:07:04.963  6878  6878 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 17:07:04.973  6986  7416 V FormManager: Network unavailable.
,08-31 17:07:04.977  6986  7416 V FormManager: Network unavailable.
08-31 17:07:04.978  6917  6917 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-31 17:07:04.981  6878  6878 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-31 17:07:04.984  6986  7417 W FormManager: Network not available. Please check & try again.
,08-31 17:07:04.989  6986  7418 V FormManager: Network unavailable.
08-31 17:07:04.990  6986  7418 V FormManager: Network unavailable.
,08-31 17:07:05.000  6878  6878 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 17:07:05.010  4304  4304 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-31 17:07:05.010  4304  4304 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-31 17:07:05.012  4304  4304 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-31 17:07:05.014  4304  4304 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-31 17:07:05.020  4304  7419 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-31 17:07:05.025  4304  7420 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-31 17:07:05.025  4304  7420 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-31 17:07:05.076  1042  2342 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7421 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-31 17:07:05.180   313  7439 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-31 17:07:05.181  1042  1115 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,08-31 17:07:05.183  1827  7262 E CheckinTask: Checkin failed: https://android.clients.google.com/checkin (request #0): java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
08-31 17:07:05.185  7421  7421 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-31 17:07:05.186  7421  7421 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
08-31 17:07:05.196  1827  7262 I CheckinService: active receiver: disabled
,08-31 17:07:05.200  7421  7421 V [BNRBootReceiver]: Boot Receiver Return
08-31 17:07:05.202  7421  7421 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-31 17:07:05.211  6479  6479 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-31 17:07:05.224  6878  6878 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 17:07:05.231  6878  6878 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-31 17:07:05.242  6945  6945 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 17:07:05.243  6945  6945 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 17:07:05.245  6945  6945 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-31 17:07:05.250  6878  6878 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
08-31 17:07:05.254  6878  6878 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-31 17:07:05.260  6479  6479 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-31 17:07:05.277  6878  6878 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 17:07:05.287  6878  6878 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 17:07:05.296  6945  6945 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-31 17:07:05.297  6945  6945 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 17:07:05.299  6945  6945 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-31 17:07:05.304  6479  6479 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-31 17:07:05.315  6878  6878 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 17:07:05.325  6814  7070 D UEI.SmartControl: Internal timer expired: 2
,08-31 17:07:05.325  6814  7070 D UEI.SmartControl: unbind internal service
08-31 17:07:05.326  6878  6878 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 17:07:05.338  6945  6945 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-31 17:07:05.339  6945  6945 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 17:07:05.342  6945  6945 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-31 17:07:05.351  6479  6479 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 17:07:05.370  6878  6878 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 17:07:05.384  6878  6878 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-31 17:07:05.401  6945  6945 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-31 17:07:05.405  6945  6945 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION,
08-31 17:07:05.406  6945  6945 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-31 17:07:05.411  6479  6479 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 17:07:05.425  6878  6878 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 17:07:05.433  6878  6878 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 17:07:05.439  6814  7067 D serial_port: close(fd = 24)
,08-31 17:07:05.443  6945  6945 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-31 17:07:05.444  6945  6945 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 17:07:05.444  6945  6945 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-31 17:07:05.446  6814  7067 I UEI.SmartControl: Serial port is closed.
08-31 17:07:05.449  6479  6479 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 17:07:05.461  6878  6878 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 17:07:05.469  6878  6878 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-31 17:07:05.481  6945  6945 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 17:07:05.482  6945  6945 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 17:07:05.483  6945  6945 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-31 17:07:05.490  6479  6479 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 17:07:05.507  6878  6878 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 17:07:05.517  6878  6878 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 17:07:05.527  6945  6945 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-31 17:07:05.529  6945  6945 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-31 17:07:05.529  6945  6945 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-31 17:07:05.542  6479  6479 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-31 17:07:05.555  6878  6878 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 17:07:05.573  6878  6878 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 17:07:05.582  6945  6945 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 17:07:05.583  6945  6945 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-31 17:07:05.591  6945  6945 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-31 17:07:05.598  6479  6479 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 17:07:05.615  6878  6878 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 17:07:05.622  6878  6878 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-31 17:07:05.634  6945  6945 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-31 17:07:05.635  6945  6945 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-31 17:07:05.637  6945  6945 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-31 17:07:05.648  6479  6479 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-31 17:07:05.661  6917  6917 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,08-31 17:07:05.679  1042  1529 D WifiService: New client listening to asynchronous messages
,08-31 17:07:05.681  6917  6917 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-31 17:07:05.690  6878  6878 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 17:07:05.704  6878  6878 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-31 17:07:05.719  6945  6945 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 17:07:05.720  6945  6945 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-31 17:07:05.723  6945  6945 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-31 17:07:05.728  6945  6945 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-31 17:07:05.729  6945  6945 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-31 17:07:05.744  6479  6479 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-31 17:07:05.759  6917  6917 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,08-31 17:07:05.763  6917  6917 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-31 17:07:05.774  6878  6878 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 17:07:05.794  6878  6878 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 17:07:05.815  6945  6945 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 17:07:05.816  6945  6945 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-31 17:07:05.819  6945  6945 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-31 17:07:05.821  6945  6945 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-31 17:07:05.822  6945  6945 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-31 17:07:05.832  1042  1918 I ActivityManager: Killing 6898:com.lge.lifetracker/u0a37 (adj 15): empty #17
,08-31 17:07:05.951  2230  2230 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
08-31 17:07:05.952  1042  1057 W libprocessgroup: failed to open /acct/uid_10037/pid_6898/cgroup.procs: No such file or directory
,08-31 17:07:05.970  2230  2230 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,08-31 17:07:05.971  2230  2230 D c       : Getting all permits...
08-31 17:07:05.971  2230  2230 D a       : Opening database...
08-31 17:07:05.975  2230  2230 D a       : Opening database auth.proximity.permit_store...
08-31 17:07:05.976  2230  2230 D a       : Closing database...
08-31 17:07:05.987  6479  6479 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-31 17:07:05.992  6917  6917 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-31 17:07:05.993  6917  6917 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-31 17:07:05.993  6917  6917 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-31 17:07:05.997  6878  6878 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 17:07:06.004  6878  6878 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 17:07:06.010  6945  6945 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-31 17:07:06.010  6945  6945 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 17:07:06.012  6945  6945 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-31 17:07:06.017  6479  6479 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 17:07:06.021  6917  6917 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-31 17:07:06.021  6917  6917 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-31 17:07:06.021  6917  6917 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-31 17:07:06.025  6878  6878 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 17:07:06.032  6878  6878 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 17:07:06.039  6945  6945 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-31 17:07:06.040  6945  6945 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 17:07:06.042  6945  6945 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-31 17:07:06.045  6479  6479 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 17:07:06.050  6917  6917 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-31 17:07:06.050  6917  6917 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-31 17:07:06.050  6917  6917 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-31 17:07:06.053  6878  6878 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 17:07:06.060  6878  6878 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 17:07:06.067  6945  6945 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-31 17:07:06.068  6945  6945 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 17:07:06.070  6945  6945 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-31 17:07:06.079  6917  6917 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-31 17:07:06.083  6878  6878 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-31 17:07:06.093  6878  6878 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 17:07:06.093  6986  7451 W FormManager: Network not available. Please check & try again.
,08-31 17:07:06.099  6986  7452 V FormManager: Network unavailable.
08-31 17:07:06.107  6986  7452 V FormManager: Network unavailable.
,08-31 17:07:06.109  4304  4304 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-31 17:07:06.110  4304  4304 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-31 17:07:06.111  4304  4304 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-31 17:07:06.115  4304  4304 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-31 17:07:06.121  4304  7453 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-31 17:07:06.127  6917  6917 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-31 17:07:06.127  6917  6917 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
,08-31 17:07:06.128  4304  7454 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-31 17:07:06.129  4304  7454 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-31 17:07:06.130  6917  6917 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-31 17:07:06.134  6878  6878 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-31 17:07:06.142  6878  6878 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 17:07:06.150  6986  7456 W FormManager: Network not available. Please check & try again.
08-31 17:07:06.163  2230  2230 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,08-31 17:07:06.166  6986  7457 V FormManager: Network unavailable.
,08-31 17:07:06.170  6986  7457 V FormManager: Network unavailable.
,08-31 17:07:06.173  1042  1523 E WifiStateMachine:  InitialState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-517756355] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-31 17:07:06.173  1042  1523 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:0] from screen [on:0 period:-517756355] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-31 17:07:06.476  1042  1530 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE,
,08-31 17:07:06.500  1042  1117 D Tethering: MasterInitialState.processMessage what=3
08-31 17:07:06.508  6694  6694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 17:07:06.512  6694  6694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 17:07:06.516  1042  1108 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-31 17:07:06.519  6479  6479 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-31 17:07:06.520  6479  6511 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-31 17:07:06.533  5759  5759 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-31 17:07:06.551  2230  2230 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-31 17:07:06.570  7098  7098 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-31 17:07:06.570  7098  7098 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-31 17:07:06.570  7098  7098 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-31 17:07:06.570  7098  7098 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-31 17:07:06.575  7098  7098 I AppUp4:CustModeStarterReceiver: onReceive
08-31 17:07:06.579  7098  7098 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2107a606
08-31 17:07:06.579  7098  7098 D AppUp4:CustFacade: isCustomizationCompleted : false
08-31 17:07:06.579  7098  7098 D AppUp4:CustFacade: isPhone : true
08-31 17:07:06.580  7098  7098 D AppUp4:CustModeStarterReceiver: begin check event
08-31 17:07:06.580  7098  7098 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-31 17:07:06.585  4304  4304 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-31 17:07:06.585  4304  4304 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-31 17:07:06.587  4304  4304 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-31 17:07:06.592  4304  4304 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-31 17:07:06.600  7132  7132 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-31 17:07:06.623  4304  7463 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-31 17:07:06.637  7132  7462 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-31 17:07:06.647  1042  1108 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 17:07:06.649  6986  7477 W FormManager: Network not available. Please check & try again.
08-31 17:07:06.650  4304  7464 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-31 17:07:06.650  4304  7464 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-31 17:07:06.653  6986  7478 V FormManager: Network unavailable.
08-31 17:07:06.659  6986  7478 V FormManager: Network unavailable.
08-31 17:07:06.663  3366  3366 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-31 17:07:06.663  3366  3366 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-31 17:07:06.663  3366  3366 I LgeMiscReceiver: networkInfo.isConnected() = true
08-31 17:07:06.663  3366  3366 D PhoneState: setPdpRejectCasuse : false
,08-31 17:07:06.668  7168  7168 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-31 17:07:06.668  7168  7168 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-31 17:07:06.683  7237  7237 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:7:6
,08-31 17:07:06.684  7237  7237 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
,08-31 17:07:06.685  7237  7237 D Weather.Utils: 2 : All the weather widget is gone.
,08-31 17:07:06.687  7237  7237 D UpdateThreadPoolManager: 2 : This is isUpdating : false
,08-31 17:07:06.687  7237  7237 D WeatherAncestor: connectivity changed - connection : true
,08-31 17:07:06.687  7237  7237 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@15aacaf4
08-31 17:07:06.688  7237  7237 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-31 17:07:06.688  7237  7237 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-31 17:07:06.688  7237  7237 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-31 17:07:06.688  7237  7237 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-31 17:07:06.688  7237  7237 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:7:6
08-31 17:07:07.415  1042  2342 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 17:07:07.416  1042  2342 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-31 17:07:07.448  1042  1042 D LocationManagerService: getAllProviders()=[passive, gps, network]
,08-31 17:07:07.450  1042  1042 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-31 17:07:07.451  1042  1042 D Ulp_jni : JNI:system_update. Event-4
08-31 17:07:07.451  1042  1117 D BluetoothManagerService: Message: 1
08-31 17:07:07.451  1042  1117 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
,08-31 17:07:07.481  1042  1117 D BluetoothManagerService: Message: 20
08-31 17:07:07.481  1042  1117 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3d3a63d6:true
08-31 17:07:07.483  7025  7025 D BluetoothAdapterState: make
,08-31 17:07:07.490  7025  7025 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-31 17:07:07.490  7025  7025 I bluedroid-qcom: init
08-31 17:07:07.491  7025  7494 I BluetoothAdapterState: Entering OffState
08-31 17:07:07.492  7025  7025 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-31 17:07:07.492  7025  7025 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-31 17:07:07.492  7025  7025 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-31 17:07:07.492  7025  7025 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-31 17:07:07.492  7025  7025 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-31 17:07:07.494  7025  7025 I bluedroid-qcom: get_profile_interface socket
08-31 17:07:07.494  7025  7025 I bluedroid-qcom: get_profile_interface map_client
,08-31 17:07:07.498  7025  7498 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-31 17:07:07.494  7497  7497 W bdaddr_loader: type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 17:07:07.504  7025  7498 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-31 17:07:07.494  7497  7497 W bdaddr_loader: type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 17:07:07.515  7497  7497 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-31 17:07:07.515  7497  7497 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-31 17:07:07.515  7497  7497 I LGFTMITEM: [GET_FTM][id=8], offset=16384
,08-31 17:07:07.518  1042  1042 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-31 17:07:07.519  1042  1117 D BluetoothManagerService: Message: 40
08-31 17:07:07.519  1042  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-31 17:07:07.520  1042  1042 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-31 17:07:07.520  1042  1042 D BluetoothManagerService: Stored Bluetooth name: G3
08-31 17:07:07.521  7025  7040 I bluedroid-qcom: config_hci_snoop_log
08-31 17:07:07.522  1042  1117 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-31 17:07:07.522  1042  1117 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-31 17:07:07.523  7497  7497 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-31 17:07:07.530  7025  7494 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
,08-31 17:07:07.533  7497  7497 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-31 17:07:07.533  7497  7497 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-31 17:07:07.535  7025  7498 D BluetoothAdapterProperties: Name is: G3
08-31 17:07:07.535  7025  7494 D BluetoothAdapterProperties: Setting state to 11
08-31 17:07:07.536  7025  7494 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-31 17:07:07.536  1042  1117 D BluetoothManagerService: Message: 60
08-31 17:07:07.536  1042  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-31 17:07:07.536  1042  1117 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-31 17:07:07.542  1956  1956 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-31 17:07:07.544  1589  1589 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-31 17:07:07.545  1042  1530 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-31 17:07:07.548  6694  6694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 17:07:07.552  6878  6878 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-31 17:07:07.553  6694  6694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 17:07:07.555  1042  1530 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-31 17:07:07.571  7025  7025 V BluetoothPbapReceiver: PbapReceiver onReceive 
,08-31 17:07:07.574  7025  7025 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-31 17:07:07.574  7025  7025 V BluetoothPbapReceiver: ***********state = 11
,08-31 17:07:07.586  1042  1108 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-31 17:07:07.587  7025  7494 I LGBluetoothServiceJni: classInitNative: succeeds
08-31 17:07:07.588  1042  1117 D Tethering: MasterInitialState.processMessage what=3
08-31 17:07:07.593  1042  1117 D Tethering: MasterInitialState.processMessage what=3
,08-31 17:07:07.598  6694  6694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 17:07:07.600  6694  6694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 17:07:07.602  6694  6694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 17:07:07.605  6694  6694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 17:07:07.610  6479  6479 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-31 17:07:07.611  7025  7494 D BluetoothBondStateMachine: make
08-31 17:07:07.612  6479  6511 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-31 17:07:07.613  5759  5759 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-31 17:07:07.614  1042  1108 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-31 17:07:07.615  2230  2230 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-31 17:07:07.619  7025  7494 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15aacaf4
08-31 17:07:07.619  7025  7494 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-31 17:07:07.619  7025  7494 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15aacaf4
08-31 17:07:07.620  7025  7494 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-31 17:07:07.620  7025  7514 I BluetoothBondStateMachine: StableState(): Entering Off State
08-31 17:07:07.621  7025  7494 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-31 17:07:07.624  5759  5759 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-31 17:07:07.627  7025  7494 E BluetoothAdapterService: File transfer profiles supported!!
08-31 17:07:07.675  1042  2046 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7516 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-31 17:07:07.685  1042  1108 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 17:07:07.685  1042  1108 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 17:07:07.686  7025  7025 D HeadsetService: Received start request. Starting profile...
08-31 17:07:07.686  7025  7025 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-31 17:07:07.687  7025  7025 D LGBluetoothHfpAdapter: Version 1.6
08-31 17:07:07.690  7025  7025 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,08-31 17:07:07.691  7025  7025 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-31 17:07:07.691  7025  7025 D HeadsetStateMachine: make
08-31 17:07:07.693  7025  7494 E BluetoothAdapterService: File transfer profiles supported!!
08-31 17:07:07.697  2230  2230 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
08-31 17:07:07.702  7025  7494 E BluetoothAdapterService: File transfer profiles supported!!
,08-31 17:07:07.721  7098  7098 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-31 17:07:07.721  7098  7098 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-31 17:07:07.721  7098  7098 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-31 17:07:07.721  7098  7098 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-31 17:07:07.722  7025  7494 E BluetoothAdapterService: File transfer profiles supported!!
08-31 17:07:07.728  7025  7025 D LgDataFeature: LgDataFeature() Constructor: none
08-31 17:07:07.729  7025  7025 D LgDataFeature: LgDataFeature() Constructor Done, null
08-31 17:07:07.731  7098  7098 I AppUp4:CustModeStarterReceiver: onReceive
08-31 17:07:07.732  7025  7494 E BluetoothAdapterService: File transfer profiles supported!!
,08-31 17:07:07.735  7025  7025 D HeadsetStateMachine: max_hf_connections = 1
08-31 17:07:07.735  7025  7025 I bluedroid-qcom: get_profile_interface handsfree
08-31 17:07:07.737  7025  7025 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-31 17:07:07.738   317  1370 V AudioPolicyService: registerClient() client 0xb558a9c0, uid 1002
08-31 17:07:07.739   317  1369 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-31 17:07:07.739   317  1369 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-31 17:07:07.739   317  1369 V AudioPolicyManagerEx: getOutput() returns output 2
08-31 17:07:07.739  7025  7025 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-31 17:07:07.739   317  3990 V AudioFlinger: registerClient() client 0xb5581928, pid 7025
08-31 17:07:07.740   317  1364 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-31 17:07:07.740   317  1364 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-31 17:07:07.740  7025  7025 V ToneGenerator: Create Track: 0xb4928a80
08-31 17:07:07.740  7025  7025 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-31 17:07:07.740  7025  7025 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-31 17:07:07.740   317  1369 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-31 17:07:07.740   317  1369 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-31 17:07:07.740  1042  2342 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-31 17:07:07.740  1042  2342 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-31 17:07:07.740   317  1369 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-31 17:07:07.740   317  1369 V AudioPolicyManagerEx: getOutput() returns output 2
08-31 17:07:07.740  7025  7025 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-31 17:07:07.740  7025  7041 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-31 17:07:07.740  7025  7041 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-31 17:07:07.740   317  1365 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-31 17:07:07.740   317   317 I AudioFlinger: isAudioPlaybackHookOn() false
08-31 17:07:07.740   317  1365 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-31 17:07:07.741   317  3990 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-31 17:07:07.741   317  3990 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-31 17:07:07.741   317  3990 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-31 17:07:07.741   317  3990 V AudioPolicyManagerEx: getOutput() returns output 2
08-31 17:07:07.741  7025  7025 V AudioSystem: getLatency() output 2, latency 50
08-31 17:07:07.741  7025  7025 V AudioSystem: getFrameCount() output 2, frameCount 960
08-31 17:07:07.741  7025  7025 V AudioTrack: createTrack_l() output 2 afLatency 50
08-31 17:07:07.741  1589  2592 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-31 17:07:07.741  1589  2592 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-31 17:07:07.741  1589  2592 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-31 17:07:07.741  1042  2341 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-31 17:07:07.741  1589  2592 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-31 17:07:07.741  1042  2341 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-31 17:07:07.741  3366  3383 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-31 17:07:07.741  3366  3383 V AudioSystem: ioConfigChanged() opening already existing output,! 2
08-31 17:07:07.741  3366  3383 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-31 17:07:07.741  3366  3383 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-31 17:07:07.741  7025  7040 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-31 17:07:07.741  7025  7040 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-31 17:07:07.741   317  3990 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-31 17:07:07.741   317  3990 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-31 17:07:07.742   317  3990 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-31 17:07:07.742   317  3990 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-31 17:07:07.742   317  3990 V AudioFlinger: createTrack() lSessionId: 22
08-31 17:07:07.742  1866  2524 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-31 17:07:07.742  1866  2524 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-31 17:07:07.742  1866  2524 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-31 17:07:07.742  1866  2524 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-31 17:07:07.743  7025  7494 E BluetoothAdapterService: File transfer profiles supported!!
08-31 17:07:07.745  7025  7025 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-31 17:07:07.745   317   317 V AudioFlinger: acquiring 22 from 7025, for 7025
08-31 17:07:07.745   317   317 V AudioFlinger:  added new entry for 22
08-31 17:07:07.745  7025  7025 V ToneGenerator: ToneGenerator INIT OK, time: 125837
08-31 17:07:07.745  7098  7098 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2107a606
08-31 17:07:07.745  7098  7098 D AppUp4:CustFacade: isCustomizationCompleted : false
08-31 17:07:07.745  7025  7025 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15aacaf4
08-31 17:07:07.745  7098  7098 D AppUp4:CustFacade: isPhone : true
08-31 17:07:07.745  7098  7098 D AppUp4:CustModeStarterReceiver: begin check event
08-31 17:07:07.746  7098  7098 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-31 17:07:07.746  7025  7527 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-31 17:07:07.746  7025  7527 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-31 17:07:07.747  7025  7527 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-31 17:07:07.747  7025  7527 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-31 17:07:07.747  7025  7025 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15aacaf4
,08-31 17:07:07.748   317  3990 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7025
08-31 17:07:07.749  7025  7025 D A2dpService: Received start request. Starting profile...
08-31 17:07:07.750  7025  7025 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-31 17:07:07.750  7025  7494 E BluetoothAdapterService: File transfer profiles supported!!
08-31 17:07:07.750  7025  7025 V Avrcp   : make
08-31 17:07:07.751  7025  7025 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-31 17:07:07.751  7025  7025 I bluedroid-qcom: get_profile_interface avrcp
08-31 17:07:07.751   317  3990 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-31 17:07:07.751   317  3990 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-31 17:07:07.751   317  3990 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-31 17:07:07.751   317  3990 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-31 17:07:07.751   317  3990 V voice   : voice_set_parameters: exit with code(0)
08-31 17:07:07.751   317  3990 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-31 17:07:07.751   317  3990 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-31 17:07:07.752   317  3990 V msm8974_platform: platform_set_parameters: exit with code(0)
08-31 17:07:07.752   317  3990 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-31 17:07:07.752   317  3990 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-31 17:07:07.752   317  3990 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-31 17:07:07.752  7025  7527 V ToneGenerator: ToneGenerator destructor
08-31 17:07:07.752  7025  7527 V ToneGenerator: stopTone
08-31 17:07:07.752  7025  7527 V ToneGenerator: Delete Track: 0xb4928a80
08-31 17:07:07.753  7025  7527 V AudioTrack: ~AudioTrack, releasing session id from 7025 on behalf of 7025
08-31 17:07:07.753   317  1370 V AudioPolicyService: AudioCommandThread() adding release output 2
08-31 17:07:07.753   317  1370 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-31 17:07:07.753   317  1270 V AudioPolicyService: AudioCommandThread() waking up
08-31 17:07:07.753   317  1270 V AudioPolicyService: AudioCommandThread() processing release output 2
08-31 17:07:07.753   317  1270 V AudioPolicyManager: releaseOutput() 2
08-31 17:07:07.753   317  1270 V AudioPolicyService: AudioCommandThread() going to sleep
08-31 17:07:07.753   317  1370 V AudioFlinger: PlaybackThread::Track destructor
08-31 17:07:07.753   317  1370 V AudioFlinger: removeClient_l() pid 7025, calling pid 317
08-31 17:07:07.753   317  1370 V AudioFlinger: releasing 22 from 7025 for 7025
08-31 17:07:07.753   317  1370 V AudioFlinger:  decremented refcount to 0
08-31 17:07:07.753   317  1370 V AudioFlinger: purging stale effects
08-31 17:07:07.755  4304  4304 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-31 17:07:07.755  4304  4304 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-31 17:07:07.756  4304  4304 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-31 17:07:07.760  4304  4304 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-31 17:07:07.761  7025  7025 V AudioManager: registerRemoteContr,oller: size of Media player list: 0
08-31 17:07:07.763  7025  7025 E AudioManager: No RCC entry present to update
08-31 17:07:07.763  7025  7025 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-31 17:07:07.765  7025  7025 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-31 17:07:07.766  7025  7025 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-31 17:07:07.766  7025  7025 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-31 17:07:07.767  7132  7132 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-31 17:07:07.770  7025  7025 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-31 17:07:07.771  7025  7494 V LGMDMManager: Create singleton instance
,08-31 17:07:07.772  7025  7494 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-31 17:07:07.775  4304  7538 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-31 17:07:07.777  4304  7539 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-31 17:07:07.777  4304  7539 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-31 17:07:07.825  7516  7516 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-31 17:07:07.825  7516  7516 W LG Account v2.2: No ProfileInfo entries
08-31 17:07:07.825  7516  7516 I LG Account v2.2: isEnabled: false
08-31 17:07:07.825  7516  7516 I Feature : [Lifetracker]ver: 4.21.112(40211120)
,08-31 17:07:07.826  7516  7516 I Feature : [Lifetracker]Country: EU
08-31 17:07:07.826  7516  7516 I Feature : [Lifetracker]Operator: OPEN
08-31 17:07:07.826  7516  7516 I Feature : [Lifetracker]Ranking support: false
08-31 17:07:07.826  7516  7516 I Feature : [Lifetracker]Comfort support: false
08-31 17:07:07.826  7516  7516 I Feature : [Lifetracker]Accessory: true
08-31 17:07:07.826  7516  7516 I Feature : [Lifetracker]Health device: true
08-31 17:07:07.826  7516  7516 I Feature : [Lifetracker]Extra Pedometer: false
08-31 17:07:07.826  7516  7516 I Feature : [Lifetracker]Blood glucose device: false
08-31 17:07:07.826  7516  7516 I Feature : [Lifetracker]Device Number: 3
,08-31 17:07:07.840  7132  7544 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-31 17:07:07.843  3366  3366 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,08-31 17:07:07.843  3366  3366 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-31 17:07:07.844  3366  3366 I LgeMiscReceiver: networkInfo.isConnected() = false
08-31 17:07:07.847  6878  6878 D BluetoothPermissionRequest: onReceive
08-31 17:07:07.849  7168  7168 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-31 17:07:07.849  7168  7168 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-31 17:07:07.850  6986  7543 W FormManager: Network not available. Please check & try again.
08-31 17:07:07.857  6878  6878 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-31 17:07:07.867  7237  7237 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:7:7
08-31 17:07:07.868  6986  7545 V FormManager: Network unavailable.
08-31 17:07:07.869  7237  7237 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-31 17:07:07.869  7237  7237 D Weather.Utils: 2 : All the weather widget is gone.
,08-31 17:07:07.869  7237  7237 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-31 17:07:07.869  6986  7545 V FormManager: Network unavailable.
08-31 17:07:07.869  7237  7237 D WeatherAncestor: connectivity changed - connection : true
08-31 17:07:07.869  7237  7237 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@15aacaf4
08-31 17:07:07.871  7237  7237 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-31 17:07:07.871  7237  7237 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-31 17:07:07.871  7237  7237 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-31 17:07:07.871  7237  7237 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-31 17:07:07.871  7237  7237 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:7:7
08-31 17:07:07.885  1042  1726 V SIM_STK : Menu title from STK is T-Mobile
08-31 17:07:07.885  1042  1726 V SIM_STK : Menu title from STK is T-Mobile
,08-31 17:07:07.891  6479  6479 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-31 17:07:07.893  6479  6511 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-31 17:07:07.903  2230  2230 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-31 17:07:07.911  7098  7098 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-31 17:07:07.911  7098  7098 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-31 17:07:07.912  7098  7098 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-31 17:07:07.912  7098  7098 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-31 17:07:07.913  7098  7098 I AppUp4:CustModeStarterReceiver: onReceive
,08-31 17:07:07.916  7098  7098 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2107a606
08-31 17:07:07.916  7098  7098 D AppUp4:CustFacade: isCustomizationCompleted : false
08-31 17:07:07.916  7098  7098 D AppUp4:CustFacade: isPhone : true
08-31 17:07:07.916  7098  7098 D AppUp4:CustModeStarterReceiver: begin check event
08-31 17:07:07.916  7098  7098 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-31 17:07:07.919  4304  4304 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-31 17:07:07.920  4304  4304 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-31 17:07:07.921  4304  4304 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-31 17:07:07.923  4304  4304 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-31 17:07:07.928  7132  7132 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-31 17:07:07.929  4304  7548 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-31 17:07:07.936  4304  7549 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-31 17:07:07.937  4304  7549 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-31 17:07:07.945  7132  7550 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-31 17:07:07.948  1042  2248 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-31 17:07:07.952  3366  3366 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-31 17:07:07.952  6986  7552 W FormManager: Network not available. Please check & try again.
08-31 17:07:07.952  3366  3366 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-31 17:07:07.953  6986  7553 V FormManager: Network unavailable.
08-31 17:07:07.953  3366  3366 I LgeMiscReceiver: networkInfo.isConnected() = false
08-31 17:07:07.954  7025  7025 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-31 17:07:07.956  7168  7168 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-31 17:07:07.956  7168  7168 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-31 17:07:07.958  7025  7025 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-31 17:07:07.958  7025  7025 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-31 17:07:07.958  7025  7025 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-31 17:07:07.958  7025  7025 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-31 17:07:07.959  7025  7025 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-31 17:07:07.959  7025  7025 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-31 17:07:07.959  7025  7025 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-31 17:07:07.959  7025  7025 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-31 17:07:07.959  7025  7025 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-31 17:07:07.959  7025  7025 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-31 17:07:07.959  7025  7025 I BluetoothA2dpServiceJni: classInitNative
08-31 17:07:07.959  7025  7025 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-31 17:07:07.960  7025  7025 D A2dpStateMachine: make
08-31 17:07:07.961  7025  7025 I bluedroid-qcom: get_profile_interface a2dp
08-31 17:07:07.961  7025  7556 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-31 17:07:07.963  6986  7553 V FormManager: Network unavailable.
08-31 17:07:07.964  7025  7025 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-31 17:07:07.964  7025  7025 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-31 17:07:07.964  7237  7237 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:7:7
08-31 17:07:07.965  7025  7025 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15aacaf4
08-31 17:07:07.966  7237  7237 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-31 17:07:07.966  7025  7025 I BluetoothHidServiceJni: classInitNative: succeeds
08-31 17:07:07.966  7237  7237 D Weather.Utils: 2 : All the weather widget is gone.
08-31 17:07:07.967  7237  7237 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-31 17:07:07.967  7237  7237 D WeatherAncestor: connectivity changed - connection : true
08-31 17:07:07.967  7237  7237 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@15aacaf4
08-31 17:07:07.967  7237  7237 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-31 17:07:07.967  7237  7237 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-31 17:07:07.967  7237  7237 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-31 17:07:07.967  7237  7237 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-31 17:07:07.968  7237  7237 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:7:7
08-31 17:07:07.968  7025  7025 D HidService: Received start request. Starting profile...
08-31 17:07:07.968  7025  7025 I bluedroid-qcom: get_profile_interface hidhost
08-31 17:07:07.968  7025  7025 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15aacaf4
08-31 17:07:07.969  7025  7025 I BluetoothHealthServiceJni: classInitNative: succeeds
08-31 17:07:07.970  7025  7555 D A2dpStateMachine: Enter Disconnected: -2
08-31 17:07:07.971  7025  7025 D HealthService: Received start request. Starting profile...
,08-31 17:07:07.972  7025  7025 I bluedroid-qcom: get_profile_interface health
08-31 17:07:07.972  7025  7025 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-31 17:07:07.972  7025  7025 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15aacaf4
08-31 17:07:07.972  7025  7025 D HeadsetStateMachine: Proxy object connected
08-31 17:07:07.973  7025  7025 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-31 17:07:07.973  7025  7025 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-31 17:07:07.974  7025  7025 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-31 17:07:07.975  7025  7025 D PanService: Received start request. Starting profile...
08-31 17:07:07.976  7025  7025 D BluetoothPanServiceJni: initializeNative(L110): pan
08-31 17:07:07.976  7025  7025 I bluedroid-qcom: get_profile_interface pan
08-31 17:07:07.980  7025  7025 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-31 17:07:07.980  7025  7025 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15aacaf4
08-31 17:07:07.981  7025  7025 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-31 17:07:07.987  7025  7025 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-31 17:07:07.987  7025  7025 D BtGatt.GattService: Received start request. Starting profile...
08-31 17:07:07.987  7025  7025 D BtGatt.GattService: start()
08-31 17:07:07.987  7025  7025 I bluedroid-qcom: get_profile_interface gatt
08-31 17:07:07.988  7025  7025 D BtGatt.AdvertiseManager: advertise manager created
08-31 17:07:07.993  7025  7025 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15aacaf4
08-31 17:07:07.996  7025  7025 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-31 17:07:07.998  7025  7025 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15aacaf4
08-31 17:07:07.998  7025  7527 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-31 17:07:07.998  7025  7025 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-31 17:07:07.999  7025  7025 V BluetoothMapService: BluetoothMapBinder()
08-31 17:07:08.000  7025  7025 D BluetoothMapService: Received start request. Starting profile...
08-31 17:07:08.000  7025  7025 D BluetoothMapService: start()
08-31 17:07:08.001  7025  7527 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-31 17:07:08.002  7025  7025 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-31 17:07:08.002  7025  7025 D BluetoothMapEmailAppObserver: createReceiver()
08-31 17:07:08.003  7025  7527 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-31 17:07:08.003  7025  7025 D BluetoothMapEmailAppObserver: initObservers()
08-31 17:07:08.003  7025  7025 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-31 17:07:08.011  7025  7025 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15aacaf4
,08-31 17:07:08.014  7025  7025 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-31 17:07:08.016  7025  7025 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-31 17:07:08.018  7025  7025 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-31 17:07:08.018  7025  7025 V PanService: [BTUI] SIM Extra State :ABSENT
08-31 17:07:08.022  7025  7025 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-31 17:07:08.024  7025  7025 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-31 17:07:08.024  7025  7025 V BluetoothMapService: Handler(): got msg=1
08-31 17:07:08.025  7025  7494 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-31 17:07:08.025  7025  7494 I bluedroid-qcom: enable
,08-31 17:07:08.026  7025  7494 I bt_hci_bdroid: init
,08-31 17:07:08.027  7025  7563 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-31 17:07:08.027  7025  7025 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-31 17:07:08.027  7025  7563 I bt-btu  : btu_task pending for preload complete event
08-31 17:07:08.029  7025  7494 I bt_vendor: bt-vendor : init
08-31 17:07:08.029  7025  7494 I bt_vendor: bt-vendor : get_bt_soc_type
08-31 17:07:08.029  7025  7494 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-31 17:07:08.029  7025  7494 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-31 17:07:08.029  7025  7494 D bt_userial_mct: userial_init
08-31 17:07:08.030  7025  7025 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-31 17:07:08.030  7025  7025 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-31 17:07:08.030  7025  7025 V BluetoothSapReceiver: SapReceiver onReceive 
08-31 17:07:08.030  7025  7025 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-31 17:07:08.030  7025  7025 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-31 17:07:08.030  7025  7494 D bt_hci_bdroid: set_power 1
08-31 17:07:08.030  7025  7494 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-31 17:07:08.031  7025  7494 I bt_vendor: Starting hciattach daemon
08-31 17:07:08.031  7025  7494 I bt_vendor: try to set true
08-31 17:07:08.024  7566  7566 W sh      : type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 17:07:08.024  7566  7566 W sh      : type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 17:07:08.062  7567  7567 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-31 17:07:08.204  7573  7573 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-31 17:07:08.219  7574  7574 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-31 17:07:08.270  7579  7579 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-31 17:07:08.282  7580  7580 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
08-31 17:07:08.296  7581  7581 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-31 17:07:08.308  7582  7582 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
08-31 17:07:08.332  7584  7584 I libmdmdetect: ESOC framework not supported
,08-31 17:07:08.335  7584  7584 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
08-31 17:07:08.343  7584  7584 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-31 17:07:08.343  7584  7584 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-31 17:07:08.343  7584  7584 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-31 17:07:08.343  7584  7584 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-31 17:07:08.343  7584  7584 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-31 17:07:08.343  7584  7584 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-31 17:07:08.344  7584  7584 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
,08-31 17:07:08.391  7584  7585 E QC-QMI  : qmi_client [7584] 14: failed to locate client data
,08-31 17:07:08.394   486   486 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
,08-31 17:07:08.395   486   486 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
08-31 17:07:08.440  7586  7586 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-31 17:07:08.462  7587  7587 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-31 17:07:08.482  7025  7494 I bt_vendor: bluetooth satus is on
08-31 17:07:08.482  7025  7494 D bt_hci_bdroid: preload
08-31 17:07:08.483  7025  7565 D bt_userial_mct: userial_open(port:0)
08-31 17:07:08.484  7025  7565 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-31 17:07:08.487  7025  7565 I bt_vendor: Done intiailizing UART
08-31 17:07:08.488  7025  7565 I bt_vendor: Done intiailizing UART
08-31 17:07:08.488  7025  7565 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-31 17:07:08.488  7025  7565 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-31 17:07:08.489  7025  7589 D bt_userial_mct: Entering userial_read_thread()
08-31 17:07:08.489  7025  7563 I bt-btu  : btu_task received preload complete event
08-31 17:07:08.489  7025  7563 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-31 17:07:08.489  7025  7563 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-31 17:07:08.492  7025  7563 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-31 17:07:08.495  7025  7563 I         : BTE_InitTraceLevels -- TRC_HCI
08-31 17:07:08.495  7025  7563 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-31 17:07:08.495  7025  7563 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-31 17:07:08.495  7025  7563 I         : BTE_InitTraceLevels -- TRC_AVDT
08-31 17:07:08.495  7025  7563 I         : BTE_InitTraceLevels -- TRC_AVRC
08-31 17:07:08.495  7025  7563 I         : BTE_InitTraceLevels -- TRC_A2D
08-31 17:07:08.495  7025  7563 I         : BTE_InitTraceLevels -- TRC_BNEP
08-31 17:07:08.495  7025  7563 I         : BTE_InitTraceLevels -- TRC_BTM
08-31 17:07:08.495  7025  7563 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-31 17:07:08.495  7025  7563 I         : BTE_InitTraceLevels -- TRC_GAP
08-31 17:07:08.495  7025  7563 I         : BTE_InitTraceLevels -- TRC_PAN
08-31 17:07:08.495  7025  7563 I         : BTE_InitTraceLevels -- TRC_SDP
08-31 17:07:08.495  7025  7563 I         : BTE_InitTraceLevels -- TRC_GATT
08-31 17:07:08.495  7025  7563 I         : BTE_InitTraceLevels -- TRC_SMP
08-31 17:07:08.495  7025  7563 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-31 17:07:08.495  7025  7563 I         : BTE_InitTraceLevels -- TRC_BTIF
08-31 17:07:08.559  7025  7563 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-31 17:07:08.559  7025  7563 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa0241061 
08-31 17:07:08.559  7025  7563 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0241061 
,08-31 17:07:08.600  7025  7498 E bt-btif : Calling BTA_HhEnable
08-31 17:07:08.601  7025  7498 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-31 17:07:08.601  7025  7563 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
,08-31 17:07:08.601  7025  7563 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-31 17:07:08.601  7025  7498 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-31 17:07:08.601  7025  7563 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-31 17:07:08.602  7025  7563 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-31 17:07:08.602  7025  7563 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-31 17:07:08.604  1042  1042 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-31 17:07:08.605  1042  1042 D BluetoothManagerService: Stored Bluetooth name: G3
08-31 17:07:08.605  7025  7498 D BluetoothAdapterProperties: Name is: G3
,08-31 17:07:08.611  7025  7498 D BluetoothAdapterProperties: Scan Mode:20
08-31 17:07:08.612  7025  7498 D BluetoothAdapterProperties: Discoverable Timeout:120
08-31 17:07:08.612  7025  7498 D bt_hci_bdroid: postload
08-31 17:07:08.612  7025  7565 D bt_hci_bdroid: Used up Tx Cmd credits
08-31 17:07:08.613  7025  7563 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-31 17:07:08.614  7025  7498 D bte_conf: Device ID record 1 : primary
08-31 17:07:08.614  7025  7498 D bte_conf:   vendorId            = 00c4
08-31 17:07:08.614  7025  7565 D bt_hci_bdroid: Used up Tx Cmd credits
08-31 17:07:08.614  7025  7498 D bte_conf:   vendorIdSource      = 0001
08-31 17:07:08.614  7025  7498 D bte_conf:   product             = 13a1
08-31 17:07:08.614  7025  7498 D bte_conf:   version             = 1000
08-31 17:07:08.614  7025  7498 D bte_conf:   clientExecutableURL = 
08-31 17:07:08.614  7025  7498 D bte_conf:   serviceDescription  = 
,08-31 17:07:08.614  7025  7498 D bte_conf:   documentationURL    = 
08-31 17:07:08.614  7025  7498 D bte_conf: bte_load_did_conf no section named DID2.
08-31 17:07:08.617  7025  7565 D bt_hci_bdroid: Used up Tx Cmd credits
08-31 17:07:08.620  7025  7498 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-31 17:07:08.614  7594  7594 W sh      : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 17:07:08.623  7025  7494 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-31 17:07:08.614  7594  7594 W sh      : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-31 17:07:08.624  7025  7494 D BluetoothAdapterProperties: State =  11
08-31 17:07:08.624  7025  7494 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-31 17:07:08.626  7025  7494 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-31 17:07:08.626  7025  7494 D BluetoothAdapterProperties: Setting state to 12
08-31 17:07:08.627  7025  7494 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-31 17:07:08.627  7025  7563 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-31 17:07:08.627  7025  7563 W bt-smp  : Plain text(LSB ~ MSB) = 8b e7 5b 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-31 17:07:08.627  7025  7563 W bt-smp  : Encrypted text(LSB ~ MSB) = 7b 9a 05 63 8e 17 85 6e af 8a a6 7b 14 c0 11 03 
08-31 17:07:08.627  7025  7563 W bt-btm  : Stopping oneshot timer
08-31 17:07:08.628  7025  7565 D bt_hci_bdroid: Used up Tx Cmd credits
08-31 17:07:08.631  7025  7589 E bt_mct  : hci lib postload completed
08-31 17:07:08.632  1042  1117 D BluetoothManagerService: Message: 60
08-31 17:07:08.632  1042  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-31 17:07:08.632  1042  1117 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
08-31 17:07:08.633  7025  7498 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-31 17:07:08.638  1866  2552 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-31 17:07:08.643  7025  7494 I BluetoothAdapterState: Entering On State
08-31 17:07:08.646  7025  7494 D LGBluetoothServiceAdapter: [BTUI] OnState
08-31 17:07:08.646  7025  7494 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-31 17:07:08.646  7025  7494 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-31 17:07:08.648  7025  7494 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-31 17:07:08.648  7025  7498 D BluetoothAdapterProperties: Discoverable Timeout:120
08-31 17:07:08.648  7025  7498 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-31 17:07:08.649  6694  6694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 17:07:08.649  6694  6694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 17:07:08.649  6694  6694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 17:07:08.649  6694  6694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 17:07:08.649  6694  6694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 17:07:08.649  6694  6694 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 17:07:08.649  6694  6694 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 17:07:08.649  6694  6694 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 17:07:08.651  6694  6694 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 17:07:08.662  6694  6694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 17:07:08.662  6694  6694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 17:07:08.662  6694  6694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 17:07:08.662  6694  6694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 17:07:08.662  6694  6694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 17:07:08.662  6694  6694 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 17:07:08.662  6694  6694 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 17:07:08.662  6694  6694 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 17:07:08.664  7025  7563 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-31 17:07:08.664  7025  7563 W bt-smp  : Plain text(LSB ~ MSB) = 78 fc 45 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-31 17:07:08.665  7025  7563 W bt-smp  : Encrypted text(LSB ~ MSB) = 44 17 3f cf dc fb 8c 7b 90 80 16 ab 34 80 3e 16 
08-31 17:07:08.665  7025  7563 W bt-btm  : Stopping oneshot timer
08-31 17:07:08.669  6694  6694 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 17:07:08.670  1866  1866 D BluetoothHeadset: Proxy object connected
08-31 17:07:08.671  1866  2524 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 17:07:08.673  1866  1866 D BluetoothHeadset: Proxy object connected
,08-31 17:07:08.675  6878  6897 D BluetoothPbap: onBluetoothStateChange: up=true
08-31 17:07:08.678  7025  7563 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-31 17:07:08.678  7025  7563 W bt-smp  : Plain text(LSB ~ MSB) = d9 e9 62 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-31 17:07:08.678  7025  7563 W bt-smp  : Encrypted text(LSB ~ MSB) = f7 c6 c8 a5 75 51 8a 40 be 0b 37 66 ba d6 39 9c 
08-31 17:07:08.678  7025  7563 W bt-btm  : Stopping oneshot timer
08-31 17:07:08.679  1042  1117 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 17:07:08.681  1042  1042 D BluetoothHeadset: Proxy object connected
08-31 17:07:08.682  1866  2552 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 17:07:08.685  1866  1866 D BluetoothHeadset: Proxy object connected
08-31 17:07:08.685  6878  7396 D BluetoothMap: onBluetoothStateChange: up=true
,08-31 17:07:08.691  6878  6878 D BluetoothMap: Proxy object connected
08-31 17:07:08.691  6878  6878 D MapProfile: Bluetooth service connected
,08-31 17:07:08.691  6878  6878 D BluetoothMap: getConnectedDevices()
08-31 17:07:08.692  1042  1117 D BluetoothA2dp: onBluetoothStateChange: up=true
08-31 17:07:08.696  6878  6896 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-31 17:07:08.697  7025  7494 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
,08-31 17:07:08.700  1042  1042 D BluetoothA2dp: Proxy object connected
08-31 17:07:08.701  7025  7563 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-31 17:07:08.701  7025  7563 W bt-smp  : Plain text(LSB ~ MSB) = a3 0a 62 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-31 17:07:08.701  7025  7563 W bt-smp  : Encrypted text(LSB ~ MSB) = f1 6f 88 16 22 b0 80 bc 2d 8e f2 04 61 27 65 82 
08-31 17:07:08.701  7025  7563 W bt-btm  : Stopping oneshot timer
08-31 17:07:08.702  6878  6897 D BluetoothPan: onBluetoothStateChange on: true
08-31 17:07:08.702  6878  6897 D BluetoothPan: onBluetoothStateChange call bindService
08-31 17:07:08.709  7025  7597 V BluetoothMapService: getConnectedDevices()
,08-31 17:07:08.713  7025  7563 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-31 17:07:08.713  7025  7563 W bt-smp  : Plain text(LSB ~ MSB) = e5 0e 52 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-31 17:07:08.713  7025  7563 W bt-smp  : Encrypted text(LSB ~ MSB) = c0 b3 ad 66 eb b9 83 68 74 6f 2e 95 7a 06 87 49 
08-31 17:07:08.713  7025  7563 W bt-btm  : Stopping oneshot timer
08-31 17:07:08.716  7608  7608 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-31 17:07:08.717  6878  6878 D BluetoothInputDevice: Proxy object connected
08-31 17:07:08.717  1042  1117 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-31 17:07:08.717  6878  6878 D HidProfile: Bluetooth service connected
08-31 17:07:08.717  1042  1117 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-31 17:07:08.721  1589  1589 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-31 17:07:08.722  1956  1956 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-31 17:07:08.723  1956  2166 D LGBluetoothAPIService: Message: 1
08-31 17:07:08.723  1956  2166 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
,08-31 17:07:08.729  1042  1042 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-31 17:07:08.729  1042  1117 D BluetoothManagerService: Message: 40
08-31 17:07:08.729  1042  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-31 17:07:08.730  1956  2166 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
08-31 17:07:08.731  7025  7025 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-31 17:07:08.731  6694  6694 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
08-31 17:07:08.731  7025  7025 D BluetoothMapService: STATE_ON
08-31 17:07:08.734  6694  6694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 17:07:08.735  7025  7025 D LGBluetoothAPIServer: [BTUI] onCreate()
08-31 17:07:08.736  7025  7025 D LGBluetoothAPIServer: [BTUI] onBind()
08-31 17:07:08.737  1956  1956 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-31 17:07:08.737  1956  2166 D LGBluetoothAPIService: Message: 100
08-31 17:07:08.737  6878  6878 D BluetoothPan: BluetoothPAN Proxy object connected
08-31 17:07:08.737  1956  2166 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-31 17:07:08.737  6878  6878 D PanProfile: Bluetooth service connected
08-31 17:07:08.738  6694  6694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 17:07:08.742  6878  6878 D LocalBluetoothProfileManager: Adding local A2DP profile
08-31 17:07:08.745  1042  1117 D BluetoothManagerService: Message: 30
,08-31 17:07:08.748  6878  6878 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-31 17:07:08.752  1042  1117 D BluetoothManagerService: Message: 30
08-31 17:07:08.755  7025  7025 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15aacaf4
08-31 17:07:08.755  7025  7025 V BluetoothPbapService: Pbap Service onCreate
08-31 17:07:08.755  7025  7025 V BluetoothPbapService: Starting PBAP service
08-31 17:07:08.756  7025  7025 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-31 17:07:08.756  7025  7025 V BluetoothMapService: Handler(): got msg=1
08-31 17:07:08.757  7025  7025 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-31 17:07:08.757  6878  6878 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-31 17:07:08.758  7025  7025 V BluetoothPbapService: Pbap Service onBind
08-31 17:07:08.759  7025  7612 D BluetoothMapMasInstance: MAS initSocket()
08-31 17:07:08.759  7025  7025 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
,08-31 17:07:08.759  7025  7025 V BluetoothPbapService: state: 12
08-31 17:07:08.759  7025  7025 V BluetoothPbapService: Handler(): got msg=1
08-31 17:07:08.760  7025  7612 D BluetoothMapMasInstance:   masId = 00
08-31 17:07:08.760  7025  7612 D BluetoothMapMasInstance:   msgTypes = 0e
08-31 17:07:08.760  7025  7612 D BluetoothMapMasInstance:   masName = SMS/MMS
08-31 17:07:08.760  7025  7612 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-31 17:07:08.761  7025  7025 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-31 17:07:08.762  6878  6878 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-31 17:07:08.765  1042  2027 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 17:07:08.765  6878  6878 D BluetoothA2dp: Proxy object connected
08-31 17:07:08.765  7025  7613 V BluetoothPbapService: Pbap Service initSocket
08-31 17:07:08.766  6878  6878 D A2dpProfile: Bluetooth service connected
08-31 17:07:08.767  7025  7025 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-31 17:07:08.767  7025  7025 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-31 17:07:08.767  7025  7025 V BluetoothPbapReceiver: ***********state = 12
08-31 17:07:08.768  1042  2248 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 17:07:08.769  7025  7612 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 17:07:08.770  7025  7613 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-31 17:07:08.773  2230  2230 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-31 17:07:08.774  7025  7612 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-31 17:07:08.774  2230  2230 D c       : Getting all permits...
08-31 17:07:08.774  2230  2230 D a       : Opening database...
08-31 17:07:08.774  7025  7612 V BluetoothMapMasInstance: Succeed to create listening socket 
08-31 17:07:08.774  7025  7612 D BluetoothMapMasInstance: Accepting socket connection...
08-31 17:07:08.774  7025  7613 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-31 17:07:08.774  7025  7613 V BluetoothPbapService: Succeed to create listening socket 
08-31 17:07:08.774  7025  7613 V BluetoothPbapService: Accepting socket connection...
08-31 17:07:08.775  6878  6878 D BluetoothHeadset: Proxy object connected
08-31 17:07:08.775  7025  7498 D BluetoothAdapterProperties: Scan Mode:21
08-31 17:07:08.775  7025  7498 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-31 17:07:08.776  6878  6878 D HeadsetProfile: Bluetooth service connected
08-31 17:07:08.777  2230  2230 D a       : Opening database auth.proximity.permit_store...
08-31 17:07:08.778  2230  2230 D a       : Closing database...
08-31 17:07:08.779  6694  6694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 17:07:08.781  6694  6694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 17:07:08.786  6878  6878 D BluetoothPbap: Proxy object connected
08-31 17:07:08.787  6878  6878 D PbapServerProfile: Bluetooth service connected
,08-31 17:07:08.790  6878  6878 D DockEventReceiver: finishStartingService: stopping service
08-31 17:07:08.795  6878  6878 D BluetoothPermissionRequest: onReceive
08-31 17:07:08.797  6878  6878 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-31 17:07:08.799  6878  6878 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-31 17:07:08.802  7025  7025 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
,08-31 17:07:08.804  7025  7025 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-31 17:07:08.809  7025  7025 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
08-31 17:07:08.827  7025  7025 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-31 17:07:08.827  7025  7025 V BtOppService: onCreate
,08-31 17:07:08.832  7025  7025 V BluetoothOppNotification: send message
,08-31 17:07:08.834  7025  7025 V BtOppService: Starting RfcommListener
08-31 17:07:08.838  7025  7025 D BluetoothOppPreference: Dumping Names:  
08-31 17:07:08.838  7025  7025 D BluetoothOppPreference: {}
08-31 17:07:08.838  7025  7025 D BluetoothOppPreference: Dumping Channels:  
08-31 17:07:08.838  7025  7025 D BluetoothOppPreference: {}
08-31 17:07:08.839  7025  7025 V BtOppService: onStartCommand
08-31 17:07:08.841  7025  7623 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
,08-31 17:07:08.845  7025  7619 V BtOppService: Deleted complete outbound shares, number =  0
08-31 17:07:08.847  7025  7025 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-31 17:07:08.847  7025  7619 V BtOppService: Deleted complete inbound failed shares, number = 0
08-31 17:07:08.848  7025  7025 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-31 17:07:08.849  7025  7619 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-31 17:07:08.849  7025  7623 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-31 17:07:08.850  7025  7619 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@482eb69 on behalf of 
08-31 17:07:08.850  7025  7025 V BluetoothOppNotification: new notify threadi!
08-31 17:07:08.851  7025  7025 V BluetoothOppNotification: send delay message
08-31 17:07:08.852  7025  7025 V BtOppService: start RfcommListener
08-31 17:07:08.853  7025  7623 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@bae69ee on behalf of 
08-31 17:07:08.853  7025  7624 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,08-31 17:07:08.855  7025  7025 V BtOppService: RfcommListener started
08-31 17:07:08.855  7025  7025 V BtOppService: ContentObserver received notification
08-31 17:07:08.855  7025  7025 V BtOppService: ContentObserver received notification
08-31 17:07:08.856  7025  7625 V BtOppRfcommListener: Starting RFCOMM listener....
08-31 17:07:08.856  1042  1762 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 17:07:08.856  7025  7623 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-31 17:07:08.857  7025  7623 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-31 17:07:08.857  7025  7625 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 17:07:08.857  7025  7624 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@399dce8f on behalf of 
08-31 17:07:08.857  7025  7624 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-31 17:07:08.858  7025  7623 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2ebab51c on behalf of 
08-31 17:07:08.859  7025  7623 V BluetoothOppNotification: update too frequent, put in queue
08-31 17:07:08.859  7025  7625 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=79 mFd=75
08-31 17:07:08.859  7025  7625 V BtOppRfcommListener: Started RFCOMM listener....
08-31 17:07:08.860  7025  7625 I BtOppRfcommListener: Accept thread started.
08-31 17:07:08.860  7025  7625 V BtOppRfcommListener: Accepting connection...
,08-31 17:07:08.860  7025  7623 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-31 17:07:08.860  7025  7624 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-31 17:07:08.861  7025  7624 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3855d525 on behalf of 
08-31 17:07:08.862  7025  7624 V BluetoothOppNotification: outbound: succ-0  fail-0
08-31 17:07:08.863  7025  7624 V BluetoothOppNotification: outbound notification was removed.
08-31 17:07:08.863  7025  7624 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-31 17:07:08.865  7025  7624 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@231b36fa on behalf of 
,08-31 17:07:08.869  7025  7624 V BluetoothOppNotification: inbound: succ-0  fail-0
08-31 17:07:08.870  7025  7025 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15aacaf4
08-31 17:07:08.870  7025  7025 V BluetoothFtpService: Ftp Service onCreate
08-31 17:07:08.870  7025  7025 I BluetoothFtpService: Ftp Service onCreate
08-31 17:07:08.870  7025  7624 V BluetoothOppNotification: inbound notification was removed.
08-31 17:07:08.870  7025  7025 V BluetoothFtpService: Ftp Service onStartCommand
08-31 17:07:08.871  7025  7025 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-31 17:07:08.871  7025  7624 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-31 17:07:08.871  7025  7025 V BluetoothFtpService: Starting Listening on sockets
08-31 17:07:08.871  7025  7025 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-31 17:07:08.871  7025  7025 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-31 17:07:08.871  7025  7025 V BluetoothSapReceiver: SapReceiver onReceive 
08-31 17:07:08.871  7025  7025 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-31 17:07:08.871  7025  7025 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-31 17:07:08.871  7025  7025 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-31 17:07:08.872  7025  7624 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@174c0708 on behalf of 
08-31 17:07:08.873  7025  7025 V BluetoothFtpService: Handler(): got msg=1
08-31 17:07:08.874  7025  7025 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-31 17:07:08.874  7025  7025 V BluetoothFtpService: Ftp Service initSocket
08-31 17:07:08.879  1042  1728 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 17:07:08.880  7025  7025 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-31 17:07:08.884  7025  7025 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=79
08-31 17:07:08.884  7025  7025 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-31 17:07:08.885  7025  7626 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-31 17:07:08.896  7298  7328 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,08-31 17:07:08.898  7025  7025 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15aacaf4
,08-31 17:07:08.898  7025  7025 V BluetoothSapService: Sap Service onCreate
08-31 17:07:08.900  7025  7025 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-31 17:07:08.900  7025  7025 V BluetoothSapService: state: 12
08-31 17:07:08.900  7025  7025 V BluetoothSapService: Starting SAP server process
08-31 17:07:08.901  7025  7025 V BluetoothSapService: SAP Service startRfcommListenerThread
08-31 17:07:08.902  7025  7630 V BluetoothSapService: Sap Service initRfcommSocket
08-31 17:07:08.894  7629  7629 W sapd    : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 17:07:08.903  1042  1918 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 17:07:08.894  7629  7629 W sapd    : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 17:07:08.903  7025  7630 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 17:07:08.904  7025  7630 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-31 17:07:08.904  7025  7630 V BluetoothSapService: Succeed to create listening socket 
08-31 17:07:08.904  7025  7630 V BluetoothSapService: Accepting socket connection...
08-31 17:07:08.912  7629  7629 V BT_SAP  : Event pipe created
08-31 17:07:08.912  7629  7629 V BT_SAP  : create_server_socket qcom.sap.server
08-31 17:07:08.912  7629  7629 V BT_SAP  : created socket fd 6
,08-31 17:07:09.470  1042  1522 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-31 17:07:09.470  1042  1522 D LGWifiP2pService: DefaultState{ when=-1ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-31 17:07:09.541  1042  1523 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-31 17:07:09.547  1042  1523 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-31 17:07:09.836  1042  2341 I ActivityManager: Killing 7421:com.lge.bnr/1000 (adj 15): empty #17
,08-31 17:07:09.853  7025  7025 V BluetoothOppNotification: new notify threadi!
08-31 17:07:09.854  7025  7025 V BluetoothOppNotification: send delay message
,08-31 17:07:09.863  7025  7640 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-31 17:07:09.866  7025  7640 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@341e8bb4 on behalf of 
08-31 17:07:09.867  7025  7640 V BluetoothOppNotification: mUpdateCompleteNotification = true
,08-31 17:07:09.871  7025  7640 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-31 17:07:09.872  7025  7640 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@ca83dd on behalf of 
08-31 17:07:09.873  7025  7640 V BluetoothOppNotification: outbound: succ-0  fail-0
08-31 17:07:09.874  7025  7640 V BluetoothOppNotification: outbound notification was removed.
08-31 17:07:09.874  7025  7640 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-31 17:07:09.875  7025  7640 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2455ab52 on behalf of 
08-31 17:07:09.876  7025  7640 V BluetoothOppNotification: inbound: succ-0  fail-0
08-31 17:07:09.877  7025  7640 V BluetoothOppNotification: inbound notification was removed.
08-31 17:07:09.877  7025  7640 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-31 17:07:09.880  7025  7640 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@26191e23 on behalf of 
,08-31 17:07:09.886  1042  1726 W libprocessgroup: failed to open /acct/uid_1000/pid_7421/cgroup.procs: No such file or directory
,08-31 17:07:10.175  1042  1762 I ActivityManager: Killing 6814:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,08-31 17:07:10.200  6945  6945 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
08-31 17:07:10.201  6945  6945 W System.err: android.os.DeadObjectException
08-31 17:07:10.201  6945  6945 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-31 17:07:10.201  6945  6945 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-31 17:07:10.201  6945  6945 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-31 17:07:10.201  6945  6945 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-31 17:07:10.201  6945  6945 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-31 17:07:10.201  6945  6945 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-31 17:07:10.201  6945  6945 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-31 17:07:10.201  6945  6945 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-31 17:07:10.201  6945  6945 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-31 17:07:10.202  6945  6945 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-31 17:07:10.202  6945  6945 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 17:07:10.202  6945  6945 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 17:07:10.202  6945  6945 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-31 17:07:10.202  6945  6945 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,08-31 17:07:10.206  6945  6945 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-31 17:07:10.207  6945  6945 W System.err: android.os.DeadObjectException
08-31 17:07:10.207  6945  6945 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-31 17:07:10.207  6945  6945 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-31 17:07:10.207  6945  6945 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-31 17:07:10.207  6945  6945 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-31 17:07:10.207  6945  6945 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-31 17:07:10.207  6945  6945 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-31 17:07:10.207  6945  6945 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-31 17:07:10.207  6945  6945 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-31 17:07:10.207  6945  6945 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-31 17:07:10.207  6945  6945 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-31 17:07:10.207  6945  6945 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 17:07:10.207  6945  6945 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 17:07:10.207  6945  6945 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-31 17:07:10.208  6945  6945 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-31 17:07:10.208  6945  6945 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-31 17:07:10.209  6945  6945 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
08-31 17:07:10.212  1042  2027 W libprocessgroup: failed to open /acct/uid_1000/pid_6814/cgroup.procs: No such file or directory
08-31 17:07:10.212  1042  2027 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
08-31 17:07:10.216  6945  6945 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-31 17:07:10.217  6945  6945 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
,08-31 17:07:10.268  1042  2046 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7641 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-31 17:07:10.299  6945  6945 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-31 17:07:10.363  7641  7641 D UEI.SmartControl: Quickset Services start...
08-31 17:07:10.365  7641  7641 I UEI.SmartControl: Manufacture = LGE
08-31 17:07:10.366  7641  7641 D UEI.SmartControl: Id = LGNevo
,08-31 17:07:10.369  7641  7641 D UEI.SmartControl: File observer start...
,08-31 17:07:10.372  7641  7641 E UEI.SmartControl: IR Port is disabled: false
08-31 17:07:10.373  7641  7641 D UEI.SmartControl: Starting file observer...
08-31 17:07:10.373  7641  7641 D UEI.SmartControl: Extracting JNI libs...
08-31 17:07:10.374  7641  7641 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
08-31 17:07:10.472  1042  2342 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 17:07:10.472  1042  2342 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@1596dcc9 mBinding = false
,08-31 17:07:10.490  7641  7641 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
08-31 17:07:10.491  7641  7641 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
,08-31 17:07:10.491  7641  7641 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
08-31 17:07:10.496  1042  1042 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-31 17:07:10.497  1042  1042 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-31 17:07:10.497  1042  1042 D Ulp_jni : JNI:system_update. Event-4
08-31 17:07:10.499  1042  1117 D BluetoothManagerService: Message: 2
08-31 17:07:10.500  1042  1117 D BluetoothManagerService: Sending off request.
08-31 17:07:10.501  7025  7040 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-31 17:07:10.502  7025  7494 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-31 17:07:10.503  7025  7494 D BluetoothAdapterProperties: Setting state to 13
,08-31 17:07:10.503  7025  7494 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-31 17:07:10.507  7025  7494 D BluetoothAdapterProperties: onBluetoothDisable()
08-31 17:07:10.507  7025  7494 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-31 17:07:10.509  7025  7498 D BluetoothAdapterProperties: Scan Mode:20
08-31 17:07:10.509  7025  7494 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-31 17:07:10.510  7025  7563 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-31 17:07:10.510  7025  7494 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-31 17:07:10.510  7025  7563 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-31 17:07:10.512  7025  7613 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-31 17:07:10.513  7025  7625 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-31 17:07:10.514  7025  7626 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-31 17:07:10.514  7025  7630 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-31 17:07:10.515  7025  7612 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-31 17:07:10.515  7025  7612 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-31 17:07:10.515  7025  7612 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-31 17:07:10.515  7025  7612 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-31 17:07:10.515  7025  7612 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-31 17:07:10.515  7025  7612 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-31 17:07:10.515  7025  7612 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-31 17:07:10.515  7025  7612 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
,08-31 17:07:10.518  7025  7563 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-31 17:07:10.518  7025  7563 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-31 17:07:10.518  7025  7563 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-31 17:07:10.518  7025  7563 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-31 17:07:10.518  7025  7563 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-31 17:07:10.518  7025  7563 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-31 17:07:10.518  7025  7563 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-31 17:07:10.518  7025  7563 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-31 17:07:10.518  7025  7563 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-31 17:07:10.518  7025  7563 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-31 17:07:10.518  7025  7563 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-31 17:07:10.519  7025  7563 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-31 17:07:10.521  6694  6694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 17:07:10.521  6694  6694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 17:07:10.521  6694  6694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 17:07:10.521  6694  6694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 17:07:10.521  6694  6694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 17:07:10.521  6694  6694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 17:07:10.521  6694  6694 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 17:07:10.521  6694  6694 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 17:07:10.521  6694  6694 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 17:07:10.523  1042  1117 D BluetoothManagerService: Message: 60
08-31 17:07:10.523  1042  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-31 17:07:10.524  1042  1117 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-31 17:07:10.525  6694  6694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 17:07:10.525  6694  6694 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 17:07:10.529  1956  1956 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-31 17:07:10.530  6694  6694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 17:07:10.530  6694  6694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 17:07:10.530  6694  6694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 17:07:10.530  6694  6694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 17:07:10.530  6694  6694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 17:07:10.530  6694  6694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 17:07:10.530  6694  6694 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 17:07:10.530  6694  6694 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 17:07:10.530  6694  6694 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 17:07:10.532  6694  6694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 17:07:10.532  6694  6694 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 17:07:10.533  1589  1589 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-31 17:07:10.533  6878  6878 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
08-31 17:07:10.534  7025  7025 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-31 17:07:10.534  7025  7025 D BluetoothMapService: STATE_TURNING_OFF
08-31 17:07:10.534  7025  7025 V BluetoothMapService: Handler(): got msg=4
08-31 17:07:10.535  7025  7025 D BluetoothMapService: MAP Service closeService in
08-31 17:07:10.535  7025  7025 D BluetoothMapMasInstance: MAP Service shutdown
08-31 17:07:10.535  6878  6878 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-31 17:07:10.535  7025  7025 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-31 17:07:10.535  7025  7025 V BluetoothMapService: MAP Service closeService out
08-31 17:07:10.536  6694  6694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 17:07:10.537  7025  7025 V BtOppService: Receiver DISABLED_ACTION 
08-31 17:07:10.537  7025  7025 I BtOppRfcommListener: stopping Accept Thread
08-31 17:07:10.537  7025  7025 V BtOppRfcommListener: close mBtServerSocket
08-31 17:07:10.537  7025  7025 V BtOppRfcommListener: waiting for thread to terminate
08-31 17:07:10.537  7025  7625 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-31 17:07:10.537  7025  7025 V BtOppRfcommListener: done waiting for thread to terminate
08-31 17:07:10.539  7025  7025 V BtOppService: onDestroy
08-31 17:07:10.541  7025  7025 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-31 17:07:10.541  6694  6694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 17:07:10.541  7025  7025 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-31 17:07:10.541  7025  7025 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-31 17:07:10.541  7025  7025 V BluetoothPbapReceiver: ***********state = 13
,08-31 17:07:10.545  7025  7025 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-31 17:07:10.546  6878  6878 D DockEventReceiver: finishStartingService: stopping service
08-31 17:07:10.547  7025  7025 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-31 17:07:10.547  7025  7025 V BluetoothPbapService: state: 13
08-31 17:07:10.547  7025  7025 V BluetoothPbapService: Pbap Service closeService in
08-31 17:07:10.550  6878  6878 D BluetoothPbap: Proxy object disconnected
08-31 17:07:10.550  6878  6878 D PbapServerProfile: Bluetooth service disconnected
08-31 17:07:10.550  2230  2230 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-31 17:07:10.550  7025  7025 V BluetoothPbapService: successfully stopped pbap service
08-31 17:07:10.550  7025  7025 V BluetoothPbapService: Pbap Service closeService out
08-31 17:07:10.551  7025  7025 V BluetoothPbapService: Pbap Service onDestroy
08-31 17:07:10.551  7025  7025 V BluetoothPbapService: Pbap Service closeService in
08-31 17:07:10.551  7025  7025 V BluetoothPbapService: Pbap Service closeService out
08-31 17:07:10.551  7025  7025 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-31 17:07:10.565  6878  6878 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-31 17:07:10.570  6878  6878 D BluetoothPermissionRequest: onReceive
08-31 17:07:10.572  6878  6878 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-31 17:07:10.582  6878  6878 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-31 17:07:10.586  7641  7641 I UEI.SmartControl: --- Selecting new region: 6
08-31 17:07:10.589  7641  7641 I UEI.SmartControl: Model = LG-D855
08-31 17:07:10.589  7025  7025 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-31 17:07:10.589  7025  7025 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-31 17:07:10.590  7025  7025 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-31 17:07:10.592  7641  7641 D UEI.SmartControl: QS Service created
08-31 17:07:10.594  7025  7025 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-31 17:07:10.594  7025  7025 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
,08-31 17:07:10.597  7025  7025 V BluetoothFtpService: Ftp Service onStartCommand
08-31 17:07:10.597  7025  7025 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-31 17:07:10.598  7025  7025 V BluetoothFtpService: Ftp Service closeService
08-31 17:07:10.598  7025  7025 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-31 17:07:10.600  7025  7025 V BluetoothFtpService: successfully stopped ftp service
08-31 17:07:10.600  7025  7025 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-31 17:07:10.600  7025  7025 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-31 17:07:10.600  7025  7025 V BluetoothSapReceiver: SapReceiver onReceive 
08-31 17:07:10.600  7025  7025 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-31 17:07:10.600  7025  7025 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-31 17:07:10.600  7025  7025 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-31 17:07:10.602  7025  7025 V BluetoothFtpService: Ftp Service onDestroy
08-31 17:07:10.602  7025  7025 V BluetoothFtpService: Ftp Service closeService
08-31 17:07:10.606  7025  7025 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-31 17:07:10.606  7025  7025 V BluetoothSapService: state: 13
,08-31 17:07:10.606  7025  7025 V BluetoothSapService: Stopping SAP server process
08-31 17:07:10.607  7025  7025 V BluetoothSapService: Sap Service closeSapService in
08-31 17:07:10.608  7025  7025 V BluetoothSapService: Close listen Socket : 
08-31 17:07:10.608  7025  7025 V BluetoothSapService: Close rfcomm Socket : 
08-31 17:07:10.608  7025  7025 V BluetoothSapService: Close sapd  Socket : 
08-31 17:07:10.610  7025  7025 V BluetoothSapService: Sap Service closeSapService out
08-31 17:07:10.610  7025  7025 V BluetoothSapService: Sap Service onDestroy
08-31 17:07:10.610  7025  7025 V BluetoothSapService: Sap Service closeSapService in
08-31 17:07:10.610  7025  7025 V BluetoothSapService: Close listen Socket : 
08-31 17:07:10.610  7025  7025 V BluetoothSapService: Close rfcomm Socket : 
08-31 17:07:10.610  7025  7025 V BluetoothSapService: Close sapd  Socket : 
08-31 17:07:10.615  7025  7025 V BluetoothSapService: Sap Service closeSapService out
08-31 17:07:10.617  7641  7641 I UEI.SmartControl: Service initServices...
08-31 17:07:10.623  7641  7641 D UEI.SmartControl: QS start get config
,08-31 17:07:10.697  7641  7641 D UEI.SmartControl: Loading JNI Libs...
,08-31 17:07:11.151  7641  7641 I UEI.SmartControl: Supports setup maps: true
,08-31 17:07:11.159  7641  7641 D UEI.SmartControl: QS start statue = true Error code = 0
08-31 17:07:11.159  7641  7641 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-31 17:07:11.159  7641  7641 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-31 17:07:11.159  7641  7641 I UEI.SmartControl: ### init IR Blaster...
08-31 17:07:11.166  7641  7641 D serial_port: Configuring serial port
,08-31 17:07:11.173  7641  7641 E UEI.SmartControl: UEIBLaster setting for 616
,08-31 17:07:11.173  7641  7641 I UEI.SmartControl: Setting serial record hearder size = 2
08-31 17:07:11.174  7641  7641 I UEI.SmartControl: configuring settings for MAXQ616
08-31 17:07:11.174  7641  7641 I UEI.SmartControl: Get version...
08-31 17:07:11.191  7641  7685 D UEI.SmartControl: serial port data available: 21
,08-31 17:07:11.221  7641  7641 D UEI.SmartControl: MAXQ616 A2-X4 software.
,08-31 17:07:11.221  7641  7641 I UEI.SmartControl: IR Blaster version: 256702256704300002
,08-31 17:07:11.222  7641  7641 I UEI.SmartControl: QS saving settings...
08-31 17:07:11.224  7641  7641 D UEI.SmartControl: IR Blaster version: 25672567
,08-31 17:07:11.244  7641  7685 D UEI.SmartControl: serial port data available: 4
,08-31 17:07:11.287  7641  7641 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-31 17:07:11.290  7641  7688 I UEI.SmartControl: Device manager: loading config....
08-31 17:07:11.291  7641  7688 D UEI.SmartControl: ----------- loading internal config...
08-31 17:07:11.298  7641  7641 E UEI.SmartControl: Services init done
08-31 17:07:11.299  7641  7641 D UEI.SmartControl: QS Service init finished
08-31 17:07:11.301  7641  7641 D UEI.SmartControl: QS Service version name: 2.1.91
08-31 17:07:11.301  7641  7641 D UEI.SmartControl: QS Service version code: 201091
08-31 17:07:11.304  7641  7641 D UEI.SmartControl: Service requested: Control
,08-31 17:07:11.310  7641  7688 E UEI.SmartControl: Loading SETTINGS...
08-31 17:07:11.314  7641  7641 D UEI.SmartControl: Request IControl service: devices are loaded...
08-31 17:07:11.317  6945  6945 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
,08-31 17:07:11.318  1042  1954 I ActivityManager: Killing 6945:com.lge.qremote/u0a112 (adj 15): empty #17
08-31 17:07:11.318  7641  7657 I UEI.SmartControl: ------ IControl API: 11
08-31 17:07:11.320  7641  7657 I UEI.SmartControl: Registering callback...
08-31 17:07:11.321  7641  7688 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-31 17:07:11.328  7641  7687 I UEI.SmartControl: Notify AllClients services are ready: 0
08-31 17:07:11.328  7641  7687 D UEI.SmartControl: -----service ready thread exits
,08-31 17:07:11.371  1042  2342 W libprocessgroup: failed to open /acct/uid_10112/pid_6945/cgroup.procs: No such file or directory
,08-31 17:07:11.375  7641  7641 D UEI.SmartControl: Internal service binding...
,08-31 17:07:11.500  7025  7563 W bt-btif : ag scb idx 1 not allocated
08-31 17:07:11.500  7025  7498 D bt_hci_bdroid: cleanup
08-31 17:07:11.500  7025  7563 E bt-btif : BTA AG is already disabled, ignoring ...
,08-31 17:07:11.500  7025  7563 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
,08-31 17:07:11.500  7025  7563 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-31 17:07:11.500  7025  7563 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-31 17:07:11.501  7025  7563 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-31 17:07:11.501  7025  7563 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-31 17:07:11.501  7025  7563 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-31 17:07:11.501  7025  7563 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-31 17:07:11.501  7025  7563 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-31 17:07:11.501  7025  7563 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-31 17:07:11.501  7025  7563 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-31 17:07:11.501  7025  7563 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
,08-31 17:07:11.501  7025  7563 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-31 17:07:11.501  7025  7563 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-31 17:07:11.501  7025  7563 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-31 17:07:11.501  7025  7563 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-31 17:07:11.501  7025  7563 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-31 17:07:11.502  7025  7565 I bt_lpm  : LPM is already off!!!
08-31 17:07:11.502  7025  7589 I bt_userial_mct: exiting userial_read_thread
08-31 17:07:11.502  7025  7589 D bt_userial_mct: Leaving userial_evt_read_thread()
08-31 17:07:11.503  7025  7498 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-31 17:07:11.503  7025  7565 I bt_vendor: hw_epilog_process
08-31 17:07:11.504  7025  7498 D bt_hci_bdroid: cleanup Finalizing cleanup
08-31 17:07:11.504  7025  7498 D bt_userial_mct: userial_close
08-31 17:07:11.504  7025  7498 E bt_userial_mct: pthread_join() FAILED result:3
08-31 17:07:11.504  7025  7498 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,08-31 17:07:11.501  7025  7563 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
,08-31 17:07:11.505  7025  7563 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-31 17:07:11.505  7025  7563 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
,08-31 17:07:11.529  7025  7498 D bt_hci_bdroid: set_power 0
08-31 17:07:11.529  7025  7498 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
,08-31 17:07:11.538  7025  7498 I bt_vendor: bluetooth satus is on
08-31 17:07:11.538  7025  7498 I bt_vendor: bt-vendor : resetting BT status
08-31 17:07:11.538  7025  7498 I bt_vendor: Starting hciattach daemon
08-31 17:07:11.538  7025  7498 I bt_vendor: try to set false
08-31 17:07:11.540  7025  7498 I bt_vendor: Starting hciattach daemon
08-31 17:07:11.540  7025  7498 I bt_vendor: try to set false
08-31 17:07:11.541  7025  7498 I bt_vendor: cleanup
08-31 17:07:11.541  7025  7563 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-31 17:07:11.542  7025  7498 I GKI_LINUX: GKI_exit_task 0 done
08-31 17:07:11.542  7025  7498 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-31 17:07:11.543  7025  7494 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-31 17:07:11.550  7025  7025 D HeadsetService: Received stop request...Stopping profile...
,08-31 17:07:11.554  7025  7025 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-31 17:07:11.554  7025  7025 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-31 17:07:11.554  7025  7025 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15aacaf4
08-31 17:07:11.555  7025  7527 D HeadsetStateMachine: Exit Disconnected: -1
08-31 17:07:11.558  1042  1042 D BluetoothHeadset: Proxy object disconnected
08-31 17:07:11.558  1042  1042 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-31 17:07:11.560  1866  1866 D BluetoothHeadset: Proxy object disconnected
08-31 17:07:11.560  1866  1866 D BluetoothHeadset: Proxy object disconnected
08-31 17:07:11.560  1866  1866 D BluetoothHeadset: Proxy object disconnected
08-31 17:07:11.563  7025  7025 D A2dpService: Received stop request...Stopping profile...
,08-31 17:07:11.565  7025  7555 D A2dpStateMachine: Exit Disconnected: -1
08-31 17:07:11.567  7025  7025 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-31 17:07:11.568  7025  7494 D BluetoothAdapterState: Stopping profile services that were post enabled
08-31 17:07:11.569  7025  7025 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-31 17:07:11.569  7025  7025 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-31 17:07:11.569  7025  7025 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15aacaf4
08-31 17:07:11.573  7025  7025 D HidService: Received stop request...Stopping profile...
08-31 17:07:11.573  7025  7025 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15aacaf4
08-31 17:07:11.574  1042  1042 D BluetoothA2dp: Proxy object disconnected
08-31 17:07:11.574  1042  1042 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-31 17:07:11.578  7025  7025 D HealthService: Received stop request...Stopping profile...
08-31 17:07:11.580  7025  7025 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15aacaf4
08-31 17:07:11.582  7025  7025 D HeadsetStateMachine: Unbinding service...
08-31 17:07:11.584  7025  7025 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-31 17:07:11.584  7025  7025 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-31 17:07:11.584  7025  7025 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-31 17:07:11.584  7025  7025 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-31 17:07:11.584  7025  7025 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-31 17:07:11.584  7025  7025 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-31 17:07:11.584  7025  7025 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-31 17:07:11.585  7025  7025 D PanService: Received stop request...Stopping profile...
08-31 17:07:11.586  7025  7025 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15aacaf4
,08-31 17:07:11.589  7025  7025 D BtGatt.DebugUtils: handleDebugAction() action=null
08-31 17:07:11.590  7025  7025 D BtGatt.GattService: Received stop request...Stopping profile...
08-31 17:07:11.590  7025  7025 D BtGatt.GattService: stop()
08-31 17:07:11.590  7025  7025 D BtGatt.AdvertiseManager: advertise clients cleared
08-31 17:07:11.591  7025  7025 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15aacaf4
08-31 17:07:11.592  7025  7025 D BluetoothMapService: Received stop request...Stopping profile...
08-31 17:07:11.592  7025  7025 D BluetoothMapService: stop()
08-31 17:07:11.593  7025  7025 D BluetoothMapEmailAppObserver: deinitObservers()
08-31 17:07:11.593  7025  7025 D BluetoothMapEmailAppObserver: removeReceiver()
08-31 17:07:11.595  7025  7025 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15aacaf4
08-31 17:07:11.599  7025  7025 I BluetoothA2dpServiceJni: cleanupNative
08-31 17:07:11.601  7025  7556 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-31 17:07:11.602  7025  7025 I GKI_LINUX: GKI_exit_task 2 done
08-31 17:07:11.602  7025  7025 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-31 17:07:11.602  7025  7025 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-31 17:07:11.602  7025  7025 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-31 17:07:11.602  7025  7025 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-31 17:07:11.603  7025  7025 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-31 17:07:11.603  7025  7025 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-31 17:07:11.603  7025  7025 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-31 17:07:11.603  7025  7025 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-31 17:07:11.606  7025  7025 V BluetoothMapService: Handler(): got msg=4
08-31 17:07:11.606  7025  7025 D BluetoothMapService: MAP Service closeService in
08-31 17:07:11.606  7025  7025 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-31 17:07:11.606  7025  7025 V BluetoothMapService: MAP Service closeService out
08-31 17:07:11.608  7025  7494 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-31 17:07:11.608  7025  7494 D BluetoothAdapterProperties: Setting state to 10
08-31 17:07:11.608  7025  7494 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-31 17:07:11.608  7025  7025 D BluetoothMapService: cleanup()
08-31 17:07:11.608  7025  7025 D BluetoothMapService: MAP Service closeService in
08-31 17:07:11.608  7025  7025 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-31 17:07:11.608  7025  7025 V BluetoothMapService: MAP Service closeService out
08-31 17:07:11.609  1042  1117 D BluetoothManagerService: Message: 60
08-31 17:07:11.610  1042  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-31 17:07:11.610  1042  1117 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
08-31 17:07:11.610  7025  7494 I BluetoothAdapterState: Entering OffState
08-31 17:07:11.610  1866  2524 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 17:07:11.614  1866  2552 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 17:07:11.615  6878  6897 D BluetoothPbap: onBluetoothStateChange: up=false
08-31 17:07:11.615  1042  1117 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 17:07:11.616  1866  1881 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 17:07:11.616  6878  6897 D BluetoothA2dp: onBluetoothStateChange: up=false
08-31 17:07:11.617  6878  6897 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 17:07:11.617  6878  6897 D BluetoothMap: onBluetoothStateChange: up=false
08-31 17:07:11.619  1042  1117 D BluetoothA2dp: onBluetoothStateChange: up=false
08-31 17:07:11.619  6878  6897 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-31 17:07:11.620  6878  6897 D BluetoothPan: onBluetoothStateChange on: false
08-31 17:07:11.621  1042  1117 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-31 17:07:11.621  1042  1117 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-31 17:07:11.623  1042  1117 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-31 17:07:11.623  1042  1117 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-31 17:07:11.623  1042  1117 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@1596dcc9 mBinding = false
08-31 17:07:11.625  1042  1117 D BluetoothManagerService: Sending unbind request.
08-31 17:07:11.630  7025  7498 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-31 17:07:11.632  7025  7025 I GKI_LINUX: GKI_exit_task 1 done
08-31 17:07:11.632  7025  7025 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-31 17:07:11.632  7025  7025 I BluetoothServiceJni: cleanupNative: return from cleanup
08-31 17:07:11.632  7025  7025 I art     : --- WEIRD: removing null entry 248
08-31 17:07:11.632  7025  7025 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
08-31 17:07:11.632  7025  7025 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-31 17:07:11.633  7025  7025 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-31 17:07:11.635  1042  1117 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
,08-31 17:07:11.639  7025  7025 I art     : System.exit called, status: 0
08-31 17:07:11.639  7025  7025 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-31 17:07:11.659   317  1370 V AudioFlinger: 7025 died, releasing its sessions
08-31 17:07:11.659   317  1370 V AudioFlinger:  pid 1866 @ 0
08-31 17:07:11.659   317  1370 V AudioFlinger:  pid 3366 @ 1
08-31 17:07:11.659   317  1370 V AudioFlinger:  pid 3366 @ 2
08-31 17:07:11.663  1956  1956 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: disconnected from LGBluetoothAPIAdapter
08-31 17:07:11.663  1956  2166 D LGBluetoothAPIService: Message: 101
08-31 17:07:11.663  1956  2166 E LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED
08-31 17:07:11.664  1956  2166 D LGBluetoothAPIService: Calling onBluetoothServiceDown callbacks
08-31 17:07:11.664  1956  2166 D LGBluetoothAPIService: Broadcasting onBluetoothServiceDown() to 0 receivers.
08-31 17:07:11.665  6878  6878 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-31 17:07:11.668  1042  1057 I ActivityManager: Process com.android.bluetooth (pid 7025) has died
08-31 17:07:11.668  1042  1057 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 4000ms
08-31 17:07:11.668  1042  1057 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer in 14000ms
08-31 17:07:11.674  1956  1956 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-31 17:07:11.677  1589  1589 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-31 17:07:11.678  1956  2166 D LGBluetoothAPIService: Message: 2
08-31 17:07:11.678  1956  2166 D LGBluetoothAPIService: unbindAndFinish(): null mBinding = false
08-31 17:07:11.679  6694  6694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 17:07:11.679  6694  6694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 17:07:11.687  6878  6878 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-31 17:07:11.687  6878  6878 D LGBluetoothEventManager: [BTUI] clear device connection state
,08-31 17:07:11.709  1589  1589 D BluetoothAdapter: 316630425: getState() :  mService = null. Returning STATE_OFF
08-31 17:07:11.709  1589  1589 D BluetoothAdapter: 316630425: getState() :  mService = null. Returning STATE_OFF
,08-31 17:07:11.854  1042  2046 I art     : Explicit concurrent mark sweep GC freed 73070(3MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/64MB, paused 1.988ms total 160.545ms
,08-31 17:07:11.859  6878  6878 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-31 17:07:11.950  1042  1058 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=7719 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-31 17:07:11.955  6878  6878 D DockEventReceiver: finishStartingService: stopping service
,08-31 17:07:12.043  7719  7719 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-31 17:07:12.044  7719  7719 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-31 17:07:12.044  7719  7719 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-31 17:07:12.045  7719  7719 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-31 17:07:12.065  7719  7719 D BluetoothAdapterApp: Loading JNI Library
,08-31 17:07:12.102  7719  7719 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@23334c5c Instance Count = 1
,08-31 17:07:12.109  7719  7719 D BluetoothAdapterApp: onCreate
,08-31 17:07:12.135  7719  7719 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-31 17:07:12.136  7719  7719 D ProfileConfigQcom: Adding HeadsetService
08-31 17:07:12.136  7719  7719 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-31 17:07:12.136  7719  7719 D ProfileConfigQcom: Adding A2dpService
08-31 17:07:12.136  7719  7719 D ProfileConfigQcom: [BTUI] HidService is supported
08-31 17:07:12.136  7719  7719 D ProfileConfigQcom: Adding HidService
08-31 17:07:12.137  7719  7719 D ProfileConfigQcom: [BTUI] HealthService is supported
08-31 17:07:12.137  7719  7719 D ProfileConfigQcom: Adding HealthService
08-31 17:07:12.137  7719  7719 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-31 17:07:12.138  7719  7719 D ProfileConfigQcom: [BTUI] PanService is supported
08-31 17:07:12.139  7719  7719 D ProfileConfigQcom: Adding PanService
08-31 17:07:12.139  7719  7719 D ProfileConfigQcom: [BTUI] GattService is supported
08-31 17:07:12.139  7719  7719 D ProfileConfigQcom: Adding GattService
08-31 17:07:12.139  7719  7719 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-31 17:07:12.140  7719  7719 D ProfileConfigQcom: Adding BluetoothMapService
08-31 17:07:12.140  7719  7719 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
,08-31 17:07:12.141  7719  7719 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-31 17:07:12.142  7719  7719 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-31 17:07:12.143  7719  7719 V BluetoothPbapReceiver: ***********state = 10
08-31 17:07:12.145  7719  7719 V LGMDMManagerInternal: Create singleton instance
08-31 17:07:12.240  2230  2230 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-31 17:07:12.244  7719  7719 D LGBluetoothAPIServer: [BTUI] onCreate()
08-31 17:07:12.245  7719  7719 D LGBluetoothAPIServer: [BTUI] onBind()
08-31 17:07:12.246  6878  6878 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-31 17:07:12.252  1956  1956 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-31 17:07:12.252  1956  2166 D LGBluetoothAPIService: Message: 100
08-31 17:07:12.252  1956  2166 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-31 17:07:12.261  6878  6878 D BluetoothPermissionRequest: onReceive
,08-31 17:07:12.264  6878  6878 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-31 17:07:12.264  6878  6878 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-31 17:07:12.268  6878  6878 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-31 17:07:12.275  7719  7719 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
,08-31 17:07:12.281  7719  7719 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-31 17:07:12.285  7719  7719 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-31 17:07:12.285  7719  7719 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-31 17:07:12.285  7719  7719 V BluetoothSapReceiver: SapReceiver onReceive 
08-31 17:07:12.287  7719  7719 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-31 17:07:12.287  7719  7719 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-31 17:07:12.290  6962  6962 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,08-31 17:07:13.500  6694  6804 D io.jxcore.node.ConnectivityMonitor: stop
,08-31 17:07:13.500  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 17:07:13.593  1589  1589 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,08-31 17:07:13.684  1042  1110 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7749 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-31 17:07:13.699  1589  1589 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
,08-31 17:07:13.702  1589  1589 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
08-31 17:07:13.711  2081  2081 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-31 17:07:13.735  1042  1419 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-31 17:07:13.742  1042  1042 D administrator: Handling package changes for user 0
,08-31 17:07:13.777  2081  2081 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-31 17:07:13.793  7749  7749 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-31 17:07:13.862  1042  1042 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
08-31 17:07:13.862  1042  1042 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-31 17:07:13.892  7749  7749 D LgDataFeature: LgDataFeature() Constructor: none
08-31 17:07:13.892  7749  7749 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-31 17:07:13.899  1042  1108 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-31 17:07:13.904  1042  1108 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-31 17:07:13.912  2479  2479 V GmsNetworkLocationProvi: DISABLE
,08-31 17:07:13.916  2081  2081 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-31 17:07:13.942  1042  1108 D LocationProviderProxy: applying state to connected service
08-31 17:07:13.943  2479  2479 E GCoreFlp: Bound FusedProviderService with LocationManager
,08-31 17:07:14.021  7749  7793 I Babel   : MmsConfig: mnc/mcc: 0/0
08-31 17:07:14.023  7749  7793 I Babel   : MmsConfig.loadMmsSettings
08-31 17:07:14.037  7749  7793 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-31 17:07:14.037  7749  7793 I Babel   : MmsConfig.loadFromDatabase
,08-31 17:07:14.053  7749  7793 E Babel   : canonicalizeMccMnc: invalid mccmnc 
08-31 17:07:14.053  7749  7793 I Babel   : MmsConfig.loadFromResources
08-31 17:07:14.057  7749  7749 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 17:07:14.057  7749  7793 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
08-31 17:07:14.059  7749  7793 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
,08-31 17:07:14.082  7749  7792 W AudioCapabilities: Unsupported mime audio/evrc
,08-31 17:07:14.084  7749  7792 W AudioCapabilities: Unsupported mime audio/qcelp
08-31 17:07:14.088  1827  7797 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
08-31 17:07:14.088  1827  7797 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
08-31 17:07:14.103  7098  7098 I AppUp4:CustModeStarterReceiver: onReceive
,08-31 17:07:14.105  7749  7792 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
08-31 17:07:14.113  1827  4758 I Icing   : updateResources: need to parse e{com.google.android.gms}
,08-31 17:07:14.116  7098  7098 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2107a606
08-31 17:07:14.116  7098  7098 D AppUp4:CustFacade: isCustomizationCompleted : false
08-31 17:07:14.116  7098  7098 D AppUp4:CustFacade: isPhone : true
08-31 17:07:14.116  7098  7098 D AppUp4:CustModeStarterReceiver: begin check event
08-31 17:07:14.117  7098  7098 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
08-31 17:07:14.127  7749  7792 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
08-31 17:07:14.128  7749  7792 W AudioCapabilities: Unsupported mime audio/qcelp
,08-31 17:07:14.134  7749  7792 W AudioCapabilities: Unsupported mime audio/evrc
08-31 17:07:14.146  7749  7792 W VideoCapabilities: Unsupported mime video/x-ms-wmv
08-31 17:07:14.149  7749  7792 W VideoCapabilities: Unsupported mime video/divx
,08-31 17:07:14.152  7749  7792 W VideoCapabilities: Unsupported mime video/divx311
08-31 17:07:14.154  7749  7792 W VideoCapabilities: Unsupported mime video/divx4
08-31 17:07:14.160  7749  7792 W VideoCapabilities: Unsupported mime video/mp4v-esdp
08-31 17:07:14.163  1042  2027 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7800 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,08-31 17:07:14.168  1042  2342 I ActivityManager: Killing 6917:com.lge.sync/1000 (adj 15): empty #17
08-31 17:07:14.180  1042  1529 D WifiService: Client connection lost with reason: 4
,08-31 17:07:14.193  7749  7792 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-31 17:07:14.197  7749  7792 W AudioCapabilities: Unsupported mime audio/eac3
08-31 17:07:14.198  7749  7792 W AudioCapabilities: Unsupported mime audio/ac3
08-31 17:07:14.199  7749  7792 W AudioCapabilities: Unsupported mime audio/g726
08-31 17:07:14.200  7749  7792 W AudioCapabilities: Unsupported mime audio/wma-voice
08-31 17:07:14.201  7749  7792 W AudioCapabilities: Unsupported mime audio/x-ms-wma
08-31 17:07:14.201  7749  7792 W AudioCapabilities: Unsupported mime audio/adpcm
08-31 17:07:14.203  7749  7792 W VideoCapabilities: Unsupported mime video/theora
08-31 17:07:14.205  7749  7792 W VideoCapabilities: Unsupported mime video/mjpg
,08-31 17:07:14.219  1042  2341 W libprocessgroup: failed to open /acct/uid_1000/pid_6917/cgroup.procs: No such file or directory
,08-31 17:07:14.247  7800  7800 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-31 17:07:14.248  7800  7800 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-31 17:07:14.248  7800  7800 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,08-31 17:07:14.250  7800  7800 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
08-31 17:07:14.250  7800  7800 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-31 17:07:14.326  7800  7800 I SystemConfig: BUILD Country: EU
,08-31 17:07:14.327  7800  7800 I SystemConfig: BUILD Operator: OPEN
,08-31 17:07:14.377  1042  1955 I ActivityManager: Killing 7132:com.lge.email/u0a23 (adj 15): empty #17
,08-31 17:07:14.491  1042  1561 W libprocessgroup: failed to open /acct/uid_10023/pid_7132/cgroup.procs: No such file or directory
,08-31 17:07:14.505  7800  7818 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
08-31 17:07:14.506  7800  7818 I SystemConfig: existFile = false
08-31 17:07:14.506  7800  7818 I SystemConfig: canReadFile = false
08-31 17:07:14.506  7800  7818 I SystemConfig: systemFeature RCS result false
08-31 17:07:14.506  7800  7818 D SystemConfig: refreshRcsSupport() :false
,08-31 17:07:14.557  1042  2027 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7820 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,08-31 17:07:14.618  7820  7820 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-31 17:07:14.618  7820  7820 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-31 17:07:14.618  7820  7820 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,08-31 17:07:14.619  7820  7820 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-31 17:07:14.727  7820  7820 I AppConfig: Total System Memory = 2995761152
,08-31 17:07:14.739  7820  7820 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
08-31 17:07:14.831  1042  2011 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7842 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-31 17:07:14.841  1042  2011 I ActivityManager: Killing 6986:com.lge.formmanager/u0a26 (adj 15): empty #17
08-31 17:07:14.899  1042  1728 W libprocessgroup: failed to open /acct/uid_10026/pid_6986/cgroup.procs: No such file or directory
,08-31 17:07:15.097  7842  7842 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,08-31 17:07:15.225  7842  7842 D LgDataFeature: LgDataFeature() Constructor: none
08-31 17:07:15.226  7842  7842 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-31 17:07:15.278  7842  7842 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
08-31 17:07:15.297  7842  7842 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
08-31 17:07:15.297  7842  7842 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-31 17:07:15.313  7842  7842 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-31 17:07:15.313  7842  7842 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
08-31 17:07:15.330  1042  1057 I ActivityManager: Killing 6479:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,08-31 17:07:15.434  1042  1918 W libprocessgroup: failed to open /acct/uid_1000/pid_6479/cgroup.procs: No such file or directory
,08-31 17:07:15.445  4594  7881 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,08-31 17:07:15.501  1042  1762 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7883 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,08-31 17:07:15.517  2845  4460 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
,08-31 17:07:15.524  2845  4460 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@17e554b5 on behalf of 7842
,08-31 17:07:15.600  7842  7842 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,08-31 17:07:15.616  7842  7842 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,08-31 17:07:15.632  7883  7883 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,08-31 17:07:15.656  7883  7883 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
08-31 17:07:15.656  7883  7883 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
08-31 17:07:15.656  7883  7883 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
08-31 17:07:15.656  7883  7883 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
08-31 17:07:15.656  7883  7883 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
08-31 17:07:15.656  7883  7883 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
,08-31 17:07:15.676  1042  2248 I ActivityManager: Killing 7168:com.google.android.setupwizard/u0a46 (adj 15): empty #17
,08-31 17:07:15.709  1042  1728 W libprocessgroup: failed to open /acct/uid_10046/pid_7168/cgroup.procs: No such file or directory
,08-31 17:07:15.805  1589  1589 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-31 17:07:15.805  1589  1589 I [SystemUI]LGPowerUI: On Skip Timer : true
,08-31 17:07:15.815  1956  2134 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-31 17:07:15.815  1956  2134 D LEDHandler: Battery Level Remaining: 100%
08-31 17:07:15.815  1956  2134 D LEDHandler: Battery Temp: 306, mChargingStatus=5, mChargingStop=false
08-31 17:07:15.815  1042  1529 D WifiController: battery changed pluggedType: 2
08-31 17:07:15.815  1589  1589 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 306
08-31 17:07:15.815  1589  1589 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-31 17:07:15.817  1589  1589 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
,08-31 17:07:15.829  1042  1762 V SIM_STK : Menu title from STK is T-Mobile
,08-31 17:07:15.848  4594  7881 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 401 ms] updated apps [took 401 ms] 
,08-31 17:07:16.285  7641  7689 D UEI.SmartControl: Internal timer expired: 1
,08-31 17:07:16.286  7641  7689 D UEI.SmartControl: unbind internal service
,08-31 17:07:16.303  7641  7641 D UEI.SmartControl: Service.onUnbind: IControl
08-31 17:07:16.310  7641  7641 D UEI.SmartControl: Service.onDestroy
08-31 17:07:16.310  7641  7641 D UEI.SmartControl: Lock is in USE false
08-31 17:07:16.310  7641  7641 D UEI.SmartControl: unbind internal service
08-31 17:07:16.311  7641  7641 W System.err: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@b681c92
08-31 17:07:16.311  7641  7641 W System.err: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
08-31 17:07:16.311  7641  7641 W System.err: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
08-31 17:07:16.311  7641  7641 W System.err: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
08-31 17:07:16.311  7641  7641 W System.err: 	at com.uei.control.Service.c(Unknown Source)
08-31 17:07:16.311  7641  7641 W System.err: 	at com.uei.control.Service.onDestroy(Unknown Source)
08-31 17:07:16.311  7641  7641 W System.err: 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
08-31 17:07:16.311  7641  7641 W System.err: 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
08-31 17:07:16.311  7641  7641 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
08-31 17:07:16.311  7641  7641 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 17:07:16.312  7641  7641 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-31 17:07:16.312  7641  7641 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-31 17:07:16.312  7641  7641 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 17:07:16.312  7641  7641 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 17:07:16.312  7641  7641 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-31 17:07:16.312  7641  7641 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-31 17:07:16.312  7641  7641 E UEI.SmartControl: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@b681c92
,08-31 17:07:16.318  7641  7641 D serial_port: close(fd = 25)
08-31 17:07:16.323  7641  7641 I UEI.SmartControl: Serial port is closed.
08-31 17:07:16.324  7641  7641 I UEI.SmartControl: Serial port is closed.
08-31 17:07:16.324  7641  7641 D UEI.SmartControl: Blaster closed
08-31 17:07:16.324  7641  7641 D UEI.SmartControl: Shut down QS...
08-31 17:07:16.324  7641  7641 D UEI.SmartControl: Stopping QS lib
08-31 17:07:16.324  7641  7641 D UEI.SmartControl: QS lib stop result = true
08-31 17:07:16.324  7641  7641 D UEI.SmartControl: Stopped QS lib
08-31 17:07:16.325  7641  7641 D UEI.SmartControl: Stopped file observer...
08-31 17:07:16.325  7641  7641 D UEI.SmartControl: QS shutdown complete
,08-31 17:07:16.515  6694  6804 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-31 17:07:16.515  6694  6804 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2df028a8 added. We now have 6 listener(s)
,08-31 17:07:16.516  6694  6804 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 17:07:16.530  6694  6804 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 17:07:16.530  6694  6804 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1594afc1 added. We now have 7 listener(s)
08-31 17:07:16.530  6694  6804 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 17:07:16.531  6694  6804 I System.out: IsBluetoothEnabled
08-31 17:07:16.532  1042  1561 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 17:07:16.532  1042  1561 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
08-31 17:07:16.533  1042  1117 D BluetoothManagerService: Message: 2
08-31 17:07:16.537  6694  6804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 17:07:16.540  1042  1057 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 17:07:16.540  1042  1057 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
08-31 17:07:16.556  1042  1042 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-31 17:07:16.556  1042  1042 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-31 17:07:16.556  1042  1042 D Ulp_jni : JNI:system_update. Event-4
,08-31 17:07:16.560  1042  1117 D BluetoothManagerService: Message: 1
08-31 17:07:16.560  1042  1117 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
,08-31 17:07:16.588  1042  1117 D BluetoothManagerService: Message: 20
08-31 17:07:16.588  1042  1117 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@13a2854e:true
,08-31 17:07:16.592  7719  7719 D BluetoothAdapterState: make
08-31 17:07:16.596  7719  7719 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-31 17:07:16.597  7719  7719 I bluedroid-qcom: init
08-31 17:07:16.598  7719  7928 I BluetoothAdapterState: Entering OffState
08-31 17:07:16.598  7719  7719 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-31 17:07:16.599  7719  7719 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-31 17:07:16.599  7719  7719 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-31 17:07:16.599  7719  7719 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-31 17:07:16.599  7719  7719 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-31 17:07:16.600  7719  7719 I bluedroid-qcom: get_profile_interface socket
08-31 17:07:16.601  7719  7719 I bluedroid-qcom: get_profile_interface map_client
,08-31 17:07:16.594  7931  7931 W bdaddr_loader: type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 17:07:16.607  7719  7932 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-31 17:07:16.604  7931  7931 W bdaddr_loader: type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 17:07:16.614  7719  7932 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-31 17:07:16.622  7931  7931 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-31 17:07:16.622  7931  7931 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-31 17:07:16.622  7931  7931 I LGFTMITEM: [GET_FTM][id=8], offset=16384
08-31 17:07:16.624  1042  1042 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-31 17:07:16.624  1042  1042 D BluetoothManagerService: Stored Bluetooth name: G3
08-31 17:07:16.626  1042  1042 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
,08-31 17:07:16.628  1042  1117 D BluetoothManagerService: Message: 40
08-31 17:07:16.629  1042  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-31 17:07:16.630  7719  7736 I bluedroid-qcom: config_hci_snoop_log
08-31 17:07:16.631  1042  1117 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-31 17:07:16.631  1042  1117 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-31 17:07:16.632  7931  7931 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-31 17:07:16.634  7719  7932 D BluetoothAdapterProperties: Name is: G3
08-31 17:07:16.638  7931  7931 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-31 17:07:16.638  7931  7931 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
,08-31 17:07:16.644  7719  7928 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-31 17:07:16.644  7719  7928 D BluetoothAdapterProperties: Setting state to 11
08-31 17:07:16.644  7719  7928 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-31 17:07:16.646  1042  1117 D BluetoothManagerService: Message: 60
08-31 17:07:16.646  1042  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-31 17:07:16.646  1042  1117 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-31 17:07:16.652  1956  1956 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-31 17:07:16.653  1589  1589 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-31 17:07:16.655  6694  6694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 17:07:16.659  6878  6878 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-31 17:07:16.666  7719  7719 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-31 17:07:16.666  7719  7719 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-31 17:07:16.666  7719  7719 V BluetoothPbapReceiver: ***********state = 11
,08-31 17:07:16.682  7719  7928 I LGBluetoothServiceJni: classInitNative: succeeds
,08-31 17:07:16.685  2230  2230 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-31 17:07:16.698  7719  7928 D BluetoothBondStateMachine: make
,08-31 17:07:16.702  7719  7928 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3046f21d
08-31 17:07:16.702  7719  7928 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-31 17:07:16.702  7719  7928 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3046f21d
08-31 17:07:16.702  7719  7928 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-31 17:07:16.703  7719  7928 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-31 17:07:16.704  6878  6878 D BluetoothPermissionRequest: onReceive
08-31 17:07:16.704  7719  7948 I BluetoothBondStateMachine: StableState(): Entering Off State
08-31 17:07:16.706  7719  7928 E BluetoothAdapterService: File transfer profiles supported!!
08-31 17:07:16.717  7719  7719 D HeadsetService: Received start request. Starting profile...
08-31 17:07:16.718  7719  7719 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-31 17:07:16.718  7719  7719 D LGBluetoothHfpAdapter: Version 1.6
08-31 17:07:16.718  6878  6878 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-31 17:07:16.720  7719  7928 E BluetoothAdapterService: File transfer profiles supported!!
,08-31 17:07:16.721  7719  7719 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,08-31 17:07:16.723  7719  7719 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-31 17:07:16.723  7719  7719 D HeadsetStateMachine: make
08-31 17:07:16.733  7719  7928 E BluetoothAdapterService: File transfer profiles supported!!
,08-31 17:07:16.742  7719  7928 E BluetoothAdapterService: File transfer profiles supported!!
08-31 17:07:16.749  7719  7928 E BluetoothAdapterService: File transfer profiles supported!!
,08-31 17:07:16.758  7719  7928 E BluetoothAdapterService: File transfer profiles supported!!
08-31 17:07:16.764  7719  7928 E BluetoothAdapterService: File transfer profiles supported!!
,08-31 17:07:16.764  7719  7719 D LgDataFeature: LgDataFeature() Constructor: none
08-31 17:07:16.765  7719  7719 D LgDataFeature: LgDataFeature() Constructor Done, null
08-31 17:07:16.771  7719  7719 D HeadsetStateMachine: max_hf_connections = 1
08-31 17:07:16.771  7719  7719 I bluedroid-qcom: get_profile_interface handsfree
08-31 17:07:16.773  7719  7719 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-31 17:07:16.774   317  1369 V AudioPolicyService: registerClient() client 0xb558a560, uid 1002
08-31 17:07:16.774   317  3990 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-31 17:07:16.774   317  3990 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-31 17:07:16.774   317  3990 V AudioPolicyManagerEx: getOutput() returns output 2
08-31 17:07:16.775  7719  7719 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
,08-31 17:07:16.775   317   317 V AudioFlinger: registerClient() client 0xb55814f0, pid 7719
08-31 17:07:16.775   317  1364 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-31 17:07:16.775   317  1364 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-31 17:07:16.776  1042  1561 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-31 17:07:16.776  1042  1561 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-31 17:07:16.776  3366  3382 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-31 17:07:16.776  3366  3382 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-31 17:07:16.776  1866  2524 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-31 17:07:16.776  1866  2524 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-31 17:07:16.776   317  1365 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-31 17:07:16.776   317  1365 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-31 17:07:16.776  7719  7736 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-31 17:07:16.776  7719  7736 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-31 17:07:16.776  1042  1057 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-31 17:07:16.776  1042  1057 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-31 17:07:16.776  7719  7736 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-31 17:07:16.776  7719  7736 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-31 17:07:16.776  3366  3383 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-31 17:07:16.776  3366  3383 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-31 17:07:16.777  1589  1608 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-31 17:07:16.777  1866  1881 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-31 17:07:16.777  1866  1881 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-31 17:07:16.777  1589  1608 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-31 17:07:16.777  1589  1608 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-31 17:07:16.777  7719  7719 V ToneGenerator: Create Track: 0xb4928080
08-31 17:07:16.777  1589  1608 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-31 17:07:16.777  7719  7719 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-31 17:07:16.777  7719  7719 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-31 17:07:16.777   317  1370 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
,08-31 17:07:16.777   317  1370 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
,08-31 17:07:16.777   317  1370 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-31 17:07:16.777   317  1370 V AudioPolicyManagerEx: getOutput() returns output 2
08-31 17:07:16.777   317  1369 I AudioFlinger: isAudioPlaybackHookOn() false
08-31 17:07:16.777   317  3990 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
,08-31 17:07:16.777   317  3990 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-31 17:07:16.777   317  3990 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-31 17:07:16.777   317  3990 V AudioPolicyManagerEx: getOutput() returns output 2
08-31 17:07:16.778  7719  7719 V AudioSystem: getLatency() output 2, latency 50
08-31 17:07:16.778  7719  7719 V AudioSystem: getFrameCount() output 2, frameCount 960
,08-31 17:07:16.778  7719  7719 V AudioTrack: createTrack_l() output 2 afLatency 50
08-31 17:07:16.778   317   317 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-31 17:07:16.778   317   317 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-31 17:07:16.778   317   317 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-31 17:07:16.778   317   317 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
,08-31 17:07:16.778   317   317 V AudioFlinger: createTrack() lSessionId: 23
08-31 17:07:16.779  7719  7719 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-31 17:07:16.779   317  1370 V AudioFlinger: acquiring 23 from 7719, for 7719
08-31 17:07:16.779   317  1370 V AudioFlinger:  added new entry for 23
08-31 17:07:16.779  7719  7719 V ToneGenerator: ToneGenerator INIT OK, time: 134871
08-31 17:07:16.780  7719  7719 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3046f21d
08-31 17:07:16.781  7719  7949 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-31 17:07:16.782  7719  7949 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-31 17:07:16.782  7719  7949 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-31 17:07:16.782  7719  7949 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-31 17:07:16.782   317  1369 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7719
08-31 17:07:16.783   317  1369 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-31 17:07:16.783  7719  7719 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3046f21d
08-31 17:07:16.783   317  1369 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-31 17:07:16.783   317  1369 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-31 17:07:16.783   317  1369 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-31 17:07:16.783   317  1369 V voice   : voice_set_parameters: exit with code(0)
08-31 17:07:16.783   317  1369 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-31 17:07:16.783   317  1369 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-31 17:07:16.783   317  1369 V msm8974_platform: platform_set_parameters: exit with code(0)
08-31 17:07:16.783   317  1369 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-31 17:07:16.783   317  1369 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-31 17:07:16.783   317  1369 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-31 17:07:16.784  7719  7949 V ToneGenerator: ToneGenerator destructor
08-31 17:07:16.784  7719  7949 V ToneGenerator: stopTone
08-31 17:07:16.784  7719  7949 V ToneGenerator: Delete Track: 0xb4928080
08-31 17:07:16.786  7719  7949 V AudioTrack: ~AudioTrack, releasing session id from 7719 on behalf of 7719
08-31 17:07:16.786  7719  7719 D A2dpService: Received start request. Starting profile...
08-31 17:07:16.786   317  1369 V AudioFlinger: releasing 23 from 7719 for 7719
08-31 17:07:16.787   317  1369 V AudioFlinger:  decremented refcount to 0
08-31 17:07:16.787   317  1369 V AudioFlinger: purging stale effects
08-31 17:07:16.787   317  1369 V AudioPolicyService: AudioCommandThread() adding release output 2
08-31 17:07:16.787   317  1369 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-31 17:07:16.787   317  1270 V AudioPolicyService: AudioCommandThread() waking up
08-31 17:07:16.787   317  1369 V AudioFlinger: PlaybackThread::Track destructor
08-31 17:07:16.787   317  1270 V AudioPolicyService: AudioCommandThread() processing release output 2
08-31 17:07:16.787   317  1270 V AudioPolicyManager: releaseOutput() 2
08-31 17:07:16.787   317  1369 V AudioFlinger: removeClient_l() pid 7719, calling pid 317
08-31 17:07:16.787   317  1270 V AudioPolicyService: AudioCommandThread() going to sleep
08-31 17:07:16.787  7719  7719 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-31 17:07:16.788  1042  1955 W Process : Unable to open /proc/7952/status
08-31 17:07:16.788  7719  7719 V Avrcp   : make
08-31 17:07:16.789  7719  7719 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-31 17:07:16.789  7719  7719 I bluedroid-qcom: get_profile_interface avrcp
08-31 17:07:16.794  7719  7928 V ,LGMDMManager: Create singleton instance
08-31 17:07:16.795  7719  7928 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,08-31 17:07:16.799  7719  7719 V AudioManager: registerRemoteController: size of Media player list: 0
08-31 17:07:16.801  7719  7719 E AudioManager: No RCC entry present to update
08-31 17:07:16.801  7719  7719 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-31 17:07:16.804  7719  7719 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-31 17:07:16.806  7719  7719 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-31 17:07:16.806  7719  7719 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-31 17:07:16.810  7719  7719 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,08-31 17:07:16.914  1042  1728 V SIM_STK : Menu title from STK is T-Mobile
08-31 17:07:16.914  1042  1728 V SIM_STK : Menu title from STK is T-Mobile
,08-31 17:07:16.986  1042  1726 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-31 17:07:16.992  7719  7719 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-31 17:07:16.996  7719  7719 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-31 17:07:16.997  7719  7719 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-31 17:07:16.997  7719  7719 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-31 17:07:16.997  7719  7719 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-31 17:07:16.997  7719  7719 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-31 17:07:16.997  7719  7719 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-31 17:07:16.997  7719  7719 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-31 17:07:16.997  7719  7719 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
,08-31 17:07:16.997  7719  7719 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-31 17:07:16.997  7719  7719 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-31 17:07:16.998  7719  7719 I BluetoothA2dpServiceJni: classInitNative
08-31 17:07:16.998  7719  7719 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-31 17:07:16.998  7719  7719 D A2dpStateMachine: make
08-31 17:07:17.001  7719  7719 I bluedroid-qcom: get_profile_interface a2dp
08-31 17:07:17.001  7719  7957 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-31 17:07:17.003  7719  7719 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-31 17:07:17.004  7719  7719 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-31 17:07:17.004  7719  7719 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3046f21d
08-31 17:07:17.005  7719  7719 I BluetoothHidServiceJni: classInitNative: succeeds
08-31 17:07:17.005  7719  7956 D A2dpStateMachine: Enter Disconnected: -2
08-31 17:07:17.006  7719  7719 D HidService: Received start request. Starting profile...
08-31 17:07:17.006  7719  7719 I bluedroid-qcom: get_profile_interface hidhost
08-31 17:07:17.006  7719  7719 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3046f21d
08-31 17:07:17.007  7719  7719 I BluetoothHealthServiceJni: classInitNative: succeeds
08-31 17:07:17.008  7719  7719 D HealthService: Received start request. Starting profile...
08-31 17:07:17.011  7719  7719 I bluedroid-qcom: get_profile_interface health
08-31 17:07:17.012  7719  7719 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-31 17:07:17.012  7719  7719 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3046f21d
08-31 17:07:17.012  7719  7719 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-31 17:07:17.013  7719  7719 D PanService: Received start request. Starting profile...
08-31 17:07:17.013  7719  7719 D BluetoothPanServiceJni: initializeNative(L110): pan
08-31 17:07:17.013  7719  7719 I bluedroid-qcom: get_profile_interface pan
,08-31 17:07:17.020  7719  7719 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-31 17:07:17.020  7719  7719 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3046f21d
08-31 17:07:17.021  7719  7719 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-31 17:07:17.024  7719  7719 D BtGatt.DebugUtils: handleDebugAction() action=null
08-31 17:07:17.025  7719  7719 D BtGatt.GattService: Received start request. Starting profile...
08-31 17:07:17.025  7719  7719 D BtGatt.GattService: start()
08-31 17:07:17.025  7719  7719 I bluedroid-qcom: get_profile_interface gatt
08-31 17:07:17.025  7719  7719 D BtGatt.AdvertiseManager: advertise manager created
08-31 17:07:17.039  7719  7719 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3046f21d
,08-31 17:07:17.042  7719  7719 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3046f21d
08-31 17:07:17.043  7719  7719 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-31 17:07:17.046  7719  7719 V BluetoothMapService: BluetoothMapBinder()
08-31 17:07:17.047  7719  7719 D BluetoothMapService: Received start request. Starting profile...
08-31 17:07:17.047  7719  7719 D BluetoothMapService: start()
08-31 17:07:17.051  7719  7719 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-31 17:07:17.051  7719  7719 D BluetoothMapEmailAppObserver: createReceiver()
08-31 17:07:17.053  7719  7719 D BluetoothMapEmailAppObserver: initObservers()
08-31 17:07:17.053  7719  7719 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
,08-31 17:07:17.062  7719  7719 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3046f21d
08-31 17:07:17.063  7719  7719 D HeadsetStateMachine: Proxy object connected
08-31 17:07:17.063  7719  7719 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
,08-31 17:07:17.064  7719  7719 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-31 17:07:17.065  7719  7949 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-31 17:07:17.066  7719  7949 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-31 17:07:17.067  7719  7949 D HeadsetStateMachine: Disconnected process message: 11, size: 0
,08-31 17:07:17.071  7719  7719 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-31 17:07:17.076  7719  7719 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-31 17:07:17.082  7719  7719 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-31 17:07:17.087  7719  7719 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-31 17:07:17.092  7719  7719 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-31 17:07:17.092  7719  7719 V PanService: [BTUI] SIM Extra State :ABSENT
08-31 17:07:17.097  7719  7719 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-31 17:07:17.105  7719  7719 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-31 17:07:17.105  7719  7719 V BluetoothMapService: Handler(): got msg=1
08-31 17:07:17.107  7719  7719 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-31 17:07:17.107  7719  7719 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-31 17:07:17.108  7719  7719 V BluetoothSapReceiver: SapReceiver onReceive 
08-31 17:07:17.108  7719  7719 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-31 17:07:17.108  7719  7719 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-31 17:07:17.108  7719  7928 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-31 17:07:17.108  7719  7928 I bluedroid-qcom: enable
08-31 17:07:17.109  7719  7967 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-31 17:07:17.109  7719  7967 I bt-btu  : btu_task pending for preload complete event
08-31 17:07:17.110  7719  7928 I bt_hci_bdroid: init
,08-31 17:07:17.115  7719  7928 I bt_vendor: bt-vendor : init
08-31 17:07:17.115  7719  7928 I bt_vendor: bt-vendor : get_bt_soc_type
08-31 17:07:17.115  7719  7928 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-31 17:07:17.115  7719  7928 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-31 17:07:17.115  7719  7928 D bt_userial_mct: userial_init
08-31 17:07:17.117  7719  7928 D bt_hci_bdroid: set_power 1
08-31 17:07:17.117  7719  7928 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-31 17:07:17.117  7719  7928 I bt_vendor: Starting hciattach daemon
08-31 17:07:17.117  7719  7928 I bt_vendor: try to set true
08-31 17:07:17.114  7970  7970 W sh      : type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 17:07:17.114  7970  7970 W sh      : type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-31 17:07:17.168  7971  7971 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-31 17:07:17.256  7977  7977 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-31 17:07:17.280  7978  7978 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-31 17:07:17.317  7980  7980 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-31 17:07:17.330  7981  7981 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-31 17:07:17.350  7982  7982 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-31 17:07:17.376  7983  7983 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-31 17:07:17.418  7985  7985 I libmdmdetect: ESOC framework not supported
,08-31 17:07:17.420  7985  7985 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
08-31 17:07:17.431  7985  7985 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-31 17:07:17.431  7985  7985 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
,08-31 17:07:17.431  7985  7985 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
,08-31 17:07:17.432  7985  7985 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-31 17:07:17.432  7985  7985 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-31 17:07:17.432  7985  7985 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-31 17:07:17.432  7985  7985 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-31 17:07:17.481  7985  7986 E QC-QMI  : qmi_client [7985] 15: failed to locate client data
08-31 17:07:17.482   486   486 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-31 17:07:17.482   486   486 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
,08-31 17:07:17.548  7987  7987 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-31 17:07:17.574  7991  7991 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-31 17:07:17.623  7719  7928 I bt_vendor: bluetooth satus is on
,08-31 17:07:17.623  7719  7928 D bt_hci_bdroid: preload
,08-31 17:07:17.630  7719  7969 D bt_userial_mct: userial_open(port:0)
,08-31 17:07:17.630  7719  7969 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-31 17:07:17.635  7719  7969 I bt_vendor: Done intiailizing UART
,08-31 17:07:17.638  7719  7969 I bt_vendor: Done intiailizing UART
,08-31 17:07:17.638  7719  7969 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
,08-31 17:07:17.638  7719  7969 I bt_vendor: Bluetooth Firmware and transport layer are initialized,
,08-31 17:07:17.639  7719  7967 I bt-btu  : btu_task received preload complete event
,08-31 17:07:17.640  7719  7967 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
,08-31 17:07:17.640  7719  7967 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
,08-31 17:07:17.669  7719  7993 D bt_userial_mct: Entering userial_read_thread()
08-31 17:07:17.671  7719  7967 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
,08-31 17:07:17.676  7719  7967 I         : BTE_InitTraceLevels -- TRC_HCI
,08-31 17:07:17.676  7719  7967 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-31 17:07:17.676  7719  7967 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-31 17:07:17.677  7719  7967 I         : BTE_InitTraceLevels -- TRC_AVDT
08-31 17:07:17.677  7719  7967 I         : BTE_InitTraceLevels -- TRC_AVRC
08-31 17:07:17.677  7719  7967 I         : BTE_InitTraceLevels -- TRC_A2D
08-31 17:07:17.677  7719  7967 I         : BTE_InitTraceLevels -- TRC_BNEP
08-31 17:07:17.677  7719  7967 I         : BTE_InitTraceLevels -- TRC_BTM
08-31 17:07:17.677  7719  7967 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-31 17:07:17.677  7719  7967 I         : BTE_InitTraceLevels -- TRC_GAP
08-31 17:07:17.677  7719  7967 I         : BTE_InitTraceLevels -- TRC_PAN
08-31 17:07:17.677  7719  7967 I         : BTE_InitTraceLevels -- TRC_SDP
08-31 17:07:17.677  7719  7967 I         : BTE_InitTraceLevels -- TRC_GATT
08-31 17:07:17.677  7719  7967 I         : BTE_InitTraceLevels -- TRC_SMP
08-31 17:07:17.677  7719  7967 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-31 17:07:17.677  7719  7967 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-31 17:07:17.733  7719  7967 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled,
08-31 17:07:17.733  7719  7967 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa0241061 
08-31 17:07:17.733  7719  7967 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0241061 
,08-31 17:07:17.762  7719  7932 E bt-btif : Calling BTA_HhEnable
08-31 17:07:17.762  7719  7932 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
,08-31 17:07:17.766  7719  7932 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-31 17:07:17.768  1042  1042 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-31 17:07:17.768  7719  7967 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-31 17:07:17.769  7719  7967 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-31 17:07:17.769  7719  7967 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-31 17:07:17.769  7719  7967 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-31 17:07:17.769  7719  7967 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-31 17:07:17.770  7719  7932 D BluetoothAdapterProperties: Name is: G3
08-31 17:07:17.772  1042  1042 D BluetoothManagerService: Stored Bluetooth name: G3
08-31 17:07:17.772  7719  7932 D BluetoothAdapterProperties: Scan Mode:20
08-31 17:07:17.773  7719  7932 D BluetoothAdapterProperties: Discoverable Timeout:120
08-31 17:07:17.773  7719  7932 D bt_hci_bdroid: postload
08-31 17:07:17.773  7719  7969 D bt_hci_bdroid: Used up Tx Cmd credits
08-31 17:07:17.774  7719  7967 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
,08-31 17:07:17.781  7719  7969 D bt_hci_bdroid: Used up Tx Cmd credits
08-31 17:07:17.783  7719  7932 D bte_conf: Device ID record 1 : primary
08-31 17:07:17.783  7719  7932 D bte_conf:   vendorId            = 00c4
08-31 17:07:17.783  7719  7932 D bte_conf:   vendorIdSource      = 0001
08-31 17:07:17.783  7719  7932 D bte_conf:   product             = 13a1
08-31 17:07:17.783  7719  7932 D bte_conf:   version             = 1000
08-31 17:07:17.783  7719  7932 D bte_conf:   clientExecutableURL = 
08-31 17:07:17.783  7719  7932 D bte_conf:   serviceDescription  = 
08-31 17:07:17.783  7719  7932 D bte_conf:   documentationURL    = 
08-31 17:07:17.783  7719  7932 D bte_conf: bte_load_did_conf no section named DID2.
08-31 17:07:17.785  7719  7969 D bt_hci_bdroid: Used up Tx Cmd credits
08-31 17:07:17.789  7719  7969 D bt_hci_bdroid: Used up Tx Cmd credits
08-31 17:07:17.784  7998  7998 W sh      : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-31 17:07:17.794  7719  7993 E bt_mct  : hci lib postload completed
08-31 17:07:17.795  7719  7928 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-31 17:07:17.795  7719  7928 D BluetoothAdapterProperties: ScanMode =  20
08-31 17:07:17.795  7719  7928 D BluetoothAdapterProperties: State =  11
08-31 17:07:17.796  7719  7928 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-31 17:07:17.796  7719  7928 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-31 17:07:17.796  7719  7928 D BluetoothAdapterProperties: Setting state to 12
08-31 17:07:17.796  7719  7928 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-31 17:07:17.797  7719  7932 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-31 17:07:17.797  7719  7932 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-31 17:07:17.794  7998  7998 W sh      : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 17:07:17.804  7719  7928 I BluetoothAdapterState: Entering On State
,08-31 17:07:17.808  1042  1117 D BluetoothManagerService: Message: 60
08-31 17:07:17.808  1042  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-31 17:07:17.808  1042  1117 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
08-31 17:07:17.810  7719  7967 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-31 17:07:17.810  7719  7967 W bt-smp  : Plain text(LSB ~ MSB) = 7e 4c 4a 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-31 17:07:17.810  7719  7967 W bt-smp  : Encrypted text(LSB ~ MSB) = 69 ac 26 fd 1b e5 10 38 fb 2b 8d 4f fe 41 1e 2b 
08-31 17:07:17.810  7719  7967 W bt-btm  : Stopping oneshot timer
08-31 17:07:17.825  1866  2552 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-31 17:07:17.838  6694  6694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 17:07:17.838  6694  6694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 17:07:17.838  6694  6694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 17:07:17.838  6694  6694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 17:07:17.838  6694  6694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 17:07:17.838  6694  6694 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 17:07:17.838  6694  6694 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 17:07:17.838  6694  6694 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 17:07:17.845  7719  7967 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-31 17:07:17.845  7719  7967 W bt-smp  : Plain text(LSB ~ MSB) = ce 4f 67 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-31 17:07:17.845  7719  7967 W bt-smp  : Encrypted text(LSB ~ MSB) = 09 4b 5b 10 c4 7b 06 6a ca 03 b7 84 d6 c8 bc b6 
08-31 17:07:17.845  7719  7967 W bt-btm  : Stopping oneshot timer
08-31 17:07:17.851  7719  7932 D BluetoothAdapterProperties: Discoverable Timeout:120
08-31 17:07:17.851  7719  7932 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
,08-31 17:07:17.854  6694  6694 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 17:07:17.862  7719  7967 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-31 17:07:17.862  7719  7967 W bt-smp  : Plain text(LSB ~ MSB) = 0f a1 68 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-31 17:07:17.862  7719  7967 W bt-smp  : Encrypted text(LSB ~ MSB) = b4 1f b4 34 02 df 00 b9 f2 9c 10 e1 fb 7c 04 88 
08-31 17:07:17.863  7719  7967 W bt-btm  : Stopping oneshot timer
,08-31 17:07:17.874  7719  7928 D LGBluetoothServiceAdapter: [BTUI] OnState
08-31 17:07:17.875  7719  7928 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-31 17:07:17.875  7719  7928 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
,08-31 17:07:17.878  7719  7928 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-31 17:07:17.878  7719  7928 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-31 17:07:17.884  1866  1866 D BluetoothHeadset: Proxy object connected
08-31 17:07:17.884  7719  7967 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-31 17:07:17.885  7719  7967 W bt-smp  : Plain text(LSB ~ MSB) = c3 db 48 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-31 17:07:17.885  7719  7967 W bt-smp  : Encrypted text(LSB ~ MSB) = 0f 61 29 79 d2 62 e0 ac 66 3a a3 cc d1 16 a4 ee 
08-31 17:07:17.885  7719  7967 W bt-btm  : Stopping oneshot timer
08-31 17:07:17.885  1866  1881 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 17:07:17.898  1866  1866 D BluetoothHeadset: Proxy object connected
,08-31 17:07:17.921  8003  8003 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
,08-31 17:07:17.926  7719  7967 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-31 17:07:17.926  7719  7967 W bt-smp  : Plain text(LSB ~ MSB) = 1a d3 78 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-31 17:07:17.926  7719  7967 W bt-smp  : Encrypted text(LSB ~ MSB) = d4 a8 74 d1 1d cf 6c 51 3e 3a 7c f0 d8 04 df 2b 
08-31 17:07:17.926  7719  7967 W bt-btm  : Stopping oneshot timer
08-31 17:07:17.927  6878  6896 D BluetoothPbap: onBluetoothStateChange: up=true
08-31 17:07:17.932  1042  1117 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 17:07:17.934  1042  1042 D BluetoothHeadset: Proxy object connected
08-31 17:07:17.940  1866  2524 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-31 17:07:17.946  1866  1866 D BluetoothHeadset: Proxy object connected
08-31 17:07:17.948  6878  7396 D BluetoothA2dp: onBluetoothStateChange: up=true
08-31 17:07:17.952  6878  6897 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 17:07:17.953  6878  6878 D BluetoothA2dp: Proxy object connected
08-31 17:07:17.953  6878  6878 D A2dpProfile: Bluetooth service connected
,08-31 17:07:17.958  6878  6896 D BluetoothMap: onBluetoothStateChange: up=true
08-31 17:07:17.963  1042  1117 D BluetoothA2dp: onBluetoothStateChange: up=true
08-31 17:07:17.963  6878  6878 D BluetoothHeadset: Proxy object connected
08-31 17:07:17.963  6878  6878 D HeadsetProfile: Bluetooth service connected
08-31 17:07:17.964  1042  1042 D BluetoothA2dp: Proxy object connected
,08-31 17:07:17.964  6878  6896 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-31 17:07:17.966  6878  6897 D BluetoothPan: onBluetoothStateChange on: true
08-31 17:07:17.966  6878  6897 D BluetoothPan: onBluetoothStateChange call bindService
,08-31 17:07:17.969  6878  6878 D BluetoothMap: Proxy object connected
08-31 17:07:17.969  6878  6878 D MapProfile: Bluetooth service connected
08-31 17:07:17.969  6878  6878 D BluetoothMap: getConnectedDevices()
08-31 17:07:17.971  1042  1117 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-31 17:07:17.971  7719  7737 V BluetoothMapService: getConnectedDevices()
08-31 17:07:17.971  1042  1117 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-31 17:07:17.973  1956  1956 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-31 17:07:17.976  6694  6694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 17:07:17.976  1956  2166 D LGBluetoothAPIService: Message: 1
08-31 17:07:17.976  1956  2166 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-31 17:07:17.977  1956  2166 D LGBluetoothAPIService: Calling onBluetoothServiceUp callbacks
08-31 17:07:17.977  1956  2166 D LGBluetoothAPIService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-31 17:07:17.978  1589  1589 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-31 17:07:17.978  6878  6878 D BluetoothInputDevice: Proxy object connected
08-31 17:07:17.978  6878  6878 D HidProfile: Bluetooth service connected
08-31 17:07:17.980  1042  1042 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-31 17:07:17.981  1042  1117 D BluetoothManagerService: Message: 40
08-31 17:07:17.981  1042  1117 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-31 17:07:17.982  6878  6878 D BluetoothPan: BluetoothPAN Proxy object connected
08-31 17:07:17.982  6878  6878 D PanProfile: Bluetooth service connected
08-31 17:07:17.983  7719  7719 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-31 17:07:17.983  7719  7719 D BluetoothMapService: STATE_ON
08-31 17:07:17.991  6878  6878 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-31 17:07:17.993  6878  6878 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-31 17:07:17.999  6878  6878 D DockEventReceiver: finishStartingService: stopping service
08-31 17:07:18.001  7719  7719 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3046f21d
08-31 17:07:18.001  7719  7719 V BluetoothPbapService: Pbap Service onCreate
08-31 17:07:18.001  7719  7719 V BluetoothPbapService: Starting PBAP service
,08-31 17:07:18.003  7719  7719 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-31 17:07:18.003  7719  7719 V BluetoothMapService: Handler(): got msg=1
08-31 17:07:18.004  7719  7719 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-31 17:07:18.005  7719  7719 V BluetoothPbapService: Pbap Service onBind
08-31 17:07:18.005  7719  8023 D BluetoothMapMasInstance: MAS initSocket()
08-31 17:07:18.006  7719  8023 D BluetoothMapMasInstance:   masId = 00
08-31 17:07:18.006  7719  8023 D BluetoothMapMasInstance:   msgTypes = 0e
08-31 17:07:18.006  7719  8023 D BluetoothMapMasInstance:   masName = SMS/MMS
08-31 17:07:18.006  7719  8023 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-31 17:07:18.006  6878  6878 D BluetoothPbap: Proxy object connected
08-31 17:07:18.006  7719  7719 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-31 17:07:18.006  6878  6878 D PbapServerProfile: Bluetooth service connected
08-31 17:07:18.006  7719  7719 V BluetoothPbapService: state: 12
08-31 17:07:18.007  7719  7719 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-31 17:07:18.007  7719  7719 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-31 17:07:18.007  7719  7719 V BluetoothPbapReceiver: ***********state = 12
,08-31 17:07:18.007  1042  2248 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 17:07:18.009  7719  7719 V BluetoothPbapService: Handler(): got msg=1
08-31 17:07:18.009  7719  7719 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-31 17:07:18.011  7719  8023 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 17:07:18.011  2230  2230 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-31 17:07:18.011  7719  8025 V BluetoothPbapService: Pbap Service initSocket
08-31 17:07:18.011  2230  2230 D c       : Getting all permits...
08-31 17:07:18.011  2230  2230 D a       : Opening database...
08-31 17:07:18.011  1042  1058 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 17:07:18.012  7719  8025 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 17:07:18.013  7719  8023 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-31 17:07:18.013  7719  8023 V BluetoothMapMasInstance: Succeed to create listening socket 
08-31 17:07:18.014  7719  7932 D BluetoothAdapterProperties: Scan Mode:21
08-31 17:07:18.015  7719  8025 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-31 17:07:18.015  2230  2230 D a       : Opening database auth.proximity.permit_store...
08-31 17:07:18.015  7719  8025 V BluetoothPbapService: Succeed to create listening socket 
08-31 17:07:18.016  2230  2230 D a       : Closing database...
08-31 17:07:18.017  7719  7932 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-31 17:07:18.017  7719  8025 V BluetoothPbapService: Accepting socket connection...
,08-31 17:07:18.017  7719  8023 D BluetoothMapMasInstance: Accepting socket connection...
08-31 17:07:18.020  6694  6694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 17:07:18.028  6878  6878 D BluetoothPermissionRequest: onReceive
,08-31 17:07:18.030  6878  6878 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-31 17:07:18.032  6878  6878 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-31 17:07:18.036  7719  7719 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-31 17:07:18.037  7719  7719 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-31 17:07:18.043  7719  7719 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-31 17:07:18.064  7719  7719 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,08-31 17:07:18.064  7719  7719 V BtOppService: onCreate
,08-31 17:07:18.069  7719  7719 V BluetoothOppNotification: send message
08-31 17:07:18.073  7719  7719 V BtOppService: Starting RfcommListener
08-31 17:07:18.089  7719  7719 D BluetoothOppPreference: Dumping Names:  
08-31 17:07:18.089  7719  7719 D BluetoothOppPreference: {}
08-31 17:07:18.089  7719  7719 D BluetoothOppPreference: Dumping Channels:  
08-31 17:07:18.089  7719  7719 D BluetoothOppPreference: {}
08-31 17:07:18.091  7719  7719 V BtOppService: onStartCommand
,08-31 17:07:18.094  7719  8028 V BtOppService: Deleted complete outbound shares, number =  0
08-31 17:07:18.095  7719  8028 V BtOppService: Deleted complete inbound failed shares, number = 0
08-31 17:07:18.097  7719  7719 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-31 17:07:18.097  7719  7719 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-31 17:07:18.097  7719  8028 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-31 17:07:18.098  7719  8031 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-31 17:07:18.098  7719  8031 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-31 17:07:18.100  7719  8028 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@482eb69 on behalf of 
08-31 17:07:18.100  7719  8031 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@bae69ee on behalf of 
08-31 17:07:18.101  7719  8031 V BluetoothOppNotification: update too frequent, put in queue
08-31 17:07:18.102  7719  8031 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
,08-31 17:07:18.103  7719  7719 V BluetoothOppNotification: new notify threadi!
08-31 17:07:18.104  7719  7719 V BluetoothOppNotification: send delay message
08-31 17:07:18.105  7719  7719 V BtOppService: start RfcommListener
08-31 17:07:18.110  7719  7719 V BtOppService: RfcommListener started
08-31 17:07:18.110  7719  7719 V BtOppService: ContentObserver received notification
08-31 17:07:18.113  7719  7719 V BtOppService: ContentObserver received notification
08-31 17:07:18.113  7719  8033 V BtOppRfcommListener: Starting RFCOMM listener....
08-31 17:07:18.113  1042  2027 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-31 17:07:18.115  7719  8034 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-31 17:07:18.115  7719  8033 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-31 17:07:18.116  7719  8034 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-31 17:07:18.117  7719  8032 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-31 17:07:18.118  7719  8033 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=78 mFd=75
08-31 17:07:18.118  7719  8033 V BtOppRfcommListener: Started RFCOMM listener....
08-31 17:07:18.119  7719  8033 I BtOppRfcommListener: Accept thread started.
08-31 17:07:18.119  7719  8033 V BtOppRfcommListener: Accepting connection...
08-31 17:07:18.119  7719  8034 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@399dce8f on behalf of 
08-31 17:07:18.120  7719  8032 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2ebab51c on behalf of 
08-31 17:07:18.122  7719  8032 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-31 17:07:18.122  7719  8034 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-31 17:07:18.124  7719  8032 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-31 17:07:18.125  7719  8032 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3855d525 on behalf of 
,08-31 17:07:18.126  7719  8032 V BluetoothOppNotification: outbound: succ-0  fail-0
08-31 17:07:18.128  7719  8032 V BluetoothOppNotification: outbound notification was removed.
08-31 17:07:18.128  7719  8032 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-31 17:07:18.130  7719  8032 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@231b36fa on behalf of 
08-31 17:07:18.131  7719  8032 V BluetoothOppNotification: inbound: succ-0  fail-0
,08-31 17:07:18.133  7719  8032 V BluetoothOppNotification: inbound notification was removed.
08-31 17:07:18.134  7719  8032 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-31 17:07:18.135  7719  7719 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3046f21d
08-31 17:07:18.135  7719  7719 V BluetoothFtpService: Ftp Service onCreate
08-31 17:07:18.135  7719  7719 I BluetoothFtpService: Ftp Service onCreate
08-31 17:07:18.136  7719  7719 V BluetoothFtpService: Ftp Service onStartCommand
08-31 17:07:18.136  7719  7719 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-31 17:07:18.136  7719  7719 V BluetoothFtpService: Starting Listening on sockets
,08-31 17:07:18.136  7719  7719 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-31 17:07:18.137  7719  7719 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-31 17:07:18.137  7719  7719 V BluetoothSapReceiver: SapReceiver onReceive 
08-31 17:07:18.137  7719  7719 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-31 17:07:18.137  7719  7719 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-31 17:07:18.137  7719  7719 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-31 17:07:18.141  7719  7719 V BluetoothFtpService: Handler(): got msg=1
08-31 17:07:18.144  7719  7719 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-31 17:07:18.145  7719  7719 V BluetoothFtpService: Ftp Service initSocket
08-31 17:07:18.148  1042  1561 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 17:07:18.149  7719  7719 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-31 17:07:18.150  7719  7719 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=78
08-31 17:07:18.151  7719  7719 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-31 17:07:18.153  7719  8036 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-31 17:07:18.177  7719  7719 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3046f21d
,08-31 17:07:18.177  7719  7719 V BluetoothSapService: Sap Service onCreate
08-31 17:07:18.180  7719  7719 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-31 17:07:18.180  7719  7719 V BluetoothSapService: state: 12
08-31 17:07:18.180  7719  7719 V BluetoothSapService: Starting SAP server process
08-31 17:07:18.181  7719  7719 V BluetoothSapService: SAP Service startRfcommListenerThread
08-31 17:07:18.174  8037  8037 W sapd    : type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 17:07:18.174  8037  8037 W sapd    : type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 17:07:18.183  7719  8038 V BluetoothSapService: Sap Service initRfcommSocket
08-31 17:07:18.184  1042  2341 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 17:07:18.185  7719  8038 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 17:07:18.191  7719  8038 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-31 17:07:18.191  7719  8038 V BluetoothSapService: Succeed to create listening socket 
08-31 17:07:18.191  7719  8038 V BluetoothSapService: Accepting socket connection...
,08-31 17:07:18.195  8037  8037 V BT_SAP  : Event pipe created
08-31 17:07:18.195  8037  8037 V BT_SAP  : create_server_socket qcom.sap.server
08-31 17:07:18.195  8037  8037 V BT_SAP  : created socket fd 6
08-31 17:07:18.280  1042  1728 I art     : Explicit concurrent mark sweep GC freed 24944(1235KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 2.202ms total 143.896ms
08-31 17:07:18.280  7719  8032 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@23d70087 on behalf of 
,08-31 17:07:18.594  6694  6804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 17:07:18.594  6694  6804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 17:07:18.594  6694  6804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 17:07:18.594  6694  6804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 17:07:18.594  6694  6804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 17:07:18.594  6694  6804 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 17:07:18.594  6694  6804 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 17:07:18.594  6694  6804 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 17:07:18.606  6694  6804 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 17:07:18.613  6694  6804 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-31 17:07:18.613  6694  6804 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2e21d366 added. We now have 8 listener(s)
08-31 17:07:18.627  6694  6804 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 17:07:18.633  1042  1058 D WifiServiceImplEx: setWifiEnabled: false pid=6694, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-31 17:07:18.633  1042  1058 D WifiService: setWifiEnabled: false pid=6694, uid=10118
08-31 17:07:18.633  1042  1058 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-31 17:07:18.637  6694  6804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 17:07:18.639  1042  1955 D WifiServiceImplEx: setWifiEnabled: true pid=6694, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-31 17:07:18.639  1042  1955 D WifiService: setWifiEnabled: true pid=6694, uid=10118
08-31 17:07:18.639  1042  1955 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-31 17:07:18.660  1042  1042 D LocationManagerService: getAllProviders()=[passive, gps, network]
,08-31 17:07:18.660  1042  1042 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
,08-31 17:07:18.660  1042  1042 D Ulp_jni : JNI:system_update. Event-4
,08-31 17:07:18.662  1042  1523 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
,08-31 17:07:18.662  1042  1523 I LGFTMITEM: [GET_FTM][id=6], offset=12288
,08-31 17:07:18.664  1042  1523 E WifiUtil: wfc_util_ffile_check_copy(): pid[1042] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-31 17:07:18.664  1042  1523 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-31 17:07:18.665  1042  1523 E WifiUtil: wfc_util_ffile_check_copy(): pid[1042] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-31 17:07:18.665  1042  1523 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
,08-31 17:07:18.665  1042  1523 I WifiUtil: Intf0MacAddress=C49A027FFB5D,
08-31 17:07:18.665  1042  1523 E WifiHW  : unknown target_country: EU , set to default
,08-31 17:07:18.665  1042  1523 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
,08-31 17:07:18.665  1042  1523 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
,08-31 17:07:18.665  1042  1523 I WifiUtil: gEnableBmps=1,
08-31 17:07:19.107  7719  7719 V BluetoothOppNotification: new notify threadi!
08-31 17:07:19.107  7719  7719 V BluetoothOppNotification: send delay message
,08-31 17:07:19.132  7719  8051 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-31 17:07:19.134  7719  8051 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@341e8bb4 on behalf of 
08-31 17:07:19.135  7719  8051 V BluetoothOppNotification: mUpdateCompleteNotification = true
,08-31 17:07:19.138  7719  8051 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,08-31 17:07:19.154  7719  8051 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@ca83dd on behalf of 
,08-31 17:07:19.173  7719  8051 V BluetoothOppNotification: outbound: succ-0  fail-0
,08-31 17:07:19.177  7719  8051 V BluetoothOppNotification: outbound notification was removed.
,08-31 17:07:19.177  7719  8051 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-31 17:07:19.179  7719  8051 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2455ab52 on behalf of 
,08-31 17:07:19.180  7719  8051 V BluetoothOppNotification: inbound: succ-0  fail-0
08-31 17:07:19.182  7719  8051 V BluetoothOppNotification: inbound notification was removed.
08-31 17:07:19.182  7719  8051 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-31 17:07:19.183  7719  8051 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@26191e23 on behalf of 
08-31 17:07:19.336   313   893 D SoftapController: Softap fwReload - Ok
,08-31 17:07:19.348  1042  1117 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-31 17:07:19.350  1042  1523 E NetdConnector: NDC Command {83 softap fwreload wlan0 STA} took too long (680ms)
,08-31 17:07:19.366   313   893 D CommandListener: Setting iface cfg
08-31 17:07:19.366   313   893 D CommandListener: Trying to bring down wlan0
08-31 17:07:19.376  1042  1117 D Tethering: InitialState.processMessage what=4
08-31 17:07:19.377  1042  1117 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-31 17:07:19.387   313   893 D CommandListener: Clearing all IP addresses on wlan0
08-31 17:07:19.395  1042  1523 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,08-31 17:07:19.404  8059  8059 W wpa_supplicant: type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-31 17:07:19.415  1042  1523 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-31 17:07:19.415  1042  1523 E WifiStateMachine: useWiFiOffloading() : false
08-31 17:07:19.415  1042  1523 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-31 17:07:19.414  8059  8059 W wpa_supplicant: type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 17:07:19.432  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-31 17:07:19.439  1956  1956 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-31 17:07:19.455  6694  6694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 17:07:19.464  1042  1523 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-31 17:07:19.464  1042  1523 D WifiMonitor: connecting to supplicant
08-31 17:07:19.469  6878  6878 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-31 17:07:19.469  6878  6878 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-31 17:07:19.469  6878  6878 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-31 17:07:19.469  6878  6878 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
,08-31 17:07:19.473  1042  1042 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-31 17:07:19.475  6878  6878 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-31 17:07:19.477  6878  6878 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-31 17:07:19.477  6878  6878 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-31 17:07:19.477  6878  6878 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-31 17:07:19.477  6878  6878 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-31 17:07:19.477  6878  6878 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-31 17:07:19.478  6878  6878 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-31 17:07:19.483  6878  6878 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-31 17:07:19.483  6878  6878 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-31 17:07:19.483  6878  6878 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-31 17:07:19.483  6878  6878 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
,08-31 17:07:19.484  8059  8059 I wpa_supplicant: Successfully initialized wpa_supplicant
08-31 17:07:19.486  6878  6878 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-31 17:07:19.487  6878  6878 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-31 17:07:19.487  6878  6878 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-31 17:07:19.487  6878  6878 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-31 17:07:19.488  6878  6878 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-31 17:07:19.488  6878  6878 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-31 17:07:19.488  6878  6878 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-31 17:07:19.520  8059  8059 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-31 17:07:19.521  8059  8059 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,08-31 17:07:19.543  1042  1918 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=8078 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-31 17:07:19.577  8059  8059 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-31 17:07:19.667  8059  8059 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-31 17:07:19.682  8059  8059 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
,08-31 17:07:19.687  1042  8104 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-31 17:07:19.687  1042  8104 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-31 17:07:19.687  1042  8104 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-31 17:07:19.687  1042  8104 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-31 17:07:19.687  1042  1523 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-31 17:07:19.689  1042  1523 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-31 17:07:19.690  1042  1523 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-31 17:07:19.691  1042  1523 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-31 17:07:19.693  1042  1523 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-31 17:07:19.694  1042  1523 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-31 17:07:19.694  1042  1954 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=8099 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-31 17:07:19.695  1042  1523 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
,08-31 17:07:19.697  1042  1523 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-31 17:07:19.699  1042  1523 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-31 17:07:19.699  1042  1523 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-31 17:07:19.700  1042  1523 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-31 17:07:19.700  1042  1523 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-31 17:07:19.700  1042  1523 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-31 17:07:19.702  1042  1523 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-31 17:07:19.702  1042  1523 E WifiStateMachine: useWiFiOffloading() : false
08-31 17:07:19.702  1042  1523 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-31 17:07:19.702  1042  1042 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 17:07:19.702  1042  1042 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 17:07:19.703  1042  1042 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 17:07:19.703  1042  1523 D WifiNative-wlan0: doBoolean: SET update_config 1
08-31 17:07:19.703  1042  1042 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 17:07:19.703  1042  1042 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-31 17:07:19.703  1042  1523 D WifiNative-wlan0: SET update_config 1: returned true
08-31 17:07:19.704  1042  1523 D WifiConfigStore: Loading config and enabling all networks 
08-31 17:07:19.704  1042  1523 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-31 17:07:19.704  1042  1523 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-31 17:07:19.705  1956  1956 D WfdService: Waiting for WifiP2p enabling
08-31 17:07:19.706  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 17:07:19.707  1042  1042 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
,08-31 17:07:19.712  6694  6694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 17:07:19.712  6694  6694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 17:07:19.712  6694  6694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 17:07:19.712  6694  6694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 17:07:19.712  6694  6694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 17:07:19.712  6694  6694 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 17:07:19.712  6694  6694 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 17:07:19.712  6694  6694 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 17:07:19.714  6694  6694 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-31 17:07:19.714   351   351 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 426us total 21.207ms
08-31 17:07:19.714  1042  1528 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-31 17:07:19.715  8078  8097 W FormManager: Network not available. Please check & try again.
08-31 17:07:19.715  1042  1523 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
,08-31 17:07:19.726  1042  1523 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-31 17:07:19.726  1042  1523 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-31 17:07:19.727  1042  1523 D WifiStateMachine: enableVerboseLogging : level 2
08-31 17:07:19.727  1042  1523 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-31 17:07:19.728  1042  1523 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-31 17:07:19.728  1042  1523 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-31 17:07:19.729  1042  1523 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-31 17:07:19.729  1042  1523 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-31 17:07:19.729  1042  1523 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-31 17:07:19.729  1042  1523 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-31 17:07:19.730  1042  1523 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-31 17:07:19.730  1042  1523 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-31 17:07:19.730  1042  1523 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-31 17:07:19.730  1042  1523 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-31 17:07:19.731  1042  1523 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
,08-31 17:07:19.731  1042  1523 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-31 17:07:19.731   351   351 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 366us total 17.192ms
08-31 17:07:19.731  1042  1523 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-31 17:07:19.732  1042  1523 D WifiStateMachine: Setting OUI to DA-A1-19
08-31 17:07:19.732  1042  1523 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
,08-31 17:07:19.733  1042  1523 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-31 17:07:19.733  1042  1523 D WifiNative-HAL: Setting external_sim to 1
08-31 17:07:19.733  1042  1523 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-31 17:07:19.733  1042  1523 D WifiNative-wlan0: SET external_sim 1: returned true
08-31 17:07:19.733  1042  1523 I WifiNative-HAL: startHal
08-31 17:07:19.733  1042  1523 D wifi    : setting scan oui 0xaf6ca040
08-31 17:07:19.734  1042  1523 D WifiStateMachine: Setting OUI to DA-A1-19
08-31 17:07:19.734  1042  1523 I WifiNative-HAL: startHal
08-31 17:07:19.734  1042  1523 D wifi    : setting scan oui 0xaf6ca040
08-31 17:07:19.734  1042  1523 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-31 17:07:19.735  1042  1523 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-31 17:07:19.735  1042  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-31 17:07:19.735  8059  8059 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-31 17:07:19.736  1042  1523 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-31 17:07:19.736  1042  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-31 17:07:19.736  8059  8059 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-31 17:07:19.736  1042  1523 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-31 17:07:19.736  1042  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-31 17:07:19.737  8059  8059 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-31 17:07:19.737  1042  1523 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-31 17:07:19.737  1042  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-31 17:07:19.737  8059  8059 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-31 17:07:19.737  1042  1523 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-31 17:07:19.737  1042  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-31 17:07:19.737  8059  8059 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-31 17:07:19.738  1042  1523 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-31 17:07:19.738  1042  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-31 17:07:19.738  8059  8059 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-31 17:07:19.739  1042  1523 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-31 17:07:19.739  1042  1523 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-31 17:07:19.739  8059  8059 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-31 17:07:19.739  1956  1956 D WfdsService: Supplicant Connection state is changed : true
08-31 17:07:19.739  1042  1523 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-31 17:07:19.740  1956  2323 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-31 17:07:19.740  1956  2323 D WfdsService: Set the WFDS Monitor: true
08-31 17:07:19.740  1956  2323 D WfdsMonitor: WfdsMonitorThread create
08-31 17:07:19.740  1956  2323 D WfdsMonitor: WFDS Monitor is created and started
08-31 17:07:19.740  1956  2323 D WfdsService: WiFi: Supplicant connection re-established
08-31 17:07:19.740  7749  7749 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 17:07:19.740  1042  1523 E WifiNative: : [137,816,030 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-31 17:07:19.740  1042  1523 D WifiNative-wlan0: doBoolean: RECONNECT
08-31 17:07:19.741  1956  8118 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-31 17:07:19.741  1042  1523 D WifiNative-wlan0: RECONNECT: returned true
08-31 17:07:19.741  1042  1523 D WifiNative-wlan0: doString: [STATUS]
08-31 17:07:19.741  1956  8118 E CtrlSupplicant: Succeed to open control connection
08-31 17:07:19.741  1956  8118 E CtrlSupplicant: Succeed to open monitor connection
08-31 17:07:19.741  1042  8,104 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-31 17:07:19.742  1042  8104 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-31 17:07:19.742  1956  8118 D WfdsMonitor: Supplicant connection established
08-31 17:07:19.742  1956  2323 D WfdsService: Connected to the supplicant for wfds
08-31 17:07:19.742  1042  1523 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-31 17:07:19.742  1042  1523 D WifiNative-wlan0: doBoolean: SET ps 1
08-31 17:07:19.742  1042  1523 D WifiNative-wlan0: SET ps 1: returned true
08-31 17:07:19.743  1042  1522 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
,08-31 17:07:19.743  1042  1042 D WifiScanningService: SCAN_AVAILABLE : 3
08-31 17:07:19.743  1042  1042 D RttService: SCAN_AVAILABLE : 3
08-31 17:07:19.743  1042  1542 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-31 17:07:19.743  1042  1542 I WifiNative-HAL: startHal
08-31 17:07:19.743  1042  1542 D wifi    : getting scan capabilities on interface[1] = 0xaf6ca040
08-31 17:07:19.743  1042  1542 D wifi    : failed to get capabilities : -3
,08-31 17:07:19.743  1042  1542 E WifiScanningService: could not get scan capabilities
08-31 17:07:19.743  1042  1523 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-31 17:07:19.744  1042  1543 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-31 17:07:19.744  1042  1523 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-31 17:07:19.744   313   893 D CommandListener: Setting iface cfg
08-31 17:07:19.744   313   893 D CommandListener: Trying to bring up p2p0
08-31 17:07:19.744  1042  1523 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-31 17:07:19.744  1042  1522 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-31 17:07:19.744  1042  1523 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-31 17:07:19.745  1042  1522 D LGWifiP2pService: P2pEnablingState
08-31 17:07:19.745  1042  1522 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-31 17:07:19.745  1042  1522 D LGWifiP2pService: P2p socket connection successful
08-31 17:07:19.745  1042  1522 D LGWifiP2pService: P2pEnabledState
08-31 17:07:19.745  1042  1523 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-31 17:07:19.745  1042  1523 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-31 17:07:19.746  1042  1523 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-31 17:07:19.746  1042  1523 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-31 17:07:19.746  8059  8059 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-31 17:07:19.746  1042  1523 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-31 17:07:19.747  1042  1523 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-31 17:07:19.747   351   351 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 293us total 14.741ms
08-31 17:07:19.747  1956  1956 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-31 17:07:19.747  1956  1956 D WfdsService: WifiP2pState is changed : true
08-31 17:07:19.747  1042  1523 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-31 17:07:19.747  1042  1523 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-31 17:07:19.747  8059  8059 E wpa_supplicant: disconnect_rssi_lvl: -100
08-31 17:07:19.747  1956  2323 D WfdsService: Receive the WFDS_ENABLE Method
08-31 17:07:19.747  1956  2323 D WfdsService: Set the WFDS Monitor: true
08-31 17:07:19.747  1956  2323 D WfdsService: Connected to the supplicant for wfds
08-31 17:07:19.747  1956  2323 D WfdsJNI : doCommand: WFDS_SET TRUE
08-31 17:07:19.747  8059  8059 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-31 17:07:19.748  1956  2323 D WfdsService: selectPreferredScanChannel [36]
08-31 17:07:19.748  1956  2323 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-31 17:07:19.749  1042  1523 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
08-31 17:07:19.750  1042  1523 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
08-31 17:07:19.750  1042  1522 D LGWifiP2pService: sending p2p connection changed broadcast
08-31 17:07:19.750  1042  1523 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
08-31 17:07:19.750  1042  1523 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-31 17:07:19.751  8059  8059 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-31 17:07:19.751  8059  8059 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-31 17:07:19.752  8059  8059 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-31 17:07:19.752  8059  8059 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 17:07:19.752  1042  1523 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-31 17:07:19.752  1042  8104 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=C,OUNTRY alpha2=CZ]
08-31 17:07:19.752  1042  8104 E WifiMonitor: WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-31 17:07:19.752  1042  8104 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-31 17:07:19.752  1042  8104 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-31 17:07:19.752  1042  8104 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-31 17:07:19.752  1042  8104 E WifiMonitor: WifiMonitor:p2p0 cnt=47 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 17:07:19.752  1042  8104 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 17:07:19.752  1042  1523 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-31 17:07:19.752  1042  8104 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 17:07:19.752  8059  8059 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 17:07:19.752  1956  8118 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-31 17:07:19.752  1956  8118 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-31 17:07:19.752  1042  8104 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-31 17:07:19.752  1042  8104 E WifiMonitor: WifiMonitor:p2p0 cnt=48 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 17:07:19.753  1042  1523 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-31 17:07:19.753  1042  8104 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 17:07:19.753  1042  8104 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 17:07:19.753  1042  1523 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-31 17:07:19.753  1042  1523 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-31 17:07:19.753  8059  8059 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-31 17:07:19.753  8059  8059 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-31 17:07:19.753  1042  8104 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-31 17:07:19.753  1042  8104 E WifiMonitor: WifiMonitor:wlan0 cnt=49 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-31 17:07:19.753  1042  8104 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-31 17:07:19.753  1042  8104 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-31 17:07:19.754  1042  1522 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-31 17:07:19.754  1042  1523 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-31 17:07:19.755  1042  1522 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-31 17:07:19.755  1042  1522 D WifiNative-p2p0: doBoolean: SET device_name G3
08-31 17:07:19.755  1042  1522 D WifiNative-p2p0: SET device_name G3: returned true
08-31 17:07:19.755  1956  1956 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-31 17:07:19.755  1042  1522 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-31 17:07:19.755  1042  1522 D LGWifiP2pService: before postfix = G3
08-31 17:07:19.755  1042  1522 D WifiServerServiceExt: postfix byte check : 2
08-31 17:07:19.755  1042  1522 D LGWifiP2pService: after postfix = G3
,08-31 17:07:19.755  1042  1522 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-31 17:07:19.755  1956  1956 D WfdsService: isConnected: false
08-31 17:07:19.756  1042  1522 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-31 17:07:19.756  1042  1522 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-31 17:07:19.756  1042  1523 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-31 17:07:19.756  1042  1522 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-31 17:07:19.756  1042  1522 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-31 17:07:19.757  1042  1523 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-31 17:07:19.757  1042  1523 D WifiNative-wlan0: doBoolean: SCAN
08-31 17:07:19.757  1042  1523 D WifiNative-wlan0: SCAN: returned false
08-31 17:07:19.758  1042  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=137833  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
,08-31 17:07:19.758  1042  1522 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-31 17:07:19.758  1042  1522 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-31 17:07:19.759  1042  1522 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-31 17:07:19.759  1042  1522 D WifiNative-HAL: p2pGetDeviceAddress
08-31 17:07:19.759  1042  1522 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
,08-31 17:07:19.761  1042  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=137837  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-31 17:07:19.761  1956  1956 I WfdStateTracker: handleP2pThisDeviceChanged
08-31 17:07:19.761  1956  1956 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-31 17:07:19.761  1956  1956 D WfdsService: Update P2p Interface State: 3
08-31 17:07:19.762  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 17:07:19.762  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 17:07:19.763  1042  1523 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
,08-31 17:07:19.764  1042  1523 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-31 17:07:19.764  1042  1523 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-31 17:07:19.764  1042  1523 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-31 17:07:19.764  1042  1523 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-31 17:07:19.765  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 17:07:19.765  1042  1522 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-31 17:07:19.765  1042  1522 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-31 17:07:19.765  1042  1522 D WifiNative-p2p0: P2P_FLUSH: returned true
08-31 17:07:19.765  1042  1522 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-31 17:07:19.765  1042  1522 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-31 17:07:19.765  1042  1522 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-31 17:07:19.766  1042  1522 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-31 17:07:19.766  1042  1522 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-31 17:07:19.766  1042  1042 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 17:07:19.766  1042  1042 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 17:07:19.766  1042  1042 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-31 17:07:19.766  1042  1042 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-31 17:07:19.766  8078  8098 V FormManager: Network unavailable.
08-31 17:07:19.766  1042  1042 D WifiServerServiceExt: setSupplicantStateSCANNING
08-31 17:07:19.769  8078  8098 V FormManager: Network unavailable.
08-31 17:07:19.774  1042  1522 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-31 17:07:19.774  1042  1522 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-31 17:07:19.774  1042  1522 D LGWifiP2pService: InactiveState
08-31 17:07:19.775  1042  1522 D LGWifiP2pService: InactiveState{ when=-23ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-31 17:07:19.775  1042  1522 D LGWifiP2pService: P2pEnabledState{ when=-23ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-31 17:07:19.775  1042  1522 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-31 17:07:19.775  8059  8059 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
,08-31 17:07:19.775  8059  8059 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
,08-31 17:07:19.776  1956  8118 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-31 17:07:19.776  8059  8059 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-31 17:07:19.776  8059  8059 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 17:07:19.776  1956  8118 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-31 17:07:19.777  8059  8059 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 17:07:19.777  1956  8118 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-31 17:07:19.777  1042  8104 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-31 17:07:19.777  1042  8104 E WifiMonitor: WifiMonitor:p2p0 cnt=50 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-31 17:07:19.777  1042  8104 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-31 17:07:19.777  1042  8104 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-31 17:07:19.777  1042  8104 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-31 17:07:19.777  1042  8104 E WifiMonitor: WifiMonitor:p2p0 cnt=51 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 17:07:19.778  1042  8104 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 17:07:19.778  1042  8104 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 17:07:19.778  1042  8104 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-31 17:07:19.778  1042  8104 E WifiMonitor: WifiMonitor:p2p0 cnt=52 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 17:07:19.778  1042  8104 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 17:07:19.778  1042  8104 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,08-31 17:07:19.779  1042  1522 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-31 17:07:19.779  1042  1522 D LGWifiP2pService: InactiveState{ when=-13ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-31 17:07:19.779  1042  1522 D LGWifiP2pService: P2pEnabledState{ when=-13ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-31 17:07:19.779  1042  1522 D LGWifiP2pService: InactiveState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-31 17:07:19.779  1042  1522 D LGWifiP2pService: P2pEnabledState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-31 17:07:19.779  1042  1522 D LGWifiP2pService: DefaultState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-31 17:07:19.779  1042  1522 D LGWifiP2pService: InactiveState{ when=-1ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-31 17:07:19.779  1042  1522 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-31 17:07:19.779  1042  1522 D LGWifiP2pService: DefaultState{ when=-1ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-31 17:07:19.779  1042  1522 D LGWifiP2pService: InactiveState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-31 17:07:19.779  1042  1522 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-31 17:07:19.779  1042  1522 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-31 17:07:19.779  1042  1522 D LGWifiP2pService: InactiveState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-31 17:07:19.779  1956  2323 W WfdsService: DefaultState - msg [9441285] is not handled
08-31 17:07:19.779  1042  1522 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-31 17:07:19.779  1042  1522 D LGWifiP2pService: DefaultState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-31 17:07:19.780  1042  1042 E WifiServerServiceExt: No p2p device connected
08-31 17:07:19.783  1042  2046 I ActivityManager: Killing 7191:com.android.chrome/u0a57 (adj 15): empty #17
08-31 17:07:19.807  8099  8099 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-31 17:07:19.821  1042  2011 W libprocessgroup: failed to open /acct/uid_10057/pid_7191/cgroup.procs: No such file or directory
,08-31 17:07:19.821  6878  6878 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-31 17:07:19.826  6878  6878 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-31 17:07:19.826  1042  1955 I ActivityManager: Killing 7215:com.lge.drmservice/u0a62 (adj 15): empty #17
08-31 17:07:19.854  1042  1728 W libprocessgroup: failed to open /acct/uid_10062/pid_7215/cgroup.procs: No such file or directory
,08-31 17:07:19.887  8099  8099 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-31 17:07:19.893  6878  6878 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-31 17:07:19.897  8078  8122 W FormManager: Network not available. Please check & try again.
,08-31 17:07:19.904  8078  8123 V FormManager: Network unavailable.
08-31 17:07:19.912  8078  8123 V FormManager: Network unavailable.
08-31 17:07:19.914  6878  6878 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-31 17:07:19.937  4304  4304 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
,08-31 17:07:19.937  4304  4304 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-31 17:07:19.940  4304  4304 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-31 17:07:19.943  4304  4304 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-31 17:07:19.949  4304  8124 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-31 17:07:19.954  4304  8125 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
,08-31 17:07:19.955  4304  8125 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-31 17:07:20.002  1042  2341 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=8126 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-31 17:07:20.148  8126  8126 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-31 17:07:20.148  8126  8126 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-31 17:07:20.161  8126  8126 V [BNRBootReceiver]: Boot Receiver Return
,08-31 17:07:20.162  8126  8126 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-31 17:07:20.205  1042  1561 I ActivityManager: Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=8144 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-31 17:07:20.209  1042  1561 I ActivityManager: Killing 7237:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
08-31 17:07:20.298  1042  2027 W libprocessgroup: failed to open /acct/uid_10085/pid_7237/cgroup.procs: No such file or directory
,08-31 17:07:20.314  1042  8104 E WifiMonitor: WifiMonitor:wlan0 cnt=53 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-31 17:07:20.314  1042  8104 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-31 17:07:20.314  1042  8104 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-31 17:07:20.314  8059  8059 E wpa_supplicant: USIM:  scard_init function
08-31 17:07:20.314  1042  8104 E WifiMonitor: WifiMonitor:wlan0 cnt=54 dispatchEvent: WPS-AP-AVAILABLE 
08-31 17:07:20.314  1042  8104 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
,08-31 17:07:20.315  8059  8059 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-31 17:07:20.317  1042  1523 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-31 17:07:20.318  1042  1523 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-31 17:07:20.319  1042  1523 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-31 17:07:20.319  1042  1523 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-31 17:07:20.319  1042  1523 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-31 17:07:20.320  1042  8104 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-31 17:07:20.320  1042  8104 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-31 17:07:20.328  1042  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 55 0 rt=138403  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-31 17:07:20.329  1042  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 55 0 rt=138405  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-31 17:07:20.333  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 17:07:20.333  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 17:07:20.335  1042  1042 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 17:07:20.335  1042  1042 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 17:07:20.336  1042  1042 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-31 17:07:20.340  1042  1042 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 17:07:20.340  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 17:07:20.340  1042  1042 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 17:07:20.340  1042  1042 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
,08-31 17:07:20.345  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 17:07:20.345  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 17:07:20.346  1042  1042 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-31 17:07:20.346  1042  1042 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-31 17:07:20.347  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 17:07:20.369  8144  8144 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-31 17:07:20.393  8144  8144 D PluginManager: init()
,08-31 17:07:20.508  8059  8059 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
08-31 17:07:20.509  1042  8104 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-31 17:07:20.509  1042  8104 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-31 17:07:20.509  1042  8104 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-31 17:07:20.509  1042  8104 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-31 17:07:20.510  1042  8104 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-31 17:07:20.510  1042  8104 E WifiMonitor: WifiMonitor:wlan0 cnt=58 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-31 17:07:20.511  1042  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=138587  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-31 17:07:20.513  1042  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=138588  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-31 17:07:20.514  1042  1523 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=138590
08-31 17:07:20.515  1042  1523 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=138591
08-31 17:07:20.516  1042  1523 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=138592
08-31 17:07:20.518  1042  1523 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=138594
08-31 17:07:20.522  1042  1523 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=138598
,08-31 17:07:20.525  8059  8059 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-31 17:07:20.525  8059  8059 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-31 17:07:20.526  1042  8104 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-31 17:07:20.526  1042  8104 E WifiMonitor: WifiMonitor:wlan0 cnt=59 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-31 17:07:20.526  1042  8104 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-31 17:07:20.526  1042  8104 E WifiMonitor: WifiMonitor:wlan0 cnt=60 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-31 17:07:20.526  1042  8104 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-31 17:07:20.526  1042  8104 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-31 17:07:20.526  1042  8104 E WifiMonitor: WifiMonitor:wlan0 cnt=61 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-31 17:07:20.526  1042  8104 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-31 17:07:20.526  1042  8104 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-31 17:07:20.526  1042  8104 E WifiMonitor: WifiMonitor:wlan0 cnt=62 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-31 17:07:20.529  1042  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=138605  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-31 17:07:20.532  1042  1117 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-31 17:07:20.535  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 17:07:20.535  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 17:07:20.536  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 17:07:20.536  1042  1042 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 17:07:20.536  1042  1042 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 17:07:20.536  1042  1042 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
,08-31 17:07:20.540  1042  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=138615  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-31 17:07:20.540  1042  1042 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 17:07:20.540  1042  1042 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 17:07:20.540  1042  1042 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-31 17:07:20.542  1042  1042 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-31 17:07:20.542  1042  1042 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-31 17:07:20.543  1042  1523 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=138619  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-31 17:07:20.544  1042  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=138620  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-31 17:07:20.544  1042  1523 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=138620
08-31 17:07:20.545  1042  1523 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=138621
08-31 17:07:20.545  1042  1523 D WifiNative-wlan0: doString: [STATUS]
08-31 17:07:20.546  1042  8104 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-31 17:07:20.546  1042  8104 E WifiMonitor: WifiMonitor:wlan0 cnt=63 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-31 17:07:20.546  1042  1523 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-31 17:07:20.548  1042  1523 I WifiServiceExtension: setVHTCapabilityType  : false
,08-31 17:07:20.553  1042  1523 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-31 17:07:20.553  1042  1523 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
08-31 17:07:20.557  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 17:07:20.557  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 17:07:20.558  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-31 17:07:20.561  1042  1042 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 17:07:20.561  1042  1042 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 17:07:20.561  1042  1042 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-31 17:07:20.562  1042  1042 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 17:07:20.562  1042  1042 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 17:07:20.562  1042  1042 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-31 17:07:20.564  1042  1523 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-31 17:07:20.564  1042  1523 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-31 17:07:20.564  1042  1523 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-31 17:07:20.564  1042  1530 D ConnectivityService: Got NetworkAgent Messenger
08-31 17:07:20.564  1042  1530 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-31 17:07:20.564  1042  1530 D ConnectivityService: NetworkAgent connected
08-31 17:07:20.564  1042  1523 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-31 17:07:20.565  1042  1523 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-31 17:07:20.568  1042  1523 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-31 17:07:20.568  1042  1523 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-31 17:07:20.568  1042  1523 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-31 17:07:20.569  1042  1523 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-31 17:07:20.569  1042  1523 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-31 17:07:20.572  1042  1523 D WifiNative-wlan0: SAVE_CONFIG: returned true
,08-31 17:07:20.574   313   893 D CommandListener: Setting iface cfg
08-31 17:07:20.577  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 17:07:20.577  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 17:07:20.577  1042  1523 E WifiStateMachine: Start Dhcp Watchdog 3
08-31 17:07:20.578  1042  8165 D DhcpStateMachine: StoppedState
08-31 17:07:20.578  1042  8165 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-31 17:07:20.578  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 17:07:20.578  1042  8165 D DhcpStateMachine: WaitBeforeStartState
08-31 17:07:20.578  1042  1523 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 62 0 rt=138654  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-31 17:07:20.579  1042  1523 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 62 0 rt=138655  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-31 17:07:20.580  1042  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 62 0 rt=138655  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-31 17:07:20.580  1042  1523 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
08-31 17:07:20.582  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 17:07:20.582  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 17:07:20.582  1042  1523 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
08-31 17:07:20.582  1042  1523 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-31 17:07:20.583  1042  1523 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-31 17:07:20.583  1042  1523 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-31 17:07:20.583  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 17:07:20.583  1042  1523 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-31 17:07:20.584  1042  1042 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-31 17:07:20.584  1042  1042 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-31 17:07:20.585  1042  1042 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-31 17:07:20.585  1042  1042 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
,08-31 17:07:20.586  1042  1523 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=138662  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-31 17:07:20.587  1042  1523 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=138663  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-31 17:07:20.587  1042  1523 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=138663  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-31 17:07:20.588  1042  1523 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:14414] from screen [on:0 period:-517741940] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-31 17:07:20.589  1042  1523 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-517741939] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-31 17:07:20.590  1042  1523 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-31 17:07:20.593  1042  1523 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 17:07:20.593  1042  1523 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 17:07:20.594  1042  1523 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 17:07:20.594  1042  1523 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 17:07:20.594  1042  1523 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 17:07:20.595  1042  1523 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 17:07:20.595  1042  1530 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
08-31 17:07:20.596  1042  1530 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-31 17:07:20.596  1042  1523 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=139,0,0
08-31 17:07:20.596  1042  1523 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=139,0,0
08-31 17:07:20.596  1042  1523 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-31 17:07:20.597  8059  8059 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
,08-31 17:07:20.598  1042  1523 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-31 17:07:20.598  1042  1523 D WifiNative-wlan0: doBoolean: SET ps 0
08-31 17:07:20.598  1042  1523 D WifiNative-wlan0: SET ps 0: returned true
08-31 17:07:20.598  1042  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-31 17:07:20.599  8059  8059 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-31 17:07:20.599  1042  1523 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-31 17:07:20.599  1042  1523 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-31 17:07:20.599  1042  1523 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-31 17:07:20.599  1042  1523 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-31 17:07:20.600   313   893 D CommandListener: Setting iface cfg
08-31 17:07:20.600   313   893 D CommandListener: Trying to bring up wlan0
08-31 17:07:20.601  1042  1522 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@14606f7 target=com.android.internal.util.StateMachine$SmHandler }
08-31 17:07:20.601  1042  1522 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@14606f7 target=com.android.internal.util.StateMachine$SmHandler }
08-31 17:07:20.601  1042  8165 D DhcpStateMachine: WaitBeforeStartState{ when=-1ms what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-31 17:07:20.601  1042  8165 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-31 17:07:20.601  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 17:07:20.602  1042  1523 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-31 17:07:20.603  1042  1042 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-31 17:07:20.603  1042  1042 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-31 17:07:20.604  1042  1523 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK 
08-31 17:07:20.604  1042  1523 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK 
08-31 17:07:20.604  1042  1523 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-31 17:07:20.604  8059  8059 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-31 17:07:20.606  1042  1042 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-31 17:07:20.606  1042  1042 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-31 17:07:20.606  1042  1522 D LGWifiP2pService: InactiveState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-31 17:07:20.606  1042  1522 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-31 17:07:20.606  1042  1523 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-31 17:07:20.606  1042  1523 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-31 17:07:20.606  8059  8059 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-31 17:07:20.607  1042  1523 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-31 17:07:20.607  1042  1523 D WifiNative-wlan0: doBoolean: SET ps 1
08-31 17:07:20.623  1042  1523 D WifiNative-wlan0: SET ps 1: returned true
,08-31 17:07:20.624  1042  1530 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-31 17:07:20.624  1042  1523 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-31 17:07:20.624  1042  1523 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-31 17:07:20.625  1042  1523 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-31 17:07:20.625  1042  1523 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-31 17:07:20.625  1042  1523 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-31 17:07:20.626  1042  1523 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-31 17:07:20.628  1042  1530 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-31 17:07:20.629  1042  1523 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-31 17:07:20.629  1042  1523 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-31 17:07:20.629  1042  1523 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-31 17:07:20.630  1042  1530 D ConnectivityService: ignoring duplicate network state non-change
08-31 17:07:20.631  1042  1530 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-31 17:07:20.632  1042  1530 D ConnectivityService: Adding iface wlan0 to network 102
08-31 17:07:20.633  1042  1523 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-31 17:07:20.661  1042  1530 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-31 17:07:20.661  1042  1530 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
08-31 17:07:20.663  1042  1530 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,08-31 17:07:20.664   313   893 E Netd    : netlink response contains error (File exists)
08-31 17:07:20.665  1042  1530 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
08-31 17:07:20.666  1042  1530 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-31 17:07:20.666  1042  1530 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 102
08-31 17:07:20.666  1042  1530 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
08-31 17:07:20.667  1042  1530 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-31 17:07:20.667  1042  1530 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-31 17:07:20.667  1042  1530 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-31 17:07:20.667  1042  1530 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-31 17:07:20.667  1042  1530 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-31 17:07:20.667  1042  1530 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 17:07:20.667  1042  8164 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-31 17:07:20.667  1042  8164 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-31 17:07:20.667  1042  1530 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-31 17:07:20.667  1042  1530 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 17:07:20.667  1042  8164 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-31 17:07:20.667  1042  1530 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-31 17:07:20.668  1042  1530 D ConnectivityService: currentScore = 0, newScore = 20
08-31 17:07:20.668  1042  1530 D ConnectivityService:    accepting network in place of null
08-31 17:07:20.668  1042  1530 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 17:07:20.668  1042  8164 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-31 17:07:20.670  1042  1530 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-31 17:07:20.670  1042  1530 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
08-31 17:07:20.670  1866  1866 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 17:07:20.670  1042  1530 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-31 17:07:20.670  18,66  1866 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-31 17:07:20.671  1042  1523 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 17:07:20.671  1042  1523 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-31 17:07:20.672   313  8175 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-31 17:07:20.673  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 17:07:20.673  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 17:07:20.674  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-31 17:07:20.680  6694  6804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 17:07:20.680  6694  6804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 17:07:20.680  6694  6804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 17:07:20.680  6694  6804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 17:07:20.680  6694  6804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 17:07:20.680  6694  6804 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 17:07:20.680  6694  6804 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 17:07:20.680  6694  6804 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 17:07:20.683  1042  1042 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 17:07:20.683  1042  1042 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 17:07:20.683  1042  1042 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-31 17:07:20.683  6694  6804 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 17:07:20.685  1042  1042 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 17:07:20.685  1042  1042 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 17:07:20.685  1042  1042 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-31 17:07:20.685  1042  1042 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-31 17:07:20.687  6694  6804 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
08-31 17:07:20.687  1956  1956 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-31 17:07:20.687  6694  6804 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-31 17:07:20.688  1042  1042 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-31 17:07:20.688  1042  1042 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 17:07:20.688  1042  1042 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-31 17:07:20.688  1042  1042 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-31 17:07:20.689  6694  6804 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@24075d78 Bundle[{}]
08-31 17:07:20.690  6694  6804 I io.jxcore.node.LifeCycleMonitor: start: OK
08-31 17:07:20.690  6694  6804 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-31 17:07:20.691  6694  6804 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-31 17:07:20.691  1042  1042 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 17:07:20.691  1042  1042 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 17:07:20.691  1042  1042 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-31 17:07:20.692  6694  6804 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-31 17:07:20.693  6694  6804 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-31 17:07:20.694  6694  6804 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-31 17:07:20.695  1042  1530 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-31 17:07:20.695  1042  1530 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-31 17:07:20.695  1042  1042 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-31 17:07:20.695  1042  1530 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-31 17:07:20.695  1042  1042 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-31 17:07:20.696  1042  1042 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-31 17:07:20.696  1042  1042 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-31 17:07:20.698  1042  1530 D ConnectivityService: validation of new default Network = false
08-31 17:07:20.698  1042  1530 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-31 17:07:20.698  1042  1530 D DSQN    : enableDataServiceNotify 
08-31 17:07:20.698  1042  1530 D DSQN    : start dsqn bin
08-31 17:07:20.700  6694  6804 I System.out: Running OutgoingSocketThread
,08-31 17:07:20.702  6694  8176 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 846)
08-31 17:07:20.703  6694  8176 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 44278
08-31 17:07:20.703  6694  8176 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
08-31 17:07:20.694  8177  8177 W dsqn    : type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 17:07:20.694  8177  8177 W dsqn    : type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 17:07:20.709  1042  1530 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-31 17:07:20.709  1042  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 17:07:20.709  1042  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 17:07:20.709  1042  1530 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 17:07:20.710  1589  1799 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-31 17:07:20.711  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 17:07:20.711  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-31 17:07:20.711  1042  1521 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
08-31 17:07:20.721  8177  8177 E DSQN    : DSQN ssw
08-31 17:07:20.723  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 17:07:20.724  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-31 17:07:20.724  1589  1589 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-31 17:07:20.725  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 17:07:20.726   313  8175 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-31 17:07:20.726  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 17:07:20.726  1589  1589 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-31 17:07:20.726  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-31 17:07:20.740  1589  1589 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-31 17:07:20.741  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-31 17:07:20.741  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 17:07:20.767   313  8175 D libc-netbsd: res_queryN name = clients3.google.com succeed
,08-31 17:07:20.799   313   892 D LGDataListener: argv[0]=dsqncommand
08-31 17:07:20.799   313   892 D LGDataListener: argv[1]=wlan0
,08-31 17:07:20.799   313   892 D LGDataListener: argv[2]=1
08-31 17:07:20.799   313   892 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-31 17:07:20.800  1042  1115 D DSQN    : DSQM DsqnNotification wlan0  1
08-31 17:07:20.800  1042  1115 D DSQN    : start to monitor internet connection
08-31 17:07:20.804  1042  8165 D DhcpStateMachine: DHCPV4 request on wlan0
08-31 17:07:20.804  1042  8165 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-31 17:07:20.804  1042  8165 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-31 17:07:20.794  8183  8183 W dhcpcd  : type=1400 audit(0.0:193): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 17:07:20.794  8183  8183 W dhcpcd  : type=1400 audit(0.0:194): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 17:07:20.814  8183  8183 I dhcpcd  : version 5.5.6 starting
08-31 17:07:20.816  8183  8183 E dhcpcd  : get_duid: m
08-31 17:07:20.816  8183  8183 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-31 17:07:20.816  8183  8183 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,08-31 17:07:20.832  1042  8164 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 31 Aug 2016 15:07:20 GMT], X-Android-Received-Millis=[1472656040831], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472656040798]},
,08-31 17:07:20.832  1042  8164 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-31 17:07:20.833  1042  8164 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-31 17:07:20.834  1042  1530 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
08-31 17:07:20.834  1042  1530 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-31 17:07:20.834  1042  1530 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-31 17:07:20.834  1042  1530 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 17:07:20.834  1042  1530 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-31 17:07:20.834  1042  1530 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
08-31 17:07:20.835  1042  1530 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-31 17:07:20.835  1042  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 17:07:20.835  1042  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 17:07:20.836  1042  1530 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 17:07:20.837  1042  1530 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 17:07:20.837  1589  1799 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-31 17:07:20.838  1042  1523 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 17:07:20.838  1042  1523 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-31 17:07:20.839  1866  1866 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 17:07:20.840  1042  1530 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-31 17:07:20.840  1866  1866 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
,08-31 17:07:20.860  1589  1589 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-31 17:07:20.861  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 17:07:20.862  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 17:07:20.885  8183  8183 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-31 17:07:20.885  8183  8183 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-31 17:07:20.885  8183  8183 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,08-31 17:07:20.885  8183  8183 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
,08-31 17:07:20.886  8183  8183 D dhcpcd  : wlan0: sending REQUEST (xid 0xe2a07b0a), next in 3.79 seconds
08-31 17:07:20.914  8144  8144 W ExternalStrings: load override strings
08-31 17:07:20.914  8144  8144 W ExternalStrings: java.lang.RuntimeException: Unexpected tag, got eat-comment
08-31 17:07:20.914  8144  8144 W ExternalStrings: 	at com.mcafee.plugin.af.a(Unknown Source)
08-31 17:07:20.914  8144  8144 W ExternalStrings: 	at com.mcafee.plugin.ac.b(Unknown Source)
08-31 17:07:20.914  8144  8144 W ExternalStrings: 	at com.mcafee.plugin.ak.d(Unknown Source)
08-31 17:07:20.914  8144  8144 W ExternalStrings: 	at com.mcafee.plugin.ak.a(Unknown Source)
08-31 17:07:20.914  8144  8144 W ExternalStrings: 	at com.mcafee.app.s.getClassLoader(Unknown Source)
08-31 17:07:20.914  8144  8144 W ExternalStrings: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
08-31 17:07:20.914  8144  8144 W ExternalStrings: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-31 17:07:20.914  8144  8144 W ExternalStrings: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-31 17:07:20.914  8144  8144 W ExternalStrings: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-31 17:07:20.914  8144  8144 W ExternalStrings: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-31 17:07:20.914  8144  8144 W ExternalStrings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 17:07:20.914  8144  8144 W ExternalStrings: 	at android.os.Looper.loop(Looper.java:135)
08-31 17:07:20.914  8144  8144 W ExternalStrings: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-31 17:07:20.914  8144  8144 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 17:07:20.914  8144  8144 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 17:07:20.914  8144  8144 W ExternalStrings: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-31 17:07:20.914  8144  8144 W ExternalStrings: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-31 17:07:20.915  8144  8144 D StatusProvider: onCreate
,08-31 17:07:20.926  8183  8183 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
08-31 17:07:20.958  8183  8183 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
08-31 17:07:20.958  8183  8183 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
08-31 17:07:20.959  8183  8183 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-31 17:07:20.960  8183  8183 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-31 17:07:20.960  8183  8183 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-31 17:07:20.961  8183  8183 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-31 17:07:20.961  8183  8183 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
,08-31 17:07:20.961  8183  8183 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-31 17:07:20.991  8144  8144 V Signer  : override build config not found
08-31 17:07:20.991  8144  8144 D Signer  : value of property debug is false
,08-31 17:07:21.029  8144  8144 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
,08-31 17:07:21.029  8144  8144 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
,08-31 17:07:21.029  8144  8144 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
08-31 17:07:21.030  8144  8144 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
08-31 17:07:21.030  8144  8144 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
08-31 17:07:21.030  8144  8144 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
08-31 17:07:21.030  8144  8144 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
08-31 17:07:21.031  8144  8144 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
08-31 17:07:21.031  8144  8144 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
08-31 17:07:21.031  8144  8144 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
08-31 17:07:21.031  8144  8144 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
08-31 17:07:21.031  8144  8144 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
08-31 17:07:21.032  8144  8144 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
,08-31 17:07:21.041  8144  8144 V LGMDMManager: Create singleton instance
08-31 17:07:21.085  8144  8144 D LGMDMWrapper: LG MDM library v4.0.0 is available on this device.
,08-31 17:07:21.151  8144  8144 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-31 17:07:21.159  8144  8211 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-31 17:07:21.161  6878  6878 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 17:07:21.168  6878  6878 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 17:07:21.207  1042  8165 D DhcpStateMachine: DHCPV4 succeeded on wlan0
08-31 17:07:21.207  1042  8165 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-31 17:07:21.207  1042  8165 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
,08-31 17:07:21.208  1042  8165 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
08-31 17:07:21.208  1042  8165 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-31 17:07:21.208  1042  8165 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-31 17:07:21.208  1042  8165 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-31 17:07:21.208  1042  8165 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-31 17:07:21.208  1042  8165 D DhcpStateMachine: RunningState
08-31 17:07:21.219  1042  1954 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=8218 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
08-31 17:07:21.220  1042  1954 I ActivityManager: Killing 7298:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
,08-31 17:07:21.318  8144  8210 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-31 17:07:21.473  1042  2342 W libprocessgroup: failed to open /acct/uid_10093/pid_7298/cgroup.procs: No such file or directory
,08-31 17:07:21.516  8218  8218 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-31 17:07:21.545  8218  8218 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,08-31 17:07:21.578  8218  8218 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,08-31 17:07:21.579  8218  8218 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-31 17:07:21.579  8218  8218 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-31 17:07:21.579  8218  8218 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-31 17:07:21.580  8218  8218 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-31 17:07:21.581  8218  8218 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-31 17:07:21.587  8218  8218 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-31 17:07:21.593  8218  8218 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 17:07:21.600  8218  8218 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-31 17:07:21.620  8218  8218 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-31 17:07:21.624  6878  6878 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
08-31 17:07:21.626  8218  8218 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-31 17:07:21.627  6878  6878 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-31 17:07:21.627  8144  8210 D LgDataFeature: LgDataFeature() Constructor: none
08-31 17:07:21.628  8144  8210 D LgDataFeature: LgDataFeature() Constructor Done, null
08-31 17:07:21.629  8218  8218 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-31 17:07:21.630  8144  8144 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 17:07:21.630  8144  8211 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-31 17:07:21.639  6878  6878 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-31 17:07:21.644  6878  6878 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-31 17:07:21.650  8218  8218 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 17:07:21.651  8218  8218 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 17:07:21.652  8218  8218 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-31 17:07:21.654  8144  8144 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 17:07:21.654  8144  8211 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-31 17:07:21.660  6878  6878 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 17:07:21.664  6878  6878 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 17:07:21.671  8218  8218 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 17:07:21.671  8218  8218 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 17:07:21.671  8218  8218 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-31 17:07:21.673  6878  6878 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-31 17:07:21.674  6878  6878 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-31 17:07:21.674  6878  6878 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-31 17:07:21.674  6878  6878 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-31 17:07:21.674  6878  6878 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-31 17:07:21.675  6878  6878 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-31 17:07:21.675  6878  6878 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-31 17:07:21.675  6878  6878 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-31 17:07:21.675  6878  6878 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-31 17:07:21.675  6878  6878 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-31 17:07:21.676  6878  6878 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-31 17:07:21.676  6878  6878 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-31 17:07:21.678  8144  8144 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-31 17:07:21.678  8144  8211 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-31 17:07:21.691  6878  6878 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 17:07:21.698  6878  6878 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 17:07:21.701  6694  6804 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 847)
08-31 17:07:21.701  6694  6804 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 847)
08-31 17:07:21.705  6694  6804 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 852)
08-31 17:07:21.705  8218  8218 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 17:07:21.706  8218  8218 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-31 17:07:21.706  6694  6804 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-31 17:07:21.706  6694  6804 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 853)
08-31 17:07:21.706  8218  8218 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-31 17:07:21.710  8144  8144 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 17:07:21.710  6694  6804 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 17:07:21.710  6694  6804 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19b446a7 added. We now have 2 listener(s)
08-31 17:07:21.710  8144  8211 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-31 17:07:21.713  1042  2342 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 17:07:21.715  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-31 17:07:21.715  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 17:07:21.715  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 17:07:21.715  6694  6804 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 17:07:21.715  6694  6804 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b732754 added. We now have 9 listener(s)
08-31 17:07:21.715  6694  6804 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 17:07:21.716  6694  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-31 17:07:21.717  6878  6878 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-31 17:07:21.718  6694  6804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 17:07:21.723  6694  6804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 17:07:21.723  6694  6804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 17:07:21.723  6694  6804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 17:07:21.723  6694  6804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 17:07:21.723  6694  6804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 17:07:21.723  6694  6804 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 17:07:21.723  6694  6804 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 17:07:21.723  6694  6804 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 17:07:21.725  6694  6804 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 17:07:21.725  6694  6804 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 17:07:21.725  6694  6804 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 17:07:21.725  6694  6804 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36e7bff2 added. We now have 3 listener(s)
08-31 17:07:21.725  1042  2341 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 17:07:21.726  6878  6878 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 17:07:21.728  6694  6694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 17:07:21.728  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-31 17:07:21.728  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 17:07:21.728  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 17:07:21.728  6694  6804 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 17:07:21.728  6694  6804 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2454a643 added. We now have 10 listener(s)
08-31 17:07:21.729  6694  6804 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 17:07:21.729  6694  6804 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 17:07:21.729  6694  6804 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 17:07:21.729  6694  6804 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 17:07:21.729  6694  6804 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 17:07:21.729  6694  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:07:21.729  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 17:07:21.729  6694  6804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 17:07:21.729  6694  6804 V org.thaliproject.p2p.btconnectorlib.Connecti,onManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19b446a7 removed from the list
08-31 17:07:21.729  6694  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:07:21.729  6694  6804 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b732754 removed from the list
08-31 17:07:21.730  6694  6694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 17:07:21.730  6694  6804 D io.jxcore.node.ConnectivityMonitor: stop
08-31 17:07:21.730  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 17:07:21.732  6694  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:07:21.732  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:07:21.733  6694  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 17:07:21.733  6694  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 17:07:21.733  6694  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:07:21.733  6694  6804 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b732754 not in the list
08-31 17:07:21.733  6694  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:07:21.733  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:07:21.734  6694  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 17:07:21.734  6694  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 17:07:21.734  6694  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:07:21.734  6694  6804 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2454a643 removed from the list
08-31 17:07:21.734  6694  6804 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 17:07:21.734  6694  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:07:21.734  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:07:21.734  6694  6804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 17:07:21.734  6694  6804 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36e7bff2 removed from the list
08-31 17:07:21.735  6694  6804 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 17:07:21.735  6694  6804 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d8564c0 added. We now have 2 listener(s)
08-31 17:07:21.736  1042  1955 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 17:07:21.737  8218  8218 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 17:07:21.737  8218  8218 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 17:07:21.737  8218  8218 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-31 17:07:21.740  8144  8144 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 17:07:21.740  8144  8211 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-31 17:07:21.740  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-31 17:07:21.740  6694  6804 D org.thaliproject.p2p.btconnectorlib.interna,l.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 17:07:21.740  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 17:07:21.740  6694  6804 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 17:07:21.740  6694  6804 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22fe95f9 added. We now have 9 listener(s)
08-31 17:07:21.740  6694  6804 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 17:07:21.741  6694  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-31 17:07:21.743  6694  6804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 17:07:21.747  6878  6878 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-31 17:07:21.749  6694  6804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 17:07:21.749  6694  6804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 17:07:21.749  6694  6804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 17:07:21.749  6694  6804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 17:07:21.749  6694  6804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 17:07:21.749  6694  6804 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 17:07:21.749  6694  6804 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 17:07:21.749  6694  6804 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 17:07:21.752  6694  6804 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 17:07:21.752  6694  6804 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 17:07:21.752  6694  6804 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 17:07:21.752  6694  6804 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2e11639f added. We now have 3 listener(s)
08-31 17:07:21.752  1042  2027 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 17:07:21.754  6694  6694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 17:07:21.755  6878  6878 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 17:07:21.755  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-31 17:07:21.755  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 17:07:21.755  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 17:07:21.755  6694  6804 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 17:07:21.755  6694  6804 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15bc0cec added. We now have 10 listener(s)
08-31 17:07:21.755  6694  6804 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 17:07:21.755  6694  6804 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 17:07:21.756  6694  6804 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-31 17:07:21.756  6694  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-31 17:07:21.756  6694  6804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 17:07:21.756  6694  6804 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-31 17:07:21.757  6694  6694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 17:07:21.759  6694  6804 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-31 17:07:21.759  1042  2027 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 17:07:21.760  8218  8218 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 17:07:21.760  8218  8218 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 17:07:21.760  8218  8218 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-31 17:07:21.763  8144  8144 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 17:07:21.763  8144  8211 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-31 17:07:21.767  6694  6804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-31 17:07:21.767  6694  6804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-31 17:07:21.769  6694  6804 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-31 17:07:21.769  6878  6878 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-31 17:07:21.769  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-31 17:07:21.771  6694  6804 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,08-31 17:07:21.772  6694  6804 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 17:07:21.772  6694  6804 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 17:07:21.774  6694  6804 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 17:07:21.774  6694  6804 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 17:07:21.774  6694  6804 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 17:07:21.774  6694  6804 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 17:07:21.774  6694  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:07:21.774  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 17:07:21.774  6694  6804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 17:07:21.774  6694  6804 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d8564c0 removed from the list
08-31 17:07:21.774  6694  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:07:21.774  6694  6804 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22fe95f9 removed from the list
08-31 17:07:21.774  6694  6804 D io.jxcore.node.ConnectivityMonitor: stop
08-31 17:07:21.774  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:07:21.775  6694  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:07:21.775  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:07:21.775  6878  6878 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 17:07:21.777  6694  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 17:07:21.777  6694  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 17:07:21.777  6694  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:07:21.777  6694  6804 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22fe95f9 not in the list
08-31 17:07:21.777  6694  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:07:21.777  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:07:21.778  6694  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 17:07:21.778  6694  6804 D BluetoothLeScanner: could not find callback wrapper
08-31 17:07:21.778  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 17:07:21.778  6694  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 17:07:21.778  6694  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:07:21.778  6694  6804 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject,.p2p.btconnectorlib.DiscoveryManager@15bc0cec removed from the list
08-31 17:07:21.778  6694  6804 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 17:07:21.779  6694  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:07:21.779  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:07:21.779  6694  6804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 17:07:21.779  6694  6804 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2e11639f removed from the list
08-31 17:07:21.779  6694  6804 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 17:07:21.779  6694  6804 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2db29abb added. We now have 2 listener(s)
08-31 17:07:21.782  8218  8218 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 17:07:21.782  8218  8218 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 17:07:21.782  1042  2027 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 17:07:21.782  8218  8218 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-31 17:07:21.785  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-31 17:07:21.785  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 17:07:21.785  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 17:07:21.785  6694  6804 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 17:07:21.785  6694  6804 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7d30bd8 added. We now have 9 listener(s)
08-31 17:07:21.785  6694  6804 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 17:07:21.785  6694  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-31 17:07:21.787  6694  6804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 17:07:21.791  6694  6804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 17:07:21.791  6694  6804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 17:07:21.791  6694  6804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 17:07:21.791  6694  6804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 17:07:21.791  6694  6804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 17:07:21.791  6694  6804 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 17:07:21.791  6694  6804 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 17:07:21.791  6694  6804 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 17:07:21.792  8144  8210 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
08-31 17:07:21.793  6694  6804 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 17:07:21.793  6694  6804 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-31 17:07:21.793  6694  6804 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 17:07:21.793  6694  6804 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d3be216 added. We now have 3 listener(s)
08-31 17:07:21.794  1042  1561 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 17:07:21.794  8144  8211 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-31 17:07:21.795  6694  6694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 17:07:21.796  8144  8144 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 17:07:21.796  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-31 17:07:21.797  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 17:07:21.797  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 17:07:21.797  6694  6804 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 17:07:21.797  6694  6804 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34662797 added. We now have 10 listener(s)
08-31 17:07:21.797  6694  6804 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 17:07:21.797  6694  6804 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 17:07:21.799  6694  6804 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 17:07:21.799  6694  6804 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-31 17:07:21.799  6694  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-31 17:07:21.799  6694  6804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 17:07:21.799  6694  6804 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-31 17:07:21.801  6694  6694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 17:07:21.801  6694  6804 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-31 17:07:21.802  1042  2046 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-31 17:07:21.805  6694  6804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-31 17:07:21.806  6694  6804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-31 17:07:21.807  6694  6804 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-31 17:07:21.808  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 17:07:21.809  6694  6804 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-31 17:07:21.809  6694  6804 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 17:07:21.810  6694  6804 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 17:07:21.810  6694  6804 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 17:07:21.810  6694  6804 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 17:07:21.810  6694  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:07:21.810  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 17:07:21.810  6694  6804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 17:07:21.810  6694  6804 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2db29abb removed from the list
08-31 17:07:21.810  6694  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:07:21.810  6694  6804 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7d30bd8 removed from the list
08-31 17:07:21.810  6694  6804 D io.jxcore.node.ConnectivityMonitor: stop
08-31 17:07:21.810  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:07:21.810  6694  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:07:21.810  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:07:21.811  6694  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 17:07:21.811  6694  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 17:07:21.811  6694  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:07:21.811  6694  6804 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7d30bd8 not in the list
08-31 17:07:21.811  6694  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:07:21.811  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:07:21.812  6694  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 17:07:21.812  6694  6804 D BluetoothLeScanner: could not find callback wrapper
08-31 17:07:21.812  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 17:07:21.813  6694  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 17:07:21.813  8144  8210 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-,1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
08-31 17:07:21.813  6694  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:07:21.813  6694  6804 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34662797 removed from the list
08-31 17:07:21.813  6694  6804 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 17:07:21.813  6694  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:07:21.813  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:07:21.813  6694  6804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 17:07:21.813  6694  6804 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d3be216 removed from the list
08-31 17:07:21.813  6694  6804 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 17:07:21.814  6694  6804 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d0c09a2 added. We now have 2 listener(s)
,08-31 17:07:21.816  1042  1726 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 17:07:21.819  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-31 17:07:21.819  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 17:07:21.819  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 17:07:21.819  6694  6804 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 17:07:21.819  6694  6804 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e5ba633 added. We now have 9 listener(s)
08-31 17:07:21.819  6694  6804 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 17:07:21.819  6694  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-31 17:07:21.821  6878  6878 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-31 17:07:21.823  6694  6804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 17:07:21.824  8144  8210 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
08-31 17:07:21.825  8144  8210 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-31 17:07:21.826  6694  6804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 17:07:21.826  6694  6804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 17:07:21.826  6694  6804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 17:07:21.826  6694  6804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 17:07:21.826  6694  6804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 17:07:21.826  6694  6804 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 17:07:21.826  6694  6804 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 17:07:21.826  6694  6804 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 17:07:21.826  8144  8210 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
,08-31 17:07:21.827  6878  6878 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 17:07:21.827  6694  6804 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 17:07:21.827  6694  6804 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 17:07:21.828  6694  6804 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 17:07:21.829  6694  6804 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2bb3ef69 added. We now have 3 listener(s)
08-31 17:07:21.830  6694  6694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 17:07:21.830  8144  8210 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
08-31 17:07:21.830  8144  8210 I SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
08-31 17:07:21.831  1042  1728 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 17:07:21.833  6694  6694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 17:07:21.833  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-31 17:07:21.833  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 17:07:21.834  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 17:07:21.834  6694  6804 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 17:07:21.834  6694  6804 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c51dee added. We now have 10 listener(s)
08-31 17:07:21.834  6694  6804 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 17:07:21.834  6694  6804 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 17:07:21.834  6694  6804 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-31 17:07:21.834  6694  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-31 17:07:21.834  6694  6804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 17:07:21.834  6694  6804 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-31 17:07:21.835  8218  8218 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 17:07:21.835  8218  8218 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 17:07:21.836  6694  6804 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-31 17:07:21.837  1042  1983 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 17:07:21.838  8144  8210 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown, Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
,08-31 17:07:21.839  8144  8210 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
08-31 17:07:21.840  6694  6804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-31 17:07:21.841  6694  6804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-31 17:07:21.843  6694  6804 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-31 17:07:21.843  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 17:07:21.844  6694  6804 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-31 17:07:21.846  6694  6804 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 17:07:21.846  6694  6804 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 17:07:21.846  6694  6804 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 17:07:21.846  6694  6804 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 17:07:21.846  6694  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:07:21.846  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 17:07:21.846  6694  6804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 17:07:21.846  6694  6804 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d0c09a2 removed from the list
08-31 17:07:21.846  6694  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:07:21.846  8218  8218 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-31 17:07:21.846  6694  6804 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e5ba633 removed from the list
08-31 17:07:21.846  6694  6804 D io.jxcore.node.ConnectivityMonitor: stop
08-31 17:07:21.846  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:07:21.848  6694  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:07:21.849  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:07:21.849  6694  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 17:07:21.849  6694  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 17:07:21.849  6694  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:07:21.849  6694  6804 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e5ba633 not in the list
08-31 17:07:21.849  6694  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:07:21.849  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:07:21.849  8144  8144 D Postpon,albeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 17:07:21.850  8144  8211 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-31 17:07:21.850  6694  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-31 17:07:21.851  6694  6804 D BluetoothLeScanner: could not find callback wrapper
08-31 17:07:21.851  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 17:07:21.851  6694  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 17:07:21.851  6694  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:07:21.851  6694  6804 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c51dee removed from the list
08-31 17:07:21.851  6694  6804 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 17:07:21.851  6694  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:07:21.851  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:07:21.851  6694  6804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 17:07:21.851  6694  6804 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2bb3ef69 removed from the list
08-31 17:07:21.852  6694  6804 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 17:07:21.852  6694  6804 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b931925 added. We now have 2 listener(s)
08-31 17:07:21.854  1042  1918 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 17:07:21.857  6878  6878 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-31 17:07:21.859  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-31 17:07:21.859  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-31 17:07:21.859  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 17:07:21.859  6694  6804 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 17:07:21.859  6694  6804 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e92afa added. We now have 9 listener(s)
08-31 17:07:21.859  6694  6804 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 17:07:21.860  6694  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-31 17:07:21.863  6694  6804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 17:07:21.866  6878  6878 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 17:07:21.868  6694  6804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 17:07:21.868  6694  6804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 17:07:21.868  6694  6804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 17:07:21.868  6694  6804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 17:07:21.868  6694  6804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 17:07:21.868  6694  6804 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 17:07:21.868  6694  6804 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 17:07:21.868  6694  6804 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 17:07:21.871  6694  6804 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 17:07:21.871  6694  6804 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 17:07:21.871  6694  6804 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 17:07:21.871  6694  6804 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@138d1b08 added. We now have 3 listener(s)
08-31 17:07:21.874  6694  6694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 17:07:21.874  1042  1762 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-31 17:07:21.876  6694  6694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 17:07:21.876  8218  8218 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 17:07:21.876  8218  8218 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 17:07:21.877  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-31 17:07:21.877  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 17:07:21.877  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 17:07:21.877  6694  6804 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 17:07:21.877  6694  6804 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18122a1 added. We now have 10 listener(s)
08-31 17:07:21.877  8218  8218 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-31 17:07:21.877  6694  6804 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 17:07:21.878  6694  6804 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 17:07:21.878  6694  6804 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 17:07:21.878  6694  6804 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 17:07:21.878  6694  6804 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 17:07:21.878  6694  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:07:21.879  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 17:07:21.879  6694  6804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 17:07:21.879  6694  6804 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b931925 removed from the list
08-31 17:07:21.879  6694  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:07:21.879  6694  6804 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e92afa removed from the list
08-31 17:07:21.879  6694  6804 D io.jxcore.node.ConnectivityMonitor: stop
08-31 17:07:21.879  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:07:21.881  8144  8144 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 17:07:21.882  6694  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:07:21.882  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:07:21.881  8144  8211 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:81,8 
08-31 17:07:21.882  6694  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 17:07:21.882  6694  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 17:07:21.882  6694  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:07:21.882  6694  6804 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e92afa not in the list
08-31 17:07:21.882  6694  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:07:21.882  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:07:21.883  6694  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 17:07:21.883  6694  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 17:07:21.883  6694  6804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 17:07:21.883  6694  6804 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18122a1 removed from the list
08-31 17:07:21.883  6694  6804 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 17:07:21.883  6694  6804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 17:07:21.883  6694  6804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 17:07:21.883  6694  6804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 17:07:21.883  6694  6804 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@138d1b08 removed from the list
08-31 17:07:21.884  8099  8099 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-31 17:07:21.884  6694  6804 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-31 17:07:21.884  6694  6804 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-31 17:07:21.884  6694  6804 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-31 17:07:21.885  6694  6804 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 17:07:21.885  6694  6804 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
,08-31 17:07:21.885  6694  6804 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-31 17:07:21.889  8099  8099 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,08-31 17:07:21.892  6878  6878 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-31 17:07:21.897  6694  8264 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 860, name: My test thread name)
08-31 17:07:21.898  6694  8264 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 860, thread name: My test thread name)
08-31 17:07:21.898  6694  8264 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 860, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-31 17:07:21.902  6878  6878 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 17:07:21.902  6694  8265 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 862, name: My test thread name)
08-31 17:07:21.902  6694  8265 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 862, thread name: My test thread name)
08-31 17:07:21.902  6694  8265 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 862, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-31 17:07:21.904  6694  6804 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-31 17:07:21.904  6694  6804 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-31 17:07:21.904  6694  6804 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-31 17:07:21.905  6694  6804 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-31 17:07:21.905  6694  6804 D com.test.thalitest.ThaliTestRunner: Total duration: 23867 ms
08-31 17:07:21.907  6694  6804 I jxcore-log: *Native tests were executed*
08-31 17:07:21.907  6694  6804 I jxcore-log: 
08-31 17:07:21.907  6694  6804 I jxcore-log: Total number of executed tests:  80
08-31 17:07:21.907  6694  6804 I jxcore-log: 
08-31 17:07:21.907  6694  6804 I jxcore-log: Number of passed tests:  80
08-31 17:07:21.907  6694  6804 I jxcore-log: 
08-31 17:07:21.907  6694  6804 I jxcore-log: Number of failed tests:  0
08-31 17:07:21.907  6694  6804 I jxcore-log: 
08-31 17:07:21.907  8218  8218 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 17:07:21.908  6694  6804 I jxcore-log: Number of ignored tests:  0
08-31 17:07:21.908  6694  6804 I jxcore-log: 
08-31 17:07:21.908  8218  8218 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 17:07:21.908  6694  6804 I jxcore-log: Total duration:  23867
08-31 17:07:21.908  6694  6804 I jxcore-log: 
08-31 17:07:21.908  6694  6804 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-31 17:07:21.908  6694  6804 I jxcore-log: 
08-31 17:07:21.909  8218  8218 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-31 17:07:21.910  8218  8218 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-31 17:07:21.910  8218  8218 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-31 17:07:21.913  8144  8144 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 17:07:21.914  8144  8211 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-31 17:07:21.914  6694  6804 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 17:07:21.914  6694  6804 I jxcore-log: 
08-31 17:07:21.918  6694  6804 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 17:07:21.918  6694  6804 I jxcore-log: 
08-31 17:07:21.919  8099  8099 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-31 17:07:21.919  8099  8099 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,08-31 17:07:21.920  6694  6804 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 17:07:21.920  6694  6804 I jxcore-log: 
08-31 17:07:21.920  6694  6694 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-31 17:07:21.921  6694  6804 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 17:07:21.921  6694  6804 I jxcore-log: 
08-31 17:07:21.922  6878  6878 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-31 17:07:21.922  6694  6804 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 17:07:21.922  6694  6804 I jxcore-log: 
08-31 17:07:21.924  6694  6804 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 17:07:21.924  6694  6804 I jxcore-log: 
08-31 17:07:21.925  6878  6878 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 17:07:21.927  6694  6804 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 17:07:21.927  6694  6804 I jxcore-log: 
08-31 17:07:21.930  8218  8218 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 17:07:21.931  8218  8218 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 17:07:21.931  8218  8218 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-31 17:07:21.932  8218  8218 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-31 17:07:21.932  8218  8218 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-31 17:07:21.933  6694  6804 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-31 17:07:21.933  6694  6804 I jxcore-log: 
08-31 17:07:21.934  6694  6804 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-31 17:07:21.934  6694  6804 I jxcore-log: 
08-31 17:07:21.935  6694  6804 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 17:07:21.935  6694  6804 I jxcore-log: 
08-31 17:07:21.935  8144  8144 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-31 17:07:21.936  6694  6804 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 17:07:21.936  6694  6804 I jxcore-log: 
08-31 17:07:21.937  6694  6804 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-31 17:07:21.937  6694  6804 I jxcore-log: 
08-31 17:07:21.939  6694  6804 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-31 17:07:21.939  6694  6804 I jxcore-log: 
08-31 17:07:21.939  6694  6804 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-31 17:07:21.939  6694  6804 I jxcore-log: 
08-31 17:07:21.940  6694  6804 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":",notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 17:07:21.940  6694  6804 I jxcore-log: 
,08-31 17:07:21.941  6694  6804 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 17:07:21.941  6694  6804 I jxcore-log: 
08-31 17:07:21.942  6694  6804 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-31 17:07:21.942  6694  6804 I jxcore-log: 
08-31 17:07:21.943  6694  6804 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-31 17:07:21.943  6694  6804 I jxcore-log: 
08-31 17:07:21.943  6694  6804 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 17:07:21.943  6694  6804 I jxcore-log: 
08-31 17:07:21.943  8218  8218 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-31 17:07:21.944  8218  8218 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-31 17:07:21.944  6694  6804 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 17:07:21.944  6694  6804 I jxcore-log: 
08-31 17:07:21.944  8218  8218 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
08-31 17:07:21.945  6694  6804 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-31 17:07:21.945  6694  6804 I jxcore-log: 
08-31 17:07:21.946  6694  6804 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-31 17:07:21.946  6694  6804 I jxcore-log: 
08-31 17:07:21.946  6694  6804 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-31 17:07:21.946  6694  6804 I jxcore-log: 
08-31 17:07:21.947  6694  6804 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 17:07:21.947  6694  6804 I jxcore-log: 
08-31 17:07:21.948  6694  6804 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 17:07:21.948  6694  6804 I jxcore-log: 
08-31 17:07:21.949  6694  6804 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 17:07:21.949  6694  6804 I jxcore-log: 
08-31 17:07:21.950  6694  6804 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 17:07:21.950  6694  6804 I jxcore-log: 
08-31 17:07:21.951  6694  6804 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 17:07:21.951  6694  6804 I jxcore-log: 
,08-31 17:07:21.951  6694  6804 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 17:07:21.951  6694  6804 I jxcore-log: 
08-31 17:07:21.971  8218  8218 D LgDataFeature: LgDataFeature() Constructor: none
08-31 17:07:21.971  8218  8218 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-31 17:07:21.976  8218  8218 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
08-31 17:07:21.977  8218  8218 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-31 17:07:21.977  8218  8218 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-31 17:07:21.977  8218  8218 V SoundPool: doLoad: loading sample sampleID=1
08-31 17:07:21.977  8218  8218 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-31 17:07:21.979  8218  8270 V SoundPool: Start decode
08-31 17:07:21.979  8218  8270 V MediaPlayer[Native]: decode(31, 10857164, 17813)
08-31 17:07:21.980  1042  1523 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-31 17:07:21.980  1042  1523 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-31 17:07:21.980  1042  1523 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-31 17:07:21.980   317  1369 V MediaPlayerService: decode(23, 10857164, 17813)
08-31 17:07:21.980   317  1369 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-31 17:07:21.981   317  1369 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-31 17:07:21.981   317  1369 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-31 17:07:21.981   317  1369 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-31 17:07:21.981   317  1369 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-31 17:07:21.981   317  1369 V MediaPlayerService: player type = 3
08-31 17:07:21.981   317  1369 V AwesomePlayer: AwesomePlayer create()
08-31 17:07:21.981  1042  1523 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-31 17:07:21.981   317  1369 V AwesomePlayer: reset_l() 
08-31 17:07:21.981   317  1369 V AwesomePlayer: cancelPlayerEvents
08-31 17:07:21.981   317  1369 V AwesomePlayer: setAudioSink() 
08-31 17:07:21.981   317  1369 V AwesomePlayer: reset_l() 
08-31 17:07:21.981   317  1369 V AudioCache: notify(0xb1004300, 8, 0, 0)
08-31 17:07:21.981   317  1369 V AudioCache: ignored
08-31 17:07:21.981   317  1369 V AwesomePlayer: cancelPlayerEvents
08-31 17:07:21.981   317  1369 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
08-31 17:07:21.981  1042  1523 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-31 17:07:21.981   317  1369 V AwesomePlayer: setDataSource_l dataSource
08-31 17:07:21.981   317  1369 V LGParserOSAL: SniffLGParser start
08-31 17:07:21.981   317  1369 V LGParserOSAL: MainType:5, SubType=0
08-31 17:07:21.981   317  1369 V LGParserOSAL: #### check Mime : application/ogg
08-31 17:07:21.981   317  1369 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-31 17:07:21.981   317  1369 E MediaExtractor: Use LGExtractor :application/ogg 
08-31 17:07:21.982  1042  1523 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-31 17:07:21.982  1042  1530 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=true
08-31 17:07:21.982  1042  1530 D ConnectivityService: identical MTU - not setting
08-31 17:07:21.982  1042  1530 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-31 17:07:21.982  1042  1530 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-31 17:07:21.982  1042  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 17:07:21.982  1042  1530 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 17:07:21.983  1042  1530 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,08-31 17:07:21.984  1589  1799 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
08-31 17:07:21.986  8218  8218 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-31 17:07:21.988  7641  7641 D UEI.SmartControl: QS Service created
08-31 17:07:21.989  8218  8218 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-31 17:07:21.989  8218  8218 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-31 17:07:21.999  7641  7641 I UEI.SmartControl: Service initServices...
,08-31 17:07:22.001  7641  7641 D UEI.SmartControl: QS start get config
08-31 17:07:22.021  8218  8218 V LGMDMManager: Create singleton instance
08-31 17:07:22.023   317  1369 V LGParserOSAL: supported mime: application/ogg
,08-31 17:07:22.023   317  1369 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-31 17:07:22.023   317  1369 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-31 17:07:22.023   317  1369 V AwesomePlayer: mBitrate = -1 bits/sec
08-31 17:07:22.023   317  1369 V AwesomePlayer: AudioTrack Setting
08-31 17:07:22.023   317  1369 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-31 17:07:22.023   317  1369 V AwesomePlayer: setAudioSource() 
08-31 17:07:22.023   317  1369 V MediaPlayerService: prepare
08-31 17:07:22.023   317  1369 V AwesomePlayer: prepareAsync_l() 
08-31 17:07:22.023   317  1369 V MediaPlayerService: wait for prepare
08-31 17:07:22.023   317  8273 V AwesomePlayer: onPrepareAsyncEvent() 
08-31 17:07:22.023   317  8273 V AwesomePlayer: initAudioDecoder() 
08-31 17:07:22.023   317  8273 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-31 17:07:22.023   317  8273 V AudioSystem: isOffloadSupported()
08-31 17:07:22.023   317  8273 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-31 17:07:22.023   317  8273 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-31 17:07:22.023   317  8273 I AudioFlinger: isAudioPlaybackHookOn() false
08-31 17:07:22.023   317  8273 V AwesomePlayer: getUseOffload() = 0 
08-31 17:07:22.023   317  8273 V OMXCodec: OMXCodec::Create
08-31 17:07:22.023   317  8273 V OMXCodec: findMatchingCodecs()
08-31 17:07:22.024   317  8273 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-31 17:07:22.024   317  8273 V OMXCodec: matchingCodecs.size()=1
08-31 17:07:22.024   317  8273 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
08-31 17:07:22.026   317  8273 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-31 17:07:22.026   317  8273 V LGCodecAdapter: LG Codec Adapter start
08-31 17:07:22.026   317  8273 V OMXCodec: OMXCodec Createtor
08-31 17:07:22.026   317  8273 V OMXCodec: setComponentRole
08-31 17:07:22.026   317  8273 V OMXCodec: configureCodec protected=0
08-31 17:07:22.026   317  8273 V LGCodecAdapter: called getLGCodecSpecificData
08-31 17:07:22.026   317  8273 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-31 17:07:22.026   317  8273 V LGCodecOSAL: Called LGconfigureCodecMETA
08-31 17:07:22.026   317  8273 V LGCodecOSAL: Called LGconfigureCodecMSG
08-31 17:07:22.026   317  8273 V LGCodecOSAL: Not support LGCodec
08-31 17:07:22.027   317  8273 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-31 17:07:22.027   317  8273 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-31 17:07:22.027   317  8273 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-31 17:07:22.027   317  8273 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-31 17:07:22.027   317  8273 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-31 17:07:22.027   317  8273 V AudioSystem: isOffloadSupported()
08-31 17:07:22.027   317  8273 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-31 17:07:22.027   317  8273 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-31 17:07:22.027   317  8273 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-31 17:07:22.027   317  8273 V OMXCodec: init()
08-31 17:07:22.027   317  8273 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-31 17:07:22.027   317  8273 V OMXCodec: allocate,Buffers
08-31 17:07:22.027   317  8273 V OMXCodec: allocateBuffersOnPort portIndex=0
08-31 17:07:22.027   317  8273 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-31 17:07:22.027   317  8273 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f920 on input port
08-31 17:07:22.027   317  8273 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f970 on input port
08-31 17:07:22.027   317  8273 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f9c0 on input port
08-31 17:07:22.027   317  8273 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fa10 on input port
08-31 17:07:22.028   317  8273 V OMXCodec: allocateBuffersOnPort portIndex=1
08-31 17:07:22.028   317  8273 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-31 17:07:22.028   317  8273 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fa60 on output port
08-31 17:07:22.028   317  8273 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fb00 on output port
08-31 17:07:22.028   317  8273 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fba0 on output port
08-31 17:07:22.030   317  8273 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fe70 on output port
08-31 17:07:22.030   317  8273 V OMXCodec: init() mAsyncCompletion wait!!! 
08-31 17:07:22.030   317  8275 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-31 17:07:22.030   317  8275 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-31 17:07:22.030   317  8275 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-31 17:07:22.030   317  8273 V OMXCodec: init() mAsyncCompletion wait!!! 
08-31 17:07:22.030   317  8275 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-31 17:07:22.030   317  8275 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-31 17:07:22.030   317  8275 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-31 17:07:22.030   317  8273 V OMXCodec: init() mAsyncCompletion wait free! 
08-31 17:07:22.030   317  8273 V AwesomePlayer: finishAsyncPrepare_l() 
08-31 17:07:22.030   317  8273 V AudioCache: notify(0xb1004300, 5, 0, 0)
08-31 17:07:22.030   317  8273 V AudioCache: ignored
08-31 17:07:22.030   317  8273 V AudioCache: notify(0xb1004300, 1, 0, 0)
08-31 17:07:22.030   317  8273 V AudioCache: prepared
08-31 17:07:22.030   317  1369 V AudioCache: wait - success
08-31 17:07:22.030   317  1369 V MediaPlayerService: start
08-31 17:07:22.030   317  1369 V AwesomePlayer: play_l() 
08-31 17:07:22.030   317  1369 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-31 17:07:22.030   317  1369 V AwesomePlayer: createAudioPlayer_l
08-31 17:07:22.030   317  1369 V AwesomePlayer: seekAudioIfNecessary_l() 
08-31 17:07:22.031   317  1369 V AwesomePlayer: startAudioPlayer_l() 
08-31 17:07:22.031   317  1369 D AudioPlayer: start of Playback, useOffload 0
08-31 17:07:22.031   317  1369 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-31 17:07:22.031   317  1369 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-31 17:07:22.033   317  8275 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-31 17:07:22.033   317  8275 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
,08-31 17:07:22.033   317  8275 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-31 17:07:22.033   317  8275 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-31 17:07:22.034   317  8275 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-31 17:07:22.034   317  8275 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-31 17:07:22.034   317  8275 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957048416
08-31 17:07:22.034   317  8275 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-31 17:07:22.034   317  8275 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957048576
08-31 17:07:22.034   317  8275 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-31 17:07:22.034   317  8275 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957048736
08-31 17:07:22.034   317  8275 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-31 17:07:22.034   317  8275 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957049456
08-31 17:07:22.034   317  8275 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-31 17:07:22.034   317  8275 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-31 17:07:22.034   317  8275 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
,08-31 17:07:22.034   317  8275 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-31 17:07:22.034   317  8275 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-31 17:07:22.034   317  8275 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-31 17:07:22.035   317  8275 V OMXCodec: allocateBuffersOnPort portIndex=1
08-31 17:07:22.035   317  8275 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-31 17:07:22.035   317  8275 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fba0 on output port
08-31 17:07:22.035   317  8275 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fb00 on output port
08-31 17:07:22.035   317  8275 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fa60 on output port
08-31 17:07:22.035   317  8275 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7650 on output port
08-31 17:07:22.035   317  8275 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-31 17:07:22.035   317  8275 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-31 17:07:22.037   317  1369 V AudioCache: open(48000, 2, 0x0, 1, 4)
,08-31 17:07:22.046   317  1369 V AudioCache: notify(0xb1004300, 6, 0, 0)
08-31 17:07:22.046   317  1369 V AudioCache: ignored
08-31 17:07:22.046   317  1369 V MediaPlayerService: wait for playback complete
08-31 17:07:22.047   317  8276 V AudioCache: write(0xb57c4000, 4096)
08-31 17:07:22.047   317  8276 V AudioCache: memcpy(0xac200000, 0xb57c4000, 4096)
08-31 17:07:22.050   317  8276 V AudioCache: write(0xb57c4000, 4096)
08-31 17:07:22.050   317  8276 V AudioCache: memcpy(0xac201000, 0xb57c4000, 4096)
08-31 17:07:22.050   317  8276 V AudioCache: write(0xb57c4000, 4096)
08-31 17:07:22.050   317  8276 V AudioCache: memcpy(0xac202000, 0xb57c4000, 4096)
08-31 17:07:22.051   317  8276 V AudioCache: write(0xb57c4000, 4096)
08-31 17:07:22.051   317  8276 V AudioCache: memcpy(0xac203000, 0xb57c4000, 4096)
08-31 17:07:22.052   317  8276 V AudioCache: write(0xb57c4000, 4096)
08-31 17:07:22.052   317  8276 V AudioCache: memcpy(0xac204000, 0xb57c4000, 4096)
08-31 17:07:22.052   317  8276 V AudioCache: write(0xb57c4000, 4096)
08-31 17:07:22.053   317  8276 V AudioCache: memcpy(0xac205000, 0xb57c4000, 4096)
08-31 17:07:22.053   317  8276 V AudioCache: write(0xb57c4000, 4096)
08-31 17:07:22.053   317  8276 V AudioCache: memcpy(0xac206000, 0xb57c4000, 4096)
08-31 17:07:22.054   317  8276 V AudioCache: write(0xb57c4000, 4096)
08-31 17:07:22.054   317  8276 V AudioCache: memcpy(0xac207000, 0xb57c4000, 4096)
,08-31 17:07:22.055   317  8276 V AudioCache: write(0xb57c4000, 4096)
08-31 17:07:22.055   317  8276 V AudioCache: memcpy(0xac208000, 0xb57c4000, 4096)
08-31 17:07:22.056   317  8276 V AudioCache: write(0xb57c4000, 4096)
08-31 17:07:22.056   317  8276 V AudioCache: memcpy(0xac209000, 0xb57c4000, 4096)
08-31 17:07:22.056   317  8276 V AudioCache: write(0xb57c4000, 4096)
08-31 17:07:22.056   317  8276 V AudioCache: memcpy(0xac20a000, 0xb57c4000, 4096)
08-31 17:07:22.057   317  8276 V AudioCache: write(0xb57c4000, 4096)
08-31 17:07:22.057   317  8276 V AudioCache: memcpy(0xac20b000, 0xb57c4000, 4096)
08-31 17:07:22.058   317  8276 V AudioCache: write(0xb57c4000, 4096)
08-31 17:07:22.058   317  8276 V AudioCache: memcpy(0xac20c000, 0xb57c4000, 4096)
08-31 17:07:22.058   317  8276 V AudioCache: write(0xb57c4000, 4096)
08-31 17:07:22.059   317  8276 V AudioCache: memcpy(0xac20d000, 0xb57c4000, 4096)
08-31 17:07:22.059   317  8276 V AudioCache: write(0xb57c4000, 4096)
08-31 17:07:22.059   317  8276 V AudioCache: memcpy(0xac20e000, 0xb57c4000, 4096)
08-31 17:07:22.060   317  8276 V AudioCache: write(0xb57c4000, 4096)
08-31 17:07:22.060   317  8276 V AudioCache: memcpy(0xac20f000, 0xb57c4000, 4096)
08-31 17:07:22.061   317  8276 V AudioCache: write(0xb57c4000, 4096)
08-31 17:07:22.061   317  8276 V AudioCache: memcpy(0xac210000, 0xb57c4000, 4096)
08-31 17:07:22.061   317  8276 V AudioCache: write(0xb57c4000, 4096)
08-31 17:07:22.061   317  8276 V AudioCache: memcpy(0xac211000, 0xb57c4000, 4096)
08-31 17:07:22.062   317  8276 V AudioCache: write(0xb57c4000, 4096)
08-31 17:07:22.062   317  8276 V AudioCache: memcpy(0xac212000, 0xb57c4000, 4096)
08-31 17:07:22.063   317  8276 V AudioCache: write(0xb57c4000, 4096)
08-31 17:07:22.063   317  8276 V AudioCache: memcpy(0xac213000, 0xb57c4000, 4096)
,08-31 17:07:22.064   317  8276 V AudioCache: write(0xb57c4000, 4096)
08-31 17:07:22.064   317  8276 V AudioCache: memcpy(0xac214000, 0xb57c4000, 4096)
08-31 17:07:22.065   317  8276 V AudioCache: write(0xb57c4000, 4096)
08-31 17:07:22.065   317  8276 V AudioCache: memcpy(0xac215000, 0xb57c4000, 4096)
08-31 17:07:22.065   317  8276 V AudioCache: write(0xb57c4000, 4096)
08-31 17:07:22.065   317  8276 V AudioCache: memcpy(0xac216000, 0xb57c4000, 4096)
08-31 17:07:22.066   317  8276 V AudioCache: write(0xb57c4000, 4096)
08-31 17:07:22.066   317  8276 V AudioCache: memcpy(0xac217000, 0xb57c4000, 4096)
08-31 17:07:22.067   317  8276 V AudioCache: write(0xb57c4000, 4096)
08-31 17:07:22.067   317  8276 V AudioCache: memcpy(0xac218000, 0xb57c4000, 4096)
08-31 17:07:22.068   317  8276 V AudioCache: write(0xb57c4000, 4096)
08-31 17:07:22.068   317  8276 V AudioCache: memcpy(0xac219000, 0xb57c4000, 4096)
08-31 17:07:22.068   317  8276 V AudioCache: write(0xb57c4000, 4096)
08-31 17:07:22.068   317  8276 V AudioCache: memcpy(0xac21a000, 0xb57c4000, 4096)
08-31 17:07:22.068   317  8276 V AudioCache: write(0xb57c4000, 4096)
08-31 17:07:22.068   317  8276 V AudioCache: memcpy(0xac21b000, 0xb57c4000, 4096)
08-31 17:07:22.080   317  8276 V AudioCache: write(0xb57c4000, 4096)
08-31 17:07:22.080   317  8276 V AudioCache: memcpy(0xac21c000, 0xb57c4000, 4096)
08-31 17:07:22.080   317  8276 V AudioCache: write(0xb57c4000, 4096)
08-31 17:07:22.080   317  8276 V AudioCache: memcpy(0xac21d000, 0xb57c4000, 4096)
08-31 17:07:22.080   317  8276 V AudioCache: write(0xb57c4000, 4096)
08-31 17:07:22.080   317  8276 V AudioCache: memcpy(0xac21e000, 0xb57c4000, 4096)
,08-31 17:07:22.083   317  8276 V AudioCache: write(0xb57c4000, 4096)
08-31 17:07:22.083   317  8276 V AudioCache: memcpy(0xac21f000, 0xb57c4000, 4096)
08-31 17:07:22.083   317  8276 V AudioCache: write(0xb57c4000, 4096)
08-31 17:07:22.083   317  8276 V AudioCache: memcpy(0xac220000, 0xb57c4000, 4096)
08-31 17:07:22.083   317  8276 V AudioCache: write(0xb57c4000, 4096)
08-31 17:07:22.083   317  8276 V AudioCache: memcpy(0xac221000, 0xb57c4000, 4096)
08-31 17:07:22.083   317  8276 V AudioCache: write(0xb57c4000, 4096)
08-31 17:07:22.083   317  8276 V AudioCache: memcpy(0xac222000, 0xb57c4000, 4096)
08-31 17:07:22.084   317  8276 V AudioCache: write(0xb57c4000, 4096)
08-31 17:07:22.084   317  8276 V AudioCache: memcpy(0xac223000, 0xb57c4000, 4096)
08-31 17:07:22.084   317  8276 V AudioCache: write(0xb57c4000, 4096)
08-31 17:07:22.084   317  8276 V AudioCache: memcpy(0xac224000, 0xb57c4000, 4096)
08-31 17:07:22.084   317  8276 V AudioCache: write(0xb57c4000, 4096)
08-31 17:07:22.084   317  8276 V AudioCache: memcpy(0xac225000, 0xb57c4000, 4096)
08-31 17:07:22.084   317  8276 V AudioCache: write(0xb57c4000, 4096)
08-31 17:07:22.084   317  8276 V AudioCache: memcpy(0xac226000, 0xb57c4000, 4096)
08-31 17:07:22.085   317  8276 V AudioCache: write(0xb57c4000, 4096)
08-31 17:07:22.085   317  8276 V AudioCache: memcpy(0xac227000, 0xb57c4000, 4096)
08-31 17:07:22.085   317  8276 V AudioCache: write(0xb57c4000, 4096)
08-31 17:07:22.085   317  8276 V AudioCache: memcpy(0xac228000, 0xb57c4000, 4096)
08-31 17:07:22.085   317  8276 V AudioCache: write(0xb57c4000, 4096)
08-31 17:07:22.085   317  8276 V AudioCache: memcpy(0xac229000, 0xb57c4000, 4096)
08-31 17:07:22.085   317  8276 V AudioCache: write(0xb57c4000, 4096)
08-31 17:07:22.085   317  8276 V AudioCache: memcpy(0xac22a000, 0xb57c4000, 4096)
08-31 17:07:22.086   317  8276 V AudioCache: write(0xb57c4000, 4096)
08-31 17:07:22.086   317  8276 V AudioCache: memcpy(0xac22b000, 0xb57c4000, 4096)
08-31 17:07:22.086   317  8276 V AudioCache: write(0xb57c4000, 4096)
08-31 17:07:22.086   317  8276 V AudioCache: memcpy(0xac22c000, 0xb57c4000, 4096)
08-31 17:07:22.086   317  8276 V AudioCache: write(0xb57c4000, 4096)
08-31 17:07:22.086   317  8276 V AudioCache: memcpy(0xac22d000, 0xb57c4000, 4096)
08-31 17:07:22.086   317  8276 V AudioCache: write(0xb57c4000, 4096)
08-31 17:07:22.086   317  8276 V AudioCache: memcpy(0xac22e000, 0xb57c4000, 4096)
08-31 17:07:22.087   317  8275 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-31 17:07:22.087   317  8276 V AudioCache: write(0xb57c4000, 4096)
08-31 17:07:22.087   317  8276 V AudioCache: memcpy(0xac22f000, 0xb57c4000, 4096)
08-31 17:07:22.087   317  8276 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-31 17:07:22.087   317  8276 V AudioCache: write(0xb57c4000, 4096)
08-31 17:07:22.087   317  8276 V AudioCache: memcpy(0xac230000, 0xb57c4000, 4096)
08-31 17:07:22.087   317  8276 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-31 17:07:22.087   317  8276 V AudioCache: write(0xb57c4000, 4096)
08-31 17:07:22.087   317  8276 V AudioCache: memcpy(0xac231000, 0xb57c4000, 4096)
08-31 17:07:22.087   317  8276 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-31 17:07:22.087   317  8276 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-31 17:07:22.087   317  8276 V AwesomePlayer: postAudioEOS() 
08-31 17:07:22.087   317  8276 V AudioCache: write(0xb57c4000, 280)
08-31 17:07:22.087   317  8276 V AudioCache: memcpy(0xac232000, 0xb57c4000, 280)
08-31 17:07:22.089   317  8273 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-31 17:07:22.089   317  8273 V AwesomePlayer: onStreamDone
08-31 17:07:22.089   317  8273 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-31 17:07:22.089   317  8273 V AudioCache: notify(0xb1004300, 2, 0, 0)
08-31 17:07:22.08,9   317  8273 V AudioCache: playback complete
08-31 17:07:22.089   317  8273 V AwesomePlayer: pause_l() 
08-31 17:07:22.089   317  8273 V AudioCache: notify(0xb1004300, 7, 0, 0)
08-31 17:07:22.089   317  8273 V AudioCache: ignored
08-31 17:07:22.089   317  8273 V AwesomePlayer: cancelPlayerEvents
08-31 17:07:22.089   317  1369 V AudioCache: wait - success
08-31 17:07:22.089   317  1369 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-31 17:07:22.089   317  8273 D AudioPlayer: Pause Playback at 1068125
08-31 17:07:22.090   317  1369 V AwesomePlayer: reset_l() 
08-31 17:07:22.090   317  1369 V AudioCache: notify(0xb1004300, 8, 0, 0)
08-31 17:07:22.090   317  1369 V AudioCache: ignored
08-31 17:07:22.090   317  1369 V AwesomePlayer: cancelPlayerEvents
08-31 17:07:22.090   317  1369 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-31 17:07:22.090   317  1369 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-31 17:07:22.090   317  1369 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-31 17:07:22.090   317  1369 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-31 17:07:22.090   317  1369 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-31 17:07:22.090   317  8275 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-31 17:07:22.090   317  8275 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-31 17:07:22.090   317  8275 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-31 17:07:22.090   317  8275 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fa10 on port 0
08-31 17:07:22.090   317  8275 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-31 17:07:22.090   317  8275 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f9c0 on port 0
08-31 17:07:22.090   317  8275 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-31 17:07:22.090   317  8275 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f970 on port 0
08-31 17:07:22.090   317  8275 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-31 17:07:22.090   317  8275 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f920 on port 0
08-31 17:07:22.090   317  8275 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-31 17:07:22.090   317  8275 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-31 17:07:22.090   317  8275 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7650 on port 1
08-31 17:07:22.090   317  8275 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-31 17:07:22.090   317  8275 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fa60 on port 1
08-31 17:07:22.090   317  8275 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
,08-31 17:07:22.090   317  8275 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fb00 on port 1
08-31 17:07:22.090   317  8275 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-31 17:07:22.090   317  8275 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fba0 on port 1
08-31 17:07:22.090   317  8275 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-31 17:07:22.090   317  8275 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-31 17:07:22.090   317  1369 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-31 17:07:22.090   317  1369 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-31 17:07:22.091   317  8275 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-31 17:07:22.091   317  8275 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-31 17:07:22.091   317  8275 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-31 17:07:22.091   317  1369 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-31 17:07:22.091   317  1369 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-31 17:07:22.091   317  1369 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-31 17:07:22.091   317  1369 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-31 17:07:22.091   317  1369 D AudioPlayer: AudioPlayer releasing audio source
08-31 17:07:22.091   317  1369 D AudioPlayer: AudioPlayer done releasing audio source
08-31 17:07:22.092   317  1369 V AwesomePlayer: reset_l() 
08-31 17:07:22.092   317  1369 V AwesomePlayer: cancelPlayerEvents
08-31 17:07:22.092   317  1369 V AwesomePlayer: ~AwesomePlayer call
08-31 17:07:22.092   317  1369 V AwesomePlayer: reset_l() 
08-31 17:07:22.092   317  1369 V AwesomePlayer: cancelPlayerEvents
08-31 17:07:22.092  8218  8270 V SoundPool: close(31)
08-31 17:07:22.092  8218  8270 V SoundPool: pointer = 0xa0033000, size = 205080, sampleRate = 48000, numChannels = 2
08-31 17:07:22.102  8218  8218 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-31 17:07:22.103  8218  8218 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
08-31 17:07:22.104  8218  8218 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:964
08-31 17:07:22.106  8144  8144 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 17:07:22.127  8144  8144 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-31 17:07:22.131  8144  8144 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 17:07:22.132  8144  8144 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 17:07:22.134  8144  8144 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 17:07:22.137  8144  8144 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 17:07:22.139  8144  8144 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-31 17:07:22.143  8144  8144 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 17:07:22.145  8144  8144 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 17:07:22.149  8144  8144 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 17:07:22.164  8271  8271 D AndroidRuntime: 
08-31 17:07:22.164  8271  8271 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-31 17:07:22.168  8271  8271 D AndroidRuntime: CheckJNI is OFF
,08-31 17:07:22.357  8271  8271 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-31 17:07:22.384  1042  1110 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
,08-31 17:07:22.386  1042  1110 I ActivityManager: Killing 6694:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
08-31 17:07:22.411  7641  7641 I UEI.SmartControl: Supports setup maps: true
08-31 17:07:22.414  7641  7641 D UEI.SmartControl: QS start statue = true Error code = 0
08-31 17:07:22.414  7641  7641 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-31 17:07:22.414  7641  7641 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-31 17:07:22.414  7641  7641 I UEI.SmartControl: ### init IR Blaster...
,08-31 17:07:22.418  7641  7641 D serial_port: Configuring serial port
,08-31 17:07:22.418  7641  7641 E UEI.SmartControl: UEIBLaster setting for 616
08-31 17:07:22.418  7641  7641 I UEI.SmartControl: Setting serial record hearder size = 2
08-31 17:07:22.418  7641  7641 I UEI.SmartControl: configuring settings for MAXQ616
08-31 17:07:22.418  7641  7641 I UEI.SmartControl: Get version...
08-31 17:07:22.435  7641  8290 D UEI.SmartControl: serial port data available: 21
,08-31 17:07:22.453  1042  1561 I WindowState: WIN DEATH: Window{1385d5e u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-31 17:07:22.454  1042  1529 D WifiService: Client connection lost with reason: 4
,08-31 17:07:22.461  1042  1561 D InputDispatcher: Window went away: Window{1385d5e u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-31 17:07:22.462  7641  7641 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-31 17:07:22.462  7641  7641 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-31 17:07:22.462  7641  7641 I UEI.SmartControl: QS saving settings...
08-31 17:07:22.463  7641  7641 D UEI.SmartControl: IR Blaster version: 25672567
08-31 17:07:22.479  7641  8290 D UEI.SmartControl: serial port data available: 4
,08-31 17:07:22.507  7641  8293 I UEI.SmartControl: Device manager: loading config....
,08-31 17:07:22.510  7641  8293 D UEI.SmartControl: ----------- loading internal config...
,08-31 17:07:22.510  7641  7641 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-31 17:07:22.518  7641  8293 E UEI.SmartControl: Loading SETTINGS...
08-31 17:07:22.523  7641  8293 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,08-31 17:07:22.546  7641  8292 I UEI.SmartControl: Notify AllClients services are ready: 0
,08-31 17:07:22.547  7641  8292 D UEI.SmartControl: -----service ready thread exits
,08-31 17:07:22.600  1042  1110 I ActivityManager:   Force finishing activity ActivityRecord{51aee7b u0 com.test.thalitest/.MainActivity t6}
,08-31 17:07:22.632   347   417 E GBMv2   : DFP En is all cleared set to be enabled
08-31 17:07:22.633  1042  1123 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
08-31 17:07:22.640  1042  1123 I ActivityManager:   Force finishing activity ActivityRecord{51aee7b u0 com.test.thalitest/.MainActivity t6 f}
08-31 17:07:22.640  1042  1123 W ActivityManager: Duplicate finish request for ActivityRecord{51aee7b u0 com.test.thalitest/.MainActivity t6 f}
,08-31 17:07:22.667  1042  1726 W ActivityManager: Spurious death for ProcessRecord{21a645e1 6694:com.test.thalitest/u0a118}, curProc for 6694: null
,08-31 17:07:22.669  2081  2081 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
08-31 17:07:22.670  1956  3966 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
08-31 17:07:22.671  1956  3966 D SplitWindowPolicy: topRunningActivity=ActivityInfo{1a87c72d co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-31 17:07:22.672  2081  2081 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
08-31 17:07:22.672  1956  1972 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
08-31 17:07:22.673  1956  1972 D SplitWindowPolicy: topRunningActivity=ActivityInfo{244db462 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-31 17:07:22.674  2081  2081 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
08-31 17:07:22.674  7641  7641 E UEI.SmartControl: Services init done
08-31 17:07:22.674  7641  7641 D UEI.SmartControl: QS Service init finished
08-31 17:07:22.675  2081  2165 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
08-31 17:07:22.679  7641  7641 D UEI.SmartControl: QS Service version name: 2.1.91
08-31 17:07:22.679  7641  7641 D UEI.SmartControl: QS Service version code: 201091
,08-31 17:07:22.682  7641  7641 D UEI.SmartControl: Service requested: Control
08-31 17:07:22.686  1589  1589 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
08-31 17:07:22.703  2028  2028 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-31 17:07:22.703  3810  3810 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
,08-31 17:07:22.704  4477  4477 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-31 17:07:22.704  4477  4477 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-31 17:07:22.704  4477  4477 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-31 17:07:22.704  4477  4477 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-31 17:07:22.704  4477  4477 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-31 17:07:22.704  4477  4477 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-31 17:07:22.704  4477  4477 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-31 17:07:22.704  4477  4477 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-31 17:07:22.704  4477  4477 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 17:07:22.705  4477  4477 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 17:07:22.705  4477  4477 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-31 17:07:22.705  4477  4477 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-31 17:07:22.707  7719  7719 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
08-31 17:07:22.707  7719  7719 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-31 17:07:22.737  1042  1419 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-31 17:07:22.745  4594  4594 I art     : Explicit concurrent mark sweep GC freed 8236(471KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 30MB/46MB, paused 730us total 85.531ms
08-31 17:07:22.752  1042  1561 V SIM_STK : Menu title from STK is T-Mobile
08-31 17:07:22.761  1042  1108 W InputMethodInfo: Duplicated subtype definition found: , voice
,08-31 17:07:22.773  1042  1042 D administrator: Handling package changes for user 0
,08-31 17:07:22.774  2479  2595 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-31 17:07:22.788  2081  2081 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
08-31 17:07:22.788  1917  1917 D ActionManagerService: notifyUserLog: 1000003
08-31 17:07:22.789  3810  4469 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
08-31 17:07:22.791  2081  2081 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
,08-31 17:07:22.794  2081  2081 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
08-31 17:07:22.795  8144  8144 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-31 17:07:22.805  1827  1827 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
,08-31 17:07:22.809  2081  2081 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
08-31 17:07:22.811  1589  1589 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
08-31 17:07:22.811  7641  7641 D UEI.SmartControl: Internal service binding...
08-31 17:07:22.811  8218  8218 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-31 17:07:22.819  2230  2230 I ConfigService: onCreate
08-31 17:07:22.823  7641  7657 I UEI.SmartControl: ------ IControl API: 11
08-31 17:07:22.823  7641  7657 D UEI.SmartControl: File observer start...
,08-31 17:07:22.823  7641  7657 E UEI.SmartControl: IR Port is disabled: false
08-31 17:07:22.823  7641  7657 D UEI.SmartControl: Starting file observer...
08-31 17:07:22.823  7641  7657 I UEI.SmartControl: Registering callback...
08-31 17:07:22.824  2230  2230 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
08-31 17:07:22.827  1917  1917 D ActionManagerService: notifyUserLog: 1000004
08-31 17:07:22.828  1589  1639 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-31 17:07:22.828  1589  1639 D KeyguardModel: createShortcutInfo...
08-31 17:07:22.829  3810  4469 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
08-31 17:07:22.829  2081  2081 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
08-31 17:07:22.831  1589  1589 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-31 17:07:22.831  1589  1589 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
08-31 17:07:22.831  3810  3829 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-31 17:07:22.832  1883  1883 D SplitUIManager: split_name #11 / not available #0
08-31 17:07:22.833  1883  1883 D SplitUIService: removed split : 
08-31 17:07:22.835  2081  2081 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-31 17:07:22.835  2081  2081 I GBoardWebViewUtils: , create_time: 1430832262123
08-31 17:07:22.835  2081  2081 I GBoardWebViewUtils: , expire_time: 0
08-31 17:07:22.835  2081  2081 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-31 17:07:22.835  2081  2081 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-31 17:07:22.835  2081  2081 I GBoardWebViewUtils: , display: false
08-31 17:07:22.835  2081  2081 I GBoardWebViewUtils: , animation: false }
08-31 17:07:22.835  2081  2081 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-31 17:07:22.835  2081  2081 I GBoardWebViewUtils: , create_time: 1430832262287
08-31 17:07:22.835  2081  2081 I GBoardWebViewUtils: , expire_time: 0
08-31 17:07:22.835  2081  2081 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-31 17:07:22.835  2081  2081 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-31 17:07:22.835  2081  2081 I GBoardWebViewUtils: , display: false
08-31 17:07:22.835  2081  2081 I GBoardWebViewUtils: , animation: false }
08-31 17:07:22.835  1827  1827 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
08-31 17:07:22.835  2081  2081 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1472216587976
08-31 17:07:22.835  2081  2081 I GBoardWebViewUtils: , create_time: 1472216588858
08-31 17:07:22.835  2081  2081 I GBoardWebViewUtils: , expire_time: 0
08-31 17:07:22.835  2081  2081 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide.html?id=guide_1111111111116_1472216587976&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-31 17:07:22.835  2081  2081 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-31 17:07:22.835  2081  2081 I GBoardWebViewUtils: , display: false
08-31 17:07:22.835  2081  2081 I GBoardWebViewUtils: , animation: false }
08-31 17:07:,22.837  1042  1918 V SIM_STK : Menu title from STK is T-Mobile
08-31 17:07:22.837  1042  1918 V SIM_STK : Menu title from STK is T-Mobile
,08-31 17:07:22.840  2230  2230 I ConfigService: onBind returning update interface
08-31 17:07:22.842  7641  7656 I UEI.SmartControl: ------ IControl API: 19
08-31 17:07:22.850  2230  2230 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-31 17:07:22.850  2230  2230 I ConfigService: onBind returning config service
08-31 17:07:22.850  2081  8297 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
08-31 17:07:22.851  1589  1639 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-31 17:07:22.851  1589  1639 D KeyguardModel: createShortcutInfo...
08-31 17:07:22.851  7641  7656 I UEI.SmartControl: Registering Services Ready callback...
,08-31 17:07:22.852  7641  7656 I UEI.SmartControl: Notify client services are ready...
08-31 17:07:22.852  8218  8233 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-31 17:07:22.853  8218  8268 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-31 17:07:22.853  8218  8268 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-31 17:07:22.863  1589  1639 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-31 17:07:22.864  1589  1639 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-31 17:07:22.864  1589  1639 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-31 17:07:22.866  1589  1639 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-31 17:07:22.870  1827  8298 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,08-31 17:07:22.870  2230  2230 I ConfigService: onDestroy
08-31 17:07:22.875  1589  1639 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-31 17:07:22.875  1589  1639 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-31 17:07:22.881  8218  8218 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-31 17:07:22.881  8218  8218 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-31 17:07:22.882  7641  7657 I UEI.SmartControl: ------ IControl API: 8
08-31 17:07:22.882  1589  1639 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-31 17:07:22.882  1589  1639 D KeyguardModel: createShortcutInfo...
08-31 17:07:22.883  8218  8218 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
,08-31 17:07:22.883  2081  2081 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-31 17:07:22.883  8218  8218 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-31 17:07:22.883  8218  8218 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-31 17:07:22.883  1883  1883 D SplitUIManager: split_name #11 / not available #0
08-31 17:07:22.883  1883  1883 I SplitUIService: split app #11
,08-31 17:07:22.885  2081  2081 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
08-31 17:07:22.887  1589  1639 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-31 17:07:22.888  1589  1639 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-31 17:07:22.888  1042  2046 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-31 17:07:22.889  7719  7719 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-31 17:07:22.889  7719  7719 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-31 17:07:22.889  7719  7719 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-31 17:07:22.889  7719  7719 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-31 17:07:22.889  7719  7719 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-31 17:07:22.889  7719  7719 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-31 17:07:22.889  7719  7719 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-31 17:07:22.889  7719  7719 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-31 17:07:22.889  7719  7719 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
,08-31 17:07:22.889  7719  7719 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-31 17:07:22.889  7719  7719 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-31 17:07:22.892  1042  1918 V SIM_STK : Menu title from STK is T-Mobile
08-31 17:07:22.893  1589  1639 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-31 17:07:22.893  1589  1639 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-31 17:07:22.893  8218  8218 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-31 17:07:22.894  1589  1639 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-31 17:07:22.894  1589  1639 D KeyguardModel: createShortcutInfo...
08-31 17:07:22.898  8218  8218 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-31 17:07:22.898  8218  8218 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
,08-31 17:07:22.903  8218  8218 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
08-31 17:07:22.907  7098  7098 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
08-31 17:07:22.908  8218  8218 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
08-31 17:07:22.909  1589  1639 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-31 17:07:22.909  1589  1639 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-31 17:07:22.909  1589  1639 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-31 17:07:22.909  1589  1639 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-31 17:07:22.913  1589  1639 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-31 17:07:22.913  1589  1639 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
,08-31 17:07:22.921  1589  1639 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-31 17:07:22.921  1589  1639 D KeyguardModel: createShortcutInfo...
08-31 17:07:22.927  5944  8305 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
08-31 17:07:22.928  1827  8306 I PeopleContactsSync: CP2 sync disabled
,08-31 17:07:22.935  1827  4758 I Icing   : doRemovePackageData com.test.thalitest
08-31 17:07:22.944  1042  1561 I ActivityManager: Killing 7278:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
08-31 17:07:22.967  2186  8308 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-31 17:07:22.983  1042  1123 I art     : Explicit concurrent mark sweep GC freed 80883(4MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 43MB/65MB, paused 1.870ms total 310.317ms
,08-31 17:07:23.027  1589  1589 D KeyguardModel: handleShortcutListChanged...
,08-31 17:07:23.027  1589  1589 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
,08-31 17:07:23.031  8271  8271 D AndroidRuntime: Shutting down VM
08-31 17:07:23.037  1042  2027 W libprocessgroup: failed to open /acct/uid_10005/pid_7278/cgroup.procs: No such file or directory
08-31 17:07:23.044  2081  2081 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
,08-31 17:07:23.057  1042  1042 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-31 17:07:23.057  1042  1042 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-31 17:07:23.058  1042  1042 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-31 17:07:23.091  1042  1123 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8310 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-31 17:07:23.133  1042  2248 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8327 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-31 17:07:23.141  1042  1563 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
08-31 17:07:23.141  1589  1639 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-31 17:07:23.141  1589  1639 D KeyguardModel: createShortcutInfo...
08-31 17:07:23.144  1589  1639 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
,08-31 17:07:23.144  1589  1639 D KeyguardModel: createShortcutInfo...
08-31 17:07:23.146  2081  2081 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,08-31 17:07:23.148  2081  2081 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-31 17:07:23.150  2081  2081 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
08-31 17:07:23.151  2081  2081 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-31 17:07:23.152  2081  2081 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-31 17:07:23.153  2081  2081 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
08-31 17:07:23.153  1589  1639 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-31 17:07:23.153  1589  1639 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-31 17:07:23.154  1589  1639 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-31 17:07:23.155  1589  1639 D KeyguardModel: createShortcutInfo...
08-31 17:07:23.155  1589  1639 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-31 17:07:23.156  1589  1639 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-31 17:07:23.157  1589  1639 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-31 17:07:23.157  1589  1639 D KeyguardModel: createShortcutInfo...
08-31 17:07:23.158  1589  1639 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-31 17:07:23.158  1589  1639 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
,08-31 17:07:23.162  1589  1639 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-31 17:07:23.162  1589  1639 D KeyguardModel: createShortcutInfo...
08-31 17:07:23.169  2081  2081 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
08-31 17:07:23.169  2081  2081 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-31 17:07:23.173  2081  2293 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-31 17:07:23.173  2081  2293 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
,08-31 17:07:23.177  1042  1118 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{393ab87d u0 com.lge.launcher2/.Launcher t5} time:141269
08-31 17:07:23.188  1042  1108 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-31 17:07:23.192  1042  1108 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-31 17:07:23.195  2081  2081 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
08-31 17:07:23.196  1589  1589 D KeyguardModel: handleShortcutListChanged...
08-31 17:07:23.196  1589  1589 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-31 17:07:23.196  2081  2081 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-31 17:07:23.197  1827  8304 W GmsApplication: Using Auth Proxy for data requests.
08-31 17:07:23.197  2081  2081 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-31 17:07:23.197  2081  2081 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-31 17:07:23.202  1827  8304 W GmsApplication: Using Auth Proxy for data requests.
,08-31 17:07:23.206  2081  2081 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
08-31 17:07:23.208  2639  2639 D [Concierge]Service: onStartCommand(). Type : 8
08-31 17:07:23.208  2639  2639 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
08-31 17:07:23.209  1042  2342 I ActivityManager: Killing 7749:com.google.android.talk/u0a72 (adj 15): empty #17
08-31 17:07:23.210  2639  2639 D [Concierge]Service: Update widget ID : 11
08-31 17:07:23.211  2081  2081 D [Concierge]WidgetView: change position of spinner
08-31 17:07:23.221  2230  2249 I art     : Explicit concurrent mark sweep GC freed 7146(412KB) AllocSpace objects, 0(0B) LOS objects, 52% free, 29MB/61MB, paused 595us total 17.230ms
,08-31 17:07:23.228  8327  8327 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-31 17:07:23.228  8327  8327 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-31 17:07:23.229  8327  8327 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-31 17:07:23.229  8327  8327 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-31 17:07:23.292  2081  2081 I [Concierge]WidgetView: initWebView(). Time : 1472656043292
08-31 17:07:23.293  1042  1983 W libprocessgroup: failed to open /acct/uid_10072/pid_7749/cgroup.procs: No such file or directory
,08-31 17:07:23.294  2639  2639 D [Concierge]Service: onStartCommand(). Type : 0
08-31 17:07:23.302  8327  8327 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
08-31 17:07:23.320  8327  8327 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,08-31 17:07:23.353  8327  8327 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-31 17:07:23.376  2081  2081 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 669688421
08-31 17:07:23.377  2081  2081 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
08-31 17:07:23.377  2081  2081 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,08-31 17:07:23.381  2081  2081 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@230f5fae
08-31 17:07:23.381  2081  2081 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
08-31 17:07:23.382  2081  2081 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-31 17:07:23.382  2081  2081 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-31 17:07:23.388  2081  2081 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
08-31 17:07:23.388  8327  8327 D LgDataFeature: LgDataFeature() Constructor: none
08-31 17:07:23.388  8327  8327 D LgDataFeature: LgDataFeature() Constructor Done, null
08-31 17:07:23.389  2081  2081 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-31 17:07:23.389  2081  2081 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
,08-31 17:07:23.391  2081  2081 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1472655930073, New one : 1472656043292
08-31 17:07:23.391  2081  2081 D [Concierge]WidgetView: Unregister all receivers
08-31 17:07:23.391  2081  2081 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-31 17:07:23.392  2081  2081 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-31 17:07:23.393  2081  2081 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
08-31 17:07:23.395  2081  2081 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
08-31 17:07:23.396  2081  2081 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
08-31 17:07:23.397  2081  2081 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
08-31 17:07:23.399  2081  2081 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
08-31 17:07:23.400  2081  2081 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-31 17:07:23.400  2081  2081 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-31 17:07:23.453  8327  8327 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,08-31 17:07:23.457  2081  2081 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-31 17:07:23.459  7820  7820 E SharedPreferencesImpl: Couldn't rename file /data/data/com.android.gallery3d/shared_prefs/com.android.gallery3d_preferences.xml to backup file /data/data/com.android.gallery3d/shared_prefs/com.android.gallery3d_preferences.xml.bak
08-31 17:07:23.460  1042  1954 I ActivityManager: Killing 7842:com.android.vending/u0a44 (adj 15): empty #17
08-31 17:07:23.475  2081  2081 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null

```
