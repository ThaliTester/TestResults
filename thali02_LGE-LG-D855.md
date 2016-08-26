#### Test 79896569fbe8035_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
08-26 21:53:15.475  6582  6582 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
--------- beginning of system
08-26 21:53:15.510  1034  1887 I ActivityManager: Killing 6098:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
08-26 21:53:15.555  1996  1996 D LIA_Service_NativeEventReceiver: onReceive action : android.intent.action.PACKAGE_ADDED = package:com.test.thalitest
08-26 21:53:15.555  1996  1996 I LIA_Service_PlatformUtil: startLIAService() : Trying to start LIA service ...
,08-26 21:53:15.557  1034  1975 W libprocessgroup: failed to open /acct/uid_10080/pid_6098/cgroup.procs: No such file or directory
08-26 21:53:15.562  1996  1996 D LIA_Service_LIAService: onStartCommand() : LIAService started! - id :3, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
08-26 21:53:15.592  6448  6448 D PostponalbeReceiver: OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_ADDED'.
08-26 21:53:15.599  6448  6448 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsm.mss.OasPackageScanReceiver.onReceive:-1 android.app.ActivityThread.handleReceiver:2586 
08-26 21:53:15.682  1034  1995 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=6613 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-26 21:53:15.873  6611  6611 D AndroidRuntime: 
08-26 21:53:15.873  6611  6611 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-26 21:53:15.876  6611  6611 D AndroidRuntime: CheckJNI is OFF
08-26 21:53:15.921  6613  6613 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
08-26 21:53:15.986  6613  6613 D LgDataFeature: LgDataFeature() Constructor: none
08-26 21:53:15.987  6613  6613 D LgDataFeature: LgDataFeature() Constructor Done, null
08-26 21:53:16.004  6611  6611 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-26 21:53:16.008  1034  1887 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-26 21:53:16.016   335   415 I ThermalEngine: Thermal-Server: Thermal received msg from  override
08-26 21:53:16.017  1942  1958 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-26 21:53:16.019  1034  1887 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-26 21:53:16.020  1034  1887 D ActivityManager: setTaskToReturnTo : TaskRecord{354328e9 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-26 21:53:16.020  1034  1887 D ActivityManager: setTaskToReturnTo : TaskRecord{354328e9 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-26 21:53:16.021  3293  6670 I Thermal-Lib: Thermal-Lib-Client: Client request sent
08-26 21:53:16.022  1034  1887 D WindowStateEx: AppWindowTokenEx init.. 
08-26 21:53:16.022   341   352 E GBMv2   : DFP En is all cleared set to be enabled
08-26 21:53:16.029  6613  6613 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
08-26 21:53:16.043  6613  6613 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
08-26 21:53:16.044  6613  6613 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
08-26 21:53:16.059  6613  6613 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-26 21:53:16.059  1034  1887 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6674 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-26 21:53:16.059  6613  6613 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
08-26 21:53:16.060  6611  6611 D AndroidRuntime: Shutting down VM
08-26 21:53:16.073  1034  2006 I ActivityManager: Killing 5479:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
08-26 21:53:16.103  1034  2030 W libprocessgroup: failed to open /acct/uid_10085/pid_5479/cgroup.procs: No such file or directory
08-26 21:53:16.125  1942  4399 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-26 21:53:16.125  1942  4399 D SplitWindowPolicy: topRunningActivity=ActivityInfo{1ddddb8 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-26 21:53:16.126  1942  1958 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-26 21:53:16.126  1942  1958 D SplitWindowPolicy: topRunningActivity=ActivityInfo{1955a791 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-26 21:53:16.127  2859  4199 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
08-26 21:53:16.128  2859  4199 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@1b1a7b6a on behalf of 6613
08-26 21:53:16.136  5021  6692 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
08-26 21:53:16.177  1034  1898 V SIM_STK : Menu title from STK is T-Mobile
08-26 21:53:16.179  1034  1887 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=6694 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-26 21:53:16.183  6613  6613 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
08-26 21:53:16.193  6674  6674 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-26 21:53:16.229  6613  6613 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,08-26 21:53:16.301  6674  6674 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
08-26 21:53:16.308  6674  6674 I LibraryLoader: Loading: webviewchromium
08-26 21:53:16.310  6674  6674 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 9076-9078)
08-26 21:53:16.310  6674  6674 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-26 21:53:16.322  6674  6674 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {b1b8426}
08-26 21:53:16.323  6674  6674 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-26 21:53:16.323  6674  6674 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-26 21:53:16.330  6674  6674 I BrowserStartupController: Initializing chromium process, renderers=0
08-26 21:53:16.331  6674  6674 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-26 21:53:16.333  1817  1834 I art     : Explicit concurrent mark sweep GC freed 31300(1969KB) AllocSpace objects, 12(192KB) LOS objects, 51% free, 29MB/61MB, paused 2.028ms total 71.678ms
08-26 21:53:16.347  5021  6692 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 211 ms] updated apps [took 211 ms] 
08-26 21:53:16.354  6674  6674 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-26 21:53:16.354  6674  6674 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=33 off=46780 len=2953
08-26 21:53:16.355  6674  6674 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:34 off:229536 len:643667
08-26 21:53:16.359   319  1384 V AudioPolicyService: registerClient() client 0xb558a220, uid 10118
08-26 21:53:16.363  6674  6674 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-26 21:53:16.363  6674  6674 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-26 21:53:16.363  6674  6674 I Adreno-EGL: Build Date: 12/12/14 금
08-26 21:53:16.363  6674  6674 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-26 21:53:16.363  6674  6674 I Adreno-EGL: Remote Branch: 
08-26 21:53:16.363  6674  6674 I Adreno-EGL: Local Patches: 
08-26 21:53:16.363  6674  6674 I Adreno-EGL: Reconstruct Branch: 
08-26 21:53:16.365  1034  1105 D BluetoothManagerService: Message: 20
08-26 21:53:16.365  1034  1105 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@67b1e59:true
08-26 21:53:16.414  6694  6694 D DocsApplication: Installing DEX configuration.
08-26 21:53:16.427  6694  6694 D DexInstaller: Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
08-26 21:53:16.430  6694  6694 I PackageInfoHelper: Provided clientMode=RELEASE, packageInfo=PackageInfo{1a40e37c com.google.android.apps.docs}
08-26 21:53:16.440  6674  6735 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
08-26 21:53:16.440  6694  6694 D TAG     : onCreate()
08-26 21:53:16.444  6674  6674 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
08-26 21:53:16.455  6694  6694 D CrossAppStateProvider: Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
08-26 21:53:16.455  6674  6674 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-26 21:53:16.458  6674  6674 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-26 21:53:16.460  6674  6674 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-26 21:53:16.462  6674  6674 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-26 21:53:16.462  6674  6674 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
08-26 21:53:16.472  6674  6674 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
08-26 21:53:16.479  6674  6674 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-26 21:53:16.479  6674  6674 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-26 21:53:16.504  6674  6747 D OpenGLRenderer: Render dirty regions requested: true
08-26 21:53:16.505  6674  6747 I OpenGLRenderer: Initialized EGL, version 1.4
08-26 21:53:16.510  6674  6747 D OpenGLRenderer: Enabling debug mode 0
08-26 21:53:16.522  6674  6674 D Atlas   : Validating map...
08-26 21:53:16.527  1034  1995 D SplitWindow: check instance of lgWin Window{2c891ce8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-26 21:53:16.564  6674  6745 D LgDataFeature: LgDataFeature() Constructor: none
08-26 21:53:16.564  6674  6745 D LgDataFeature: LgDataFeature() Constructor Done, null
08-26 21:53:16.657  1034  1107 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +536ms (total +634ms)
08-26 21:53:16.658  1034  1107 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3145996e u0 com.test.thalitest/.MainActivity t6} time:109426
08-26 21:53:16.664  6674  6674 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1bc5912d time:109433
08-26 21:53:16.763  6674  6674 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
08-26 21:53:16.792  6674  6674 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-26 21:53:16.792  6674  6674 I chromium: 
08-26 21:53:16.813  6674  6745 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-26 21:53:16.813  6674  6745 I chromium: 
08-26 21:53:16.912  6674  6761 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1434963456
08-26 21:53:16.930  6674  6761 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-26 21:53:16.930  6674  6761 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-26 21:53:16.930  6674  6761 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-26 21:53:16.930  6674  6761 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-26 21:53:16.930  6674  6761 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-26 21:53:16.932  6674  6761 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19acfe61 added. We now have 1 listener(s)
08-26 21:53:16.944  1034  1576 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 21:53:16.948  6674  6761 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-26 21:53:16.951  6674  6761 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-26 21:53:16.952  6674  6761 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 21:53:16.952  6674  6761 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 21:53:16.960  6674  6761 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-26 21:53:16.960  6674  6761 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-26 21:53:16.960  6674  6761 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-26 21:53:16.960  6674  6761 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-26 21:53:16.960  6674  6761 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-26 21:53:16.960  6674  6761 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-26 21:53:16.960  6674  6761 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-26 21:53:16.960  6674  6761 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-26 21:53:16.960  6674  6761 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-26 21:53:16.960  6674  6761 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-26 21:53:16.960  6674  6761 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-26 21:53:16.960  6674  6761 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-26 21:53:16.960  6674  6761 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-26 21:53:16.960  6674  6761 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-26 21:53:16.960  6674  6761 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e803e74 added. We now have 1 listener(s)
08-26 21:53:16.960  6674  6761 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 21:53:16.965  1034  1542 D WifiService: New client listening to asynchronous messages
08-26 21:53:16.969  6674  6761 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-26 21:53:16.969  6674  6761 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-26 21:53:16.971  6674  6761 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-26 21:53:16.971  6674  6761 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-26 21:53:16.971  6674  6761 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-26 21:53:16.983  6674  6761 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 21:53:16.986  1034  1975 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 21:53:16.987  6674  6761 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-26 21:53:16.994  6674  6761 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-26 21:53:16.994  6674  6761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 21:53:16.994  6674  6761 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 21:53:16.994  6674  6761 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 21:53:16.994  6674  6761 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 21:53:16.994  6674  6761 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 21:53:16.994  6674  6761 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 21:53:16.994  6674  6761 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 21:53:16.994  6674  6761 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 21:53:16.994  6674  6761 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-26 21:53:16.995  6674  6761 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 21:53:16.995  6674  6761 I io.jxcore.node.LifeCycleMonitor: start: OK
08-26 21:53:16.998  6674  6674 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 21:53:17.000  6674  6674 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 21:53:17.040  6674  6674 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
08-26 21:53:17.056   341   354 E GBMv2   : DFP En is all cleared set to be enabled
08-26 21:53:17.056   341   354 E GBMv2   : Set value is all cleared set the max
08-26 21:53:17.056   341   354 I GBMv2   : DFP Enabled. Ignore VFP set
,08-26 21:53:17.347  1817  5197 I Icing   : Indexing 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4 from com.google.android.googlequicksearchbox
,08-26 21:53:17.405  1817  5197 D Icing   : Loaded CLD2 Version V2.0 - 20140131
,08-26 21:53:17.456  1817  5197 I Icing   : Indexing done 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4
,08-26 21:53:17.579  6694  6694 D LgDataFeature: LgDataFeature() Constructor: none
,08-26 21:53:17.579  6694  6694 D LgDataFeature: LgDataFeature() Constructor Done, null
08-26 21:53:17.737  6694  6694 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,08-26 21:53:17.756  1034  2030 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=6783 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,08-26 21:53:17.809  6783  6783 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,08-26 21:53:17.817  6783  6783 I LockScreenSettings: New app installed broadcast received ..
08-26 21:53:17.819  6783  6783 I LockScreenSettings: Number of installed packages  1
08-26 21:53:17.853  1034  1898 V SIM_STK : Menu title from STK is T-Mobile
,08-26 21:53:17.879  6674  6764 W jxcore-log: Initializing JXcore engine
08-26 21:53:17.879  6674  6764 W jxcore-log: JXcore engine is ready
,08-26 21:53:17.902  1034  1576 I ActivityManager: Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=6802 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-26 21:53:17.902  1034  1576 I ActivityManager: Killing 5604:com.lge.bnr/1000 (adj 15): empty #17
08-26 21:53:17.908   345   345 I art     : Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 214us total 10.522ms
08-26 21:53:17.918   345   345 I art     : Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 196us total 9.469ms
,08-26 21:53:17.919  6764  6764 W Thread-777: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[7368]" dev="sockfs" ino=7368 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-26 21:53:17.919  6764  6764 W Thread-777: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-26 21:53:17.929   345   345 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 206us total 10.452ms
08-26 21:53:17.919  6764  6764 W Thread-777: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[8581]" dev="sockfs" ino=8581 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-26 21:53:17.919  6764  6764 W Thread-777: type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-26 21:53:17.919  6764  6764 W Thread-777: type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[32803]" dev="sockfs" ino=32803 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
08-26 21:53:17.941  6674  6764 W jxcore-log: Starting JXcore engine
,08-26 21:53:17.972  1034  1050 W libprocessgroup: failed to open /acct/uid_1000/pid_5604/cgroup.procs: No such file or directory
,08-26 21:53:18.071  1034  1732 I art     : Explicit concurrent mark sweep GC freed 23147(1047KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/64MB, paused 1.921ms total 84.390ms
,08-26 21:53:18.076  6674  6764 W jxcore-log: Platform android
08-26 21:53:18.076  6674  6764 W jxcore-log: 
08-26 21:53:18.076  6674  6764 W jxcore-log: Process ARCH arm
08-26 21:53:18.076  6674  6764 W jxcore-log: 
08-26 21:53:18.096  6802  6802 D EulaProviderUpdateObserver: action : android.intent.action.PACKAGE_ADDED
08-26 21:53:18.096  6802  6802 D EulaProviderUpdateObserver: uri : package:com.test.thalitest
,08-26 21:53:18.118  1034  1576 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.BNRAppInstallReceiver: pid=6819 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
08-26 21:53:18.119  1034  1576 I ActivityManager: Killing 6158:com.google.android.gm/u0a64 (adj 15): empty #17
,08-26 21:53:18.192  1034  1975 W libprocessgroup: failed to open /acct/uid_10064/pid_6158/cgroup.procs: No such file or directory
,08-26 21:53:18.234  6819  6819 D [BNRAppListMgrReceiver]: android.intent.action.PACKAGE_ADDED : com.test.thalitest
,08-26 21:53:18.251  6819  6819 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-26 21:53:18.253  6448  6448 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.intent.action.PACKAGE_ADDED'.
08-26 21:53:18.295  1034  1995 I ActivityManager: Killing 5945:com.google.android.talk/u0a72 (adj 15): empty #17
,08-26 21:53:18.339  6674  6764 I jxcore-log: JXcore Cordova bridge is ready!
08-26 21:53:18.339  6674  6764 I jxcore-log: 
08-26 21:53:18.339  6674  6764 W jxcore-log: JXcore engine is started
,08-26 21:53:18.346  6674  6761 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-26 21:53:18.351  6674  6674 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-26 21:53:18.364  1034  1898 W libprocessgroup: failed to open /acct/uid_10072/pid_5945/cgroup.procs: No such file or directory
08-26 21:53:18.562  2803  2803 I MusicWidget: mDelayedStopHandler : unbind
,08-26 21:53:18.576  2172  2172 I MusicBrowser: [MediaPlaybackService.java:2869:onUnbind()] oooooo 
08-26 21:53:18.576  2172  2172 I MusicBrowser: [MediaPlaybackService.java:2076:saveQueue()] oooooo {full=true}
08-26 21:53:18.577  2172  2172 I MusicBrowser: [MediaPlaybackService.java:2081:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
,08-26 21:53:18.583  2172  2172 D MusicBrowser: [MediaPlaybackService.java:2161:saveQueue()] oooooo {queue=}
08-26 21:53:18.584  2172  2172 D MusicBrowser: [MediaPlaybackService.java:2163:saveQueue()] oooooo {mCardId=-1}
08-26 21:53:18.585  2172  2172 D MusicBrowser: [MediaPlaybackService.java:2198:saveQueue()] oooooo {curpos=-1}
08-26 21:53:18.588  2172  2172 I MusicBrowser: [MediaPlaybackService.java:2046:onDestroy()] oooooo 
08-26 21:53:18.590  2172  2172 I MusicBrowser: [MediaPlaybackService.java:8635:clearReceiver()] oooooo 
,08-26 21:53:18.593  1034  1614 I MediaFocusControl:  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@d333c44com.lge.music.MediaPlaybackService$5@1bc5912d
08-26 21:53:18.595  2172  2172 D MusicBrowser: [MediaPlaybackService.java:8669:clearReceiver()] oooooo abandonAudioFocus : 1
08-26 21:53:18.595  2172  2172 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-26 21:53:18.597  2172  2172 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-26 21:53:18.599  2172  2172 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-26 21:53:18.601  2172  2172 I MusicBrowser: [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$27@26abbcb2
08-26 21:53:18.602  2172  2172 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-26 21:53:18.602  2172  2172 I MusicBrowser: [MusicUtils.java:6801:endNotiTimer()] oooooo endNotiTimer
08-26 21:53:18.603  2172  2172 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-26 21:53:18.603  2172  2172 I MusicBrowser: [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
08-26 21:53:18.603  2172  2172 I MusicBrowser: [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
08-26 21:53:18.604  2172  2172 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-26 21:53:18.604  2172  2172 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-26 21:53:18.605  2172  2172 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-26 21:53:18.605  2172  2172 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-26 21:53:18.606  2172  2172 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-26 21:53:18.607  2172  2172 I MusicBrowser: [MusicUtils.java:10406:isAKACoverSupported()] oooooo aka not support!
08-26 21:53:18.608  2172  2172 I MusicBrowser: [MediaPlaybackService.java:6704:release()] oooooo 
08-26 21:53:18.608  2172  2172 I MusicBrowser: [MediaPlaybackService.java:6665:stop()] oooooo 
08-26 21:53:18.608  2172  2172 V MediaPlayer[Native]: reset
,08-26 21:53:18.614  2172  2172 V MediaPlayer[Native]: setListener
08-26 21:53:18.614  2172  2172 V MediaPlayer[Native]: disconnect
08-26 21:53:18.614  2172  2172 V MediaPlayer[Native]: destructor
08-26 21:53:18.617   319  2203 V AudioFlinger: releasing 18 from 2172 for -1
08-26 21:53:18.617   319  2203 V AudioFlinger:  decremented refcount to 0
08-26 21:53:18.617   319  2203 V AudioFlinger: purging stale effects
08-26 21:53:18.617  2172  2172 V MediaPlayer[Native]: disconnect
08-26 21:53:18.618  2172  2172 D MusicBrowser: [MusicUtils.java:615:getSmartShareVersion()] oooooo versionCode:305000
08-26 21:53:18.619  2172  2172 I SmartShareClient: [SmartShareManagerClient] smartshare client supported version code: 305000
08-26 21:53:18.619  2172  2172 I SmartShareClient: [SmartShareManagerClient] smartshare client enabled
08-26 21:53:18.620  2172  2172 I MusicBrowser: [MusicUtils.java:787:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000018
08-26 21:53:18.621  2172  2172 I MusicBrowser: [MusicUtils.java:635:getSmartShareVersion()] oooooo SmartshareVersion:953
08-26 21:53:18.621  2172  2172 V MusicBrowser: [MediaPlaybackService.java:9312:terminateSmartShareClient()] oooooo 
08-26 21:53:18.621  2172  2172 I SmartShareClient: [SmartShareManagerClient] unregisterListener: 992523874
08-26 21:53:18.621  2172  2172 W SmartShareClient: [SmartShareManagerClient] unregisterListener invalid listener: 992523874
08-26 21:53:18.631  2172  2172 I SmartShareClient: [SmartShareManagerClient] terminate service: 2172/MediaPlaybackService/578206568
,08-26 21:53:18.635  2172  2172 E HomeCloudIF: unregiterHomeCloudBroadcast(), Illegal argument.
08-26 21:53:18.635  2172  2172 I SmartShareClient: [SmartShareManagerClient] unbindService context:android.app.Application@9b3b3f3
08-26 21:53:18.639  2172  2172 V CloudHub: [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.2.1, versionCode=202001, state=0
08-26 21:53:18.639  2172  2172 V CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
08-26 21:53:18.640  2172  2172 I CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
08-26 21:53:18.641  2172  2172 D MusicBrowser: [MediaPlaybackService.java:9007:setStopForeground()] oooooo bValue : true
08-26 21:53:18.643  1034  1995 I ActivityManager: Killing 5729:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,08-26 21:53:18.663  2172  2172 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29978
,08-26 21:53:18.673  5704  5704 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
08-26 21:53:18.673  5704  5704 W System.err: android.os.DeadObjectException
08-26 21:53:18.673  5704  5704 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-26 21:53:18.674  5704  5704 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-26 21:53:18.674  5704  5704 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-26 21:53:18.674  5704  5704 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-26 21:53:18.674  5704  5704 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-26 21:53:18.674  5704  5704 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-26 21:53:18.674  5704  5704 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-26 21:53:18.674  5704  5704 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-26 21:53:18.674  5704  5704 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-26 21:53:18.674  5704  5704 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-26 21:53:18.674  5704  5704 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 21:53:18.674  5704  5704 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 21:53:18.674  5704  5704 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-26 21:53:18.674  5704  5704 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-26 21:53:18.674  5704  5704 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-26 21:53:18.674  5704  5704 W System.err: android.os.DeadObjectException
08-26 21:53:18.675  5704  5704 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-26 21:53:18.675  5704  5704 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-26 21:53:18.675  5704  5704 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-26 21:53:18.675  5704  5704 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-26 21:53:18.676  5704  5704 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-26 21:53:18.676  5704  5704 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-26 21:53:18.676  5704  5704 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-26 21:53:18.676  5704  5704 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-26 21:53:18.676  5704  5704 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-26 21:53:18.676  5704  5704 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-26 21:53:18.676  5704  5704 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 21:53:18.676  5704  5704 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 21:53:18.676  5704  5704 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-26 21:53:18.676  5704  5704 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-26 21:53:18.676  5704  5704 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-26 21:53:18.676  5704  5704 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
08-26 21:53:18.967  1034  1732 W libprocessgroup: failed to open /acct/uid_1000/pid_5729/cgroup.procs: No such file or directory
08-26 21:53:18.968  1034  1732 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,08-26 21:53:18.983  5704  5704 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-26 21:53:18.983  5704  5704 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-26 21:53:19.030  1034  2030 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=6850 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-26 21:53:19.034  5704  5704 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-26 21:53:19.080  6850  6850 D UEI.SmartControl: Quickset Services start...
08-26 21:53:19.082  6850  6850 I UEI.SmartControl: Manufacture = LGE
08-26 21:53:19.082  6850  6850 D UEI.SmartControl: Id = LGNevo
08-26 21:53:19.083  6850  6850 D UEI.SmartControl: File observer start...
,08-26 21:53:19.083  6850  6850 E UEI.SmartControl: IR Port is disabled: false
08-26 21:53:19.083  6850  6850 D UEI.SmartControl: Starting file observer...
08-26 21:53:19.083  6850  6850 D UEI.SmartControl: Extracting JNI libs...
08-26 21:53:19.084  6850  6850 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
,08-26 21:53:19.133  6850  6850 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
08-26 21:53:19.133  6850  6850 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-26 21:53:19.133  6850  6850 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,08-26 21:53:19.155  6850  6850 I UEI.SmartControl: --- Selecting new region: 6
08-26 21:53:19.156  6850  6850 I UEI.SmartControl: Model = LG-D855
08-26 21:53:19.157  6850  6850 D UEI.SmartControl: QS Service created
,08-26 21:53:19.166  6850  6850 I UEI.SmartControl: Service initServices...
,08-26 21:53:19.169  6850  6850 D UEI.SmartControl: QS start get config
,08-26 21:53:19.200  6850  6850 D UEI.SmartControl: Loading JNI Libs...
,08-26 21:53:19.484  6850  6850 I UEI.SmartControl: Supports setup maps: true
,08-26 21:53:19.488  6850  6850 D UEI.SmartControl: QS start statue = true Error code = 0
08-26 21:53:19.488  6850  6850 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-26 21:53:19.488  6850  6850 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-26 21:53:19.488  6850  6850 I UEI.SmartControl: ### init IR Blaster...
08-26 21:53:19.493  6850  6850 D serial_port: Configuring serial port
08-26 21:53:19.496  6850  6850 E UEI.SmartControl: UEIBLaster setting for 616
08-26 21:53:19.496  6850  6850 I UEI.SmartControl: Setting serial record hearder size = 2
08-26 21:53:19.497  6850  6850 I UEI.SmartControl: configuring settings for MAXQ616
08-26 21:53:19.497  6850  6850 I UEI.SmartControl: Get version...
,08-26 21:53:19.513  6850  6881 D UEI.SmartControl: serial port data available: 21
,08-26 21:53:19.541  6850  6850 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-26 21:53:19.541  6850  6850 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-26 21:53:19.542  6850  6850 I UEI.SmartControl: QS saving settings...
08-26 21:53:19.544  6850  6850 D UEI.SmartControl: IR Blaster version: 25672567
,08-26 21:53:19.563  6850  6881 D UEI.SmartControl: serial port data available: 4
,08-26 21:53:19.594  6850  6884 I UEI.SmartControl: Device manager: loading config....
08-26 21:53:19.595  6850  6884 D UEI.SmartControl: ----------- loading internal config...
08-26 21:53:19.595  6850  6850 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-26 21:53:19.596  6850  6850 E UEI.SmartControl: Services init done
08-26 21:53:19.596  6850  6850 D UEI.SmartControl: QS Service init finished
08-26 21:53:19.597  6850  6850 D UEI.SmartControl: QS Service version name: 2.1.91
08-26 21:53:19.597  6850  6850 D UEI.SmartControl: QS Service version code: 201091
08-26 21:53:19.597  6850  6850 D UEI.SmartControl: Service requested: Control
,08-26 21:53:19.602  6850  6884 E UEI.SmartControl: Loading SETTINGS...
08-26 21:53:19.603  6850  6850 D UEI.SmartControl: Request IControl service: devices are loaded...
08-26 21:53:19.605  1034  1898 I ActivityManager: Killing 5704:com.lge.qremote/u0a112 (adj 15): empty #17
08-26 21:53:19.607  6850  6884 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-26 21:53:19.614  6850  6883 I UEI.SmartControl: Notify AllClients services are ready: 0
08-26 21:53:19.614  6850  6883 D UEI.SmartControl: -----service ready thread exits
,08-26 21:53:19.732  1034  1959 W libprocessgroup: failed to open /acct/uid_10112/pid_5704/cgroup.procs: No such file or directory
,08-26 21:53:19.736  6850  6850 D UEI.SmartControl: Internal service binding...
08-26 21:53:21.650  6694  6694 W GAV2    : Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,08-26 21:53:21.656  1034  1614 I ActivityManager: Killing 5648:com.android.calendar/u0a13 (adj 15): empty #17
08-26 21:53:21.724  1034  1050 W libprocessgroup: failed to open /acct/uid_10013/pid_5648/cgroup.procs: No such file or directory
,08-26 21:53:22.651  6694  6771 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,08-26 21:53:24.595  6850  6885 D UEI.SmartControl: Internal timer expired: 1
,08-26 21:53:24.599  6850  6885 D UEI.SmartControl: unbind internal service
,08-26 21:53:24.610  6850  6850 D UEI.SmartControl: Service.onUnbind: IControl
,08-26 21:53:24.615  6850  6850 D UEI.SmartControl: Service.onDestroy
,08-26 21:53:24.615  6850  6850 D UEI.SmartControl: Lock is in USE false
08-26 21:53:24.615  6850  6850 D UEI.SmartControl: unbind internal service
08-26 21:53:24.616  6850  6882 D serial_port: close(fd = 25)
08-26 21:53:24.619  6850  6882 I UEI.SmartControl: Serial port is closed.
08-26 21:53:24.620  6850  6850 I UEI.SmartControl: Serial port is closed.
08-26 21:53:24.620  6850  6850 I UEI.SmartControl: Serial port is closed.
08-26 21:53:24.620  6850  6850 D UEI.SmartControl: Blaster closed
08-26 21:53:24.620  6850  6850 D UEI.SmartControl: Shut down QS...
08-26 21:53:24.620  6850  6850 D UEI.SmartControl: Stopping QS lib
08-26 21:53:24.620  6850  6850 D UEI.SmartControl: QS lib stop result = true
08-26 21:53:24.621  6850  6850 D UEI.SmartControl: Stopped QS lib
08-26 21:53:24.621  6850  6850 D UEI.SmartControl: Stopped file observer...
08-26 21:53:24.621  6850  6850 D UEI.SmartControl: QS shutdown complete
,08-26 21:53:28.097  6674  6764 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-26 21:53:28.097  6674  6764 I jxcore-log: 
,08-26 21:53:28.099  6674  6764 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-26 21:53:28.099  6674  6764 I jxcore-log: 
08-26 21:53:28.105  6674  6764 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 21:53:28.105  6674  6764 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 21:53:28.105  6674  6764 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 21:53:28.105  6674  6764 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 21:53:28.105  6674  6764 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 21:53:28.105  6674  6764 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 21:53:28.105  6674  6764 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 21:53:28.105  6674  6764 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 21:53:28.107  6674  6764 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 21:53:28.109  6674  6764 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-26 21:53:28.109  6674  6764 I jxcore-log: 
,08-26 21:53:28.111  6674  6764 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-26 21:53:28.111  6674  6764 I jxcore-log: 
08-26 21:53:28.617  6674  6764 D executeNativeTests: Running unit tests
,08-26 21:53:28.672  2172  2172 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19969
,08-26 21:53:28.699  6674  6764 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-26 21:53:28.699  6674  6764 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2cc9faf1 added. We now have 2 listener(s)
08-26 21:53:28.700  1034  2006 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 21:53:28.702  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-26 21:53:28.702  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 21:53:28.702  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 21:53:28.702  6674  6764 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 21:53:28.702  6674  6764 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23db76d6 added. We now have 2 listener(s)
08-26 21:53:28.702  6674  6764 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 21:53:28.702  6674  6764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-26 21:53:28.705  6674  6764 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 21:53:28.707  6674  6764 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 21:53:28.707  6674  6764 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 21:53:28.707  6674  6764 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 21:53:28.707  6674  6764 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true,
08-26 21:53:28.707  6674  6764 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 21:53:28.707  6674  6764 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e,
08-26 21:53:28.707  6674  6764 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 21:53:28.707  6674  6764 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 21:53:28.708  6674  6764 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 21:53:28.708  6674  6764 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 21:53:28.709  6674  6674 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 21:53:28.710  6674  6674 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 21:53:28.712  6674  6764 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-26 21:53:28.712  6674  6764 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-26 21:53:28.712  6674  6764 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-26 21:53:28.713  6674  6764 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out,
,08-26 21:53:28.714  6674  6764 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-26 21:53:28.714  6674  6764 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-26 21:53:28.714  6674  6764 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-26 21:53:28.714  6674  6764 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-26 21:53:28.714  6674  6764 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 21:53:28.715  6674  6764 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 21:53:28.715  6674  6764 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 21:53:28.715  6674  6764 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 21:53:28.716  6674  6764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:28.716  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 21:53:28.716  6674  6764 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 21:53:28.716  6674  6764 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2cc9faf1 removed from the list
08-26 21:53:28.716  6674  6764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:53:28.716  6674  6764 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23db76d6 removed from the list
08-26 21:53:28.716  6674  6764 D io.jxcore.node.ConnectivityMonitor: stop
08-26 21:53:28.716  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:53:28.716  6674  6764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:28.717  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:53:28.717  6674  6764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 21:53:28.717  6674  6764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 21:53:28.717  6674  6764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:53:28.717  6674  6764 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23db76d6 not in the list
08-26 21:53:28.718  6674  6764 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-26 21:53:28.719  6674  6764 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 21:53:28.719  6674  6764 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 21:53:28.719  6674  6764 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-26 21:53:28.719  6674  6764 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
08-26 21:53:28.719  6674  6764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:28.719  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:53:28.719  6674  6764 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2cc9faf1 not in the list
08-26 21:53:28.719  6674  6764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 21:53:28.719  6674  6764 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23db76d6 not in the list
08-26 21:53:28.719  6674  6764 D io.jxcore.node.ConnectivityMonitor: stop
08-26 21:53:28.719  6674  6764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:28.719  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:53:28.719  6674  6764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 21:53:28.719  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:53:28.720  6674  6764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 21:53:28.720  6674  6764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 21:53:28.720  6674  6764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-26 21:53:28.720  6674  6764 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23db76d6 not in the list
08-26 21:53:28.724  6674  6764 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-26 21:53:28.724  6674  6764 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-26 21:53:28.724  6674  6764 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110],
08-26 21:53:28.724  6674  6764 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-26 21:53:28.724  6674  6764 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-26 21:53:28.724  6674  6764 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-26 21:53:28.724  6674  6764 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-26 21:53:28.724  6674  6764 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,08-26 21:53:28.724  6674  6764 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-26 21:53:28.724  6674  6764 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-26 21:53:28.724  6674  6764 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-26 21:53:28.724  6674  6764 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-26 21:53:28.724  6674  6764 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110],
08-26 21:53:28.724  6674  6764 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-26 21:53:28.724  6674  6764 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-26 21:53:28.724  6674  6764 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-26 21:53:28.724  6674  6764 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510],
08-26 21:53:28.724  6674  6764 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-26 21:53:28.724  6674  6764 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-26 21:53:28.724  6674  6764 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-26 21:53:28.724  6674  6764 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-26 21:53:28.724  6674  6764 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010],
,08-26 21:53:28.724  6674  6764 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-26 21:53:28.724  6674  6764 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-26 21:53:28.724  6674  6764 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-26 21:53:28.724  6674  6764 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
,08-26 21:53:28.724  6674  6764 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-26 21:53:28.724  6674  6764 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-26 21:53:28.724  6674  6764 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-26 21:53:28.725  6674  6764 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-26 21:53:28.725  6674  6764 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,08-26 21:53:28.725  6674  6764 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 21:53:28.725  6674  6764 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 21:53:28.725  6674  6764 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 21:53:28.726  6674  6764 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 21:53:28.726  6674  6764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 21:53:28.726  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:53:28.726  6674  6764 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2cc9faf1 not in the list
08-26 21:53:28.726  6674  6764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 21:53:28.726  6674  6764 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23db76d6 not in the list,
08-26 21:53:28.726  6674  6764 D io.jxcore.node.ConnectivityMonitor: stop
08-26 21:53:28.726  6674  6764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:28.726  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
08-26 21:53:28.726  6674  6764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:28.726  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:53:28.727  6674  6764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 21:53:28.727  6674  6764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-26 21:53:28.727  6674  6764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:53:28.727  6674  6764 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23db76d6 not in the list
08-26 21:53:28.728  6674  6764 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-26 21:53:28.729  6674  6764 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 21:53:28.732  6674  6764 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
,08-26 21:53:28.732  6674  6764 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 21:53:28.732  6674  6764 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 21:53:28.732  6674  6764 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 21:53:28.732  6674  6764 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 21:53:28.732  6674  6764 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 21:53:28.732  6674  6764 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 21:53:28.732  6674  6764 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 21:53:28.733  6674  6764 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 21:53:28.733  6674  6764 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 21:53:28.734  6674  6674 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 21:53:28.735  6674  6674 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 21:53:28.735  6674  6764 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 21:53:28.735  6674  6764 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-26 21:53:28.735  6674  6764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 21:53:28.735  6674  6764 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 21:53:28.735  6674  6764 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-26 21:53:28.738  6674  6764 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-26 21:53:28.738  1034  1050 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-26 21:53:28.741  6674  6764 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-26 21:53:28.745  6674  6764 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-26 21:53:28.746  6674  6764 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
08-26 21:53:28.746  6674  6764 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-26 21:53:28.747  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 21:53:28.748  6674  6764 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-26 21:53:28.748  6674  6764 I io.jxcore.node.ConnectionHelper: start: OK
08-26 21:53:28.750  6674  6764 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 21:53:28.750  6674  6764 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 21:53:28.750  6674  6764 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 21:53:28.750  6674  6764 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 21:53:28.750  6674  6764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:28.750  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 21:53:28.750  6674  6764 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2cc9faf1 not in the list
08-26 21:53:28.750  6674  6764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:53:28.750  6674  6764 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23db76d6 not in the list
08-26 21:53:28.750  6674  6764 D io.jxcore.node.ConnectivityMonitor: stop
08-26 21:53:28.750  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:53:28.751  6674  6764 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-26 21:53:28.751  6674  6764 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 21:53:28.753  6674  6764 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 21:53:28.753  6674  6764 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 21:53:28.753  6674  6764 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 21:53:28.753  6674  6764 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 21:53:28.753  6674  6764 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 21:53:28.753  6674  6764 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 21:53:28.753  6674  6764 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 21:53:28.753  6674  6764 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 21:53:28.754  6674  6764 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 21:53:28.754  6674  6764 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 21:53:28.754  6674  6764 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 21:53:28.754  6674  6764 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 21:53:28.754  6674  6764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 21:53:28.754  6674  6764 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 21:53:28.755  6674  6764 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-26 21:53:28.758  6674  6674 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 21:53:28.759  6674  6674 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 21:53:28.759  6674  6764 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-26 21:53:28.760  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 21:53:28.760  6674  6764 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-26 21:53:28.761  6674  6764 I io.jxcore.node.ConnectionHelper: start: OK
08-26 21:53:28.762  6674  6764 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 21:53:28.762  6674  6764 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 21:53:28.762  6674  6764 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 21:53:28.762  6674  6764 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 21:53:28.762  6674  6764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:28.762  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 21:53:28.762  6674  6764 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2cc9faf1 not in the list
08-26 21:53:28.762  6674  6764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:53:28.762  6674  6764 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23db76d6 not in the list
08-26 21:53:28.762  6674  6764 D io.jxcore.node.ConnectivityMonitor: stop
08-26 21:53:28.762  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:53:28.763  6674  6764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:28.763  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:53:28.763  6674  6764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 21:53:28.763  6674  6764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 21:53:28.764  6674  6764 D BluetoothLeScann,er: could not find callback wrapper
08-26 21:53:28.764  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 21:53:28.765  6674  6764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:53:28.765  6674  6764 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23db76d6 not in the list
08-26 21:53:28.765  6674  6764 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-26 21:53:28.766  6674  6764 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 21:53:28.768  6674  6764 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 21:53:28.768  6674  6764 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 21:53:28.768  6674  6764 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 21:53:28.768  6674  6764 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 21:53:28.768  6674  6764 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 21:53:28.768  6674  6764 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 21:53:28.768  6674  6764 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 21:53:28.768  6674  6764 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 21:53:28.769  6674  6764 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 21:53:28.769  6674  6764 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 21:53:28.770  6674  6764 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 21:53:28.770  6674  6764 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 21:53:28.770  6674  6674 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 21:53:28.770  6674  6764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 21:53:28.770  6674  6764 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 21:53:28.770  6674  6764 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-26 21:53:28.772  6674  6674 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 21:53:28.773  6674  6764 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-26 21:53:28.773  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 21:53:28.774  6674  6764 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-26 21:53:28.774  6674  6764 I io.jxcore.node.ConnectionHelper: start: OK
08-26 21:53:28.774  6674  6764 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 21:53:28.774  6674  6764 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 21:53:28.774  6674  6764 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 21:53:28.775  6674  6764 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 21:53:28.775  6674  6764 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 21:53:28.775  6674  6764 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 21:53:28.775  6674  6764 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 21:53:28.775  6674  6764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:28.775  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 21:53:28.775  6674  6764 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2cc9faf1 not in the list
08-26 21:53:28.775  6674  6764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:53:28.775  6674  6764 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23db76d6 not in the list
08-26 21:53:28.775  6674  6764 D io.jxcore.node.ConnectivityMonitor: stop
08-26 21:53:28.775  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:53:28.775  6674  6764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:28.775  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:53:28.776  6674  6764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 21:53:28.776  6674  6764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 21:53:28.776  6674  6764 D BluetoothLeScanner: could not find callback wrapper
08-26 21:53:28.776  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 21:53:28.776  6674  6764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:53:28.776  6674  6764 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23db76d6 not in the list
08-26 21:53:28.777  6674  6764 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-26 21:53:28.777  6674  6764 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 21:53:28.777  6674  6764 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 21:53:28.777  6674  6764 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 21:53:28.777  6674  6764 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 21:53:28.777  6674  6764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:28.777  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:53:28.777  6674  6764 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2cc9faf1 not in the list
08-26 21:53:28.777  6674  6764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:53:28.777  6674  6764 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23db76d6 not in the list
08-26 21:53:28.777  6674  6764 D io.jxcore.node.ConnectivityMonitor: stop
08-26 21:53:28.777  6674  6764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:28.777  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:53:28.777  6674  6764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:28.777  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:53:28.778  6674  6764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 21:53:28.778  6674  6764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 21:53:28.778  6674  6764 D BluetoothLeScanner: could not find callback wrapper
08-26 21:53:28.778  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 21:53:28.778  6674  6764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:53:28.778  6674  6764 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23db76d6 not in the list
08-26 21:53:28.779  6674  6764 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-26 21:53:28.779  6674  6764 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 21:53:28.779  6674  6764 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 21:53:28.779  6674  6764 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 21:53:28.780  6674  6764 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 21:53:28.780  6674  6764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:28.780  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:53:28.780  6674  6764 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2cc9faf1 not in the list
08-26 21:53:28.780  6674  6764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:53:28.780  6674  6764 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23db76d6 not in the list
08-26 21:53:28.780  6674  6764 D io.jxcore.node.ConnectivityMonitor: stop
08-26 21:53:28.780  6674  6764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:28.780  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:53:28.780  6674  6764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:28.780  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:53:28.780  6674  6764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 21:53:28.781  6674  6764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 21:53:28.781  6674  6764 D BluetoothLeScanner: could not find callback wrapper
08-26 21:53:28.781  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 21:53:28.781  6674  6764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:53:28.781  6674  6764 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23db76d6 not in the list
08-26 21:53:28.781  6674  6764 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-26 21:53:28.782  6674  6764 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 21:53:28.782  6674  6764 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 21:53:28.782  6674  6764 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 21:53:28.782  6674  6764 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 21:53:28.782  6674  6764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:28.782  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:53:28.782  6674  6764 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2cc9faf1 not in the list
08-26 21:53:28.782  6674  6764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:53:28.782  6674  6764 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23db76d6 not in the list
08-26 21:53:28.782  6674  6764 D io.jxcore.node.ConnectivityMonitor: stop
08-26 21:53:28.782  6674  6764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:28.782  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:53:28.782  6674  6764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:28.782  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:53:28.783  6674  6764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 21:53:28.783  6674  6764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 21:53:28.783  6674  6764 D BluetoothLeScanner: could not find callback wrapper
08-26 21:53:28.783  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 21:53:28.783  6674  6764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:53:28.783  6674  6764 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23db76d6 not in the list
08-26 21:53:28.784  6674  6764 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-26 21:53:28.784  6674  6764 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 21:53:28.784  6674  6764 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 21:53:28.784  6674  6764 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 21:53:28.784  6674  6764 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 21:53:28.784  6674  6764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:28.784  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:53:28.784  6674  6764 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2cc9faf1 not in the list
08-26 21:53:28.784  6674  6764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:53:28.784  6674  6764 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23db76d6 not in the list
08-26 21:53:28.784  6674  6764 D io.jxcore.node.ConnectivityMonitor: stop
08-26 21:53:28.784  6674  6764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:28.784  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:53:28.784  6674  6764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:28.784  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:53:28.785  6674  6764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 21:53:28.785  6674  6764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 21:53:28.786  6674  6764 D BluetoothLeScanner: could not find callback wrapper
08-26 21:53:28.786  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 21:53:28.786  6674  6764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:53:28.786  6674  6764 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23db76d6 not in the list
08-26 21:53:28.786  6674  6764 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-26 21:53:28.786  6674  6764 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-26 21:53:28.787  6674  6764 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-26 21:53:28.787  6674  6764 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-26 21:53:28.787  6674  6764 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-26 21:53:28.787  6674  6764 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-26 21:53:28.787  6674  6764 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 21:53:28.787  6674  6764 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 21:53:28.787  6674  6764 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 21:53:28.787  6674  6764 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 21:53:28.787  6674  6764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:28.787  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:53:28.787  6674  6764 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2cc9faf1 not in the list
08-26 21:53:28.787  6674  6764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:53:28.787  6674  6764 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23db76d6 not in the list
08-26 21:53:28.787  6674  6764 D io.jxcore.node.ConnectivityMonitor: stop
08-26 21:53:28.787  6674  6764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:28.787  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:53:28.787  6674  6764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:28.787  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:53:28.788  6674  6764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 21:53:28.788  6674  6764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 21:53:28.789  6674  6764 D BluetoothLeScanner: could not find callback wrapper
08-26 21:53:28.789  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 21:53:28.789  6674  6764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:53:28.789  6674  6764 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23db76d6 not in the list
08-26 21:53:28.789  6674  6764 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 21:53:28.789  6674  6764 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-26 21:53:28.789  6674  6764 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-26 21:53:28.791  6674  6764 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 21:53:28.791  6674  6764 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-26 21:53:28.791  6674  6764 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-26 21:53:28.791  6674  6764 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-26 21:53:28.791  6674  6764 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-26 21:53:28.791  6674  6764 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-26 21:53:28.791  6674  6764 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-26 21:53:28.791  6674  6764 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-26 21:53:28.791  6674  6764 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-26 21:53:28.791  6674  6764 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-26 21:53:28.791  6674  6764 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-26 21:53:28.791  6674  6764 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-26 21:53:28.791  6674  6764 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-26 21:53:28.791  6674  6764 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-26 21:53:28.791  6674  6764 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-26 21:53:28.791  6674  6764 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-26 21:53:28.791  6674  6764 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-26 21:53:28.791  6674  6764 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-26 21:53:28.791  6674  6764 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-26 21:53:28.791  6674  6764 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-26 21:53:28.792  6674  6764 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-26 21:53:28.792  6674  6764 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-26 21:53:28.792  6674  6764 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-26 21:53:28.792  6674  6764 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-26 21:53:28.792  6674  6764 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-26 21:53:28.792  6674  6764 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-26 21:53:28.792  6674  6764 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-26 21:53:28.792  6674  6764 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-26 21:53:28.792  6674  6764 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-26 21:53:28.792  6674  6764 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-26 21:53:28.792  6674  6764 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-26 21:53:28.792  6674  6764 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-26 21:53:28.792  6674  6764 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-26 21:53:28.792  6674  6764 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-26 21:53:28.792  6674  6764 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-26 21:53:28.792  6674  6764 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 21:53:28.792  6674  6764 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-26 21:53:28.792  6674  6764 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-26 21:53:28.792  6674  6764 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 21:53:28.792  6674  6764 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-26 21:53:28.792  6674  6764 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-26 21:53:28.793  6674  6764 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-26 21:53:28.794  6674  6764 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-26 21:53:28.794  6674  6764 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-26 21:53:28.795  6674  6764 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-26 21:53:28.795  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-26 21:53:28.795  6674  6764 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-26 21:53:28.795  6674  6764 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 21:53:28.795  6674  6764 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-26 21:53:28.796  6674  6764 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 21:53:28.796  6674  6764 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 21:53:28.796  6674  6764 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 21:53:28.796  6674  6897 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 841)
08-26 21:53:28.801  6674  6764 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 21:53:28.801  6674  6764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:28.802  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:53:28.802  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-26 21:53:28.802  6674  6764 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2cc9faf1 not in the list
08-26 21:53:28.802  6674  6764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:53:28.802  6674  6764 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23db76d6 not in the list
08-26 21:53:28.802  6674  6764 D io.jxcore.node.ConnectivityMonitor: stop
08-26 21:53:28.802  6674  6764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:28.802  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:53:28.802  6674  6764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:28.802  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:53:28.803  6674  6898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 841
08-26 21:53:28.803  6674  6898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 841)
08-26 21:53:28.803  6674  6898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 841)
08-26 21:53:28.803  6674  6764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 21:53:28.803  6674  6764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 21:53:28.803  6674  6764 D BluetoothLeScanner: could not find callback wrapper
08-26 21:53:28.803  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 21:53:28.803  6674  6764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:53:28.803  6674  6764 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23db76d6 not in the list
08-26 21:53:28.804  6674  6764 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
,08-26 21:53:28.804  6674  6764 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 21:53:28.804  6674  6764 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 21:53:28.804  6674  6764 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 21:53:28.804  6674  6764 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 21:53:28.804  6674  6764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:28.804  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:53:28.804  6674  6764 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2cc9faf1 not in the list
08-26 21:53:28.804  6674  6764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:53:28.804  6674  6764 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23db76d6 not in the list
08-26 21:53:28.804  6674  6764 D io.jxcore.node.ConnectivityMonitor: stop
08-26 21:53:28.804  6674  6764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:28.804  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:53:28.805  6674  6764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:28.805  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:53:28.805  6674  6764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 21:53:28.805  6674  6764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 21:53:28.805  6674  6764 D BluetoothLeScanner: could not find callback wrapper
08-26 21:53:28.805  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 21:53:28.805  6674  6764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:53:28.805  6674  6764 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23db76d6 not in the list
08-26 21:53:28.806  6674  6764 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-26 21:53:28.806  6674  6764 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 21:53:28.806  6674  6764 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 21:53:28.806  6674  6764 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 21:53:28.807  6674  6764 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 21:53:28.807  6674  6764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:28.807  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:53:28.807  6674  6764 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2cc9faf1 not in the list
08-26 21:53:28.807  6674  6764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:53:28.807  6674  6764 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23db76d6 not in the list
08-26 21:53:28.807  6674  6764 D io.jxcore.node.ConnectivityMonitor: stop
08-26 21:53:28.807  6674  6764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:28.807  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:53:28.807  6674  6764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:28.807  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:53:28.808  6674  6764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 21:53:28.808  6674  6764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 21:53:28.808  6674  6764 D BluetoothLeScanner: could not find callback wrapper
08-26 21:53:28.808  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 21:53:28.808  6674  6764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:53:28.808  6674  6764 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23db76d6 not in the list
08-26 21:53:28.809  6674  6764 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-26 21:53:28.809  6674  6764 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-26 21:53:28.809  6674  6764 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-26 21:53:28.809  6674  6764 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-26 21:53:28.809  6674  6764 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-26 21:53:28.809  6674  6764 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-26 21:53:28.809  6674  6764 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-26 21:53:28.811  6674  6764 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-26 21:53:28.811  6674  6764 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-26 21:53:28.811  6674  6764 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-26 21:53:28.811  6674  6764 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-26 21:53:28.811  6674  6764 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-26 21:53:28.811  6674  6764 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 21:53:28.811  6674  6764 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 21:53:28.811  6674  6764 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 21:53:28.811  6674  6764 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 21:53:28.811  6674  6764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:28.811  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:53:28.811  6674  6764 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2cc9faf1 not in the list
08-26 21:53:28.811  6674  6764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:53:28.811  6674  6764 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23db76d6 not in the list
08-26 21:53:28.811  6674  6764 D io.jxcore.node.ConnectivityMonitor: stop
08-26 21:53:28.811  6674  6764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:28.811  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:53:28.811  6674  6764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:28.811  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:53:28.812  6674  6764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 21:53:28.812  6674  6764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 21:53:28.812  6674  6764 D BluetoothLeScanner: could not find callback wrapper
08-26 21:53:28.812  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 21:53:28.812  6674  6764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:53:28.812  6674  6764 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23db76d6 not in the list
08-26 21:53:28.813  6674  6764 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 21:53:28.813  6674  6764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:28.813  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:53:28.813  6674  6764 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2cc9faf1 not in the list
08-26 21:53:28.813  6674  6764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:53:28.813  6674  6764 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23db76d6 not in the list
08-26 21:53:28.813  6674  6764 D io.jxcore.node.ConnectivityMonitor: stop
08-26 21:53:28.813  6674  6764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:28.813  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:53:28.813  6674  6764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:53:28.813  6674  6764 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23db76d6 not in the list
08-26 21:53:28.813  6674  6764 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 21:53:28.813  6674  6764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:28.814  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:53:28.814  6674  6764 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2cc9faf1 not in the list
08-26 21:53:28.814  6674  6764 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 21:53:28.814  6674  6764 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 21:53:28.814  6674  6764 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 21:53:28.814  6674  6764 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 21:53:28.814  6674  6764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:28.814  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:53:28.814  6674  6764 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2cc9faf1 not in the list
08-26 21:53:28.814  6674  6764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:53:28.814  6674  6764 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23db76d6 not in the list
08-26 21:53:28.814  6674  6764 D io.jxcore.node.ConnectivityMonitor: stop
08-26 21:53:28.814  6674  6764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:28.814  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:53:28.814  6674  6764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:28.814  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:53:28.822  6674  6764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 21:53:28.822  6674  6764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 21:53:28.825  6674  6764 D BluetoothLeScanner: could not find callback wrapper
08-26 21:53:28.825  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 21:53:28.825  6674  6764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:53:28.825  6674  6764 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23db76d6 not in the list
08-26 21:53:28.827  6674  6764 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-26 21:53:28.828  6674  6764 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 21:53:28.831  6674  6764 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-26 21:53:28.832  6674  6764 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-26 21:53:28.832  6674  6764 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-26 21:53:28.833  6674  6674 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-26 21:53:28.833  6674  6764 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-26 21:53:28.833  6674  6764 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-26 21:53:28.833  1034  1995 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 21:53:28.834  6674  6764 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 21:53:28.834  6674  6764 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-26 21:53:28.834  6674  6899 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 21:53:28.834  6674  6764 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-26 21:53:28.834  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-26 21:53:28.834  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:53:28.834  6674  6764 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-26 21:53:28.834  6674  6764 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2cc9faf1 not in the list
08-26 21:53:28.834  6674  6764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:53:28.834  6674  6674 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-26 21:53:28.834  6674  6764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 21:53:28.834  6674  6764 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 21:53:28.834  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 21:53:28.835  4290  4308 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=84 mFd=82
08-26 21:53:28.835  6674  6899 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-26 21:53:28.835  6674  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-26 21:53:28.835  6674  6899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-26 21:53:28.835  6674  6674 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-26 21:53:28.836  6674  6764 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-26 21:53:28.836  6674  6764 D BluetoothLeScanner: could not find callback wrapper
08-26 21:53:28.836  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 21:53:28.836  6674  6764 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-26 21:53:28.837  6674  6764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:28.837  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 21:53:28.837  6674  6764 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false,
08-26 21:53:28.837  6674  6674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 21:53:28.838  6674  6674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-26 21:53:28.838  6674  6674 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 21:53:28.838  6674  6764 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23db76d6 not in the list
08-26 21:53:28.838  6674  6764 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 21:53:28.838  6674  6764 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 21:53:28.838  6674  6764 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 21:53:28.838  6674  6764 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 21:53:28.838  6674  6764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 21:53:28.838  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:53:28.838  6674  6764 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2cc9faf1 not in the list
08-26 21:53:28.838  6674  6764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 21:53:28.838  6674  6764 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23db76d6 not in the list
08-26 21:53:28.838  6674  6764 D io.jxcore.node.ConnectivityMonitor: stop
08-26 21:53:28.838  6674  6764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:28.838  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 21:53:28.838  6674  6764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:28.838  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:53:28.839  6674  6764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 21:53:28.839  6674  6764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-26 21:53:28.839  6674  6764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:53:28.839  6674  6764 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23db76d6 not in the list
08-26 21:53:28.840  6674  6764 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
,08-26 21:53:28.840  6674  6764 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-26 21:53:28.840  6674  6764 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-26 21:53:28.840  6674  6764 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-26 21:53:28.840  6674  6764 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 21:53:28.840  6674  6764 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 21:53:28.840  6674  6764 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 21:53:28.841  6674  6764 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 21:53:28.841  6674  6764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 21:53:28.841  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:53:28.841  6674  6764 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2cc9faf1 not in the list
08-26 21:53:28.841  6674  6764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:53:28.841  6674  6764 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23db76d6 not in the list,
08-26 21:53:28.841  6674  6764 D io.jxcore.node.ConnectivityMonitor: stop
08-26 21:53:28.841  6674  6764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:28.841  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 21:53:28.841  6674  6764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:28.841  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:53:28.842  6674  6764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 21:53:28.842  6674  6764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-26 21:53:28.842  6674  6764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:53:28.842  6674  6764 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23db76d6 not in the list
08-26 21:53:28.842  1034  1614 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 21:53:28.843  1034  1975 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0,
08-26 21:53:28.843  1034  2033 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 21:53:28.844  6674  6764 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 21:53:28.844  6674  6764 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-26 21:53:28.844  6674  6764 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 21:53:28.844  6674  6764 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 21:53:28.844  6674  6764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:28.844  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 21:53:28.844  6674  6764 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2cc9faf1 not in the list
08-26 21:53:28.844  6674  6764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:53:28.844  6674  6764 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23db76d6 not in the list
08-26 21:53:28.844  6674  6764 D io.jxcore.node.ConnectivityMonitor: stop
08-26 21:53:28.844  6674  6764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-26 21:53:28.844  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:53:28.844  6674  6764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:28.844  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:53:28.845  6674  6764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 21:53:28.845  6674  6764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 21:53:28.845  6674  6764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:53:28.845  6674  6764 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23db76d6 not in the list
08-26 21:53:28.845  6674  6764 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 21:53:28.845  6674  6764 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 21:53:28.845  6674  6764 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 21:53:28.845  6674  6764 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 21:53:28.845  6674  6764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 21:53:28.845  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:53:28.846  6674  6764 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2cc9faf1 not in the list
08-26 21:53:28.846  6674  6764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:53:28.846  6674  6764 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23db76d6 not in the list
,08-26 21:53:28.846  6674  6764 D io.jxcore.node.ConnectivityMonitor: stop
08-26 21:53:28.846  6674  6764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:28.846  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:53:28.846  6674  6764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:28.846  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 21:53:28.846  6674  6764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 21:53:28.846  6674  6764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 21:53:28.846  6674  6764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:53:28.846  6674  6764 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23db76d6 not in the list
08-26 21:53:28.847  6674  6764 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing,
08-26 21:53:28.847  6674  6764 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-26 21:53:28.847  6674  6764 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-26 21:53:28.847  6674  6764 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-26 21:53:28.847  6674  6764 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
,08-26 21:53:28.847  6674  6764 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-26 21:53:28.849  6674  6764 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-26 21:53:28.849  6674  6764 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-26 21:53:28.849  6674  6764 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-26 21:53:28.849  6674  6764 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-26 21:53:28.850  6674  6764 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
,08-26 21:53:28.850  6674  6764 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-26 21:53:28.850  6674  6764 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-26 21:53:28.850  6674  6764 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-26 21:53:28.850  6674  6764 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-26 21:53:28.850  6674  6764 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-26 21:53:28.851  6674  6764 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id,
08-26 21:53:28.851  6674  6764 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-26 21:53:28.851  6674  6764 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-26 21:53:28.851  6674  6764 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-26 21:53:28.852  6674  6764 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 21:53:28.852  6674  6764 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3472404f added. We now have 2 listener(s)
,08-26 21:53:28.852  6674  6764 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 21:53:28.856  6674  6764 D BluetoothAdapter: enable(): BT is already enabled..!
08-26 21:53:28.857  1034  2033 D WifiServiceImplEx: setWifiEnabled: true pid=6674, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-26 21:53:28.857  1034  2033 D WifiService: setWifiEnabled: true pid=6674, uid=10118
,08-26 21:53:28.857  1034  2033 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-26 21:53:28.858  6674  6897 W LGMDMUISystemServiceAdapter: checkBluetoothPairing btPolicy: false
08-26 21:53:28.859  6674  6764 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 21:53:28.859  6674  6897 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 841)
08-26 21:53:28.859  6674  6764 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3057a3dc added. We now have 3 listener(s)
08-26 21:53:28.859  6674  6764 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 21:53:28.861  6674  6764 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 21:53:28.861  6674  6764 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2165fce5 added. We now have 4 listener(s)
08-26 21:53:28.861  6674  6764 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 21:53:28.862  6674  6764 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 21:53:28.862  6674  6764 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@998a3ba added. We now have 5 listener(s)
08-26 21:53:28.862  6674  6764 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 21:53:28.864  1034  1732 D WifiServiceImplEx: setWifiEnabled: false pid=6674, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-26 21:53:28.864  1034  1732 D WifiService: setWifiEnabled: false pid=6674, uid=10118
08-26 21:53:28.864  1034  1732 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-26 21:53:28.881  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-26 21:53:28.881  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-26 21:53:28.881  1034  1034 D Ulp_jni : JNI:system_update. Event-4
08-26 21:53:28.882  1034  1537 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-26 21:53:28.882  1034  1537 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-26 21:53:28.882  1034  1537 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-26 21:53:28.882  1034  1537 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-26 21:53:28.883  1034  1537 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-26 21:53:28.883  1034  1537 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-26 21:53:28.883  1034  1537 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-26 21:53:28.883  1034  1537 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-26 21:53:28.883  1034  1537 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-26 21:53:28.883  1034  1537 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
,08-26 21:53:28.884  1034  2006 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 21:53:28.884  1034  2006 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@e36fa78 mBinding = false
08-26 21:53:28.897  1034  1537 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-26 21:53:28.897  1034  1537 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2,
08-26 21:53:28.897  1034  1536 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,08-26 21:53:28.897  2658  2658 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-26 21:53:28.897  1034  1536 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-26 21:53:28.897  1034  1537 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-26 21:53:28.897  1034  1537 D WifiNative-wlan0: doBoolean: SET ps 1
08-26 21:53:28.898  1034  1537 D WifiNative-wlan0: SET ps 1: returned true
08-26 21:53:28.898  1034  2802 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-26 21:53:28.898   314   879 D CommandListener: Clearing all IP addresses on wlan0
08-26 21:53:28.904  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-26 21:53:28.905  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-26 21:53:28.905  1034  1034 D Ulp_jni : JNI:system_update. Event-4
08-26 21:53:28.916  1034  1105 D BluetoothManagerService: Message: 2
08-26 21:53:28.918  1034  1105 D BluetoothManagerService: Sending off request.
,08-26 21:53:28.918  4290  4308 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-26 21:53:28.919  4290  4380 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-26 21:53:28.919  4290  4380 D BluetoothAdapterProperties: Setting state to 13
08-26 21:53:28.919  4290  4380 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-26 21:53:28.919  4290  4380 D BluetoothAdapterProperties: onBluetoothDisable()
08-26 21:53:28.920  4290  4380 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-26 21:53:28.920  1034  1543 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-26 21:53:28.920  1034  1543 D ConnectivityService: ignoring duplicate network state non-change
08-26 21:53:28.921  1034  1543 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
08-26 21:53:28.922  1034  1034 D WifiHS20: hidePasspointNotification off =false
08-26 21:53:28.931  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 21:53:28.931  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-26 21:53:28.931  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 21:53:28.931  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 21:53:28.932  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-26 21:53:28.934  1942  1942 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-26 21:53:28.936  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 21:53:28.936  1034  1898 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
08-26 21:53:28.936  1034  2801 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-26 21:53:28.937  1034  2801 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-26 21:53:28.937  1034  2801 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-26 21:53:28.937  1034  2801 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-26 21:53:28.937  1034  2801 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on <unknown ssid>
08-26 21:53:28.937  1034  1105 D BluetoothManagerService: Message: 60
08-26 21:53:28.937  1034  1105 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-26 21:53:28.937  1034  1105 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-26 21:53:28.940  1034  1537 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 21:53:28.940  1034  1537 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 21:53:28.940  1034  1537 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 21:53:28.940  1034  1537 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 21:53:28.940  1034  1537 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 21:53:28.941  1034  1536 D LGWifiP2pService: InactiveState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-26 21:53:28.941  1034  1536 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-26 21:53:28.941  1034  1537 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 21:53:28.941  1034  1536 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@abccd34
08-26 21:53:28.941  1034  1537 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-26 21:53:28.941  1034  1536 D LGWifiP2pService: P2pDisablingState
08-26 21:53:28.941  4290  4384 D BluetoothAdapterProperties: Scan Mode:20
08-26 21:53:28.941  4290  4380 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-26 21:53:28.942  1034  1536 D LGWifiP2pService: P2pDisablingState{ when=-1ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-26 21:53:28.942  1034  1536 D LGWifiP2pService: p2p socket connection lost
08-26 21:53:28.942  4290  4380 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-26 21:53:28.942  1034  1536 D LGWifiP2pService: P2pDisabledState
08-26 21:53:28.942  4290  4693 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-26 21:53:28.942  4290  4693 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 21:53:28.942  4290  4693 V BluetoothMapMasInstance: 	at android.bluetooth.Bluetoo,thSocket.readAll(BluetoothSocket.java:586)
08-26 21:53:28.942  4290  4693 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-26 21:53:28.942  4290  4693 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-26 21:53:28.942  4290  4693 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-26 21:53:28.942  4290  4693 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-26 21:53:28.942  4290  4693 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-26 21:53:28.943  4290  4512 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-26 21:53:28.943  4290  4512 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
,08-26 21:53:28.946  4290  4753 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 21:53:28.948  4290  4694 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 21:53:28.948  4290  4747 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 21:53:28.948  4290  4750 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 21:53:28.950  4290  4512 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-26 21:53:28.950  4290  4512 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-26 21:53:28.950  4290  4512 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-26 21:53:28.950  4290  4512 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-26 21:53:28.950  4290  4512 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 21:53:28.950  4290  4512 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-26 21:53:28.950  4290  4512 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 21:53:28.950  4290  4512 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-26 21:53:28.950  4290  4512 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 21:53:28.950  4290  4512 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-26 21:53:28.950  4290  4512 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-26 21:53:28.950  4290  4512 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-26 21:53:28.954  1034  1034 D WifiHS20: hidePasspointNotification off =false
08-26 21:53:28.954  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 21:53:28.954  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 21:53:28.954  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-26 21:53:28.954  1034  1034 D WifiScanningService: SCAN_AVAILABLE : 1
08-26 21:53:28.954  1034  1034 D RttService: SCAN_AVAILABLE : 1
08-26 21:53:28.955  1034  1558 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-26 21:53:28.955  1034  1537 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
,08-26 21:53:28.956  1034  1537 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-26 21:53:28.956  2658  2658 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-26 21:53:28.956  1034  1536 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-26 21:53:28.956  1034  1557 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-26 21:53:28.956  1034  1536 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-26 21:53:28.956  1034  1537 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-26 21:53:28.956  1034  1537 D WifiNative-wlan0: doBoolean: SET ps 1
08-26 21:53:28.956  1034  1537 D WifiNative-wlan0: SET ps 1: returned true
08-26 21:53:28.957  6674  6764 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 21:53:28.958  1942  1942 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-26 21:53:28.958  1942  1942 D WfdsService: WifiP2pState is changed : false
08-26 21:53:28.958  1942  2307 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-26 21:53:28.958  1942  2307 D WfdsService: Set the WFDS Monitor: false
08-26 21:53:28.960  6674  6674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 21:53:28.960  6674  6674 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 21:53:28.960  6674  6674 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 21:53:28.960  6674  6674 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 21:53:28.960  6674  6674 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 21:53:28.960  6674  6674 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 21:53:28.960  6674  6674 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 21:53:28.960  6674  6674 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 21:53:28.960  6674  6674 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 21:53:28.960  6674  6764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 21:53:28.960  6674  6764 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 21:53:28.960  6674  6764 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 21:53:28.960  6674  6764 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 21:53:28.960  6674  6764 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 21:53:28.960  6674  6764 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 21:53:28.960  6674  6764 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 21:53:28.960  6674  6764 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 21:53:28.960  6674  6764 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 21:53:28.961  6674  6674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 21:53:28.961  6674  6674 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-26 21:53:28.962  6674  6764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: ,Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 21:53:28.962  6674  6764 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-26 21:53:28.962  6674  6764 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 21:53:28.963  1942  1942 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-26 21:53:28.964  1942  2307 D WfdsMonitor: WFDS Monitor is stopped
08-26 21:53:28.964  6674  6674 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 21:53:28.964  1942  2307 D WfdsService: STATE : WfdsDisabledState - enter
08-26 21:53:28.965  1942  2724 D CtrlSupplicant: Received on exit socket, terminate
08-26 21:53:28.965  1942  2724 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-26 21:53:28.965  1942  2724 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-26 21:53:28.965  1942  2310 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-26 21:53:28.965  1942  2724 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-26 21:53:28.965  1942  2307 W WfdsService: DefaultState - msg [9445378] is not handled
08-26 21:53:28.968  6674  6674 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 21:53:28.969  6674  6674 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 21:53:28.969  6674  6674 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 21:53:28.971  6448  6448 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 21:53:28.972  4290  4290 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-26 21:53:28.972  4290  4290 D BluetoothMapService: STATE_TURNING_OFF
08-26 21:53:28.972  4290  4290 V BluetoothMapService: Handler(): got msg=4
08-26 21:53:28.972  4290  4290 D BluetoothMapService: MAP Service closeService in
08-26 21:53:28.972  4290  4290 D BluetoothMapMasInstance: MAP Service shutdown
08-26 21:53:28.972  4290  4290 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-26 21:53:28.973  4290  4290 V BluetoothMapService: MAP Service closeService out
08-26 21:53:28.973  4290  4290 V BtOppService: Receiver DISABLED_ACTION 
08-26 21:53:28.973  4290  4290 I BtOppRfcommListener: stopping Accept Thread
08-26 21:53:28.973  4290  4290 V BtOppRfcommListener: close mBtServerSocket
08-26 21:53:28.974  4290  4747 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-26 21:53:28.974  4290  4290 V BtOppRfcommListener: waiting for thread to terminate
08-26 21:53:28.974  4290  4290 V BtOppRfcommListener: done waiting for thread to terminate
,08-26 21:53:28.974  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 21:53:28.974  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 21:53:28.975  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 21:53:28.976  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-26 21:53:28.978   314   879 D CommandListener: Clearing all IP addresses on wlan0
08-26 21:53:28.978   314  6907 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-26 21:53:28.979  1034  2801 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
08-26 21:53:28.979  1034  1543 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-26 21:53:28.979  1034  1103 D DSQN    : Dns fail occured do internet check.
08-26 21:53:28.979  1034  1543 D DSQN    : disableDataServiceNotify
08-26 21:53:28.979  1034  1543 D DSQN    : stop dsqn bin
08-26 21:53:28.980  1034  1034 D DSQN    : EVENT_INTERNET_CHECK_REQUEST received
08-26 21:53:28.980  1034  1034 D DSQN    : try Internet connection check
08-26 21:53:28.984   314  6910 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-26 21:53:28.985  1034  6909 D DSQN    : ThreadTCPConnectionCheck DNS fail internet is not possible
08-26 21:53:28.985  1034  6908 D DSQN    : ThreadInternetCheck internet check NOK 
,08-26 21:53:28.986  1034  1103 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-26 21:53:28.986  1034  6908 D DSQN    : L3_DATA_SERVICE_QUALITY STATUS 0 DataEnabled: false
08-26 21:53:28.986  1034  6908 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 com.android.server.DataServiceQualityMonitor.sendDSqualityIntent:1103 com.android.server.DataServiceQualityMonitor.access$200:55 com.android.server.DataServiceQualityMonitor$ThreadInternetCheck.run:921 <bottom of call stack> 
08-26 21:53:28.992  1034  1543 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-26 21:53:28.992  1034  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 21:53:28.992  1034  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 21:53:28.992  1034  1543 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 21:53:28.992  1034  1543 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-26 21:53:28.993  1034  2801 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-26 21:53:28.993  1034  2801 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-26 21:53:28.993  1603  1827 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-26 21:53:28.994  1034  2801 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-26 21:53:28.994  1034  1543 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-26 21:53:28.994  1034  1543 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-26 21:53:28.994  1034  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,08-26 21:53:29.012  1034  1091 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6917 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-26 21:53:29.060  1034  1921 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6934 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-26 21:53:29.063  4290  4290 V BtOppService: onDestroy
08-26 21:53:29.064  1034  1543 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-26 21:53:29.064  1034  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-26 21:53:29.069  1034  1034 D WifiDataContinuityService: L3_DATA_SERVICE_QUALITY_ACTION, resultStatus : 0
08-26 21:53:29.070  1034  1535 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-26 21:53:29.072  4290  4290 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-26 21:53:29.073  1034  1537 D WifiNative-p2p0: doBoolean: TERMINATE
08-26 21:53:29.073  1034  1537 D WifiNative-p2p0: TERMINATE: returned true
08-26 21:53:29.074  1034  1537 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-26 21:53:29.074  1034  1537 E WifiStateMachine: useWiFiOffloading() : false
08-26 21:53:29.074  1034  1537 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-26 21:53:29.076  1034  1543 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-26 21:53:29.076  1034  1543 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 21:53:29.076  1034  1543 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 21:53:29.077  1034  1543 D NetworkManagementService: Removing idletimer
08-26 21:53:29.077  1034  1543 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 21:53:29.078  1034  1537 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 21:53:29.078  1034  1537 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 21:53:29.079  1034  1535 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-26 21:53:29.079  1942  1957 D WifiServiceExtension: isInternetCheckAvailable return false
08-26 21:53:29.080  1853  1853 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 21:53:29.080  1853  1853 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-26 21:53:29.080  1034  1034 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-26 21:53:29.081  1034  1034 D WifiHS20: hidePasspointNotification off =false
08-26 21:53:29.081  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 21:53:29.081  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 21:53:29.081  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-26 21:53:29.081  1034  1034 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-26 21:53:29.081  1034  1034 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-26 21:53:29.081  1034  1034 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-26 21:53:29.083  1034  1034 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-26 21:53:29.084  1942  1942 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-26 21:53:29.088  6674  6674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 21:53:29.088  6674  6674 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 21:53:29.088  6674  6674 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 21:53:29.088  6674  6674 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 21:53:29.088  6674  6674 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 21:53:29.088  6674  6674 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 21:53:29.088  6674  6674 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 21:53:29.088  6674  6674 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 21,:53:29.088  6674  6674 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 21:53:29.089  6674  6674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 21:53:29.089  6674  6674 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 21:53:29.089  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-26 21:53:29.089  1034  1034 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-26 21:53:29.089  1034  1034 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-26 21:53:29.089  1034  1034 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-26 21:53:29.089  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 21:53:29.089  1034  1034 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-26 21:53:29.091  6674  6674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 21:53:29.091  6674  6674 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 21:53:29.091  6674  6674 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 21:53:29.091  6674  6674 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 21:53:29.091  6674  6674 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 21:53:29.091  6674  6674 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 21:53:29.091  6674  6674 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 21:53:29.091  6674  6674 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 21:53:29.091  6674  6674 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 21:53:29.091  6674  6674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 21:53:29.091  6674  6674 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 21:53:29.102  6917  6917 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-26 21:53:29.102  6917  6917 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
,08-26 21:53:29.102  6917  6917 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-26 21:53:29.103  6917  6917 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
08-26 21:53:29.103  6917  6917 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-26 21:53:29.104  6917  6917 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-26 21:53:29.114  1603  1603 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-26 21:53:29.115  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 21:53:29.115  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 21:53:29.115  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-26 21:53:29.116  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 21:53:29.117  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 21:53:29.122  1034  2802 D DhcpStateMachine: StoppedState
08-26 21:53:29.122  1034  2802 D DhcpStateMachine: StoppedState{ when=-165ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-26 21:53:29.123  1034  1537 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-26 21:53:29.123  1034  1537 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
,08-26 21:53:29.149  1603  1603 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-26 21:53:29.150  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 21:53:29.150  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 21:53:29.150  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 21:53:29.162  2658  2658 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-26 21:53:29.162  2658  2658 I wpa_supplicant: monitor socket send errors count : 1
08-26 21:53:29.162  2658  2658 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1942-2\x00 that cannot receive messages
,08-26 21:53:29.164  6934  6934 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-26 21:53:29.164  1034  2721 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-26 21:53:29.165  1034  2721 D WifiMonitor: Dropping event because (p2p0) is stopped
08-26 21:53:29.172  6934  6934 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-26 21:53:29.172  6934  6934 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-26 21:53:29.174  1034  1050 I ActivityManager: Killing 6227:com.android.providers.calendar/u0a14 (adj 15): empty #17
,08-26 21:53:29.201  2658  2658 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-26 21:53:29.201  1034  2721 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-26 21:53:29.201  1034  2721 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-26 21:53:29.201  1034  2721 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-26 21:53:29.202  1034  2721 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-26 21:53:29.202  1034  1105 D Tethering: InitialState.processMessage what=4
08-26 21:53:29.202  2658  2658 W wpa_supplicant: USIM:  scard_deinit function
08-26 21:53:29.202  1034  2721 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-26 21:53:29.202  1034  2721 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-26 21:53:29.203  1034  1537 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=121959
08-26 21:53:29.203  1034  1537 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=121959
08-26 21:53:29.203  1034  1537 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=121960  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-26 21:53:29.204  1034  1537 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=121960  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-26 21:53:29.207  6917  6917 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-26 21:53:29.223  1034  1732 W libprocessgroup: failed to open /acct/uid_10014/pid_6227/cgroup.procs: No such file or directory
,08-26 21:53:29.228  1034  1105 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-26 21:53:29.235  1034  1537 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-26 21:53:29.235  1034  1537 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,08-26 21:53:29.239  4290  4290 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-26 21:53:29.239  4290  4290 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 21:53:29.239  4290  4290 V BluetoothPbapReceiver: ***********state = 13
08-26 21:53:29.242  4290  4290 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-26 21:53:29.248  4290  4290 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-26 21:53:29.248  4290  4290 V BluetoothPbapService: state: 13
08-26 21:53:29.248  4290  4290 V BluetoothPbapService: Pbap Service closeService in
08-26 21:53:29.249  2205  2205 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-26 21:53:29.251  4290  4290 V BluetoothPbapService: successfully stopped pbap service
08-26 21:53:29.252  4290  4290 V BluetoothPbapService: Pbap Service closeService out
08-26 21:53:29.252  4290  4290 V BluetoothPbapService: Pbap Service onDestroy
08-26 21:53:29.252  4290  4290 V BluetoothPbapService: Pbap Service closeService in
08-26 21:53:29.252  4290  4290 V BluetoothPbapService: Pbap Service closeService out
08-26 21:53:29.252  4290  4290 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-26 21:53:29.258  6917  6917 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-26 21:53:29.312  2658  2658 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-26 21:53:29.313  1034  2721 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-26 21:53:29.313  1034  2721 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
08-26 21:53:29.313  1034  2721 D WifiMonitor: Disconnecting from the supplicant, no more events
,08-26 21:53:29.314  1034  1537 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
,08-26 21:53:29.317  1034  1921 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6957 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
08-26 21:53:29.318  1034  1378 V AlarmManager: ELAPSED_WAKEUP set : Alarm{2bd78342 type 2 when 122070 com.google.android.gms} when 122070
08-26 21:53:29.334  6917  6917 D LgDataFeature: LgDataFeature() Constructor: none
08-26 21:53:29.335  6917  6917 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-26 21:53:29.339  6674  6674 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-26 21:53:29.347  6917  6917 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-26 21:53:29.357  1034  1105 D BluetoothManagerService: Message: 20
08-26 21:53:29.357  1034  1105 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@7faa090:true
08-26 21:53:29.383  1034  1105 D BluetoothManagerService: Message: 30
,08-26 21:53:29.388  1034  1105 D BluetoothManagerService: Message: 30
08-26 21:53:29.390  6917  6917 D LocalBluetoothProfileManager: Adding local MAP profile
08-26 21:53:29.392  6917  6917 D BluetoothMap: Create BluetoothMap proxy object
08-26 21:53:29.393  1034  1105 D BluetoothManagerService: Message: 30
08-26 21:53:29.397  1034  1105 D BluetoothManagerService: Message: 30
,08-26 21:53:29.399  6917  6917 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
08-26 21:53:29.400  6917  6917 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
08-26 21:53:29.415  1034  1537 D WifiOffDelayIfNotUsed: stopMonitoring
,08-26 21:53:29.415  1034  1537 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-26 21:53:29.415  1034  1537 E WifiStateMachine: useWiFiOffloading() : false
08-26 21:53:29.415  1034  1537 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-26 21:53:29.416  6917  6917 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
08-26 21:53:29.417  1942  1942 D WfdsService: Supplicant Connection state is changed : false
08-26 21:53:29.417  1942  2307 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-26 21:53:29.417  1942  1942 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-26 21:53:29.417  1942  2307 D WfdsService: Set the WFDS Monitor: false
08-26 21:53:29.417  1942  2307 D WfdsMonitor: WFDS Monitor is stopped
08-26 21:53:29.418  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 21:53:29.418  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-26 21:53:29.418  2481  2481 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 21:53:29.419  1034  1541 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-26 21:53:29.419  1034  1541 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-26 21:53:29.420  6674  6674 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 21:53:29.422  6674  6674 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 21:53:29.425  6917  6917 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
08-26 21:53:29.439  6917  6917 D DockEventReceiver: finishStartingService: stopping service
,08-26 21:53:29.451  6957  6957 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-26 21:53:29.452  6957  6957 W LG Account v2.2: No ProfileInfo entries
08-26 21:53:29.452  6957  6957 I LG Account v2.2: isEnabled: false
,08-26 21:53:29.452  6957  6957 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-26 21:53:29.452  6957  6957 I Feature : [Lifetracker]Country: EU
08-26 21:53:29.452  6957  6957 I Feature : [Lifetracker]Operator: OPEN
08-26 21:53:29.452  6957  6957 I Feature : [Lifetracker]Ranking support: false
08-26 21:53:29.452  6957  6957 I Feature : [Lifetracker]Comfort support: false
08-26 21:53:29.452  6957  6957 I Feature : [Lifetracker]Accessory: true
08-26 21:53:29.452  6957  6957 I Feature : [Lifetracker]Health device: true
08-26 21:53:29.452  6957  6957 I Feature : [Lifetracker]Extra Pedometer: false
08-26 21:53:29.453  6957  6957 I Feature : [Lifetracker]Blood glucose device: false
08-26 21:53:29.453  6957  6957 I Feature : [Lifetracker]Device Number: 3
08-26 21:53:29.454  6917  6917 D BluetoothInputDevice: Proxy object connected
08-26 21:53:29.455  6917  6917 D HidProfile: Bluetooth service connected
08-26 21:53:29.457  6917  6917 D BluetoothPan: BluetoothPAN Proxy object connected
08-26 21:53:29.458  6917  6917 D PanProfile: Bluetooth service connected
08-26 21:53:29.460  6917  6917 D BluetoothMap: Proxy object connected
08-26 21:53:29.461  6917  6917 D MapProfile: Bluetooth service connected
08-26 21:53:29.461  6917  6917 D BluetoothMap: getConnectedDevices()
08-26 21:53:29.462  6917  6917 D BluetoothMap: Bluetooth is Not enabled
08-26 21:53:29.462  6917  6917 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-26 21:53:29.512  1034  1887 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6981 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,08-26 21:53:29.516  1034  1887 I ActivityManager: Killing 6356:com.android.defcontainer/u0a4 (adj 15): empty #17
08-26 21:53:29.565  1034  1898 W libprocessgroup: failed to open /acct/uid_10004/pid_6356/cgroup.procs: No such file or directory
,08-26 21:53:29.579  6917  6917 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-26 21:53:29.590  6917  6917 D BluetoothPermissionRequest: onReceive
08-26 21:53:29.595  6917  6917 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-26 21:53:29.616  6917  6917 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-26 21:53:29.628  1034  2033 I ActivityManager: Killing 6500:com.google.android.partnersetup/u0a8 (adj 15): empty #17
,08-26 21:53:29.637  6981  6981 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-26 21:53:29.688  4290  4290 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
,08-26 21:53:29.688  4290  4290 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-26 21:53:29.690  4290  4290 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-26 21:53:29.693  1034  2006 W libprocessgroup: failed to open /acct/uid_10008/pid_6500/cgroup.procs: No such file or directory
08-26 21:53:29.704  6981  6981 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,08-26 21:53:29.707  4290  4290 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-26 21:53:29.707  4290  4290 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-26 21:53:29.709  4290  4290 V BluetoothFtpService: Ftp Service onStartCommand
08-26 21:53:29.709  4290  4290 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-26 21:53:29.710  4290  4290 V BluetoothFtpService: Ftp Service closeService
08-26 21:53:29.710  4290  4290 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-26 21:53:29.712  4290  4290 V BluetoothFtpService: successfully stopped ftp service
08-26 21:53:29.713  4290  4290 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-26 21:53:29.713  4290  4290 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-26 21:53:29.713  4290  4290 V BluetoothSapReceiver: SapReceiver onReceive 
08-26 21:53:29.713  4290  4290 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 21:53:29.713  4290  4290 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-26 21:53:29.714  4290  4290 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-26 21:53:29.715  4290  4290 V BluetoothFtpService: Ftp Service onDestroy
08-26 21:53:29.715  4290  4290 V BluetoothFtpService: Ftp Service closeService
08-26 21:53:29.774  1034  1614 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=7003 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-26 21:53:29.781  1034  1091 I ActivityManager: Waited long enough for: ServiceRecord{1a4ed941 u0 com.google.android.gms/.wearable.service.WearableService}
08-26 21:53:29.782  4290  4290 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-26 21:53:29.782  4290  4290 V BluetoothSapService: state: 13
08-26 21:53:29.782  4290  4290 V BluetoothSapService: Stopping SAP server process
08-26 21:53:29.784  4290  4290 V BluetoothSapService: Sap Service closeSapService in
08-26 21:53:29.785  4290  4290 V BluetoothSapService: Close listen Socket : 
08-26 21:53:29.785  4290  4290 V BluetoothSapService: Close rfcomm Socket : 
08-26 21:53:29.785  4290  4290 V BluetoothSapService: Close sapd  Socket : 
08-26 21:53:29.788  4290  4290 V BluetoothSapService: Sap Service closeSapService out
08-26 21:53:29.789  4290  4290 V BluetoothSapService: Sap Service onDestroy
08-26 21:53:29.789  4290  4290 V BluetoothSapService: Sap Service closeSapService in
08-26 21:53:29.789  4290  4290 V BluetoothSapService: Close listen Socket : 
08-26 21:53:29.789  4290  4290 V BluetoothSapService: Close rfcomm Socket : 
08-26 21:53:29.789  4290  4290 V BluetoothSapService: Close sapd  Socket : 
08-26 21:53:29.789  4290  4290 V BluetoothSapService: Sap Service closeSapService out
,08-26 21:53:29.850  7003  7003 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-26 21:53:29.865  6981  6981 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
08-26 21:53:29.865  6981  6981 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-26 21:53:29.866  6981  6981 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-26 21:53:29.867  6981  6981 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-26 21:53:29.867  1034  1921 I ActivityManager: Killing 5982:com.lge.appbox.client/u0a11 (adj 15): empty #17
,08-26 21:53:29.867  6981  6981 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-26 21:53:29.870  6981  6981 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-26 21:53:29.876  6981  6981 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-26 21:53:29.898  1034  1887 W libprocessgroup: failed to open /acct/uid_10011/pid_5982/cgroup.procs: No such file or directory
,08-26 21:53:29.905  6981  6981 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 21:53:29.910  6981  6981 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-26 21:53:29.931  6981  6981 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-26 21:53:29.937  6448  6448 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 21:53:29.940  6981  6981 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-26 21:53:29.942  6934  6934 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-26 21:53:29.942  6934  6934 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-26 21:53:29.942  6934  6934 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-26 21:53:29.948  6917  6917 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 21:53:29.953  4290  4514 I bt_lpm  : LPM is already off!!!
08-26 21:53:29.953  4290  4384 D bt_hci_bdroid: cleanup
08-26 21:53:29.953  4290  4512 W bt-btif : ag scb idx 1 not allocated
08-26 21:53:29.954  4290  4512 E bt-btif : BTA AG is already disabled, ignoring ...
08-26 21:53:29.954  4290  4512 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-26 21:53:29.954  4290  4512 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 21:53:29.954  4290  4512 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-26 21:53:29.954  4290  4512 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 21:53:29.954  4290  4512 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-26 21:53:29.954  4290  4512 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 21:53:29.954  4290  4512 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-26 21:53:29.954  4290  4512 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 21:53:29.954  4290  4512 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-26 21:53:29.954  4290  4512 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 21:53:29.954  4290  4512 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-26 21:53:29.954  4290  4512 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 21:53:29.954  4290  4512 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-26 21:53:29.954  4290  4512 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 21:53:29.954  4290  4512 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-26 21:53:29.954  4290  4512 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 21:53:29.954  4290  4512 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-26 21:53:29.954  4290  4512 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 21:53:29.954  4290  4512 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-26 21:53:29.954  6981  6981 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-26 21:53:29.954  4290  4677 I bt_userial_mct: exiting userial_read_thread
08-26 21:53:29.954  4290  4677 D bt_userial_mct: Leaving userial_evt_read_thread()
08-26 21:53:29.955  4290  4384 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-26 21:53:29.955  4290  4514 I bt_vendor: hw_epilog_process
08-26 21:53:29.956  4290  4384 D bt_hci_bdroid: cleanup Finalizing cleanup
08-26 21:53:29.956  4290  4384 D bt_userial_mct: userial_close
08-26 21:53:29.956  4290  4384 E bt_userial_mct: pthread_join() FAILED result:3
08-26 21:53:29.956  4290  4384 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-26 21:53:29.957  6917  6917 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 21:53:29.966  6981  6981 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 21:53:29.967  6981  6981 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 21:53:29.968  6981  6981 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-26 21:53:29.975  6448  6448 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 21:53:29.980  6934  6934 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-26 21:53:29.980  6934  6934 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-26 21:53:29.981  6934  6934 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-26 21:53:29.984  6917  6917 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-26 21:53:29.990  6917  6917 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 21:53:29.997  6981  6981 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 21:53:29.997  6981  6981 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-26 21:53:30.000  6981  6981 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-26 21:53:30.011  4290  4384 D bt_hci_bdroid: set_power 0
08-26 21:53:30.012  4290  4384 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-26 21:53:30.012  4290  4384 I bt_vendor: bluetooth satus is on
08-26 21:53:30.012  4290  4384 I bt_vendor: bt-vendor : resetting BT status
08-26 21:53:30.012  4290  4384 I bt_vendor: Starting hciattach daemon
08-26 21:53:30.012  4290  4384 I bt_vendor: try to set false
,08-26 21:53:30.014  4290  4384 I bt_vendor: Starting hciattach daemon
08-26 21:53:30.014  4290  4384 I bt_vendor: try to set false
08-26 21:53:30.014  4290  4384 I bt_vendor: cleanup
08-26 21:53:30.015  4290  4512 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-26 21:53:30.015  4290  4384 I GKI_LINUX: GKI_exit_task 0 done
08-26 21:53:30.015  4290  4384 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-26 21:53:30.016  4290  4380 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-26 21:53:30.063  1034  1034 D DSQN    : EVENT_INTERNET_CHECK_ENABLE received
,08-26 21:53:30.063  1034  1576 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7024 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
08-26 21:53:30.067  4290  4290 D HeadsetService: Received stop request...Stopping profile...
08-26 21:53:30.068  4290  4290 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-26 21:53:30.069  4290  4290 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-26 21:53:30.069  4290  4290 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@385f0867
08-26 21:53:30.069  4290  4454 D HeadsetStateMachine: Exit Disconnected: -1
08-26 21:53:30.070  1853  1853 D BluetoothHeadset: Proxy object disconnected
08-26 21:53:30.070  1853  1853 D BluetoothHeadset: Proxy object disconnected
08-26 21:53:30.072  1853  1853 D BluetoothHeadset: Proxy object disconnected
08-26 21:53:30.073  1034  1034 D BluetoothHeadset: Proxy object disconnected
08-26 21:53:30.073  1034  1034 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-26 21:53:30.075  4290  4290 D A2dpService: Received stop request...Stopping profile...
08-26 21:53:30.075  4290  4487 D A2dpStateMachine: Exit Disconnected: -1
,08-26 21:53:30.076  4290  4290 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-26 21:53:30.078  4290  4380 D BluetoothAdapterState: Stopping profile services that were post enabled
08-26 21:53:30.079  4290  4290 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-26 21:53:30.079  4290  4290 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-26 21:53:30.079  4290  4290 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@385f0867
08-26 21:53:30.080  1034  1034 D BluetoothA2dp: Proxy object disconnected
08-26 21:53:30.080  1034  1034 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-26 21:53:30.082  4290  4290 D HidService: Received stop request...Stopping profile...
08-26 21:53:30.082  4290  4290 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@385f0867
08-26 21:53:30.083  4290  4290 D HeadsetStateMachine: Unbinding service...
08-26 21:53:30.084  4290  4290 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-26 21:53:30.084  4290  4290 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-26 21:53:30.084  4290  4290 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-26 21:53:30.084  4290  4290 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-26 21:53:30.084  4290  4290 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-26 21:53:30.084  4290  4290 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-26 21:53:30.084  4290  4290 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-26 21:53:30.084  4290  4290 D HealthService: Received stop request...Stopping profile...
08-26 21:53:30.084  6917  6917 D BluetoothInputDevice: Proxy object disconnected
08-26 21:53:30.085  4290  4290 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@385f0867
08-26 21:53:30.085  6917  6917 D HidProfile: Bluetooth service disconnected
08-26 21:53:30.086  4290  4290 D PanService: Received stop request...Stopping profile...
08-26 21:53:30.087  4290  4290 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@385f0867
08-26 21:53:30.087  4290  4290 D BtGatt.DebugUtils: handleDebugAction() action=null
08-26 21:53:30.088  4290  4290 D BtGatt.GattService: Received stop request...Stopping profile...
08-26 21:53:30.088  4290  4290 D BtGatt.GattService: stop()
08-26 21:53:30.088  4290  4290 D BtGatt.AdvertiseManager: advertise clients cleared
08-26 21:53:30.089  4290  4290 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@385f0867
08-26 21:53:30.090  4290  4290 D BluetoothMapService: Received stop request...Stopping profile...
08-26 21:53:30.090  4290  4290 D BluetoothMapService: stop()
08-26 21:53:30.090  6917  6917 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-26 21:53:30.091  6917  6917 D PanProfile: Bluetooth service disconnected
,08-26 21:53:30.091  4290  4290 D BluetoothMapEmailAppObserver: deinitObservers()
08-26 21:53:30.091  4290  4290 D BluetoothMapEmailAppObserver: removeReceiver()
08-26 21:53:30.092  4290  4290 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@385f0867
08-26 21:53:30.093  4290  4290 I BluetoothA2dpServiceJni: cleanupNative
08-26 21:53:30.094  4290  4488 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
,08-26 21:53:30.094  6917  6917 D BluetoothMap: Proxy object disconnected
08-26 21:53:30.094  6917  6917 D MapProfile: Bluetooth service disconnected
08-26 21:53:30.094  4290  4290 I GKI_LINUX: GKI_exit_task 2 done
08-26 21:53:30.094  4290  4290 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-26 21:53:30.095  4290  4290 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-26 21:53:30.095  4290  4290 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-26 21:53:30.095  4290  4290 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-26 21:53:30.095  4290  4290 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,08-26 21:53:30.095  4290  4290 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-26 21:53:30.095  4290  4290 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-26 21:53:30.095  4290  4290 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-26 21:53:30.096  4290  4290 V BluetoothMapService: Handler(): got msg=4
08-26 21:53:30.096  4290  4290 D BluetoothMapService: MAP Service closeService in
08-26 21:53:30.096  4290  4290 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-26 21:53:30.096  4290  4290 V BluetoothMapService: MAP Service closeService out
08-26 21:53:30.097  4290  4290 D BluetoothMapService: cleanup()
08-26 21:53:30.097  4290  4290 D BluetoothMapService: MAP Service closeService in
08-26 21:53:30.097  4290  4290 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-26 21:53:30.097  4290  4290 V BluetoothMapService: MAP Service closeService out
08-26 21:53:30.097  4290  4380 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-26 21:53:30.097  4290  4380 D BluetoothAdapterProperties: Setting state to 10
08-26 21:53:30.097  4290  4380 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-26 21:53:30.098  1034  1105 D BluetoothManagerService: Message: 60
08-26 21:53:30.098  1034  1105 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-26 21:53:30.098  1034  1105 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
08-26 21:53:30.098  4290  4380 I BluetoothAdapterState: Entering OffState
08-26 21:53:30.098  1853  2419 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 21:53:30.099  1853  1869 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 21:53:30.099  6917  6933 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-26 21:53:30.100  1853  1868 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 21:53:30.100  6917  6932 D BluetoothPbap: onBluetoothStateChange: up=false
08-26 21:53:30.101  6917  6933 D BluetoothPan: onBluetoothStateChange on: false
08-26 21:53:30.102  1034  1105 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 21:53:30.102  6917  6932 D BluetoothMap: onBluetoothStateChange: up=false
08-26 21:53:30.103  1034  1105 D BluetoothA2dp: onBluetoothStateChange: up=false
08-26 21:53:30.103  1034  1105 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-26 21:53:30.103  1034  1105 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-26 21:53:30.106  1034  1105 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-26 21:53:30.106  1034  1105 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-26 21:53:30.106  1034  1105 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@e36fa78 mBinding = false
08-26 21:53:30.106  1034  1105 D BluetoothManagerService: Sending unbind request.
,08-26 21:53:30.110  1034  1105 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-26 21:53:30.112  1942  1942 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-26 21:53:30.113  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-26 21:53:30.116  1942  2102 D LGBluetoothAPIService: Message: 2
08-26 21:53:30.116  1942  2102 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@dacb6f6 mBinding = false
08-26 21:53:30.116  1942  2102 D LGBluetoothAPIService: Sending unbind request.
08-26 21:53:30.117  4290  4384 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-26 21:53:30.118  4290  4290 I GKI_LINUX: GKI_exit_task 1 done
08-26 21:53:30.118  4290  4290 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-26 21:53:30.118  4290  4290 I BluetoothServiceJni: cleanupNative: return from cleanup
08-26 21:53:30.118  4290  4290 I art     : --- WEIRD: removing null entry 246
,08-26 21:53:30.118  4290  4290 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
08-26 21:53:30.118  4290  4290 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-26 21:53:30.122  1603  1603 D BluetoothAdapter: 127316959: getState() :  mService = null. Returning STATE_OFF
,08-26 21:53:30.122  1603  1603 D BluetoothAdapter: 127316959: getState() :  mService = null. Returning STATE_OFF
08-26 21:53:30.123  4290  4290 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-26 21:53:30.124  6917  6917 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-26 21:53:30.125  6917  6917 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-26 21:53:30.125  6917  6917 D LGBluetoothEventManager: [BTUI] clear device connection state
08-26 21:53:30.126  6674  6674 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 21:53:30.127  6674  6674 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 21:53:30.128  4290  4290 I art     : System.exit called, status: 0
08-26 21:53:30.128  4290  4290 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-26 21:53:30.130  6917  6917 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-26 21:53:30.142  6917  6917 D DockEventReceiver: finishStartingService: stopping service
08-26 21:53:30.155   319  1383 V AudioFlinger: 4290 died, releasing its sessions
08-26 21:53:30.155   319  1383 V AudioFlinger:  pid 1853 @ 0
,08-26 21:53:30.155   319  1383 V AudioFlinger:  pid 3203 @ 1
,08-26 21:53:30.155   319  1383 V AudioFlinger:  pid 3203 @ 2
08-26 21:53:30.155  6917  6917 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-26 21:53:30.242  1034  1576 I ActivityManager: Process com.android.bluetooth (pid 4290) has died
,08-26 21:53:30.243  1034  1576 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
,08-26 21:53:30.256  2205  2205 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-26 21:53:30.286  6934  6934 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-26 21:53:30.298  6917  6917 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-26 21:53:30.313  6917  6917 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 21:53:30.314  6917  6917 D BluetoothPermissionRequest: onReceive
,08-26 21:53:30.318  6917  6917 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-26 21:53:30.319  6917  6917 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-26 21:53:30.320  7024  7052 W FormManager: Network not available. Please check & try again.
08-26 21:53:30.322  6917  6917 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-26 21:53:30.398  1034  1614 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7054 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-26 21:53:30.418  7024  7053 V FormManager: Network unavailable.
,08-26 21:53:30.426  7024  7053 V FormManager: Network unavailable.
08-26 21:53:30.440  6917  6917 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-26 21:53:30.440  6917  6917 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-26 21:53:30.441  6917  6917 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-26 21:53:30.441  6917  6917 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
,08-26 21:53:30.446  6917  6917 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-26 21:53:30.457  6917  6917 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-26 21:53:30.457  6917  6917 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-26 21:53:30.457  6917  6917 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-26 21:53:30.457  6917  6917 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-26 21:53:30.457  6917  6917 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-26 21:53:30.458  6917  6917 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,08-26 21:53:30.461  1034  2033 I ActivityManager: Killing 6007:com.android.contacts/u0a19 (adj 15): empty #17
08-26 21:53:30.465   314  7077 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-26 21:53:30.465  1034  1103 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,08-26 21:53:30.499  1034  1975 W libprocessgroup: failed to open /acct/uid_10019/pid_6007/cgroup.procs: No such file or directory
08-26 21:53:30.512  4754  4754 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-26 21:53:30.513  4754  4754 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-26 21:53:30.518  4754  4754 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 21:53:30.524  4754  4754 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 21:53:30.527  7054  7054 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-26 21:53:30.527  7054  7054 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-26 21:53:30.528  7054  7054 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-26 21:53:30.528  7054  7054 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-26 21:53:30.536  4754  7087 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-26 21:53:30.537  4754  7086 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-26 21:53:30.539  6934  6934 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-26 21:53:30.539  6934  6934 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-26 21:53:30.539  6934  6934 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-26 21:53:30.542  4754  7087 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-26 21:53:30.543  6917  6917 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-26 21:53:30.551  6917  6917 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 21:53:30.553  7054  7054 D BluetoothAdapterApp: Loading JNI Library
08-26 21:53:30.558  4909  7078 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,08-26 21:53:30.560  7024  7091 W FormManager: Network not available. Please check & try again.
08-26 21:53:30.565  7024  7092 V FormManager: Network unavailable.
08-26 21:53:30.571  7024  7092 V FormManager: Network unavailable.
08-26 21:53:30.572  6981  6981 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-26 21:53:30.573  6981  6981 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-26 21:53:30.574  6981  6981 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
,08-26 21:53:30.587  7054  7054 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@1a40e37c Instance Count = 1
,08-26 21:53:30.592  7054  7054 D BluetoothAdapterApp: onCreate
,08-26 21:53:30.610  7054  7054 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-26 21:53:30.610  7054  7054 D ProfileConfigQcom: Adding HeadsetService
08-26 21:53:30.610  7054  7054 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-26 21:53:30.610  7054  7054 D ProfileConfigQcom: Adding A2dpService
08-26 21:53:30.610  7054  7054 D ProfileConfigQcom: [BTUI] HidService is supported
08-26 21:53:30.610  7054  7054 D ProfileConfigQcom: Adding HidService
08-26 21:53:30.611  7054  7054 D ProfileConfigQcom: [BTUI] HealthService is supported
08-26 21:53:30.611  7054  7054 D ProfileConfigQcom: Adding HealthService
08-26 21:53:30.611  7054  7054 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-26 21:53:30.612  7054  7054 D ProfileConfigQcom: [BTUI] PanService is supported
08-26 21:53:30.612  7054  7054 D ProfileConfigQcom: Adding PanService
08-26 21:53:30.612  7054  7054 D ProfileConfigQcom: [BTUI] GattService is supported
08-26 21:53:30.612  7054  7054 D ProfileConfigQcom: Adding GattService
08-26 21:53:30.612  7054  7054 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-26 21:53:30.612  7054  7054 D ProfileConfigQcom: Adding BluetoothMapService
08-26 21:53:30.613  7054  7054 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-26 21:53:30.614  7054  7054 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
,08-26 21:53:30.616  6917  6917 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-26 21:53:30.618  7054  7054 V LGMDMManagerInternal: Create singleton instance
08-26 21:53:30.620  6981  6981 D LgDataFeature: LgDataFeature() Constructor: none
08-26 21:53:30.621  6981  6981 D LgDataFeature: LgDataFeature() Constructor Done, null
08-26 21:53:30.627  6981  6981 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
08-26 21:53:30.629  6981  6981 V SoundPool: load: fd=31, offset=10857164, length=17813, priority=1
08-26 21:53:30.629  6981  6981 V SoundPool: create sampleID=1, fd=30, offset=17813 length=10857164
,08-26 21:53:30.629  6981  6981 V SoundPool: doLoad: loading sample sampleID=1
08-26 21:53:30.629  6981  7099 V SoundPool: Start decode
08-26 21:53:30.629  6981  7099 V MediaPlayer[Native]: decode(30, 10857164, 17813)
08-26 21:53:30.630   319  2203 V MediaPlayerService: decode(22, 10857164, 17813)
08-26 21:53:30.630   319  2203 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-26 21:53:30.630   319  2203 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-26 21:53:30.630   319  2203 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-26 21:53:30.630   319  2203 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-26 21:53:30.630   319  2203 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-26 21:53:30.630   319  2203 V MediaPlayerService: player type = 3
08-26 21:53:30.630   319  2203 V AwesomePlayer: AwesomePlayer create()
08-26 21:53:30.631   319  2203 V AwesomePlayer: reset_l() 
08-26 21:53:30.631   319  2203 V AwesomePlayer: cancelPlayerEvents
08-26 21:53:30.631   319  2203 V AwesomePlayer: setAudioSink() 
08-26 21:53:30.631  6981  6981 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-26 21:53:30.631   319  2203 V AwesomePlayer: reset_l() 
08-26 21:53:30.631   319  2203 V AudioCache: notify(0xb04095c0, 8, 0, 0)
08-26 21:53:30.631   319  2203 V AudioCache: ignored
08-26 21:53:30.631   319  2203 V AwesomePlayer: cancelPlayerEvents
08-26 21:53:30.631   319  2203 D Utils   : printFileName fd(23) -> /data/preload/LGQRemote/LGQRemote.apk
08-26 21:53:30.631   319  2203 V AwesomePlayer: setDataSource_l dataSource
08-26 21:53:30.631   319  2203 V LGParserOSAL: SniffLGParser start
08-26 21:53:30.631   319  2203 V LGParserOSAL: MainType:5, SubType=0
08-26 21:53:30.631   319  2203 V LGParserOSAL: #### check Mime : application/ogg
08-26 21:53:30.631   319  2203 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-26 21:53:30.631   319  2203 E MediaExtractor: Use LGExtractor :application/ogg 
08-26 21:53:30.634  6981  6981 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-26 21:53:30.635  6981  6981 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-26 21:53:30.635  6981  6981 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-26 21:53:30.646  6981  6981 V LGMDMManager: Create singleton instance
08-26 21:53:30.650  6850  6850 D UEI.SmartControl: QS Service created
,08-26 21:53:30.662   319  2203 V LGParserOSAL: supported mime: application/ogg
08-26 21:53:30.663   319  2203 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-26 21:53:30.663   319  2203 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-26 21:53:30.663   319  2203 V AwesomePlayer: mBitrate = -1 bits/sec
08-26 21:53:30.663   319  2203 V AwesomePlayer: AudioTrack Setting
08-26 21:53:30.663   319  2203 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-26 21:53:30.663   319  2203 V AwesomePlayer: setAudioSource() 
08-26 21:53:30.663   319  2203 V MediaPlayerService: prepare
08-26 21:53:30.663   319  2203 V AwesomePlayer: prepareAsync_l() 
08-26 21:53:30.663   319  2203 V MediaPlayerService: wait for prepare
08-26 21:53:30.663   319  7101 V AwesomePlayer: onPrepareAsyncEvent() 
08-26 21:53:30.663   319  7101 V AwesomePlayer: initAudioDecoder() 
08-26 21:53:30.663   319  7101 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-26 21:53:30.663   319  7101 V AudioSystem: isOffloadSupported()
08-26 21:53:30.663   319  7101 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-26 21:53:30.663   319  7101 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-26 21:53:30.663   319  7101 I AudioFlinger: isAudioPlaybackHookOn() false
08-26 21:53:30.663   319  7101 V AwesomePlayer: getUseOffload() = 0 
,08-26 21:53:30.663   319  7101 V OMXCodec: OMXCodec::Create
08-26 21:53:30.663   319  7101 V OMXCodec: findMatchingCodecs()
08-26 21:53:30.663   319  7101 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-26 21:53:30.663   319  7101 V OMXCodec: matchingCodecs.size()=1
08-26 21:53:30.663   319  7101 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
08-26 21:53:30.664   319  7101 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-26 21:53:30.664   319  7101 V LGCodecAdapter: LG Codec Adapter start
08-26 21:53:30.664   319  7101 V OMXCodec: OMXCodec Createtor
08-26 21:53:30.664   319  7101 V OMXCodec: setComponentRole
08-26 21:53:30.665   319  7101 V OMXCodec: configureCodec protected=0
08-26 21:53:30.665   319  7101 V LGCodecAdapter: called getLGCodecSpecificData
08-26 21:53:30.665   319  7101 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-26 21:53:30.665   319  7101 V LGCodecOSAL: Called LGconfigureCodecMETA
08-26 21:53:30.665   319  7101 V LGCodecOSAL: Called LGconfigureCodecMSG
08-26 21:53:30.665   319  7101 V LGCodecOSAL: Not support LGCodec
08-26 21:53:30.665   319  7101 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-26 21:53:30.665   319  7101 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-26 21:53:30.665   319  7101 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-26 21:53:30.665   319  7101 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-26 21:53:30.665   319  7101 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-26 21:53:30.665   319  7101 V AudioSystem: isOffloadSupported()
08-26 21:53:30.665   319  7101 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-26 21:53:30.665   319  7101 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-26 21:53:30.665   319  7101 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-26 21:53:30.665   319  7101 V OMXCodec: init()
08-26 21:53:30.665   319  7101 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-26 21:53:30.665   319  7101 V OMXCodec: allocateBuffers
08-26 21:53:30.665   319  7101 V OMXCodec: allocateBuffersOnPort portIndex=0
08-26 21:53:30.665   319  7101 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-26 21:53:30.665   319  7101 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f79c0 on input port
08-26 21:53:30.665   319  7101 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ba0 on input port
08-26 21:53:30.665   319  7101 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c40 on input port
08-26 21:53:30.665   319  7101 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7e20 on input port
08-26 21:53:30.665   319  7101 V OMXCodec: allocateBuffersOnPort portIndex=1
08-26 21:53:30.665   319  7101 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-26 21:53:30.665   319  7101 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7e70 on output port
08-26 21:53:30.665   319  7101 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57bc060 on output port
08-26 21:53:30.665   319  7101 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57bc6a0 on output port
08-26 21:53:30.665   319  7101 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57bc740 on output port
08-26 21:53:30.665   319  7101 V OMXCodec: init() mAsyncCompletion wait!!! 
08-26 21:53:30.666   319  7103 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-26 21:53:30.666   319  7103 V OMXCodec: [OMX.google.vorbis.d,ecoder] Now Idle.
08-26 21:53:30.666   319  7103 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-26 21:53:30.666   319  7101 V OMXCodec: init() mAsyncCompletion wait!!! 
08-26 21:53:30.666   319  7103 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-26 21:53:30.666   319  7103 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-26 21:53:30.666   319  7103 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-26 21:53:30.666   319  7101 V OMXCodec: init() mAsyncCompletion wait free! 
,08-26 21:53:30.666   319  7101 V AwesomePlayer: finishAsyncPrepare_l() 
08-26 21:53:30.666   319  7101 V AudioCache: notify(0xb04095c0, 5, 0, 0)
08-26 21:53:30.666   319  7101 V AudioCache: ignored
08-26 21:53:30.666   319  7101 V AudioCache: notify(0xb04095c0, 1, 0, 0)
08-26 21:53:30.666   319  7101 V AudioCache: prepared
08-26 21:53:30.666   319  2203 V AudioCache: wait - success
08-26 21:53:30.666   319  2203 V MediaPlayerService: start
08-26 21:53:30.666   319  2203 V AwesomePlayer: play_l() 
08-26 21:53:30.666   319  2203 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-26 21:53:30.666   319  2203 V AwesomePlayer: createAudioPlayer_l
08-26 21:53:30.666   319  2203 V AwesomePlayer: seekAudioIfNecessary_l() 
08-26 21:53:30.666   319  2203 V AwesomePlayer: startAudioPlayer_l() 
08-26 21:53:30.666   319  2203 D AudioPlayer: start of Playback, useOffload 0
08-26 21:53:30.666   319  2203 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-26 21:53:30.666   319  2203 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
,08-26 21:53:30.667   319  7103 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-26 21:53:30.667   319  7103 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-26 21:53:30.667   319  7103 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-26 21:53:30.667   319  7103 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-26 21:53:30.667   319  7103 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-26 21:53:30.667   319  7103 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-26 21:53:30.667   319  7103 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885808
08-26 21:53:30.668   319  7103 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-26 21:53:30.668   319  7103 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044786272
,08-26 21:53:30.668   319  7103 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-26 21:53:30.668   319  7103 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044787872
08-26 21:53:30.668   319  7103 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-26 21:53:30.668   319  7103 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044788032
08-26 21:53:30.668   319  7103 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-26 21:53:30.668   319  7103 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-26 21:53:30.668   319  7103 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-26 21:53:30.668   319  7103 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-26 21:53:30.668   319  7103 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1,
08-26 21:53:30.668   319  7103 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-26 21:53:30.668   319  7103 V OMXCodec: allocateBuffersOnPort portIndex=1
08-26 21:53:30.668   319  7103 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-26 21:53:30.668   319  7103 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57bc6a0 on output port
08-26 21:53:30.668   319  7103 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57bc060 on output port
08-26 21:53:30.668   319  7103 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7e70 on output port
08-26 21:53:30.668   319  7103 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57bc9c0 on output port
,08-26 21:53:30.668   319  7103 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-26 21:53:30.668   319  7103 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-26 21:53:30.668  7054  7054 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-26 21:53:30.669   319  2203 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-26 21:53:30.669   319  2203 V AudioCache: notify(0xb04095c0, 6, 0, 0)
08-26 21:53:30.669   319  2203 V AudioCache: ignored
08-26 21:53:30.669   319  7104 V AudioCache: write(0xb16eb000, 4096)
08-26 21:53:30.669   319  7104 V AudioCache: memcpy(0xae602000, 0xb16eb000, 4096)
08-26 21:53:30.670   319  2203 V MediaPlayerService: wait for playback complete,
08-26 21:53:30.670  7054  7054 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-26 21:53:30.670   319  7104 V AudioCache: write(0xb16eb000, 4096)
08-26 21:53:30.670   319  7104 V AudioCache: memcpy(0xae603000, 0xb16eb000, 4096)
08-26 21:53:30.670   319  7104 V AudioCache: write(0xb16eb000, 4096)
08-26 21:53:30.670   319  7104 V AudioCache: memcpy(0xae604000, 0xb16eb000, 4096)
08-26 21:53:30.670  7054  7054 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-26 21:53:30.670  7054  7054 V BluetoothSapReceiver: SapReceiver onReceive 
08-26 21:53:30.671  7054  7054 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED,
08-26 21:53:30.671  7054  7054 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-26 21:53:30.671   319  7104 V AudioCache: write(0xb16eb000, 4096)
08-26 21:53:30.671   319  7104 V AudioCache: memcpy(0xae605000, 0xb16eb000, 4096)
08-26 21:53:30.671   319  7104 V AudioCache: write(0xb16eb000, 4096)
08-26 21:53:30.671   319  7104 V AudioCache: memcpy(0xae606000, 0xb16eb000, 4096)
08-26 21:53:30.671   319  7104 V AudioCache: write(0xb16eb000, 4096)
08-26 21:53:30.671   319  7104 V AudioCache: memcpy(0xae607000, 0xb16eb000, 4096)
08-26 21:53:30.671   319  7104 V AudioCache: write(0xb16eb000, 4096)
08-26 21:53:30.671   319  7104 V AudioCache: memcpy(0xae608000, 0xb16eb000, 4096)
,08-26 21:53:30.672   319  7104 V AudioCache: write(0xb16eb000, 4096)
08-26 21:53:30.672   319  7104 V AudioCache: memcpy(0xae609000, 0xb16eb000, 4096)
08-26 21:53:30.672   319  7104 V AudioCache: write(0xb16eb000, 4096)
08-26 21:53:30.672   319  7104 V AudioCache: memcpy(0xae60a000, 0xb16eb000, 4096)
08-26 21:53:30.672   319  7104 V AudioCache: write(0xb16eb000, 4096)
08-26 21:53:30.672   319  7104 V AudioCache: memcpy(0xae60b000, 0xb16eb000, 4096)
08-26 21:53:30.673   319  7104 V AudioCache: write(0xb16eb000, 4096)
08-26 21:53:30.673   319  7104 V AudioCache: memcpy(0xae60c000, 0xb16eb000, 4096)
08-26 21:53:30.674   319  7104 V AudioCache: write(0xb16eb000, 4096)
08-26 21:53:30.674   319  7104 V AudioCache: memcpy(0xae60d000, 0xb16eb000, 4096)
,08-26 21:53:30.674   319  7104 V AudioCache: write(0xb16eb000, 4096)
08-26 21:53:30.674   319  7104 V AudioCache: memcpy(0xae60e000, 0xb16eb000, 4096)
08-26 21:53:30.674   319  7104 V AudioCache: write(0xb16eb000, 4096)
08-26 21:53:30.674   319  7104 V AudioCache: memcpy(0xae60f000, 0xb16eb000, 4096)
08-26 21:53:30.674   319  7104 V AudioCache: write(0xb16eb000, 4096)
08-26 21:53:30.674   319  7104 V AudioCache: memcpy(0xae610000, 0xb16eb000, 4096)
08-26 21:53:30.676   319  7104 V AudioCache: write(0xb16eb000, 4096)
08-26 21:53:30.676   319  7104 V AudioCache: memcpy(0xae611000, 0xb16eb000, 4096)
,08-26 21:53:30.676   319  7104 V AudioCache: write(0xb16eb000, 4096)
08-26 21:53:30.676   319  7104 V AudioCache: memcpy(0xae612000, 0xb16eb000, 4096)
08-26 21:53:30.676   319  7104 V AudioCache: write(0xb16eb000, 4096)
08-26 21:53:30.676   319  7104 V AudioCache: memcpy(0xae613000, 0xb16eb000, 4096)
08-26 21:53:30.676   319  7104 V AudioCache: write(0xb16eb000, 4096)
08-26 21:53:30.676   319  7104 V AudioCache: memcpy(0xae614000, 0xb16eb000, 4096)
08-26 21:53:30.677   319  7104 V AudioCache: write(0xb16eb000, 4096)
08-26 21:53:30.677   319  7104 V AudioCache: memcpy(0xae615000, 0xb16eb000, 4096)
08-26 21:53:30.677   319  7104 V AudioCache: write(0xb16eb000, 4096)
08-26 21:53:30.677   319  7104 V AudioCache: memcpy(0xae616000, 0xb16eb000, 4096)
08-26 21:53:30.677   319  7104 V AudioCache: write(0xb16eb000, 4096)
08-26 21:53:30.677   319  7104 V AudioCache: memcpy(0xae617000, 0xb16eb000, 4096)
08-26 21:53:30.677   319  7104 V AudioCache: write(0xb16eb000, 4096)
08-26 21:53:30.677   319  7104 V AudioCache: memcpy(0xae618000, 0xb16eb000, 4096)
08-26 21:53:30.679   319  7104 V AudioCache: write(0xb16eb000, 4096)
08-26 21:53:30.679   319  7104 V AudioCache: memcpy(0xae619000, 0xb16eb000, 4096)
08-26 21:53:30.679   319  7104 V AudioCache: write(0xb16eb000, 4096)
08-26 21:53:30.679   319  7104 V AudioCache: memcpy(0xae61a000, 0xb16eb000, 4096)
08-26 21:53:30.679   319  7104 V AudioCache: write(0xb16eb000, 4096)
08-26 21:53:30.679   319  7104 V AudioCache: memcpy(0xae61b000, 0xb16eb000, 4096)
08-26 21:53:30.679   319  7104 V AudioCache: write(0xb16eb000, 4096)
08-26 21:53:30.679   319  7104 V AudioCache: memcpy(0xae61c000, 0xb16eb000, 4096)
08-26 21:53:30.680  7003  7003 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
08-26 21:53:30.680   319  7104 V AudioCache: write(0xb16eb000, 4096)
08-26 21:53:30.680   319  7104 V AudioCache: memcpy(0xae61d000, 0xb16eb000, 4096)
08-26 21:53:30.680   319  7104 V AudioCache: write(0xb16eb000, 4096)
08-26 21:53:30.680   319  7104 V AudioCache: memcpy(0xae61e000, 0xb16eb000, 4096)
08-26 21:53:30.680   319  7104 V AudioCache: write(0xb16eb000, 4096)
08-26 21:53:30.680   319  7104 V AudioCache: memcpy(0xae61f000, 0xb16eb000, 4096)
08-26 21:53:30.680   319  7104 V AudioCache: write(0xb16eb000, 4096)
08-26 21:53:30.680   319  7104 V AudioCache: memcpy(0xae620000, 0xb16eb000, 4096)
08-26 21:53:30.681   319  7104 V AudioCache: write(0xb16eb000, 4096)
08-26 21:53:30.681   319  7104 V AudioCache: memcpy(0xae621000, 0xb16eb000, 4096)
08-26 21:53:30.681   319  7104 V AudioCache: write(0xb16eb000, 4096)
08-26 21:53:30.682   319  7104 V AudioCache: memcpy(0xae622000, 0xb16eb000, 4096)
08-26 21:53:30.682   319  7104 V AudioCache: write(0xb16eb000, 4096)
08-26 21:53:30.682   319  7104 V AudioCache: memcpy(0xae623000, 0xb16eb000, 4096)
08-26 21:53:30.683   319  7104 V AudioCache: write(0xb16eb000, 4096)
08-26 21:53:30.683   319  7104 V AudioCache: memcpy(0xae624000, 0xb16eb000, 4096)
08-26 21:53:30.683  6850  6850 I UEI.SmartControl: Service initServices...
,08-26 21:53:30.683  6850  6850 D UEI.SmartControl: QS start get config
,08-26 21:53:30.683   319  7104 V AudioCache: write(0xb16eb000, 4096)
08-26 21:53:30.683   319  7104 V AudioCache: memcpy(0xae625000, 0xb16eb000, 4096)
08-26 21:53:30.684   319  7104 V AudioCache: write(0xb16eb000, 4096)
08-26 21:53:30.684   319  7104 V AudioCache: memcpy(0xae626000, 0xb16eb000, 4096)
08-26 21:53:30.684   319  7104 V AudioCache: write(0xb16eb000, 4096)
08-26 21:53:30.684   319  7104 V AudioCache: memcpy(0xae627000, 0xb16eb000, 4096)
08-26 21:53:30.684   319  7104 V AudioCache: write(0xb16eb000, 4096)
08-26 21:53:30.684   319  7104 V AudioCache: memcpy(0xae628000, 0xb16eb000, 4096)
08-26 21:53:30.685   319  7104 V AudioCache: write(0xb16eb000, 4096)
08-26 21:53:30.685   319  7104 V AudioCache: memcpy(0xae629000, 0xb16eb000, 4096)
08-26 21:53:30.685   319  7104 V AudioCache: write(0xb16eb000, 4096)
08-26 21:53:30.685   319  7104 V AudioCache: memcpy(0xae62a000, 0xb16eb000, 4096)
08-26 21:53:30.686   319  7104 V AudioCache: write(0xb16eb000, 4096)
08-26 21:53:30.686   319  7104 V AudioCache: memcpy(0xae62b000, 0xb16eb000, 4096)
08-26 21:53:30.686   319  7104 V AudioCache: write(0xb16eb000, 4096)
08-26 21:53:30.686   319  7104 V AudioCache: memcpy(0xae62c000, 0xb16eb000, 4096)
08-26 21:53:30.686   319  7104 V AudioCache: write(0xb16eb000, 4096)
08-26 21:53:30.686   319  7104 V AudioCache: memcpy(0xae62d000, 0xb16eb000, 4096)
08-26 21:53:30.687   319  7104 V AudioCache: write(0xb16eb000, 4096)
08-26 21:53:30.687   319  7104 V AudioCache: memcpy(0xae62e000, 0xb16eb000, 4096)
08-26 21:53:30.687   319  7104 V AudioCache: write(0xb16eb000, 4096)
08-26 21:53:30.687   319  7104 V AudioCache: memcpy(0xae62f000, 0xb16eb000, 4096)
08-26 21:53:30.688   319  7104 V AudioCache: write(0xb16eb000, 4096)
08-26 21:53:30.688   319  7104 V AudioCache: memcpy(0xae630000, 0xb16eb000, 4096)
08-26 21:53:30.688   319  7104 V AudioCache: write(0xb16eb000, 4096)
08-26 21:53:30.688   319  7104 V AudioCache: memcpy(0xae631000, 0xb16eb000, 4096)
08-26 21:53:30.688   319  7104 V AudioCache: write(0xb16eb000, 4096)
08-26 21:53:30.688   319  7104 V AudioCache: memcpy(0xae632000, 0xb16eb000, 4096)
08-26 21:53:30.689   319  7104 V AudioCache: write(0xb16eb000, 4096)
08-26 21:53:30.689   319  7104 V AudioCache: memcpy(0xae633000, 0xb16eb000, 4096)
08-26 21:53:30.689   319  7103 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-26 21:53:30.689   319  7104 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-26 21:53:30.689   319  7104 V AwesomePlayer: postAudioEOS() 
08-26 21:53:30.689   319  7104 V AudioCache: write(0xb16eb000, 280)
08-26 21:53:30.689   319  7104 V AudioCache: memcpy(0xae634000, 0xb16eb000, 280)
08-26 21:53:30.691   319  7101 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-26 21:53:30.691   319  7101 V AwesomePlayer: onStreamDone
08-26 21:53:30.691   319  7101 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-26 21:53:30.691   319  7101 V AudioCache: notify(0xb04095c0, 2, 0, 0)
08-26 21:53:30.691   319  7101 V AudioCache: playback complete
08-26 21:53:30.691   319  7101 V AwesomePlayer: pause_l() 
08-26 21:53:30.691   319  7101 V AudioCache: notify(0xb04095c0, 7, 0, 0)
08-26 21:53:30.691   319  7101 V AudioCache: ignored
08-26 21:53:30.691   319  7101 V AwesomePlayer: cancelPlayerEvents
08-26 21:53:30.691   319  2203 V AudioCache: wait - success
08-26 21:53:30.691   319  2203 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-26 21:53:30.691   319  7101 D AudioPlayer: Pause Playback at 1068125
08-26 21:53:30.691   319  2203 V AwesomePlayer: reset_l() 
08-26 21:53:30.691   319  2203 V AudioCache: notify(0xb04095c0, 8, 0, 0)
08-26 21:53:30.691   319  2203 V AudioCache: ignored
08-26 21:53:30.691   319  2203 V AwesomePlayer: cancelPlayerEvents
08-26 21:53:30.691   319  2203 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-26 21:53:30.691   319  2203 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-26 21:53:30.691   319  2203 V OMXCodec: ,[OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-26 21:53:30.691   319  2203 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-26 21:53:30.691   319  2203 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-26 21:53:30.691   319  7103 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-26 21:53:30.691   319  7103 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-26 21:53:30.691   319  7103 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-26 21:53:30.691   319  7103 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7e20 on port 0
08-26 21:53:30.691   319  7103 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-26 21:53:30.691   319  7103 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7c40 on port 0
08-26 21:53:30.691   319  7103 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-26 21:53:30.691   319  7103 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ba0 on port 0
08-26 21:53:30.691   319  7103 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-26 21:53:30.692   319  7103 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f79c0 on port 0
08-26 21:53:30.692   319  7103 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-26 21:53:30.692   319  7103 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-26 21:53:30.692   319  7103 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb57bc9c0 on port 1
08-26 21:53:30.692   319  7103 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-26 21:53:30.692   319  7103 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7e70 on port 1
08-26 21:53:30.692   319  7103 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-26 21:53:30.692   319  7103 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb57bc060 on port 1
08-26 21:53:30.692   319  7103 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-26 21:53:30.692   319  7103 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb57bc6a0 on port 1
08-26 21:53:30.692   319  7103 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-26 21:53:30.692   319  7103 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-26 21:53:30.692   319  2203 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-26 21:53:30.692   319  2203 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-26 21:53:30.692   319  7103 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-26 21:53:30.692   319  7103 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-26 21:53:30.692   319  7103 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-26 21:53:30.692   319  2203 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-26 21:53:30.692   319  2203 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-26 21:53:30.692   319  2203 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-26 21:53:30.693   319  2203 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-26 21:53:30.693   319  2203 D AudioPlayer: AudioPlayer releasing audio source
08-26 21:53:30.693   319  2203 D AudioPlayer: AudioPlayer done releasing audio source
08-26 21:53:30.693   319  2203 V AwesomePlayer: reset_l() 
08-26 21:53:30.693   319  2203 V AwesomePlayer: cancelPlayerEvents
08-26 21:53:30.693   319  2203 V AwesomePlayer: ~AwesomePlayer call
08-26 21:53:30.693   319  2203 V AwesomePlayer: reset_l() 
08-26 21:53:30.693   319  2203 V AwesomePlayer: cancelPlayerEvents
08-26 21:53:30.693  6981  7099 V SoundPool: close(30)
08-26 21:53:30.693  6981  7099 V SoundPool: pointer = 0x9fe53000, size = 205080, sampleRate = 48000, numChannels = 2
08-26 21:53:30.705  6981  6981 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to ,loading view
08-26 21:53:30.705  6981  6981 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
,08-26 21:53:30.706  6981  6981 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:4596
08-26 21:53:30.924  6850  6850 I UEI.SmartControl: Supports setup maps: true
,08-26 21:53:30.927  6850  6850 D UEI.SmartControl: QS start statue = true Error code = 0
,08-26 21:53:30.927  6850  6850 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-26 21:53:30.927  6850  6850 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-26 21:53:30.927  6850  6850 I UEI.SmartControl: ### init IR Blaster...
08-26 21:53:30.930  6850  6850 D serial_port: Configuring serial port
08-26 21:53:30.930  6850  6850 E UEI.SmartControl: UEIBLaster setting for 616
08-26 21:53:30.930  6850  6850 I UEI.SmartControl: Setting serial record hearder size = 2
08-26 21:53:30.930  6850  6850 I UEI.SmartControl: configuring settings for MAXQ616
08-26 21:53:30.930  6850  6850 I UEI.SmartControl: Get version...
08-26 21:53:30.949  6850  7106 D UEI.SmartControl: serial port data available: 21
,08-26 21:53:30.977  6850  6850 D UEI.SmartControl: MAXQ616 A2-X4 software.
,08-26 21:53:30.977  6850  6850 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-26 21:53:30.977  6850  6850 I UEI.SmartControl: QS saving settings...
08-26 21:53:30.980  6850  6850 D UEI.SmartControl: IR Blaster version: 25672567
,08-26 21:53:30.996  6850  7106 D UEI.SmartControl: serial port data available: 4
,08-26 21:53:31.025  6850  6850 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-26 21:53:31.034  6850  6850 E UEI.SmartControl: Services init done
08-26 21:53:31.034  6850  6850 D UEI.SmartControl: QS Service init finished
,08-26 21:53:31.039  6850  6850 D UEI.SmartControl: QS Service version name: 2.1.91
08-26 21:53:31.039  6850  6850 D UEI.SmartControl: QS Service version code: 201091
08-26 21:53:31.040  6850  6850 D UEI.SmartControl: Service requested: Control
08-26 21:53:31.040  6850  7115 I UEI.SmartControl: Device manager: loading config....
08-26 21:53:31.041  6850  7115 D UEI.SmartControl: ----------- loading internal config...
08-26 21:53:31.050  6850  7115 E UEI.SmartControl: Loading SETTINGS...
,08-26 21:53:31.050  6850  6850 D UEI.SmartControl: Request IControl service: devices are loaded...
08-26 21:53:31.053  6850  6850 D UEI.SmartControl: Internal service binding...
08-26 21:53:31.054  6981  6981 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-26 21:53:31.055  6850  6865 I UEI.SmartControl: ------ IControl API: 11
08-26 21:53:31.055  6850  6865 D UEI.SmartControl: File observer start...
08-26 21:53:31.056  6850  6865 E UEI.SmartControl: IR Port is disabled: false
08-26 21:53:31.056  6850  6865 D UEI.SmartControl: Starting file observer...
08-26 21:53:31.057  6850  6865 I UEI.SmartControl: Registering callback...
08-26 21:53:31.058  6850  6865 I UEI.SmartControl: ------ IControl API: 19
08-26 21:53:31.059  6850  6865 I UEI.SmartControl: Registering Services Ready callback...
08-26 21:53:31.063  6850  7115 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,08-26 21:53:31.071  1034  1378 V AlarmManager: RTC_WAKEUP set : Alarm{24f837a1 type 0 when 1472241211066 com.android.vending} when 1472241211066
08-26 21:53:31.073  6850  7111 I UEI.SmartControl: Notify AllClients services are ready: 0
08-26 21:53:31.073  6850  7111 D UEI.SmartControl: -----service ready thread exits
08-26 21:53:31.074  6981  6997 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-26 21:53:31.075  6981  7097 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-26 21:53:31.075  6981  7097 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-26 21:53:31.076  6981  6981 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-26 21:53:31.076  6981  6981 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-26 21:53:31.077  6850  6866 I UEI.SmartControl: ------ IControl API: 8
08-26 21:53:31.078  6981  6981 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-26 21:53:31.078  6981  6981 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-26 21:53:31.079  6981  6981 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-26 21:53:31.079  6981  6981 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-26 21:53:31.080  6981  6981 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-26 21:53:31.081  6981  6981 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-26 21:53:31.085  6981  6981 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
,08-26 21:53:31.087  6981  6981 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-26 21:53:31.088  6981  6981 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-26 21:53:31.091  6981  6981 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-26 21:53:31.092  6981  6981 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-26 21:53:31.093  6981  6981 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-26 21:53:31.094  6981  6981 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-26 21:53:31.094  6981  6981 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-26 21:53:31.095  6981  6981 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1472241211095]
08-26 21:53:31.099  6981  6981 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
,08-26 21:53:31.102  1034  2030 I ActivityManager: Killing 6550:com.lge.email/u0a23 (adj 15): empty #17
08-26 21:53:31.131  6981  7117 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-26 21:53:31.156  1034  1614 V SIM_STK : Menu title from STK is T-Mobile
,08-26 21:53:31.194  1034  1732 W libprocessgroup: failed to open /acct/uid_10023/pid_6550/cgroup.procs: No such file or directory
,08-26 21:53:31.202  6981  6981 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
08-26 21:53:31.203  6981  6981 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-26 21:53:31.204  6981  6981 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-26 21:53:31.204  6981  6981 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-26 21:53:31.204  6981  6981 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-26 21:53:31.205  6981  6981 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
,08-26 21:53:31.205  6981  6981 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
,08-26 21:53:31.207  1034  1378 V AlarmManager: ELAPSED_WAKEUP set : Alarm{628edc6 type 2 when 123963 com.google.android.gms} when 123963
08-26 21:53:31.215  6981  6981 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,08-26 21:53:31.373  6613  6613 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.
,08-26 21:53:31.379  1034  2030 I ActivityManager: Killing 6582:com.android.gallery3d/u0a27 (adj 15): empty #17
,08-26 21:53:31.464  1034  1576 W libprocessgroup: failed to open /acct/uid_10027/pid_6582/cgroup.procs: No such file or directory
,08-26 21:53:31.967  1034  1975 D WifiServiceImplEx: setWifiEnabled: true pid=6674, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,08-26 21:53:31.968  1034  1975 D WifiService: setWifiEnabled: true pid=6674, uid=10118
08-26 21:53:31.968  1034  1975 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-26 21:53:31.999  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-26 21:53:31.999  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-26 21:53:31.999  1034  1034 D Ulp_jni : JNI:system_update. Event-4
,08-26 21:53:32.003  1034  1537 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
,08-26 21:53:32.003  1034  1537 I LGFTMITEM: [GET_FTM][id=6], offset=12288
,08-26 21:53:32.006  1034  1537 E WifiUtil: wfc_util_ffile_check_copy(): pid[1034] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-26 21:53:32.006  1034  1537 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-26 21:53:32.006  1034  1537 E WifiUtil: wfc_util_ffile_check_copy(): pid[1034] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-26 21:53:32.006  1034  1537 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-26 21:53:32.006  1034  1537 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-26 21:53:32.006  1034  1537 E WifiHW  : unknown target_country: EU , set to default
08-26 21:53:32.006  1034  1537 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-26 21:53:32.006  1034  1537 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-26 21:53:32.006  1034  1537 I WifiUtil: gEnableBmps=1
08-26 21:53:32.067  1034  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-26 21:53:32.093  1034  1105 D Tethering: MasterInitialState.processMessage what=3
,08-26 21:53:32.105  6674  6674 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 21:53:32.110  6674  6674 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 21:53:32.117  1034  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-26 21:53:32.123  1034  1105 D Tethering: MasterInitialState.processMessage what=3
08-26 21:53:32.133  6674  6674 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 21:53:32.136  6674  6674 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 21:53:32.137  1034  1090 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-26 21:53:32.139  6448  6448 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-26 21:53:32.152  5837  5837 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-26 21:53:32.159  5837  5837 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-26 21:53:32.160  6448  6478 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-26 21:53:32.196  2205  2205 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-26 21:53:32.231  1034  1090 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-26 21:53:32.276  1034  1576 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7154 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
08-26 21:53:32.279  1034  1090 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 21:53:32.280  1034  1090 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-26 21:53:32.388  7154  7154 I AppUp4:AppBoxCP: onCreate
08-26 21:53:32.389  7154  7154 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,08-26 21:53:32.400  7154  7154 I AppUp4:DB:  setFingerPrint start
,08-26 21:53:32.400  7154  7154 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
08-26 21:53:32.409  7154  7154 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
,08-26 21:53:32.409  7154  7154 I AppUp4:DB:  SDK version = 21
08-26 21:53:32.409  7154  7154 I AppUp4:DB:  beforefinger == newfinger no write in DB
08-26 21:53:32.412  7154  7154 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
,08-26 21:53:32.413  7154  7154 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
,08-26 21:53:32.413  7154  7154 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-26 21:53:32.416  7154  7154 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-26 21:53:32.416  7154  7154 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-26 21:53:32.424  7154  7154 I AppUp4:CustModeStarterReceiver: onReceive
,08-26 21:53:32.468  7154  7154 D LgDataFeature: LgDataFeature() Constructor: none
,08-26 21:53:32.468  7154  7154 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-26 21:53:32.484  7154  7154 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@b1b8426
,08-26 21:53:32.485  7154  7154 D AppUp4:CustFacade: isCustomizationCompleted : false
08-26 21:53:32.485  7154  7154 D AppUp4:CustFacade: isPhone : true
08-26 21:53:32.486  7154  7154 D AppUp4:CustModeStarterReceiver: begin check event
08-26 21:53:32.488  7154  7154 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
08-26 21:53:32.489  7154  7154 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
08-26 21:53:32.490  7154  7174 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
08-26 21:53:32.490  7154  7174 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
08-26 21:53:32.490  7154  7174 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
08-26 21:53:32.492  1034  1975 I ActivityManager: Killing 6694:com.google.android.apps.docs/u0a61 (adj 15): empty #17
08-26 21:53:32.523  1034  2033 W libprocessgroup: failed to open /acct/uid_10061/pid_6694/cgroup.procs: No such file or directory
08-26 21:53:32.525  4754  4754 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-26 21:53:32.526  4754  4754 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-26 21:53:32.528  4754  4754 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 21:53:32.531  4754  4754 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 21:53:32.535  4754  7186 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-26 21:53:32.537  4754  7187 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-26 21:53:32.538  4754  7187 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-26 21:53:32.598  1034  1940 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7188 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-26 21:53:32.625   345   345 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 571us total 22.700ms
,08-26 21:53:32.648   345   345 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 444us total 20.846ms
,08-26 21:53:32.658  1034  1105 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-26 21:53:32.668   314   879 D SoftapController: Softap fwReload - Ok
08-26 21:53:32.672  1034  1105 D Tethering: InitialState.processMessage what=4
08-26 21:53:32.676  1034  1537 E NetdConnector: NDC Command {52 softap fwreload wlan0 STA} took too long (664ms)
08-26 21:53:32.677   345   345 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 444us total 27.035ms
,08-26 21:53:32.678  1034  1105 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-26 21:53:32.679   314   879 D CommandListener: Setting iface cfg
,08-26 21:53:32.679   314   879 D CommandListener: Trying to bring down wlan0
08-26 21:53:32.680   314   879 D CommandListener: Clearing all IP addresses on wlan0
08-26 21:53:32.683  1034  1537 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
08-26 21:53:32.685  1034  1537 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-26 21:53:32.685  1034  1537 E WifiStateMachine: useWiFiOffloading() : false
08-26 21:53:32.685  1034  1537 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-26 21:53:32.688  1942  1942 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-26 21:53:32.689  6674  6674 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 21:53:32.689  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-26 21:53:32.690  6674  6674 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 21:53:32.679  7210  7210 W wpa_supplicant: type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 21:53:32.679  7210  7210 W wpa_supplicant: type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 21:53:32.693  1034  1537 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-26 21:53:32.693  1034  1537 D WifiMonitor: connecting to supplicant
08-26 21:53:32.701  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
,08-26 21:53:32.714  7210  7210 I wpa_supplicant: Successfully initialized wpa_supplicant
08-26 21:53:32.720  7188  7188 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-26 21:53:32.720  7188  7188 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-26 21:53:32.722  7188  7188 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-26 21:53:32.722  7188  7188 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-26 21:53:32.744  7210  7210 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-26 21:53:32.744  7210  7210 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,08-26 21:53:32.800  7188  7188 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-26 21:53:32.811  7188  7188 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
08-26 21:53:32.840  7188  7188 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-26 21:53:32.846  7210  7210 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-26 21:53:32.864  7188  7188 D LgDataFeature: LgDataFeature() Constructor: none
08-26 21:53:32.864  7188  7188 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-26 21:53:32.920  7210  7210 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-26 21:53:32.935  7210  7210 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
08-26 21:53:32.935  7210  7210 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-26 21:53:32.938  1034  1537 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-26 21:53:32.938  1034  7217 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
08-26 21:53:32.938  1034  7217 D WifiMonitor: Dropping event because (p2p0) is stopped
08-26 21:53:32.938  1034  7217 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-26 21:53:32.939  1034  7217 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-26 21:53:32.939  1034  7217 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-26 21:53:32.939  1034  7217 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,08-26 21:53:32.939  1034  1537 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-26 21:53:32.941  1034  1537 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-26 21:53:32.942  1034  1537 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-26 21:53:32.943  1034  1537 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-26 21:53:32.944  1034  1537 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-26 21:53:32.946  1034  1537 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-26 21:53:32.947  1034  1537 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-26 21:53:32.948  1034  1537 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-26 21:53:32.948  1034  1537 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-26 21:53:32.949  1034  1537 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-26 21:53:32.949  1034  1537 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-26 21:53:32.949  1034  1537 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
,08-26 21:53:32.951  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 21:53:32.951  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 21:53:32.951  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 21:53:32.951  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 21:53:32.951  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-26 21:53:32.951  1034  1537 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-26 21:53:32.951  1034  1537 E WifiStateMachine: useWiFiOffloading() : false
08-26 21:53:32.951  1034  1537 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-26 21:53:32.954  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 21:53:32.954  1034  1537 D WifiNative-wlan0: doBoolean: SET update_config 1
08-26 21:53:32.955  1034  1537 D WifiNative-wlan0: SET update_config 1: returned true
08-26 21:53:32.955  1034  1537 D WifiConfigStore: Loading config and enabling all networks 
08-26 21:53:32.955  1034  1537 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-26 21:53:32.955  1034  1537 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-26 21:53:32.956  1942  1942 D WfdService: Waiting for WifiP2p enabling
08-26 21:53:32.960  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-26 21:53:32.961  6674  6674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 21:53:32.961  6674  6674 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 21:53:32.961  6674  6674 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 21:53:32.961  6674  6674 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 21:53:32.961  6674  6674 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 21:53:32.961  6674  6674 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 21:53:32.961  6674  6674 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 21:53:32.961  6674  6674 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 21:53:32.961  6674  6674 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 21:53:32.961  6674  6674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 21:53:32.961  1034  1541 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-26 21:53:32.961  6674  6674 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-26 21:53:32.963  6674  6674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 21:53:32.963  6674  6674 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 21:53:32.963  6674  6674 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 21:53:32.963  6674  6674 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 21:53:32.963  6674  6674 V io.jxcore.node.Co,nnectivityMonitor:     - is Wi-Fi enabled: true
08-26 21:53:32.963  6674  6674 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 21:53:32.963  6674  6674 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 21:53:32.963  6674  6674 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 21:53:32.963  6674  6674 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 21:53:32.963  6674  6674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 21:53:32.963  6674  6674 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-26 21:53:32.964  1034  1537 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-26 21:53:32.977  1034  1537 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-26 21:53:32.977  1034  1537 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-26 21:53:32.979  1034  1537 D WifiStateMachine: enableVerboseLogging : level 2
08-26 21:53:32.979  1034  1537 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-26 21:53:32.979  1034  1537 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-26 21:53:32.979  1034  1537 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-26 21:53:32.980  1034  1537 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-26 21:53:32.980  1034  1537 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-26 21:53:32.980  1034  1537 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-26 21:53:32.980  1034  1537 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-26 21:53:32.980  1034  1537 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-26 21:53:32.980  1034  1537 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-26 21:53:32.981  1034  1537 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-26 21:53:32.981  1034  1537 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-26 21:53:32.981  1034  1537 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-26 21:53:32.981  1034  1537 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-26 21:53:32.981  1034  1537 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-26 21:53:32.982  1034  1537 D WifiStateMachine: Setting OUI to DA-A1-19
08-26 21:53:32.982  1034  1537 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-26 21:53:32.983  1942  1942 D WfdsService: Supplicant Connection state is changed : true
08-26 21:53:32.983  1942  2307 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-26 21:53:32.983  1942  2307 D WfdsService: Set the WFDS Monitor: true
08-26 21:53:32.983  1942  2307 D WfdsMonitor: WfdsMonitorThread create
08-26 21:53:32.983  1034  1537 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-26 21:53:32.983  1034  1537 D WifiNative-HAL: Setting external_sim to 1
08-26 21:53:32.983  1034  1537 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-26 21:53:32.983  1942  2307 D WfdsMonitor: WFDS Monitor is created and started
08-26 21:53:32.983  1942  2307 D WfdsService: WiFi: Supplicant connection re-established
08-26 21:53:32.983  1034  1537 D WifiNative-wlan0: SET external_sim 1: returned true
08-26 21:53:32.983  1034  1537 I WifiNative-HAL: startHal
08-26 21:53:32.983  1034  1537 D wifi    : setting scan oui 0x953ec3e0
08-26 21:53:32.984  1942  7218 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-26 21:53:32.984  1034  1537 D WifiStateMachine: Setting OUI to DA-A1-19
08-26 21:53:32.984  1034  1537 I WifiNative-HAL: startHal
08-26 21:53:32.984  1034  1537 D wifi    : setting scan oui 0x953ec3e0
08-26 21:53:32.984  1034  1537 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-26 21:53:32.984  1942  7218 E CtrlSupplicant: Succeed to open control connection
08-26 21:53:32.984  1942  7218 E CtrlSupplicant: Succeed to open monitor connection
08-26 21:53:32.984  1034  1537 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-26 21:53:32.985  1034  1537 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-26 21:53:32.985  7210  7210 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-26 21:53:32.985  1942  7218 D WfdsMonitor: Supplicant connection established
08-26 21:53:32.985  1942  2307 D WfdsService: Connected to the supplicant for wfds
08-26 21:53:32.985  1034  1537 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-26 21:53:32.985  1034  1537 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-26 21:53:32.985  7210  7210 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-26 21:53:32.986  1034  1537 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-26 21:53:32.986  1034  1537 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-26 21:53:32.986  7210  7210 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-26 21:53:32.986  1034  1537 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-26 21:53:32.987  1034  1537 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-26 21:53:32.987  7210  7210 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-26 21:53:32.987  1034  1537 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-26 21:53:32.987  1034  1537 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-26 21:53:32.987  7210  7210 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-26 21:53:32.988  1034  1537 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-26 21:53:32.988  1034  1537 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-26 21:53:32.988  7210  7210 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-26 21:53:32.988  1034  1537 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
,08-26 21:53:32.988  1034  1537 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-26 21:53:32.988  7210  7210 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-26 21:53:32.989  1034  1537 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-26 21:53:32.990  1034  1537 E WifiNative: : [125,745,755 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-26 21:53:32.990  1034  1537 D WifiNative-wlan0: doBoolean: RECONNECT
08-26 21:53:32.990  1034  1537 D WifiNative-wlan0: RECONNECT: returned true
08-26 21:53:32.990  1034  1537 D WifiNative-wlan0: doString: [STATUS]
08-26 21:53:32.991  1034  7217 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-26 21:53:32.991  1034  7217 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-26 21:53:32.992  1034  1537 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-26 21:53:32.992  1034  1537 D WifiNative-wlan0: doBoolean: SET ps 1
08-26 21:53:32.992  1034  1537 D WifiNative-wlan0: SET ps 1: returned true
08-26 21:53:32.992  1034  1536 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-26 21:53:32.994  1034  1034 D WifiScanningService: SCAN_AVAILABLE : 3
08-26 21:53:32.994  1034  1557 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-26 21:53:32.994   314   879 D CommandListener: Setting iface cfg
08-26 21:53:32.994  1034  1557 I WifiNative-HAL: startHal
08-26 21:53:32.994   314   879 D CommandListener: Trying to bring up p2p0
08-26 21:53:32.994  1034  1034 D RttService: SCAN_AVAILABLE : 3
08-26 21:53:32.994  1034  1557 D wifi    : getting scan capabilities on interface[1] = 0x953ec3e0
08-26 21:53:32.994  1034  1557 D wifi    : failed to get capabilities : -3
08-26 21:53:32.994  1034  1557 E WifiScanningService: could not get scan capabilities
08-26 21:53:32.994  1034  1558 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-26 21:53:32.994  1034  1536 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-26 21:53:32.994  1034  1536 D LGWifiP2pService: P2pEnablingState
08-26 21:53:32.994  1034  1536 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-26 21:53:32.994  1034  1536 D LGWifiP2pService: P2p socket connection successful
08-26 21:53:32.994  1034  1536 D LGWifiP2pService: P2pEnabledState
08-26 21:53:32.994  1034  1536 D LGWifiP2pService: sending p2p connection changed broadcast
08-26 21:53:32.995  1034  1536 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-26 21:53:32.996  1942  1942 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-26 21:53:32.996  1942  1942 D WfdsService: WifiP2pState is changed : true
08-26 21:53:32.996  1034  1536 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-26 21:53:32.996  1942  1942 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-26 21:53:32.996  1034  1536 D WifiNative-p2p0: doBoolean: SET device_name G3
08-26 21:53:32.997  1034  1536 D WifiNative-p2p0: SET device_name G3: returned true
08-26 21:53:32.997  1034  1537 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-26 21:53:32.997  1034  1536 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-26 21:53:32.997  1034  1536 D LGWifiP2pService: before postfix = G3
08-26 21:53:32.997  1034  1536 D WifiServerServiceExt: postfix byte check : 2
08-26 21:53:32.997  1034  1536 D LGWifiP2pService: after postfix = G3
08-26 21:53:32.997  1034  1536 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-26 21:53:32.997  1942  2307 D WfdsService: Receive the WFDS_ENABLE Method
08-26 21:53:32.997  1942  2307 D WfdsService: Set the WFDS Monitor: true
08-26 21:53:32.997  1034  1537 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-26 21:53:32.997  1034  1536 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-26 21:53:32.997  1942  2307 D WfdsService: Connected to the supplicant for wfds
08-26 21:53:32.997  1034  1536 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-26 21:53:32.997  1942  2307 D WfdsJNI : doCommand: WFDS_SET TRUE
08-26 21:53:32.997  7210  7210 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-26 21:53:32.997  1034  1537 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-26 21:53:32.998  1942  2307 D WfdsService: selectPreferredScanChannel [36]
08-26 21:53:32.998  1942  2307 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-26 21:53:32.998  1034  1536 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-26 21:53:32.998  1034  1536 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-26 21:53:32.998  1034  1537 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-26 21:53:32.998  1034  1536 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-26 21:53:32.998  1034  1536 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-26 21:53:32.998  1942  1942 D WfdsService: isConnected: false
08-26 21:53:32.998  1034  1537 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-26 21:53:32.999  1034  1537 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-26 21:53:32.999  1034  1537 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-26 21:53:32.999  1034  1537 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-26 21:53:32.999  7210  7210 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-26 21:53:32.999  1034  1536 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-26 21:53:32.999  1034  1536 D WifiNative-HAL: p2pGetDeviceAddress
08-26 21:53:32.999  1034  1537 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-26 21:53:33.000  1034  1536 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-26 21:53:33.000  1034  1537 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-26 21:53:33.000  1034  1536 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-26 21:53:33.000  1034  1536 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-26 21:53:33.000  1034  1537 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-26 21:53:33.000  1034  1537 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-26 21:53:33.000  7210  7210 E wpa_supplicant: disconnect_rssi_lvl: -100
08-26 21:53:33.001  1034  1537 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
08-26 21:53:33.001  1034  1537 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
08-26 21:53:33.001  1034  1537 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
08-26 21:53:33.001  1942  1942 I WfdStateTracker: handleP2pThisDeviceChanged
08-26 21:53:33.001  1034  1536 D WifiNative-p2p0: P2P_FLUSH: returned true
08-26 21:53:33.001  1034  1537 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-26 21:53:33.001  1034  1536 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-26 21:53:33.002  1942  1942 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-26 21:53:33.002  1942  1942 D WfdsService: Update P2p Interface State: 3
08-26 21:53:33.002  7210  7210 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-26 21:53:33.011  7210  7210 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 21:53:33.012  1034  7217 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-26 21:53:33.012  1034  7217 E WifiMonitor: WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 21:53:33.012  1034  7217 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 21:53:33.012  1034  7217 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 21:53:33.013  7210  7210 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-26 21:53:33.013  7210  7210 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 21:53:33.013  1034  1537 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-26 21:53:33.013  1034  1537 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-26 21:53:33.014  1034  7217 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 21:53:33.014  1034  7217 E WifiMonitor: WifiMonitor:p2p0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 21:53:33.014  1942  7218 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 21:53:33.014  1034  7217 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 21:53:33.014  1034  7217 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 21:53:33.014  1034  1537 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-26 21:53:33.014  1034  1537 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-26 21:53:33.014  1034  1537 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-26 21:53:33.015  1034  1536 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-26 21:53:33.015  7210  7210 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 21:53:33.015  1034  1536 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-26 21:53:33.015  1034  7217 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 21:53:33.015  1034  7217 E WifiMonitor: WifiMonitor:p2p0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 21:53:33.015  1034  7217 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 21:53:33.015  1034  7217 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 21:53:33.016  1942  7218 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 21:53:33.017  7188  7188 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-26 21:53:33.018  1034  1536 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-26 21:53:33.018  1034  1536 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-26 21:53:33.018  7210  7210 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-26 21:53:33.018  7210  7210 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-26 21:53:33.018  1034  7217 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-26 21:53:33.018  1034  7217 E WifiMonitor: WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-26 21:53:33.018  1034  7217 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-26 21:53:33.019  1034  7217 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-26 21:53:33.019  1034  1537 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-26 21:53:33.019  1034  1537 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-26 21:53:33.020  1034  1537 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-26 21:53:33.020  1034  1537 D WifiNative-wlan0: doBoolean: SCAN
08-26 21:53:33.020  1034  1537 D WifiNative-wlan0: SCAN: returned false
08-26 21:53:33.021  1034  1537 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=125777  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-26 21:53:33.022  1034  1537 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=125779  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-26 21:53:33.022  1034  1537 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-26 21:53:33.023  1034  1537 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-26 21:53:33.023  1034  1537 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-26 21:53:33.023  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 21:53:33.023  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 21:53:33.023  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-26 21:53:33.023  1034  1537 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-26 21:53:33.024  1034  1537 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-26 21:53:33.024  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 21:53:33.024  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 21:53:33.024  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 21:53:33.024  1034  1034 D WifiServerServiceExt: setSupplicantStateSCANNING
08-26 21:53:33.025  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 21:53:33.033  1034  1536 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-26 21:53:33.033  1034  1536 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-26 21:53:33.033  1034  1536 D LGWifiP2pService: InactiveState
08-26 21:53:33.033  1034  1536 D LGWifiP2pService: InactiveState{ when=-20ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-26 21:53:33.033  1034  1536 D LGWifiP2pService: P2pEnabledState{ when=-20ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-26 21:53:33.033  1034  1536 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
,08-26 21:53:33.034  7210  7210 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-26 21:53:33.034  7210  7210 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 21:53:33.035  1034  7217 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-26 21:53:33.035  1034  7217 E WifiMonitor: WifiMonitor:p2p0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 21:53:33.035  1034  7217 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 21:53:33.035  1034  7217 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 21:53:33.035  1942  7218 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-26 21:53:33.035  7210  7210 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-26 21:53:33.035  7210  7210 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 21:53:33.035  1942  7218 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 21:53:33.035  1034  7217 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 21:53:33.035  1034  7217 E WifiMonitor: WifiMonitor:p2p0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 21:53:33.035  1034  7217 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 21:53:33.035  1034  7217 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 21:53:33.035  7210  7210 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 21:53:33.036  1034  1536 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-26 21:53:33.036  1034  1536 D LGWifiP2pService: InactiveState{ when=-21ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-26 21:53:33.036  1034  1536 D LGWifiP2pService: P2pEnabledState{ when=-21ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-26 21:53:33.036  1034  1536 D LGWifiP2pService: InactiveState{ when=-3ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-26 21:53:33.036  1034  1536 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-26 21:53:33.036  1034  1536 D LGWifiP2pService: DefaultState{ when=-3ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-26 21:53:33.036  1034  1536 D LGWifiP2pService: InactiveState{ when=-3ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-26 21:53:33.036  1034  1536 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-26 21:53:33.036  1034  1536 D LGWifiP2pService: DefaultState{ when=-3ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-26 21:53:33.036  1034  1536 D LGWifiP2pService: InactiveState{ when=-3ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-26 21:53:33.036  1034  1536 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-26 21:53:33.036  1034  1536 D LGWifiP2pService: DefaultState{ when=-4ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-26 21:53:33.037  1034  1536 D LGWifiP2pService: InactiveState{ when=-5ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-26 21:53:33.038  1034  1536 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-26 21:53:33.038  1034  1536 D LGWifiP2pService: DefaultState{ when=-5ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-26 21:53:33.038  1942  7218 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 21:53:33.038  1034  7217 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 21:53:33.038  1034  7217 E WifiMonitor: WifiMonitor:p2p0 cnt=30 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 21:53:33.038  1034  7217 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 21:53:33.038  1034  7217 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 21:53:33.038  1034  1034 E WifiServerServiceExt: No p2p device connected
08-26 21:53:33.038  1942  2307 W WfdsService: DefaultState - msg [9441285] is not handled
08-26 21:53:33.052  3203  3203 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-26 21:53:33.052  3203  3203 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-26 21:53:33.052  3203  3203 I LgeMiscReceiver: networkInfo.isConnected() = false
,08-26 21:53:33.056  7188  7188 I HubEmail: JNI_OnLoad()
08-26 21:53:33.056  7188  7188 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-26 21:53:33.056  7188  7188 I HubEmail: registerNatives()
08-26 21:53:33.056  7188  7188 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-26 21:53:33.057  7188  7188 I HubEmail: registerNativeMethods()
08-26 21:53:33.057  7188  7188 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-26 21:53:33.057  7188  7188 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,08-26 21:53:33.103  1034  2006 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7224 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
08-26 21:53:33.107  7024  7221 W FormManager: Network not available. Please check & try again.
08-26 21:53:33.109  7188  7223 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 21:53:33.116  7024  7222 V FormManager: Network unavailable.
,08-26 21:53:33.120  7024  7222 V FormManager: Network unavailable.
,08-26 21:53:33.127  1034  1898 I ActivityManager: Killing 6783:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
08-26 21:53:33.173  1034  1975 W libprocessgroup: failed to open /acct/uid_10080/pid_6783/cgroup.procs: No such file or directory
,08-26 21:53:33.271  7224  7224 D LgDataFeature: LgDataFeature() Constructor: none
,08-26 21:53:33.272  7224  7224 D LgDataFeature: LgDataFeature() Constructor Done, null
08-26 21:53:33.276  7224  7224 D PhoneMonitor: Register our PhoneStateListener
08-26 21:53:33.302  7224  7224 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,08-26 21:53:33.304  7224  7224 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-26 21:53:33.328  7224  7224 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,08-26 21:53:33.331  7224  7224 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
08-26 21:53:33.332  7224  7224 D TelephonyAutoProfiling: [parse] Load xml
08-26 21:53:33.339  7224  7224 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
08-26 21:53:33.339  7224  7224 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
08-26 21:53:33.339  7224  7224 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-26 21:53:33.339  7224  7224 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
08-26 21:53:33.339  7224  7224 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
08-26 21:53:33.339  7224  7224 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
08-26 21:53:33.339  7224  7224 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-26 21:53:33.339  7224  7224 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-26 21:53:33.340  7224  7224 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-26 21:53:33.340  7224  7224 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-26 21:53:33.340  7224  7224 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-26 21:53:33.340  7224  7224 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-26 21:53:33.340  7224  7224 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-26 21:53:33.340  7224  7224 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-26 21:53:33.340  7224  7224 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-26 21:53:33.340  7224  7224 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-26 21:53:33.340  7224  7224 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
,08-26 21:53:33.354  7224  7224 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
08-26 21:53:33.357  1034  2030 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7246 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-26 21:53:33.358  1034  2030 I ActivityManager: Killing 6130:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,08-26 21:53:33.402  1034  2033 W libprocessgroup: failed to open /acct/uid_10097/pid_6130/cgroup.procs: No such file or directory
,08-26 21:53:33.549  7210  7210 E wpa_supplicant: USIM:  scard_init function
08-26 21:53:33.550  1034  2033 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7264 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
08-26 21:53:33.550  7210  7210 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-26 21:53:33.551  1034  2033 I ActivityManager: Killing 6802:com.lge.eula/1000 (adj 15): empty #17
08-26 21:53:33.552  1034  7217 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-26 21:53:33.552  1034  7217 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-26 21:53:33.552  1034  7217 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-26 21:53:33.552  1034  7217 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: WPS-AP-AVAILABLE 
08-26 21:53:33.552  1034  7217 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-26 21:53:33.553  1034  7217 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-26 21:53:33.553  1034  7217 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
,08-26 21:53:33.558  1034  1537 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
,08-26 21:53:33.559  1034  1537 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-26 21:53:33.562  1034  1537 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-26 21:53:33.562  1034  1537 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-26 21:53:33.562  1034  1537 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-26 21:53:33.613  1034  1537 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=126370  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-26 21:53:33.619  1034  1921 W libprocessgroup: failed to open /acct/uid_1000/pid_6802/cgroup.procs: No such file or directory
08-26 21:53:33.628  1034  1537 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=126385  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-26 21:53:33.630  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 21:53:33.630  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-26 21:53:33.632  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 21:53:33.632  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 21:53:33.632  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-26 21:53:33.636  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 21:53:33.638  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 21:53:33.638  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 21:53:33.639  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 21:53:33.639  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 21:53:33.639  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-26 21:53:33.640  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 21:53:33.640  1034  1034 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-26 21:53:33.640  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 21:53:33.669  7210  7210 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
08-26 21:53:33.669  1034  7217 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-26 21:53:33.669  1034  7217 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-26 21:53:33.669  1034  7217 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-26 21:53:33.669  1034  7217 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-26 21:53:33.669  1034  7217 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-26 21:53:33.669  1034  7217 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,08-26 21:53:33.670  1034  1537 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=126426  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-26 21:53:33.671  1034  1537 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=126427  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-26 21:53:33.671  1034  1537 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=126428
08-26 21:53:33.672  1034  1537 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=126428
08-26 21:53:33.672  1034  1537 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=126429
08-26 21:53:33.673  1034  1537 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=126429
08-26 21:53:33.673  1034  1537 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=126430
08-26 21:53:33.677  1034  1105 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-26 21:53:33.680  7210  7210 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-26 21:53:33.680  7210  7210 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-26 21:53:33.682  1034  7217 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-26 21:53:33.682  1034  7217 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-26 21:53:33.682  1034  7217 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-26 21:53:33.682  1034  7217 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-26 21:53:33.682  1034  7217 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-26 21:53:33.682  1034  7217 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-26 21:53:33.682  1034  7217 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-26 21:53:33.682  1034  7217 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-26 21:53:33.682  1034  7217 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-26 21:53:33.683  1034  7217 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-26 21:53:33.674  1034  1537 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=126430  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
,08-26 21:53:33.731  1034  1959 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7285 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-26 21:53:33.734  1034  1959 I ActivityManager: Killing 6819:com.lge.bnr/1000 (adj 15): empty #17
,08-26 21:53:33.840  1034  1537 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=126596  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-26 21:53:33.854  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 21:53:33.854  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-26 21:53:33.857  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 21:53:33.857  1034  1975 W libprocessgroup: failed to open /acct/uid_1000/pid_6819/cgroup.procs: No such file or directory
08-26 21:53:33.859  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 21:53:33.860  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-26 21:53:33.861  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 21:53:33.861  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 21:53:33.861  1034  1537 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
08-26 21:53:33.861  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-26 21:53:33.861  1034  1537 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-26 21:53:33.862  1034  1537 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-26 21:53:33.862  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 21:53:33.862  1034  1034 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-26 21:53:33.862  1034  1537 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-26 21:53:33.863  1034  1537 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-26 21:53:33.863  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 21:53:33.863  1034  1537 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=126620  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-26 21:53:33.864  1034  1537 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=126621  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-26 21:53:33.865  1034  1537 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=126621
08-26 21:53:33.865  1034  1537 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=126622
,08-26 21:53:33.866  1034  1537 D WifiNative-wlan0: doString: [STATUS]
,08-26 21:53:33.867  1034  1537 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-26 21:53:33.868  1034  7217 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-26 21:53:33.868  1034  7217 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-26 21:53:33.870  1034  1537 I WifiServiceExtension: setVHTCapabilityType  : false
08-26 21:53:33.872  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 21:53:33.872  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 21:53:33.874  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 21:53:33.875  1034  1537 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-26 21:53:33.875  1034  1537 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
08-26 21:53:33.879  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 21:53:33.879  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 21:53:33.879  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-26 21:53:33.883  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 21:53:33.883  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 21:53:33.883  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-26 21:53:33.886  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 21:53:33.886  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 21:53:33.888  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-26 21:53:33.890  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 21:53:33.890  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 21:53:33.892  1034  1537 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-26 21:53:33.892  1034  1537 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-26 21:53:33.892  1034  1537 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-26 21:53:33.892  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 21:53:33.892  1034  1543 D ConnectivityService: Got NetworkAgent Messenger
08-26 21:53:33.892  1034  1543 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-26 21:53:33.893  1034  1543 D ConnectivityService: NetworkAgent connected
08-26 21:53:33.893  1034  1537 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-26 21:53:33.893  1034  1537 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-26 21:53:33.896  7285  7285 I art     : Almond Protected OAT
08-26 21:53:33.898  1034  1537 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-26 21:53:33.899  1034  1537 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-26 21:53:33.899  1034  1537 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-26 21:53:33.899  1034  1537 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-26 21:53:33.899  1034  1537 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
,08-26 21:53:33.902  1034  1537 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-26 21:53:33.904   314   879 D CommandListener: Setting iface cfg
08-26 21:53:33.910  1034  1537 E WifiStateMachine: Start Dhcp Watchdog 2
08-26 21:53:33.910  1034  7305 D DhcpStateMachine: StoppedState
08-26 21:53:33.910  1034  7305 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-26 21:53:33.910  1034  7305 D DhcpStateMachine: WaitBeforeStartState
08-26 21:53:33.910  1034  1537 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=126667  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-26 21:53:33.911  1034  1537 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=126667  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
,08-26 21:53:33.912  1034  1537 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=126668  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-26 21:53:33.913  1034  1537 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=126669  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-26 21:53:33.914  1034  1537 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=126670  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-26 21:53:33.914  1034  1537 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=126670  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-26 21:53:33.915  1034  1537 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:79997] from screen [on:0 period:-932568613] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-26 21:53:33.916  1034  1537 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-932568612] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-26 21:53:33.916  1034  1537 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-26 21:53:33.922  1034  1543 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
08-26 21:53:33.923  1034  1537 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
,08-26 21:53:33.923  1034  1537 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 21:53:33.923  1034  1537 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 21:53:33.924  1034  1537 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 21:53:33.924  1034  1537 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 21:53:33.925  1034  1537 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 21:53:33.925  1034  1543 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-26 21:53:33.925  1034  1537 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=96,0,0
08-26 21:53:33.926  1034  1537 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=96,0,0
08-26 21:53:33.926  1034  1537 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-26 21:53:33.926  7210  7210 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-26 21:53:33.927  1034  1537 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-26 21:53:33.927  1034  1537 D WifiNative-wlan0: doBoolean: SET ps 0
08-26 21:53:33.927  1034  1537 D WifiNative-wlan0: SET ps 0: returned true
08-26 21:53:33.927  1034  1537 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-26 21:53:33.927  7210  7210 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-26 21:53:33.928  1034  1537 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-26 21:53:33.928  1034  1536 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@23f23974 target=com.android.internal.util.StateMachine$SmHandler }
08-26 21:53:33.928  1034  1536 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@23f23974 target=com.android.internal.util.StateMachine$SmHandler }
08-26 21:53:33.928  1034  7305 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-26 21:53:33.928  1034  7305 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-26 21:53:33.928  1034  1537 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-26 21:53:33.928  1034  1537 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-26 21:53:33.929  1034  1537 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-26 21:53:33.929   314   879 D CommandListener: Setting iface cfg
08-26 21:53:33.930   314   879 D CommandListener: Trying to bring up wlan0
,08-26 21:53:33.930  1034  1537 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
,08-26 21:53:33.931  1034  1537 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 21:53:33.932  1034  1537 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 21:53:33.932  1034  1537 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 21:53:33.933  1034  1537 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 21:53:33.933  1034  1537 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 21:53:33.934  1034  1537 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 21:53:33.934  1034  1543 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-26 21:53:33.935  1034  1537 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-26 21:53:33.935  1034  1537 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-26 21:53:33.935  1034  1536 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-26 21:53:33.935  1034  1536 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-26 21:53:33.936  1034  1537 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-26 21:53:33.936  7210  7210 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-26 21:53:33.936  1034  1537 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-26 21:53:33.936  1034  1537 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-26 21:53:33.936  7210  7210 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-26 21:53:33.937  1034  1537 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-26 21:53:33.937  1034  1537 D WifiNative-wlan0: doBoolean: SET ps 1
08-26 21:53:33.941  1034  1536 D LGWifiP2pService: InactiveState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-26 21:53:33.941  1034  1536 D LGWifiP2pService: P2pEnabledState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-26 21:53:33.941  1034  1536 D LGWifiP2pService: DefaultState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-26 21:53:33.951  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 21:53:33.951  1034  1034 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-26 21:53:33.952  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-26 21:53:33.952  1034  1537 D WifiNative-wlan0: SET ps 1: returned true
08-26 21:53:33.953  1034  1543 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-26 21:53:33.953  1034  1537 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-26 21:53:33.954  1034  1537 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-26 21:53:33.954  1034  1537 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-26 21:53:33.954  1034  1543 D ConnectivityService: ignoring duplicate network state non-change
08-26 21:53:33.955  1034  1543 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-26 21:53:33.956  1034  1543 D ConnectivityService: Adding iface wlan0 to network 101
08-26 21:53:33.958  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 21:53:33.958  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 21:53:33.959  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 21:53:33.960  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 21:53:33.960  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 21:53:33.960  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,08-26 21:53:33.968  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 21:53:33.968  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 21:53:33.968  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-26 21:53:33.969  1034  1034 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-26 21:53:33.970  1942  1942 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-26 21:53:33.973  7285  7285 D WeatherApplication: removeAccount
08-26 21:53:33.974  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 21:53:33.974  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 21:53:33.974  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-26 21:53:33.975  7285  7285 D WeatherApplication: Account.length = 0
08-26 21:53:33.975  7285  7285 E WeatherApplication: OPERATOR:OPEN
08-26 21:53:33.975  1034  1537 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-26 21:53:33.979  7285  7285 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 21:53:33
,08-26 21:53:33.980  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 21:53:33.980  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 21:53:33.981  1034  1034 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-26 21:53:33.984  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 21:53:33.984  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 21:53:33.984  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-26 21:53:33.984  1034  1543 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-26 21:53:33.984  1034  1543 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
08-26 21:53:33.985  7285  7285 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-26 21:53:33.985  7285  7285 D Weather.Utils: 2 : All the weather widget is gone.
08-26 21:53:33.985  1034  1543 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
08-26 21:53:33.986  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 21:53:33.986   314   879 E Netd    : netlink response contains error (File exists)
,08-26 21:53:33.986  1034  1543 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
08-26 21:53:33.987  7285  7285 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-26 21:53:33.987  1034  1543 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-26 21:53:33.987  1034  1543 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
08-26 21:53:33.987  1034  1543 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
08-26 21:53:33.987  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 21:53:33.987  1603  1603 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-26 21:53:33.988  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 21:53:33.988  1034  1543 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-26 21:53:33.988  1034  1543 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-26 21:53:33.988  1034  1543 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-26 21:53:33.988  1034  1543 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-26 21:53:33.988  1034  1543 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 21:53:33.989  1034  1543 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 21:53:33.989  1034  7304 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-26 21:53:33.989  1034  7304 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-26 21:53:33.989  1034  1543 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-26 21:53:33.989  1034  1543 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 21:53:33.989  1034  7304 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-26 21:53:33.989  1034  1543 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-26 21:53:33.989  1034  7304 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-26 21:53:33.989  1034  1543 D ConnectivityService: currentScore = 0, newScore = 20
08-26 21:53:33.989  1034  1543 D ConnectivityService:    accepting network in place of null
08-26 21:53:33.989  1034  1543 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 21:53:33.990  1034  1537 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 21:53:33.990  1034  1537 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 21:53:33.990  1853  1853 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 21:53:33.991  1853  1853 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specif,ier: <-1>]
08-26 21:53:33.991  1034  1543 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-26 21:53:33.992  1034  1543 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-26 21:53:33.992  1034  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-26 21:53:33.992   314  7309 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
,08-26 21:53:33.993  1034  1543 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-26 21:53:33.993  1034  1543 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-26 21:53:33.994  1034  1543 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-26 21:53:33.994  7285  7285 D WeatherAncestor: connectivity changed - connection : true
08-26 21:53:33.995  7285  7285 D WeatherService: 2 : isServiceAlived():false forecastCache:null
08-26 21:53:33.996  1034  1034 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-26 21:53:33.996  1034  1034 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-26 21:53:33.996  1034  1034 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-26 21:53:33.996  1034  1034 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-26 21:53:33.996  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 21:53:33.997  1603  1603 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-26 21:53:33.997  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 21:53:33.997  1034  1543 D ConnectivityService: validation of new default Network = false
08-26 21:53:33.997  1034  1543 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-26 21:53:33.997  1034  1543 D DSQN    : enableDataServiceNotify 
08-26 21:53:33.997  1034  1543 D DSQN    : start dsqn bin
08-26 21:53:34.003  1034  1535 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
08-26 21:53:34.006  1034  1543 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-26 21:53:34.006  1034  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 21:53:34.006  1034  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 21:53:34.006  1034  1543 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 21:53:34.006  1603  1827 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-26 21:53:33.999  7311  7311 W dsqn    : type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 21:53:34.012  7285  7285 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-26 21:53:34.012  7285  7285 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-26 21:53:34.012  7285  7285 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
08-26 21:53:33.999  7311  7311 W dsqn    : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 21:53:34.018  1817  7312 I CheckinService: active receiver: enabled
,08-26 21:53:34.023  7311  7311 E DSQN    : DSQN ssw
08-26 21:53:34.028  1817  7312 I CheckinService: Preparing to send checkin request
08-26 21:53:34.028  1817  7312 I EventLogService: Accumulating logs since 1472241129372
08-26 21:53:34.032  1603  1603 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,08-26 21:53:34.033  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 21:53:34.033  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 21:53:34.036  7285  7285 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-26 21:53:34.036  7285  7285 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 21:53:34
08-26 21:53:34.047   314  7309 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,08-26 21:53:34.069  1034  1049 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7317 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-26 21:53:34.071  1034  1049 I ActivityManager: Killing 2172:com.lge.music/u0a34 (adj 15): empty #17
08-26 21:53:34.074  1034  1537 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
,08-26 21:53:34.075  1034  1537 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-26 21:53:34.075  1034  1537 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
08-26 21:53:34.075  1034  1537 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-26 21:53:34.075  1034  1537 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-26 21:53:34.076  1034  1537 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
08-26 21:53:34.083   314  7309 D libc-netbsd: res_queryN name = clients3.google.com succeed
,08-26 21:53:34.089   319  1383 V AudioFlinger: 2172 died, releasing its sessions
08-26 21:53:34.089   319  1383 V AudioFlinger:  pid 1853 @ 0
08-26 21:53:34.089   319  1383 V AudioFlinger:  pid 3203 @ 1
08-26 21:53:34.089   319  1383 V AudioFlinger:  pid 3203 @ 2
08-26 21:53:34.113   314   878 D LGDataListener: argv[0]=dsqncommand
08-26 21:53:34.113   314   878 D LGDataListener: argv[1]=wlan0
08-26 21:53:34.113   314   878 D LGDataListener: argv[2]=1
08-26 21:53:34.113   314   878 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-26 21:53:34.114  1034  1103 D DSQN    : DSQM DsqnNotification wlan0  1
08-26 21:53:34.114  1034  1103 D DSQN    : start to monitor internet connection
,08-26 21:53:34.131  1034  7305 D DhcpStateMachine: DHCPV4 request on wlan0
,08-26 21:53:34.131  1034  7305 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-26 21:53:34.131  1034  7305 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
,08-26 21:53:34.129  7336  7336 W dhcpcd  : type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 21:53:34.135  1817  7312 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
08-26 21:53:34.135  1034  1940 W libprocessgroup: failed to open /acct/uid_10034/pid_2172/cgroup.procs: No such file or directory
08-26 21:53:34.129  7336  7336 W dhcpcd  : type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 21:53:34.139  7336  7336 I dhcpcd  : version 5.5.6 starting
08-26 21:53:34.140  7336  7336 E dhcpcd  : get_duid: m
08-26 21:53:34.140  7336  7336 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-26 21:53:34.140  7336  7336 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-26 21:53:34.141  1034  7304 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 26 Aug 2016 19:53:33 GMT], X-Android-Received-Millis=[1472241214141], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472241214113]}
08-26 21:53:34.141  1034  7304 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-26 21:53:34.141  1034  7304 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-26 21:53:34.142  1034  1543 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
08-26 21:53:34.142  1034  1543 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-26 21:53:34.142  1034  1543 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 21:53:34.142  1034  1543 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 21:53:34.142  1034  1543 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-26 21:53:34.142  1034  1543 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
08-26 21:53:34.142  1034  1543 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-26 21:53:34.142  1034  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 21:53:34.142  1034  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 21:53:34.142  1034  1543 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 21:53:34.143  1034  1543 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 21:53:34.143  1034  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-26 21:53:34.143  1034  1537 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 21:53:34.143  1034  1537 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 21:53:34.143  1853  1853 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 21:53:34.143  1603  1827 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-26 21:53:34.143  1853  1853 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT,_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
,08-26 21:53:34.168  1603  1603 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-26 21:53:34.169  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 21:53:34.170  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-26 21:53:34.192  7336  7336 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-26 21:53:34.192  7336  7336 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-26 21:53:34.192  7336  7336 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,08-26 21:53:34.192  7336  7336 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
08-26 21:53:34.192  7336  7336 D dhcpcd  : wlan0: sending REQUEST (xid 0x2dc0bd4a), next in 3.36 seconds
08-26 21:53:34.233  7336  7336 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
,08-26 21:53:34.253  1034  1995 I art     : Explicit concurrent mark sweep GC freed 104701(5MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 43MB/64MB, paused 1.571ms total 100.129ms
,08-26 21:53:34.272  7336  7336 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
08-26 21:53:34.272  7336  7336 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
08-26 21:53:34.272  7336  7336 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-26 21:53:34.272  7336  7336 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-26 21:53:34.272  7336  7336 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-26 21:53:34.273  7336  7336 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-26 21:53:34.273  7336  7336 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-26 21:53:34.273  7336  7336 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,08-26 21:53:34.322   277   364 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-26 21:53:34.322   277   364 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-26 21:53:34.322   277   364 W Vold    : Returning OperationFailed - no handler for errno 0
,08-26 21:53:34.324  7317  7349 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,08-26 21:53:34.328   277   364 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-26 21:53:34.328   277   364 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-26 21:53:34.328   277   364 W Vold    : Returning OperationFailed - no handler for errno 0
08-26 21:53:34.329  1034  1614 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7352 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
08-26 21:53:34.330  7317  7349 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-26 21:53:34.346   277   364 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-26 21:53:34.346   277   364 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-26 21:53:34.346   277   364 W Vold    : Returning OperationFailed - no handler for errno 0
,08-26 21:53:34.347  7317  7369 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-26 21:53:34.349   277   364 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-26 21:53:34.349   277   364 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-26 21:53:34.349   277   364 W Vold    : Returning OperationFailed - no handler for errno 0
08-26 21:53:34.349  7317  7369 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,08-26 21:53:34.379  7352  7352 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,08-26 21:53:34.379  7352  7352 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
08-26 21:53:34.403  7352  7352 I MultiDex: VM with version 2.1.0 has multidex support
,08-26 21:53:34.403  7352  7352 I MultiDex: install
08-26 21:53:34.403  7352  7352 I MultiDex: VM has multidex support, MultiDex support library is disabled.
08-26 21:53:34.412  7352  7352 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
08-26 21:53:34.499  7317  7317 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-26 21:53:34.506  7317  7317 I LibraryLoader: Loading: webviewchromium
08-26 21:53:34.508  7317  7317 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 7273-7276)
08-26 21:53:34.508  7317  7317 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-26 21:53:34.512  7317  7317 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2e971329}
,08-26 21:53:34.513  7317  7317 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-26 21:53:34.514  7317  7317 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-26 21:53:34.523  7317  7317 I BrowserStartupController: Initializing chromium process, renderers=0
,08-26 21:53:34.524  7317  7317 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-26 21:53:34.533  1034  7305 D DhcpStateMachine: DHCPV4 succeeded on wlan0
08-26 21:53:34.534  7317  7317 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,08-26 21:53:34.535  1034  7305 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-26 21:53:34.535  1034  7305 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-26 21:53:34.535  1034  7305 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
08-26 21:53:34.535  1034  7305 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-26 21:53:34.535  1034  7305 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-26 21:53:34.535  1034  7305 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-26 21:53:34.535  1034  7305 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-26 21:53:34.535  1034  7305 D DhcpStateMachine: RunningState
08-26 21:53:34.537  7317  7317 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
08-26 21:53:34.537  7317  7317 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
08-26 21:53:34.540   319   319 V AudioPolicyService: registerClient() client 0xb558a2c0, uid 10093
08-26 21:53:34.542  7317  7408 W AudioManagerAndroid: Requires BLUETOOTH permission
08-26 21:53:34.551  7317  7317 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-26 21:53:34.551  7317  7317 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-26 21:53:34.551  7317  7317 I Adreno-EGL: Build Date: 12/12/14 금
08-26 21:53:34.551  7317  7317 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-26 21:53:34.551  7317  7317 I Adreno-EGL: Remote Branch: 
08-26 21:53:34.551  7317  7317 I Adreno-EGL: Local Patches: 
08-26 21:53:34.551  7317  7317 I Adreno-EGL: Reconstruct Branch: 
,08-26 21:53:34.615  7317  7317 I NSApplication: Starting up...
,08-26 21:53:34.673  1034  1576 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7421 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,08-26 21:53:34.674  1034  1576 I ActivityManager: Killing 6957:com.lge.lifetracker/u0a37 (adj 15): empty #17
,08-26 21:53:34.694  7425  7425 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-26 21:53:34.744  1034  1995 W libprocessgroup: failed to open /acct/uid_10037/pid_6957/cgroup.procs: No such file or directory
,08-26 21:53:34.762  7425  7425 I dex2oat : dex2oat took 68.261ms (threads: 4)
,08-26 21:53:34.776  7352  7399 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-26 21:53:34.776  7352  7399 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-26 21:53:34.776  7352  7399 I Adreno-EGL: Build Date: 12/12/14 금
08-26 21:53:34.776  7352  7399 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-26 21:53:34.776  7352  7399 I Adreno-EGL: Remote Branch: 
08-26 21:53:34.776  7352  7399 I Adreno-EGL: Local Patches: 
08-26 21:53:34.776  7352  7399 I Adreno-EGL: Reconstruct Branch: 
,08-26 21:53:34.782  7421  7421 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-26 21:53:35.005  1034  2006 D WifiServiceImplEx: setWifiEnabled: false pid=6674, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,08-26 21:53:35.005  1034  2006 D WifiService: setWifiEnabled: false pid=6674, uid=10118
08-26 21:53:35.005  1034  2006 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-26 21:53:35.012  1034  1543 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
08-26 21:53:35.025  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-26 21:53:35.026  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-26 21:53:35.026  1034  1034 D Ulp_jni : JNI:system_update. Event-4
08-26 21:53:35.027  1034  1537 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-26 21:53:35.027  1034  1537 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-26 21:53:35.027  1034  1537 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-26 21:53:35.028  1034  1537 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-26 21:53:35.028  1034  1537 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-26 21:53:35.028  1034  1537 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-26 21:53:35.028  1034  1537 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-26 21:53:35.028  1034  1537 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-26 21:53:35.029  1034  1537 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-26 21:53:35.029  1034  1537 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
,08-26 21:53:35.045  1034  1537 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-26 21:53:35.046  1034  1537 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-26 21:53:35.046  7210  7210 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-26 21:53:35.046  1034  1536 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-26 21:53:35.046  1034  1536 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-26 21:53:35.047  1034  1537 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-26 21:53:35.047  1034  1537 D WifiNative-wlan0: doBoolean: SET ps 1
,08-26 21:53:35.047  1034  1537 D WifiNative-wlan0: SET ps 1: returned true
08-26 21:53:35.048   314   879 D CommandListener: Clearing all IP addresses on wlan0
08-26 21:53:35.052  1034  7305 D DhcpStateMachine: RunningState{ when=-4ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-26 21:53:35.094  1034  1537 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 21:53:35.094  1034  1537 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 21:53:35.095  1034  1537 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 21:53:35.095  1034  1537 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 21:53:35.096  1034  1537 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 21:53:35.096  1034  1537 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
,08-26 21:53:35.097  1034  1543 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-26 21:53:35.097  1034  1543 D ConnectivityService: ignoring duplicate network state non-change
08-26 21:53:35.097  1034  1543 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
08-26 21:53:35.100  1034  1536 D LGWifiP2pService: InactiveState{ when=-6ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-26 21:53:35.100  1034  1536 D LGWifiP2pService: P2pEnabledState{ when=-6ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-26 21:53:35.100  1034  1034 D WifiHS20: hidePasspointNotification off =false
08-26 21:53:35.101  1034  1536 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@abccd34
08-26 21:53:35.118  1034  1537 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-26 21:53:35.124  1942  1942 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-26 21:53:35.135  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 21:53:35.135  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-26 21:53:35.137  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 21:53:35.137  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 21:53:35.138  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-26 21:53:35.141  1034  1536 D LGWifiP2pService: P2pDisablingState
08-26 21:53:35.141  1034  1536 D LGWifiP2pService: P2pDisablingState{ when=-40ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-26 21:53:35.141  1034  1536 D LGWifiP2pService: p2p socket connection lost
08-26 21:53:35.141  1034  1536 D LGWifiP2pService: P2pDisabledState
08-26 21:53:35.142  1034  1537 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-26 21:53:35.143  1034  1537 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-26 21:53:35.143  1034  1034 D WifiHS20: hidePasspointNotification off =false
08-26 21:53:35.143  7210  7210 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-26 21:53:35.143  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 21:53:35.143  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 21:53:35.143  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-26 21:53:35.143  1034  1034 D WifiScanningService: SCAN_AVAILABLE : 1
08-26 21:53:35.143  1034  1034 D RttService: SCAN_AVAILABLE : 1
08-26 21:53:35.143  1034  1557 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-26 21:53:35.144  1034  1558 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-26 21:53:35.144  1034  1536 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-26 21:53:35.144  1034  1536 D LGWifiP2pService: DefaultState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-26 21:53:35.144  1034  1537 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-26 21:53:35.144  1034  1537 D WifiNative-wlan0: doBoolean: SET ps 1
08-26 21:53:35.145  1034  1537 D WifiNative-wlan0: SET ps 1: returned true
08-26 21:53:35.145  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 21:53:35.150  1942  1942 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-26 21:53:35.150  1942  1942 D WfdsService: WifiP2pState is changed : false
08-26 21:53:35.151  1942  2307 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-26 21:53:35.151  1942  2307 D WfdsService: Set the WFDS Monitor: false
08-26 21:53:35.152  1942  2307 D WfdsMonitor: WFDS Monitor is stopped
08-26 21:53:35.152  1942  2307 D WfdsService: STATE : WfdsDisabledState - enter
08-26 21:53:35.152  1942  7218 D CtrlSupplicant: Received on exit socket, terminate
08-26 21:53:35.152  1942  7218 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-26 21:53:35.152  1942  7218 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-26 21:53:35.152  1942  7218 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
,08-26 21:53:35.152  1942  2310 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-26 21:53:35.152  1942  2307 W WfdsService: DefaultState - msg [9445378] is not handled
08-26 21:53:35.153  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 21:53:35.153  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 21:53:35.156  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 21:53:35.171  1034  1378 V AlarmManager: ELAPSED_WAKEUP set : Alarm{3c8f81d4 type 2 when 127927 com.google.android.gms} when 127927
08-26 21:53:35.173   314   879 D CommandListener: Clearing all IP addresses on wlan0
08-26 21:53:35.173  1034  1543 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-26 21:53:35.173  1034  1543 D DSQN    : disableDataServiceNotify
08-26 21:53:35.173  1034  1543 D DSQN    : stop dsqn bin
08-26 21:53:35.174  1034  1537 D WifiNative-p2p0: doBoolean: TERMINATE
08-26 21:53:35.175  1034  1034 D WifiHS20: hidePasspointNotification off =false
08-26 21:53:35.175  1034  1537 D WifiNative-p2p0: TERMINATE: returned true
08-26 21:53:35.175  1034  1537 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-26 21:53:35.175  1034  1537 E WifiStateMachine: useWiFiOffloading() : false
08-26 21:53:35.175  1034  1537 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-26 21:53:35.177  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-26 21:53:35.177  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-26 21:53:35.178  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 21:53:35.178  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 21:53:35.178  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-26 21:53:35.179  1942  1942 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-26 21:53:35.180  6674  6674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 21:53:35.180  6674  6674 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 21:53:35.180  6674  6674 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 21:53:35.180  6674  6674 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 21:53:35.180  6674  6674 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 21:53:35.180  6674  6674 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 21:53:35.180  6674  6674 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 21:53:35.180  6674  6674 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 21:53:35.180  6674  6674 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 21:53:35.180  6674  6674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 21:53:35.180  6674  6674 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 21:53:35.180  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 21:53:35.181  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-26 21:53:35.181  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 21:53:35.181  1034  1034 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-26 21:53:35.182  6674  6674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 21:53:35.182  6674  6674 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 21:53:35.182  6674  6674 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 21:53:35.182  6674  6674 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 21:53:35.182  6674  6674 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 21:53:35.182  6674  6674 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 21:53:35.182  6674  6674 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 21:53:35.182  6674  6674 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 21:53:35.182  6674  6674 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 21:53:35.182  6674  6674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 21:53:35.182  6674  6674 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 21:53:35.183  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connec,ted!! Set no data type icon / Roaming
08-26 21:53:35.188  1034  1543 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
08-26 21:53:35.188  1034  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 21:53:35.188  1034  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 21:53:35.189  1034  1543 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 21:53:35.189  1034  1543 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-26 21:53:35.189  1034  7304 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-26 21:53:35.189  1034  7304 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-26 21:53:35.189  1034  7304 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-26 21:53:35.189  1034  1543 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-26 21:53:35.189  1034  1543 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-26 21:53:35.189  1034  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-26 21:53:35.190  1603  1827 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-26 21:53:35.190  1034  1543 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-26 21:53:35.190  1034  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-26 21:53:35.190  1034  1535 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-26 21:53:35.192  1034  1034 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-26 21:53:35.192  1034  1543 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-26 21:53:35.192  1034  1543 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 21:53:35.192  1034  1543 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 21:53:35.193  1034  1034 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-26 21:53:35.193  1034  1034 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-26 21:53:35.193  1034  1034 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
,08-26 21:53:35.193  1034  1535 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-26 21:53:35.195  1034  1543 D NetworkManagementService: Removing idletimer
08-26 21:53:35.195  1034  1543 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 21:53:35.195  1034  1537 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 21:53:35.195  1034  1537 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 21:53:35.196  1853  1853 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 21:53:35.196  1034  1034 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-26 21:53:35.196  1853  1853 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-26 21:53:35.196  1034  1034 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-26 21:53:35.196  1034  1034 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-26 21:53:35.196  1034  1034 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-26 21:53:35.200  6448  6448 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-26 21:53:35.201  6448  6478 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-26 21:53:35.218  2205  2205 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-26 21:53:35.228  7154  7154 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-26 21:53:35.228  7154  7154 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-26 21:53:35.228  7154  7154 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-26 21:53:35.228  7154  7154 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-26 21:53:35.230  7154  7154 I AppUp4:CustModeStarterReceiver: onReceive
,08-26 21:53:35.234  7154  7154 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@b1b8426
08-26 21:53:35.234  7154  7154 D AppUp4:CustFacade: isCustomizationCompleted : false
08-26 21:53:35.234  7154  7154 D AppUp4:CustFacade: isPhone : true
08-26 21:53:35.234  7154  7154 D AppUp4:CustModeStarterReceiver: begin check event
08-26 21:53:35.234  7154  7154 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-26 21:53:35.238  4754  4754 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-26 21:53:35.238  4754  4754 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-26 21:53:35.239  4754  4754 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 21:53:35.242  4754  4754 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-26 21:53:35.247  4754  7475 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-26 21:53:35.248  1603  1603 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-26 21:53:35.249  7188  7188 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-26 21:53:35.249  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 21:53:35.250  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-26 21:53:35.255  4754  7476 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-26 21:53:35.255  4754  7476 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-26 21:53:35.261  1034  7305 D DhcpStateMachine: StoppedState
08-26 21:53:35.261  1034  7305 D DhcpStateMachine: StoppedState{ when=-116ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-26 21:53:35.262  1034  1537 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-26 21:53:35.262  1034  1537 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-26 21:53:35.264  7210  7210 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-26 21:53:35.264  7210  7210 I wpa_supplicant: monitor socket send errors count : 1
08-26 21:53:35.264  7210  7210 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1942-4\x00 that cannot receive messages
08-26 21:53:35.265  1034  7217 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-26 21:53:35.265  1034  7217 D WifiMonitor: Dropping event because (p2p0) is stopped
08-26 21:53:35.268  7188  7480 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 21:53:35.270  3203  3203 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,08-26 21:53:35.270  3203  3203 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-26 21:53:35.270  3203  3203 I LgeMiscReceiver: networkInfo.isConnected() = false
08-26 21:53:35.275  7224  7224 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-26 21:53:35.275  7224  7224 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-26 21:53:35.280  7024  7478 W FormManager: Network not available. Please check & try again.
,08-26 21:53:35.282  1603  1603 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-26 21:53:35.283  7024  7479 V FormManager: Network unavailable.
08-26 21:53:35.283  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 21:53:35.283  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 21:53:35.285  7285  7285 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 21:53:35
08-26 21:53:35.287  7024  7479 V FormManager: Network unavailable.
08-26 21:53:35.287  7285  7285 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-26 21:53:35.287  7285  7285 D Weather.Utils: 2 : All the weather widget is gone.
08-26 21:53:35.288  7285  7285 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-26 21:53:35.288  7285  7285 D WeatherAncestor: connectivity changed - connection : true
08-26 21:53:35.288  7285  7285 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@1bb02614
08-26 21:53:35.288  7285  7285 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-26 21:53:35.288  7285  7285 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-26 21:53:35.289  7285  7285 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-26 21:53:35.289  7285  7285 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-26 21:53:35.289  7285  7285 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 21:53:35
08-26 21:53:35.306  6917  6917 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-26 21:53:35.306  6917  6917 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-26 21:53:35.306  6917  6917 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-26 21:53:35.306  6917  6917 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
,08-26 21:53:35.307  6917  6917 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-26 21:53:35.309  6917  6917 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-26 21:53:35.309  6917  6917 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-26 21:53:35.309  6917  6917 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-26 21:53:35.309  6917  6917 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-26 21:53:35.309  6917  6917 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-26 21:53:35.309  6917  6917 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-26 21:53:35.309  6917  6917 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-26 21:53:35.310  7210  7210 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-26 21:53:35.310  1034  7217 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-26 21:53:35.310  1034  7217 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-26 21:53:35.310  1034  7217 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-26 21:53:35.311  1034  7217 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-26 21:53:35.311  7210  7210 W wpa_supplicant: USIM:  scard_deinit function
08-26 21:53:35.311  1034  1537 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=128067
08-26 21:53:35.311  1034  7217 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-26 21:53:35.311  1034  1537 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=128068
08-26 21:53:35.311  1034  7217 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-26 21:53:35.312  1034  1537 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=128068  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-26 21:53:35.312  1034  1537 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=128069  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-26 21:53:35.313  1034  1105 D Tethering: InitialState.processMessage what=4
08-26 21:53:35.314  1034  1105 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-26 21:53:35.315  1034  1537 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-26 21:53:35.315  1034  1537 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-26 21:53:35.316  6934  6934 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-26 21:53:35.318  6917  6917 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-26 21:53:35.324  6917  6917 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 21:53:35.334  7024  7488 W FormManager: Network not available. Please check & try again.
,08-26 21:53:35.336  6934  6934 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-26 21:53:35.339  6917  6917 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-26 21:53:35.340  7024  7489 V FormManager: Network unavailable.
08-26 21:53:35.341  7024  7489 V FormManager: Network unavailable.
,08-26 21:53:35.347  6917  6917 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 21:53:35.351  7024  7490 W FormManager: Network not available. Please check & try again.
08-26 21:53:35.353  7024  7491 V FormManager: Network unavailable.
08-26 21:53:35.355  7024  7491 V FormManager: Network unavailable.
08-26 21:53:35.356  4754  4754 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-26 21:53:35.356  4754  4754 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-26 21:53:35.357  4754  4754 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-26 21:53:35.361  4754  4754 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 21:53:35.363  7352  7399 D LgDataFeature: LgDataFeature() Constructor: none
08-26 21:53:35.363  7352  7399 D LgDataFeature: LgDataFeature() Constructor Done, null
08-26 21:53:35.364  4754  7492 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-26 21:53:35.365  4754  7493 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-26 21:53:35.366  4754  7493 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-26 21:53:35.371  7352  7399 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-26 21:53:35.371  7352  7399 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-26 21:53:35.371  7352  7399 I Adreno-EGL: Build Date: 12/12/14 금
08-26 21:53:35.371  7352  7399 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-26 21:53:35.371  7352  7399 I Adreno-EGL: Remote Branch: 
08-26 21:53:35.371  7352  7399 I Adreno-EGL: Local Patches: 
08-26 21:53:35.371  7352  7399 I Adreno-EGL: Reconstruct Branch: 
,08-26 21:53:35.388  1034  1050 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7494 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
08-26 21:53:35.411  1603  1603 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
,08-26 21:53:35.411  1603  1603 I [SystemUI]LGPowerUI: On Skip Timer : true
08-26 21:53:35.413  7352  7399 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-26 21:53:35.413  7352  7399 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-26 21:53:35.413  7352  7399 I Adreno-EGL: Build Date: 12/12/14 금
08-26 21:53:35.413  7352  7399 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-26 21:53:35.413  7352  7399 I Adreno-EGL: Remote Branch: 
08-26 21:53:35.413  7352  7399 I Adreno-EGL: Local Patches: 
08-26 21:53:35.413  7352  7399 I Adreno-EGL: Reconstruct Branch: 
08-26 21:53:35.419  1603  1603 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 308
08-26 21:53:35.419  1603  1603 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-26 21:53:35.420  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 21:53:35.420  1034  1542 D WifiController: battery changed pluggedType: 2
08-26 21:53:35.420  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 21:53:35.420  1942  2086 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-26 21:53:35.420  1942  2086 D LEDHandler: Battery Level Remaining: 100%
08-26 21:53:35.420  1942  2086 D LEDHandler: Battery Temp: 308, mChargingStatus=5, mChargingStop=false
08-26 21:53:35.421  1603  1603 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-26 21:53:35.442  7210  7210 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,08-26 21:53:35.444  1034  7217 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-26 21:53:35.444  1034  7217 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-TERMINATING 
08-26 21:53:35.444  1034  7217 D WifiMonitor: Disconnecting from the supplicant, no more events
08-26 21:53:35.444  1034  1537 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 44 0
08-26 21:53:35.454  7494  7494 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-26 21:53:35.454  7494  7494 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-26 21:53:35.458  7494  7494 V [BNRBootReceiver]: Boot Receiver Return
08-26 21:53:35.460  6448  6448 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 21:53:35.460  7494  7494 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-26 21:53:35.464  6917  6917 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 21:53:35.467  6917  6917 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 21:53:35.474  6981  6981 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 21:53:35.475  6981  6981 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-26 21:53:35.476  6981  6981 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-26 21:53:35.479  6917  6917 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
08-26 21:53:35.480  6917  6917 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-26 21:53:35.482  6448  6448 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 21:53:35.488  6917  6917 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 21:53:35.489   314  7513 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-26 21:53:35.489  1034  1103 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-26 21:53:35.489  1817  7312 E CheckinTask: Checkin failed: https://android.clients.google.com/checkin (request #0): java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
08-26 21:53:35.492  6917  6917 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 21:53:35.501  6981  6981 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 21:53:35.502  6981  6981 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-26 21:53:35.503  6981  6981 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-26 21:53:35.505  6448  6448 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 21:53:35.505  1817  7312 I CheckinService: active receiver: disabled
,08-26 21:53:35.520  6917  6917 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 21:53:35.525  6917  6917 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 21:53:35.530  6981  6981 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 21:53:35.530  6981  6981 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 21:53:35.530  6981  6981 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-26 21:53:35.534  6448  6448 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 21:53:35.539  6917  6917 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-26 21:53:35.543  6917  6917 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-26 21:53:35.545  1034  1537 D WifiOffDelayIfNotUsed: stopMonitoring
08-26 21:53:35.545  1034  1537 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-26 21:53:35.545  1034  1537 E WifiStateMachine: useWiFiOffloading() : false
08-26 21:53:35.545  1034  1537 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-26 21:53:35.546  1942  1942 D WfdsService: Supplicant Connection state is changed : false
08-26 21:53:35.546  1942  2307 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-26 21:53:35.546  1942  2307 D WfdsService: Set the WFDS Monitor: false
08-26 21:53:35.546  1942  2307 D WfdsMonitor: WFDS Monitor is stopped
08-26 21:53:35.547  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 21:53:35.548  1942  1942 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-26 21:53:35.549  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-26 21:53:35.549  1034  1541 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-26 21:53:35.549  1034  1541 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-26 21:53:35.550  6674  6674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 21:53:35.550  6674  6674 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 21:53:35.550  6674  6674 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 21:53:35.550  6674  6674 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 21:53:35.550  6674  6674 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 21:53:35.550  6674  6674 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 21:53:35.550  6674  6674 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 21:53:35.550  6674  6674 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 21:53:35.550  6674  6674 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 21:53:35.550  2481  2481 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 21:53:35.551  6981  6981 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 21:53:35.551  6674  6674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 21:53:35.551  6981  6981 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 21:53:35.551  6674  6674 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 21:53:35.551  6674  6674 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 21:53:35.551  6674  6674 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 21:53:35.551  6674  6674 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 21:53:35.551  6674  6674 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 21:53:35.551  6674  6674 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 21:53:35.551  6674  6674 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 21:53:35.551  6674  6674 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 21:53:35.551  6981  6981 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-26 21:53:35.556  6448  6448 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is proc,essing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-26 21:53:35.562  6917  6917 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 21:53:35.572  6917  6917 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-26 21:53:35.579  6981  6981 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 21:53:35.579  6981  6981 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 21:53:35.579  6981  6981 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-26 21:53:35.582  6448  6448 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-26 21:53:35.589  6917  6917 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 21:53:35.595  6917  6917 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 21:53:35.601  6981  6981 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 21:53:35.602  6981  6981 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 21:53:35.602  6981  6981 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-26 21:53:35.606  6448  6448 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-26 21:53:35.616  6917  6917 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 21:53:35.624  6917  6917 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 21:53:35.633  6981  6981 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 21:53:35.634  6981  6981 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 21:53:35.635  6981  6981 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-26 21:53:35.646  6448  6448 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-26 21:53:35.672  6917  6917 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 21:53:35.686  6917  6917 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-26 21:53:35.697  6981  6981 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 21:53:35.698  6981  6981 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-26 21:53:35.706  6981  6981 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-26 21:53:35.713  6448  6448 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 21:53:35.724  6917  6917 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 21:53:35.735  6917  6917 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 21:53:35.745  6981  6981 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 21:53:35.746  6981  6981 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-26 21:53:35.748  6981  6981 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-26 21:53:35.753  6448  6448 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 21:53:35.761  6934  6934 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,08-26 21:53:35.777  1034  1542 D WifiService: New client listening to asynchronous messages
08-26 21:53:35.778  6934  6934 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-26 21:53:35.787  6917  6917 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 21:53:35.796  6917  6917 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 21:53:35.806  6981  6981 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-26 21:53:35.807  6981  6981 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 21:53:35.809  6981  6981 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-26 21:53:35.812  6981  6981 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-26 21:53:35.813  6981  6981 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-26 21:53:35.821  6448  6448 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-26 21:53:35.827  6934  6934 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-26 21:53:35.829  6934  6934 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-26 21:53:35.834  6917  6917 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 21:53:35.844  6917  6917 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 21:53:35.858  6981  6981 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-26 21:53:35.858  6981  6981 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 21:53:35.860  6981  6981 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-26 21:53:35.861  6981  6981 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-26 21:53:35.861  6981  6981 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-26 21:53:35.867  1034  1975 I ActivityManager: Killing 7003:com.lge.settings.easy/1000 (adj 15): empty #17
08-26 21:53:35.924  1034  1732 W libprocessgroup: failed to open /acct/uid_1000/pid_7003/cgroup.procs: No such file or directory
,08-26 21:53:35.929  2205  2205 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
08-26 21:53:35.943  2205  2205 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,08-26 21:53:35.944  2205  2205 D c       : Getting all permits...
08-26 21:53:35.944  2205  2205 D a       : Opening database...
08-26 21:53:35.950  2205  2205 D a       : Opening database auth.proximity.permit_store...
08-26 21:53:35.951  2205  2205 D a       : Closing database...
08-26 21:53:35.965  6448  6448 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-26 21:53:35.976  6934  6934 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-26 21:53:35.976  6934  6934 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-26 21:53:35.976  6934  6934 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-26 21:53:35.981  6917  6917 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 21:53:35.991  6917  6917 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 21:53:36.007  6981  6981 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 21:53:36.007  6981  6981 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-26 21:53:36.010  6981  6981 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-26 21:53:36.018  6448  6448 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 21:53:36.025  6850  7116 D UEI.SmartControl: Internal timer expired: 2
08-26 21:53:36.025  6850  7116 D UEI.SmartControl: unbind internal service
08-26 21:53:36.025  6934  6934 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-26 21:53:36.025  6934  6934 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-26 21:53:36.025  6934  6934 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-26 21:53:36.033  6917  6917 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 21:53:36.046  6917  6917 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 21:53:36.057  6981  6981 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 21:53:36.057  6981  6981 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 21:53:36.060  6981  6981 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-26 21:53:36.070   314  7522 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-26 21:53:36.070  1034  1103 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-26 21:53:36.072  6448  6448 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-26 21:53:36.080  6934  6934 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,08-26 21:53:36.080  6934  6934 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-26 21:53:36.080  6934  6934 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-26 21:53:36.086  6917  6917 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 21:53:36.094  6917  6917 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 21:53:36.101  6981  6981 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 21:53:36.102  6981  6981 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-26 21:53:36.105  6981  6981 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-26 21:53:36.113  6934  6934 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-26 21:53:36.118  6917  6917 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-26 21:53:36.126  7024  7524 W FormManager: Network not available. Please check & try again.
08-26 21:53:36.128  6917  6917 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 21:53:36.134  6850  7110 D serial_port: close(fd = 24)
,08-26 21:53:36.138  6850  7110 I UEI.SmartControl: Serial port is closed.
08-26 21:53:36.138  7024  7525 V FormManager: Network unavailable.
08-26 21:53:36.145  7024  7525 V FormManager: Network unavailable.
,08-26 21:53:36.151  6917  6917 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
,08-26 21:53:36.151  6917  6917 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-26 21:53:36.151  6917  6917 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-26 21:53:36.151  6917  6917 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-26 21:53:36.154  6917  6917 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-26 21:53:36.158  6917  6917 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
,08-26 21:53:36.158  6917  6917 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-26 21:53:36.158  6917  6917 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-26 21:53:36.158  6917  6917 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-26 21:53:36.158  6917  6917 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-26 21:53:36.158  6917  6917 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-26 21:53:36.166  2205  2205 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
08-26 21:53:36.183  4754  4754 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-26 21:53:36.183  4754  4754 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-26 21:53:36.185  4754  4754 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 21:53:36.188  4754  4754 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 21:53:36.194  4754  7526 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-26 21:53:36.199  6934  6934 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-26 21:53:36.199  6934  6934 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-26 21:53:36.199  6934  6934 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-26 21:53:36.202  4754  7527 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-26 21:53:36.202  4754  7527 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-26 21:53:36.205  6917  6917 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-26 21:53:36.213  7024  7529 W FormManager: Network not available. Please check & try again.
08-26 21:53:36.218  6917  6917 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 21:53:36.224  7024  7530 V FormManager: Network unavailable.
,08-26 21:53:36.230  7024  7530 V FormManager: Network unavailable.
,08-26 21:53:36.924  1034  1537 E WifiStateMachine:  InitialState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-932565604] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-26 21:53:36.926  1034  1537 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-932565602] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-26 21:53:36.995  1034  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-26 21:53:37.008  1034  1105 D Tethering: MasterInitialState.processMessage what=3
08-26 21:53:37.019  6674  6674 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 21:53:37.023  6674  6674 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 21:53:37.027  1034  1090 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-26 21:53:37.029  6448  6448 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-26 21:53:37.031  6448  6478 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-26 21:53:37.041  5837  5837 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-26 21:53:37.061  2205  2205 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-26 21:53:37.079  7154  7154 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-26 21:53:37.079  7154  7154 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-26 21:53:37.079  7154  7154 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
,08-26 21:53:37.079  7154  7154 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-26 21:53:37.087  7154  7154 I AppUp4:CustModeStarterReceiver: onReceive
08-26 21:53:37.091  7154  7154 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@b1b8426
08-26 21:53:37.091  7154  7154 D AppUp4:CustFacade: isCustomizationCompleted : false
08-26 21:53:37.091  7154  7154 D AppUp4:CustFacade: isPhone : true
08-26 21:53:37.092  7154  7154 D AppUp4:CustModeStarterReceiver: begin check event
08-26 21:53:37.092  7154  7154 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
,08-26 21:53:37.099  4754  4754 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-26 21:53:37.099  4754  4754 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-26 21:53:37.100  4754  4754 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 21:53:37.105  4754  4754 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-26 21:53:37.114  7188  7188 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-26 21:53:37.141  7188  7539 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-26 21:53:37.143  4754  7538 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-26 21:53:37.148  4754  7542 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-26 21:53:37.148  4754  7542 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-26 21:53:37.164  7024  7540 W FormManager: Network not available. Please check & try again.
,08-26 21:53:37.172  1034  1090 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 21:53:37.181  7024  7541 V FormManager: Network unavailable.
08-26 21:53:37.179  3203  3203 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-26 21:53:37.181  3203  3203 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
,08-26 21:53:37.181  3203  3203 I LgeMiscReceiver: networkInfo.isConnected() = true
08-26 21:53:37.181  3203  3203 D PhoneState: setPdpRejectCasuse : false
08-26 21:53:37.189  7224  7224 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-26 21:53:37.190  7024  7541 V FormManager: Network unavailable.
08-26 21:53:37.190  7224  7224 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-26 21:53:37.203  7285  7285 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 21:53:37
08-26 21:53:37.207  7285  7285 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
,08-26 21:53:37.207  7285  7285 D Weather.Utils: 2 : All the weather widget is gone.
,08-26 21:53:37.207  7285  7285 D UpdateThreadPoolManager: 2 : This is isUpdating : false
,08-26 21:53:37.208  7285  7285 D WeatherAncestor: connectivity changed - connection : true
,08-26 21:53:37.208  7285  7285 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@1bb02614
,08-26 21:53:37.209  7285  7285 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-26 21:53:37.209  7285  7285 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-26 21:53:37.209  7285  7285 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
,08-26 21:53:37.209  7285  7285 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-26 21:53:37.209  7285  7285 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 21:53:37
08-26 21:53:38.028  1034  1049 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-26 21:53:38.029  1034  1049 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-26 21:53:38.070  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-26 21:53:38.070  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-26 21:53:38.070  1034  1034 D Ulp_jni : JNI:system_update. Event-4
08-26 21:53:38.071  1034  1105 D BluetoothManagerService: Message: 1
08-26 21:53:38.071  1034  1105 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-26 21:53:38.101  1034  1105 D BluetoothManagerService: Message: 20
08-26 21:53:38.101  1034  1105 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a7d05a0:true
,08-26 21:53:38.106  7054  7054 D BluetoothAdapterState: make
08-26 21:53:38.111  7054  7054 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-26 21:53:38.111  7054  7054 I bluedroid-qcom: init
08-26 21:53:38.112  7054  7570 I BluetoothAdapterState: Entering OffState
08-26 21:53:38.113  7054  7054 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-26 21:53:38.113  7054  7054 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-26 21:53:38.113  7054  7054 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-26 21:53:38.113  7054  7054 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-26 21:53:38.113  7054  7054 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-26 21:53:38.115  7054  7054 I bluedroid-qcom: get_profile_interface socket
08-26 21:53:38.115  7054  7054 I bluedroid-qcom: get_profile_interface map_client
,08-26 21:53:38.120  7054  7574 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-26 21:53:38.119  7573  7573 W bdaddr_loader: type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 21:53:38.119  7573  7573 W bdaddr_loader: type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 21:53:38.131  7573  7573 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-26 21:53:38.131  7573  7573 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-26 21:53:38.131  7573  7573 I LGFTMITEM: [GET_FTM][id=8], offset=16384
,08-26 21:53:38.137  1034  1034 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-26 21:53:38.137  1034  1105 D BluetoothManagerService: Message: 40
08-26 21:53:38.137  1034  1105 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-26 21:53:38.138  7054  7074 I bluedroid-qcom: config_hci_snoop_log
08-26 21:53:38.139  1034  1105 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-26 21:53:38.139  1034  1105 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-26 21:53:38.145  7573  7573 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
,08-26 21:53:38.149  7054  7570 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-26 21:53:38.149  7054  7570 D BluetoothAdapterProperties: Setting state to 11
08-26 21:53:38.150  7054  7570 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-26 21:53:38.153  1034  1105 D BluetoothManagerService: Message: 60
08-26 21:53:38.153  1034  1105 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-26 21:53:38.153  1034  1105 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-26 21:53:38.154  7573  7573 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-26 21:53:38.154  7573  7573 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-26 21:53:38.159  1942  1942 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-26 21:53:38.163  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-26 21:53:38.165  6674  6674 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 21:53:38.167  6917  6917 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-26 21:53:38.168  6674  6674 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 21:53:38.175  7054  7570 I LGBluetoothServiceJni: classInitNative: succeeds
,08-26 21:53:38.152  7054  7574 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-26 21:53:38.183  7054  7054 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-26 21:53:38.192  1034  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-26 21:53:38.196  1034  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-26 21:53:38.199  7054  7054 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 21:53:38.200  7054  7054 V BluetoothPbapReceiver: ***********state = 11
08-26 21:53:38.202  7054  7570 D BluetoothBondStateMachine: make
08-26 21:53:38.203  1034  1105 D Tethering: MasterInitialState.processMessage what=3
08-26 21:53:38.208  7054  7570 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1bb02614
08-26 21:53:38.208  7054  7570 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-26 21:53:38.209  7054  7570 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1bb02614
,08-26 21:53:38.209  7054  7570 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-26 21:53:38.209  6674  6674 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 21:53:38.210  7054  7570 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-26 21:53:38.212  1034  1105 D Tethering: MasterInitialState.processMessage what=3
08-26 21:53:38.213  6674  6674 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 21:53:38.215  7054  7588 I BluetoothBondStateMachine: StableState(): Entering Off State
08-26 21:53:38.216  7054  7570 E BluetoothAdapterService: File transfer profiles supported!!
08-26 21:53:38.220  6674  6674 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 21:53:38.222  6674  6674 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 21:53:38.224  6448  6448 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-26 21:53:38.224  7054  7574 D BluetoothAdapterProperties: Name is: G3
08-26 21:53:38.224  1034  1034 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-26 21:53:38.225  1034  1034 D BluetoothManagerService: Stored Bluetooth name: G3
08-26 21:53:38.225  6448  6478 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-26 21:53:38.226  2205  2205 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-26 21:53:38.230  5837  5837 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-26 21:53:38.236  7054  7570 E BluetoothAdapterService: File transfer profiles supported!!
08-26 21:53:38.236  7054  7054 D HeadsetService: Received start request. Starting profile...
08-26 21:53:38.237  7054  7054 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-26 21:53:38.237  7054  7054 D LGBluetoothHfpAdapter: Version 1.6
08-26 21:53:38.240  7054  7054 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,08-26 21:53:38.241  7054  7054 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-26 21:53:38.242  7054  7054 D HeadsetStateMachine: make
08-26 21:53:38.273  1034  1049 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7594 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-26 21:53:38.274  1034  1090 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-26 21:53:38.276  7054  7054 D LgDataFeature: LgDataFeature() Constructor: none
08-26 21:53:38.276  7054  7054 D LgDataFeature: LgDataFeature() Constructor Done, null
08-26 21:53:38.277  5837  5837 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-26 21:53:38.277  7054  7570 E BluetoothAdapterService: File transfer profiles supported!!
08-26 21:53:38.280  1034  1090 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-26 21:53:38.281  7054  7054 D HeadsetStateMachine: max_hf_connections = 1
08-26 21:53:38.281  7054  7054 I bluedroid-qcom: get_profile_interface handsfree
08-26 21:53:38.281  1034  1090 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 21:53:38.281  1034  1090 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 21:53:38.283  7054  7054 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-26 21:53:38.283  7054  7570 E BluetoothAdapterService: File transfer profiles supported!!
08-26 21:53:38.283   319  2203 V AudioPolicyService: registerClient() client 0xb57c0d40, uid 1002
08-26 21:53:38.283   319  1383 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-26 21:53:38.284   319  1383 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-26 21:53:38.284   319  1383 V AudioPolicyManagerEx: getOutput() returns output 2
08-26 21:53:38.284  7054  7054 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-26 21:53:38.284   319   319 V AudioFlinger: registerClient() client 0xb5581cb8, pid 7054
08-26 21:53:38.285   319  1377 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
,08-26 21:53:38.285   319  1377 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-26 21:53:38.285  7054  7054 V ToneGenerator: Create Track: 0xb4928a80
08-26 21:53:38.285  7054  7054 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-26 21:53:38.285  7054  7054 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-26 21:53:38.285   319  1384 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-26 21:53:38.285   319  1384 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-26 21:53:38.285   319  1384 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-26 21:53:38.285  1603  1622 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-26 21:53:38.285   319  1384 V AudioPolicyManagerEx: getOutput() returns output 2
08-26 21:53:38.285  1603  1622 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-26 21:53:38.285  7054  7054 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-26 21:53:38.285  7054  7073 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-26 21:53:38.285  7054  7073 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-26 21:53:38.286   319  1379 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-26 21:53:38.286   319  1379 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-26 21:53:38.286  7054  7073 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-26 21:53:38.286  7054  7073 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-26 21:53:38.286  1603  1622 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-26 21:53:38.286  1603  1622 V AudioSystem: ioConfigChanged() opening already existing output! 4
,08-26 21:53:38.286  1034  1049 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
,08-26 21:53:38.287  1034  1049 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-26 21:53:38.287  1034  1049 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-26 21:53:38.287  1034  1049 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-26 21:53:38.287  1853  2419 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-26 21:53:38.287  1853  2419 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-26 21:53:38.287  1853  2419 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-26 21:53:38.287  1853  2419 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-26 21:53:38.288  3203  3218 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-26 21:53:38.288  3203  3218 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-26 21:53:38.288  3203  3218 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-26 21:53:38.288  3203  3218 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-26 21:53:38.288   319  1384 I AudioFlinger: isAudioPlaybackHookOn() false
08-26 21:53:38.288   319  2204 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-26 21:53:38.288   319  2204 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-26 21:53:38.288   319  2204 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-26 21:53:38.288   319  2204 V AudioPolicyManagerEx: getOutput() returns output 2
08-26 21:53:38.288  7054  7054 V AudioSystem: getLatency() output 2, latency 50
08-26 21:53:38.288  7054  7054 V AudioSystem: getFrameCount() output 2, frameCount 960
08-26 21:53:38.288  7054  7054 V AudioTrack: createTrack_l() output 2 afLatency 50
08-26 21:53:38.289   319   319 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-26 21:53:38.289   319   319 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-26 21:53:38.289   319   319 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-26 21:53:38.289   319   319 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-26 21:53:38.289   319   319 V AudioFlinger: createTrack() lSessionId: 22
08-26 21:53:38.290  7054  7054 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-26 21:53:38.290   319   319 V AudioFlinger: acquiring 22 from 7054, for 7054
08-26 21:53:38.290   319   319 V AudioFlinger:  added new entry for 22
08-26 21:53:38.290  7054  7054 V ToneGenerator: ToneGenerator INIT OK, time: 131058
08-26 21:53:38.290  7054  7054 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1bb02614
08-26 21:53:38.291  7054  7054 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1bb02614
08-26 21:53:38.291  7054  7570 E BluetoothAdapterService: File transfer profiles supported!!
08-26 21:53:38.292  7054  7593 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-26 21:53:38.293  7054  7593 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-26 21:53:38.293  7054  7593 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-26 21:53:38.293  7054  7593 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-26 21:53:38.293  7054  7054 D A2dpService: Received start request. Starting profile...
08-26 21:53:38.293   319  1383 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7054
08-26 21:53:38.293  7054  7054 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-26 21:53:38.293   319  1383 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-26 21:53:38.293   319  1383 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-26 21:53:38.293   319  1383 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-26 21:53:38.293   319  1383 V compress_v,oip: voice_extn_compress_voip_set_parameters: exit
08-26 21:53:38.293   319  1383 V voice   : voice_set_parameters: exit with code(0)
08-26 21:53:38.294   319  1383 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-26 21:53:38.294   319  1383 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-26 21:53:38.294   319  1383 V msm8974_platform: platform_set_parameters: exit with code(0)
08-26 21:53:38.294   319  1383 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-26 21:53:38.294   319  1383 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-26 21:53:38.294   319  1383 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-26 21:53:38.294  7054  7593 V ToneGenerator: ToneGenerator destructor
08-26 21:53:38.294  7054  7593 V ToneGenerator: stopTone
08-26 21:53:38.294  7054  7593 V ToneGenerator: Delete Track: 0xb4928a80
08-26 21:53:38.294  7054  7593 V AudioTrack: ~AudioTrack, releasing session id from 7054 on behalf of 7054
08-26 21:53:38.294  7054  7054 V Avrcp   : make
08-26 21:53:38.294   319  1384 V AudioFlinger: releasing 22 from 7054 for 7054
08-26 21:53:38.294   319  1384 V AudioFlinger:  decremented refcount to 0
08-26 21:53:38.294   319  1384 V AudioFlinger: purging stale effects
08-26 21:53:38.294   319  1384 V AudioPolicyService: AudioCommandThread() adding release output 2
08-26 21:53:38.294   319  1384 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-26 21:53:38.294   319  1272 V AudioPolicyService: AudioCommandThread() waking up
08-26 21:53:38.294   319  1272 V AudioPolicyService: AudioCommandThread() processing release output 2
08-26 21:53:38.294   319  1272 V AudioPolicyManager: releaseOutput() 2
08-26 21:53:38.294   319  1272 V AudioPolicyService: AudioCommandThread() going to sleep
08-26 21:53:38.294   319  1384 V AudioFlinger: PlaybackThread::Track destructor
08-26 21:53:38.295   319  1384 V AudioFlinger: removeClient_l() pid 7054, calling pid 319
08-26 21:53:38.295  7054  7054 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-26 21:53:38.295  7054  7054 I bluedroid-qcom: get_profile_interface avrcp
08-26 21:53:38.295  2205  2205 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
08-26 21:53:38.298  7054  7570 E BluetoothAdapterService: File transfer profiles supported!!
,08-26 21:53:38.304  7054  7054 V AudioManager: registerRemoteController: size of Media player list: 0
08-26 21:53:38.305  7054  7054 E AudioManager: No RCC entry present to update
08-26 21:53:38.305  7054  7054 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-26 21:53:38.308  7054  7054 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-26 21:53:38.309  7054  7054 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-26 21:53:38.309  7054  7054 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
,08-26 21:53:38.316  7054  7570 E BluetoothAdapterService: File transfer profiles supported!!
,08-26 21:53:38.319  7154  7154 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-26 21:53:38.319  7054  7054 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-26 21:53:38.319  7154  7154 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-26 21:53:38.319  7154  7154 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-26 21:53:38.319  7154  7154 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-26 21:53:38.361  7154  7154 I AppUp4:CustModeStarterReceiver: onReceive
08-26 21:53:38.371  7154  7154 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@b1b8426
08-26 21:53:38.371  7154  7154 D AppUp4:CustFacade: isCustomizationCompleted : false
08-26 21:53:38.371  7154  7154 D AppUp4:CustFacade: isPhone : true
,08-26 21:53:38.374  7154  7154 D AppUp4:CustModeStarterReceiver: begin check event
08-26 21:53:38.375  7154  7154 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-26 21:53:38.378  4754  4754 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-26 21:53:38.378  4754  4754 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-26 21:53:38.379  4754  4754 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 21:53:38.380  4754  4754 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 21:53:38.387  7188  7188 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-26 21:53:38.393  4754  7614 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-26 21:53:38.398  4754  7615 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-26 21:53:38.398  4754  7615 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-26 21:53:38.399  7054  7570 V LGMDMManager: Create singleton instance
08-26 21:53:38.401  7054  7570 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,08-26 21:53:38.407  7188  7616 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 21:53:38.411  7024  7618 W FormManager: Network not available. Please check & try again.
08-26 21:53:38.412  3203  3203 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-26 21:53:38.412  3203  3203 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-26 21:53:38.412  3203  3203 I LgeMiscReceiver: networkInfo.isConnected() = false
08-26 21:53:38.415  7224  7224 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,08-26 21:53:38.415  7224  7224 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-26 21:53:38.420  7024  7619 V FormManager: Network unavailable.
08-26 21:53:38.423  7594  7594 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-26 21:53:38.423  7594  7594 W LG Account v2.2: No ProfileInfo entries
08-26 21:53:38.423  7594  7594 I LG Account v2.2: isEnabled: false
08-26 21:53:38.423  7594  7594 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-26 21:53:38.423  7594  7594 I Feature : [Lifetracker]Country: EU
08-26 21:53:38.424  7594  7594 I Feature : [Lifetracker]Operator: OPEN
08-26 21:53:38.424  7594  7594 I Feature : [Lifetracker]Ranking support: false
08-26 21:53:38.424  7594  7594 I Feature : [Lifetracker]Comfort support: false
08-26 21:53:38.424  7594  7594 I Feature : [Lifetracker]Accessory: true
08-26 21:53:38.424  7594  7594 I Feature : [Lifetracker]Health device: true
08-26 21:53:38.424  7594  7594 I Feature : [Lifetracker]Extra Pedometer: false
08-26 21:53:38.424  7594  7594 I Feature : [Lifetracker]Blood glucose device: false
08-26 21:53:38.424  7594  7594 I Feature : [Lifetracker]Device Number: 3
08-26 21:53:38.426  7024  7619 V FormManager: Network unavailable.
,08-26 21:53:38.437  7285  7285 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 21:53:38
08-26 21:53:38.438  7285  7285 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-26 21:53:38.438  7285  7285 D Weather.Utils: 2 : All the weather widget is gone.
08-26 21:53:38.438  7285  7285 D UpdateThreadPoolManager: 2 : This is isUpdating : false
,08-26 21:53:38.439  7285  7285 D WeatherAncestor: connectivity changed - connection : true
08-26 21:53:38.439  7285  7285 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@1bb02614
,08-26 21:53:38.441  6917  6917 D BluetoothPermissionRequest: onReceive
08-26 21:53:38.441  7285  7285 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-26 21:53:38.441  7285  7285 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-26 21:53:38.441  7285  7285 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-26 21:53:38.441  7285  7285 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-26 21:53:38.442  7285  7285 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 21:53:38
08-26 21:53:38.444  1034  1940 V SIM_STK : Menu title from STK is T-Mobile
08-26 21:53:38.444  1034  1940 V SIM_STK : Menu title from STK is T-Mobile
08-26 21:53:38.445  6917  6917 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-26 21:53:38.462  6448  6448 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-26 21:53:38.465  6448  6478 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-26 21:53:38.475  2205  2205 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-26 21:53:38.482  7154  7154 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-26 21:53:38.482  7154  7154 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-26 21:53:38.482  7154  7154 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-26 21:53:38.482  7154  7154 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-26 21:53:38.483  7154  7154 I AppUp4:CustModeStarterReceiver: onReceive
08-26 21:53:38.485  7154  7154 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@b1b8426
08-26 21:53:38.485  7154  7154 D AppUp4:CustFacade: isCustomizationCompleted : false
08-26 21:53:38.485  7154  7154 D AppUp4:CustFacade: isPhone : true
08-26 21:53:38.486  7154  7154 D AppUp4:CustModeStarterReceiver: begin check event
08-26 21:53:38.486  7154  7154 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-26 21:53:38.488  4754  4754 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-26 21:53:38.488  4754  4754 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-26 21:53:38.489  4754  4754 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-26 21:53:38.491  4754  4754 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 21:53:38.495  7188  7188 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-26 21:53:38.495  4754  7624 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-26 21:53:38.496  4754  7625 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-26 21:53:38.496  4754  7625 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-26 21:53:38.509  1034  1732 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-26 21:53:38.509  7188  7626 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-26 21:53:38.512  3203  3203 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,08-26 21:53:38.512  3203  3203 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-26 21:53:38.512  3203  3203 I LgeMiscReceiver: networkInfo.isConnected() = false
08-26 21:53:38.514  7054  7054 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-26 21:53:38.517  7224  7224 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-26 21:53:38.517  7224  7224 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-26 21:53:38.518  7054  7054 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-26 21:53:38.518  7054  7054 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-26 21:53:38.518  7054  7054 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-26 21:53:38.518  7054  7054 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-26 21:53:38.518  7054  7054 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-26 21:53:38.518  7054  7054 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-26 21:53:38.518  7054  7054 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-26 21:53:38.518  7054  7054 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-26 21:53:38.519  7054  7054 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-26 21:53:38.519  7054  7054 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-26 21:53:38.519  7054  7054 I BluetoothA2dpServiceJni: classInitNative
08-26 21:53:38.519  7054  7054 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-26 21:53:38.519  7054  7054 D A2dpStateMachine: make
08-26 21:53:38.520  7054  7054 I bluedroid-qcom: get_profile_interface a2dp
08-26 21:53:38.520  7054  7632 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-26 21:53:38.522  7054  7054 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-26 21:53:38.522  7054  7054 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-26 21:53:38.523  7054  7054 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1bb02614
08-26 21:53:38.523  7054  7631 D A2dpStateMachine: Enter Disconnected: -2
08-26 21:53:38.524  7054  7054 I BluetoothHidServiceJni: classInitNative: succeeds
08-26 21:53:38.525  7054  7054 D HidService: Received start request. Starting profile...
08-26 21:53:38.525  7054  7054 I bluedroid-qcom: get_profile_interface hidhost
08-26 21:53:38.525  7054  7054 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1bb02614
08-26 21:53:38.525  7054  7054 D HeadsetStateMachine: Proxy object connected
08-26 21:53:38.525  7054  7054 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-26 21:53:38.525  7054  7054 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-26 21:53:38.525  7024  7629 W FormManager: Network not available. Please check & try again.
,08-26 21:53:38.529  7024  7630 V FormManager: Network unavailable.
08-26 21:53:38.530  7054  7054 I BluetoothHealthServiceJni: classInitNative: succeeds
08-26 21:53:38.531  7054  7054 D HealthService: Received start request. Starting profile...
08-26 21:53:38.532  7054  7054 I bluedroid-qcom: get_profile_interface health
08-26 21:53:38.532  7054  7054 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-26 21:53:38.532  7054  7054 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1bb02614
08-26 21:53:38.533  7285  7285 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 21:53:38
08-26 21:53:38.533  7054  7593 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-26 21:53:38.534  7054  7593 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-26 21:53:38.534  7024  7630 V FormManager: Network unavailable.
,08-26 21:53:38.534  7054  7593 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-26 21:53:38.535  7285  7285 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-26 21:53:38.535  7285  7285 D Weather.Utils: 2 : All the weather widget is gone.
08-26 21:53:38.535  7285  7285 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-26 21:53:38.535  7285  7285 D WeatherAncestor: connectivity changed - connection : true
08-26 21:53:38.535  7285  7285 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@1bb02614
08-26 21:53:38.535  7054  7054 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-26 21:53:38.536  7285  7285 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-26 21:53:38.536  7054  7054 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-26 21:53:38.536  7285  7285 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-26 21:53:38.536  7285  7285 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-26 21:53:38.536  7285  7285 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-26 21:53:38.536  7285  7285 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 21:53:38
,08-26 21:53:38.538  7054  7054 D PanService: Received start request. Starting profile...
08-26 21:53:38.538  7054  7054 D BluetoothPanServiceJni: initializeNative(L110): pan
08-26 21:53:38.538  7054  7054 I bluedroid-qcom: get_profile_interface pan
08-26 21:53:38.544  7054  7054 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-26 21:53:38.544  7054  7054 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1bb02614
08-26 21:53:38.545  7054  7054 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-26 21:53:38.551  7054  7054 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-26 21:53:38.551  7054  7054 D BtGatt.GattService: Received start request. Starting profile...
08-26 21:53:38.551  7054  7054 D BtGatt.GattService: start()
08-26 21:53:38.551  7054  7054 I bluedroid-qcom: get_profile_interface gatt
08-26 21:53:38.552  7054  7054 D BtGatt.AdvertiseManager: advertise manager created
08-26 21:53:38.557  7054  7054 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1bb02614
08-26 21:53:38.558  7054  7054 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1bb02614
08-26 21:53:38.558  7054  7054 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-26 21:53:38.559  7054  7054 V BluetoothMapService: BluetoothMapBinder()
08-26 21:53:38.559  7054  7054 D BluetoothMapService: Received start request. Starting profile...
08-26 21:53:38.559  7054  7054 D BluetoothMapService: start()
08-26 21:53:38.561  7054  7054 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-26 21:53:38.561  7054  7054 D BluetoothMapEmailAppObserver: createReceiver()
08-26 21:53:38.562  7054  7054 D BluetoothMapEmailAppObserver: initObservers()
,08-26 21:53:38.562  7054  7054 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-26 21:53:38.568  7054  7054 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1bb02614
08-26 21:53:38.570  7054  7054 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-26 21:53:38.572  7054  7054 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-26 21:53:38.574  7054  7054 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-26 21:53:38.574  7054  7054 V PanService: [BTUI] SIM Extra State :ABSENT
,08-26 21:53:38.577  7054  7054 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-26 21:53:38.578  7054  7054 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-26 21:53:38.578  7054  7054 V BluetoothMapService: Handler(): got msg=1
08-26 21:53:38.579  7054  7570 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-26 21:53:38.579  7054  7570 I bluedroid-qcom: enable
08-26 21:53:38.579  7054  7570 I bt_hci_bdroid: init
08-26 21:53:38.580  7054  7054 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-26 21:53:38.581  7054  7570 I bt_vendor: bt-vendor : init
08-26 21:53:38.581  7054  7570 I bt_vendor: bt-vendor : get_bt_soc_type
08-26 21:53:38.581  7054  7570 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-26 21:53:38.581  7054  7570 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-26 21:53:38.581  7054  7570 D bt_userial_mct: userial_init
08-26 21:53:38.581  7054  7639 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-26 21:53:38.581  7054  7570 D bt_hci_bdroid: set_power 1
08-26 21:53:38.581  7054  7570 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-26 21:53:38.581  7054  7570 I bt_vendor: Starting hciattach daemon
08-26 21:53:38.581  7054  7570 I bt_vendor: try to set true
08-26 21:53:38.581  7054  7639 I bt-btu  : btu_task pending for preload complete event
08-26 21:53:38.582  7054  7054 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-26 21:53:38.582  7054  7054 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-26 21:53:38.582  7054  7054 V BluetoothSapReceiver: SapReceiver onReceive 
08-26 21:53:38.582  7054  7054 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 21:53:38.582  7054  7054 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-26 21:53:38.579  7642  7642 W sh      : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 21:53:38.579  7642  7642 W sh      : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 21:53:38.606  7643  7643 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-26 21:53:38.646  1034  1940 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=7646 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-26 21:53:38.685  7666  7666 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-26 21:53:38.697  7667  7667 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-26 21:53:38.705  7646  7646 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-26 21:53:38.721  1034  1940 I ActivityManager: Killing 6613:com.android.vending/u0a44 (adj 15): empty #17
,08-26 21:53:38.735  7669  7669 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-26 21:53:38.748  7670  7670 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-26 21:53:38.764  7671  7671 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-26 21:53:38.785  7672  7672 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-26 21:53:38.814  1034  2006 W libprocessgroup: failed to open /acct/uid_10044/pid_6613/cgroup.procs: No such file or directory
,08-26 21:53:38.822  7674  7674 I libmdmdetect: ESOC framework not supported
08-26 21:53:38.824  7674  7674 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
08-26 21:53:38.833  7674  7674 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-26 21:53:38.833  7674  7674 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-26 21:53:38.833  7674  7674 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-26 21:53:38.833  7674  7674 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
,08-26 21:53:38.833  7674  7674 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-26 21:53:38.833  7674  7674 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-26 21:53:38.833  7674  7674 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
,08-26 21:53:38.884  7674  7675 E QC-QMI  : qmi_client [7674] 14: failed to locate client data
,08-26 21:53:38.887   469   469 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-26 21:53:38.887   469   469 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
08-26 21:53:38.942  7679  7679 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-26 21:53:38.969  7683  7683 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-26 21:53:38.990  1034  1091 W ProcessCpuTracker: Skipping unknown process pid 7579
,08-26 21:53:38.992  1034  1091 W ProcessCpuTracker: Skipping unknown process pid 7582
08-26 21:53:38.995  1034  1091 W ProcessCpuTracker: Skipping unknown process pid 7642
08-26 21:53:38.996  1034  1091 W ProcessCpuTracker: Skipping unknown process pid 7679
08-26 21:53:39.034  7054  7570 I bt_vendor: bluetooth satus is on
,08-26 21:53:39.034  7054  7570 D bt_hci_bdroid: preload
,08-26 21:53:39.034  7054  7641 D bt_userial_mct: userial_open(port:0)
08-26 21:53:39.034  7054  7641 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
08-26 21:53:39.038  7054  7641 I bt_vendor: Done intiailizing UART
08-26 21:53:39.039  7054  7641 I bt_vendor: Done intiailizing UART
,08-26 21:53:39.039  7054  7641 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-26 21:53:39.039  7054  7641 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-26 21:53:39.039  7054  7639 I bt-btu  : btu_task received preload complete event
08-26 21:53:39.040  7054  7685 D bt_userial_mct: Entering userial_read_thread()
08-26 21:53:39.041  7054  7639 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
,08-26 21:53:39.041  7054  7639 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-26 21:53:39.043  7054  7639 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-26 21:53:39.046  7054  7639 I         : BTE_InitTraceLevels -- TRC_HCI
08-26 21:53:39.046  7054  7639 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-26 21:53:39.046  7054  7639 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-26 21:53:39.046  7054  7639 I         : BTE_InitTraceLevels -- TRC_AVDT
08-26 21:53:39.046  7054  7639 I         : BTE_InitTraceLevels -- TRC_AVRC
08-26 21:53:39.047  7054  7639 I         : BTE_InitTraceLevels -- TRC_A2D
08-26 21:53:39.047  7054  7639 I         : BTE_InitTraceLevels -- TRC_BNEP
08-26 21:53:39.047  7054  7639 I         : BTE_InitTraceLevels -- TRC_BTM
08-26 21:53:39.047  7054  7639 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-26 21:53:39.047  7054  7639 I         : BTE_InitTraceLevels -- TRC_GAP
08-26 21:53:39.047  7054  7639 I         : BTE_InitTraceLevels -- TRC_PAN
08-26 21:53:39.047  7054  7639 I         : BTE_InitTraceLevels -- TRC_SDP
08-26 21:53:39.047  7054  7639 I         : BTE_InitTraceLevels -- TRC_GATT
08-26 21:53:39.047  7054  7639 I         : BTE_InitTraceLevels -- TRC_SMP
08-26 21:53:39.048  7054  7639 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-26 21:53:39.048  7054  7639 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-26 21:53:39.129  7054  7639 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
,08-26 21:53:39.129  7054  7639 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa016c061 
08-26 21:53:39.129  7054  7639 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa016c061 
,08-26 21:53:39.172  7054  7574 E bt-btif : Calling BTA_HhEnable
08-26 21:53:39.173  7054  7574 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-26 21:53:39.173  7054  7574 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-26 21:53:39.179  7054  7639 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-26 21:53:39.179  7054  7639 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
,08-26 21:53:39.179  7054  7639 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-26 21:53:39.179  1034  1034 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-26 21:53:39.180  1034  1034 D BluetoothManagerService: Stored Bluetooth name: G3
08-26 21:53:39.180  7054  7574 D BluetoothAdapterProperties: Name is: G3
08-26 21:53:39.181  7054  7639 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
,08-26 21:53:39.181  7054  7639 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-26 21:53:39.181  7054  7574 D BluetoothAdapterProperties: Scan Mode:20
08-26 21:53:39.181  7054  7574 D BluetoothAdapterProperties: Discoverable Timeout:120
08-26 21:53:39.182  7054  7574 D bt_hci_bdroid: postload
08-26 21:53:39.185  7054  7574 D bte_conf: Device ID record 1 : primary
08-26 21:53:39.185  7054  7574 D bte_conf:   vendorId            = 00c4
08-26 21:53:39.185  7054  7574 D bte_conf:   vendorIdSource      = 0001
08-26 21:53:39.185  7054  7574 D bte_conf:   product             = 13a1
08-26 21:53:39.185  7054  7574 D bte_conf:   version             = 1000
08-26 21:53:39.185  7054  7574 D bte_conf:   clientExecutableURL = 
08-26 21:53:39.185  7054  7574 D bte_conf:   serviceDescription  = 
08-26 21:53:39.185  7054  7574 D bte_conf:   documentationURL    = 
08-26 21:53:39.185  7054  7574 D bte_conf: bte_load_did_conf no section named DID2.
08-26 21:53:39.185  7054  7639 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-26 21:53:39.186  7054  7641 D bt_hci_bdroid: Used up Tx Cmd credits
08-26 21:53:39.186  6674  6674 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 21:53:39.189  7054  7641 D bt_hci_bdroid: Used up Tx Cmd credits
08-26 21:53:39.189  7054  7641 D bt_hci_bdroid: Used up Tx Cmd credits
08-26 21:53:39.190  7054  7641 D bt_hci_bdroid: Used up Tx Cmd credits
08-26 21:53:39.190  7054  7641 D bt_hci_bdroid: Used up Tx Cmd credits
08-26 21:53:39.189  7687  7687 W sh      : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 21:53:39.189  7687  7687 W sh      : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-26 21:53:39.196  7054  7685 E bt_mct  : hci lib postload completed
08-26 21:53:39.196  6674  6674 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 21:53:39.197  7054  7570 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-26 21:53:39.197  7054  7570 D BluetoothAdapterProperties: ScanMode =  20
08-26 21:53:39.198  7054  7570 D BluetoothAdapterProperties: State =  11
08-26 21:53:39.198  7054  7570 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-26 21:53:39.198  7054  7570 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-26 21:53:39.198  7054  7570 D BluetoothAdapterProperties: Setting state to 12
08-26 21:53:39.198  7054  7570 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-26 21:53:39.199  1034  1105 D BluetoothManagerService: Message: 60
08-26 21:53:39.199  1034  1105 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-26 21:53:39.199  1034  1105 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
08-26 21:53:39.199  7054  7570 I BluetoothAdapterState: Entering On State
08-26 21:53:39.199  1853  2717 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 21:53:39.201  7054  7570 D LGBluetoothServiceAdapter: [BTUI] OnState
08-26 21:53:39.201  7054  7570 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-26 21:53:39.201  7054  7570 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-26 21:53:39.202  7054  7570 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-26 21:53:39.202  7054  7574 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-26 21:53:39.203  7054  7574 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-26 21:53:39.204  7054  7639 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
,08-26 21:53:39.204  7054  7639 W bt-smp  : Plain text(LSB ~ MSB) = 76 f2 43 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-26 21:53:39.204  7054  7639 W bt-smp  : Encrypted text(LSB ~ MSB) = db 23 61 fb e8 a7 79 db 7b be a4 33 89 c9 04 a9 
08-26 21:53:39.204  7054  7639 W bt-btm  : Stopping oneshot timer
08-26 21:53:39.212  1853  1853 D BluetoothHeadset: Proxy object connected
08-26 21:53:39.213  1853  2419 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 21:53:39.215  1853  1853 D BluetoothHeadset: Proxy object connected
08-26 21:53:39.215  6917  7041 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-26 21:53:39.223  1853  2717 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 21:53:39.224  7054  7639 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-26 21:53:39.224  7054  7639 W bt-smp  : Plain text(LSB ~ MSB) = 75 13 7a 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-26 21:53:39.224  7054  7639 W bt-smp  : Encrypted text(LSB ~ MSB) = b3 7d b9 e9 01 b9 33 bf 02 8b 35 96 9b 8b a0 35 
08-26 21:53:39.224  7054  7639 W bt-btm  : Stopping oneshot timer
,08-26 21:53:39.232  6917  6917 D BluetoothInputDevice: Proxy object connected
08-26 21:53:39.232  6917  6917 D HidProfile: Bluetooth service connected
08-26 21:53:39.236  1853  1853 D BluetoothHeadset: Proxy object connected
,08-26 21:53:39.239  6917  7041 D BluetoothPbap: onBluetoothStateChange: up=true
08-26 21:53:39.243  6917  6933 D BluetoothPan: onBluetoothStateChange on: true
08-26 21:53:39.243  6917  6933 D BluetoothPan: onBluetoothStateChange call bindService
08-26 21:53:39.244  7054  7639 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-26 21:53:39.244  7054  7639 W bt-smp  : Plain text(LSB ~ MSB) = 0d 37 6e 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-26 21:53:39.244  7054  7639 W bt-smp  : Encrypted text(LSB ~ MSB) = 1d 73 26 e9 ed a4 fb 1d 8b e7 aa 12 90 ad 10 79 
08-26 21:53:39.244  7054  7639 W bt-btm  : Stopping oneshot timer
08-26 21:53:39.248  1034  1105 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-26 21:53:39.251  7054  7570 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-26 21:53:39.260  7054  7639 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-26 21:53:39.260  7054  7639 W bt-smp  : Plain text(LSB ~ MSB) = ee 2d 62 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-26 21:53:39.260  7054  7639 W bt-smp  : Encrypted text(LSB ~ MSB) = 78 6d 2d d4 f7 3b 55 c8 e3 bc 76 ad f5 29 8d 91 
08-26 21:53:39.260  7054  7639 W bt-btm  : Stopping oneshot timer
08-26 21:53:39.262  6917  6917 D BluetoothPan: BluetoothPAN Proxy object connected
08-26 21:53:39.262  6917  6917 D PanProfile: Bluetooth service connected
,08-26 21:53:39.266  1034  1034 D BluetoothHeadset: Proxy object connected
08-26 21:53:39.265  7054  7574 D BluetoothAdapterProperties: Discoverable Timeout:120
08-26 21:53:39.267  7054  7574 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-26 21:53:39.269  6917  7041 D BluetoothMap: onBluetoothStateChange: up=true
08-26 21:53:39.273  7700  7700 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-26 21:53:39.280  6917  6917 D BluetoothMap: Proxy object connected
08-26 21:53:39.280  6917  6917 D MapProfile: Bluetooth service connected
08-26 21:53:39.280  1034  1105 D BluetoothA2dp: onBluetoothStateChange: up=true
08-26 21:53:39.280  6917  6917 D BluetoothMap: getConnectedDevices()
,08-26 21:53:39.284  7054  7639 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-26 21:53:39.284  7054  7639 W bt-smp  : Plain text(LSB ~ MSB) = 30 ba 6b 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-26 21:53:39.284  7054  7639 W bt-smp  : Encrypted text(LSB ~ MSB) = d5 52 de 36 4b f5 8f 0d c3 04 10 02 01 29 c7 a6 
08-26 21:53:39.284  7054  7639 W bt-btm  : Stopping oneshot timer
08-26 21:53:39.285  7054  7701 V BluetoothMapService: getConnectedDevices()
08-26 21:53:39.287  1034  1034 D BluetoothA2dp: Proxy object connected
08-26 21:53:39.288  1034  1105 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-26 21:53:39.288  1034  1105 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-26 21:53:39.291  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-26 21:53:39.292  1942  1942 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-26 21:53:39.292  1942  2102 D LGBluetoothAPIService: Message: 1
08-26 21:53:39.292  1942  2102 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-26 21:53:39.298  6674  6674 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
08-26 21:53:39.302  1942  2102 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
08-26 21:53:39.303  6917  6917 D LocalBluetoothProfileManager: Adding local A2DP profile
08-26 21:53:39.306  1034  1105 D BluetoothManagerService: Message: 30
,08-26 21:53:39.316  6674  6674 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 21:53:39.316  6674  6674 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 21:53:39.316  6674  6674 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 21:53:39.316  6674  6674 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 21:53:39.316  6674  6674 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 21:53:39.316  6674  6674 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 21:53:39.316  6674  6674 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 21:53:39.316  6674  6674 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 21:53:39.318  7054  7054 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-26 21:53:39.318  6917  6917 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-26 21:53:39.318  7054  7054 D BluetoothMapService: STATE_ON
08-26 21:53:39.319  6674  6674 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 21:53:39.321  1034  1105 D BluetoothManagerService: Message: 30
08-26 21:53:39.321  7054  7054 D LGBluetoothAPIServer: [BTUI] onCreate()
08-26 21:53:39.321  7054  7054 D LGBluetoothAPIServer: [BTUI] onBind()
08-26 21:53:39.324  6674  6674 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 21:53:39.324  6674  6674 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 21:53:39.324  6674  6674 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 21:53:39.324  6674  6674 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 21:53:39.324  6674  6674 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 21:53:39.324  6674  6674 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 21:53:39.324  6674  6674 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 21:53:39.324  6674  6674 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 21:53:39.324  1942  1942 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-26 21:53:39.325  1942  2102 D LGBluetoothAPIService: Message: 100
08-26 21:53:39.325  1942  2102 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-26 21:53:39.326  6674  6674 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 21:53:39.327  6917  6917 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-26 21:53:39.328  6917  6917 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-26 21:53:39.335  6917  6917 D BluetoothA2dp: Proxy object connected
,08-26 21:53:39.335  6917  6917 D A2dpProfile: Bluetooth service connected
08-26 21:53:39.338  7317  7353 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
08-26 21:53:39.339  6917  6917 D BluetoothHeadset: Proxy object connected
08-26 21:53:39.340  6917  6917 D HeadsetProfile: Bluetooth service connected
08-26 21:53:39.342  7054  7054 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1bb02614
08-26 21:53:39.342  7054  7054 V BluetoothPbapService: Pbap Service onCreate
08-26 21:53:39.342  7054  7054 V BluetoothPbapService: Starting PBAP service
,08-26 21:53:39.344  7054  7054 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-26 21:53:39.344  7054  7054 V BluetoothPbapService: Pbap Service onBind
08-26 21:53:39.346  7054  7054 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-26 21:53:39.346  7054  7054 V BluetoothPbapService: state: 12
08-26 21:53:39.346  7054  7054 V BluetoothMapService: Handler(): got msg=1
08-26 21:53:39.347  6917  6917 D DockEventReceiver: finishStartingService: stopping service
08-26 21:53:39.347  7054  7054 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-26 21:53:39.348  7054  7054 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-26 21:53:39.348  7054  7054 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 21:53:39.348  6917  6917 D BluetoothPbap: Proxy object connected
08-26 21:53:39.348  7054  7054 V BluetoothPbapReceiver: ***********state = 12
08-26 21:53:39.348  6917  6917 D PbapServerProfile: Bluetooth service connected
08-26 21:53:39.350  7054  7710 D BluetoothMapMasInstance: MAS initSocket()
08-26 21:53:39.350  7054  7710 D BluetoothMapMasInstance:   masId = 00
08-26 21:53:39.350  7054  7710 D BluetoothMapMasInstance:   msgTypes = 0e
08-26 21:53:39.350  7054  7710 D BluetoothMapMasInstance:   masName = SMS/MMS
08-26 21:53:39.350  7054  7710 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-26 21:53:39.353  7054  7054 V BluetoothPbapService: Handler(): got msg=1
08-26 21:53:39.353  7054  7054 V BluetoothPbapService: Pbap Service startRfcommSocketListener
,08-26 21:53:39.354  1034  2030 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 21:53:39.355  7054  7711 V BluetoothPbapService: Pbap Service initSocket
08-26 21:53:39.356  2205  2205 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-26 21:53:39.356  7054  7710 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 21:53:39.357  2205  2205 D c       : Getting all permits...
08-26 21:53:39.357  2205  2205 D a       : Opening database...
08-26 21:53:39.357  1034  2030 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 21:53:39.358  7054  7711 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 21:53:39.359  7054  7574 D BluetoothAdapterProperties: Scan Mode:21
08-26 21:53:39.360  7054  7574 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-26 21:53:39.360  7054  7711 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=0
08-26 21:53:39.360  7054  7710 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-26 21:53:39.360  7054  7710 V BluetoothMapMasInstance: Succeed to create listening socket 
08-26 21:53:39.360  7054  7711 V BluetoothPbapService: Succeed to create listening socket 
08-26 21:53:39.360  7054  7711 V BluetoothPbapService: Accepting socket connection...
08-26 21:53:39.360  7054  7710 D BluetoothMapMasInstance: Accepting socket connection...
08-26 21:53:39.361  6674  6674 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 21:53:39.364  6674  6674 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 21:53:39.365  2205  2205 D a       : Opening database auth.proximity.permit_store...
08-26 21:53:39.366  2205  2205 D a       : Closing database...
,08-26 21:53:39.374  6917  6917 D BluetoothPermissionRequest: onReceive
08-26 21:53:39.376  6917  6917 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-26 21:53:39.377  6917  6917 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-26 21:53:39.380  7054  7054 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
,08-26 21:53:39.381  7054  7054 I LGBluetoothOppAdapter: [BTUI] startOppService()
,08-26 21:53:39.386  7054  7054 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
08-26 21:53:39.401  7054  7054 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-26 21:53:39.402  7054  7054 V BtOppService: onCreate
,08-26 21:53:39.405  7054  7054 V BluetoothOppNotification: send message
08-26 21:53:39.408  7054  7054 V BtOppService: Starting RfcommListener
08-26 21:53:39.410  7054  7054 D BluetoothOppPreference: Dumping Names:  
08-26 21:53:39.410  7054  7054 D BluetoothOppPreference: {}
08-26 21:53:39.410  7054  7054 D BluetoothOppPreference: Dumping Channels:  
08-26 21:53:39.411  7054  7054 D BluetoothOppPreference: {}
08-26 21:53:39.411  7054  7054 V BtOppService: onStartCommand
08-26 21:53:39.414  7054  7717 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
,08-26 21:53:39.416  7054  7714 V BtOppService: Deleted complete outbound shares, number =  0
08-26 21:53:39.416  7054  7717 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-26 21:53:39.418  7054  7054 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-26 21:53:39.419  7054  7054 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-26 21:53:39.419  7054  7714 V BtOppService: Deleted complete inbound failed shares, number = 0
08-26 21:53:39.420  7054  7714 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-26 21:53:39.422  7054  7714 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3700440e on behalf of 
08-26 21:53:39.422  7054  7054 V BluetoothOppNotification: new notify threadi!
08-26 21:53:39.422  7054  7054 V BluetoothOppNotification: send delay message
08-26 21:53:39.422  7054  7717 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@20295a09 on behalf of 
08-26 21:53:39.423  7054  7054 V BtOppService: start RfcommListener
08-26 21:53:39.424  7054  7717 V BluetoothOppNotification: update too frequent, put in queue
08-26 21:53:39.424  1034  1034 I art     : Explicit concurrent mark sweep GC freed 95790(4MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/64MB, paused 2.446ms total 121.355ms
08-26 21:53:39.424  1034  1034 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-26 21:53:39.424  1034  1105 D BluetoothManagerService: Message: 40
08-26 21:53:39.424  1034  1105 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-26 21:53:39.425  7054  7717 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
,08-26 21:53:39.426  7054  7717 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-26 21:53:39.428  7054  7054 V BtOppService: RfcommListener started
08-26 21:53:39.428  7054  7054 V BtOppService: ContentObserver received notification
08-26 21:53:39.428  7054  7054 V BtOppService: ContentObserver received notification
08-26 21:53:39.430  7054  7718 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-26 21:53:39.431  7054  7719 V BtOppRfcommListener: Starting RFCOMM listener....
08-26 21:53:39.431  7054  7718 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@30ad6e2f on behalf of 
08-26 21:53:39.431  1034  1940 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 21:53:39.432  7054  7718 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-26 21:53:39.432  7054  7717 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@38c46c3c on behalf of 
08-26 21:53:39.432  7054  7719 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 21:53:39.434  7054  7719 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=73
08-26 21:53:39.434  7054  7719 V BtOppRfcommListener: Started RFCOMM listener....
08-26 21:53:39.434  7054  7719 I BtOppRfcommListener: Accept thread started.
08-26 21:53:39.434  7054  7719 V BtOppRfcommListener: Accepting connection...
08-26 21:53:39.434  7054  7717 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-26 21:53:39.434  7054  7717 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-26 21:53:39.435  7054  7718 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-26 21:53:39.436  7054  7717 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@37048dc5 on behalf of 
08-26 21:53:39.436  7054  7717 V BluetoothOppNotification: update too frequent, put in queue
08-26 21:53:39.437  7054  7718 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3b80931a on behalf of 
08-26 21:53:39.438  7054  7718 V BluetoothOppNotification: outbound: succ-0  fail-0
,08-26 21:53:39.440  7054  7717 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-26 21:53:39.442  7054  7718 V BluetoothOppNotification: outbound notification was removed.
08-26 21:53:39.442  7054  7718 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-26 21:53:39.443  7054  7718 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@22acbe4b on behalf of 
08-26 21:53:39.444  7054  7718 V BluetoothOppNotification: inbound: succ-0  fail-0
08-26 21:53:39.444  7054  7054 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1bb02614
08-26 21:53:39.444  7054  7054 V BluetoothFtpService: Ftp Service onCreate
08-26 21:53:39.444  7054  7054 I BluetoothFtpService: Ftp Service onCreate
08-26 21:53:39.445  7054  7054 V BluetoothFtpService: Ftp Service onStartCommand
08-26 21:53:39.445  7054  7718 V BluetoothOppNotification: inbound notification was removed.
08-26 21:53:39.445  7054  7054 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-26 21:53:39.445  7054  7718 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-26 21:53:39.445  7054  7054 V BluetoothFtpService: Starting Listening on sockets
08-26 21:53:39.445  7054  7054 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-26 21:53:39.445  7054  7054 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-26 21:53:39.445  7054  7054 V BluetoothSapReceiver: SapReceiver onReceive 
08-26 21:53:39.445  7054  7054 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 21:53:39.445  7054  7054 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-26 21:53:39.445  7054  7718 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@38a54141 on behalf of 
08-26 21:53:39.445  7054  7054 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-26 21:53:39.447  7054  7054 V BluetoothFtpService: Handler(): got msg=1
08-26 21:53:39.447  7054  7054 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-26 21:53:39.447  7054  7054 V BluetoothFtpService: Ftp Service initSocket
08-26 21:53:39.452  1034  1576 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 21:53:39.452  7054  7054 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 21:53:39.453  7054  7054 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-26 21:53:39.455  7054  7720 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-26 21:53:39.464  7054  7054 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1bb02614
08-26 21:53:39.464  7054  7054 V BluetoothSapService: Sap Service onCreate
08-26 21:53:39.466  7054  7054 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-26 21:53:39.466  7054  7054 V BluetoothSapService: state: 12
,08-26 21:53:39.466  7054  7054 V BluetoothSapService: Starting SAP server process
08-26 21:53:39.459  7721  7721 W sapd    : type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 21:53:39.459  7721  7721 W sapd    : type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 21:53:39.468  7054  7054 V BluetoothSapService: SAP Service startRfcommListenerThread
08-26 21:53:39.469  7054  7722 V BluetoothSapService: Sap Service initRfcommSocket
08-26 21:53:39.470  1034  1959 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 21:53:39.470  7054  7722 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 21:53:39.471  7054  7722 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-26 21:53:39.471  7054  7722 V BluetoothSapService: Succeed to create listening socket 
08-26 21:53:39.471  7054  7722 V BluetoothSapService: Accepting socket connection...
08-26 21:53:39.478  7721  7721 V BT_SAP  : Event pipe created
08-26 21:53:39.478  7721  7721 V BT_SAP  : create_server_socket qcom.sap.server
08-26 21:53:39.478  7721  7721 V BT_SAP  : created socket fd 6
,08-26 21:53:40.143  1034  1536 D LGWifiP2pService: P2pDisabledState{ when=-2ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-26 21:53:40.143  1034  1536 D LGWifiP2pService: DefaultState{ when=-3ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-26 21:53:40.180  1034  1537 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-26 21:53:40.186  1034  1537 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-26 21:53:40.206  1034  1995 I ActivityManager: Killing 7494:com.lge.bnr/1000 (adj 15): empty #17
,08-26 21:53:40.239  1034  1887 W libprocessgroup: failed to open /acct/uid_1000/pid_7494/cgroup.procs: No such file or directory
,08-26 21:53:40.425  7054  7054 V BluetoothOppNotification: new notify threadi!
,08-26 21:53:40.425  7054  7054 V BluetoothOppNotification: send delay message
,08-26 21:53:40.438  7054  7732 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-26 21:53:40.443  7054  7732 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@a43b07d on behalf of 
08-26 21:53:40.443  7054  7732 V BluetoothOppNotification: mUpdateCompleteNotification = true
,08-26 21:53:40.448  7054  7732 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-26 21:53:40.449  7054  7732 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3c466b72 on behalf of 
08-26 21:53:40.450  7054  7732 V BluetoothOppNotification: outbound: succ-0  fail-0
08-26 21:53:40.452  7054  7732 V BluetoothOppNotification: outbound notification was removed.
08-26 21:53:40.452  7054  7732 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-26 21:53:40.453  7054  7732 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2ae4abc3 on behalf of 
08-26 21:53:40.453  7054  7732 V BluetoothOppNotification: inbound: succ-0  fail-0
08-26 21:53:40.455  7054  7732 V BluetoothOppNotification: inbound notification was removed.
08-26 21:53:40.455  7054  7732 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-26 21:53:40.456  7054  7732 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@b84bc40 on behalf of 
,08-26 21:53:40.481  1034  1995 I ActivityManager: Killing 6850:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,08-26 21:53:40.503  6981  6981 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
,08-26 21:53:40.503  6981  6981 W System.err: android.os.DeadObjectException
08-26 21:53:40.503  6981  6981 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-26 21:53:40.503  6981  6981 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-26 21:53:40.503  6981  6981 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-26 21:53:40.503  6981  6981 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
,08-26 21:53:40.509  6981  6981 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-26 21:53:40.509  6981  6981 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-26 21:53:40.510  6981  6981 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-26 21:53:40.510  6981  6981 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-26 21:53:40.510  6981  6981 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-26 21:53:40.510  6981  6981 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-26 21:53:40.510  6981  6981 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 21:53:40.510  6981  6981 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 21:53:40.510  6981  6981 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-26 21:53:40.510  6981  6981 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-26 21:53:40.510  6981  6981 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-26 21:53:40.511  6981  6981 W System.err: android.os.DeadObjectException
08-26 21:53:40.512  6981  6981 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-26 21:53:40.512  6981  6981 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-26 21:53:40.512  6981  6981 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-26 21:53:40.512  6981  6981 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-26 21:53:40.512  6981  6981 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-26 21:53:40.512  6981  6981 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-26 21:53:40.512  6981  6981 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-26 21:53:40.512  6981  6981 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-26 21:53:40.512  6981  6981 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-26 21:53:40.512  6981  6981 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-26 21:53:40.512  6981  6981 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 21:53:40.512  6981  6981 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 21:53:40.512  6981  6981 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-26 21:53:40.512  6981  6981 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-26 21:53:40.512  6981  6981 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-26 21:53:40.513  6981  6981 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
08-26 21:53:40.538  1034  1887 W libprocessgroup: failed to open /acct/uid_1000/pid_6850/cgroup.procs: No such file or directory
08-26 21:53:40.539  1034  1887 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,08-26 21:53:40.552  6981  6981 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-26 21:53:40.552  6981  6981 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
,08-26 21:53:40.613  1034  1614 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7734 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-26 21:53:40.643   345   345 I art     : Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 437us total 29.686ms
,08-26 21:53:40.675   345   345 I art     : Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 360us total 29.382ms
,08-26 21:53:40.706  6981  6981 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-26 21:53:40.713   345   345 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 1.331ms total 35.059ms
08-26 21:53:40.752  7734  7734 D UEI.SmartControl: Quickset Services start...
,08-26 21:53:40.754  7734  7734 I UEI.SmartControl: Manufacture = LGE
,08-26 21:53:40.754  7734  7734 D UEI.SmartControl: Id = LGNevo
08-26 21:53:40.755  7734  7734 D UEI.SmartControl: File observer start...
08-26 21:53:40.757  7734  7734 E UEI.SmartControl: IR Port is disabled: false
,08-26 21:53:40.757  7734  7734 D UEI.SmartControl: Starting file observer...
08-26 21:53:40.757  7734  7734 D UEI.SmartControl: Extracting JNI libs...
,08-26 21:53:40.757  7734  7734 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
08-26 21:53:40.843  7734  7734 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
08-26 21:53:40.844  7734  7734 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-26 21:53:40.844  7734  7734 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,08-26 21:53:40.872  7734  7734 I UEI.SmartControl: --- Selecting new region: 6
,08-26 21:53:40.874  7734  7734 I UEI.SmartControl: Model = LG-D855
,08-26 21:53:40.876  7734  7734 D UEI.SmartControl: QS Service created
,08-26 21:53:40.888  7734  7734 I UEI.SmartControl: Service initServices...
,08-26 21:53:40.892  7734  7734 D UEI.SmartControl: QS start get config
,08-26 21:53:40.928  7734  7734 D UEI.SmartControl: Loading JNI Libs...
,08-26 21:53:41.084  1034  2033 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-26 21:53:41.085  1034  2033 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@24c726bb mBinding = false
,08-26 21:53:41.104  1034  1105 D BluetoothManagerService: Message: 2
08-26 21:53:41.105  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-26 21:53:41.106  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-26 21:53:41.106  1034  1034 D Ulp_jni : JNI:system_update. Event-4
08-26 21:53:41.107  1034  1105 D BluetoothManagerService: Sending off request.
,08-26 21:53:41.108  7054  7073 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-26 21:53:41.109  7054  7570 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
,08-26 21:53:41.110  7054  7570 D BluetoothAdapterProperties: Setting state to 13
08-26 21:53:41.110  7054  7570 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-26 21:53:41.110  7054  7570 D BluetoothAdapterProperties: onBluetoothDisable()
08-26 21:53:41.110  7054  7570 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-26 21:53:41.111  1034  1105 D BluetoothManagerService: Message: 60
08-26 21:53:41.111  1034  1105 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-26 21:53:41.111  1034  1105 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-26 21:53:41.112  1942  1942 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-26 21:53:41.115  7054  7054 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-26 21:53:41.115  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-26 21:53:41.115  7054  7054 D BluetoothMapService: STATE_TURNING_OFF
08-26 21:53:41.115  7054  7054 V BluetoothMapService: Handler(): got msg=4
08-26 21:53:41.115  7054  7054 D BluetoothMapService: MAP Service closeService in
08-26 21:53:41.115  7054  7054 D BluetoothMapMasInstance: MAP Service shutdown
08-26 21:53:41.116  7054  7710 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-26 21:53:41.116  7054  7710 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 21:53:41.116  7054  7710 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-26 21:53:41.116  7054  7710 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-26 21:53:41.116  7054  7710 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-26 21:53:41.116  7054  7710 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-26 21:53:41.116  7054  7710 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-26 21:53:41.116  7054  7710 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-26 21:53:41.117  6917  6917 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
08-26 21:53:41.119  7054  7054 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-26 21:53:41.120  7054  7054 V BluetoothMapService: MAP Service closeService out
08-26 21:53:41.120  7054  7054 V BtOppService: Receiver DISABLED_ACTION 
08-26 21:53:41.120  7054  7054 I BtOppRfcommListener: stopping Accept Thread
08-26 21:53:41.121  7054  7054 V BtOppRfcommListener: close mBtServerSocket
,08-26 21:53:41.121  7054  7719 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 21:53:41.122  7054  7719 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-26 21:53:41.122  7054  7574 D BluetoothAdapterProperties: Scan Mode:20
08-26 21:53:41.123  7054  7054 V BtOppRfcommListener: waiting for thread to terminate
08-26 21:53:41.123  7054  7054 V BtOppRfcommListener: done waiting for thread to terminate
08-26 21:53:41.123  7054  7570 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-26 21:53:41.123  7054  7570 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-26 21:53:41.124  7054  7639 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-26 21:53:41.124  7054  7639 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-26 21:53:41.125  7054  7722 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 21:53:41.126  7054  7720 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 21:53:41.126  7054  7711 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 21:53:41.130  7054  7639 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-26 21:53:41.130  7054  7639 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-26 21:53:41.130  7054  7639 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-26 21:53:41.130  7054  7639 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-26 21:53:41.130  6674  6674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 21:53:41.130  7054  7639 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 21:53:41.130  7054  7639 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-26 21:53:41.130  7054  7639 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 21:53:41.130  7054  7639 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-26 21:53:41.130  7054  7639 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 21:53:41.130  6674  6674 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 21:53:41.130  6674  6674 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 21:53:41.130  6674  6674 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 21:53:41.130  6674  6674 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 21:53:41.130  6674  6674 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 21:53:41.130  6674  6674 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 21:53:41.130  6674  6674 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 21:53:41.130  6674  6674 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 21:53:41.130  7054  7639 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-26 21:53:41.130  7054  7639 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-26 21:53:41.130  7054  7639 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-26 21:53:41.131  6674  6674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 21:53:41.131  6674  6674 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: nul,l
08-26 21:53:41.132  7054  7054 V BtOppService: onDestroy
,08-26 21:53:41.136  6917  6917 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-26 21:53:41.137  6674  6674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 21:53:41.137  6674  6674 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 21:53:41.137  6674  6674 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 21:53:41.137  6674  6674 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 21:53:41.137  6674  6674 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 21:53:41.137  6674  6674 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 21:53:41.137  6674  6674 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 21:53:41.137  6674  6674 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 21:53:41.137  6674  6674 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 21:53:41.138  6674  6674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 21:53:41.138  6674  6674 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 21:53:41.140  6674  6674 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 21:53:41.141  6674  6674 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 21:53:41.146  7054  7054 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
,08-26 21:53:41.158  7054  7054 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-26 21:53:41.158  7054  7054 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 21:53:41.158  7054  7054 V BluetoothPbapReceiver: ***********state = 13
08-26 21:53:41.161  7054  7054 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-26 21:53:41.163  7054  7054 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-26 21:53:41.163  7054  7054 V BluetoothPbapService: state: 13
08-26 21:53:41.163  7054  7054 V BluetoothPbapService: Pbap Service closeService in
08-26 21:53:41.164  7054  7054 V BluetoothPbapService: successfully stopped pbap service
08-26 21:53:41.164  7054  7054 V BluetoothPbapService: Pbap Service closeService out
08-26 21:53:41.165  7054  7054 V BluetoothPbapService: Pbap Service onDestroy
08-26 21:53:41.165  7054  7054 V BluetoothPbapService: Pbap Service closeService in
08-26 21:53:41.165  7054  7054 V BluetoothPbapService: Pbap Service closeService out
08-26 21:53:41.165  7054  7054 D LGBluetoothPbapAdapter: [BTUI] cleanup
,08-26 21:53:41.165  6917  6917 D DockEventReceiver: finishStartingService: stopping service
08-26 21:53:41.167  6917  6917 D BluetoothPbap: Proxy object disconnected
08-26 21:53:41.167  6917  6917 D PbapServerProfile: Bluetooth service disconnected
08-26 21:53:41.169  2205  2205 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-26 21:53:41.181  6917  6917 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-26 21:53:41.187  6917  6917 D BluetoothPermissionRequest: onReceive
08-26 21:53:41.187  6917  6917 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-26 21:53:41.193  6917  6917 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-26 21:53:41.197  7054  7054 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-26 21:53:41.197  7054  7054 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
,08-26 21:53:41.198  7054  7054 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-26 21:53:41.202  7734  7734 I UEI.SmartControl: Supports setup maps: true
08-26 21:53:41.202  7054  7054 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-26 21:53:41.203  7054  7054 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-26 21:53:41.204  7054  7054 V BluetoothFtpService: Ftp Service onStartCommand
08-26 21:53:41.204  7054  7054 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-26 21:53:41.204  7054  7054 V BluetoothFtpService: Ftp Service closeService
08-26 21:53:41.204  7054  7054 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-26 21:53:41.205  7054  7054 V BluetoothFtpService: successfully stopped ftp service
08-26 21:53:41.205  7054  7054 V BluetoothFtpService: Ftp Service onDestroy
08-26 21:53:41.205  7054  7054 V BluetoothFtpService: Ftp Service closeService
08-26 21:53:41.205  7734  7734 D UEI.SmartControl: QS start statue = true Error code = 0
08-26 21:53:41.205  7734  7734 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-26 21:53:41.205  7734  7734 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-26 21:53:41.205  7734  7734 I UEI.SmartControl: ### init IR Blaster...
08-26 21:53:41.208  7054  7054 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-26 21:53:41.208  7054  7054 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-26 21:53:41.208  7054  7054 V BluetoothSapReceiver: SapReceiver onReceive 
08-26 21:53:41.208  7054  7054 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 21:53:41.208  7054  7054 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-26 21:53:41.208  7054  7054 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-26 21:53:41.209  7054  7054 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-26 21:53:41.209  7054  7054 V BluetoothSapService: state: 13
08-26 21:53:41.209  7054  7054 V BluetoothSapService: Stopping SAP server process
,08-26 21:53:41.213  7054  7054 V BluetoothSapService: Sap Service closeSapService in
08-26 21:53:41.213  7054  7054 V BluetoothSapService: Close listen Socket : 
08-26 21:53:41.213  7054  7054 V BluetoothSapService: Close rfcomm Socket : 
08-26 21:53:41.213  7054  7054 V BluetoothSapService: Close sapd  Socket : 
08-26 21:53:41.214  7054  7054 V BluetoothSapService: Sap Service closeSapService out
08-26 21:53:41.214  7054  7054 V BluetoothSapService: Sap Service onDestroy
08-26 21:53:41.214  7054  7054 V BluetoothSapService: Sap Service closeSapService in
08-26 21:53:41.214  7054  7054 V BluetoothSapService: Close listen Socket : 
08-26 21:53:41.214  7054  7054 V BluetoothSapService: Close rfcomm Socket : 
08-26 21:53:41.214  7054  7054 V BluetoothSapService: Close sapd  Socket : 
08-26 21:53:41.215  7734  7734 D serial_port: Configuring serial port
08-26 21:53:41.217  7734  7734 E UEI.SmartControl: UEIBLaster setting for 616
08-26 21:53:41.217  7734  7734 I UEI.SmartControl: Setting serial record hearder size = 2
08-26 21:53:41.218  7734  7734 I UEI.SmartControl: configuring settings for MAXQ616
08-26 21:53:41.219  7734  7734 I UEI.SmartControl: Get version...
08-26 21:53:41.219  7054  7054 V BluetoothSapService: Sap Service closeSapService out
08-26 21:53:41.236  7734  7784 D UEI.SmartControl: serial port data available: 21
,08-26 21:53:41.265  7734  7734 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-26 21:53:41.265  7734  7734 I UEI.SmartControl: IR Blaster version: 256702256704300002
,08-26 21:53:41.266  7734  7734 I UEI.SmartControl: QS saving settings...
08-26 21:53:41.267  7734  7734 D UEI.SmartControl: IR Blaster version: 25672567
,08-26 21:53:41.284  7734  7784 D UEI.SmartControl: serial port data available: 4
,08-26 21:53:41.326  7734  7734 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-26 21:53:41.324  7734  7788 I UEI.SmartControl: Device manager: loading config....
08-26 21:53:41.329  7734  7788 D UEI.SmartControl: ----------- loading internal config...
,08-26 21:53:41.333  7734  7734 E UEI.SmartControl: Services init done
08-26 21:53:41.334  7734  7734 D UEI.SmartControl: QS Service init finished
08-26 21:53:41.335  7734  7734 D UEI.SmartControl: QS Service version name: 2.1.91
08-26 21:53:41.335  7734  7734 D UEI.SmartControl: QS Service version code: 201091
08-26 21:53:41.336  7734  7734 D UEI.SmartControl: Service requested: Control
08-26 21:53:41.344  7734  7788 E UEI.SmartControl: Loading SETTINGS...
,08-26 21:53:41.347  7734  7734 D UEI.SmartControl: Request IControl service: devices are loaded...
08-26 21:53:41.349  1034  1576 I ActivityManager: Killing 6981:com.lge.qremote/u0a112 (adj 15): empty #17
08-26 21:53:41.362  7734  7788 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,08-26 21:53:41.380  7734  7787 I UEI.SmartControl: Notify AllClients services are ready: 0
,08-26 21:53:41.381  7734  7787 D UEI.SmartControl: -----service ready thread exits
,08-26 21:53:41.392  1034  1049 W libprocessgroup: failed to open /acct/uid_10112/pid_6981/cgroup.procs: No such file or directory
08-26 21:53:41.393  7734  7734 D UEI.SmartControl: Internal service binding...
,08-26 21:53:42.052  7054  7641 I bt_lpm  : LPM is already off!!!
,08-26 21:53:42.058  7054  7639 W bt-btif : ag scb idx 1 not allocated
,08-26 21:53:42.058  7054  7639 E bt-btif : BTA AG is already disabled, ignoring ...
08-26 21:53:42.058  7054  7639 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-26 21:53:42.058  7054  7639 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 21:53:42.058  7054  7639 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-26 21:53:42.058  7054  7639 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 21:53:42.058  7054  7639 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-26 21:53:42.058  7054  7639 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 21:53:42.060  7054  7574 D bt_hci_bdroid: cleanup
08-26 21:53:42.062  7054  7639 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-26 21:53:42.063  7054  7685 I bt_userial_mct: exiting userial_read_thread
08-26 21:53:42.063  7054  7685 D bt_userial_mct: Leaving userial_evt_read_thread()
08-26 21:53:42.064  7054  7639 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 21:53:42.064  7054  7639 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-26 21:53:42.064  7054  7639 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 21:53:42.064  7054  7639 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-26 21:53:42.064  7054  7639 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 21:53:42.064  7054  7639 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-26 21:53:42.064  7054  7639 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 21:53:42.064  7054  7639 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-26 21:53:42.064  7054  7639 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 21:53:42.064  7054  7639 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-26 21:53:42.064  7054  7639 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 21:53:42.065  7054  7639 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-26 21:53:42.066  7054  7574 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-26 21:53:42.067  7054  7641 I bt_vendor: hw_epilog_process
08-26 21:53:42.071  7054  7574 D bt_hci_bdroid: cleanup Finalizing cleanup
08-26 21:53:42.071  7054  7574 D bt_userial_mct: userial_close
08-26 21:53:42.071  7054  7574 E bt_userial_mct: pthread_join() FAILED result:3
08-26 21:53:42.071  7054  7574 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,08-26 21:53:42.082  7054  7574 D bt_hci_bdroid: set_power 0
08-26 21:53:42.082  7054  7574 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-26 21:53:42.083  7054  7574 I bt_vendor: bluetooth satus is on
08-26 21:53:42.083  7054  7574 I bt_vendor: bt-vendor : resetting BT status
08-26 21:53:42.084  7054  7574 I bt_vendor: Starting hciattach daemon
08-26 21:53:42.084  7054  7574 I bt_vendor: try to set false
08-26 21:53:42.086  7054  7574 I bt_vendor: Starting hciattach daemon
08-26 21:53:42.086  7054  7574 I bt_vendor: try to set false
,08-26 21:53:42.088  7054  7574 I bt_vendor: cleanup
08-26 21:53:42.089  7054  7639 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-26 21:53:42.090  7054  7574 I GKI_LINUX: GKI_exit_task 0 done
08-26 21:53:42.090  7054  7574 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-26 21:53:42.092  7054  7570 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-26 21:53:42.097  7054  7054 D HeadsetService: Received stop request...Stopping profile...
08-26 21:53:42.100  7054  7054 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-26 21:53:42.100  7054  7054 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-26 21:53:42.100  7054  7054 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1bb02614
,08-26 21:53:42.103  7054  7593 D HeadsetStateMachine: Exit Disconnected: -1
08-26 21:53:42.105  1853  1853 D BluetoothHeadset: Proxy object disconnected
08-26 21:53:42.105  1853  1853 D BluetoothHeadset: Proxy object disconnected
08-26 21:53:42.105  1853  1853 D BluetoothHeadset: Proxy object disconnected
08-26 21:53:42.106  1034  1034 D BluetoothHeadset: Proxy object disconnected
08-26 21:53:42.106  1034  1034 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-26 21:53:42.108  7054  7054 D A2dpService: Received stop request...Stopping profile...
08-26 21:53:42.108  7054  7631 D A2dpStateMachine: Exit Disconnected: -1
08-26 21:53:42.111  7054  7570 D BluetoothAdapterState: Stopping profile services that were post enabled
08-26 21:53:42.112  7054  7054 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
,08-26 21:53:42.115  7054  7054 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-26 21:53:42.115  7054  7054 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-26 21:53:42.115  7054  7054 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1bb02614
08-26 21:53:42.118  1034  1034 D BluetoothA2dp: Proxy object disconnected
08-26 21:53:42.118  1034  1034 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-26 21:53:42.119  7054  7054 D HidService: Received stop request...Stopping profile...
08-26 21:53:42.119  7054  7054 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1bb02614
08-26 21:53:42.122  7054  7054 D HealthService: Received stop request...Stopping profile...
08-26 21:53:42.124  7054  7054 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1bb02614
,08-26 21:53:42.128  7054  7054 D PanService: Received stop request...Stopping profile...
08-26 21:53:42.129  7054  7054 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1bb02614
08-26 21:53:42.130  7054  7054 D HeadsetStateMachine: Unbinding service...
08-26 21:53:42.132  7054  7054 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-26 21:53:42.132  7054  7054 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-26 21:53:42.132  7054  7054 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-26 21:53:42.132  7054  7054 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-26 21:53:42.133  7054  7054 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-26 21:53:42.133  7054  7054 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-26 21:53:42.133  7054  7054 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-26 21:53:42.133  7054  7054 D BtGatt.DebugUtils: handleDebugAction() action=null
08-26 21:53:42.134  7054  7054 D BtGatt.GattService: Received stop request...Stopping profile...
08-26 21:53:42.134  7054  7054 D BtGatt.GattService: stop()
08-26 21:53:42.134  7054  7054 D BtGatt.AdvertiseManager: advertise clients cleared
08-26 21:53:42.137  7054  7054 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1bb02614
,08-26 21:53:42.140  7054  7054 D BluetoothMapService: Received stop request...Stopping profile...
,08-26 21:53:42.140  7054  7054 D BluetoothMapService: stop()
08-26 21:53:42.141  7054  7054 D BluetoothMapEmailAppObserver: deinitObservers()
08-26 21:53:42.141  7054  7054 D BluetoothMapEmailAppObserver: removeReceiver()
08-26 21:53:42.142  7054  7054 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1bb02614
08-26 21:53:42.143  7054  7054 I BluetoothA2dpServiceJni: cleanupNative
08-26 21:53:42.143  7054  7632 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-26 21:53:42.144  7054  7054 I GKI_LINUX: GKI_exit_task 2 done
08-26 21:53:42.144  7054  7054 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-26 21:53:42.144  7054  7054 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-26 21:53:42.144  7054  7054 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-26 21:53:42.144  7054  7054 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-26 21:53:42.145  7054  7054 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-26 21:53:42.145  7054  7054 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-26 21:53:42.145  7054  7054 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-26 21:53:42.145  7054  7054 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-26 21:53:42.150  7054  7054 V BluetoothMapService: Handler(): got msg=4
08-26 21:53:42.151  7054  7054 D BluetoothMapService: MAP Service closeService in
08-26 21:53:42.151  7054  7054 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-26 21:53:42.151  7054  7054 V BluetoothMapService: MAP Service closeService out
,08-26 21:53:42.156  7054  7570 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-26 21:53:42.156  7054  7570 D BluetoothAdapterProperties: Setting state to 10
08-26 21:53:42.156  7054  7570 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-26 21:53:42.157  7054  7054 D BluetoothMapService: cleanup()
08-26 21:53:42.157  7054  7054 D BluetoothMapService: MAP Service closeService in
08-26 21:53:42.157  7054  7054 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-26 21:53:42.157  7054  7054 V BluetoothMapService: MAP Service closeService out
08-26 21:53:42.158  1034  1105 D BluetoothManagerService: Message: 60
08-26 21:53:42.158  1034  1105 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-26 21:53:42.158  1034  1105 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
08-26 21:53:42.159  7054  7570 I BluetoothAdapterState: Entering OffState
08-26 21:53:42.159  1853  2419 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 21:53:42.160  1853  2717 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 21:53:42.160  6917  7041 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-26 21:53:42.161  6917  7041 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 21:53:42.162  1853  1869 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 21:53:42.163  6917  7041 D BluetoothPbap: onBluetoothStateChange: up=false
08-26 21:53:42.163  6917  7041 D BluetoothA2dp: onBluetoothStateChange: up=false
08-26 21:53:42.164  6917  7041 D BluetoothPan: onBluetoothStateChange on: false
08-26 21:53:42.165  1034  1105 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-26 21:53:42.168  6917  7041 D BluetoothMap: onBluetoothStateChange: up=false
08-26 21:53:42.168  1034  1105 D BluetoothA2dp: onBluetoothStateChange: up=false
08-26 21:53:42.169  1034  1105 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-26 21:53:42.169  1034  1105 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-26 21:53:42.171  1034  1105 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-26 21:53:42.171  1034  1105 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-26 21:53:42.171  1034  1105 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@24c726bb mBinding = false
08-26 21:53:42.172  1034  1105 D BluetoothManagerService: Sending unbind request.
08-26 21:53:42.176  7054  7574 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-26 21:53:42.179  7054  7054 I GKI_LINUX: GKI_exit_task 1 done
,08-26 21:53:42.179  7054  7054 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
,08-26 21:53:42.180  7054  7054 I BluetoothServiceJni: cleanupNative: return from cleanup
08-26 21:53:42.180  7054  7054 I art     : --- WEIRD: removing null entry 248
08-26 21:53:42.180  7054  7054 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
08-26 21:53:42.181  7054  7054 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-26 21:53:42.181  7054  7054 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-26 21:53:42.183  1034  1105 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-26 21:53:42.185  7054  7054 I art     : System.exit called, status: 0
08-26 21:53:42.185  7054  7054 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-26 21:53:42.209  1942  1942 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-26 21:53:42.218  1942  2102 D LGBluetoothAPIService: Message: 2
08-26 21:53:42.218  1942  2102 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@2a8d0af7 mBinding = false
08-26 21:53:42.218  1942  2102 D LGBluetoothAPIService: Sending unbind request.
08-26 21:53:42.220  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-26 21:53:42.221  6917  6917 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-26 21:53:42.221  6917  6917 D LGBluetoothEventManager: [BTUI] clear device connection state
08-26 21:53:42.223   319  1383 V AudioFlinger: 7054 died, releasing its sessions
08-26 21:53:42.223   319  1383 V AudioFlinger:  pid 1853 @ 0
08-26 21:53:42.223   319  1383 V AudioFlinger:  pid 3203 @ 1
08-26 21:53:42.223   319  1383 V AudioFlinger:  pid 3203 @ 2
08-26 21:53:42.223  6674  6674 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 21:53:42.224  6674  6674 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 21:53:42.224  6917  6917 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-26 21:53:42.228  1034  1921 W ActivityManager: Exception when unbinding service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer
08-26 21:53:42.228  1034  1921 W ActivityManager: android.os.DeadObjectException
08-26 21:53:42.228  1034  1921 W ActivityManager: 	at android.os.BinderProxy.transactNative(Native Method)
08-26 21:53:42.228  1034  1921 W ActivityManager: 	at android.os.BinderProxy.transact(Binder.java:496)
08-26 21:53:42.228  1034  1921 W ActivityManager: 	at android.app.ApplicationThreadProxy.scheduleUnbindService(ApplicationThreadNative.java:917)
08-26 21:53:42.228  1034  1921 W ActivityManager: 	at com.android.server.am.ActiveServices.removeConnectionLocked(ActiveServices.java:1776)
08-26 21:53:42.228  1034  1921 W ActivityManager: 	at com.android.server.am.ActiveServices.unbindServiceLocked(ActiveServices.java:901)
08-26 21:53:42.228  1034  1921 W ActivityManager: 	at com.android.server.am.ActivityManagerService.unbindService(ActivityManagerService.java:15417)
08-26 21:53:42.228  1034  1921 W ActivityManager: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:963)
08-26 21:53:42.228  1034  1921 W ActivityManager: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2560)
08-26 21:53:42.228  1034  1921 W ActivityManager: 	at com.android.server.am.ActivityManagerServiceEx.onTransact(ActivityManagerServiceEx.java:421)
08-26 21:53:42.228  1034  1921 W ActivityManager: 	at android.os.Binder.execTransact(Binder.java:446)
08-26 21:53:42.229  1603  1603 D BluetoothAdapter: 127316959: getState() :  mService = null. Returning STATE_OFF
08-26 21:53:42.229  1603  1603 D BluetoothAdapter: 127316959: getState() :  mService = null. Returning STATE_OFF
08-26 21:53:42.230  6917  6917 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-26 21:53:42.281  1034  1576 I ActivityManager: Process com.android.bluetooth (pid 7054) has died
,08-26 21:53:42.282  1034  1576 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 4000ms
08-26 21:53:42.347  1034  2006 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=7821 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
08-26 21:53:42.349  6917  6917 D DockEventReceiver: finishStartingService: stopping service
,08-26 21:53:42.454  7821  7821 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-26 21:53:42.455  7821  7821 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-26 21:53:42.455  7821  7821 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
,08-26 21:53:42.456  7821  7821 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-26 21:53:42.477  7821  7821 D BluetoothAdapterApp: Loading JNI Library
,08-26 21:53:42.535  7821  7821 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@1a40e37c Instance Count = 1
,08-26 21:53:42.544  7821  7821 D BluetoothAdapterApp: onCreate
08-26 21:53:42.571  7821  7821 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-26 21:53:42.571  7821  7821 D ProfileConfigQcom: Adding HeadsetService
,08-26 21:53:42.571  7821  7821 D ProfileConfigQcom: [BTUI] A2dpService is supported
,08-26 21:53:42.572  7821  7821 D ProfileConfigQcom: Adding A2dpService
08-26 21:53:42.572  7821  7821 D ProfileConfigQcom: [BTUI] HidService is supported
08-26 21:53:42.572  7821  7821 D ProfileConfigQcom: Adding HidService
08-26 21:53:42.572  7821  7821 D ProfileConfigQcom: [BTUI] HealthService is supported
08-26 21:53:42.573  7821  7821 D ProfileConfigQcom: Adding HealthService
08-26 21:53:42.573  7821  7821 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-26 21:53:42.574  7821  7821 D ProfileConfigQcom: [BTUI] PanService is supported
08-26 21:53:42.574  7821  7821 D ProfileConfigQcom: Adding PanService
08-26 21:53:42.574  7821  7821 D ProfileConfigQcom: [BTUI] GattService is supported
08-26 21:53:42.574  7821  7821 D ProfileConfigQcom: Adding GattService
08-26 21:53:42.575  7821  7821 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-26 21:53:42.575  7821  7821 D ProfileConfigQcom: Adding BluetoothMapService
08-26 21:53:42.575  7821  7821 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-26 21:53:42.576  7821  7821 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-26 21:53:42.577  7821  7821 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 21:53:42.578  7821  7821 V BluetoothPbapReceiver: ***********state = 10
08-26 21:53:42.580  7821  7821 V LGMDMManagerInternal: Create singleton instance
08-26 21:53:42.698  2205  2205 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-26 21:53:42.710  6917  6917 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
,08-26 21:53:42.720  6917  6917 D BluetoothPermissionRequest: onReceive
08-26 21:53:42.723  6917  6917 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-26 21:53:42.723  6917  6917 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-26 21:53:42.725  6917  6917 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-26 21:53:42.731  7821  7821 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-26 21:53:42.736  7821  7821 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-26 21:53:42.739  7821  7821 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-26 21:53:42.740  7821  7821 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-26 21:53:42.740  7821  7821 V BluetoothSapReceiver: SapReceiver onReceive 
08-26 21:53:42.741  7821  7821 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 21:53:42.741  7821  7821 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
,08-26 21:53:42.751  7646  7646 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
08-26 21:53:42.756  1034  1921 I ActivityManager: Killing 6934:com.lge.sync/1000 (adj 15): empty #17
,08-26 21:53:42.773  1034  1542 D WifiService: Client connection lost with reason: 4
,08-26 21:53:42.785  1034  1887 W libprocessgroup: failed to open /acct/uid_1000/pid_6934/cgroup.procs: No such file or directory
,08-26 21:53:44.105  6674  6764 D io.jxcore.node.ConnectivityMonitor: stop
08-26 21:53:44.105  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 21:53:44.131  1603  1603 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,08-26 21:53:44.163  1034  1436 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-26 21:53:44.225  1034  1034 D administrator: Handling package changes for user 0
08-26 21:53:44.226  1034  1091 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7858 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-26 21:53:44.233  1603  1603 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
08-26 21:53:44.233  1603  1603 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
08-26 21:53:44.237  2034  2034 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
08-26 21:53:44.266  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-26 21:53:44.308  7858  7858 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-26 21:53:44.336  1034  1034 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
08-26 21:53:44.336  1034  1034 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-26 21:53:44.386  1034  1090 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-26 21:53:44.388  7858  7858 D LgDataFeature: LgDataFeature() Constructor: none
08-26 21:53:44.389  7858  7858 D LgDataFeature: LgDataFeature() Constructor Done, null
08-26 21:53:44.393  1034  1090 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,08-26 21:53:44.400  2481  2481 V GmsNetworkLocationProvi: DISABLE
08-26 21:53:44.400  2034  2034 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,08-26 21:53:44.429  1034  1090 D LocationProviderProxy: applying state to connected service
,08-26 21:53:44.431  2481  2481 E GCoreFlp: Bound FusedProviderService with LocationManager
,08-26 21:53:44.503  7858  7895 I Babel   : MmsConfig: mnc/mcc: 0/0
,08-26 21:53:44.503  7858  7895 I Babel   : MmsConfig.loadMmsSettings
08-26 21:53:44.506  7858  7895 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-26 21:53:44.507  7858  7895 I Babel   : MmsConfig.loadFromDatabase
,08-26 21:53:44.531  7858  7893 W AudioCapabilities: Unsupported mime audio/evrc
,08-26 21:53:44.532  7858  7893 W AudioCapabilities: Unsupported mime audio/qcelp
08-26 21:53:44.533  7858  7895 E Babel   : canonicalizeMccMnc: invalid mccmnc 
08-26 21:53:44.534  7858  7895 I Babel   : MmsConfig.loadFromResources
08-26 21:53:44.535  7858  7893 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
08-26 21:53:44.537  7858  7895 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
08-26 21:53:44.538  7858  7895 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-26 21:53:44.545  7858  7858 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 21:53:44.546  7858  7893 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
,08-26 21:53:44.547  7858  7893 W AudioCapabilities: Unsupported mime audio/qcelp
,08-26 21:53:44.548  7858  7893 W AudioCapabilities: Unsupported mime audio/evrc
08-26 21:53:44.558  7858  7893 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-26 21:53:44.560  7858  7893 W VideoCapabilities: Unsupported mime video/divx
08-26 21:53:44.562  7858  7893 W VideoCapabilities: Unsupported mime video/divx311
08-26 21:53:44.563  7858  7893 W VideoCapabilities: Unsupported mime video/divx4
08-26 21:53:44.576  7858  7893 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,08-26 21:53:44.585  1817  7897 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
08-26 21:53:44.585  1817  7897 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
,08-26 21:53:44.591  7154  7154 I AppUp4:CustModeStarterReceiver: onReceive
,08-26 21:53:44.594  7154  7154 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@b1b8426
08-26 21:53:44.594  7154  7154 D AppUp4:CustFacade: isCustomizationCompleted : false
08-26 21:53:44.594  7154  7154 D AppUp4:CustFacade: isPhone : true
08-26 21:53:44.594  7154  7154 D AppUp4:CustModeStarterReceiver: begin check event
08-26 21:53:44.595  7154  7154 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
08-26 21:53:44.598  1817  5197 I Icing   : updateResources: need to parse e{com.google.android.gms}
08-26 21:53:44.613  7858  7893 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-26 21:53:44.618  7858  7893 W AudioCapabilities: Unsupported mime audio/eac3
08-26 21:53:44.619  7858  7893 W AudioCapabilities: Unsupported mime audio/ac3
08-26 21:53:44.620  7858  7893 W AudioCapabilities: Unsupported mime audio/g726
08-26 21:53:44.622  7858  7893 W AudioCapabilities: Unsupported mime audio/wma-voice
08-26 21:53:44.623  7858  7893 W AudioCapabilities: Unsupported mime audio/x-ms-wma
08-26 21:53:44.623  7858  7893 W AudioCapabilities: Unsupported mime audio/adpcm
08-26 21:53:44.626  7858  7893 W VideoCapabilities: Unsupported mime video/theora
,08-26 21:53:44.628  7858  7893 W VideoCapabilities: Unsupported mime video/mjpg
08-26 21:53:44.641  1034  1049 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7900 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,08-26 21:53:44.675  1034  2006 I ActivityManager: Killing 7188:com.lge.email/u0a23 (adj 15): empty #17
08-26 21:53:44.689  7900  7900 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-26 21:53:44.689  7900  7900 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-26 21:53:44.689  7900  7900 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-26 21:53:44.691  7900  7900 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
08-26 21:53:44.691  7900  7900 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-26 21:53:44.805  1034  1576 W libprocessgroup: failed to open /acct/uid_10023/pid_7188/cgroup.procs: No such file or directory
,08-26 21:53:44.855  7900  7900 I SystemConfig: BUILD Country: EU
,08-26 21:53:44.856  7900  7900 I SystemConfig: BUILD Operator: OPEN
08-26 21:53:44.909  1034  1959 I ActivityManager: Killing 7024:com.lge.formmanager/u0a26 (adj 15): empty #17
,08-26 21:53:44.999  1034  1050 W libprocessgroup: failed to open /acct/uid_10026/pid_7024/cgroup.procs: No such file or directory
,08-26 21:53:45.050  1034  1959 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7924 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
08-26 21:53:45.055  7900  7919 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
08-26 21:53:45.055  7900  7919 I SystemConfig: existFile = false
08-26 21:53:45.055  7900  7919 I SystemConfig: canReadFile = false
08-26 21:53:45.055  7900  7919 I SystemConfig: systemFeature RCS result false
08-26 21:53:45.056  7900  7919 D SystemConfig: refreshRcsSupport() :false
,08-26 21:53:45.105  7924  7924 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-26 21:53:45.106  7924  7924 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-26 21:53:45.106  7924  7924 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-26 21:53:45.106  7924  7924 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-26 21:53:45.202  1034  1543 D ConnectivityService: Failed to find a new network - expiring NetTransition Wakelock
,08-26 21:53:45.213  7924  7924 I AppConfig: Total System Memory = 2995761152
,08-26 21:53:45.224  7924  7924 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
,08-26 21:53:45.342  1034  1975 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7946 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-26 21:53:45.346  1034  1975 I ActivityManager: Killing 6448:com.wsandroid.suite.lge/1000 (adj 15): empty #17
08-26 21:53:45.403  1034  1049 W libprocessgroup: failed to open /acct/uid_1000/pid_6448/cgroup.procs: No such file or directory
,08-26 21:53:45.624  7946  7946 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,08-26 21:53:45.687  7946  7946 D LgDataFeature: LgDataFeature() Constructor: none
08-26 21:53:45.687  7946  7946 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-26 21:53:45.738  7946  7946 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,08-26 21:53:45.764  7946  7946 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-26 21:53:45.766  7946  7946 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
08-26 21:53:45.782  7946  7946 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-26 21:53:45.782  7946  7946 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,08-26 21:53:45.801  1034  1995 I ActivityManager: Killing 7224:com.google.android.setupwizard/u0a46 (adj 15): empty #17
,08-26 21:53:45.909  1034  1921 W libprocessgroup: failed to open /acct/uid_10046/pid_7224/cgroup.procs: No such file or directory
,08-26 21:53:45.917  2859  4199 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
08-26 21:53:45.921  2859  4199 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@39dd085b on behalf of 7946
08-26 21:53:45.939  5021  7988 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,08-26 21:53:46.026  1034  2033 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7992 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,08-26 21:53:46.056  7946  7946 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,08-26 21:53:46.093  7946  7946 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,08-26 21:53:46.123  7992  7992 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,08-26 21:53:46.150  7992  7992 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
,08-26 21:53:46.151  7992  7992 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
08-26 21:53:46.151  7992  7992 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
08-26 21:53:46.151  7992  7992 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
08-26 21:53:46.151  7992  7992 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
08-26 21:53:46.151  7992  7992 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
,08-26 21:53:46.176  1034  1576 I ActivityManager: Killing 7246:com.android.chrome/u0a57 (adj 15): empty #17
,08-26 21:53:46.285  1034  1940 W libprocessgroup: failed to open /acct/uid_10057/pid_7246/cgroup.procs: No such file or directory
,08-26 21:53:46.324  7734  7789 D UEI.SmartControl: Internal timer expired: 1
,08-26 21:53:46.324  7734  7789 D UEI.SmartControl: unbind internal service
,08-26 21:53:46.332  7734  7734 D UEI.SmartControl: Service.onUnbind: IControl
08-26 21:53:46.333  7734  7734 D UEI.SmartControl: Service.onDestroy
,08-26 21:53:46.333  7734  7734 D UEI.SmartControl: Lock is in USE false
08-26 21:53:46.333  7734  7734 D UEI.SmartControl: unbind internal service
,08-26 21:53:46.336  7734  7734 D serial_port: close(fd = 25)
08-26 21:53:46.340  7734  7734 I UEI.SmartControl: Serial port is closed.
08-26 21:53:46.340  7734  7734 I UEI.SmartControl: Serial port is closed.
08-26 21:53:46.341  7734  7734 D UEI.SmartControl: Blaster closed
08-26 21:53:46.341  7734  7734 D UEI.SmartControl: Shut down QS...
08-26 21:53:46.344  7734  7734 D UEI.SmartControl: Stopping QS lib
,08-26 21:53:46.346  7734  7734 D UEI.SmartControl: QS lib stop result = true
,08-26 21:53:46.346  7734  7734 D UEI.SmartControl: Stopped QS lib
08-26 21:53:46.347  7734  7734 D UEI.SmartControl: Stopped file observer...
,08-26 21:53:46.348  7734  7734 D UEI.SmartControl: QS shutdown complete
,08-26 21:53:46.505  1034  1576 V SIM_STK : Menu title from STK is T-Mobile
,08-26 21:53:46.538  5021  7988 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 598 ms] updated apps [took 598 ms] 
,08-26 21:53:47.233  6674  6764 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 21:53:47.233  6674  6764 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@25a921c8 added. We now have 6 listener(s)
,08-26 21:53:47.233  6674  6764 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 21:53:47.245  6674  6764 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 21:53:47.245  6674  6764 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@39fe8261 added. We now have 7 listener(s)
08-26 21:53:47.245  6674  6764 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 21:53:47.246  6674  6764 I System.out: IsBluetoothEnabled
08-26 21:53:47.247  1034  1921 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 21:53:47.247  1034  1921 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
08-26 21:53:47.248  1034  1105 D BluetoothManagerService: Message: 2
08-26 21:53:47.253  6674  6764 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 21:53:47.255  1034  1049 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-26 21:53:47.257  1034  1049 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
08-26 21:53:47.268  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-26 21:53:47.269  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-26 21:53:47.269  1034  1034 D Ulp_jni : JNI:system_update. Event-4
,08-26 21:53:47.272  1034  1105 D BluetoothManagerService: Message: 1
08-26 21:53:47.272  1034  1105 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-26 21:53:47.299  1034  1105 D BluetoothManagerService: Message: 20
08-26 21:53:47.300  1034  1105 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2787f158:true
,08-26 21:53:47.304  7821  7821 D BluetoothAdapterState: make
08-26 21:53:47.309  7821  7821 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-26 21:53:47.309  7821  7821 I bluedroid-qcom: init
08-26 21:53:47.310  7821  8028 I BluetoothAdapterState: Entering OffState
08-26 21:53:47.311  7821  7821 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-26 21:53:47.311  7821  7821 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-26 21:53:47.311  7821  7821 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-26 21:53:47.311  7821  7821 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-26 21:53:47.311  7821  7821 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-26 21:53:47.313  7821  7821 I bluedroid-qcom: get_profile_interface socket
08-26 21:53:47.313  7821  7821 I bluedroid-qcom: get_profile_interface map_client
,08-26 21:53:47.317  7821  8032 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-26 21:53:47.309  8031  8031 W bdaddr_loader: type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 21:53:47.309  8031  8031 W bdaddr_loader: type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 21:53:47.326  1034  1034 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
,08-26 21:53:47.328  1034  1105 D BluetoothManagerService: Message: 40
08-26 21:53:47.328  1034  1105 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-26 21:53:47.329  7821  7838 I bluedroid-qcom: config_hci_snoop_log
08-26 21:53:47.335  8031  8031 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-26 21:53:47.335  8031  8031 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-26 21:53:47.335  8031  8031 I LGFTMITEM: [GET_FTM][id=8], offset=16384
08-26 21:53:47.336  1034  1105 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-26 21:53:47.336  1034  1105 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-26 21:53:47.340  7821  8032 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-26 21:53:47.344  8031  8031 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-26 21:53:47.346  1034  1034 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-26 21:53:47.346  1034  1034 D BluetoothManagerService: Stored Bluetooth name: G3
08-26 21:53:47.346  7821  8032 D BluetoothAdapterProperties: Name is: G3
08-26 21:53:47.350  8031  8031 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-26 21:53:47.350  8031  8031 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-26 21:53:47.355  7821  8028 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-26 21:53:47.355  7821  8028 D BluetoothAdapterProperties: Setting state to 11
08-26 21:53:47.355  7821  8028 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
,08-26 21:53:47.359  7821  8028 I LGBluetoothServiceJni: classInitNative: succeeds
08-26 21:53:47.362  1034  1105 D BluetoothManagerService: Message: 60
08-26 21:53:47.362  1034  1105 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-26 21:53:47.362  1034  1105 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-26 21:53:47.368  1942  1942 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-26 21:53:47.371  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-26 21:53:47.373  6674  6674 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 21:53:47.378  6917  6917 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-26 21:53:47.380  7821  8028 D BluetoothBondStateMachine: make
,08-26 21:53:47.388  7821  7821 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-26 21:53:47.388  7821  7821 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 21:53:47.388  7821  7821 V BluetoothPbapReceiver: ***********state = 11
08-26 21:53:47.407  2205  2205 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-26 21:53:47.410  7821  8028 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1bb02614
08-26 21:53:47.410  7821  8028 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-26 21:53:47.410  7821  8028 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1bb02614
08-26 21:53:47.410  7821  8028 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-26 21:53:47.412  7821  8033 I BluetoothBondStateMachine: StableState(): Entering Off State
08-26 21:53:47.413  7821  8028 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-26 21:53:47.418  7821  8028 E BluetoothAdapterService: File transfer profiles supported!!
08-26 21:53:47.424  7821  8028 E BluetoothAdapterService: File transfer profiles supported!!
,08-26 21:53:47.427  7821  7821 D HeadsetService: Received start request. Starting profile...
08-26 21:53:47.428  7821  7821 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-26 21:53:47.428  7821  7821 D LGBluetoothHfpAdapter: Version 1.6
08-26 21:53:47.430  6917  6917 D BluetoothPermissionRequest: onReceive
08-26 21:53:47.432  7821  7821 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-26 21:53:47.433  7821  7821 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-26 21:53:47.434  7821  7821 D HeadsetStateMachine: make
08-26 21:53:47.437  7821  8028 E BluetoothAdapterService: File transfer profiles supported!!
08-26 21:53:47.437  6917  6917 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-26 21:53:47.447  7821  8028 E BluetoothAdapterService: File transfer profiles supported!!
08-26 21:53:47.451  7821  8028 E BluetoothAdapterService: File transfer profiles supported!!
,08-26 21:53:47.455  7821  8028 E BluetoothAdapterService: File transfer profiles supported!!
08-26 21:53:47.459  7821  8028 E BluetoothAdapterService: File transfer profiles supported!!
08-26 21:53:47.469  7821  8028 V LGMDMManager: Create singleton instance
,08-26 21:53:47.469  7821  7821 D LgDataFeature: LgDataFeature() Constructor: none
08-26 21:53:47.470  7821  7821 D LgDataFeature: LgDataFeature() Constructor Done, null
08-26 21:53:47.473  7821  8028 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-26 21:53:47.474  7821  7821 D HeadsetStateMachine: max_hf_connections = 1
08-26 21:53:47.474  7821  7821 I bluedroid-qcom: get_profile_interface handsfree
08-26 21:53:47.476  7821  7821 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-26 21:53:47.477   319  2203 V AudioPolicyService: registerClient() client 0xb57ecd00, uid 1002
08-26 21:53:47.477   319   319 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-26 21:53:47.477   319   319 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-26 21:53:47.477   319   319 V AudioPolicyManagerEx: getOutput() returns output 2
08-26 21:53:47.477  7821  7821 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-26 21:53:47.478   319  2204 V AudioFlinger: registerClient() client 0xb55814f0, pid 7821
08-26 21:53:47.478   319  1379 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-26 21:53:47.478   319  1379 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-26 21:53:47.478  1603  1622 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-26 21:53:47.478  1603  1622 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-26 21:53:47.478  7821  7821 V ToneGenerator: Create Track: 0xb4928080
08-26 21:53:47.478  7821  7821 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-26 21:53:47.478  7821  7821 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-26 21:53:47.479  7821  7838 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-26 21:53:47.479  7821  7838 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-26 21:53:47.479   319  2203 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-26 21:53:47.479   319  2203 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-26 21:53:47.479   319  2203 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-26 21:53:47.479   319  2203 V AudioPolicyManagerEx: getOutput() returns output 2
08-26 21:53:47.479  7821  7821 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-26 21:53:47.479   319  1384 I AudioFlinger: isAudioPlaybackHookOn() false
08-26 21:53:47.479  1034  1887 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-26 21:53:47.479  1034  1887 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-26 21:53:47.479   319  2203 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-26 21:53:47.479   319  2203 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-26 21:53:47.479   319  2203 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-26 21:53:47.479   319  2203 V AudioPolicyManagerEx: getOutput() returns output 2
08-26 21:53:47.479  1853  2717 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-26 21:53:47.480  1853  2717 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-26 21:53:47.480  3203  3219 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-26 21:53:47.480  3203  3219 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-26 21:53:47.480   319  1377 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-26 21:53:47.480   319  1377 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-26 21:53:47.480  3203  3218 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-26 21:53:47.480  3203  3218 V AudioSyste,m: ioConfigChanged() opening already existing output! 2
08-26 21:53:47.480  7821  7838 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-26 21:53:47.481  7821  7838 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-26 21:53:47.481  7821  7821 V AudioSystem: getLatency() output 2, latency 50
08-26 21:53:47.481  7821  7821 V AudioSystem: getFrameCount() output 2, frameCount 960
08-26 21:53:47.481  7821  7821 V AudioTrack: createTrack_l() output 2 afLatency 50
08-26 21:53:47.481   319  1384 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-26 21:53:47.481   319  1384 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-26 21:53:47.481   319  1384 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-26 21:53:47.481   319  1384 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-26 21:53:47.481   319  1384 V AudioFlinger: createTrack() lSessionId: 23
08-26 21:53:47.481  1603  1621 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
,08-26 21:53:47.481  1603  1621 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-26 21:53:47.481  1034  2030 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-26 21:53:47.481  1034  2030 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-26 21:53:47.482  1853  2419 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-26 21:53:47.482  1853  2419 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-26 21:53:47.482  7821  7821 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-26 21:53:47.482   319  1383 V AudioFlinger: acquiring 23 from 7821, for 7821
08-26 21:53:47.482   319  1383 V AudioFlinger:  added new entry for 23
08-26 21:53:47.482  7821  7821 V ToneGenerator: ToneGenerator INIT OK, time: 140251
08-26 21:53:47.482  7821  7821 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1bb02614
08-26 21:53:47.483  7821  8050 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-26 21:53:47.483  7821  8050 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-26 21:53:47.484  7821  8050 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-26 21:53:47.484  7821  8050 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-26 21:53:47.485   319  2203 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7821
08-26 21:53:47.485   319  2203 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-26 21:53:47.485   319  2203 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-26 21:53:47.485   319  2203 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-26 21:53:47.485   319  2203 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-26 21:53:47.485   319  2203 V voice   : voice_set_parameters: exit with code(0)
08-26 21:53:47.485   319  2203 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-26 21:53:47.485   319  2203 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-26 21:53:47.485   319  2203 V msm8974_platform: platform_set_parameters: exit with code(0)
08-26 21:53:47.485   319  2203 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-26 21:53:47.485   319  2203 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-26 21:53:47.485   319  2203 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-26 21:53:47.486  7821  7821 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1bb02614
08-26 21:53:47.487  7821  8050 V ToneGenerator: ToneGenerator destructor
08-26 21:53:47.487  7821  8050 V ToneGenerator: stopTone
08-26 21:53:47.487  7821  8050 V ToneGenerator: Delete Track: 0xb4928080
08-26 21:53:47.488  7821  7821 D A2dpService: Received start request. Starting profile...
08-26 21:53:47.488  7821  8050 V AudioTrack: ~AudioTrack, releasing session id from 7821 on behalf of 7821
08-26 21:53:47.488   319  1384 V AudioFlinger: releasing 23 from 7821 for 7821
08-26 21:53:47.488   319  1384 V AudioFlinger:  decremented refcount to 0
08-26 21:53:47.488   319  1384 V AudioFlinger: purging stale effects
08-26 21:53:47.488   319  1384 V AudioPolicyService: AudioCommandThread() adding release output 2
08-26 21:53:47.488   319  1384 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-26 21:53:47.488   319  1272 V AudioPolicyService: AudioCommandThread() waking up
08-26 21:53:47.488  7821  7821 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-26 21:53:47.488   319  1272 V AudioPolicyService: AudioCommandThread() processing release output 2
08-26 21:53:47.488   319  1272 V AudioPolicyManager: releaseOutput() 2
08-26 21:53:47.488   319  1272 V AudioPolicyService: AudioCommandThread() going to sleep
08-26 21:53:47.488   319  1384 V AudioFlinger: PlaybackThread::Track destructor
08-26 21:53:47,.488   319  1384 V AudioFlinger: removeClient_l() pid 7821, calling pid 319
08-26 21:53:47.489  7821  7821 V Avrcp   : make
08-26 21:53:47.489  7821  7821 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-26 21:53:47.490  7821  7821 I bluedroid-qcom: get_profile_interface avrcp
08-26 21:53:47.492  1034  1576 W Process : Unable to open /proc/8051/status
08-26 21:53:47.497  7821  7821 V AudioManager: registerRemoteController: size of Media player list: 0
,08-26 21:53:47.499  7821  7821 E AudioManager: No RCC entry present to update
08-26 21:53:47.499  7821  7821 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-26 21:53:47.504  7821  7821 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-26 21:53:47.505  7821  7821 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-26 21:53:47.505  7821  7821 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-26 21:53:47.508  7821  7821 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-26 21:53:47.609  1034  1050 V SIM_STK : Menu title from STK is T-Mobile
08-26 21:53:47.610  1034  1050 V SIM_STK : Menu title from STK is T-Mobile
,08-26 21:53:47.721  1034  1887 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-26 21:53:47.731  7821  7821 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-26 21:53:47.736  7821  7821 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-26 21:53:47.737  7821  7821 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-26 21:53:47.737  7821  7821 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-26 21:53:47.737  7821  7821 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-26 21:53:47.737  7821  7821 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
,08-26 21:53:47.737  7821  7821 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
,08-26 21:53:47.737  7821  7821 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-26 21:53:47.737  7821  7821 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-26 21:53:47.737  7821  7821 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-26 21:53:47.737  7821  7821 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-26 21:53:47.738  7821  7821 I BluetoothA2dpServiceJni: classInitNative
08-26 21:53:47.738  7821  7821 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-26 21:53:47.738  7821  7821 D A2dpStateMachine: make
08-26 21:53:47.742  7821  7821 I bluedroid-qcom: get_profile_interface a2dp
08-26 21:53:47.743  7821  8057 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-26 21:53:47.752  7821  7821 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-26 21:53:47.752  7821  7821 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-26 21:53:47.753  7821  7821 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1bb02614
08-26 21:53:47.753  7821  8055 D A2dpStateMachine: Enter Disconnected: -2
,08-26 21:53:47.755  7821  7821 I BluetoothHidServiceJni: classInitNative: succeeds
,08-26 21:53:47.757  7821  7821 D HidService: Received start request. Starting profile...
08-26 21:53:47.757  7821  7821 I bluedroid-qcom: get_profile_interface hidhost
08-26 21:53:47.757  7821  7821 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1bb02614
08-26 21:53:47.758  7821  7821 I BluetoothHealthServiceJni: classInitNative: succeeds
08-26 21:53:47.759  7821  7821 D HealthService: Received start request. Starting profile...
08-26 21:53:47.763  7821  7821 I bluedroid-qcom: get_profile_interface health
08-26 21:53:47.763  7821  7821 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-26 21:53:47.763  7821  7821 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1bb02614
08-26 21:53:47.764  7821  7821 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-26 21:53:47.765  7821  7821 D PanService: Received start request. Starting profile...
08-26 21:53:47.765  7821  7821 D BluetoothPanServiceJni: initializeNative(L110): pan
08-26 21:53:47.765  7821  7821 I bluedroid-qcom: get_profile_interface pan
,08-26 21:53:47.773  7821  7821 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-26 21:53:47.773  7821  7821 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1bb02614
08-26 21:53:47.774  7821  7821 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-26 21:53:47.778  7821  7821 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-26 21:53:47.778  7821  7821 D BtGatt.GattService: Received start request. Starting profile...
08-26 21:53:47.778  7821  7821 D BtGatt.GattService: start()
08-26 21:53:47.778  7821  7821 I bluedroid-qcom: get_profile_interface gatt
08-26 21:53:47.779  7821  7821 D BtGatt.AdvertiseManager: advertise manager created
08-26 21:53:47.787  7821  7821 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1bb02614
08-26 21:53:47.788  7821  7821 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1bb02614
08-26 21:53:47.789  7821  7821 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-26 21:53:47.789  7821  7821 V BluetoothMapService: BluetoothMapBinder()
,08-26 21:53:47.790  7821  7821 D BluetoothMapService: Received start request. Starting profile...
,08-26 21:53:47.790  7821  7821 D BluetoothMapService: start()
08-26 21:53:47.794  7821  7821 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-26 21:53:47.794  7821  7821 D BluetoothMapEmailAppObserver: createReceiver()
08-26 21:53:47.795  7821  7821 D BluetoothMapEmailAppObserver: initObservers()
08-26 21:53:47.795  7821  7821 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-26 21:53:47.801  7821  7821 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1bb02614
08-26 21:53:47.802  7821  7821 D HeadsetStateMachine: Proxy object connected
08-26 21:53:47.802  7821  7821 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-26 21:53:47.803  7821  7821 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
,08-26 21:53:47.804  7821  8050 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-26 21:53:47.805  7821  8050 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-26 21:53:47.805  7821  8050 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-26 21:53:47.809  7821  7821 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-26 21:53:47.812  7821  7821 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-26 21:53:47.814  7821  7821 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-26 21:53:47.820  7821  7821 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-26 21:53:47.823  7821  7821 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-26 21:53:47.826  7821  7821 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-26 21:53:47.826  7821  7821 V PanService: [BTUI] SIM Extra State :ABSENT
08-26 21:53:47.831  7821  7821 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-26 21:53:47.831  7821  7821 V BluetoothMapService: Handler(): got msg=1
08-26 21:53:47.831  7821  8028 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-26 21:53:47.832  7821  8028 I bluedroid-qcom: enable
08-26 21:53:47.832  7821  7821 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-26 21:53:47.832  7821  7821 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-26 21:53:47.832  7821  7821 V BluetoothSapReceiver: SapReceiver onReceive 
08-26 21:53:47.832  7821  8028 I bt_hci_bdroid: init
08-26 21:53:47.832  7821  7821 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 21:53:47.832  7821  7821 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-26 21:53:47.832  7821  8067 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-26 21:53:47.836  7821  8067 I bt-btu  : btu_task pending for preload complete event
,08-26 21:53:47.836  7821  8028 I bt_vendor: bt-vendor : init
,08-26 21:53:47.836  7821  8028 I bt_vendor: bt-vendor : get_bt_soc_type
08-26 21:53:47.836  7821  8028 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-26 21:53:47.836  7821  8028 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-26 21:53:47.836  7821  8028 D bt_userial_mct: userial_init
08-26 21:53:47.837  7821  8028 D bt_hci_bdroid: set_power 1
08-26 21:53:47.837  7821  8028 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-26 21:53:47.837  7821  8028 I bt_vendor: Starting hciattach daemon
08-26 21:53:47.837  7821  8028 I bt_vendor: try to set true
08-26 21:53:47.829  8070  8070 W sh      : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 21:53:47.829  8070  8070 W sh      : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 21:53:47.873  8071  8071 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-26 21:53:47.986  8077  8077 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-26 21:53:48.000  8078  8078 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-26 21:53:48.041  8080  8080 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-26 21:53:48.068  8081  8081 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-26 21:53:48.083  8085  8085 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-26 21:53:48.096  8086  8086 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-26 21:53:48.117  8088  8088 I libmdmdetect: ESOC framework not supported
,08-26 21:53:48.118  8088  8088 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-26 21:53:48.126  8088  8088 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
,08-26 21:53:48.126  8088  8088 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-26 21:53:48.126  8088  8088 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-26 21:53:48.126  8088  8088 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-26 21:53:48.126  8088  8088 D bthci_qcomm_common: [BTUI]     LE: Class 2
,08-26 21:53:48.126  8088  8088 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-26 21:53:48.126  8088  8088 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
,08-26 21:53:48.163  8088  8089 E QC-QMI  : qmi_client [8088] 15: failed to locate client data
,08-26 21:53:48.165   469   469 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-26 21:53:48.165   469   469 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
,08-26 21:53:48.193  8090  8090 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-26 21:53:48.209  8091  8091 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-26 21:53:48.242  7821  8028 I bt_vendor: bluetooth satus is on
,08-26 21:53:48.242  7821  8028 D bt_hci_bdroid: preload
,08-26 21:53:48.246  7821  8069 D bt_userial_mct: userial_open(port:0)
08-26 21:53:48.246  7821  8069 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
08-26 21:53:48.250  7821  8069 I bt_vendor: Done intiailizing UART
08-26 21:53:48.252  7821  8069 I bt_vendor: Done intiailizing UART
08-26 21:53:48.252  7821  8069 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-26 21:53:48.252  7821  8069 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-26 21:53:48.253  7821  8093 D bt_userial_mct: Entering userial_read_thread()
08-26 21:53:48.254  7821  8067 I bt-btu  : btu_task received preload complete event
08-26 21:53:48.255  7821  8067 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-26 21:53:48.255  7821  8067 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-26 21:53:48.262  7821  8067 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
,08-26 21:53:48.273  7821  8067 I         : BTE_InitTraceLevels -- TRC_HCI
,08-26 21:53:48.273  7821  8067 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-26 21:53:48.273  7821  8067 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-26 21:53:48.273  7821  8067 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-26 21:53:48.273  7821  8067 I         : BTE_InitTraceLevels -- TRC_AVRC
08-26 21:53:48.273  7821  8067 I         : BTE_InitTraceLevels -- TRC_A2D
08-26 21:53:48.273  7821  8067 I         : BTE_InitTraceLevels -- TRC_BNEP
08-26 21:53:48.273  7821  8067 I         : BTE_InitTraceLevels -- TRC_BTM
,08-26 21:53:48.273  7821  8067 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-26 21:53:48.274  7821  8067 I         : BTE_InitTraceLevels -- TRC_GAP
08-26 21:53:48.274  7821  8067 I         : BTE_InitTraceLevels -- TRC_PAN
08-26 21:53:48.274  7821  8067 I         : BTE_InitTraceLevels -- TRC_SDP
,08-26 21:53:48.274  7821  8067 I         : BTE_InitTraceLevels -- TRC_GATT
08-26 21:53:48.274  7821  8067 I         : BTE_InitTraceLevels -- TRC_SMP
08-26 21:53:48.274  7821  8067 I         : BTE_InitTraceLevels -- TRC_BTAPP
,08-26 21:53:48.274  7821  8067 I         : BTE_InitTraceLevels -- TRC_BTIF
08-26 21:53:48.383  7821  8067 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-26 21:53:48.383  7821  8067 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa016c061 
,08-26 21:53:48.383  7821  8067 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa016c061 
,08-26 21:53:48.410  7821  8032 E bt-btif : Calling BTA_HhEnable
08-26 21:53:48.410  7821  8032 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-26 21:53:48.411  7821  8032 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-26 21:53:48.413  7821  8067 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
,08-26 21:53:48.413  7821  8067 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-26 21:53:48.413  7821  8067 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-26 21:53:48.415  1034  1034 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-26 21:53:48.415  1034  1034 D BluetoothManagerService: Stored Bluetooth name: G3
08-26 21:53:48.416  7821  8067 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-26 21:53:48.416  7821  8067 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-26 21:53:48.416  7821  8032 D BluetoothAdapterProperties: Name is: G3
08-26 21:53:48.417  7821  8032 D BluetoothAdapterProperties: Scan Mode:20
08-26 21:53:48.418  7821  8032 D BluetoothAdapterProperties: Discoverable Timeout:120
08-26 21:53:48.418  7821  8032 D bt_hci_bdroid: postload
08-26 21:53:48.418  7821  8069 D bt_hci_bdroid: Used up Tx Cmd credits
08-26 21:53:48.420  7821  8069 D bt_hci_bdroid: Used up Tx Cmd credits
08-26 21:53:48.420  7821  8032 D bte_conf: Device ID record 1 : primary
08-26 21:53:48.420  7821  8032 D bte_conf:   vendorId            = 00c4
08-26 21:53:48.420  7821  8032 D bte_conf:   vendorIdSource      = 0001
08-26 21:53:48.420  7821  8032 D bte_conf:   product             = 13a1
08-26 21:53:48.420  7821  8032 D bte_conf:   version             = 1000
08-26 21:53:48.420  7821  8032 D bte_conf:   clientExecutableURL = 
08-26 21:53:48.420  7821  8032 D bte_conf:   serviceDescription  = 
08-26 21:53:48.420  7821  8032 D bte_conf:   documentationURL    = 
08-26 21:53:48.420  7821  8032 D bte_conf: bte_load_did_conf no section named DID2.
08-26 21:53:48.421  7821  8067 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-26 21:53:48.424  7821  8069 D bt_hci_bdroid: Used up Tx Cmd credits
,08-26 21:53:48.429  7821  8028 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
,08-26 21:53:48.429  7821  8028 D BluetoothAdapterProperties: ScanMode =  20
08-26 21:53:48.430  7821  8028 D BluetoothAdapterProperties: State =  11
08-26 21:53:48.430  7821  8028 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-26 21:53:48.430  7821  8028 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-26 21:53:48.430  7821  8028 D BluetoothAdapterProperties: Setting state to 12
08-26 21:53:48.430  7821  8028 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-26 21:53:48.429  8098  8098 W sh      : type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 21:53:48.429  8098  8098 W sh      : type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 21:53:48.439  7821  8032 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-26 21:53:48.439  7821  8032 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-26 21:53:48.448  1034  1105 D BluetoothManagerService: Message: 60
08-26 21:53:48.448  1034  1105 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-26 21:53:48.448  1034  1105 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
08-26 21:53:48.448  7821  8067 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-26 21:53:48.449  7821  8067 W bt-smp  : Plain text(LSB ~ MSB) = 87 ea 68 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-26 21:53:48.449  7821  8067 W bt-smp  : Encrypted text(LSB ~ MSB) = eb 8c a3 f5 75 da 47 90 c2 9d 37 5c e6 bf f9 6a 
08-26 21:53:48.449  7821  8069 D bt_hci_bdroid: Used up Tx Cmd credits
08-26 21:53:48.449  7821  8067 W bt-btm  : Stopping oneshot timer
08-26 21:53:48.455  7821  8093 E bt_mct  : hci lib postload completed
08-26 21:53:48.478  6674  6674 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 21:53:48.478  6674  6674 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 21:53:48.478  6674  6674 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 21:53:48.478  6674  6674 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 21:53:48.478  6674  6674 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 21:53:48.478  6674  6674 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 21:53:48.478  6674  6674 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 21:53:48.478  6674  6674 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 21:53:48.483  7821  8067 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-26 21:53:48.483  7821  8067 W bt-smp  : Plain text(LSB ~ MSB) = 74 23 78 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-26 21:53:48.483  7821  8067 W bt-smp  : Encrypted text(LSB ~ MSB) = 4b 6a e5 98 f2 ee 91 0b b7 6f b7 24 df c4 fc ac 
08-26 21:53:48.483  7821  8067 W bt-btm  : Stopping oneshot timer
08-26 21:53:48.488  1853  1868 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 21:53:48.489  7821  8028 I BluetoothAdapterState: Entering On State
08-26 21:53:48.496  7821  8032 D BluetoothAdapterProperties: Discoverable Timeout:120
08-26 21:53:48.496  7821  8032 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
,08-26 21:53:48.500  7821  8067 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-26 21:53:48.500  7821  8067 W bt-smp  : Plain text(LSB ~ MSB) = d0 28 7e 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-26 21:53:48.500  7821  8067 W bt-smp  : Encrypted text(LSB ~ MSB) = aa 65 65 49 f4 d8 50 93 2b 3f 7f a7 87 de 42 81 
08-26 21:53:48.500  7821  8067 W bt-btm  : Stopping oneshot timer
08-26 21:53:48.516  7821  8067 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-26 21:53:48.516  7821  8067 W bt-smp  : Plain text(LSB ~ MSB) = 82 bb 4e 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-26 21:53:48.516  7821  8067 W bt-smp  : Encrypted text(LSB ~ MSB) = b0 26 d0 04 f1 45 e7 c7 37 52 08 51 6b e2 0f e7 
08-26 21:53:48.518  7821  8067 W bt-btm  : Stopping oneshot timer
,08-26 21:53:48.521  6674  6674 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 21:53:48.528  7821  8028 D LGBluetoothServiceAdapter: [BTUI] OnState
08-26 21:53:48.528  7821  8028 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-26 21:53:48.529  7821  8028 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-26 21:53:48.531  7821  8028 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
,08-26 21:53:48.536  1853  1853 D BluetoothHeadset: Proxy object connected
08-26 21:53:48.536  1853  2419 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 21:53:48.538  1853  1853 D BluetoothHeadset: Proxy object connected
08-26 21:53:48.541  6917  6932 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-26 21:53:48.542  8114  8114 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-26 21:53:48.543  7821  8028 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
,08-26 21:53:48.545  7821  8067 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-26 21:53:48.545  7821  8067 W bt-smp  : Plain text(LSB ~ MSB) = 82 e9 5d 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-26 21:53:48.545  7821  8067 W bt-smp  : Encrypted text(LSB ~ MSB) = b4 f6 8c ad 97 d6 11 49 61 6d f0 18 62 b1 51 39 
08-26 21:53:48.545  7821  8067 W bt-btm  : Stopping oneshot timer
08-26 21:53:48.547  6917  6933 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 21:53:48.548  6917  6917 D BluetoothInputDevice: Proxy object connected
08-26 21:53:48.548  6917  6917 D HidProfile: Bluetooth service connected
08-26 21:53:48.702  1034  1105 I art     : Explicit concurrent mark sweep GC freed 26652(1330KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/64MB, paused 3.820ms total 152.869ms
,08-26 21:53:48.703  1853  1868 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 21:53:48.703  6917  6917 D BluetoothHeadset: Proxy object connected
08-26 21:53:48.704  6917  6917 D HeadsetProfile: Bluetooth service connected
08-26 21:53:48.706  1853  1853 D BluetoothHeadset: Proxy object connected
08-26 21:53:48.707  6917  7041 D BluetoothPbap: onBluetoothStateChange: up=true
08-26 21:53:48.709  6917  6933 D BluetoothA2dp: onBluetoothStateChange: up=true
08-26 21:53:48.711  6917  6932 D BluetoothPan: onBluetoothStateChange on: true
08-26 21:53:48.711  6917  6932 D BluetoothPan: onBluetoothStateChange call bindService
08-26 21:53:48.713  1034  1105 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 21:53:48.714  6917  6917 D BluetoothA2dp: Proxy object connected
08-26 21:53:48.714  6917  6917 D A2dpProfile: Bluetooth service connected
08-26 21:53:48.714  1034  1034 D BluetoothHeadset: Proxy object connected
08-26 21:53:48.715  6917  6933 D BluetoothMap: onBluetoothStateChange: up=true
,08-26 21:53:48.718  1034  1105 D BluetoothA2dp: onBluetoothStateChange: up=true
08-26 21:53:48.723  1034  1105 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-26 21:53:48.723  1034  1034 D BluetoothA2dp: Proxy object connected
08-26 21:53:48.723  1034  1105 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-26 21:53:48.727  1942  1942 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-26 21:53:48.728  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,08-26 21:53:48.729  6674  6674 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 21:53:48.730  6917  6917 D BluetoothPan: BluetoothPAN Proxy object connected
08-26 21:53:48.730  6917  6917 D PanProfile: Bluetooth service connected
08-26 21:53:48.731  1942  2102 D LGBluetoothAPIService: Message: 1
08-26 21:53:48.731  1942  2102 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-26 21:53:48.731  1034  1034 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-26 21:53:48.735  1034  1105 D BluetoothManagerService: Message: 40
08-26 21:53:48.735  1034  1105 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-26 21:53:48.740  1942  2102 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
,08-26 21:53:48.744  7821  7821 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-26 21:53:48.744  7821  7821 D BluetoothMapService: STATE_ON
08-26 21:53:48.745  6917  6917 D BluetoothMap: Proxy object connected
08-26 21:53:48.745  6917  6917 D MapProfile: Bluetooth service connected
08-26 21:53:48.745  6917  6917 D BluetoothMap: getConnectedDevices()
08-26 21:53:48.746  7821  7821 D LGBluetoothAPIServer: [BTUI] onCreate()
08-26 21:53:48.746  7821  7821 D LGBluetoothAPIServer: [BTUI] onBind()
08-26 21:53:48.747  7821  8122 V BluetoothMapService: getConnectedDevices()
08-26 21:53:48.747  1942  1942 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-26 21:53:48.747  1942  2102 D LGBluetoothAPIService: Message: 100
08-26 21:53:48.747  1942  2102 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-26 21:53:48.751  6917  6917 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-26 21:53:48.752  6917  6917 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-26 21:53:48.758  7821  7821 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1bb02614
08-26 21:53:48.759  7821  7821 V BluetoothPbapService: Pbap Service onCreate
08-26 21:53:48.759  6917  6917 D DockEventReceiver: finishStartingService: stopping service
08-26 21:53:48.759  7821  7821 V BluetoothPbapService: Starting PBAP service
08-26 21:53:48.760  7821  7821 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-26 21:53:48.760  7821  7821 V BluetoothPbapService: Pbap Service onBind
08-26 21:53:48.762  7821  7821 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-26 21:53:48.762  7821  7821 V BluetoothPbapService: state: 12
08-26 21:53:48.762  6917  6917 D BluetoothPbap: Proxy object connected
08-26 21:53:48.762  6917  6917 D PbapServerProfile: Bluetooth service connected
08-26 21:53:48.762  7821  7821 V BluetoothMapService: Handler(): got msg=1
08-26 21:53:48.763  7821  7821 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-26 21:53:48.763  7821  7821 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-26 21:53:48.763  7821  7821 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 21:53:48.764  7821  7821 V BluetoothPbapReceiver: ***********state = 12
08-26 21:53:48.764  7821  8125 D BluetoothMapMasInstance: MAS initSocket()
08-26 21:53:48.765  7821  8125 D BluetoothMapMasInstance:   masId = 00
08-26 21:53:48.765  7821  8125 D BluetoothMapMasInstance:   msgTypes = 0e
08-26 21:53:48.765  7821  8125 D BluetoothMapMasInstance:   masName = SMS/MMS
08-26 21:53:48.765  7821  8125 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-26 21:53:48.765  7821  7821 V BluetoothPbapService: Handler(): got msg=1
08-26 21:53:48.766  7821  7821 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-26 21:53:48.767  7821  8126 V BluetoothPbapService: Pbap Service initSocket
,08-26 21:53:48.768  2205  2205 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-26 21:53:48.768  1034  1576 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 21:53:48.768  1034  1940 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 21:53:48.769  2205  2205 D c       : Getting all permits...
08-26 21:53:48.769  2205  2205 D a       : Opening database...
08-26 21:53:48.770  7821  8126 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 21:53:48.770  7821  8125 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 21:53:48.771  7821  8126 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-26 21:53:48.771  7821  8126 V BluetoothPbapService: Succeed to create listening socket 
08-26 21:53:48.772  7821  8126 V BluetoothPbapService: Accepting socket connection...
08-26 21:53:48.772  7821  8032 D BluetoothAdapterProperties: Scan Mode:21
08-26 21:53:48.772  7821  8032 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-26 21:53:48.772  7821  8125 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-26 21:53:48.773  7821  8125 V BluetoothMapMasInstance: Succeed to create listening socket 
08-26 21:53:48.773  7821  8125 D BluetoothMapMasInstance: Accepting socket connection...
08-26 21:53:48.774  6674  6674 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 21:53:48.778  2205  2205 D a       : Opening database auth.proximity.permit_store...
,08-26 21:53:48.779  2205  2205 D a       : Closing database...
08-26 21:53:48.789  6917  6917 D BluetoothPermissionRequest: onReceive
08-26 21:53:48.792  6917  6917 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
,08-26 21:53:48.794  6917  6917 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-26 21:53:48.797  7821  7821 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-26 21:53:48.798  7821  7821 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-26 21:53:48.806  7821  7821 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-26 21:53:48.831  7821  7821 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,08-26 21:53:48.832  7821  7821 V BtOppService: onCreate
08-26 21:53:48.836  7821  7821 V BluetoothOppNotification: send message
,08-26 21:53:48.840  7821  7821 V BtOppService: Starting RfcommListener
08-26 21:53:48.852  7821  7821 D BluetoothOppPreference: Dumping Names:  
08-26 21:53:48.852  7821  7821 D BluetoothOppPreference: {}
08-26 21:53:48.852  7821  7821 D BluetoothOppPreference: Dumping Channels:  
08-26 21:53:48.852  7821  7821 D BluetoothOppPreference: {}
08-26 21:53:48.852  7821  7821 V BtOppService: onStartCommand
,08-26 21:53:48.857  7821  8132 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-26 21:53:48.858  7821  7821 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-26 21:53:48.858  7821  7821 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-26 21:53:48.859  7821  8132 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-26 21:53:48.860  7821  8129 V BtOppService: Deleted complete outbound shares, number =  0
08-26 21:53:48.862  7821  7821 V BluetoothOppNotification: new notify threadi!
08-26 21:53:48.863  7821  7821 V BluetoothOppNotification: send delay message
08-26 21:53:48.864  7821  8129 V BtOppService: Deleted complete inbound failed shares, number = 0
08-26 21:53:48.864  7821  8129 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-26 21:53:48.864  7821  7821 V BtOppService: start RfcommListener
08-26 21:53:48.865  7821  8129 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@20295a09 on behalf of 
,08-26 21:53:48.867  7821  8133 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,08-26 21:53:48.870  7821  8132 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3700440e on behalf of 
08-26 21:53:48.871  7821  8133 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@30ad6e2f on behalf of 
08-26 21:53:48.871  7821  7821 V BtOppService: RfcommListener started
08-26 21:53:48.872  7821  7821 V BtOppService: ContentObserver received notification
08-26 21:53:48.872  7821  7821 V BtOppService: ContentObserver received notification
08-26 21:53:48.873  7821  8132 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-26 21:53:48.873  7821  8132 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-26 21:53:48.874  7821  8132 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@38c46c3c on behalf of 
08-26 21:53:48.874  7821  8134 V BtOppRfcommListener: Starting RFCOMM listener....
08-26 21:53:48.875  1034  1898 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 21:53:48.877  7821  8134 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 21:53:48.878  7821  8134 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=75
08-26 21:53:48.879  7821  8134 V BtOppRfcommListener: Started RFCOMM listener....
08-26 21:53:48.879  7821  8134 I BtOppRfcommListener: Accept thread started.
08-26 21:53:48.879  7821  8134 V BtOppRfcommListener: Accepting connection...
08-26 21:53:48.880  7821  8133 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-26 21:53:48.882  7821  8132 V BluetoothOppNotification: update too frequent, put in queue
,08-26 21:53:48.884  7821  8132 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-26 21:53:48.885  7821  8133 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-26 21:53:48.886  7821  8133 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@37048dc5 on behalf of 
08-26 21:53:48.887  7821  8133 V BluetoothOppNotification: outbound: succ-0  fail-0
08-26 21:53:48.889  7821  8133 V BluetoothOppNotification: outbound notification was removed.
08-26 21:53:48.889  7821  8133 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-26 21:53:48.890  7821  8133 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3b80931a on behalf of 
08-26 21:53:48.891  7821  8133 V BluetoothOppNotification: inbound: succ-0  fail-0
08-26 21:53:48.893  7821  8133 V BluetoothOppNotification: inbound notification was removed.
08-26 21:53:48.893  7821  8133 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-26 21:53:48.894  7821  8133 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@22acbe4b on behalf of 
,08-26 21:53:48.898  7821  7821 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1bb02614
,08-26 21:53:48.898  7821  7821 V BluetoothFtpService: Ftp Service onCreate
08-26 21:53:48.898  7821  7821 I BluetoothFtpService: Ftp Service onCreate
08-26 21:53:48.899  7821  7821 V BluetoothFtpService: Ftp Service onStartCommand
08-26 21:53:48.899  7821  7821 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-26 21:53:48.899  7821  7821 V BluetoothFtpService: Starting Listening on sockets
08-26 21:53:48.899  7821  7821 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-26 21:53:48.899  7821  7821 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-26 21:53:48.899  7821  7821 V BluetoothSapReceiver: SapReceiver onReceive 
08-26 21:53:48.900  7821  7821 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 21:53:48.900  7821  7821 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-26 21:53:48.900  7821  7821 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-26 21:53:48.902  7821  7821 V BluetoothFtpService: Handler(): got msg=1
08-26 21:53:48.902  7821  7821 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-26 21:53:48.903  7821  7821 V BluetoothFtpService: Ftp Service initSocket
08-26 21:53:48.907  1034  2006 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-26 21:53:48.909  7821  7821 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 21:53:48.911  7821  7821 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-26 21:53:48.913  7821  8135 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-26 21:53:48.928  7821  7821 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1bb02614
08-26 21:53:48.928  7821  7821 V BluetoothSapService: Sap Service onCreate
,08-26 21:53:48.931  7821  7821 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-26 21:53:48.931  7821  7821 V BluetoothSapService: state: 12
,08-26 21:53:48.931  7821  7821 V BluetoothSapService: Starting SAP server process
08-26 21:53:48.934  7821  7821 V BluetoothSapService: SAP Service startRfcommListenerThread
08-26 21:53:48.929  8136  8136 W sapd    : type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 21:53:48.929  8136  8136 W sapd    : type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 21:53:48.935  7821  8137 V BluetoothSapService: Sap Service initRfcommSocket
08-26 21:53:48.936  1034  1921 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 21:53:48.937  7821  8137 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 21:53:48.938  7821  8137 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-26 21:53:48.938  7821  8137 V BluetoothSapService: Succeed to create listening socket 
08-26 21:53:48.938  7821  8137 V BluetoothSapService: Accepting socket connection...
08-26 21:53:48.958  8136  8136 V BT_SAP  : Event pipe created
08-26 21:53:48.958  8136  8136 V BT_SAP  : create_server_socket qcom.sap.server
08-26 21:53:48.958  8136  8136 V BT_SAP  : created socket fd 6
,08-26 21:53:49.310  6674  6764 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 21:53:49.310  6674  6764 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 21:53:49.310  6674  6764 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 21:53:49.310  6674  6764 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 21:53:49.310  6674  6764 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 21:53:49.310  6674  6764 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 21:53:49.310  6674  6764 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 21:53:49.310  6674  6764 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 21:53:49.317  6674  6764 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 21:53:49.319  6674  6764 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 21:53:49.319  6674  6764 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@351d4186 added. We now have 8 listener(s)
08-26 21:53:49.319  6674  6764 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 21:53:49.324  1034  1959 D WifiServiceImplEx: setWifiEnabled: false pid=6674, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-26 21:53:49.324  1034  1959 D WifiService: setWifiEnabled: false pid=6674, uid=10118
08-26 21:53:49.324  1034  1959 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-26 21:53:49.330  6674  6764 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 21:53:49.334  1034  2006 D WifiServiceImplEx: setWifiEnabled: true pid=6674, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-26 21:53:49.334  1034  2006 D WifiService: setWifiEnabled: true pid=6674, uid=10118
08-26 21:53:49.334  1034  2006 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-26 21:53:49.346  1034  1537 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-26 21:53:49.346  1034  1537 I LGFTMITEM: [GET_FTM][id=6], offset=12288
,08-26 21:53:49.350  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
,08-26 21:53:49.351  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
,08-26 21:53:49.351  1034  1034 D Ulp_jni : JNI:system_update. Event-4
,08-26 21:53:49.351  1034  1537 E WifiUtil: wfc_util_ffile_check_copy(): pid[1034] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
,08-26 21:53:49.351  1034  1537 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
,08-26 21:53:49.351  1034  1537 E WifiUtil: wfc_util_ffile_check_copy(): pid[1034] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
,08-26 21:53:49.351  1034  1537 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010],
,08-26 21:53:49.352  1034  1537 I WifiUtil: Intf0MacAddress=C49A027FFB5D
,08-26 21:53:49.352  1034  1537 E WifiHW  : unknown target_country: EU , set to default,
,08-26 21:53:49.352  1034  1537 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
,08-26 21:53:49.352  1034  1537 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-26 21:53:49.352  1034  1537 I WifiUtil: gEnableBmps=1,
08-26 21:53:49.866  7821  7821 V BluetoothOppNotification: new notify threadi!,
08-26 21:53:49.867  7821  7821 V BluetoothOppNotification: send delay message,
,08-26 21:53:49.894  7821  8156 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-26 21:53:49.897  7821  8156 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2c8406d4 on behalf of 
08-26 21:53:49.898  7821  8156 V BluetoothOppNotification: mUpdateCompleteNotification = true
,08-26 21:53:49.901  7821  8156 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-26 21:53:49.903  7821  8156 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@a43b07d on behalf of 
08-26 21:53:49.903  7821  8156 V BluetoothOppNotification: outbound: succ-0  fail-0
08-26 21:53:49.905  7821  8156 V BluetoothOppNotification: outbound notification was removed.
08-26 21:53:49.905  7821  8156 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-26 21:53:49.906  7821  8156 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3c466b72 on behalf of 
08-26 21:53:49.907  7821  8156 V BluetoothOppNotification: inbound: succ-0  fail-0
,08-26 21:53:49.913  7821  8156 V BluetoothOppNotification: inbound notification was removed.
08-26 21:53:49.913  7821  8156 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-26 21:53:49.914  7821  8156 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2ae4abc3 on behalf of 
08-26 21:53:49.950  1034  1105 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-26 21:53:49.950  1034  1105 D Tethering: InitialState.processMessage what=4
08-26 21:53:49.951  1034  1105 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-26 21:53:49.958   314   879 D SoftapController: Softap fwReload - Ok
,08-26 21:53:49.969  1034  1537 E NetdConnector: NDC Command {83 softap fwreload wlan0 STA} took too long (584ms)
,08-26 21:53:49.983   314   879 D CommandListener: Setting iface cfg
08-26 21:53:49.983   314   879 D CommandListener: Trying to bring down wlan0
,08-26 21:53:49.995   314   879 D CommandListener: Clearing all IP addresses on wlan0
,08-26 21:53:50.022  1034  1537 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,08-26 21:53:50.019  8158  8158 W wpa_supplicant: type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 21:53:50.030  1034  1537 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-26 21:53:50.030  1034  1537 E WifiStateMachine: useWiFiOffloading() : false
08-26 21:53:50.030  1034  1537 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-26 21:53:50.029  8158  8158 W wpa_supplicant: type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-26 21:53:50.061  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
,08-26 21:53:50.064  6674  6674 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 21:53:50.066  1942  1942 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-26 21:53:50.067  6917  6917 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-26 21:53:50.067  6917  6917 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-26 21:53:50.067  6917  6917 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-26 21:53:50.067  6917  6917 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-26 21:53:50.068  6917  6917 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-26 21:53:50.069  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 21:53:50.070  6917  6917 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-26 21:53:50.070  6917  6917 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-26 21:53:50.070  6917  6917 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-26 21:53:50.070  6917  6917 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-26 21:53:50.070  6917  6917 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-26 21:53:50.071  6917  6917 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-26 21:53:50.072  1034  1537 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-26 21:53:50.072  1034  1537 D WifiMonitor: connecting to supplicant
,08-26 21:53:50.077  6917  6917 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-26 21:53:50.077  6917  6917 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-26 21:53:50.077  6917  6917 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-26 21:53:50.077  6917  6917 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-26 21:53:50.078  6917  6917 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-26 21:53:50.078  6917  6917 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-26 21:53:50.078  6917  6917 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-26 21:53:50.078  6917  6917 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-26 21:53:50.078  6917  6917 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-26 21:53:50.078  6917  6917 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-26 21:53:50.078  6917  6917 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-26 21:53:50.090  8158  8158 I wpa_supplicant: Successfully initialized wpa_supplicant
08-26 21:53:50.114   345   345 I art     : Background concurrent mark sweep GC freed 786(33KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 10.509ms total 30.431ms
,08-26 21:53:50.124  1034  1576 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=8175 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
08-26 21:53:50.128  8158  8158 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-26 21:53:50.129  8158  8158 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,08-26 21:53:50.186  8158  8158 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-26 21:53:50.217  1034  1887 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=8197 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-26 21:53:50.229  8175  8196 V FormManager: Network unavailable.
08-26 21:53:50.230  8175  8196 V FormManager: Network unavailable.
08-26 21:53:50.232  8158  8158 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
08-26 21:53:50.233  8175  8195 W FormManager: Network not available. Please check & try again.
08-26 21:53:50.239  1034  1537 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
,08-26 21:53:50.240  1034  1537 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-26 21:53:50.240  1034  1537 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-26 21:53:50.241  1034  1537 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-26 21:53:50.241  1034  1537 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-26 21:53:50.242  1034  1537 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-26 21:53:50.242  1034  8215 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-26 21:53:50.243  1034  8215 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-26 21:53:50.243  8158  8158 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-26 21:53:50.243  1034  8215 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-26 21:53:50.243  1034  8215 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-26 21:53:50.243  1034  8215 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-26 21:53:50.243  1034  8215 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-26 21:53:50.243  1034  1537 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-26 21:53:50.244  1034  1537 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-26 21:53:50.244  1034  1537 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-26 21:53:50.244  1034  1537 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-26 21:53:50.244  1034  1537 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-26 21:53:50.245  1034  1537 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-26 21:53:50.245  1034  1537 E WifiStateMachine: useWiFiOffloading() : false
08-26 21:53:50.245  1034  1537 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-26 21:53:50.245  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 21:53:50.245  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 21:53:50.245  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 21:53:50.245  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 21:53:50.245  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-26 21:53:50.245  1034  1537 D WifiNative-wlan0: doBoolean: SET update_config 1
08-26 21:53:50.247  1034  1537 D WifiNative-wlan0: SET update_config 1: returned true
08-26 21:53:50.247  1034  1537 D WifiConfigStore: Loading config and enabling all networks 
08-26 21:53:50.247  1034  1537 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-26 21:53:50.247  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 21:53:50.247  1034  1537 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-26 21:53:50.248  1942  1942 D WfdService: Waiting for WifiP2p enabling
08-26 21:53:50.249  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-26 21:53:50.249  1034  1541 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-26 21:53:50.252  6674  6674 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 21:53:50.252  6674  6674 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 21:53:50.252  6674  6674 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 21:53:50.252  6674  6674 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled,: true
08-26 21:53:50.252  6674  6674 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 21:53:50.252  6674  6674 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 21:53:50.252  6674  6674 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 21:53:50.252  6674  6674 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 21:53:50.254  1034  1537 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-26 21:53:50.254  6674  6674 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-26 21:53:50.263  1034  1537 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-26 21:53:50.263  1034  1537 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-26 21:53:50.264  1034  1537 D WifiStateMachine: enableVerboseLogging : level 2
08-26 21:53:50.264  1034  1537 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-26 21:53:50.264  1034  1537 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-26 21:53:50.264  1034  1537 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-26 21:53:50.265  1034  1537 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-26 21:53:50.265  1034  1537 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-26 21:53:50.265  1034  1537 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-26 21:53:50.265  1034  1537 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-26 21:53:50.266  1034  1537 D WifiNative-wlan0: SET model_number LG-D855: returned true
,08-26 21:53:50.266  1034  1537 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-26 21:53:50.266  1034  1537 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-26 21:53:50.266  1034  1537 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-26 21:53:50.266  1034  1537 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-26 21:53:50.266  1034  1537 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-26 21:53:50.267  1034  1537 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-26 21:53:50.268  1034  1537 D WifiStateMachine: Setting OUI to DA-A1-19
,08-26 21:53:50.268  1034  1537 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-26 21:53:50.268  1034  1537 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-26 21:53:50.268  1034  1537 D WifiNative-HAL: Setting external_sim to 1
08-26 21:53:50.268  1034  1537 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-26 21:53:50.269  1942  1942 D WfdsService: Supplicant Connection state is changed : true
08-26 21:53:50.269  1942  2307 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-26 21:53:50.269  1942  2307 D WfdsService: Set the WFDS Monitor: true
08-26 21:53:50.269  1942  2307 D WfdsMonitor: WfdsMonitorThread create
08-26 21:53:50.269  1942  2307 D WfdsMonitor: WFDS Monitor is created and started
08-26 21:53:50.269  1942  2307 D WfdsService: WiFi: Supplicant connection re-established
08-26 21:53:50.269  7858  7858 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 21:53:50.269  1034  1537 D WifiNative-wlan0: SET external_sim 1: returned true
08-26 21:53:50.270  1034  1537 I WifiNative-HAL: startHal
08-26 21:53:50.270  1034  1537 D wifi    : setting scan oui 0x953ec3e0
08-26 21:53:50.270  1942  8217 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-26 21:53:50.270  1034  1537 D WifiStateMachine: Setting OUI to DA-A1-19
08-26 21:53:50.270  1034  1537 I WifiNative-HAL: startHal
08-26 21:53:50.270  1034  1537 D wifi    : setting scan oui 0x953ec3e0
08-26 21:53:50.270  1034  1537 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-26 21:53:50.270  1942  8217 E CtrlSupplicant: Succeed to open control connection
08-26 21:53:50.271  1942  8217 E CtrlSupplicant: Succeed to open monitor connection
08-26 21:53:50.271  1942  8217 D WfdsMonitor: Supplicant connection established
08-26 21:53:50.271  1942  2307 D WfdsService: Connected to the supplicant for wfds
08-26 21:53:50.272  1034  1537 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-26 21:53:50.272  1034  1537 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-26 21:53:50.272  8158  8158 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-26 21:53:50.272  1034  1537 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-26 21:53:50.272  1034  1537 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-26 21:53:50.273  8158  8158 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-26 21:53:50.273  1034  1537 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-26 21:53:50.273  1034  1537 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-26 21:53:50.274  8158  8158 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-26 21:53:50.274  1034  1537 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-26 21:53:50.274  1034  1537 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-26 21:53:50.274  8158  8158 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-26 21:53:50.275  1034  1537 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-26 21:53:50.275  1034  1537 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-26 21:53:50.275  8158  8158 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-26 21:53:50.275  1034  1537 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-26 21:53:50.275  1034  1537 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-26 21:53:50.275  8158  8158 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-26 21:53:50.275  1034  1537 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-26 21:53:50.275  1034  1537 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-26 21:53:50.276  8158  8158 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-26 21:53:50.276  1034  1537 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-26 21:53:50.276  1034  1537 E WifiNative: : [143,032,779 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08,-26 21:53:50.276  1034  1537 D WifiNative-wlan0: doBoolean: RECONNECT
08-26 21:53:50.277  1034  1537 D WifiNative-wlan0: RECONNECT: returned true
08-26 21:53:50.277  1034  1537 D WifiNative-wlan0: doString: [STATUS]
08-26 21:53:50.277  1034  8215 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-26 21:53:50.277  1034  8215 E WifiMonitor: WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-26 21:53:50.277  1034  1537 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-26 21:53:50.278  1034  1537 D WifiNative-wlan0: doBoolean: SET ps 1
08-26 21:53:50.278  1034  1537 D WifiNative-wlan0: SET ps 1: returned true
08-26 21:53:50.278  1034  1536 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-26 21:53:50.280   314   879 D CommandListener: Setting iface cfg
08-26 21:53:50.280   314   879 D CommandListener: Trying to bring up p2p0
,08-26 21:53:50.280  1034  1536 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-26 21:53:50.280  1034  1536 D LGWifiP2pService: P2pEnablingState
08-26 21:53:50.280  1034  1536 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-26 21:53:50.280  1034  1536 D LGWifiP2pService: P2p socket connection successful
08-26 21:53:50.280  1034  1536 D LGWifiP2pService: P2pEnabledState
08-26 21:53:50.280  1034  1536 D LGWifiP2pService: sending p2p connection changed broadcast
08-26 21:53:50.281  1942  1942 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-26 21:53:50.281  1942  1942 D WfdsService: WifiP2pState is changed : true
08-26 21:53:50.281  1034  1536 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-26 21:53:50.281  1942  2307 D WfdsService: Receive the WFDS_ENABLE Method
08-26 21:53:50.281  1942  2307 D WfdsService: Set the WFDS Monitor: true
08-26 21:53:50.282  1942  2307 D WfdsService: Connected to the supplicant for wfds
08-26 21:53:50.282  1942  2307 D WfdsJNI : doCommand: WFDS_SET TRUE
08-26 21:53:50.282  8158  8158 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-26 21:53:50.282  1942  2307 D WfdsService: selectPreferredScanChannel [36]
08-26 21:53:50.282  1034  1536 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-26 21:53:50.282  1942  2307 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-26 21:53:50.282  1034  1536 D WifiNative-p2p0: doBoolean: SET device_name G3
08-26 21:53:50.282  1034  1536 D WifiNative-p2p0: SET device_name G3: returned true
08-26 21:53:50.282  1034  1536 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-26 21:53:50.282  1034  1536 D LGWifiP2pService: before postfix = G3
08-26 21:53:50.283  1034  1536 D WifiServerServiceExt: postfix byte check : 2
08-26 21:53:50.283  1034  1536 D LGWifiP2pService: after postfix = G3
08-26 21:53:50.283  1034  1536 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-26 21:53:50.283  1034  1536 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-26 21:53:50.283  1034  1536 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-26 21:53:50.283  1034  1537 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-26 21:53:50.283  1034  1536 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-26 21:53:50.283  1034  1536 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-26 21:53:50.283  1034  1537 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-26 21:53:50.284  1942  1942 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-26 21:53:50.284  1034  1536 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-26 21:53:50.284  1034  1536 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-26 21:53:50.284  1034  1537 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-26 21:53:50.284  1942  1942 D WfdsService: isConnected: false
08-26 21:53:50.284  1034  1537 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-26 21:53:50.284  1034  1536 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-26 21:53:50.284  1034  1536 D WifiNative-HAL: p2pGetDeviceAddress
08-26 21:53:50.285  1034  1537 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=143041  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-26 21:53:50.285  1034  1536 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-26 21:53:50.285  1034  1034 D WifiScanningService: SCAN_AVAILABLE : 3
08-26 21:53:50.285  1034  1034 D RttService: SCAN_AVAILABLE : 3
08-26 21:53:50.285  1034  1557 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-26 21:53:50.286  1034  1557 I WifiNative-HAL: startHal
08-26 21:53:50.286  1034  1557 D wifi    : getting scan capabilities on interface[1] = 0x953ec3e0
08-26 21:53:50.286  1034  1557 D wifi    : failed to get capabilities : -3
08-26 21:5,3:50.286  1034  1557 E WifiScanningService: could not get scan capabilities
08-26 21:53:50.286  1034  1558 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-26 21:53:50.287  1034  1536 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-26 21:53:50.287  1034  1536 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-26 21:53:50.287  1034  1536 D WifiNative-p2p0: P2P_FLUSH: returned true
08-26 21:53:50.287  1034  1536 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-26 21:53:50.288  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 21:53:50.288  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 21:53:50.288  1034  1536 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-26 21:53:50.288  1034  1536 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-26 21:53:50.288  1034  1536 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-26 21:53:50.288  1034  1536 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-26 21:53:50.288  1034  1537 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=143045  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-26 21:53:50.289  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 21:53:50.289  1034  1537 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-26 21:53:50.290  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 21:53:50.290  1034  1537 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-26 21:53:50.290  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 21:53:50.290  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-26 21:53:50.290  1034  1537 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-26 21:53:50.290  1034  1537 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-26 21:53:50.291  1942  1942 I WfdStateTracker: handleP2pThisDeviceChanged
08-26 21:53:50.291  1942  1942 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-26 21:53:50.291  1942  1942 D WfdsService: Update P2p Interface State: 3
,08-26 21:53:50.303  8197  8197 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-26 21:53:50.307  6917  6917 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-26 21:53:50.311  6917  6917 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 21:53:50.312  1034  1576 I ActivityManager: Killing 7264:com.lge.drmservice/u0a62 (adj 15): empty #17
08-26 21:53:50.312  8158  8158 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-26 21:53:50.312  1034  1536 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-26 21:53:50.312  1034  1536 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-26 21:53:50.313  1034  1537 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-26 21:53:50.313  1034  1537 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-26 21:53:50.314  1034  1537 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-26 21:53:50.314  1034  1537 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-26 21:53:50.314  8158  8158 E wpa_supplicant: disconnect_rssi_lvl: -100
08-26 21:53:50.314  1034  1537 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
,08-26 21:53:50.315  1034  1537 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
08-26 21:53:50.315  1034  1537 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
08-26 21:53:50.315  1034  1537 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-26 21:53:50.316  8158  8158 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-26 21:53:50.316  8158  8158 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 21:53:50.317  8158  8158 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-26 21:53:50.317  8158  8158 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 21:53:50.318  1034  8215 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-26 21:53:50.318  1034  8215 E WifiMonitor: WifiMonitor:wlan0 cnt=47 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 21:53:50.318  1034  8215 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 21:53:50.318  1942  8217 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 21:53:50.318  1034  8215 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 21:53:50.318  8158  8158 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 21:53:50.318  1034  8215 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 21:53:50.318  1034  8215 E WifiMonitor: WifiMonitor:p2p0 cnt=48 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 21:53:50.318  1034  8215 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 21:53:50.318  1034  8215 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 21:53:50.318  1942  8217 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 21:53:50.318  1034  8215 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 21:53:50.318  1034  8215 E WifiMonitor: WifiMonitor:p2p0 cnt=49 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 21:53:50.318  1034  8215 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 21:53:50.318  1034  8215 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 21:53:50.318  1034  1537 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-26 21:53:50.319  1034  1537 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-26 21:53:50.319  1034  1537 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-26 21:53:50.319  1034  1537 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-26 21:53:50.319  1034  1537 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-26 21:53:50.319  8158  8158 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-26 21:53:50.319  8158  8158 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-26 21:53:50.320  1034  8215 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-26 21:53:50.320  1034  8215 E WifiMonitor: WifiMonitor:wlan0 cnt=50 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-26 21:53:50.320  1034  8215 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-26 21:53:50.320  1034  8215 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-26 21:53:50.320  1034  1537 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-26 21:53:50.320  1034  1537 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-26 21:53:50.320  1034  1537 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-26 21:53:50.321  1034  1537 D WifiNative-wlan0: doBoolean: SCAN
08-26 21:53:50.321  1034  1537 D WifiNative-wlan0: SCAN: returned false
08-26 21:53:50.321  1034  1537 E WifiStateMachine:  DisconnectedState SUPPLICANT_ST,ATE_CHANGE_EVENT 46 0 rt=143078  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-26 21:53:50.364  1034  1536 D LGWifiP2pService: InactiveState
08-26 21:53:50.365  1034  1536 D LGWifiP2pService: InactiveState{ when=-77ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-26 21:53:50.365  1034  1536 D LGWifiP2pService: P2pEnabledState{ when=-77ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-26 21:53:50.365  1034  1536 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-26 21:53:50.365  8158  8158 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
,08-26 21:53:50.366  8158  8158 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 21:53:50.366  1034  8215 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-26 21:53:50.366  1034  8215 E WifiMonitor: WifiMonitor:p2p0 cnt=51 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
,08-26 21:53:50.366  1034  8215 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 21:53:50.366  1034  8215 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 21:53:50.368  8158  8158 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-26 21:53:50.368  1034  1536 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-26 21:53:50.368  8158  8158 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 21:53:50.368  1034  1536 D LGWifiP2pService: InactiveState{ when=-49ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-26 21:53:50.368  1034  1536 D LGWifiP2pService: P2pEnabledState{ when=-49ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-26 21:53:50.368  1034  1536 D LGWifiP2pService: InactiveState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-26 21:53:50.368  1034  1536 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-26 21:53:50.368  1034  1536 D LGWifiP2pService: DefaultState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-26 21:53:50.368  1034  1536 D LGWifiP2pService: InactiveState{ when=-3ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-26 21:53:50.368  1034  1536 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-26 21:53:50.368  1034  1536 D LGWifiP2pService: DefaultState{ when=-3ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-26 21:53:50.368  1034  8215 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 21:53:50.368  1034  8215 E WifiMonitor: WifiMonitor:p2p0 cnt=52 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 21:53:50.368  1034  8215 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 21:53:50.368  1034  8215 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 21:53:50.369  1942  8217 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-26 21:53:50.369  1942  8217 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 21:53:50.369  1034  1536 D LGWifiP2pService: InactiveState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-26 21:53:50.369  1034  1536 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-26 21:53:50.369  1034  1536 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-26 21:53:50.369  1034  1536 D LGWifiP2pService: InactiveState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
,08-26 21:53:50.369  1034  1536 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-26 21:53:50.369  1034  1536 D LGWifiP2pService: DefaultState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-26 21:53:50.369  1034  1034 E WifiServerServiceExt: No p2p device connected
08-26 21:53:50.369  1942  2307 W WfdsService: DefaultState - msg [9441285] is not handled
,08-26 21:53:50.370  6674  6764 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 21:53:50.370  6674  6764 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 21:53:50.370  6674  6764 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 21:53:50.370  6674  6764 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 21:53:50.370  6674  6764 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 21:53:50.370  6674  6764 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 21:53:50.370  6674  6764 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 21:53:50.370  6674  6764 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 21:53:50.370  1034  1975 W libprocessgroup: failed to open /acct/uid_10062/pid_7264/cgroup.procs: No such file or directory
08-26 21:53:50.370  8158  8158 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 21:53:50.371  1942  8217 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 21:53:50.371  1034  8215 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 21:53:50.371  1034  8215 E WifiMonitor: WifiMonitor:p2p0 cnt=53 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 21:53:50.371  1034  8215 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 21:53:50.371  1034  8215 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 21:53:50.372  6674  6764 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-26 21:53:50.373  1034  1537 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=143129  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-26 21:53:50.373  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 21:53:50.373  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 21:53:50.374  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 21:53:50.374  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 21:53:50.374  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 21:53:50.374  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-26 21:53:50.374  1034  1537 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-26 21:53:50.375  1034  1537 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-26 21:53:50.376  1034  1537 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-26 21:53:50.376  1034  1537 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-26 21:53:50.376  1034  1537 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-26 21:53:50.380  6674  6764 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
08-26 21:53:50.381  6674  6764 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-26 21:53:50.383  6674  6764 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@3383ce98 Bundle[{}]
08-26 21:53:50.383  6674  6764 I io.jxcore.node.LifeCycleMonitor: start: OK
08-26 21:53:50.384  6674  6764 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-,26 21:53:50.384  6674  6764 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-26 21:53:50.385  6674  6764 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-26 21:53:50.385  6674  6764 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-26 21:53:50.386  6674  6764 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-26 21:53:50.390  6674  6764 I System.out: Running OutgoingSocketThread
08-26 21:53:50.390  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 21:53:50.390  1034  1034 D WifiServerServiceExt: setSupplicantStateSCANNING
08-26 21:53:50.392  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 21:53:50.392  1034  1034 D WifiServerServiceExt: setSupplicantStateSCANNING
08-26 21:53:50.395  6674  8220 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 871)
08-26 21:53:50.397  8197  8197 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-26 21:53:50.398  6674  8220 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 58584
,08-26 21:53:50.398  6674  8220 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
08-26 21:53:50.400  6917  6917 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-26 21:53:50.403  8175  8222 W FormManager: Network not available. Please check & try again.
08-26 21:53:50.406  6917  6917 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 21:53:50.410  8175  8223 V FormManager: Network unavailable.
,08-26 21:53:50.416  8175  8223 V FormManager: Network unavailable.
08-26 21:53:50.422  4754  4754 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-26 21:53:50.422  4754  4754 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-26 21:53:50.423  4754  4754 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-26 21:53:50.425  4754  4754 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 21:53:50.430  4754  8224 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-26 21:53:50.431  4754  8225 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-26 21:53:50.431  4754  8225 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-26 21:53:50.483  1034  1614 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=8226 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-26 21:53:50.585  8226  8226 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-26 21:53:50.585  8226  8226 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-26 21:53:50.594  8226  8226 V [BNRBootReceiver]: Boot Receiver Return
,08-26 21:53:50.595  8226  8226 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-26 21:53:50.666  1034  1614 I ActivityManager: Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=8244 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-26 21:53:50.674  1034  1614 I ActivityManager: Killing 7285:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
08-26 21:53:50.722  1034  1959 W libprocessgroup: failed to open /acct/uid_10085/pid_7285/cgroup.procs: No such file or directory
,08-26 21:53:50.757  8244  8244 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-26 21:53:50.782  8244  8244 D PluginManager: init()
,08-26 21:53:50.828  1034  8215 E WifiMonitor: WifiMonitor:wlan0 cnt=54 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
,08-26 21:53:50.828  1034  8215 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-26 21:53:50.828  1034  8215 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
,08-26 21:53:50.828  1034  8215 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: WPS-AP-AVAILABLE 
08-26 21:53:50.828  1034  8215 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
,08-26 21:53:50.829  1034  1537 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
08-26 21:53:50.829  8158  8158 E wpa_supplicant: USIM:  scard_init function
08-26 21:53:50.829  1034  1537 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
,08-26 21:53:50.830  1034  1537 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
08-26 21:53:50.830  8158  8158 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-26 21:53:50.830  1034  1537 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
08-26 21:53:50.830  1034  1537 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-26 21:53:50.831  1034  8215 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-26 21:53:50.831  1034  8215 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
,08-26 21:53:50.850  1034  1537 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=143607  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-26 21:53:50.854  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 21:53:50.854  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 21:53:50.857  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 21:53:50.858  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 21:53:50.858  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 21:53:50.858  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-26 21:53:50.860  1034  1537 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=143616  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-26 21:53:50.862  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 21:53:50.862  1034  1034 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-26 21:53:50.953  8158  8158 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
08-26 21:53:50.953  1034  1105 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-26 21:53:50.959  1034  1537 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
08-26 21:53:50.960  1034  1537 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-26 21:53:50.960  1034  1537 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-26 21:53:50.961  1034  1537 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
,08-26 21:53:50.961  1034  1537 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-26 21:53:50.962  1034  8215 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-26 21:53:50.962  1034  8215 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-26 21:53:50.963  1034  8215 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-26 21:53:50.963  1034  8215 E WifiMonitor: WifiMonitor:wlan0 cnt=58 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-26 21:53:50.963  1034  8215 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-26 21:53:50.963  1034  8215 E WifiMonitor: WifiMonitor:wlan0 cnt=59 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-26 21:53:50.965  1034  1537 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=143721  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-26 21:53:50.967  1034  1537 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=143723  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-26 21:53:50.968  1034  1537 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=143725
08-26 21:53:50.969  8158  8158 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-26 21:53:50.969  8158  8158 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-26 21:53:50.969  1034  1537 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=143726
08-26 21:53:50.971  1034  1537 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=143727
08-26 21:53:50.972  1034  8215 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-26 21:53:50.973  1034  8215 E WifiMonitor: WifiMonitor:wlan0 cnt=60 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-26 21:53:50.973  1034  8215 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-26 21:53:50.973  1034  8215 E WifiMonitor: WifiMonitor:wlan0 cnt=61 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-26 21:53:50.974  1034  8215 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-26 21:53:50.974  1034  8215 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-26 21:53:50.974  1034  8215 E WifiMonitor: WifiMonitor:wlan0 cnt=62 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-26 21:53:50.974  1034  8215 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-26 21:53:50.975  1034  8215 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-26 21:53:50.975  1034  8215 E WifiMonitor: WifiMonitor:wlan0 cnt=63 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-26 21:53:50.977  1034  1537 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=143733
08-26 21:53:50.978  1034  1537 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=143734
08-26 21:53:50.978  1034  1537 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=143735  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
,08-26 21:53:50.981  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 21:53:50.981  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 21:53:50.982  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 21:53:50.982  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 21:53:50.982  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-26 21:53:50.983  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 21:53:50.983  1034  1537 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=143740  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-26 21:53:50.984  1034  1537 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=143741  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-26 21:53:50.985  1034  1537 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=143741  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-26 21:53:50.985  1034  1537 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=143742
08-26 21:53:50.986  1034  1537 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=143742
08-26 21:53:50.986  1034  1537 D WifiNative-wlan0: doString: [STATUS]
08-26 21:53:50.987  1034  8215 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-26 21:53:50.987  1034  8215 E WifiMonitor: WifiMonitor:wlan0 cnt=64 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-26 21:53:50.989  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 21:53:50.989  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 21:53:50.989  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-26 21:53:50.989  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 21:53:50.989  1034  1034 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-26 21:53:50.990  1034  1537 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-26 21:53:50.991  1034  1537 I WifiServiceExtension: setVHTCapabilityType  : false
,08-26 21:53:51.005  1034  1537 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
,08-26 21:53:51.005  1034  1537 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
,08-26 21:53:51.010  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 21:53:51.010  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 21:53:51.010  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-26 21:53:51.011  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 21:53:51.011  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 21:53:51.017  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-26 21:53:51.017  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 21:53:51.017  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-26 21:53:51.018  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 21:53:51.019  1034  1537 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-26 21:53:51.019  1034  1537 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-26 21:53:51.019  1034  1537 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-26 21:53:51.020  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 21:53:51.020  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 21:53:51.020  1034  1537 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-26 21:53:51.020  1034  1537 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-26 21:53:51.020  1034  1543 D ConnectivityService: Got NetworkAgent Messenger
08-26 21:53:51.020  1034  1543 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-26 21:53:51.020  1034  1543 D ConnectivityService: NetworkAgent connected
08-26 21:53:51.021  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-26 21:53:51.025  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 21:53:51.025  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 21:53:51.026  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 21:53:51.027  1034  1537 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-26 21:53:51.028  1034  1537 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-26 21:53:51.028  1034  1537 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-26 21:53:51.028  1034  1537 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-26 21:53:51.028  1034  1537 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-26 21:53:51.035  1034  1537 D WifiNative-wlan0: SAVE_CONFIG: returned true
,08-26 21:53:51.038   314   879 D CommandListener: Setting iface cfg
08-26 21:53:51.041  1034  1537 E WifiStateMachine: Start Dhcp Watchdog 3
08-26 21:53:51.041  1034  8269 D DhcpStateMachine: StoppedState
08-26 21:53:51.041  1034  8269 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-26 21:53:51.041  1034  8269 D DhcpStateMachine: WaitBeforeStartState
08-26 21:53:51.041  1034  1537 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=143797  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-26 21:53:51.042  1034  1537 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=143798  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-26 21:53:51.043  1034  1537 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=143799  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-26 21:53:51.044  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 21:53:51.044  1034  1034 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-26 21:53:51.045  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 21:53:51.045  1034  1034 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-26 21:53:51.045  1034  1537 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=143802  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-26 21:53:51.046  1034  1537 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=143803  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-26 21:53:51.047  1034  1537 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=143803  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-26 21:53:51.048  1034  1537 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:14121] from screen [on:0 period:-932551480] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-26 21:53:51.049  1034  1537 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-932551479] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-26 21:53:51.050  1034  1537 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-26 21:53:51.053  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 21:53:51.055  1034  1543 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
08-26 21:53:51.055  1034  1537 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 21:53:51.056  1034  1537 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 21:53:51.056  1034  1537 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 21:53:51.057  1034  1537 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 21:53:51.058  1034  1537 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0,
08-26 21:53:51.058  1034  1537 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 21:53:51.059  1034  1543 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-26 21:53:51.059  1034  1537 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=106,0,0
08-26 21:53:51.060  1034  1537 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=106,0,0
08-26 21:53:51.060  1034  1537 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
,08-26 21:53:51.060  8158  8158 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-26 21:53:51.061  1034  1537 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-26 21:53:51.061  1034  1537 D WifiNative-wlan0: doBoolean: SET ps 0
08-26 21:53:51.062  1034  1537 D WifiNative-wlan0: SET ps 0: returned true
08-26 21:53:51.062  1034  1537 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-26 21:53:51.062  8158  8158 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-26 21:53:51.062  1034  1537 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-26 21:53:51.062  1034  1537 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-26 21:53:51.062  1034  1537 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-26 21:53:51.063  1034  1536 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1cc44bec target=com.android.internal.util.StateMachine$SmHandler }
,08-26 21:53:51.063  1034  1537 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-26 21:53:51.063  1034  1536 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1cc44bec target=com.android.internal.util.StateMachine$SmHandler }
08-26 21:53:51.063  1034  8269 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-26 21:53:51.063  1034  8269 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-26 21:53:51.064   314   879 D CommandListener: Setting iface cfg
08-26 21:53:51.064   314   879 D CommandListener: Trying to bring up wlan0
08-26 21:53:51.065  1034  1537 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-26 21:53:51.066  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 21:53:51.066  1034  1034 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-26 21:53:51.067  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 21:53:51.067  1034  1034 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-26 21:53:51.068  1034  1537 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 21:53:51.068  1034  1537 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 21:53:51.069  1034  1537 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 21:53:51.069  1034  1537 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 21:53:51.070  1034  1537 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 21:53:51.070  1034  1537 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 21:53:51.071  1034  1543 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-26 21:53:51.071  1034  1537 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-26 21:53:51.072  1034  1537 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-26 21:53:51.072  1034  1536 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-26 21:53:51.072  1034  1536 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,08-26 21:53:51.073  1034  1537 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
,08-26 21:53:51.073  8158  8158 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-26 21:53:51.074  1034  1537 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-26 21:53:51.074  1034  1537 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-26 21:53:51.074  8158  8158 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-26 21:53:51.074  1034  1537 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-26 21:53:51.074  1034  1537 D WifiNative-wlan0: doBoolean: SET ps 1
08-26 21:53:51.091  1034  1537 D WifiNative-wlan0: SET ps 1: returned true
,08-26 21:53:51.092  1034  1537 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-26 21:53:51.092  1034  1537 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-26 21:53:51.092  1034  1537 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-26 21:53:51.093  1034  1543 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-26 21:53:51.093  1034  1543 D ConnectivityService: ignoring duplicate network state non-change
08-26 21:53:51.095  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 21:53:51.095  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 21:53:51.096  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 21:53:51.096  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 21:53:51.097  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 21:53:51.097  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-26 21:53:51.102  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 21:53:51.102  1034  1543 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-26 21:53:51.102  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 21:53:51.102  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-26 21:53:51.103  1034  1543 D ConnectivityService: Adding iface wlan0 to network 102
08-26 21:53:51.107  1034  1537 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-26 21:53:51.109  1034  1034 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
,08-26 21:53:51.113  1942  1942 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-26 21:53:51.118  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 21:53:51.118  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 21:53:51.120  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 21:53:51.120  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 21:53:51.120  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-26 21:53:51.120  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 21:53:51.122  1034  1034 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-26 21:53:51.122  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 21:53:51.122  1603  1603 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-26 21:53:51.123  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-26 21:53:51.128  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 21:53:51.128  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 21:53:51.128  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-26 21:53:51.128  1034  1543 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-26 21:53:51.128  1034  1543 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
08-26 21:53:51.129  1034  1543 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
08-26 21:53:51.130   314   879 E Netd    : netlink response contains error (File exists)
08-26 21:53:51.130  1034  1543 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
08-26 21:53:51.131  1034  1543 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-26 21:53:51.131  1034  1543 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 102
08-26 21:53:51.131  1034  1543 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
08-26 21:53:51.132  1034  1543 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-26 21:53:51.132  1034  1543 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-26 21:53:51.132  1034  1543 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-26 21:53:51.133  1034  8268 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-26 21:53:51.133  1034  8268 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-26 21:53:51.133  1034  8268 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-26 21:53:51.133  1034  8268 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-26 21:53:51.135  1034  1543 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-26 21:53:51.135   314  8274 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-26 21:53:51.135  1034  1543 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 21:53:51.135  1034  1543 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 21:53:51.135  1034  1543 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-26 21:53:51.135  1034  1543 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 21:53:51.135  1034  1543 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-26 21:53:51.135  1034  1543 D ConnectivityService: currentScore = 0, newScore = 20
,08-26 21:53:51.135  1034  1543 D ConnectivityService:    accepting network in place of null
08-26 21:53:51.135  1034  1543 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 21:53:51.136  1853  1853 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 21:53:51.136  1853  1853 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-26 21:53:51.137  1034  1537 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 21:53:51.137  1034  1537 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 21:53:51.137  1034  1543 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-26 21:53:51.138  1034  1543 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
08-26 21:53:51.138  1034  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-26 21:53:51.138  1034  1543 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-26 21:53:51.138  1034  1543 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-26 21:53:51.138  1034  1543 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,08-26 21:53:51.139  1034  1034 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-26 21:53:51.141  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 21:53:51.141  1603  1603 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-26 21:53:51.141  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 21:53:51.141  1034  1034 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-26 21:53:51.141  1034  1034 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-26 21:53:51.141  1034  1034 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-26 21:53:51.143  1034  1543 D ConnectivityService: validation of new default Network = false
08-26 21:53:51.143  1034  1543 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-26 21:53:51.143  1034  1543 D DSQN    : enableDataServiceNotify 
08-26 21:53:51.143  1034  1543 D DSQN    : start dsqn bin
08-26 21:53:51.153  1034  1535 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
,08-26 21:53:51.161  1603  1603 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-26 21:53:51.161  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 21:53:51.162  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 21:53:51.163  1034  1543 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-26 21:53:51.163  1034  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 21:53:51.163  1034  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 21:53:51.163  1034  1543 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 21:53:51.164  1603  1827 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-26 21:53:51.159  8275  8275 W dsqn    : type=1400 audit(0.0:193): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 21:53:51.159  8275  8275 W dsqn    : type=1400 audit(0.0:194): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 21:53:51.175  8275  8275 E DSQN    : DSQN ssw
,08-26 21:53:51.183   314  8274 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,08-26 21:53:51.214   314  8274 D libc-netbsd: res_queryN name = clients3.google.com succeed
,08-26 21:53:51.245   314   878 D LGDataListener: argv[0]=dsqncommand
08-26 21:53:51.245   314   878 D LGDataListener: argv[1]=wlan0
,08-26 21:53:51.245   314   878 D LGDataListener: argv[2]=1
,08-26 21:53:51.245   314   878 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
,08-26 21:53:51.246  1034  1103 D DSQN    : DSQM DsqnNotification wlan0  1
,08-26 21:53:51.246  1034  1103 D DSQN    : start to monitor internet connection
08-26 21:53:51.265  1034  8269 D DhcpStateMachine: DHCPV4 request on wlan0
,08-26 21:53:51.267  1034  8269 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-26 21:53:51.267  1034  8269 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
,08-26 21:53:51.282  1034  8268 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 26 Aug 2016 19:53:51 GMT], X-Android-Received-Millis=[1472241231281], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472241231244]}
,08-26 21:53:51.282  1034  8268 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-26 21:53:51.282  1034  8268 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-26 21:53:51.279  8281  8281 W dhcpcd  : type=1400 audit(0.0:195): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 21:53:51.279  8281  8281 W dhcpcd  : type=1400 audit(0.0:196): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-26 21:53:51.283  1034  1543 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-26 21:53:51.283  1034  1543 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 21:53:51.284  1034  1543 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 21:53:51.284  1034  1543 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-26 21:53:51.284  1034  1543 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
08-26 21:53:51.284  1034  1543 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-26 21:53:51.284  1034  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 21:53:51.284  1034  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 21:53:51.285  1034  1543 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 21:53:51.286  1603  1827 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-26 21:53:51.286  1034  1543 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 21:53:51.286  1034  1543 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-26 21:53:51.287  1853  1853 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 21:53:51.287  1853  1853 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-26 21:53:51.287  1034  1537 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 21:53:51.287  1034  1537 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 21:53:51.303  8244  8244 W ExternalStrings: load override strings
08-26 21:53:51.303  8244  8244 W ExternalStrings: java.lang.RuntimeException: Unexpected tag, got eat-comment
08-26 21:53:51.303  8244  8244 W ExternalStrings: 	at com.mcafee.plugin.af.a(Unknown Source)
08-26 21:53:51.303  8244  8244 W ExternalStrings: 	at com.mcafee.plugin.ac.b(Unknown Source)
08-26 21:53:51.303  8244  8244 W ExternalStrings: 	at com.mcafee.plugin.ak.d(Unknown Source)
08-26 21:53:51.303  8244  8244 W ExternalStrings: 	at com.mcafee.plugin.ak.a(Unknown Source)
08-26 21:53:51.303  8244  8244 W ExternalStrings: 	at com.mcafee.app.s.getClassLoader(Unknown Source)
08-26 21:53:51.303  8244  8244 W ExternalStrings: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
08-26 21:53:51.303  8244  8244 W ExternalStrings: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-26 21:53:51.303  8244  8244 W ExternalStrings: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-26 21:53:51.303  8244  8244 W ExternalStrings: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-26 21:53:51.303  8244  8244 W ExternalStrings: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-26 21:53:51.303  8244  8244 W ExternalStrings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 21:53:51.303  8244  8244 W ExternalStrings: 	at android.os.Looper.loop(Looper.java:135)
08-26 21:53:51.303  8244  8244 W ExternalStrings: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08,-26 21:53:51.303  8244  8244 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 21:53:51.303  8244  8244 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 21:53:51.303  8244  8244 W ExternalStrings: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-26 21:53:51.303  8244  8244 W ExternalStrings: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,08-26 21:53:51.304  8244  8244 D StatusProvider: onCreate
08-26 21:53:51.306  8281  8281 I dhcpcd  : version 5.5.6 starting
08-26 21:53:51.311  8281  8281 E dhcpcd  : get_duid: m
08-26 21:53:51.311  8281  8281 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-26 21:53:51.312  8281  8281 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,08-26 21:53:51.324  1603  1603 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-26 21:53:51.324  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 21:53:51.325  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 21:53:51.357  8244  8244 V Signer  : override build config not found
,08-26 21:53:51.357  8244  8244 D Signer  : value of property debug is false
08-26 21:53:51.384  8281  8281 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
,08-26 21:53:51.385  8281  8281 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
,08-26 21:53:51.385  8281  8281 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-26 21:53:51.385  8281  8281 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
08-26 21:53:51.385  8281  8281 D dhcpcd  : wlan0: sending REQUEST (xid 0xc3948852), next in 4.99 seconds
08-26 21:53:51.392  6674  6764 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 872)
08-26 21:53:51.392  6674  6764 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 872)
08-26 21:53:51.396  8244  8244 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
08-26 21:53:51.397  8244  8244 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
08-26 21:53:51.397  8244  8244 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
08-26 21:53:51.397  8244  8244 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
08-26 21:53:51.397  8244  8244 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
08-26 21:53:51.397  8244  8244 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
08-26 21:53:51.398  8244  8244 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
08-26 21:53:51.398  8244  8244 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
08-26 21:53:51.398  8244  8244 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
08-26 21:53:51.398  8244  8244 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
08-26 21:53:51.398  8244  8244 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
08-26 21:53:51.398  8244  8244 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
08-26 21:53:51.399  8244  8244 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
08-26 21:53:51.402  6674  6764 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 877)
08-26 21:53:51.404  6674  6764 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-26 21:53:51.404  6674  6764 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 878)
08-26 21:53:51.409  8244  8244 V LGMDMManager: Create singleton instance
,08-26 21:53:51.413  6674  6764 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 21:53:51.413  6674  6764 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b0fea47 added. We now have 2 listener(s)
08-26 21:53:51.414  1034  1898 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 21:53:51.416  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-26 21:53:51.417  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 21:53:51.417  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 21:53:51.417  6674  6764 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 21:53:51.417  6674  6764 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39129274 added. We now have 9 listener(s)
08-26 21:53:51.417  6674  6764 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 21:53:51.417  6674  6764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-26 21:53:51.421  6674  6764 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 21:53:51.425  6674  6764 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 21:53:51.425  6674  6764 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 21:53:51.425  6674  6764 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 21:53:51.425  6674  6764 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 21:53:51.425  6674  6764 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 21:53:51.425  6674  6764 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 21:53:51.425  6674  6764 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 21:53:51.425  6674  6764 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 21:53:51.427  6674  6764 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 21:53:51.427  6674  6764 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 21:53:51.428  6674  6764 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 21:53:51.428  6674  6764 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3dfbf012 added. We now have 3 listener(s)
08-26 21:53:51.429  6674  6674 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 21:53:51.429  1034  2030 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 21:53:51.430  6674  6674 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 21:53:51.431  8281  8281 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
08-26 21:53:51.434  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-26 21:53:51.434  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 21:53:51.434  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 21:53:51.434  6674  6764 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 21:53:51.434  6674  6764 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2756e3e3 added. We now have 10 listener(s)
08-26 21:53:51.434  6674  6764 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 21:53:51.434  6674  6764 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 21:53:51.434  6674  6764 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 21:53:51.435  6674  6764 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 21:53:51.435  6674  6764 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 21:53:51.435  6674  6764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:51.435  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 21:53:51.435  6674  6764 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 21:53:51.435  6674  6764 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b0fea47 removed from the list
08-26 21:53:51.435  6674  6764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:53:51.435  6674  6764 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39129274 removed from the list
08-26 21:53:51.435  6674  6764 D io.jxcore.node.ConnectivityMonitor: stop
08-26 21:53:51.435  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:53:51.436  6674  6764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener, does not exist in the list - probably already removed
08-26 21:53:51.436  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:53:51.436  6674  6764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 21:53:51.436  6674  6764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 21:53:51.436  6674  6764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:53:51.436  6674  6764 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39129274 not in the list
08-26 21:53:51.436  6674  6764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:51.436  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:53:51.437  6674  6764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 21:53:51.437  6674  6764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 21:53:51.437  6674  6764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:53:51.437  6674  6764 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2756e3e3 removed from the list
08-26 21:53:51.437  6674  6764 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 21:53:51.437  6674  6764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:51.437  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:53:51.437  6674  6764 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 21:53:51.437  6674  6764 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3dfbf012 removed from the list
08-26 21:53:51.438  6674  6764 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 21:53:51.438  6674  6764 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e0061e0 added. We now have 2 listener(s)
08-26 21:53:51.438  1034  1614 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 21:53:51.441  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-26 21:53:51.441  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 21:53:51.441  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 21:53:51.441  6674  6764 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 21:53:51.441  6674  6764 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@373c1c99 added. We now have 9 listener(s)
08-26 21:53:51.441  6674  6764 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 21:53:51.442  6674  6764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-26 21:53:51.446  6674  6764 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 21:53:51.449  6674  6764 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 21:53:51.449  6674  6764 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 21:53:51.449  6674  6764 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 21:53:51.449  6674  6764 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 21:53:51.449  6674  6764 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 21:53:51.449  6674  6764 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 21:53:51.449  6674  6764 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 21:53:51.449  6674  6764 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 21:53:51.451  6674  6764 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 21:53:51.451  6674  6764 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 21:53:51.451  6674  6764 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 21:53:51.451  6674  6764 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f89db3f added. We now have 3 listener(s)
08-26 21:53:51.452  1034  1975 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 21:53:51.453  8281  8281 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
08-26 21:53:51.453  8281  8281 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
08-26 21:53:51.453  6674  6674 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 21:53:51.453  8281  8281 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-26 21:53:51.454  8281  8281 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-26 21:53:51.454  8281  8281 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-26 21:53:51.454  8281  8281 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-26 21:53:51.454  8281  8281 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-26 21:53:51.454  8281  8281 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-26 21:53:51.456  6674  6674 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 21:53:51.461  8244  8244 D LGMDMWrapper: LG MDM library v4.0.0 is available on this device.
08-26 21:53:51.461  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-26 21:53:51.461  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 21:53:51.461  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 21:53:51.462  6674  6764 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 21:53:51.462  6674  6764 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1039bc0c added. We now have 10 listener(s)
08-26 21:53:51.462  6674  6764 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 21:53:51.462  6674  6764 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 21:53:51.462  6674  6764 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 21:53:51.462  6674  6764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 21:53:51.462  6674  6764 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 21:53:51.462  6674  6764 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-26 21:53:51.465  6674  6764 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-26 21:53:51.466  1034  1050 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 21:53:51.471  6674  6764 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-26 21:53:51.472  6674  6764 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-26 21:53:51.473  6674  6764 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-26 21:53:51.474  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 21:53:51.475  6674  6764 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-26 21:53:51.475  6674  6764 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 21:53:51.476  6674  6764 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 21:53:51.478  6674  6764 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 21:53:51.478  6674  6764 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 21:53:51.478  6674  6764 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 21:53:51.478  6674  6764 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 21:53:51.478  6674  6764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:51.478  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 21:53:51.478  6674  6764 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 21:53:51.478  6674  6764 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e0061e0 removed from the list
08-26 21:53:51.478  6674  6764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:53:51.478  6674  6764 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@373c1c99 removed from the list
08-26 21:53:51.478  6674  6764 D io.jxcore.node.ConnectivityMonitor: stop
08-26 21:53:51.478  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:53:51.479  6674  6764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:51.479  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:53:51.480  6674  6764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 21:53:51.480  6674  6764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 21:53:51.480  6674  6764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:53:51.480  6674  6764 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@373c1c99 not in the list
08-26 21:53:51.480  6674  6764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:51.480  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:53:51.481  6674  6764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 21:53:51.481  6674  6764 D BluetoothLeScanner: could not find callback wrapper
08-26 21:53:51.481  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stop,ped
08-26 21:53:51.481  6674  6764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 21:53:51.482  6674  6764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:53:51.482  6674  6764 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1039bc0c removed from the list
08-26 21:53:51.482  6674  6764 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 21:53:51.482  6674  6764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:51.482  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:53:51.482  6674  6764 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 21:53:51.482  6674  6764 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f89db3f removed from the list
08-26 21:53:51.482  6674  6764 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 21:53:51.483  6674  6764 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@17caec5b added. We now have 2 listener(s)
08-26 21:53:51.483  1034  2033 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 21:53:51.485  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-26 21:53:51.485  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 21:53:51.485  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 21:53:51.486  6674  6764 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 21:53:51.486  6674  6764 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ecc8cf8 added. We now have 9 listener(s)
08-26 21:53:51.486  6674  6764 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 21:53:51.486  6674  6764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-26 21:53:51.489  6674  6764 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 21:53:51.494  6674  6764 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 21:53:51.494  6674  6764 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 21:53:51.494  6674  6764 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 21:53:51.494  6674  6764 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 21:53:51.494  6674  6764 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 21:53:51.494  6674  6764 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 21:53:51.494  6674  6764 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 21:53:51.494  6674  6764 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 21:53:51.495  6674  6764 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 21:53:51.495  6674  6764 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 21:53:51.496  6674  6764 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 21:53:51.496  6674  6764 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@277f1836 added. We now have 3 listener(s)
,08-26 21:53:51.496  1034  1995 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0,
,08-26 21:53:51.497  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-26 21:53:51.498  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 21:53:51.498  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 21:53:51.498  6674  6764 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 21:53:51.498  6674  6764 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a41f337 added. We now have 10 listener(s)
,08-26 21:53:51.498  6674  6764 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 21:53:51.498  6674  6764 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 21:53:51.498  6674  6764 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 21:53:51.498  6674  6764 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 21:53:51.498  6674  6764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-26 21:53:51.498  6674  6764 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 21:53:51.499  6674  6764 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-26 21:53:51.501  6674  6674 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 21:53:51.502  6674  6764 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-26 21:53:51.502  1034  2030 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 21:53:51.504  6674  6674 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 21:53:51.507  6674  6764 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-26 21:53:51.507  6674  6764 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-26 21:53:51.511  6674  6764 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-26 21:53:51.512  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 21:53:51.514  6674  6764 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,08-26 21:53:51.514  6674  6764 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 21:53:51.514  6674  6764 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 21:53:51.514  6674  6764 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 21:53:51.515  6674  6764 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 21:53:51.515  6674  6764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:51.515  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 21:53:51.515  6674  6764 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 21:53:51.515  6674  6764 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@17caec5b removed from the list
08-26 21:53:51.515  6674  6764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:53:51.515  6674  6764 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ecc8cf8 removed from the list
08-26 21:53:51.515  6674  6764 D io.jxcore.node.ConnectivityMonitor: stop
08-26 21:53:51.515  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:53:51.515  6674  6764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:51.515  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:53:51.516  6674  6764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 21:53:51.516  6674  6764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 21:53:51.516  6674  6764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:53:51.516  6674  6764 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ecc8cf8 not in the list
08-26 21:53:51.516  6674  6764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:51.516  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:53:51.516  6674  6764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 21:53:51.517  6674  6764 D BluetoothLeScanner: could not find callback wrapper
08-26 21:53:51.517  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 21:53:51.517  6674  6764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 21:53:51.517  6674  6764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:53:51.517  6674  6764 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a41f337 removed from the list
08-26 21:53:51.517  6674  6764 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 21:53:51.517  6674  6764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:51.517  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 ,21:53:51.517  6674  6764 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 21:53:51.517  6674  6764 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@277f1836 removed from the list
08-26 21:53:51.517  6674  6764 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 21:53:51.517  6674  6764 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@81c81c2 added. We now have 2 listener(s)
08-26 21:53:51.518  1034  1898 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 21:53:51.519  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-26 21:53:51.519  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 21:53:51.519  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 21:53:51.519  6674  6764 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 21:53:51.519  6674  6764 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b88bd3 added. We now have 9 listener(s)
08-26 21:53:51.519  6674  6764 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 21:53:51.520  6674  6764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-26 21:53:51.521  6674  6764 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 21:53:51.524  6674  6764 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 21:53:51.524  6674  6764 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 21:53:51.524  6674  6764 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 21:53:51.524  6674  6764 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 21:53:51.524  6674  6764 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 21:53:51.524  6674  6764 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 21:53:51.524  6674  6764 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 21:53:51.524  6674  6764 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 21:53:51.525  6674  6764 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 21:53:51.525  6674  6764 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 21:53:51.526  6674  6764 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 21:53:51.526  6674  6764 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2e305e09 added. We now have 3 listener(s)
08-26 21:53:51.527  1034  1049 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 21:53:51.527  6674  6674 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 21:53:51.529  6674  6674 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 21:53:51.530  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-26 21:53:51.530  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 21:53:51.530  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 21:53:51.530  6674  6764 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 21:53:51.530  6674  6764 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b34f80e added. We now have 10 listener(s)
08-26 21:53:51.530  6674  6764 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 21:53:51.530  6674  6764 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 21:53:51.530  6674  6764 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 21:53:51.530  6674  6764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 21:53:51.530  6674  6764 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 21:53:51.530  6674  6764 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-26 21:53:51.533  6674  6764 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-26 21:53:51.533  1034  1898 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 21:53:51.536  6674  6764 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-26 21:53:51.537  6674  6764 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-26 21:53:51.538  6674  6764 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-26 21:53:51.539  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 21:53:51.540  6674  6764 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,08-26 21:53:51.542  6674  6764 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 21:53:51.542  6674  6764 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 21:53:51.542  6674  6764 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 21:53:51.542  6674  6764 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 21:53:51.542  6674  6764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:51.542  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 21:53:51.542  6674  6764 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 21:53:51.543  6674  6764 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@81c81c2 removed from the list
08-26 21:53:51.543  6674  6764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:53:51.543  6674  6764 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b88bd3 removed from the list
08-26 21:53:51.543  6674  6764 D io.jxcore.node.ConnectivityMonitor: stop
08-26 21:53:51.543  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:53:51.543  6674  6764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:51.543  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:53:51.544  6674  6764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 21:53:51.544  6674  6764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 21:53:51.544  6674  6764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:53:51.544  6674  6764 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b88bd3 not in the list
08-26 21:53:51.544  6674  6764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:51.544  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:53:51.545  6674  6764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 21:53:51.545  6674  6764 D BluetoothLeScanner: could not find callback wrapper
08-26 21:53:51.545  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 21:53:51.545  6674  6764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 21:53:51.545  6674  6764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:53:51.545  6674  6764 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b34f80e removed from the list
08-26 21:53:51.545  6674  6764 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 21:53:51.545  6674  6764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:51.545  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:,53:51.545  6674  6764 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 21:53:51.545  6674  6764 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2e305e09 removed from the list
08-26 21:53:51.546  6674  6764 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 21:53:51.546  6674  6764 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3877d1c5 added. We now have 2 listener(s)
08-26 21:53:51.547  1034  1887 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 21:53:51.548  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-26 21:53:51.548  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 21:53:51.548  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 21:53:51.548  6674  6764 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 21:53:51.548  6674  6764 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@104c871a added. We now have 9 listener(s)
08-26 21:53:51.548  6674  6764 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 21:53:51.548  6674  6764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-26 21:53:51.550  6674  6764 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 21:53:51.553  6674  6764 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 21:53:51.553  6674  6764 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 21:53:51.553  6674  6764 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 21:53:51.553  6674  6764 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 21:53:51.553  6674  6764 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 21:53:51.553  6674  6764 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 21:53:51.553  6674  6764 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 21:53:51.553  6674  6764 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 21:53:51.554  6674  6764 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 21:53:51.554  6674  6764 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 21:53:51.555  6674  6764 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 21:53:51.555  6674  6764 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ef92428 added. We now have 3 listener(s)
08-26 21:53:51.555  1034  1921 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 21:53:51.556  6674  6674 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 21:53:51.557  6674  6674 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 21:53:51.559  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-26 21:53:51.559  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 21:53:51.559  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 21:53:51.559  6674  6764 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 21:53:51.559  6674  6764 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1808c541 added. We now have 10 listener(s)
08-26 21:53:51.559  6674  6764 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 21:53:51.560  6674  6764 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 21:53:51.560  6674  6764 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 21:53:51.560  6674  6764 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 21:53:51.560  6674  6764 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 21:53:51.560  6674  6764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:51.560  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 21:53:51.560  6674  6764 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 21:53:51.560  6674  6764 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3877d1c5 removed from the list
08-26 21:53:51.560  6674  6764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:53:51.560  6674  6764 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@104c871a removed from the list
08-26 21:53:51.560  6674  6764 D io.jxcore.node.ConnectivityMonitor: stop
08-26 21:53:51.560  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:53:51.561  6674  6764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:51.561  6674  6764 D org.th,aliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:53:51.561  6674  6764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 21:53:51.561  6674  6764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 21:53:51.561  6674  6764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:53:51.561  6674  6764 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@104c871a not in the list
08-26 21:53:51.561  6674  6764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:51.561  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:53:51.562  6674  6764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 21:53:51.562  6674  6764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 21:53:51.562  6674  6764 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:53:51.562  6674  6764 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1808c541 removed from the list
08-26 21:53:51.562  6674  6764 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 21:53:51.562  6674  6764 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:51.562  6674  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:53:51.562  6674  6764 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-26 21:53:51.562  6674  6764 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ef92428 removed from the list
08-26 21:53:51.562  6674  6764 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-26 21:53:51.563  6674  6764 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-26 21:53:51.563  6674  6764 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-26 21:53:51.563  8244  8300 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-26 21:53:51.563  6674  6764 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-26 21:53:51.563  6674  6764 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-26 21:53:51.563  6674  6764 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-26 21:53:51.564  8244  8244 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-26 21:53:51.573  6917  6917 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-26 21:53:51.574  6674  8307 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 885, name: My test thread name)
08-26 21:53:51.574  6674  8307 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 885, thread name: My test thread name)
08-26 21:53:51.574  6674  8307 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 885, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-26 21:53:51.576  6674  8308 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 887, name: My test thread name)
08-26 21:53:51.577  6674  8308 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 887, thread name: My test thread name)
08-26 21:53:51.577  6674  8308 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 887, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-26 21:53:51.578  6674  6764 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-26 21:53:51.578  6674  6764 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-26 21:53:51.578  6674  6764 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-26 21:53:51.578  6674  6764 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-26 21:53:51.578  6674  6764 D com.test.thalitest.ThaliTestRunner: Total duration: 22882 ms
08-26 21:53:51.579  6674  6764 I jxcore-log: *Native tests were executed*
08-26 21:53:51.579  6674  6764 I jxcore-log: 
08-26 21:53:51.579  6674  6764 I jxcore-log: Total number of executed tests:  80
08-26 21:53:51.579  6674  6764 I jxcore-log: 
08-26 21:53:51.579  6674  6764 I jxcore-log: Number of passed tests:  80
08-26 21:53:51.579  6674  6764 I jxcore-log: 
08-26 21:53:51.579  6674  6764 I jxcore-log: Number of failed tests:  0
08-26 21:53:51.579  6674  6764 I jxcore-log: 
08-26 21:53:51.579  6674  6764 I jxcore-log: Number of ignored tests:  0
08-26 21:53:51.579  6674  6764 I jxcore-log: 
,08-26 21:53:51.580  6674  6764 I jxcore-log: Total duration:  22882
08-26 21:53:51.580  6674  6764 I jxcore-log: 
08-26 21:53:51.580  6674  6764 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-26 21:53:51.580  6674  6764 I jxcore-log: 
08-26 21:53:51.582  6674  6764 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 21:53:51.582  6674  6764 I jxcore-log: 
,08-26 21:53:51.585  6674  6764 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 21:53:51.585  6674  6764 I jxcore-log: 
08-26 21:53:51.586  6674  6764 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 21:53:51.586  6674  6764 I jxcore-log: 
08-26 21:53:51.586  6674  6764 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 21:53:51.586  6674  6764 I jxcore-log: 
08-26 21:53:51.587  6674  6764 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 21:53:51.587  6674  6764 I jxcore-log: 
08-26 21:53:51.588  6674  6764 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-26 21:53:51.588  6674  6764 I jxcore-log: 
08-26 21:53:51.592  6917  6917 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 21:53:51.592  6674  6674 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-26 21:53:51.593  6674  6764 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-26 21:53:51.593  6674  6764 I jxcore-log: 
08-26 21:53:51.595  6674  6764 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 21:53:51.595  6674  6764 I jxcore-log: 
08-26 21:53:51.596  6674  6764 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 21:53:51.596  6674  6764 I jxcore-log: 
08-26 21:53:51.597  6674  6764 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-26 21:53:51.597  6674  6764 I jxcore-log: 
08-26 21:53:51.598  6674  6764 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-26 21:53:51.598  6674  6764 I jxcore-log: 
,08-26 21:53:51.601  6674  6764 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-26 21:53:51.601  6674  6764 I jxcore-log: 
08-26 21:53:51.602  6674  6764 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 21:53:51.602  6674  6764 I jxcore-log: 
08-26 21:53:51.603  6674  6764 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 21:53:51.603  6674  6764 I jxcore-log: 
08-26 21:53:51.604  6674  6764 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 21:53:51.604  6674  6764 I jxcore-log: 
08-26 21:53:51.604  6674  6764 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 21:53:51.604  6674  6764 I jxcore-log: 
08-26 21:53:51.605  6674  6764 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 21:53:51.605  6674  6764 I jxcore-log: 
08-26 21:53:51.606  6674  6764 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 21:53:51.606  6674  6764 I jxcore-log: 
08-26 21:53:51.607  6674  6764 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 21:53:51.607  6674  6764 I jxcore-log: 
,08-26 21:53:51.609  6674  6764 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 21:53:51.609  6674  6764 I jxcore-log: 
08-26 21:53:51.610  6674  6764 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-26 21:53:51.610  6674  6764 I jxcore-log: 
08-26 21:53:51.610  6674  6764 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-26 21:53:51.610  6674  6764 I jxcore-log: 
08-26 21:53:51.611  6674  6764 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 21:53:51.611  6674  6764 I jxcore-log: 
08-26 21:53:51.612  6674  6764 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 21:53:51.612  6674  6764 I jxcore-log: 
08-26 21:53:51.613  6674  6764 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 21:53:51.613  6674  6764 I jxcore-log: 
08-26 21:53:51.614  6674  6764 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 21:53:51.614  6674  6764 I jxcore-log: 
08-26 21:53:51.615  6674  6764 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 21:53:51.615  6674  6764 I jxcore-log: 
08-26 21:53:51.632  1034  1898 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=8314 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
08-26 21:53:51.632  1034  1898 I ActivityManager: Killing 7317:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
,08-26 21:53:51.637   345   345 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 197us total 9.463ms
08-26 21:53:51.647   345   345 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 194us total 9.144ms
08-26 21:53:51.657   345   345 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 193us total 9.134ms
,08-26 21:53:51.672  1034  8269 D DhcpStateMachine: DHCPV4 succeeded on wlan0
08-26 21:53:51.673  1034  8269 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-26 21:53:51.673  1034  8269 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-26 21:53:51.674  1034  8269 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
08-26 21:53:51.674  1034  8269 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-26 21:53:51.674  1034  8269 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-26 21:53:51.674  1034  8269 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-26 21:53:51.674  1034  8269 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-26 21:53:51.674  1034  8269 D DhcpStateMachine: RunningState
,08-26 21:53:51.693  8244  8299 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-26 21:53:51.780  8333  8333 D AndroidRuntime: 
08-26 21:53:51.780  8333  8333 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-26 21:53:51.783  8333  8333 D AndroidRuntime: CheckJNI is OFF
,08-26 21:53:51.907  1034  1050 W libprocessgroup: failed to open /acct/uid_10093/pid_7317/cgroup.procs: No such file or directory
,08-26 21:53:51.910  8333  8333 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-26 21:53:51.926  1034  1091 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
08-26 21:53:51.926  1034  1091 I ActivityManager: Killing 6674:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
,08-26 21:53:51.935  8314  8314 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-26 21:53:51.959  1034  1887 I WindowState: WIN DEATH: Window{2c891ce8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-26 21:53:51.959  1034  1542 D WifiService: Client connection lost with reason: 4
,08-26 21:53:51.964  1034  1887 D InputDispatcher: Window went away: Window{2c891ce8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-26 21:53:52.037  1034  1091 I ActivityManager:   Force finishing activity ActivityRecord{3145996e u0 com.test.thalitest/.MainActivity t6}
,08-26 21:53:52.100   341   352 E GBMv2   : DFP En is all cleared set to be enabled
,08-26 21:53:52.104  1034  1049 W ActivityManager: Spurious death for ProcessRecord{1f75a7d9 6674:com.test.thalitest/u0a118}, curProc for 6674: null
08-26 21:53:52.108  1034  1123 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
08-26 21:53:52.113  1034  1123 I ActivityManager:   Force finishing activity ActivityRecord{3145996e u0 com.test.thalitest/.MainActivity t6 f}
08-26 21:53:52.113  1034  1123 W ActivityManager: Duplicate finish request for ActivityRecord{3145996e u0 com.test.thalitest/.MainActivity t6 f}
,08-26 21:53:52.139  2034  2034 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
08-26 21:53:52.139  1942  4399 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
08-26 21:53:52.139  1942  4399 D SplitWindowPolicy: topRunningActivity=ActivityInfo{2b654c82 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-26 21:53:52.140  2034  2034 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
08-26 21:53:52.142  1942  1957 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
08-26 21:53:52.142  1942  1957 D SplitWindowPolicy: topRunningActivity=ActivityInfo{5fd5f93 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-26 21:53:52.142  8314  8314 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
08-26 21:53:52.142  2034  2034 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
,08-26 21:53:52.144  2034  2126 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
08-26 21:53:52.146  1603  1603 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
08-26 21:53:52.154  7821  7821 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
08-26 21:53:52.154  7821  7821 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-26 21:53:52.156  1996  1996 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-26 21:53:52.157  3770  3770 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
08-26 21:53:52.161  2481  2648 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-26 21:53:52.162  1034  1436 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-26 21:53:52.178  5021  5021 I art     : Explicit concurrent mark sweep GC freed 8220(470KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 29MB/45MB, paused 541us total 52.572ms
,08-26 21:53:52.214  1034  1034 D administrator: Handling package changes for user 0
,08-26 21:53:52.216  1906  1906 D ActionManagerService: notifyUserLog: 1000003
08-26 21:53:52.216  3770  4929 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
08-26 21:53:52.217  2034  2034 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
08-26 21:53:52.219  2034  2034 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
08-26 21:53:52.218  4909  4909 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-26 21:53:52.220  4909  4909 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-26 21:53:52.220  4909  4909 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-26 21:53:52.220  4909  4909 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-26 21:53:52.220  4909  4909 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-26 21:53:52.220  4909  4909 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-26 21:53:52.220  4909  4909 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-26 21:53:52.220  4909  4909 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-26 21:53:52.220  4909  4909 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 21:53:52.220  4909  4909 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 21:53:52.220  4909  4909 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-26 21:53:52.220  4909  4909 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-26 21:53:52.235  2034  2034 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
,08-26 21:53:52.258  2034  2034 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
08-26 21:53:52.258  1603  1651 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-26 21:53:52.258  1603  1651 D KeyguardModel: createShortcutInfo...
,08-26 21:53:52.261  2034  2034 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
08-26 21:53:52.261  1906  1906 D ActionManagerService: notifyUserLog: 1000004
08-26 21:53:52.262  3770  4929 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
08-26 21:53:52.262  1603  1603 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
08-26 21:53:52.263  1603  1651 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-26 21:53:52.263  1603  1651 D KeyguardModel: createShortcutInfo...
08-26 21:53:52.264  3770  3785 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-26 21:53:52.267  2034  2034 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-26 21:53:52.267  2034  2034 I GBoardWebViewUtils: , create_time: 1430832262123
08-26 21:53:52.267  2034  2034 I GBoardWebViewUtils: , expire_time: 0
08-26 21:53:52.267  2034  2034 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-26 21:53:52.267  2034  2034 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-26 21:53:52.267  2034  2034 I GBoardWebViewUtils: , display: false
08-26 21:53:52.267  2034  2034 I GBoardWebViewUtils: , animation: false }
08-26 21:53:52.267  2034  2034 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-26 21:53:52.267  2034  2034 I GBoardWebViewUtils: , create_time: 1430832262287
08-26 21:53:52.267  2034  2034 I GBoardWebViewUtils: , expire_time: 0
08-26 21:53:52.267  2034  2034 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-26 21:53:52.267  2034  2034 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-26 21:53:52.267  2034  2034 I GBoardWebViewUtils: , display: false
08-26 21:53:52.267  2034  2034 I GBoardWebViewUtils: , animation: false }
08-26 21:53:52.267  2034  2034 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1472216587976
08-26 21:53:52.267  2034  2034 I GBoardWebViewUtils: , create_time: 1472216588858
08-26 21:53:52.267  2034  2034 I GBoardWebViewUtils: , expire_time: 0
08-26 21:53:52.267  2034  2034 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide.html?id=guide_1111111111116_1472216587976&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-26 21:53:52.267  2034  2034 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-26 21:53:52.267  2034  2034 I GBoardWebViewUtils: , display: false
08-26 21:53:52.267  2034  2034 I GBoardWebViewUtils: , animation: false }
08-26 21:53:52.269  1603  1651 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
,08-26 21:53:52.273  1603  1651 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-26 21:53:52.273  1603  1651 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-26 21:53:52.274  1603  1651 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-26 21:53:52.275  2034  8355 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
08-26 21:53:52.284  8314  8314 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
08-26 21:53:52.285  8314  8314 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-26 21:53:52.285  8314  8314 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-26 21:53:52.285  8314  8314 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
,08-26 21:53:52.285  8314  8314 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-26 21:53:52.286  8314  8314 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-26 21:53:52.288  1870  1870 D SplitUIManager: split_name #11 / not available #0
08-26 21:53:52.288  1870  1870 D SplitUIService: removed split : 
08-26 21:53:52.292  1603  1651 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-26 21:53:52.292  1603  1651 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-26 21:53:52.293  1603  1651 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-26 21:53:52.293  1034  1049 V SIM_STK : Menu title from STK is T-Mobile
08-26 21:53:52.293  1603  1651 D KeyguardModel: createShortcutInfo...
08-26 21:53:52.293  1034  1049 V SIM_STK : Menu title from STK is T-Mobile
08-26 21:53:52.298  1603  1651 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-26 21:53:52.298  1603  1651 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-26 21:53:52.299  1603  1651 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-26 21:53:52.299  1603  1651 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
,08-26 21:53:52.300  8314  8314 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-26 21:53:52.303  1603  1651 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-26 21:53:52.303  1603  1651 D KeyguardModel: createShortcutInfo...
08-26 21:53:52.307  1603  1651 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-26 21:53:52.307  1603  1651 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-26 21:53:52.307  1603  1651 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-26 21:53:52.307  1603  1651 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-26 21:53:52.312  1603  1651 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-26 21:53:52.312  1603  1651 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-26 21:53:52.312  1603  1603 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-26 21:53:52.312  1603  1603 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
,08-26 21:53:52.314  1603  1651 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-26 21:53:52.314  1603  1651 D KeyguardModel: createShortcutInfo...
08-26 21:53:52.322  2034  2034 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-26 21:53:52.323  2034  2034 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
08-26 21:53:52.333  1034  2033 V SIM_STK : Menu title from STK is T-Mobile
08-26 21:53:52.334  1603  1603 D KeyguardModel: handleShortcutListChanged...
08-26 21:53:52.334  1603  1603 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
,08-26 21:53:52.338  1603  1651 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-26 21:53:52.339  1603  1651 D KeyguardModel: createShortcutInfo...
08-26 21:53:52.345  1870  1870 D SplitUIManager: split_name #11 / not available #0
08-26 21:53:52.345  1870  1870 I SplitUIService: split app #11
08-26 21:53:52.345  1603  1651 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-26 21:53:52.345  1603  1651 D KeyguardModel: createShortcutInfo...
08-26 21:53:52.346  1603  1651 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-26 21:53:52.347  1603  1651 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-26 21:53:52.348  1603  1651 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-26 21:53:52.348  1603  1651 D KeyguardModel: createShortcutInfo...
08-26 21:53:52.349  1603  1651 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-26 21:53:52.349  1603  1651 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-26 21:53:52.350  1603  1651 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-26 21:53:52.350  1603  1651 D KeyguardModel: createShortcutInfo...
08-26 21:53:52.351  1603  1651 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-26 21:53:52.351  1603  1651 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-26 21:53:52.352  1603  1651 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-26 21:53:52.352  1603  1651 D KeyguardModel: createShortcutInfo...
08-26 21:53:52.356  1034  1050 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-26 21:53:52.356  7821  7821 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-26 21:53:52.356  7821  7821 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-26 21:53:52.356  7821  7821 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-26 21:53:52.356  7821  7821 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-26 21:53:52.356  7821  7821 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-26 21:53:52.356  7821  7821 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-26 21:53:52.356  7821  7821 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-26 21:53:52.356  7821  7821 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-26 21:53:52.356  7821  7821 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-26 21:53:52.356  7821  7821 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-26 21:53:52.356  7821  7821 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
,08-26 21:53:52.369  8314  8314 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 21:53:52.370  8314  8314 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 21:53:52.378  1034  1034 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-26 21:53:52.379  1034  1034 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-26 21:53:52.379  1034  1034 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-26 21:53:52.386  1034  1578 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
08-26 21:53:52.393  1603  1603 D KeyguardModel: handleShortcutListChanged...
08-26 21:53:52.393  1603  1603 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-26 21:53:52.395  8314  8314 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-26 21:53:52.399  8314  8314 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-26 21:53:52.403  8244  8244 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 21:53:52.403  8244  8300 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-26 21:53:52.421  1034  2033 V SIM_STK : Menu title from STK is T-Mobile
,08-26 21:53:52.421  2034  2034 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
08-26 21:53:52.426  8314  8314 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-26 21:53:52.432  6917  6917 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 21:53:52.434  6917  6917 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 21:53:52.435  8244  8299 D LgDataFeature: LgDataFeature() Constructor: none
08-26 21:53:52.438  8314  8314 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 21:53:52.438  8314  8314 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 21:53:52.439  8314  8314 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-26 21:53:52.440  6917  6917 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
08-26 21:53:52.441  8244  8299 D LgDataFeature: LgDataFeature() Constructor Done, null
08-26 21:53:52.442  6917  6917 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-26 21:53:52.443  8244  8244 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 21:53:52.443  8244  8300 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-26 21:53:52.446  6917  6917 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 21:53:52.448  1034  1123 I art     : Explicit concurrent mark sweep GC freed 78610(4MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 43MB/65MB, paused 1.898ms total 306.990ms
08-26 21:53:52.450  6917  6917 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 21:53:52.455  8314  8314 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 21:53:52.455  8314  8314 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 21:53:52.455  8314  8314 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-26 21:53:52.461  6917  6917 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-26 21:53:52.461  6917  6917 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-26 21:53:52.461  6917  6917 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-26 21:53:52.461  6917  6917 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
,08-26 21:53:52.461  6917  6917 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-26 21:53:52.462  6917  6917 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-26 21:53:52.463  6917  6917 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-26 21:53:52.463  6917  6917 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-26 21:53:52.463  6917  6917 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-26 21:53:52.463  6917  6917 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-26 21:53:52.463  6917  6917 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-26 21:53:52.463  6917  6917 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-26 21:53:52.467  8244  8244 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 21:53:52.467  8244  8300 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-26 21:53:52.471   335   415 I ThermalEngine: Thermal-Server: Thermal received msg from  override
08-26 21:53:52.471  3293  8362 I Thermal-Lib: Thermal-Lib-Client: Client request sent
,08-26 21:53:52.484  8333  8333 D AndroidRuntime: Shutting down VM
,08-26 21:53:52.497  2034  2034 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,08-26 21:53:52.503  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-26 21:53:52.504  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
08-26 21:53:52.506  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-26 21:53:52.506  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-26 21:53:52.507  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
08-26 21:53:52.508  6917  6917 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 21:53:52.518  6917  6917 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 21:53:52.523  2034  2034 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
08-26 21:53:52.523  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-26 21:53:52.539  2034  2162 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-26 21:53:52.539  2034  2162 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
,08-26 21:53:52.542  1034  1123 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8364 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
08-26 21:53:52.545  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
08-26 21:53:52.546  2034  2034 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-26 21:53:52.546  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-26 21:53:52.546  1034  1107 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2c4fb256 u0 com.lge.launcher2/.Launcher t5} time:145314
08-26 21:53:52.554  2034  2034 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
,08-26 21:53:52.555  8314  8314 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 21:53:52.555  8314  8314 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 21:53:52.555  2619  2619 D [Concierge]Service: onStartCommand(). Type : 8
08-26 21:53:52.555  2619  2619 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
08-26 21:53:52.555  8314  8314 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-26 21:53:52.557  8244  8244 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 21:53:52.558  2619  2619 D [Concierge]Service: Update widget ID : 11
08-26 21:53:52.560  2034  2034 D [Concierge]WidgetView: change position of spinner
08-26 21:53:52.560  2034  2034 I [Concierge]WidgetView: initWebView(). Time : 1472241232560
08-26 21:53:52.561  2619  2619 D [Concierge]Service: onStartCommand(). Type : 0
08-26 21:53:52.566  8244  8300 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-26 21:53:52.574  6917  6917 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-26 21:53:52.579  6917  6917 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-26 21:53:52.584  8244  8299 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
08-26 21:53:52.586  8314  8314 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 21:53:52.586  8314  8314 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 21:53:52.586  8314  8314 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-26 21:53:52.588  8244  8244 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 21:53:52.588  8244  8300 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-26 21:53:52.592  6917  6917 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 21:53:52.592  2034  2034 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 732314373
,08-26 21:53:52.593  2034  2034 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
08-26 21:53:52.593  2034  2034 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-26 21:53:52.596  2034  2034 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@3088c4da
08-26 21:53:52.596  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
08-26 21:53:52.597  2034  2034 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-26 21:53:52.597  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-26 21:53:52.601  6917  6917 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 21:53:52.602  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
08-26 21:53:52.602  2034  2034 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-26 21:53:52.602  2034  2034 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-26 21:53:52.603  2034  2034 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1472241114684, New one : 1472241232560
08-26 21:53:52.603  2034  2034 D [Concierge]WidgetView: Unregister all receivers
08-26 21:53:52.603  2034  2034 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-26 21:53:52.603  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-26 21:53:52.604  1034  1975 I ActivityManager: Killing 7352:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
08-26 21:53:52.605  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
08-26 21:53:52.606  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
08-26 21:53:52.607  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
08-26 21:53:52.607  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
08-26 21:53:52.608  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
,08-26 21:53:52.613  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-26 21:53:52.614  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-26 21:53:52.617  8244  8299 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
08-26 21:53:52.622  8244  8299 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
08-26 21:53:52.622  8244  8299 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
,08-26 21:53:52.622  8244  8299 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-26 21:53:52.623  8244  8299 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
08-26 21:53:52.623  8244  8299 I SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
08-26 21:53:52.625  8244  8299 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
08-26 21:53:52.626  8244  8299 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
,08-26 21:53:52.648  2034  2034 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-26 21:53:52.656  2034  2034 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
08-26 21:53:52.656  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
08-26 21:53:52.657  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-26 21:53:52.663  8314  8314 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 21:53:52.663  8314  8314 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 21:53:52.664  8314  8314 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-26 21:53:52.665  1034  1940 W libprocessgroup: failed to open /acct/uid_10005/pid_7352/cgroup.procs: No such file or directory
,08-26 21:53:52.668  8244  8244 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 21:53:52.668  8244  8300 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-26 21:53:52.672  6917  6917 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 21:53:52.678  2034  2034 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1f02b596 time:145446
08-26 21:53:52.681  6917  6917 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 21:53:52.684  8314  8314 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 21:53:52.684  8314  8314 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 21:53:52.685  8314  8314 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-26 21:53:52.698  8244  8300 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-26 21:53:52.698  8244  8244 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 21:53:52.705  6917  6917 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 21:53:52.712  6917  6917 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 21:53:52.717  8314  8314 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 21:53:52.717  8314  8314 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 21:53:52.720  8314  8314 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-26 21:53:52.722  8244  8244 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 21:53:52.740  6917  6917 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 21:53:52.745  6917  6917 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-26 21:53:52.748  8314  8314 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 21:53:52.748  8314  8314 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 21:53:52.749  8314  8314 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-26 21:53:52.750  8244  8244 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 21:53:52.752  8197  8197 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,08-26 21:53:52.754  8197  8197 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-26 21:53:52.756  6917  6917 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-26 21:53:52.759  6917  6917 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 21:53:52.763  8314  8314 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 21:53:52.763  8314  8314 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 21:53:52.764  8314  8314 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-26 21:53:52.764  8314  8314 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-26 21:53:52.765  8314  8314 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,08-26 21:53:52.772  8244  8244 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 21:53:52.774  8197  8197 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-26 21:53:52.775  8197  8197 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-26 21:53:52.777  6917  6917 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 21:53:52.780  6917  6917 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 21:53:52.783  8314  8314 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 21:53:52.783  8314  8314 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 21:53:52.783  8314  8314 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-26 21:53:52.784  8314  8314 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-26 21:53:52.784  8314  8314 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-26 21:53:52.786  8244  8244 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 21:53:52.787  8244  8244 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-26 21:53:52.789  1817  1817 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
08-26 21:53:52.794  2205  2205 I ConfigService: onCreate
08-26 21:53:52.794  2205  2205 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
,08-26 21:53:52.795  1817  1817 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
08-26 21:53:52.796  2205  8390 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/config.db'.
08-26 21:53:52.796  2205  8390 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 21:53:52.796  2205  8390 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 21:53:52.796  2205  8390 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
08-26 21:53:52.796  2205  8390 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
08-26 21:53:52.796  2205  8390 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-26 21:53:52.796  2205  8390 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-26 21:53:52.796  2205  8390 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-26 21:53:52.796  2205  8390 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
08-26 21:53:52.796  2205  8390 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
08-26 21:53:52.796  2205  8390 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
08-26 21:53:52.796  2205  8390 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
08-26 21:53:52.796  2205  8390 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-26 21:53:52.796  2205  8390 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 21:53:52.796  2205  8390 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-26 21:53:52.796  2205  8390 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:36)
08-26 21:53:52.796  2205  8390 E SQLiteDatabase: 	at com.google.android.gms.config.h.run(SourceFile:121)
08-26 21:53:52.796  2205  8390 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
08-26 21:53:52.796  2205  8390 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
08-26 21:53:52.796  2205  8390 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 21:53:52.796  2205  8390 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 21:53:52.796  2205  8390 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
08-26 21:53:52.796  2205  8390 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
08-26 21:53:52.796  2205  8390 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-26 21:53:52.796  2205  8390 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-26 21:53:52.796  2205  8390 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-26 21:53:52.796  2205  8390 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
08-26 21:53:52.796  2205  8390 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
08-26 21:53:52.796  2205  8390 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
08-26 21:53:52.796  2205  8390 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCr,eateDatabase(ContextImpl.java:1213)
08-26 21:53:52.796  2205  8390 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-26 21:53:52.796  2205  8390 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 21:53:52.796  2205  8390 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-26 21:53:52.796  2205  8390 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:36)
08-26 21:53:52.796  2205  8390 E SQLiteOpenHelper: 	at com.google.android.gms.config.h.run(SourceFile:121)
08-26 21:53:52.796  2205  8390 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
08-26 21:53:52.796  1817  3963 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.gms/shared_prefs/config_removals.xml to backup file /data/data/com.google.android.gms/shared_prefs/config_removals.xml.bak
08-26 21:53:52.797  2205  8390 W SQLiteOpenHelper: Opened config.db in read-only mode
08-26 21:53:52.798  2205  2205 I ConfigService: onBind returning update interface
08-26 21:53:52.799  2205  2205 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-26 21:53:52.799  2205  2205 I ConfigService: onBind returning config service
08-26 21:53:52.800  2205  2205 I ConfigService: onDestroy
08-26 21:53:52.804  1817  8391 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
08-26 21:53:52.807  2034  2034 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,08-26 21:53:52.811  7154  7154 E SQLiteLog: (3850) statement aborts at 24: [INSERT INTO exclude_apps(package) VALUES (?)] disk I/O error
08-26 21:53:52.812  1034  1537 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-26 21:53:52.812  7154  7154 E SQLiteDatabase: Error inserting package=com.test.thalitest
08-26 21:53:52.812  7154  7154 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-26 21:53:52.812  7154  7154 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
08-26 21:53:52.812  7154  7154 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:787)
08-26 21:53:52.812  7154  7154 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:926)
08-26 21:53:52.812  7154  7154 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
08-26 21:53:52.812  7154  7154 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1572)
08-26 21:53:52.812  7154  7154 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1442)
08-26 21:53:52.812  7154  7154 E SQLiteDatabase: 	at com.lge.appbox.databases.AppBoxContentProvider.insert(AppBoxContentProvider.java:220)
08-26 21:53:52.812  7154  7154 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:238)
08-26 21:53:52.812  7154  7154 E SQLiteDatabase: 	at android.content.ContentResolver.insert(ContentResolver.java:1223)
08-26 21:53:52.812  7154  7154 E SQLiteDatabase: 	at com.lge.appbox.manager.PreloadListManagerHelper.addExcludeApp(PreloadListManagerHelper.java:134)
08-26 21:53:52.812  7154  7154 E SQLiteDatabase: 	at com.lge.appbox.manager.PreloadListManagerHelper.addExcludeAppInternal(PreloadListManagerHelper.java:115)
08-26 21:53:52.812  7154  7154 E SQLiteDatabase: 	at com.lge.appbox.manager.PreloadListManagerHelper.onRemoveAppEvent(PreloadListManagerHelper.java:100)
08-26 21:53:52.812  7154  7154 E SQLiteDatabase: 	at com.lge.appbox.manager.PreloadListManagerHelper.updateExDb(PreloadListManagerHelper.java:65)
08-26 21:53:52.812  7154  7154 E SQLiteDatabase: 	at com.lge.appbox.manager.PreloadListManagerHelper.onReceive(PreloadListManagerHelper.java:46)
08-26 21:53:52.812  7154  7154 E SQLiteDatabase: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2586)
08-26 21:53:52.812  7154  7154 E SQLiteDatabase: 	at android.app.ActivityThread.access$1700(ActivityThread.java:148)
08-26 21:53:52.812  7154  7154 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1360)
08-26 21:53:52.812  7154  7154 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 21:53:52.812  7154  7154 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
08-26 21:53:52.812  7154  7154 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-26 21:53:52.812  7154  7154 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 21:53:52.812  7154  7154 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 21:53:52.812  7154  7154 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-26 21:53:52.812  7154  7154 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-26 21:53:52.813  1034  1537 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-26 21:53:52.813  1034  1537 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-26 21:53:52.813  1034  1537 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-26 21:53:52.813  1034  1537 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-26 21:53:52.814  1034  1537 E WifiStateMachine:  Defaul,tState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-26 21:53:52.815  1034  1543 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=true
08-26 21:53:52.815  1034  1543 D ConnectivityService: identical MTU - not setting
08-26 21:53:52.815  1034  1543 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-26 21:53:52.815  1034  1543 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-26 21:53:52.815  1034  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 21:53:52.815  1034  1543 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 21:53:52.815  1034  1543 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 21:53:52.816  1603  1827 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
08-26 21:53:52.826  5867  8398 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
,08-26 21:53:52.827  2352  8396 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
08-26 21:53:52.829  2352  2461 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
08-26 21:53:52.830  1817  8395 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
08-26 21:53:52.830  1817  8395 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 21:53:52.830  1817  8395 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 21:53:52.830  1817  8395 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
08-26 21:53:52.830  1817  8395 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
08-26 21:53:52.830  1817  8395 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-26 21:53:52.830  1817  8395 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-26 21:53:52.830  1817  8395 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-26 21:53:52.830  1817  8395 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
08-26 21:53:52.830  1817  8395 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
08-26 21:53:52.830  1817  8395 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
08-26 21:53:52.830  1817  8395 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
08-26 21:53:52.830  1817  8395 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-26 21:53:52.830  1817  8395 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 21:53:52.830  1817  8395 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-26 21:53:52.830  1817  8395 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.d.e.e(SourceFile:98)
08-26 21:53:52.830  1817  8395 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.d.e.a(SourceFile:212)
08-26 21:53:52.830  1817  8395 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:47)
08-26 21:53:52.830  1817  8395 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-26 21:53:52.830  1817  8395 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 21:53:52.830  1817  8395 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
08-26 21:53:52.830  1817  8395 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-26 21:53:52.830  1817  8395 E SQLiteOpenHelper: Couldn't open metrics.db for writing (will try read-only):
08-26 21:53:52.830  1817  8395 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 21:53:52.830  1817  8395 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 21:53:52.830  1817  8395 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
08-26 21:53:52.830  1817  8395 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
08-26 21:53:52.830  1817  8395 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-26 21:53:52.830  1817  8395 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-26 21:53:52.830  1817  8395 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteC,onnectionPool.java:177)
08-26 21:53:52.830  1817  8395 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
08-26 21:53:52.830  1817  8395 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
08-26 21:53:52.830  1817  8395 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
08-26 21:53:52.830  1817  8395 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
08-26 21:53:52.830  1817  8395 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-26 21:53:52.830  1817  8395 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 21:53:52.830  1817  8395 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-26 21:53:52.830  1817  8395 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.d.e.e(SourceFile:98)
08-26 21:53:52.830  1817  8395 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.d.e.a(SourceFile:212)
08-26 21:53:52.830  1817  8395 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:47)
08-26 21:53:52.830  1817  8395 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-26 21:53:52.830  1817  8395 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 21:53:52.830  1817  8395 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:135)
08-26 21:53:52.830  1817  8395 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-26 21:53:52.831  2352  2461 D ContactsProvider2ForLG: performBackgroundTask SQLiteDiskIOException during query
08-26 21:53:52.831  2352  2461 D ContactsProvider2ForLG: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-26 21:53:52.831  2352  2461 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-26 21:53:52.831  2352  2461 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:560)
08-26 21:53:52.831  2352  2461 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-26 21:53:52.831  2352  2461 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-26 21:53:52.831  2352  2461 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-26 21:53:52.831  2352  2461 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
08-26 21:53:52.831  2352  2461 D ContactsProvider2ForLG: 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:394)
08-26 21:53:52.831  2352  2461 D ContactsProvider2ForLG: 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:363)
08-26 21:53:52.831  2352  2461 D ContactsProvider2ForLG: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:974)
08-26 21:53:52.831  2352  2461 D ContactsProvider2ForLG: 	at com.android.providers.contacts.ContactsProvider2ForLG.performBackgroundTask(ContactsProvider2ForLG.java:375)
08-26 21:53:52.831  2352  2461 D ContactsProvider2ForLG: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:748)
08-26 21:53:52.831  2352  2461 D ContactsProvider2ForLG: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 21:53:52.831  2352  2461 D ContactsProvider2ForLG: 	at android.os.Looper.loop(Looper.java:135)
08-26 21:53:52.831  2352  2461 D ContactsProvider2ForLG: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-26 21:53:52.832  1817  8395 W SQLiteOpenHelper: Op,ened metrics.db in read-only mode
08-26 21:53:52.833  1817  8395 E SQLiteLog: (8) statement aborts at 16: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
--------- beginning of crash
08-26 21:53:52.833  1817  8395 E AndroidRuntime: FATAL EXCEPTION: IntentService[ClearHelpHistoryIntentService]
08-26 21:53:52.833  1817  8395 E AndroidRuntime: Process: com.google.android.gms, PID: 1817
08-26 21:53:52.833  1817  8395 E AndroidRuntime: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
08-26 21:53:52.833  1817  8395 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-26 21:53:52.833  1817  8395 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:739)
08-26 21:53:52.833  1817  8395 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:892)
08-26 21:53:52.833  1817  8395 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-26 21:53:52.833  1817  8395 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1600)
08-26 21:53:52.833  1817  8395 E AndroidRuntime: 	at com.google.android.gms.googlehelp.d.e.a(SourceFile:215)
08-26 21:53:52.833  1817  8395 E AndroidRuntime: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:47)
08-26 21:53:52.833  1817  8395 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-26 21:53:52.833  1817  8395 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 21:53:52.833  1817  8395 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
08-26 21:53:52.833  1817  8395 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-26 21:53:52.835  2352  8396 E SQLiteLog: (3850) statement aborts at 37: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
08-26 21:53:52.835  2352  8396 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-26 21:53:52.835  2352  8396 E AndroidRuntime: Process: android.process.acore, PID: 2352
08-26 21:53:52.835  2352  8396 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-26 21:53:52.835  2352  8396 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-26 21:53:52.835  2352  8396 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:739)
08-26 21:53:52.835  2352  8396 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:892)
08-26 21:53:52.835  2352  8396 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-26 21:53:52.835  2352  8396 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1600)
08-26 21:53:52.835  2352  8396 E AndroidRuntime: 	at com.android.providers.contacts.util.DbModifierWithNotification.delete(DbModifierWithNotification.java:161)
08-26 21:53:52.835  2352  8396 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailContentTable.delete(VoicemailContentTable.java:229)
08-26 21:53:52.835  2352  8396 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailContentProvider.delete(VoicemailContentProvider.java:135)
08-26 21:53:52.835  2352  8396 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
08-26 21:53:52.835  2352  8396 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1315)
08-26 21:53:52.835  2352  8396 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-26 21:53:52.835  2352  8396 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-26 21:53:52.835  2352  8396 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-26 21:53:52.835  2352  8396 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 21:53:52.835  2352  8396 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
08-26 21:53:52.835  2352  8396 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-26 21:53:52.850  2034  2927 I GBoardtInterface: onReloaded()
08-26 21:53:52.852  1034  1995 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8399 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
08-26 21:53:52.853  2034  2034 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
08-26 21:53:52.856  1817  8408 I PeopleContactsSync: CP2 sync disabled
08-26 21:53:52.857  3770  3785 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-26 21:53:52.861  1817  5197 I Icing   : doRemovePackageData com.test.thalitest

```
